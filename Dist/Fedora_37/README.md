Fedora 37 - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Fedora 37.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Fedora_37/Desktop/README.md) and [notebooks](/Dist/Fedora_37/Notebook/README.md).

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

Total: 2993

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkBook 13s-IWL 20R9      | Notebook    | [eaa68fe0f5](https://linux-hardware.org/?probe=eaa68fe0f5) | Dec 27, 2023 |
| ASUSTek       | P5B                         | Desktop     | [a700c11a65](https://linux-hardware.org/?probe=a700c11a65) | Dec 19, 2023 |
| Lenovo        | IdeaPad Slim 9 14ITL5 82... | Notebook    | [9e217a08be](https://linux-hardware.org/?probe=9e217a08be) | Dec 16, 2023 |
| HP            | OMEN by Laptop 15-dh1xxx    | Notebook    | [6a493a834d](https://linux-hardware.org/?probe=6a493a834d) | Dec 14, 2023 |
| HP            | OMEN by Laptop 15-dh1xxx    | Notebook    | [9d34609e0d](https://linux-hardware.org/?probe=9d34609e0d) | Dec 14, 2023 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [d31e9bc5eb](https://linux-hardware.org/?probe=d31e9bc5eb) | Dec 10, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [140789380e](https://linux-hardware.org/?probe=140789380e) | Dec 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [2cc6eaff05](https://linux-hardware.org/?probe=2cc6eaff05) | Dec 08, 2023 |
| BESSTAR Te... | UM350                       | Desktop     | [28b627c64a](https://linux-hardware.org/?probe=28b627c64a) | Dec 03, 2023 |
| Dynabook      | PORTEGE X50-G               | Notebook    | [65a2f2f3d5](https://linux-hardware.org/?probe=65a2f2f3d5) | Dec 01, 2023 |
| HP            | EliteBook 850 G6            | Notebook    | [597c5faf3a](https://linux-hardware.org/?probe=597c5faf3a) | Nov 27, 2023 |
| Matsushita... | CF-30FCDALAM                | Notebook    | [94d60b91d5](https://linux-hardware.org/?probe=94d60b91d5) | Nov 25, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [2b2ac91a50](https://linux-hardware.org/?probe=2b2ac91a50) | Nov 24, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [a8112be1bd](https://linux-hardware.org/?probe=a8112be1bd) | Nov 16, 2023 |
| Lenovo        | ThinkPad T490 20N2000NRT    | Notebook    | [fa750668a7](https://linux-hardware.org/?probe=fa750668a7) | Nov 15, 2023 |
| ASUSTek       | W580/SYS                    | Desktop     | [31a696a5bc](https://linux-hardware.org/?probe=31a696a5bc) | Nov 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [47d681f4e6](https://linux-hardware.org/?probe=47d681f4e6) | Nov 13, 2023 |
| Lenovo        | ThinkPad T490 20N2000NRT    | Notebook    | [fe5dd30b3d](https://linux-hardware.org/?probe=fe5dd30b3d) | Nov 10, 2023 |
| Lenovo        | ThinkPad L380 Yoga 20M7S... | Convertible | [d82b317402](https://linux-hardware.org/?probe=d82b317402) | Nov 07, 2023 |
| ASUSTek       | N552VW                      | Notebook    | [b8f226f7f0](https://linux-hardware.org/?probe=b8f226f7f0) | Nov 07, 2023 |
| Dell          | 05GD68 A00                  | Desktop     | [222146ef15](https://linux-hardware.org/?probe=222146ef15) | Nov 06, 2023 |
| HP            | Dragonfly Folio 13.5 inc... | Notebook    | [ffb075a639](https://linux-hardware.org/?probe=ffb075a639) | Oct 24, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [3d211c5277](https://linux-hardware.org/?probe=3d211c5277) | Oct 24, 2023 |
| ASUSTek       | X510UQ                      | Notebook    | [0494369566](https://linux-hardware.org/?probe=0494369566) | Oct 12, 2023 |
| HP            | 802F                        | Desktop     | [ed3a09f912](https://linux-hardware.org/?probe=ed3a09f912) | Oct 12, 2023 |
| HP            | 802F                        | Desktop     | [c2b0f9720e](https://linux-hardware.org/?probe=c2b0f9720e) | Oct 12, 2023 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | Notebook    | [60a4c67d48](https://linux-hardware.org/?probe=60a4c67d48) | Oct 09, 2023 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | Notebook    | [65a1ff3587](https://linux-hardware.org/?probe=65a1ff3587) | Oct 09, 2023 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | Notebook    | [a1ae219e54](https://linux-hardware.org/?probe=a1ae219e54) | Oct 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [ee95e8f5fd](https://linux-hardware.org/?probe=ee95e8f5fd) | Oct 05, 2023 |
| Dell          | Inspiron 5459               | Notebook    | [965f7580d3](https://linux-hardware.org/?probe=965f7580d3) | Oct 05, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [2447ea5d85](https://linux-hardware.org/?probe=2447ea5d85) | Oct 04, 2023 |
| HP            | EliteBook 735 G5            | Notebook    | [5600a75dba](https://linux-hardware.org/?probe=5600a75dba) | Oct 04, 2023 |
| HP            | 802E                        | Desktop     | [2d84b83c17](https://linux-hardware.org/?probe=2d84b83c17) | Oct 03, 2023 |
| HP            | 802E                        | Desktop     | [10fcb68621](https://linux-hardware.org/?probe=10fcb68621) | Oct 03, 2023 |
| Supermicro    | H8DM8-2                     | Desktop     | [5386350e20](https://linux-hardware.org/?probe=5386350e20) | Oct 03, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [7a670fe0ef](https://linux-hardware.org/?probe=7a670fe0ef) | Sep 30, 2023 |
| HP            | EliteBook 745 G3            | Notebook    | [700c901144](https://linux-hardware.org/?probe=700c901144) | Sep 30, 2023 |
| HP            | EliteBook 745 G3            | Notebook    | [16f4068970](https://linux-hardware.org/?probe=16f4068970) | Sep 30, 2023 |
| HP            | ProBook 430 G5              | Notebook    | [9e68b6e2be](https://linux-hardware.org/?probe=9e68b6e2be) | Sep 28, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [a90c8128d1](https://linux-hardware.org/?probe=a90c8128d1) | Sep 26, 2023 |
| ASRock        | B150M Pro4/Hyper            | Desktop     | [6bd5055b96](https://linux-hardware.org/?probe=6bd5055b96) | Sep 24, 2023 |
| Dell          | 060J9C A00                  | Mini pc     | [338cbff584](https://linux-hardware.org/?probe=338cbff584) | Sep 23, 2023 |
| Dell          | 00010C A00                  | Desktop     | [40d7defca4](https://linux-hardware.org/?probe=40d7defca4) | Sep 23, 2023 |
| Dell          | 0PP150 A00                  | Desktop     | [766815ba45](https://linux-hardware.org/?probe=766815ba45) | Sep 22, 2023 |
| Lenovo        | ThinkPad P50 20EQS0VV2S     | Notebook    | [b7d1f6f3cf](https://linux-hardware.org/?probe=b7d1f6f3cf) | Sep 20, 2023 |
| MSI           | Summit E15 A11SCST          | Notebook    | [aa908f1cea](https://linux-hardware.org/?probe=aa908f1cea) | Sep 19, 2023 |
| Samsung       | 940X5M                      | Convertible | [94c453eda5](https://linux-hardware.org/?probe=94c453eda5) | Sep 19, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [d00d3fed03](https://linux-hardware.org/?probe=d00d3fed03) | Sep 18, 2023 |
| HP            | 84FD                        | Desktop     | [d0845ca4d2](https://linux-hardware.org/?probe=d0845ca4d2) | Sep 15, 2023 |
| Lenovo        | G505 20240                  | Notebook    | [db2962124c](https://linux-hardware.org/?probe=db2962124c) | Sep 14, 2023 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [172b7a1d48](https://linux-hardware.org/?probe=172b7a1d48) | Sep 13, 2023 |
| Dell          | 0GXM1W A01                  | Desktop     | [ff9bf89fad](https://linux-hardware.org/?probe=ff9bf89fad) | Sep 11, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [92762d264f](https://linux-hardware.org/?probe=92762d264f) | Sep 11, 2023 |
| Dell          | 0GM819                      | Desktop     | [f7d8bdb2a3](https://linux-hardware.org/?probe=f7d8bdb2a3) | Sep 10, 2023 |
| HP            | ProBook 440 14 inch G9 N... | Notebook    | [b37cf7f8cf](https://linux-hardware.org/?probe=b37cf7f8cf) | Aug 30, 2023 |
| ASUSTek       | TUF Z370-PLUS GAMING        | Desktop     | [b93e0fc32b](https://linux-hardware.org/?probe=b93e0fc32b) | Aug 30, 2023 |
| HP            | Laptop 17-by0xxx            | Notebook    | [4617fe766a](https://linux-hardware.org/?probe=4617fe766a) | Aug 29, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [44e98cb157](https://linux-hardware.org/?probe=44e98cb157) | Aug 29, 2023 |
| MSI           | Z370-A PRO                  | Desktop     | [d9a6d27a28](https://linux-hardware.org/?probe=d9a6d27a28) | Aug 29, 2023 |
| ASUSTek       | TUF Z370-PLUS GAMING        | Desktop     | [7da432892e](https://linux-hardware.org/?probe=7da432892e) | Aug 29, 2023 |
| Dell          | 0GXM1W A01                  | Desktop     | [9bd4ef3aac](https://linux-hardware.org/?probe=9bd4ef3aac) | Aug 26, 2023 |
| Dell          | 0GXM1W A01                  | Desktop     | [978f1e9fa5](https://linux-hardware.org/?probe=978f1e9fa5) | Aug 26, 2023 |
| MSI           | MS-B9321                    | Desktop     | [07564a2fc4](https://linux-hardware.org/?probe=07564a2fc4) | Aug 25, 2023 |
| Dell          | 0HHV7N A00                  | Desktop     | [1bcc49b615](https://linux-hardware.org/?probe=1bcc49b615) | Aug 25, 2023 |
| MSI           | MS-B9321                    | Desktop     | [df54486a48](https://linux-hardware.org/?probe=df54486a48) | Aug 25, 2023 |
| HP            | OMEN by Laptop 15-dh1xxx    | Notebook    | [6e84e686ec](https://linux-hardware.org/?probe=6e84e686ec) | Aug 25, 2023 |
| ASUSTek       | X540UP                      | Notebook    | [7041925c33](https://linux-hardware.org/?probe=7041925c33) | Aug 23, 2023 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [fed21c9b13](https://linux-hardware.org/?probe=fed21c9b13) | Aug 23, 2023 |
| Toshiba       | Satellite L515              | Notebook    | [fa5d7d5547](https://linux-hardware.org/?probe=fa5d7d5547) | Aug 23, 2023 |
| ASUSTek       | CM6870                      | Desktop     | [05507d2151](https://linux-hardware.org/?probe=05507d2151) | Aug 20, 2023 |
| ASUSTek       | CM6870                      | Desktop     | [b91ffcb2be](https://linux-hardware.org/?probe=b91ffcb2be) | Aug 20, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [34f09bffb0](https://linux-hardware.org/?probe=34f09bffb0) | Aug 20, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [bbf57bf744](https://linux-hardware.org/?probe=bbf57bf744) | Aug 17, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [12c4ed323e](https://linux-hardware.org/?probe=12c4ed323e) | Aug 15, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81G3      | Notebook    | [83879b8247](https://linux-hardware.org/?probe=83879b8247) | Aug 11, 2023 |
| Fujitsu       | UH-X                        | Notebook    | [e26b430aef](https://linux-hardware.org/?probe=e26b430aef) | Aug 09, 2023 |
| Microsoft     | Surface Pro 6               | Tablet      | [d9513873ac](https://linux-hardware.org/?probe=d9513873ac) | Aug 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [2980681052](https://linux-hardware.org/?probe=2980681052) | Aug 07, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [08b395f8d6](https://linux-hardware.org/?probe=08b395f8d6) | Aug 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [4dec7b692a](https://linux-hardware.org/?probe=4dec7b692a) | Aug 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [2771828543](https://linux-hardware.org/?probe=2771828543) | Aug 06, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [8add0a69cc](https://linux-hardware.org/?probe=8add0a69cc) | Aug 05, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [9a4f9f590c](https://linux-hardware.org/?probe=9a4f9f590c) | Aug 04, 2023 |
| HP            | ENVY Laptop 16-h1xxx        | Notebook    | [ca0d3636a5](https://linux-hardware.org/?probe=ca0d3636a5) | Aug 03, 2023 |
| Lenovo        | ThinkPad X240 20AMS1RR0D    | Notebook    | [dcf2bedb58](https://linux-hardware.org/?probe=dcf2bedb58) | Aug 03, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [41cc0d3bfc](https://linux-hardware.org/?probe=41cc0d3bfc) | Aug 01, 2023 |
| MSI           | GE75 Raider 10SE            | Notebook    | [995b9ae73e](https://linux-hardware.org/?probe=995b9ae73e) | Jul 31, 2023 |
| ASUSTek       | M4A89TD PRO USB3            | Desktop     | [bcfe09b617](https://linux-hardware.org/?probe=bcfe09b617) | Jul 29, 2023 |
| ECS           | H61H2-M17                   | Desktop     | [360623689a](https://linux-hardware.org/?probe=360623689a) | Jul 29, 2023 |
| ECS           | H61H2-M17                   | Desktop     | [aa0f0813e4](https://linux-hardware.org/?probe=aa0f0813e4) | Jul 29, 2023 |
| ASUSTek       | PRIME X570-P                | Notebook    | [fa1452d305](https://linux-hardware.org/?probe=fa1452d305) | Jul 28, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [87d69792fb](https://linux-hardware.org/?probe=87d69792fb) | Jul 26, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [83097985a2](https://linux-hardware.org/?probe=83097985a2) | Jul 26, 2023 |
| Gigabyte      | H61MS                       | Desktop     | [545d840e2f](https://linux-hardware.org/?probe=545d840e2f) | Jul 23, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [6c0c0671df](https://linux-hardware.org/?probe=6c0c0671df) | Jul 23, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20HE... | Notebook    | [e6320dd4ae](https://linux-hardware.org/?probe=e6320dd4ae) | Jul 22, 2023 |
| Toshiba       | TECRA A50-A                 | Notebook    | [e96ff00334](https://linux-hardware.org/?probe=e96ff00334) | Jul 21, 2023 |
| Dell          | 00010C A00                  | Desktop     | [71eca6ee4c](https://linux-hardware.org/?probe=71eca6ee4c) | Jul 20, 2023 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [a1f316c8c9](https://linux-hardware.org/?probe=a1f316c8c9) | Jul 20, 2023 |
| Lenovo        | ThinkPad T61 6465CTO        | Notebook    | [fcf6ce5b9e](https://linux-hardware.org/?probe=fcf6ce5b9e) | Jul 13, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [c09e539c94](https://linux-hardware.org/?probe=c09e539c94) | Jul 09, 2023 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [b4d926a4bc](https://linux-hardware.org/?probe=b4d926a4bc) | Jul 08, 2023 |
| MSI           | GF65 Thin 10UE              | Notebook    | [8dd1516457](https://linux-hardware.org/?probe=8dd1516457) | Jul 08, 2023 |
| AZW           | SER                         | Mini pc     | [1a93a70c6b](https://linux-hardware.org/?probe=1a93a70c6b) | Jul 07, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [2ed128676f](https://linux-hardware.org/?probe=2ed128676f) | Jul 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [0b4200c1e4](https://linux-hardware.org/?probe=0b4200c1e4) | Jul 07, 2023 |
| Lenovo        | ThinkPad P52 20MAS17228     | Notebook    | [cb869cfeab](https://linux-hardware.org/?probe=cb869cfeab) | Jul 07, 2023 |
| Dell          | 0KRC95 A02                  | Desktop     | [5d0d505ca1](https://linux-hardware.org/?probe=5d0d505ca1) | Jul 07, 2023 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | Notebook    | [b50c5ad983](https://linux-hardware.org/?probe=b50c5ad983) | Jul 06, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [dfd88b9f78](https://linux-hardware.org/?probe=dfd88b9f78) | Jul 04, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [ca25e859c3](https://linux-hardware.org/?probe=ca25e859c3) | Jul 04, 2023 |
| MSI           | Z170A KRAIT GAMING          | Desktop     | [4bede9ff31](https://linux-hardware.org/?probe=4bede9ff31) | Jul 03, 2023 |
| MSI           | Raider GE77HX 12UHS         | Notebook    | [87cc790852](https://linux-hardware.org/?probe=87cc790852) | Jul 03, 2023 |
| ASRock        | Z87 Extreme6                | Desktop     | [d69ea1a2cb](https://linux-hardware.org/?probe=d69ea1a2cb) | Jul 02, 2023 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | Notebook    | [4586b855ca](https://linux-hardware.org/?probe=4586b855ca) | Jul 02, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [8ea4c888cf](https://linux-hardware.org/?probe=8ea4c888cf) | Jul 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [77e6b09eb9](https://linux-hardware.org/?probe=77e6b09eb9) | Jun 30, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [08708e8e9d](https://linux-hardware.org/?probe=08708e8e9d) | Jun 28, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [a974c1b82e](https://linux-hardware.org/?probe=a974c1b82e) | Jun 26, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [1c648f1f3e](https://linux-hardware.org/?probe=1c648f1f3e) | Jun 25, 2023 |
| Lenovo        | V14 G2 ALC 82KC             | Notebook    | [40cbc38a69](https://linux-hardware.org/?probe=40cbc38a69) | Jun 25, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [e44e80fc33](https://linux-hardware.org/?probe=e44e80fc33) | Jun 23, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [b07361bc89](https://linux-hardware.org/?probe=b07361bc89) | Jun 22, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [8f6d75c75e](https://linux-hardware.org/?probe=8f6d75c75e) | Jun 22, 2023 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [e4407d328d](https://linux-hardware.org/?probe=e4407d328d) | Jun 22, 2023 |
| Lenovo        | IdeaPad S540-14IWL 81ND     | Notebook    | [3be3d70197](https://linux-hardware.org/?probe=3be3d70197) | Jun 20, 2023 |
| Dell          | Inspiron 7415 2-in-1        | Convertible | [744e0e7188](https://linux-hardware.org/?probe=744e0e7188) | Jun 20, 2023 |
| Gigabyte      | MZBAYAB-00                  | Desktop     | [5864261490](https://linux-hardware.org/?probe=5864261490) | Jun 20, 2023 |
| Lenovo        | Legion 5 82B5               | Notebook    | [146ef72817](https://linux-hardware.org/?probe=146ef72817) | Jun 19, 2023 |
| HP            | 212B                        | Desktop     | [134ff203c4](https://linux-hardware.org/?probe=134ff203c4) | Jun 16, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X6... | Notebook    | [e3e61eef7a](https://linux-hardware.org/?probe=e3e61eef7a) | Jun 15, 2023 |
| HP            | 212B                        | Desktop     | [b107461bdd](https://linux-hardware.org/?probe=b107461bdd) | Jun 14, 2023 |
| ECS           | H61H2-M17                   | Desktop     | [63ded73edb](https://linux-hardware.org/?probe=63ded73edb) | Jun 14, 2023 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [57b3c23d43](https://linux-hardware.org/?probe=57b3c23d43) | Jun 14, 2023 |
| Dell          | 0KRC95 A02                  | Desktop     | [5f9a1aafe0](https://linux-hardware.org/?probe=5f9a1aafe0) | Jun 14, 2023 |
| ECS           | H61H2-M17                   | Desktop     | [fb57cc3ed4](https://linux-hardware.org/?probe=fb57cc3ed4) | Jun 13, 2023 |
| Gigabyte      | D525TUD                     | Desktop     | [be2c796ab2](https://linux-hardware.org/?probe=be2c796ab2) | Jun 13, 2023 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [b9c83e1b8a](https://linux-hardware.org/?probe=b9c83e1b8a) | Jun 12, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [cf9274f969](https://linux-hardware.org/?probe=cf9274f969) | Jun 11, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [1c5e1b092a](https://linux-hardware.org/?probe=1c5e1b092a) | Jun 11, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [212c44c43f](https://linux-hardware.org/?probe=212c44c43f) | Jun 10, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [f9677c0861](https://linux-hardware.org/?probe=f9677c0861) | Jun 09, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [e28668e147](https://linux-hardware.org/?probe=e28668e147) | Jun 08, 2023 |
| Lenovo        | ThinkPad T590 20N5S2NC0F    | Notebook    | [581602e921](https://linux-hardware.org/?probe=581602e921) | Jun 07, 2023 |
| Dell          | Latitude 5300               | Notebook    | [1eea10cfa3](https://linux-hardware.org/?probe=1eea10cfa3) | Jun 07, 2023 |
| Lenovo        | ThinkPad P51 20HH0011US     | Notebook    | [4766608bc1](https://linux-hardware.org/?probe=4766608bc1) | Jun 06, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [3c3708dcec](https://linux-hardware.org/?probe=3c3708dcec) | Jun 06, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [79b80daf83](https://linux-hardware.org/?probe=79b80daf83) | Jun 05, 2023 |
| ASUSTek       | X540UP                      | Notebook    | [b6613930a2](https://linux-hardware.org/?probe=b6613930a2) | Jun 05, 2023 |
| ASUSTek       | X540UP                      | Notebook    | [5102ecc266](https://linux-hardware.org/?probe=5102ecc266) | Jun 04, 2023 |
| Acer          | Aspire AV15-51              | Notebook    | [41e5c1790c](https://linux-hardware.org/?probe=41e5c1790c) | Jun 03, 2023 |
| Acer          | Aspire AV15-51              | Notebook    | [d583c74274](https://linux-hardware.org/?probe=d583c74274) | Jun 03, 2023 |
| Acer          | Aspire AV15-51              | Notebook    | [7ed9ba7165](https://linux-hardware.org/?probe=7ed9ba7165) | Jun 03, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [1aa286ccff](https://linux-hardware.org/?probe=1aa286ccff) | Jun 03, 2023 |
| HP            | 212B                        | Desktop     | [15c4a7b64f](https://linux-hardware.org/?probe=15c4a7b64f) | Jun 02, 2023 |
| Dell          | Latitude 7490               | Notebook    | [3cb9ad156f](https://linux-hardware.org/?probe=3cb9ad156f) | Jun 01, 2023 |
| Toshiba       | TECRA Z40t-C                | Notebook    | [f3dc10c852](https://linux-hardware.org/?probe=f3dc10c852) | Jun 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [df9086deb4](https://linux-hardware.org/?probe=df9086deb4) | Jun 01, 2023 |
| Toshiba       | TECRA Z40t-C                | Notebook    | [1d128e6153](https://linux-hardware.org/?probe=1d128e6153) | Jun 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [4a908da319](https://linux-hardware.org/?probe=4a908da319) | May 31, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [287ebf0b10](https://linux-hardware.org/?probe=287ebf0b10) | May 30, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [882f43330b](https://linux-hardware.org/?probe=882f43330b) | May 30, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [ffbccb8f47](https://linux-hardware.org/?probe=ffbccb8f47) | May 30, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [360e8fd5e5](https://linux-hardware.org/?probe=360e8fd5e5) | May 30, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [8b96413dfd](https://linux-hardware.org/?probe=8b96413dfd) | May 30, 2023 |
| HP            | 8169                        | Desktop     | [4f10a589e7](https://linux-hardware.org/?probe=4f10a589e7) | May 29, 2023 |
| MSI           | GF65 Thin 10UE              | Notebook    | [98e2096ab6](https://linux-hardware.org/?probe=98e2096ab6) | May 29, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [94e5a63c07](https://linux-hardware.org/?probe=94e5a63c07) | May 29, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [38936854c8](https://linux-hardware.org/?probe=38936854c8) | May 29, 2023 |
| HP            | ProLiant ML110 G7           | Desktop     | [fd74c84f0a](https://linux-hardware.org/?probe=fd74c84f0a) | May 28, 2023 |
| Dell          | XPS 9320                    | Notebook    | [33e7d964ad](https://linux-hardware.org/?probe=33e7d964ad) | May 28, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [3c001962b0](https://linux-hardware.org/?probe=3c001962b0) | May 28, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [dc2b5e538f](https://linux-hardware.org/?probe=dc2b5e538f) | May 27, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | Notebook    | [f068d88c01](https://linux-hardware.org/?probe=f068d88c01) | May 27, 2023 |
| AAEON         | AEC-6637                    | Notebook    | [19050f7ccd](https://linux-hardware.org/?probe=19050f7ccd) | May 26, 2023 |
| Intel Clie... | LAPBC510                    | Notebook    | [fe45f8ba3c](https://linux-hardware.org/?probe=fe45f8ba3c) | May 26, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | Notebook    | [29d761bff5](https://linux-hardware.org/?probe=29d761bff5) | May 26, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [5dd56ed986](https://linux-hardware.org/?probe=5dd56ed986) | May 25, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [063077bd52](https://linux-hardware.org/?probe=063077bd52) | May 25, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [2c31d88fa2](https://linux-hardware.org/?probe=2c31d88fa2) | May 25, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [efb5aa9bfc](https://linux-hardware.org/?probe=efb5aa9bfc) | May 24, 2023 |
| Dell          | Precision 7530              | Notebook    | [5cf37f39f4](https://linux-hardware.org/?probe=5cf37f39f4) | May 24, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [1280876877](https://linux-hardware.org/?probe=1280876877) | May 24, 2023 |
| HP            | ENVY 15                     | Notebook    | [85a97390d5](https://linux-hardware.org/?probe=85a97390d5) | May 23, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [ec7d8d12e1](https://linux-hardware.org/?probe=ec7d8d12e1) | May 23, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d5b2c1e7b5](https://linux-hardware.org/?probe=d5b2c1e7b5) | May 22, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [ecc77ee7a9](https://linux-hardware.org/?probe=ecc77ee7a9) | May 22, 2023 |
| HP            | ENVY 15                     | Notebook    | [21a38278ca](https://linux-hardware.org/?probe=21a38278ca) | May 21, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [7b5628af0e](https://linux-hardware.org/?probe=7b5628af0e) | May 21, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | Notebook    | [8ec7bb4682](https://linux-hardware.org/?probe=8ec7bb4682) | May 21, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [0f8329fecb](https://linux-hardware.org/?probe=0f8329fecb) | May 20, 2023 |
| Lenovo        | ThinkPad T480 20L5S1S000    | Notebook    | [30950ddd01](https://linux-hardware.org/?probe=30950ddd01) | May 19, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [b59b0160fb](https://linux-hardware.org/?probe=b59b0160fb) | May 19, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [d6e14242b8](https://linux-hardware.org/?probe=d6e14242b8) | May 19, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | Notebook    | [f811501691](https://linux-hardware.org/?probe=f811501691) | May 18, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [b8ed6a8b77](https://linux-hardware.org/?probe=b8ed6a8b77) | May 18, 2023 |
| Gigabyte      | 990FXA-UD3 R5               | Desktop     | [b3e10fd912](https://linux-hardware.org/?probe=b3e10fd912) | May 17, 2023 |
| HP            | ENVY 15                     | Notebook    | [4576cea8b0](https://linux-hardware.org/?probe=4576cea8b0) | May 17, 2023 |
| Gigabyte      | H170-Gaming 3               | Desktop     | [ae5f06df99](https://linux-hardware.org/?probe=ae5f06df99) | May 16, 2023 |
| MSI           | H170A PC MATE               | Desktop     | [389ab53539](https://linux-hardware.org/?probe=389ab53539) | May 15, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [d4344603b6](https://linux-hardware.org/?probe=d4344603b6) | May 15, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [bd390995e3](https://linux-hardware.org/?probe=bd390995e3) | May 14, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [903ece310a](https://linux-hardware.org/?probe=903ece310a) | May 14, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | Notebook    | [9dda4f6b83](https://linux-hardware.org/?probe=9dda4f6b83) | May 13, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [4243b6a57b](https://linux-hardware.org/?probe=4243b6a57b) | May 13, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [fdf45a81de](https://linux-hardware.org/?probe=fdf45a81de) | May 13, 2023 |
| HP            | ENVY 15                     | Notebook    | [e188fe21b7](https://linux-hardware.org/?probe=e188fe21b7) | May 12, 2023 |
| Dell          | 02YYK5 A00                  | Desktop     | [68213fddbd](https://linux-hardware.org/?probe=68213fddbd) | May 12, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | Desktop     | [35990f19da](https://linux-hardware.org/?probe=35990f19da) | May 12, 2023 |
| Lenovo        | YangTian V340-15-IML 81V... | Notebook    | [cedb6136dc](https://linux-hardware.org/?probe=cedb6136dc) | May 12, 2023 |
| ASUSTek       | X79-DELUXE                  | Desktop     | [ad6be5fe7c](https://linux-hardware.org/?probe=ad6be5fe7c) | May 12, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [e985d1beac](https://linux-hardware.org/?probe=e985d1beac) | May 12, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [1b0cd4f3e1](https://linux-hardware.org/?probe=1b0cd4f3e1) | May 11, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [3dc1af6df9](https://linux-hardware.org/?probe=3dc1af6df9) | May 11, 2023 |
| Dell          | Precision M3800             | Notebook    | [f5f8f44c9e](https://linux-hardware.org/?probe=f5f8f44c9e) | May 10, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [b791be35c2](https://linux-hardware.org/?probe=b791be35c2) | May 10, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [7058baf75d](https://linux-hardware.org/?probe=7058baf75d) | May 10, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [80a4bfeb08](https://linux-hardware.org/?probe=80a4bfeb08) | May 10, 2023 |
| ASUSTek       | PRIME B560M-K               | Desktop     | [ce0391bdee](https://linux-hardware.org/?probe=ce0391bdee) | May 09, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [e2bbbffe45](https://linux-hardware.org/?probe=e2bbbffe45) | May 09, 2023 |
| SK hynix      | HyBook Plus                 | Notebook    | [817a46f154](https://linux-hardware.org/?probe=817a46f154) | May 09, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [0a72d00670](https://linux-hardware.org/?probe=0a72d00670) | May 09, 2023 |
| Supermicro    | X11DPU                      | Server      | [d4b08b5129](https://linux-hardware.org/?probe=d4b08b5129) | May 08, 2023 |
| Notebook      | P750ZM                      | Notebook    | [2cbd56abdc](https://linux-hardware.org/?probe=2cbd56abdc) | May 08, 2023 |
| ASRock        | B560M-ITX/ac                | Desktop     | [80b16a8567](https://linux-hardware.org/?probe=80b16a8567) | May 08, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [d782846579](https://linux-hardware.org/?probe=d782846579) | May 08, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [53c03d6942](https://linux-hardware.org/?probe=53c03d6942) | May 08, 2023 |
| ASRock        | N68C-GS FX                  | Desktop     | [dcf5cd4ca2](https://linux-hardware.org/?probe=dcf5cd4ca2) | May 08, 2023 |
| Intel         | DP43TF AAE34878-403         | Desktop     | [9d5ca00c7c](https://linux-hardware.org/?probe=9d5ca00c7c) | May 07, 2023 |
| Intel         | DP43TF AAE34878-404         | Desktop     | [6bea90b569](https://linux-hardware.org/?probe=6bea90b569) | May 07, 2023 |
| Intel         | DP43TF AAE34878-403         | Desktop     | [6353d110f5](https://linux-hardware.org/?probe=6353d110f5) | May 07, 2023 |
| Intel         | DP43TF AAE34878-404         | Desktop     | [db0ab14831](https://linux-hardware.org/?probe=db0ab14831) | May 07, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [82afa36341](https://linux-hardware.org/?probe=82afa36341) | May 06, 2023 |
| Dell          | Inspiron 5490               | Notebook    | [6e2a4689b5](https://linux-hardware.org/?probe=6e2a4689b5) | May 06, 2023 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | Notebook    | [b8a363f717](https://linux-hardware.org/?probe=b8a363f717) | May 04, 2023 |
| Dell          | Precision 5540              | Notebook    | [3139d97ce0](https://linux-hardware.org/?probe=3139d97ce0) | May 04, 2023 |
| Toshiba       | PORTEGE Z830                | Notebook    | [a8cc4a63c2](https://linux-hardware.org/?probe=a8cc4a63c2) | May 03, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | Notebook    | [143b75f514](https://linux-hardware.org/?probe=143b75f514) | May 02, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [513f1e9efb](https://linux-hardware.org/?probe=513f1e9efb) | May 02, 2023 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [dc9cb3badc](https://linux-hardware.org/?probe=dc9cb3badc) | May 02, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [961ec7671c](https://linux-hardware.org/?probe=961ec7671c) | May 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [be8b69e1b4](https://linux-hardware.org/?probe=be8b69e1b4) | May 01, 2023 |
| Intel         | CHERRYVIEW D1 PLATFORM      | Notebook    | [6c58138c35](https://linux-hardware.org/?probe=6c58138c35) | May 01, 2023 |
| ASUSTek       | X555QG                      | Notebook    | [5263b174b2](https://linux-hardware.org/?probe=5263b174b2) | Apr 30, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [c33288abe2](https://linux-hardware.org/?probe=c33288abe2) | Apr 30, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [c262e81ab9](https://linux-hardware.org/?probe=c262e81ab9) | Apr 30, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [c6591b0852](https://linux-hardware.org/?probe=c6591b0852) | Apr 29, 2023 |
| Intel         | CHERRYVIEW D1 PLATFORM      | Notebook    | [edf1d60e46](https://linux-hardware.org/?probe=edf1d60e46) | Apr 29, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [80ea529a18](https://linux-hardware.org/?probe=80ea529a18) | Apr 29, 2023 |
| MSI           | Modern 14 B11MOU            | Notebook    | [6b3fcf3fcc](https://linux-hardware.org/?probe=6b3fcf3fcc) | Apr 29, 2023 |
| ASUSTek       | X555QG                      | Notebook    | [b33f41d3c3](https://linux-hardware.org/?probe=b33f41d3c3) | Apr 28, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [e0ef7894af](https://linux-hardware.org/?probe=e0ef7894af) | Apr 28, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [8a3c1cbc1c](https://linux-hardware.org/?probe=8a3c1cbc1c) | Apr 28, 2023 |
| Lenovo        | ThinkPad L13 Yoga 20R6S1... | Convertible | [c01483e50f](https://linux-hardware.org/?probe=c01483e50f) | Apr 28, 2023 |
| Lenovo        | ThinkPad X230 2325O32       | Notebook    | [b38ef1a717](https://linux-hardware.org/?probe=b38ef1a717) | Apr 27, 2023 |
| Lenovo        | ThinkPad T420 4177QKU       | Notebook    | [cbabefb1fa](https://linux-hardware.org/?probe=cbabefb1fa) | Apr 27, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [853016bfe3](https://linux-hardware.org/?probe=853016bfe3) | Apr 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | Notebook    | [3a6e27c6ce](https://linux-hardware.org/?probe=3a6e27c6ce) | Apr 26, 2023 |
| Gigabyte      | EX58-EXTREME                | Desktop     | [3b263c29fc](https://linux-hardware.org/?probe=3b263c29fc) | Apr 26, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [909ad37ab0](https://linux-hardware.org/?probe=909ad37ab0) | Apr 26, 2023 |
| MSI           | Creator 15 A10SGS           | Notebook    | [1b364e385a](https://linux-hardware.org/?probe=1b364e385a) | Apr 26, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [cc994920bf](https://linux-hardware.org/?probe=cc994920bf) | Apr 25, 2023 |
| HP            | 0AECh D                     | Desktop     | [c9e99b3f8c](https://linux-hardware.org/?probe=c9e99b3f8c) | Apr 25, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [c0d8e6e6b5](https://linux-hardware.org/?probe=c0d8e6e6b5) | Apr 25, 2023 |
| Lenovo        | 1037 SDK0Q40104 WIN 3305... | Server      | [1d6082efe8](https://linux-hardware.org/?probe=1d6082efe8) | Apr 25, 2023 |
| Lenovo        | 1037 SDK0Q40104 WIN 3305... | Server      | [d86639089a](https://linux-hardware.org/?probe=d86639089a) | Apr 25, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [373372bf75](https://linux-hardware.org/?probe=373372bf75) | Apr 25, 2023 |
| Lenovo        | V130-15IKB 81HN             | Notebook    | [1b26b3f89b](https://linux-hardware.org/?probe=1b26b3f89b) | Apr 24, 2023 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [2f3390afca](https://linux-hardware.org/?probe=2f3390afca) | Apr 24, 2023 |
| Gigabyte      | X570S I AORUS PRO AX        | Desktop     | [9c37fa5192](https://linux-hardware.org/?probe=9c37fa5192) | Apr 24, 2023 |
| Gigabyte      | F2A88X-UP4                  | Desktop     | [06859fe586](https://linux-hardware.org/?probe=06859fe586) | Apr 23, 2023 |
| Notebook      | NLxxPUx                     | Notebook    | [3648be5b0f](https://linux-hardware.org/?probe=3648be5b0f) | Apr 23, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | Notebook    | [a8644a5b03](https://linux-hardware.org/?probe=a8644a5b03) | Apr 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [0e798db6a8](https://linux-hardware.org/?probe=0e798db6a8) | Apr 23, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [f51db9e4de](https://linux-hardware.org/?probe=f51db9e4de) | Apr 23, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [3c0a66f0fc](https://linux-hardware.org/?probe=3c0a66f0fc) | Apr 22, 2023 |
| MSI           | Z370M MORTAR                | Desktop     | [9ed0395d2c](https://linux-hardware.org/?probe=9ed0395d2c) | Apr 22, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [80312ab34c](https://linux-hardware.org/?probe=80312ab34c) | Apr 22, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [b7f138b04c](https://linux-hardware.org/?probe=b7f138b04c) | Apr 20, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [81334f294e](https://linux-hardware.org/?probe=81334f294e) | Apr 20, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [cebfbef6d8](https://linux-hardware.org/?probe=cebfbef6d8) | Apr 20, 2023 |
| Dell          | G15 5510                    | Notebook    | [724945ee92](https://linux-hardware.org/?probe=724945ee92) | Apr 20, 2023 |
| Gigabyte      | Z270XP-SLI-CF               | Desktop     | [1383ab9981](https://linux-hardware.org/?probe=1383ab9981) | Apr 20, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHS... | Notebook    | [59d7ef5ddd](https://linux-hardware.org/?probe=59d7ef5ddd) | Apr 20, 2023 |
| Toshiba       | Satellite L515              | Notebook    | [5262a186b5](https://linux-hardware.org/?probe=5262a186b5) | Apr 20, 2023 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [990cf467d8](https://linux-hardware.org/?probe=990cf467d8) | Apr 19, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [4fbb42afa0](https://linux-hardware.org/?probe=4fbb42afa0) | Apr 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [85700f4804](https://linux-hardware.org/?probe=85700f4804) | Apr 19, 2023 |
| Dell          | Precision 5540              | Notebook    | [66b58fad6c](https://linux-hardware.org/?probe=66b58fad6c) | Apr 19, 2023 |
| Dell          | Precision 5540              | Notebook    | [e114fb911c](https://linux-hardware.org/?probe=e114fb911c) | Apr 19, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [2a80be40e3](https://linux-hardware.org/?probe=2a80be40e3) | Apr 19, 2023 |
| HP            | Pavilion 17                 | Notebook    | [66df49c906](https://linux-hardware.org/?probe=66df49c906) | Apr 19, 2023 |
| Intel         | X79M-S                      | Desktop     | [0c51f5a0e0](https://linux-hardware.org/?probe=0c51f5a0e0) | Apr 19, 2023 |
| Alienware     | 0K9TKY A00                  | Desktop     | [22582f8d3e](https://linux-hardware.org/?probe=22582f8d3e) | Apr 19, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [1a5add814c](https://linux-hardware.org/?probe=1a5add814c) | Apr 18, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [67a6474ece](https://linux-hardware.org/?probe=67a6474ece) | Apr 18, 2023 |
| Fujitsu       | LIFEBOOK U7510              | Notebook    | [21605e555f](https://linux-hardware.org/?probe=21605e555f) | Apr 18, 2023 |
| MSI           | Z170A GAMING PRO CARBON     | Desktop     | [cf13c3781c](https://linux-hardware.org/?probe=cf13c3781c) | Apr 18, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [7fcc7d1b34](https://linux-hardware.org/?probe=7fcc7d1b34) | Apr 18, 2023 |
| ASRock        | Z170 Gaming K4              | Desktop     | [cbd09f0f67](https://linux-hardware.org/?probe=cbd09f0f67) | Apr 18, 2023 |
| Lenovo        | ThinkPad Edge 031946U       | Notebook    | [f9d813509a](https://linux-hardware.org/?probe=f9d813509a) | Apr 18, 2023 |
| Dell          | 0XHYJF A00                  | All in one  | [9348834e54](https://linux-hardware.org/?probe=9348834e54) | Apr 18, 2023 |
| Dell          | 0XHYJF A00                  | All in one  | [c8804b1836](https://linux-hardware.org/?probe=c8804b1836) | Apr 18, 2023 |
| Lenovo        | ThinkPad P52 20MAS11D00     | Notebook    | [c2227e5f29](https://linux-hardware.org/?probe=c2227e5f29) | Apr 18, 2023 |
| Lenovo        | Unknown                     | Notebook    | [99a0c76ea9](https://linux-hardware.org/?probe=99a0c76ea9) | Apr 18, 2023 |
| Lenovo        | ThinkPad P52 20MAS11D00     | Notebook    | [f56edbb1d1](https://linux-hardware.org/?probe=f56edbb1d1) | Apr 18, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [7b3a68ca48](https://linux-hardware.org/?probe=7b3a68ca48) | Apr 18, 2023 |
| Intel         | DZ68DB AAG27985-105         | Desktop     | [aa030a4054](https://linux-hardware.org/?probe=aa030a4054) | Apr 18, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [90c4ba9f6e](https://linux-hardware.org/?probe=90c4ba9f6e) | Apr 17, 2023 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [bbe3e437d6](https://linux-hardware.org/?probe=bbe3e437d6) | Apr 17, 2023 |
| Lenovo        | Unknown                     | Notebook    | [653cf225b8](https://linux-hardware.org/?probe=653cf225b8) | Apr 17, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [4b953003cc](https://linux-hardware.org/?probe=4b953003cc) | Apr 17, 2023 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [07a49303af](https://linux-hardware.org/?probe=07a49303af) | Apr 17, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [f8a45caf43](https://linux-hardware.org/?probe=f8a45caf43) | Apr 17, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [7ca92cfada](https://linux-hardware.org/?probe=7ca92cfada) | Apr 17, 2023 |
| HP            | Pavilion 17                 | Notebook    | [a09113d5ab](https://linux-hardware.org/?probe=a09113d5ab) | Apr 17, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [a6a81342e7](https://linux-hardware.org/?probe=a6a81342e7) | Apr 17, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [3d14cefd78](https://linux-hardware.org/?probe=3d14cefd78) | Apr 17, 2023 |
| MSI           | H310M PRO-VD PLUS           | Desktop     | [bff38bc725](https://linux-hardware.org/?probe=bff38bc725) | Apr 16, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [fd256ca124](https://linux-hardware.org/?probe=fd256ca124) | Apr 16, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [2092251807](https://linux-hardware.org/?probe=2092251807) | Apr 16, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [c8513ddcf3](https://linux-hardware.org/?probe=c8513ddcf3) | Apr 16, 2023 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [1fa07cd218](https://linux-hardware.org/?probe=1fa07cd218) | Apr 16, 2023 |
| HP            | 15-dc1018ur                 | Notebook    | [7df35a90ad](https://linux-hardware.org/?probe=7df35a90ad) | Apr 16, 2023 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [c228cbe8e1](https://linux-hardware.org/?probe=c228cbe8e1) | Apr 16, 2023 |
| Framework     | Laptop                      | Notebook    | [c03bcdf19a](https://linux-hardware.org/?probe=c03bcdf19a) | Apr 16, 2023 |
| Gigabyte      | B85-HD3                     | Desktop     | [25e7d545ae](https://linux-hardware.org/?probe=25e7d545ae) | Apr 16, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [afc478cf27](https://linux-hardware.org/?probe=afc478cf27) | Apr 16, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [19b858e5f8](https://linux-hardware.org/?probe=19b858e5f8) | Apr 16, 2023 |
| ASRock        | A520M-HVS                   | Desktop     | [a0d799e140](https://linux-hardware.org/?probe=a0d799e140) | Apr 16, 2023 |
| Sony          | VPCCA1S1E                   | Notebook    | [05ab5df066](https://linux-hardware.org/?probe=05ab5df066) | Apr 16, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [73c46e2901](https://linux-hardware.org/?probe=73c46e2901) | Apr 15, 2023 |
| Google        | Dragonair                   | Notebook    | [be10ee5035](https://linux-hardware.org/?probe=be10ee5035) | Apr 15, 2023 |
| Sony          | VPCCA1S1E                   | Notebook    | [30625007d9](https://linux-hardware.org/?probe=30625007d9) | Apr 15, 2023 |
| Google        | Dragonair                   | Notebook    | [cb2aa57d07](https://linux-hardware.org/?probe=cb2aa57d07) | Apr 15, 2023 |
| HP            | 212B                        | Desktop     | [c8f86eb8a4](https://linux-hardware.org/?probe=c8f86eb8a4) | Apr 15, 2023 |
| Acer          | Aspire A114-33              | Notebook    | [53c9fe0b8d](https://linux-hardware.org/?probe=53c9fe0b8d) | Apr 15, 2023 |
| Acer          | Aspire A114-33              | Notebook    | [99f95937d4](https://linux-hardware.org/?probe=99f95937d4) | Apr 15, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [c649f1b898](https://linux-hardware.org/?probe=c649f1b898) | Apr 15, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [37eee19e22](https://linux-hardware.org/?probe=37eee19e22) | Apr 15, 2023 |
| Lenovo        | ThinkCentre M58p 7220A72    | Desktop     | [2be395131f](https://linux-hardware.org/?probe=2be395131f) | Apr 15, 2023 |
| HONOR         | HYM-WXX                     | Notebook    | [109b28f217](https://linux-hardware.org/?probe=109b28f217) | Apr 15, 2023 |
| Lenovo        | ThinkCentre M58p 7220A72    | Desktop     | [0ca4b7045e](https://linux-hardware.org/?probe=0ca4b7045e) | Apr 15, 2023 |
| ASUSTek       | TUF Gaming X570-PRO WIFI... | Desktop     | [2e601ecae8](https://linux-hardware.org/?probe=2e601ecae8) | Apr 15, 2023 |
| Panasonic     | CF-C2CCEZXCM                | Notebook    | [361573ef78](https://linux-hardware.org/?probe=361573ef78) | Apr 14, 2023 |
| Dell          | Inspiron 7460               | Notebook    | [ae861b54cd](https://linux-hardware.org/?probe=ae861b54cd) | Apr 14, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [b60b4dbb07](https://linux-hardware.org/?probe=b60b4dbb07) | Apr 14, 2023 |
| Dell          | Precision 5560              | Notebook    | [b6d20ef4bf](https://linux-hardware.org/?probe=b6d20ef4bf) | Apr 14, 2023 |
| Dell          | Precision 5560              | Notebook    | [b76f840bd9](https://linux-hardware.org/?probe=b76f840bd9) | Apr 14, 2023 |
| MSI           | H310M PRO-VD PLUS           | Desktop     | [9f6209111c](https://linux-hardware.org/?probe=9f6209111c) | Apr 14, 2023 |
| Toshiba       | PORTEGE X20W-E              | Convertible | [40894d0141](https://linux-hardware.org/?probe=40894d0141) | Apr 14, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [ec08193576](https://linux-hardware.org/?probe=ec08193576) | Apr 14, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d4f384271e](https://linux-hardware.org/?probe=d4f384271e) | Apr 14, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [c7ca0e9fd1](https://linux-hardware.org/?probe=c7ca0e9fd1) | Apr 14, 2023 |
| Toshiba       | PORTEGE X20W-E              | Convertible | [d2c04327fb](https://linux-hardware.org/?probe=d2c04327fb) | Apr 14, 2023 |
| HP            | ZBook 15                    | Notebook    | [c5397a7fbb](https://linux-hardware.org/?probe=c5397a7fbb) | Apr 14, 2023 |
| Gigabyte      | B560M H                     | Desktop     | [c59729f9d2](https://linux-hardware.org/?probe=c59729f9d2) | Apr 14, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [f02a5fef82](https://linux-hardware.org/?probe=f02a5fef82) | Apr 14, 2023 |
| Lenovo        | Legion 5 15IAH7 82RC        | Notebook    | [9cb53e6d6f](https://linux-hardware.org/?probe=9cb53e6d6f) | Apr 13, 2023 |
| HP            | ZBook 15                    | Notebook    | [aaaa838a8f](https://linux-hardware.org/?probe=aaaa838a8f) | Apr 13, 2023 |
| 3Logic Gro... | Graviton N15i-K2            | Notebook    | [7b75b7b08e](https://linux-hardware.org/?probe=7b75b7b08e) | Apr 13, 2023 |
| Dell          | Inspiron 5515               | Notebook    | [e7306b2521](https://linux-hardware.org/?probe=e7306b2521) | Apr 13, 2023 |
| Lenovo        | ThinkPad T490 20N2000NRT    | Notebook    | [ea97cd752d](https://linux-hardware.org/?probe=ea97cd752d) | Apr 13, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [2d321f3134](https://linux-hardware.org/?probe=2d321f3134) | Apr 13, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [1d6ace19a5](https://linux-hardware.org/?probe=1d6ace19a5) | Apr 13, 2023 |
| Dell          | Inspiron 5482               | Convertible | [2d1dbac3cf](https://linux-hardware.org/?probe=2d1dbac3cf) | Apr 13, 2023 |
| Lenovo        | Yoga 6 13ABR8 83B2          | Convertible | [817e4bb939](https://linux-hardware.org/?probe=817e4bb939) | Apr 13, 2023 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [29d92f085a](https://linux-hardware.org/?probe=29d92f085a) | Apr 12, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [77384847ef](https://linux-hardware.org/?probe=77384847ef) | Apr 12, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [ada19dbe5c](https://linux-hardware.org/?probe=ada19dbe5c) | Apr 12, 2023 |
| MSI           | MS-7388                     | Desktop     | [d7f892b3e2](https://linux-hardware.org/?probe=d7f892b3e2) | Apr 12, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [6182cca953](https://linux-hardware.org/?probe=6182cca953) | Apr 12, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [66924704d2](https://linux-hardware.org/?probe=66924704d2) | Apr 12, 2023 |
| Intel         | NUC8BEB J72692-304          | Mini pc     | [19c864f074](https://linux-hardware.org/?probe=19c864f074) | Apr 12, 2023 |
| Lenovo        | IdeaPad Slim 9 14ITL5 82... | Notebook    | [16a7a866f1](https://linux-hardware.org/?probe=16a7a866f1) | Apr 12, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [10da0191c4](https://linux-hardware.org/?probe=10da0191c4) | Apr 11, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [c279e7b8fe](https://linux-hardware.org/?probe=c279e7b8fe) | Apr 11, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [5662df110d](https://linux-hardware.org/?probe=5662df110d) | Apr 11, 2023 |
| Dell          | 0J3C2F A00                  | Desktop     | [12f634cf42](https://linux-hardware.org/?probe=12f634cf42) | Apr 11, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [da86532b55](https://linux-hardware.org/?probe=da86532b55) | Apr 11, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [e8645a51dc](https://linux-hardware.org/?probe=e8645a51dc) | Apr 11, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [3792cccd19](https://linux-hardware.org/?probe=3792cccd19) | Apr 11, 2023 |
| Notebook      | NH55RGQ                     | Notebook    | [7fc1310fc2](https://linux-hardware.org/?probe=7fc1310fc2) | Apr 11, 2023 |
| HP            | 225E                        | Desktop     | [46f665e085](https://linux-hardware.org/?probe=46f665e085) | Apr 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [3c1e7c6f4a](https://linux-hardware.org/?probe=3c1e7c6f4a) | Apr 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [9d3c5ea28d](https://linux-hardware.org/?probe=9d3c5ea28d) | Apr 11, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [ac983c99b9](https://linux-hardware.org/?probe=ac983c99b9) | Apr 10, 2023 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [6e4aea5587](https://linux-hardware.org/?probe=6e4aea5587) | Apr 10, 2023 |
| Lenovo        | ThinkPad L13 Yoga 20R6S1... | Convertible | [8ca7e7c5ad](https://linux-hardware.org/?probe=8ca7e7c5ad) | Apr 10, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [6fe9dfd9a6](https://linux-hardware.org/?probe=6fe9dfd9a6) | Apr 10, 2023 |
| ECS           | H61H2-M12                   | Desktop     | [f3e8f5eb22](https://linux-hardware.org/?probe=f3e8f5eb22) | Apr 10, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [11ecb91fec](https://linux-hardware.org/?probe=11ecb91fec) | Apr 09, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [621eb9522f](https://linux-hardware.org/?probe=621eb9522f) | Apr 09, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [87f9a72b18](https://linux-hardware.org/?probe=87f9a72b18) | Apr 09, 2023 |
| ASUSTek       | P552LA                      | Notebook    | [803ac095e7](https://linux-hardware.org/?probe=803ac095e7) | Apr 08, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [a334fb8e82](https://linux-hardware.org/?probe=a334fb8e82) | Apr 08, 2023 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [c06058447c](https://linux-hardware.org/?probe=c06058447c) | Apr 08, 2023 |
| Samsung       | Galaxy Book 12 LTE          | Tablet      | [d866c03132](https://linux-hardware.org/?probe=d866c03132) | Apr 08, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [f65d106f65](https://linux-hardware.org/?probe=f65d106f65) | Apr 08, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [5605228f3b](https://linux-hardware.org/?probe=5605228f3b) | Apr 08, 2023 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [e34683f5f0](https://linux-hardware.org/?probe=e34683f5f0) | Apr 07, 2023 |
| ASUSTek       | X553MA                      | Notebook    | [0a307c8c2b](https://linux-hardware.org/?probe=0a307c8c2b) | Apr 07, 2023 |
| HP            | Pavilion dv7                | Notebook    | [3a159264b1](https://linux-hardware.org/?probe=3a159264b1) | Apr 07, 2023 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [8c1127cfab](https://linux-hardware.org/?probe=8c1127cfab) | Apr 07, 2023 |
| Dell          | Latitude 7490               | Notebook    | [01957ea955](https://linux-hardware.org/?probe=01957ea955) | Apr 07, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [8d68ef79c3](https://linux-hardware.org/?probe=8d68ef79c3) | Apr 06, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [e9281d0364](https://linux-hardware.org/?probe=e9281d0364) | Apr 06, 2023 |
| Clevo         | M815P                       | Notebook    | [e5194b9fea](https://linux-hardware.org/?probe=e5194b9fea) | Apr 06, 2023 |
| Dell          | XPS 9320                    | Notebook    | [ff14e0074a](https://linux-hardware.org/?probe=ff14e0074a) | Apr 06, 2023 |
| MSI           | Katana 17 B12VGK            | Notebook    | [0f8f9e8ba8](https://linux-hardware.org/?probe=0f8f9e8ba8) | Apr 06, 2023 |
| Samsung       | 760XDA                      | Notebook    | [625178fa5a](https://linux-hardware.org/?probe=625178fa5a) | Apr 06, 2023 |
| NEC Comput... | PC-VK27MCZCK                | Notebook    | [e9572ebd2e](https://linux-hardware.org/?probe=e9572ebd2e) | Apr 06, 2023 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [320195c782](https://linux-hardware.org/?probe=320195c782) | Apr 06, 2023 |
| MSI           | Delta 15 A5EFK              | Notebook    | [d3066bb3d4](https://linux-hardware.org/?probe=d3066bb3d4) | Apr 06, 2023 |
| ASUSTek       | GL552VW                     | Notebook    | [ab450c0ddd](https://linux-hardware.org/?probe=ab450c0ddd) | Apr 06, 2023 |
| HP            | OMEN by Laptop 16-b1xxx     | Notebook    | [d741226152](https://linux-hardware.org/?probe=d741226152) | Apr 06, 2023 |
| Dell          | Latitude E7470              | Notebook    | [64721a0d8a](https://linux-hardware.org/?probe=64721a0d8a) | Apr 05, 2023 |
| ASUSTek       | T100TAF                     | Notebook    | [fed8f42482](https://linux-hardware.org/?probe=fed8f42482) | Apr 05, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [a64c365f62](https://linux-hardware.org/?probe=a64c365f62) | Apr 05, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [86291f499e](https://linux-hardware.org/?probe=86291f499e) | Apr 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [f98b9efce7](https://linux-hardware.org/?probe=f98b9efce7) | Apr 05, 2023 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [7e5be74f0b](https://linux-hardware.org/?probe=7e5be74f0b) | Apr 05, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [b469666726](https://linux-hardware.org/?probe=b469666726) | Apr 05, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [3a70dc24db](https://linux-hardware.org/?probe=3a70dc24db) | Apr 05, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [4710939159](https://linux-hardware.org/?probe=4710939159) | Apr 05, 2023 |
| HP            | 1495                        | Desktop     | [c0665ecb23](https://linux-hardware.org/?probe=c0665ecb23) | Apr 04, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [4c46d2ae80](https://linux-hardware.org/?probe=4c46d2ae80) | Apr 04, 2023 |
| ASUSTek       | X550JK                      | Notebook    | [b75b9b9fa2](https://linux-hardware.org/?probe=b75b9b9fa2) | Apr 04, 2023 |
| HP            | Notebook                    | Notebook    | [935131a649](https://linux-hardware.org/?probe=935131a649) | Apr 04, 2023 |
| HP            | Notebook                    | Notebook    | [f35bee3b90](https://linux-hardware.org/?probe=f35bee3b90) | Apr 04, 2023 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [316e31eae5](https://linux-hardware.org/?probe=316e31eae5) | Apr 04, 2023 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [088a09317e](https://linux-hardware.org/?probe=088a09317e) | Apr 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [c2240b20c2](https://linux-hardware.org/?probe=c2240b20c2) | Apr 04, 2023 |
| Notebook      | L140PU                      | Notebook    | [628319771e](https://linux-hardware.org/?probe=628319771e) | Apr 04, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [f801258fa5](https://linux-hardware.org/?probe=f801258fa5) | Apr 04, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [ddbd47af34](https://linux-hardware.org/?probe=ddbd47af34) | Apr 04, 2023 |
| Itautec       | ST 4265 ST-4265 Padrao 0... | Desktop     | [26e8d46d94](https://linux-hardware.org/?probe=26e8d46d94) | Apr 03, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [84c709f5f9](https://linux-hardware.org/?probe=84c709f5f9) | Apr 03, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [95a98c59b1](https://linux-hardware.org/?probe=95a98c59b1) | Apr 03, 2023 |
| Fanless Mi... | Rev GMLR1                   | Mini pc     | [58eae7ff4e](https://linux-hardware.org/?probe=58eae7ff4e) | Apr 03, 2023 |
| Fujitsu       | LIFEBOOK U747               | Notebook    | [868448ea4b](https://linux-hardware.org/?probe=868448ea4b) | Apr 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [e6a732e9b0](https://linux-hardware.org/?probe=e6a732e9b0) | Apr 03, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [0b97a5a77a](https://linux-hardware.org/?probe=0b97a5a77a) | Apr 03, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [e65532d978](https://linux-hardware.org/?probe=e65532d978) | Apr 03, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [ada2cb6e08](https://linux-hardware.org/?probe=ada2cb6e08) | Apr 02, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [a761c8f978](https://linux-hardware.org/?probe=a761c8f978) | Apr 02, 2023 |
| Toshiba       | Satellite C55-B             | Notebook    | [da341e3be8](https://linux-hardware.org/?probe=da341e3be8) | Apr 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [f995b3a81f](https://linux-hardware.org/?probe=f995b3a81f) | Apr 02, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [65cee818b6](https://linux-hardware.org/?probe=65cee818b6) | Apr 02, 2023 |
| Samsung       | 550P5C/550P7C               | Notebook    | [8e6191f4bb](https://linux-hardware.org/?probe=8e6191f4bb) | Apr 02, 2023 |
| Medion        | MS-7728                     | Desktop     | [83f7f01bde](https://linux-hardware.org/?probe=83f7f01bde) | Apr 02, 2023 |
| ilife         | S806                        | Notebook    | [d089301e66](https://linux-hardware.org/?probe=d089301e66) | Apr 02, 2023 |
| Lenovo        | ThinkPad E14 20RAS0D800     | Notebook    | [ea2f5b484f](https://linux-hardware.org/?probe=ea2f5b484f) | Apr 02, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [60e80d51ab](https://linux-hardware.org/?probe=60e80d51ab) | Apr 02, 2023 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [71f34e6ebc](https://linux-hardware.org/?probe=71f34e6ebc) | Apr 02, 2023 |
| Gigabyte      | X570S AERO G                | Desktop     | [30e0bd8317](https://linux-hardware.org/?probe=30e0bd8317) | Apr 02, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [f3b1797500](https://linux-hardware.org/?probe=f3b1797500) | Apr 02, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [94df0605ae](https://linux-hardware.org/?probe=94df0605ae) | Apr 02, 2023 |
| Lenovo        | ThinkPad A485 20MUCTO1WW    | Notebook    | [f64cf6a2ae](https://linux-hardware.org/?probe=f64cf6a2ae) | Apr 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [9148a1d487](https://linux-hardware.org/?probe=9148a1d487) | Apr 02, 2023 |
| HP            | Snappy                      | Notebook    | [993161a4c7](https://linux-hardware.org/?probe=993161a4c7) | Apr 02, 2023 |
| Chuwi         | LarkBox Pro                 | Mini pc     | [237eb0712d](https://linux-hardware.org/?probe=237eb0712d) | Apr 02, 2023 |
| ASRock        | J3160DC-ITX                 | Desktop     | [7735423853](https://linux-hardware.org/?probe=7735423853) | Apr 02, 2023 |
| BYTENUC       | AZ51                        | Mini pc     | [d75fba5311](https://linux-hardware.org/?probe=d75fba5311) | Apr 02, 2023 |
| ilife         | S806                        | Notebook    | [3a3ccd7c55](https://linux-hardware.org/?probe=3a3ccd7c55) | Apr 02, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [dabe76e4ca](https://linux-hardware.org/?probe=dabe76e4ca) | Apr 01, 2023 |
| Lenovo        | 30FD NOK                    | Mini pc     | [f355bab53f](https://linux-hardware.org/?probe=f355bab53f) | Apr 01, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [f278e6aad0](https://linux-hardware.org/?probe=f278e6aad0) | Apr 01, 2023 |
| HP            | ProBook 6475b               | Notebook    | [680348d948](https://linux-hardware.org/?probe=680348d948) | Apr 01, 2023 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [30d25bdb17](https://linux-hardware.org/?probe=30d25bdb17) | Apr 01, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [b4a624599e](https://linux-hardware.org/?probe=b4a624599e) | Apr 01, 2023 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [f0d73d9284](https://linux-hardware.org/?probe=f0d73d9284) | Apr 01, 2023 |
| ASUSTek       | T100TA                      | Notebook    | [5be9a0230e](https://linux-hardware.org/?probe=5be9a0230e) | Apr 01, 2023 |
| MSI           | MAG B660M MORTAR WIFI DD... | Desktop     | [c512f4cdd9](https://linux-hardware.org/?probe=c512f4cdd9) | Apr 01, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [79d44a9e66](https://linux-hardware.org/?probe=79d44a9e66) | Apr 01, 2023 |
| MSI           | MAG B660M MORTAR WIFI DD... | Desktop     | [e615755655](https://linux-hardware.org/?probe=e615755655) | Apr 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [4a9aebc7f0](https://linux-hardware.org/?probe=4a9aebc7f0) | Apr 01, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [acfff71638](https://linux-hardware.org/?probe=acfff71638) | Mar 31, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [36fab57ba7](https://linux-hardware.org/?probe=36fab57ba7) | Mar 31, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [5800e3859c](https://linux-hardware.org/?probe=5800e3859c) | Mar 31, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | Notebook    | [c76f4f4354](https://linux-hardware.org/?probe=c76f4f4354) | Mar 31, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | Notebook    | [3a74487ae8](https://linux-hardware.org/?probe=3a74487ae8) | Mar 31, 2023 |
| Toshiba       | Satellite U940              | Notebook    | [277dba9c1f](https://linux-hardware.org/?probe=277dba9c1f) | Mar 31, 2023 |
| Gigabyte      | Z270P-D3-CF                 | Desktop     | [8ce3dc1981](https://linux-hardware.org/?probe=8ce3dc1981) | Mar 31, 2023 |
| Toshiba       | Satellite U940              | Notebook    | [8a5046cad7](https://linux-hardware.org/?probe=8a5046cad7) | Mar 31, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS1... | Convertible | [bb2f5a2276](https://linux-hardware.org/?probe=bb2f5a2276) | Mar 31, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [4693b65922](https://linux-hardware.org/?probe=4693b65922) | Mar 31, 2023 |
| MSI           | GS66 Stealth 10SF           | Notebook    | [a2589dd6f5](https://linux-hardware.org/?probe=a2589dd6f5) | Mar 31, 2023 |
| Google        | Cave                        | Notebook    | [8bd24407be](https://linux-hardware.org/?probe=8bd24407be) | Mar 31, 2023 |
| ASUSTek       | TUF B365M-PLUS GAMING       | Desktop     | [8d4ef602e5](https://linux-hardware.org/?probe=8d4ef602e5) | Mar 31, 2023 |
| Dell          | 0PP150 A00                  | Desktop     | [fdc879a486](https://linux-hardware.org/?probe=fdc879a486) | Mar 31, 2023 |
| Dell          | Latitude D620               | Notebook    | [801ede47a2](https://linux-hardware.org/?probe=801ede47a2) | Mar 31, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [fcb2279eb0](https://linux-hardware.org/?probe=fcb2279eb0) | Mar 31, 2023 |
| Acer          | Swift SFA16-41              | Notebook    | [e110fbb7d6](https://linux-hardware.org/?probe=e110fbb7d6) | Mar 31, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [1417777bbc](https://linux-hardware.org/?probe=1417777bbc) | Mar 30, 2023 |
| Gigabyte      | Z170XP-SLI-CF               | Desktop     | [70efcb81e9](https://linux-hardware.org/?probe=70efcb81e9) | Mar 30, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [2ac52b4538](https://linux-hardware.org/?probe=2ac52b4538) | Mar 30, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [5b087b11f5](https://linux-hardware.org/?probe=5b087b11f5) | Mar 30, 2023 |
| Dell          | Precision 5510              | Notebook    | [4bbf7f5ef2](https://linux-hardware.org/?probe=4bbf7f5ef2) | Mar 30, 2023 |
| AIR           | CX30500                     | Notebook    | [2ea4d0ec83](https://linux-hardware.org/?probe=2ea4d0ec83) | Mar 30, 2023 |
| Lenovo        | ThinkPad T470s 20HGS23V0... | Notebook    | [6af08c4bfe](https://linux-hardware.org/?probe=6af08c4bfe) | Mar 30, 2023 |
| Lenovo        | ThinkPad T470s 20HGS23V0... | Notebook    | [6f0d3fd82b](https://linux-hardware.org/?probe=6f0d3fd82b) | Mar 30, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [ab31f6f63d](https://linux-hardware.org/?probe=ab31f6f63d) | Mar 30, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [5cf96e41e0](https://linux-hardware.org/?probe=5cf96e41e0) | Mar 30, 2023 |
| Dell          | G15 5515                    | Notebook    | [7bb6311632](https://linux-hardware.org/?probe=7bb6311632) | Mar 30, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [881f70cb12](https://linux-hardware.org/?probe=881f70cb12) | Mar 30, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [bc798d371a](https://linux-hardware.org/?probe=bc798d371a) | Mar 30, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [159d154fca](https://linux-hardware.org/?probe=159d154fca) | Mar 30, 2023 |
| System76      | Thelio Mira thelio-mira-... | Desktop     | [4915a172bd](https://linux-hardware.org/?probe=4915a172bd) | Mar 29, 2023 |
| Dell          | Latitude 5580               | Notebook    | [84157deda8](https://linux-hardware.org/?probe=84157deda8) | Mar 29, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [2eb96be1ee](https://linux-hardware.org/?probe=2eb96be1ee) | Mar 29, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [6023df2b8b](https://linux-hardware.org/?probe=6023df2b8b) | Mar 29, 2023 |
| Dell          | Latitude 5420               | Notebook    | [aee5c648e7](https://linux-hardware.org/?probe=aee5c648e7) | Mar 29, 2023 |
| Dell          | Latitude 7430               | Notebook    | [3f3b04c185](https://linux-hardware.org/?probe=3f3b04c185) | Mar 29, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [2f6655b77c](https://linux-hardware.org/?probe=2f6655b77c) | Mar 29, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [bf2f7820cd](https://linux-hardware.org/?probe=bf2f7820cd) | Mar 29, 2023 |
| Notebook      | L140CU                      | Notebook    | [e24f4b285d](https://linux-hardware.org/?probe=e24f4b285d) | Mar 29, 2023 |
| Gigabyte      | Z270P-D3-CF                 | Desktop     | [a091222ad4](https://linux-hardware.org/?probe=a091222ad4) | Mar 29, 2023 |
| Notebook      | L140CU                      | Notebook    | [b1b0a5fc03](https://linux-hardware.org/?probe=b1b0a5fc03) | Mar 29, 2023 |
| Acer          | Veriton N4630G              | Desktop     | [fab3140b7b](https://linux-hardware.org/?probe=fab3140b7b) | Mar 29, 2023 |
| ASUSTek       | Zenbook UX5401ZA_UX5401Z... | Notebook    | [c8f2b78c09](https://linux-hardware.org/?probe=c8f2b78c09) | Mar 29, 2023 |
| Clevo         | M815P                       | Notebook    | [ac4eae2a0b](https://linux-hardware.org/?probe=ac4eae2a0b) | Mar 29, 2023 |
| Gigabyte      | P55-UD6-C                   | Desktop     | [7c56c30e23](https://linux-hardware.org/?probe=7c56c30e23) | Mar 29, 2023 |
| HP            | Pavilion g7                 | Notebook    | [5b1e547f92](https://linux-hardware.org/?probe=5b1e547f92) | Mar 29, 2023 |
| Gigabyte      | P55-UD6-C                   | Desktop     | [010ed7a818](https://linux-hardware.org/?probe=010ed7a818) | Mar 29, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [ccb2d60f5c](https://linux-hardware.org/?probe=ccb2d60f5c) | Mar 29, 2023 |
| HP            | Pavilion g7                 | Notebook    | [ce74564fd9](https://linux-hardware.org/?probe=ce74564fd9) | Mar 28, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [5520b0fc5f](https://linux-hardware.org/?probe=5520b0fc5f) | Mar 28, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | Notebook    | [67789fc0d1](https://linux-hardware.org/?probe=67789fc0d1) | Mar 28, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [042e72aea5](https://linux-hardware.org/?probe=042e72aea5) | Mar 28, 2023 |
| MSI           | B450M MORTAR                | Desktop     | [7febdf82c0](https://linux-hardware.org/?probe=7febdf82c0) | Mar 28, 2023 |
| Lenovo        | ThinkPad T470p 20J7S0QK0... | Notebook    | [7f5fb11940](https://linux-hardware.org/?probe=7f5fb11940) | Mar 28, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [151a527b35](https://linux-hardware.org/?probe=151a527b35) | Mar 28, 2023 |
| ASUSTek       | TX201LA                     | Notebook    | [27c77d0b6c](https://linux-hardware.org/?probe=27c77d0b6c) | Mar 28, 2023 |
| ASUSTek       | ROG Flow Z13 GZ301ZC_GZ3... | Tablet      | [e5644591de](https://linux-hardware.org/?probe=e5644591de) | Mar 28, 2023 |
| ASUSTek       | TP410UA                     | Convertible | [b74b7f7d31](https://linux-hardware.org/?probe=b74b7f7d31) | Mar 28, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [4b0ae8033f](https://linux-hardware.org/?probe=4b0ae8033f) | Mar 28, 2023 |
| Lenovo        | ThinkPad T495 20NJ000XGE    | Notebook    | [70715024f2](https://linux-hardware.org/?probe=70715024f2) | Mar 28, 2023 |
| Intel         | NUC11PABi7 K90104-305       | Mini pc     | [35510eaf63](https://linux-hardware.org/?probe=35510eaf63) | Mar 28, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [999219f420](https://linux-hardware.org/?probe=999219f420) | Mar 28, 2023 |
| Lenovo        | ThinkServer TS130           | Desktop     | [2a36fc5043](https://linux-hardware.org/?probe=2a36fc5043) | Mar 28, 2023 |
| Dell          | 08HPGT A01                  | Desktop     | [451ccd93f2](https://linux-hardware.org/?probe=451ccd93f2) | Mar 27, 2023 |
| Dell          | 08HPGT A01                  | Desktop     | [e38a63e793](https://linux-hardware.org/?probe=e38a63e793) | Mar 27, 2023 |
| Huanan        | X99-F8D V2.6                | Desktop     | [65f96586ec](https://linux-hardware.org/?probe=65f96586ec) | Mar 27, 2023 |
| HP            | Compaq 6720s                | Notebook    | [9998cb9bfb](https://linux-hardware.org/?probe=9998cb9bfb) | Mar 27, 2023 |
| HP            | 250 G1                      | Notebook    | [75cf798dde](https://linux-hardware.org/?probe=75cf798dde) | Mar 27, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [fc1af1a499](https://linux-hardware.org/?probe=fc1af1a499) | Mar 27, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [ccc0edffff](https://linux-hardware.org/?probe=ccc0edffff) | Mar 27, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [14380327b0](https://linux-hardware.org/?probe=14380327b0) | Mar 27, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [3173dc99b6](https://linux-hardware.org/?probe=3173dc99b6) | Mar 27, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [79dc82b50b](https://linux-hardware.org/?probe=79dc82b50b) | Mar 27, 2023 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [23ee1856bc](https://linux-hardware.org/?probe=23ee1856bc) | Mar 27, 2023 |
| Dell          | Latitude E5250              | Notebook    | [7d9e678484](https://linux-hardware.org/?probe=7d9e678484) | Mar 27, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [6b00de6bed](https://linux-hardware.org/?probe=6b00de6bed) | Mar 27, 2023 |
| Alienware     | 17 R4                       | Notebook    | [4a61d300b5](https://linux-hardware.org/?probe=4a61d300b5) | Mar 27, 2023 |
| Acer          | Predator PT515-51           | Notebook    | [2ac6541cf1](https://linux-hardware.org/?probe=2ac6541cf1) | Mar 27, 2023 |
| Dell          | Latitude 7280               | Notebook    | [409cf549eb](https://linux-hardware.org/?probe=409cf549eb) | Mar 27, 2023 |
| Dell          | 07PR60 A01                  | Desktop     | [f312d049e0](https://linux-hardware.org/?probe=f312d049e0) | Mar 27, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [e069fb2622](https://linux-hardware.org/?probe=e069fb2622) | Mar 26, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [0ab4054ab9](https://linux-hardware.org/?probe=0ab4054ab9) | Mar 26, 2023 |
| Dell          | G15 5515                    | Notebook    | [3af5157823](https://linux-hardware.org/?probe=3af5157823) | Mar 26, 2023 |
| Acer          | Veriton M2631 V:1.0         | Desktop     | [4a4f12631a](https://linux-hardware.org/?probe=4a4f12631a) | Mar 26, 2023 |
| Chuwi         | HeroBook Air                | Notebook    | [836112a53f](https://linux-hardware.org/?probe=836112a53f) | Mar 26, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [250e0a99d1](https://linux-hardware.org/?probe=250e0a99d1) | Mar 26, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [36d5ba7071](https://linux-hardware.org/?probe=36d5ba7071) | Mar 26, 2023 |
| MSI           | X79A-GD45 Plus              | Desktop     | [0a5446e862](https://linux-hardware.org/?probe=0a5446e862) | Mar 26, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [a607ac616d](https://linux-hardware.org/?probe=a607ac616d) | Mar 26, 2023 |
| Dell          | Latitude 7410               | Convertible | [59c5a72671](https://linux-hardware.org/?probe=59c5a72671) | Mar 26, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [3711318620](https://linux-hardware.org/?probe=3711318620) | Mar 26, 2023 |
| BESSTAR Te... | F6BFC                       | Desktop     | [881c531ee5](https://linux-hardware.org/?probe=881c531ee5) | Mar 25, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [2163c72a12](https://linux-hardware.org/?probe=2163c72a12) | Mar 25, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [95b0768bfc](https://linux-hardware.org/?probe=95b0768bfc) | Mar 25, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [a999580cf7](https://linux-hardware.org/?probe=a999580cf7) | Mar 25, 2023 |
| MSI           | 2AE0                        | Desktop     | [43a4a75176](https://linux-hardware.org/?probe=43a4a75176) | Mar 25, 2023 |
| Lenovo        | SHARKBAY No DPK             | Desktop     | [2941abc936](https://linux-hardware.org/?probe=2941abc936) | Mar 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [31788e7103](https://linux-hardware.org/?probe=31788e7103) | Mar 25, 2023 |
| ASRock        | AD525PV3                    | Desktop     | [84545fd0ea](https://linux-hardware.org/?probe=84545fd0ea) | Mar 25, 2023 |
| Dell          | Latitude E6230              | Notebook    | [1a248bdc33](https://linux-hardware.org/?probe=1a248bdc33) | Mar 25, 2023 |
| Lenovo        | G580 2189                   | Notebook    | [edba6da5b6](https://linux-hardware.org/?probe=edba6da5b6) | Mar 25, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [505777b9b6](https://linux-hardware.org/?probe=505777b9b6) | Mar 25, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [ae09be520b](https://linux-hardware.org/?probe=ae09be520b) | Mar 25, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [5acd2b0492](https://linux-hardware.org/?probe=5acd2b0492) | Mar 25, 2023 |
| HP            | OMEN by Laptop 16-b1xxx     | Notebook    | [0096d3d3b1](https://linux-hardware.org/?probe=0096d3d3b1) | Mar 25, 2023 |
| ASUSTek       | GL503VS                     | Notebook    | [8e066fcf6e](https://linux-hardware.org/?probe=8e066fcf6e) | Mar 25, 2023 |
| Samsung       | 950QED                      | Convertible | [14fa80f70c](https://linux-hardware.org/?probe=14fa80f70c) | Mar 25, 2023 |
| MSI           | Summit E16FlipEvo A11MT     | Notebook    | [62839dd4ac](https://linux-hardware.org/?probe=62839dd4ac) | Mar 24, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [24784bc54d](https://linux-hardware.org/?probe=24784bc54d) | Mar 24, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [c2255f36b2](https://linux-hardware.org/?probe=c2255f36b2) | Mar 24, 2023 |
| ASUSTek       | ROG Strix G512LW_G512LW     | Notebook    | [cbb1418cfa](https://linux-hardware.org/?probe=cbb1418cfa) | Mar 24, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [518cef7fe4](https://linux-hardware.org/?probe=518cef7fe4) | Mar 24, 2023 |
| Acer          | Aspire E5-574               | Notebook    | [51a085fb56](https://linux-hardware.org/?probe=51a085fb56) | Mar 24, 2023 |
| Dell          | G15 5515                    | Notebook    | [3510cdb4cf](https://linux-hardware.org/?probe=3510cdb4cf) | Mar 24, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [cce19de050](https://linux-hardware.org/?probe=cce19de050) | Mar 24, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [1503a33123](https://linux-hardware.org/?probe=1503a33123) | Mar 24, 2023 |
| Dell          | Precision 3551              | Notebook    | [bc979e320b](https://linux-hardware.org/?probe=bc979e320b) | Mar 24, 2023 |
| Dell          | Precision 3551              | Notebook    | [0509bee16a](https://linux-hardware.org/?probe=0509bee16a) | Mar 24, 2023 |
| ASUSTek       | ZenBook UX433FN_BX433FN     | Notebook    | [d8e67b032e](https://linux-hardware.org/?probe=d8e67b032e) | Mar 24, 2023 |
| MSI           | Modern 14 B4MW              | Notebook    | [c81d9f3b07](https://linux-hardware.org/?probe=c81d9f3b07) | Mar 24, 2023 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [88900a37b9](https://linux-hardware.org/?probe=88900a37b9) | Mar 24, 2023 |
| ASRock        | X670E Pro RS                | Desktop     | [8437e47a82](https://linux-hardware.org/?probe=8437e47a82) | Mar 24, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [b2cdf1deb7](https://linux-hardware.org/?probe=b2cdf1deb7) | Mar 24, 2023 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [56d564423e](https://linux-hardware.org/?probe=56d564423e) | Mar 24, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [ca7d9a9342](https://linux-hardware.org/?probe=ca7d9a9342) | Mar 24, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [3769ec9ab5](https://linux-hardware.org/?probe=3769ec9ab5) | Mar 24, 2023 |
| Dell          | Latitude 5580               | Notebook    | [d4ad4c55a6](https://linux-hardware.org/?probe=d4ad4c55a6) | Mar 24, 2023 |
| Itautec       | ST 4265                     | Desktop     | [4671d7c30e](https://linux-hardware.org/?probe=4671d7c30e) | Mar 23, 2023 |
| Dell          | Latitude 5285               | Notebook    | [a8114ded15](https://linux-hardware.org/?probe=a8114ded15) | Mar 23, 2023 |
| HP            | 250 G4                      | Notebook    | [e0ff721413](https://linux-hardware.org/?probe=e0ff721413) | Mar 23, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [4731315325](https://linux-hardware.org/?probe=4731315325) | Mar 23, 2023 |
| Dell          | Latitude 5285               | Notebook    | [baa8f358cf](https://linux-hardware.org/?probe=baa8f358cf) | Mar 23, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [aeb25bc22b](https://linux-hardware.org/?probe=aeb25bc22b) | Mar 23, 2023 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [7ed577df49](https://linux-hardware.org/?probe=7ed577df49) | Mar 23, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [50931f533e](https://linux-hardware.org/?probe=50931f533e) | Mar 23, 2023 |
| ASUSTek       | PRIME Z590M-PLUS            | Desktop     | [0027308e3d](https://linux-hardware.org/?probe=0027308e3d) | Mar 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [2d44e8f5c2](https://linux-hardware.org/?probe=2d44e8f5c2) | Mar 23, 2023 |
| Dell          | Latitude 5480               | Notebook    | [ff60b91842](https://linux-hardware.org/?probe=ff60b91842) | Mar 23, 2023 |
| Acer          | Aspire E3-112               | Notebook    | [721e804a03](https://linux-hardware.org/?probe=721e804a03) | Mar 23, 2023 |
| ASRock        | X79 Extreme6                | Desktop     | [1287699f09](https://linux-hardware.org/?probe=1287699f09) | Mar 23, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [950e4b69e8](https://linux-hardware.org/?probe=950e4b69e8) | Mar 23, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [bf24fe6112](https://linux-hardware.org/?probe=bf24fe6112) | Mar 23, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d32ee19009](https://linux-hardware.org/?probe=d32ee19009) | Mar 23, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [457915fe10](https://linux-hardware.org/?probe=457915fe10) | Mar 23, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [69e58cde56](https://linux-hardware.org/?probe=69e58cde56) | Mar 23, 2023 |
| Lenovo        | SDK0F82993 WIN              | Desktop     | [fbff3ec47c](https://linux-hardware.org/?probe=fbff3ec47c) | Mar 23, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [1159055040](https://linux-hardware.org/?probe=1159055040) | Mar 23, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [aad036448d](https://linux-hardware.org/?probe=aad036448d) | Mar 23, 2023 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [299072c37e](https://linux-hardware.org/?probe=299072c37e) | Mar 22, 2023 |
| Lenovo        | ThinkPad L380 20M6S3Q000    | Notebook    | [aab8aada0e](https://linux-hardware.org/?probe=aab8aada0e) | Mar 22, 2023 |
| Lenovo        | Legion 5 82B5               | Notebook    | [5298c41263](https://linux-hardware.org/?probe=5298c41263) | Mar 22, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [7b899e790a](https://linux-hardware.org/?probe=7b899e790a) | Mar 22, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [2be6f0d943](https://linux-hardware.org/?probe=2be6f0d943) | Mar 22, 2023 |
| Apple         | MacBookPro11,5              | Notebook    | [ac5768cd3f](https://linux-hardware.org/?probe=ac5768cd3f) | Mar 22, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [ea18262536](https://linux-hardware.org/?probe=ea18262536) | Mar 22, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [e973d0294d](https://linux-hardware.org/?probe=e973d0294d) | Mar 22, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [386f37d114](https://linux-hardware.org/?probe=386f37d114) | Mar 22, 2023 |
| Samsung       | 550XDA                      | Notebook    | [b145c438d7](https://linux-hardware.org/?probe=b145c438d7) | Mar 22, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [4ee498d9fc](https://linux-hardware.org/?probe=4ee498d9fc) | Mar 22, 2023 |
| MSI           | GF63 Thin 11SC              | Notebook    | [a63c9ded60](https://linux-hardware.org/?probe=a63c9ded60) | Mar 22, 2023 |
| MSI           | GF63 Thin 11SC              | Notebook    | [cc5ca6f040](https://linux-hardware.org/?probe=cc5ca6f040) | Mar 22, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [5207701ff8](https://linux-hardware.org/?probe=5207701ff8) | Mar 22, 2023 |
| Lenovo        | Legion 5 82B5               | Notebook    | [8dfc670e24](https://linux-hardware.org/?probe=8dfc670e24) | Mar 22, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [23e4353a34](https://linux-hardware.org/?probe=23e4353a34) | Mar 22, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [aede16096d](https://linux-hardware.org/?probe=aede16096d) | Mar 22, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [61025e6e8b](https://linux-hardware.org/?probe=61025e6e8b) | Mar 22, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [80d1a2d67d](https://linux-hardware.org/?probe=80d1a2d67d) | Mar 22, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [eb718edb23](https://linux-hardware.org/?probe=eb718edb23) | Mar 22, 2023 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [825332bfce](https://linux-hardware.org/?probe=825332bfce) | Mar 21, 2023 |
| Lenovo        | B50-10 80QR                 | Notebook    | [134bf99094](https://linux-hardware.org/?probe=134bf99094) | Mar 21, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [b4d5442d02](https://linux-hardware.org/?probe=b4d5442d02) | Mar 21, 2023 |
| NZXT          | N7 B550                     | Desktop     | [8ca9bc3db9](https://linux-hardware.org/?probe=8ca9bc3db9) | Mar 21, 2023 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [6d96576431](https://linux-hardware.org/?probe=6d96576431) | Mar 21, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [dbbcf4a29a](https://linux-hardware.org/?probe=dbbcf4a29a) | Mar 21, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [ec2390af74](https://linux-hardware.org/?probe=ec2390af74) | Mar 21, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [a9c58c1f47](https://linux-hardware.org/?probe=a9c58c1f47) | Mar 21, 2023 |
| Dell          | Vostro 14-5480              | Notebook    | [ee892df403](https://linux-hardware.org/?probe=ee892df403) | Mar 21, 2023 |
| Shuttle       | SH570                       | Desktop     | [3ef2bf52b7](https://linux-hardware.org/?probe=3ef2bf52b7) | Mar 21, 2023 |
| Notebook      | W51XTU                      | Notebook    | [de60f3fcba](https://linux-hardware.org/?probe=de60f3fcba) | Mar 21, 2023 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [57663c8d60](https://linux-hardware.org/?probe=57663c8d60) | Mar 21, 2023 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [f5cbd1977f](https://linux-hardware.org/?probe=f5cbd1977f) | Mar 20, 2023 |
| Hampoo        | Cherry Trail CR Hampoo_r... | Notebook    | [e7eb855568](https://linux-hardware.org/?probe=e7eb855568) | Mar 20, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [3298f3c951](https://linux-hardware.org/?probe=3298f3c951) | Mar 20, 2023 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [1686ba2df4](https://linux-hardware.org/?probe=1686ba2df4) | Mar 20, 2023 |
| Lenovo        | ThinkPad T480s 20L8002WM... | Notebook    | [762762da77](https://linux-hardware.org/?probe=762762da77) | Mar 20, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [cb21d30b9e](https://linux-hardware.org/?probe=cb21d30b9e) | Mar 20, 2023 |
| MSI           | PRO Z790-P WIFI             | Desktop     | [038bd3a32b](https://linux-hardware.org/?probe=038bd3a32b) | Mar 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [7fb78c1c79](https://linux-hardware.org/?probe=7fb78c1c79) | Mar 20, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [e3e0efa236](https://linux-hardware.org/?probe=e3e0efa236) | Mar 20, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [4483bfa54d](https://linux-hardware.org/?probe=4483bfa54d) | Mar 20, 2023 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [1840c57073](https://linux-hardware.org/?probe=1840c57073) | Mar 20, 2023 |
| Win elemen... | M600                        | Desktop     | [eb40c2a7fc](https://linux-hardware.org/?probe=eb40c2a7fc) | Mar 20, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [c63a27da32](https://linux-hardware.org/?probe=c63a27da32) | Mar 20, 2023 |
| ASRock        | H81M-HG4 R4.0               | Desktop     | [ef87ac1a64](https://linux-hardware.org/?probe=ef87ac1a64) | Mar 20, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [53a3d14aa0](https://linux-hardware.org/?probe=53a3d14aa0) | Mar 20, 2023 |
| Microsoft     | Surface Laptop 2            | Tablet      | [58900f0caa](https://linux-hardware.org/?probe=58900f0caa) | Mar 19, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [cb27b0fbaf](https://linux-hardware.org/?probe=cb27b0fbaf) | Mar 19, 2023 |
| Dell          | 0YXT71 A00                  | Desktop     | [7a4669a603](https://linux-hardware.org/?probe=7a4669a603) | Mar 19, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [4ad2d5c249](https://linux-hardware.org/?probe=4ad2d5c249) | Mar 19, 2023 |
| Prestigio     | PSB141C01BFH                | Notebook    | [9190e0a0e7](https://linux-hardware.org/?probe=9190e0a0e7) | Mar 19, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [4223bbbf7e](https://linux-hardware.org/?probe=4223bbbf7e) | Mar 19, 2023 |
| Avell High... | B.ON                        | Notebook    | [b215c2fd75](https://linux-hardware.org/?probe=b215c2fd75) | Mar 19, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [5033dda127](https://linux-hardware.org/?probe=5033dda127) | Mar 19, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D60... | Notebook    | [63b182c7d6](https://linux-hardware.org/?probe=63b182c7d6) | Mar 19, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [93ff9f0891](https://linux-hardware.org/?probe=93ff9f0891) | Mar 19, 2023 |
| Toshiba       | Satellite C75D-B            | Notebook    | [1ff56ed31f](https://linux-hardware.org/?probe=1ff56ed31f) | Mar 19, 2023 |
| HP            | G62                         | Notebook    | [2cb4092da0](https://linux-hardware.org/?probe=2cb4092da0) | Mar 19, 2023 |
| HP            | G62                         | Notebook    | [76d7e36f21](https://linux-hardware.org/?probe=76d7e36f21) | Mar 19, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [dca0487261](https://linux-hardware.org/?probe=dca0487261) | Mar 19, 2023 |
| HONOR         | GLO-FX6P                    | Notebook    | [0fb3ebc365](https://linux-hardware.org/?probe=0fb3ebc365) | Mar 19, 2023 |
| ASUSTek       | PRIME Z690-P                | Desktop     | [923aa59ad5](https://linux-hardware.org/?probe=923aa59ad5) | Mar 19, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [88b7883383](https://linux-hardware.org/?probe=88b7883383) | Mar 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [cbad8c5f1e](https://linux-hardware.org/?probe=cbad8c5f1e) | Mar 18, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [b63ad62fc2](https://linux-hardware.org/?probe=b63ad62fc2) | Mar 18, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [783a968012](https://linux-hardware.org/?probe=783a968012) | Mar 18, 2023 |
| MSI           | B365M PRO-VDH               | Desktop     | [3332cb54e5](https://linux-hardware.org/?probe=3332cb54e5) | Mar 18, 2023 |
| Acer          | Aspire A315-54              | Notebook    | [49b005770d](https://linux-hardware.org/?probe=49b005770d) | Mar 18, 2023 |
| Acer          | Aspire A315-54              | Notebook    | [6af556d727](https://linux-hardware.org/?probe=6af556d727) | Mar 18, 2023 |
| Dell          | Vostro 5471                 | Notebook    | [3b0eb35766](https://linux-hardware.org/?probe=3b0eb35766) | Mar 18, 2023 |
| Dell          | Vostro 5471                 | Notebook    | [7743b2a5a9](https://linux-hardware.org/?probe=7743b2a5a9) | Mar 18, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [501c72715a](https://linux-hardware.org/?probe=501c72715a) | Mar 18, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [280e67175b](https://linux-hardware.org/?probe=280e67175b) | Mar 18, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [def0907a23](https://linux-hardware.org/?probe=def0907a23) | Mar 18, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [674c4a159e](https://linux-hardware.org/?probe=674c4a159e) | Mar 18, 2023 |
| ASUSTek       | X750JN                      | Notebook    | [7dd8257bc8](https://linux-hardware.org/?probe=7dd8257bc8) | Mar 18, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [bd119c8898](https://linux-hardware.org/?probe=bd119c8898) | Mar 17, 2023 |
| MSI           | GF65 Thin 10UE              | Notebook    | [8d2db4b0fe](https://linux-hardware.org/?probe=8d2db4b0fe) | Mar 17, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [f219a6e14a](https://linux-hardware.org/?probe=f219a6e14a) | Mar 17, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [35505ab2bf](https://linux-hardware.org/?probe=35505ab2bf) | Mar 17, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [261bcbfc32](https://linux-hardware.org/?probe=261bcbfc32) | Mar 17, 2023 |
| ASUSTek       | X750JN                      | Notebook    | [7ee3dac323](https://linux-hardware.org/?probe=7ee3dac323) | Mar 17, 2023 |
| ASUSTek       | M2N-E SLI                   | Desktop     | [bf5b0c4406](https://linux-hardware.org/?probe=bf5b0c4406) | Mar 17, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [d79a6ae160](https://linux-hardware.org/?probe=d79a6ae160) | Mar 17, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [691f338c53](https://linux-hardware.org/?probe=691f338c53) | Mar 17, 2023 |
| ASUSTek       | X555LB                      | Notebook    | [a00be2eabe](https://linux-hardware.org/?probe=a00be2eabe) | Mar 17, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [4d82c078c8](https://linux-hardware.org/?probe=4d82c078c8) | Mar 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [2ab659150c](https://linux-hardware.org/?probe=2ab659150c) | Mar 16, 2023 |
| HONOR         | BMH-WCX9                    | Notebook    | [47a9ec2aa1](https://linux-hardware.org/?probe=47a9ec2aa1) | Mar 16, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [03123126d0](https://linux-hardware.org/?probe=03123126d0) | Mar 16, 2023 |
| HP            | EliteBook 850 G2            | Notebook    | [f2b9853f35](https://linux-hardware.org/?probe=f2b9853f35) | Mar 16, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [b4483fd4e2](https://linux-hardware.org/?probe=b4483fd4e2) | Mar 16, 2023 |
| Lenovo        | ThinkPad T540p 20BFS1N00... | Notebook    | [03b210c1f8](https://linux-hardware.org/?probe=03b210c1f8) | Mar 16, 2023 |
| Dell          | Latitude D620               | Notebook    | [1731735e10](https://linux-hardware.org/?probe=1731735e10) | Mar 16, 2023 |
| LG Electro... | 15Z980-G.BH72P1             | Notebook    | [0bba01d850](https://linux-hardware.org/?probe=0bba01d850) | Mar 16, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [5667e8416e](https://linux-hardware.org/?probe=5667e8416e) | Mar 16, 2023 |
| Dell          | Latitude E5470              | Notebook    | [cc4f08349d](https://linux-hardware.org/?probe=cc4f08349d) | Mar 16, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [5bf235f5d3](https://linux-hardware.org/?probe=5bf235f5d3) | Mar 16, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [6023b7ce1d](https://linux-hardware.org/?probe=6023b7ce1d) | Mar 16, 2023 |
| Lenovo        | 32E6 SDK0T76530 WIN 3556... | Desktop     | [69cb363858](https://linux-hardware.org/?probe=69cb363858) | Mar 16, 2023 |
| Lenovo        | 32E6 SDK0T76530 WIN 3556... | Desktop     | [c9e4cb7c2e](https://linux-hardware.org/?probe=c9e4cb7c2e) | Mar 16, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [f48398a1e2](https://linux-hardware.org/?probe=f48398a1e2) | Mar 16, 2023 |
| Unknown       | V00                         | Mini pc     | [3a2e981385](https://linux-hardware.org/?probe=3a2e981385) | Mar 16, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [679da48c41](https://linux-hardware.org/?probe=679da48c41) | Mar 16, 2023 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [b72b91fd00](https://linux-hardware.org/?probe=b72b91fd00) | Mar 16, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [907581c9cc](https://linux-hardware.org/?probe=907581c9cc) | Mar 16, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [897879b2c7](https://linux-hardware.org/?probe=897879b2c7) | Mar 16, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [bf303c0c16](https://linux-hardware.org/?probe=bf303c0c16) | Mar 16, 2023 |
| Intel         | NUC5i5RYB H40999-502        | Mini pc     | [8f1af30bba](https://linux-hardware.org/?probe=8f1af30bba) | Mar 15, 2023 |
| MSI           | H81M-P33                    | Desktop     | [cb3d11f591](https://linux-hardware.org/?probe=cb3d11f591) | Mar 15, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0AF00    | Notebook    | [fe02ac3290](https://linux-hardware.org/?probe=fe02ac3290) | Mar 15, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [db96098c80](https://linux-hardware.org/?probe=db96098c80) | Mar 15, 2023 |
| MSI           | B450M MORTAR                | Desktop     | [14a4314e39](https://linux-hardware.org/?probe=14a4314e39) | Mar 15, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [d19eaf791f](https://linux-hardware.org/?probe=d19eaf791f) | Mar 15, 2023 |
| Dell          | Latitude 7430               | Notebook    | [58024877c3](https://linux-hardware.org/?probe=58024877c3) | Mar 15, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | Notebook    | [1e802bfcd0](https://linux-hardware.org/?probe=1e802bfcd0) | Mar 15, 2023 |
| Dell          | Latitude 5530               | Notebook    | [aac966a8af](https://linux-hardware.org/?probe=aac966a8af) | Mar 15, 2023 |
| Dell          | Latitude 7390               | Notebook    | [7cc6b3a278](https://linux-hardware.org/?probe=7cc6b3a278) | Mar 15, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [a519acdd2e](https://linux-hardware.org/?probe=a519acdd2e) | Mar 15, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [96f3739077](https://linux-hardware.org/?probe=96f3739077) | Mar 15, 2023 |
| HP            | 245 G8 Notebook PC          | Notebook    | [6c73c46184](https://linux-hardware.org/?probe=6c73c46184) | Mar 15, 2023 |
| ASUSTek       | X550MD                      | Notebook    | [2cd5ae8a43](https://linux-hardware.org/?probe=2cd5ae8a43) | Mar 15, 2023 |
| Toshiba       | Satellite P55t-B            | Notebook    | [7bd981d445](https://linux-hardware.org/?probe=7bd981d445) | Mar 15, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [fb73add0f6](https://linux-hardware.org/?probe=fb73add0f6) | Mar 14, 2023 |
| Dell          | Inspiron 7375               | Notebook    | [430599b2da](https://linux-hardware.org/?probe=430599b2da) | Mar 14, 2023 |
| Lenovo        | ThinkPad T490 20N3S3UL00    | Notebook    | [a9db94aee2](https://linux-hardware.org/?probe=a9db94aee2) | Mar 14, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [e6fd051ae8](https://linux-hardware.org/?probe=e6fd051ae8) | Mar 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [112d979fc6](https://linux-hardware.org/?probe=112d979fc6) | Mar 14, 2023 |
| MSI           | MS-AEA11                    | All in one  | [b1afba007b](https://linux-hardware.org/?probe=b1afba007b) | Mar 14, 2023 |
| Exo           | Smart XS1                   | Notebook    | [e1e04684eb](https://linux-hardware.org/?probe=e1e04684eb) | Mar 14, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [933110cc30](https://linux-hardware.org/?probe=933110cc30) | Mar 14, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [800c597040](https://linux-hardware.org/?probe=800c597040) | Mar 14, 2023 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [b324afc6f8](https://linux-hardware.org/?probe=b324afc6f8) | Mar 14, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | Notebook    | [d23ddde885](https://linux-hardware.org/?probe=d23ddde885) | Mar 14, 2023 |
| ASRock        | H170M Pro4                  | Desktop     | [c34ef2441a](https://linux-hardware.org/?probe=c34ef2441a) | Mar 14, 2023 |
| Intel         | W2600CR G21602-308          | Server      | [96cda648c2](https://linux-hardware.org/?probe=96cda648c2) | Mar 14, 2023 |
| Dell          | 0C96W1 A03                  | Desktop     | [171959ac44](https://linux-hardware.org/?probe=171959ac44) | Mar 14, 2023 |
| Dell          | 0C96W1 A03                  | Desktop     | [9456c9ff8e](https://linux-hardware.org/?probe=9456c9ff8e) | Mar 14, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [eac2f2ae40](https://linux-hardware.org/?probe=eac2f2ae40) | Mar 14, 2023 |
| System76      | Gazelle                     | Notebook    | [d45f36e46f](https://linux-hardware.org/?probe=d45f36e46f) | Mar 14, 2023 |
| MSI           | Katana GF76 11UD            | Notebook    | [37edbdcce5](https://linux-hardware.org/?probe=37edbdcce5) | Mar 14, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D60... | Notebook    | [2c2920d462](https://linux-hardware.org/?probe=2c2920d462) | Mar 14, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [d422d0d291](https://linux-hardware.org/?probe=d422d0d291) | Mar 14, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | Notebook    | [e6792912bf](https://linux-hardware.org/?probe=e6792912bf) | Mar 14, 2023 |
| MSI           | Stealth GS77 12UHS          | Notebook    | [fe00606a03](https://linux-hardware.org/?probe=fe00606a03) | Mar 14, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [59d2c50a02](https://linux-hardware.org/?probe=59d2c50a02) | Mar 14, 2023 |
| ASUSTek       | Rampage V EXTREME           | Desktop     | [e186537a7e](https://linux-hardware.org/?probe=e186537a7e) | Mar 14, 2023 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [532c5768ad](https://linux-hardware.org/?probe=532c5768ad) | Mar 14, 2023 |
| Toshiba       | Satellite L40               | Notebook    | [bfc73429bb](https://linux-hardware.org/?probe=bfc73429bb) | Mar 13, 2023 |
| HP            | Pro x2 612 G2               | Tablet      | [6ecc8f0bad](https://linux-hardware.org/?probe=6ecc8f0bad) | Mar 13, 2023 |
| Dell          | Inspiron 13 5320            | Notebook    | [efbe50cd5c](https://linux-hardware.org/?probe=efbe50cd5c) | Mar 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [c59a00db09](https://linux-hardware.org/?probe=c59a00db09) | Mar 13, 2023 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [ca456dde7d](https://linux-hardware.org/?probe=ca456dde7d) | Mar 13, 2023 |
| HP            | Pro x2 612 G2               | Tablet      | [13f42eb616](https://linux-hardware.org/?probe=13f42eb616) | Mar 13, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [70de894994](https://linux-hardware.org/?probe=70de894994) | Mar 13, 2023 |
| ASUSTek       | X510UAR                     | Notebook    | [815dfc26ec](https://linux-hardware.org/?probe=815dfc26ec) | Mar 13, 2023 |
| Samsung       | 300E5M/300E5L               | Notebook    | [8567b21f41](https://linux-hardware.org/?probe=8567b21f41) | Mar 13, 2023 |
| MSI           | PRO B550M-VC WIFI           | Desktop     | [c3a62d14b3](https://linux-hardware.org/?probe=c3a62d14b3) | Mar 13, 2023 |
| Gigabyte      | B650 AORUS PRO AX           | Desktop     | [e245557641](https://linux-hardware.org/?probe=e245557641) | Mar 13, 2023 |
| Gigabyte      | 990FXA-UD5 R5               | Desktop     | [532bf1dca2](https://linux-hardware.org/?probe=532bf1dca2) | Mar 13, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [74452c1274](https://linux-hardware.org/?probe=74452c1274) | Mar 13, 2023 |
| Acer          | Aspire R7-371T              | Notebook    | [b6aef449b6](https://linux-hardware.org/?probe=b6aef449b6) | Mar 13, 2023 |
| Lenovo        | Yoga 6-13ALC7 82UD          | Convertible | [6e3643ecb4](https://linux-hardware.org/?probe=6e3643ecb4) | Mar 13, 2023 |
| Lenovo        | IdeaPad U300s 20111         | Notebook    | [aaaee5fcf5](https://linux-hardware.org/?probe=aaaee5fcf5) | Mar 12, 2023 |
| Lenovo        | IdeaPad U300s 20111         | Notebook    | [3f3945f7e3](https://linux-hardware.org/?probe=3f3945f7e3) | Mar 12, 2023 |
| TECNO         | MEGABOOK T1                 | Notebook    | [000c3e4761](https://linux-hardware.org/?probe=000c3e4761) | Mar 12, 2023 |
| Acer          | One S1003                   | Tablet      | [89fff0b13a](https://linux-hardware.org/?probe=89fff0b13a) | Mar 12, 2023 |
| Dell          | Inspiron 5565               | Notebook    | [9415690de2](https://linux-hardware.org/?probe=9415690de2) | Mar 12, 2023 |
| Insyde        | BayTrail                    | Notebook    | [8d0337a8ee](https://linux-hardware.org/?probe=8d0337a8ee) | Mar 12, 2023 |
| Lenovo        | ThinkPad E590 20NBA000AU    | Notebook    | [47bfd44610](https://linux-hardware.org/?probe=47bfd44610) | Mar 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [5c45eb6864](https://linux-hardware.org/?probe=5c45eb6864) | Mar 12, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [1875fd875d](https://linux-hardware.org/?probe=1875fd875d) | Mar 12, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [28769bd85b](https://linux-hardware.org/?probe=28769bd85b) | Mar 12, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [e45386803e](https://linux-hardware.org/?probe=e45386803e) | Mar 12, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [f70aee3bd6](https://linux-hardware.org/?probe=f70aee3bd6) | Mar 12, 2023 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [03c104f5f3](https://linux-hardware.org/?probe=03c104f5f3) | Mar 12, 2023 |
| Dell          | Vostro 14-5480              | Notebook    | [3ea64e75d4](https://linux-hardware.org/?probe=3ea64e75d4) | Mar 12, 2023 |
| ASUSTek       | PRIME Z690-P                | Desktop     | [76054930ac](https://linux-hardware.org/?probe=76054930ac) | Mar 12, 2023 |
| ASUSTek       | PRIME Z690-P                | Desktop     | [a925c8a320](https://linux-hardware.org/?probe=a925c8a320) | Mar 12, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [5434188010](https://linux-hardware.org/?probe=5434188010) | Mar 12, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | Notebook    | [8a8b88087b](https://linux-hardware.org/?probe=8a8b88087b) | Mar 12, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [07ebf171d6](https://linux-hardware.org/?probe=07ebf171d6) | Mar 12, 2023 |
| ASUSTek       | PRIME A520M-E               | Desktop     | [d2b4cffe84](https://linux-hardware.org/?probe=d2b4cffe84) | Mar 11, 2023 |
| ASUSTek       | H170-PRO                    | Desktop     | [c3e0b5bc1d](https://linux-hardware.org/?probe=c3e0b5bc1d) | Mar 11, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [b7a4968bcd](https://linux-hardware.org/?probe=b7a4968bcd) | Mar 11, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | Notebook    | [8aff6217a5](https://linux-hardware.org/?probe=8aff6217a5) | Mar 11, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [599f8de7ba](https://linux-hardware.org/?probe=599f8de7ba) | Mar 11, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | Notebook    | [2a0539c2b1](https://linux-hardware.org/?probe=2a0539c2b1) | Mar 11, 2023 |
| Gigabyte      | Z170X-UD3 Ultra-CF          | Desktop     | [fa2be7de30](https://linux-hardware.org/?probe=fa2be7de30) | Mar 11, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | Notebook    | [5d69c96eca](https://linux-hardware.org/?probe=5d69c96eca) | Mar 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [7e7927f2dd](https://linux-hardware.org/?probe=7e7927f2dd) | Mar 11, 2023 |
| BESSTAR Te... | X300                        | Notebook    | [3f12a2f32e](https://linux-hardware.org/?probe=3f12a2f32e) | Mar 11, 2023 |
| BESSTAR Te... | X300                        | Notebook    | [a6ba9c1545](https://linux-hardware.org/?probe=a6ba9c1545) | Mar 11, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [1d552cfca2](https://linux-hardware.org/?probe=1d552cfca2) | Mar 11, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [d674283cb0](https://linux-hardware.org/?probe=d674283cb0) | Mar 11, 2023 |
| HP            | EliteBook x360 830 G6       | Convertible | [fd29c0dc4e](https://linux-hardware.org/?probe=fd29c0dc4e) | Mar 11, 2023 |
| Proline       | V146SH                      | Notebook    | [460deab2ea](https://linux-hardware.org/?probe=460deab2ea) | Mar 11, 2023 |
| Dell          | XPS 13 9300                 | Notebook    | [d3b7f2f978](https://linux-hardware.org/?probe=d3b7f2f978) | Mar 11, 2023 |
| ASUSTek       | G752VL                      | Notebook    | [4a4ea6f987](https://linux-hardware.org/?probe=4a4ea6f987) | Mar 11, 2023 |
| Acer          | Veriton X4620G v1.0         | Desktop     | [fc27bc474e](https://linux-hardware.org/?probe=fc27bc474e) | Mar 11, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [0f9de03c50](https://linux-hardware.org/?probe=0f9de03c50) | Mar 11, 2023 |
| Fujitsu       | LIFEBOOK U759               | Notebook    | [01025c7c43](https://linux-hardware.org/?probe=01025c7c43) | Mar 11, 2023 |
| MSI           | X370 XPOWER GAMING TITAN... | Desktop     | [abebd8a5c2](https://linux-hardware.org/?probe=abebd8a5c2) | Mar 11, 2023 |
| ASUSTek       | ZenBook 13 UX331UAL         | Notebook    | [9b38c9668e](https://linux-hardware.org/?probe=9b38c9668e) | Mar 10, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [037f2e4a2d](https://linux-hardware.org/?probe=037f2e4a2d) | Mar 10, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [f9cf8b06f6](https://linux-hardware.org/?probe=f9cf8b06f6) | Mar 10, 2023 |
| Lenovo        | ThinkPad T460 20LPS3K002    | Notebook    | [c375b36f4a](https://linux-hardware.org/?probe=c375b36f4a) | Mar 10, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [80ecfacebf](https://linux-hardware.org/?probe=80ecfacebf) | Mar 10, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [e9af5c4cb2](https://linux-hardware.org/?probe=e9af5c4cb2) | Mar 10, 2023 |
| Unknown       | Unknown                     | Notebook    | [cd382356be](https://linux-hardware.org/?probe=cd382356be) | Mar 10, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | Desktop     | [ca937e17a7](https://linux-hardware.org/?probe=ca937e17a7) | Mar 10, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [d35d11c64e](https://linux-hardware.org/?probe=d35d11c64e) | Mar 09, 2023 |
| Lenovo        | 3190 SDK0J40697 WIN 3305... | Mini pc     | [56b4f8a1a9](https://linux-hardware.org/?probe=56b4f8a1a9) | Mar 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [d35772b8bc](https://linux-hardware.org/?probe=d35772b8bc) | Mar 09, 2023 |
| HP            | Notebook                    | Notebook    | [b5ee32f085](https://linux-hardware.org/?probe=b5ee32f085) | Mar 09, 2023 |
| Lenovo        | ThinkPad T440p 20AWS0XX0... | Notebook    | [780937bb9f](https://linux-hardware.org/?probe=780937bb9f) | Mar 09, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [e27d91ea6f](https://linux-hardware.org/?probe=e27d91ea6f) | Mar 09, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [790877da61](https://linux-hardware.org/?probe=790877da61) | Mar 09, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [d7129009b0](https://linux-hardware.org/?probe=d7129009b0) | Mar 09, 2023 |
| Lenovo        | ThinkPad L13 Yoga 20R6S1... | Convertible | [970e94ad07](https://linux-hardware.org/?probe=970e94ad07) | Mar 09, 2023 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | Notebook    | [e4164a80cd](https://linux-hardware.org/?probe=e4164a80cd) | Mar 09, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [c50daaf3b9](https://linux-hardware.org/?probe=c50daaf3b9) | Mar 09, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [5535b412ed](https://linux-hardware.org/?probe=5535b412ed) | Mar 09, 2023 |
| Dell          | Inspiron 7375               | Notebook    | [2dbb99bbb2](https://linux-hardware.org/?probe=2dbb99bbb2) | Mar 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [2664be8926](https://linux-hardware.org/?probe=2664be8926) | Mar 09, 2023 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [9cd2cf85c7](https://linux-hardware.org/?probe=9cd2cf85c7) | Mar 09, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | Notebook    | [dc915e443d](https://linux-hardware.org/?probe=dc915e443d) | Mar 09, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [97698bd9a9](https://linux-hardware.org/?probe=97698bd9a9) | Mar 09, 2023 |
| Google        | Cave                        | Notebook    | [37d6d413b7](https://linux-hardware.org/?probe=37d6d413b7) | Mar 09, 2023 |
| Intel         | NUC5i5RYB H40999-502        | Mini pc     | [7d6aa1edeb](https://linux-hardware.org/?probe=7d6aa1edeb) | Mar 08, 2023 |
| Dell          | Inspiron 3505               | Notebook    | [5ffa875792](https://linux-hardware.org/?probe=5ffa875792) | Mar 08, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [b349a8eedd](https://linux-hardware.org/?probe=b349a8eedd) | Mar 08, 2023 |
| Intel         | ArcherCity                  | Server      | [3ddb00da94](https://linux-hardware.org/?probe=3ddb00da94) | Mar 08, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [ac772ea51f](https://linux-hardware.org/?probe=ac772ea51f) | Mar 08, 2023 |
| Lenovo        | ThinkPad X12 Detachable ... | Tablet      | [89adccae04](https://linux-hardware.org/?probe=89adccae04) | Mar 08, 2023 |
| Lenovo        | ThinkPad T450s 20BX0013G... | Notebook    | [11cf435bfe](https://linux-hardware.org/?probe=11cf435bfe) | Mar 08, 2023 |
| ASRock        | Z370M Pro4                  | Desktop     | [c4bb8436ac](https://linux-hardware.org/?probe=c4bb8436ac) | Mar 08, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [f4de2d1a2a](https://linux-hardware.org/?probe=f4de2d1a2a) | Mar 08, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [a3a369de93](https://linux-hardware.org/?probe=a3a369de93) | Mar 08, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [439ea07bc5](https://linux-hardware.org/?probe=439ea07bc5) | Mar 08, 2023 |
| MSI           | MAG B460M MORTAR            | Desktop     | [233700c52d](https://linux-hardware.org/?probe=233700c52d) | Mar 08, 2023 |
| Dell          | Inspiron 14 5420            | Notebook    | [cb6ec54195](https://linux-hardware.org/?probe=cb6ec54195) | Mar 08, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [dfe7f75406](https://linux-hardware.org/?probe=dfe7f75406) | Mar 08, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [ffaa232ea2](https://linux-hardware.org/?probe=ffaa232ea2) | Mar 08, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [916862cd66](https://linux-hardware.org/?probe=916862cd66) | Mar 08, 2023 |
| Dell          | Latitude 5400               | Notebook    | [3d2504745e](https://linux-hardware.org/?probe=3d2504745e) | Mar 08, 2023 |
| HP            | ProBook 440 G7              | Notebook    | [7f4678dcf1](https://linux-hardware.org/?probe=7f4678dcf1) | Mar 07, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [62800640af](https://linux-hardware.org/?probe=62800640af) | Mar 07, 2023 |
| Dell          | Latitude 5300 2-in-1        | Convertible | [5a706c6543](https://linux-hardware.org/?probe=5a706c6543) | Mar 07, 2023 |
| AZW           | GTR V02                     | Desktop     | [030dde937b](https://linux-hardware.org/?probe=030dde937b) | Mar 07, 2023 |
| Dell          | Latitude 7290               | Notebook    | [38f12088b2](https://linux-hardware.org/?probe=38f12088b2) | Mar 07, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [1aaf3d1b9f](https://linux-hardware.org/?probe=1aaf3d1b9f) | Mar 07, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [e88ffa7e1d](https://linux-hardware.org/?probe=e88ffa7e1d) | Mar 07, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [bac7bd817d](https://linux-hardware.org/?probe=bac7bd817d) | Mar 07, 2023 |
| Acer          | One S1001                   | Notebook    | [b43d7f0a84](https://linux-hardware.org/?probe=b43d7f0a84) | Mar 06, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [5750b514a0](https://linux-hardware.org/?probe=5750b514a0) | Mar 06, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [1209c224e1](https://linux-hardware.org/?probe=1209c224e1) | Mar 06, 2023 |
| Microsoft     | Surface Laptop Go 2         | Tablet      | [f5a1ceaa74](https://linux-hardware.org/?probe=f5a1ceaa74) | Mar 06, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [6735fc94ae](https://linux-hardware.org/?probe=6735fc94ae) | Mar 06, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [3fb642aac7](https://linux-hardware.org/?probe=3fb642aac7) | Mar 06, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [798d6e74da](https://linux-hardware.org/?probe=798d6e74da) | Mar 06, 2023 |
| MSI           | MAG B460M MORTAR            | Desktop     | [de44275a2c](https://linux-hardware.org/?probe=de44275a2c) | Mar 06, 2023 |
| HP            | ProLiant DL380p Gen8        | Server      | [c36bf90efb](https://linux-hardware.org/?probe=c36bf90efb) | Mar 06, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X6... | Notebook    | [bd9c4997b0](https://linux-hardware.org/?probe=bd9c4997b0) | Mar 06, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [98a2c9f264](https://linux-hardware.org/?probe=98a2c9f264) | Mar 06, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [4e05d0a0e9](https://linux-hardware.org/?probe=4e05d0a0e9) | Mar 06, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [4b6c93e678](https://linux-hardware.org/?probe=4b6c93e678) | Mar 06, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [0fca5ee94e](https://linux-hardware.org/?probe=0fca5ee94e) | Mar 06, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [d256faa9fc](https://linux-hardware.org/?probe=d256faa9fc) | Mar 06, 2023 |
| Dell          | 0RY007                      | Desktop     | [1aff8f499e](https://linux-hardware.org/?probe=1aff8f499e) | Mar 06, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [d725cc57f0](https://linux-hardware.org/?probe=d725cc57f0) | Mar 06, 2023 |
| Dell          | Inspiron 15 3525            | Notebook    | [cc3e080ded](https://linux-hardware.org/?probe=cc3e080ded) | Mar 06, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [14eb2d295d](https://linux-hardware.org/?probe=14eb2d295d) | Mar 06, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [e6421e9301](https://linux-hardware.org/?probe=e6421e9301) | Mar 06, 2023 |
| Huanan        | X99-TF                      | Desktop     | [99a3729e53](https://linux-hardware.org/?probe=99a3729e53) | Mar 05, 2023 |
| MSI           | B550M PRO                   | Desktop     | [6d904e2413](https://linux-hardware.org/?probe=6d904e2413) | Mar 05, 2023 |
| Dell          | Inspiron 3593               | Notebook    | [f33f04396c](https://linux-hardware.org/?probe=f33f04396c) | Mar 05, 2023 |
| HP            | 2B05                        | Desktop     | [deb075440f](https://linux-hardware.org/?probe=deb075440f) | Mar 05, 2023 |
| Acer          | Aspire A515-57T             | Notebook    | [ebd1e9103e](https://linux-hardware.org/?probe=ebd1e9103e) | Mar 05, 2023 |
| HP            | 2B05                        | Desktop     | [f21bd9cc58](https://linux-hardware.org/?probe=f21bd9cc58) | Mar 05, 2023 |
| ASUSTek       | P8P67 DELUXE                | Desktop     | [31e4b3ada8](https://linux-hardware.org/?probe=31e4b3ada8) | Mar 05, 2023 |
| Google        | Lillipup                    | Notebook    | [6c7cf4cd9e](https://linux-hardware.org/?probe=6c7cf4cd9e) | Mar 05, 2023 |
| Lenovo        | ThinkPad T15p Gen 1 20TN... | Notebook    | [0811163639](https://linux-hardware.org/?probe=0811163639) | Mar 05, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [dfc84acc1a](https://linux-hardware.org/?probe=dfc84acc1a) | Mar 05, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [42469e8f5d](https://linux-hardware.org/?probe=42469e8f5d) | Mar 05, 2023 |
| Gigabyte      | Z87X-UD3H-CF                | Desktop     | [f0b9f4e39f](https://linux-hardware.org/?probe=f0b9f4e39f) | Mar 05, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [d42a19d17b](https://linux-hardware.org/?probe=d42a19d17b) | Mar 05, 2023 |
| ASRock        | B560M-ITX/ac                | Desktop     | [0bbfe90659](https://linux-hardware.org/?probe=0bbfe90659) | Mar 05, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [eeb75c7723](https://linux-hardware.org/?probe=eeb75c7723) | Mar 05, 2023 |
| Dell          | Latitude 5410               | Notebook    | [6f55e8bbfe](https://linux-hardware.org/?probe=6f55e8bbfe) | Mar 05, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [e61f05b7f6](https://linux-hardware.org/?probe=e61f05b7f6) | Mar 05, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U4S... | Notebook    | [fb996384c6](https://linux-hardware.org/?probe=fb996384c6) | Mar 05, 2023 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [79e06d188d](https://linux-hardware.org/?probe=79e06d188d) | Mar 04, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [925e02d1dc](https://linux-hardware.org/?probe=925e02d1dc) | Mar 04, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [e2ad6f0e57](https://linux-hardware.org/?probe=e2ad6f0e57) | Mar 04, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [7d9acf8639](https://linux-hardware.org/?probe=7d9acf8639) | Mar 04, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [a28f5eeec0](https://linux-hardware.org/?probe=a28f5eeec0) | Mar 04, 2023 |
| Toshiba       | Satellite L40               | Notebook    | [bd108fcfba](https://linux-hardware.org/?probe=bd108fcfba) | Mar 04, 2023 |
| ASRock        | X470 Taichi                 | Desktop     | [59392dfa37](https://linux-hardware.org/?probe=59392dfa37) | Mar 04, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [6f7115f084](https://linux-hardware.org/?probe=6f7115f084) | Mar 04, 2023 |
| ASUSTek       | ROG Flow X16 GV601RM_GV6... | Convertible | [d24552db45](https://linux-hardware.org/?probe=d24552db45) | Mar 04, 2023 |
| MSI           | B350 TOMAHAWK ARCTIC        | Desktop     | [06063736c6](https://linux-hardware.org/?probe=06063736c6) | Mar 04, 2023 |
| Purism        | Librem 14                   | Notebook    | [fbae41cbd5](https://linux-hardware.org/?probe=fbae41cbd5) | Mar 04, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [b4110d0e0b](https://linux-hardware.org/?probe=b4110d0e0b) | Mar 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [bd5e51c339](https://linux-hardware.org/?probe=bd5e51c339) | Mar 04, 2023 |
| Toshiba       | Satellite L40               | Notebook    | [e3f1423c39](https://linux-hardware.org/?probe=e3f1423c39) | Mar 04, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | Notebook    | [1bcec582e3](https://linux-hardware.org/?probe=1bcec582e3) | Mar 03, 2023 |
| MSI           | MAG B460M MORTAR WIFI       | Desktop     | [4b9b04ef26](https://linux-hardware.org/?probe=4b9b04ef26) | Mar 03, 2023 |
| MSI           | MAG B460M MORTAR WIFI       | Desktop     | [b6535fad6b](https://linux-hardware.org/?probe=b6535fad6b) | Mar 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [1ee7b087a8](https://linux-hardware.org/?probe=1ee7b087a8) | Mar 03, 2023 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [196e49402d](https://linux-hardware.org/?probe=196e49402d) | Mar 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [4b20311834](https://linux-hardware.org/?probe=4b20311834) | Mar 03, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [cd6c75d08e](https://linux-hardware.org/?probe=cd6c75d08e) | Mar 03, 2023 |
| Chuwi         | HeroBook Air                | Notebook    | [43248e0ae9](https://linux-hardware.org/?probe=43248e0ae9) | Mar 03, 2023 |
| Toshiba       | Satellite L515              | Notebook    | [daf95cc1e5](https://linux-hardware.org/?probe=daf95cc1e5) | Mar 03, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [7efed287ee](https://linux-hardware.org/?probe=7efed287ee) | Mar 03, 2023 |
| MSI           | GS63VR 6RF                  | Notebook    | [dd60a9c73b](https://linux-hardware.org/?probe=dd60a9c73b) | Mar 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [5906e1b848](https://linux-hardware.org/?probe=5906e1b848) | Mar 03, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [c4c7ebf544](https://linux-hardware.org/?probe=c4c7ebf544) | Mar 03, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [191bd6ec28](https://linux-hardware.org/?probe=191bd6ec28) | Mar 03, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [391c255a97](https://linux-hardware.org/?probe=391c255a97) | Mar 03, 2023 |
| ASUSTek       | TUF Gaming B660M-E D4       | Desktop     | [277d16fb2a](https://linux-hardware.org/?probe=277d16fb2a) | Mar 02, 2023 |
| Microsoft     | Surface Go 3                | Tablet      | [86ec7ef027](https://linux-hardware.org/?probe=86ec7ef027) | Mar 02, 2023 |
| ASUSTek       | Maximus VII RANGER          | Desktop     | [3934b91be7](https://linux-hardware.org/?probe=3934b91be7) | Mar 02, 2023 |
| ASUSTek       | ROG Flow X13 GV301RE_GV3... | Convertible | [886538fe37](https://linux-hardware.org/?probe=886538fe37) | Mar 02, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [8ef1c9b71d](https://linux-hardware.org/?probe=8ef1c9b71d) | Mar 02, 2023 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [e5b411431c](https://linux-hardware.org/?probe=e5b411431c) | Mar 02, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [22c9e146ee](https://linux-hardware.org/?probe=22c9e146ee) | Mar 02, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [6b7925d129](https://linux-hardware.org/?probe=6b7925d129) | Mar 02, 2023 |
| MSI           | B350 TOMAHAWK               | Desktop     | [e699d6bb6e](https://linux-hardware.org/?probe=e699d6bb6e) | Mar 02, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [883911a8df](https://linux-hardware.org/?probe=883911a8df) | Mar 02, 2023 |
| AZW           | SEi                         | Desktop     | [eb876ab2f4](https://linux-hardware.org/?probe=eb876ab2f4) | Mar 02, 2023 |
| AZW           | SEi                         | Desktop     | [7184a124c7](https://linux-hardware.org/?probe=7184a124c7) | Mar 02, 2023 |
| Dell          | 0KRC95 A02                  | Desktop     | [3bb7b686ec](https://linux-hardware.org/?probe=3bb7b686ec) | Mar 02, 2023 |
| HP            | 255 G3                      | Notebook    | [78c4cd0a9c](https://linux-hardware.org/?probe=78c4cd0a9c) | Mar 01, 2023 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | Desktop     | [420e6e6325](https://linux-hardware.org/?probe=420e6e6325) | Mar 01, 2023 |
| Lenovo        | Yoga 920-13IKB 80Y7         | Convertible | [43deb753b9](https://linux-hardware.org/?probe=43deb753b9) | Mar 01, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [50520b2cf0](https://linux-hardware.org/?probe=50520b2cf0) | Mar 01, 2023 |
| Gigabyte      | B365M GAMING HD             | Desktop     | [1b3d15d8f6](https://linux-hardware.org/?probe=1b3d15d8f6) | Mar 01, 2023 |
| Gigabyte      | B365M GAMING HD             | Desktop     | [0485a3d508](https://linux-hardware.org/?probe=0485a3d508) | Mar 01, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [9d6539b8f6](https://linux-hardware.org/?probe=9d6539b8f6) | Mar 01, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [588ac214ef](https://linux-hardware.org/?probe=588ac214ef) | Mar 01, 2023 |
| HP            | 834F                        | Desktop     | [96631603b3](https://linux-hardware.org/?probe=96631603b3) | Mar 01, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [8c878d99a1](https://linux-hardware.org/?probe=8c878d99a1) | Mar 01, 2023 |
| ASUSTek       | ROG Flow X13 GV301RE_GV3... | Convertible | [915d5fcb1d](https://linux-hardware.org/?probe=915d5fcb1d) | Mar 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [9ba7cfbdeb](https://linux-hardware.org/?probe=9ba7cfbdeb) | Mar 01, 2023 |
| Lenovo        | ThinkBook 15 G4 ABA 21DL    | Notebook    | [94809b7bc2](https://linux-hardware.org/?probe=94809b7bc2) | Mar 01, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [4d1bdc90ea](https://linux-hardware.org/?probe=4d1bdc90ea) | Mar 01, 2023 |
| MSI           | A320M GRENADE               | Desktop     | [1a5ffd0fc4](https://linux-hardware.org/?probe=1a5ffd0fc4) | Mar 01, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [6a99428156](https://linux-hardware.org/?probe=6a99428156) | Mar 01, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [3db8300147](https://linux-hardware.org/?probe=3db8300147) | Mar 01, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [1c09e468d0](https://linux-hardware.org/?probe=1c09e468d0) | Mar 01, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [713781f44e](https://linux-hardware.org/?probe=713781f44e) | Mar 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [833b6835b6](https://linux-hardware.org/?probe=833b6835b6) | Mar 01, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [165c0356a5](https://linux-hardware.org/?probe=165c0356a5) | Mar 01, 2023 |
| Dell          | 0KRC95 A02                  | Desktop     | [5cf1539621](https://linux-hardware.org/?probe=5cf1539621) | Mar 01, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [22d51a725f](https://linux-hardware.org/?probe=22d51a725f) | Feb 28, 2023 |
| Dell          | Latitude E7270              | Notebook    | [2718026d03](https://linux-hardware.org/?probe=2718026d03) | Feb 28, 2023 |
| TECNO         | MEGABOOK T1                 | Notebook    | [3b70c27ca4](https://linux-hardware.org/?probe=3b70c27ca4) | Feb 28, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [48c5c743c9](https://linux-hardware.org/?probe=48c5c743c9) | Feb 28, 2023 |
| ASRock        | H61M-VS                     | Desktop     | [04d5b9593e](https://linux-hardware.org/?probe=04d5b9593e) | Feb 28, 2023 |
| HUAWEI        | MRC-WX0                     | Notebook    | [e2776f99bf](https://linux-hardware.org/?probe=e2776f99bf) | Feb 28, 2023 |
| HP            | ProBook 635 Aero G8 Note... | Notebook    | [93ee76f198](https://linux-hardware.org/?probe=93ee76f198) | Feb 28, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [9a897f5d7c](https://linux-hardware.org/?probe=9a897f5d7c) | Feb 28, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | Notebook    | [b5a4a1809f](https://linux-hardware.org/?probe=b5a4a1809f) | Feb 28, 2023 |
| TECNO         | MEGABOOK T1                 | Notebook    | [3d003c6d17](https://linux-hardware.org/?probe=3d003c6d17) | Feb 28, 2023 |
| ASUSTek       | ROG Strix G712LW_G712LW     | Notebook    | [ed67c567d2](https://linux-hardware.org/?probe=ed67c567d2) | Feb 28, 2023 |
| Standard      | Unknown                     | Notebook    | [63732ac2da](https://linux-hardware.org/?probe=63732ac2da) | Feb 28, 2023 |
| HP            | 158A                        | Desktop     | [64f3590183](https://linux-hardware.org/?probe=64f3590183) | Feb 28, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [1b5fd0df61](https://linux-hardware.org/?probe=1b5fd0df61) | Feb 28, 2023 |
| Dell          | Precision 5570              | Notebook    | [7e8d7c37cb](https://linux-hardware.org/?probe=7e8d7c37cb) | Feb 28, 2023 |
| Fujitsu       | D3224-P1 S26361-D3224-P1    | Desktop     | [53649a9546](https://linux-hardware.org/?probe=53649a9546) | Feb 28, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [c829e9e0b8](https://linux-hardware.org/?probe=c829e9e0b8) | Feb 27, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Fedora_37/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                 | Computers | Percent |
|-------------------------|-----------|---------|
| 6.0.7-301.fc37.x86_64   | 148       | 6.47%   |
| 6.0.15-300.fc37.x86_64  | 131       | 5.73%   |
| 6.0.12-300.fc37.x86_64  | 107       | 4.68%   |
| 6.1.14-200.fc37.x86_64  | 97        | 4.24%   |
| 6.1.18-200.fc37.x86_64  | 88        | 3.85%   |
| 6.0.9-300.fc37.x86_64   | 87        | 3.81%   |
| 6.0.8-300.fc37.x86_64   | 86        | 3.76%   |
| 6.1.7-200.fc37.x86_64   | 80        | 3.5%    |
| 6.0.11-300.fc37.x86_64  | 71        | 3.11%   |
| 6.2.8-200.fc37.x86_64   | 69        | 3.02%   |
| 6.1.8-200.fc37.x86_64   | 69        | 3.02%   |
| 6.1.11-200.fc37.x86_64  | 67        | 2.93%   |
| 6.2.7-200.fc37.x86_64   | 66        | 2.89%   |
| 6.1.9-200.fc37.x86_64   | 66        | 2.89%   |
| 6.1.6-200.fc37.x86_64   | 64        | 2.8%    |
| 6.0.10-300.fc37.x86_64  | 62        | 2.71%   |
| 6.1.13-200.fc37.x86_64  | 58        | 2.54%   |
| 6.2.9-200.fc37.x86_64   | 57        | 2.49%   |
| 6.1.15-200.fc37.x86_64  | 51        | 2.23%   |
| 6.0.18-300.fc37.x86_64  | 50        | 2.19%   |
| 6.1.10-200.fc37.x86_64  | 49        | 2.14%   |
| 6.0.16-300.fc37.x86_64  | 40        | 1.75%   |
| 5.19.16-301.fc37.x86_64 | 39        | 1.71%   |
| 6.1.5-200.fc37.x86_64   | 35        | 1.53%   |
| 6.2.15-200.fc37.x86_64  | 32        | 1.4%    |
| 6.2.10-200.fc37.x86_64  | 30        | 1.31%   |
| 6.0.17-300.fc37.x86_64  | 29        | 1.27%   |
| 6.1.12-200.fc37.x86_64  | 28        | 1.22%   |
| 6.0.14-300.fc37.x86_64  | 28        | 1.22%   |
| 6.0.13-300.fc37.x86_64  | 22        | 0.96%   |
| 6.2.14-200.fc37.x86_64  | 20        | 0.87%   |
| 5.19.13-300.fc37.x86_64 | 18        | 0.79%   |
| 6.3.8-100.fc37.x86_64   | 16        | 0.7%    |
| 6.2.11-200.fc37.x86_64  | 15        | 0.66%   |
| 5.19.8-300.fc37.x86_64  | 15        | 0.66%   |
| 5.19.9-300.fc37.x86_64  | 14        | 0.61%   |
| 5.19.7-300.fc37.x86_64  | 14        | 0.61%   |
| 6.2.12-200.fc37.x86_64  | 13        | 0.57%   |
| 6.0.6-300.fc37.x86_64   | 9         | 0.39%   |
| 5.19.15-301.fc37.x86_64 | 9         | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.0.7   | 150       | 6.56%   |
| 6.0.15  | 134       | 5.86%   |
| 6.0.12  | 109       | 4.77%   |
| 6.1.14  | 100       | 4.37%   |
| 6.0.9   | 94        | 4.11%   |
| 6.1.18  | 91        | 3.98%   |
| 6.0.8   | 90        | 3.94%   |
| 6.1.7   | 80        | 3.5%    |
| 6.1.11  | 72        | 3.15%   |
| 6.0.11  | 72        | 3.15%   |
| 6.1.8   | 71        | 3.11%   |
| 6.2.8   | 70        | 3.06%   |
| 6.2.7   | 68        | 2.97%   |
| 6.1.9   | 67        | 2.93%   |
| 6.0.10  | 65        | 2.84%   |
| 6.1.6   | 64        | 2.8%    |
| 6.2.9   | 58        | 2.54%   |
| 6.1.13  | 58        | 2.54%   |
| 6.1.15  | 51        | 2.23%   |
| 6.1.10  | 51        | 2.23%   |
| 6.0.18  | 50        | 2.19%   |
| 5.19.16 | 47        | 2.06%   |
| 6.0.16  | 42        | 1.84%   |
| 6.1.5   | 36        | 1.57%   |
| 6.2.15  | 33        | 1.44%   |
| 6.2.10  | 32        | 1.4%    |
| 6.1.12  | 31        | 1.36%   |
| 6.0.17  | 30        | 1.31%   |
| 6.0.14  | 28        | 1.22%   |
| 6.0.13  | 23        | 1.01%   |
| 6.2.14  | 20        | 0.87%   |
| 5.19.13 | 19        | 0.83%   |
| 6.3.8   | 16        | 0.7%    |
| 5.19.8  | 16        | 0.7%    |
| 6.2.11  | 15        | 0.66%   |
| 5.19.9  | 14        | 0.61%   |
| 5.19.7  | 14        | 0.61%   |
| 6.2.12  | 13        | 0.57%   |
| 5.19.15 | 11        | 0.48%   |
| 6.1.0   | 9         | 0.39%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.0     | 866       | 39.6%   |
| 6.1     | 745       | 34.06%  |
| 6.2     | 313       | 14.31%  |
| 5.19    | 157       | 7.18%   |
| 6.3     | 36        | 1.65%   |
| 6.4     | 34        | 1.55%   |
| 6.5     | 21        | 0.96%   |
| 5.18    | 5         | 0.23%   |
| 5.17    | 4         | 0.18%   |
| 5.15    | 2         | 0.09%   |
| 5.8     | 1         | 0.05%   |
| 5.16    | 1         | 0.05%   |
| 5.10    | 1         | 0.05%   |
| 5.0     | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 2045      | 99.66%  |
| aarch64 | 7         | 0.34%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| GNOME                        | 1502      | 72.81%  |
| KDE5                         | 351       | 17.01%  |
| Unknown                      | 56        | 2.71%   |
| XFCE                         | 40        | 1.94%   |
| X-Cinnamon                   | 24        | 1.16%   |
| MATE                         | 22        | 1.07%   |
| i3                           | 15        | 0.73%   |
| Cinnamon                     | 14        | 0.68%   |
| sway                         | 6         | 0.29%   |
| LXQt                         | 5         | 0.24%   |
| GNOME Classic                | 5         | 0.24%   |
| LXDE                         | 4         | 0.19%   |
| Xpra                         | 3         | 0.15%   |
| qtile                        | 2         | 0.1%    |
| KDE                          | 2         | 0.1%    |
| GNOME-Classic                | 2         | 0.1%    |
| bspwm                        | 2         | 0.1%    |
| xmonad                       | 1         | 0.05%   |
| xinit-compat                 | 1         | 0.05%   |
| Phosh:GNOME                  | 1         | 0.05%   |
| Hyprland                     | 1         | 0.05%   |
| fluxbox                      | 1         | 0.05%   |
| Deepin                       | 1         | 0.05%   |
| custom                       | 1         | 0.05%   |
| ${XDG_CURRENT_DESKTOP:-sway} | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 1490      | 71.67%  |
| X11     | 522       | 25.11%  |
| Tty     | 38        | 1.83%   |
| Unknown | 29        | 1.39%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1028      | 49.66%  |
| GDM     | 735       | 35.51%  |
| SDDM    | 183       | 8.84%   |
| LightDM | 119       | 5.75%   |
| LXDM    | 4         | 0.19%   |
| GREETD  | 1         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1091      | 52.91%  |
| en_GB   | 155       | 7.52%   |
| ru_RU   | 126       | 6.11%   |
| de_DE   | 89        | 4.32%   |
| pt_BR   | 86        | 4.17%   |
| fr_FR   | 57        | 2.76%   |
| it_IT   | 53        | 2.57%   |
| en_AU   | 46        | 2.23%   |
| en_CA   | 43        | 2.09%   |
| es_ES   | 37        | 1.79%   |
| pl_PL   | 29        | 1.41%   |
| en_IN   | 28        | 1.36%   |
| es_MX   | 15        | 0.73%   |
| es_CL   | 15        | 0.73%   |
| zh_CN   | 14        | 0.68%   |
| tr_TR   | 12        | 0.58%   |
| C       | 9         | 0.44%   |
| Unknown | 9         | 0.44%   |
| en_NZ   | 8         | 0.39%   |
| de_AT   | 8         | 0.39%   |
| cs_CZ   | 8         | 0.39%   |
| hu_HU   | 7         | 0.34%   |
| es_AR   | 7         | 0.34%   |
| en_IE   | 7         | 0.34%   |
| nl_NL   | 6         | 0.29%   |
| sv_SE   | 5         | 0.24%   |
| fi_FI   | 5         | 0.24%   |
| en_ZA   | 5         | 0.24%   |
| de_CH   | 5         | 0.24%   |
| zh_TW   | 4         | 0.19%   |
| fr_BE   | 4         | 0.19%   |
| es_CO   | 4         | 0.19%   |
| en_IL   | 4         | 0.19%   |
| en_DK   | 4         | 0.19%   |
| pt_PT   | 3         | 0.15%   |
| ko_KR   | 3         | 0.15%   |
| ja_JP   | 3         | 0.15%   |
| es_PE   | 3         | 0.15%   |
| en_PH   | 3         | 0.15%   |
| ca_ES   | 3         | 0.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1704      | 82.56%  |
| BIOS | 360       | 17.44%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 1640      | 79.73%  |
| Ext4    | 361       | 17.55%  |
| Xfs     | 48        | 2.33%   |
| Overlay | 5         | 0.24%   |
| F2fs    | 2         | 0.1%    |
| Unknown | 1         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 1015      | 49.1%   |
| Unknown | 979       | 47.36%  |
| MBR     | 73        | 3.53%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1838      | 89.01%  |
| Yes       | 227       | 10.99%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1647      | 79.84%  |
| Yes       | 416       | 20.16%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 414       | 20.18%  |
| ASUSTek Computer    | 363       | 17.69%  |
| Hewlett-Packard     | 255       | 12.43%  |
| Dell                | 251       | 12.23%  |
| MSI                 | 145       | 7.07%   |
| Gigabyte Technology | 107       | 5.21%   |
| Acer                | 89        | 4.34%   |
| ASRock              | 60        | 2.92%   |
| HUAWEI              | 43        | 2.1%    |
| Intel               | 31        | 1.51%   |
| Apple               | 28        | 1.36%   |
| Samsung Electronics | 23        | 1.12%   |
| Toshiba             | 18        | 0.88%   |
| Microsoft           | 16        | 0.78%   |
| Google              | 14        | 0.68%   |
| Timi                | 13        | 0.63%   |
| Fujitsu             | 9         | 0.44%   |
| TUXEDO              | 8         | 0.39%   |
| Notebook            | 8         | 0.39%   |
| Unknown             | 8         | 0.39%   |
| HONOR               | 7         | 0.34%   |
| Framework           | 6         | 0.29%   |
| Alienware           | 6         | 0.29%   |
| System76            | 5         | 0.24%   |
| Pegatron            | 5         | 0.24%   |
| GPD                 | 5         | 0.24%   |
| AZW                 | 5         | 0.24%   |
| Supermicro          | 4         | 0.19%   |
| Schenker            | 4         | 0.19%   |
| Huanan              | 4         | 0.19%   |
| Dynabook            | 4         | 0.19%   |
| Chuwi               | 4         | 0.19%   |
| BESSTAR Tech        | 4         | 0.19%   |
| Sony                | 3         | 0.15%   |
| Positivo            | 3         | 0.15%   |
| LG Electronics      | 3         | 0.15%   |
| Itautec             | 3         | 0.15%   |
| ECS                 | 3         | 0.15%   |
| TECNO               | 2         | 0.1%    |
| Standard            | 2         | 0.1%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| ASUS All Series                             | 17        | 0.83%   |
| Unknown                                     | 12        | 0.58%   |
| Dell OptiPlex 7010                          | 8         | 0.39%   |
| ASUS TUF Gaming X570-PLUS                   | 7         | 0.34%   |
| MSI MS-7C37                                 | 6         | 0.29%   |
| Lenovo ThinkPad X1 Carbon Gen 10 21CBCTO1WW | 6         | 0.29%   |
| Lenovo ThinkBook 15 G3 ACL 21A4             | 6         | 0.29%   |
| HUAWEI CREM-WXX9                            | 6         | 0.29%   |
| HP Notebook                                 | 5         | 0.24%   |
| HP ENVY x360 Convertible 13-ay0xxx          | 5         | 0.24%   |
| Dell XPS 13 7390                            | 5         | 0.24%   |
| ASUS TUF Gaming B550M-PLUS                  | 5         | 0.24%   |
| MSI MS-7C91                                 | 4         | 0.19%   |
| MSI MS-7C84                                 | 4         | 0.19%   |
| MSI MS-7C56                                 | 4         | 0.19%   |
| MSI MS-7C02                                 | 4         | 0.19%   |
| MSI MS-7B89                                 | 4         | 0.19%   |
| MSI MS-7A38                                 | 4         | 0.19%   |
| MSI Modern 14 B11MOU                        | 4         | 0.19%   |
| Lenovo IdeaPadFlex 5 14ARE05 81X2           | 4         | 0.19%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5            | 4         | 0.19%   |
| Lenovo IdeaPad 330-15IKB 81DE               | 4         | 0.19%   |
| HUAWEI MACH-WX9                             | 4         | 0.19%   |
| HUAWEI HVY-WXX9                             | 4         | 0.19%   |
| HP OMEN by Laptop 16-c0xxx                  | 4         | 0.19%   |
| Framework Laptop (12th Gen Intel Core)      | 4         | 0.19%   |
| Dell XPS 13 9310                            | 4         | 0.19%   |
| Dell Latitude 7490                          | 4         | 0.19%   |
| Dell Latitude 5420                          | 4         | 0.19%   |
| Dell Inspiron 5566                          | 4         | 0.19%   |
| ASUS VivoBook_ASUSLaptop X515EA_X515EA      | 4         | 0.19%   |
| ASUS ROG STRIX B450-F GAMING                | 4         | 0.19%   |
| ASUS ProArt Z690-CREATOR WIFI               | 4         | 0.19%   |
| ASUS ProArt X670E-CREATOR WIFI              | 4         | 0.19%   |
| ASUS PRIME B450M-A II                       | 4         | 0.19%   |
| Acer Nitro AN515-54                         | 4         | 0.19%   |
| MSI MS-7C94                                 | 3         | 0.15%   |
| MSI MS-7C52                                 | 3         | 0.15%   |
| MSI MS-7971                                 | 3         | 0.15%   |
| Microsoft Surface Laptop 3                  | 3         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 226       | 11.01%  |
| Dell Inspiron      | 72        | 3.51%   |
| Lenovo IdeaPad     | 70        | 3.41%   |
| Dell Latitude      | 69        | 3.36%   |
| ASUS ROG           | 69        | 3.36%   |
| ASUS PRIME         | 48        | 2.34%   |
| Acer Aspire        | 48        | 2.34%   |
| HP Pavilion        | 45        | 2.19%   |
| ASUS VivoBook      | 43        | 2.1%    |
| HP EliteBook       | 40        | 1.95%   |
| Dell XPS           | 40        | 1.95%   |
| ASUS TUF           | 37        | 1.8%    |
| Lenovo ThinkBook   | 31        | 1.51%   |
| HP Laptop          | 30        | 1.46%   |
| HP ENVY            | 29        | 1.41%   |
| Dell OptiPlex      | 26        | 1.27%   |
| HP ProBook         | 24        | 1.17%   |
| ASUS ASUS          | 24        | 1.17%   |
| Lenovo Yoga        | 23        | 1.12%   |
| ASUS Zenbook       | 21        | 1.02%   |
| Dell Precision     | 20        | 0.97%   |
| ASUS All           | 17        | 0.83%   |
| Microsoft Surface  | 16        | 0.78%   |
| Lenovo Legion      | 16        | 0.78%   |
| Acer Nitro         | 16        | 0.78%   |
| Toshiba Satellite  | 13        | 0.63%   |
| Lenovo ThinkCentre | 12        | 0.58%   |
| HP OMEN            | 12        | 0.58%   |
| Unknown            | 12        | 0.58%   |
| HP ZBook           | 11        | 0.54%   |
| Dell Vostro        | 11        | 0.54%   |
| MSI Modern         | 9         | 0.44%   |
| Gigabyte X570      | 9         | 0.44%   |
| ASUS ProArt        | 8         | 0.39%   |
| Gigabyte B550      | 7         | 0.34%   |
| Acer Predator      | 7         | 0.34%   |
| MSI MS-7C37        | 6         | 0.29%   |
| Lenovo IdeaPadFlex | 6         | 0.29%   |
| HUAWEI CREM-WXX9   | 6         | 0.29%   |
| HP Compaq          | 6         | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 329       | 16.03%  |
| 2020    | 306       | 14.91%  |
| 2022    | 276       | 13.45%  |
| 2019    | 223       | 10.87%  |
| 2018    | 214       | 10.43%  |
| 2017    | 144       | 7.02%   |
| 2012    | 97        | 4.73%   |
| 2014    | 85        | 4.14%   |
| 2013    | 84        | 4.09%   |
| 2016    | 74        | 3.61%   |
| 2015    | 73        | 3.56%   |
| 2011    | 45        | 2.19%   |
| 2010    | 33        | 1.61%   |
| 2008    | 21        | 1.02%   |
| 2009    | 19        | 0.93%   |
| 2023    | 12        | 0.58%   |
| 2007    | 7         | 0.34%   |
| 2006    | 7         | 0.34%   |
| Unknown | 3         | 0.15%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1240      | 60.43%  |
| Desktop        | 613       | 29.87%  |
| Convertible    | 113       | 5.51%   |
| Tablet         | 30        | 1.46%   |
| Mini pc        | 30        | 1.46%   |
| All in one     | 12        | 0.58%   |
| Server         | 8         | 0.39%   |
| System on chip | 6         | 0.29%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1591      | 76.97%  |
| Enabled  | 476       | 23.03%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2034      | 99.12%  |
| Yes  | 18        | 0.88%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 515       | 24.98%  |
| 4.01-8.0        | 430       | 20.85%  |
| 8.01-16.0       | 411       | 19.93%  |
| 32.01-64.0      | 360       | 17.46%  |
| 3.01-4.0        | 143       | 6.94%   |
| 64.01-256.0     | 95        | 4.61%   |
| 24.01-32.0      | 74        | 3.59%   |
| 1.01-2.0        | 27        | 1.31%   |
| 2.01-3.0        | 4         | 0.19%   |
| More than 256.0 | 3         | 0.15%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 752       | 34.32%  |
| 3.01-4.0   | 493       | 22.5%   |
| 2.01-3.0   | 481       | 21.95%  |
| 8.01-16.0  | 206       | 9.4%    |
| 1.01-2.0   | 186       | 8.49%   |
| 0.51-1.0   | 32        | 1.46%   |
| 16.01-24.0 | 26        | 1.19%   |
| 24.01-32.0 | 7         | 0.32%   |
| 32.01-64.0 | 5         | 0.23%   |
| 0.01-0.5   | 3         | 0.14%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1246      | 60.05%  |
| 2      | 507       | 24.43%  |
| 3      | 166       | 8%      |
| 4      | 74        | 3.57%   |
| 5      | 35        | 1.69%   |
| 6      | 15        | 0.72%   |
| 0      | 12        | 0.58%   |
| 7      | 8         | 0.39%   |
| 9      | 3         | 0.14%   |
| 8      | 3         | 0.14%   |
| 410    | 1         | 0.05%   |
| 18     | 1         | 0.05%   |
| 17     | 1         | 0.05%   |
| 15     | 1         | 0.05%   |
| 12     | 1         | 0.05%   |
| 10     | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1704      | 82.92%  |
| Yes       | 351       | 17.08%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1535      | 74.62%  |
| No        | 522       | 25.38%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1706      | 82.94%  |
| No        | 351       | 17.06%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1557      | 75.51%  |
| No        | 505       | 24.49%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 372       | 18.02%  |
| Germany      | 167       | 8.09%   |
| Russia       | 151       | 7.32%   |
| Brazil       | 124       | 6.01%   |
| Italy        | 103       | 4.99%   |
| France       | 70        | 3.39%   |
| UK           | 69        | 3.34%   |
| Poland       | 67        | 3.25%   |
| Canada       | 63        | 3.05%   |
| India        | 62        | 3%      |
| Australia    | 55        | 2.66%   |
| Spain        | 53        | 2.57%   |
| Netherlands  | 51        | 2.47%   |
| Turkey       | 35        | 1.7%    |
| Austria      | 33        | 1.6%    |
| Sweden       | 29        | 1.41%   |
| Mexico       | 25        | 1.21%   |
| Switzerland  | 23        | 1.11%   |
| Czechia      | 22        | 1.07%   |
| Belgium      | 19        | 0.92%   |
| Taiwan       | 16        | 0.78%   |
| Hungary      | 16        | 0.78%   |
| Chile        | 16        | 0.78%   |
| Portugal     | 15        | 0.73%   |
| Indonesia    | 15        | 0.73%   |
| Romania      | 14        | 0.68%   |
| Norway       | 14        | 0.68%   |
| Japan        | 14        | 0.68%   |
| Finland      | 14        | 0.68%   |
| Argentina    | 14        | 0.68%   |
| Israel       | 13        | 0.63%   |
| Vietnam      | 12        | 0.58%   |
| Thailand     | 11        | 0.53%   |
| New Zealand  | 11        | 0.53%   |
| Colombia     | 11        | 0.53%   |
| Ireland      | 10        | 0.48%   |
| Hong Kong    | 10        | 0.48%   |
| South Africa | 9         | 0.44%   |
| Greece       | 9         | 0.44%   |
| Denmark      | 9         | 0.44%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 42        | 1.96%   |
| Berlin            | 23        | 1.08%   |
| Sydney            | 19        | 0.89%   |
| Vienna            | 17        | 0.8%    |
| St Petersburg     | 16        | 0.75%   |
| Madrid            | 16        | 0.75%   |
| Sao Paulo         | 15        | 0.7%    |
| Warsaw            | 14        | 0.65%   |
| Frankfurt am Main | 13        | 0.61%   |
| Milan             | 12        | 0.56%   |
| Melbourne         | 12        | 0.56%   |
| Istanbul          | 12        | 0.56%   |
| Wroclaw           | 10        | 0.47%   |
| London            | 10        | 0.47%   |
| Paris             | 9         | 0.42%   |
| Helsinki          | 9         | 0.42%   |
| Delft             | 9         | 0.42%   |
| Budapest          | 9         | 0.42%   |
| Bengaluru         | 9         | 0.42%   |
| Amsterdam         | 9         | 0.42%   |
| Tokyo             | 8         | 0.37%   |
| Portland          | 8         | 0.37%   |
| Montreal          | 8         | 0.37%   |
| Milano            | 8         | 0.37%   |
| Brisbane          | 8         | 0.37%   |
| Singapore         | 7         | 0.33%   |
| Seattle           | 7         | 0.33%   |
| Santiago          | 7         | 0.33%   |
| Prague            | 7         | 0.33%   |
| Porto Alegre      | 7         | 0.33%   |
| Palmas            | 7         | 0.33%   |
| New York          | 7         | 0.33%   |
| New Taipei        | 7         | 0.33%   |
| Krasnodar         | 7         | 0.33%   |
| Jakarta           | 7         | 0.33%   |
| Bogotá           | 7         | 0.33%   |
| Bangkok           | 7         | 0.33%   |
| Auckland          | 7         | 0.33%   |
| Zurich            | 6         | 0.28%   |
| Yekaterinburg     | 6         | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 667       | 914    | 21.96%  |
| WDC                         | 340       | 519    | 11.2%   |
| Seagate                     | 263       | 346    | 8.66%   |
| SanDisk                     | 226       | 276    | 7.44%   |
| Kingston                    | 168       | 203    | 5.53%   |
| Toshiba                     | 149       | 179    | 4.91%   |
| SK hynix                    | 141       | 156    | 4.64%   |
| Crucial                     | 127       | 160    | 4.18%   |
| Intel                       | 107       | 132    | 3.52%   |
| Unknown                     | 99        | 121    | 3.26%   |
| Micron Technology           | 87        | 101    | 2.86%   |
| KIOXIA                      | 56        | 67     | 1.84%   |
| Phison Electronics          | 44        | 51     | 1.45%   |
| HGST                        | 38        | 57     | 1.25%   |
| A-DATA Technology           | 33        | 34     | 1.09%   |
| Micron/Crucial Technology   | 30        | 35     | 0.99%   |
| Hitachi                     | 29        | 39     | 0.95%   |
| China                       | 25        | 32     | 0.82%   |
| Kingston Technology Company | 19        | 20     | 0.63%   |
| ADATA Technology            | 18        | 20     | 0.59%   |
| Apple                       | 17        | 26     | 0.56%   |
| PNY                         | 16        | 18     | 0.53%   |
| Silicon Motion              | 15        | 16     | 0.49%   |
| Realtek Semiconductor       | 14        | 15     | 0.46%   |
| LITEON                      | 13        | 13     | 0.43%   |
| Corsair                     | 13        | 18     | 0.43%   |
| SPCC                        | 12        | 15     | 0.4%    |
| Phison                      | 12        | 12     | 0.4%    |
| Apacer                      | 12        | 17     | 0.4%    |
| JMicron Technology          | 11        | 14     | 0.36%   |
| Netac                       | 10        | 14     | 0.33%   |
| Unknown                     | 10        | 14     | 0.33%   |
| Intenso                     | 8         | 9      | 0.26%   |
| UMIS                        | 7         | 7      | 0.23%   |
| Transcend                   | 7         | 7      | 0.23%   |
| Gigabyte Technology         | 7         | 9      | 0.23%   |
| Lexar                       | 6         | 8      | 0.2%    |
| Lenovo                      | 6         | 6      | 0.2%    |
| SABRENT                     | 5         | 5      | 0.16%   |
| Patriot                     | 5         | 5      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 122       | 3.68%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 60        | 1.81%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 2TB      | 32        | 0.97%   |
| Kingston SA400S37240G 240GB SSD                     | 32        | 0.97%   |
| Crucial CT1000MX500SSD1 1TB                         | 24        | 0.72%   |
| Seagate ST2000DM008-2FR102 2TB                      | 23        | 0.69%   |
| Kingston SA400S37480G 480GB SSD                     | 23        | 0.69%   |
| Seagate ST1000LM035-1RK172 1TB                      | 21        | 0.63%   |
| Samsung SSD 850 EVO 250GB                           | 21        | 0.63%   |
| Toshiba MQ04ABF100 1TB                              | 20        | 0.6%    |
| Sandisk WD Blue SN550 NVMe SSD 1TB                  | 20        | 0.6%    |
| Samsung SSD 860 EVO 500GB                           | 20        | 0.6%    |
| Micron/Crucial P2 NVMe PCIe SSD 4TB                 | 20        | 0.6%    |
| Intel SSDPEKNU512GZ 512GB                           | 20        | 0.6%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963 250GB | 19        | 0.57%   |
| Kingston SA400S37120G 120GB SSD                     | 19        | 0.57%   |
| Intel SSD 660P Series 1TB                           | 18        | 0.54%   |
| Samsung SSD 980 1TB                                 | 17        | 0.51%   |
| Samsung SSD 870 EVO 500GB                           | 17        | 0.51%   |
| Phison E12 NVMe Controller 1TB                      | 17        | 0.51%   |
| Unknown MMC Card  32GB                              | 16        | 0.48%   |
| Seagate ST1000DM010-2EP102 1TB                      | 16        | 0.48%   |
| Crucial CT240BX500SSD1 240GB                        | 16        | 0.48%   |
| Seagate ST500DM002-1BD142 500GB                     | 15        | 0.45%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 128GB     | 15        | 0.45%   |
| Samsung SSD 980 PRO 1TB                             | 15        | 0.45%   |
| Samsung SSD 860 EVO 250GB                           | 15        | 0.45%   |
| Samsung SSD 850 EVO 500GB                           | 15        | 0.45%   |
| Samsung SSD 970 EVO Plus 500GB                      | 14        | 0.42%   |
| Samsung SSD 860 EVO 1TB                             | 14        | 0.42%   |
| Unknown MMC Card  128GB                             | 13        | 0.39%   |
| Phison E16 PCIe4 NVMe Controller 2TB                | 13        | 0.39%   |
| Crucial CT500MX500SSD1 500GB                        | 13        | 0.39%   |
| Unknown MMC Card  64GB                              | 12        | 0.36%   |
| Samsung SSD 870 EVO 1TB                             | 12        | 0.36%   |
| HGST HTS721010A9E630 1TB                            | 12        | 0.36%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 11        | 0.33%   |
| Toshiba XG6 NVMe SSD Controller 512GB               | 11        | 0.33%   |
| Sandisk WD Black SN850 1024GB                       | 11        | 0.33%   |
| Samsung SSD 970 EVO Plus 2TB                        | 11        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 259       | 340    | 37.37%  |
| WDC                 | 225       | 363    | 32.47%  |
| Toshiba             | 99        | 116    | 14.29%  |
| HGST                | 38        | 57     | 5.48%   |
| Hitachi             | 29        | 39     | 4.18%   |
| Samsung Electronics | 14        | 19     | 2.02%   |
| Unknown             | 6         | 8      | 0.87%   |
| SABRENT             | 5         | 5      | 0.72%   |
| Maxtor              | 4         | 5      | 0.58%   |
| Intenso             | 2         | 2      | 0.29%   |
| External            | 2         | 2      | 0.29%   |
| USB3.0              | 1         | 1      | 0.14%   |
| TO Exter            | 1         | 1      | 0.14%   |
| JMicron Technology  | 1         | 4      | 0.14%   |
| Inateck             | 1         | 4      | 0.14%   |
| IET                 | 1         | 1      | 0.14%   |
| HGST HTS            | 1         | 1      | 0.14%   |
| Hewlett-Packard     | 1         | 12     | 0.14%   |
| Fujitsu             | 1         | 1      | 0.14%   |
| ASMT                | 1         | 2      | 0.14%   |
| Apple               | 1         | 1      | 0.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 218       | 292    | 25.17%  |
| Kingston            | 114       | 134    | 13.16%  |
| Crucial             | 111       | 140    | 12.82%  |
| SanDisk             | 69        | 75     | 7.97%   |
| WDC                 | 56        | 69     | 6.47%   |
| China               | 25        | 32     | 2.89%   |
| SK hynix            | 21        | 21     | 2.42%   |
| Intel               | 20        | 23     | 2.31%   |
| A-DATA Technology   | 20        | 20     | 2.31%   |
| PNY                 | 15        | 17     | 1.73%   |
| Micron Technology   | 15        | 17     | 1.73%   |
| Toshiba             | 14        | 16     | 1.62%   |
| LITEON              | 11        | 11     | 1.27%   |
| Apple               | 11        | 12     | 1.27%   |
| Apacer              | 10        | 14     | 1.15%   |
| Corsair             | 9         | 12     | 1.04%   |
| SPCC                | 7         | 9      | 0.81%   |
| Netac               | 7         | 10     | 0.81%   |
| JMicron Technology  | 6         | 6      | 0.69%   |
| Intenso             | 6         | 6      | 0.69%   |
| Gigabyte Technology | 6         | 8      | 0.69%   |
| Transcend           | 5         | 5      | 0.58%   |
| Patriot             | 5         | 5      | 0.58%   |
| Lexar               | 5         | 7      | 0.58%   |
| GOODRAM             | 5         | 9      | 0.58%   |
| KingSpec            | 4         | 5      | 0.46%   |
| Team                | 3         | 4      | 0.35%   |
| Plextor             | 3         | 3      | 0.35%   |
| Mushkin             | 3         | 3      | 0.35%   |
| LITEONIT            | 3         | 3      | 0.35%   |
| ASMT                | 3         | 3      | 0.35%   |
| WDC WDS2            | 2         | 2      | 0.23%   |
| Verbatim            | 2         | 2      | 0.23%   |
| Unknown             | 2         | 2      | 0.23%   |
| Teclast             | 2         | 3      | 0.23%   |
| OCZ                 | 2         | 2      | 0.23%   |
| LT                  | 2         | 2      | 0.23%   |
| Lenovo              | 2         | 2      | 0.23%   |
| KIOXIA-EXCERIA      | 2         | 2      | 0.23%   |
| KingFast            | 2         | 2      | 0.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 1300      | 1709   | 46.9%   |
| SSD     | 755       | 1458   | 27.24%  |
| HDD     | 579       | 984    | 20.89%  |
| MMC     | 93        | 109    | 3.35%   |
| Unknown | 45        | 53     | 1.62%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 1296      | 1702   | 51%     |
| SATA | 1040      | 2355   | 40.93%  |
| SAS  | 112       | 147    | 4.41%   |
| MMC  | 93        | 109    | 3.66%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 697       | 1382   | 48.98%  |
| 0.51-1.0   | 457       | 634    | 32.12%  |
| 1.01-2.0   | 157       | 204    | 11.03%  |
| 3.01-4.0   | 45        | 74     | 3.16%   |
| 4.01-10.0  | 35        | 62     | 2.46%   |
| 2.01-3.0   | 28        | 63     | 1.97%   |
| 10.01-20.0 | 4         | 23     | 0.28%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 437       | 20.93%  |
| 251-500        | 387       | 18.53%  |
| 1001-2000      | 314       | 15.04%  |
| 101-250        | 236       | 11.3%   |
| 1-20           | 227       | 10.87%  |
| Unknown        | 162       | 7.76%   |
| More than 3000 | 148       | 7.09%   |
| 2001-3000      | 89        | 4.26%   |
| 51-100         | 53        | 2.54%   |
| 21-50          | 35        | 1.68%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 553       | 25.76%  |
| 21-50          | 318       | 14.81%  |
| 101-250        | 292       | 13.6%   |
| 51-100         | 240       | 11.18%  |
| 251-500        | 223       | 10.39%  |
| 501-1000       | 194       | 9.04%   |
| Unknown        | 162       | 7.55%   |
| 1001-2000      | 97        | 4.52%   |
| More than 3000 | 37        | 1.72%   |
| 2001-3000      | 31        | 1.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                                           | Computers | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 870 EVO 1TB                             | 4         | 4      | 2.7%    |
| Samsung Electronics SSD 980 1TB                                 | 3         | 3      | 2.03%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                                | 2         | 2      | 1.35%   |
| WDC WD5000AAKX-603CA0 500GB                                     | 2         | 2      | 1.35%   |
| WDC WD5000AAKX-00ERMA0 500GB                                    | 2         | 2      | 1.35%   |
| WDC WD10EZEX-00BN5A0 1TB                                        | 2         | 2      | 1.35%   |
| Seagate ST500LT012-1DG142 500GB                                 | 2         | 2      | 1.35%   |
| Seagate ST500DM002-1BD142 500GB                                 | 2         | 2      | 1.35%   |
| Seagate ST3500418AS 500GB                                       | 2         | 2      | 1.35%   |
| Seagate ST31000524AS 1TB                                        | 2         | 2      | 1.35%   |
| Samsung Electronics SSD 870 EVO 500GB                           | 2         | 3      | 1.35%   |
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 512GB | 2         | 2      | 1.35%   |
| Intel SSDSC2CT120A3 120GB                                       | 2         | 5      | 1.35%   |
| HGST HTS725050A7E630 500GB                                      | 2         | 2      | 1.35%   |
| HGST HTS721010A9E630 1TB                                        | 2         | 2      | 1.35%   |
| Crucial CT275MX300SSD1 275GB                                    | 2         | 2      | 1.35%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                                | 1         | 1      | 0.68%   |
| WDC WD50EFRX-68MYMN1 5TB                                        | 1         | 4      | 0.68%   |
| WDC WD5000LPVX-22V0TT0 500GB                                    | 1         | 1      | 0.68%   |
| WDC WD5000AVVS-63H0B1 500GB                                     | 1         | 1      | 0.68%   |
| WDC WD5000AAKX-60U6AA0 500GB                                    | 1         | 1      | 0.68%   |
| WDC WD40PURZ-85AKKY0 4TB                                        | 1         | 1      | 0.68%   |
| WDC WD40EZRZ-00WN9B0 4TB                                        | 1         | 1      | 0.68%   |
| WDC WD3200BPVT-80JJ5T0 320GB                                    | 1         | 1      | 0.68%   |
| WDC WD3200AAKS-00V1A0 320GB                                     | 1         | 1      | 0.68%   |
| WDC WD3200AAKS-00UU3A0 320GB                                    | 1         | 1      | 0.68%   |
| WDC WD30EFRX-68AX9N0 3TB                                        | 1         | 1      | 0.68%   |
| WDC WD2500BEVT-80A23T0 250GB                                    | 1         | 1      | 0.68%   |
| WDC WD2500AAKX-753CA1 250GB                                     | 1         | 1      | 0.68%   |
| WDC WD20EZRX-22D8PB0 2TB                                        | 1         | 1      | 0.68%   |
| WDC WD20EZRX-00D8PB0 2TB                                        | 1         | 1      | 0.68%   |
| WDC WD15EARS-00MVWB0 1TB                                        | 1         | 1      | 0.68%   |
| WDC WD140EDFZ-11A0VA0 14TB                                      | 1         | 2      | 0.68%   |
| WDC WD10JPVX-60JC3T1 1TB                                        | 1         | 1      | 0.68%   |
| WDC WD10EZEX-60WN4A0 1TB                                        | 1         | 2      | 0.68%   |
| WDC WD10EZEX-08WN4A0 1TB                                        | 1         | 1      | 0.68%   |
| WDC WD10EZEX-00WN4A0 1TB                                        | 1         | 1      | 0.68%   |
| WDC WD10EFRX-68FYTN0 1TB                                        | 1         | 1      | 0.68%   |
| WDC WD10EADS-65M2B0 1TB                                         | 1         | 1      | 0.68%   |
| WDC WD10EADS-00L5B1 1TB                                         | 1         | 1      | 0.68%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 39        | 52     | 27.46%  |
| WDC                 | 31        | 38     | 21.83%  |
| Samsung Electronics | 18        | 25     | 12.68%  |
| Toshiba             | 8         | 8      | 5.63%   |
| Crucial             | 8         | 8      | 5.63%   |
| SK hynix            | 7         | 7      | 4.93%   |
| HGST                | 5         | 5      | 3.52%   |
| SanDisk             | 4         | 4      | 2.82%   |
| Micron Technology   | 3         | 3      | 2.11%   |
| Kingston            | 3         | 3      | 2.11%   |
| Intel               | 3         | 6      | 2.11%   |
| Maxtor              | 2         | 2      | 1.41%   |
| Hitachi             | 2         | 2      | 1.41%   |
| Corsair             | 2         | 2      | 1.41%   |
| SPCC                | 1         | 1      | 0.7%    |
| Intenso             | 1         | 1      | 0.7%    |
| HGST HTS            | 1         | 1      | 0.7%    |
| Apple               | 1         | 1      | 0.7%    |
| AMD                 | 1         | 2      | 0.7%    |
| A-DATA Technology   | 1         | 1      | 0.7%    |
| Unknown             | 1         | 1      | 0.7%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 39        | 52     | 43.33%  |
| WDC                 | 28        | 35     | 31.11%  |
| Toshiba             | 7         | 7      | 7.78%   |
| Samsung Electronics | 6         | 11     | 6.67%   |
| HGST                | 5         | 5      | 5.56%   |
| Maxtor              | 2         | 2      | 2.22%   |
| Hitachi             | 2         | 2      | 2.22%   |
| HGST HTS            | 1         | 1      | 1.11%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 84        | 115    | 61.76%  |
| SSD  | 41        | 47     | 30.15%  |
| NVMe | 11        | 11     | 8.09%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 980 1TB                  | 2         | 3      | 40%     |
| SPCC M.2 PCIe SSD 2TB                            | 1         | 1      | 20%     |
| Seagate ST31000528AS 1TB                         | 1         | 2      | 20%     |
| Samsung Electronics MZNTY128HDHP-00000 128GB SSD | 1         | 1      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 4      | 60%     |
| SPCC                | 1         | 1      | 20%     |
| Seagate             | 1         | 2      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1136      | 2122   | 50.92%  |
| Works    | 961       | 2011   | 43.07%  |
| Malfunc  | 129       | 173    | 5.78%   |
| Failed   | 5         | 7      | 0.22%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 1065      | 36.74%  |
| Samsung Electronics            | 487       | 16.8%   |
| AMD                            | 423       | 14.59%  |
| SanDisk                        | 229       | 7.9%    |
| SK hynix                       | 120       | 4.14%   |
| Kingston Technology Company    | 77        | 2.66%   |
| Micron Technology              | 73        | 2.52%   |
| Phison Electronics             | 65        | 2.24%   |
| KIOXIA                         | 51        | 1.76%   |
| Toshiba America Info Systems   | 44        | 1.52%   |
| Micron/Crucial Technology      | 43        | 1.48%   |
| ASMedia Technology             | 42        | 1.45%   |
| ADATA Technology               | 31        | 1.07%   |
| Silicon Motion                 | 21        | 0.72%   |
| Marvell Technology Group       | 20        | 0.69%   |
| Realtek Semiconductor          | 17        | 0.59%   |
| Union Memory (Shenzhen)        | 11        | 0.38%   |
| JMicron Technology             | 10        | 0.34%   |
| MAXIO Technology (Hangzhou)    | 9         | 0.31%   |
| Nvidia                         | 8         | 0.28%   |
| Solid State Storage Technology | 7         | 0.24%   |
| Shenzhen Longsys Electronics   | 7         | 0.24%   |
| Lite-On Technology             | 7         | 0.24%   |
| Yangtze Memory Technologies    | 4         | 0.14%   |
| Lenovo                         | 4         | 0.14%   |
| Broadcom / LSI                 | 4         | 0.14%   |
| LSI Logic / Symbios Logic      | 3         | 0.1%    |
| Biwin Storage Technology       | 3         | 0.1%    |
| Apple                          | 3         | 0.1%    |
| VIA Technologies               | 2         | 0.07%   |
| Netac Technology               | 2         | 0.07%   |
| ULi Electronics                | 1         | 0.03%   |
| Transcend                      | 1         | 0.03%   |
| Solidigm                       | 1         | 0.03%   |
| Silicon Image                  | 1         | 0.03%   |
| Seagate Technology             | 1         | 0.03%   |
| Hewlett-Packard                | 1         | 0.03%   |
| Adaptec                        | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 309       | 9.74%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 211       | 6.65%   |
| Intel Volume Management Device NVMe RAID Controller                            | 126       | 3.97%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 119       | 3.75%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 115       | 3.63%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 114       | 3.6%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 69        | 2.18%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 66        | 2.08%   |
| AMD 400 Series Chipset SATA Controller                                         | 61        | 1.92%   |
| AMD 500 Series Chipset SATA Controller                                         | 56        | 1.77%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 54        | 1.7%    |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 51        | 1.61%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 48        | 1.51%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 46        | 1.45%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 44        | 1.39%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 40        | 1.26%   |
| Intel Tiger Lake-LP SATA Controller                                            | 36        | 1.14%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 36        | 1.14%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 35        | 1.1%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 34        | 1.07%   |
| Intel Comet Lake SATA AHCI Controller                                          | 33        | 1.04%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 31        | 0.98%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 31        | 0.98%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 29        | 0.91%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 29        | 0.91%   |
| Phison E12 NVMe Controller                                                     | 28        | 0.88%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 27        | 0.85%   |
| Intel SSD 660P Series                                                          | 27        | 0.85%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 26        | 0.82%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 26        | 0.82%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 26        | 0.82%   |
| Intel SATA Controller [RAID mode]                                              | 25        | 0.79%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 24        | 0.76%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 22        | 0.69%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 22        | 0.69%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 22        | 0.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 22        | 0.69%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 19        | 0.6%    |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 19        | 0.6%    |
| SK hynix BC501 NVMe Solid State Drive                                          | 17        | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 1289      | 45.02%  |
| SATA | 1240      | 43.31%  |
| RAID | 234       | 8.17%   |
| IDE  | 88        | 3.07%   |
| SAS  | 10        | 0.35%   |
| SCSI | 2         | 0.07%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 1408      | 68.62%  |
| AMD     | 637       | 31.04%  |
| ARM     | 6         | 0.29%   |
| Unknown | 1         | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 55        | 2.68%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 37        | 1.8%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 29        | 1.41%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 26        | 1.27%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 26        | 1.27%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 26        | 1.27%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 26        | 1.27%   |
| AMD Ryzen 5 3600 6-Core Processor             | 25        | 1.22%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 24        | 1.17%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 22        | 1.07%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 22        | 1.07%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 22        | 1.07%   |
| Intel 12th Gen Core i7-1260P                  | 22        | 1.07%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 21        | 1.02%   |
| Intel 12th Gen Core i7-12700H                 | 20        | 0.97%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 18        | 0.88%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 18        | 0.88%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 17        | 0.83%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 17        | 0.83%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 17        | 0.83%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 16        | 0.78%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 15        | 0.73%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 15        | 0.73%   |
| Intel 12th Gen Core i7-1255U                  | 15        | 0.73%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 15        | 0.73%   |
| Intel 12th Gen Core i5-1235U                  | 14        | 0.68%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 14        | 0.68%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 13        | 0.63%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 13        | 0.63%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 13        | 0.63%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 13        | 0.63%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 13        | 0.63%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 12        | 0.58%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 12        | 0.58%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 12        | 0.58%   |
| Intel 12th Gen Core i5-1240P                  | 12        | 0.58%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 12        | 0.58%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 12        | 0.58%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 12        | 0.58%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 12        | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 397       | 19.34%  |
| Intel Core i5           | 380       | 18.51%  |
| Other                   | 354       | 17.24%  |
| AMD Ryzen 5             | 217       | 10.57%  |
| AMD Ryzen 7             | 186       | 9.06%   |
| Intel Core i3           | 91        | 4.43%   |
| AMD Ryzen 9             | 78        | 3.8%    |
| Intel Celeron           | 41        | 2%      |
| Intel Xeon              | 39        | 1.9%    |
| AMD Ryzen 7 PRO         | 30        | 1.46%   |
| AMD Ryzen 3             | 27        | 1.32%   |
| Intel Core 2 Duo        | 25        | 1.22%   |
| Intel Atom              | 24        | 1.17%   |
| Intel Pentium           | 20        | 0.97%   |
| AMD Ryzen 5 PRO         | 19        | 0.93%   |
| AMD FX                  | 15        | 0.73%   |
| Intel Core i9           | 13        | 0.63%   |
| AMD A6                  | 10        | 0.49%   |
| Intel Core 2 Quad       | 8         | 0.39%   |
| AMD A4                  | 8         | 0.39%   |
| AMD A10                 | 8         | 0.39%   |
| Intel Pentium Dual-Core | 6         | 0.29%   |
| AMD A8                  | 6         | 0.29%   |
| Intel Pentium Silver    | 4         | 0.19%   |
| AMD Ryzen Threadripper  | 4         | 0.19%   |
| AMD A12                 | 4         | 0.19%   |
| Intel Core m3           | 3         | 0.15%   |
| AMD Phenom II X6        | 3         | 0.15%   |
| AMD Phenom II X4        | 3         | 0.15%   |
| Intel Pentium Gold      | 2         | 0.1%    |
| Intel Pentium Dual      | 2         | 0.1%    |
| Intel Genuine           | 2         | 0.1%    |
| Intel Core 2            | 2         | 0.1%    |
| AMD PRO A10             | 2         | 0.1%    |
| AMD Phenom II X2        | 2         | 0.1%    |
| AMD E1                  | 2         | 0.1%    |
| AMD Athlon 64 X2        | 2         | 0.1%    |
| Intel Xeon Silver       | 1         | 0.05%   |
| Intel Xeon Platinum     | 1         | 0.05%   |
| Intel Xeon Gold         | 1         | 0.05%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 737       | 35.92%  |
| 2       | 441       | 21.49%  |
| 6       | 328       | 15.98%  |
| 8       | 306       | 14.91%  |
| 12      | 93        | 4.53%   |
| 10      | 44        | 2.14%   |
| 14      | 42        | 2.05%   |
| 16      | 38        | 1.85%   |
| 24      | 5         | 0.24%   |
| 3       | 5         | 0.24%   |
| 1       | 5         | 0.24%   |
| 36      | 2         | 0.1%    |
| Unknown | 2         | 0.1%    |
| 96      | 1         | 0.05%   |
| 32      | 1         | 0.05%   |
| 20      | 1         | 0.05%   |
| 5       | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2035      | 99.17%  |
| 2       | 15        | 0.73%   |
| Unknown | 2         | 0.1%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1738      | 84.66%  |
| 1       | 313       | 15.25%  |
| Unknown | 2         | 0.1%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2047      | 99.76%  |
| 64-bit         | 5         | 0.24%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 362       | 17.26%  |
| 0x806c1    | 108       | 5.15%   |
| 0x0a50000c | 85        | 4.05%   |
| 0x306a9    | 77        | 3.67%   |
| 0x806ec    | 76        | 3.62%   |
| 0x806ea    | 75        | 3.58%   |
| 0x906a3    | 71        | 3.39%   |
| 0x906ea    | 63        | 3%      |
| 0x08701021 | 53        | 2.53%   |
| 0x306c3    | 48        | 2.29%   |
| 0x806e9    | 46        | 2.19%   |
| 0x506e3    | 46        | 2.19%   |
| 0x406e3    | 44        | 2.1%    |
| 0x08600106 | 44        | 2.1%    |
| 0x08608103 | 42        | 2%      |
| 0x206a7    | 38        | 1.81%   |
| 0x0a50000d | 37        | 1.76%   |
| 0x08108109 | 33        | 1.57%   |
| 0xa0652    | 32        | 1.53%   |
| 0x306d4    | 29        | 1.38%   |
| 0x0a404102 | 29        | 1.38%   |
| 0x906e9    | 28        | 1.34%   |
| 0x906a4    | 27        | 1.29%   |
| 0x806d1    | 24        | 1.14%   |
| 0x90672    | 22        | 1.05%   |
| 0x706e5    | 21        | 1%      |
| 0x0a601203 | 21        | 1%      |
| 0x40651    | 20        | 0.95%   |
| 0x1067a    | 18        | 0.86%   |
| 0x0a20120a | 18        | 0.86%   |
| 0x0a201016 | 18        | 0.86%   |
| 0x08600104 | 18        | 0.86%   |
| 0x806eb    | 17        | 0.81%   |
| 0x906ed    | 16        | 0.76%   |
| 0x30678    | 15        | 0.72%   |
| 0x0810100b | 15        | 0.72%   |
| 0x0a404101 | 14        | 0.67%   |
| 0x806c2    | 13        | 0.62%   |
| 0x706a8    | 13        | 0.62%   |
| 0x08701013 | 12        | 0.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 420       | 20.47%  |
| Zen 3            | 194       | 9.45%   |
| Alderlake Hybrid | 160       | 7.8%    |
| Zen 2            | 148       | 7.21%   |
| Unknown          | 146       | 7.12%   |
| TigerLake        | 143       | 6.97%   |
| Skylake          | 115       | 5.6%    |
| IvyBridge        | 99        | 4.82%   |
| Haswell          | 98        | 4.78%   |
| CometLake        | 70        | 3.41%   |
| SandyBridge      | 60        | 2.92%   |
| IceLake          | 59        | 2.88%   |
| Zen+             | 55        | 2.68%   |
| Zen              | 38        | 1.85%   |
| Silvermont       | 38        | 1.85%   |
| Broadwell        | 34        | 1.66%   |
| Penryn           | 30        | 1.46%   |
| Piledriver       | 20        | 0.97%   |
| Excavator        | 19        | 0.93%   |
| Westmere         | 16        | 0.78%   |
| Goldmont plus    | 16        | 0.78%   |
| Core             | 15        | 0.73%   |
| K10              | 11        | 0.54%   |
| Tremont          | 7         | 0.34%   |
| Nehalem          | 7         | 0.34%   |
| Steamroller      | 6         | 0.29%   |
| Goldmont         | 6         | 0.29%   |
| Jaguar           | 5         | 0.24%   |
| Bonnell          | 5         | 0.24%   |
| Puma             | 3         | 0.15%   |
| Bulldozer        | 3         | 0.15%   |
| K8 Hammer        | 2         | 0.1%    |
| K10 Llano        | 2         | 0.1%    |
| K8 & K10 hybrid  | 1         | 0.05%   |
| Bobcat           | 1         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 1149      | 45.78%  |
| Nvidia                     | 678       | 27.01%  |
| AMD                        | 674       | 26.85%  |
| ASPEED Technology          | 7         | 0.28%   |
| Matrox Electronics Systems | 2         | 0.08%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 125       | 4.85%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 105       | 4.08%   |
| Intel UHD Graphics 620                                                    | 85        | 3.3%    |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                 | 77        | 2.99%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]             | 74        | 2.87%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 60        | 2.33%   |
| Intel HD Graphics 620                                                     | 58        | 2.25%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 57        | 2.21%   |
| AMD Lucienne                                                              | 54        | 2.1%    |
| Intel 3rd Gen Core processor Graphics Controller                          | 52        | 2.02%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 50        | 1.94%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                   | 50        | 1.94%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 47        | 1.82%   |
| AMD Rembrandt [Radeon 680M]                                               | 46        | 1.79%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 40        | 1.55%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 37        | 1.44%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 36        | 1.4%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 33        | 1.28%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 33        | 1.28%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                               | 31        | 1.2%    |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                | 30        | 1.16%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]             | 30        | 1.16%   |
| Intel HD Graphics 630                                                     | 29        | 1.13%   |
| Intel HD Graphics 5500                                                    | 28        | 1.09%   |
| Intel HD Graphics 530                                                     | 28        | 1.09%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 25        | 0.97%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]          | 25        | 0.97%   |
| AMD Raphael                                                               | 25        | 0.97%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 24        | 0.93%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 24        | 0.93%   |
| AMD Barcelo                                                               | 23        | 0.89%   |
| Nvidia GP108M [GeForce MX150]                                             | 18        | 0.7%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 18        | 0.7%    |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 17        | 0.66%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                 | 15        | 0.58%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 15        | 0.58%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 15        | 0.58%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                 | 15        | 0.58%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 14        | 0.54%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 14        | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 756       | 36.79%  |
| 1 x AMD                  | 517       | 25.16%  |
| Intel + Nvidia           | 332       | 16.16%  |
| 1 x Nvidia               | 265       | 12.9%   |
| AMD + Nvidia             | 72        | 3.5%    |
| 2 x AMD                  | 45        | 2.19%   |
| Intel + AMD              | 37        | 1.8%    |
| 2 x Intel                | 10        | 0.49%   |
| Other                    | 7         | 0.34%   |
| 1 x ASPEED               | 4         | 0.19%   |
| 2 x Nvidia               | 2         | 0.1%    |
| 3 x AMD                  | 1         | 0.05%   |
| 2 x Nvidia + 1 x ASPEED  | 1         | 0.05%   |
| Nvidia + ASPEED          | 1         | 0.05%   |
| 1 x Matrox               | 1         | 0.05%   |
| Intel + 2 x Nvidia       | 1         | 0.05%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.05%   |
| AMD + Matrox             | 1         | 0.05%   |
| AMD + ASPEED             | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1640      | 79.42%  |
| Proprietary | 367       | 17.77%  |
| Unknown     | 58        | 2.81%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1082      | 52.04%  |
| 0.01-0.5   | 239       | 11.5%   |
| 1.01-2.0   | 206       | 9.91%   |
| 3.01-4.0   | 152       | 7.31%   |
| 7.01-8.0   | 149       | 7.17%   |
| 0.51-1.0   | 114       | 5.48%   |
| 8.01-16.0  | 63        | 3.03%   |
| 5.01-6.0   | 55        | 2.65%   |
| 2.01-3.0   | 12        | 0.58%   |
| 16.01-24.0 | 7         | 0.34%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 300       | 12.42%  |
| BOE                     | 291       | 12.05%  |
| Chimei Innolux          | 240       | 9.94%   |
| Samsung Electronics     | 218       | 9.03%   |
| LG Display              | 188       | 7.78%   |
| Dell                    | 175       | 7.25%   |
| Goldstar                | 132       | 5.47%   |
| Hewlett-Packard         | 76        | 3.15%   |
| AOC                     | 71        | 2.94%   |
| Sharp                   | 67        | 2.77%   |
| Acer                    | 66        | 2.73%   |
| Lenovo                  | 53        | 2.19%   |
| BenQ                    | 53        | 2.19%   |
| Philips                 | 38        | 1.57%   |
| ASUSTek Computer        | 35        | 1.45%   |
| Ancor Communications    | 34        | 1.41%   |
| PANDA                   | 30        | 1.24%   |
| CSO                     | 30        | 1.24%   |
| Apple                   | 23        | 0.95%   |
| InfoVision              | 20        | 0.83%   |
| ViewSonic               | 19        | 0.79%   |
| Iiyama                  | 18        | 0.75%   |
| MSI                     | 14        | 0.58%   |
| Gigabyte Technology     | 13        | 0.54%   |
| Sony                    | 12        | 0.5%    |
| Mi                      | 11        | 0.46%   |
| Sceptre Tech            | 10        | 0.41%   |
| Chi Mei Optoelectronics | 9         | 0.37%   |
| Panasonic               | 8         | 0.33%   |
| Unknown                 | 7         | 0.29%   |
| TMX                     | 7         | 0.29%   |
| JDI                     | 7         | 0.29%   |
| Eizo                    | 7         | 0.29%   |
| Toshiba                 | 6         | 0.25%   |
| NEC Computers           | 6         | 0.25%   |
| Vizio                   | 5         | 0.21%   |
| LG Philips              | 5         | 0.21%   |
| HUAWEI                  | 5         | 0.21%   |
| Unknown                 | 5         | 0.21%   |
| Pixio                   | 4         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 20        | 0.8%    |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 15        | 0.6%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 15        | 0.6%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 14        | 0.56%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 14        | 0.56%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 12        | 0.48%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                      | 11        | 0.44%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 10        | 0.4%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 10        | 0.4%    |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 9         | 0.36%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 9         | 0.36%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 8         | 0.32%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 8         | 0.32%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                 | 8         | 0.32%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 8         | 0.32%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 7         | 0.28%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 7         | 0.28%   |
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch      | 7         | 0.28%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 7         | 0.28%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 6         | 0.24%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 6         | 0.24%   |
| Hewlett-Packard 24f HPN3545 1920x1080 527x296mm 23.8-inch             | 6         | 0.24%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 6         | 0.24%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                     | 6         | 0.24%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 6         | 0.24%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch      | 6         | 0.24%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 6         | 0.24%   |
| BOE LCD Monitor BOE092F 2520x1680 338x226mm 16.0-inch                 | 6         | 0.24%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                 | 6         | 0.24%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                 | 6         | 0.24%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch        | 6         | 0.24%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch        | 6         | 0.24%   |
| AOC 24B2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                    | 6         | 0.24%   |
| Samsung Electronics LCD Monitor SDC416D 2880x1800 312x195mm 14.5-inch | 5         | 0.2%    |
| Panasonic TDM13O56 MEI96A2 3000x2000 285x190mm 13.5-inch              | 5         | 0.2%    |
| LG Display LCD Monitor LGD0555 2736x1824 260x173mm 12.3-inch          | 5         | 0.2%    |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 5         | 0.2%    |
| Lenovo LEN L28u-30 LEN65FA 3840x2160 621x341mm 27.9-inch              | 5         | 0.2%    |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 5         | 0.2%    |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 5         | 0.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1120      | 49.6%   |
| 1366x768 (WXGA)    | 211       | 9.34%   |
| 3840x2160 (4K)     | 205       | 9.08%   |
| 2560x1440 (QHD)    | 183       | 8.1%    |
| 1920x1200 (WUXGA)  | 78        | 3.45%   |
| 3440x1440          | 65        | 2.88%   |
| 1600x900 (HD+)     | 58        | 2.57%   |
| 2560x1600          | 53        | 2.35%   |
| 2880x1800          | 31        | 1.37%   |
| 1280x1024 (SXGA)   | 26        | 1.15%   |
| 2560x1080          | 25        | 1.11%   |
| 1680x1050 (WSXGA+) | 23        | 1.02%   |
| 3840x2400          | 19        | 0.84%   |
| 1440x900 (WXGA+)   | 19        | 0.84%   |
| 1280x800 (WXGA)    | 13        | 0.58%   |
| 2256x1504          | 10        | 0.44%   |
| 2160x1440          | 10        | 0.44%   |
| 1920x1280          | 9         | 0.4%    |
| 3840x1080          | 8         | 0.35%   |
| 3000x2000          | 8         | 0.35%   |
| 2736x1824          | 8         | 0.35%   |
| 1360x768           | 7         | 0.31%   |
| 2520x1680          | 6         | 0.27%   |
| 2288x1287          | 6         | 0.27%   |
| Unknown            | 6         | 0.27%   |
| 1600x1200          | 5         | 0.22%   |
| 3456x2160          | 4         | 0.18%   |
| 3200x2000          | 3         | 0.13%   |
| 3200x1800 (QHD+)   | 3         | 0.13%   |
| 3072x1920          | 3         | 0.13%   |
| 1024x768 (XGA)     | 3         | 0.13%   |
| 5760x1080          | 2         | 0.09%   |
| 3840x1600          | 2         | 0.09%   |
| 2880x1620          | 2         | 0.09%   |
| 2240x1400          | 2         | 0.09%   |
| 2160x1350          | 2         | 0.09%   |
| 2160x1200          | 2         | 0.09%   |
| 1920x540           | 2         | 0.09%   |
| 800x1280           | 1         | 0.04%   |
| 4160x1440          | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 606       | 25%     |
| 13      | 287       | 11.84%  |
| 27      | 250       | 10.31%  |
| 14      | 228       | 9.41%   |
| 24      | 192       | 7.92%   |
| 23      | 126       | 5.2%    |
| 21      | 97        | 4%      |
| 17      | 76        | 3.14%   |
| 34      | 74        | 3.05%   |
| 31      | 72        | 2.97%   |
| 16      | 64        | 2.64%   |
| 12      | 45        | 1.86%   |
| Unknown | 30        | 1.24%   |
| 19      | 29        | 1.2%    |
| 20      | 27        | 1.11%   |
| 18      | 26        | 1.07%   |
| 25      | 17        | 0.7%    |
| 22      | 16        | 0.66%   |
| 40      | 15        | 0.62%   |
| 32      | 15        | 0.62%   |
| 11      | 15        | 0.62%   |
| 84      | 13        | 0.54%   |
| 48      | 10        | 0.41%   |
| 54      | 9         | 0.37%   |
| 26      | 9         | 0.37%   |
| 29      | 8         | 0.33%   |
| 28      | 8         | 0.33%   |
| 72      | 7         | 0.29%   |
| 142     | 6         | 0.25%   |
| 35      | 5         | 0.21%   |
| 10      | 5         | 0.21%   |
| 43      | 4         | 0.17%   |
| 42      | 4         | 0.17%   |
| 39      | 4         | 0.17%   |
| 86      | 3         | 0.12%   |
| 69      | 3         | 0.12%   |
| 65      | 2         | 0.08%   |
| 52      | 2         | 0.08%   |
| 38      | 2         | 0.08%   |
| 37      | 2         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1016      | 42.91%  |
| 501-600        | 526       | 22.21%  |
| 201-300        | 218       | 9.21%   |
| 401-500        | 175       | 7.39%   |
| 601-700        | 108       | 4.56%   |
| 351-400        | 104       | 4.39%   |
| 701-800        | 92        | 3.89%   |
| Unknown        | 30        | 1.27%   |
| 1001-1500      | 29        | 1.22%   |
| 801-900        | 26        | 1.1%    |
| 1501-2000      | 24        | 1.01%   |
| 901-1000       | 13        | 0.55%   |
| More than 2000 | 6         | 0.25%   |
| 1-100          | 1         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1617      | 77.15%  |
| 16/10   | 258       | 12.31%  |
| 21/9    | 88        | 4.2%    |
| 3/2     | 56        | 2.67%   |
| 5/4     | 24        | 1.15%   |
| Unknown | 17        | 0.81%   |
| 4/3     | 16        | 0.76%   |
| 32/9    | 7         | 0.33%   |
| 1.00    | 6         | 0.29%   |
| 0.56    | 3         | 0.14%   |
| 3.33    | 1         | 0.05%   |
| 1.96    | 1         | 0.05%   |
| 0.89    | 1         | 0.05%   |
| 0.67    | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 613       | 25.49%  |
| 81-90          | 388       | 16.13%  |
| 201-250        | 335       | 13.93%  |
| 301-350        | 256       | 10.64%  |
| 351-500        | 177       | 7.36%   |
| 71-80          | 129       | 5.36%   |
| 151-200        | 86        | 3.58%   |
| 251-300        | 81        | 3.37%   |
| 121-130        | 64        | 2.66%   |
| 111-120        | 54        | 2.25%   |
| More than 1000 | 50        | 2.08%   |
| 501-1000       | 44        | 1.83%   |
| 61-70          | 35        | 1.46%   |
| Unknown        | 30        | 1.25%   |
| 141-150        | 27        | 1.12%   |
| 51-60          | 18        | 0.75%   |
| 91-100         | 11        | 0.46%   |
| 131-140        | 4         | 0.17%   |
| 41-50          | 2         | 0.08%   |
| 1-40           | 1         | 0.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 805       | 34.7%   |
| 51-100        | 601       | 25.91%  |
| 101-120       | 443       | 19.09%  |
| 161-240       | 292       | 12.59%  |
| More than 240 | 109       | 4.7%    |
| 1-50          | 40        | 1.72%   |
| Unknown       | 30        | 1.29%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1504      | 72.03%  |
| 2     | 441       | 21.12%  |
| 0     | 70        | 3.35%   |
| 3     | 65        | 3.11%   |
| 4     | 6         | 0.29%   |
| 5     | 2         | 0.1%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1227      | 41.09%  |
| Realtek Semiconductor             | 1033      | 34.59%  |
| Qualcomm Atheros                  | 196       | 6.56%   |
| MediaTek                          | 136       | 4.55%   |
| Broadcom                          | 89        | 2.98%   |
| TP-Link                           | 32        | 1.07%   |
| Qualcomm                          | 21        | 0.7%    |
| Lenovo                            | 21        | 0.7%    |
| Ralink Technology                 | 16        | 0.54%   |
| Ralink                            | 15        | 0.5%    |
| Samsung Electronics               | 14        | 0.47%   |
| ASIX Electronics                  | 14        | 0.47%   |
| Aquantia                          | 14        | 0.47%   |
| Xiaomi                            | 13        | 0.44%   |
| Broadcom Limited                  | 13        | 0.44%   |
| Sierra Wireless                   | 12        | 0.4%    |
| Marvell Technology Group          | 10        | 0.33%   |
| Microsoft                         | 9         | 0.3%    |
| Hewlett-Packard                   | 8         | 0.27%   |
| Google                            | 8         | 0.27%   |
| DisplayLink                       | 8         | 0.27%   |
| Dell                              | 8         | 0.27%   |
| D-Link                            | 8         | 0.27%   |
| Nvidia                            | 4         | 0.13%   |
| Mellanox Technologies             | 4         | 0.13%   |
| Huawei Technologies               | 4         | 0.13%   |
| ASUSTek Computer                  | 4         | 0.13%   |
| OPPO Electronics                  | 3         | 0.1%    |
| Linksys                           | 3         | 0.1%    |
| Fibocom                           | 3         | 0.1%    |
| Ericsson Business Mobile Networks | 3         | 0.1%    |
| Qualcomm Atheros Communications   | 2         | 0.07%   |
| NetGear                           | 2         | 0.07%   |
| Motorola PCS                      | 2         | 0.07%   |
| InterBiometrics                   | 2         | 0.07%   |
| Arduino SA                        | 2         | 0.07%   |
| Apple                             | 2         | 0.07%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.03%   |
| Zoom Telephonics                  | 1         | 0.03%   |
| T & A Mobile Phones               | 1         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 649       | 18.42%  |
| Intel Wi-Fi 6 AX200                                               | 161       | 4.57%   |
| Intel Wi-Fi 6 AX201                                               | 119       | 3.38%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 104       | 2.95%   |
| Intel Wireless 8265 / 8275                                        | 99        | 2.81%   |
| Realtek RTL8125 2.5GbE Controller                                 | 89        | 2.53%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 85        | 2.41%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 78        | 2.21%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 69        | 1.96%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 67        | 1.9%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 54        | 1.53%   |
| Intel I211 Gigabit Network Connection                             | 51        | 1.45%   |
| Intel Ethernet Controller I225-V                                  | 49        | 1.39%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 48        | 1.36%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 48        | 1.36%   |
| Intel Wireless 8260                                               | 43        | 1.22%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 42        | 1.19%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 42        | 1.19%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 41        | 1.16%   |
| Intel Wireless 7265                                               | 41        | 1.16%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 38        | 1.08%   |
| Intel Ethernet Connection (4) I219-LM                             | 37        | 1.05%   |
| Intel Ethernet Connection (2) I219-V                              | 37        | 1.05%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 36        | 1.02%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 35        | 0.99%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 35        | 0.99%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 29        | 0.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 28        | 0.79%   |
| Intel Wireless 7260                                               | 28        | 0.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 27        | 0.77%   |
| Intel Wireless-AC 9260                                            | 25        | 0.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 22        | 0.62%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 21        | 0.6%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 20        | 0.57%   |
| Intel Ethernet Connection I219-LM                                 | 20        | 0.57%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 19        | 0.54%   |
| Intel Ethernet Connection (2) I219-LM                             | 18        | 0.51%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 17        | 0.48%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 17        | 0.48%   |
| Intel Ethernet Connection (7) I219-V                              | 17        | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1015      | 56.93%  |
| Realtek Semiconductor                 | 269       | 15.09%  |
| Qualcomm Atheros                      | 155       | 8.69%   |
| MediaTek                              | 134       | 7.52%   |
| Broadcom                              | 61        | 3.42%   |
| TP-Link                               | 29        | 1.63%   |
| Ralink Technology                     | 16        | 0.9%    |
| Qualcomm                              | 16        | 0.9%    |
| Ralink                                | 15        | 0.84%   |
| Broadcom Limited                      | 13        | 0.73%   |
| Sierra Wireless                       | 12        | 0.67%   |
| Microsoft                             | 8         | 0.45%   |
| Dell                                  | 7         | 0.39%   |
| Marvell Technology Group              | 5         | 0.28%   |
| D-Link                                | 5         | 0.28%   |
| Hewlett-Packard                       | 4         | 0.22%   |
| ASUSTek Computer                      | 4         | 0.22%   |
| Fibocom                               | 3         | 0.17%   |
| Qualcomm Atheros Communications       | 2         | 0.11%   |
| NetGear                               | 2         | 0.11%   |
| Linksys                               | 2         | 0.11%   |
| NEC Computers                         | 1         | 0.06%   |
| IMC Networks                          | 1         | 0.06%   |
| Ericsson Business Mobile Networks     | 1         | 0.06%   |
| D-Link System                         | 1         | 0.06%   |
| AboCom Systems                        | 1         | 0.06%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 161       | 9.01%   |
| Intel Wi-Fi 6 AX201                                            | 119       | 6.66%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 104       | 5.82%   |
| Intel Wireless 8265 / 8275                                     | 99        | 5.54%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 78        | 4.37%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 69        | 3.86%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 54        | 3.02%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 48        | 2.69%   |
| Intel Wireless 8260                                            | 43        | 2.41%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 42        | 2.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 41        | 2.3%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 41        | 2.3%    |
| Intel Wireless 7265                                            | 41        | 2.3%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 38        | 2.13%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 36        | 2.02%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 35        | 1.96%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 35        | 1.96%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 29        | 1.62%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 28        | 1.57%   |
| Intel Wireless 7260                                            | 28        | 1.57%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 27        | 1.51%   |
| Intel Wireless-AC 9260                                         | 25        | 1.4%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 22        | 1.23%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 21        | 1.18%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 20        | 1.12%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 19        | 1.06%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 17        | 0.95%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 17        | 0.95%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 16        | 0.9%    |
| Intel Wireless 3165                                            | 15        | 0.84%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 14        | 0.78%   |
| Broadcom BCM43142 802.11b/g/n                                  | 13        | 0.73%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 11        | 0.62%   |
| Intel Centrino Ultimate-N 6300                                 | 11        | 0.62%   |
| Realtek 802.11ac NIC                                           | 10        | 0.56%   |
| Intel Wireless 3160                                            | 10        | 0.56%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 10        | 0.56%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 9         | 0.5%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 9         | 0.5%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 8         | 0.45%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 901       | 54.02%  |
| Intel                                  | 540       | 32.37%  |
| Qualcomm Atheros                       | 49        | 2.94%   |
| Broadcom                               | 41        | 2.46%   |
| Lenovo                                 | 20        | 1.2%    |
| ASIX Electronics                       | 14        | 0.84%   |
| Aquantia                               | 14        | 0.84%   |
| Xiaomi                                 | 13        | 0.78%   |
| Samsung Electronics                    | 13        | 0.78%   |
| Google                                 | 8         | 0.48%   |
| DisplayLink                            | 8         | 0.48%   |
| Qualcomm                               | 5         | 0.3%    |
| Marvell Technology Group               | 5         | 0.3%    |
| Nvidia                                 | 4         | 0.24%   |
| Mellanox Technologies                  | 4         | 0.24%   |
| TP-Link                                | 3         | 0.18%   |
| OPPO Electronics                       | 3         | 0.18%   |
| D-Link                                 | 3         | 0.18%   |
| MediaTek                               | 2         | 0.12%   |
| Huawei Technologies                    | 2         | 0.12%   |
| Apple                                  | 2         | 0.12%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.06%   |
| T & A Mobile Phones                    | 1         | 0.06%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.06%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.06%   |
| National Semiconductor                 | 1         | 0.06%   |
| Motorola PCS                           | 1         | 0.06%   |
| Microsoft                              | 1         | 0.06%   |
| Magic Control Technology               | 1         | 0.06%   |
| Linksys                                | 1         | 0.06%   |
| JMicron Technology                     | 1         | 0.06%   |
| ICS Advent                             | 1         | 0.06%   |
| Hewlett-Packard                        | 1         | 0.06%   |
| American Megatrends                    | 1         | 0.06%   |
| 3Com                                   | 1         | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 649       | 37.82%  |
| Realtek RTL8125 2.5GbE Controller                                   | 89        | 5.19%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 85        | 4.95%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 67        | 3.9%    |
| Intel I211 Gigabit Network Connection                               | 51        | 2.97%   |
| Intel Ethernet Controller I225-V                                    | 49        | 2.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 48        | 2.8%    |
| Intel Ethernet Connection (4) I219-LM                               | 37        | 2.16%   |
| Intel Ethernet Connection (2) I219-V                                | 37        | 2.16%   |
| Intel Ethernet Connection I219-LM                                   | 20        | 1.17%   |
| Intel Ethernet Connection (2) I219-LM                               | 18        | 1.05%   |
| Intel Ethernet Connection (7) I219-V                                | 17        | 0.99%   |
| Intel Ethernet Connection (4) I219-V                                | 17        | 0.99%   |
| Intel Ethernet Connection (10) I219-V                               | 16        | 0.93%   |
| Intel Ethernet Connection I217-LM                                   | 15        | 0.87%   |
| Intel Ethernet Connection (6) I219-V                                | 14        | 0.82%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 13        | 0.76%   |
| Realtek RTL8152 Fast Ethernet Adapter                               | 13        | 0.76%   |
| Intel Ethernet Connection (16) I219-V                               | 13        | 0.76%   |
| ASIX AX88179 Gigabit Ethernet                                       | 13        | 0.76%   |
| Xiaomi Mi/Redmi series (RNDIS)                                      | 12        | 0.7%    |
| Intel Ethernet Connection I218-LM                                   | 12        | 0.7%    |
| Intel Ethernet Connection (7) I219-LM                               | 12        | 0.7%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller           | 11        | 0.64%   |
| Intel Ethernet Connection (6) I219-LM                               | 11        | 0.64%   |
| Intel Ethernet Connection (13) I219-V                               | 11        | 0.64%   |
| Intel 82579V Gigabit Network Connection                             | 10        | 0.58%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                    | 9         | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 9         | 0.52%   |
| Intel Ethernet Connection (3) I218-LM                               | 9         | 0.52%   |
| Intel 82574L Gigabit Network Connection                             | 9         | 0.52%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 9         | 0.52%   |
| Lenovo ThinkPad TBT 3 Dock                                          | 8         | 0.47%   |
| Intel Ethernet Connection I217-V                                    | 8         | 0.47%   |
| Intel Ethernet Connection (2) I218-V                                | 8         | 0.47%   |
| Realtek Killer E3000 2.5GbE Controller                              | 7         | 0.41%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller           | 7         | 0.41%   |
| Intel I210 Gigabit Network Connection                               | 6         | 0.35%   |
| Intel Ethernet Connection I219-V                                    | 6         | 0.35%   |
| Intel Ethernet Connection (11) I219-V                               | 6         | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1704      | 52.3%   |
| Ethernet | 1532      | 47.02%  |
| Modem    | 17        | 0.52%   |
| Unknown  | 5         | 0.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1389      | 64.73%  |
| Ethernet | 757       | 35.27%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1032      | 50.17%  |
| 1     | 914       | 44.43%  |
| 3     | 63        | 3.06%   |
| 0     | 33        | 1.6%    |
| 4     | 11        | 0.53%   |
| 5     | 2         | 0.1%    |
| 9     | 1         | 0.05%   |
| 8     | 1         | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1510      | 72.98%  |
| Yes  | 559       | 27.02%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 908       | 57.8%   |
| Realtek Semiconductor           | 166       | 10.57%  |
| Foxconn / Hon Hai               | 73        | 4.65%   |
| Qualcomm Atheros Communications | 72        | 4.58%   |
| IMC Networks                    | 65        | 4.14%   |
| Cambridge Silicon Radio         | 63        | 4.01%   |
| Lite-On Technology              | 42        | 2.67%   |
| Broadcom                        | 38        | 2.42%   |
| MediaTek                        | 28        | 1.78%   |
| Apple                           | 26        | 1.65%   |
| Realtek                         | 19        | 1.21%   |
| TP-Link                         | 15        | 0.95%   |
| ASUSTek Computer                | 11        | 0.7%    |
| Toshiba                         | 5         | 0.32%   |
| Marvell Semiconductor           | 5         | 0.32%   |
| Dell                            | 5         | 0.32%   |
| USI                             | 4         | 0.25%   |
| Opticis                         | 4         | 0.25%   |
| Hewlett-Packard                 | 4         | 0.25%   |
| Belkin Components               | 3         | 0.19%   |
| Ralink                          | 2         | 0.13%   |
| Integrated System Solution      | 2         | 0.13%   |
| HTC (High Tech Computer)        | 2         | 0.13%   |
| Edimax Technology               | 2         | 0.13%   |
| Smart Modular Technologies      | 1         | 0.06%   |
| SINO WEALTH                     | 1         | 0.06%   |
| Foxconn International           | 1         | 0.06%   |
| Dynex                           | 1         | 0.06%   |
| Corsair                         | 1         | 0.06%   |
| Chicony Electronics             | 1         | 0.06%   |
| Alps Electric                   | 1         | 0.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                              | 307       | 19.52%  |
| Intel Bluetooth wireless interface                  | 208       | 13.22%  |
| Intel AX200 Bluetooth                               | 155       | 9.85%   |
| Realtek Bluetooth Radio                             | 135       | 8.58%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 128       | 8.14%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 63        | 4.01%   |
| Intel AX210 Bluetooth                               | 53        | 3.37%   |
| Qualcomm Atheros  Bluetooth Device                  | 46        | 2.92%   |
| IMC Networks Wireless_Device                        | 34        | 2.16%   |
| MediaTek Wireless_Device                            | 28        | 1.78%   |
| Intel Wireless-AC 3168 Bluetooth                    | 26        | 1.65%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 26        | 1.65%   |
| Realtek  Bluetooth 4.2 Adapter                      | 22        | 1.4%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 21        | 1.34%   |
| Foxconn / Hon Hai Wireless_Device                   | 21        | 1.34%   |
| Realtek Bluetooth Radio                             | 19        | 1.21%   |
| IMC Networks Bluetooth Radio                        | 17        | 1.08%   |
| TP-Link UB500 Adapter                               | 15        | 0.95%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 14        | 0.89%   |
| Lite-On Bluetooth Device                            | 13        | 0.83%   |
| Foxconn / Hon Hai Bluetooth Device                  | 13        | 0.83%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 12        | 0.76%   |
| Apple Bluetooth Host Controller                     | 12        | 0.76%   |
| Apple Bluetooth USB Host Controller                 | 11        | 0.7%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 10        | 0.64%   |
| Lite-On Wireless_Device                             | 9         | 0.57%   |
| IMC Networks Bluetooth Device                       | 9         | 0.57%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 8         | 0.51%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 6         | 0.38%   |
| ASUS Bluetooth Device                               | 6         | 0.38%   |
| Marvell Bluetooth and Wireless LAN Composite        | 5         | 0.32%   |
| Foxconn / Hon Hai MediaTek MT7921 Bluetooth         | 5         | 0.32%   |
| USI Bluetooth Device                                | 4         | 0.25%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 4         | 0.25%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 4         | 0.25%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 4         | 0.25%   |
| Opticis Bluetooth Radio                             | 4         | 0.25%   |
| Lite-On Bluetooth Radio                             | 4         | 0.25%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 4         | 0.25%   |
| Realtek RTL8821A Bluetooth                          | 3         | 0.19%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1365      | 45.39%  |
| AMD                                  | 715       | 23.78%  |
| Nvidia                               | 483       | 16.06%  |
| C-Media Electronics                  | 51        | 1.7%    |
| Logitech                             | 37        | 1.23%   |
| Lenovo                               | 22        | 0.73%   |
| GN Netcom                            | 19        | 0.63%   |
| Razer USA                            | 17        | 0.57%   |
| JMTek                                | 17        | 0.57%   |
| ASUSTek Computer                     | 17        | 0.57%   |
| Realtek Semiconductor                | 16        | 0.53%   |
| Creative Labs                        | 16        | 0.53%   |
| Kingston Technology                  | 15        | 0.5%    |
| Plantronics                          | 12        | 0.4%    |
| SteelSeries ApS                      | 11        | 0.37%   |
| Generalplus Technology               | 11        | 0.37%   |
| Focusrite-Novation                   | 11        | 0.37%   |
| Corsair                              | 10        | 0.33%   |
| Texas Instruments                    | 8         | 0.27%   |
| Hewlett-Packard                      | 8         | 0.27%   |
| Dell                                 | 7         | 0.23%   |
| Creative Technology                  | 7         | 0.23%   |
| Samson Technologies                  | 6         | 0.2%    |
| RODE Microphones                     | 5         | 0.17%   |
| Blue Microphones                     | 5         | 0.17%   |
| VIA Technologies                     | 4         | 0.13%   |
| Sony                                 | 4         | 0.13%   |
| Samsung Electronics                  | 4         | 0.13%   |
| Micro Star International             | 4         | 0.13%   |
| M-Audio                              | 4         | 0.13%   |
| Huawei Technologies                  | 4         | 0.13%   |
| XMOS                                 | 3         | 0.1%    |
| Thesycon Systemsoftware & Consulting | 3         | 0.1%    |
| Giga-Byte Technology                 | 3         | 0.1%    |
| FiiO Electronics Technology          | 3         | 0.1%    |
| FDUCE PRO AUDIO MADE                 | 3         | 0.1%    |
| Cambridge Silicon Radio              | 3         | 0.1%    |
| Asahi Kasei Microsystems             | 3         | 0.1%    |
| Apple                                | 3         | 0.1%    |
| Yamaha                               | 2         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 390       | 10.7%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 248       | 6.81%   |
| Intel Sunrise Point-LP HD Audio                                            | 207       | 5.68%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 142       | 3.9%    |
| AMD Starship/Matisse HD Audio Controller                                   | 127       | 3.49%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 126       | 3.46%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 91        | 2.5%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 90        | 2.47%   |
| Intel Cannon Lake PCH cAVS                                                 | 77        | 2.11%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 69        | 1.89%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 68        | 1.87%   |
| Intel Comet Lake PCH-LP cAVS                                               | 62        | 1.7%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 60        | 1.65%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 59        | 1.62%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 54        | 1.48%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 53        | 1.45%   |
| Intel Comet Lake PCH cAVS                                                  | 51        | 1.4%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 51        | 1.4%    |
| Nvidia GA106 High Definition Audio Controller                              | 47        | 1.29%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 42        | 1.15%   |
| Nvidia GP107GL High Definition Audio Controller                            | 41        | 1.13%   |
| Intel 200 Series PCH HD Audio                                              | 37        | 1.02%   |
| Nvidia TU106 High Definition Audio Controller                              | 34        | 0.93%   |
| Nvidia GA104 High Definition Audio Controller                              | 34        | 0.93%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 34        | 0.93%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 32        | 0.88%   |
| Intel Alder Lake-S HD Audio Controller                                     | 32        | 0.88%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 31        | 0.85%   |
| Intel Broadwell-U Audio Controller                                         | 31        | 0.85%   |
| Nvidia Audio device                                                        | 29        | 0.8%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 28        | 0.77%   |
| Nvidia GP106 High Definition Audio Controller                              | 27        | 0.74%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 25        | 0.69%   |
| Intel Haswell-ULT HD Audio Controller                                      | 25        | 0.69%   |
| Intel 8 Series HD Audio Controller                                         | 25        | 0.69%   |
| AMD FCH Azalia Controller                                                  | 24        | 0.66%   |
| Intel CM238 HD Audio Controller                                            | 23        | 0.63%   |
| Nvidia TU116 High Definition Audio Controller                              | 22        | 0.6%    |
| Nvidia GP104 High Definition Audio Controller                              | 22        | 0.6%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 22        | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 310       | 24.68%  |
| SK hynix            | 232       | 18.47%  |
| Micron Technology   | 162       | 12.9%   |
| Kingston            | 112       | 8.92%   |
| Crucial             | 76        | 6.05%   |
| Corsair             | 64        | 5.1%    |
| G.Skill             | 60        | 4.78%   |
| Unknown             | 59        | 4.7%    |
| A-DATA Technology   | 32        | 2.55%   |
| Ramaxel Technology  | 21        | 1.67%   |
| Team                | 15        | 1.19%   |
| Unknown             | 12        | 0.96%   |
| Patriot             | 10        | 0.8%    |
| Smart               | 9         | 0.72%   |
| Elpida              | 9         | 0.72%   |
| Unknown (ABCD)      | 6         | 0.48%   |
| Nanya Technology    | 6         | 0.48%   |
| Transcend           | 5         | 0.4%    |
| AMD                 | 4         | 0.32%   |
| PNY                 | 3         | 0.24%   |
| GeIL                | 3         | 0.24%   |
| Avant               | 3         | 0.24%   |
| Apacer              | 3         | 0.24%   |
| Unifosa             | 2         | 0.16%   |
| Smart Brazil        | 2         | 0.16%   |
| Silicon Power       | 2         | 0.16%   |
| PUSKILL             | 2         | 0.16%   |
| Hewlett-Packard     | 2         | 0.16%   |
| GOODRAM             | 2         | 0.16%   |
| Goldkey             | 2         | 0.16%   |
| Gold Key            | 2         | 0.16%   |
| Wodposit            | 1         | 0.08%   |
| Wilk                | 1         | 0.08%   |
| V-Color             | 1         | 0.08%   |
| Unknown (F288)      | 1         | 0.08%   |
| Unknown (0x0C97)    | 1         | 0.08%   |
| Unknown (0x0B5E)    | 1         | 0.08%   |
| Unknown (08C8)      | 1         | 0.08%   |
| Timetec             | 1         | 0.08%   |
| Teikon              | 1         | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 18        | 1.36%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 15        | 1.13%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 15        | 1.13%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 15        | 1.13%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 13        | 0.98%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 13        | 0.98%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 13        | 0.98%   |
| Unknown                                                          | 12        | 0.9%    |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 11        | 0.83%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 10        | 0.75%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 9         | 0.68%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 9         | 0.68%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 7         | 0.53%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 7         | 0.53%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 7         | 0.53%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 6         | 0.45%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 6         | 0.45%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 6         | 0.45%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 6         | 0.45%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s           | 6         | 0.45%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 6         | 0.45%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 6         | 0.45%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 6         | 0.45%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s              | 6         | 0.45%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s            | 6         | 0.45%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 5         | 0.38%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s        | 5         | 0.38%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 5         | 0.38%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 5         | 0.38%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 5         | 0.38%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 5         | 0.38%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 5         | 0.38%   |
| Samsung RAM K3LKBKB@BM-MGCP 8GB Row Of Chips LPDDR5 6400MT/s     | 5         | 0.38%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 5         | 0.38%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 5         | 0.38%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s           | 5         | 0.38%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s             | 5         | 0.38%   |
| A-DATA RAM Module 16GB SODIMM DDR4 3200MT/s                      | 5         | 0.38%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 4         | 0.3%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 4         | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind            | Computers | Percent |
|-----------------|-----------|---------|
| DDR4            | 665       | 61.52%  |
| DDR3            | 178       | 16.47%  |
| LPDDR4          | 61        | 5.64%   |
| DDR5            | 54        | 5%      |
| LPDDR5          | 47        | 4.35%   |
| LPDDR3          | 39        | 3.61%   |
| DDR2            | 23        | 2.13%   |
| Unknown         | 7         | 0.65%   |
| SDRAM           | 5         | 0.46%   |
| Logical non-vol | 1         | 0.09%   |
| DDR             | 1         | 0.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 621       | 56.82%  |
| DIMM         | 279       | 25.53%  |
| Row Of Chips | 178       | 16.29%  |
| Unknown      | 8         | 0.73%   |
| Chip         | 4         | 0.37%   |
| FB-DIMM      | 2         | 0.18%   |
| RIMM         | 1         | 0.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size   | Computers | Percent |
|--------|-----------|---------|
| 8192   | 537       | 46.41%  |
| 16384  | 241       | 20.83%  |
| 4096   | 207       | 17.89%  |
| 2048   | 86        | 7.43%   |
| 32768  | 74        | 6.4%    |
| 1024   | 10        | 0.86%   |
| 129408 | 1         | 0.09%   |
| 12288  | 1         | 0.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 344       | 29.76%  |
| 2667    | 181       | 15.66%  |
| 1600    | 117       | 10.12%  |
| 2400    | 62        | 5.36%   |
| 2133    | 59        | 5.1%    |
| 6400    | 47        | 4.07%   |
| 1333    | 39        | 3.37%   |
| 4800    | 36        | 3.11%   |
| 4267    | 30        | 2.6%    |
| 3600    | 29        | 2.51%   |
| 1867    | 26        | 2.25%   |
| 3733    | 16        | 1.38%   |
| 800     | 13        | 1.12%   |
| 4266    | 11        | 0.95%   |
| 667     | 9         | 0.78%   |
| 3866    | 8         | 0.69%   |
| 3266    | 8         | 0.69%   |
| 2666    | 7         | 0.61%   |
| 1800    | 7         | 0.61%   |
| 5200    | 6         | 0.52%   |
| 3533    | 6         | 0.52%   |
| 3466    | 6         | 0.52%   |
| 3000    | 6         | 0.52%   |
| 1866    | 6         | 0.52%   |
| 1334    | 6         | 0.52%   |
| 8400    | 5         | 0.43%   |
| 3400    | 5         | 0.43%   |
| 2933    | 5         | 0.43%   |
| 6000    | 4         | 0.35%   |
| 5600    | 4         | 0.35%   |
| 3800    | 4         | 0.35%   |
| 1066    | 4         | 0.35%   |
| 533     | 4         | 0.35%   |
| 3666    | 3         | 0.26%   |
| Unknown | 3         | 0.26%   |
| 3100    | 2         | 0.17%   |
| 2800    | 2         | 0.17%   |
| 1067    | 2         | 0.17%   |
| 400     | 2         | 0.17%   |
| 333     | 2         | 0.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 8         | 26.67%  |
| Brother Industries    | 8         | 26.67%  |
| Seiko Epson           | 4         | 13.33%  |
| Samsung Electronics   | 4         | 13.33%  |
| Canon                 | 2         | 6.67%   |
| Sato                  | 1         | 3.33%   |
| Prolific Technology   | 1         | 3.33%   |
| MiiiW                 | 1         | 3.33%   |
| Lexmark International | 1         | 3.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Seiko Epson WP-4020 Series    | 1         | 3.33%   |
| Seiko Epson WF-2860 Series    | 1         | 3.33%   |
| Seiko Epson Printer           | 1         | 3.33%   |
| Seiko Epson L300 Series       | 1         | 3.33%   |
| Sato WS408 SBPL               | 1         | 3.33%   |
| Samsung SCX-4623 Series       | 1         | 3.33%   |
| Samsung SCX-4300 Series       | 1         | 3.33%   |
| Samsung ML-2855 Series        | 1         | 3.33%   |
| Samsung M2070 Series          | 1         | 3.33%   |
| Prolific PL2305 Parallel Port | 1         | 3.33%   |
| MiiiW MW USB Receiver         | 1         | 3.33%   |
| Lexmark International B2236dw | 1         | 3.33%   |
| HP Officejet 2620 series      | 1         | 3.33%   |
| HP LaserJet P2055 series      | 1         | 3.33%   |
| HP LaserJet 1012              | 1         | 3.33%   |
| HP LaserJet 1010              | 1         | 3.33%   |
| HP ENVY Photo 7800 series     | 1         | 3.33%   |
| HP DeskJet F300 series        | 1         | 3.33%   |
| HP DeskJet 5650c              | 1         | 3.33%   |
| HP DeskJet 3630 series        | 1         | 3.33%   |
| Canon TS5100 series           | 1         | 3.33%   |
| Canon LiDE 400                | 1         | 3.33%   |
| Brother MFC-7460DN            | 1         | 3.33%   |
| Brother HL-L2350DW series     | 1         | 3.33%   |
| Brother HL-L2320D series      | 1         | 3.33%   |
| Brother HL-L2300D series      | 1         | 3.33%   |
| Brother HL-2030 Laser Printer | 1         | 3.33%   |
| Brother DCP-L2510D series     | 1         | 3.33%   |
| Brother DCP-7025 Printer      | 1         | 3.33%   |
| Brother DCP-1600              | 1         | 3.33%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 5         | 55.56%  |
| Canon       | 4         | 44.44%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Seiko Epson GT-X770 [Perfection V500]                    | 2         | 22.22%  |
| Seiko Epson GT-6600U [Perfection 610]                    | 2         | 22.22%  |
| Canon CanoScan N670U/N676U/LiDE 20                       | 2         | 22.22%  |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1         | 11.11%  |
| Canon CanoScan LiDE 210                                  | 1         | 11.11%  |
| Canon CanoScan LiDE 100                                  | 1         | 11.11%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 319       | 22%     |
| IMC Networks                           | 182       | 12.55%  |
| Microdia                               | 132       | 9.1%    |
| Logitech                               | 111       | 7.66%   |
| Bison Electronics                      | 109       | 7.52%   |
| Quanta                                 | 107       | 7.38%   |
| Realtek Semiconductor                  | 73        | 5.03%   |
| Sunplus Innovation Technology          | 61        | 4.21%   |
| Cheng Uei Precision Industry (Foxlink) | 44        | 3.03%   |
| Syntek                                 | 40        | 2.76%   |
| Luxvisions Innotech Limited            | 40        | 2.76%   |
| Lite-On Technology                     | 27        | 1.86%   |
| Apple                                  | 25        | 1.72%   |
| Sonix Technology                       | 22        | 1.52%   |
| Microsoft                              | 18        | 1.24%   |
| Silicon Motion                         | 13        | 0.9%    |
| Samsung Electronics                    | 10        | 0.69%   |
| Suyin                                  | 9         | 0.62%   |
| SunplusIT                              | 8         | 0.55%   |
| Acer                                   | 8         | 0.55%   |
| KYE Systems (Mouse Systems)            | 5         | 0.34%   |
| AVerMedia Technologies                 | 5         | 0.34%   |
| Alcor Micro                            | 5         | 0.34%   |
| Tripath Technology                     | 4         | 0.28%   |
| MacroSilicon                           | 4         | 0.28%   |
| WaveRider Communications               | 3         | 0.21%   |
| Primax Electronics                     | 3         | 0.21%   |
| LG Electronics                         | 3         | 0.21%   |
| Generalplus Technology                 | 3         | 0.21%   |
| Creality 3D Technology                 | 3         | 0.21%   |
| ARC International                      | 3         | 0.21%   |
| 8SSC21D67422V1SR28902JL                | 3         | 0.21%   |
| Trust                                  | 2         | 0.14%   |
| Shenzhen Kingcome Optoelectronic       | 2         | 0.14%   |
| Ricoh                                  | 2         | 0.14%   |
| Lenovo                                 | 2         | 0.14%   |
| kingcome                               | 2         | 0.14%   |
| Importek                               | 2         | 0.14%   |
| icSpring                               | 2         | 0.14%   |
| Hewlett-Packard                        | 2         | 0.14%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 110       | 7.53%   |
| Microdia Integrated_Webcam_HD                    | 68        | 4.65%   |
| IMC Networks Integrated Camera                   | 61        | 4.18%   |
| IMC Networks USB2.0 HD UVC WebCam                | 59        | 4.04%   |
| Bison Integrated Camera                          | 45        | 3.08%   |
| Realtek Integrated_Webcam_HD                     | 41        | 2.81%   |
| Syntek Integrated Camera                         | 28        | 1.92%   |
| Sunplus Integrated_Webcam_HD                     | 24        | 1.64%   |
| Chicony HD Webcam                                | 23        | 1.57%   |
| Quanta HD User Facing                            | 22        | 1.51%   |
| Logitech HD Pro Webcam C920                      | 19        | 1.3%    |
| IMC Networks HD Camera                           | 19        | 1.3%    |
| Quanta HP Wide Vision HD Camera                  | 17        | 1.16%   |
| Microdia Integrated_Webcam_FHD                   | 17        | 1.16%   |
| Logitech Webcam C270                             | 17        | 1.16%   |
| Quanta HP HD Camera                              | 15        | 1.03%   |
| Chicony HP Wide Vision HD Camera                 | 15        | 1.03%   |
| Chicony Integrated Camera (1280x720@30)          | 14        | 0.96%   |
| Sonix USB2.0 HD UVC WebCam                       | 13        | 0.89%   |
| Logitech C922 Pro Stream Webcam                  | 12        | 0.82%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 12        | 0.82%   |
| Chicony USB2.0 Camera                            | 12        | 0.82%   |
| Chicony Integrated IR Camera                     | 12        | 0.82%   |
| Chicony HP TrueVision HD Camera                  | 12        | 0.82%   |
| Lite-On Integrated Camera                        | 11        | 0.75%   |
| Chicony HP HD Camera                             | 11        | 0.75%   |
| Bison SunplusIT Integrated Camera                | 11        | 0.75%   |
| Samsung Galaxy series, misc. (MTP mode)          | 10        | 0.68%   |
| Luxvisions Innotech Limited Integrated Camera    | 10        | 0.68%   |
| Apple iPhone 5/5C/5S/6/SE                        | 10        | 0.68%   |
| Quanta HP TrueVision HD Camera                   | 9         | 0.62%   |
| Microdia Webcam Vitade AF                        | 9         | 0.62%   |
| Logitech HD Webcam C525                          | 9         | 0.62%   |
| Lite-On HP HD Camera                             | 9         | 0.62%   |
| IMC Networks ov9734_azurewave_camera             | 9         | 0.62%   |
| Chicony USB2.0 VGA UVC WebCam                    | 9         | 0.62%   |
| Chicony HD User Facing                           | 9         | 0.62%   |
| Chicony EasyCamera                               | 9         | 0.62%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera | 9         | 0.62%   |
| Bison HD Webcam                                  | 9         | 0.62%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 140       | 41.3%   |
| Shenzhen Goodix Technology         | 82        | 24.19%  |
| Validity Sensors                   | 70        | 20.65%  |
| Elan Microelectronics              | 22        | 6.49%   |
| LighTuning Technology              | 8         | 2.36%   |
| AuthenTec                          | 6         | 1.77%   |
| Realtek USB2.0 Finger Print Bridge | 4         | 1.18%   |
| Upek                               | 2         | 0.59%   |
| Samsung Electronics                | 2         | 0.59%   |
| STMicroelectronics                 | 1         | 0.29%   |
| Microsoft                          | 1         | 0.29%   |
| DigitalPersona                     | 1         | 0.29%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 61        | 17.99%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 57        | 16.81%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 20        | 5.9%    |
| Validity Sensors Synaptics WBDI                                            | 15        | 4.42%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 13        | 3.83%   |
| Shenzhen Goodix Fingerprint Reader                                         | 13        | 3.83%   |
| Elan ELAN:ARM-M4                                                           | 13        | 3.83%   |
| Synaptics  WBDI                                                            | 11        | 3.24%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 10        | 2.95%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 10        | 2.95%   |
| Synaptics UWP WBDI                                                         | 9         | 2.65%   |
| Synaptics WBDI                                                             | 8         | 2.36%   |
| Shenzhen Goodix FingerPrint                                                | 8         | 2.36%   |
| Elan ELAN:Fingerprint                                                      | 8         | 2.36%   |
| Synaptics UWP WBDI Device                                                  | 7         | 2.06%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 1.77%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 6         | 1.77%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 6         | 1.77%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 5         | 1.47%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 5         | 1.47%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 4         | 1.18%   |
| Synaptics Fingerprint reader [HP G6]                                       | 4         | 1.18%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 4         | 1.18%   |
| Validity Sensors VFS491                                                    | 3         | 0.88%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 0.88%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 3         | 0.88%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 0.88%   |
| AuthenTec AES1600                                                          | 3         | 0.88%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 0.59%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 0.59%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 2         | 0.59%   |
| LighTuning Fingerprint Sensor                                              | 2         | 0.59%   |
| AuthenTec AES2810                                                          | 2         | 0.59%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.29%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.29%   |
| Synaptics WBDI Device                                                      | 1         | 0.29%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.29%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.29%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 0.29%   |
| Samsung Fingerprint Device                                                 | 1         | 0.29%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Alcor Micro              | 51        | 42.86%  |
| Broadcom                 | 48        | 40.34%  |
| Upek                     | 6         | 5.04%   |
| O2 Micro                 | 3         | 2.52%   |
| Lenovo                   | 3         | 2.52%   |
| Gemalto (was Gemplus)    | 3         | 2.52%   |
| Yubico.com               | 1         | 0.84%   |
| Reiner SCT Kartensysteme | 1         | 0.84%   |
| Realtek Semiconductor    | 1         | 0.84%   |
| Purism, SPC              | 1         | 0.84%   |
| Aktiv                    | 1         | 0.84%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 51        | 42.86%  |
| Broadcom 58200                                                               | 20        | 16.81%  |
| Broadcom 5880                                                                | 19        | 15.97%  |
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 5.88%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 6         | 5.04%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 2.52%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 2.52%   |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 1.68%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 1.68%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.84%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.84%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.84%   |
| Purism, SPC Librem Key                                                       | 1         | 0.84%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 0.84%   |
| Aktiv Rutoken lite                                                           | 1         | 0.84%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1377      | 66.23%  |
| 1     | 585       | 28.14%  |
| 2     | 86        | 4.14%   |
| 3     | 13        | 0.63%   |
| 4     | 8         | 0.38%   |
| 5     | 5         | 0.24%   |
| 7     | 4         | 0.19%   |
| 8     | 1         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 335       | 39.79%  |
| Graphics card            | 200       | 23.75%  |
| Multimedia controller    | 90        | 10.69%  |
| Net/wireless             | 62        | 7.36%   |
| Camera                   | 37        | 4.39%   |
| Chipcard                 | 24        | 2.85%   |
| Sound                    | 22        | 2.61%   |
| Communication controller | 16        | 1.9%    |
| Unassigned class         | 13        | 1.54%   |
| Card reader              | 13        | 1.54%   |
| Bluetooth                | 12        | 1.43%   |
| Net/ethernet             | 6         | 0.71%   |
| Network                  | 4         | 0.48%   |
| Storage/raid             | 3         | 0.36%   |
| Storage                  | 3         | 0.36%   |
| Modem                    | 1         | 0.12%   |
| Firewire controller      | 1         | 0.12%   |

