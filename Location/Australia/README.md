Linux in Australia - Tested Hardware & Statistics
-------------------------------------------------

A project to collect tested hardware configurations for Linux in Australia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Australia/Desktop/README.md) and [notebooks](/Location/Australia/Notebook/README.md).

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

Total: 5720

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Apple         | MacBookPro14,3              | Notebook    | [ec90ed2076](https://linux-hardware.org/?probe=ec90ed2076) | Oct 01, 2023 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [def4633785](https://linux-hardware.org/?probe=def4633785) | Oct 01, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c99f28b27d](https://linux-hardware.org/?probe=c99f28b27d) | Oct 01, 2023 |
| Gigabyte      | D525TUD                     | Desktop     | [913e98318d](https://linux-hardware.org/?probe=913e98318d) | Oct 01, 2023 |
| Gigabyte      | D525TUD                     | Desktop     | [f48a538837](https://linux-hardware.org/?probe=f48a538837) | Oct 01, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [288f5f8266](https://linux-hardware.org/?probe=288f5f8266) | Sep 30, 2023 |
| Metabox       | Prime-X X170KM              | Notebook    | [8ab33a8bd3](https://linux-hardware.org/?probe=8ab33a8bd3) | Sep 30, 2023 |
| Fanless Mi... | Rev GMLR1                   | Mini pc     | [751b4d268a](https://linux-hardware.org/?probe=751b4d268a) | Sep 30, 2023 |
| Gigabyte      | X99-UD3-CF                  | Desktop     | [f1cc7e5a93](https://linux-hardware.org/?probe=f1cc7e5a93) | Sep 30, 2023 |
| Gigabyte      | X99-UD3-CF                  | Desktop     | [51d10770c6](https://linux-hardware.org/?probe=51d10770c6) | Sep 30, 2023 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [5a507ec4da](https://linux-hardware.org/?probe=5a507ec4da) | Sep 30, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [c69ab4bc0f](https://linux-hardware.org/?probe=c69ab4bc0f) | Sep 30, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [4a7b1ee936](https://linux-hardware.org/?probe=4a7b1ee936) | Sep 29, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [c25eeffab1](https://linux-hardware.org/?probe=c25eeffab1) | Sep 28, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [001231c730](https://linux-hardware.org/?probe=001231c730) | Sep 28, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [b0c2b630a6](https://linux-hardware.org/?probe=b0c2b630a6) | Sep 28, 2023 |
| Apple         | MacBookPro15,2              | Notebook    | [1331a57778](https://linux-hardware.org/?probe=1331a57778) | Sep 27, 2023 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [4f0651ccc2](https://linux-hardware.org/?probe=4f0651ccc2) | Sep 27, 2023 |
| HP            | EliteBook x360 1020 G2      | Convertible | [7b6ee612cf](https://linux-hardware.org/?probe=7b6ee612cf) | Sep 27, 2023 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [a4d1820df5](https://linux-hardware.org/?probe=a4d1820df5) | Sep 27, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | Notebook    | [fed9f17a22](https://linux-hardware.org/?probe=fed9f17a22) | Sep 27, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | Notebook    | [0dd1b47aa0](https://linux-hardware.org/?probe=0dd1b47aa0) | Sep 27, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [c60600b4f0](https://linux-hardware.org/?probe=c60600b4f0) | Sep 27, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [78d31814cf](https://linux-hardware.org/?probe=78d31814cf) | Sep 26, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [0d7d5f0613](https://linux-hardware.org/?probe=0d7d5f0613) | Sep 26, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [5bf8234727](https://linux-hardware.org/?probe=5bf8234727) | Sep 25, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [55dec782e7](https://linux-hardware.org/?probe=55dec782e7) | Sep 25, 2023 |
| Acer          | Aspire E5-571               | Notebook    | [c834abf6b2](https://linux-hardware.org/?probe=c834abf6b2) | Sep 25, 2023 |
| Acer          | Aspire R3-131T              | Notebook    | [bf8f7a55ae](https://linux-hardware.org/?probe=bf8f7a55ae) | Sep 24, 2023 |
| Acer          | Aspire R3-131T              | Notebook    | [a426f4a94e](https://linux-hardware.org/?probe=a426f4a94e) | Sep 24, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [25c109d366](https://linux-hardware.org/?probe=25c109d366) | Sep 24, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | Desktop     | [3346cccd71](https://linux-hardware.org/?probe=3346cccd71) | Sep 24, 2023 |
| Dell          | Inspiron 14 5420            | Notebook    | [ade3d11822](https://linux-hardware.org/?probe=ade3d11822) | Sep 24, 2023 |
| HP            | 843B                        | Desktop     | [4e11e8ae1a](https://linux-hardware.org/?probe=4e11e8ae1a) | Sep 24, 2023 |
| COM1          | NBINF-X5-9G5                | Notebook    | [919d36ddd8](https://linux-hardware.org/?probe=919d36ddd8) | Sep 24, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [086b0dc21a](https://linux-hardware.org/?probe=086b0dc21a) | Sep 23, 2023 |
| HP            | 1905                        | Desktop     | [786257c0e1](https://linux-hardware.org/?probe=786257c0e1) | Sep 23, 2023 |
| Panasonic     | FZG1-4                      | Notebook    | [bb4677655e](https://linux-hardware.org/?probe=bb4677655e) | Sep 23, 2023 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [2867e39109](https://linux-hardware.org/?probe=2867e39109) | Sep 23, 2023 |
| HP            | 3397                        | Desktop     | [fa230ba389](https://linux-hardware.org/?probe=fa230ba389) | Sep 23, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [ce0f2babca](https://linux-hardware.org/?probe=ce0f2babca) | Sep 22, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [8b1188ba33](https://linux-hardware.org/?probe=8b1188ba33) | Sep 22, 2023 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [e57a830f9c](https://linux-hardware.org/?probe=e57a830f9c) | Sep 21, 2023 |
| Dell          | Precision 5680              | Notebook    | [55deb46665](https://linux-hardware.org/?probe=55deb46665) | Sep 21, 2023 |
| HP            | Pavilion dv7                | Notebook    | [a879a0a88f](https://linux-hardware.org/?probe=a879a0a88f) | Sep 21, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [3762f344e9](https://linux-hardware.org/?probe=3762f344e9) | Sep 21, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [c5e9108ee7](https://linux-hardware.org/?probe=c5e9108ee7) | Sep 20, 2023 |
| Dell          | 03NVJ6 A00                  | Desktop     | [af48b03e82](https://linux-hardware.org/?probe=af48b03e82) | Sep 20, 2023 |
| Dell          | Precision 5560              | Notebook    | [456e9e2c78](https://linux-hardware.org/?probe=456e9e2c78) | Sep 20, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [624ebbd6c1](https://linux-hardware.org/?probe=624ebbd6c1) | Sep 20, 2023 |
| Dell          | Precision 5680              | Notebook    | [a75a75f080](https://linux-hardware.org/?probe=a75a75f080) | Sep 20, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [7a6c8c1d0a](https://linux-hardware.org/?probe=7a6c8c1d0a) | Sep 20, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [6f7974b0f0](https://linux-hardware.org/?probe=6f7974b0f0) | Sep 20, 2023 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [01e90212e5](https://linux-hardware.org/?probe=01e90212e5) | Sep 20, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [71d11373aa](https://linux-hardware.org/?probe=71d11373aa) | Sep 20, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [5e50efa2c4](https://linux-hardware.org/?probe=5e50efa2c4) | Sep 19, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [1bd6653d3e](https://linux-hardware.org/?probe=1bd6653d3e) | Sep 19, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [eeeb11e211](https://linux-hardware.org/?probe=eeeb11e211) | Sep 19, 2023 |
| Sony          | SVE15137CGW                 | Notebook    | [b454be55a2](https://linux-hardware.org/?probe=b454be55a2) | Sep 19, 2023 |
| Framework     | Laptop                      | Notebook    | [f379873c4b](https://linux-hardware.org/?probe=f379873c4b) | Sep 19, 2023 |
| Lenovo        | ThinkCentre M58p 7220A72    | Desktop     | [39d6e8a728](https://linux-hardware.org/?probe=39d6e8a728) | Sep 18, 2023 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [7e05f3299f](https://linux-hardware.org/?probe=7e05f3299f) | Sep 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [82e9cc2c9a](https://linux-hardware.org/?probe=82e9cc2c9a) | Sep 18, 2023 |
| HP            | EliteBook 745 G2            | Notebook    | [7e5ee5a990](https://linux-hardware.org/?probe=7e5ee5a990) | Sep 18, 2023 |
| Dell          | Latitude 7490               | Notebook    | [91a3ecf449](https://linux-hardware.org/?probe=91a3ecf449) | Sep 18, 2023 |
| HP            | 8158 A01                    | Mini pc     | [bd8aa3d09c](https://linux-hardware.org/?probe=bd8aa3d09c) | Sep 18, 2023 |
| HP            | 1998                        | Desktop     | [4af6b915c2](https://linux-hardware.org/?probe=4af6b915c2) | Sep 17, 2023 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [ab8cb379a8](https://linux-hardware.org/?probe=ab8cb379a8) | Sep 17, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [42bb973998](https://linux-hardware.org/?probe=42bb973998) | Sep 16, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [d5c797d43b](https://linux-hardware.org/?probe=d5c797d43b) | Sep 16, 2023 |
| Dell          | 0Y56T3 A01                  | Desktop     | [0ecd730eca](https://linux-hardware.org/?probe=0ecd730eca) | Sep 16, 2023 |
| Lenovo        | ThinkPad X380 Yoga 20LHS... | Convertible | [e18d005071](https://linux-hardware.org/?probe=e18d005071) | Sep 16, 2023 |
| Dell          | Inspiron M5010              | Notebook    | [c78ab23cc7](https://linux-hardware.org/?probe=c78ab23cc7) | Sep 16, 2023 |
| Lenovo        | ThinkCentre M58 7360BB6     | Desktop     | [cb32849dcc](https://linux-hardware.org/?probe=cb32849dcc) | Sep 16, 2023 |
| Dell          | 0TDG4V A01                  | Desktop     | [7c2d7aeafa](https://linux-hardware.org/?probe=7c2d7aeafa) | Sep 15, 2023 |
| ASUSTek       | PN50-E1                     | Mini pc     | [f76358580b](https://linux-hardware.org/?probe=f76358580b) | Sep 15, 2023 |
| COM1          | NBINF-X5-9G5                | Notebook    | [aca0ed1105](https://linux-hardware.org/?probe=aca0ed1105) | Sep 15, 2023 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [e9d6d94486](https://linux-hardware.org/?probe=e9d6d94486) | Sep 15, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [dd637b6425](https://linux-hardware.org/?probe=dd637b6425) | Sep 15, 2023 |
| Dell          | 0TDG4V A01                  | Desktop     | [7d79af3d22](https://linux-hardware.org/?probe=7d79af3d22) | Sep 13, 2023 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [20ec05f55b](https://linux-hardware.org/?probe=20ec05f55b) | Sep 13, 2023 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [172b7a1d48](https://linux-hardware.org/?probe=172b7a1d48) | Sep 13, 2023 |
| Dell          | XPS L322X                   | Notebook    | [77135f7967](https://linux-hardware.org/?probe=77135f7967) | Sep 11, 2023 |
| Dell          | Inspiron M5010              | Notebook    | [70147b0015](https://linux-hardware.org/?probe=70147b0015) | Sep 11, 2023 |
| ASRock        | B360M-HDV                   | Desktop     | [d4b0ae4d0c](https://linux-hardware.org/?probe=d4b0ae4d0c) | Sep 11, 2023 |
| Dell          | XPS L322X                   | Notebook    | [fdf4ba47e1](https://linux-hardware.org/?probe=fdf4ba47e1) | Sep 11, 2023 |
| Dell          | 0GM819                      | Desktop     | [f7d8bdb2a3](https://linux-hardware.org/?probe=f7d8bdb2a3) | Sep 10, 2023 |
| ASRock        | H97M Pro4                   | Desktop     | [a875b11982](https://linux-hardware.org/?probe=a875b11982) | Sep 10, 2023 |
| MSI           | MAG B550M MORTAR MAX WIF... | Desktop     | [5cb0ed682a](https://linux-hardware.org/?probe=5cb0ed682a) | Sep 10, 2023 |
| Pegatron      | 2AB6                        | Desktop     | [5b2fda7ad6](https://linux-hardware.org/?probe=5b2fda7ad6) | Sep 09, 2023 |
| Intel         | NUC11PABi5 K90634-302       | Mini pc     | [0e97d18f32](https://linux-hardware.org/?probe=0e97d18f32) | Sep 09, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [7b02c70750](https://linux-hardware.org/?probe=7b02c70750) | Sep 09, 2023 |
| Gigabyte      | Q87M-MK                     | Desktop     | [1c45c834fe](https://linux-hardware.org/?probe=1c45c834fe) | Sep 09, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [0940dc7ebd](https://linux-hardware.org/?probe=0940dc7ebd) | Sep 08, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [fac3b5ba62](https://linux-hardware.org/?probe=fac3b5ba62) | Sep 08, 2023 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [6bea6e300b](https://linux-hardware.org/?probe=6bea6e300b) | Sep 07, 2023 |
| Dell          | 0J37VM A01                  | Desktop     | [7781be38be](https://linux-hardware.org/?probe=7781be38be) | Sep 07, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | Notebook    | [da7303433d](https://linux-hardware.org/?probe=da7303433d) | Sep 07, 2023 |
| Gigabyte      | Z87X-UD3H-CF                | Desktop     | [43f205483a](https://linux-hardware.org/?probe=43f205483a) | Sep 07, 2023 |
| Valve         | Jupiter                     | Notebook    | [d4ca58e970](https://linux-hardware.org/?probe=d4ca58e970) | Sep 07, 2023 |
| Intel         | NUC8BEB J72692-306          | Mini pc     | [6cbfa96139](https://linux-hardware.org/?probe=6cbfa96139) | Sep 07, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [f0c3188082](https://linux-hardware.org/?probe=f0c3188082) | Sep 07, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [2285c5c493](https://linux-hardware.org/?probe=2285c5c493) | Sep 06, 2023 |
| Dell          | 0PC5F7 A00                  | Desktop     | [9ffb575d81](https://linux-hardware.org/?probe=9ffb575d81) | Sep 06, 2023 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | Desktop     | [c43f7a6e53](https://linux-hardware.org/?probe=c43f7a6e53) | Sep 06, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [f421de992d](https://linux-hardware.org/?probe=f421de992d) | Sep 06, 2023 |
| ASRock        | B650E PG-ITX WiFi           | Desktop     | [9dd5c2a861](https://linux-hardware.org/?probe=9dd5c2a861) | Sep 06, 2023 |
| Acer          | Aspire Z3-615               | All in one  | [10bb2b77f8](https://linux-hardware.org/?probe=10bb2b77f8) | Sep 06, 2023 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [7db6779b5c](https://linux-hardware.org/?probe=7db6779b5c) | Sep 06, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [424ab4dc3d](https://linux-hardware.org/?probe=424ab4dc3d) | Sep 05, 2023 |
| Dell          | Latitude 7280               | Notebook    | [3cf6ec76b5](https://linux-hardware.org/?probe=3cf6ec76b5) | Sep 05, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [51b40f3137](https://linux-hardware.org/?probe=51b40f3137) | Sep 05, 2023 |
| ASRock        | AD525PV3                    | Desktop     | [0fa982f7ad](https://linux-hardware.org/?probe=0fa982f7ad) | Sep 05, 2023 |
| ASRock        | AD525PV3                    | Desktop     | [9ab25d4913](https://linux-hardware.org/?probe=9ab25d4913) | Sep 05, 2023 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [d20cf2e835](https://linux-hardware.org/?probe=d20cf2e835) | Sep 05, 2023 |
| Gigabyte      | Z590 AORUS MASTER           | Desktop     | [40785211e9](https://linux-hardware.org/?probe=40785211e9) | Sep 05, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [318d03cfad](https://linux-hardware.org/?probe=318d03cfad) | Sep 04, 2023 |
| Intel         | NUC12WSBi5 M46425-302       | Mini pc     | [362e60bccc](https://linux-hardware.org/?probe=362e60bccc) | Sep 04, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [ae41ba8b62](https://linux-hardware.org/?probe=ae41ba8b62) | Sep 04, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [6cbaac077e](https://linux-hardware.org/?probe=6cbaac077e) | Sep 03, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [16b96480a2](https://linux-hardware.org/?probe=16b96480a2) | Sep 03, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [bf3a5838f0](https://linux-hardware.org/?probe=bf3a5838f0) | Sep 02, 2023 |
| Dell          | Latitude E6520              | Notebook    | [b53cd78958](https://linux-hardware.org/?probe=b53cd78958) | Sep 02, 2023 |
| Dell          | G15 5520                    | Notebook    | [796ae7cf79](https://linux-hardware.org/?probe=796ae7cf79) | Sep 02, 2023 |
| ASUSTek       | ROG Maximus XII EXTREME     | Desktop     | [7cfd1c36d1](https://linux-hardware.org/?probe=7cfd1c36d1) | Sep 02, 2023 |
| Intel         | NUC11PABi7 M68262-501       | Mini pc     | [59677d7116](https://linux-hardware.org/?probe=59677d7116) | Sep 02, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [da8d60051c](https://linux-hardware.org/?probe=da8d60051c) | Sep 02, 2023 |
| ASUSTek       | K53SD                       | Notebook    | [9a208331c5](https://linux-hardware.org/?probe=9a208331c5) | Sep 01, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [f3c99a0cc5](https://linux-hardware.org/?probe=f3c99a0cc5) | Sep 01, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [17e3dd86e8](https://linux-hardware.org/?probe=17e3dd86e8) | Sep 01, 2023 |
| Dell          | Latitude E7470              | Notebook    | [0580f1c293](https://linux-hardware.org/?probe=0580f1c293) | Sep 01, 2023 |
| HP            | EliteBook Folio 1040 G1     | Notebook    | [1c496aba4a](https://linux-hardware.org/?probe=1c496aba4a) | Sep 01, 2023 |
| Lenovo        | Legion Slim 7 16IRH8 82Y... | Notebook    | [ab14d9d9bb](https://linux-hardware.org/?probe=ab14d9d9bb) | Aug 31, 2023 |
| Dell          | Latitude 7340               | Notebook    | [d6d1df94f5](https://linux-hardware.org/?probe=d6d1df94f5) | Aug 31, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [a99931801d](https://linux-hardware.org/?probe=a99931801d) | Aug 31, 2023 |
| HP            | ENVY m6                     | Notebook    | [eea19d891e](https://linux-hardware.org/?probe=eea19d891e) | Aug 31, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [84ed05802d](https://linux-hardware.org/?probe=84ed05802d) | Aug 31, 2023 |
| Gigabyte      | D525TUD                     | Desktop     | [9a459d2372](https://linux-hardware.org/?probe=9a459d2372) | Aug 31, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [ffb1e72844](https://linux-hardware.org/?probe=ffb1e72844) | Aug 31, 2023 |
| Dell          | Latitude 7390               | Notebook    | [3aaefe5b81](https://linux-hardware.org/?probe=3aaefe5b81) | Aug 31, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [7741e9850b](https://linux-hardware.org/?probe=7741e9850b) | Aug 31, 2023 |
| Microsoft     | Surface Go 3                | Tablet      | [4f320554b6](https://linux-hardware.org/?probe=4f320554b6) | Aug 31, 2023 |
| HP            | 843B                        | Desktop     | [472228092a](https://linux-hardware.org/?probe=472228092a) | Aug 31, 2023 |
| Dell          | 0Y5DDC A00                  | Desktop     | [21ec7587ed](https://linux-hardware.org/?probe=21ec7587ed) | Aug 30, 2023 |
| Apple         | MacBookPro15,2              | Notebook    | [a93751de6d](https://linux-hardware.org/?probe=a93751de6d) | Aug 30, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [9782f69f43](https://linux-hardware.org/?probe=9782f69f43) | Aug 30, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [1964cb4738](https://linux-hardware.org/?probe=1964cb4738) | Aug 30, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [7176f2933c](https://linux-hardware.org/?probe=7176f2933c) | Aug 30, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [ea2ba90391](https://linux-hardware.org/?probe=ea2ba90391) | Aug 30, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [13b77d8273](https://linux-hardware.org/?probe=13b77d8273) | Aug 30, 2023 |
| Acer          | Aspire E1-572               | Notebook    | [77cdb6f4a4](https://linux-hardware.org/?probe=77cdb6f4a4) | Aug 30, 2023 |
| ASUSTek       | P552LA                      | Notebook    | [6eca0a231c](https://linux-hardware.org/?probe=6eca0a231c) | Aug 30, 2023 |
| Dell          | Latitude 3350               | Notebook    | [4fa556a69f](https://linux-hardware.org/?probe=4fa556a69f) | Aug 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [dc4910965c](https://linux-hardware.org/?probe=dc4910965c) | Aug 29, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [a2f594cf56](https://linux-hardware.org/?probe=a2f594cf56) | Aug 29, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [43db739186](https://linux-hardware.org/?probe=43db739186) | Aug 29, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [4cdf174574](https://linux-hardware.org/?probe=4cdf174574) | Aug 29, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [4c46f7ae80](https://linux-hardware.org/?probe=4c46f7ae80) | Aug 28, 2023 |
| Intel         | NUC11PABi7 K90104-302       | Mini pc     | [ee8ee6bf06](https://linux-hardware.org/?probe=ee8ee6bf06) | Aug 28, 2023 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [ed544a4405](https://linux-hardware.org/?probe=ed544a4405) | Aug 28, 2023 |
| Lenovo        | Yoga 310-11IAP 80U2         | Convertible | [5cd969711d](https://linux-hardware.org/?probe=5cd969711d) | Aug 28, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [714c46e2fd](https://linux-hardware.org/?probe=714c46e2fd) | Aug 28, 2023 |
| Dell          | Latitude 14 Rugged (5404... | Notebook    | [c96c172d03](https://linux-hardware.org/?probe=c96c172d03) | Aug 27, 2023 |
| Dell          | 03NVJ6 A01                  | Desktop     | [00a28522c2](https://linux-hardware.org/?probe=00a28522c2) | Aug 27, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [883d4fbfeb](https://linux-hardware.org/?probe=883d4fbfeb) | Aug 27, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [d80e4744e9](https://linux-hardware.org/?probe=d80e4744e9) | Aug 27, 2023 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [ea6d90ba09](https://linux-hardware.org/?probe=ea6d90ba09) | Aug 27, 2023 |
| HP            | Compaq 6710b (GE822PA#AB... | Notebook    | [134d0685ff](https://linux-hardware.org/?probe=134d0685ff) | Aug 26, 2023 |
| Gigabyte      | H97N-WIFI                   | Desktop     | [6edcb45992](https://linux-hardware.org/?probe=6edcb45992) | Aug 26, 2023 |
| ASUSTek       | P5K-E                       | Desktop     | [aa48da4e34](https://linux-hardware.org/?probe=aa48da4e34) | Aug 26, 2023 |
| HP            | ProLiant ML10 v2            | Desktop     | [86cb962a7d](https://linux-hardware.org/?probe=86cb962a7d) | Aug 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [e78b6b1077](https://linux-hardware.org/?probe=e78b6b1077) | Aug 26, 2023 |
| Acer          | Predator G9-793             | Notebook    | [531f857477](https://linux-hardware.org/?probe=531f857477) | Aug 26, 2023 |
| HP            | ProBook 450 15.6 inch G1... | Notebook    | [973d7867a4](https://linux-hardware.org/?probe=973d7867a4) | Aug 26, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [fc8e4dd4ff](https://linux-hardware.org/?probe=fc8e4dd4ff) | Aug 25, 2023 |
| Gigabyte      | Z68MX-UD2H-B3               | Desktop     | [93cce7551b](https://linux-hardware.org/?probe=93cce7551b) | Aug 25, 2023 |
| Dell          | 02C2CP A06                  | Server      | [dad6e7b74c](https://linux-hardware.org/?probe=dad6e7b74c) | Aug 25, 2023 |
| Dell          | XPS 17 9700                 | Notebook    | [93fec269da](https://linux-hardware.org/?probe=93fec269da) | Aug 25, 2023 |
| Gigabyte      | X79-UP4                     | Desktop     | [58ae6791f0](https://linux-hardware.org/?probe=58ae6791f0) | Aug 25, 2023 |
| Dell          | Vostro 2520                 | Notebook    | [96018ae096](https://linux-hardware.org/?probe=96018ae096) | Aug 24, 2023 |
| Dell          | 06D7TR A02                  | Desktop     | [d0b04a9056](https://linux-hardware.org/?probe=d0b04a9056) | Aug 24, 2023 |
| AZW           | SER                         | Mini pc     | [309bc27af7](https://linux-hardware.org/?probe=309bc27af7) | Aug 24, 2023 |
| Lenovo        | ThinkPad R61 7732NDG        | Notebook    | [b0d510a7ad](https://linux-hardware.org/?probe=b0d510a7ad) | Aug 24, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [a06cf8de37](https://linux-hardware.org/?probe=a06cf8de37) | Aug 24, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [b6591e9fd9](https://linux-hardware.org/?probe=b6591e9fd9) | Aug 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [5a6247f9b2](https://linux-hardware.org/?probe=5a6247f9b2) | Aug 24, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [a1bdeba9c8](https://linux-hardware.org/?probe=a1bdeba9c8) | Aug 23, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [c5484868fd](https://linux-hardware.org/?probe=c5484868fd) | Aug 23, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [68d3bc88e4](https://linux-hardware.org/?probe=68d3bc88e4) | Aug 23, 2023 |
| Gigabyte      | GA-A55M-S2V                 | Desktop     | [e9b32aa827](https://linux-hardware.org/?probe=e9b32aa827) | Aug 23, 2023 |
| HP            | Pavilion dv6                | Notebook    | [38fbd02f14](https://linux-hardware.org/?probe=38fbd02f14) | Aug 23, 2023 |
| HP            | 212B                        | Desktop     | [a186c2ccf3](https://linux-hardware.org/?probe=a186c2ccf3) | Aug 23, 2023 |
| Fujitsu       | S6420                       | Notebook    | [044d4185b7](https://linux-hardware.org/?probe=044d4185b7) | Aug 22, 2023 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [b40144bd93](https://linux-hardware.org/?probe=b40144bd93) | Aug 22, 2023 |
| Microsoft     | Surface Go 3                | Tablet      | [17d3cd9a3c](https://linux-hardware.org/?probe=17d3cd9a3c) | Aug 22, 2023 |
| ASUSTek       | P7P55-M                     | Desktop     | [0f5028d5fc](https://linux-hardware.org/?probe=0f5028d5fc) | Aug 22, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [a8a1e5df49](https://linux-hardware.org/?probe=a8a1e5df49) | Aug 21, 2023 |
| Kogan         | KAL14N360PA                 | Notebook    | [527a0d3cba](https://linux-hardware.org/?probe=527a0d3cba) | Aug 20, 2023 |
| Kogan         | KAL14N360PA                 | Notebook    | [b7cecb1518](https://linux-hardware.org/?probe=b7cecb1518) | Aug 20, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [158cc5fe6f](https://linux-hardware.org/?probe=158cc5fe6f) | Aug 20, 2023 |
| HP            | 158A                        | Desktop     | [ba0211611f](https://linux-hardware.org/?probe=ba0211611f) | Aug 19, 2023 |
| HP            | 158A                        | Desktop     | [25e8725a35](https://linux-hardware.org/?probe=25e8725a35) | Aug 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [c642878288](https://linux-hardware.org/?probe=c642878288) | Aug 19, 2023 |
| Lenovo        | Yoga 7 14IAL7 82QE          | Convertible | [dc5d42e6cb](https://linux-hardware.org/?probe=dc5d42e6cb) | Aug 19, 2023 |
| Intel         | NUC8BEB J72692-306          | Mini pc     | [6a155984af](https://linux-hardware.org/?probe=6a155984af) | Aug 19, 2023 |
| Lenovo        | Yoga Pro 9 14IRP8 83BU      | Notebook    | [b42f885e14](https://linux-hardware.org/?probe=b42f885e14) | Aug 18, 2023 |
| Toshiba       | Satellite L550              | Notebook    | [4c331017e2](https://linux-hardware.org/?probe=4c331017e2) | Aug 18, 2023 |
| Acer          | Aspire 5755G                | Notebook    | [720c3bfa88](https://linux-hardware.org/?probe=720c3bfa88) | Aug 18, 2023 |
| Intel         | D53427RKE G87971-402        | Desktop     | [433dcaffa6](https://linux-hardware.org/?probe=433dcaffa6) | Aug 17, 2023 |
| Acer          | Aspire E5-571               | Notebook    | [8a924c30e6](https://linux-hardware.org/?probe=8a924c30e6) | Aug 17, 2023 |
| MSI           | MAG Z390 TOMAHAWK           | Desktop     | [1d389611a3](https://linux-hardware.org/?probe=1d389611a3) | Aug 16, 2023 |
| HP            | Elite Dragonfly             | Convertible | [7419fe990e](https://linux-hardware.org/?probe=7419fe990e) | Aug 16, 2023 |
| Dell          | Latitude 7210 2-in-1        | Tablet      | [59b0f15b1d](https://linux-hardware.org/?probe=59b0f15b1d) | Aug 16, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO II     | Desktop     | [122b800eae](https://linux-hardware.org/?probe=122b800eae) | Aug 16, 2023 |
| MSI           | GS60 6QE                    | Notebook    | [3372d46d8c](https://linux-hardware.org/?probe=3372d46d8c) | Aug 16, 2023 |
| Google        | Phaser360                   | Notebook    | [3c248cc2c8](https://linux-hardware.org/?probe=3c248cc2c8) | Aug 16, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [881b50cb6f](https://linux-hardware.org/?probe=881b50cb6f) | Aug 16, 2023 |
| Dell          | Precision 5520              | Notebook    | [0516c33229](https://linux-hardware.org/?probe=0516c33229) | Aug 16, 2023 |
| Dell          | Precision 5520              | Notebook    | [b9a35fa791](https://linux-hardware.org/?probe=b9a35fa791) | Aug 16, 2023 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | Notebook    | [6242833326](https://linux-hardware.org/?probe=6242833326) | Aug 15, 2023 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | Notebook    | [22252eb1d9](https://linux-hardware.org/?probe=22252eb1d9) | Aug 15, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [290298fd99](https://linux-hardware.org/?probe=290298fd99) | Aug 15, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [bf2f7b52d1](https://linux-hardware.org/?probe=bf2f7b52d1) | Aug 15, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [7b94897e1a](https://linux-hardware.org/?probe=7b94897e1a) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [b62ff7f358](https://linux-hardware.org/?probe=b62ff7f358) | Aug 14, 2023 |
| HP            | Notebook                    | Notebook    | [f32b596c87](https://linux-hardware.org/?probe=f32b596c87) | Aug 14, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [fd93a82029](https://linux-hardware.org/?probe=fd93a82029) | Aug 14, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [b950177908](https://linux-hardware.org/?probe=b950177908) | Aug 14, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [dc696b572c](https://linux-hardware.org/?probe=dc696b572c) | Aug 14, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [d2ccdc066b](https://linux-hardware.org/?probe=d2ccdc066b) | Aug 14, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [11b8c16b30](https://linux-hardware.org/?probe=11b8c16b30) | Aug 14, 2023 |
| Gigabyte      | Z77M-D3H-MVP                | Desktop     | [c939a92f1d](https://linux-hardware.org/?probe=c939a92f1d) | Aug 14, 2023 |
| Apple         | Mac-F223BEC8                | Desktop     | [74a3be9a4a](https://linux-hardware.org/?probe=74a3be9a4a) | Aug 14, 2023 |
| Gigabyte      | Z77M-D3H-MVP                | Desktop     | [56efab026f](https://linux-hardware.org/?probe=56efab026f) | Aug 14, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | Desktop     | [9a8e4bc08d](https://linux-hardware.org/?probe=9a8e4bc08d) | Aug 14, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [5d7e68e3ae](https://linux-hardware.org/?probe=5d7e68e3ae) | Aug 14, 2023 |
| Dell          | Latitude E7470              | Notebook    | [99518b81f7](https://linux-hardware.org/?probe=99518b81f7) | Aug 13, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [6602bb3d0a](https://linux-hardware.org/?probe=6602bb3d0a) | Aug 13, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [5a809fe1c3](https://linux-hardware.org/?probe=5a809fe1c3) | Aug 13, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [1de4045fb5](https://linux-hardware.org/?probe=1de4045fb5) | Aug 13, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [3ac1be3b93](https://linux-hardware.org/?probe=3ac1be3b93) | Aug 13, 2023 |
| HP            | ProBook 6450b               | Notebook    | [8862a40143](https://linux-hardware.org/?probe=8862a40143) | Aug 13, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [c28cbbd2a1](https://linux-hardware.org/?probe=c28cbbd2a1) | Aug 13, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [6d1e3a24e8](https://linux-hardware.org/?probe=6d1e3a24e8) | Aug 13, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [551d8f3fc8](https://linux-hardware.org/?probe=551d8f3fc8) | Aug 13, 2023 |
| Dell          | Latitude E6410              | Notebook    | [8ed9952374](https://linux-hardware.org/?probe=8ed9952374) | Aug 13, 2023 |
| Dell          | Inspiron M5010              | Notebook    | [dd2538ba1a](https://linux-hardware.org/?probe=dd2538ba1a) | Aug 13, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [b6b99bf7bd](https://linux-hardware.org/?probe=b6b99bf7bd) | Aug 12, 2023 |
| Gigabyte      | G1.Sniper M3-CF             | Desktop     | [f4d0fd6811](https://linux-hardware.org/?probe=f4d0fd6811) | Aug 12, 2023 |
| Gigabyte      | G1.Sniper M3-CF             | Desktop     | [a5681e12d3](https://linux-hardware.org/?probe=a5681e12d3) | Aug 12, 2023 |
| Panasonic     | CF-19ADNAXDA                | Notebook    | [d96cf2b13c](https://linux-hardware.org/?probe=d96cf2b13c) | Aug 12, 2023 |
| Dell          | G7 7790                     | Notebook    | [b5062f0928](https://linux-hardware.org/?probe=b5062f0928) | Aug 12, 2023 |
| Intel         | NUC11PABi7 M68262-501       | Mini pc     | [422a91a4eb](https://linux-hardware.org/?probe=422a91a4eb) | Aug 12, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [359d84713c](https://linux-hardware.org/?probe=359d84713c) | Aug 11, 2023 |
| Acer          | TMP255-M                    | Notebook    | [0b1adaea4e](https://linux-hardware.org/?probe=0b1adaea4e) | Aug 11, 2023 |
| Microsoft     | Surface Go 3                | Tablet      | [75d63c7495](https://linux-hardware.org/?probe=75d63c7495) | Aug 11, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [93a61b62a5](https://linux-hardware.org/?probe=93a61b62a5) | Aug 11, 2023 |
| Leader        | SC404PRO                    | Notebook    | [6f24ee5e0c](https://linux-hardware.org/?probe=6f24ee5e0c) | Aug 11, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [025afcb20d](https://linux-hardware.org/?probe=025afcb20d) | Aug 10, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | Notebook    | [2f64f3ee9a](https://linux-hardware.org/?probe=2f64f3ee9a) | Aug 10, 2023 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | Desktop     | [5264c46571](https://linux-hardware.org/?probe=5264c46571) | Aug 10, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [c5491b8e9f](https://linux-hardware.org/?probe=c5491b8e9f) | Aug 10, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [2be2a9d5f4](https://linux-hardware.org/?probe=2be2a9d5f4) | Aug 09, 2023 |
| Dell          | Inspiron M5010              | Notebook    | [be4ad618b4](https://linux-hardware.org/?probe=be4ad618b4) | Aug 09, 2023 |
| Apple         | MacBookPro15,2              | Notebook    | [68e26bb5d3](https://linux-hardware.org/?probe=68e26bb5d3) | Aug 09, 2023 |
| Dell          | 0X2MKR A00                  | All in one  | [84c3eefc94](https://linux-hardware.org/?probe=84c3eefc94) | Aug 08, 2023 |
| Dell          | Vostro 5581                 | Notebook    | [b4495daa07](https://linux-hardware.org/?probe=b4495daa07) | Aug 08, 2023 |
| Dell          | Inspiron 5485 2n1           | Convertible | [f4c69a94e9](https://linux-hardware.org/?probe=f4c69a94e9) | Aug 08, 2023 |
| Dell          | Inspiron 5485 2n1           | Convertible | [e5efd1b16c](https://linux-hardware.org/?probe=e5efd1b16c) | Aug 08, 2023 |
| ASUSTek       | STRIX H270F GAMING          | Desktop     | [ab74b5c684](https://linux-hardware.org/?probe=ab74b5c684) | Aug 08, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [e8524b0045](https://linux-hardware.org/?probe=e8524b0045) | Aug 08, 2023 |
| ASUSTek       | STRIX H270F GAMING          | Desktop     | [85ffbedac4](https://linux-hardware.org/?probe=85ffbedac4) | Aug 08, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [ffd0be48c6](https://linux-hardware.org/?probe=ffd0be48c6) | Aug 08, 2023 |
| HP            | 212B                        | Desktop     | [b7de4a2b0a](https://linux-hardware.org/?probe=b7de4a2b0a) | Aug 07, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [51c3d4511a](https://linux-hardware.org/?probe=51c3d4511a) | Aug 07, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [fb1aaeae43](https://linux-hardware.org/?probe=fb1aaeae43) | Aug 07, 2023 |
| Dell          | Inspiron 5770               | Notebook    | [d6a978f124](https://linux-hardware.org/?probe=d6a978f124) | Aug 07, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [f2d72fe710](https://linux-hardware.org/?probe=f2d72fe710) | Aug 07, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [c003e20331](https://linux-hardware.org/?probe=c003e20331) | Aug 06, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [3b589d53bc](https://linux-hardware.org/?probe=3b589d53bc) | Aug 06, 2023 |
| Dell          | 08VT7V A01                  | Server      | [422a30cacf](https://linux-hardware.org/?probe=422a30cacf) | Aug 06, 2023 |
| MSI           | P65 Creator 8RE             | Notebook    | [853567f156](https://linux-hardware.org/?probe=853567f156) | Aug 06, 2023 |
| MSI           | P65 Creator 8RE             | Notebook    | [f26344a920](https://linux-hardware.org/?probe=f26344a920) | Aug 05, 2023 |
| Dell          | Latitude E6220              | Notebook    | [636392b4bf](https://linux-hardware.org/?probe=636392b4bf) | Aug 05, 2023 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [b9d8025a54](https://linux-hardware.org/?probe=b9d8025a54) | Aug 05, 2023 |
| Acer          | AS E5-523G                  | Notebook    | [b37e833d1e](https://linux-hardware.org/?probe=b37e833d1e) | Aug 05, 2023 |
| ASUSTek       | ROG Maximus XII EXTREME     | Desktop     | [f5ebaad3b1](https://linux-hardware.org/?probe=f5ebaad3b1) | Aug 05, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [dd1767aec1](https://linux-hardware.org/?probe=dd1767aec1) | Aug 04, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [15fb5d0baf](https://linux-hardware.org/?probe=15fb5d0baf) | Aug 04, 2023 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [a02f0405a3](https://linux-hardware.org/?probe=a02f0405a3) | Aug 04, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [fe0a1dbc45](https://linux-hardware.org/?probe=fe0a1dbc45) | Aug 04, 2023 |
| Acer          | Aspire 8943G                | Notebook    | [fedb43e298](https://linux-hardware.org/?probe=fedb43e298) | Aug 04, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [90aecb9ada](https://linux-hardware.org/?probe=90aecb9ada) | Aug 04, 2023 |
| Lenovo        | ThinkPad T480s 20L8S84H0... | Notebook    | [d64e9809fa](https://linux-hardware.org/?probe=d64e9809fa) | Aug 04, 2023 |
| Gigabyte      | Z490M GAMING X              | Desktop     | [ad51d2548b](https://linux-hardware.org/?probe=ad51d2548b) | Aug 03, 2023 |
| Dell          | 09M8Y8 A01                  | Desktop     | [e5649696d0](https://linux-hardware.org/?probe=e5649696d0) | Aug 03, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | Notebook    | [c96666b80d](https://linux-hardware.org/?probe=c96666b80d) | Aug 03, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [1eb6fd9620](https://linux-hardware.org/?probe=1eb6fd9620) | Aug 02, 2023 |
| HP            | 2B2C                        | Desktop     | [3f0b3f8811](https://linux-hardware.org/?probe=3f0b3f8811) | Aug 01, 2023 |
| Dell          | 06NWYK A00                  | Desktop     | [1c3a3db0ec](https://linux-hardware.org/?probe=1c3a3db0ec) | Aug 01, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [888c56f232](https://linux-hardware.org/?probe=888c56f232) | Aug 01, 2023 |
| Dell          | 0Y5DDC A00                  | Desktop     | [43624df7d4](https://linux-hardware.org/?probe=43624df7d4) | Jul 30, 2023 |
| Dell          | Inspiron M5010              | Notebook    | [8608f29a0f](https://linux-hardware.org/?probe=8608f29a0f) | Jul 30, 2023 |
| MSI           | Z87-G45 GAMING              | Desktop     | [6c5528a787](https://linux-hardware.org/?probe=6c5528a787) | Jul 30, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [4fb6a46f65](https://linux-hardware.org/?probe=4fb6a46f65) | Jul 30, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [60bf32a368](https://linux-hardware.org/?probe=60bf32a368) | Jul 29, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [580c4fb755](https://linux-hardware.org/?probe=580c4fb755) | Jul 29, 2023 |
| Lenovo        | ThinkBook 13x G2 IAP 21A... | Notebook    | [bc18b4b7ed](https://linux-hardware.org/?probe=bc18b4b7ed) | Jul 29, 2023 |
| Lenovo        | ThinkBook 13x G2 IAP 21A... | Notebook    | [9b4b9b9d59](https://linux-hardware.org/?probe=9b4b9b9d59) | Jul 29, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [e4efeb0276](https://linux-hardware.org/?probe=e4efeb0276) | Jul 29, 2023 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | Desktop     | [8c930cc5e4](https://linux-hardware.org/?probe=8c930cc5e4) | Jul 29, 2023 |
| ASUSTek       | WS C246 PRO                 | Desktop     | [cfffc2ba92](https://linux-hardware.org/?probe=cfffc2ba92) | Jul 28, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [7864dbf54c](https://linux-hardware.org/?probe=7864dbf54c) | Jul 28, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [abf0e5979c](https://linux-hardware.org/?probe=abf0e5979c) | Jul 27, 2023 |
| Toshiba       | PORTEGE X30-E               | Notebook    | [c610464fb5](https://linux-hardware.org/?probe=c610464fb5) | Jul 27, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [0b04075e09](https://linux-hardware.org/?probe=0b04075e09) | Jul 27, 2023 |
| Acer          | TMP255-M                    | Notebook    | [25d376a674](https://linux-hardware.org/?probe=25d376a674) | Jul 26, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [0059745bdf](https://linux-hardware.org/?probe=0059745bdf) | Jul 25, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [90beff8e65](https://linux-hardware.org/?probe=90beff8e65) | Jul 25, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [31b7924358](https://linux-hardware.org/?probe=31b7924358) | Jul 25, 2023 |
| Google        | Sumo                        | Desktop     | [71a7167d22](https://linux-hardware.org/?probe=71a7167d22) | Jul 25, 2023 |
| HP            | 1998                        | Desktop     | [ef5201611b](https://linux-hardware.org/?probe=ef5201611b) | Jul 24, 2023 |
| HP            | 1998                        | Desktop     | [5a95ac128d](https://linux-hardware.org/?probe=5a95ac128d) | Jul 24, 2023 |
| Acer          | TMP255-M                    | Notebook    | [c4bfc82a98](https://linux-hardware.org/?probe=c4bfc82a98) | Jul 24, 2023 |
| Acer          | TMP255-M                    | Notebook    | [7a57ee89af](https://linux-hardware.org/?probe=7a57ee89af) | Jul 24, 2023 |
| Acer          | Aspire A3SP14-31PT          | Convertible | [97f835b6ca](https://linux-hardware.org/?probe=97f835b6ca) | Jul 24, 2023 |
| Intel         | NUC11PABi7 M68262-501       | Mini pc     | [f3d1b0d511](https://linux-hardware.org/?probe=f3d1b0d511) | Jul 24, 2023 |
| ASUSTek       | PN61                        | Mini pc     | [78418a9a7f](https://linux-hardware.org/?probe=78418a9a7f) | Jul 24, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [579d5d5771](https://linux-hardware.org/?probe=579d5d5771) | Jul 24, 2023 |
| Dell          | Latitude 5410               | Notebook    | [29261ea2bb](https://linux-hardware.org/?probe=29261ea2bb) | Jul 24, 2023 |
| MSI           | Cyborg 15 A13VE             | Notebook    | [edf7b092ec](https://linux-hardware.org/?probe=edf7b092ec) | Jul 23, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [35d95135f4](https://linux-hardware.org/?probe=35d95135f4) | Jul 23, 2023 |
| MSI           | Cyborg 15 A13VE             | Notebook    | [421c2ff6b0](https://linux-hardware.org/?probe=421c2ff6b0) | Jul 23, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [a4b823b309](https://linux-hardware.org/?probe=a4b823b309) | Jul 23, 2023 |
| HP            | EliteBook 835 G8 Noteboo... | Notebook    | [a3350e1d80](https://linux-hardware.org/?probe=a3350e1d80) | Jul 23, 2023 |
| HP            | ZBook Studio G3             | Notebook    | [bcfc5b64f4](https://linux-hardware.org/?probe=bcfc5b64f4) | Jul 23, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [f525252834](https://linux-hardware.org/?probe=f525252834) | Jul 23, 2023 |
| MSI           | MEGA BOOK GX620             | Notebook    | [184ec8dfc2](https://linux-hardware.org/?probe=184ec8dfc2) | Jul 22, 2023 |
| Dell          | Latitude E6430s             | Notebook    | [8e74e2a524](https://linux-hardware.org/?probe=8e74e2a524) | Jul 22, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [25ab3b442b](https://linux-hardware.org/?probe=25ab3b442b) | Jul 22, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [20ec4f50dc](https://linux-hardware.org/?probe=20ec4f50dc) | Jul 22, 2023 |
| Lenovo        | ThinkPad Yoga 11e 5th Ge... | Convertible | [bcd5455f58](https://linux-hardware.org/?probe=bcd5455f58) | Jul 22, 2023 |
| MSI           | Z97 PC Mate                 | Desktop     | [f4cddb5e86](https://linux-hardware.org/?probe=f4cddb5e86) | Jul 22, 2023 |
| Intel         | NUC11PABi7 M68262-501       | Mini pc     | [39f954742c](https://linux-hardware.org/?probe=39f954742c) | Jul 21, 2023 |
| Intel         | DQ57TM AAE70931-402         | Desktop     | [01621f8578](https://linux-hardware.org/?probe=01621f8578) | Jul 21, 2023 |
| Gigabyte      | 945GCMX-S2                  | Desktop     | [46e297492f](https://linux-hardware.org/?probe=46e297492f) | Jul 21, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [fa4def4ece](https://linux-hardware.org/?probe=fa4def4ece) | Jul 21, 2023 |
| Apple         | MacBookPro14,3              | Notebook    | [e24c8a224e](https://linux-hardware.org/?probe=e24c8a224e) | Jul 21, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [044cf93e31](https://linux-hardware.org/?probe=044cf93e31) | Jul 20, 2023 |
| Toshiba       | Satellite L750              | Notebook    | [662f89dcc3](https://linux-hardware.org/?probe=662f89dcc3) | Jul 20, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [3da3da07e9](https://linux-hardware.org/?probe=3da3da07e9) | Jul 19, 2023 |
| ASUSTek       | ROG Maximus XII EXTREME     | Desktop     | [0f7fea54eb](https://linux-hardware.org/?probe=0f7fea54eb) | Jul 19, 2023 |
| Dell          | Latitude 5330               | Convertible | [45ca5a9872](https://linux-hardware.org/?probe=45ca5a9872) | Jul 19, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [572537c287](https://linux-hardware.org/?probe=572537c287) | Jul 19, 2023 |
| Microsoft     | Surface Pro 6               | Tablet      | [9a9670d446](https://linux-hardware.org/?probe=9a9670d446) | Jul 18, 2023 |
| ASUSTek       | PRIME Z370-A II             | Desktop     | [6ca4720242](https://linux-hardware.org/?probe=6ca4720242) | Jul 18, 2023 |
| ASRock        | Z77 Performance             | Notebook    | [585aaad9ad](https://linux-hardware.org/?probe=585aaad9ad) | Jul 18, 2023 |
| ASRock        | B660M-HDV                   | Desktop     | [3a0685bcf0](https://linux-hardware.org/?probe=3a0685bcf0) | Jul 18, 2023 |
| Toshiba       | Satellite L850              | Notebook    | [afdd53cd2f](https://linux-hardware.org/?probe=afdd53cd2f) | Jul 18, 2023 |
| Toshiba       | Satellite L850              | Notebook    | [23c31a7c87](https://linux-hardware.org/?probe=23c31a7c87) | Jul 17, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [553cbdb79d](https://linux-hardware.org/?probe=553cbdb79d) | Jul 17, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [60d7a077dc](https://linux-hardware.org/?probe=60d7a077dc) | Jul 17, 2023 |
| SONIQ Digi... | Soniq 11.6inch Convertib... | Convertible | [8e01cf8f1e](https://linux-hardware.org/?probe=8e01cf8f1e) | Jul 17, 2023 |
| Lenovo        | ThinkPad L390 Yoga 20NUS... | Convertible | [c9f052e7ff](https://linux-hardware.org/?probe=c9f052e7ff) | Jul 16, 2023 |
| Lenovo        | ThinkPad X13s Gen 1 21BY... | Notebook    | [1a0f8c842b](https://linux-hardware.org/?probe=1a0f8c842b) | Jul 16, 2023 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | Desktop     | [20ee7f8016](https://linux-hardware.org/?probe=20ee7f8016) | Jul 16, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [5bf40815d5](https://linux-hardware.org/?probe=5bf40815d5) | Jul 16, 2023 |
| Gigabyte      | Z490 AORUS PRO AX           | Desktop     | [1b32b611bf](https://linux-hardware.org/?probe=1b32b611bf) | Jul 16, 2023 |
| Acer          | TravelMate Spin B118-R      | Convertible | [c0ad7a539d](https://linux-hardware.org/?probe=c0ad7a539d) | Jul 15, 2023 |
| Dell          | G5 5505                     | Notebook    | [ba144013b3](https://linux-hardware.org/?probe=ba144013b3) | Jul 15, 2023 |
| ASUSTek       | X99-DELUXE II               | Desktop     | [d132761a85](https://linux-hardware.org/?probe=d132761a85) | Jul 14, 2023 |
| ASUSTek       | X99-DELUXE II               | Desktop     | [70345fff08](https://linux-hardware.org/?probe=70345fff08) | Jul 14, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [8ee665fb8f](https://linux-hardware.org/?probe=8ee665fb8f) | Jul 14, 2023 |
| Gigabyte      | GA-A55M-S2V                 | Desktop     | [fadd5eeba6](https://linux-hardware.org/?probe=fadd5eeba6) | Jul 13, 2023 |
| Dell          | 03NVJ6 A01                  | Desktop     | [b575153979](https://linux-hardware.org/?probe=b575153979) | Jul 13, 2023 |
| Dell          | 03NVJ6 A01                  | Desktop     | [05e8a2652e](https://linux-hardware.org/?probe=05e8a2652e) | Jul 13, 2023 |
| MSI           | Stealth 16Studio A13VG      | Notebook    | [ab3683571a](https://linux-hardware.org/?probe=ab3683571a) | Jul 13, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [706f24ffe5](https://linux-hardware.org/?probe=706f24ffe5) | Jul 12, 2023 |
| ASUSTek       | Zephyrus M GM501GM          | Notebook    | [72454f0f8e](https://linux-hardware.org/?probe=72454f0f8e) | Jul 11, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [5c12592f23](https://linux-hardware.org/?probe=5c12592f23) | Jul 11, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [38f91b870c](https://linux-hardware.org/?probe=38f91b870c) | Jul 11, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [e0c7ec0cbc](https://linux-hardware.org/?probe=e0c7ec0cbc) | Jul 11, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [e2023d0c6d](https://linux-hardware.org/?probe=e2023d0c6d) | Jul 11, 2023 |
| Inventec      | 0W63N3 A01                  | Mini pc     | [02a820f6b2](https://linux-hardware.org/?probe=02a820f6b2) | Jul 11, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [a9e19d3887](https://linux-hardware.org/?probe=a9e19d3887) | Jul 11, 2023 |
| MSI           | PRO H610M-G DDR4            | Desktop     | [4ff789de3b](https://linux-hardware.org/?probe=4ff789de3b) | Jul 11, 2023 |
| HP            | 250 G2                      | Notebook    | [7fd1832150](https://linux-hardware.org/?probe=7fd1832150) | Jul 11, 2023 |
| HP            | 250 G2                      | Notebook    | [738b04c947](https://linux-hardware.org/?probe=738b04c947) | Jul 11, 2023 |
| ASUSTek       | ZenBook UX431FA             | Notebook    | [09edc8f932](https://linux-hardware.org/?probe=09edc8f932) | Jul 11, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [ac8df9628d](https://linux-hardware.org/?probe=ac8df9628d) | Jul 10, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [f4f002c37a](https://linux-hardware.org/?probe=f4f002c37a) | Jul 10, 2023 |
| MSI           | MPG B650I EDGE WIFI         | Desktop     | [dcf418007d](https://linux-hardware.org/?probe=dcf418007d) | Jul 10, 2023 |
| MSI           | MPG B650I EDGE WIFI         | Desktop     | [b515a2980e](https://linux-hardware.org/?probe=b515a2980e) | Jul 10, 2023 |
| Avalue        | NUC-APL E9697JAI006R        | Desktop     | [8e289dc3f9](https://linux-hardware.org/?probe=8e289dc3f9) | Jul 10, 2023 |
| Avalue        | NUC-APL E9697JAI006R        | Desktop     | [8f7a02d8b5](https://linux-hardware.org/?probe=8f7a02d8b5) | Jul 10, 2023 |
| Acer          | ConceptD CN315-71P          | Notebook    | [a211dd78de](https://linux-hardware.org/?probe=a211dd78de) | Jul 09, 2023 |
| Gigabyte      | X570S AORUS ELITE           | Desktop     | [6381f6da84](https://linux-hardware.org/?probe=6381f6da84) | Jul 09, 2023 |
| Toshiba       | PORTEGE Z30-C               | Notebook    | [f9d1d19d05](https://linux-hardware.org/?probe=f9d1d19d05) | Jul 09, 2023 |
| MSI           | Stealth 16Studio A13VG      | Notebook    | [e16527e244](https://linux-hardware.org/?probe=e16527e244) | Jul 09, 2023 |
| HP            | 1791                        | Desktop     | [a2bf914a45](https://linux-hardware.org/?probe=a2bf914a45) | Jul 08, 2023 |
| ASRock        | X670E Pro RS                | Desktop     | [d41838c540](https://linux-hardware.org/?probe=d41838c540) | Jul 08, 2023 |
| Gigabyte      | GA-A55M-S2V                 | Desktop     | [6cac69cac1](https://linux-hardware.org/?probe=6cac69cac1) | Jul 08, 2023 |
| Acer          | Aspire One 753              | Notebook    | [f47888ce55](https://linux-hardware.org/?probe=f47888ce55) | Jul 08, 2023 |
| Acer          | Aspire One 753              | Notebook    | [9f56cc566d](https://linux-hardware.org/?probe=9f56cc566d) | Jul 08, 2023 |
| MSI           | MPG B650I EDGE WIFI         | Desktop     | [bdaa09e52c](https://linux-hardware.org/?probe=bdaa09e52c) | Jul 08, 2023 |
| Dell          | 09D2HH A00                  | Desktop     | [2885be7e12](https://linux-hardware.org/?probe=2885be7e12) | Jul 07, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [0d98ce8578](https://linux-hardware.org/?probe=0d98ce8578) | Jul 07, 2023 |
| MSI           | Z97S SLI Krait Edition      | Desktop     | [c353b62b15](https://linux-hardware.org/?probe=c353b62b15) | Jul 07, 2023 |
| MSI           | MS-7142                     | Desktop     | [3247a2f71c](https://linux-hardware.org/?probe=3247a2f71c) | Jul 06, 2023 |
| MSI           | B150 GAMING M3              | Desktop     | [a8018be55a](https://linux-hardware.org/?probe=a8018be55a) | Jul 06, 2023 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [3af1e33a01](https://linux-hardware.org/?probe=3af1e33a01) | Jul 06, 2023 |
| Toshiba       | PORTEGE X30-E               | Notebook    | [d68e9cd764](https://linux-hardware.org/?probe=d68e9cd764) | Jul 06, 2023 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [04d7534d9e](https://linux-hardware.org/?probe=04d7534d9e) | Jul 06, 2023 |
| ASUSTek       | G750JZA                     | Notebook    | [fb2477dd61](https://linux-hardware.org/?probe=fb2477dd61) | Jul 06, 2023 |
| MSI           | Z97 PC Mate                 | Desktop     | [495b6e6e4a](https://linux-hardware.org/?probe=495b6e6e4a) | Jul 06, 2023 |
| HP            | ProBook 4540s               | Notebook    | [cccf56865c](https://linux-hardware.org/?probe=cccf56865c) | Jul 06, 2023 |
| Acer          | TravelMate 8572T            | Notebook    | [67f4a2af7e](https://linux-hardware.org/?probe=67f4a2af7e) | Jul 05, 2023 |
| MSI           | Z97 PC Mate                 | Desktop     | [0d9ce2b3d2](https://linux-hardware.org/?probe=0d9ce2b3d2) | Jul 05, 2023 |
| Lenovo        | ThinkPad P50 20EQS48H00     | Notebook    | [7f64164b64](https://linux-hardware.org/?probe=7f64164b64) | Jul 04, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [407e00921f](https://linux-hardware.org/?probe=407e00921f) | Jul 04, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [da0ca66579](https://linux-hardware.org/?probe=da0ca66579) | Jul 04, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [f7a7db0702](https://linux-hardware.org/?probe=f7a7db0702) | Jul 04, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [464ff62eaf](https://linux-hardware.org/?probe=464ff62eaf) | Jul 04, 2023 |
| ASUSTek       | G750JZA                     | Notebook    | [72fc73822c](https://linux-hardware.org/?probe=72fc73822c) | Jul 04, 2023 |
| Dell          | Latitude 5420               | Notebook    | [dedd6c842c](https://linux-hardware.org/?probe=dedd6c842c) | Jul 04, 2023 |
| Dell          | Latitude 5420               | Notebook    | [dfe3274d7e](https://linux-hardware.org/?probe=dfe3274d7e) | Jul 03, 2023 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | Notebook    | [4586b855ca](https://linux-hardware.org/?probe=4586b855ca) | Jul 02, 2023 |
| Dell          | 0TY565                      | Desktop     | [98f290cadd](https://linux-hardware.org/?probe=98f290cadd) | Jul 02, 2023 |
| Gigabyte      | Q2532N                      | Notebook    | [4560685060](https://linux-hardware.org/?probe=4560685060) | Jul 02, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [b6b1cf5b68](https://linux-hardware.org/?probe=b6b1cf5b68) | Jul 02, 2023 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [49c764507c](https://linux-hardware.org/?probe=49c764507c) | Jul 01, 2023 |
| Gigabyte      | P67A-UD5-B3                 | Desktop     | [b763c860fa](https://linux-hardware.org/?probe=b763c860fa) | Jun 30, 2023 |
| Acer          | TravelMate 8572T            | Notebook    | [a73fd92e21](https://linux-hardware.org/?probe=a73fd92e21) | Jun 30, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [593512053f](https://linux-hardware.org/?probe=593512053f) | Jun 30, 2023 |
| Gigabyte      | H170-HD3-CF                 | Desktop     | [59d1be1c5d](https://linux-hardware.org/?probe=59d1be1c5d) | Jun 30, 2023 |
| ASRock        | Z690 Steel Legend WiFi 6... | Desktop     | [d09ee66df1](https://linux-hardware.org/?probe=d09ee66df1) | Jun 29, 2023 |
| ASRock        | Z77 Performance             | Notebook    | [a678dc9605](https://linux-hardware.org/?probe=a678dc9605) | Jun 29, 2023 |
| Acer          | TravelMate B113             | Notebook    | [04738ce824](https://linux-hardware.org/?probe=04738ce824) | Jun 29, 2023 |
| Acer          | TravelMate B113             | Notebook    | [9cfe4d5036](https://linux-hardware.org/?probe=9cfe4d5036) | Jun 29, 2023 |
| Unknown       | Unknown                     | Notebook    | [d358089f32](https://linux-hardware.org/?probe=d358089f32) | Jun 29, 2023 |
| Acer          | Aspire xxxx                 | Notebook    | [67e8606837](https://linux-hardware.org/?probe=67e8606837) | Jun 29, 2023 |
| HP            | Pavilion dv6                | Notebook    | [7fe9e439c0](https://linux-hardware.org/?probe=7fe9e439c0) | Jun 28, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [ba0db6c3e9](https://linux-hardware.org/?probe=ba0db6c3e9) | Jun 28, 2023 |
| ASUSTek       | ZenBook Pro 15 UX550GEX_... | Notebook    | [56eef68e89](https://linux-hardware.org/?probe=56eef68e89) | Jun 28, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [f4540c6370](https://linux-hardware.org/?probe=f4540c6370) | Jun 27, 2023 |
| Intel         | LADPNVMO AAE76523-300       | Desktop     | [76cc7bbb86](https://linux-hardware.org/?probe=76cc7bbb86) | Jun 27, 2023 |
| Lenovo        | ThinkPad X230 2325CW1       | Notebook    | [70cbf738e8](https://linux-hardware.org/?probe=70cbf738e8) | Jun 27, 2023 |
| ASRock        | X370 Gaming-ITX/ac          | Desktop     | [975e5164c6](https://linux-hardware.org/?probe=975e5164c6) | Jun 27, 2023 |
| Leader        | SC8-PRO                     | Stick pc    | [ad54f075f6](https://linux-hardware.org/?probe=ad54f075f6) | Jun 26, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [06a581d65d](https://linux-hardware.org/?probe=06a581d65d) | Jun 25, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [a105b6264f](https://linux-hardware.org/?probe=a105b6264f) | Jun 25, 2023 |
| Toshiba       | Satellite L550              | Notebook    | [321ec36f85](https://linux-hardware.org/?probe=321ec36f85) | Jun 25, 2023 |
| ASUSTek       | X550LA                      | Notebook    | [225516996c](https://linux-hardware.org/?probe=225516996c) | Jun 25, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [79979ceac7](https://linux-hardware.org/?probe=79979ceac7) | Jun 25, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [ac084eba06](https://linux-hardware.org/?probe=ac084eba06) | Jun 24, 2023 |
| Acer          | Aspire A315-22              | Notebook    | [5e2e395efd](https://linux-hardware.org/?probe=5e2e395efd) | Jun 24, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [54d0d54490](https://linux-hardware.org/?probe=54d0d54490) | Jun 24, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [2b61a56610](https://linux-hardware.org/?probe=2b61a56610) | Jun 24, 2023 |
| System76      | Oryx Pro                    | Notebook    | [eaa4d8e105](https://linux-hardware.org/?probe=eaa4d8e105) | Jun 24, 2023 |
| ASUSTek       | X550LC                      | Notebook    | [30369c12e1](https://linux-hardware.org/?probe=30369c12e1) | Jun 24, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [a3a840a283](https://linux-hardware.org/?probe=a3a840a283) | Jun 23, 2023 |
| Lenovo        | ThinkPad T460s 20FAS0NF0... | Notebook    | [f2e368a70d](https://linux-hardware.org/?probe=f2e368a70d) | Jun 23, 2023 |
| ASRock        | B365M Pro4-F                | Desktop     | [16a5102512](https://linux-hardware.org/?probe=16a5102512) | Jun 23, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [efc582d761](https://linux-hardware.org/?probe=efc582d761) | Jun 23, 2023 |
| HP            | Pavilion dv6                | Notebook    | [fa9045c36f](https://linux-hardware.org/?probe=fa9045c36f) | Jun 22, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [d3a63bb6aa](https://linux-hardware.org/?probe=d3a63bb6aa) | Jun 22, 2023 |
| Lenovo        | 30C0 SDK0J40697 WIN 3305... | Desktop     | [8c4bd347a7](https://linux-hardware.org/?probe=8c4bd347a7) | Jun 21, 2023 |
| HP            | 1588h                       | Desktop     | [abe5412cf6](https://linux-hardware.org/?probe=abe5412cf6) | Jun 21, 2023 |
| HP            | 1588h                       | Desktop     | [f08e230cd3](https://linux-hardware.org/?probe=f08e230cd3) | Jun 21, 2023 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [4131c0a5bb](https://linux-hardware.org/?probe=4131c0a5bb) | Jun 20, 2023 |
| ASUSTek       | X550LA                      | Notebook    | [9b58f1abd3](https://linux-hardware.org/?probe=9b58f1abd3) | Jun 20, 2023 |
| Microsoft     | Surface Laptop              | Tablet      | [401cb6a1f1](https://linux-hardware.org/?probe=401cb6a1f1) | Jun 20, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [c1aac2f0a4](https://linux-hardware.org/?probe=c1aac2f0a4) | Jun 19, 2023 |
| IBM           | FAB2 Controller Producti... | Server      | [daa3df0f31](https://linux-hardware.org/?probe=daa3df0f31) | Jun 19, 2023 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [e5740353af](https://linux-hardware.org/?probe=e5740353af) | Jun 19, 2023 |
| COM1          | NBINF-X5-9G5                | Notebook    | [fe2f1cfef6](https://linux-hardware.org/?probe=fe2f1cfef6) | Jun 19, 2023 |
| HP            | EliteBook 8760w             | Notebook    | [ac41230354](https://linux-hardware.org/?probe=ac41230354) | Jun 18, 2023 |
| Microsoft     | Surface Go                  | Tablet      | [f266551c9d](https://linux-hardware.org/?probe=f266551c9d) | Jun 18, 2023 |
| Dell          | 06NWYK A00                  | Desktop     | [5e065b17cf](https://linux-hardware.org/?probe=5e065b17cf) | Jun 18, 2023 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [fdbe50b1d6](https://linux-hardware.org/?probe=fdbe50b1d6) | Jun 18, 2023 |
| Gigabyte      | Z690 AORUS PRO              | Desktop     | [e9dd574827](https://linux-hardware.org/?probe=e9dd574827) | Jun 18, 2023 |
| Dell          | Latitude E7440              | Notebook    | [60d14fe6ab](https://linux-hardware.org/?probe=60d14fe6ab) | Jun 18, 2023 |
| Alienware     | M14xR2                      | Notebook    | [2eb0cc2d0e](https://linux-hardware.org/?probe=2eb0cc2d0e) | Jun 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [26b4c05332](https://linux-hardware.org/?probe=26b4c05332) | Jun 17, 2023 |
| Intel         | NUC12WSBi5 M46425-302       | Mini pc     | [79c0cd0257](https://linux-hardware.org/?probe=79c0cd0257) | Jun 17, 2023 |
| Apple         | Mac-F2238AC8                | All in one  | [7d9f25dc5f](https://linux-hardware.org/?probe=7d9f25dc5f) | Jun 17, 2023 |
| Acer          | Aspire A315-510P            | Notebook    | [d1be914db1](https://linux-hardware.org/?probe=d1be914db1) | Jun 17, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [852d16ee14](https://linux-hardware.org/?probe=852d16ee14) | Jun 16, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [b7faea4be3](https://linux-hardware.org/?probe=b7faea4be3) | Jun 16, 2023 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [29ff056f4a](https://linux-hardware.org/?probe=29ff056f4a) | Jun 16, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | Notebook    | [99cc4bf84b](https://linux-hardware.org/?probe=99cc4bf84b) | Jun 16, 2023 |
| HP            | Pavilion dv6                | Notebook    | [55c83ec890](https://linux-hardware.org/?probe=55c83ec890) | Jun 15, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | Notebook    | [f7049b2256](https://linux-hardware.org/?probe=f7049b2256) | Jun 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [613aa12940](https://linux-hardware.org/?probe=613aa12940) | Jun 14, 2023 |
| Dell          | Inspiron M5010              | Notebook    | [33541731e3](https://linux-hardware.org/?probe=33541731e3) | Jun 14, 2023 |
| Gigabyte      | D525TUD                     | Desktop     | [2d854be38a](https://linux-hardware.org/?probe=2d854be38a) | Jun 14, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [993f00eca6](https://linux-hardware.org/?probe=993f00eca6) | Jun 14, 2023 |
| Gigabyte      | D525TUD                     | Desktop     | [be2c796ab2](https://linux-hardware.org/?probe=be2c796ab2) | Jun 13, 2023 |
| ASRock        | X570 Phantom Gaming-ITX/... | Desktop     | [7689518326](https://linux-hardware.org/?probe=7689518326) | Jun 13, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [b2eb89c4fd](https://linux-hardware.org/?probe=b2eb89c4fd) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M58 7360PL9     | Desktop     | [da837e8612](https://linux-hardware.org/?probe=da837e8612) | Jun 13, 2023 |
| Seco          | C40 C                       | Desktop     | [37b8e950d0](https://linux-hardware.org/?probe=37b8e950d0) | Jun 12, 2023 |
| ASRock        | X570 Phantom Gaming-ITX/... | Desktop     | [e68b78c037](https://linux-hardware.org/?probe=e68b78c037) | Jun 12, 2023 |
| ASRock        | Z690 Steel Legend WiFi 6... | Desktop     | [0190531869](https://linux-hardware.org/?probe=0190531869) | Jun 12, 2023 |
| ASRock        | Z690 Steel Legend WiFi 6... | Desktop     | [648161a6ff](https://linux-hardware.org/?probe=648161a6ff) | Jun 12, 2023 |
| Acer          | Aspire A315-510P            | Notebook    | [705ad3c316](https://linux-hardware.org/?probe=705ad3c316) | Jun 12, 2023 |
| NEC Comput... | VERSA P91 series            | Notebook    | [7a4183e095](https://linux-hardware.org/?probe=7a4183e095) | Jun 12, 2023 |
| NEC Comput... | VERSA P91 series            | Notebook    | [2051db7014](https://linux-hardware.org/?probe=2051db7014) | Jun 12, 2023 |
| BESSTAR Te... | B550                        | Desktop     | [b74cc9dfff](https://linux-hardware.org/?probe=b74cc9dfff) | Jun 11, 2023 |
| COM1          | NBINF-X5-9G5                | Notebook    | [755841cee1](https://linux-hardware.org/?probe=755841cee1) | Jun 11, 2023 |
| Pegatron      | 2ACB                        | Desktop     | [61e759f7db](https://linux-hardware.org/?probe=61e759f7db) | Jun 11, 2023 |
| MSI           | GS60 6QE                    | Notebook    | [e04ff9df40](https://linux-hardware.org/?probe=e04ff9df40) | Jun 10, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [b599a55609](https://linux-hardware.org/?probe=b599a55609) | Jun 10, 2023 |
| Dell          | 0N4YC8 A00                  | Desktop     | [bc832400b4](https://linux-hardware.org/?probe=bc832400b4) | Jun 10, 2023 |
| Toshiba       | PORTEGE Z10t-A              | Notebook    | [4a0712b322](https://linux-hardware.org/?probe=4a0712b322) | Jun 10, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [5d21e64704](https://linux-hardware.org/?probe=5d21e64704) | Jun 10, 2023 |
| IT Channel... | N8xEJEK                     | Notebook    | [51a7e3f5b4](https://linux-hardware.org/?probe=51a7e3f5b4) | Jun 10, 2023 |
| ASRock        | X570 Phantom Gaming X       | Desktop     | [0c4db9b922](https://linux-hardware.org/?probe=0c4db9b922) | Jun 10, 2023 |
| IBM           | FAB2 Controller Producti... | Server      | [af396cb333](https://linux-hardware.org/?probe=af396cb333) | Jun 10, 2023 |
| Dell          | 0XCR8D A03                  | Desktop     | [e37bceb6fb](https://linux-hardware.org/?probe=e37bceb6fb) | Jun 09, 2023 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [f02bc23dd0](https://linux-hardware.org/?probe=f02bc23dd0) | Jun 09, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [8ab2ec8df4](https://linux-hardware.org/?probe=8ab2ec8df4) | Jun 09, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [c96be9f4cd](https://linux-hardware.org/?probe=c96be9f4cd) | Jun 08, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [65e06561cf](https://linux-hardware.org/?probe=65e06561cf) | Jun 08, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [e1fdfde650](https://linux-hardware.org/?probe=e1fdfde650) | Jun 08, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [9ea0a82205](https://linux-hardware.org/?probe=9ea0a82205) | Jun 07, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [1c8078b748](https://linux-hardware.org/?probe=1c8078b748) | Jun 07, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | Notebook    | [ee9c6252ae](https://linux-hardware.org/?probe=ee9c6252ae) | Jun 07, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [646e1db08d](https://linux-hardware.org/?probe=646e1db08d) | Jun 07, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [b0435761df](https://linux-hardware.org/?probe=b0435761df) | Jun 07, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [a76212cc40](https://linux-hardware.org/?probe=a76212cc40) | Jun 07, 2023 |
| Apple         | MacBookAir4,2               | Notebook    | [afc9f50009](https://linux-hardware.org/?probe=afc9f50009) | Jun 05, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [3a1c1daa3d](https://linux-hardware.org/?probe=3a1c1daa3d) | Jun 05, 2023 |
| HP            | 83E2                        | Desktop     | [522273fe60](https://linux-hardware.org/?probe=522273fe60) | Jun 05, 2023 |
| HP            | 83E2                        | Desktop     | [3684f8562d](https://linux-hardware.org/?probe=3684f8562d) | Jun 04, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [88fbd57dac](https://linux-hardware.org/?probe=88fbd57dac) | Jun 04, 2023 |
| Dell          | 0Y5DDC A00                  | Desktop     | [5713168678](https://linux-hardware.org/?probe=5713168678) | Jun 04, 2023 |
| ASUSTek       | ROG STRIX B360-I GAMING     | Desktop     | [0c8afa948b](https://linux-hardware.org/?probe=0c8afa948b) | Jun 04, 2023 |
| MSI           | GS60 6QE                    | Notebook    | [65ea70f7fa](https://linux-hardware.org/?probe=65ea70f7fa) | Jun 03, 2023 |
| Lenovo        | ThinkStation D30 42234T7    | Desktop     | [18cb6a946b](https://linux-hardware.org/?probe=18cb6a946b) | Jun 03, 2023 |
| Acer          | TravelMate 8572T            | Notebook    | [46920007ed](https://linux-hardware.org/?probe=46920007ed) | Jun 03, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [8e46a969c7](https://linux-hardware.org/?probe=8e46a969c7) | Jun 03, 2023 |
| Intel         | DB85FL AAG89861-202         | Desktop     | [8ededa47e6](https://linux-hardware.org/?probe=8ededa47e6) | Jun 02, 2023 |
| Intel         | DB85FL AAG89861-202         | Desktop     | [7bd893ebe1](https://linux-hardware.org/?probe=7bd893ebe1) | Jun 02, 2023 |
| Toshiba       | Satellite P870              | Notebook    | [559a48c91b](https://linux-hardware.org/?probe=559a48c91b) | Jun 01, 2023 |
| Supermicro    | X11SCD-F                    | Desktop     | [4646e2fe85](https://linux-hardware.org/?probe=4646e2fe85) | Jun 01, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [0e89db7255](https://linux-hardware.org/?probe=0e89db7255) | Jun 01, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [6d7803788d](https://linux-hardware.org/?probe=6d7803788d) | Jun 01, 2023 |
| Dell          | 03NVJ6 A00                  | Desktop     | [1f295f3ec2](https://linux-hardware.org/?probe=1f295f3ec2) | Jun 01, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX DDR4    | Desktop     | [5f1045564e](https://linux-hardware.org/?probe=5f1045564e) | Jun 01, 2023 |
| Intel Clie... | LAPRC710                    | Notebook    | [ef0d589f75](https://linux-hardware.org/?probe=ef0d589f75) | May 31, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [1383313bbb](https://linux-hardware.org/?probe=1383313bbb) | May 31, 2023 |
| Gigabyte      | H270-HD3-CF                 | Desktop     | [d2912dfb69](https://linux-hardware.org/?probe=d2912dfb69) | May 31, 2023 |
| Acer          | Predator G9-793             | Notebook    | [26ea66d872](https://linux-hardware.org/?probe=26ea66d872) | May 31, 2023 |
| HP            | 8648                        | Desktop     | [11e777087a](https://linux-hardware.org/?probe=11e777087a) | May 31, 2023 |
| Acer          | E5-551G-871W                | Notebook    | [8034a1ee0b](https://linux-hardware.org/?probe=8034a1ee0b) | May 30, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [c75d4298dc](https://linux-hardware.org/?probe=c75d4298dc) | May 30, 2023 |
| Toshiba       | Satellite C665              | Notebook    | [c6149a6430](https://linux-hardware.org/?probe=c6149a6430) | May 30, 2023 |
| ASRock        | AB350M Pro4                 | Desktop     | [4f23de2827](https://linux-hardware.org/?probe=4f23de2827) | May 30, 2023 |
| HP            | EliteBook x360 1030 G3      | Convertible | [f762140894](https://linux-hardware.org/?probe=f762140894) | May 30, 2023 |
| Toshiba       | Satellite P870              | Notebook    | [2b57ca6d62](https://linux-hardware.org/?probe=2b57ca6d62) | May 29, 2023 |
| Valve         | Jupiter                     | Notebook    | [e6e97426e3](https://linux-hardware.org/?probe=e6e97426e3) | May 29, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [528f7440b7](https://linux-hardware.org/?probe=528f7440b7) | May 29, 2023 |
| HP            | 83E2                        | Desktop     | [0db8dcbc23](https://linux-hardware.org/?probe=0db8dcbc23) | May 28, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [c256cd6942](https://linux-hardware.org/?probe=c256cd6942) | May 28, 2023 |
| Apple         | MacBookPro10,2              | Notebook    | [34d96aa1df](https://linux-hardware.org/?probe=34d96aa1df) | May 28, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [3c001962b0](https://linux-hardware.org/?probe=3c001962b0) | May 28, 2023 |
| Lenovo        | IdeaPad 3 14ABA7 82RM       | Notebook    | [d83ee3fda2](https://linux-hardware.org/?probe=d83ee3fda2) | May 28, 2023 |
| HP            | 83E2                        | Desktop     | [6eea8879ca](https://linux-hardware.org/?probe=6eea8879ca) | May 28, 2023 |
| ASUSTek       | ROG STRIX X399-E GAMING     | Desktop     | [4f1ff269d2](https://linux-hardware.org/?probe=4f1ff269d2) | May 28, 2023 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [5a39bd1d78](https://linux-hardware.org/?probe=5a39bd1d78) | May 28, 2023 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [a36d2b541a](https://linux-hardware.org/?probe=a36d2b541a) | May 28, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [0ff9159d89](https://linux-hardware.org/?probe=0ff9159d89) | May 27, 2023 |
| Acer          | Aspire A315-22              | Notebook    | [18a13174aa](https://linux-hardware.org/?probe=18a13174aa) | May 27, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [9cb2973f2f](https://linux-hardware.org/?probe=9cb2973f2f) | May 27, 2023 |
| HP            | 81B9 1000                   | All in one  | [55380f30ca](https://linux-hardware.org/?probe=55380f30ca) | May 27, 2023 |
| Lenovo        | ThinkPad W541 20EGS1AR00    | Notebook    | [b7f46e7180](https://linux-hardware.org/?probe=b7f46e7180) | May 27, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [2cea143017](https://linux-hardware.org/?probe=2cea143017) | May 26, 2023 |
| Dell          | Latitude 5430               | Notebook    | [e8b9199229](https://linux-hardware.org/?probe=e8b9199229) | May 26, 2023 |
| ASUSTek       | G20AJ                       | Desktop     | [92223e639f](https://linux-hardware.org/?probe=92223e639f) | May 26, 2023 |
| ASUSTek       | G20AJ                       | Desktop     | [9a58438669](https://linux-hardware.org/?probe=9a58438669) | May 26, 2023 |
| Apple         | Mac-7BA5B2794B2CDB12 Mac... | Mini pc     | [a3456d6048](https://linux-hardware.org/?probe=a3456d6048) | May 26, 2023 |
| Lenovo        | ThinkPad W541 20EGS1AR00    | Notebook    | [a5301f505d](https://linux-hardware.org/?probe=a5301f505d) | May 25, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [f0c2fede02](https://linux-hardware.org/?probe=f0c2fede02) | May 25, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [a167562cba](https://linux-hardware.org/?probe=a167562cba) | May 25, 2023 |
| Intel         | NUC11DBBi9 M17026-403       | Mini pc     | [61970448fa](https://linux-hardware.org/?probe=61970448fa) | May 24, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [585b85e476](https://linux-hardware.org/?probe=585b85e476) | May 23, 2023 |
| Dell          | Latitude 7280               | Notebook    | [215bef2144](https://linux-hardware.org/?probe=215bef2144) | May 23, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [ca5f5ee7bf](https://linux-hardware.org/?probe=ca5f5ee7bf) | May 23, 2023 |
| MSI           | X99A GAMING 7               | Desktop     | [ec94d173a7](https://linux-hardware.org/?probe=ec94d173a7) | May 23, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [dfb369a8d2](https://linux-hardware.org/?probe=dfb369a8d2) | May 22, 2023 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [e110548f6e](https://linux-hardware.org/?probe=e110548f6e) | May 22, 2023 |
| Lenovo        | ThinkCentre M58p 7220A72    | Desktop     | [c2965aff69](https://linux-hardware.org/?probe=c2965aff69) | May 22, 2023 |
| COM1          | NBINF-X5-9G5                | Notebook    | [33aa60eaa2](https://linux-hardware.org/?probe=33aa60eaa2) | May 22, 2023 |
| COM1          | NBINF-X5-9G5                | Notebook    | [8d8c13c10c](https://linux-hardware.org/?probe=8d8c13c10c) | May 22, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [b0fac119c2](https://linux-hardware.org/?probe=b0fac119c2) | May 22, 2023 |
| Microsoft     | Surface Go 3                | Tablet      | [83e639f8e7](https://linux-hardware.org/?probe=83e639f8e7) | May 22, 2023 |
| Microsoft     | Surface Go 3                | Tablet      | [749e013179](https://linux-hardware.org/?probe=749e013179) | May 21, 2023 |
| ASUSTek       | K56CA                       | Notebook    | [6ae76c1553](https://linux-hardware.org/?probe=6ae76c1553) | May 21, 2023 |
| ASUSTek       | P8H77-M LE                  | Desktop     | [e9b749f2ba](https://linux-hardware.org/?probe=e9b749f2ba) | May 21, 2023 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [8dcb326301](https://linux-hardware.org/?probe=8dcb326301) | May 21, 2023 |
| ASUSTek       | P5B                         | Desktop     | [3effc437bb](https://linux-hardware.org/?probe=3effc437bb) | May 20, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [b59b0160fb](https://linux-hardware.org/?probe=b59b0160fb) | May 19, 2023 |
| Dell          | Inspiron 7586               | Convertible | [f4aaec3fda](https://linux-hardware.org/?probe=f4aaec3fda) | May 19, 2023 |
| MSI           | VR601                       | Notebook    | [7f9381407d](https://linux-hardware.org/?probe=7f9381407d) | May 19, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [4a9869b7a6](https://linux-hardware.org/?probe=4a9869b7a6) | May 19, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [337509e694](https://linux-hardware.org/?probe=337509e694) | May 19, 2023 |
| ASRock        | Z390 Phantom Gaming 9       | Desktop     | [5ca1acbf9b](https://linux-hardware.org/?probe=5ca1acbf9b) | May 19, 2023 |
| Dell          | 0VNP2H A01                  | Desktop     | [6e51bd033e](https://linux-hardware.org/?probe=6e51bd033e) | May 19, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [64b9ba417c](https://linux-hardware.org/?probe=64b9ba417c) | May 19, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [5c07806ab1](https://linux-hardware.org/?probe=5c07806ab1) | May 19, 2023 |
| ASUSTek       | Zephyrus M GM501GM          | Notebook    | [bf1eed0e60](https://linux-hardware.org/?probe=bf1eed0e60) | May 18, 2023 |
| MSI           | MPG B650I EDGE WIFI         | Desktop     | [c15ff8f4c4](https://linux-hardware.org/?probe=c15ff8f4c4) | May 18, 2023 |
| HP            | Pavilion 15                 | Notebook    | [fd87e57fc3](https://linux-hardware.org/?probe=fd87e57fc3) | May 18, 2023 |
| Dell          | Vostro V131                 | Notebook    | [e20ddd5bca](https://linux-hardware.org/?probe=e20ddd5bca) | May 18, 2023 |
| Dell          | Vostro V131                 | Notebook    | [7714e1784a](https://linux-hardware.org/?probe=7714e1784a) | May 18, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [4bd367b4c7](https://linux-hardware.org/?probe=4bd367b4c7) | May 17, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [09e723be6f](https://linux-hardware.org/?probe=09e723be6f) | May 17, 2023 |
| Gigabyte      | X99-Gaming 5                | Desktop     | [81eee33114](https://linux-hardware.org/?probe=81eee33114) | May 17, 2023 |
| HP            | Notebook                    | Notebook    | [8d3bd6a690](https://linux-hardware.org/?probe=8d3bd6a690) | May 17, 2023 |
| Acer          | Predator G9-793             | Notebook    | [1739ea2f45](https://linux-hardware.org/?probe=1739ea2f45) | May 17, 2023 |
| Gigabyte      | H170-Gaming 3               | Desktop     | [ae5f06df99](https://linux-hardware.org/?probe=ae5f06df99) | May 16, 2023 |
| Google        | Sumo                        | Desktop     | [1455a81901](https://linux-hardware.org/?probe=1455a81901) | May 15, 2023 |
| MSI           | Summit E14FlipEvo A13MT     | Notebook    | [60e19220b9](https://linux-hardware.org/?probe=60e19220b9) | May 15, 2023 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [fe36fee27a](https://linux-hardware.org/?probe=fe36fee27a) | May 14, 2023 |
| ASRock        | AD2700-ITX                  | Desktop     | [fe80771d2e](https://linux-hardware.org/?probe=fe80771d2e) | May 14, 2023 |
| MSI           | MAG B560M MORTAR            | Desktop     | [1556b05d13](https://linux-hardware.org/?probe=1556b05d13) | May 14, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [07bf228811](https://linux-hardware.org/?probe=07bf228811) | May 14, 2023 |
| Acer          | Aspire ES1-531              | Notebook    | [56cdac831f](https://linux-hardware.org/?probe=56cdac831f) | May 13, 2023 |
| Gigabyte      | P34V7                       | Notebook    | [90e6e5d5d9](https://linux-hardware.org/?probe=90e6e5d5d9) | May 13, 2023 |
| Unknown       | Unknown                     | Notebook    | [3fbabd3df0](https://linux-hardware.org/?probe=3fbabd3df0) | May 11, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [393b2da4bc](https://linux-hardware.org/?probe=393b2da4bc) | May 11, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [3dc1af6df9](https://linux-hardware.org/?probe=3dc1af6df9) | May 11, 2023 |
| Acer          | Predator G9-793             | Notebook    | [95595808a8](https://linux-hardware.org/?probe=95595808a8) | May 11, 2023 |
| AOpen         | aA70Mx-VW R1.01 55DE8100... | Desktop     | [400b616f1c](https://linux-hardware.org/?probe=400b616f1c) | May 10, 2023 |
| Dell          | 03NVJ6 A02                  | Desktop     | [9f509a2647](https://linux-hardware.org/?probe=9f509a2647) | May 10, 2023 |
| Toshiba       | Satellite M60               | Notebook    | [91437556e8](https://linux-hardware.org/?probe=91437556e8) | May 09, 2023 |
| Toshiba       | Satellite M60               | Notebook    | [39b2bcd3a5](https://linux-hardware.org/?probe=39b2bcd3a5) | May 09, 2023 |
| Dell          | Inspiron N5010              | Notebook    | [5dd91a589b](https://linux-hardware.org/?probe=5dd91a589b) | May 09, 2023 |
| Lenovo        | ThinkPad 11e Yoga Gen 6 ... | Convertible | [2a7a243899](https://linux-hardware.org/?probe=2a7a243899) | May 09, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [503204d798](https://linux-hardware.org/?probe=503204d798) | May 09, 2023 |
| Lenovo        | ThinkPad 11e Yoga Gen 6 ... | Convertible | [c7a298018f](https://linux-hardware.org/?probe=c7a298018f) | May 08, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [def28849c6](https://linux-hardware.org/?probe=def28849c6) | May 08, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [f23fb5cca0](https://linux-hardware.org/?probe=f23fb5cca0) | May 08, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [36f1aa431d](https://linux-hardware.org/?probe=36f1aa431d) | May 08, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [3daf4fbc68](https://linux-hardware.org/?probe=3daf4fbc68) | May 07, 2023 |
| Lenovo        | 30C0 SDK0J40697 WIN 3305... | Desktop     | [94ab5e431c](https://linux-hardware.org/?probe=94ab5e431c) | May 07, 2023 |
| Dell          | Inspiron N5010              | Notebook    | [2a418b4e97](https://linux-hardware.org/?probe=2a418b4e97) | May 07, 2023 |
| MSI           | MAG B560M MORTAR            | Desktop     | [db1ad69341](https://linux-hardware.org/?probe=db1ad69341) | May 06, 2023 |
| Lenovo        | Mixx-700-12ISK 80QL         | Notebook    | [14bc666ec3](https://linux-hardware.org/?probe=14bc666ec3) | May 06, 2023 |
| MSI           | MAG B560M MORTAR            | Desktop     | [8c41580881](https://linux-hardware.org/?probe=8c41580881) | May 06, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [f743e9293e](https://linux-hardware.org/?probe=f743e9293e) | May 06, 2023 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [1515a37b97](https://linux-hardware.org/?probe=1515a37b97) | May 06, 2023 |
| Toshiba       | PORTEGE Z30t-A              | Notebook    | [18cc14eee0](https://linux-hardware.org/?probe=18cc14eee0) | May 05, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [fec056072d](https://linux-hardware.org/?probe=fec056072d) | May 05, 2023 |
| Gigabyte      | X99-Gaming 5                | Desktop     | [e1d1bdef81](https://linux-hardware.org/?probe=e1d1bdef81) | May 04, 2023 |
| System76      | Oryx Pro                    | Notebook    | [cae9fadc38](https://linux-hardware.org/?probe=cae9fadc38) | May 04, 2023 |
| Acer          | Predator G9-793             | Notebook    | [b3bd1a1031](https://linux-hardware.org/?probe=b3bd1a1031) | May 03, 2023 |
| Lenovo        | Yoga 510-14ISK 80S7         | Convertible | [47ff74d363](https://linux-hardware.org/?probe=47ff74d363) | May 03, 2023 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [a23cace014](https://linux-hardware.org/?probe=a23cace014) | May 02, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [3742def878](https://linux-hardware.org/?probe=3742def878) | May 02, 2023 |
| Intel Clie... | LAPRC510                    | Notebook    | [40c181b615](https://linux-hardware.org/?probe=40c181b615) | May 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [925b5748b9](https://linux-hardware.org/?probe=925b5748b9) | May 01, 2023 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [e812a255a4](https://linux-hardware.org/?probe=e812a255a4) | May 01, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [fa4e32fe2c](https://linux-hardware.org/?probe=fa4e32fe2c) | May 01, 2023 |
| ASRock        | B660M-HDV                   | Desktop     | [a137e6ab62](https://linux-hardware.org/?probe=a137e6ab62) | May 01, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [7fb1708706](https://linux-hardware.org/?probe=7fb1708706) | May 01, 2023 |
| Lenovo        | ThinkPad X260 20F5002NAU    | Notebook    | [7fcb72c132](https://linux-hardware.org/?probe=7fcb72c132) | May 01, 2023 |
| ASUSTek       | X501A1                      | Notebook    | [66b02cc148](https://linux-hardware.org/?probe=66b02cc148) | Apr 30, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [7a86bdd993](https://linux-hardware.org/?probe=7a86bdd993) | Apr 30, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [6206b317f2](https://linux-hardware.org/?probe=6206b317f2) | Apr 30, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [01311e320c](https://linux-hardware.org/?probe=01311e320c) | Apr 30, 2023 |
| MSI           | MPG B650I EDGE WIFI         | Desktop     | [eda4874295](https://linux-hardware.org/?probe=eda4874295) | Apr 30, 2023 |
| Apple         | Mac-F2208EC8                | Mini pc     | [6bad65ad2d](https://linux-hardware.org/?probe=6bad65ad2d) | Apr 29, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [081551c776](https://linux-hardware.org/?probe=081551c776) | Apr 29, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [ee288626f4](https://linux-hardware.org/?probe=ee288626f4) | Apr 29, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI D... | Desktop     | [c880b8dcdd](https://linux-hardware.org/?probe=c880b8dcdd) | Apr 29, 2023 |
| ASUSTek       | PRIME A520M-E               | Desktop     | [048fda2c60](https://linux-hardware.org/?probe=048fda2c60) | Apr 28, 2023 |
| MSI           | MPG X570S CARBON MAX WIF... | Desktop     | [d472fb0a32](https://linux-hardware.org/?probe=d472fb0a32) | Apr 28, 2023 |
| Intel         | DZ68DB AAG27985-101         | Desktop     | [b3323dcc11](https://linux-hardware.org/?probe=b3323dcc11) | Apr 28, 2023 |
| ASRock        | X470 Master SLI             | Desktop     | [cded55a936](https://linux-hardware.org/?probe=cded55a936) | Apr 28, 2023 |
| Lenovo        | ThinkPad L13 Yoga 20R6S1... | Convertible | [c01483e50f](https://linux-hardware.org/?probe=c01483e50f) | Apr 28, 2023 |
| Acer          | ConceptD CN315-71P          | Notebook    | [3cc902ff5c](https://linux-hardware.org/?probe=3cc902ff5c) | Apr 28, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | Notebook    | [73141c5006](https://linux-hardware.org/?probe=73141c5006) | Apr 27, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | Notebook    | [0cb164ac2f](https://linux-hardware.org/?probe=0cb164ac2f) | Apr 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [3f44947226](https://linux-hardware.org/?probe=3f44947226) | Apr 27, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [198fa6162e](https://linux-hardware.org/?probe=198fa6162e) | Apr 27, 2023 |
| ASUSTek       | X99-A                       | Desktop     | [6788eea8d2](https://linux-hardware.org/?probe=6788eea8d2) | Apr 26, 2023 |
| ASUSTek       | X550CA                      | Notebook    | [a63293fe36](https://linux-hardware.org/?probe=a63293fe36) | Apr 26, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [b8b51b29ef](https://linux-hardware.org/?probe=b8b51b29ef) | Apr 25, 2023 |
| Dell          | Inspiron 5548               | Notebook    | [42908a7ab7](https://linux-hardware.org/?probe=42908a7ab7) | Apr 25, 2023 |
| Dell          | System XPS L702X            | Notebook    | [d1aa167e90](https://linux-hardware.org/?probe=d1aa167e90) | Apr 25, 2023 |
| Acer          | E5-551G-871W                | Notebook    | [2730a30d89](https://linux-hardware.org/?probe=2730a30d89) | Apr 25, 2023 |
| MSI           | GE72VR 6RF                  | Notebook    | [89cb17ee72](https://linux-hardware.org/?probe=89cb17ee72) | Apr 25, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [373372bf75](https://linux-hardware.org/?probe=373372bf75) | Apr 25, 2023 |
| Dell          | 08WXMX A02                  | Desktop     | [5f68c6a285](https://linux-hardware.org/?probe=5f68c6a285) | Apr 24, 2023 |
| MSI           | Z97S SLI Krait Edition      | Desktop     | [6ed93f8338](https://linux-hardware.org/?probe=6ed93f8338) | Apr 24, 2023 |
| HP            | 0AA8h                       | Desktop     | [071191ddf3](https://linux-hardware.org/?probe=071191ddf3) | Apr 23, 2023 |
| Dell          | Precision 5520              | Notebook    | [4d1dd8b673](https://linux-hardware.org/?probe=4d1dd8b673) | Apr 23, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [ef59f5ff9b](https://linux-hardware.org/?probe=ef59f5ff9b) | Apr 23, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [5da3166132](https://linux-hardware.org/?probe=5da3166132) | Apr 22, 2023 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | Desktop     | [03a331aa44](https://linux-hardware.org/?probe=03a331aa44) | Apr 22, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [80312ab34c](https://linux-hardware.org/?probe=80312ab34c) | Apr 22, 2023 |
| Shuttle       | DS10U                       | Desktop     | [ffcce61d82](https://linux-hardware.org/?probe=ffcce61d82) | Apr 22, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [1dd1bcd00e](https://linux-hardware.org/?probe=1dd1bcd00e) | Apr 22, 2023 |
| Valve         | Jupiter                     | Notebook    | [b5be7aa6ff](https://linux-hardware.org/?probe=b5be7aa6ff) | Apr 21, 2023 |
| ASRock        | AD2700-ITX                  | Desktop     | [e688e656cd](https://linux-hardware.org/?probe=e688e656cd) | Apr 21, 2023 |
| Shuttle       | FS81                        | Desktop     | [051b7f4753](https://linux-hardware.org/?probe=051b7f4753) | Apr 20, 2023 |
| Acer          | Predator G9-793             | Notebook    | [664d6de816](https://linux-hardware.org/?probe=664d6de816) | Apr 20, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | Notebook    | [8daf9af9b5](https://linux-hardware.org/?probe=8daf9af9b5) | Apr 20, 2023 |
| Acer          | Aspire 5733Z                | Notebook    | [de205c8c62](https://linux-hardware.org/?probe=de205c8c62) | Apr 19, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [7da02a75b5](https://linux-hardware.org/?probe=7da02a75b5) | Apr 18, 2023 |
| ASRock        | Z170 Gaming K4              | Desktop     | [cbd09f0f67](https://linux-hardware.org/?probe=cbd09f0f67) | Apr 18, 2023 |
| Shuttle       | DS10U                       | Desktop     | [b25013d04f](https://linux-hardware.org/?probe=b25013d04f) | Apr 18, 2023 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [07a49303af](https://linux-hardware.org/?probe=07a49303af) | Apr 17, 2023 |
| Toshiba       | Satellite E45-B             | Notebook    | [ec0bb6bfc6](https://linux-hardware.org/?probe=ec0bb6bfc6) | Apr 17, 2023 |
| MSI           | MS-B0A41                    | Desktop     | [5950f6e73c](https://linux-hardware.org/?probe=5950f6e73c) | Apr 17, 2023 |
| Dell          | Inspiron 13-5378            | Notebook    | [bcb18ae818](https://linux-hardware.org/?probe=bcb18ae818) | Apr 17, 2023 |
| HP            | Pavilion dv6                | Notebook    | [fc41269cf8](https://linux-hardware.org/?probe=fc41269cf8) | Apr 16, 2023 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [1fa07cd218](https://linux-hardware.org/?probe=1fa07cd218) | Apr 16, 2023 |
| HP            | 212B                        | Desktop     | [343f1f5eba](https://linux-hardware.org/?probe=343f1f5eba) | Apr 16, 2023 |
| Dell          | Latitude 5420               | Notebook    | [03247dc98c](https://linux-hardware.org/?probe=03247dc98c) | Apr 16, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [71e03c5459](https://linux-hardware.org/?probe=71e03c5459) | Apr 15, 2023 |
| Gigabyte      | X79-UD5                     | Desktop     | [369c3cfdb2](https://linux-hardware.org/?probe=369c3cfdb2) | Apr 15, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [3470b35550](https://linux-hardware.org/?probe=3470b35550) | Apr 15, 2023 |
| Lenovo        | ThinkCentre M58p 7220A72    | Desktop     | [2be395131f](https://linux-hardware.org/?probe=2be395131f) | Apr 15, 2023 |
| Lenovo        | ThinkCentre M58p 7220A72    | Desktop     | [0ca4b7045e](https://linux-hardware.org/?probe=0ca4b7045e) | Apr 15, 2023 |
| Toshiba       | QOSMIO F750                 | Notebook    | [590801670a](https://linux-hardware.org/?probe=590801670a) | Apr 15, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [ffa823032e](https://linux-hardware.org/?probe=ffa823032e) | Apr 14, 2023 |
| Toshiba       | Satellite L850              | Notebook    | [dc9e77bd65](https://linux-hardware.org/?probe=dc9e77bd65) | Apr 14, 2023 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [fe75c98b15](https://linux-hardware.org/?probe=fe75c98b15) | Apr 14, 2023 |
| Lenovo        | ThinkStation D30 42234T7    | Desktop     | [7730eb04fa](https://linux-hardware.org/?probe=7730eb04fa) | Apr 14, 2023 |
| Dell          | Latitude E6540              | Notebook    | [61ab891b01](https://linux-hardware.org/?probe=61ab891b01) | Apr 13, 2023 |
| Dell          | Vostro 7590                 | Notebook    | [f759d8ab72](https://linux-hardware.org/?probe=f759d8ab72) | Apr 13, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [8e641b5fd5](https://linux-hardware.org/?probe=8e641b5fd5) | Apr 13, 2023 |
| Acer          | Aspire 5720Z                | Notebook    | [1ac7eb0d0c](https://linux-hardware.org/?probe=1ac7eb0d0c) | Apr 13, 2023 |
| ECS           | H61H2-MV                    | Desktop     | [5a3fbafb75](https://linux-hardware.org/?probe=5a3fbafb75) | Apr 12, 2023 |
| HP            | 843B                        | Desktop     | [90de5c4ff1](https://linux-hardware.org/?probe=90de5c4ff1) | Apr 12, 2023 |
| Gigabyte      | X79-UP4                     | Desktop     | [8f9b60caf3](https://linux-hardware.org/?probe=8f9b60caf3) | Apr 12, 2023 |
| HP            | 3646h                       | Desktop     | [c36653d824](https://linux-hardware.org/?probe=c36653d824) | Apr 12, 2023 |
| ASRock        | X370 Gaming-ITX/ac          | Desktop     | [29ed28536e](https://linux-hardware.org/?probe=29ed28536e) | Apr 12, 2023 |
| Acer          | TM6495T                     | Notebook    | [435ae018a2](https://linux-hardware.org/?probe=435ae018a2) | Apr 11, 2023 |
| Lenovo        | ThinkPad L13 Yoga 20R6S1... | Convertible | [8ca7e7c5ad](https://linux-hardware.org/?probe=8ca7e7c5ad) | Apr 10, 2023 |
| MSI           | H81M-P33                    | Desktop     | [129abe0b90](https://linux-hardware.org/?probe=129abe0b90) | Apr 10, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [f9382ece8e](https://linux-hardware.org/?probe=f9382ece8e) | Apr 10, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [6dd2d460aa](https://linux-hardware.org/?probe=6dd2d460aa) | Apr 10, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [7d5fb1a311](https://linux-hardware.org/?probe=7d5fb1a311) | Apr 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [2765290b8c](https://linux-hardware.org/?probe=2765290b8c) | Apr 09, 2023 |
| Lenovo        | ThinkPad E460 20ETA05KAU    | Notebook    | [a8090f51bc](https://linux-hardware.org/?probe=a8090f51bc) | Apr 09, 2023 |
| SYWZ          | S210H Series                | Desktop     | [5989537064](https://linux-hardware.org/?probe=5989537064) | Apr 09, 2023 |
| Dell          | Inspiron 1720               | Notebook    | [a2e3b07f6b](https://linux-hardware.org/?probe=a2e3b07f6b) | Apr 09, 2023 |
| ASUSTek       | PRIME Z590-P WIFI           | Desktop     | [e579aabfdb](https://linux-hardware.org/?probe=e579aabfdb) | Apr 09, 2023 |
| Samsung       | Galaxy Book 12 LTE          | Tablet      | [d866c03132](https://linux-hardware.org/?probe=d866c03132) | Apr 08, 2023 |
| Dell          | Latitude E5470              | Notebook    | [3e49e9c541](https://linux-hardware.org/?probe=3e49e9c541) | Apr 08, 2023 |
| MSI           | B550M-A PRO                 | Desktop     | [e3fcf877c0](https://linux-hardware.org/?probe=e3fcf877c0) | Apr 08, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [5aad90904c](https://linux-hardware.org/?probe=5aad90904c) | Apr 07, 2023 |
| Acer          | TravelMate 8572T            | Notebook    | [04f50662d8](https://linux-hardware.org/?probe=04f50662d8) | Apr 07, 2023 |
| Toshiba       | Satellite P70-A             | Notebook    | [6ffb7a79ef](https://linux-hardware.org/?probe=6ffb7a79ef) | Apr 06, 2023 |
| MSI           | MS-B1831                    | Desktop     | [9ea2ec4f47](https://linux-hardware.org/?probe=9ea2ec4f47) | Apr 06, 2023 |
| MSI           | A88XM-E35 V2                | Desktop     | [bf4c16404e](https://linux-hardware.org/?probe=bf4c16404e) | Apr 06, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [be741560b8](https://linux-hardware.org/?probe=be741560b8) | Apr 06, 2023 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [7644d4a8fa](https://linux-hardware.org/?probe=7644d4a8fa) | Apr 06, 2023 |
| HP            | Pavilion dv6                | Notebook    | [be695e2cd4](https://linux-hardware.org/?probe=be695e2cd4) | Apr 06, 2023 |
| ASUSTek       | H87-PRO                     | Desktop     | [085dc66a77](https://linux-hardware.org/?probe=085dc66a77) | Apr 05, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [258f32d502](https://linux-hardware.org/?probe=258f32d502) | Apr 05, 2023 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [7e5be74f0b](https://linux-hardware.org/?probe=7e5be74f0b) | Apr 05, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [473a8c1d7b](https://linux-hardware.org/?probe=473a8c1d7b) | Apr 05, 2023 |
| Shenzhen M... | F7BFD                       | Desktop     | [7f6103b394](https://linux-hardware.org/?probe=7f6103b394) | Apr 05, 2023 |
| Shenzhen M... | F7BFD                       | Desktop     | [ac039ed7e6](https://linux-hardware.org/?probe=ac039ed7e6) | Apr 05, 2023 |
| HP            | Notebook                    | Notebook    | [50c03e608d](https://linux-hardware.org/?probe=50c03e608d) | Apr 05, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [56079f49e3](https://linux-hardware.org/?probe=56079f49e3) | Apr 04, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [4ef5210167](https://linux-hardware.org/?probe=4ef5210167) | Apr 04, 2023 |
| HP            | 843B                        | Desktop     | [aa679005d3](https://linux-hardware.org/?probe=aa679005d3) | Apr 04, 2023 |
| HP            | 843B                        | Desktop     | [ba686ac542](https://linux-hardware.org/?probe=ba686ac542) | Apr 04, 2023 |
| Shuttle       | DS10U                       | Desktop     | [a35fd102f2](https://linux-hardware.org/?probe=a35fd102f2) | Apr 04, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [3a87280f55](https://linux-hardware.org/?probe=3a87280f55) | Apr 03, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [1cb5977d82](https://linux-hardware.org/?probe=1cb5977d82) | Apr 03, 2023 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [9e25dfd6bb](https://linux-hardware.org/?probe=9e25dfd6bb) | Apr 02, 2023 |
| ASRock        | FM2A55M-DGS                 | Desktop     | [250384a794](https://linux-hardware.org/?probe=250384a794) | Apr 02, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [d016e78eab](https://linux-hardware.org/?probe=d016e78eab) | Apr 02, 2023 |
| Acer          | EQ45LM                      | Desktop     | [5bafe47784](https://linux-hardware.org/?probe=5bafe47784) | Apr 02, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [89622c73d1](https://linux-hardware.org/?probe=89622c73d1) | Apr 02, 2023 |
| Gigabyte      | X99-UD3-CF                  | Desktop     | [82a3b55b60](https://linux-hardware.org/?probe=82a3b55b60) | Apr 02, 2023 |
| Dell          | 09M8Y8 A01                  | Desktop     | [17d5390549](https://linux-hardware.org/?probe=17d5390549) | Apr 01, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [7beef34820](https://linux-hardware.org/?probe=7beef34820) | Apr 01, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [8357ff8cf5](https://linux-hardware.org/?probe=8357ff8cf5) | Apr 01, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [89ca656f30](https://linux-hardware.org/?probe=89ca656f30) | Apr 01, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [2a881cc01e](https://linux-hardware.org/?probe=2a881cc01e) | Apr 01, 2023 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [2be0fa6524](https://linux-hardware.org/?probe=2be0fa6524) | Apr 01, 2023 |
| Lenovo        | ThinkStation D30 42234T7    | Desktop     | [47f6f4653b](https://linux-hardware.org/?probe=47f6f4653b) | Mar 31, 2023 |
| Unknown       | Unknown                     | Desktop     | [1f64d2db28](https://linux-hardware.org/?probe=1f64d2db28) | Mar 31, 2023 |
| ASRock        | FM2A55M-DGS                 | Desktop     | [3ab2e2c720](https://linux-hardware.org/?probe=3ab2e2c720) | Mar 31, 2023 |
| Gigabyte      | B85M-HD3                    | Desktop     | [3d24b75a10](https://linux-hardware.org/?probe=3d24b75a10) | Mar 31, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [05d42527df](https://linux-hardware.org/?probe=05d42527df) | Mar 31, 2023 |
| Dell          | 09M8Y8 A01                  | Desktop     | [2c13e40cd2](https://linux-hardware.org/?probe=2c13e40cd2) | Mar 30, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [92981c741d](https://linux-hardware.org/?probe=92981c741d) | Mar 30, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [af4901f141](https://linux-hardware.org/?probe=af4901f141) | Mar 30, 2023 |
| HP            | ProBook 450 G5              | Notebook    | [89dfecad7e](https://linux-hardware.org/?probe=89dfecad7e) | Mar 30, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [8d0c93e1a8](https://linux-hardware.org/?probe=8d0c93e1a8) | Mar 30, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [881f70cb12](https://linux-hardware.org/?probe=881f70cb12) | Mar 30, 2023 |
| Dell          | Precision 5550              | Notebook    | [c7244f1e31](https://linux-hardware.org/?probe=c7244f1e31) | Mar 30, 2023 |
| Dell          | G3 3590                     | Notebook    | [f61ce9bb82](https://linux-hardware.org/?probe=f61ce9bb82) | Mar 28, 2023 |
| Gigabyte      | H55M-USB3                   | Desktop     | [140b984b9f](https://linux-hardware.org/?probe=140b984b9f) | Mar 28, 2023 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [5064a5267e](https://linux-hardware.org/?probe=5064a5267e) | Mar 28, 2023 |
| MSI           | Delta 15 A5EFK              | Notebook    | [6f4e3ec28b](https://linux-hardware.org/?probe=6f4e3ec28b) | Mar 28, 2023 |
| MSI           | Delta 15 A5EFK              | Notebook    | [9dd1b67b2f](https://linux-hardware.org/?probe=9dd1b67b2f) | Mar 28, 2023 |
| Lenovo        | 0x36A017AA SDK0J40709 WI... | Desktop     | [562426633d](https://linux-hardware.org/?probe=562426633d) | Mar 28, 2023 |
| ASRock        | FM2A88X+ Killer             | Desktop     | [6180e562dd](https://linux-hardware.org/?probe=6180e562dd) | Mar 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [de6a63685a](https://linux-hardware.org/?probe=de6a63685a) | Mar 27, 2023 |
| Lenovo        | ThinkStation D30 42234T7    | Desktop     | [cfb8c9d396](https://linux-hardware.org/?probe=cfb8c9d396) | Mar 27, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [e67759f49b](https://linux-hardware.org/?probe=e67759f49b) | Mar 26, 2023 |
| HP            | 0B54h D                     | Desktop     | [540caaf04c](https://linux-hardware.org/?probe=540caaf04c) | Mar 26, 2023 |
| ASUSTek       | Maximus VIII HERO ALPHA     | Desktop     | [cc262bb41a](https://linux-hardware.org/?probe=cc262bb41a) | Mar 26, 2023 |
| ASRock        | AD525PV3                    | Desktop     | [84545fd0ea](https://linux-hardware.org/?probe=84545fd0ea) | Mar 25, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [8060aec150](https://linux-hardware.org/?probe=8060aec150) | Mar 25, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [5acd2b0492](https://linux-hardware.org/?probe=5acd2b0492) | Mar 25, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [5312ec3cc9](https://linux-hardware.org/?probe=5312ec3cc9) | Mar 25, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [1503a33123](https://linux-hardware.org/?probe=1503a33123) | Mar 24, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [9edd5002f0](https://linux-hardware.org/?probe=9edd5002f0) | Mar 24, 2023 |
| HP            | ProBook 470 G5              | Notebook    | [1672158957](https://linux-hardware.org/?probe=1672158957) | Mar 24, 2023 |
| HP            | ProBook 470 G5              | Notebook    | [383b333f72](https://linux-hardware.org/?probe=383b333f72) | Mar 24, 2023 |
| ReachingTe... | DreamQuest Pro 2022         | Mini pc     | [696a898cd2](https://linux-hardware.org/?probe=696a898cd2) | Mar 24, 2023 |
| ASRock        | AD525PV3                    | Desktop     | [0749ec7b44](https://linux-hardware.org/?probe=0749ec7b44) | Mar 23, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | Notebook    | [fc1c184c05](https://linux-hardware.org/?probe=fc1c184c05) | Mar 23, 2023 |
| AMI           | Intel                       | Desktop     | [5e7b21c227](https://linux-hardware.org/?probe=5e7b21c227) | Mar 23, 2023 |
| Acer          | ConceptD CN315-71P          | Notebook    | [14b71e7a26](https://linux-hardware.org/?probe=14b71e7a26) | Mar 22, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [10269c811b](https://linux-hardware.org/?probe=10269c811b) | Mar 22, 2023 |
| MSI           | MS-7142                     | Desktop     | [1cb67ac1ca](https://linux-hardware.org/?probe=1cb67ac1ca) | Mar 22, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [61025e6e8b](https://linux-hardware.org/?probe=61025e6e8b) | Mar 22, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [80d1a2d67d](https://linux-hardware.org/?probe=80d1a2d67d) | Mar 22, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [eb718edb23](https://linux-hardware.org/?probe=eb718edb23) | Mar 22, 2023 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [8c50d5ae87](https://linux-hardware.org/?probe=8c50d5ae87) | Mar 21, 2023 |
| Acer          | Spin SP314-54N              | Convertible | [4f2e83ab00](https://linux-hardware.org/?probe=4f2e83ab00) | Mar 21, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [a1e76aa5c1](https://linux-hardware.org/?probe=a1e76aa5c1) | Mar 21, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [16253cadcf](https://linux-hardware.org/?probe=16253cadcf) | Mar 21, 2023 |
| Dell          | Latitude E6520              | Notebook    | [857fdb4095](https://linux-hardware.org/?probe=857fdb4095) | Mar 21, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [c2191470c7](https://linux-hardware.org/?probe=c2191470c7) | Mar 21, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [6f98b39459](https://linux-hardware.org/?probe=6f98b39459) | Mar 21, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [c5c907b643](https://linux-hardware.org/?probe=c5c907b643) | Mar 21, 2023 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [ad4c43dd09](https://linux-hardware.org/?probe=ad4c43dd09) | Mar 21, 2023 |
| Apple         | Mac-F2208EC8                | Mini pc     | [4b47e3ed6c](https://linux-hardware.org/?probe=4b47e3ed6c) | Mar 20, 2023 |
| Gigabyte      | H610M H DDR4                | Desktop     | [b7cf9d91ee](https://linux-hardware.org/?probe=b7cf9d91ee) | Mar 20, 2023 |
| Acer          | Spin SP314-54N              | Convertible | [40d6f69489](https://linux-hardware.org/?probe=40d6f69489) | Mar 20, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [c63a27da32](https://linux-hardware.org/?probe=c63a27da32) | Mar 20, 2023 |
| ASUSTek       | Maximus Extreme             | Desktop     | [c6215ec2f3](https://linux-hardware.org/?probe=c6215ec2f3) | Mar 20, 2023 |
| ASUSTek       | PRIME B250M-K               | Desktop     | [99cb000a4e](https://linux-hardware.org/?probe=99cb000a4e) | Mar 19, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [67c8f562e5](https://linux-hardware.org/?probe=67c8f562e5) | Mar 18, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [dc411c9ce3](https://linux-hardware.org/?probe=dc411c9ce3) | Mar 18, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | Notebook    | [786fded1ce](https://linux-hardware.org/?probe=786fded1ce) | Mar 17, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [49bb337156](https://linux-hardware.org/?probe=49bb337156) | Mar 17, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [d762fe2bf3](https://linux-hardware.org/?probe=d762fe2bf3) | Mar 17, 2023 |
| Valve         | Jupiter                     | Notebook    | [8f51ab644e](https://linux-hardware.org/?probe=8f51ab644e) | Mar 17, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [b4483fd4e2](https://linux-hardware.org/?probe=b4483fd4e2) | Mar 16, 2023 |
| Dell          | G3 3590                     | Notebook    | [9ef42643d8](https://linux-hardware.org/?probe=9ef42643d8) | Mar 16, 2023 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [a4c449eef4](https://linux-hardware.org/?probe=a4c449eef4) | Mar 16, 2023 |
| HP            | ProBook 430 G8 Notebook ... | Notebook    | [ca6ab3c197](https://linux-hardware.org/?probe=ca6ab3c197) | Mar 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [684375b9a0](https://linux-hardware.org/?probe=684375b9a0) | Mar 16, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | Notebook    | [787dfaa7d4](https://linux-hardware.org/?probe=787dfaa7d4) | Mar 15, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [12e9972d5a](https://linux-hardware.org/?probe=12e9972d5a) | Mar 15, 2023 |
| Huanan        | X99-AD3 GAMING V2.0         | Desktop     | [0586633e29](https://linux-hardware.org/?probe=0586633e29) | Mar 15, 2023 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [b324afc6f8](https://linux-hardware.org/?probe=b324afc6f8) | Mar 14, 2023 |
| Intel         | DB85FL AAG89861-203         | Desktop     | [e17dae3447](https://linux-hardware.org/?probe=e17dae3447) | Mar 14, 2023 |
| Intel         | DB85FL AAG89861-203         | Desktop     | [f1004a32e1](https://linux-hardware.org/?probe=f1004a32e1) | Mar 14, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [59478f318e](https://linux-hardware.org/?probe=59478f318e) | Mar 14, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [954055245e](https://linux-hardware.org/?probe=954055245e) | Mar 14, 2023 |
| Dell          | Inspiron M5010              | Notebook    | [0a5d0c9169](https://linux-hardware.org/?probe=0a5d0c9169) | Mar 14, 2023 |
| QIYIDA        | X99-H9 V2.0                 | Desktop     | [0f440670f2](https://linux-hardware.org/?probe=0f440670f2) | Mar 14, 2023 |
| Acer          | Aspire E5-511               | Notebook    | [5343f73c67](https://linux-hardware.org/?probe=5343f73c67) | Mar 13, 2023 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [61af17e1cd](https://linux-hardware.org/?probe=61af17e1cd) | Mar 13, 2023 |
| Apple         | Mac-7BA5B2794B2CDB12 Mac... | Mini pc     | [cd75bab781](https://linux-hardware.org/?probe=cd75bab781) | Mar 13, 2023 |
| Fanless Mi... | Rev GMLR1                   | Mini pc     | [4ac1bccada](https://linux-hardware.org/?probe=4ac1bccada) | Mar 13, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | Notebook    | [b5d8bdc57d](https://linux-hardware.org/?probe=b5d8bdc57d) | Mar 12, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | Notebook    | [4525fa2931](https://linux-hardware.org/?probe=4525fa2931) | Mar 12, 2023 |
| Lenovo        | ThinkPad E590 20NBA000AU    | Notebook    | [47bfd44610](https://linux-hardware.org/?probe=47bfd44610) | Mar 12, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [e45386803e](https://linux-hardware.org/?probe=e45386803e) | Mar 12, 2023 |
| Gigabyte      | Z590I AORUS ULTRA           | Desktop     | [47ea9647d3](https://linux-hardware.org/?probe=47ea9647d3) | Mar 12, 2023 |
| Gigabyte      | X670E AORUS XTREME          | Desktop     | [83cb566647](https://linux-hardware.org/?probe=83cb566647) | Mar 12, 2023 |
| ASUSTek       | A88X-PLUS                   | Desktop     | [3624df5386](https://linux-hardware.org/?probe=3624df5386) | Mar 11, 2023 |
| Maibenben     | P748                        | Notebook    | [a44d1bb8e4](https://linux-hardware.org/?probe=a44d1bb8e4) | Mar 11, 2023 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [23b5dbe59d](https://linux-hardware.org/?probe=23b5dbe59d) | Mar 11, 2023 |
| ASRock        | 990FX Killer                | Desktop     | [23bd30e79e](https://linux-hardware.org/?probe=23bd30e79e) | Mar 11, 2023 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [46c1d399ac](https://linux-hardware.org/?probe=46c1d399ac) | Mar 11, 2023 |
| Gigabyte      | Z590 AORUS ELITE            | Desktop     | [790a51e99f](https://linux-hardware.org/?probe=790a51e99f) | Mar 11, 2023 |
| Acer          | Veriton X4640G V:1.1        | Desktop     | [dd3e15feee](https://linux-hardware.org/?probe=dd3e15feee) | Mar 10, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [35ab0f32c5](https://linux-hardware.org/?probe=35ab0f32c5) | Mar 10, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [9d14bee09f](https://linux-hardware.org/?probe=9d14bee09f) | Mar 10, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [e27d91ea6f](https://linux-hardware.org/?probe=e27d91ea6f) | Mar 09, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [790877da61](https://linux-hardware.org/?probe=790877da61) | Mar 09, 2023 |
| Lenovo        | ThinkPad L13 Yoga 20R6S1... | Convertible | [970e94ad07](https://linux-hardware.org/?probe=970e94ad07) | Mar 09, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [ded87de736](https://linux-hardware.org/?probe=ded87de736) | Mar 09, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [7413353e38](https://linux-hardware.org/?probe=7413353e38) | Mar 09, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [89647ee142](https://linux-hardware.org/?probe=89647ee142) | Mar 08, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [fd0eabacbf](https://linux-hardware.org/?probe=fd0eabacbf) | Mar 08, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [dfe7f75406](https://linux-hardware.org/?probe=dfe7f75406) | Mar 08, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [ffaa232ea2](https://linux-hardware.org/?probe=ffaa232ea2) | Mar 08, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [916862cd66](https://linux-hardware.org/?probe=916862cd66) | Mar 08, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | Notebook    | [54ad36532c](https://linux-hardware.org/?probe=54ad36532c) | Mar 07, 2023 |
| HP            | Stream Laptop 11-ah1XX      | Notebook    | [61e3840465](https://linux-hardware.org/?probe=61e3840465) | Mar 07, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [70eb1caef5](https://linux-hardware.org/?probe=70eb1caef5) | Mar 07, 2023 |
| HP            | Compaq Presario C700        | Notebook    | [fe1c136403](https://linux-hardware.org/?probe=fe1c136403) | Mar 06, 2023 |
| HP            | Compaq Presario C700        | Notebook    | [0b29805ec8](https://linux-hardware.org/?probe=0b29805ec8) | Mar 06, 2023 |
| HP            | ENVY 17                     | Notebook    | [ce2278a2e4](https://linux-hardware.org/?probe=ce2278a2e4) | Mar 05, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [dfc84acc1a](https://linux-hardware.org/?probe=dfc84acc1a) | Mar 05, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [3d1560d3d1](https://linux-hardware.org/?probe=3d1560d3d1) | Mar 05, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [7d1b3a73f9](https://linux-hardware.org/?probe=7d1b3a73f9) | Mar 05, 2023 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [9de6b65a45](https://linux-hardware.org/?probe=9de6b65a45) | Mar 04, 2023 |
| Google        | Ultima                      | Notebook    | [5e42f67839](https://linux-hardware.org/?probe=5e42f67839) | Mar 04, 2023 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [fca1ca2628](https://linux-hardware.org/?probe=fca1ca2628) | Mar 04, 2023 |
| SONIQ Digi... | Soniq 11.6inch Convertib... | Convertible | [e0b2fdc347](https://linux-hardware.org/?probe=e0b2fdc347) | Mar 04, 2023 |
| Valve         | Jupiter                     | Notebook    | [65a9e7ef52](https://linux-hardware.org/?probe=65a9e7ef52) | Mar 04, 2023 |
| Intel         | NUC12EDBi7 M27908-302       | Mini pc     | [bb51e864a7](https://linux-hardware.org/?probe=bb51e864a7) | Mar 03, 2023 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [3be3c8d79d](https://linux-hardware.org/?probe=3be3c8d79d) | Mar 03, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [906cb4b50a](https://linux-hardware.org/?probe=906cb4b50a) | Mar 03, 2023 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [f043beec18](https://linux-hardware.org/?probe=f043beec18) | Mar 03, 2023 |
| Dell          | 0KC9NP A00                  | Desktop     | [45397750b4](https://linux-hardware.org/?probe=45397750b4) | Mar 02, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [2173dea5df](https://linux-hardware.org/?probe=2173dea5df) | Mar 02, 2023 |
| Toshiba       | TECRA Z50-C                 | Notebook    | [c30ead38bd](https://linux-hardware.org/?probe=c30ead38bd) | Mar 02, 2023 |
| MSI           | PRO H610M-G DDR4            | Desktop     | [8ecbea06f8](https://linux-hardware.org/?probe=8ecbea06f8) | Mar 02, 2023 |
| Apple         | MacBookPro14,3              | Notebook    | [6f952b4c9b](https://linux-hardware.org/?probe=6f952b4c9b) | Mar 01, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [25c46b6f70](https://linux-hardware.org/?probe=25c46b6f70) | Mar 01, 2023 |
| Dell          | 09KPNV A01                  | Desktop     | [08346526f3](https://linux-hardware.org/?probe=08346526f3) | Mar 01, 2023 |
| Biostar       | B450MH                      | Desktop     | [aa05ee87d1](https://linux-hardware.org/?probe=aa05ee87d1) | Mar 01, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [131f94f213](https://linux-hardware.org/?probe=131f94f213) | Mar 01, 2023 |
| Intel Clie... | LAPRC510                    | Notebook    | [925c24b3db](https://linux-hardware.org/?probe=925c24b3db) | Feb 28, 2023 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [021853dafb](https://linux-hardware.org/?probe=021853dafb) | Feb 28, 2023 |
| Intel Clie... | LAPRC510                    | Notebook    | [6d9a8edb0c](https://linux-hardware.org/?probe=6d9a8edb0c) | Feb 28, 2023 |
| Dell          | 0XHGV1 A00                  | Desktop     | [75249be116](https://linux-hardware.org/?probe=75249be116) | Feb 27, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [816a4eb27e](https://linux-hardware.org/?probe=816a4eb27e) | Feb 26, 2023 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [b27fb5e204](https://linux-hardware.org/?probe=b27fb5e204) | Feb 26, 2023 |
| Pegatron      | 2ACB                        | Desktop     | [13355a7d07](https://linux-hardware.org/?probe=13355a7d07) | Feb 26, 2023 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [a2356a66ba](https://linux-hardware.org/?probe=a2356a66ba) | Feb 26, 2023 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [ce67684fdf](https://linux-hardware.org/?probe=ce67684fdf) | Feb 26, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [7f2823a756](https://linux-hardware.org/?probe=7f2823a756) | Feb 26, 2023 |
| HP            | 0AECh D                     | Desktop     | [5baf25e8af](https://linux-hardware.org/?probe=5baf25e8af) | Feb 26, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [0b1c4036b1](https://linux-hardware.org/?probe=0b1c4036b1) | Feb 26, 2023 |
| HP            | Notebook                    | Notebook    | [4a72575c17](https://linux-hardware.org/?probe=4a72575c17) | Feb 25, 2023 |
| Medion        | MAG Z390M MORTAR            | Desktop     | [e2445cf24c](https://linux-hardware.org/?probe=e2445cf24c) | Feb 25, 2023 |
| Toshiba       | Satellite C850              | Notebook    | [99d4efbb52](https://linux-hardware.org/?probe=99d4efbb52) | Feb 25, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [4a0d65f6b5](https://linux-hardware.org/?probe=4a0d65f6b5) | Feb 24, 2023 |
| Gigabyte      | Z77M-D3H-MVP                | Desktop     | [e27e1cd0e8](https://linux-hardware.org/?probe=e27e1cd0e8) | Feb 24, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [72e11db1c0](https://linux-hardware.org/?probe=72e11db1c0) | Feb 24, 2023 |
| MSI           | Vector GP66 12UEO           | Notebook    | [9b6bf9479e](https://linux-hardware.org/?probe=9b6bf9479e) | Feb 24, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [ea2663126f](https://linux-hardware.org/?probe=ea2663126f) | Feb 24, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [8a09d5e812](https://linux-hardware.org/?probe=8a09d5e812) | Feb 23, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [e386073c5d](https://linux-hardware.org/?probe=e386073c5d) | Feb 23, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [d65a9c975d](https://linux-hardware.org/?probe=d65a9c975d) | Feb 23, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | Notebook    | [fa9427d71f](https://linux-hardware.org/?probe=fa9427d71f) | Feb 22, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [2d36b57c9c](https://linux-hardware.org/?probe=2d36b57c9c) | Feb 22, 2023 |
| Lenovo        | ThinkPad X131e 3367AH5      | Notebook    | [3c1cec4c1c](https://linux-hardware.org/?probe=3c1cec4c1c) | Feb 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [8110c575e9](https://linux-hardware.org/?probe=8110c575e9) | Feb 22, 2023 |
| Acer          | TravelMate 8572T            | Notebook    | [20d7321f8f](https://linux-hardware.org/?probe=20d7321f8f) | Feb 21, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [e293e73518](https://linux-hardware.org/?probe=e293e73518) | Feb 21, 2023 |
| MSI           | B550 GAMING GEN3            | Desktop     | [d92a4239ee](https://linux-hardware.org/?probe=d92a4239ee) | Feb 21, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [edd5640ca7](https://linux-hardware.org/?probe=edd5640ca7) | Feb 21, 2023 |
| Dell          | Latitude 5430               | Notebook    | [69fd82c453](https://linux-hardware.org/?probe=69fd82c453) | Feb 21, 2023 |
| Acer          | Aspire X3950                | Desktop     | [f5b4a3baa3](https://linux-hardware.org/?probe=f5b4a3baa3) | Feb 20, 2023 |
| Dell          | Latitude E6430              | Notebook    | [42750c43b5](https://linux-hardware.org/?probe=42750c43b5) | Feb 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [2cc51656a5](https://linux-hardware.org/?probe=2cc51656a5) | Feb 20, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [f8a26128a4](https://linux-hardware.org/?probe=f8a26128a4) | Feb 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [d4663db4e0](https://linux-hardware.org/?probe=d4663db4e0) | Feb 19, 2023 |
| AZW           | GTi                         | Desktop     | [17bb698441](https://linux-hardware.org/?probe=17bb698441) | Feb 19, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [ca676dc566](https://linux-hardware.org/?probe=ca676dc566) | Feb 19, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [9b0ecbd3c7](https://linux-hardware.org/?probe=9b0ecbd3c7) | Feb 19, 2023 |
| Gigabyte      | Z590I AORUS ULTRA           | Desktop     | [9805ab5764](https://linux-hardware.org/?probe=9805ab5764) | Feb 19, 2023 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [aa49c18960](https://linux-hardware.org/?probe=aa49c18960) | Feb 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [0365a40dd4](https://linux-hardware.org/?probe=0365a40dd4) | Feb 18, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | Notebook    | [cc44156b99](https://linux-hardware.org/?probe=cc44156b99) | Feb 17, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | Notebook    | [bc234d0b32](https://linux-hardware.org/?probe=bc234d0b32) | Feb 17, 2023 |
| Toshiba       | Satellite P750              | Notebook    | [6f5f99b514](https://linux-hardware.org/?probe=6f5f99b514) | Feb 16, 2023 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [68f0415788](https://linux-hardware.org/?probe=68f0415788) | Feb 16, 2023 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [2560ba7644](https://linux-hardware.org/?probe=2560ba7644) | Feb 16, 2023 |
| Raspberry ... | Raspberry Pi Model B Plu... | Soc         | [65c778e356](https://linux-hardware.org/?probe=65c778e356) | Feb 16, 2023 |
| ASRock        | Z77 Extreme6                | Desktop     | [48328ab864](https://linux-hardware.org/?probe=48328ab864) | Feb 15, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [8f5697ea3a](https://linux-hardware.org/?probe=8f5697ea3a) | Feb 15, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [f12f20217b](https://linux-hardware.org/?probe=f12f20217b) | Feb 15, 2023 |
| ASUSTek       | V-P7H55E                    | Desktop     | [27ddce20a1](https://linux-hardware.org/?probe=27ddce20a1) | Feb 15, 2023 |
| Gigabyte      | H410M DS2V                  | Desktop     | [b2e8c15dc4](https://linux-hardware.org/?probe=b2e8c15dc4) | Feb 15, 2023 |
| Dell          | 09M8Y8 A01                  | Desktop     | [beabc46f67](https://linux-hardware.org/?probe=beabc46f67) | Feb 14, 2023 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [f298c1fc7e](https://linux-hardware.org/?probe=f298c1fc7e) | Feb 14, 2023 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [45cfd72091](https://linux-hardware.org/?probe=45cfd72091) | Feb 14, 2023 |
| Dell          | 09M8Y8 A01                  | Desktop     | [fb1ff4a6d9](https://linux-hardware.org/?probe=fb1ff4a6d9) | Feb 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [1a20fdd090](https://linux-hardware.org/?probe=1a20fdd090) | Feb 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [3384ced1ca](https://linux-hardware.org/?probe=3384ced1ca) | Feb 14, 2023 |
| MSI           | Vector GP66 12UEO           | Notebook    | [040bddeff8](https://linux-hardware.org/?probe=040bddeff8) | Feb 14, 2023 |
| Gigabyte      | Z68X-UD3H-B3                | Desktop     | [0ad0fe310f](https://linux-hardware.org/?probe=0ad0fe310f) | Feb 14, 2023 |
| HP            | Compaq nc6400 (RM741PA#A... | Notebook    | [d556bf453d](https://linux-hardware.org/?probe=d556bf453d) | Feb 13, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [b563d8f052](https://linux-hardware.org/?probe=b563d8f052) | Feb 13, 2023 |
| ASUSTek       | K45VS                       | Notebook    | [faf4fc0251](https://linux-hardware.org/?probe=faf4fc0251) | Feb 12, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [219157717b](https://linux-hardware.org/?probe=219157717b) | Feb 12, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [cdc63fb05e](https://linux-hardware.org/?probe=cdc63fb05e) | Feb 12, 2023 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [7fec987264](https://linux-hardware.org/?probe=7fec987264) | Feb 12, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [72b0ba099a](https://linux-hardware.org/?probe=72b0ba099a) | Feb 11, 2023 |
| Acer          | Aspire One 753              | Notebook    | [b3ef912b35](https://linux-hardware.org/?probe=b3ef912b35) | Feb 10, 2023 |
| Dell          | G15 5520                    | Notebook    | [121b06f3cc](https://linux-hardware.org/?probe=121b06f3cc) | Feb 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | Notebook    | [e3ea6ad8da](https://linux-hardware.org/?probe=e3ea6ad8da) | Feb 10, 2023 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [99dda6c06c](https://linux-hardware.org/?probe=99dda6c06c) | Feb 09, 2023 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [30363b3a5d](https://linux-hardware.org/?probe=30363b3a5d) | Feb 09, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [fff70a8d2c](https://linux-hardware.org/?probe=fff70a8d2c) | Feb 09, 2023 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | Notebook    | [b79b2f3f75](https://linux-hardware.org/?probe=b79b2f3f75) | Feb 09, 2023 |
| Intel         | LADPNVMO AAE76523-300       | Desktop     | [6ced92edc7](https://linux-hardware.org/?probe=6ced92edc7) | Feb 09, 2023 |
| ASUSTek       | ZenBook UX463FA_UX463FA     | Convertible | [e43aebc69d](https://linux-hardware.org/?probe=e43aebc69d) | Feb 08, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Australia/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 438       | 11.47%  |
| Ubuntu 22.04       | 182       | 4.76%   |
| Ubuntu 18.04       | 173       | 4.53%   |
| Debian 11          | 110       | 2.88%   |
| Pop!_OS 22.04      | 106       | 2.77%   |
| Linux Mint 20.3    | 77        | 2.02%   |
| Arch Rolling       | 75        | 1.96%   |
| OpenMandriva 4.3   | 74        | 1.94%   |
| KDE neon 20.04     | 71        | 1.86%   |
| Fedora 38          | 71        | 1.86%   |
| Zorin 16           | 70        | 1.83%   |
| Fedora 36          | 66        | 1.73%   |
| Pop!_OS 21.04      | 64        | 1.68%   |
| OpenMandriva 4.2   | 56        | 1.47%   |
| Fedora 37          | 52        | 1.36%   |
| Pop!_OS 20.04      | 51        | 1.34%   |
| Linux Mint 21.1    | 50        | 1.31%   |
| Linux Mint 20.2    | 49        | 1.28%   |
| Pop!_OS 20.10      | 48        | 1.26%   |
| Manjaro            | 48        | 1.26%   |
| Ubuntu 21.10       | 46        | 1.2%    |
| ArcoLinux Rolling  | 46        | 1.2%    |
| Arch               | 44        | 1.15%   |
| Linux Mint 20.1    | 42        | 1.1%    |
| Fedora 35          | 42        | 1.1%    |
| Ubuntu 19.04       | 41        | 1.07%   |
| Fedora 33          | 41        | 1.07%   |
| Ubuntu 20.10       | 39        | 1.02%   |
| Fedora 34          | 38        | 0.99%   |
| Ubuntu 21.04       | 37        | 0.97%   |
| Ubuntu 19.10       | 37        | 0.97%   |
| Linux Mint 19.3    | 36        | 0.94%   |
| Ubuntu 23.04       | 33        | 0.86%   |
| OpenMandriva 23.03 | 33        | 0.86%   |
| Linux Mint 20      | 33        | 0.86%   |
| OpenMandriva 23.01 | 31        | 0.81%   |
| Xubuntu 18.04      | 30        | 0.79%   |
| Pop!_OS 21.10      | 30        | 0.79%   |
| Xubuntu 20.04      | 29        | 0.76%   |
| Ubuntu 22.10       | 29        | 0.76%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1029      | 28.92%  |
| Linux Mint    | 331       | 9.3%    |
| Fedora        | 292       | 8.21%   |
| Pop!_OS       | 286       | 8.04%   |
| OpenMandriva  | 232       | 6.52%   |
| Debian        | 179       | 5.03%   |
| Arch          | 118       | 3.32%   |
| Zorin         | 104       | 2.92%   |
| Manjaro       | 103       | 2.89%   |
| KDE neon      | 99        | 2.78%   |
| Xubuntu       | 86        | 2.42%   |
| Kubuntu       | 74        | 2.08%   |
| ArcoLinux     | 48        | 1.35%   |
| Elementary    | 40        | 1.12%   |
| openSUSE      | 36        | 1.01%   |
| Gentoo        | 34        | 0.96%   |
| Kali          | 33        | 0.93%   |
| ROSA          | 29        | 0.82%   |
| Ubuntu MATE   | 27        | 0.76%   |
| Clear Linux   | 25        | 0.7%    |
| Lubuntu       | 23        | 0.65%   |
| ClearOS       | 23        | 0.65%   |
| MX            | 19        | 0.53%   |
| EndeavourOS   | 19        | 0.53%   |
| BlackPanther  | 19        | 0.53%   |
| Endless       | 18        | 0.51%   |
| LMDE          | 16        | 0.45%   |
| Ubuntu Unity  | 15        | 0.42%   |
| Ubuntu Budgie | 14        | 0.39%   |
| SteamOS       | 13        | 0.37%   |
| Parrot        | 13        | 0.37%   |
| CentOS        | 12        | 0.34%   |
| Raspbian      | 10        | 0.28%   |
| Nobara        | 10        | 0.28%   |
| Feren OS      | 8         | 0.22%   |
| LinuxFX       | 7         | 0.2%    |
| Xero          | 6         | 0.17%   |
| Rocky Linux   | 6         | 0.17%   |
| Reborn OS     | 6         | 0.17%   |
| Solus         | 5         | 0.14%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 71        | 1.6%    |
| 5.4.0-42-generic         | 64        | 1.44%   |
| 5.10.14-desktop-1omv4002 | 52        | 1.17%   |
| 6.2.6-desktop-1omv2390   | 31        | 0.7%    |
| 5.15.0-56-generic        | 31        | 0.7%    |
| 5.4.0-40-generic         | 30        | 0.68%   |
| 5.11.0-7620-generic      | 30        | 0.68%   |
| 6.1.1-desktop-1omv2290   | 29        | 0.65%   |
| 5.4.0-58-generic         | 29        | 0.65%   |
| 5.4.0-48-generic         | 27        | 0.61%   |
| 5.15.0-58-generic        | 25        | 0.56%   |
| 5.15.0-52-generic        | 25        | 0.56%   |
| 5.4.0-26-generic         | 24        | 0.54%   |
| 5.3.0-46-generic         | 24        | 0.54%   |
| 6.2.6-76060206-generic   | 23        | 0.52%   |
| 5.4.0-52-generic         | 23        | 0.52%   |
| 5.11.0-37-generic        | 23        | 0.52%   |
| 5.4.0-29-generic         | 22        | 0.5%    |
| 5.3.0-40-generic         | 22        | 0.5%    |
| 5.3.0-28-generic         | 22        | 0.5%    |
| 6.4.11-desktop-1omv2390  | 21        | 0.47%   |
| 5.17.5-76051705-generic  | 21        | 0.47%   |
| 5.15.0-48-generic        | 21        | 0.47%   |
| 6.2.0-20-generic         | 20        | 0.45%   |
| 5.11.0-27-generic        | 20        | 0.45%   |
| 5.4.0-7634-generic       | 19        | 0.43%   |
| 5.15.0-46-generic        | 19        | 0.43%   |
| 5.4.0-74-generic         | 18        | 0.41%   |
| 5.4.0-47-generic         | 18        | 0.41%   |
| 5.19.0-38-generic        | 17        | 0.38%   |
| 5.13.0-7620-generic      | 17        | 0.38%   |
| 6.0.12-76060006-generic  | 16        | 0.36%   |
| 5.8.0-7630-generic       | 16        | 0.36%   |
| 5.8.0-44-generic         | 16        | 0.36%   |
| 5.4.0-91-generic         | 16        | 0.36%   |
| 5.4.0-65-generic         | 16        | 0.36%   |
| 5.15.0-41-generic        | 16        | 0.36%   |
| 5.13.0-40-generic        | 16        | 0.36%   |
| 4.15.0-99-generic        | 16        | 0.36%   |
| 5.8.0-7642-generic       | 15        | 0.34%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 574       | 13.97%  |
| 5.15.0  | 310       | 7.54%   |
| 5.11.0  | 228       | 5.55%   |
| 5.13.0  | 192       | 4.67%   |
| 5.8.0   | 181       | 4.4%    |
| 4.15.0  | 162       | 3.94%   |
| 5.19.0  | 134       | 3.26%   |
| 5.3.0   | 128       | 3.11%   |
| 5.10.0  | 111       | 2.7%    |
| 5.0.0   | 86        | 2.09%   |
| 5.16.7  | 72        | 1.75%   |
| 6.2.0   | 71        | 1.73%   |
| 4.18.0  | 65        | 1.58%   |
| 6.2.6   | 56        | 1.36%   |
| 5.10.14 | 52        | 1.27%   |
| 6.1.1   | 36        | 0.88%   |
| 4.19.0  | 36        | 0.88%   |
| 5.17.5  | 31        | 0.75%   |
| 3.10.0  | 30        | 0.73%   |
| 6.1.0   | 29        | 0.71%   |
| 6.4.11  | 26        | 0.63%   |
| 6.0.12  | 22        | 0.54%   |
| 6.0.0   | 21        | 0.51%   |
| 6.4.6   | 16        | 0.39%   |
| 5.18.0  | 16        | 0.39%   |
| 5.14.0  | 15        | 0.36%   |
| 6.0.7   | 14        | 0.34%   |
| 5.16.11 | 14        | 0.34%   |
| 5.18.10 | 13        | 0.32%   |
| 5.16.0  | 13        | 0.32%   |
| 4.4.0   | 13        | 0.32%   |
| 6.4.10  | 11        | 0.27%   |
| 5.6.14  | 11        | 0.27%   |
| 5.17.0  | 11        | 0.27%   |
| 4.18.16 | 11        | 0.27%   |
| 6.0.6   | 10        | 0.24%   |
| 5.9.16  | 10        | 0.24%   |
| 5.18.12 | 10        | 0.24%   |
| 5.15.11 | 10        | 0.24%   |
| 5.13.13 | 10        | 0.24%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 626       | 15.7%   |
| 5.15    | 421       | 10.56%  |
| 5.11    | 267       | 6.7%    |
| 5.13    | 238       | 5.97%   |
| 5.8     | 228       | 5.72%   |
| 5.10    | 225       | 5.64%   |
| 5.19    | 182       | 4.57%   |
| 6.2     | 175       | 4.39%   |
| 4.15    | 162       | 4.06%   |
| 5.16    | 154       | 3.86%   |
| 5.3     | 143       | 3.59%   |
| 6.1     | 136       | 3.41%   |
| 6.0     | 109       | 2.73%   |
| 6.4     | 106       | 2.66%   |
| 5.0     | 95        | 2.38%   |
| 5.17    | 83        | 2.08%   |
| 5.18    | 81        | 2.03%   |
| 4.18    | 78        | 1.96%   |
| 6.3     | 60        | 1.51%   |
| 5.14    | 50        | 1.25%   |
| 5.6     | 46        | 1.15%   |
| 5.12    | 46        | 1.15%   |
| 4.19    | 46        | 1.15%   |
| 5.9     | 38        | 0.95%   |
| 4.9     | 30        | 0.75%   |
| 3.10    | 30        | 0.75%   |
| 5.5     | 26        | 0.65%   |
| 5.7     | 25        | 0.63%   |
| 6.5     | 17        | 0.43%   |
| 5.2     | 17        | 0.43%   |
| 4.4     | 14        | 0.35%   |
| 5.1     | 9         | 0.23%   |
| 4.1     | 4         | 0.1%    |
| 4.20    | 3         | 0.08%   |
| 4.14    | 3         | 0.08%   |
| 4.13    | 3         | 0.08%   |
| 3.16    | 2         | 0.05%   |
| 5       | 1         | 0.03%   |
| 4.8     | 1         | 0.03%   |
| 4.17    | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 3279      | 97.07%  |
| i686    | 50        | 1.48%   |
| aarch64 | 30        | 0.89%   |
| armv7l  | 13        | 0.38%   |
| riscv64 | 2         | 0.06%   |
| i586    | 2         | 0.06%   |
| armv6l  | 1         | 0.03%   |
| Unknown | 1         | 0.03%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 1562      | 43.64%  |
| KDE5             | 586       | 16.37%  |
| Unknown          | 403       | 11.26%  |
| X-Cinnamon       | 284       | 7.94%   |
| XFCE             | 257       | 7.18%   |
| KDE              | 100       | 2.79%   |
| MATE             | 99        | 2.77%   |
| Cinnamon         | 64        | 1.79%   |
| Pantheon         | 38        | 1.06%   |
| LXQt             | 29        | 0.81%   |
| Budgie           | 22        | 0.61%   |
| Unity            | 20        | 0.56%   |
| LXDE             | 19        | 0.53%   |
| KDE4             | 18        | 0.5%    |
| i3               | 18        | 0.5%    |
| Deepin           | 8         | 0.22%   |
| awesome          | 8         | 0.22%   |
| Openbox          | 7         | 0.2%    |
| GNOME Classic    | 7         | 0.2%    |
| GNOME Flashback  | 4         | 0.11%   |
| xmonad           | 3         | 0.08%   |
| Hyprland         | 3         | 0.08%   |
| BunsenLabs       | 3         | 0.08%   |
| bspwm            | 3         | 0.08%   |
| qtile            | 2         | 0.06%   |
| dwm              | 2         | 0.06%   |
| Trinity          | 1         | 0.03%   |
| sway             | 1         | 0.03%   |
| pop              | 1         | 0.03%   |
| Phosh:GNOME      | 1         | 0.03%   |
| lightdm-xsession | 1         | 0.03%   |
| LeftWM           | 1         | 0.03%   |
| icewm            | 1         | 0.03%   |
| herbstluftwm     | 1         | 0.03%   |
| GNUstep          | 1         | 0.03%   |
| dusk             | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 2631      | 75%     |
| Wayland | 563       | 16.05%  |
| Unknown | 184       | 5.25%   |
| Tty     | 129       | 3.68%   |
| Web     | 1         | 0.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1836      | 52%     |
| SDDM    | 504       | 14.27%  |
| LightDM | 368       | 10.42%  |
| GDM     | 358       | 10.14%  |
| GDM3    | 345       | 9.77%   |
| TDM     | 85        | 2.41%   |
| KDM     | 17        | 0.48%   |
| SLiM    | 6         | 0.17%   |
| LXDM    | 5         | 0.14%   |
| XDM     | 4         | 0.11%   |
| Ly      | 2         | 0.06%   |
| GREETD  | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang         | Computers | Percent |
|--------------|-----------|---------|
| en_AU        | 2458      | 70.25%  |
| en_US        | 546       | 15.6%   |
| Unknown      | 327       | 9.35%   |
| C            | 75        | 2.14%   |
| en_GB        | 65        | 1.86%   |
| C.UTF8       | 6         | 0.17%   |
| POSIX        | 4         | 0.11%   |
| zh_CN        | 3         | 0.09%   |
| de_DE        | 3         | 0.09%   |
| en_CA        | 2         | 0.06%   |
| ru_RU        | 1         | 0.03%   |
| it_IT        | 1         | 0.03%   |
| fr_FR        | 1         | 0.03%   |
| es_ES        | 1         | 0.03%   |
| en_US.utf-8  | 1         | 0.03%   |
| en_IN        | 1         | 0.03%   |
| en_GB.UTF-12 | 1         | 0.03%   |
| en_BW        | 1         | 0.03%   |
| en_AU.UFT-8  | 1         | 0.03%   |
| en-AU        | 1         | 0.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 1780      | 51.36%  |
| EFI  | 1686      | 48.64%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 2531      | 72.63%  |
| Btrfs    | 354       | 10.16%  |
| Overlay  | 248       | 7.12%   |
| Unknown  | 100       | 2.87%   |
| Xfs      | 97        | 2.78%   |
| Tmpfs    | 76        | 2.18%   |
| Zfs      | 52        | 1.49%   |
| Ext2     | 10        | 0.29%   |
| Ext3     | 5         | 0.14%   |
| XXXXXXX  | 4         | 0.11%   |
| F2fs     | 4         | 0.11%   |
| Reiserfs | 2         | 0.06%   |
| Jfs      | 1         | 0.03%   |
| Aufs     | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1876      | 53.83%  |
| GPT     | 1264      | 36.27%  |
| MBR     | 345       | 9.9%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2922      | 84.43%  |
| Yes       | 539       | 15.57%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2555      | 73.93%  |
| Yes       | 901       | 26.07%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 491       | 14.56%  |
| Hewlett-Packard         | 439       | 13.02%  |
| Dell                    | 439       | 13.02%  |
| Gigabyte Technology     | 396       | 11.74%  |
| Lenovo                  | 354       | 10.5%   |
| MSI                     | 217       | 6.44%   |
| Apple                   | 172       | 5.1%    |
| Acer                    | 165       | 4.89%   |
| ASRock                  | 127       | 3.77%   |
| Toshiba                 | 108       | 3.2%    |
| Intel                   | 95        | 2.82%   |
| Microsoft               | 39        | 1.16%   |
| Raspberry Pi Foundation | 30        | 0.89%   |
| Alienware               | 21        | 0.62%   |
| Unknown                 | 21        | 0.62%   |
| Samsung Electronics     | 16        | 0.47%   |
| Sony                    | 11        | 0.33%   |
| Pegatron                | 11        | 0.33%   |
| AMI                     | 11        | 0.33%   |
| Notebook                | 10        | 0.3%    |
| Panasonic               | 9         | 0.27%   |
| Google                  | 9         | 0.27%   |
| Timi                    | 8         | 0.24%   |
| Medion                  | 8         | 0.24%   |
| Metabox                 | 7         | 0.21%   |
| IT Channel Pty          | 7         | 0.21%   |
| IBM                     | 7         | 0.21%   |
| HUAWEI                  | 7         | 0.21%   |
| Valve                   | 6         | 0.18%   |
| Supermicro              | 6         | 0.18%   |
| Razer                   | 6         | 0.18%   |
| Kogan                   | 6         | 0.18%   |
| Fanless Mini PC         | 6         | 0.18%   |
| ECS                     | 6         | 0.18%   |
| System76                | 5         | 0.15%   |
| Shuttle                 | 5         | 0.15%   |
| Pine Microsystems       | 5         | 0.15%   |
| Intel Client Systems    | 5         | 0.15%   |
| Hardkernel              | 4         | 0.12%   |
| Framework               | 4         | 0.12%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| ASUS All Series                        | 36        | 1.07%   |
| Dell OptiPlex 9020                     | 30        | 0.89%   |
| Unknown                                | 25        | 0.74%   |
| HP Pavilion dv6                        | 18        | 0.53%   |
| HP Notebook                            | 13        | 0.39%   |
| MSI MS-7B89                            | 11        | 0.33%   |
| HP Pavilion g6                         | 11        | 0.33%   |
| Dell OptiPlex 780                      | 11        | 0.33%   |
| RPi Raspberry Pi                       | 10        | 0.3%    |
| Gigabyte 970A-D3P                      | 10        | 0.3%    |
| Apple MacBookPro8,1                    | 10        | 0.3%    |
| Apple iMac12,2                         | 10        | 0.3%    |
| MSI MS-7817                            | 9         | 0.27%   |
| HP Pavilion 15                         | 9         | 0.27%   |
| Apple MacBookPro9,2                    | 9         | 0.27%   |
| Apple MacBookPro10,1                   | 9         | 0.27%   |
| Apple MacBookAir7,2                    | 9         | 0.27%   |
| MSI MS-7C37                            | 8         | 0.24%   |
| MSI MS-7C94                            | 7         | 0.21%   |
| Gigabyte X58A-UD3R                     | 7         | 0.21%   |
| Gigabyte B75M-D3H                      | 7         | 0.21%   |
| Dell XPS 15 9570                       | 7         | 0.21%   |
| Dell OptiPlex 990                      | 7         | 0.21%   |
| Valve Jupiter                          | 6         | 0.18%   |
| Toshiba Satellite L850                 | 6         | 0.18%   |
| MSI MS-7C84                            | 6         | 0.18%   |
| MSI MS-7C02                            | 6         | 0.18%   |
| MSI MS-7B86                            | 6         | 0.18%   |
| Microsoft Surface Laptop 3             | 6         | 0.18%   |
| Dell XPS 13 9360                       | 6         | 0.18%   |
| Dell OptiPlex 9010                     | 6         | 0.18%   |
| ASUS TUF Gaming B550M-PLUS             | 6         | 0.18%   |
| ASUS ROG CROSSHAIR VIII DARK HERO      | 6         | 0.18%   |
| Acer ConceptD CN315-71P                | 6         | 0.18%   |
| Toshiba Satellite P750                 | 5         | 0.15%   |
| MSI MS-7A38                            | 5         | 0.15%   |
| Microsoft Surface Pro 3                | 5         | 0.15%   |
| Lenovo ThinkPad T470s W10DG 20JTS0HT00 | 5         | 0.15%   |
| Intel NUC11PAHi5                       | 5         | 0.15%   |
| HP Pavilion x360 Convertible           | 5         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 164       | 4.86%   |
| Acer Aspire         | 112       | 3.32%   |
| Dell OptiPlex       | 105       | 3.11%   |
| Dell Latitude       | 91        | 2.7%    |
| HP Pavilion         | 87        | 2.58%   |
| Toshiba Satellite   | 84        | 2.49%   |
| Dell Inspiron       | 80        | 2.37%   |
| ASUS PRIME          | 71        | 2.11%   |
| Dell XPS            | 67        | 1.99%   |
| ASUS ROG            | 67        | 1.99%   |
| HP EliteBook        | 60        | 1.78%   |
| Lenovo IdeaPad      | 48        | 1.42%   |
| Dell Precision      | 45        | 1.33%   |
| HP Compaq           | 44        | 1.3%    |
| Microsoft Surface   | 39        | 1.16%   |
| ASUS TUF            | 39        | 1.16%   |
| Lenovo Yoga         | 37        | 1.1%    |
| Lenovo ThinkCentre  | 37        | 1.1%    |
| ASUS All            | 36        | 1.07%   |
| HP ProBook          | 34        | 1.01%   |
| RPi Raspberry       | 30        | 0.89%   |
| HP Laptop           | 26        | 0.77%   |
| Unknown             | 25        | 0.74%   |
| Gigabyte X570       | 23        | 0.68%   |
| HP ENVY             | 21        | 0.62%   |
| ASUS ZenBook        | 19        | 0.56%   |
| Gigabyte B450       | 18        | 0.53%   |
| Dell Vostro         | 18        | 0.53%   |
| ASUS VivoBook       | 14        | 0.42%   |
| Apple iMac12        | 14        | 0.42%   |
| Toshiba PORTEGE     | 13        | 0.39%   |
| HP Notebook         | 13        | 0.39%   |
| Gigabyte B450M      | 13        | 0.39%   |
| Apple MacBookPro10  | 13        | 0.39%   |
| HP Spectre          | 12        | 0.36%   |
| MSI MS-7B89         | 11        | 0.33%   |
| Lenovo ThinkStation | 11        | 0.33%   |
| Lenovo IdeaPadFlex  | 11        | 0.33%   |
| HP ProDesk          | 11        | 0.33%   |
| Acer Swift          | 11        | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 310       | 9.19%   |
| 2019    | 309       | 9.16%   |
| 2020    | 289       | 8.57%   |
| 2012    | 279       | 8.27%   |
| 2013    | 249       | 7.38%   |
| 2011    | 247       | 7.33%   |
| 2017    | 213       | 6.32%   |
| 2021    | 211       | 6.26%   |
| 2014    | 208       | 6.17%   |
| 2016    | 196       | 5.81%   |
| 2015    | 177       | 5.25%   |
| 2010    | 163       | 4.83%   |
| 2009    | 122       | 3.62%   |
| 2008    | 122       | 3.62%   |
| 2022    | 115       | 3.41%   |
| 2007    | 60        | 1.78%   |
| Unknown | 43        | 1.28%   |
| 2023    | 22        | 0.65%   |
| 2006    | 20        | 0.59%   |
| 2005    | 13        | 0.39%   |
| 2004    | 2         | 0.06%   |
| 2003    | 1         | 0.03%   |
| 2002    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 1497      | 44.4%   |
| Notebook       | 1449      | 42.97%  |
| Convertible    | 118       | 3.5%    |
| Mini pc        | 94        | 2.79%   |
| All in one     | 85        | 2.52%   |
| Tablet         | 57        | 1.69%   |
| System on chip | 37        | 1.1%    |
| Server         | 29        | 0.86%   |
| Phone          | 3         | 0.09%   |
| Stick pc       | 3         | 0.09%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 3133      | 92.26%  |
| Enabled  | 263       | 7.74%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3357      | 99.56%  |
| Yes  | 15        | 0.44%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 841       | 24.35%  |
| 4.01-8.0        | 716       | 20.73%  |
| 8.01-16.0       | 570       | 16.5%   |
| 3.01-4.0        | 528       | 15.29%  |
| 32.01-64.0      | 443       | 12.83%  |
| 64.01-256.0     | 140       | 4.05%   |
| 1.01-2.0        | 105       | 3.04%   |
| 24.01-32.0      | 63        | 1.82%   |
| 2.01-3.0        | 21        | 0.61%   |
| 0.51-1.0        | 14        | 0.41%   |
| 0.01-0.5        | 7         | 0.2%    |
| More than 256.0 | 5         | 0.14%   |
| Unknown         | 1         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 1262      | 32.43%  |
| 2.01-3.0    | 984       | 25.28%  |
| 4.01-8.0    | 589       | 15.13%  |
| 3.01-4.0    | 518       | 13.31%  |
| 0.51-1.0    | 232       | 5.96%   |
| 8.01-16.0   | 200       | 5.14%   |
| 0.01-0.5    | 51        | 1.31%   |
| 16.01-24.0  | 32        | 0.82%   |
| 24.01-32.0  | 13        | 0.33%   |
| 32.01-64.0  | 4         | 0.1%    |
| 64.01-256.0 | 3         | 0.08%   |
| 0           | 2         | 0.05%   |
| Unknown     | 2         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1908      | 53.69%  |
| 2       | 863       | 24.28%  |
| 3       | 340       | 9.57%   |
| 4       | 199       | 5.6%    |
| 5       | 94        | 2.64%   |
| 6       | 47        | 1.32%   |
| 0       | 35        | 0.98%   |
| 7       | 25        | 0.7%    |
| 8       | 21        | 0.59%   |
| 9       | 9         | 0.25%   |
| 10      | 5         | 0.14%   |
| 13      | 3         | 0.08%   |
| 36      | 1         | 0.03%   |
| 14      | 1         | 0.03%   |
| 12      | 1         | 0.03%   |
| 11      | 1         | 0.03%   |
| Unknown | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2073      | 60.74%  |
| Yes       | 1340      | 39.26%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2920      | 86.34%  |
| No        | 462       | 13.66%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2525      | 73.98%  |
| No        | 888       | 26.02%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1996      | 58.24%  |
| No        | 1431      | 41.76%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| Australia | 3372      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Sydney         | 940       | 25.95%  |
| Melbourne      | 738       | 20.38%  |
| Brisbane       | 518       | 14.3%   |
| Perth          | 312       | 8.61%   |
| Adelaide       | 212       | 5.85%   |
| Canberra       | 78        | 2.15%   |
| Wahroonga      | 39        | 1.08%   |
| Hobart         | 34        | 0.94%   |
| Launceston     | 27        | 0.75%   |
| Alexandria     | 21        | 0.58%   |
| Gold Coast     | 19        | 0.52%   |
| Surry Hills    | 17        | 0.47%   |
| Geelong        | 16        | 0.44%   |
| Richmond       | 12        | 0.33%   |
| Newcastle      | 12        | 0.33%   |
| Lane Cove      | 12        | 0.33%   |
| Central Coast  | 12        | 0.33%   |
| Woolloongabba  | 11        | 0.3%    |
| Mitcham        | 11        | 0.3%    |
| Southport      | 10        | 0.28%   |
| Brighton       | 9         | 0.25%   |
| Wollongong     | 8         | 0.22%   |
| Traralgon      | 8         | 0.22%   |
| Townsville     | 8         | 0.22%   |
| Parramatta     | 7         | 0.19%   |
| Nyngan         | 7         | 0.19%   |
| North Sydney   | 7         | 0.19%   |
| Mandurah       | 7         | 0.19%   |
| Macquarie Park | 7         | 0.19%   |
| Artarmon       | 7         | 0.19%   |
| West End       | 6         | 0.17%   |
| Point Cook     | 6         | 0.17%   |
| Mount Waverley | 6         | 0.17%   |
| Geraldton      | 6         | 0.17%   |
| Sunshine West  | 5         | 0.14%   |
| Spring Field   | 5         | 0.14%   |
| Ringwood East  | 5         | 0.14%   |
| Northcote      | 5         | 0.14%   |
| Mascot         | 5         | 0.14%   |
| Leinster       | 5         | 0.14%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 972       | 1763   | 18.56%  |
| Seagate                     | 842       | 1617   | 16.08%  |
| WDC                         | 781       | 1513   | 14.92%  |
| Crucial                     | 289       | 434    | 5.52%   |
| Toshiba                     | 263       | 375    | 5.02%   |
| Kingston                    | 235       | 306    | 4.49%   |
| Sandisk                     | 219       | 287    | 4.18%   |
| Unknown                     | 198       | 287    | 3.78%   |
| Intel                       | 188       | 344    | 3.59%   |
| Hitachi                     | 158       | 257    | 3.02%   |
| SK hynix                    | 109       | 134    | 2.08%   |
| Apple                       | 96        | 131    | 1.83%   |
| HGST                        | 81        | 120    | 1.55%   |
| Micron Technology           | 75        | 96     | 1.43%   |
| Micron/Crucial Technology   | 66        | 90     | 1.26%   |
| Phison                      | 38        | 59     | 0.73%   |
| OCZ                         | 37        | 54     | 0.71%   |
| SPCC                        | 36        | 44     | 0.69%   |
| KIOXIA                      | 33        | 36     | 0.63%   |
| A-DATA Technology           | 32        | 45     | 0.61%   |
| Phison Electronics          | 25        | 34     | 0.48%   |
| JMicron Technology          | 22        | 26     | 0.42%   |
| Corsair                     | 21        | 35     | 0.4%    |
| LITEONIT                    | 20        | 28     | 0.38%   |
| LITEON                      | 20        | 35     | 0.38%   |
| Kingston Technology Company | 18        | 22     | 0.34%   |
| Unknown                     | 18        | 20     | 0.34%   |
| KingSpec                    | 17        | 37     | 0.32%   |
| Fujitsu                     | 17        | 21     | 0.32%   |
| Transcend                   | 15        | 22     | 0.29%   |
| Patriot                     | 14        | 21     | 0.27%   |
| Gigabyte Technology         | 14        | 17     | 0.27%   |
| LaCie                       | 13        | 20     | 0.25%   |
| China                       | 13        | 15     | 0.25%   |
| ASMT                        | 13        | 21     | 0.25%   |
| Silicon Motion              | 11        | 22     | 0.21%   |
| Maxtor                      | 11        | 14     | 0.21%   |
| Realtek Semiconductor       | 9         | 12     | 0.17%   |
| Hewlett-Packard             | 9         | 13     | 0.17%   |
| XPG                         | 8         | 9      | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB                           | 64        | 1.06%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 52        | 0.86%   |
| Samsung SSD 850 EVO 250GB                           | 51        | 0.85%   |
| Crucial CT500MX500SSD1 500GB                        | 42        | 0.7%    |
| Crucial CT240BX500SSD1 240GB                        | 39        | 0.65%   |
| Unknown MMC Card  64GB                              | 38        | 0.63%   |
| Samsung SSD 850 EVO 500GB                           | 38        | 0.63%   |
| Unknown MMC Card  32GB                              | 37        | 0.61%   |
| Seagate ST1000DM010-2EP102 1TB                      | 36        | 0.6%    |
| Seagate ST500DM002-1BD142 500GB                     | 34        | 0.56%   |
| Seagate Expansion Desk 8TB                          | 34        | 0.56%   |
| Seagate Expansion 1TB                               | 34        | 0.56%   |
| Kingston SA400S37240G 240GB SSD                     | 34        | 0.56%   |
| Seagate ST4000DM004-2CV104 4TB                      | 33        | 0.55%   |
| Seagate ST2000DM008-2FR102 2TB                      | 33        | 0.55%   |
| Samsung SSD 860 EVO 1TB                             | 33        | 0.55%   |
| Samsung NVMe SSD Drive 1TB                          | 32        | 0.53%   |
| Seagate ST2000DM001-1ER164 2TB                      | 31        | 0.51%   |
| Samsung NVMe SSD Drive 512GB                        | 28        | 0.46%   |
| Samsung NVMe SSD Drive 500GB                        | 28        | 0.46%   |
| Seagate ST2000DM001-1CH164 2TB                      | 27        | 0.45%   |
| Crucial CT480BX500SSD1 480GB                        | 27        | 0.45%   |
| Seagate ST3500418AS 500GB                           | 26        | 0.43%   |
| Crucial CT1000MX500SSD1 1TB                         | 26        | 0.43%   |
| Toshiba MQ01ABD100 1TB                              | 24        | 0.4%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 24        | 0.4%    |
| Crucial CT1000BX500SSD1 1TB                         | 24        | 0.4%    |
| Seagate ST31000528AS 1TB                            | 23        | 0.38%   |
| Seagate ST2000DL003-9VT166 2TB                      | 23        | 0.38%   |
| Samsung SSD 860 QVO 1TB                             | 23        | 0.38%   |
| Kingston SV300S37A120G 120GB SSD                    | 23        | 0.38%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 22        | 0.37%   |
| Kingston SA400S37480G 480GB SSD                     | 22        | 0.37%   |
| Kingston SA400S37120G 120GB SSD                     | 22        | 0.37%   |
| Unknown SD/MMC/MS PRO 128GB                         | 21        | 0.35%   |
| WDC WD20EARX-00PASB0 2TB                            | 20        | 0.33%   |
| Seagate ST2000DM006-2DM164 2TB                      | 20        | 0.33%   |
| Seagate ST1000LM035-1RK172 1TB                      | 20        | 0.33%   |
| Samsung SSD 970 EVO Plus 500GB                      | 20        | 0.33%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 19        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 827       | 1573   | 39.57%  |
| WDC                 | 635       | 1258   | 30.38%  |
| Toshiba             | 177       | 266    | 8.47%   |
| Hitachi             | 157       | 255    | 7.51%   |
| Samsung Electronics | 95        | 250    | 4.55%   |
| HGST                | 79        | 118    | 3.78%   |
| Apple               | 26        | 32     | 1.24%   |
| Unknown             | 23        | 34     | 1.1%    |
| Fujitsu             | 16        | 20     | 0.77%   |
| Maxtor              | 11        | 14     | 0.53%   |
| LaCie               | 10        | 16     | 0.48%   |
| ASMT                | 8         | 15     | 0.38%   |
| USB                 | 4         | 5      | 0.19%   |
| SABRENT             | 4         | 4      | 0.19%   |
| Hewlett-Packard     | 3         | 4      | 0.14%   |
| KESU                | 2         | 2      | 0.1%    |
| HGST HUS            | 2         | 2      | 0.1%    |
| External            | 2         | 2      | 0.1%    |
| USB3.0              | 1         | 2      | 0.05%   |
| QNAP                | 1         | 2      | 0.05%   |
| MaxDigital          | 1         | 1      | 0.05%   |
| IET                 | 1         | 1      | 0.05%   |
| IBM/Hitachi         | 1         | 1      | 0.05%   |
| HPE                 | 1         | 1      | 0.05%   |
| Hajaan              | 1         | 1      | 0.05%   |
| DAS                 | 1         | 1      | 0.05%   |
| AAPL                | 1         | 1      | 0.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 541       | 900    | 30.34%  |
| Crucial             | 251       | 386    | 14.08%  |
| Kingston            | 167       | 216    | 9.37%   |
| SanDisk             | 139       | 173    | 7.8%    |
| WDC                 | 127       | 174    | 7.12%   |
| Intel               | 94        | 199    | 5.27%   |
| Apple               | 50        | 56     | 2.8%    |
| SK hynix            | 37        | 44     | 2.08%   |
| OCZ                 | 37        | 54     | 2.08%   |
| SPCC                | 32        | 38     | 1.79%   |
| Toshiba             | 29        | 40     | 1.63%   |
| Micron Technology   | 29        | 34     | 1.63%   |
| LITEONIT            | 20        | 28     | 1.12%   |
| A-DATA Technology   | 19        | 25     | 1.07%   |
| LITEON              | 18        | 33     | 1.01%   |
| KingSpec            | 16        | 36     | 0.9%    |
| Transcend           | 15        | 22     | 0.84%   |
| Patriot             | 14        | 21     | 0.79%   |
| JMicron Technology  | 14        | 16     | 0.79%   |
| Corsair             | 14        | 28     | 0.79%   |
| China               | 13        | 15     | 0.73%   |
| Seagate             | 12        | 19     | 0.67%   |
| Gigabyte Technology | 8         | 8      | 0.45%   |
| TO Exter            | 7         | 7      | 0.39%   |
| Team                | 6         | 10     | 0.34%   |
| OWC                 | 6         | 17     | 0.34%   |
| Plextor             | 5         | 17     | 0.28%   |
| Lexar               | 4         | 4      | 0.22%   |
| KingFast            | 4         | 4      | 0.22%   |
| ASMT                | 4         | 5      | 0.22%   |
| Vaseky              | 3         | 8      | 0.17%   |
| PNY                 | 3         | 3      | 0.17%   |
| T-CREATE            | 2         | 2      | 0.11%   |
| NGFF                | 2         | 2      | 0.11%   |
| Hajaan              | 2         | 2      | 0.11%   |
| FORESEE             | 2         | 2      | 0.11%   |
| Apacer              | 2         | 3      | 0.11%   |
| 2.0TB               | 2         | 3      | 0.11%   |
| XPG                 | 1         | 1      | 0.06%   |
| WDC WDS2            | 1         | 1      | 0.06%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1691      | 3881   | 36.74%  |
| SSD     | 1537      | 2697   | 33.4%   |
| NVMe    | 1127      | 1768   | 24.49%  |
| MMC     | 177       | 247    | 3.85%   |
| Unknown | 70        | 98     | 1.52%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2517      | 6221   | 61.35%  |
| NVMe | 1127      | 1759   | 27.47%  |
| SAS  | 282       | 464    | 6.87%   |
| MMC  | 177       | 247    | 4.31%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1827      | 3485   | 51.93%  |
| 0.51-1.0   | 934       | 1662   | 26.55%  |
| 1.01-2.0   | 395       | 736    | 11.23%  |
| 3.01-4.0   | 133       | 282    | 3.78%   |
| 4.01-10.0  | 132       | 255    | 3.75%   |
| 2.01-3.0   | 86        | 144    | 2.44%   |
| 10.01-20.0 | 10        | 13     | 0.28%   |
| 0          | 1         | 1      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 812       | 22.17%  |
| 251-500        | 754       | 20.58%  |
| 501-1000       | 559       | 15.26%  |
| 1001-2000      | 340       | 9.28%   |
| More than 3000 | 306       | 8.35%   |
| 1-20           | 296       | 8.08%   |
| 51-100         | 242       | 6.61%   |
| 2001-3000      | 140       | 3.82%   |
| Unknown        | 111       | 3.03%   |
| 21-50          | 103       | 2.81%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1430      | 37.21%  |
| 21-50          | 644       | 16.76%  |
| 101-250        | 427       | 11.11%  |
| 51-100         | 391       | 10.17%  |
| 251-500        | 311       | 8.09%   |
| 501-1000       | 209       | 5.44%   |
| 1001-2000      | 143       | 3.72%   |
| More than 3000 | 118       | 3.07%   |
| Unknown        | 111       | 2.89%   |
| 2001-3000      | 57        | 1.48%   |
| 0              | 2         | 0.05%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                   | Computers | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| Intel SSDSC2CT120A3 120GB               | 8         | 39     | 2.52%   |
| Seagate ST500DM002-1BD142 500GB         | 5         | 18     | 1.57%   |
| Seagate ST3500418AS 500GB               | 5         | 15     | 1.57%   |
| Hitachi HDS721010DLE630 1TB             | 5         | 7      | 1.57%   |
| Maxtor 6Y080L0 82GB                     | 4         | 6      | 1.26%   |
| Kingston SV300S37A120G 120GB SSD        | 4         | 4      | 1.26%   |
| WDC WD20EARX-00PASB0 2TB                | 3         | 3      | 0.94%   |
| WDC WD2002FAEX-007BA0 2TB               | 3         | 4      | 0.94%   |
| Seagate ST9500325AS 500GB               | 3         | 3      | 0.94%   |
| Seagate ST31000528AS 1TB                | 3         | 3      | 0.94%   |
| Seagate ST2000DM001-9YN164 2TB          | 3         | 3      | 0.94%   |
| Seagate ST2000DM001-1ER164 2TB          | 3         | 3      | 0.94%   |
| Seagate ST2000DM001-1CH164 2TB          | 3         | 3      | 0.94%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 3         | 4      | 0.94%   |
| Seagate ST1000DM003-1ER162 1TB          | 3         | 8      | 0.94%   |
| Samsung Electronics HD501LJ 500GB       | 3         | 32     | 0.94%   |
| Maxtor 6L200M0 208GB                    | 3         | 4      | 0.94%   |
| Kingston RBU-SNS8350DES3128GP 128GB SSD | 3         | 3      | 0.94%   |
| HGST HTS725050A7E630 500GB              | 3         | 3      | 0.94%   |
| HGST HTS545050A7E680 500GB              | 3         | 4      | 0.94%   |
| Crucial CT525MX300SSD1 528GB            | 3         | 5      | 0.94%   |
| WDC WDS500G1X0E-00AFY0 500GB            | 2         | 2      | 0.63%   |
| WDC WD5000AVCS-632DY1 500GB             | 2         | 3      | 0.63%   |
| WDC WD30EZRX-00DC0B0 3TB                | 2         | 2      | 0.63%   |
| WDC WD20EFRX-68EUZN0 2TB                | 2         | 3      | 0.63%   |
| WDC WD20EARS-00MVWB0 2TB                | 2         | 2      | 0.63%   |
| WDC WD20EARS-00J2GB0 2TB                | 2         | 3      | 0.63%   |
| WDC WD1600AVVS-63L2B0 160GB             | 2         | 5      | 0.63%   |
| WDC WD10EZEX-60ZF5A0 1TB                | 2         | 2      | 0.63%   |
| WDC WD10EZEX-60WN4A0 1TB                | 2         | 3      | 0.63%   |
| WDC WD10EFRX-68FYTN0 1TB                | 2         | 2      | 0.63%   |
| WDC WD10EARS-00Y5B1 1TB                 | 2         | 2      | 0.63%   |
| WDC WD10EADS-11M2B1 1TB                 | 2         | 2      | 0.63%   |
| WDC WD10EADS-00P8B0 1TB                 | 2         | 2      | 0.63%   |
| WDC WD1003FZEX-00K3CA0 1TB              | 2         | 3      | 0.63%   |
| Toshiba THNSNK128GCS8 SATA 128GB SSD    | 2         | 2      | 0.63%   |
| Toshiba MQ01ABF050 500GB                | 2         | 2      | 0.63%   |
| SK hynix HFS256G3AMNB-2200A 256GB SSD   | 2         | 2      | 0.63%   |
| Seagate ST9320423AS 320GB               | 2         | 3      | 0.63%   |
| Seagate ST500LT012-9WS142 500GB         | 2         | 4      | 0.63%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                   | Computers | Drives | Percent |
|--------------------------|-----------|--------|---------|
| Seagate                  | 78        | 127    | 25.83%  |
| WDC                      | 61        | 102    | 20.2%   |
| Samsung Electronics      | 30        | 78     | 9.93%   |
| Hitachi                  | 23        | 27     | 7.62%   |
| Intel                    | 21        | 68     | 6.95%   |
| Toshiba                  | 14        | 18     | 4.64%   |
| Kingston                 | 12        | 12     | 3.97%   |
| HGST                     | 9         | 10     | 2.98%   |
| SanDisk                  | 7         | 7      | 2.32%   |
| Maxtor                   | 7         | 10     | 2.32%   |
| Crucial                  | 6         | 8      | 1.99%   |
| Fujitsu                  | 5         | 5      | 1.66%   |
| SK hynix                 | 4         | 4      | 1.32%   |
| Micron Technology        | 4         | 4      | 1.32%   |
| Corsair                  | 4         | 5      | 1.32%   |
| Apple                    | 3         | 3      | 0.99%   |
| Transcend                | 1         | 1      | 0.33%   |
| SPCC                     | 1         | 1      | 0.33%   |
| Realtek Semiconductor    | 1         | 2      | 0.33%   |
| OCZ                      | 1         | 1      | 0.33%   |
| Netac                    | 1         | 1      | 0.33%   |
| MaxDigital               | 1         | 1      | 0.33%   |
| KingSpec                 | 1         | 3      | 0.33%   |
| KingFast                 | 1         | 1      | 0.33%   |
| HPE                      | 1         | 1      | 0.33%   |
| Hewlett-Packard          | 1         | 2      | 0.33%   |
| Gigabyte Technology      | 1         | 1      | 0.33%   |
| Biwin Storage Technology | 1         | 1      | 0.33%   |
| ASMT                     | 1         | 1      | 0.33%   |
| A-DATA Technology        | 1         | 1      | 0.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 78        | 127    | 36.45%  |
| WDC                 | 59        | 98     | 27.57%  |
| Hitachi             | 23        | 27     | 10.75%  |
| Samsung Electronics | 15        | 62     | 7.01%   |
| Toshiba             | 12        | 16     | 5.61%   |
| HGST                | 9         | 10     | 4.21%   |
| Maxtor              | 7         | 10     | 3.27%   |
| Fujitsu             | 5         | 5      | 2.34%   |
| Apple               | 2         | 2      | 0.93%   |
| MaxDigital          | 1         | 1      | 0.47%   |
| HPE                 | 1         | 1      | 0.47%   |
| Hewlett-Packard     | 1         | 2      | 0.47%   |
| ASMT                | 1         | 1      | 0.47%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 190       | 362    | 68.35%  |
| SSD  | 74        | 126    | 26.62%  |
| NVMe | 14        | 18     | 5.04%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                         | Computers | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| WDC WD3200AAJS-40RYA0 320GB   | 1         | 1      | 33.33%  |
| Hitachi HDS721010DLE630 1TB   | 1         | 8      | 33.33%  |
| Apple HDD HTS541010A9E662 1TB | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 33.33%  |
| Hitachi | 1         | 8      | 33.33%  |
| Apple   | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2146      | 4957   | 58.22%  |
| Works    | 1268      | 3218   | 34.4%   |
| Malfunc  | 269       | 506    | 7.3%    |
| Failed   | 3         | 10     | 0.08%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2244      | 50.43%  |
| AMD                              | 650       | 14.61%  |
| Samsung Electronics              | 459       | 10.31%  |
| SanDisk                          | 128       | 2.88%   |
| Micron/Crucial Technology        | 105       | 2.36%   |
| Marvell Technology Group         | 99        | 2.22%   |
| Kingston Technology Company      | 88        | 1.98%   |
| ASMedia Technology               | 88        | 1.98%   |
| Phison Electronics               | 75        | 1.69%   |
| SK hynix                         | 73        | 1.64%   |
| JMicron Technology               | 73        | 1.64%   |
| Toshiba America Info Systems     | 58        | 1.3%    |
| Micron Technology                | 47        | 1.06%   |
| KIOXIA                           | 32        | 0.72%   |
| Nvidia                           | 29        | 0.65%   |
| ADATA Technology                 | 25        | 0.56%   |
| Silicon Motion                   | 21        | 0.47%   |
| LSI Logic / Symbios Logic        | 21        | 0.47%   |
| Apple                            | 20        | 0.45%   |
| Broadcom / LSI                   | 14        | 0.31%   |
| VIA Technologies                 | 12        | 0.27%   |
| Realtek Semiconductor            | 12        | 0.27%   |
| Seagate Technology               | 9         | 0.2%    |
| Integrated Technology Express    | 9         | 0.2%    |
| Solid State Storage Technology   | 7         | 0.16%   |
| Silicon Image                    | 6         | 0.13%   |
| Hewlett-Packard                  | 6         | 0.13%   |
| Lite-On Technology               | 5         | 0.11%   |
| Union Memory (Shenzhen)          | 4         | 0.09%   |
| MAXIO Technology (Hangzhou)      | 4         | 0.09%   |
| Adaptec                          | 4         | 0.09%   |
| ULi Electronics                  | 3         | 0.07%   |
| Silicon Integrated Systems [SiS] | 3         | 0.07%   |
| Shenzhen Longsys Electronics     | 3         | 0.07%   |
| Lenovo                           | 3         | 0.07%   |
| 3ware                            | 3         | 0.07%   |
| O2 Micro                         | 2         | 0.04%   |
| Biwin Storage Technology         | 2         | 0.04%   |
| Promise Technology               | 1         | 0.02%   |
| PMC-Sierra                       | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 452       | 8.76%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 231       | 4.48%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 174       | 3.37%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 133       | 2.58%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 129       | 2.5%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 111       | 2.15%   |
| AMD 400 Series Chipset SATA Controller                                                  | 107       | 2.07%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 102       | 1.98%   |
| Intel SATA Controller [RAID mode]                                                       | 90        | 1.74%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 90        | 1.74%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 79        | 1.53%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 79        | 1.53%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 74        | 1.43%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 73        | 1.41%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 70        | 1.36%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 69        | 1.34%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 67        | 1.3%    |
| AMD 500 Series Chipset SATA Controller                                                  | 67        | 1.3%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 63        | 1.22%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 63        | 1.22%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 62        | 1.2%    |
| Samsung NVMe SSD Controller 980                                                         | 60        | 1.16%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 57        | 1.1%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 57        | 1.1%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 53        | 1.03%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 51        | 0.99%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 48        | 0.93%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 42        | 0.81%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 40        | 0.78%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 38        | 0.74%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 37        | 0.72%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 36        | 0.7%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 36        | 0.7%    |
| Intel SSD 660P Series                                                                   | 35        | 0.68%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 34        | 0.66%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 33        | 0.64%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton2]                                              | 32        | 0.62%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 32        | 0.62%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 32        | 0.62%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 30        | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2408      | 55.12%  |
| NVMe | 1133      | 25.93%  |
| IDE  | 470       | 10.76%  |
| RAID | 324       | 7.42%   |
| SAS  | 24        | 0.55%   |
| SCSI | 10        | 0.23%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor        | Computers | Percent |
|---------------|-----------|---------|
| Intel         | 2573      | 76.3%   |
| AMD           | 752       | 22.3%   |
| ARM           | 44        | 1.3%    |
| sifive,u74-mc | 1         | 0.03%   |
| CentaurHauls  | 1         | 0.03%   |
| Unknown       | 1         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor       | 44        | 1.3%    |
| Intel Core i7-2600 CPU @ 3.40GHz        | 38        | 1.12%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 36        | 1.07%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 30        | 0.89%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 30        | 0.89%   |
| ARM Processor                           | 30        | 0.89%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 29        | 0.86%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 29        | 0.86%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 28        | 0.83%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 28        | 0.83%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 28        | 0.83%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 28        | 0.83%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 27        | 0.8%    |
| Intel Core i5-3470 CPU @ 3.20GHz        | 26        | 0.77%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 25        | 0.74%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 25        | 0.74%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 25        | 0.74%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 24        | 0.71%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 23        | 0.68%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 22        | 0.65%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 22        | 0.65%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 22        | 0.65%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 20        | 0.59%   |
| Intel Core i7-4770 CPU @ 3.40GHz        | 20        | 0.59%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 20        | 0.59%   |
| AMD Ryzen 9 5950X 16-Core Processor     | 20        | 0.59%   |
| AMD Ryzen 5 2600 Six-Core Processor     | 20        | 0.59%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 19        | 0.56%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 19        | 0.56%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 19        | 0.56%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 18        | 0.53%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 17        | 0.5%    |
| Intel Core i5-3210M CPU @ 2.50GHz       | 16        | 0.47%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 15        | 0.44%   |
| Intel Core i7-3770K CPU @ 3.50GHz       | 15        | 0.44%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 15        | 0.44%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 15        | 0.44%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 15        | 0.44%   |
| Intel Celeron CPU N3350 @ 1.10GHz       | 15        | 0.44%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 14        | 0.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 884       | 26.18%  |
| Intel Core i5           | 752       | 22.27%  |
| Other                   | 242       | 7.17%   |
| AMD Ryzen 5             | 194       | 5.75%   |
| AMD Ryzen 7             | 154       | 4.56%   |
| Intel Core i3           | 141       | 4.18%   |
| Intel Core 2 Duo        | 138       | 4.09%   |
| Intel Celeron           | 124       | 3.67%   |
| Intel Xeon              | 99        | 2.93%   |
| AMD Ryzen 9             | 79        | 2.34%   |
| Intel Pentium           | 51        | 1.51%   |
| AMD FX                  | 47        | 1.39%   |
| Intel Atom              | 32        | 0.95%   |
| AMD A6                  | 31        | 0.92%   |
| AMD A4                  | 28        | 0.83%   |
| AMD Ryzen 3             | 26        | 0.77%   |
| Intel Core 2 Quad       | 25        | 0.74%   |
| Intel Core i9           | 24        | 0.71%   |
| Intel Core 2            | 24        | 0.71%   |
| AMD A8                  | 22        | 0.65%   |
| Intel Pentium Dual-Core | 18        | 0.53%   |
| AMD Phenom II X4        | 16        | 0.47%   |
| AMD E2                  | 16        | 0.47%   |
| AMD A10                 | 16        | 0.47%   |
| ARM BCM                 | 12        | 0.36%   |
| AMD Ryzen Threadripper  | 12        | 0.36%   |
| Intel Core m3           | 10        | 0.3%    |
| AMD Ryzen 7 PRO         | 10        | 0.3%    |
| AMD Phenom II X6        | 10        | 0.3%    |
| AMD Athlon              | 9         | 0.27%   |
| Intel Pentium Dual      | 8         | 0.24%   |
| Intel Genuine           | 8         | 0.24%   |
| AMD E1                  | 8         | 0.24%   |
| Intel Pentium D         | 7         | 0.21%   |
| Intel Core M            | 6         | 0.18%   |
| Intel Pentium Silver    | 5         | 0.15%   |
| Intel Pentium 4         | 5         | 0.15%   |
| AMD Sempron             | 5         | 0.15%   |
| AMD Phenom II X2        | 5         | 0.15%   |
| AMD E                   | 5         | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 1325      | 39.19%  |
| 2       | 1114      | 32.95%  |
| 6       | 404       | 11.95%  |
| 8       | 260       | 7.69%   |
| 12      | 82        | 2.43%   |
| 1       | 60        | 1.77%   |
| 16      | 48        | 1.42%   |
| 10      | 29        | 0.86%   |
| 14      | 19        | 0.56%   |
| 3       | 19        | 0.56%   |
| 24      | 9         | 0.27%   |
| 32      | 4         | 0.12%   |
| Unknown | 4         | 0.12%   |
| 40      | 2         | 0.06%   |
| 128     | 1         | 0.03%   |
| 5       | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3319      | 98.4%   |
| 2       | 49        | 1.45%   |
| Unknown | 4         | 0.12%   |
| 4       | 1         | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2334      | 69.09%  |
| 1       | 1035      | 30.64%  |
| Unknown | 4         | 0.12%   |
| 4       | 3         | 0.09%   |
| 8       | 2         | 0.06%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3281      | 96.98%  |
| Unknown        | 72        | 2.13%   |
| 32-bit         | 23        | 0.68%   |
| 64-bit         | 7         | 0.21%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1108      | 31.31%  |
| 0x206a7    | 183       | 5.17%   |
| 0x306a9    | 168       | 4.75%   |
| 0x306c3    | 147       | 4.15%   |
| 0x1067a    | 95        | 2.68%   |
| 0x906ea    | 88        | 2.49%   |
| 0x506e3    | 70        | 1.98%   |
| 0x906e9    | 69        | 1.95%   |
| 0x806e9    | 65        | 1.84%   |
| 0x406e3    | 61        | 1.72%   |
| 0x08701021 | 59        | 1.67%   |
| 0x40651    | 58        | 1.64%   |
| 0x806ea    | 56        | 1.58%   |
| 0x806ec    | 55        | 1.55%   |
| 0x806c1    | 53        | 1.5%    |
| 0x306d4    | 46        | 1.3%    |
| 0x20655    | 46        | 1.3%    |
| 0x106e5    | 34        | 0.96%   |
| 0x08701013 | 34        | 0.96%   |
| 0x0800820d | 32        | 0.9%    |
| 0x10676    | 31        | 0.88%   |
| 0x30678    | 26        | 0.73%   |
| 0x0a50000c | 26        | 0.73%   |
| 0x20652    | 25        | 0.71%   |
| 0x06006705 | 23        | 0.65%   |
| 0xa0652    | 22        | 0.62%   |
| 0x706e5    | 22        | 0.62%   |
| 0x06000852 | 22        | 0.62%   |
| 0x906ed    | 21        | 0.59%   |
| 0x106a5    | 21        | 0.59%   |
| 0x010000c8 | 21        | 0.59%   |
| 0x806eb    | 20        | 0.57%   |
| 0x0a201016 | 20        | 0.57%   |
| 0x08108109 | 20        | 0.57%   |
| 0x6fb      | 19        | 0.54%   |
| 0x07030105 | 18        | 0.51%   |
| 0x06001119 | 18        | 0.51%   |
| 0x6fd      | 17        | 0.48%   |
| 0x306f2    | 17        | 0.48%   |
| 0x206c2    | 17        | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 535       | 15.82%  |
| Haswell          | 343       | 10.14%  |
| IvyBridge        | 265       | 7.84%   |
| SandyBridge      | 262       | 7.75%   |
| Skylake          | 199       | 5.89%   |
| Zen 2            | 173       | 5.12%   |
| Penryn           | 156       | 4.61%   |
| Unknown          | 133       | 3.93%   |
| Zen 3            | 128       | 3.79%   |
| Westmere         | 116       | 3.43%   |
| Zen+             | 84        | 2.48%   |
| Core             | 76        | 2.25%   |
| CometLake        | 76        | 2.25%   |
| TigerLake        | 72        | 2.13%   |
| Broadwell        | 70        | 2.07%   |
| Zen              | 69        | 2.04%   |
| Nehalem          | 69        | 2.04%   |
| Silvermont       | 67        | 1.98%   |
| Alderlake Hybrid | 59        | 1.75%   |
| Piledriver       | 58        | 1.72%   |
| IceLake          | 56        | 1.66%   |
| K10              | 53        | 1.57%   |
| Excavator        | 44        | 1.3%    |
| Goldmont plus    | 39        | 1.15%   |
| Puma             | 24        | 0.71%   |
| Goldmont         | 24        | 0.71%   |
| Steamroller      | 17        | 0.5%    |
| Bonnell          | 16        | 0.47%   |
| NetBurst         | 14        | 0.41%   |
| Jaguar           | 14        | 0.41%   |
| P6               | 13        | 0.38%   |
| K8 Hammer        | 13        | 0.38%   |
| Bulldozer        | 13        | 0.38%   |
| K10 Llano        | 12        | 0.35%   |
| Bobcat           | 9         | 0.27%   |
| Tremont          | 7         | 0.21%   |
| K8 & K10 hybrid  | 2         | 0.06%   |
| Gracemont        | 1         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1813      | 45.92%  |
| Nvidia                           | 1207      | 30.57%  |
| AMD                              | 892       | 22.59%  |
| Matrox Electronics Systems       | 23        | 0.58%   |
| VIA Technologies                 | 5         | 0.13%   |
| Silicon Integrated Systems [SiS] | 3         | 0.08%   |
| ASPEED Technology                | 3         | 0.08%   |
| Neomagic                         | 2         | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 175       | 4.3%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 125       | 3.07%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 92        | 2.26%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 90        | 2.21%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 86        | 2.11%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 82        | 2.01%   |
| Intel UHD Graphics 620                                                                   | 78        | 1.92%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 73        | 1.79%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 68        | 1.67%   |
| Intel HD Graphics 620                                                                    | 64        | 1.57%   |
| Intel HD Graphics 530                                                                    | 58        | 1.43%   |
| Intel Core Processor Integrated Graphics Controller                                      | 58        | 1.43%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 49        | 1.2%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 47        | 1.15%   |
| Intel HD Graphics 630                                                                    | 47        | 1.15%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 46        | 1.13%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 45        | 1.11%   |
| Intel HD Graphics 5500                                                                   | 39        | 0.96%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 39        | 0.96%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 39        | 0.96%   |
| AMD Renoir                                                                               | 37        | 0.91%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 36        | 0.88%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 35        | 0.86%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 35        | 0.86%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 34        | 0.84%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 32        | 0.79%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 31        | 0.76%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 31        | 0.76%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 30        | 0.74%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 29        | 0.71%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 28        | 0.69%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 27        | 0.66%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 26        | 0.64%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 26        | 0.64%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 23        | 0.57%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 23        | 0.57%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 23        | 0.57%   |
| Intel Iris Plus Graphics G7                                                              | 21        | 0.52%   |
| Intel HD Graphics 500                                                                    | 21        | 0.52%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 21        | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1268      | 37.1%   |
| 1 x Nvidia               | 759       | 22.21%  |
| 1 x AMD                  | 699       | 20.45%  |
| Intel + Nvidia           | 391       | 11.44%  |
| Intel + AMD              | 86        | 2.52%   |
| 2 x AMD                  | 61        | 1.78%   |
| AMD + Nvidia             | 49        | 1.43%   |
| Other                    | 47        | 1.38%   |
| 1 x Matrox               | 20        | 0.59%   |
| 2 x Nvidia               | 10        | 0.29%   |
| 2 x Intel                | 7         | 0.2%    |
| 1 x VIA                  | 5         | 0.15%   |
| 1 x SiS                  | 3         | 0.09%   |
| Nvidia + Matrox          | 3         | 0.09%   |
| Intel + AMD + 1 x Nvidia | 3         | 0.09%   |
| Nvidia + ASPEED          | 2         | 0.06%   |
| 1 x Neomagic             | 2         | 0.06%   |
| Intel + 2 x Nvidia       | 1         | 0.03%   |
| Intel + 2 x AMD          | 1         | 0.03%   |
| 1 x ASPEED               | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 2611      | 75.51%  |
| Proprietary | 676       | 19.55%  |
| Unknown     | 171       | 4.95%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1894      | 54.1%   |
| 1.01-2.0   | 422       | 12.05%  |
| 0.01-0.5   | 299       | 8.54%   |
| 0.51-1.0   | 259       | 7.4%    |
| 3.01-4.0   | 241       | 6.88%   |
| 7.01-8.0   | 195       | 5.57%   |
| 5.01-6.0   | 83        | 2.37%   |
| 8.01-16.0  | 58        | 1.66%   |
| 2.01-3.0   | 30        | 0.86%   |
| 16.01-24.0 | 17        | 0.49%   |
| 4.01-5.0   | 2         | 0.06%   |
| 32.01-64.0 | 1         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 453       | 11.9%   |
| AU Optronics            | 373       | 9.8%    |
| Dell                    | 287       | 7.54%   |
| LG Display              | 269       | 7.07%   |
| Chimei Innolux          | 208       | 5.46%   |
| Acer                    | 190       | 4.99%   |
| BOE                     | 178       | 4.68%   |
| Goldstar                | 161       | 4.23%   |
| Apple                   | 149       | 3.91%   |
| Hewlett-Packard         | 146       | 3.84%   |
| BenQ                    | 144       | 3.78%   |
| Philips                 | 123       | 3.23%   |
| AOC                     | 105       | 2.76%   |
| Ancor Communications    | 105       | 2.76%   |
| Sharp                   | 88        | 2.31%   |
| ViewSonic               | 81        | 2.13%   |
| Lenovo                  | 77        | 2.02%   |
| Unknown                 | 62        | 1.63%   |
| Chi Mei Optoelectronics | 48        | 1.26%   |
| ASUSTek Computer        | 43        | 1.13%   |
| Sony                    | 38        | 1%      |
| ___                     | 31        | 0.81%   |
| Panasonic               | 29        | 0.76%   |
| Kogan                   | 28        | 0.74%   |
| LG Electronics          | 26        | 0.68%   |
| PANDA                   | 23        | 0.6%    |
| GKK                     | 17        | 0.45%   |
| Gigabyte Technology     | 17        | 0.45%   |
| Toshiba                 | 16        | 0.42%   |
| MSI                     | 15        | 0.39%   |
| Hitachi                 | 13        | 0.34%   |
| MiTAC                   | 12        | 0.32%   |
| Unknown (XXX)           | 11        | 0.29%   |
| SAC                     | 11        | 0.29%   |
| InfoVision              | 11        | 0.29%   |
| TCL                     | 9         | 0.24%   |
| CVT                     | 9         | 0.24%   |
| CSO                     | 9         | 0.24%   |
| Unknown                 | 9         | 0.24%   |
| MStar                   | 8         | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SyncMaster SAM01D3 1440x900 410x260mm 19.1-inch   | 21        | 0.52%   |
| ___ LCDTV16 ___0101 1920x1080                                         | 19        | 0.47%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 19        | 0.47%   |
| ___ LCDTV16 ___9000 1360x768                                          | 14        | 0.35%   |
| ViewSonic VA2226w-3 VSC2051 1680x1050 490x290mm 22.4-inch             | 13        | 0.32%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 13        | 0.32%   |
| Panasonic LCD Monitor MEI96A2 2880x1620 344x193mm 15.5-inch           | 12        | 0.3%    |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 12        | 0.3%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 12        | 0.3%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 11        | 0.27%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                     | 11        | 0.27%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 11        | 0.27%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                    | 10        | 0.25%   |
| Unknown LCDTV16 0101 1920x1080 1600x900mm 72.3-inch                   | 10        | 0.25%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 10        | 0.25%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 10        | 0.25%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x173mm 12.3-inch          | 9         | 0.22%   |
| BenQ G2420HD BNQ7840 1920x1080 531x299mm 24.0-inch                    | 9         | 0.22%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch         | 9         | 0.22%   |
| Apple iMac APPA007 2560x1440 597x336mm 27.0-inch                      | 9         | 0.22%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                  | 9         | 0.22%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                  | 9         | 0.22%   |
| Unknown                                                               | 9         | 0.22%   |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1209x680mm 54.6-inch        | 8         | 0.2%    |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch     | 8         | 0.2%    |
| Samsung Electronics LCD Monitor SAM2C35 1024x768 280x210mm 13.8-inch  | 8         | 0.2%    |
| SAC DM-MONB2205 SAC952D 1920x1080 450x270mm 20.7-inch                 | 8         | 0.2%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 8         | 0.2%    |
| Ancor Communications ASUS VP247 ACI24C7 1920x1080 521x293mm 23.5-inch | 8         | 0.2%    |
| Philips PHL 273V7 PHLC156 1920x1080 600x340mm 27.2-inch               | 7         | 0.17%   |
| Lenovo LEN L1711pC LEN13B7 1280x1024 338x270mm 17.0-inch              | 7         | 0.17%   |
| Kogan KAMN341FQULA KGN3400 3440x1440 795x334mm 33.9-inch              | 7         | 0.17%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 7         | 0.17%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 7         | 0.17%   |
| Dell S2721DGF DEL41D9 2560x1440 597x336mm 27.0-inch                   | 7         | 0.17%   |
| CVT CVTE TV CVT0003 1920x1080 575x323mm 26.0-inch                     | 7         | 0.17%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 7         | 0.17%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch       | 7         | 0.17%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch       | 7         | 0.17%   |
| Chimei Innolux LCD Monitor CMN1514 1920x1080 344x193mm 15.5-inch      | 7         | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1527      | 42.05%  |
| 1366x768 (WXGA)    | 517       | 14.24%  |
| 3840x2160 (4K)     | 322       | 8.87%   |
| 2560x1440 (QHD)    | 206       | 5.67%   |
| 1680x1050 (WSXGA+) | 129       | 3.55%   |
| 1280x1024 (SXGA)   | 111       | 3.06%   |
| 1920x1200 (WUXGA)  | 108       | 2.97%   |
| 1440x900 (WXGA+)   | 103       | 2.84%   |
| 1600x900 (HD+)     | 79        | 2.18%   |
| 1280x800 (WXGA)    | 70        | 1.93%   |
| 3440x1440          | 63        | 1.74%   |
| Unknown            | 59        | 1.62%   |
| 2560x1600          | 38        | 1.05%   |
| 3840x1080          | 29        | 0.8%    |
| 1360x768           | 26        | 0.72%   |
| 2880x1800          | 24        | 0.66%   |
| 2560x1080          | 24        | 0.66%   |
| 3840x2400          | 16        | 0.44%   |
| 2736x1824          | 13        | 0.36%   |
| 1920x540           | 12        | 0.33%   |
| 3200x1800 (QHD+)   | 9         | 0.25%   |
| 2160x1440          | 9         | 0.25%   |
| 1280x768           | 9         | 0.25%   |
| 1920x1280          | 8         | 0.22%   |
| 1280x720 (HD)      | 7         | 0.19%   |
| 800x1280           | 6         | 0.17%   |
| 3840x1600          | 6         | 0.17%   |
| 2256x1504          | 6         | 0.17%   |
| 1024x768 (XGA)     | 6         | 0.17%   |
| 1024x600           | 6         | 0.17%   |
| 3072x1920          | 5         | 0.14%   |
| 5760x2160          | 4         | 0.11%   |
| 5120x1440          | 4         | 0.11%   |
| 4480x1440          | 4         | 0.11%   |
| 3600x1080          | 4         | 0.11%   |
| 3200x2000          | 4         | 0.11%   |
| 2288x1287          | 4         | 0.11%   |
| 2240x1400          | 4         | 0.11%   |
| 1600x1200          | 4         | 0.11%   |
| 3200x1080          | 3         | 0.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 694       | 18.27%  |
| 27      | 389       | 10.24%  |
| 13      | 326       | 8.58%   |
| 24      | 321       | 8.45%   |
| 23      | 276       | 7.27%   |
| Unknown | 236       | 6.21%   |
| 14      | 216       | 5.69%   |
| 21      | 207       | 5.45%   |
| 17      | 143       | 3.77%   |
| 19      | 135       | 3.55%   |
| 31      | 123       | 3.24%   |
| 22      | 94        | 2.47%   |
| 34      | 74        | 1.95%   |
| 12      | 68        | 1.79%   |
| 72      | 55        | 1.45%   |
| 11      | 55        | 1.45%   |
| 20      | 50        | 1.32%   |
| 18      | 41        | 1.08%   |
| 84      | 27        | 0.71%   |
| 32      | 25        | 0.66%   |
| 54      | 21        | 0.55%   |
| 16      | 20        | 0.53%   |
| 26      | 19        | 0.5%    |
| 52      | 17        | 0.45%   |
| 48      | 15        | 0.39%   |
| 42      | 15        | 0.39%   |
| 40      | 13        | 0.34%   |
| 35      | 12        | 0.32%   |
| 37      | 11        | 0.29%   |
| 10      | 11        | 0.29%   |
| 25      | 10        | 0.26%   |
| 29      | 9         | 0.24%   |
| 55      | 7         | 0.18%   |
| 63      | 6         | 0.16%   |
| 46      | 6         | 0.16%   |
| 7       | 6         | 0.16%   |
| 36      | 5         | 0.13%   |
| 28      | 4         | 0.11%   |
| 142     | 3         | 0.08%   |
| 86      | 3         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1041      | 28.06%  |
| 501-600        | 887       | 23.91%  |
| 401-500        | 429       | 11.56%  |
| 201-300        | 351       | 9.46%   |
| Unknown        | 236       | 6.36%   |
| 351-400        | 225       | 6.06%   |
| 601-700        | 195       | 5.26%   |
| 701-800        | 103       | 2.78%   |
| 1001-1500      | 88        | 2.37%   |
| 1501-2000      | 87        | 2.35%   |
| 801-900        | 40        | 1.08%   |
| 901-1000       | 17        | 0.46%   |
| 1-100          | 6         | 0.16%   |
| More than 2000 | 3         | 0.08%   |
| 101-200        | 2         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2401      | 71.01%  |
| 16/10   | 475       | 14.05%  |
| Unknown | 197       | 5.83%   |
| 5/4     | 99        | 2.93%   |
| 21/9    | 93        | 2.75%   |
| 3/2     | 50        | 1.48%   |
| 4/3     | 24        | 0.71%   |
| 32/9    | 16        | 0.47%   |
| 6/5     | 12        | 0.35%   |
| 0.67    | 6         | 0.18%   |
| 1.00    | 3         | 0.09%   |
| 0.56    | 3         | 0.09%   |
| 3.40    | 1         | 0.03%   |
| 0.62    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 726       | 19.41%  |
| 101-110        | 687       | 18.36%  |
| 301-350        | 403       | 10.77%  |
| 81-90          | 377       | 10.08%  |
| 351-500        | 240       | 6.42%   |
| Unknown        | 236       | 6.31%   |
| 151-200        | 235       | 6.28%   |
| 71-80          | 168       | 4.49%   |
| More than 1000 | 154       | 4.12%   |
| 251-300        | 111       | 2.97%   |
| 121-130        | 99        | 2.65%   |
| 501-1000       | 69        | 1.84%   |
| 51-60          | 58        | 1.55%   |
| 61-70          | 55        | 1.47%   |
| 141-150        | 50        | 1.34%   |
| 111-120        | 26        | 0.7%    |
| 131-140        | 17        | 0.45%   |
| 91-100         | 12        | 0.32%   |
| 41-50          | 10        | 0.27%   |
| 1-40           | 8         | 0.21%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1289      | 35.8%   |
| 101-120       | 854       | 23.72%  |
| 121-160       | 722       | 20.05%  |
| 161-240       | 253       | 7.03%   |
| Unknown       | 236       | 6.55%   |
| 1-50          | 125       | 3.47%   |
| More than 240 | 122       | 3.39%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 2662      | 75.63%  |
| 2     | 598       | 16.99%  |
| 0     | 176       | 5%      |
| 3     | 72        | 2.05%   |
| 4     | 11        | 0.31%   |
| 5     | 1         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1778      | 34.13%  |
| Realtek Semiconductor           | 1688      | 32.41%  |
| Qualcomm Atheros                | 529       | 10.16%  |
| Broadcom                        | 366       | 7.03%   |
| Broadcom Limited                | 79        | 1.52%   |
| Marvell Technology Group        | 66        | 1.27%   |
| Ralink                          | 60        | 1.15%   |
| TP-Link                         | 51        | 0.98%   |
| Ralink Technology               | 49        | 0.94%   |
| MediaTek                        | 48        | 0.92%   |
| Samsung Electronics             | 36        | 0.69%   |
| Sierra Wireless                 | 27        | 0.52%   |
| DisplayLink                     | 27        | 0.52%   |
| NetGear                         | 26        | 0.5%    |
| Huawei Technologies             | 22        | 0.42%   |
| Aquantia                        | 22        | 0.42%   |
| Nvidia                          | 20        | 0.38%   |
| D-Link                          | 20        | 0.38%   |
| Microsoft                       | 17        | 0.33%   |
| Edimax Technology               | 17        | 0.33%   |
| Dell                            | 17        | 0.33%   |
| D-Link System                   | 17        | 0.33%   |
| ASIX Electronics                | 17        | 0.33%   |
| ZTE WCDMA Technologies MSM      | 13        | 0.25%   |
| Lenovo                          | 13        | 0.25%   |
| Apple                           | 13        | 0.25%   |
| Hewlett-Packard                 | 12        | 0.23%   |
| ASUSTek Computer                | 12        | 0.23%   |
| Motorola PCS                    | 10        | 0.19%   |
| Google                          | 10        | 0.19%   |
| OPPO Electronics                | 9         | 0.17%   |
| VIA Technologies                | 8         | 0.15%   |
| Qualcomm Atheros Communications | 7         | 0.13%   |
| Qualcomm                        | 7         | 0.13%   |
| ICS Advent                      | 6         | 0.12%   |
| Standard Microsystems           | 5         | 0.1%    |
| Mellanox Technologies           | 5         | 0.1%    |
| Arduino SA                      | 5         | 0.1%    |
| Xiaomi                          | 4         | 0.08%   |
| Microchip Technology            | 4         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1118      | 18.26%  |
| Intel Wi-Fi 6 AX200                                               | 171       | 2.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 140       | 2.29%   |
| Intel I211 Gigabit Network Connection                             | 132       | 2.16%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 130       | 2.12%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 125       | 2.04%   |
| Realtek RTL8125 2.5GbE Controller                                 | 100       | 1.63%   |
| Intel Wireless 8265 / 8275                                        | 94        | 1.53%   |
| Intel Wireless 8260                                               | 79        | 1.29%   |
| Intel Ethernet Connection I217-LM                                 | 67        | 1.09%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 66        | 1.08%   |
| Intel Wireless 7260                                               | 66        | 1.08%   |
| Intel Ethernet Connection (2) I219-V                              | 65        | 1.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 62        | 1.01%   |
| Intel Wireless 7265                                               | 60        | 0.98%   |
| Intel Wi-Fi 6 AX201                                               | 57        | 0.93%   |
| Intel Ethernet Controller I225-V                                  | 56        | 0.91%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 55        | 0.9%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 53        | 0.87%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 51        | 0.83%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 50        | 0.82%   |
| Intel Wireless 3165                                               | 49        | 0.8%    |
| Intel Ethernet Connection (7) I219-V                              | 48        | 0.78%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 47        | 0.77%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 47        | 0.77%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 44        | 0.72%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 44        | 0.72%   |
| Intel Wireless-AC 9260                                            | 43        | 0.7%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 41        | 0.67%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 40        | 0.65%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 40        | 0.65%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 40        | 0.65%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 39        | 0.64%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 37        | 0.6%    |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 36        | 0.59%   |
| Intel Ethernet Connection I219-LM                                 | 35        | 0.57%   |
| Intel Centrino Ultimate-N 6300                                    | 35        | 0.57%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 34        | 0.56%   |
| Intel Ethernet Connection (2) I219-LM                             | 34        | 0.56%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 34        | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1243      | 45.97%  |
| Qualcomm Atheros                | 396       | 14.64%  |
| Realtek Semiconductor           | 382       | 14.13%  |
| Broadcom                        | 244       | 9.02%   |
| Ralink                          | 60        | 2.22%   |
| Broadcom Limited                | 57        | 2.11%   |
| TP-Link                         | 49        | 1.81%   |
| Ralink Technology               | 49        | 1.81%   |
| MediaTek                        | 43        | 1.59%   |
| Sierra Wireless                 | 27        | 1%      |
| NetGear                         | 24        | 0.89%   |
| Marvell Technology Group        | 24        | 0.89%   |
| Edimax Technology               | 17        | 0.63%   |
| Microsoft                       | 12        | 0.44%   |
| D-Link System                   | 12        | 0.44%   |
| D-Link                          | 12        | 0.44%   |
| ASUSTek Computer                | 12        | 0.44%   |
| Dell                            | 10        | 0.37%   |
| Qualcomm Atheros Communications | 7         | 0.26%   |
| Belkin Components               | 4         | 0.15%   |
| Qualcomm                        | 3         | 0.11%   |
| Hewlett-Packard                 | 3         | 0.11%   |
| BUFFALO                         | 3         | 0.11%   |
| Wacom                           | 2         | 0.07%   |
| Linksys                         | 2         | 0.07%   |
| AVM                             | 2         | 0.07%   |
| Xiaomi                          | 1         | 0.04%   |
| Wilocity                        | 1         | 0.04%   |
| Toshiba                         | 1         | 0.04%   |
| IMC Networks                    | 1         | 0.04%   |
| AboCom Systems                  | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 171       | 6.29%   |
| Intel Wireless 8265 / 8275                                     | 94        | 3.46%   |
| Intel Wireless 8260                                            | 79        | 2.91%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 66        | 2.43%   |
| Intel Wireless 7260                                            | 66        | 2.43%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 62        | 2.28%   |
| Intel Wireless 7265                                            | 60        | 2.21%   |
| Intel Wi-Fi 6 AX201                                            | 57        | 2.1%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 55        | 2.02%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 53        | 1.95%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 51        | 1.88%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 50        | 1.84%   |
| Intel Wireless 3165                                            | 49        | 1.8%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 47        | 1.73%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 47        | 1.73%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 44        | 1.62%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 44        | 1.62%   |
| Intel Wireless-AC 9260                                         | 43        | 1.58%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 41        | 1.51%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 40        | 1.47%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 40        | 1.47%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 39        | 1.43%   |
| Intel Centrino Ultimate-N 6300                                 | 35        | 1.29%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 34        | 1.25%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 34        | 1.25%   |
| Realtek 802.11ac NIC                                           | 33        | 1.21%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 28        | 1.03%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 28        | 1.03%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 27        | 0.99%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 27        | 0.99%   |
| Intel Wireless 3160                                            | 26        | 0.96%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 26        | 0.96%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 25        | 0.92%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 23        | 0.85%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless              | 23        | 0.85%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 22        | 0.81%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 21        | 0.77%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 21        | 0.77%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 18        | 0.66%   |
| Intel Centrino Advanced-N 6235                                 | 18        | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1491      | 46.18%  |
| Intel                            | 1013      | 31.37%  |
| Qualcomm Atheros                 | 190       | 5.88%   |
| Broadcom                         | 188       | 5.82%   |
| Marvell Technology Group         | 42        | 1.3%    |
| Samsung Electronics              | 36        | 1.11%   |
| DisplayLink                      | 27        | 0.84%   |
| Broadcom Limited                 | 22        | 0.68%   |
| Aquantia                         | 22        | 0.68%   |
| Nvidia                           | 20        | 0.62%   |
| Huawei Technologies              | 17        | 0.53%   |
| ASIX Electronics                 | 17        | 0.53%   |
| ZTE WCDMA Technologies MSM       | 13        | 0.4%    |
| Lenovo                           | 13        | 0.4%    |
| Apple                            | 13        | 0.4%    |
| Google                           | 10        | 0.31%   |
| OPPO Electronics                 | 9         | 0.28%   |
| VIA Technologies                 | 8         | 0.25%   |
| D-Link                           | 8         | 0.25%   |
| Motorola PCS                     | 6         | 0.19%   |
| ICS Advent                       | 6         | 0.19%   |
| Standard Microsystems            | 5         | 0.15%   |
| D-Link System                    | 5         | 0.15%   |
| Microsoft                        | 4         | 0.12%   |
| Microchip Technology             | 4         | 0.12%   |
| MediaTek                         | 4         | 0.12%   |
| JMicron Technology               | 4         | 0.12%   |
| Xiaomi                           | 3         | 0.09%   |
| Qualcomm                         | 3         | 0.09%   |
| NetGear                          | 3         | 0.09%   |
| IBM                              | 3         | 0.09%   |
| Hewlett-Packard                  | 3         | 0.09%   |
| Silicon Integrated Systems [SiS] | 2         | 0.06%   |
| QLogic                           | 2         | 0.06%   |
| Mellanox Technologies            | 2         | 0.06%   |
| Dell                             | 2         | 0.06%   |
| vivo                             | 1         | 0.03%   |
| TP-Link                          | 1         | 0.03%   |
| T & A Mobile Phones              | 1         | 0.03%   |
| National Semiconductor           | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1118      | 33.52%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 140       | 4.2%    |
| Intel I211 Gigabit Network Connection                             | 132       | 3.96%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 130       | 3.9%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 125       | 3.75%   |
| Realtek RTL8125 2.5GbE Controller                                 | 100       | 3%      |
| Intel Ethernet Connection I217-LM                                 | 67        | 2.01%   |
| Intel Ethernet Connection (2) I219-V                              | 65        | 1.95%   |
| Intel Ethernet Controller I225-V                                  | 56        | 1.68%   |
| Intel Ethernet Connection (7) I219-V                              | 48        | 1.44%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 40        | 1.2%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 37        | 1.11%   |
| Intel Ethernet Connection I219-LM                                 | 35        | 1.05%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 34        | 1.02%   |
| Intel Ethernet Connection (2) I219-LM                             | 34        | 1.02%   |
| Intel 82579V Gigabit Network Connection                           | 29        | 0.87%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 28        | 0.84%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 27        | 0.81%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 27        | 0.81%   |
| Intel Ethernet Connection I217-V                                  | 24        | 0.72%   |
| Intel 82574L Gigabit Network Connection                           | 24        | 0.72%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 23        | 0.69%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 23        | 0.69%   |
| Intel Ethernet Connection (4) I219-LM                             | 22        | 0.66%   |
| Intel Ethernet Connection (2) I218-V                              | 22        | 0.66%   |
| Intel I210 Gigabit Network Connection                             | 20        | 0.6%    |
| Intel 82577LM Gigabit Network Connection                          | 20        | 0.6%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 18        | 0.54%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 17        | 0.51%   |
| Intel Ethernet Connection I218-LM                                 | 17        | 0.51%   |
| Intel Ethernet Connection (4) I219-V                              | 16        | 0.48%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 16        | 0.48%   |
| Intel Ethernet Connection (6) I219-V                              | 14        | 0.42%   |
| ASIX AX88179 Gigabit Ethernet                                     | 14        | 0.42%   |
| Intel Ethernet Connection I219-V                                  | 13        | 0.39%   |
| Intel Ethernet Connection (10) I219-V                             | 13        | 0.39%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 13        | 0.39%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 12        | 0.36%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 12        | 0.36%   |
| Intel Ethernet Connection (3) I218-LM                             | 12        | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2909      | 52.92%  |
| WiFi     | 2518      | 45.81%  |
| Modem    | 56        | 1.02%   |
| Unknown  | 14        | 0.25%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1899      | 54.04%  |
| Ethernet | 1615      | 45.96%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1777      | 52.14%  |
| 1     | 1380      | 40.49%  |
| 3     | 132       | 3.87%   |
| 0     | 77        | 2.26%   |
| 4     | 27        | 0.79%   |
| 5     | 9         | 0.26%   |
| 6     | 4         | 0.12%   |
| 9     | 1         | 0.03%   |
| 8     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2965      | 86.32%  |
| Yes  | 470       | 13.68%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1019      | 50.15%  |
| Apple                           | 156       | 7.68%   |
| Broadcom                        | 133       | 6.55%   |
| Realtek Semiconductor           | 128       | 6.3%    |
| Qualcomm Atheros Communications | 124       | 6.1%    |
| Cambridge Silicon Radio         | 122       | 6%      |
| IMC Networks                    | 53        | 2.61%   |
| Lite-On Technology              | 52        | 2.56%   |
| Foxconn / Hon Hai               | 47        | 2.31%   |
| Toshiba                         | 39        | 1.92%   |
| ASUSTek Computer                | 27        | 1.33%   |
| Marvell Semiconductor           | 22        | 1.08%   |
| Hewlett-Packard                 | 21        | 1.03%   |
| Ralink                          | 17        | 0.84%   |
| Dell                            | 17        | 0.84%   |
| MediaTek                        | 13        | 0.64%   |
| TP-Link                         | 7         | 0.34%   |
| Alps Electric                   | 7         | 0.34%   |
| Realtek                         | 6         | 0.3%    |
| Edimax Technology               | 5         | 0.25%   |
| Ralink Technology               | 4         | 0.2%    |
| USI                             | 3         | 0.15%   |
| Micro Star International        | 2         | 0.1%    |
| Integrated System Solution      | 2         | 0.1%    |
| Belkin Components               | 2         | 0.1%    |
| Taiyo Yuden                     | 1         | 0.05%   |
| Opticis                         | 1         | 0.05%   |
| Logitech                        | 1         | 0.05%   |
| Creative Technology             | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 354       | 17.4%   |
| Intel AX201 Bluetooth                               | 178       | 8.75%   |
| Intel AX200 Bluetooth                               | 163       | 8.01%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 122       | 6%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 111       | 5.45%   |
| Realtek Bluetooth Radio                             | 74        | 3.64%   |
| Apple Bluetooth Host Controller                     | 67        | 3.29%   |
| Qualcomm Atheros  Bluetooth Device                  | 53        | 2.6%    |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 52        | 2.56%   |
| Intel Wireless-AC 3168 Bluetooth                    | 47        | 2.31%   |
| Intel Bluetooth Device                              | 46        | 2.26%   |
| Apple Bluetooth USB Host Controller                 | 43        | 2.11%   |
| Realtek  Bluetooth 4.2 Adapter                      | 41        | 2.01%   |
| Intel AX210 Bluetooth                               | 41        | 2.01%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 39        | 1.92%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 31        | 1.52%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 30        | 1.47%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 27        | 1.33%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 23        | 1.13%   |
| IMC Networks Bluetooth Radio                        | 21        | 1.03%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 19        | 0.93%   |
| Ralink RT3290 Bluetooth                             | 17        | 0.84%   |
| Marvell Bluetooth and Wireless LAN Composite        | 17        | 0.84%   |
| Lite-On Atheros AR3012 Bluetooth                    | 16        | 0.79%   |
| Broadcom BCM2045B (BDC-2.1)                         | 16        | 0.79%   |
| Foxconn / Hon Hai Bluetooth Device                  | 15        | 0.74%   |
| Apple Bluetooth HCI                                 | 15        | 0.74%   |
| Toshiba Bluetooth Device                            | 13        | 0.64%   |
| MediaTek Wireless_Device                            | 13        | 0.64%   |
| Lite-On Bluetooth Device                            | 13        | 0.64%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 13        | 0.64%   |
| HP Broadcom 2070 Bluetooth Combo                    | 12        | 0.59%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 11        | 0.54%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 11        | 0.54%   |
| Broadcom HP Portable Bumble Bee                     | 10        | 0.49%   |
| IMC Networks Wireless_Device                        | 9         | 0.44%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 9         | 0.44%   |
| Toshiba Integrated Bluetooth HCI                    | 8         | 0.39%   |
| Broadcom HP Portable SoftSailing                    | 8         | 0.39%   |
| TP-Link UB5A Adapter                                | 7         | 0.34%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 2462      | 49.22%  |
| AMD                                  | 1002      | 20.03%  |
| Nvidia                               | 924       | 18.47%  |
| C-Media Electronics                  | 65        | 1.3%    |
| Logitech                             | 60        | 1.2%    |
| Creative Labs                        | 31        | 0.62%   |
| Realtek Semiconductor                | 27        | 0.54%   |
| Kingston Technology                  | 21        | 0.42%   |
| Texas Instruments                    | 20        | 0.4%    |
| Razer USA                            | 20        | 0.4%    |
| GN Netcom                            | 20        | 0.4%    |
| Plantronics                          | 17        | 0.34%   |
| Creative Technology                  | 17        | 0.34%   |
| Apple                                | 16        | 0.32%   |
| Generalplus Technology               | 15        | 0.3%    |
| RODE Microphones                     | 13        | 0.26%   |
| Corsair                              | 13        | 0.26%   |
| SteelSeries ApS                      | 11        | 0.22%   |
| Micro Star International             | 10        | 0.2%    |
| Lenovo                               | 10        | 0.2%    |
| JMTek                                | 9         | 0.18%   |
| VIA Technologies                     | 8         | 0.16%   |
| Hewlett-Packard                      | 8         | 0.16%   |
| DSEA A/S                             | 8         | 0.16%   |
| Blue Microphones                     | 8         | 0.16%   |
| Astro Gaming                         | 8         | 0.16%   |
| Dell                                 | 7         | 0.14%   |
| Audio-Technica                       | 7         | 0.14%   |
| ASUSTek Computer                     | 7         | 0.14%   |
| Thesycon Systemsoftware & Consulting | 6         | 0.12%   |
| M-Audio                              | 6         | 0.12%   |
| Focusrite-Novation                   | 6         | 0.12%   |
| Cambridge Silicon Radio              | 6         | 0.12%   |
| Sony                                 | 5         | 0.1%    |
| Samson Technologies                  | 5         | 0.1%    |
| OPPO Electronics                     | 5         | 0.1%    |
| Microsoft                            | 5         | 0.1%    |
| Giga-Byte Technology                 | 5         | 0.1%    |
| PreSonus Audio Electronics           | 4         | 0.08%   |
| Native Instruments                   | 4         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 257       | 4.41%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 252       | 4.32%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 236       | 4.05%   |
| AMD Starship/Matisse HD Audio Controller                                   | 207       | 3.55%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 200       | 3.43%   |
| AMD Family 17h/19h HD Audio Controller                                     | 192       | 3.29%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 142       | 2.43%   |
| Intel Cannon Lake PCH cAVS                                                 | 140       | 2.4%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 131       | 2.25%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 108       | 1.85%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 93        | 1.59%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 93        | 1.59%   |
| AMD FCH Azalia Controller                                                  | 93        | 1.59%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 93        | 1.59%   |
| Intel 8 Series HD Audio Controller                                         | 89        | 1.53%   |
| Intel Haswell-ULT HD Audio Controller                                      | 88        | 1.51%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 80        | 1.37%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 77        | 1.32%   |
| Intel 200 Series PCH HD Audio                                              | 77        | 1.32%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 71        | 1.22%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 69        | 1.18%   |
| Intel Broadwell-U Audio Controller                                         | 60        | 1.03%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 59        | 1.01%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 59        | 1.01%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 59        | 1.01%   |
| Nvidia TU116 High Definition Audio Controller                              | 58        | 0.99%   |
| Nvidia GP107GL High Definition Audio Controller                            | 58        | 0.99%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 58        | 0.99%   |
| Nvidia GP104 High Definition Audio Controller                              | 56        | 0.96%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 53        | 0.91%   |
| Nvidia TU106 High Definition Audio Controller                              | 52        | 0.89%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 51        | 0.87%   |
| Intel Comet Lake PCH-LP cAVS                                               | 50        | 0.86%   |
| Intel Comet Lake PCH cAVS                                                  | 49        | 0.84%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 49        | 0.84%   |
| Nvidia GF108 High Definition Audio Controller                              | 48        | 0.82%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 46        | 0.79%   |
| AMD Kabini HDMI/DP Audio                                                   | 45        | 0.77%   |
| Nvidia GK107 HDMI Audio Controller                                         | 44        | 0.75%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 44        | 0.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 396       | 20.91%  |
| SK hynix                                | 323       | 17.05%  |
| Kingston                                | 209       | 11.03%  |
| Micron Technology                       | 194       | 10.24%  |
| Corsair                                 | 170       | 8.98%   |
| Unknown                                 | 153       | 8.08%   |
| Crucial                                 | 117       | 6.18%   |
| G.Skill                                 | 99        | 5.23%   |
| Team                                    | 33        | 1.74%   |
| Elpida                                  | 31        | 1.64%   |
| Nanya Technology                        | 25        | 1.32%   |
| A-DATA Technology                       | 19        | 1%      |
| Patriot                                 | 17        | 0.9%    |
| Ramaxel Technology                      | 16        | 0.84%   |
| Apacer                                  | 12        | 0.63%   |
| Unknown                                 | 11        | 0.58%   |
| Transcend                               | 10        | 0.53%   |
| Unknown (ABCD)                          | 8         | 0.42%   |
| Strontium                               | 4         | 0.21%   |
| Silicon Power                           | 4         | 0.21%   |
| Neo Forza                               | 4         | 0.21%   |
| GeIL                                    | 4         | 0.21%   |
| Hewlett-Packard                         | 3         | 0.16%   |
| Unknown (0x873E)                        | 2         | 0.11%   |
| Toshiba                                 | 2         | 0.11%   |
| Smart                                   | 2         | 0.11%   |
| pqi                                     | 2         | 0.11%   |
| Goldenmars                              | 2         | 0.11%   |
| Avant                                   | 2         | 0.11%   |
| ASint Technology                        | 2         | 0.11%   |
| Unknown (0x89AD)                        | 1         | 0.05%   |
| Unknown (0x0562)                        | 1         | 0.05%   |
| Undefi                                  | 1         | 0.05%   |
| Timetec                                 | 1         | 0.05%   |
| Silicon Power Computer & Communications | 1         | 0.05%   |
| Qimonda                                 | 1         | 0.05%   |
| Princeton                               | 1         | 0.05%   |
| PNY                                     | 1         | 0.05%   |
| Netlist                                 | 1         | 0.05%   |
| KingFast                                | 1         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s         | 19        | 0.93%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s         | 17        | 0.83%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s         | 14        | 0.68%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s        | 13        | 0.64%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s         | 13        | 0.64%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s         | 13        | 0.64%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s         | 12        | 0.59%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s        | 11        | 0.54%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s        | 11        | 0.54%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s         | 11        | 0.54%   |
| Unknown                                                       | 11        | 0.54%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s         | 10        | 0.49%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s         | 10        | 0.49%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s         | 10        | 0.49%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s        | 10        | 0.49%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s        | 9         | 0.44%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s         | 9         | 0.44%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                       | 8         | 0.39%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 8         | 0.39%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s     | 8         | 0.39%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s        | 8         | 0.39%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s         | 8         | 0.39%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s         | 8         | 0.39%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s | 8         | 0.39%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s         | 8         | 0.39%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                          | 7         | 0.34%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                        | 7         | 0.34%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s        | 7         | 0.34%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s       | 7         | 0.34%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s        | 7         | 0.34%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s         | 7         | 0.34%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s         | 7         | 0.34%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s         | 7         | 0.34%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s          | 7         | 0.34%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s          | 6         | 0.29%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s         | 6         | 0.29%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s         | 6         | 0.29%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s          | 6         | 0.29%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                       | 5         | 0.24%   |
| Unknown RAM Module 2GB DIMM 800MT/s                           | 5         | 0.24%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 766       | 45.9%   |
| DDR3    | 558       | 33.43%  |
| LPDDR3  | 76        | 4.55%   |
| Unknown | 74        | 4.43%   |
| DDR2    | 62        | 3.71%   |
| LPDDR4  | 54        | 3.24%   |
| SDRAM   | 24        | 1.44%   |
| DDR5    | 23        | 1.38%   |
| LPDDR5  | 17        | 1.02%   |
| DDR     | 12        | 0.72%   |
| DRAM    | 3         | 0.18%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 823       | 49.58%  |
| DIMM         | 684       | 41.2%   |
| Row Of Chips | 136       | 8.19%   |
| Chip         | 11        | 0.66%   |
| FB-DIMM      | 3         | 0.18%   |
| Unknown      | 3         | 0.18%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 707       | 39.81%  |
| 4096  | 441       | 24.83%  |
| 16384 | 300       | 16.89%  |
| 2048  | 205       | 11.54%  |
| 32768 | 74        | 4.17%   |
| 1024  | 36        | 2.03%   |
| 512   | 8         | 0.45%   |
| 65536 | 2         | 0.11%   |
| 49152 | 1         | 0.06%   |
| 1536  | 1         | 0.06%   |
| 256   | 1         | 0.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 374       | 20.66%  |
| 2667    | 249       | 13.76%  |
| 3200    | 213       | 11.77%  |
| 1333    | 140       | 7.73%   |
| 2133    | 111       | 6.13%   |
| 2400    | 107       | 5.91%   |
| 3600    | 68        | 3.76%   |
| 1334    | 54        | 2.98%   |
| 800     | 48        | 2.65%   |
| 1867    | 43        | 2.38%   |
| 667     | 40        | 2.21%   |
| 4267    | 25        | 1.38%   |
| 1067    | 24        | 1.33%   |
| 4800    | 23        | 1.27%   |
| 3400    | 23        | 1.27%   |
| Unknown | 22        | 1.22%   |
| 3000    | 21        | 1.16%   |
| 6400    | 18        | 0.99%   |
| 3533    | 14        | 0.77%   |
| 3266    | 14        | 0.77%   |
| 1866    | 14        | 0.77%   |
| 1066    | 14        | 0.77%   |
| 3733    | 11        | 0.61%   |
| 2933    | 10        | 0.55%   |
| 1800    | 9         | 0.5%    |
| 2800    | 8         | 0.44%   |
| 8400    | 7         | 0.39%   |
| 3866    | 7         | 0.39%   |
| 2666    | 7         | 0.39%   |
| 4266    | 6         | 0.33%   |
| 4000    | 6         | 0.33%   |
| 3800    | 6         | 0.33%   |
| 3100    | 5         | 0.28%   |
| 2048    | 5         | 0.28%   |
| 533     | 5         | 0.28%   |
| 400     | 5         | 0.28%   |
| 5200    | 4         | 0.22%   |
| 3666    | 4         | 0.22%   |
| 3534    | 4         | 0.22%   |
| 3500    | 4         | 0.22%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Brother Industries     | 37        | 28.91%  |
| Hewlett-Packard        | 30        | 23.44%  |
| Canon                  | 22        | 17.19%  |
| Fuji Xerox             | 8         | 6.25%   |
| Seiko Epson            | 7         | 5.47%   |
| Samsung Electronics    | 6         | 4.69%   |
| Prolific Technology    | 6         | 4.69%   |
| Dymo-CoStar            | 3         | 2.34%   |
| Lexmark International  | 2         | 1.56%   |
| Kyocera                | 2         | 1.56%   |
| Zebra                  | 1         | 0.78%   |
| Xerox                  | 1         | 0.78%   |
| Ricoh                  | 1         | 0.78%   |
| Custom Engineering SPA | 1         | 0.78%   |
| BIXOLON                | 1         | 0.78%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| HP DeskJet 2600 series                       | 8         | 6.11%   |
| Prolific PL2305 Parallel Port                | 6         | 4.58%   |
| Brother HL-2130 series                       | 5         | 3.82%   |
| Brother HL-1110 series                       | 5         | 3.82%   |
| HP DeskJet 2130 series                       | 4         | 3.05%   |
| HP ENVY 5000 series                          | 3         | 2.29%   |
| HP DeskJet F2100 Printer series              | 3         | 2.29%   |
| Fuji Xerox DocuPrint CM215 fw                | 3         | 2.29%   |
| Canon TS3100 series                          | 3         | 2.29%   |
| Brother HL-L3230CDW series                   | 3         | 2.29%   |
| Brother HL-1210W series                      | 3         | 2.29%   |
| HP OfficeJet 5200 series                     | 2         | 1.53%   |
| HP DeskJet 3630 series                       | 2         | 1.53%   |
| Fuji Xerox DocuPrint P205 b                  | 2         | 1.53%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo       | 2         | 1.53%   |
| Canon TR8500 series                          | 2         | 1.53%   |
| Canon PIXMA MX920 Series                     | 2         | 1.53%   |
| Canon PIXMA MG2500 Series                    | 2         | 1.53%   |
| Canon MG5600 series                          | 2         | 1.53%   |
| Canon LiDE 400                               | 2         | 1.53%   |
| Brother QL-570 Label Printer                 | 2         | 1.53%   |
| Brother MFC-L8690CDW series                  | 2         | 1.53%   |
| Brother MFC-1810                             | 2         | 1.53%   |
| Brother HL-L2305 series                      | 2         | 1.53%   |
| Zebra ZTC LP2844-Z-200dpi                    | 1         | 0.76%   |
| Xerox Phaser 8400N                           | 1         | 0.76%   |
| Seiko Epson XP-4100 Series                   | 1         | 0.76%   |
| Seiko Epson XP-240 Series                    | 1         | 0.76%   |
| Seiko Epson WF-5190 Series                   | 1         | 0.76%   |
| Seiko Epson WF-4830 Series                   | 1         | 0.76%   |
| Seiko Epson Thermal Receipt Printer [TM-T20] | 1         | 0.76%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1         | 0.76%   |
| Seiko Epson ET-2820 Series                   | 1         | 0.76%   |
| Samsung ML-2010P Mono Laser Printer          | 1         | 0.76%   |
| Samsung ML-1865                              | 1         | 0.76%   |
| Samsung ML-1640 Series Laser Printer         | 1         | 0.76%   |
| Samsung ML-1450                              | 1         | 0.76%   |
| Samsung M267x 287x Series                    | 1         | 0.76%   |
| Samsung M2020 Series                         | 1         | 0.76%   |
| Ricoh Printer                                | 1         | 0.76%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Canon            | 10        | 58.82%  |
| Seiko Epson      | 4         | 23.53%  |
| Syscan           | 1         | 5.88%   |
| Salix Technology | 1         | 5.88%   |
| Mustek Systems   | 1         | 5.88%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Canon CanoScan LIDE 25                                  | 2         | 11.76%  |
| Canon CanoScan LiDE 210                                 | 2         | 11.76%  |
| Syscan TravelScan 460/464                               | 1         | 5.88%   |
| Seiko Epson Scanner                                     | 1         | 5.88%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]             | 1         | 5.88%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1         | 5.88%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]       | 1         | 5.88%   |
| Salix USB Scanner.                                      | 1         | 5.88%   |
| Mustek Systems BearPaw 2448 TA Plus                     | 1         | 5.88%   |
| Canon CanoScan N670U/N676U/LiDE 20                      | 1         | 5.88%   |
| Canon CanoScan N1240U/LiDE 30                           | 1         | 5.88%   |
| Canon CanoScan LiDE 220                                 | 1         | 5.88%   |
| Canon CanoScan LiDE 200                                 | 1         | 5.88%   |
| Canon CanoScan LiDE 110                                 | 1         | 5.88%   |
| Canon CanoScan 1220U                                    | 1         | 5.88%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 397       | 21.24%  |
| Logitech                               | 186       | 9.95%   |
| Microdia                               | 153       | 8.19%   |
| Apple                                  | 143       | 7.65%   |
| Realtek Semiconductor                  | 131       | 7.01%   |
| IMC Networks                           | 120       | 6.42%   |
| Sunplus Innovation Technology          | 118       | 6.31%   |
| Bison Electronics                      | 72        | 3.85%   |
| Quanta                                 | 68        | 3.64%   |
| Cheng Uei Precision Industry (Foxlink) | 64        | 3.42%   |
| Suyin                                  | 58        | 3.1%    |
| Microsoft                              | 51        | 2.73%   |
| Acer                                   | 33        | 1.77%   |
| Lite-On Technology                     | 30        | 1.61%   |
| Samsung Electronics                    | 27        | 1.44%   |
| Syntek                                 | 26        | 1.39%   |
| Luxvisions Innotech Limited            | 19        | 1.02%   |
| Silicon Motion                         | 12        | 0.64%   |
| Importek                               | 12        | 0.64%   |
| Alcor Micro                            | 12        | 0.64%   |
| Ricoh                                  | 10        | 0.54%   |
| Razer USA                              | 9         | 0.48%   |
| Lenovo                                 | 9         | 0.48%   |
| Primax Electronics                     | 7         | 0.37%   |
| GEMBIRD                                | 7         | 0.37%   |
| Sonix Technology                       | 6         | 0.32%   |
| OPPO Electronics                       | 6         | 0.32%   |
| LG Electronics                         | 6         | 0.32%   |
| Generalplus Technology                 | 6         | 0.32%   |
| Z-Star Microelectronics                | 5         | 0.27%   |
| OmniVision Technologies                | 5         | 0.27%   |
| Magic Control Technology               | 4         | 0.21%   |
| icSpring                               | 4         | 0.21%   |
| Genesys Logic                          | 4         | 0.21%   |
| DigiTech                               | 4         | 0.21%   |
| Cubeternet                             | 4         | 0.21%   |
| ALi                                    | 4         | 0.21%   |
| webcamvendor                           | 2         | 0.11%   |
| SunplusIT                              | 2         | 0.11%   |
| MacroSilicon                           | 2         | 0.11%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 75        | 3.93%   |
| Chicony Integrated Camera                               | 69        | 3.62%   |
| Apple FaceTime HD Camera (Built-in)                     | 49        | 2.57%   |
| Realtek Integrated_Webcam_HD                            | 39        | 2.05%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                      | 36        | 1.89%   |
| Sunplus Integrated_Webcam_HD                            | 33        | 1.73%   |
| Apple Built-in iSight                                   | 33        | 1.73%   |
| Chicony HD WebCam                                       | 32        | 1.68%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 31        | 1.63%   |
| IMC Networks Integrated Camera                          | 30        | 1.57%   |
| Samsung Galaxy series, misc. (MTP mode)                 | 27        | 1.42%   |
| Logitech Webcam C270                                    | 27        | 1.42%   |
| Logitech HD Pro Webcam C920                             | 27        | 1.42%   |
| Bison Integrated Camera                                 | 25        | 1.31%   |
| Logitech C922 Pro Stream Webcam                         | 21        | 1.1%    |
| Chicony TOSHIBA Web Camera - HD                         | 20        | 1.05%   |
| Syntek Integrated Camera                                | 18        | 0.94%   |
| Chicony HP TrueVision HD Camera                         | 18        | 0.94%   |
| Apple FaceTime HD Camera                                | 18        | 0.94%   |
| Sunplus HD WebCam                                       | 17        | 0.89%   |
| Chicony HP Truevision HD                                | 16        | 0.84%   |
| Chicony HP HD Camera                                    | 16        | 0.84%   |
| Chicony USB 2.0 Camera                                  | 14        | 0.73%   |
| Chicony HD User Facing                                  | 14        | 0.73%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 14        | 0.73%   |
| Quanta HD User Facing                                   | 13        | 0.68%   |
| Suyin HP TrueVision HD                                  | 12        | 0.63%   |
| Realtek USB Camera                                      | 12        | 0.63%   |
| Microsoft LifeCam HD-3000                               | 12        | 0.63%   |
| Logitech Webcam C930e                                   | 12        | 0.63%   |
| Lite-On Integrated Camera                               | 12        | 0.63%   |
| Chicony EasyCamera                                      | 12        | 0.63%   |
| Logitech StreamCam                                      | 11        | 0.58%   |
| Logitech HD Webcam C615                                 | 11        | 0.58%   |
| Chicony USB2.0 Camera                                   | 11        | 0.58%   |
| Chicony CNF9055 Toshiba Webcam                          | 11        | 0.58%   |
| Quanta HP TrueVision HD Camera                          | 10        | 0.52%   |
| Microdia Integrated_Webcam_FHD                          | 10        | 0.52%   |
| Microdia Integrated Webcam                              | 10        | 0.52%   |
| Logitech Webcam C170                                    | 10        | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 147       | 42.49%  |
| Synaptics                  | 80        | 23.12%  |
| Shenzhen Goodix Technology | 42        | 12.14%  |
| LighTuning Technology      | 22        | 6.36%   |
| AuthenTec                  | 17        | 4.91%   |
| Elan Microelectronics      | 16        | 4.62%   |
| Upek                       | 14        | 4.05%   |
| STMicroelectronics         | 7         | 2.02%   |
| Focal-systems.Corp         | 1         | 0.29%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 26        | 7.51%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 23        | 6.65%   |
| Shenzhen Goodix Fingerprint Reader                                         | 19        | 5.49%   |
| Validity Sensors Synaptics WBDI                                            | 14        | 4.05%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 14        | 4.05%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 13        | 3.76%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 12        | 3.47%   |
| Validity Sensors Fingerprint scanner                                       | 12        | 3.47%   |
| Shenzhen Goodix  FingerPrint Device                                        | 12        | 3.47%   |
| Validity Sensors VFS491                                                    | 11        | 3.18%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 11        | 3.18%   |
| Shenzhen Goodix FingerPrint                                                | 11        | 3.18%   |
| Synaptics  WBDI                                                            | 10        | 2.89%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 9         | 2.6%    |
| Synaptics WBDI                                                             | 9         | 2.6%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 8         | 2.31%   |
| Validity Sensors VFS Fingerprint sensor                                    | 8         | 2.31%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 8         | 2.31%   |
| Synaptics UWP WBDI                                                         | 8         | 2.31%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 2.31%   |
| Elan ELAN:ARM-M4                                                           | 8         | 2.31%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 7         | 2.02%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 7         | 2.02%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 2.02%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 7         | 2.02%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 1.73%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 6         | 1.73%   |
| Synaptics WBDI Device                                                      | 5         | 1.45%   |
| Elan WBF Fingerprint Sensor                                                | 5         | 1.45%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 1.16%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 1.16%   |
| AuthenTec AES1600                                                          | 4         | 1.16%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 3         | 0.87%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 0.87%   |
| Synaptics Fingerprint reader [HP G6]                                       | 3         | 0.87%   |
| Elan ELAN:Fingerprint                                                      | 3         | 0.87%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 0.87%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 2         | 0.58%   |
| Synaptics UWP WBDI Device                                                  | 2         | 0.58%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.58%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 38        | 62.3%   |
| Alcor Micro           | 13        | 21.31%  |
| Upek                  | 4         | 6.56%   |
| Lenovo                | 3         | 4.92%   |
| O2 Micro              | 2         | 3.28%   |
| Advanced Card Systems | 1         | 1.64%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 17        | 27.87%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 13        | 21.31%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 8         | 13.11%  |
| Broadcom 58200                                                               | 7         | 11.48%  |
| Broadcom 5880                                                                | 6         | 9.84%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 6.56%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 4.92%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 3.28%   |
| Advanced Card Systems ACR122U                                                | 1         | 1.64%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2431      | 69.32%  |
| 1     | 880       | 25.09%  |
| 2     | 152       | 4.33%   |
| 3     | 31        | 0.88%   |
| 4     | 11        | 0.31%   |
| 7     | 1         | 0.03%   |
| 5     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 344       | 27.56%  |
| Graphics card            | 289       | 23.16%  |
| Net/wireless             | 185       | 14.82%  |
| Multimedia controller    | 83        | 6.65%   |
| Communication controller | 56        | 4.49%   |
| Chipcard                 | 55        | 4.41%   |
| Camera                   | 41        | 3.29%   |
| Bluetooth                | 41        | 3.29%   |
| Unassigned class         | 36        | 2.88%   |
| Net/ethernet             | 25        | 2%      |
| Sound                    | 22        | 1.76%   |
| Storage                  | 17        | 1.36%   |
| Modem                    | 11        | 0.88%   |
| Network                  | 9         | 0.72%   |
| Card reader              | 9         | 0.72%   |
| Dvb card                 | 8         | 0.64%   |
| Storage/raid             | 4         | 0.32%   |
| Video                    | 3         | 0.24%   |
| Firewire controller      | 3         | 0.24%   |
| Storage/ata              | 2         | 0.16%   |
| Unclassified device      | 1         | 0.08%   |
| Tv card                  | 1         | 0.08%   |
| Storage/nvme             | 1         | 0.08%   |
| Storage/ide              | 1         | 0.08%   |
| Flash memory             | 1         | 0.08%   |

