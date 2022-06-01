Linux in Netherlands - Tested Hardware & Statistics
---------------------------------------------------

A project to collect tested hardware configurations for Linux in Netherlands.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Netherlands/Desktop/README.md) and [notebooks](/Location/Netherlands/Notebook/README.md).

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

Total: 4053

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | P8B75-M LE                  | Desktop     | [8ee7ddfd56](https://linux-hardware.org/?probe=8ee7ddfd56) | Jun 01, 2022 |
| HP            | EliteBook 2560p             | Notebook    | [af6a91d3c7](https://linux-hardware.org/?probe=af6a91d3c7) | Jun 01, 2022 |
| Dell          | Inspiron 14 7420 2-in-1     | Notebook    | [131a117ca2](https://linux-hardware.org/?probe=131a117ca2) | May 31, 2022 |
| Acer          | Aspire XC-886 V:2.0         | Desktop     | [2fe8cdaf93](https://linux-hardware.org/?probe=2fe8cdaf93) | May 31, 2022 |
| Dell          | Inspiron 5491 2n1           | Convertible | [652f774655](https://linux-hardware.org/?probe=652f774655) | May 30, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [0020802901](https://linux-hardware.org/?probe=0020802901) | May 30, 2022 |
| HP            | 829A                        | Mini pc     | [534d46fcab](https://linux-hardware.org/?probe=534d46fcab) | May 30, 2022 |
| HONOR         | BOHK-WAX9X                  | Notebook    | [7941caaa08](https://linux-hardware.org/?probe=7941caaa08) | May 29, 2022 |
| ASUSTek       | F1A55-M LX                  | Desktop     | [eeeb2c5bfa](https://linux-hardware.org/?probe=eeeb2c5bfa) | May 29, 2022 |
| ASUSTek       | P7P55D DELUXE               | Desktop     | [ba2d55d308](https://linux-hardware.org/?probe=ba2d55d308) | May 29, 2022 |
| Medion        | X6816                       | Notebook    | [6d7996894c](https://linux-hardware.org/?probe=6d7996894c) | May 28, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [4111506bc3](https://linux-hardware.org/?probe=4111506bc3) | May 28, 2022 |
| BESSTAR Te... | HM80                        | Desktop     | [f507d65c2e](https://linux-hardware.org/?probe=f507d65c2e) | May 28, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [1bb179225c](https://linux-hardware.org/?probe=1bb179225c) | May 28, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [61cbe48681](https://linux-hardware.org/?probe=61cbe48681) | May 28, 2022 |
| Unknown       | Unknown                     | Notebook    | [7ca69b6206](https://linux-hardware.org/?probe=7ca69b6206) | May 28, 2022 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [4813c4e0b4](https://linux-hardware.org/?probe=4813c4e0b4) | May 28, 2022 |
| Medion        | P6812                       | Notebook    | [b5416af5fd](https://linux-hardware.org/?probe=b5416af5fd) | May 28, 2022 |
| Medion        | X6816                       | Notebook    | [69e3c742fe](https://linux-hardware.org/?probe=69e3c742fe) | May 27, 2022 |
| Alienware     | 17 R4                       | Notebook    | [0a7c1705c9](https://linux-hardware.org/?probe=0a7c1705c9) | May 27, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [93d1ebbb72](https://linux-hardware.org/?probe=93d1ebbb72) | May 27, 2022 |
| ASRock        | IMB-185                     | Desktop     | [f7b3b565a0](https://linux-hardware.org/?probe=f7b3b565a0) | May 27, 2022 |
| ASUSTek       | F1A55-M LX                  | Desktop     | [ec77008f63](https://linux-hardware.org/?probe=ec77008f63) | May 26, 2022 |
| Acer          | Aspire 7750G                | Notebook    | [d059ef8864](https://linux-hardware.org/?probe=d059ef8864) | May 26, 2022 |
| ASUSTek       | P5KPL-SE                    | Desktop     | [c4b27d79ef](https://linux-hardware.org/?probe=c4b27d79ef) | May 26, 2022 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [af3a0a674a](https://linux-hardware.org/?probe=af3a0a674a) | May 26, 2022 |
| MSI           | GP62MVR 7RF                 | Notebook    | [2690f91679](https://linux-hardware.org/?probe=2690f91679) | May 25, 2022 |
| Valve         | Jupiter                     | Notebook    | [dee0bbedd1](https://linux-hardware.org/?probe=dee0bbedd1) | May 25, 2022 |
| Acer          | TravelMate 8372             | Notebook    | [fda4340056](https://linux-hardware.org/?probe=fda4340056) | May 25, 2022 |
| Lenovo        | ThinkPad W520 428223G       | Notebook    | [5672a27a7e](https://linux-hardware.org/?probe=5672a27a7e) | May 24, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [66b453536a](https://linux-hardware.org/?probe=66b453536a) | May 24, 2022 |
| HP            | 8158 A01                    | Mini pc     | [0d32a2b2e3](https://linux-hardware.org/?probe=0d32a2b2e3) | May 24, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [5c9c033d2f](https://linux-hardware.org/?probe=5c9c033d2f) | May 24, 2022 |
| MSI           | H97M-G43                    | Desktop     | [4c1e9752b6](https://linux-hardware.org/?probe=4c1e9752b6) | May 23, 2022 |
| Gigabyte      | GB-BRR7H-4700               | Desktop     | [4e378acf87](https://linux-hardware.org/?probe=4e378acf87) | May 23, 2022 |
| Gigabyte      | GB-BRR7H-4700               | Desktop     | [9ba025f6fd](https://linux-hardware.org/?probe=9ba025f6fd) | May 23, 2022 |
| Notebook      | NL5xRU                      | Notebook    | [fa1c36e965](https://linux-hardware.org/?probe=fa1c36e965) | May 23, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [80ccb1775d](https://linux-hardware.org/?probe=80ccb1775d) | May 23, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [b58e8317a1](https://linux-hardware.org/?probe=b58e8317a1) | May 23, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [a76a3417d7](https://linux-hardware.org/?probe=a76a3417d7) | May 23, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [952fd6afe9](https://linux-hardware.org/?probe=952fd6afe9) | May 22, 2022 |
| Lenovo        | ThinkPad Edge 03193TG       | Notebook    | [1ef9886070](https://linux-hardware.org/?probe=1ef9886070) | May 22, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [7a2b254899](https://linux-hardware.org/?probe=7a2b254899) | May 22, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [5ecfcfab7b](https://linux-hardware.org/?probe=5ecfcfab7b) | May 22, 2022 |
| Acer          | Aspire E5-573               | Notebook    | [e31114a6b2](https://linux-hardware.org/?probe=e31114a6b2) | May 21, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [654070d432](https://linux-hardware.org/?probe=654070d432) | May 21, 2022 |
| Gigabyte      | GB-BRR7H-4700               | Desktop     | [1f9eed3fb4](https://linux-hardware.org/?probe=1f9eed3fb4) | May 20, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [5c133a0848](https://linux-hardware.org/?probe=5c133a0848) | May 20, 2022 |
| Lenovo        | Legion Y540-17IRH-PG0 81... | Notebook    | [086fceea4f](https://linux-hardware.org/?probe=086fceea4f) | May 19, 2022 |
| ASUSTek       | A8R-MX                      | Desktop     | [50420da989](https://linux-hardware.org/?probe=50420da989) | May 19, 2022 |
| Acer          | Aspire G7750                | Desktop     | [28f3018ecc](https://linux-hardware.org/?probe=28f3018ecc) | May 18, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [d1575ec23a](https://linux-hardware.org/?probe=d1575ec23a) | May 17, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [124aa63eaf](https://linux-hardware.org/?probe=124aa63eaf) | May 17, 2022 |
| Lenovo        | Legion 5 15ACH6A 82NW       | Notebook    | [e0697c999e](https://linux-hardware.org/?probe=e0697c999e) | May 17, 2022 |
| ASUSTek       | UL30A                       | Notebook    | [c121dd37ba](https://linux-hardware.org/?probe=c121dd37ba) | May 16, 2022 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [a32c82c654](https://linux-hardware.org/?probe=a32c82c654) | May 16, 2022 |
| Packard Be... | EasyNote LE69KB             | Notebook    | [71c0982b04](https://linux-hardware.org/?probe=71c0982b04) | May 15, 2022 |
| HP            | 0A54h                       | Desktop     | [c785131d66](https://linux-hardware.org/?probe=c785131d66) | May 15, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [e8443680c9](https://linux-hardware.org/?probe=e8443680c9) | May 15, 2022 |
| MSI           | H87-G41 PC Mate             | Desktop     | [b8c903e438](https://linux-hardware.org/?probe=b8c903e438) | May 14, 2022 |
| MSI           | H87-G41 PC Mate             | Desktop     | [ea3683a2da](https://linux-hardware.org/?probe=ea3683a2da) | May 14, 2022 |
| Dell          | Precision 3551              | Notebook    | [8685d59ac6](https://linux-hardware.org/?probe=8685d59ac6) | May 14, 2022 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | Notebook    | [4fe9787a82](https://linux-hardware.org/?probe=4fe9787a82) | May 14, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [5dea5cd6ff](https://linux-hardware.org/?probe=5dea5cd6ff) | May 14, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [eab6a0ee2a](https://linux-hardware.org/?probe=eab6a0ee2a) | May 14, 2022 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [8af018aabb](https://linux-hardware.org/?probe=8af018aabb) | May 13, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [49c8fb1741](https://linux-hardware.org/?probe=49c8fb1741) | May 13, 2022 |
| Dell          | G3 3779                     | Notebook    | [75a0c428dd](https://linux-hardware.org/?probe=75a0c428dd) | May 13, 2022 |
| HP            | ZBook Studio G5             | Notebook    | [32358d7f08](https://linux-hardware.org/?probe=32358d7f08) | May 13, 2022 |
| HONOR         | BOHK-WAX9X                  | Notebook    | [e6c4aaa3d8](https://linux-hardware.org/?probe=e6c4aaa3d8) | May 12, 2022 |
| Dell          | Inspiron 1525               | Notebook    | [a9e9868b12](https://linux-hardware.org/?probe=a9e9868b12) | May 12, 2022 |
| HP            | ZBook 15 G6                 | Notebook    | [a4ce7187a6](https://linux-hardware.org/?probe=a4ce7187a6) | May 12, 2022 |
| Acer          | Swift SF514-55T             | Notebook    | [02cae91736](https://linux-hardware.org/?probe=02cae91736) | May 12, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [cbced4dcff](https://linux-hardware.org/?probe=cbced4dcff) | May 11, 2022 |
| Dell          | 0WMJ54 A00                  | Desktop     | [393406b0e8](https://linux-hardware.org/?probe=393406b0e8) | May 11, 2022 |
| Dell          | Latitude 3120               | Convertible | [fdb8aed8ce](https://linux-hardware.org/?probe=fdb8aed8ce) | May 11, 2022 |
| Dell          | Latitude 3120               | Convertible | [216d204154](https://linux-hardware.org/?probe=216d204154) | May 10, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [a63f7cf593](https://linux-hardware.org/?probe=a63f7cf593) | May 10, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [7ea6059ac1](https://linux-hardware.org/?probe=7ea6059ac1) | May 10, 2022 |
| MSI           | Z170A GAMING M5             | Desktop     | [766ec913a6](https://linux-hardware.org/?probe=766ec913a6) | May 09, 2022 |
| Dell          | 0GXM1W A02                  | Desktop     | [1606b44e03](https://linux-hardware.org/?probe=1606b44e03) | May 09, 2022 |
| Dell          | 0GXM1W A02                  | Desktop     | [bf028580b1](https://linux-hardware.org/?probe=bf028580b1) | May 09, 2022 |
| HP            | ProBook x360 11 G1 EE       | Notebook    | [cfe7a62390](https://linux-hardware.org/?probe=cfe7a62390) | May 08, 2022 |
| Panasonic     | CF-AX2LDCZMF                | Notebook    | [0eb2c8ff07](https://linux-hardware.org/?probe=0eb2c8ff07) | May 08, 2022 |
| Supermicro    | H8QG6                       | Server      | [d341c929e0](https://linux-hardware.org/?probe=d341c929e0) | May 08, 2022 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [8a10210f97](https://linux-hardware.org/?probe=8a10210f97) | May 08, 2022 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [2cd65296c2](https://linux-hardware.org/?probe=2cd65296c2) | May 08, 2022 |
| MSI           | GS63 7RD                    | Notebook    | [eff12e3973](https://linux-hardware.org/?probe=eff12e3973) | May 08, 2022 |
| HP            | 0A54h                       | Desktop     | [ccc66dd2d8](https://linux-hardware.org/?probe=ccc66dd2d8) | May 07, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [8d9c902ae4](https://linux-hardware.org/?probe=8d9c902ae4) | May 07, 2022 |
| Dell          | Latitude 3120               | Notebook    | [0da044ae6c](https://linux-hardware.org/?probe=0da044ae6c) | May 06, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [ef836a5eca](https://linux-hardware.org/?probe=ef836a5eca) | May 06, 2022 |
| ASRock        | B85M DASH/OL R2.0           | Desktop     | [61c86467ba](https://linux-hardware.org/?probe=61c86467ba) | May 06, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [0021b7ff7f](https://linux-hardware.org/?probe=0021b7ff7f) | May 05, 2022 |
| ASUSTek       | UX430UAR                    | Notebook    | [6d471de246](https://linux-hardware.org/?probe=6d471de246) | May 05, 2022 |
| ASUSTek       | UX430UAR                    | Notebook    | [4aea04443a](https://linux-hardware.org/?probe=4aea04443a) | May 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [8919eebaa3](https://linux-hardware.org/?probe=8919eebaa3) | May 05, 2022 |
| HP            | 1906                        | Desktop     | [6f7f0536a9](https://linux-hardware.org/?probe=6f7f0536a9) | May 05, 2022 |
| HP            | ProBook 6560b               | Notebook    | [10ed31948a](https://linux-hardware.org/?probe=10ed31948a) | May 04, 2022 |
| Dell          | Latitude 3520               | Notebook    | [586dc3475e](https://linux-hardware.org/?probe=586dc3475e) | May 04, 2022 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [c2ab1a3ec2](https://linux-hardware.org/?probe=c2ab1a3ec2) | May 04, 2022 |
| Acer          | Aspire XC100A               | Desktop     | [dbad5c417d](https://linux-hardware.org/?probe=dbad5c417d) | May 04, 2022 |
| Gigabyte      | EP45-DS3P                   | Desktop     | [871c09cebe](https://linux-hardware.org/?probe=871c09cebe) | May 03, 2022 |
| HP            | 1906                        | Desktop     | [60ce09d82e](https://linux-hardware.org/?probe=60ce09d82e) | May 03, 2022 |
| Acer          | Aspire X3995                | Desktop     | [7db1de12e9](https://linux-hardware.org/?probe=7db1de12e9) | May 03, 2022 |
| Dell          | Latitude 3120               | Convertible | [a7375cad0b](https://linux-hardware.org/?probe=a7375cad0b) | May 03, 2022 |
| Lenovo        | ThinkPad X240 20AMS1S800    | Notebook    | [a00b8586b6](https://linux-hardware.org/?probe=a00b8586b6) | May 03, 2022 |
| Intel         | NUC10i7FNB M38062-307       | Mini pc     | [f64b812cc5](https://linux-hardware.org/?probe=f64b812cc5) | May 02, 2022 |
| Dell          | 0M017G A00                  | Desktop     | [93884340db](https://linux-hardware.org/?probe=93884340db) | May 02, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [b5bb3e821e](https://linux-hardware.org/?probe=b5bb3e821e) | May 02, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [2cf6d0c3f9](https://linux-hardware.org/?probe=2cf6d0c3f9) | May 02, 2022 |
| Dell          | Latitude 3310               | Notebook    | [2b74207996](https://linux-hardware.org/?probe=2b74207996) | May 02, 2022 |
| Dell          | Latitude 3120               | Convertible | [ce61c0c036](https://linux-hardware.org/?probe=ce61c0c036) | May 02, 2022 |
| Dell          | Latitude E6510              | Notebook    | [916f405c55](https://linux-hardware.org/?probe=916f405c55) | May 02, 2022 |
| Lenovo        | ThinkPad X201 3680AC2       | Notebook    | [5c4515d51e](https://linux-hardware.org/?probe=5c4515d51e) | May 01, 2022 |
| Notebook      | PB50_70RF,RD,RC             | Notebook    | [43afa2936d](https://linux-hardware.org/?probe=43afa2936d) | May 01, 2022 |
| Gigabyte      | P55A-UD3                    | Desktop     | [b212517217](https://linux-hardware.org/?probe=b212517217) | May 01, 2022 |
| Acer          | Aspire E1-532               | Notebook    | [38d01733a6](https://linux-hardware.org/?probe=38d01733a6) | May 01, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [79a3d8d3f6](https://linux-hardware.org/?probe=79a3d8d3f6) | May 01, 2022 |
| HP            | 18E7                        | Desktop     | [90a161bd80](https://linux-hardware.org/?probe=90a161bd80) | Apr 30, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [7cd33daa8a](https://linux-hardware.org/?probe=7cd33daa8a) | Apr 29, 2022 |
| Lenovo        | Legion 7 16ACHg6 82N6       | Notebook    | [bad5b7036e](https://linux-hardware.org/?probe=bad5b7036e) | Apr 29, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [e6f47edf47](https://linux-hardware.org/?probe=e6f47edf47) | Apr 29, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [e2f7ad0f81](https://linux-hardware.org/?probe=e2f7ad0f81) | Apr 29, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [ab83eedd1f](https://linux-hardware.org/?probe=ab83eedd1f) | Apr 28, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [f45e5abc4a](https://linux-hardware.org/?probe=f45e5abc4a) | Apr 28, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [6f3ea2d512](https://linux-hardware.org/?probe=6f3ea2d512) | Apr 28, 2022 |
| Dell          | Latitude 3120               | Convertible | [952eee1425](https://linux-hardware.org/?probe=952eee1425) | Apr 28, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [44e25caaa1](https://linux-hardware.org/?probe=44e25caaa1) | Apr 28, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [e962d2016e](https://linux-hardware.org/?probe=e962d2016e) | Apr 28, 2022 |
| Packard Be... | EasyNote_MX37-U-057NL       | Notebook    | [41760b3852](https://linux-hardware.org/?probe=41760b3852) | Apr 27, 2022 |
| Unknown       | Unknown                     | Desktop     | [82ad7e86b5](https://linux-hardware.org/?probe=82ad7e86b5) | Apr 27, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [f3eb691337](https://linux-hardware.org/?probe=f3eb691337) | Apr 27, 2022 |
| ASUSTek       | Hematite                    | Desktop     | [a6eec927f0](https://linux-hardware.org/?probe=a6eec927f0) | Apr 26, 2022 |
| HP            | Compaq Presario CQ70        | Notebook    | [ebfb06702f](https://linux-hardware.org/?probe=ebfb06702f) | Apr 25, 2022 |
| Lenovo        | Legion 7 16ACHg6 82N6       | Notebook    | [a65d23d316](https://linux-hardware.org/?probe=a65d23d316) | Apr 25, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [319157372c](https://linux-hardware.org/?probe=319157372c) | Apr 25, 2022 |
| Dell          | Latitude 3120               | Convertible | [57a9cd74db](https://linux-hardware.org/?probe=57a9cd74db) | Apr 25, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [190d52b2d6](https://linux-hardware.org/?probe=190d52b2d6) | Apr 25, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [803959fe3c](https://linux-hardware.org/?probe=803959fe3c) | Apr 24, 2022 |
| Dell          | Latitude 3380               | Notebook    | [2aa3eacaee](https://linux-hardware.org/?probe=2aa3eacaee) | Apr 24, 2022 |
| Lenovo        | ThinkPad X390 Yoga 20NN0... | Convertible | [3c1ff82bb0](https://linux-hardware.org/?probe=3c1ff82bb0) | Apr 24, 2022 |
| HP            | 3646h                       | Desktop     | [131d2ef893](https://linux-hardware.org/?probe=131d2ef893) | Apr 23, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [30209dbcd1](https://linux-hardware.org/?probe=30209dbcd1) | Apr 23, 2022 |
| Dell          | Latitude 5580               | Notebook    | [cbd7aaec4a](https://linux-hardware.org/?probe=cbd7aaec4a) | Apr 23, 2022 |
| HP            | 3646h                       | Desktop     | [e232464dd6](https://linux-hardware.org/?probe=e232464dd6) | Apr 22, 2022 |
| ASRock        | AB350M Pro4                 | Desktop     | [544c5dbbf7](https://linux-hardware.org/?probe=544c5dbbf7) | Apr 22, 2022 |
| Fujitsu       | CELSIUS H720                | Notebook    | [4c3233cd10](https://linux-hardware.org/?probe=4c3233cd10) | Apr 22, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6be9414efd](https://linux-hardware.org/?probe=6be9414efd) | Apr 22, 2022 |
| Dell          | Precision 3560              | Notebook    | [cc7a9c5fe2](https://linux-hardware.org/?probe=cc7a9c5fe2) | Apr 22, 2022 |
| Dell          | Latitude 3310               | Notebook    | [3130a4d7c3](https://linux-hardware.org/?probe=3130a4d7c3) | Apr 21, 2022 |
| Dell          | XPS 13 9333                 | Notebook    | [e3fcba68df](https://linux-hardware.org/?probe=e3fcba68df) | Apr 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [f2e59fcb97](https://linux-hardware.org/?probe=f2e59fcb97) | Apr 20, 2022 |
| Toshiba       | dynabook Satellite B552/... | Notebook    | [60e6d780aa](https://linux-hardware.org/?probe=60e6d780aa) | Apr 19, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [51a3d5d920](https://linux-hardware.org/?probe=51a3d5d920) | Apr 19, 2022 |
| Lenovo        | IdeaPad S510p 20298         | Notebook    | [80943ca395](https://linux-hardware.org/?probe=80943ca395) | Apr 18, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [9e1d98199a](https://linux-hardware.org/?probe=9e1d98199a) | Apr 18, 2022 |
| Packard Be... | EasyNote LE69KB             | Notebook    | [0afcb896ee](https://linux-hardware.org/?probe=0afcb896ee) | Apr 18, 2022 |
| Unknown       | Unknown                     | Desktop     | [f5deab7689](https://linux-hardware.org/?probe=f5deab7689) | Apr 17, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [647f782e9f](https://linux-hardware.org/?probe=647f782e9f) | Apr 17, 2022 |
| Lenovo        | ThinkPad X230 2325YGM       | Notebook    | [3606442649](https://linux-hardware.org/?probe=3606442649) | Apr 16, 2022 |
| Dell          | Latitude E6320              | Notebook    | [84523d9bd9](https://linux-hardware.org/?probe=84523d9bd9) | Apr 16, 2022 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [923a82e975](https://linux-hardware.org/?probe=923a82e975) | Apr 16, 2022 |
| MSI           | H110M PRO-VD                | Desktop     | [2fc240d0aa](https://linux-hardware.org/?probe=2fc240d0aa) | Apr 16, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [9529ed78e9](https://linux-hardware.org/?probe=9529ed78e9) | Apr 16, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [1ef9e4e85d](https://linux-hardware.org/?probe=1ef9e4e85d) | Apr 16, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [abee14fa00](https://linux-hardware.org/?probe=abee14fa00) | Apr 16, 2022 |
| Acer          | ConceptD CC314-72           | Convertible | [07f3c16543](https://linux-hardware.org/?probe=07f3c16543) | Apr 16, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | Notebook    | [9f099000d4](https://linux-hardware.org/?probe=9f099000d4) | Apr 16, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [4645168704](https://linux-hardware.org/?probe=4645168704) | Apr 15, 2022 |
| MSI           | CX700                       | Notebook    | [b7715b0ff7](https://linux-hardware.org/?probe=b7715b0ff7) | Apr 15, 2022 |
| Dell          | 0TWFTR A01                  | All in one  | [77c3745dab](https://linux-hardware.org/?probe=77c3745dab) | Apr 15, 2022 |
| Notebook      | NH55RGQ                     | Notebook    | [a5b036d6a3](https://linux-hardware.org/?probe=a5b036d6a3) | Apr 15, 2022 |
| ASUSTek       | GX501VIK                    | Notebook    | [076208c6fd](https://linux-hardware.org/?probe=076208c6fd) | Apr 15, 2022 |
| ASUSTek       | GX501VIK                    | Notebook    | [15c4c7877b](https://linux-hardware.org/?probe=15c4c7877b) | Apr 15, 2022 |
| Dell          | XPS 13 9333                 | Notebook    | [0d1712dd76](https://linux-hardware.org/?probe=0d1712dd76) | Apr 14, 2022 |
| HP            | ProBook 650 G5              | Notebook    | [db89b961c4](https://linux-hardware.org/?probe=db89b961c4) | Apr 14, 2022 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [afe37cb756](https://linux-hardware.org/?probe=afe37cb756) | Apr 14, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [e1b00199f8](https://linux-hardware.org/?probe=e1b00199f8) | Apr 14, 2022 |
| Notebook      | P7xxTM1                     | Notebook    | [b502ccf767](https://linux-hardware.org/?probe=b502ccf767) | Apr 14, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [0175e41474](https://linux-hardware.org/?probe=0175e41474) | Apr 14, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [76bb4d06e3](https://linux-hardware.org/?probe=76bb4d06e3) | Apr 13, 2022 |
| MSI           | Z270 SLI PLUS               | Desktop     | [fa00f6ccd6](https://linux-hardware.org/?probe=fa00f6ccd6) | Apr 13, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [b5375b9ffb](https://linux-hardware.org/?probe=b5375b9ffb) | Apr 13, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [20f315a2e7](https://linux-hardware.org/?probe=20f315a2e7) | Apr 13, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | Notebook    | [6dc0087ab4](https://linux-hardware.org/?probe=6dc0087ab4) | Apr 13, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [90505ddcfa](https://linux-hardware.org/?probe=90505ddcfa) | Apr 13, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [5923be4543](https://linux-hardware.org/?probe=5923be4543) | Apr 13, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [1f7a434559](https://linux-hardware.org/?probe=1f7a434559) | Apr 13, 2022 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | Notebook    | [5584985b1e](https://linux-hardware.org/?probe=5584985b1e) | Apr 13, 2022 |
| Google        | Kip                         | Notebook    | [4641a94428](https://linux-hardware.org/?probe=4641a94428) | Apr 13, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [ac864fd90c](https://linux-hardware.org/?probe=ac864fd90c) | Apr 13, 2022 |
| ASUSTek       | H87-PLUS                    | Desktop     | [8555858306](https://linux-hardware.org/?probe=8555858306) | Apr 13, 2022 |
| Dell          | 0JP3NX A00                  | Desktop     | [c76114b4b3](https://linux-hardware.org/?probe=c76114b4b3) | Apr 13, 2022 |
| TongFang      | GM5TG8W                     | Notebook    | [a37f30bc86](https://linux-hardware.org/?probe=a37f30bc86) | Apr 12, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [1e2fd3e919](https://linux-hardware.org/?probe=1e2fd3e919) | Apr 12, 2022 |
| Lenovo        | Y310                        | Notebook    | [09b47046f3](https://linux-hardware.org/?probe=09b47046f3) | Apr 11, 2022 |
| Clevo         | P770ZM                      | Notebook    | [0bc9b7a8b9](https://linux-hardware.org/?probe=0bc9b7a8b9) | Apr 11, 2022 |
| Lenovo        | 3135 SDK0J40697 WIN 3305... | Mini pc     | [214517d875](https://linux-hardware.org/?probe=214517d875) | Apr 10, 2022 |
| Notebook      | NS50_70MU                   | Notebook    | [cf76bb9e39](https://linux-hardware.org/?probe=cf76bb9e39) | Apr 10, 2022 |
| Gigabyte      | P55A-UD3                    | Desktop     | [9c6781cf90](https://linux-hardware.org/?probe=9c6781cf90) | Apr 10, 2022 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [4c37e32ae6](https://linux-hardware.org/?probe=4c37e32ae6) | Apr 10, 2022 |
| TongFang      | GM5TG8W                     | Notebook    | [b4004b859e](https://linux-hardware.org/?probe=b4004b859e) | Apr 10, 2022 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [88fba1bae6](https://linux-hardware.org/?probe=88fba1bae6) | Apr 09, 2022 |
| Timi          | A35                         | Notebook    | [d7e8ca818b](https://linux-hardware.org/?probe=d7e8ca818b) | Apr 09, 2022 |
| Microsoft     | Surface Pro                 | Tablet      | [487adfbcb9](https://linux-hardware.org/?probe=487adfbcb9) | Apr 09, 2022 |
| Microsoft     | Surface Book                | Tablet      | [bb26ae58f4](https://linux-hardware.org/?probe=bb26ae58f4) | Apr 09, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [cd14172a62](https://linux-hardware.org/?probe=cd14172a62) | Apr 09, 2022 |
| Acer          | EG43M                       | Desktop     | [cf64046a46](https://linux-hardware.org/?probe=cf64046a46) | Apr 08, 2022 |
| HP            | Pavilion dv7                | Notebook    | [7dbbd223a6](https://linux-hardware.org/?probe=7dbbd223a6) | Apr 08, 2022 |
| Dell          | 0TP406                      | Desktop     | [13fa76c1c5](https://linux-hardware.org/?probe=13fa76c1c5) | Apr 07, 2022 |
| ASRock        | H310CM-ITX/ac               | Desktop     | [60948d1473](https://linux-hardware.org/?probe=60948d1473) | Apr 07, 2022 |
| Dell          | Latitude E6530              | Notebook    | [46bbc49e43](https://linux-hardware.org/?probe=46bbc49e43) | Apr 07, 2022 |
| ASUSTek       | N750JV                      | Notebook    | [9b4200359d](https://linux-hardware.org/?probe=9b4200359d) | Apr 07, 2022 |
| Biostar       | A55ML2                      | Desktop     | [11d2b22b90](https://linux-hardware.org/?probe=11d2b22b90) | Apr 06, 2022 |
| BESSTAR Te... | HM90                        | Desktop     | [202fc7c2a2](https://linux-hardware.org/?probe=202fc7c2a2) | Apr 06, 2022 |
| Dell          | Latitude E7250              | Notebook    | [a39d4e32a0](https://linux-hardware.org/?probe=a39d4e32a0) | Apr 06, 2022 |
| Dell          | 0TP406                      | Desktop     | [28425b209c](https://linux-hardware.org/?probe=28425b209c) | Apr 06, 2022 |
| Dell          | 0TP406                      | Desktop     | [8805b80b73](https://linux-hardware.org/?probe=8805b80b73) | Apr 06, 2022 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | Notebook    | [fe1e7bc4e4](https://linux-hardware.org/?probe=fe1e7bc4e4) | Apr 06, 2022 |
| Dell          | Latitude 3120               | Convertible | [f24c4b6564](https://linux-hardware.org/?probe=f24c4b6564) | Apr 06, 2022 |
| HP            | Laptop 14-df0xxx            | Notebook    | [11e5440dde](https://linux-hardware.org/?probe=11e5440dde) | Apr 06, 2022 |
| HP            | Laptop 14-df0xxx            | Notebook    | [509c236d89](https://linux-hardware.org/?probe=509c236d89) | Apr 06, 2022 |
| ASUSTek       | X756UQK                     | Notebook    | [136b45b510](https://linux-hardware.org/?probe=136b45b510) | Apr 06, 2022 |
| Dell          | 0D24M8 A00                  | Desktop     | [4f81a4a54a](https://linux-hardware.org/?probe=4f81a4a54a) | Apr 06, 2022 |
| Medion        | E15303                      | Notebook    | [21bdec99bb](https://linux-hardware.org/?probe=21bdec99bb) | Apr 05, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [de29cbd8d8](https://linux-hardware.org/?probe=de29cbd8d8) | Apr 05, 2022 |
| Dell          | 09D2HH A00                  | Desktop     | [ed5450f496](https://linux-hardware.org/?probe=ed5450f496) | Apr 05, 2022 |
| ASUSTek       | X756UQK                     | Notebook    | [fc8869d11f](https://linux-hardware.org/?probe=fc8869d11f) | Apr 05, 2022 |
| Dell          | Latitude 3120               | Convertible | [12457a7d44](https://linux-hardware.org/?probe=12457a7d44) | Apr 05, 2022 |
| Dell          | Latitude 3120               | Convertible | [1d02403c4e](https://linux-hardware.org/?probe=1d02403c4e) | Apr 05, 2022 |
| Dell          | Latitude 3189               | Notebook    | [326c734059](https://linux-hardware.org/?probe=326c734059) | Apr 05, 2022 |
| Dell          | Latitude 3310               | Notebook    | [69ee7c1eaf](https://linux-hardware.org/?probe=69ee7c1eaf) | Apr 05, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [e422a0e166](https://linux-hardware.org/?probe=e422a0e166) | Apr 05, 2022 |
| MSI           | MS-7204                     | Desktop     | [e04077c3ac](https://linux-hardware.org/?probe=e04077c3ac) | Apr 05, 2022 |
| MSI           | MS-7204                     | Desktop     | [817c6f06bf](https://linux-hardware.org/?probe=817c6f06bf) | Apr 05, 2022 |
| Dell          | Latitude 3190               | Notebook    | [bac14a83cf](https://linux-hardware.org/?probe=bac14a83cf) | Apr 04, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [1bbdbe7117](https://linux-hardware.org/?probe=1bbdbe7117) | Apr 04, 2022 |
| HP            | 2820h                       | Desktop     | [c4461b3710](https://linux-hardware.org/?probe=c4461b3710) | Apr 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP41... | Convertible | [8f4a6e4775](https://linux-hardware.org/?probe=8f4a6e4775) | Apr 04, 2022 |
| ASRock        | X470 Master SLI             | Desktop     | [255ce25970](https://linux-hardware.org/?probe=255ce25970) | Apr 04, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [1834881ac9](https://linux-hardware.org/?probe=1834881ac9) | Apr 04, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [c1419a6f3c](https://linux-hardware.org/?probe=c1419a6f3c) | Apr 03, 2022 |
| HP            | 0AA8h                       | Desktop     | [f599c9dc5b](https://linux-hardware.org/?probe=f599c9dc5b) | Apr 03, 2022 |
| Dell          | Latitude 5520               | Notebook    | [0fc592dd2c](https://linux-hardware.org/?probe=0fc592dd2c) | Apr 03, 2022 |
| Framework     | Laptop                      | Notebook    | [a0e35b1871](https://linux-hardware.org/?probe=a0e35b1871) | Apr 03, 2022 |
| Minix         | NEO Z83-4 V1.1              | Desktop     | [81925864d4](https://linux-hardware.org/?probe=81925864d4) | Apr 02, 2022 |
| Apple         | Mac-F2218FC8                | All in one  | [cee74cf184](https://linux-hardware.org/?probe=cee74cf184) | Apr 02, 2022 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [0fd3382ba7](https://linux-hardware.org/?probe=0fd3382ba7) | Apr 02, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [0d1d941941](https://linux-hardware.org/?probe=0d1d941941) | Apr 02, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [0c15b6cd16](https://linux-hardware.org/?probe=0c15b6cd16) | Apr 02, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [96c05c62d7](https://linux-hardware.org/?probe=96c05c62d7) | Apr 02, 2022 |
| Lenovo        | 3135 SDK0J40697 WIN 3305... | Mini pc     | [38edda489a](https://linux-hardware.org/?probe=38edda489a) | Apr 01, 2022 |
| HP            | Compaq 6730b (NN204ET#AB... | Notebook    | [4f09568c52](https://linux-hardware.org/?probe=4f09568c52) | Apr 01, 2022 |
| ASUSTek       | Strix GL504GW_GL504GW       | Notebook    | [aa7f16fc39](https://linux-hardware.org/?probe=aa7f16fc39) | Apr 01, 2022 |
| Dell          | Latitude 3390 2-in-1        | Convertible | [d75716478b](https://linux-hardware.org/?probe=d75716478b) | Apr 01, 2022 |
| Lenovo        | ThinkPad Edge E531 6885D... | Notebook    | [913c396bde](https://linux-hardware.org/?probe=913c396bde) | Apr 01, 2022 |
| Lenovo        | ThinkPad Edge E531 6885D... | Notebook    | [6774f9f9c8](https://linux-hardware.org/?probe=6774f9f9c8) | Apr 01, 2022 |
| Lenovo        | 3135 SDK0J40697 WIN 3305... | Mini pc     | [51316d9a43](https://linux-hardware.org/?probe=51316d9a43) | Mar 31, 2022 |
| Acer          | Aspire V3-372               | Notebook    | [f330b12de2](https://linux-hardware.org/?probe=f330b12de2) | Mar 31, 2022 |
| Dell          | Latitude 3189               | Notebook    | [36115f4eb5](https://linux-hardware.org/?probe=36115f4eb5) | Mar 31, 2022 |
| Intel         | D33217GKE G76540-201        | Desktop     | [04874b84db](https://linux-hardware.org/?probe=04874b84db) | Mar 31, 2022 |
| Acer          | EG43M                       | Desktop     | [28b4dd5236](https://linux-hardware.org/?probe=28b4dd5236) | Mar 31, 2022 |
| Toshiba       | Satellite C660D             | Notebook    | [ccdf4d5f94](https://linux-hardware.org/?probe=ccdf4d5f94) | Mar 30, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [271af2d869](https://linux-hardware.org/?probe=271af2d869) | Mar 30, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [001de10f82](https://linux-hardware.org/?probe=001de10f82) | Mar 30, 2022 |
| HP            | 0AA8h                       | Desktop     | [374efb9d66](https://linux-hardware.org/?probe=374efb9d66) | Mar 29, 2022 |
| Gigabyte      | G1.Sniper 5                 | Desktop     | [918167d1e1](https://linux-hardware.org/?probe=918167d1e1) | Mar 29, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V6555        | Notebook    | [b6b724342d](https://linux-hardware.org/?probe=b6b724342d) | Mar 29, 2022 |
| Gigabyte      | EX58-UD4P                   | Desktop     | [b3a7b518b6](https://linux-hardware.org/?probe=b3a7b518b6) | Mar 29, 2022 |
| Lenovo        | ThinkPad X200 7458FDG       | Notebook    | [273e92c386](https://linux-hardware.org/?probe=273e92c386) | Mar 28, 2022 |
| Google        | Guado                       | Desktop     | [b9e3791c3d](https://linux-hardware.org/?probe=b9e3791c3d) | Mar 28, 2022 |
| MeLE          | Rev GMLR1                   | Mini pc     | [1bf135bca8](https://linux-hardware.org/?probe=1bf135bca8) | Mar 28, 2022 |
| Acer          | FMP55                       | Desktop     | [3464cd398f](https://linux-hardware.org/?probe=3464cd398f) | Mar 28, 2022 |
| Lenovo        | ThinkPad X200 7458FDG       | Notebook    | [c53390efae](https://linux-hardware.org/?probe=c53390efae) | Mar 27, 2022 |
| Medion        | MS-7848                     | Desktop     | [8d6108a1a8](https://linux-hardware.org/?probe=8d6108a1a8) | Mar 27, 2022 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [fd1c735c98](https://linux-hardware.org/?probe=fd1c735c98) | Mar 27, 2022 |
| Samsung       | RV420/RV520/RV720/E3530/... | Notebook    | [972823a7b3](https://linux-hardware.org/?probe=972823a7b3) | Mar 27, 2022 |
| Gigabyte      | Z87P-D3                     | Desktop     | [3313178485](https://linux-hardware.org/?probe=3313178485) | Mar 25, 2022 |
| Samsung       | RV420/RV520/RV720/E3530/... | Notebook    | [a087e0e731](https://linux-hardware.org/?probe=a087e0e731) | Mar 25, 2022 |
| Gigabyte      | G1.Sniper 5                 | Desktop     | [272dabac8d](https://linux-hardware.org/?probe=272dabac8d) | Mar 25, 2022 |
| Dell          | Latitude 3300               | Notebook    | [0dbed1a827](https://linux-hardware.org/?probe=0dbed1a827) | Mar 25, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [0bb5a2b0d1](https://linux-hardware.org/?probe=0bb5a2b0d1) | Mar 24, 2022 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [090041bea7](https://linux-hardware.org/?probe=090041bea7) | Mar 24, 2022 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [337b027d96](https://linux-hardware.org/?probe=337b027d96) | Mar 23, 2022 |
| Dell          | Latitude 3120               | Convertible | [6296dda66d](https://linux-hardware.org/?probe=6296dda66d) | Mar 23, 2022 |
| Dell          | Latitude 3120               | Convertible | [72ad8d3201](https://linux-hardware.org/?probe=72ad8d3201) | Mar 23, 2022 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [d081c85de2](https://linux-hardware.org/?probe=d081c85de2) | Mar 23, 2022 |
| Dell          | Latitude 3120               | Convertible | [111659c2f2](https://linux-hardware.org/?probe=111659c2f2) | Mar 23, 2022 |
| Dell          | Latitude 3120               | Convertible | [b38c76b426](https://linux-hardware.org/?probe=b38c76b426) | Mar 23, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [4345817b16](https://linux-hardware.org/?probe=4345817b16) | Mar 23, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U1S... | Notebook    | [f140780c32](https://linux-hardware.org/?probe=f140780c32) | Mar 22, 2022 |
| Gigabyte      | Z370 HD3-OP-CF              | Desktop     | [7bbd4d76d8](https://linux-hardware.org/?probe=7bbd4d76d8) | Mar 22, 2022 |
| Dell          | Latitude 3189               | Notebook    | [1ba82561d5](https://linux-hardware.org/?probe=1ba82561d5) | Mar 22, 2022 |
| Dell          | Latitude 3120               | Convertible | [f674dfe98c](https://linux-hardware.org/?probe=f674dfe98c) | Mar 22, 2022 |
| ASUSTek       | X501A                       | Notebook    | [5c8c010850](https://linux-hardware.org/?probe=5c8c010850) | Mar 22, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [0f99b7ff76](https://linux-hardware.org/?probe=0f99b7ff76) | Mar 21, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [9ff3211d28](https://linux-hardware.org/?probe=9ff3211d28) | Mar 20, 2022 |
| Acer          | Aspire X1440                | Desktop     | [dba7164067](https://linux-hardware.org/?probe=dba7164067) | Mar 20, 2022 |
| HP            | x2 210 G2                   | Tablet      | [1bb8e71c3a](https://linux-hardware.org/?probe=1bb8e71c3a) | Mar 20, 2022 |
| HP            | x2 210 G2                   | Tablet      | [af84bc2d89](https://linux-hardware.org/?probe=af84bc2d89) | Mar 20, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [861e43b0c6](https://linux-hardware.org/?probe=861e43b0c6) | Mar 19, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [8328ee30d7](https://linux-hardware.org/?probe=8328ee30d7) | Mar 19, 2022 |
| Online Lab... | SR 42                       | Desktop     | [2e13340a50](https://linux-hardware.org/?probe=2e13340a50) | Mar 19, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [0207f22677](https://linux-hardware.org/?probe=0207f22677) | Mar 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [2c1ca9145b](https://linux-hardware.org/?probe=2c1ca9145b) | Mar 18, 2022 |
| ASRock        | H370M-ITX/ac                | Desktop     | [e425e911e9](https://linux-hardware.org/?probe=e425e911e9) | Mar 18, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [687497e8c2](https://linux-hardware.org/?probe=687497e8c2) | Mar 18, 2022 |
| Dell          | Latitude 3189               | Notebook    | [89ec672f05](https://linux-hardware.org/?probe=89ec672f05) | Mar 18, 2022 |
| Acer          | Aspire A317-51G             | Notebook    | [f2a7cadaff](https://linux-hardware.org/?probe=f2a7cadaff) | Mar 18, 2022 |
| ASUSTek       | Hematite                    | Desktop     | [e4258e3376](https://linux-hardware.org/?probe=e4258e3376) | Mar 17, 2022 |
| ASUSTek       | M2A-VM HDMI                 | Desktop     | [ea35877485](https://linux-hardware.org/?probe=ea35877485) | Mar 17, 2022 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [80788c6cd4](https://linux-hardware.org/?probe=80788c6cd4) | Mar 17, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [07ed5bde71](https://linux-hardware.org/?probe=07ed5bde71) | Mar 17, 2022 |
| Timi          | TM1613                      | Notebook    | [1127e193e2](https://linux-hardware.org/?probe=1127e193e2) | Mar 17, 2022 |
| ASUSTek       | Rampage IV FORMULA          | Desktop     | [433ed3c3d7](https://linux-hardware.org/?probe=433ed3c3d7) | Mar 17, 2022 |
| Dell          | Latitude 3390 2-in-1        | Convertible | [2df1532313](https://linux-hardware.org/?probe=2df1532313) | Mar 17, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [781207a46b](https://linux-hardware.org/?probe=781207a46b) | Mar 17, 2022 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [e704011071](https://linux-hardware.org/?probe=e704011071) | Mar 16, 2022 |
| Dell          | Latitude 3120               | Convertible | [5a7e1993ff](https://linux-hardware.org/?probe=5a7e1993ff) | Mar 16, 2022 |
| HP            | 826A A01                    | All in one  | [e7df5fb705](https://linux-hardware.org/?probe=e7df5fb705) | Mar 16, 2022 |
| Samsung       | RV420/RV520/RV720/E3530/... | Notebook    | [13baa252d4](https://linux-hardware.org/?probe=13baa252d4) | Mar 16, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [624b149362](https://linux-hardware.org/?probe=624b149362) | Mar 15, 2022 |
| ASRock        | Z87 Professional            | Desktop     | [e75eb7a802](https://linux-hardware.org/?probe=e75eb7a802) | Mar 15, 2022 |
| Dell          | 06X1TJ A00                  | Desktop     | [0480518e2e](https://linux-hardware.org/?probe=0480518e2e) | Mar 15, 2022 |
| Dell          | Precision 7540              | Notebook    | [0af29774c8](https://linux-hardware.org/?probe=0af29774c8) | Mar 15, 2022 |
| Dell          | Latitude 3120               | Convertible | [68195969f8](https://linux-hardware.org/?probe=68195969f8) | Mar 15, 2022 |
| Lenovo        | ThinkPad X200 7458FDG       | Notebook    | [0fa518d174](https://linux-hardware.org/?probe=0fa518d174) | Mar 15, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [7c09492e3b](https://linux-hardware.org/?probe=7c09492e3b) | Mar 14, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [f7e85dbf71](https://linux-hardware.org/?probe=f7e85dbf71) | Mar 14, 2022 |
| Apple         | Mac-F2268CC8                | All in one  | [d3cf4d161d](https://linux-hardware.org/?probe=d3cf4d161d) | Mar 13, 2022 |
| ASUSTek       | M4A87TD                     | Desktop     | [aded9135ae](https://linux-hardware.org/?probe=aded9135ae) | Mar 13, 2022 |
| Samsung       | RV420/RV520/RV720/E3530/... | Notebook    | [a4b13c65c3](https://linux-hardware.org/?probe=a4b13c65c3) | Mar 13, 2022 |
| Acer          | TravelMate B113             | Notebook    | [e4b608fade](https://linux-hardware.org/?probe=e4b608fade) | Mar 13, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [6b82f2f5f8](https://linux-hardware.org/?probe=6b82f2f5f8) | Mar 13, 2022 |
| ASUSTek       | P5QL-E                      | Desktop     | [e73adbc339](https://linux-hardware.org/?probe=e73adbc339) | Mar 12, 2022 |
| ASUSTek       | F5RL                        | Notebook    | [aed8a7279f](https://linux-hardware.org/?probe=aed8a7279f) | Mar 12, 2022 |
| Lenovo        | Y310                        | Notebook    | [96745135a2](https://linux-hardware.org/?probe=96745135a2) | Mar 12, 2022 |
| HP            | 8767 A                      | Desktop     | [6eca88e86f](https://linux-hardware.org/?probe=6eca88e86f) | Mar 12, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [48767ec6ab](https://linux-hardware.org/?probe=48767ec6ab) | Mar 11, 2022 |
| Dell          | Latitude 3310               | Notebook    | [d0f00ace6c](https://linux-hardware.org/?probe=d0f00ace6c) | Mar 11, 2022 |
| Dell          | Latitude 3390 2-in-1        | Notebook    | [b482b781bd](https://linux-hardware.org/?probe=b482b781bd) | Mar 11, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [43bb230e40](https://linux-hardware.org/?probe=43bb230e40) | Mar 11, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [2b1ac5c4f4](https://linux-hardware.org/?probe=2b1ac5c4f4) | Mar 11, 2022 |
| Dell          | Latitude 3120               | Convertible | [11a913c19d](https://linux-hardware.org/?probe=11a913c19d) | Mar 11, 2022 |
| Apple         | Mac-F2268CC8                | All in one  | [fe9ab2819c](https://linux-hardware.org/?probe=fe9ab2819c) | Mar 11, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [889e5fe7a3](https://linux-hardware.org/?probe=889e5fe7a3) | Mar 11, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [02df6e8b6e](https://linux-hardware.org/?probe=02df6e8b6e) | Mar 10, 2022 |
| Dell          | Latitude 3120               | Convertible | [8cb0c8f9c9](https://linux-hardware.org/?probe=8cb0c8f9c9) | Mar 10, 2022 |
| ASUSTek       | P8P67                       | Desktop     | [33bf33cb8d](https://linux-hardware.org/?probe=33bf33cb8d) | Mar 10, 2022 |
| Intel         | NUC8BEB J72692-310          | Mini pc     | [2068efcd75](https://linux-hardware.org/?probe=2068efcd75) | Mar 10, 2022 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [6536e752dd](https://linux-hardware.org/?probe=6536e752dd) | Mar 10, 2022 |
| Unknown       | Unknown                     | Desktop     | [b60fd7636c](https://linux-hardware.org/?probe=b60fd7636c) | Mar 10, 2022 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [0bd936f5b1](https://linux-hardware.org/?probe=0bd936f5b1) | Mar 09, 2022 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [85bfdc09db](https://linux-hardware.org/?probe=85bfdc09db) | Mar 09, 2022 |
| Gigabyte      | B660 GAMING X DDR4          | Desktop     | [77b32e1116](https://linux-hardware.org/?probe=77b32e1116) | Mar 09, 2022 |
| Toshiba       | Satellite L350D             | Notebook    | [8023f07e6c](https://linux-hardware.org/?probe=8023f07e6c) | Mar 09, 2022 |
| HP            | ZBook 15 G6                 | Notebook    | [41ac7effbe](https://linux-hardware.org/?probe=41ac7effbe) | Mar 09, 2022 |
| Dell          | Latitude 3120               | Convertible | [2de1ff0870](https://linux-hardware.org/?probe=2de1ff0870) | Mar 09, 2022 |
| Toshiba       | TECRA Z50-A                 | Notebook    | [cc5f0f79dd](https://linux-hardware.org/?probe=cc5f0f79dd) | Mar 09, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [95b7c99a5a](https://linux-hardware.org/?probe=95b7c99a5a) | Mar 08, 2022 |
| Dell          | Latitude 3180               | Notebook    | [87f27d2503](https://linux-hardware.org/?probe=87f27d2503) | Mar 08, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [7cf1e6f3af](https://linux-hardware.org/?probe=7cf1e6f3af) | Mar 08, 2022 |
| Dell          | Latitude 3310               | Notebook    | [0268bb19d1](https://linux-hardware.org/?probe=0268bb19d1) | Mar 07, 2022 |
| Dell          | Latitude 3120               | Convertible | [18f9eef1a1](https://linux-hardware.org/?probe=18f9eef1a1) | Mar 07, 2022 |
| Acer          | EG43M                       | Desktop     | [3df7717081](https://linux-hardware.org/?probe=3df7717081) | Mar 06, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [f9c159a911](https://linux-hardware.org/?probe=f9c159a911) | Mar 06, 2022 |
| HPE           | ProLiant MicroServer Gen... | Server      | [f7739e263e](https://linux-hardware.org/?probe=f7739e263e) | Mar 06, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [ec13383aff](https://linux-hardware.org/?probe=ec13383aff) | Mar 06, 2022 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [be661f5a39](https://linux-hardware.org/?probe=be661f5a39) | Mar 05, 2022 |
| Acer          | TravelMate B113             | Notebook    | [12d09f53a2](https://linux-hardware.org/?probe=12d09f53a2) | Mar 05, 2022 |
| Dell          | 0WR7PY A00                  | Desktop     | [19895058a5](https://linux-hardware.org/?probe=19895058a5) | Mar 05, 2022 |
| ASRock        | FM2A58M-DG3+                | Desktop     | [0b7875b1b5](https://linux-hardware.org/?probe=0b7875b1b5) | Mar 05, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [3345ff19cd](https://linux-hardware.org/?probe=3345ff19cd) | Mar 04, 2022 |
| HP            | ProBook 4720s               | Notebook    | [631600dd74](https://linux-hardware.org/?probe=631600dd74) | Mar 04, 2022 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [d37684f01f](https://linux-hardware.org/?probe=d37684f01f) | Mar 04, 2022 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [30da3f764c](https://linux-hardware.org/?probe=30da3f764c) | Mar 04, 2022 |
| HP            | Pavilion dv7                | Notebook    | [db550138fb](https://linux-hardware.org/?probe=db550138fb) | Mar 03, 2022 |
| SLIMBOOK      | ONE-AMD-M4                  | Desktop     | [d92c05a18a](https://linux-hardware.org/?probe=d92c05a18a) | Mar 03, 2022 |
| HP            | ProBook 4720s               | Notebook    | [8afd2b3c97](https://linux-hardware.org/?probe=8afd2b3c97) | Mar 03, 2022 |
| Dell          | Latitude 3120               | Convertible | [6f02843a83](https://linux-hardware.org/?probe=6f02843a83) | Mar 03, 2022 |
| ASRock        | AB350M Pro4                 | Desktop     | [6ea2fbdb95](https://linux-hardware.org/?probe=6ea2fbdb95) | Mar 03, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [851e340c24](https://linux-hardware.org/?probe=851e340c24) | Mar 03, 2022 |
| Dell          | Latitude 3120               | Convertible | [b4cda44b20](https://linux-hardware.org/?probe=b4cda44b20) | Mar 03, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [70d2afda85](https://linux-hardware.org/?probe=70d2afda85) | Mar 03, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [d4bbdbf3d7](https://linux-hardware.org/?probe=d4bbdbf3d7) | Mar 03, 2022 |
| Gigabyte      | Z590 UD AC                  | Desktop     | [5e75b405ea](https://linux-hardware.org/?probe=5e75b405ea) | Mar 02, 2022 |
| Gigabyte      | Z590 UD AC                  | Desktop     | [74601a3854](https://linux-hardware.org/?probe=74601a3854) | Mar 02, 2022 |
| HP            | Compaq 6730b (NN204ET#AB... | Notebook    | [f20f8759b1](https://linux-hardware.org/?probe=f20f8759b1) | Mar 02, 2022 |
| Dell          | XPS 13 9333                 | Notebook    | [93ec468fa7](https://linux-hardware.org/?probe=93ec468fa7) | Mar 02, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [7af526bbb7](https://linux-hardware.org/?probe=7af526bbb7) | Mar 01, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [dcd6f3190e](https://linux-hardware.org/?probe=dcd6f3190e) | Mar 01, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [96f81d9300](https://linux-hardware.org/?probe=96f81d9300) | Mar 01, 2022 |
| Gigabyte      | P55A-UD3                    | Desktop     | [677fa0d0a3](https://linux-hardware.org/?probe=677fa0d0a3) | Mar 01, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [e81420b85c](https://linux-hardware.org/?probe=e81420b85c) | Mar 01, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [01f6429898](https://linux-hardware.org/?probe=01f6429898) | Mar 01, 2022 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | Notebook    | [159807ca18](https://linux-hardware.org/?probe=159807ca18) | Feb 28, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [1c7889cec5](https://linux-hardware.org/?probe=1c7889cec5) | Feb 28, 2022 |
| HP            | EliteBook 840 G4            | Notebook    | [c00d2254e9](https://linux-hardware.org/?probe=c00d2254e9) | Feb 28, 2022 |
| HP            | EliteBook 840 G4            | Notebook    | [4e9488a678](https://linux-hardware.org/?probe=4e9488a678) | Feb 28, 2022 |
| Medion        | E6226                       | Notebook    | [ef3a4be7c2](https://linux-hardware.org/?probe=ef3a4be7c2) | Feb 27, 2022 |
| Medion        | P6812                       | Notebook    | [b458fbb9de](https://linux-hardware.org/?probe=b458fbb9de) | Feb 27, 2022 |
| Lenovo        | G70-70 80HW007LNX           | Notebook    | [a0ba78ccea](https://linux-hardware.org/?probe=a0ba78ccea) | Feb 27, 2022 |
| HP            | ZBook 15 G6                 | Notebook    | [e7a8b4af9f](https://linux-hardware.org/?probe=e7a8b4af9f) | Feb 27, 2022 |
| TYAN Compu... | S7012                       | Server      | [fec98b51da](https://linux-hardware.org/?probe=fec98b51da) | Feb 27, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [71a4f46379](https://linux-hardware.org/?probe=71a4f46379) | Feb 27, 2022 |
| HP            | 0B54h D                     | Desktop     | [56502d78cd](https://linux-hardware.org/?probe=56502d78cd) | Feb 26, 2022 |
| Medion        | WIM2140                     | Notebook    | [ce6005769a](https://linux-hardware.org/?probe=ce6005769a) | Feb 26, 2022 |
| TYAN Compu... | S7012                       | Server      | [81a490184b](https://linux-hardware.org/?probe=81a490184b) | Feb 26, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [71a28af480](https://linux-hardware.org/?probe=71a28af480) | Feb 25, 2022 |
| Microsoft     | Surface Book                | Tablet      | [dc0e450d2c](https://linux-hardware.org/?probe=dc0e450d2c) | Feb 25, 2022 |
| HP            | Compaq nc6320 (RH380ET#A... | Notebook    | [a1a7a8fd65](https://linux-hardware.org/?probe=a1a7a8fd65) | Feb 25, 2022 |
| Dell          | Latitude 3540               | Notebook    | [6fb057646a](https://linux-hardware.org/?probe=6fb057646a) | Feb 25, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [34d4439b39](https://linux-hardware.org/?probe=34d4439b39) | Feb 25, 2022 |
| Dell          | 0FJ030                      | Desktop     | [7a5ba0085b](https://linux-hardware.org/?probe=7a5ba0085b) | Feb 25, 2022 |
| HP            | EliteBook 820 G4            | Notebook    | [2d4387b0f4](https://linux-hardware.org/?probe=2d4387b0f4) | Feb 24, 2022 |
| Samsung       | 950QCG                      | Convertible | [5b950e3462](https://linux-hardware.org/?probe=5b950e3462) | Feb 24, 2022 |
| ASUSTek       | Q87M-E                      | Desktop     | [9d4c111e9a](https://linux-hardware.org/?probe=9d4c111e9a) | Feb 23, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [46cf1eb748](https://linux-hardware.org/?probe=46cf1eb748) | Feb 23, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [dd889a3b3e](https://linux-hardware.org/?probe=dd889a3b3e) | Feb 23, 2022 |
| ASUSTek       | P8H67                       | Desktop     | [8f3572d865](https://linux-hardware.org/?probe=8f3572d865) | Feb 23, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [52bbb8515e](https://linux-hardware.org/?probe=52bbb8515e) | Feb 23, 2022 |
| TYAN Compu... | D1691 S26361-D1691          | Desktop     | [2e2ef200f8](https://linux-hardware.org/?probe=2e2ef200f8) | Feb 23, 2022 |
| TYAN Compu... | D1691 S26361-D1691          | Desktop     | [7d04325630](https://linux-hardware.org/?probe=7d04325630) | Feb 22, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [6c5203e00a](https://linux-hardware.org/?probe=6c5203e00a) | Feb 22, 2022 |
| Toshiba       | Satellite C50-A-19T         | Notebook    | [c0735b93a0](https://linux-hardware.org/?probe=c0735b93a0) | Feb 22, 2022 |
| Toshiba       | Satellite C50-A-19T         | Notebook    | [c307c3abc8](https://linux-hardware.org/?probe=c307c3abc8) | Feb 22, 2022 |
| Acer          | Aspire E5-774               | Notebook    | [39ee56bc80](https://linux-hardware.org/?probe=39ee56bc80) | Feb 21, 2022 |
| ASUSTek       | F1A55-M LX                  | Desktop     | [c032200973](https://linux-hardware.org/?probe=c032200973) | Feb 21, 2022 |
| ASUSTek       | F1A55-M LX                  | Desktop     | [1980619c3c](https://linux-hardware.org/?probe=1980619c3c) | Feb 21, 2022 |
| ASUSTek       | K52F                        | Notebook    | [51504b5b77](https://linux-hardware.org/?probe=51504b5b77) | Feb 21, 2022 |
| MSI           | GT70 2OC/2OD                | Notebook    | [bae169d343](https://linux-hardware.org/?probe=bae169d343) | Feb 21, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [6808e089af](https://linux-hardware.org/?probe=6808e089af) | Feb 21, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [41a38c1e60](https://linux-hardware.org/?probe=41a38c1e60) | Feb 21, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [e1943c32e9](https://linux-hardware.org/?probe=e1943c32e9) | Feb 20, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [362c220f2d](https://linux-hardware.org/?probe=362c220f2d) | Feb 20, 2022 |
| HP            | 1998                        | Desktop     | [1cd99a92d0](https://linux-hardware.org/?probe=1cd99a92d0) | Feb 20, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [39a12eaef0](https://linux-hardware.org/?probe=39a12eaef0) | Feb 20, 2022 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [9d3a5fd18e](https://linux-hardware.org/?probe=9d3a5fd18e) | Feb 20, 2022 |
| Lenovo        | G505 20240                  | Notebook    | [7813a47a19](https://linux-hardware.org/?probe=7813a47a19) | Feb 20, 2022 |
| HP            | 3397                        | Desktop     | [05cb6a1cf3](https://linux-hardware.org/?probe=05cb6a1cf3) | Feb 19, 2022 |
| MSI           | MS-AAA71 100                | Desktop     | [cf1a921cae](https://linux-hardware.org/?probe=cf1a921cae) | Feb 19, 2022 |
| ASRock        | FM2A75 Pro4-M               | Desktop     | [fd9cad1813](https://linux-hardware.org/?probe=fd9cad1813) | Feb 19, 2022 |
| ASUSTek       | X705UDR                     | Notebook    | [6788479ad3](https://linux-hardware.org/?probe=6788479ad3) | Feb 18, 2022 |
| MSI           | MS-B9181                    | Desktop     | [e9c63013e3](https://linux-hardware.org/?probe=e9c63013e3) | Feb 18, 2022 |
| Biostar       | A960A3+                     | Desktop     | [cafdbc0ef4](https://linux-hardware.org/?probe=cafdbc0ef4) | Feb 18, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [ff74abc44d](https://linux-hardware.org/?probe=ff74abc44d) | Feb 18, 2022 |
| ASUSTek       | ROG ZENITH II EXTREME AL... | Desktop     | [15efc7df1a](https://linux-hardware.org/?probe=15efc7df1a) | Feb 18, 2022 |
| ASUSTek       | B150M-PLUS                  | Desktop     | [40b6be481b](https://linux-hardware.org/?probe=40b6be481b) | Feb 17, 2022 |
| Acer          | Extensa 5230                | Notebook    | [3c58103e6a](https://linux-hardware.org/?probe=3c58103e6a) | Feb 17, 2022 |
| HP            | ProBook 470 G4              | Notebook    | [e612c279bf](https://linux-hardware.org/?probe=e612c279bf) | Feb 17, 2022 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [41713d7553](https://linux-hardware.org/?probe=41713d7553) | Feb 17, 2022 |
| Google        | Buddy                       | Desktop     | [ad6c39107e](https://linux-hardware.org/?probe=ad6c39107e) | Feb 17, 2022 |
| Google        | Buddy                       | Desktop     | [bfc46ff8aa](https://linux-hardware.org/?probe=bfc46ff8aa) | Feb 17, 2022 |
| Dell          | Latitude E5550              | Notebook    | [302c0a3b5f](https://linux-hardware.org/?probe=302c0a3b5f) | Feb 16, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [41039ffe41](https://linux-hardware.org/?probe=41039ffe41) | Feb 16, 2022 |
| HP            | Pavilion g7                 | Notebook    | [d550adc412](https://linux-hardware.org/?probe=d550adc412) | Feb 16, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [4ebe999152](https://linux-hardware.org/?probe=4ebe999152) | Feb 16, 2022 |
| HP            | 3031h                       | Desktop     | [2c5079d9d8](https://linux-hardware.org/?probe=2c5079d9d8) | Feb 16, 2022 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [9a95256627](https://linux-hardware.org/?probe=9a95256627) | Feb 16, 2022 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | Mini pc     | [c7930b0d92](https://linux-hardware.org/?probe=c7930b0d92) | Feb 15, 2022 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | Mini pc     | [b0d7840143](https://linux-hardware.org/?probe=b0d7840143) | Feb 15, 2022 |
| Google        | Chell                       | Notebook    | [a7795e2fb9](https://linux-hardware.org/?probe=a7795e2fb9) | Feb 15, 2022 |
| Google        | Chell                       | Notebook    | [9ec35bc2d1](https://linux-hardware.org/?probe=9ec35bc2d1) | Feb 15, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [832c433c19](https://linux-hardware.org/?probe=832c433c19) | Feb 15, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [bd1fb80901](https://linux-hardware.org/?probe=bd1fb80901) | Feb 15, 2022 |
| ASUSTek       | F5VL                        | Notebook    | [acdfe6952b](https://linux-hardware.org/?probe=acdfe6952b) | Feb 13, 2022 |
| Acer          | Aspire A114-32              | Notebook    | [ac87b42a18](https://linux-hardware.org/?probe=ac87b42a18) | Feb 13, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [73752ed315](https://linux-hardware.org/?probe=73752ed315) | Feb 13, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [74ae2ff1b5](https://linux-hardware.org/?probe=74ae2ff1b5) | Feb 13, 2022 |
| HP            | 3031h                       | Desktop     | [1475e006cd](https://linux-hardware.org/?probe=1475e006cd) | Feb 13, 2022 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [d5ba9deed5](https://linux-hardware.org/?probe=d5ba9deed5) | Feb 13, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [05460455bc](https://linux-hardware.org/?probe=05460455bc) | Feb 12, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [f84892675f](https://linux-hardware.org/?probe=f84892675f) | Feb 12, 2022 |
| Gigabyte      | B460M DS3H V2               | Desktop     | [791cf67d84](https://linux-hardware.org/?probe=791cf67d84) | Feb 12, 2022 |
| Acer          | Aspire M3920                | Desktop     | [8f76b3f28c](https://linux-hardware.org/?probe=8f76b3f28c) | Feb 12, 2022 |
| Dell          | Latitude E5540              | Notebook    | [b5d2027192](https://linux-hardware.org/?probe=b5d2027192) | Feb 12, 2022 |
| Lenovo        | ThinkPad T500 2241CT7       | Notebook    | [e8559e7aba](https://linux-hardware.org/?probe=e8559e7aba) | Feb 12, 2022 |
| Acer          | Aspire M3920                | Desktop     | [9f171d548e](https://linux-hardware.org/?probe=9f171d548e) | Feb 12, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [ad7ba85afc](https://linux-hardware.org/?probe=ad7ba85afc) | Feb 11, 2022 |
| ASRock        | Z370M Pro4                  | Desktop     | [f98f8c1b7e](https://linux-hardware.org/?probe=f98f8c1b7e) | Feb 11, 2022 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [1b6bf699a8](https://linux-hardware.org/?probe=1b6bf699a8) | Feb 11, 2022 |
| Dell          | Latitude E7240              | Notebook    | [0ba881cc6e](https://linux-hardware.org/?probe=0ba881cc6e) | Feb 11, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [d0bc075b13](https://linux-hardware.org/?probe=d0bc075b13) | Feb 11, 2022 |
| Acer          | Aspire ES1-520              | Notebook    | [dadc839fc9](https://linux-hardware.org/?probe=dadc839fc9) | Feb 10, 2022 |
| TongFang      | LYNX 4                      | Notebook    | [425c72db05](https://linux-hardware.org/?probe=425c72db05) | Feb 10, 2022 |
| ASUSTek       | Rampage II GENE             | Desktop     | [2f13c2e219](https://linux-hardware.org/?probe=2f13c2e219) | Feb 10, 2022 |
| ASUSTek       | X751LAB                     | Notebook    | [53d804a7ed](https://linux-hardware.org/?probe=53d804a7ed) | Feb 09, 2022 |
| Gigabyte      | H81M-HD3                    | Desktop     | [c0334497da](https://linux-hardware.org/?probe=c0334497da) | Feb 09, 2022 |
| Sony          | VGN-FW51JF_H                | Notebook    | [922a10f2f4](https://linux-hardware.org/?probe=922a10f2f4) | Feb 09, 2022 |
| Dell          | Latitude E6420              | Notebook    | [85d1f4fe0a](https://linux-hardware.org/?probe=85d1f4fe0a) | Feb 09, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [d73530de34](https://linux-hardware.org/?probe=d73530de34) | Feb 09, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [0c4ce33bab](https://linux-hardware.org/?probe=0c4ce33bab) | Feb 08, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [691b0d2c8a](https://linux-hardware.org/?probe=691b0d2c8a) | Feb 08, 2022 |
| Notebook      | N85_N87,HJ,HJ1,HK1          | Notebook    | [0ec0943d03](https://linux-hardware.org/?probe=0ec0943d03) | Feb 08, 2022 |
| Dell          | Studio 1747                 | Notebook    | [3ba0a684e4](https://linux-hardware.org/?probe=3ba0a684e4) | Feb 07, 2022 |
| Lenovo        | Y310                        | Notebook    | [11bab215f5](https://linux-hardware.org/?probe=11bab215f5) | Feb 07, 2022 |
| ASUSTek       | K73SD                       | Notebook    | [ee4f8f2bfb](https://linux-hardware.org/?probe=ee4f8f2bfb) | Feb 07, 2022 |
| Lenovo        | ThinkPad W510 431963G       | Notebook    | [a2e027fa38](https://linux-hardware.org/?probe=a2e027fa38) | Feb 07, 2022 |
| Lenovo        | G70-70 80HW007LNX           | Notebook    | [79e8d4895c](https://linux-hardware.org/?probe=79e8d4895c) | Feb 06, 2022 |
| Acer          | Aspire 5600                 | Notebook    | [35dd7239e3](https://linux-hardware.org/?probe=35dd7239e3) | Feb 06, 2022 |
| Acer          | Aspire 5600                 | Notebook    | [4d2723a19e](https://linux-hardware.org/?probe=4d2723a19e) | Feb 06, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [b3ff58ce92](https://linux-hardware.org/?probe=b3ff58ce92) | Feb 06, 2022 |
| Dell          | System XPS L502X            | Notebook    | [c2a3b5d930](https://linux-hardware.org/?probe=c2a3b5d930) | Feb 05, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [25d529f5d7](https://linux-hardware.org/?probe=25d529f5d7) | Feb 05, 2022 |
| ASUSTek       | ROG Strix G713QE_G713QE     | Notebook    | [af586bb69e](https://linux-hardware.org/?probe=af586bb69e) | Feb 05, 2022 |
| Dell          | Latitude E6420              | Notebook    | [45ce016cb4](https://linux-hardware.org/?probe=45ce016cb4) | Feb 05, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [711d2a668d](https://linux-hardware.org/?probe=711d2a668d) | Feb 05, 2022 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [451c540217](https://linux-hardware.org/?probe=451c540217) | Feb 05, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [2f03547791](https://linux-hardware.org/?probe=2f03547791) | Feb 05, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [cf90d5430c](https://linux-hardware.org/?probe=cf90d5430c) | Feb 04, 2022 |
| Medion        | B360H4-EM V1.0              | Desktop     | [d1518dc34b](https://linux-hardware.org/?probe=d1518dc34b) | Feb 04, 2022 |
| Notebook      | PCx0Dx                      | Notebook    | [d14bd1019f](https://linux-hardware.org/?probe=d14bd1019f) | Feb 04, 2022 |
| Notebook      | PCx0Dx                      | Notebook    | [6a6b14cdb5](https://linux-hardware.org/?probe=6a6b14cdb5) | Feb 04, 2022 |
| ASRock        | 870 Extreme3                | Desktop     | [6bbf5f06c2](https://linux-hardware.org/?probe=6bbf5f06c2) | Feb 03, 2022 |
| ASUSTek       | N750JV                      | Notebook    | [bd64d6f2dc](https://linux-hardware.org/?probe=bd64d6f2dc) | Feb 03, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [b5d54059d7](https://linux-hardware.org/?probe=b5d54059d7) | Feb 03, 2022 |
| Gigabyte      | H81M-H                      | Desktop     | [4c55c42084](https://linux-hardware.org/?probe=4c55c42084) | Feb 03, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [3e91c92999](https://linux-hardware.org/?probe=3e91c92999) | Feb 02, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [e1c7c237e8](https://linux-hardware.org/?probe=e1c7c237e8) | Feb 02, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [7b7a2f85e0](https://linux-hardware.org/?probe=7b7a2f85e0) | Feb 02, 2022 |
| Notebook      | PA70ES                      | Notebook    | [794ffc9a83](https://linux-hardware.org/?probe=794ffc9a83) | Feb 02, 2022 |
| Dell          | 0H21J3 A09                  | Server      | [c0aa1bf2f1](https://linux-hardware.org/?probe=c0aa1bf2f1) | Feb 02, 2022 |
| Dell          | 0H21J3 A09                  | Server      | [6b48b653ea](https://linux-hardware.org/?probe=6b48b653ea) | Feb 02, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [7d22e9e472](https://linux-hardware.org/?probe=7d22e9e472) | Feb 02, 2022 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [81f3f014e7](https://linux-hardware.org/?probe=81f3f014e7) | Feb 01, 2022 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [8699f7407a](https://linux-hardware.org/?probe=8699f7407a) | Feb 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [f302ce9f42](https://linux-hardware.org/?probe=f302ce9f42) | Feb 01, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [c8025340af](https://linux-hardware.org/?probe=c8025340af) | Feb 01, 2022 |
| ASUSTek       | N56VM                       | Notebook    | [6ad187a1ef](https://linux-hardware.org/?probe=6ad187a1ef) | Feb 01, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [a598d34d8b](https://linux-hardware.org/?probe=a598d34d8b) | Feb 01, 2022 |
| ASUSTek       | N750JV                      | Notebook    | [dc4c5eb361](https://linux-hardware.org/?probe=dc4c5eb361) | Feb 01, 2022 |
| HP            | EliteBook 725 G2            | Notebook    | [d49dd26324](https://linux-hardware.org/?probe=d49dd26324) | Feb 01, 2022 |
| HP            | 158A                        | Desktop     | [1f77d0f211](https://linux-hardware.org/?probe=1f77d0f211) | Feb 01, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [27f07635df](https://linux-hardware.org/?probe=27f07635df) | Jan 31, 2022 |
| Lenovo        | 374F SDK0R32862 WIN 3258... | Desktop     | [ee7ecf2967](https://linux-hardware.org/?probe=ee7ecf2967) | Jan 31, 2022 |
| Lenovo        | Y310                        | Notebook    | [e72f6125db](https://linux-hardware.org/?probe=e72f6125db) | Jan 31, 2022 |
| Dell          | Latitude 7410               | Notebook    | [5f60c8df83](https://linux-hardware.org/?probe=5f60c8df83) | Jan 31, 2022 |
| HP            | ProBook 4310s               | Notebook    | [d256362c70](https://linux-hardware.org/?probe=d256362c70) | Jan 30, 2022 |
| HP            | ProBook 4310s               | Notebook    | [333d4b626a](https://linux-hardware.org/?probe=333d4b626a) | Jan 30, 2022 |
| Lenovo        | ThinkPad E570 20H500B4MH    | Notebook    | [209156e57d](https://linux-hardware.org/?probe=209156e57d) | Jan 29, 2022 |
| Lenovo        | ThinkPad E570 20H500B4MH    | Notebook    | [2f9a17c907](https://linux-hardware.org/?probe=2f9a17c907) | Jan 29, 2022 |
| Dell          | Precision 7520              | Notebook    | [4cdcfc0e31](https://linux-hardware.org/?probe=4cdcfc0e31) | Jan 29, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [e498058bd8](https://linux-hardware.org/?probe=e498058bd8) | Jan 28, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [a2e3ba2bd6](https://linux-hardware.org/?probe=a2e3ba2bd6) | Jan 28, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [ce77a09245](https://linux-hardware.org/?probe=ce77a09245) | Jan 28, 2022 |
| ASUSTek       | P5Q SE2                     | Desktop     | [c599255dc5](https://linux-hardware.org/?probe=c599255dc5) | Jan 28, 2022 |
| Lenovo        | ThinkPad L380 20M5003GMH    | Notebook    | [df98a8a0b7](https://linux-hardware.org/?probe=df98a8a0b7) | Jan 27, 2022 |
| Lenovo        | ThinkPad L380 20M5003GMH    | Notebook    | [a1b013a1cf](https://linux-hardware.org/?probe=a1b013a1cf) | Jan 27, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [289d329def](https://linux-hardware.org/?probe=289d329def) | Jan 27, 2022 |
| Dell          | Latitude 3120               | Convertible | [7c22aca292](https://linux-hardware.org/?probe=7c22aca292) | Jan 26, 2022 |
| MSI           | Z97 GAMING 3                | Desktop     | [7bf9b21a5c](https://linux-hardware.org/?probe=7bf9b21a5c) | Jan 25, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [16aeee2b77](https://linux-hardware.org/?probe=16aeee2b77) | Jan 24, 2022 |
| ASUSTek       | ZenBook UX363EA_UX371EA     | Convertible | [6593d27252](https://linux-hardware.org/?probe=6593d27252) | Jan 24, 2022 |
| ASUSTek       | ZenBook UX363EA_UX371EA     | Convertible | [b5899e206a](https://linux-hardware.org/?probe=b5899e206a) | Jan 24, 2022 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [1fabe2847b](https://linux-hardware.org/?probe=1fabe2847b) | Jan 24, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [813105d44d](https://linux-hardware.org/?probe=813105d44d) | Jan 24, 2022 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [a34f050707](https://linux-hardware.org/?probe=a34f050707) | Jan 24, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [1bea66eb77](https://linux-hardware.org/?probe=1bea66eb77) | Jan 23, 2022 |
| Acer          | Aspire E1-572G              | Notebook    | [26dbe44da4](https://linux-hardware.org/?probe=26dbe44da4) | Jan 23, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [e4f1a055f6](https://linux-hardware.org/?probe=e4f1a055f6) | Jan 23, 2022 |
| Phoenix/Si... | M7x0S                       | Notebook    | [85f4d256df](https://linux-hardware.org/?probe=85f4d256df) | Jan 23, 2022 |
| Phoenix/Si... | M7x0S                       | Notebook    | [1c646d422a](https://linux-hardware.org/?probe=1c646d422a) | Jan 23, 2022 |
| Medion        | Akoya E6412T                | Notebook    | [c6d08ba1cd](https://linux-hardware.org/?probe=c6d08ba1cd) | Jan 22, 2022 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [3c6b61aac9](https://linux-hardware.org/?probe=3c6b61aac9) | Jan 22, 2022 |
| Gateway       | NV57H                       | Notebook    | [0ddff00cb3](https://linux-hardware.org/?probe=0ddff00cb3) | Jan 22, 2022 |
| ASUSTek       | Rampage II GENE             | Desktop     | [7bda8eb36a](https://linux-hardware.org/?probe=7bda8eb36a) | Jan 21, 2022 |
| HP            | ZBook 14                    | Notebook    | [b64ef7e687](https://linux-hardware.org/?probe=b64ef7e687) | Jan 21, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [eee753c85b](https://linux-hardware.org/?probe=eee753c85b) | Jan 21, 2022 |
| HP            | 158A                        | Desktop     | [c889f7be59](https://linux-hardware.org/?probe=c889f7be59) | Jan 21, 2022 |
| Shuttle       | FB62                        | Desktop     | [01c9cc70b3](https://linux-hardware.org/?probe=01c9cc70b3) | Jan 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [c996d7e988](https://linux-hardware.org/?probe=c996d7e988) | Jan 20, 2022 |
| Lenovo        | ThinkPad W510 431963G       | Notebook    | [6906b181eb](https://linux-hardware.org/?probe=6906b181eb) | Jan 20, 2022 |
| Dell          | Latitude E6410              | Notebook    | [2e43a65524](https://linux-hardware.org/?probe=2e43a65524) | Jan 20, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [9d0aeb7635](https://linux-hardware.org/?probe=9d0aeb7635) | Jan 20, 2022 |
| ASUSTek       | P6T WS PRO                  | Desktop     | [bbc373d97c](https://linux-hardware.org/?probe=bbc373d97c) | Jan 19, 2022 |
| ASUSTek       | P6T WS PRO                  | Desktop     | [011bdd164f](https://linux-hardware.org/?probe=011bdd164f) | Jan 19, 2022 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [b48e7b60cd](https://linux-hardware.org/?probe=b48e7b60cd) | Jan 19, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [ca82eeb3d3](https://linux-hardware.org/?probe=ca82eeb3d3) | Jan 19, 2022 |
| Intel         | NUC11PHBi7 M26151-404       | Mini pc     | [1158cbfeaa](https://linux-hardware.org/?probe=1158cbfeaa) | Jan 18, 2022 |
| MSI           | 880GM-E41                   | Desktop     | [88e5431a81](https://linux-hardware.org/?probe=88e5431a81) | Jan 18, 2022 |
| MSI           | 880GM-E41                   | Desktop     | [49aaf5ccbe](https://linux-hardware.org/?probe=49aaf5ccbe) | Jan 18, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [ce0d7ad7f6](https://linux-hardware.org/?probe=ce0d7ad7f6) | Jan 18, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [0370593223](https://linux-hardware.org/?probe=0370593223) | Jan 18, 2022 |
| Lenovo        | ThinkPad X240 20AMS1S800    | Notebook    | [a168ef0aa5](https://linux-hardware.org/?probe=a168ef0aa5) | Jan 18, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [edc7be1068](https://linux-hardware.org/?probe=edc7be1068) | Jan 18, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [ad25878d8b](https://linux-hardware.org/?probe=ad25878d8b) | Jan 17, 2022 |
| Lenovo        | ThinkPad T495 20NKS0QN0C    | Notebook    | [e9b572998d](https://linux-hardware.org/?probe=e9b572998d) | Jan 17, 2022 |
| HP            | Unknown                     | Notebook    | [f42c9c5b75](https://linux-hardware.org/?probe=f42c9c5b75) | Jan 17, 2022 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [1612c5ca91](https://linux-hardware.org/?probe=1612c5ca91) | Jan 17, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [0f5a776f84](https://linux-hardware.org/?probe=0f5a776f84) | Jan 16, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [e324ae4a05](https://linux-hardware.org/?probe=e324ae4a05) | Jan 16, 2022 |
| Dell          | Latitude E5570              | Notebook    | [5c4c02c6f4](https://linux-hardware.org/?probe=5c4c02c6f4) | Jan 16, 2022 |
| Lenovo        | ThinkPad T460s 20FAS09Y0... | Notebook    | [339ea299c8](https://linux-hardware.org/?probe=339ea299c8) | Jan 16, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [04ad5fb2c1](https://linux-hardware.org/?probe=04ad5fb2c1) | Jan 16, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [dd6c66b4dc](https://linux-hardware.org/?probe=dd6c66b4dc) | Jan 15, 2022 |
| Biostar       | H77MU3                      | Desktop     | [da779dbb31](https://linux-hardware.org/?probe=da779dbb31) | Jan 15, 2022 |
| Lenovo        | ThinkPad T495 20NKS0QN0C    | Notebook    | [7a3312aec2](https://linux-hardware.org/?probe=7a3312aec2) | Jan 15, 2022 |
| MSI           | H61M-P25                    | Desktop     | [3433cb58a1](https://linux-hardware.org/?probe=3433cb58a1) | Jan 14, 2022 |
| HYRICAN_AG    | M550SE/M660SE               | Notebook    | [3097837534](https://linux-hardware.org/?probe=3097837534) | Jan 14, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [7bf06ab6f0](https://linux-hardware.org/?probe=7bf06ab6f0) | Jan 14, 2022 |
| Intel Clie... | LAPBC710                    | Notebook    | [50f8ca3c0e](https://linux-hardware.org/?probe=50f8ca3c0e) | Jan 14, 2022 |
| Intel Clie... | LAPBC710                    | Notebook    | [bff400b353](https://linux-hardware.org/?probe=bff400b353) | Jan 14, 2022 |
| Alienware     | 13 R2                       | Notebook    | [65c1ae9026](https://linux-hardware.org/?probe=65c1ae9026) | Jan 14, 2022 |
| Acer          | Aspire A315-31              | Notebook    | [972630705f](https://linux-hardware.org/?probe=972630705f) | Jan 14, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [edb752adea](https://linux-hardware.org/?probe=edb752adea) | Jan 13, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [eb7e68d366](https://linux-hardware.org/?probe=eb7e68d366) | Jan 13, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [5a816ac2fa](https://linux-hardware.org/?probe=5a816ac2fa) | Jan 13, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [4e45161acc](https://linux-hardware.org/?probe=4e45161acc) | Jan 12, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [771b852db1](https://linux-hardware.org/?probe=771b852db1) | Jan 12, 2022 |
| Dell          | Precision 5510              | Notebook    | [4df6b95a0d](https://linux-hardware.org/?probe=4df6b95a0d) | Jan 11, 2022 |
| ASUSTek       | PN50-E1                     | Mini pc     | [4e0ba9d6d3](https://linux-hardware.org/?probe=4e0ba9d6d3) | Jan 11, 2022 |
| Lenovo        | 374F SDK0R32862 WIN 3258... | Desktop     | [dcd83fe037](https://linux-hardware.org/?probe=dcd83fe037) | Jan 10, 2022 |
| Acer          | Aspire V3-371               | Notebook    | [01a96428e7](https://linux-hardware.org/?probe=01a96428e7) | Jan 10, 2022 |
| ASUSTek       | P8H61-I R2.0                | Desktop     | [5b08de311b](https://linux-hardware.org/?probe=5b08de311b) | Jan 10, 2022 |
| MSI           | A68HM GRENADE               | Desktop     | [0f44471905](https://linux-hardware.org/?probe=0f44471905) | Jan 10, 2022 |
| ASUSTek       | N750JV                      | Notebook    | [35339ffa21](https://linux-hardware.org/?probe=35339ffa21) | Jan 10, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [538509922f](https://linux-hardware.org/?probe=538509922f) | Jan 10, 2022 |
| TUXEDO        | Polaris 15 AMD Gen1         | Notebook    | [4df70f0938](https://linux-hardware.org/?probe=4df70f0938) | Jan 09, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [37d39e8efe](https://linux-hardware.org/?probe=37d39e8efe) | Jan 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [d43bc9ead0](https://linux-hardware.org/?probe=d43bc9ead0) | Jan 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [5cabde7162](https://linux-hardware.org/?probe=5cabde7162) | Jan 08, 2022 |
| MSI           | H61M-P25                    | Desktop     | [5f095c2bf8](https://linux-hardware.org/?probe=5f095c2bf8) | Jan 08, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [401e51bc40](https://linux-hardware.org/?probe=401e51bc40) | Jan 07, 2022 |
| Gigabyte      | P55A-UD3                    | Desktop     | [46878503d2](https://linux-hardware.org/?probe=46878503d2) | Jan 07, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [6be1bf5b86](https://linux-hardware.org/?probe=6be1bf5b86) | Jan 07, 2022 |
| Acer          | Aspire 1510                 | Notebook    | [26c825b4a7](https://linux-hardware.org/?probe=26c825b4a7) | Jan 07, 2022 |
| MSI           | H61M-P25                    | Desktop     | [f5060a86a8](https://linux-hardware.org/?probe=f5060a86a8) | Jan 07, 2022 |
| Dell          | 072T6D A01                  | Server      | [11ddc3d97b](https://linux-hardware.org/?probe=11ddc3d97b) | Jan 06, 2022 |
| Lenovo        | IdeaPad 530S-15IKB 81EV     | Notebook    | [96dd604fa9](https://linux-hardware.org/?probe=96dd604fa9) | Jan 06, 2022 |
| Shuttle       | FB62                        | Desktop     | [704df008d5](https://linux-hardware.org/?probe=704df008d5) | Jan 06, 2022 |
| Shuttle       | FB62                        | Desktop     | [2da02c481d](https://linux-hardware.org/?probe=2da02c481d) | Jan 06, 2022 |
| Packard Be... | EasyNote MZ35               | Notebook    | [63281c8766](https://linux-hardware.org/?probe=63281c8766) | Jan 06, 2022 |
| Packard Be... | EasyNote MZ35               | Notebook    | [205f3bc0b9](https://linux-hardware.org/?probe=205f3bc0b9) | Jan 06, 2022 |
| Dell          | Latitude E6520              | Notebook    | [8c59662d46](https://linux-hardware.org/?probe=8c59662d46) | Jan 06, 2022 |
| Dell          | Latitude E6520              | Notebook    | [6065957c5e](https://linux-hardware.org/?probe=6065957c5e) | Jan 05, 2022 |
| Compaq        | 07E4h                       | Desktop     | [535804dbc6](https://linux-hardware.org/?probe=535804dbc6) | Jan 05, 2022 |
| Supermicro    | C7SIM-Q                     | Desktop     | [e4919133a9](https://linux-hardware.org/?probe=e4919133a9) | Jan 05, 2022 |
| ASUSTek       | TUF Z370-PLUS GAMING        | Desktop     | [54f06dc854](https://linux-hardware.org/?probe=54f06dc854) | Jan 04, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [c804b37a93](https://linux-hardware.org/?probe=c804b37a93) | Jan 04, 2022 |
| MSI           | H61M-P25                    | Desktop     | [3679d16bdb](https://linux-hardware.org/?probe=3679d16bdb) | Jan 04, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [9b8e2862e0](https://linux-hardware.org/?probe=9b8e2862e0) | Jan 04, 2022 |
| Acer          | TravelMate P253             | Notebook    | [90c92c4f35](https://linux-hardware.org/?probe=90c92c4f35) | Jan 04, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [5ce8d98461](https://linux-hardware.org/?probe=5ce8d98461) | Jan 04, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [4020ca9754](https://linux-hardware.org/?probe=4020ca9754) | Jan 04, 2022 |
| MSI           | H61M-P25                    | Desktop     | [004392f0ef](https://linux-hardware.org/?probe=004392f0ef) | Jan 04, 2022 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [7202f73eb4](https://linux-hardware.org/?probe=7202f73eb4) | Jan 03, 2022 |
| Samsung       | 900X3C/900X3D/900X3E/900... | Notebook    | [83036c3a63](https://linux-hardware.org/?probe=83036c3a63) | Jan 03, 2022 |
| Lenovo        | Yoga C940-15IRH 81TE        | Convertible | [1efcfafdfe](https://linux-hardware.org/?probe=1efcfafdfe) | Jan 03, 2022 |
| Acer          | Aspire 7715Z                | Notebook    | [4f79a85c6b](https://linux-hardware.org/?probe=4f79a85c6b) | Jan 03, 2022 |
| MSI           | Z97S SLI Krait Edition      | Desktop     | [abff969a99](https://linux-hardware.org/?probe=abff969a99) | Jan 02, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [7a62214858](https://linux-hardware.org/?probe=7a62214858) | Jan 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [e55162d481](https://linux-hardware.org/?probe=e55162d481) | Jan 02, 2022 |
| Dell          | 0D28YY A03                  | Desktop     | [1eabdb1eec](https://linux-hardware.org/?probe=1eabdb1eec) | Jan 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [ee6ede67e9](https://linux-hardware.org/?probe=ee6ede67e9) | Jan 02, 2022 |
| Samsung       | NC210/NC110                 | Notebook    | [ccee740b06](https://linux-hardware.org/?probe=ccee740b06) | Jan 02, 2022 |
| Dell          | 0D28YY A03                  | Desktop     | [5bdfb337f2](https://linux-hardware.org/?probe=5bdfb337f2) | Jan 02, 2022 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [f288a91383](https://linux-hardware.org/?probe=f288a91383) | Jan 02, 2022 |
| Dell          | Latitude E5470              | Notebook    | [f1623fdbd5](https://linux-hardware.org/?probe=f1623fdbd5) | Jan 02, 2022 |
| HP            | Notebook                    | Notebook    | [42e7ac4065](https://linux-hardware.org/?probe=42e7ac4065) | Jan 02, 2022 |
| Apple         | Mac-F2268DC8                | All in one  | [b87b1d2bcf](https://linux-hardware.org/?probe=b87b1d2bcf) | Jan 02, 2022 |
| HP            | 83E8                        | Desktop     | [c79a0cc45e](https://linux-hardware.org/?probe=c79a0cc45e) | Dec 31, 2021 |
| Samsung       | NC210/NC110                 | Notebook    | [4d26b14130](https://linux-hardware.org/?probe=4d26b14130) | Dec 31, 2021 |
| Samsung       | NC210/NC110                 | Notebook    | [bb92ee12a5](https://linux-hardware.org/?probe=bb92ee12a5) | Dec 31, 2021 |
| ASUSTek       | P9X79 LE                    | Desktop     | [61e605e1d8](https://linux-hardware.org/?probe=61e605e1d8) | Dec 31, 2021 |
| Apple         | Mac-F2268DC8                | All in one  | [90194f839e](https://linux-hardware.org/?probe=90194f839e) | Dec 31, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [02881d7e37](https://linux-hardware.org/?probe=02881d7e37) | Dec 30, 2021 |
| ASRock        | X570M Pro4                  | Desktop     | [18830ebc64](https://linux-hardware.org/?probe=18830ebc64) | Dec 30, 2021 |
| Lenovo        | ThinkPad T460 20FMS80M0C    | Notebook    | [dfdcb1f759](https://linux-hardware.org/?probe=dfdcb1f759) | Dec 29, 2021 |
| Lenovo        | ThinkPad A485 20MU000CMH    | Notebook    | [ec36ac81a4](https://linux-hardware.org/?probe=ec36ac81a4) | Dec 29, 2021 |
| ASRock        | H370M-ITX/ac                | Desktop     | [12dd615663](https://linux-hardware.org/?probe=12dd615663) | Dec 29, 2021 |
| ASUSTek       | Maximus VIII EXTREME        | Desktop     | [ccc49903fd](https://linux-hardware.org/?probe=ccc49903fd) | Dec 28, 2021 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [19ab5f1e89](https://linux-hardware.org/?probe=19ab5f1e89) | Dec 27, 2021 |
| MSI           | Z390-A PRO                  | Desktop     | [b8d518ea38](https://linux-hardware.org/?probe=b8d518ea38) | Dec 27, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [24cecfe4c4](https://linux-hardware.org/?probe=24cecfe4c4) | Dec 26, 2021 |
| HP            | ProBook 6450b               | Notebook    | [4790bd694c](https://linux-hardware.org/?probe=4790bd694c) | Dec 26, 2021 |
| HP            | ProBook 6450b               | Notebook    | [b0439a1f8a](https://linux-hardware.org/?probe=b0439a1f8a) | Dec 26, 2021 |
| Lenovo        | MIIX 510-12IKB 80XE         | Tablet      | [d249085990](https://linux-hardware.org/?probe=d249085990) | Dec 26, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [17cc2bca69](https://linux-hardware.org/?probe=17cc2bca69) | Dec 26, 2021 |
| Acer          | Aspire A715-75G             | Notebook    | [65a1aa570a](https://linux-hardware.org/?probe=65a1aa570a) | Dec 25, 2021 |
| Dell          | Vostro 3560                 | Notebook    | [7bd51b12d6](https://linux-hardware.org/?probe=7bd51b12d6) | Dec 25, 2021 |
| Dell          | Vostro 3560                 | Notebook    | [0929a4f988](https://linux-hardware.org/?probe=0929a4f988) | Dec 25, 2021 |
| Intel         | DG965RY AAD41691-301        | Desktop     | [c2d30af3ce](https://linux-hardware.org/?probe=c2d30af3ce) | Dec 25, 2021 |
| Intel         | DG965RY AAD41691-301        | Desktop     | [586e536e6c](https://linux-hardware.org/?probe=586e536e6c) | Dec 25, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [840f7b0eff](https://linux-hardware.org/?probe=840f7b0eff) | Dec 25, 2021 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [c8a696340f](https://linux-hardware.org/?probe=c8a696340f) | Dec 24, 2021 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [2797b5bd37](https://linux-hardware.org/?probe=2797b5bd37) | Dec 23, 2021 |
| MSI           | 0A90                        | Desktop     | [b08d40599d](https://linux-hardware.org/?probe=b08d40599d) | Dec 23, 2021 |
| Dell          | Inspiron MP061              | Notebook    | [ecf9d462df](https://linux-hardware.org/?probe=ecf9d462df) | Dec 23, 2021 |
| Gigabyte      | H110N-CF                    | Desktop     | [17067982ca](https://linux-hardware.org/?probe=17067982ca) | Dec 23, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d00c0b2ded](https://linux-hardware.org/?probe=d00c0b2ded) | Dec 23, 2021 |
| HP            | EliteBook 745 G3            | Notebook    | [ea071b8d0b](https://linux-hardware.org/?probe=ea071b8d0b) | Dec 23, 2021 |
| HP            | EliteBook 745 G3            | Notebook    | [fd30ba561a](https://linux-hardware.org/?probe=fd30ba561a) | Dec 23, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [f74c2da103](https://linux-hardware.org/?probe=f74c2da103) | Dec 22, 2021 |
| ASRock        | J4105B-ITX                  | Desktop     | [e6b535db39](https://linux-hardware.org/?probe=e6b535db39) | Dec 22, 2021 |
| HP            | 87C3                        | Desktop     | [b9310a3287](https://linux-hardware.org/?probe=b9310a3287) | Dec 22, 2021 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [4a626ea302](https://linux-hardware.org/?probe=4a626ea302) | Dec 22, 2021 |
| ASRock        | Z170 Extreme7+              | Desktop     | [094b6e829a](https://linux-hardware.org/?probe=094b6e829a) | Dec 21, 2021 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [086effe4a8](https://linux-hardware.org/?probe=086effe4a8) | Dec 21, 2021 |
| Acer          | Aspire A715-75G             | Notebook    | [c349552561](https://linux-hardware.org/?probe=c349552561) | Dec 20, 2021 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [7f09e89b0f](https://linux-hardware.org/?probe=7f09e89b0f) | Dec 20, 2021 |
| HP            | 1998                        | Desktop     | [42064cfbfc](https://linux-hardware.org/?probe=42064cfbfc) | Dec 20, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [8986819d3f](https://linux-hardware.org/?probe=8986819d3f) | Dec 19, 2021 |
| ASUSTek       | PRIME Z490M-PLUS            | Desktop     | [4d12856637](https://linux-hardware.org/?probe=4d12856637) | Dec 19, 2021 |
| ASUSTek       | X751LD                      | Notebook    | [2013d9d5d8](https://linux-hardware.org/?probe=2013d9d5d8) | Dec 19, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [b76cc36b22](https://linux-hardware.org/?probe=b76cc36b22) | Dec 19, 2021 |
| ASUSTek       | X751LD                      | Notebook    | [67286f0d11](https://linux-hardware.org/?probe=67286f0d11) | Dec 19, 2021 |
| Acer          | Aspire XC-704               | Desktop     | [6f35b410ae](https://linux-hardware.org/?probe=6f35b410ae) | Dec 19, 2021 |
| Fujitsu       | LIFEBOOK E544               | Notebook    | [e3c52dc6ae](https://linux-hardware.org/?probe=e3c52dc6ae) | Dec 18, 2021 |
| HP            | EliteBook 745 G6            | Notebook    | [7ec5b89a1f](https://linux-hardware.org/?probe=7ec5b89a1f) | Dec 18, 2021 |
| Acer          | EG43M                       | Desktop     | [6f5d9e50df](https://linux-hardware.org/?probe=6f5d9e50df) | Dec 17, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [5627f53d66](https://linux-hardware.org/?probe=5627f53d66) | Dec 17, 2021 |
| MSI           | Z390-A PRO                  | Desktop     | [c1a35b5a0c](https://linux-hardware.org/?probe=c1a35b5a0c) | Dec 17, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [68f7af279e](https://linux-hardware.org/?probe=68f7af279e) | Dec 17, 2021 |
| ASRock        | Z87 Pro3                    | Desktop     | [8e1159b4c7](https://linux-hardware.org/?probe=8e1159b4c7) | Dec 16, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [a42a1e13ab](https://linux-hardware.org/?probe=a42a1e13ab) | Dec 16, 2021 |
| Gigabyte      | EX58-UD5                    | Desktop     | [57e73dd859](https://linux-hardware.org/?probe=57e73dd859) | Dec 16, 2021 |
| Dell          | Latitude D830               | Notebook    | [5c79754a4d](https://linux-hardware.org/?probe=5c79754a4d) | Dec 15, 2021 |
| HP            | ENVY Notebook               | Notebook    | [69b60fabe0](https://linux-hardware.org/?probe=69b60fabe0) | Dec 15, 2021 |
| HP            | ProBook 450 G3              | Notebook    | [d197761676](https://linux-hardware.org/?probe=d197761676) | Dec 15, 2021 |
| Sony          | VGN-FW51JF_H                | Notebook    | [65e7795371](https://linux-hardware.org/?probe=65e7795371) | Dec 15, 2021 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [275bcfce49](https://linux-hardware.org/?probe=275bcfce49) | Dec 15, 2021 |
| Dell          | Inspiron MP061              | Notebook    | [8f57caacb2](https://linux-hardware.org/?probe=8f57caacb2) | Dec 15, 2021 |
| MSI           | B85M-E33                    | Desktop     | [40a459840d](https://linux-hardware.org/?probe=40a459840d) | Dec 15, 2021 |
| HP            | ProBook 6550b               | Notebook    | [c09879cfcd](https://linux-hardware.org/?probe=c09879cfcd) | Dec 15, 2021 |
| Dell          | 0PU052                      | Desktop     | [280cb1ef78](https://linux-hardware.org/?probe=280cb1ef78) | Dec 14, 2021 |
| ASUSTek       | Rampage IV EXTREME          | Desktop     | [6e6b8401d5](https://linux-hardware.org/?probe=6e6b8401d5) | Dec 14, 2021 |
| Dell          | 072T6D A01                  | Server      | [3e58f60e33](https://linux-hardware.org/?probe=3e58f60e33) | Dec 14, 2021 |
| Dell          | Latitude E6410              | Notebook    | [fc321454c3](https://linux-hardware.org/?probe=fc321454c3) | Dec 14, 2021 |
| HP            | 1495                        | Desktop     | [7566d35441](https://linux-hardware.org/?probe=7566d35441) | Dec 13, 2021 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [7370afc8b1](https://linux-hardware.org/?probe=7370afc8b1) | Dec 12, 2021 |
| HP            | ProBook 450 G3              | Notebook    | [54846cdc88](https://linux-hardware.org/?probe=54846cdc88) | Dec 12, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [1f799f28c2](https://linux-hardware.org/?probe=1f799f28c2) | Dec 12, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [da7c19f0b4](https://linux-hardware.org/?probe=da7c19f0b4) | Dec 12, 2021 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [b9eda20029](https://linux-hardware.org/?probe=b9eda20029) | Dec 12, 2021 |
| Lenovo        | ThinkPad E495 20NECTO1WW    | Notebook    | [b34dcf2270](https://linux-hardware.org/?probe=b34dcf2270) | Dec 11, 2021 |
| Dell          | Precision 3561              | Notebook    | [1a93ee047d](https://linux-hardware.org/?probe=1a93ee047d) | Dec 11, 2021 |
| Lenovo        | ThinkPad E495 20NECTO1WW    | Notebook    | [eda70fd30b](https://linux-hardware.org/?probe=eda70fd30b) | Dec 11, 2021 |
| HP            | 304Ah                       | Desktop     | [6d87535158](https://linux-hardware.org/?probe=6d87535158) | Dec 10, 2021 |
| Unknown       | 1.0                         | Desktop     | [884c6fee8a](https://linux-hardware.org/?probe=884c6fee8a) | Dec 10, 2021 |
| HP            | ProBook 470 G3              | Notebook    | [f09340f6d9](https://linux-hardware.org/?probe=f09340f6d9) | Dec 09, 2021 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Desktop     | [bf533d0378](https://linux-hardware.org/?probe=bf533d0378) | Dec 09, 2021 |
| Lenovo        | ThinkPad T510 4384A78       | Notebook    | [2c5d450c67](https://linux-hardware.org/?probe=2c5d450c67) | Dec 08, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [a85a563642](https://linux-hardware.org/?probe=a85a563642) | Dec 08, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [5a2032216b](https://linux-hardware.org/?probe=5a2032216b) | Dec 08, 2021 |
| Toshiba       | Satellite L40               | Notebook    | [e0b79ec8e8](https://linux-hardware.org/?probe=e0b79ec8e8) | Dec 07, 2021 |
| Dell          | Latitude E6320              | Notebook    | [55b3a4ea7f](https://linux-hardware.org/?probe=55b3a4ea7f) | Dec 07, 2021 |
| Fujitsu       | D2990-A3 S26361-D2990-A3    | Desktop     | [b1ff547978](https://linux-hardware.org/?probe=b1ff547978) | Dec 07, 2021 |
| HP            | HDX 16                      | Notebook    | [cf114f9094](https://linux-hardware.org/?probe=cf114f9094) | Dec 07, 2021 |
| Toshiba       | Satellite C850-19Z          | Notebook    | [4fdaf4108a](https://linux-hardware.org/?probe=4fdaf4108a) | Dec 07, 2021 |
| Dell          | Latitude E5420              | Notebook    | [e9fdf365b6](https://linux-hardware.org/?probe=e9fdf365b6) | Dec 07, 2021 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [fba5b9a41b](https://linux-hardware.org/?probe=fba5b9a41b) | Dec 07, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [caaaef312c](https://linux-hardware.org/?probe=caaaef312c) | Dec 06, 2021 |
| Acer          | Aspire 5336                 | Notebook    | [ce9d41eb2f](https://linux-hardware.org/?probe=ce9d41eb2f) | Dec 06, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [f2cf016694](https://linux-hardware.org/?probe=f2cf016694) | Dec 06, 2021 |
| Acer          | Aspire 7715Z                | Notebook    | [8124f61a3f](https://linux-hardware.org/?probe=8124f61a3f) | Dec 06, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [49fe509dd2](https://linux-hardware.org/?probe=49fe509dd2) | Dec 04, 2021 |
| Gigabyte      | Z170X-UD5 TH-CF             | Desktop     | [36879da781](https://linux-hardware.org/?probe=36879da781) | Dec 04, 2021 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [633a8b9f67](https://linux-hardware.org/?probe=633a8b9f67) | Dec 03, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [25a3151fc1](https://linux-hardware.org/?probe=25a3151fc1) | Dec 02, 2021 |
| Toshiba       | Satellite L300              | Notebook    | [1a2930b22b](https://linux-hardware.org/?probe=1a2930b22b) | Dec 02, 2021 |
| HP            | ProBook 450 G3              | Notebook    | [ca49dc0eee](https://linux-hardware.org/?probe=ca49dc0eee) | Dec 02, 2021 |
| HP            | Presario CQ56               | Notebook    | [cc3bb815a9](https://linux-hardware.org/?probe=cc3bb815a9) | Dec 01, 2021 |
| Apple         | MacBookPro7,1               | Notebook    | [976a64dcf0](https://linux-hardware.org/?probe=976a64dcf0) | Dec 01, 2021 |
| Apple         | MacBookPro7,1               | Notebook    | [dae33f2aa5](https://linux-hardware.org/?probe=dae33f2aa5) | Dec 01, 2021 |
| HP            | 0AA4h                       | Desktop     | [f7438f59ac](https://linux-hardware.org/?probe=f7438f59ac) | Dec 01, 2021 |
| Dell          | Inspiron MP061              | Notebook    | [f4d9686e78](https://linux-hardware.org/?probe=f4d9686e78) | Nov 30, 2021 |
| ASUSTek       | ZenBook UX533FN_UX533FN     | Notebook    | [f7103cbd20](https://linux-hardware.org/?probe=f7103cbd20) | Nov 30, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [81e0d1f84c](https://linux-hardware.org/?probe=81e0d1f84c) | Nov 30, 2021 |
| Acer          | Aspire V3-371               | Notebook    | [ae313b5d79](https://linux-hardware.org/?probe=ae313b5d79) | Nov 30, 2021 |
| Gigabyte      | B450M S2H V2                | Desktop     | [63228e3c6f](https://linux-hardware.org/?probe=63228e3c6f) | Nov 30, 2021 |
| ASRock        | H67DE3                      | Desktop     | [d710784470](https://linux-hardware.org/?probe=d710784470) | Nov 30, 2021 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [f219ee63ff](https://linux-hardware.org/?probe=f219ee63ff) | Nov 30, 2021 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [3199d159a4](https://linux-hardware.org/?probe=3199d159a4) | Nov 30, 2021 |
| ASUSTek       | P7P55 LX                    | Desktop     | [fbeb247dbf](https://linux-hardware.org/?probe=fbeb247dbf) | Nov 30, 2021 |
| Acer          | Swift SF314-56              | Notebook    | [6c60445d08](https://linux-hardware.org/?probe=6c60445d08) | Nov 29, 2021 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [afc69583d1](https://linux-hardware.org/?probe=afc69583d1) | Nov 29, 2021 |
| MSI           | Alpha 17 A4DEK              | Notebook    | [6a72e44cf5](https://linux-hardware.org/?probe=6a72e44cf5) | Nov 29, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [c9ecec864f](https://linux-hardware.org/?probe=c9ecec864f) | Nov 29, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [89adc65591](https://linux-hardware.org/?probe=89adc65591) | Nov 29, 2021 |
| ASUSTek       | UN45H                       | Desktop     | [7ef92e91ad](https://linux-hardware.org/?probe=7ef92e91ad) | Nov 29, 2021 |
| Lenovo        | G40-30 80FY                 | Notebook    | [43ff865e00](https://linux-hardware.org/?probe=43ff865e00) | Nov 28, 2021 |
| ASUSTek       | H97M-E                      | Desktop     | [4a9ecb83f8](https://linux-hardware.org/?probe=4a9ecb83f8) | Nov 28, 2021 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [e03e498453](https://linux-hardware.org/?probe=e03e498453) | Nov 28, 2021 |
| Apple         | MacBookPro11,2              | Notebook    | [826ba30f64](https://linux-hardware.org/?probe=826ba30f64) | Nov 28, 2021 |
| Lenovo        | ThinkPad P40 Yoga 20GRS0... | Convertible | [1f9d03992d](https://linux-hardware.org/?probe=1f9d03992d) | Nov 28, 2021 |
| Dell          | G3 3579                     | Notebook    | [26c20a8325](https://linux-hardware.org/?probe=26c20a8325) | Nov 28, 2021 |
| ASUSTek       | X202EP                      | Notebook    | [0ac8fbbbd1](https://linux-hardware.org/?probe=0ac8fbbbd1) | Nov 27, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [5a3c7dac55](https://linux-hardware.org/?probe=5a3c7dac55) | Nov 27, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [c260f22229](https://linux-hardware.org/?probe=c260f22229) | Nov 27, 2021 |
| Gigabyte      | MZBSWIP-SI                  | Desktop     | [e348715c0e](https://linux-hardware.org/?probe=e348715c0e) | Nov 27, 2021 |
| ASUSTek       | K55VD                       | Notebook    | [682d323df2](https://linux-hardware.org/?probe=682d323df2) | Nov 26, 2021 |
| ASUSTek       | K55VD                       | Notebook    | [4d2c0a8906](https://linux-hardware.org/?probe=4d2c0a8906) | Nov 26, 2021 |
| HP            | 0AA8h                       | Desktop     | [1d80d6636e](https://linux-hardware.org/?probe=1d80d6636e) | Nov 26, 2021 |
| Notebook      | PCX0DX                      | Notebook    | [dd551e6aad](https://linux-hardware.org/?probe=dd551e6aad) | Nov 26, 2021 |
| Intel         | NUC6CAYB J26842-405         | Mini pc     | [f9a19f16ad](https://linux-hardware.org/?probe=f9a19f16ad) | Nov 26, 2021 |
| Dell          | 0WG864                      | Desktop     | [0c33b47ccd](https://linux-hardware.org/?probe=0c33b47ccd) | Nov 26, 2021 |
| HP            | EliteBook 2560p             | Notebook    | [94ff8f8214](https://linux-hardware.org/?probe=94ff8f8214) | Nov 26, 2021 |
| HP            | EliteBook x360 1030 G3      | Convertible | [74626859f8](https://linux-hardware.org/?probe=74626859f8) | Nov 25, 2021 |
| Dell          | XPS 15 9510                 | Notebook    | [bf2867279a](https://linux-hardware.org/?probe=bf2867279a) | Nov 25, 2021 |
| Unknown       | 1.0                         | Desktop     | [9587847a87](https://linux-hardware.org/?probe=9587847a87) | Nov 25, 2021 |
| HP            | ZBook Studio G5             | Notebook    | [1fbb0d4bba](https://linux-hardware.org/?probe=1fbb0d4bba) | Nov 25, 2021 |
| Lenovo        | ThinkPad T490 20N2006KMH    | Notebook    | [d4b2302c72](https://linux-hardware.org/?probe=d4b2302c72) | Nov 24, 2021 |
| HP            | EliteBook 850 G3            | Notebook    | [18d1fa0af4](https://linux-hardware.org/?probe=18d1fa0af4) | Nov 24, 2021 |
| Toxic         | GM7MQ8P                     | Notebook    | [deb5cbd490](https://linux-hardware.org/?probe=deb5cbd490) | Nov 24, 2021 |
| Lenovo        | ThinkPad X230 23252FG       | Notebook    | [35508b1562](https://linux-hardware.org/?probe=35508b1562) | Nov 24, 2021 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [a6b3b8877b](https://linux-hardware.org/?probe=a6b3b8877b) | Nov 24, 2021 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [7546b1e030](https://linux-hardware.org/?probe=7546b1e030) | Nov 24, 2021 |
| Acer          | Aspire XC-105               | Desktop     | [84fd6895ba](https://linux-hardware.org/?probe=84fd6895ba) | Nov 23, 2021 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [1bfd5fb612](https://linux-hardware.org/?probe=1bfd5fb612) | Nov 23, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [35063b25d7](https://linux-hardware.org/?probe=35063b25d7) | Nov 23, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [3c3fbf498a](https://linux-hardware.org/?probe=3c3fbf498a) | Nov 23, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [fac36029d0](https://linux-hardware.org/?probe=fac36029d0) | Nov 23, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [01fd26642f](https://linux-hardware.org/?probe=01fd26642f) | Nov 23, 2021 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [4597ebef52](https://linux-hardware.org/?probe=4597ebef52) | Nov 23, 2021 |
| Dell          | Latitude E7240              | Notebook    | [d18ac2e69d](https://linux-hardware.org/?probe=d18ac2e69d) | Nov 22, 2021 |
| Apple         | MacBook3,1                  | Notebook    | [990a15b0b4](https://linux-hardware.org/?probe=990a15b0b4) | Nov 22, 2021 |
| Dell          | Latitude E5570              | Notebook    | [8cf8db7a89](https://linux-hardware.org/?probe=8cf8db7a89) | Nov 21, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [c9ecfca27b](https://linux-hardware.org/?probe=c9ecfca27b) | Nov 21, 2021 |
| HP            | Compaq 6730b (KE717AV)      | Notebook    | [71527b8152](https://linux-hardware.org/?probe=71527b8152) | Nov 21, 2021 |
| Packard Be... | EasyNote TJ75               | Notebook    | [76b8b98ec9](https://linux-hardware.org/?probe=76b8b98ec9) | Nov 21, 2021 |
| Medion        | MS-7728                     | Desktop     | [3968447dc2](https://linux-hardware.org/?probe=3968447dc2) | Nov 21, 2021 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [674bb00d63](https://linux-hardware.org/?probe=674bb00d63) | Nov 21, 2021 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [47908fe107](https://linux-hardware.org/?probe=47908fe107) | Nov 21, 2021 |
| HP            | ProLiant ML150 G6           | Desktop     | [ddb6ba2a2b](https://linux-hardware.org/?probe=ddb6ba2a2b) | Nov 21, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [f8501c9239](https://linux-hardware.org/?probe=f8501c9239) | Nov 21, 2021 |
| HP            | ProLiant ML150 G6           | Desktop     | [734028d2b9](https://linux-hardware.org/?probe=734028d2b9) | Nov 21, 2021 |
| HP            | ProBook x360 11 G1 EE       | Notebook    | [6147da0a48](https://linux-hardware.org/?probe=6147da0a48) | Nov 20, 2021 |
| ASUSTek       | P5K3 Deluxe                 | Desktop     | [be68b07b70](https://linux-hardware.org/?probe=be68b07b70) | Nov 20, 2021 |
| Toshiba       | Satellite C850-19Z          | Notebook    | [38b73bb691](https://linux-hardware.org/?probe=38b73bb691) | Nov 20, 2021 |
| Intel         | NUC7i3BNB J22859-309        | Mini pc     | [3ad13c47bb](https://linux-hardware.org/?probe=3ad13c47bb) | Nov 20, 2021 |
| MSI           | MS-1688                     | Notebook    | [c773cbb1a7](https://linux-hardware.org/?probe=c773cbb1a7) | Nov 19, 2021 |
| Lenovo        | ThinkPad T61 766511G        | Notebook    | [e1c74cc580](https://linux-hardware.org/?probe=e1c74cc580) | Nov 19, 2021 |
| HP            | Pavilion Laptop             | Notebook    | [ab2e04130f](https://linux-hardware.org/?probe=ab2e04130f) | Nov 19, 2021 |
| Lenovo        | ThinkPad T470 20HD000EMH    | Notebook    | [31902cc75f](https://linux-hardware.org/?probe=31902cc75f) | Nov 19, 2021 |
| Dell          | Inspiron 3593               | Notebook    | [0e670dc090](https://linux-hardware.org/?probe=0e670dc090) | Nov 19, 2021 |
| ASUSTek       | P7P55 LX                    | Desktop     | [3c44bbdaeb](https://linux-hardware.org/?probe=3c44bbdaeb) | Nov 19, 2021 |
| Apple         | MacBookPro5,2               | Notebook    | [f98f49bb84](https://linux-hardware.org/?probe=f98f49bb84) | Nov 18, 2021 |
| Dell          | Latitude 7410               | Notebook    | [3efa87284e](https://linux-hardware.org/?probe=3efa87284e) | Nov 18, 2021 |
| Apple         | MacBook3,1                  | Notebook    | [ee6a3c4240](https://linux-hardware.org/?probe=ee6a3c4240) | Nov 18, 2021 |
| Microsoft     | Surface Pro                 | Tablet      | [5f40fb240a](https://linux-hardware.org/?probe=5f40fb240a) | Nov 17, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [33fcefc1b3](https://linux-hardware.org/?probe=33fcefc1b3) | Nov 17, 2021 |
| ASRock        | H55M Pro                    | Desktop     | [174ad8527c](https://linux-hardware.org/?probe=174ad8527c) | Nov 17, 2021 |
| HP            | 0AA8h                       | Desktop     | [5cd5f5de04](https://linux-hardware.org/?probe=5cd5f5de04) | Nov 16, 2021 |
| Intel Clie... | LAPBC710                    | Notebook    | [994e4bac0a](https://linux-hardware.org/?probe=994e4bac0a) | Nov 16, 2021 |
| Notebook      | NH55RGQ                     | Notebook    | [b3cb30c28d](https://linux-hardware.org/?probe=b3cb30c28d) | Nov 16, 2021 |
| Lenovo        | ThinkPad T495s 20QJ000FM... | Notebook    | [b6a64d8dae](https://linux-hardware.org/?probe=b6a64d8dae) | Nov 15, 2021 |
| Acer          | Aspire A715-72G             | Notebook    | [2a2d9fc8f1](https://linux-hardware.org/?probe=2a2d9fc8f1) | Nov 15, 2021 |
| MSI           | 2A9C                        | Desktop     | [80ef0caf18](https://linux-hardware.org/?probe=80ef0caf18) | Nov 15, 2021 |
| MSI           | 2A9C                        | Desktop     | [44e1dcea05](https://linux-hardware.org/?probe=44e1dcea05) | Nov 15, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [691e7450a0](https://linux-hardware.org/?probe=691e7450a0) | Nov 15, 2021 |
| ASUSTek       | P5E3 PRO                    | Desktop     | [b07b0970ae](https://linux-hardware.org/?probe=b07b0970ae) | Nov 15, 2021 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [c202664327](https://linux-hardware.org/?probe=c202664327) | Nov 15, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [ce3c46ffb6](https://linux-hardware.org/?probe=ce3c46ffb6) | Nov 14, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [e6648ee972](https://linux-hardware.org/?probe=e6648ee972) | Nov 14, 2021 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | Desktop     | [79a4be215e](https://linux-hardware.org/?probe=79a4be215e) | Nov 14, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [2070d323c9](https://linux-hardware.org/?probe=2070d323c9) | Nov 13, 2021 |
| Acer          | Aspire VN7-593G             | Notebook    | [9d5442fe37](https://linux-hardware.org/?probe=9d5442fe37) | Nov 13, 2021 |
| Acer          | Aspire XC-105               | Desktop     | [e433def470](https://linux-hardware.org/?probe=e433def470) | Nov 13, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [9e8eab1073](https://linux-hardware.org/?probe=9e8eab1073) | Nov 13, 2021 |
| HP            | 0AACh                       | Desktop     | [31db25eee2](https://linux-hardware.org/?probe=31db25eee2) | Nov 13, 2021 |
| HP            | 0AACh                       | Desktop     | [490587bfd6](https://linux-hardware.org/?probe=490587bfd6) | Nov 13, 2021 |
| SIMPC         | MS-7621                     | Desktop     | [3f67bd227e](https://linux-hardware.org/?probe=3f67bd227e) | Nov 13, 2021 |
| Dell          | Latitude E6220              | Notebook    | [09a75055c9](https://linux-hardware.org/?probe=09a75055c9) | Nov 12, 2021 |
| Lenovo        | ThinkPad E15 20RD004FMH     | Notebook    | [898d6c5381](https://linux-hardware.org/?probe=898d6c5381) | Nov 12, 2021 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [1a9a79dad8](https://linux-hardware.org/?probe=1a9a79dad8) | Nov 12, 2021 |
| Gigabyte      | B85M-HD3                    | Desktop     | [f042aedbd9](https://linux-hardware.org/?probe=f042aedbd9) | Nov 12, 2021 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [482e2e3376](https://linux-hardware.org/?probe=482e2e3376) | Nov 12, 2021 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [1af862be27](https://linux-hardware.org/?probe=1af862be27) | Nov 12, 2021 |
| Dell          | Latitude E6410              | Notebook    | [08fde74c0e](https://linux-hardware.org/?probe=08fde74c0e) | Nov 12, 2021 |
| HP            | Compaq 6710b (KE121ET#AB... | Notebook    | [4fa3fa9834](https://linux-hardware.org/?probe=4fa3fa9834) | Nov 12, 2021 |
| ASUSTek       | X501A                       | Notebook    | [f1eb057027](https://linux-hardware.org/?probe=f1eb057027) | Nov 11, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [79e78d0c90](https://linux-hardware.org/?probe=79e78d0c90) | Nov 11, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [df0cb26378](https://linux-hardware.org/?probe=df0cb26378) | Nov 10, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [4f2ba75be6](https://linux-hardware.org/?probe=4f2ba75be6) | Nov 10, 2021 |
| HP            | Pavilion g6                 | Notebook    | [ed1f976323](https://linux-hardware.org/?probe=ed1f976323) | Nov 10, 2021 |
| Toshiba       | Satellite L300              | Notebook    | [6962924fff](https://linux-hardware.org/?probe=6962924fff) | Nov 10, 2021 |
| ASUSTek       | P5QP18L/T5-P5G41E           | Desktop     | [c64c41d162](https://linux-hardware.org/?probe=c64c41d162) | Nov 10, 2021 |
| Samsung       | R530/R730/R540              | Notebook    | [a9360a0208](https://linux-hardware.org/?probe=a9360a0208) | Nov 09, 2021 |
| Dell          | G3 3779                     | Notebook    | [341c243df9](https://linux-hardware.org/?probe=341c243df9) | Nov 09, 2021 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [8378557eb5](https://linux-hardware.org/?probe=8378557eb5) | Nov 09, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [94b138fb37](https://linux-hardware.org/?probe=94b138fb37) | Nov 09, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [3f47def69d](https://linux-hardware.org/?probe=3f47def69d) | Nov 09, 2021 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | Notebook    | [6d3d2766f2](https://linux-hardware.org/?probe=6d3d2766f2) | Nov 09, 2021 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [2e75320963](https://linux-hardware.org/?probe=2e75320963) | Nov 09, 2021 |
| HP            | Notebook                    | Notebook    | [e254c5c947](https://linux-hardware.org/?probe=e254c5c947) | Nov 08, 2021 |
| Medion        | P8610                       | Notebook    | [122043c04d](https://linux-hardware.org/?probe=122043c04d) | Nov 08, 2021 |
| HP            | 872C                        | Mini pc     | [e4450bb253](https://linux-hardware.org/?probe=e4450bb253) | Nov 08, 2021 |
| Lenovo        | ThinkPad P50 20ENS1L000     | Notebook    | [318b5aea2b](https://linux-hardware.org/?probe=318b5aea2b) | Nov 08, 2021 |
| Lenovo        | ThinkPad E590 20NB005GMH    | Notebook    | [146b572cd0](https://linux-hardware.org/?probe=146b572cd0) | Nov 08, 2021 |
| HP            | Compaq 6710b (KE121ET#AB... | Notebook    | [2eb6ea64c6](https://linux-hardware.org/?probe=2eb6ea64c6) | Nov 08, 2021 |
| ASUSTek       | M51Vr                       | Notebook    | [79b0978619](https://linux-hardware.org/?probe=79b0978619) | Nov 08, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [6a2354e970](https://linux-hardware.org/?probe=6a2354e970) | Nov 07, 2021 |
| Lenovo        | ThinkPad E590 20NB001AMH    | Notebook    | [745ce58b52](https://linux-hardware.org/?probe=745ce58b52) | Nov 07, 2021 |
| Medion        | P8610                       | Notebook    | [4d519680a1](https://linux-hardware.org/?probe=4d519680a1) | Nov 07, 2021 |
| ASRock        | H55M Pro                    | Desktop     | [32ba6b164c](https://linux-hardware.org/?probe=32ba6b164c) | Nov 06, 2021 |
| PC Special... | W94_95_97PU                 | Notebook    | [2c6e08bf5d](https://linux-hardware.org/?probe=2c6e08bf5d) | Nov 06, 2021 |
| HP            | Laptop 15-bw0xx             | Notebook    | [746f64d20b](https://linux-hardware.org/?probe=746f64d20b) | Nov 06, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [72769ff542](https://linux-hardware.org/?probe=72769ff542) | Nov 06, 2021 |
| HP            | Laptop 15-bw0xx             | Notebook    | [245941966f](https://linux-hardware.org/?probe=245941966f) | Nov 06, 2021 |
| HP            | Compaq 6710b (KE121ET#AB... | Notebook    | [5d577f71a4](https://linux-hardware.org/?probe=5d577f71a4) | Nov 06, 2021 |
| HP            | Compaq 6710b (KE121ET#AB... | Notebook    | [c37780e9ad](https://linux-hardware.org/?probe=c37780e9ad) | Nov 06, 2021 |
| ASUSTek       | K53TA                       | Notebook    | [e924b214bc](https://linux-hardware.org/?probe=e924b214bc) | Nov 06, 2021 |
| Dell          | 0NKW6Y A00                  | Desktop     | [82a09e132d](https://linux-hardware.org/?probe=82a09e132d) | Nov 05, 2021 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [25f858c7b1](https://linux-hardware.org/?probe=25f858c7b1) | Nov 05, 2021 |
| Biostar       | H77MU3                      | Desktop     | [620dd98d14](https://linux-hardware.org/?probe=620dd98d14) | Nov 05, 2021 |
| ASUSTek       | G551JM                      | Notebook    | [e4d8d0194f](https://linux-hardware.org/?probe=e4d8d0194f) | Nov 04, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [cd9efb14b2](https://linux-hardware.org/?probe=cd9efb14b2) | Nov 04, 2021 |
| HP            | ProBook 450 G4              | Notebook    | [8a681d718e](https://linux-hardware.org/?probe=8a681d718e) | Nov 04, 2021 |
| Medion        | MS-7646                     | Desktop     | [eb827743e9](https://linux-hardware.org/?probe=eb827743e9) | Nov 04, 2021 |
| Lenovo        | ThinkCentre M70e 0833A29    | Desktop     | [6d1875bdd9](https://linux-hardware.org/?probe=6d1875bdd9) | Nov 04, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [cd291857e2](https://linux-hardware.org/?probe=cd291857e2) | Nov 04, 2021 |
| Lenovo        | IdeaPad Z580                | Notebook    | [6ed854b445](https://linux-hardware.org/?probe=6ed854b445) | Nov 03, 2021 |
| HP            | 3031h                       | Desktop     | [9803321690](https://linux-hardware.org/?probe=9803321690) | Nov 03, 2021 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [56a2cc16cf](https://linux-hardware.org/?probe=56a2cc16cf) | Nov 03, 2021 |
| Medion        | MS-7646                     | Desktop     | [5cf0312f01](https://linux-hardware.org/?probe=5cf0312f01) | Nov 03, 2021 |
| Dell          | Latitude E5440              | Notebook    | [8cc78d0e7a](https://linux-hardware.org/?probe=8cc78d0e7a) | Nov 03, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [c8716ec9a6](https://linux-hardware.org/?probe=c8716ec9a6) | Nov 03, 2021 |
| Intel         | NUC7JYB J67969-403          | Mini pc     | [95a1f9d8fd](https://linux-hardware.org/?probe=95a1f9d8fd) | Nov 02, 2021 |
| Intel         | NUC7JYB J67969-403          | Mini pc     | [2f501cd9fe](https://linux-hardware.org/?probe=2f501cd9fe) | Nov 02, 2021 |
| HP            | ProBook 450 G4              | Notebook    | [933ed05cbc](https://linux-hardware.org/?probe=933ed05cbc) | Nov 02, 2021 |
| Google        | Edgar                       | Notebook    | [1d16a72e5c](https://linux-hardware.org/?probe=1d16a72e5c) | Nov 01, 2021 |
| HP            | Compaq nc6320 (RH569ET#A... | Notebook    | [33a586daf3](https://linux-hardware.org/?probe=33a586daf3) | Nov 01, 2021 |
| HP            | Compaq nc6320 (RH569ET#A... | Notebook    | [9bfece22f2](https://linux-hardware.org/?probe=9bfece22f2) | Nov 01, 2021 |
| Dell          | Latitude 5580               | Notebook    | [d8ac1567c1](https://linux-hardware.org/?probe=d8ac1567c1) | Nov 01, 2021 |
| Lenovo        | ThinkCentre M70e 0833A29    | Desktop     | [e13dd10e78](https://linux-hardware.org/?probe=e13dd10e78) | Oct 31, 2021 |
| HP            | Pavilion g7                 | Notebook    | [fbf77d8c63](https://linux-hardware.org/?probe=fbf77d8c63) | Oct 30, 2021 |
| HP            | Mini 110-3100               | Notebook    | [7312570938](https://linux-hardware.org/?probe=7312570938) | Oct 30, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [cf804488dd](https://linux-hardware.org/?probe=cf804488dd) | Oct 30, 2021 |
| ASUSTek       | M4A87TD EVO                 | Desktop     | [fbcb5d8594](https://linux-hardware.org/?probe=fbcb5d8594) | Oct 29, 2021 |
| Gigabyte      | Z68X-UD7-B3                 | Desktop     | [ab9c12af26](https://linux-hardware.org/?probe=ab9c12af26) | Oct 29, 2021 |
| MSI           | B150M BAZOOKA               | Desktop     | [b396e1c4f4](https://linux-hardware.org/?probe=b396e1c4f4) | Oct 29, 2021 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [72617e5dd9](https://linux-hardware.org/?probe=72617e5dd9) | Oct 29, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [5b10037da5](https://linux-hardware.org/?probe=5b10037da5) | Oct 29, 2021 |
| ASUSTek       | N71Jv                       | Notebook    | [29e3747e17](https://linux-hardware.org/?probe=29e3747e17) | Oct 28, 2021 |
| HP            | ZBook Studio G3             | Notebook    | [b91315ee52](https://linux-hardware.org/?probe=b91315ee52) | Oct 28, 2021 |
| Dell          | 0HHV7N A00                  | Desktop     | [6eba24cf71](https://linux-hardware.org/?probe=6eba24cf71) | Oct 28, 2021 |
| Dell          | 088DT1 A01                  | Desktop     | [287d0004f3](https://linux-hardware.org/?probe=287d0004f3) | Oct 28, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [a7cc3183f2](https://linux-hardware.org/?probe=a7cc3183f2) | Oct 28, 2021 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [6f6e5daf18](https://linux-hardware.org/?probe=6f6e5daf18) | Oct 28, 2021 |
| HP            | ZBook Power G7 Mobile Wo... | Notebook    | [e0d6eafd15](https://linux-hardware.org/?probe=e0d6eafd15) | Oct 28, 2021 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [c7a45f22c5](https://linux-hardware.org/?probe=c7a45f22c5) | Oct 27, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [542c0524de](https://linux-hardware.org/?probe=542c0524de) | Oct 27, 2021 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [9a707e937a](https://linux-hardware.org/?probe=9a707e937a) | Oct 27, 2021 |
| ASRock        | A300M-STX                   | Desktop     | [1fb86737fd](https://linux-hardware.org/?probe=1fb86737fd) | Oct 27, 2021 |
| ASUSTek       | X501A                       | Notebook    | [2e47dd4121](https://linux-hardware.org/?probe=2e47dd4121) | Oct 27, 2021 |
| HP            | 805F                        | Desktop     | [f7bfb95642](https://linux-hardware.org/?probe=f7bfb95642) | Oct 26, 2021 |
| HP            | 84EE 1100                   | All in one  | [225f3ee57b](https://linux-hardware.org/?probe=225f3ee57b) | Oct 26, 2021 |
| MSI           | Z68A-GD55                   | Desktop     | [e83f9dcbbc](https://linux-hardware.org/?probe=e83f9dcbbc) | Oct 25, 2021 |
| Apple         | MacBookPro12,1              | Notebook    | [f69b01435f](https://linux-hardware.org/?probe=f69b01435f) | Oct 25, 2021 |
| ASRock        | H370M-ITX/ac                | Desktop     | [b84ac64f99](https://linux-hardware.org/?probe=b84ac64f99) | Oct 25, 2021 |
| Timi          | A35S                        | Notebook    | [99eff2370b](https://linux-hardware.org/?probe=99eff2370b) | Oct 24, 2021 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [97f8374a85](https://linux-hardware.org/?probe=97f8374a85) | Oct 24, 2021 |
| MSI           | Z77A-GD65                   | Desktop     | [947cdfd30b](https://linux-hardware.org/?probe=947cdfd30b) | Oct 24, 2021 |
| Toshiba       | Satellite C70-B             | Notebook    | [a17b7c3888](https://linux-hardware.org/?probe=a17b7c3888) | Oct 24, 2021 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [d3d69e7587](https://linux-hardware.org/?probe=d3d69e7587) | Oct 24, 2021 |
| Dell          | System XPS 15Z              | Notebook    | [33cec7ae6f](https://linux-hardware.org/?probe=33cec7ae6f) | Oct 24, 2021 |
| Dell          | 0T10XW A00                  | Desktop     | [971b85f5db](https://linux-hardware.org/?probe=971b85f5db) | Oct 23, 2021 |
| ASUSTek       | PN50-E1                     | Mini pc     | [4ba408d68c](https://linux-hardware.org/?probe=4ba408d68c) | Oct 23, 2021 |
| ASUSTek       | Q87M-E                      | Desktop     | [2253d95e90](https://linux-hardware.org/?probe=2253d95e90) | Oct 22, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [994b96d25d](https://linux-hardware.org/?probe=994b96d25d) | Oct 22, 2021 |
| Fujitsu       | LIFEBOOK E544               | Notebook    | [a0197c30db](https://linux-hardware.org/?probe=a0197c30db) | Oct 22, 2021 |
| Lenovo        | ThinkPad T61p 64575KG       | Notebook    | [87aad99434](https://linux-hardware.org/?probe=87aad99434) | Oct 22, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [966d510281](https://linux-hardware.org/?probe=966d510281) | Oct 21, 2021 |
| Lenovo        | ThinkPad W510 431963G       | Notebook    | [ba467258aa](https://linux-hardware.org/?probe=ba467258aa) | Oct 21, 2021 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [627c62ae00](https://linux-hardware.org/?probe=627c62ae00) | Oct 21, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [20be8bd8e7](https://linux-hardware.org/?probe=20be8bd8e7) | Oct 21, 2021 |
| Notebook      | NS50MU                      | Notebook    | [ad8b0e22a7](https://linux-hardware.org/?probe=ad8b0e22a7) | Oct 21, 2021 |
| Medion        | H81H3-EM2 H81EM2W08.309     | Desktop     | [7775a20781](https://linux-hardware.org/?probe=7775a20781) | Oct 20, 2021 |
| HP            | Pavilion 15                 | Notebook    | [a111283a6b](https://linux-hardware.org/?probe=a111283a6b) | Oct 20, 2021 |
| Dell          | System XPS 15Z              | Notebook    | [751ffeefa0](https://linux-hardware.org/?probe=751ffeefa0) | Oct 20, 2021 |
| ASUSTek       | X580VD                      | Notebook    | [aff8edafa4](https://linux-hardware.org/?probe=aff8edafa4) | Oct 20, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [8a6e0ee275](https://linux-hardware.org/?probe=8a6e0ee275) | Oct 19, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [4967676215](https://linux-hardware.org/?probe=4967676215) | Oct 19, 2021 |
| Lenovo        | ThinkPad T590 20N5S4Y100    | Notebook    | [f00be1a69f](https://linux-hardware.org/?probe=f00be1a69f) | Oct 19, 2021 |
| Lenovo        | ThinkPad T510 4384A78       | Notebook    | [a2aee507a3](https://linux-hardware.org/?probe=a2aee507a3) | Oct 19, 2021 |
| Lenovo        | ThinkPad T510 4384A78       | Notebook    | [5a3e03b67e](https://linux-hardware.org/?probe=5a3e03b67e) | Oct 19, 2021 |
| HP            | Presario CQ42               | Notebook    | [d82c04d026](https://linux-hardware.org/?probe=d82c04d026) | Oct 19, 2021 |
| Dell          | 0GXM1W A02                  | Desktop     | [fedcdfcd41](https://linux-hardware.org/?probe=fedcdfcd41) | Oct 19, 2021 |
| Lenovo        | ThinkPad X230 23245NG       | Notebook    | [8daf8f0501](https://linux-hardware.org/?probe=8daf8f0501) | Oct 18, 2021 |
| Matsushita... | CF-30GTSZZAM                | Notebook    | [3678f83bba](https://linux-hardware.org/?probe=3678f83bba) | Oct 18, 2021 |
| Acer          | Extensa 2511                | Notebook    | [d6d3f97221](https://linux-hardware.org/?probe=d6d3f97221) | Oct 17, 2021 |
| ASUSTek       | PRIME H410I-PLUS            | Desktop     | [58f899c8dc](https://linux-hardware.org/?probe=58f899c8dc) | Oct 17, 2021 |
| ASUSTek       | PRIME H410I-PLUS            | Desktop     | [3a9e47a21b](https://linux-hardware.org/?probe=3a9e47a21b) | Oct 17, 2021 |
| Microsoft     | Surface Pro 7               | Tablet      | [7c8422e762](https://linux-hardware.org/?probe=7c8422e762) | Oct 17, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [bdbff8abc8](https://linux-hardware.org/?probe=bdbff8abc8) | Oct 16, 2021 |
| Acer          | Aspire 7715Z                | Notebook    | [d2b159ed70](https://linux-hardware.org/?probe=d2b159ed70) | Oct 16, 2021 |
| ASUSTek       | PRIME A320M-A               | Desktop     | [6b7f927fe2](https://linux-hardware.org/?probe=6b7f927fe2) | Oct 16, 2021 |
| Acer          | Aspire E5-571               | Notebook    | [b967df63ce](https://linux-hardware.org/?probe=b967df63ce) | Oct 15, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [c8741d1225](https://linux-hardware.org/?probe=c8741d1225) | Oct 15, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [626699038a](https://linux-hardware.org/?probe=626699038a) | Oct 15, 2021 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [8c2ed0d838](https://linux-hardware.org/?probe=8c2ed0d838) | Oct 15, 2021 |
| Microsoft     | Surface Pro 3               | Tablet      | [f24eb0ac23](https://linux-hardware.org/?probe=f24eb0ac23) | Oct 15, 2021 |
| HP            | 1906                        | Desktop     | [e1eaae6e47](https://linux-hardware.org/?probe=e1eaae6e47) | Oct 14, 2021 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [e9abe9397f](https://linux-hardware.org/?probe=e9abe9397f) | Oct 14, 2021 |
| Dell          | Latitude 7490               | Notebook    | [790768846e](https://linux-hardware.org/?probe=790768846e) | Oct 14, 2021 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [10fb804abd](https://linux-hardware.org/?probe=10fb804abd) | Oct 13, 2021 |
| Lenovo        | ThinkPad X230 2325DE0       | Notebook    | [991007e92a](https://linux-hardware.org/?probe=991007e92a) | Oct 13, 2021 |
| Toshiba       | Satellite C850-19Z          | Notebook    | [59617db66a](https://linux-hardware.org/?probe=59617db66a) | Oct 13, 2021 |
| Intel         | NUC10i5FNB K61361-306       | Mini pc     | [e4020a0558](https://linux-hardware.org/?probe=e4020a0558) | Oct 12, 2021 |
| ASUSTek       | M5A78L                      | Desktop     | [a027b0f5ba](https://linux-hardware.org/?probe=a027b0f5ba) | Oct 12, 2021 |
| Foxconn       | 2AB1h                       | Desktop     | [6216ce3f5c](https://linux-hardware.org/?probe=6216ce3f5c) | Oct 12, 2021 |
| Dell          | Inspiron 5567               | Notebook    | [e551d622a8](https://linux-hardware.org/?probe=e551d622a8) | Oct 11, 2021 |
| ASUSTek       | M5A78L                      | Desktop     | [071d7e45a0](https://linux-hardware.org/?probe=071d7e45a0) | Oct 11, 2021 |
| ASUSTek       | K75VJ                       | Notebook    | [e460d65395](https://linux-hardware.org/?probe=e460d65395) | Oct 10, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [3e524af836](https://linux-hardware.org/?probe=3e524af836) | Oct 10, 2021 |
| ASUSTek       | Maximus IX FORMULA          | Desktop     | [a6b5188018](https://linux-hardware.org/?probe=a6b5188018) | Oct 09, 2021 |
| ASRock        | H110M-ITX/ac                | Desktop     | [261f3477ea](https://linux-hardware.org/?probe=261f3477ea) | Oct 09, 2021 |
| ASUSTek       | P8P67                       | Desktop     | [271ce3048a](https://linux-hardware.org/?probe=271ce3048a) | Oct 08, 2021 |
| MSI           | GE66 Raider 10UH            | Notebook    | [43c72c2ff3](https://linux-hardware.org/?probe=43c72c2ff3) | Oct 08, 2021 |
| MSI           | GE66 Raider 10UH            | Notebook    | [7994b3449d](https://linux-hardware.org/?probe=7994b3449d) | Oct 08, 2021 |
| Lenovo        | ThinkPad P50 20ENS1L000     | Notebook    | [f8443770b9](https://linux-hardware.org/?probe=f8443770b9) | Oct 08, 2021 |
| Medion        | S17402 MD63000              | Notebook    | [9df17ecabd](https://linux-hardware.org/?probe=9df17ecabd) | Oct 07, 2021 |
| Notebook      | NH5x_NH7x_HHx_HJx_HKx       | Notebook    | [d2088e43b2](https://linux-hardware.org/?probe=d2088e43b2) | Oct 07, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [ae113c0df0](https://linux-hardware.org/?probe=ae113c0df0) | Oct 06, 2021 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [bd9fe373d2](https://linux-hardware.org/?probe=bd9fe373d2) | Oct 06, 2021 |
| Dell          | XPS 13 9305                 | Notebook    | [4be3125675](https://linux-hardware.org/?probe=4be3125675) | Oct 06, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [dc9074514c](https://linux-hardware.org/?probe=dc9074514c) | Oct 06, 2021 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [b7fdcc1fb7](https://linux-hardware.org/?probe=b7fdcc1fb7) | Oct 05, 2021 |
| Toshiba       | Satellite P50-A-12P         | Notebook    | [7730af22ba](https://linux-hardware.org/?probe=7730af22ba) | Oct 05, 2021 |
| Lenovo        | ThinkPad T530 2394CJ9       | Notebook    | [b36a94241d](https://linux-hardware.org/?probe=b36a94241d) | Oct 05, 2021 |
| Dell          | Inspiron 7506 2n1           | Convertible | [dd1daa0074](https://linux-hardware.org/?probe=dd1daa0074) | Oct 05, 2021 |
| Dell          | Studio 1558                 | Notebook    | [0bd515d97a](https://linux-hardware.org/?probe=0bd515d97a) | Oct 05, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [0923a8b728](https://linux-hardware.org/?probe=0923a8b728) | Oct 05, 2021 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [13d7ad71c7](https://linux-hardware.org/?probe=13d7ad71c7) | Oct 05, 2021 |
| Toshiba       | Satellite C70-B             | Notebook    | [2d4b467fdc](https://linux-hardware.org/?probe=2d4b467fdc) | Oct 04, 2021 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [219e5cd0d5](https://linux-hardware.org/?probe=219e5cd0d5) | Oct 04, 2021 |
| HP            | ProBook 450 G3              | Notebook    | [4cadac3f8a](https://linux-hardware.org/?probe=4cadac3f8a) | Oct 04, 2021 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [f34d1166a5](https://linux-hardware.org/?probe=f34d1166a5) | Oct 03, 2021 |
| Acer          | E1-510                      | Notebook    | [5ccb33482f](https://linux-hardware.org/?probe=5ccb33482f) | Oct 03, 2021 |
| ASRock        | AM1B-ITX                    | Desktop     | [6cd53a4eb7](https://linux-hardware.org/?probe=6cd53a4eb7) | Oct 03, 2021 |
| Gigabyte      | H61MA-D3V                   | Desktop     | [275c0aa427](https://linux-hardware.org/?probe=275c0aa427) | Oct 02, 2021 |
| HP            | ENVY Laptop 13-ad0xx        | Notebook    | [a6d1182c1c](https://linux-hardware.org/?probe=a6d1182c1c) | Oct 01, 2021 |
| Notebook      | P7xxTM1                     | Notebook    | [ad788dd7dd](https://linux-hardware.org/?probe=ad788dd7dd) | Oct 01, 2021 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [2a8da86d79](https://linux-hardware.org/?probe=2a8da86d79) | Oct 01, 2021 |
| TrekStor      | Surfbook A13                | Notebook    | [e393d9bc10](https://linux-hardware.org/?probe=e393d9bc10) | Oct 01, 2021 |
| Acer          | Aspire XC-780               | Desktop     | [f723ac396a](https://linux-hardware.org/?probe=f723ac396a) | Oct 01, 2021 |
| Lenovo        | IdeaPad 320-17AST 80XW      | Notebook    | [5dee3aa26b](https://linux-hardware.org/?probe=5dee3aa26b) | Oct 01, 2021 |
| Apple         | MacBookPro15,2              | Notebook    | [a93a313453](https://linux-hardware.org/?probe=a93a313453) | Sep 30, 2021 |
| Lenovo        | ThinkPad X131e 33691J1      | Notebook    | [9d07865058](https://linux-hardware.org/?probe=9d07865058) | Sep 30, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [ee67fb66ed](https://linux-hardware.org/?probe=ee67fb66ed) | Sep 29, 2021 |
| ASUSTek       | UX31A                       | Notebook    | [3a2b9502e1](https://linux-hardware.org/?probe=3a2b9502e1) | Sep 29, 2021 |
| Sony          | VPCSA2FGX                   | Notebook    | [60cfbaebef](https://linux-hardware.org/?probe=60cfbaebef) | Sep 29, 2021 |
| Gigabyte      | B85M-HD3 R4                 | Desktop     | [ab7bf7f0db](https://linux-hardware.org/?probe=ab7bf7f0db) | Sep 29, 2021 |
| ASRock        | B150 Pro4                   | Desktop     | [a949a65588](https://linux-hardware.org/?probe=a949a65588) | Sep 29, 2021 |
| HP            | ProBook 455 G7              | Notebook    | [491cab82de](https://linux-hardware.org/?probe=491cab82de) | Sep 29, 2021 |
| HP            | ProBook 455 G7              | Notebook    | [04ff8f3c32](https://linux-hardware.org/?probe=04ff8f3c32) | Sep 29, 2021 |
| Gigabyte      | Z97-HD3                     | Desktop     | [5f6c245dc5](https://linux-hardware.org/?probe=5f6c245dc5) | Sep 28, 2021 |
| Acer          | Aspire 6530G                | Notebook    | [0cabe05cd9](https://linux-hardware.org/?probe=0cabe05cd9) | Sep 27, 2021 |
| Lenovo        | ThinkPad X131e 33691J1      | Notebook    | [fc55841d61](https://linux-hardware.org/?probe=fc55841d61) | Sep 26, 2021 |
| MSI           | PS63 Modern 8RC             | Notebook    | [91194a3fe1](https://linux-hardware.org/?probe=91194a3fe1) | Sep 26, 2021 |
| Unknown       | Unknown                     | Desktop     | [49df68356d](https://linux-hardware.org/?probe=49df68356d) | Sep 26, 2021 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [82e0f76133](https://linux-hardware.org/?probe=82e0f76133) | Sep 25, 2021 |
| HP            | 0A80h                       | Desktop     | [b939bfa24c](https://linux-hardware.org/?probe=b939bfa24c) | Sep 25, 2021 |
| ASUSTek       | N751JX                      | Notebook    | [fab78e7b72](https://linux-hardware.org/?probe=fab78e7b72) | Sep 25, 2021 |
| Acer          | Aspire V3-771               | Notebook    | [2173e84f13](https://linux-hardware.org/?probe=2173e84f13) | Sep 24, 2021 |
| Acer          | Aspire V3-771               | Notebook    | [2d78661355](https://linux-hardware.org/?probe=2d78661355) | Sep 24, 2021 |
| Acer          | Aspire A515-44G             | Notebook    | [fceda20a86](https://linux-hardware.org/?probe=fceda20a86) | Sep 23, 2021 |
| Acer          | Aspire V3-771               | Notebook    | [6970955a58](https://linux-hardware.org/?probe=6970955a58) | Sep 23, 2021 |
| Lenovo        | ThinkPad W520 42763JU       | Notebook    | [efc15757fc](https://linux-hardware.org/?probe=efc15757fc) | Sep 23, 2021 |
| Dell          | Inspiron 7348               | Notebook    | [0fffa19186](https://linux-hardware.org/?probe=0fffa19186) | Sep 22, 2021 |
| Dell          | Latitude 3189               | Notebook    | [0bf27d0f8e](https://linux-hardware.org/?probe=0bf27d0f8e) | Sep 22, 2021 |
| HP            | 1906                        | Desktop     | [a9117a2b7d](https://linux-hardware.org/?probe=a9117a2b7d) | Sep 22, 2021 |
| Notebook      | NH55RGQ                     | Notebook    | [a3dfc7df90](https://linux-hardware.org/?probe=a3dfc7df90) | Sep 22, 2021 |
| HP            | ZBook Studio G5             | Notebook    | [0f2ad22f4c](https://linux-hardware.org/?probe=0f2ad22f4c) | Sep 22, 2021 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [8d38632cc6](https://linux-hardware.org/?probe=8d38632cc6) | Sep 21, 2021 |
| ASRock        | X99 Extreme11               | Desktop     | [b502d23978](https://linux-hardware.org/?probe=b502d23978) | Sep 21, 2021 |
| HP            | ProLiant ML350 G6           | Desktop     | [d0063b7f93](https://linux-hardware.org/?probe=d0063b7f93) | Sep 21, 2021 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | Desktop     | [ef22f8090a](https://linux-hardware.org/?probe=ef22f8090a) | Sep 20, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [0b68c3f5c3](https://linux-hardware.org/?probe=0b68c3f5c3) | Sep 20, 2021 |
| Google        | Coral                       | Notebook    | [b389cbaa5d](https://linux-hardware.org/?probe=b389cbaa5d) | Sep 20, 2021 |
| ASUSTek       | P5KPL-AM EPU                | Desktop     | [9c0ade7c9c](https://linux-hardware.org/?probe=9c0ade7c9c) | Sep 20, 2021 |
| HP            | Compaq CQ45                 | Notebook    | [87a47d3bc8](https://linux-hardware.org/?probe=87a47d3bc8) | Sep 20, 2021 |
| HP            | ProBook 4510s               | Notebook    | [721b35cbcb](https://linux-hardware.org/?probe=721b35cbcb) | Sep 19, 2021 |
| Notebook      | NL40_50CU                   | Notebook    | [9319323793](https://linux-hardware.org/?probe=9319323793) | Sep 19, 2021 |
| Dell          | Inspiron 1545               | Notebook    | [45b03d16ce](https://linux-hardware.org/?probe=45b03d16ce) | Sep 18, 2021 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [a3bffa63dd](https://linux-hardware.org/?probe=a3bffa63dd) | Sep 18, 2021 |
| ASRock        | FM2A58M-DG3+                | Desktop     | [183fc0dd5e](https://linux-hardware.org/?probe=183fc0dd5e) | Sep 18, 2021 |
| Gigabyte      | GA-E7AUM-DS2H               | Desktop     | [879eb33660](https://linux-hardware.org/?probe=879eb33660) | Sep 18, 2021 |
| HP            | 304Ah                       | Desktop     | [ea9dbc3295](https://linux-hardware.org/?probe=ea9dbc3295) | Sep 18, 2021 |
| ASUSTek       | X202EP                      | Notebook    | [ceb0df45dc](https://linux-hardware.org/?probe=ceb0df45dc) | Sep 18, 2021 |
| HUAWEI        | MACH-WX9                    | Notebook    | [cfa4f26454](https://linux-hardware.org/?probe=cfa4f26454) | Sep 15, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [4d4918a470](https://linux-hardware.org/?probe=4d4918a470) | Sep 15, 2021 |
| Acer          | Aspire V3-571G              | Notebook    | [81ab7840d1](https://linux-hardware.org/?probe=81ab7840d1) | Sep 15, 2021 |
| Gigabyte      | GA-E7AUM-DS2H               | Desktop     | [423826edd0](https://linux-hardware.org/?probe=423826edd0) | Sep 14, 2021 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [65b676f061](https://linux-hardware.org/?probe=65b676f061) | Sep 14, 2021 |
| HP            | 1906                        | Desktop     | [1eb46ff281](https://linux-hardware.org/?probe=1eb46ff281) | Sep 14, 2021 |
| Gigabyte      | GA-E7AUM-DS2H               | Desktop     | [c5801cfce8](https://linux-hardware.org/?probe=c5801cfce8) | Sep 14, 2021 |
| Microsoft     | Surface Pro                 | Tablet      | [814c706a03](https://linux-hardware.org/?probe=814c706a03) | Sep 13, 2021 |
| MSI           | Z68A-GD55                   | Desktop     | [aae29d0847](https://linux-hardware.org/?probe=aae29d0847) | Sep 13, 2021 |
| ASRock        | FM2A58M-DG3+                | Desktop     | [7433bea790](https://linux-hardware.org/?probe=7433bea790) | Sep 13, 2021 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [6928772253](https://linux-hardware.org/?probe=6928772253) | Sep 12, 2021 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [93a0d7ac6a](https://linux-hardware.org/?probe=93a0d7ac6a) | Sep 12, 2021 |
| Acer          | TravelMate 5720             | Notebook    | [4de6ed548e](https://linux-hardware.org/?probe=4de6ed548e) | Sep 12, 2021 |
| HP            | 339A                        | Desktop     | [9284a70a92](https://linux-hardware.org/?probe=9284a70a92) | Sep 12, 2021 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [1a4b83e8cc](https://linux-hardware.org/?probe=1a4b83e8cc) | Sep 12, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [0b9ee7a59d](https://linux-hardware.org/?probe=0b9ee7a59d) | Sep 12, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [800d54370e](https://linux-hardware.org/?probe=800d54370e) | Sep 11, 2021 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [5c407737c5](https://linux-hardware.org/?probe=5c407737c5) | Sep 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [bced59049e](https://linux-hardware.org/?probe=bced59049e) | Sep 11, 2021 |
| Dell          | System XPS L702X            | Notebook    | [8842f899d2](https://linux-hardware.org/?probe=8842f899d2) | Sep 11, 2021 |
| ASUSTek       | N55SF                       | Notebook    | [33fd6d8c8f](https://linux-hardware.org/?probe=33fd6d8c8f) | Sep 11, 2021 |
| ASUSTek       | N55SF                       | Notebook    | [fa33f94b27](https://linux-hardware.org/?probe=fa33f94b27) | Sep 11, 2021 |
| Apple         | MacBookPro16,1              | Notebook    | [c8cc288f90](https://linux-hardware.org/?probe=c8cc288f90) | Sep 10, 2021 |
| HP            | Pavilion x2 Detachable      | Notebook    | [ddcedfc109](https://linux-hardware.org/?probe=ddcedfc109) | Sep 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [a3e329ff30](https://linux-hardware.org/?probe=a3e329ff30) | Sep 09, 2021 |
| HP            | ProBook 4510s               | Notebook    | [b2e4641005](https://linux-hardware.org/?probe=b2e4641005) | Sep 09, 2021 |
| HP            | ZBook 15 G6                 | Notebook    | [77972d0737](https://linux-hardware.org/?probe=77972d0737) | Sep 07, 2021 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [70c214c3b6](https://linux-hardware.org/?probe=70c214c3b6) | Sep 07, 2021 |
| Acer          | Aspire A315-41              | Notebook    | [48a05b1697](https://linux-hardware.org/?probe=48a05b1697) | Sep 07, 2021 |
| ASUSTek       | V-P8H67E                    | Desktop     | [a5eb4302d5](https://linux-hardware.org/?probe=a5eb4302d5) | Sep 06, 2021 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [ce822e1caa](https://linux-hardware.org/?probe=ce822e1caa) | Sep 06, 2021 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [b34b284f99](https://linux-hardware.org/?probe=b34b284f99) | Sep 06, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [46bc533002](https://linux-hardware.org/?probe=46bc533002) | Sep 06, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [e59fb690d7](https://linux-hardware.org/?probe=e59fb690d7) | Sep 06, 2021 |
| HP            | ProBook 450 G3              | Notebook    | [d480a297c7](https://linux-hardware.org/?probe=d480a297c7) | Sep 06, 2021 |
| Packard Be... | EasyNote MH35               | Notebook    | [2b9a87de84](https://linux-hardware.org/?probe=2b9a87de84) | Sep 06, 2021 |
| Packard Be... | EasyNote MH35               | Notebook    | [25ee5fd445](https://linux-hardware.org/?probe=25ee5fd445) | Sep 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [734b8a2cfa](https://linux-hardware.org/?probe=734b8a2cfa) | Sep 05, 2021 |
| Hampoo        | Cherry Trail CR             | Notebook    | [c1a354c2e2](https://linux-hardware.org/?probe=c1a354c2e2) | Sep 03, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [54ddd1baea](https://linux-hardware.org/?probe=54ddd1baea) | Sep 03, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [acc05dc902](https://linux-hardware.org/?probe=acc05dc902) | Sep 03, 2021 |
| Dell          | Latitude 5580               | Notebook    | [2d949d7117](https://linux-hardware.org/?probe=2d949d7117) | Sep 02, 2021 |
| ASUSTek       | N551JX                      | Notebook    | [66e7ade0f9](https://linux-hardware.org/?probe=66e7ade0f9) | Sep 02, 2021 |
| TrekStor      | Primebook P14               | Notebook    | [026e7277ee](https://linux-hardware.org/?probe=026e7277ee) | Sep 02, 2021 |
| Dell          | Studio 1747                 | Notebook    | [8e77a169f4](https://linux-hardware.org/?probe=8e77a169f4) | Sep 02, 2021 |
| Intel         | NUC8CYB J69922-404          | Mini pc     | [d9ac661777](https://linux-hardware.org/?probe=d9ac661777) | Sep 01, 2021 |
| MSI           | Alpha 15 A3DDK              | Notebook    | [37b9634480](https://linux-hardware.org/?probe=37b9634480) | Aug 31, 2021 |
| ASUSTek       | ZenBook Pro 15 UX550GE_U... | Notebook    | [7a407e7543](https://linux-hardware.org/?probe=7a407e7543) | Aug 31, 2021 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | Desktop     | [0c12f5a5a6](https://linux-hardware.org/?probe=0c12f5a5a6) | Aug 31, 2021 |
| Lenovo        | G50-30 80G0                 | Notebook    | [69f5c7f265](https://linux-hardware.org/?probe=69f5c7f265) | Aug 31, 2021 |
| Acer          | Aspire E5-571               | Notebook    | [c9b9067a3e](https://linux-hardware.org/?probe=c9b9067a3e) | Aug 31, 2021 |
| ASUSTek       | ET2321I                     | Desktop     | [5520af0af4](https://linux-hardware.org/?probe=5520af0af4) | Aug 30, 2021 |
| Dell          | Latitude E5570              | Notebook    | [c0e5d1fbdb](https://linux-hardware.org/?probe=c0e5d1fbdb) | Aug 30, 2021 |
| Dell          | Latitude E5570              | Notebook    | [bcc83fad01](https://linux-hardware.org/?probe=bcc83fad01) | Aug 30, 2021 |
| ASUSTek       | N55SF                       | Notebook    | [37589f5a69](https://linux-hardware.org/?probe=37589f5a69) | Aug 29, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [126a68c966](https://linux-hardware.org/?probe=126a68c966) | Aug 29, 2021 |
| ASUSTek       | ZenBook Pro 15 UX550GE_U... | Notebook    | [e9eb54512d](https://linux-hardware.org/?probe=e9eb54512d) | Aug 29, 2021 |
| ASUSTek       | K56CB                       | Notebook    | [1a44fc7e8f](https://linux-hardware.org/?probe=1a44fc7e8f) | Aug 29, 2021 |
| ASUSTek       | 1201HA                      | Notebook    | [eadb8752c9](https://linux-hardware.org/?probe=eadb8752c9) | Aug 28, 2021 |
| HP            | 815A                        | Mini pc     | [7d65a83025](https://linux-hardware.org/?probe=7d65a83025) | Aug 28, 2021 |
| HP            | 815A                        | Mini pc     | [538655c4f2](https://linux-hardware.org/?probe=538655c4f2) | Aug 28, 2021 |
| TUXEDO        | Unknown                     | Notebook    | [d72b243802](https://linux-hardware.org/?probe=d72b243802) | Aug 27, 2021 |
| Acer          | TravelMate 7750G            | Notebook    | [8d3d35021f](https://linux-hardware.org/?probe=8d3d35021f) | Aug 27, 2021 |
| Google        | Careena                     | Notebook    | [ab1bafda25](https://linux-hardware.org/?probe=ab1bafda25) | Aug 27, 2021 |
| Google        | Careena                     | Notebook    | [c71e6267cb](https://linux-hardware.org/?probe=c71e6267cb) | Aug 27, 2021 |
| Notebook      | N85_N87,HJ,HJ1,HK1          | Notebook    | [e7d4558643](https://linux-hardware.org/?probe=e7d4558643) | Aug 26, 2021 |
| Medion        | MS-7646                     | Desktop     | [51b5a18244](https://linux-hardware.org/?probe=51b5a18244) | Aug 26, 2021 |
| Gigabyte      | Z68X-UD3H-B3                | Desktop     | [c55ae2cdce](https://linux-hardware.org/?probe=c55ae2cdce) | Aug 26, 2021 |
| Packard Be... | FMP55                       | Desktop     | [ecaccf06ea](https://linux-hardware.org/?probe=ecaccf06ea) | Aug 26, 2021 |
| HP            | 815A                        | Mini pc     | [bcd0bfb481](https://linux-hardware.org/?probe=bcd0bfb481) | Aug 26, 2021 |
| Acer          | Swift SF514-55T             | Notebook    | [82e21775f5](https://linux-hardware.org/?probe=82e21775f5) | Aug 26, 2021 |
| HP            | Pavilion dv2000 (RD665EA... | Notebook    | [3b6dfaf6db](https://linux-hardware.org/?probe=3b6dfaf6db) | Aug 25, 2021 |
| Acer          | Aspire X3990                | Desktop     | [7873e0e2e6](https://linux-hardware.org/?probe=7873e0e2e6) | Aug 24, 2021 |
| HUAWEI        | MACH-WX9                    | Notebook    | [ffd49f5a01](https://linux-hardware.org/?probe=ffd49f5a01) | Aug 23, 2021 |
| MSI           | H87-G41 PC Mate             | Desktop     | [5983efaa09](https://linux-hardware.org/?probe=5983efaa09) | Aug 23, 2021 |
| ASRock        | H370M-ITX/ac                | Desktop     | [d967006286](https://linux-hardware.org/?probe=d967006286) | Aug 23, 2021 |
| ASRock        | H370M-ITX/ac                | Desktop     | [2459d35480](https://linux-hardware.org/?probe=2459d35480) | Aug 23, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [be4febc53b](https://linux-hardware.org/?probe=be4febc53b) | Aug 23, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [6eb4797b58](https://linux-hardware.org/?probe=6eb4797b58) | Aug 23, 2021 |
| Acer          | Aspire V3-771               | Notebook    | [86a90d5316](https://linux-hardware.org/?probe=86a90d5316) | Aug 23, 2021 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [983a472563](https://linux-hardware.org/?probe=983a472563) | Aug 22, 2021 |
| Lenovo        | G50-30 80G0                 | Notebook    | [d9a5ac6cc0](https://linux-hardware.org/?probe=d9a5ac6cc0) | Aug 22, 2021 |
| HP            | EliteBook 850 G2            | Notebook    | [89bfd52b3d](https://linux-hardware.org/?probe=89bfd52b3d) | Aug 22, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [a6f2aa42c9](https://linux-hardware.org/?probe=a6f2aa42c9) | Aug 22, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [03826ea2dc](https://linux-hardware.org/?probe=03826ea2dc) | Aug 22, 2021 |
| HP            | EliteBook 850 G2            | Notebook    | [a82576e8e2](https://linux-hardware.org/?probe=a82576e8e2) | Aug 22, 2021 |
| ASUSTek       | M51Sn                       | Notebook    | [5acb8c28ad](https://linux-hardware.org/?probe=5acb8c28ad) | Aug 21, 2021 |
| ASUSTek       | M51Sn                       | Notebook    | [4a85a76b94](https://linux-hardware.org/?probe=4a85a76b94) | Aug 21, 2021 |
| Acer          | Aspire 5680                 | Notebook    | [45c723fae8](https://linux-hardware.org/?probe=45c723fae8) | Aug 21, 2021 |
| ASUSTek       | X580VD                      | Notebook    | [5df36dba53](https://linux-hardware.org/?probe=5df36dba53) | Aug 21, 2021 |
| ASUSTek       | X501A                       | Notebook    | [e9784e8db3](https://linux-hardware.org/?probe=e9784e8db3) | Aug 21, 2021 |
| Dell          | Inspiron 5491 2n1           | Convertible | [e85575b823](https://linux-hardware.org/?probe=e85575b823) | Aug 21, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [c673203c6b](https://linux-hardware.org/?probe=c673203c6b) | Aug 20, 2021 |
| Dell          | System XPS L702X            | Notebook    | [32448925cb](https://linux-hardware.org/?probe=32448925cb) | Aug 20, 2021 |
| Dell          | System XPS L702X            | Notebook    | [93f7edad9b](https://linux-hardware.org/?probe=93f7edad9b) | Aug 20, 2021 |
| ASRock        | B450 Steel Legend           | Desktop     | [4819fabe04](https://linux-hardware.org/?probe=4819fabe04) | Aug 20, 2021 |
| ASUSTek       | P6X58D-E                    | Desktop     | [db1ef28e92](https://linux-hardware.org/?probe=db1ef28e92) | Aug 20, 2021 |
| Acer          | Aspire V3-771               | Notebook    | [c47071ce0b](https://linux-hardware.org/?probe=c47071ce0b) | Aug 20, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [b708963e17](https://linux-hardware.org/?probe=b708963e17) | Aug 20, 2021 |
| Lenovo        | ThinkPad W530 2447A55       | Notebook    | [bb1dabf95c](https://linux-hardware.org/?probe=bb1dabf95c) | Aug 19, 2021 |
| ASRock        | H310CM-ITX/ac               | Desktop     | [894b4aa792](https://linux-hardware.org/?probe=894b4aa792) | Aug 19, 2021 |
| HP            | Mini 110-3100               | Notebook    | [9e1a66a2c0](https://linux-hardware.org/?probe=9e1a66a2c0) | Aug 19, 2021 |
| ASRock        | X399 Professional Gaming    | Desktop     | [30e51ec830](https://linux-hardware.org/?probe=30e51ec830) | Aug 19, 2021 |
| Notebook      | NS50MU                      | Notebook    | [4131fc9389](https://linux-hardware.org/?probe=4131fc9389) | Aug 19, 2021 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [d789709af4](https://linux-hardware.org/?probe=d789709af4) | Aug 19, 2021 |
| Apple         | MacBookPro8,3               | Notebook    | [367d598698](https://linux-hardware.org/?probe=367d598698) | Aug 18, 2021 |
| HP            | 304Ah                       | Desktop     | [047d1b0887](https://linux-hardware.org/?probe=047d1b0887) | Aug 18, 2021 |
| MSI           | GP62M 7RDX                  | Notebook    | [c82adc38b2](https://linux-hardware.org/?probe=c82adc38b2) | Aug 18, 2021 |
| ASUSTek       | E200HA                      | Notebook    | [d54a711f31](https://linux-hardware.org/?probe=d54a711f31) | Aug 18, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [635d8e55e7](https://linux-hardware.org/?probe=635d8e55e7) | Aug 17, 2021 |
| Acer          | Aspire TC-605               | Desktop     | [b8346987e3](https://linux-hardware.org/?probe=b8346987e3) | Aug 17, 2021 |
| ASUSTek       | UX305CA                     | Notebook    | [9b7ea1199f](https://linux-hardware.org/?probe=9b7ea1199f) | Aug 16, 2021 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [87cd3e3c9e](https://linux-hardware.org/?probe=87cd3e3c9e) | Aug 16, 2021 |
| Acer          | Aspire TC-605               | Desktop     | [2b22f501e9](https://linux-hardware.org/?probe=2b22f501e9) | Aug 16, 2021 |
| Intel         | NUC7i5BNB J31144-305        | Mini pc     | [1c581950df](https://linux-hardware.org/?probe=1c581950df) | Aug 16, 2021 |
| AMD           | AOPW-PLUS                   | Server      | [58771d090d](https://linux-hardware.org/?probe=58771d090d) | Aug 16, 2021 |
| Acer          | Aspire TC-605               | Desktop     | [a358ccd34e](https://linux-hardware.org/?probe=a358ccd34e) | Aug 16, 2021 |
| AMD           | AOPW-PLUS                   | Server      | [a8a8e3e52c](https://linux-hardware.org/?probe=a8a8e3e52c) | Aug 16, 2021 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [83e29d3882](https://linux-hardware.org/?probe=83e29d3882) | Aug 16, 2021 |
| Microsoft     | Surface Pro                 | Tablet      | [31c30e5c1f](https://linux-hardware.org/?probe=31c30e5c1f) | Aug 15, 2021 |
| HP            | 0AA8h                       | Desktop     | [d9a8fd3722](https://linux-hardware.org/?probe=d9a8fd3722) | Aug 15, 2021 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [66ff9d7471](https://linux-hardware.org/?probe=66ff9d7471) | Aug 15, 2021 |
| HP            | 3396                        | Desktop     | [d30572a124](https://linux-hardware.org/?probe=d30572a124) | Aug 14, 2021 |
| ASUSTek       | X580VD                      | Notebook    | [4a86f48291](https://linux-hardware.org/?probe=4a86f48291) | Aug 14, 2021 |
| MSI           | B350M MORTAR ARCTIC         | Desktop     | [944cd264e8](https://linux-hardware.org/?probe=944cd264e8) | Aug 13, 2021 |
| Medion        | Z370H4-EM                   | Desktop     | [3561e67663](https://linux-hardware.org/?probe=3561e67663) | Aug 13, 2021 |
| ASUSTek       | Z170-PRO                    | Desktop     | [7f9b5606a5](https://linux-hardware.org/?probe=7f9b5606a5) | Aug 13, 2021 |
| MSI           | Alpha 15 A3DDK              | Notebook    | [569059c4cd](https://linux-hardware.org/?probe=569059c4cd) | Aug 12, 2021 |
| ASUSTek       | X580VD                      | Notebook    | [aeae754f0f](https://linux-hardware.org/?probe=aeae754f0f) | Aug 12, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [897b41af3b](https://linux-hardware.org/?probe=897b41af3b) | Aug 11, 2021 |
| Acer          | Aspire 5680                 | Notebook    | [8889a2924f](https://linux-hardware.org/?probe=8889a2924f) | Aug 10, 2021 |
| Medion        | H110H4-EM2                  | Desktop     | [f4e01958e5](https://linux-hardware.org/?probe=f4e01958e5) | Aug 10, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [4aeef8ef33](https://linux-hardware.org/?probe=4aeef8ef33) | Aug 10, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [d74d9e37ce](https://linux-hardware.org/?probe=d74d9e37ce) | Aug 10, 2021 |
| Notebook      | NH55RGQ                     | Notebook    | [985e447ff5](https://linux-hardware.org/?probe=985e447ff5) | Aug 09, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [48f2b29fbb](https://linux-hardware.org/?probe=48f2b29fbb) | Aug 08, 2021 |
| ASUSTek       | ZenBook 13 UX331FN_UX331... | Notebook    | [fe9a44853c](https://linux-hardware.org/?probe=fe9a44853c) | Aug 08, 2021 |
| Lenovo        | ThinkPad T480 20L6SA5Q00    | Notebook    | [5459bf7337](https://linux-hardware.org/?probe=5459bf7337) | Aug 08, 2021 |
| Lenovo        | ThinkCentre M70e 0833A29    | Desktop     | [b4fe0907aa](https://linux-hardware.org/?probe=b4fe0907aa) | Aug 08, 2021 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [0eafaadf13](https://linux-hardware.org/?probe=0eafaadf13) | Aug 07, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [c64960a834](https://linux-hardware.org/?probe=c64960a834) | Aug 07, 2021 |
| ASUSTek       | TUF Z370-PLUS GAMING        | Desktop     | [80c7711147](https://linux-hardware.org/?probe=80c7711147) | Aug 07, 2021 |
| Toshiba       | Satellite A300              | Notebook    | [227c27dda2](https://linux-hardware.org/?probe=227c27dda2) | Aug 07, 2021 |
| Toshiba       | Satellite A300              | Notebook    | [2d36d2e641](https://linux-hardware.org/?probe=2d36d2e641) | Aug 07, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [dd86f5be32](https://linux-hardware.org/?probe=dd86f5be32) | Aug 06, 2021 |
| Lenovo        | ThinkCentre M70e 0833A29    | Desktop     | [a053325efe](https://linux-hardware.org/?probe=a053325efe) | Aug 06, 2021 |
| ASUSTek       | G551JM                      | Notebook    | [78ce8eae1b](https://linux-hardware.org/?probe=78ce8eae1b) | Aug 06, 2021 |
| Acer          | Aspire 5310                 | Notebook    | [7cfa18c731](https://linux-hardware.org/?probe=7cfa18c731) | Aug 06, 2021 |
| Lenovo        | ThinkCentre M70e 0833A29    | Desktop     | [2415e3e33f](https://linux-hardware.org/?probe=2415e3e33f) | Aug 06, 2021 |
| Acer          | Aspire E5-575               | Notebook    | [9d4f584337](https://linux-hardware.org/?probe=9d4f584337) | Aug 06, 2021 |
| Notebook      | PCX0DX                      | Notebook    | [fe9c787f69](https://linux-hardware.org/?probe=fe9c787f69) | Aug 06, 2021 |
| HKC           | Y11CC                       | Notebook    | [a8e149ef22](https://linux-hardware.org/?probe=a8e149ef22) | Aug 05, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [fc6a3dd16d](https://linux-hardware.org/?probe=fc6a3dd16d) | Aug 05, 2021 |
| Lenovo        | ThinkPad Edge E535 32608... | Notebook    | [28ec8ce819](https://linux-hardware.org/?probe=28ec8ce819) | Aug 04, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [05c1703574](https://linux-hardware.org/?probe=05c1703574) | Aug 03, 2021 |
| Acer          | Veriton L4610G              | Desktop     | [8f81cbc969](https://linux-hardware.org/?probe=8f81cbc969) | Aug 02, 2021 |
| Intel         | DH87RL AAG74240-403         | Desktop     | [ec1970f896](https://linux-hardware.org/?probe=ec1970f896) | Aug 02, 2021 |
| ASUSTek       | PRIME B350M-K               | Desktop     | [b195a48138](https://linux-hardware.org/?probe=b195a48138) | Aug 02, 2021 |
| ASUSTek       | GL553VD                     | Notebook    | [67a5dfd8d6](https://linux-hardware.org/?probe=67a5dfd8d6) | Aug 02, 2021 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [cc58c27c6f](https://linux-hardware.org/?probe=cc58c27c6f) | Aug 02, 2021 |
| Acer          | Mantasta                    | Notebook    | [ae5999001a](https://linux-hardware.org/?probe=ae5999001a) | Aug 02, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [faf304d157](https://linux-hardware.org/?probe=faf304d157) | Aug 02, 2021 |
| Acer          | Aspire V3-571G              | Notebook    | [8f049503c9](https://linux-hardware.org/?probe=8f049503c9) | Aug 01, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [3577610ea4](https://linux-hardware.org/?probe=3577610ea4) | Aug 01, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [8b4aa2f705](https://linux-hardware.org/?probe=8b4aa2f705) | Jul 31, 2021 |
| MSI           | Z97 GAMING 3                | Desktop     | [35871e8f66](https://linux-hardware.org/?probe=35871e8f66) | Jul 31, 2021 |
| ASUSTek       | TUF B350M-PLUS GAMING       | Desktop     | [6e3b595fb5](https://linux-hardware.org/?probe=6e3b595fb5) | Jul 31, 2021 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [60f065b770](https://linux-hardware.org/?probe=60f065b770) | Jul 31, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [eafe3a403f](https://linux-hardware.org/?probe=eafe3a403f) | Jul 30, 2021 |
| Lenovo        | G710 20252                  | Notebook    | [225bbab28e](https://linux-hardware.org/?probe=225bbab28e) | Jul 30, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [fb839f1401](https://linux-hardware.org/?probe=fb839f1401) | Jul 30, 2021 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | Notebook    | [ba1ddda65a](https://linux-hardware.org/?probe=ba1ddda65a) | Jul 29, 2021 |
| MSI           | GE72 2QE                    | Notebook    | [899dfe320b](https://linux-hardware.org/?probe=899dfe320b) | Jul 29, 2021 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [ed7394c65a](https://linux-hardware.org/?probe=ed7394c65a) | Jul 29, 2021 |
| Dell          | 0J3C2F A02                  | Desktop     | [c41a93deb8](https://linux-hardware.org/?probe=c41a93deb8) | Jul 29, 2021 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [c55a385620](https://linux-hardware.org/?probe=c55a385620) | Jul 28, 2021 |
| Apple         | MacBookPro11,2              | Notebook    | [700c8de7a9](https://linux-hardware.org/?probe=700c8de7a9) | Jul 28, 2021 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [50ebb9f152](https://linux-hardware.org/?probe=50ebb9f152) | Jul 28, 2021 |
| Gigabyte      | X570 GAMING X               | Desktop     | [71ec66a230](https://linux-hardware.org/?probe=71ec66a230) | Jul 28, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [c027708276](https://linux-hardware.org/?probe=c027708276) | Jul 28, 2021 |
| Lenovo        | ThinkPad T490 20RYCTO1WW    | Notebook    | [60c16ed267](https://linux-hardware.org/?probe=60c16ed267) | Jul 28, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [265ab10b75](https://linux-hardware.org/?probe=265ab10b75) | Jul 27, 2021 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [a7813af9da](https://linux-hardware.org/?probe=a7813af9da) | Jul 27, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d84cc38785](https://linux-hardware.org/?probe=d84cc38785) | Jul 27, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [0ccf971558](https://linux-hardware.org/?probe=0ccf971558) | Jul 26, 2021 |
| ASUSTek       | X75A                        | Notebook    | [59d886e9e2](https://linux-hardware.org/?probe=59d886e9e2) | Jul 26, 2021 |
| Lenovo        | G710 20252                  | Notebook    | [508a289100](https://linux-hardware.org/?probe=508a289100) | Jul 26, 2021 |
| Apple         | MacBookPro11,2              | Notebook    | [6682bf2673](https://linux-hardware.org/?probe=6682bf2673) | Jul 26, 2021 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | Notebook    | [b56b5cfff2](https://linux-hardware.org/?probe=b56b5cfff2) | Jul 26, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [0207d45fee](https://linux-hardware.org/?probe=0207d45fee) | Jul 26, 2021 |
| HP            | EliteBook 8440p             | Notebook    | [c703cf93ed](https://linux-hardware.org/?probe=c703cf93ed) | Jul 25, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [a085cda70b](https://linux-hardware.org/?probe=a085cda70b) | Jul 25, 2021 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | Notebook    | [26ab6b470a](https://linux-hardware.org/?probe=26ab6b470a) | Jul 25, 2021 |
| HP            | ProBook x360 11 G1 EE       | Notebook    | [90aeea53cc](https://linux-hardware.org/?probe=90aeea53cc) | Jul 25, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [a1a8e51991](https://linux-hardware.org/?probe=a1a8e51991) | Jul 25, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [1d35172085](https://linux-hardware.org/?probe=1d35172085) | Jul 25, 2021 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [b8a2299d30](https://linux-hardware.org/?probe=b8a2299d30) | Jul 25, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [93b1f77c92](https://linux-hardware.org/?probe=93b1f77c92) | Jul 25, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [722792ec34](https://linux-hardware.org/?probe=722792ec34) | Jul 25, 2021 |
| MSI           | Z170A TOMAHAWK              | Desktop     | [a3022fab56](https://linux-hardware.org/?probe=a3022fab56) | Jul 25, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [f22f34ea9a](https://linux-hardware.org/?probe=f22f34ea9a) | Jul 25, 2021 |
| Panasonic     | CF-AX2LDCZMF                | Notebook    | [31feab61fe](https://linux-hardware.org/?probe=31feab61fe) | Jul 25, 2021 |
| Fujitsu       | LIFEBOOK E751               | Notebook    | [8c1a8a17dc](https://linux-hardware.org/?probe=8c1a8a17dc) | Jul 24, 2021 |
| Lenovo        | G710 20252                  | Notebook    | [70a2143938](https://linux-hardware.org/?probe=70a2143938) | Jul 24, 2021 |
| Acer          | Veriton EN76G V:1.2         | Desktop     | [a1cf4c4535](https://linux-hardware.org/?probe=a1cf4c4535) | Jul 24, 2021 |
| Acer          | Veriton EN76G V:1.2         | Desktop     | [505f1008b9](https://linux-hardware.org/?probe=505f1008b9) | Jul 24, 2021 |
| Intel         | NUC8BEB J72693-303          | Mini pc     | [596eea9169](https://linux-hardware.org/?probe=596eea9169) | Jul 24, 2021 |
| ASRock        | X99 Extreme11               | Desktop     | [cdb84a3960](https://linux-hardware.org/?probe=cdb84a3960) | Jul 24, 2021 |
| Medion        | Unknown                     | Notebook    | [c9b56ed29d](https://linux-hardware.org/?probe=c9b56ed29d) | Jul 23, 2021 |
| Intel         | DG41TY AAE47335-300         | Desktop     | [1f0237b627](https://linux-hardware.org/?probe=1f0237b627) | Jul 23, 2021 |
| Acer          | Aspire E1-572G              | Notebook    | [8532638f35](https://linux-hardware.org/?probe=8532638f35) | Jul 23, 2021 |
| Acer          | WMCP78M                     | Desktop     | [591c077e28](https://linux-hardware.org/?probe=591c077e28) | Jul 22, 2021 |
| HP            | EliteBook 830 G6            | Notebook    | [cdeb3f5272](https://linux-hardware.org/?probe=cdeb3f5272) | Jul 21, 2021 |
| ASUSTek       | K52JT                       | Notebook    | [243cac5745](https://linux-hardware.org/?probe=243cac5745) | Jul 20, 2021 |
| MAXSUN        | MS-A10 4600 Quad            | Desktop     | [18d7ee985d](https://linux-hardware.org/?probe=18d7ee985d) | Jul 20, 2021 |
| Acer          | Aspire E1-572G              | Notebook    | [5c3b7994ad](https://linux-hardware.org/?probe=5c3b7994ad) | Jul 20, 2021 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [70ca44751b](https://linux-hardware.org/?probe=70ca44751b) | Jul 19, 2021 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [9d9600aa00](https://linux-hardware.org/?probe=9d9600aa00) | Jul 19, 2021 |
| Gigabyte      | Z490 GAMING X               | Desktop     | [a540fa2f59](https://linux-hardware.org/?probe=a540fa2f59) | Jul 19, 2021 |
| ASUSTek       | P5Q                         | Desktop     | [3f95acd934](https://linux-hardware.org/?probe=3f95acd934) | Jul 19, 2021 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [1b699bf875](https://linux-hardware.org/?probe=1b699bf875) | Jul 19, 2021 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [f8767723e4](https://linux-hardware.org/?probe=f8767723e4) | Jul 18, 2021 |
| Intel         | NUC8BEB J72693-308          | Mini pc     | [304db19f25](https://linux-hardware.org/?probe=304db19f25) | Jul 18, 2021 |
| Dell          | 0M863N A00                  | Desktop     | [3d05e8db4a](https://linux-hardware.org/?probe=3d05e8db4a) | Jul 18, 2021 |
| Unknown       | Unknown                     | Soc         | [944b172397](https://linux-hardware.org/?probe=944b172397) | Jul 18, 2021 |
| HP            | EliteBook 2560p             | Notebook    | [4dee6aa64b](https://linux-hardware.org/?probe=4dee6aa64b) | Jul 17, 2021 |
| HP            | EliteBook 2560p             | Notebook    | [b1b419e395](https://linux-hardware.org/?probe=b1b419e395) | Jul 17, 2021 |
| MSI           | Katana GF66 11UC            | Notebook    | [3d71bcfe22](https://linux-hardware.org/?probe=3d71bcfe22) | Jul 16, 2021 |
| MSI           | CSM-H81M-P32                | Desktop     | [bb1a577dcb](https://linux-hardware.org/?probe=bb1a577dcb) | Jul 16, 2021 |
| Dell          | G3 3590                     | Notebook    | [5526842a03](https://linux-hardware.org/?probe=5526842a03) | Jul 16, 2021 |
| ASRock        | Z370 Extreme4               | Desktop     | [2bb85ea1fa](https://linux-hardware.org/?probe=2bb85ea1fa) | Jul 16, 2021 |
| Acer          | Swift SF314-55              | Notebook    | [1ba77ad32d](https://linux-hardware.org/?probe=1ba77ad32d) | Jul 16, 2021 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [28a75498dc](https://linux-hardware.org/?probe=28a75498dc) | Jul 16, 2021 |
| MSI           | CSM-H81M-P32                | Desktop     | [33a729d21a](https://linux-hardware.org/?probe=33a729d21a) | Jul 16, 2021 |
| Gigabyte      | H510M H                     | Desktop     | [70f8b94923](https://linux-hardware.org/?probe=70f8b94923) | Jul 16, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [75ec31cefd](https://linux-hardware.org/?probe=75ec31cefd) | Jul 16, 2021 |
| MSI           | CSM-H81M-P32                | Desktop     | [898c0290c3](https://linux-hardware.org/?probe=898c0290c3) | Jul 16, 2021 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [560552deb4](https://linux-hardware.org/?probe=560552deb4) | Jul 16, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [58d278daa8](https://linux-hardware.org/?probe=58d278daa8) | Jul 15, 2021 |
| ASUSTek       | K52F                        | Notebook    | [d5e4b88107](https://linux-hardware.org/?probe=d5e4b88107) | Jul 15, 2021 |
| ASUSTek       | K52F                        | Notebook    | [ddb285f827](https://linux-hardware.org/?probe=ddb285f827) | Jul 15, 2021 |
| Lenovo        | IdeaPad 15ARE05 81YQ        | Notebook    | [9edec18576](https://linux-hardware.org/?probe=9edec18576) | Jul 15, 2021 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [4ec6b2f316](https://linux-hardware.org/?probe=4ec6b2f316) | Jul 14, 2021 |
| HP            | ZBook 15 G6                 | Notebook    | [4c8dc5d218](https://linux-hardware.org/?probe=4c8dc5d218) | Jul 14, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [529b60fd9a](https://linux-hardware.org/?probe=529b60fd9a) | Jul 14, 2021 |
| Lenovo        | ThinkPad A485 20MUCTO1WW    | Notebook    | [483690e890](https://linux-hardware.org/?probe=483690e890) | Jul 14, 2021 |
| Dell          | 0PC5F7 A02                  | Desktop     | [22292958a8](https://linux-hardware.org/?probe=22292958a8) | Jul 13, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Convertible | [5e8726a333](https://linux-hardware.org/?probe=5e8726a333) | Jul 13, 2021 |
| Dell          | 0D6H9T A00                  | Desktop     | [a989b9d184](https://linux-hardware.org/?probe=a989b9d184) | Jul 13, 2021 |
| Dell          | 0D6H9T A00                  | Desktop     | [19a34b1a62](https://linux-hardware.org/?probe=19a34b1a62) | Jul 13, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [300cd4ff38](https://linux-hardware.org/?probe=300cd4ff38) | Jul 13, 2021 |
| HP            | 3033h                       | Desktop     | [c2c9087398](https://linux-hardware.org/?probe=c2c9087398) | Jul 13, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [870b9bdfca](https://linux-hardware.org/?probe=870b9bdfca) | Jul 13, 2021 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [a1078eb34f](https://linux-hardware.org/?probe=a1078eb34f) | Jul 12, 2021 |
| HP            | 3396                        | Desktop     | [b4b3b24ab8](https://linux-hardware.org/?probe=b4b3b24ab8) | Jul 12, 2021 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [98271924ba](https://linux-hardware.org/?probe=98271924ba) | Jul 11, 2021 |
| Acer          | Aspire 7740                 | Notebook    | [d8694dd629](https://linux-hardware.org/?probe=d8694dd629) | Jul 09, 2021 |
| MSI           | CSM-H81M-P32                | Desktop     | [dcac2bf6e1](https://linux-hardware.org/?probe=dcac2bf6e1) | Jul 08, 2021 |
| ASUSTek       | N53SV                       | Notebook    | [53fef6a61a](https://linux-hardware.org/?probe=53fef6a61a) | Jul 08, 2021 |
| Notebook      | NH55RGQ                     | Notebook    | [553b287a99](https://linux-hardware.org/?probe=553b287a99) | Jul 08, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [7d426cda13](https://linux-hardware.org/?probe=7d426cda13) | Jul 07, 2021 |
| MSI           | H170 GAMING M3              | Desktop     | [664dcbec03](https://linux-hardware.org/?probe=664dcbec03) | Jul 07, 2021 |
| Acer          | Swift SF713-51              | Notebook    | [cfbfabdf1e](https://linux-hardware.org/?probe=cfbfabdf1e) | Jul 06, 2021 |
| MSI           | GF63 Thin 10SCSR            | Notebook    | [9da2c8084a](https://linux-hardware.org/?probe=9da2c8084a) | Jul 06, 2021 |
| Dell          | 0PC5F7 A02                  | Desktop     | [69010b3987](https://linux-hardware.org/?probe=69010b3987) | Jul 06, 2021 |
| Toshiba       | Satellite P870              | Notebook    | [c896408bd5](https://linux-hardware.org/?probe=c896408bd5) | Jul 06, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [d8aa41e9c2](https://linux-hardware.org/?probe=d8aa41e9c2) | Jul 06, 2021 |
| ASUSTek       | ROG Strix G713QR_G713QR     | Notebook    | [0b10aaa23c](https://linux-hardware.org/?probe=0b10aaa23c) | Jul 06, 2021 |
| ASUSTek       | ROG Strix G713QR_G713QR     | Notebook    | [6c81e98dd0](https://linux-hardware.org/?probe=6c81e98dd0) | Jul 06, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [28ed4f2d79](https://linux-hardware.org/?probe=28ed4f2d79) | Jul 06, 2021 |
| ASUSTek       | G60JX                       | Notebook    | [e8d5f8310c](https://linux-hardware.org/?probe=e8d5f8310c) | Jul 06, 2021 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [85ee7fa5f1](https://linux-hardware.org/?probe=85ee7fa5f1) | Jul 05, 2021 |
| ASUSTek       | P8H61 R2.0                  | Desktop     | [4b09460ffe](https://linux-hardware.org/?probe=4b09460ffe) | Jul 05, 2021 |
| ASUSTek       | P8H61 R2.0                  | Desktop     | [e8b5b518f5](https://linux-hardware.org/?probe=e8b5b518f5) | Jul 05, 2021 |
| HP            | 2000                        | Notebook    | [d407444700](https://linux-hardware.org/?probe=d407444700) | Jul 05, 2021 |
| HP            | Compaq Presario CQ70        | Notebook    | [67164ff77c](https://linux-hardware.org/?probe=67164ff77c) | Jul 04, 2021 |
| Samsung       | NC210/NC110                 | Notebook    | [0723913929](https://linux-hardware.org/?probe=0723913929) | Jul 04, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [121cbd3010](https://linux-hardware.org/?probe=121cbd3010) | Jul 03, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [db93b6b390](https://linux-hardware.org/?probe=db93b6b390) | Jul 03, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [f02362501b](https://linux-hardware.org/?probe=f02362501b) | Jul 03, 2021 |
| HP            | 212B                        | Desktop     | [17ed8f7604](https://linux-hardware.org/?probe=17ed8f7604) | Jul 03, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [64beaec8c9](https://linux-hardware.org/?probe=64beaec8c9) | Jul 03, 2021 |
| ASUSTek       | H97-PRO GAMER               | Desktop     | [2a51e0d9e9](https://linux-hardware.org/?probe=2a51e0d9e9) | Jul 03, 2021 |
| Samsung       | NC210/NC110                 | Notebook    | [89830217f4](https://linux-hardware.org/?probe=89830217f4) | Jul 03, 2021 |
| ASUSTek       | ROG Strix G731GW_G731GW     | Notebook    | [fc6a98826e](https://linux-hardware.org/?probe=fc6a98826e) | Jul 02, 2021 |
| MSI           | CSM-H81M-P32                | Desktop     | [f1598502b7](https://linux-hardware.org/?probe=f1598502b7) | Jul 02, 2021 |
| Dell          | 0WMJ54 A01                  | Desktop     | [54eb3b7908](https://linux-hardware.org/?probe=54eb3b7908) | Jul 01, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e42003e8ce](https://linux-hardware.org/?probe=e42003e8ce) | Jul 01, 2021 |
| MSI           | CSM-H81M-P32                | Desktop     | [4d9ea62879](https://linux-hardware.org/?probe=4d9ea62879) | Jun 30, 2021 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [e325df530d](https://linux-hardware.org/?probe=e325df530d) | Jun 30, 2021 |
| Packard Be... | EasyNote_SJ51               | Notebook    | [e997783e39](https://linux-hardware.org/?probe=e997783e39) | Jun 30, 2021 |
| MSI           | CSM-H81M-P32                | Desktop     | [aeddb749a5](https://linux-hardware.org/?probe=aeddb749a5) | Jun 30, 2021 |
| ASUSTek       | X501A                       | Notebook    | [0a17576c5f](https://linux-hardware.org/?probe=0a17576c5f) | Jun 30, 2021 |
| Intel Clie... | LAPBC710                    | Notebook    | [93690f8eec](https://linux-hardware.org/?probe=93690f8eec) | Jun 30, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [1185271556](https://linux-hardware.org/?probe=1185271556) | Jun 29, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [0369ff2b06](https://linux-hardware.org/?probe=0369ff2b06) | Jun 29, 2021 |
| Microsoft     | Surface Book 2              | Tablet      | [9f586c4fda](https://linux-hardware.org/?probe=9f586c4fda) | Jun 28, 2021 |
| HP            | Pavilion g7                 | Notebook    | [46f283d457](https://linux-hardware.org/?probe=46f283d457) | Jun 28, 2021 |
| HP            | Pavilion dv7                | Notebook    | [abc0d17af2](https://linux-hardware.org/?probe=abc0d17af2) | Jun 27, 2021 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [f6b5474cbd](https://linux-hardware.org/?probe=f6b5474cbd) | Jun 27, 2021 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [df070cec60](https://linux-hardware.org/?probe=df070cec60) | Jun 27, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [1b814c87a5](https://linux-hardware.org/?probe=1b814c87a5) | Jun 27, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [306b388a14](https://linux-hardware.org/?probe=306b388a14) | Jun 27, 2021 |
| ASRock        | TRX40 Taichi                | Desktop     | [6a2d22eae8](https://linux-hardware.org/?probe=6a2d22eae8) | Jun 26, 2021 |
| ASRock        | TRX40 Taichi                | Desktop     | [5b1b696b98](https://linux-hardware.org/?probe=5b1b696b98) | Jun 26, 2021 |
| HP            | Pavilion dv7                | Notebook    | [93d2d0e853](https://linux-hardware.org/?probe=93d2d0e853) | Jun 26, 2021 |
| HP            | G72                         | Notebook    | [1d1f4771a9](https://linux-hardware.org/?probe=1d1f4771a9) | Jun 26, 2021 |
| HP            | Pavilion dv6                | Notebook    | [7f27dab916](https://linux-hardware.org/?probe=7f27dab916) | Jun 26, 2021 |
| ONDA          | D1800 BTC V1.04 Ver:1.04    | Desktop     | [65beb6c6f4](https://linux-hardware.org/?probe=65beb6c6f4) | Jun 26, 2021 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [134c59d2f0](https://linux-hardware.org/?probe=134c59d2f0) | Jun 25, 2021 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [95a80b91fd](https://linux-hardware.org/?probe=95a80b91fd) | Jun 25, 2021 |
| HP            | 0AA8h                       | Desktop     | [8de391044c](https://linux-hardware.org/?probe=8de391044c) | Jun 24, 2021 |
| HP            | 0AA8h                       | Desktop     | [a477bc402f](https://linux-hardware.org/?probe=a477bc402f) | Jun 24, 2021 |
| ASUSTek       | PRIME Z270-K                | Desktop     | [407cc03b98](https://linux-hardware.org/?probe=407cc03b98) | Jun 24, 2021 |
| ASUSTek       | PRIME Z270-K                | Desktop     | [a6ea87df19](https://linux-hardware.org/?probe=a6ea87df19) | Jun 24, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [9957b51bea](https://linux-hardware.org/?probe=9957b51bea) | Jun 24, 2021 |
| Pegatron      | 2A94                        | Desktop     | [670987b884](https://linux-hardware.org/?probe=670987b884) | Jun 24, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [2c6ef158c3](https://linux-hardware.org/?probe=2c6ef158c3) | Jun 23, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1B70... | Notebook    | [41e8be3712](https://linux-hardware.org/?probe=41e8be3712) | Jun 23, 2021 |
| Dell          | Latitude 3310               | Notebook    | [ddea5b3c29](https://linux-hardware.org/?probe=ddea5b3c29) | Jun 23, 2021 |
| MSI           | A78M-E45                    | Desktop     | [65c6ba4865](https://linux-hardware.org/?probe=65c6ba4865) | Jun 23, 2021 |
| Dell          | Inspiron 1764               | Notebook    | [c07ba0955b](https://linux-hardware.org/?probe=c07ba0955b) | Jun 23, 2021 |
| Medion        | MS-7800                     | Desktop     | [90db582ae3](https://linux-hardware.org/?probe=90db582ae3) | Jun 22, 2021 |
| Intel         | X79 V2.0                    | Desktop     | [8d919f5f90](https://linux-hardware.org/?probe=8d919f5f90) | Jun 22, 2021 |
| Medion        | MS-7848                     | Desktop     | [9b089ee5f2](https://linux-hardware.org/?probe=9b089ee5f2) | Jun 22, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [f1a33d99b9](https://linux-hardware.org/?probe=f1a33d99b9) | Jun 21, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [60fd517dae](https://linux-hardware.org/?probe=60fd517dae) | Jun 21, 2021 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [5050b7baad](https://linux-hardware.org/?probe=5050b7baad) | Jun 21, 2021 |
| HP            | 8184 X4                     | Desktop     | [429b73d4c9](https://linux-hardware.org/?probe=429b73d4c9) | Jun 20, 2021 |
| HP            | 8184 X4                     | Desktop     | [a7280fe917](https://linux-hardware.org/?probe=a7280fe917) | Jun 20, 2021 |
| HP            | 8184 X4                     | Desktop     | [dd1fa9b71e](https://linux-hardware.org/?probe=dd1fa9b71e) | Jun 20, 2021 |
| Notebook      | NHxxRZQ                     | Notebook    | [221e4d197b](https://linux-hardware.org/?probe=221e4d197b) | Jun 19, 2021 |
| HP            | 3031h                       | Desktop     | [e216976e4f](https://linux-hardware.org/?probe=e216976e4f) | Jun 18, 2021 |
| Acer          | Predator PH317-51           | Notebook    | [8d95247823](https://linux-hardware.org/?probe=8d95247823) | Jun 18, 2021 |
| Lenovo        | ThinkPad T480 20L6S29D07    | Notebook    | [5c87bcb1dc](https://linux-hardware.org/?probe=5c87bcb1dc) | Jun 18, 2021 |
| System76      | Adder WS                    | Notebook    | [5ac75f80f1](https://linux-hardware.org/?probe=5ac75f80f1) | Jun 18, 2021 |
| Dell          | 0DR845                      | Desktop     | [5b3909eeea](https://linux-hardware.org/?probe=5b3909eeea) | Jun 18, 2021 |
| HP            | 0AA8h                       | Desktop     | [43103b39a5](https://linux-hardware.org/?probe=43103b39a5) | Jun 17, 2021 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | Desktop     | [5aba9bb92a](https://linux-hardware.org/?probe=5aba9bb92a) | Jun 17, 2021 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [944c9f91a2](https://linux-hardware.org/?probe=944c9f91a2) | Jun 17, 2021 |
| Samsung       | NC210/NC110                 | Notebook    | [796bc88fae](https://linux-hardware.org/?probe=796bc88fae) | Jun 17, 2021 |
| Samsung       | NC210/NC110                 | Notebook    | [e64d06bc43](https://linux-hardware.org/?probe=e64d06bc43) | Jun 17, 2021 |
| Gigabyte      | Z170M-D3H-CF                | Desktop     | [afd44ff35a](https://linux-hardware.org/?probe=afd44ff35a) | Jun 14, 2021 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [715f19bf10](https://linux-hardware.org/?probe=715f19bf10) | Jun 13, 2021 |
| Acer          | Swift SF314-55G             | Notebook    | [4e5cf8aa1e](https://linux-hardware.org/?probe=4e5cf8aa1e) | Jun 13, 2021 |
| HP            | 0AA8h                       | Desktop     | [9154911bc9](https://linux-hardware.org/?probe=9154911bc9) | Jun 13, 2021 |
| ASUSTek       | P8H67                       | Desktop     | [07c121e3a8](https://linux-hardware.org/?probe=07c121e3a8) | Jun 12, 2021 |
| Unknown       | Unknown                     | Notebook    | [5f185a4077](https://linux-hardware.org/?probe=5f185a4077) | Jun 12, 2021 |
| Unknown       | Unknown                     | Notebook    | [d14b5b4d00](https://linux-hardware.org/?probe=d14b5b4d00) | Jun 12, 2021 |
| HP            | 212B                        | Desktop     | [cccf3ad9d7](https://linux-hardware.org/?probe=cccf3ad9d7) | Jun 11, 2021 |
| Dell          | 0M863N A00                  | Desktop     | [791a12cef2](https://linux-hardware.org/?probe=791a12cef2) | Jun 10, 2021 |
| Gigabyte      | Z97-HD3                     | Desktop     | [1ab4ff25ab](https://linux-hardware.org/?probe=1ab4ff25ab) | Jun 10, 2021 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | Desktop     | [841baaf1eb](https://linux-hardware.org/?probe=841baaf1eb) | Jun 09, 2021 |
| MSI           | K9N6PGM2-V2                 | Desktop     | [07e0f412b0](https://linux-hardware.org/?probe=07e0f412b0) | Jun 09, 2021 |
| Fujitsu Si... | AMILO Li 1718               | Notebook    | [28837b4881](https://linux-hardware.org/?probe=28837b4881) | Jun 08, 2021 |
| Timi          | RedmiBook Pro 14S           | Notebook    | [c23781809b](https://linux-hardware.org/?probe=c23781809b) | Jun 08, 2021 |
| Lenovo        | IdeaPad 330-17AST 81D7      | Notebook    | [164c8b2ff9](https://linux-hardware.org/?probe=164c8b2ff9) | Jun 07, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [7c843291b5](https://linux-hardware.org/?probe=7c843291b5) | Jun 07, 2021 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [6f5aed374a](https://linux-hardware.org/?probe=6f5aed374a) | Jun 06, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [28e371a13c](https://linux-hardware.org/?probe=28e371a13c) | Jun 06, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [a7f3e31683](https://linux-hardware.org/?probe=a7f3e31683) | Jun 06, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [f49f22766b](https://linux-hardware.org/?probe=f49f22766b) | Jun 05, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [204b2a5d7c](https://linux-hardware.org/?probe=204b2a5d7c) | Jun 05, 2021 |
| HP            | G72                         | Notebook    | [dfae1b630a](https://linux-hardware.org/?probe=dfae1b630a) | Jun 05, 2021 |
| Acer          | Aspire 5715Z                | Notebook    | [5824a05a58](https://linux-hardware.org/?probe=5824a05a58) | Jun 05, 2021 |
| ASRock        | Q1900M                      | Desktop     | [5a6a3fd400](https://linux-hardware.org/?probe=5a6a3fd400) | Jun 04, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [985f14462f](https://linux-hardware.org/?probe=985f14462f) | Jun 04, 2021 |
| MSI           | B85-G43 GAMING              | Desktop     | [00d1d057e5](https://linux-hardware.org/?probe=00d1d057e5) | Jun 03, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [d63b4a98c3](https://linux-hardware.org/?probe=d63b4a98c3) | Jun 03, 2021 |
| Acer          | Swift SF314-57              | Notebook    | [274b678e7a](https://linux-hardware.org/?probe=274b678e7a) | Jun 03, 2021 |
| Sony          | SVF1521A6EW                 | Notebook    | [5d6f2d1dbf](https://linux-hardware.org/?probe=5d6f2d1dbf) | Jun 02, 2021 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [7fb5f68146](https://linux-hardware.org/?probe=7fb5f68146) | Jun 02, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [8533dbc1de](https://linux-hardware.org/?probe=8533dbc1de) | Jun 02, 2021 |
| MSI           | H97M-G43                    | Desktop     | [ad63da340e](https://linux-hardware.org/?probe=ad63da340e) | Jun 02, 2021 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [9194adf3ed](https://linux-hardware.org/?probe=9194adf3ed) | Jun 02, 2021 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [09a3733791](https://linux-hardware.org/?probe=09a3733791) | Jun 01, 2021 |
| HP            | ProBook 450 G6              | Notebook    | [6c241e0b82](https://linux-hardware.org/?probe=6c241e0b82) | Jun 01, 2021 |
| HP            | ZBook Studio G5             | Notebook    | [72c6428c32](https://linux-hardware.org/?probe=72c6428c32) | Jun 01, 2021 |
| Medion        | B360H4-EM V1.0              | Desktop     | [8ce3bc5db0](https://linux-hardware.org/?probe=8ce3bc5db0) | Jun 01, 2021 |
| HP            | 0AA8h                       | Desktop     | [5ef9b701f3](https://linux-hardware.org/?probe=5ef9b701f3) | Jun 01, 2021 |
| Gigabyte      | AX370M-DS3H-CF              | Desktop     | [f544511e0a](https://linux-hardware.org/?probe=f544511e0a) | Jun 01, 2021 |
| Gigabyte      | X79-UP4                     | Desktop     | [912c8764ef](https://linux-hardware.org/?probe=912c8764ef) | May 31, 2021 |
| Dell          | 0R849J A00                  | Desktop     | [7a75936b55](https://linux-hardware.org/?probe=7a75936b55) | May 31, 2021 |
| Dell          | Latitude 7400               | Notebook    | [011a257801](https://linux-hardware.org/?probe=011a257801) | May 31, 2021 |
| HP            | ZBook Studio G5             | Notebook    | [1060065f34](https://linux-hardware.org/?probe=1060065f34) | May 30, 2021 |
| Acer          | Aspire 5715Z                | Notebook    | [2e325cddc1](https://linux-hardware.org/?probe=2e325cddc1) | May 30, 2021 |
| Fujitsu       | LIFEBOOK E751               | Notebook    | [57d55a953c](https://linux-hardware.org/?probe=57d55a953c) | May 30, 2021 |
| Dell          | XPS 17 9700                 | Notebook    | [3b1546b203](https://linux-hardware.org/?probe=3b1546b203) | May 30, 2021 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [f36828f316](https://linux-hardware.org/?probe=f36828f316) | May 30, 2021 |
| Acer          | Aspire 5715Z                | Notebook    | [417206cc6a](https://linux-hardware.org/?probe=417206cc6a) | May 30, 2021 |
| HP            | Compaq Presario CQ70        | Notebook    | [ba556f37a1](https://linux-hardware.org/?probe=ba556f37a1) | May 30, 2021 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [75b89efd82](https://linux-hardware.org/?probe=75b89efd82) | May 29, 2021 |
| Acer          | TravelMate 5730             | Notebook    | [b6e44b21db](https://linux-hardware.org/?probe=b6e44b21db) | May 29, 2021 |
| MSI           | P45 Neo3                    | Desktop     | [568ab8505e](https://linux-hardware.org/?probe=568ab8505e) | May 28, 2021 |
| HP            | Pavilion g7                 | Notebook    | [6607d7bfd4](https://linux-hardware.org/?probe=6607d7bfd4) | May 28, 2021 |
| Samsung       | RF510/RF410/RF710           | Notebook    | [ee109d9097](https://linux-hardware.org/?probe=ee109d9097) | May 27, 2021 |
| HP            | ZBook Studio G5             | Notebook    | [d21ff38bb9](https://linux-hardware.org/?probe=d21ff38bb9) | May 27, 2021 |
| Dell          | Latitude D630               | Notebook    | [e271885d51](https://linux-hardware.org/?probe=e271885d51) | May 27, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [d29da6f4ad](https://linux-hardware.org/?probe=d29da6f4ad) | May 27, 2021 |
| Unknown       | Unknown                     | Notebook    | [f36322ada4](https://linux-hardware.org/?probe=f36322ada4) | May 27, 2021 |
| HP            | Laptop 17-bs1xx             | Notebook    | [582d387cec](https://linux-hardware.org/?probe=582d387cec) | May 27, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [052b95ba1d](https://linux-hardware.org/?probe=052b95ba1d) | May 27, 2021 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [cc3b68507d](https://linux-hardware.org/?probe=cc3b68507d) | May 27, 2021 |
| Biostar       | H77MU3                      | Desktop     | [68732ecd4b](https://linux-hardware.org/?probe=68732ecd4b) | May 26, 2021 |
| Medion        | MS-7748                     | Desktop     | [ce5b2bf4ab](https://linux-hardware.org/?probe=ce5b2bf4ab) | May 26, 2021 |
| MSI           | FM2-A85XMA-P33              | Desktop     | [0a01344d75](https://linux-hardware.org/?probe=0a01344d75) | May 26, 2021 |
| ASUSTek       | P8P67 LE                    | Desktop     | [33bb3c3b9a](https://linux-hardware.org/?probe=33bb3c3b9a) | May 26, 2021 |
| HP            | 635                         | Notebook    | [c0fccb63bb](https://linux-hardware.org/?probe=c0fccb63bb) | May 26, 2021 |
| HP            | 635                         | Notebook    | [acff9705ee](https://linux-hardware.org/?probe=acff9705ee) | May 26, 2021 |
| MSI           | FM2-A85XMA-P33              | Desktop     | [0fabdb3aad](https://linux-hardware.org/?probe=0fabdb3aad) | May 25, 2021 |
| MSI           | Gamila/Giovani/Neon seri... | Desktop     | [cd3697bd15](https://linux-hardware.org/?probe=cd3697bd15) | May 25, 2021 |
| MSI           | Gamila/Giovani/Neon seri... | Desktop     | [7c520b0d6e](https://linux-hardware.org/?probe=7c520b0d6e) | May 25, 2021 |
| Notebook      | PB50_70RF,RD,RC             | Notebook    | [fcd5c85a91](https://linux-hardware.org/?probe=fcd5c85a91) | May 25, 2021 |
| Notebook      | PB50_70RF,RD,RC             | Notebook    | [5607d8fb3e](https://linux-hardware.org/?probe=5607d8fb3e) | May 25, 2021 |
| MSI           | FM2-A85XMA-P33              | Desktop     | [40de3f5310](https://linux-hardware.org/?probe=40de3f5310) | May 25, 2021 |
| Apple         | MacBookAir5,2               | Notebook    | [ec1abd9485](https://linux-hardware.org/?probe=ec1abd9485) | May 24, 2021 |
| HP            | 0A60h                       | Desktop     | [1065543012](https://linux-hardware.org/?probe=1065543012) | May 24, 2021 |
| HP            | 635                         | Notebook    | [b96dfdc2fa](https://linux-hardware.org/?probe=b96dfdc2fa) | May 24, 2021 |
| Acer          | TravelMate 8172Z            | Notebook    | [ed52345849](https://linux-hardware.org/?probe=ed52345849) | May 24, 2021 |
| ASRock        | FM2A58M-DG3+                | Desktop     | [55e751ab54](https://linux-hardware.org/?probe=55e751ab54) | May 24, 2021 |
| HP            | EliteBook 8440p             | Notebook    | [f168c3b8d9](https://linux-hardware.org/?probe=f168c3b8d9) | May 24, 2021 |
| MSI           | Z490-A PRO                  | Desktop     | [e034d1b339](https://linux-hardware.org/?probe=e034d1b339) | May 23, 2021 |
| Unknown       | Unknown                     | Notebook    | [de75ca92a2](https://linux-hardware.org/?probe=de75ca92a2) | May 23, 2021 |
| Unknown       | Unknown                     | Notebook    | [292fe218cd](https://linux-hardware.org/?probe=292fe218cd) | May 23, 2021 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [92187479c3](https://linux-hardware.org/?probe=92187479c3) | May 22, 2021 |
| ASRock        | H97 Pro4                    | Desktop     | [b58191c0ab](https://linux-hardware.org/?probe=b58191c0ab) | May 22, 2021 |
| Acer          | EG43LMK                     | Desktop     | [c6f4b7dc40](https://linux-hardware.org/?probe=c6f4b7dc40) | May 22, 2021 |
| HP            | Pavilion dv7                | Notebook    | [f04eba21ce](https://linux-hardware.org/?probe=f04eba21ce) | May 22, 2021 |
| Dell          | Precision M2800             | Notebook    | [5b5d653c7a](https://linux-hardware.org/?probe=5b5d653c7a) | May 21, 2021 |
| Notebook      | NHxxRZQ                     | Notebook    | [f74dd50825](https://linux-hardware.org/?probe=f74dd50825) | May 21, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [f2d9eef592](https://linux-hardware.org/?probe=f2d9eef592) | May 21, 2021 |
| Dell          | Precision 7720              | Notebook    | [00ffeba6fc](https://linux-hardware.org/?probe=00ffeba6fc) | May 21, 2021 |
| Notebook      | NS50MU                      | Notebook    | [2feaa5043c](https://linux-hardware.org/?probe=2feaa5043c) | May 20, 2021 |
| HP            | Pavilion dv7                | Notebook    | [f908acc1ad](https://linux-hardware.org/?probe=f908acc1ad) | May 20, 2021 |
| Medion        | MS-7366                     | Desktop     | [c554c3a77f](https://linux-hardware.org/?probe=c554c3a77f) | May 20, 2021 |
| Medion        | MS-7366                     | Desktop     | [903b29e77e](https://linux-hardware.org/?probe=903b29e77e) | May 20, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [936e09e13c](https://linux-hardware.org/?probe=936e09e13c) | May 20, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [c0b08eec61](https://linux-hardware.org/?probe=c0b08eec61) | May 20, 2021 |
| Lenovo        | Y720-15IKB 80VR             | Notebook    | [dcc3f43c5b](https://linux-hardware.org/?probe=dcc3f43c5b) | May 19, 2021 |
| Lenovo        | Y720-15IKB 80VR             | Notebook    | [9a395856c5](https://linux-hardware.org/?probe=9a395856c5) | May 19, 2021 |
| Notebook      | NS50MU                      | Notebook    | [8e08645823](https://linux-hardware.org/?probe=8e08645823) | May 19, 2021 |
| Lenovo        | ThinkPad P51 20HHCT01WW     | Notebook    | [3f42eaf28b](https://linux-hardware.org/?probe=3f42eaf28b) | May 19, 2021 |
| Acer          | TravelMate 8172Z            | Notebook    | [3eb161b631](https://linux-hardware.org/?probe=3eb161b631) | May 19, 2021 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [6b27a727be](https://linux-hardware.org/?probe=6b27a727be) | May 19, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [b3af421ae5](https://linux-hardware.org/?probe=b3af421ae5) | May 18, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [368044e19e](https://linux-hardware.org/?probe=368044e19e) | May 18, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [fd2d87232f](https://linux-hardware.org/?probe=fd2d87232f) | May 18, 2021 |
| Acer          | EG43LMK                     | Desktop     | [1aaa7ce005](https://linux-hardware.org/?probe=1aaa7ce005) | May 18, 2021 |
| Dell          | Inspiron 7537               | Notebook    | [0e3be0292d](https://linux-hardware.org/?probe=0e3be0292d) | May 17, 2021 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [1fc64a9567](https://linux-hardware.org/?probe=1fc64a9567) | May 16, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [5da8abe961](https://linux-hardware.org/?probe=5da8abe961) | May 16, 2021 |
| ASUSTek       | P8H61-I R2.0                | Desktop     | [c641f2aee4](https://linux-hardware.org/?probe=c641f2aee4) | May 16, 2021 |
| ASUSTek       | P8H61-I R2.0                | Desktop     | [500443b449](https://linux-hardware.org/?probe=500443b449) | May 16, 2021 |
| HP            | 198E                        | Desktop     | [01e862baa7](https://linux-hardware.org/?probe=01e862baa7) | May 16, 2021 |
| Apple         | MacBookPro12,1              | Notebook    | [d0f7cef5fe](https://linux-hardware.org/?probe=d0f7cef5fe) | May 16, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [51c5d13230](https://linux-hardware.org/?probe=51c5d13230) | May 16, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [557f952ce8](https://linux-hardware.org/?probe=557f952ce8) | May 16, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [7d180179c9](https://linux-hardware.org/?probe=7d180179c9) | May 15, 2021 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [a31ac61c4b](https://linux-hardware.org/?probe=a31ac61c4b) | May 15, 2021 |
| Microsoft     | Surface Pro                 | Tablet      | [7a294509de](https://linux-hardware.org/?probe=7a294509de) | May 15, 2021 |
| Intel         | NUC10i5FNB K61361-306       | Mini pc     | [efaeef46d4](https://linux-hardware.org/?probe=efaeef46d4) | May 14, 2021 |
| Dell          | 0RY007                      | Desktop     | [409813e8e9](https://linux-hardware.org/?probe=409813e8e9) | May 14, 2021 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [a44fcb1c39](https://linux-hardware.org/?probe=a44fcb1c39) | May 13, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [42615ceaf6](https://linux-hardware.org/?probe=42615ceaf6) | May 13, 2021 |
| Lenovo        | Y720-15IKB 80VR             | Notebook    | [49c655dd05](https://linux-hardware.org/?probe=49c655dd05) | May 12, 2021 |
| Acer          | AOA150                      | Notebook    | [21647e22ba](https://linux-hardware.org/?probe=21647e22ba) | May 12, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [307f03a22d](https://linux-hardware.org/?probe=307f03a22d) | May 12, 2021 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [2efd6e26e3](https://linux-hardware.org/?probe=2efd6e26e3) | May 12, 2021 |
| Dell          | Latitude E6320              | Notebook    | [3d76e2296e](https://linux-hardware.org/?probe=3d76e2296e) | May 11, 2021 |
| Toshiba       | All In One PC MP            | All in one  | [d417ad3262](https://linux-hardware.org/?probe=d417ad3262) | May 11, 2021 |
| ASRock        | Z68 Extreme4 Gen3           | Desktop     | [1a53bcfaee](https://linux-hardware.org/?probe=1a53bcfaee) | May 11, 2021 |
| HP            | ZBook Studio G5             | Notebook    | [b5231411fd](https://linux-hardware.org/?probe=b5231411fd) | May 11, 2021 |
| Dell          | 0200DY A00                  | Desktop     | [38f2da4073](https://linux-hardware.org/?probe=38f2da4073) | May 11, 2021 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [b61a1c61d8](https://linux-hardware.org/?probe=b61a1c61d8) | May 10, 2021 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | Notebook    | [b71b291af5](https://linux-hardware.org/?probe=b71b291af5) | May 10, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [e2f53fd988](https://linux-hardware.org/?probe=e2f53fd988) | May 09, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [7e1389e1ed](https://linux-hardware.org/?probe=7e1389e1ed) | May 09, 2021 |
| Fujitsu Si... | MS-7379VP                   | Desktop     | [37fc7a9d11](https://linux-hardware.org/?probe=37fc7a9d11) | May 09, 2021 |
| ASUSTek       | K52Jr                       | Notebook    | [5484537afd](https://linux-hardware.org/?probe=5484537afd) | May 09, 2021 |
| HP            | 1495                        | Desktop     | [edcac20052](https://linux-hardware.org/?probe=edcac20052) | May 09, 2021 |
| HP            | 826A A01                    | All in one  | [c60fceaee4](https://linux-hardware.org/?probe=c60fceaee4) | May 09, 2021 |
| Intel         | NUC8BEB J72688-307          | Mini pc     | [3f5cd628cc](https://linux-hardware.org/?probe=3f5cd628cc) | May 09, 2021 |
| HP            | 1495                        | Desktop     | [511a9836f9](https://linux-hardware.org/?probe=511a9836f9) | May 09, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [bc1c6768ef](https://linux-hardware.org/?probe=bc1c6768ef) | May 08, 2021 |
| ASUSTek       | P5LD2-SE                    | Desktop     | [01a631df0a](https://linux-hardware.org/?probe=01a631df0a) | May 08, 2021 |
| Fujitsu Si... | MS-7379VP                   | Desktop     | [e9df0666cb](https://linux-hardware.org/?probe=e9df0666cb) | May 08, 2021 |
| Dell          | Precision 7750              | Notebook    | [439fb8f524](https://linux-hardware.org/?probe=439fb8f524) | May 08, 2021 |
| Dell          | Precision 7750              | Notebook    | [f3cdb6163b](https://linux-hardware.org/?probe=f3cdb6163b) | May 08, 2021 |
| Dell          | Precision M4600             | Notebook    | [9f1f5b7ef7](https://linux-hardware.org/?probe=9f1f5b7ef7) | May 08, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [143d4d07ab](https://linux-hardware.org/?probe=143d4d07ab) | May 07, 2021 |
| HP            | Pavilion g6                 | Notebook    | [225644d3a3](https://linux-hardware.org/?probe=225644d3a3) | May 07, 2021 |
| HP            | 8710                        | Mini pc     | [a862c9d728](https://linux-hardware.org/?probe=a862c9d728) | May 07, 2021 |
| Gigabyte      | A520I AC                    | Desktop     | [eb32404ebf](https://linux-hardware.org/?probe=eb32404ebf) | May 07, 2021 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [0b4a5c33ef](https://linux-hardware.org/?probe=0b4a5c33ef) | May 06, 2021 |
| HP            | EliteBook 850 G1            | Notebook    | [42955b2c95](https://linux-hardware.org/?probe=42955b2c95) | May 06, 2021 |
| HP            | ZBook 15                    | Notebook    | [ccdf2eebed](https://linux-hardware.org/?probe=ccdf2eebed) | May 06, 2021 |
| HP            | ZBook 15                    | Notebook    | [702b924ad3](https://linux-hardware.org/?probe=702b924ad3) | May 06, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [d186bad578](https://linux-hardware.org/?probe=d186bad578) | May 06, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [9036e74d34](https://linux-hardware.org/?probe=9036e74d34) | May 06, 2021 |
| HP            | ProBook 4720s               | Notebook    | [be29386ec0](https://linux-hardware.org/?probe=be29386ec0) | May 05, 2021 |
| Acer          | TravelMate Spin B118-R      | Convertible | [aca273fe62](https://linux-hardware.org/?probe=aca273fe62) | May 05, 2021 |
| Toshiba       | Satellite P200              | Notebook    | [5fff6be5f0](https://linux-hardware.org/?probe=5fff6be5f0) | May 05, 2021 |
| Fujitsu Si... | MS-7379VP                   | Desktop     | [7607ff1e97](https://linux-hardware.org/?probe=7607ff1e97) | May 05, 2021 |
| ASRock        | Z77 Pro4-M                  | Desktop     | [e9fe60f89a](https://linux-hardware.org/?probe=e9fe60f89a) | May 05, 2021 |
| TUXEDO        | Polaris 15 AMD Gen1         | Notebook    | [4dd6f9ee66](https://linux-hardware.org/?probe=4dd6f9ee66) | May 04, 2021 |
| ASRock        | FM2A58M-HD+                 | Desktop     | [22cfe5b72a](https://linux-hardware.org/?probe=22cfe5b72a) | May 04, 2021 |
| HP            | Pavilion                    | Notebook    | [e874b8bf1c](https://linux-hardware.org/?probe=e874b8bf1c) | May 04, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [18fedce180](https://linux-hardware.org/?probe=18fedce180) | May 04, 2021 |
| TUXEDO        | Unknown                     | Notebook    | [daacb350d8](https://linux-hardware.org/?probe=daacb350d8) | May 03, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6f0263cc5e](https://linux-hardware.org/?probe=6f0263cc5e) | May 03, 2021 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [a9f1f61276](https://linux-hardware.org/?probe=a9f1f61276) | May 03, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [05bc374383](https://linux-hardware.org/?probe=05bc374383) | May 02, 2021 |
| Acer          | AO725                       | Notebook    | [4af062c83b](https://linux-hardware.org/?probe=4af062c83b) | May 02, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [a9b6476d74](https://linux-hardware.org/?probe=a9b6476d74) | May 02, 2021 |
| HP            | 3397                        | Desktop     | [52732e2ef7](https://linux-hardware.org/?probe=52732e2ef7) | May 01, 2021 |
| ASUSTek       | Z97-PRO                     | Desktop     | [fbe5a2da06](https://linux-hardware.org/?probe=fbe5a2da06) | May 01, 2021 |
| HP            | ProBook 640 G1              | Notebook    | [c48920b807](https://linux-hardware.org/?probe=c48920b807) | May 01, 2021 |
| Pegatron      | 2A94h                       | Desktop     | [a878fd66eb](https://linux-hardware.org/?probe=a878fd66eb) | May 01, 2021 |
| Acer          | Aspire A515-51G             | Notebook    | [c871e2a253](https://linux-hardware.org/?probe=c871e2a253) | May 01, 2021 |
| ASUSTek       | GL552VW                     | Notebook    | [4fcc4fbcb8](https://linux-hardware.org/?probe=4fcc4fbcb8) | Apr 30, 2021 |
| ASUSTek       | P5QL-ASUS-SE                | Desktop     | [72b785dd42](https://linux-hardware.org/?probe=72b785dd42) | Apr 29, 2021 |
| MSI           | 990FXA-GD65                 | Desktop     | [3ab1cd59ae](https://linux-hardware.org/?probe=3ab1cd59ae) | Apr 29, 2021 |
| MSI           | 990FXA-GD65                 | Desktop     | [99308888c8](https://linux-hardware.org/?probe=99308888c8) | Apr 28, 2021 |
| ASUSTek       | UX550VD                     | Notebook    | [8564c561bd](https://linux-hardware.org/?probe=8564c561bd) | Apr 28, 2021 |
| Fujitsu       | LIFEBOOK AH531/GFO          | Notebook    | [ad0dfb309f](https://linux-hardware.org/?probe=ad0dfb309f) | Apr 27, 2021 |
| Intel         | NUC7i5BNB J31144-305        | Mini pc     | [ae9a58ea22](https://linux-hardware.org/?probe=ae9a58ea22) | Apr 27, 2021 |
| ASRock        | H310CM-ITX/ac               | Desktop     | [638690d465](https://linux-hardware.org/?probe=638690d465) | Apr 27, 2021 |
| Acer          | Veriton L4610G              | Desktop     | [ce84b68730](https://linux-hardware.org/?probe=ce84b68730) | Apr 27, 2021 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [ef922fa721](https://linux-hardware.org/?probe=ef922fa721) | Apr 26, 2021 |
| Microsoft     | Surface Pro                 | Tablet      | [4238374bcc](https://linux-hardware.org/?probe=4238374bcc) | Apr 26, 2021 |
| HP            | 0A54h                       | Desktop     | [6ffbc65ee7](https://linux-hardware.org/?probe=6ffbc65ee7) | Apr 26, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [7a133af461](https://linux-hardware.org/?probe=7a133af461) | Apr 25, 2021 |
| HP            | Pavilion 13 x360 PC         | Notebook    | [23fb448b76](https://linux-hardware.org/?probe=23fb448b76) | Apr 25, 2021 |
| HP            | 0A54h                       | Desktop     | [6d52fc9b60](https://linux-hardware.org/?probe=6d52fc9b60) | Apr 25, 2021 |
| Colorful T... | BATTLE-AX B365M-HD PRO V... | Desktop     | [0058e203e8](https://linux-hardware.org/?probe=0058e203e8) | Apr 25, 2021 |
| Intel         | DX58SO AAE29331-404         | Desktop     | [e4f384c278](https://linux-hardware.org/?probe=e4f384c278) | Apr 24, 2021 |
| Lenovo        | ThinkPad S430 33644KG       | Notebook    | [ef8d3e2cea](https://linux-hardware.org/?probe=ef8d3e2cea) | Apr 24, 2021 |
| Dell          | Inspiron 5748               | Notebook    | [796f084ee3](https://linux-hardware.org/?probe=796f084ee3) | Apr 24, 2021 |
| HP            | 8430 1000                   | All in one  | [5c5adcc248](https://linux-hardware.org/?probe=5c5adcc248) | Apr 24, 2021 |
| ASUSTek       | K53E                        | Notebook    | [54fb711c08](https://linux-hardware.org/?probe=54fb711c08) | Apr 23, 2021 |
| Google        | Lars                        | Notebook    | [e37c5680c3](https://linux-hardware.org/?probe=e37c5680c3) | Apr 23, 2021 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [02220ad005](https://linux-hardware.org/?probe=02220ad005) | Apr 23, 2021 |
| Google        | Lars                        | Notebook    | [d2f13246b1](https://linux-hardware.org/?probe=d2f13246b1) | Apr 23, 2021 |
| HP            | ZBook Studio G5             | Notebook    | [d323a9cfbf](https://linux-hardware.org/?probe=d323a9cfbf) | Apr 23, 2021 |
| Dell          | Latitude E6540              | Notebook    | [26df8e7b5d](https://linux-hardware.org/?probe=26df8e7b5d) | Apr 22, 2021 |
| Toshiba       | Satellite L350              | Notebook    | [94f6fd27b6](https://linux-hardware.org/?probe=94f6fd27b6) | Apr 22, 2021 |
| Intel         | NUC10i3FNB K61362-305       | Mini pc     | [b01212219b](https://linux-hardware.org/?probe=b01212219b) | Apr 21, 2021 |
| HP            | 86C7 0001                   | All in one  | [b928a63ef1](https://linux-hardware.org/?probe=b928a63ef1) | Apr 21, 2021 |
| MSI           | Prestige 15 A10SC           | Notebook    | [ece4d8837e](https://linux-hardware.org/?probe=ece4d8837e) | Apr 21, 2021 |
| ASUSTek       | K70IJ                       | Notebook    | [c372d5427b](https://linux-hardware.org/?probe=c372d5427b) | Apr 21, 2021 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [75567232ab](https://linux-hardware.org/?probe=75567232ab) | Apr 21, 2021 |
| Toshiba       | Satellite L775-18Q          | Notebook    | [3adfb91705](https://linux-hardware.org/?probe=3adfb91705) | Apr 21, 2021 |
| Intel         | NUC10i3FNB K61362-305       | Mini pc     | [291119278b](https://linux-hardware.org/?probe=291119278b) | Apr 21, 2021 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [59dbdcb7ca](https://linux-hardware.org/?probe=59dbdcb7ca) | Apr 21, 2021 |
| Lenovo        | ThinkPad X220 4291JN1       | Notebook    | [4f57fda418](https://linux-hardware.org/?probe=4f57fda418) | Apr 21, 2021 |
| Dell          | G3 3579                     | Notebook    | [44e3a249ee](https://linux-hardware.org/?probe=44e3a249ee) | Apr 21, 2021 |
| Dell          | G3 3579                     | Notebook    | [f61d3bc8d9](https://linux-hardware.org/?probe=f61d3bc8d9) | Apr 21, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [dc24c1770f](https://linux-hardware.org/?probe=dc24c1770f) | Apr 20, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [b231eba176](https://linux-hardware.org/?probe=b231eba176) | Apr 20, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [bca00a44eb](https://linux-hardware.org/?probe=bca00a44eb) | Apr 20, 2021 |
| Gigabyte      | H81M-S2V                    | Desktop     | [6dba735784](https://linux-hardware.org/?probe=6dba735784) | Apr 20, 2021 |
| Gigabyte      | 970A-UD3                    | Desktop     | [a10778a5bb](https://linux-hardware.org/?probe=a10778a5bb) | Apr 20, 2021 |
| Connect       | Tablet 9                    | Notebook    | [6d68fde5d8](https://linux-hardware.org/?probe=6d68fde5d8) | Apr 19, 2021 |
| MPMAN         | MPWIN8900CL                 | Notebook    | [3c21016b82](https://linux-hardware.org/?probe=3c21016b82) | Apr 19, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [16d4553883](https://linux-hardware.org/?probe=16d4553883) | Apr 19, 2021 |
| Insyde        | i71c                        | Notebook    | [ec749b6624](https://linux-hardware.org/?probe=ec749b6624) | Apr 18, 2021 |
| Irbis         | TW90                        | Tablet      | [129d1bda9e](https://linux-hardware.org/?probe=129d1bda9e) | Apr 18, 2021 |
| Dell          | 0WMJ54 A01                  | Desktop     | [09232a1dc1](https://linux-hardware.org/?probe=09232a1dc1) | Apr 18, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [71cec0648d](https://linux-hardware.org/?probe=71cec0648d) | Apr 18, 2021 |
| TrekStor      | SurfTab wintron 7.0 ST70... | Notebook    | [12af9205b0](https://linux-hardware.org/?probe=12af9205b0) | Apr 18, 2021 |
| Dell          | 0WMJ54 A01                  | Desktop     | [13d82b26a3](https://linux-hardware.org/?probe=13d82b26a3) | Apr 18, 2021 |
| Notebook      | N150CU                      | Notebook    | [47188901d9](https://linux-hardware.org/?probe=47188901d9) | Apr 17, 2021 |
| Acer          | E1-510                      | Notebook    | [d5a5b71d6a](https://linux-hardware.org/?probe=d5a5b71d6a) | Apr 17, 2021 |
| Teclast       | TbooK 11                    | Notebook    | [29537c9609](https://linux-hardware.org/?probe=29537c9609) | Apr 17, 2021 |
| Notebook      | P95_96_97Ex,Rx              | Notebook    | [d15260f198](https://linux-hardware.org/?probe=d15260f198) | Apr 17, 2021 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [4dd2eeb695](https://linux-hardware.org/?probe=4dd2eeb695) | Apr 17, 2021 |
| ASUSTek       | P6T DELUXE                  | Desktop     | [ca892da387](https://linux-hardware.org/?probe=ca892da387) | Apr 16, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [105e10df58](https://linux-hardware.org/?probe=105e10df58) | Apr 16, 2021 |
| Dell          | Latitude 5480               | Notebook    | [ff6578cc63](https://linux-hardware.org/?probe=ff6578cc63) | Apr 16, 2021 |
| Shenzhen P... | MOMO7W                      | Notebook    | [763921a4a1](https://linux-hardware.org/?probe=763921a4a1) | Apr 16, 2021 |
| Gigabyte      | H81M-S2V                    | Desktop     | [8e9d22ed4d](https://linux-hardware.org/?probe=8e9d22ed4d) | Apr 15, 2021 |
| Fujitsu Si... | D2840-A1 S26361-D2840-A1    | Desktop     | [d5310b7f74](https://linux-hardware.org/?probe=d5310b7f74) | Apr 15, 2021 |
| Medion        | P861X                       | Notebook    | [109599a6f6](https://linux-hardware.org/?probe=109599a6f6) | Apr 15, 2021 |
| Medion        | P861X                       | Notebook    | [ae05cea55d](https://linux-hardware.org/?probe=ae05cea55d) | Apr 15, 2021 |
| Acer          | E1-510                      | Notebook    | [a831e2fdb1](https://linux-hardware.org/?probe=a831e2fdb1) | Apr 15, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [30b766af67](https://linux-hardware.org/?probe=30b766af67) | Apr 14, 2021 |
| Medion        | H61H2-TI2                   | All in one  | [4ff205bed4](https://linux-hardware.org/?probe=4ff205bed4) | Apr 14, 2021 |
| HP            | 3031h                       | Desktop     | [c5ae037d12](https://linux-hardware.org/?probe=c5ae037d12) | Apr 14, 2021 |
| Lenovo        | ThinkPad T440p 20AN00C2U... | Notebook    | [b0a0db02b2](https://linux-hardware.org/?probe=b0a0db02b2) | Apr 13, 2021 |
| ASUSTek       | PRIME H310I-PLUS R2.0       | Desktop     | [9aee7b7176](https://linux-hardware.org/?probe=9aee7b7176) | Apr 13, 2021 |
| Microsoft     | Surface Laptop Go           | Tablet      | [bed5c42cc5](https://linux-hardware.org/?probe=bed5c42cc5) | Apr 13, 2021 |
| ASUSTek       | M4A78LT-M                   | Desktop     | [7b793e42b6](https://linux-hardware.org/?probe=7b793e42b6) | Apr 13, 2021 |
| HP            | 18E7                        | Desktop     | [81ec312d3f](https://linux-hardware.org/?probe=81ec312d3f) | Apr 13, 2021 |
| Medion        | P6815                       | Notebook    | [684ff8cd10](https://linux-hardware.org/?probe=684ff8cd10) | Apr 13, 2021 |
| ASUSTek       | P6T DELUXE                  | Desktop     | [e22cceb6c8](https://linux-hardware.org/?probe=e22cceb6c8) | Apr 12, 2021 |
| Fujitsu       | LIFEBOOK A555               | Notebook    | [7382b5564b](https://linux-hardware.org/?probe=7382b5564b) | Apr 11, 2021 |
| Toshiba       | Satellite P200              | Notebook    | [f6b3c134f2](https://linux-hardware.org/?probe=f6b3c134f2) | Apr 11, 2021 |
| Dell          | Latitude 7410               | Notebook    | [f37e7ac49d](https://linux-hardware.org/?probe=f37e7ac49d) | Apr 11, 2021 |
| Dell          | Inspiron 1545               | Notebook    | [a23936a0de](https://linux-hardware.org/?probe=a23936a0de) | Apr 10, 2021 |
| Dell          | Inspiron 3505               | Notebook    | [94af09f8f4](https://linux-hardware.org/?probe=94af09f8f4) | Apr 10, 2021 |
| HP            | Pavilion g6                 | Notebook    | [0c94394ebf](https://linux-hardware.org/?probe=0c94394ebf) | Apr 10, 2021 |
| Toshiba       | PORTEGE R500                | Notebook    | [217bd4d237](https://linux-hardware.org/?probe=217bd4d237) | Apr 10, 2021 |
| Acer          | Swift SF314-58              | Notebook    | [6dbc12e41d](https://linux-hardware.org/?probe=6dbc12e41d) | Apr 10, 2021 |
| Foxconn       | 45CS/45CSX                  | Desktop     | [a2238ca7c2](https://linux-hardware.org/?probe=a2238ca7c2) | Apr 10, 2021 |
| Foxconn       | 45CS/45CSX                  | Desktop     | [d512a6b9f4](https://linux-hardware.org/?probe=d512a6b9f4) | Apr 10, 2021 |
| Gigabyte      | B75M-D3V                    | Desktop     | [e99429099b](https://linux-hardware.org/?probe=e99429099b) | Apr 10, 2021 |
| Lenovo        | G70-70 80HW007LNX           | Notebook    | [4dae948802](https://linux-hardware.org/?probe=4dae948802) | Apr 09, 2021 |
| ASUSTek       | P6T DELUXE                  | Desktop     | [4f894a1421](https://linux-hardware.org/?probe=4f894a1421) | Apr 09, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [4c2971804a](https://linux-hardware.org/?probe=4c2971804a) | Apr 09, 2021 |
| Unknown       | Unknown                     | Soc         | [882e173f92](https://linux-hardware.org/?probe=882e173f92) | Apr 09, 2021 |
| ASUSTek       | B75M-PLUS                   | Desktop     | [1885080105](https://linux-hardware.org/?probe=1885080105) | Apr 08, 2021 |
| ASUSTek       | B75M-PLUS                   | Desktop     | [91e82d93c1](https://linux-hardware.org/?probe=91e82d93c1) | Apr 08, 2021 |
| MSI           | B85-G43 GAMING              | Desktop     | [01687bd18e](https://linux-hardware.org/?probe=01687bd18e) | Apr 08, 2021 |
| MSI           | B85-G43 GAMING              | Desktop     | [35a99c45fd](https://linux-hardware.org/?probe=35a99c45fd) | Apr 08, 2021 |
| Apple         | Mac-F221BEC8                | Desktop     | [e3292dd662](https://linux-hardware.org/?probe=e3292dd662) | Apr 08, 2021 |
| ASRock        | B360M Pro4                  | Desktop     | [07fba1f228](https://linux-hardware.org/?probe=07fba1f228) | Apr 07, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [b590cd21cc](https://linux-hardware.org/?probe=b590cd21cc) | Apr 07, 2021 |
| ASRock        | B360M Pro4                  | Desktop     | [65dd1419ba](https://linux-hardware.org/?probe=65dd1419ba) | Apr 06, 2021 |
| Dell          | Latitude E7440              | Notebook    | [476c3b6c59](https://linux-hardware.org/?probe=476c3b6c59) | Apr 06, 2021 |
| Dell          | 040DDP A01                  | Desktop     | [b9a72b6307](https://linux-hardware.org/?probe=b9a72b6307) | Apr 05, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [a03ddac4a4](https://linux-hardware.org/?probe=a03ddac4a4) | Apr 05, 2021 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [b7ca2f4a18](https://linux-hardware.org/?probe=b7ca2f4a18) | Apr 04, 2021 |
| HP            | Pavilion g6                 | Notebook    | [0b60251ab6](https://linux-hardware.org/?probe=0b60251ab6) | Apr 04, 2021 |
| Dell          | Latitude E7440              | Notebook    | [628956bc89](https://linux-hardware.org/?probe=628956bc89) | Apr 04, 2021 |
| ASRock        | H81M-HDS                    | Desktop     | [44d4e3ca20](https://linux-hardware.org/?probe=44d4e3ca20) | Apr 04, 2021 |
| Dell          | Precision 5550              | Notebook    | [fb83e2c0e0](https://linux-hardware.org/?probe=fb83e2c0e0) | Apr 04, 2021 |
| Dell          | Precision 5550              | Notebook    | [bf3982f88a](https://linux-hardware.org/?probe=bf3982f88a) | Apr 04, 2021 |
| HP            | 15                          | Notebook    | [86dfaa0690](https://linux-hardware.org/?probe=86dfaa0690) | Apr 03, 2021 |
| ASRock        | A300M-STX                   | Desktop     | [fab06f5134](https://linux-hardware.org/?probe=fab06f5134) | Apr 03, 2021 |
| Intel         | DG33FB AAD81072-303         | Desktop     | [af996aa861](https://linux-hardware.org/?probe=af996aa861) | Apr 03, 2021 |
| HP            | 2ADE                        | Desktop     | [5d3e982185](https://linux-hardware.org/?probe=5d3e982185) | Apr 03, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [9529a146ea](https://linux-hardware.org/?probe=9529a146ea) | Apr 03, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [a54331c236](https://linux-hardware.org/?probe=a54331c236) | Apr 03, 2021 |
| Dell          | Venue 10 Pro 5055           | Notebook    | [39feaef221](https://linux-hardware.org/?probe=39feaef221) | Apr 03, 2021 |
| ASUSTek       | P5KPL-AM                    | Desktop     | [5d108994bf](https://linux-hardware.org/?probe=5d108994bf) | Apr 02, 2021 |
| Dell          | 0VRWRC A00                  | Desktop     | [379fb6e9d5](https://linux-hardware.org/?probe=379fb6e9d5) | Apr 02, 2021 |
| Acer          | Spin SP513-54N              | Convertible | [5f8889c781](https://linux-hardware.org/?probe=5f8889c781) | Apr 02, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [c21b745152](https://linux-hardware.org/?probe=c21b745152) | Apr 02, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [d0f094fc1b](https://linux-hardware.org/?probe=d0f094fc1b) | Apr 02, 2021 |
| ASUSTek       | K73SV                       | Notebook    | [73cb5986f0](https://linux-hardware.org/?probe=73cb5986f0) | Apr 02, 2021 |
| ASUSTek       | K73SV                       | Notebook    | [c927ee6194](https://linux-hardware.org/?probe=c927ee6194) | Apr 02, 2021 |
| Gigabyte      | B550M S2H                   | Desktop     | [993b88f7a7](https://linux-hardware.org/?probe=993b88f7a7) | Apr 02, 2021 |
| ASRock        | N68C-GS4 FX                 | Desktop     | [f8c2960a69](https://linux-hardware.org/?probe=f8c2960a69) | Apr 02, 2021 |
| Dell          | 00NH4P A09                  | Server      | [21b5080a81](https://linux-hardware.org/?probe=21b5080a81) | Apr 02, 2021 |
| Dell          | 00NH4P A09                  | Server      | [71caeb9ca5](https://linux-hardware.org/?probe=71caeb9ca5) | Apr 01, 2021 |
| Dell          | Latitude D630               | Notebook    | [0f25d6dee3](https://linux-hardware.org/?probe=0f25d6dee3) | Mar 31, 2021 |
| Notebook      | N7x0WU                      | Notebook    | [b67aa0cc8a](https://linux-hardware.org/?probe=b67aa0cc8a) | Mar 30, 2021 |
| HP            | Pavilion dv7                | Notebook    | [0ac3629fe7](https://linux-hardware.org/?probe=0ac3629fe7) | Mar 30, 2021 |
| HP            | Pavilion dv7                | Notebook    | [c52ed4a403](https://linux-hardware.org/?probe=c52ed4a403) | Mar 30, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [74dc73e867](https://linux-hardware.org/?probe=74dc73e867) | Mar 29, 2021 |
| Intel         | NUC8BEB J72688-307          | Mini pc     | [9e179afd14](https://linux-hardware.org/?probe=9e179afd14) | Mar 28, 2021 |
| Packard Be... | EasyNote TK85               | Notebook    | [ef386f82ab](https://linux-hardware.org/?probe=ef386f82ab) | Mar 28, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [a7ba6cfb28](https://linux-hardware.org/?probe=a7ba6cfb28) | Mar 28, 2021 |
| HP            | 82DC 1000                   | All in one  | [036481482e](https://linux-hardware.org/?probe=036481482e) | Mar 28, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [b41b0c2610](https://linux-hardware.org/?probe=b41b0c2610) | Mar 28, 2021 |
| ASUSTek       | M5A88-M EVO                 | Desktop     | [68d4045b2b](https://linux-hardware.org/?probe=68d4045b2b) | Mar 27, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [5f69c7e7af](https://linux-hardware.org/?probe=5f69c7e7af) | Mar 27, 2021 |
| Medion        | MS-7708                     | Desktop     | [1124efcc8b](https://linux-hardware.org/?probe=1124efcc8b) | Mar 26, 2021 |
| ASUSTek       | N750JV                      | Notebook    | [3fe074b7b5](https://linux-hardware.org/?probe=3fe074b7b5) | Mar 26, 2021 |
| ASUSTek       | N750JV                      | Notebook    | [6351a50f64](https://linux-hardware.org/?probe=6351a50f64) | Mar 26, 2021 |
| Apple         | MacBook10,1                 | Notebook    | [91ecdd0d87](https://linux-hardware.org/?probe=91ecdd0d87) | Mar 26, 2021 |
| Dell          | Latitude 7300               | Notebook    | [0dd11ceadd](https://linux-hardware.org/?probe=0dd11ceadd) | Mar 25, 2021 |
| Dell          | Latitude E5470              | Notebook    | [6f77c7810a](https://linux-hardware.org/?probe=6f77c7810a) | Mar 25, 2021 |
| Intel         | DH87RL AAG74240-403         | Desktop     | [24a18712e2](https://linux-hardware.org/?probe=24a18712e2) | Mar 25, 2021 |
| ASUSTek       | PRIME Z270M-PLUS            | Desktop     | [3185f9f525](https://linux-hardware.org/?probe=3185f9f525) | Mar 25, 2021 |
| ASUSTek       | Leonite2                    | Desktop     | [5a924aa5d6](https://linux-hardware.org/?probe=5a924aa5d6) | Mar 24, 2021 |
| ASUSTek       | K52JT                       | Notebook    | [56fa400fae](https://linux-hardware.org/?probe=56fa400fae) | Mar 23, 2021 |
| Dell          | Latitude 5300               | Notebook    | [efd4a051e5](https://linux-hardware.org/?probe=efd4a051e5) | Mar 23, 2021 |
| Dell          | Latitude 5300               | Notebook    | [1da225004a](https://linux-hardware.org/?probe=1da225004a) | Mar 23, 2021 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [a9aefaa328](https://linux-hardware.org/?probe=a9aefaa328) | Mar 23, 2021 |
| Apple         | MacBook10,1                 | Notebook    | [fa67f39496](https://linux-hardware.org/?probe=fa67f39496) | Mar 23, 2021 |
| ASUSTek       | PRIME Z270M-PLUS            | Desktop     | [e83bcffc5c](https://linux-hardware.org/?probe=e83bcffc5c) | Mar 23, 2021 |
| Dell          | 05R2TK A01                  | All in one  | [bdf125b54e](https://linux-hardware.org/?probe=bdf125b54e) | Mar 22, 2021 |
| Alienware     | m15 R2                      | Notebook    | [78d083f161](https://linux-hardware.org/?probe=78d083f161) | Mar 22, 2021 |
| ASUSTek       | PRIME Z270M-PLUS            | Desktop     | [e84eaa43a6](https://linux-hardware.org/?probe=e84eaa43a6) | Mar 22, 2021 |
| Acer          | Predator G9-791             | Notebook    | [c059c4e3b6](https://linux-hardware.org/?probe=c059c4e3b6) | Mar 22, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [4c755699d3](https://linux-hardware.org/?probe=4c755699d3) | Mar 21, 2021 |
| HP            | 1850                        | Desktop     | [dc3365be9e](https://linux-hardware.org/?probe=dc3365be9e) | Mar 21, 2021 |
| HP            | Pavilion g6                 | Notebook    | [7def32f317](https://linux-hardware.org/?probe=7def32f317) | Mar 21, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [0804c208fa](https://linux-hardware.org/?probe=0804c208fa) | Mar 21, 2021 |
| HP            | 1850                        | Desktop     | [d100f6f8d2](https://linux-hardware.org/?probe=d100f6f8d2) | Mar 21, 2021 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [5f904125d3](https://linux-hardware.org/?probe=5f904125d3) | Mar 21, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [fa10b7878e](https://linux-hardware.org/?probe=fa10b7878e) | Mar 20, 2021 |
| Acer          | Veriton X2611G V1.0         | Desktop     | [fb7ee37f69](https://linux-hardware.org/?probe=fb7ee37f69) | Mar 20, 2021 |
| Dell          | 0VHXCD A01                  | Desktop     | [8363ef2a4d](https://linux-hardware.org/?probe=8363ef2a4d) | Mar 20, 2021 |
| MSI           | K9N6PGM2-V2                 | Desktop     | [2c47bb1725](https://linux-hardware.org/?probe=2c47bb1725) | Mar 19, 2021 |
| Fujitsu Si... | AMILO Pi 2512               | Notebook    | [64d9b3cc48](https://linux-hardware.org/?probe=64d9b3cc48) | Mar 19, 2021 |
| Dell          | Inspiron 5521               | Notebook    | [86c41c25e8](https://linux-hardware.org/?probe=86c41c25e8) | Mar 19, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [46aa7a9f77](https://linux-hardware.org/?probe=46aa7a9f77) | Mar 19, 2021 |
| Intel         | DH67BL AAG10189-207         | Desktop     | [74fdf95be5](https://linux-hardware.org/?probe=74fdf95be5) | Mar 18, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [98158b966b](https://linux-hardware.org/?probe=98158b966b) | Mar 18, 2021 |
| ASUSTek       | K42Jc                       | Notebook    | [a09d3e4590](https://linux-hardware.org/?probe=a09d3e4590) | Mar 18, 2021 |
| ASUSTek       | K42Jc                       | Notebook    | [a0072f783d](https://linux-hardware.org/?probe=a0072f783d) | Mar 18, 2021 |
| ASUSTek       | K53SC                       | Notebook    | [5d856bc420](https://linux-hardware.org/?probe=5d856bc420) | Mar 18, 2021 |
| ASUSTek       | K53SC                       | Notebook    | [5caa8f28d4](https://linux-hardware.org/?probe=5caa8f28d4) | Mar 18, 2021 |
| Apple         | MacBook10,1                 | Notebook    | [a43f5ee2d4](https://linux-hardware.org/?probe=a43f5ee2d4) | Mar 18, 2021 |
| ASUSTek       | ET1610PT                    | Desktop     | [9962e5d3c3](https://linux-hardware.org/?probe=9962e5d3c3) | Mar 17, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [931b4ef61d](https://linux-hardware.org/?probe=931b4ef61d) | Mar 17, 2021 |
| Dell          | Latitude E6420              | Notebook    | [b006880df4](https://linux-hardware.org/?probe=b006880df4) | Mar 17, 2021 |
| HP            | Pavilion dv6                | Notebook    | [cf490a5888](https://linux-hardware.org/?probe=cf490a5888) | Mar 17, 2021 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [c783c34d90](https://linux-hardware.org/?probe=c783c34d90) | Mar 17, 2021 |
| Dell          | Studio 1747                 | Notebook    | [aaab9c19df](https://linux-hardware.org/?probe=aaab9c19df) | Mar 16, 2021 |
| ASUSTek       | F1A75-M LE                  | Desktop     | [f75d4bc749](https://linux-hardware.org/?probe=f75d4bc749) | Mar 16, 2021 |
| Dell          | Latitude 7300               | Notebook    | [f67f5c2c95](https://linux-hardware.org/?probe=f67f5c2c95) | Mar 16, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [6b8f41261a](https://linux-hardware.org/?probe=6b8f41261a) | Mar 16, 2021 |
| Acer          | Aspire V3-772               | Notebook    | [6fd8e535b3](https://linux-hardware.org/?probe=6fd8e535b3) | Mar 15, 2021 |
| HP            | EliteBook 2560p             | Notebook    | [14300c6f28](https://linux-hardware.org/?probe=14300c6f28) | Mar 15, 2021 |
| Acer          | Spin SP513-54N              | Convertible | [0ad9ffb361](https://linux-hardware.org/?probe=0ad9ffb361) | Mar 15, 2021 |
| Apple         | MacBook5,1                  | Notebook    | [0abdfbf8bf](https://linux-hardware.org/?probe=0abdfbf8bf) | Mar 15, 2021 |
| Apple         | MacBook5,1                  | Notebook    | [9eaf31396b](https://linux-hardware.org/?probe=9eaf31396b) | Mar 14, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [effd213d01](https://linux-hardware.org/?probe=effd213d01) | Mar 13, 2021 |
| HP            | 339A                        | Desktop     | [355b85c060](https://linux-hardware.org/?probe=355b85c060) | Mar 13, 2021 |
| ASUSTek       | P5P43TD                     | Desktop     | [f0539d32a3](https://linux-hardware.org/?probe=f0539d32a3) | Mar 13, 2021 |
| ASUSTek       | P5P43TD                     | Desktop     | [b3f2fab399](https://linux-hardware.org/?probe=b3f2fab399) | Mar 13, 2021 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [582965792d](https://linux-hardware.org/?probe=582965792d) | Mar 12, 2021 |
| ASRock        | H370M-ITX/ac                | Desktop     | [27c62d531a](https://linux-hardware.org/?probe=27c62d531a) | Mar 11, 2021 |
| Medion        | Akoya E7416                 | Notebook    | [310e7f2288](https://linux-hardware.org/?probe=310e7f2288) | Mar 11, 2021 |
| Lenovo        | ThinkPad L450 20DSS1G604    | Notebook    | [b38d404d64](https://linux-hardware.org/?probe=b38d404d64) | Mar 11, 2021 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [00cdb13890](https://linux-hardware.org/?probe=00cdb13890) | Mar 11, 2021 |
| Microsoft     | Surface Pro                 | Tablet      | [02f1e5b3f9](https://linux-hardware.org/?probe=02f1e5b3f9) | Mar 11, 2021 |
| Dell          | Latitude 7280               | Notebook    | [552b8e5250](https://linux-hardware.org/?probe=552b8e5250) | Mar 11, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [18ce3596d7](https://linux-hardware.org/?probe=18ce3596d7) | Mar 10, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [cb6eaf072a](https://linux-hardware.org/?probe=cb6eaf072a) | Mar 09, 2021 |
| Notebook      | NH55RGQ                     | Notebook    | [4d907831d6](https://linux-hardware.org/?probe=4d907831d6) | Mar 09, 2021 |
| Sony          | VPCEA36FG                   | Notebook    | [29422d1d98](https://linux-hardware.org/?probe=29422d1d98) | Mar 09, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [0b70f18f6d](https://linux-hardware.org/?probe=0b70f18f6d) | Mar 09, 2021 |
| Dell          | Latitude E6420              | Notebook    | [027c467458](https://linux-hardware.org/?probe=027c467458) | Mar 09, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [9df5a8eb64](https://linux-hardware.org/?probe=9df5a8eb64) | Mar 08, 2021 |
| Dell          | 08K0X7 A01                  | Desktop     | [95a6ea57e6](https://linux-hardware.org/?probe=95a6ea57e6) | Mar 08, 2021 |
| Gigabyte      | Z87-HD3                     | Desktop     | [661d1b585d](https://linux-hardware.org/?probe=661d1b585d) | Mar 07, 2021 |
| Medion        | P861X                       | Notebook    | [f163e14733](https://linux-hardware.org/?probe=f163e14733) | Mar 07, 2021 |
| ASUSTek       | K42Jc                       | Notebook    | [d21d838be1](https://linux-hardware.org/?probe=d21d838be1) | Mar 07, 2021 |
| AMD           | Armorhead CRB               | Desktop     | [5039edaecf](https://linux-hardware.org/?probe=5039edaecf) | Mar 07, 2021 |
| AMD           | Armorhead CRB               | Desktop     | [59cb66c6da](https://linux-hardware.org/?probe=59cb66c6da) | Mar 07, 2021 |
| HP            | 3048h                       | Desktop     | [27c3c8df0e](https://linux-hardware.org/?probe=27c3c8df0e) | Mar 07, 2021 |
| Dell          | 0C522T A01                  | Desktop     | [4871abab72](https://linux-hardware.org/?probe=4871abab72) | Mar 06, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [57bb9f146c](https://linux-hardware.org/?probe=57bb9f146c) | Mar 06, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [de7cd1f262](https://linux-hardware.org/?probe=de7cd1f262) | Mar 05, 2021 |
| Dell          | Inspiron 5420               | Notebook    | [11a466e06d](https://linux-hardware.org/?probe=11a466e06d) | Mar 05, 2021 |
| MSI           | Z97 GAMING 3                | Desktop     | [2e5166f59c](https://linux-hardware.org/?probe=2e5166f59c) | Mar 05, 2021 |
| Dell          | Latitude E6220              | Notebook    | [48df3fe508](https://linux-hardware.org/?probe=48df3fe508) | Mar 04, 2021 |
| ASUSTek       | P5B-MX                      | Desktop     | [0caf3ef9eb](https://linux-hardware.org/?probe=0caf3ef9eb) | Mar 04, 2021 |
| PC Special... | NS50MU                      | Notebook    | [bcaee8aeeb](https://linux-hardware.org/?probe=bcaee8aeeb) | Mar 04, 2021 |
| Medion        | P861X                       | Notebook    | [6b6562c621](https://linux-hardware.org/?probe=6b6562c621) | Mar 04, 2021 |
| MSI           | B75MA-P45                   | Desktop     | [9cfb1efab5](https://linux-hardware.org/?probe=9cfb1efab5) | Mar 04, 2021 |
| Timi          | TM1701                      | Notebook    | [a47b371c00](https://linux-hardware.org/?probe=a47b371c00) | Mar 03, 2021 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [881150ed50](https://linux-hardware.org/?probe=881150ed50) | Mar 03, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [8ebc8b06a5](https://linux-hardware.org/?probe=8ebc8b06a5) | Mar 03, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [13649ef673](https://linux-hardware.org/?probe=13649ef673) | Mar 03, 2021 |
| HP            | 0A98h                       | Desktop     | [0a7ab4d43e](https://linux-hardware.org/?probe=0a7ab4d43e) | Mar 03, 2021 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | Desktop     | [445a3c1e01](https://linux-hardware.org/?probe=445a3c1e01) | Mar 02, 2021 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [1afc152f2e](https://linux-hardware.org/?probe=1afc152f2e) | Mar 02, 2021 |
| Unknown       | Unknown                     | Notebook    | [327f8d1737](https://linux-hardware.org/?probe=327f8d1737) | Mar 02, 2021 |
| Unknown       | Unknown                     | Notebook    | [f134c85b61](https://linux-hardware.org/?probe=f134c85b61) | Mar 02, 2021 |
| Lenovo        | ThinkPad T420s 4174CN5      | Notebook    | [3cfc7cd94d](https://linux-hardware.org/?probe=3cfc7cd94d) | Mar 02, 2021 |
| Timi          | TM1701                      | Notebook    | [c82a03edc2](https://linux-hardware.org/?probe=c82a03edc2) | Mar 01, 2021 |
| HP            | Compaq nx7400 (EY294ET#A... | Notebook    | [b253d7d3fa](https://linux-hardware.org/?probe=b253d7d3fa) | Mar 01, 2021 |
| Acer          | Veriton X2611G V1.0         | Desktop     | [0f52aff29d](https://linux-hardware.org/?probe=0f52aff29d) | Feb 27, 2021 |
| Acer          | Veriton X2611G V1.0         | Desktop     | [ba907b59a6](https://linux-hardware.org/?probe=ba907b59a6) | Feb 27, 2021 |
| ZOTAC         | ZBOX-EN1070 Rev.00          | Mini pc     | [a080ca6ad4](https://linux-hardware.org/?probe=a080ca6ad4) | Feb 26, 2021 |
| HP            | Compaq 6510b (GR690ET#AB... | Notebook    | [b9b8fa550a](https://linux-hardware.org/?probe=b9b8fa550a) | Feb 26, 2021 |
| HP            | Compaq 6510b (GR690ET#AB... | Notebook    | [4529dc90b2](https://linux-hardware.org/?probe=4529dc90b2) | Feb 26, 2021 |
| HP            | EliteBook 850 G3            | Notebook    | [8f0cc7194c](https://linux-hardware.org/?probe=8f0cc7194c) | Feb 26, 2021 |
| Dell          | Latitude 5590               | Notebook    | [95fa6d8570](https://linux-hardware.org/?probe=95fa6d8570) | Feb 26, 2021 |
| Toshiba       | Satellite L650              | Notebook    | [e5fff439ec](https://linux-hardware.org/?probe=e5fff439ec) | Feb 26, 2021 |
| Medion        | P861X                       | Notebook    | [b2b7b32fe1](https://linux-hardware.org/?probe=b2b7b32fe1) | Feb 26, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [0752151d41](https://linux-hardware.org/?probe=0752151d41) | Feb 26, 2021 |
| PC Special... | NS50MU                      | Notebook    | [144fda6559](https://linux-hardware.org/?probe=144fda6559) | Feb 26, 2021 |
| PC Special... | NS50MU                      | Notebook    | [1f5f05239e](https://linux-hardware.org/?probe=1f5f05239e) | Feb 26, 2021 |
| Medion        | P861X                       | Notebook    | [ef45a1774d](https://linux-hardware.org/?probe=ef45a1774d) | Feb 26, 2021 |
| Clevo         | P65_P67SE                   | Notebook    | [0757e565d0](https://linux-hardware.org/?probe=0757e565d0) | Feb 25, 2021 |
| ASUSTek       | K75VM                       | Notebook    | [76b4457e58](https://linux-hardware.org/?probe=76b4457e58) | Feb 25, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [3defa02f89](https://linux-hardware.org/?probe=3defa02f89) | Feb 24, 2021 |
| Gigabyte      | M55S-S3                     | Desktop     | [0d4f758e92](https://linux-hardware.org/?probe=0d4f758e92) | Feb 24, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [ceb6b94413](https://linux-hardware.org/?probe=ceb6b94413) | Feb 23, 2021 |
| Apple         | MacBookPro11,3              | Notebook    | [c529114c36](https://linux-hardware.org/?probe=c529114c36) | Feb 23, 2021 |
| Apple         | MacBookPro11,3              | Notebook    | [c28a0de3f6](https://linux-hardware.org/?probe=c28a0de3f6) | Feb 23, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [d49e5b0303](https://linux-hardware.org/?probe=d49e5b0303) | Feb 23, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [290d20ab8b](https://linux-hardware.org/?probe=290d20ab8b) | Feb 23, 2021 |
| Gigabyte      | AX370-Gaming 5              | Desktop     | [20714e3850](https://linux-hardware.org/?probe=20714e3850) | Feb 22, 2021 |
| Gigabyte      | Z97X-UD3H-BK-CF             | Desktop     | [801ba81801](https://linux-hardware.org/?probe=801ba81801) | Feb 22, 2021 |
| Dell          | Studio 1747                 | Notebook    | [114730b64e](https://linux-hardware.org/?probe=114730b64e) | Feb 21, 2021 |
| ASUSTek       | A88XM-PLUS                  | Desktop     | [36132fe892](https://linux-hardware.org/?probe=36132fe892) | Feb 21, 2021 |
| HP            | ENVY Notebook               | Notebook    | [e4cc508565](https://linux-hardware.org/?probe=e4cc508565) | Feb 21, 2021 |
| Dell          | 0JJ7YG A00                  | Desktop     | [d068643fef](https://linux-hardware.org/?probe=d068643fef) | Feb 21, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [8afeeb9a4d](https://linux-hardware.org/?probe=8afeeb9a4d) | Feb 20, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [c4b8167be5](https://linux-hardware.org/?probe=c4b8167be5) | Feb 20, 2021 |
| Notebook      | P95_96_97Ex,Rx              | Notebook    | [b9a07cad35](https://linux-hardware.org/?probe=b9a07cad35) | Feb 20, 2021 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [b738509452](https://linux-hardware.org/?probe=b738509452) | Feb 20, 2021 |
| Dell          | Latitude 7420               | Convertible | [6b922f27d1](https://linux-hardware.org/?probe=6b922f27d1) | Feb 20, 2021 |
| ASRock        | B550M Pro4                  | Desktop     | [c076095afb](https://linux-hardware.org/?probe=c076095afb) | Feb 20, 2021 |
| Notebook      | P95_96_97Ex,Rx              | Notebook    | [4df1c636a1](https://linux-hardware.org/?probe=4df1c636a1) | Feb 20, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [7ce0cf2ddb](https://linux-hardware.org/?probe=7ce0cf2ddb) | Feb 19, 2021 |
| Acer          | Swift SF314-56G             | Notebook    | [57ee4960f6](https://linux-hardware.org/?probe=57ee4960f6) | Feb 19, 2021 |
| Dell          | Inspiron 1525               | Notebook    | [ccb2c058d2](https://linux-hardware.org/?probe=ccb2c058d2) | Feb 18, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [23c8d52843](https://linux-hardware.org/?probe=23c8d52843) | Feb 18, 2021 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [7e13ee8b5e](https://linux-hardware.org/?probe=7e13ee8b5e) | Feb 18, 2021 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [cd6b364d5c](https://linux-hardware.org/?probe=cd6b364d5c) | Feb 18, 2021 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [ebed50eedc](https://linux-hardware.org/?probe=ebed50eedc) | Feb 18, 2021 |
| HP            | 650                         | Notebook    | [1496183ef4](https://linux-hardware.org/?probe=1496183ef4) | Feb 17, 2021 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [7f41757cff](https://linux-hardware.org/?probe=7f41757cff) | Feb 17, 2021 |
| Gigabyte      | B85M-HD3                    | Desktop     | [84d70bc8d9](https://linux-hardware.org/?probe=84d70bc8d9) | Feb 17, 2021 |
| MSI           | G31TM-P21                   | Desktop     | [ad864ed4a7](https://linux-hardware.org/?probe=ad864ed4a7) | Feb 17, 2021 |
| Acer          | One S1002                   | Notebook    | [23688b2708](https://linux-hardware.org/?probe=23688b2708) | Feb 17, 2021 |
| Acer          | Aspire E1-531               | Notebook    | [73f0c23dcd](https://linux-hardware.org/?probe=73f0c23dcd) | Feb 16, 2021 |
| Insyde        | BayTrail                    | Notebook    | [90ffd16d35](https://linux-hardware.org/?probe=90ffd16d35) | Feb 16, 2021 |
| HP            | Notebook                    | Notebook    | [0102f95d55](https://linux-hardware.org/?probe=0102f95d55) | Feb 16, 2021 |
| Acer          | Aspire X3995                | Desktop     | [17cacbd59e](https://linux-hardware.org/?probe=17cacbd59e) | Feb 15, 2021 |
| ASUSTek       | X75A                        | Notebook    | [b7f386cb96](https://linux-hardware.org/?probe=b7f386cb96) | Feb 15, 2021 |
| Acer          | Aspire ES1-531              | Notebook    | [6bbbe6bd30](https://linux-hardware.org/?probe=6bbbe6bd30) | Feb 15, 2021 |
| ASUSTek       | X541UJ                      | Notebook    | [62cee7f93a](https://linux-hardware.org/?probe=62cee7f93a) | Feb 14, 2021 |
| ASUSTek       | X541UJ                      | Notebook    | [24109da610](https://linux-hardware.org/?probe=24109da610) | Feb 14, 2021 |
| MSI           | H81M-P33                    | Desktop     | [a242aae8f0](https://linux-hardware.org/?probe=a242aae8f0) | Feb 14, 2021 |
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [bbf8f212f1](https://linux-hardware.org/?probe=bbf8f212f1) | Feb 14, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [9caf272c25](https://linux-hardware.org/?probe=9caf272c25) | Feb 14, 2021 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [0e9296574f](https://linux-hardware.org/?probe=0e9296574f) | Feb 14, 2021 |
| ASUSTek       | ET1610PT                    | Desktop     | [cfd29dadc2](https://linux-hardware.org/?probe=cfd29dadc2) | Feb 14, 2021 |
| ASUSTek       | F5VL                        | Notebook    | [7610db0920](https://linux-hardware.org/?probe=7610db0920) | Feb 14, 2021 |
| Toshiba       | Satellite L850-14L          | Notebook    | [d37e16e595](https://linux-hardware.org/?probe=d37e16e595) | Feb 14, 2021 |
| ASUSTek       | X705NA                      | Notebook    | [681b624ddd](https://linux-hardware.org/?probe=681b624ddd) | Feb 13, 2021 |
| Intel         | DH55TC AAE70932-205         | Desktop     | [4b77473a07](https://linux-hardware.org/?probe=4b77473a07) | Feb 13, 2021 |
| Acer          | Extensa 5635Z               | Notebook    | [c1269f168e](https://linux-hardware.org/?probe=c1269f168e) | Feb 13, 2021 |
| ASUSTek       | K73E                        | Notebook    | [bd22570811](https://linux-hardware.org/?probe=bd22570811) | Feb 13, 2021 |
| ASUSTek       | K73E                        | Notebook    | [20fefaf2bb](https://linux-hardware.org/?probe=20fefaf2bb) | Feb 13, 2021 |
| Acer          | Aspire E5-773G              | Notebook    | [1abd616409](https://linux-hardware.org/?probe=1abd616409) | Feb 13, 2021 |
| ASUSTek       | PRIME Z490M-PLUS            | Desktop     | [b66d9aba5f](https://linux-hardware.org/?probe=b66d9aba5f) | Feb 13, 2021 |
| ZOTAC         | ZBOX-CI320NANO series Re... | Mini pc     | [81ecc97538](https://linux-hardware.org/?probe=81ecc97538) | Feb 13, 2021 |
| Acer          | Aspire E1-531               | Notebook    | [c7c9db803b](https://linux-hardware.org/?probe=c7c9db803b) | Feb 13, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [ff97cc5a5f](https://linux-hardware.org/?probe=ff97cc5a5f) | Feb 13, 2021 |
| ASUSTek       | ET1610PT                    | Desktop     | [46c0d18b91](https://linux-hardware.org/?probe=46c0d18b91) | Feb 13, 2021 |
| ASUSTek       | H81I-PLUS                   | Desktop     | [65a76fd75d](https://linux-hardware.org/?probe=65a76fd75d) | Feb 13, 2021 |
| HP            | ProBook 470 G3              | Notebook    | [0981049ac0](https://linux-hardware.org/?probe=0981049ac0) | Feb 12, 2021 |
| Acer          | Aspire X3995                | Desktop     | [0a74fd3993](https://linux-hardware.org/?probe=0a74fd3993) | Feb 12, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [ed1e90d31f](https://linux-hardware.org/?probe=ed1e90d31f) | Feb 12, 2021 |
| Toshiba       | Satellite C850-14X          | Notebook    | [73977134ff](https://linux-hardware.org/?probe=73977134ff) | Feb 12, 2021 |
| System76      | Lemur Pro                   | Notebook    | [fda0816588](https://linux-hardware.org/?probe=fda0816588) | Feb 12, 2021 |
| HP            | Pavilion dv5                | Notebook    | [5256bfbe63](https://linux-hardware.org/?probe=5256bfbe63) | Feb 12, 2021 |
| Toshiba       | Satellite L500              | Notebook    | [003b1f0799](https://linux-hardware.org/?probe=003b1f0799) | Feb 12, 2021 |
| Toshiba       | Satellite L500              | Notebook    | [a642972ffa](https://linux-hardware.org/?probe=a642972ffa) | Feb 12, 2021 |
| Acer          | Aspire E1-531               | Notebook    | [6818ad4fea](https://linux-hardware.org/?probe=6818ad4fea) | Feb 12, 2021 |
| Acer          | Aspire 7520                 | Notebook    | [eaf2861cd2](https://linux-hardware.org/?probe=eaf2861cd2) | Feb 11, 2021 |
| Acer          | Aspire 7520                 | Notebook    | [17161d338b](https://linux-hardware.org/?probe=17161d338b) | Feb 11, 2021 |
| Unknown       | Unknown                     | Notebook    | [b4f46a59c0](https://linux-hardware.org/?probe=b4f46a59c0) | Feb 10, 2021 |
| Unknown       | Unknown                     | Notebook    | [a8fca5b59d](https://linux-hardware.org/?probe=a8fca5b59d) | Feb 10, 2021 |
| Toshiba       | Satellite L350              | Notebook    | [0d808f968d](https://linux-hardware.org/?probe=0d808f968d) | Feb 10, 2021 |
| ASUSTek       | K55VM                       | Notebook    | [d1086456e9](https://linux-hardware.org/?probe=d1086456e9) | Feb 10, 2021 |
| Gigabyte      | H61MA-D3V                   | Desktop     | [316105fe11](https://linux-hardware.org/?probe=316105fe11) | Feb 09, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [7c2ef960b5](https://linux-hardware.org/?probe=7c2ef960b5) | Feb 09, 2021 |
| MSI           | A78M-E45                    | Desktop     | [4bf342433c](https://linux-hardware.org/?probe=4bf342433c) | Feb 09, 2021 |
| Gigabyte      | Z370 AORUS Gaming K3-CF     | Desktop     | [39720b4123](https://linux-hardware.org/?probe=39720b4123) | Feb 09, 2021 |
| Dell          | 0F96C8 A00                  | All in one  | [47041042c3](https://linux-hardware.org/?probe=47041042c3) | Feb 08, 2021 |
| Gigabyte      | Z97P-D3                     | Desktop     | [61688ec01d](https://linux-hardware.org/?probe=61688ec01d) | Feb 08, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [001a68d211](https://linux-hardware.org/?probe=001a68d211) | Feb 08, 2021 |
| HP            | EliteBook 2540p             | Notebook    | [833c1e8751](https://linux-hardware.org/?probe=833c1e8751) | Feb 08, 2021 |
| HP            | EliteBook 2540p             | Notebook    | [3ea6f66338](https://linux-hardware.org/?probe=3ea6f66338) | Feb 08, 2021 |
| MSI           | H87-G43 GAMING              | Desktop     | [c87c06fa30](https://linux-hardware.org/?probe=c87c06fa30) | Feb 07, 2021 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [71f376cf2c](https://linux-hardware.org/?probe=71f376cf2c) | Feb 07, 2021 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [e06cd7dcc1](https://linux-hardware.org/?probe=e06cd7dcc1) | Feb 07, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [f0a8cd5fb0](https://linux-hardware.org/?probe=f0a8cd5fb0) | Feb 07, 2021 |
| HP            | Compaq 6710b (KE121ET#AB... | Notebook    | [81884ad87c](https://linux-hardware.org/?probe=81884ad87c) | Feb 07, 2021 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [8bd48eef32](https://linux-hardware.org/?probe=8bd48eef32) | Feb 07, 2021 |
| ASUSTek       | LITHIUM                     | Desktop     | [78517932f6](https://linux-hardware.org/?probe=78517932f6) | Feb 07, 2021 |
| HP            | Pavilion g6                 | Notebook    | [e99adeae5d](https://linux-hardware.org/?probe=e99adeae5d) | Feb 06, 2021 |
| Sony          | VGN-AR71S                   | Notebook    | [a5c6539aca](https://linux-hardware.org/?probe=a5c6539aca) | Feb 05, 2021 |
| Gigabyte      | G33-DS3R                    | Desktop     | [380fca47e2](https://linux-hardware.org/?probe=380fca47e2) | Feb 05, 2021 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [f7337b0aef](https://linux-hardware.org/?probe=f7337b0aef) | Feb 05, 2021 |
| MSI           | G31TM-P21                   | Desktop     | [32a55d5e20](https://linux-hardware.org/?probe=32a55d5e20) | Feb 05, 2021 |
| ASUSTek       | M2A-VM HDMI                 | Desktop     | [bdc752e9c2](https://linux-hardware.org/?probe=bdc752e9c2) | Feb 05, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [9d077a104b](https://linux-hardware.org/?probe=9d077a104b) | Feb 04, 2021 |
| Supermicro    | X8DA3                       | Server      | [039bf2c96a](https://linux-hardware.org/?probe=039bf2c96a) | Feb 04, 2021 |
| Supermicro    | X8DA3                       | Server      | [3731f93e51](https://linux-hardware.org/?probe=3731f93e51) | Feb 04, 2021 |
| Toshiba       | Satellite C70-A             | Notebook    | [e5381ff276](https://linux-hardware.org/?probe=e5381ff276) | Feb 04, 2021 |
| Toshiba       | Satellite C70-A             | Notebook    | [b1927c3e27](https://linux-hardware.org/?probe=b1927c3e27) | Feb 04, 2021 |
| Dell          | Latitude E6420              | Notebook    | [e5eaf078fb](https://linux-hardware.org/?probe=e5eaf078fb) | Feb 03, 2021 |
| ASRock        | FM2A58M-HD+                 | Desktop     | [d629981b18](https://linux-hardware.org/?probe=d629981b18) | Feb 03, 2021 |
| Toshiba       | Satellite Pro A120          | Notebook    | [cdd1e92e16](https://linux-hardware.org/?probe=cdd1e92e16) | Feb 03, 2021 |
| Packard Be... | MCP73PVT-PM                 | Desktop     | [066559ea13](https://linux-hardware.org/?probe=066559ea13) | Feb 03, 2021 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [16a2447c65](https://linux-hardware.org/?probe=16a2447c65) | Feb 02, 2021 |
| Gigabyte      | H61M-D2H-USB3               | Desktop     | [e39393dcdb](https://linux-hardware.org/?probe=e39393dcdb) | Feb 02, 2021 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | Notebook    | [ac59e600a6](https://linux-hardware.org/?probe=ac59e600a6) | Feb 02, 2021 |
| Wortmann      | TERRA_PAD_1060              | Tablet      | [8f2478944c](https://linux-hardware.org/?probe=8f2478944c) | Feb 02, 2021 |
| MSI           | B450-A PRO MAX              | Desktop     | [0521e66a3f](https://linux-hardware.org/?probe=0521e66a3f) | Feb 01, 2021 |
| HP            | EliteBook 2560p             | Notebook    | [6541923c82](https://linux-hardware.org/?probe=6541923c82) | Feb 01, 2021 |
| HP            | EliteBook 840 G4            | Notebook    | [5de895acb9](https://linux-hardware.org/?probe=5de895acb9) | Jan 31, 2021 |
| Toshiba       | Satellite L850-14L          | Notebook    | [726ba236d8](https://linux-hardware.org/?probe=726ba236d8) | Jan 31, 2021 |
| Apple         | Mac-F2218FC8                | All in one  | [8a60d17e4e](https://linux-hardware.org/?probe=8a60d17e4e) | Jan 31, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [c8a843e815](https://linux-hardware.org/?probe=c8a843e815) | Jan 31, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [92b33844dc](https://linux-hardware.org/?probe=92b33844dc) | Jan 30, 2021 |
| ASUSTek       | P5KPL-AM EPU                | Desktop     | [9761a3446c](https://linux-hardware.org/?probe=9761a3446c) | Jan 30, 2021 |
| MSI           | B450-A PRO MAX              | Desktop     | [1e3b19bb06](https://linux-hardware.org/?probe=1e3b19bb06) | Jan 30, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [203f2abb14](https://linux-hardware.org/?probe=203f2abb14) | Jan 30, 2021 |
| MSI           | B350 PC MATE                | Desktop     | [2f5faaf22e](https://linux-hardware.org/?probe=2f5faaf22e) | Jan 29, 2021 |
| Toshiba       | Satellite L300              | Notebook    | [9b7beecf8b](https://linux-hardware.org/?probe=9b7beecf8b) | Jan 29, 2021 |
| Lenovo        | ThinkPad X270 20HMS0930J    | Notebook    | [e1e217471d](https://linux-hardware.org/?probe=e1e217471d) | Jan 29, 2021 |
| Acer          | Swift SF314-55              | Notebook    | [14e5a2a9f5](https://linux-hardware.org/?probe=14e5a2a9f5) | Jan 28, 2021 |
| Lenovo        | ThinkPad X270 20HMS0930J    | Notebook    | [b9e14ae3f2](https://linux-hardware.org/?probe=b9e14ae3f2) | Jan 28, 2021 |
| Estar         | BEAUTY HD Intel Quad cor... | Notebook    | [59c1597fbb](https://linux-hardware.org/?probe=59c1597fbb) | Jan 28, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [f32975549c](https://linux-hardware.org/?probe=f32975549c) | Jan 28, 2021 |
| Jumper        | EZpad                       | Tablet      | [ab39f4f442](https://linux-hardware.org/?probe=ab39f4f442) | Jan 28, 2021 |
| HP            | 250 G3                      | Notebook    | [19a1d2d008](https://linux-hardware.org/?probe=19a1d2d008) | Jan 28, 2021 |
| ASRock        | B550M-HDV                   | Desktop     | [91b6e1cb16](https://linux-hardware.org/?probe=91b6e1cb16) | Jan 28, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [dcefb0ec8f](https://linux-hardware.org/?probe=dcefb0ec8f) | Jan 28, 2021 |
| ASRock        | H55M Pro                    | Desktop     | [ab945b1fda](https://linux-hardware.org/?probe=ab945b1fda) | Jan 27, 2021 |
| HP            | ZBook 17 G6                 | Notebook    | [63c3d95bd5](https://linux-hardware.org/?probe=63c3d95bd5) | Jan 27, 2021 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | Notebook    | [f32f6f69f0](https://linux-hardware.org/?probe=f32f6f69f0) | Jan 26, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [6d86921fcf](https://linux-hardware.org/?probe=6d86921fcf) | Jan 26, 2021 |
| HP            | 843B                        | Desktop     | [4d87dc2b65](https://linux-hardware.org/?probe=4d87dc2b65) | Jan 25, 2021 |
| Dell          | Inspiron 7537               | Notebook    | [13f6a97193](https://linux-hardware.org/?probe=13f6a97193) | Jan 24, 2021 |
| Dell          | Inspiron 7537               | Notebook    | [7fdbfa0330](https://linux-hardware.org/?probe=7fdbfa0330) | Jan 24, 2021 |
| ASUSTek       | P9X79                       | Desktop     | [b96b88613a](https://linux-hardware.org/?probe=b96b88613a) | Jan 24, 2021 |
| MSI           | MS-7270                     | Desktop     | [9e5fa11934](https://linux-hardware.org/?probe=9e5fa11934) | Jan 24, 2021 |
| Dell          | Latitude E6430              | Notebook    | [f5bb578cc8](https://linux-hardware.org/?probe=f5bb578cc8) | Jan 24, 2021 |
| Microsoft     | Surface Pro 3               | Tablet      | [3d2863ffc2](https://linux-hardware.org/?probe=3d2863ffc2) | Jan 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [edf6b41ca7](https://linux-hardware.org/?probe=edf6b41ca7) | Jan 23, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [6fd25b9832](https://linux-hardware.org/?probe=6fd25b9832) | Jan 23, 2021 |
| Toshiba       | Satellite C70-A             | Notebook    | [a5bfecf081](https://linux-hardware.org/?probe=a5bfecf081) | Jan 23, 2021 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [bc781fb0f1](https://linux-hardware.org/?probe=bc781fb0f1) | Jan 23, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [b1f5eac9a6](https://linux-hardware.org/?probe=b1f5eac9a6) | Jan 23, 2021 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [47517be667](https://linux-hardware.org/?probe=47517be667) | Jan 23, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [9577ce9e95](https://linux-hardware.org/?probe=9577ce9e95) | Jan 23, 2021 |
| Dell          | 0D6H9T A01                  | Desktop     | [33d903fa91](https://linux-hardware.org/?probe=33d903fa91) | Jan 23, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [befc13b460](https://linux-hardware.org/?probe=befc13b460) | Jan 23, 2021 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [2c760a2055](https://linux-hardware.org/?probe=2c760a2055) | Jan 22, 2021 |
| ASUSTek       | H81I-PLUS                   | Desktop     | [cf3bc6aae7](https://linux-hardware.org/?probe=cf3bc6aae7) | Jan 22, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [ad0350b448](https://linux-hardware.org/?probe=ad0350b448) | Jan 21, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [1e5b1ac8ca](https://linux-hardware.org/?probe=1e5b1ac8ca) | Jan 21, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [bd5bdfd31f](https://linux-hardware.org/?probe=bd5bdfd31f) | Jan 21, 2021 |
| ASUSTek       | N53SV                       | Notebook    | [214cebc0cf](https://linux-hardware.org/?probe=214cebc0cf) | Jan 19, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [80243b8154](https://linux-hardware.org/?probe=80243b8154) | Jan 18, 2021 |
| Toshiba       | Satellite Pro C870-11R      | Notebook    | [7e95db6658](https://linux-hardware.org/?probe=7e95db6658) | Jan 18, 2021 |
| Toshiba       | Satellite Pro C870-11R      | Notebook    | [1f106a8eea](https://linux-hardware.org/?probe=1f106a8eea) | Jan 18, 2021 |
| Dell          | 03NVJ6 A03                  | Desktop     | [be3757c485](https://linux-hardware.org/?probe=be3757c485) | Jan 18, 2021 |
| Gigabyte      | B460M DS3H                  | Desktop     | [7c6d1576bc](https://linux-hardware.org/?probe=7c6d1576bc) | Jan 18, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [f25a998d4f](https://linux-hardware.org/?probe=f25a998d4f) | Jan 18, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [a09e6f3fc7](https://linux-hardware.org/?probe=a09e6f3fc7) | Jan 18, 2021 |
| MSI           | B550-A PRO                  | Desktop     | [19aff6f710](https://linux-hardware.org/?probe=19aff6f710) | Jan 16, 2021 |
| MSI           | B550-A PRO                  | Desktop     | [9b567554f4](https://linux-hardware.org/?probe=9b567554f4) | Jan 16, 2021 |
| Gigabyte      | Z97X-Gaming 5               | Desktop     | [62a6d2d0b8](https://linux-hardware.org/?probe=62a6d2d0b8) | Jan 15, 2021 |
| Google        | Panther                     | Desktop     | [f75d17f4a1](https://linux-hardware.org/?probe=f75d17f4a1) | Jan 15, 2021 |
| Lenovo        | ThinkPad T470 20HD000EMH    | Notebook    | [067312326b](https://linux-hardware.org/?probe=067312326b) | Jan 15, 2021 |
| Gigabyte      | Z370 AORUS Gaming K3-CF     | Desktop     | [de64a038f3](https://linux-hardware.org/?probe=de64a038f3) | Jan 15, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [866d489976](https://linux-hardware.org/?probe=866d489976) | Jan 15, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [c473e50c22](https://linux-hardware.org/?probe=c473e50c22) | Jan 15, 2021 |
| Microsoft     | Surface Pro                 | Tablet      | [f71ad79543](https://linux-hardware.org/?probe=f71ad79543) | Jan 14, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [a771572dc3](https://linux-hardware.org/?probe=a771572dc3) | Jan 14, 2021 |
| Apple         | MacBookPro8,2               | Notebook    | [8d99afdb6a](https://linux-hardware.org/?probe=8d99afdb6a) | Jan 14, 2021 |
| ZOTAC         | ZBOX-EN1070 Rev.00          | Mini pc     | [e9edea594f](https://linux-hardware.org/?probe=e9edea594f) | Jan 14, 2021 |
| MSI           | Z97M-G43                    | Desktop     | [65ae7ef0c9](https://linux-hardware.org/?probe=65ae7ef0c9) | Jan 14, 2021 |
| Microsoft     | Surface Pro 4               | Tablet      | [236d892a17](https://linux-hardware.org/?probe=236d892a17) | Jan 13, 2021 |
| Dell          | G7 7588                     | Notebook    | [d8a002c84f](https://linux-hardware.org/?probe=d8a002c84f) | Jan 13, 2021 |
| Toshiba       | All In One PC MP            | All in one  | [d1348b43e6](https://linux-hardware.org/?probe=d1348b43e6) | Jan 13, 2021 |
| Pegatron      | 2A73h                       | Desktop     | [0bd79433a3](https://linux-hardware.org/?probe=0bd79433a3) | Jan 13, 2021 |
| Acer          | Aspire VN7-792G             | Notebook    | [0b1c2de104](https://linux-hardware.org/?probe=0b1c2de104) | Jan 13, 2021 |
| Gigabyte      | B460M DS3H                  | Desktop     | [1f148c6329](https://linux-hardware.org/?probe=1f148c6329) | Jan 13, 2021 |
| Microsoft     | Surface Pro 4               | Tablet      | [a403d043dc](https://linux-hardware.org/?probe=a403d043dc) | Jan 13, 2021 |
| Microsoft     | Surface Pro 4               | Tablet      | [a5eb09f06e](https://linux-hardware.org/?probe=a5eb09f06e) | Jan 12, 2021 |
| HP            | 2240 1                      | Desktop     | [8d09c291c1](https://linux-hardware.org/?probe=8d09c291c1) | Jan 12, 2021 |
| ASUSTek       | Berkeley                    | Desktop     | [4db5f0b0aa](https://linux-hardware.org/?probe=4db5f0b0aa) | Jan 12, 2021 |
| MSI           | Prestige 15 A10SC           | Notebook    | [a9bca2911b](https://linux-hardware.org/?probe=a9bca2911b) | Jan 12, 2021 |
| HP            | Pavilion g6                 | Notebook    | [2132944e80](https://linux-hardware.org/?probe=2132944e80) | Jan 12, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [77514dd5e2](https://linux-hardware.org/?probe=77514dd5e2) | Jan 11, 2021 |
| ASUSTek       | N750JV                      | Notebook    | [cc980741ae](https://linux-hardware.org/?probe=cc980741ae) | Jan 11, 2021 |
| ASUSTek       | VM60                        | Desktop     | [d2c347340e](https://linux-hardware.org/?probe=d2c347340e) | Jan 11, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [5bf0c5ef4e](https://linux-hardware.org/?probe=5bf0c5ef4e) | Jan 11, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [ae2c1ae2d1](https://linux-hardware.org/?probe=ae2c1ae2d1) | Jan 10, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [dd96b6cc50](https://linux-hardware.org/?probe=dd96b6cc50) | Jan 10, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a88caa73f3](https://linux-hardware.org/?probe=a88caa73f3) | Jan 10, 2021 |
| Apple         | MacBookPro8,2               | Notebook    | [cd809823f0](https://linux-hardware.org/?probe=cd809823f0) | Jan 10, 2021 |
| Apple         | MacBookPro8,2               | Notebook    | [1bf59f534a](https://linux-hardware.org/?probe=1bf59f534a) | Jan 10, 2021 |
| MSI           | B450 GAMING PRO CARBON M... | Desktop     | [920bde8fca](https://linux-hardware.org/?probe=920bde8fca) | Jan 09, 2021 |
| MSI           | A78M-E45                    | Desktop     | [fd2b198e3b](https://linux-hardware.org/?probe=fd2b198e3b) | Jan 09, 2021 |
| ASUSTek       | X553MA                      | Notebook    | [a8dacfffee](https://linux-hardware.org/?probe=a8dacfffee) | Jan 09, 2021 |
| MiPi PC       | Mini PC                     | Mini pc     | [e2f9dbb383](https://linux-hardware.org/?probe=e2f9dbb383) | Jan 09, 2021 |
| Acer          | WMCP78M                     | Desktop     | [b942b5fb12](https://linux-hardware.org/?probe=b942b5fb12) | Jan 09, 2021 |
| ASRock        | N68C-GS4 FX                 | Desktop     | [4ceac56e05](https://linux-hardware.org/?probe=4ceac56e05) | Jan 09, 2021 |
| ASRock        | N68C-GS4 FX                 | Desktop     | [20d5511b5f](https://linux-hardware.org/?probe=20d5511b5f) | Jan 09, 2021 |
| MSI           | G41M-P28                    | Desktop     | [fd37a435f8](https://linux-hardware.org/?probe=fd37a435f8) | Jan 09, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [781971121a](https://linux-hardware.org/?probe=781971121a) | Jan 09, 2021 |
| ASRock        | B75 Pro3-M                  | Desktop     | [e514f058fe](https://linux-hardware.org/?probe=e514f058fe) | Jan 08, 2021 |
| Dell          | 0R849J A00                  | Desktop     | [09a2b418d2](https://linux-hardware.org/?probe=09a2b418d2) | Jan 08, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [0b7c80f593](https://linux-hardware.org/?probe=0b7c80f593) | Jan 07, 2021 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | Notebook    | [cccd6e2d9f](https://linux-hardware.org/?probe=cccd6e2d9f) | Jan 07, 2021 |
| MSI           | B85-G43 GAMING              | Desktop     | [db6ce0d0e4](https://linux-hardware.org/?probe=db6ce0d0e4) | Jan 07, 2021 |
| HP            | 0B4Ch D                     | Desktop     | [1cf9b4e160](https://linux-hardware.org/?probe=1cf9b4e160) | Jan 06, 2021 |
| Fujitsu Si... | D2812-A1 S26361-D2812-A1    | Desktop     | [2e6d1bb521](https://linux-hardware.org/?probe=2e6d1bb521) | Jan 06, 2021 |
| Fujitsu Si... | D2812-A1 S26361-D2812-A1    | Desktop     | [f371c46d8c](https://linux-hardware.org/?probe=f371c46d8c) | Jan 06, 2021 |
| HP            | Pavilion dv6                | Notebook    | [f7f371d643](https://linux-hardware.org/?probe=f7f371d643) | Jan 05, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [5a90cd5b0f](https://linux-hardware.org/?probe=5a90cd5b0f) | Jan 05, 2021 |
| Gigabyte      | B75M-D3V                    | Desktop     | [29a9e9dd7a](https://linux-hardware.org/?probe=29a9e9dd7a) | Jan 04, 2021 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [17344d5408](https://linux-hardware.org/?probe=17344d5408) | Jan 04, 2021 |
| Packard Be... | Veriton M275                | Desktop     | [6ab8bf0485](https://linux-hardware.org/?probe=6ab8bf0485) | Jan 04, 2021 |
| ASRock        | X570 Phantom Gaming-ITX/... | Desktop     | [f3e397ac96](https://linux-hardware.org/?probe=f3e397ac96) | Jan 04, 2021 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [3d8c62e8fe](https://linux-hardware.org/?probe=3d8c62e8fe) | Jan 04, 2021 |
| MSI           | B85-G43 GAMING              | Desktop     | [8fe013f04a](https://linux-hardware.org/?probe=8fe013f04a) | Jan 04, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [a9379157cd](https://linux-hardware.org/?probe=a9379157cd) | Jan 03, 2021 |
| Medion        | MS-7848                     | Desktop     | [e845ea11e1](https://linux-hardware.org/?probe=e845ea11e1) | Jan 03, 2021 |
| Dell          | Inspiron 5720               | Notebook    | [5b3ea29f87](https://linux-hardware.org/?probe=5b3ea29f87) | Jan 03, 2021 |
| HP            | EliteBook 2730p             | Notebook    | [e0f107c8be](https://linux-hardware.org/?probe=e0f107c8be) | Jan 03, 2021 |
| PEAQ          | PMM C1010-I01NL MD99337     | Notebook    | [33f6e6e450](https://linux-hardware.org/?probe=33f6e6e450) | Jan 02, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [52ce3be58a](https://linux-hardware.org/?probe=52ce3be58a) | Jan 02, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [1483935c23](https://linux-hardware.org/?probe=1483935c23) | Jan 02, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [3ecb2794ed](https://linux-hardware.org/?probe=3ecb2794ed) | Jan 02, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [c49aa2f880](https://linux-hardware.org/?probe=c49aa2f880) | Jan 02, 2021 |
| MSI           | G41M-P28                    | Desktop     | [44ae201a42](https://linux-hardware.org/?probe=44ae201a42) | Jan 02, 2021 |
| Dell          | Latitude E6420              | Notebook    | [8d40249c4e](https://linux-hardware.org/?probe=8d40249c4e) | Jan 01, 2021 |
| HP            | EliteBook 2730p             | Notebook    | [699bdefe63](https://linux-hardware.org/?probe=699bdefe63) | Jan 01, 2021 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [2b9d1a410c](https://linux-hardware.org/?probe=2b9d1a410c) | Dec 31, 2020 |
| MSI           | Z97M-G43                    | Desktop     | [b56961504d](https://linux-hardware.org/?probe=b56961504d) | Dec 31, 2020 |
| Samsung       | 900X3C/900X3D/900X4C/900... | Notebook    | [492bf814a7](https://linux-hardware.org/?probe=492bf814a7) | Dec 31, 2020 |
| MSI           | Z97M-G43                    | Desktop     | [5910fdd202](https://linux-hardware.org/?probe=5910fdd202) | Dec 31, 2020 |
| ASUSTek       | GL502VSK                    | Notebook    | [0d9dea21ba](https://linux-hardware.org/?probe=0d9dea21ba) | Dec 31, 2020 |
| Samsung       | 300E4A/300E5A/300E7A        | Notebook    | [a8028340ae](https://linux-hardware.org/?probe=a8028340ae) | Dec 31, 2020 |
| MSI           | MAG B550M MORTAR            | Desktop     | [62695e050c](https://linux-hardware.org/?probe=62695e050c) | Dec 29, 2020 |
| HP            | Laptop 15-db0xxx            | Notebook    | [f430118e5a](https://linux-hardware.org/?probe=f430118e5a) | Dec 29, 2020 |
| Gigabyte      | B450M DS3H-CF               | Notebook    | [b9c02872aa](https://linux-hardware.org/?probe=b9c02872aa) | Dec 29, 2020 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [c775fa1cd5](https://linux-hardware.org/?probe=c775fa1cd5) | Dec 29, 2020 |
| ASUSTek       | P8Z77-I DELUXE              | Desktop     | [188b144bf8](https://linux-hardware.org/?probe=188b144bf8) | Dec 29, 2020 |
| Dell          | Inspiron 1545               | Notebook    | [690ebfdf8f](https://linux-hardware.org/?probe=690ebfdf8f) | Dec 28, 2020 |
| Dell          | Vostro 3360                 | Notebook    | [86c9d529ee](https://linux-hardware.org/?probe=86c9d529ee) | Dec 28, 2020 |
| Dell          | XPS L521X                   | Notebook    | [c109644955](https://linux-hardware.org/?probe=c109644955) | Dec 28, 2020 |
| ASUSTek       | P8H67                       | Desktop     | [da589a4e39](https://linux-hardware.org/?probe=da589a4e39) | Dec 28, 2020 |
| Lenovo        | ThinkPad P43s 20RHCTO1WW    | Notebook    | [1e6d6813b9](https://linux-hardware.org/?probe=1e6d6813b9) | Dec 28, 2020 |
| ASUSTek       | P8H67                       | Desktop     | [f7049a20a9](https://linux-hardware.org/?probe=f7049a20a9) | Dec 28, 2020 |
| Medion        | Z370H4-EM                   | Desktop     | [74aa93009c](https://linux-hardware.org/?probe=74aa93009c) | Dec 28, 2020 |
| Dell          | 0GXM1W A04                  | Desktop     | [989f983b51](https://linux-hardware.org/?probe=989f983b51) | Dec 28, 2020 |
| HP            | EliteBook Folio 9470m       | Notebook    | [9df1bba9f4](https://linux-hardware.org/?probe=9df1bba9f4) | Dec 27, 2020 |
| Dell          | 03NVJ6 A03                  | Desktop     | [5f73d09607](https://linux-hardware.org/?probe=5f73d09607) | Dec 27, 2020 |
| Dell          | 03NVJ6 A03                  | Desktop     | [416b042b63](https://linux-hardware.org/?probe=416b042b63) | Dec 27, 2020 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [3d02ccd633](https://linux-hardware.org/?probe=3d02ccd633) | Dec 27, 2020 |
| Lenovo        | ThinkPad T480 20L6S29D07    | Notebook    | [b29aa67573](https://linux-hardware.org/?probe=b29aa67573) | Dec 27, 2020 |
| HP            | Pavilion g6                 | Notebook    | [a2f441222a](https://linux-hardware.org/?probe=a2f441222a) | Dec 26, 2020 |
| ASUSTek       | ZenBook UX434FLC_UX434FL    | Notebook    | [5b174411b3](https://linux-hardware.org/?probe=5b174411b3) | Dec 26, 2020 |
| Acer          | Aspire V3-574G              | Notebook    | [0d6f471bad](https://linux-hardware.org/?probe=0d6f471bad) | Dec 26, 2020 |
| MSI           | MAG B550M MORTAR            | Desktop     | [3bbb320076](https://linux-hardware.org/?probe=3bbb320076) | Dec 26, 2020 |
| ASRock        | FM2A58M-HD+                 | Desktop     | [cd038bd21f](https://linux-hardware.org/?probe=cd038bd21f) | Dec 26, 2020 |
| MSI           | MAG B550M MORTAR            | Desktop     | [962c03c577](https://linux-hardware.org/?probe=962c03c577) | Dec 26, 2020 |
| Dell          | 0M3849                      | Desktop     | [b3f8c202e6](https://linux-hardware.org/?probe=b3f8c202e6) | Dec 26, 2020 |
| Dell          | 0M3849                      | Desktop     | [d7fa6537a1](https://linux-hardware.org/?probe=d7fa6537a1) | Dec 26, 2020 |
| Notebook      | NH50_70RH                   | Notebook    | [17b9e17199](https://linux-hardware.org/?probe=17b9e17199) | Dec 25, 2020 |
| Dell          | 0HN7XN A01                  | Desktop     | [4056bb2a7a](https://linux-hardware.org/?probe=4056bb2a7a) | Dec 25, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [9f73be02e9](https://linux-hardware.org/?probe=9f73be02e9) | Dec 24, 2020 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Notebook    | [94da6e09db](https://linux-hardware.org/?probe=94da6e09db) | Dec 24, 2020 |
| Gigabyte      | B450M DS3H-CF               | Notebook    | [d2701aa534](https://linux-hardware.org/?probe=d2701aa534) | Dec 24, 2020 |
| ASUSTek       | ZenBook UX434FLC_UX434FL    | Notebook    | [f1ae9f4de0](https://linux-hardware.org/?probe=f1ae9f4de0) | Dec 24, 2020 |
| HPE           | ProLiant MicroServer Gen... | Server      | [56e685a6f9](https://linux-hardware.org/?probe=56e685a6f9) | Dec 24, 2020 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [efee113ead](https://linux-hardware.org/?probe=efee113ead) | Dec 24, 2020 |
| HP            | 8767 A                      | Desktop     | [8f872e22d2](https://linux-hardware.org/?probe=8f872e22d2) | Dec 23, 2020 |
| Medion        | B360H4-EM V1.0              | Desktop     | [d3136c1071](https://linux-hardware.org/?probe=d3136c1071) | Dec 23, 2020 |
| Raspberry ... | Raspberry Pi                | Soc         | [e5ed3ce077](https://linux-hardware.org/?probe=e5ed3ce077) | Dec 23, 2020 |
| ASUSTek       | N76VJ                       | Notebook    | [0e32d22b62](https://linux-hardware.org/?probe=0e32d22b62) | Dec 22, 2020 |
| MSI           | PS63 Modern 8RC             | Notebook    | [443a2a6be0](https://linux-hardware.org/?probe=443a2a6be0) | Dec 22, 2020 |
| ASUSTek       | K73E                        | Notebook    | [3173159735](https://linux-hardware.org/?probe=3173159735) | Dec 22, 2020 |
| ASUSTek       | K52JT                       | Notebook    | [e6da2dae88](https://linux-hardware.org/?probe=e6da2dae88) | Dec 22, 2020 |
| HP            | ZBook 17                    | Notebook    | [a931da71a8](https://linux-hardware.org/?probe=a931da71a8) | Dec 22, 2020 |
| Dell          | XPS M1330                   | Notebook    | [2a99154233](https://linux-hardware.org/?probe=2a99154233) | Dec 22, 2020 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [4d8ae624b5](https://linux-hardware.org/?probe=4d8ae624b5) | Dec 22, 2020 |
| Dell          | Latitude E6430              | Notebook    | [ff1b9b54b8](https://linux-hardware.org/?probe=ff1b9b54b8) | Dec 21, 2020 |
| Acer          | Veriton X4640G V:1.1        | Desktop     | [8a65f68e82](https://linux-hardware.org/?probe=8a65f68e82) | Dec 21, 2020 |
| ASUSTek       | N76VJ                       | Notebook    | [abd4959e3f](https://linux-hardware.org/?probe=abd4959e3f) | Dec 21, 2020 |
| HP            | 8767 A                      | Desktop     | [8197cd2a3e](https://linux-hardware.org/?probe=8197cd2a3e) | Dec 21, 2020 |
| ASRock        | H81M-GL                     | Desktop     | [218126d732](https://linux-hardware.org/?probe=218126d732) | Dec 21, 2020 |
| Dell          | Latitude 3160               | Notebook    | [8d6b0a7484](https://linux-hardware.org/?probe=8d6b0a7484) | Dec 21, 2020 |
| HP            | Pavilion g6                 | Notebook    | [9149b8cc4f](https://linux-hardware.org/?probe=9149b8cc4f) | Dec 21, 2020 |
| MSI           | Z270-A PRO                  | Desktop     | [ebf927d0a8](https://linux-hardware.org/?probe=ebf927d0a8) | Dec 21, 2020 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [aeaa55d759](https://linux-hardware.org/?probe=aeaa55d759) | Dec 21, 2020 |
| Apple         | MacBookPro8,1               | Notebook    | [aa3e4ca9f5](https://linux-hardware.org/?probe=aa3e4ca9f5) | Dec 20, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [01f4c5a26d](https://linux-hardware.org/?probe=01f4c5a26d) | Dec 20, 2020 |
| Dell          | Latitude 3550               | Notebook    | [a04f3a171a](https://linux-hardware.org/?probe=a04f3a171a) | Dec 20, 2020 |
| Packard Be... | EasyNote_SJ51               | Notebook    | [1b681621b8](https://linux-hardware.org/?probe=1b681621b8) | Dec 19, 2020 |
| MSI           | Z97 GAMING 3                | Desktop     | [6e4b2c6326](https://linux-hardware.org/?probe=6e4b2c6326) | Dec 19, 2020 |
| Acer          | Nitro AN515-52              | Notebook    | [b9668982a0](https://linux-hardware.org/?probe=b9668982a0) | Dec 19, 2020 |
| Dell          | Inspiron 7537               | Notebook    | [e9a1e6063b](https://linux-hardware.org/?probe=e9a1e6063b) | Dec 19, 2020 |
| Acer          | Nitro AN515-52              | Notebook    | [040fca4445](https://linux-hardware.org/?probe=040fca4445) | Dec 19, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [244e92ab75](https://linux-hardware.org/?probe=244e92ab75) | Dec 19, 2020 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [7ab44a96a1](https://linux-hardware.org/?probe=7ab44a96a1) | Dec 18, 2020 |
| ASRock        | H310CM-ITX/ac               | Desktop     | [441ecf536e](https://linux-hardware.org/?probe=441ecf536e) | Dec 18, 2020 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [d4f30fc8ce](https://linux-hardware.org/?probe=d4f30fc8ce) | Dec 18, 2020 |
| MSI           | B150M BAZOOKA               | Desktop     | [dd32b9e41e](https://linux-hardware.org/?probe=dd32b9e41e) | Dec 18, 2020 |
| HP            | ZBook 17 G6                 | Notebook    | [94594a968a](https://linux-hardware.org/?probe=94594a968a) | Dec 17, 2020 |
| ASUSTek       | B85M-G                      | Desktop     | [b35c4ecd4c](https://linux-hardware.org/?probe=b35c4ecd4c) | Dec 17, 2020 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [ad16b0aefe](https://linux-hardware.org/?probe=ad16b0aefe) | Dec 17, 2020 |
| ASUSTek       | VM60                        | Desktop     | [fba63481f8](https://linux-hardware.org/?probe=fba63481f8) | Dec 17, 2020 |
| Apple         | MacBookPro14,1              | Notebook    | [16916f679a](https://linux-hardware.org/?probe=16916f679a) | Dec 17, 2020 |
| ASRock        | H310CM-ITX/ac               | Desktop     | [ad2314503d](https://linux-hardware.org/?probe=ad2314503d) | Dec 17, 2020 |
| HP            | ZBook 17 G6                 | Notebook    | [d253ffd0f9](https://linux-hardware.org/?probe=d253ffd0f9) | Dec 16, 2020 |
| Lenovo        | IdeaPad 330-17AST 81D7      | Notebook    | [d85c828c73](https://linux-hardware.org/?probe=d85c828c73) | Dec 16, 2020 |
| Dell          | Inspiron 3521               | Notebook    | [aefa168b04](https://linux-hardware.org/?probe=aefa168b04) | Dec 16, 2020 |
| Dell          | Latitude 7300               | Notebook    | [07ee4ec79c](https://linux-hardware.org/?probe=07ee4ec79c) | Dec 16, 2020 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [f3c803e537](https://linux-hardware.org/?probe=f3c803e537) | Dec 16, 2020 |
| HP            | 250 G1                      | Notebook    | [7d28ed7dd9](https://linux-hardware.org/?probe=7d28ed7dd9) | Dec 15, 2020 |
| HP            | Compaq 6710b (KE121ET#AB... | Notebook    | [06f85ea2e5](https://linux-hardware.org/?probe=06f85ea2e5) | Dec 15, 2020 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [20e30ae2de](https://linux-hardware.org/?probe=20e30ae2de) | Dec 15, 2020 |
| MSI           | B450M MORTAR MAX            | Desktop     | [72bb4c14cb](https://linux-hardware.org/?probe=72bb4c14cb) | Dec 14, 2020 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [0098c9b9df](https://linux-hardware.org/?probe=0098c9b9df) | Dec 14, 2020 |
| Notebook      | NL5xRU                      | Notebook    | [1ce919a3e5](https://linux-hardware.org/?probe=1ce919a3e5) | Dec 14, 2020 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [72c36533be](https://linux-hardware.org/?probe=72c36533be) | Dec 14, 2020 |
| Notebook      | NL5xRU                      | Notebook    | [c2f10e5702](https://linux-hardware.org/?probe=c2f10e5702) | Dec 14, 2020 |
| HP            | EliteBook 8460p             | Notebook    | [95ab4572a0](https://linux-hardware.org/?probe=95ab4572a0) | Dec 14, 2020 |
| Intel         | NUC7i3BNB J22859-313        | Mini pc     | [0ed5a6345e](https://linux-hardware.org/?probe=0ed5a6345e) | Dec 14, 2020 |
| ASUSTek       | P6T DELUXE                  | Desktop     | [8c9d0043e2](https://linux-hardware.org/?probe=8c9d0043e2) | Dec 13, 2020 |
| MSI           | GP62M 7RDX                  | Notebook    | [83f38dcecb](https://linux-hardware.org/?probe=83f38dcecb) | Dec 13, 2020 |
| Dell          | Inspiron 15-3552            | Notebook    | [52a8ee00b5](https://linux-hardware.org/?probe=52a8ee00b5) | Dec 13, 2020 |
| HP            | Pavilion g6                 | Notebook    | [9704fac062](https://linux-hardware.org/?probe=9704fac062) | Dec 13, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [9df5886310](https://linux-hardware.org/?probe=9df5886310) | Dec 12, 2020 |
| MSI           | G31TM-P21                   | Desktop     | [f2c2f603ce](https://linux-hardware.org/?probe=f2c2f603ce) | Dec 12, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [c02041f2c7](https://linux-hardware.org/?probe=c02041f2c7) | Dec 12, 2020 |
| Medion        | P7612                       | Notebook    | [4a528affeb](https://linux-hardware.org/?probe=4a528affeb) | Dec 12, 2020 |
| Acer          | Aspire A515-51G             | Notebook    | [d93841255d](https://linux-hardware.org/?probe=d93841255d) | Dec 12, 2020 |
| Acer          | Aspire V5-123               | Notebook    | [3fd99c398f](https://linux-hardware.org/?probe=3fd99c398f) | Dec 12, 2020 |
| HP            | ZBook 15 G6                 | Notebook    | [718d464d73](https://linux-hardware.org/?probe=718d464d73) | Dec 11, 2020 |
| ASUSTek       | P5QD TURBO                  | Desktop     | [5fa9477ba3](https://linux-hardware.org/?probe=5fa9477ba3) | Dec 11, 2020 |
| ASUSTek       | P5QD TURBO                  | Desktop     | [9f8c1a298a](https://linux-hardware.org/?probe=9f8c1a298a) | Dec 11, 2020 |
| Acer          | Aspire 5735                 | Notebook    | [8e251a6942](https://linux-hardware.org/?probe=8e251a6942) | Dec 10, 2020 |
| Acer          | Aspire V5-123               | Notebook    | [c9d15f9341](https://linux-hardware.org/?probe=c9d15f9341) | Dec 10, 2020 |
| Dell          | XPS 17 9700                 | Notebook    | [f40de39846](https://linux-hardware.org/?probe=f40de39846) | Dec 10, 2020 |
| Dell          | XPS 17 9700                 | Notebook    | [7dfab28acb](https://linux-hardware.org/?probe=7dfab28acb) | Dec 10, 2020 |
| Lenovo        | G70-70 80HW007LNX           | Notebook    | [f377016464](https://linux-hardware.org/?probe=f377016464) | Dec 09, 2020 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [e4ea0cc463](https://linux-hardware.org/?probe=e4ea0cc463) | Dec 09, 2020 |
| Lenovo        | Z50-70 20354                | Notebook    | [588130295d](https://linux-hardware.org/?probe=588130295d) | Dec 08, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [9b23b69040](https://linux-hardware.org/?probe=9b23b69040) | Dec 08, 2020 |
| HP            | ProBook 450 G3              | Notebook    | [68d5e14ae0](https://linux-hardware.org/?probe=68d5e14ae0) | Dec 08, 2020 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [a138dbf3ac](https://linux-hardware.org/?probe=a138dbf3ac) | Dec 08, 2020 |
| Biostar       | A880G+                      | Desktop     | [90d4449293](https://linux-hardware.org/?probe=90d4449293) | Dec 08, 2020 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [9efe0dd098](https://linux-hardware.org/?probe=9efe0dd098) | Dec 08, 2020 |
| HP            | 18E9                        | Desktop     | [72c2d9d600](https://linux-hardware.org/?probe=72c2d9d600) | Dec 07, 2020 |
| Lenovo        | 1051L 60073                 | Tablet      | [6309af4b59](https://linux-hardware.org/?probe=6309af4b59) | Dec 06, 2020 |
| Insyde        | CherryTrail                 | Notebook    | [9820f25f9c](https://linux-hardware.org/?probe=9820f25f9c) | Dec 06, 2020 |
| HP            | ProBook 450 G3              | Notebook    | [a2e08c9405](https://linux-hardware.org/?probe=a2e08c9405) | Dec 06, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [95b4bf9004](https://linux-hardware.org/?probe=95b4bf9004) | Dec 06, 2020 |
| HP            | Pavilion g6                 | Notebook    | [8daab67fa2](https://linux-hardware.org/?probe=8daab67fa2) | Dec 06, 2020 |
| HP            | 1497                        | Desktop     | [ad8270246c](https://linux-hardware.org/?probe=ad8270246c) | Dec 05, 2020 |
| Acer          | Spin SP513-54N              | Convertible | [842edc9a76](https://linux-hardware.org/?probe=842edc9a76) | Dec 05, 2020 |
| Acer          | FMP55                       | Desktop     | [7836ab23f2](https://linux-hardware.org/?probe=7836ab23f2) | Dec 04, 2020 |
| HP            | 18E9                        | Desktop     | [de8a5b56d9](https://linux-hardware.org/?probe=de8a5b56d9) | Dec 04, 2020 |
| HP            | 212B                        | Desktop     | [1f35323dc0](https://linux-hardware.org/?probe=1f35323dc0) | Dec 04, 2020 |
| Dell          | XPS 15 9570                 | Notebook    | [a87f057c6a](https://linux-hardware.org/?probe=a87f057c6a) | Dec 04, 2020 |
| ASUSTek       | Hematite                    | Desktop     | [92eba910df](https://linux-hardware.org/?probe=92eba910df) | Dec 04, 2020 |
| ASRock        | X370 Pro4                   | Desktop     | [accfe08fcf](https://linux-hardware.org/?probe=accfe08fcf) | Dec 03, 2020 |
| Dell          | XPS 13 9380                 | Notebook    | [12eca6d5e6](https://linux-hardware.org/?probe=12eca6d5e6) | Dec 03, 2020 |
| Dell          | XPS 13 9380                 | Notebook    | [3966da77f8](https://linux-hardware.org/?probe=3966da77f8) | Dec 03, 2020 |
| ASRock        | H110M-STX/COM               | Desktop     | [64b456b069](https://linux-hardware.org/?probe=64b456b069) | Dec 03, 2020 |
| Pegatron      | VIOLET                      | Desktop     | [d3bb4bd97a](https://linux-hardware.org/?probe=d3bb4bd97a) | Dec 03, 2020 |
| Apple         | Mac-F2268CC8                | All in one  | [3ded0e3135](https://linux-hardware.org/?probe=3ded0e3135) | Dec 03, 2020 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [b9c5f5fd4f](https://linux-hardware.org/?probe=b9c5f5fd4f) | Dec 02, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [7ef37d3b67](https://linux-hardware.org/?probe=7ef37d3b67) | Dec 02, 2020 |
| HP            | Pavilion g6                 | Notebook    | [12028704e4](https://linux-hardware.org/?probe=12028704e4) | Dec 02, 2020 |
| ASUSTek       | N750JV                      | Notebook    | [c53109e741](https://linux-hardware.org/?probe=c53109e741) | Dec 02, 2020 |
| Medion        | Cattle24 1M                 | Desktop     | [61f840f162](https://linux-hardware.org/?probe=61f840f162) | Dec 02, 2020 |
| Lenovo        | ThinkPad T400 2768G17       | Notebook    | [7fe76b1b56](https://linux-hardware.org/?probe=7fe76b1b56) | Dec 01, 2020 |
| Lenovo        | ThinkPad T400 2768G17       | Notebook    | [f34a6172e5](https://linux-hardware.org/?probe=f34a6172e5) | Dec 01, 2020 |
| Acer          | EM61SM/EM61PM               | Desktop     | [3ef5d8d387](https://linux-hardware.org/?probe=3ef5d8d387) | Dec 01, 2020 |
| Dell          | Latitude E6430              | Notebook    | [ebcf4f0d5f](https://linux-hardware.org/?probe=ebcf4f0d5f) | Dec 01, 2020 |
| HPE           | ProLiant MicroServer Gen... | Server      | [406553ffd4](https://linux-hardware.org/?probe=406553ffd4) | Dec 01, 2020 |
| Intel         | NUC8i7HVB J68196-503        | Mini pc     | [50e2f6d7bf](https://linux-hardware.org/?probe=50e2f6d7bf) | Dec 01, 2020 |
| Dell          | XPS 13 9310                 | Notebook    | [ba53f6e513](https://linux-hardware.org/?probe=ba53f6e513) | Dec 01, 2020 |
| Acer          | Aspire ES1-511              | Notebook    | [6b1a6c1d81](https://linux-hardware.org/?probe=6b1a6c1d81) | Dec 01, 2020 |
| MSI           | B350 PC MATE                | Desktop     | [da50ee97cf](https://linux-hardware.org/?probe=da50ee97cf) | Dec 01, 2020 |
| NEXCOM        | NSA3110 B                   | Desktop     | [5da8a8bcdf](https://linux-hardware.org/?probe=5da8a8bcdf) | Nov 30, 2020 |
| Toshiba       | Satellite L50D-B            | Notebook    | [2b270faac1](https://linux-hardware.org/?probe=2b270faac1) | Nov 30, 2020 |
| HP            | EliteBook Folio 9470m       | Notebook    | [b3ff293458](https://linux-hardware.org/?probe=b3ff293458) | Nov 29, 2020 |
| HP            | EliteBook Folio 9470m       | Notebook    | [5d18fe2e3f](https://linux-hardware.org/?probe=5d18fe2e3f) | Nov 29, 2020 |
| Toshiba       | Satellite P50-A-12P         | Notebook    | [d8d0c804d1](https://linux-hardware.org/?probe=d8d0c804d1) | Nov 29, 2020 |
| Toshiba       | Satellite P50-A-12P         | Notebook    | [209cefb8da](https://linux-hardware.org/?probe=209cefb8da) | Nov 29, 2020 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [bac9b50aa6](https://linux-hardware.org/?probe=bac9b50aa6) | Nov 29, 2020 |
| Medion        | E2228T MD60250              | Convertible | [9d61c8d7d7](https://linux-hardware.org/?probe=9d61c8d7d7) | Nov 29, 2020 |
| HP            | ProBook 6550b               | Notebook    | [bf1857d7de](https://linux-hardware.org/?probe=bf1857d7de) | Nov 29, 2020 |
| HP            | ProBook 6550b               | Notebook    | [5f152a63b9](https://linux-hardware.org/?probe=5f152a63b9) | Nov 29, 2020 |
| HP            | ProBook 455R G6             | Notebook    | [589714df6f](https://linux-hardware.org/?probe=589714df6f) | Nov 28, 2020 |
| NEXCOM        | NSA3110 B                   | Desktop     | [915437aff9](https://linux-hardware.org/?probe=915437aff9) | Nov 28, 2020 |
| Toshiba       | Satellite C70-A             | Notebook    | [d25f4553bd](https://linux-hardware.org/?probe=d25f4553bd) | Nov 27, 2020 |
| Dell          | Latitude 3350               | Notebook    | [46de8f611e](https://linux-hardware.org/?probe=46de8f611e) | Nov 27, 2020 |
| MSI           | X99S SLI PLUS               | Desktop     | [31752a553b](https://linux-hardware.org/?probe=31752a553b) | Nov 27, 2020 |
| ASUSTek       | N53SV                       | Notebook    | [444b4904d5](https://linux-hardware.org/?probe=444b4904d5) | Nov 26, 2020 |
| Acer          | Veriton X4620G V1.0         | Desktop     | [0c9f3c4db1](https://linux-hardware.org/?probe=0c9f3c4db1) | Nov 26, 2020 |
| Gigabyte      | AX370M-DS3H-CF              | Desktop     | [d390d5e008](https://linux-hardware.org/?probe=d390d5e008) | Nov 26, 2020 |
| ASUSTek       | X205TA                      | Notebook    | [819f50e58e](https://linux-hardware.org/?probe=819f50e58e) | Nov 26, 2020 |
| Apple         | MacBookPro12,1              | Notebook    | [3a38070df9](https://linux-hardware.org/?probe=3a38070df9) | Nov 26, 2020 |
| Dell          | Inspiron 5720               | Notebook    | [96891b6fcf](https://linux-hardware.org/?probe=96891b6fcf) | Nov 26, 2020 |
| MSI           | Gypsum                      | Desktop     | [22314ebafc](https://linux-hardware.org/?probe=22314ebafc) | Nov 25, 2020 |
| MSI           | Gypsum                      | Desktop     | [fdfd3108bd](https://linux-hardware.org/?probe=fdfd3108bd) | Nov 25, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [b7fec4788f](https://linux-hardware.org/?probe=b7fec4788f) | Nov 25, 2020 |
| Dell          | XPS 15 9570                 | Notebook    | [613707835e](https://linux-hardware.org/?probe=613707835e) | Nov 24, 2020 |
| HP            | 84EE 1100                   | All in one  | [ff1b979eb8](https://linux-hardware.org/?probe=ff1b979eb8) | Nov 24, 2020 |
| Lenovo        | ThinkPad X220 4291QT1       | Notebook    | [a440445f3f](https://linux-hardware.org/?probe=a440445f3f) | Nov 24, 2020 |
| Dell          | Latitude 3310               | Notebook    | [8097d5c876](https://linux-hardware.org/?probe=8097d5c876) | Nov 23, 2020 |
| Dell          | Latitude 3180               | Notebook    | [04310607c3](https://linux-hardware.org/?probe=04310607c3) | Nov 23, 2020 |
| Dell          | Latitude 3180               | Notebook    | [0e5789a5ed](https://linux-hardware.org/?probe=0e5789a5ed) | Nov 23, 2020 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | Desktop     | [bc0f93a7b3](https://linux-hardware.org/?probe=bc0f93a7b3) | Nov 22, 2020 |
| Dell          | 0KC9NP A01                  | Desktop     | [57ef5451bc](https://linux-hardware.org/?probe=57ef5451bc) | Nov 21, 2020 |
| Toshiba       | Satellite S50-B             | Notebook    | [3a844ee120](https://linux-hardware.org/?probe=3a844ee120) | Nov 21, 2020 |
| Dell          | 0DR845                      | Desktop     | [592326d99b](https://linux-hardware.org/?probe=592326d99b) | Nov 21, 2020 |
| Dell          | Latitude 7400               | Notebook    | [c471c6db8e](https://linux-hardware.org/?probe=c471c6db8e) | Nov 21, 2020 |
| HP            | 530 Notebook PC(KD092AA#... | Notebook    | [ae8a3e55cd](https://linux-hardware.org/?probe=ae8a3e55cd) | Nov 21, 2020 |
| ASRock        | A55M-HVS                    | Desktop     | [c214b14df7](https://linux-hardware.org/?probe=c214b14df7) | Nov 20, 2020 |
| Gigabyte      | Z270X-UD3-CF                | Desktop     | [3015fe939e](https://linux-hardware.org/?probe=3015fe939e) | Nov 20, 2020 |
| HP            | 1494                        | Desktop     | [d358799e79](https://linux-hardware.org/?probe=d358799e79) | Nov 20, 2020 |
| ASUSTek       | N750JV                      | Notebook    | [324b36f2d2](https://linux-hardware.org/?probe=324b36f2d2) | Nov 20, 2020 |
| ASRock        | A55M-HVS                    | Desktop     | [9c29cee20d](https://linux-hardware.org/?probe=9c29cee20d) | Nov 20, 2020 |
| Rockwell A... | 6177R A1                    | Desktop     | [fe9015c15e](https://linux-hardware.org/?probe=fe9015c15e) | Nov 20, 2020 |
| Lenovo        | ThinkCentre A58 75227CG     | Desktop     | [24c4cbf87b](https://linux-hardware.org/?probe=24c4cbf87b) | Nov 19, 2020 |
| HP            | 84EE 1100                   | All in one  | [e71cb079f3](https://linux-hardware.org/?probe=e71cb079f3) | Nov 19, 2020 |
| Lenovo        | ThinkPad X395 20NM0002UK    | Notebook    | [9e71e4e71c](https://linux-hardware.org/?probe=9e71e4e71c) | Nov 19, 2020 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [85932e6090](https://linux-hardware.org/?probe=85932e6090) | Nov 19, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a339ccacaa](https://linux-hardware.org/?probe=a339ccacaa) | Nov 19, 2020 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [836130efe9](https://linux-hardware.org/?probe=836130efe9) | Nov 18, 2020 |
| Lenovo        | ThinkPad L480 20LTS6VS00    | Notebook    | [c1376469ef](https://linux-hardware.org/?probe=c1376469ef) | Nov 18, 2020 |
| HP            | EliteBook 725 G2            | Notebook    | [c7f76b756a](https://linux-hardware.org/?probe=c7f76b756a) | Nov 18, 2020 |
| Toshiba       | Satellite C70-A             | Notebook    | [5c59fc6b41](https://linux-hardware.org/?probe=5c59fc6b41) | Nov 17, 2020 |
| Acer          | Aspire 7551                 | Notebook    | [958a844d2f](https://linux-hardware.org/?probe=958a844d2f) | Nov 17, 2020 |
| MSI           | MEG X570 ACE                | Desktop     | [df9073af0d](https://linux-hardware.org/?probe=df9073af0d) | Nov 16, 2020 |
| HP            | EliteBook Folio G1          | Notebook    | [7b48d6a46e](https://linux-hardware.org/?probe=7b48d6a46e) | Nov 16, 2020 |
| Apple         | Mac-F2268DAE                | All in one  | [e01cf9234b](https://linux-hardware.org/?probe=e01cf9234b) | Nov 16, 2020 |
| Apple         | Mac-F2268DAE                | All in one  | [c74cdc7f6f](https://linux-hardware.org/?probe=c74cdc7f6f) | Nov 16, 2020 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [df70e49f02](https://linux-hardware.org/?probe=df70e49f02) | Nov 16, 2020 |
| Rockwell A... | 6177R A1                    | Desktop     | [a12a2989fd](https://linux-hardware.org/?probe=a12a2989fd) | Nov 16, 2020 |
| Dell          | Latitude E6430              | Notebook    | [4cbfa4d98e](https://linux-hardware.org/?probe=4cbfa4d98e) | Nov 16, 2020 |
| HP            | Compaq 8510p                | Notebook    | [532c0efba2](https://linux-hardware.org/?probe=532c0efba2) | Nov 16, 2020 |
| Medion        | B360H4-EM V1.0              | Desktop     | [1915ad5c58](https://linux-hardware.org/?probe=1915ad5c58) | Nov 15, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [02882ab1a8](https://linux-hardware.org/?probe=02882ab1a8) | Nov 15, 2020 |
| Medion        | Akoya E7416                 | Notebook    | [b01171ae2d](https://linux-hardware.org/?probe=b01171ae2d) | Nov 13, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [6fbae424bd](https://linux-hardware.org/?probe=6fbae424bd) | Nov 13, 2020 |
| ASUSTek       | B150M-PLUS                  | Desktop     | [27cd387c8d](https://linux-hardware.org/?probe=27cd387c8d) | Nov 13, 2020 |
| MSI           | B150M BAZOOKA               | Desktop     | [0e4495c03f](https://linux-hardware.org/?probe=0e4495c03f) | Nov 13, 2020 |
| Packard Be... | EasyNote MH36               | Notebook    | [d84fe10113](https://linux-hardware.org/?probe=d84fe10113) | Nov 13, 2020 |
| Packard Be... | EasyNote MH36               | Notebook    | [4f76ec5df8](https://linux-hardware.org/?probe=4f76ec5df8) | Nov 13, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [852e3e07ea](https://linux-hardware.org/?probe=852e3e07ea) | Nov 13, 2020 |
| HP            | EliteBook 2760p             | Notebook    | [c95f2a55fc](https://linux-hardware.org/?probe=c95f2a55fc) | Nov 13, 2020 |
| HP            | ZBook Studio G5             | Notebook    | [5dfa83d621](https://linux-hardware.org/?probe=5dfa83d621) | Nov 12, 2020 |
| ASUSTek       | ZenBook UX431FA_UX431FA     | Notebook    | [a075f54055](https://linux-hardware.org/?probe=a075f54055) | Nov 12, 2020 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [ac9374fc21](https://linux-hardware.org/?probe=ac9374fc21) | Nov 12, 2020 |
| MSI           | Prestige 15 A10SC           | Notebook    | [594737cb8b](https://linux-hardware.org/?probe=594737cb8b) | Nov 12, 2020 |
| MSI           | Prestige 15 A10SC           | Notebook    | [a261f81748](https://linux-hardware.org/?probe=a261f81748) | Nov 12, 2020 |
| HP            | 09F8h                       | Desktop     | [41f17bf7fc](https://linux-hardware.org/?probe=41f17bf7fc) | Nov 12, 2020 |
| HP            | 09F8h                       | Desktop     | [879925f102](https://linux-hardware.org/?probe=879925f102) | Nov 12, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [7de01328d2](https://linux-hardware.org/?probe=7de01328d2) | Nov 12, 2020 |
| Notebook      | NH50_70RA                   | Notebook    | [06db49dffa](https://linux-hardware.org/?probe=06db49dffa) | Nov 12, 2020 |
| Toshiba       | Satellite L850-14L          | Notebook    | [30037dd663](https://linux-hardware.org/?probe=30037dd663) | Nov 12, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [7ab630580d](https://linux-hardware.org/?probe=7ab630580d) | Nov 12, 2020 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [2fe2d6ddb1](https://linux-hardware.org/?probe=2fe2d6ddb1) | Nov 12, 2020 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [72e0270e6d](https://linux-hardware.org/?probe=72e0270e6d) | Nov 11, 2020 |
| ASRock        | H270M-ITX/ac                | Desktop     | [b21c36ea25](https://linux-hardware.org/?probe=b21c36ea25) | Nov 11, 2020 |
| Lenovo        | IdeaPad S540-15IWL 81NE     | Notebook    | [23431dd3f0](https://linux-hardware.org/?probe=23431dd3f0) | Nov 11, 2020 |
| ASUSTek       | PN62                        | Mini pc     | [945c5cadf4](https://linux-hardware.org/?probe=945c5cadf4) | Nov 11, 2020 |
| HP            | Laptop 17-bs1xx             | Notebook    | [3bd46e272b](https://linux-hardware.org/?probe=3bd46e272b) | Nov 11, 2020 |
| ASUSTek       | B150M-PLUS                  | Desktop     | [5f181e0e65](https://linux-hardware.org/?probe=5f181e0e65) | Nov 10, 2020 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [6608936515](https://linux-hardware.org/?probe=6608936515) | Nov 10, 2020 |
| HP            | EliteBook 840 G3            | Notebook    | [e7a663c792](https://linux-hardware.org/?probe=e7a663c792) | Nov 10, 2020 |
| HP            | Mini 110-3100               | Notebook    | [0fede729f6](https://linux-hardware.org/?probe=0fede729f6) | Nov 09, 2020 |
| ASUSTek       | PN62                        | Mini pc     | [82ddcf65c3](https://linux-hardware.org/?probe=82ddcf65c3) | Nov 09, 2020 |
| HP            | ZBook 15 G2                 | Notebook    | [b31f30762f](https://linux-hardware.org/?probe=b31f30762f) | Nov 09, 2020 |
| Dell          | 06NWYK A00                  | Desktop     | [b62f9d4650](https://linux-hardware.org/?probe=b62f9d4650) | Nov 09, 2020 |
| SLIMBOOK      | PROX14-AMD                  | Notebook    | [deec7a28d9](https://linux-hardware.org/?probe=deec7a28d9) | Nov 09, 2020 |
| HP            | ENVY x360 Convertible 15... | Convertible | [bd6b18e7dc](https://linux-hardware.org/?probe=bd6b18e7dc) | Nov 09, 2020 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [52fb917bb4](https://linux-hardware.org/?probe=52fb917bb4) | Nov 09, 2020 |
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [5f8bd77a30](https://linux-hardware.org/?probe=5f8bd77a30) | Nov 08, 2020 |
| Intel         | NUC8BEB J72693-308          | Mini pc     | [b8439cdc72](https://linux-hardware.org/?probe=b8439cdc72) | Nov 08, 2020 |
| HP            | Compaq Presario CQ60        | Notebook    | [3744807a1e](https://linux-hardware.org/?probe=3744807a1e) | Nov 08, 2020 |
| Acer          | Veriton X4640G V:1.1        | Desktop     | [b2fa5948d8](https://linux-hardware.org/?probe=b2fa5948d8) | Nov 08, 2020 |
| HP            | Compaq Presario CQ60        | Notebook    | [96e8dbfe06](https://linux-hardware.org/?probe=96e8dbfe06) | Nov 08, 2020 |
| HP            | 1587h                       | Desktop     | [6c8e8d3a2e](https://linux-hardware.org/?probe=6c8e8d3a2e) | Nov 07, 2020 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [a5c518748c](https://linux-hardware.org/?probe=a5c518748c) | Nov 06, 2020 |
| Toshiba       | Satellite S50-B             | Notebook    | [f3397d1a0f](https://linux-hardware.org/?probe=f3397d1a0f) | Nov 06, 2020 |
| Medion        | MS-7797                     | Desktop     | [7e6563d31c](https://linux-hardware.org/?probe=7e6563d31c) | Nov 06, 2020 |
| Dell          | Latitude 3390 2-in-1        | Convertible | [91f3d918a0](https://linux-hardware.org/?probe=91f3d918a0) | Nov 06, 2020 |
| Dell          | Vostro 3360                 | Notebook    | [68c510e0bc](https://linux-hardware.org/?probe=68c510e0bc) | Nov 06, 2020 |
| Gigabyte      | EP45T-UD3R                  | Desktop     | [92065256f6](https://linux-hardware.org/?probe=92065256f6) | Nov 06, 2020 |
| Gigabyte      | EP45T-UD3R                  | Desktop     | [42a45f3dbb](https://linux-hardware.org/?probe=42a45f3dbb) | Nov 06, 2020 |
| MSI           | H87-G43 GAMING              | Desktop     | [38591dcea5](https://linux-hardware.org/?probe=38591dcea5) | Nov 06, 2020 |
| MSI           | H87-G43 GAMING              | Desktop     | [f0921d8567](https://linux-hardware.org/?probe=f0921d8567) | Nov 06, 2020 |
| Notebook      | NH5xAx                      | Notebook    | [ac9f796111](https://linux-hardware.org/?probe=ac9f796111) | Nov 05, 2020 |
| HP            | EliteBook 840 G3            | Notebook    | [364cc81bf5](https://linux-hardware.org/?probe=364cc81bf5) | Nov 05, 2020 |
| Dell          | Latitude 5491               | Notebook    | [5b17fdf40d](https://linux-hardware.org/?probe=5b17fdf40d) | Nov 05, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [0000ff019e](https://linux-hardware.org/?probe=0000ff019e) | Nov 05, 2020 |
| Dell          | Latitude E5440              | Notebook    | [8d21aaa286](https://linux-hardware.org/?probe=8d21aaa286) | Nov 05, 2020 |
| Apple         | MacBookPro5,3               | Notebook    | [8a2ec55fee](https://linux-hardware.org/?probe=8a2ec55fee) | Nov 05, 2020 |
| Dell          | Precision 7730              | Notebook    | [20f0cbd338](https://linux-hardware.org/?probe=20f0cbd338) | Nov 05, 2020 |
| Notebook      | NL40_50CU                   | Notebook    | [df59f055e3](https://linux-hardware.org/?probe=df59f055e3) | Nov 05, 2020 |
| Dell          | System XPS L502X            | Notebook    | [1d535cfdfe](https://linux-hardware.org/?probe=1d535cfdfe) | Nov 05, 2020 |
| Lenovo        | ThinkPad T430s 2356L2G      | Notebook    | [201613938f](https://linux-hardware.org/?probe=201613938f) | Nov 05, 2020 |
| Apple         | MacBookPro11,4              | Notebook    | [e459ac1163](https://linux-hardware.org/?probe=e459ac1163) | Nov 04, 2020 |
| Apple         | MacBookPro11,4              | Notebook    | [df989b8919](https://linux-hardware.org/?probe=df989b8919) | Nov 04, 2020 |
| MSI           | H81M-E34                    | Desktop     | [52c225c379](https://linux-hardware.org/?probe=52c225c379) | Nov 04, 2020 |
| ASUSTek       | X75A                        | Notebook    | [4a0fb25d57](https://linux-hardware.org/?probe=4a0fb25d57) | Nov 03, 2020 |
| Acer          | Swift SF314-55              | Notebook    | [1cb334b7fd](https://linux-hardware.org/?probe=1cb334b7fd) | Nov 03, 2020 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [5d1138192c](https://linux-hardware.org/?probe=5d1138192c) | Nov 03, 2020 |
| Dell          | Latitude E6530              | Notebook    | [46ebf29e8a](https://linux-hardware.org/?probe=46ebf29e8a) | Nov 03, 2020 |
| Gigabyte      | EP45T-UD3R                  | Desktop     | [4a31c6bc7c](https://linux-hardware.org/?probe=4a31c6bc7c) | Nov 03, 2020 |
| Acer          | Aspire A314-32              | Notebook    | [686d0b8c4f](https://linux-hardware.org/?probe=686d0b8c4f) | Nov 03, 2020 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [6879002942](https://linux-hardware.org/?probe=6879002942) | Nov 03, 2020 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [97130cbbc4](https://linux-hardware.org/?probe=97130cbbc4) | Nov 03, 2020 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [6edccaf622](https://linux-hardware.org/?probe=6edccaf622) | Nov 03, 2020 |
| ASUSTek       | Hematite                    | Desktop     | [f460b9f0eb](https://linux-hardware.org/?probe=f460b9f0eb) | Nov 02, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [7c29ba500b](https://linux-hardware.org/?probe=7c29ba500b) | Nov 02, 2020 |
| Gigabyte      | EP45T-UD3R                  | Desktop     | [563f5dbad8](https://linux-hardware.org/?probe=563f5dbad8) | Nov 02, 2020 |
| Notebook      | NH55RGQ                     | Notebook    | [7cf0031671](https://linux-hardware.org/?probe=7cf0031671) | Nov 02, 2020 |
| Lenovo        | IdeaPad Flex-14IWL 81SQ     | Convertible | [1ee6549140](https://linux-hardware.org/?probe=1ee6549140) | Nov 02, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [2ba9d9cee4](https://linux-hardware.org/?probe=2ba9d9cee4) | Nov 02, 2020 |
| Dell          | 0G3HR7 A00                  | Desktop     | [edb93958c2](https://linux-hardware.org/?probe=edb93958c2) | Nov 01, 2020 |
| ASRock        | FM2A88M Extreme4+           | Desktop     | [9875911102](https://linux-hardware.org/?probe=9875911102) | Nov 01, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [e97f97fd1b](https://linux-hardware.org/?probe=e97f97fd1b) | Nov 01, 2020 |
| Medion        | P7612                       | Notebook    | [7045b11fbd](https://linux-hardware.org/?probe=7045b11fbd) | Nov 01, 2020 |
| HP            | ProBook 440 G7              | Notebook    | [11cc71290a](https://linux-hardware.org/?probe=11cc71290a) | Nov 01, 2020 |
| HP            | EliteBook 840 G3            | Notebook    | [6603ba59d7](https://linux-hardware.org/?probe=6603ba59d7) | Oct 31, 2020 |
| Gigabyte      | P55A-UD3                    | Desktop     | [8dafd4dd5b](https://linux-hardware.org/?probe=8dafd4dd5b) | Oct 31, 2020 |
| MiTAC         | PH12LI                      | Desktop     | [bd586137ba](https://linux-hardware.org/?probe=bd586137ba) | Oct 31, 2020 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [57d7a8f5f7](https://linux-hardware.org/?probe=57d7a8f5f7) | Oct 31, 2020 |
| Gigabyte      | AERO 15 WB                  | Notebook    | [1a70aca57b](https://linux-hardware.org/?probe=1a70aca57b) | Oct 31, 2020 |
| Dell          | Latitude 5490               | Notebook    | [70f49f9246](https://linux-hardware.org/?probe=70f49f9246) | Oct 31, 2020 |
| Dell          | Latitude E6530              | Notebook    | [620044198e](https://linux-hardware.org/?probe=620044198e) | Oct 31, 2020 |
| HP            | 0AA8h                       | Desktop     | [e64ebb4397](https://linux-hardware.org/?probe=e64ebb4397) | Oct 30, 2020 |
| HP            | 0AA8h                       | Desktop     | [765793ea94](https://linux-hardware.org/?probe=765793ea94) | Oct 30, 2020 |
| ASRock        | B75 Pro3-M                  | Desktop     | [6123325109](https://linux-hardware.org/?probe=6123325109) | Oct 29, 2020 |
| Foxconn       | 2AB1h                       | Desktop     | [dd42a7e94c](https://linux-hardware.org/?probe=dd42a7e94c) | Oct 29, 2020 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [58ddbe0cbb](https://linux-hardware.org/?probe=58ddbe0cbb) | Oct 29, 2020 |
| ASRock        | B450M Pro4                  | Desktop     | [b56d43c472](https://linux-hardware.org/?probe=b56d43c472) | Oct 28, 2020 |
| Shuttle       | FS81                        | Desktop     | [2d64e921a9](https://linux-hardware.org/?probe=2d64e921a9) | Oct 28, 2020 |
| Shuttle       | FS81                        | Desktop     | [163d0e5bc9](https://linux-hardware.org/?probe=163d0e5bc9) | Oct 28, 2020 |
| ASRock        | FM2A88M Extreme4+           | Desktop     | [dcbbea95b8](https://linux-hardware.org/?probe=dcbbea95b8) | Oct 28, 2020 |
| ASRockRack    | X399D8A-2T                  | Desktop     | [069e75c80b](https://linux-hardware.org/?probe=069e75c80b) | Oct 28, 2020 |
| ASRockRack    | X399D8A-2T                  | Desktop     | [b8a8dbd1aa](https://linux-hardware.org/?probe=b8a8dbd1aa) | Oct 28, 2020 |
| ASUSTek       | X555LA                      | Notebook    | [c50647764f](https://linux-hardware.org/?probe=c50647764f) | Oct 28, 2020 |
| ASUSTek       | M4A78LT-M                   | Desktop     | [180b2ec397](https://linux-hardware.org/?probe=180b2ec397) | Oct 28, 2020 |
| Raspberry ... | Raspberry Pi                | Soc         | [a54edcaa04](https://linux-hardware.org/?probe=a54edcaa04) | Oct 28, 2020 |
| Notebook      | NH55RGQ                     | Notebook    | [c71e9b2d88](https://linux-hardware.org/?probe=c71e9b2d88) | Oct 27, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [b2cc3d1bfe](https://linux-hardware.org/?probe=b2cc3d1bfe) | Oct 27, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [36167f1f96](https://linux-hardware.org/?probe=36167f1f96) | Oct 27, 2020 |
| MSI           | A78M-E35                    | Desktop     | [6e4eaa3c6d](https://linux-hardware.org/?probe=6e4eaa3c6d) | Oct 27, 2020 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [c69d1ad2b4](https://linux-hardware.org/?probe=c69d1ad2b4) | Oct 27, 2020 |
| ASRock        | B550M Steel Legend          | Desktop     | [4a39d12d46](https://linux-hardware.org/?probe=4a39d12d46) | Oct 26, 2020 |
| Acer          | Swift SF314-55              | Notebook    | [018146573b](https://linux-hardware.org/?probe=018146573b) | Oct 26, 2020 |
| HP            | EliteBook 840 G3            | Notebook    | [cad395fc2e](https://linux-hardware.org/?probe=cad395fc2e) | Oct 26, 2020 |
| HP            | EliteBook 840 G3            | Notebook    | [31d1f58eb9](https://linux-hardware.org/?probe=31d1f58eb9) | Oct 26, 2020 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [13bbb928b0](https://linux-hardware.org/?probe=13bbb928b0) | Oct 26, 2020 |
| Dell          | Latitude 5500               | Notebook    | [b1f5e9ea7a](https://linux-hardware.org/?probe=b1f5e9ea7a) | Oct 25, 2020 |
| ASRock        | FM2A75 Pro4-M               | Desktop     | [8ebc1639b1](https://linux-hardware.org/?probe=8ebc1639b1) | Oct 25, 2020 |
| Acer          | F690GVM                     | Desktop     | [b6fcdf0abb](https://linux-hardware.org/?probe=b6fcdf0abb) | Oct 25, 2020 |
| Packard Be... | MCP61                       | Desktop     | [c838b17430](https://linux-hardware.org/?probe=c838b17430) | Oct 25, 2020 |
| Notebook      | W35xSS_370SS                | Notebook    | [b277432aee](https://linux-hardware.org/?probe=b277432aee) | Oct 25, 2020 |
| MSI           | MS-7367                     | Desktop     | [7b41b504d7](https://linux-hardware.org/?probe=7b41b504d7) | Oct 24, 2020 |
| Dell          | 0N826N A03                  | Desktop     | [fb7b9f374b](https://linux-hardware.org/?probe=fb7b9f374b) | Oct 24, 2020 |
| Toshiba       | Satellite L850-14L          | Notebook    | [49923964af](https://linux-hardware.org/?probe=49923964af) | Oct 24, 2020 |
| Intel         | D915GAV AAC64134-400        | Desktop     | [73b829201a](https://linux-hardware.org/?probe=73b829201a) | Oct 24, 2020 |
| Intel         | D915GAV AAC64134-400        | Desktop     | [5df08a35e8](https://linux-hardware.org/?probe=5df08a35e8) | Oct 24, 2020 |
| Lenovo        | ThinkPad T450s 20BWS1CN0... | Notebook    | [a74f6e95d7](https://linux-hardware.org/?probe=a74f6e95d7) | Oct 24, 2020 |
| ASUSTek       | WS-C621E-SAGE Series        | Desktop     | [f3f320a44e](https://linux-hardware.org/?probe=f3f320a44e) | Oct 24, 2020 |
| ASUSTek       | WS-C621E-SAGE Series        | Desktop     | [fbc73137e6](https://linux-hardware.org/?probe=fbc73137e6) | Oct 24, 2020 |
| ASUSTek       | F5SL                        | Notebook    | [44dab16e0a](https://linux-hardware.org/?probe=44dab16e0a) | Oct 23, 2020 |
| MECHREVO      | Code 01 Series PF5NU1G      | Notebook    | [ad8c53bb70](https://linux-hardware.org/?probe=ad8c53bb70) | Oct 22, 2020 |
| HP            | 530                         | Notebook    | [b7b25f64ec](https://linux-hardware.org/?probe=b7b25f64ec) | Oct 22, 2020 |
| HP            | 530                         | Notebook    | [108027ac63](https://linux-hardware.org/?probe=108027ac63) | Oct 22, 2020 |
| ASUSTek       | P5Q-EM                      | Desktop     | [5b449cf9a6](https://linux-hardware.org/?probe=5b449cf9a6) | Oct 22, 2020 |
| Dell          | Inspiron 7559               | Notebook    | [d3265c616b](https://linux-hardware.org/?probe=d3265c616b) | Oct 21, 2020 |
| ASUSTek       | E45M1-M PRO                 | Desktop     | [559b9ca151](https://linux-hardware.org/?probe=559b9ca151) | Oct 21, 2020 |
| Notebook      | W35xSS_370SS                | Notebook    | [b8aa7a6f9a](https://linux-hardware.org/?probe=b8aa7a6f9a) | Oct 21, 2020 |
| HP            | ZBook 15 G2                 | Notebook    | [e08af6da0f](https://linux-hardware.org/?probe=e08af6da0f) | Oct 21, 2020 |
| Acer          | Aspire ES1-511              | Notebook    | [a23a177823](https://linux-hardware.org/?probe=a23a177823) | Oct 20, 2020 |
| Dell          | Inspiron 7559               | Notebook    | [01f75c41ed](https://linux-hardware.org/?probe=01f75c41ed) | Oct 20, 2020 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [23b99cc8ba](https://linux-hardware.org/?probe=23b99cc8ba) | Oct 20, 2020 |
| Dell          | System XPS L502X            | Notebook    | [178e6c01b7](https://linux-hardware.org/?probe=178e6c01b7) | Oct 20, 2020 |
| Acer          | Aspire A517-51              | Notebook    | [4b5f7f71e3](https://linux-hardware.org/?probe=4b5f7f71e3) | Oct 20, 2020 |
| Acer          | Aspire ZC-602               | All in one  | [76fb26f605](https://linux-hardware.org/?probe=76fb26f605) | Oct 20, 2020 |
| HP            | ZBook Studio G5             | Notebook    | [d37cbd44aa](https://linux-hardware.org/?probe=d37cbd44aa) | Oct 20, 2020 |
| Notebook      | X170SM                      | Notebook    | [55521a7f28](https://linux-hardware.org/?probe=55521a7f28) | Oct 20, 2020 |
| HP            | Compaq 6710b (KE121ET#AB... | Notebook    | [bf3317f9bb](https://linux-hardware.org/?probe=bf3317f9bb) | Oct 19, 2020 |
| ASRock        | B450M-HDV                   | Desktop     | [bd79aa3e2b](https://linux-hardware.org/?probe=bd79aa3e2b) | Oct 19, 2020 |
| ASRock        | FM2A88M Extreme4+           | Desktop     | [f1597de5a9](https://linux-hardware.org/?probe=f1597de5a9) | Oct 19, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [5283ed3ddd](https://linux-hardware.org/?probe=5283ed3ddd) | Oct 18, 2020 |
| Lenovo        | IdeaPad 330S-14IKB U 81F... | Notebook    | [bbf4db42c0](https://linux-hardware.org/?probe=bbf4db42c0) | Oct 18, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [63e58bdbc7](https://linux-hardware.org/?probe=63e58bdbc7) | Oct 18, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [adb3b7b623](https://linux-hardware.org/?probe=adb3b7b623) | Oct 18, 2020 |
| ASRock        | N68C-GS FX                  | Desktop     | [d0dcba5f5d](https://linux-hardware.org/?probe=d0dcba5f5d) | Oct 18, 2020 |
| ASRock        | N68C-GS FX                  | Desktop     | [54d0b30e69](https://linux-hardware.org/?probe=54d0b30e69) | Oct 18, 2020 |
| Dell          | Latitude 5300               | Notebook    | [4169f50442](https://linux-hardware.org/?probe=4169f50442) | Oct 18, 2020 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [bed914e833](https://linux-hardware.org/?probe=bed914e833) | Oct 18, 2020 |
| Dell          | Latitude E5540              | Notebook    | [e643f1337b](https://linux-hardware.org/?probe=e643f1337b) | Oct 17, 2020 |
| HP            | Pavilion TS Sleekbook 15    | Notebook    | [0d3675b44f](https://linux-hardware.org/?probe=0d3675b44f) | Oct 16, 2020 |
| Dell          | Inspiron 3521               | Notebook    | [5353f1b7ff](https://linux-hardware.org/?probe=5353f1b7ff) | Oct 16, 2020 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [cacf226be4](https://linux-hardware.org/?probe=cacf226be4) | Oct 16, 2020 |
| HP            | 3397                        | Desktop     | [33fdc768a1](https://linux-hardware.org/?probe=33fdc768a1) | Oct 15, 2020 |
| MSI           | Z97 GAMING 3                | Desktop     | [d70dc5679f](https://linux-hardware.org/?probe=d70dc5679f) | Oct 15, 2020 |
| ASRock        | B450M Pro4                  | Desktop     | [928ffa0370](https://linux-hardware.org/?probe=928ffa0370) | Oct 15, 2020 |
| Dell          | Latitude 5300               | Notebook    | [4bd822b6e3](https://linux-hardware.org/?probe=4bd822b6e3) | Oct 15, 2020 |
| HP            | Pavilion dv6                | Notebook    | [aa66ea4d86](https://linux-hardware.org/?probe=aa66ea4d86) | Oct 15, 2020 |
| ASRock        | B450M Pro4                  | Desktop     | [2ff14fe718](https://linux-hardware.org/?probe=2ff14fe718) | Oct 15, 2020 |
| ASRock        | FM2A88M Extreme4+           | Desktop     | [5b3b9a365f](https://linux-hardware.org/?probe=5b3b9a365f) | Oct 14, 2020 |
| ASUSTek       | X550CC                      | Notebook    | [6379bf0f07](https://linux-hardware.org/?probe=6379bf0f07) | Oct 14, 2020 |
| ASRock        | B450M Pro4                  | Desktop     | [676623dc17](https://linux-hardware.org/?probe=676623dc17) | Oct 14, 2020 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [65c2e79405](https://linux-hardware.org/?probe=65c2e79405) | Oct 13, 2020 |
| ASUSTek       | UX430UAR                    | Notebook    | [41467f30ea](https://linux-hardware.org/?probe=41467f30ea) | Oct 13, 2020 |
| ASUSTek       | UX430UAR                    | Notebook    | [41a02f4df8](https://linux-hardware.org/?probe=41a02f4df8) | Oct 13, 2020 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [48350eed4b](https://linux-hardware.org/?probe=48350eed4b) | Oct 11, 2020 |
| Microsoft     | Surface Pro 4               | Tablet      | [1567910fa2](https://linux-hardware.org/?probe=1567910fa2) | Oct 11, 2020 |
| Intel         | DG965RY AAD41691-301        | Desktop     | [22be735dca](https://linux-hardware.org/?probe=22be735dca) | Oct 11, 2020 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | Notebook    | [6b9b35b851](https://linux-hardware.org/?probe=6b9b35b851) | Oct 11, 2020 |
| ASRock        | FM2A58M-HD+                 | Desktop     | [2971e5263a](https://linux-hardware.org/?probe=2971e5263a) | Oct 10, 2020 |
| ASRock        | J4105B-ITX                  | Desktop     | [5229312d8a](https://linux-hardware.org/?probe=5229312d8a) | Oct 10, 2020 |
| Acer          | Aspire A517-51              | Notebook    | [fea8ec5bcc](https://linux-hardware.org/?probe=fea8ec5bcc) | Oct 10, 2020 |
| HP            | 1495                        | Desktop     | [95e7609af2](https://linux-hardware.org/?probe=95e7609af2) | Oct 10, 2020 |
| Dell          | Latitude 7300               | Notebook    | [56f4461a88](https://linux-hardware.org/?probe=56f4461a88) | Oct 09, 2020 |
| Intel         | NUC6i3SYB H81132-505        | Mini pc     | [e5c0786e3f](https://linux-hardware.org/?probe=e5c0786e3f) | Oct 09, 2020 |
| Apple         | MacBookAir5,2               | Notebook    | [2e3f769866](https://linux-hardware.org/?probe=2e3f769866) | Oct 08, 2020 |
| Lenovo        | ThinkCentre A58 75227CG     | Desktop     | [6254b64f24](https://linux-hardware.org/?probe=6254b64f24) | Oct 08, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a116b7a0e3](https://linux-hardware.org/?probe=a116b7a0e3) | Oct 08, 2020 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [5d3f7000fa](https://linux-hardware.org/?probe=5d3f7000fa) | Oct 08, 2020 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [a8135f177b](https://linux-hardware.org/?probe=a8135f177b) | Oct 08, 2020 |
| ASUSTek       | P5Q-EM                      | Desktop     | [693986101b](https://linux-hardware.org/?probe=693986101b) | Oct 07, 2020 |
| ASUSTek       | P5Q-EM                      | Desktop     | [f0cc4734aa](https://linux-hardware.org/?probe=f0cc4734aa) | Oct 07, 2020 |
| ASUSTek       | A8R-MX                      | Desktop     | [791a3288d5](https://linux-hardware.org/?probe=791a3288d5) | Oct 07, 2020 |
| Dell          | System Vostro 3750          | Notebook    | [e2cf9fa658](https://linux-hardware.org/?probe=e2cf9fa658) | Oct 07, 2020 |
| HP            | G72                         | Notebook    | [9ffd6f9800](https://linux-hardware.org/?probe=9ffd6f9800) | Oct 06, 2020 |
| ASRock        | J4105B-ITX                  | Desktop     | [5ea1332795](https://linux-hardware.org/?probe=5ea1332795) | Oct 06, 2020 |
| ASRock        | X570 Phantom Gaming-ITX/... | Desktop     | [4c9fc71c64](https://linux-hardware.org/?probe=4c9fc71c64) | Oct 06, 2020 |
| ASRock        | X570 Phantom Gaming-ITX/... | Desktop     | [f3201a0e2c](https://linux-hardware.org/?probe=f3201a0e2c) | Oct 06, 2020 |
| HP            | EliteBook 840 G1            | Notebook    | [59f038ef0b](https://linux-hardware.org/?probe=59f038ef0b) | Oct 06, 2020 |
| ASUSTek       | LEONITE                     | Desktop     | [ab0e072f1e](https://linux-hardware.org/?probe=ab0e072f1e) | Oct 06, 2020 |
| Toshiba       | Satellite C55D-C            | Notebook    | [0eaf011174](https://linux-hardware.org/?probe=0eaf011174) | Oct 06, 2020 |
| Toshiba       | Satellite C55D-C            | Notebook    | [20cb8f3aa6](https://linux-hardware.org/?probe=20cb8f3aa6) | Oct 06, 2020 |
| MSI           | H110M ECO                   | Desktop     | [21fea178f7](https://linux-hardware.org/?probe=21fea178f7) | Oct 06, 2020 |
| HP            | 1589                        | Desktop     | [21308638c4](https://linux-hardware.org/?probe=21308638c4) | Oct 06, 2020 |
| TUXEDO        | Unknown                     | Notebook    | [809434c279](https://linux-hardware.org/?probe=809434c279) | Oct 06, 2020 |
| ASRock        | J4105B-ITX                  | Desktop     | [c4633d012b](https://linux-hardware.org/?probe=c4633d012b) | Oct 05, 2020 |
| Acer          | Aspire 7720                 | Notebook    | [37ee142080](https://linux-hardware.org/?probe=37ee142080) | Oct 05, 2020 |
| HP            | 3047h                       | Desktop     | [7c018d0b98](https://linux-hardware.org/?probe=7c018d0b98) | Oct 05, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [36889b5833](https://linux-hardware.org/?probe=36889b5833) | Oct 05, 2020 |
| ASUSTek       | F1A75-M LE                  | Desktop     | [a528bbeefc](https://linux-hardware.org/?probe=a528bbeefc) | Oct 05, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [56667ca59e](https://linux-hardware.org/?probe=56667ca59e) | Oct 05, 2020 |
| Gigabyte      | AERO 15 WB                  | Notebook    | [736fac7664](https://linux-hardware.org/?probe=736fac7664) | Oct 05, 2020 |
| ASUSTek       | H81M-C                      | Desktop     | [cd136e059e](https://linux-hardware.org/?probe=cd136e059e) | Oct 05, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [5cd90973fc](https://linux-hardware.org/?probe=5cd90973fc) | Oct 04, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [703925da2c](https://linux-hardware.org/?probe=703925da2c) | Oct 04, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [95662d3a2a](https://linux-hardware.org/?probe=95662d3a2a) | Oct 04, 2020 |
| Gigabyte      | AERO 15 WB                  | Notebook    | [39a35b4381](https://linux-hardware.org/?probe=39a35b4381) | Oct 04, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [9c5d15be62](https://linux-hardware.org/?probe=9c5d15be62) | Oct 04, 2020 |
| ASUSTek       | P5Q3                        | Desktop     | [5c14426d29](https://linux-hardware.org/?probe=5c14426d29) | Oct 03, 2020 |
| ASUSTek       | P5Q3                        | Desktop     | [fd685fd8b1](https://linux-hardware.org/?probe=fd685fd8b1) | Oct 03, 2020 |
| ASUSTek       | P5B-MX/WiFi-AP              | Desktop     | [6f952c42c3](https://linux-hardware.org/?probe=6f952c42c3) | Oct 03, 2020 |
| ASUSTek       | P5B-MX/WiFi-AP              | Desktop     | [77c8601464](https://linux-hardware.org/?probe=77c8601464) | Oct 03, 2020 |
| Dell          | Latitude E5470              | Notebook    | [7b0f84256b](https://linux-hardware.org/?probe=7b0f84256b) | Oct 03, 2020 |
| Dell          | 0F0XJ6 A11                  | Server      | [ba4ffbda6d](https://linux-hardware.org/?probe=ba4ffbda6d) | Oct 03, 2020 |
| HP            | ProBook 650 G1              | Notebook    | [eff1f91a65](https://linux-hardware.org/?probe=eff1f91a65) | Oct 03, 2020 |
| HP            | 0A60h                       | Desktop     | [2e07c80651](https://linux-hardware.org/?probe=2e07c80651) | Oct 02, 2020 |
| HP            | ProBook 450 G6              | Notebook    | [967430ded8](https://linux-hardware.org/?probe=967430ded8) | Oct 02, 2020 |
| ASUSTek       | P8H67-M EVO                 | Desktop     | [817e2f90af](https://linux-hardware.org/?probe=817e2f90af) | Oct 02, 2020 |
| ASRock        | H61M-DGS R2.0               | Desktop     | [d9af6eb687](https://linux-hardware.org/?probe=d9af6eb687) | Oct 02, 2020 |
| HP            | 0A60h                       | Desktop     | [2d4669733f](https://linux-hardware.org/?probe=2d4669733f) | Oct 01, 2020 |
| HP            | 09F8h                       | Desktop     | [a05c147755](https://linux-hardware.org/?probe=a05c147755) | Oct 01, 2020 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [09a02746ac](https://linux-hardware.org/?probe=09a02746ac) | Oct 01, 2020 |
| HP            | ENVY Laptop 15-ep0xxx       | Notebook    | [991dcf8dae](https://linux-hardware.org/?probe=991dcf8dae) | Oct 01, 2020 |
| Acer          | Nitro AN515-52              | Notebook    | [811e442c45](https://linux-hardware.org/?probe=811e442c45) | Oct 01, 2020 |
| Medion        | P861X                       | Notebook    | [b088ab1281](https://linux-hardware.org/?probe=b088ab1281) | Oct 01, 2020 |
| HP            | Pavilion dv6                | Notebook    | [e579b3a47a](https://linux-hardware.org/?probe=e579b3a47a) | Sep 30, 2020 |
| HP            | Stream x360 Convertible ... | Convertible | [8269e87811](https://linux-hardware.org/?probe=8269e87811) | Sep 30, 2020 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [9cbca84e95](https://linux-hardware.org/?probe=9cbca84e95) | Sep 30, 2020 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [efdcdc1c74](https://linux-hardware.org/?probe=efdcdc1c74) | Sep 30, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [2c35fa260a](https://linux-hardware.org/?probe=2c35fa260a) | Sep 29, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [dec1a01b1c](https://linux-hardware.org/?probe=dec1a01b1c) | Sep 29, 2020 |
| MSI           | 2A9Ch                       | Desktop     | [09fc4642cf](https://linux-hardware.org/?probe=09fc4642cf) | Sep 29, 2020 |
| HUAWEI        | MACH-WX9                    | Notebook    | [73668957cf](https://linux-hardware.org/?probe=73668957cf) | Sep 29, 2020 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [cdf1ea1232](https://linux-hardware.org/?probe=cdf1ea1232) | Sep 29, 2020 |
| ASRock        | X570 Phantom Gaming X       | Desktop     | [241be84584](https://linux-hardware.org/?probe=241be84584) | Sep 28, 2020 |
| Acer          | Aspire 5736Z                | Notebook    | [45d37c8d1d](https://linux-hardware.org/?probe=45d37c8d1d) | Sep 28, 2020 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [bf255c3c98](https://linux-hardware.org/?probe=bf255c3c98) | Sep 28, 2020 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [2b8de9d4d4](https://linux-hardware.org/?probe=2b8de9d4d4) | Sep 28, 2020 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [968d37fe06](https://linux-hardware.org/?probe=968d37fe06) | Sep 28, 2020 |
| Gigabyte      | AB350M-DS3H-CF              | Desktop     | [18ab2e789b](https://linux-hardware.org/?probe=18ab2e789b) | Sep 28, 2020 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [7f19a0b86d](https://linux-hardware.org/?probe=7f19a0b86d) | Sep 28, 2020 |
| Acer          | Aspire ZC-602               | All in one  | [78b9b15e0c](https://linux-hardware.org/?probe=78b9b15e0c) | Sep 28, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [07e8019f76](https://linux-hardware.org/?probe=07e8019f76) | Sep 28, 2020 |
| Toshiba       | Satellite C70-A             | Notebook    | [6089c4157f](https://linux-hardware.org/?probe=6089c4157f) | Sep 27, 2020 |
| Microsoft     | Surface Pro                 | Tablet      | [0d9f0ac93a](https://linux-hardware.org/?probe=0d9f0ac93a) | Sep 26, 2020 |
| ASUSTek       | X202EP                      | Notebook    | [7003257b9c](https://linux-hardware.org/?probe=7003257b9c) | Sep 26, 2020 |
| Acer          | Iconia W700                 | Notebook    | [2b49917dd2](https://linux-hardware.org/?probe=2b49917dd2) | Sep 25, 2020 |
| MSI           | B450 TOMAHAWK               | Desktop     | [0d7ff552ea](https://linux-hardware.org/?probe=0d7ff552ea) | Sep 25, 2020 |
| Toshiba       | Satellite C660              | Notebook    | [bff4df02c8](https://linux-hardware.org/?probe=bff4df02c8) | Sep 24, 2020 |
| Apple         | MacBookPro13,2              | Notebook    | [5dcafc6901](https://linux-hardware.org/?probe=5dcafc6901) | Sep 24, 2020 |
| Toshiba       | Satellite C70-A             | Notebook    | [11ea717058](https://linux-hardware.org/?probe=11ea717058) | Sep 24, 2020 |
| Lenovo        | ThinkPad L380 20M6S24V00    | Notebook    | [5ed75210ae](https://linux-hardware.org/?probe=5ed75210ae) | Sep 24, 2020 |
| HP            | EliteBook 850 G1            | Notebook    | [d96f5a68b7](https://linux-hardware.org/?probe=d96f5a68b7) | Sep 24, 2020 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [b2866e5035](https://linux-hardware.org/?probe=b2866e5035) | Sep 23, 2020 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [a0f9a063a1](https://linux-hardware.org/?probe=a0f9a063a1) | Sep 23, 2020 |
| Acer          | Swift SF314-55              | Notebook    | [222c0aa8f6](https://linux-hardware.org/?probe=222c0aa8f6) | Sep 23, 2020 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [c645438893](https://linux-hardware.org/?probe=c645438893) | Sep 23, 2020 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [20bbf9f706](https://linux-hardware.org/?probe=20bbf9f706) | Sep 23, 2020 |
| HUAWEI        | MACH-WX9                    | Notebook    | [77ca0c89ab](https://linux-hardware.org/?probe=77ca0c89ab) | Sep 22, 2020 |
| Notebook      | NL40_50CU                   | Notebook    | [61025fd739](https://linux-hardware.org/?probe=61025fd739) | Sep 21, 2020 |
| Dell          | Latitude E6430              | Notebook    | [ea0ad060bb](https://linux-hardware.org/?probe=ea0ad060bb) | Sep 21, 2020 |
| ASUSTek       | K52F                        | Notebook    | [1c33f7ae8d](https://linux-hardware.org/?probe=1c33f7ae8d) | Sep 21, 2020 |
| Dell          | XPS 15 9550                 | Notebook    | [7dcf186e26](https://linux-hardware.org/?probe=7dcf186e26) | Sep 21, 2020 |
| Toshiba       | Satellite L670              | Notebook    | [1e4f6b645b](https://linux-hardware.org/?probe=1e4f6b645b) | Sep 20, 2020 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [05e817eba5](https://linux-hardware.org/?probe=05e817eba5) | Sep 20, 2020 |
| ASUSTek       | UX430UAR                    | Notebook    | [2a6591b64b](https://linux-hardware.org/?probe=2a6591b64b) | Sep 20, 2020 |
| Lenovo        | ThinkPad T420 4236PRG       | Notebook    | [642718e912](https://linux-hardware.org/?probe=642718e912) | Sep 20, 2020 |
| ASRock        | B450M Pro4                  | Desktop     | [95734c50d2](https://linux-hardware.org/?probe=95734c50d2) | Sep 20, 2020 |
| Dell          | 0Y958C A00                  | Desktop     | [c3013c3f27](https://linux-hardware.org/?probe=c3013c3f27) | Sep 19, 2020 |
| Lenovo        | ThinkPad Edge E540 20C6S... | Notebook    | [f4cf2142bc](https://linux-hardware.org/?probe=f4cf2142bc) | Sep 19, 2020 |
| Lenovo        | ThinkPad Edge E540 20C6S... | Notebook    | [0f906e176f](https://linux-hardware.org/?probe=0f906e176f) | Sep 19, 2020 |
| HP            | Pavilion g7                 | Notebook    | [7a81ae667b](https://linux-hardware.org/?probe=7a81ae667b) | Sep 19, 2020 |
| HP            | Pavilion g7                 | Notebook    | [767609618f](https://linux-hardware.org/?probe=767609618f) | Sep 19, 2020 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [bfb6d5de37](https://linux-hardware.org/?probe=bfb6d5de37) | Sep 18, 2020 |
| Notebook      | NH55RGQ                     | Notebook    | [0c25dbec1a](https://linux-hardware.org/?probe=0c25dbec1a) | Sep 18, 2020 |
| Notebook      | NL40_50CU                   | Notebook    | [6b0b09bd3b](https://linux-hardware.org/?probe=6b0b09bd3b) | Sep 17, 2020 |
| Lenovo        | IdeaPadFlex 4-1470 80SA     | Convertible | [8bcf500b4f](https://linux-hardware.org/?probe=8bcf500b4f) | Sep 17, 2020 |
| Lenovo        | IdeaPadFlex 4-1470 80SA     | Convertible | [099a09641e](https://linux-hardware.org/?probe=099a09641e) | Sep 17, 2020 |
| Lenovo        | ThinkPad E14 Gen 2 20T6C... | Notebook    | [b2f146a3d1](https://linux-hardware.org/?probe=b2f146a3d1) | Sep 16, 2020 |
| Medion        | Z370H4-EM                   | Desktop     | [5f10c1b458](https://linux-hardware.org/?probe=5f10c1b458) | Sep 16, 2020 |
| HP            | 1495                        | Desktop     | [94de1a6e23](https://linux-hardware.org/?probe=94de1a6e23) | Sep 16, 2020 |
| Raspberry ... | Raspberry Pi Model B Rev... | Soc         | [728d37c560](https://linux-hardware.org/?probe=728d37c560) | Sep 16, 2020 |
| Google        | Rammus                      | Notebook    | [efde72e6be](https://linux-hardware.org/?probe=efde72e6be) | Sep 16, 2020 |
| ASUSTek       | P8H61-M LX2                 | Desktop     | [6b0f8a2063](https://linux-hardware.org/?probe=6b0f8a2063) | Sep 16, 2020 |
| ASUSTek       | P8H61-M LX2                 | Desktop     | [048dd53259](https://linux-hardware.org/?probe=048dd53259) | Sep 16, 2020 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [5ad28e0063](https://linux-hardware.org/?probe=5ad28e0063) | Sep 16, 2020 |
| ASUSTek       | X202EP                      | Notebook    | [7331377f2b](https://linux-hardware.org/?probe=7331377f2b) | Sep 16, 2020 |
| Intel         | DH87RL AAG74240-403         | Desktop     | [afa08a0ab9](https://linux-hardware.org/?probe=afa08a0ab9) | Sep 16, 2020 |
| Dell          | Inspiron 5491 2n1           | Convertible | [585116ec81](https://linux-hardware.org/?probe=585116ec81) | Sep 16, 2020 |
| Intel         | DH87RL AAG74240-403         | Desktop     | [1f8ed93153](https://linux-hardware.org/?probe=1f8ed93153) | Sep 16, 2020 |
| HP            | 1495                        | Desktop     | [0c1425b11e](https://linux-hardware.org/?probe=0c1425b11e) | Sep 16, 2020 |
| MSI           | Prestige 15 A10SC           | Notebook    | [f725fcdd36](https://linux-hardware.org/?probe=f725fcdd36) | Sep 15, 2020 |
| Acer          | Aspire 7520                 | Notebook    | [d8ae16fc0b](https://linux-hardware.org/?probe=d8ae16fc0b) | Sep 14, 2020 |
| Dell          | 0GXM1W A02                  | Desktop     | [d4f329e596](https://linux-hardware.org/?probe=d4f329e596) | Sep 13, 2020 |
| MSI           | Z170A GAMING M7             | Desktop     | [148ef17d91](https://linux-hardware.org/?probe=148ef17d91) | Sep 13, 2020 |
| Microsoft     | Surface Pro                 | Tablet      | [682b5d5694](https://linux-hardware.org/?probe=682b5d5694) | Sep 13, 2020 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [9316561dfe](https://linux-hardware.org/?probe=9316561dfe) | Sep 13, 2020 |
| MSI           | Z97 GAMING 5                | Desktop     | [f1d169324d](https://linux-hardware.org/?probe=f1d169324d) | Sep 13, 2020 |
| ASRock        | B450M Pro4                  | Desktop     | [338d6ecd8e](https://linux-hardware.org/?probe=338d6ecd8e) | Sep 12, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [749dd9856d](https://linux-hardware.org/?probe=749dd9856d) | Sep 12, 2020 |
| ASRock        | B450M-HDV                   | Desktop     | [b1f92807e9](https://linux-hardware.org/?probe=b1f92807e9) | Sep 11, 2020 |
| Fujitsu Si... | AMILO Pi 2540               | Notebook    | [97ab8300bc](https://linux-hardware.org/?probe=97ab8300bc) | Sep 10, 2020 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [e6bcdfd9c3](https://linux-hardware.org/?probe=e6bcdfd9c3) | Sep 10, 2020 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [f31147b2b2](https://linux-hardware.org/?probe=f31147b2b2) | Sep 09, 2020 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [ed6724ef0b](https://linux-hardware.org/?probe=ed6724ef0b) | Sep 09, 2020 |
| Apple         | MacBookAir5,2               | Notebook    | [94c42c7f17](https://linux-hardware.org/?probe=94c42c7f17) | Sep 09, 2020 |
| HP            | ProBook 6360b               | Notebook    | [492279ec24](https://linux-hardware.org/?probe=492279ec24) | Sep 09, 2020 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [af78002507](https://linux-hardware.org/?probe=af78002507) | Sep 09, 2020 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [c45b64a8d0](https://linux-hardware.org/?probe=c45b64a8d0) | Sep 08, 2020 |
| ASUSTek       | H97M-E                      | Desktop     | [e1952c8c11](https://linux-hardware.org/?probe=e1952c8c11) | Sep 08, 2020 |
| Acer          | Aspire A715-75G             | Notebook    | [b134acf810](https://linux-hardware.org/?probe=b134acf810) | Sep 08, 2020 |
| Dell          | Latitude E5410              | Notebook    | [233cd6ea97](https://linux-hardware.org/?probe=233cd6ea97) | Sep 07, 2020 |
| HP            | ENVY Laptop 13-ah0xxx       | Notebook    | [b224b859d0](https://linux-hardware.org/?probe=b224b859d0) | Sep 07, 2020 |
| Dell          | Inspiron 5557               | Notebook    | [7359e2dd84](https://linux-hardware.org/?probe=7359e2dd84) | Sep 07, 2020 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [72e7305bc5](https://linux-hardware.org/?probe=72e7305bc5) | Sep 07, 2020 |
| Dell          | Latitude E6430              | Notebook    | [cf911b6935](https://linux-hardware.org/?probe=cf911b6935) | Sep 06, 2020 |
| Fujitsu Si... | AMILO Pi 2540               | Notebook    | [26dc47d759](https://linux-hardware.org/?probe=26dc47d759) | Sep 06, 2020 |
| ASUSTek       | P6T                         | Desktop     | [5b4f0b4a9d](https://linux-hardware.org/?probe=5b4f0b4a9d) | Sep 06, 2020 |
| Intel         | powered classmate PC        | Notebook    | [a0df584def](https://linux-hardware.org/?probe=a0df584def) | Sep 06, 2020 |
| Toshiba       | Satellite L850-14L          | Notebook    | [80c07200fb](https://linux-hardware.org/?probe=80c07200fb) | Sep 06, 2020 |
| Dell          | Latitude E6430              | Notebook    | [c939b86591](https://linux-hardware.org/?probe=c939b86591) | Sep 06, 2020 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [37ce819888](https://linux-hardware.org/?probe=37ce819888) | Sep 06, 2020 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [ab556edb8e](https://linux-hardware.org/?probe=ab556edb8e) | Sep 06, 2020 |
| HP            | Compaq Presario CQ60        | Notebook    | [5a10409a8a](https://linux-hardware.org/?probe=5a10409a8a) | Sep 06, 2020 |
| MSI           | GV72 8RD                    | Notebook    | [cc59f0f327](https://linux-hardware.org/?probe=cc59f0f327) | Sep 06, 2020 |
| MSI           | GV72 8RD                    | Notebook    | [ea6b4e99be](https://linux-hardware.org/?probe=ea6b4e99be) | Sep 06, 2020 |
| HP            | ProBook 440 G3              | Notebook    | [3af7fb8714](https://linux-hardware.org/?probe=3af7fb8714) | Sep 06, 2020 |
| Acer          | Aspire 7520                 | Notebook    | [f77db01d2b](https://linux-hardware.org/?probe=f77db01d2b) | Sep 06, 2020 |
| Unknown       | Unknown                     | Desktop     | [5ac8dac001](https://linux-hardware.org/?probe=5ac8dac001) | Sep 05, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [d6346fbb4b](https://linux-hardware.org/?probe=d6346fbb4b) | Sep 05, 2020 |
| ASUSTek       | P8H77-V                     | Desktop     | [04efcd81d1](https://linux-hardware.org/?probe=04efcd81d1) | Sep 05, 2020 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [61cb9d03a6](https://linux-hardware.org/?probe=61cb9d03a6) | Sep 04, 2020 |
| Lenovo        | G710 20252                  | Notebook    | [74e56831fb](https://linux-hardware.org/?probe=74e56831fb) | Sep 04, 2020 |
| HP            | 0A1Ch D                     | Desktop     | [e9c43bb0bf](https://linux-hardware.org/?probe=e9c43bb0bf) | Sep 04, 2020 |
| HP            | ZBook 15 G3                 | Notebook    | [acc6c85624](https://linux-hardware.org/?probe=acc6c85624) | Sep 04, 2020 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [4a3037422e](https://linux-hardware.org/?probe=4a3037422e) | Sep 04, 2020 |
| Dell          | Inspiron 5557               | Notebook    | [a6f77b3cc6](https://linux-hardware.org/?probe=a6f77b3cc6) | Sep 04, 2020 |
| Dell          | Latitude E5540              | Notebook    | [7f237410a4](https://linux-hardware.org/?probe=7f237410a4) | Sep 03, 2020 |
| Medion        | MS-7708                     | Desktop     | [c58e461f9d](https://linux-hardware.org/?probe=c58e461f9d) | Sep 03, 2020 |
| ASUSTek       | Zephyrus M GM501GS          | Notebook    | [1b62a94c2d](https://linux-hardware.org/?probe=1b62a94c2d) | Sep 03, 2020 |
| HP            | ZBook Studio G3             | Notebook    | [ab052271f5](https://linux-hardware.org/?probe=ab052271f5) | Sep 03, 2020 |
| Samsung       | 530U4E/540U4E               | Notebook    | [0225e13980](https://linux-hardware.org/?probe=0225e13980) | Sep 03, 2020 |
| ASRock        | Z97 Extreme4                | Desktop     | [63353fe20b](https://linux-hardware.org/?probe=63353fe20b) | Sep 03, 2020 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [368ce209d9](https://linux-hardware.org/?probe=368ce209d9) | Sep 03, 2020 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [4bf4f029df](https://linux-hardware.org/?probe=4bf4f029df) | Sep 03, 2020 |
| ASRock        | 970 Extreme4                | Desktop     | [18ee353c55](https://linux-hardware.org/?probe=18ee353c55) | Sep 03, 2020 |
| Gigabyte      | Z87-HD3                     | Desktop     | [488a7a8338](https://linux-hardware.org/?probe=488a7a8338) | Sep 03, 2020 |
| Raspberry ... | Raspberry Pi                | Soc         | [7d51e2e653](https://linux-hardware.org/?probe=7d51e2e653) | Sep 03, 2020 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [fd255f2532](https://linux-hardware.org/?probe=fd255f2532) | Sep 03, 2020 |
| Apple         | MacBookPro12,1              | Notebook    | [a1b06858c1](https://linux-hardware.org/?probe=a1b06858c1) | Sep 03, 2020 |
| Gigabyte      | B85M-HD3                    | Desktop     | [587f334b75](https://linux-hardware.org/?probe=587f334b75) | Sep 03, 2020 |
| Apple         | MacBookPro12,1              | Notebook    | [ffec166d37](https://linux-hardware.org/?probe=ffec166d37) | Sep 03, 2020 |
| Gigabyte      | B85M-HD3                    | Desktop     | [1cdb83831f](https://linux-hardware.org/?probe=1cdb83831f) | Sep 03, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [390dde37d9](https://linux-hardware.org/?probe=390dde37d9) | Sep 03, 2020 |
| MSI           | Z97 GAMING 5                | Desktop     | [0beaa388d7](https://linux-hardware.org/?probe=0beaa388d7) | Sep 03, 2020 |
| Apple         | MacBookAir6,2               | Notebook    | [53f51fb08c](https://linux-hardware.org/?probe=53f51fb08c) | Sep 03, 2020 |
| ASUSTek       | X510UQ                      | Notebook    | [8131ef522a](https://linux-hardware.org/?probe=8131ef522a) | Sep 03, 2020 |
| Medion        | MS-7616                     | Desktop     | [4a3d334430](https://linux-hardware.org/?probe=4a3d334430) | Sep 02, 2020 |
| ASUSTek       | N76VB                       | Notebook    | [d0a2ff590e](https://linux-hardware.org/?probe=d0a2ff590e) | Sep 02, 2020 |
| Medion        | MS-7616                     | Desktop     | [f60cb7c32e](https://linux-hardware.org/?probe=f60cb7c32e) | Sep 02, 2020 |
| Dell          | 0599V5 A06                  | Server      | [018184f964](https://linux-hardware.org/?probe=018184f964) | Sep 02, 2020 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [8639b42e78](https://linux-hardware.org/?probe=8639b42e78) | Sep 02, 2020 |
| MSI           | GX60 3CC                    | Notebook    | [95480b0e35](https://linux-hardware.org/?probe=95480b0e35) | Sep 02, 2020 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [b26d63baac](https://linux-hardware.org/?probe=b26d63baac) | Sep 02, 2020 |
| Medion        | Akoya E1318T                | Notebook    | [31e33c9d63](https://linux-hardware.org/?probe=31e33c9d63) | Sep 01, 2020 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [87547cb8b3](https://linux-hardware.org/?probe=87547cb8b3) | Sep 01, 2020 |
| Apple         | MacBookPro9,2               | Notebook    | [a00607ac5f](https://linux-hardware.org/?probe=a00607ac5f) | Sep 01, 2020 |
| Apple         | MacBookPro9,2               | Notebook    | [e76eecbdaa](https://linux-hardware.org/?probe=e76eecbdaa) | Sep 01, 2020 |
| HP            | ZBook Studio G5             | Notebook    | [4474effbd4](https://linux-hardware.org/?probe=4474effbd4) | Sep 01, 2020 |
| MSI           | GP72M 7REX                  | Notebook    | [08b9ad1081](https://linux-hardware.org/?probe=08b9ad1081) | Sep 01, 2020 |
| Dell          | Latitude D630               | Notebook    | [10c340ddb1](https://linux-hardware.org/?probe=10c340ddb1) | Sep 01, 2020 |
| ASUSTek       | P5K PRO                     | Desktop     | [0c2a333044](https://linux-hardware.org/?probe=0c2a333044) | Sep 01, 2020 |
| Acer          | Aspire A315-51              | Notebook    | [abcf37cb0c](https://linux-hardware.org/?probe=abcf37cb0c) | Sep 01, 2020 |
| ASUSTek       | K53TK                       | Notebook    | [fb10f0e1b6](https://linux-hardware.org/?probe=fb10f0e1b6) | Sep 01, 2020 |
| ASUSTek       | ZenBook UX433FA_RX433FA     | Notebook    | [c5c5d7842d](https://linux-hardware.org/?probe=c5c5d7842d) | Aug 31, 2020 |
| Dell          | XPS 17 9700                 | Notebook    | [53ebfb48a3](https://linux-hardware.org/?probe=53ebfb48a3) | Aug 31, 2020 |
| ASUSTek       | P6T DELUXE                  | Desktop     | [c100066771](https://linux-hardware.org/?probe=c100066771) | Aug 30, 2020 |
| Dell          | Latitude D620               | Notebook    | [2cee9ad674](https://linux-hardware.org/?probe=2cee9ad674) | Aug 29, 2020 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [e4cd61504d](https://linux-hardware.org/?probe=e4cd61504d) | Aug 29, 2020 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [ce54993f5d](https://linux-hardware.org/?probe=ce54993f5d) | Aug 29, 2020 |
| Medion        | Akoya E7416                 | Notebook    | [180701ddac](https://linux-hardware.org/?probe=180701ddac) | Aug 28, 2020 |
| Dell          | 0773VG A00                  | Desktop     | [1ad044293c](https://linux-hardware.org/?probe=1ad044293c) | Aug 28, 2020 |
| MSI           | Z370 PC PRO                 | Desktop     | [e93beec26d](https://linux-hardware.org/?probe=e93beec26d) | Aug 28, 2020 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [b0459adaa7](https://linux-hardware.org/?probe=b0459adaa7) | Aug 28, 2020 |
| Acer          | Aspire ES1-512              | Notebook    | [9c0a45470d](https://linux-hardware.org/?probe=9c0a45470d) | Aug 28, 2020 |
| ASUSTek       | N53SV                       | Notebook    | [eacd03fc77](https://linux-hardware.org/?probe=eacd03fc77) | Aug 27, 2020 |
| Dell          | Inspiron 5557               | Notebook    | [09095e1ecf](https://linux-hardware.org/?probe=09095e1ecf) | Aug 27, 2020 |
| ASUSTek       | N53SV                       | Notebook    | [57ae84508b](https://linux-hardware.org/?probe=57ae84508b) | Aug 27, 2020 |
| Acer          | Aspire 9920 Aspire 9920     | Notebook    | [d1a0e6a322](https://linux-hardware.org/?probe=d1a0e6a322) | Aug 26, 2020 |
| Acer          | Spin SP513-54N              | Convertible | [15851cd5d6](https://linux-hardware.org/?probe=15851cd5d6) | Aug 26, 2020 |
| Acer          | Spin SP513-54N              | Convertible | [99f97194d2](https://linux-hardware.org/?probe=99f97194d2) | Aug 26, 2020 |
| HP            | 339A                        | Desktop     | [6565380ec2](https://linux-hardware.org/?probe=6565380ec2) | Aug 26, 2020 |
| Acer          | Swift SF114-32              | Notebook    | [179b01c469](https://linux-hardware.org/?probe=179b01c469) | Aug 25, 2020 |
| Dell          | 0W7H8C A03                  | Server      | [b5fdc70e19](https://linux-hardware.org/?probe=b5fdc70e19) | Aug 25, 2020 |
| Lenovo        | ThinkPad T450s 20BWS17H0... | Notebook    | [6f245259d5](https://linux-hardware.org/?probe=6f245259d5) | Aug 25, 2020 |
| Hampoo        | Cherry Trail CR             | Notebook    | [adcbc1af5f](https://linux-hardware.org/?probe=adcbc1af5f) | Aug 25, 2020 |
| Hampoo        | Cherry Trail CR             | Notebook    | [b2a99bdee8](https://linux-hardware.org/?probe=b2a99bdee8) | Aug 25, 2020 |
| Dell          | 0773VG A00                  | Desktop     | [7011550263](https://linux-hardware.org/?probe=7011550263) | Aug 23, 2020 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [00834d5b62](https://linux-hardware.org/?probe=00834d5b62) | Aug 23, 2020 |
| Dell          | 0773VG A00                  | Desktop     | [57daef2be7](https://linux-hardware.org/?probe=57daef2be7) | Aug 23, 2020 |
| Dell          | XPS 13 9380                 | Notebook    | [ab6b629076](https://linux-hardware.org/?probe=ab6b629076) | Aug 23, 2020 |
| ASUSTek       | M4N68T                      | Desktop     | [12daabedc0](https://linux-hardware.org/?probe=12daabedc0) | Aug 23, 2020 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [0a3570e8fc](https://linux-hardware.org/?probe=0a3570e8fc) | Aug 23, 2020 |
| Acer          | Swift SF314-56G             | Notebook    | [483472ff3c](https://linux-hardware.org/?probe=483472ff3c) | Aug 21, 2020 |
| Lenovo        | ThinkPad T420 4236PRG       | Notebook    | [909b7ff191](https://linux-hardware.org/?probe=909b7ff191) | Aug 21, 2020 |
| HP            | 212B                        | Desktop     | [2ec5e51a63](https://linux-hardware.org/?probe=2ec5e51a63) | Aug 21, 2020 |
| Lenovo        | ThinkPad T420 4236PRG       | Notebook    | [3f035061a7](https://linux-hardware.org/?probe=3f035061a7) | Aug 21, 2020 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [532be87782](https://linux-hardware.org/?probe=532be87782) | Aug 20, 2020 |
| Unknown       | Unknown                     | Phone       | [77d25775f4](https://linux-hardware.org/?probe=77d25775f4) | Aug 20, 2020 |
| MSI           | GE65 Raider 9SE             | Notebook    | [9d51fe9468](https://linux-hardware.org/?probe=9d51fe9468) | Aug 20, 2020 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [858df13bbc](https://linux-hardware.org/?probe=858df13bbc) | Aug 20, 2020 |
| Acer          | Aspire A114-32              | Notebook    | [7f178a7089](https://linux-hardware.org/?probe=7f178a7089) | Aug 20, 2020 |
| Google        | Edgar                       | Notebook    | [ab25bf9595](https://linux-hardware.org/?probe=ab25bf9595) | Aug 20, 2020 |
| Dell          | Latitude E6410              | Notebook    | [650b03c57a](https://linux-hardware.org/?probe=650b03c57a) | Aug 19, 2020 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [9b4d2c057e](https://linux-hardware.org/?probe=9b4d2c057e) | Aug 19, 2020 |
| Intel         | DN2820FYK H24582-201        | Desktop     | [1b1964b688](https://linux-hardware.org/?probe=1b1964b688) | Aug 19, 2020 |
| Dell          | Latitude E6220              | Notebook    | [cfa9971ad6](https://linux-hardware.org/?probe=cfa9971ad6) | Aug 19, 2020 |
| Dell          | Latitude E6220              | Notebook    | [0b5903e0ce](https://linux-hardware.org/?probe=0b5903e0ce) | Aug 19, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9ec1ddedd4](https://linux-hardware.org/?probe=9ec1ddedd4) | Aug 18, 2020 |
| HP            | Spectre x360 Convertible    | Convertible | [5aa43175bd](https://linux-hardware.org/?probe=5aa43175bd) | Aug 18, 2020 |
| HP            | 1497                        | Desktop     | [d91b32bb86](https://linux-hardware.org/?probe=d91b32bb86) | Aug 18, 2020 |
| HP            | Compaq 6730b (NN204ET#AB... | Notebook    | [e7408dcfa5](https://linux-hardware.org/?probe=e7408dcfa5) | Aug 17, 2020 |
| Notebook      | P95xER                      | Notebook    | [bacf614951](https://linux-hardware.org/?probe=bacf614951) | Aug 17, 2020 |
| ASUSTek       | GL553VW                     | Notebook    | [b84ed4ed7f](https://linux-hardware.org/?probe=b84ed4ed7f) | Aug 16, 2020 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [1789dafea4](https://linux-hardware.org/?probe=1789dafea4) | Aug 16, 2020 |
| MSI           | MS-7513                     | Desktop     | [fa5bfb63a5](https://linux-hardware.org/?probe=fa5bfb63a5) | Aug 16, 2020 |
| System76      | Lemur Pro                   | Notebook    | [42b5653929](https://linux-hardware.org/?probe=42b5653929) | Aug 16, 2020 |
| Dell          | XPS 15 7590                 | Notebook    | [a8e81cc13a](https://linux-hardware.org/?probe=a8e81cc13a) | Aug 15, 2020 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [5648cf98d6](https://linux-hardware.org/?probe=5648cf98d6) | Aug 15, 2020 |
| Dell          | Venue 8 Pro 5830            | Notebook    | [38e5e1e612](https://linux-hardware.org/?probe=38e5e1e612) | Aug 15, 2020 |
| Dell          | Venue 8 Pro 5830            | Notebook    | [e64ea85035](https://linux-hardware.org/?probe=e64ea85035) | Aug 15, 2020 |
| ASUSTek       | Q87M-E                      | Desktop     | [bb59bcf511](https://linux-hardware.org/?probe=bb59bcf511) | Aug 14, 2020 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [46fd96264c](https://linux-hardware.org/?probe=46fd96264c) | Aug 14, 2020 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [2e6f84cebd](https://linux-hardware.org/?probe=2e6f84cebd) | Aug 13, 2020 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [0a11f1e3d8](https://linux-hardware.org/?probe=0a11f1e3d8) | Aug 13, 2020 |
| HP            | 1497                        | Desktop     | [1d640d030f](https://linux-hardware.org/?probe=1d640d030f) | Aug 13, 2020 |
| Lenovo        | ThinkPad L590 20Q8S1J200    | Notebook    | [a53ab805a9](https://linux-hardware.org/?probe=a53ab805a9) | Aug 13, 2020 |
| Acer          | Aspire 7520                 | Notebook    | [d878dbb71e](https://linux-hardware.org/?probe=d878dbb71e) | Aug 13, 2020 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [ce76243437](https://linux-hardware.org/?probe=ce76243437) | Aug 12, 2020 |
| HP            | EliteBook 8540p             | Notebook    | [152d3bf850](https://linux-hardware.org/?probe=152d3bf850) | Aug 11, 2020 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [4d18520109](https://linux-hardware.org/?probe=4d18520109) | Aug 11, 2020 |
| Lenovo        | ThinkPad T495s 20QJ000FM... | Notebook    | [5783469d3d](https://linux-hardware.org/?probe=5783469d3d) | Aug 10, 2020 |
| HP            | ProBook 4510s               | Notebook    | [7de91c360c](https://linux-hardware.org/?probe=7de91c360c) | Aug 10, 2020 |
| ASUSTek       | CM6630_CM6730_CM6830        | Desktop     | [c37ffa0d1f](https://linux-hardware.org/?probe=c37ffa0d1f) | Aug 09, 2020 |
| Acer          | Veriton X4640G V:1.1        | Desktop     | [fca8a5b540](https://linux-hardware.org/?probe=fca8a5b540) | Aug 09, 2020 |
| Toshiba       | Satellite C660              | Notebook    | [90db4cc4d1](https://linux-hardware.org/?probe=90db4cc4d1) | Aug 07, 2020 |
| Intel         | MAHOBAY                     | Desktop     | [c0dde75b94](https://linux-hardware.org/?probe=c0dde75b94) | Aug 06, 2020 |
| HP            | 3647h                       | Desktop     | [f8ef8bf474](https://linux-hardware.org/?probe=f8ef8bf474) | Aug 05, 2020 |
| Dell          | XPS 13 9360                 | Notebook    | [2f78aa8493](https://linux-hardware.org/?probe=2f78aa8493) | Aug 05, 2020 |
| Acer          | One S1003                   | Tablet      | [5f28f7354b](https://linux-hardware.org/?probe=5f28f7354b) | Aug 05, 2020 |
| Lenovo        | ThinkPad T500 2089WPF       | Notebook    | [2ccba9c959](https://linux-hardware.org/?probe=2ccba9c959) | Aug 03, 2020 |
| Samsung       | NC210/NC110                 | Notebook    | [5ec25fc1a7](https://linux-hardware.org/?probe=5ec25fc1a7) | Aug 03, 2020 |
| ASUSTek       | P9X79 DELUXE                | Desktop     | [bd1790913e](https://linux-hardware.org/?probe=bd1790913e) | Aug 03, 2020 |
| HP            | ProBook 6550b               | Notebook    | [6e29ae91ff](https://linux-hardware.org/?probe=6e29ae91ff) | Aug 02, 2020 |
| Acer          | Chapala                     | Notebook    | [709c333693](https://linux-hardware.org/?probe=709c333693) | Aug 02, 2020 |
| Acer          | Chapala                     | Notebook    | [6d9d4616c7](https://linux-hardware.org/?probe=6d9d4616c7) | Aug 02, 2020 |
| Lenovo        | ThinkPad X260 20F5000RSG    | Notebook    | [0368e4c996](https://linux-hardware.org/?probe=0368e4c996) | Aug 01, 2020 |
| Toshiba       | Satellite L850-14L          | Notebook    | [3c7f413bf7](https://linux-hardware.org/?probe=3c7f413bf7) | Aug 01, 2020 |
| Intel         | MAHOBAY                     | Desktop     | [f79f3b002e](https://linux-hardware.org/?probe=f79f3b002e) | Jul 31, 2020 |
| Acer          | Aspire 7720                 | Notebook    | [99c73340ba](https://linux-hardware.org/?probe=99c73340ba) | Jul 31, 2020 |
| ASUSTek       | K50IJ                       | Notebook    | [9fbf3bc839](https://linux-hardware.org/?probe=9fbf3bc839) | Jul 31, 2020 |
| ASUSTek       | K50IJ                       | Notebook    | [341db39a5d](https://linux-hardware.org/?probe=341db39a5d) | Jul 31, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [fff84548aa](https://linux-hardware.org/?probe=fff84548aa) | Jul 30, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [c13b45a4ff](https://linux-hardware.org/?probe=c13b45a4ff) | Jul 30, 2020 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [71ec735f2d](https://linux-hardware.org/?probe=71ec735f2d) | Jul 30, 2020 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [236b52433f](https://linux-hardware.org/?probe=236b52433f) | Jul 29, 2020 |
| Acer          | Aspire 7520                 | Notebook    | [8e2cccfb97](https://linux-hardware.org/?probe=8e2cccfb97) | Jul 28, 2020 |
| ASUSTek       | P9X79 DELUXE                | Desktop     | [3ee7d0dc49](https://linux-hardware.org/?probe=3ee7d0dc49) | Jul 28, 2020 |
| HP            | G62                         | Notebook    | [2e41eeac58](https://linux-hardware.org/?probe=2e41eeac58) | Jul 28, 2020 |
| Acer          | Aspire 7520                 | Notebook    | [818cf10a71](https://linux-hardware.org/?probe=818cf10a71) | Jul 28, 2020 |
| HP            | G62                         | Notebook    | [65ef1efc27](https://linux-hardware.org/?probe=65ef1efc27) | Jul 28, 2020 |
| HP            | ProBook 450 G4              | Notebook    | [a50f775904](https://linux-hardware.org/?probe=a50f775904) | Jul 28, 2020 |
| HP            | ProBook 450 G4              | Notebook    | [289fdd4b71](https://linux-hardware.org/?probe=289fdd4b71) | Jul 28, 2020 |
| Google        | Coral                       | Notebook    | [a7fd3eea00](https://linux-hardware.org/?probe=a7fd3eea00) | Jul 27, 2020 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [cbcb48792e](https://linux-hardware.org/?probe=cbcb48792e) | Jul 27, 2020 |
| ASUSTek       | E45M1-M PRO                 | Desktop     | [b4e6ad4325](https://linux-hardware.org/?probe=b4e6ad4325) | Jul 25, 2020 |
| HP            | 1497                        | Desktop     | [ef31cca294](https://linux-hardware.org/?probe=ef31cca294) | Jul 25, 2020 |
| ASRock        | X399 Taichi                 | Desktop     | [325996fbbc](https://linux-hardware.org/?probe=325996fbbc) | Jul 25, 2020 |
| ASUSTek       | K52F                        | Notebook    | [26641f81f2](https://linux-hardware.org/?probe=26641f81f2) | Jul 25, 2020 |
| Lenovo        | ThinkPad T431s 20ACA06PU... | Notebook    | [7e699b9138](https://linux-hardware.org/?probe=7e699b9138) | Jul 25, 2020 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [48655ae4ad](https://linux-hardware.org/?probe=48655ae4ad) | Jul 24, 2020 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [e25c083873](https://linux-hardware.org/?probe=e25c083873) | Jul 24, 2020 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [41cceef79b](https://linux-hardware.org/?probe=41cceef79b) | Jul 23, 2020 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [34ffe85e1f](https://linux-hardware.org/?probe=34ffe85e1f) | Jul 23, 2020 |
| MSI           | H97 GUARD-PRO               | Desktop     | [ca29557f55](https://linux-hardware.org/?probe=ca29557f55) | Jul 23, 2020 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [f55972e41a](https://linux-hardware.org/?probe=f55972e41a) | Jul 23, 2020 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [b41752e878](https://linux-hardware.org/?probe=b41752e878) | Jul 23, 2020 |
| ASUSTek       | E45M1-M PRO                 | Desktop     | [cf22d23381](https://linux-hardware.org/?probe=cf22d23381) | Jul 22, 2020 |
| Fujitsu       | LIFEBOOK T901               | Notebook    | [0894432e30](https://linux-hardware.org/?probe=0894432e30) | Jul 21, 2020 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [f69af5d26f](https://linux-hardware.org/?probe=f69af5d26f) | Jul 21, 2020 |
| Dell          | XPS 15 7590                 | Notebook    | [d4b2c87aab](https://linux-hardware.org/?probe=d4b2c87aab) | Jul 21, 2020 |
| Dell          | Precision 5540              | Notebook    | [a7ae20a237](https://linux-hardware.org/?probe=a7ae20a237) | Jul 20, 2020 |
| HP            | EliteBook 840 G3            | Notebook    | [08ca93b34a](https://linux-hardware.org/?probe=08ca93b34a) | Jul 20, 2020 |
| HP            | EliteBook 840 G3            | Notebook    | [b9dd901c1b](https://linux-hardware.org/?probe=b9dd901c1b) | Jul 20, 2020 |
| HP            | Compaq Presario CQ60        | Notebook    | [79c11f4f35](https://linux-hardware.org/?probe=79c11f4f35) | Jul 19, 2020 |
| Samsung       | 530U4E/540U4E               | Notebook    | [8672def9fa](https://linux-hardware.org/?probe=8672def9fa) | Jul 18, 2020 |
| ASUSTek       | K52F                        | Notebook    | [bdd3eb05cf](https://linux-hardware.org/?probe=bdd3eb05cf) | Jul 18, 2020 |
| Dell          | XPS 15 9560                 | Notebook    | [987d62f6ed](https://linux-hardware.org/?probe=987d62f6ed) | Jul 17, 2020 |
| MSI           | B350 PC MATE                | Desktop     | [a32f4bbad4](https://linux-hardware.org/?probe=a32f4bbad4) | Jul 17, 2020 |
| Packard Be... | Veriton M275                | Desktop     | [422ac96231](https://linux-hardware.org/?probe=422ac96231) | Jul 17, 2020 |
| ASUSTek       | K52F                        | Notebook    | [7690f672d5](https://linux-hardware.org/?probe=7690f672d5) | Jul 16, 2020 |
| Packard Be... | IMEDIA S2185                | Desktop     | [6279b73002](https://linux-hardware.org/?probe=6279b73002) | Jul 16, 2020 |
| Dell          | Precision M4700             | Notebook    | [289bb61580](https://linux-hardware.org/?probe=289bb61580) | Jul 16, 2020 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [ead1bdd199](https://linux-hardware.org/?probe=ead1bdd199) | Jul 16, 2020 |
| Dell          | Latitude 7390               | Notebook    | [72b667003a](https://linux-hardware.org/?probe=72b667003a) | Jul 16, 2020 |
| Intel         | NUC8i7HVB J68196-503        | Mini pc     | [d4583b58fe](https://linux-hardware.org/?probe=d4583b58fe) | Jul 16, 2020 |
| Packard Be... | IMEDIA S2185                | Desktop     | [13760f9004](https://linux-hardware.org/?probe=13760f9004) | Jul 15, 2020 |
| Dell          | Precision M90               | Notebook    | [914b3eee26](https://linux-hardware.org/?probe=914b3eee26) | Jul 15, 2020 |
| Medion        | H110H4-EM2                  | Desktop     | [180d6f662c](https://linux-hardware.org/?probe=180d6f662c) | Jul 14, 2020 |
| HP            | EliteBook 850 G3            | Notebook    | [529b5be1b5](https://linux-hardware.org/?probe=529b5be1b5) | Jul 14, 2020 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | Notebook    | [43a917118a](https://linux-hardware.org/?probe=43a917118a) | Jul 14, 2020 |
| ASUSTek       | P5QL PRO                    | Desktop     | [84fcdb52ef](https://linux-hardware.org/?probe=84fcdb52ef) | Jul 14, 2020 |
| ASUSTek       | ROG STRIX X299-XE GAMING    | Desktop     | [8431be310d](https://linux-hardware.org/?probe=8431be310d) | Jul 14, 2020 |
| ASRock        | P55 Pro                     | Desktop     | [8e89302495](https://linux-hardware.org/?probe=8e89302495) | Jul 14, 2020 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [e20ae600e7](https://linux-hardware.org/?probe=e20ae600e7) | Jul 13, 2020 |
| ASRock        | B450 Gaming K4              | Desktop     | [994119d6f6](https://linux-hardware.org/?probe=994119d6f6) | Jul 11, 2020 |
| Sony          | VGN-P11Z_G                  | Notebook    | [7615c6d02b](https://linux-hardware.org/?probe=7615c6d02b) | Jul 11, 2020 |
| HP            | 2820h                       | Desktop     | [4c52a559b2](https://linux-hardware.org/?probe=4c52a559b2) | Jul 11, 2020 |
| HP            | 3048h                       | Desktop     | [d5a59e4d72](https://linux-hardware.org/?probe=d5a59e4d72) | Jul 11, 2020 |
| ASRock        | B450 Gaming K4              | Desktop     | [c3658c312d](https://linux-hardware.org/?probe=c3658c312d) | Jul 11, 2020 |
| Gigabyte      | B450M S2H                   | Desktop     | [93b9ba0c1d](https://linux-hardware.org/?probe=93b9ba0c1d) | Jul 11, 2020 |
| Dell          | XPS 15 9560                 | Notebook    | [63d3bdd37e](https://linux-hardware.org/?probe=63d3bdd37e) | Jul 10, 2020 |
| HP            | ProBook 440 G4              | Notebook    | [bdacffe665](https://linux-hardware.org/?probe=bdacffe665) | Jul 10, 2020 |
| Dell          | 0J8H4R A00                  | Desktop     | [9a85f778c4](https://linux-hardware.org/?probe=9a85f778c4) | Jul 10, 2020 |
| ASUSTek       | ZenBook UX431FA_UX431FA     | Notebook    | [05fd7017cd](https://linux-hardware.org/?probe=05fd7017cd) | Jul 10, 2020 |
| Dell          | Latitude 7390               | Notebook    | [f054294bac](https://linux-hardware.org/?probe=f054294bac) | Jul 10, 2020 |
| Dell          | XPS 15 9560                 | Notebook    | [4924ca9182](https://linux-hardware.org/?probe=4924ca9182) | Jul 09, 2020 |
| ASUSTek       | M4A78LT-M                   | Desktop     | [d370221a33](https://linux-hardware.org/?probe=d370221a33) | Jul 09, 2020 |
| MSI           | Prestige 15 A10SC           | Notebook    | [58ef520c43](https://linux-hardware.org/?probe=58ef520c43) | Jul 09, 2020 |
| MSI           | Prestige 15 A10SC           | Notebook    | [d7d44f6154](https://linux-hardware.org/?probe=d7d44f6154) | Jul 09, 2020 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d629a23c3c](https://linux-hardware.org/?probe=d629a23c3c) | Jul 08, 2020 |
| ASUSTek       | Leonite2                    | Desktop     | [982bee04b0](https://linux-hardware.org/?probe=982bee04b0) | Jul 08, 2020 |
| ASUSTek       | Q87M-E                      | Desktop     | [4c1fd357f4](https://linux-hardware.org/?probe=4c1fd357f4) | Jul 08, 2020 |
| Acer          | Aspire 5742G                | Notebook    | [50b3972995](https://linux-hardware.org/?probe=50b3972995) | Jul 08, 2020 |
| Acer          | Nitro AN517-51              | Notebook    | [c796207530](https://linux-hardware.org/?probe=c796207530) | Jul 08, 2020 |
| Dell          | Inspiron 5491 2n1           | Convertible | [027944dede](https://linux-hardware.org/?probe=027944dede) | Jul 07, 2020 |
| HP            | EliteBook 840 G6            | Notebook    | [1a175eee47](https://linux-hardware.org/?probe=1a175eee47) | Jul 07, 2020 |
| MSI           | Prestige 15 A10SC           | Notebook    | [b89eb4168e](https://linux-hardware.org/?probe=b89eb4168e) | Jul 06, 2020 |
| HP            | ProBook 450 G4              | Notebook    | [844578109a](https://linux-hardware.org/?probe=844578109a) | Jul 06, 2020 |
| Acer          | Aspire 7520                 | Notebook    | [d2d6a3d4e6](https://linux-hardware.org/?probe=d2d6a3d4e6) | Jul 06, 2020 |
| ASRock        | J4105M                      | Desktop     | [7677c5d88e](https://linux-hardware.org/?probe=7677c5d88e) | Jul 05, 2020 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [23faee185b](https://linux-hardware.org/?probe=23faee185b) | Jul 05, 2020 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [884c20e57a](https://linux-hardware.org/?probe=884c20e57a) | Jul 04, 2020 |
| Notebook      | P9XXEN_EF_ED                | Notebook    | [f930622ffe](https://linux-hardware.org/?probe=f930622ffe) | Jul 04, 2020 |
| Dell          | Latitude 5300               | Notebook    | [65284e0295](https://linux-hardware.org/?probe=65284e0295) | Jul 04, 2020 |
| HP            | 1791                        | Desktop     | [685526db7c](https://linux-hardware.org/?probe=685526db7c) | Jul 04, 2020 |
| HP            | 1791                        | Desktop     | [7cfbc9a18c](https://linux-hardware.org/?probe=7cfbc9a18c) | Jul 04, 2020 |
| Acer          | Veriton L4610G              | Desktop     | [a6b3ba6f49](https://linux-hardware.org/?probe=a6b3ba6f49) | Jul 04, 2020 |
| Lenovo        | ThinkPad A485 20MUCTO1WW    | Notebook    | [359f4615fa](https://linux-hardware.org/?probe=359f4615fa) | Jul 03, 2020 |
| HPE           | ProLiant DL360 Gen10        | Server      | [352fee0e7f](https://linux-hardware.org/?probe=352fee0e7f) | Jul 03, 2020 |
| Lenovo        | ThinkPad L470 20J4002FMH    | Notebook    | [f5262493e1](https://linux-hardware.org/?probe=f5262493e1) | Jul 03, 2020 |
| Acer          | Aspire E5-521               | Notebook    | [52cc50cce3](https://linux-hardware.org/?probe=52cc50cce3) | Jul 02, 2020 |
| Apple         | MacBookAir4,1               | Notebook    | [20b063b667](https://linux-hardware.org/?probe=20b063b667) | Jul 02, 2020 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [3dab9867c3](https://linux-hardware.org/?probe=3dab9867c3) | Jul 02, 2020 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [3123634f83](https://linux-hardware.org/?probe=3123634f83) | Jul 02, 2020 |
| Alienware     | 17 R4                       | Notebook    | [719e71f732](https://linux-hardware.org/?probe=719e71f732) | Jul 01, 2020 |
| ASUSTek       | Hematite                    | Desktop     | [808fceee5d](https://linux-hardware.org/?probe=808fceee5d) | Jul 01, 2020 |
| HP            | EliteBook 840 G6            | Notebook    | [a1a5f19b97](https://linux-hardware.org/?probe=a1a5f19b97) | Jul 01, 2020 |
| HP            | EliteBook 840 G6            | Notebook    | [4a8b4959c2](https://linux-hardware.org/?probe=4a8b4959c2) | Jul 01, 2020 |
| ASUSTek       | Hematite                    | Desktop     | [19944fac99](https://linux-hardware.org/?probe=19944fac99) | Jul 01, 2020 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [7cb20a8170](https://linux-hardware.org/?probe=7cb20a8170) | Jul 01, 2020 |
| MSI           | 970A-G46                    | Desktop     | [9fe4406d67](https://linux-hardware.org/?probe=9fe4406d67) | Jul 01, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [a960a3762f](https://linux-hardware.org/?probe=a960a3762f) | Jul 01, 2020 |
| Dell          | XPS 15 7590                 | Notebook    | [258c0a5093](https://linux-hardware.org/?probe=258c0a5093) | Jun 30, 2020 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [f719e48a04](https://linux-hardware.org/?probe=f719e48a04) | Jun 30, 2020 |
| Dell          | XPS 15 7590                 | Notebook    | [29d813936b](https://linux-hardware.org/?probe=29d813936b) | Jun 29, 2020 |
| Biostar       | A10N-8800E                  | Desktop     | [3943d3c1f2](https://linux-hardware.org/?probe=3943d3c1f2) | Jun 29, 2020 |
| Apple         | MacBookAir4,1               | Notebook    | [b69102bd6b](https://linux-hardware.org/?probe=b69102bd6b) | Jun 28, 2020 |
| Acer          | TravelMate 5742ZG           | Notebook    | [727591a399](https://linux-hardware.org/?probe=727591a399) | Jun 28, 2020 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [4347672a65](https://linux-hardware.org/?probe=4347672a65) | Jun 28, 2020 |
| Dell          | 0773VG A00                  | Desktop     | [bde6f8112f](https://linux-hardware.org/?probe=bde6f8112f) | Jun 28, 2020 |
| Acer          | Swift SF314-57              | Notebook    | [6f94930e8e](https://linux-hardware.org/?probe=6f94930e8e) | Jun 28, 2020 |
| Acer          | Aspire V3-771               | Notebook    | [e255f13987](https://linux-hardware.org/?probe=e255f13987) | Jun 28, 2020 |
| Acer          | Aspire V3-771               | Notebook    | [b0a48a42dd](https://linux-hardware.org/?probe=b0a48a42dd) | Jun 28, 2020 |
| ASUSTek       | Leonite2                    | Desktop     | [12ce72fcbd](https://linux-hardware.org/?probe=12ce72fcbd) | Jun 27, 2020 |
| Dell          | Precision 5520              | Notebook    | [751f4c96a3](https://linux-hardware.org/?probe=751f4c96a3) | Jun 27, 2020 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [05e6c3c6bc](https://linux-hardware.org/?probe=05e6c3c6bc) | Jun 26, 2020 |
| Dell          | XPS 13 7390                 | Notebook    | [598acef23f](https://linux-hardware.org/?probe=598acef23f) | Jun 26, 2020 |
| Acer          | Peppy                       | Notebook    | [c858e37129](https://linux-hardware.org/?probe=c858e37129) | Jun 26, 2020 |
| Dell          | 0773VG A00                  | Desktop     | [046d3ac2ef](https://linux-hardware.org/?probe=046d3ac2ef) | Jun 26, 2020 |
| Acer          | Peppy                       | Notebook    | [773efcf87c](https://linux-hardware.org/?probe=773efcf87c) | Jun 25, 2020 |
| HP            | EliteBook 8440p             | Notebook    | [841e46f062](https://linux-hardware.org/?probe=841e46f062) | Jun 25, 2020 |
| Lenovo        | ThinkPad E15 20RD004FMH     | Notebook    | [4bd7b759cb](https://linux-hardware.org/?probe=4bd7b759cb) | Jun 23, 2020 |
| ASUSTek       | X705UDR                     | Notebook    | [30f73b5b7f](https://linux-hardware.org/?probe=30f73b5b7f) | Jun 23, 2020 |
| ASUSTek       | X705UDR                     | Notebook    | [bd1d0f1829](https://linux-hardware.org/?probe=bd1d0f1829) | Jun 23, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [326b11f044](https://linux-hardware.org/?probe=326b11f044) | Jun 22, 2020 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [019f7ecfc7](https://linux-hardware.org/?probe=019f7ecfc7) | Jun 22, 2020 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [9d863f1440](https://linux-hardware.org/?probe=9d863f1440) | Jun 22, 2020 |
| Acer          | Swift SF314-55              | Notebook    | [50c925adf2](https://linux-hardware.org/?probe=50c925adf2) | Jun 22, 2020 |
| Dell          | XPS 15 9560                 | Notebook    | [fd0f1c10ea](https://linux-hardware.org/?probe=fd0f1c10ea) | Jun 22, 2020 |
| Dell          | 0N826N A03                  | Desktop     | [6bae57ac48](https://linux-hardware.org/?probe=6bae57ac48) | Jun 21, 2020 |
| Dell          | 0Y2MRG A00                  | Desktop     | [c64fcf2a5d](https://linux-hardware.org/?probe=c64fcf2a5d) | Jun 21, 2020 |
| HP            | EliteBook 745 G2            | Notebook    | [9e3d4f423a](https://linux-hardware.org/?probe=9e3d4f423a) | Jun 21, 2020 |
| HP            | EliteBook 745 G2            | Notebook    | [07027013e9](https://linux-hardware.org/?probe=07027013e9) | Jun 21, 2020 |
| HP            | Laptop 17-bs1xx             | Notebook    | [195819dd0b](https://linux-hardware.org/?probe=195819dd0b) | Jun 21, 2020 |
| Lenovo        | ThinkPad P51 W10DG 20MNS... | Notebook    | [31741c6aa1](https://linux-hardware.org/?probe=31741c6aa1) | Jun 21, 2020 |
| Dell          | 0Y2MRG A00                  | Desktop     | [21bd837ffa](https://linux-hardware.org/?probe=21bd837ffa) | Jun 20, 2020 |
| Dell          | 0N826N A03                  | Desktop     | [e5d1b05e9f](https://linux-hardware.org/?probe=e5d1b05e9f) | Jun 19, 2020 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [031299eea4](https://linux-hardware.org/?probe=031299eea4) | Jun 19, 2020 |
| Biostar       | TB250-BTC                   | Desktop     | [7c56efb9cd](https://linux-hardware.org/?probe=7c56efb9cd) | Jun 19, 2020 |
| HP            | ZBook 15 G3                 | Notebook    | [a78d1dc06e](https://linux-hardware.org/?probe=a78d1dc06e) | Jun 19, 2020 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [eea45be825](https://linux-hardware.org/?probe=eea45be825) | Jun 19, 2020 |
| Dell          | XPS 13 9300                 | Notebook    | [fd7a1b9ce0](https://linux-hardware.org/?probe=fd7a1b9ce0) | Jun 19, 2020 |
| Biostar       | A10N-8800E                  | Desktop     | [a745e33262](https://linux-hardware.org/?probe=a745e33262) | Jun 19, 2020 |
| Sony          | VPCF23P1E                   | Notebook    | [2e0915f8a9](https://linux-hardware.org/?probe=2e0915f8a9) | Jun 18, 2020 |
| Dell          | Latitude 5300               | Notebook    | [8ebae81f7c](https://linux-hardware.org/?probe=8ebae81f7c) | Jun 18, 2020 |
| Biostar       | TB250-BTC                   | Desktop     | [9401828e3e](https://linux-hardware.org/?probe=9401828e3e) | Jun 18, 2020 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [2c0dcbae5e](https://linux-hardware.org/?probe=2c0dcbae5e) | Jun 16, 2020 |
| ASRock        | X570 Taichi                 | Desktop     | [d12eef2feb](https://linux-hardware.org/?probe=d12eef2feb) | Jun 16, 2020 |
| Dell          | Latitude 7400               | Notebook    | [bef95ed2c8](https://linux-hardware.org/?probe=bef95ed2c8) | Jun 16, 2020 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | Notebook    | [c3cf636984](https://linux-hardware.org/?probe=c3cf636984) | Jun 16, 2020 |
| Alienware     | 07JNH0 A00                  | Desktop     | [2951b9c787](https://linux-hardware.org/?probe=2951b9c787) | Jun 16, 2020 |
| Dell          | Latitude D630               | Notebook    | [256a715a94](https://linux-hardware.org/?probe=256a715a94) | Jun 16, 2020 |
| HP            | 3048h                       | Desktop     | [de98bd1bfa](https://linux-hardware.org/?probe=de98bd1bfa) | Jun 15, 2020 |
| Acer          | Aspire E5-521               | Notebook    | [7830dcd3e6](https://linux-hardware.org/?probe=7830dcd3e6) | Jun 15, 2020 |
| Samsung       | RC530/RC730                 | Notebook    | [42eab22006](https://linux-hardware.org/?probe=42eab22006) | Jun 15, 2020 |
| HP            | EliteBook 8440p             | Notebook    | [1f56fc2fae](https://linux-hardware.org/?probe=1f56fc2fae) | Jun 15, 2020 |
| HP            | 255 G2                      | Notebook    | [1de74926dc](https://linux-hardware.org/?probe=1de74926dc) | Jun 14, 2020 |
| Dell          | Latitude 5480               | Notebook    | [d0d56fbb1d](https://linux-hardware.org/?probe=d0d56fbb1d) | Jun 14, 2020 |
| Notebook      | W9x0LU                      | Notebook    | [862b20ad4a](https://linux-hardware.org/?probe=862b20ad4a) | Jun 14, 2020 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [30d93c4533](https://linux-hardware.org/?probe=30d93c4533) | Jun 14, 2020 |
| ASUSTek       | Basswood                    | Desktop     | [57d0efb326](https://linux-hardware.org/?probe=57d0efb326) | Jun 14, 2020 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [2f3c35745c](https://linux-hardware.org/?probe=2f3c35745c) | Jun 14, 2020 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [efaa58fcc8](https://linux-hardware.org/?probe=efaa58fcc8) | Jun 14, 2020 |
| ASUSTek       | K52F                        | Notebook    | [45cae7fd85](https://linux-hardware.org/?probe=45cae7fd85) | Jun 13, 2020 |
| Acer          | Aspire VN7-791G             | Notebook    | [597601467d](https://linux-hardware.org/?probe=597601467d) | Jun 13, 2020 |
| HP            | EliteBook 8440p             | Notebook    | [f13ca230eb](https://linux-hardware.org/?probe=f13ca230eb) | Jun 13, 2020 |
| Acer          | FIH57                       | All in one  | [306081b9c5](https://linux-hardware.org/?probe=306081b9c5) | Jun 13, 2020 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [b5fee1bf94](https://linux-hardware.org/?probe=b5fee1bf94) | Jun 12, 2020 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [fbbf2e05d2](https://linux-hardware.org/?probe=fbbf2e05d2) | Jun 12, 2020 |
| ASUSTek       | P5K                         | Desktop     | [b2eaae9b33](https://linux-hardware.org/?probe=b2eaae9b33) | Jun 12, 2020 |
| Gigabyte      | B450M S2H                   | Desktop     | [43a4aa57d5](https://linux-hardware.org/?probe=43a4aa57d5) | Jun 12, 2020 |
| Acer          | Swift SF314-58              | Notebook    | [6faaf05f42](https://linux-hardware.org/?probe=6faaf05f42) | Jun 11, 2020 |
| MSI           | B150 PC MATE                | Desktop     | [f60e9ece43](https://linux-hardware.org/?probe=f60e9ece43) | Jun 10, 2020 |
| Fujitsu       | LIFEBOOK P772               | Notebook    | [0589b2e0a0](https://linux-hardware.org/?probe=0589b2e0a0) | Jun 10, 2020 |
| Fujitsu       | LIFEBOOK P772               | Notebook    | [957ad12749](https://linux-hardware.org/?probe=957ad12749) | Jun 09, 2020 |
| Acer          | Aspire S3-391               | Notebook    | [7561b2014d](https://linux-hardware.org/?probe=7561b2014d) | Jun 09, 2020 |
| Dell          | 0HH807                      | Desktop     | [e233bd2a4d](https://linux-hardware.org/?probe=e233bd2a4d) | Jun 09, 2020 |
| Apple         | MacBookAir5,2               | Notebook    | [0f1ebdef37](https://linux-hardware.org/?probe=0f1ebdef37) | Jun 09, 2020 |
| HP            | 0AACh                       | Desktop     | [03c30eff1a](https://linux-hardware.org/?probe=03c30eff1a) | Jun 08, 2020 |
| Packard Be... | EasyNote_SJ51               | Notebook    | [2e57d2a609](https://linux-hardware.org/?probe=2e57d2a609) | Jun 08, 2020 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [683118ef37](https://linux-hardware.org/?probe=683118ef37) | Jun 08, 2020 |
| MSI           | IONA                        | Desktop     | [7d98f45ec2](https://linux-hardware.org/?probe=7d98f45ec2) | Jun 08, 2020 |
| HP            | ProBook 4730s               | Notebook    | [36ab8e3fce](https://linux-hardware.org/?probe=36ab8e3fce) | Jun 07, 2020 |
| Sony          | VGN-P11Z_G                  | Notebook    | [3dbf83be03](https://linux-hardware.org/?probe=3dbf83be03) | Jun 07, 2020 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [b615dce0ce](https://linux-hardware.org/?probe=b615dce0ce) | Jun 07, 2020 |
| ASUSTek       | N751JK                      | Notebook    | [e8f47a4600](https://linux-hardware.org/?probe=e8f47a4600) | Jun 06, 2020 |
| Lenovo        | 0833AL2                     | Desktop     | [e648610bef](https://linux-hardware.org/?probe=e648610bef) | Jun 06, 2020 |
| Acer          | Veriton X4620G V1.0         | Desktop     | [4ffadd9b76](https://linux-hardware.org/?probe=4ffadd9b76) | Jun 06, 2020 |
| Packard Be... | EasyNote TK36               | Notebook    | [e040069d0d](https://linux-hardware.org/?probe=e040069d0d) | Jun 06, 2020 |
| Lenovo        | 0833AL2                     | Desktop     | [582d333d15](https://linux-hardware.org/?probe=582d333d15) | Jun 06, 2020 |
| ASRock        | B450M Pro4                  | Desktop     | [09fde042b6](https://linux-hardware.org/?probe=09fde042b6) | Jun 06, 2020 |
| Packard Be... | EasyNote TK36               | Notebook    | [4a212dec2f](https://linux-hardware.org/?probe=4a212dec2f) | Jun 06, 2020 |
| HP            | Mini 110-3100               | Notebook    | [0379643484](https://linux-hardware.org/?probe=0379643484) | Jun 05, 2020 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [7fa78a7e1d](https://linux-hardware.org/?probe=7fa78a7e1d) | Jun 05, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [3417f87a15](https://linux-hardware.org/?probe=3417f87a15) | Jun 05, 2020 |
| Microsoft     | Surface Pro                 | Tablet      | [a0a89a4431](https://linux-hardware.org/?probe=a0a89a4431) | Jun 05, 2020 |
| ASUSTek       | X756UQK                     | Notebook    | [c587d8fe0a](https://linux-hardware.org/?probe=c587d8fe0a) | Jun 05, 2020 |
| HP            | Pavilion dv9700             | Notebook    | [ac50f54c18](https://linux-hardware.org/?probe=ac50f54c18) | Jun 04, 2020 |
| ASUSTek       | 1225B                       | Notebook    | [9dfff1eb3d](https://linux-hardware.org/?probe=9dfff1eb3d) | Jun 03, 2020 |
| ASUSTek       | 1225B                       | Notebook    | [aca43b35da](https://linux-hardware.org/?probe=aca43b35da) | Jun 03, 2020 |
| Acer          | Aspire 7738                 | Notebook    | [452d04f351](https://linux-hardware.org/?probe=452d04f351) | Jun 03, 2020 |
| Lenovo        | SHARKBAY 31900058 STD or... | Desktop     | [7851d4e40c](https://linux-hardware.org/?probe=7851d4e40c) | Jun 03, 2020 |
| Lenovo        | SHARKBAY 31900058 STD or... | Desktop     | [1bea676492](https://linux-hardware.org/?probe=1bea676492) | Jun 03, 2020 |
| Acer          | Aspire 1810TZ               | Notebook    | [45ccb6143d](https://linux-hardware.org/?probe=45ccb6143d) | Jun 03, 2020 |
| HP            | 213D A01                    | Desktop     | [35b53f617e](https://linux-hardware.org/?probe=35b53f617e) | Jun 03, 2020 |
| HP            | 213D A01                    | Desktop     | [32547410a5](https://linux-hardware.org/?probe=32547410a5) | Jun 03, 2020 |
| Lenovo        | ThinkPad X240 20AMS70D00    | Notebook    | [02e0881f6f](https://linux-hardware.org/?probe=02e0881f6f) | Jun 01, 2020 |
| Lenovo        | IdeaPad 330S-14IKB U 81F... | Notebook    | [6eee76c0de](https://linux-hardware.org/?probe=6eee76c0de) | Jun 01, 2020 |
| Dell          | System XPS L502X            | Notebook    | [2f5ce6894f](https://linux-hardware.org/?probe=2f5ce6894f) | May 31, 2020 |
| HP            | 15                          | Notebook    | [6e8c13d052](https://linux-hardware.org/?probe=6e8c13d052) | May 30, 2020 |
| ASUSTek       | P8Z68-V                     | Desktop     | [0fedb7707a](https://linux-hardware.org/?probe=0fedb7707a) | May 30, 2020 |
| MSI           | GX700                       | Notebook    | [3f04da7d3f](https://linux-hardware.org/?probe=3f04da7d3f) | May 29, 2020 |
| MSI           | GP62 7RD                    | Notebook    | [8815b05b9d](https://linux-hardware.org/?probe=8815b05b9d) | May 29, 2020 |
| HP            | Notebook                    | Notebook    | [264c81dc81](https://linux-hardware.org/?probe=264c81dc81) | May 29, 2020 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [3edf71cb2e](https://linux-hardware.org/?probe=3edf71cb2e) | May 28, 2020 |
| ASUSTek       | UX31A                       | Notebook    | [3ec81caa8d](https://linux-hardware.org/?probe=3ec81caa8d) | May 28, 2020 |
| Medion        | E6415 MD60848               | Notebook    | [6a9987d214](https://linux-hardware.org/?probe=6a9987d214) | May 28, 2020 |
| Notebook      | NH55RGQ                     | Notebook    | [f2f21426d6](https://linux-hardware.org/?probe=f2f21426d6) | May 28, 2020 |
| HP            | Laptop 15-db1xxx            | Notebook    | [3d95f1786b](https://linux-hardware.org/?probe=3d95f1786b) | May 28, 2020 |
| Lenovo        | ThinkPad W550s 20E1S0L50... | Notebook    | [f4657ce6c7](https://linux-hardware.org/?probe=f4657ce6c7) | May 27, 2020 |
| HP            | Laptop 15-db1xxx            | Notebook    | [d81c93199c](https://linux-hardware.org/?probe=d81c93199c) | May 27, 2020 |
| Toshiba       | Satellite L870-141          | Notebook    | [f16ec3024d](https://linux-hardware.org/?probe=f16ec3024d) | May 27, 2020 |
| Toshiba       | Satellite L870-141          | Notebook    | [d4a67162b6](https://linux-hardware.org/?probe=d4a67162b6) | May 27, 2020 |
| MSI           | IONA                        | Desktop     | [338a663a47](https://linux-hardware.org/?probe=338a663a47) | May 26, 2020 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [ec9adc1cdc](https://linux-hardware.org/?probe=ec9adc1cdc) | May 26, 2020 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [aa53a3eba5](https://linux-hardware.org/?probe=aa53a3eba5) | May 26, 2020 |
| Lenovo        | ThinkCentre M58 7359WK5     | Desktop     | [1b004d7746](https://linux-hardware.org/?probe=1b004d7746) | May 26, 2020 |
| Apple         | MacBookAir5,2               | Notebook    | [279b43d96a](https://linux-hardware.org/?probe=279b43d96a) | May 26, 2020 |
| Linx          | LINX12X64                   | Tablet      | [1af0d056be](https://linux-hardware.org/?probe=1af0d056be) | May 25, 2020 |
| MSI           | GX60 3CC                    | Notebook    | [12a7f3a64f](https://linux-hardware.org/?probe=12a7f3a64f) | May 25, 2020 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | Desktop     | [2840080980](https://linux-hardware.org/?probe=2840080980) | May 25, 2020 |
| Acer          | Prespa M                    | Notebook    | [890a8d820f](https://linux-hardware.org/?probe=890a8d820f) | May 24, 2020 |
| Dell          | 0X231R A01                  | Desktop     | [f49d48a769](https://linux-hardware.org/?probe=f49d48a769) | May 24, 2020 |
| HP            | G61                         | Notebook    | [fcf7874b89](https://linux-hardware.org/?probe=fcf7874b89) | May 24, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Netherlands/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 528       | 18.16%  |
| Ubuntu 18.04                 | 305       | 10.49%  |
| OpenMandriva 4.3             | 73        | 2.51%   |
| Ubuntu 20.10                 | 65        | 2.24%   |
| Arch                         | 63        | 2.17%   |
| Xubuntu 20.04                | 54        | 1.86%   |
| OpenMandriva 4.2             | 54        | 1.86%   |
| Fedora 34                    | 53        | 1.82%   |
| Linux Mint 20.2              | 50        | 1.72%   |
| Ubuntu 21.10                 | 49        | 1.69%   |
| Ubuntu 21.04                 | 46        | 1.58%   |
| KDE neon 20.04               | 46        | 1.58%   |
| Linux Mint 19.3              | 45        | 1.55%   |
| Debian 11                    | 45        | 1.55%   |
| Zorin 16                     | 44        | 1.51%   |
| Linux Mint 20.1              | 44        | 1.51%   |
| Ubuntu 19.10                 | 43        | 1.48%   |
| Linux Mint 20.3              | 43        | 1.48%   |
| Pop!_OS 20.10                | 41        | 1.41%   |
| Fedora 33                    | 41        | 1.41%   |
| Pop!_OS 20.04                | 39        | 1.34%   |
| Pop!_OS 21.04                | 38        | 1.31%   |
| Fedora 31                    | 38        | 1.31%   |
| Fedora 35                    | 37        | 1.27%   |
| Zorin 15                     | 36        | 1.24%   |
| Linux Mint 20                | 36        | 1.24%   |
| Ubuntu 19.04                 | 35        | 1.2%    |
| Manjaro                      | 35        | 1.2%    |
| Kubuntu 20.04                | 35        | 1.2%    |
| Pop!_OS 21.10                | 34        | 1.17%   |
| Fedora 32                    | 33        | 1.13%   |
| openSUSE Tumbleweed-XXXXXXXX | 31        | 1.07%   |
| Arch Rolling                 | 31        | 1.07%   |
| Ubuntu 16.04                 | 30        | 1.03%   |
| Debian 10                    | 30        | 1.03%   |
| ArcoLinux Rolling            | 25        | 0.86%   |
| Xubuntu 18.04                | 23        | 0.79%   |
| Ubuntu 22.04                 | 22        | 0.76%   |
| Linux Mint 19.1              | 18        | 0.62%   |
| Ubuntu 18.10                 | 16        | 0.55%   |
| Linux Mint 19.2              | 15        | 0.52%   |
| Gentoo 2.7                   | 15        | 0.52%   |
| Debian Testing               | 15        | 0.52%   |
| Ubuntu MATE 20.04            | 13        | 0.45%   |
| EndeavourOS Rolling          | 12        | 0.41%   |
| Manjaro 20.1                 | 11        | 0.38%   |
| LMDE 4                       | 11        | 0.38%   |
| Kubuntu 21.10                | 11        | 0.38%   |
| Zorin 12                     | 8         | 0.28%   |
| ROSA R10                     | 8         | 0.28%   |
| Peppermint 10                | 8         | 0.28%   |
| Manjaro 20.0.3               | 8         | 0.28%   |
| Lubuntu 20.04                | 8         | 0.28%   |
| Raspbian 10                  | 7         | 0.24%   |
| openSUSE Leap-15.2           | 7         | 0.24%   |
| KDE neon 18.04               | 7         | 0.24%   |
| Fedora 36                    | 7         | 0.24%   |
| Fedora 30                    | 7         | 0.24%   |
| ROSA R11                     | 6         | 0.21%   |
| Manjaro 21.2.1               | 6         | 0.21%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Ubuntu            | 1093      | 39.56%  |
| Linux Mint        | 241       | 8.72%   |
| Fedora            | 191       | 6.91%   |
| Pop!_OS           | 150       | 5.43%   |
| OpenMandriva      | 131       | 4.74%   |
| Manjaro           | 109       | 3.94%   |
| Arch              | 96        | 3.47%   |
| Debian            | 95        | 3.44%   |
| Zorin             | 88        | 3.18%   |
| Xubuntu           | 84        | 3.04%   |
| Kubuntu           | 60        | 2.17%   |
| KDE neon          | 52        | 1.88%   |
| openSUSE          | 43        | 1.56%   |
| ArcoLinux         | 28        | 1.01%   |
| ROSA              | 25        | 0.9%    |
| Gentoo            | 24        | 0.87%   |
| Ubuntu MATE       | 19        | 0.69%   |
| Lubuntu           | 19        | 0.69%   |
| Clear Linux       | 18        | 0.65%   |
| Kali              | 16        | 0.58%   |
| Endless           | 15        | 0.54%   |
| Elementary        | 15        | 0.54%   |
| EndeavourOS       | 14        | 0.51%   |
| Parrot            | 11        | 0.4%    |
| LMDE              | 11        | 0.4%    |
| Ubuntu Budgie     | 10        | 0.36%   |
| Peppermint        | 10        | 0.36%   |
| CentOS            | 9         | 0.33%   |
| Solus             | 8         | 0.29%   |
| Raspbian          | 8         | 0.29%   |
| MX                | 7         | 0.25%   |
| BlackPanther      | 6         | 0.22%   |
| Reborn OS         | 5         | 0.18%   |
| Garuda Linux      | 5         | 0.18%   |
| RHEL              | 4         | 0.14%   |
| SteamOS           | 3         | 0.11%   |
| Devuan            | 3         | 0.11%   |
| Chrome OS         | 3         | 0.11%   |
| Artix             | 3         | 0.11%   |
| Void Linux        | 2         | 0.07%   |
| Oracle Linux      | 2         | 0.07%   |
| MocaccinoOS       | 2         | 0.07%   |
| Manjaro-ARM       | 2         | 0.07%   |
| LinuxFX           | 2         | 0.07%   |
| Linux Lite        | 2         | 0.07%   |
| Android           | 2         | 0.07%   |
| Xero              | 1         | 0.04%   |
| UbuntuDDE         | 1         | 0.04%   |
| Ubuntu Studio     | 1         | 0.04%   |
| Slackware         | 1         | 0.04%   |
| Rockstor          | 1         | 0.04%   |
| Q4OS              | 1         | 0.04%   |
| Point Linux       | 1         | 0.04%   |
| Parabola          | 1         | 0.04%   |
| NixOS             | 1         | 0.04%   |
| Makulu            | 1         | 0.04%   |
| LFS               | 1         | 0.04%   |
| GNOME OS          | 1         | 0.04%   |
| GalliumOS         | 1         | 0.04%   |
| Citrix Hypervisor | 1         | 0.04%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 73        | 2.26%   |
| 5.4.0-42-generic         | 69        | 2.14%   |
| 5.10.14-desktop-1omv4002 | 53        | 1.64%   |
| 5.4.0-58-generic         | 43        | 1.33%   |
| 5.4.0-52-generic         | 36        | 1.11%   |
| 5.8.0-50-generic         | 35        | 1.08%   |
| 5.4.0-48-generic         | 35        | 1.08%   |
| 5.11.0-38-generic        | 31        | 0.96%   |
| 5.8.0-43-generic         | 26        | 0.8%    |
| 5.11.0-27-generic        | 26        | 0.8%    |
| 5.4.0-77-generic         | 25        | 0.77%   |
| 5.4.0-26-generic         | 25        | 0.77%   |
| 5.13.0-28-generic        | 25        | 0.77%   |
| 5.4.0-40-generic         | 24        | 0.74%   |
| 5.4.0-37-generic         | 22        | 0.68%   |
| 5.8.0-53-generic         | 21        | 0.65%   |
| 5.4.0-65-generic         | 21        | 0.65%   |
| 5.11.0-7620-generic      | 21        | 0.65%   |
| 5.8.0-7630-generic       | 20        | 0.62%   |
| 5.4.0-56-generic         | 20        | 0.62%   |
| 5.4.0-33-generic         | 20        | 0.62%   |
| 5.4.0-29-generic         | 20        | 0.62%   |
| 5.13.0-39-generic        | 20        | 0.62%   |
| 5.3.0-46-generic         | 19        | 0.59%   |
| 5.8.0-48-generic         | 18        | 0.56%   |
| 5.4.0-54-generic         | 18        | 0.56%   |
| 5.4.0-47-generic         | 18        | 0.56%   |
| 4.15.0-29-generic        | 18        | 0.56%   |
| 5.8.0-44-generic         | 17        | 0.53%   |
| 5.4.0-74-generic         | 17        | 0.53%   |
| 5.4.0-45-generic         | 17        | 0.53%   |
| 5.3.0-28-generic         | 17        | 0.53%   |
| 5.11.0-41-generic        | 17        | 0.53%   |
| 5.11.0-40-generic        | 17        | 0.53%   |
| 5.11.0-37-generic        | 17        | 0.53%   |
| 5.4.0-91-generic         | 16        | 0.5%    |
| 5.4.0-72-generic         | 16        | 0.5%    |
| 5.3.0-42-generic         | 16        | 0.5%    |
| 5.11.0-43-generic        | 16        | 0.5%    |
| 4.15.0-54-generic        | 16        | 0.5%    |
| 5.4.0-89-generic         | 15        | 0.46%   |
| 5.0.0-37-generic         | 15        | 0.46%   |
| 5.0.0-32-generic         | 15        | 0.46%   |
| 5.0.0-31-generic         | 15        | 0.46%   |
| 5.4.0-81-generic         | 14        | 0.43%   |
| 5.4.0-66-generic         | 14        | 0.43%   |
| 5.13.0-40-generic        | 14        | 0.43%   |
| 4.15.0-43-generic        | 14        | 0.43%   |
| 5.8.0-7642-generic       | 13        | 0.4%    |
| 5.8.0-59-generic         | 13        | 0.4%    |
| 5.8.0-45-generic         | 13        | 0.4%    |
| 5.8.0-33-generic         | 13        | 0.4%    |
| 5.4.0-7642-generic       | 13        | 0.4%    |
| 5.3.0-51-generic         | 13        | 0.4%    |
| 5.8.0-41-generic         | 12        | 0.37%   |
| 5.4.0-90-generic         | 12        | 0.37%   |
| 5.4.0-104-generic        | 12        | 0.37%   |
| 5.3.0-40-generic         | 12        | 0.37%   |
| 5.3.0-26-generic         | 12        | 0.37%   |
| 5.13.0-35-generic        | 12        | 0.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 668       | 22.16%  |
| 5.8.0   | 276       | 9.16%   |
| 4.15.0  | 235       | 7.8%    |
| 5.11.0  | 227       | 7.53%   |
| 5.13.0  | 162       | 5.37%   |
| 5.3.0   | 141       | 4.68%   |
| 5.0.0   | 106       | 3.52%   |
| 5.16.7  | 76        | 2.52%   |
| 4.18.0  | 72        | 2.39%   |
| 5.10.0  | 59        | 1.96%   |
| 5.10.14 | 56        | 1.86%   |
| 4.19.0  | 36        | 1.19%   |
| 5.15.0  | 30        | 1%      |
| 4.4.0   | 18        | 0.6%    |
| 5.6.0   | 16        | 0.53%   |
| 5.16.11 | 16        | 0.53%   |
| 5.9.16  | 14        | 0.46%   |
| 5.3.18  | 11        | 0.36%   |
| 5.17.1  | 11        | 0.36%   |
| 5.14.0  | 11        | 0.36%   |
| 5.9.8   | 9         | 0.3%    |
| 5.9.0   | 9         | 0.3%    |
| 5.8.16  | 9         | 0.3%    |
| 5.15.5  | 9         | 0.3%    |
| 5.14.14 | 9         | 0.3%    |
| 5.4.8   | 8         | 0.27%   |
| 5.16.19 | 8         | 0.27%   |
| 5.15.12 | 8         | 0.27%   |
| 5.11.12 | 8         | 0.27%   |
| 5.9.1   | 7         | 0.23%   |
| 5.7.0   | 7         | 0.23%   |
| 5.16.14 | 7         | 0.23%   |
| 5.16.0  | 7         | 0.23%   |
| 5.6.15  | 6         | 0.2%    |
| 5.5.5   | 6         | 0.2%    |
| 5.17.5  | 6         | 0.2%    |
| 5.15.11 | 6         | 0.2%    |
| 5.13.13 | 6         | 0.2%    |
| 5.13.12 | 6         | 0.2%    |
| 5.12.13 | 6         | 0.2%    |
| 5.11.14 | 6         | 0.2%    |
| 5.10.19 | 6         | 0.2%    |
| 4.9.60  | 6         | 0.2%    |
| 4.9.20  | 6         | 0.2%    |
| 4.9.0   | 6         | 0.2%    |
| 4.18.16 | 6         | 0.2%    |
| 5.9.10  | 5         | 0.17%   |
| 5.8.12  | 5         | 0.17%   |
| 5.8.10  | 5         | 0.17%   |
| 5.4.13  | 5         | 0.17%   |
| 5.17.0  | 5         | 0.17%   |
| 5.15.8  | 5         | 0.17%   |
| 5.15.15 | 5         | 0.17%   |
| 5.15.10 | 5         | 0.17%   |
| 5.13.19 | 5         | 0.17%   |
| 5.12.4  | 5         | 0.17%   |
| 4.10.0  | 5         | 0.17%   |
| 5.9.11  | 4         | 0.13%   |
| 5.8.6   | 4         | 0.13%   |
| 5.8.11  | 4         | 0.13%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 730       | 24.5%   |
| 5.8     | 327       | 10.98%  |
| 5.11    | 273       | 9.16%   |
| 4.15    | 236       | 7.92%   |
| 5.13    | 202       | 6.78%   |
| 5.10    | 178       | 5.98%   |
| 5.3     | 173       | 5.81%   |
| 5.16    | 137       | 4.6%    |
| 5.0     | 110       | 3.69%   |
| 5.15    | 101       | 3.39%   |
| 4.18    | 86        | 2.89%   |
| 5.9     | 56        | 1.88%   |
| 5.6     | 51        | 1.71%   |
| 4.19    | 49        | 1.64%   |
| 5.14    | 47        | 1.58%   |
| 5.17    | 41        | 1.38%   |
| 5.12    | 36        | 1.21%   |
| 5.7     | 32        | 1.07%   |
| 5.5     | 28        | 0.94%   |
| 4.9     | 24        | 0.81%   |
| 4.4     | 20        | 0.67%   |
| 5.2     | 9         | 0.3%    |
| 4.16    | 5         | 0.17%   |
| 4.10    | 5         | 0.17%   |
| 4.20    | 4         | 0.13%   |
| 4.14    | 4         | 0.13%   |
| 4.12    | 4         | 0.13%   |
| 5.18    | 2         | 0.07%   |
| 4.1     | 2         | 0.07%   |
| 3.16    | 2         | 0.07%   |
| 5.1     | 1         | 0.03%   |
| 4.7     | 1         | 0.03%   |
| 4.17    | 1         | 0.03%   |
| 3.10    | 1         | 0.03%   |
| Unknown | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 2564      | 95.21%  |
| i686    | 91        | 3.38%   |
| aarch64 | 30        | 1.11%   |
| armv7l  | 6         | 0.22%   |
| armv8l  | 1         | 0.04%   |
| armv6l  | 1         | 0.04%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 1241      | 44.42%  |
| Unknown          | 497       | 17.79%  |
| KDE5             | 336       | 12.03%  |
| XFCE             | 204       | 7.3%    |
| X-Cinnamon       | 175       | 6.26%   |
| KDE              | 92        | 3.29%   |
| MATE             | 57        | 2.04%   |
| Cinnamon         | 30        | 1.07%   |
| Unity            | 21        | 0.75%   |
| LXDE             | 20        | 0.72%   |
| LXQt             | 19        | 0.68%   |
| Budgie           | 19        | 0.68%   |
| Pantheon         | 15        | 0.54%   |
| KDE4             | 15        | 0.54%   |
| i3               | 12        | 0.43%   |
| GNOME Flashback  | 8         | 0.29%   |
| Deepin           | 6         | 0.21%   |
| sway             | 4         | 0.14%   |
| Openbox          | 3         | 0.11%   |
| Enlightenment    | 3         | 0.11%   |
| awesome          | 3         | 0.11%   |
| ICEWM            | 2         | 0.07%   |
| GNOME Classic    | 2         | 0.07%   |
| xmonad           | 1         | 0.04%   |
| trinity          | 1         | 0.04%   |
| qtile            | 1         | 0.04%   |
| lightdm-xsession | 1         | 0.04%   |
| jwm              | 1         | 0.04%   |
| fluxbox          | 1         | 0.04%   |
| dwm              | 1         | 0.04%   |
| dusk             | 1         | 0.04%   |
| Core             | 1         | 0.04%   |
| bspwm            | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 2169      | 78.82%  |
| Wayland | 280       | 10.17%  |
| Unknown | 244       | 8.87%   |
| Tty     | 59        | 2.14%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1653      | 59.4%   |
| GDM     | 345       | 12.4%   |
| SDDM    | 307       | 11.03%  |
| LightDM | 193       | 6.93%   |
| GDM3    | 161       | 5.79%   |
| TDM     | 93        | 3.34%   |
| KDM     | 14        | 0.5%    |
| XDM     | 6         | 0.22%   |
| Ly      | 4         | 0.14%   |
| SLiM    | 3         | 0.11%   |
| GREETD  | 2         | 0.07%   |
| NODM    | 1         | 0.04%   |
| MDM     | 1         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 1207      | 43.64%  |
| nl_NL       | 812       | 29.36%  |
| Unknown     | 421       | 15.22%  |
| en_GB       | 106       | 3.83%   |
| C           | 46        | 1.66%   |
| de_DE       | 25        | 0.9%    |
| pl_PL       | 22        | 0.8%    |
| ru_RU       | 16        | 0.58%   |
| POSIX       | 9         | 0.33%   |
| en_IE       | 9         | 0.33%   |
| en_NL       | 8         | 0.29%   |
| fr_FR       | 6         | 0.22%   |
| fr_BE       | 5         | 0.18%   |
| en_IN       | 5         | 0.18%   |
| en_DK       | 5         | 0.18%   |
| en_CA       | 5         | 0.18%   |
| nl_BE       | 4         | 0.14%   |
| es_ES       | 4         | 0.14%   |
| de_AT       | 4         | 0.14%   |
| sv_SE       | 3         | 0.11%   |
| ru_UA       | 3         | 0.11%   |
| it_IT       | 3         | 0.11%   |
| es_MX       | 3         | 0.11%   |
| C.UTF8      | 3         | 0.11%   |
| sk_SK       | 2         | 0.07%   |
| pt_PT       | 2         | 0.07%   |
| pt_BR       | 2         | 0.07%   |
| hu_HU       | 2         | 0.07%   |
| en_ZA       | 2         | 0.07%   |
| en_US.utf-8 | 2         | 0.07%   |
| en_SG       | 2         | 0.07%   |
| cs_CZ       | 2         | 0.07%   |
| ar_KW       | 2         | 0.07%   |
| zh_CN       | 1         | 0.04%   |
| uk_UA       | 1         | 0.04%   |
| tr_TR       | 1         | 0.04%   |
| nl_AW       | 1         | 0.04%   |
| nb_NO       | 1         | 0.04%   |
| fi_FI       | 1         | 0.04%   |
| es_CR       | 1         | 0.04%   |
| eo          | 1         | 0.04%   |
| en_PH       | 1         | 0.04%   |
| en_NZ       | 1         | 0.04%   |
| en_DE       | 1         | 0.04%   |
| en_AU       | 1         | 0.04%   |
| en_001      | 1         | 0.04%   |
| de_CH       | 1         | 0.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 1407      | 51.24%  |
| EFI  | 1339      | 48.76%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 2182      | 79.43%  |
| Overlay | 178       | 6.48%   |
| Btrfs   | 166       | 6.04%   |
| Unknown | 125       | 4.55%   |
| Xfs     | 40        | 1.46%   |
| Zfs     | 28        | 1.02%   |
| Ext2    | 9         | 0.33%   |
| F2fs    | 8         | 0.29%   |
| Ext3    | 4         | 0.15%   |
| Tmpfs   | 3         | 0.11%   |
| Aufs    | 3         | 0.11%   |
| Jfs     | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1756      | 64.49%  |
| GPT     | 754       | 27.69%  |
| MBR     | 213       | 7.82%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2339      | 85.46%  |
| Yes       | 398       | 14.54%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1956      | 71.57%  |
| Yes       | 777       | 28.43%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| Hewlett-Packard                   | 434       | 16.15%  |
| ASUSTek Computer                  | 402       | 14.96%  |
| Dell                              | 388       | 14.43%  |
| Lenovo                            | 290       | 10.79%  |
| Acer                              | 176       | 6.55%   |
| Gigabyte Technology               | 158       | 5.88%   |
| MSI                               | 155       | 5.77%   |
| ASRock                            | 119       | 4.43%   |
| Apple                             | 67        | 2.49%   |
| Intel                             | 57        | 2.12%   |
| Toshiba                           | 47        | 1.75%   |
| Medion                            | 44        | 1.64%   |
| Notebook                          | 42        | 1.56%   |
| Raspberry Pi Foundation           | 33        | 1.23%   |
| Packard Bell                      | 22        | 0.82%   |
| Samsung Electronics               | 20        | 0.74%   |
| Unknown                           | 18        | 0.67%   |
| Fujitsu                           | 15        | 0.56%   |
| Google                            | 13        | 0.48%   |
| Microsoft                         | 12        | 0.45%   |
| Fujitsu Siemens                   | 12        | 0.45%   |
| Sony                              | 10        | 0.37%   |
| Foxconn                           | 10        | 0.37%   |
| Supermicro                        | 7         | 0.26%   |
| Pegatron                          | 7         | 0.26%   |
| HUAWEI                            | 7         | 0.26%   |
| Biostar                           | 7         | 0.26%   |
| Timi                              | 6         | 0.22%   |
| TUXEDO                            | 5         | 0.19%   |
| Alienware                         | 5         | 0.19%   |
| Shuttle                           | 4         | 0.15%   |
| PC Specialist                     | 4         | 0.15%   |
| AMI                               | 4         | 0.15%   |
| ZOTAC                             | 3         | 0.11%   |
| TrekStor                          | 3         | 0.11%   |
| System76                          | 3         | 0.11%   |
| Insyde                            | 3         | 0.11%   |
| Chuwi                             | 3         | 0.11%   |
| AMD                               | 3         | 0.11%   |
| Valve                             | 2         | 0.07%   |
| TYAN Computer                     | 2         | 0.07%   |
| TongFang                          | 2         | 0.07%   |
| SLIMBOOK                          | 2         | 0.07%   |
| Intel Client Systems              | 2         | 0.07%   |
| HPE                               | 2         | 0.07%   |
| Hampoo                            | 2         | 0.07%   |
| Getac                             | 2         | 0.07%   |
| Clevo                             | 2         | 0.07%   |
| BESSTAR Tech                      | 2         | 0.07%   |
| Wortmann AG                       | 1         | 0.04%   |
| Wistron                           | 1         | 0.04%   |
| Toxic                             | 1         | 0.04%   |
| Teclast                           | 1         | 0.04%   |
| sunxi                             | 1         | 0.04%   |
| SIMPC                             | 1         | 0.04%   |
| Shenzhen PLOYER electronics       | 1         | 0.04%   |
| Sapphire                          | 1         | 0.04%   |
| Rockwell Automation/Allen-Bradley | 1         | 0.04%   |
| RKM                               | 1         | 0.04%   |
| Razer                             | 1         | 0.04%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 26        | 0.97%   |
| Dell Latitude 3120                  | 24        | 0.89%   |
| ASUS All Series                     | 22        | 0.82%   |
| RPi Raspberry Pi                    | 12        | 0.45%   |
| Dell XPS 15 7590                    | 10        | 0.37%   |
| Dell Latitude 3190 2-in-1           | 10        | 0.37%   |
| RPi Raspberry Pi 4 Model B Rev 1.4  | 9         | 0.33%   |
| HP ZBook Studio G5                  | 8         | 0.3%    |
| Dell XPS 15 9560                    | 8         | 0.3%    |
| ASRock B450M Pro4                   | 8         | 0.3%    |
| MSI MS-7C02                         | 7         | 0.26%   |
| Dell OptiPlex 3020                  | 7         | 0.26%   |
| Dell Latitude E6410                 | 7         | 0.26%   |
| Dell Latitude 3310                  | 7         | 0.26%   |
| MSI MS-7817                         | 6         | 0.22%   |
| HP Pavilion g6                      | 6         | 0.22%   |
| HP Pavilion dv6                     | 6         | 0.22%   |
| HP Notebook                         | 6         | 0.22%   |
| Dell OptiPlex 7010                  | 6         | 0.22%   |
| Dell Latitude D630                  | 6         | 0.22%   |
| ASUS M4A78LT-M                      | 6         | 0.22%   |
| MSI MS-7C37                         | 5         | 0.19%   |
| MSI MS-7B86                         | 5         | 0.19%   |
| MSI MS-7816                         | 5         | 0.19%   |
| MSI MS-7721                         | 5         | 0.19%   |
| Intel NUC8i3BEH                     | 5         | 0.19%   |
| HP Pavilion Laptop 15-cw1xxx        | 5         | 0.19%   |
| HP Pavilion g7                      | 5         | 0.19%   |
| HP Pavilion dv7                     | 5         | 0.19%   |
| HP EliteBook 8460p                  | 5         | 0.19%   |
| HP Compaq dc7900 Small Form Factor  | 5         | 0.19%   |
| Dell XPS 15 9570                    | 5         | 0.19%   |
| Dell XPS 15 9550                    | 5         | 0.19%   |
| Dell XPS 15 9500                    | 5         | 0.19%   |
| Dell XPS 13 9360                    | 5         | 0.19%   |
| Dell XPS 13 9310                    | 5         | 0.19%   |
| Dell OptiPlex 9020                  | 5         | 0.19%   |
| Dell Latitude 3189                  | 5         | 0.19%   |
| ASUS Z170 PRO GAMING                | 5         | 0.19%   |
| ASUS PRIME A320M-K                  | 5         | 0.19%   |
| ASUS K52F                           | 5         | 0.19%   |
| RPi Raspberry Pi 4 Model B Rev 1.2  | 4         | 0.15%   |
| MSI MS-7B89                         | 4         | 0.15%   |
| MSI MS-7B85                         | 4         | 0.15%   |
| Lenovo Yoga C740-14IML 81TC         | 4         | 0.15%   |
| Intel NUC7i3BNH                     | 4         | 0.15%   |
| HP ProBook 6570b                    | 4         | 0.15%   |
| HP ProBook 650 G1                   | 4         | 0.15%   |
| HP ProBook 450 G3                   | 4         | 0.15%   |
| HP Pavilion Laptop 15-eh0xxx        | 4         | 0.15%   |
| HP Pavilion Gaming Laptop 15-cx0xxx | 4         | 0.15%   |
| HP EliteBook 8570w                  | 4         | 0.15%   |
| HP EliteBook 850 G3                 | 4         | 0.15%   |
| HP EliteBook 8470p                  | 4         | 0.15%   |
| HP EliteBook 8440p                  | 4         | 0.15%   |
| HP EliteBook 840 G1                 | 4         | 0.15%   |
| HP Compaq dc7800 Small Form Factor  | 4         | 0.15%   |
| HP Compaq 6000 Pro SFF PC           | 4         | 0.15%   |
| Gigabyte X570 AORUS PRO             | 4         | 0.15%   |
| Gigabyte X570 AORUS ELITE           | 4         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell Latitude           | 159       | 5.92%   |
| Lenovo ThinkPad         | 158       | 5.88%   |
| Acer Aspire             | 122       | 4.54%   |
| HP Compaq               | 81        | 3.01%   |
| HP EliteBook            | 74        | 2.75%   |
| Dell XPS                | 71        | 2.64%   |
| HP Pavilion             | 68        | 2.53%   |
| HP ProBook              | 51        | 1.9%    |
| Lenovo IdeaPad          | 49        | 1.82%   |
| Dell OptiPlex           | 49        | 1.82%   |
| ASUS PRIME              | 45        | 1.67%   |
| Toshiba Satellite       | 42        | 1.56%   |
| Dell Inspiron           | 37        | 1.38%   |
| RPi Raspberry           | 33        | 1.23%   |
| ASUS ROG                | 32        | 1.19%   |
| Unknown                 | 26        | 0.97%   |
| Dell Precision          | 25        | 0.93%   |
| HP ZBook                | 24        | 0.89%   |
| HP ENVY                 | 22        | 0.82%   |
| ASUS All                | 22        | 0.82%   |
| Lenovo Yoga             | 16        | 0.6%    |
| Lenovo Legion           | 16        | 0.6%    |
| Packard Bell EasyNote   | 15        | 0.56%   |
| Gigabyte X570           | 15        | 0.56%   |
| HP Laptop               | 13        | 0.48%   |
| Microsoft Surface       | 12        | 0.45%   |
| ASUS TUF                | 12        | 0.45%   |
| Lenovo ThinkCentre      | 11        | 0.41%   |
| Acer Swift              | 11        | 0.41%   |
| Dell Studio             | 10        | 0.37%   |
| ASUS ZenBook            | 10        | 0.37%   |
| ASUS VivoBook           | 10        | 0.37%   |
| ASUS P8H61-M            | 10        | 0.37%   |
| ASRock B450M            | 10        | 0.37%   |
| Acer TravelMate         | 10        | 0.37%   |
| Lenovo ThinkBook        | 9         | 0.33%   |
| HP Spectre              | 9         | 0.33%   |
| Fujitsu LIFEBOOK        | 9         | 0.33%   |
| Dell System             | 9         | 0.33%   |
| Acer Veriton            | 9         | 0.33%   |
| HP ProDesk              | 8         | 0.3%    |
| Gigabyte B450M          | 8         | 0.3%    |
| ASUS P6T                | 8         | 0.3%    |
| ASRock 970              | 8         | 0.3%    |
| MSI MS-7C02             | 7         | 0.26%   |
| Dell Vostro             | 7         | 0.26%   |
| ASRock X570             | 7         | 0.26%   |
| ASRock B450             | 7         | 0.26%   |
| MSI MS-7817             | 6         | 0.22%   |
| Medion Akoya            | 6         | 0.22%   |
| HP ProLiant             | 6         | 0.22%   |
| HP Notebook             | 6         | 0.22%   |
| HP EliteDesk            | 6         | 0.22%   |
| Fujitsu Siemens ESPRIMO | 6         | 0.22%   |
| Dell PowerEdge          | 6         | 0.22%   |
| ASUS M5A78L-M           | 6         | 0.22%   |
| ASUS M4A78LT-M          | 6         | 0.22%   |
| ASRock Z87              | 6         | 0.22%   |
| Apple MacBookPro8       | 6         | 0.22%   |
| MSI MS-7C37             | 5         | 0.19%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 289       | 10.75%  |
| 2018    | 246       | 9.15%   |
| 2012    | 212       | 7.89%   |
| 2020    | 209       | 7.78%   |
| 2011    | 198       | 7.37%   |
| 2017    | 183       | 6.81%   |
| 2013    | 179       | 6.66%   |
| 2014    | 160       | 5.95%   |
| 2010    | 152       | 5.65%   |
| 2015    | 151       | 5.62%   |
| 2016    | 136       | 5.06%   |
| 2021    | 127       | 4.72%   |
| 2008    | 126       | 4.69%   |
| 2009    | 125       | 4.65%   |
| 2007    | 97        | 3.61%   |
| 2006    | 39        | 1.45%   |
| Unknown | 35        | 1.3%    |
| 2005    | 11        | 0.41%   |
| 2004    | 6         | 0.22%   |
| 2022    | 4         | 0.15%   |
| 2003    | 2         | 0.07%   |
| 2002    | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1404      | 52.23%  |
| Desktop        | 1006      | 37.43%  |
| Convertible    | 101       | 3.76%   |
| Mini pc        | 58        | 2.16%   |
| System on chip | 36        | 1.34%   |
| All in one     | 33        | 1.23%   |
| Tablet         | 29        | 1.08%   |
| Server         | 20        | 0.74%   |
| Phone          | 1         | 0.04%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 2485      | 91.9%   |
| Enabled  | 219       | 8.1%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2671      | 99.37%  |
| Yes  | 17        | 0.63%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 603       | 22.06%  |
| 16.01-24.0  | 561       | 20.53%  |
| 3.01-4.0    | 547       | 20.01%  |
| 8.01-16.0   | 452       | 16.54%  |
| 32.01-64.0  | 260       | 9.51%   |
| 1.01-2.0    | 113       | 4.13%   |
| 64.01-256.0 | 64        | 2.34%   |
| 2.01-3.0    | 60        | 2.2%    |
| 24.01-32.0  | 41        | 1.5%    |
| 0.51-1.0    | 31        | 1.13%   |
| 0.01-0.5    | 1         | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 1134      | 38.32%  |
| 2.01-3.0    | 701       | 23.69%  |
| 4.01-8.0    | 374       | 12.64%  |
| 3.01-4.0    | 347       | 11.73%  |
| 0.51-1.0    | 212       | 7.16%   |
| 8.01-16.0   | 123       | 4.16%   |
| 0.01-0.5    | 33        | 1.12%   |
| 16.01-24.0  | 23        | 0.78%   |
| 32.01-64.0  | 9         | 0.3%    |
| 24.01-32.0  | 2         | 0.07%   |
| 64.01-256.0 | 1         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1592      | 57.64%  |
| 2       | 701       | 25.38%  |
| 3       | 221       | 8%      |
| 4       | 109       | 3.95%   |
| 5       | 52        | 1.88%   |
| 0       | 36        | 1.3%    |
| 6       | 25        | 0.91%   |
| 7       | 13        | 0.47%   |
| 8       | 5         | 0.18%   |
| Unknown | 4         | 0.14%   |
| 28      | 1         | 0.04%   |
| 27      | 1         | 0.04%   |
| 10      | 1         | 0.04%   |
| 9       | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1598      | 58.95%  |
| Yes       | 1113      | 41.05%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2315      | 85.9%   |
| No        | 380       | 14.1%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1934      | 71.6%   |
| No        | 767       | 28.4%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1512      | 55.36%  |
| No        | 1219      | 44.64%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Netherlands | 2688      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Amsterdam              | 495       | 17.5%   |
| The Hague              | 141       | 4.99%   |
| Rotterdam              | 94        | 3.32%   |
| Utrecht                | 78        | 2.76%   |
| Haarlem                | 60        | 2.12%   |
| Delft                  | 53        | 1.87%   |
| Groningen              | 48        | 1.7%    |
| Schagen                | 45        | 1.59%   |
| Eindhoven              | 43        | 1.52%   |
| Almere Stad            | 38        | 1.34%   |
| Tilburg                | 35        | 1.24%   |
| Amersfoort             | 34        | 1.2%    |
| Naaldwijk              | 31        | 1.1%    |
| Leiden                 | 31        | 1.1%    |
| Nijmegen               | 28        | 0.99%   |
| Zoetermeer             | 27        | 0.95%   |
| Breda                  | 26        | 0.92%   |
| Enschede               | 23        | 0.81%   |
| Arnhem                 | 23        | 0.81%   |
| Apeldoorn              | 20        | 0.71%   |
| Almelo                 | 20        | 0.71%   |
| Zwolle                 | 19        | 0.67%   |
| Hilversum              | 19        | 0.67%   |
| Lelystad               | 18        | 0.64%   |
| Capelle aan den IJssel | 18        | 0.64%   |
| 's-Hertogenbosch       | 18        | 0.64%   |
| Maastricht             | 17        | 0.6%    |
| Zeist                  | 16        | 0.57%   |
| Dordrecht              | 16        | 0.57%   |
| Assen                  | 15        | 0.53%   |
| Alkmaar                | 14        | 0.5%    |
| Schiedam               | 13        | 0.46%   |
| Helmond                | 12        | 0.42%   |
| Heerlen                | 12        | 0.42%   |
| Diemen                 | 12        | 0.42%   |
| Amstelveen             | 12        | 0.42%   |
| Roosendaal             | 11        | 0.39%   |
| Meppel                 | 11        | 0.39%   |
| Heerenveen             | 11        | 0.39%   |
| Gouda                  | 11        | 0.39%   |
| Venlo                  | 10        | 0.35%   |
| Spijkenisse            | 10        | 0.35%   |
| Purmerend              | 10        | 0.35%   |
| Oss                    | 10        | 0.35%   |
| Goes                   | 10        | 0.35%   |
| Emmen                  | 10        | 0.35%   |
| Ede                    | 10        | 0.35%   |
| Deventer               | 10        | 0.35%   |
| Alphen aan den Rijn    | 10        | 0.35%   |
| Waalwijk               | 9         | 0.32%   |
| Leeuwarden             | 9         | 0.32%   |
| Hoorn                  | 9         | 0.32%   |
| Zaandam                | 8         | 0.28%   |
| Wijchen                | 8         | 0.28%   |
| Weert                  | 8         | 0.28%   |
| Vlaardingen            | 8         | 0.28%   |
| Steenbergen            | 8         | 0.28%   |
| Rijswijk               | 8         | 0.28%   |
| Oosterhout             | 8         | 0.28%   |
| Ochten                 | 8         | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 884       | 1420   | 22.78%  |
| WDC                       | 558       | 842    | 14.38%  |
| Seagate                   | 518       | 809    | 13.35%  |
| Toshiba                   | 244       | 323    | 6.29%   |
| Kingston                  | 236       | 306    | 6.08%   |
| Sandisk                   | 171       | 233    | 4.41%   |
| Crucial                   | 166       | 212    | 4.28%   |
| Unknown                   | 158       | 195    | 4.07%   |
| Hitachi                   | 133       | 162    | 3.43%   |
| Intel                     | 118       | 151    | 3.04%   |
| SK Hynix                  | 101       | 117    | 2.6%    |
| HGST                      | 74        | 87     | 1.91%   |
| A-DATA Technology         | 48        | 53     | 1.24%   |
| Micron Technology         | 45        | 52     | 1.16%   |
| LITEON                    | 30        | 38     | 0.77%   |
| Apple                     | 29        | 38     | 0.75%   |
| OCZ                       | 26        | 32     | 0.67%   |
| MAXTOR                    | 24        | 30     | 0.62%   |
| LITEONIT                  | 20        | 22     | 0.52%   |
| KIOXIA                    | 20        | 29     | 0.52%   |
| Fujitsu                   | 20        | 22     | 0.52%   |
| Phison                    | 19        | 25     | 0.49%   |
| Transcend                 | 17        | 22     | 0.44%   |
| Corsair                   | 17        | 22     | 0.44%   |
| China                     | 13        | 22     | 0.34%   |
| ASMT                      | 12        | 14     | 0.31%   |
| PNY                       | 11        | 12     | 0.28%   |
| Gigabyte Technology       | 10        | 12     | 0.26%   |
| Patriot                   | 9         | 12     | 0.23%   |
| KingFast                  | 9         | 12     | 0.23%   |
| Intenso                   | 9         | 9      | 0.23%   |
| XPG                       | 8         | 10     | 0.21%   |
| GOODRAM                   | 8         | 9      | 0.21%   |
| JMicron                   | 7         | 13     | 0.18%   |
| Micron/Crucial Technology | 6         | 8      | 0.15%   |
| SPCC                      | 5         | 6      | 0.13%   |
| Silicon Motion            | 5         | 6      | 0.13%   |
| Mushkin                   | 5         | 7      | 0.13%   |
| SSSTC                     | 4         | 4      | 0.1%    |
| ACASIS                    | 4         | 4      | 0.1%    |
| PLEXTOR                   | 3         | 4      | 0.08%   |
| Netac                     | 3         | 3      | 0.08%   |
| Apacer                    | 3         | 3      | 0.08%   |
| Unknown                   | 3         | 4      | 0.08%   |
| Vaseky                    | 2         | 2      | 0.05%   |
| UMIS                      | 2         | 2      | 0.05%   |
| SABRENT                   | 2         | 2      | 0.05%   |
| Realtek                   | 2         | 2      | 0.05%   |
| Philips                   | 2         | 2      | 0.05%   |
| MAIWO                     | 2         | 2      | 0.05%   |
| Lite-On                   | 2         | 2      | 0.05%   |
| Linux                     | 2         | 2      | 0.05%   |
| LaCie                     | 2         | 2      | 0.05%   |
| KingSpec                  | 2         | 3      | 0.05%   |
| Kingchuxing               | 2         | 2      | 0.05%   |
| IBM/Hitachi               | 2         | 2      | 0.05%   |
| Hewlett-Packard           | 2         | 2      | 0.05%   |
| Freecom                   | 2         | 2      | 0.05%   |
| FORESEE                   | 2         | 2      | 0.05%   |
| asmedia                   | 2         | 4      | 0.05%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB           | 77        | 1.77%   |
| Samsung SSD 860 EVO 500GB           | 53        | 1.22%   |
| Samsung SSD 850 EVO 500GB           | 48        | 1.1%    |
| Samsung NVMe SSD Drive 500GB        | 44        | 1.01%   |
| Samsung NVMe SSD Drive 1TB          | 37        | 0.85%   |
| Kingston SA400S37240G 240GB SSD     | 35        | 0.8%    |
| Samsung SSD 840 EVO 250GB           | 30        | 0.69%   |
| Kingston SA400S37120G 120GB SSD     | 30        | 0.69%   |
| Unknown MMC Card  32GB              | 28        | 0.64%   |
| Samsung SSD 840 EVO 120GB           | 28        | 0.64%   |
| Samsung NVMe SSD Drive 256GB        | 26        | 0.6%    |
| Samsung SSD 970 EVO 1TB             | 25        | 0.57%   |
| Samsung SSD 860 EVO 1TB             | 25        | 0.57%   |
| Seagate ST2000DM008-2FR102 2TB      | 24        | 0.55%   |
| Seagate Expansion 4TB               | 24        | 0.55%   |
| Samsung NVMe SSD Drive 512GB        | 23        | 0.53%   |
| Kingston SV300S37A120G 120GB SSD    | 23        | 0.53%   |
| Crucial CT500MX500SSD1 500GB        | 23        | 0.53%   |
| Unknown MMC Card  64GB              | 22        | 0.5%    |
| Seagate ST1000LM035-1RK172 1TB      | 22        | 0.5%    |
| Seagate ST9500325AS 500GB           | 21        | 0.48%   |
| Seagate ST500DM002-1BD142 500GB     | 19        | 0.44%   |
| Samsung NVMe SSD Drive 1024GB       | 19        | 0.44%   |
| HGST HTS721010A9E630 1TB            | 19        | 0.44%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD | 18        | 0.41%   |
| Toshiba MQ01ABF050 500GB            | 17        | 0.39%   |
| Toshiba DT01ACA100 1TB              | 16        | 0.37%   |
| Sandisk NVMe SSD Drive 512GB        | 16        | 0.37%   |
| Crucial CT1000MX500SSD1 1TB         | 16        | 0.37%   |
| Toshiba NVMe SSD Drive 512GB        | 15        | 0.34%   |
| Toshiba MQ01ABD100 1TB              | 15        | 0.34%   |
| Seagate ST1000DM010-2EP102 1TB      | 15        | 0.34%   |
| Samsung SSD 860 QVO 1TB             | 15        | 0.34%   |
| Samsung HD204UI 2TB                 | 15        | 0.34%   |
| Samsung HD103SJ 1TB                 | 15        | 0.34%   |
| Kingston SV300S37A240G 240GB SSD    | 15        | 0.34%   |
| Crucial CT240BX500SSD1 240GB        | 15        | 0.34%   |
| Seagate ST2000DM006-2DM164 2TB      | 14        | 0.32%   |
| Samsung SSD 970 EVO Plus 500GB      | 14        | 0.32%   |
| Samsung SSD 970 EVO Plus 1TB        | 14        | 0.32%   |
| Samsung SSD 860 EVO 250GB           | 14        | 0.32%   |
| Samsung SSD 850 EVO 120GB           | 14        | 0.32%   |
| Samsung NVMe SSD Drive 250GB        | 14        | 0.32%   |
| Kingston NVMe SSD Drive 1TB         | 14        | 0.32%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 13        | 0.3%    |
| WDC WD20EARX-00PASB0 2TB            | 13        | 0.3%    |
| Seagate ST1000DM003-1CH162 1TB      | 13        | 0.3%    |
| Samsung SSD 870 QVO 1TB             | 13        | 0.3%    |
| HGST HTS725050A7E630 500GB          | 13        | 0.3%    |
| WDC WD20EZRX-00D8PB0 2TB            | 12        | 0.28%   |
| Seagate ST31000524AS 1TB            | 12        | 0.28%   |
| Intel NVMe SSD Drive 512GB          | 12        | 0.28%   |
| Intel NVMe SSD Drive 1024GB         | 12        | 0.28%   |
| Crucial CT256MX100SSD1 256GB        | 12        | 0.28%   |
| Toshiba DT01ACA050 500GB            | 11        | 0.25%   |
| SK Hynix NVMe SSD Drive 512GB       | 11        | 0.25%   |
| Seagate ST31000528AS 1TB            | 11        | 0.25%   |
| Seagate ST2000DM001-1CH164 2TB      | 11        | 0.25%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 11        | 0.25%   |
| Seagate Expansion Desk 10TB         | 11        | 0.25%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 513       | 798    | 33.23%  |
| WDC                 | 455       | 700    | 29.47%  |
| Toshiba             | 165       | 226    | 10.69%  |
| Hitachi             | 133       | 162    | 8.61%   |
| Samsung Electronics | 118       | 177    | 7.64%   |
| HGST                | 74        | 87     | 4.79%   |
| MAXTOR              | 24        | 30     | 1.55%   |
| Fujitsu             | 20        | 22     | 1.3%    |
| ASMT                | 9         | 11     | 0.58%   |
| Unknown             | 7         | 10     | 0.45%   |
| Apple               | 6         | 7      | 0.39%   |
| JMicron             | 3         | 5      | 0.19%   |
| Intenso             | 3         | 3      | 0.19%   |
| SABRENT             | 2         | 2      | 0.13%   |
| IBM/Hitachi         | 2         | 2      | 0.13%   |
| ASMedia             | 2         | 4      | 0.13%   |
| NAS                 | 1         | 10     | 0.06%   |
| Maxtor 6            | 1         | 2      | 0.06%   |
| Magnetic Data       | 1         | 1      | 0.06%   |
| LIO-ORG             | 1         | 4      | 0.06%   |
| LaCie               | 1         | 1      | 0.06%   |
| KESU                | 1         | 1      | 0.06%   |
| Hewlett-Packard     | 1         | 1      | 0.06%   |
| ExcelStor           | 1         | 1      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 500       | 741    | 35.16%  |
| Kingston            | 182       | 223    | 12.8%   |
| Crucial             | 160       | 206    | 11.25%  |
| SanDisk             | 118       | 147    | 8.3%    |
| WDC                 | 59        | 77     | 4.15%   |
| Intel               | 57        | 72     | 4.01%   |
| A-DATA Technology   | 40        | 45     | 2.81%   |
| SK Hynix            | 30        | 33     | 2.11%   |
| Micron Technology   | 29        | 34     | 2.04%   |
| OCZ                 | 26        | 32     | 1.83%   |
| LITEON              | 25        | 33     | 1.76%   |
| Toshiba             | 22        | 24     | 1.55%   |
| LITEONIT            | 20        | 22     | 1.41%   |
| Apple               | 17        | 20     | 1.2%    |
| Transcend           | 14        | 19     | 0.98%   |
| China               | 13        | 22     | 0.91%   |
| Corsair             | 12        | 16     | 0.84%   |
| PNY                 | 11        | 12     | 0.77%   |
| Patriot             | 9         | 12     | 0.63%   |
| GOODRAM             | 8         | 9      | 0.56%   |
| SPCC                | 5         | 6      | 0.35%   |
| Mushkin             | 5         | 7      | 0.35%   |
| Intenso             | 4         | 4      | 0.28%   |
| Gigabyte Technology | 4         | 6      | 0.28%   |
| ACASIS              | 4         | 4      | 0.28%   |
| PLEXTOR             | 3         | 4      | 0.21%   |
| Netac               | 3         | 3      | 0.21%   |
| KingFast            | 3         | 3      | 0.21%   |
| JMicron             | 3         | 3      | 0.21%   |
| ASMT                | 3         | 3      | 0.21%   |
| Apacer              | 3         | 3      | 0.21%   |
| Vaseky              | 2         | 2      | 0.14%   |
| Unknown             | 2         | 2      | 0.14%   |
| KingSpec            | 2         | 3      | 0.14%   |
| FORESEE             | 2         | 2      | 0.14%   |
| TrekStor            | 1         | 1      | 0.07%   |
| TO Exter            | 1         | 1      | 0.07%   |
| Team                | 1         | 2      | 0.07%   |
| StoreJet            | 1         | 1      | 0.07%   |
| Seagate             | 1         | 1      | 0.07%   |
| PHISON              | 1         | 1      | 0.07%   |
| OWC                 | 1         | 1      | 0.07%   |
| OCZ-VERTEX2         | 1         | 2      | 0.07%   |
| Linux               | 1         | 1      | 0.07%   |
| Leven               | 1         | 1      | 0.07%   |
| KingDian            | 1         | 1      | 0.07%   |
| Innodisk            | 1         | 1      | 0.07%   |
| HPE                 | 1         | 1      | 0.07%   |
| HP Phison           | 1         | 1      | 0.07%   |
| Hewlett-Packard     | 1         | 1      | 0.07%   |
| GOLDEN              | 1         | 2      | 0.07%   |
| External            | 1         | 3      | 0.07%   |
| CT480BX5            | 1         | 2      | 0.07%   |
| Biostar             | 1         | 1      | 0.07%   |
| BHT                 | 1         | 1      | 0.07%   |
| Anobit              | 1         | 1      | 0.07%   |
| Unknown             | 1         | 2      | 0.07%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1271      | 2267   | 36.28%  |
| SSD     | 1257      | 1883   | 35.88%  |
| NVMe    | 785       | 1128   | 22.41%  |
| MMC     | 149       | 180    | 4.25%   |
| Unknown | 41        | 51     | 1.17%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2029      | 3938   | 65.03%  |
| NVMe | 784       | 1126   | 25.13%  |
| SAS  | 158       | 265    | 5.06%   |
| MMC  | 149       | 180    | 4.78%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1660      | 2525   | 62.27%  |
| 0.51-1.0   | 622       | 939    | 23.33%  |
| 1.01-2.0   | 210       | 341    | 7.88%   |
| 3.01-4.0   | 79        | 148    | 2.96%   |
| 4.01-10.0  | 47        | 114    | 1.76%   |
| 2.01-3.0   | 46        | 69     | 1.73%   |
| 10.01-20.0 | 2         | 14     | 0.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 809       | 28.5%   |
| 251-500        | 565       | 19.9%   |
| 501-1000       | 367       | 12.93%  |
| 1-20           | 236       | 8.31%   |
| 1001-2000      | 224       | 7.89%   |
| 51-100         | 196       | 6.9%    |
| More than 3000 | 161       | 5.67%   |
| 21-50          | 130       | 4.58%   |
| 2001-3000      | 82        | 2.89%   |
| Unknown        | 69        | 2.43%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1194      | 40.83%  |
| 21-50          | 424       | 14.5%   |
| 101-250        | 338       | 11.56%  |
| 51-100         | 318       | 10.88%  |
| 251-500        | 204       | 6.98%   |
| 501-1000       | 173       | 5.92%   |
| 1001-2000      | 95        | 3.25%   |
| Unknown        | 69        | 2.36%   |
| More than 3000 | 68        | 2.33%   |
| 2001-3000      | 40        | 1.37%   |
| 0              | 1         | 0.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 4         | 4      | 2.44%   |
| SanDisk SD6SF1M128G1022I 128GB SSD    | 4         | 4      | 2.44%   |
| WDC WD10EADS-22M2B0 1TB               | 3         | 3      | 1.83%   |
| Seagate ST9250410AS 250GB             | 3         | 3      | 1.83%   |
| HGST HTS725050A7E630 500GB            | 3         | 3      | 1.83%   |
| HGST HTS721010A9E630 1TB              | 3         | 3      | 1.83%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 2         | 2      | 1.22%   |
| Toshiba MQ01ABF050 500GB              | 2         | 2      | 1.22%   |
| Toshiba MQ01ABD050 500GB              | 2         | 3      | 1.22%   |
| Seagate ST9500325AS 500GB             | 2         | 2      | 1.22%   |
| Seagate ST500LT012-9WS142 500GB       | 2         | 2      | 1.22%   |
| Seagate ST380011A 80GB                | 2         | 2      | 1.22%   |
| Seagate ST3500418AS 500GB             | 2         | 2      | 1.22%   |
| Seagate ST31000524AS 1TB              | 2         | 2      | 1.22%   |
| Samsung Electronics HM500JI 500GB     | 2         | 2      | 1.22%   |
| Intel SSDSC2CW120A3 120GB             | 2         | 2      | 1.22%   |
| Intel SSDSC2BW120A4 120GB             | 2         | 3      | 1.22%   |
| Intel SSDSA2M080G2GC 80GB             | 2         | 3      | 1.22%   |
| Crucial CT525MX300SSD1 528GB          | 2         | 2      | 1.22%   |
| Crucial CT128MX100SSD1 128GB          | 2         | 2      | 1.22%   |
| WDC WD7500BPVT-08HXZT3 752GB          | 1         | 1      | 0.61%   |
| WDC WD6400AACS-00G8B1 640GB           | 1         | 1      | 0.61%   |
| WDC WD60EFRX-68MYMN1 6TB              | 1         | 1      | 0.61%   |
| WDC WD5000BPVT-22HXZT3 500GB          | 1         | 1      | 0.61%   |
| WDC WD5000AVDS-63U7B1 500GB           | 1         | 1      | 0.61%   |
| WDC WD5000AAKX-001CA0 500GB           | 1         | 1      | 0.61%   |
| WDC WD5000AAKS-75V0A0 500GB           | 1         | 1      | 0.61%   |
| WDC WD5000AAKS-60Z1A0 500GB           | 1         | 1      | 0.61%   |
| WDC WD5000AAKS-41YGA1 500GB           | 1         | 1      | 0.61%   |
| WDC WD3200BPVT-80ZEST0 320GB          | 1         | 1      | 0.61%   |
| WDC WD3200BEVT-60ZCT1 320GB           | 1         | 1      | 0.61%   |
| WDC WD30EZRX-00MMMB0 3TB              | 1         | 1      | 0.61%   |
| WDC WD30EFRX-68EUZN0 3TB              | 1         | 2      | 0.61%   |
| WDC WD2500AAKX-00ERMA0 250GB          | 1         | 1      | 0.61%   |
| WDC WD2500AAJS-40VWA1 250GB           | 1         | 1      | 0.61%   |
| WDC WD20PURZ-85AKKY0 2TB              | 1         | 1      | 0.61%   |
| WDC WD20EZRZ-00Z5HB0 2TB              | 1         | 1      | 0.61%   |
| WDC WD20EFRX-68EUZN0 2TB              | 1         | 6      | 0.61%   |
| WDC WD20EARX-00PASB0 2TB              | 1         | 1      | 0.61%   |
| WDC WD1600BEVT-75A23T0 160GB          | 1         | 1      | 0.61%   |
| WDC WD1600AAJS-75M0A0 160GB           | 1         | 2      | 0.61%   |
| WDC WD15EADS-00P8B0 1TB               | 1         | 1      | 0.61%   |
| WDC WD1200JB-00CRA1 120GB             | 1         | 1      | 0.61%   |
| WDC WD10SPZX-24Z10T0 1TB              | 1         | 1      | 0.61%   |
| WDC WD10JPVX-22JC3T0 1TB              | 1         | 1      | 0.61%   |
| WDC WD10EZEX-60M2NA0 1TB              | 1         | 1      | 0.61%   |
| WDC WD10EARS-00Y5B1 1TB               | 1         | 1      | 0.61%   |
| WDC WD1003FZEX-00MK2A0 1TB            | 1         | 1      | 0.61%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 1         | 1      | 0.61%   |
| WDC WD1002FAEX-00Y9A0 1TB             | 1         | 1      | 0.61%   |
| Toshiba MQ01ABD100 1TB                | 1         | 1      | 0.61%   |
| Toshiba MK1252GSX 120GB               | 1         | 1      | 0.61%   |
| Toshiba MK1234GSX 120GB               | 1         | 1      | 0.61%   |
| SK Hynix HFS128G39TND-N210A 128GB SSD | 1         | 1      | 0.61%   |
| SK Hynix HFS064G3AMNB-2200A 64GB SSD  | 1         | 1      | 0.61%   |
| Seagate ST9500420AS 500GB             | 1         | 1      | 0.61%   |
| Seagate ST9250315AS 250GB             | 1         | 1      | 0.61%   |
| Seagate ST9200420ASG 200GB            | 1         | 1      | 0.61%   |
| Seagate ST9160821A 137GB              | 1         | 1      | 0.61%   |
| Seagate ST9100822A 100GB              | 1         | 1      | 0.61%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 36        | 50     | 22.22%  |
| WDC                 | 34        | 42     | 20.99%  |
| Intel               | 11        | 13     | 6.79%   |
| Hitachi             | 10        | 11     | 6.17%   |
| Crucial             | 10        | 12     | 6.17%   |
| Samsung Electronics | 9         | 9      | 5.56%   |
| HGST                | 9         | 10     | 5.56%   |
| SanDisk             | 8         | 8      | 4.94%   |
| Kingston            | 8         | 10     | 4.94%   |
| Toshiba             | 7         | 8      | 4.32%   |
| Micron Technology   | 3         | 3      | 1.85%   |
| Fujitsu             | 3         | 3      | 1.85%   |
| SK Hynix            | 2         | 2      | 1.23%   |
| OCZ                 | 2         | 2      | 1.23%   |
| MAXTOR              | 2         | 2      | 1.23%   |
| A-DATA Technology   | 2         | 2      | 1.23%   |
| Patriot             | 1         | 1      | 0.62%   |
| LITEONIT            | 1         | 1      | 0.62%   |
| LITEON              | 1         | 3      | 0.62%   |
| GOODRAM             | 1         | 1      | 0.62%   |
| Apple               | 1         | 1      | 0.62%   |
| Anobit              | 1         | 1      | 0.62%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 36        | 50     | 33.96%  |
| WDC                 | 32        | 40     | 30.19%  |
| Hitachi             | 10        | 11     | 9.43%   |
| HGST                | 9         | 10     | 8.49%   |
| Toshiba             | 7         | 8      | 6.6%    |
| Samsung Electronics | 6         | 6      | 5.66%   |
| Fujitsu             | 3         | 3      | 2.83%   |
| MAXTOR              | 2         | 2      | 1.89%   |
| Apple               | 1         | 1      | 0.94%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 99        | 131    | 63.87%  |
| SSD  | 54        | 62     | 34.84%  |
| NVMe | 2         | 2      | 1.29%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD2500BEVT-22ZCT0 250GB       | 1         | 1      | 20%     |
| Toshiba MK5065GSXN 500GB          | 1         | 1      | 20%     |
| Seagate ST2000DL001-9VT156 2TB    | 1         | 1      | 20%     |
| Samsung Electronics HD502HJ 500GB | 1         | 1      | 20%     |
| Samsung Electronics HD161HJ 160GB | 1         | 1      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 2      | 40%     |
| WDC                 | 1         | 1      | 20%     |
| Toshiba             | 1         | 1      | 20%     |
| Seagate             | 1         | 1      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1855      | 3804   | 65.04%  |
| Works    | 843       | 1505   | 29.56%  |
| Malfunc  | 149       | 195    | 5.22%   |
| Failed   | 5         | 5      | 0.18%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1819      | 55.27%  |
| AMD                              | 444       | 13.49%  |
| Samsung Electronics              | 365       | 11.09%  |
| Sandisk                          | 102       | 3.1%    |
| SK Hynix                         | 69        | 2.1%    |
| Toshiba America Info Systems     | 65        | 1.98%   |
| Kingston Technology Company      | 57        | 1.73%   |
| ASMedia Technology               | 51        | 1.55%   |
| Nvidia                           | 47        | 1.43%   |
| JMicron Technology               | 44        | 1.34%   |
| Marvell Technology Group         | 41        | 1.25%   |
| Phison Electronics               | 29        | 0.88%   |
| KIOXIA                           | 22        | 0.67%   |
| Micron Technology                | 17        | 0.52%   |
| Silicon Integrated Systems [SiS] | 12        | 0.36%   |
| ADATA Technology                 | 12        | 0.36%   |
| VIA Technologies                 | 11        | 0.33%   |
| Micron/Crucial Technology        | 10        | 0.3%    |
| Silicon Motion                   | 8         | 0.24%   |
| Lite-On Technology               | 7         | 0.21%   |
| Apple                            | 7         | 0.21%   |
| Silicon Image                    | 6         | 0.18%   |
| LSI Logic / Symbios Logic        | 6         | 0.18%   |
| Broadcom / LSI                   | 6         | 0.18%   |
| Seagate Technology               | 5         | 0.15%   |
| Realtek Semiconductor            | 5         | 0.15%   |
| Union Memory (Shenzhen)          | 4         | 0.12%   |
| Solid State Storage Technology   | 3         | 0.09%   |
| Integrated Technology Express    | 3         | 0.09%   |
| Hewlett-Packard                  | 3         | 0.09%   |
| Adaptec                          | 3         | 0.09%   |
| ULi Electronics                  | 2         | 0.06%   |
| Promise Technology               | 2         | 0.06%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.03%   |
| Lenovo                           | 1         | 0.03%   |
| HighPoint Technologies           | 1         | 0.03%   |
| Biwin Storage Technology         | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 283       | 7.31%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 217       | 5.61%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 134       | 3.46%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 130       | 3.36%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 126       | 3.26%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 108       | 2.79%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 88        | 2.27%   |
| AMD 400 Series Chipset SATA Controller                                                  | 78        | 2.02%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 68        | 1.76%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 68        | 1.76%   |
| Samsung NVMe SSD Controller 980                                                         | 62        | 1.6%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 62        | 1.6%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 59        | 1.52%   |
| Intel SATA Controller [RAID mode]                                                       | 56        | 1.45%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 56        | 1.45%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 55        | 1.42%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 54        | 1.4%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 53        | 1.37%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 51        | 1.32%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 47        | 1.21%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 47        | 1.21%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 46        | 1.19%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 44        | 1.14%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 43        | 1.11%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 42        | 1.09%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 42        | 1.09%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 41        | 1.06%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 39        | 1.01%   |
| Kingston Company A2000 NVMe SSD                                                         | 38        | 0.98%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 36        | 0.93%   |
| AMD 500 Series Chipset SATA Controller                                                  | 36        | 0.93%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 35        | 0.9%    |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 33        | 0.85%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 32        | 0.83%   |
| Intel SSD 660P Series                                                                   | 31        | 0.8%    |
| Intel Comet Lake SATA AHCI Controller                                                   | 30        | 0.78%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 29        | 0.75%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 29        | 0.75%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 29        | 0.75%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 28        | 0.72%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 27        | 0.7%    |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 27        | 0.7%    |
| SK Hynix Gold P31 SSD                                                                   | 23        | 0.59%   |
| KIOXIA Non-Volatile memory controller                                                   | 22        | 0.57%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 22        | 0.57%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 22        | 0.57%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 22        | 0.57%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 22        | 0.57%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 21        | 0.54%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 21        | 0.54%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 21        | 0.54%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 20        | 0.52%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 19        | 0.49%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 19        | 0.49%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 18        | 0.47%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 17        | 0.44%   |
| Micron Non-Volatile memory controller                                                   | 17        | 0.44%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 17        | 0.44%   |
| AMD FCH IDE Controller                                                                  | 17        | 0.44%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller        | 15        | 0.39%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1866      | 55.54%  |
| NVMe | 796       | 23.69%  |
| IDE  | 466       | 13.87%  |
| RAID | 222       | 6.61%   |
| SAS  | 5         | 0.15%   |
| SCSI | 5         | 0.15%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 2109      | 78.46%  |
| AMD          | 539       | 20.05%  |
| ARM          | 37        | 1.38%   |
| CentaurHauls | 2         | 0.07%   |
| QUALCOMM     | 1         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz             | 35        | 1.3%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 29        | 1.08%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 29        | 1.08%   |
| ARM Processor                                 | 28        | 1.04%   |
| AMD Ryzen 5 3600 6-Core Processor             | 25        | 0.93%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 24        | 0.89%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 24        | 0.89%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 24        | 0.89%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 23        | 0.85%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 23        | 0.85%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 22        | 0.82%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 22        | 0.82%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 21        | 0.78%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 19        | 0.71%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 19        | 0.71%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 19        | 0.71%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 19        | 0.71%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 19        | 0.71%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 18        | 0.67%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 17        | 0.63%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 17        | 0.63%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 17        | 0.63%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 16        | 0.59%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 15        | 0.56%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 15        | 0.56%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 15        | 0.56%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 15        | 0.56%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 14        | 0.52%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 14        | 0.52%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 13        | 0.48%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 13        | 0.48%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 13        | 0.48%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 13        | 0.48%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 13        | 0.48%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 13        | 0.48%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 12        | 0.45%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 12        | 0.45%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 12        | 0.45%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 12        | 0.45%   |
| AMD FX-8350 Eight-Core Processor              | 12        | 0.45%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 11        | 0.41%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 11        | 0.41%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 11        | 0.41%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 11        | 0.41%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 11        | 0.41%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 11        | 0.41%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 10        | 0.37%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 10        | 0.37%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 10        | 0.37%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 10        | 0.37%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 10        | 0.37%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 9         | 0.33%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 9         | 0.33%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 9         | 0.33%   |
| Intel Core i7 CPU 920 @ 2.67GHz               | 9         | 0.33%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 9         | 0.33%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 9         | 0.33%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 9         | 0.33%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 9         | 0.33%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 9         | 0.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 619       | 23.01%  |
| Intel Core i7                  | 575       | 21.38%  |
| Intel Core i3                  | 194       | 7.21%   |
| Intel Core 2 Duo               | 138       | 5.13%   |
| AMD Ryzen 5                    | 128       | 4.76%   |
| AMD Ryzen 7                    | 108       | 4.01%   |
| Other                          | 95        | 3.53%   |
| Intel Celeron                  | 95        | 3.53%   |
| Intel Pentium                  | 65        | 2.42%   |
| Intel Xeon                     | 59        | 2.19%   |
| Intel Atom                     | 58        | 2.16%   |
| Intel Pentium Dual-Core        | 40        | 1.49%   |
| Intel Pentium Silver           | 37        | 1.38%   |
| Intel Core 2 Quad              | 35        | 1.3%    |
| AMD Ryzen 9                    | 30        | 1.12%   |
| AMD FX                         | 30        | 1.12%   |
| Intel Core 2                   | 25        | 0.93%   |
| Intel Pentium Dual             | 24        | 0.89%   |
| Intel Core i9                  | 24        | 0.89%   |
| AMD A6                         | 21        | 0.78%   |
| Intel Genuine                  | 20        | 0.74%   |
| AMD Athlon 64 X2               | 19        | 0.71%   |
| AMD A8                         | 19        | 0.71%   |
| AMD Ryzen 5 PRO                | 15        | 0.56%   |
| AMD Ryzen 7 PRO                | 14        | 0.52%   |
| Intel Pentium 4                | 13        | 0.48%   |
| AMD Phenom II X4               | 13        | 0.48%   |
| AMD A4                         | 13        | 0.48%   |
| Intel Pentium D                | 12        | 0.45%   |
| AMD Ryzen 3                    | 12        | 0.45%   |
| AMD E                          | 11        | 0.41%   |
| AMD Athlon II X2               | 11        | 0.41%   |
| AMD A10                        | 11        | 0.41%   |
| ARM BCM                        | 8         | 0.3%    |
| AMD E1                         | 7         | 0.26%   |
| AMD Athlon                     | 7         | 0.26%   |
| AMD Ryzen Threadripper         | 6         | 0.22%   |
| AMD Athlon II X4               | 6         | 0.22%   |
| AMD E2                         | 5         | 0.19%   |
| Intel Core m3                  | 4         | 0.15%   |
| Intel Celeron Dual-Core        | 4         | 0.15%   |
| AMD Athlon X2                  | 4         | 0.15%   |
| AMD Athlon 64                  | 4         | 0.15%   |
| Intel Celeron M                | 3         | 0.11%   |
| AMD Sempron                    | 3         | 0.11%   |
| AMD Phenom II X6               | 3         | 0.11%   |
| AMD Opteron                    | 3         | 0.11%   |
| AMD Athlon II                  | 3         | 0.11%   |
| AMD Athlon Dual Core           | 3         | 0.11%   |
| Intel Pentium Gold             | 2         | 0.07%   |
| AMD Turion X2 Dual-Core Mobile | 2         | 0.07%   |
| AMD Ryzen 3 PRO                | 2         | 0.07%   |
| AMD Mobile Sempron             | 2         | 0.07%   |
| AMD Athlon X4                  | 2         | 0.07%   |
| AMD Athlon II X3               | 2         | 0.07%   |
| QUALCOMM AArch64               | 1         | 0.04%   |
| Intel Xeon Silver              | 1         | 0.04%   |
| Intel Core m7                  | 1         | 0.04%   |
| Intel Core m5                  | 1         | 0.04%   |
| Intel Core Duo                 | 1         | 0.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1070      | 39.78%  |
| 4       | 1058      | 39.33%  |
| 6       | 260       | 9.67%   |
| 8       | 166       | 6.17%   |
| 1       | 74        | 2.75%   |
| 12      | 32        | 1.19%   |
| 3       | 8         | 0.3%    |
| 16      | 6         | 0.22%   |
| 10      | 6         | 0.22%   |
| 24      | 3         | 0.11%   |
| Unknown | 3         | 0.11%   |
| 64      | 1         | 0.04%   |
| 48      | 1         | 0.04%   |
| 32      | 1         | 0.04%   |
| 5       | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2664      | 99.11%  |
| 2       | 21        | 0.78%   |
| 4       | 1         | 0.04%   |
| 3       | 1         | 0.04%   |
| Unknown | 1         | 0.04%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1676      | 62.28%  |
| 1       | 1011      | 37.57%  |
| Unknown | 3         | 0.11%   |
| 16      | 1         | 0.04%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2586      | 95.85%  |
| Unknown        | 85        | 3.15%   |
| 32-bit         | 25        | 0.93%   |
| 64-bit         | 2         | 0.07%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 568       | 20.47%  |
| 0x206a7    | 165       | 5.95%   |
| 0x306a9    | 157       | 5.66%   |
| 0x306c3    | 144       | 5.19%   |
| 0x1067a    | 119       | 4.29%   |
| 0x906ea    | 85        | 3.06%   |
| 0x806ec    | 74        | 2.67%   |
| 0x506e3    | 67        | 2.41%   |
| 0x806ea    | 60        | 2.16%   |
| 0x40651    | 59        | 2.13%   |
| 0x406e3    | 56        | 2.02%   |
| 0x6fd      | 51        | 1.84%   |
| 0x20655    | 50        | 1.8%    |
| 0x806e9    | 49        | 1.77%   |
| 0x906e9    | 48        | 1.73%   |
| 0x806c1    | 45        | 1.62%   |
| 0x08701021 | 41        | 1.48%   |
| 0x306d4    | 39        | 1.41%   |
| 0x08600106 | 34        | 1.23%   |
| 0x30678    | 33        | 1.19%   |
| 0x6fb      | 30        | 1.08%   |
| 0x08701013 | 29        | 1.05%   |
| 0x010000c8 | 29        | 1.05%   |
| 0x806eb    | 27        | 0.97%   |
| 0x10676    | 25        | 0.9%    |
| 0x906c0    | 24        | 0.86%   |
| 0x106e5    | 23        | 0.83%   |
| 0x0800820d | 23        | 0.83%   |
| 0x08108102 | 21        | 0.76%   |
| 0xa0652    | 20        | 0.72%   |
| 0x20652    | 20        | 0.72%   |
| 0x06001119 | 20        | 0.72%   |
| 0x06000852 | 20        | 0.72%   |
| 0x6f6      | 19        | 0.68%   |
| 0x406c4    | 19        | 0.68%   |
| 0x906ed    | 18        | 0.65%   |
| 0x506c9    | 18        | 0.65%   |
| 0x406c3    | 17        | 0.61%   |
| 0x706e5    | 15        | 0.54%   |
| 0x106a5    | 15        | 0.54%   |
| 0x706a1    | 14        | 0.5%    |
| 0x0a50000c | 14        | 0.5%    |
| 0x08108109 | 13        | 0.47%   |
| 0x206c2    | 11        | 0.4%    |
| 0x08600103 | 11        | 0.4%    |
| 0x05000119 | 11        | 0.4%    |
| 0x03000027 | 11        | 0.4%    |
| 0x906ec    | 9         | 0.32%   |
| 0x706a8    | 9         | 0.32%   |
| 0x6e8      | 9         | 0.32%   |
| 0x0a201016 | 9         | 0.32%   |
| 0x08600104 | 9         | 0.32%   |
| 0x0700010f | 9         | 0.32%   |
| 0x06003106 | 9         | 0.32%   |
| 0xa0655    | 8         | 0.29%   |
| 0x40661    | 8         | 0.29%   |
| 0x0a201009 | 8         | 0.29%   |
| 0x08101016 | 8         | 0.29%   |
| 0x0810100b | 8         | 0.29%   |
| 0x6f2      | 7         | 0.25%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 469       | 17.45%  |
| Haswell          | 257       | 9.56%   |
| SandyBridge      | 208       | 7.74%   |
| IvyBridge        | 193       | 7.18%   |
| Penryn           | 166       | 6.18%   |
| Skylake          | 160       | 5.95%   |
| Zen 2            | 146       | 5.43%   |
| Core             | 129       | 4.8%    |
| Westmere         | 100       | 3.72%   |
| Silvermont       | 89        | 3.31%   |
| Zen+             | 79        | 2.94%   |
| Unknown          | 56        | 2.08%   |
| Piledriver       | 49        | 1.82%   |
| TigerLake        | 47        | 1.75%   |
| Broadwell        | 47        | 1.75%   |
| Zen 3            | 46        | 1.71%   |
| Nehalem          | 46        | 1.71%   |
| K10              | 44        | 1.64%   |
| CometLake        | 44        | 1.64%   |
| Zen              | 43        | 1.6%    |
| K8 Hammer        | 35        | 1.3%    |
| NetBurst         | 29        | 1.08%   |
| Goldmont plus    | 23        | 0.86%   |
| IceLake          | 22        | 0.82%   |
| Tremont          | 21        | 0.78%   |
| Goldmont         | 21        | 0.78%   |
| Bobcat           | 17        | 0.63%   |
| Excavator        | 16        | 0.6%    |
| Bonnell          | 14        | 0.52%   |
| K10 Llano        | 13        | 0.48%   |
| P6               | 12        | 0.45%   |
| Jaguar           | 12        | 0.45%   |
| Steamroller      | 11        | 0.41%   |
| Puma             | 8         | 0.3%    |
| K8 & K10 hybrid  | 8         | 0.3%    |
| Bulldozer        | 6         | 0.22%   |
| CannonLake       | 1         | 0.04%   |
| Alderlake Hybrid | 1         | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1555      | 49.73%  |
| Nvidia                           | 902       | 28.85%  |
| AMD                              | 639       | 20.43%  |
| Matrox Electronics Systems       | 13        | 0.42%   |
| Silicon Integrated Systems [SiS] | 7         | 0.22%   |
| VIA Technologies                 | 6         | 0.19%   |
| ASPEED Technology                | 5         | 0.16%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 149       | 4.63%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 119       | 3.69%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 85        | 2.64%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 73        | 2.27%   |
| Intel UHD Graphics 620                                                                   | 65        | 2.02%   |
| AMD Renoir                                                                               | 64        | 1.99%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 63        | 1.96%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 61        | 1.89%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 58        | 1.8%    |
| Intel Core Processor Integrated Graphics Controller                                      | 57        | 1.77%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 57        | 1.77%   |
| Intel HD Graphics 620                                                                    | 50        | 1.55%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 49        | 1.52%   |
| Intel HD Graphics 630                                                                    | 47        | 1.46%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 46        | 1.43%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 45        | 1.4%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 45        | 1.4%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 44        | 1.37%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 43        | 1.33%   |
| Intel HD Graphics 530                                                                    | 42        | 1.3%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 36        | 1.12%   |
| Intel HD Graphics 5500                                                                   | 34        | 1.06%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 32        | 0.99%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 31        | 0.96%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 29        | 0.9%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 29        | 0.9%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 27        | 0.84%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 26        | 0.81%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 25        | 0.78%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 24        | 0.75%   |
| Intel JasperLake [UHD Graphics]                                                          | 24        | 0.75%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 24        | 0.75%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 23        | 0.71%   |
| Nvidia GT218 [GeForce 210]                                                               | 21        | 0.65%   |
| AMD Cezanne                                                                              | 21        | 0.65%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 19        | 0.59%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 19        | 0.59%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 18        | 0.56%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 18        | 0.56%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 18        | 0.56%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 16        | 0.5%    |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 15        | 0.47%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 15        | 0.47%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 13        | 0.4%    |
| Intel GeminiLake [UHD Graphics 605]                                                      | 13        | 0.4%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 13        | 0.4%    |
| Nvidia GP108M [GeForce MX250]                                                            | 12        | 0.37%   |
| Nvidia GP108M [GeForce MX150]                                                            | 12        | 0.37%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 12        | 0.37%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 12        | 0.37%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 12        | 0.37%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 12        | 0.37%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 12        | 0.37%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 12        | 0.37%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                                         | 12        | 0.37%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 12        | 0.37%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 11        | 0.34%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 11        | 0.34%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 10        | 0.31%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 10        | 0.31%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1126      | 41.57%  |
| 1 x AMD                  | 529       | 19.53%  |
| 1 x Nvidia               | 516       | 19.05%  |
| Intel + Nvidia           | 347       | 12.81%  |
| Intel + AMD              | 50        | 1.85%   |
| Other                    | 42        | 1.55%   |
| 2 x AMD                  | 32        | 1.18%   |
| AMD + Nvidia             | 25        | 0.92%   |
| 1 x Matrox               | 10        | 0.37%   |
| 2 x Nvidia               | 9         | 0.33%   |
| 1 x SiS                  | 7         | 0.26%   |
| 1 x VIA                  | 6         | 0.22%   |
| Nvidia + ASPEED          | 3         | 0.11%   |
| Nvidia + Matrox          | 2         | 0.07%   |
| Intel + AMD + 1 x Nvidia | 2         | 0.07%   |
| 1 x ASPEED               | 1         | 0.04%   |
| AMD + Matrox             | 1         | 0.04%   |
| AMD + ASPEED             | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 2117      | 77.38%  |
| Proprietary | 488       | 17.84%  |
| Unknown     | 131       | 4.79%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1476      | 53.44%  |
| 1.01-2.0   | 339       | 12.27%  |
| 0.01-0.5   | 297       | 10.75%  |
| 0.51-1.0   | 232       | 8.4%    |
| 3.01-4.0   | 203       | 7.35%   |
| 7.01-8.0   | 120       | 4.34%   |
| 5.01-6.0   | 61        | 2.21%   |
| 2.01-3.0   | 20        | 0.72%   |
| 8.01-16.0  | 13        | 0.47%   |
| 16.01-24.0 | 1         | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 392       | 13.21%  |
| AU Optronics            | 363       | 12.23%  |
| LG Display              | 260       | 8.76%   |
| Chimei Innolux          | 192       | 6.47%   |
| BOE                     | 188       | 6.33%   |
| Dell                    | 169       | 5.69%   |
| Philips                 | 141       | 4.75%   |
| Iiyama                  | 137       | 4.62%   |
| Goldstar                | 128       | 4.31%   |
| Hewlett-Packard         | 111       | 3.74%   |
| Acer                    | 101       | 3.4%    |
| Sharp                   | 70        | 2.36%   |
| AOC                     | 66        | 2.22%   |
| BenQ                    | 63        | 2.12%   |
| Apple                   | 61        | 2.06%   |
| Ancor Communications    | 48        | 1.62%   |
| Chi Mei Optoelectronics | 43        | 1.45%   |
| Lenovo                  | 38        | 1.28%   |
| LG Philips              | 26        | 0.88%   |
| Idek Iiyama             | 25        | 0.84%   |
| Medion                  | 24        | 0.81%   |
| Sony                    | 21        | 0.71%   |
| LG Electronics          | 19        | 0.64%   |
| InfoVision              | 15        | 0.51%   |
| Eizo                    | 15        | 0.51%   |
| Unknown                 | 13        | 0.44%   |
| PANDA                   | 12        | 0.4%    |
| Packard Bell            | 11        | 0.37%   |
| MSI                     | 11        | 0.37%   |
| Vestel Elektronik       | 9         | 0.3%    |
| Toshiba                 | 9         | 0.3%    |
| Fujitsu Siemens         | 9         | 0.3%    |
| NEC Computers           | 8         | 0.27%   |
| LGD                     | 8         | 0.27%   |
| ASUSTek Computer        | 8         | 0.27%   |
| Panasonic               | 7         | 0.24%   |
| HannStar                | 7         | 0.24%   |
| CSO                     | 7         | 0.24%   |
| ViewSonic               | 6         | 0.2%    |
| CPT                     | 6         | 0.2%    |
| Belinea                 | 6         | 0.2%    |
| Seiko/Epson             | 5         | 0.17%   |
| Marantz                 | 5         | 0.17%   |
| Quanta Display          | 4         | 0.13%   |
| JDI                     | 4         | 0.13%   |
| ONKYO                   | 3         | 0.1%    |
| MStar                   | 3         | 0.1%    |
| Medion Akoya            | 3         | 0.1%    |
| FUS                     | 3         | 0.1%    |
| ___                     | 2         | 0.07%   |
| Wacom                   | 2         | 0.07%   |
| Vizio                   | 2         | 0.07%   |
| Valve                   | 2         | 0.07%   |
| Sun                     | 2         | 0.07%   |
| Sanyo                   | 2         | 0.07%   |
| Ruijiang                | 2         | 0.07%   |
| RIS                     | 2         | 0.07%   |
| Microstep               | 2         | 0.07%   |
| LPL                     | 2         | 0.07%   |
| Lite-On                 | 2         | 0.07%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 16        | 0.52%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch      | 15        | 0.49%   |
| BOE LCD Monitor BOE093D 1366x768 256x144mm 11.6-inch                      | 14        | 0.45%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch     | 13        | 0.42%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                  | 11        | 0.36%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 11        | 0.36%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch          | 11        | 0.36%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 11        | 0.36%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch            | 10        | 0.32%   |
| Vestel Elektronik 22W_LCD_TV VES3700 1920x540                             | 9         | 0.29%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch              | 9         | 0.29%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch            | 9         | 0.29%   |
| LGD LCD Monitor 1920x1080                                                 | 8         | 0.26%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 8         | 0.26%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch      | 7         | 0.23%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch         | 7         | 0.23%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 7         | 0.23%   |
| Iiyama PLT1931 IVM483F 1280x1024 376x301mm 19.0-inch                      | 7         | 0.23%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                 | 7         | 0.23%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch          | 7         | 0.23%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 7         | 0.23%   |
| AU Optronics LCD Monitor AUO213D 1920x1080 309x173mm 13.9-inch            | 7         | 0.23%   |
| Acer AL1716 ACRAD46 1280x1024 338x270mm 17.0-inch                         | 7         | 0.23%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                   | 6         | 0.19%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch                   | 6         | 0.19%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 6         | 0.19%   |
| Iiyama PL2409HD IVM560C 1920x1080 521x293mm 23.5-inch                     | 6         | 0.19%   |
| Hewlett-Packard L1740 HWP2649 1280x1024 338x270mm 17.0-inch               | 6         | 0.19%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch          | 6         | 0.19%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                     | 6         | 0.19%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                     | 6         | 0.19%   |
| AU Optronics LCD Monitor AUO7E91 1366x768 256x144mm 11.6-inch             | 6         | 0.19%   |
| AU Optronics LCD Monitor AUO6287 1440x900 367x229mm 17.0-inch             | 6         | 0.19%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch             | 6         | 0.19%   |
| AU Optronics LCD Monitor AUO202D 1920x1080 293x165mm 13.2-inch            | 6         | 0.19%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch             | 6         | 0.19%   |
| AU Optronics LCD Monitor AUO105C 1366x768 256x144mm 11.6-inch             | 6         | 0.19%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                   | 5         | 0.16%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch                   | 5         | 0.16%   |
| Sharp LCD Monitor SHP143E 3840x2160 346x194mm 15.6-inch                   | 5         | 0.16%   |
| Samsung Electronics S24B350 SAM08DA 1920x1080 531x299mm 24.0-inch         | 5         | 0.16%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch                  | 5         | 0.16%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch               | 5         | 0.16%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch               | 5         | 0.16%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 5         | 0.16%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch               | 5         | 0.16%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                  | 5         | 0.16%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                   | 5         | 0.16%   |
| Hewlett-Packard LA2205 HWP2847 1680x1050 473x296mm 22.0-inch              | 5         | 0.16%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                   | 5         | 0.16%   |
| Goldstar LG HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                  | 5         | 0.16%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                   | 5         | 0.16%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 5         | 0.16%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 5         | 0.16%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch           | 5         | 0.16%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 5         | 0.16%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 5         | 0.16%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch  | 5         | 0.16%   |
| BOE LCD Monitor BOE0744 1366x768 256x144mm 11.6-inch                      | 5         | 0.16%   |
| BOE LCD Monitor BOE06C6 1920x1080 344x194mm 15.5-inch                     | 5         | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1198      | 41.93%  |
| 1366x768 (WXGA)    | 396       | 13.86%  |
| 3840x2160 (4K)     | 174       | 6.09%   |
| 2560x1440 (QHD)    | 164       | 5.74%   |
| 1600x900 (HD+)     | 125       | 4.38%   |
| 1280x1024 (SXGA)   | 122       | 4.27%   |
| 1680x1050 (WSXGA+) | 119       | 4.17%   |
| 1280x800 (WXGA)    | 92        | 3.22%   |
| 1440x900 (WXGA+)   | 79        | 2.77%   |
| 1920x1200 (WUXGA)  | 75        | 2.63%   |
| Unknown            | 47        | 1.65%   |
| 3440x1440          | 40        | 1.4%    |
| 2560x1080          | 29        | 1.02%   |
| 1360x768           | 24        | 0.84%   |
| 3840x1080          | 15        | 0.53%   |
| 2560x1600          | 15        | 0.53%   |
| 1024x768 (XGA)     | 14        | 0.49%   |
| 3840x2400          | 13        | 0.46%   |
| 1920x540           | 12        | 0.42%   |
| 2880x1800          | 10        | 0.35%   |
| 2736x1824          | 7         | 0.25%   |
| 3600x1080          | 5         | 0.18%   |
| 3200x1800 (QHD+)   | 5         | 0.18%   |
| 1600x1200          | 5         | 0.18%   |
| 1280x720 (HD)      | 5         | 0.18%   |
| 7680x2160          | 4         | 0.14%   |
| 3000x2000          | 4         | 0.14%   |
| 2160x1440          | 4         | 0.14%   |
| 2048x1152          | 4         | 0.14%   |
| 1400x1050          | 4         | 0.14%   |
| 3840x1200          | 3         | 0.11%   |
| 2256x1504          | 3         | 0.11%   |
| 1280x960           | 3         | 0.11%   |
| 5760x2160          | 2         | 0.07%   |
| 5760x1080          | 2         | 0.07%   |
| 3456x2160          | 2         | 0.07%   |
| 2304x1440          | 2         | 0.07%   |
| 1680x945           | 2         | 0.07%   |
| 1024x600           | 2         | 0.07%   |
| 8960x2160          | 1         | 0.04%   |
| 800x480            | 1         | 0.04%   |
| 800x1280           | 1         | 0.04%   |
| 6400x2160          | 1         | 0.04%   |
| 6400x1440          | 1         | 0.04%   |
| 5760x1200          | 1         | 0.04%   |
| 5520x2160          | 1         | 0.04%   |
| 5440x1800          | 1         | 0.04%   |
| 5120x2160          | 1         | 0.04%   |
| 5120x1440          | 1         | 0.04%   |
| 4480x1600          | 1         | 0.04%   |
| 4480x1440          | 1         | 0.04%   |
| 3840x1600          | 1         | 0.04%   |
| 3840x1100          | 1         | 0.04%   |
| 3240x2160          | 1         | 0.04%   |
| 3200x1080          | 1         | 0.04%   |
| 3072x1920          | 1         | 0.04%   |
| 2880x1200          | 1         | 0.04%   |
| 2800x1752          | 1         | 0.04%   |
| 2720x1024          | 1         | 0.04%   |
| 2560x1024          | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 680       | 22.95%  |
| 17      | 243       | 8.2%    |
| 13      | 223       | 7.53%   |
| 27      | 215       | 7.26%   |
| 24      | 214       | 7.22%   |
| Unknown | 204       | 6.88%   |
| 23      | 199       | 6.72%   |
| 14      | 164       | 5.53%   |
| 21      | 138       | 4.66%   |
| 19      | 93        | 3.14%   |
| 22      | 74        | 2.5%    |
| 11      | 73        | 2.46%   |
| 12      | 65        | 2.19%   |
| 34      | 55        | 1.86%   |
| 20      | 45        | 1.52%   |
| 31      | 43        | 1.45%   |
| 18      | 32        | 1.08%   |
| 25      | 25        | 0.84%   |
| 84      | 21        | 0.71%   |
| 72      | 17        | 0.57%   |
| 40      | 17        | 0.57%   |
| 10      | 15        | 0.51%   |
| 54      | 12        | 0.4%    |
| 32      | 11        | 0.37%   |
| 16      | 10        | 0.34%   |
| 33      | 8         | 0.27%   |
| 65      | 7         | 0.24%   |
| 28      | 6         | 0.2%    |
| 26      | 6         | 0.2%    |
| 29      | 5         | 0.17%   |
| 52      | 4         | 0.13%   |
| 47      | 4         | 0.13%   |
| 46      | 4         | 0.13%   |
| 43      | 4         | 0.13%   |
| 39      | 3         | 0.1%    |
| 37      | 3         | 0.1%    |
| 36      | 3         | 0.1%    |
| 57      | 2         | 0.07%   |
| 55      | 2         | 0.07%   |
| 48      | 2         | 0.07%   |
| 42      | 2         | 0.07%   |
| 35      | 2         | 0.07%   |
| 8       | 2         | 0.07%   |
| 86      | 1         | 0.03%   |
| 66      | 1         | 0.03%   |
| 64      | 1         | 0.03%   |
| 60      | 1         | 0.03%   |
| 49      | 1         | 0.03%   |
| 41      | 1         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 971       | 33.38%  |
| 501-600     | 599       | 20.59%  |
| 401-500     | 307       | 10.55%  |
| 351-400     | 282       | 9.69%   |
| 201-300     | 282       | 9.69%   |
| Unknown     | 204       | 7.01%   |
| 601-700     | 77        | 2.65%   |
| 701-800     | 72        | 2.48%   |
| 1001-1500   | 40        | 1.38%   |
| 1501-2000   | 39        | 1.34%   |
| 801-900     | 27        | 0.93%   |
| 901-1000    | 7         | 0.24%   |
| 101-200     | 2         | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1865      | 69.54%  |
| 16/10   | 395       | 14.73%  |
| Unknown | 173       | 6.45%   |
| 5/4     | 114       | 4.25%   |
| 21/9    | 63        | 2.35%   |
| 3/2     | 30        | 1.12%   |
| 4/3     | 29        | 1.08%   |
| 6/5     | 5         | 0.19%   |
| 32/9    | 3         | 0.11%   |
| 0.62    | 2         | 0.07%   |
| 3.40    | 1         | 0.04%   |
| 0.80    | 1         | 0.04%   |
| 0.45    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 678       | 23.05%  |
| 201-250        | 494       | 16.79%  |
| 81-90          | 277       | 9.42%   |
| 301-350        | 221       | 7.51%   |
| Unknown        | 204       | 6.93%   |
| 151-200        | 186       | 6.32%   |
| 121-130        | 156       | 5.3%    |
| 351-500        | 128       | 4.35%   |
| 71-80          | 113       | 3.84%   |
| 251-300        | 106       | 3.6%    |
| 51-60          | 75        | 2.55%   |
| 141-150        | 75        | 2.55%   |
| More than 1000 | 70        | 2.38%   |
| 61-70          | 58        | 1.97%   |
| 501-1000       | 42        | 1.43%   |
| 131-140        | 30        | 1.02%   |
| 41-50          | 14        | 0.48%   |
| 111-120        | 10        | 0.34%   |
| 91-100         | 3         | 0.1%    |
| 1-40           | 2         | 0.07%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 970       | 33.99%  |
| 121-160       | 756       | 26.49%  |
| 101-120       | 619       | 21.69%  |
| Unknown       | 204       | 7.15%   |
| 161-240       | 143       | 5.01%   |
| More than 240 | 95        | 3.33%   |
| 1-50          | 67        | 2.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 2135      | 77.47%  |
| 2     | 449       | 16.29%  |
| 0     | 126       | 4.57%   |
| 3     | 43        | 1.56%   |
| 4     | 3         | 0.11%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 1386      | 34.86%  |
| Realtek Semiconductor                  | 1300      | 32.7%   |
| Qualcomm Atheros                       | 429       | 10.79%  |
| Broadcom                               | 253       | 6.36%   |
| Broadcom Limited                       | 65        | 1.63%   |
| Marvell Technology Group               | 58        | 1.46%   |
| TP-Link                                | 53        | 1.33%   |
| Ralink Technology                      | 46        | 1.16%   |
| Ralink                                 | 43        | 1.08%   |
| Nvidia                                 | 38        | 0.96%   |
| Dell                                   | 23        | 0.58%   |
| Hewlett-Packard                        | 20        | 0.5%    |
| DisplayLink                            | 16        | 0.4%    |
| Sitecom Europe                         | 15        | 0.38%   |
| ASIX Electronics                       | 15        | 0.38%   |
| MEDIATEK                               | 14        | 0.35%   |
| JMicron Technology                     | 11        | 0.28%   |
| Ericsson Business Mobile Networks      | 11        | 0.28%   |
| ASUSTek Computer                       | 11        | 0.28%   |
| Sierra Wireless                        | 10        | 0.25%   |
| NetGear                                | 10        | 0.25%   |
| Microsoft                              | 10        | 0.25%   |
| IMC Networks                           | 10        | 0.25%   |
| Silicon Integrated Systems [SiS]       | 8         | 0.2%    |
| Huawei Technologies                    | 8         | 0.2%    |
| VIA Technologies                       | 6         | 0.15%   |
| Samsung Electronics                    | 6         | 0.15%   |
| Gemtek                                 | 6         | 0.15%   |
| Qualcomm                               | 5         | 0.13%   |
| Lenovo                                 | 5         | 0.13%   |
| Xiaomi                                 | 4         | 0.1%    |
| Mellanox Technologies                  | 4         | 0.1%    |
| ULi Electronics                        | 3         | 0.08%   |
| U-Blox                                 | 3         | 0.08%   |
| Standard Microsystems                  | 3         | 0.08%   |
| Sigma Designs                          | 3         | 0.08%   |
| Qualcomm Atheros Communications        | 3         | 0.08%   |
| OnePlus Technology (Shenzhen)          | 3         | 0.08%   |
| Motorola PCS                           | 3         | 0.08%   |
| Linksys                                | 3         | 0.08%   |
| Edimax Technology                      | 3         | 0.08%   |
| D-Link                                 | 3         | 0.08%   |
| Belkin Components                      | 3         | 0.08%   |
| Arduino SA                             | 3         | 0.08%   |
| Aquantia                               | 3         | 0.08%   |
| 802.11g Adapter [Linksys WUSB54GC v3]  | 3         | 0.08%   |
| Texas Instruments                      | 2         | 0.05%   |
| Senao                                  | 2         | 0.05%   |
| Sagem                                  | 2         | 0.05%   |
| Microchip Technology                   | 2         | 0.05%   |
| Fibocom                                | 2         | 0.05%   |
| Accton Technology                      | 2         | 0.05%   |
| 3Com                                   | 2         | 0.05%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.03%   |
| Wilocity                               | 1         | 0.03%   |
| Tenda                                  | 1         | 0.03%   |
| Sundance Technology Inc / IC Plus      | 1         | 0.03%   |
| Spreadtrum Communications              | 1         | 0.03%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.03%   |
| QLogic                                 | 1         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 969       | 20.92%  |
| Intel Wi-Fi 6 AX200                                                     | 142       | 3.07%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 120       | 2.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 116       | 2.5%    |
| Intel Wireless 8265 / 8275                                              | 90        | 1.94%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 80        | 1.73%   |
| Intel I211 Gigabit Network Connection                                   | 75        | 1.62%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 70        | 1.51%   |
| Intel Wireless 7265                                                     | 64        | 1.38%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 56        | 1.21%   |
| Intel Wireless 7260                                                     | 56        | 1.21%   |
| Intel Ethernet Connection (2) I219-V                                    | 52        | 1.12%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 51        | 1.1%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 49        | 1.06%   |
| Intel Wireless 8260                                                     | 47        | 1.01%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 46        | 0.99%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 43        | 0.93%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 38        | 0.82%   |
| Intel Wi-Fi 6 AX201                                                     | 38        | 0.82%   |
| Intel Wireless 3165                                                     | 37        | 0.8%    |
| Intel Wireless-AC 9260                                                  | 35        | 0.76%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 35        | 0.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 34        | 0.73%   |
| Realtek RTL8125 2.5GbE Controller                                       | 32        | 0.69%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 32        | 0.69%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 32        | 0.69%   |
| Intel Ethernet Connection I217-LM                                       | 31        | 0.67%   |
| Intel 82579V Gigabit Network Connection                                 | 31        | 0.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 30        | 0.65%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 30        | 0.65%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 28        | 0.6%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 27        | 0.58%   |
| Intel Ethernet Connection I219-LM                                       | 27        | 0.58%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 26        | 0.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 26        | 0.56%   |
| Intel Wireless 3160                                                     | 25        | 0.54%   |
| Intel Ethernet Connection (6) I219-V                                    | 25        | 0.54%   |
| Intel Centrino Ultimate-N 6300                                          | 25        | 0.54%   |
| Intel 82577LM Gigabit Network Connection                                | 25        | 0.54%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 25        | 0.54%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 24        | 0.52%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller               | 22        | 0.48%   |
| Intel Ethernet Connection I218-LM                                       | 21        | 0.45%   |
| Intel Centrino Advanced-N 6200                                          | 21        | 0.45%   |
| Intel Ethernet Connection I217-V                                        | 20        | 0.43%   |
| Intel Ethernet Connection (4) I219-LM                                   | 20        | 0.43%   |
| Intel 82567LM-3 Gigabit Network Connection                              | 20        | 0.43%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 20        | 0.43%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 19        | 0.41%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 19        | 0.41%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 18        | 0.39%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 18        | 0.39%   |
| Intel Ethernet Connection (4) I219-V                                    | 18        | 0.39%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 18        | 0.39%   |
| Intel Ethernet Connection (7) I219-V                                    | 17        | 0.37%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                         | 17        | 0.37%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 16        | 0.35%   |
| Intel Centrino Advanced-N 6235                                          | 16        | 0.35%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 15        | 0.32%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 15        | 0.32%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1029      | 50.29%  |
| Qualcomm Atheros                      | 341       | 16.67%  |
| Realtek Semiconductor                 | 224       | 10.95%  |
| Broadcom                              | 151       | 7.38%   |
| TP-Link                               | 47        | 2.3%    |
| Ralink Technology                     | 46        | 2.25%   |
| Ralink                                | 43        | 2.1%    |
| Broadcom Limited                      | 29        | 1.42%   |
| Sitecom Europe                        | 15        | 0.73%   |
| MEDIATEK                              | 12        | 0.59%   |
| ASUSTek Computer                      | 11        | 0.54%   |
| Sierra Wireless                       | 10        | 0.49%   |
| NetGear                               | 10        | 0.49%   |
| IMC Networks                          | 10        | 0.49%   |
| Marvell Technology Group              | 9         | 0.44%   |
| Dell                                  | 9         | 0.44%   |
| Microsoft                             | 8         | 0.39%   |
| Gemtek                                | 6         | 0.29%   |
| Hewlett-Packard                       | 4         | 0.2%    |
| Qualcomm Atheros Communications       | 3         | 0.15%   |
| Qualcomm                              | 3         | 0.15%   |
| Linksys                               | 3         | 0.15%   |
| Edimax Technology                     | 3         | 0.15%   |
| D-Link                                | 3         | 0.15%   |
| Belkin Components                     | 3         | 0.15%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.15%   |
| Senao                                 | 2         | 0.1%    |
| Sagem                                 | 2         | 0.1%    |
| Wilocity                              | 1         | 0.05%   |
| Tenda                                 | 1         | 0.05%   |
| Samsung Electronics                   | 1         | 0.05%   |
| Fibocom                               | 1         | 0.05%   |
| CyberTAN Technology                   | 1         | 0.05%   |
| Cinterion                             | 1         | 0.05%   |
| BUFFALO                               | 1         | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 142       | 6.91%   |
| Intel Wireless 8265 / 8275                                              | 90        | 4.38%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 70        | 3.4%    |
| Intel Wireless 7265                                                     | 64        | 3.11%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 56        | 2.72%   |
| Intel Wireless 7260                                                     | 56        | 2.72%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 51        | 2.48%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 49        | 2.38%   |
| Intel Wireless 8260                                                     | 47        | 2.29%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 46        | 2.24%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 43        | 2.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 38        | 1.85%   |
| Intel Wi-Fi 6 AX201                                                     | 38        | 1.85%   |
| Intel Wireless 3165                                                     | 37        | 1.8%    |
| Intel Wireless-AC 9260                                                  | 35        | 1.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 35        | 1.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 34        | 1.65%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 32        | 1.56%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 32        | 1.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 30        | 1.46%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 30        | 1.46%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 28        | 1.36%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 26        | 1.26%   |
| Intel Wireless 3160                                                     | 25        | 1.22%   |
| Intel Centrino Ultimate-N 6300                                          | 25        | 1.22%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 25        | 1.22%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 24        | 1.17%   |
| Intel Centrino Advanced-N 6200                                          | 21        | 1.02%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 20        | 0.97%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 19        | 0.92%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 19        | 0.92%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 18        | 0.88%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 18        | 0.88%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 18        | 0.88%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 16        | 0.78%   |
| Intel Centrino Advanced-N 6235                                          | 16        | 0.78%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 15        | 0.73%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 15        | 0.73%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 14        | 0.68%   |
| Broadcom BCM43142 802.11b/g/n                                           | 14        | 0.68%   |
| Ralink RT5370 Wireless Adapter                                          | 13        | 0.63%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 13        | 0.63%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 12        | 0.58%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 12        | 0.58%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 12        | 0.58%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 12        | 0.58%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 12        | 0.58%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 11        | 0.54%   |
| Intel Centrino Wireless-N 2230                                          | 11        | 0.54%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 10        | 0.49%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 10        | 0.49%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 10        | 0.49%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 10        | 0.49%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 10        | 0.49%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 9         | 0.44%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 9         | 0.44%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 9         | 0.44%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 9         | 0.44%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                       | 9         | 0.44%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 9         | 0.44%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1216      | 49.63%  |
| Intel                                  | 718       | 29.31%  |
| Qualcomm Atheros                       | 141       | 5.76%   |
| Broadcom                               | 131       | 5.35%   |
| Marvell Technology Group               | 49        | 2%      |
| Nvidia                                 | 37        | 1.51%   |
| Broadcom Limited                       | 36        | 1.47%   |
| DisplayLink                            | 16        | 0.65%   |
| ASIX Electronics                       | 15        | 0.61%   |
| JMicron Technology                     | 11        | 0.45%   |
| Silicon Integrated Systems [SiS]       | 8         | 0.33%   |
| VIA Technologies                       | 6         | 0.24%   |
| TP-Link                                | 6         | 0.24%   |
| Huawei Technologies                    | 6         | 0.24%   |
| Lenovo                                 | 5         | 0.2%    |
| Xiaomi                                 | 4         | 0.16%   |
| Hewlett-Packard                        | 4         | 0.16%   |
| Standard Microsystems                  | 3         | 0.12%   |
| Samsung Electronics                    | 3         | 0.12%   |
| Mellanox Technologies                  | 3         | 0.12%   |
| Aquantia                               | 3         | 0.12%   |
| ULi Electronics                        | 2         | 0.08%   |
| Qualcomm                               | 2         | 0.08%   |
| Motorola PCS                           | 2         | 0.08%   |
| Microsoft                              | 2         | 0.08%   |
| Microchip Technology                   | 2         | 0.08%   |
| Accton Technology                      | 2         | 0.08%   |
| 3Com                                   | 2         | 0.08%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.04%   |
| Sundance Technology Inc / IC Plus      | 1         | 0.04%   |
| Spreadtrum Communications              | 1         | 0.04%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.04%   |
| QLogic                                 | 1         | 0.04%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.04%   |
| MosChip Semiconductor                  | 1         | 0.04%   |
| MediaTek                               | 1         | 0.04%   |
| Jolla Oy                               | 1         | 0.04%   |
| ICS Advent                             | 1         | 0.04%   |
| Google                                 | 1         | 0.04%   |
| Fibocom                                | 1         | 0.04%   |
| Emulex                                 | 1         | 0.04%   |
| Apple                                  | 1         | 0.04%   |
| ADMtek                                 | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 969       | 38.62%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 120       | 4.78%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 116       | 4.62%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 80        | 3.19%   |
| Intel I211 Gigabit Network Connection                             | 75        | 2.99%   |
| Intel Ethernet Connection (2) I219-V                              | 52        | 2.07%   |
| Realtek RTL8125 2.5GbE Controller                                 | 32        | 1.28%   |
| Intel Ethernet Connection I217-LM                                 | 31        | 1.24%   |
| Intel 82579V Gigabit Network Connection                           | 31        | 1.24%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 27        | 1.08%   |
| Intel Ethernet Connection I219-LM                                 | 27        | 1.08%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 26        | 1.04%   |
| Intel Ethernet Connection (6) I219-V                              | 25        | 1%      |
| Intel 82577LM Gigabit Network Connection                          | 25        | 1%      |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 22        | 0.88%   |
| Intel Ethernet Connection I218-LM                                 | 21        | 0.84%   |
| Intel Ethernet Connection I217-V                                  | 20        | 0.8%    |
| Intel Ethernet Connection (4) I219-LM                             | 20        | 0.8%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 20        | 0.8%    |
| Intel Ethernet Connection (4) I219-V                              | 18        | 0.72%   |
| Intel Ethernet Connection (7) I219-V                              | 17        | 0.68%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 17        | 0.68%   |
| Intel Ethernet Connection (2) I219-LM                             | 15        | 0.6%    |
| Intel 82566DM-2 Gigabit Network Connection                        | 15        | 0.6%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 14        | 0.56%   |
| Intel Ethernet Connection (3) I218-LM                             | 14        | 0.56%   |
| Intel 82574L Gigabit Network Connection                           | 14        | 0.56%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 13        | 0.52%   |
| Nvidia MCP79 Ethernet                                             | 13        | 0.52%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 13        | 0.52%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 12        | 0.48%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 12        | 0.48%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 11        | 0.44%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 11        | 0.44%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 11        | 0.44%   |
| Intel I210 Gigabit Network Connection                             | 11        | 0.44%   |
| Intel Ethernet Connection (7) I219-LM                             | 11        | 0.44%   |
| Intel Ethernet Connection (2) I218-V                              | 11        | 0.44%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 11        | 0.44%   |
| ASIX AX88179 Gigabit Ethernet                                     | 11        | 0.44%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 10        | 0.4%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 10        | 0.4%    |
| Intel 82567LM Gigabit Network Connection                          | 10        | 0.4%    |
| Intel Ethernet Controller I225-V                                  | 9         | 0.36%   |
| Intel Ethernet Connection (6) I219-LM                             | 9         | 0.36%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 8         | 0.32%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 8         | 0.32%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 8         | 0.32%   |
| Intel NM10/ICH7 Family LAN Controller                             | 8         | 0.32%   |
| Intel Ethernet Connection (5) I219-LM                             | 8         | 0.32%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 8         | 0.32%   |
| Intel Ethernet Connection (10) I219-V                             | 7         | 0.28%   |
| Intel 82573L Gigabit Ethernet Controller                          | 7         | 0.28%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 7         | 0.28%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 7         | 0.28%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 7         | 0.28%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 7         | 0.28%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 6         | 0.24%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 6         | 0.24%   |
| Nvidia MCP77 Ethernet                                             | 6         | 0.24%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2316      | 53.67%  |
| WiFi     | 1934      | 44.82%  |
| Modem    | 58        | 1.34%   |
| Unknown  | 7         | 0.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1469      | 52.04%  |
| Ethernet | 1353      | 47.93%  |
| Unknown  | 1         | 0.04%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1426      | 52.91%  |
| 1     | 1126      | 41.78%  |
| 0     | 72        | 2.67%   |
| 3     | 53        | 1.97%   |
| 4     | 12        | 0.45%   |
| 7     | 3         | 0.11%   |
| 6     | 2         | 0.07%   |
| 8     | 1         | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2333      | 84.84%  |
| Yes  | 417       | 15.16%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 787       | 51.54%  |
| Cambridge Silicon Radio         | 135       | 8.84%   |
| Qualcomm Atheros Communications | 102       | 6.68%   |
| Realtek Semiconductor           | 91        | 5.96%   |
| Broadcom                        | 81        | 5.3%    |
| Apple                           | 61        | 3.99%   |
| Lite-On Technology              | 48        | 3.14%   |
| IMC Networks                    | 43        | 2.82%   |
| Hewlett-Packard                 | 36        | 2.36%   |
| Foxconn / Hon Hai               | 34        | 2.23%   |
| ASUSTek Computer                | 33        | 2.16%   |
| Dell                            | 27        | 1.77%   |
| Toshiba                         | 16        | 1.05%   |
| Marvell Semiconductor           | 9         | 0.59%   |
| Ralink                          | 6         | 0.39%   |
| MediaTek                        | 3         | 0.2%    |
| Alps Electric                   | 3         | 0.2%    |
| Sitecom Europe                  | 2         | 0.13%   |
| Ralink Technology               | 2         | 0.13%   |
| Integrated System Solution      | 2         | 0.13%   |
| TP-Link                         | 1         | 0.07%   |
| Roper                           | 1         | 0.07%   |
| Realtek                         | 1         | 0.07%   |
| Micro Star International        | 1         | 0.07%   |
| Chicony Electronics             | 1         | 0.07%   |
| Unknown                         | 1         | 0.07%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 298       | 19.5%   |
| Intel AX200 Bluetooth                                 | 135       | 8.84%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 135       | 8.84%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 121       | 7.92%   |
| Intel AX201 Bluetooth                                 | 119       | 7.79%   |
| Realtek Bluetooth Radio                               | 42        | 2.75%   |
| Qualcomm Atheros  Bluetooth Device                    | 35        | 2.29%   |
| Intel Wireless-AC 3168 Bluetooth                      | 35        | 2.29%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 33        | 2.16%   |
| Realtek  Bluetooth 4.2 Adapter                        | 31        | 2.03%   |
| Apple Bluetooth Host Controller                       | 27        | 1.77%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 23        | 1.51%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 22        | 1.44%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 22        | 1.44%   |
| Lite-On Bluetooth Device                              | 21        | 1.37%   |
| Foxconn / Hon Hai Bluetooth Device                    | 20        | 1.31%   |
| HP Broadcom 2070 Bluetooth Combo                      | 19        | 1.24%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 18        | 1.18%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]         | 17        | 1.11%   |
| IMC Networks Bluetooth Radio                          | 14        | 0.92%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                  | 14        | 0.92%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter      | 13        | 0.85%   |
| IMC Networks Bluetooth Device                         | 13        | 0.85%   |
| Dell DW375 Bluetooth Module                           | 13        | 0.85%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 13        | 0.85%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth            | 12        | 0.79%   |
| Broadcom BCM2045B (BDC-2.1)                           | 12        | 0.79%   |
| Apple Bluetooth USB Host Controller                   | 12        | 0.79%   |
| Dell BCM20702A0 Bluetooth Module                      | 11        | 0.72%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]            | 11        | 0.72%   |
| Broadcom BCM2045 Bluetooth                            | 11        | 0.72%   |
| Intel AX210 Bluetooth                                 | 10        | 0.65%   |
| Realtek 802.11ac WLAN Adapter                         | 9         | 0.59%   |
| Broadcom HP Portable SoftSailing                      | 9         | 0.59%   |
| Broadcom HP Portable Bumble Bee                       | 8         | 0.52%   |
| Apple Bluetooth HCI                                   | 8         | 0.52%   |
| Marvell Bluetooth and Wireless LAN Composite          | 7         | 0.46%   |
| Lite-On Atheros AR3012 Bluetooth                      | 7         | 0.46%   |
| Foxconn / Hon Hai BCM20702A0                          | 7         | 0.46%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter               | 6         | 0.39%   |
| Ralink RT3290 Bluetooth                               | 6         | 0.39%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter     | 5         | 0.33%   |
| IMC Networks Wireless_Device                          | 4         | 0.26%   |
| Broadcom BCM43142 Bluetooth 4.0                       | 4         | 0.26%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 4         | 0.26%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]    | 4         | 0.26%   |
| ASUS Bluetooth Radio                                  | 4         | 0.26%   |
| ASUS ASUS USB-BT500                                   | 4         | 0.26%   |
| Toshiba Bluetooth USB Host Controller                 | 3         | 0.2%    |
| Toshiba Atheros AR3012 Bluetooth                      | 3         | 0.2%    |
| Realtek RTL8723B Bluetooth                            | 3         | 0.2%    |
| Qualcomm Atheros Bluetooth USB Host Controller        | 3         | 0.2%    |
| IMC Networks Bluetooth Module                         | 3         | 0.2%    |
| Foxconn / Hon Hai Wireless_Device                     | 3         | 0.2%    |
| Broadcom BCM43142A0 Bluetooth 4.0                     | 3         | 0.2%    |
| Broadcom BCM20703A1 Bluetooth 4.1 + LE                | 3         | 0.2%    |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 3         | 0.2%    |
| Toshiba RT Bluetooth Radio                            | 2         | 0.13%   |
| Toshiba Integrated Bluetooth HCI                      | 2         | 0.13%   |
| Toshiba Bluetooth Device                              | 2         | 0.13%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1974      | 53.48%  |
| AMD                                          | 684       | 18.53%  |
| Nvidia                                       | 634       | 17.18%  |
| C-Media Electronics                          | 56        | 1.52%   |
| Realtek Semiconductor                        | 27        | 0.73%   |
| Logitech                                     | 26        | 0.7%    |
| Creative Labs                                | 23        | 0.62%   |
| GN Netcom                                    | 21        | 0.57%   |
| Texas Instruments                            | 19        | 0.51%   |
| Focusrite-Novation                           | 15        | 0.41%   |
| Creative Technology                          | 13        | 0.35%   |
| Silicon Integrated Systems [SiS]             | 11        | 0.3%    |
| Kingston Technology                          | 10        | 0.27%   |
| BEHRINGER International                      | 10        | 0.27%   |
| VIA Technologies                             | 9         | 0.24%   |
| JMTek                                        | 9         | 0.24%   |
| Corsair                                      | 9         | 0.24%   |
| Plantronics                                  | 8         | 0.22%   |
| SteelSeries ApS                              | 7         | 0.19%   |
| Sennheiser Communications                    | 7         | 0.19%   |
| Apple                                        | 6         | 0.16%   |
| RODE Microphones                             | 5         | 0.14%   |
| Generalplus Technology                       | 5         | 0.14%   |
| Yamaha                                       | 4         | 0.11%   |
| Sony                                         | 4         | 0.11%   |
| Native Instruments                           | 4         | 0.11%   |
| Lenovo                                       | 4         | 0.11%   |
| GYROCOM C&C                                  | 4         | 0.11%   |
| XMOS                                         | 3         | 0.08%   |
| Tenx Technology                              | 3         | 0.08%   |
| Samson Technologies                          | 3         | 0.08%   |
| Razer USA                                    | 3         | 0.08%   |
| M-Audio                                      | 3         | 0.08%   |
| Hewlett-Packard                              | 3         | 0.08%   |
| Guillemot                                    | 3         | 0.08%   |
| Cambridge Silicon Radio                      | 3         | 0.08%   |
| Blue Microphones                             | 3         | 0.08%   |
| AKAI Professional M.I.                       | 3         | 0.08%   |
| Valve Software                               | 2         | 0.05%   |
| ULi Electronics                              | 2         | 0.05%   |
| Schiit Audio                                 | 2         | 0.05%   |
| SAVITECH                                     | 2         | 0.05%   |
| Philips (or NXP)                             | 2         | 0.05%   |
| Google                                       | 2         | 0.05%   |
| FiiO Electronics Technology                  | 2         | 0.05%   |
| Dell                                         | 2         | 0.05%   |
| Cooler Master                                | 2         | 0.05%   |
| Audient                                      | 2         | 0.05%   |
| ASUSTek Computer                             | 2         | 0.05%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.03%   |
| Xilinx                                       | 1         | 0.03%   |
| Veho                                         | 1         | 0.03%   |
| Unknown                                      | 1         | 0.03%   |
| Turtle Beach                                 | 1         | 0.03%   |
| Trust                                        | 1         | 0.03%   |
| Thesycon Systemsoftware & Consulting         | 1         | 0.03%   |
| SlrTek                                       | 1         | 0.03%   |
| Shenzhen Riitek Technology                   | 1         | 0.03%   |
| PreSonus Audio Electronics                   | 1         | 0.03%   |
| Pioneer DJ                                   | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 197       | 4.58%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 197       | 4.58%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 185       | 4.3%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 149       | 3.46%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 148       | 3.44%   |
| Intel Cannon Lake PCH cAVS                                                                        | 122       | 2.84%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 111       | 2.58%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 104       | 2.42%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 104       | 2.42%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 99        | 2.3%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 94        | 2.18%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 86        | 2%      |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 83        | 1.93%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 82        | 1.91%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 75        | 1.74%   |
| AMD FCH Azalia Controller                                                                         | 73        | 1.7%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 65        | 1.51%   |
| Intel 8 Series HD Audio Controller                                                                | 65        | 1.51%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 64        | 1.49%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 62        | 1.44%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 61        | 1.42%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 58        | 1.35%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 54        | 1.25%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 52        | 1.21%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 48        | 1.12%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 47        | 1.09%   |
| Nvidia High Definition Audio Controller                                                           | 46        | 1.07%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 46        | 1.07%   |
| Intel 200 Series PCH HD Audio                                                                     | 44        | 1.02%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 43        | 1%      |
| Intel Broadwell-U Audio Controller                                                                | 43        | 1%      |
| Nvidia TU106 High Definition Audio Controller                                                     | 41        | 0.95%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 41        | 0.95%   |
| Intel CM238 HD Audio Controller                                                                   | 40        | 0.93%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 39        | 0.91%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 37        | 0.86%   |
| Intel Comet Lake PCH cAVS                                                                         | 35        | 0.81%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 33        | 0.77%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 28        | 0.65%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 28        | 0.65%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 25        | 0.58%   |
| AMD Navi 10 HDMI Audio                                                                            | 25        | 0.58%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 25        | 0.58%   |
| Realtek Semiconductor USB Audio                                                                   | 24        | 0.56%   |
| Intel Jasper Lake HD Audio                                                                        | 24        | 0.56%   |
| AMD Kabini HDMI/DP Audio                                                                          | 24        | 0.56%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 23        | 0.53%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 23        | 0.53%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 23        | 0.53%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 22        | 0.51%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 22        | 0.51%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 21        | 0.49%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 21        | 0.49%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 21        | 0.49%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 20        | 0.46%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 19        | 0.44%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 19        | 0.44%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 19        | 0.44%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 19        | 0.44%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 18        | 0.42%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 298       | 21.38%  |
| Samsung Electronics | 263       | 18.87%  |
| Kingston            | 169       | 12.12%  |
| Micron Technology   | 131       | 9.4%    |
| Unknown             | 123       | 8.82%   |
| Corsair             | 122       | 8.75%   |
| Crucial             | 95        | 6.81%   |
| G.Skill             | 40        | 2.87%   |
| A-DATA Technology   | 21        | 1.51%   |
| Ramaxel Technology  | 20        | 1.43%   |
| Nanya Technology    | 19        | 1.36%   |
| Elpida              | 16        | 1.15%   |
| Transcend           | 9         | 0.65%   |
| Team                | 7         | 0.5%    |
| Unknown             | 6         | 0.43%   |
| ASint Technology    | 5         | 0.36%   |
| Unknown (ABCD)      | 4         | 0.29%   |
| Qimonda             | 4         | 0.29%   |
| 48spaces            | 4         | 0.29%   |
| GeIL                | 3         | 0.22%   |
| Wilk                | 2         | 0.14%   |
| Toshiba             | 2         | 0.14%   |
| TakeMS              | 2         | 0.14%   |
| Patriot             | 2         | 0.14%   |
| GOODRAM             | 2         | 0.14%   |
| Axiom               | 2         | 0.14%   |
| zApacer             | 1         | 0.07%   |
| Unknown (AD8A)      | 1         | 0.07%   |
| Unknown (0x873E)    | 1         | 0.07%   |
| Unknown (08C8)      | 1         | 0.07%   |
| SHARETRONIC         | 1         | 0.07%   |
| Sesame              | 1         | 0.07%   |
| PKI/Kingston        | 1         | 0.07%   |
| OCZ                 | 1         | 0.07%   |
| Micron/Elpida       | 1         | 0.07%   |
| Kllisre             | 1         | 0.07%   |
| Kingmax             | 1         | 0.07%   |
| Juhor               | 1         | 0.07%   |
| HPE                 | 1         | 0.07%   |
| Hewlett-Packard     | 1         | 0.07%   |
| Goldkey             | 1         | 0.07%   |
| Golden Empire       | 1         | 0.07%   |
| F7852C80            | 1         | 0.07%   |
| CSX                 | 1         | 0.07%   |
| Avant               | 1         | 0.07%   |
| Apacer              | 1         | 0.07%   |
| AMD                 | 1         | 0.07%   |
| A-DA                | 1         | 0.07%   |
| A Force             | 1         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 22        | 1.47%   |
| SK Hynix RAM HCNNNBKMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 19        | 1.27%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 15        | 1%      |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 10        | 0.67%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 10        | 0.67%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 9         | 0.6%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 9         | 0.6%    |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 9         | 0.6%    |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 0.53%   |
| SK Hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 8         | 0.53%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 8         | 0.53%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 0.53%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 0.53%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 8         | 0.53%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 7         | 0.47%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 7         | 0.47%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 7         | 0.47%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 7         | 0.47%   |
| Crucial RAM BLS4G3D1609DS1S00. 4GB DIMM DDR3 1600MT/s            | 7         | 0.47%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s            | 7         | 0.47%   |
| Unknown RAM Module 1GB SODIMM DDR3 1333MT/s                      | 6         | 0.4%    |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 6         | 0.4%    |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 6         | 0.4%    |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 6         | 0.4%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 0.4%    |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 6         | 0.4%    |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s           | 6         | 0.4%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 6         | 0.4%    |
| Crucial RAM BLS8G3D1609DS1S00. 8192MB DIMM DDR3 1600MT/s         | 6         | 0.4%    |
| Unknown                                                          | 6         | 0.4%    |
| SK Hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s        | 5         | 0.33%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 5         | 0.33%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 5         | 0.33%   |
| Samsung RAM M471B5273DH0-CK0 4096MB SODIMM DDR3 1600MT/s         | 5         | 0.33%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 0.33%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 5         | 0.33%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 5         | 0.33%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 5         | 0.33%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 5         | 0.33%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 5         | 0.33%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 5         | 0.33%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8192MB SODIMM DDR3 1600MT/s         | 5         | 0.33%   |
| Kingston RAM KHX1600C10D3/8G 4096MB DIMM DDR3 1600MT/s           | 5         | 0.33%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3200MT/s            | 5         | 0.33%   |
| Corsair RAM CMK16GX4M2A2400C16 8GB DIMM DDR4 2933MT/s            | 5         | 0.33%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 4         | 0.27%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 4         | 0.27%   |
| Team RAM TEAMGROUP-SD4-2400 16GB SODIMM DDR4 8400MT/s            | 4         | 0.27%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 4         | 0.27%   |
| SK Hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 4         | 0.27%   |
| SK Hynix RAM HMAA2GS6CJR8N-XN 16384MB SODIMM DDR4 3200MT/s       | 4         | 0.27%   |
| SK Hynix RAM HMAA1GS6CMR6N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 0.27%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 4         | 0.27%   |
| SK Hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 4         | 0.27%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16384MB SODIMM DDR4 2667MT/s       | 4         | 0.27%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 0.27%   |
| SK Hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 4         | 0.27%   |
| SK Hynix RAM 0000000000-00000 8GB SODIMM DDR4 2400MT/s           | 4         | 0.27%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                   | 4         | 0.27%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 4         | 0.27%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 574       | 46.7%   |
| DDR3    | 415       | 33.77%  |
| DDR2    | 59        | 4.8%    |
| LPDDR4  | 57        | 4.64%   |
| LPDDR3  | 48        | 3.91%   |
| SDRAM   | 43        | 3.5%    |
| Unknown | 22        | 1.79%   |
| DDR     | 7         | 0.57%   |
| DRAM    | 3         | 0.24%   |
| EEPROM  | 1         | 0.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 686       | 55.95%  |
| DIMM         | 414       | 33.77%  |
| Row Of Chips | 110       | 8.97%   |
| Chip         | 7         | 0.57%   |
| Unknown      | 7         | 0.57%   |
| RIMM         | 1         | 0.08%   |
| FB-DIMM      | 1         | 0.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 487       | 36.37%  |
| 4096  | 363       | 27.11%  |
| 16384 | 201       | 15.01%  |
| 2048  | 185       | 13.82%  |
| 1024  | 57        | 4.26%   |
| 32768 | 35        | 2.61%   |
| 512   | 8         | 0.6%    |
| 256   | 1         | 0.07%   |
| 64    | 1         | 0.07%   |
| 1     | 1         | 0.07%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 246       | 18.72%  |
| 2667    | 215       | 16.36%  |
| 3200    | 151       | 11.49%  |
| 1333    | 106       | 8.07%   |
| 2133    | 86        | 6.54%   |
| 2400    | 80        | 6.09%   |
| 4267    | 46        | 3.5%    |
| 1334    | 45        | 3.42%   |
| 3600    | 39        | 2.97%   |
| 1867    | 37        | 2.82%   |
| 800     | 35        | 2.66%   |
| 667     | 32        | 2.44%   |
| Unknown | 26        | 1.98%   |
| 3466    | 13        | 0.99%   |
| 3000    | 13        | 0.99%   |
| 3266    | 12        | 0.91%   |
| 2933    | 12        | 0.91%   |
| 1067    | 12        | 0.91%   |
| 1066    | 12        | 0.91%   |
| 1866    | 9         | 0.68%   |
| 3400    | 8         | 0.61%   |
| 400     | 8         | 0.61%   |
| 4199    | 7         | 0.53%   |
| 2048    | 6         | 0.46%   |
| 1639    | 6         | 0.46%   |
| 8400    | 4         | 0.3%    |
| 2800    | 4         | 0.3%    |
| 49926   | 3         | 0.23%   |
| 3866    | 3         | 0.23%   |
| 2666    | 3         | 0.23%   |
| 533     | 3         | 0.23%   |
| 333     | 3         | 0.23%   |
| 4200    | 2         | 0.15%   |
| 3800    | 2         | 0.15%   |
| 3733    | 2         | 0.15%   |
| 3500    | 2         | 0.15%   |
| 3334    | 2         | 0.15%   |
| 3333    | 2         | 0.15%   |
| 1800    | 2         | 0.15%   |
| 31582   | 1         | 0.08%   |
| 4400    | 1         | 0.08%   |
| 4266    | 1         | 0.08%   |
| 4000    | 1         | 0.08%   |
| 3666    | 1         | 0.08%   |
| 3533    | 1         | 0.08%   |
| 2866    | 1         | 0.08%   |
| 2465    | 1         | 0.08%   |
| 2176    | 1         | 0.08%   |
| 2134    | 1         | 0.08%   |
| 1648    | 1         | 0.08%   |
| 1280    | 1         | 0.08%   |
| 975     | 1         | 0.08%   |
| 266     | 1         | 0.08%   |
| 33      | 1         | 0.08%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 19        | 28.79%  |
| Canon               | 13        | 19.7%   |
| Brother Industries  | 12        | 18.18%  |
| Samsung Electronics | 9         | 13.64%  |
| Seiko Epson         | 5         | 7.58%   |
| Dymo-CoStar         | 4         | 6.06%   |
| Citizen             | 3         | 4.55%   |
| Prolific Technology | 1         | 1.52%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| HP Deskjet 2540 series                                | 3         | 4.55%   |
| Dymo-CoStar LabelWriter 450                           | 3         | 4.55%   |
| Citizen Thermal Receipt Printer [CT-E351]             | 3         | 4.55%   |
| Samsung SCX-4600 Series                               | 2         | 3.03%   |
| Samsung ML-1640 Series Laser Printer                  | 2         | 3.03%   |
| HP DeskJet 2620 All-in-One Printer                    | 2         | 3.03%   |
| Canon TS3100 series                                   | 2         | 3.03%   |
| Canon PIXMA MX920 Series                              | 2         | 3.03%   |
| Canon PIXMA MG5600 Series                             | 2         | 3.03%   |
| Brother Printer                                       | 2         | 3.03%   |
| Brother HL-2030 Laser Printer                         | 2         | 3.03%   |
| Seiko Epson XP-202 203 206 Series                     | 1         | 1.52%   |
| Seiko Epson TM-T20                                    | 1         | 1.52%   |
| Seiko Epson Printer                                   | 1         | 1.52%   |
| Seiko Epson ET-2820 Series                            | 1         | 1.52%   |
| Seiko Epson ET-2720 Series                            | 1         | 1.52%   |
| Samsung SCX-4300 Series                               | 1         | 1.52%   |
| Samsung ML-2240 Series                                | 1         | 1.52%   |
| Samsung ML-216x Series Laser Printer                  | 1         | 1.52%   |
| Samsung C48x Series Color Laser Multifunction Printer | 1         | 1.52%   |
| Samsung C43x Series                                   | 1         | 1.52%   |
| Prolific PL2305 Parallel Port                         | 1         | 1.52%   |
| HP Printing Support                                   | 1         | 1.52%   |
| HP OfficeJet 6950                                     | 1         | 1.52%   |
| HP OfficeJet 3830 series                              | 1         | 1.52%   |
| HP LaserJet Professional P1102w                       | 1         | 1.52%   |
| HP LaserJet P1005                                     | 1         | 1.52%   |
| HP LaserJet 1320                                      | 1         | 1.52%   |
| HP ENVY 5000 series                                   | 1         | 1.52%   |
| HP DeskJet F2100 Printer series                       | 1         | 1.52%   |
| HP Deskjet D1500 series                               | 1         | 1.52%   |
| HP DeskJet 916C                                       | 1         | 1.52%   |
| HP DeskJet 6940 series                                | 1         | 1.52%   |
| HP DeskJet 3630 series                                | 1         | 1.52%   |
| HP DeskJet 2700 series                                | 1         | 1.52%   |
| HP designjet 30/130 series                            | 1         | 1.52%   |
| Dymo-CoStar LabelWriter 400                           | 1         | 1.52%   |
| Canon PIXMA MG2500 Series                             | 1         | 1.52%   |
| Canon MF4010 series                                   | 1         | 1.52%   |
| Canon LiDE 400                                        | 1         | 1.52%   |
| Canon LBP6680/3480 UFR II                             | 1         | 1.52%   |
| Canon iP7200 series                                   | 1         | 1.52%   |
| Canon iP4800 series                                   | 1         | 1.52%   |
| Canon iP2600 series                                   | 1         | 1.52%   |
| Brother MFC-L3770CDW series                           | 1         | 1.52%   |
| Brother MFC-J480DW                                    | 1         | 1.52%   |
| Brother HL-3140CW series                              | 1         | 1.52%   |
| Brother HL-2130 series                                | 1         | 1.52%   |
| Brother HL-1430 Laser Printer                         | 1         | 1.52%   |
| Brother HL-1210W series                               | 1         | 1.52%   |
| Brother DCP-L2560DW                                   | 1         | 1.52%   |
| Brother DCP-1510                                      | 1         | 1.52%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 20        | 64.52%  |
| Seiko Epson     | 6         | 19.35%  |
| Mustek Systems  | 2         | 6.45%   |
| Hewlett-Packard | 2         | 6.45%   |
| Plustek         | 1         | 3.23%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 220                       | 4         | 12.5%   |
| Canon CanoScan LiDE 210                       | 3         | 9.38%   |
| Seiko Epson Scanner                           | 2         | 6.25%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]   | 2         | 6.25%   |
| Seiko Epson GT-X770 [Perfection V500]         | 2         | 6.25%   |
| Mustek Systems ScanExpress 1200 UB            | 2         | 6.25%   |
| Canon CanoScan N650U/N656U                    | 2         | 6.25%   |
| Canon CanoScan LiDE 200                       | 2         | 6.25%   |
| Canon CanoScan LiDE 120                       | 2         | 6.25%   |
| Canon CanoScan LiDE 110                       | 2         | 6.25%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 1         | 3.13%   |
| Plustek 600dpi USB Scanner                    | 1         | 3.13%   |
| HP ScanJet 5590                               | 1         | 3.13%   |
| HP ScanJet 3300c                              | 1         | 3.13%   |
| Canon CanoScan N670U/N676U/LiDE 20            | 1         | 3.13%   |
| Canon CanoScan N1240U/LiDE 30                 | 1         | 3.13%   |
| Canon CanoScan FB630U                         | 1         | 3.13%   |
| Canon CanoScan 9000F Mark II                  | 1         | 3.13%   |
| Canon CanoScan 5600F                          | 1         | 3.13%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 362       | 23.28%  |
| Microdia                               | 155       | 9.97%   |
| Realtek Semiconductor                  | 127       | 8.17%   |
| IMC Networks                           | 122       | 7.85%   |
| Acer                                   | 109       | 7.01%   |
| Logitech                               | 108       | 6.95%   |
| Sunplus Innovation Technology          | 98        | 6.3%    |
| Cheng Uei Precision Industry (Foxlink) | 82        | 5.27%   |
| Apple                                  | 58        | 3.73%   |
| Suyin                                  | 54        | 3.47%   |
| Quanta                                 | 47        | 3.02%   |
| Lite-On Technology                     | 34        | 2.19%   |
| Syntek                                 | 19        | 1.22%   |
| Silicon Motion                         | 17        | 1.09%   |
| Samsung Electronics                    | 15        | 0.96%   |
| Ricoh                                  | 14        | 0.9%    |
| Lenovo                                 | 11        | 0.71%   |
| Microsoft                              | 10        | 0.64%   |
| Alcor Micro                            | 10        | 0.64%   |
| Primax Electronics                     | 9         | 0.58%   |
| Luxvisions Innotech Limited            | 8         | 0.51%   |
| Trust                                  | 7         | 0.45%   |
| Importek                               | 6         | 0.39%   |
| Generalplus Technology                 | 5         | 0.32%   |
| MacroSilicon                           | 4         | 0.26%   |
| Jieli Technology                       | 4         | 0.26%   |
| Creative Technology                    | 4         | 0.26%   |
| Z-Star Microelectronics                | 3         | 0.19%   |
| Sweex                                  | 3         | 0.19%   |
| ARC International                      | 3         | 0.19%   |
| Y Media                                | 2         | 0.13%   |
| Valve Software                         | 2         | 0.13%   |
| Tobii Technology AB                    | 2         | 0.13%   |
| Sonix Technology                       | 2         | 0.13%   |
| Pixart Imaging                         | 2         | 0.13%   |
| OmniVision Technologies                | 2         | 0.13%   |
| Genesys Logic                          | 2         | 0.13%   |
| DigiTech                               | 2         | 0.13%   |
| Cubeternet                             | 2         | 0.13%   |
| Alpha Imaging Technology               | 2         | 0.13%   |
| ALi                                    | 2         | 0.13%   |
| Xiongmai                               | 1         | 0.06%   |
| Xiaomi                                 | 1         | 0.06%   |
| ViewSonic                              | 1         | 0.06%   |
| USB Camera                             | 1         | 0.06%   |
| Unknown                                | 1         | 0.06%   |
| Teslong Camera                         | 1         | 0.06%   |
| SunplusIT                              | 1         | 0.06%   |
| Softkinetic                            | 1         | 0.06%   |
| Service & Quality Technology           | 1         | 0.06%   |
| Philips (or NXP)                       | 1         | 0.06%   |
| Novatel Wireless                       | 1         | 0.06%   |
| Novatek Microelectronics               | 1         | 0.06%   |
| Nikon                                  | 1         | 0.06%   |
| LG Electronics                         | 1         | 0.06%   |
| kingcome                               | 1         | 0.06%   |
| Intel                                  | 1         | 0.06%   |
| Huawei Technologies                    | 1         | 0.06%   |
| Holitech                               | 1         | 0.06%   |
| HHT                                    | 1         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                              | 81        | 5.13%   |
| Chicony Integrated Camera                                                  | 56        | 3.55%   |
| Realtek Integrated_Webcam_HD                                               | 52        | 3.29%   |
| Chicony HD WebCam                                                          | 48        | 3.04%   |
| IMC Networks Integrated Camera                                             | 42        | 2.66%   |
| Sunplus Integrated_Webcam_HD                                               | 37        | 2.34%   |
| Acer Integrated Camera                                                     | 26        | 1.65%   |
| Realtek Integrated_Webcam_5M                                               | 22        | 1.39%   |
| Logitech Webcam C270                                                       | 21        | 1.33%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 20        | 1.27%   |
| Chicony USB2.0 Camera                                                      | 19        | 1.2%    |
| Chicony HP HD Camera                                                       | 19        | 1.2%    |
| Apple Built-in iSight                                                      | 19        | 1.2%    |
| Logitech HD Pro Webcam C920                                                | 18        | 1.14%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 17        | 1.08%   |
| Chicony TOSHIBA Web Camera - HD                                            | 16        | 1.01%   |
| Samsung Galaxy A5 (MTP)                                                    | 15        | 0.95%   |
| Chicony HP Wide Vision HD Camera                                           | 15        | 0.95%   |
| Acer BisonCam,NB Pro                                                       | 15        | 0.95%   |
| Chicony USB 2.0 Camera                                                     | 14        | 0.89%   |
| Sunplus HD WebCam                                                          | 13        | 0.82%   |
| Logitech Webcam C310                                                       | 13        | 0.82%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 13        | 0.82%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 12        | 0.76%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                   | 11        | 0.7%    |
| Microdia Integrated Webcam                                                 | 11        | 0.7%    |
| Chicony USB2.0 HD UVC WebCam                                               | 11        | 0.7%    |
| Acer BisonCam, NB Pro                                                      | 11        | 0.7%    |
| Syntek Integrated Camera                                                   | 10        | 0.63%   |
| Logitech HD Webcam C525                                                    | 10        | 0.63%   |
| Lite-On Integrated Camera                                                  | 10        | 0.63%   |
| Lite-On HP HD Camera                                                       | 10        | 0.63%   |
| IMC Networks USB2.0 UVC HD Webcam                                          | 10        | 0.63%   |
| IMC Networks Integrated Webcam                                             | 10        | 0.63%   |
| Chicony Integrated HP HD Webcam                                            | 10        | 0.63%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                        | 10        | 0.63%   |
| Acer SunplusIT Integrated Camera                                           | 10        | 0.63%   |
| Microdia Sonix USB 2.0 Camera                                              | 9         | 0.57%   |
| Apple FaceTime HD Camera (Built-in)                                        | 9         | 0.57%   |
| Apple FaceTime HD Camera                                                   | 9         | 0.57%   |
| Quanta HP Wide Vision HD Camera                                            | 8         | 0.51%   |
| Microdia Integrated_Webcam_5M                                              | 8         | 0.51%   |
| Logitech C922 Pro Stream Webcam                                            | 8         | 0.51%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 8         | 0.51%   |
| Chicony Integrated Camera (1280x720@30)                                    | 8         | 0.51%   |
| Chicony FJ Camera                                                          | 8         | 0.51%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                           | 8         | 0.51%   |
| Acer HD Webcam                                                             | 8         | 0.51%   |
| Suyin HP Truevision HD                                                     | 7         | 0.44%   |
| Sunplus Laptop_Integrated_Webcam_HD                                        | 7         | 0.44%   |
| Sunplus HP HD Webcam [Fixed]                                               | 7         | 0.44%   |
| Realtek USB Camera                                                         | 7         | 0.44%   |
| Quanta HP HD Camera                                                        | 7         | 0.44%   |
| Primax HP HD Webcam [Fixed]                                                | 7         | 0.44%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 7         | 0.44%   |
| Chicony HP HD Webcam                                                       | 7         | 0.44%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD                    | 7         | 0.44%   |
| Acer ThinkPad Integrated Camera                                            | 7         | 0.44%   |
| Acer EasyCamera                                                            | 7         | 0.44%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                       | 6         | 0.38%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 115       | 33.82%  |
| Synaptics                  | 106       | 31.18%  |
| Shenzhen Goodix Technology | 40        | 11.76%  |
| AuthenTec                  | 28        | 8.24%   |
| Upek                       | 16        | 4.71%   |
| Elan Microelectronics      | 16        | 4.71%   |
| LighTuning Technology      | 15        | 4.41%   |
| STMicroelectronics         | 3         | 0.88%   |
| Samsung Electronics        | 1         | 0.29%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                    | 38        | 11.18%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 37        | 10.88%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 33        | 9.71%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 16        | 4.71%   |
| Shenzhen Goodix FingerPrint                                                | 15        | 4.41%   |
| Shenzhen Goodix  Fingerprint Device                                        | 14        | 4.12%   |
| Validity Sensors VFS491                                                    | 12        | 3.53%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 12        | 3.53%   |
| Shenzhen Goodix Fingerprint Reader                                         | 11        | 3.24%   |
| Elan ELAN:Fingerprint                                                      | 11        | 3.24%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 10        | 2.94%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 10        | 2.94%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 10        | 2.94%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 9         | 2.65%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 9         | 2.65%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 8         | 2.35%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 8         | 2.35%   |
| AuthenTec AES2810                                                          | 8         | 2.35%   |
| Synaptics  WBDI                                                            | 7         | 2.06%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 6         | 1.76%   |
| Validity Sensors Fingerprint scanner                                       | 5         | 1.47%   |
| Elan ELAN:ARM-M4                                                           | 5         | 1.47%   |
| AuthenTec AES1600                                                          | 5         | 1.47%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 1.18%   |
| Validity Sensors Synaptics WBDI                                            | 4         | 1.18%   |
| Synaptics WBDI Device                                                      | 4         | 1.18%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 4         | 1.18%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 3         | 0.88%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 0.88%   |
| STMicroelectronics Fingerprint Reader                                      | 3         | 0.88%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 0.88%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 0.59%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 0.59%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.59%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 2         | 0.59%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.29%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.29%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.29%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.29%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 0.29%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 76        | 51.35%  |
| Alcor Micro                       | 34        | 22.97%  |
| O2 Micro                          | 22        | 14.86%  |
| Lenovo                            | 6         | 4.05%   |
| Upek                              | 5         | 3.38%   |
| VASCO Data Security International | 1         | 0.68%   |
| SCM Microsystems                  | 1         | 0.68%   |
| Clay Logic                        | 1         | 0.68%   |
| Chicony Electronics               | 1         | 0.68%   |
| Advanced Card Systems             | 1         | 0.68%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 34        | 22.97%  |
| Broadcom BCM5880 Secure Applications Processor                               | 25        | 16.89%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 20        | 13.51%  |
| Broadcom 58200                                                               | 18        | 12.16%  |
| Broadcom 5880                                                                | 17        | 11.49%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 16        | 10.81%  |
| Lenovo Integrated Smart Card Reader                                          | 6         | 4.05%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 3.38%   |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 1.35%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.68%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.68%   |
| Clay Logic Nitrokey HSM                                                      | 1         | 0.68%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.68%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.68%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1916      | 69.57%  |
| 1     | 653       | 23.71%  |
| 2     | 146       | 5.3%    |
| 3     | 25        | 0.91%   |
| 4     | 8         | 0.29%   |
| 5     | 4         | 0.15%   |
| 6     | 2         | 0.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 336       | 32.31%  |
| Graphics card            | 200       | 19.23%  |
| Chipcard                 | 132       | 12.69%  |
| Net/wireless             | 97        | 9.33%   |
| Multimedia controller    | 83        | 7.98%   |
| Communication controller | 41        | 3.94%   |
| Camera                   | 24        | 2.31%   |
| Bluetooth                | 20        | 1.92%   |
| Unassigned class         | 19        | 1.83%   |
| Sound                    | 17        | 1.63%   |
| Storage                  | 16        | 1.54%   |
| Network                  | 11        | 1.06%   |
| Net/ethernet             | 11        | 1.06%   |
| Card reader              | 11        | 1.06%   |
| Flash memory             | 7         | 0.67%   |
| Storage/ide              | 4         | 0.38%   |
| Storage/ata              | 4         | 0.38%   |
| Tv card                  | 2         | 0.19%   |
| Storage/nvme             | 2         | 0.19%   |
| Modem                    | 1         | 0.1%    |
| Firewire controller      | 1         | 0.1%    |
| Dvb card                 | 1         | 0.1%    |

