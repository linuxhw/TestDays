Arch - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------

A project to collect tested hardware configurations for Arch.

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

Total: 3478

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | Stream Laptop 14-ds0xxx     | [a008ad925d](https://linux-hardware.org/?probe=a008ad925d) | Aug 01, 2022 |
| Acidanther... | MacBookPro13,1              | [5c8158f059](https://linux-hardware.org/?probe=5c8158f059) | Aug 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [d77ac14ae9](https://linux-hardware.org/?probe=d77ac14ae9) | Aug 01, 2022 |
| Lenovo        | ThinkPad T420 4180LN1       | [65d5b19d40](https://linux-hardware.org/?probe=65d5b19d40) | Aug 01, 2022 |
| Lenovo        | ThinkPad T420 4180LN1       | [35304c2321](https://linux-hardware.org/?probe=35304c2321) | Aug 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [b2385a694b](https://linux-hardware.org/?probe=b2385a694b) | Jul 31, 2022 |
| Toshiba       | dynabook Satellite B35/R    | [4600fb0c71](https://linux-hardware.org/?probe=4600fb0c71) | Jul 31, 2022 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | [d3b270c068](https://linux-hardware.org/?probe=d3b270c068) | Jul 31, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [97f6892c6c](https://linux-hardware.org/?probe=97f6892c6c) | Jul 30, 2022 |
| Acer          | Nitro AN515-55              | [3b08b42260](https://linux-hardware.org/?probe=3b08b42260) | Jul 30, 2022 |
| Dell          | Inspiron N4010              | [7589775fb4](https://linux-hardware.org/?probe=7589775fb4) | Jul 30, 2022 |
| Lenovo        | ThinkPad E480 20KN001QRT    | [e0e0792a71](https://linux-hardware.org/?probe=e0e0792a71) | Jul 30, 2022 |
| Clevo         | W150HNM/W170HN              | [31c83153b5](https://linux-hardware.org/?probe=31c83153b5) | Jul 29, 2022 |
| MSI           | GF75 Thin 9SC               | [a6113f2e35](https://linux-hardware.org/?probe=a6113f2e35) | Jul 29, 2022 |
| Toshiba       | Satellite L70-B             | [bee2cdca79](https://linux-hardware.org/?probe=bee2cdca79) | Jul 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [ef7aa9cb2e](https://linux-hardware.org/?probe=ef7aa9cb2e) | Jul 29, 2022 |
| Dell          | Latitude 5480               | [2e2d540cb0](https://linux-hardware.org/?probe=2e2d540cb0) | Jul 29, 2022 |
| Framework     | Laptop                      | [626e3266c7](https://linux-hardware.org/?probe=626e3266c7) | Jul 29, 2022 |
| HP            | ZBook 15v G5                | [b08d670a98](https://linux-hardware.org/?probe=b08d670a98) | Jul 28, 2022 |
| HP            | 255 G7 Notebook PC          | [bc1a82a647](https://linux-hardware.org/?probe=bc1a82a647) | Jul 28, 2022 |
| Dell          | XPS 15 9500                 | [e5d7cc54e7](https://linux-hardware.org/?probe=e5d7cc54e7) | Jul 28, 2022 |
| Timi          | TM1703                      | [b3c578658f](https://linux-hardware.org/?probe=b3c578658f) | Jul 28, 2022 |
| Acer          | Aspire A715-42G             | [8d87e3bb3b](https://linux-hardware.org/?probe=8d87e3bb3b) | Jul 28, 2022 |
| Lenovo        | ThinkPad X230 2325TXV       | [2c5c6ba837](https://linux-hardware.org/?probe=2c5c6ba837) | Jul 28, 2022 |
| Apple         | MacBookAir7,2               | [b547e23eb1](https://linux-hardware.org/?probe=b547e23eb1) | Jul 28, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [7d9d58c2da](https://linux-hardware.org/?probe=7d9d58c2da) | Jul 27, 2022 |
| Dell          | G5 5590                     | [ae478a8f82](https://linux-hardware.org/?probe=ae478a8f82) | Jul 27, 2022 |
| Samsung       | 935XDB                      | [d6149a337b](https://linux-hardware.org/?probe=d6149a337b) | Jul 26, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [75c2236b06](https://linux-hardware.org/?probe=75c2236b06) | Jul 26, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [6577d30f3e](https://linux-hardware.org/?probe=6577d30f3e) | Jul 26, 2022 |
| Alienware     | m15 R4                      | [2f80ebdd19](https://linux-hardware.org/?probe=2f80ebdd19) | Jul 26, 2022 |
| Dell          | Precision 7560              | [2fdcece648](https://linux-hardware.org/?probe=2fdcece648) | Jul 25, 2022 |
| Dell          | Precision 7560              | [02fb353f1e](https://linux-hardware.org/?probe=02fb353f1e) | Jul 25, 2022 |
| Dell          | Vostro 3491                 | [6ce65dccb7](https://linux-hardware.org/?probe=6ce65dccb7) | Jul 24, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [ce2ecc0fd8](https://linux-hardware.org/?probe=ce2ecc0fd8) | Jul 24, 2022 |
| Timi          | RedmiBook 14 II             | [cd8d5a1ee6](https://linux-hardware.org/?probe=cd8d5a1ee6) | Jul 24, 2022 |
| Lenovo        | ThinkPad X280 20KES2SN00    | [202423ba73](https://linux-hardware.org/?probe=202423ba73) | Jul 24, 2022 |
| Google        | Wolf                        | [f2397aadef](https://linux-hardware.org/?probe=f2397aadef) | Jul 23, 2022 |
| Google        | Wolf                        | [ffa74c4dc0](https://linux-hardware.org/?probe=ffa74c4dc0) | Jul 23, 2022 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | [492b4e1236](https://linux-hardware.org/?probe=492b4e1236) | Jul 23, 2022 |
| ASUSTek       | X555LD                      | [bc783f5d64](https://linux-hardware.org/?probe=bc783f5d64) | Jul 23, 2022 |
| Apple         | MacBookAir7,1               | [51d002e1b7](https://linux-hardware.org/?probe=51d002e1b7) | Jul 23, 2022 |
| Apple         | MacBookAir7,1               | [41d0e95039](https://linux-hardware.org/?probe=41d0e95039) | Jul 23, 2022 |
| Timi          | Redmi Book Pro 15 2022      | [3428364c49](https://linux-hardware.org/?probe=3428364c49) | Jul 22, 2022 |
| Acer          | Nitro AN515-55              | [85f2ffe45a](https://linux-hardware.org/?probe=85f2ffe45a) | Jul 22, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [b8ce5a0377](https://linux-hardware.org/?probe=b8ce5a0377) | Jul 22, 2022 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | [02dd3c2357](https://linux-hardware.org/?probe=02dd3c2357) | Jul 21, 2022 |
| Samsung       | 935XDB                      | [e01b518899](https://linux-hardware.org/?probe=e01b518899) | Jul 21, 2022 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [8505a7d575](https://linux-hardware.org/?probe=8505a7d575) | Jul 21, 2022 |
| Lenovo        | Legion Y7000P 2019 81Q5     | [d101f95ac2](https://linux-hardware.org/?probe=d101f95ac2) | Jul 20, 2022 |
| Lenovo        | V570 HuronRiver Platform    | [7e317412e0](https://linux-hardware.org/?probe=7e317412e0) | Jul 20, 2022 |
| HP            | ProBook 640 G5              | [36a725c595](https://linux-hardware.org/?probe=36a725c595) | Jul 19, 2022 |
| MSI           | Stealth GS77 12UGS          | [8d6d581aac](https://linux-hardware.org/?probe=8d6d581aac) | Jul 19, 2022 |
| Acer          | Aspire A515-45              | [323aa03c61](https://linux-hardware.org/?probe=323aa03c61) | Jul 18, 2022 |
| ASUSTek       | GL752VW                     | [b13a184720](https://linux-hardware.org/?probe=b13a184720) | Jul 18, 2022 |
| HP            | ZHAN 99 Mobile Workstati... | [cafc6119f3](https://linux-hardware.org/?probe=cafc6119f3) | Jul 18, 2022 |
| MSI           | GS75 Stealth 9SF            | [24e8aca8d1](https://linux-hardware.org/?probe=24e8aca8d1) | Jul 17, 2022 |
| System76      | Lemur Pro                   | [a4adde6cf9](https://linux-hardware.org/?probe=a4adde6cf9) | Jul 17, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [321c1a6e7a](https://linux-hardware.org/?probe=321c1a6e7a) | Jul 17, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [03839f9fef](https://linux-hardware.org/?probe=03839f9fef) | Jul 17, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | [ebcca43b7f](https://linux-hardware.org/?probe=ebcca43b7f) | Jul 17, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | [e94cde9ec6](https://linux-hardware.org/?probe=e94cde9ec6) | Jul 17, 2022 |
| Dell          | Latitude E6540              | [595eeced49](https://linux-hardware.org/?probe=595eeced49) | Jul 16, 2022 |
| Dell          | Latitude E6540              | [804dad339b](https://linux-hardware.org/?probe=804dad339b) | Jul 16, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [a6e936c29d](https://linux-hardware.org/?probe=a6e936c29d) | Jul 16, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [d465259da1](https://linux-hardware.org/?probe=d465259da1) | Jul 16, 2022 |
| HP            | ProBook 640 G5              | [93e838afb1](https://linux-hardware.org/?probe=93e838afb1) | Jul 16, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [1dc42453a1](https://linux-hardware.org/?probe=1dc42453a1) | Jul 15, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [164d1ff988](https://linux-hardware.org/?probe=164d1ff988) | Jul 15, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [e4530dd7b4](https://linux-hardware.org/?probe=e4530dd7b4) | Jul 15, 2022 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [c475c84f19](https://linux-hardware.org/?probe=c475c84f19) | Jul 15, 2022 |
| HP            | EliteBook 8570w             | [c21885de7f](https://linux-hardware.org/?probe=c21885de7f) | Jul 15, 2022 |
| MSI           | Stealth GS77 12UGS          | [b5f57e7b95](https://linux-hardware.org/?probe=b5f57e7b95) | Jul 14, 2022 |
| Hyperbook     | Z15 Zen                     | [41129ecc5e](https://linux-hardware.org/?probe=41129ecc5e) | Jul 14, 2022 |
| Dell          | Inspiron 7570               | [872ca81b40](https://linux-hardware.org/?probe=872ca81b40) | Jul 13, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [896226e566](https://linux-hardware.org/?probe=896226e566) | Jul 13, 2022 |
| Lenovo        | ThinkPad T430 2349CV8       | [fac90d81d0](https://linux-hardware.org/?probe=fac90d81d0) | Jul 13, 2022 |
| HP            | Pavilion Laptop 13-an0xx... | [6021e75347](https://linux-hardware.org/?probe=6021e75347) | Jul 13, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [eb05f4aed9](https://linux-hardware.org/?probe=eb05f4aed9) | Jul 13, 2022 |
| Toshiba       | Satellite M645              | [0149367a4e](https://linux-hardware.org/?probe=0149367a4e) | Jul 12, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [eac5600627](https://linux-hardware.org/?probe=eac5600627) | Jul 12, 2022 |
| Notebook      | NL5xRU                      | [a4bc7e790c](https://linux-hardware.org/?probe=a4bc7e790c) | Jul 11, 2022 |
| HP            | ProBook 440 G6              | [6a065093ba](https://linux-hardware.org/?probe=6a065093ba) | Jul 10, 2022 |
| Acer          | Nitro AN515-44              | [1478a70c4b](https://linux-hardware.org/?probe=1478a70c4b) | Jul 10, 2022 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [de4d640168](https://linux-hardware.org/?probe=de4d640168) | Jul 10, 2022 |
| Acer          | Nitro AN515-45              | [a9dd7c4072](https://linux-hardware.org/?probe=a9dd7c4072) | Jul 08, 2022 |
| ASUSTek       | U36SG                       | [878e0283d9](https://linux-hardware.org/?probe=878e0283d9) | Jul 08, 2022 |
| ASUSTek       | GL702VSK                    | [4fe32d25e5](https://linux-hardware.org/?probe=4fe32d25e5) | Jul 08, 2022 |
| Apple         | MacBookPro12,1              | [62fb099dfd](https://linux-hardware.org/?probe=62fb099dfd) | Jul 07, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [f7ecc76d69](https://linux-hardware.org/?probe=f7ecc76d69) | Jul 07, 2022 |
| Acer          | Nitro AN515-55              | [8e7d7a945f](https://linux-hardware.org/?probe=8e7d7a945f) | Jul 06, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [92b59598e5](https://linux-hardware.org/?probe=92b59598e5) | Jul 06, 2022 |
| MSI           | GP66 Leopard 10UH           | [dcbe6f403d](https://linux-hardware.org/?probe=dcbe6f403d) | Jul 06, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [9ad51a3a2c](https://linux-hardware.org/?probe=9ad51a3a2c) | Jul 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [341858c479](https://linux-hardware.org/?probe=341858c479) | Jul 05, 2022 |
| MSI           | GP66 Leopard 11UG           | [bc37067029](https://linux-hardware.org/?probe=bc37067029) | Jul 05, 2022 |
| Acer          | Aspire E5-522               | [9693c1d4ff](https://linux-hardware.org/?probe=9693c1d4ff) | Jul 04, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [4829f98af6](https://linux-hardware.org/?probe=4829f98af6) | Jul 04, 2022 |
| HP            | 250 G6 Notebook PC          | [fed0993c92](https://linux-hardware.org/?probe=fed0993c92) | Jul 03, 2022 |
| Dell          | Vostro 2420                 | [ce9585eac5](https://linux-hardware.org/?probe=ce9585eac5) | Jul 03, 2022 |
| Intel         | HuronRiver Platform         | [c0d79569d8](https://linux-hardware.org/?probe=c0d79569d8) | Jul 03, 2022 |
| Acer          | Aspire VX5-591G             | [5393a13046](https://linux-hardware.org/?probe=5393a13046) | Jul 02, 2022 |
| Infinix       | INBOOK X2                   | [eedac976d8](https://linux-hardware.org/?probe=eedac976d8) | Jul 02, 2022 |
| Acer          | Swift SF314-42              | [bd4792ebd8](https://linux-hardware.org/?probe=bd4792ebd8) | Jul 02, 2022 |
| Apple         | MacBookPro14,1              | [aad648ac8d](https://linux-hardware.org/?probe=aad648ac8d) | Jul 02, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | [5950f35d56](https://linux-hardware.org/?probe=5950f35d56) | Jul 02, 2022 |
| ASUSTek       | ROG Strix G713RW_G713RW     | [6904140540](https://linux-hardware.org/?probe=6904140540) | Jul 02, 2022 |
| Razer         | Blade 14 (2022) - RZ09-0... | [927dbb8452](https://linux-hardware.org/?probe=927dbb8452) | Jul 01, 2022 |
| Razer         | Blade 15 Base Model (Ear... | [7e809da3ad](https://linux-hardware.org/?probe=7e809da3ad) | Jul 01, 2022 |
| Lenovo        | ThinkPad W510 4318CTO       | [27cd378ed6](https://linux-hardware.org/?probe=27cd378ed6) | Jul 01, 2022 |
| HP            | Pavilion g4                 | [3626d9afe4](https://linux-hardware.org/?probe=3626d9afe4) | Jul 01, 2022 |
| Dell          | XPS M1330                   | [b891e49fac](https://linux-hardware.org/?probe=b891e49fac) | Jun 30, 2022 |
| HP            | EliteBook 8470p             | [96b07cbbd5](https://linux-hardware.org/?probe=96b07cbbd5) | Jun 30, 2022 |
| ASUSTek       | ROG Strix G713RW_G713RW     | [abebd5c659](https://linux-hardware.org/?probe=abebd5c659) | Jun 30, 2022 |
| Dell          | Vostro 5625                 | [0a047126ba](https://linux-hardware.org/?probe=0a047126ba) | Jun 30, 2022 |
| HUAWEI        | HVY-WXX9                    | [e7f3ea5cf5](https://linux-hardware.org/?probe=e7f3ea5cf5) | Jun 30, 2022 |
| Infinix       | INBOOK X2                   | [1c87102f96](https://linux-hardware.org/?probe=1c87102f96) | Jun 29, 2022 |
| Lenovo        | ThinkPad P50 20EQS5M100     | [d0b6aa0a1a](https://linux-hardware.org/?probe=d0b6aa0a1a) | Jun 29, 2022 |
| Dell          | XPS 13 9310                 | [6a2b56796c](https://linux-hardware.org/?probe=6a2b56796c) | Jun 28, 2022 |
| Acer          | Aspire M5-582PT             | [e159de9f3e](https://linux-hardware.org/?probe=e159de9f3e) | Jun 28, 2022 |
| HP            | EliteBook 840 G2            | [79a978476b](https://linux-hardware.org/?probe=79a978476b) | Jun 28, 2022 |
| Dell          | Latitude 7350               | [427cc37d76](https://linux-hardware.org/?probe=427cc37d76) | Jun 28, 2022 |
| Dell          | Latitude 7350               | [65d1c5c6f5](https://linux-hardware.org/?probe=65d1c5c6f5) | Jun 28, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [20054c6da2](https://linux-hardware.org/?probe=20054c6da2) | Jun 27, 2022 |
| Lenovo        | ThinkPad T580 20LAS6XC00    | [a4b9098138](https://linux-hardware.org/?probe=a4b9098138) | Jun 26, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [0beecf61e4](https://linux-hardware.org/?probe=0beecf61e4) | Jun 26, 2022 |
| Dell          | Inspiron 3442               | [72286bac00](https://linux-hardware.org/?probe=72286bac00) | Jun 26, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [68e2e0bbdb](https://linux-hardware.org/?probe=68e2e0bbdb) | Jun 25, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [27343a622f](https://linux-hardware.org/?probe=27343a622f) | Jun 25, 2022 |
| Dell          | Latitude 5420               | [2149a24612](https://linux-hardware.org/?probe=2149a24612) | Jun 25, 2022 |
| Dell          | Latitude 5490               | [4c3d48724c](https://linux-hardware.org/?probe=4c3d48724c) | Jun 25, 2022 |
| Dell          | Latitude 5490               | [3bb8a81dbf](https://linux-hardware.org/?probe=3bb8a81dbf) | Jun 25, 2022 |
| ASUSTek       | G551JM                      | [2d8e7ffcb2](https://linux-hardware.org/?probe=2d8e7ffcb2) | Jun 24, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [e575e05b18](https://linux-hardware.org/?probe=e575e05b18) | Jun 24, 2022 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | [5bd3ad4d01](https://linux-hardware.org/?probe=5bd3ad4d01) | Jun 24, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [fac01563a9](https://linux-hardware.org/?probe=fac01563a9) | Jun 24, 2022 |
| Acer          | Nitro AN715-51              | [a8df58056b](https://linux-hardware.org/?probe=a8df58056b) | Jun 24, 2022 |
| Lenovo        | ThinkPad T580 20LAS6XC00    | [55e631d9b6](https://linux-hardware.org/?probe=55e631d9b6) | Jun 24, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [1780abcf08](https://linux-hardware.org/?probe=1780abcf08) | Jun 24, 2022 |
| Lenovo        | Legion Y740-15IRHg 81UH     | [e0da282c48](https://linux-hardware.org/?probe=e0da282c48) | Jun 23, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [a1a0b3b43b](https://linux-hardware.org/?probe=a1a0b3b43b) | Jun 23, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [cacc2464af](https://linux-hardware.org/?probe=cacc2464af) | Jun 23, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [7d5a943ab0](https://linux-hardware.org/?probe=7d5a943ab0) | Jun 23, 2022 |
| Dell          | Vostro 2420                 | [2d50f4b4d8](https://linux-hardware.org/?probe=2d50f4b4d8) | Jun 23, 2022 |
| Acer          | Nitro AN515-55              | [c4b2a02630](https://linux-hardware.org/?probe=c4b2a02630) | Jun 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [f2b61e1e02](https://linux-hardware.org/?probe=f2b61e1e02) | Jun 23, 2022 |
| Acer          | Aspire E1-570               | [906b1f465e](https://linux-hardware.org/?probe=906b1f465e) | Jun 23, 2022 |
| Razer         | Blade                       | [6c8b201cd9](https://linux-hardware.org/?probe=6c8b201cd9) | Jun 23, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [51ec938467](https://linux-hardware.org/?probe=51ec938467) | Jun 22, 2022 |
| LG Electro... | 15Z95N-G.AAC6U1             | [c5b4596c19](https://linux-hardware.org/?probe=c5b4596c19) | Jun 22, 2022 |
| Acer          | Nitro AN515-55              | [bc159b637c](https://linux-hardware.org/?probe=bc159b637c) | Jun 22, 2022 |
| Dell          | Vostro 2420                 | [84a4eb23c6](https://linux-hardware.org/?probe=84a4eb23c6) | Jun 21, 2022 |
| Acer          | Ferrari One 200             | [52ba124048](https://linux-hardware.org/?probe=52ba124048) | Jun 21, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [a8d78740e8](https://linux-hardware.org/?probe=a8d78740e8) | Jun 21, 2022 |
| HUAWEI        | KLVL-WXXW                   | [4539c26ede](https://linux-hardware.org/?probe=4539c26ede) | Jun 21, 2022 |
| HUAWEI        | KLVL-WXXW                   | [cf80e45435](https://linux-hardware.org/?probe=cf80e45435) | Jun 21, 2022 |
| Apple         | MacBookPro16,1              | [35f551b127](https://linux-hardware.org/?probe=35f551b127) | Jun 21, 2022 |
| HP            | EliteBook 8570w             | [2530e2e400](https://linux-hardware.org/?probe=2530e2e400) | Jun 21, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [9a9dd8fa0c](https://linux-hardware.org/?probe=9a9dd8fa0c) | Jun 21, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | [ff5ed1835c](https://linux-hardware.org/?probe=ff5ed1835c) | Jun 20, 2022 |
| Philco        | OEM                         | [bee7961704](https://linux-hardware.org/?probe=bee7961704) | Jun 20, 2022 |
| HONOR         | HYM-WXX                     | [9eb7129a46](https://linux-hardware.org/?probe=9eb7129a46) | Jun 20, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [fc053b8a95](https://linux-hardware.org/?probe=fc053b8a95) | Jun 20, 2022 |
| HP            | ENVY dv7                    | [22dec86487](https://linux-hardware.org/?probe=22dec86487) | Jun 20, 2022 |
| ASUSTek       | GL502VMK                    | [d872e88532](https://linux-hardware.org/?probe=d872e88532) | Jun 20, 2022 |
| ASUSTek       | X550JX                      | [999d6e4735](https://linux-hardware.org/?probe=999d6e4735) | Jun 20, 2022 |
| Framework     | Laptop                      | [f5ece7ce85](https://linux-hardware.org/?probe=f5ece7ce85) | Jun 19, 2022 |
| Toshiba       | Satellite Click 10 LX5W-... | [b8f87c8ede](https://linux-hardware.org/?probe=b8f87c8ede) | Jun 19, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [fcbbdaf844](https://linux-hardware.org/?probe=fcbbdaf844) | Jun 18, 2022 |
| HUAWEI        | KPR-WX9                     | [4c08060155](https://linux-hardware.org/?probe=4c08060155) | Jun 18, 2022 |
| HP            | EliteBook 8460p             | [e19c095325](https://linux-hardware.org/?probe=e19c095325) | Jun 18, 2022 |
| Acer          | Nitro AN515-44              | [9ed8b5c759](https://linux-hardware.org/?probe=9ed8b5c759) | Jun 17, 2022 |
| Lenovo        | ThinkPad P50 20EQS31G00     | [2e98922741](https://linux-hardware.org/?probe=2e98922741) | Jun 17, 2022 |
| Dell          | Latitude E5450              | [42f5a53e24](https://linux-hardware.org/?probe=42f5a53e24) | Jun 16, 2022 |
| HP            | Laptop 15-dw2xxx            | [7eee6145a1](https://linux-hardware.org/?probe=7eee6145a1) | Jun 16, 2022 |
| ASUSTek       | X411UA                      | [da7deca26c](https://linux-hardware.org/?probe=da7deca26c) | Jun 16, 2022 |
| ASUSTek       | T100HAN                     | [20105d0e64](https://linux-hardware.org/?probe=20105d0e64) | Jun 16, 2022 |
| Acer          | Swift SF314-511             | [c414ab98c5](https://linux-hardware.org/?probe=c414ab98c5) | Jun 16, 2022 |
| MSI           | GP66 Leopard 11UG           | [ffcca1ccac](https://linux-hardware.org/?probe=ffcca1ccac) | Jun 16, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | [27d9d9e55e](https://linux-hardware.org/?probe=27d9d9e55e) | Jun 16, 2022 |
| Lenovo        | ThinkPad P50 20EQS31G00     | [51042aca4a](https://linux-hardware.org/?probe=51042aca4a) | Jun 15, 2022 |
| Acer          | Nitro AN515-55              | [bb631825e3](https://linux-hardware.org/?probe=bb631825e3) | Jun 15, 2022 |
| Lenovo        | ThinkPad E490 20N8002APB    | [3a17ac0192](https://linux-hardware.org/?probe=3a17ac0192) | Jun 15, 2022 |
| Acer          | Nitro AN515-55              | [670d05fbe3](https://linux-hardware.org/?probe=670d05fbe3) | Jun 15, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [527587d2b9](https://linux-hardware.org/?probe=527587d2b9) | Jun 14, 2022 |
| GPU Compan... | GWTN141-10                  | [c856f6d54f](https://linux-hardware.org/?probe=c856f6d54f) | Jun 14, 2022 |
| Timi          | TM1701                      | [e57d1ac956](https://linux-hardware.org/?probe=e57d1ac956) | Jun 14, 2022 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [ee0b4c4389](https://linux-hardware.org/?probe=ee0b4c4389) | Jun 14, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | [c87c87881e](https://linux-hardware.org/?probe=c87c87881e) | Jun 14, 2022 |
| Google        | Quawks                      | [c513bb8294](https://linux-hardware.org/?probe=c513bb8294) | Jun 14, 2022 |
| ASUSTek       | U36SG                       | [d5c67322d4](https://linux-hardware.org/?probe=d5c67322d4) | Jun 14, 2022 |
| HONOR         | HYM-WXX                     | [0f745d7bc7](https://linux-hardware.org/?probe=0f745d7bc7) | Jun 13, 2022 |
| HP            | Laptop 15-dw2xxx            | [cdc0b49b72](https://linux-hardware.org/?probe=cdc0b49b72) | Jun 13, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [e33ea31f97](https://linux-hardware.org/?probe=e33ea31f97) | Jun 13, 2022 |
| HP            | Laptop 15q-bu0xx            | [859d1ddbb0](https://linux-hardware.org/?probe=859d1ddbb0) | Jun 13, 2022 |
| Samsung       | 670Z5E                      | [049e305b33](https://linux-hardware.org/?probe=049e305b33) | Jun 13, 2022 |
| Dell          | Inspiron 1545               | [ac1f1fe24f](https://linux-hardware.org/?probe=ac1f1fe24f) | Jun 12, 2022 |
| ASUSTek       | T100HAN                     | [9a5b9400a1](https://linux-hardware.org/?probe=9a5b9400a1) | Jun 12, 2022 |
| HP            | ProBook 440 G4              | [52efea465c](https://linux-hardware.org/?probe=52efea465c) | Jun 12, 2022 |
| HP            | ProBook 440 G4              | [731e6f4aa8](https://linux-hardware.org/?probe=731e6f4aa8) | Jun 12, 2022 |
| Dell          | Precision 7520              | [002f7ce017](https://linux-hardware.org/?probe=002f7ce017) | Jun 12, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [e414ea3e15](https://linux-hardware.org/?probe=e414ea3e15) | Jun 11, 2022 |
| Alienware     | m15 R4                      | [5299db8f70](https://linux-hardware.org/?probe=5299db8f70) | Jun 11, 2022 |
| ASUSTek       | X555LD                      | [d5d6eeb639](https://linux-hardware.org/?probe=d5d6eeb639) | Jun 11, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [c8f8c1a8e3](https://linux-hardware.org/?probe=c8f8c1a8e3) | Jun 10, 2022 |
| HUAWEI        | CREM-WXX9                   | [91580d9a20](https://linux-hardware.org/?probe=91580d9a20) | Jun 10, 2022 |
| Fujitsu       | LIFEBOOK E556               | [1dd2b6a645](https://linux-hardware.org/?probe=1dd2b6a645) | Jun 10, 2022 |
| Lenovo        | ThinkPad X230 2325TXV       | [67f152d520](https://linux-hardware.org/?probe=67f152d520) | Jun 10, 2022 |
| ASUSTek       | ROG Strix G513QR_G513QR     | [e33e73a70f](https://linux-hardware.org/?probe=e33e73a70f) | Jun 10, 2022 |
| Lenovo        | ThinkPad X220 4291IR6       | [958f8bb25b](https://linux-hardware.org/?probe=958f8bb25b) | Jun 09, 2022 |
| Lenovo        | Unknown                     | [2921bcaa1c](https://linux-hardware.org/?probe=2921bcaa1c) | Jun 09, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [dcfb1c33aa](https://linux-hardware.org/?probe=dcfb1c33aa) | Jun 09, 2022 |
| Chuwi         | GemiBook Pro                | [737a4183c8](https://linux-hardware.org/?probe=737a4183c8) | Jun 07, 2022 |
| Avell High... | A62 LIV                     | [5a7be822e3](https://linux-hardware.org/?probe=5a7be822e3) | Jun 07, 2022 |
| Dell          | Precision 5550              | [a4bf41771c](https://linux-hardware.org/?probe=a4bf41771c) | Jun 07, 2022 |
| Lenovo        | ThinkPad T495 20NJ0007US    | [2b3ee11cad](https://linux-hardware.org/?probe=2b3ee11cad) | Jun 07, 2022 |
| HP            | EliteBook 840 G5            | [73ba6fe3c0](https://linux-hardware.org/?probe=73ba6fe3c0) | Jun 06, 2022 |
| Acer          | Nitro AN515-55              | [0546f2fdfd](https://linux-hardware.org/?probe=0546f2fdfd) | Jun 06, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [228fe8f3f1](https://linux-hardware.org/?probe=228fe8f3f1) | Jun 06, 2022 |
| Dell          | Latitude 5511               | [5d9a12a88d](https://linux-hardware.org/?probe=5d9a12a88d) | Jun 06, 2022 |
| Acer          | Nitro AN515-55              | [4ab9f94abe](https://linux-hardware.org/?probe=4ab9f94abe) | Jun 06, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | [6d46a6107c](https://linux-hardware.org/?probe=6d46a6107c) | Jun 06, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [f4dcc8e7a1](https://linux-hardware.org/?probe=f4dcc8e7a1) | Jun 06, 2022 |
| Samsung       | 550XBE/350XBE               | [4746fe546b](https://linux-hardware.org/?probe=4746fe546b) | Jun 05, 2022 |
| Lenovo        | ThinkPad T460p 20FW0005A... | [f9bd82bcd7](https://linux-hardware.org/?probe=f9bd82bcd7) | Jun 05, 2022 |
| Dell          | G3 3500                     | [6734206fa0](https://linux-hardware.org/?probe=6734206fa0) | Jun 05, 2022 |
| Fujitsu       | LIFEBOOK U937               | [44d3d1edad](https://linux-hardware.org/?probe=44d3d1edad) | Jun 04, 2022 |
| TUXEDO        | Book_XA1510                 | [6738253853](https://linux-hardware.org/?probe=6738253853) | Jun 04, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [66cc7342ec](https://linux-hardware.org/?probe=66cc7342ec) | Jun 04, 2022 |
| Acer          | Swift SF314-511             | [883f386564](https://linux-hardware.org/?probe=883f386564) | Jun 03, 2022 |
| Acer          | Swift SF314-511             | [ecd590c347](https://linux-hardware.org/?probe=ecd590c347) | Jun 03, 2022 |
| HP            | Pavilion Notebook           | [0fe589689b](https://linux-hardware.org/?probe=0fe589689b) | Jun 02, 2022 |
| Dell          | Latitude 9420               | [28ba6de10d](https://linux-hardware.org/?probe=28ba6de10d) | Jun 01, 2022 |
| Lenovo        | ThinkPad X200T 7449G6G      | [fd7f5dd506](https://linux-hardware.org/?probe=fd7f5dd506) | Jun 01, 2022 |
| Lenovo        | ThinkPad X200s 74663RG      | [84efabac8f](https://linux-hardware.org/?probe=84efabac8f) | Jun 01, 2022 |
| MSI           | Bravo 15 B5DD               | [4ae400000f](https://linux-hardware.org/?probe=4ae400000f) | Jun 01, 2022 |
| MSI           | Bravo 15 B5DD               | [d561d8dbdb](https://linux-hardware.org/?probe=d561d8dbdb) | Jun 01, 2022 |
| Lenovo        | ThinkPad X200s 74663RG      | [460e11ebe2](https://linux-hardware.org/?probe=460e11ebe2) | May 31, 2022 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | [3195728920](https://linux-hardware.org/?probe=3195728920) | May 31, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [799a25df83](https://linux-hardware.org/?probe=799a25df83) | May 31, 2022 |
| Dell          | Latitude 5511               | [ef262c4020](https://linux-hardware.org/?probe=ef262c4020) | May 31, 2022 |
| Dell          | Inspiron 5567               | [2f14b6956f](https://linux-hardware.org/?probe=2f14b6956f) | May 31, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [49c400d1f7](https://linux-hardware.org/?probe=49c400d1f7) | May 31, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [deaac8464e](https://linux-hardware.org/?probe=deaac8464e) | May 31, 2022 |
| HP            | EliteBook 8470p             | [6b22d31e8e](https://linux-hardware.org/?probe=6b22d31e8e) | May 31, 2022 |
| Lenovo        | ThinkPad T460p 20FW0005A... | [df0f623625](https://linux-hardware.org/?probe=df0f623625) | May 30, 2022 |
| Dell          | Latitude 5511               | [33b796acff](https://linux-hardware.org/?probe=33b796acff) | May 30, 2022 |
| ASUSTek       | X555UQ                      | [c266f3d070](https://linux-hardware.org/?probe=c266f3d070) | May 30, 2022 |
| Dell          | Inspiron 15-3567            | [3299abfc78](https://linux-hardware.org/?probe=3299abfc78) | May 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [c71a8e9817](https://linux-hardware.org/?probe=c71a8e9817) | May 29, 2022 |
| Timi          | TM1604                      | [cd9b839800](https://linux-hardware.org/?probe=cd9b839800) | May 29, 2022 |
| Lenovo        | Legion Y7000P2020H 82AX     | [220325c031](https://linux-hardware.org/?probe=220325c031) | May 29, 2022 |
| HP            | Laptop 15-dy2xxx            | [1c71dac18b](https://linux-hardware.org/?probe=1c71dac18b) | May 29, 2022 |
| ASUSTek       | GL502VSK                    | [44fb5da9d6](https://linux-hardware.org/?probe=44fb5da9d6) | May 29, 2022 |
| eMachines     | eM350                       | [2573854a09](https://linux-hardware.org/?probe=2573854a09) | May 29, 2022 |
| SLIMBOOK      | TITAN                       | [1029a819d7](https://linux-hardware.org/?probe=1029a819d7) | May 29, 2022 |
| SLIMBOOK      | TITAN                       | [c4e27f4d19](https://linux-hardware.org/?probe=c4e27f4d19) | May 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [de7ed0046e](https://linux-hardware.org/?probe=de7ed0046e) | May 29, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [09aa4c998d](https://linux-hardware.org/?probe=09aa4c998d) | May 28, 2022 |
| ASUSTek       | G750JX                      | [dfb08cef0b](https://linux-hardware.org/?probe=dfb08cef0b) | May 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [ae044ab2d9](https://linux-hardware.org/?probe=ae044ab2d9) | May 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [b8c8e8baef](https://linux-hardware.org/?probe=b8c8e8baef) | May 27, 2022 |
| System76      | Lemur Pro                   | [dcfd3abdd6](https://linux-hardware.org/?probe=dcfd3abdd6) | May 26, 2022 |
| Lenovo        | IdeaPad Z580                | [4b1c87e746](https://linux-hardware.org/?probe=4b1c87e746) | May 26, 2022 |
| Dell          | G15 5515                    | [4f47780467](https://linux-hardware.org/?probe=4f47780467) | May 26, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [1eecb7a012](https://linux-hardware.org/?probe=1eecb7a012) | May 26, 2022 |
| Lenovo        | IdeaPad 310-14ISK 80UG      | [2eb4f98b37](https://linux-hardware.org/?probe=2eb4f98b37) | May 26, 2022 |
| Acer          | Aspire A515-46              | [e004aa3fd2](https://linux-hardware.org/?probe=e004aa3fd2) | May 25, 2022 |
| Lenovo        | IdeaPad 310-14ISK 80UG      | [4b23940919](https://linux-hardware.org/?probe=4b23940919) | May 25, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [c8051b3bfc](https://linux-hardware.org/?probe=c8051b3bfc) | May 24, 2022 |
| HP            | Pavilion 15                 | [4140810d35](https://linux-hardware.org/?probe=4140810d35) | May 24, 2022 |
| System76      | Oryx Pro                    | [f95bed2419](https://linux-hardware.org/?probe=f95bed2419) | May 24, 2022 |
| System76      | Oryx Pro                    | [10502c5379](https://linux-hardware.org/?probe=10502c5379) | May 24, 2022 |
| Dell          | Inspiron N4010              | [872649a8b4](https://linux-hardware.org/?probe=872649a8b4) | May 23, 2022 |
| Acer          | Nitro AN515-45              | [293712cc51](https://linux-hardware.org/?probe=293712cc51) | May 23, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [5c74b9f6e4](https://linux-hardware.org/?probe=5c74b9f6e4) | May 23, 2022 |
| HP            | Pavilion 15                 | [ca77af8ab9](https://linux-hardware.org/?probe=ca77af8ab9) | May 23, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [5ab3662d65](https://linux-hardware.org/?probe=5ab3662d65) | May 22, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [fe1d187774](https://linux-hardware.org/?probe=fe1d187774) | May 22, 2022 |
| Dell          | Inspiron 3558               | [47b2310054](https://linux-hardware.org/?probe=47b2310054) | May 22, 2022 |
| Google        | Quawks                      | [cb763161cf](https://linux-hardware.org/?probe=cb763161cf) | May 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [f2c0dedc02](https://linux-hardware.org/?probe=f2c0dedc02) | May 20, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [99283be07b](https://linux-hardware.org/?probe=99283be07b) | May 20, 2022 |
| Dell          | XPS 15 9510                 | [ee62ecda2e](https://linux-hardware.org/?probe=ee62ecda2e) | May 19, 2022 |
| Apple         | MacBookPro8,1               | [e9a6f0bd85](https://linux-hardware.org/?probe=e9a6f0bd85) | May 19, 2022 |
| Google        | Caroline                    | [2b665e84d3](https://linux-hardware.org/?probe=2b665e84d3) | May 19, 2022 |
| Samsung       | 730QCJ/730QCR               | [08452b3686](https://linux-hardware.org/?probe=08452b3686) | May 19, 2022 |
| Lenovo        | IdeaPad U430p 20269         | [bcf848458f](https://linux-hardware.org/?probe=bcf848458f) | May 18, 2022 |
| HP            | ProBook 445 G7 Notebook ... | [e85e2e6559](https://linux-hardware.org/?probe=e85e2e6559) | May 18, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [2ee4916960](https://linux-hardware.org/?probe=2ee4916960) | May 18, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [153dab147a](https://linux-hardware.org/?probe=153dab147a) | May 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [843a31b222](https://linux-hardware.org/?probe=843a31b222) | May 17, 2022 |
| Acer          | Aspire A515-56              | [a32b5ba574](https://linux-hardware.org/?probe=a32b5ba574) | May 17, 2022 |
| Acer          | Aspire A515-56              | [27366d5566](https://linux-hardware.org/?probe=27366d5566) | May 17, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [a10241fd00](https://linux-hardware.org/?probe=a10241fd00) | May 17, 2022 |
| Dell          | Vostro 3405                 | [fcec5f1cdd](https://linux-hardware.org/?probe=fcec5f1cdd) | May 17, 2022 |
| Fujitsu Si... | AMILO Li 2727               | [d52e9e2938](https://linux-hardware.org/?probe=d52e9e2938) | May 17, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [21f3f7368f](https://linux-hardware.org/?probe=21f3f7368f) | May 17, 2022 |
| Dell          | Precision 5540              | [02576569ce](https://linux-hardware.org/?probe=02576569ce) | May 16, 2022 |
| Dell          | Inspiron 3458               | [5c4fca4c42](https://linux-hardware.org/?probe=5c4fca4c42) | May 16, 2022 |
| Lenovo        | ThinkPad W510 4318CTO       | [00acddbf24](https://linux-hardware.org/?probe=00acddbf24) | May 16, 2022 |
| HP            | Pavilion Laptop 13-an0xx... | [b4d7d75ad1](https://linux-hardware.org/?probe=b4d7d75ad1) | May 15, 2022 |
| Dell          | XPS 17 9710                 | [449c90c9dd](https://linux-hardware.org/?probe=449c90c9dd) | May 15, 2022 |
| MSI           | Stealth 15M A11SDK          | [0067badf7c](https://linux-hardware.org/?probe=0067badf7c) | May 15, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [0793a5608a](https://linux-hardware.org/?probe=0793a5608a) | May 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [84ae0966e6](https://linux-hardware.org/?probe=84ae0966e6) | May 15, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [d8361f7895](https://linux-hardware.org/?probe=d8361f7895) | May 14, 2022 |
| Dell          | Latitude E6400              | [2831bacde3](https://linux-hardware.org/?probe=2831bacde3) | May 13, 2022 |
| ASUSTek       | ROG Strix G513QE_G513QE     | [0a28329f7a](https://linux-hardware.org/?probe=0a28329f7a) | May 12, 2022 |
| MSI           | Alpha 15 B5EEK              | [ea8ce36bef](https://linux-hardware.org/?probe=ea8ce36bef) | May 12, 2022 |
| Dell          | Vostro 3405                 | [3c8e334d43](https://linux-hardware.org/?probe=3c8e334d43) | May 12, 2022 |
| Lenovo        | Unknown                     | [3cced8a4fa](https://linux-hardware.org/?probe=3cced8a4fa) | May 12, 2022 |
| MSI           | Modern 14 B5M               | [b207ce7566](https://linux-hardware.org/?probe=b207ce7566) | May 12, 2022 |
| Dell          | XPS 17 9710                 | [ff27218d11](https://linux-hardware.org/?probe=ff27218d11) | May 12, 2022 |
| Dell          | XPS 15 9510                 | [299f811f98](https://linux-hardware.org/?probe=299f811f98) | May 12, 2022 |
| Lenovo        | ThinkPad X230 23257Y1       | [0c4e13a23d](https://linux-hardware.org/?probe=0c4e13a23d) | May 11, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [0e3079b5a1](https://linux-hardware.org/?probe=0e3079b5a1) | May 11, 2022 |
| MSI           | GF75 Thin 9SC               | [6e8c40ad7c](https://linux-hardware.org/?probe=6e8c40ad7c) | May 10, 2022 |
| Dell          | Inspiron 5567               | [f09183023d](https://linux-hardware.org/?probe=f09183023d) | May 10, 2022 |
| Toshiba       | Satellite C55-A-1N0         | [c64d31da4e](https://linux-hardware.org/?probe=c64d31da4e) | May 10, 2022 |
| Notebook      | P65xHP                      | [b1205b8ca1](https://linux-hardware.org/?probe=b1205b8ca1) | May 10, 2022 |
| Dell          | Latitude E6430              | [a188e200b3](https://linux-hardware.org/?probe=a188e200b3) | May 10, 2022 |
| Acer          | Aspire A315-22              | [b3c9da4989](https://linux-hardware.org/?probe=b3c9da4989) | May 09, 2022 |
| Dell          | Inspiron 13-7378            | [768b19f0ff](https://linux-hardware.org/?probe=768b19f0ff) | May 09, 2022 |
| Dell          | Latitude E6430              | [a6b570e125](https://linux-hardware.org/?probe=a6b570e125) | May 08, 2022 |
| HUAWEI        | BOD-WXX9                    | [b0b389263a](https://linux-hardware.org/?probe=b0b389263a) | May 08, 2022 |
| Dell          | Latitude 3330               | [4f05d8475c](https://linux-hardware.org/?probe=4f05d8475c) | May 08, 2022 |
| Acer          | Aspire R7-371T              | [207110a3d4](https://linux-hardware.org/?probe=207110a3d4) | May 07, 2022 |
| Timi          | TM1604                      | [bc97206a3a](https://linux-hardware.org/?probe=bc97206a3a) | May 07, 2022 |
| HP            | ProBook 4530s               | [76fc5ea6ce](https://linux-hardware.org/?probe=76fc5ea6ce) | May 06, 2022 |
| Lenovo        | ThinkPad E15 20RD0011GE     | [795365ba55](https://linux-hardware.org/?probe=795365ba55) | May 06, 2022 |
| Lenovo        | B590 37613LG                | [b0226c712c](https://linux-hardware.org/?probe=b0226c712c) | May 06, 2022 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | [ac270166aa](https://linux-hardware.org/?probe=ac270166aa) | May 06, 2022 |
| Framework     | Laptop                      | [67c58248dd](https://linux-hardware.org/?probe=67c58248dd) | May 06, 2022 |
| Compal        | QAQXX                       | [d3211e6bc6](https://linux-hardware.org/?probe=d3211e6bc6) | May 05, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [fb4cf43d54](https://linux-hardware.org/?probe=fb4cf43d54) | May 05, 2022 |
| Apple         | MacBookAir7,2               | [8a9eed8fe0](https://linux-hardware.org/?probe=8a9eed8fe0) | May 05, 2022 |
| Apple         | MacBookAir7,2               | [0f36c83b15](https://linux-hardware.org/?probe=0f36c83b15) | May 05, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [0bbc6c64c2](https://linux-hardware.org/?probe=0bbc6c64c2) | May 05, 2022 |
| Dell          | Latitude 3340               | [b724073bff](https://linux-hardware.org/?probe=b724073bff) | May 05, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [3c081a7012](https://linux-hardware.org/?probe=3c081a7012) | May 04, 2022 |
| HP            | EliteBook 8470p             | [db81dd7652](https://linux-hardware.org/?probe=db81dd7652) | May 04, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [ee3b3dc380](https://linux-hardware.org/?probe=ee3b3dc380) | May 04, 2022 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [79491af642](https://linux-hardware.org/?probe=79491af642) | May 03, 2022 |
| Acer          | Aspire A517-51G             | [1dc71986aa](https://linux-hardware.org/?probe=1dc71986aa) | May 03, 2022 |
| Acer          | Aspire A517-51G             | [d0ad1ff2fe](https://linux-hardware.org/?probe=d0ad1ff2fe) | May 03, 2022 |
| Acer          | Nitro AN517-54              | [de2960b350](https://linux-hardware.org/?probe=de2960b350) | May 01, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [f937431614](https://linux-hardware.org/?probe=f937431614) | May 01, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [59e65b422b](https://linux-hardware.org/?probe=59e65b422b) | May 01, 2022 |
| MSI           | Modern 14 B5M               | [04dee023e6](https://linux-hardware.org/?probe=04dee023e6) | May 01, 2022 |
| Acer          | Aspire E5-571               | [35b5fa2276](https://linux-hardware.org/?probe=35b5fa2276) | Apr 30, 2022 |
| Dell          | Precision 7540              | [8b1b7dd8da](https://linux-hardware.org/?probe=8b1b7dd8da) | Apr 30, 2022 |
| Dell          | Precision M6600             | [bb40a22dd3](https://linux-hardware.org/?probe=bb40a22dd3) | Apr 29, 2022 |
| Acer          | Aspire A715-71G             | [ec6c90818c](https://linux-hardware.org/?probe=ec6c90818c) | Apr 29, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [96fc510369](https://linux-hardware.org/?probe=96fc510369) | Apr 29, 2022 |
| Razer         | Blade 15 Studio Edition ... | [563510a4b7](https://linux-hardware.org/?probe=563510a4b7) | Apr 28, 2022 |
| HP            | ZBook 17 G2                 | [81409450dc](https://linux-hardware.org/?probe=81409450dc) | Apr 28, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [ab11d6ac2f](https://linux-hardware.org/?probe=ab11d6ac2f) | Apr 28, 2022 |
| Acer          | Aspire ES1-572              | [25f9b83c30](https://linux-hardware.org/?probe=25f9b83c30) | Apr 28, 2022 |
| HP            | Notebook                    | [daaa31b65a](https://linux-hardware.org/?probe=daaa31b65a) | Apr 27, 2022 |
| ASUSTek       | E402SA                      | [4c5cbe705d](https://linux-hardware.org/?probe=4c5cbe705d) | Apr 27, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [ea3e0b8695](https://linux-hardware.org/?probe=ea3e0b8695) | Apr 26, 2022 |
| MouseCompu... | NH55Dx                      | [0a397dd5e7](https://linux-hardware.org/?probe=0a397dd5e7) | Apr 25, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [37a92322aa](https://linux-hardware.org/?probe=37a92322aa) | Apr 25, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [190d52b2d6](https://linux-hardware.org/?probe=190d52b2d6) | Apr 25, 2022 |
| Acer          | TravelMate P259-MG          | [debe4697b9](https://linux-hardware.org/?probe=debe4697b9) | Apr 23, 2022 |
| Dell          | Latitude 3340               | [e6aa31da26](https://linux-hardware.org/?probe=e6aa31da26) | Apr 23, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c90694a42c](https://linux-hardware.org/?probe=c90694a42c) | Apr 23, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [e97ab3fc6c](https://linux-hardware.org/?probe=e97ab3fc6c) | Apr 22, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [2c17462cda](https://linux-hardware.org/?probe=2c17462cda) | Apr 22, 2022 |
| Dell          | Latitude E5500              | [500b4b5ee2](https://linux-hardware.org/?probe=500b4b5ee2) | Apr 22, 2022 |
| Dell          | Inspiron 7577               | [ea4f513eb9](https://linux-hardware.org/?probe=ea4f513eb9) | Apr 22, 2022 |
| HP            | EliteBook 8470p             | [c1623a9f89](https://linux-hardware.org/?probe=c1623a9f89) | Apr 21, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [ce3b387afa](https://linux-hardware.org/?probe=ce3b387afa) | Apr 21, 2022 |
| Dell          | XPS 13 7390                 | [b2cc2161d3](https://linux-hardware.org/?probe=b2cc2161d3) | Apr 21, 2022 |
| Apple         | MacBookAir5,1               | [3dd8282149](https://linux-hardware.org/?probe=3dd8282149) | Apr 20, 2022 |
| Toshiba       | TECRA R940                  | [e7dc07a41c](https://linux-hardware.org/?probe=e7dc07a41c) | Apr 20, 2022 |
| Intel         | W7650                       | [cdf0885f07](https://linux-hardware.org/?probe=cdf0885f07) | Apr 20, 2022 |
| Dell          | XPS 13 9310                 | [e6f96a585c](https://linux-hardware.org/?probe=e6f96a585c) | Apr 18, 2022 |
| Alienware     | M11x                        | [df72ecbe58](https://linux-hardware.org/?probe=df72ecbe58) | Apr 18, 2022 |
| Avell High... | B.ON                        | [6f37e0aabc](https://linux-hardware.org/?probe=6f37e0aabc) | Apr 18, 2022 |
| Apple         | MacBookPro12,1              | [3c5f232016](https://linux-hardware.org/?probe=3c5f232016) | Apr 17, 2022 |
| TUXEDO        | Book_XA1510                 | [441b2fd4ab](https://linux-hardware.org/?probe=441b2fd4ab) | Apr 17, 2022 |
| TUXEDO        | Book_XA1510                 | [b109942662](https://linux-hardware.org/?probe=b109942662) | Apr 17, 2022 |
| HP            | ZBook 17 G2                 | [d7b7a81cbb](https://linux-hardware.org/?probe=d7b7a81cbb) | Apr 16, 2022 |
| Dell          | XPS 15 9560                 | [9529ed78e9](https://linux-hardware.org/?probe=9529ed78e9) | Apr 16, 2022 |
| Dell          | XPS 15 9560                 | [1ef9e4e85d](https://linux-hardware.org/?probe=1ef9e4e85d) | Apr 16, 2022 |
| Dell          | XPS 15 9560                 | [abee14fa00](https://linux-hardware.org/?probe=abee14fa00) | Apr 16, 2022 |
| Fujitsu       | LIFEBOOK P771               | [f9d5ba9c1c](https://linux-hardware.org/?probe=f9d5ba9c1c) | Apr 16, 2022 |
| Fujitsu       | LIFEBOOK P771               | [a6580631d1](https://linux-hardware.org/?probe=a6580631d1) | Apr 16, 2022 |
| LG Electro... | 15Z95P-G.AA78B              | [f5ef9987a4](https://linux-hardware.org/?probe=f5ef9987a4) | Apr 15, 2022 |
| MSI           | Creator 15 A10SFS           | [42b2140343](https://linux-hardware.org/?probe=42b2140343) | Apr 15, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [539ce7e59a](https://linux-hardware.org/?probe=539ce7e59a) | Apr 15, 2022 |
| Alienware     | x17 R1                      | [86a2d88704](https://linux-hardware.org/?probe=86a2d88704) | Apr 15, 2022 |
| Sony          | VPCF115FM                   | [b174df5915](https://linux-hardware.org/?probe=b174df5915) | Apr 15, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [078a3464bf](https://linux-hardware.org/?probe=078a3464bf) | Apr 15, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [cffdde259f](https://linux-hardware.org/?probe=cffdde259f) | Apr 15, 2022 |
| Dell          | Inspiron 7559               | [5302420f94](https://linux-hardware.org/?probe=5302420f94) | Apr 15, 2022 |
| Dell          | Latitude E7450              | [9af0006104](https://linux-hardware.org/?probe=9af0006104) | Apr 15, 2022 |
| Framework     | Laptop                      | [e4c994f47a](https://linux-hardware.org/?probe=e4c994f47a) | Apr 14, 2022 |
| HP            | Laptop 14-cf0xxx            | [3fcf4f7e02](https://linux-hardware.org/?probe=3fcf4f7e02) | Apr 14, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [68d7627d20](https://linux-hardware.org/?probe=68d7627d20) | Apr 14, 2022 |
| Sony          | VPCF115FM                   | [03f96804b2](https://linux-hardware.org/?probe=03f96804b2) | Apr 14, 2022 |
| Lenovo        | E31-80 80MX                 | [ea96e85c49](https://linux-hardware.org/?probe=ea96e85c49) | Apr 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [c49c891a78](https://linux-hardware.org/?probe=c49c891a78) | Apr 14, 2022 |
| Lenovo        | ThinkPad T480 20L6S93F00    | [b8c57e6b8a](https://linux-hardware.org/?probe=b8c57e6b8a) | Apr 14, 2022 |
| Lenovo        | ThinkPad X220 4291QT1       | [9e6fc630f4](https://linux-hardware.org/?probe=9e6fc630f4) | Apr 14, 2022 |
| Framework     | Laptop                      | [d4a02dfec9](https://linux-hardware.org/?probe=d4a02dfec9) | Apr 14, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [c9e8c79a2e](https://linux-hardware.org/?probe=c9e8c79a2e) | Apr 14, 2022 |
| Lenovo        | XiaoXin Chao7000-14IKBR ... | [2394088db1](https://linux-hardware.org/?probe=2394088db1) | Apr 14, 2022 |
| Framework     | Laptop                      | [b8850e9dc8](https://linux-hardware.org/?probe=b8850e9dc8) | Apr 14, 2022 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | [5f85d41ef2](https://linux-hardware.org/?probe=5f85d41ef2) | Apr 14, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [f3d294f808](https://linux-hardware.org/?probe=f3d294f808) | Apr 14, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [a7f25c6027](https://linux-hardware.org/?probe=a7f25c6027) | Apr 14, 2022 |
| Dell          | G5 5505                     | [7c8b949b95](https://linux-hardware.org/?probe=7c8b949b95) | Apr 14, 2022 |
| HP            | ENVY Notebook               | [2b982a201c](https://linux-hardware.org/?probe=2b982a201c) | Apr 14, 2022 |
| Lenovo        | ThinkPad T550 20CKCTO1WW    | [81d6a811d5](https://linux-hardware.org/?probe=81d6a811d5) | Apr 14, 2022 |
| Lenovo        | ThinkPad T410 2537E82       | [84026a1dd3](https://linux-hardware.org/?probe=84026a1dd3) | Apr 14, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [c68c62f98c](https://linux-hardware.org/?probe=c68c62f98c) | Apr 14, 2022 |
| Framework     | Laptop                      | [16d27bad7a](https://linux-hardware.org/?probe=16d27bad7a) | Apr 14, 2022 |
| Lenovo        | IdeaPad S540-13ARE 82DL     | [17363a1a13](https://linux-hardware.org/?probe=17363a1a13) | Apr 14, 2022 |
| HP            | ZBook Firefly 15 G7 Mobi... | [0e9e99acae](https://linux-hardware.org/?probe=0e9e99acae) | Apr 13, 2022 |
| Monster       | ABRA A5 V15.8               | [28f1e82585](https://linux-hardware.org/?probe=28f1e82585) | Apr 13, 2022 |
| Lenovo        | ThinkPad X220 4291QT1       | [58ef1f3594](https://linux-hardware.org/?probe=58ef1f3594) | Apr 13, 2022 |
| Apple         | MacBookPro10,2              | [cf7c54ff19](https://linux-hardware.org/?probe=cf7c54ff19) | Apr 13, 2022 |
| Lenovo        | ThinkPad T440p 20AN006GU... | [8c26cf3ce0](https://linux-hardware.org/?probe=8c26cf3ce0) | Apr 13, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [6dc0087ab4](https://linux-hardware.org/?probe=6dc0087ab4) | Apr 13, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [b076cac85d](https://linux-hardware.org/?probe=b076cac85d) | Apr 13, 2022 |
| Samsung       | 270E5J/2570EJ               | [4aeb8de6f6](https://linux-hardware.org/?probe=4aeb8de6f6) | Apr 13, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [90505ddcfa](https://linux-hardware.org/?probe=90505ddcfa) | Apr 13, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [eff12a28fd](https://linux-hardware.org/?probe=eff12a28fd) | Apr 13, 2022 |
| Lenovo        | ThinkPad T490s 20NY000JM... | [e93e7d9ad1](https://linux-hardware.org/?probe=e93e7d9ad1) | Apr 13, 2022 |
| Lenovo        | ThinkPad T490s 20NXCTO1W... | [2edcc0aefa](https://linux-hardware.org/?probe=2edcc0aefa) | Apr 13, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [32371c52a6](https://linux-hardware.org/?probe=32371c52a6) | Apr 13, 2022 |
| Apple         | MacBookPro8,1               | [fad4436356](https://linux-hardware.org/?probe=fad4436356) | Apr 13, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [75f2876f06](https://linux-hardware.org/?probe=75f2876f06) | Apr 12, 2022 |
| Lenovo        | V130-15IGM 81HL             | [c74caa4194](https://linux-hardware.org/?probe=c74caa4194) | Apr 12, 2022 |
| Dell          | Vostro 14-5459              | [89d65f0a36](https://linux-hardware.org/?probe=89d65f0a36) | Apr 12, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [7c4eb57bca](https://linux-hardware.org/?probe=7c4eb57bca) | Apr 12, 2022 |
| Razer         | Blade                       | [13c7eb09fa](https://linux-hardware.org/?probe=13c7eb09fa) | Apr 12, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [7007f9e0fc](https://linux-hardware.org/?probe=7007f9e0fc) | Apr 12, 2022 |
| Framework     | Laptop                      | [02b837b78a](https://linux-hardware.org/?probe=02b837b78a) | Apr 12, 2022 |
| Dell          | Latitude 5480               | [f733f24fdc](https://linux-hardware.org/?probe=f733f24fdc) | Apr 12, 2022 |
| ASUSTek       | S551LN                      | [8795a49142](https://linux-hardware.org/?probe=8795a49142) | Apr 12, 2022 |
| ASUSTek       | S551LN                      | [4999fb1eff](https://linux-hardware.org/?probe=4999fb1eff) | Apr 12, 2022 |
| HUAWEI        | KLVL-WXX9                   | [47cecc43f6](https://linux-hardware.org/?probe=47cecc43f6) | Apr 11, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [a86b688768](https://linux-hardware.org/?probe=a86b688768) | Apr 11, 2022 |
| Dell          | Precision M6800             | [571eab63d2](https://linux-hardware.org/?probe=571eab63d2) | Apr 10, 2022 |
| Dell          | Precision M6800             | [236217f64d](https://linux-hardware.org/?probe=236217f64d) | Apr 10, 2022 |
| Acer          | One 14 Z2-485               | [57f307fa80](https://linux-hardware.org/?probe=57f307fa80) | Apr 09, 2022 |
| Lenovo        | XiaoXin Air 13IML 81WV      | [c5ae7c810d](https://linux-hardware.org/?probe=c5ae7c810d) | Apr 09, 2022 |
| HP            | Pavilion Notebook           | [f76d101440](https://linux-hardware.org/?probe=f76d101440) | Apr 09, 2022 |
| Acer          | Nitro AN515-45              | [ce9698e187](https://linux-hardware.org/?probe=ce9698e187) | Apr 09, 2022 |
| Lenovo        | Yoga Slim 7 Carbon 14ACN... | [5328fde624](https://linux-hardware.org/?probe=5328fde624) | Apr 08, 2022 |
| LG Electro... | S430-G.BC33P1               | [95f8d514d6](https://linux-hardware.org/?probe=95f8d514d6) | Apr 08, 2022 |
| Acer          | Aspire A515-44              | [9dfd75a7dd](https://linux-hardware.org/?probe=9dfd75a7dd) | Apr 07, 2022 |
| Dell          | Latitude 5480               | [4e82478bdf](https://linux-hardware.org/?probe=4e82478bdf) | Apr 07, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [345734b3fd](https://linux-hardware.org/?probe=345734b3fd) | Apr 07, 2022 |
| Dell          | XPS 13 9310                 | [a497a79602](https://linux-hardware.org/?probe=a497a79602) | Apr 07, 2022 |
| Dell          | XPS 13 9310                 | [f5d617af1b](https://linux-hardware.org/?probe=f5d617af1b) | Apr 07, 2022 |
| Dell          | Inspiron 5565               | [265b99f9a2](https://linux-hardware.org/?probe=265b99f9a2) | Apr 07, 2022 |
| ASUSTek       | GL752VW                     | [0dbc471fee](https://linux-hardware.org/?probe=0dbc471fee) | Apr 07, 2022 |
| MSI           | GL75 Leopard 10SDK          | [e168714dee](https://linux-hardware.org/?probe=e168714dee) | Apr 06, 2022 |
| MSI           | GL63 9SD                    | [6b4f4b5c10](https://linux-hardware.org/?probe=6b4f4b5c10) | Apr 06, 2022 |
| Star Labs     | Lite                        | [7a49876efc](https://linux-hardware.org/?probe=7a49876efc) | Apr 05, 2022 |
| Acer          | Extensa 2511                | [00d24bfb95](https://linux-hardware.org/?probe=00d24bfb95) | Apr 05, 2022 |
| Dell          | XPS 15 9570                 | [0437f62b89](https://linux-hardware.org/?probe=0437f62b89) | Apr 05, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [91bae7b644](https://linux-hardware.org/?probe=91bae7b644) | Apr 05, 2022 |
| Razer         | Blade Stealth               | [426dc681c4](https://linux-hardware.org/?probe=426dc681c4) | Apr 05, 2022 |
| Dell          | Inspiron 5565               | [ec32d093d4](https://linux-hardware.org/?probe=ec32d093d4) | Apr 05, 2022 |
| Dell          | Vostro 3578                 | [8e2637c774](https://linux-hardware.org/?probe=8e2637c774) | Apr 05, 2022 |
| Acer          | E1-510                      | [bdcc9d59ad](https://linux-hardware.org/?probe=bdcc9d59ad) | Apr 05, 2022 |
| Lenovo        | Flex 2-14 20404             | [4368114931](https://linux-hardware.org/?probe=4368114931) | Apr 04, 2022 |
| Acer          | Nitro AN515-52              | [08491e74ef](https://linux-hardware.org/?probe=08491e74ef) | Apr 04, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [ecdd532a2c](https://linux-hardware.org/?probe=ecdd532a2c) | Apr 03, 2022 |
| Acer          | Nitro AN515-43              | [e6e1af5316](https://linux-hardware.org/?probe=e6e1af5316) | Apr 03, 2022 |
| Acer          | Aspire E5-573G              | [8c6db85346](https://linux-hardware.org/?probe=8c6db85346) | Apr 03, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [262e4f8317](https://linux-hardware.org/?probe=262e4f8317) | Apr 02, 2022 |
| Dell          | Inspiron 5520               | [63f818dc19](https://linux-hardware.org/?probe=63f818dc19) | Apr 02, 2022 |
| MSI           | Modern 15 A5M               | [ea091854ed](https://linux-hardware.org/?probe=ea091854ed) | Apr 01, 2022 |
| MSI           | Modern 15 A5M               | [ae491737c7](https://linux-hardware.org/?probe=ae491737c7) | Apr 01, 2022 |
| HUAWEI        | KLVL-WXXW                   | [4246affe99](https://linux-hardware.org/?probe=4246affe99) | Apr 01, 2022 |
| ASUSTek       | Strix GL504GW_GL504GW       | [aa7f16fc39](https://linux-hardware.org/?probe=aa7f16fc39) | Apr 01, 2022 |
| Lenovo        | ThinkPad T480s 20L70058G... | [d9fb78563a](https://linux-hardware.org/?probe=d9fb78563a) | Apr 01, 2022 |
| Dell          | Inspiron 7460               | [9658d99893](https://linux-hardware.org/?probe=9658d99893) | Apr 01, 2022 |
| Dell          | Inspiron 7460               | [24e5262a03](https://linux-hardware.org/?probe=24e5262a03) | Apr 01, 2022 |
| Acer          | Nitro AN517-41              | [7bce36b9fa](https://linux-hardware.org/?probe=7bce36b9fa) | Apr 01, 2022 |
| HP            | Laptop 14-cm0xxx            | [01f7a198c5](https://linux-hardware.org/?probe=01f7a198c5) | Mar 31, 2022 |
| HP            | EliteBook 820 G2            | [5308b25e76](https://linux-hardware.org/?probe=5308b25e76) | Mar 31, 2022 |
| System76      | Lemur Pro                   | [34b16b2584](https://linux-hardware.org/?probe=34b16b2584) | Mar 31, 2022 |
| Avell High... | B.ON                        | [d2628705e8](https://linux-hardware.org/?probe=d2628705e8) | Mar 31, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [27f986af8c](https://linux-hardware.org/?probe=27f986af8c) | Mar 30, 2022 |
| MSI           | GP62 7QF                    | [c15ac1cd59](https://linux-hardware.org/?probe=c15ac1cd59) | Mar 29, 2022 |
| Acer          | Nitro AN515-43              | [d1c02dfaee](https://linux-hardware.org/?probe=d1c02dfaee) | Mar 29, 2022 |
| Dell          | XPS 15 7590                 | [426b141f91](https://linux-hardware.org/?probe=426b141f91) | Mar 29, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [d346f2a1b1](https://linux-hardware.org/?probe=d346f2a1b1) | Mar 29, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [b0a630a992](https://linux-hardware.org/?probe=b0a630a992) | Mar 29, 2022 |
| ASUSTek       | X751LD                      | [6741a3f9dc](https://linux-hardware.org/?probe=6741a3f9dc) | Mar 28, 2022 |
| HUAWEI        | BOHB-WAX9                   | [cb353468c2](https://linux-hardware.org/?probe=cb353468c2) | Mar 28, 2022 |
| HONOR         | NMH-WCX9                    | [b8f4b2750d](https://linux-hardware.org/?probe=b8f4b2750d) | Mar 27, 2022 |
| Notebook      | N85_N87,HJ,HJ1,HK1          | [078c1af4c3](https://linux-hardware.org/?probe=078c1af4c3) | Mar 27, 2022 |
| HP            | ZBook 17 G2                 | [f0efa22aa2](https://linux-hardware.org/?probe=f0efa22aa2) | Mar 27, 2022 |
| HP            | ENVY dv6                    | [bfe11c2160](https://linux-hardware.org/?probe=bfe11c2160) | Mar 27, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [ba743bbb3b](https://linux-hardware.org/?probe=ba743bbb3b) | Mar 27, 2022 |
| ASUSTek       | GL552VW                     | [7e8bfac4b7](https://linux-hardware.org/?probe=7e8bfac4b7) | Mar 27, 2022 |
| Acer          | Aspire 4752                 | [a30c3c112b](https://linux-hardware.org/?probe=a30c3c112b) | Mar 27, 2022 |
| MSI           | GP62 7QF                    | [f05a7cf0e8](https://linux-hardware.org/?probe=f05a7cf0e8) | Mar 26, 2022 |
| Notebook      | NV4XMB,ME,MZ                | [8c3ffc28b7](https://linux-hardware.org/?probe=8c3ffc28b7) | Mar 26, 2022 |
| Acer          | Nitro AN515-45              | [c6fa89e81f](https://linux-hardware.org/?probe=c6fa89e81f) | Mar 26, 2022 |
| Alienware     | 15 R4                       | [204145e795](https://linux-hardware.org/?probe=204145e795) | Mar 26, 2022 |
| HUAWEI        | HVY-WXX9                    | [cc9e9e5839](https://linux-hardware.org/?probe=cc9e9e5839) | Mar 25, 2022 |
| Acer          | E1-510                      | [acfbdcfffc](https://linux-hardware.org/?probe=acfbdcfffc) | Mar 25, 2022 |
| Dell          | XPS 15 9510                 | [e463ecc7bc](https://linux-hardware.org/?probe=e463ecc7bc) | Mar 25, 2022 |
| Apple         | MacBookPro10,1              | [a9caf3d428](https://linux-hardware.org/?probe=a9caf3d428) | Mar 25, 2022 |
| MSI           | GL63 9SD                    | [d82d8f7857](https://linux-hardware.org/?probe=d82d8f7857) | Mar 25, 2022 |
| HP            | Laptop 14-fq1xxx            | [c6f4cf8c7a](https://linux-hardware.org/?probe=c6f4cf8c7a) | Mar 25, 2022 |
| Lenovo        | ThinkPad X220 4290LL3       | [4a7adefa43](https://linux-hardware.org/?probe=4a7adefa43) | Mar 25, 2022 |
| Lenovo        | V15 G2 ITL 82ME             | [f89824dbc7](https://linux-hardware.org/?probe=f89824dbc7) | Mar 24, 2022 |
| ASUSTek       | ROG Zephyrus M15 GU502LW... | [c9775b9b30](https://linux-hardware.org/?probe=c9775b9b30) | Mar 23, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [321d0c1b4a](https://linux-hardware.org/?probe=321d0c1b4a) | Mar 23, 2022 |
| Dell          | Inspiron 3185               | [f46418a449](https://linux-hardware.org/?probe=f46418a449) | Mar 23, 2022 |
| ASUSTek       | VivoBook S15 X510UF         | [10bc700e9b](https://linux-hardware.org/?probe=10bc700e9b) | Mar 23, 2022 |
| ASUSTek       | X510UNR                     | [ab3b8653a6](https://linux-hardware.org/?probe=ab3b8653a6) | Mar 23, 2022 |
| Lenovo        | G565 20071                  | [40cf723fac](https://linux-hardware.org/?probe=40cf723fac) | Mar 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [f7f7b2d459](https://linux-hardware.org/?probe=f7f7b2d459) | Mar 22, 2022 |
| Acer          | Aspire 4752                 | [609641d7df](https://linux-hardware.org/?probe=609641d7df) | Mar 21, 2022 |
| ASUSTek       | GL752VW                     | [39746d7497](https://linux-hardware.org/?probe=39746d7497) | Mar 20, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [da23c76a90](https://linux-hardware.org/?probe=da23c76a90) | Mar 19, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [be18e33911](https://linux-hardware.org/?probe=be18e33911) | Mar 19, 2022 |
| MSI           | Stealth GS66 12UGS          | [882be4cd35](https://linux-hardware.org/?probe=882be4cd35) | Mar 19, 2022 |
| Timi          | TM1701                      | [5127044e2a](https://linux-hardware.org/?probe=5127044e2a) | Mar 19, 2022 |
| ASUSTek       | GL752VW                     | [6d64c8e4de](https://linux-hardware.org/?probe=6d64c8e4de) | Mar 19, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [35e488d04a](https://linux-hardware.org/?probe=35e488d04a) | Mar 19, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [4db96169bf](https://linux-hardware.org/?probe=4db96169bf) | Mar 18, 2022 |
| Dell          | Inspiron 5566               | [7ab3aba611](https://linux-hardware.org/?probe=7ab3aba611) | Mar 18, 2022 |
| Toshiba       | Satellite L655              | [117807dfde](https://linux-hardware.org/?probe=117807dfde) | Mar 18, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [f785998dcb](https://linux-hardware.org/?probe=f785998dcb) | Mar 16, 2022 |
| HUAWEI        | KLVL-WXX9                   | [91eab99551](https://linux-hardware.org/?probe=91eab99551) | Mar 15, 2022 |
| HP            | Laptop 14-dq0xxx            | [46b66a5e79](https://linux-hardware.org/?probe=46b66a5e79) | Mar 15, 2022 |
| Dell          | Precision 5560              | [37f8320dbb](https://linux-hardware.org/?probe=37f8320dbb) | Mar 15, 2022 |
| HP            | ProBook 455 G7              | [453d423ede](https://linux-hardware.org/?probe=453d423ede) | Mar 15, 2022 |
| HP            | Laptop 14-dq0xxx            | [58afe91a23](https://linux-hardware.org/?probe=58afe91a23) | Mar 14, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [78ae0419a3](https://linux-hardware.org/?probe=78ae0419a3) | Mar 14, 2022 |
| Eluktronic... | Mech-15 G2                  | [5dd8b83919](https://linux-hardware.org/?probe=5dd8b83919) | Mar 14, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [82cfb46909](https://linux-hardware.org/?probe=82cfb46909) | Mar 13, 2022 |
| HP            | EliteBook 840 G2            | [b2ae743e44](https://linux-hardware.org/?probe=b2ae743e44) | Mar 13, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [692ae92211](https://linux-hardware.org/?probe=692ae92211) | Mar 13, 2022 |
| Acer          | Aspire A515-52G             | [e86cb3194d](https://linux-hardware.org/?probe=e86cb3194d) | Mar 13, 2022 |
| Toshiba       | Satellite C50-A             | [f778fcf85e](https://linux-hardware.org/?probe=f778fcf85e) | Mar 11, 2022 |
| Lenovo        | ThinkPad T490 20N2000KRT    | [4766fe6362](https://linux-hardware.org/?probe=4766fe6362) | Mar 10, 2022 |
| ASUSTek       | X510UAR                     | [3bef060804](https://linux-hardware.org/?probe=3bef060804) | Mar 10, 2022 |
| MSI           | Modern 14 B4MW              | [698af00b9c](https://linux-hardware.org/?probe=698af00b9c) | Mar 10, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [f351d9839b](https://linux-hardware.org/?probe=f351d9839b) | Mar 09, 2022 |
| MSI           | GP66 Leopard 11UG           | [ccbd207ebd](https://linux-hardware.org/?probe=ccbd207ebd) | Mar 09, 2022 |
| Dell          | Inspiron 3793               | [1fb19c1b23](https://linux-hardware.org/?probe=1fb19c1b23) | Mar 09, 2022 |
| Dell          | XPS 15 9550                 | [c39fe1a3e3](https://linux-hardware.org/?probe=c39fe1a3e3) | Mar 08, 2022 |
| Samsung       | 767XCL                      | [7685cdcfb9](https://linux-hardware.org/?probe=7685cdcfb9) | Mar 07, 2022 |
| Avell High... | 1513                        | [c2a1be9b32](https://linux-hardware.org/?probe=c2a1be9b32) | Mar 06, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [2d5c05af33](https://linux-hardware.org/?probe=2d5c05af33) | Mar 06, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [e7d5945f3d](https://linux-hardware.org/?probe=e7d5945f3d) | Mar 05, 2022 |
| Samsung       | 767XCL                      | [a45c6cfda9](https://linux-hardware.org/?probe=a45c6cfda9) | Mar 05, 2022 |
| HP            | ProBook 450 G4              | [87d97b3c00](https://linux-hardware.org/?probe=87d97b3c00) | Mar 05, 2022 |
| MSI           | Modern 14 B4MW              | [b52536f8a4](https://linux-hardware.org/?probe=b52536f8a4) | Mar 05, 2022 |
| ASUSTek       | X550VX                      | [91eafd1ed4](https://linux-hardware.org/?probe=91eafd1ed4) | Mar 04, 2022 |
| Dell          | Latitude 7480               | [68996ba096](https://linux-hardware.org/?probe=68996ba096) | Mar 03, 2022 |
| Dell          | Latitude 9420               | [355f64f6a7](https://linux-hardware.org/?probe=355f64f6a7) | Mar 03, 2022 |
| Dell          | Latitude 7480               | [4eb2f9a217](https://linux-hardware.org/?probe=4eb2f9a217) | Mar 03, 2022 |
| HP            | ENVY Laptop 13-ah0xxx       | [7fb04e6c7d](https://linux-hardware.org/?probe=7fb04e6c7d) | Mar 03, 2022 |
| HP            | ENVY Laptop 13-ah0xxx       | [0f27bdf5a8](https://linux-hardware.org/?probe=0f27bdf5a8) | Mar 02, 2022 |
| Packard Be... | DOT S                       | [4110664747](https://linux-hardware.org/?probe=4110664747) | Mar 02, 2022 |
| Samsung       | 670Z5E                      | [fd7ddf8a96](https://linux-hardware.org/?probe=fd7ddf8a96) | Mar 01, 2022 |
| Samsung       | R530/R730                   | [d28aae8671](https://linux-hardware.org/?probe=d28aae8671) | Mar 01, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [01f6429898](https://linux-hardware.org/?probe=01f6429898) | Mar 01, 2022 |
| ASUSTek       | X751LD                      | [c2d198ab83](https://linux-hardware.org/?probe=c2d198ab83) | Feb 28, 2022 |
| HP            | Laptop 15s-fq0xxx           | [9acf95b26b](https://linux-hardware.org/?probe=9acf95b26b) | Feb 28, 2022 |
| Lenovo        | ThinkPad X220 42912WU       | [71cc4e2875](https://linux-hardware.org/?probe=71cc4e2875) | Feb 28, 2022 |
| Notebook      | P15SM-A                     | [dfe7b95d25](https://linux-hardware.org/?probe=dfe7b95d25) | Feb 27, 2022 |
| HP            | Laptop 15-da0xxx            | [c06730e711](https://linux-hardware.org/?probe=c06730e711) | Feb 27, 2022 |
| Samsung       | 550XDA                      | [460d65857c](https://linux-hardware.org/?probe=460d65857c) | Feb 26, 2022 |
| Teclast       | F15 Plus                    | [a14a5fd6eb](https://linux-hardware.org/?probe=a14a5fd6eb) | Feb 26, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [59b53c7f42](https://linux-hardware.org/?probe=59b53c7f42) | Feb 26, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [ab78767b82](https://linux-hardware.org/?probe=ab78767b82) | Feb 26, 2022 |
| Samsung       | R530/R730                   | [8786882929](https://linux-hardware.org/?probe=8786882929) | Feb 25, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [cfd0806662](https://linux-hardware.org/?probe=cfd0806662) | Feb 25, 2022 |
| Acer          | Swift SF314-43              | [1434453fc0](https://linux-hardware.org/?probe=1434453fc0) | Feb 24, 2022 |
| MSI           | GL75 Leopard 10SDK          | [6a14728490](https://linux-hardware.org/?probe=6a14728490) | Feb 24, 2022 |
| Teclast       | F15 Plus                    | [e8e8b2f6da](https://linux-hardware.org/?probe=e8e8b2f6da) | Feb 24, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [393e833123](https://linux-hardware.org/?probe=393e833123) | Feb 24, 2022 |
| Dell          | XPS 15 7590                 | [69896e5117](https://linux-hardware.org/?probe=69896e5117) | Feb 23, 2022 |
| Dell          | Latitude 7480               | [fbd2d9b5c7](https://linux-hardware.org/?probe=fbd2d9b5c7) | Feb 23, 2022 |
| Razer         | Blade                       | [4b78377a27](https://linux-hardware.org/?probe=4b78377a27) | Feb 21, 2022 |
| Dell          | Precision 3530              | [8cf015e233](https://linux-hardware.org/?probe=8cf015e233) | Feb 21, 2022 |
| HUAWEI        | BOHB-WAX9                   | [8e2cd5844e](https://linux-hardware.org/?probe=8e2cd5844e) | Feb 21, 2022 |
| LG Electro... | 17UD70P-PX76K               | [968b189e38](https://linux-hardware.org/?probe=968b189e38) | Feb 21, 2022 |
| HP            | OMEN by Laptop 15-dh1xxx    | [fde67099dc](https://linux-hardware.org/?probe=fde67099dc) | Feb 20, 2022 |
| Dell          | Inspiron 3576               | [6b61eccd4d](https://linux-hardware.org/?probe=6b61eccd4d) | Feb 20, 2022 |
| Dell          | Inspiron 3576               | [16ffefcda4](https://linux-hardware.org/?probe=16ffefcda4) | Feb 20, 2022 |
| Framework     | Laptop                      | [1644c89c1c](https://linux-hardware.org/?probe=1644c89c1c) | Feb 20, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [bcb0d0c077](https://linux-hardware.org/?probe=bcb0d0c077) | Feb 19, 2022 |
| Avell High... | B.ON                        | [9ef94d96d1](https://linux-hardware.org/?probe=9ef94d96d1) | Feb 18, 2022 |
| IT Channel... | P95xER                      | [c8add471fb](https://linux-hardware.org/?probe=c8add471fb) | Feb 18, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [c2df5bb692](https://linux-hardware.org/?probe=c2df5bb692) | Feb 18, 2022 |
| Acer          | Predator PH517-61           | [96eedc2832](https://linux-hardware.org/?probe=96eedc2832) | Feb 18, 2022 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [bda7853dd1](https://linux-hardware.org/?probe=bda7853dd1) | Feb 17, 2022 |
| Dell          | Precision 7560              | [811983afdd](https://linux-hardware.org/?probe=811983afdd) | Feb 17, 2022 |
| Dell          | Latitude 9420               | [80a2f3e508](https://linux-hardware.org/?probe=80a2f3e508) | Feb 17, 2022 |
| Lenovo        | Yoga Creator 7 15IMH05 8... | [12a1b54a3a](https://linux-hardware.org/?probe=12a1b54a3a) | Feb 16, 2022 |
| Toshiba       | Satellite C870-19R          | [72755f69a8](https://linux-hardware.org/?probe=72755f69a8) | Feb 16, 2022 |
| Lenovo        | B50-30 80ES                 | [d9b49b400b](https://linux-hardware.org/?probe=d9b49b400b) | Feb 16, 2022 |
| Lenovo        | ThinkPad X220 42912WU       | [05281aa81f](https://linux-hardware.org/?probe=05281aa81f) | Feb 16, 2022 |
| Lenovo        | ThinkPad X220 42912WU       | [1c04b9e65f](https://linux-hardware.org/?probe=1c04b9e65f) | Feb 16, 2022 |
| CJSCOPE       | Z Series                    | [c594abda0a](https://linux-hardware.org/?probe=c594abda0a) | Feb 16, 2022 |
| Dell          | Inspiron 5520               | [fa0603a25d](https://linux-hardware.org/?probe=fa0603a25d) | Feb 16, 2022 |
| Fujitsu       | LIFEBOOK E556               | [b9f9511cb0](https://linux-hardware.org/?probe=b9f9511cb0) | Feb 15, 2022 |
| Toshiba       | Satellite C870-19R          | [4e0345b36d](https://linux-hardware.org/?probe=4e0345b36d) | Feb 15, 2022 |
| HP            | Notebook                    | [40c672794e](https://linux-hardware.org/?probe=40c672794e) | Feb 15, 2022 |
| Lenovo        | XiaoXinPro 14IHU 2021 82... | [d994752dc6](https://linux-hardware.org/?probe=d994752dc6) | Feb 15, 2022 |
| Avell High... | B.ON                        | [736bab4e42](https://linux-hardware.org/?probe=736bab4e42) | Feb 14, 2022 |
| LG Electro... | 17UD70P-PX76K               | [d8f6d95994](https://linux-hardware.org/?probe=d8f6d95994) | Feb 14, 2022 |
| Dell          | Inspiron 3793               | [108edf2064](https://linux-hardware.org/?probe=108edf2064) | Feb 13, 2022 |
| Acer          | Aspire VX5-591G             | [f8602e7dbf](https://linux-hardware.org/?probe=f8602e7dbf) | Feb 13, 2022 |
| Dell          | Inspiron 13-7378            | [53bdd438f6](https://linux-hardware.org/?probe=53bdd438f6) | Feb 13, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [2289e255e7](https://linux-hardware.org/?probe=2289e255e7) | Feb 13, 2022 |
| Dell          | Latitude E6420              | [019b0aeeea](https://linux-hardware.org/?probe=019b0aeeea) | Feb 13, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [6284595dc0](https://linux-hardware.org/?probe=6284595dc0) | Feb 13, 2022 |
| ASUSTek       | S550CM                      | [a6605f0fa3](https://linux-hardware.org/?probe=a6605f0fa3) | Feb 13, 2022 |
| Dell          | Latitude 5480               | [1804ba8af6](https://linux-hardware.org/?probe=1804ba8af6) | Feb 12, 2022 |
| Dell          | Latitude 5480               | [198846e977](https://linux-hardware.org/?probe=198846e977) | Feb 12, 2022 |
| Lenovo        | G40-80 80JE                 | [efb0663602](https://linux-hardware.org/?probe=efb0663602) | Feb 12, 2022 |
| Dell          | Inspiron N4050              | [0619812e27](https://linux-hardware.org/?probe=0619812e27) | Feb 11, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [4d49233d4b](https://linux-hardware.org/?probe=4d49233d4b) | Feb 11, 2022 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | [63be20cf71](https://linux-hardware.org/?probe=63be20cf71) | Feb 11, 2022 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | [a7d5970d58](https://linux-hardware.org/?probe=a7d5970d58) | Feb 11, 2022 |
| Acer          | Swift SF314-43              | [2a2573e162](https://linux-hardware.org/?probe=2a2573e162) | Feb 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [046ea2d5dc](https://linux-hardware.org/?probe=046ea2d5dc) | Feb 10, 2022 |
| Lenovo        | ThinkPad T460 20FMS2TG0D    | [f51933de6d](https://linux-hardware.org/?probe=f51933de6d) | Feb 10, 2022 |
| System76      | Oryx Pro                    | [f8437eee6d](https://linux-hardware.org/?probe=f8437eee6d) | Feb 10, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [1a90d7bf00](https://linux-hardware.org/?probe=1a90d7bf00) | Feb 09, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [74c0d79425](https://linux-hardware.org/?probe=74c0d79425) | Feb 09, 2022 |
| Avell High... | B.ON                        | [299d30a86c](https://linux-hardware.org/?probe=299d30a86c) | Feb 09, 2022 |
| GPD           | G1621-02                    | [d823ea2989](https://linux-hardware.org/?probe=d823ea2989) | Feb 09, 2022 |
| HONOR         | NMH-WCX9                    | [854a761f9f](https://linux-hardware.org/?probe=854a761f9f) | Feb 09, 2022 |
| Dell          | G3 3500                     | [9001ccacbc](https://linux-hardware.org/?probe=9001ccacbc) | Feb 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [0c5853297a](https://linux-hardware.org/?probe=0c5853297a) | Feb 09, 2022 |
| Dell          | Precision 3520              | [c2e3e54c45](https://linux-hardware.org/?probe=c2e3e54c45) | Feb 09, 2022 |
| Lenovo        | ThinkPad W500 40624DG       | [2d9ffc1ce5](https://linux-hardware.org/?probe=2d9ffc1ce5) | Feb 08, 2022 |
| Acer          | Nitro AN515-54              | [2656f9019e](https://linux-hardware.org/?probe=2656f9019e) | Feb 08, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [dfc4821588](https://linux-hardware.org/?probe=dfc4821588) | Feb 08, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [73962c18e5](https://linux-hardware.org/?probe=73962c18e5) | Feb 08, 2022 |
| Lenovo        | ThinkPad L420 7829BH2       | [7196de2b08](https://linux-hardware.org/?probe=7196de2b08) | Feb 06, 2022 |
| Acer          | Aspire A315-56              | [bf52089137](https://linux-hardware.org/?probe=bf52089137) | Feb 06, 2022 |
| Acer          | Aspire A315-56              | [d069ac806e](https://linux-hardware.org/?probe=d069ac806e) | Feb 06, 2022 |
| Timi          | TM1701                      | [64527262f8](https://linux-hardware.org/?probe=64527262f8) | Feb 06, 2022 |
| Star Labs     | StarBook                    | [e53bcff920](https://linux-hardware.org/?probe=e53bcff920) | Feb 06, 2022 |
| Google        | Ampton                      | [0f1564bb4a](https://linux-hardware.org/?probe=0f1564bb4a) | Feb 06, 2022 |
| ASUSTek       | K42F                        | [8bab320535](https://linux-hardware.org/?probe=8bab320535) | Feb 06, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [34488dc6f3](https://linux-hardware.org/?probe=34488dc6f3) | Feb 05, 2022 |
| ASUSTek       | X510UNR                     | [df6616c490](https://linux-hardware.org/?probe=df6616c490) | Feb 04, 2022 |
| HP            | 650                         | [0b786d0490](https://linux-hardware.org/?probe=0b786d0490) | Feb 04, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [cbb1e33af4](https://linux-hardware.org/?probe=cbb1e33af4) | Feb 03, 2022 |
| ASUSTek       | K55VJ                       | [f0421851fa](https://linux-hardware.org/?probe=f0421851fa) | Feb 03, 2022 |
| Razer         | Blade                       | [54b2f401d2](https://linux-hardware.org/?probe=54b2f401d2) | Feb 03, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [76b3522c5f](https://linux-hardware.org/?probe=76b3522c5f) | Feb 03, 2022 |
| Lenovo        | ThinkPad Mini10 3507A31     | [f49f0801c0](https://linux-hardware.org/?probe=f49f0801c0) | Feb 03, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [d134e108f4](https://linux-hardware.org/?probe=d134e108f4) | Feb 03, 2022 |
| Dell          | Vostro 3558                 | [de621c4916](https://linux-hardware.org/?probe=de621c4916) | Feb 02, 2022 |
| Samsung       | RV415/RV515                 | [1762291c98](https://linux-hardware.org/?probe=1762291c98) | Feb 02, 2022 |
| Samsung       | RV415/RV515                 | [1fc021cf65](https://linux-hardware.org/?probe=1fc021cf65) | Feb 02, 2022 |
| Dell          | XPS 13 9305                 | [3db01f2b60](https://linux-hardware.org/?probe=3db01f2b60) | Feb 02, 2022 |
| LG Electro... | S425-G.BC31P1               | [fa414c50c0](https://linux-hardware.org/?probe=fa414c50c0) | Feb 02, 2022 |
| HP            | EliteBook x360 1040 G5      | [4aa3aa1f30](https://linux-hardware.org/?probe=4aa3aa1f30) | Feb 02, 2022 |
| Toshiba       | Satellite P500              | [2403a2d0f9](https://linux-hardware.org/?probe=2403a2d0f9) | Feb 02, 2022 |
| MSI           | GP73 Leopard 8RE            | [98271a4acb](https://linux-hardware.org/?probe=98271a4acb) | Feb 02, 2022 |
| Avell High... | B.ON                        | [845b25e77d](https://linux-hardware.org/?probe=845b25e77d) | Feb 01, 2022 |
| MSI           | GP73 Leopard 8RE            | [9638de228d](https://linux-hardware.org/?probe=9638de228d) | Feb 01, 2022 |
| HP            | ProBook 450 G6              | [1de51c3e3b](https://linux-hardware.org/?probe=1de51c3e3b) | Feb 01, 2022 |
| HP            | ProBook 450 G6              | [e6dfa0f8ec](https://linux-hardware.org/?probe=e6dfa0f8ec) | Feb 01, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [2eb1af6927](https://linux-hardware.org/?probe=2eb1af6927) | Feb 01, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [1e4a3dd14b](https://linux-hardware.org/?probe=1e4a3dd14b) | Feb 01, 2022 |
| Acer          | Nitro AN715-51              | [6455c7e22d](https://linux-hardware.org/?probe=6455c7e22d) | Jan 30, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [91f859c774](https://linux-hardware.org/?probe=91f859c774) | Jan 30, 2022 |
| Acer          | Aspire A715-42G             | [f9c872ec0c](https://linux-hardware.org/?probe=f9c872ec0c) | Jan 30, 2022 |
| HP            | Pavilion Laptop 15z-eh00... | [c825fd8c26](https://linux-hardware.org/?probe=c825fd8c26) | Jan 30, 2022 |
| Lenovo        | ThinkPad X260 20F5S08P00    | [1fcf6565e3](https://linux-hardware.org/?probe=1fcf6565e3) | Jan 30, 2022 |
| Acer          | Aspire 7741                 | [900ca238e9](https://linux-hardware.org/?probe=900ca238e9) | Jan 29, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [a1b813490a](https://linux-hardware.org/?probe=a1b813490a) | Jan 29, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | [7f9793a709](https://linux-hardware.org/?probe=7f9793a709) | Jan 29, 2022 |
| HP            | EliteBook 830 G5            | [89e0eab168](https://linux-hardware.org/?probe=89e0eab168) | Jan 29, 2022 |
| ASUSTek       | X556UQ                      | [b9589b97a3](https://linux-hardware.org/?probe=b9589b97a3) | Jan 28, 2022 |
| HP            | ProBook 445 G7              | [a386252eaa](https://linux-hardware.org/?probe=a386252eaa) | Jan 28, 2022 |
| Lenovo        | ThinkPad A485 20MVS0FH00    | [1df9dbefa1](https://linux-hardware.org/?probe=1df9dbefa1) | Jan 28, 2022 |
| Dell          | G3 3579                     | [c869de19b3](https://linux-hardware.org/?probe=c869de19b3) | Jan 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [6b771832b8](https://linux-hardware.org/?probe=6b771832b8) | Jan 27, 2022 |
| Medion        | P6685 MD61138               | [57dfdfb610](https://linux-hardware.org/?probe=57dfdfb610) | Jan 27, 2022 |
| Acer          | Nitro AN515-55              | [ca4c953595](https://linux-hardware.org/?probe=ca4c953595) | Jan 27, 2022 |
| Alienware     | x15 R1                      | [4d82c0e97f](https://linux-hardware.org/?probe=4d82c0e97f) | Jan 26, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [eeadbaa61e](https://linux-hardware.org/?probe=eeadbaa61e) | Jan 26, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [11d9c59e44](https://linux-hardware.org/?probe=11d9c59e44) | Jan 26, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [4a3755734e](https://linux-hardware.org/?probe=4a3755734e) | Jan 26, 2022 |
| MSI           | GP73 Leopard 8RE            | [908e003892](https://linux-hardware.org/?probe=908e003892) | Jan 26, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [fcaa7e58f1](https://linux-hardware.org/?probe=fcaa7e58f1) | Jan 26, 2022 |
| Lenovo        | V155-15API 81V5             | [25e8674c5b](https://linux-hardware.org/?probe=25e8674c5b) | Jan 26, 2022 |
| Dell          | G3 3500                     | [57dd97e7c8](https://linux-hardware.org/?probe=57dd97e7c8) | Jan 25, 2022 |
| Eluktronic... | THINN-15                    | [d4c177ff7d](https://linux-hardware.org/?probe=d4c177ff7d) | Jan 25, 2022 |
| Intel Clie... | LAPBC710                    | [586a7bef92](https://linux-hardware.org/?probe=586a7bef92) | Jan 25, 2022 |
| Unknown       | Unknown                     | [84effb261a](https://linux-hardware.org/?probe=84effb261a) | Jan 24, 2022 |
| HP            | Elite x2 1012 G1            | [64fdc4c525](https://linux-hardware.org/?probe=64fdc4c525) | Jan 24, 2022 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [9b0a73843e](https://linux-hardware.org/?probe=9b0a73843e) | Jan 24, 2022 |
| Framework     | Laptop                      | [47222fcb36](https://linux-hardware.org/?probe=47222fcb36) | Jan 23, 2022 |
| Lenovo        | ThinkPad T420 423664U       | [0e2bb9a59f](https://linux-hardware.org/?probe=0e2bb9a59f) | Jan 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [086f2b17b3](https://linux-hardware.org/?probe=086f2b17b3) | Jan 23, 2022 |
| ASUSTek       | GL702VM                     | [7e9406edc6](https://linux-hardware.org/?probe=7e9406edc6) | Jan 23, 2022 |
| ASUSTek       | X450CP                      | [3f431523c1](https://linux-hardware.org/?probe=3f431523c1) | Jan 22, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | [c081d60b2a](https://linux-hardware.org/?probe=c081d60b2a) | Jan 22, 2022 |
| ASUSTek       | UX303UB                     | [c48fbc97e2](https://linux-hardware.org/?probe=c48fbc97e2) | Jan 22, 2022 |
| Lenovo        | ThinkPad X395 20NL000HMC    | [6c07e3f92a](https://linux-hardware.org/?probe=6c07e3f92a) | Jan 21, 2022 |
| HP            | Elite x2 1012 G1            | [2c73df6abc](https://linux-hardware.org/?probe=2c73df6abc) | Jan 21, 2022 |
| Acer          | Nitro AN515-44              | [e9a3d35409](https://linux-hardware.org/?probe=e9a3d35409) | Jan 21, 2022 |
| Dell          | Inspiron 15 5510            | [e40957f661](https://linux-hardware.org/?probe=e40957f661) | Jan 21, 2022 |
| Acer          | Nitro AN515-52              | [e4791d09ec](https://linux-hardware.org/?probe=e4791d09ec) | Jan 20, 2022 |
| Lenovo        | IdeaPad 305-14IBD 80R1      | [f963f78bc6](https://linux-hardware.org/?probe=f963f78bc6) | Jan 20, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [178c594c6a](https://linux-hardware.org/?probe=178c594c6a) | Jan 20, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [dfbb7c034f](https://linux-hardware.org/?probe=dfbb7c034f) | Jan 20, 2022 |
| Lenovo        | ThinkPad P50 20EQS2AB00     | [bdc680b5f1](https://linux-hardware.org/?probe=bdc680b5f1) | Jan 19, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [2e7e3ccc17](https://linux-hardware.org/?probe=2e7e3ccc17) | Jan 19, 2022 |
| MSI           | Modern 14 B5M               | [ae605d8a23](https://linux-hardware.org/?probe=ae605d8a23) | Jan 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X411... | [6294ff032d](https://linux-hardware.org/?probe=6294ff032d) | Jan 18, 2022 |
| Dell          | XPS 13 9360                 | [0370593223](https://linux-hardware.org/?probe=0370593223) | Jan 18, 2022 |
| LG Electro... | 17UD70P-PX76K               | [d0d21d2892](https://linux-hardware.org/?probe=d0d21d2892) | Jan 18, 2022 |
| Lenovo        | Legion R9000P2021H 82JQ     | [51d6b35ddf](https://linux-hardware.org/?probe=51d6b35ddf) | Jan 17, 2022 |
| Dell          | Inspiron 5515               | [b2251870ed](https://linux-hardware.org/?probe=b2251870ed) | Jan 17, 2022 |
| ASUSTek       | X751LB                      | [c9d01095cd](https://linux-hardware.org/?probe=c9d01095cd) | Jan 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X531... | [88f62c8333](https://linux-hardware.org/?probe=88f62c8333) | Jan 15, 2022 |
| Multilaser    | UB32X                       | [f65b37d922](https://linux-hardware.org/?probe=f65b37d922) | Jan 15, 2022 |
| ASUSTek       | X580VD                      | [9cb7ebea38](https://linux-hardware.org/?probe=9cb7ebea38) | Jan 14, 2022 |
| Dell          | XPS 15 7590                 | [91ac362b29](https://linux-hardware.org/?probe=91ac362b29) | Jan 14, 2022 |
| Intel Clie... | LAPBC710                    | [50f8ca3c0e](https://linux-hardware.org/?probe=50f8ca3c0e) | Jan 14, 2022 |
| Intel Clie... | LAPBC710                    | [bff400b353](https://linux-hardware.org/?probe=bff400b353) | Jan 14, 2022 |
| Acer          | Swift SF314-55G             | [fc48cf8ace](https://linux-hardware.org/?probe=fc48cf8ace) | Jan 14, 2022 |
| Lenovo        | ThinkPad T420 4236WR1       | [15dd95fdfd](https://linux-hardware.org/?probe=15dd95fdfd) | Jan 14, 2022 |
| MSI           | GS66 Stealth 10SFS          | [6401c76a8f](https://linux-hardware.org/?probe=6401c76a8f) | Jan 14, 2022 |
| Acer          | Swift SF114-32              | [f45f5dc35b](https://linux-hardware.org/?probe=f45f5dc35b) | Jan 13, 2022 |
| HP            | ProBook 450 G4              | [38a7870ece](https://linux-hardware.org/?probe=38a7870ece) | Jan 13, 2022 |
| Dell          | Latitude E5470              | [f1f2897964](https://linux-hardware.org/?probe=f1f2897964) | Jan 13, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [137736d936](https://linux-hardware.org/?probe=137736d936) | Jan 11, 2022 |
| Apple         | MacBookPro9,2               | [34acf9099a](https://linux-hardware.org/?probe=34acf9099a) | Jan 11, 2022 |
| Dell          | Latitude E5570              | [09a67dee6c](https://linux-hardware.org/?probe=09a67dee6c) | Jan 11, 2022 |
| MSI           | GS66 Stealth 10UH           | [a38abf3dd0](https://linux-hardware.org/?probe=a38abf3dd0) | Jan 10, 2022 |
| Lenovo        | ThinkPad T480 20L5001DUS    | [872bc057f0](https://linux-hardware.org/?probe=872bc057f0) | Jan 10, 2022 |
| Dell          | Precision 7550              | [0b72e489be](https://linux-hardware.org/?probe=0b72e489be) | Jan 10, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [c98201c522](https://linux-hardware.org/?probe=c98201c522) | Jan 09, 2022 |
| MSI           | Modern 14 B5M               | [4822adcbc3](https://linux-hardware.org/?probe=4822adcbc3) | Jan 09, 2022 |
| HP            | Notebook                    | [4e0916b606](https://linux-hardware.org/?probe=4e0916b606) | Jan 08, 2022 |
| MSI           | Modern 14 B5M               | [ea82b6b417](https://linux-hardware.org/?probe=ea82b6b417) | Jan 08, 2022 |
| Lenovo        | S145-15API 81UT             | [74b342a9fe](https://linux-hardware.org/?probe=74b342a9fe) | Jan 07, 2022 |
| Lenovo        | S145-15API 81UT             | [ed7ca5bcb0](https://linux-hardware.org/?probe=ed7ca5bcb0) | Jan 07, 2022 |
| Samsung       | 935XDB                      | [1bb7122515](https://linux-hardware.org/?probe=1bb7122515) | Jan 06, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [d331d91cd7](https://linux-hardware.org/?probe=d331d91cd7) | Jan 06, 2022 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | [0bba156d27](https://linux-hardware.org/?probe=0bba156d27) | Jan 06, 2022 |
| HP            | ProBook 6460b               | [344d4bf578](https://linux-hardware.org/?probe=344d4bf578) | Jan 06, 2022 |
| ASUSTek       | UX303LAB                    | [f67f6315ad](https://linux-hardware.org/?probe=f67f6315ad) | Jan 05, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 80X4     | [235ebe435c](https://linux-hardware.org/?probe=235ebe435c) | Jan 04, 2022 |
| Lenovo        | U310                        | [47b64f9b71](https://linux-hardware.org/?probe=47b64f9b71) | Jan 04, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [2e7edfda25](https://linux-hardware.org/?probe=2e7edfda25) | Jan 04, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [9f198f45b9](https://linux-hardware.org/?probe=9f198f45b9) | Jan 04, 2022 |
| Dell          | Latitude E5570              | [c8aab15c00](https://linux-hardware.org/?probe=c8aab15c00) | Jan 03, 2022 |
| Acer          | Aspire A515-44              | [d53cecaa8d](https://linux-hardware.org/?probe=d53cecaa8d) | Jan 03, 2022 |
| Samsung       | 300E5M/300E5L               | [3d96bb9bc2](https://linux-hardware.org/?probe=3d96bb9bc2) | Jan 02, 2022 |
| Apple         | MacBookPro11,5              | [1c88a2bad0](https://linux-hardware.org/?probe=1c88a2bad0) | Jan 02, 2022 |
| HP            | Laptop 15-da0xxx            | [50a5dc78eb](https://linux-hardware.org/?probe=50a5dc78eb) | Jan 02, 2022 |
| Medion        | S4216                       | [5d64e25278](https://linux-hardware.org/?probe=5d64e25278) | Jan 02, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [e0415c1970](https://linux-hardware.org/?probe=e0415c1970) | Jan 01, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [d5e6362672](https://linux-hardware.org/?probe=d5e6362672) | Jan 01, 2022 |
| Acer          | Swift SF314-41              | [d7b4fd099d](https://linux-hardware.org/?probe=d7b4fd099d) | Jan 01, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [65c9a87d51](https://linux-hardware.org/?probe=65c9a87d51) | Jan 01, 2022 |
| Dell          | Latitude E6230              | [fd4e9c6d43](https://linux-hardware.org/?probe=fd4e9c6d43) | Dec 31, 2021 |
| Hyperbook     | Z15 Zen                     | [6fe0e1a6d0](https://linux-hardware.org/?probe=6fe0e1a6d0) | Dec 30, 2021 |
| LG Electro... | 16ZD90P-GX7LK               | [0870fd8772](https://linux-hardware.org/?probe=0870fd8772) | Dec 29, 2021 |
| Lenovo        | V15 G2 ALC 82KD             | [57a3728f0d](https://linux-hardware.org/?probe=57a3728f0d) | Dec 29, 2021 |
| Apple         | MacBookAir7,2               | [2429b77086](https://linux-hardware.org/?probe=2429b77086) | Dec 29, 2021 |
| Apple         | MacBookAir7,2               | [847cf2b80d](https://linux-hardware.org/?probe=847cf2b80d) | Dec 29, 2021 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | [0d09c12302](https://linux-hardware.org/?probe=0d09c12302) | Dec 28, 2021 |
| Dell          | Vostro 3590                 | [31338a4a85](https://linux-hardware.org/?probe=31338a4a85) | Dec 27, 2021 |
| Acer          | Swift SF314-511             | [3a201fd936](https://linux-hardware.org/?probe=3a201fd936) | Dec 27, 2021 |
| Lenovo        | G580 20150                  | [71135c1724](https://linux-hardware.org/?probe=71135c1724) | Dec 27, 2021 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [c688144796](https://linux-hardware.org/?probe=c688144796) | Dec 26, 2021 |
| HP            | EliteBook 2570p             | [e17f3ed027](https://linux-hardware.org/?probe=e17f3ed027) | Dec 26, 2021 |
| MSI           | GS66 Stealth 10UH           | [6246228e2d](https://linux-hardware.org/?probe=6246228e2d) | Dec 26, 2021 |
| ASUSTek       | X580VD                      | [fe350107e3](https://linux-hardware.org/?probe=fe350107e3) | Dec 25, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | [15cd749c6e](https://linux-hardware.org/?probe=15cd749c6e) | Dec 25, 2021 |
| Microtech     | ebookPro                    | [3c55dc5833](https://linux-hardware.org/?probe=3c55dc5833) | Dec 24, 2021 |
| Microtech     | ebookPro                    | [6f13d15aaf](https://linux-hardware.org/?probe=6f13d15aaf) | Dec 24, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b2b9ea9e60](https://linux-hardware.org/?probe=b2b9ea9e60) | Dec 24, 2021 |
| HP            | Pav Gaming Laptop 15-dk1... | [b0f9889c91](https://linux-hardware.org/?probe=b0f9889c91) | Dec 24, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [573930ce59](https://linux-hardware.org/?probe=573930ce59) | Dec 23, 2021 |
| Schenker      | XMG CORE 15(M20, RTX 206... | [f4c47d6284](https://linux-hardware.org/?probe=f4c47d6284) | Dec 23, 2021 |
| Lenovo        | V14-ADA 82C6                | [c8371f27fd](https://linux-hardware.org/?probe=c8371f27fd) | Dec 23, 2021 |
| Dell          | Latitude 5580               | [f0bf7f4dd9](https://linux-hardware.org/?probe=f0bf7f4dd9) | Dec 23, 2021 |
| Toshiba       | Satellite L650              | [6ce7007b2b](https://linux-hardware.org/?probe=6ce7007b2b) | Dec 23, 2021 |
| ASUSTek       | Strix 17 GL703GE            | [f34a512b46](https://linux-hardware.org/?probe=f34a512b46) | Dec 22, 2021 |
| HP            | Laptop 15s-eq1xxx           | [bdb88d3ef1](https://linux-hardware.org/?probe=bdb88d3ef1) | Dec 22, 2021 |
| Timi          | TM1701                      | [96e5b3d8a2](https://linux-hardware.org/?probe=96e5b3d8a2) | Dec 22, 2021 |
| Lenovo        | ThinkPad P51 20HJS16Q0K     | [5390e6662b](https://linux-hardware.org/?probe=5390e6662b) | Dec 22, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [d844963da6](https://linux-hardware.org/?probe=d844963da6) | Dec 22, 2021 |
| Lenovo        | Legion Y7000 2019 1050 8... | [b16546ce2c](https://linux-hardware.org/?probe=b16546ce2c) | Dec 22, 2021 |
| Lenovo        | Legion Y7000 81FW           | [a7cc31a69f](https://linux-hardware.org/?probe=a7cc31a69f) | Dec 22, 2021 |
| Medion        | ERAZER X7857 MD60893        | [3662e2c4d5](https://linux-hardware.org/?probe=3662e2c4d5) | Dec 21, 2021 |
| Dell          | XPS 15 9500                 | [86789982ba](https://linux-hardware.org/?probe=86789982ba) | Dec 21, 2021 |
| Apple         | MacBookPro4,1               | [855e5ba65d](https://linux-hardware.org/?probe=855e5ba65d) | Dec 21, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [897aac29d2](https://linux-hardware.org/?probe=897aac29d2) | Dec 21, 2021 |
| HP            | Victus by Laptop 16-e0xx... | [29b9cc77f1](https://linux-hardware.org/?probe=29b9cc77f1) | Dec 21, 2021 |
| Timi          | RedmiBook 14 II             | [b6179a5282](https://linux-hardware.org/?probe=b6179a5282) | Dec 19, 2021 |
| HUAWEI        | KLVD-WXX9                   | [96661cdf6b](https://linux-hardware.org/?probe=96661cdf6b) | Dec 19, 2021 |
| ASUSTek       | GX501VIK                    | [40e6f35954](https://linux-hardware.org/?probe=40e6f35954) | Dec 19, 2021 |
| Dell          | Inspiron 5575               | [9a0876b2f1](https://linux-hardware.org/?probe=9a0876b2f1) | Dec 18, 2021 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | [3cd4b5c111](https://linux-hardware.org/?probe=3cd4b5c111) | Dec 18, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [ae4b7d946e](https://linux-hardware.org/?probe=ae4b7d946e) | Dec 18, 2021 |
| Dell          | Latitude 9420               | [a5eeb38a83](https://linux-hardware.org/?probe=a5eeb38a83) | Dec 18, 2021 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | [03115bdd2e](https://linux-hardware.org/?probe=03115bdd2e) | Dec 18, 2021 |
| Dell          | XPS 15 9500                 | [f9a4ac885d](https://linux-hardware.org/?probe=f9a4ac885d) | Dec 17, 2021 |
| Acer          | Nitro AN515-54              | [cda96a5417](https://linux-hardware.org/?probe=cda96a5417) | Dec 16, 2021 |
| System76      | Galago Pro                  | [e702cc7d76](https://linux-hardware.org/?probe=e702cc7d76) | Dec 16, 2021 |
| Alienware     | x15 R1                      | [e93cad3713](https://linux-hardware.org/?probe=e93cad3713) | Dec 16, 2021 |
| Dell          | XPS 15 9570                 | [3a5c1ae641](https://linux-hardware.org/?probe=3a5c1ae641) | Dec 16, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | [a0ec890791](https://linux-hardware.org/?probe=a0ec890791) | Dec 15, 2021 |
| HP            | Laptop 15-db1xxx            | [a0f01cc0fa](https://linux-hardware.org/?probe=a0f01cc0fa) | Dec 15, 2021 |
| ASUSTek       | N53SV                       | [c17076e55c](https://linux-hardware.org/?probe=c17076e55c) | Dec 15, 2021 |
| Dell          | Vostro 1720                 | [551616e359](https://linux-hardware.org/?probe=551616e359) | Dec 14, 2021 |
| System76      | Gazelle                     | [8c9e49308f](https://linux-hardware.org/?probe=8c9e49308f) | Dec 14, 2021 |
| System76      | Gazelle                     | [5b43bc13d5](https://linux-hardware.org/?probe=5b43bc13d5) | Dec 14, 2021 |
| Dell          | XPS 13 9360                 | [b4a6dc4e1b](https://linux-hardware.org/?probe=b4a6dc4e1b) | Dec 14, 2021 |
| ASUSTek       | G752VT                      | [2fd049dae1](https://linux-hardware.org/?probe=2fd049dae1) | Dec 14, 2021 |
| Lenovo        | ThinkPad T400 2768GB4       | [7b62a6c11b](https://linux-hardware.org/?probe=7b62a6c11b) | Dec 14, 2021 |
| Lenovo        | ThinkPad T400 2768GB4       | [02de13907c](https://linux-hardware.org/?probe=02de13907c) | Dec 14, 2021 |
| Toshiba       | Satellite L650              | [550eaaed77](https://linux-hardware.org/?probe=550eaaed77) | Dec 14, 2021 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | [5b3b8680df](https://linux-hardware.org/?probe=5b3b8680df) | Dec 13, 2021 |
| ASUSTek       | X55CR                       | [fbfa84587c](https://linux-hardware.org/?probe=fbfa84587c) | Dec 13, 2021 |
| Samsung       | RV415/RV515                 | [16af5a00db](https://linux-hardware.org/?probe=16af5a00db) | Dec 13, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [499d539995](https://linux-hardware.org/?probe=499d539995) | Dec 12, 2021 |
| Lenovo        | ThinkPad T460s 20FAS05Q0... | [3a4b9beb1d](https://linux-hardware.org/?probe=3a4b9beb1d) | Dec 12, 2021 |
| Apple         | MacBookAir3,1               | [edebb4d39b](https://linux-hardware.org/?probe=edebb4d39b) | Dec 12, 2021 |
| HP            | Pavilion g7                 | [c158dbcdcf](https://linux-hardware.org/?probe=c158dbcdcf) | Dec 12, 2021 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [d09c52b686](https://linux-hardware.org/?probe=d09c52b686) | Dec 11, 2021 |
| Dell          | Precision 3561              | [1a93ee047d](https://linux-hardware.org/?probe=1a93ee047d) | Dec 11, 2021 |
| Dell          | Inspiron 3521               | [2ffd4b930a](https://linux-hardware.org/?probe=2ffd4b930a) | Dec 10, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | [87d91182e5](https://linux-hardware.org/?probe=87d91182e5) | Dec 09, 2021 |
| Lenovo        | ThinkPad T470s 20HF004UM... | [e7144e5f86](https://linux-hardware.org/?probe=e7144e5f86) | Dec 09, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [11fb7ea1d7](https://linux-hardware.org/?probe=11fb7ea1d7) | Dec 08, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [23579d8b3a](https://linux-hardware.org/?probe=23579d8b3a) | Dec 08, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [6860b48116](https://linux-hardware.org/?probe=6860b48116) | Dec 08, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [66796a4303](https://linux-hardware.org/?probe=66796a4303) | Dec 06, 2021 |
| UNOWHY        | Y13G002S4EI                 | [d3328717de](https://linux-hardware.org/?probe=d3328717de) | Dec 06, 2021 |
| Dell          | Latitude E6400              | [b8d03425c9](https://linux-hardware.org/?probe=b8d03425c9) | Dec 05, 2021 |
| HP            | ProBook 4740s               | [a24f0e642b](https://linux-hardware.org/?probe=a24f0e642b) | Dec 05, 2021 |
| Dell          | Latitude 5410               | [af7b378137](https://linux-hardware.org/?probe=af7b378137) | Dec 05, 2021 |
| Dell          | Latitude 5410               | [0d992a9be7](https://linux-hardware.org/?probe=0d992a9be7) | Dec 05, 2021 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [d566229da2](https://linux-hardware.org/?probe=d566229da2) | Dec 05, 2021 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [7eed1618fe](https://linux-hardware.org/?probe=7eed1618fe) | Dec 04, 2021 |
| Chuwi         | GemiBook Pro                | [664d1dc278](https://linux-hardware.org/?probe=664d1dc278) | Dec 04, 2021 |
| HP            | ProBook 450 G4              | [42edbb20ce](https://linux-hardware.org/?probe=42edbb20ce) | Dec 04, 2021 |
| HP            | 250 G7 Notebook PC          | [3f21e28b42](https://linux-hardware.org/?probe=3f21e28b42) | Dec 03, 2021 |
| Lenovo        | IdeaPad Y510P 20217         | [74c27eb6e8](https://linux-hardware.org/?probe=74c27eb6e8) | Dec 01, 2021 |
| HP            | ProBook 440 G8 Notebook ... | [a70cef2501](https://linux-hardware.org/?probe=a70cef2501) | Dec 01, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | [e9fd574b87](https://linux-hardware.org/?probe=e9fd574b87) | Nov 30, 2021 |
| HP            | Compaq Presario CQ40        | [677782bf59](https://linux-hardware.org/?probe=677782bf59) | Nov 29, 2021 |
| Dell          | XPS 13 9300                 | [f3177651b4](https://linux-hardware.org/?probe=f3177651b4) | Nov 29, 2021 |
| Notebook      | NHx0DB,DE                   | [90806839ac](https://linux-hardware.org/?probe=90806839ac) | Nov 28, 2021 |
| HP            | EliteBook 840 G1            | [6eff02505f](https://linux-hardware.org/?probe=6eff02505f) | Nov 27, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [dc981a1604](https://linux-hardware.org/?probe=dc981a1604) | Nov 27, 2021 |
| Acer          | Nitro AN515-52              | [49a5e6faa8](https://linux-hardware.org/?probe=49a5e6faa8) | Nov 26, 2021 |
| ASUSTek       | X556URK                     | [dcb4c56719](https://linux-hardware.org/?probe=dcb4c56719) | Nov 26, 2021 |
| Dell          | Inspiron 5567               | [e73341feab](https://linux-hardware.org/?probe=e73341feab) | Nov 26, 2021 |
| Dell          | Vostro 3500                 | [c323b490bf](https://linux-hardware.org/?probe=c323b490bf) | Nov 26, 2021 |
| Framework     | Laptop                      | [2669bf6af2](https://linux-hardware.org/?probe=2669bf6af2) | Nov 25, 2021 |
| Dell          | Inspiron 3505               | [9d28cad38c](https://linux-hardware.org/?probe=9d28cad38c) | Nov 24, 2021 |
| Alienware     | m15 R6                      | [7a71325757](https://linux-hardware.org/?probe=7a71325757) | Nov 24, 2021 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | [55a7f1df10](https://linux-hardware.org/?probe=55a7f1df10) | Nov 24, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [e1827cbbc6](https://linux-hardware.org/?probe=e1827cbbc6) | Nov 24, 2021 |
| Lenovo        | Legion R9000P2021H 82JQ     | [4a634caeca](https://linux-hardware.org/?probe=4a634caeca) | Nov 24, 2021 |
| Dell          | Vostro 5515                 | [85d1947f69](https://linux-hardware.org/?probe=85d1947f69) | Nov 24, 2021 |
| Acer          | Aspire A515-43              | [20d1a10bbf](https://linux-hardware.org/?probe=20d1a10bbf) | Nov 24, 2021 |
| Dell          | G5 5590                     | [3a149ffc5e](https://linux-hardware.org/?probe=3a149ffc5e) | Nov 23, 2021 |
| HP            | 250 G7 Notebook PC          | [fac36029d0](https://linux-hardware.org/?probe=fac36029d0) | Nov 23, 2021 |
| Dell          | XPS 13 9310                 | [01fd26642f](https://linux-hardware.org/?probe=01fd26642f) | Nov 23, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [78868c28c5](https://linux-hardware.org/?probe=78868c28c5) | Nov 22, 2021 |
| HP            | Victus by Laptop 16-e0xx... | [53e26c9677](https://linux-hardware.org/?probe=53e26c9677) | Nov 22, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 80X4     | [bfb50a6ed5](https://linux-hardware.org/?probe=bfb50a6ed5) | Nov 21, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 80X4     | [1793df5011](https://linux-hardware.org/?probe=1793df5011) | Nov 21, 2021 |
| ASUSTek       | UX410UAK                    | [5f7c5692f7](https://linux-hardware.org/?probe=5f7c5692f7) | Nov 21, 2021 |
| Dell          | Inspiron 5570               | [bde1fd1da2](https://linux-hardware.org/?probe=bde1fd1da2) | Nov 20, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [362a840c47](https://linux-hardware.org/?probe=362a840c47) | Nov 20, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [0f2e59e45b](https://linux-hardware.org/?probe=0f2e59e45b) | Nov 20, 2021 |
| Dell          | Inspiron 15-3552            | [50311c71ac](https://linux-hardware.org/?probe=50311c71ac) | Nov 20, 2021 |
| Dell          | Inspiron 5570               | [9c7eba9b77](https://linux-hardware.org/?probe=9c7eba9b77) | Nov 19, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [1afc762c2d](https://linux-hardware.org/?probe=1afc762c2d) | Nov 19, 2021 |
| Chuwi         | CoreBook XPro               | [0052e1b593](https://linux-hardware.org/?probe=0052e1b593) | Nov 19, 2021 |
| Lenovo        | Yoga 14sACH 2021 82MS       | [69c06885de](https://linux-hardware.org/?probe=69c06885de) | Nov 18, 2021 |
| Dell          | Inspiron 15 5510            | [1a6cade330](https://linux-hardware.org/?probe=1a6cade330) | Nov 18, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [33fcefc1b3](https://linux-hardware.org/?probe=33fcefc1b3) | Nov 17, 2021 |
| Lenovo        | ThinkPad T530 24341G0       | [0dcfa8bdc7](https://linux-hardware.org/?probe=0dcfa8bdc7) | Nov 17, 2021 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [81a7c19597](https://linux-hardware.org/?probe=81a7c19597) | Nov 17, 2021 |
| Dell          | Inspiron 5515               | [acd9469780](https://linux-hardware.org/?probe=acd9469780) | Nov 16, 2021 |
| ASUSTek       | X550LD                      | [6337158c74](https://linux-hardware.org/?probe=6337158c74) | Nov 16, 2021 |
| Acer          | Swift SF315-41              | [6720bdb10e](https://linux-hardware.org/?probe=6720bdb10e) | Nov 16, 2021 |
| Dell          | Vostro 7500                 | [773174f5d1](https://linux-hardware.org/?probe=773174f5d1) | Nov 16, 2021 |
| Intel Clie... | LAPBC710                    | [994e4bac0a](https://linux-hardware.org/?probe=994e4bac0a) | Nov 16, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [ad427f77d7](https://linux-hardware.org/?probe=ad427f77d7) | Nov 15, 2021 |
| HP            | 250 G4 Notebook PC          | [795371d9ce](https://linux-hardware.org/?probe=795371d9ce) | Nov 15, 2021 |
| TUXEDO        | InfinityBook S 15 Gen6      | [90b63564bb](https://linux-hardware.org/?probe=90b63564bb) | Nov 15, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [0362606eb7](https://linux-hardware.org/?probe=0362606eb7) | Nov 15, 2021 |
| LG Electro... | 17UD70P-PX76K               | [b4c7522ea3](https://linux-hardware.org/?probe=b4c7522ea3) | Nov 15, 2021 |
| LG Electro... | 16Z90P-G.AA75A              | [d15e199bb4](https://linux-hardware.org/?probe=d15e199bb4) | Nov 14, 2021 |
| Framework     | Laptop                      | [4be893ca2b](https://linux-hardware.org/?probe=4be893ca2b) | Nov 14, 2021 |
| Notebook      | NP50DE_DB                   | [62a4d59bf5](https://linux-hardware.org/?probe=62a4d59bf5) | Nov 12, 2021 |
| Dell          | Inspiron 5515               | [c4f55dcfb7](https://linux-hardware.org/?probe=c4f55dcfb7) | Nov 12, 2021 |
| Lenovo        | IdeaPad 130-14IKB 81H6      | [7f8d17d99d](https://linux-hardware.org/?probe=7f8d17d99d) | Nov 12, 2021 |
| Dell          | Precision 7540              | [321b2a1ab3](https://linux-hardware.org/?probe=321b2a1ab3) | Nov 12, 2021 |
| Notebook      | P870DM                      | [7681edf3ee](https://linux-hardware.org/?probe=7681edf3ee) | Nov 12, 2021 |
| Lenovo        | ThinkPad T520 4243E51       | [b15d1927cd](https://linux-hardware.org/?probe=b15d1927cd) | Nov 12, 2021 |
| HP            | Pavilion 15                 | [366558c9a6](https://linux-hardware.org/?probe=366558c9a6) | Nov 11, 2021 |
| ASUSTek       | Strix 17 GL703GE            | [72c968f9eb](https://linux-hardware.org/?probe=72c968f9eb) | Nov 11, 2021 |
| Dell          | XPS 15 9510                 | [b95625ab23](https://linux-hardware.org/?probe=b95625ab23) | Nov 10, 2021 |
| HP            | Pavilion g6                 | [ed1f976323](https://linux-hardware.org/?probe=ed1f976323) | Nov 10, 2021 |
| ASUSTek       | X550CC                      | [d45eb47123](https://linux-hardware.org/?probe=d45eb47123) | Nov 09, 2021 |
| Google        | Morphius                    | [36055c10c4](https://linux-hardware.org/?probe=36055c10c4) | Nov 09, 2021 |
| HP            | EliteBook 8570w             | [034b6c777c](https://linux-hardware.org/?probe=034b6c777c) | Nov 08, 2021 |
| HP            | Pavilion Laptop 14-ce3xx... | [d410e36b94](https://linux-hardware.org/?probe=d410e36b94) | Nov 08, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [6a4809c5af](https://linux-hardware.org/?probe=6a4809c5af) | Nov 08, 2021 |
| Schenker      | VIA 15 Pro                  | [82e1c9fd71](https://linux-hardware.org/?probe=82e1c9fd71) | Nov 07, 2021 |
| Acer          | Aspire A315-58G             | [64f0bb3f2b](https://linux-hardware.org/?probe=64f0bb3f2b) | Nov 06, 2021 |
| Lenovo        | ThinkPad L520 5016NY9       | [1ee21cf82c](https://linux-hardware.org/?probe=1ee21cf82c) | Nov 05, 2021 |
| Dell          | XPS 13 9310                 | [b893e4e865](https://linux-hardware.org/?probe=b893e4e865) | Nov 05, 2021 |
| Acer          | Swift SF114-33              | [9e177a92f3](https://linux-hardware.org/?probe=9e177a92f3) | Nov 05, 2021 |
| Razer         | Blade 14 - RZ09-0370        | [7a3fca17d8](https://linux-hardware.org/?probe=7a3fca17d8) | Nov 05, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [180651af3b](https://linux-hardware.org/?probe=180651af3b) | Nov 04, 2021 |
| Dell          | G5 5505                     | [6d39464c66](https://linux-hardware.org/?probe=6d39464c66) | Nov 04, 2021 |
| Dell          | G3 3579                     | [f9fdeb003b](https://linux-hardware.org/?probe=f9fdeb003b) | Nov 03, 2021 |
| HP            | Pavilion Laptop 15z-eh00... | [9c1a540a1c](https://linux-hardware.org/?probe=9c1a540a1c) | Nov 03, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | [aee42c40ca](https://linux-hardware.org/?probe=aee42c40ca) | Nov 03, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | [5eb29a4a05](https://linux-hardware.org/?probe=5eb29a4a05) | Nov 03, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [834d5535cd](https://linux-hardware.org/?probe=834d5535cd) | Nov 02, 2021 |
| HP            | EliteBook 840 G6            | [078ed9c13e](https://linux-hardware.org/?probe=078ed9c13e) | Nov 02, 2021 |
| HUAWEI        | BOHB-WAX9                   | [9949626d9a](https://linux-hardware.org/?probe=9949626d9a) | Nov 02, 2021 |
| Acer          | Aspire E5-573G              | [606c8d7a59](https://linux-hardware.org/?probe=606c8d7a59) | Nov 02, 2021 |
| Acer          | Aspire E5-573G              | [20e08af002](https://linux-hardware.org/?probe=20e08af002) | Nov 01, 2021 |
| ASUSTek       | X580VD                      | [2970522382](https://linux-hardware.org/?probe=2970522382) | Nov 01, 2021 |
| Dell          | G5 5505                     | [af69179892](https://linux-hardware.org/?probe=af69179892) | Nov 01, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | [70074ebee1](https://linux-hardware.org/?probe=70074ebee1) | Nov 01, 2021 |
| Acer          | Aspire 7741                 | [1cd84ea563](https://linux-hardware.org/?probe=1cd84ea563) | Oct 30, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [eb89bbebfe](https://linux-hardware.org/?probe=eb89bbebfe) | Oct 30, 2021 |
| HP            | Laptop 15s-eq2xxx           | [d14fe5657a](https://linux-hardware.org/?probe=d14fe5657a) | Oct 30, 2021 |
| Notebook      | NP50DE_DB                   | [435743b201](https://linux-hardware.org/?probe=435743b201) | Oct 29, 2021 |
| HUAWEI        | KLVL-WXX9                   | [1e059db869](https://linux-hardware.org/?probe=1e059db869) | Oct 29, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | [8db63e7a74](https://linux-hardware.org/?probe=8db63e7a74) | Oct 28, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [89afa44bcf](https://linux-hardware.org/?probe=89afa44bcf) | Oct 28, 2021 |
| Dell          | Latitude 7520               | [ee28f23b26](https://linux-hardware.org/?probe=ee28f23b26) | Oct 27, 2021 |
| Lenovo        | ThinkPad T420 4236VHV       | [a75ffd5203](https://linux-hardware.org/?probe=a75ffd5203) | Oct 26, 2021 |
| ASUSTek       | N53SM                       | [c9d463149f](https://linux-hardware.org/?probe=c9d463149f) | Oct 26, 2021 |
| Lenovo        | ThinkPad E585 20KVCTO1WW    | [204598f27d](https://linux-hardware.org/?probe=204598f27d) | Oct 26, 2021 |
| Samsung       | 900X3C/900X3D/900X3E/900... | [0396eac317](https://linux-hardware.org/?probe=0396eac317) | Oct 26, 2021 |
| Lenovo        | ThinkPad E595 20NF0002BM    | [52ba950565](https://linux-hardware.org/?probe=52ba950565) | Oct 25, 2021 |
| TUXEDO        | InfinityBook S 15 Gen6      | [a3ab1b4a11](https://linux-hardware.org/?probe=a3ab1b4a11) | Oct 25, 2021 |
| Dell          | G3 3500                     | [a2d09beb8d](https://linux-hardware.org/?probe=a2d09beb8d) | Oct 25, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [2f23c1aaa4](https://linux-hardware.org/?probe=2f23c1aaa4) | Oct 25, 2021 |
| Acer          | Nitro AN515-43              | [bcc833ac3c](https://linux-hardware.org/?probe=bcc833ac3c) | Oct 25, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [e0ae7283fb](https://linux-hardware.org/?probe=e0ae7283fb) | Oct 24, 2021 |
| Toshiba       | dynabook Satellite T772/... | [070723f36c](https://linux-hardware.org/?probe=070723f36c) | Oct 24, 2021 |
| Dell          | Inspiron 3583               | [217767cb69](https://linux-hardware.org/?probe=217767cb69) | Oct 23, 2021 |
| MSI           | GL73 8RD                    | [cf259f0674](https://linux-hardware.org/?probe=cf259f0674) | Oct 23, 2021 |
| Lenovo        | ThinkPad T490 20N20009PB    | [fbe1d68b82](https://linux-hardware.org/?probe=fbe1d68b82) | Oct 23, 2021 |
| HP            | EliteBook 830 G5            | [46392181d6](https://linux-hardware.org/?probe=46392181d6) | Oct 23, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [8c961555fe](https://linux-hardware.org/?probe=8c961555fe) | Oct 23, 2021 |
| Lenovo        | ThinkPad E480 20KN0069RT    | [a3c4c76fa5](https://linux-hardware.org/?probe=a3c4c76fa5) | Oct 21, 2021 |
| Acer          | Predator PH315-53           | [046f9cd623](https://linux-hardware.org/?probe=046f9cd623) | Oct 19, 2021 |
| Dell          | G3 3500                     | [ec734562a6](https://linux-hardware.org/?probe=ec734562a6) | Oct 19, 2021 |
| Lenovo        | ThinkPad T440s 20AQS0090... | [415cc7fe56](https://linux-hardware.org/?probe=415cc7fe56) | Oct 18, 2021 |
| Lenovo        | ThinkPad X230 23203BU       | [525ce59581](https://linux-hardware.org/?probe=525ce59581) | Oct 18, 2021 |
| Acer          | Aspire 7741                 | [7eeec5c322](https://linux-hardware.org/?probe=7eeec5c322) | Oct 17, 2021 |
| Lenovo        | ThinkPad T490 20N2000KRT    | [55daad7a3a](https://linux-hardware.org/?probe=55daad7a3a) | Oct 17, 2021 |
| Dell          | Latitude 9420               | [e37216cfa8](https://linux-hardware.org/?probe=e37216cfa8) | Oct 17, 2021 |
| Dell          | G3 3579                     | [28d725057f](https://linux-hardware.org/?probe=28d725057f) | Oct 17, 2021 |
| HP            | Laptop 15-bw0xx             | [99fc59557a](https://linux-hardware.org/?probe=99fc59557a) | Oct 17, 2021 |
| Dell          | G5 5587                     | [cfa2dd7e7c](https://linux-hardware.org/?probe=cfa2dd7e7c) | Oct 16, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [397c4c2aca](https://linux-hardware.org/?probe=397c4c2aca) | Oct 16, 2021 |
| Dell          | XPS 15 9500                 | [1443087847](https://linux-hardware.org/?probe=1443087847) | Oct 14, 2021 |
| Acer          | Aspire A515-51G             | [af67b942ec](https://linux-hardware.org/?probe=af67b942ec) | Oct 14, 2021 |
| Lenovo        | ThinkPad T450s 20BWS2KM0... | [e02c35310a](https://linux-hardware.org/?probe=e02c35310a) | Oct 13, 2021 |
| HP            | ProBook 445 G7 Notebook ... | [83045a6763](https://linux-hardware.org/?probe=83045a6763) | Oct 13, 2021 |
| Lenovo        | ThinkPad X395 20NL0007US    | [6b6b00f95c](https://linux-hardware.org/?probe=6b6b00f95c) | Oct 12, 2021 |
| MSI           | GL65 9SEK                   | [adf9179f71](https://linux-hardware.org/?probe=adf9179f71) | Oct 11, 2021 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [6e46c6efad](https://linux-hardware.org/?probe=6e46c6efad) | Oct 11, 2021 |
| Acer          | Swift SF314-42              | [bce3e39f4c](https://linux-hardware.org/?probe=bce3e39f4c) | Oct 10, 2021 |
| Acer          | Swift SF314-42              | [1c4fbe0fa4](https://linux-hardware.org/?probe=1c4fbe0fa4) | Oct 10, 2021 |
| Google        | Delbin                      | [a712393014](https://linux-hardware.org/?probe=a712393014) | Oct 10, 2021 |
| Lenovo        | ThinkPad X230 2324FV6       | [eaf1bb2c45](https://linux-hardware.org/?probe=eaf1bb2c45) | Oct 09, 2021 |
| Acer          | Extensa 5635Z               | [4e0d4fc31e](https://linux-hardware.org/?probe=4e0d4fc31e) | Oct 07, 2021 |
| Acer          | Nitro AN515-45              | [6918b927d0](https://linux-hardware.org/?probe=6918b927d0) | Oct 07, 2021 |
| Acer          | Extensa 5635Z               | [b60109c4e1](https://linux-hardware.org/?probe=b60109c4e1) | Oct 07, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [48c1ff5b7e](https://linux-hardware.org/?probe=48c1ff5b7e) | Oct 07, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [33137c7c23](https://linux-hardware.org/?probe=33137c7c23) | Oct 07, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [69752b194b](https://linux-hardware.org/?probe=69752b194b) | Oct 06, 2021 |
| MSI           | GP66 Leopard 11UG           | [f72ab1b3eb](https://linux-hardware.org/?probe=f72ab1b3eb) | Oct 05, 2021 |
| TUXEDO        | InfinityBook S 15 Gen6      | [1af27d6451](https://linux-hardware.org/?probe=1af27d6451) | Oct 04, 2021 |
| Dell          | XPS 13 9380                 | [0b768f6fac](https://linux-hardware.org/?probe=0b768f6fac) | Oct 04, 2021 |
| ASUSTek       | X555LD                      | [c3bbad62c6](https://linux-hardware.org/?probe=c3bbad62c6) | Oct 04, 2021 |
| Acer          | Nitro AN515-54              | [cfe8864b1f](https://linux-hardware.org/?probe=cfe8864b1f) | Oct 04, 2021 |
| Framework     | Laptop                      | [9b67aff13b](https://linux-hardware.org/?probe=9b67aff13b) | Oct 04, 2021 |
| Dell          | Latitude E7450              | [f7faec22bf](https://linux-hardware.org/?probe=f7faec22bf) | Oct 03, 2021 |
| Dell          | Latitude E7450              | [f5dea355f4](https://linux-hardware.org/?probe=f5dea355f4) | Oct 03, 2021 |
| HP            | ZHAN 66 Pro 15 G3           | [0f58e969f6](https://linux-hardware.org/?probe=0f58e969f6) | Oct 03, 2021 |
| HP            | 15                          | [a9f0ec716f](https://linux-hardware.org/?probe=a9f0ec716f) | Oct 03, 2021 |
| HP            | 15                          | [e6f3f8f6ee](https://linux-hardware.org/?probe=e6f3f8f6ee) | Oct 03, 2021 |
| ASUSTek       | K55VM                       | [848fef92f0](https://linux-hardware.org/?probe=848fef92f0) | Oct 02, 2021 |
| Acer          | Peppy                       | [9779f3cabd](https://linux-hardware.org/?probe=9779f3cabd) | Oct 02, 2021 |
| HP            | 255 G7 Notebook PC          | [472633cfb7](https://linux-hardware.org/?probe=472633cfb7) | Oct 02, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [9843c09d18](https://linux-hardware.org/?probe=9843c09d18) | Oct 02, 2021 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [8e7fe0d176](https://linux-hardware.org/?probe=8e7fe0d176) | Oct 01, 2021 |
| Dell          | Latitude E5470              | [b4171e377e](https://linux-hardware.org/?probe=b4171e377e) | Oct 01, 2021 |
| HP            | EliteBook 840 G6            | [cd2412d37e](https://linux-hardware.org/?probe=cd2412d37e) | Oct 01, 2021 |
| Hyperbook     | Z15 Zen                     | [33127f8488](https://linux-hardware.org/?probe=33127f8488) | Oct 01, 2021 |
| Dell          | XPS 15 9500                 | [ca9966968c](https://linux-hardware.org/?probe=ca9966968c) | Oct 01, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [7aabf374a2](https://linux-hardware.org/?probe=7aabf374a2) | Sep 30, 2021 |
| Eluktronic... | RP-15                       | [c147de5b16](https://linux-hardware.org/?probe=c147de5b16) | Sep 30, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [e8dc01aef2](https://linux-hardware.org/?probe=e8dc01aef2) | Sep 30, 2021 |
| Notebook      | P7xxTM1                     | [a63472fe1d](https://linux-hardware.org/?probe=a63472fe1d) | Sep 30, 2021 |
| HP            | ProBook 440 G8 Notebook ... | [e11ce63403](https://linux-hardware.org/?probe=e11ce63403) | Sep 29, 2021 |
| Lenovo        | ThinkPad T490 20N20009RT    | [4d28ac0812](https://linux-hardware.org/?probe=4d28ac0812) | Sep 29, 2021 |
| Dell          | XPS 15 9500                 | [ee67fb66ed](https://linux-hardware.org/?probe=ee67fb66ed) | Sep 29, 2021 |
| TUXEDO        | Book BA1510                 | [e408c8fb46](https://linux-hardware.org/?probe=e408c8fb46) | Sep 28, 2021 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [db7c214214](https://linux-hardware.org/?probe=db7c214214) | Sep 28, 2021 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [6cfb3f0c44](https://linux-hardware.org/?probe=6cfb3f0c44) | Sep 28, 2021 |
| Acer          | Aspire V5-471               | [a9e4f4822e](https://linux-hardware.org/?probe=a9e4f4822e) | Sep 28, 2021 |
| HP            | 350 G2                      | [29da7cc52e](https://linux-hardware.org/?probe=29da7cc52e) | Sep 26, 2021 |
| Sony          | VPCEH1S1E                   | [a337d919b1](https://linux-hardware.org/?probe=a337d919b1) | Sep 25, 2021 |
| Dell          | Inspiron 11-3168            | [4c7c72b321](https://linux-hardware.org/?probe=4c7c72b321) | Sep 25, 2021 |
| ASUSTek       | K53SD                       | [0f6a772a44](https://linux-hardware.org/?probe=0f6a772a44) | Sep 25, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TAC... | [7745647936](https://linux-hardware.org/?probe=7745647936) | Sep 24, 2021 |
| Dell          | XPS 15 9500                 | [e975dc486c](https://linux-hardware.org/?probe=e975dc486c) | Sep 24, 2021 |
| Acer          | Aspire E5-573G              | [fb2aa21c82](https://linux-hardware.org/?probe=fb2aa21c82) | Sep 24, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [534a4c683f](https://linux-hardware.org/?probe=534a4c683f) | Sep 24, 2021 |
| Lenovo        | ThinkPad X200 74574AC       | [be9156bd20](https://linux-hardware.org/?probe=be9156bd20) | Sep 24, 2021 |
| Dell          | Inspiron 5575               | [57a0b50aec](https://linux-hardware.org/?probe=57a0b50aec) | Sep 23, 2021 |
| Dell          | Inspiron 5575               | [f40c9de6c3](https://linux-hardware.org/?probe=f40c9de6c3) | Sep 23, 2021 |
| ASUSTek       | GL752VW                     | [79007686bc](https://linux-hardware.org/?probe=79007686bc) | Sep 23, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [28cec81520](https://linux-hardware.org/?probe=28cec81520) | Sep 22, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [8141d6fa89](https://linux-hardware.org/?probe=8141d6fa89) | Sep 22, 2021 |
| Acer          | Aspire A515-44              | [94203d3564](https://linux-hardware.org/?probe=94203d3564) | Sep 22, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [a240f7e211](https://linux-hardware.org/?probe=a240f7e211) | Sep 22, 2021 |
| Framework     | Laptop                      | [8c2272b18b](https://linux-hardware.org/?probe=8c2272b18b) | Sep 22, 2021 |
| HP            | ProBook 445 G7 Notebook ... | [c9a187f9b5](https://linux-hardware.org/?probe=c9a187f9b5) | Sep 22, 2021 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [99ddef5ed9](https://linux-hardware.org/?probe=99ddef5ed9) | Sep 21, 2021 |
| Apple         | MacBookPro15,1              | [3a3ccf8143](https://linux-hardware.org/?probe=3a3ccf8143) | Sep 21, 2021 |
| ASUSTek       | X55U                        | [953078ddf4](https://linux-hardware.org/?probe=953078ddf4) | Sep 20, 2021 |
| HP            | Laptop 15s-eq2xxx           | [e2593bb917](https://linux-hardware.org/?probe=e2593bb917) | Sep 20, 2021 |
| HP            | Pavilion g6                 | [4c2e2b745c](https://linux-hardware.org/?probe=4c2e2b745c) | Sep 20, 2021 |
| HP            | Pavilion g6                 | [ac47a40b15](https://linux-hardware.org/?probe=ac47a40b15) | Sep 20, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [e106c35284](https://linux-hardware.org/?probe=e106c35284) | Sep 20, 2021 |
| Lenovo        | Yoga 900-13ISK 80MK         | [7166b839d8](https://linux-hardware.org/?probe=7166b839d8) | Sep 19, 2021 |
| ASUSTek       | VivoBook S15 X510UF         | [883e0dec71](https://linux-hardware.org/?probe=883e0dec71) | Sep 19, 2021 |
| Lenovo        | Yoga 900-13ISK 80MK         | [937cdf5686](https://linux-hardware.org/?probe=937cdf5686) | Sep 19, 2021 |
| Lenovo        | ThinkPad P50 20EQS25D0G     | [21cc4f0d72](https://linux-hardware.org/?probe=21cc4f0d72) | Sep 19, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [b528c44b32](https://linux-hardware.org/?probe=b528c44b32) | Sep 18, 2021 |
| HP            | Compaq 8510p                | [cbf5040ff7](https://linux-hardware.org/?probe=cbf5040ff7) | Sep 17, 2021 |
| Dell          | Latitude E7250              | [f22656907f](https://linux-hardware.org/?probe=f22656907f) | Sep 16, 2021 |
| MECHREVO      | Code 01 Series PF5NU1G      | [88cae87203](https://linux-hardware.org/?probe=88cae87203) | Sep 16, 2021 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | [60004ef2bb](https://linux-hardware.org/?probe=60004ef2bb) | Sep 16, 2021 |
| Acer          | Aspire V3-571G              | [2b132c74b6](https://linux-hardware.org/?probe=2b132c74b6) | Sep 16, 2021 |
| Acer          | Aspire V3-571G              | [ca2bc77aa5](https://linux-hardware.org/?probe=ca2bc77aa5) | Sep 16, 2021 |
| TUXEDO        | Book BA1510                 | [2397ee987d](https://linux-hardware.org/?probe=2397ee987d) | Sep 15, 2021 |
| Apple         | MacBookPro15,1              | [73bab0d19c](https://linux-hardware.org/?probe=73bab0d19c) | Sep 15, 2021 |
| HP            | ProBook 450 G6              | [e03d6ba4c2](https://linux-hardware.org/?probe=e03d6ba4c2) | Sep 15, 2021 |
| Lenovo        | ThinkPad T460p 20FW0005A... | [8f19930d07](https://linux-hardware.org/?probe=8f19930d07) | Sep 15, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 80X4     | [8407fe83d7](https://linux-hardware.org/?probe=8407fe83d7) | Sep 14, 2021 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [620fd14b92](https://linux-hardware.org/?probe=620fd14b92) | Sep 14, 2021 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [d58f229004](https://linux-hardware.org/?probe=d58f229004) | Sep 14, 2021 |
| Lenovo        | ThinkPad X390 20Q00058MH    | [01755fd33c](https://linux-hardware.org/?probe=01755fd33c) | Sep 13, 2021 |
| Lenovo        | ThinkPad W541 20EFS01B09    | [8dd2c7497e](https://linux-hardware.org/?probe=8dd2c7497e) | Sep 13, 2021 |
| Dell          | Latitude E6430              | [3626675792](https://linux-hardware.org/?probe=3626675792) | Sep 12, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [d0e2e19e84](https://linux-hardware.org/?probe=d0e2e19e84) | Sep 12, 2021 |
| Dell          | XPS 13 9380                 | [e972359bdf](https://linux-hardware.org/?probe=e972359bdf) | Sep 12, 2021 |
| ASUSTek       | ZenBook UX425JA_UX425JA     | [44e4c991ca](https://linux-hardware.org/?probe=44e4c991ca) | Sep 12, 2021 |
| HP            | Pavilion g6                 | [e303d0a48a](https://linux-hardware.org/?probe=e303d0a48a) | Sep 12, 2021 |
| HP            | Pavilion g6                 | [b970db8313](https://linux-hardware.org/?probe=b970db8313) | Sep 12, 2021 |
| Acer          | Swift SF314-511             | [4286a4710c](https://linux-hardware.org/?probe=4286a4710c) | Sep 11, 2021 |
| Acer          | Aspire 5741ZG               | [e9ef45456c](https://linux-hardware.org/?probe=e9ef45456c) | Sep 11, 2021 |
| Acer          | Aspire 5741ZG               | [bdcfab6eb5](https://linux-hardware.org/?probe=bdcfab6eb5) | Sep 11, 2021 |
| Lenovo        | IdeaPad 320S-13IKB 81AK     | [3c2564d223](https://linux-hardware.org/?probe=3c2564d223) | Sep 11, 2021 |
| HP            | ProBook 640 G5              | [8ecd82ac84](https://linux-hardware.org/?probe=8ecd82ac84) | Sep 10, 2021 |
| Acer          | AO722                       | [c3db5acb34](https://linux-hardware.org/?probe=c3db5acb34) | Sep 09, 2021 |
| HP            | EliteBook 8470p             | [1dd7e46071](https://linux-hardware.org/?probe=1dd7e46071) | Sep 09, 2021 |
| TUXEDO        | Book_XA1510                 | [611957e5f1](https://linux-hardware.org/?probe=611957e5f1) | Sep 09, 2021 |
| Google        | Delbin                      | [d36cba3746](https://linux-hardware.org/?probe=d36cba3746) | Sep 09, 2021 |
| HP            | Laptop 15s-eq0xxx           | [361beeda3d](https://linux-hardware.org/?probe=361beeda3d) | Sep 08, 2021 |
| Intel         | Pine Trail - M Revision ... | [147f6959ad](https://linux-hardware.org/?probe=147f6959ad) | Sep 08, 2021 |
| ASUSTek       | UX530UX                     | [c713dcf9e2](https://linux-hardware.org/?probe=c713dcf9e2) | Sep 08, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [66acc2cf73](https://linux-hardware.org/?probe=66acc2cf73) | Sep 07, 2021 |
| Acer          | Aspire A515-44              | [2bea52d2d8](https://linux-hardware.org/?probe=2bea52d2d8) | Sep 07, 2021 |
| Acer          | Aspire A515-51G             | [63cddbf8f9](https://linux-hardware.org/?probe=63cddbf8f9) | Sep 05, 2021 |
| Apple         | MacBookAir7,2               | [92978eec15](https://linux-hardware.org/?probe=92978eec15) | Sep 05, 2021 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [e5a1539353](https://linux-hardware.org/?probe=e5a1539353) | Sep 05, 2021 |
| Toshiba       | dynabook T55/PW             | [1ce1b25ad5](https://linux-hardware.org/?probe=1ce1b25ad5) | Sep 04, 2021 |
| Dell          | Inspiron 3785               | [8fad89cd6b](https://linux-hardware.org/?probe=8fad89cd6b) | Sep 04, 2021 |
| Samsung       | 275E4E/275E5E               | [1503acee14](https://linux-hardware.org/?probe=1503acee14) | Sep 04, 2021 |
| MSI           | GL65 9SEK                   | [1db789e204](https://linux-hardware.org/?probe=1db789e204) | Sep 03, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [acc05dc902](https://linux-hardware.org/?probe=acc05dc902) | Sep 03, 2021 |
| Apple         | MacBookPro16,1              | [4bb5bbcfd7](https://linux-hardware.org/?probe=4bb5bbcfd7) | Sep 02, 2021 |
| HP            | EliteBook 850 G5            | [cd819892ba](https://linux-hardware.org/?probe=cd819892ba) | Sep 02, 2021 |
| ASUSTek       | N551JX                      | [66e7ade0f9](https://linux-hardware.org/?probe=66e7ade0f9) | Sep 02, 2021 |
| HP            | EliteBook 850 G5            | [7cd9e2b617](https://linux-hardware.org/?probe=7cd9e2b617) | Sep 02, 2021 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [0c32c5b849](https://linux-hardware.org/?probe=0c32c5b849) | Sep 02, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [08697dbfcd](https://linux-hardware.org/?probe=08697dbfcd) | Sep 01, 2021 |
| Acer          | Aspire V3-571G              | [b011298d66](https://linux-hardware.org/?probe=b011298d66) | Sep 01, 2021 |
| GPD           | G1618-03                    | [41916177c2](https://linux-hardware.org/?probe=41916177c2) | Sep 01, 2021 |
| GPD           | G1618-03                    | [c2abcaf10c](https://linux-hardware.org/?probe=c2abcaf10c) | Sep 01, 2021 |
| Lenovo        | ThinkPad T440 20B6CTO1WW    | [d294b3f8f1](https://linux-hardware.org/?probe=d294b3f8f1) | Sep 01, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [7c07413efb](https://linux-hardware.org/?probe=7c07413efb) | Sep 01, 2021 |
| Fujitsu       | LIFEBOOK U7310              | [6d2339463c](https://linux-hardware.org/?probe=6d2339463c) | Sep 01, 2021 |
| MSI           | GL65 9SEK                   | [620fe29cdf](https://linux-hardware.org/?probe=620fe29cdf) | Aug 31, 2021 |
| ASUSTek       | X550LN                      | [46a61ffaa2](https://linux-hardware.org/?probe=46a61ffaa2) | Aug 31, 2021 |
| Lenovo        | IdeaPad Y510P 20217         | [eeb41e2209](https://linux-hardware.org/?probe=eeb41e2209) | Aug 31, 2021 |
| ASUSTek       | ZenBook Pro 15 UX550GE_U... | [7a407e7543](https://linux-hardware.org/?probe=7a407e7543) | Aug 31, 2021 |
| Lenovo        | ThinkPad T510 4314DEU       | [4ab1f8b52e](https://linux-hardware.org/?probe=4ab1f8b52e) | Aug 31, 2021 |
| GPD           | G1618-03                    | [d680dd4360](https://linux-hardware.org/?probe=d680dd4360) | Aug 31, 2021 |
| Acer          | Nitro AN515-43              | [580efac81c](https://linux-hardware.org/?probe=580efac81c) | Aug 30, 2021 |
| MSI           | GL65 9SEK                   | [5671593a3d](https://linux-hardware.org/?probe=5671593a3d) | Aug 30, 2021 |
| Dell          | Latitude E6230              | [055cc1b72a](https://linux-hardware.org/?probe=055cc1b72a) | Aug 30, 2021 |
| Dell          | G5 5590                     | [268f4cffb4](https://linux-hardware.org/?probe=268f4cffb4) | Aug 30, 2021 |
| Dell          | Latitude E7240              | [0c834ea6d8](https://linux-hardware.org/?probe=0c834ea6d8) | Aug 30, 2021 |
| Intel         | SandyBridge Platform        | [cde550fde9](https://linux-hardware.org/?probe=cde550fde9) | Aug 30, 2021 |
| Dell          | Inspiron 5520               | [ff1579dda4](https://linux-hardware.org/?probe=ff1579dda4) | Aug 29, 2021 |
| Sony          | SVE1113M1EW                 | [8b0721e72c](https://linux-hardware.org/?probe=8b0721e72c) | Aug 29, 2021 |
| ASUSTek       | ZenBook Pro 15 UX550GE_U... | [e9eb54512d](https://linux-hardware.org/?probe=e9eb54512d) | Aug 29, 2021 |
| Lenovo        | G400s VILG1                 | [20d6b25fd3](https://linux-hardware.org/?probe=20d6b25fd3) | Aug 29, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [97afdfd346](https://linux-hardware.org/?probe=97afdfd346) | Aug 29, 2021 |
| HP            | ProBook 450 G3              | [babc892804](https://linux-hardware.org/?probe=babc892804) | Aug 28, 2021 |
| Dell          | XPS 15 7590                 | [80e5272f76](https://linux-hardware.org/?probe=80e5272f76) | Aug 28, 2021 |
| MSI           | GE66 Raider 10SFS           | [6e7cfb3d12](https://linux-hardware.org/?probe=6e7cfb3d12) | Aug 28, 2021 |
| Acer          | Aspire E5-521               | [5716a5328f](https://linux-hardware.org/?probe=5716a5328f) | Aug 28, 2021 |
| Acer          | Aspire E5-573G              | [78ad2b6854](https://linux-hardware.org/?probe=78ad2b6854) | Aug 27, 2021 |
| Eluktronic... | THINN-15                    | [3371828db5](https://linux-hardware.org/?probe=3371828db5) | Aug 27, 2021 |
| Dell          | Precision 7560              | [75c607555e](https://linux-hardware.org/?probe=75c607555e) | Aug 27, 2021 |
| Dell          | Vostro1710                  | [b56378610a](https://linux-hardware.org/?probe=b56378610a) | Aug 27, 2021 |
| Dell          | Latitude 5420 Rugged        | [079460ff34](https://linux-hardware.org/?probe=079460ff34) | Aug 27, 2021 |
| Notebook      | N85_N87,HJ,HJ1,HK1          | [e7d4558643](https://linux-hardware.org/?probe=e7d4558643) | Aug 26, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [516c59e9bb](https://linux-hardware.org/?probe=516c59e9bb) | Aug 26, 2021 |
| Intel         | SandyBridge Platform        | [3b2180f4ae](https://linux-hardware.org/?probe=3b2180f4ae) | Aug 26, 2021 |
| MSI           | GP62 7RD                    | [79183c00ea](https://linux-hardware.org/?probe=79183c00ea) | Aug 25, 2021 |
| Dell          | Inspiron 5570               | [235a060440](https://linux-hardware.org/?probe=235a060440) | Aug 25, 2021 |
| ASUSTek       | X205TAW                     | [09a1f35f1b](https://linux-hardware.org/?probe=09a1f35f1b) | Aug 25, 2021 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | [4362c6ef79](https://linux-hardware.org/?probe=4362c6ef79) | Aug 24, 2021 |
| HUAWEI        | NBLL-WXX9                   | [11b752eb71](https://linux-hardware.org/?probe=11b752eb71) | Aug 23, 2021 |
| Acer          | Aspire V3-371               | [d34df8e36e](https://linux-hardware.org/?probe=d34df8e36e) | Aug 23, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [be4febc53b](https://linux-hardware.org/?probe=be4febc53b) | Aug 23, 2021 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [1893452fad](https://linux-hardware.org/?probe=1893452fad) | Aug 22, 2021 |
| Dell          | Inspiron 5577               | [f6fa87a9c7](https://linux-hardware.org/?probe=f6fa87a9c7) | Aug 22, 2021 |
| ASUSTek       | GL752VW                     | [cb94b79d0d](https://linux-hardware.org/?probe=cb94b79d0d) | Aug 22, 2021 |
| Dell          | Inspiron 3583               | [0c1b7de3c6](https://linux-hardware.org/?probe=0c1b7de3c6) | Aug 22, 2021 |
| HP            | EliteBook 840 G6            | [9532e24f35](https://linux-hardware.org/?probe=9532e24f35) | Aug 21, 2021 |
| HP            | EliteBook 840 G6            | [fe1661f42b](https://linux-hardware.org/?probe=fe1661f42b) | Aug 21, 2021 |
| Lenovo        | ThinkPad T570 20JXS1S900    | [dec9f41914](https://linux-hardware.org/?probe=dec9f41914) | Aug 21, 2021 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [b82146eec2](https://linux-hardware.org/?probe=b82146eec2) | Aug 21, 2021 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [620599dff3](https://linux-hardware.org/?probe=620599dff3) | Aug 21, 2021 |
| Acer          | Aspire F5-572G              | [7cb9e5444b](https://linux-hardware.org/?probe=7cb9e5444b) | Aug 19, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [8461b48819](https://linux-hardware.org/?probe=8461b48819) | Aug 19, 2021 |
| Lenovo        | ThinkPad T440 20B60061MD    | [5f9d1cd1a6](https://linux-hardware.org/?probe=5f9d1cd1a6) | Aug 18, 2021 |
| PC Special... | Standard                    | [b7baa43d24](https://linux-hardware.org/?probe=b7baa43d24) | Aug 18, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | [735e9cba22](https://linux-hardware.org/?probe=735e9cba22) | Aug 18, 2021 |
| ASUSTek       | GL752VW                     | [3a2a0e0204](https://linux-hardware.org/?probe=3a2a0e0204) | Aug 17, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [e0bb471580](https://linux-hardware.org/?probe=e0bb471580) | Aug 17, 2021 |
| Apple         | MacBookPro15,1              | [c797030409](https://linux-hardware.org/?probe=c797030409) | Aug 17, 2021 |
| Toshiba       | Satellite L55-C             | [a565258ce1](https://linux-hardware.org/?probe=a565258ce1) | Aug 17, 2021 |
| HP            | Laptop 14-df0xxx            | [da7d5c133c](https://linux-hardware.org/?probe=da7d5c133c) | Aug 17, 2021 |
| HP            | Notebook                    | [50a8d63a0d](https://linux-hardware.org/?probe=50a8d63a0d) | Aug 16, 2021 |
| Lenovo        | ThinkPad X395 20NL0005US    | [d4b1c184ee](https://linux-hardware.org/?probe=d4b1c184ee) | Aug 16, 2021 |
| Samsung       | 550XDA                      | [244a7e0557](https://linux-hardware.org/?probe=244a7e0557) | Aug 15, 2021 |
| Samsung       | 550XDA                      | [a4a0ff8db8](https://linux-hardware.org/?probe=a4a0ff8db8) | Aug 15, 2021 |
| HP            | EliteBook 745 G5            | [7154f86bd2](https://linux-hardware.org/?probe=7154f86bd2) | Aug 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [9099610ac6](https://linux-hardware.org/?probe=9099610ac6) | Aug 15, 2021 |
| MSI           | GL63 8SE                    | [1ddd546c85](https://linux-hardware.org/?probe=1ddd546c85) | Aug 15, 2021 |
| HP            | EliteBook 820 G3            | [9e40c4d015](https://linux-hardware.org/?probe=9e40c4d015) | Aug 15, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [77c51b6b7b](https://linux-hardware.org/?probe=77c51b6b7b) | Aug 15, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | [f4503e4a04](https://linux-hardware.org/?probe=f4503e4a04) | Aug 15, 2021 |
| Apple         | MacBookAir4,1               | [5ebcdd94a7](https://linux-hardware.org/?probe=5ebcdd94a7) | Aug 15, 2021 |
| Lenovo        | ThinkPad T480s 20L8S3DK1... | [695ac6427d](https://linux-hardware.org/?probe=695ac6427d) | Aug 15, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [7fc85e36c6](https://linux-hardware.org/?probe=7fc85e36c6) | Aug 14, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [9cf85e6952](https://linux-hardware.org/?probe=9cf85e6952) | Aug 14, 2021 |
| Dell          | Inspiron 5577               | [613d21d87b](https://linux-hardware.org/?probe=613d21d87b) | Aug 14, 2021 |
| Lenovo        | ThinkPad T440 20B60061MD    | [fcd91a58e2](https://linux-hardware.org/?probe=fcd91a58e2) | Aug 13, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [5742cb7dd7](https://linux-hardware.org/?probe=5742cb7dd7) | Aug 12, 2021 |
| Dell          | Latitude 5300               | [17a1dbdc0d](https://linux-hardware.org/?probe=17a1dbdc0d) | Aug 12, 2021 |
| Dell          | Studio 1450                 | [4210599af2](https://linux-hardware.org/?probe=4210599af2) | Aug 12, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [791486ac11](https://linux-hardware.org/?probe=791486ac11) | Aug 11, 2021 |
| HP            | EliteBook 8470p             | [e0a8156e11](https://linux-hardware.org/?probe=e0a8156e11) | Aug 11, 2021 |
| ASUSTek       | X550JX                      | [da2cacc763](https://linux-hardware.org/?probe=da2cacc763) | Aug 11, 2021 |
| Dell          | XPS 15 7590                 | [ec22347a62](https://linux-hardware.org/?probe=ec22347a62) | Aug 10, 2021 |
| Acer          | Aspire ES1-533              | [cbd597c9a6](https://linux-hardware.org/?probe=cbd597c9a6) | Aug 10, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [19eed9d32d](https://linux-hardware.org/?probe=19eed9d32d) | Aug 10, 2021 |
| HP            | EliteBook 8740w             | [3c345bc85c](https://linux-hardware.org/?probe=3c345bc85c) | Aug 09, 2021 |
| Dell          | Latitude E6510              | [13e2d05856](https://linux-hardware.org/?probe=13e2d05856) | Aug 09, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [7eda370c4a](https://linux-hardware.org/?probe=7eda370c4a) | Aug 08, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [8d464633db](https://linux-hardware.org/?probe=8d464633db) | Aug 08, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [bd3d1ed844](https://linux-hardware.org/?probe=bd3d1ed844) | Aug 08, 2021 |
| Acer          | Aspire E5-575               | [a859929261](https://linux-hardware.org/?probe=a859929261) | Aug 08, 2021 |
| Dell          | XPS 15 9500                 | [7520bd42bf](https://linux-hardware.org/?probe=7520bd42bf) | Aug 08, 2021 |
| ASUSTek       | GL752VW                     | [6a065328e1](https://linux-hardware.org/?probe=6a065328e1) | Aug 08, 2021 |
| Lenovo        | V155-15API 81V5             | [fbb5b0de92](https://linux-hardware.org/?probe=fbb5b0de92) | Aug 08, 2021 |
| Lenovo        | ThinkPad T440p 2000CT0      | [574392d159](https://linux-hardware.org/?probe=574392d159) | Aug 07, 2021 |
| Acer          | Aspire A515-44              | [ce69ebd65c](https://linux-hardware.org/?probe=ce69ebd65c) | Aug 07, 2021 |
| GPD           | G1618-03                    | [25a0b540aa](https://linux-hardware.org/?probe=25a0b540aa) | Aug 07, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [e3f477789b](https://linux-hardware.org/?probe=e3f477789b) | Aug 06, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [0c9d109446](https://linux-hardware.org/?probe=0c9d109446) | Aug 06, 2021 |
| Lenovo        | ThinkPad L390 20NR001LGE    | [ae8cde2ce0](https://linux-hardware.org/?probe=ae8cde2ce0) | Aug 06, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [a4ba68cc4e](https://linux-hardware.org/?probe=a4ba68cc4e) | Aug 06, 2021 |
| Dell          | Inspiron 5593               | [1f6017347e](https://linux-hardware.org/?probe=1f6017347e) | Aug 05, 2021 |
| HP            | EliteBook 8530p             | [844351ff2c](https://linux-hardware.org/?probe=844351ff2c) | Aug 05, 2021 |
| Dell          | XPS 15 9560                 | [2dee4232d5](https://linux-hardware.org/?probe=2dee4232d5) | Aug 05, 2021 |
| ASUSTek       | N53SV                       | [1e165352ad](https://linux-hardware.org/?probe=1e165352ad) | Aug 04, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 80X4     | [45046455dc](https://linux-hardware.org/?probe=45046455dc) | Aug 04, 2021 |
| Lenovo        | ThinkPad X230 Tablet 343... | [76ae0e2554](https://linux-hardware.org/?probe=76ae0e2554) | Aug 04, 2021 |
| Dell          | Inspiron 11-3168            | [b1d63336dc](https://linux-hardware.org/?probe=b1d63336dc) | Aug 04, 2021 |
| Acer          | Aspire E1-570G              | [7f839b8f46](https://linux-hardware.org/?probe=7f839b8f46) | Aug 03, 2021 |
| MSI           | Bravo 17 A4DDK              | [bcb7170c7f](https://linux-hardware.org/?probe=bcb7170c7f) | Aug 03, 2021 |
| HP            | Laptop 14-bs1xx             | [6770f5a114](https://linux-hardware.org/?probe=6770f5a114) | Aug 03, 2021 |
| MSI           | Modern 14 B4MW              | [840e7730e2](https://linux-hardware.org/?probe=840e7730e2) | Aug 02, 2021 |
| MSI           | Modern 14 B4MW              | [ac04deced5](https://linux-hardware.org/?probe=ac04deced5) | Aug 02, 2021 |
| HP            | Pavilion Laptop 13-an0xx... | [ff5bee5ff8](https://linux-hardware.org/?probe=ff5bee5ff8) | Aug 01, 2021 |
| HUAWEI        | NBLL-WXX9                   | [2cc3a3c1d9](https://linux-hardware.org/?probe=2cc3a3c1d9) | Jul 31, 2021 |
| HUAWEI        | NBLL-WXX9                   | [e38e82c69a](https://linux-hardware.org/?probe=e38e82c69a) | Jul 31, 2021 |
| Lenovo        | ThinkPad P50 20EN0007MS     | [73902de0d8](https://linux-hardware.org/?probe=73902de0d8) | Jul 31, 2021 |
| Toshiba       | Satellite L850-1LK          | [8e8d84c8eb](https://linux-hardware.org/?probe=8e8d84c8eb) | Jul 30, 2021 |
| Dell          | Vostro 1015                 | [0e16f2bc9c](https://linux-hardware.org/?probe=0e16f2bc9c) | Jul 30, 2021 |
| Toshiba       | Satellite L850-1LK          | [b0b636bbee](https://linux-hardware.org/?probe=b0b636bbee) | Jul 30, 2021 |
| HP            | ProBook 450 G2              | [6d45e5794a](https://linux-hardware.org/?probe=6d45e5794a) | Jul 29, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [1d638fd7ae](https://linux-hardware.org/?probe=1d638fd7ae) | Jul 29, 2021 |
| ASUSTek       | N53SV                       | [13e3cf7a5f](https://linux-hardware.org/?probe=13e3cf7a5f) | Jul 29, 2021 |
| Razer         | Blade 14 - RZ09-0370        | [3927a38ae3](https://linux-hardware.org/?probe=3927a38ae3) | Jul 28, 2021 |
| Lenovo        | ThinkPad T410 2522W5D       | [32c38164aa](https://linux-hardware.org/?probe=32c38164aa) | Jul 28, 2021 |
| Acer          | Nitro AN515-52              | [68e8608d11](https://linux-hardware.org/?probe=68e8608d11) | Jul 28, 2021 |
| MSI           | GT62VR 7RE                  | [5f02658195](https://linux-hardware.org/?probe=5f02658195) | Jul 27, 2021 |
| Acer          | Aspire 5735                 | [a28b01d57e](https://linux-hardware.org/?probe=a28b01d57e) | Jul 27, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | [efc844205b](https://linux-hardware.org/?probe=efc844205b) | Jul 27, 2021 |
| Positivo      | CHT12CP                     | [85ff7d5708](https://linux-hardware.org/?probe=85ff7d5708) | Jul 27, 2021 |
| Lenovo        | ThinkPad T460p 20FW0005A... | [2a54318c46](https://linux-hardware.org/?probe=2a54318c46) | Jul 27, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [19b3b1a4ee](https://linux-hardware.org/?probe=19b3b1a4ee) | Jul 27, 2021 |
| HP            | Laptop 14-cm0xxx            | [4f0cb504ec](https://linux-hardware.org/?probe=4f0cb504ec) | Jul 26, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [51fe0127e7](https://linux-hardware.org/?probe=51fe0127e7) | Jul 26, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [10b4953c7e](https://linux-hardware.org/?probe=10b4953c7e) | Jul 26, 2021 |
| Dell          | Latitude E5250              | [f50f84a6a3](https://linux-hardware.org/?probe=f50f84a6a3) | Jul 26, 2021 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [e74f010570](https://linux-hardware.org/?probe=e74f010570) | Jul 26, 2021 |
| Dell          | G5 5505                     | [cb0527cc40](https://linux-hardware.org/?probe=cb0527cc40) | Jul 26, 2021 |
| HP            | 250 G7 Notebook PC          | [0207d45fee](https://linux-hardware.org/?probe=0207d45fee) | Jul 26, 2021 |
| Lenovo        | IdeaPad Z400 Touch VIWZ1    | [75a01751c3](https://linux-hardware.org/?probe=75a01751c3) | Jul 25, 2021 |
| HP            | 250 G7 Notebook PC          | [a1a8e51991](https://linux-hardware.org/?probe=a1a8e51991) | Jul 25, 2021 |
| ASUSTek       | GX501VIK                    | [5dd879c697](https://linux-hardware.org/?probe=5dd879c697) | Jul 25, 2021 |
| Lenovo        | ThinkPad T410 2522W5D       | [7c8122cefe](https://linux-hardware.org/?probe=7c8122cefe) | Jul 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [4322cd9adf](https://linux-hardware.org/?probe=4322cd9adf) | Jul 25, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [5a4803b91b](https://linux-hardware.org/?probe=5a4803b91b) | Jul 25, 2021 |
| Dell          | Latitude E5250              | [9806ab15ab](https://linux-hardware.org/?probe=9806ab15ab) | Jul 25, 2021 |
| Dell          | Latitude E5250              | [9a475d76a4](https://linux-hardware.org/?probe=9a475d76a4) | Jul 25, 2021 |
| Acer          | Nitro AN515-45              | [fbf1f240f4](https://linux-hardware.org/?probe=fbf1f240f4) | Jul 24, 2021 |
| Chuwi         | LapBook Pro                 | [3b424912fa](https://linux-hardware.org/?probe=3b424912fa) | Jul 24, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | [4a458edcf6](https://linux-hardware.org/?probe=4a458edcf6) | Jul 24, 2021 |
| Sony          | SVE1713A1EW                 | [f63a4c173e](https://linux-hardware.org/?probe=f63a4c173e) | Jul 24, 2021 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [cc8bca442d](https://linux-hardware.org/?probe=cc8bca442d) | Jul 24, 2021 |
| HP            | ProBook 6450b               | [557056dd22](https://linux-hardware.org/?probe=557056dd22) | Jul 24, 2021 |
| Dell          | Inspiron 3583               | [46f1655ef9](https://linux-hardware.org/?probe=46f1655ef9) | Jul 24, 2021 |
| Lenovo        | ThinkPad X260 20F5S08P00    | [53f182a11d](https://linux-hardware.org/?probe=53f182a11d) | Jul 24, 2021 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [7815ba99db](https://linux-hardware.org/?probe=7815ba99db) | Jul 23, 2021 |
| Dell          | Latitude E7440              | [6e60b85b4a](https://linux-hardware.org/?probe=6e60b85b4a) | Jul 23, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [e481c52e98](https://linux-hardware.org/?probe=e481c52e98) | Jul 23, 2021 |
| LG Electro... | 17UD70P-PX76K               | [dc6d809e73](https://linux-hardware.org/?probe=dc6d809e73) | Jul 23, 2021 |
| LG Electro... | 17UD70P-PX76K               | [c0869b1919](https://linux-hardware.org/?probe=c0869b1919) | Jul 23, 2021 |
| Lenovo        | ThinkPad T480s 20L8S2N80... | [72cbbe92a0](https://linux-hardware.org/?probe=72cbbe92a0) | Jul 22, 2021 |
| Eluktronic... | THINN-15                    | [7aa75a0584](https://linux-hardware.org/?probe=7aa75a0584) | Jul 22, 2021 |
| Dell          | Inspiron 5515               | [262db9da1d](https://linux-hardware.org/?probe=262db9da1d) | Jul 22, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [9063c2c94b](https://linux-hardware.org/?probe=9063c2c94b) | Jul 22, 2021 |
| Lenovo        | Legion R70002020 82B6       | [d620ec97eb](https://linux-hardware.org/?probe=d620ec97eb) | Jul 21, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [9d13b7e8df](https://linux-hardware.org/?probe=9d13b7e8df) | Jul 21, 2021 |
| Lenovo        | ThinkPad E15 20RDCTO1WW     | [570d86d845](https://linux-hardware.org/?probe=570d86d845) | Jul 20, 2021 |
| Dell          | Latitude E7440              | [d8fd7fe06d](https://linux-hardware.org/?probe=d8fd7fe06d) | Jul 20, 2021 |
| Dell          | XPS 13 9310                 | [bcb7059afa](https://linux-hardware.org/?probe=bcb7059afa) | Jul 19, 2021 |
| HP            | Pavilion g4                 | [656a370d74](https://linux-hardware.org/?probe=656a370d74) | Jul 19, 2021 |
| HP            | ENVY TS m6 Sleekbook        | [2e1797ad6c](https://linux-hardware.org/?probe=2e1797ad6c) | Jul 19, 2021 |
| AZW           | GT-R                        | [115230aa47](https://linux-hardware.org/?probe=115230aa47) | Jul 19, 2021 |
| Lenovo        | ThinkPad T500 2089W6A       | [184daa4087](https://linux-hardware.org/?probe=184daa4087) | Jul 18, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [fc671b46d4](https://linux-hardware.org/?probe=fc671b46d4) | Jul 17, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [57ad37e858](https://linux-hardware.org/?probe=57ad37e858) | Jul 17, 2021 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | [c66b00a0b1](https://linux-hardware.org/?probe=c66b00a0b1) | Jul 17, 2021 |
| Lenovo        | ThinkPad X395 20NL0005US    | [51dbde3e85](https://linux-hardware.org/?probe=51dbde3e85) | Jul 17, 2021 |
| HP            | ProBook 430 G1              | [4b607fd8a5](https://linux-hardware.org/?probe=4b607fd8a5) | Jul 16, 2021 |
| Dell          | Precision 5540              | [2ea0168954](https://linux-hardware.org/?probe=2ea0168954) | Jul 16, 2021 |
| Dell          | Latitude E5250              | [d65621a003](https://linux-hardware.org/?probe=d65621a003) | Jul 16, 2021 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [56faa89619](https://linux-hardware.org/?probe=56faa89619) | Jul 16, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [27ea2ac026](https://linux-hardware.org/?probe=27ea2ac026) | Jul 16, 2021 |
| HP            | ProBook 6450b               | [f596a27975](https://linux-hardware.org/?probe=f596a27975) | Jul 16, 2021 |
| Sony          | SVE15111EBS                 | [65df293d03](https://linux-hardware.org/?probe=65df293d03) | Jul 16, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [ce02831a0a](https://linux-hardware.org/?probe=ce02831a0a) | Jul 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [23fea281d9](https://linux-hardware.org/?probe=23fea281d9) | Jul 14, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [2a4060981e](https://linux-hardware.org/?probe=2a4060981e) | Jul 14, 2021 |
| Lenovo        | ThinkPad T580 20L90025GE    | [304ba44405](https://linux-hardware.org/?probe=304ba44405) | Jul 13, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [6b11ceaab4](https://linux-hardware.org/?probe=6b11ceaab4) | Jul 13, 2021 |
| Dell          | Inspiron 1545               | [e4d655b420](https://linux-hardware.org/?probe=e4d655b420) | Jul 13, 2021 |
| PC Special... | Fusion IV                   | [b972aa6131](https://linux-hardware.org/?probe=b972aa6131) | Jul 13, 2021 |
| HUAWEI        | HLYL-WXX9                   | [272fc722c0](https://linux-hardware.org/?probe=272fc722c0) | Jul 12, 2021 |
| HP            | OMEN by Laptop 17-cb0xxx    | [03411156ff](https://linux-hardware.org/?probe=03411156ff) | Jul 12, 2021 |
| HP            | ProBook 430 G1              | [0311c022ff](https://linux-hardware.org/?probe=0311c022ff) | Jul 12, 2021 |
| Acer          | NC-V3-575G-58LU             | [da6da7fbd6](https://linux-hardware.org/?probe=da6da7fbd6) | Jul 11, 2021 |
| HP            | ProBook 6450b               | [d9d8115d98](https://linux-hardware.org/?probe=d9d8115d98) | Jul 11, 2021 |
| HP            | ProBook 6450b               | [c3bdfd8206](https://linux-hardware.org/?probe=c3bdfd8206) | Jul 11, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [25fd3802fd](https://linux-hardware.org/?probe=25fd3802fd) | Jul 11, 2021 |
| HP            | ProBook 450 G3              | [7d009c5619](https://linux-hardware.org/?probe=7d009c5619) | Jul 11, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [56668451b0](https://linux-hardware.org/?probe=56668451b0) | Jul 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [3508d853ae](https://linux-hardware.org/?probe=3508d853ae) | Jul 09, 2021 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [7c78cbb69a](https://linux-hardware.org/?probe=7c78cbb69a) | Jul 09, 2021 |
| Lenovo        | ThinkPad T490 20N2S3H300    | [7ca3d5ee11](https://linux-hardware.org/?probe=7ca3d5ee11) | Jul 09, 2021 |
| ASUSTek       | ZenBook 13 UX331FAL_UX33... | [31ae8b8049](https://linux-hardware.org/?probe=31ae8b8049) | Jul 08, 2021 |
| SLIMBOOK      | PROX14-AMD                  | [805eeee81b](https://linux-hardware.org/?probe=805eeee81b) | Jul 08, 2021 |
| Lenovo        | ThinkPad T440 20B60061MD    | [7207e6aa0f](https://linux-hardware.org/?probe=7207e6aa0f) | Jul 08, 2021 |
| Lenovo        | ThinkPad T430 2344BZU       | [27d628b154](https://linux-hardware.org/?probe=27d628b154) | Jul 07, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | [c431ee437b](https://linux-hardware.org/?probe=c431ee437b) | Jul 07, 2021 |
| Lenovo        | ThinkPad T440 20B7S1N809    | [b9ab49e917](https://linux-hardware.org/?probe=b9ab49e917) | Jul 07, 2021 |
| HP            | EliteBook 8470p             | [505684a737](https://linux-hardware.org/?probe=505684a737) | Jul 07, 2021 |
| MSI           | GL62M 7RDX                  | [83baf2f2d5](https://linux-hardware.org/?probe=83baf2f2d5) | Jul 07, 2021 |
| MSI           | GL62M 7RDX                  | [7f782b90e4](https://linux-hardware.org/?probe=7f782b90e4) | Jul 06, 2021 |
| AVITA         | NS13A2                      | [8ccfb136b0](https://linux-hardware.org/?probe=8ccfb136b0) | Jul 04, 2021 |
| Dell          | Inspiron 1545               | [602a2bc224](https://linux-hardware.org/?probe=602a2bc224) | Jul 04, 2021 |
| Acer          | Aspire A515-54G             | [f926fbd545](https://linux-hardware.org/?probe=f926fbd545) | Jul 04, 2021 |
| HP            | EliteBook 850 G6            | [27b614c70e](https://linux-hardware.org/?probe=27b614c70e) | Jul 04, 2021 |
| Acer          | Aspire V3-731               | [818a0706cf](https://linux-hardware.org/?probe=818a0706cf) | Jul 04, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [41837d1bed](https://linux-hardware.org/?probe=41837d1bed) | Jul 04, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [aea8fb485e](https://linux-hardware.org/?probe=aea8fb485e) | Jul 04, 2021 |
| SANTECH       | PCX0DX                      | [fee2d7443a](https://linux-hardware.org/?probe=fee2d7443a) | Jul 03, 2021 |
| Lenovo        | ThinkPad T490 20N2S04200    | [331968a8d9](https://linux-hardware.org/?probe=331968a8d9) | Jul 03, 2021 |
| Lenovo        | ThinkPad T490 20N2S04200    | [59e9a66bff](https://linux-hardware.org/?probe=59e9a66bff) | Jul 03, 2021 |
| Lenovo        | ThinkPad T490 20N2S04200    | [e20b747527](https://linux-hardware.org/?probe=e20b747527) | Jul 03, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [f4778083d9](https://linux-hardware.org/?probe=f4778083d9) | Jul 02, 2021 |
| ASUSTek       | ROG Strix G731GW_G731GW     | [fc6a98826e](https://linux-hardware.org/?probe=fc6a98826e) | Jul 02, 2021 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [bdba392a3f](https://linux-hardware.org/?probe=bdba392a3f) | Jul 02, 2021 |
| Google        | Helios                      | [644f9f9062](https://linux-hardware.org/?probe=644f9f9062) | Jul 02, 2021 |
| Acer          | Aspire A315-41              | [67c143c435](https://linux-hardware.org/?probe=67c143c435) | Jul 01, 2021 |
| Acer          | TravelMate P633-M           | [1c0b704e2f](https://linux-hardware.org/?probe=1c0b704e2f) | Jul 01, 2021 |
| Packard Be... | EasyNote TE69BM             | [b1113dfd2c](https://linux-hardware.org/?probe=b1113dfd2c) | Jul 01, 2021 |
| Packard Be... | EasyNote TE69BM             | [86c12f4dc4](https://linux-hardware.org/?probe=86c12f4dc4) | Jul 01, 2021 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [a7410bf8c7](https://linux-hardware.org/?probe=a7410bf8c7) | Jul 01, 2021 |
| Lenovo        | ThinkPad T480 20L50067US    | [987d9489d4](https://linux-hardware.org/?probe=987d9489d4) | Jul 01, 2021 |
| Dell          | XPS 13 7390                 | [a40bb01515](https://linux-hardware.org/?probe=a40bb01515) | Jun 30, 2021 |
| ASUSTek       | X751LJ                      | [8a67af6b70](https://linux-hardware.org/?probe=8a67af6b70) | Jun 30, 2021 |
| Intel Clie... | LAPBC710                    | [93690f8eec](https://linux-hardware.org/?probe=93690f8eec) | Jun 30, 2021 |
| Apple         | MacBookPro16,1              | [40c080965e](https://linux-hardware.org/?probe=40c080965e) | Jun 29, 2021 |
| Dell          | Inspiron 5583               | [a1f0396c8e](https://linux-hardware.org/?probe=a1f0396c8e) | Jun 29, 2021 |
| System76      | Oryx Pro                    | [7ccf59ae28](https://linux-hardware.org/?probe=7ccf59ae28) | Jun 28, 2021 |
| ASUSTek       | X751LJ                      | [d4314245a2](https://linux-hardware.org/?probe=d4314245a2) | Jun 28, 2021 |
| Dell          | Latitude E5470              | [a4c33f1b5b](https://linux-hardware.org/?probe=a4c33f1b5b) | Jun 28, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | [39f7878023](https://linux-hardware.org/?probe=39f7878023) | Jun 28, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y2... | [6f712e13a8](https://linux-hardware.org/?probe=6f712e13a8) | Jun 27, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [306b388a14](https://linux-hardware.org/?probe=306b388a14) | Jun 27, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [39f8c7f885](https://linux-hardware.org/?probe=39f8c7f885) | Jun 26, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | [2ebba9b2b1](https://linux-hardware.org/?probe=2ebba9b2b1) | Jun 25, 2021 |
| Samsung       | RV411/RV511/E3511/S3511     | [48f732d759](https://linux-hardware.org/?probe=48f732d759) | Jun 23, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [b7f67f4e5c](https://linux-hardware.org/?probe=b7f67f4e5c) | Jun 23, 2021 |
| MSI           | GF65 Thin 10UE              | [af8d7a6b6f](https://linux-hardware.org/?probe=af8d7a6b6f) | Jun 22, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [cee538b2a6](https://linux-hardware.org/?probe=cee538b2a6) | Jun 20, 2021 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [8ed58d00f1](https://linux-hardware.org/?probe=8ed58d00f1) | Jun 19, 2021 |
| Acer          | Aspire A314-22              | [4baa5a5a3c](https://linux-hardware.org/?probe=4baa5a5a3c) | Jun 19, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [32c83da9dd](https://linux-hardware.org/?probe=32c83da9dd) | Jun 19, 2021 |
| Lenovo        | ThinkPad X220 4291LR8       | [69031eda12](https://linux-hardware.org/?probe=69031eda12) | Jun 18, 2021 |
| Lenovo        | ThinkPad X220 4291LR8       | [d7b3c8fc20](https://linux-hardware.org/?probe=d7b3c8fc20) | Jun 18, 2021 |
| Acer          | Aspire E5-574G              | [5263e616d8](https://linux-hardware.org/?probe=5263e616d8) | Jun 17, 2021 |
| MSI           | GL75 Leopard 10SER          | [0e182c2523](https://linux-hardware.org/?probe=0e182c2523) | Jun 17, 2021 |
| Lenovo        | ThinkPad T490 20N2CT01WW    | [93d574c42b](https://linux-hardware.org/?probe=93d574c42b) | Jun 16, 2021 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [10938ced47](https://linux-hardware.org/?probe=10938ced47) | Jun 16, 2021 |
| Dell          | XPS 13 9370                 | [7e7246b2ae](https://linux-hardware.org/?probe=7e7246b2ae) | Jun 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [21fac9393e](https://linux-hardware.org/?probe=21fac9393e) | Jun 15, 2021 |
| Lenovo        | ThinkPad T460s 20F90043G... | [4ea3c64329](https://linux-hardware.org/?probe=4ea3c64329) | Jun 14, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [fc5d0440be](https://linux-hardware.org/?probe=fc5d0440be) | Jun 14, 2021 |
| Acer          | Aspire A715-71G             | [cb59081351](https://linux-hardware.org/?probe=cb59081351) | Jun 14, 2021 |
| Lenovo        | Yoga 14sARH 2021 82LB       | [54128eb7cf](https://linux-hardware.org/?probe=54128eb7cf) | Jun 13, 2021 |
| Lenovo        | Yoga 14sARH 2021 82LB       | [c178189191](https://linux-hardware.org/?probe=c178189191) | Jun 12, 2021 |
| HP            | Pavilion dv5                | [d9f46a83a2](https://linux-hardware.org/?probe=d9f46a83a2) | Jun 12, 2021 |
| Timi          | RedmiBook 13 R              | [ce648ba480](https://linux-hardware.org/?probe=ce648ba480) | Jun 12, 2021 |
| Dell          | Precision M4800             | [298694c222](https://linux-hardware.org/?probe=298694c222) | Jun 12, 2021 |
| HP            | Laptop 15-bw0xx             | [e8ea42bf4b](https://linux-hardware.org/?probe=e8ea42bf4b) | Jun 11, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [0dde07f321](https://linux-hardware.org/?probe=0dde07f321) | Jun 11, 2021 |
| HP            | Pavilion Laptop 13-an0xx... | [2da9390d91](https://linux-hardware.org/?probe=2da9390d91) | Jun 11, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 80X4     | [841583a190](https://linux-hardware.org/?probe=841583a190) | Jun 11, 2021 |
| Schenker      | XMG CORE (REN/E21)          | [e9a8a12e60](https://linux-hardware.org/?probe=e9a8a12e60) | Jun 10, 2021 |
| HP            | Laptop 14-dk0xxx            | [04a08f235b](https://linux-hardware.org/?probe=04a08f235b) | Jun 10, 2021 |
| Acer          | Aspire A715-71G             | [961bf4c8e2](https://linux-hardware.org/?probe=961bf4c8e2) | Jun 10, 2021 |
| HP            | Pavilion Laptop 13-an0xx... | [c33921449f](https://linux-hardware.org/?probe=c33921449f) | Jun 10, 2021 |
| Acer          | Aspire V3-372               | [cef1a574e6](https://linux-hardware.org/?probe=cef1a574e6) | Jun 10, 2021 |
| Acer          | Aspire V3-372               | [74c08d970a](https://linux-hardware.org/?probe=74c08d970a) | Jun 10, 2021 |
| Acer          | Swift SF314-52              | [af097bb3da](https://linux-hardware.org/?probe=af097bb3da) | Jun 09, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 80X4     | [b20669e907](https://linux-hardware.org/?probe=b20669e907) | Jun 08, 2021 |
| HP            | Laptop 14-cm0xxx            | [28fb1b0135](https://linux-hardware.org/?probe=28fb1b0135) | Jun 08, 2021 |
| Sony          | SVS13112FXB                 | [9ce22cf208](https://linux-hardware.org/?probe=9ce22cf208) | Jun 08, 2021 |
| Lenovo        | ThinkPad X240 20AMS1RR0L    | [1a1a97017a](https://linux-hardware.org/?probe=1a1a97017a) | Jun 08, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [45b678cc45](https://linux-hardware.org/?probe=45b678cc45) | Jun 07, 2021 |
| Acer          | Extensa 5635ZG              | [540d6fca8e](https://linux-hardware.org/?probe=540d6fca8e) | Jun 07, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [6824b735cb](https://linux-hardware.org/?probe=6824b735cb) | Jun 07, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [3dbcf31286](https://linux-hardware.org/?probe=3dbcf31286) | Jun 07, 2021 |
| HP            | ProBook 430 G7              | [f29e92258f](https://linux-hardware.org/?probe=f29e92258f) | Jun 07, 2021 |
| HP            | ProBook 430 G7              | [c62e2bfa56](https://linux-hardware.org/?probe=c62e2bfa56) | Jun 07, 2021 |
| Samsung       | 900X3G                      | [2ce9dac4c3](https://linux-hardware.org/?probe=2ce9dac4c3) | Jun 06, 2021 |
| Samsung       | 900X3G                      | [1f7e3d2301](https://linux-hardware.org/?probe=1f7e3d2301) | Jun 06, 2021 |
| ASUSTek       | N53SV                       | [28e717743a](https://linux-hardware.org/?probe=28e717743a) | Jun 06, 2021 |
| Dell          | Precision M4800             | [67fb08d285](https://linux-hardware.org/?probe=67fb08d285) | Jun 06, 2021 |
| Dell          | Precision M4800             | [c72664a2f4](https://linux-hardware.org/?probe=c72664a2f4) | Jun 06, 2021 |
| HP            | 250 G6 Notebook PC          | [9da7a2a7e4](https://linux-hardware.org/?probe=9da7a2a7e4) | Jun 06, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [63b5d9a81a](https://linux-hardware.org/?probe=63b5d9a81a) | Jun 05, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [56308999d2](https://linux-hardware.org/?probe=56308999d2) | Jun 05, 2021 |
| Lenovo        | ThinkPad T420 4236PFG       | [fa5abfccf8](https://linux-hardware.org/?probe=fa5abfccf8) | Jun 04, 2021 |
| Dell          | Inspiron 3583               | [08dbd93be1](https://linux-hardware.org/?probe=08dbd93be1) | Jun 04, 2021 |
| Acer          | Nitro AN515-43              | [4b725ca633](https://linux-hardware.org/?probe=4b725ca633) | Jun 04, 2021 |
| Acer          | Nitro AN515-43              | [3ded8fe948](https://linux-hardware.org/?probe=3ded8fe948) | Jun 04, 2021 |
| Dell          | XPS 15 9550                 | [a06f0af7cd](https://linux-hardware.org/?probe=a06f0af7cd) | Jun 04, 2021 |
| Lenovo        | ThinkPad T440p 20AWA0850... | [8390e1030c](https://linux-hardware.org/?probe=8390e1030c) | Jun 04, 2021 |
| Positivo      | S14CT01                     | [ca501443b2](https://linux-hardware.org/?probe=ca501443b2) | Jun 03, 2021 |
| ASUSTek       | ROG Zephyrus GX550LXS_GX... | [5d36f4d5d1](https://linux-hardware.org/?probe=5d36f4d5d1) | Jun 03, 2021 |
| Acer          | Aspire E5-571               | [31a46644a6](https://linux-hardware.org/?probe=31a46644a6) | Jun 03, 2021 |
| HP            | Laptop 15-da0xxx            | [60b8f556d5](https://linux-hardware.org/?probe=60b8f556d5) | Jun 03, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [1fa6a4756a](https://linux-hardware.org/?probe=1fa6a4756a) | Jun 02, 2021 |
| Acer          | Nitro AN515-42              | [28aadacd07](https://linux-hardware.org/?probe=28aadacd07) | Jun 02, 2021 |
| HP            | 250 G6 Notebook PC          | [f569a1ada7](https://linux-hardware.org/?probe=f569a1ada7) | Jun 01, 2021 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [573bcd314d](https://linux-hardware.org/?probe=573bcd314d) | Jun 01, 2021 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [73aad972ad](https://linux-hardware.org/?probe=73aad972ad) | May 31, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [161b42524b](https://linux-hardware.org/?probe=161b42524b) | May 31, 2021 |
| Hyperbook     | Z15 Zen                     | [60d8a6b854](https://linux-hardware.org/?probe=60d8a6b854) | May 31, 2021 |
| Lenovo        | ThinkPad T460s 20F9003UP... | [79d4310531](https://linux-hardware.org/?probe=79d4310531) | May 31, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [cb9d7d7035](https://linux-hardware.org/?probe=cb9d7d7035) | May 30, 2021 |
| Apple         | MacBookAir7,2               | [c0ed6370c5](https://linux-hardware.org/?probe=c0ed6370c5) | May 30, 2021 |
| Dell          | Inspiron 17-7778            | [f0f4829a9a](https://linux-hardware.org/?probe=f0f4829a9a) | May 29, 2021 |
| Dell          | Inspiron 17-7778            | [ee6e030924](https://linux-hardware.org/?probe=ee6e030924) | May 29, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [c0c2cadff1](https://linux-hardware.org/?probe=c0c2cadff1) | May 29, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [b63698a4af](https://linux-hardware.org/?probe=b63698a4af) | May 29, 2021 |
| Samsung       | RV411/RV511/E3511/S3511     | [8bdfad6e5a](https://linux-hardware.org/?probe=8bdfad6e5a) | May 27, 2021 |
| Medion        | S4216                       | [a70d378dd0](https://linux-hardware.org/?probe=a70d378dd0) | May 27, 2021 |
| Dell          | Inspiron 5567               | [904017303b](https://linux-hardware.org/?probe=904017303b) | May 26, 2021 |
| ASUSTek       | UX430UAR                    | [da74cc2e60](https://linux-hardware.org/?probe=da74cc2e60) | May 26, 2021 |
| ASUSTek       | UX430UAR                    | [b842a7432b](https://linux-hardware.org/?probe=b842a7432b) | May 26, 2021 |
| Eluktronic... | THINN-15                    | [69510c22f1](https://linux-hardware.org/?probe=69510c22f1) | May 25, 2021 |
| Dell          | Inspiron N5110              | [45bcac0d81](https://linux-hardware.org/?probe=45bcac0d81) | May 25, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [7a8bb7eb07](https://linux-hardware.org/?probe=7a8bb7eb07) | May 24, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [dc5ce4c601](https://linux-hardware.org/?probe=dc5ce4c601) | May 24, 2021 |
| Samsung       | 300E5M/300E5L               | [2bcd802792](https://linux-hardware.org/?probe=2bcd802792) | May 24, 2021 |
| HP            | OMEN by Laptop 17-cb0xxx    | [cf1becc8c4](https://linux-hardware.org/?probe=cf1becc8c4) | May 24, 2021 |
| HP            | kip                         | [63eca41cd1](https://linux-hardware.org/?probe=63eca41cd1) | May 24, 2021 |
| Apple         | MacBookPro16,1              | [2bddf8b98a](https://linux-hardware.org/?probe=2bddf8b98a) | May 23, 2021 |
| HP            | EliteBook Revolve 810 G3    | [e0068ae9b7](https://linux-hardware.org/?probe=e0068ae9b7) | May 23, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [c9a0b1991a](https://linux-hardware.org/?probe=c9a0b1991a) | May 21, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [398efe5207](https://linux-hardware.org/?probe=398efe5207) | May 21, 2021 |
| MSI           | GL62 6QF                    | [de64f90482](https://linux-hardware.org/?probe=de64f90482) | May 21, 2021 |
| Lenovo        | ThinkBook 13s G2 ARE 20W... | [99ec307c23](https://linux-hardware.org/?probe=99ec307c23) | May 19, 2021 |
| Lenovo        | ThinkPad L380 20M50013UK    | [65dc1ecf31](https://linux-hardware.org/?probe=65dc1ecf31) | May 19, 2021 |
| ASUSTek       | GL702VMK                    | [142a31af57](https://linux-hardware.org/?probe=142a31af57) | May 19, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [b6cac26930](https://linux-hardware.org/?probe=b6cac26930) | May 19, 2021 |
| Apple         | MacBookPro15,1              | [891913ceec](https://linux-hardware.org/?probe=891913ceec) | May 19, 2021 |
| Apple         | MacBookPro9,2               | [d82057afa6](https://linux-hardware.org/?probe=d82057afa6) | May 19, 2021 |
| 51nb          | X210                        | [1805d2ed4d](https://linux-hardware.org/?probe=1805d2ed4d) | May 19, 2021 |
| ASUSTek       | TP300LD                     | [56d2168d65](https://linux-hardware.org/?probe=56d2168d65) | May 19, 2021 |
| Samsung       | 700Z3C/700Z5C               | [3b6226081b](https://linux-hardware.org/?probe=3b6226081b) | May 19, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [1abefab68f](https://linux-hardware.org/?probe=1abefab68f) | May 19, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [c4ea8f1bab](https://linux-hardware.org/?probe=c4ea8f1bab) | May 19, 2021 |
| Acer          | Aspire 8950G                | [7955f23581](https://linux-hardware.org/?probe=7955f23581) | May 18, 2021 |
| ASUSTek       | Strix 17 GL703GE            | [1cba3fc4fc](https://linux-hardware.org/?probe=1cba3fc4fc) | May 17, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [a5c4698e61](https://linux-hardware.org/?probe=a5c4698e61) | May 17, 2021 |
| Apple         | MacBook4,1                  | [e31dde7e74](https://linux-hardware.org/?probe=e31dde7e74) | May 16, 2021 |
| Lenovo        | ThinkPad T480 20L5S01J00    | [e8e2bd3b06](https://linux-hardware.org/?probe=e8e2bd3b06) | May 15, 2021 |
| Apple         | MacBook4,1                  | [227997bfb2](https://linux-hardware.org/?probe=227997bfb2) | May 15, 2021 |
| HP            | Pavilion Sleekbook 15 PC    | [6778794f42](https://linux-hardware.org/?probe=6778794f42) | May 15, 2021 |
| Acer          | Predator PH315-52           | [0afa1e0fdf](https://linux-hardware.org/?probe=0afa1e0fdf) | May 14, 2021 |
| HP            | 15 Notebook PC              | [52e14efd44](https://linux-hardware.org/?probe=52e14efd44) | May 14, 2021 |
| HP            | OMEN by Laptop              | [43907153c2](https://linux-hardware.org/?probe=43907153c2) | May 13, 2021 |
| Lenovo        | Unknown                     | [d553fa0eee](https://linux-hardware.org/?probe=d553fa0eee) | May 12, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [c943a65ac4](https://linux-hardware.org/?probe=c943a65ac4) | May 11, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [bef320c4be](https://linux-hardware.org/?probe=bef320c4be) | May 11, 2021 |
| Dell          | Latitude E5470              | [9ed0c349f9](https://linux-hardware.org/?probe=9ed0c349f9) | May 10, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [0d98994072](https://linux-hardware.org/?probe=0d98994072) | May 10, 2021 |
| HP            | Laptop 17-ak0xx             | [b2207b19c0](https://linux-hardware.org/?probe=b2207b19c0) | May 09, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X40... | [085d40790e](https://linux-hardware.org/?probe=085d40790e) | May 09, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [a91b62859a](https://linux-hardware.org/?probe=a91b62859a) | May 09, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | [fbc432b3fb](https://linux-hardware.org/?probe=fbc432b3fb) | May 08, 2021 |
| HP            | ProBook 470 G2              | [fc85d1a891](https://linux-hardware.org/?probe=fc85d1a891) | May 08, 2021 |
| HP            | OMEN by Laptop 17-cb0xxx    | [f1f8997736](https://linux-hardware.org/?probe=f1f8997736) | May 07, 2021 |
| HP            | 250 G6 Notebook PC          | [0193e32ca2](https://linux-hardware.org/?probe=0193e32ca2) | May 07, 2021 |
| Dell          | XPS 13 9310                 | [8ffcb6811e](https://linux-hardware.org/?probe=8ffcb6811e) | May 07, 2021 |
| HP            | Pavilion g6                 | [225644d3a3](https://linux-hardware.org/?probe=225644d3a3) | May 07, 2021 |
| HP            | 250 G6 Notebook PC          | [cee69d2935](https://linux-hardware.org/?probe=cee69d2935) | May 07, 2021 |
| Hyperbook     | Z15 Zen                     | [baf0379a0a](https://linux-hardware.org/?probe=baf0379a0a) | May 07, 2021 |
| Lenovo        | ThinkPad T420 42363Y5       | [5a93fb1b0b](https://linux-hardware.org/?probe=5a93fb1b0b) | May 07, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [de14cb7c23](https://linux-hardware.org/?probe=de14cb7c23) | May 06, 2021 |
| Unknown       | Unknown                     | [67388a630f](https://linux-hardware.org/?probe=67388a630f) | May 06, 2021 |
| Lenovo        | ThinkPad W540 20BG001KUK    | [8dad1422da](https://linux-hardware.org/?probe=8dad1422da) | May 06, 2021 |
| ASUSTek       | X450MD                      | [b77e4abcd8](https://linux-hardware.org/?probe=b77e4abcd8) | May 06, 2021 |
| ASUSTek       | TP300LD                     | [cb877f7f21](https://linux-hardware.org/?probe=cb877f7f21) | May 05, 2021 |
| LG Electro... | R590-X.ARU4BT               | [ab5e5c2584](https://linux-hardware.org/?probe=ab5e5c2584) | May 05, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U5S... | [fdbc72ed13](https://linux-hardware.org/?probe=fdbc72ed13) | May 05, 2021 |
| Acer          | Aspire A515-51G             | [ab92d875c3](https://linux-hardware.org/?probe=ab92d875c3) | May 04, 2021 |
| Acer          | Aspire A515-51              | [ea1d5762db](https://linux-hardware.org/?probe=ea1d5762db) | May 04, 2021 |
| Lenovo        | G710 20252                  | [e77f1af187](https://linux-hardware.org/?probe=e77f1af187) | May 04, 2021 |
| Lenovo        | ThinkPad E480 20KN000UCD    | [f665cfa22e](https://linux-hardware.org/?probe=f665cfa22e) | May 04, 2021 |
| Lenovo        | ThinkPad E480 20KN000UCD    | [6309138445](https://linux-hardware.org/?probe=6309138445) | May 04, 2021 |
| Lenovo        | ThinkPad T430 2349N7G       | [58a90d5786](https://linux-hardware.org/?probe=58a90d5786) | May 03, 2021 |
| Hyperbook     | Z15 Zen                     | [30ecd899c0](https://linux-hardware.org/?probe=30ecd899c0) | May 03, 2021 |
| Lenovo        | ThinkPad T440s 20ARS3B00... | [fa546522c1](https://linux-hardware.org/?probe=fa546522c1) | May 02, 2021 |
| Toshiba       | Satellite L775-11K          | [4dd28f3705](https://linux-hardware.org/?probe=4dd28f3705) | May 01, 2021 |
| HP            | ElitePad 1000 G2            | [0015c6d1ec](https://linux-hardware.org/?probe=0015c6d1ec) | May 01, 2021 |
| ASUSTek       | K501UX                      | [a940987f89](https://linux-hardware.org/?probe=a940987f89) | May 01, 2021 |
| ASUSTek       | K501UX                      | [c37b2264b2](https://linux-hardware.org/?probe=c37b2264b2) | May 01, 2021 |
| Lenovo        | ThinkPad T490 20N2003NUS    | [52792d3773](https://linux-hardware.org/?probe=52792d3773) | May 01, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | [473f17b0f1](https://linux-hardware.org/?probe=473f17b0f1) | May 01, 2021 |
| Dell          | Precision 7540              | [93fae8cdd3](https://linux-hardware.org/?probe=93fae8cdd3) | May 01, 2021 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [1a6e48b6a6](https://linux-hardware.org/?probe=1a6e48b6a6) | Apr 29, 2021 |
| Lenovo        | ThinkPad P50 20EN0005PG     | [b3a280cc6b](https://linux-hardware.org/?probe=b3a280cc6b) | Apr 29, 2021 |
| Acer          | Aspire A115-31              | [897a4d5aa5](https://linux-hardware.org/?probe=897a4d5aa5) | Apr 28, 2021 |
| Unknown       | Unknown                     | [ab017a3754](https://linux-hardware.org/?probe=ab017a3754) | Apr 28, 2021 |
| ASUSTek       | X555LF                      | [7cd9ae11e6](https://linux-hardware.org/?probe=7cd9ae11e6) | Apr 28, 2021 |
| ASUSTek       | X555LF                      | [c1ba03bd7c](https://linux-hardware.org/?probe=c1ba03bd7c) | Apr 28, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | [84f31a5fd7](https://linux-hardware.org/?probe=84f31a5fd7) | Apr 28, 2021 |
| HP            | EliteBook 820 G3            | [26c2c579ee](https://linux-hardware.org/?probe=26c2c579ee) | Apr 28, 2021 |
| Dell          | Latitude 5401               | [cd8363b187](https://linux-hardware.org/?probe=cd8363b187) | Apr 27, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [209887e993](https://linux-hardware.org/?probe=209887e993) | Apr 27, 2021 |
| Lenovo        | ThinkPad T495s 20QJ001MG... | [1363a8e68d](https://linux-hardware.org/?probe=1363a8e68d) | Apr 27, 2021 |
| Lenovo        | ThinkPad T495s 20QJ001MG... | [aede883551](https://linux-hardware.org/?probe=aede883551) | Apr 27, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | [bb346e5b0c](https://linux-hardware.org/?probe=bb346e5b0c) | Apr 26, 2021 |
| SLIMBOOK      | PROX14-AMD                  | [ddb2ebb6b8](https://linux-hardware.org/?probe=ddb2ebb6b8) | Apr 26, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | [8117a3bdde](https://linux-hardware.org/?probe=8117a3bdde) | Apr 26, 2021 |
| Lenovo        | ThinkPad P53 20QN0034MH     | [bcb2272cf0](https://linux-hardware.org/?probe=bcb2272cf0) | Apr 25, 2021 |
| ASUSTek       | GL503VD                     | [3befdf805e](https://linux-hardware.org/?probe=3befdf805e) | Apr 25, 2021 |
| ASUSTek       | UX32LN                      | [503a837fd2](https://linux-hardware.org/?probe=503a837fd2) | Apr 25, 2021 |
| Samsung       | 300E5M/300E5L               | [2386be709a](https://linux-hardware.org/?probe=2386be709a) | Apr 24, 2021 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | [26133ce35a](https://linux-hardware.org/?probe=26133ce35a) | Apr 24, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [62a9d02812](https://linux-hardware.org/?probe=62a9d02812) | Apr 23, 2021 |
| Google        | Lars                        | [e37c5680c3](https://linux-hardware.org/?probe=e37c5680c3) | Apr 23, 2021 |
| Google        | Lars                        | [d2f13246b1](https://linux-hardware.org/?probe=d2f13246b1) | Apr 23, 2021 |
| Dell          | XPS 13 9350                 | [cf2f86441f](https://linux-hardware.org/?probe=cf2f86441f) | Apr 22, 2021 |
| Alienware     | 17 R4                       | [9905a07e17](https://linux-hardware.org/?probe=9905a07e17) | Apr 21, 2021 |
| Dell          | Latitude E6540              | [522d36a07e](https://linux-hardware.org/?probe=522d36a07e) | Apr 21, 2021 |
| Dell          | Latitude E6540              | [3c76496221](https://linux-hardware.org/?probe=3c76496221) | Apr 21, 2021 |
| HP            | ProBook 640 G2              | [cc4b216807](https://linux-hardware.org/?probe=cc4b216807) | Apr 21, 2021 |
| HUAWEI        | HN-WX9X                     | [426bcb28b3](https://linux-hardware.org/?probe=426bcb28b3) | Apr 21, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | [bd14a696eb](https://linux-hardware.org/?probe=bd14a696eb) | Apr 20, 2021 |
| HP            | ProBook 440 G7              | [33df615e9c](https://linux-hardware.org/?probe=33df615e9c) | Apr 20, 2021 |
| Lenovo        | ThinkPad T490s 20NXCTO1W... | [92fe8bf812](https://linux-hardware.org/?probe=92fe8bf812) | Apr 20, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [90ba83bead](https://linux-hardware.org/?probe=90ba83bead) | Apr 20, 2021 |
| Dell          | Vostro 5568                 | [c163b3d990](https://linux-hardware.org/?probe=c163b3d990) | Apr 19, 2021 |
| Lenovo        | IdeaPad Y510P 20217         | [846845746f](https://linux-hardware.org/?probe=846845746f) | Apr 19, 2021 |
| HP            | ProBook 640 G2              | [9b79c42f94](https://linux-hardware.org/?probe=9b79c42f94) | Apr 19, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [2e1606428e](https://linux-hardware.org/?probe=2e1606428e) | Apr 19, 2021 |
| Toshiba       | Satellite L55-C             | [3ddd1f04d9](https://linux-hardware.org/?probe=3ddd1f04d9) | Apr 19, 2021 |
| Dell          | XPS 15 9500                 | [7d95a882b3](https://linux-hardware.org/?probe=7d95a882b3) | Apr 19, 2021 |
| Lenovo        | ThinkPad T440p 20AWS0DU0... | [998919a455](https://linux-hardware.org/?probe=998919a455) | Apr 18, 2021 |
| HP            | ENVY Notebook               | [756fd70b35](https://linux-hardware.org/?probe=756fd70b35) | Apr 18, 2021 |
| Toshiba       | Satellite L55-C             | [a42183751a](https://linux-hardware.org/?probe=a42183751a) | Apr 18, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [5d66639b00](https://linux-hardware.org/?probe=5d66639b00) | Apr 17, 2021 |
| HP            | EliteBook 835 G7 Noteboo... | [ca7d831008](https://linux-hardware.org/?probe=ca7d831008) | Apr 17, 2021 |
| Lenovo        | ThinkPad 20QJ000DRT         | [c3d38b2bcb](https://linux-hardware.org/?probe=c3d38b2bcb) | Apr 17, 2021 |
| HP            | Pavilion dv6                | [1f7c25614f](https://linux-hardware.org/?probe=1f7c25614f) | Apr 17, 2021 |
| HP            | Pavilion dv6                | [50f5e0cc11](https://linux-hardware.org/?probe=50f5e0cc11) | Apr 17, 2021 |
| Lenovo        | ThinkPad T430 2349OB6       | [7a6f541470](https://linux-hardware.org/?probe=7a6f541470) | Apr 16, 2021 |
| Lenovo        | ThinkPad T430 2349OB6       | [e22d3efcdd](https://linux-hardware.org/?probe=e22d3efcdd) | Apr 16, 2021 |
| Acer          | AOD260                      | [97f6b98307](https://linux-hardware.org/?probe=97f6b98307) | Apr 16, 2021 |
| Dell          | XPS 15 9500                 | [618664469a](https://linux-hardware.org/?probe=618664469a) | Apr 16, 2021 |
| Positivo      | CHT14B                      | [98a1d3fba5](https://linux-hardware.org/?probe=98a1d3fba5) | Apr 15, 2021 |
| HP            | ProBook 445 G6              | [520083c016](https://linux-hardware.org/?probe=520083c016) | Apr 14, 2021 |
| ASUSTek       | TUF Gaming FX505DY_TUF50... | [be7a218721](https://linux-hardware.org/?probe=be7a218721) | Apr 12, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [12fb9fd662](https://linux-hardware.org/?probe=12fb9fd662) | Apr 12, 2021 |
| HP            | Elite x2 1012 G1            | [00fb0f909e](https://linux-hardware.org/?probe=00fb0f909e) | Apr 11, 2021 |
| HP            | Elite x2 1012 G1            | [6b0bb3d5d4](https://linux-hardware.org/?probe=6b0bb3d5d4) | Apr 11, 2021 |
| Acer          | Aspire 5553G                | [95a2c5cc20](https://linux-hardware.org/?probe=95a2c5cc20) | Apr 11, 2021 |
| Lenovo        | ThinkPad T410s 2912B99      | [cce75356c4](https://linux-hardware.org/?probe=cce75356c4) | Apr 11, 2021 |
| Dell          | XPS 13 7390                 | [94d4928b3c](https://linux-hardware.org/?probe=94d4928b3c) | Apr 11, 2021 |
| Dell          | Inspiron N5050              | [f34dd55177](https://linux-hardware.org/?probe=f34dd55177) | Apr 11, 2021 |
| Dell          | Inspiron N5050              | [b408f5c9d6](https://linux-hardware.org/?probe=b408f5c9d6) | Apr 11, 2021 |
| Lenovo        | G710 20252                  | [ee2a454fb6](https://linux-hardware.org/?probe=ee2a454fb6) | Apr 11, 2021 |
| Maibenben     | MaiBook M                   | [6db19936ac](https://linux-hardware.org/?probe=6db19936ac) | Apr 10, 2021 |
| Acer          | Aspire E5-575G              | [c3486f6056](https://linux-hardware.org/?probe=c3486f6056) | Apr 10, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | [b8af821993](https://linux-hardware.org/?probe=b8af821993) | Apr 10, 2021 |
| Acer          | Nitro AN515-44              | [19f0a0eeed](https://linux-hardware.org/?probe=19f0a0eeed) | Apr 10, 2021 |
| HP            | EliteBook 835 G7 Noteboo... | [7b80b7da71](https://linux-hardware.org/?probe=7b80b7da71) | Apr 10, 2021 |
| Acer          | TravelMate 7750G            | [1790f79449](https://linux-hardware.org/?probe=1790f79449) | Apr 10, 2021 |
| Lenovo        | ThinkPad P53 20QNCTO1WW     | [932694448b](https://linux-hardware.org/?probe=932694448b) | Apr 09, 2021 |
| HP            | EliteBook 8470p             | [ad6b18f63a](https://linux-hardware.org/?probe=ad6b18f63a) | Apr 09, 2021 |
| HP            | EliteBook 835 G7 Noteboo... | [69bcee1aae](https://linux-hardware.org/?probe=69bcee1aae) | Apr 09, 2021 |
| ASUSTek       | X542UQ                      | [5b0c97ade1](https://linux-hardware.org/?probe=5b0c97ade1) | Apr 09, 2021 |
| HP            | EliteBook 840 G1            | [c6fc94dd62](https://linux-hardware.org/?probe=c6fc94dd62) | Apr 08, 2021 |
| Dell          | XPS 15 9500                 | [ddfdb5ea88](https://linux-hardware.org/?probe=ddfdb5ea88) | Apr 08, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [2926c6ad2e](https://linux-hardware.org/?probe=2926c6ad2e) | Apr 07, 2021 |
| Dell          | XPS 13 9370                 | [1f83042804](https://linux-hardware.org/?probe=1f83042804) | Apr 07, 2021 |
| Lenovo        | V330-14IKB 81B0             | [729cbf17a4](https://linux-hardware.org/?probe=729cbf17a4) | Apr 07, 2021 |
| Lenovo        | ThinkPad T430 2351BL9       | [767376e1bf](https://linux-hardware.org/?probe=767376e1bf) | Apr 06, 2021 |
| Lenovo        | ThinkPad T430 2351BL9       | [e42589938f](https://linux-hardware.org/?probe=e42589938f) | Apr 06, 2021 |
| Dell          | XPS 15 9570                 | [ae7370813d](https://linux-hardware.org/?probe=ae7370813d) | Apr 05, 2021 |
| Dell          | XPS 15 9570                 | [7d0cde3b09](https://linux-hardware.org/?probe=7d0cde3b09) | Apr 05, 2021 |
| ASUSTek       | ASUS EXPERTBOOK B9400CEA... | [6631550f57](https://linux-hardware.org/?probe=6631550f57) | Apr 04, 2021 |
| HP            | Pavilion g6                 | [0b60251ab6](https://linux-hardware.org/?probe=0b60251ab6) | Apr 04, 2021 |
| HP            | Pavilion Laptop 15-ck069... | [7ba5010911](https://linux-hardware.org/?probe=7ba5010911) | Apr 04, 2021 |
| HP            | Pavilion Laptop 15-ck069... | [647ed2511e](https://linux-hardware.org/?probe=647ed2511e) | Apr 04, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [e8f955c2e7](https://linux-hardware.org/?probe=e8f955c2e7) | Apr 04, 2021 |
| Acer          | Aspire E5-571               | [7c881fe5f7](https://linux-hardware.org/?probe=7c881fe5f7) | Apr 04, 2021 |
| GEO           | GeoBook3                    | [4d6333682f](https://linux-hardware.org/?probe=4d6333682f) | Apr 04, 2021 |
| Lenovo        | ThinkPad T440p 20AWS0DU0... | [8d5f33367e](https://linux-hardware.org/?probe=8d5f33367e) | Apr 04, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [aaa65ac72e](https://linux-hardware.org/?probe=aaa65ac72e) | Apr 03, 2021 |
| Alienware     | m15 R3                      | [4bb00b8c3e](https://linux-hardware.org/?probe=4bb00b8c3e) | Apr 03, 2021 |
| ASUSTek       | FX503VM                     | [ab804c36d0](https://linux-hardware.org/?probe=ab804c36d0) | Apr 02, 2021 |
| Dell          | Inspiron 5448               | [b93b519ee4](https://linux-hardware.org/?probe=b93b519ee4) | Apr 01, 2021 |
| HP            | Laptop 15s-eq0xxx           | [b27e47c9b2](https://linux-hardware.org/?probe=b27e47c9b2) | Apr 01, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | [aa8f00686c](https://linux-hardware.org/?probe=aa8f00686c) | Apr 01, 2021 |
| Dell          | Inspiron 5448               | [c7478acb44](https://linux-hardware.org/?probe=c7478acb44) | Apr 01, 2021 |
| Lenovo        | ThinkPad X230 23252QG       | [a3e8c4ecb4](https://linux-hardware.org/?probe=a3e8c4ecb4) | Mar 31, 2021 |
| HP            | EliteBook 8470p             | [2e3301413b](https://linux-hardware.org/?probe=2e3301413b) | Mar 31, 2021 |
| Dell          | Vostro 3460                 | [22e8a09fcc](https://linux-hardware.org/?probe=22e8a09fcc) | Mar 31, 2021 |
| Dell          | Latitude E6430              | [3f2de2fadd](https://linux-hardware.org/?probe=3f2de2fadd) | Mar 30, 2021 |
| Lenovo        | G40-80 80JE                 | [c87db67f57](https://linux-hardware.org/?probe=c87db67f57) | Mar 30, 2021 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | [74d654a45f](https://linux-hardware.org/?probe=74d654a45f) | Mar 30, 2021 |
| Dell          | G3 3579                     | [b0bbd5bb7d](https://linux-hardware.org/?probe=b0bbd5bb7d) | Mar 29, 2021 |
| Lenovo        | Unknown                     | [98ed905fb1](https://linux-hardware.org/?probe=98ed905fb1) | Mar 28, 2021 |
| HP            | Laptop 15s-eq0xxx           | [80528e6667](https://linux-hardware.org/?probe=80528e6667) | Mar 28, 2021 |
| ASUSTek       | X550LN                      | [ae445d335b](https://linux-hardware.org/?probe=ae445d335b) | Mar 27, 2021 |
| Dell          | Inspiron 3543               | [240e26d151](https://linux-hardware.org/?probe=240e26d151) | Mar 27, 2021 |
| Lenovo        | Y520-15IKBA 80WY            | [57f82f03ae](https://linux-hardware.org/?probe=57f82f03ae) | Mar 25, 2021 |
| ASUSTek       | X555QG                      | [9e2fba943d](https://linux-hardware.org/?probe=9e2fba943d) | Mar 25, 2021 |
| Lenovo        | Legion 7 15IMH05 81YT       | [850c64ba7f](https://linux-hardware.org/?probe=850c64ba7f) | Mar 24, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [80917b7c82](https://linux-hardware.org/?probe=80917b7c82) | Mar 24, 2021 |
| Lenovo        | Yoga 900-13ISK 80MK         | [e78a3ca624](https://linux-hardware.org/?probe=e78a3ca624) | Mar 24, 2021 |
| Lenovo        | ThinkPad T460s 20F90043G... | [dab7f21292](https://linux-hardware.org/?probe=dab7f21292) | Mar 24, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [cf83d29ea6](https://linux-hardware.org/?probe=cf83d29ea6) | Mar 23, 2021 |
| Lenovo        | ThinkPad T460s 20F90043G... | [9d6c87a657](https://linux-hardware.org/?probe=9d6c87a657) | Mar 23, 2021 |
| Dell          | Latitude 5300               | [1da225004a](https://linux-hardware.org/?probe=1da225004a) | Mar 23, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [367455807e](https://linux-hardware.org/?probe=367455807e) | Mar 23, 2021 |
| MSI           | GT80 2QE                    | [48a433dac8](https://linux-hardware.org/?probe=48a433dac8) | Mar 23, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [1de185d0da](https://linux-hardware.org/?probe=1de185d0da) | Mar 22, 2021 |
| MSI           | Prestige 14Evo A11M         | [f335b7e690](https://linux-hardware.org/?probe=f335b7e690) | Mar 22, 2021 |
| TUXEDO        | InfinityBook S 14 Gen6      | [5fc12f578b](https://linux-hardware.org/?probe=5fc12f578b) | Mar 22, 2021 |
| HP            | OMEN by Laptop 17-cb0xxx    | [89b25409bb](https://linux-hardware.org/?probe=89b25409bb) | Mar 22, 2021 |
| HP            | EliteBook 840 G3            | [47b39d68e6](https://linux-hardware.org/?probe=47b39d68e6) | Mar 22, 2021 |
| Dell          | Inspiron 7375               | [3208c17fb3](https://linux-hardware.org/?probe=3208c17fb3) | Mar 22, 2021 |
| HP            | EliteBook 840 G3            | [5807483d66](https://linux-hardware.org/?probe=5807483d66) | Mar 22, 2021 |
| Dell          | Latitude E4200              | [cad17f5f44](https://linux-hardware.org/?probe=cad17f5f44) | Mar 21, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [9e4bff4b7d](https://linux-hardware.org/?probe=9e4bff4b7d) | Mar 21, 2021 |
| China         | c16b                        | [797cc04800](https://linux-hardware.org/?probe=797cc04800) | Mar 21, 2021 |
| Lenovo        | ThinkPad X220 4291B66       | [411fb65be7](https://linux-hardware.org/?probe=411fb65be7) | Mar 21, 2021 |
| Lenovo        | Yoga 900-13ISK 80MK         | [d32ba25353](https://linux-hardware.org/?probe=d32ba25353) | Mar 21, 2021 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [5f904125d3](https://linux-hardware.org/?probe=5f904125d3) | Mar 21, 2021 |
| ASUSTek       | N752VX                      | [48cb617015](https://linux-hardware.org/?probe=48cb617015) | Mar 20, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [17a432847e](https://linux-hardware.org/?probe=17a432847e) | Mar 20, 2021 |
| ASUSTek       | X411UA                      | [076339c09d](https://linux-hardware.org/?probe=076339c09d) | Mar 20, 2021 |
| HP            | EliteBook x360 1040 G5      | [6c42757430](https://linux-hardware.org/?probe=6c42757430) | Mar 19, 2021 |
| Lenovo        | S10-3                       | [4414b02b8e](https://linux-hardware.org/?probe=4414b02b8e) | Mar 19, 2021 |
| Acer          | Aspire 5742G                | [047a34bb2c](https://linux-hardware.org/?probe=047a34bb2c) | Mar 19, 2021 |
| Lenovo        | IdeaPad 710S-13IKB 80VQ     | [449aefbf2c](https://linux-hardware.org/?probe=449aefbf2c) | Mar 18, 2021 |
| Acer          | Aspire A317-51G             | [d771eb869d](https://linux-hardware.org/?probe=d771eb869d) | Mar 18, 2021 |
| Dell          | XPS 15 9570                 | [a0c9dc85c3](https://linux-hardware.org/?probe=a0c9dc85c3) | Mar 18, 2021 |
| ASUSTek       | ROG Strix G731GW_G731GW     | [23fdd22c97](https://linux-hardware.org/?probe=23fdd22c97) | Mar 18, 2021 |
| ASUSTek       | ROG Strix G731GW_G731GW     | [53bd92f462](https://linux-hardware.org/?probe=53bd92f462) | Mar 18, 2021 |
| HP            | ProBook 430 G1              | [77fb822f1f](https://linux-hardware.org/?probe=77fb822f1f) | Mar 18, 2021 |
| MSI           | GV62 8RD                    | [e5203bf25c](https://linux-hardware.org/?probe=e5203bf25c) | Mar 18, 2021 |
| Lenovo        | ThinkPad E570 20H500B1RT    | [6b48c91fde](https://linux-hardware.org/?probe=6b48c91fde) | Mar 17, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [11a847cd7f](https://linux-hardware.org/?probe=11a847cd7f) | Mar 17, 2021 |
| Lenovo        | ThinkPad E570 20H500B1RT    | [1e9e5e7dca](https://linux-hardware.org/?probe=1e9e5e7dca) | Mar 17, 2021 |
| ASUSTek       | TUF Gaming FX505DY_TUF50... | [60ad7c7aec](https://linux-hardware.org/?probe=60ad7c7aec) | Mar 17, 2021 |
| Lenovo        | ThinkPad X250 20CLS0PU00    | [625aee5fcc](https://linux-hardware.org/?probe=625aee5fcc) | Mar 17, 2021 |
| Lenovo        | ThinkPad E585 20KV0008GE    | [37fd15b69e](https://linux-hardware.org/?probe=37fd15b69e) | Mar 17, 2021 |
| Dell          | XPS 13 9350                 | [acca6463dc](https://linux-hardware.org/?probe=acca6463dc) | Mar 17, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [2d79aa5932](https://linux-hardware.org/?probe=2d79aa5932) | Mar 17, 2021 |
| Lenovo        | ThinkPad X220 4290LA9       | [a2fbdbe6c9](https://linux-hardware.org/?probe=a2fbdbe6c9) | Mar 17, 2021 |
| HP            | ProBook 6560b               | [2f34d9893d](https://linux-hardware.org/?probe=2f34d9893d) | Mar 17, 2021 |
| Lenovo        | G500 20236                  | [a4e5de433a](https://linux-hardware.org/?probe=a4e5de433a) | Mar 17, 2021 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [2d9b9381bd](https://linux-hardware.org/?probe=2d9b9381bd) | Mar 16, 2021 |
| Dell          | Latitude E6410              | [cb1ddd4272](https://linux-hardware.org/?probe=cb1ddd4272) | Mar 16, 2021 |
| Dell          | Latitude E6410              | [4e32f113da](https://linux-hardware.org/?probe=4e32f113da) | Mar 16, 2021 |
| Acer          | Nitro AN515-43              | [009a95412f](https://linux-hardware.org/?probe=009a95412f) | Mar 16, 2021 |
| Toshiba       | PORTEGE R30-A               | [765ae993b9](https://linux-hardware.org/?probe=765ae993b9) | Mar 16, 2021 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | [5265c78fd2](https://linux-hardware.org/?probe=5265c78fd2) | Mar 16, 2021 |
| Lenovo        | ThinkPad T590 20N4004UMB    | [7746d65773](https://linux-hardware.org/?probe=7746d65773) | Mar 15, 2021 |
| Micro Elec... | 1530                        | [8e06c0291f](https://linux-hardware.org/?probe=8e06c0291f) | Mar 14, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [02962e3835](https://linux-hardware.org/?probe=02962e3835) | Mar 13, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [ae0a17e8ab](https://linux-hardware.org/?probe=ae0a17e8ab) | Mar 13, 2021 |
| Acer          | Nitro AN515-52              | [84d11c6201](https://linux-hardware.org/?probe=84d11c6201) | Mar 12, 2021 |
| Dell          | G3 3579                     | [3a5fd42c39](https://linux-hardware.org/?probe=3a5fd42c39) | Mar 12, 2021 |
| Dell          | G3 3579                     | [4b4386b160](https://linux-hardware.org/?probe=4b4386b160) | Mar 12, 2021 |
| HP            | EliteBook 840 G2            | [e90e4463c7](https://linux-hardware.org/?probe=e90e4463c7) | Mar 11, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [800fa8f91a](https://linux-hardware.org/?probe=800fa8f91a) | Mar 10, 2021 |
| Dell          | Latitude 5501               | [50c751b097](https://linux-hardware.org/?probe=50c751b097) | Mar 10, 2021 |
| Dell          | XPS 13 9370                 | [865e070587](https://linux-hardware.org/?probe=865e070587) | Mar 10, 2021 |
| HP            | EliteBook 830 G6            | [45f8bdabb0](https://linux-hardware.org/?probe=45f8bdabb0) | Mar 09, 2021 |
| HP            | EliteBook 830 G6            | [de6b1ee9fe](https://linux-hardware.org/?probe=de6b1ee9fe) | Mar 09, 2021 |
| ASUSTek       | ROG Strix G533QS_G533QS     | [9fd07bc65d](https://linux-hardware.org/?probe=9fd07bc65d) | Mar 09, 2021 |
| Dell          | XPS 15 7590                 | [c77cc6f8de](https://linux-hardware.org/?probe=c77cc6f8de) | Mar 08, 2021 |
| Dell          | XPS 15 7590                 | [6c7c063a10](https://linux-hardware.org/?probe=6c7c063a10) | Mar 08, 2021 |
| ASUSTek       | UX31A                       | [47d50acdde](https://linux-hardware.org/?probe=47d50acdde) | Mar 08, 2021 |
| Dell          | Latitude 5491               | [ccb1badf86](https://linux-hardware.org/?probe=ccb1badf86) | Mar 08, 2021 |
| Dell          | XPS 15 9570                 | [72854cf243](https://linux-hardware.org/?probe=72854cf243) | Mar 08, 2021 |
| HP            | EliteBook 840 G6            | [e6dd893b74](https://linux-hardware.org/?probe=e6dd893b74) | Mar 07, 2021 |
| Dell          | XPS 15 9570                 | [f6574e5a69](https://linux-hardware.org/?probe=f6574e5a69) | Mar 07, 2021 |
| Apple         | MacBookPro11,1              | [3d2cf39440](https://linux-hardware.org/?probe=3d2cf39440) | Mar 07, 2021 |
| Dell          | Latitude 7280               | [64e390d0d6](https://linux-hardware.org/?probe=64e390d0d6) | Mar 07, 2021 |
| ASUSTek       | X555UB                      | [8175c8eb47](https://linux-hardware.org/?probe=8175c8eb47) | Mar 07, 2021 |
| Lenovo        | ThinkPad X200 7459KM3       | [15ccb74794](https://linux-hardware.org/?probe=15ccb74794) | Mar 07, 2021 |
| Dell          | Inspiron 3785               | [dddbed1892](https://linux-hardware.org/?probe=dddbed1892) | Mar 06, 2021 |
| Lenovo        | ThinkPad X200 7459KM3       | [85e3dc0a82](https://linux-hardware.org/?probe=85e3dc0a82) | Mar 06, 2021 |
| Lenovo        | ThinkPad T440p 20AWA0LUP... | [3b4b899f7c](https://linux-hardware.org/?probe=3b4b899f7c) | Mar 06, 2021 |
| Toshiba       | Satellite S55t-A            | [5aa53770bf](https://linux-hardware.org/?probe=5aa53770bf) | Mar 06, 2021 |
| Toshiba       | Satellite S55t-A            | [5ed863271a](https://linux-hardware.org/?probe=5ed863271a) | Mar 06, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | [57bb9f146c](https://linux-hardware.org/?probe=57bb9f146c) | Mar 06, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [5051ba6156](https://linux-hardware.org/?probe=5051ba6156) | Mar 05, 2021 |
| Lenovo        | Legion R7000 2020 82B6      | [3b64f161c0](https://linux-hardware.org/?probe=3b64f161c0) | Mar 05, 2021 |
| Acer          | Aspire A515-51G             | [820e208bca](https://linux-hardware.org/?probe=820e208bca) | Mar 05, 2021 |
| Dell          | Vostro 3478                 | [c5dfc3ea83](https://linux-hardware.org/?probe=c5dfc3ea83) | Mar 05, 2021 |
| Lenovo        | Legion R7000 2020 82B6      | [f3cfea77ac](https://linux-hardware.org/?probe=f3cfea77ac) | Mar 04, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [4080da309c](https://linux-hardware.org/?probe=4080da309c) | Mar 03, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [8ebc8b06a5](https://linux-hardware.org/?probe=8ebc8b06a5) | Mar 03, 2021 |
| HP            | 255 G6 Notebook PC          | [7935ceaf6b](https://linux-hardware.org/?probe=7935ceaf6b) | Mar 03, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | [13649ef673](https://linux-hardware.org/?probe=13649ef673) | Mar 03, 2021 |
| Dell          | Latitude E5540              | [90f7f06845](https://linux-hardware.org/?probe=90f7f06845) | Mar 03, 2021 |
| Lenovo        | ThinkPad X280 20KES3F7TH    | [c0e975c3fa](https://linux-hardware.org/?probe=c0e975c3fa) | Mar 02, 2021 |
| Lenovo        | ThinkPad T490 20RYS0K400    | [fc42a67aa7](https://linux-hardware.org/?probe=fc42a67aa7) | Mar 02, 2021 |
| Lenovo        | IdeaPad Y510P 20217         | [c71c072906](https://linux-hardware.org/?probe=c71c072906) | Mar 01, 2021 |
| HP            | Laptop 14-dk0xxx            | [29c5bf05a9](https://linux-hardware.org/?probe=29c5bf05a9) | Mar 01, 2021 |
| Lenovo        | IdeaPad Y510P 20217         | [1ab5a27c64](https://linux-hardware.org/?probe=1ab5a27c64) | Feb 28, 2021 |
| Lenovo        | IdeaPad Y510P 20217         | [5c874e5faf](https://linux-hardware.org/?probe=5c874e5faf) | Feb 28, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [1c5f0762d1](https://linux-hardware.org/?probe=1c5f0762d1) | Feb 28, 2021 |
| Dell          | Inspiron 5458               | [2c82f40b93](https://linux-hardware.org/?probe=2c82f40b93) | Feb 27, 2021 |
| ASUSTek       | GL753VD                     | [bdb6fc8fb3](https://linux-hardware.org/?probe=bdb6fc8fb3) | Feb 27, 2021 |
| Timi          | RedmiBook 14 II             | [082f8fd3e5](https://linux-hardware.org/?probe=082f8fd3e5) | Feb 27, 2021 |
| Timi          | RedmiBook 14 II             | [1555ed8743](https://linux-hardware.org/?probe=1555ed8743) | Feb 27, 2021 |
| Lenovo        | ThinkPad S5-S540 20B3CTO... | [501f921177](https://linux-hardware.org/?probe=501f921177) | Feb 27, 2021 |
| Dell          | Vostro 3460                 | [3127b67fa3](https://linux-hardware.org/?probe=3127b67fa3) | Feb 27, 2021 |
| Dell          | Vostro 3460                 | [452f5e2dc5](https://linux-hardware.org/?probe=452f5e2dc5) | Feb 27, 2021 |
| HP            | Spectre XT Ultrabook PC     | [217e6af3b8](https://linux-hardware.org/?probe=217e6af3b8) | Feb 26, 2021 |
| Acer          | Predator PH315-52           | [9c0c42a7f6](https://linux-hardware.org/?probe=9c0c42a7f6) | Feb 26, 2021 |
| ASUSTek       | K75VM                       | [76b4457e58](https://linux-hardware.org/?probe=76b4457e58) | Feb 25, 2021 |
| HP            | ProBook 4320s               | [0032b94e02](https://linux-hardware.org/?probe=0032b94e02) | Feb 25, 2021 |
| HP            | ProBook 4320s               | [bbed0b55e2](https://linux-hardware.org/?probe=bbed0b55e2) | Feb 25, 2021 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | [d787733560](https://linux-hardware.org/?probe=d787733560) | Feb 25, 2021 |
| Dell          | Precision M6600             | [117e981ef3](https://linux-hardware.org/?probe=117e981ef3) | Feb 24, 2021 |
| ASUSTek       | M50Vc                       | [8abf85e052](https://linux-hardware.org/?probe=8abf85e052) | Feb 24, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | [58d3bac346](https://linux-hardware.org/?probe=58d3bac346) | Feb 24, 2021 |
| ASUSTek       | M50Vc                       | [3a9a5e9b7c](https://linux-hardware.org/?probe=3a9a5e9b7c) | Feb 24, 2021 |
| ASUSTek       | M50Vc                       | [295654ca20](https://linux-hardware.org/?probe=295654ca20) | Feb 24, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | [96a3577708](https://linux-hardware.org/?probe=96a3577708) | Feb 24, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [e94a904ba5](https://linux-hardware.org/?probe=e94a904ba5) | Feb 23, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [8dcb374de2](https://linux-hardware.org/?probe=8dcb374de2) | Feb 23, 2021 |
| Apple         | MacBookPro15,1              | [566cc27d41](https://linux-hardware.org/?probe=566cc27d41) | Feb 22, 2021 |
| Apple         | MacBookPro15,1              | [18cb9d83ae](https://linux-hardware.org/?probe=18cb9d83ae) | Feb 22, 2021 |
| HP            | Compaq 8710w                | [b65b21f334](https://linux-hardware.org/?probe=b65b21f334) | Feb 22, 2021 |
| HP            | Compaq 8710w                | [c29370c73e](https://linux-hardware.org/?probe=c29370c73e) | Feb 22, 2021 |
| HP            | OMEN by Laptop              | [673e68974f](https://linux-hardware.org/?probe=673e68974f) | Feb 22, 2021 |
| Lenovo        | ThinkPad L460 20FVS14T00    | [8348d962fe](https://linux-hardware.org/?probe=8348d962fe) | Feb 22, 2021 |
| HP            | ENVY Laptop 13-ad1xx        | [4299d44910](https://linux-hardware.org/?probe=4299d44910) | Feb 22, 2021 |
| Dell          | XPS 17 9700                 | [e826c938ba](https://linux-hardware.org/?probe=e826c938ba) | Feb 21, 2021 |
| HP            | ProBook 455 G1              | [9f234b4c02](https://linux-hardware.org/?probe=9f234b4c02) | Feb 21, 2021 |
| HP            | ProBook 455 G1              | [93fe8fc674](https://linux-hardware.org/?probe=93fe8fc674) | Feb 21, 2021 |
| Timi          | TM1701                      | [5b111b9525](https://linux-hardware.org/?probe=5b111b9525) | Feb 21, 2021 |
| ASUSTek       | X550EP                      | [13e287661b](https://linux-hardware.org/?probe=13e287661b) | Feb 21, 2021 |
| ASUSTek       | X550EP                      | [35d75dd761](https://linux-hardware.org/?probe=35d75dd761) | Feb 20, 2021 |
| Acer          | Swift SF314-56              | [e893201b87](https://linux-hardware.org/?probe=e893201b87) | Feb 20, 2021 |
| Acer          | Nitro AN515-42              | [1de937bc00](https://linux-hardware.org/?probe=1de937bc00) | Feb 19, 2021 |
| MIFcom        | W35xSS_370SS                | [6f7495d474](https://linux-hardware.org/?probe=6f7495d474) | Feb 19, 2021 |
| ASUSTek       | X705UDR                     | [40cce11cc2](https://linux-hardware.org/?probe=40cce11cc2) | Feb 19, 2021 |
| Acer          | Aspire A315-53              | [f2a32b0652](https://linux-hardware.org/?probe=f2a32b0652) | Feb 18, 2021 |
| Dell          | Latitude E5540              | [2734875cc0](https://linux-hardware.org/?probe=2734875cc0) | Feb 18, 2021 |
| Lenovo        | IdeaPad C340-14API 81N6     | [6e91e6e551](https://linux-hardware.org/?probe=6e91e6e551) | Feb 18, 2021 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | [3d98231277](https://linux-hardware.org/?probe=3d98231277) | Feb 17, 2021 |
| HP            | EliteBook 820 G1            | [ddb80094f7](https://linux-hardware.org/?probe=ddb80094f7) | Feb 17, 2021 |
| HP            | EliteBook 820 G1            | [d16c5df2d5](https://linux-hardware.org/?probe=d16c5df2d5) | Feb 17, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [42cd2866c5](https://linux-hardware.org/?probe=42cd2866c5) | Feb 17, 2021 |
| Acer          | Swift SF314-42              | [401fbc4e6c](https://linux-hardware.org/?probe=401fbc4e6c) | Feb 17, 2021 |
| Acer          | Swift SF314-42              | [3911c9802c](https://linux-hardware.org/?probe=3911c9802c) | Feb 17, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [c56aef8cf9](https://linux-hardware.org/?probe=c56aef8cf9) | Feb 17, 2021 |
| MIFcom        | W35xSS_370SS                | [f79ecc233a](https://linux-hardware.org/?probe=f79ecc233a) | Feb 16, 2021 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | [653cc5e0df](https://linux-hardware.org/?probe=653cc5e0df) | Feb 16, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | [44d369c633](https://linux-hardware.org/?probe=44d369c633) | Feb 16, 2021 |
| Dell          | Inspiron 5570               | [a79c837a9b](https://linux-hardware.org/?probe=a79c837a9b) | Feb 16, 2021 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | [977e293baa](https://linux-hardware.org/?probe=977e293baa) | Feb 16, 2021 |
| Dell          | Inspiron 5570               | [5cb0f77327](https://linux-hardware.org/?probe=5cb0f77327) | Feb 16, 2021 |
| Notebook      | W350STQ/W370ST              | [d79f3dab77](https://linux-hardware.org/?probe=d79f3dab77) | Feb 16, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | [9994b75c38](https://linux-hardware.org/?probe=9994b75c38) | Feb 15, 2021 |
| Dell          | Inspiron 7591               | [c3585d014b](https://linux-hardware.org/?probe=c3585d014b) | Feb 14, 2021 |
| HP            | Notebook                    | [2835b358ff](https://linux-hardware.org/?probe=2835b358ff) | Feb 14, 2021 |
| Intel         | powered classmate PC        | [dd8b22c3e5](https://linux-hardware.org/?probe=dd8b22c3e5) | Feb 13, 2021 |
| HP            | Laptop 15q-ds0xxx           | [64c04449f5](https://linux-hardware.org/?probe=64c04449f5) | Feb 13, 2021 |
| Dell          | Precision M6600             | [ce93ab4159](https://linux-hardware.org/?probe=ce93ab4159) | Feb 12, 2021 |
| OEM           | Unknown                     | [3f911df0ff](https://linux-hardware.org/?probe=3f911df0ff) | Feb 11, 2021 |
| Acer          | Aspire A515-44              | [813981d5ea](https://linux-hardware.org/?probe=813981d5ea) | Feb 11, 2021 |
| Lenovo        | ThinkPad E570 20H5CTO1WW    | [c4511e85fc](https://linux-hardware.org/?probe=c4511e85fc) | Feb 11, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [0d1446c219](https://linux-hardware.org/?probe=0d1446c219) | Feb 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [ec95272afa](https://linux-hardware.org/?probe=ec95272afa) | Feb 10, 2021 |
| MSI           | MS-7A33                     | [001ec3af7f](https://linux-hardware.org/?probe=001ec3af7f) | Feb 10, 2021 |
| Samsung       | RV415/RV515                 | [b2c92d075d](https://linux-hardware.org/?probe=b2c92d075d) | Feb 10, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [0d21d2fd42](https://linux-hardware.org/?probe=0d21d2fd42) | Feb 09, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [f68acdb5fc](https://linux-hardware.org/?probe=f68acdb5fc) | Feb 09, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | [6f095f70ea](https://linux-hardware.org/?probe=6f095f70ea) | Feb 08, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | [4573978fce](https://linux-hardware.org/?probe=4573978fce) | Feb 08, 2021 |
| HP            | EliteBook 840 G6            | [4caff97f56](https://linux-hardware.org/?probe=4caff97f56) | Feb 08, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [586feb8dc5](https://linux-hardware.org/?probe=586feb8dc5) | Feb 08, 2021 |
| Acer          | Aspire A515-44              | [60229a2d17](https://linux-hardware.org/?probe=60229a2d17) | Feb 06, 2021 |
| Acer          | Aspire A515-44              | [2503a53be9](https://linux-hardware.org/?probe=2503a53be9) | Feb 06, 2021 |
| HP            | Pavilion g6                 | [e99adeae5d](https://linux-hardware.org/?probe=e99adeae5d) | Feb 06, 2021 |
| HP            | EliteBook 8470p             | [023da1c7d7](https://linux-hardware.org/?probe=023da1c7d7) | Feb 06, 2021 |
| Apple         | MacBookPro9,2               | [c3062ebba4](https://linux-hardware.org/?probe=c3062ebba4) | Feb 04, 2021 |
| Apple         | MacBookPro9,2               | [2203826b83](https://linux-hardware.org/?probe=2203826b83) | Feb 04, 2021 |
| Acer          | Nitro AN515-55              | [eb001a0c54](https://linux-hardware.org/?probe=eb001a0c54) | Feb 03, 2021 |
| HP            | Laptop 15s-eq0xxx           | [552a1ab8f4](https://linux-hardware.org/?probe=552a1ab8f4) | Feb 03, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [50f82f6bd6](https://linux-hardware.org/?probe=50f82f6bd6) | Feb 02, 2021 |
| Lenovo        | IdeaPad 320S-13IKB 81AK     | [c9009b15f1](https://linux-hardware.org/?probe=c9009b15f1) | Feb 01, 2021 |
| Dell          | Latitude E6320              | [cfed1ad7b7](https://linux-hardware.org/?probe=cfed1ad7b7) | Jan 31, 2021 |
| Dell          | Vostro 5470                 | [73aeae1ff3](https://linux-hardware.org/?probe=73aeae1ff3) | Jan 30, 2021 |
| HP            | Pavilion Laptop 15-cs1xx... | [f13d698217](https://linux-hardware.org/?probe=f13d698217) | Jan 30, 2021 |
| HP            | EliteBook Folio 1040 G3     | [2f2fafc282](https://linux-hardware.org/?probe=2f2fafc282) | Jan 30, 2021 |
| Dell          | Latitude 5424 Rugged        | [bd0889c8d5](https://linux-hardware.org/?probe=bd0889c8d5) | Jan 30, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | [251b2141ee](https://linux-hardware.org/?probe=251b2141ee) | Jan 30, 2021 |
| Samsung       | 300E5M/300E5L               | [3cc4bb3368](https://linux-hardware.org/?probe=3cc4bb3368) | Jan 30, 2021 |
| ASUSTek       | ZenBook 13 UX331FAL_UX33... | [2c7cc1502f](https://linux-hardware.org/?probe=2c7cc1502f) | Jan 30, 2021 |
| Dell          | Latitude E5570              | [2e00acc013](https://linux-hardware.org/?probe=2e00acc013) | Jan 29, 2021 |
| Packard Be... | EasyNote TM86               | [049a58f1bd](https://linux-hardware.org/?probe=049a58f1bd) | Jan 29, 2021 |
| ASUSTek       | N56JR                       | [29ad612f88](https://linux-hardware.org/?probe=29ad612f88) | Jan 28, 2021 |
| Lenovo        | ThinkPad W540 20BHS0B30T    | [5ed4d3f0ad](https://linux-hardware.org/?probe=5ed4d3f0ad) | Jan 28, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [e2fdb97a29](https://linux-hardware.org/?probe=e2fdb97a29) | Jan 28, 2021 |
| Dell          | Latitude E6430              | [2202c1628a](https://linux-hardware.org/?probe=2202c1628a) | Jan 27, 2021 |
| Dell          | Inspiron 1018               | [570fb5f20b](https://linux-hardware.org/?probe=570fb5f20b) | Jan 27, 2021 |
| Dell          | Inspiron 1018               | [b481e5f8d2](https://linux-hardware.org/?probe=b481e5f8d2) | Jan 27, 2021 |
| Lenovo        | Legion Y7000 81FW           | [a7106e3642](https://linux-hardware.org/?probe=a7106e3642) | Jan 27, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | [f212b04d45](https://linux-hardware.org/?probe=f212b04d45) | Jan 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [3f7639b6ec](https://linux-hardware.org/?probe=3f7639b6ec) | Jan 26, 2021 |
| HP            | ProBook 645 G4              | [8167ad2172](https://linux-hardware.org/?probe=8167ad2172) | Jan 26, 2021 |
| Dell          | Studio 1458                 | [20fe01ffe7](https://linux-hardware.org/?probe=20fe01ffe7) | Jan 24, 2021 |
| ASUSTek       | X580VD                      | [8b40c6b1eb](https://linux-hardware.org/?probe=8b40c6b1eb) | Jan 23, 2021 |
| Lenovo        | X200 2024AB3                | [0facd5402c](https://linux-hardware.org/?probe=0facd5402c) | Jan 23, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [db16047c5f](https://linux-hardware.org/?probe=db16047c5f) | Jan 21, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [863b8f47ac](https://linux-hardware.org/?probe=863b8f47ac) | Jan 21, 2021 |
| HP            | Pavilion 15                 | [da8215cc9f](https://linux-hardware.org/?probe=da8215cc9f) | Jan 21, 2021 |
| Google        | Candy                       | [78ffc02d1f](https://linux-hardware.org/?probe=78ffc02d1f) | Jan 21, 2021 |
| HP            | Pavilion dv6                | [6ed5af78cb](https://linux-hardware.org/?probe=6ed5af78cb) | Jan 20, 2021 |
| Dell          | XPS 17 9700                 | [0e6d1b7894](https://linux-hardware.org/?probe=0e6d1b7894) | Jan 20, 2021 |
| Dell          | XPS 17 9700                 | [d1a11dfc1d](https://linux-hardware.org/?probe=d1a11dfc1d) | Jan 20, 2021 |
| Dell          | Precision 5530              | [a3ff57b5ec](https://linux-hardware.org/?probe=a3ff57b5ec) | Jan 19, 2021 |
| ASUSTek       | Strix 15 GL503GE            | [0333bda726](https://linux-hardware.org/?probe=0333bda726) | Jan 19, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [333e5b1050](https://linux-hardware.org/?probe=333e5b1050) | Jan 19, 2021 |
| Acer          | Aspire 5738                 | [0c63002956](https://linux-hardware.org/?probe=0c63002956) | Jan 18, 2021 |
| Lenovo        | Unknown                     | [36fd6d092f](https://linux-hardware.org/?probe=36fd6d092f) | Jan 18, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [bcc97fd52d](https://linux-hardware.org/?probe=bcc97fd52d) | Jan 18, 2021 |
| Dell          | Latitude 5480               | [c160f7d7d8](https://linux-hardware.org/?probe=c160f7d7d8) | Jan 18, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [c7ba195cc9](https://linux-hardware.org/?probe=c7ba195cc9) | Jan 17, 2021 |
| HP            | Laptop 15s-eq0xxx           | [bea6c2935b](https://linux-hardware.org/?probe=bea6c2935b) | Jan 17, 2021 |
| Lenovo        | ThinkPad T460p 20FW0005A... | [ecc872dc4a](https://linux-hardware.org/?probe=ecc872dc4a) | Jan 16, 2021 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [9b0d2c9855](https://linux-hardware.org/?probe=9b0d2c9855) | Jan 16, 2021 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [82728c7a68](https://linux-hardware.org/?probe=82728c7a68) | Jan 15, 2021 |
| Google        | Candy                       | [647e483ccd](https://linux-hardware.org/?probe=647e483ccd) | Jan 15, 2021 |
| ASUSTek       | X580VD                      | [0c7390dde1](https://linux-hardware.org/?probe=0c7390dde1) | Jan 15, 2021 |
| Lenovo        | ThinkPad T460 20FMS2FR00    | [3c308a7199](https://linux-hardware.org/?probe=3c308a7199) | Jan 15, 2021 |
| ASUSTek       | X55A                        | [bbac234938](https://linux-hardware.org/?probe=bbac234938) | Jan 14, 2021 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | [b7b3175352](https://linux-hardware.org/?probe=b7b3175352) | Jan 14, 2021 |
| Lenovo        | V155-15API 81V5             | [9bce8db002](https://linux-hardware.org/?probe=9bce8db002) | Jan 14, 2021 |
| Acer          | Aspire V5-571G              | [05c38f7c4f](https://linux-hardware.org/?probe=05c38f7c4f) | Jan 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [d07945b691](https://linux-hardware.org/?probe=d07945b691) | Jan 13, 2021 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | [ed7d9bff15](https://linux-hardware.org/?probe=ed7d9bff15) | Jan 13, 2021 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [0cfe91c011](https://linux-hardware.org/?probe=0cfe91c011) | Jan 13, 2021 |
| Dell          | XPS 13 9300                 | [a6353a7b80](https://linux-hardware.org/?probe=a6353a7b80) | Jan 13, 2021 |
| Acer          | Aspire A515-51              | [04d5372852](https://linux-hardware.org/?probe=04d5372852) | Jan 13, 2021 |
| Dell          | Inspiron 3558               | [8cb65414eb](https://linux-hardware.org/?probe=8cb65414eb) | Jan 12, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [a716890bba](https://linux-hardware.org/?probe=a716890bba) | Jan 12, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [cc4b76d3f9](https://linux-hardware.org/?probe=cc4b76d3f9) | Jan 12, 2021 |
| Acer          | Aspire ES1-533              | [85584b3a30](https://linux-hardware.org/?probe=85584b3a30) | Jan 12, 2021 |
| Lenovo        | ThinkPad T490 20N20042US    | [ea09a2d475](https://linux-hardware.org/?probe=ea09a2d475) | Jan 12, 2021 |
| HP            | Pavilion g6                 | [2132944e80](https://linux-hardware.org/?probe=2132944e80) | Jan 12, 2021 |
| Sony          | SVE14A1X1EH                 | [f188daf894](https://linux-hardware.org/?probe=f188daf894) | Jan 11, 2021 |
| Razer         | Blade 15 Studio Edition ... | [4be7c1083a](https://linux-hardware.org/?probe=4be7c1083a) | Jan 11, 2021 |
| Unknown       | Unknown                     | [cb85e871ca](https://linux-hardware.org/?probe=cb85e871ca) | Jan 11, 2021 |
| HP            | Pavilion x2 Detachable      | [ff5cd9f8c3](https://linux-hardware.org/?probe=ff5cd9f8c3) | Jan 10, 2021 |
| HP            | Pavilion x2 Detachable      | [7f36b8febc](https://linux-hardware.org/?probe=7f36b8febc) | Jan 10, 2021 |
| Alienware     | 13 R3                       | [d3e331e671](https://linux-hardware.org/?probe=d3e331e671) | Jan 10, 2021 |
| Acer          | Extensa 5220                | [d782466748](https://linux-hardware.org/?probe=d782466748) | Jan 09, 2021 |
| Dell          | Inspiron 3476               | [71383e0fb0](https://linux-hardware.org/?probe=71383e0fb0) | Jan 09, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [7250d3b87b](https://linux-hardware.org/?probe=7250d3b87b) | Jan 08, 2021 |
| Dell          | Inspiron 3476               | [7c1ddbccc2](https://linux-hardware.org/?probe=7c1ddbccc2) | Jan 08, 2021 |
| Lenovo        | V15-IIL 82C5                | [a25d93686f](https://linux-hardware.org/?probe=a25d93686f) | Jan 08, 2021 |
| ASUSTek       | X510UR                      | [2549408023](https://linux-hardware.org/?probe=2549408023) | Jan 08, 2021 |
| Acer          | Aspire 5733                 | [1f4e4d7fbc](https://linux-hardware.org/?probe=1f4e4d7fbc) | Jan 08, 2021 |
| Dell          | XPS 13 9360                 | [df444c69ca](https://linux-hardware.org/?probe=df444c69ca) | Jan 07, 2021 |
| Lenovo        | V15-IIL 82C5                | [aadc39a98b](https://linux-hardware.org/?probe=aadc39a98b) | Jan 07, 2021 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | [643e539134](https://linux-hardware.org/?probe=643e539134) | Jan 06, 2021 |
| Dell          | Inspiron 3420               | [ee741ae355](https://linux-hardware.org/?probe=ee741ae355) | Jan 06, 2021 |
| Lenovo        | Legion Y7000 81FW           | [8b678d540d](https://linux-hardware.org/?probe=8b678d540d) | Jan 06, 2021 |
| Lenovo        | Legion Y7000 81FW           | [95eb2199fd](https://linux-hardware.org/?probe=95eb2199fd) | Jan 06, 2021 |
| Eluktronic... | THINN-15                    | [bc1c14dedc](https://linux-hardware.org/?probe=bc1c14dedc) | Jan 06, 2021 |
| Lenovo        | IdeaPad 320S-13IKB 81AK     | [1bddc81441](https://linux-hardware.org/?probe=1bddc81441) | Jan 06, 2021 |
| Dell          | XPS 13 9350                 | [5c7374311f](https://linux-hardware.org/?probe=5c7374311f) | Jan 05, 2021 |
| Dell          | Inspiron 3420               | [67dcf3b060](https://linux-hardware.org/?probe=67dcf3b060) | Jan 05, 2021 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [ea36c16e10](https://linux-hardware.org/?probe=ea36c16e10) | Jan 05, 2021 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [89d2d898df](https://linux-hardware.org/?probe=89d2d898df) | Jan 05, 2021 |
| Lenovo        | ThinkPad T450s 20BWS2KM0... | [15b25ccd9e](https://linux-hardware.org/?probe=15b25ccd9e) | Jan 05, 2021 |
| Lenovo        | ThinkPad X200 74591P0       | [63f030c61a](https://linux-hardware.org/?probe=63f030c61a) | Jan 04, 2021 |
| Acer          | Aspire 5738                 | [5be13b8e2d](https://linux-hardware.org/?probe=5be13b8e2d) | Jan 04, 2021 |
| Lenovo        | ThinkPad X200 74591P0       | [0280683b9f](https://linux-hardware.org/?probe=0280683b9f) | Jan 04, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [0f2ae77a6d](https://linux-hardware.org/?probe=0f2ae77a6d) | Jan 04, 2021 |
| Dell          | G7 7590                     | [d82419598a](https://linux-hardware.org/?probe=d82419598a) | Jan 04, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [7e0f5ef3ce](https://linux-hardware.org/?probe=7e0f5ef3ce) | Jan 04, 2021 |
| Acer          | Extensa 5220                | [32f287365f](https://linux-hardware.org/?probe=32f287365f) | Jan 04, 2021 |
| Lenovo        | ThinkPad X1 Carbon 34483... | [4e6cc9fdc4](https://linux-hardware.org/?probe=4e6cc9fdc4) | Jan 03, 2021 |
| Lenovo        | ThinkPad X121e 3045A64      | [704ade71dc](https://linux-hardware.org/?probe=704ade71dc) | Jan 03, 2021 |
| ASUSTek       | 900                         | [567f7ed581](https://linux-hardware.org/?probe=567f7ed581) | Jan 03, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [5f33bb97cc](https://linux-hardware.org/?probe=5f33bb97cc) | Jan 02, 2021 |
| HP            | Pavilion dv7                | [cdf6cceaa1](https://linux-hardware.org/?probe=cdf6cceaa1) | Jan 02, 2021 |
| Dell          | G3 3500                     | [584259b642](https://linux-hardware.org/?probe=584259b642) | Jan 02, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [75dc4698bf](https://linux-hardware.org/?probe=75dc4698bf) | Jan 02, 2021 |
| Dell          | Precision M6600             | [6e3b3211f0](https://linux-hardware.org/?probe=6e3b3211f0) | Jan 02, 2021 |
| Lenovo        | ThinkPad E570 20H5CTO1WW    | [e87d83f415](https://linux-hardware.org/?probe=e87d83f415) | Jan 01, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | [57e32dde0f](https://linux-hardware.org/?probe=57e32dde0f) | Jan 01, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [7214344943](https://linux-hardware.org/?probe=7214344943) | Jan 01, 2021 |
| Dell          | Precision 7740              | [ce9c5977c0](https://linux-hardware.org/?probe=ce9c5977c0) | Dec 31, 2020 |
| Dell          | XPS 15 7590                 | [5333c8596c](https://linux-hardware.org/?probe=5333c8596c) | Dec 31, 2020 |
| Dell          | Precision 7740              | [f0bb72a21a](https://linux-hardware.org/?probe=f0bb72a21a) | Dec 30, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | [e2599b8b3f](https://linux-hardware.org/?probe=e2599b8b3f) | Dec 30, 2020 |
| Dell          | XPS 13 9300                 | [97f9947fbc](https://linux-hardware.org/?probe=97f9947fbc) | Dec 30, 2020 |
| Dell          | Precision M6600             | [2757c1e066](https://linux-hardware.org/?probe=2757c1e066) | Dec 30, 2020 |
| Apple         | MacBookPro12,1              | [e60ff2c9ad](https://linux-hardware.org/?probe=e60ff2c9ad) | Dec 28, 2020 |
| Acer          | Aspire 5755G                | [5577ccef28](https://linux-hardware.org/?probe=5577ccef28) | Dec 28, 2020 |
| Fujitsu       | LIFEBOOK E780               | [573f8b6a9a](https://linux-hardware.org/?probe=573f8b6a9a) | Dec 27, 2020 |
| HP            | Laptop 15-dw0xxx            | [3cccdd4f54](https://linux-hardware.org/?probe=3cccdd4f54) | Dec 27, 2020 |
| ASUSTek       | X55A                        | [79e9816c30](https://linux-hardware.org/?probe=79e9816c30) | Dec 27, 2020 |
| HP            | Pavilion g6                 | [a2f441222a](https://linux-hardware.org/?probe=a2f441222a) | Dec 26, 2020 |
| ASUSTek       | X705UDR                     | [f9b297fcd2](https://linux-hardware.org/?probe=f9b297fcd2) | Dec 26, 2020 |
| ASUSTek       | X580VD                      | [73b015a681](https://linux-hardware.org/?probe=73b015a681) | Dec 24, 2020 |
| Lenovo        | ThinkPad E495 20NE0001US    | [976a04dc77](https://linux-hardware.org/?probe=976a04dc77) | Dec 24, 2020 |
| Timi          | RedmiBook 16                | [34bc3ceb48](https://linux-hardware.org/?probe=34bc3ceb48) | Dec 24, 2020 |
| HP            | OMEN Laptop 15-en0xxx       | [f98663f878](https://linux-hardware.org/?probe=f98663f878) | Dec 24, 2020 |
| HP            | 15                          | [e9ea153217](https://linux-hardware.org/?probe=e9ea153217) | Dec 23, 2020 |
| HP            | 15                          | [df1bd71a5b](https://linux-hardware.org/?probe=df1bd71a5b) | Dec 23, 2020 |
| Dell          | Inspiron 5423               | [e26ba66cc2](https://linux-hardware.org/?probe=e26ba66cc2) | Dec 23, 2020 |
| Dell          | Latitude 5400               | [212951f2c0](https://linux-hardware.org/?probe=212951f2c0) | Dec 23, 2020 |
| Unknown       | Unknown                     | [6f4de557cd](https://linux-hardware.org/?probe=6f4de557cd) | Dec 23, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [9fc1e83873](https://linux-hardware.org/?probe=9fc1e83873) | Dec 22, 2020 |
| HP            | EliteBook 845 G7 Noteboo... | [87c08ecbb6](https://linux-hardware.org/?probe=87c08ecbb6) | Dec 22, 2020 |
| Dell          | XPS 15 9560                 | [cd36c0f16e](https://linux-hardware.org/?probe=cd36c0f16e) | Dec 22, 2020 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | [d64c711496](https://linux-hardware.org/?probe=d64c711496) | Dec 22, 2020 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | [6b9276e883](https://linux-hardware.org/?probe=6b9276e883) | Dec 21, 2020 |
| Dell          | G5 5587                     | [046f189eac](https://linux-hardware.org/?probe=046f189eac) | Dec 21, 2020 |
| Dell          | XPS 15 9570                 | [169f75ba5c](https://linux-hardware.org/?probe=169f75ba5c) | Dec 21, 2020 |
| Lenovo        | Legion Y545 81Q6            | [0ec751ede8](https://linux-hardware.org/?probe=0ec751ede8) | Dec 21, 2020 |
| Dell          | XPS 13 9370                 | [965028440f](https://linux-hardware.org/?probe=965028440f) | Dec 21, 2020 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [f815cf63a0](https://linux-hardware.org/?probe=f815cf63a0) | Dec 21, 2020 |
| Eluktronic... | THINN-15                    | [af129bfcd6](https://linux-hardware.org/?probe=af129bfcd6) | Dec 20, 2020 |
| Unknown       | Unknown                     | [015d610ec9](https://linux-hardware.org/?probe=015d610ec9) | Dec 20, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [676c937813](https://linux-hardware.org/?probe=676c937813) | Dec 20, 2020 |
| HP            | EliteBook 845 G7 Noteboo... | [14a84d3948](https://linux-hardware.org/?probe=14a84d3948) | Dec 20, 2020 |
| Unknown       | CL341                       | [58a1317fdb](https://linux-hardware.org/?probe=58a1317fdb) | Dec 20, 2020 |
| HP            | ProBook 440 G3              | [ad30a7ae38](https://linux-hardware.org/?probe=ad30a7ae38) | Dec 20, 2020 |
| Packard Be... | EasyNote TH36               | [a27244410d](https://linux-hardware.org/?probe=a27244410d) | Dec 19, 2020 |
| Dell          | Vostro 5590                 | [32fc96f796](https://linux-hardware.org/?probe=32fc96f796) | Dec 19, 2020 |
| Schenker      | VIA 15 Pro                  | [241abeeed6](https://linux-hardware.org/?probe=241abeeed6) | Dec 18, 2020 |
| Acer          | Aspire A315-41G             | [50d9384f5c](https://linux-hardware.org/?probe=50d9384f5c) | Dec 18, 2020 |
| Lenovo        | ThinkPad T460s 20F9003UP... | [93a1f17197](https://linux-hardware.org/?probe=93a1f17197) | Dec 18, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [e9118b7dc7](https://linux-hardware.org/?probe=e9118b7dc7) | Dec 18, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [d0a8d6ce10](https://linux-hardware.org/?probe=d0a8d6ce10) | Dec 18, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [77e1cb3ca1](https://linux-hardware.org/?probe=77e1cb3ca1) | Dec 18, 2020 |
| HP            | ENVY Laptop 13-ad1xx        | [df48ec41c9](https://linux-hardware.org/?probe=df48ec41c9) | Dec 17, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [ba436cbd34](https://linux-hardware.org/?probe=ba436cbd34) | Dec 17, 2020 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [3919c21de0](https://linux-hardware.org/?probe=3919c21de0) | Dec 17, 2020 |
| Apple         | MacBookPro9,2               | [455989bdd1](https://linux-hardware.org/?probe=455989bdd1) | Dec 17, 2020 |
| Lenovo        | ThinkPad P70 20ER000EGE     | [6413990c99](https://linux-hardware.org/?probe=6413990c99) | Dec 16, 2020 |
| Lenovo        | B5400 20278                 | [56ea17c80b](https://linux-hardware.org/?probe=56ea17c80b) | Dec 15, 2020 |
| MSI           | GE70 2OC\2OE                | [60dea2620f](https://linux-hardware.org/?probe=60dea2620f) | Dec 15, 2020 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [f84406f485](https://linux-hardware.org/?probe=f84406f485) | Dec 15, 2020 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | [5b56323f14](https://linux-hardware.org/?probe=5b56323f14) | Dec 15, 2020 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | [2c7c774492](https://linux-hardware.org/?probe=2c7c774492) | Dec 15, 2020 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [b7fa9e38a1](https://linux-hardware.org/?probe=b7fa9e38a1) | Dec 14, 2020 |
| Lenovo        | ThinkPad T470s 20HGS6PF0... | [2f91f2576d](https://linux-hardware.org/?probe=2f91f2576d) | Dec 14, 2020 |
| Lenovo        | ThinkPad T490 20N3S2WY00    | [0997e16562](https://linux-hardware.org/?probe=0997e16562) | Dec 14, 2020 |
| Lenovo        | ThinkPad T490 20N3S2WY00    | [be34836704](https://linux-hardware.org/?probe=be34836704) | Dec 14, 2020 |
| Dell          | Inspiron 5559               | [9c8c42c87f](https://linux-hardware.org/?probe=9c8c42c87f) | Dec 14, 2020 |
| MSI           | GP60 2PE                    | [86b14d5fe3](https://linux-hardware.org/?probe=86b14d5fe3) | Dec 13, 2020 |
| MSI           | GP60 2PE                    | [a9d1e44e9e](https://linux-hardware.org/?probe=a9d1e44e9e) | Dec 13, 2020 |
| Fujitsu       | LIFEBOOK U772               | [4c1ac7d858](https://linux-hardware.org/?probe=4c1ac7d858) | Dec 13, 2020 |
| MSI           | GE62MVR 7RG                 | [43868ae5c1](https://linux-hardware.org/?probe=43868ae5c1) | Dec 13, 2020 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [c992c3ddb6](https://linux-hardware.org/?probe=c992c3ddb6) | Dec 13, 2020 |
| HP            | Pavilion g6                 | [9704fac062](https://linux-hardware.org/?probe=9704fac062) | Dec 13, 2020 |
| HUAWEI        | NBLK-WAX9X                  | [5ade11c62e](https://linux-hardware.org/?probe=5ade11c62e) | Dec 12, 2020 |
| Dell          | XPS 17 9700                 | [c86faa6047](https://linux-hardware.org/?probe=c86faa6047) | Dec 11, 2020 |
| Apple         | MacBookPro15,1              | [6b39cb0ac1](https://linux-hardware.org/?probe=6b39cb0ac1) | Dec 11, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [9a5a4b5f51](https://linux-hardware.org/?probe=9a5a4b5f51) | Dec 11, 2020 |
| Apple         | MacBookPro15,1              | [4a2bda5c7e](https://linux-hardware.org/?probe=4a2bda5c7e) | Dec 11, 2020 |
| Dell          | Inspiron 3583               | [43701f33b8](https://linux-hardware.org/?probe=43701f33b8) | Dec 10, 2020 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | [e8ad4359a8](https://linux-hardware.org/?probe=e8ad4359a8) | Dec 10, 2020 |
| Acer          | Aspire 5735                 | [f0486e9ce7](https://linux-hardware.org/?probe=f0486e9ce7) | Dec 10, 2020 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [84c876d970](https://linux-hardware.org/?probe=84c876d970) | Dec 10, 2020 |
| HP            | ZBook Studio G5             | [af0417cef5](https://linux-hardware.org/?probe=af0417cef5) | Dec 10, 2020 |
| Dell          | Latitude E6500              | [618abfec56](https://linux-hardware.org/?probe=618abfec56) | Dec 10, 2020 |
| Dell          | XPS 15 9500                 | [6cd743bdc6](https://linux-hardware.org/?probe=6cd743bdc6) | Dec 09, 2020 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [729ee9df19](https://linux-hardware.org/?probe=729ee9df19) | Dec 09, 2020 |
| HUAWEI        | HLY-WX9XX                   | [87cfa2982d](https://linux-hardware.org/?probe=87cfa2982d) | Dec 09, 2020 |
| Dell          | Inspiron 5370               | [9cf5fbfe60](https://linux-hardware.org/?probe=9cf5fbfe60) | Dec 09, 2020 |
| HP            | ProBook 640 G2              | [96df5858ea](https://linux-hardware.org/?probe=96df5858ea) | Dec 08, 2020 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [16d0321f68](https://linux-hardware.org/?probe=16d0321f68) | Dec 08, 2020 |
| Dell          | Latitude E5470              | [cae4e793ab](https://linux-hardware.org/?probe=cae4e793ab) | Dec 08, 2020 |
| Dell          | Precision 7510              | [fde3a0fab2](https://linux-hardware.org/?probe=fde3a0fab2) | Dec 08, 2020 |
| Lenovo        | ThinkPad L380 20M5CTO1WW    | [4fcc54ddaa](https://linux-hardware.org/?probe=4fcc54ddaa) | Dec 08, 2020 |
| HUAWEI        | HLY-WX9XX                   | [290c53b26c](https://linux-hardware.org/?probe=290c53b26c) | Dec 08, 2020 |
| Samsung       | 300E5M/300E5L               | [6b8a646e1d](https://linux-hardware.org/?probe=6b8a646e1d) | Dec 07, 2020 |
| Samsung       | 300E5M/300E5L               | [f303ec926f](https://linux-hardware.org/?probe=f303ec926f) | Dec 07, 2020 |
| ASUSTek       | X541UJ                      | [da286674b6](https://linux-hardware.org/?probe=da286674b6) | Dec 07, 2020 |
| ASUSTek       | X550EA                      | [1a233301ae](https://linux-hardware.org/?probe=1a233301ae) | Dec 07, 2020 |
| Acer          | Aspire A315-41              | [fbae74765b](https://linux-hardware.org/?probe=fbae74765b) | Dec 06, 2020 |
| HP            | Laptop 15-db1xxx            | [90a4638597](https://linux-hardware.org/?probe=90a4638597) | Dec 06, 2020 |
| HUAWEI        | BOHK-WAX9X                  | [58f006c48a](https://linux-hardware.org/?probe=58f006c48a) | Dec 06, 2020 |
| HP            | EliteBook 8560p             | [3cc104d803](https://linux-hardware.org/?probe=3cc104d803) | Dec 05, 2020 |
| ASUSTek       | X550EA                      | [164938366b](https://linux-hardware.org/?probe=164938366b) | Dec 05, 2020 |
| Dell          | Precision M6600             | [c73334f29e](https://linux-hardware.org/?probe=c73334f29e) | Dec 05, 2020 |
| HUAWEI        | BOHK-WAX9X                  | [ea2fd928c7](https://linux-hardware.org/?probe=ea2fd928c7) | Dec 05, 2020 |
| Toshiba       | Unknown                     | [dff44dc3ed](https://linux-hardware.org/?probe=dff44dc3ed) | Dec 05, 2020 |
| Unknown       | CL341                       | [a89169cc88](https://linux-hardware.org/?probe=a89169cc88) | Dec 05, 2020 |
| Unknown       | CL341                       | [b5fedabc1d](https://linux-hardware.org/?probe=b5fedabc1d) | Dec 05, 2020 |
| Lenovo        | ThinkPad T440p 20AN00C1G... | [a58b60cd7b](https://linux-hardware.org/?probe=a58b60cd7b) | Dec 05, 2020 |
| Lenovo        | ThinkPad T440p 20AN00C1G... | [f20c8690d8](https://linux-hardware.org/?probe=f20c8690d8) | Dec 04, 2020 |
| Lenovo        | ThinkPad T440p 20AWS5AD0... | [019dc4a90e](https://linux-hardware.org/?probe=019dc4a90e) | Dec 03, 2020 |
| EUROCOM       | Q6                          | [b177943ed3](https://linux-hardware.org/?probe=b177943ed3) | Dec 03, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [0fa7d651a6](https://linux-hardware.org/?probe=0fa7d651a6) | Dec 03, 2020 |
| Samsung       | 300E5M/300E5L               | [ea6f881de4](https://linux-hardware.org/?probe=ea6f881de4) | Dec 02, 2020 |
| Dell          | XPS 13 9350                 | [281d8f431c](https://linux-hardware.org/?probe=281d8f431c) | Dec 02, 2020 |
| ASUSTek       | X556UQK                     | [529e0c244d](https://linux-hardware.org/?probe=529e0c244d) | Dec 02, 2020 |
| MSI           | PE70 6QE                    | [cb5f05e67d](https://linux-hardware.org/?probe=cb5f05e67d) | Dec 02, 2020 |
| Dell          | Inspiron 3542               | [634959fc72](https://linux-hardware.org/?probe=634959fc72) | Dec 02, 2020 |
| Lenovo        | ThinkPad Edge E545 20B20... | [6bb8a90d90](https://linux-hardware.org/?probe=6bb8a90d90) | Dec 02, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [2a305a9be7](https://linux-hardware.org/?probe=2a305a9be7) | Dec 02, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [cf81aea5fe](https://linux-hardware.org/?probe=cf81aea5fe) | Dec 02, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [c0b9af35b9](https://linux-hardware.org/?probe=c0b9af35b9) | Dec 01, 2020 |
| HP            | ENVY Laptop 13-ad1xx        | [644123f7a9](https://linux-hardware.org/?probe=644123f7a9) | Dec 01, 2020 |
| Lenovo        | IdeaPad S145-15API 81UT     | [0f52051051](https://linux-hardware.org/?probe=0f52051051) | Dec 01, 2020 |
| Cube          | i16-L                       | [80ab92ec4d](https://linux-hardware.org/?probe=80ab92ec4d) | Dec 01, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [8783c87bb9](https://linux-hardware.org/?probe=8783c87bb9) | Nov 30, 2020 |
| Lenovo        | ThinkPad T420 4236MD4       | [1161db61e3](https://linux-hardware.org/?probe=1161db61e3) | Nov 30, 2020 |
| HP            | Laptop 15-db1xxx            | [16e814d66d](https://linux-hardware.org/?probe=16e814d66d) | Nov 29, 2020 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [75bf2ba123](https://linux-hardware.org/?probe=75bf2ba123) | Nov 29, 2020 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [e3c0f67fb8](https://linux-hardware.org/?probe=e3c0f67fb8) | Nov 29, 2020 |
| Acer          | Aspire ES1-732              | [243f8b5015](https://linux-hardware.org/?probe=243f8b5015) | Nov 29, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [3d5adf0bca](https://linux-hardware.org/?probe=3d5adf0bca) | Nov 29, 2020 |
| Dell          | Inspiron 5547               | [958e1e4b68](https://linux-hardware.org/?probe=958e1e4b68) | Nov 29, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [5d82f8dab5](https://linux-hardware.org/?probe=5d82f8dab5) | Nov 29, 2020 |
| HP            | Pavilion Laptop 15-ck069... | [03e4541f61](https://linux-hardware.org/?probe=03e4541f61) | Nov 29, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [91ff5fdd53](https://linux-hardware.org/?probe=91ff5fdd53) | Nov 28, 2020 |
| Dell          | Latitude E6510              | [48ea363079](https://linux-hardware.org/?probe=48ea363079) | Nov 28, 2020 |
| ASUSTek       | X510URR                     | [a3dd9f864c](https://linux-hardware.org/?probe=a3dd9f864c) | Nov 28, 2020 |
| Notebook      | NH5xAx                      | [f16ed03562](https://linux-hardware.org/?probe=f16ed03562) | Nov 28, 2020 |
| ASUSTek       | X510URR                     | [a72d856adc](https://linux-hardware.org/?probe=a72d856adc) | Nov 28, 2020 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | [eecab17720](https://linux-hardware.org/?probe=eecab17720) | Nov 28, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [a0054d7337](https://linux-hardware.org/?probe=a0054d7337) | Nov 27, 2020 |
| ASUSTek       | GL553VD                     | [46d4c1f45d](https://linux-hardware.org/?probe=46d4c1f45d) | Nov 26, 2020 |
| Dell          | Precision 7530              | [6ea3afdb4a](https://linux-hardware.org/?probe=6ea3afdb4a) | Nov 26, 2020 |
| Dell          | Inspiron 3583               | [226613d9e9](https://linux-hardware.org/?probe=226613d9e9) | Nov 25, 2020 |
| Samsung       | 550XCJ/550XCR               | [e2445ab852](https://linux-hardware.org/?probe=e2445ab852) | Nov 25, 2020 |
| Dell          | Latitude E5400              | [f7de592657](https://linux-hardware.org/?probe=f7de592657) | Nov 25, 2020 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [3665df34b1](https://linux-hardware.org/?probe=3665df34b1) | Nov 25, 2020 |
| ASUSTek       | UX31E                       | [b9f953bfed](https://linux-hardware.org/?probe=b9f953bfed) | Nov 25, 2020 |
| Sony          | VJF155B0121B                | [651661bfc9](https://linux-hardware.org/?probe=651661bfc9) | Nov 25, 2020 |
| HP            | ProBook 440 G6              | [d4f0cf4cf6](https://linux-hardware.org/?probe=d4f0cf4cf6) | Nov 25, 2020 |
| HP            | Compaq 6730b (GW687AV)      | [75dc9610dc](https://linux-hardware.org/?probe=75dc9610dc) | Nov 24, 2020 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [bd5a310b05](https://linux-hardware.org/?probe=bd5a310b05) | Nov 24, 2020 |
| HP            | Stream 11 Pro G4 EE         | [7b3ca4c46e](https://linux-hardware.org/?probe=7b3ca4c46e) | Nov 24, 2020 |
| MSI           | PE70 6QE                    | [90b21f8369](https://linux-hardware.org/?probe=90b21f8369) | Nov 23, 2020 |
| HUAWEI        | MACHC-WAX9                  | [79c7bfdad5](https://linux-hardware.org/?probe=79c7bfdad5) | Nov 23, 2020 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [ebd4db52e3](https://linux-hardware.org/?probe=ebd4db52e3) | Nov 23, 2020 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [4257a05b56](https://linux-hardware.org/?probe=4257a05b56) | Nov 23, 2020 |
| Acer          | Aspire A315-55G             | [5e19227f50](https://linux-hardware.org/?probe=5e19227f50) | Nov 23, 2020 |
| Lenovo        | ThinkPad T460p 20FWCTO1W... | [1a347f21fa](https://linux-hardware.org/?probe=1a347f21fa) | Nov 22, 2020 |
| Acer          | Aspire ES1-732              | [9a62fb8fe7](https://linux-hardware.org/?probe=9a62fb8fe7) | Nov 21, 2020 |
| Lenovo        | Unknown                     | [3c62a3829e](https://linux-hardware.org/?probe=3c62a3829e) | Nov 21, 2020 |
| Dell          | Inspiron N5010              | [2a68f69fe5](https://linux-hardware.org/?probe=2a68f69fe5) | Nov 21, 2020 |
| Razer         | Blade 15 Studio Edition ... | [35d9817a27](https://linux-hardware.org/?probe=35d9817a27) | Nov 21, 2020 |
| TUXEDO        | InfinityBook Pro 15 v4      | [1ce96fc94c](https://linux-hardware.org/?probe=1ce96fc94c) | Nov 21, 2020 |
| Lenovo        | ThinkPad T495 20NJ0008US    | [b5d29937ca](https://linux-hardware.org/?probe=b5d29937ca) | Nov 21, 2020 |
| Acer          | Predator PH317-52           | [acd91e696a](https://linux-hardware.org/?probe=acd91e696a) | Nov 21, 2020 |
| Lenovo        | ThinkPad T480s 20L8S2SD0... | [5b8cba727a](https://linux-hardware.org/?probe=5b8cba727a) | Nov 20, 2020 |
| MSI           | Bravo 15 A4DDR              | [476567d5b4](https://linux-hardware.org/?probe=476567d5b4) | Nov 20, 2020 |
| Lenovo        | Legion 5P 15IMH05H 82AW     | [46d30ce200](https://linux-hardware.org/?probe=46d30ce200) | Nov 20, 2020 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [41991db053](https://linux-hardware.org/?probe=41991db053) | Nov 20, 2020 |
| Lenovo        | ThinkPad T530 2429AE1       | [d5c940ab41](https://linux-hardware.org/?probe=d5c940ab41) | Nov 19, 2020 |
| ASUSTek       | Strix 17 GL703GE            | [3b9cfa3841](https://linux-hardware.org/?probe=3b9cfa3841) | Nov 19, 2020 |
| HUAWEI        | BOHK-WAX9X                  | [73c5a8bd67](https://linux-hardware.org/?probe=73c5a8bd67) | Nov 19, 2020 |
| Lenovo        | ThinkPad T495 20NJ0008US    | [e897473ade](https://linux-hardware.org/?probe=e897473ade) | Nov 19, 2020 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [c3aa7a6297](https://linux-hardware.org/?probe=c3aa7a6297) | Nov 18, 2020 |
| Lenovo        | ThinkPad L380 Yoga 20M8S... | [a68bf7cfc5](https://linux-hardware.org/?probe=a68bf7cfc5) | Nov 18, 2020 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [3e8df8bd9c](https://linux-hardware.org/?probe=3e8df8bd9c) | Nov 18, 2020 |
| Lenovo        | ThinkPad T530 2429AE1       | [07d8e71ce9](https://linux-hardware.org/?probe=07d8e71ce9) | Nov 18, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [ec114f6471](https://linux-hardware.org/?probe=ec114f6471) | Nov 18, 2020 |
| Google        | Celes                       | [6745b70f9d](https://linux-hardware.org/?probe=6745b70f9d) | Nov 18, 2020 |
| ASUSTek       | UX305UA                     | [f6e53adad1](https://linux-hardware.org/?probe=f6e53adad1) | Nov 18, 2020 |
| Dell          | XPS 15 9530                 | [498a6352ca](https://linux-hardware.org/?probe=498a6352ca) | Nov 17, 2020 |
| ASUSTek       | P53E                        | [d7d1d58006](https://linux-hardware.org/?probe=d7d1d58006) | Nov 17, 2020 |
| Acer          | Nitro AN515-54              | [6b6517fc84](https://linux-hardware.org/?probe=6b6517fc84) | Nov 17, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | [5f82a45024](https://linux-hardware.org/?probe=5f82a45024) | Nov 17, 2020 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [7b05bb837b](https://linux-hardware.org/?probe=7b05bb837b) | Nov 16, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [a3ffdab533](https://linux-hardware.org/?probe=a3ffdab533) | Nov 16, 2020 |
| Lenovo        | ThinkPad T530 24296HG       | [04b88a5f7b](https://linux-hardware.org/?probe=04b88a5f7b) | Nov 16, 2020 |
| HP            | EliteBook 2760p             | [ef3d5ea150](https://linux-hardware.org/?probe=ef3d5ea150) | Nov 15, 2020 |
| Toshiba       | Satellite Pro C655          | [58f0af0b39](https://linux-hardware.org/?probe=58f0af0b39) | Nov 14, 2020 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [d41338321f](https://linux-hardware.org/?probe=d41338321f) | Nov 14, 2020 |
| Dell          | XPS 15 7590                 | [5ac1223bbf](https://linux-hardware.org/?probe=5ac1223bbf) | Nov 14, 2020 |
| HP            | EliteBook Revolve 810       | [29b4740f0e](https://linux-hardware.org/?probe=29b4740f0e) | Nov 14, 2020 |
| HP            | EliteBook Revolve 810       | [fc46156f6d](https://linux-hardware.org/?probe=fc46156f6d) | Nov 14, 2020 |
| Lenovo        | ThinkPad T410s 2904CGU      | [271f9ac078](https://linux-hardware.org/?probe=271f9ac078) | Nov 14, 2020 |
| Dell          | Inspiron 3542               | [a61e523ec8](https://linux-hardware.org/?probe=a61e523ec8) | Nov 13, 2020 |
| Dell          | Inspiron 3542               | [3b32f13fb6](https://linux-hardware.org/?probe=3b32f13fb6) | Nov 13, 2020 |
| HP            | EliteBook 2760p             | [c95f2a55fc](https://linux-hardware.org/?probe=c95f2a55fc) | Nov 13, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0VK0... | [5f15747748](https://linux-hardware.org/?probe=5f15747748) | Nov 13, 2020 |
| Lenovo        | ThinkPad T430s 23571A3      | [9724440b38](https://linux-hardware.org/?probe=9724440b38) | Nov 12, 2020 |
| Dell          | Inspiron 3180               | [e9bec88a6c](https://linux-hardware.org/?probe=e9bec88a6c) | Nov 12, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop X40... | [843749d56e](https://linux-hardware.org/?probe=843749d56e) | Nov 12, 2020 |
| Lenovo        | ThinkPad T480s 20L8S7KH0... | [12db3bfed3](https://linux-hardware.org/?probe=12db3bfed3) | Nov 12, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | [7ab630580d](https://linux-hardware.org/?probe=7ab630580d) | Nov 12, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | [51e78e8b53](https://linux-hardware.org/?probe=51e78e8b53) | Nov 11, 2020 |
| Google        | Celes                       | [7b4eb00ecd](https://linux-hardware.org/?probe=7b4eb00ecd) | Nov 11, 2020 |
| ASUSTek       | T100TAS                     | [f735e14462](https://linux-hardware.org/?probe=f735e14462) | Nov 11, 2020 |
| Lenovo        | ThinkPad T480s 20L8S7PP0... | [4154403e2c](https://linux-hardware.org/?probe=4154403e2c) | Nov 11, 2020 |
| Lenovo        | ThinkPad T460p 20FW0044A... | [0001b76ceb](https://linux-hardware.org/?probe=0001b76ceb) | Nov 10, 2020 |
| Dell          | Inspiron N5010              | [7da18f5b92](https://linux-hardware.org/?probe=7da18f5b92) | Nov 10, 2020 |
| Dell          | Inspiron N5010              | [e543426587](https://linux-hardware.org/?probe=e543426587) | Nov 10, 2020 |
| Acer          | Aspire V3-772G              | [63b708b27b](https://linux-hardware.org/?probe=63b708b27b) | Nov 10, 2020 |
| HP            | Notebook                    | [636add61ed](https://linux-hardware.org/?probe=636add61ed) | Nov 10, 2020 |
| HP            | Notebook                    | [6b0502f1dd](https://linux-hardware.org/?probe=6b0502f1dd) | Nov 10, 2020 |
| ASUSTek       | X540LJ                      | [3a7e7932f2](https://linux-hardware.org/?probe=3a7e7932f2) | Nov 10, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [c4e3cf4d4b](https://linux-hardware.org/?probe=c4e3cf4d4b) | Nov 10, 2020 |
| HP            | EliteBook 745 G6            | [7aa5c86f85](https://linux-hardware.org/?probe=7aa5c86f85) | Nov 10, 2020 |
| Acer          | Nitro AN515-42              | [dc775bfd02](https://linux-hardware.org/?probe=dc775bfd02) | Nov 09, 2020 |
| Acer          | Nitro AN515-42              | [5bf122df5e](https://linux-hardware.org/?probe=5bf122df5e) | Nov 09, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [04dd6da950](https://linux-hardware.org/?probe=04dd6da950) | Nov 09, 2020 |
| Lenovo        | ThinkPad T480s 20L8S2SD0... | [441bbe5cf1](https://linux-hardware.org/?probe=441bbe5cf1) | Nov 09, 2020 |
| ASUSTek       | X705UDR                     | [ff4ee089ea](https://linux-hardware.org/?probe=ff4ee089ea) | Nov 09, 2020 |
| HP            | 420                         | [8b2ce5df27](https://linux-hardware.org/?probe=8b2ce5df27) | Nov 09, 2020 |
| Lenovo        | Legion Y540-15IRH 81SX      | [48c0e4bb1c](https://linux-hardware.org/?probe=48c0e4bb1c) | Nov 08, 2020 |
| ASUSTek       | GL753VD                     | [6d8ed717a3](https://linux-hardware.org/?probe=6d8ed717a3) | Nov 08, 2020 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [d98727e765](https://linux-hardware.org/?probe=d98727e765) | Nov 08, 2020 |
| Lenovo        | Legion 5P 15IMH05H 82AW     | [21105809e4](https://linux-hardware.org/?probe=21105809e4) | Nov 08, 2020 |
| Dell          | XPS 13 9370                 | [b75b281fee](https://linux-hardware.org/?probe=b75b281fee) | Nov 08, 2020 |
| Dell          | Inspiron 3583               | [855e73af05](https://linux-hardware.org/?probe=855e73af05) | Nov 08, 2020 |
| Dell          | Inspiron 3583               | [9fbfedabdb](https://linux-hardware.org/?probe=9fbfedabdb) | Nov 08, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [681c3073f9](https://linux-hardware.org/?probe=681c3073f9) | Nov 07, 2020 |
| Notebook      | P64_HJ,HK1                  | [9881503776](https://linux-hardware.org/?probe=9881503776) | Nov 07, 2020 |
| Google        | Celes                       | [8ecf8a2eef](https://linux-hardware.org/?probe=8ecf8a2eef) | Nov 07, 2020 |
| Chuwi         | LapBook SE                  | [8fbdedc1b9](https://linux-hardware.org/?probe=8fbdedc1b9) | Nov 06, 2020 |
| Dell          | Latitude 5411               | [e880b200a0](https://linux-hardware.org/?probe=e880b200a0) | Nov 06, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [76967badfe](https://linux-hardware.org/?probe=76967badfe) | Nov 06, 2020 |
| Lenovo        | ThinkPad E570 20H5CTO1WW    | [82ca1d68cf](https://linux-hardware.org/?probe=82ca1d68cf) | Nov 05, 2020 |
| Lenovo        | ThinkPad T470s 20HGS33N0... | [46e54eb12c](https://linux-hardware.org/?probe=46e54eb12c) | Nov 05, 2020 |
| Dell          | Inspiron 5423               | [2ce968af69](https://linux-hardware.org/?probe=2ce968af69) | Nov 05, 2020 |
| ASUSTek       | G74Sx                       | [35a8e0845e](https://linux-hardware.org/?probe=35a8e0845e) | Nov 05, 2020 |
| Lenovo        | ThinkPad T61 7663BL3        | [412e6eca38](https://linux-hardware.org/?probe=412e6eca38) | Nov 05, 2020 |
| Lenovo        | ThinkPad T61 7663BL3        | [6fb42db6e5](https://linux-hardware.org/?probe=6fb42db6e5) | Nov 05, 2020 |
| Samsung       | N150/N210/N220              | [fd176dd130](https://linux-hardware.org/?probe=fd176dd130) | Nov 05, 2020 |
| Dell          | Inspiron 3442               | [3e1ef3d0d5](https://linux-hardware.org/?probe=3e1ef3d0d5) | Nov 05, 2020 |
| Dell          | Inspiron 3442               | [91e0e72594](https://linux-hardware.org/?probe=91e0e72594) | Nov 05, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [3440ac4e77](https://linux-hardware.org/?probe=3440ac4e77) | Nov 05, 2020 |
| Lenovo        | ThinkPad L380 20M5CTO1WW    | [ddb7ee8ea5](https://linux-hardware.org/?probe=ddb7ee8ea5) | Nov 04, 2020 |
| HP            | Laptop 15-dw1xxx            | [91e0e6c6bc](https://linux-hardware.org/?probe=91e0e6c6bc) | Nov 04, 2020 |
| Dell          | XPS 13 9380                 | [3d7eeaaa37](https://linux-hardware.org/?probe=3d7eeaaa37) | Nov 03, 2020 |
| Lenovo        | ThinkPad L380 20M5CTO1WW    | [27cff0ca67](https://linux-hardware.org/?probe=27cff0ca67) | Nov 03, 2020 |
| Lenovo        | ThinkPad T400 6474AH5       | [e587049ce7](https://linux-hardware.org/?probe=e587049ce7) | Nov 02, 2020 |
| Lenovo        | ThinkPad P53 20QNCTO1WW     | [318f5595fc](https://linux-hardware.org/?probe=318f5595fc) | Nov 02, 2020 |
| Unknown       | Unknown                     | [4c80913adb](https://linux-hardware.org/?probe=4c80913adb) | Nov 02, 2020 |
| Lenovo        | ThinkPad T420 4178C9U       | [f535361119](https://linux-hardware.org/?probe=f535361119) | Nov 01, 2020 |
| Lenovo        | IdeaPad 330S-14AST 81F8     | [c481bfe017](https://linux-hardware.org/?probe=c481bfe017) | Nov 01, 2020 |
| Toshiba       | Satellite L500              | [58911831e9](https://linux-hardware.org/?probe=58911831e9) | Nov 01, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [0b3fe9a6f2](https://linux-hardware.org/?probe=0b3fe9a6f2) | Nov 01, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [49bc5032be](https://linux-hardware.org/?probe=49bc5032be) | Nov 01, 2020 |
| Lenovo        | ThinkPad T480s 20L8S7PP0... | [defeca094b](https://linux-hardware.org/?probe=defeca094b) | Oct 31, 2020 |
| Lenovo        | Z50-70 20354                | [b252d0ad02](https://linux-hardware.org/?probe=b252d0ad02) | Oct 31, 2020 |
| HP            | EliteBook 2530p             | [c384fe6c1c](https://linux-hardware.org/?probe=c384fe6c1c) | Oct 31, 2020 |
| Dell          | Latitude E4300              | [2cd7ae1a0e](https://linux-hardware.org/?probe=2cd7ae1a0e) | Oct 30, 2020 |
| ASUSTek       | X556UQK                     | [c05de50902](https://linux-hardware.org/?probe=c05de50902) | Oct 30, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [c03ca44bcf](https://linux-hardware.org/?probe=c03ca44bcf) | Oct 30, 2020 |
| Timi          | TM1604                      | [e1106c1a68](https://linux-hardware.org/?probe=e1106c1a68) | Oct 30, 2020 |
| ASUSTek       | UX32VD                      | [6c9095c4b8](https://linux-hardware.org/?probe=6c9095c4b8) | Oct 30, 2020 |
| ASUSTek       | X556UQK                     | [18b5d78bf7](https://linux-hardware.org/?probe=18b5d78bf7) | Oct 29, 2020 |
| Google        | Link                        | [d62d93631a](https://linux-hardware.org/?probe=d62d93631a) | Oct 29, 2020 |
| Lenovo        | ThinkPad X250 20CMS09M00    | [bdabcfce6f](https://linux-hardware.org/?probe=bdabcfce6f) | Oct 29, 2020 |
| Dell          | Latitude 5480               | [356ef986cc](https://linux-hardware.org/?probe=356ef986cc) | Oct 29, 2020 |
| Dell          | Latitude 5480               | [ecc79d59e4](https://linux-hardware.org/?probe=ecc79d59e4) | Oct 29, 2020 |
| Lenovo        | ThinkPad X230 Tablet 343... | [516ff504f0](https://linux-hardware.org/?probe=516ff504f0) | Oct 29, 2020 |
| Lenovo        | ThinkPad T430 23501K0       | [cbaf077bd3](https://linux-hardware.org/?probe=cbaf077bd3) | Oct 29, 2020 |
| Lenovo        | ThinkPad T430 23501K0       | [604548bcb1](https://linux-hardware.org/?probe=604548bcb1) | Oct 29, 2020 |
| Lenovo        | ThinkPad T430 23501K0       | [ab43860392](https://linux-hardware.org/?probe=ab43860392) | Oct 29, 2020 |
| HP            | 15                          | [8ebe037b8f](https://linux-hardware.org/?probe=8ebe037b8f) | Oct 29, 2020 |
| HP            | EliteBook 830 G6            | [dc7b299eaf](https://linux-hardware.org/?probe=dc7b299eaf) | Oct 28, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [d992d44e88](https://linux-hardware.org/?probe=d992d44e88) | Oct 28, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [faa055219d](https://linux-hardware.org/?probe=faa055219d) | Oct 28, 2020 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [f6c5e1d108](https://linux-hardware.org/?probe=f6c5e1d108) | Oct 28, 2020 |
| Dell          | XPS 15 9500                 | [8830a8b145](https://linux-hardware.org/?probe=8830a8b145) | Oct 28, 2020 |
| Lenovo        | ThinkPad T420s 4170CTO      | [b7de4955fc](https://linux-hardware.org/?probe=b7de4955fc) | Oct 27, 2020 |
| Lenovo        | ThinkPad T420s 4170CTO      | [656624cd9e](https://linux-hardware.org/?probe=656624cd9e) | Oct 27, 2020 |
| Dell          | Inspiron 3542               | [890ddf1809](https://linux-hardware.org/?probe=890ddf1809) | Oct 27, 2020 |
| MSI           | GE62VR 6RF                  | [6a35da088e](https://linux-hardware.org/?probe=6a35da088e) | Oct 27, 2020 |
| Dell          | XPS 13 9300                 | [dc071d5960](https://linux-hardware.org/?probe=dc071d5960) | Oct 27, 2020 |
| Lenovo        | ThinkPad T480s 20L8S2SD0... | [e7f1242947](https://linux-hardware.org/?probe=e7f1242947) | Oct 27, 2020 |
| Lenovo        | ThinkPad T480 20L5000BRT    | [0a8e79d72b](https://linux-hardware.org/?probe=0a8e79d72b) | Oct 26, 2020 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [6f98575351](https://linux-hardware.org/?probe=6f98575351) | Oct 26, 2020 |
| Lenovo        | ThinkPad T460p 20FWCTO1W... | [36f0c4669c](https://linux-hardware.org/?probe=36f0c4669c) | Oct 25, 2020 |
| Acer          | Aspire V3-772               | [1e355bb7fa](https://linux-hardware.org/?probe=1e355bb7fa) | Oct 25, 2020 |
| HP            | OMEN by Laptop              | [648bb29d40](https://linux-hardware.org/?probe=648bb29d40) | Oct 25, 2020 |
| Packard Be... | EasyNote MZ45               | [5a75a151a8](https://linux-hardware.org/?probe=5a75a151a8) | Oct 25, 2020 |
| HP            | ProBook 455 G7              | [e78b8a0028](https://linux-hardware.org/?probe=e78b8a0028) | Oct 25, 2020 |
| Dell          | XPS 13 9380                 | [70a8f0f066](https://linux-hardware.org/?probe=70a8f0f066) | Oct 24, 2020 |
| HP            | Notebook                    | [92da656432](https://linux-hardware.org/?probe=92da656432) | Oct 24, 2020 |
| HP            | Notebook                    | [f32d81a789](https://linux-hardware.org/?probe=f32d81a789) | Oct 24, 2020 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [e8b5c9cb6b](https://linux-hardware.org/?probe=e8b5c9cb6b) | Oct 24, 2020 |
| MSI           | Modern 14 B10MW             | [ad7f190464](https://linux-hardware.org/?probe=ad7f190464) | Oct 23, 2020 |
| MECHREVO      | Code 01 Series PF5NU1G      | [ad8c53bb70](https://linux-hardware.org/?probe=ad8c53bb70) | Oct 22, 2020 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [a5a9e99d05](https://linux-hardware.org/?probe=a5a9e99d05) | Oct 22, 2020 |
| HP            | EliteBook x360 1040 G5      | [118974f05c](https://linux-hardware.org/?probe=118974f05c) | Oct 22, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [e1692333bf](https://linux-hardware.org/?probe=e1692333bf) | Oct 22, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [526bac536d](https://linux-hardware.org/?probe=526bac536d) | Oct 22, 2020 |
| Dell          | System Inspiron N411Z       | [427836f8d3](https://linux-hardware.org/?probe=427836f8d3) | Oct 22, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [6605efe469](https://linux-hardware.org/?probe=6605efe469) | Oct 21, 2020 |
| MSI           | Bravo 15 A4DDR              | [d46c023011](https://linux-hardware.org/?probe=d46c023011) | Oct 21, 2020 |
| ASUSTek       | P453UA                      | [a376addbeb](https://linux-hardware.org/?probe=a376addbeb) | Oct 21, 2020 |
| Dell          | Inspiron N5010              | [6b6c9f021f](https://linux-hardware.org/?probe=6b6c9f021f) | Oct 21, 2020 |
| Dell          | Inspiron N5010              | [5238ba6d8e](https://linux-hardware.org/?probe=5238ba6d8e) | Oct 21, 2020 |
| HP            | ZBook Studio G5             | [d37cbd44aa](https://linux-hardware.org/?probe=d37cbd44aa) | Oct 20, 2020 |
| ASUSTek       | U47A                        | [b7c3bb57cf](https://linux-hardware.org/?probe=b7c3bb57cf) | Oct 20, 2020 |
| HP            | ZHAN 66 Pro G1              | [f7e9f8ad3f](https://linux-hardware.org/?probe=f7e9f8ad3f) | Oct 19, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [8852b44f29](https://linux-hardware.org/?probe=8852b44f29) | Oct 19, 2020 |
| Fujitsu       | LIFEBOOK S710               | [fa8314c368](https://linux-hardware.org/?probe=fa8314c368) | Oct 19, 2020 |
| MSI           | PE70 6QE                    | [8c3ccf4956](https://linux-hardware.org/?probe=8c3ccf4956) | Oct 19, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [4713621a5a](https://linux-hardware.org/?probe=4713621a5a) | Oct 19, 2020 |
| Lenovo        | 10017                       | [0812a4efc1](https://linux-hardware.org/?probe=0812a4efc1) | Oct 19, 2020 |
| Lenovo        | IdeaPad S340-15API 81NC     | [b26f19cc58](https://linux-hardware.org/?probe=b26f19cc58) | Oct 18, 2020 |
| HP            | ZHAN 66 Pro G1              | [d5564091b0](https://linux-hardware.org/?probe=d5564091b0) | Oct 18, 2020 |
| HP            | EliteBook 8470p             | [1a049977b7](https://linux-hardware.org/?probe=1a049977b7) | Oct 18, 2020 |
| HP            | OMEN by Laptop              | [c2f4f40a20](https://linux-hardware.org/?probe=c2f4f40a20) | Oct 18, 2020 |
| HP            | Pavilion dv6                | [3ada1420d3](https://linux-hardware.org/?probe=3ada1420d3) | Oct 18, 2020 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | [d7c4496b69](https://linux-hardware.org/?probe=d7c4496b69) | Oct 17, 2020 |
| Dell          | XPS 15 9500                 | [38048dd7f1](https://linux-hardware.org/?probe=38048dd7f1) | Oct 17, 2020 |
| Lenovo        | ThinkPad T460p 20FW0044A... | [8720432e33](https://linux-hardware.org/?probe=8720432e33) | Oct 16, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [1491dd3d5b](https://linux-hardware.org/?probe=1491dd3d5b) | Oct 16, 2020 |
| Acer          | Swift SF314-57              | [c49aa23f27](https://linux-hardware.org/?probe=c49aa23f27) | Oct 16, 2020 |
| Acer          | Swift SF314-57              | [3646c1a6a3](https://linux-hardware.org/?probe=3646c1a6a3) | Oct 16, 2020 |
| Dell          | G3 3500                     | [5cb1ce307e](https://linux-hardware.org/?probe=5cb1ce307e) | Oct 16, 2020 |
| Lenovo        | IdeaPad 320-15IKB 81G3      | [24700ea99c](https://linux-hardware.org/?probe=24700ea99c) | Oct 16, 2020 |
| Dell          | Latitude 3350               | [4cd708305e](https://linux-hardware.org/?probe=4cd708305e) | Oct 15, 2020 |
| Dell          | XPS 15 9575                 | [fc1be75c85](https://linux-hardware.org/?probe=fc1be75c85) | Oct 15, 2020 |
| Novatech      | A15A/HE/HC                  | [44dff7f4a3](https://linux-hardware.org/?probe=44dff7f4a3) | Oct 15, 2020 |
| Lenovo        | IdeaPad Slim 7 14IIL05 8... | [b0b94af1b5](https://linux-hardware.org/?probe=b0b94af1b5) | Oct 15, 2020 |
| 51nb          | X210                        | [431ebffab8](https://linux-hardware.org/?probe=431ebffab8) | Oct 15, 2020 |
| ASUSTek       | X550CC                      | [6379bf0f07](https://linux-hardware.org/?probe=6379bf0f07) | Oct 14, 2020 |
| Acer          | Predator PH315-52           | [d8c809c598](https://linux-hardware.org/?probe=d8c809c598) | Oct 14, 2020 |
| Apple         | MacBookAir4,2               | [9924876508](https://linux-hardware.org/?probe=9924876508) | Oct 14, 2020 |
| Acer          | Predator G3-571             | [8a5037db6b](https://linux-hardware.org/?probe=8a5037db6b) | Oct 14, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [34ddf62c5a](https://linux-hardware.org/?probe=34ddf62c5a) | Oct 14, 2020 |
| Acer          | Aspire ES1-572              | [01c897b031](https://linux-hardware.org/?probe=01c897b031) | Oct 14, 2020 |
| Dell          | Inspiron 3180               | [a265161401](https://linux-hardware.org/?probe=a265161401) | Oct 14, 2020 |
| Acer          | Aspire ES1-572              | [a976cbfe68](https://linux-hardware.org/?probe=a976cbfe68) | Oct 13, 2020 |
| Dell          | Inspiron 15-5578            | [c407fb473e](https://linux-hardware.org/?probe=c407fb473e) | Oct 13, 2020 |
| ASUSTek       | TUF Gaming FA506II_FA506... | [9356879a60](https://linux-hardware.org/?probe=9356879a60) | Oct 13, 2020 |
| Acer          | Aspire E5-571               | [3f640876ce](https://linux-hardware.org/?probe=3f640876ce) | Oct 13, 2020 |
| HP            | Laptop 15-da1xxx            | [88b6f3e1ab](https://linux-hardware.org/?probe=88b6f3e1ab) | Oct 13, 2020 |
| Lenovo        | ThinkPad T580 20L90026RT    | [a814ed9bb5](https://linux-hardware.org/?probe=a814ed9bb5) | Oct 13, 2020 |
| Notebook      | N8xEJEK                     | [e6e3ed79bc](https://linux-hardware.org/?probe=e6e3ed79bc) | Oct 13, 2020 |
| HP            | ProBook 445 G7              | [d915bbd395](https://linux-hardware.org/?probe=d915bbd395) | Oct 12, 2020 |
| MSI           | PE70 6QE                    | [1691661a18](https://linux-hardware.org/?probe=1691661a18) | Oct 12, 2020 |
| Lenovo        | ThinkPad Helix MFG_IN       | [d18f772e79](https://linux-hardware.org/?probe=d18f772e79) | Oct 12, 2020 |
| HP            | EliteBook 840 G5            | [ce9d88fc35](https://linux-hardware.org/?probe=ce9d88fc35) | Oct 12, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [e8f0459471](https://linux-hardware.org/?probe=e8f0459471) | Oct 11, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [e0d54e69ff](https://linux-hardware.org/?probe=e0d54e69ff) | Oct 11, 2020 |
| Acer          | Aspire 7738                 | [d7948db850](https://linux-hardware.org/?probe=d7948db850) | Oct 11, 2020 |
| Acer          | Aspire 7738                 | [ffe98b7af3](https://linux-hardware.org/?probe=ffe98b7af3) | Oct 11, 2020 |
| MSI           | GL62 7RD                    | [554bd8d782](https://linux-hardware.org/?probe=554bd8d782) | Oct 11, 2020 |
| MSI           | GL62 7RD                    | [6bc56d2ba7](https://linux-hardware.org/?probe=6bc56d2ba7) | Oct 11, 2020 |
| Eluktronic... | THINN-15                    | [183cf86941](https://linux-hardware.org/?probe=183cf86941) | Oct 11, 2020 |
| Eluktronic... | THINN-15                    | [b7d1368bb5](https://linux-hardware.org/?probe=b7d1368bb5) | Oct 11, 2020 |
| HP            | ZHAN 66 Pro G1              | [2dd4ba952c](https://linux-hardware.org/?probe=2dd4ba952c) | Oct 10, 2020 |
| Dell          | Vostro 1015                 | [ca936265ce](https://linux-hardware.org/?probe=ca936265ce) | Oct 10, 2020 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [58d860d2b8](https://linux-hardware.org/?probe=58d860d2b8) | Oct 09, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [825f3a623e](https://linux-hardware.org/?probe=825f3a623e) | Oct 09, 2020 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [820ad028ce](https://linux-hardware.org/?probe=820ad028ce) | Oct 09, 2020 |
| HP            | EliteBook x360 1040 G5      | [0c8712a97d](https://linux-hardware.org/?probe=0c8712a97d) | Oct 08, 2020 |
| Dell          | Latitude 5490               | [2695de70f7](https://linux-hardware.org/?probe=2695de70f7) | Oct 08, 2020 |
| Dell          | XPS 13 9380                 | [f1ec778131](https://linux-hardware.org/?probe=f1ec778131) | Oct 08, 2020 |
| Apple         | MacBookPro15,1              | [d1bf2547ae](https://linux-hardware.org/?probe=d1bf2547ae) | Oct 07, 2020 |
| Apple         | MacBookPro15,1              | [9782f126d8](https://linux-hardware.org/?probe=9782f126d8) | Oct 07, 2020 |
| Dell          | G3 3579                     | [f92b4feea2](https://linux-hardware.org/?probe=f92b4feea2) | Oct 07, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [ddcde88c3c](https://linux-hardware.org/?probe=ddcde88c3c) | Oct 07, 2020 |
| Dell          | G3 3579                     | [8db7cab8f9](https://linux-hardware.org/?probe=8db7cab8f9) | Oct 07, 2020 |
| Lenovo        | ThinkPad X230 2325SSF       | [e4b06fc3af](https://linux-hardware.org/?probe=e4b06fc3af) | Oct 07, 2020 |
| Lenovo        | V330-14ARR 81B1             | [62310522c0](https://linux-hardware.org/?probe=62310522c0) | Oct 07, 2020 |
| HP            | ZHAN 66 Pro G1              | [43935519f5](https://linux-hardware.org/?probe=43935519f5) | Oct 06, 2020 |
| Dell          | Inspiron 3180               | [d9ef314d15](https://linux-hardware.org/?probe=d9ef314d15) | Oct 06, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [e09a6ea5c4](https://linux-hardware.org/?probe=e09a6ea5c4) | Oct 05, 2020 |
| Dell          | Vostro 1015                 | [229eb116c1](https://linux-hardware.org/?probe=229eb116c1) | Oct 05, 2020 |
| HP            | ZHAN 66 Pro G1              | [10e7dd93c4](https://linux-hardware.org/?probe=10e7dd93c4) | Oct 04, 2020 |
| Schenker      | XMG CORE 17(M20, RTX 206... | [5a8e589b6c](https://linux-hardware.org/?probe=5a8e589b6c) | Oct 04, 2020 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [47c12da0bc](https://linux-hardware.org/?probe=47c12da0bc) | Oct 03, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [513e2509b4](https://linux-hardware.org/?probe=513e2509b4) | Oct 03, 2020 |
| HP            | ZHAN 66 Pro G1              | [d066fbf3a0](https://linux-hardware.org/?probe=d066fbf3a0) | Oct 02, 2020 |
| Dell          | Latitude D820               | [ae1fa80f73](https://linux-hardware.org/?probe=ae1fa80f73) | Oct 02, 2020 |
| Dell          | Precision 5520              | [c7cf5ea90e](https://linux-hardware.org/?probe=c7cf5ea90e) | Oct 02, 2020 |
| Dell          | XPS 13 9360                 | [fc05378a10](https://linux-hardware.org/?probe=fc05378a10) | Oct 02, 2020 |
| ASUSTek       | X510UQ                      | [75933321b6](https://linux-hardware.org/?probe=75933321b6) | Oct 02, 2020 |
| Dell          | Inspiron 7572               | [7624ab2529](https://linux-hardware.org/?probe=7624ab2529) | Oct 02, 2020 |
| ASUSTek       | G53SW                       | [cb9eb22047](https://linux-hardware.org/?probe=cb9eb22047) | Oct 02, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [06cc9298b0](https://linux-hardware.org/?probe=06cc9298b0) | Oct 02, 2020 |
| HP            | ENVY Laptop 15-ep0xxx       | [991dcf8dae](https://linux-hardware.org/?probe=991dcf8dae) | Oct 01, 2020 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [f9f212a509](https://linux-hardware.org/?probe=f9f212a509) | Oct 01, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [73218ced29](https://linux-hardware.org/?probe=73218ced29) | Oct 01, 2020 |
| Lenovo        | ThinkPad E580 20KS006GUK    | [43cd14b799](https://linux-hardware.org/?probe=43cd14b799) | Oct 01, 2020 |
| Dell          | Inspiron 15-5578            | [6cce1fbf9c](https://linux-hardware.org/?probe=6cce1fbf9c) | Sep 30, 2020 |
| Acer          | TravelMate B117-M           | [0d658847c1](https://linux-hardware.org/?probe=0d658847c1) | Sep 30, 2020 |
| Lenovo        | ThinkPad T500 2089W6A       | [62adf41a4a](https://linux-hardware.org/?probe=62adf41a4a) | Sep 30, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [582a247b73](https://linux-hardware.org/?probe=582a247b73) | Sep 30, 2020 |
| HUAWEI        | BOHK-WAX9X                  | [f6eb8cdb32](https://linux-hardware.org/?probe=f6eb8cdb32) | Sep 30, 2020 |
| ASUSTek       | K72Jr                       | [1cf0357bcf](https://linux-hardware.org/?probe=1cf0357bcf) | Sep 29, 2020 |
| HP            | Notebook                    | [0ad6264bdf](https://linux-hardware.org/?probe=0ad6264bdf) | Sep 29, 2020 |
| ASUSTek       | ZenBook UX434FAC_UX433FA... | [28aa6ce10e](https://linux-hardware.org/?probe=28aa6ce10e) | Sep 29, 2020 |
| HP            | 250 G6 Notebook PC          | [bf895835ad](https://linux-hardware.org/?probe=bf895835ad) | Sep 29, 2020 |
| HUAWEI        | MACH-WX9                    | [73668957cf](https://linux-hardware.org/?probe=73668957cf) | Sep 29, 2020 |
| Lenovo        | ThinkPad E495 20NECTO1WW    | [d05fedd2c6](https://linux-hardware.org/?probe=d05fedd2c6) | Sep 29, 2020 |
| Dell          | XPS 15 7590                 | [21e9d3a50f](https://linux-hardware.org/?probe=21e9d3a50f) | Sep 29, 2020 |
| Lenovo        | IdeaPad Z500 20202          | [3c6ab16d6f](https://linux-hardware.org/?probe=3c6ab16d6f) | Sep 29, 2020 |
| Lenovo        | ThinkPad T440p 20AWS1HE0... | [cda2001ea0](https://linux-hardware.org/?probe=cda2001ea0) | Sep 29, 2020 |
| Dell          | XPS 13 9370                 | [f5a66c82e5](https://linux-hardware.org/?probe=f5a66c82e5) | Sep 29, 2020 |
| Lenovo        | ThinkPad T480 20L5S01J00    | [c6285ca7b6](https://linux-hardware.org/?probe=c6285ca7b6) | Sep 29, 2020 |
| Dell          | XPS M1530                   | [dc08069215](https://linux-hardware.org/?probe=dc08069215) | Sep 29, 2020 |
| Dell          | Inspiron 3583               | [5f2d468001](https://linux-hardware.org/?probe=5f2d468001) | Sep 29, 2020 |
| Dell          | XPS 13 9370                 | [4859c81afa](https://linux-hardware.org/?probe=4859c81afa) | Sep 29, 2020 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [ab3bdfbb48](https://linux-hardware.org/?probe=ab3bdfbb48) | Sep 29, 2020 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [8328a535a2](https://linux-hardware.org/?probe=8328a535a2) | Sep 29, 2020 |
| Lenovo        | ThinkPad E495 20NE001TMX    | [fe24c7efc7](https://linux-hardware.org/?probe=fe24c7efc7) | Sep 28, 2020 |
| HP            | Pavilion Power Laptop 15... | [6f97a1bc53](https://linux-hardware.org/?probe=6f97a1bc53) | Sep 28, 2020 |
| Lenovo        | ThinkPad T495 20NKS08G00    | [a067aa71d0](https://linux-hardware.org/?probe=a067aa71d0) | Sep 28, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [03af73e317](https://linux-hardware.org/?probe=03af73e317) | Sep 28, 2020 |
| ASUSTek       | K52JT                       | [2acb54cb0d](https://linux-hardware.org/?probe=2acb54cb0d) | Sep 28, 2020 |
| HP            | EliteBook 830 G6            | [f3313ab891](https://linux-hardware.org/?probe=f3313ab891) | Sep 28, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [fb0b39218e](https://linux-hardware.org/?probe=fb0b39218e) | Sep 28, 2020 |
| Dell          | Latitude E7450              | [0350e7f8c5](https://linux-hardware.org/?probe=0350e7f8c5) | Sep 28, 2020 |
| ASUSTek       | X510UQR                     | [de4940d184](https://linux-hardware.org/?probe=de4940d184) | Sep 28, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0KK0... | [d231920967](https://linux-hardware.org/?probe=d231920967) | Sep 28, 2020 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [5339666aad](https://linux-hardware.org/?probe=5339666aad) | Sep 28, 2020 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [527e753269](https://linux-hardware.org/?probe=527e753269) | Sep 28, 2020 |
| HP            | OMEN Laptop 15-en0xxx       | [397513d6dc](https://linux-hardware.org/?probe=397513d6dc) | Sep 28, 2020 |
| Monster       | Unknown                     | [f4bd2dd3fe](https://linux-hardware.org/?probe=f4bd2dd3fe) | Sep 28, 2020 |
| Dell          | Inspiron 5567               | [7aa5b3ca83](https://linux-hardware.org/?probe=7aa5b3ca83) | Sep 28, 2020 |
| Lenovo        | ThinkPad W541 20EGS03101    | [b0fe42deef](https://linux-hardware.org/?probe=b0fe42deef) | Sep 28, 2020 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [e02b125ebc](https://linux-hardware.org/?probe=e02b125ebc) | Sep 28, 2020 |
| ASUSTek       | K55VD                       | [42170c6ff1](https://linux-hardware.org/?probe=42170c6ff1) | Sep 28, 2020 |
| Lenovo        | ThinkPad T530 2429AE1       | [111f79b909](https://linux-hardware.org/?probe=111f79b909) | Sep 28, 2020 |
| ASUSTek       | X550JK                      | [66d74bcdcd](https://linux-hardware.org/?probe=66d74bcdcd) | Sep 28, 2020 |
| Unknown       | Unknown                     | [f7ca0ed673](https://linux-hardware.org/?probe=f7ca0ed673) | Sep 28, 2020 |
| Lenovo        | ThinkPad X230 2320B3V       | [fc3c575752](https://linux-hardware.org/?probe=fc3c575752) | Sep 27, 2020 |
| HP            | ProBook 455 G7              | [62da42ec3c](https://linux-hardware.org/?probe=62da42ec3c) | Sep 27, 2020 |
| Dell          | Inspiron 3583               | [f35e5bb46b](https://linux-hardware.org/?probe=f35e5bb46b) | Sep 27, 2020 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [1e07f4e360](https://linux-hardware.org/?probe=1e07f4e360) | Sep 27, 2020 |
| ASUSTek       | ROG Zephyrus G15 GA502IV... | [26c49850ea](https://linux-hardware.org/?probe=26c49850ea) | Sep 27, 2020 |
| Dell          | Inspiron 3580               | [ee71f44aa5](https://linux-hardware.org/?probe=ee71f44aa5) | Sep 26, 2020 |
| ASUSTek       | GL502VSK                    | [f9028267d2](https://linux-hardware.org/?probe=f9028267d2) | Sep 26, 2020 |
| Lenovo        | ThinkPad E550 20DF0011UE    | [6707f14d96](https://linux-hardware.org/?probe=6707f14d96) | Sep 26, 2020 |
| Dell          | Vostro 1015                 | [f8815a41c3](https://linux-hardware.org/?probe=f8815a41c3) | Sep 26, 2020 |
| ASUSTek       | ROG Zephyrus G15 GA502IV... | [b849506743](https://linux-hardware.org/?probe=b849506743) | Sep 26, 2020 |
| Dell          | Inspiron 3580               | [399c4fb6d6](https://linux-hardware.org/?probe=399c4fb6d6) | Sep 26, 2020 |
| Acer          | Iconia W700                 | [2b49917dd2](https://linux-hardware.org/?probe=2b49917dd2) | Sep 25, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [70a3828248](https://linux-hardware.org/?probe=70a3828248) | Sep 25, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [36a242f9fd](https://linux-hardware.org/?probe=36a242f9fd) | Sep 25, 2020 |
| HP            | ProBook 455 G7              | [b2cdadc21e](https://linux-hardware.org/?probe=b2cdadc21e) | Sep 25, 2020 |
| Dell          | Inspiron 15-3567            | [46a59c8725](https://linux-hardware.org/?probe=46a59c8725) | Sep 25, 2020 |
| Lenovo        | IdeaPadFlex 14 20308        | [f89ea52852](https://linux-hardware.org/?probe=f89ea52852) | Sep 24, 2020 |
| Dell          | Latitude 5491               | [e386dcf4f4](https://linux-hardware.org/?probe=e386dcf4f4) | Sep 24, 2020 |
| Lenovo        | ThinkPad X260 20F5S08P00    | [8d61a73a3e](https://linux-hardware.org/?probe=8d61a73a3e) | Sep 24, 2020 |
| Toshiba       | Satellite C650              | [29cd216c62](https://linux-hardware.org/?probe=29cd216c62) | Sep 23, 2020 |
| Acer          | TravelMate P614-51TG        | [e0fbefb33a](https://linux-hardware.org/?probe=e0fbefb33a) | Sep 23, 2020 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [21c296dde3](https://linux-hardware.org/?probe=21c296dde3) | Sep 22, 2020 |
| Lenovo        | ThinkPad L390 20NSS1XF00    | [8bb96d9902](https://linux-hardware.org/?probe=8bb96d9902) | Sep 22, 2020 |
| Lenovo        | ThinkPad L390 20NSS1XF00    | [ce306a7fa2](https://linux-hardware.org/?probe=ce306a7fa2) | Sep 22, 2020 |
| Dell          | XPS 15 9550                 | [25873c8158](https://linux-hardware.org/?probe=25873c8158) | Sep 22, 2020 |
| Dell          | Inspiron 13-7359            | [5f15030f71](https://linux-hardware.org/?probe=5f15030f71) | Sep 22, 2020 |
| Dell          | Inspiron 7560               | [bd75024215](https://linux-hardware.org/?probe=bd75024215) | Sep 22, 2020 |
| Dell          | Inspiron 7560               | [32aed04ac2](https://linux-hardware.org/?probe=32aed04ac2) | Sep 22, 2020 |
| Lenovo        | ThinkPad T460p 20FW0044A... | [616e26ca49](https://linux-hardware.org/?probe=616e26ca49) | Sep 20, 2020 |
| ASUSTek       | X556URK                     | [1c0033b367](https://linux-hardware.org/?probe=1c0033b367) | Sep 20, 2020 |
| Lenovo        | IdeaPad 530S-15IKB 81EV     | [25a18b6913](https://linux-hardware.org/?probe=25a18b6913) | Sep 20, 2020 |
| ASUSTek       | UX550VE                     | [f538a53c10](https://linux-hardware.org/?probe=f538a53c10) | Sep 20, 2020 |
| Lenovo        | IdeaPad Y580                | [d4dcb0a3cc](https://linux-hardware.org/?probe=d4dcb0a3cc) | Sep 20, 2020 |
| HP            | EliteBook 6930p             | [0de41272d6](https://linux-hardware.org/?probe=0de41272d6) | Sep 20, 2020 |
| HP            | EliteBook 6930p             | [c2f09d7bd9](https://linux-hardware.org/?probe=c2f09d7bd9) | Sep 20, 2020 |
| Notebook      | W350STQ/W370ST              | [3662070925](https://linux-hardware.org/?probe=3662070925) | Sep 20, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [01bef6eb46](https://linux-hardware.org/?probe=01bef6eb46) | Sep 20, 2020 |
| Acer          | Aspire E5-575               | [54521bfc7d](https://linux-hardware.org/?probe=54521bfc7d) | Sep 19, 2020 |
| Apple         | MacBookPro6,2               | [fcaec2f33f](https://linux-hardware.org/?probe=fcaec2f33f) | Sep 19, 2020 |
| HUAWEI        | NBLK-WAX9X                  | [0bdb1c03a9](https://linux-hardware.org/?probe=0bdb1c03a9) | Sep 18, 2020 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [c27c169cc3](https://linux-hardware.org/?probe=c27c169cc3) | Sep 17, 2020 |
| HP            | OMEN by Laptop 15-dc0xxx    | [1662a9985d](https://linux-hardware.org/?probe=1662a9985d) | Sep 17, 2020 |
| Apple         | MacBookPro12,1              | [d766064036](https://linux-hardware.org/?probe=d766064036) | Sep 17, 2020 |
| Lenovo        | ThinkPad X230 2325SSF       | [087fa4f531](https://linux-hardware.org/?probe=087fa4f531) | Sep 17, 2020 |
| Dell          | Inspiron 5576               | [2f26661677](https://linux-hardware.org/?probe=2f26661677) | Sep 17, 2020 |
| Dell          | Precision 7710              | [1e58b4271d](https://linux-hardware.org/?probe=1e58b4271d) | Sep 16, 2020 |
| Dell          | Precision 7710              | [7821b2dffc](https://linux-hardware.org/?probe=7821b2dffc) | Sep 16, 2020 |
| Dell          | XPS 15 9550                 | [4b695b4b07](https://linux-hardware.org/?probe=4b695b4b07) | Sep 16, 2020 |
| Lenovo        | ThinkPad T470p 20J60015G... | [ef86b9ba5e](https://linux-hardware.org/?probe=ef86b9ba5e) | Sep 16, 2020 |
| Dell          | Inspiron 3558               | [7ce8166884](https://linux-hardware.org/?probe=7ce8166884) | Sep 16, 2020 |
| Lenovo        | ThinkPad T430s 2356G28      | [25712d0e61](https://linux-hardware.org/?probe=25712d0e61) | Sep 16, 2020 |
| Lenovo        | Legion R7000P2020H 82GR     | [dae1221cfd](https://linux-hardware.org/?probe=dae1221cfd) | Sep 16, 2020 |
| HUAWEI        | HLY-WX9XX                   | [55bf2ea24a](https://linux-hardware.org/?probe=55bf2ea24a) | Sep 16, 2020 |
| Acer          | Aspire A315-41              | [84a64864b6](https://linux-hardware.org/?probe=84a64864b6) | Sep 15, 2020 |
| Toshiba       | Satellite T135D             | [924f6ab4d4](https://linux-hardware.org/?probe=924f6ab4d4) | Sep 15, 2020 |
| HP            | OMEN Laptop 15-en0xxx       | [26a5c24a57](https://linux-hardware.org/?probe=26a5c24a57) | Sep 14, 2020 |
| Lenovo        | G50-70 20351                | [f7f932b330](https://linux-hardware.org/?probe=f7f932b330) | Sep 14, 2020 |
| ASUSTek       | X510UQ                      | [e289d19d20](https://linux-hardware.org/?probe=e289d19d20) | Sep 14, 2020 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [86096bb0d6](https://linux-hardware.org/?probe=86096bb0d6) | Sep 13, 2020 |
| HP            | Laptop 15-bw0xx             | [80611690cf](https://linux-hardware.org/?probe=80611690cf) | Sep 13, 2020 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [451f9dcbaa](https://linux-hardware.org/?probe=451f9dcbaa) | Sep 13, 2020 |
| Apple         | MacBookPro11,5              | [e98f9caf71](https://linux-hardware.org/?probe=e98f9caf71) | Sep 13, 2020 |
| HP            | OMEN Laptop 15-en0xxx       | [b6001f0a3e](https://linux-hardware.org/?probe=b6001f0a3e) | Sep 12, 2020 |
| Notebook      | N8xEJEK                     | [d617a51c21](https://linux-hardware.org/?probe=d617a51c21) | Sep 12, 2020 |
| Notebook      | N85_N87,HJ,HJ1,HK1          | [d664f379c6](https://linux-hardware.org/?probe=d664f379c6) | Sep 12, 2020 |
| HP            | OMEN Laptop 15-en0xxx       | [db017a504b](https://linux-hardware.org/?probe=db017a504b) | Sep 12, 2020 |
| Apple         | MacBookPro11,5              | [2ed0138305](https://linux-hardware.org/?probe=2ed0138305) | Sep 12, 2020 |
| Dell          | Inspiron 5520               | [4afa713a1f](https://linux-hardware.org/?probe=4afa713a1f) | Sep 12, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | [749dd9856d](https://linux-hardware.org/?probe=749dd9856d) | Sep 12, 2020 |
| Notebook      | N8xEJEK                     | [b1125e8a06](https://linux-hardware.org/?probe=b1125e8a06) | Sep 11, 2020 |
| Dell          | Latitude E6400              | [24107c1488](https://linux-hardware.org/?probe=24107c1488) | Sep 11, 2020 |
| Lenovo        | ThinkPad T420 4180PBG       | [66e104dd81](https://linux-hardware.org/?probe=66e104dd81) | Sep 11, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [73da40e8b7](https://linux-hardware.org/?probe=73da40e8b7) | Sep 11, 2020 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [e2c849dca9](https://linux-hardware.org/?probe=e2c849dca9) | Sep 10, 2020 |
| Acer          | Aspire E5-571G              | [c10fa7f017](https://linux-hardware.org/?probe=c10fa7f017) | Sep 09, 2020 |
| MSI           | GS40 6QE Phantom            | [e625fd220d](https://linux-hardware.org/?probe=e625fd220d) | Sep 09, 2020 |
| HP            | EliteBook 840 G6            | [7b0c82c0ba](https://linux-hardware.org/?probe=7b0c82c0ba) | Sep 09, 2020 |
| Dell          | Inspiron 5423               | [d8dc0213bf](https://linux-hardware.org/?probe=d8dc0213bf) | Sep 09, 2020 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [0adf167b3c](https://linux-hardware.org/?probe=0adf167b3c) | Sep 09, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [eae52adaf0](https://linux-hardware.org/?probe=eae52adaf0) | Sep 09, 2020 |
| Lenovo        | ThinkPad Z61t 9441W15       | [e609777f1d](https://linux-hardware.org/?probe=e609777f1d) | Sep 08, 2020 |
| Lenovo        | G50-80 80E5                 | [16e2be1e8c](https://linux-hardware.org/?probe=16e2be1e8c) | Sep 08, 2020 |
| Acer          | Aspire A715-75G             | [b134acf810](https://linux-hardware.org/?probe=b134acf810) | Sep 08, 2020 |
| Lenovo        | ThinkPad X230 23243Q3       | [ea433dae2d](https://linux-hardware.org/?probe=ea433dae2d) | Sep 08, 2020 |
| HP            | ElitePad 1000 G2            | [836ce575ff](https://linux-hardware.org/?probe=836ce575ff) | Sep 08, 2020 |
| HP            | EliteBook 840 G5            | [0a16cda83f](https://linux-hardware.org/?probe=0a16cda83f) | Sep 08, 2020 |
| Lenovo        | IdeaPad Slim 7 14IIL05 8... | [fe106c40e3](https://linux-hardware.org/?probe=fe106c40e3) | Sep 08, 2020 |
| Acer          | Aspire 5733Z                | [543c4e9780](https://linux-hardware.org/?probe=543c4e9780) | Sep 07, 2020 |
| Apple         | MacBookPro15,1              | [14f7792e0d](https://linux-hardware.org/?probe=14f7792e0d) | Sep 07, 2020 |
| HP            | Pavilion 17                 | [9cedfb1b3b](https://linux-hardware.org/?probe=9cedfb1b3b) | Sep 07, 2020 |
| Acer          | Aspire E5-575G              | [828c695fab](https://linux-hardware.org/?probe=828c695fab) | Sep 06, 2020 |
| Lenovo        | ThinkPad W701 25002LG       | [dc4ad35f97](https://linux-hardware.org/?probe=dc4ad35f97) | Sep 06, 2020 |
| Lenovo        | ThinkPad X230 2325W3J       | [b076277c46](https://linux-hardware.org/?probe=b076277c46) | Sep 05, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [ee329db2e4](https://linux-hardware.org/?probe=ee329db2e4) | Sep 05, 2020 |
| Dell          | XPS 15 7590                 | [1674993692](https://linux-hardware.org/?probe=1674993692) | Sep 05, 2020 |
| Lenovo        | V310-15ISK 80SY             | [fc06b19016](https://linux-hardware.org/?probe=fc06b19016) | Sep 05, 2020 |
| Lenovo        | ThinkPad T410s 2912AJ7      | [5b29fd8262](https://linux-hardware.org/?probe=5b29fd8262) | Sep 05, 2020 |
| Lenovo        | ThinkPad X240 20AMS39B00    | [b2f7ace5e9](https://linux-hardware.org/?probe=b2f7ace5e9) | Sep 05, 2020 |
| Lenovo        | Flex 2-14 20404             | [74cf2869d7](https://linux-hardware.org/?probe=74cf2869d7) | Sep 05, 2020 |
| Lenovo        | IdeaPad Slim 7 14IIL05 8... | [f9ab1be423](https://linux-hardware.org/?probe=f9ab1be423) | Sep 05, 2020 |
| Lenovo        | IdeaPad Slim 7 14IIL05 8... | [de9385a8e3](https://linux-hardware.org/?probe=de9385a8e3) | Sep 05, 2020 |
| Acer          | Aspire V5-471               | [4135632706](https://linux-hardware.org/?probe=4135632706) | Sep 05, 2020 |
| HP            | OMEN by Laptop 15-dc0xxx    | [845ef5bafe](https://linux-hardware.org/?probe=845ef5bafe) | Sep 04, 2020 |
| ASUSTek       | N550JV                      | [aadfffaa16](https://linux-hardware.org/?probe=aadfffaa16) | Sep 04, 2020 |
| Dell          | XPS 13 9370                 | [8164e45f29](https://linux-hardware.org/?probe=8164e45f29) | Sep 04, 2020 |
| Lenovo        | ThinkPad T590 20N4000BMZ    | [ff7f82b032](https://linux-hardware.org/?probe=ff7f82b032) | Sep 04, 2020 |
| Lenovo        | ThinkPad T590 20N4000BMZ    | [587d4d9277](https://linux-hardware.org/?probe=587d4d9277) | Sep 04, 2020 |
| ASUSTek       | N550JV                      | [1a44373bdb](https://linux-hardware.org/?probe=1a44373bdb) | Sep 04, 2020 |
| Lenovo        | IdeaPad S340-14API 81NB     | [712ec86d11](https://linux-hardware.org/?probe=712ec86d11) | Sep 04, 2020 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [f2920039e5](https://linux-hardware.org/?probe=f2920039e5) | Sep 04, 2020 |
| HP            | EliteBook 830 G6            | [fcfe0671f0](https://linux-hardware.org/?probe=fcfe0671f0) | Sep 04, 2020 |
| Lenovo        | Z50-75 80EC                 | [acfd05fde1](https://linux-hardware.org/?probe=acfd05fde1) | Sep 03, 2020 |
| Acer          | Aspire E5-571               | [d818328b7e](https://linux-hardware.org/?probe=d818328b7e) | Sep 03, 2020 |
| Lenovo        | ThinkPad X280 20KF001YUS    | [d1f3e1be66](https://linux-hardware.org/?probe=d1f3e1be66) | Sep 03, 2020 |
| HP            | ZBook Studio G3             | [ab052271f5](https://linux-hardware.org/?probe=ab052271f5) | Sep 03, 2020 |
| Samsung       | 530U4E/540U4E               | [0225e13980](https://linux-hardware.org/?probe=0225e13980) | Sep 03, 2020 |
| Lenovo        | Flex 2-15 20405             | [56c2d6c665](https://linux-hardware.org/?probe=56c2d6c665) | Sep 03, 2020 |
| Lenovo        | ThinkPad L390 20NRCTO1WW    | [a6f4ef55ee](https://linux-hardware.org/?probe=a6f4ef55ee) | Sep 03, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [f8631e5f4a](https://linux-hardware.org/?probe=f8631e5f4a) | Sep 03, 2020 |
| ASUSTek       | VivoBook S14 X430UA         | [85ab9de98f](https://linux-hardware.org/?probe=85ab9de98f) | Sep 03, 2020 |
| Acer          | Aspire A315-41G             | [ec1a232ba9](https://linux-hardware.org/?probe=ec1a232ba9) | Sep 03, 2020 |
| Acer          | Aspire A315-41G             | [3cff1527be](https://linux-hardware.org/?probe=3cff1527be) | Sep 03, 2020 |
| Lenovo        | ThinkPad T420 4180PBG       | [e208d6ec85](https://linux-hardware.org/?probe=e208d6ec85) | Sep 03, 2020 |
| Lenovo        | ThinkPad T430 2344BMU       | [8690f62d83](https://linux-hardware.org/?probe=8690f62d83) | Sep 03, 2020 |
| Lenovo        | ThinkPad T420 4180PBG       | [3c29962537](https://linux-hardware.org/?probe=3c29962537) | Sep 03, 2020 |
| Dell          | Precision 7530              | [91306b715e](https://linux-hardware.org/?probe=91306b715e) | Sep 03, 2020 |
| Unknown       | Unknown                     | [230b86b151](https://linux-hardware.org/?probe=230b86b151) | Sep 03, 2020 |
| Lenovo        | ThinkPad T540p 20BE003AU... | [d6115592e4](https://linux-hardware.org/?probe=d6115592e4) | Sep 03, 2020 |
| Dell          | XPS 13 9370                 | [4a2a7b2689](https://linux-hardware.org/?probe=4a2a7b2689) | Sep 03, 2020 |
| Lenovo        | ThinkPad X230 2324AS7       | [676f1b8dce](https://linux-hardware.org/?probe=676f1b8dce) | Sep 03, 2020 |
| Dell          | Latitude E6440              | [6ffbd1ed44](https://linux-hardware.org/?probe=6ffbd1ed44) | Sep 03, 2020 |
| Lenovo        | ThinkPad E490 20N9CTO1WW    | [a102f4027a](https://linux-hardware.org/?probe=a102f4027a) | Sep 03, 2020 |
| MSI           | GL63 8RC                    | [92cb0f7af2](https://linux-hardware.org/?probe=92cb0f7af2) | Sep 03, 2020 |
| MSI           | GS65 Stealth 8SE            | [7192438530](https://linux-hardware.org/?probe=7192438530) | Sep 03, 2020 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [1fe9922ceb](https://linux-hardware.org/?probe=1fe9922ceb) | Sep 03, 2020 |
| HP            | Pavilion g6                 | [45379e40d7](https://linux-hardware.org/?probe=45379e40d7) | Sep 02, 2020 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [2de7a19bf0](https://linux-hardware.org/?probe=2de7a19bf0) | Sep 02, 2020 |
| Dell          | Inspiron 5570               | [e674f6cca9](https://linux-hardware.org/?probe=e674f6cca9) | Sep 02, 2020 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [08cf061344](https://linux-hardware.org/?probe=08cf061344) | Sep 02, 2020 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [9c0614c658](https://linux-hardware.org/?probe=9c0614c658) | Sep 02, 2020 |
| Dell          | XPS 15 9500                 | [8dae51e89a](https://linux-hardware.org/?probe=8dae51e89a) | Sep 02, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [95a8303440](https://linux-hardware.org/?probe=95a8303440) | Sep 02, 2020 |
| HP            | 15                          | [5b582297ed](https://linux-hardware.org/?probe=5b582297ed) | Sep 02, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [f86fcd9072](https://linux-hardware.org/?probe=f86fcd9072) | Sep 01, 2020 |
| Dell          | Latitude E6540              | [9abf14d168](https://linux-hardware.org/?probe=9abf14d168) | Aug 31, 2020 |
| Dell          | Precision 5540              | [b4708f88f0](https://linux-hardware.org/?probe=b4708f88f0) | Aug 31, 2020 |
| Dell          | XPS 15 9500                 | [867b9c76b4](https://linux-hardware.org/?probe=867b9c76b4) | Aug 31, 2020 |
| Dell          | Precision 5540              | [85b5a2fe9e](https://linux-hardware.org/?probe=85b5a2fe9e) | Aug 31, 2020 |
| Apple         | MacBook7,1                  | [8d88dd1e82](https://linux-hardware.org/?probe=8d88dd1e82) | Aug 31, 2020 |
| Dell          | XPS 13 7390                 | [a6b876446c](https://linux-hardware.org/?probe=a6b876446c) | Aug 30, 2020 |
| Mediacom      | K147                        | [bf2819850e](https://linux-hardware.org/?probe=bf2819850e) | Aug 30, 2020 |
| HP            | Laptop 17-ca1xxx            | [25a5f3010d](https://linux-hardware.org/?probe=25a5f3010d) | Aug 30, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [bc8e0f5bcb](https://linux-hardware.org/?probe=bc8e0f5bcb) | Aug 30, 2020 |
| HP            | ProBook 440 G3              | [1e65e31e23](https://linux-hardware.org/?probe=1e65e31e23) | Aug 30, 2020 |
| Lenovo        | ThinkPad E450 20DDA02WIG    | [57573ff6a0](https://linux-hardware.org/?probe=57573ff6a0) | Aug 29, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [2cb8ed0df6](https://linux-hardware.org/?probe=2cb8ed0df6) | Aug 29, 2020 |
| Acer          | Aspire 6930G                | [7e32ffe51a](https://linux-hardware.org/?probe=7e32ffe51a) | Aug 29, 2020 |
| Acer          | Aspire A315-55G             | [d2b3e2ed46](https://linux-hardware.org/?probe=d2b3e2ed46) | Aug 29, 2020 |
| Google        | Chell                       | [3bf843ce58](https://linux-hardware.org/?probe=3bf843ce58) | Aug 28, 2020 |
| HP            | ProBook 445 G7              | [b8baf427ab](https://linux-hardware.org/?probe=b8baf427ab) | Aug 28, 2020 |
| Dell          | Inspiron 5520               | [339803c33f](https://linux-hardware.org/?probe=339803c33f) | Aug 28, 2020 |
| Dell          | Inspiron 5520               | [cdfa8e081f](https://linux-hardware.org/?probe=cdfa8e081f) | Aug 28, 2020 |
| Lenovo        | ThinkPad L540 20AUS0HV00    | [16e26763b0](https://linux-hardware.org/?probe=16e26763b0) | Aug 28, 2020 |
| Lenovo        | ThinkPad L540 20AUS0HV00    | [5d3a78e0ab](https://linux-hardware.org/?probe=5d3a78e0ab) | Aug 28, 2020 |
| Lenovo        | Yoga 3 14 80JH              | [3623866056](https://linux-hardware.org/?probe=3623866056) | Aug 28, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [44e0b6eec0](https://linux-hardware.org/?probe=44e0b6eec0) | Aug 27, 2020 |
| Notebook      | N85_N87,HJ,HJ1,HK1          | [bbe6637570](https://linux-hardware.org/?probe=bbe6637570) | Aug 27, 2020 |
| MSI           | GE72 7RE                    | [3f705b4ac3](https://linux-hardware.org/?probe=3f705b4ac3) | Aug 26, 2020 |
| HP            | 630                         | [96c2eb25ab](https://linux-hardware.org/?probe=96c2eb25ab) | Aug 26, 2020 |
| Lenovo        | ThinkPad L430 2465CTO       | [e5371d9b58](https://linux-hardware.org/?probe=e5371d9b58) | Aug 26, 2020 |
| Lenovo        | ThinkPad T460p 20FW0044A... | [4d92725c5a](https://linux-hardware.org/?probe=4d92725c5a) | Aug 26, 2020 |
| HP            | Casablanca H710             | [2061828542](https://linux-hardware.org/?probe=2061828542) | Aug 26, 2020 |
| HP            | Casablanca H710             | [f566c52ffd](https://linux-hardware.org/?probe=f566c52ffd) | Aug 26, 2020 |
| Intel         | H81U                        | [9dfe47a2b3](https://linux-hardware.org/?probe=9dfe47a2b3) | Aug 26, 2020 |
| Intel         | H81U                        | [65f88785ff](https://linux-hardware.org/?probe=65f88785ff) | Aug 26, 2020 |
| Lenovo        | ThinkPad T460 20FMS2FR00    | [1707834024](https://linux-hardware.org/?probe=1707834024) | Aug 26, 2020 |
| TUXEDO        | Unknown                     | [8d654053ba](https://linux-hardware.org/?probe=8d654053ba) | Aug 25, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [73da60bf54](https://linux-hardware.org/?probe=73da60bf54) | Aug 25, 2020 |
| Timi          | TM1701                      | [4c01fca357](https://linux-hardware.org/?probe=4c01fca357) | Aug 25, 2020 |
| Notebook      | NJ50GU                      | [768588c7e0](https://linux-hardware.org/?probe=768588c7e0) | Aug 25, 2020 |
| Dell          | Latitude E6320              | [8e2c4b7947](https://linux-hardware.org/?probe=8e2c4b7947) | Aug 25, 2020 |
| Apple         | MacBookPro15,1              | [7453da059c](https://linux-hardware.org/?probe=7453da059c) | Aug 25, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [0c0829346d](https://linux-hardware.org/?probe=0c0829346d) | Aug 25, 2020 |
| Dell          | XPS 15 9500                 | [179f5dc03a](https://linux-hardware.org/?probe=179f5dc03a) | Aug 24, 2020 |
| Notebook      | N8xEJEK                     | [f068e46853](https://linux-hardware.org/?probe=f068e46853) | Aug 24, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | [760d946282](https://linux-hardware.org/?probe=760d946282) | Aug 24, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | [9ba3e88545](https://linux-hardware.org/?probe=9ba3e88545) | Aug 24, 2020 |
| MSI           | GS40 6QE Phantom            | [6a030e65ff](https://linux-hardware.org/?probe=6a030e65ff) | Aug 24, 2020 |
| HP            | Laptop 14s-dq1xxx           | [e7450d32f7](https://linux-hardware.org/?probe=e7450d32f7) | Aug 24, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [f0150526b6](https://linux-hardware.org/?probe=f0150526b6) | Aug 24, 2020 |
| Toshiba       | Satellite C650              | [62b9540e29](https://linux-hardware.org/?probe=62b9540e29) | Aug 24, 2020 |
| Lenovo        | ThinkPad W520 4284Y3Z       | [24e4877efc](https://linux-hardware.org/?probe=24e4877efc) | Aug 24, 2020 |
| HUAWEI        | HLY-WX9XX                   | [d53a271c2a](https://linux-hardware.org/?probe=d53a271c2a) | Aug 23, 2020 |
| Apple         | MacBookPro15,1              | [be21c397d9](https://linux-hardware.org/?probe=be21c397d9) | Aug 23, 2020 |
| TUXEDO        | InfinityBook Pro 15 v4      | [a379e0f730](https://linux-hardware.org/?probe=a379e0f730) | Aug 23, 2020 |
| Samsung       | 340XAA/350XAA/550XAA        | [2513f28d92](https://linux-hardware.org/?probe=2513f28d92) | Aug 23, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [f3ab45b511](https://linux-hardware.org/?probe=f3ab45b511) | Aug 22, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [c985c20ccc](https://linux-hardware.org/?probe=c985c20ccc) | Aug 22, 2020 |
| Notebook      | W65_67SZ                    | [9f17ede2c0](https://linux-hardware.org/?probe=9f17ede2c0) | Aug 22, 2020 |
| Notebook      | W65_67SZ                    | [0eb94fa31d](https://linux-hardware.org/?probe=0eb94fa31d) | Aug 22, 2020 |
| Lenovo        | G400 20235                  | [f209fc4fd1](https://linux-hardware.org/?probe=f209fc4fd1) | Aug 22, 2020 |
| Lenovo        | ThinkPad T430 2347G5U       | [d0065f57d5](https://linux-hardware.org/?probe=d0065f57d5) | Aug 22, 2020 |
| Dell          | Inspiron 5547               | [26c9490e16](https://linux-hardware.org/?probe=26c9490e16) | Aug 21, 2020 |
| ASUSTek       | ROG Zephyrus S17 GX701LW... | [980765374d](https://linux-hardware.org/?probe=980765374d) | Aug 21, 2020 |
| Acer          | Aspire A715-71G             | [68e607956b](https://linux-hardware.org/?probe=68e607956b) | Aug 21, 2020 |
| MSI           | Prestige 14 A10RB           | [940b3a9ce5](https://linux-hardware.org/?probe=940b3a9ce5) | Aug 21, 2020 |
| Lenovo        | ThinkPad T420 4236DY5       | [214d39a637](https://linux-hardware.org/?probe=214d39a637) | Aug 21, 2020 |
| Lenovo        | ThinkPad T460 20FMS2FR00    | [db76b91e62](https://linux-hardware.org/?probe=db76b91e62) | Aug 21, 2020 |
| MSI           | GT72VR 7RE                  | [76f1f4212e](https://linux-hardware.org/?probe=76f1f4212e) | Aug 21, 2020 |
| Dell          | Inspiron 15-5578            | [4361868d04](https://linux-hardware.org/?probe=4361868d04) | Aug 21, 2020 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [9b6f868dc3](https://linux-hardware.org/?probe=9b6f868dc3) | Aug 21, 2020 |
| Lenovo        | ThinkPad T420 4180AG8       | [dbf644c8d0](https://linux-hardware.org/?probe=dbf644c8d0) | Aug 20, 2020 |
| Lenovo        | ThinkPad T420 4180AG8       | [f1e685866f](https://linux-hardware.org/?probe=f1e685866f) | Aug 20, 2020 |
| Lenovo        | ThinkPad T420 4236DY5       | [0359993339](https://linux-hardware.org/?probe=0359993339) | Aug 20, 2020 |
| Lenovo        | ThinkPad E450 20DD001NIG    | [3b3540b3a9](https://linux-hardware.org/?probe=3b3540b3a9) | Aug 20, 2020 |
| HP            | Pavilion g4                 | [f16a6b4a6b](https://linux-hardware.org/?probe=f16a6b4a6b) | Aug 20, 2020 |
| ASUSTek       | N56VZ                       | [fccd9aa436](https://linux-hardware.org/?probe=fccd9aa436) | Aug 19, 2020 |
| ASUSTek       | X411UN                      | [9048a4d602](https://linux-hardware.org/?probe=9048a4d602) | Aug 19, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [bf99687d06](https://linux-hardware.org/?probe=bf99687d06) | Aug 19, 2020 |
| Dell          | XPS 13 9360                 | [a12230c5ef](https://linux-hardware.org/?probe=a12230c5ef) | Aug 19, 2020 |
| Dell          | Latitude E6220              | [cfa9971ad6](https://linux-hardware.org/?probe=cfa9971ad6) | Aug 19, 2020 |
| Dell          | Latitude E6220              | [0b5903e0ce](https://linux-hardware.org/?probe=0b5903e0ce) | Aug 19, 2020 |
| HP            | EliteBook 840 G6            | [8f768222bd](https://linux-hardware.org/?probe=8f768222bd) | Aug 19, 2020 |
| Dell          | Inspiron 1545               | [7ca56bb771](https://linux-hardware.org/?probe=7ca56bb771) | Aug 18, 2020 |
| Dell          | Inspiron 1545               | [99a2dcf63e](https://linux-hardware.org/?probe=99a2dcf63e) | Aug 18, 2020 |
| HUAWEI        | HN-WX9X                     | [8b773f01d7](https://linux-hardware.org/?probe=8b773f01d7) | Aug 17, 2020 |
| Dell          | XPS 13 9350                 | [f74f045bcc](https://linux-hardware.org/?probe=f74f045bcc) | Aug 17, 2020 |
| HUAWEI        | HLY-WX9XX                   | [fb2ef05779](https://linux-hardware.org/?probe=fb2ef05779) | Aug 17, 2020 |
| HP            | Notebook                    | [5938941100](https://linux-hardware.org/?probe=5938941100) | Aug 15, 2020 |
| Dell          | Latitude 3550               | [9caa1b1f2b](https://linux-hardware.org/?probe=9caa1b1f2b) | Aug 15, 2020 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [e753dce85a](https://linux-hardware.org/?probe=e753dce85a) | Aug 14, 2020 |
| Acer          | Swift SF314-42              | [bec5ea27a1](https://linux-hardware.org/?probe=bec5ea27a1) | Aug 13, 2020 |
| Toshiba       | Satellite C650              | [6efbdabe8a](https://linux-hardware.org/?probe=6efbdabe8a) | Aug 13, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [4505f37f8a](https://linux-hardware.org/?probe=4505f37f8a) | Aug 12, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [9feef64d5b](https://linux-hardware.org/?probe=9feef64d5b) | Aug 11, 2020 |
| Lenovo        | ThinkPad Edge E440 20C50... | [e2a554e507](https://linux-hardware.org/?probe=e2a554e507) | Aug 11, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [ac527dcde7](https://linux-hardware.org/?probe=ac527dcde7) | Aug 11, 2020 |
| TUXEDO        | Book BA1510                 | [cb33d0e196](https://linux-hardware.org/?probe=cb33d0e196) | Aug 11, 2020 |
| Dell          | Latitude E7450              | [ae8d11da33](https://linux-hardware.org/?probe=ae8d11da33) | Aug 10, 2020 |
| Acer          | Aspire E5-573G              | [da1cda520b](https://linux-hardware.org/?probe=da1cda520b) | Aug 10, 2020 |
| Dell          | Latitude E6410              | [df34559907](https://linux-hardware.org/?probe=df34559907) | Aug 09, 2020 |
| Apple         | MacBook6,1                  | [36dc269753](https://linux-hardware.org/?probe=36dc269753) | Aug 09, 2020 |
| Dell          | XPS 13 7390                 | [93ab526480](https://linux-hardware.org/?probe=93ab526480) | Aug 09, 2020 |
| Acer          | Aspire ES1-533              | [171dab82c1](https://linux-hardware.org/?probe=171dab82c1) | Aug 09, 2020 |
| Toshiba       | Satellite L505D             | [4326b03817](https://linux-hardware.org/?probe=4326b03817) | Aug 09, 2020 |
| HP            | 250 G6 Notebook PC          | [1ec8af3962](https://linux-hardware.org/?probe=1ec8af3962) | Aug 08, 2020 |
| Lenovo        | ThinkPad T430 2349G4G       | [db1ba375f2](https://linux-hardware.org/?probe=db1ba375f2) | Aug 08, 2020 |
| HUAWEI        | MACH-WX9                    | [6e807af57e](https://linux-hardware.org/?probe=6e807af57e) | Aug 08, 2020 |
| Lenovo        | ThinkPad E590 20NB0029PG    | [f93a4e17ee](https://linux-hardware.org/?probe=f93a4e17ee) | Aug 07, 2020 |
| Dell          | Latitude 7424 Rugged Ext... | [f3c642b552](https://linux-hardware.org/?probe=f3c642b552) | Aug 07, 2020 |
| Lenovo        | ThinkPad E485 20KUCTO1WW    | [1b75a09188](https://linux-hardware.org/?probe=1b75a09188) | Aug 07, 2020 |
| Samsung       | 940X3G/930X3G               | [ffc91a2241](https://linux-hardware.org/?probe=ffc91a2241) | Aug 07, 2020 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [22b35f10f0](https://linux-hardware.org/?probe=22b35f10f0) | Aug 07, 2020 |
| Gigabyte      | P65Q                        | [9c9c4e982e](https://linux-hardware.org/?probe=9c9c4e982e) | Aug 07, 2020 |
| HP            | Notebook                    | [cd99381570](https://linux-hardware.org/?probe=cd99381570) | Aug 07, 2020 |
| Dell          | Inspiron 11-3162            | [4134cbf286](https://linux-hardware.org/?probe=4134cbf286) | Aug 07, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [27ab69410a](https://linux-hardware.org/?probe=27ab69410a) | Aug 07, 2020 |
| Dell          | XPS 15 9570                 | [2c753d0441](https://linux-hardware.org/?probe=2c753d0441) | Aug 06, 2020 |
| Lenovo        | ThinkPad L480 20LS001AGE    | [cfdc343369](https://linux-hardware.org/?probe=cfdc343369) | Aug 05, 2020 |
| Dell          | Vostro 5470                 | [256c18cab4](https://linux-hardware.org/?probe=256c18cab4) | Aug 05, 2020 |
| HP            | EliteBook 8470p             | [2f68aeb923](https://linux-hardware.org/?probe=2f68aeb923) | Aug 05, 2020 |
| ASUSTek       | TUF Gaming FA506II_FA506... | [e91c9def49](https://linux-hardware.org/?probe=e91c9def49) | Aug 04, 2020 |
| ASUSTek       | TUF Gaming FA506II_FA506... | [8878011fd9](https://linux-hardware.org/?probe=8878011fd9) | Aug 04, 2020 |
| Samsung       | 340XAA/350XAA/550XAA        | [2975c7952b](https://linux-hardware.org/?probe=2975c7952b) | Aug 04, 2020 |
| Acer          | Aspire 5735                 | [557852f24b](https://linux-hardware.org/?probe=557852f24b) | Aug 04, 2020 |
| Lenovo        | ThinkPad X240 20AMS0SQ02    | [e04ff98ba4](https://linux-hardware.org/?probe=e04ff98ba4) | Aug 03, 2020 |
| ASUSTek       | GL752VW                     | [26fc584896](https://linux-hardware.org/?probe=26fc584896) | Aug 02, 2020 |
| Dell          | XPS M1330                   | [4a907eebb9](https://linux-hardware.org/?probe=4a907eebb9) | Aug 02, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [f03bf738aa](https://linux-hardware.org/?probe=f03bf738aa) | Aug 02, 2020 |
| Lenovo        | ThinkPad T470 20HES2SF00    | [20e409a273](https://linux-hardware.org/?probe=20e409a273) | Aug 01, 2020 |
| Lenovo        | Legion 5 17IMH05H 81Y8      | [bc2c24e3ce](https://linux-hardware.org/?probe=bc2c24e3ce) | Aug 01, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [4c30d37bab](https://linux-hardware.org/?probe=4c30d37bab) | Aug 01, 2020 |
| HP            | Pavilion dv6                | [30347c164f](https://linux-hardware.org/?probe=30347c164f) | Aug 01, 2020 |
| HP            | Pavilion dv6                | [3144e5f6ea](https://linux-hardware.org/?probe=3144e5f6ea) | Aug 01, 2020 |
| Lenovo        | ThinkPad E495 20NECTO1WW    | [41885ba39d](https://linux-hardware.org/?probe=41885ba39d) | Aug 01, 2020 |
| Lenovo        | V330-14ARR 81B1             | [e89440dd5a](https://linux-hardware.org/?probe=e89440dd5a) | Aug 01, 2020 |
| Lenovo        | Legion 5 17IMH05H 81Y8      | [c4a96176ab](https://linux-hardware.org/?probe=c4a96176ab) | Jul 31, 2020 |
| ASUSTek       | Strix 17 GL703GE            | [42c96eeb97](https://linux-hardware.org/?probe=42c96eeb97) | Jul 31, 2020 |
| Toshiba       | Satellite C850-C1S          | [edf449258e](https://linux-hardware.org/?probe=edf449258e) | Jul 31, 2020 |
| HP            | ProBook 650 G1              | [1e65ebcb5c](https://linux-hardware.org/?probe=1e65ebcb5c) | Jul 30, 2020 |
| Lenovo        | ThinkPad T450 20BUS5LE0Y    | [763c87cacb](https://linux-hardware.org/?probe=763c87cacb) | Jul 30, 2020 |
| Lenovo        | ThinkPad T450 20BUS5LE0Y    | [11f4349e37](https://linux-hardware.org/?probe=11f4349e37) | Jul 30, 2020 |
| Dell          | XPS 15 9560                 | [897c79afd9](https://linux-hardware.org/?probe=897c79afd9) | Jul 28, 2020 |
| MSI           | GL62 7QF                    | [41ba1cba4b](https://linux-hardware.org/?probe=41ba1cba4b) | Jul 27, 2020 |
| TUXEDO        | InfinityBook Pro 15 v4      | [ff15a4fc2e](https://linux-hardware.org/?probe=ff15a4fc2e) | Jul 27, 2020 |
| Lenovo        | ThinkPad L460 20FUCTO1WW    | [813cd0abea](https://linux-hardware.org/?probe=813cd0abea) | Jul 27, 2020 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [7efc08bc3f](https://linux-hardware.org/?probe=7efc08bc3f) | Jul 27, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [a2dd413553](https://linux-hardware.org/?probe=a2dd413553) | Jul 26, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [e1073052d4](https://linux-hardware.org/?probe=e1073052d4) | Jul 26, 2020 |
| Dell          | G3 3579                     | [73f1877845](https://linux-hardware.org/?probe=73f1877845) | Jul 26, 2020 |
| Acer          | Aspire VN7-591G             | [ed0294174f](https://linux-hardware.org/?probe=ed0294174f) | Jul 25, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [54cf61f4ba](https://linux-hardware.org/?probe=54cf61f4ba) | Jul 25, 2020 |
| Lenovo        | ThinkPad T60 2007B66        | [1e85c7ff14](https://linux-hardware.org/?probe=1e85c7ff14) | Jul 25, 2020 |
| Sony          | VPCEH40EB                   | [bbc46d6b5d](https://linux-hardware.org/?probe=bbc46d6b5d) | Jul 24, 2020 |
| ASUSTek       | X450LCP                     | [56895b5f9f](https://linux-hardware.org/?probe=56895b5f9f) | Jul 24, 2020 |
| Dell          | Inspiron 5558               | [733e2adede](https://linux-hardware.org/?probe=733e2adede) | Jul 24, 2020 |
| Positivo      | H14BT58                     | [cce8bd1346](https://linux-hardware.org/?probe=cce8bd1346) | Jul 24, 2020 |
| Sony          | VPCEH40EB                   | [fd2e876751](https://linux-hardware.org/?probe=fd2e876751) | Jul 24, 2020 |
| HP            | Laptop 17-by0xxx            | [b6b2f414c1](https://linux-hardware.org/?probe=b6b2f414c1) | Jul 24, 2020 |
| HP            | Laptop 17-by0xxx            | [bf786cd708](https://linux-hardware.org/?probe=bf786cd708) | Jul 24, 2020 |
| Dell          | Inspiron 7460               | [fdf368f027](https://linux-hardware.org/?probe=fdf368f027) | Jul 24, 2020 |
| Acer          | Aspire E5-571               | [02298ff698](https://linux-hardware.org/?probe=02298ff698) | Jul 24, 2020 |
| Lenovo        | ThinkPad T440p 20AW002VB... | [1f64c96402](https://linux-hardware.org/?probe=1f64c96402) | Jul 24, 2020 |
| Acer          | Aspire E5-573G              | [1fdae0ae02](https://linux-hardware.org/?probe=1fdae0ae02) | Jul 24, 2020 |
| Samsung       | RV415/RV515                 | [78582134c7](https://linux-hardware.org/?probe=78582134c7) | Jul 24, 2020 |
| Acer          | Aspire E5-571               | [3dee9106c3](https://linux-hardware.org/?probe=3dee9106c3) | Jul 24, 2020 |
| Dell          | Inspiron 5448               | [c43390163e](https://linux-hardware.org/?probe=c43390163e) | Jul 24, 2020 |
| MSI           | GL62 7QF                    | [e8493fd391](https://linux-hardware.org/?probe=e8493fd391) | Jul 24, 2020 |
| Dell          | XPS 13 9380                 | [52f2ef30e6](https://linux-hardware.org/?probe=52f2ef30e6) | Jul 23, 2020 |
| Lenovo        | ThinkPad X240 20AMS4SD00    | [bb5295f1b8](https://linux-hardware.org/?probe=bb5295f1b8) | Jul 23, 2020 |
| HP            | ProBook 430 G5              | [b78ef0df21](https://linux-hardware.org/?probe=b78ef0df21) | Jul 23, 2020 |
| Lenovo        | ThinkPad X240 20AMS4SD00    | [dba185f4fa](https://linux-hardware.org/?probe=dba185f4fa) | Jul 23, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0VK0... | [9c7d5b4dfa](https://linux-hardware.org/?probe=9c7d5b4dfa) | Jul 23, 2020 |
| Acer          | Aspire E5-571               | [207dddbd8e](https://linux-hardware.org/?probe=207dddbd8e) | Jul 22, 2020 |
| Acer          | Aspire E5-571               | [2226bce117](https://linux-hardware.org/?probe=2226bce117) | Jul 22, 2020 |
| HP            | ProBook 450 G1              | [8db5efa1fc](https://linux-hardware.org/?probe=8db5efa1fc) | Jul 22, 2020 |
| Dell          | Vostro 2520                 | [3865f7c366](https://linux-hardware.org/?probe=3865f7c366) | Jul 22, 2020 |
| Samsung       | 305E4A/305E5A/305E7A        | [5894c718bc](https://linux-hardware.org/?probe=5894c718bc) | Jul 21, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0VK0... | [092e55e5fb](https://linux-hardware.org/?probe=092e55e5fb) | Jul 21, 2020 |
| Samsung       | N150P/N210P/N220P           | [59871cb887](https://linux-hardware.org/?probe=59871cb887) | Jul 20, 2020 |
| MSI           | Prestige 14 A10RB           | [5fcce1c75a](https://linux-hardware.org/?probe=5fcce1c75a) | Jul 20, 2020 |
| Dell          | Latitude E5570              | [6408e82f4f](https://linux-hardware.org/?probe=6408e82f4f) | Jul 20, 2020 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [2ea1abc830](https://linux-hardware.org/?probe=2ea1abc830) | Jul 20, 2020 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [661056c5c7](https://linux-hardware.org/?probe=661056c5c7) | Jul 19, 2020 |
| Dell          | Inspiron 5423               | [13dad3f5c6](https://linux-hardware.org/?probe=13dad3f5c6) | Jul 18, 2020 |
| Samsung       | 530U4E/540U4E               | [8672def9fa](https://linux-hardware.org/?probe=8672def9fa) | Jul 18, 2020 |
| Sony          | VGN-FW360TJ                 | [8b037cac91](https://linux-hardware.org/?probe=8b037cac91) | Jul 18, 2020 |
| HP            | Pavilion Laptop 15-cc1xx    | [f37c80648c](https://linux-hardware.org/?probe=f37c80648c) | Jul 17, 2020 |
| HP            | Pavilion Laptop 15-cc1xx    | [7e09e54d48](https://linux-hardware.org/?probe=7e09e54d48) | Jul 17, 2020 |
| HP            | EliteBook Folio 9470m       | [551b645980](https://linux-hardware.org/?probe=551b645980) | Jul 17, 2020 |
| Apple         | MacBookPro15,1              | [f128e49c63](https://linux-hardware.org/?probe=f128e49c63) | Jul 16, 2020 |
| Lenovo        | ThinkPad T430 2349S31       | [e3c066c916](https://linux-hardware.org/?probe=e3c066c916) | Jul 16, 2020 |
| MSI           | GL72M 7REX                  | [31a6c9eb66](https://linux-hardware.org/?probe=31a6c9eb66) | Jul 16, 2020 |
| Dell          | Latitude 7390               | [72b667003a](https://linux-hardware.org/?probe=72b667003a) | Jul 16, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | [50272ea6ea](https://linux-hardware.org/?probe=50272ea6ea) | Jul 16, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | [2b9f97d49e](https://linux-hardware.org/?probe=2b9f97d49e) | Jul 15, 2020 |
| YiFang        | NXW116QC264                 | [ac99170698](https://linux-hardware.org/?probe=ac99170698) | Jul 15, 2020 |
| YiFang        | NXW116QC264                 | [7d0e957672](https://linux-hardware.org/?probe=7d0e957672) | Jul 14, 2020 |
| Dell          | Inspiron N5050              | [7fcea2abda](https://linux-hardware.org/?probe=7fcea2abda) | Jul 14, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [face34003d](https://linux-hardware.org/?probe=face34003d) | Jul 13, 2020 |
| HUAWEI        | MACH-WX9                    | [37c5c89447](https://linux-hardware.org/?probe=37c5c89447) | Jul 12, 2020 |
| Unknown       | Unknown                     | [36dde76f28](https://linux-hardware.org/?probe=36dde76f28) | Jul 11, 2020 |
| Lenovo        | ThinkPad T440p 20AWS4VW0... | [7a9fd6ca85](https://linux-hardware.org/?probe=7a9fd6ca85) | Jul 11, 2020 |
| Lenovo        | ThinkPad T440p 20AWS4VW0... | [f3d5dc151d](https://linux-hardware.org/?probe=f3d5dc151d) | Jul 11, 2020 |
| HP            | ENVY Laptop 13-aq0xxx       | [1cb4a44270](https://linux-hardware.org/?probe=1cb4a44270) | Jul 11, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [4175ac62a0](https://linux-hardware.org/?probe=4175ac62a0) | Jul 10, 2020 |
| Dell          | Latitude 7390               | [f054294bac](https://linux-hardware.org/?probe=f054294bac) | Jul 10, 2020 |
| Dell          | Inspiron N5050              | [9ab83e152a](https://linux-hardware.org/?probe=9ab83e152a) | Jul 10, 2020 |
| Lenovo        | ThinkPad T490 20N20046US    | [d8668c4c19](https://linux-hardware.org/?probe=d8668c4c19) | Jul 09, 2020 |
| Dell          | XPS 15 7590                 | [f5ff1447a7](https://linux-hardware.org/?probe=f5ff1447a7) | Jul 08, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0edda35d25](https://linux-hardware.org/?probe=0edda35d25) | Jul 08, 2020 |
| Acer          | Aspire A315-53G             | [b6506c9a23](https://linux-hardware.org/?probe=b6506c9a23) | Jul 07, 2020 |
| Lenovo        | ThinkPad SL510 2847CZU      | [c6093e0557](https://linux-hardware.org/?probe=c6093e0557) | Jul 06, 2020 |
| HP            | Stream Laptop 14-cb0XX      | [d4caa20d24](https://linux-hardware.org/?probe=d4caa20d24) | Jul 06, 2020 |
| ASUSTek       | X540SA                      | [eee66795aa](https://linux-hardware.org/?probe=eee66795aa) | Jul 06, 2020 |
| ASUSTek       | X540SA                      | [1abcabceee](https://linux-hardware.org/?probe=1abcabceee) | Jul 06, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [6720e4b6ee](https://linux-hardware.org/?probe=6720e4b6ee) | Jul 06, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [a16d4773bb](https://linux-hardware.org/?probe=a16d4773bb) | Jul 06, 2020 |
| Lenovo        | ThinkPad T420 4236B88       | [479e014452](https://linux-hardware.org/?probe=479e014452) | Jul 05, 2020 |
| Lenovo        | ThinkPad T450 20BUS5LE0Y    | [cebd4f1895](https://linux-hardware.org/?probe=cebd4f1895) | Jul 04, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0VK0... | [02e5a12797](https://linux-hardware.org/?probe=02e5a12797) | Jul 04, 2020 |
| MSI           | GL75 9SDK                   | [d443e0cd31](https://linux-hardware.org/?probe=d443e0cd31) | Jul 02, 2020 |
| Dell          | Inspiron N5050              | [90db8065b9](https://linux-hardware.org/?probe=90db8065b9) | Jul 02, 2020 |
| MSI           | GL75 9SDK                   | [de612259f1](https://linux-hardware.org/?probe=de612259f1) | Jul 02, 2020 |
| DNS           | DNSNB                       | [44ab78f88b](https://linux-hardware.org/?probe=44ab78f88b) | Jul 02, 2020 |
| Dell          | Inspiron N5050              | [d45d995566](https://linux-hardware.org/?probe=d45d995566) | Jul 02, 2020 |
| HP            | 250 G4 Notebook PC          | [19b574b5d6](https://linux-hardware.org/?probe=19b574b5d6) | Jul 02, 2020 |
| Acer          | Aspire A315-42              | [3fdd357dd7](https://linux-hardware.org/?probe=3fdd357dd7) | Jul 01, 2020 |
| Apple         | MacBookPro15,1              | [e686fdbfb1](https://linux-hardware.org/?probe=e686fdbfb1) | Jul 01, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [5c49970b6b](https://linux-hardware.org/?probe=5c49970b6b) | Jul 01, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [5b11ecddba](https://linux-hardware.org/?probe=5b11ecddba) | Jul 01, 2020 |
| HP            | Pavilion 17                 | [a50758bdb0](https://linux-hardware.org/?probe=a50758bdb0) | Jun 30, 2020 |
| Samsung       | RV411/RV511/E3511/S3511     | [a6dcbcadc4](https://linux-hardware.org/?probe=a6dcbcadc4) | Jun 30, 2020 |
| Lenovo        | IdeaPad S340-14API 81NB     | [4349eb8e68](https://linux-hardware.org/?probe=4349eb8e68) | Jun 30, 2020 |
| Toshiba       | Satellite P55-A             | [42e96f7b00](https://linux-hardware.org/?probe=42e96f7b00) | Jun 30, 2020 |
| Samsung       | 550XBE/350XBE               | [455533b4dd](https://linux-hardware.org/?probe=455533b4dd) | Jun 30, 2020 |
| Acer          | Aspire 5742G                | [68f61986f8](https://linux-hardware.org/?probe=68f61986f8) | Jun 29, 2020 |
| ASUSTek       | UX31E                       | [e34c8bd1a4](https://linux-hardware.org/?probe=e34c8bd1a4) | Jun 29, 2020 |
| Lenovo        | ThinkPad X270 20HNCTO1WW    | [25f1493308](https://linux-hardware.org/?probe=25f1493308) | Jun 29, 2020 |
| Samsung       | RV411/RV511/E3511/S3511     | [df5777de6d](https://linux-hardware.org/?probe=df5777de6d) | Jun 29, 2020 |
| Lenovo        | ThinkPad E580 20KS006AMC    | [1e8b0ede4b](https://linux-hardware.org/?probe=1e8b0ede4b) | Jun 29, 2020 |
| HP            | Pavilion 15                 | [499f0c72ee](https://linux-hardware.org/?probe=499f0c72ee) | Jun 29, 2020 |
| ASUSTek       | X751NV                      | [0962b2b4e4](https://linux-hardware.org/?probe=0962b2b4e4) | Jun 29, 2020 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [b447cf6be4](https://linux-hardware.org/?probe=b447cf6be4) | Jun 28, 2020 |
| HP            | EliteBook 850 G6            | [b6be78472b](https://linux-hardware.org/?probe=b6be78472b) | Jun 28, 2020 |
| HP            | EliteBook 850 G6            | [c675ca1388](https://linux-hardware.org/?probe=c675ca1388) | Jun 28, 2020 |
| Lenovo        | Yoga 900S-12ISK 80ML        | [52b64b75a3](https://linux-hardware.org/?probe=52b64b75a3) | Jun 28, 2020 |
| HP            | Pavilion Notebook           | [6cbbda84bb](https://linux-hardware.org/?probe=6cbbda84bb) | Jun 28, 2020 |
| HP            | Laptop 15-db0xxx            | [e4082323a7](https://linux-hardware.org/?probe=e4082323a7) | Jun 27, 2020 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [369b3c8e65](https://linux-hardware.org/?probe=369b3c8e65) | Jun 27, 2020 |
| Acer          | Aspire 5755G                | [0fb98929d1](https://linux-hardware.org/?probe=0fb98929d1) | Jun 26, 2020 |
| Lenovo        | ThinkPad T460 20FMS17900    | [e805bec3e5](https://linux-hardware.org/?probe=e805bec3e5) | Jun 26, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [563fa2ac74](https://linux-hardware.org/?probe=563fa2ac74) | Jun 26, 2020 |
| Apple         | MacBookPro15,1              | [f08f8c5db7](https://linux-hardware.org/?probe=f08f8c5db7) | Jun 26, 2020 |
| Acer          | Swift SF314-41              | [0255fcb566](https://linux-hardware.org/?probe=0255fcb566) | Jun 26, 2020 |
| Dell          | Inspiron 15-3552            | [9b7f2ae65e](https://linux-hardware.org/?probe=9b7f2ae65e) | Jun 25, 2020 |
| Dell          | Precision 7710              | [f6d2736398](https://linux-hardware.org/?probe=f6d2736398) | Jun 25, 2020 |
| HP            | 450                         | [44abffa880](https://linux-hardware.org/?probe=44abffa880) | Jun 25, 2020 |
| HP            | EliteBook 840 G6            | [9fccdcc42f](https://linux-hardware.org/?probe=9fccdcc42f) | Jun 25, 2020 |
| Lenovo        | ThinkPad E15 20RD004FMH     | [4bd7b759cb](https://linux-hardware.org/?probe=4bd7b759cb) | Jun 23, 2020 |
| HP            | EliteBook 840 G6            | [068efa1ec2](https://linux-hardware.org/?probe=068efa1ec2) | Jun 23, 2020 |
| MSI           | GL72M 7REX                  | [32d16d555b](https://linux-hardware.org/?probe=32d16d555b) | Jun 23, 2020 |
| Lenovo        | G500 20236                  | [57838d96e9](https://linux-hardware.org/?probe=57838d96e9) | Jun 22, 2020 |
| Lenovo        | G500 20236                  | [6dc3f7da7f](https://linux-hardware.org/?probe=6dc3f7da7f) | Jun 22, 2020 |
| LG Electro... | C400-G.BC22P1               | [f19968577f](https://linux-hardware.org/?probe=f19968577f) | Jun 22, 2020 |
| HP            | EliteBook 8440p             | [dd3630bd3a](https://linux-hardware.org/?probe=dd3630bd3a) | Jun 22, 2020 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [0e3e48c501](https://linux-hardware.org/?probe=0e3e48c501) | Jun 22, 2020 |
| Lenovo        | ThinkPad X220 4290WLA       | [537b204a6b](https://linux-hardware.org/?probe=537b204a6b) | Jun 22, 2020 |
| Dell          | Latitude 7490               | [b4eb598a15](https://linux-hardware.org/?probe=b4eb598a15) | Jun 21, 2020 |
| Acer          | Aspire E5-511G              | [ec787b05dc](https://linux-hardware.org/?probe=ec787b05dc) | Jun 21, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | [844f7b115e](https://linux-hardware.org/?probe=844f7b115e) | Jun 21, 2020 |
| Razer         | Blade                       | [595015df2b](https://linux-hardware.org/?probe=595015df2b) | Jun 21, 2020 |
| ASUSTek       | UX30                        | [2b613d2551](https://linux-hardware.org/?probe=2b613d2551) | Jun 20, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [b388cd0a96](https://linux-hardware.org/?probe=b388cd0a96) | Jun 20, 2020 |
| Lenovo        | ThinkPad X250 20CLS00201    | [f59685133b](https://linux-hardware.org/?probe=f59685133b) | Jun 19, 2020 |
| HP            | Pavilion dv7                | [ab0c4d56ee](https://linux-hardware.org/?probe=ab0c4d56ee) | Jun 18, 2020 |
| ASUSTek       | X556UQK                     | [c6c57358a6](https://linux-hardware.org/?probe=c6c57358a6) | Jun 18, 2020 |
| Toshiba       | Satellite L755              | [c484f0d58f](https://linux-hardware.org/?probe=c484f0d58f) | Jun 18, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [eaccc0249f](https://linux-hardware.org/?probe=eaccc0249f) | Jun 17, 2020 |
| Dell          | Inspiron 3558               | [e91895ca7c](https://linux-hardware.org/?probe=e91895ca7c) | Jun 17, 2020 |
| HUAWEI        | HLY-WX9XX                   | [f532f4f740](https://linux-hardware.org/?probe=f532f4f740) | Jun 17, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [bcbc0e3494](https://linux-hardware.org/?probe=bcbc0e3494) | Jun 16, 2020 |
| Lenovo        | V130-15IKB 81HN             | [aa720bf1ab](https://linux-hardware.org/?probe=aa720bf1ab) | Jun 15, 2020 |
| Lenovo        | V130-15IKB 81HN             | [179350d4b3](https://linux-hardware.org/?probe=179350d4b3) | Jun 15, 2020 |
| Apple         | MacBookPro6,2               | [e22d69a6c7](https://linux-hardware.org/?probe=e22d69a6c7) | Jun 14, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [36d0697b1e](https://linux-hardware.org/?probe=36d0697b1e) | Jun 14, 2020 |
| Alienware     | 17                          | [0d7bc9a0c2](https://linux-hardware.org/?probe=0d7bc9a0c2) | Jun 13, 2020 |
| Lenovo        | ThinkPad T420 4178C9U       | [a92bb807e3](https://linux-hardware.org/?probe=a92bb807e3) | Jun 13, 2020 |
| Lenovo        | ThinkPad T410s 2904CFU      | [e25f89bb18](https://linux-hardware.org/?probe=e25f89bb18) | Jun 12, 2020 |
| Lenovo        | ThinkPad T410s 2904CFU      | [c7be0b1189](https://linux-hardware.org/?probe=c7be0b1189) | Jun 12, 2020 |
| HUAWEI        | HLY-WX9XX                   | [443ec260d7](https://linux-hardware.org/?probe=443ec260d7) | Jun 12, 2020 |
| SLIMBOOK      | PROX15                      | [a4e6b0723d](https://linux-hardware.org/?probe=a4e6b0723d) | Jun 12, 2020 |
| HP            | ProBook 430 G1              | [4203bc537c](https://linux-hardware.org/?probe=4203bc537c) | Jun 11, 2020 |
| Lenovo        | ThinkPad S3-S440 20BBS00... | [4306284e1d](https://linux-hardware.org/?probe=4306284e1d) | Jun 10, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [c2edfc5f23](https://linux-hardware.org/?probe=c2edfc5f23) | Jun 10, 2020 |
| Samsung       | 550XBE/350XBE               | [a29992d85c](https://linux-hardware.org/?probe=a29992d85c) | Jun 10, 2020 |
| Samsung       | 550P5C/550P7C               | [aeb86dbea9](https://linux-hardware.org/?probe=aeb86dbea9) | Jun 09, 2020 |
| HUAWEI        | MACH-WX9                    | [830d429968](https://linux-hardware.org/?probe=830d429968) | Jun 09, 2020 |
| Toshiba       | Satellite L755              | [4adcecbb98](https://linux-hardware.org/?probe=4adcecbb98) | Jun 07, 2020 |
| Notebook      | P65_67HSHP                  | [e549272682](https://linux-hardware.org/?probe=e549272682) | Jun 06, 2020 |
| Notebook      | P65_67HSHP                  | [ee97744453](https://linux-hardware.org/?probe=ee97744453) | Jun 06, 2020 |
| Apple         | MacBookPro15,1              | [953fe94792](https://linux-hardware.org/?probe=953fe94792) | Jun 06, 2020 |
| MSI           | GF63 Thin 9RCX              | [e819cc9e69](https://linux-hardware.org/?probe=e819cc9e69) | Jun 05, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [2bdef8be56](https://linux-hardware.org/?probe=2bdef8be56) | Jun 04, 2020 |
| Dell          | Precision 7540              | [218efd739a](https://linux-hardware.org/?probe=218efd739a) | Jun 04, 2020 |
| Sony          | VPCS13C5E                   | [e297b43775](https://linux-hardware.org/?probe=e297b43775) | Jun 03, 2020 |
| ASUSTek       | S400CA                      | [53ec789941](https://linux-hardware.org/?probe=53ec789941) | Jun 03, 2020 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [abf56b6ebd](https://linux-hardware.org/?probe=abf56b6ebd) | Jun 01, 2020 |
| Apple         | MacBook5,1                  | [841614c2d1](https://linux-hardware.org/?probe=841614c2d1) | Jun 01, 2020 |
| Apple         | MacBook5,1                  | [8126e4dea3](https://linux-hardware.org/?probe=8126e4dea3) | Jun 01, 2020 |
| HUAWEI        | KPRC-WX0                    | [6e02cd7e95](https://linux-hardware.org/?probe=6e02cd7e95) | Jun 01, 2020 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [592793d453](https://linux-hardware.org/?probe=592793d453) | Jun 01, 2020 |
| Dell          | Precision 7540              | [b6f0fff8fe](https://linux-hardware.org/?probe=b6f0fff8fe) | Jun 01, 2020 |
| HP            | Pavilion Gaming Notebook    | [baa77c716f](https://linux-hardware.org/?probe=baa77c716f) | Jun 01, 2020 |
| Apple         | MacBookPro15,1              | [4b8f308a9a](https://linux-hardware.org/?probe=4b8f308a9a) | May 30, 2020 |
| Apple         | MacBookPro8,1               | [c56d1a43cd](https://linux-hardware.org/?probe=c56d1a43cd) | May 29, 2020 |
| Apple         | MacBookPro15,1              | [c856b73498](https://linux-hardware.org/?probe=c856b73498) | May 28, 2020 |
| Dell          | Inspiron 7347               | [bcddf0f5e9](https://linux-hardware.org/?probe=bcddf0f5e9) | May 28, 2020 |
| Dell          | Inspiron 7347               | [5725dd2537](https://linux-hardware.org/?probe=5725dd2537) | May 28, 2020 |
| HP            | Compaq 615                  | [b5764f8ab1](https://linux-hardware.org/?probe=b5764f8ab1) | May 28, 2020 |
| ASUSTek       | Q502LA                      | [a110b8a50a](https://linux-hardware.org/?probe=a110b8a50a) | May 27, 2020 |
| Dream Mach... | N85_N87,HJ,HJ1,HK1          | [4b5a476e0f](https://linux-hardware.org/?probe=4b5a476e0f) | May 27, 2020 |
| HUAWEI        | BOHK-WAX9X                  | [1ef79c4312](https://linux-hardware.org/?probe=1ef79c4312) | May 27, 2020 |
| HUAWEI        | BOHK-WAX9X                  | [49337f4321](https://linux-hardware.org/?probe=49337f4321) | May 27, 2020 |
| Acer          | Swift SF315-41              | [48ce1a3f58](https://linux-hardware.org/?probe=48ce1a3f58) | May 26, 2020 |
| Timi          | TM1613                      | [fa82d3ea96](https://linux-hardware.org/?probe=fa82d3ea96) | May 26, 2020 |
| Lenovo        | ThinkPad T430 2349K63       | [43257c3441](https://linux-hardware.org/?probe=43257c3441) | May 26, 2020 |
| Lenovo        | ThinkPad E490 20N8S0WY00    | [6bd9a86d5e](https://linux-hardware.org/?probe=6bd9a86d5e) | May 25, 2020 |
| Lenovo        | ThinkPad T60 2623KEU        | [25f0eca4fa](https://linux-hardware.org/?probe=25f0eca4fa) | May 25, 2020 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | [fb71ef9a51](https://linux-hardware.org/?probe=fb71ef9a51) | May 25, 2020 |
| Lenovo        | IdeaPad S400 Touch 20283    | [526ac33f57](https://linux-hardware.org/?probe=526ac33f57) | May 25, 2020 |
| Dell          | Precision 7740              | [0a2948a3b8](https://linux-hardware.org/?probe=0a2948a3b8) | May 25, 2020 |
| Dell          | Inspiron 5570               | [17ee2fe764](https://linux-hardware.org/?probe=17ee2fe764) | May 25, 2020 |
| HP            | ProBook 450 G2              | [ed836a46ac](https://linux-hardware.org/?probe=ed836a46ac) | May 25, 2020 |
| Lenovo        | IdeaPad 720-15IKB 81C7      | [8ec0dccec9](https://linux-hardware.org/?probe=8ec0dccec9) | May 25, 2020 |
| Dell          | Inspiron 7348               | [30ed2641c4](https://linux-hardware.org/?probe=30ed2641c4) | May 25, 2020 |
| Dell          | XPS 15 9570                 | [879f81ed53](https://linux-hardware.org/?probe=879f81ed53) | May 24, 2020 |
| HP            | EliteBook 840 G6            | [07829f089a](https://linux-hardware.org/?probe=07829f089a) | May 24, 2020 |
| HP            | Pavilion Notebook           | [cb9e8104bf](https://linux-hardware.org/?probe=cb9e8104bf) | May 23, 2020 |
| HP            | Pavilion Notebook           | [80a4fb2c10](https://linux-hardware.org/?probe=80a4fb2c10) | May 23, 2020 |
| Dell          | XPS 13 9370                 | [685714710a](https://linux-hardware.org/?probe=685714710a) | May 23, 2020 |
| HP            | ENVY 15                     | [0cb17045b2](https://linux-hardware.org/?probe=0cb17045b2) | May 23, 2020 |
| Dream Mach... | N85_N87,HJ,HJ1,HK1          | [23acd69555](https://linux-hardware.org/?probe=23acd69555) | May 22, 2020 |
| Lenovo        | ThinkPad T420 4180WA4       | [5703225d45](https://linux-hardware.org/?probe=5703225d45) | May 22, 2020 |
| Samsung       | RC530/RC730                 | [7e180f5fd2](https://linux-hardware.org/?probe=7e180f5fd2) | May 21, 2020 |
| Lenovo        | IdeaPad Y510P 20217         | [8db2f8c286](https://linux-hardware.org/?probe=8db2f8c286) | May 21, 2020 |
| Notebook      | NJ50GU                      | [74320599e5](https://linux-hardware.org/?probe=74320599e5) | May 21, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0Y80... | [5ba91f303a](https://linux-hardware.org/?probe=5ba91f303a) | May 21, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [66881ee404](https://linux-hardware.org/?probe=66881ee404) | May 21, 2020 |
| Dell          | G3 3590                     | [8c7226a738](https://linux-hardware.org/?probe=8c7226a738) | May 20, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [eb8c922364](https://linux-hardware.org/?probe=eb8c922364) | May 20, 2020 |
| Lenovo        | G40-80 80JE                 | [b4326791fc](https://linux-hardware.org/?probe=b4326791fc) | May 19, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [2f78e2e0b7](https://linux-hardware.org/?probe=2f78e2e0b7) | May 19, 2020 |
| Dell          | XPS 15 9570                 | [782dc5461c](https://linux-hardware.org/?probe=782dc5461c) | May 19, 2020 |
| ASUSTek       | X556UQK                     | [3af44fa105](https://linux-hardware.org/?probe=3af44fa105) | May 18, 2020 |
| MSI           | GP62 7QF                    | [d39aa81f63](https://linux-hardware.org/?probe=d39aa81f63) | May 18, 2020 |
| HP            | OMEN by Laptop              | [9fbc594ec1](https://linux-hardware.org/?probe=9fbc594ec1) | May 18, 2020 |
| HP            | EliteBook 8470p             | [e4b360801a](https://linux-hardware.org/?probe=e4b360801a) | May 17, 2020 |
| HP            | EliteBook 8470p             | [5ab7a88f30](https://linux-hardware.org/?probe=5ab7a88f30) | May 17, 2020 |
| Samsung       | 700Z3C/700Z5C               | [025d270cb3](https://linux-hardware.org/?probe=025d270cb3) | May 17, 2020 |
| Apple         | MacBookPro8,1               | [faa3b94dc4](https://linux-hardware.org/?probe=faa3b94dc4) | May 17, 2020 |
| Apple         | MacBookPro8,1               | [cf9d79037e](https://linux-hardware.org/?probe=cf9d79037e) | May 17, 2020 |
| Sony          | VPCEH28FG                   | [f241603946](https://linux-hardware.org/?probe=f241603946) | May 17, 2020 |
| Lenovo        | ThinkPad T480s 20L8S2SD0... | [506a181b94](https://linux-hardware.org/?probe=506a181b94) | May 16, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [39edd5fcd9](https://linux-hardware.org/?probe=39edd5fcd9) | May 16, 2020 |
| Apple         | MacBookPro8,1               | [1f6549c2bd](https://linux-hardware.org/?probe=1f6549c2bd) | May 16, 2020 |
| Lenovo        | IdeaPad 310-14ISK 80SL      | [84509a1db2](https://linux-hardware.org/?probe=84509a1db2) | May 15, 2020 |
| Lenovo        | ThinkPad T495s 20QKA008C... | [fd09b801b7](https://linux-hardware.org/?probe=fd09b801b7) | May 14, 2020 |
| Lenovo        | ThinkPad L470 20J5S00C00    | [d7269c3fc3](https://linux-hardware.org/?probe=d7269c3fc3) | May 14, 2020 |
| Dell          | Vostro 5468                 | [b012926424](https://linux-hardware.org/?probe=b012926424) | May 14, 2020 |
| Dell          | Vostro 5468                 | [cd1e9d33af](https://linux-hardware.org/?probe=cd1e9d33af) | May 14, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [4f0c5e2966](https://linux-hardware.org/?probe=4f0c5e2966) | May 13, 2020 |
| Acer          | Aspire 5742G                | [f27a7b8301](https://linux-hardware.org/?probe=f27a7b8301) | May 13, 2020 |
| Toshiba       | Satellite L750D             | [8ef3d0dcc6](https://linux-hardware.org/?probe=8ef3d0dcc6) | May 13, 2020 |
| Lenovo        | ThinkPad T495s 20QKA008C... | [8006d3f65a](https://linux-hardware.org/?probe=8006d3f65a) | May 12, 2020 |
| Lenovo        | ThinkPad T495s 20QKA008C... | [9767ed89e1](https://linux-hardware.org/?probe=9767ed89e1) | May 12, 2020 |
| Lenovo        | ThinkPad T430 2347H76       | [6203d93cd1](https://linux-hardware.org/?probe=6203d93cd1) | May 12, 2020 |
| Acer          | Aspire 5742G                | [2dec87937c](https://linux-hardware.org/?probe=2dec87937c) | May 12, 2020 |
| Dell          | XPS 15 7590                 | [f8c51c58df](https://linux-hardware.org/?probe=f8c51c58df) | May 12, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [f15c21aabd](https://linux-hardware.org/?probe=f15c21aabd) | May 11, 2020 |
| Toshiba       | Satellite C50-B             | [1c545663ac](https://linux-hardware.org/?probe=1c545663ac) | May 11, 2020 |
| Lenovo        | Flex 2-14 20404             | [879453a9cc](https://linux-hardware.org/?probe=879453a9cc) | May 10, 2020 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [05629af0cf](https://linux-hardware.org/?probe=05629af0cf) | May 10, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [65a73b22e2](https://linux-hardware.org/?probe=65a73b22e2) | May 09, 2020 |
| Acer          | Aspire E5-571               | [bcb2e6f15d](https://linux-hardware.org/?probe=bcb2e6f15d) | May 09, 2020 |
| ASUSTek       | Strix 15 GL503GE            | [ce4afc65f5](https://linux-hardware.org/?probe=ce4afc65f5) | May 09, 2020 |
| Alienware     | 17                          | [28b676a334](https://linux-hardware.org/?probe=28b676a334) | May 09, 2020 |
| Apple         | MacBookPro12,1              | [b0c6f48549](https://linux-hardware.org/?probe=b0c6f48549) | May 08, 2020 |
| Acer          | Swift SF314-42              | [642385511c](https://linux-hardware.org/?probe=642385511c) | May 08, 2020 |
| Alienware     | 17                          | [3d7dd13aea](https://linux-hardware.org/?probe=3d7dd13aea) | May 08, 2020 |
| Positivo      | Mobile                      | [127bdec728](https://linux-hardware.org/?probe=127bdec728) | May 07, 2020 |
| HP            | ENVY Notebook               | [a4fa6c3075](https://linux-hardware.org/?probe=a4fa6c3075) | May 06, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [48220a649d](https://linux-hardware.org/?probe=48220a649d) | May 06, 2020 |
| Lenovo        | ThinkPad T495 20NJ000XIX    | [1f1afb68f1](https://linux-hardware.org/?probe=1f1afb68f1) | May 05, 2020 |
| Lenovo        | ThinkPad T495 20NJ000XIX    | [e363273031](https://linux-hardware.org/?probe=e363273031) | May 05, 2020 |
| Apple         | MacBookPro10,2              | [1c55c8940d](https://linux-hardware.org/?probe=1c55c8940d) | May 05, 2020 |
| Sony          | VGN-CR590E                  | [cb2c7466cc](https://linux-hardware.org/?probe=cb2c7466cc) | May 04, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [f8d2fac712](https://linux-hardware.org/?probe=f8d2fac712) | May 04, 2020 |
| ASUSTek       | GL752VW                     | [a7acec52b4](https://linux-hardware.org/?probe=a7acec52b4) | May 04, 2020 |
| Dream Mach... | N85_N87,HJ,HJ1,HK1          | [2a599d62eb](https://linux-hardware.org/?probe=2a599d62eb) | May 03, 2020 |
| Lenovo        | ThinkPad X131e 3368A77      | [c376fe66df](https://linux-hardware.org/?probe=c376fe66df) | May 03, 2020 |
| HIGRADED      | M7x0S                       | [8c6849bd5f](https://linux-hardware.org/?probe=8c6849bd5f) | May 03, 2020 |
| HIGRADED      | M7x0S                       | [42741a7b8b](https://linux-hardware.org/?probe=42741a7b8b) | May 03, 2020 |
| HIGRADED      | M7x0S                       | [805d65445b](https://linux-hardware.org/?probe=805d65445b) | May 03, 2020 |
| Dell          | Latitude E6440              | [ff5829a93b](https://linux-hardware.org/?probe=ff5829a93b) | May 03, 2020 |
| Dell          | Latitude E6410              | [2f23602ace](https://linux-hardware.org/?probe=2f23602ace) | May 02, 2020 |
| ASUSTek       | Strix GL504GS_GL504GS       | [cd5dcecf80](https://linux-hardware.org/?probe=cd5dcecf80) | May 02, 2020 |
| Toshiba       | Satellite L875D             | [c20040df15](https://linux-hardware.org/?probe=c20040df15) | May 01, 2020 |
| Lenovo        | IdeaPad L340-17API 81LY     | [e030a286c2](https://linux-hardware.org/?probe=e030a286c2) | May 01, 2020 |
| Lenovo        | ThinkPad E470 20H2S00700    | [5509ae8eb8](https://linux-hardware.org/?probe=5509ae8eb8) | Apr 30, 2020 |
| Lenovo        | ThinkPad X260 20F5S5MQ00    | [0db882b228](https://linux-hardware.org/?probe=0db882b228) | Apr 30, 2020 |
| ASUSTek       | X301A1                      | [f12f5c2ad9](https://linux-hardware.org/?probe=f12f5c2ad9) | Apr 30, 2020 |
| Dell          | Studio 1558                 | [9c7cf0df73](https://linux-hardware.org/?probe=9c7cf0df73) | Apr 30, 2020 |
| Acer          | Aspire E1-572               | [bdc3322971](https://linux-hardware.org/?probe=bdc3322971) | Apr 29, 2020 |
| Lenovo        | G700 20251                  | [393964f1d1](https://linux-hardware.org/?probe=393964f1d1) | Apr 28, 2020 |
| Lenovo        | G700 20251                  | [8c70ccaf08](https://linux-hardware.org/?probe=8c70ccaf08) | Apr 28, 2020 |
| Mediacom      | SmartBook 14 FullHD - SB... | [29ff18d6f2](https://linux-hardware.org/?probe=29ff18d6f2) | Apr 28, 2020 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [70df794b74](https://linux-hardware.org/?probe=70df794b74) | Apr 28, 2020 |
| Dell          | Precision 5510              | [7a45c56bfb](https://linux-hardware.org/?probe=7a45c56bfb) | Apr 27, 2020 |
| Acer          | Aspire 5553G                | [7b98f4d4cd](https://linux-hardware.org/?probe=7b98f4d4cd) | Apr 27, 2020 |
| Acer          | Aspire E5-571               | [f8b537bbb5](https://linux-hardware.org/?probe=f8b537bbb5) | Apr 27, 2020 |
| Lenovo        | ThinkPad T490 20N2000BRT    | [c046ea9a7c](https://linux-hardware.org/?probe=c046ea9a7c) | Apr 27, 2020 |
| MSI           | GE70 2PE                    | [6c5209016c](https://linux-hardware.org/?probe=6c5209016c) | Apr 26, 2020 |
| Acer          | Aspire V3-772G              | [ba31bea3f7](https://linux-hardware.org/?probe=ba31bea3f7) | Apr 26, 2020 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [25ed04e7f9](https://linux-hardware.org/?probe=25ed04e7f9) | Apr 25, 2020 |
| Dell          | Inspiron 3558               | [966984764b](https://linux-hardware.org/?probe=966984764b) | Apr 25, 2020 |
| Notebook      | W54_55_94_95_97AU,AUQ       | [cd89dd62c8](https://linux-hardware.org/?probe=cd89dd62c8) | Apr 25, 2020 |
| Acer          | Aspire V3-331               | [19e34515bd](https://linux-hardware.org/?probe=19e34515bd) | Apr 25, 2020 |
| Acer          | Aspire V3-331               | [7241132c19](https://linux-hardware.org/?probe=7241132c19) | Apr 24, 2020 |
| Acer          | Aspire V3-331               | [48c0c96bcb](https://linux-hardware.org/?probe=48c0c96bcb) | Apr 24, 2020 |
| HP            | EliteBook 830 G6            | [20c5b917ca](https://linux-hardware.org/?probe=20c5b917ca) | Apr 22, 2020 |
| Lenovo        | Z50-70 20354                | [f429ce4848](https://linux-hardware.org/?probe=f429ce4848) | Apr 22, 2020 |
| Notebook      | W65_67SZ                    | [dd1415c69a](https://linux-hardware.org/?probe=dd1415c69a) | Apr 22, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [9345e782bf](https://linux-hardware.org/?probe=9345e782bf) | Apr 22, 2020 |
| Notebook      | P65_P67RGRERA               | [d7098ddacc](https://linux-hardware.org/?probe=d7098ddacc) | Apr 21, 2020 |
| Lenovo        | ThinkPad T430 2349PT4       | [37041a70bd](https://linux-hardware.org/?probe=37041a70bd) | Apr 21, 2020 |
| Lenovo        | ThinkPad T430 2349PT4       | [a5f3accc50](https://linux-hardware.org/?probe=a5f3accc50) | Apr 21, 2020 |
| HP            | Mini 110-3100               | [0230a47b05](https://linux-hardware.org/?probe=0230a47b05) | Apr 20, 2020 |
| HP            | Mini 110-3100               | [f83ebce7af](https://linux-hardware.org/?probe=f83ebce7af) | Apr 20, 2020 |
| ASUSTek       | U47A                        | [3b85d1aeb4](https://linux-hardware.org/?probe=3b85d1aeb4) | Apr 20, 2020 |
| Lenovo        | IdeaPad Y510P 20217         | [f70b6fc25c](https://linux-hardware.org/?probe=f70b6fc25c) | Apr 20, 2020 |
| Dell          | XPS 15 9570                 | [784397abb8](https://linux-hardware.org/?probe=784397abb8) | Apr 20, 2020 |
| HP            | ProBook 6470b               | [183db58585](https://linux-hardware.org/?probe=183db58585) | Apr 19, 2020 |
| HP            | 250 G6 Notebook PC          | [603fee3265](https://linux-hardware.org/?probe=603fee3265) | Apr 19, 2020 |
| HP            | 250 G6 Notebook PC          | [f78fbccf61](https://linux-hardware.org/?probe=f78fbccf61) | Apr 19, 2020 |
| Dell          | Inspiron 11-3162            | [4b5bb67ac7](https://linux-hardware.org/?probe=4b5bb67ac7) | Apr 19, 2020 |
| Dell          | Latitude 7490               | [e758664c53](https://linux-hardware.org/?probe=e758664c53) | Apr 18, 2020 |
| HP            | EliteBook 840 G6            | [2943b5a174](https://linux-hardware.org/?probe=2943b5a174) | Apr 17, 2020 |
| Dell          | Latitude E6430              | [b2df99dc08](https://linux-hardware.org/?probe=b2df99dc08) | Apr 16, 2020 |
| Lenovo        | IdeaPad Z575 12992PU        | [a29c25ce04](https://linux-hardware.org/?probe=a29c25ce04) | Apr 16, 2020 |
| MSI           | GX720                       | [f3055f11ee](https://linux-hardware.org/?probe=f3055f11ee) | Apr 16, 2020 |
| ASUSTek       | X411UA                      | [9f07f64ebf](https://linux-hardware.org/?probe=9f07f64ebf) | Apr 16, 2020 |
| Dell          | XPS 13 7390                 | [be445b8162](https://linux-hardware.org/?probe=be445b8162) | Apr 15, 2020 |
| Dell          | Latitude E6530              | [9d4a15e1d1](https://linux-hardware.org/?probe=9d4a15e1d1) | Apr 15, 2020 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [fae24ef621](https://linux-hardware.org/?probe=fae24ef621) | Apr 15, 2020 |
| Dell          | XPS 13 9370                 | [f11d6eedc7](https://linux-hardware.org/?probe=f11d6eedc7) | Apr 14, 2020 |
| HP            | ENVY Laptop 13-aq0xxx       | [db086adca0](https://linux-hardware.org/?probe=db086adca0) | Apr 14, 2020 |
| Samsung       | 530U4E/540U4E               | [33747354e3](https://linux-hardware.org/?probe=33747354e3) | Apr 13, 2020 |
| Samsung       | 530U4E/540U4E               | [06fa247c32](https://linux-hardware.org/?probe=06fa247c32) | Apr 13, 2020 |
| ASUSTek       | X411UA                      | [83f884f0db](https://linux-hardware.org/?probe=83f884f0db) | Apr 12, 2020 |
| Dell          | Inspiron 5558               | [4b3c82b48c](https://linux-hardware.org/?probe=4b3c82b48c) | Apr 11, 2020 |
| Dell          | Inspiron 5558               | [5f14c20cc3](https://linux-hardware.org/?probe=5f14c20cc3) | Apr 11, 2020 |
| Lenovo        | Flex 3-1480                 | [4327baf273](https://linux-hardware.org/?probe=4327baf273) | Apr 11, 2020 |
| Sony          | SVP13215CDB                 | [9d61dd3d43](https://linux-hardware.org/?probe=9d61dd3d43) | Apr 11, 2020 |
| Lenovo        | ThinkPad X230 232578G       | [e17fe53805](https://linux-hardware.org/?probe=e17fe53805) | Apr 10, 2020 |
| Dell          | Precision 7540              | [9b4e4569fc](https://linux-hardware.org/?probe=9b4e4569fc) | Apr 10, 2020 |
| Acer          | Nitro AN515-51              | [e14db66781](https://linux-hardware.org/?probe=e14db66781) | Apr 10, 2020 |
| HP            | Stream Laptop 14-cb0XX      | [03eeccb15f](https://linux-hardware.org/?probe=03eeccb15f) | Apr 09, 2020 |
| HP            | Stream Laptop 14-cb0XX      | [d215d63268](https://linux-hardware.org/?probe=d215d63268) | Apr 09, 2020 |
| Acer          | Aspire E5-571               | [fcd84ba9a1](https://linux-hardware.org/?probe=fcd84ba9a1) | Apr 09, 2020 |
| Acer          | Aspire V3-572G              | [6921c5ff38](https://linux-hardware.org/?probe=6921c5ff38) | Apr 09, 2020 |
| Acer          | Aspire V3-572G              | [e7d1beeab1](https://linux-hardware.org/?probe=e7d1beeab1) | Apr 09, 2020 |
| Dell          | Vostro 5471                 | [031fe22aec](https://linux-hardware.org/?probe=031fe22aec) | Apr 08, 2020 |
| Sony          | VPCEJ2Z1E                   | [8644050307](https://linux-hardware.org/?probe=8644050307) | Apr 07, 2020 |
| Sony          | VPCEJ2Z1E                   | [d2f25d33cd](https://linux-hardware.org/?probe=d2f25d33cd) | Apr 07, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [8f07cc8381](https://linux-hardware.org/?probe=8f07cc8381) | Apr 06, 2020 |
| HP            | Pavilion Notebook           | [f76d614382](https://linux-hardware.org/?probe=f76d614382) | Apr 06, 2020 |
| Dell          | Inspiron 7348               | [bfa1f898fb](https://linux-hardware.org/?probe=bfa1f898fb) | Apr 06, 2020 |
| Dell          | Inspiron 7348               | [2ef1c418d1](https://linux-hardware.org/?probe=2ef1c418d1) | Apr 06, 2020 |
| Acer          | Aspire E5-475G              | [a8a037650e](https://linux-hardware.org/?probe=a8a037650e) | Apr 05, 2020 |
| Dell          | G7 7588                     | [68c5b927d7](https://linux-hardware.org/?probe=68c5b927d7) | Apr 05, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [faa38e47b2](https://linux-hardware.org/?probe=faa38e47b2) | Apr 04, 2020 |
| Apple         | MacBookPro9,2               | [5235b4af96](https://linux-hardware.org/?probe=5235b4af96) | Apr 04, 2020 |
| Sony          | VGN-CR590E                  | [121394a15c](https://linux-hardware.org/?probe=121394a15c) | Apr 03, 2020 |
| Dell          | Studio 1558                 | [36307f44b0](https://linux-hardware.org/?probe=36307f44b0) | Apr 03, 2020 |
| Samsung       | RF511/RF411/RF711           | [f5b77b6c69](https://linux-hardware.org/?probe=f5b77b6c69) | Apr 03, 2020 |
| Lenovo        | ThinkPad T420 4236A72       | [bc5affd886](https://linux-hardware.org/?probe=bc5affd886) | Apr 03, 2020 |
| Samsung       | RF511/RF411/RF711           | [63138d0083](https://linux-hardware.org/?probe=63138d0083) | Apr 03, 2020 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [a7c8627fc5](https://linux-hardware.org/?probe=a7c8627fc5) | Apr 02, 2020 |
| Lenovo        | ThinkPad P53 20QNCTO1WW     | [ffce1d3116](https://linux-hardware.org/?probe=ffce1d3116) | Apr 01, 2020 |
| HP            | ProBook 6470b               | [bdcec83002](https://linux-hardware.org/?probe=bdcec83002) | Apr 01, 2020 |
| Lenovo        | ThinkPad E480 20KN005CBM    | [cbc70bfce5](https://linux-hardware.org/?probe=cbc70bfce5) | Apr 01, 2020 |
| Lenovo        | ThinkPad E480 20KN001QRT    | [d788ef0c91](https://linux-hardware.org/?probe=d788ef0c91) | Mar 31, 2020 |
| HP            | EliteBook 840 G2            | [5eab830173](https://linux-hardware.org/?probe=5eab830173) | Mar 31, 2020 |
| Lenovo        | ThinkPad E480 20KN005CBM    | [d018206f33](https://linux-hardware.org/?probe=d018206f33) | Mar 31, 2020 |
| ASUSTek       | X580VD                      | [e8c7cfc3af](https://linux-hardware.org/?probe=e8c7cfc3af) | Mar 31, 2020 |
| ASUSTek       | Zephyrus M GU502GV_GU502... | [cd4497e617](https://linux-hardware.org/?probe=cd4497e617) | Mar 31, 2020 |
| Dell          | Latitude 5480               | [7b20aae777](https://linux-hardware.org/?probe=7b20aae777) | Mar 30, 2020 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [b9f6bf0ad4](https://linux-hardware.org/?probe=b9f6bf0ad4) | Mar 29, 2020 |
| Lenovo        | ThinkPad E480 20KN005CBM    | [99865fe49f](https://linux-hardware.org/?probe=99865fe49f) | Mar 29, 2020 |
| Lenovo        | Unknown                     | [82ffb0dbfb](https://linux-hardware.org/?probe=82ffb0dbfb) | Mar 29, 2020 |
| Dell          | System XPS L502X            | [ca0b9b5008](https://linux-hardware.org/?probe=ca0b9b5008) | Mar 29, 2020 |
| HP            | ZBook Studio G5             | [2d450c351c](https://linux-hardware.org/?probe=2d450c351c) | Mar 27, 2020 |
| HP            | EliteBook 840 G6            | [5ed448ba13](https://linux-hardware.org/?probe=5ed448ba13) | Mar 27, 2020 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [ec4e7e6a24](https://linux-hardware.org/?probe=ec4e7e6a24) | Mar 26, 2020 |
| Dell          | Inspiron 5559               | [7e3eeba3ca](https://linux-hardware.org/?probe=7e3eeba3ca) | Mar 26, 2020 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [bc4c776682](https://linux-hardware.org/?probe=bc4c776682) | Mar 26, 2020 |
| Lenovo        | G710 20252                  | [2971fd6031](https://linux-hardware.org/?probe=2971fd6031) | Mar 26, 2020 |
| Sony          | VPCEB42EG                   | [d2586cdd17](https://linux-hardware.org/?probe=d2586cdd17) | Mar 25, 2020 |
| Sony          | VPCEB42EG                   | [424402e2b1](https://linux-hardware.org/?probe=424402e2b1) | Mar 25, 2020 |
| Lenovo        | ThinkPad X230 23255B2       | [06d70ab8b3](https://linux-hardware.org/?probe=06d70ab8b3) | Mar 24, 2020 |
| Dell          | XPS 15 9570                 | [c7e45d9422](https://linux-hardware.org/?probe=c7e45d9422) | Mar 24, 2020 |
| HP            | Spectre Laptop 13-af0xx     | [021e27fe92](https://linux-hardware.org/?probe=021e27fe92) | Mar 22, 2020 |
| Dell          | Precision 5520              | [0cca0b66f1](https://linux-hardware.org/?probe=0cca0b66f1) | Mar 22, 2020 |
| Dell          | XPS 13 9380                 | [3bec053314](https://linux-hardware.org/?probe=3bec053314) | Mar 21, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [06f9079e6b](https://linux-hardware.org/?probe=06f9079e6b) | Mar 21, 2020 |
| Lenovo        | ThinkPad T440s 20AQ004GU... | [ceb7b6b6cf](https://linux-hardware.org/?probe=ceb7b6b6cf) | Mar 21, 2020 |
| Medion        | Erazer P6679 MD60262        | [96f1f9cf27](https://linux-hardware.org/?probe=96f1f9cf27) | Mar 21, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Arch/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Arch          | 1623      | 65%     |
| Arch Rolling  | 864       | 34.6%   |
| Arch V20.5.7  | 2         | 0.08%   |
| Arch V19.04.4 | 2         | 0.08%   |
| Arch V6.9.2   | 1         | 0.04%   |
| Arch V20.3.4  | 1         | 0.04%   |
| Arch V19.07.9 | 1         | 0.04%   |
| Arch V19.06.1 | 1         | 0.04%   |
| Arch V19.01.4 | 1         | 0.04%   |
| Arch 2.7      | 1         | 0.04%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| Arch | 2432      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.17.1-arch1-1    | 52        | 1.82%   |
| 5.9.14-arch1-1    | 31        | 1.08%   |
| 5.9.1-arch1-1     | 31        | 1.08%   |
| 5.8.5-arch1-1     | 28        | 0.98%   |
| 5.17.5-arch1-1    | 28        | 0.98%   |
| 5.8.10-arch1-1    | 26        | 0.91%   |
| 5.11.16-arch1-1   | 24        | 0.84%   |
| 5.8.14-arch1-1    | 23        | 0.8%    |
| 5.8.1-arch1-1     | 23        | 0.8%    |
| 5.7.12-arch1-1    | 23        | 0.8%    |
| 5.17.9-arch1-1    | 23        | 0.8%    |
| 5.18.1-arch1-1    | 22        | 0.77%   |
| 5.13.13-arch1-1   | 22        | 0.77%   |
| 5.13.12-arch1-1   | 22        | 0.77%   |
| 5.9.10-arch1-1    | 20        | 0.7%    |
| 5.8.12-arch1-1    | 20        | 0.7%    |
| 5.8.3-arch1-1     | 19        | 0.66%   |
| 5.16.16-arch1-1   | 19        | 0.66%   |
| 5.11.11-arch1-1   | 19        | 0.66%   |
| 5.9.11-arch2-1    | 18        | 0.63%   |
| 5.16.2-arch1-1    | 18        | 0.63%   |
| 5.12.15-arch1-1   | 18        | 0.63%   |
| 5.11.2-arch1-1    | 18        | 0.63%   |
| 5.7.6-arch1-1     | 17        | 0.59%   |
| 5.6.13-arch1-1    | 17        | 0.59%   |
| 5.15.2-arch1-1    | 17        | 0.59%   |
| 5.14.14-arch1-1   | 17        | 0.59%   |
| 5.10.16-arch1-1   | 17        | 0.59%   |
| 5.6.15-arch1-1    | 16        | 0.56%   |
| 5.15.7-arch1-1    | 16        | 0.56%   |
| 5.14.8-arch1-1    | 16        | 0.56%   |
| 5.6.11-arch1-1    | 15        | 0.52%   |
| 5.18.14-arch1-1   | 15        | 0.52%   |
| 5.15.10-arch1-1   | 15        | 0.52%   |
| 5.9.6-arch1-1     | 14        | 0.49%   |
| 5.18.3-arch1-1    | 14        | 0.49%   |
| 5.13.10-arch1-1   | 14        | 0.49%   |
| 5.12.9-arch1-1    | 14        | 0.49%   |
| 5.12.14-arch1-1   | 14        | 0.49%   |
| 5.8.8-arch1-1     | 13        | 0.45%   |
| 5.5.13-arch2-1    | 13        | 0.45%   |
| 5.18.7-arch1-1    | 13        | 0.45%   |
| 5.18.6-arch1-1    | 13        | 0.45%   |
| 5.18.12-arch1-1   | 13        | 0.45%   |
| 5.17.3-arch1-1    | 13        | 0.45%   |
| 5.15.12-arch1-1   | 13        | 0.45%   |
| 5.9.8-arch1-1     | 12        | 0.42%   |
| 5.7.10-arch1-1    | 12        | 0.42%   |
| 5.6.4-arch1-1     | 12        | 0.42%   |
| 5.6.14-arch1-1    | 12        | 0.42%   |
| 5.4.13-arch1-1    | 12        | 0.42%   |
| 5.18.5-arch1-1    | 12        | 0.42%   |
| 5.17.1-zen1-1-zen | 12        | 0.42%   |
| 5.16.5-arch1-1    | 12        | 0.42%   |
| 5.16.15-arch1-1   | 12        | 0.42%   |
| 5.14.16-arch1-1   | 12        | 0.42%   |
| 5.14.12-arch1-1   | 12        | 0.42%   |
| 5.10.11-arch1-1   | 12        | 0.42%   |
| 5.9.13-arch1-1    | 11        | 0.38%   |
| 5.8.13-arch1-1    | 11        | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.17.1  | 65        | 2.27%   |
| 5.9.1   | 40        | 1.4%    |
| 5.9.14  | 38        | 1.33%   |
| 5.8.5   | 38        | 1.33%   |
| 5.17.5  | 38        | 1.33%   |
| 5.13.13 | 31        | 1.08%   |
| 5.8.14  | 30        | 1.05%   |
| 5.8.10  | 29        | 1.01%   |
| 5.17.9  | 28        | 0.98%   |
| 5.8.12  | 26        | 0.91%   |
| 5.8.1   | 26        | 0.91%   |
| 5.18.1  | 26        | 0.91%   |
| 5.16.2  | 26        | 0.91%   |
| 5.13.12 | 26        | 0.91%   |
| 5.11.16 | 26        | 0.91%   |
| 5.7.12  | 25        | 0.87%   |
| 5.16.16 | 24        | 0.84%   |
| 5.14.8  | 24        | 0.84%   |
| 5.11.2  | 24        | 0.84%   |
| 5.10.16 | 24        | 0.84%   |
| 5.18.3  | 23        | 0.8%    |
| 5.12.15 | 23        | 0.8%    |
| 5.14.14 | 22        | 0.77%   |
| 5.9.11  | 21        | 0.73%   |
| 5.9.10  | 21        | 0.73%   |
| 5.8.3   | 21        | 0.73%   |
| 5.15.10 | 21        | 0.73%   |
| 5.11.11 | 21        | 0.73%   |
| 5.7.6   | 20        | 0.7%    |
| 5.5.13  | 20        | 0.7%    |
| 5.13.4  | 20        | 0.7%    |
| 5.6.13  | 19        | 0.66%   |
| 5.15.2  | 19        | 0.66%   |
| 5.15.12 | 19        | 0.66%   |
| 5.15.7  | 18        | 0.63%   |
| 5.12.14 | 18        | 0.63%   |
| 5.9.8   | 17        | 0.59%   |
| 5.9.6   | 17        | 0.59%   |
| 5.6.15  | 17        | 0.59%   |
| 5.18.7  | 17        | 0.59%   |
| 5.18.14 | 17        | 0.59%   |
| 5.6.14  | 16        | 0.56%   |
| 5.6.11  | 16        | 0.56%   |
| 5.18.5  | 16        | 0.56%   |
| 5.16.10 | 16        | 0.56%   |
| 5.15.4  | 16        | 0.56%   |
| 5.13.10 | 16        | 0.56%   |
| 5.12.9  | 16        | 0.56%   |
| 5.9.9   | 15        | 0.52%   |
| 5.9.13  | 15        | 0.52%   |
| 5.8.8   | 15        | 0.52%   |
| 5.7.9   | 15        | 0.52%   |
| 5.7.10  | 15        | 0.52%   |
| 5.4.13  | 15        | 0.52%   |
| 5.18.6  | 15        | 0.52%   |
| 5.18.12 | 15        | 0.52%   |
| 5.17.4  | 15        | 0.52%   |
| 5.17.3  | 15        | 0.52%   |
| 5.14.16 | 14        | 0.49%   |
| 5.8.9   | 13        | 0.45%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.8     | 232       | 8.43%   |
| 5.9     | 208       | 7.56%   |
| 5.17    | 196       | 7.12%   |
| 5.4     | 193       | 7.01%   |
| 5.15    | 188       | 6.83%   |
| 5.16    | 187       | 6.8%    |
| 5.10    | 182       | 6.61%   |
| 5.18    | 176       | 6.4%    |
| 5.11    | 168       | 6.1%    |
| 5.12    | 152       | 5.52%   |
| 5.13    | 141       | 5.12%   |
| 5.7     | 138       | 5.01%   |
| 5.6     | 135       | 4.91%   |
| 5.14    | 129       | 4.69%   |
| 5.5     | 93        | 3.38%   |
| 5.3     | 64        | 2.33%   |
| 5.2     | 33        | 1.2%    |
| 4.19    | 26        | 0.94%   |
| 5.0     | 19        | 0.69%   |
| 5.1     | 16        | 0.58%   |
| 4.18    | 16        | 0.58%   |
| 4.17    | 12        | 0.44%   |
| 4.20    | 9         | 0.33%   |
| 4.14    | 9         | 0.33%   |
| 4.15    | 5         | 0.18%   |
| 4.9     | 4         | 0.15%   |
| 4.7     | 4         | 0.15%   |
| 4.16    | 4         | 0.15%   |
| 4.6     | 3         | 0.11%   |
| 4.4     | 3         | 0.11%   |
| 4.8     | 2         | 0.07%   |
| 4.13    | 2         | 0.07%   |
| 4.11    | 2         | 0.07%   |
| Unknown | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 2429      | 99.88%  |
| i686   | 3         | 0.12%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| GNOME                    | 848       | 33.46%  |
| KDE5                     | 528       | 20.84%  |
| Unknown                  | 373       | 14.72%  |
| XFCE                     | 203       | 8.01%   |
| i3                       | 144       | 5.68%   |
| KDE                      | 139       | 5.49%   |
| MATE                     | 38        | 1.5%    |
| Budgie                   | 37        | 1.46%   |
| Cinnamon                 | 36        | 1.42%   |
| X-Cinnamon               | 31        | 1.22%   |
| sway                     | 26        | 1.03%   |
| LXQt                     | 24        | 0.95%   |
| awesome                  | 18        | 0.71%   |
| Deepin                   | 16        | 0.63%   |
| bspwm                    | 12        | 0.47%   |
| LXDE                     | 11        | 0.43%   |
| GNOME Flashback          | 9         | 0.36%   |
| xmonad                   | 7         | 0.28%   |
| DWM                      | 6         | 0.24%   |
| Unity                    | 5         | 0.2%    |
| openbox                  | 5         | 0.2%    |
| qtile                    | 4         | 0.16%   |
| GNOME Classic            | 3         | 0.12%   |
| Enlightenment            | 3         | 0.12%   |
| i3-with-shmlog           | 2         | 0.08%   |
| river                    | 1         | 0.04%   |
| Pantheon                 | 1         | 0.04%   |
| ICEWM                    | 1         | 0.04%   |
| hyprland                 | 1         | 0.04%   |
| default                  | 1         | 0.04%   |
| /usr/bin/openbox-session | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 1515      | 60.33%  |
| Wayland | 585       | 23.3%   |
| Tty     | 233       | 9.28%   |
| Unknown | 178       | 7.09%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1070      | 42.49%  |
| SDDM    | 546       | 21.68%  |
| GDM     | 381       | 15.13%  |
| LightDM | 241       | 9.57%   |
| TDM     | 191       | 7.59%   |
| XDM     | 26        | 1.03%   |
| Ly      | 24        | 0.95%   |
| LXDM    | 20        | 0.79%   |
| SLiM    | 10        | 0.4%    |
| GREETD  | 4         | 0.16%   |
| NODM    | 3         | 0.12%   |
| MDM     | 1         | 0.04%   |
| EMPTTY  | 1         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| en_US       | 1180      | 47.47%  |
| Unknown     | 327       | 13.15%  |
| en_GB       | 136       | 5.47%   |
| C           | 104       | 4.18%   |
| de_DE       | 89        | 3.58%   |
| pt_BR       | 74        | 2.98%   |
| ru_RU       | 63        | 2.53%   |
| fr_FR       | 56        | 2.25%   |
| it_IT       | 51        | 2.05%   |
| en_IN       | 37        | 1.49%   |
| pl_PL       | 36        | 1.45%   |
| es_ES       | 27        | 1.09%   |
| zh_CN       | 26        | 1.05%   |
| en_CA       | 26        | 1.05%   |
| en_AU       | 20        | 0.8%    |
| es_MX       | 13        | 0.52%   |
| es_AR       | 10        | 0.4%    |
| en_IE       | 10        | 0.4%    |
| de_AT       | 10        | 0.4%    |
| tr_TR       | 9         | 0.36%   |
| ru_UA       | 7         | 0.28%   |
| ja_JP       | 7         | 0.28%   |
| hu_HU       | 7         | 0.28%   |
| en_SG       | 7         | 0.28%   |
| en_DK       | 7         | 0.28%   |
| pt_PT       | 6         | 0.24%   |
| nl_NL       | 6         | 0.24%   |
| es_CO       | 6         | 0.24%   |
| es_CL       | 6         | 0.24%   |
| en_NZ       | 6         | 0.24%   |
| zh_TW       | 5         | 0.2%    |
| ca_ES       | 5         | 0.2%    |
| fr_CH       | 4         | 0.16%   |
| fr_CA       | 4         | 0.16%   |
| fr_BE       | 4         | 0.16%   |
| en_ZA       | 4         | 0.16%   |
| en-US       | 4         | 0.16%   |
| cs_CZ       | 4         | 0.16%   |
| unm_US      | 3         | 0.12%   |
| sv_SE       | 3         | 0.12%   |
| lv_LV       | 3         | 0.12%   |
| ko_KR       | 3         | 0.12%   |
| es_PE       | 3         | 0.12%   |
| en_US.UTF8  | 3         | 0.12%   |
| en_IL       | 3         | 0.12%   |
| uk_UA       | 2         | 0.08%   |
| szl_PL      | 2         | 0.08%   |
| sk_SK       | 2         | 0.08%   |
| nl_BE       | 2         | 0.08%   |
| nb_NO       | 2         | 0.08%   |
| es_MX.UTF8  | 2         | 0.08%   |
| en_GB.UTF8  | 2         | 0.08%   |
| en_GB.utf-8 | 2         | 0.08%   |
| en_DE       | 2         | 0.08%   |
| en_150      | 2         | 0.08%   |
| el_GR       | 2         | 0.08%   |
| de_CH       | 2         | 0.08%   |
| vi_VN       | 1         | 0.04%   |
| sv_SE.UTF8  | 1         | 0.04%   |
| sp_SP       | 1         | 0.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 1569      | 62.96%  |
| BIOS | 923       | 37.04%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 1835      | 74.59%  |
| Btrfs   | 389       | 15.81%  |
| Unknown | 108       | 4.39%   |
| Xfs     | 59        | 2.4%    |
| F2fs    | 32        | 1.3%    |
| Zfs     | 15        | 0.61%   |
| Overlay | 15        | 0.61%   |
| Ext2    | 3         | 0.12%   |
| XXXXX   | 1         | 0.04%   |
| XXX4    | 1         | 0.04%   |
| Jfs     | 1         | 0.04%   |
| Aufs    | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 1516      | 61.45%  |
| Unknown | 721       | 29.23%  |
| MBR     | 230       | 9.32%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2207      | 89.82%  |
| Yes       | 250       | 10.18%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1806      | 73.33%  |
| Yes       | 657       | 26.67%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 715       | 29.4%   |
| Dell                   | 415       | 17.06%  |
| Hewlett-Packard        | 323       | 13.28%  |
| ASUSTek Computer       | 283       | 11.64%  |
| Acer                   | 193       | 7.94%   |
| MSI                    | 68        | 2.8%    |
| Apple                  | 51        | 2.1%    |
| Samsung Electronics    | 43        | 1.77%   |
| HUAWEI                 | 39        | 1.6%    |
| Toshiba                | 31        | 1.27%   |
| Notebook               | 25        | 1.03%   |
| Sony                   | 17        | 0.7%    |
| Timi                   | 16        | 0.66%   |
| Google                 | 15        | 0.62%   |
| TUXEDO                 | 13        | 0.53%   |
| Razer                  | 13        | 0.53%   |
| Framework              | 12        | 0.49%   |
| Alienware              | 12        | 0.49%   |
| Unknown                | 9         | 0.37%   |
| System76               | 8         | 0.33%   |
| LG Electronics         | 8         | 0.33%   |
| Fujitsu                | 8         | 0.33%   |
| Schenker               | 7         | 0.29%   |
| Intel                  | 7         | 0.29%   |
| Avell High Performance | 7         | 0.29%   |
| Packard Bell           | 6         | 0.25%   |
| Positivo               | 5         | 0.21%   |
| Chuwi                  | 5         | 0.21%   |
| Medion                 | 4         | 0.16%   |
| MECHREVO               | 4         | 0.16%   |
| Koompi                 | 4         | 0.16%   |
| Gigabyte Technology    | 4         | 0.16%   |
| Teclast                | 3         | 0.12%   |
| SLIMBOOK               | 3         | 0.12%   |
| PC Specialist          | 3         | 0.12%   |
| Intel Client Systems   | 3         | 0.12%   |
| GPD                    | 3         | 0.12%   |
| Eluktronics            | 3         | 0.12%   |
| Star Labs              | 2         | 0.08%   |
| Monster                | 2         | 0.08%   |
| Mediacom               | 2         | 0.08%   |
| Jumper                 | 2         | 0.08%   |
| HONOR                  | 2         | 0.08%   |
| Fujitsu Siemens        | 2         | 0.08%   |
| YiFang                 | 1         | 0.04%   |
| UNOWHY                 | 1         | 0.04%   |
| SANTECH                | 1         | 0.04%   |
| Philco                 | 1         | 0.04%   |
| OEM                    | 1         | 0.04%   |
| Novatech               | 1         | 0.04%   |
| Multilaser             | 1         | 0.04%   |
| MouseComputer          | 1         | 0.04%   |
| MIFcom                 | 1         | 0.04%   |
| Microtech              | 1         | 0.04%   |
| Micro Electronics      | 1         | 0.04%   |
| Maibenben              | 1         | 0.04%   |
| IT Channel Pty         | 1         | 0.04%   |
| Infinix                | 1         | 0.04%   |
| Hyperbook              | 1         | 0.04%   |
| HIGRADED               | 1         | 0.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 26        | 1.07%   |
| HP Notebook                         | 13        | 0.53%   |
| Framework Laptop                    | 12        | 0.49%   |
| Dell XPS 15 9570                    | 12        | 0.49%   |
| Dell XPS 15 9500                    | 12        | 0.49%   |
| Dell Inspiron 15 7000 Gaming        | 10        | 0.41%   |
| Dell XPS 15 7590                    | 9         | 0.37%   |
| Dell XPS 13 9370                    | 9         | 0.37%   |
| Dell XPS 13 9360                    | 9         | 0.37%   |
| Lenovo IdeaPad 5 14ARE05 81YM       | 8         | 0.33%   |
| HUAWEI NBLK-WAX9X                   | 8         | 0.33%   |
| HP EliteBook 840 G6                 | 8         | 0.33%   |
| Dell XPS 13 9380                    | 8         | 0.33%   |
| Dell XPS 13 9350                    | 8         | 0.33%   |
| Dell Precision 7540                 | 7         | 0.29%   |
| Dell Latitude E7450                 | 7         | 0.29%   |
| Dell Latitude E6430                 | 7         | 0.29%   |
| Lenovo Legion 5 15ARH05 82B5        | 6         | 0.25%   |
| HP Pavilion Notebook                | 6         | 0.25%   |
| HP Pavilion g6                      | 6         | 0.25%   |
| HP 250 G6 Notebook PC               | 6         | 0.25%   |
| Dell XPS 13 9310                    | 6         | 0.25%   |
| Dell Latitude 5480                  | 6         | 0.25%   |
| ASUS X580VD                         | 6         | 0.25%   |
| ASUS TUF Gaming FX505DT_FX505DT     | 6         | 0.25%   |
| Acer Nitro AN515-52                 | 6         | 0.25%   |
| Acer Aspire E5-571                  | 6         | 0.25%   |
| Timi TM1701                         | 5         | 0.21%   |
| Razer Blade                         | 5         | 0.21%   |
| Lenovo ThinkPad T480 20L5CTO1WW     | 5         | 0.21%   |
| Lenovo ThinkBook 15 G2 ITL 20VE     | 5         | 0.21%   |
| Lenovo Legion Y530-15ICH 81FV       | 5         | 0.21%   |
| Lenovo IdeaPad L340-15API 81LW      | 5         | 0.21%   |
| Lenovo IdeaPad Flex-14API 81SS      | 5         | 0.21%   |
| HUAWEI MACH-WX9                     | 5         | 0.21%   |
| HUAWEI BOHK-WAX9X                   | 5         | 0.21%   |
| HP Pavilion dv6                     | 5         | 0.21%   |
| HP Pavilion 15                      | 5         | 0.21%   |
| HP Laptop 15-da0xxx                 | 5         | 0.21%   |
| Dell XPS 15 9560                    | 5         | 0.21%   |
| Dell XPS 13 7390                    | 5         | 0.21%   |
| Dell Inspiron 5570                  | 5         | 0.21%   |
| Dell G3 3579                        | 5         | 0.21%   |
| Dell G3 3500                        | 5         | 0.21%   |
| ASUS ROG Strix G513QY_G513QY        | 5         | 0.21%   |
| Apple MacBookPro9,2                 | 5         | 0.21%   |
| Apple MacBookPro15,1                | 5         | 0.21%   |
| Acer Aspire E5-573G                 | 5         | 0.21%   |
| Acer Aspire A515-51G                | 5         | 0.21%   |
| Acer Aspire A515-44                 | 5         | 0.21%   |
| Samsung RV415/RV515                 | 4         | 0.16%   |
| Lenovo Y520-15IKBN 80WK             | 4         | 0.16%   |
| Lenovo V155-15API 81V5              | 4         | 0.16%   |
| Lenovo ThinkPad P53 20QNCTO1WW      | 4         | 0.16%   |
| Lenovo Legion Y540-15IRH-PG0 81SY   | 4         | 0.16%   |
| Lenovo Legion 5 15ARH05H 82B1       | 4         | 0.16%   |
| Lenovo IdeaPad 700-15ISK 80RU       | 4         | 0.16%   |
| Lenovo IdeaPad 5 14ALC05 82LM       | 4         | 0.16%   |
| Lenovo IdeaPad 330-15IKB 81DE       | 4         | 0.16%   |
| HP Pavilion Gaming Laptop 15-dk0xxx | 4         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 438       | 18.01%  |
| Lenovo IdeaPad        | 129       | 5.3%    |
| Dell Inspiron         | 118       | 4.85%   |
| Acer Aspire           | 113       | 4.65%   |
| Dell Latitude         | 104       | 4.28%   |
| Dell XPS              | 103       | 4.24%   |
| HP EliteBook          | 69        | 2.84%   |
| HP Pavilion           | 68        | 2.8%    |
| Lenovo Legion         | 45        | 1.85%   |
| HP ProBook            | 43        | 1.77%   |
| HP Laptop             | 41        | 1.69%   |
| ASUS VivoBook         | 39        | 1.6%    |
| Dell Precision        | 37        | 1.52%   |
| ASUS ROG              | 35        | 1.44%   |
| Acer Nitro            | 33        | 1.36%   |
| Unknown               | 26        | 1.07%   |
| Toshiba Satellite     | 25        | 1.03%   |
| Dell Vostro           | 24        | 0.99%   |
| ASUS TUF              | 22        | 0.9%    |
| Acer Swift            | 19        | 0.78%   |
| HP ENVY               | 18        | 0.74%   |
| ASUS ZenBook          | 16        | 0.66%   |
| Lenovo ThinkBook      | 15        | 0.62%   |
| ASUS ASUS             | 15        | 0.62%   |
| Razer Blade           | 13        | 0.53%   |
| HP OMEN               | 13        | 0.53%   |
| HP Notebook           | 13        | 0.53%   |
| Framework Laptop      | 12        | 0.49%   |
| Lenovo Yoga           | 11        | 0.45%   |
| HP 250                | 11        | 0.45%   |
| Dell G3               | 11        | 0.45%   |
| HUAWEI NBLK-WAX9X     | 8         | 0.33%   |
| Fujitsu LIFEBOOK      | 8         | 0.33%   |
| ASUS Strix            | 8         | 0.33%   |
| HP ZBook              | 7         | 0.29%   |
| Dell G5               | 7         | 0.29%   |
| Acer Predator         | 7         | 0.29%   |
| MSI Modern            | 6         | 0.25%   |
| Lenovo Flex           | 6         | 0.25%   |
| HP Compaq             | 6         | 0.25%   |
| ASUS X580VD           | 6         | 0.25%   |
| Apple MacBookPro15    | 6         | 0.25%   |
| Acer TravelMate       | 6         | 0.25%   |
| TUXEDO InfinityBook   | 5         | 0.21%   |
| Timi TM1701           | 5         | 0.21%   |
| Timi RedmiBook        | 5         | 0.21%   |
| Schenker XMG          | 5         | 0.21%   |
| Packard Bell EasyNote | 5         | 0.21%   |
| HUAWEI MACH-WX9       | 5         | 0.21%   |
| HUAWEI BOHK-WAX9X     | 5         | 0.21%   |
| HP 255                | 5         | 0.21%   |
| Dell Studio           | 5         | 0.21%   |
| Apple MacBookPro9     | 5         | 0.21%   |
| Apple MacBookAir7     | 5         | 0.21%   |
| Acer Extensa          | 5         | 0.21%   |
| Samsung RV415         | 4         | 0.16%   |
| MSI GL63              | 4         | 0.16%   |
| MSI Bravo             | 4         | 0.16%   |
| Lenovo Y520-15IKBN    | 4         | 0.16%   |
| Lenovo V155-15API     | 4         | 0.16%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 357       | 14.68%  |
| 2018    | 313       | 12.87%  |
| 2020    | 307       | 12.62%  |
| 2017    | 211       | 8.68%   |
| 2021    | 210       | 8.63%   |
| 2016    | 167       | 6.87%   |
| 2015    | 149       | 6.13%   |
| 2012    | 143       | 5.88%   |
| 2013    | 130       | 5.35%   |
| 2014    | 128       | 5.26%   |
| 2011    | 127       | 5.22%   |
| 2010    | 80        | 3.29%   |
| 2008    | 50        | 2.06%   |
| 2009    | 35        | 1.44%   |
| 2022    | 14        | 0.58%   |
| 2007    | 7         | 0.29%   |
| 2006    | 3         | 0.12%   |
| Unknown | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 2432      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 2415      | 99.1%   |
| Enabled  | 22        | 0.9%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2404      | 98.85%  |
| Yes  | 28        | 1.15%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 645       | 26.2%   |
| 16.01-24.0  | 585       | 23.76%  |
| 8.01-16.0   | 554       | 22.5%   |
| 3.01-4.0    | 299       | 12.14%  |
| 32.01-64.0  | 238       | 9.67%   |
| 1.01-2.0    | 45        | 1.83%   |
| 64.01-256.0 | 37        | 1.5%    |
| 24.01-32.0  | 36        | 1.46%   |
| 2.01-3.0    | 18        | 0.73%   |
| 0.51-1.0    | 5         | 0.2%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 713       | 26.55%  |
| 2.01-3.0   | 700       | 26.06%  |
| 4.01-8.0   | 512       | 19.06%  |
| 3.01-4.0   | 439       | 16.34%  |
| 8.01-16.0  | 150       | 5.58%   |
| 0.51-1.0   | 119       | 4.43%   |
| 0.01-0.5   | 26        | 0.97%   |
| 16.01-24.0 | 17        | 0.63%   |
| 24.01-32.0 | 9         | 0.34%   |
| 32.01-64.0 | 1         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1669      | 67.41%  |
| 2      | 688       | 27.79%  |
| 3      | 93        | 3.76%   |
| 0      | 14        | 0.57%   |
| 4      | 9         | 0.36%   |
| 5      | 2         | 0.08%   |
| 6      | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1891      | 77.44%  |
| Yes       | 551       | 22.56%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1933      | 79.16%  |
| No        | 509       | 20.84%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2411      | 99.1%   |
| No        | 22        | 0.9%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2061      | 83.88%  |
| No        | 396       | 16.12%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 425       | 17.37%  |
| Germany      | 219       | 8.95%   |
| Russia       | 148       | 6.05%   |
| Brazil       | 142       | 5.8%    |
| France       | 114       | 4.66%   |
| India        | 110       | 4.5%    |
| Italy        | 92        | 3.76%   |
| UK           | 79        | 3.23%   |
| Poland       | 74        | 3.02%   |
| Canada       | 63        | 2.57%   |
| Spain        | 54        | 2.21%   |
| Netherlands  | 54        | 2.21%   |
| China        | 44        | 1.8%    |
| Turkey       | 40        | 1.63%   |
| Ukraine      | 39        | 1.59%   |
| Sweden       | 34        | 1.39%   |
| Austria      | 34        | 1.39%   |
| Australia    | 34        | 1.39%   |
| Belgium      | 28        | 1.14%   |
| Mexico       | 26        | 1.06%   |
| Indonesia    | 26        | 1.06%   |
| Czechia      | 21        | 0.86%   |
| Switzerland  | 20        | 0.82%   |
| Romania      | 20        | 0.82%   |
| Portugal     | 20        | 0.82%   |
| Iran         | 19        | 0.78%   |
| Japan        | 18        | 0.74%   |
| Argentina    | 18        | 0.74%   |
| Hungary      | 17        | 0.69%   |
| Greece       | 17        | 0.69%   |
| Finland      | 17        | 0.69%   |
| Colombia     | 17        | 0.69%   |
| New Zealand  | 16        | 0.65%   |
| Vietnam      | 15        | 0.61%   |
| Chile        | 14        | 0.57%   |
| Belarus      | 14        | 0.57%   |
| Norway       | 13        | 0.53%   |
| Denmark      | 11        | 0.45%   |
| Bangladesh   | 11        | 0.45%   |
| Taiwan       | 10        | 0.41%   |
| South Africa | 10        | 0.41%   |
| Slovakia     | 10        | 0.41%   |
| Serbia       | 10        | 0.41%   |
| Lithuania    | 10        | 0.41%   |
| Hong Kong    | 10        | 0.41%   |
| Bulgaria     | 10        | 0.41%   |
| Peru         | 9         | 0.37%   |
| Thailand     | 8         | 0.33%   |
| South Korea  | 8         | 0.33%   |
| Singapore    | 8         | 0.33%   |
| Estonia      | 8         | 0.33%   |
| Philippines  | 7         | 0.29%   |
| Latvia       | 7         | 0.29%   |
| Israel       | 7         | 0.29%   |
| Nepal        | 6         | 0.25%   |
| Ireland      | 6         | 0.25%   |
| Guatemala    | 6         | 0.25%   |
| Cyprus       | 6         | 0.25%   |
| Croatia      | 6         | 0.25%   |
| UAE          | 5         | 0.2%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 37        | 1.43%   |
| Sao Paulo         | 25        | 0.97%   |
| St Petersburg     | 23        | 0.89%   |
| Paris             | 21        | 0.81%   |
| Berlin            | 21        | 0.81%   |
| Warsaw            | 20        | 0.77%   |
| Vienna            | 18        | 0.7%    |
| Munich            | 18        | 0.7%    |
| Amsterdam         | 16        | 0.62%   |
| Los Angeles       | 15        | 0.58%   |
| Kyiv              | 15        | 0.58%   |
| Istanbul          | 15        | 0.58%   |
| Valencia          | 12        | 0.46%   |
| Frankfurt am Main | 12        | 0.46%   |
| Bengaluru         | 12        | 0.46%   |
| Tehran            | 11        | 0.43%   |
| Sydney            | 11        | 0.43%   |
| Prague            | 11        | 0.43%   |
| Milan             | 11        | 0.43%   |
| Phoenix           | 10        | 0.39%   |
| Montreal          | 10        | 0.39%   |
| Melbourne         | 10        | 0.39%   |
| Helsinki          | 10        | 0.39%   |
| Hamburg           | 10        | 0.39%   |
| Budapest          | 10        | 0.39%   |
| Cologne           | 9         | 0.35%   |
| Bogotá           | 9         | 0.35%   |
| Beijing           | 9         | 0.35%   |
| Athens            | 9         | 0.35%   |
| Seattle           | 8         | 0.31%   |
| Rome              | 8         | 0.31%   |
| New York          | 8         | 0.31%   |
| Mexico City       | 8         | 0.31%   |
| London            | 8         | 0.31%   |
| Krakow            | 8         | 0.31%   |
| Jakarta           | 8         | 0.31%   |
| Buenos Aires      | 8         | 0.31%   |
| Stockholm         | 7         | 0.27%   |
| Singapore         | 7         | 0.27%   |
| Ottawa            | 7         | 0.27%   |
| Minsk             | 7         | 0.27%   |
| Lille             | 7         | 0.27%   |
| Kolkata           | 7         | 0.27%   |
| Dhaka             | 7         | 0.27%   |
| Curitiba          | 7         | 0.27%   |
| Chennai           | 7         | 0.27%   |
| Baton Rouge       | 7         | 0.27%   |
| Washington        | 6         | 0.23%   |
| Vilnius           | 6         | 0.23%   |
| Toronto           | 6         | 0.23%   |
| Riga              | 6         | 0.23%   |
| Mumbai            | 6         | 0.23%   |
| Madrid            | 6         | 0.23%   |
| Lima              | 6         | 0.23%   |
| Florence          | 6         | 0.23%   |
| Dublin            | 6         | 0.23%   |
| Denver            | 6         | 0.23%   |
| Copenhagen        | 6         | 0.23%   |
| Brooklyn          | 6         | 0.23%   |
| Brasília         | 6         | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 662       | 871    | 20.6%   |
| WDC                         | 385       | 471    | 11.98%  |
| Seagate                     | 313       | 376    | 9.74%   |
| Toshiba                     | 248       | 288    | 7.72%   |
| SanDisk                     | 234       | 272    | 7.28%   |
| SK hynix                    | 178       | 211    | 5.54%   |
| Kingston                    | 159       | 195    | 4.95%   |
| Unknown                     | 133       | 160    | 4.14%   |
| Intel                       | 107       | 138    | 3.33%   |
| HGST                        | 98        | 105    | 3.05%   |
| Crucial                     | 95        | 130    | 2.96%   |
| Micron Technology           | 81        | 96     | 2.52%   |
| Hitachi                     | 53        | 54     | 1.65%   |
| A-DATA Technology           | 42        | 58     | 1.31%   |
| Apple                       | 31        | 38     | 0.96%   |
| Phison                      | 26        | 30     | 0.81%   |
| LITEON                      | 24        | 25     | 0.75%   |
| Transcend                   | 19        | 20     | 0.59%   |
| SPCC                        | 16        | 17     | 0.5%    |
| Lenovo                      | 16        | 18     | 0.5%    |
| KIOXIA                      | 16        | 18     | 0.5%    |
| China                       | 14        | 19     | 0.44%   |
| KingSpec                    | 10        | 11     | 0.31%   |
| Goodram                     | 10        | 10     | 0.31%   |
| Silicon Motion              | 9         | 9      | 0.28%   |
| PNY                         | 9         | 12     | 0.28%   |
| OCZ                         | 9         | 9      | 0.28%   |
| LITEONIT                    | 9         | 9      | 0.28%   |
| JMicron Technology          | 9         | 8      | 0.28%   |
| Patriot                     | 8         | 8      | 0.25%   |
| Lite-On                     | 8         | 10     | 0.25%   |
| Plextor                     | 7         | 7      | 0.22%   |
| Micron/Crucial Technology   | 7         | 8      | 0.22%   |
| FORESEE                     | 7         | 9      | 0.22%   |
| Corsair                     | 7         | 8      | 0.22%   |
| UMIS                        | 6         | 7      | 0.19%   |
| Lexar                       | 6         | 9      | 0.19%   |
| ADATA Technology            | 6         | 7      | 0.19%   |
| XPG                         | 5         | 7      | 0.16%   |
| Union Memory (Shenzhen)     | 5         | 5      | 0.16%   |
| Union Memory                | 5         | 5      | 0.16%   |
| External                    | 5         | 6      | 0.16%   |
| SABRENT                     | 4         | 4      | 0.12%   |
| Realtek Semiconductor       | 4         | 4      | 0.12%   |
| Intenso                     | 4         | 5      | 0.12%   |
| Hewlett-Packard             | 4         | 4      | 0.12%   |
| Fujitsu                     | 4         | 4      | 0.12%   |
| Team                        | 3         | 3      | 0.09%   |
| Netac                       | 3         | 5      | 0.09%   |
| Mushkin                     | 3         | 3      | 0.09%   |
| MAXIO Technology (Hangzhou) | 3         | 4      | 0.09%   |
| Gigabyte Technology         | 3         | 3      | 0.09%   |
| BHT                         | 3         | 5      | 0.09%   |
| ASMT                        | 3         | 4      | 0.09%   |
| XrayDisk                    | 2         | 3      | 0.06%   |
| Verbatim                    | 2         | 2      | 0.06%   |
| Teclast                     | 2         | 2      | 0.06%   |
| SSSTC                       | 2         | 2      | 0.06%   |
| Solid State Storage         | 2         | 2      | 0.06%   |
| Realtek                     | 2         | 2      | 0.06%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 68        | 2.02%   |
| Samsung NVMe SSD Drive 512GB         | 56        | 1.66%   |
| SanDisk NVMe SSD Drive 512GB         | 44        | 1.31%   |
| SK hynix NVMe SSD Drive 512GB        | 39        | 1.16%   |
| HGST HTS721010A9E630 1TB             | 39        | 1.16%   |
| Toshiba MQ04ABF100 1TB               | 33        | 0.98%   |
| Toshiba MQ01ABD100 1TB               | 33        | 0.98%   |
| Samsung SSD 860 EVO 500GB            | 31        | 0.92%   |
| Samsung NVMe SSD Drive 256GB         | 31        | 0.92%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 28        | 0.83%   |
| Samsung SSD 850 EVO 500GB            | 25        | 0.74%   |
| Kingston SA400S37240G 240GB SSD      | 25        | 0.74%   |
| SanDisk NVMe SSD Drive 256GB         | 21        | 0.62%   |
| Samsung SSD 970 EVO Plus 1TB         | 21        | 0.62%   |
| Toshiba NVMe SSD Drive 512GB         | 20        | 0.59%   |
| Seagate ST1000LM048-2E7172 1TB       | 20        | 0.59%   |
| WDC WD10SPZX-21Z10T0 1TB             | 19        | 0.56%   |
| Seagate ST2000LM007-1R8174 2TB       | 19        | 0.56%   |
| SanDisk NVMe SSD Drive 1TB           | 19        | 0.56%   |
| Samsung SSD 970 EVO Plus 500GB       | 19        | 0.56%   |
| HGST HTS541010A9E680 1TB             | 19        | 0.56%   |
| Samsung NVMe SSD Drive 1TB           | 18        | 0.53%   |
| Seagate ST500LT012-1DG142 500GB      | 17        | 0.5%    |
| Samsung NVMe SSD Drive 500GB         | 17        | 0.5%    |
| Crucial CT500MX500SSD1 500GB         | 17        | 0.5%    |
| Unknown MMC Card  32GB               | 16        | 0.48%   |
| Seagate ST1000LX015-1U7172 1TB       | 16        | 0.48%   |
| Samsung SSD 860 EVO 1TB              | 16        | 0.48%   |
| WDC WD10JPVX-22JC3T0 1TB             | 15        | 0.45%   |
| Intel SSDPEKNW512G8 512GB            | 15        | 0.45%   |
| Toshiba MQ01ABF050 500GB             | 14        | 0.42%   |
| SK hynix NVMe SSD Drive 256GB        | 14        | 0.42%   |
| Samsung MZVLB512HBJQ-000L7 512GB     | 14        | 0.42%   |
| Micron NVMe SSD Drive 512GB          | 14        | 0.42%   |
| Kingston SA400S37120G 120GB SSD      | 14        | 0.42%   |
| HGST HTS725050A7E630 500GB           | 14        | 0.42%   |
| Samsung SSD 970 EVO Plus 2TB         | 13        | 0.39%   |
| Samsung SSD 860 EVO 250GB            | 13        | 0.39%   |
| Samsung SSD 850 EVO 250GB            | 13        | 0.39%   |
| Kingston SA400S37480G 480GB SSD      | 13        | 0.39%   |
| Intel NVMe SSD Drive 512GB           | 13        | 0.39%   |
| Crucial CT1000MX500SSD1 1TB          | 13        | 0.39%   |
| Seagate ST1000LM049-2GH172 1TB       | 12        | 0.36%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB | 11        | 0.33%   |
| Seagate ST9500325AS 500GB            | 11        | 0.33%   |
| Seagate Expansion 1TB                | 11        | 0.33%   |
| WDC WD10SPZX-24Z10 1TB               | 10        | 0.3%    |
| Toshiba NVMe SSD Drive 256GB         | 10        | 0.3%    |
| Samsung NVMe SSD Drive 250GB         | 10        | 0.3%    |
| Samsung NVMe SSD Drive 1024GB        | 10        | 0.3%    |
| Intel SSDPEKNW010T8 1TB              | 10        | 0.3%    |
| Unknown MMC Card  64GB               | 9         | 0.27%   |
| Seagate ST2000LX001-1RG174 2TB       | 9         | 0.27%   |
| Samsung SSD 970 EVO Plus 250GB       | 9         | 0.27%   |
| WDC WDS500G2B0B-00YS70 500GB SSD     | 8         | 0.24%   |
| Unknown SD/MMC/MS PRO 64GB           | 8         | 0.24%   |
| Unknown MMC Card  128GB              | 8         | 0.24%   |
| SK hynix NVMe SSD Drive 1TB          | 8         | 0.24%   |
| Seagate ST500LM021-1KJ152 500GB      | 8         | 0.24%   |
| Seagate ST2000LM015-2E8174 2TB       | 8         | 0.24%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 306       | 367    | 37.05%  |
| WDC                 | 201       | 230    | 24.33%  |
| Toshiba             | 139       | 155    | 16.83%  |
| HGST                | 98        | 105    | 11.86%  |
| Hitachi             | 53        | 54     | 6.42%   |
| Unknown             | 8         | 10     | 0.97%   |
| Samsung Electronics | 7         | 7      | 0.85%   |
| Fujitsu             | 4         | 4      | 0.48%   |
| Apple               | 3         | 3      | 0.36%   |
| SABRENT             | 2         | 2      | 0.24%   |
| SAGE                | 1         | 1      | 0.12%   |
| PHD 3.0             | 1         | 1      | 0.12%   |
| NeoTech             | 1         | 1      | 0.12%   |
| Maxone              | 1         | 1      | 0.12%   |
| ASMT                | 1         | 1      | 0.12%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 271       | 338    | 26.44%  |
| SanDisk             | 122       | 137    | 11.9%   |
| Kingston            | 110       | 133    | 10.73%  |
| Crucial             | 82        | 108    | 8%      |
| WDC                 | 68        | 88     | 6.63%   |
| Toshiba             | 30        | 38     | 2.93%   |
| SK hynix            | 29        | 35     | 2.83%   |
| Micron Technology   | 29        | 34     | 2.83%   |
| Intel               | 26        | 30     | 2.54%   |
| A-DATA Technology   | 26        | 40     | 2.54%   |
| LITEON              | 21        | 22     | 2.05%   |
| Transcend           | 19        | 20     | 1.85%   |
| Apple               | 18        | 19     | 1.76%   |
| China               | 14        | 19     | 1.37%   |
| SPCC                | 12        | 12     | 1.17%   |
| KingSpec            | 10        | 11     | 0.98%   |
| OCZ                 | 9         | 9      | 0.88%   |
| LITEONIT            | 9         | 9      | 0.88%   |
| GOODRAM             | 9         | 9      | 0.88%   |
| PNY                 | 8         | 11     | 0.78%   |
| Patriot             | 8         | 8      | 0.78%   |
| Plextor             | 7         | 7      | 0.68%   |
| FORESEE             | 6         | 8      | 0.59%   |
| Lexar               | 5         | 8      | 0.49%   |
| Intenso             | 4         | 5      | 0.39%   |
| Unknown             | 3         | 3      | 0.29%   |
| Mushkin             | 3         | 3      | 0.29%   |
| Gigabyte Technology | 3         | 3      | 0.29%   |
| BHT                 | 3         | 5      | 0.29%   |
| ASMT                | 3         | 3      | 0.29%   |
| Verbatim            | 2         | 2      | 0.2%    |
| Teclast             | 2         | 2      | 0.2%    |
| Seagate             | 2         | 2      | 0.2%    |
| Netac               | 2         | 2      | 0.2%    |
| Lenovo              | 2         | 2      | 0.2%    |
| HS-SSD-E100         | 2         | 2      | 0.2%    |
| Hewlett-Packard     | 2         | 2      | 0.2%    |
| Dell                | 2         | 3      | 0.2%    |
| Corsair             | 2         | 3      | 0.2%    |
| Apacer              | 2         | 2      | 0.2%    |
| AEGO                | 2         | 2      | 0.2%    |
| ZHITAI              | 1         | 2      | 0.1%    |
| XrayDisk            | 1         | 1      | 0.1%    |
| Xinsujie            | 1         | 1      | 0.1%    |
| WALRAM              | 1         | 1      | 0.1%    |
| Union Memory        | 1         | 1      | 0.1%    |
| UMAX                | 1         | 1      | 0.1%    |
| TO Exter            | 1         | 2      | 0.1%    |
| Team                | 1         | 1      | 0.1%    |
| TCSUNBOW            | 1         | 2      | 0.1%    |
| StoreJet            | 1         | 1      | 0.1%    |
| Pioneer             | 1         | 1      | 0.1%    |
| Phison              | 1         | 1      | 0.1%    |
| OCZ-AGIL            | 1         | 1      | 0.1%    |
| MidasForce          | 1         | 1      | 0.1%    |
| Microtech           | 1         | 1      | 0.1%    |
| Micron 1            | 1         | 1      | 0.1%    |
| MicroDream          | 1         | 1      | 0.1%    |
| Kross Elegance      | 1         | 1      | 0.1%    |
| KIOXIA-EXCERIA      | 1         | 2      | 0.1%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 1132      | 1547   | 37.34%  |
| SSD     | 945       | 1241   | 31.17%  |
| HDD     | 802       | 942    | 26.45%  |
| MMC     | 123       | 147    | 4.06%   |
| Unknown | 30        | 31     | 0.99%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1481      | 2101   | 52.26%  |
| NVMe | 1127      | 1534   | 39.77%  |
| MMC  | 123       | 147    | 4.34%   |
| SAS  | 103       | 126    | 3.63%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1038      | 1348   | 59.97%  |
| 0.51-1.0   | 627       | 754    | 36.22%  |
| 1.01-2.0   | 61        | 75     | 3.52%   |
| 3.01-4.0   | 4         | 5      | 0.23%   |
| 2.01-3.0   | 1         | 1      | 0.06%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 699       | 27.63%  |
| 251-500        | 683       | 27%     |
| 501-1000       | 496       | 19.6%   |
| 1001-2000      | 261       | 10.32%  |
| 51-100         | 112       | 4.43%   |
| More than 3000 | 67        | 2.65%   |
| Unknown        | 65        | 2.57%   |
| 2001-3000      | 60        | 2.37%   |
| 21-50          | 46        | 1.82%   |
| 1-20           | 41        | 1.62%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 572       | 21.73%  |
| 101-250        | 507       | 19.26%  |
| 21-50          | 439       | 16.68%  |
| 51-100         | 390       | 14.82%  |
| 251-500        | 345       | 13.11%  |
| 501-1000       | 212       | 8.05%   |
| 1001-2000      | 70        | 2.66%   |
| Unknown        | 65        | 2.47%   |
| 2001-3000      | 17        | 0.65%   |
| More than 3000 | 15        | 0.57%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Notebooks | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| HGST HTS721010A9E630 1TB                | 7         | 7      | 4.02%   |
| Seagate ST1000LM035-1RK172 1TB          | 6         | 6      | 3.45%   |
| HGST HTS541010A9E680 1TB                | 6         | 6      | 3.45%   |
| SK hynix HFS128G39TND-N210A 128GB SSD   | 4         | 4      | 2.3%    |
| HGST HTS725050A7E630 500GB              | 4         | 4      | 2.3%    |
| HGST HTS545050A7E680 500GB              | 4         | 5      | 2.3%    |
| Seagate ST9500325AS 500GB               | 3         | 3      | 1.72%   |
| Seagate ST500LT012-1DG142 500GB         | 3         | 3      | 1.72%   |
| Seagate ST1000LX015-1U7172 1TB          | 3         | 4      | 1.72%   |
| Seagate ST1000LM014-SSHD-8GB            | 3         | 3      | 1.72%   |
| WDC WD10JPVX-22JC3T0 1TB                | 2         | 2      | 1.15%   |
| Toshiba MQ01ABD100 1TB                  | 2         | 2      | 1.15%   |
| Toshiba MK3276GSX 320GB                 | 2         | 2      | 1.15%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD | 2         | 2      | 1.15%   |
| Seagate ST9250315AS 250GB               | 2         | 2      | 1.15%   |
| Seagate ST500LT012-9WS142 500GB         | 2         | 2      | 1.15%   |
| Seagate ST500LM021-1KJ152 500GB         | 2         | 2      | 1.15%   |
| Seagate ST500LM012 HN-M500MBB 500GB     | 2         | 2      | 1.15%   |
| Seagate ST500LM000-SSHD-8GB             | 2         | 2      | 1.15%   |
| Seagate ST2000LX001-1RG174 2TB          | 2         | 2      | 1.15%   |
| Seagate ST1000LM048-2E7172 1TB          | 2         | 2      | 1.15%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 2         | 2      | 1.15%   |
| SanDisk SD7SB3Q256G1002 256GB SSD       | 2         | 2      | 1.15%   |
| Samsung Electronics SSD 970 EVO 2TB     | 2         | 2      | 1.15%   |
| LITEON CV8-8E128-HP 128GB SSD           | 2         | 2      | 1.15%   |
| Intel SSDSC2BF240A4L 240GB              | 2         | 2      | 1.15%   |
| Hitachi HTS723232A7A364 320GB           | 2         | 2      | 1.15%   |
| Hitachi HTS545050A7E380 500GB           | 2         | 3      | 1.15%   |
| Hitachi HTS545025B9A300 250GB           | 2         | 2      | 1.15%   |
| Hitachi HTS541680J9SA00 80GB            | 2         | 2      | 1.15%   |
| Hitachi HTS541616J9SA00 160GB           | 2         | 2      | 1.15%   |
| HGST HTS545050A7E380 500GB              | 2         | 2      | 1.15%   |
| WDC WDS100T2B0B-00YS70 1TB SSD          | 1         | 1      | 0.57%   |
| WDC WD7500BPKT-00PK4T0 752GB            | 1         | 1      | 0.57%   |
| WDC WD5000LPVX-80V0TT0 500GB            | 1         | 1      | 0.57%   |
| WDC WD5000LPCX-24VHAT0 500GB            | 1         | 1      | 0.57%   |
| WDC WD5000LPCX-00VHAT0 500GB            | 1         | 1      | 0.57%   |
| WDC WD5000BEVT-22ZAT0 500GB             | 1         | 1      | 0.57%   |
| WDC WD5000BEVT-11ZAT0 500GB             | 1         | 1      | 0.57%   |
| WDC WD5000BEKT-00KA9T0 500GB            | 1         | 1      | 0.57%   |
| WDC WD3200BPVT-22JJ5T0 320GB            | 1         | 1      | 0.57%   |
| WDC WD3200BEKT-60V5T1 320GB             | 1         | 1      | 0.57%   |
| WDC WD3200BEKT-60F3T1 320GB             | 1         | 1      | 0.57%   |
| WDC WD2500BEVT-22A23T0 250GB            | 1         | 1      | 0.57%   |
| WDC WD1600BEKT-60V5T1 160GB             | 1         | 1      | 0.57%   |
| WDC WD10JPVX-60JC3T1 1TB                | 1         | 2      | 0.57%   |
| WDC WD10JPVX-60JC3T0 1TB                | 1         | 2      | 0.57%   |
| WDC WD10JPVX-08JC3T6 1TB                | 1         | 1      | 0.57%   |
| Toshiba THNSNH256G8NT 256GB SSD         | 1         | 1      | 0.57%   |
| Toshiba MQ02ABD100H 1TB                 | 1         | 3      | 0.57%   |
| Toshiba MQ01ACF050 500GB                | 1         | 1      | 0.57%   |
| Toshiba MQ01ABD075 752GB                | 1         | 1      | 0.57%   |
| Toshiba MK7575GSX 752GB                 | 1         | 1      | 0.57%   |
| Toshiba MK6476GSX 640GB                 | 1         | 1      | 0.57%   |
| Toshiba MK6475GSX 640GB                 | 1         | 1      | 0.57%   |
| Toshiba MK6465GSX 640GB                 | 1         | 1      | 0.57%   |
| Toshiba MK5055GSX 500GB                 | 1         | 1      | 0.57%   |
| Toshiba MK3265GSXN 320GB                | 1         | 1      | 0.57%   |
| Toshiba KSG60ZSE512G SATA 512GB SSD     | 1         | 1      | 0.57%   |
| Toshiba HDWK105 500GB                   | 1         | 1      | 0.57%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 50        | 52     | 28.74%  |
| HGST                | 25        | 26     | 14.37%  |
| WDC                 | 18        | 20     | 10.34%  |
| Toshiba             | 18        | 20     | 10.34%  |
| Hitachi             | 16        | 17     | 9.2%    |
| SK hynix            | 8         | 9      | 4.6%    |
| Samsung Electronics | 8         | 9      | 4.6%    |
| SanDisk             | 6         | 7      | 3.45%   |
| Kingston            | 5         | 5      | 2.87%   |
| Intel               | 5         | 6      | 2.87%   |
| LITEON              | 3         | 3      | 1.72%   |
| Crucial             | 3         | 3      | 1.72%   |
| Micron Technology   | 2         | 3      | 1.15%   |
| ASMT                | 2         | 2      | 1.15%   |
| OCZ                 | 1         | 1      | 0.57%   |
| KingSpec            | 1         | 1      | 0.57%   |
| China               | 1         | 1      | 0.57%   |
| Apple               | 1         | 1      | 0.57%   |
| A-DATA Technology   | 1         | 1      | 0.57%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 50        | 52     | 40.65%  |
| HGST    | 25        | 26     | 20.33%  |
| WDC     | 17        | 19     | 13.82%  |
| Hitachi | 16        | 17     | 13.01%  |
| Toshiba | 14        | 16     | 11.38%  |
| Apple   | 1         | 1      | 0.81%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 122       | 131    | 70.52%  |
| SSD  | 42        | 44     | 24.28%  |
| NVMe | 9         | 12     | 5.2%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Samsung Electronics MZVLW128HEGR-000L2 128GB     | 1         | 2      | 33.33%  |
| Samsung Electronics MZNLN128HAHQ-000H1 128GB SSD | 1         | 1      | 33.33%  |
| Kingston SV300S37A120G 120GB SSD                 | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 3      | 66.67%  |
| Kingston            | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1271      | 1905   | 47.98%  |
| Works    | 1204      | 1812   | 45.45%  |
| Malfunc  | 171       | 187    | 6.46%   |
| Failed   | 3         | 4      | 0.11%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1581      | 52.26%  |
| Samsung Electronics              | 413       | 13.65%  |
| AMD                              | 297       | 9.82%   |
| SanDisk                          | 211       | 6.98%   |
| SK hynix                         | 146       | 4.83%   |
| Toshiba America Info Systems     | 79        | 2.61%   |
| Micron Technology                | 53        | 1.75%   |
| Kingston Technology Company      | 48        | 1.59%   |
| Phison Electronics               | 37        | 1.22%   |
| Micron/Crucial Technology        | 20        | 0.66%   |
| KIOXIA                           | 19        | 0.63%   |
| ADATA Technology                 | 19        | 0.63%   |
| Silicon Motion                   | 17        | 0.56%   |
| Union Memory (Shenzhen)          | 15        | 0.5%    |
| Lenovo                           | 14        | 0.46%   |
| Lite-On Technology               | 10        | 0.33%   |
| Apple                            | 10        | 0.33%   |
| Realtek Semiconductor            | 9         | 0.3%    |
| Solid State Storage Technology   | 6         | 0.2%    |
| Nvidia                           | 4         | 0.13%   |
| Yangtze Memory Technologies      | 3         | 0.1%    |
| Silicon Integrated Systems [SiS] | 3         | 0.1%    |
| MAXIO Technology (Hangzhou)      | 3         | 0.1%    |
| Marvell Technology Group         | 2         | 0.07%   |
| Biwin Storage Technology         | 2         | 0.07%   |
| ASMedia Technology               | 2         | 0.07%   |
| Unknown                          | 1         | 0.03%   |
| Shenzhen Longsys Electronics     | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 280       | 8.99%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 262       | 8.41%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 241       | 7.73%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 158       | 5.07%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 138       | 4.43%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 128       | 4.11%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 105       | 3.37%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 99        | 3.18%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 91        | 2.92%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 89        | 2.86%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 76        | 2.44%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 70        | 2.25%   |
| Samsung NVMe SSD Controller 980                                                  | 67        | 2.15%   |
| SK hynix Gold P31 SSD                                                            | 53        | 1.7%    |
| Micron Non-Volatile memory controller                                            | 53        | 1.7%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 50        | 1.6%    |
| Intel SSD 660P Series                                                            | 48        | 1.54%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 45        | 1.44%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 43        | 1.38%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 39        | 1.25%   |
| Intel Volume Management Device NVMe RAID Controller                              | 33        | 1.06%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 33        | 1.06%   |
| SK hynix Non-Volatile memory controller                                          | 32        | 1.03%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 32        | 1.03%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 32        | 1.03%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 29        | 0.93%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 28        | 0.9%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 27        | 0.87%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 25        | 0.8%    |
| Phison E12 NVMe Controller                                                       | 25        | 0.8%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 25        | 0.8%    |
| SK hynix BC501 NVMe Solid State Drive                                            | 24        | 0.77%   |
| SanDisk Non-Volatile memory controller                                           | 24        | 0.77%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 22        | 0.71%   |
| Intel Comet Lake SATA AHCI Controller                                            | 20        | 0.64%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 18        | 0.58%   |
| SK hynix BC511                                                                   | 18        | 0.58%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 18        | 0.58%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 16        | 0.51%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 15        | 0.48%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 15        | 0.48%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 15        | 0.48%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 14        | 0.45%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 14        | 0.45%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                      | 14        | 0.45%   |
| Lenovo Non-Volatile memory controller                                            | 14        | 0.45%   |
| Kingston Company Company Non-Volatile memory controller                          | 14        | 0.45%   |
| SanDisk PC SN520 NVMe SSD                                                        | 13        | 0.42%   |
| Kingston Company A2000 NVMe SSD                                                  | 13        | 0.42%   |
| Intel Tiger Lake-LP SATA Controller                                              | 13        | 0.42%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 12        | 0.39%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 12        | 0.39%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 12        | 0.39%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 12        | 0.39%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                             | 11        | 0.35%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 11        | 0.35%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                  | 11        | 0.35%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 11        | 0.35%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 11        | 0.35%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 10        | 0.32%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1656      | 55.11%  |
| NVMe | 1132      | 37.67%  |
| RAID | 173       | 5.76%   |
| IDE  | 44        | 1.46%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 1952      | 80.26%  |
| AMD    | 480       | 19.74%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 67        | 2.75%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 63        | 2.59%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 62        | 2.55%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 56        | 2.3%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 55        | 2.26%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 55        | 2.26%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 51        | 2.1%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 41        | 1.68%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 41        | 1.68%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 39        | 1.6%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 38        | 1.56%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 36        | 1.48%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 33        | 1.36%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 33        | 1.36%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 32        | 1.31%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 31        | 1.27%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 29        | 1.19%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 28        | 1.15%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 28        | 1.15%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 25        | 1.03%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 25        | 1.03%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 24        | 0.99%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 23        | 0.94%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 23        | 0.94%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 22        | 0.9%    |
| Intel Core i7-6500U CPU @ 2.50GHz             | 21        | 0.86%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 21        | 0.86%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 21        | 0.86%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 21        | 0.86%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 21        | 0.86%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 19        | 0.78%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 18        | 0.74%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 16        | 0.66%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 16        | 0.66%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 16        | 0.66%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 15        | 0.62%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 15        | 0.62%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 15        | 0.62%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 14        | 0.58%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 14        | 0.58%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 14        | 0.58%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 13        | 0.53%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 13        | 0.53%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 13        | 0.53%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 13        | 0.53%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 12        | 0.49%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 12        | 0.49%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 11        | 0.45%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 11        | 0.45%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 11        | 0.45%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 11        | 0.45%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 11        | 0.45%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 11        | 0.45%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 11        | 0.45%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 11        | 0.45%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 11        | 0.45%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 10        | 0.41%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 10        | 0.41%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 10        | 0.41%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 10        | 0.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 754       | 30.98%  |
| Intel Core i5           | 652       | 26.79%  |
| AMD Ryzen 5             | 156       | 6.41%   |
| Intel Core i3           | 149       | 6.12%   |
| AMD Ryzen 7             | 143       | 5.88%   |
| Other                   | 128       | 5.26%   |
| Intel Core 2 Duo        | 65        | 2.67%   |
| Intel Celeron           | 65        | 2.67%   |
| Intel Pentium           | 43        | 1.77%   |
| AMD Ryzen 7 PRO         | 43        | 1.77%   |
| Intel Atom              | 29        | 1.19%   |
| AMD Ryzen 9             | 27        | 1.11%   |
| Intel Core i9           | 26        | 1.07%   |
| AMD Ryzen 3             | 19        | 0.78%   |
| AMD Ryzen 5 PRO         | 14        | 0.58%   |
| AMD A6                  | 14        | 0.58%   |
| Intel Xeon              | 11        | 0.45%   |
| AMD A4                  | 11        | 0.45%   |
| AMD A10                 | 10        | 0.41%   |
| Intel Pentium Silver    | 7         | 0.29%   |
| Intel Pentium Dual-Core | 6         | 0.25%   |
| AMD E2                  | 6         | 0.25%   |
| Intel Genuine           | 5         | 0.21%   |
| AMD E                   | 5         | 0.21%   |
| AMD A8                  | 5         | 0.21%   |
| Intel Core m3           | 4         | 0.16%   |
| Intel Core 2            | 4         | 0.16%   |
| AMD E1                  | 4         | 0.16%   |
| AMD A12                 | 3         | 0.12%   |
| Intel Pentium Dual      | 2         | 0.08%   |
| Intel Core m7           | 2         | 0.08%   |
| Intel Core m5           | 2         | 0.08%   |
| Intel Core M            | 2         | 0.08%   |
| Intel Celeron Dual-Core | 2         | 0.08%   |
| AMD Phenom II           | 2         | 0.08%   |
| AMD FX                  | 2         | 0.08%   |
| AMD Athlon X2           | 2         | 0.08%   |
| AMD Athlon              | 2         | 0.08%   |
| Intel Core 2 Solo       | 1         | 0.04%   |
| Intel Celeron M         | 1         | 0.04%   |
| AMD Turion Neo X2       | 1         | 0.04%   |
| AMD Turion II Neo       | 1         | 0.04%   |
| AMD Turion II Dual-Core | 1         | 0.04%   |
| AMD Turion II           | 1         | 0.04%   |
| AMD C-60                | 1         | 0.04%   |
| AMD Athlon II           | 1         | 0.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 972       | 39.93%  |
| 4      | 953       | 39.15%  |
| 6      | 251       | 10.31%  |
| 8      | 234       | 9.61%   |
| 1      | 17        | 0.7%    |
| 14     | 3         | 0.12%   |
| 12     | 2         | 0.08%   |
| 5      | 1         | 0.04%   |
| 3      | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2432      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 2062      | 84.68%  |
| 1      | 373       | 15.32%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2371      | 97.41%  |
| Unknown        | 60        | 2.47%   |
| 32-bit         | 3         | 0.12%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 666       | 26.42%  |
| 0x806ea    | 119       | 4.72%   |
| 0x906ea    | 118       | 4.68%   |
| 0x306a9    | 107       | 4.24%   |
| 0x206a7    | 94        | 3.73%   |
| 0x806ec    | 91        | 3.61%   |
| 0x406e3    | 90        | 3.57%   |
| 0x306d4    | 84        | 3.33%   |
| 0x40651    | 77        | 3.05%   |
| 0x906e9    | 75        | 2.98%   |
| 0x806c1    | 70        | 2.78%   |
| 0x806e9    | 68        | 2.7%    |
| 0x08108102 | 66        | 2.62%   |
| 0x306c3    | 59        | 2.34%   |
| 0x08600106 | 57        | 2.26%   |
| 0xa0652    | 49        | 1.94%   |
| 0x0a50000c | 45        | 1.79%   |
| 0x20655    | 42        | 1.67%   |
| 0x506e3    | 38        | 1.51%   |
| 0x08600104 | 35        | 1.39%   |
| 0x08600103 | 35        | 1.39%   |
| 0x806eb    | 34        | 1.35%   |
| 0x08108109 | 33        | 1.31%   |
| 0x1067a    | 31        | 1.23%   |
| 0x0810100b | 24        | 0.95%   |
| 0x706e5    | 19        | 0.75%   |
| 0x406c4    | 18        | 0.71%   |
| 0x10676    | 17        | 0.67%   |
| 0x906ed    | 16        | 0.63%   |
| 0x706a1    | 15        | 0.6%    |
| 0x30678    | 15        | 0.6%    |
| 0x806d1    | 13        | 0.52%   |
| 0x506c9    | 13        | 0.52%   |
| 0x08608103 | 13        | 0.52%   |
| 0x20652    | 11        | 0.44%   |
| 0x06006705 | 11        | 0.44%   |
| 0x106ca    | 9         | 0.36%   |
| 0x08608102 | 9         | 0.36%   |
| 0x406c3    | 8         | 0.32%   |
| 0x08600102 | 7         | 0.28%   |
| 0x03000027 | 7         | 0.28%   |
| 0x6fd      | 6         | 0.24%   |
| 0x106e5    | 6         | 0.24%   |
| 0xa0660    | 5         | 0.2%    |
| 0x08101007 | 5         | 0.2%    |
| 0x0600611a | 5         | 0.2%    |
| 0x706a8    | 4         | 0.16%   |
| 0x6fb      | 4         | 0.16%   |
| 0x0a50000b | 4         | 0.16%   |
| 0x07030105 | 4         | 0.16%   |
| 0x06006704 | 4         | 0.16%   |
| 0x06006118 | 4         | 0.16%   |
| 0x06001119 | 4         | 0.16%   |
| 0x05000119 | 4         | 0.16%   |
| 0x806c2    | 3         | 0.12%   |
| 0x40661    | 3         | 0.12%   |
| 0x08701013 | 3         | 0.12%   |
| 0x906c0    | 2         | 0.08%   |
| 0x906a3    | 2         | 0.08%   |
| 0x6f6      | 2         | 0.08%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 712       | 29.26%  |
| Haswell          | 181       | 7.44%   |
| Skylake          | 178       | 7.32%   |
| IvyBridge        | 155       | 6.37%   |
| Zen 2            | 149       | 6.12%   |
| SandyBridge      | 130       | 5.34%   |
| Zen+             | 115       | 4.73%   |
| Broadwell        | 106       | 4.36%   |
| TigerLake        | 97        | 3.99%   |
| CometLake        | 80        | 3.29%   |
| Penryn           | 70        | 2.88%   |
| Zen 3            | 63        | 2.59%   |
| Westmere         | 59        | 2.42%   |
| Silvermont       | 55        | 2.26%   |
| Unknown          | 50        | 2.06%   |
| Zen              | 42        | 1.73%   |
| IceLake          | 36        | 1.48%   |
| Excavator        | 28        | 1.15%   |
| Goldmont plus    | 23        | 0.95%   |
| Core             | 16        | 0.66%   |
| Goldmont         | 14        | 0.58%   |
| Bonnell          | 13        | 0.53%   |
| Bobcat           | 9         | 0.37%   |
| Nehalem          | 8         | 0.33%   |
| Puma             | 7         | 0.29%   |
| Piledriver       | 7         | 0.29%   |
| K10 Llano        | 7         | 0.29%   |
| K10              | 6         | 0.25%   |
| Jaguar           | 6         | 0.25%   |
| Tremont          | 2         | 0.08%   |
| Steamroller      | 2         | 0.08%   |
| P6               | 2         | 0.08%   |
| K8 Hammer        | 2         | 0.08%   |
| Alderlake Hybrid | 2         | 0.08%   |
| K8 & K10 hybrid  | 1         | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1816      | 54.83%  |
| Nvidia                           | 865       | 26.12%  |
| AMD                              | 627       | 18.93%  |
| Silicon Integrated Systems [SiS] | 3         | 0.09%   |
| ATI Technologies                 | 1         | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 166       | 4.94%   |
| Intel UHD Graphics 620                                                                   | 157       | 4.67%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 147       | 4.37%   |
| AMD Renoir                                                                               | 143       | 4.25%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 121       | 3.6%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 116       | 3.45%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 116       | 3.45%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 101       | 3%      |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 100       | 2.97%   |
| Intel HD Graphics 620                                                                    | 93        | 2.77%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 90        | 2.68%   |
| Intel HD Graphics 5500                                                                   | 89        | 2.65%   |
| Intel HD Graphics 630                                                                    | 80        | 2.38%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 76        | 2.26%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 70        | 2.08%   |
| AMD Cezanne                                                                              | 60        | 1.78%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 59        | 1.75%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 59        | 1.75%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 48        | 1.43%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 46        | 1.37%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 45        | 1.34%   |
| Intel HD Graphics 530                                                                    | 45        | 1.34%   |
| Nvidia GP108M [GeForce MX150]                                                            | 40        | 1.19%   |
| Intel Core Processor Integrated Graphics Controller                                      | 40        | 1.19%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 39        | 1.16%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 36        | 1.07%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 33        | 0.98%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 30        | 0.89%   |
| AMD Lucienne                                                                             | 30        | 0.89%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 27        | 0.8%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 25        | 0.74%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 24        | 0.71%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 24        | 0.71%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 23        | 0.68%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 23        | 0.68%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 21        | 0.62%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 21        | 0.62%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 20        | 0.59%   |
| Nvidia TU117M                                                                            | 19        | 0.56%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 19        | 0.56%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 18        | 0.54%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 17        | 0.51%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 17        | 0.51%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 16        | 0.48%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 16        | 0.48%   |
| Nvidia GM108M [GeForce MX130]                                                            | 15        | 0.45%   |
| Nvidia GM108M [GeForce 940M]                                                             | 15        | 0.45%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 15        | 0.45%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 13        | 0.39%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                                  | 11        | 0.33%   |
| Nvidia GM108M [GeForce 840M]                                                             | 11        | 0.33%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 11        | 0.33%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 10        | 0.3%    |
| Nvidia GP108M [GeForce MX250]                                                            | 10        | 0.3%    |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 10        | 0.3%    |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                                 | 10        | 0.3%    |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 10        | 0.3%    |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 9         | 0.27%   |
| Intel HD Graphics 500                                                                    | 9         | 0.27%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 9         | 0.27%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1036      | 42.46%  |
| Intel + Nvidia           | 665       | 27.25%  |
| 1 x AMD                  | 382       | 15.66%  |
| Intel + AMD              | 109       | 4.47%   |
| 1 x Nvidia               | 105       | 4.3%    |
| AMD + Nvidia             | 95        | 3.89%   |
| 2 x AMD                  | 40        | 1.64%   |
| 1 x SiS                  | 3         | 0.12%   |
| Intel + 2 x Nvidia       | 2         | 0.08%   |
| Intel + AMD + 1 x Nvidia | 2         | 0.08%   |
| 2 x Intel                | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1930      | 78.71%  |
| Proprietary | 514       | 20.96%  |
| Unknown     | 8         | 0.33%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1663      | 66.65%  |
| 0.01-0.5   | 244       | 9.78%   |
| 1.01-2.0   | 241       | 9.66%   |
| 3.01-4.0   | 138       | 5.53%   |
| 0.51-1.0   | 103       | 4.13%   |
| 5.01-6.0   | 48        | 1.92%   |
| 7.01-8.0   | 45        | 1.8%    |
| 2.01-3.0   | 9         | 0.36%   |
| 8.01-16.0  | 4         | 0.16%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 603       | 20.17%  |
| LG Display              | 410       | 13.72%  |
| BOE                     | 402       | 13.45%  |
| Chimei Innolux          | 373       | 12.48%  |
| Samsung Electronics     | 248       | 8.3%    |
| Sharp                   | 132       | 4.42%   |
| Dell                    | 117       | 3.91%   |
| PANDA                   | 73        | 2.44%   |
| Goldstar                | 71        | 2.38%   |
| Lenovo                  | 69        | 2.31%   |
| Apple                   | 53        | 1.77%   |
| Hewlett-Packard         | 39        | 1.3%    |
| Acer                    | 35        | 1.17%   |
| BenQ                    | 33        | 1.1%    |
| AOC                     | 32        | 1.07%   |
| InfoVision              | 30        | 1%      |
| Philips                 | 27        | 0.9%    |
| Chi Mei Optoelectronics | 26        | 0.87%   |
| Ancor Communications    | 21        | 0.7%    |
| Iiyama                  | 19        | 0.64%   |
| CSO                     | 17        | 0.57%   |
| Sony                    | 11        | 0.37%   |
| ViewSonic               | 10        | 0.33%   |
| ASUSTek Computer        | 9         | 0.3%    |
| CPT                     | 8         | 0.27%   |
| NEC Computers           | 7         | 0.23%   |
| JDI                     | 7         | 0.23%   |
| Panasonic               | 6         | 0.2%    |
| Toshiba                 | 5         | 0.17%   |
| Eizo                    | 5         | 0.17%   |
| MSI                     | 4         | 0.13%   |
| LGD                     | 4         | 0.13%   |
| LG Philips              | 4         | 0.13%   |
| InnoLux Display         | 4         | 0.13%   |
| HannStar                | 4         | 0.13%   |
| TMX                     | 3         | 0.1%    |
| Pixio                   | 3         | 0.1%    |
| ITE                     | 3         | 0.1%    |
| Fujitsu Siemens         | 3         | 0.1%    |
| BOE Technology Group    | 3         | 0.1%    |
| Vizio                   | 2         | 0.07%   |
| Vestel Elektronik       | 2         | 0.07%   |
| Unknown                 | 2         | 0.07%   |
| SKY                     | 2         | 0.07%   |
| Olevia                  | 2         | 0.07%   |
| Mi                      | 2         | 0.07%   |
| Lenovo Group Limited    | 2         | 0.07%   |
| KDC                     | 2         | 0.07%   |
| IPS                     | 2         | 0.07%   |
| IBM                     | 2         | 0.07%   |
| Hitachi                 | 2         | 0.07%   |
| eMachines               | 2         | 0.07%   |
| Zoran                   | 1         | 0.03%   |
| ZLX                     | 1         | 0.03%   |
| YTH                     | 1         | 0.03%   |
| Viotek                  | 1         | 0.03%   |
| Valve                   | 1         | 0.03%   |
| TBT                     | 1         | 0.03%   |
| SLD                     | 1         | 0.03%   |
| Sceptre Tech            | 1         | 0.03%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 36        | 1.19%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 29        | 0.96%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 24        | 0.8%    |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch        | 23        | 0.76%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 20        | 0.66%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 18        | 0.6%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 18        | 0.6%    |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch        | 17        | 0.56%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 14        | 0.46%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 13        | 0.43%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 13        | 0.43%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 381x214mm 17.2-inch      | 13        | 0.43%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 13        | 0.43%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch         | 13        | 0.43%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 12        | 0.4%    |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 12        | 0.4%    |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 12        | 0.4%    |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 12        | 0.4%    |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 11        | 0.36%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch         | 11        | 0.36%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 10        | 0.33%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 10        | 0.33%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 10        | 0.33%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 10        | 0.33%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch         | 10        | 0.33%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch        | 10        | 0.33%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch               | 9         | 0.3%    |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch               | 9         | 0.3%    |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 9         | 0.3%    |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch          | 9         | 0.3%    |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 9         | 0.3%    |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 9         | 0.3%    |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch         | 9         | 0.3%    |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 8         | 0.27%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 8         | 0.27%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 8         | 0.27%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 8         | 0.27%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch      | 8         | 0.27%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                 | 8         | 0.27%   |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch                 | 8         | 0.27%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                 | 8         | 0.27%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch        | 8         | 0.27%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch         | 8         | 0.27%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 8         | 0.27%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 7         | 0.23%   |
| LG Display LCD Monitor LGD0608 1920x1080 309x174mm 14.0-inch          | 7         | 0.23%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch          | 7         | 0.23%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 7         | 0.23%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 7         | 0.23%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 7         | 0.23%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 7         | 0.23%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                 | 7         | 0.23%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                 | 7         | 0.23%   |
| AU Optronics LCD Monitor AUO423D 1920x1080 309x173mm 13.9-inch        | 7         | 0.23%   |
| AU Optronics LCD Monitor AUO408D 1920x1080 309x174mm 14.0-inch        | 7         | 0.23%   |
| AU Optronics LCD Monitor AUO2036 2560x1440 309x174mm 14.0-inch        | 7         | 0.23%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch               | 6         | 0.2%    |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x174mm 14.0-inch  | 6         | 0.2%    |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 309x174mm 14.0-inch | 6         | 0.2%    |
| Samsung Electronics LCD Monitor SDC364D 1920x1080 309x174mm 14.0-inch | 6         | 0.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1429      | 51.68%  |
| 1366x768 (WXGA)    | 579       | 20.94%  |
| 3840x2160 (4K)     | 151       | 5.46%   |
| 2560x1440 (QHD)    | 113       | 4.09%   |
| 1600x900 (HD+)     | 109       | 3.94%   |
| 1920x1200 (WUXGA)  | 48        | 1.74%   |
| 1280x800 (WXGA)    | 47        | 1.7%    |
| 1440x900 (WXGA+)   | 32        | 1.16%   |
| 1680x1050 (WSXGA+) | 27        | 0.98%   |
| 2560x1600          | 23        | 0.83%   |
| 3840x2400          | 20        | 0.72%   |
| 3440x1440          | 20        | 0.72%   |
| 2880x1800          | 20        | 0.72%   |
| 3200x1800 (QHD+)   | 17        | 0.61%   |
| 2560x1080          | 17        | 0.61%   |
| 1280x1024 (SXGA)   | 15        | 0.54%   |
| 2256x1504          | 12        | 0.43%   |
| 1360x768           | 11        | 0.4%    |
| 2160x1440          | 8         | 0.29%   |
| 3000x2000          | 7         | 0.25%   |
| 3840x1600          | 6         | 0.22%   |
| 1024x600           | 6         | 0.22%   |
| Unknown            | 6         | 0.22%   |
| 1280x720 (HD)      | 5         | 0.18%   |
| 3072x1920          | 4         | 0.14%   |
| 2240x1400          | 3         | 0.11%   |
| 1920x540           | 3         | 0.11%   |
| 1680x945           | 3         | 0.11%   |
| 3840x1080          | 2         | 0.07%   |
| 3456x2160          | 2         | 0.07%   |
| 3200x2000          | 2         | 0.07%   |
| 1920x1280          | 2         | 0.07%   |
| 1600x1200          | 2         | 0.07%   |
| 7680x1440          | 1         | 0.04%   |
| 5520x1080          | 1         | 0.04%   |
| 4480x1440          | 1         | 0.04%   |
| 3840x1100          | 1         | 0.04%   |
| 3286x1080          | 1         | 0.04%   |
| 2560x1700          | 1         | 0.04%   |
| 2520x1680          | 1         | 0.04%   |
| 2400x1600          | 1         | 0.04%   |
| 2048x1536          | 1         | 0.04%   |
| 2048x1152          | 1         | 0.04%   |
| 1920x550           | 1         | 0.04%   |
| 1400x1050          | 1         | 0.04%   |
| 1280x768           | 1         | 0.04%   |
| 1024x768 (XGA)     | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1156      | 38.73%  |
| 13      | 481       | 16.11%  |
| 14      | 400       | 13.4%   |
| 17      | 154       | 5.16%   |
| 27      | 142       | 4.76%   |
| 24      | 129       | 4.32%   |
| 23      | 94        | 3.15%   |
| 12      | 86        | 2.88%   |
| 21      | 57        | 1.91%   |
| Unknown | 36        | 1.21%   |
| 34      | 34        | 1.14%   |
| 11      | 33        | 1.11%   |
| 18      | 25        | 0.84%   |
| 16      | 24        | 0.8%    |
| 31      | 21        | 0.7%    |
| 19      | 16        | 0.54%   |
| 20      | 14        | 0.47%   |
| 22      | 12        | 0.4%    |
| 10      | 11        | 0.37%   |
| 72      | 8         | 0.27%   |
| 84      | 7         | 0.23%   |
| 25      | 6         | 0.2%    |
| 54      | 5         | 0.17%   |
| 37      | 5         | 0.17%   |
| 28      | 5         | 0.17%   |
| 29      | 4         | 0.13%   |
| 40      | 3         | 0.1%    |
| 48      | 2         | 0.07%   |
| 32      | 2         | 0.07%   |
| 26      | 2         | 0.07%   |
| 74      | 1         | 0.03%   |
| 55      | 1         | 0.03%   |
| 52      | 1         | 0.03%   |
| 50      | 1         | 0.03%   |
| 47      | 1         | 0.03%   |
| 46      | 1         | 0.03%   |
| 42      | 1         | 0.03%   |
| 38      | 1         | 0.03%   |
| 35      | 1         | 0.03%   |
| 9       | 1         | 0.03%   |
| 8       | 1         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 1780      | 60.34%  |
| 201-300     | 371       | 12.58%  |
| 501-600     | 334       | 11.32%  |
| 351-400     | 191       | 6.47%   |
| 401-500     | 114       | 3.86%   |
| 601-700     | 47        | 1.59%   |
| 701-800     | 36        | 1.22%   |
| Unknown     | 36        | 1.22%   |
| 1501-2000   | 16        | 0.54%   |
| 1001-1500   | 12        | 0.41%   |
| 801-900     | 10        | 0.34%   |
| 101-200     | 2         | 0.07%   |
| 901-1000    | 1         | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 2199      | 85.6%   |
| 16/10   | 230       | 8.95%   |
| 21/9    | 42        | 1.63%   |
| 3/2     | 39        | 1.52%   |
| Unknown | 25        | 0.97%   |
| 5/4     | 17        | 0.66%   |
| 4/3     | 8         | 0.31%   |
| 32/9    | 4         | 0.16%   |
| 2.65    | 3         | 0.12%   |
| 3.40    | 1         | 0.04%   |
| 1.03    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1157      | 38.93%  |
| 81-90          | 681       | 22.91%  |
| 201-250        | 243       | 8.18%   |
| 71-80          | 197       | 6.63%   |
| 301-350        | 144       | 4.85%   |
| 121-130        | 131       | 4.41%   |
| 61-70          | 83        | 2.79%   |
| 351-500        | 60        | 2.02%   |
| 251-300        | 47        | 1.58%   |
| 151-200        | 40        | 1.35%   |
| Unknown        | 36        | 1.21%   |
| 51-60          | 34        | 1.14%   |
| 141-150        | 28        | 0.94%   |
| More than 1000 | 24        | 0.81%   |
| 111-120        | 16        | 0.54%   |
| 131-140        | 14        | 0.47%   |
| 501-1000       | 14        | 0.47%   |
| 41-50          | 12        | 0.4%    |
| 91-100         | 10        | 0.34%   |
| 1-40           | 1         | 0.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1362      | 46.72%  |
| 101-120       | 663       | 22.74%  |
| 51-100        | 426       | 14.61%  |
| 161-240       | 261       | 8.95%   |
| More than 240 | 140       | 4.8%    |
| Unknown       | 36        | 1.23%   |
| 1-50          | 27        | 0.93%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1923      | 77.38%  |
| 2     | 490       | 19.72%  |
| 3     | 57        | 2.29%   |
| 0     | 10        | 0.4%    |
| 4     | 5         | 0.2%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1507      | 38.99%  |
| Realtek Semiconductor             | 1273      | 32.94%  |
| Qualcomm Atheros                  | 518       | 13.4%   |
| Broadcom                          | 162       | 4.19%   |
| MediaTek                          | 47        | 1.22%   |
| Broadcom Limited                  | 38        | 0.98%   |
| Lenovo                            | 33        | 0.85%   |
| Ericsson Business Mobile Networks | 22        | 0.57%   |
| Sierra Wireless                   | 21        | 0.54%   |
| ASIX Electronics                  | 21        | 0.54%   |
| TP-Link                           | 20        | 0.52%   |
| Marvell Technology Group          | 20        | 0.52%   |
| Ralink Technology                 | 15        | 0.39%   |
| Ralink                            | 15        | 0.39%   |
| Qualcomm                          | 15        | 0.39%   |
| Hewlett-Packard                   | 14        | 0.36%   |
| DisplayLink                       | 13        | 0.34%   |
| Apple                             | 11        | 0.28%   |
| Samsung Electronics               | 10        | 0.26%   |
| Dell                              | 10        | 0.26%   |
| Xiaomi                            | 9         | 0.23%   |
| Huawei Technologies               | 8         | 0.21%   |
| D-Link                            | 7         | 0.18%   |
| NetGear                           | 6         | 0.16%   |
| Cypress Semiconductor             | 6         | 0.16%   |
| JMicron Technology                | 5         | 0.13%   |
| Linksys                           | 4         | 0.1%    |
| Fibocom                           | 4         | 0.1%    |
| Silicon Integrated Systems [SiS]  | 3         | 0.08%   |
| Qualcomm Atheros Communications   | 3         | 0.08%   |
| Nvidia                            | 3         | 0.08%   |
| Microsoft                         | 3         | 0.08%   |
| Google                            | 3         | 0.08%   |
| Arduino SA                        | 3         | 0.08%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.05%   |
| Motorola PCS                      | 2         | 0.05%   |
| ASUSTek Computer                  | 2         | 0.05%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.03%   |
| SEGGER                            | 1         | 0.03%   |
| QNAP System                       | 1         | 0.03%   |
| LG Electronics                    | 1         | 0.03%   |
| ICS Advent                        | 1         | 0.03%   |
| HMD Global                        | 1         | 0.03%   |
| Edimax Technology                 | 1         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 864       | 18.64%  |
| Intel Wi-Fi 6 AX200                                               | 229       | 4.94%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 173       | 3.73%   |
| Intel Wireless 8265 / 8275                                        | 160       | 3.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 117       | 2.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 105       | 2.27%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 104       | 2.24%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 98        | 2.11%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 95        | 2.05%   |
| Intel Wireless 7265                                               | 93        | 2.01%   |
| Intel Wireless 8260                                               | 80        | 1.73%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 74        | 1.6%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 70        | 1.51%   |
| Intel Wireless 7260                                               | 70        | 1.51%   |
| Intel Wi-Fi 6 AX201                                               | 68        | 1.47%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 66        | 1.42%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 64        | 1.38%   |
| Intel Wireless 3165                                               | 62        | 1.34%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 58        | 1.25%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 58        | 1.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 56        | 1.21%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 51        | 1.1%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 46        | 0.99%   |
| Intel Wireless-AC 9260                                            | 43        | 0.93%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 43        | 0.93%   |
| Intel Ethernet Connection (4) I219-V                              | 42        | 0.91%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 41        | 0.88%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 36        | 0.78%   |
| Intel Wireless 3160                                               | 36        | 0.78%   |
| Intel Ethernet Connection (6) I219-V                              | 36        | 0.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 35        | 0.76%   |
| Intel Ethernet Connection (4) I219-LM                             | 33        | 0.71%   |
| Intel Ethernet Connection I217-LM                                 | 32        | 0.69%   |
| Intel Ethernet Connection (3) I218-LM                             | 32        | 0.69%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 32        | 0.69%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 32        | 0.69%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 29        | 0.63%   |
| Intel Ethernet Connection I219-LM                                 | 26        | 0.56%   |
| Intel Ethernet Connection I218-LM                                 | 23        | 0.5%    |
| Intel Ethernet Connection (7) I219-LM                             | 23        | 0.5%    |
| Intel 82577LM Gigabit Network Connection                          | 23        | 0.5%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 22        | 0.47%   |
| Intel 82567LM Gigabit Network Connection                          | 22        | 0.47%   |
| Intel Ethernet Connection (2) I219-LM                             | 21        | 0.45%   |
| Intel Centrino Advanced-N 6235                                    | 21        | 0.45%   |
| Intel Ethernet Connection (6) I219-LM                             | 20        | 0.43%   |
| Broadcom BCM43142 802.11b/g/n                                     | 20        | 0.43%   |
| Intel Centrino Ultimate-N 6300                                    | 19        | 0.41%   |
| ASIX AX88179 Gigabit Ethernet                                     | 18        | 0.39%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 17        | 0.37%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 15        | 0.32%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 15        | 0.32%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 15        | 0.32%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 15        | 0.32%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 15        | 0.32%   |
| Intel Centrino Advanced-N 6200                                    | 15        | 0.32%   |
| Intel Ethernet Connection I219-V                                  | 14        | 0.3%    |
| Intel Centrino Wireless-N 2230                                    | 14        | 0.3%    |
| Broadcom BCM43224 802.11a/b/g/n                                   | 14        | 0.3%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 13        | 0.28%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1451      | 57.72%  |
| Qualcomm Atheros                | 435       | 17.3%   |
| Realtek Semiconductor           | 301       | 11.97%  |
| Broadcom                        | 139       | 5.53%   |
| MediaTek                        | 44        | 1.75%   |
| Broadcom Limited                | 29        | 1.15%   |
| Sierra Wireless                 | 21        | 0.84%   |
| TP-Link                         | 15        | 0.6%    |
| Ralink Technology               | 15        | 0.6%    |
| Ralink                          | 15        | 0.6%    |
| Qualcomm                        | 12        | 0.48%   |
| NetGear                         | 5         | 0.2%    |
| Hewlett-Packard                 | 5         | 0.2%    |
| D-Link                          | 5         | 0.2%    |
| Linksys                         | 4         | 0.16%   |
| Fibocom                         | 4         | 0.16%   |
| Dell                            | 4         | 0.16%   |
| Qualcomm Atheros Communications | 3         | 0.12%   |
| Xiaomi                          | 2         | 0.08%   |
| ASUSTek Computer                | 2         | 0.08%   |
| Microsoft                       | 1         | 0.04%   |
| Marvell Technology Group        | 1         | 0.04%   |
| Edimax Technology               | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 229       | 9.08%   |
| Intel Wireless 8265 / 8275                                     | 160       | 6.34%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 117       | 4.64%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 98        | 3.89%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 95        | 3.77%   |
| Intel Wireless 7265                                            | 93        | 3.69%   |
| Intel Wireless 8260                                            | 80        | 3.17%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 74        | 2.93%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 70        | 2.78%   |
| Intel Wireless 7260                                            | 70        | 2.78%   |
| Intel Wi-Fi 6 AX201                                            | 68        | 2.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 66        | 2.62%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 64        | 2.54%   |
| Intel Wireless 3165                                            | 62        | 2.46%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 58        | 2.3%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 58        | 2.3%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 56        | 2.22%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 51        | 2.02%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 46        | 1.82%   |
| Intel Wireless-AC 9260                                         | 43        | 1.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 43        | 1.7%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 41        | 1.63%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 36        | 1.43%   |
| Intel Wireless 3160                                            | 36        | 1.43%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 35        | 1.39%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 32        | 1.27%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 32        | 1.27%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 29        | 1.15%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 22        | 0.87%   |
| Intel Centrino Advanced-N 6235                                 | 21        | 0.83%   |
| Broadcom BCM43142 802.11b/g/n                                  | 20        | 0.79%   |
| Intel Centrino Ultimate-N 6300                                 | 19        | 0.75%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 15        | 0.59%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 15        | 0.59%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 15        | 0.59%   |
| Intel Centrino Advanced-N 6200                                 | 15        | 0.59%   |
| Intel Centrino Wireless-N 2230                                 | 14        | 0.56%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 14        | 0.56%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 13        | 0.52%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 13        | 0.52%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 12        | 0.48%   |
| Intel WiFi Link 5100                                           | 11        | 0.44%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 11        | 0.44%   |
| Sierra Wireless EM7455                                         | 10        | 0.4%    |
| Intel Tiger Lake PCH CNVi WiFi                                 | 10        | 0.4%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 10        | 0.4%    |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 10        | 0.4%    |
| Broadcom BCM4364 802.11ac Wireless Network Adapter             | 9         | 0.36%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 9         | 0.36%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 8         | 0.32%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 8         | 0.32%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 8         | 0.32%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter             | 8         | 0.32%   |
| Sierra Wireless EM7345 4G LTE                                  | 7         | 0.28%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 7         | 0.28%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 7         | 0.28%   |
| Realtek 802.11ac NIC                                           | 7         | 0.28%   |
| Qualcomm QCA6390 Wireless Network Adapter                      | 7         | 0.28%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 7         | 0.28%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 7         | 0.28%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1159      | 56.9%   |
| Intel                            | 535       | 26.26%  |
| Qualcomm Atheros                 | 124       | 6.09%   |
| Broadcom                         | 44        | 2.16%   |
| Lenovo                           | 33        | 1.62%   |
| ASIX Electronics                 | 21        | 1.03%   |
| Marvell Technology Group         | 19        | 0.93%   |
| DisplayLink                      | 13        | 0.64%   |
| Apple                            | 11        | 0.54%   |
| Samsung Electronics              | 10        | 0.49%   |
| Broadcom Limited                 | 9         | 0.44%   |
| Xiaomi                           | 7         | 0.34%   |
| Cypress Semiconductor            | 6         | 0.29%   |
| TP-Link                          | 5         | 0.25%   |
| JMicron Technology               | 5         | 0.25%   |
| Huawei Technologies              | 4         | 0.2%    |
| Silicon Integrated Systems [SiS] | 3         | 0.15%   |
| Qualcomm                         | 3         | 0.15%   |
| Nvidia                           | 3         | 0.15%   |
| MediaTek                         | 3         | 0.15%   |
| Hewlett-Packard                  | 3         | 0.15%   |
| Google                           | 3         | 0.15%   |
| OnePlus Technology (Shenzhen)    | 2         | 0.1%    |
| Motorola PCS                     | 2         | 0.1%    |
| Microsoft                        | 2         | 0.1%    |
| D-Link                           | 2         | 0.1%    |
| ZTE WCDMA Technologies MSM       | 1         | 0.05%   |
| QNAP System                      | 1         | 0.05%   |
| NetGear                          | 1         | 0.05%   |
| LG Electronics                   | 1         | 0.05%   |
| ICS Advent                       | 1         | 0.05%   |
| HMD Global                       | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 864       | 41.78%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 173       | 8.37%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 105       | 5.08%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 104       | 5.03%   |
| Intel Ethernet Connection (4) I219-V                              | 42        | 2.03%   |
| Intel Ethernet Connection (6) I219-V                              | 36        | 1.74%   |
| Intel Ethernet Connection (4) I219-LM                             | 33        | 1.6%    |
| Intel Ethernet Connection I217-LM                                 | 32        | 1.55%   |
| Intel Ethernet Connection (3) I218-LM                             | 32        | 1.55%   |
| Intel Ethernet Connection I219-LM                                 | 26        | 1.26%   |
| Intel Ethernet Connection I218-LM                                 | 23        | 1.11%   |
| Intel Ethernet Connection (7) I219-LM                             | 23        | 1.11%   |
| Intel 82577LM Gigabit Network Connection                          | 23        | 1.11%   |
| Intel 82567LM Gigabit Network Connection                          | 22        | 1.06%   |
| Intel Ethernet Connection (2) I219-LM                             | 21        | 1.02%   |
| Intel Ethernet Connection (6) I219-LM                             | 20        | 0.97%   |
| ASIX AX88179 Gigabit Ethernet                                     | 18        | 0.87%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 17        | 0.82%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 15        | 0.73%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 15        | 0.73%   |
| Intel Ethernet Connection I219-V                                  | 14        | 0.68%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 13        | 0.63%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 13        | 0.63%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 11        | 0.53%   |
| Intel Ethernet Connection (10) I219-V                             | 11        | 0.53%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 9         | 0.44%   |
| Lenovo USB-C Dock Ethernet                                        | 9         | 0.44%   |
| Intel Ethernet Connection (13) I219-V                             | 9         | 0.44%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 9         | 0.44%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 8         | 0.39%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 8         | 0.39%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 8         | 0.39%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 8         | 0.39%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 8         | 0.39%   |
| Intel Ethernet Connection (5) I219-LM                             | 8         | 0.39%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 8         | 0.39%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 7         | 0.34%   |
| Realtek RTL8125 2.5GbE Controller                                 | 7         | 0.34%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 7         | 0.34%   |
| Intel Ethernet Connection (7) I219-V                              | 7         | 0.34%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 7         | 0.34%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                  | 6         | 0.29%   |
| Cypress K38231_03                                                 | 6         | 0.29%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 6         | 0.29%   |
| Apple iBridge                                                     | 6         | 0.29%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 5         | 0.24%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 5         | 0.24%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 5         | 0.24%   |
| Lenovo ThinkPad Lan                                               | 5         | 0.24%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 5         | 0.24%   |
| Intel I210 Gigabit Network Connection                             | 5         | 0.24%   |
| Intel 82579V Gigabit Network Connection                           | 5         | 0.24%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 5         | 0.24%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 5         | 0.24%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 4         | 0.19%   |
| Realtek Killer E3000 2.5GbE Controller                            | 4         | 0.19%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 4         | 0.19%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 4         | 0.19%   |
| Intel Ethernet controller                                         | 4         | 0.19%   |
| Intel Ethernet Connection I217-V                                  | 4         | 0.19%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2412      | 55.01%  |
| Ethernet | 1929      | 43.99%  |
| Modem    | 41        | 0.94%   |
| Unknown  | 3         | 0.07%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2044      | 78.98%  |
| Ethernet | 543       | 20.98%  |
| Modem    | 1         | 0.04%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1759      | 72.27%  |
| 1     | 620       | 25.47%  |
| 3     | 32        | 1.31%   |
| 0     | 22        | 0.9%    |
| 4     | 1         | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2141      | 87.1%   |
| Yes  | 317       | 12.9%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1186      | 57.05%  |
| Qualcomm Atheros Communications | 186       | 8.95%   |
| Realtek Semiconductor           | 176       | 8.47%   |
| Broadcom                        | 106       | 5.1%    |
| Lite-On Technology              | 94        | 4.52%   |
| IMC Networks                    | 93        | 4.47%   |
| Foxconn / Hon Hai               | 65        | 3.13%   |
| Apple                           | 38        | 1.83%   |
| Realtek                         | 26        | 1.25%   |
| Dell                            | 26        | 1.25%   |
| Cambridge Silicon Radio         | 21        | 1.01%   |
| Hewlett-Packard                 | 14        | 0.67%   |
| Toshiba                         | 8         | 0.38%   |
| Ralink                          | 8         | 0.38%   |
| Foxconn International           | 5         | 0.24%   |
| ASUSTek Computer                | 5         | 0.24%   |
| MediaTek                        | 4         | 0.19%   |
| Chicony Electronics             | 3         | 0.14%   |
| Ralink Technology               | 2         | 0.1%    |
| Askey Computer                  | 2         | 0.1%    |
| Alps Electric                   | 2         | 0.1%    |
| USI                             | 1         | 0.05%   |
| Unknown                         | 1         | 0.05%   |
| TP-Link                         | 1         | 0.05%   |
| Syntek                          | 1         | 0.05%   |
| Micro Star International        | 1         | 0.05%   |
| Marvell Semiconductor           | 1         | 0.05%   |
| Edimax Technology               | 1         | 0.05%   |
| Dynex                           | 1         | 0.05%   |
| Belkin Components               | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 482       | 23.15%  |
| Intel AX200 Bluetooth                               | 214       | 10.28%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 176       | 8.45%   |
| Intel AX201 Bluetooth                               | 162       | 7.78%   |
| Qualcomm Atheros  Bluetooth Device                  | 132       | 6.34%   |
| Realtek Bluetooth Radio                             | 95        | 4.56%   |
| Intel AX210 Bluetooth                               | 46        | 2.21%   |
| Realtek  Bluetooth 4.2 Adapter                      | 45        | 2.16%   |
| Intel Bluetooth Device                              | 45        | 2.16%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 35        | 1.68%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 35        | 1.68%   |
| Foxconn / Hon Hai Bluetooth Device                  | 35        | 1.68%   |
| Lite-On Bluetooth Device                            | 33        | 1.59%   |
| IMC Networks Bluetooth Radio                        | 30        | 1.44%   |
| Intel Wireless-AC 3168 Bluetooth                    | 28        | 1.34%   |
| Realtek Bluetooth Radio                             | 26        | 1.25%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 26        | 1.25%   |
| IMC Networks Bluetooth Device                       | 25        | 1.2%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 22        | 1.06%   |
| Broadcom BCM2045B (BDC-2.1)                         | 22        | 1.06%   |
| IMC Networks Wireless_Device                        | 21        | 1.01%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 21        | 1.01%   |
| Apple Bluetooth Host Controller                     | 21        | 1.01%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 17        | 0.82%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 14        | 0.67%   |
| Realtek RTL8723B Bluetooth                          | 11        | 0.53%   |
| Lite-On Atheros AR3012 Bluetooth                    | 11        | 0.53%   |
| Apple Bluetooth USB Host Controller                 | 11        | 0.53%   |
| Dell DW375 Bluetooth Module                         | 10        | 0.48%   |
| Realtek RTL8821A Bluetooth                          | 9         | 0.43%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 9         | 0.43%   |
| Foxconn / Hon Hai Wireless_Device                   | 9         | 0.43%   |
| Ralink RT3290 Bluetooth                             | 8         | 0.38%   |
| Lite-On Wireless_Device                             | 8         | 0.38%   |
| HP Broadcom 2070 Bluetooth Combo                    | 8         | 0.38%   |
| Dell BCM20702A0 Bluetooth Module                    | 8         | 0.38%   |
| Broadcom HP Portable SoftSailing                    | 8         | 0.38%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 8         | 0.38%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 7         | 0.34%   |
| Foxconn / Hon Hai BCM20702A0                        | 6         | 0.29%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 6         | 0.29%   |
| Broadcom BCM2045A0                                  | 6         | 0.29%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 5         | 0.24%   |
| IMC Networks Bluetooth USB Host Controller          | 5         | 0.24%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 5         | 0.24%   |
| Foxconn International BCM43142A0 Bluetooth module   | 5         | 0.24%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 5         | 0.24%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 5         | 0.24%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 4         | 0.19%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 4         | 0.19%   |
| Broadcom BCM2070 Bluetooth Device                   | 4         | 0.19%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 4         | 0.19%   |
| Toshiba Bluetooth USB Host Controller               | 3         | 0.14%   |
| MediaTek Wireless_Device                            | 3         | 0.14%   |
| Foxconn / Hon Hai Acer Module                       | 3         | 0.14%   |
| Dell Wireless 360 Bluetooth                         | 3         | 0.14%   |
| Dell Wireless 355 Bluetooth                         | 3         | 0.14%   |
| Chicony Bluetooth (RTL8723BE)                       | 3         | 0.14%   |
| Broadcom HP Portable Valentine                      | 3         | 0.14%   |
| Broadcom BCM20702A0 Bluetooth                       | 3         | 0.14%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1919      | 60.21%  |
| AMD                                  | 532       | 16.69%  |
| Nvidia                               | 455       | 14.28%  |
| Lenovo                               | 31        | 0.97%   |
| C-Media Electronics                  | 31        | 0.97%   |
| Realtek Semiconductor                | 27        | 0.85%   |
| Texas Instruments                    | 16        | 0.5%    |
| Logitech                             | 15        | 0.47%   |
| JMTek                                | 13        | 0.41%   |
| Apple                                | 13        | 0.41%   |
| Kingston Technology                  | 11        | 0.35%   |
| Focusrite-Novation                   | 11        | 0.35%   |
| GN Netcom                            | 10        | 0.31%   |
| SteelSeries ApS                      | 7         | 0.22%   |
| Razer USA                            | 7         | 0.22%   |
| Plantronics                          | 6         | 0.19%   |
| Creative Technology                  | 6         | 0.19%   |
| Generalplus Technology               | 4         | 0.13%   |
| Silicon Integrated Systems [SiS]     | 3         | 0.09%   |
| Samson Technologies                  | 3         | 0.09%   |
| Hewlett-Packard                      | 3         | 0.09%   |
| XMOS                                 | 2         | 0.06%   |
| Valve Software                       | 2         | 0.06%   |
| Sennheiser Communications            | 2         | 0.06%   |
| Schiit Audio                         | 2         | 0.06%   |
| SAVITECH                             | 2         | 0.06%   |
| No brand                             | 2         | 0.06%   |
| Native Instruments                   | 2         | 0.06%   |
| Mackie Designs                       | 2         | 0.06%   |
| GYROCOM C&C                          | 2         | 0.06%   |
| Corsair                              | 2         | 0.06%   |
| Audio-Technica                       | 2         | 0.06%   |
| A4Tech                               | 2         | 0.06%   |
| ZOOM                                 | 1         | 0.03%   |
| Yamaha                               | 1         | 0.03%   |
| USB MICROPHONE                       | 1         | 0.03%   |
| Turtle Beach                         | 1         | 0.03%   |
| Trust                                | 1         | 0.03%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.03%   |
| Thermaltake                          | 1         | 0.03%   |
| Tdlasunnic                           | 1         | 0.03%   |
| Sony                                 | 1         | 0.03%   |
| SOMIC Industrial                     | 1         | 0.03%   |
| Samsung Electronics                  | 1         | 0.03%   |
| Quanta                               | 1         | 0.03%   |
| PreSonus Audio Electronics           | 1         | 0.03%   |
| Other World Computing                | 1         | 0.03%   |
| NAD Electronics                      | 1         | 0.03%   |
| NAD                                  | 1         | 0.03%   |
| Microsoft                            | 1         | 0.03%   |
| Micronas                             | 1         | 0.03%   |
| Medeli Electronics                   | 1         | 0.03%   |
| LG Electronics                       | 1         | 0.03%   |
| JOUNIVO JV601                        | 1         | 0.03%   |
| Jieli Technology                     | 1         | 0.03%   |
| Google                               | 1         | 0.03%   |
| Goldvish                             | 1         | 0.03%   |
| FiiO Electronics Technology          | 1         | 0.03%   |
| FiiO                                 | 1         | 0.03%   |
| DSEA A/S                             | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 394       | 10.14%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 375       | 9.65%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 186       | 4.79%   |
| Intel Cannon Lake PCH cAVS                                                                        | 177       | 4.56%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 173       | 4.45%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 143       | 3.68%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 127       | 3.27%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 111       | 2.86%   |
| Intel Broadwell-U Audio Controller                                                                | 105       | 2.7%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 101       | 2.6%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 100       | 2.57%   |
| Intel 8 Series HD Audio Controller                                                                | 100       | 2.57%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 97        | 2.5%    |
| Intel CM238 HD Audio Controller                                                                   | 93        | 2.39%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 84        | 2.16%   |
| Intel Comet Lake PCH cAVS                                                                         | 75        | 1.93%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 74        | 1.91%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 74        | 1.91%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 69        | 1.78%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 67        | 1.73%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 61        | 1.57%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 60        | 1.54%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 53        | 1.36%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 51        | 1.31%   |
| AMD FCH Azalia Controller                                                                         | 31        | 0.8%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 29        | 0.75%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 28        | 0.72%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 27        | 0.7%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 25        | 0.64%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 23        | 0.59%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 23        | 0.59%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 23        | 0.59%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 22        | 0.57%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 22        | 0.57%   |
| AMD Kabini HDMI/DP Audio                                                                          | 22        | 0.57%   |
| Realtek Semiconductor USB Audio                                                                   | 21        | 0.54%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 20        | 0.51%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 19        | 0.49%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 19        | 0.49%   |
| AMD High Definition Audio Controller                                                              | 19        | 0.49%   |
| Nvidia TU104 HD Audio Controller                                                                  | 17        | 0.44%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 17        | 0.44%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 16        | 0.41%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 14        | 0.36%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 14        | 0.36%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 14        | 0.36%   |
| Nvidia High Definition Audio Controller                                                           | 13        | 0.33%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 12        | 0.31%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 11        | 0.28%   |
| AMD Navi 10 HDMI Audio                                                                            | 11        | 0.28%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 11        | 0.28%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 10        | 0.26%   |
| Apple Audio Device                                                                                | 10        | 0.26%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 9         | 0.23%   |
| Nvidia Audio device                                                                               | 9         | 0.23%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                                         | 9         | 0.23%   |
| JMTek USB PnP Audio Device                                                                        | 9         | 0.23%   |
| C-Media Electronics USB Audio Device                                                              | 9         | 0.23%   |
| Texas Instruments PCM2912A Audio Codec                                                            | 8         | 0.21%   |
| AMD Wrestler HDMI Audio                                                                           | 8         | 0.21%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 636       | 29.75%  |
| SK hynix            | 477       | 22.31%  |
| Micron Technology   | 275       | 12.86%  |
| Kingston            | 214       | 10.01%  |
| Crucial             | 127       | 5.94%   |
| Unknown             | 79        | 3.7%    |
| Ramaxel Technology  | 62        | 2.9%    |
| A-DATA Technology   | 47        | 2.2%    |
| Corsair             | 39        | 1.82%   |
| Elpida              | 36        | 1.68%   |
| G.Skill             | 14        | 0.65%   |
| Patriot             | 12        | 0.56%   |
| Nanya Technology    | 12        | 0.56%   |
| Smart               | 11        | 0.51%   |
| Unknown (ABCD)      | 10        | 0.47%   |
| Goodram             | 9         | 0.42%   |
| Transcend           | 8         | 0.37%   |
| Team                | 7         | 0.33%   |
| Teikon              | 5         | 0.23%   |
| Smart Brazil        | 5         | 0.23%   |
| PNY                 | 5         | 0.23%   |
| Goldkey             | 5         | 0.23%   |
| AMD                 | 4         | 0.19%   |
| Apacer              | 3         | 0.14%   |
| 48spaces            | 3         | 0.14%   |
| Unknown             | 3         | 0.14%   |
| V-GeN               | 2         | 0.09%   |
| Silicon Power       | 2         | 0.09%   |
| Neo Forza           | 2         | 0.09%   |
| High Bridge         | 2         | 0.09%   |
| Avant               | 2         | 0.09%   |
| V-Color             | 1         | 0.05%   |
| Unknown (C509)      | 1         | 0.05%   |
| Unknown (0x0C26)    | 1         | 0.05%   |
| Unknown (07F7)      | 1         | 0.05%   |
| Timetec             | 1         | 0.05%   |
| Spectek             | 1         | 0.05%   |
| SHARETRONIC         | 1         | 0.05%   |
| Sesame              | 1         | 0.05%   |
| PKI/Kingston        | 1         | 0.05%   |
| MLLSE               | 1         | 0.05%   |
| Micron/Elpida       | 1         | 0.05%   |
| Lexar Co Limited    | 1         | 0.05%   |
| Lexar               | 1         | 0.05%   |
| Kingmax             | 1         | 0.05%   |
| GSkill              | 1         | 0.05%   |
| CFD                 | 1         | 0.05%   |
| ASint Technology    | 1         | 0.05%   |
| Apogee              | 1         | 0.05%   |
| Aeneon              | 1         | 0.05%   |
| 0161000080AD        | 1         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 48        | 2.12%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 43        | 1.9%    |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s            | 39        | 1.72%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 31        | 1.37%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 31        | 1.37%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 22        | 0.97%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 22        | 0.97%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 21        | 0.93%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 20        | 0.88%   |
| Samsung RAM M471A1K43DB1-CTD 8192MB SODIMM DDR4 2667MT/s            | 20        | 0.88%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 19        | 0.84%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 18        | 0.79%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 18        | 0.79%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 18        | 0.79%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 18        | 0.79%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 17        | 0.75%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 17        | 0.75%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 17        | 0.75%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 17        | 0.75%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 16        | 0.71%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 15        | 0.66%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 15        | 0.66%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 15        | 0.66%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 14        | 0.62%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 13        | 0.57%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 12        | 0.53%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 12        | 0.53%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 12        | 0.53%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s              | 12        | 0.53%   |
| Samsung RAM M471A2K43CB1-CRC 16384MB SODIMM DDR4 2667MT/s           | 12        | 0.53%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s              | 12        | 0.53%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s        | 11        | 0.49%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16384MB SODIMM DDR4 2667MT/s          | 11        | 0.49%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 11        | 0.49%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                | 11        | 0.49%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s                | 11        | 0.49%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s             | 10        | 0.44%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 10        | 0.44%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s             | 10        | 0.44%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s           | 10        | 0.44%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s                | 10        | 0.44%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 9         | 0.4%    |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 9         | 0.4%    |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s              | 9         | 0.4%    |
| Samsung RAM M471A5244BB0-CRC 4096MB SODIMM DDR4 2667MT/s            | 9         | 0.4%    |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s              | 9         | 0.4%    |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s    | 8         | 0.35%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 8         | 0.35%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 8         | 0.35%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 8         | 0.35%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s               | 8         | 0.35%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s               | 8         | 0.35%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s               | 8         | 0.35%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s       | 8         | 0.35%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s                | 8         | 0.35%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16384MB SODIMM DDR4 3200MT/s            | 8         | 0.35%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s               | 8         | 0.35%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s          | 8         | 0.35%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s              | 7         | 0.31%   |
| Samsung RAM M471A1K43BB1-CTD 8192MB SODIMM DDR4 2667MT/s            | 7         | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 1034      | 59.05%  |
| DDR3    | 505       | 28.84%  |
| LPDDR3  | 76        | 4.34%   |
| LPDDR4  | 74        | 4.23%   |
| DDR2    | 26        | 1.48%   |
| SDRAM   | 25        | 1.43%   |
| Unknown | 6         | 0.34%   |
| LPDDR5  | 3         | 0.17%   |
| DRAM    | 1         | 0.06%   |
| DDR     | 1         | 0.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1545      | 88.29%  |
| Row Of Chips | 174       | 9.94%   |
| Chip         | 22        | 1.26%   |
| Unknown      | 5         | 0.29%   |
| DIMM         | 4         | 0.23%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 819       | 42.92%  |
| 4096  | 536       | 28.09%  |
| 16384 | 311       | 16.3%   |
| 2048  | 158       | 8.28%   |
| 32768 | 58        | 3.04%   |
| 1024  | 26        | 1.36%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 530       | 27.52%  |
| 1600    | 371       | 19.26%  |
| 3200    | 325       | 16.87%  |
| 2400    | 198       | 10.28%  |
| 2133    | 125       | 6.49%   |
| 1334    | 73        | 3.79%   |
| 1333    | 44        | 2.28%   |
| 3266    | 43        | 2.23%   |
| 4267    | 37        | 1.92%   |
| 1867    | 35        | 1.82%   |
| 1067    | 22        | 1.14%   |
| 667     | 20        | 1.04%   |
| 4199    | 14        | 0.73%   |
| 8400    | 13        | 0.67%   |
| Unknown | 13        | 0.67%   |
| 1066    | 12        | 0.62%   |
| 4266    | 9         | 0.47%   |
| 2048    | 9         | 0.47%   |
| 975     | 7         | 0.36%   |
| 6400    | 4         | 0.21%   |
| 800     | 4         | 0.21%   |
| 4800    | 3         | 0.16%   |
| 2933    | 3         | 0.16%   |
| 1866    | 2         | 0.1%    |
| 533     | 2         | 0.1%    |
| 3733    | 1         | 0.05%   |
| 3000    | 1         | 0.05%   |
| 2666    | 1         | 0.05%   |
| 1776    | 1         | 0.05%   |
| 1639    | 1         | 0.05%   |
| 1200    | 1         | 0.05%   |
| 400     | 1         | 0.05%   |
| 200     | 1         | 0.05%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 8         | 50%     |
| Samsung Electronics | 2         | 12.5%   |
| Prolific Technology | 2         | 12.5%   |
| Seiko Epson         | 1         | 6.25%   |
| Dymo-CoStar         | 1         | 6.25%   |
| Canon               | 1         | 6.25%   |
| Brother Industries  | 1         | 6.25%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port      | 2         | 12.5%   |
| HP DeskJet 2130 series             | 2         | 12.5%   |
| Seiko Epson WF-2530 Series         | 1         | 6.25%   |
| Samsung SCX-3200 Series            | 1         | 6.25%   |
| Samsung M2020 Series               | 1         | 6.25%   |
| HP OfficeJet 5600 (USBHUB)         | 1         | 6.25%   |
| HP LaserJet 1320                   | 1         | 6.25%   |
| HP ENVY 5000 series                | 1         | 6.25%   |
| HP DeskJet 840c                    | 1         | 6.25%   |
| HP DeskJet 4100 series             | 1         | 6.25%   |
| HP DeskJet 2620 All-in-One Printer | 1         | 6.25%   |
| Dymo-CoStar LabelWriter 400        | 1         | 6.25%   |
| Canon PIXMA MG2500 Series          | 1         | 6.25%   |
| Brother HL-1110 series             | 1         | 6.25%   |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 542       | 24.2%   |
| IMC Networks                           | 274       | 12.23%  |
| Acer                                   | 226       | 10.09%  |
| Microdia                               | 214       | 9.55%   |
| Realtek Semiconductor                  | 178       | 7.95%   |
| Quanta                                 | 126       | 5.63%   |
| Sunplus Innovation Technology          | 120       | 5.36%   |
| Cheng Uei Precision Industry (Foxlink) | 82        | 3.66%   |
| Lite-On Technology                     | 68        | 3.04%   |
| Syntek                                 | 65        | 2.9%    |
| Apple                                  | 45        | 2.01%   |
| Suyin                                  | 42        | 1.88%   |
| Logitech                               | 39        | 1.74%   |
| Silicon Motion                         | 37        | 1.65%   |
| Alcor Micro                            | 26        | 1.16%   |
| Luxvisions Innotech Limited            | 21        | 0.94%   |
| Lenovo                                 | 18        | 0.8%    |
| Samsung Electronics                    | 13        | 0.58%   |
| Ricoh                                  | 10        | 0.45%   |
| ALi                                    | 9         | 0.4%    |
| Importek                               | 8         | 0.36%   |
| Primax Electronics                     | 7         | 0.31%   |
| Microsoft                              | 6         | 0.27%   |
| Z-Star Microelectronics                | 5         | 0.22%   |
| Sonix Technology                       | 5         | 0.22%   |
| Unknown                                | 4         | 0.18%   |
| OmniVision Technologies                | 3         | 0.13%   |
| MacroSilicon                           | 3         | 0.13%   |
| ARC International                      | 3         | 0.13%   |
| YGTek                                  | 2         | 0.09%   |
| Valve Software                         | 2         | 0.09%   |
| SunplusIT                              | 2         | 0.09%   |
| Intel                                  | 2         | 0.09%   |
| Holitech                               | 2         | 0.09%   |
| DigiTech                               | 2         | 0.09%   |
| USB3.0 HD Audio Capture                | 1         | 0.04%   |
| Trust                                  | 1         | 0.04%   |
| Tobii Technology AB                    | 1         | 0.04%   |
| Sunplus Technology                     | 1         | 0.04%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.04%   |
| Ruision                                | 1         | 0.04%   |
| Razer USA                              | 1         | 0.04%   |
| Pixart Imaging                         | 1         | 0.04%   |
| Oculus VR                              | 1         | 0.04%   |
| MSD                                    | 1         | 0.04%   |
| Linux Foundation                       | 1         | 0.04%   |
| LG Electronics                         | 1         | 0.04%   |
| KYE Systems (Mouse Systems)            | 1         | 0.04%   |
| Jieli Technology                       | 1         | 0.04%   |
| icSpring                               | 1         | 0.04%   |
| HTC (High Tech Computer)               | 1         | 0.04%   |
| Google                                 | 1         | 0.04%   |
| Goodong Industry                       | 1         | 0.04%   |
| Generalplus Technology                 | 1         | 0.04%   |
| GEMBIRD                                | 1         | 0.04%   |
| Foxconn / Hon Hai                      | 1         | 0.04%   |
| Etron Technology                       | 1         | 0.04%   |
| DJJHNA29IE70D3                         | 1         | 0.04%   |
| Creative Technology                    | 1         | 0.04%   |
| Canon                                  | 1         | 0.04%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 156       | 6.89%   |
| Microdia Integrated_Webcam_HD                                              | 116       | 5.12%   |
| IMC Networks Integrated Camera                                             | 94        | 4.15%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 74        | 3.27%   |
| Acer Integrated Camera                                                     | 73        | 3.22%   |
| Chicony HD Webcam                                                          | 66        | 2.92%   |
| Realtek Integrated_Webcam_HD                                               | 65        | 2.87%   |
| Sunplus Integrated_Webcam_HD                                               | 56        | 2.47%   |
| Lite-On Integrated Camera                                                  | 35        | 1.55%   |
| Quanta HD User Facing                                                      | 33        | 1.46%   |
| Syntek Integrated Camera                                                   | 32        | 1.41%   |
| Acer HD Webcam                                                             | 29        | 1.28%   |
| Acer SunplusIT Integrated Camera                                           | 28        | 1.24%   |
| Chicony USB2.0 Camera                                                      | 26        | 1.15%   |
| Chicony Integrated Camera (1280x720@30)                                    | 26        | 1.15%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 25        | 1.1%    |
| Microdia Integrated Webcam                                                 | 20        | 0.88%   |
| Chicony HP HD Camera                                                       | 20        | 0.88%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 19        | 0.84%   |
| Syntek Lenovo EasyCamera                                                   | 18        | 0.8%    |
| Realtek Integrated Webcam                                                  | 18        | 0.8%    |
| Acer Lenovo EasyCamera                                                     | 18        | 0.8%    |
| Sunplus HD WebCam                                                          | 17        | 0.75%   |
| IMC Networks ov9734_azurewave_camera                                       | 17        | 0.75%   |
| Chicony HP Wide Vision HD Camera                                           | 17        | 0.75%   |
| Chicony HD User Facing                                                     | 17        | 0.75%   |
| Chicony EasyCamera                                                         | 17        | 0.75%   |
| Lite-On HP HD Camera                                                       | 16        | 0.71%   |
| Chicony USB2.0 HD UVC WebCam                                               | 16        | 0.71%   |
| Acer BisonCam, NB Pro                                                      | 16        | 0.71%   |
| Quanta HP TrueVision HD Camera                                             | 15        | 0.66%   |
| Quanta HD Webcam                                                           | 15        | 0.66%   |
| Microdia Integrated Webcam HD                                              | 15        | 0.66%   |
| Chicony ThinkPad T490 Webcam                                               | 15        | 0.66%   |
| Realtek USB Camera                                                         | 14        | 0.62%   |
| Quanta VGA WebCam                                                          | 14        | 0.62%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 14        | 0.62%   |
| Samsung Galaxy A5 (MTP)                                                    | 13        | 0.57%   |
| IMC Networks VGA UVC WebCam                                                | 13        | 0.57%   |
| Chicony HP Truevision HD                                                   | 13        | 0.57%   |
| Quanta HP HD Camera                                                        | 12        | 0.53%   |
| Chicony USB 2.0 Camera                                                     | 12        | 0.53%   |
| Chicony Integrated IR Camera                                               | 12        | 0.53%   |
| Apple FaceTime HD Camera (Built-in)                                        | 12        | 0.53%   |
| Chicony Lenovo Integrated Camera (0.3MP)                                   | 11        | 0.49%   |
| Realtek USB2.0 HD UVC WebCam                                               | 10        | 0.44%   |
| Quanta HP Webcam                                                           | 10        | 0.44%   |
| Chicony HP TrueVision HD Camera                                            | 10        | 0.44%   |
| Acer ThinkPad Integrated Camera                                            | 10        | 0.44%   |
| Acer EasyCamera                                                            | 10        | 0.44%   |
| Silicon Motion Web Camera                                                  | 9         | 0.4%    |
| Realtek HD WebCam                                                          | 9         | 0.4%    |
| Logitech HD Pro Webcam C920                                                | 9         | 0.4%    |
| IMC Networks USB2.0 UVC HD Webcam                                          | 9         | 0.4%    |
| Chicony Lenovo EasyCamera                                                  | 9         | 0.4%    |
| Apple FaceTime HD Camera                                                   | 9         | 0.4%    |
| Suyin HP Truevision HD                                                     | 8         | 0.35%   |
| Realtek USB2.0 VGA UVC WebCam                                              | 8         | 0.35%   |
| Microdia Amcrest AWC2198 USB Webcam                                        | 8         | 0.35%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 8         | 0.35%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 185       | 35.31%  |
| Validity Sensors           | 151       | 28.82%  |
| Shenzhen Goodix Technology | 85        | 16.22%  |
| Elan Microelectronics      | 30        | 5.73%   |
| Upek                       | 23        | 4.39%   |
| LighTuning Technology      | 23        | 4.39%   |
| AuthenTec                  | 19        | 3.63%   |
| STMicroelectronics         | 6         | 1.15%   |
| Samsung Electronics        | 2         | 0.38%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 89        | 16.98%  |
| Shenzhen Goodix  Fingerprint Device                                        | 42        | 8.02%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 36        | 6.87%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 30        | 5.73%   |
| Elan ELAN:Fingerprint                                                      | 24        | 4.58%   |
| Shenzhen Goodix Fingerprint Reader                                         | 22        | 4.2%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 21        | 4.01%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 21        | 4.01%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 21        | 4.01%   |
| Shenzhen Goodix FingerPrint                                                | 21        | 4.01%   |
| Unknown                                                                    | 17        | 3.24%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 15        | 2.86%   |
| Validity Sensors Synaptics WBDI                                            | 15        | 2.86%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 15        | 2.86%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 13        | 2.48%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 12        | 2.29%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 12        | 2.29%   |
| Validity Sensors VFS491                                                    | 11        | 2.1%    |
| AuthenTec AES2810                                                          | 10        | 1.91%   |
| Validity Sensors Fingerprint scanner                                       | 9         | 1.72%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 9         | 1.72%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 7         | 1.34%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 1.15%   |
| Elan ELAN:ARM-M4                                                           | 6         | 1.15%   |
| Synaptics  WBDI                                                            | 5         | 0.95%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 3         | 0.57%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 0.57%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 0.57%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 0.57%   |
| Synaptics WBDI Device                                                      | 3         | 0.57%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 0.57%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.38%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.38%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.38%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.38%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 0.38%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 0.38%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.19%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 0.19%   |
| Samsung Fingerprint Device                                                 | 1         | 0.19%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.19%   |
| AuthenTec AES1600                                                          | 1         | 0.19%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 93        | 42.47%  |
| Broadcom                  | 89        | 40.64%  |
| Upek                      | 15        | 6.85%   |
| Lenovo                    | 10        | 4.57%   |
| SCM Microsystems          | 3         | 1.37%   |
| O2 Micro                  | 3         | 1.37%   |
| Yubico.com                | 2         | 0.91%   |
| Hewlett-Packard           | 1         | 0.46%   |
| Gemalto (was Gemplus)     | 1         | 0.46%   |
| Clay Logic                | 1         | 0.46%   |
| Aladdin Knowledge Systems | 1         | 0.46%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 93        | 42.47%  |
| Broadcom 5880                                                                | 25        | 11.42%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 23        | 10.5%   |
| Broadcom 58200                                                               | 20        | 9.13%   |
| Broadcom BCM5880 Secure Applications Processor                               | 19        | 8.68%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 15        | 6.85%   |
| Lenovo Integrated Smart Card Reader                                          | 10        | 4.57%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 0.91%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 0.91%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 0.91%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.91%   |
| SCM Microsystems SCR3500 C Contact Reader                                    | 1         | 0.46%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.46%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.46%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.46%   |
| Clay Logic CanoKey                                                           | 1         | 0.46%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.46%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1500      | 60.39%  |
| 1     | 755       | 30.39%  |
| 2     | 178       | 7.17%   |
| 3     | 45        | 1.81%   |
| 4     | 5         | 0.2%    |
| 7     | 1         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 517       | 41.59%  |
| Graphics card            | 214       | 17.22%  |
| Chipcard                 | 200       | 16.09%  |
| Net/wireless             | 76        | 6.11%   |
| Multimedia controller    | 70        | 5.63%   |
| Camera                   | 68        | 5.47%   |
| Bluetooth                | 23        | 1.85%   |
| Net/ethernet             | 15        | 1.21%   |
| Storage                  | 14        | 1.13%   |
| Sound                    | 13        | 1.05%   |
| Communication controller | 11        | 0.88%   |
| Card reader              | 8         | 0.64%   |
| Network                  | 5         | 0.4%    |
| Wireless                 | 2         | 0.16%   |
| Unassigned class         | 1         | 0.08%   |
| Storage/nvme             | 1         | 0.08%   |
| Storage/ata              | 1         | 0.08%   |
| Modem                    | 1         | 0.08%   |
| Flash memory             | 1         | 0.08%   |
| Firewire controller      | 1         | 0.08%   |
| Dvb card                 | 1         | 0.08%   |

