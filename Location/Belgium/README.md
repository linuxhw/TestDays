Linux in Belgium - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Belgium.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Belgium/Desktop/README.md) and [notebooks](/Location/Belgium/Notebook/README.md).

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

Total: 2354

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [cccf492c06](https://linux-hardware.org/?probe=cccf492c06) | Dec 01, 2022 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [4c7e1d5bc4](https://linux-hardware.org/?probe=4c7e1d5bc4) | Dec 01, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [3a64631617](https://linux-hardware.org/?probe=3a64631617) | Nov 30, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [12492cb99a](https://linux-hardware.org/?probe=12492cb99a) | Nov 29, 2022 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [bb49870780](https://linux-hardware.org/?probe=bb49870780) | Nov 28, 2022 |
| MSI           | MEG Z490 UNIFY              | Desktop     | [b6af703e1a](https://linux-hardware.org/?probe=b6af703e1a) | Nov 28, 2022 |
| Dell          | G3 3779                     | Notebook    | [1cf1d8aa20](https://linux-hardware.org/?probe=1cf1d8aa20) | Nov 26, 2022 |
| Dell          | G3 3779                     | Notebook    | [4bc02c1721](https://linux-hardware.org/?probe=4bc02c1721) | Nov 26, 2022 |
| Lenovo        | MIIX 2 11 20327             | Tablet      | [2eb5cc0a12](https://linux-hardware.org/?probe=2eb5cc0a12) | Nov 25, 2022 |
| Lenovo        | MIIX 2 11 20327             | Tablet      | [c0102f2633](https://linux-hardware.org/?probe=c0102f2633) | Nov 25, 2022 |
| Acer          | NC-ES1-512-C3AH             | Notebook    | [0670f9ed15](https://linux-hardware.org/?probe=0670f9ed15) | Nov 25, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [62e12083b5](https://linux-hardware.org/?probe=62e12083b5) | Nov 23, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [9ed3a001c9](https://linux-hardware.org/?probe=9ed3a001c9) | Nov 23, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [495d972ae3](https://linux-hardware.org/?probe=495d972ae3) | Nov 23, 2022 |
| MSI           | Z87-G45 GAMING              | Desktop     | [66383ce902](https://linux-hardware.org/?probe=66383ce902) | Nov 22, 2022 |
| ASRock        | H81M-DGS R2.0               | Desktop     | [0354f9cb0e](https://linux-hardware.org/?probe=0354f9cb0e) | Nov 21, 2022 |
| Acer          | MCP73VE NVIDIA MCP73        | Desktop     | [c6b206401a](https://linux-hardware.org/?probe=c6b206401a) | Nov 21, 2022 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [d7ee80553a](https://linux-hardware.org/?probe=d7ee80553a) | Nov 20, 2022 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [f55a45b87f](https://linux-hardware.org/?probe=f55a45b87f) | Nov 20, 2022 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [e3d6c78ed4](https://linux-hardware.org/?probe=e3d6c78ed4) | Nov 20, 2022 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [dfd1c98a18](https://linux-hardware.org/?probe=dfd1c98a18) | Nov 20, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [de8b7d8220](https://linux-hardware.org/?probe=de8b7d8220) | Nov 19, 2022 |
| HP            | Pavilion dv6                | Notebook    | [a7ca712256](https://linux-hardware.org/?probe=a7ca712256) | Nov 19, 2022 |
| HP            | Pavilion dv6                | Notebook    | [571dc553f9](https://linux-hardware.org/?probe=571dc553f9) | Nov 19, 2022 |
| Intel         | NUC11DBBi7 M17027-403       | Mini pc     | [d0d37dd251](https://linux-hardware.org/?probe=d0d37dd251) | Nov 17, 2022 |
| Dell          | Latitude 5530               | Notebook    | [35a6ba0a9f](https://linux-hardware.org/?probe=35a6ba0a9f) | Nov 17, 2022 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [7c8d905b3d](https://linux-hardware.org/?probe=7c8d905b3d) | Nov 17, 2022 |
| Dell          | Precision 7560              | Notebook    | [0ee8814502](https://linux-hardware.org/?probe=0ee8814502) | Nov 16, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [5d11a28230](https://linux-hardware.org/?probe=5d11a28230) | Nov 16, 2022 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [c9876aa0fd](https://linux-hardware.org/?probe=c9876aa0fd) | Nov 16, 2022 |
| ASRock        | H81M-DGS R2.0               | Desktop     | [f56f2c6a53](https://linux-hardware.org/?probe=f56f2c6a53) | Nov 14, 2022 |
| ASRock        | B660M-HDV                   | Desktop     | [eeaa5c82ea](https://linux-hardware.org/?probe=eeaa5c82ea) | Nov 13, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [9ef06fcef1](https://linux-hardware.org/?probe=9ef06fcef1) | Nov 13, 2022 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [94e5dec391](https://linux-hardware.org/?probe=94e5dec391) | Nov 12, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [022a97b52e](https://linux-hardware.org/?probe=022a97b52e) | Nov 11, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [3f11ca7016](https://linux-hardware.org/?probe=3f11ca7016) | Nov 11, 2022 |
| Lenovo        | 36DC SDK0J40709 WIN 3259... | All in one  | [929685d936](https://linux-hardware.org/?probe=929685d936) | Nov 11, 2022 |
| ASRock        | H81M-DGS R2.0               | Desktop     | [07bae444fc](https://linux-hardware.org/?probe=07bae444fc) | Nov 11, 2022 |
| HP            | EliteBook 850 G5            | Notebook    | [331a1db69d](https://linux-hardware.org/?probe=331a1db69d) | Nov 11, 2022 |
| HP            | Pavilion 15                 | Notebook    | [d703e1c63c](https://linux-hardware.org/?probe=d703e1c63c) | Nov 10, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [6d00ba40be](https://linux-hardware.org/?probe=6d00ba40be) | Nov 10, 2022 |
| Acer          | Aspire 1825PTZ              | Notebook    | [c2dc801a81](https://linux-hardware.org/?probe=c2dc801a81) | Nov 09, 2022 |
| ASUSTek       | P5E-VM SE                   | Desktop     | [a41a51330d](https://linux-hardware.org/?probe=a41a51330d) | Nov 08, 2022 |
| Acer          | Aspire 7741                 | Notebook    | [9fda4c3798](https://linux-hardware.org/?probe=9fda4c3798) | Nov 08, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [e9389bc87e](https://linux-hardware.org/?probe=e9389bc87e) | Nov 08, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [25756ad3c1](https://linux-hardware.org/?probe=25756ad3c1) | Nov 07, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [5505ec9b09](https://linux-hardware.org/?probe=5505ec9b09) | Nov 06, 2022 |
| HP            | Pavilion 17                 | Notebook    | [958de69d5b](https://linux-hardware.org/?probe=958de69d5b) | Nov 06, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [47dda70950](https://linux-hardware.org/?probe=47dda70950) | Nov 06, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [5a2028bd2d](https://linux-hardware.org/?probe=5a2028bd2d) | Nov 05, 2022 |
| HP            | Pavilion 17                 | Notebook    | [9dd715b48e](https://linux-hardware.org/?probe=9dd715b48e) | Nov 05, 2022 |
| Gigabyte      | B450M GAMING-CF             | Desktop     | [4e35f6b15e](https://linux-hardware.org/?probe=4e35f6b15e) | Nov 05, 2022 |
| ASUSTek       | K56CM                       | Notebook    | [c93289dc28](https://linux-hardware.org/?probe=c93289dc28) | Nov 05, 2022 |
| TUXEDO        | Aura 15 Gen2                | Notebook    | [681d0b959b](https://linux-hardware.org/?probe=681d0b959b) | Nov 05, 2022 |
| Dell          | 0M863N A00                  | Desktop     | [3e390c5fb3](https://linux-hardware.org/?probe=3e390c5fb3) | Nov 04, 2022 |
| Gigabyte      | B450M GAMING-CF             | Desktop     | [0f4bdc1677](https://linux-hardware.org/?probe=0f4bdc1677) | Nov 04, 2022 |
| ASUSTek       | GL703VD                     | Notebook    | [3e8fbc43d7](https://linux-hardware.org/?probe=3e8fbc43d7) | Nov 04, 2022 |
| Gigabyte      | B450M GAMING-CF             | Desktop     | [ff19454b61](https://linux-hardware.org/?probe=ff19454b61) | Nov 04, 2022 |
| ASUSTek       | PRIME Z690-A                | Desktop     | [e7254fb467](https://linux-hardware.org/?probe=e7254fb467) | Nov 04, 2022 |
| Intel         | NUC6i7KYB H90766-408        | Mini pc     | [2069a0e7fc](https://linux-hardware.org/?probe=2069a0e7fc) | Nov 02, 2022 |
| Dell          | Latitude 5580               | Notebook    | [92545fb976](https://linux-hardware.org/?probe=92545fb976) | Nov 02, 2022 |
| Dell          | Precision 7550              | Notebook    | [2065f4ab5f](https://linux-hardware.org/?probe=2065f4ab5f) | Nov 02, 2022 |
| Gigabyte      | B450M GAMING-CF             | Desktop     | [95e2a1e7d9](https://linux-hardware.org/?probe=95e2a1e7d9) | Nov 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [63bf11c696](https://linux-hardware.org/?probe=63bf11c696) | Nov 02, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [034414a73e](https://linux-hardware.org/?probe=034414a73e) | Nov 01, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [6f635f46c6](https://linux-hardware.org/?probe=6f635f46c6) | Nov 01, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [0424e08b3d](https://linux-hardware.org/?probe=0424e08b3d) | Oct 31, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [f497e98b58](https://linux-hardware.org/?probe=f497e98b58) | Oct 31, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [80f6da5216](https://linux-hardware.org/?probe=80f6da5216) | Oct 31, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [cfe35367bf](https://linux-hardware.org/?probe=cfe35367bf) | Oct 30, 2022 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [81ccab7297](https://linux-hardware.org/?probe=81ccab7297) | Oct 29, 2022 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [4eff9900f2](https://linux-hardware.org/?probe=4eff9900f2) | Oct 28, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [6cfd4bdb14](https://linux-hardware.org/?probe=6cfd4bdb14) | Oct 28, 2022 |
| PC Special... | Recoil II                   | Notebook    | [9ec5a6ef20](https://linux-hardware.org/?probe=9ec5a6ef20) | Oct 27, 2022 |
| PC Special... | Recoil II                   | Notebook    | [38ec5a7708](https://linux-hardware.org/?probe=38ec5a7708) | Oct 27, 2022 |
| MSI           | MS-AE611 100                | All in one  | [7527f4a200](https://linux-hardware.org/?probe=7527f4a200) | Oct 27, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | Notebook    | [0763832411](https://linux-hardware.org/?probe=0763832411) | Oct 27, 2022 |
| MSI           | MS-AE611 100                | All in one  | [1f6fc12b09](https://linux-hardware.org/?probe=1f6fc12b09) | Oct 25, 2022 |
| Gigabyte      | 965P-DS3                    | Desktop     | [18dad8d151](https://linux-hardware.org/?probe=18dad8d151) | Oct 25, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [76fa0d836f](https://linux-hardware.org/?probe=76fa0d836f) | Oct 25, 2022 |
| Lenovo        | 0x36C017AA SDK0J40700 WI... | Desktop     | [0d21d658ee](https://linux-hardware.org/?probe=0d21d658ee) | Oct 24, 2022 |
| TUXEDO        | Pulse 14 Gen1               | Notebook    | [0e12d15b78](https://linux-hardware.org/?probe=0e12d15b78) | Oct 24, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [8b0377a420](https://linux-hardware.org/?probe=8b0377a420) | Oct 24, 2022 |
| Medion        | B460H6-EM                   | Desktop     | [9023ea833f](https://linux-hardware.org/?probe=9023ea833f) | Oct 24, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [f82a2d8d8e](https://linux-hardware.org/?probe=f82a2d8d8e) | Oct 23, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [25295c680c](https://linux-hardware.org/?probe=25295c680c) | Oct 23, 2022 |
| ASUSTek       | P9X79 WS                    | Desktop     | [86f91e4898](https://linux-hardware.org/?probe=86f91e4898) | Oct 23, 2022 |
| Acer          | Aspire E5-521               | Notebook    | [a7bffc7d13](https://linux-hardware.org/?probe=a7bffc7d13) | Oct 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [39c064d0df](https://linux-hardware.org/?probe=39c064d0df) | Oct 22, 2022 |
| ASUSTek       | H170M-PLUS                  | Desktop     | [e34cb7ea31](https://linux-hardware.org/?probe=e34cb7ea31) | Oct 20, 2022 |
| Lenovo        | ThinkPad E590 20NB002BMB    | Notebook    | [4b272ef951](https://linux-hardware.org/?probe=4b272ef951) | Oct 20, 2022 |
| TUXEDO        | Aura 15 Gen2                | Notebook    | [f5d5e3fb86](https://linux-hardware.org/?probe=f5d5e3fb86) | Oct 19, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [aa8a459961](https://linux-hardware.org/?probe=aa8a459961) | Oct 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | Notebook    | [d51ba4a008](https://linux-hardware.org/?probe=d51ba4a008) | Oct 18, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [70d12e710f](https://linux-hardware.org/?probe=70d12e710f) | Oct 18, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [9d471dbf37](https://linux-hardware.org/?probe=9d471dbf37) | Oct 18, 2022 |
| MSI           | GE70 2PE                    | Notebook    | [ff621f681e](https://linux-hardware.org/?probe=ff621f681e) | Oct 17, 2022 |
| Medion        | B250H4-EM                   | Desktop     | [f6c1e8e061](https://linux-hardware.org/?probe=f6c1e8e061) | Oct 17, 2022 |
| Dell          | Latitude 3380               | Notebook    | [901d7614e5](https://linux-hardware.org/?probe=901d7614e5) | Oct 17, 2022 |
| Shuttle       | FS81                        | Desktop     | [61c0ca02f3](https://linux-hardware.org/?probe=61c0ca02f3) | Oct 16, 2022 |
| ASUSTek       | GD30CI                      | Desktop     | [e002a9ef5c](https://linux-hardware.org/?probe=e002a9ef5c) | Oct 16, 2022 |
| HP            | ProBook 450 G6              | Notebook    | [fda3302752](https://linux-hardware.org/?probe=fda3302752) | Oct 16, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [76f457f2aa](https://linux-hardware.org/?probe=76f457f2aa) | Oct 16, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [c22c1df016](https://linux-hardware.org/?probe=c22c1df016) | Oct 15, 2022 |
| Dell          | 0M863N A00                  | Desktop     | [870d58dd75](https://linux-hardware.org/?probe=870d58dd75) | Oct 15, 2022 |
| Dell          | 0M863N A00                  | Desktop     | [27e1ded122](https://linux-hardware.org/?probe=27e1ded122) | Oct 15, 2022 |
| ASUSTek       | P5GC-MX                     | Desktop     | [73f8df6ec6](https://linux-hardware.org/?probe=73f8df6ec6) | Oct 14, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [89b3dc8edd](https://linux-hardware.org/?probe=89b3dc8edd) | Oct 14, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [0bc0bf85be](https://linux-hardware.org/?probe=0bc0bf85be) | Oct 14, 2022 |
| Dell          | Latitude E6330              | Notebook    | [1b1f5a27f7](https://linux-hardware.org/?probe=1b1f5a27f7) | Oct 14, 2022 |
| Dell          | Precision M3800             | Notebook    | [96ea6a1a31](https://linux-hardware.org/?probe=96ea6a1a31) | Oct 13, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [20eebb7b05](https://linux-hardware.org/?probe=20eebb7b05) | Oct 12, 2022 |
| Notebook      | NS5x_NS7xPU                 | Notebook    | [b35f6c63de](https://linux-hardware.org/?probe=b35f6c63de) | Oct 12, 2022 |
| Dell          | Latitude 5530               | Notebook    | [9453558076](https://linux-hardware.org/?probe=9453558076) | Oct 12, 2022 |
| ASUSTek       | X756UVK                     | Notebook    | [8d2e9a5e1e](https://linux-hardware.org/?probe=8d2e9a5e1e) | Oct 12, 2022 |
| HP            | 82A5                        | Mini pc     | [5a8ea35493](https://linux-hardware.org/?probe=5a8ea35493) | Oct 11, 2022 |
| Lenovo        | ThinkPad L450 20DTCTO1WW    | Notebook    | [2209173803](https://linux-hardware.org/?probe=2209173803) | Oct 10, 2022 |
| Lenovo        | ThinkPad L520 5017AL3       | Notebook    | [2e43bb8a31](https://linux-hardware.org/?probe=2e43bb8a31) | Oct 10, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [b26ceb2206](https://linux-hardware.org/?probe=b26ceb2206) | Oct 10, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [bc86477fff](https://linux-hardware.org/?probe=bc86477fff) | Oct 09, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [24d18c0f7f](https://linux-hardware.org/?probe=24d18c0f7f) | Oct 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [1c71987bd5](https://linux-hardware.org/?probe=1c71987bd5) | Oct 08, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [1798b09b89](https://linux-hardware.org/?probe=1798b09b89) | Oct 08, 2022 |
| HP            | EliteBook 745 G6            | Notebook    | [b1ff49ff0f](https://linux-hardware.org/?probe=b1ff49ff0f) | Oct 07, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [cc955e89b7](https://linux-hardware.org/?probe=cc955e89b7) | Oct 07, 2022 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [8b0ed3f04c](https://linux-hardware.org/?probe=8b0ed3f04c) | Oct 06, 2022 |
| ASUSTek       | PRIME B365M-K               | Desktop     | [b419239d57](https://linux-hardware.org/?probe=b419239d57) | Oct 06, 2022 |
| Gigabyte      | Spring Peak                 | Notebook    | [45794008e2](https://linux-hardware.org/?probe=45794008e2) | Oct 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [36ad4bb59b](https://linux-hardware.org/?probe=36ad4bb59b) | Oct 06, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [03dc83a686](https://linux-hardware.org/?probe=03dc83a686) | Oct 05, 2022 |
| ASUSTek       | X756UQ                      | Notebook    | [e17cbbf886](https://linux-hardware.org/?probe=e17cbbf886) | Oct 03, 2022 |
| ASUSTek       | X756UQ                      | Notebook    | [5767aaf6db](https://linux-hardware.org/?probe=5767aaf6db) | Oct 03, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [bce5ab0354](https://linux-hardware.org/?probe=bce5ab0354) | Oct 02, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [b8d65ced41](https://linux-hardware.org/?probe=b8d65ced41) | Oct 02, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [b5b057439d](https://linux-hardware.org/?probe=b5b057439d) | Oct 02, 2022 |
| Notebook      | W330SU2                     | Notebook    | [a5d5500584](https://linux-hardware.org/?probe=a5d5500584) | Oct 01, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [541e327f0f](https://linux-hardware.org/?probe=541e327f0f) | Oct 01, 2022 |
| Dell          | Latitude 5530               | Notebook    | [43874dad6d](https://linux-hardware.org/?probe=43874dad6d) | Sep 30, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [02c5cd53e9](https://linux-hardware.org/?probe=02c5cd53e9) | Sep 30, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d658b9dcbe](https://linux-hardware.org/?probe=d658b9dcbe) | Sep 30, 2022 |
| Lenovo        | ThinkPad X260 20F5S6P801    | Notebook    | [e948792d3d](https://linux-hardware.org/?probe=e948792d3d) | Sep 30, 2022 |
| TUXEDO        | Aura 15 Gen2                | Notebook    | [e8ebe97f13](https://linux-hardware.org/?probe=e8ebe97f13) | Sep 30, 2022 |
| Acer          | Aspire VX5-591G             | Notebook    | [b321f4561b](https://linux-hardware.org/?probe=b321f4561b) | Sep 29, 2022 |
| HP            | EliteBook 6930p             | Notebook    | [56e5d25094](https://linux-hardware.org/?probe=56e5d25094) | Sep 29, 2022 |
| Lenovo        | ThinkPad E590 20NB002AMB    | Notebook    | [0c8a6ce686](https://linux-hardware.org/?probe=0c8a6ce686) | Sep 29, 2022 |
| Razer         | Blade                       | Notebook    | [63a4e5f829](https://linux-hardware.org/?probe=63a4e5f829) | Sep 29, 2022 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [81ddb430e3](https://linux-hardware.org/?probe=81ddb430e3) | Sep 28, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | Desktop     | [757d465447](https://linux-hardware.org/?probe=757d465447) | Sep 27, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [70f86aa587](https://linux-hardware.org/?probe=70f86aa587) | Sep 27, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [8ee663c695](https://linux-hardware.org/?probe=8ee663c695) | Sep 26, 2022 |
| Intel         | NUC5i3RYB H41000-502        | Mini pc     | [d09f4c4501](https://linux-hardware.org/?probe=d09f4c4501) | Sep 25, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [36a7fc8903](https://linux-hardware.org/?probe=36a7fc8903) | Sep 24, 2022 |
| Raspberry ... | Raspberry Pi Zero 2 W Re... | Soc         | [3d7933270a](https://linux-hardware.org/?probe=3d7933270a) | Sep 22, 2022 |
| Raspberry ... | Raspberry Pi Zero 2 W Re... | Soc         | [1e6b1b068a](https://linux-hardware.org/?probe=1e6b1b068a) | Sep 22, 2022 |
| Raspberry ... | Raspberry Pi Zero 2 W Re... | Soc         | [a978086f1b](https://linux-hardware.org/?probe=a978086f1b) | Sep 22, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [3b1de255e3](https://linux-hardware.org/?probe=3b1de255e3) | Sep 22, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [dc49b2baf4](https://linux-hardware.org/?probe=dc49b2baf4) | Sep 21, 2022 |
| Lenovo        | B570e 476025G               | Notebook    | [ab67a90ba7](https://linux-hardware.org/?probe=ab67a90ba7) | Sep 20, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [153aed4d7c](https://linux-hardware.org/?probe=153aed4d7c) | Sep 19, 2022 |
| Intel         | NUC6i7KYB H90766-408        | Mini pc     | [e728637650](https://linux-hardware.org/?probe=e728637650) | Sep 19, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [de718ac983](https://linux-hardware.org/?probe=de718ac983) | Sep 19, 2022 |
| MSI           | Z77A-G43                    | Desktop     | [4b91f7a270](https://linux-hardware.org/?probe=4b91f7a270) | Sep 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [3da12828c0](https://linux-hardware.org/?probe=3da12828c0) | Sep 19, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [798bb8eda6](https://linux-hardware.org/?probe=798bb8eda6) | Sep 18, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [24534d00db](https://linux-hardware.org/?probe=24534d00db) | Sep 17, 2022 |
| Dell          | Latitude 5520               | Notebook    | [3e023f86c9](https://linux-hardware.org/?probe=3e023f86c9) | Sep 17, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [90871c217b](https://linux-hardware.org/?probe=90871c217b) | Sep 17, 2022 |
| ASUSTek       | UX32VD                      | Notebook    | [324cafa8d2](https://linux-hardware.org/?probe=324cafa8d2) | Sep 17, 2022 |
| Dell          | Precision 7720              | Notebook    | [9658507a0b](https://linux-hardware.org/?probe=9658507a0b) | Sep 17, 2022 |
| Acer          | Aspire XC-705               | Desktop     | [b8e79c9c77](https://linux-hardware.org/?probe=b8e79c9c77) | Sep 16, 2022 |
| Acer          | Aspire XC-705               | Desktop     | [2600793890](https://linux-hardware.org/?probe=2600793890) | Sep 15, 2022 |
| Medion        | MS-7857                     | Desktop     | [98a978898c](https://linux-hardware.org/?probe=98a978898c) | Sep 14, 2022 |
| Medion        | MS-7857                     | Desktop     | [54237e3276](https://linux-hardware.org/?probe=54237e3276) | Sep 14, 2022 |
| Acer          | Aspire 7551                 | Notebook    | [916aa5cc5d](https://linux-hardware.org/?probe=916aa5cc5d) | Sep 14, 2022 |
| Acer          | Aspire 7551                 | Notebook    | [3f97043d7a](https://linux-hardware.org/?probe=3f97043d7a) | Sep 14, 2022 |
| ASUSTek       | P5K-E                       | Desktop     | [ddac4b0175](https://linux-hardware.org/?probe=ddac4b0175) | Sep 13, 2022 |
| Sony          | SVE1712L1EW                 | Notebook    | [18400c7a0d](https://linux-hardware.org/?probe=18400c7a0d) | Sep 13, 2022 |
| Gigabyte      | Z77-D3H                     | Desktop     | [b1b929517d](https://linux-hardware.org/?probe=b1b929517d) | Sep 13, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [f062dd3ff8](https://linux-hardware.org/?probe=f062dd3ff8) | Sep 12, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [864a5abac7](https://linux-hardware.org/?probe=864a5abac7) | Sep 12, 2022 |
| ASUSTek       | UX32VD                      | Notebook    | [6a6e7e4207](https://linux-hardware.org/?probe=6a6e7e4207) | Sep 12, 2022 |
| HP            | 158B                        | Desktop     | [ba2366e9ad](https://linux-hardware.org/?probe=ba2366e9ad) | Sep 12, 2022 |
| Sony          | SVE1712L1EW                 | Notebook    | [6a797dc1cf](https://linux-hardware.org/?probe=6a797dc1cf) | Sep 12, 2022 |
| Hampoo        | Cherry Trail CR Hampoo_r... | Notebook    | [8d76919c1a](https://linux-hardware.org/?probe=8d76919c1a) | Sep 11, 2022 |
| Gigabyte      | GB-BRR7H-4800               | Desktop     | [c7eb1fd4ca](https://linux-hardware.org/?probe=c7eb1fd4ca) | Sep 11, 2022 |
| MSI           | Z77A-G43                    | Desktop     | [d0e5863756](https://linux-hardware.org/?probe=d0e5863756) | Sep 10, 2022 |
| Gigabyte      | GB-BRR7H-4800               | Desktop     | [5fb806b2c8](https://linux-hardware.org/?probe=5fb806b2c8) | Sep 10, 2022 |
| Sony          | SVE14A2V1EW                 | Notebook    | [5123cfd3cd](https://linux-hardware.org/?probe=5123cfd3cd) | Sep 09, 2022 |
| Medion        | B250H4-EM                   | Desktop     | [857e841fb7](https://linux-hardware.org/?probe=857e841fb7) | Sep 09, 2022 |
| Medion        | Akoya E1318T                | Notebook    | [749a12fd63](https://linux-hardware.org/?probe=749a12fd63) | Sep 09, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [603514ef84](https://linux-hardware.org/?probe=603514ef84) | Sep 09, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [90908282f2](https://linux-hardware.org/?probe=90908282f2) | Sep 07, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [f0ce37ab5a](https://linux-hardware.org/?probe=f0ce37ab5a) | Sep 06, 2022 |
| Panasonic     | CF-D1DVA06F3                | Notebook    | [e3cc43135a](https://linux-hardware.org/?probe=e3cc43135a) | Sep 05, 2022 |
| ASUSTek       | P6X58D-E                    | Desktop     | [cf774b3e03](https://linux-hardware.org/?probe=cf774b3e03) | Sep 02, 2022 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [143e6e1816](https://linux-hardware.org/?probe=143e6e1816) | Sep 01, 2022 |
| Gigabyte      | Z97-HD3                     | Desktop     | [32e71c2905](https://linux-hardware.org/?probe=32e71c2905) | Sep 01, 2022 |
| Notebook      | NL40_50CU                   | Notebook    | [af0da080ec](https://linux-hardware.org/?probe=af0da080ec) | Sep 01, 2022 |
| Medion        | H110H4-EM                   | Desktop     | [9f80ee3a09](https://linux-hardware.org/?probe=9f80ee3a09) | Sep 01, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [1f8274de5a](https://linux-hardware.org/?probe=1f8274de5a) | Aug 31, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [567bf4b44a](https://linux-hardware.org/?probe=567bf4b44a) | Aug 31, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [71cd60f1b9](https://linux-hardware.org/?probe=71cd60f1b9) | Aug 30, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [748558225a](https://linux-hardware.org/?probe=748558225a) | Aug 30, 2022 |
| Intel         | NUC6i7KYB H90766-408        | Mini pc     | [14f4c7e248](https://linux-hardware.org/?probe=14f4c7e248) | Aug 29, 2022 |
| Lenovo        | ThinkPad P1 20MDS0FC00      | Notebook    | [dcdde00f17](https://linux-hardware.org/?probe=dcdde00f17) | Aug 29, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [3a448c33f9](https://linux-hardware.org/?probe=3a448c33f9) | Aug 28, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [4210c6a219](https://linux-hardware.org/?probe=4210c6a219) | Aug 28, 2022 |
| Packard Be... | EasyNote_MX37-U-017         | Notebook    | [abc3dbdaec](https://linux-hardware.org/?probe=abc3dbdaec) | Aug 28, 2022 |
| HP            | ENVY Laptop 13-aq1xxx       | Notebook    | [095ecf5f87](https://linux-hardware.org/?probe=095ecf5f87) | Aug 25, 2022 |
| Dell          | Latitude 5511               | Notebook    | [22c835a93a](https://linux-hardware.org/?probe=22c835a93a) | Aug 25, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [413cc5a3c3](https://linux-hardware.org/?probe=413cc5a3c3) | Aug 24, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [fdc1bb0c75](https://linux-hardware.org/?probe=fdc1bb0c75) | Aug 23, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [fca17b512f](https://linux-hardware.org/?probe=fca17b512f) | Aug 23, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [b3fcba32bd](https://linux-hardware.org/?probe=b3fcba32bd) | Aug 22, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [5dabf74b7f](https://linux-hardware.org/?probe=5dabf74b7f) | Aug 21, 2022 |
| Dell          | Vostro 3360                 | Notebook    | [0964195fe5](https://linux-hardware.org/?probe=0964195fe5) | Aug 21, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [47b1480e61](https://linux-hardware.org/?probe=47b1480e61) | Aug 20, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [d1fb1214f6](https://linux-hardware.org/?probe=d1fb1214f6) | Aug 20, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [fc1a1cd41f](https://linux-hardware.org/?probe=fc1a1cd41f) | Aug 20, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [7dbac78a87](https://linux-hardware.org/?probe=7dbac78a87) | Aug 20, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [abbb1d7360](https://linux-hardware.org/?probe=abbb1d7360) | Aug 20, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [c3e335499f](https://linux-hardware.org/?probe=c3e335499f) | Aug 20, 2022 |
| HP            | EliteBook 8540p             | Notebook    | [cdd3dd9925](https://linux-hardware.org/?probe=cdd3dd9925) | Aug 19, 2022 |
| MSI           | MS-AE611 100                | All in one  | [336e0dfd12](https://linux-hardware.org/?probe=336e0dfd12) | Aug 18, 2022 |
| ASUSTek       | X756UQ                      | Notebook    | [9b30268acb](https://linux-hardware.org/?probe=9b30268acb) | Aug 17, 2022 |
| HP            | 872B                        | Desktop     | [466f4962fe](https://linux-hardware.org/?probe=466f4962fe) | Aug 17, 2022 |
| ASUSTek       | PRIME B365M-K               | Desktop     | [bd808084a5](https://linux-hardware.org/?probe=bd808084a5) | Aug 16, 2022 |
| ASRock        | Z77 Extreme4                | Desktop     | [07e825ed5b](https://linux-hardware.org/?probe=07e825ed5b) | Aug 16, 2022 |
| HP            | 2AB6                        | Desktop     | [bf0c915ea8](https://linux-hardware.org/?probe=bf0c915ea8) | Aug 15, 2022 |
| HP            | 2AB6                        | Desktop     | [2fe34984da](https://linux-hardware.org/?probe=2fe34984da) | Aug 15, 2022 |
| HP            | 1825                        | Desktop     | [bceae72004](https://linux-hardware.org/?probe=bceae72004) | Aug 15, 2022 |
| MSI           | Z170A PC MATE               | Desktop     | [97f14bc24c](https://linux-hardware.org/?probe=97f14bc24c) | Aug 14, 2022 |
| Lenovo        | ThinkCentre XXXX 739527G    | Desktop     | [ca5fe11e2c](https://linux-hardware.org/?probe=ca5fe11e2c) | Aug 13, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [3e63b30226](https://linux-hardware.org/?probe=3e63b30226) | Aug 12, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [bc32ff70b7](https://linux-hardware.org/?probe=bc32ff70b7) | Aug 12, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [d7735b3387](https://linux-hardware.org/?probe=d7735b3387) | Aug 12, 2022 |
| MSI           | Vector GP76 12UH            | Notebook    | [4549b417bf](https://linux-hardware.org/?probe=4549b417bf) | Aug 12, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [ba9961565a](https://linux-hardware.org/?probe=ba9961565a) | Aug 12, 2022 |
| MSI           | Vector GP76 12UH            | Notebook    | [8bbf4dd310](https://linux-hardware.org/?probe=8bbf4dd310) | Aug 12, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [fe91d8cdd3](https://linux-hardware.org/?probe=fe91d8cdd3) | Aug 11, 2022 |
| ASUSTek       | UX410UAR                    | Notebook    | [9de54b22a8](https://linux-hardware.org/?probe=9de54b22a8) | Aug 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [26b1a32b84](https://linux-hardware.org/?probe=26b1a32b84) | Aug 11, 2022 |
| MSI           | MS-AE611 100                | All in one  | [94bcb206d3](https://linux-hardware.org/?probe=94bcb206d3) | Aug 10, 2022 |
| Dell          | Latitude D630               | Notebook    | [5f682c6798](https://linux-hardware.org/?probe=5f682c6798) | Aug 09, 2022 |
| MSI           | 2A9C                        | Desktop     | [8913065613](https://linux-hardware.org/?probe=8913065613) | Aug 06, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [aee6d50427](https://linux-hardware.org/?probe=aee6d50427) | Aug 05, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [882cec3541](https://linux-hardware.org/?probe=882cec3541) | Aug 02, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [f6f97a58c4](https://linux-hardware.org/?probe=f6f97a58c4) | Aug 02, 2022 |
| TUXEDO        | Pulse 15 Gen2               | Notebook    | [e650b177cc](https://linux-hardware.org/?probe=e650b177cc) | Aug 02, 2022 |
| Dell          | Latitude 5520               | Notebook    | [0406990128](https://linux-hardware.org/?probe=0406990128) | Aug 01, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [b59f87dd02](https://linux-hardware.org/?probe=b59f87dd02) | Aug 01, 2022 |
| Acer          | Swift SF114-32              | Notebook    | [9e219bd7c2](https://linux-hardware.org/?probe=9e219bd7c2) | Jul 29, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [e6f2cdc55e](https://linux-hardware.org/?probe=e6f2cdc55e) | Jul 29, 2022 |
| Dell          | Latitude 5590               | Notebook    | [ab7d6b9f02](https://linux-hardware.org/?probe=ab7d6b9f02) | Jul 28, 2022 |
| ASUSTek       | Pro B560M-C                 | Desktop     | [c4a4fed104](https://linux-hardware.org/?probe=c4a4fed104) | Jul 28, 2022 |
| Dell          | Latitude E6430s             | Notebook    | [356556d83a](https://linux-hardware.org/?probe=356556d83a) | Jul 28, 2022 |
| Dell          | Latitude D630               | Notebook    | [a14838d1ef](https://linux-hardware.org/?probe=a14838d1ef) | Jul 28, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [e5d7cc54e7](https://linux-hardware.org/?probe=e5d7cc54e7) | Jul 28, 2022 |
| ASUSTek       | Rampage IV GENE             | Desktop     | [bf64b6cf98](https://linux-hardware.org/?probe=bf64b6cf98) | Jul 28, 2022 |
| ASUSTek       | Pro B560M-C                 | Desktop     | [d8b47ea062](https://linux-hardware.org/?probe=d8b47ea062) | Jul 27, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [c2f56b2458](https://linux-hardware.org/?probe=c2f56b2458) | Jul 27, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [910067609e](https://linux-hardware.org/?probe=910067609e) | Jul 27, 2022 |
| Toshiba       | Satellite C870D-116         | Notebook    | [d92af8246c](https://linux-hardware.org/?probe=d92af8246c) | Jul 26, 2022 |
| Lenovo        | ThinkPad T61 7661A16        | Notebook    | [df4af55b5b](https://linux-hardware.org/?probe=df4af55b5b) | Jul 26, 2022 |
| Lenovo        | ThinkPad T61 7661A16        | Notebook    | [892a11d89d](https://linux-hardware.org/?probe=892a11d89d) | Jul 26, 2022 |
| Sony          | VGN-Z31XN_B                 | Notebook    | [f27c511d04](https://linux-hardware.org/?probe=f27c511d04) | Jul 26, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [b2e54629e5](https://linux-hardware.org/?probe=b2e54629e5) | Jul 25, 2022 |
| Panasonic     | FZ55-2                      | Notebook    | [a190a7d890](https://linux-hardware.org/?probe=a190a7d890) | Jul 25, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [d3ac2d72dd](https://linux-hardware.org/?probe=d3ac2d72dd) | Jul 25, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [df38a7a1ff](https://linux-hardware.org/?probe=df38a7a1ff) | Jul 25, 2022 |
| MSI           | Vector GP76 12UH            | Notebook    | [7ac84940b8](https://linux-hardware.org/?probe=7ac84940b8) | Jul 24, 2022 |
| Toshiba       | Portable PC                 | Notebook    | [00cd85e866](https://linux-hardware.org/?probe=00cd85e866) | Jul 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [1860c6d71f](https://linux-hardware.org/?probe=1860c6d71f) | Jul 23, 2022 |
| Foxconn       | G41MX/G41MX-K 2.0 1.0       | Desktop     | [d13d96da02](https://linux-hardware.org/?probe=d13d96da02) | Jul 23, 2022 |
| ASUSTek       | Rampage IV GENE             | Desktop     | [f8ce34248a](https://linux-hardware.org/?probe=f8ce34248a) | Jul 22, 2022 |
| Lenovo        | ThinkPad E580 20KSS0GK01    | Notebook    | [b2d902cbc6](https://linux-hardware.org/?probe=b2d902cbc6) | Jul 21, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [f4f889fb4e](https://linux-hardware.org/?probe=f4f889fb4e) | Jul 20, 2022 |
| Razer         | Blade 17 (Mid 2021) - RZ... | Notebook    | [0b73c72c74](https://linux-hardware.org/?probe=0b73c72c74) | Jul 19, 2022 |
| MSI           | Z97-G43 GAMING              | Desktop     | [f7f43ba6ed](https://linux-hardware.org/?probe=f7f43ba6ed) | Jul 18, 2022 |
| Acer          | Aspire A515-54              | Notebook    | [bffac60888](https://linux-hardware.org/?probe=bffac60888) | Jul 16, 2022 |
| Acer          | Aspire A515-54              | Notebook    | [d52eabbac8](https://linux-hardware.org/?probe=d52eabbac8) | Jul 16, 2022 |
| HP            | ProBook 650 G5              | Notebook    | [471b64a407](https://linux-hardware.org/?probe=471b64a407) | Jul 16, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [84b1994696](https://linux-hardware.org/?probe=84b1994696) | Jul 16, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [5b07f65ff5](https://linux-hardware.org/?probe=5b07f65ff5) | Jul 16, 2022 |
| Sony          | SVE1513H1EW                 | Notebook    | [6e4d66c2ee](https://linux-hardware.org/?probe=6e4d66c2ee) | Jul 15, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [cb6916e513](https://linux-hardware.org/?probe=cb6916e513) | Jul 15, 2022 |
| Medion        | MS-7797                     | Desktop     | [caf13d5392](https://linux-hardware.org/?probe=caf13d5392) | Jul 14, 2022 |
| Lenovo        | ThinkPad P15s Gen 1 20T5... | Notebook    | [b85cc7c80c](https://linux-hardware.org/?probe=b85cc7c80c) | Jul 14, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | Notebook    | [33bea96de9](https://linux-hardware.org/?probe=33bea96de9) | Jul 12, 2022 |
| Acer          | Aspire M3920                | Desktop     | [9b12bf66ac](https://linux-hardware.org/?probe=9b12bf66ac) | Jul 11, 2022 |
| MSI           | Z490-A PRO                  | Desktop     | [b40a6c6b15](https://linux-hardware.org/?probe=b40a6c6b15) | Jul 09, 2022 |
| Sony          | VGN-Z31XN_B                 | Notebook    | [e541b7743e](https://linux-hardware.org/?probe=e541b7743e) | Jul 08, 2022 |
| HP            | 2820h                       | Desktop     | [bfc5afa2c8](https://linux-hardware.org/?probe=bfc5afa2c8) | Jul 07, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [b08ab62885](https://linux-hardware.org/?probe=b08ab62885) | Jul 06, 2022 |
| Dell          | 0200DY A00                  | Desktop     | [442b0c2a46](https://linux-hardware.org/?probe=442b0c2a46) | Jul 06, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [e7c2f09e51](https://linux-hardware.org/?probe=e7c2f09e51) | Jul 05, 2022 |
| NEC Comput... | NEC Versa M370              | Notebook    | [d4dbd6878c](https://linux-hardware.org/?probe=d4dbd6878c) | Jul 04, 2022 |
| ASRock        | Z87 Extreme4                | Desktop     | [238f7bf18c](https://linux-hardware.org/?probe=238f7bf18c) | Jul 03, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [0dfbfe1182](https://linux-hardware.org/?probe=0dfbfe1182) | Jul 03, 2022 |
| HP            | Pavilion dm1                | Notebook    | [927f5b38e0](https://linux-hardware.org/?probe=927f5b38e0) | Jun 29, 2022 |
| Apple         | MacBookPro5,4               | Notebook    | [66a8fd4642](https://linux-hardware.org/?probe=66a8fd4642) | Jun 28, 2022 |
| Medion        | E7214                       | Notebook    | [439509e70a](https://linux-hardware.org/?probe=439509e70a) | Jun 28, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [740f06d30d](https://linux-hardware.org/?probe=740f06d30d) | Jun 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [90a56ffa69](https://linux-hardware.org/?probe=90a56ffa69) | Jun 27, 2022 |
| ASUSTek       | X555LJ                      | Notebook    | [0c6dd4c77c](https://linux-hardware.org/?probe=0c6dd4c77c) | Jun 27, 2022 |
| Google        | Bobba360                    | Notebook    | [6fcae5202a](https://linux-hardware.org/?probe=6fcae5202a) | Jun 26, 2022 |
| Dell          | Latitude E6330              | Notebook    | [969981b8cb](https://linux-hardware.org/?probe=969981b8cb) | Jun 25, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [9421b03b9e](https://linux-hardware.org/?probe=9421b03b9e) | Jun 25, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [c2e6e05eea](https://linux-hardware.org/?probe=c2e6e05eea) | Jun 25, 2022 |
| ASRock        | Z87M Extreme4               | Desktop     | [06504aecc5](https://linux-hardware.org/?probe=06504aecc5) | Jun 24, 2022 |
| MSI           | IONA                        | Desktop     | [9f4e8871a7](https://linux-hardware.org/?probe=9f4e8871a7) | Jun 24, 2022 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [34e3aad338](https://linux-hardware.org/?probe=34e3aad338) | Jun 24, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [9f67f6836e](https://linux-hardware.org/?probe=9f67f6836e) | Jun 23, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [32a4f6d3e0](https://linux-hardware.org/?probe=32a4f6d3e0) | Jun 23, 2022 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [f3ceed4c58](https://linux-hardware.org/?probe=f3ceed4c58) | Jun 20, 2022 |
| ASUSTek       | GL502VMK                    | Notebook    | [d872e88532](https://linux-hardware.org/?probe=d872e88532) | Jun 20, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [17e0b3e4c0](https://linux-hardware.org/?probe=17e0b3e4c0) | Jun 19, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [b070339877](https://linux-hardware.org/?probe=b070339877) | Jun 18, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [6d1dcb879d](https://linux-hardware.org/?probe=6d1dcb879d) | Jun 18, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [6647ddd346](https://linux-hardware.org/?probe=6647ddd346) | Jun 17, 2022 |
| Unknown       | Unknown                     | Notebook    | [812caba8bf](https://linux-hardware.org/?probe=812caba8bf) | Jun 16, 2022 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [c1efcc5411](https://linux-hardware.org/?probe=c1efcc5411) | Jun 16, 2022 |
| Unknown       | MediaTek krane sku176       | Soc         | [c992270582](https://linux-hardware.org/?probe=c992270582) | Jun 15, 2022 |
| Medion        | Cattle24 1M                 | Desktop     | [5ef81d4b82](https://linux-hardware.org/?probe=5ef81d4b82) | Jun 15, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [d4e4001c4c](https://linux-hardware.org/?probe=d4e4001c4c) | Jun 15, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [4b6c230717](https://linux-hardware.org/?probe=4b6c230717) | Jun 12, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [3ddbde438b](https://linux-hardware.org/?probe=3ddbde438b) | Jun 12, 2022 |
| MSI           | H55M-E33                    | Desktop     | [1fa7005827](https://linux-hardware.org/?probe=1fa7005827) | Jun 12, 2022 |
| HP            | Laptop 15s-fq3xxx           | Notebook    | [6acd8f6081](https://linux-hardware.org/?probe=6acd8f6081) | Jun 12, 2022 |
| Dell          | 0XCR8D A03                  | Desktop     | [7b5fb1809b](https://linux-hardware.org/?probe=7b5fb1809b) | Jun 09, 2022 |
| HP            | Compaq 8710w                | Notebook    | [666f2ebcf0](https://linux-hardware.org/?probe=666f2ebcf0) | Jun 08, 2022 |
| Dell          | 0HX555                      | Desktop     | [41ae8a1dd5](https://linux-hardware.org/?probe=41ae8a1dd5) | Jun 08, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [9e49a2cbac](https://linux-hardware.org/?probe=9e49a2cbac) | Jun 05, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [bfd4aab236](https://linux-hardware.org/?probe=bfd4aab236) | Jun 04, 2022 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | Desktop     | [68a1616b4a](https://linux-hardware.org/?probe=68a1616b4a) | Jun 03, 2022 |
| Samsung       | 900X3C/900X3D/900X3E/900... | Notebook    | [54fb76191c](https://linux-hardware.org/?probe=54fb76191c) | Jun 03, 2022 |
| HP            | ProBook 470 G1              | Notebook    | [ea56369709](https://linux-hardware.org/?probe=ea56369709) | Jun 03, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [909d9cb8d5](https://linux-hardware.org/?probe=909d9cb8d5) | Jun 03, 2022 |
| Samsung       | 750XED                      | Notebook    | [1a900ee340](https://linux-hardware.org/?probe=1a900ee340) | Jun 02, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [d81154a7e1](https://linux-hardware.org/?probe=d81154a7e1) | Jun 02, 2022 |
| ASUSTek       | G11CD-K                     | Desktop     | [6550f85808](https://linux-hardware.org/?probe=6550f85808) | Jun 01, 2022 |
| Unknown       | SKYBAY                      | Desktop     | [88ef811c4d](https://linux-hardware.org/?probe=88ef811c4d) | May 31, 2022 |
| Toshiba       | Satellite C70D-A            | Notebook    | [70313d6ed4](https://linux-hardware.org/?probe=70313d6ed4) | May 31, 2022 |
| Toshiba       | Satellite C70D-A            | Notebook    | [820a9fb182](https://linux-hardware.org/?probe=820a9fb182) | May 30, 2022 |
| SLIMBOOK      | TITAN                       | Notebook    | [1029a819d7](https://linux-hardware.org/?probe=1029a819d7) | May 29, 2022 |
| SLIMBOOK      | TITAN                       | Notebook    | [c4e27f4d19](https://linux-hardware.org/?probe=c4e27f4d19) | May 29, 2022 |
| HP            | Pavilion 17                 | Notebook    | [077be5d10b](https://linux-hardware.org/?probe=077be5d10b) | May 28, 2022 |
| Schenker      | XMG_APEX15_XAP15E20         | Notebook    | [475315dc10](https://linux-hardware.org/?probe=475315dc10) | May 28, 2022 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | Notebook    | [397d64e10c](https://linux-hardware.org/?probe=397d64e10c) | May 27, 2022 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | Notebook    | [a74cc1410a](https://linux-hardware.org/?probe=a74cc1410a) | May 27, 2022 |
| HP            | Pavilion g6                 | Notebook    | [ef71909561](https://linux-hardware.org/?probe=ef71909561) | May 26, 2022 |
| HP            | Pavilion g6                 | Notebook    | [41d1e81397](https://linux-hardware.org/?probe=41d1e81397) | May 26, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [6e5dd6f76f](https://linux-hardware.org/?probe=6e5dd6f76f) | May 25, 2022 |
| Dell          | 0HY9JP A01                  | Desktop     | [4107e267d7](https://linux-hardware.org/?probe=4107e267d7) | May 24, 2022 |
| HP            | OMEN by Laptop              | Notebook    | [6e1f063199](https://linux-hardware.org/?probe=6e1f063199) | May 24, 2022 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [fdc743e9e1](https://linux-hardware.org/?probe=fdc743e9e1) | May 23, 2022 |
| ASUSTek       | X756UQ                      | Notebook    | [e8736821c1](https://linux-hardware.org/?probe=e8736821c1) | May 23, 2022 |
| Medion        | P6624                       | Notebook    | [ed8bd28269](https://linux-hardware.org/?probe=ed8bd28269) | May 21, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [d1ca28a2fb](https://linux-hardware.org/?probe=d1ca28a2fb) | May 21, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [a0597ba198](https://linux-hardware.org/?probe=a0597ba198) | May 20, 2022 |
| HP            | ProBook 470 G2              | Notebook    | [9d14cc23ca](https://linux-hardware.org/?probe=9d14cc23ca) | May 20, 2022 |
| HP            | ProBook 470 G2              | Notebook    | [9a331b90a5](https://linux-hardware.org/?probe=9a331b90a5) | May 19, 2022 |
| HP            | 82A2                        | Desktop     | [56d6c8d749](https://linux-hardware.org/?probe=56d6c8d749) | May 19, 2022 |
| HP            | 82A2                        | Desktop     | [6e0efeba1d](https://linux-hardware.org/?probe=6e0efeba1d) | May 19, 2022 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [2886b99972](https://linux-hardware.org/?probe=2886b99972) | May 17, 2022 |
| HP            | ProBook 470 G2              | Notebook    | [4c3a3b2de2](https://linux-hardware.org/?probe=4c3a3b2de2) | May 17, 2022 |
| ASUSTek       | GL552VW                     | Notebook    | [2f26e2ec6e](https://linux-hardware.org/?probe=2f26e2ec6e) | May 15, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [74cb2084ef](https://linux-hardware.org/?probe=74cb2084ef) | May 15, 2022 |
| ASUSTek       | Mac-F60DEB81FF30ACF6 Mac... | Notebook    | [0f8829e460](https://linux-hardware.org/?probe=0f8829e460) | May 15, 2022 |
| Lenovo        | ThinkPad T450s 20BWS4X50... | Notebook    | [0fb588c686](https://linux-hardware.org/?probe=0fb588c686) | May 15, 2022 |
| ASUSTek       | Mac-F60DEB81FF30ACF6 Mac... | Notebook    | [83b27998e5](https://linux-hardware.org/?probe=83b27998e5) | May 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [6adb7e22c5](https://linux-hardware.org/?probe=6adb7e22c5) | May 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [3f84f4220e](https://linux-hardware.org/?probe=3f84f4220e) | May 14, 2022 |
| Sony          | VPCEH1M0E                   | Notebook    | [eefe7eee06](https://linux-hardware.org/?probe=eefe7eee06) | May 13, 2022 |
| HP            | ProBook 470 G1              | Notebook    | [06030eee20](https://linux-hardware.org/?probe=06030eee20) | May 13, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [9722abbde0](https://linux-hardware.org/?probe=9722abbde0) | May 12, 2022 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [3f20d2bc2b](https://linux-hardware.org/?probe=3f20d2bc2b) | May 12, 2022 |
| Dell          | 0HY9JP A01                  | Desktop     | [0026740e3f](https://linux-hardware.org/?probe=0026740e3f) | May 12, 2022 |
| Acer          | Aspire M3985                | Desktop     | [e650ae1a26](https://linux-hardware.org/?probe=e650ae1a26) | May 11, 2022 |
| MSI           | GF63 Thin 9SC               | Notebook    | [a6f5c6215d](https://linux-hardware.org/?probe=a6f5c6215d) | May 11, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [4f87a5b748](https://linux-hardware.org/?probe=4f87a5b748) | May 10, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [eaa10a050b](https://linux-hardware.org/?probe=eaa10a050b) | May 10, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [0066686d1d](https://linux-hardware.org/?probe=0066686d1d) | May 10, 2022 |
| Dell          | 0KV3RP A00                  | Desktop     | [6ef8c2f171](https://linux-hardware.org/?probe=6ef8c2f171) | May 10, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [05b7c2c72c](https://linux-hardware.org/?probe=05b7c2c72c) | May 09, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [a9e6ecf483](https://linux-hardware.org/?probe=a9e6ecf483) | May 09, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [8080b9becd](https://linux-hardware.org/?probe=8080b9becd) | May 08, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [1d84f1a74a](https://linux-hardware.org/?probe=1d84f1a74a) | May 07, 2022 |
| HP            | 82F2                        | Desktop     | [cb49a04bce](https://linux-hardware.org/?probe=cb49a04bce) | May 07, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [8e2da684e0](https://linux-hardware.org/?probe=8e2da684e0) | May 07, 2022 |
| Dell          | Latitude E6330              | Notebook    | [cbfc4e6f78](https://linux-hardware.org/?probe=cbfc4e6f78) | May 07, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [093d7ea1c9](https://linux-hardware.org/?probe=093d7ea1c9) | May 06, 2022 |
| Lenovo        | ThinkPad X280 20KES94F05    | Notebook    | [16b4cbc9fb](https://linux-hardware.org/?probe=16b4cbc9fb) | May 05, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [c08f733706](https://linux-hardware.org/?probe=c08f733706) | May 05, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [53a75b2d5c](https://linux-hardware.org/?probe=53a75b2d5c) | May 04, 2022 |
| Dell          | 0VHRW1 A03                  | Desktop     | [2a5880a214](https://linux-hardware.org/?probe=2a5880a214) | May 03, 2022 |
| Dell          | 0VHRW1 A03                  | Desktop     | [8204a08a04](https://linux-hardware.org/?probe=8204a08a04) | May 03, 2022 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [a7396f278d](https://linux-hardware.org/?probe=a7396f278d) | May 02, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [01a95b61fe](https://linux-hardware.org/?probe=01a95b61fe) | May 02, 2022 |
| ASUSTek       | X550LD                      | Notebook    | [5625deb6aa](https://linux-hardware.org/?probe=5625deb6aa) | May 01, 2022 |
| ASUSTek       | X756UQ                      | Notebook    | [130944084d](https://linux-hardware.org/?probe=130944084d) | May 01, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [cc016ce0c5](https://linux-hardware.org/?probe=cc016ce0c5) | May 01, 2022 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [0e0d0dd3aa](https://linux-hardware.org/?probe=0e0d0dd3aa) | Apr 30, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [f140b54261](https://linux-hardware.org/?probe=f140b54261) | Apr 30, 2022 |
| ASUSTek       | X756UQ                      | Notebook    | [2543d87831](https://linux-hardware.org/?probe=2543d87831) | Apr 30, 2022 |
| Google        | Bobba360                    | Notebook    | [e90fbcc91d](https://linux-hardware.org/?probe=e90fbcc91d) | Apr 29, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [21fcbc1850](https://linux-hardware.org/?probe=21fcbc1850) | Apr 27, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [edf60be002](https://linux-hardware.org/?probe=edf60be002) | Apr 26, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [de010dfc55](https://linux-hardware.org/?probe=de010dfc55) | Apr 24, 2022 |
| BLAUPUNKT     | Discovery 1011WI            | Notebook    | [c20b87673e](https://linux-hardware.org/?probe=c20b87673e) | Apr 24, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [c668e0d48e](https://linux-hardware.org/?probe=c668e0d48e) | Apr 23, 2022 |
| Lenovo        | ThinkPad T450s 20BWS2HP0... | Notebook    | [762843e768](https://linux-hardware.org/?probe=762843e768) | Apr 23, 2022 |
| Lenovo        | ThinkPad T450s 20BWS2HP0... | Notebook    | [11ec4d291b](https://linux-hardware.org/?probe=11ec4d291b) | Apr 23, 2022 |
| Fujitsu       | LIFEBOOK E744               | Notebook    | [ca56dc9824](https://linux-hardware.org/?probe=ca56dc9824) | Apr 21, 2022 |
| ASUSTek       | GL502VMK                    | Notebook    | [cc5ed34db8](https://linux-hardware.org/?probe=cc5ed34db8) | Apr 21, 2022 |
| Lenovo        | ThinkPad T520 4243AP1       | Notebook    | [7723ab4bd9](https://linux-hardware.org/?probe=7723ab4bd9) | Apr 19, 2022 |
| Medion        | D3F3-EM2                    | Desktop     | [733df830d1](https://linux-hardware.org/?probe=733df830d1) | Apr 19, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [0e53d4286d](https://linux-hardware.org/?probe=0e53d4286d) | Apr 19, 2022 |
| MSI           | GL65 Leopard 10SER          | Notebook    | [2bdfe0279e](https://linux-hardware.org/?probe=2bdfe0279e) | Apr 19, 2022 |
| ASUSTek       | G752VSK                     | Notebook    | [4b6d535621](https://linux-hardware.org/?probe=4b6d535621) | Apr 18, 2022 |
| Lenovo        | ThinkPad T440s 20ARS1940... | Notebook    | [a7fbe1af34](https://linux-hardware.org/?probe=a7fbe1af34) | Apr 18, 2022 |
| ASUSTek       | G752VSK                     | Notebook    | [dfbc0779e8](https://linux-hardware.org/?probe=dfbc0779e8) | Apr 17, 2022 |
| Lenovo        | ThinkPad T430 2349D53       | Notebook    | [7b1d2ec5a1](https://linux-hardware.org/?probe=7b1d2ec5a1) | Apr 17, 2022 |
| Acer          | Aspire 5735                 | Notebook    | [e43434e15c](https://linux-hardware.org/?probe=e43434e15c) | Apr 15, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [4639b09a3e](https://linux-hardware.org/?probe=4639b09a3e) | Apr 14, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [5bdba5a921](https://linux-hardware.org/?probe=5bdba5a921) | Apr 14, 2022 |
| MSI           | B250M MORTAR                | Desktop     | [8bf9715804](https://linux-hardware.org/?probe=8bf9715804) | Apr 14, 2022 |
| ASRock        | TRX40 Taichi                | Desktop     | [4a90b659fc](https://linux-hardware.org/?probe=4a90b659fc) | Apr 14, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [b80dc08588](https://linux-hardware.org/?probe=b80dc08588) | Apr 14, 2022 |
| Dell          | Latitude 5591               | Notebook    | [3f3f097a1a](https://linux-hardware.org/?probe=3f3f097a1a) | Apr 13, 2022 |
| ASRock        | H170M Pro4                  | Desktop     | [a8bd162bf1](https://linux-hardware.org/?probe=a8bd162bf1) | Apr 13, 2022 |
| Gigabyte      | Z77-D3H                     | Desktop     | [2ddb0d0765](https://linux-hardware.org/?probe=2ddb0d0765) | Apr 13, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [5aafaf0890](https://linux-hardware.org/?probe=5aafaf0890) | Apr 13, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [983dbbf9e8](https://linux-hardware.org/?probe=983dbbf9e8) | Apr 13, 2022 |
| Medion        | BTDD-EAIO                   | All in one  | [8de03f374b](https://linux-hardware.org/?probe=8de03f374b) | Apr 13, 2022 |
| Acer          | Aspire 7745G                | Notebook    | [7ea9773813](https://linux-hardware.org/?probe=7ea9773813) | Apr 12, 2022 |
| ASRock        | EP2C602-4L/D16              | Desktop     | [938b601307](https://linux-hardware.org/?probe=938b601307) | Apr 11, 2022 |
| Lenovo        | Legion Y540-17IRH-PG0 81... | Notebook    | [09f8f09862](https://linux-hardware.org/?probe=09f8f09862) | Apr 11, 2022 |
| Lenovo        | Legion Y540-17IRH-PG0 81... | Notebook    | [da1cd5bf6e](https://linux-hardware.org/?probe=da1cd5bf6e) | Apr 11, 2022 |
| Google        | Akali 360                   | Notebook    | [dccccb359b](https://linux-hardware.org/?probe=dccccb359b) | Apr 11, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [2ce1788c33](https://linux-hardware.org/?probe=2ce1788c33) | Apr 11, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [01f57dd952](https://linux-hardware.org/?probe=01f57dd952) | Apr 10, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [7f71b84230](https://linux-hardware.org/?probe=7f71b84230) | Apr 10, 2022 |
| HP            | ProBook 470 G2              | Notebook    | [a6aee71c13](https://linux-hardware.org/?probe=a6aee71c13) | Apr 09, 2022 |
| HP            | ProBook 470 G2              | Notebook    | [1d1cdbd95c](https://linux-hardware.org/?probe=1d1cdbd95c) | Apr 09, 2022 |
| Dell          | Latitude E6430              | Notebook    | [dd09c863c8](https://linux-hardware.org/?probe=dd09c863c8) | Apr 08, 2022 |
| ASRockRack    | ROMED8-2T                   | Server      | [49aedaee61](https://linux-hardware.org/?probe=49aedaee61) | Apr 08, 2022 |
| HP            | ProBook 430 G1              | Notebook    | [8bcbe236a7](https://linux-hardware.org/?probe=8bcbe236a7) | Apr 07, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [af324f356f](https://linux-hardware.org/?probe=af324f356f) | Apr 07, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [27bddd0a9c](https://linux-hardware.org/?probe=27bddd0a9c) | Apr 07, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [fc358abe4b](https://linux-hardware.org/?probe=fc358abe4b) | Apr 06, 2022 |
| HP            | 470 G7 Notebook PC          | Notebook    | [34fc91d9ac](https://linux-hardware.org/?probe=34fc91d9ac) | Apr 06, 2022 |
| ASUSTek       | P8H61-M LX2 R2.0            | Desktop     | [dff8141976](https://linux-hardware.org/?probe=dff8141976) | Apr 06, 2022 |
| MSI           | Eclipse SLI                 | Desktop     | [e488b9407a](https://linux-hardware.org/?probe=e488b9407a) | Apr 05, 2022 |
| MSI           | Eclipse SLI                 | Desktop     | [aebfec44b2](https://linux-hardware.org/?probe=aebfec44b2) | Apr 05, 2022 |
| Dell          | Latitude 5410               | Notebook    | [9d03bb6cad](https://linux-hardware.org/?probe=9d03bb6cad) | Apr 05, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [8c4011afa9](https://linux-hardware.org/?probe=8c4011afa9) | Apr 04, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [b697fd5f0a](https://linux-hardware.org/?probe=b697fd5f0a) | Apr 03, 2022 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [b8d47c54c3](https://linux-hardware.org/?probe=b8d47c54c3) | Apr 03, 2022 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [53da5b2d7c](https://linux-hardware.org/?probe=53da5b2d7c) | Apr 03, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [94a9015090](https://linux-hardware.org/?probe=94a9015090) | Apr 03, 2022 |
| ASRock        | B75M-GL                     | Desktop     | [087381b93e](https://linux-hardware.org/?probe=087381b93e) | Apr 02, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [1de292a85c](https://linux-hardware.org/?probe=1de292a85c) | Apr 02, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [387b77f172](https://linux-hardware.org/?probe=387b77f172) | Apr 01, 2022 |
| ASUSTek       | X540LA                      | Notebook    | [732406d8b0](https://linux-hardware.org/?probe=732406d8b0) | Apr 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [086261ecef](https://linux-hardware.org/?probe=086261ecef) | Apr 01, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [4731581e9b](https://linux-hardware.org/?probe=4731581e9b) | Mar 31, 2022 |
| HP            | ZBook Studio G4             | Notebook    | [d5ec5c3e8e](https://linux-hardware.org/?probe=d5ec5c3e8e) | Mar 30, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [670f83f6bb](https://linux-hardware.org/?probe=670f83f6bb) | Mar 29, 2022 |
| Medion        | Crawler E25                 | Notebook    | [6093396d8a](https://linux-hardware.org/?probe=6093396d8a) | Mar 28, 2022 |
| HP            | 82A2                        | Desktop     | [5736762c06](https://linux-hardware.org/?probe=5736762c06) | Mar 28, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [b8969bf34b](https://linux-hardware.org/?probe=b8969bf34b) | Mar 27, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [e04592bee1](https://linux-hardware.org/?probe=e04592bee1) | Mar 27, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [c4b697295e](https://linux-hardware.org/?probe=c4b697295e) | Mar 26, 2022 |
| Acer          | Aspire 8930                 | Notebook    | [6774be59d3](https://linux-hardware.org/?probe=6774be59d3) | Mar 26, 2022 |
| HP            | EliteBook Folio 1040 G1     | Notebook    | [bbdb3c316f](https://linux-hardware.org/?probe=bbdb3c316f) | Mar 25, 2022 |
| HP            | EliteBook Folio 1040 G1     | Notebook    | [6096fbc1ba](https://linux-hardware.org/?probe=6096fbc1ba) | Mar 25, 2022 |
| ASUSTek       | N56VZ                       | Notebook    | [7ad46659a5](https://linux-hardware.org/?probe=7ad46659a5) | Mar 24, 2022 |
| Packard Be... | DOT S                       | Notebook    | [591be1d465](https://linux-hardware.org/?probe=591be1d465) | Mar 22, 2022 |
| Lenovo        | ThinkPad T430 2349D53       | Notebook    | [26cd5cf250](https://linux-hardware.org/?probe=26cd5cf250) | Mar 20, 2022 |
| ASUSTek       | X555LJ                      | Notebook    | [9e38b0860e](https://linux-hardware.org/?probe=9e38b0860e) | Mar 19, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [1feeb83fb4](https://linux-hardware.org/?probe=1feeb83fb4) | Mar 19, 2022 |
| Gigabyte      | GB-BRR7H-4800               | Desktop     | [5415b5f876](https://linux-hardware.org/?probe=5415b5f876) | Mar 18, 2022 |
| Acer          | Aspire 8930                 | Notebook    | [79f6f7d9c1](https://linux-hardware.org/?probe=79f6f7d9c1) | Mar 18, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [2692e4dfd1](https://linux-hardware.org/?probe=2692e4dfd1) | Mar 18, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [6a5b5cd15e](https://linux-hardware.org/?probe=6a5b5cd15e) | Mar 17, 2022 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [908e3fe366](https://linux-hardware.org/?probe=908e3fe366) | Mar 16, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [a3444ce232](https://linux-hardware.org/?probe=a3444ce232) | Mar 16, 2022 |
| Dell          | 0XHGV1 A00                  | Desktop     | [605d83cd15](https://linux-hardware.org/?probe=605d83cd15) | Mar 15, 2022 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [1b6764fd97](https://linux-hardware.org/?probe=1b6764fd97) | Mar 15, 2022 |
| Lenovo        | Yoga 730-13IWL 81JR         | Convertible | [00edfc8f9b](https://linux-hardware.org/?probe=00edfc8f9b) | Mar 14, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [37a24fa0b8](https://linux-hardware.org/?probe=37a24fa0b8) | Mar 13, 2022 |
| Medion        | H81H3-EM2 H81EM2W08.304     | Desktop     | [e2e15f011b](https://linux-hardware.org/?probe=e2e15f011b) | Mar 12, 2022 |
| ASUSTek       | X756UQ                      | Notebook    | [30ec3132c4](https://linux-hardware.org/?probe=30ec3132c4) | Mar 12, 2022 |
| Lenovo        | ThinkPad T540p 20BE005YM... | Notebook    | [6d0cd0f4b9](https://linux-hardware.org/?probe=6d0cd0f4b9) | Mar 10, 2022 |
| Lenovo        | ThinkPad X260 20F5S6MF02    | Notebook    | [5e026c07c0](https://linux-hardware.org/?probe=5e026c07c0) | Mar 10, 2022 |
| Lenovo        | ThinkPad L390 20NSS1YV0B    | Notebook    | [a48bd2e59b](https://linux-hardware.org/?probe=a48bd2e59b) | Mar 10, 2022 |
| Dell          | 0XHGV1 A00                  | Desktop     | [8d3cfb2f81](https://linux-hardware.org/?probe=8d3cfb2f81) | Mar 09, 2022 |
| HP            | Pavilion zd8000 (EL052EA... | Notebook    | [18f42a184c](https://linux-hardware.org/?probe=18f42a184c) | Mar 08, 2022 |
| Dell          | Latitude 5500               | Notebook    | [3d87bc42c6](https://linux-hardware.org/?probe=3d87bc42c6) | Mar 08, 2022 |
| Dell          | Latitude 5500               | Notebook    | [fc0c5280d7](https://linux-hardware.org/?probe=fc0c5280d7) | Mar 08, 2022 |
| Lenovo        | ThinkPad W541 20EFA013MB    | Notebook    | [b4087fab13](https://linux-hardware.org/?probe=b4087fab13) | Mar 06, 2022 |
| Dell          | Latitude E6330              | Notebook    | [f4491d2da7](https://linux-hardware.org/?probe=f4491d2da7) | Mar 06, 2022 |
| Medion        | MS-7797                     | Desktop     | [88982d8ccb](https://linux-hardware.org/?probe=88982d8ccb) | Mar 05, 2022 |
| Supermicro    | X11DPi-N                    | Server      | [73518731a1](https://linux-hardware.org/?probe=73518731a1) | Mar 03, 2022 |
| Lenovo        | 36F4 SDK0J40709 WIN 3259... | All in one  | [68b6455d7a](https://linux-hardware.org/?probe=68b6455d7a) | Mar 03, 2022 |
| Supermicro    | X11DPi-N                    | Server      | [2ffd17de74](https://linux-hardware.org/?probe=2ffd17de74) | Mar 03, 2022 |
| HP            | 1825                        | Desktop     | [a7ce5b6b11](https://linux-hardware.org/?probe=a7ce5b6b11) | Mar 03, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [435c237f8f](https://linux-hardware.org/?probe=435c237f8f) | Mar 02, 2022 |
| ASUSTek       | ZenBook UX482EG_UX482EG     | Notebook    | [f67c401f47](https://linux-hardware.org/?probe=f67c401f47) | Feb 27, 2022 |
| HP            | Pavilion dv6                | Notebook    | [d04802b99e](https://linux-hardware.org/?probe=d04802b99e) | Feb 27, 2022 |
| HP            | Pavilion 15                 | Notebook    | [e72fbddbc9](https://linux-hardware.org/?probe=e72fbddbc9) | Feb 25, 2022 |
| Gigabyte      | Z590 VISION G               | Desktop     | [163b1f4a34](https://linux-hardware.org/?probe=163b1f4a34) | Feb 25, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [8166a6711c](https://linux-hardware.org/?probe=8166a6711c) | Feb 25, 2022 |
| Fujitsu Si... | D2151-A1 S26361-D2151-A1    | Desktop     | [866eeb024c](https://linux-hardware.org/?probe=866eeb024c) | Feb 24, 2022 |
| Fujitsu Si... | D2151-A1 S26361-D2151-A1    | Desktop     | [9e1c3db4b1](https://linux-hardware.org/?probe=9e1c3db4b1) | Feb 24, 2022 |
| HP            | 2129                        | Desktop     | [b4445ac549](https://linux-hardware.org/?probe=b4445ac549) | Feb 24, 2022 |
| Packard Be... | EasyNote_MX67               | Notebook    | [0687a8a072](https://linux-hardware.org/?probe=0687a8a072) | Feb 23, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [a85780aaae](https://linux-hardware.org/?probe=a85780aaae) | Feb 23, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [fb10931f05](https://linux-hardware.org/?probe=fb10931f05) | Feb 23, 2022 |
| Dell          | Latitude E5550              | Notebook    | [7eb0675554](https://linux-hardware.org/?probe=7eb0675554) | Feb 22, 2022 |
| HP            | Pavilion 15                 | Notebook    | [6aaa686668](https://linux-hardware.org/?probe=6aaa686668) | Feb 22, 2022 |
| Sony          | VGN-FW51JF_H                | Notebook    | [03c4e88514](https://linux-hardware.org/?probe=03c4e88514) | Feb 22, 2022 |
| Dell          | 054KM3 A01                  | Desktop     | [f00a30a31e](https://linux-hardware.org/?probe=f00a30a31e) | Feb 22, 2022 |
| Dell          | 042P49 A00                  | Desktop     | [0be5823fc2](https://linux-hardware.org/?probe=0be5823fc2) | Feb 22, 2022 |
| Lenovo        | ThinkPad W541 20EFA013MB    | Notebook    | [99676b9365](https://linux-hardware.org/?probe=99676b9365) | Feb 21, 2022 |
| MSI           | Z97 PC Mate                 | Desktop     | [e7013b772d](https://linux-hardware.org/?probe=e7013b772d) | Feb 21, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [59476747e2](https://linux-hardware.org/?probe=59476747e2) | Feb 20, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [5b9ec4cd6a](https://linux-hardware.org/?probe=5b9ec4cd6a) | Feb 20, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [ad3eb03b54](https://linux-hardware.org/?probe=ad3eb03b54) | Feb 20, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [83b3333eb0](https://linux-hardware.org/?probe=83b3333eb0) | Feb 20, 2022 |
| Acer          | Aspire V3-771               | Notebook    | [962c444158](https://linux-hardware.org/?probe=962c444158) | Feb 19, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [4f87ec9849](https://linux-hardware.org/?probe=4f87ec9849) | Feb 19, 2022 |
| ASUSTek       | P751JA                      | Notebook    | [54c2cab341](https://linux-hardware.org/?probe=54c2cab341) | Feb 18, 2022 |
| ASUSTek       | X756UQ                      | Notebook    | [757a05c274](https://linux-hardware.org/?probe=757a05c274) | Feb 18, 2022 |
| Lenovo        | ThinkPad X1 Yoga Gen 6 2... | Convertible | [973f8ebf5e](https://linux-hardware.org/?probe=973f8ebf5e) | Feb 17, 2022 |
| Acer          | Aspire 7745G                | Notebook    | [b32ffb9adc](https://linux-hardware.org/?probe=b32ffb9adc) | Feb 17, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [3bb86aa608](https://linux-hardware.org/?probe=3bb86aa608) | Feb 17, 2022 |
| ASUSTek       | P751JA                      | Notebook    | [8e2a0e2970](https://linux-hardware.org/?probe=8e2a0e2970) | Feb 16, 2022 |
| HP            | 82A2                        | Desktop     | [5efad9b732](https://linux-hardware.org/?probe=5efad9b732) | Feb 16, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [df46a37f1a](https://linux-hardware.org/?probe=df46a37f1a) | Feb 15, 2022 |
| HP            | Pavilion dv6500             | Notebook    | [70b0938bc3](https://linux-hardware.org/?probe=70b0938bc3) | Feb 15, 2022 |
| HP            | Pavilion dv6500             | Notebook    | [918d93ea7a](https://linux-hardware.org/?probe=918d93ea7a) | Feb 15, 2022 |
| HP            | Pavilion 15                 | Notebook    | [67825b30b9](https://linux-hardware.org/?probe=67825b30b9) | Feb 15, 2022 |
| HP            | ProBook 6560b               | Notebook    | [425caa152d](https://linux-hardware.org/?probe=425caa152d) | Feb 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [ed2717ae86](https://linux-hardware.org/?probe=ed2717ae86) | Feb 14, 2022 |
| Lenovo        | ThinkPad X260 20F5S3FY00    | Notebook    | [08006b1c3a](https://linux-hardware.org/?probe=08006b1c3a) | Feb 13, 2022 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [1b9f62185f](https://linux-hardware.org/?probe=1b9f62185f) | Feb 13, 2022 |
| HP            | 18E7                        | Desktop     | [b047f83746](https://linux-hardware.org/?probe=b047f83746) | Feb 12, 2022 |
| ASUSTek       | N501JW                      | Notebook    | [7937164c8a](https://linux-hardware.org/?probe=7937164c8a) | Feb 11, 2022 |
| Packard Be... | IMEDIA S2190                | Desktop     | [d0b8d7064b](https://linux-hardware.org/?probe=d0b8d7064b) | Feb 10, 2022 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [d455b09330](https://linux-hardware.org/?probe=d455b09330) | Feb 10, 2022 |
| HP            | 198E                        | Desktop     | [f4781dd683](https://linux-hardware.org/?probe=f4781dd683) | Feb 10, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [804f3b74e0](https://linux-hardware.org/?probe=804f3b74e0) | Feb 10, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [9e1c3acaf3](https://linux-hardware.org/?probe=9e1c3acaf3) | Feb 10, 2022 |
| Gigabyte      | 965P-DS3                    | Desktop     | [1da45b4476](https://linux-hardware.org/?probe=1da45b4476) | Feb 10, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [baf12e4099](https://linux-hardware.org/?probe=baf12e4099) | Feb 09, 2022 |
| GPD           | G1621-02                    | Notebook    | [d823ea2989](https://linux-hardware.org/?probe=d823ea2989) | Feb 09, 2022 |
| Acer          | Aspire A715-74G             | Notebook    | [00f0fe6cd3](https://linux-hardware.org/?probe=00f0fe6cd3) | Feb 09, 2022 |
| HP            | Pavilion dv7                | Notebook    | [03b19f857f](https://linux-hardware.org/?probe=03b19f857f) | Feb 09, 2022 |
| Gigabyte      | Z370 AORUS Gaming 7         | Desktop     | [746ddfc621](https://linux-hardware.org/?probe=746ddfc621) | Feb 09, 2022 |
| Lenovo        | ThinkPad T500 20828VG       | Notebook    | [f79076499b](https://linux-hardware.org/?probe=f79076499b) | Feb 09, 2022 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | Desktop     | [b6b1889923](https://linux-hardware.org/?probe=b6b1889923) | Feb 09, 2022 |
| PC Special... | GK5NPFO                     | Notebook    | [14695b59b4](https://linux-hardware.org/?probe=14695b59b4) | Feb 08, 2022 |
| Toshiba       | Satellite C855-112          | Notebook    | [99cb514a47](https://linux-hardware.org/?probe=99cb514a47) | Feb 07, 2022 |
| HP            | 82F2                        | Desktop     | [6c8626b785](https://linux-hardware.org/?probe=6c8626b785) | Feb 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [48b1ca5fbc](https://linux-hardware.org/?probe=48b1ca5fbc) | Feb 07, 2022 |
| Lenovo        | ThinkPad E495 20NES01600    | Notebook    | [c40a0c5222](https://linux-hardware.org/?probe=c40a0c5222) | Feb 07, 2022 |
| Sony          | VGN-FW51JF_H                | Notebook    | [0e5f92c7b7](https://linux-hardware.org/?probe=0e5f92c7b7) | Feb 07, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [bfe6169921](https://linux-hardware.org/?probe=bfe6169921) | Feb 07, 2022 |
| Intel         | H61 V124                    | Desktop     | [258b472104](https://linux-hardware.org/?probe=258b472104) | Feb 06, 2022 |
| Dell          | 0200DY A00                  | Desktop     | [5714dfdd29](https://linux-hardware.org/?probe=5714dfdd29) | Feb 06, 2022 |
| Acer          | Nitro AN515-52              | Notebook    | [51a06ffad3](https://linux-hardware.org/?probe=51a06ffad3) | Feb 05, 2022 |
| MSI           | MS-7502 Fab D               | Desktop     | [c4bd8c53df](https://linux-hardware.org/?probe=c4bd8c53df) | Feb 05, 2022 |
| MSI           | MS-7502 Fab D               | Desktop     | [01ac407ee8](https://linux-hardware.org/?probe=01ac407ee8) | Feb 05, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [63a70836f3](https://linux-hardware.org/?probe=63a70836f3) | Feb 05, 2022 |
| ASUSTek       | K73SV                       | Notebook    | [0610b130c8](https://linux-hardware.org/?probe=0610b130c8) | Feb 05, 2022 |
| ASUSTek       | K73SV                       | Notebook    | [519bc1d808](https://linux-hardware.org/?probe=519bc1d808) | Feb 05, 2022 |
| ASUSTek       | PRIME TRX40-PRO S           | Desktop     | [cc04fe990c](https://linux-hardware.org/?probe=cc04fe990c) | Feb 03, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [0b95e33d17](https://linux-hardware.org/?probe=0b95e33d17) | Feb 03, 2022 |
| Acer          | Aspire TC-105               | Desktop     | [638079e113](https://linux-hardware.org/?probe=638079e113) | Feb 03, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [690ef309e9](https://linux-hardware.org/?probe=690ef309e9) | Feb 03, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [3171e9710d](https://linux-hardware.org/?probe=3171e9710d) | Feb 03, 2022 |
| ASUSTek       | K95VJ                       | Notebook    | [ebff9950e3](https://linux-hardware.org/?probe=ebff9950e3) | Feb 02, 2022 |
| Notebook      | NH5x_7xDPx                  | Notebook    | [a43204a8d7](https://linux-hardware.org/?probe=a43204a8d7) | Feb 02, 2022 |
| Dell          | G3 3500                     | Notebook    | [141e63ae77](https://linux-hardware.org/?probe=141e63ae77) | Feb 02, 2022 |
| Dell          | 0200DY A00                  | Desktop     | [824ae3f413](https://linux-hardware.org/?probe=824ae3f413) | Feb 02, 2022 |
| Dell          | 0200DY A00                  | Desktop     | [e5f15a17d5](https://linux-hardware.org/?probe=e5f15a17d5) | Feb 02, 2022 |
| Sony          | SVE1713F1EW                 | Notebook    | [34db9cd3c0](https://linux-hardware.org/?probe=34db9cd3c0) | Feb 01, 2022 |
| Sony          | VGN-FE31H                   | Notebook    | [a7185cc26a](https://linux-hardware.org/?probe=a7185cc26a) | Feb 01, 2022 |
| Sony          | SVE1713F1EW                 | Notebook    | [591b6e4d01](https://linux-hardware.org/?probe=591b6e4d01) | Feb 01, 2022 |
| BESSTAR Te... | UM300 V1.0                  | Desktop     | [13b724ceeb](https://linux-hardware.org/?probe=13b724ceeb) | Feb 01, 2022 |
| Dell          | 0M863N A00                  | Desktop     | [7b6c2d4857](https://linux-hardware.org/?probe=7b6c2d4857) | Feb 01, 2022 |
| EVGA          | 131-HE-E095                 | Desktop     | [6d45d47131](https://linux-hardware.org/?probe=6d45d47131) | Jan 31, 2022 |
| Unknown       | Unknown                     | Notebook    | [f3b0dd4384](https://linux-hardware.org/?probe=f3b0dd4384) | Jan 31, 2022 |
| BESSTAR Te... | UM300 V1.0                  | Desktop     | [66320a8981](https://linux-hardware.org/?probe=66320a8981) | Jan 31, 2022 |
| MSI           | GE70 2OC\2OD\2OE            | Notebook    | [f9efba7bbf](https://linux-hardware.org/?probe=f9efba7bbf) | Jan 30, 2022 |
| Sony          | SVE1712W1EB                 | Notebook    | [c6b525e9c3](https://linux-hardware.org/?probe=c6b525e9c3) | Jan 29, 2022 |
| Sony          | SVE1712W1EB                 | Notebook    | [c780c90c73](https://linux-hardware.org/?probe=c780c90c73) | Jan 29, 2022 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | Desktop     | [9cc991a921](https://linux-hardware.org/?probe=9cc991a921) | Jan 29, 2022 |
| Apple         | MacBookPro9,1               | Notebook    | [857a74feaa](https://linux-hardware.org/?probe=857a74feaa) | Jan 28, 2022 |
| Sony          | VGN-FE31H                   | Notebook    | [a53478c6b1](https://linux-hardware.org/?probe=a53478c6b1) | Jan 28, 2022 |
| Sony          | VGN-FE31H                   | Notebook    | [90e1046590](https://linux-hardware.org/?probe=90e1046590) | Jan 28, 2022 |
| ASUSTek       | X551CA                      | Notebook    | [0cb832f85f](https://linux-hardware.org/?probe=0cb832f85f) | Jan 27, 2022 |
| ASUSTek       | ZenBook UX325UAZ_UM325UA... | Notebook    | [7a90772bfd](https://linux-hardware.org/?probe=7a90772bfd) | Jan 27, 2022 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Server      | [de8d4d24b6](https://linux-hardware.org/?probe=de8d4d24b6) | Jan 27, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [9091cc83ba](https://linux-hardware.org/?probe=9091cc83ba) | Jan 26, 2022 |
| Lenovo        | Legion 5P 15IMH05 82AW      | Notebook    | [1abbb329fa](https://linux-hardware.org/?probe=1abbb329fa) | Jan 26, 2022 |
| HP            | Pavilion dv7                | Notebook    | [c639bc4c98](https://linux-hardware.org/?probe=c639bc4c98) | Jan 25, 2022 |
| HP            | ProBook 6570b               | Notebook    | [681a804c88](https://linux-hardware.org/?probe=681a804c88) | Jan 24, 2022 |
| Lenovo        | ThinkPad X250 20CMS02F00    | Notebook    | [e4d90a5ae8](https://linux-hardware.org/?probe=e4d90a5ae8) | Jan 23, 2022 |
| Lenovo        | ThinkPad T420 423664U       | Notebook    | [0e2bb9a59f](https://linux-hardware.org/?probe=0e2bb9a59f) | Jan 23, 2022 |
| Medion        | BTDD-EAIO                   | All in one  | [19e17713b3](https://linux-hardware.org/?probe=19e17713b3) | Jan 22, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [6610c7d6e1](https://linux-hardware.org/?probe=6610c7d6e1) | Jan 22, 2022 |
| Dell          | XPS 13 9350                 | Notebook    | [485c5e0968](https://linux-hardware.org/?probe=485c5e0968) | Jan 21, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [db0cc3978c](https://linux-hardware.org/?probe=db0cc3978c) | Jan 21, 2022 |
| Dell          | Latitude E6530              | Notebook    | [bf71e70abb](https://linux-hardware.org/?probe=bf71e70abb) | Jan 21, 2022 |
| Lenovo        | ThinkPad P17 Gen 1 20SNC... | Notebook    | [0b0ddf4175](https://linux-hardware.org/?probe=0b0ddf4175) | Jan 21, 2022 |
| Medion        | BTDD-EAIO                   | All in one  | [acee4deb32](https://linux-hardware.org/?probe=acee4deb32) | Jan 21, 2022 |
| ASUSTek       | GL552VW                     | Notebook    | [4544642750](https://linux-hardware.org/?probe=4544642750) | Jan 20, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [6edcdd522d](https://linux-hardware.org/?probe=6edcdd522d) | Jan 19, 2022 |
| Packard Be... | IMEDIA S3840                | Desktop     | [4c9e934fd0](https://linux-hardware.org/?probe=4c9e934fd0) | Jan 19, 2022 |
| Packard Be... | IMEDIA S3840                | Desktop     | [9c5aa67db5](https://linux-hardware.org/?probe=9c5aa67db5) | Jan 19, 2022 |
| Dell          | Latitude E6530              | Notebook    | [8559d4a5b0](https://linux-hardware.org/?probe=8559d4a5b0) | Jan 19, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [211aac7b59](https://linux-hardware.org/?probe=211aac7b59) | Jan 18, 2022 |
| MSI           | Z170A GAMING M3             | Desktop     | [57e7500f2a](https://linux-hardware.org/?probe=57e7500f2a) | Jan 17, 2022 |
| Medion        | B250H4-EM                   | Desktop     | [2dc4d456bb](https://linux-hardware.org/?probe=2dc4d456bb) | Jan 17, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [cf36481feb](https://linux-hardware.org/?probe=cf36481feb) | Jan 16, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [d6594c7edb](https://linux-hardware.org/?probe=d6594c7edb) | Jan 15, 2022 |
| Dell          | Latitude 5520               | Notebook    | [95721c3566](https://linux-hardware.org/?probe=95721c3566) | Jan 15, 2022 |
| ASUSTek       | X580VD                      | Notebook    | [9cb7ebea38](https://linux-hardware.org/?probe=9cb7ebea38) | Jan 14, 2022 |
| HP            | EliteBook 830 G8 Noteboo... | Notebook    | [e293ddf5fc](https://linux-hardware.org/?probe=e293ddf5fc) | Jan 14, 2022 |
| Dell          | Latitude 7490               | Notebook    | [98c318edfd](https://linux-hardware.org/?probe=98c318edfd) | Jan 13, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [de24bac4e8](https://linux-hardware.org/?probe=de24bac4e8) | Jan 13, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [7edab0851b](https://linux-hardware.org/?probe=7edab0851b) | Jan 12, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [66d12682ac](https://linux-hardware.org/?probe=66d12682ac) | Jan 10, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [5d7aaea168](https://linux-hardware.org/?probe=5d7aaea168) | Jan 10, 2022 |
| Apple         | Mac-F2208EC8                | Mini pc     | [cf21ff9bc1](https://linux-hardware.org/?probe=cf21ff9bc1) | Jan 09, 2022 |
| Intel         | DP55WB AAE64798-205         | Desktop     | [7e26a217f2](https://linux-hardware.org/?probe=7e26a217f2) | Jan 09, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [2f505d02d9](https://linux-hardware.org/?probe=2f505d02d9) | Jan 09, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [b51f64610b](https://linux-hardware.org/?probe=b51f64610b) | Jan 09, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [62c4e26a01](https://linux-hardware.org/?probe=62c4e26a01) | Jan 09, 2022 |
| ASUSTek       | GL552VW                     | Notebook    | [69a4959007](https://linux-hardware.org/?probe=69a4959007) | Jan 09, 2022 |
| Apple         | Mac-F2208EC8                | Mini pc     | [ddb6347103](https://linux-hardware.org/?probe=ddb6347103) | Jan 09, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [83ccc00b28](https://linux-hardware.org/?probe=83ccc00b28) | Jan 08, 2022 |
| Dell          | Latitude E6330              | Notebook    | [da29c6f100](https://linux-hardware.org/?probe=da29c6f100) | Jan 08, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [85fc03c636](https://linux-hardware.org/?probe=85fc03c636) | Jan 08, 2022 |
| ASRock        | Q1900-ITX                   | Desktop     | [a0983541e3](https://linux-hardware.org/?probe=a0983541e3) | Jan 08, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [5ed2055b1e](https://linux-hardware.org/?probe=5ed2055b1e) | Jan 08, 2022 |
| Gigabyte      | B460M DS3H                  | Desktop     | [40f4de9da7](https://linux-hardware.org/?probe=40f4de9da7) | Jan 07, 2022 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | Notebook    | [95c067b96e](https://linux-hardware.org/?probe=95c067b96e) | Jan 07, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [5b879a9c87](https://linux-hardware.org/?probe=5b879a9c87) | Jan 07, 2022 |
| HP            | Compaq 8710w                | Notebook    | [ab5f731d97](https://linux-hardware.org/?probe=ab5f731d97) | Jan 05, 2022 |
| ASRock        | Q1900-ITX                   | Desktop     | [e7b19454b7](https://linux-hardware.org/?probe=e7b19454b7) | Jan 04, 2022 |
| Acer          | Aspire 7520                 | Notebook    | [462c034a56](https://linux-hardware.org/?probe=462c034a56) | Jan 04, 2022 |
| HP            | Compaq 8710w                | Notebook    | [573e8e760f](https://linux-hardware.org/?probe=573e8e760f) | Jan 03, 2022 |
| Dell          | Latitude E6510              | Notebook    | [7a6c58b609](https://linux-hardware.org/?probe=7a6c58b609) | Jan 02, 2022 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [e6e4d232a9](https://linux-hardware.org/?probe=e6e4d232a9) | Jan 02, 2022 |
| HP            | EliteBook 6930p (GB995EA... | Notebook    | [e0a482ab1e](https://linux-hardware.org/?probe=e0a482ab1e) | Jan 02, 2022 |
| Intel         | NUC5i3RYB K23918-501        | Mini pc     | [dd99198f60](https://linux-hardware.org/?probe=dd99198f60) | Dec 31, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [211b09522f](https://linux-hardware.org/?probe=211b09522f) | Dec 31, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [7376dd6793](https://linux-hardware.org/?probe=7376dd6793) | Dec 29, 2021 |
| Dell          | 0HX555                      | Desktop     | [f8ad9742a7](https://linux-hardware.org/?probe=f8ad9742a7) | Dec 28, 2021 |
| Packard Be... | EasyNote TK85               | Notebook    | [cef3f4f826](https://linux-hardware.org/?probe=cef3f4f826) | Dec 28, 2021 |
| HP            | ProBook 4730s               | Notebook    | [08cca0b4b5](https://linux-hardware.org/?probe=08cca0b4b5) | Dec 28, 2021 |
| Lenovo        | ThinkPad L540 20AV0031MB    | Notebook    | [5abe6c6347](https://linux-hardware.org/?probe=5abe6c6347) | Dec 28, 2021 |
| ASUSTek       | X302LA                      | Notebook    | [3c747e6bb0](https://linux-hardware.org/?probe=3c747e6bb0) | Dec 28, 2021 |
| HP            | EliteBook 850 G5            | Notebook    | [f385608043](https://linux-hardware.org/?probe=f385608043) | Dec 28, 2021 |
| Sony          | VPCEL1E1E                   | Notebook    | [4deb7655c4](https://linux-hardware.org/?probe=4deb7655c4) | Dec 27, 2021 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [23460afe38](https://linux-hardware.org/?probe=23460afe38) | Dec 27, 2021 |
| Lenovo        | ThinkPad W520 42844LG       | Notebook    | [0af1aded1f](https://linux-hardware.org/?probe=0af1aded1f) | Dec 27, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [4fe24b4f44](https://linux-hardware.org/?probe=4fe24b4f44) | Dec 26, 2021 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [54774d551c](https://linux-hardware.org/?probe=54774d551c) | Dec 26, 2021 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [05b30c96fd](https://linux-hardware.org/?probe=05b30c96fd) | Dec 26, 2021 |
| ASUSTek       | ROG STRIX B460-I GAMING     | Desktop     | [88ecd12a4e](https://linux-hardware.org/?probe=88ecd12a4e) | Dec 26, 2021 |
| Intel         | DG965WH AAD41692-304        | Desktop     | [e53228af1f](https://linux-hardware.org/?probe=e53228af1f) | Dec 25, 2021 |
| Apple         | MacBookPro10,1              | Notebook    | [381c7dee2d](https://linux-hardware.org/?probe=381c7dee2d) | Dec 25, 2021 |
| HP            | ProBook 640 G4              | Notebook    | [f1fa3d65b1](https://linux-hardware.org/?probe=f1fa3d65b1) | Dec 25, 2021 |
| HP            | 3398                        | Desktop     | [759e3821b8](https://linux-hardware.org/?probe=759e3821b8) | Dec 22, 2021 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [14d7bc4e66](https://linux-hardware.org/?probe=14d7bc4e66) | Dec 22, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [d4fcc94659](https://linux-hardware.org/?probe=d4fcc94659) | Dec 22, 2021 |
| MSI           | GE72 6QC                    | Notebook    | [4c5a8f6b4a](https://linux-hardware.org/?probe=4c5a8f6b4a) | Dec 21, 2021 |
| Notebook      | NH5x_NH7xHP                 | Notebook    | [0408aca941](https://linux-hardware.org/?probe=0408aca941) | Dec 21, 2021 |
| HP            | ENVY Laptop 13-aq1xxx       | Notebook    | [88a4b38685](https://linux-hardware.org/?probe=88a4b38685) | Dec 21, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [03abaff4ae](https://linux-hardware.org/?probe=03abaff4ae) | Dec 21, 2021 |
| HP            | G62                         | Notebook    | [fac3d0a6b6](https://linux-hardware.org/?probe=fac3d0a6b6) | Dec 21, 2021 |
| ASUSTek       | N501JW                      | Notebook    | [2b928f1e66](https://linux-hardware.org/?probe=2b928f1e66) | Dec 19, 2021 |
| Toshiba       | Satellite C50-B             | Notebook    | [9da235adb3](https://linux-hardware.org/?probe=9da235adb3) | Dec 19, 2021 |
| Toshiba       | Satellite C50-B             | Notebook    | [037f47a340](https://linux-hardware.org/?probe=037f47a340) | Dec 19, 2021 |
| Google        | Pantheon                    | Notebook    | [8b1d8783ad](https://linux-hardware.org/?probe=8b1d8783ad) | Dec 17, 2021 |
| HP            | Pavilion dv7                | Notebook    | [0e0f0e3c23](https://linux-hardware.org/?probe=0e0f0e3c23) | Dec 15, 2021 |
| Intel         | DH55TC AAE70932-302         | Desktop     | [d08d387e5b](https://linux-hardware.org/?probe=d08d387e5b) | Dec 15, 2021 |
| Intel         | DH55TC AAE70932-302         | Desktop     | [e659faacc7](https://linux-hardware.org/?probe=e659faacc7) | Dec 15, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [b14b8a40ec](https://linux-hardware.org/?probe=b14b8a40ec) | Dec 12, 2021 |
| Acer          | Swift SF113-31              | Notebook    | [e951b45254](https://linux-hardware.org/?probe=e951b45254) | Dec 12, 2021 |
| Clevo         | W270HU                      | Notebook    | [486cbb154a](https://linux-hardware.org/?probe=486cbb154a) | Dec 12, 2021 |
| Dell          | Latitude E5410              | Notebook    | [8b6bc5cf8e](https://linux-hardware.org/?probe=8b6bc5cf8e) | Dec 12, 2021 |
| Clevo         | W270HU                      | Notebook    | [5152801cbe](https://linux-hardware.org/?probe=5152801cbe) | Dec 10, 2021 |
| MSI           | B85-G41 PC Mate             | Desktop     | [1440a6309d](https://linux-hardware.org/?probe=1440a6309d) | Dec 10, 2021 |
| Lenovo        | ThinkPad W530 244743G       | Notebook    | [4aff204627](https://linux-hardware.org/?probe=4aff204627) | Dec 10, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [77ee4f08a8](https://linux-hardware.org/?probe=77ee4f08a8) | Dec 10, 2021 |
| ASUSTek       | M4N68T-M                    | Desktop     | [2eb06a60de](https://linux-hardware.org/?probe=2eb06a60de) | Dec 10, 2021 |
| Intel         | NUC5i7RYB H73774-102        | Mini pc     | [9115bc7a4e](https://linux-hardware.org/?probe=9115bc7a4e) | Dec 09, 2021 |
| Intel         | DG31PR AAD97573-206         | Desktop     | [0b9336e2b8](https://linux-hardware.org/?probe=0b9336e2b8) | Dec 08, 2021 |
| Lenovo        | ThinkPad X280 20KES94F05    | Notebook    | [ba3d89dca3](https://linux-hardware.org/?probe=ba3d89dca3) | Dec 08, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [032805bb35](https://linux-hardware.org/?probe=032805bb35) | Dec 08, 2021 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [78b37822bc](https://linux-hardware.org/?probe=78b37822bc) | Dec 08, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [211486de2c](https://linux-hardware.org/?probe=211486de2c) | Dec 05, 2021 |
| Medion        | B360H4-EM V1.0              | Desktop     | [5f5964c9a4](https://linux-hardware.org/?probe=5f5964c9a4) | Dec 05, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [fb84f5c3c5](https://linux-hardware.org/?probe=fb84f5c3c5) | Dec 05, 2021 |
| MSI           | Z370 KRAIT GAMING           | Desktop     | [b213dc07b8](https://linux-hardware.org/?probe=b213dc07b8) | Dec 04, 2021 |
| HP            | ProBook 470 G5              | Notebook    | [1cfd3aadd8](https://linux-hardware.org/?probe=1cfd3aadd8) | Dec 04, 2021 |
| Acer          | Aspire A315-21              | Notebook    | [322f9afcb0](https://linux-hardware.org/?probe=322f9afcb0) | Dec 04, 2021 |
| MSI           | Z370 KRAIT GAMING           | Desktop     | [b562e90f75](https://linux-hardware.org/?probe=b562e90f75) | Dec 04, 2021 |
| Gigabyte      | Z87X-UD3H-CF                | Desktop     | [5efc3e5fc4](https://linux-hardware.org/?probe=5efc3e5fc4) | Dec 03, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [8f978c02bd](https://linux-hardware.org/?probe=8f978c02bd) | Dec 03, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [df01b853dd](https://linux-hardware.org/?probe=df01b853dd) | Dec 03, 2021 |
| Gigabyte      | GA-MA74GM-S2H               | Desktop     | [bd33efb6f7](https://linux-hardware.org/?probe=bd33efb6f7) | Dec 01, 2021 |
| Acer          | Aspire 7736                 | Notebook    | [20d3c3fff5](https://linux-hardware.org/?probe=20d3c3fff5) | Dec 01, 2021 |
| Celestica     | D4040                       | Notebook    | [109f886f1d](https://linux-hardware.org/?probe=109f886f1d) | Nov 30, 2021 |
| ASRock        | Z87 Extreme4                | Desktop     | [2eb7265c5e](https://linux-hardware.org/?probe=2eb7265c5e) | Nov 30, 2021 |
| ASRock        | Z87 Extreme4                | Desktop     | [c131e8ee89](https://linux-hardware.org/?probe=c131e8ee89) | Nov 30, 2021 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | Notebook    | [3a85954b66](https://linux-hardware.org/?probe=3a85954b66) | Nov 29, 2021 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | Notebook    | [5271c46262](https://linux-hardware.org/?probe=5271c46262) | Nov 29, 2021 |
| HP            | ProBook 640 G4              | Notebook    | [e58b0e7945](https://linux-hardware.org/?probe=e58b0e7945) | Nov 29, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [6e63fb12a3](https://linux-hardware.org/?probe=6e63fb12a3) | Nov 28, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [73dbadb8f1](https://linux-hardware.org/?probe=73dbadb8f1) | Nov 28, 2021 |
| HP            | Compaq 6720s                | Notebook    | [2c62d9df9c](https://linux-hardware.org/?probe=2c62d9df9c) | Nov 28, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3d1d036e1e](https://linux-hardware.org/?probe=3d1d036e1e) | Nov 27, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [2f2ac97b5b](https://linux-hardware.org/?probe=2f2ac97b5b) | Nov 26, 2021 |
| Dell          | 0200DY A03                  | Desktop     | [d4ebf48195](https://linux-hardware.org/?probe=d4ebf48195) | Nov 26, 2021 |
| Dell          | Latitude 5580               | Notebook    | [a10f022f63](https://linux-hardware.org/?probe=a10f022f63) | Nov 26, 2021 |
| Toshiba       | Satellite A300              | Notebook    | [c62dc3b138](https://linux-hardware.org/?probe=c62dc3b138) | Nov 25, 2021 |
| Medion        | H110H4-EM                   | Desktop     | [8b1485f27d](https://linux-hardware.org/?probe=8b1485f27d) | Nov 25, 2021 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [126787ad75](https://linux-hardware.org/?probe=126787ad75) | Nov 24, 2021 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [05fcb362a6](https://linux-hardware.org/?probe=05fcb362a6) | Nov 24, 2021 |
| HP            | EliteBook 735 G5            | Notebook    | [d80b574cb4](https://linux-hardware.org/?probe=d80b574cb4) | Nov 24, 2021 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Server      | [5416eaf379](https://linux-hardware.org/?probe=5416eaf379) | Nov 23, 2021 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Server      | [ed0dd14ccd](https://linux-hardware.org/?probe=ed0dd14ccd) | Nov 23, 2021 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [6994e8dbb3](https://linux-hardware.org/?probe=6994e8dbb3) | Nov 23, 2021 |
| ASUSTek       | GL552VW                     | Notebook    | [59670a3933](https://linux-hardware.org/?probe=59670a3933) | Nov 23, 2021 |
| Microsoft     | Surface Pro 4               | Tablet      | [5aed957968](https://linux-hardware.org/?probe=5aed957968) | Nov 23, 2021 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [fbc257563e](https://linux-hardware.org/?probe=fbc257563e) | Nov 22, 2021 |
| Gigabyte      | F2A85XM-D3H                 | Desktop     | [1c41d8c34c](https://linux-hardware.org/?probe=1c41d8c34c) | Nov 22, 2021 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [8c5bc064e9](https://linux-hardware.org/?probe=8c5bc064e9) | Nov 21, 2021 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [d1d161f6ad](https://linux-hardware.org/?probe=d1d161f6ad) | Nov 21, 2021 |
| Lenovo        | ThinkPad X1 Yoga Gen 6 2... | Convertible | [5933792dbf](https://linux-hardware.org/?probe=5933792dbf) | Nov 21, 2021 |
| Dell          | Latitude D630               | Notebook    | [0d437ca2f6](https://linux-hardware.org/?probe=0d437ca2f6) | Nov 21, 2021 |
| Notebook      | PA70ES                      | Notebook    | [55d43af19e](https://linux-hardware.org/?probe=55d43af19e) | Nov 20, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII EXTRE... | Desktop     | [efea8a4f1a](https://linux-hardware.org/?probe=efea8a4f1a) | Nov 18, 2021 |
| Lenovo        | ThinkPad E495 20NES01600    | Notebook    | [aacc57f134](https://linux-hardware.org/?probe=aacc57f134) | Nov 17, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [ddfb1c2b1a](https://linux-hardware.org/?probe=ddfb1c2b1a) | Nov 17, 2021 |
| Notebook      | N24_25JU                    | Notebook    | [30df18e398](https://linux-hardware.org/?probe=30df18e398) | Nov 16, 2021 |
| Teclast       | F6 Plus                     | Notebook    | [7e5836dbaa](https://linux-hardware.org/?probe=7e5836dbaa) | Nov 16, 2021 |
| Intel         | DG31PR AAD97573-206         | Desktop     | [e6cd09e40a](https://linux-hardware.org/?probe=e6cd09e40a) | Nov 16, 2021 |
| Gigabyte      | B85M-HD3                    | Desktop     | [73ff149bf3](https://linux-hardware.org/?probe=73ff149bf3) | Nov 16, 2021 |
| Dell          | Latitude D620               | Notebook    | [855218ab46](https://linux-hardware.org/?probe=855218ab46) | Nov 16, 2021 |
| ASUSTek       | Strix GL703GS_GL703GS       | Notebook    | [6eb0749ee8](https://linux-hardware.org/?probe=6eb0749ee8) | Nov 15, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [2142069a51](https://linux-hardware.org/?probe=2142069a51) | Nov 13, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [5f21c28c3a](https://linux-hardware.org/?probe=5f21c28c3a) | Nov 12, 2021 |
| ASUSTek       | X75VC                       | Notebook    | [39352780e5](https://linux-hardware.org/?probe=39352780e5) | Nov 12, 2021 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [51dd491e34](https://linux-hardware.org/?probe=51dd491e34) | Nov 11, 2021 |
| Packard Be... | EasyNote TE11BZ             | Notebook    | [de427e19ea](https://linux-hardware.org/?probe=de427e19ea) | Nov 11, 2021 |
| Lenovo        | ThinkPad T61 64669YG        | Notebook    | [0cbad8aae1](https://linux-hardware.org/?probe=0cbad8aae1) | Nov 11, 2021 |
| Acer          | AO751h                      | Notebook    | [e2beb798cc](https://linux-hardware.org/?probe=e2beb798cc) | Nov 10, 2021 |
| Fujitsu       | D3433-S2 S26361-D3433-S2    | Desktop     | [a9a66b59f1](https://linux-hardware.org/?probe=a9a66b59f1) | Nov 09, 2021 |
| Packard Be... | IXTREME M5800               | Desktop     | [b52db0ec1d](https://linux-hardware.org/?probe=b52db0ec1d) | Nov 09, 2021 |
| Medion        | H110H4-EM                   | Desktop     | [3ecf7775d6](https://linux-hardware.org/?probe=3ecf7775d6) | Nov 09, 2021 |
| Sony          | VPCF13M1E                   | Notebook    | [9858905cc2](https://linux-hardware.org/?probe=9858905cc2) | Nov 09, 2021 |
| Toshiba       | TECRA W50-A                 | Notebook    | [abee9f36ad](https://linux-hardware.org/?probe=abee9f36ad) | Nov 05, 2021 |
| Unknown       | Unknown                     | Notebook    | [ed806d64c8](https://linux-hardware.org/?probe=ed806d64c8) | Nov 05, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [4f70ff5761](https://linux-hardware.org/?probe=4f70ff5761) | Nov 04, 2021 |
| Intel         | NUC7i5BNB J31144-304        | Mini pc     | [4bbc26f44b](https://linux-hardware.org/?probe=4bbc26f44b) | Nov 04, 2021 |
| Gigabyte      | Spring Peak                 | Notebook    | [fc1efa8df5](https://linux-hardware.org/?probe=fc1efa8df5) | Nov 04, 2021 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [4478f8c509](https://linux-hardware.org/?probe=4478f8c509) | Nov 03, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | Desktop     | [276bfdb97e](https://linux-hardware.org/?probe=276bfdb97e) | Nov 03, 2021 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [209a1faa74](https://linux-hardware.org/?probe=209a1faa74) | Nov 02, 2021 |
| Lenovo        | Yoga 510-14IKB 80VB         | Convertible | [d1313d684c](https://linux-hardware.org/?probe=d1313d684c) | Nov 01, 2021 |
| Intel         | DG31PR AAD97573-206         | Desktop     | [7ca61ca6e1](https://linux-hardware.org/?probe=7ca61ca6e1) | Oct 31, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b2d3620851](https://linux-hardware.org/?probe=b2d3620851) | Oct 31, 2021 |
| Lenovo        | Yoga 510-14IKB 80VB         | Convertible | [5154e96abe](https://linux-hardware.org/?probe=5154e96abe) | Oct 31, 2021 |
| ASUSTek       | PRIME H310T R2.0            | Desktop     | [9f69e439bc](https://linux-hardware.org/?probe=9f69e439bc) | Oct 30, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [735015dce2](https://linux-hardware.org/?probe=735015dce2) | Oct 30, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [2ecc44141a](https://linux-hardware.org/?probe=2ecc44141a) | Oct 30, 2021 |
| Medion        | E3216 MD61800               | Convertible | [02e94e7cd4](https://linux-hardware.org/?probe=02e94e7cd4) | Oct 30, 2021 |
| HP            | ZBook Studio G4             | Notebook    | [984d3cdc29](https://linux-hardware.org/?probe=984d3cdc29) | Oct 30, 2021 |
| Medion        | E3216 MD61800               | Convertible | [cab2bcc5ee](https://linux-hardware.org/?probe=cab2bcc5ee) | Oct 29, 2021 |
| ASUSTek       | TUF Z270 MARK 1             | Desktop     | [f60a34fe5c](https://linux-hardware.org/?probe=f60a34fe5c) | Oct 28, 2021 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [66fa4360dd](https://linux-hardware.org/?probe=66fa4360dd) | Oct 27, 2021 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [3f5dd495d5](https://linux-hardware.org/?probe=3f5dd495d5) | Oct 27, 2021 |
| Lenovo        | G570 4334                   | Notebook    | [cc07ebf9b6](https://linux-hardware.org/?probe=cc07ebf9b6) | Oct 27, 2021 |
| Lenovo        | ThinkPad E560 20EV000NIV    | Notebook    | [65eac6abc6](https://linux-hardware.org/?probe=65eac6abc6) | Oct 27, 2021 |
| ASUSTek       | TUF X299 MARK 1             | Desktop     | [6fc3b2d35d](https://linux-hardware.org/?probe=6fc3b2d35d) | Oct 26, 2021 |
| Unknown       | Unknown                     | Desktop     | [3313aa3c86](https://linux-hardware.org/?probe=3313aa3c86) | Oct 26, 2021 |
| Unknown       | Unknown                     | Desktop     | [668f61352d](https://linux-hardware.org/?probe=668f61352d) | Oct 26, 2021 |
| ASUSTek       | Leonite2                    | Desktop     | [1f00f6d692](https://linux-hardware.org/?probe=1f00f6d692) | Oct 26, 2021 |
| Dell          | Latitude 7390               | Notebook    | [92dcb677f7](https://linux-hardware.org/?probe=92dcb677f7) | Oct 26, 2021 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [39e318621b](https://linux-hardware.org/?probe=39e318621b) | Oct 26, 2021 |
| Notebook      | P7xxDM3(-G)                 | Notebook    | [5c62ec0ce3](https://linux-hardware.org/?probe=5c62ec0ce3) | Oct 24, 2021 |
| Dell          | Studio 1555                 | Notebook    | [3fed161971](https://linux-hardware.org/?probe=3fed161971) | Oct 24, 2021 |
| HP            | ProBook 4540s               | Notebook    | [49ce392cd2](https://linux-hardware.org/?probe=49ce392cd2) | Oct 24, 2021 |
| ASUSTek       | H110M-C                     | Desktop     | [ba3ddf870d](https://linux-hardware.org/?probe=ba3ddf870d) | Oct 24, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | Desktop     | [fac95138dc](https://linux-hardware.org/?probe=fac95138dc) | Oct 23, 2021 |
| HP            | ProBook 470 G5              | Notebook    | [725627d16b](https://linux-hardware.org/?probe=725627d16b) | Oct 23, 2021 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [2b043d7a15](https://linux-hardware.org/?probe=2b043d7a15) | Oct 23, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [fe7a37dce1](https://linux-hardware.org/?probe=fe7a37dce1) | Oct 22, 2021 |
| Notebook      | P7xxDM3(-G)                 | Notebook    | [250e2a46b0](https://linux-hardware.org/?probe=250e2a46b0) | Oct 22, 2021 |
| Dell          | 0KFKMF A00                  | All in one  | [4c88b83358](https://linux-hardware.org/?probe=4c88b83358) | Oct 21, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [86bc5ddc56](https://linux-hardware.org/?probe=86bc5ddc56) | Oct 21, 2021 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [44537c7fba](https://linux-hardware.org/?probe=44537c7fba) | Oct 20, 2021 |
| Notebook      | PB50_70RF,RD,RC             | Notebook    | [ec41eeb7c0](https://linux-hardware.org/?probe=ec41eeb7c0) | Oct 20, 2021 |
| ASUSTek       | K72F                        | Notebook    | [0eedfc8a67](https://linux-hardware.org/?probe=0eedfc8a67) | Oct 20, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [2412314ad9](https://linux-hardware.org/?probe=2412314ad9) | Oct 18, 2021 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [57260c1999](https://linux-hardware.org/?probe=57260c1999) | Oct 18, 2021 |
| Medion        | BTDD-EAIO                   | All in one  | [f04d685411](https://linux-hardware.org/?probe=f04d685411) | Oct 18, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [7075439e69](https://linux-hardware.org/?probe=7075439e69) | Oct 17, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [5c4edf2e8d](https://linux-hardware.org/?probe=5c4edf2e8d) | Oct 17, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [20c432ef7d](https://linux-hardware.org/?probe=20c432ef7d) | Oct 17, 2021 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [274cba3955](https://linux-hardware.org/?probe=274cba3955) | Oct 17, 2021 |
| Acer          | Nitro AN515-55              | Notebook    | [9bf062da25](https://linux-hardware.org/?probe=9bf062da25) | Oct 16, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [69fc64df8b](https://linux-hardware.org/?probe=69fc64df8b) | Oct 16, 2021 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [a402bb261d](https://linux-hardware.org/?probe=a402bb261d) | Oct 15, 2021 |
| HP            | ProBook 4540s               | Notebook    | [046acc5982](https://linux-hardware.org/?probe=046acc5982) | Oct 14, 2021 |
| Gigabyte      | Z270X-Gaming K5             | Desktop     | [6096718e44](https://linux-hardware.org/?probe=6096718e44) | Oct 13, 2021 |
| Gigabyte      | Z270X-Gaming K5             | Desktop     | [b935797d2e](https://linux-hardware.org/?probe=b935797d2e) | Oct 13, 2021 |
| MSI           | 2AE0                        | Desktop     | [eb0924e07d](https://linux-hardware.org/?probe=eb0924e07d) | Oct 12, 2021 |
| MSI           | 2AE0                        | Desktop     | [e39aeb8c18](https://linux-hardware.org/?probe=e39aeb8c18) | Oct 12, 2021 |
| Gigabyte      | B85M-HD3                    | Desktop     | [47185d16f7](https://linux-hardware.org/?probe=47185d16f7) | Oct 11, 2021 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [a5072cec8c](https://linux-hardware.org/?probe=a5072cec8c) | Oct 10, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | Desktop     | [e2dff5f003](https://linux-hardware.org/?probe=e2dff5f003) | Oct 10, 2021 |
| Lenovo        | ThinkPad E560 20EV000NIV    | Notebook    | [4bb69f9fcc](https://linux-hardware.org/?probe=4bb69f9fcc) | Oct 10, 2021 |
| Acer          | Aspire C24-963              | All in one  | [9b4659e4dd](https://linux-hardware.org/?probe=9b4659e4dd) | Oct 09, 2021 |
| Lenovo        | ThinkPad L390 20NSS1YV0B    | Notebook    | [bf3209df55](https://linux-hardware.org/?probe=bf3209df55) | Oct 07, 2021 |
| Acer          | Aspire C24-963              | All in one  | [215146c423](https://linux-hardware.org/?probe=215146c423) | Oct 06, 2021 |
| Intel         | NUC7i5BNB J31144-304        | Mini pc     | [a392dd59eb](https://linux-hardware.org/?probe=a392dd59eb) | Oct 06, 2021 |
| Dell          | 0200DY A03                  | Desktop     | [999feee9dc](https://linux-hardware.org/?probe=999feee9dc) | Oct 04, 2021 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [03ba78f145](https://linux-hardware.org/?probe=03ba78f145) | Oct 04, 2021 |
| ASUSTek       | N76VZ                       | Notebook    | [8e260cdbc8](https://linux-hardware.org/?probe=8e260cdbc8) | Oct 04, 2021 |
| ASUSTek       | N76VZ                       | Notebook    | [94e6fbc140](https://linux-hardware.org/?probe=94e6fbc140) | Oct 03, 2021 |
| HP            | ProLiant ML350 G6           | Desktop     | [26ff13863b](https://linux-hardware.org/?probe=26ff13863b) | Oct 03, 2021 |
| HP            | ProLiant ML350 G6           | Desktop     | [2645539128](https://linux-hardware.org/?probe=2645539128) | Oct 03, 2021 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [0e54f43704](https://linux-hardware.org/?probe=0e54f43704) | Oct 02, 2021 |
| Google        | Pantheon                    | Notebook    | [72ded95fab](https://linux-hardware.org/?probe=72ded95fab) | Oct 02, 2021 |
| HP            | ProBook 470 G5              | Notebook    | [fef4cfba03](https://linux-hardware.org/?probe=fef4cfba03) | Oct 02, 2021 |
| Dell          | 0200DY A03                  | Desktop     | [270938ccab](https://linux-hardware.org/?probe=270938ccab) | Oct 02, 2021 |
| Notebook      | NH5x_NH7xHP                 | Notebook    | [f6fd6bd3dc](https://linux-hardware.org/?probe=f6fd6bd3dc) | Oct 02, 2021 |
| Notebook      | NH5x_NH7xHP                 | Notebook    | [fbcd6bfe42](https://linux-hardware.org/?probe=fbcd6bfe42) | Oct 02, 2021 |
| Gigabyte      | X79-UP4                     | Desktop     | [349f8dbe53](https://linux-hardware.org/?probe=349f8dbe53) | Oct 01, 2021 |
| Lenovo        | Legion 5P 15IMH05 82AW      | Notebook    | [fbade9e61e](https://linux-hardware.org/?probe=fbade9e61e) | Oct 01, 2021 |
| ASUSTek       | X555LJ                      | Notebook    | [dea4201e98](https://linux-hardware.org/?probe=dea4201e98) | Oct 01, 2021 |
| Foxconn       | 2ABF                        | Desktop     | [de498adb08](https://linux-hardware.org/?probe=de498adb08) | Sep 30, 2021 |
| Notebook      | P7xxTM1                     | Notebook    | [a63472fe1d](https://linux-hardware.org/?probe=a63472fe1d) | Sep 30, 2021 |
| HP            | ProLiant ML350 G6           | Desktop     | [a7ccd5b628](https://linux-hardware.org/?probe=a7ccd5b628) | Sep 30, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [1e96ea621f](https://linux-hardware.org/?probe=1e96ea621f) | Sep 29, 2021 |
| Dell          | Precision 3561              | Notebook    | [59bbb944c2](https://linux-hardware.org/?probe=59bbb944c2) | Sep 29, 2021 |
| Intel         | BTC-T37                     | Desktop     | [773b0505a9](https://linux-hardware.org/?probe=773b0505a9) | Sep 28, 2021 |
| HP            | Elite x2 1012 G1            | Notebook    | [90cbd6d0a7](https://linux-hardware.org/?probe=90cbd6d0a7) | Sep 26, 2021 |
| Apple         | MacBookPro16,2              | Notebook    | [f1c5cf0c43](https://linux-hardware.org/?probe=f1c5cf0c43) | Sep 25, 2021 |
| ASUSTek       | N56VZ                       | Notebook    | [824dc21fac](https://linux-hardware.org/?probe=824dc21fac) | Sep 23, 2021 |
| ASUSTek       | N56VZ                       | Notebook    | [6c4623e356](https://linux-hardware.org/?probe=6c4623e356) | Sep 23, 2021 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | Notebook    | [81c1403674](https://linux-hardware.org/?probe=81c1403674) | Sep 22, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [710301deba](https://linux-hardware.org/?probe=710301deba) | Sep 22, 2021 |
| Lenovo        | 36C5 SDK0J40709 WIN 3259... | Desktop     | [49e564cb99](https://linux-hardware.org/?probe=49e564cb99) | Sep 21, 2021 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [9748894c7e](https://linux-hardware.org/?probe=9748894c7e) | Sep 19, 2021 |
| Google        | Pantheon                    | Notebook    | [eaa5a17c4b](https://linux-hardware.org/?probe=eaa5a17c4b) | Sep 19, 2021 |
| Dell          | Latitude 9510               | Convertible | [f146e46238](https://linux-hardware.org/?probe=f146e46238) | Sep 19, 2021 |
| Dell          | 042P49 A02                  | Desktop     | [7ffbfd1e5a](https://linux-hardware.org/?probe=7ffbfd1e5a) | Sep 18, 2021 |
| Gigabyte      | P35-DS3                     | Desktop     | [32413546ce](https://linux-hardware.org/?probe=32413546ce) | Sep 18, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [67449a33dc](https://linux-hardware.org/?probe=67449a33dc) | Sep 18, 2021 |
| ASUSTek       | X540SA                      | Notebook    | [177c537ae0](https://linux-hardware.org/?probe=177c537ae0) | Sep 17, 2021 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [7ab07746a7](https://linux-hardware.org/?probe=7ab07746a7) | Sep 17, 2021 |
| Medion        | H81H3-EM2 H81EM2W08.304     | Desktop     | [ab13892a70](https://linux-hardware.org/?probe=ab13892a70) | Sep 17, 2021 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [094059270a](https://linux-hardware.org/?probe=094059270a) | Sep 16, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [fdcc98fb1d](https://linux-hardware.org/?probe=fdcc98fb1d) | Sep 16, 2021 |
| Gigabyte      | B85M-HD3                    | Desktop     | [87c38c92e2](https://linux-hardware.org/?probe=87c38c92e2) | Sep 16, 2021 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [33e36b0623](https://linux-hardware.org/?probe=33e36b0623) | Sep 15, 2021 |
| Acer          | Aspire XC-830               | Desktop     | [ad445dc43a](https://linux-hardware.org/?probe=ad445dc43a) | Sep 15, 2021 |
| HP            | EliteBook 6930p             | Notebook    | [8f38de340d](https://linux-hardware.org/?probe=8f38de340d) | Sep 15, 2021 |
| Medion        | MS-7797                     | Desktop     | [f2f5579dc5](https://linux-hardware.org/?probe=f2f5579dc5) | Sep 15, 2021 |
| Medion        | MS-7797                     | Desktop     | [6ca6bee736](https://linux-hardware.org/?probe=6ca6bee736) | Sep 15, 2021 |
| Acer          | Aspire C24-963              | All in one  | [01d4780c32](https://linux-hardware.org/?probe=01d4780c32) | Sep 14, 2021 |
| Dell          | Inspiron 14-3452            | Notebook    | [ec9da4ca73](https://linux-hardware.org/?probe=ec9da4ca73) | Sep 14, 2021 |
| Lenovo        | ThinkPad T61 7659AB7        | Notebook    | [3c213b818b](https://linux-hardware.org/?probe=3c213b818b) | Sep 14, 2021 |
| Lenovo        | ThinkPad X390 20Q00058MH    | Notebook    | [01755fd33c](https://linux-hardware.org/?probe=01755fd33c) | Sep 13, 2021 |
| HP            | 872B                        | Desktop     | [1ad7d53f97](https://linux-hardware.org/?probe=1ad7d53f97) | Sep 13, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [0b058e8bd8](https://linux-hardware.org/?probe=0b058e8bd8) | Sep 13, 2021 |
| Medion        | WIM2140                     | Notebook    | [cf2f9bdca7](https://linux-hardware.org/?probe=cf2f9bdca7) | Sep 12, 2021 |
| Medion        | WIM2140                     | Notebook    | [0023f88625](https://linux-hardware.org/?probe=0023f88625) | Sep 12, 2021 |
| ASUSTek       | F70SL                       | Notebook    | [32a3e01bbd](https://linux-hardware.org/?probe=32a3e01bbd) | Sep 12, 2021 |
| ASUSTek       | F70SL                       | Notebook    | [4db3ac07eb](https://linux-hardware.org/?probe=4db3ac07eb) | Sep 12, 2021 |
| ASUSTek       | H110M-C                     | Desktop     | [e73e96c866](https://linux-hardware.org/?probe=e73e96c866) | Sep 11, 2021 |
| Acer          | Spin SP513-54N              | Convertible | [059b59e828](https://linux-hardware.org/?probe=059b59e828) | Sep 09, 2021 |
| Notebook      | NJ5x_NJ7xLU                 | Notebook    | [4d544fc5d5](https://linux-hardware.org/?probe=4d544fc5d5) | Sep 09, 2021 |
| Intel         | DH61WW AAG23116-206         | Desktop     | [adbe5bb406](https://linux-hardware.org/?probe=adbe5bb406) | Sep 09, 2021 |
| Acer          | Aspire A514-53              | Notebook    | [a4c57ccf99](https://linux-hardware.org/?probe=a4c57ccf99) | Sep 09, 2021 |
| Acer          | WG43M                       | Desktop     | [35c29a05ff](https://linux-hardware.org/?probe=35c29a05ff) | Sep 09, 2021 |
| HP            | ENVY Laptop 13-ah0xxx       | Notebook    | [c06b09d9c4](https://linux-hardware.org/?probe=c06b09d9c4) | Sep 09, 2021 |
| HP            | ENVY Laptop 13-ah0xxx       | Notebook    | [87e79937c9](https://linux-hardware.org/?probe=87e79937c9) | Sep 09, 2021 |
| Dell          | Latitude 5520               | Notebook    | [7e327f4604](https://linux-hardware.org/?probe=7e327f4604) | Sep 09, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [6d55ad062f](https://linux-hardware.org/?probe=6d55ad062f) | Sep 08, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [cfcaf524be](https://linux-hardware.org/?probe=cfcaf524be) | Sep 07, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [dfb9789af2](https://linux-hardware.org/?probe=dfb9789af2) | Sep 07, 2021 |
| Dell          | Inspiron 1010               | Notebook    | [ee05ebef50](https://linux-hardware.org/?probe=ee05ebef50) | Sep 07, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [a47848e559](https://linux-hardware.org/?probe=a47848e559) | Sep 07, 2021 |
| Dell          | Inspiron 1010               | Notebook    | [8805be4e5c](https://linux-hardware.org/?probe=8805be4e5c) | Sep 07, 2021 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [8a53d9eccc](https://linux-hardware.org/?probe=8a53d9eccc) | Sep 05, 2021 |
| ASUSTek       | K53U                        | Notebook    | [a2f8f1be7d](https://linux-hardware.org/?probe=a2f8f1be7d) | Sep 04, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [f8735054b4](https://linux-hardware.org/?probe=f8735054b4) | Sep 02, 2021 |
| Dell          | 0M863N A00                  | Desktop     | [d8083308fc](https://linux-hardware.org/?probe=d8083308fc) | Sep 01, 2021 |
| Lenovo        | Legion 5P 15IMH05 82AW      | Notebook    | [f1b58d72ac](https://linux-hardware.org/?probe=f1b58d72ac) | Aug 31, 2021 |
| Dell          | Vostro 3300                 | Notebook    | [7d86f3f367](https://linux-hardware.org/?probe=7d86f3f367) | Aug 31, 2021 |
| Dell          | Vostro 3300                 | Notebook    | [be8b05e2a2](https://linux-hardware.org/?probe=be8b05e2a2) | Aug 31, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [2b9238ec6e](https://linux-hardware.org/?probe=2b9238ec6e) | Aug 31, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [e289576136](https://linux-hardware.org/?probe=e289576136) | Aug 31, 2021 |
| Dell          | 0KFKMF A00                  | All in one  | [7c3c22add4](https://linux-hardware.org/?probe=7c3c22add4) | Aug 30, 2021 |
| HP            | Pavilion 17                 | Notebook    | [ca125d2f3c](https://linux-hardware.org/?probe=ca125d2f3c) | Aug 30, 2021 |
| HP            | 198E                        | Desktop     | [82d1a8a5a7](https://linux-hardware.org/?probe=82d1a8a5a7) | Aug 29, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [0edc78c136](https://linux-hardware.org/?probe=0edc78c136) | Aug 28, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [a13b05f65f](https://linux-hardware.org/?probe=a13b05f65f) | Aug 27, 2021 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [65fcfef06f](https://linux-hardware.org/?probe=65fcfef06f) | Aug 27, 2021 |
| YJKC          | vBOOK Plus RVP7             | Notebook    | [8c051a0ce9](https://linux-hardware.org/?probe=8c051a0ce9) | Aug 26, 2021 |
| Lenovo        | Legion 5P 15IMH05 82AW      | Notebook    | [994e94defa](https://linux-hardware.org/?probe=994e94defa) | Aug 26, 2021 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [ad12a8f4b5](https://linux-hardware.org/?probe=ad12a8f4b5) | Aug 26, 2021 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [0d404bc317](https://linux-hardware.org/?probe=0d404bc317) | Aug 25, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [74a9538d04](https://linux-hardware.org/?probe=74a9538d04) | Aug 25, 2021 |
| Medion        | MS-7857                     | Desktop     | [4df85042be](https://linux-hardware.org/?probe=4df85042be) | Aug 25, 2021 |
| Dell          | Latitude E5440              | Notebook    | [ed4911006a](https://linux-hardware.org/?probe=ed4911006a) | Aug 23, 2021 |
| Gigabyte      | H87M-HD3                    | Desktop     | [b39ebeca56](https://linux-hardware.org/?probe=b39ebeca56) | Aug 23, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [58eced1242](https://linux-hardware.org/?probe=58eced1242) | Aug 21, 2021 |
| Medion        | B360H4-EM V1.0              | Desktop     | [376acac039](https://linux-hardware.org/?probe=376acac039) | Aug 21, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [5fcfdd2678](https://linux-hardware.org/?probe=5fcfdd2678) | Aug 20, 2021 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [b2ed4bc6fe](https://linux-hardware.org/?probe=b2ed4bc6fe) | Aug 18, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [c1a350cfa0](https://linux-hardware.org/?probe=c1a350cfa0) | Aug 17, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [f30480d463](https://linux-hardware.org/?probe=f30480d463) | Aug 17, 2021 |
| Fujitsu       | LIFEBOOK T937               | Convertible | [2de9720090](https://linux-hardware.org/?probe=2de9720090) | Aug 17, 2021 |
| HP            | ProBook 430 G1              | Notebook    | [9567d77449](https://linux-hardware.org/?probe=9567d77449) | Aug 17, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [05e4a8bcb2](https://linux-hardware.org/?probe=05e4a8bcb2) | Aug 16, 2021 |
| Dell          | XPS 17 9700                 | Notebook    | [0c38591981](https://linux-hardware.org/?probe=0c38591981) | Aug 16, 2021 |
| HP            | Compaq 8710w                | Notebook    | [1e1d518b29](https://linux-hardware.org/?probe=1e1d518b29) | Aug 14, 2021 |
| Acer          | Aspire XC-830               | Desktop     | [1e1a867c2a](https://linux-hardware.org/?probe=1e1a867c2a) | Aug 14, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [71645376f3](https://linux-hardware.org/?probe=71645376f3) | Aug 13, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [eb8c86aba1](https://linux-hardware.org/?probe=eb8c86aba1) | Aug 13, 2021 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [f59179a579](https://linux-hardware.org/?probe=f59179a579) | Aug 13, 2021 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [835e8af58f](https://linux-hardware.org/?probe=835e8af58f) | Aug 12, 2021 |
| HP            | ProBook 6460b               | Notebook    | [83029580f3](https://linux-hardware.org/?probe=83029580f3) | Aug 11, 2021 |
| Acer          | Swift SF314-54G             | Notebook    | [0cf6373ba8](https://linux-hardware.org/?probe=0cf6373ba8) | Aug 10, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [1a27b7d75c](https://linux-hardware.org/?probe=1a27b7d75c) | Aug 09, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [f2c3f335f8](https://linux-hardware.org/?probe=f2c3f335f8) | Aug 09, 2021 |
| Dell          | Latitude 5500               | Notebook    | [7cb9c5d946](https://linux-hardware.org/?probe=7cb9c5d946) | Aug 09, 2021 |
| ASRock        | FM2A75 Pro4                 | Desktop     | [09791b465e](https://linux-hardware.org/?probe=09791b465e) | Aug 09, 2021 |
| ASRock        | FM2A75 Pro4                 | Desktop     | [9608199058](https://linux-hardware.org/?probe=9608199058) | Aug 09, 2021 |
| HP            | ProBook 430 G1              | Notebook    | [f7438f6cab](https://linux-hardware.org/?probe=f7438f6cab) | Aug 08, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [44b36ed25b](https://linux-hardware.org/?probe=44b36ed25b) | Aug 08, 2021 |
| Dell          | 0WMJ54 A00                  | Desktop     | [d577241d35](https://linux-hardware.org/?probe=d577241d35) | Aug 08, 2021 |
| ASUSTek       | PRIME B460-PLUS             | Desktop     | [733a3e325c](https://linux-hardware.org/?probe=733a3e325c) | Aug 07, 2021 |
| MSI           | CR70 2M/CX70 2OC/CX70 2O... | Notebook    | [798feee097](https://linux-hardware.org/?probe=798feee097) | Aug 07, 2021 |
| Lenovo        | B40-30 80F1                 | Notebook    | [d7f9ec3de6](https://linux-hardware.org/?probe=d7f9ec3de6) | Aug 06, 2021 |
| Intel         | DG31PR AAD97573-206         | Desktop     | [9e4f8cf9b1](https://linux-hardware.org/?probe=9e4f8cf9b1) | Aug 06, 2021 |
| HP            | ProBook 4540s               | Notebook    | [52b0186956](https://linux-hardware.org/?probe=52b0186956) | Aug 06, 2021 |
| HP            | ENVY Laptop 13-aq1xxx       | Notebook    | [6af058344f](https://linux-hardware.org/?probe=6af058344f) | Aug 06, 2021 |
| Dell          | Latitude E6420              | Notebook    | [9e72687dd4](https://linux-hardware.org/?probe=9e72687dd4) | Aug 05, 2021 |
| Acer          | Aspire ES1-111              | Notebook    | [5f5802297c](https://linux-hardware.org/?probe=5f5802297c) | Aug 05, 2021 |
| Pegatron      | 2A84h                       | Desktop     | [93efec553e](https://linux-hardware.org/?probe=93efec553e) | Aug 04, 2021 |
| Acer          | Swift SF314-54G             | Notebook    | [3bca4552ab](https://linux-hardware.org/?probe=3bca4552ab) | Aug 04, 2021 |
| ASUSTek       | M3N78-EMH HDMI              | Desktop     | [6e6ac0f1b7](https://linux-hardware.org/?probe=6e6ac0f1b7) | Aug 04, 2021 |
| Acer          | Swift SF314-54G             | Notebook    | [8076357ae9](https://linux-hardware.org/?probe=8076357ae9) | Aug 03, 2021 |
| Lenovo        | ThinkPad T520 4243AP1       | Notebook    | [f1773945f2](https://linux-hardware.org/?probe=f1773945f2) | Aug 02, 2021 |
| HP            | OMEN by Laptop              | Notebook    | [7ca0de35b4](https://linux-hardware.org/?probe=7ca0de35b4) | Aug 01, 2021 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | Desktop     | [ff35a54fd5](https://linux-hardware.org/?probe=ff35a54fd5) | Aug 01, 2021 |
| ASUSTek       | UX305CA                     | Notebook    | [7fec0c7d28](https://linux-hardware.org/?probe=7fec0c7d28) | Aug 01, 2021 |
| HP            | Pavilion dv7                | Notebook    | [2966b0fcc3](https://linux-hardware.org/?probe=2966b0fcc3) | Jul 31, 2021 |
| Dell          | Latitude E6530              | Notebook    | [3318146af3](https://linux-hardware.org/?probe=3318146af3) | Jul 31, 2021 |
| ASUSTek       | P8H61-M PRO                 | Desktop     | [c9c2971ed8](https://linux-hardware.org/?probe=c9c2971ed8) | Jul 28, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [b423307c7c](https://linux-hardware.org/?probe=b423307c7c) | Jul 28, 2021 |
| Dell          | 0WWJRX A03                  | Desktop     | [f8ab0d9571](https://linux-hardware.org/?probe=f8ab0d9571) | Jul 27, 2021 |
| Foxconn       | 2A8C                        | Desktop     | [c545107086](https://linux-hardware.org/?probe=c545107086) | Jul 27, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [cd13d1596f](https://linux-hardware.org/?probe=cd13d1596f) | Jul 25, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [beec8a1c7d](https://linux-hardware.org/?probe=beec8a1c7d) | Jul 25, 2021 |
| Toshiba       | Satellite C850D-11K         | Notebook    | [c442634262](https://linux-hardware.org/?probe=c442634262) | Jul 24, 2021 |
| Acer          | WG43M                       | Desktop     | [9efd66b779](https://linux-hardware.org/?probe=9efd66b779) | Jul 22, 2021 |
| Lenovo        | ThinkPad 10 20C1S05H00      | Tablet      | [a8ee82d975](https://linux-hardware.org/?probe=a8ee82d975) | Jul 20, 2021 |
| Lenovo        | ThinkPad L580 20LXS4K600    | Notebook    | [fc8ad7a780](https://linux-hardware.org/?probe=fc8ad7a780) | Jul 20, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [03554a6e0d](https://linux-hardware.org/?probe=03554a6e0d) | Jul 20, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [1a3712c974](https://linux-hardware.org/?probe=1a3712c974) | Jul 19, 2021 |
| HP            | Laptop 17-by4xxx            | Notebook    | [d66405d958](https://linux-hardware.org/?probe=d66405d958) | Jul 19, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [40d1ea391b](https://linux-hardware.org/?probe=40d1ea391b) | Jul 17, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [167ddb49ce](https://linux-hardware.org/?probe=167ddb49ce) | Jul 16, 2021 |
| HP            | Laptop 17-by4xxx            | Notebook    | [460e87a27d](https://linux-hardware.org/?probe=460e87a27d) | Jul 15, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [0cc68536b5](https://linux-hardware.org/?probe=0cc68536b5) | Jul 14, 2021 |
| Gigabyte      | H55M-UD2H                   | Desktop     | [d871a17735](https://linux-hardware.org/?probe=d871a17735) | Jul 14, 2021 |
| Dell          | 02VM2Y A00                  | Desktop     | [3684dc06d5](https://linux-hardware.org/?probe=3684dc06d5) | Jul 13, 2021 |
| Intel         | NUC5i3RYB K23918-501        | Mini pc     | [5131c2b9c6](https://linux-hardware.org/?probe=5131c2b9c6) | Jul 13, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [cb44035a70](https://linux-hardware.org/?probe=cb44035a70) | Jul 13, 2021 |
| MSI           | 760GM-P23                   | Desktop     | [27b5300ea4](https://linux-hardware.org/?probe=27b5300ea4) | Jul 12, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [0b23e90cfc](https://linux-hardware.org/?probe=0b23e90cfc) | Jul 12, 2021 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [6beb6389bd](https://linux-hardware.org/?probe=6beb6389bd) | Jul 12, 2021 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [1fdcb33dcd](https://linux-hardware.org/?probe=1fdcb33dcd) | Jul 12, 2021 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [7a44c0b8e6](https://linux-hardware.org/?probe=7a44c0b8e6) | Jul 12, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [bc36fb9437](https://linux-hardware.org/?probe=bc36fb9437) | Jul 11, 2021 |
| HP            | 0A58h                       | Desktop     | [946ba8aa98](https://linux-hardware.org/?probe=946ba8aa98) | Jul 10, 2021 |
| Dell          | 0M863N A00                  | Desktop     | [574671bbb9](https://linux-hardware.org/?probe=574671bbb9) | Jul 09, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Belgium/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 291       | 17.63%  |
| Ubuntu 18.04                 | 140       | 8.48%   |
| Ubuntu 22.04                 | 54        | 3.27%   |
| OpenMandriva 4.2             | 43        | 2.6%    |
| ArcoLinux Rolling            | 35        | 2.12%   |
| OpenMandriva 4.3             | 32        | 1.94%   |
| Zorin 16                     | 31        | 1.88%   |
| Ubuntu 20.10                 | 31        | 1.88%   |
| Debian 11                    | 30        | 1.82%   |
| Linux Mint 20.1              | 29        | 1.76%   |
| Fedora 36                    | 29        | 1.76%   |
| Ubuntu 19.10                 | 27        | 1.64%   |
| Linux Mint 20.3              | 26        | 1.57%   |
| Arch                         | 26        | 1.57%   |
| Manjaro                      | 25        | 1.51%   |
| Linux Mint 19.3              | 25        | 1.51%   |
| Fedora 35                    | 25        | 1.51%   |
| Xubuntu 20.04                | 23        | 1.39%   |
| Linux Mint 20.2              | 23        | 1.39%   |
| Fedora 34                    | 21        | 1.27%   |
| Ubuntu 19.04                 | 20        | 1.21%   |
| Pop!_OS 20.04                | 20        | 1.21%   |
| Linux Mint 20                | 19        | 1.15%   |
| Arch Rolling                 | 19        | 1.15%   |
| Ubuntu 21.10                 | 17        | 1.03%   |
| Ubuntu 21.04                 | 16        | 0.97%   |
| Pop!_OS 21.04                | 16        | 0.97%   |
| KDE neon 20.04               | 16        | 0.97%   |
| Fedora 33                    | 16        | 0.97%   |
| openSUSE Tumbleweed-XXXXXXXX | 15        | 0.91%   |
| Fedora 32                    | 15        | 0.91%   |
| Debian 10                    | 15        | 0.91%   |
| Ubuntu 18.10                 | 13        | 0.79%   |
| Linux Mint 21                | 13        | 0.79%   |
| Kubuntu 20.04                | 12        | 0.73%   |
| Debian Testing               | 12        | 0.73%   |
| ROSA R10                     | 11        | 0.67%   |
| Pop!_OS 22.04                | 11        | 0.67%   |
| Elementary 6.1               | 11        | 0.67%   |
| Xubuntu 18.04                | 10        | 0.61%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 589       | 38.22%  |
| Linux Mint    | 146       | 9.47%   |
| Fedora        | 93        | 6.04%   |
| OpenMandriva  | 88        | 5.71%   |
| Debian        | 63        | 4.09%   |
| Manjaro       | 57        | 3.7%    |
| Pop!_OS       | 56        | 3.63%   |
| Xubuntu       | 47        | 3.05%   |
| Arch          | 44        | 2.86%   |
| Zorin         | 42        | 2.73%   |
| ArcoLinux     | 36        | 2.34%   |
| Kubuntu       | 28        | 1.82%   |
| ROSA          | 27        | 1.75%   |
| openSUSE      | 22        | 1.43%   |
| KDE neon      | 20        | 1.3%    |
| Ubuntu Unity  | 17        | 1.1%    |
| Elementary    | 17        | 1.1%    |
| Lubuntu       | 15        | 0.97%   |
| Gentoo        | 14        | 0.91%   |
| EndeavourOS   | 13        | 0.84%   |
| Ubuntu MATE   | 12        | 0.78%   |
| CentOS        | 12        | 0.78%   |
| Endless       | 10        | 0.65%   |
| BlackPanther  | 8         | 0.52%   |
| LMDE          | 7         | 0.45%   |
| Kali          | 6         | 0.39%   |
| Garuda Linux  | 5         | 0.32%   |
| Clear Linux   | 5         | 0.32%   |
| Ubuntu Budgie | 4         | 0.26%   |
| MX            | 3         | 0.19%   |
| LinuxFX       | 3         | 0.19%   |
| Ubuntu Studio | 2         | 0.13%   |
| SteamOS       | 2         | 0.13%   |
| Rocky Linux   | 2         | 0.13%   |
| Parrot        | 2         | 0.13%   |
| Nobara        | 2         | 0.13%   |
| NixOS         | 2         | 0.13%   |
| Feren OS      | 2         | 0.13%   |
| Devuan        | 2         | 0.13%   |
| antergos      | 2         | 0.13%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002        | 42        | 2.21%   |
| 5.16.7-desktop-1omv4003         | 31        | 1.63%   |
| 5.4.0-42-generic                | 29        | 1.53%   |
| 5.4.0-58-generic                | 22        | 1.16%   |
| 5.4.0-48-generic                | 21        | 1.11%   |
| 5.3.0-42-generic                | 20        | 1.05%   |
| 5.15.0-46-generic               | 18        | 0.95%   |
| 5.15.0-52-generic               | 17        | 0.89%   |
| 5.8.0-48-generic                | 15        | 0.79%   |
| 5.8.0-43-generic                | 15        | 0.79%   |
| 5.4.0-65-generic                | 15        | 0.79%   |
| 5.15.0-48-generic               | 15        | 0.79%   |
| 5.4.0-66-generic                | 14        | 0.74%   |
| 5.4.0-29-generic                | 14        | 0.74%   |
| 5.3.0-46-generic                | 14        | 0.74%   |
| 5.11.0-38-generic               | 14        | 0.74%   |
| 5.4.0-74-generic                | 13        | 0.68%   |
| 5.4.0-52-generic                | 13        | 0.68%   |
| 5.4.0-40-generic                | 13        | 0.68%   |
| 5.4.0-37-generic                | 12        | 0.63%   |
| 5.4.0-26-generic                | 12        | 0.63%   |
| 5.15.0-47-generic               | 12        | 0.63%   |
| 5.15.0-41-generic               | 12        | 0.63%   |
| 5.13.0-28-generic               | 12        | 0.63%   |
| 5.11.0-43-generic               | 11        | 0.58%   |
| 5.11.0-41-generic               | 11        | 0.58%   |
| 5.8.0-53-generic                | 10        | 0.53%   |
| 5.4.0-91-generic                | 10        | 0.53%   |
| 5.4.0-54-generic                | 10        | 0.53%   |
| 5.13.0-39-generic               | 10        | 0.53%   |
| 5.4.0-56-generic                | 9         | 0.47%   |
| 5.3.0-40-generic                | 9         | 0.47%   |
| 5.15.0-53-generic               | 9         | 0.47%   |
| 5.15.0-50-generic               | 9         | 0.47%   |
| 5.11.0-7620-generic             | 9         | 0.47%   |
| 5.11.0-40-generic               | 9         | 0.47%   |
| 5.10.0-8-amd64                  | 9         | 0.47%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 9         | 0.47%   |
| 5.4.0-90-generic                | 8         | 0.42%   |
| 5.4.0-47-generic                | 8         | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 343       | 19.4%   |
| 5.15.0  | 121       | 6.84%   |
| 5.8.0   | 118       | 6.67%   |
| 5.11.0  | 106       | 6%      |
| 4.15.0  | 106       | 6%      |
| 5.3.0   | 83        | 4.69%   |
| 5.13.0  | 81        | 4.58%   |
| 5.0.0   | 51        | 2.88%   |
| 5.10.14 | 42        | 2.38%   |
| 5.10.0  | 40        | 2.26%   |
| 4.18.0  | 37        | 2.09%   |
| 5.16.7  | 31        | 1.75%   |
| 4.19.0  | 16        | 0.9%    |
| 5.19.0  | 10        | 0.57%   |
| 4.18.16 | 10        | 0.57%   |
| 5.17.5  | 9         | 0.51%   |
| 4.9.20  | 9         | 0.51%   |
| 5.18.12 | 7         | 0.4%    |
| 5.14.10 | 7         | 0.4%    |
| 5.9.11  | 6         | 0.34%   |
| 5.8.5   | 6         | 0.34%   |
| 5.16.0  | 6         | 0.34%   |
| 5.13.12 | 6         | 0.34%   |
| 4.9.60  | 6         | 0.34%   |
| 4.4.0   | 6         | 0.34%   |
| 3.10.0  | 6         | 0.34%   |
| 6.0.5   | 5         | 0.28%   |
| 6.0.2   | 5         | 0.28%   |
| 6.0.0   | 5         | 0.28%   |
| 5.9.16  | 5         | 0.28%   |
| 5.19.12 | 5         | 0.28%   |
| 5.18.5  | 5         | 0.28%   |
| 5.18.0  | 5         | 0.28%   |
| 5.17.0  | 5         | 0.28%   |
| 4.13.0  | 5         | 0.28%   |
| 5.8.18  | 4         | 0.23%   |
| 5.6.0   | 4         | 0.23%   |
| 5.5.6   | 4         | 0.23%   |
| 5.3.18  | 4         | 0.23%   |
| 5.19.11 | 4         | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 372       | 21.58%  |
| 5.15    | 168       | 9.74%   |
| 5.8     | 140       | 8.12%   |
| 5.11    | 133       | 7.71%   |
| 5.10    | 114       | 6.61%   |
| 4.15    | 106       | 6.15%   |
| 5.13    | 100       | 5.8%    |
| 5.3     | 91        | 5.28%   |
| 5.16    | 67        | 3.89%   |
| 5.0     | 57        | 3.31%   |
| 4.18    | 48        | 2.78%   |
| 5.17    | 36        | 2.09%   |
| 5.19    | 33        | 1.91%   |
| 5.18    | 33        | 1.91%   |
| 5.9     | 26        | 1.51%   |
| 4.9     | 25        | 1.45%   |
| 5.12    | 24        | 1.39%   |
| 6.0     | 23        | 1.33%   |
| 5.14    | 23        | 1.33%   |
| 4.19    | 23        | 1.33%   |
| 5.6     | 22        | 1.28%   |
| 5.5     | 13        | 0.75%   |
| 5.7     | 12        | 0.7%    |
| 4.4     | 6         | 0.35%   |
| 3.10    | 6         | 0.35%   |
| 4.13    | 5         | 0.29%   |
| 5.2     | 4         | 0.23%   |
| 5.1     | 4         | 0.23%   |
| 4.12    | 3         | 0.17%   |
| 4.17    | 2         | 0.12%   |
| 4.1     | 2         | 0.12%   |
| 4.2     | 1         | 0.06%   |
| 4.10    | 1         | 0.06%   |
| 2.6     | 1         | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1418      | 96.4%   |
| i686    | 40        | 2.72%   |
| aarch64 | 11        | 0.75%   |
| armv7l  | 2         | 0.14%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 664       | 42.13%  |
| Unknown          | 230       | 14.59%  |
| KDE5             | 217       | 13.77%  |
| XFCE             | 133       | 8.44%   |
| X-Cinnamon       | 108       | 6.85%   |
| MATE             | 46        | 2.92%   |
| KDE              | 37        | 2.35%   |
| Unity            | 17        | 1.08%   |
| Pantheon         | 17        | 1.08%   |
| i3               | 17        | 1.08%   |
| Cinnamon         | 17        | 1.08%   |
| LXQt             | 16        | 1.02%   |
| KDE4             | 14        | 0.89%   |
| Budgie           | 7         | 0.44%   |
| sway             | 5         | 0.32%   |
| LXDE             | 5         | 0.32%   |
| GNOME Flashback  | 5         | 0.32%   |
| LeftWM           | 4         | 0.25%   |
| Deepin           | 3         | 0.19%   |
| awesome          | 3         | 0.19%   |
| Openbox          | 2         | 0.13%   |
| bspwm            | 2         | 0.13%   |
| xmonad           | 1         | 0.06%   |
| Trinity          | 1         | 0.06%   |
| spectrwm         | 1         | 0.06%   |
| qtile            | 1         | 0.06%   |
| lightdm-xsession | 1         | 0.06%   |
| ICEWM            | 1         | 0.06%   |
| chadwm           | 1         | 0.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1202      | 78.92%  |
| Wayland | 169       | 11.1%   |
| Unknown | 129       | 8.47%   |
| Tty     | 23        | 1.51%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 802       | 51.74%  |
| SDDM    | 224       | 14.45%  |
| GDM     | 199       | 12.84%  |
| GDM3    | 128       | 8.26%   |
| LightDM | 112       | 7.23%   |
| TDM     | 68        | 4.39%   |
| KDM     | 13        | 0.84%   |
| XDM     | 3         | 0.19%   |
| SLiM    | 1         | 0.06%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 472       | 30.77%  |
| fr_BE      | 268       | 17.47%  |
| nl_BE      | 248       | 16.17%  |
| Unknown    | 223       | 14.54%  |
| fr_FR      | 83        | 5.41%   |
| en_GB      | 72        | 4.69%   |
| nl_NL      | 71        | 4.63%   |
| C          | 25        | 1.63%   |
| de_DE      | 10        | 0.65%   |
| de_BE      | 9         | 0.59%   |
| pl_PL      | 6         | 0.39%   |
| en_IE      | 6         | 0.39%   |
| es_ES      | 5         | 0.33%   |
| ru_RU      | 4         | 0.26%   |
| pt_PT      | 3         | 0.2%    |
| ro_RO      | 2         | 0.13%   |
| POSIX      | 2         | 0.13%   |
| it_IT      | 2         | 0.13%   |
| en_US.UTF8 | 2         | 0.13%   |
| en_CA      | 2         | 0.13%   |
| en_BE      | 2         | 0.13%   |
| C.UTF8     | 2         | 0.13%   |
| tt_RU      | 1         | 0.07%   |
| tr_TR      | 1         | 0.07%   |
| pt_BR      | 1         | 0.07%   |
| nl_AW      | 1         | 0.07%   |
| li_BE      | 1         | 0.07%   |
| it_CH      | 1         | 0.07%   |
| hu_HU      | 1         | 0.07%   |
| fr_LU      | 1         | 0.07%   |
| fr_FR.UTF8 | 1         | 0.07%   |
| fr_CH      | 1         | 0.07%   |
| en_ZA      | 1         | 0.07%   |
| en_NZ      | 1         | 0.07%   |
| en_IN      | 1         | 0.07%   |
| en_DK      | 1         | 0.07%   |
| bg_BG      | 1         | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 770       | 51.09%  |
| EFI  | 737       | 48.91%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 1175      | 77.56%  |
| Btrfs    | 122       | 8.05%   |
| Overlay  | 110       | 7.26%   |
| Unknown  | 64        | 4.22%   |
| Xfs      | 24        | 1.58%   |
| Ext2     | 8         | 0.53%   |
| Zfs      | 5         | 0.33%   |
| Tmpfs    | 5         | 0.33%   |
| Reiserfs | 1         | 0.07%   |
| Ext3     | 1         | 0.07%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 863       | 57.23%  |
| GPT     | 497       | 32.96%  |
| MBR     | 148       | 9.81%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1241      | 82.68%  |
| Yes       | 260       | 17.32%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1052      | 70.13%  |
| Yes       | 448       | 29.87%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 243       | 16.54%  |
| Hewlett-Packard         | 225       | 15.32%  |
| Dell                    | 204       | 13.89%  |
| Lenovo                  | 177       | 12.05%  |
| MSI                     | 92        | 6.26%   |
| Gigabyte Technology     | 87        | 5.92%   |
| Acer                    | 86        | 5.85%   |
| Medion                  | 48        | 3.27%   |
| ASRock                  | 40        | 2.72%   |
| Apple                   | 32        | 2.18%   |
| Toshiba                 | 31        | 2.11%   |
| Intel                   | 27        | 1.84%   |
| Sony                    | 23        | 1.57%   |
| Packard Bell            | 20        | 1.36%   |
| Notebook                | 17        | 1.16%   |
| Unknown                 | 13        | 0.88%   |
| Fujitsu                 | 11        | 0.75%   |
| Raspberry Pi Foundation | 9         | 0.61%   |
| TUXEDO                  | 8         | 0.54%   |
| Samsung Electronics     | 7         | 0.48%   |
| Supermicro              | 5         | 0.34%   |
| Fujitsu Siemens         | 5         | 0.34%   |
| Foxconn                 | 5         | 0.34%   |
| PC Specialist           | 4         | 0.27%   |
| Valve                   | 3         | 0.2%    |
| HUAWEI                  | 3         | 0.2%    |
| Google                  | 3         | 0.2%    |
| AMI                     | 3         | 0.2%    |
| Shuttle                 | 2         | 0.14%   |
| Razer                   | 2         | 0.14%   |
| Pegatron                | 2         | 0.14%   |
| Panasonic               | 2         | 0.14%   |
| Nvidia                  | 2         | 0.14%   |
| Microsoft               | 2         | 0.14%   |
| Clevo                   | 2         | 0.14%   |
| BESSTAR Tech            | 2         | 0.14%   |
| YJKC                    | 1         | 0.07%   |
| TYAN Computer           | 1         | 0.07%   |
| TrekStor                | 1         | 0.07%   |
| Timi                    | 1         | 0.07%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| ASUS All Series                  | 19        | 1.29%   |
| Unknown                          | 17        | 1.16%   |
| HP ProBook 650 G1                | 5         | 0.34%   |
| HP Pavilion Notebook             | 5         | 0.34%   |
| HP Pavilion dv7                  | 5         | 0.34%   |
| Dell XPS 13 7390                 | 5         | 0.34%   |
| Dell OptiPlex 780                | 5         | 0.34%   |
| ASRock B450M Pro4                | 5         | 0.34%   |
| Toshiba Satellite C660           | 4         | 0.27%   |
| RPi Raspberry Pi                 | 4         | 0.27%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5 | 4         | 0.27%   |
| HP ProBook 6570b                 | 4         | 0.27%   |
| HP Pavilion 17                   | 4         | 0.27%   |
| Gigabyte X570 AORUS MASTER       | 4         | 0.27%   |
| Gigabyte Spring Peak             | 4         | 0.27%   |
| Dell XPS 13 9370                 | 4         | 0.27%   |
| Dell OptiPlex 3010               | 4         | 0.27%   |
| Dell Latitude 5520               | 4         | 0.27%   |
| ASUS ROG STRIX X570-E GAMING     | 4         | 0.27%   |
| ASUS PRIME X570-PRO              | 4         | 0.27%   |
| Valve Jupiter                    | 3         | 0.2%    |
| MSI MS-7C91                      | 3         | 0.2%    |
| MSI MS-7C37                      | 3         | 0.2%    |
| MSI MS-7B86                      | 3         | 0.2%    |
| MSI MS-7A38                      | 3         | 0.2%    |
| Medion MS-7728                   | 3         | 0.2%    |
| Lenovo Yoga 530-14IKB 81EK       | 3         | 0.2%    |
| Lenovo ThinkPad L390 20NSS1YV0B  | 3         | 0.2%    |
| Lenovo Legion 5 15ARH05 82B5     | 3         | 0.2%    |
| HP ProBook 470 G2                | 3         | 0.2%    |
| HP ProBook 430 G1                | 3         | 0.2%    |
| HP Pavilion Laptop 15-eh1xxx     | 3         | 0.2%    |
| HP Pavilion Laptop 15-cw0xxx     | 3         | 0.2%    |
| HP Pavilion g7                   | 3         | 0.2%    |
| HP Pavilion dv6                  | 3         | 0.2%    |
| HP Pavilion 15                   | 3         | 0.2%    |
| HP EliteBook 840 G1              | 3         | 0.2%    |
| Gigabyte GB-BRR7H-4800           | 3         | 0.2%    |
| Gigabyte B550I AORUS PRO AX      | 3         | 0.2%    |
| Dell XPS 15 9570                 | 3         | 0.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 89        | 6.06%   |
| Dell Latitude         | 77        | 5.24%   |
| Acer Aspire           | 66        | 4.49%   |
| HP EliteBook          | 46        | 3.13%   |
| HP Pavilion           | 45        | 3.06%   |
| HP ProBook            | 38        | 2.59%   |
| Dell XPS              | 34        | 2.31%   |
| HP Compaq             | 29        | 1.97%   |
| ASUS PRIME            | 29        | 1.97%   |
| Toshiba Satellite     | 27        | 1.84%   |
| Dell OptiPlex         | 27        | 1.84%   |
| Lenovo IdeaPad        | 25        | 1.7%    |
| Dell Inspiron         | 24        | 1.63%   |
| ASUS ROG              | 21        | 1.43%   |
| ASUS All              | 19        | 1.29%   |
| Dell Precision        | 18        | 1.23%   |
| Unknown               | 17        | 1.16%   |
| ASUS TUF              | 16        | 1.09%   |
| Lenovo Yoga           | 14        | 0.95%   |
| HP Laptop             | 13        | 0.88%   |
| Packard Bell EasyNote | 11        | 0.75%   |
| Medion Akoya          | 11        | 0.75%   |
| Lenovo Legion         | 11        | 0.75%   |
| Dell Vostro           | 10        | 0.68%   |
| RPi Raspberry         | 9         | 0.61%   |
| Lenovo ThinkCentre    | 9         | 0.61%   |
| Gigabyte X570         | 9         | 0.61%   |
| HP ENVY               | 8         | 0.54%   |
| HP ZBook              | 7         | 0.48%   |
| HP ProDesk            | 6         | 0.41%   |
| ASUS VivoBook         | 6         | 0.41%   |
| Dell Studio           | 5         | 0.34%   |
| ASUS STRIX            | 5         | 0.34%   |
| ASRock B450M          | 5         | 0.34%   |
| Acer Nitro            | 5         | 0.34%   |
| Packard Bell IMEDIA   | 4         | 0.27%   |
| Lenovo ThinkBook      | 4         | 0.27%   |
| Lenovo IdeaCentre     | 4         | 0.27%   |
| HP ProLiant           | 4         | 0.27%   |
| Gigabyte Spring       | 4         | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 153       | 10.42%  |
| 2019    | 143       | 9.73%   |
| 2020    | 134       | 9.12%   |
| 2012    | 119       | 8.1%    |
| 2013    | 116       | 7.9%    |
| 2011    | 103       | 7.01%   |
| 2014    | 93        | 6.33%   |
| 2017    | 86        | 5.85%   |
| 2015    | 78        | 5.31%   |
| 2008    | 76        | 5.17%   |
| 2021    | 68        | 4.63%   |
| 2016    | 67        | 4.56%   |
| 2010    | 65        | 4.42%   |
| 2009    | 60        | 4.08%   |
| 2007    | 46        | 3.13%   |
| 2006    | 24        | 1.63%   |
| 2022    | 17        | 1.16%   |
| Unknown | 15        | 1.02%   |
| 2005    | 4         | 0.27%   |
| 2004    | 2         | 0.14%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 822       | 55.96%  |
| Desktop        | 540       | 36.76%  |
| Convertible    | 41        | 2.79%   |
| Mini pc        | 18        | 1.23%   |
| Server         | 14        | 0.95%   |
| System on chip | 13        | 0.88%   |
| All in one     | 13        | 0.88%   |
| Tablet         | 8         | 0.54%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1357      | 91.5%   |
| Enabled  | 126       | 8.5%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1466      | 99.8%   |
| Yes  | 3         | 0.2%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 323       | 21.48%  |
| 16.01-24.0      | 321       | 21.34%  |
| 8.01-16.0       | 277       | 18.42%  |
| 3.01-4.0        | 275       | 18.28%  |
| 32.01-64.0      | 145       | 9.64%   |
| 1.01-2.0        | 53        | 3.52%   |
| 64.01-256.0     | 40        | 2.66%   |
| 24.01-32.0      | 27        | 1.8%    |
| 2.01-3.0        | 21        | 1.4%    |
| 0.51-1.0        | 16        | 1.06%   |
| More than 256.0 | 4         | 0.27%   |
| 0.01-0.5        | 2         | 0.13%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 584       | 34.78%  |
| 2.01-3.0    | 419       | 24.96%  |
| 4.01-8.0    | 232       | 13.82%  |
| 3.01-4.0    | 207       | 12.33%  |
| 0.51-1.0    | 114       | 6.79%   |
| 8.01-16.0   | 83        | 4.94%   |
| 0.01-0.5    | 28        | 1.67%   |
| 24.01-32.0  | 5         | 0.3%    |
| 16.01-24.0  | 5         | 0.3%    |
| 64.01-256.0 | 1         | 0.06%   |
| Unknown     | 1         | 0.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 860       | 56.54%  |
| 2       | 401       | 26.36%  |
| 3       | 104       | 6.84%   |
| 4       | 69        | 4.54%   |
| 5       | 40        | 2.63%   |
| 6       | 19        | 1.25%   |
| 0       | 14        | 0.92%   |
| 9       | 4         | 0.26%   |
| 7       | 4         | 0.26%   |
| 8       | 3         | 0.2%    |
| 16      | 1         | 0.07%   |
| 10      | 1         | 0.07%   |
| Unknown | 1         | 0.07%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 815       | 55.07%  |
| Yes       | 665       | 44.93%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1332      | 90.06%  |
| No        | 147       | 9.94%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1109      | 74.98%  |
| No        | 370       | 25.02%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 850       | 57.01%  |
| No        | 641       | 42.99%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Belgium | 1469      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Brussels       | 178       | 10.95%  |
| Antwerp        | 108       | 6.64%   |
| Ghent          | 61        | 3.75%   |
| Ixelles-Elsene | 44        | 2.71%   |
| Liège         | 37        | 2.28%   |
| Mechelen       | 26        | 1.6%    |
| Leuven         | 22        | 1.35%   |
| Turnhout       | 19        | 1.17%   |
| Schaarbeek     | 18        | 1.11%   |
| Uccle          | 14        | 0.86%   |
| Anderlecht     | 14        | 0.86%   |
| Mons           | 13        | 0.8%    |
| Hasselt        | 13        | 0.8%    |
| Bruges         | 13        | 0.8%    |
| Aalst          | 13        | 0.8%    |
| Etterbeek      | 12        | 0.74%   |
| Roeselare      | 11        | 0.68%   |
| Lier           | 11        | 0.68%   |
| La Louvière   | 11        | 0.68%   |
| Boom           | 11        | 0.68%   |
| Wilrijk        | 10        | 0.62%   |
| Kontich        | 10        | 0.62%   |
| Kanne          | 10        | 0.62%   |
| Gavere         | 10        | 0.62%   |
| Vilvoorde      | 9         | 0.55%   |
| Langdorp       | 9         | 0.55%   |
| Jette          | 9         | 0.55%   |
| Harelbeke      | 9         | 0.55%   |
| Duffel         | 9         | 0.55%   |
| Deurne         | 9         | 0.55%   |
| Brasschaat     | 9         | 0.55%   |
| Bilzen         | 9         | 0.55%   |
| Wetteren       | 8         | 0.49%   |
| Sint-Niklaas   | 8         | 0.49%   |
| Seraing        | 8         | 0.49%   |
| Namur          | 8         | 0.49%   |
| Hulshout       | 8         | 0.49%   |
| Haaltert       | 8         | 0.49%   |
| Ypres          | 7         | 0.43%   |
| Tournai        | 7         | 0.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 449       | 775    | 20.83%  |
| WDC                       | 332       | 546    | 15.4%   |
| Seagate                   | 330       | 568    | 15.31%  |
| Toshiba                   | 142       | 199    | 6.59%   |
| Kingston                  | 116       | 180    | 5.38%   |
| SanDisk                   | 99        | 127    | 4.59%   |
| Unknown                   | 81        | 110    | 3.76%   |
| Crucial                   | 70        | 103    | 3.25%   |
| Hitachi                   | 68        | 90     | 3.15%   |
| SK hynix                  | 65        | 81     | 3.01%   |
| Intel                     | 55        | 64     | 2.55%   |
| HGST                      | 37        | 55     | 1.72%   |
| Micron Technology         | 31        | 33     | 1.44%   |
| Apple                     | 17        | 21     | 0.79%   |
| Phison                    | 16        | 19     | 0.74%   |
| LITEON                    | 15        | 21     | 0.7%    |
| Maxtor                    | 13        | 16     | 0.6%    |
| Fujitsu                   | 13        | 18     | 0.6%    |
| Corsair                   | 13        | 13     | 0.6%    |
| A-DATA Technology         | 13        | 18     | 0.6%    |
| OCZ                       | 11        | 13     | 0.51%   |
| KIOXIA                    | 11        | 13     | 0.51%   |
| Intenso                   | 11        | 19     | 0.51%   |
| PNY                       | 9         | 9      | 0.42%   |
| Micron/Crucial Technology | 8         | 12     | 0.37%   |
| LITEONIT                  | 8         | 11     | 0.37%   |
| LaCie                     | 8         | 11     | 0.37%   |
| China                     | 8         | 11     | 0.37%   |
| Silicon Motion            | 7         | 9      | 0.32%   |
| LDLC                      | 5         | 6      | 0.23%   |
| KingSpec                  | 5         | 5      | 0.23%   |
| ASMT                      | 5         | 5      | 0.23%   |
| Transcend                 | 4         | 6      | 0.19%   |
| KingFast                  | 4         | 4      | 0.19%   |
| JMicron Technology        | 4         | 6      | 0.19%   |
| GOODRAM                   | 4         | 7      | 0.19%   |
| XPG                       | 3         | 7      | 0.14%   |
| Union Memory (Shenzhen)   | 3         | 4      | 0.14%   |
| SSSTC                     | 3         | 3      | 0.14%   |
| Zheino                    | 2         | 2      | 0.09%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB              | 28        | 1.15%   |
| Samsung NVMe SSD Drive 1TB             | 27        | 1.11%   |
| Samsung NVMe SSD Drive 512GB           | 23        | 0.94%   |
| Samsung SSD 850 EVO 250GB              | 22        | 0.9%    |
| Samsung SSD 850 EVO 500GB              | 21        | 0.86%   |
| Samsung NVMe SSD Drive 500GB           | 21        | 0.86%   |
| Seagate ST1000LM035-1RK172 1TB         | 20        | 0.82%   |
| Kingston SV300S37A120G 120GB SSD       | 20        | 0.82%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 19        | 0.78%   |
| Kingston SA400S37120G 120GB SSD        | 19        | 0.78%   |
| Samsung SSD 860 EVO 1TB                | 18        | 0.74%   |
| Toshiba DT01ACA100 1TB                 | 17        | 0.7%    |
| Samsung SSD 860 EVO 250GB              | 17        | 0.7%    |
| Intel NVMe SSD Drive 512GB             | 15        | 0.61%   |
| SK hynix NVMe SSD Drive 512GB          | 13        | 0.53%   |
| Seagate ST2000DM001-1ER164 2TB         | 13        | 0.53%   |
| Samsung SSD 870 EVO 1TB                | 13        | 0.53%   |
| Kingston SA400S37240G 240GB SSD        | 13        | 0.53%   |
| Toshiba MQ01ABD100 1TB                 | 12        | 0.49%   |
| Seagate ST9500325AS 500GB              | 12        | 0.49%   |
| Seagate ST500DM002-1BD142 500GB        | 12        | 0.49%   |
| Seagate ST2000DM001-1CH164 2TB         | 12        | 0.49%   |
| SanDisk NVMe SSD Drive 512GB           | 12        | 0.49%   |
| HGST HTS721010A9E630 1TB               | 12        | 0.49%   |
| Unknown MMC Card  64GB                 | 11        | 0.45%   |
| Unknown MMC Card  32GB                 | 11        | 0.45%   |
| Seagate Expansion 1TB                  | 11        | 0.45%   |
| Samsung SSD 970 EVO 1TB                | 11        | 0.45%   |
| Unknown SD/MMC/MS PRO 8GB              | 10        | 0.41%   |
| Seagate ST4000DM004-2CV104 4TB         | 9         | 0.37%   |
| Seagate ST2000DM008-2FR102 2TB         | 9         | 0.37%   |
| Seagate ST1000LM048-2E7172 1TB         | 9         | 0.37%   |
| Samsung SSD 970 EVO Plus 500GB         | 9         | 0.37%   |
| Samsung SSD 870 QVO 1TB                | 9         | 0.37%   |
| Samsung SSD 860 QVO 1TB                | 9         | 0.37%   |
| Samsung SSD 840 EVO 250GB              | 9         | 0.37%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 9         | 0.37%   |
| Crucial CT480BX500SSD1 480GB           | 9         | 0.37%   |
| WDC WD20EZRZ-00Z5HB0 2TB               | 8         | 0.33%   |
| Unknown MMC Card  128GB                | 8         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 323       | 555    | 35.97%  |
| WDC                 | 278       | 464    | 30.96%  |
| Toshiba             | 101       | 139    | 11.25%  |
| Hitachi             | 68        | 90     | 7.57%   |
| HGST                | 37        | 55     | 4.12%   |
| Samsung Electronics | 34        | 56     | 3.79%   |
| Maxtor              | 13        | 16     | 1.45%   |
| Fujitsu             | 13        | 17     | 1.45%   |
| Unknown             | 10        | 16     | 1.11%   |
| Apple               | 5         | 5      | 0.56%   |
| ASMT                | 4         | 4      | 0.45%   |
| LaCie               | 2         | 2      | 0.22%   |
| Hewlett-Packard     | 2         | 4      | 0.22%   |
| WD MediaMax         | 1         | 1      | 0.11%   |
| SINTECHI            | 1         | 1      | 0.11%   |
| Magnetic Data       | 1         | 1      | 0.11%   |
| Lenovo              | 1         | 2      | 0.11%   |
| KESU                | 1         | 3      | 0.11%   |
| Intenso             | 1         | 4      | 0.11%   |
| IET                 | 1         | 3      | 0.11%   |
| Dell                | 1         | 1      | 0.11%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 254       | 418    | 35.67%  |
| Kingston            | 96        | 151    | 13.48%  |
| Crucial             | 61        | 92     | 8.57%   |
| SanDisk             | 59        | 79     | 8.29%   |
| WDC                 | 36        | 44     | 5.06%   |
| SK hynix            | 19        | 28     | 2.67%   |
| Toshiba             | 18        | 21     | 2.53%   |
| Micron Technology   | 16        | 17     | 2.25%   |
| Intel               | 16        | 19     | 2.25%   |
| LITEON              | 13        | 19     | 1.83%   |
| OCZ                 | 11        | 13     | 1.54%   |
| Intenso             | 11        | 15     | 1.54%   |
| Apple               | 10        | 13     | 1.4%    |
| Corsair             | 9         | 9      | 1.26%   |
| PNY                 | 8         | 8      | 1.12%   |
| LITEONIT            | 8         | 11     | 1.12%   |
| China               | 8         | 11     | 1.12%   |
| A-DATA Technology   | 7         | 11     | 0.98%   |
| Transcend           | 4         | 6      | 0.56%   |
| KingSpec            | 4         | 4      | 0.56%   |
| GOODRAM             | 4         | 7      | 0.56%   |
| Zheino              | 2         | 2      | 0.28%   |
| Plextor             | 2         | 2      | 0.28%   |
| KingFast            | 2         | 2      | 0.28%   |
| JMicron Technology  | 2         | 3      | 0.28%   |
| WDC WDS             | 1         | 1      | 0.14%   |
| Verbatim            | 1         | 1      | 0.14%   |
| Vaseky              | 1         | 1      | 0.14%   |
| TO Exter            | 1         | 1      | 0.14%   |
| tigo                | 1         | 1      | 0.14%   |
| Teclast             | 1         | 1      | 0.14%   |
| SPCC                | 1         | 2      | 0.14%   |
| Seagate             | 1         | 1      | 0.14%   |
| Reeinno             | 1         | 3      | 0.14%   |
| Phison              | 1         | 1      | 0.14%   |
| Patriot             | 1         | 1      | 0.14%   |
| OWC                 | 1         | 2      | 0.14%   |
| OCZ-VERTEX          | 1         | 1      | 0.14%   |
| Netac               | 1         | 1      | 0.14%   |
| Mushkin             | 1         | 1      | 0.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 745       | 1439   | 38.34%  |
| SSD     | 637       | 1044   | 32.78%  |
| NVMe    | 466       | 694    | 23.98%  |
| MMC     | 63        | 76     | 3.24%   |
| Unknown | 32        | 49     | 1.65%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1107      | 2359   | 64.1%   |
| NVMe | 465       | 693    | 26.93%  |
| SAS  | 92        | 174    | 5.33%   |
| MMC  | 63        | 76     | 3.65%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 850       | 1412   | 57.82%  |
| 0.51-1.0   | 393       | 665    | 26.73%  |
| 1.01-2.0   | 124       | 212    | 8.44%   |
| 3.01-4.0   | 48        | 96     | 3.27%   |
| 4.01-10.0  | 27        | 50     | 1.84%   |
| 2.01-3.0   | 25        | 41     | 1.7%    |
| 10.01-20.0 | 3         | 7      | 0.2%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 410       | 25.88%  |
| 251-500        | 363       | 22.92%  |
| 501-1000       | 220       | 13.89%  |
| 1001-2000      | 140       | 8.84%   |
| 51-100         | 100       | 6.31%   |
| More than 3000 | 91        | 5.74%   |
| 1-20           | 89        | 5.62%   |
| 2001-3000      | 64        | 4.04%   |
| Unknown        | 61        | 3.85%   |
| 21-50          | 46        | 2.9%    |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 592       | 35.64%  |
| 21-50          | 242       | 14.57%  |
| 101-250        | 223       | 13.43%  |
| 51-100         | 172       | 10.36%  |
| 251-500        | 137       | 8.25%   |
| 501-1000       | 109       | 6.56%   |
| 1001-2000      | 67        | 4.03%   |
| Unknown        | 61        | 3.67%   |
| More than 3000 | 30        | 1.81%   |
| 2001-3000      | 28        | 1.69%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB      | 5         | 25     | 3.73%   |
| Seagate ST9500325AS 500GB            | 4         | 4      | 2.99%   |
| Seagate ST3500418AS 500GB            | 3         | 8      | 2.24%   |
| WDC WD10EZEX-21M2NA0 1TB             | 2         | 2      | 1.49%   |
| Seagate ST9750420AS 752GB            | 2         | 2      | 1.49%   |
| Seagate ST4000DM000-1F2168 4TB       | 2         | 3      | 1.49%   |
| Samsung Electronics SSD 970 EVO 1TB  | 2         | 2      | 1.49%   |
| Kingston SV300S37A120G 120GB SSD     | 2         | 2      | 1.49%   |
| Hitachi HTS545050A7E380 500GB        | 2         | 3      | 1.49%   |
| HGST HTS725050A7E630 500GB           | 2         | 2      | 1.49%   |
| WDC WDS100T2B0A-00SM50 1TB SSD       | 1         | 1      | 0.75%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 1      | 0.75%   |
| WDC WD5000AAKX-75U6AA0 500GB         | 1         | 1      | 0.75%   |
| WDC WD5000AAKX-07U6AA0 500GB         | 1         | 1      | 0.75%   |
| WDC WD5000AAKS-22A7B0 500GB          | 1         | 1      | 0.75%   |
| WDC WD5000AADS-00S9B0 500GB          | 1         | 1      | 0.75%   |
| WDC WD40EFRX-68N32N0 4TB             | 1         | 1      | 0.75%   |
| WDC WD3200BPVT-55JJ5T0 320GB         | 1         | 1      | 0.75%   |
| WDC WD3200BEVT-60A23T0 320GB         | 1         | 1      | 0.75%   |
| WDC WD3200BEKT-75PVMT1 320GB         | 1         | 4      | 0.75%   |
| WDC WD1600JS-60MHB5 160GB            | 1         | 1      | 0.75%   |
| WDC WD10SPCX-60HWST0 1TB             | 1         | 1      | 0.75%   |
| WDC WD10EZRX-00A8LB0 1TB             | 1         | 1      | 0.75%   |
| WDC WD10EARS-22Y5B1 1TB              | 1         | 1      | 0.75%   |
| WDC WD10EARS-00Y5B1 1TB              | 1         | 2      | 0.75%   |
| WDC WD10EALX-009BA0 1TB              | 1         | 1      | 0.75%   |
| WDC WD10EALS-00Z8A0 1TB              | 1         | 1      | 0.75%   |
| WDC WD10EADS-00P8B0 1TB              | 1         | 1      | 0.75%   |
| WDC WD10EADS-00M2B0 1TB              | 1         | 1      | 0.75%   |
| Toshiba MQ01ABD100 1TB               | 1         | 1      | 0.75%   |
| Toshiba MQ01ABD075 752GB             | 1         | 1      | 0.75%   |
| Toshiba MQ01ABD032 320GB             | 1         | 1      | 0.75%   |
| Toshiba MK6476GSX 640GB              | 1         | 1      | 0.75%   |
| Toshiba MK5075GSX 500GB              | 1         | 1      | 0.75%   |
| Toshiba MK1237GSX 120GB              | 1         | 1      | 0.75%   |
| Toshiba KSG60ZSE512G SATA 512GB SSD  | 1         | 1      | 0.75%   |
| SK hynix SH920 mSATA 256GB SSD       | 1         | 1      | 0.75%   |
| SK hynix SH920 2.5 7MM 256GB SSD     | 1         | 1      | 0.75%   |
| SK hynix SC401 SATA 512GB SSD        | 1         | 2      | 0.75%   |
| SK hynix PC711 HFS512GDE9X073N 512GB | 1         | 1      | 0.75%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 36        | 76     | 28.8%   |
| WDC                 | 18        | 25     | 14.4%   |
| Samsung Electronics | 13        | 15     | 10.4%   |
| Hitachi             | 10        | 11     | 8%      |
| Toshiba             | 7         | 7      | 5.6%    |
| Crucial             | 7         | 8      | 5.6%    |
| SK hynix            | 6         | 7      | 4.8%    |
| SanDisk             | 4         | 4      | 3.2%    |
| Maxtor              | 4         | 4      | 3.2%    |
| Intel               | 4         | 4      | 3.2%    |
| HGST                | 4         | 4      | 3.2%    |
| Fujitsu             | 4         | 7      | 3.2%    |
| Kingston            | 3         | 8      | 2.4%    |
| Micron Technology   | 2         | 2      | 1.6%    |
| OCZ                 | 1         | 1      | 0.8%    |
| KingFast            | 1         | 1      | 0.8%    |
| A-DATA Technology   | 1         | 1      | 0.8%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 36        | 76     | 41.38%  |
| WDC                 | 17        | 24     | 19.54%  |
| Hitachi             | 10        | 11     | 11.49%  |
| Toshiba             | 6         | 6      | 6.9%    |
| Samsung Electronics | 6         | 8      | 6.9%    |
| Maxtor              | 4         | 4      | 4.6%    |
| HGST                | 4         | 4      | 4.6%    |
| Fujitsu             | 4         | 7      | 4.6%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 85        | 140    | 69.67%  |
| SSD  | 30        | 38     | 24.59%  |
| NVMe | 7         | 7      | 5.74%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Samsung Electronics MZVLW128HEGR-000L2 128GB | 1         | 2      | 33.33%  |
| Hitachi HDS721010DLE630 1TB                  | 1         | 1      | 33.33%  |
| HGST HTS721010A9E630 1TB                     | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 2      | 33.33%  |
| Hitachi             | 1         | 1      | 33.33%  |
| HGST                | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 921       | 2063   | 58%     |
| Works    | 546       | 1050   | 34.38%  |
| Malfunc  | 118       | 185    | 7.43%   |
| Failed   | 3         | 4      | 0.19%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1029      | 55.26%  |
| AMD                              | 242       | 13%     |
| Samsung Electronics              | 208       | 11.17%  |
| SanDisk                          | 62        | 3.33%   |
| SK hynix                         | 44        | 2.36%   |
| Marvell Technology Group         | 27        | 1.45%   |
| JMicron Technology               | 27        | 1.45%   |
| ASMedia Technology               | 26        | 1.4%    |
| Toshiba America Info Systems     | 24        | 1.29%   |
| Kingston Technology Company      | 23        | 1.24%   |
| Phison Electronics               | 20        | 1.07%   |
| Nvidia                           | 20        | 1.07%   |
| Micron/Crucial Technology        | 17        | 0.91%   |
| Micron Technology                | 15        | 0.81%   |
| KIOXIA                           | 12        | 0.64%   |
| ADATA Technology                 | 9         | 0.48%   |
| Silicon Motion                   | 7         | 0.38%   |
| Union Memory (Shenzhen)          | 6         | 0.32%   |
| Solid State Storage Technology   | 6         | 0.32%   |
| Broadcom / LSI                   | 5         | 0.27%   |
| Silicon Image                    | 4         | 0.21%   |
| Seagate Technology               | 4         | 0.21%   |
| LSI Logic / Symbios Logic        | 4         | 0.21%   |
| Hewlett-Packard                  | 3         | 0.16%   |
| VIA Technologies                 | 2         | 0.11%   |
| Silicon Integrated Systems [SiS] | 2         | 0.11%   |
| Lite-On Technology               | 2         | 0.11%   |
| Apple                            | 2         | 0.11%   |
| Adaptec                          | 2         | 0.11%   |
| Realtek Semiconductor            | 1         | 0.05%   |
| PMC-Sierra                       | 1         | 0.05%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.05%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.05%   |
| Lenovo                           | 1         | 0.05%   |
| HighPoint Technologies           | 1         | 0.05%   |
| Biwin Storage Technology         | 1         | 0.05%   |
| Areca Technology                 | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 168       | 7.73%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 130       | 5.98%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 82        | 3.77%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 73        | 3.36%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 65        | 2.99%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 60        | 2.76%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 54        | 2.49%   |
| AMD 400 Series Chipset SATA Controller                                         | 45        | 2.07%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 44        | 2.02%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 36        | 1.66%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 33        | 1.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 33        | 1.52%   |
| Intel SATA Controller [RAID mode]                                              | 32        | 1.47%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 30        | 1.38%   |
| Samsung NVMe SSD Controller 980                                                | 29        | 1.33%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 28        | 1.29%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 26        | 1.2%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 26        | 1.2%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 26        | 1.2%    |
| Intel Volume Management Device NVMe RAID Controller                            | 25        | 1.15%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 25        | 1.15%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 25        | 1.15%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 24        | 1.1%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 24        | 1.1%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 24        | 1.1%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 24        | 1.1%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 22        | 1.01%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 21        | 0.97%   |
| AMD 500 Series Chipset SATA Controller                                         | 21        | 0.97%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 20        | 0.92%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 19        | 0.87%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 18        | 0.83%   |
| JMicron JMB363 SATA/IDE Controller                                             | 17        | 0.78%   |
| Intel SSD 660P Series                                                          | 17        | 0.78%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 16        | 0.74%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 16        | 0.74%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 15        | 0.69%   |
| Micron Non-Volatile memory controller                                          | 15        | 0.69%   |
| Intel Comet Lake SATA AHCI Controller                                          | 14        | 0.64%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 14        | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1066      | 56.08%  |
| NVMe | 469       | 24.67%  |
| IDE  | 212       | 11.15%  |
| RAID | 140       | 7.36%   |
| SAS  | 13        | 0.68%   |
| SCSI | 1         | 0.05%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 1154      | 78.56%  |
| AMD     | 302       | 20.56%  |
| ARM     | 11        | 0.75%   |
| Unknown | 2         | 0.14%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz             | 27        | 1.83%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 21        | 1.43%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 19        | 1.29%   |
| AMD Ryzen 5 3600 6-Core Processor             | 18        | 1.22%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 17        | 1.15%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 17        | 1.15%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 16        | 1.09%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 13        | 0.88%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 11        | 0.75%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 11        | 0.75%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 11        | 0.75%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 11        | 0.75%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 10        | 0.68%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 10        | 0.68%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 10        | 0.68%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 10        | 0.68%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 10        | 0.68%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 10        | 0.68%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 10        | 0.68%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 10        | 0.68%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 10        | 0.68%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 9         | 0.61%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 9         | 0.61%   |
| ARM Processor                                 | 9         | 0.61%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 8         | 0.54%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 8         | 0.54%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 8         | 0.54%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 8         | 0.54%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 8         | 0.54%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 8         | 0.54%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 7         | 0.48%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 7         | 0.48%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 7         | 0.48%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 7         | 0.48%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 7         | 0.48%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 7         | 0.48%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 7         | 0.48%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 7         | 0.48%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 7         | 0.48%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 6         | 0.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 361       | 24.56%  |
| Intel Core i5           | 327       | 22.24%  |
| Intel Core i3           | 102       | 6.94%   |
| Intel Core 2 Duo        | 85        | 5.78%   |
| AMD Ryzen 5             | 78        | 5.31%   |
| Other                   | 74        | 5.03%   |
| AMD Ryzen 7             | 61        | 4.15%   |
| Intel Celeron           | 38        | 2.59%   |
| Intel Xeon              | 32        | 2.18%   |
| Intel Pentium           | 27        | 1.84%   |
| AMD Ryzen 9             | 26        | 1.77%   |
| Intel Atom              | 21        | 1.43%   |
| Intel Pentium Dual-Core | 20        | 1.36%   |
| Intel Core 2 Quad       | 19        | 1.29%   |
| Intel Core 2            | 16        | 1.09%   |
| Intel Core i9           | 11        | 0.75%   |
| AMD Ryzen 7 PRO         | 11        | 0.75%   |
| AMD E1                  | 11        | 0.75%   |
| AMD Ryzen 5 PRO         | 10        | 0.68%   |
| AMD E                   | 10        | 0.68%   |
| AMD Ryzen 3             | 9         | 0.61%   |
| AMD FX                  | 9         | 0.61%   |
| AMD A8                  | 9         | 0.61%   |
| Intel Genuine           | 8         | 0.54%   |
| Intel Pentium Dual      | 7         | 0.48%   |
| AMD A6                  | 7         | 0.48%   |
| AMD A4                  | 7         | 0.48%   |
| AMD A10                 | 7         | 0.48%   |
| Intel Pentium Silver    | 5         | 0.34%   |
| Intel Pentium 4         | 5         | 0.34%   |
| AMD Phenom II X4        | 5         | 0.34%   |
| AMD Phenom              | 4         | 0.27%   |
| Intel Xeon Silver       | 3         | 0.2%    |
| Intel Celeron M         | 3         | 0.2%    |
| AMD Ryzen Threadripper  | 3         | 0.2%    |
| AMD Phenom II X6        | 3         | 0.2%    |
| AMD Athlon II X4        | 3         | 0.2%    |
| AMD Athlon II X2        | 3         | 0.2%    |
| AMD Athlon 64 X2        | 3         | 0.2%    |
| ARM BCM                 | 2         | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 568       | 38.59%  |
| 2       | 567       | 38.52%  |
| 6       | 145       | 9.85%   |
| 8       | 103       | 7%      |
| 12      | 28        | 1.9%    |
| 1       | 25        | 1.7%    |
| 10      | 10        | 0.68%   |
| 16      | 8         | 0.54%   |
| 3       | 5         | 0.34%   |
| Unknown | 5         | 0.34%   |
| 64      | 2         | 0.14%   |
| 32      | 2         | 0.14%   |
| 128     | 1         | 0.07%   |
| 24      | 1         | 0.07%   |
| 20      | 1         | 0.07%   |
| 14      | 1         | 0.07%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1449      | 98.64%  |
| 2       | 18        | 1.23%   |
| 3       | 1         | 0.07%   |
| Unknown | 1         | 0.07%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 999       | 67.87%  |
| 1       | 468       | 31.79%  |
| Unknown | 5         | 0.34%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1425      | 96.54%  |
| Unknown        | 38        | 2.57%   |
| 32-bit         | 12        | 0.81%   |
| 64-bit         | 1         | 0.07%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 297       | 19.42%  |
| 0x306a9    | 105       | 6.87%   |
| 0x206a7    | 93        | 6.08%   |
| 0x306c3    | 89        | 5.82%   |
| 0x1067a    | 59        | 3.86%   |
| 0x906e9    | 46        | 3.01%   |
| 0x906ea    | 41        | 2.68%   |
| 0x806ec    | 40        | 2.62%   |
| 0x806ea    | 40        | 2.62%   |
| 0x40651    | 35        | 2.29%   |
| 0x506e3    | 29        | 1.9%    |
| 0x306d4    | 29        | 1.9%    |
| 0x406e3    | 27        | 1.77%   |
| 0x20655    | 27        | 1.77%   |
| 0x806e9    | 25        | 1.64%   |
| 0x6fd      | 25        | 1.64%   |
| 0x08701021 | 24        | 1.57%   |
| 0x806c1    | 23        | 1.5%    |
| 0x10676    | 21        | 1.37%   |
| 0x08600106 | 17        | 1.11%   |
| 0xa0652    | 15        | 0.98%   |
| 0x106e5    | 14        | 0.92%   |
| 0x08701013 | 14        | 0.92%   |
| 0x806eb    | 13        | 0.85%   |
| 0x6fb      | 13        | 0.85%   |
| 0x6f6      | 13        | 0.85%   |
| 0x30678    | 12        | 0.78%   |
| 0x206d7    | 12        | 0.78%   |
| 0x08108109 | 11        | 0.72%   |
| 0x20652    | 10        | 0.65%   |
| 0x0a50000c | 10        | 0.65%   |
| 0x08600103 | 10        | 0.65%   |
| 0x05000119 | 10        | 0.65%   |
| 0x0a201009 | 9         | 0.59%   |
| 0x08608103 | 9         | 0.59%   |
| 0x0800820d | 9         | 0.59%   |
| 0x07030105 | 8         | 0.52%   |
| 0x010000c8 | 8         | 0.52%   |
| 0x0810100b | 7         | 0.46%   |
| 0x06001119 | 7         | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 259       | 17.62%  |
| Haswell          | 152       | 10.34%  |
| SandyBridge      | 123       | 8.37%   |
| IvyBridge        | 120       | 8.16%   |
| Zen 2            | 93        | 6.33%   |
| Penryn           | 91        | 6.19%   |
| Skylake          | 69        | 4.69%   |
| Core             | 68        | 4.63%   |
| Westmere         | 42        | 2.86%   |
| Zen+             | 36        | 2.45%   |
| Unknown          | 36        | 2.45%   |
| Zen 3            | 35        | 2.38%   |
| TigerLake        | 35        | 2.38%   |
| Broadwell        | 35        | 2.38%   |
| Silvermont       | 33        | 2.24%   |
| CometLake        | 33        | 2.24%   |
| Zen              | 24        | 1.63%   |
| Nehalem          | 22        | 1.5%    |
| K10              | 22        | 1.5%    |
| Piledriver       | 17        | 1.16%   |
| Bobcat           | 16        | 1.09%   |
| Icelake          | 13        | 0.88%   |
| Puma             | 12        | 0.82%   |
| Excavator        | 11        | 0.75%   |
| Alderlake Hybrid | 11        | 0.75%   |
| Goldmont plus    | 10        | 0.68%   |
| Bonnell          | 9         | 0.61%   |
| NetBurst         | 8         | 0.54%   |
| K8 Hammer        | 8         | 0.54%   |
| Jaguar           | 8         | 0.54%   |
| P6               | 7         | 0.48%   |
| Goldmont         | 5         | 0.34%   |
| Tremont          | 2         | 0.14%   |
| Steamroller      | 2         | 0.14%   |
| K8 & K10 hybrid  | 2         | 0.14%   |
| K10 Llano        | 1         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 824       | 47.88%  |
| Nvidia                           | 526       | 30.56%  |
| AMD                              | 356       | 20.69%  |
| Matrox Electronics Systems       | 10        | 0.58%   |
| ASPEED Technology                | 3         | 0.17%   |
| VIA Technologies                 | 1         | 0.06%   |
| Silicon Integrated Systems [SiS] | 1         | 0.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 74        | 4.17%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 74        | 4.17%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 48        | 2.7%    |
| Intel UHD Graphics 620                                                                   | 43        | 2.42%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 42        | 2.36%   |
| AMD Renoir                                                                               | 35        | 1.97%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 34        | 1.91%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 34        | 1.91%   |
| Intel HD Graphics 630                                                                    | 30        | 1.69%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 30        | 1.69%   |
| Intel HD Graphics 5500                                                                   | 27        | 1.52%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 25        | 1.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 24        | 1.35%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 24        | 1.35%   |
| Intel Core Processor Integrated Graphics Controller                                      | 24        | 1.35%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 23        | 1.3%    |
| Intel HD Graphics 620                                                                    | 21        | 1.18%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 21        | 1.18%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 18        | 1.01%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 18        | 1.01%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 18        | 1.01%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 17        | 0.96%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 16        | 0.9%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 15        | 0.84%   |
| Intel HD Graphics 530                                                                    | 15        | 0.84%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 15        | 0.84%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 14        | 0.79%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 14        | 0.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 14        | 0.79%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 13        | 0.73%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 12        | 0.68%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 12        | 0.68%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 11        | 0.62%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 11        | 0.62%   |
| AMD Lucienne                                                                             | 11        | 0.62%   |
| Nvidia GT218 [GeForce 210]                                                               | 10        | 0.56%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 10        | 0.56%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 10        | 0.56%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 10        | 0.56%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 9         | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 588       | 39.65%  |
| 1 x Nvidia         | 325       | 21.92%  |
| 1 x AMD            | 276       | 18.61%  |
| Intel + Nvidia     | 175       | 11.8%   |
| Intel + AMD        | 46        | 3.1%    |
| AMD + Nvidia       | 20        | 1.35%   |
| Other              | 17        | 1.15%   |
| 2 x AMD            | 16        | 1.08%   |
| 1 x Matrox         | 10        | 0.67%   |
| 2 x Nvidia         | 3         | 0.2%    |
| 1 x ASPEED         | 2         | 0.13%   |
| 2 x Intel          | 1         | 0.07%   |
| 1 x VIA            | 1         | 0.07%   |
| 1 x SiS            | 1         | 0.07%   |
| Nvidia + ASPEED    | 1         | 0.07%   |
| Intel + 2 x Nvidia | 1         | 0.07%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1155      | 76.9%   |
| Proprietary | 279       | 18.58%  |
| Unknown     | 68        | 4.53%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 785       | 51.64%  |
| 1.01-2.0   | 193       | 12.7%   |
| 0.01-0.5   | 187       | 12.3%   |
| 0.51-1.0   | 131       | 8.62%   |
| 3.01-4.0   | 87        | 5.72%   |
| 7.01-8.0   | 75        | 4.93%   |
| 5.01-6.0   | 38        | 2.5%    |
| 8.01-16.0  | 14        | 0.92%   |
| 2.01-3.0   | 7         | 0.46%   |
| 16.01-24.0 | 3         | 0.2%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 235       | 14.6%   |
| AU Optronics            | 223       | 13.85%  |
| LG Display              | 154       | 9.57%   |
| Chimei Innolux          | 106       | 6.58%   |
| BOE                     | 90        | 5.59%   |
| Dell                    | 87        | 5.4%    |
| Iiyama                  | 70        | 4.35%   |
| Goldstar                | 68        | 4.22%   |
| Hewlett-Packard         | 55        | 3.42%   |
| Philips                 | 52        | 3.23%   |
| BenQ                    | 36        | 2.24%   |
| Sharp                   | 35        | 2.17%   |
| AOC                     | 34        | 2.11%   |
| Acer                    | 34        | 2.11%   |
| Medion                  | 29        | 1.8%    |
| Lenovo                  | 29        | 1.8%    |
| Ancor Communications    | 28        | 1.74%   |
| Chi Mei Optoelectronics | 26        | 1.61%   |
| Apple                   | 25        | 1.55%   |
| Sony                    | 13        | 0.81%   |
| Unknown                 | 11        | 0.68%   |
| Fujitsu Siemens         | 10        | 0.62%   |
| LG Philips              | 9         | 0.56%   |
| InfoVision              | 9         | 0.56%   |
| PANDA                   | 8         | 0.5%    |
| ASUSTek Computer        | 8         | 0.5%    |
| Vestel Elektronik       | 7         | 0.43%   |
| Idek Iiyama             | 7         | 0.43%   |
| Panasonic               | 6         | 0.37%   |
| Eizo                    | 6         | 0.37%   |
| Arnos Instruments       | 6         | 0.37%   |
| Packard Bell            | 5         | 0.31%   |
| LG Electronics          | 5         | 0.31%   |
| CSO                     | 5         | 0.31%   |
| ViewSonic               | 4         | 0.25%   |
| Seiko/Epson             | 4         | 0.25%   |
| Quanta Display          | 4         | 0.25%   |
| MSI                     | 4         | 0.25%   |
| Toshiba                 | 3         | 0.19%   |
| NEC Computers           | 3         | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 15        | 0.88%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 14        | 0.82%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 9         | 0.53%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 9         | 0.53%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch            | 8         | 0.47%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch             | 8         | 0.47%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch    | 7         | 0.41%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch            | 7         | 0.41%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 7         | 0.41%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                  | 6         | 0.35%   |
| Iiyama PLX2783H IVM6611 1920x1080 598x336mm 27.0-inch                     | 6         | 0.35%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch               | 6         | 0.35%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                     | 6         | 0.35%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch         | 5         | 0.29%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch         | 5         | 0.29%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch         | 5         | 0.29%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch              | 5         | 0.29%   |
| Iiyama PL2409HD IVM560C 1920x1080 520x290mm 23.4-inch                     | 5         | 0.29%   |
| Dell U2515H DELD070 2560x1440 553x311mm 25.0-inch                         | 5         | 0.29%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch            | 5         | 0.29%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 5         | 0.29%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch             | 5         | 0.29%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                   | 4         | 0.24%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch      | 4         | 0.24%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch       | 4         | 0.24%   |
| Samsung Electronics S24R65x SAM1022 1920x1080 527x296mm 23.8-inch         | 4         | 0.24%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch         | 4         | 0.24%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch      | 4         | 0.24%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch         | 4         | 0.24%   |
| Medion MD 20430 MED36A2 1920x1080 521x293mm 23.5-inch                     | 4         | 0.24%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch              | 4         | 0.24%   |
| LG Display LCD Monitor LGD034C 1366x768 293x165mm 13.2-inch               | 4         | 0.24%   |
| Goldstar LG ULTRAGEAR GSM5B7F 2560x1440 600x340mm 27.2-inch               | 4         | 0.24%   |
| Dell U2417H DEL40E8 1920x1080 527x296mm 23.8-inch                         | 4         | 0.24%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch          | 4         | 0.24%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch           | 4         | 0.24%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch           | 4         | 0.24%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 4         | 0.24%   |
| Chi Mei Optoelectronics LCD Monitor CMO1719 1600x900 382x215mm 17.3-inch  | 4         | 0.24%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 4         | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 674       | 43.51%  |
| 1366x768 (WXGA)    | 193       | 12.46%  |
| 3840x2160 (4K)     | 119       | 7.68%   |
| 1600x900 (HD+)     | 105       | 6.78%   |
| 2560x1440 (QHD)    | 85        | 5.49%   |
| 1680x1050 (WSXGA+) | 59        | 3.81%   |
| 1280x1024 (SXGA)   | 57        | 3.68%   |
| 1440x900 (WXGA+)   | 45        | 2.91%   |
| 1920x1200 (WUXGA)  | 37        | 2.39%   |
| 1280x800 (WXGA)    | 31        | 2%      |
| Unknown            | 21        | 1.36%   |
| 3840x1080          | 16        | 1.03%   |
| 3440x1440          | 11        | 0.71%   |
| 1360x768           | 9         | 0.58%   |
| 2560x1600          | 8         | 0.52%   |
| 3840x2400          | 7         | 0.45%   |
| 2560x1080          | 7         | 0.45%   |
| 1600x1200          | 7         | 0.45%   |
| 1024x600           | 6         | 0.39%   |
| 3200x1800 (QHD+)   | 5         | 0.32%   |
| 1024x768 (XGA)     | 5         | 0.32%   |
| 2880x1800          | 4         | 0.26%   |
| 1680x945           | 4         | 0.26%   |
| 800x1280           | 3         | 0.19%   |
| 5760x1080          | 2         | 0.13%   |
| 3840x1600          | 2         | 0.13%   |
| 2960x1050          | 2         | 0.13%   |
| 2736x1824          | 2         | 0.13%   |
| 2256x1504          | 2         | 0.13%   |
| 2048x1152          | 2         | 0.13%   |
| 1920x540           | 2         | 0.13%   |
| 1920x1280          | 2         | 0.13%   |
| 1280x960           | 2         | 0.13%   |
| 7680x2160          | 1         | 0.06%   |
| 6320x1800          | 1         | 0.06%   |
| 5120x1440          | 1         | 0.06%   |
| 4480x1080          | 1         | 0.06%   |
| 3840x1200          | 1         | 0.06%   |
| 3600x1080          | 1         | 0.06%   |
| 3200x1080          | 1         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 389       | 23.97%  |
| 27      | 159       | 9.8%    |
| 17      | 147       | 9.06%   |
| 13      | 128       | 7.89%   |
| 24      | 118       | 7.27%   |
| 23      | 118       | 7.27%   |
| Unknown | 97        | 5.98%   |
| 14      | 90        | 5.55%   |
| 21      | 81        | 4.99%   |
| 19      | 46        | 2.83%   |
| 22      | 36        | 2.22%   |
| 18      | 28        | 1.73%   |
| 20      | 22        | 1.36%   |
| 12      | 21        | 1.29%   |
| 31      | 20        | 1.23%   |
| 34      | 17        | 1.05%   |
| 25      | 13        | 0.8%    |
| 11      | 11        | 0.68%   |
| 72      | 10        | 0.62%   |
| 10      | 10        | 0.62%   |
| 84      | 9         | 0.55%   |
| 16      | 8         | 0.49%   |
| 54      | 5         | 0.31%   |
| 48      | 4         | 0.25%   |
| 32      | 4         | 0.25%   |
| 65      | 3         | 0.18%   |
| 49      | 3         | 0.18%   |
| 40      | 3         | 0.18%   |
| 29      | 3         | 0.18%   |
| 52      | 2         | 0.12%   |
| 42      | 2         | 0.12%   |
| 39      | 2         | 0.12%   |
| 37      | 2         | 0.12%   |
| 33      | 2         | 0.12%   |
| 26      | 2         | 0.12%   |
| 142     | 1         | 0.06%   |
| 63      | 1         | 0.06%   |
| 55      | 1         | 0.06%   |
| 50      | 1         | 0.06%   |
| 46      | 1         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 531       | 33.23%  |
| 501-600        | 357       | 22.34%  |
| 351-400        | 184       | 11.51%  |
| 401-500        | 173       | 10.83%  |
| 201-300        | 125       | 7.82%   |
| Unknown        | 97        | 6.07%   |
| 601-700        | 56        | 3.5%    |
| 701-800        | 23        | 1.44%   |
| 1001-1500      | 21        | 1.31%   |
| 1501-2000      | 19        | 1.19%   |
| 801-900        | 7         | 0.44%   |
| 901-1000       | 3         | 0.19%   |
| More than 2000 | 1         | 0.06%   |
| 1-100          | 1         | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1063      | 73.77%  |
| 16/10   | 190       | 13.19%  |
| Unknown | 77        | 5.34%   |
| 5/4     | 52        | 3.61%   |
| 21/9    | 19        | 1.32%   |
| 4/3     | 14        | 0.97%   |
| 3/2     | 10        | 0.69%   |
| 32/9    | 6         | 0.42%   |
| 6/5     | 4         | 0.28%   |
| 1.00    | 2         | 0.14%   |
| 0.62    | 2         | 0.14%   |
| 3.73    | 1         | 0.07%   |
| 0.67    | 1         | 0.07%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 389       | 24.28%  |
| 201-250        | 275       | 17.17%  |
| 301-350        | 162       | 10.11%  |
| 81-90          | 143       | 8.93%   |
| 121-130        | 113       | 7.05%   |
| 151-200        | 102       | 6.37%   |
| Unknown        | 97        | 6.05%   |
| 71-80          | 75        | 4.68%   |
| 251-300        | 50        | 3.12%   |
| 351-500        | 47        | 2.93%   |
| More than 1000 | 33        | 2.06%   |
| 141-150        | 30        | 1.87%   |
| 131-140        | 21        | 1.31%   |
| 61-70          | 20        | 1.25%   |
| 501-1000       | 17        | 1.06%   |
| 51-60          | 11        | 0.69%   |
| 41-50          | 10        | 0.62%   |
| 111-120        | 4         | 0.25%   |
| 91-100         | 2         | 0.12%   |
| 1-40           | 1         | 0.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 516       | 33.01%  |
| 121-160       | 399       | 25.53%  |
| 101-120       | 383       | 24.5%   |
| 161-240       | 99        | 6.33%   |
| Unknown       | 97        | 6.21%   |
| More than 240 | 43        | 2.75%   |
| 1-50          | 26        | 1.66%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1168      | 77.25%  |
| 2     | 240       | 15.87%  |
| 0     | 76        | 5.03%   |
| 3     | 27        | 1.79%   |
| 4     | 1         | 0.07%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 785       | 35.39%  |
| Realtek Semiconductor             | 748       | 33.72%  |
| Qualcomm Atheros                  | 251       | 11.32%  |
| Broadcom                          | 123       | 5.55%   |
| Marvell Technology Group          | 29        | 1.31%   |
| Broadcom Limited                  | 29        | 1.31%   |
| TP-Link                           | 24        | 1.08%   |
| Ralink                            | 21        | 0.95%   |
| Nvidia                            | 19        | 0.86%   |
| D-Link System                     | 16        | 0.72%   |
| MediaTek                          | 15        | 0.68%   |
| Ralink Technology                 | 12        | 0.54%   |
| Dell                              | 10        | 0.45%   |
| ASIX Electronics                  | 10        | 0.45%   |
| Lenovo                            | 8         | 0.36%   |
| IMC Networks                      | 8         | 0.36%   |
| Sierra Wireless                   | 6         | 0.27%   |
| Microsoft                         | 6         | 0.27%   |
| Ericsson Business Mobile Networks | 6         | 0.27%   |
| DisplayLink                       | 6         | 0.27%   |
| D-Link                            | 6         | 0.27%   |
| ASUSTek Computer                  | 6         | 0.27%   |
| Linksys                           | 5         | 0.23%   |
| Microchip Technology              | 4         | 0.18%   |
| Hewlett-Packard                   | 4         | 0.18%   |
| Aquantia                          | 4         | 0.18%   |
| Sitecom Europe                    | 3         | 0.14%   |
| Samsung Electronics               | 3         | 0.14%   |
| Qualcomm Atheros Communications   | 3         | 0.14%   |
| Qualcomm                          | 3         | 0.14%   |
| JMicron Technology                | 3         | 0.14%   |
| Fibocom                           | 3         | 0.14%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.09%   |
| Motorola PCS                      | 2         | 0.09%   |
| MosChip Semiconductor             | 2         | 0.09%   |
| Huawei Technologies               | 2         | 0.09%   |
| Edimax Technology                 | 2         | 0.09%   |
| Attansic Technology               | 2         | 0.09%   |
| Arduino SA                        | 2         | 0.09%   |
| ADMtek                            | 2         | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 523       | 19.71%  |
| Intel Wi-Fi 6 AX200                                               | 101       | 3.81%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 67        | 2.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 64        | 2.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 50        | 1.88%   |
| Intel I211 Gigabit Network Connection                             | 47        | 1.77%   |
| Intel Wireless 7260                                               | 45        | 1.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 42        | 1.58%   |
| Realtek RTL8125 2.5GbE Controller                                 | 41        | 1.54%   |
| Intel Wireless 8265 / 8275                                        | 35        | 1.32%   |
| Intel Wireless 7265                                               | 33        | 1.24%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 33        | 1.24%   |
| Intel Wireless 8260                                               | 30        | 1.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 29        | 1.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 28        | 1.06%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 28        | 1.06%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 26        | 0.98%   |
| Intel Wireless-AC 9260                                            | 25        | 0.94%   |
| Intel Wi-Fi 6 AX201                                               | 25        | 0.94%   |
| Intel Ethernet Connection (2) I219-V                              | 25        | 0.94%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 24        | 0.9%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 23        | 0.87%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 22        | 0.83%   |
| Intel 82579V Gigabit Network Connection                           | 21        | 0.79%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 20        | 0.75%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 19        | 0.72%   |
| Intel Ethernet Connection I217-V                                  | 19        | 0.72%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 19        | 0.72%   |
| Intel Ethernet Connection I217-LM                                 | 18        | 0.68%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 17        | 0.64%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 17        | 0.64%   |
| Intel Ethernet Connection I218-LM                                 | 17        | 0.64%   |
| Intel Centrino Wireless-N 2230                                    | 17        | 0.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 15        | 0.57%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 14        | 0.53%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 13        | 0.49%   |
| Intel WiFi Link 5100                                              | 13        | 0.49%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 13        | 0.49%   |
| Intel Ethernet Connection (6) I219-V                              | 13        | 0.49%   |
| Intel Ethernet Connection (4) I219-V                              | 13        | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 591       | 50.69%  |
| Qualcomm Atheros                      | 195       | 16.72%  |
| Realtek Semiconductor                 | 146       | 12.52%  |
| Broadcom                              | 78        | 6.69%   |
| Ralink                                | 21        | 1.8%    |
| Broadcom Limited                      | 16        | 1.37%   |
| TP-Link                               | 14        | 1.2%    |
| D-Link System                         | 13        | 1.11%   |
| Ralink Technology                     | 12        | 1.03%   |
| MediaTek                              | 11        | 0.94%   |
| IMC Networks                          | 8         | 0.69%   |
| Sierra Wireless                       | 6         | 0.51%   |
| Microsoft                             | 6         | 0.51%   |
| D-Link                                | 6         | 0.51%   |
| ASUSTek Computer                      | 6         | 0.51%   |
| Linksys                               | 5         | 0.43%   |
| Hewlett-Packard                       | 4         | 0.34%   |
| Dell                                  | 4         | 0.34%   |
| Sitecom Europe                        | 3         | 0.26%   |
| Qualcomm Atheros Communications       | 3         | 0.26%   |
| Qualcomm                              | 3         | 0.26%   |
| Fibocom                               | 3         | 0.26%   |
| Marvell Technology Group              | 2         | 0.17%   |
| Edimax Technology                     | 2         | 0.17%   |
| Z-Com                                 | 1         | 0.09%   |
| Texas Instruments                     | 1         | 0.09%   |
| Tenda                                 | 1         | 0.09%   |
| Panasonic (Matsushita)                | 1         | 0.09%   |
| Guillemot                             | 1         | 0.09%   |
| Gemtek                                | 1         | 0.09%   |
| AVM                                   | 1         | 0.09%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 101       | 8.6%    |
| Intel Wireless 7260                                                     | 45        | 3.83%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 42        | 3.58%   |
| Intel Wireless 8265 / 8275                                              | 35        | 2.98%   |
| Intel Wireless 7265                                                     | 33        | 2.81%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 33        | 2.81%   |
| Intel Wireless 8260                                                     | 30        | 2.56%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 29        | 2.47%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 28        | 2.39%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 28        | 2.39%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 26        | 2.21%   |
| Intel Wireless-AC 9260                                                  | 25        | 2.13%   |
| Intel Wi-Fi 6 AX201                                                     | 25        | 2.13%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 24        | 2.04%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 23        | 1.96%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 20        | 1.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 19        | 1.62%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 19        | 1.62%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 17        | 1.45%   |
| Intel Centrino Wireless-N 2230                                          | 17        | 1.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 15        | 1.28%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 14        | 1.19%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 13        | 1.11%   |
| Intel WiFi Link 5100                                                    | 13        | 1.11%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 13        | 1.11%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 12        | 1.02%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 12        | 1.02%   |
| Broadcom BCM43142 802.11b/g/n                                           | 12        | 1.02%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 11        | 0.94%   |
| Intel Centrino Ultimate-N 6300                                          | 11        | 0.94%   |
| Intel Centrino Advanced-N 6235                                          | 11        | 0.94%   |
| Intel Centrino Advanced-N 6200                                          | 11        | 0.94%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 10        | 0.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 10        | 0.85%   |
| Intel Wireless 3165                                                     | 9         | 0.77%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 9         | 0.77%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 8         | 0.68%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 8         | 0.68%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 8         | 0.68%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 7         | 0.6%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 694       | 49.08%  |
| Intel                                  | 433       | 30.62%  |
| Qualcomm Atheros                       | 94        | 6.65%   |
| Broadcom                               | 60        | 4.24%   |
| Marvell Technology Group               | 27        | 1.91%   |
| Nvidia                                 | 19        | 1.34%   |
| Broadcom Limited                       | 13        | 0.92%   |
| ASIX Electronics                       | 10        | 0.71%   |
| TP-Link                                | 9         | 0.64%   |
| Lenovo                                 | 8         | 0.57%   |
| DisplayLink                            | 6         | 0.42%   |
| Microchip Technology                   | 4         | 0.28%   |
| MediaTek                               | 4         | 0.28%   |
| Aquantia                               | 4         | 0.28%   |
| Samsung Electronics                    | 3         | 0.21%   |
| JMicron Technology                     | 3         | 0.21%   |
| D-Link System                          | 3         | 0.21%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.14%   |
| Motorola PCS                           | 2         | 0.14%   |
| MosChip Semiconductor                  | 2         | 0.14%   |
| Attansic Technology                    | 2         | 0.14%   |
| ADMtek                                 | 2         | 0.14%   |
| Xiaomi                                 | 1         | 0.07%   |
| VIA Technologies                       | 1         | 0.07%   |
| Tehuti Networks                        | 1         | 0.07%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.07%   |
| OPPO Electronics                       | 1         | 0.07%   |
| OpenMoko                               | 1         | 0.07%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.07%   |
| IBM                                    | 1         | 0.07%   |
| Huawei Technologies                    | 1         | 0.07%   |
| Apple                                  | 1         | 0.07%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 523       | 36.02%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 67        | 4.61%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 64        | 4.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 50        | 3.44%   |
| Intel I211 Gigabit Network Connection                             | 47        | 3.24%   |
| Realtek RTL8125 2.5GbE Controller                                 | 41        | 2.82%   |
| Intel Ethernet Connection (2) I219-V                              | 25        | 1.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 22        | 1.52%   |
| Intel 82579V Gigabit Network Connection                           | 21        | 1.45%   |
| Intel Ethernet Connection I217-V                                  | 19        | 1.31%   |
| Intel Ethernet Connection I217-LM                                 | 18        | 1.24%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 17        | 1.17%   |
| Intel Ethernet Connection I218-LM                                 | 17        | 1.17%   |
| Intel Ethernet Connection (6) I219-V                              | 13        | 0.9%    |
| Intel Ethernet Connection (4) I219-V                              | 13        | 0.9%    |
| Intel Ethernet Controller I225-V                                  | 12        | 0.83%   |
| Intel Ethernet Connection I219-LM                                 | 12        | 0.83%   |
| Intel Ethernet Connection (2) I218-V                              | 12        | 0.83%   |
| Intel Ethernet Connection (6) I219-LM                             | 11        | 0.76%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 11        | 0.76%   |
| Intel 82567LM Gigabit Network Connection                          | 11        | 0.76%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 10        | 0.69%   |
| Intel 82566MM Gigabit Network Connection                          | 10        | 0.69%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 9         | 0.62%   |
| Intel Ethernet Connection (4) I219-LM                             | 9         | 0.62%   |
| Intel 82577LM Gigabit Network Connection                          | 9         | 0.62%   |
| Intel I210 Gigabit Network Connection                             | 8         | 0.55%   |
| Intel Ethernet Connection (3) I218-LM                             | 8         | 0.55%   |
| Intel Ethernet Connection (2) I219-LM                             | 8         | 0.55%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 7         | 0.48%   |
| Intel 82574L Gigabit Network Connection                           | 7         | 0.48%   |
| ASIX AX88179 Gigabit Ethernet                                     | 7         | 0.48%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 6         | 0.41%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 6         | 0.41%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 6         | 0.41%   |
| Nvidia MCP79 Ethernet                                             | 6         | 0.41%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 6         | 0.41%   |
| Intel Ethernet Connection (3) I218-V                              | 6         | 0.41%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 6         | 0.41%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 6         | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1329      | 53.87%  |
| WiFi     | 1110      | 44.99%  |
| Modem    | 25        | 1.01%   |
| Unknown  | 3         | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 827       | 52.88%  |
| Ethernet | 737       | 47.12%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 849       | 57.52%  |
| 1     | 543       | 36.79%  |
| 3     | 44        | 2.98%   |
| 0     | 28        | 1.9%    |
| 4     | 6         | 0.41%   |
| 5     | 3         | 0.2%    |
| 6     | 2         | 0.14%   |
| 7     | 1         | 0.07%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1117      | 73.34%  |
| Yes  | 406       | 26.66%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 446       | 51.74%  |
| Realtek Semiconductor           | 63        | 7.31%   |
| Qualcomm Atheros Communications | 53        | 6.15%   |
| Cambridge Silicon Radio         | 39        | 4.52%   |
| Broadcom                        | 38        | 4.41%   |
| IMC Networks                    | 33        | 3.83%   |
| Apple                           | 29        | 3.36%   |
| Foxconn / Hon Hai               | 26        | 3.02%   |
| Dell                            | 25        | 2.9%    |
| ASUSTek Computer                | 25        | 2.9%    |
| Lite-On Technology              | 23        | 2.67%   |
| Hewlett-Packard                 | 20        | 2.32%   |
| Toshiba                         | 10        | 1.16%   |
| Belkin Components               | 8         | 0.93%   |
| Ralink                          | 5         | 0.58%   |
| Alps Electric                   | 4         | 0.46%   |
| MediaTek                        | 3         | 0.35%   |
| Foxconn International           | 3         | 0.35%   |
| Ralink Technology               | 2         | 0.23%   |
| Marvell Semiconductor           | 2         | 0.23%   |
| Realtek                         | 1         | 0.12%   |
| Qcom                            | 1         | 0.12%   |
| Micro Star International        | 1         | 0.12%   |
| Logitech                        | 1         | 0.12%   |
| HTC (High Tech Computer)        | 1         | 0.12%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 153       | 17.73%  |
| Intel AX200 Bluetooth                                 | 99        | 11.47%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 64        | 7.42%   |
| Intel AX201 Bluetooth                                 | 55        | 6.37%   |
| Realtek Bluetooth Radio                               | 40        | 4.63%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 39        | 4.52%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 25        | 2.9%    |
| Intel Centrino Bluetooth Wireless Transceiver         | 24        | 2.78%   |
| Realtek  Bluetooth 4.2 Adapter                        | 18        | 2.09%   |
| Qualcomm Atheros  Bluetooth Device                    | 15        | 1.74%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 14        | 1.62%   |
| Apple Bluetooth Host Controller                       | 13        | 1.51%   |
| IMC Networks Bluetooth Device                         | 12        | 1.39%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]         | 12        | 1.39%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 11        | 1.27%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth            | 10        | 1.16%   |
| Intel Wireless-AC 3168 Bluetooth                      | 10        | 1.16%   |
| IMC Networks Bluetooth Radio                          | 10        | 1.16%   |
| Foxconn / Hon Hai Bluetooth Device                    | 10        | 1.16%   |
| Dell DW375 Bluetooth Module                           | 10        | 1.16%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 9         | 1.04%   |
| Apple Bluetooth USB Host Controller                   | 9         | 1.04%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 8         | 0.93%   |
| Intel AX210 Bluetooth                                 | 8         | 0.93%   |
| Broadcom HP Portable SoftSailing                      | 8         | 0.93%   |
| Lite-On Atheros AR3012 Bluetooth                      | 7         | 0.81%   |
| HP Broadcom 2070 Bluetooth Combo                      | 7         | 0.81%   |
| Dell BCM20702A0 Bluetooth Module                      | 7         | 0.81%   |
| Intel Bluetooth Device                                | 6         | 0.7%    |
| Foxconn / Hon Hai Wireless_Device                     | 6         | 0.7%    |
| Broadcom BCM2045B (BDC-2.1)                           | 6         | 0.7%    |
| Ralink RT3290 Bluetooth                               | 5         | 0.58%   |
| Lite-On Bluetooth Device                              | 5         | 0.58%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter     | 5         | 0.58%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller       | 5         | 0.58%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter | 5         | 0.58%   |
| Broadcom HP Portable Bumble Bee                       | 4         | 0.46%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 4         | 0.46%   |
| ASUS ASUS USB-BT500                                   | 4         | 0.46%   |
| Apple Bluetooth HCI                                   | 4         | 0.46%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1104      | 52.5%   |
| Nvidia                           | 396       | 18.83%  |
| AMD                              | 373       | 17.74%  |
| C-Media Electronics              | 34        | 1.62%   |
| Logitech                         | 20        | 0.95%   |
| Creative Labs                    | 16        | 0.76%   |
| Realtek Semiconductor            | 13        | 0.62%   |
| Kingston Technology              | 11        | 0.52%   |
| GN Netcom                        | 9         | 0.43%   |
| Corsair                          | 9         | 0.43%   |
| RODE Microphones                 | 6         | 0.29%   |
| Plantronics                      | 6         | 0.29%   |
| Focusrite-Novation               | 6         | 0.29%   |
| VIA Technologies                 | 5         | 0.24%   |
| Texas Instruments                | 5         | 0.24%   |
| Razer USA                        | 5         | 0.24%   |
| JMTek                            | 5         | 0.24%   |
| SteelSeries ApS                  | 4         | 0.19%   |
| Sennheiser Communications        | 4         | 0.19%   |
| Roland                           | 4         | 0.19%   |
| Hewlett-Packard                  | 4         | 0.19%   |
| Blue Microphones                 | 4         | 0.19%   |
| ASUSTek Computer                 | 4         | 0.19%   |
| Micro Star International         | 3         | 0.14%   |
| Astro Gaming                     | 3         | 0.14%   |
| Trust                            | 2         | 0.1%    |
| Sony                             | 2         | 0.1%    |
| Silicon Integrated Systems [SiS] | 2         | 0.1%    |
| OPPO Electronics                 | 2         | 0.1%    |
| M-Audio                          | 2         | 0.1%    |
| Lenovo                           | 2         | 0.1%    |
| Harman International             | 2         | 0.1%    |
| GYROCOM C&C                      | 2         | 0.1%    |
| FIFINE Microphones               | 2         | 0.1%    |
| BEHRINGER International          | 2         | 0.1%    |
| Audio-Technica                   | 2         | 0.1%    |
| Antlion Audio                    | 2         | 0.1%    |
| XMOS                             | 1         | 0.05%   |
| Xilinx                           | 1         | 0.05%   |
| Veho                             | 1         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 118       | 4.81%   |
| Intel Sunrise Point-LP HD Audio                                            | 106       | 4.32%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 104       | 4.24%   |
| AMD Family 17h/19h HD Audio Controller                                     | 100       | 4.08%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 81        | 3.3%    |
| AMD Starship/Matisse HD Audio Controller                                   | 70        | 2.86%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 64        | 2.61%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 58        | 2.37%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 57        | 2.33%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 54        | 2.2%    |
| Intel Cannon Lake PCH cAVS                                                 | 53        | 2.16%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 50        | 2.04%   |
| Intel Haswell-ULT HD Audio Controller                                      | 43        | 1.75%   |
| Intel 8 Series HD Audio Controller                                         | 43        | 1.75%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 41        | 1.67%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 39        | 1.59%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 37        | 1.51%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 37        | 1.51%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 35        | 1.43%   |
| AMD FCH Azalia Controller                                                  | 35        | 1.43%   |
| Intel 200 Series PCH HD Audio                                              | 32        | 1.31%   |
| Intel Broadwell-U Audio Controller                                         | 31        | 1.26%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 29        | 1.18%   |
| Nvidia GP107GL High Definition Audio Controller                            | 28        | 1.14%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 28        | 1.14%   |
| Nvidia GK107 HDMI Audio Controller                                         | 27        | 1.1%    |
| Nvidia High Definition Audio Controller                                    | 26        | 1.06%   |
| Intel Comet Lake PCH cAVS                                                  | 26        | 1.06%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 26        | 1.06%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 26        | 1.06%   |
| Nvidia TU106 High Definition Audio Controller                              | 24        | 0.98%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 24        | 0.98%   |
| Nvidia GF108 High Definition Audio Controller                              | 24        | 0.98%   |
| AMD Kabini HDMI/DP Audio                                                   | 24        | 0.98%   |
| Nvidia GP104 High Definition Audio Controller                              | 23        | 0.94%   |
| Intel CM238 HD Audio Controller                                            | 23        | 0.94%   |
| Nvidia GP106 High Definition Audio Controller                              | 22        | 0.9%    |
| Intel Comet Lake PCH-LP cAVS                                               | 22        | 0.9%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 20        | 0.82%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 19        | 0.78%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 195       | 22.49%  |
| SK hynix            | 166       | 19.15%  |
| Kingston            | 108       | 12.46%  |
| Corsair             | 95        | 10.96%  |
| Micron Technology   | 86        | 9.92%   |
| Unknown             | 71        | 8.19%   |
| Crucial             | 43        | 4.96%   |
| G.Skill             | 24        | 2.77%   |
| Elpida              | 17        | 1.96%   |
| Ramaxel Technology  | 13        | 1.5%    |
| Nanya Technology    | 12        | 1.38%   |
| A-DATA Technology   | 8         | 0.92%   |
| Unknown (ABCD)      | 4         | 0.46%   |
| Unifosa             | 4         | 0.46%   |
| Transcend           | 4         | 0.46%   |
| Team                | 2         | 0.23%   |
| Patriot             | 2         | 0.23%   |
| Unknown (0x8551)    | 1         | 0.12%   |
| Unknown (09D5)      | 1         | 0.12%   |
| TRS STAR            | 1         | 0.12%   |
| Timetec             | 1         | 0.12%   |
| TakeMS              | 1         | 0.12%   |
| Qimonda             | 1         | 0.12%   |
| PNY                 | 1         | 0.12%   |
| J&A Information     | 1         | 0.12%   |
| Goodram             | 1         | 0.12%   |
| GeIL                | 1         | 0.12%   |
| Corsair SerNum0     | 1         | 0.12%   |
| A-DA                | 1         | 0.12%   |
| Unknown             | 1         | 0.12%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 13        | 1.4%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 9         | 0.97%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 9         | 0.97%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 9         | 0.97%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 8         | 0.86%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 8         | 0.86%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s            | 8         | 0.86%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.75%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 0.75%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 7         | 0.75%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.65%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 6         | 0.65%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 6         | 0.65%   |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s          | 5         | 0.54%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 5         | 0.54%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.54%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.54%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.54%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 5         | 0.54%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 5         | 0.54%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 5         | 0.54%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 4         | 0.43%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 4         | 0.43%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 4         | 0.43%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 4         | 0.43%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 4         | 0.43%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 4         | 0.43%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 0.43%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s                  | 4         | 0.43%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 0.43%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.43%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.43%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.43%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.43%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR 2048MT/s            | 4         | 0.43%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM 1600MT/s                   | 4         | 0.43%   |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 4         | 0.43%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 4         | 0.43%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s            | 4         | 0.43%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s           | 4         | 0.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 368       | 47%     |
| DDR3    | 275       | 35.12%  |
| DDR2    | 45        | 5.75%   |
| SDRAM   | 31        | 3.96%   |
| LPDDR3  | 23        | 2.94%   |
| LPDDR4  | 18        | 2.3%    |
| Unknown | 17        | 2.17%   |
| DDR     | 3         | 0.38%   |
| LPDDR5  | 2         | 0.26%   |
| DDR5    | 1         | 0.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 441       | 57.8%   |
| DIMM         | 273       | 35.78%  |
| Row Of Chips | 42        | 5.5%    |
| Chip         | 4         | 0.52%   |
| FB-DIMM      | 2         | 0.26%   |
| RIMM         | 1         | 0.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 306       | 37.05%  |
| 4096  | 230       | 27.85%  |
| 16384 | 136       | 16.46%  |
| 2048  | 100       | 12.11%  |
| 1024  | 31        | 3.75%   |
| 32768 | 19        | 2.3%    |
| 512   | 4         | 0.48%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 180       | 21.51%  |
| 3200    | 123       | 14.7%   |
| 2667    | 119       | 14.22%  |
| 2400    | 65        | 7.77%   |
| 1333    | 62        | 7.41%   |
| 2133    | 47        | 5.62%   |
| 667     | 28        | 3.35%   |
| 3600    | 25        | 2.99%   |
| 1334    | 24        | 2.87%   |
| 800     | 17        | 2.03%   |
| Unknown | 13        | 1.55%   |
| 1067    | 12        | 1.43%   |
| 1867    | 10        | 1.19%   |
| 3466    | 9         | 1.08%   |
| 2048    | 9         | 1.08%   |
| 4267    | 8         | 0.96%   |
| 3866    | 7         | 0.84%   |
| 3400    | 7         | 0.84%   |
| 3000    | 7         | 0.84%   |
| 2666    | 7         | 0.84%   |
| 1800    | 7         | 0.84%   |
| 1066    | 7         | 0.84%   |
| 3266    | 4         | 0.48%   |
| 975     | 4         | 0.48%   |
| 533     | 4         | 0.48%   |
| 4199    | 3         | 0.36%   |
| 3100    | 3         | 0.36%   |
| 1866    | 3         | 0.36%   |
| 8400    | 2         | 0.24%   |
| 6400    | 2         | 0.24%   |
| 4800    | 2         | 0.24%   |
| 3733    | 2         | 0.24%   |
| 1639    | 2         | 0.24%   |
| 5200    | 1         | 0.12%   |
| 4266    | 1         | 0.12%   |
| 3666    | 1         | 0.12%   |
| 3020    | 1         | 0.12%   |
| 2933    | 1         | 0.12%   |
| 2747    | 1         | 0.12%   |
| 2733    | 1         | 0.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 18        | 40.91%  |
| Brother Industries  | 11        | 25%     |
| Canon               | 5         | 11.36%  |
| Seiko Epson         | 3         | 6.82%   |
| Samsung Electronics | 3         | 6.82%   |
| Ricoh               | 1         | 2.27%   |
| Prolific Technology | 1         | 2.27%   |
| Kyocera             | 1         | 2.27%   |
| Dymo-CoStar         | 1         | 2.27%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Samsung ML-1660 Series                                     | 2         | 4.44%   |
| HP ENVY 4500 series                                        | 2         | 4.44%   |
| HP DeskJet 3630 series                                     | 2         | 4.44%   |
| Seiko Epson WF-3010 Series                                 | 1         | 2.22%   |
| Seiko Epson L3150 Series                                   | 1         | 2.22%   |
| Seiko Epson ET-4750 [WorkForce ET-4750 EcoTank All-in-One] | 1         | 2.22%   |
| Samsung SCX-472x Series                                    | 1         | 2.22%   |
| Ricoh SP C250SF                                            | 1         | 2.22%   |
| Prolific PL2305 Parallel Port                              | 1         | 2.22%   |
| Kyocera TASKalfa 250ci                                     | 1         | 2.22%   |
| HP OfficeJet Pro 6960                                      | 1         | 2.22%   |
| HP OfficeJet Pro 69                                        | 1         | 2.22%   |
| HP LaserJet Professional P 1102w                           | 1         | 2.22%   |
| HP LaserJet Pro M148f-M149f                                | 1         | 2.22%   |
| HP LaserJet P4015                                          | 1         | 2.22%   |
| HP LaserJet 1015                                           | 1         | 2.22%   |
| HP EWS UPD                                                 | 1         | 2.22%   |
| HP ENVY Photo 6200 series                                  | 1         | 2.22%   |
| HP ENVY 5540 series                                        | 1         | 2.22%   |
| HP ENVY 4520 series                                        | 1         | 2.22%   |
| HP Deskjet F4500 series                                    | 1         | 2.22%   |
| HP DeskJet F300 series                                     | 1         | 2.22%   |
| HP DeskJet 5650c                                           | 1         | 2.22%   |
| HP DeskJet 5150c                                           | 1         | 2.22%   |
| Dymo-CoStar LabelWriter 450                                | 1         | 2.22%   |
| Canon TS5100 series                                        | 1         | 2.22%   |
| Canon PIXMA MX920 Series                                   | 1         | 2.22%   |
| Canon PIXMA MP240                                          | 1         | 2.22%   |
| Canon MG5700 series                                        | 1         | 2.22%   |
| Canon iP4900 series                                        | 1         | 2.22%   |
| Brother Printer                                            | 1         | 2.22%   |
| Brother MFC-L2710DW series                                 | 1         | 2.22%   |
| Brother MFC-J6530DW                                        | 1         | 2.22%   |
| Brother MFC-J5730DW                                        | 1         | 2.22%   |
| Brother MFC-J491DW                                         | 1         | 2.22%   |
| Brother HL-4150CDN series                                  | 1         | 2.22%   |
| Brother HL-2130 series                                     | 1         | 2.22%   |
| Brother HL-2030 Laser Printer                              | 1         | 2.22%   |
| Brother HL-1110 series                                     | 1         | 2.22%   |
| Brother DCP-L2520DW                                        | 1         | 2.22%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Seiko Epson     | 5         | 33.33%  |
| Hewlett-Packard | 5         | 33.33%  |
| Canon           | 4         | 26.67%  |
| AGFA-Gevaert NV | 1         | 6.67%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson GT-X900 [Perfection V700/V750 Photo]        | 1         | 6.67%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]             | 1         | 6.67%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1         | 6.67%   |
| Seiko Epson GT-F700 [Perfection V350]                   | 1         | 6.67%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]       | 1         | 6.67%   |
| HP scanjet 8270                                         | 1         | 6.67%   |
| HP ScanJet 4370                                         | 1         | 6.67%   |
| HP ScanJet 3800c                                        | 1         | 6.67%   |
| HP ScanJet 3670                                         | 1         | 6.67%   |
| HP ScanJet 3400cse                                      | 1         | 6.67%   |
| Canon CanoScan N670U/N676U/LiDE 20                      | 1         | 6.67%   |
| Canon CanoScan LiDE 210                                 | 1         | 6.67%   |
| Canon CanoScan LiDE 110                                 | 1         | 6.67%   |
| Canon CanoScan 3200F                                    | 1         | 6.67%   |
| AGFA-Gevaert NV Snapscan e40                            | 1         | 6.67%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 209       | 23.4%   |
| Microdia                               | 98        | 10.97%  |
| Realtek Semiconductor                  | 74        | 8.29%   |
| Logitech                               | 68        | 7.61%   |
| IMC Networks                           | 63        | 7.05%   |
| Acer                                   | 61        | 6.83%   |
| Sunplus Innovation Technology          | 44        | 4.93%   |
| Suyin                                  | 32        | 3.58%   |
| Lite-On Technology                     | 31        | 3.47%   |
| Quanta                                 | 28        | 3.14%   |
| Cheng Uei Precision Industry (Foxlink) | 28        | 3.14%   |
| Syntek                                 | 25        | 2.8%    |
| Apple                                  | 25        | 2.8%    |
| Alcor Micro                            | 13        | 1.46%   |
| Ricoh                                  | 12        | 1.34%   |
| Luxvisions Innotech Limited            | 8         | 0.9%    |
| Samsung Electronics                    | 7         | 0.78%   |
| Silicon Motion                         | 5         | 0.56%   |
| Lenovo                                 | 4         | 0.45%   |
| Creative Technology                    | 4         | 0.45%   |
| Z-Star Microelectronics                | 3         | 0.34%   |
| Trust                                  | 3         | 0.34%   |
| Primax Electronics                     | 3         | 0.34%   |
| Microsoft                              | 3         | 0.34%   |
| Importek                               | 3         | 0.34%   |
| Generalplus Technology                 | 3         | 0.34%   |
| ALi                                    | 3         | 0.34%   |
| WaveRider Communications               | 2         | 0.22%   |
| Technologies                           | 2         | 0.22%   |
| Sunplus Technology                     | 2         | 0.22%   |
| KYE Systems (Mouse Systems)            | 2         | 0.22%   |
| Jieli Technology                       | 2         | 0.22%   |
| DJKANA19IDX53W                         | 2         | 0.22%   |
| Valve Software                         | 1         | 0.11%   |
| Sweex                                  | 1         | 0.11%   |
| SunplusIT                              | 1         | 0.11%   |
| Pixart Imaging                         | 1         | 0.11%   |
| Panasonic (Matsushita)                 | 1         | 0.11%   |
| OmniVision Technologies                | 1         | 0.11%   |
| Novatek Microelectronics               | 1         | 0.11%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD             | 32        | 3.56%   |
| Microdia Integrated_Webcam_HD            | 30        | 3.33%   |
| Chicony Integrated Camera                | 29        | 3.22%   |
| IMC Networks Integrated Camera           | 26        | 2.89%   |
| Chicony HD Webcam                        | 18        | 2%      |
| Acer Integrated Camera                   | 18        | 2%      |
| Microdia Integrated Webcam               | 16        | 1.78%   |
| Syntek Integrated Camera                 | 15        | 1.67%   |
| IMC Networks USB2.0 HD UVC WebCam        | 13        | 1.44%   |
| Chicony HP HD Webcam                     | 12        | 1.33%   |
| Realtek USB Camera                       | 11        | 1.22%   |
| Lite-On HP HD Camera                     | 11        | 1.22%   |
| Chicony USB2.0 Camera                    | 11        | 1.22%   |
| Logitech HD Webcam C525                  | 10        | 1.11%   |
| Chicony HP Wide Vision HD Camera         | 10        | 1.11%   |
| Lite-On Integrated Camera                | 9         | 1%      |
| Chicony HP HD Camera                     | 9         | 1%      |
| Sunplus HD WebCam                        | 8         | 0.89%   |
| Quanta HP HD Camera                      | 8         | 0.89%   |
| Chicony USB2.0 HD UVC WebCam             | 8         | 0.89%   |
| Chicony TOSHIBA Web Camera - HD          | 8         | 0.89%   |
| Apple iPhone 5/5C/5S/6/SE                | 8         | 0.89%   |
| Apple Built-in iSight                    | 8         | 0.89%   |
| Acer BisonCam, NB Pro                    | 8         | 0.89%   |
| Samsung Galaxy series, misc. (MTP mode)  | 7         | 0.78%   |
| Microdia Camera                          | 7         | 0.78%   |
| Logitech Webcam C270                     | 7         | 0.78%   |
| Logitech C922 Pro Stream Webcam          | 7         | 0.78%   |
| Chicony Integrated Camera (1280x720@30)  | 7         | 0.78%   |
| Chicony EasyCamera                       | 7         | 0.78%   |
| Acer BisonCam,NB Pro                     | 7         | 0.78%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 6         | 0.67%   |
| Microdia Laptop_Integrated_Webcam_2M     | 6         | 0.67%   |
| Logitech HD Pro Webcam C920              | 6         | 0.67%   |
| Lite-On HP HD Webcam                     | 6         | 0.67%   |
| Chicony USB 2.0 Camera                   | 6         | 0.67%   |
| Chicony Integrated HP HD Webcam          | 6         | 0.67%   |
| Acer HD Webcam                           | 6         | 0.67%   |
| Sunplus Integrated_Webcam_HD             | 5         | 0.56%   |
| Sunplus Asus Webcam                      | 5         | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 71        | 36.98%  |
| Validity Sensors           | 65        | 33.85%  |
| Shenzhen Goodix Technology | 20        | 10.42%  |
| AuthenTec                  | 13        | 6.77%   |
| LighTuning Technology      | 9         | 4.69%   |
| STMicroelectronics         | 6         | 3.13%   |
| Upek                       | 5         | 2.6%    |
| Elan Microelectronics      | 2         | 1.04%   |
| DigitalPersona             | 1         | 0.52%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 26        | 13.54%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 21        | 10.94%  |
| Unknown                                                                    | 19        | 9.9%    |
| Shenzhen Goodix  Fingerprint Device                                        | 9         | 4.69%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 8         | 4.17%   |
| Shenzhen Goodix Fingerprint Reader                                         | 8         | 4.17%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 6         | 3.13%   |
| Synaptics  WBDI                                                            | 6         | 3.13%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 6         | 3.13%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 3.13%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 3.13%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 6         | 3.13%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 6         | 3.13%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 2.6%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 5         | 2.6%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 5         | 2.6%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 2.08%   |
| AuthenTec AES2810                                                          | 4         | 2.08%   |
| Validity Sensors VFS491                                                    | 3         | 1.56%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 1.56%   |
| Synaptics WBDI Device                                                      | 3         | 1.56%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 1.56%   |
| AuthenTec AES1600                                                          | 3         | 1.56%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 1.04%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 1.04%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 1.04%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 1.04%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 1.04%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 1.04%   |
| LighTuning Fingerprint Reader                                              | 2         | 1.04%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.52%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.52%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 0.52%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.52%   |
| Elan ELAN:Fingerprint                                                      | 1         | 0.52%   |
| Elan ELAN:ARM-M4                                                           | 1         | 0.52%   |
| DigitalPersona Fingerprint Reader                                          | 1         | 0.52%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 53        | 32.92%  |
| Alcor Micro                       | 42        | 26.09%  |
| VASCO Data Security International | 18        | 11.18%  |
| Realtek Semiconductor             | 13        | 8.07%   |
| O2 Micro                          | 13        | 8.07%   |
| Lenovo                            | 8         | 4.97%   |
| OmniKey                           | 3         | 1.86%   |
| Advanced Card Systems             | 3         | 1.86%   |
| Upek                              | 2         | 1.24%   |
| Yubico.com                        | 1         | 0.62%   |
| SCM Microsystems                  | 1         | 0.62%   |
| Integrated Technology Express     | 1         | 0.62%   |
| Gemalto (was Gemplus)             | 1         | 0.62%   |
| Clay Logic                        | 1         | 0.62%   |
| Cherry                            | 1         | 0.62%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 41        | 25.47%  |
| Broadcom 58200                                                               | 18        | 11.18%  |
| Broadcom BCM5880 Secure Applications Processor                               | 15        | 9.32%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 13        | 8.07%   |
| Broadcom 5880                                                                | 12        | 7.45%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 10        | 6.21%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 10        | 6.21%   |
| VASCO Data Security International DIGIPASS 870                               | 8         | 4.97%   |
| Lenovo Integrated Smart Card Reader                                          | 8         | 4.97%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 8         | 4.97%   |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 1.86%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 3         | 1.86%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 1.24%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 1.24%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.62%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.62%   |
| OmniKey CardMan 4321                                                         | 1         | 0.62%   |
| Integrated Technology Express SmartCard Reader                               | 1         | 0.62%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.62%   |
| Clay Logic Nitrokey Start                                                    | 1         | 0.62%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.62%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.62%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 994       | 65.44%  |
| 1     | 419       | 27.58%  |
| 2     | 84        | 5.53%   |
| 3     | 13        | 0.86%   |
| 4     | 6         | 0.39%   |
| 6     | 2         | 0.13%   |
| 5     | 1         | 0.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 187       | 30.06%  |
| Graphics card            | 110       | 17.68%  |
| Chipcard                 | 110       | 17.68%  |
| Net/wireless             | 57        | 9.16%   |
| Multimedia controller    | 34        | 5.47%   |
| Communication controller | 23        | 3.7%    |
| Unassigned class         | 16        | 2.57%   |
| Bluetooth                | 15        | 2.41%   |
| Camera                   | 14        | 2.25%   |
| Card reader              | 13        | 2.09%   |
| Storage                  | 11        | 1.77%   |
| Sound                    | 9         | 1.45%   |
| Net/ethernet             | 9         | 1.45%   |
| Flash memory             | 4         | 0.64%   |
| Network                  | 3         | 0.48%   |
| Modem                    | 3         | 0.48%   |
| Dvb card                 | 2         | 0.32%   |
| Storage/raid             | 1         | 0.16%   |
| Storage/ide              | 1         | 0.16%   |

