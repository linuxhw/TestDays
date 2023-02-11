Linux in Denmark - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Denmark.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Denmark/Desktop/README.md) and [notebooks](/Location/Denmark/Notebook/README.md).

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

Total: 1174

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [ab57658c86](https://linux-hardware.org/?probe=ab57658c86) | Jan 31, 2023 |
| Lenovo        | ThinkPad L380 20M5S09Y00    | Notebook    | [2326ffc032](https://linux-hardware.org/?probe=2326ffc032) | Jan 31, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [ef9c1299e6](https://linux-hardware.org/?probe=ef9c1299e6) | Jan 30, 2023 |
| HP            | Laptop 14-bp0xx             | Notebook    | [68d8a60823](https://linux-hardware.org/?probe=68d8a60823) | Jan 27, 2023 |
| Standard      | Unknown                     | Notebook    | [d9a5e68741](https://linux-hardware.org/?probe=d9a5e68741) | Jan 25, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [78b817b650](https://linux-hardware.org/?probe=78b817b650) | Jan 24, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [f9882955cb](https://linux-hardware.org/?probe=f9882955cb) | Jan 24, 2023 |
| Lenovo        | ThinkPad W541 20EF0020MD    | Notebook    | [fca73ad2a9](https://linux-hardware.org/?probe=fca73ad2a9) | Jan 24, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [96a5ca6b92](https://linux-hardware.org/?probe=96a5ca6b92) | Jan 23, 2023 |
| System76      | Darter UltraThin            | Notebook    | [47f56a1f2d](https://linux-hardware.org/?probe=47f56a1f2d) | Jan 23, 2023 |
| Google        | Phaser                      | Notebook    | [557e69c5f1](https://linux-hardware.org/?probe=557e69c5f1) | Jan 21, 2023 |
| Lenovo        | ThinkPad X230 2325AS7       | Notebook    | [71a521018d](https://linux-hardware.org/?probe=71a521018d) | Jan 19, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [4f24524e7d](https://linux-hardware.org/?probe=4f24524e7d) | Jan 19, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [a7ac9067b0](https://linux-hardware.org/?probe=a7ac9067b0) | Jan 18, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [fd99b07929](https://linux-hardware.org/?probe=fd99b07929) | Jan 18, 2023 |
| ASUSTek       | S301LA                      | Notebook    | [c45b4758ed](https://linux-hardware.org/?probe=c45b4758ed) | Jan 18, 2023 |
| Lenovo        | 32E9 SDK0T76461 WIN 3422... | Desktop     | [5480333c5b](https://linux-hardware.org/?probe=5480333c5b) | Jan 16, 2023 |
| Lenovo        | G505 20240                  | Notebook    | [ef2fdd351c](https://linux-hardware.org/?probe=ef2fdd351c) | Jan 16, 2023 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | Notebook    | [138f888e23](https://linux-hardware.org/?probe=138f888e23) | Jan 15, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [286de51ef8](https://linux-hardware.org/?probe=286de51ef8) | Jan 13, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [8a79dd9e27](https://linux-hardware.org/?probe=8a79dd9e27) | Jan 13, 2023 |
| ASUSTek       | ROG STRIX X370-F GAMING     | Desktop     | [fcda893618](https://linux-hardware.org/?probe=fcda893618) | Jan 13, 2023 |
| Acer          | Aspire 5810T                | Notebook    | [a39184ad9b](https://linux-hardware.org/?probe=a39184ad9b) | Jan 13, 2023 |
| Acer          | Aspire 5810T                | Notebook    | [ccc420a65a](https://linux-hardware.org/?probe=ccc420a65a) | Jan 13, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [2f95543d62](https://linux-hardware.org/?probe=2f95543d62) | Jan 11, 2023 |
| Lenovo        | 1059 SDK0T76538 WIN 3556... | Desktop     | [a2660dcbfb](https://linux-hardware.org/?probe=a2660dcbfb) | Jan 09, 2023 |
| Acer          | Aspire E5-553               | Notebook    | [e68c76cbee](https://linux-hardware.org/?probe=e68c76cbee) | Jan 07, 2023 |
| Lenovo        | 32E9 SDK0T76461 WIN 3422... | Desktop     | [fcc2d12f0d](https://linux-hardware.org/?probe=fcc2d12f0d) | Jan 06, 2023 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [aae608e132](https://linux-hardware.org/?probe=aae608e132) | Jan 06, 2023 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [7685480bf0](https://linux-hardware.org/?probe=7685480bf0) | Jan 05, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [26826e3c23](https://linux-hardware.org/?probe=26826e3c23) | Jan 04, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [bc17e3a0f4](https://linux-hardware.org/?probe=bc17e3a0f4) | Jan 04, 2023 |
| Medion        | P7621                       | Notebook    | [6ce2ef1abc](https://linux-hardware.org/?probe=6ce2ef1abc) | Jan 03, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [65c34944ec](https://linux-hardware.org/?probe=65c34944ec) | Jan 03, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [df9ca70fa3](https://linux-hardware.org/?probe=df9ca70fa3) | Jan 02, 2023 |
| Gigabyte      | P85-D3                      | Desktop     | [8d017ea6af](https://linux-hardware.org/?probe=8d017ea6af) | Jan 01, 2023 |
| Gigabyte      | P85-D3                      | Desktop     | [aebeaf8b5e](https://linux-hardware.org/?probe=aebeaf8b5e) | Jan 01, 2023 |
| Notebook      | P17SM                       | Notebook    | [18605208b6](https://linux-hardware.org/?probe=18605208b6) | Dec 30, 2022 |
| Apple         | MacBookPro10,2              | Notebook    | [a01c19a34d](https://linux-hardware.org/?probe=a01c19a34d) | Dec 29, 2022 |
| GPD           | WIN2                        | Notebook    | [d7d31b67d0](https://linux-hardware.org/?probe=d7d31b67d0) | Dec 28, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [6a2f859c67](https://linux-hardware.org/?probe=6a2f859c67) | Dec 27, 2022 |
| ASUSTek       | X75A1                       | Notebook    | [5a5ee8db71](https://linux-hardware.org/?probe=5a5ee8db71) | Dec 26, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [196d570869](https://linux-hardware.org/?probe=196d570869) | Dec 26, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [6cc10dd6de](https://linux-hardware.org/?probe=6cc10dd6de) | Dec 25, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [148add29a4](https://linux-hardware.org/?probe=148add29a4) | Dec 24, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [da48bed048](https://linux-hardware.org/?probe=da48bed048) | Dec 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [5c07d82410](https://linux-hardware.org/?probe=5c07d82410) | Dec 23, 2022 |
| MSI           | GP65 Leopard 9SE            | Notebook    | [7b980fbd8f](https://linux-hardware.org/?probe=7b980fbd8f) | Dec 21, 2022 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | Notebook    | [97d8552a67](https://linux-hardware.org/?probe=97d8552a67) | Dec 21, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [c4719bd0ac](https://linux-hardware.org/?probe=c4719bd0ac) | Dec 21, 2022 |
| Medion        | P7621                       | Notebook    | [eced009b2a](https://linux-hardware.org/?probe=eced009b2a) | Dec 20, 2022 |
| Lenovo        | ThinkPad W510 4318CTO       | Notebook    | [215feb2d5e](https://linux-hardware.org/?probe=215feb2d5e) | Dec 20, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [e964534175](https://linux-hardware.org/?probe=e964534175) | Dec 19, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [d367461182](https://linux-hardware.org/?probe=d367461182) | Dec 19, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [95aca2679a](https://linux-hardware.org/?probe=95aca2679a) | Dec 14, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [ea3dbee733](https://linux-hardware.org/?probe=ea3dbee733) | Dec 13, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [441dc6d8a0](https://linux-hardware.org/?probe=441dc6d8a0) | Dec 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [be36edb132](https://linux-hardware.org/?probe=be36edb132) | Dec 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [491b8d0b8f](https://linux-hardware.org/?probe=491b8d0b8f) | Dec 11, 2022 |
| Lenovo        | ThinkPad Z61m 94503HG       | Notebook    | [4131ed9268](https://linux-hardware.org/?probe=4131ed9268) | Dec 11, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | Notebook    | [4686ea3469](https://linux-hardware.org/?probe=4686ea3469) | Dec 11, 2022 |
| Lenovo        | ThinkPad T520 4243W19       | Notebook    | [86064a54c0](https://linux-hardware.org/?probe=86064a54c0) | Dec 10, 2022 |
| Gigabyte      | B650 GAMING X AX            | Desktop     | [2473215632](https://linux-hardware.org/?probe=2473215632) | Dec 10, 2022 |
| ASUSTek       | M80CJ-O                     | Desktop     | [2375dfe19f](https://linux-hardware.org/?probe=2375dfe19f) | Dec 10, 2022 |
| ASUSTek       | PRIME Z690M-PLUS D4         | Desktop     | [7abcfecd34](https://linux-hardware.org/?probe=7abcfecd34) | Dec 07, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [e5291ae74e](https://linux-hardware.org/?probe=e5291ae74e) | Dec 06, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [a4bdd8b19d](https://linux-hardware.org/?probe=a4bdd8b19d) | Dec 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [7a802a74b7](https://linux-hardware.org/?probe=7a802a74b7) | Dec 04, 2022 |
| Intel         | NUC7i5BNB J31144-304        | Mini pc     | [cc6834a359](https://linux-hardware.org/?probe=cc6834a359) | Dec 04, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [ef7a013f9b](https://linux-hardware.org/?probe=ef7a013f9b) | Dec 04, 2022 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | Desktop     | [6b2389329d](https://linux-hardware.org/?probe=6b2389329d) | Dec 04, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [8de52c0ea7](https://linux-hardware.org/?probe=8de52c0ea7) | Dec 04, 2022 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [366f9ae2aa](https://linux-hardware.org/?probe=366f9ae2aa) | Dec 03, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [dddc2b5f29](https://linux-hardware.org/?probe=dddc2b5f29) | Dec 03, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [50c8de6edf](https://linux-hardware.org/?probe=50c8de6edf) | Dec 02, 2022 |
| Standard      | Unknown                     | Notebook    | [43891b2653](https://linux-hardware.org/?probe=43891b2653) | Dec 02, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [c469225241](https://linux-hardware.org/?probe=c469225241) | Dec 01, 2022 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [9282404406](https://linux-hardware.org/?probe=9282404406) | Nov 30, 2022 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | Notebook    | [687d4d78a4](https://linux-hardware.org/?probe=687d4d78a4) | Nov 29, 2022 |
| Dell          | Inspiron 15 3520            | Notebook    | [7c53fcc73b](https://linux-hardware.org/?probe=7c53fcc73b) | Nov 24, 2022 |
| Lenovo        | ThinkPad X250 20CLS21F00    | Notebook    | [dee6d2a740](https://linux-hardware.org/?probe=dee6d2a740) | Nov 23, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [ec837e35d6](https://linux-hardware.org/?probe=ec837e35d6) | Nov 22, 2022 |
| ASUSTek       | PRIME TRX40-PRO             | Desktop     | [ecafbb7acb](https://linux-hardware.org/?probe=ecafbb7acb) | Nov 20, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [9b0f3f926d](https://linux-hardware.org/?probe=9b0f3f926d) | Nov 20, 2022 |
| Lenovo        | ThinkPad T460 20FN004CMD    | Notebook    | [1b7140151d](https://linux-hardware.org/?probe=1b7140151d) | Nov 20, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [1cc37489d5](https://linux-hardware.org/?probe=1cc37489d5) | Nov 19, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [ea05374336](https://linux-hardware.org/?probe=ea05374336) | Nov 19, 2022 |
| Acer          | Aspire 5810T                | Notebook    | [2c671f2494](https://linux-hardware.org/?probe=2c671f2494) | Nov 18, 2022 |
| Timi          | TM1607                      | Notebook    | [a93d1611bb](https://linux-hardware.org/?probe=a93d1611bb) | Nov 18, 2022 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [de3eac26e1](https://linux-hardware.org/?probe=de3eac26e1) | Nov 18, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [7352c1f1ed](https://linux-hardware.org/?probe=7352c1f1ed) | Nov 17, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [07b8a83017](https://linux-hardware.org/?probe=07b8a83017) | Nov 17, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [e4401c7591](https://linux-hardware.org/?probe=e4401c7591) | Nov 17, 2022 |
| HP            | Pavilion 15                 | Notebook    | [fbef42d1dc](https://linux-hardware.org/?probe=fbef42d1dc) | Nov 16, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [6af7c2ad85](https://linux-hardware.org/?probe=6af7c2ad85) | Nov 15, 2022 |
| Acer          | Aspire E5-553               | Notebook    | [4c031f5f3b](https://linux-hardware.org/?probe=4c031f5f3b) | Nov 15, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [a35952fc68](https://linux-hardware.org/?probe=a35952fc68) | Nov 14, 2022 |
| Lenovo        | 3135 SDK0J40697 WIN 3305... | Mini pc     | [48916ecbfa](https://linux-hardware.org/?probe=48916ecbfa) | Nov 14, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | Notebook    | [270045ffa3](https://linux-hardware.org/?probe=270045ffa3) | Nov 11, 2022 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [75ffcfaf88](https://linux-hardware.org/?probe=75ffcfaf88) | Nov 11, 2022 |
| Komplett      | LAPQC71B                    | Notebook    | [b5ee8960c6](https://linux-hardware.org/?probe=b5ee8960c6) | Nov 11, 2022 |
| Lenovo        | Yoga 720-13IKB 80X6         | Convertible | [38763f3628](https://linux-hardware.org/?probe=38763f3628) | Nov 11, 2022 |
| MSI           | GV62 8RC                    | Notebook    | [859227b2bb](https://linux-hardware.org/?probe=859227b2bb) | Nov 10, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [7afd10a1a7](https://linux-hardware.org/?probe=7afd10a1a7) | Nov 09, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [a62bf9ed3b](https://linux-hardware.org/?probe=a62bf9ed3b) | Nov 08, 2022 |
| HP            | Notebook                    | Notebook    | [0868a7d110](https://linux-hardware.org/?probe=0868a7d110) | Nov 08, 2022 |
| Lenovo        | 3135 SDK0J40697 WIN 3305... | Mini pc     | [de347eb300](https://linux-hardware.org/?probe=de347eb300) | Nov 06, 2022 |
| Lenovo        | ThinkPad T460s 20FAS3CF0... | Notebook    | [2c52a84e7c](https://linux-hardware.org/?probe=2c52a84e7c) | Nov 06, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [9a7d0e6d37](https://linux-hardware.org/?probe=9a7d0e6d37) | Nov 03, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [81a04d40a3](https://linux-hardware.org/?probe=81a04d40a3) | Nov 03, 2022 |
| ASUSTek       | N55SF                       | Notebook    | [02af74ebb6](https://linux-hardware.org/?probe=02af74ebb6) | Nov 02, 2022 |
| Dell          | Latitude 5280               | Notebook    | [368f237efe](https://linux-hardware.org/?probe=368f237efe) | Oct 28, 2022 |
| Unknown       | Unknown                     | Notebook    | [fcffee84e4](https://linux-hardware.org/?probe=fcffee84e4) | Oct 27, 2022 |
| Lenovo        | ThinkPad T470s 20HF0047U... | Notebook    | [3b9a4fb8f4](https://linux-hardware.org/?probe=3b9a4fb8f4) | Oct 26, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [251892471f](https://linux-hardware.org/?probe=251892471f) | Oct 26, 2022 |
| Lenovo        | ThinkPad X260 20F600A4MD    | Notebook    | [50cce404c7](https://linux-hardware.org/?probe=50cce404c7) | Oct 25, 2022 |
| Inventec      | DQ Class A02                | Desktop     | [f64d3223c5](https://linux-hardware.org/?probe=f64d3223c5) | Oct 24, 2022 |
| Inventec      | DQ Class A02                | Desktop     | [c4fddde4b6](https://linux-hardware.org/?probe=c4fddde4b6) | Oct 24, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | Notebook    | [e21d202e50](https://linux-hardware.org/?probe=e21d202e50) | Oct 22, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | Notebook    | [35d4f4cf0e](https://linux-hardware.org/?probe=35d4f4cf0e) | Oct 20, 2022 |
| Tactus        | GeoFlex 110                 | Convertible | [42fb435775](https://linux-hardware.org/?probe=42fb435775) | Oct 18, 2022 |
| Acer          | Aspire E5-551               | Notebook    | [9d281c015c](https://linux-hardware.org/?probe=9d281c015c) | Oct 11, 2022 |
| Acer          | Aspire E5-551               | Notebook    | [6c351b94ff](https://linux-hardware.org/?probe=6c351b94ff) | Oct 11, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [17f73f4f28](https://linux-hardware.org/?probe=17f73f4f28) | Oct 09, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | Notebook    | [d7379a41e9](https://linux-hardware.org/?probe=d7379a41e9) | Oct 08, 2022 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [e3f9c7a4f1](https://linux-hardware.org/?probe=e3f9c7a4f1) | Oct 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | Notebook    | [f913d9cde2](https://linux-hardware.org/?probe=f913d9cde2) | Oct 04, 2022 |
| Lenovo        | Yoga 510-14ISK 80S7         | Notebook    | [8731307ce6](https://linux-hardware.org/?probe=8731307ce6) | Oct 02, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [7221bbf8e7](https://linux-hardware.org/?probe=7221bbf8e7) | Oct 01, 2022 |
| Unknown       | Unknown                     | Notebook    | [b9486c47c1](https://linux-hardware.org/?probe=b9486c47c1) | Oct 01, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [0d466bc2f7](https://linux-hardware.org/?probe=0d466bc2f7) | Sep 30, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [87c9436154](https://linux-hardware.org/?probe=87c9436154) | Sep 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [d3047f6963](https://linux-hardware.org/?probe=d3047f6963) | Sep 30, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [6ea648bc51](https://linux-hardware.org/?probe=6ea648bc51) | Sep 28, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [2c52de3e56](https://linux-hardware.org/?probe=2c52de3e56) | Sep 27, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [67040d9a5e](https://linux-hardware.org/?probe=67040d9a5e) | Sep 25, 2022 |
| Acer          | Aspire V5-573G              | Notebook    | [50792d0ac6](https://linux-hardware.org/?probe=50792d0ac6) | Sep 25, 2022 |
| Gigabyte      | 990FXA-UD5                  | Desktop     | [7c8d5609e0](https://linux-hardware.org/?probe=7c8d5609e0) | Sep 22, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [0be5b29760](https://linux-hardware.org/?probe=0be5b29760) | Sep 21, 2022 |
| Gigabyte      | EX58-UD4P                   | Desktop     | [394aad4be9](https://linux-hardware.org/?probe=394aad4be9) | Sep 20, 2022 |
| Acer          | Aspire E5-553               | Notebook    | [5db637f345](https://linux-hardware.org/?probe=5db637f345) | Sep 19, 2022 |
| Acer          | Aspire E5-553               | Notebook    | [f0bbe89fe8](https://linux-hardware.org/?probe=f0bbe89fe8) | Sep 19, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [82fc38716c](https://linux-hardware.org/?probe=82fc38716c) | Sep 19, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [af2f12093c](https://linux-hardware.org/?probe=af2f12093c) | Sep 17, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [e55484acd4](https://linux-hardware.org/?probe=e55484acd4) | Sep 17, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [ed284e43fb](https://linux-hardware.org/?probe=ed284e43fb) | Sep 14, 2022 |
| MSI           | Katana GF66 12UE            | Notebook    | [955b9787eb](https://linux-hardware.org/?probe=955b9787eb) | Sep 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [224ecd9fa7](https://linux-hardware.org/?probe=224ecd9fa7) | Sep 13, 2022 |
| Lenovo        | SDK0J40700 WIN              | Desktop     | [b8f3a58a03](https://linux-hardware.org/?probe=b8f3a58a03) | Sep 11, 2022 |
| Valve         | Jupiter                     | Notebook    | [17ddfcd578](https://linux-hardware.org/?probe=17ddfcd578) | Sep 11, 2022 |
| MSI           | MPG Z390M GAMING EDGE AC    | Desktop     | [20ead11e02](https://linux-hardware.org/?probe=20ead11e02) | Sep 10, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [cc40453955](https://linux-hardware.org/?probe=cc40453955) | Sep 06, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [11b9de78b5](https://linux-hardware.org/?probe=11b9de78b5) | Sep 06, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [865455aae7](https://linux-hardware.org/?probe=865455aae7) | Sep 05, 2022 |
| Acer          | Aspire E5-553               | Notebook    | [de2cfb43d7](https://linux-hardware.org/?probe=de2cfb43d7) | Sep 03, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [4a7d6a9276](https://linux-hardware.org/?probe=4a7d6a9276) | Sep 01, 2022 |
| Gigabyte      | 990FXA-UD5                  | Desktop     | [e5364d8761](https://linux-hardware.org/?probe=e5364d8761) | Sep 01, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [3662302886](https://linux-hardware.org/?probe=3662302886) | Aug 31, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [c2d66050b5](https://linux-hardware.org/?probe=c2d66050b5) | Aug 30, 2022 |
| Unknown       | TB-4000                     | Desktop     | [8f7f2e486a](https://linux-hardware.org/?probe=8f7f2e486a) | Aug 30, 2022 |
| HP            | ProBook 6550b               | Notebook    | [662065bfe2](https://linux-hardware.org/?probe=662065bfe2) | Aug 29, 2022 |
| ASUSTek       | SABERTOOTH X58              | Desktop     | [efb40be4e1](https://linux-hardware.org/?probe=efb40be4e1) | Aug 28, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [8d17bfec23](https://linux-hardware.org/?probe=8d17bfec23) | Aug 28, 2022 |
| Gigabyte      | P85-D3                      | Desktop     | [06b934d14f](https://linux-hardware.org/?probe=06b934d14f) | Aug 26, 2022 |
| Unknown       | TB-4000                     | Desktop     | [a3cfbd4659](https://linux-hardware.org/?probe=a3cfbd4659) | Aug 25, 2022 |
| Lenovo        | B50-50 80S2                 | Notebook    | [45f5a72c59](https://linux-hardware.org/?probe=45f5a72c59) | Aug 24, 2022 |
| Acer          | Swift SF114-33              | Notebook    | [115ca42bb8](https://linux-hardware.org/?probe=115ca42bb8) | Aug 24, 2022 |
| Acer          | Swift SF114-33              | Notebook    | [0ab380f8ac](https://linux-hardware.org/?probe=0ab380f8ac) | Aug 23, 2022 |
| Gigabyte      | B460M DS3H V2               | Desktop     | [e5e74eea07](https://linux-hardware.org/?probe=e5e74eea07) | Aug 19, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1AY0... | Notebook    | [fcda79b03d](https://linux-hardware.org/?probe=fcda79b03d) | Aug 17, 2022 |
| MSI           | X470 GAMING PRO             | Desktop     | [52b08fd4ba](https://linux-hardware.org/?probe=52b08fd4ba) | Aug 16, 2022 |
| Gigabyte      | M4HM87P-00                  | Desktop     | [5bb7e42eae](https://linux-hardware.org/?probe=5bb7e42eae) | Aug 16, 2022 |
| Unknown       | TB-4000                     | Desktop     | [906699e408](https://linux-hardware.org/?probe=906699e408) | Aug 14, 2022 |
| Gigabyte      | B550 AORUS MASTER           | Desktop     | [0009de2dbb](https://linux-hardware.org/?probe=0009de2dbb) | Aug 11, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [53efca63c3](https://linux-hardware.org/?probe=53efca63c3) | Aug 10, 2022 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | Notebook    | [1d97fa15fb](https://linux-hardware.org/?probe=1d97fa15fb) | Aug 08, 2022 |
| Lenovo        | ThinkCentre M57 6087YD2     | Desktop     | [9ad2c07771](https://linux-hardware.org/?probe=9ad2c07771) | Aug 06, 2022 |
| Acer          | Aspire M3-581TG             | Notebook    | [5c73e4c75b](https://linux-hardware.org/?probe=5c73e4c75b) | Aug 05, 2022 |
| Dell          | 0V0D45 A01                  | All in one  | [7d2f0e045d](https://linux-hardware.org/?probe=7d2f0e045d) | Aug 05, 2022 |
| Lenovo        | SDK0J40700 WIN              | Desktop     | [299ac7a8ff](https://linux-hardware.org/?probe=299ac7a8ff) | Aug 03, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [41189cd175](https://linux-hardware.org/?probe=41189cd175) | Aug 03, 2022 |
| Notebook      | NS50_70MU                   | Notebook    | [35cb4f8526](https://linux-hardware.org/?probe=35cb4f8526) | Aug 02, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [e6ccfdf23c](https://linux-hardware.org/?probe=e6ccfdf23c) | Jul 31, 2022 |
| Lenovo        | SDK0J40700 WIN              | Desktop     | [f50872e350](https://linux-hardware.org/?probe=f50872e350) | Jul 29, 2022 |
| Packard Be... | H57M01                      | Desktop     | [55e1536ab6](https://linux-hardware.org/?probe=55e1536ab6) | Jul 29, 2022 |
| Packard Be... | H57M01                      | Desktop     | [4789405230](https://linux-hardware.org/?probe=4789405230) | Jul 29, 2022 |
| Lenovo        | SDK0J40700 WIN              | Desktop     | [6d95a05ee7](https://linux-hardware.org/?probe=6d95a05ee7) | Jul 28, 2022 |
| Lenovo        | SDK0J40700 WIN              | Desktop     | [96d6480781](https://linux-hardware.org/?probe=96d6480781) | Jul 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [83e5824a05](https://linux-hardware.org/?probe=83e5824a05) | Jul 24, 2022 |
| Gigabyte      | MJPLNAB-00                  | Desktop     | [d414e51a0c](https://linux-hardware.org/?probe=d414e51a0c) | Jul 23, 2022 |
| Gigabyte      | MJPLNAB-00                  | Desktop     | [9dcb499f3e](https://linux-hardware.org/?probe=9dcb499f3e) | Jul 23, 2022 |
| MSI           | Z170A KRAIT GAMING 3X       | Desktop     | [1fef57c873](https://linux-hardware.org/?probe=1fef57c873) | Jul 22, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [3c346ed8da](https://linux-hardware.org/?probe=3c346ed8da) | Jul 20, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [23f16d1cac](https://linux-hardware.org/?probe=23f16d1cac) | Jul 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [d83a4d5121](https://linux-hardware.org/?probe=d83a4d5121) | Jul 18, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [03839f9fef](https://linux-hardware.org/?probe=03839f9fef) | Jul 17, 2022 |
| HP            | Laptop 15-gw0xxx            | Notebook    | [a7f15d1696](https://linux-hardware.org/?probe=a7f15d1696) | Jul 16, 2022 |
| MSI           | X470 GAMING PRO             | Desktop     | [716dd72eeb](https://linux-hardware.org/?probe=716dd72eeb) | Jul 13, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [4d9388058d](https://linux-hardware.org/?probe=4d9388058d) | Jul 12, 2022 |
| Acer          | Aspire E5-553               | Notebook    | [e7cdc97a90](https://linux-hardware.org/?probe=e7cdc97a90) | Jul 11, 2022 |
| MSI           | MS-AF151 100                | All in one  | [cd5a32135a](https://linux-hardware.org/?probe=cd5a32135a) | Jul 07, 2022 |
| MSI           | MS-AF151 100                | All in one  | [55deb5fb81](https://linux-hardware.org/?probe=55deb5fb81) | Jul 07, 2022 |
| Medion        | Iron238KR                   | All in one  | [ff6bf1bc47](https://linux-hardware.org/?probe=ff6bf1bc47) | Jul 07, 2022 |
| Dell          | Latitude 7490               | Notebook    | [b456bca385](https://linux-hardware.org/?probe=b456bca385) | Jul 06, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [a74834b383](https://linux-hardware.org/?probe=a74834b383) | Jul 04, 2022 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | Notebook    | [0e23c1fc2b](https://linux-hardware.org/?probe=0e23c1fc2b) | Jul 02, 2022 |
| HP            | 805D                        | Desktop     | [3610332b9c](https://linux-hardware.org/?probe=3610332b9c) | Jul 01, 2022 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [c12aa3088a](https://linux-hardware.org/?probe=c12aa3088a) | Jun 30, 2022 |
| Lenovo        | ThinkPad T530 24295L4       | Notebook    | [1bdf25550e](https://linux-hardware.org/?probe=1bdf25550e) | Jun 29, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [0c1cbe6fd7](https://linux-hardware.org/?probe=0c1cbe6fd7) | Jun 28, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [b0c272ff93](https://linux-hardware.org/?probe=b0c272ff93) | Jun 26, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [66283ad8cd](https://linux-hardware.org/?probe=66283ad8cd) | Jun 24, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [6dfa236f76](https://linux-hardware.org/?probe=6dfa236f76) | Jun 18, 2022 |
| Lenovo        | SDK0J40700 WIN              | Desktop     | [82be38e941](https://linux-hardware.org/?probe=82be38e941) | Jun 17, 2022 |
| Notebook      | PB50_70DFx,DDx              | Notebook    | [21206dd6bf](https://linux-hardware.org/?probe=21206dd6bf) | Jun 14, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [527587d2b9](https://linux-hardware.org/?probe=527587d2b9) | Jun 14, 2022 |
| Lenovo        | ThinkPad T550 20CK003HMD    | Notebook    | [ea8155f580](https://linux-hardware.org/?probe=ea8155f580) | Jun 14, 2022 |
| Dell          | Latitude E7440              | Notebook    | [6bbb1944af](https://linux-hardware.org/?probe=6bbb1944af) | Jun 12, 2022 |
| Google        | Babytiger                   | Notebook    | [18f6f97122](https://linux-hardware.org/?probe=18f6f97122) | Jun 12, 2022 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [36389b33b6](https://linux-hardware.org/?probe=36389b33b6) | Jun 12, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [d3fdbc7413](https://linux-hardware.org/?probe=d3fdbc7413) | Jun 12, 2022 |
| Lenovo        | SKYBAY SDK0J40697 WIN 33... | Desktop     | [9c7b2faf2c](https://linux-hardware.org/?probe=9c7b2faf2c) | Jun 10, 2022 |
| HP            | EliteBook 2560p             | Notebook    | [5f1e0dfee7](https://linux-hardware.org/?probe=5f1e0dfee7) | Jun 09, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [bd545aec1b](https://linux-hardware.org/?probe=bd545aec1b) | Jun 09, 2022 |
| Acer          | Aspire ES1-523              | Notebook    | [242fc61e3a](https://linux-hardware.org/?probe=242fc61e3a) | Jun 08, 2022 |
| Acer          | Aspire 5732Z                | Notebook    | [b9a30cba65](https://linux-hardware.org/?probe=b9a30cba65) | Jun 08, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [a307c95089](https://linux-hardware.org/?probe=a307c95089) | Jun 08, 2022 |
| Acer          | Aspire 5732Z                | Notebook    | [3c14a5bf10](https://linux-hardware.org/?probe=3c14a5bf10) | Jun 08, 2022 |
| Unknown       | TB-4000                     | Desktop     | [c268e7111b](https://linux-hardware.org/?probe=c268e7111b) | Jun 07, 2022 |
| BESSTAR Te... | HM90                        | Desktop     | [5272429aa9](https://linux-hardware.org/?probe=5272429aa9) | Jun 04, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | Notebook    | [0b2aab3dc7](https://linux-hardware.org/?probe=0b2aab3dc7) | Jun 04, 2022 |
| Lenovo        | V330-14ARR 81B1             | Notebook    | [dad2acbf49](https://linux-hardware.org/?probe=dad2acbf49) | Jun 02, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [af42d8d0b4](https://linux-hardware.org/?probe=af42d8d0b4) | May 27, 2022 |
| Dell          | 09CGW2 A11                  | Server      | [27b873f279](https://linux-hardware.org/?probe=27b873f279) | May 27, 2022 |
| HP            | ProBook 6450b               | Notebook    | [8c35a4c278](https://linux-hardware.org/?probe=8c35a4c278) | May 26, 2022 |
| Dell          | Latitude E7440              | Notebook    | [975715a96b](https://linux-hardware.org/?probe=975715a96b) | May 26, 2022 |
| HP            | ProBook 6450b               | Notebook    | [863987eb13](https://linux-hardware.org/?probe=863987eb13) | May 26, 2022 |
| Intel         | NUC8BEB J72692-303          | Mini pc     | [94796b9e96](https://linux-hardware.org/?probe=94796b9e96) | May 26, 2022 |
| ASUSTek       | PN50                        | Mini pc     | [60a16a0a17](https://linux-hardware.org/?probe=60a16a0a17) | May 26, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [8e0addf4d3](https://linux-hardware.org/?probe=8e0addf4d3) | May 24, 2022 |
| MSI           | X470 GAMING PRO             | Desktop     | [8409fe7eab](https://linux-hardware.org/?probe=8409fe7eab) | May 24, 2022 |
| MSI           | 970A-G43                    | Desktop     | [92dd93dd78](https://linux-hardware.org/?probe=92dd93dd78) | May 24, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [d3f5e5aa45](https://linux-hardware.org/?probe=d3f5e5aa45) | May 22, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [62486fe8d6](https://linux-hardware.org/?probe=62486fe8d6) | May 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [f0f481f187](https://linux-hardware.org/?probe=f0f481f187) | May 21, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [49df794b0b](https://linux-hardware.org/?probe=49df794b0b) | May 20, 2022 |
| SLIMBOOK      | PROX14-10                   | Notebook    | [b0d5e9b290](https://linux-hardware.org/?probe=b0d5e9b290) | May 19, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [c7f7168362](https://linux-hardware.org/?probe=c7f7168362) | May 18, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [6efbcdabfc](https://linux-hardware.org/?probe=6efbcdabfc) | May 17, 2022 |
| Lenovo        | ThinkPad T480 20L6S14Y01    | Notebook    | [d3f3fff089](https://linux-hardware.org/?probe=d3f3fff089) | May 16, 2022 |
| ASUSTek       | ROG ZENITH II EXTREME AL... | Desktop     | [bc9270aeff](https://linux-hardware.org/?probe=bc9270aeff) | May 13, 2022 |
| ASUSTek       | ROG ZENITH II EXTREME AL... | Desktop     | [f0e5f896a4](https://linux-hardware.org/?probe=f0e5f896a4) | May 11, 2022 |
| Dell          | Precision 5750              | Notebook    | [11e888b7d9](https://linux-hardware.org/?probe=11e888b7d9) | May 10, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [21486c437b](https://linux-hardware.org/?probe=21486c437b) | May 08, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [591d3fa922](https://linux-hardware.org/?probe=591d3fa922) | May 07, 2022 |
| Packard Be... | EasyNote TE69BM             | Notebook    | [ed538d5b79](https://linux-hardware.org/?probe=ed538d5b79) | May 07, 2022 |
| Gigabyte      | G41M-Combo                  | Desktop     | [9940073216](https://linux-hardware.org/?probe=9940073216) | May 05, 2022 |
| Dell          | Inspiron 7786               | Convertible | [0ef12447d9](https://linux-hardware.org/?probe=0ef12447d9) | May 02, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [ac5b1123ad](https://linux-hardware.org/?probe=ac5b1123ad) | Apr 30, 2022 |
| Unknown       | TB-4000                     | Desktop     | [99911022e9](https://linux-hardware.org/?probe=99911022e9) | Apr 26, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [8694f28b60](https://linux-hardware.org/?probe=8694f28b60) | Apr 25, 2022 |
| MSI           | MS-1T11                     | Desktop     | [9c16a631ef](https://linux-hardware.org/?probe=9c16a631ef) | Apr 23, 2022 |
| MSI           | MS-1T11                     | Desktop     | [e263cd80f5](https://linux-hardware.org/?probe=e263cd80f5) | Apr 23, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | Notebook    | [0cd6fe25ec](https://linux-hardware.org/?probe=0cd6fe25ec) | Apr 22, 2022 |
| Acer          | Aspire E5-553               | Notebook    | [1c736596fa](https://linux-hardware.org/?probe=1c736596fa) | Apr 21, 2022 |
| Lenovo        | SHARKBAY SDK0J40705 WIN ... | Desktop     | [91aa85fff9](https://linux-hardware.org/?probe=91aa85fff9) | Apr 21, 2022 |
| Lenovo        | B575e 36852EG               | Notebook    | [8f5e5f427a](https://linux-hardware.org/?probe=8f5e5f427a) | Apr 18, 2022 |
| Lenovo        | B575e 36852EG               | Notebook    | [4731516b58](https://linux-hardware.org/?probe=4731516b58) | Apr 18, 2022 |
| Lenovo        | ThinkPad T440 20B7S1EV00    | Notebook    | [b035e7ae3e](https://linux-hardware.org/?probe=b035e7ae3e) | Apr 16, 2022 |
| HP            | EliteBook 820 G3            | Notebook    | [a587867d2e](https://linux-hardware.org/?probe=a587867d2e) | Apr 15, 2022 |
| MSI           | GF63 Thin 10SC              | Notebook    | [e5e0f208d9](https://linux-hardware.org/?probe=e5e0f208d9) | Apr 14, 2022 |
| MSI           | GF63 Thin 10SC              | Notebook    | [b5beb1add9](https://linux-hardware.org/?probe=b5beb1add9) | Apr 14, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [5e48e9d93d](https://linux-hardware.org/?probe=5e48e9d93d) | Apr 12, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [27825828c9](https://linux-hardware.org/?probe=27825828c9) | Apr 05, 2022 |
| Acer          | Aspire V5-573G              | Notebook    | [2b608bcde8](https://linux-hardware.org/?probe=2b608bcde8) | Apr 04, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [ddc3550f6b](https://linux-hardware.org/?probe=ddc3550f6b) | Apr 04, 2022 |
| ASRock        | X99 Extreme4                | Desktop     | [e29b4c30f1](https://linux-hardware.org/?probe=e29b4c30f1) | Apr 04, 2022 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [67b9d43387](https://linux-hardware.org/?probe=67b9d43387) | Apr 03, 2022 |
| Lenovo        | ThinkPad X390 20Q0002LMX    | Notebook    | [22aaabe433](https://linux-hardware.org/?probe=22aaabe433) | Apr 03, 2022 |
| ASUSTek       | ROG STRIX B450-E GAMING     | Desktop     | [a5c5028fde](https://linux-hardware.org/?probe=a5c5028fde) | Apr 03, 2022 |
| ASUSTek       | ROG STRIX B450-E GAMING     | Desktop     | [d978436f5f](https://linux-hardware.org/?probe=d978436f5f) | Apr 03, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [0ba5fd01fa](https://linux-hardware.org/?probe=0ba5fd01fa) | Mar 30, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [b9a21aea35](https://linux-hardware.org/?probe=b9a21aea35) | Mar 29, 2022 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [f3cd1a314c](https://linux-hardware.org/?probe=f3cd1a314c) | Mar 25, 2022 |
| Lenovo        | E31-80 80MX                 | Notebook    | [8dc93e34e9](https://linux-hardware.org/?probe=8dc93e34e9) | Mar 25, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [4ce05dd1e2](https://linux-hardware.org/?probe=4ce05dd1e2) | Mar 24, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [3bf42ed5a6](https://linux-hardware.org/?probe=3bf42ed5a6) | Mar 24, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [72da14a2b2](https://linux-hardware.org/?probe=72da14a2b2) | Mar 23, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [72245fe662](https://linux-hardware.org/?probe=72245fe662) | Mar 22, 2022 |
| Lenovo        | ThinkPad X260 20F60086MD    | Notebook    | [828cc46772](https://linux-hardware.org/?probe=828cc46772) | Mar 22, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [f3b52d9201](https://linux-hardware.org/?probe=f3b52d9201) | Mar 21, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [5c40bf9192](https://linux-hardware.org/?probe=5c40bf9192) | Mar 21, 2022 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [8be4c394f1](https://linux-hardware.org/?probe=8be4c394f1) | Mar 18, 2022 |
| Gigabyte      | MFLP7IP-00                  | Desktop     | [304c5939e7](https://linux-hardware.org/?probe=304c5939e7) | Mar 18, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [abc4597fe1](https://linux-hardware.org/?probe=abc4597fe1) | Mar 18, 2022 |
| Notebook      | P65xHP                      | Notebook    | [3222aab43a](https://linux-hardware.org/?probe=3222aab43a) | Mar 16, 2022 |
| Shuttle       | X50V2PLUS V1.00             | Desktop     | [0bd650dfff](https://linux-hardware.org/?probe=0bd650dfff) | Mar 16, 2022 |
| Acer          | Aspire 3830T                | Notebook    | [bad3a5c2d7](https://linux-hardware.org/?probe=bad3a5c2d7) | Mar 15, 2022 |
| HP            | EliteBook 850 G5            | Notebook    | [ab88a095ac](https://linux-hardware.org/?probe=ab88a095ac) | Mar 10, 2022 |
| Dell          | Latitude E6410              | Notebook    | [d4fa7879a4](https://linux-hardware.org/?probe=d4fa7879a4) | Mar 09, 2022 |
| Dell          | Precision M4800             | Notebook    | [6bca1ea21f](https://linux-hardware.org/?probe=6bca1ea21f) | Mar 06, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [e7d10ddac0](https://linux-hardware.org/?probe=e7d10ddac0) | Mar 04, 2022 |
| Dell          | Latitude E6410              | Notebook    | [6748e5a7aa](https://linux-hardware.org/?probe=6748e5a7aa) | Feb 27, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [30879c05cc](https://linux-hardware.org/?probe=30879c05cc) | Feb 24, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [500a30847d](https://linux-hardware.org/?probe=500a30847d) | Feb 23, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [04e8e7704e](https://linux-hardware.org/?probe=04e8e7704e) | Feb 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [505e1dc8cc](https://linux-hardware.org/?probe=505e1dc8cc) | Feb 21, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [c1929d8540](https://linux-hardware.org/?probe=c1929d8540) | Feb 21, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [bdc86d995a](https://linux-hardware.org/?probe=bdc86d995a) | Feb 21, 2022 |
| Lenovo        | ThinkPad L530 24812SG       | Notebook    | [6eb3e0ed53](https://linux-hardware.org/?probe=6eb3e0ed53) | Feb 19, 2022 |
| Dell          | 0KC9NP A01                  | Desktop     | [f9a0fa24f8](https://linux-hardware.org/?probe=f9a0fa24f8) | Feb 18, 2022 |
| ASRock        | FM2A55M-DGS                 | Desktop     | [efe38992bd](https://linux-hardware.org/?probe=efe38992bd) | Feb 15, 2022 |
| Dell          | 0GTK4K A02                  | Desktop     | [466029e620](https://linux-hardware.org/?probe=466029e620) | Feb 13, 2022 |
| HP            | Pavilion g6                 | Notebook    | [3971fd709d](https://linux-hardware.org/?probe=3971fd709d) | Feb 13, 2022 |
| Acer          | Aspire E5-575               | Notebook    | [3e75911df8](https://linux-hardware.org/?probe=3e75911df8) | Feb 12, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [b059819620](https://linux-hardware.org/?probe=b059819620) | Feb 11, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [87f4740598](https://linux-hardware.org/?probe=87f4740598) | Feb 11, 2022 |
| Toshiba       | Satellite L40               | Notebook    | [ba6d18935b](https://linux-hardware.org/?probe=ba6d18935b) | Feb 08, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [e63f72d407](https://linux-hardware.org/?probe=e63f72d407) | Feb 07, 2022 |
| Medion        | MS-7800                     | Desktop     | [9693a4d35c](https://linux-hardware.org/?probe=9693a4d35c) | Feb 05, 2022 |
| Lenovo        | ThinkPad L480 20LS001AMD    | Notebook    | [801aa8fb1e](https://linux-hardware.org/?probe=801aa8fb1e) | Feb 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [23c6243856](https://linux-hardware.org/?probe=23c6243856) | Feb 05, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [40ed6ce0c5](https://linux-hardware.org/?probe=40ed6ce0c5) | Feb 04, 2022 |
| Unknown       | TB-4000                     | Desktop     | [225e399fc1](https://linux-hardware.org/?probe=225e399fc1) | Feb 03, 2022 |
| Medion        | P7612                       | Notebook    | [e1c076ee06](https://linux-hardware.org/?probe=e1c076ee06) | Feb 03, 2022 |
| HP            | Compaq Presario CQ71        | Notebook    | [436407f045](https://linux-hardware.org/?probe=436407f045) | Feb 01, 2022 |
| Lenovo        | B50-50 80S2                 | Notebook    | [7602963c65](https://linux-hardware.org/?probe=7602963c65) | Feb 01, 2022 |
| Dell          | Latitude E6540              | Notebook    | [fe6720f0de](https://linux-hardware.org/?probe=fe6720f0de) | Jan 30, 2022 |
| Dell          | Latitude E6540              | Notebook    | [7c972de545](https://linux-hardware.org/?probe=7c972de545) | Jan 30, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [478d5281bd](https://linux-hardware.org/?probe=478d5281bd) | Jan 29, 2022 |
| HP            | Pavilion dv7                | Notebook    | [e6ec9b5f6a](https://linux-hardware.org/?probe=e6ec9b5f6a) | Jan 26, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [b8f4a15736](https://linux-hardware.org/?probe=b8f4a15736) | Jan 25, 2022 |
| Medion        | P7612                       | Notebook    | [50be4d531e](https://linux-hardware.org/?probe=50be4d531e) | Jan 25, 2022 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [298ddd1139](https://linux-hardware.org/?probe=298ddd1139) | Jan 24, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [82cce77f87](https://linux-hardware.org/?probe=82cce77f87) | Jan 22, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [4ef203e4a1](https://linux-hardware.org/?probe=4ef203e4a1) | Jan 22, 2022 |
| DukaPC        | Notebook                    | Notebook    | [21b4827b4b](https://linux-hardware.org/?probe=21b4827b4b) | Jan 21, 2022 |
| ASUSTek       | P8H67-M                     | Desktop     | [a69dd56657](https://linux-hardware.org/?probe=a69dd56657) | Jan 21, 2022 |
| Acer          | Aspire F5-572G              | Notebook    | [221a91f679](https://linux-hardware.org/?probe=221a91f679) | Jan 19, 2022 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | Notebook    | [80906dc02b](https://linux-hardware.org/?probe=80906dc02b) | Jan 19, 2022 |
| Gigabyte      | B460M AORUS PRO             | Desktop     | [1e301a4129](https://linux-hardware.org/?probe=1e301a4129) | Jan 19, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | Notebook    | [cc39f1fd96](https://linux-hardware.org/?probe=cc39f1fd96) | Jan 18, 2022 |
| Acer          | Predator G6-710             | Desktop     | [29bdcc72c9](https://linux-hardware.org/?probe=29bdcc72c9) | Jan 18, 2022 |
| ASUSTek       | P8H67-M                     | Desktop     | [1568252a07](https://linux-hardware.org/?probe=1568252a07) | Jan 17, 2022 |
| IBM           | ThinkPad T40 237342G        | Notebook    | [2c96b391e2](https://linux-hardware.org/?probe=2c96b391e2) | Jan 16, 2022 |
| IBM           | ThinkPad T40 237342G        | Notebook    | [5c4e8748ef](https://linux-hardware.org/?probe=5c4e8748ef) | Jan 16, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [4ebb815948](https://linux-hardware.org/?probe=4ebb815948) | Jan 15, 2022 |
| HP            | Pavilion g7                 | Notebook    | [6efd331acf](https://linux-hardware.org/?probe=6efd331acf) | Jan 14, 2022 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | Notebook    | [4cefa23802](https://linux-hardware.org/?probe=4cefa23802) | Jan 14, 2022 |
| Acer          | Aspire E5-553               | Notebook    | [149c0538ca](https://linux-hardware.org/?probe=149c0538ca) | Jan 13, 2022 |
| Lenovo        | M30-70 80H8                 | Notebook    | [2f61d772a4](https://linux-hardware.org/?probe=2f61d772a4) | Jan 12, 2022 |
| Lenovo        | Y50-70 20378                | Notebook    | [ab93bc517a](https://linux-hardware.org/?probe=ab93bc517a) | Jan 12, 2022 |
| Razer         | Blade                       | Notebook    | [afad6aaa95](https://linux-hardware.org/?probe=afad6aaa95) | Jan 08, 2022 |
| Gigabyte      | Z68X-UD3-B3                 | Desktop     | [46932917d4](https://linux-hardware.org/?probe=46932917d4) | Jan 08, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [39affa759d](https://linux-hardware.org/?probe=39affa759d) | Jan 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [1f327abc43](https://linux-hardware.org/?probe=1f327abc43) | Jan 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [53a3989606](https://linux-hardware.org/?probe=53a3989606) | Jan 03, 2022 |
| Acer          | Aspire V5-573G              | Notebook    | [a7e3940936](https://linux-hardware.org/?probe=a7e3940936) | Jan 02, 2022 |
| Dell          | Inspiron 7720               | Notebook    | [4e1ebc00ff](https://linux-hardware.org/?probe=4e1ebc00ff) | Jan 02, 2022 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [8ff352de01](https://linux-hardware.org/?probe=8ff352de01) | Dec 31, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [6246bb8ef6](https://linux-hardware.org/?probe=6246bb8ef6) | Dec 31, 2021 |
| Lenovo        | V330-14ARR 81B1             | Notebook    | [290d6b4ad5](https://linux-hardware.org/?probe=290d6b4ad5) | Dec 29, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [c38d256cab](https://linux-hardware.org/?probe=c38d256cab) | Dec 29, 2021 |
| Pegatron      | 2AD5                        | Desktop     | [efc0a3875a](https://linux-hardware.org/?probe=efc0a3875a) | Dec 29, 2021 |
| MSI           | A68HM GRENADE               | Desktop     | [18ca0bdd91](https://linux-hardware.org/?probe=18ca0bdd91) | Dec 27, 2021 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [13f35d1d12](https://linux-hardware.org/?probe=13f35d1d12) | Dec 26, 2021 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [369d18645c](https://linux-hardware.org/?probe=369d18645c) | Dec 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [e68ec90909](https://linux-hardware.org/?probe=e68ec90909) | Dec 24, 2021 |
| Medion        | P6630                       | Notebook    | [de245dfdb6](https://linux-hardware.org/?probe=de245dfdb6) | Dec 23, 2021 |
| MSI           | X470 GAMING PRO             | Desktop     | [d683987eea](https://linux-hardware.org/?probe=d683987eea) | Dec 23, 2021 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [32e8c7ccb2](https://linux-hardware.org/?probe=32e8c7ccb2) | Dec 22, 2021 |
| Notebook      | N24_25JU                    | Notebook    | [8ac7d4890e](https://linux-hardware.org/?probe=8ac7d4890e) | Dec 20, 2021 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [1e14543dfd](https://linux-hardware.org/?probe=1e14543dfd) | Dec 18, 2021 |
| Quanta        | MW1/HW1                     | Notebook    | [06bcb3603d](https://linux-hardware.org/?probe=06bcb3603d) | Dec 17, 2021 |
| ASUSTek       | K53SV                       | Notebook    | [be7844ea44](https://linux-hardware.org/?probe=be7844ea44) | Dec 17, 2021 |
| HP            | 3031h                       | Desktop     | [8a8888c824](https://linux-hardware.org/?probe=8a8888c824) | Dec 17, 2021 |
| ABIT          | I-G31                       | Desktop     | [048b7bcf6a](https://linux-hardware.org/?probe=048b7bcf6a) | Dec 13, 2021 |
| Lenovo        | ThinkPad T460s 20FAS05Q0... | Notebook    | [3a4b9beb1d](https://linux-hardware.org/?probe=3a4b9beb1d) | Dec 12, 2021 |
| Dell          | 0YXT71 A01                  | Desktop     | [fbe4f7fdb9](https://linux-hardware.org/?probe=fbe4f7fdb9) | Dec 12, 2021 |
| Apple         | Mac-F2268DC8                | All in one  | [99c299c85b](https://linux-hardware.org/?probe=99c299c85b) | Dec 11, 2021 |
| Toshiba       | Satellite P850              | Notebook    | [bfc37f531a](https://linux-hardware.org/?probe=bfc37f531a) | Dec 11, 2021 |
| ASUSTek       | Z170-P                      | Desktop     | [6e857bc210](https://linux-hardware.org/?probe=6e857bc210) | Dec 09, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [d6be9fac19](https://linux-hardware.org/?probe=d6be9fac19) | Dec 09, 2021 |
| Lenovo        | ThinkPad T470s 20HF004UM... | Notebook    | [e7144e5f86](https://linux-hardware.org/?probe=e7144e5f86) | Dec 09, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [ac173fd5ba](https://linux-hardware.org/?probe=ac173fd5ba) | Dec 09, 2021 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [e884cd44db](https://linux-hardware.org/?probe=e884cd44db) | Dec 08, 2021 |
| Fujitsu Si... | LIFEBOOK E8420              | Notebook    | [7ff3493cfe](https://linux-hardware.org/?probe=7ff3493cfe) | Dec 08, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [0dc0958719](https://linux-hardware.org/?probe=0dc0958719) | Dec 06, 2021 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [22f7fc3dbe](https://linux-hardware.org/?probe=22f7fc3dbe) | Dec 04, 2021 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [26541caf1e](https://linux-hardware.org/?probe=26541caf1e) | Dec 03, 2021 |
| HP            | 3031h                       | Desktop     | [68cf960e7f](https://linux-hardware.org/?probe=68cf960e7f) | Dec 02, 2021 |
| HP            | 3031h                       | Desktop     | [1c49cd6404](https://linux-hardware.org/?probe=1c49cd6404) | Dec 02, 2021 |
| DukaPC        | Notebook                    | Notebook    | [cfb399153a](https://linux-hardware.org/?probe=cfb399153a) | Dec 01, 2021 |
| HP            | 8299                        | Desktop     | [6eb5c6d54a](https://linux-hardware.org/?probe=6eb5c6d54a) | Nov 30, 2021 |
| HP            | 8299                        | Desktop     | [7bd1df0e4d](https://linux-hardware.org/?probe=7bd1df0e4d) | Nov 29, 2021 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [0574fefb71](https://linux-hardware.org/?probe=0574fefb71) | Nov 29, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [6071fde7dd](https://linux-hardware.org/?probe=6071fde7dd) | Nov 28, 2021 |
| Razer         | Blade Stealth               | Notebook    | [54acf9844b](https://linux-hardware.org/?probe=54acf9844b) | Nov 28, 2021 |
| Apple         | MacBookPro11,2              | Notebook    | [07931c8e7b](https://linux-hardware.org/?probe=07931c8e7b) | Nov 24, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | Notebook    | [c224ffa45a](https://linux-hardware.org/?probe=c224ffa45a) | Nov 23, 2021 |
| Acer          | Aspire X3995                | Desktop     | [cde003006d](https://linux-hardware.org/?probe=cde003006d) | Nov 22, 2021 |
| Acer          | Aspire X3995                | Desktop     | [2e97d6ef1c](https://linux-hardware.org/?probe=2e97d6ef1c) | Nov 22, 2021 |
| Toshiba       | Satellite U300              | Notebook    | [827ec6ed62](https://linux-hardware.org/?probe=827ec6ed62) | Nov 21, 2021 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [ea4842466c](https://linux-hardware.org/?probe=ea4842466c) | Nov 20, 2021 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [faf9e68f7a](https://linux-hardware.org/?probe=faf9e68f7a) | Nov 20, 2021 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [2b2ea53377](https://linux-hardware.org/?probe=2b2ea53377) | Nov 20, 2021 |
| Dell          | Inspiron 7572               | Notebook    | [0953d49db6](https://linux-hardware.org/?probe=0953d49db6) | Nov 18, 2021 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [b4512f4b54](https://linux-hardware.org/?probe=b4512f4b54) | Nov 18, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [c80aeaf7b0](https://linux-hardware.org/?probe=c80aeaf7b0) | Nov 17, 2021 |
| ASRock        | Z170 Gaming K4              | Desktop     | [53281d6c95](https://linux-hardware.org/?probe=53281d6c95) | Nov 17, 2021 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | Notebook    | [52eef25506](https://linux-hardware.org/?probe=52eef25506) | Nov 15, 2021 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | Notebook    | [7252f23e5f](https://linux-hardware.org/?probe=7252f23e5f) | Nov 15, 2021 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | Notebook    | [1a20afde4b](https://linux-hardware.org/?probe=1a20afde4b) | Nov 15, 2021 |
| Acer          | Aspire 5810T                | Notebook    | [c41d1671bc](https://linux-hardware.org/?probe=c41d1671bc) | Nov 14, 2021 |
| Lenovo        | ThinkPad R61 8935W7T        | Notebook    | [bef030b1ef](https://linux-hardware.org/?probe=bef030b1ef) | Nov 11, 2021 |
| HP            | EliteBook 850 G5            | Notebook    | [7df8bf1476](https://linux-hardware.org/?probe=7df8bf1476) | Nov 11, 2021 |
| HP            | EliteBook 850 G5            | Notebook    | [1def8c2d0b](https://linux-hardware.org/?probe=1def8c2d0b) | Nov 11, 2021 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [e03bf03f1d](https://linux-hardware.org/?probe=e03bf03f1d) | Nov 10, 2021 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [1def6bd5d8](https://linux-hardware.org/?probe=1def6bd5d8) | Nov 10, 2021 |
| Apple         | Mac-F2268CC8                | All in one  | [10262b5305](https://linux-hardware.org/?probe=10262b5305) | Nov 10, 2021 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [2d7b8c665b](https://linux-hardware.org/?probe=2d7b8c665b) | Nov 09, 2021 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [47d8931073](https://linux-hardware.org/?probe=47d8931073) | Nov 09, 2021 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [d2a33ad9d9](https://linux-hardware.org/?probe=d2a33ad9d9) | Nov 07, 2021 |
| HP            | Pavilion g7                 | Notebook    | [c1b5449516](https://linux-hardware.org/?probe=c1b5449516) | Nov 05, 2021 |
| Dell          | 0YXT71 A01                  | Desktop     | [6f599a0889](https://linux-hardware.org/?probe=6f599a0889) | Nov 03, 2021 |
| T-bao         | MINI PC V1.0                | Desktop     | [72ce248d0c](https://linux-hardware.org/?probe=72ce248d0c) | Oct 28, 2021 |
| Apple         | MacBookPro14,1              | Notebook    | [68ebc1af79](https://linux-hardware.org/?probe=68ebc1af79) | Oct 28, 2021 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [be8c7e44de](https://linux-hardware.org/?probe=be8c7e44de) | Oct 23, 2021 |
| MSI           | Z77A-G45                    | Desktop     | [7a31ca9e22](https://linux-hardware.org/?probe=7a31ca9e22) | Oct 23, 2021 |
| Lenovo        | ThinkPad T430s 23561R0      | Notebook    | [bef1593d06](https://linux-hardware.org/?probe=bef1593d06) | Oct 22, 2021 |
| HP            | 1589                        | Desktop     | [49c747efad](https://linux-hardware.org/?probe=49c747efad) | Oct 21, 2021 |
| Gigabyte      | Z68X-UD3-B3                 | Desktop     | [e1ddc26c5e](https://linux-hardware.org/?probe=e1ddc26c5e) | Oct 20, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [14d159c564](https://linux-hardware.org/?probe=14d159c564) | Oct 20, 2021 |
| Unknown       | Unknown                     | Notebook    | [a6e5e7b6ef](https://linux-hardware.org/?probe=a6e5e7b6ef) | Oct 18, 2021 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [c0c2de7d52](https://linux-hardware.org/?probe=c0c2de7d52) | Oct 17, 2021 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Desktop     | [56f27fef6e](https://linux-hardware.org/?probe=56f27fef6e) | Oct 16, 2021 |
| Intel         | NUC10i7FNB M38062-307       | Mini pc     | [8add857c1a](https://linux-hardware.org/?probe=8add857c1a) | Oct 15, 2021 |
| Lenovo        | ThinkPad X240 20AMS5FJ00    | Notebook    | [a7fa6a8110](https://linux-hardware.org/?probe=a7fa6a8110) | Oct 14, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [cef9098008](https://linux-hardware.org/?probe=cef9098008) | Oct 14, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [718bd26737](https://linux-hardware.org/?probe=718bd26737) | Oct 14, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | Notebook    | [df32df0b62](https://linux-hardware.org/?probe=df32df0b62) | Oct 13, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | Notebook    | [c7239a1379](https://linux-hardware.org/?probe=c7239a1379) | Oct 13, 2021 |
| Toshiba       | Satellite P55W-C            | Notebook    | [f16be2ec1b](https://linux-hardware.org/?probe=f16be2ec1b) | Oct 13, 2021 |
| HP            | Pavilion g7                 | Notebook    | [7e80ec4599](https://linux-hardware.org/?probe=7e80ec4599) | Oct 11, 2021 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [70d8ac443f](https://linux-hardware.org/?probe=70d8ac443f) | Oct 11, 2021 |
| HP            | Pavilion g7                 | Notebook    | [cd8ce3be30](https://linux-hardware.org/?probe=cd8ce3be30) | Oct 10, 2021 |
| HP            | Pavilion g7                 | Notebook    | [dd3f8159e0](https://linux-hardware.org/?probe=dd3f8159e0) | Oct 10, 2021 |
| Acer          | Aspire A315-41              | Notebook    | [3d5d3ddf84](https://linux-hardware.org/?probe=3d5d3ddf84) | Oct 09, 2021 |
| Lenovo        | ThinkPad X201T 3113CC7      | Notebook    | [47f63d40d5](https://linux-hardware.org/?probe=47f63d40d5) | Oct 09, 2021 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | Notebook    | [93c695e5ba](https://linux-hardware.org/?probe=93c695e5ba) | Oct 08, 2021 |
| Microsoft     | Surface Book 3              | Tablet      | [5fdb7aebb9](https://linux-hardware.org/?probe=5fdb7aebb9) | Oct 08, 2021 |
| Lenovo        | ThinkPad T480s 20L8S4T80... | Notebook    | [85a242883c](https://linux-hardware.org/?probe=85a242883c) | Oct 05, 2021 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [a36474b9ff](https://linux-hardware.org/?probe=a36474b9ff) | Oct 04, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [56ce2c44cb](https://linux-hardware.org/?probe=56ce2c44cb) | Oct 04, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [4d0eb4ccf2](https://linux-hardware.org/?probe=4d0eb4ccf2) | Oct 04, 2021 |
| Lenovo        | V330-14ARR 81B1             | Notebook    | [c8a0e5de69](https://linux-hardware.org/?probe=c8a0e5de69) | Oct 04, 2021 |
| Gigabyte      | B560M AORUS ELITE           | Desktop     | [2c73a09463](https://linux-hardware.org/?probe=2c73a09463) | Oct 03, 2021 |
| MSI           | B460M PRO-VDH WIFI          | Desktop     | [05711b548f](https://linux-hardware.org/?probe=05711b548f) | Oct 03, 2021 |
| HUAWEI        | EUL-WX9                     | Notebook    | [dfc5c12fbf](https://linux-hardware.org/?probe=dfc5c12fbf) | Oct 01, 2021 |
| ASRock        | H470M-ITX/ac                | Desktop     | [ad42fa5d08](https://linux-hardware.org/?probe=ad42fa5d08) | Oct 01, 2021 |
| Lenovo        | ThinkPad X260 20F5S31G00    | Notebook    | [575dd64064](https://linux-hardware.org/?probe=575dd64064) | Oct 01, 2021 |
| HP            | Pavilion dv7                | Notebook    | [31b035faec](https://linux-hardware.org/?probe=31b035faec) | Sep 28, 2021 |
| Acer          | Aspire 5810T                | Notebook    | [be3f4d5a01](https://linux-hardware.org/?probe=be3f4d5a01) | Sep 26, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [edfae5b796](https://linux-hardware.org/?probe=edfae5b796) | Sep 25, 2021 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [e2fc9d2585](https://linux-hardware.org/?probe=e2fc9d2585) | Sep 23, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [5df047615c](https://linux-hardware.org/?probe=5df047615c) | Sep 22, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [d7ccece3d4](https://linux-hardware.org/?probe=d7ccece3d4) | Sep 22, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [466841a201](https://linux-hardware.org/?probe=466841a201) | Sep 22, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [201176552b](https://linux-hardware.org/?probe=201176552b) | Sep 21, 2021 |
| HP            | ZBook 15                    | Notebook    | [206882306c](https://linux-hardware.org/?probe=206882306c) | Sep 20, 2021 |
| Medion        | B360H4-EM V1.0              | Desktop     | [1985156471](https://linux-hardware.org/?probe=1985156471) | Sep 19, 2021 |
| Lenovo        | V130-15IKB 81HN             | Notebook    | [f427b869d9](https://linux-hardware.org/?probe=f427b869d9) | Sep 17, 2021 |
| Lenovo        | ThinkPad X220 4291WAY       | Notebook    | [ca0ab89977](https://linux-hardware.org/?probe=ca0ab89977) | Sep 16, 2021 |
| Lenovo        | ThinkPad W541 20EFS01B09    | Notebook    | [8dd2c7497e](https://linux-hardware.org/?probe=8dd2c7497e) | Sep 13, 2021 |
| Dell          | Inspiron 3583               | Notebook    | [49b4db94c6](https://linux-hardware.org/?probe=49b4db94c6) | Sep 12, 2021 |
| HP            | Pavilion dv7                | Notebook    | [2fd3b811f6](https://linux-hardware.org/?probe=2fd3b811f6) | Sep 12, 2021 |
| Dell          | 0XCR8D A02                  | Desktop     | [9cb5ea4f4a](https://linux-hardware.org/?probe=9cb5ea4f4a) | Sep 11, 2021 |
| Dell          | XPS 15 9510                 | Notebook    | [1b80533734](https://linux-hardware.org/?probe=1b80533734) | Sep 11, 2021 |
| Dell          | XPS 15 9510                 | Notebook    | [4befd2306c](https://linux-hardware.org/?probe=4befd2306c) | Sep 11, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [5d7c3904aa](https://linux-hardware.org/?probe=5d7c3904aa) | Sep 09, 2021 |
| ASRock        | P55M Pro                    | Desktop     | [b6408718ee](https://linux-hardware.org/?probe=b6408718ee) | Sep 02, 2021 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [5cf3ed1411](https://linux-hardware.org/?probe=5cf3ed1411) | Aug 31, 2021 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [70585e2360](https://linux-hardware.org/?probe=70585e2360) | Aug 30, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [9c0457479f](https://linux-hardware.org/?probe=9c0457479f) | Aug 29, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [23b7937411](https://linux-hardware.org/?probe=23b7937411) | Aug 29, 2021 |
| Lenovo        | ThinkPad X240 20AMS5FJ00    | Notebook    | [9382443dc7](https://linux-hardware.org/?probe=9382443dc7) | Aug 27, 2021 |
| Google        | Relm                        | Notebook    | [12475037ed](https://linux-hardware.org/?probe=12475037ed) | Aug 27, 2021 |
| Google        | Relm                        | Notebook    | [36e7a1d7a1](https://linux-hardware.org/?probe=36e7a1d7a1) | Aug 26, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [61f6289d2c](https://linux-hardware.org/?probe=61f6289d2c) | Aug 26, 2021 |
| Lenovo        | ThinkPad X230 2325AN3       | Notebook    | [d6b5ef49af](https://linux-hardware.org/?probe=d6b5ef49af) | Aug 24, 2021 |
| Lenovo        | ThinkPad T470s 20HF0047U... | Notebook    | [900b0ce643](https://linux-hardware.org/?probe=900b0ce643) | Aug 24, 2021 |
| ASRock        | 980DE3/U3S3                 | Desktop     | [e8aadc0af0](https://linux-hardware.org/?probe=e8aadc0af0) | Aug 24, 2021 |
| HP            | ZBook 15 G6                 | Notebook    | [93ec0ceb52](https://linux-hardware.org/?probe=93ec0ceb52) | Aug 23, 2021 |
| Medion        | MS-7616                     | Desktop     | [cbd20c24d8](https://linux-hardware.org/?probe=cbd20c24d8) | Aug 20, 2021 |
| Lenovo        | ThinkPad E595 20NF001HMX    | Notebook    | [8e75269d33](https://linux-hardware.org/?probe=8e75269d33) | Aug 20, 2021 |
| Lenovo        | G550 2958                   | Notebook    | [5207c5584c](https://linux-hardware.org/?probe=5207c5584c) | Aug 16, 2021 |
| Lenovo        | G550 2958                   | Notebook    | [b7b363db20](https://linux-hardware.org/?probe=b7b363db20) | Aug 15, 2021 |
| HP            | ProBook 445 G7              | Notebook    | [e42e169a72](https://linux-hardware.org/?probe=e42e169a72) | Aug 15, 2021 |
| HP            | Notebook                    | Notebook    | [be1a21a391](https://linux-hardware.org/?probe=be1a21a391) | Aug 14, 2021 |
| HP            | 212B                        | Desktop     | [ee483c7463](https://linux-hardware.org/?probe=ee483c7463) | Aug 08, 2021 |
| ASUSTek       | P8B75-M                     | Desktop     | [4d29ffa0f7](https://linux-hardware.org/?probe=4d29ffa0f7) | Aug 03, 2021 |
| Lenovo        | 314F SDK0T08861 WIN 3305... | Desktop     | [4135f29492](https://linux-hardware.org/?probe=4135f29492) | Aug 02, 2021 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [59cd9e3edd](https://linux-hardware.org/?probe=59cd9e3edd) | Aug 01, 2021 |
| Pegatron      | 2AB6                        | Desktop     | [79dffb5346](https://linux-hardware.org/?probe=79dffb5346) | Jul 31, 2021 |
| GPD           | P2 MAX                      | Notebook    | [78f79b2790](https://linux-hardware.org/?probe=78f79b2790) | Jul 31, 2021 |
| Gigabyte      | P85-D3                      | Desktop     | [51f83ebd4a](https://linux-hardware.org/?probe=51f83ebd4a) | Jul 30, 2021 |
| Gigabyte      | H61M-USB3-B3                | Desktop     | [3c2020fbb6](https://linux-hardware.org/?probe=3c2020fbb6) | Jul 30, 2021 |
| Gigabyte      | H61M-USB3-B3                | Desktop     | [b3bbc6d937](https://linux-hardware.org/?probe=b3bbc6d937) | Jul 30, 2021 |
| ASUSTek       | GL702VM                     | Notebook    | [bb9d228646](https://linux-hardware.org/?probe=bb9d228646) | Jul 29, 2021 |
| Lenovo        | ThinkCentre Edge71 1577G... | Desktop     | [cf7f13e31c](https://linux-hardware.org/?probe=cf7f13e31c) | Jul 29, 2021 |
| ASRock        | H310CM-DVS                  | Desktop     | [5ae2994458](https://linux-hardware.org/?probe=5ae2994458) | Jul 28, 2021 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [c94593c3bd](https://linux-hardware.org/?probe=c94593c3bd) | Jul 25, 2021 |
| Medion        | Z370H4-EM                   | Desktop     | [f19570a630](https://linux-hardware.org/?probe=f19570a630) | Jul 24, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [a02dac8dff](https://linux-hardware.org/?probe=a02dac8dff) | Jul 23, 2021 |
| Shuttle       | FH67                        | Desktop     | [611a7c28dc](https://linux-hardware.org/?probe=611a7c28dc) | Jul 22, 2021 |
| Shuttle       | FH67                        | Desktop     | [3d3fb6c381](https://linux-hardware.org/?probe=3d3fb6c381) | Jul 22, 2021 |
| Lenovo        | ThinkPad X240 20AMS4P300    | Notebook    | [e52365f866](https://linux-hardware.org/?probe=e52365f866) | Jul 21, 2021 |
| ASRock        | 980DE3/U3S3                 | Desktop     | [9ca97016e0](https://linux-hardware.org/?probe=9ca97016e0) | Jul 21, 2021 |
| Lenovo        | ThinkPad X240 20AMS4P300    | Notebook    | [704fb2e1d1](https://linux-hardware.org/?probe=704fb2e1d1) | Jul 21, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [5fcfefa75a](https://linux-hardware.org/?probe=5fcfefa75a) | Jul 19, 2021 |
| Dell          | Latitude 7370               | Notebook    | [b10d4c18f2](https://linux-hardware.org/?probe=b10d4c18f2) | Jul 19, 2021 |
| Lenovo        | ThinkPad T460s 20F9003UM... | Notebook    | [7a03dbd869](https://linux-hardware.org/?probe=7a03dbd869) | Jul 17, 2021 |
| Lenovo        | ThinkPad T460s 20F9003UM... | Notebook    | [ce58f3f770](https://linux-hardware.org/?probe=ce58f3f770) | Jul 16, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [f0241430cc](https://linux-hardware.org/?probe=f0241430cc) | Jul 16, 2021 |
| Gigabyte      | Z68X-UD3-B3                 | Desktop     | [0c0d9cc784](https://linux-hardware.org/?probe=0c0d9cc784) | Jul 15, 2021 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | Notebook    | [a56195f1f1](https://linux-hardware.org/?probe=a56195f1f1) | Jul 13, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | Notebook    | [440841d04a](https://linux-hardware.org/?probe=440841d04a) | Jul 12, 2021 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | Notebook    | [3b106f1da0](https://linux-hardware.org/?probe=3b106f1da0) | Jul 07, 2021 |
| Lenovo        | ThinkPad X240 20AMS5FJ00    | Notebook    | [f8872c9e84](https://linux-hardware.org/?probe=f8872c9e84) | Jul 05, 2021 |
| AMI           | Cherry Trail CR             | Notebook    | [4e6f9ccc6c](https://linux-hardware.org/?probe=4e6f9ccc6c) | Jul 05, 2021 |
| DukaPC        | Notebook                    | Notebook    | [6d87054512](https://linux-hardware.org/?probe=6d87054512) | Jul 02, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [cca3e863f7](https://linux-hardware.org/?probe=cca3e863f7) | Jul 01, 2021 |
| HP            | ProBook 640 G3              | Notebook    | [c56b8f3ff1](https://linux-hardware.org/?probe=c56b8f3ff1) | Jun 29, 2021 |
| Timi          | TM1703                      | Notebook    | [bd3756811d](https://linux-hardware.org/?probe=bd3756811d) | Jun 26, 2021 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [2c4a16ea24](https://linux-hardware.org/?probe=2c4a16ea24) | Jun 25, 2021 |
| DukaPC        | Notebook                    | Notebook    | [c29d208cdf](https://linux-hardware.org/?probe=c29d208cdf) | Jun 24, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [208a9ee715](https://linux-hardware.org/?probe=208a9ee715) | Jun 23, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [86fce52939](https://linux-hardware.org/?probe=86fce52939) | Jun 23, 2021 |
| Lenovo        | ThinkPad T420 4236Y19       | Notebook    | [48927432b4](https://linux-hardware.org/?probe=48927432b4) | Jun 20, 2021 |
| Lenovo        | 3714 SDK0J40700 WIN 3258... | Desktop     | [ca43a33e1d](https://linux-hardware.org/?probe=ca43a33e1d) | Jun 18, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [d8ad69d368](https://linux-hardware.org/?probe=d8ad69d368) | Jun 15, 2021 |
| Lenovo        | Bantry CRB SDK0J40697 WI... | Desktop     | [4a0a83693b](https://linux-hardware.org/?probe=4a0a83693b) | Jun 14, 2021 |
| ASRock        | P55M Pro                    | Desktop     | [cac3198045](https://linux-hardware.org/?probe=cac3198045) | Jun 14, 2021 |
| Lenovo        | ThinkPad T440s 20ARS0Y70... | Notebook    | [5e57af6782](https://linux-hardware.org/?probe=5e57af6782) | Jun 11, 2021 |
| HP            | 212B                        | Desktop     | [b72ab2aea5](https://linux-hardware.org/?probe=b72ab2aea5) | Jun 09, 2021 |
| Lenovo        | ThinkPad T420 4236PFG       | Notebook    | [fa5abfccf8](https://linux-hardware.org/?probe=fa5abfccf8) | Jun 04, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [2927765712](https://linux-hardware.org/?probe=2927765712) | Jun 04, 2021 |
| ASRock        | P55M Pro                    | Desktop     | [b994c1917a](https://linux-hardware.org/?probe=b994c1917a) | Jun 03, 2021 |
| HP            | Compaq Presario CQ71        | Notebook    | [d4deb2b08d](https://linux-hardware.org/?probe=d4deb2b08d) | Jun 01, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [6056eac50c](https://linux-hardware.org/?probe=6056eac50c) | May 31, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [bd9fb4818b](https://linux-hardware.org/?probe=bd9fb4818b) | May 31, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [12fa3ffea5](https://linux-hardware.org/?probe=12fa3ffea5) | May 31, 2021 |
| Dell          | Latitude E6520              | Notebook    | [d1d0976880](https://linux-hardware.org/?probe=d1d0976880) | May 31, 2021 |
| Lenovo        | ThinkPad T400 647358G       | Notebook    | [b4f44d7932](https://linux-hardware.org/?probe=b4f44d7932) | May 29, 2021 |
| MSI           | Z87 MPOWER                  | Desktop     | [848def4822](https://linux-hardware.org/?probe=848def4822) | May 29, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [58d3740c30](https://linux-hardware.org/?probe=58d3740c30) | May 28, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [e0217f85a6](https://linux-hardware.org/?probe=e0217f85a6) | May 28, 2021 |
| Acer          | Aspire E5-553               | Notebook    | [70037bddcb](https://linux-hardware.org/?probe=70037bddcb) | May 27, 2021 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [f9358acedf](https://linux-hardware.org/?probe=f9358acedf) | May 27, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [787c1b3a8c](https://linux-hardware.org/?probe=787c1b3a8c) | May 26, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [92f19ca1e6](https://linux-hardware.org/?probe=92f19ca1e6) | May 25, 2021 |
| LAMINA        | T-1012B NORD                | Notebook    | [71e70e946a](https://linux-hardware.org/?probe=71e70e946a) | May 25, 2021 |
| ASUSTek       | NARRA2                      | Desktop     | [0b2cf24d70](https://linux-hardware.org/?probe=0b2cf24d70) | May 25, 2021 |
| LAMINA        | T-1012B NORD                | Notebook    | [9dc2932064](https://linux-hardware.org/?probe=9dc2932064) | May 24, 2021 |
| ASUSTek       | X553SA                      | Notebook    | [c470382d2a](https://linux-hardware.org/?probe=c470382d2a) | May 24, 2021 |
| ASUSTek       | X553SA                      | Notebook    | [31d6a914fd](https://linux-hardware.org/?probe=31d6a914fd) | May 24, 2021 |
| Acer          | Aspire E5-511               | Notebook    | [9edec55620](https://linux-hardware.org/?probe=9edec55620) | May 23, 2021 |
| Acer          | Aspire E5-511               | Notebook    | [e20c93a2c1](https://linux-hardware.org/?probe=e20c93a2c1) | May 23, 2021 |
| Lenovo        | ThinkPad X240 20AMS5FJ00    | Notebook    | [a9e4c7793b](https://linux-hardware.org/?probe=a9e4c7793b) | May 18, 2021 |
| Apple         | Mac-F2238AC8                | All in one  | [c5621d630d](https://linux-hardware.org/?probe=c5621d630d) | May 15, 2021 |
| Apple         | Mac-F2238AC8                | All in one  | [53e6447416](https://linux-hardware.org/?probe=53e6447416) | May 15, 2021 |
| eMachines     | E725                        | Notebook    | [329f8f580e](https://linux-hardware.org/?probe=329f8f580e) | May 14, 2021 |
| Medion        | MS-7646                     | Desktop     | [799be90f9c](https://linux-hardware.org/?probe=799be90f9c) | May 11, 2021 |
| ASUSTek       | K95VM                       | Notebook    | [58d4ed3c2b](https://linux-hardware.org/?probe=58d4ed3c2b) | May 10, 2021 |
| HP            | 15                          | Notebook    | [a13c097d59](https://linux-hardware.org/?probe=a13c097d59) | May 09, 2021 |
| HP            | 15                          | Notebook    | [c3cdcdab60](https://linux-hardware.org/?probe=c3cdcdab60) | May 09, 2021 |
| ASRock        | J4105-ITX                   | Desktop     | [2cb8135a58](https://linux-hardware.org/?probe=2cb8135a58) | May 08, 2021 |
| Alienware     | 17 R2                       | Notebook    | [a8470edc65](https://linux-hardware.org/?probe=a8470edc65) | May 06, 2021 |
| Intel         | NUC8i5INB K29935-404        | Mini pc     | [45b14891d4](https://linux-hardware.org/?probe=45b14891d4) | May 06, 2021 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [a8271c73ee](https://linux-hardware.org/?probe=a8271c73ee) | May 02, 2021 |
| ASUSTek       | G74Sx                       | Notebook    | [73c1eaa647](https://linux-hardware.org/?probe=73c1eaa647) | Apr 29, 2021 |
| Lenovo        | ThinkPad T520 4243PC2       | Notebook    | [915d41f361](https://linux-hardware.org/?probe=915d41f361) | Apr 29, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [e259d34a4c](https://linux-hardware.org/?probe=e259d34a4c) | Apr 28, 2021 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [9e0202e76a](https://linux-hardware.org/?probe=9e0202e76a) | Apr 27, 2021 |
| Lenovo        | ThinkPad T530 24295L4       | Notebook    | [e2f8b2beda](https://linux-hardware.org/?probe=e2f8b2beda) | Apr 25, 2021 |
| Lenovo        | ThinkPad T530 24295L4       | Notebook    | [684f1471b1](https://linux-hardware.org/?probe=684f1471b1) | Apr 23, 2021 |
| MiTAC         | PH10SI AAPH11SI-CI-700      | All in one  | [f27aee762c](https://linux-hardware.org/?probe=f27aee762c) | Apr 21, 2021 |
| Lenovo        | E31-80 80MX                 | Notebook    | [8aedfd9f4c](https://linux-hardware.org/?probe=8aedfd9f4c) | Apr 21, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [bd14a696eb](https://linux-hardware.org/?probe=bd14a696eb) | Apr 20, 2021 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [c0bd3fe537](https://linux-hardware.org/?probe=c0bd3fe537) | Apr 20, 2021 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [31cb6e83ed](https://linux-hardware.org/?probe=31cb6e83ed) | Apr 19, 2021 |
| Acer          | Veriton M275                | Desktop     | [246a662951](https://linux-hardware.org/?probe=246a662951) | Apr 17, 2021 |
| Lenovo        | ThinkPad T520 42434YG       | Notebook    | [8e0b4ee3a1](https://linux-hardware.org/?probe=8e0b4ee3a1) | Apr 17, 2021 |
| Lenovo        | ThinkPad X220 4291SVC       | Notebook    | [49e1959064](https://linux-hardware.org/?probe=49e1959064) | Apr 16, 2021 |
| Lenovo        | ThinkPad X220 4291SVC       | Notebook    | [b2853266e8](https://linux-hardware.org/?probe=b2853266e8) | Apr 15, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [cd772af567](https://linux-hardware.org/?probe=cd772af567) | Apr 14, 2021 |
| Gigabyte      | EP35-DS4                    | Desktop     | [e37cf6fc8d](https://linux-hardware.org/?probe=e37cf6fc8d) | Apr 12, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [4b127c0ba4](https://linux-hardware.org/?probe=4b127c0ba4) | Apr 11, 2021 |
| HP            | Laptop 15-da1xxx            | Notebook    | [a844e710cc](https://linux-hardware.org/?probe=a844e710cc) | Apr 09, 2021 |
| Lenovo        | ThinkPad T60 20076RG        | Notebook    | [aa3ea77acf](https://linux-hardware.org/?probe=aa3ea77acf) | Apr 08, 2021 |
| MSI           | Z87 MPOWER                  | Desktop     | [ff6aa3811c](https://linux-hardware.org/?probe=ff6aa3811c) | Apr 08, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [09cf1ed052](https://linux-hardware.org/?probe=09cf1ed052) | Apr 08, 2021 |
| HP            | G72                         | Notebook    | [2ab4eb5fcd](https://linux-hardware.org/?probe=2ab4eb5fcd) | Apr 05, 2021 |
| Dell          | Latitude 5175               | Tablet      | [36ce9ad0c9](https://linux-hardware.org/?probe=36ce9ad0c9) | Apr 02, 2021 |
| Dell          | Latitude 5175               | Tablet      | [4fa01ccee6](https://linux-hardware.org/?probe=4fa01ccee6) | Apr 02, 2021 |
| ASRock        | Z270 Pro4                   | Desktop     | [b90dd1b4d2](https://linux-hardware.org/?probe=b90dd1b4d2) | Apr 02, 2021 |
| Medion        | MS-7797                     | Desktop     | [947bc894eb](https://linux-hardware.org/?probe=947bc894eb) | Apr 01, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [757d1d0707](https://linux-hardware.org/?probe=757d1d0707) | Mar 31, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [eb1782ad49](https://linux-hardware.org/?probe=eb1782ad49) | Mar 31, 2021 |
| Lenovo        | HASWELLREFRESHDT NO DPK     | All in one  | [4c3dd6a28b](https://linux-hardware.org/?probe=4c3dd6a28b) | Mar 25, 2021 |
| Lenovo        | HASWELLREFRESHDT NO DPK     | All in one  | [344f718da0](https://linux-hardware.org/?probe=344f718da0) | Mar 25, 2021 |
| ASUSTek       | K95VM                       | Notebook    | [81a01884d2](https://linux-hardware.org/?probe=81a01884d2) | Mar 24, 2021 |
| Dell          | 0CU409                      | Desktop     | [53a8c28aed](https://linux-hardware.org/?probe=53a8c28aed) | Mar 24, 2021 |
| Lenovo        | ThinkPad W520 4284Y54       | Notebook    | [8d564e495b](https://linux-hardware.org/?probe=8d564e495b) | Mar 23, 2021 |
| Toshiba       | Satellite L350D             | Notebook    | [b083513b72](https://linux-hardware.org/?probe=b083513b72) | Mar 23, 2021 |
| Acer          | Aspire E5-553               | Notebook    | [0c21dc1b96](https://linux-hardware.org/?probe=0c21dc1b96) | Mar 19, 2021 |
| Acer          | Aspire XC-605               | Desktop     | [f8ad366bd9](https://linux-hardware.org/?probe=f8ad366bd9) | Mar 19, 2021 |
| HP            | Pavilion dm1                | Notebook    | [438cf03315](https://linux-hardware.org/?probe=438cf03315) | Mar 18, 2021 |
| Lenovo        | Yoga 700-14ISK 80QD         | Notebook    | [7e7a4bc992](https://linux-hardware.org/?probe=7e7a4bc992) | Mar 18, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [54288c23c9](https://linux-hardware.org/?probe=54288c23c9) | Mar 18, 2021 |
| ECS           | Nettle3                     | Desktop     | [f7ec16d7e7](https://linux-hardware.org/?probe=f7ec16d7e7) | Mar 16, 2021 |
| Lenovo        | ThinkPad T480s 20L8S4T80... | Notebook    | [1b8a078a19](https://linux-hardware.org/?probe=1b8a078a19) | Mar 16, 2021 |
| HP            | EliteBook 830 G5            | Notebook    | [248eb896a0](https://linux-hardware.org/?probe=248eb896a0) | Mar 15, 2021 |
| HP            | 3032h                       | Desktop     | [79b0bf2416](https://linux-hardware.org/?probe=79b0bf2416) | Mar 15, 2021 |
| HP            | Compaq Presario CQ60        | Notebook    | [e4613a6f75](https://linux-hardware.org/?probe=e4613a6f75) | Mar 15, 2021 |
| Dell          | Latitude E5250              | Notebook    | [22067e0909](https://linux-hardware.org/?probe=22067e0909) | Mar 13, 2021 |
| Dell          | Latitude E5250              | Notebook    | [df9d913f0f](https://linux-hardware.org/?probe=df9d913f0f) | Mar 13, 2021 |
| HP            | Pavilion dv9700             | Notebook    | [f55ec4dd18](https://linux-hardware.org/?probe=f55ec4dd18) | Mar 11, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [865e070587](https://linux-hardware.org/?probe=865e070587) | Mar 10, 2021 |
| Dell          | Latitude E5250              | Notebook    | [78f0a24d9a](https://linux-hardware.org/?probe=78f0a24d9a) | Mar 07, 2021 |
| Acer          | Aspire E5-575G              | Notebook    | [18240d24d8](https://linux-hardware.org/?probe=18240d24d8) | Mar 06, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [9ebf280981](https://linux-hardware.org/?probe=9ebf280981) | Mar 05, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [efa91095ab](https://linux-hardware.org/?probe=efa91095ab) | Mar 05, 2021 |
| Toshiba       | Satellite L350D             | Notebook    | [ef8a29af20](https://linux-hardware.org/?probe=ef8a29af20) | Mar 05, 2021 |
| ASUSTek       | M4N75TD                     | Desktop     | [9daf1b6529](https://linux-hardware.org/?probe=9daf1b6529) | Feb 28, 2021 |
| Acer          | Aspire E5-553               | Notebook    | [74e6da0017](https://linux-hardware.org/?probe=74e6da0017) | Feb 27, 2021 |
| ASUSTek       | P5P43TD                     | Desktop     | [3a2604a18a](https://linux-hardware.org/?probe=3a2604a18a) | Feb 27, 2021 |
| HP            | 1998                        | Desktop     | [43bd925171](https://linux-hardware.org/?probe=43bd925171) | Feb 27, 2021 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [66ce820cff](https://linux-hardware.org/?probe=66ce820cff) | Feb 25, 2021 |
| HP            | 630                         | Notebook    | [6803747e34](https://linux-hardware.org/?probe=6803747e34) | Feb 22, 2021 |
| HP            | 630                         | Notebook    | [8b04fe81aa](https://linux-hardware.org/?probe=8b04fe81aa) | Feb 22, 2021 |
| ASRock        | QC5000-ITX/WiFi             | Desktop     | [d321b1eb90](https://linux-hardware.org/?probe=d321b1eb90) | Feb 21, 2021 |
| ASRock        | Z270 Pro4                   | Desktop     | [7114de29ed](https://linux-hardware.org/?probe=7114de29ed) | Feb 20, 2021 |
| Medion        | MS-7797                     | Desktop     | [3c4d9332e4](https://linux-hardware.org/?probe=3c4d9332e4) | Feb 19, 2021 |
| Lenovo        | ThinkPad T61 7661W1D        | Notebook    | [6db91fdd34](https://linux-hardware.org/?probe=6db91fdd34) | Feb 17, 2021 |
| Lenovo        | 3000 G530 444622G           | Notebook    | [3ef99e25df](https://linux-hardware.org/?probe=3ef99e25df) | Feb 16, 2021 |
| Supermicro    | C9X299-PG300F               | Server      | [43a2d3f891](https://linux-hardware.org/?probe=43a2d3f891) | Feb 15, 2021 |
| MSI           | B150M PRO-VH                | Desktop     | [255e61b850](https://linux-hardware.org/?probe=255e61b850) | Feb 13, 2021 |
| Lenovo        | ThinkPad X240 20AMA2AE00    | Notebook    | [2730f6215a](https://linux-hardware.org/?probe=2730f6215a) | Feb 12, 2021 |
| Medion        | MS-7797                     | Desktop     | [7e6811c842](https://linux-hardware.org/?probe=7e6811c842) | Feb 10, 2021 |
| Dell          | XPS 13 9360                 | Notebook    | [564f71d6f3](https://linux-hardware.org/?probe=564f71d6f3) | Feb 10, 2021 |
| Medion        | MS-7797                     | Desktop     | [394c3c87f4](https://linux-hardware.org/?probe=394c3c87f4) | Feb 10, 2021 |
| Lenovo        | Yoga 720-13IKB 81C3         | Convertible | [944524204c](https://linux-hardware.org/?probe=944524204c) | Feb 09, 2021 |
| ASRock        | B550M-ITX/ac                | Desktop     | [909d040ae4](https://linux-hardware.org/?probe=909d040ae4) | Feb 07, 2021 |
| Acer          | Aspire E5-553               | Notebook    | [ab7532985d](https://linux-hardware.org/?probe=ab7532985d) | Feb 05, 2021 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [ed806c00b2](https://linux-hardware.org/?probe=ed806c00b2) | Feb 04, 2021 |
| HP            | EliteBook 2560p             | Notebook    | [f741035d0d](https://linux-hardware.org/?probe=f741035d0d) | Feb 02, 2021 |
| Medion        | MS-7708                     | Desktop     | [53ba901c28](https://linux-hardware.org/?probe=53ba901c28) | Feb 01, 2021 |
| Medion        | MS-7708                     | Desktop     | [8ef1638192](https://linux-hardware.org/?probe=8ef1638192) | Feb 01, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [4e1301a818](https://linux-hardware.org/?probe=4e1301a818) | Feb 01, 2021 |
| Lenovo        | ThinkServer TS140           | Desktop     | [8f911a91ca](https://linux-hardware.org/?probe=8f911a91ca) | Jan 29, 2021 |
| HP            | EliteBook 840 G5            | Notebook    | [19ef5f3adb](https://linux-hardware.org/?probe=19ef5f3adb) | Jan 29, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [34257c05a5](https://linux-hardware.org/?probe=34257c05a5) | Jan 27, 2021 |
| Dell          | Latitude E7440              | Notebook    | [ee2c17a895](https://linux-hardware.org/?probe=ee2c17a895) | Jan 26, 2021 |
| MiTAC         | PH10SI AAPH11SI-CI-700      | All in one  | [d67180ce56](https://linux-hardware.org/?probe=d67180ce56) | Jan 25, 2021 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [964b7c1b1f](https://linux-hardware.org/?probe=964b7c1b1f) | Jan 23, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [82da77953a](https://linux-hardware.org/?probe=82da77953a) | Jan 19, 2021 |
| Dell          | Latitude 5500               | Notebook    | [d7e06bd87b](https://linux-hardware.org/?probe=d7e06bd87b) | Jan 18, 2021 |
| Gigabyte      | GA-780T-D3L                 | Desktop     | [2f2ede94cb](https://linux-hardware.org/?probe=2f2ede94cb) | Jan 17, 2021 |
| Dell          | Latitude 5500               | Notebook    | [f40a2d50bc](https://linux-hardware.org/?probe=f40a2d50bc) | Jan 16, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [8fabd80d9e](https://linux-hardware.org/?probe=8fabd80d9e) | Jan 16, 2021 |
| Quanta        | MW1/HW1                     | Notebook    | [ebab0a47f8](https://linux-hardware.org/?probe=ebab0a47f8) | Jan 16, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [fc3f785613](https://linux-hardware.org/?probe=fc3f785613) | Jan 15, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [16e0cedde4](https://linux-hardware.org/?probe=16e0cedde4) | Jan 12, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [beb8fbc5b4](https://linux-hardware.org/?probe=beb8fbc5b4) | Jan 12, 2021 |
| Lenovo        | ThinkPad P52 20M9001GMX     | Notebook    | [ffdee2c6e0](https://linux-hardware.org/?probe=ffdee2c6e0) | Jan 11, 2021 |
| Dell          | XPS 13 9300                 | Notebook    | [229b46a693](https://linux-hardware.org/?probe=229b46a693) | Jan 10, 2021 |
| Lenovo        | ThinkPad P53 20QNCTO1WW     | Notebook    | [fa963386d8](https://linux-hardware.org/?probe=fa963386d8) | Jan 07, 2021 |
| NEXCOM        | NDIS B322                   | Desktop     | [c2789ca746](https://linux-hardware.org/?probe=c2789ca746) | Jan 06, 2021 |
| Toshiba       | Satellite L40               | Notebook    | [bd26bbbe43](https://linux-hardware.org/?probe=bd26bbbe43) | Jan 06, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [ba97feecf2](https://linux-hardware.org/?probe=ba97feecf2) | Jan 05, 2021 |
| Lenovo        | G570 4334                   | Notebook    | [c643363b80](https://linux-hardware.org/?probe=c643363b80) | Jan 03, 2021 |
| Intel         | NUC6i7KYB H90766-408        | Mini pc     | [400efe971d](https://linux-hardware.org/?probe=400efe971d) | Jan 02, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [2ed1a3283e](https://linux-hardware.org/?probe=2ed1a3283e) | Jan 02, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [c0c38c5aee](https://linux-hardware.org/?probe=c0c38c5aee) | Dec 30, 2020 |
| Gigabyte      | B550M DS3H                  | Desktop     | [16d30d3356](https://linux-hardware.org/?probe=16d30d3356) | Dec 30, 2020 |
| Gigabyte      | B550M DS3H                  | Desktop     | [944fc761f4](https://linux-hardware.org/?probe=944fc761f4) | Dec 30, 2020 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [65fe7eb049](https://linux-hardware.org/?probe=65fe7eb049) | Dec 30, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [c3f9fc25d4](https://linux-hardware.org/?probe=c3f9fc25d4) | Dec 29, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [dbc2669fc0](https://linux-hardware.org/?probe=dbc2669fc0) | Dec 28, 2020 |
| ASUSTek       | Z97-K                       | Desktop     | [3eacdc5965](https://linux-hardware.org/?probe=3eacdc5965) | Dec 28, 2020 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [f514e54057](https://linux-hardware.org/?probe=f514e54057) | Dec 28, 2020 |
| ASUSTek       | PU401LAC                    | Notebook    | [c5bf49eabf](https://linux-hardware.org/?probe=c5bf49eabf) | Dec 26, 2020 |
| MSI           | B150M PRO-VH                | Desktop     | [f225de5ed7](https://linux-hardware.org/?probe=f225de5ed7) | Dec 25, 2020 |
| MSI           | B150M PRO-VH                | Desktop     | [6971a673ec](https://linux-hardware.org/?probe=6971a673ec) | Dec 25, 2020 |
| HP            | EliteBook 850 G5            | Notebook    | [ce2a32dd24](https://linux-hardware.org/?probe=ce2a32dd24) | Dec 22, 2020 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [3e419467e2](https://linux-hardware.org/?probe=3e419467e2) | Dec 22, 2020 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [87c08ecbb6](https://linux-hardware.org/?probe=87c08ecbb6) | Dec 22, 2020 |
| Notebook      | W54_55SU1,SUW               | Notebook    | [52e86fd2a9](https://linux-hardware.org/?probe=52e86fd2a9) | Dec 20, 2020 |
| Lenovo        | ThinkPad T490s 20NX001PM... | Notebook    | [af7d2d4eb5](https://linux-hardware.org/?probe=af7d2d4eb5) | Dec 20, 2020 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [14a84d3948](https://linux-hardware.org/?probe=14a84d3948) | Dec 20, 2020 |
| Lenovo        | ThinkPad T520 4243W54       | Notebook    | [15862aca5c](https://linux-hardware.org/?probe=15862aca5c) | Dec 20, 2020 |
| Lenovo        | ThinkPad X260 20F5S31G00    | Notebook    | [01b87f6602](https://linux-hardware.org/?probe=01b87f6602) | Dec 18, 2020 |
| Lenovo        | Unknown                     | Notebook    | [92b19a0db9](https://linux-hardware.org/?probe=92b19a0db9) | Dec 18, 2020 |
| Dell          | Latitude E7270              | Notebook    | [bac2c2820f](https://linux-hardware.org/?probe=bac2c2820f) | Dec 17, 2020 |
| Acer          | Aspire Z5710                | All in one  | [96c29c6c68](https://linux-hardware.org/?probe=96c29c6c68) | Dec 16, 2020 |
| Lenovo        | ThinkPad X220 4291SVC       | Notebook    | [5dfa78d268](https://linux-hardware.org/?probe=5dfa78d268) | Dec 15, 2020 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | Desktop     | [13d6a7172d](https://linux-hardware.org/?probe=13d6a7172d) | Dec 15, 2020 |
| Gigabyte      | J3455N-D3H                  | Desktop     | [a9a1ba9727](https://linux-hardware.org/?probe=a9a1ba9727) | Dec 13, 2020 |
| HP            | ProBook 650 G5              | Notebook    | [56c46edc3f](https://linux-hardware.org/?probe=56c46edc3f) | Dec 13, 2020 |
| HP            | ProBook 650 G5              | Notebook    | [a035f76fcb](https://linux-hardware.org/?probe=a035f76fcb) | Dec 12, 2020 |
| Acer          | Extensa 2519                | Notebook    | [17bdd3b68f](https://linux-hardware.org/?probe=17bdd3b68f) | Dec 10, 2020 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Desktop     | [968983910f](https://linux-hardware.org/?probe=968983910f) | Dec 08, 2020 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [b3c78e0e70](https://linux-hardware.org/?probe=b3c78e0e70) | Dec 07, 2020 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [1a5eee726d](https://linux-hardware.org/?probe=1a5eee726d) | Dec 05, 2020 |
| Raspberry ... | Raspberry Pi                | Soc         | [f677339c7a](https://linux-hardware.org/?probe=f677339c7a) | Dec 04, 2020 |
| MSI           | MPG Z490 GAMING PLUS        | Desktop     | [95b94bfe02](https://linux-hardware.org/?probe=95b94bfe02) | Dec 04, 2020 |
| Lenovo        | ThinkPad X220 4291SVC       | Notebook    | [e9f3972862](https://linux-hardware.org/?probe=e9f3972862) | Dec 04, 2020 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | Notebook    | [f98c566bb6](https://linux-hardware.org/?probe=f98c566bb6) | Dec 03, 2020 |
| MSI           | X570-A PRO                  | Desktop     | [0c57860179](https://linux-hardware.org/?probe=0c57860179) | Dec 02, 2020 |
| Medion        | B360H4-EM V1.0              | Desktop     | [718acb9fc0](https://linux-hardware.org/?probe=718acb9fc0) | Dec 02, 2020 |
| Lenovo        | ThinkPad X220 4291SVC       | Notebook    | [ff051ee214](https://linux-hardware.org/?probe=ff051ee214) | Dec 01, 2020 |
| MSI           | B150M PRO-VH                | Desktop     | [ed280391f2](https://linux-hardware.org/?probe=ed280391f2) | Nov 30, 2020 |
| Dell          | Latitude E6540              | Notebook    | [5a0fbaa262](https://linux-hardware.org/?probe=5a0fbaa262) | Nov 28, 2020 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [f49b6c5048](https://linux-hardware.org/?probe=f49b6c5048) | Nov 27, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [8b31225bd7](https://linux-hardware.org/?probe=8b31225bd7) | Nov 27, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [7fd7e42e53](https://linux-hardware.org/?probe=7fd7e42e53) | Nov 25, 2020 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [ce4048d43f](https://linux-hardware.org/?probe=ce4048d43f) | Nov 24, 2020 |
| Apple         | MacBookPro7,1               | Notebook    | [ad6bb1f253](https://linux-hardware.org/?probe=ad6bb1f253) | Nov 24, 2020 |
| Lenovo        | ThinkPad P52 20M9001MMD     | Notebook    | [72ba2ae6cb](https://linux-hardware.org/?probe=72ba2ae6cb) | Nov 19, 2020 |
| Acer          | Aspire V3-575G              | Notebook    | [56c2638b77](https://linux-hardware.org/?probe=56c2638b77) | Nov 18, 2020 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [f31d348678](https://linux-hardware.org/?probe=f31d348678) | Nov 18, 2020 |
| Dell          | System XPS L321X            | Notebook    | [3fb9a4373c](https://linux-hardware.org/?probe=3fb9a4373c) | Nov 18, 2020 |
| Lenovo        | ThinkPad T530 24292VG       | Notebook    | [3460614c7f](https://linux-hardware.org/?probe=3460614c7f) | Nov 15, 2020 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Desktop     | [9845e5eb1e](https://linux-hardware.org/?probe=9845e5eb1e) | Nov 15, 2020 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Desktop     | [91207c72e3](https://linux-hardware.org/?probe=91207c72e3) | Nov 15, 2020 |
| Dell          | Inspiron 5400 2n1           | Convertible | [2758011d5e](https://linux-hardware.org/?probe=2758011d5e) | Nov 12, 2020 |
| Acer          | MCP73VE NVIDIA MCP73        | Desktop     | [d2afbbe9f9](https://linux-hardware.org/?probe=d2afbbe9f9) | Nov 10, 2020 |
| Lenovo        | ThinkPad W541 20EFS01B09    | Notebook    | [ee5da1d9b0](https://linux-hardware.org/?probe=ee5da1d9b0) | Nov 10, 2020 |
| Lenovo        | ThinkPad X301 2776LEG       | Notebook    | [2c4aa61663](https://linux-hardware.org/?probe=2c4aa61663) | Nov 09, 2020 |
| Dell          | XPS 13 9370                 | Notebook    | [b75b281fee](https://linux-hardware.org/?probe=b75b281fee) | Nov 08, 2020 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [de9ea1422c](https://linux-hardware.org/?probe=de9ea1422c) | Nov 08, 2020 |
| Lenovo        | ThinkCentre Edge72 3484F... | Desktop     | [8864ed7825](https://linux-hardware.org/?probe=8864ed7825) | Nov 08, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [1698bf3366](https://linux-hardware.org/?probe=1698bf3366) | Nov 07, 2020 |
| HP            | EliteBook 820 G3            | Notebook    | [e34831e959](https://linux-hardware.org/?probe=e34831e959) | Nov 07, 2020 |
| Dell          | XPS 15 9570                 | Notebook    | [bb40872a6b](https://linux-hardware.org/?probe=bb40872a6b) | Nov 05, 2020 |
| HP            | ProBook 4720s               | Notebook    | [acb46376ad](https://linux-hardware.org/?probe=acb46376ad) | Nov 04, 2020 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [3c1cda3225](https://linux-hardware.org/?probe=3c1cda3225) | Nov 03, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | Notebook    | [d65f8070e0](https://linux-hardware.org/?probe=d65f8070e0) | Nov 03, 2020 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [54f14d0d27](https://linux-hardware.org/?probe=54f14d0d27) | Nov 02, 2020 |
| HP            | Compaq 8510p                | Notebook    | [587f5db4a7](https://linux-hardware.org/?probe=587f5db4a7) | Nov 02, 2020 |
| Dell          | XPS 15 9560                 | Notebook    | [5e06a37540](https://linux-hardware.org/?probe=5e06a37540) | Nov 01, 2020 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [1213098826](https://linux-hardware.org/?probe=1213098826) | Oct 30, 2020 |
| ASRock        | Z170 OC Formula             | Desktop     | [067d0719a1](https://linux-hardware.org/?probe=067d0719a1) | Oct 30, 2020 |
| ASRock        | TRX40 Creator               | Desktop     | [3b1961ec14](https://linux-hardware.org/?probe=3b1961ec14) | Oct 30, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [de02478ef0](https://linux-hardware.org/?probe=de02478ef0) | Oct 29, 2020 |
| Lenovo        | E31-80 80MX                 | Notebook    | [d56dacea36](https://linux-hardware.org/?probe=d56dacea36) | Oct 29, 2020 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [2e111f0b77](https://linux-hardware.org/?probe=2e111f0b77) | Oct 29, 2020 |
| Razer         | Blade                       | Notebook    | [7aef75c2c6](https://linux-hardware.org/?probe=7aef75c2c6) | Oct 28, 2020 |
| Dell          | Vostro 3558                 | Notebook    | [eda9a94c60](https://linux-hardware.org/?probe=eda9a94c60) | Oct 28, 2020 |
| Dell          | 0CT017                      | Desktop     | [4f36a920b3](https://linux-hardware.org/?probe=4f36a920b3) | Oct 26, 2020 |
| ASRock        | B450M Pro4                  | Desktop     | [375a230939](https://linux-hardware.org/?probe=375a230939) | Oct 26, 2020 |
| Acer          | Nitro AN515-53              | Notebook    | [08235cd1ad](https://linux-hardware.org/?probe=08235cd1ad) | Oct 25, 2020 |
| Acer          | Nitro AN515-53              | Notebook    | [80a32fe04b](https://linux-hardware.org/?probe=80a32fe04b) | Oct 24, 2020 |
| Dell          | Vostro 3558                 | Notebook    | [e22529c904](https://linux-hardware.org/?probe=e22529c904) | Oct 23, 2020 |
| Apple         | MacBookPro5,5               | Notebook    | [b7c6f0c157](https://linux-hardware.org/?probe=b7c6f0c157) | Oct 22, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [cbd374b1d9](https://linux-hardware.org/?probe=cbd374b1d9) | Oct 22, 2020 |
| Toshiba       | Satellite L40               | Notebook    | [3d02e46571](https://linux-hardware.org/?probe=3d02e46571) | Oct 22, 2020 |
| HP            | EliteBook 850 G5            | Notebook    | [1a2d14ded4](https://linux-hardware.org/?probe=1a2d14ded4) | Oct 20, 2020 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [b7a16467ac](https://linux-hardware.org/?probe=b7a16467ac) | Oct 19, 2020 |
| HP            | Pavilion dv6                | Notebook    | [6fd2a79436](https://linux-hardware.org/?probe=6fd2a79436) | Oct 18, 2020 |
| ASUSTek       | P5QL-VM EPU                 | Desktop     | [97ae9ff8fd](https://linux-hardware.org/?probe=97ae9ff8fd) | Oct 16, 2020 |
| Toshiba       | Satellite P50-A-11J         | Notebook    | [720f19d566](https://linux-hardware.org/?probe=720f19d566) | Oct 15, 2020 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [afee01c14d](https://linux-hardware.org/?probe=afee01c14d) | Oct 11, 2020 |
| Lenovo        | ThinkPad T420s 4174W2P      | Notebook    | [c8eacff838](https://linux-hardware.org/?probe=c8eacff838) | Oct 10, 2020 |
| Acer          | Aspire V5-573               | Notebook    | [20453e8620](https://linux-hardware.org/?probe=20453e8620) | Oct 10, 2020 |
| Acer          | Aspire V5-573               | Notebook    | [eee8f03871](https://linux-hardware.org/?probe=eee8f03871) | Oct 10, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | Notebook    | [4ffeac234f](https://linux-hardware.org/?probe=4ffeac234f) | Oct 09, 2020 |
| Acer          | Nitro AN515-53              | Notebook    | [fe2889ef02](https://linux-hardware.org/?probe=fe2889ef02) | Oct 08, 2020 |
| Gigabyte      | Z390 AORUS MASTER-CF        | Desktop     | [734e996f73](https://linux-hardware.org/?probe=734e996f73) | Oct 07, 2020 |
| Gigabyte      | Z390 AORUS MASTER-CF        | Desktop     | [ce1874a3be](https://linux-hardware.org/?probe=ce1874a3be) | Oct 07, 2020 |
| ASRock        | Z170 Extreme4               | Desktop     | [39a631ad3c](https://linux-hardware.org/?probe=39a631ad3c) | Oct 06, 2020 |
| Pegatron      | 2AD5                        | Desktop     | [4d341edca9](https://linux-hardware.org/?probe=4d341edca9) | Oct 05, 2020 |
| Lenovo        | ThinkPad T430s 23564H3      | Notebook    | [bea20b3463](https://linux-hardware.org/?probe=bea20b3463) | Oct 04, 2020 |
| Acer          | Aspire 7551                 | Notebook    | [0524a7f258](https://linux-hardware.org/?probe=0524a7f258) | Oct 04, 2020 |
| Acer          | Aspire VN7-792G             | Notebook    | [908eea39dd](https://linux-hardware.org/?probe=908eea39dd) | Oct 04, 2020 |
| Acer          | Nitro AN515-53              | Notebook    | [a1d00d9bc3](https://linux-hardware.org/?probe=a1d00d9bc3) | Oct 03, 2020 |
| Acer          | Nitro AN515-53              | Notebook    | [be2aafbbae](https://linux-hardware.org/?probe=be2aafbbae) | Oct 03, 2020 |
| HP            | ProBook 650 G2              | Notebook    | [f04b6dbdc5](https://linux-hardware.org/?probe=f04b6dbdc5) | Oct 02, 2020 |
| HP            | ProBook 650 G2              | Notebook    | [7b826236e8](https://linux-hardware.org/?probe=7b826236e8) | Oct 02, 2020 |
| Lenovo        | Yoga C740-15IML 81TD        | Convertible | [018b5f5ee7](https://linux-hardware.org/?probe=018b5f5ee7) | Oct 02, 2020 |
| MSI           | Z87 MPOWER                  | Desktop     | [c361400ba5](https://linux-hardware.org/?probe=c361400ba5) | Oct 02, 2020 |
| Lenovo        | ThinkPad P51 20HH001QMD     | Notebook    | [9a69eca48e](https://linux-hardware.org/?probe=9a69eca48e) | Oct 01, 2020 |
| HP            | 3398                        | Desktop     | [95d758781c](https://linux-hardware.org/?probe=95d758781c) | Oct 01, 2020 |
| Acer          | AOD270                      | Notebook    | [4d7f40e97b](https://linux-hardware.org/?probe=4d7f40e97b) | Sep 30, 2020 |
| Lenovo        | 3000 N200 0769B6G           | Notebook    | [7e9967fb0e](https://linux-hardware.org/?probe=7e9967fb0e) | Sep 30, 2020 |
| ASUSTek       | Z170-DELUXE                 | Desktop     | [619ac1f764](https://linux-hardware.org/?probe=619ac1f764) | Sep 30, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [09b275ac93](https://linux-hardware.org/?probe=09b275ac93) | Sep 30, 2020 |
| Lenovo        | ThinkPad P51 20HH001QMD     | Notebook    | [3b51f51354](https://linux-hardware.org/?probe=3b51f51354) | Sep 29, 2020 |
| Notebook      | W54_55SU1,SUW               | Notebook    | [8616e28654](https://linux-hardware.org/?probe=8616e28654) | Sep 29, 2020 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [1fd3e30c8e](https://linux-hardware.org/?probe=1fd3e30c8e) | Sep 28, 2020 |
| ASUSTek       | ZenBook UX434IQ_UM433IQ     | Notebook    | [a3846db026](https://linux-hardware.org/?probe=a3846db026) | Sep 26, 2020 |
| Lenovo        | G710 20252                  | Notebook    | [6d3ef693db](https://linux-hardware.org/?probe=6d3ef693db) | Sep 23, 2020 |
| Lenovo        | ThinkCentre M81 5032W3M     | Desktop     | [b6dc69bcc6](https://linux-hardware.org/?probe=b6dc69bcc6) | Sep 23, 2020 |
| HP            | Pavilion Sleekbook 15       | Notebook    | [d5217dd737](https://linux-hardware.org/?probe=d5217dd737) | Sep 20, 2020 |
| Google        | Liara                       | Notebook    | [e6434b38e5](https://linux-hardware.org/?probe=e6434b38e5) | Sep 16, 2020 |
| HP            | 620                         | Notebook    | [3cd40bde20](https://linux-hardware.org/?probe=3cd40bde20) | Sep 11, 2020 |
| MSI           | PS42 8RB                    | Notebook    | [1f2fba4e2e](https://linux-hardware.org/?probe=1f2fba4e2e) | Sep 11, 2020 |
| MSI           | PS42 8RB                    | Notebook    | [46f7d12d9e](https://linux-hardware.org/?probe=46f7d12d9e) | Sep 11, 2020 |
| HP            | EliteBook 850 G5            | Notebook    | [826772015a](https://linux-hardware.org/?probe=826772015a) | Sep 09, 2020 |
| LG Electro... | 17Z90N-V.AA77G              | Notebook    | [eaeb99f180](https://linux-hardware.org/?probe=eaeb99f180) | Sep 06, 2020 |
| Apple         | MacBookPro10,1              | Notebook    | [3d676f563d](https://linux-hardware.org/?probe=3d676f563d) | Sep 06, 2020 |
| Lenovo        | ThinkPad X230 2325W3J       | Notebook    | [b076277c46](https://linux-hardware.org/?probe=b076277c46) | Sep 05, 2020 |
| Lenovo        | ThinkPad X240 20AMS39B00    | Notebook    | [b2f7ace5e9](https://linux-hardware.org/?probe=b2f7ace5e9) | Sep 05, 2020 |
| ASUSTek       | ROG STRIX X370-F GAMING     | Desktop     | [4298ad10c2](https://linux-hardware.org/?probe=4298ad10c2) | Sep 05, 2020 |
| ASUSTek       | ROG STRIX X370-F GAMING     | Desktop     | [d98e57a21a](https://linux-hardware.org/?probe=d98e57a21a) | Sep 05, 2020 |
| Notebook      | W35xSTQ_370ST               | Notebook    | [69960189a7](https://linux-hardware.org/?probe=69960189a7) | Sep 04, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [9cd1bda591](https://linux-hardware.org/?probe=9cd1bda591) | Sep 04, 2020 |
| Lenovo        | ThinkPad X220 42912XG       | Notebook    | [392b8d8877](https://linux-hardware.org/?probe=392b8d8877) | Sep 04, 2020 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [74a552046a](https://linux-hardware.org/?probe=74a552046a) | Sep 02, 2020 |
| Toshiba       | Satellite L755D             | Notebook    | [e3aa57d80d](https://linux-hardware.org/?probe=e3aa57d80d) | Aug 30, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [742d3f49f0](https://linux-hardware.org/?probe=742d3f49f0) | Aug 30, 2020 |
| HP            | 620                         | Notebook    | [2abb876aa3](https://linux-hardware.org/?probe=2abb876aa3) | Aug 27, 2020 |
| Purism        | Librem 13 v2                | Notebook    | [23cd34d2f6](https://linux-hardware.org/?probe=23cd34d2f6) | Aug 27, 2020 |
| HP            | Pavilion dm1                | Notebook    | [39154c83b0](https://linux-hardware.org/?probe=39154c83b0) | Aug 27, 2020 |
| Acer          | NC-SF314-51-56Y4            | Notebook    | [0627a672e7](https://linux-hardware.org/?probe=0627a672e7) | Aug 27, 2020 |
| Medion        | MS-7366                     | Desktop     | [ff7271711d](https://linux-hardware.org/?probe=ff7271711d) | Aug 25, 2020 |
| Lenovo        | Unknown                     | Notebook    | [74313d4eb1](https://linux-hardware.org/?probe=74313d4eb1) | Aug 24, 2020 |
| Lenovo        | ThinkPad P50s 20FLS02200    | Notebook    | [68d5ec0716](https://linux-hardware.org/?probe=68d5ec0716) | Aug 24, 2020 |
| HP            | 2AFA                        | Desktop     | [b60453f85a](https://linux-hardware.org/?probe=b60453f85a) | Aug 23, 2020 |
| HP            | 2AFA                        | Desktop     | [4c206cac6d](https://linux-hardware.org/?probe=4c206cac6d) | Aug 22, 2020 |
| HP            | ProBook 650 G2              | Notebook    | [4a91b4b21f](https://linux-hardware.org/?probe=4a91b4b21f) | Aug 18, 2020 |
| Razer         | Blade                       | Notebook    | [b8e7f44d4a](https://linux-hardware.org/?probe=b8e7f44d4a) | Aug 17, 2020 |
| HP            | EliteBook 820 G3            | Notebook    | [0d1ad99429](https://linux-hardware.org/?probe=0d1ad99429) | Aug 13, 2020 |
| Toshiba       | Satellite L40               | Notebook    | [33ec17e21b](https://linux-hardware.org/?probe=33ec17e21b) | Aug 13, 2020 |
| ASUSTek       | Z170-PRO                    | Desktop     | [7a14a06010](https://linux-hardware.org/?probe=7a14a06010) | Aug 11, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | Desktop     | [9ac43f513b](https://linux-hardware.org/?probe=9ac43f513b) | Aug 10, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [5c7a68d981](https://linux-hardware.org/?probe=5c7a68d981) | Aug 07, 2020 |
| Lenovo        | ThinkPad P53 20QN002VMX     | Notebook    | [8e3eee2d07](https://linux-hardware.org/?probe=8e3eee2d07) | Aug 06, 2020 |
| Lenovo        | ThinkPad P53 20QN002VMX     | Notebook    | [6b9f38754c](https://linux-hardware.org/?probe=6b9f38754c) | Aug 06, 2020 |
| Gigabyte      | Z77P-D3                     | Desktop     | [ce15c17648](https://linux-hardware.org/?probe=ce15c17648) | Aug 05, 2020 |
| Lenovo        | ThinkPad W540 20BG001BMD    | Notebook    | [72a1412fb1](https://linux-hardware.org/?probe=72a1412fb1) | Aug 04, 2020 |
| Lenovo        | ThinkPad W540 20BG001BMD    | Notebook    | [133bc3dd52](https://linux-hardware.org/?probe=133bc3dd52) | Aug 04, 2020 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [6d4445f122](https://linux-hardware.org/?probe=6d4445f122) | Aug 02, 2020 |
| Lenovo        | IdeaPad Y550 20017          | Notebook    | [c535bd5654](https://linux-hardware.org/?probe=c535bd5654) | Jul 29, 2020 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [fa42e14984](https://linux-hardware.org/?probe=fa42e14984) | Jul 28, 2020 |
| Lenovo        | IdeaPad Y550 20017          | Notebook    | [e748a3510c](https://linux-hardware.org/?probe=e748a3510c) | Jul 27, 2020 |
| MSI           | B450 TOMAHAWK               | Desktop     | [c44d7421b8](https://linux-hardware.org/?probe=c44d7421b8) | Jul 24, 2020 |
| Lenovo        | IdeaPad Y550 20017          | Notebook    | [3122f02f2c](https://linux-hardware.org/?probe=3122f02f2c) | Jul 23, 2020 |
| MSI           | X470 GAMING PRO             | Desktop     | [c12505e247](https://linux-hardware.org/?probe=c12505e247) | Jul 21, 2020 |
| MSI           | X470 GAMING PRO             | Desktop     | [ca1dac6b45](https://linux-hardware.org/?probe=ca1dac6b45) | Jul 21, 2020 |
| Packard Be... | EasyNote LJ73               | Notebook    | [b7cb387fea](https://linux-hardware.org/?probe=b7cb387fea) | Jul 21, 2020 |
| Dell          | Latitude E6420              | Notebook    | [e9238dcfff](https://linux-hardware.org/?probe=e9238dcfff) | Jul 19, 2020 |
| Dell          | Latitude E6420              | Notebook    | [231cadfc4a](https://linux-hardware.org/?probe=231cadfc4a) | Jul 19, 2020 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [861ca18aab](https://linux-hardware.org/?probe=861ca18aab) | Jul 16, 2020 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [ce07e0a768](https://linux-hardware.org/?probe=ce07e0a768) | Jul 14, 2020 |
| Toshiba       | Satellite L755D             | Notebook    | [a0cdb2f0bf](https://linux-hardware.org/?probe=a0cdb2f0bf) | Jul 12, 2020 |
| Toshiba       | Satellite L755D             | Notebook    | [f4ab460d93](https://linux-hardware.org/?probe=f4ab460d93) | Jul 12, 2020 |
| Dell          | Latitude 7480               | Notebook    | [c265940ec9](https://linux-hardware.org/?probe=c265940ec9) | Jul 11, 2020 |
| Lenovo        | ThinkCentre M58 7359WQR     | Desktop     | [73e0df5013](https://linux-hardware.org/?probe=73e0df5013) | Jul 09, 2020 |
| Gigabyte      | X570 UD                     | Desktop     | [ab1e04310e](https://linux-hardware.org/?probe=ab1e04310e) | Jul 07, 2020 |
| Gigabyte      | X570 UD                     | Desktop     | [319bbe63a2](https://linux-hardware.org/?probe=319bbe63a2) | Jul 07, 2020 |
| Apple         | MacBookPro6,1               | Notebook    | [432c9e6acf](https://linux-hardware.org/?probe=432c9e6acf) | Jul 05, 2020 |
| Apple         | MacBookPro14,1              | Notebook    | [b1b965bcfa](https://linux-hardware.org/?probe=b1b965bcfa) | Jul 03, 2020 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [1fa9af511a](https://linux-hardware.org/?probe=1fa9af511a) | Jul 03, 2020 |
| Lenovo        | 3130 SDK0J40697 WIN 3305... | Mini pc     | [0b009e8179](https://linux-hardware.org/?probe=0b009e8179) | Jul 01, 2020 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [26dfef89d5](https://linux-hardware.org/?probe=26dfef89d5) | Jun 30, 2020 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [57643353ce](https://linux-hardware.org/?probe=57643353ce) | Jun 29, 2020 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [9546ca8c2a](https://linux-hardware.org/?probe=9546ca8c2a) | Jun 29, 2020 |
| Lenovo        | ThinkPad W540 20BG001BMD    | Notebook    | [3f43b86780](https://linux-hardware.org/?probe=3f43b86780) | Jun 29, 2020 |
| Fujitsu       | LIFEBOOK U938               | Notebook    | [445cfe436d](https://linux-hardware.org/?probe=445cfe436d) | Jun 28, 2020 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [b92d2bdb9d](https://linux-hardware.org/?probe=b92d2bdb9d) | Jun 28, 2020 |
| ASUSTek       | K56CB                       | Notebook    | [bbdd76a080](https://linux-hardware.org/?probe=bbdd76a080) | Jun 21, 2020 |
| Fujitsu       | LIFEBOOK U938               | Notebook    | [6fab40c5c2](https://linux-hardware.org/?probe=6fab40c5c2) | Jun 20, 2020 |
| Gigabyte      | Z87X-UD4H-CF                | Desktop     | [8f5fc60880](https://linux-hardware.org/?probe=8f5fc60880) | Jun 20, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | Desktop     | [fdabb9483a](https://linux-hardware.org/?probe=fdabb9483a) | Jun 19, 2020 |
| Acer          | Mantasta                    | Notebook    | [fae9194978](https://linux-hardware.org/?probe=fae9194978) | Jun 19, 2020 |
| Gigabyte      | Z87X-UD4H-CF                | Desktop     | [bef7a799cc](https://linux-hardware.org/?probe=bef7a799cc) | Jun 18, 2020 |
| HP            | SpectreXT Pro 13-b000 PC    | Notebook    | [12d9fce39b](https://linux-hardware.org/?probe=12d9fce39b) | Jun 18, 2020 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [415c3a4a20](https://linux-hardware.org/?probe=415c3a4a20) | Jun 18, 2020 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | Notebook    | [8307e528e0](https://linux-hardware.org/?probe=8307e528e0) | Jun 17, 2020 |
| HP            | Pavilion 15                 | Notebook    | [6d0c4b8b4f](https://linux-hardware.org/?probe=6d0c4b8b4f) | Jun 16, 2020 |
| Lenovo        | ThinkPad W540 20BG001BMD    | Notebook    | [c9de665933](https://linux-hardware.org/?probe=c9de665933) | Jun 14, 2020 |
| Dell          | Latitude 7480               | Notebook    | [f1120b6914](https://linux-hardware.org/?probe=f1120b6914) | Jun 14, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | Desktop     | [1bd41519c5](https://linux-hardware.org/?probe=1bd41519c5) | Jun 13, 2020 |
| Dell          | XPS 15 9560                 | Notebook    | [68f8b211cb](https://linux-hardware.org/?probe=68f8b211cb) | Jun 13, 2020 |
| Dell          | XPS 15 9560                 | Notebook    | [5e9c9bd030](https://linux-hardware.org/?probe=5e9c9bd030) | Jun 13, 2020 |
| Razer         | Blade                       | Notebook    | [5ed51b12b4](https://linux-hardware.org/?probe=5ed51b12b4) | Jun 12, 2020 |
| HP            | SpectreXT Pro 13-b000 PC    | Notebook    | [6e1571661e](https://linux-hardware.org/?probe=6e1571661e) | Jun 12, 2020 |
| Lenovo        | ThinkPad W520 4284Y19       | Notebook    | [ac2ade7339](https://linux-hardware.org/?probe=ac2ade7339) | Jun 07, 2020 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [3e632a857d](https://linux-hardware.org/?probe=3e632a857d) | Jun 06, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | Desktop     | [c83816398c](https://linux-hardware.org/?probe=c83816398c) | Jun 05, 2020 |
| Lenovo        | IdeaPad U430p 20269         | Notebook    | [1431224dcf](https://linux-hardware.org/?probe=1431224dcf) | Jun 03, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | Desktop     | [82591ffa30](https://linux-hardware.org/?probe=82591ffa30) | Jun 01, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | Desktop     | [637d3d6ccc](https://linux-hardware.org/?probe=637d3d6ccc) | Jun 01, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | Desktop     | [bde3e045ca](https://linux-hardware.org/?probe=bde3e045ca) | May 31, 2020 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [1e87b772ca](https://linux-hardware.org/?probe=1e87b772ca) | May 29, 2020 |
| ASUSTek       | E45M1-I DELUXE              | Desktop     | [58f57667ee](https://linux-hardware.org/?probe=58f57667ee) | May 25, 2020 |
| Dell          | XPS 15 7590                 | Notebook    | [386ef00203](https://linux-hardware.org/?probe=386ef00203) | May 25, 2020 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [df82f94fa1](https://linux-hardware.org/?probe=df82f94fa1) | May 23, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [aafa3a16ab](https://linux-hardware.org/?probe=aafa3a16ab) | May 22, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | Desktop     | [8ab04c0e95](https://linux-hardware.org/?probe=8ab04c0e95) | May 22, 2020 |
| Dell          | XPS 15 7590                 | Notebook    | [544670327d](https://linux-hardware.org/?probe=544670327d) | May 21, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | Desktop     | [a1a244d013](https://linux-hardware.org/?probe=a1a244d013) | May 21, 2020 |
| AMI           | Cherry Trail FFD            | Desktop     | [2646be2c9b](https://linux-hardware.org/?probe=2646be2c9b) | May 17, 2020 |
| AMI           | Cherry Trail FFD            | Desktop     | [1abe48ca91](https://linux-hardware.org/?probe=1abe48ca91) | May 17, 2020 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [aa8b123cdd](https://linux-hardware.org/?probe=aa8b123cdd) | May 17, 2020 |
| Acer          | TravelMate 6592             | Notebook    | [9bb4619272](https://linux-hardware.org/?probe=9bb4619272) | May 17, 2020 |
| Acer          | TravelMate 6592             | Notebook    | [e4e54de319](https://linux-hardware.org/?probe=e4e54de319) | May 17, 2020 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [c6f0fde0d2](https://linux-hardware.org/?probe=c6f0fde0d2) | May 16, 2020 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [788a18932c](https://linux-hardware.org/?probe=788a18932c) | May 16, 2020 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [9d150cc443](https://linux-hardware.org/?probe=9d150cc443) | May 16, 2020 |
| Acer          | Swift SF514-52T             | Notebook    | [93ede38f81](https://linux-hardware.org/?probe=93ede38f81) | May 16, 2020 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [b47983a36a](https://linux-hardware.org/?probe=b47983a36a) | May 13, 2020 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [5fbd9385df](https://linux-hardware.org/?probe=5fbd9385df) | May 13, 2020 |
| Intel         | NUC5i5RYB H40999-503        | Mini pc     | [49f8fc7ad4](https://linux-hardware.org/?probe=49f8fc7ad4) | May 13, 2020 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [c6ead14954](https://linux-hardware.org/?probe=c6ead14954) | May 11, 2020 |
| Lenovo        | ThinkPad T410 2522WPH       | Notebook    | [236d1e64eb](https://linux-hardware.org/?probe=236d1e64eb) | May 10, 2020 |
| ASUSTek       | B85M-G                      | Desktop     | [f575cb11cb](https://linux-hardware.org/?probe=f575cb11cb) | May 08, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [a54bb2200a](https://linux-hardware.org/?probe=a54bb2200a) | May 06, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [0a904bfe70](https://linux-hardware.org/?probe=0a904bfe70) | May 05, 2020 |
| TUXEDO        | Unknown                     | Notebook    | [3f23947dd8](https://linux-hardware.org/?probe=3f23947dd8) | May 04, 2020 |
| MiTAC         | PH10SI AAPH11SI-CI-700      | All in one  | [e77fca8789](https://linux-hardware.org/?probe=e77fca8789) | May 04, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [b85ac004b3](https://linux-hardware.org/?probe=b85ac004b3) | May 04, 2020 |
| Lenovo        | ThinkPad T480s 20L8S5U50... | Notebook    | [d295ec1834](https://linux-hardware.org/?probe=d295ec1834) | May 03, 2020 |
| Dell          | Latitude E7450              | Notebook    | [0f14ff60e1](https://linux-hardware.org/?probe=0f14ff60e1) | May 02, 2020 |
| ASRock        | B450 Gaming K4              | Desktop     | [d82dc4eb4f](https://linux-hardware.org/?probe=d82dc4eb4f) | May 01, 2020 |
| ASRock        | B450 Gaming K4              | Desktop     | [c08ec23742](https://linux-hardware.org/?probe=c08ec23742) | May 01, 2020 |
| HP            | EliteBook 840 G1            | Notebook    | [9c6700839f](https://linux-hardware.org/?probe=9c6700839f) | May 01, 2020 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [f4f59aa7bc](https://linux-hardware.org/?probe=f4f59aa7bc) | May 01, 2020 |
| Medion        | P2212T                      | Tablet      | [49b59f34f4](https://linux-hardware.org/?probe=49b59f34f4) | May 01, 2020 |
| Lenovo        | IdeaPad U430p 20269         | Notebook    | [689865b9bf](https://linux-hardware.org/?probe=689865b9bf) | Apr 30, 2020 |
| Acer          | Aspire A715-72G             | Notebook    | [db52ab416a](https://linux-hardware.org/?probe=db52ab416a) | Apr 29, 2020 |
| Intel         | NUC5i5RYB H40999-503        | Mini pc     | [c37c94062c](https://linux-hardware.org/?probe=c37c94062c) | Apr 28, 2020 |
| ASUSTek       | ROG STRIX B360-F GAMING     | Desktop     | [3d3bc60c59](https://linux-hardware.org/?probe=3d3bc60c59) | Apr 28, 2020 |
| HP            | EliteBook 840 G1            | Notebook    | [b77a2c1bdc](https://linux-hardware.org/?probe=b77a2c1bdc) | Apr 27, 2020 |
| Lenovo        | ThinkPad T470p 20J7S0MS0... | Notebook    | [2ea2bebae7](https://linux-hardware.org/?probe=2ea2bebae7) | Apr 25, 2020 |
| Lenovo        | ThinkPad T470p 20J7S0MS0... | Notebook    | [47ae6712b9](https://linux-hardware.org/?probe=47ae6712b9) | Apr 25, 2020 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [07c0857487](https://linux-hardware.org/?probe=07c0857487) | Apr 24, 2020 |
| ASUSTek       | STRIX B250G GAMING          | Desktop     | [ed1abce019](https://linux-hardware.org/?probe=ed1abce019) | Apr 23, 2020 |
| ASUSTek       | P8Z77-V LE PLUS             | Desktop     | [0cbe6fdb9b](https://linux-hardware.org/?probe=0cbe6fdb9b) | Apr 21, 2020 |
| HP            | Unknown                     | Notebook    | [7da32c9344](https://linux-hardware.org/?probe=7da32c9344) | Apr 21, 2020 |
| Dell          | Latitude E5510              | Notebook    | [a70ec059cf](https://linux-hardware.org/?probe=a70ec059cf) | Apr 13, 2020 |
| HP            | Pavilion dv9700             | Notebook    | [6096eebeb4](https://linux-hardware.org/?probe=6096eebeb4) | Apr 11, 2020 |
| ASUSTek       | P8Z77-V LE PLUS             | Desktop     | [61d4286e96](https://linux-hardware.org/?probe=61d4286e96) | Apr 06, 2020 |
| Apple         | MacBookPro5,5               | Notebook    | [9f7081cc76](https://linux-hardware.org/?probe=9f7081cc76) | Apr 04, 2020 |
| Lenovo        | Yoga 710-14IKB 80V4         | Convertible | [0b5886cdd6](https://linux-hardware.org/?probe=0b5886cdd6) | Apr 04, 2020 |
| ECS           | Nettle3                     | Desktop     | [51538f1902](https://linux-hardware.org/?probe=51538f1902) | Apr 02, 2020 |
| ECS           | Nettle3                     | Desktop     | [5a8f6b27a0](https://linux-hardware.org/?probe=5a8f6b27a0) | Apr 02, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [efa9153f5a](https://linux-hardware.org/?probe=efa9153f5a) | Apr 02, 2020 |
| ASRock        | Z77 Pro4-M                  | Desktop     | [fee80882b4](https://linux-hardware.org/?probe=fee80882b4) | Apr 02, 2020 |
| ASRock        | Z77 Pro4-M                  | Desktop     | [309423fc5a](https://linux-hardware.org/?probe=309423fc5a) | Apr 02, 2020 |
| ASRock        | Z77 Pro4-M                  | Desktop     | [cc7be1cc44](https://linux-hardware.org/?probe=cc7be1cc44) | Apr 02, 2020 |
| Lenovo        | B50-10 80QR                 | Notebook    | [587fb80750](https://linux-hardware.org/?probe=587fb80750) | Apr 01, 2020 |
| Dixonsxp      | Unknown                     | Notebook    | [bfb0ade0c7](https://linux-hardware.org/?probe=bfb0ade0c7) | Apr 01, 2020 |
| Dixonsxp      | Unknown                     | Notebook    | [26154d1d2c](https://linux-hardware.org/?probe=26154d1d2c) | Apr 01, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [9ddd365ccc](https://linux-hardware.org/?probe=9ddd365ccc) | Mar 28, 2020 |
| Shuttle       | FS35V5                      | Mini pc     | [b31e28e55f](https://linux-hardware.org/?probe=b31e28e55f) | Mar 28, 2020 |
| Dell          | 0F373D A00                  | Desktop     | [2155b32aa1](https://linux-hardware.org/?probe=2155b32aa1) | Mar 25, 2020 |
| ASUSTek       | N76VB                       | Notebook    | [a771ac7748](https://linux-hardware.org/?probe=a771ac7748) | Mar 24, 2020 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [d67be379b0](https://linux-hardware.org/?probe=d67be379b0) | Mar 24, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | Desktop     | [fbc59a267b](https://linux-hardware.org/?probe=fbc59a267b) | Mar 23, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | Desktop     | [548b742928](https://linux-hardware.org/?probe=548b742928) | Mar 22, 2020 |
| Unknown       | Unknown                     | Phone       | [d7628d22aa](https://linux-hardware.org/?probe=d7628d22aa) | Mar 22, 2020 |
| ASUSTek       | Strix 15 GL503GE            | Notebook    | [069d575f4a](https://linux-hardware.org/?probe=069d575f4a) | Mar 21, 2020 |
| HP            | ProLiant MicroServer        | Desktop     | [b8fc545d86](https://linux-hardware.org/?probe=b8fc545d86) | Mar 19, 2020 |
| HP            | Pavilion dv7                | Notebook    | [64000a6ec8](https://linux-hardware.org/?probe=64000a6ec8) | Mar 19, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [69559fb5ce](https://linux-hardware.org/?probe=69559fb5ce) | Mar 18, 2020 |
| Toshiba       | Satellite C670D-10C         | Notebook    | [bdcd7e9b36](https://linux-hardware.org/?probe=bdcd7e9b36) | Mar 17, 2020 |
| Toshiba       | Satellite C670D-10C         | Notebook    | [ab2ea68be0](https://linux-hardware.org/?probe=ab2ea68be0) | Mar 17, 2020 |
| Lenovo        | ThinkPad S3-S440 20AY00B... | Notebook    | [86e1d115b9](https://linux-hardware.org/?probe=86e1d115b9) | Mar 15, 2020 |
| HP            | ProBook 4720s               | Notebook    | [a32d5c092c](https://linux-hardware.org/?probe=a32d5c092c) | Mar 15, 2020 |
| Unknown       | Unknown                     | Phone       | [bc4300dca6](https://linux-hardware.org/?probe=bc4300dca6) | Mar 13, 2020 |
| Toshiba       | Satellite L40               | Notebook    | [467c320928](https://linux-hardware.org/?probe=467c320928) | Mar 11, 2020 |
| ASUSTek       | P5QL-VM EPU                 | Desktop     | [73276b8f74](https://linux-hardware.org/?probe=73276b8f74) | Mar 09, 2020 |
| HP            | ProLiant DL380 G5           | Server      | [5d93d067d7](https://linux-hardware.org/?probe=5d93d067d7) | Mar 08, 2020 |
| ASUSTek       | P5QL-VM EPU                 | Desktop     | [da8bd96ca5](https://linux-hardware.org/?probe=da8bd96ca5) | Mar 07, 2020 |
| ASUSTek       | Z97-A-USB31                 | Desktop     | [63b94ee87e](https://linux-hardware.org/?probe=63b94ee87e) | Mar 06, 2020 |
| Lenovo        | ThinkPad Edge E530 3259C... | Notebook    | [7e0acb9bed](https://linux-hardware.org/?probe=7e0acb9bed) | Mar 06, 2020 |
| HP            | ProBook 4720s               | Notebook    | [823553cfbd](https://linux-hardware.org/?probe=823553cfbd) | Mar 03, 2020 |
| HP            | ProLiant DL380 G5           | Server      | [b6cb6a7704](https://linux-hardware.org/?probe=b6cb6a7704) | Mar 02, 2020 |
| MiTAC         | PH10SI AAPH11SI-CI-700      | All in one  | [f1ab819dad](https://linux-hardware.org/?probe=f1ab819dad) | Mar 02, 2020 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | Notebook    | [de25ec2891](https://linux-hardware.org/?probe=de25ec2891) | Feb 28, 2020 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | Notebook    | [b333f7015a](https://linux-hardware.org/?probe=b333f7015a) | Feb 28, 2020 |
| HP            | ZBook 14u G5                | Notebook    | [03871e6b83](https://linux-hardware.org/?probe=03871e6b83) | Feb 25, 2020 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [da2608360d](https://linux-hardware.org/?probe=da2608360d) | Feb 23, 2020 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | Notebook    | [0937d2a588](https://linux-hardware.org/?probe=0937d2a588) | Feb 20, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [5e00c1766c](https://linux-hardware.org/?probe=5e00c1766c) | Feb 19, 2020 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | Notebook    | [7f8aef2f6b](https://linux-hardware.org/?probe=7f8aef2f6b) | Feb 19, 2020 |
| Gigabyte      | Z68X-UD7-B3                 | Desktop     | [078b188645](https://linux-hardware.org/?probe=078b188645) | Feb 16, 2020 |
| Gigabyte      | Z68X-UD7-B3                 | Desktop     | [700eabb523](https://linux-hardware.org/?probe=700eabb523) | Feb 15, 2020 |
| HP            | 86D3                        | Desktop     | [83613548dc](https://linux-hardware.org/?probe=83613548dc) | Feb 13, 2020 |
| MSI           | MS-1738                     | Notebook    | [0cbf139f1d](https://linux-hardware.org/?probe=0cbf139f1d) | Feb 11, 2020 |
| Alienware     | 06G6JW A00                  | Desktop     | [f3eab06bb2](https://linux-hardware.org/?probe=f3eab06bb2) | Feb 10, 2020 |
| Lenovo        | ThinkPad T490s 20NX000EM... | Notebook    | [7773f702ab](https://linux-hardware.org/?probe=7773f702ab) | Feb 10, 2020 |
| ASUSTek       | UX331UA                     | Notebook    | [62bdf0c233](https://linux-hardware.org/?probe=62bdf0c233) | Feb 10, 2020 |
| HP            | EliteBook 850 G5            | Notebook    | [fc9101307a](https://linux-hardware.org/?probe=fc9101307a) | Feb 07, 2020 |
| Dell          | Precision 7530              | Notebook    | [bb59dc45d2](https://linux-hardware.org/?probe=bb59dc45d2) | Feb 06, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [d5e6feb702](https://linux-hardware.org/?probe=d5e6feb702) | Feb 04, 2020 |
| MSI           | MS-1738                     | Notebook    | [1f7c3ccb75](https://linux-hardware.org/?probe=1f7c3ccb75) | Jan 29, 2020 |
| Lenovo        | IdeaPad Y500 9541           | Notebook    | [1435e47012](https://linux-hardware.org/?probe=1435e47012) | Jan 27, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Denmark/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Ubuntu 20.04     | 142       | 16.36%  |
| Ubuntu 18.04     | 84        | 9.68%   |
| Ubuntu 22.04     | 34        | 3.92%   |
| Ubuntu 21.10     | 25        | 2.88%   |
| OpenMandriva 4.2 | 25        | 2.88%   |
| Arch Rolling     | 23        | 2.65%   |
| Manjaro          | 16        | 1.84%   |
| Fedora 34        | 16        | 1.84%   |
| Debian 11        | 16        | 1.84%   |
| Ubuntu 20.10     | 15        | 1.73%   |
| Zorin 16         | 14        | 1.61%   |
| Ubuntu 19.04     | 14        | 1.61%   |
| Pop!_OS 21.04    | 14        | 1.61%   |
| Linux Mint 20.2  | 14        | 1.61%   |
| Linux Mint 20.3  | 13        | 1.5%    |
| Arch             | 13        | 1.5%    |
| OpenMandriva 4.3 | 12        | 1.38%   |
| Linux Mint 20.1  | 12        | 1.38%   |
| Fedora 32        | 12        | 1.38%   |
| Zorin 15         | 11        | 1.27%   |
| Pop!_OS 22.04    | 11        | 1.27%   |
| KDE neon 20.04   | 11        | 1.27%   |
| Ubuntu 19.10     | 10        | 1.15%   |
| Pop!_OS 20.04    | 10        | 1.15%   |
| Debian 10        | 10        | 1.15%   |
| Pop!_OS 21.10    | 9         | 1.04%   |
| Pop!_OS 20.10    | 9         | 1.04%   |
| Fedora 36        | 9         | 1.04%   |
| Linux Mint 20    | 8         | 0.92%   |
| Fedora 35        | 8         | 0.92%   |
| Fedora 33        | 8         | 0.92%   |
| Ubuntu 21.04     | 7         | 0.81%   |
| Linux Mint 19.2  | 7         | 0.81%   |
| Fedora 31        | 7         | 0.81%   |
| Xubuntu 20.04    | 6         | 0.69%   |
| Ubuntu 22.10     | 6         | 0.69%   |
| Ubuntu 18.10     | 6         | 0.69%   |
| Linux Mint 21    | 6         | 0.69%   |
| Kubuntu 20.04    | 6         | 0.69%   |
| Linux Mint 21.1  | 5         | 0.58%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 324       | 39.71%  |
| Linux Mint   | 70        | 8.58%   |
| Fedora       | 59        | 7.23%   |
| Pop!_OS      | 52        | 6.37%   |
| OpenMandriva | 43        | 5.27%   |
| Manjaro      | 36        | 4.41%   |
| Arch         | 35        | 4.29%   |
| Debian       | 30        | 3.68%   |
| Zorin        | 27        | 3.31%   |
| Kubuntu      | 18        | 2.21%   |
| KDE neon     | 15        | 1.84%   |
| Xubuntu      | 10        | 1.23%   |
| ROSA         | 9         | 1.1%    |
| ArcoLinux    | 8         | 0.98%   |
| EndeavourOS  | 7         | 0.86%   |
| Ubuntu MATE  | 6         | 0.74%   |
| Elementary   | 6         | 0.74%   |
| Void Linux   | 5         | 0.61%   |
| Ubuntu Unity | 5         | 0.61%   |
| Garuda Linux | 5         | 0.61%   |
| SteamOS      | 4         | 0.49%   |
| Parrot       | 4         | 0.49%   |
| Gentoo       | 4         | 0.49%   |
| openSUSE     | 3         | 0.37%   |
| MX           | 3         | 0.37%   |
| LMDE         | 3         | 0.37%   |
| Clear Linux  | 3         | 0.37%   |
| BlackPanther | 3         | 0.37%   |
| Raspbian     | 2         | 0.25%   |
| NixOS        | 2         | 0.25%   |
| Lubuntu      | 2         | 0.25%   |
| Kali         | 2         | 0.25%   |
| Endless      | 2         | 0.25%   |
| Xero         | 1         | 0.12%   |
| TUXEDO OS    | 1         | 0.12%   |
| Solus        | 1         | 0.12%   |
| LinuxFX      | 1         | 0.12%   |
| GalliumOS    | 1         | 0.12%   |
| antiX        | 1         | 0.12%   |
| Android      | 1         | 0.12%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 23        | 2.43%   |
| 5.4.0-42-generic         | 19        | 2%      |
| 5.16.7-desktop-1omv4003  | 13        | 1.37%   |
| 5.4.0-52-generic         | 12        | 1.27%   |
| 5.15.0-56-generic        | 12        | 1.27%   |
| 5.4.0-26-generic         | 10        | 1.05%   |
| 5.4.0-58-generic         | 8         | 0.84%   |
| 5.4.0-48-generic         | 8         | 0.84%   |
| 5.3.0-28-generic         | 8         | 0.84%   |
| 5.8.0-43-generic         | 7         | 0.74%   |
| 5.4.0-29-generic         | 7         | 0.74%   |
| 5.15.0-58-generic        | 7         | 0.74%   |
| 5.15.0-46-generic        | 7         | 0.74%   |
| 5.11.0-27-generic        | 7         | 0.74%   |
| 5.4.0-91-generic         | 6         | 0.63%   |
| 5.4.0-7634-generic       | 6         | 0.63%   |
| 5.3.0-40-generic         | 6         | 0.63%   |
| 5.19.0-76051900-generic  | 6         | 0.63%   |
| 5.15.0-53-generic        | 6         | 0.63%   |
| 5.15.0-43-generic        | 6         | 0.63%   |
| 5.11.0-7620-generic      | 6         | 0.63%   |
| 5.11.0-41-generic        | 6         | 0.63%   |
| 5.8.0-41-generic         | 5         | 0.53%   |
| 5.4.0-47-generic         | 5         | 0.53%   |
| 5.15.0-52-generic        | 5         | 0.53%   |
| 5.13.12-200.fc34.x86_64  | 5         | 0.53%   |
| 5.11.0-40-generic        | 5         | 0.53%   |
| 5.11.0-37-generic        | 5         | 0.53%   |
| 5.10.0-19-amd64          | 5         | 0.53%   |
| 5.0.0-23-generic         | 5         | 0.53%   |
| 5.0.0-13-generic         | 5         | 0.53%   |
| 4.15.0-55-generic        | 5         | 0.53%   |
| 4.15.0-45-generic        | 5         | 0.53%   |
| 5.8.5-arch1-1            | 4         | 0.42%   |
| 5.8.0-7642-generic       | 4         | 0.42%   |
| 5.8.0-59-generic         | 4         | 0.42%   |
| 5.8.0-45-generic         | 4         | 0.42%   |
| 5.8.0-29-generic         | 4         | 0.42%   |
| 5.4.0-88-generic         | 4         | 0.42%   |
| 5.4.0-77-generic         | 4         | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 153       | 17.17%  |
| 4.15.0  | 65        | 7.3%    |
| 5.15.0  | 61        | 6.85%   |
| 5.8.0   | 56        | 6.29%   |
| 5.11.0  | 56        | 6.29%   |
| 5.13.0  | 55        | 6.17%   |
| 5.3.0   | 37        | 4.15%   |
| 5.0.0   | 27        | 3.03%   |
| 5.10.14 | 23        | 2.58%   |
| 5.10.0  | 20        | 2.24%   |
| 4.18.0  | 18        | 2.02%   |
| 5.19.0  | 14        | 1.57%   |
| 5.16.7  | 13        | 1.46%   |
| 4.19.0  | 11        | 1.23%   |
| 6.1.1   | 5         | 0.56%   |
| 5.4.18  | 5         | 0.56%   |
| 5.16.0  | 5         | 0.56%   |
| 5.13.12 | 5         | 0.56%   |
| 6.0.6   | 4         | 0.45%   |
| 5.9.0   | 4         | 0.45%   |
| 5.8.5   | 4         | 0.45%   |
| 5.7.15  | 4         | 0.45%   |
| 5.6.7   | 4         | 0.45%   |
| 5.16.18 | 4         | 0.45%   |
| 5.14.0  | 4         | 0.45%   |
| 6.0.10  | 3         | 0.34%   |
| 5.8.15  | 3         | 0.34%   |
| 5.6.15  | 3         | 0.34%   |
| 5.19.13 | 3         | 0.34%   |
| 5.17.5  | 3         | 0.34%   |
| 5.16.11 | 3         | 0.34%   |
| 5.15.6  | 3         | 0.34%   |
| 5.11.12 | 3         | 0.34%   |
| 5.11.11 | 3         | 0.34%   |
| 4.9.60  | 3         | 0.34%   |
| 6.1.7   | 2         | 0.22%   |
| 6.0.7   | 2         | 0.22%   |
| 6.0.15  | 2         | 0.22%   |
| 6.0.12  | 2         | 0.22%   |
| 6.0.0   | 2         | 0.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 168       | 19.07%  |
| 5.15    | 90        | 10.22%  |
| 5.8     | 76        | 8.63%   |
| 5.11    | 68        | 7.72%   |
| 5.13    | 65        | 7.38%   |
| 4.15    | 65        | 7.38%   |
| 5.10    | 53        | 6.02%   |
| 5.3     | 37        | 4.2%    |
| 5.16    | 33        | 3.75%   |
| 5.19    | 28        | 3.18%   |
| 5.0     | 28        | 3.18%   |
| 4.18    | 20        | 2.27%   |
| 6.0     | 17        | 1.93%   |
| 5.6     | 17        | 1.93%   |
| 5.14    | 16        | 1.82%   |
| 4.19    | 13        | 1.48%   |
| 5.9     | 12        | 1.36%   |
| 5.7     | 12        | 1.36%   |
| 5.17    | 12        | 1.36%   |
| 6.1     | 10        | 1.14%   |
| 5.12    | 9         | 1.02%   |
| 5.18    | 8         | 0.91%   |
| 5.1     | 6         | 0.68%   |
| 4.9     | 6         | 0.68%   |
| 4.4     | 3         | 0.34%   |
| 5.2     | 2         | 0.23%   |
| 4.14    | 2         | 0.23%   |
| 4.17    | 1         | 0.11%   |
| 4.16    | 1         | 0.11%   |
| 4.13    | 1         | 0.11%   |
| 4.10    | 1         | 0.11%   |
| Unknown | 1         | 0.11%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 755       | 95.93%  |
| i686    | 22        | 2.8%    |
| aarch64 | 8         | 1.02%   |
| armv7l  | 2         | 0.25%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 391       | 47.28%  |
| Unknown         | 137       | 16.57%  |
| KDE5            | 124       | 14.99%  |
| X-Cinnamon      | 55        | 6.65%   |
| XFCE            | 46        | 5.56%   |
| KDE             | 20        | 2.42%   |
| MATE            | 16        | 1.93%   |
| Cinnamon        | 7         | 0.85%   |
| Unity           | 5         | 0.6%    |
| Pantheon        | 5         | 0.6%    |
| i3              | 5         | 0.6%    |
| LXQt            | 2         | 0.24%   |
| KDE4            | 2         | 0.24%   |
| GNOME Flashback | 2         | 0.24%   |
| sway            | 1         | 0.12%   |
| qtile-default   | 1         | 0.12%   |
| openbox         | 1         | 0.12%   |
| LXDE            | 1         | 0.12%   |
| LeftWM          | 1         | 0.12%   |
| icewm           | 1         | 0.12%   |
| enlightenment   | 1         | 0.12%   |
| Deepin          | 1         | 0.12%   |
| bspwm           | 1         | 0.12%   |
| awesome         | 1         | 0.12%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 622       | 76.13%  |
| Wayland | 114       | 13.95%  |
| Unknown | 66        | 8.08%   |
| Tty     | 15        | 1.84%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 456       | 56.02%  |
| GDM     | 98        | 12.04%  |
| SDDM    | 96        | 11.79%  |
| GDM3    | 90        | 11.06%  |
| LightDM | 38        | 4.67%   |
| TDM     | 29        | 3.56%   |
| KDM     | 2         | 0.25%   |
| XDM     | 1         | 0.12%   |
| SLiM    | 1         | 0.12%   |
| Ly      | 1         | 0.12%   |
| LXDM    | 1         | 0.12%   |
| GREETD  | 1         | 0.12%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 283       | 34.81%  |
| da_DK      | 245       | 30.14%  |
| Unknown    | 110       | 13.53%  |
| en_DK      | 102       | 12.55%  |
| en_GB      | 33        | 4.06%   |
| de_DE      | 13        | 1.6%    |
| C          | 8         | 0.98%   |
| pl_PL      | 3         | 0.37%   |
| ru_RU      | 2         | 0.25%   |
| it_IT      | 2         | 0.25%   |
| en_AG      | 2         | 0.25%   |
| sv_SE      | 1         | 0.12%   |
| pt_BR      | 1         | 0.12%   |
| is_IS      | 1         | 0.12%   |
| io_001     | 1         | 0.12%   |
| fr_FR      | 1         | 0.12%   |
| es_ES      | 1         | 0.12%   |
| en_US.UTF8 | 1         | 0.12%   |
| en_IE      | 1         | 0.12%   |
| en_CA      | 1         | 0.12%   |
| de_AT      | 1         | 0.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 416       | 52%     |
| EFI  | 384       | 48%     |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 637       | 78.93%  |
| Btrfs   | 71        | 8.8%    |
| Overlay | 49        | 6.07%   |
| Unknown | 36        | 4.46%   |
| Zfs     | 7         | 0.87%   |
| Xfs     | 3         | 0.37%   |
| Ext2    | 3         | 0.37%   |
| F2fs    | 1         | 0.12%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 493       | 60.94%  |
| GPT     | 247       | 30.53%  |
| MBR     | 69        | 8.53%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 683       | 85.06%  |
| Yes       | 120       | 14.94%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 598       | 74.94%  |
| Yes       | 200       | 25.06%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 199       | 25.32%  |
| ASUSTek Computer        | 135       | 17.18%  |
| Hewlett-Packard         | 103       | 13.1%   |
| Dell                    | 57        | 7.25%   |
| Gigabyte Technology     | 43        | 5.47%   |
| Acer                    | 41        | 5.22%   |
| MSI                     | 35        | 4.45%   |
| ASRock                  | 24        | 3.05%   |
| Apple                   | 23        | 2.93%   |
| Medion                  | 16        | 2.04%   |
| Toshiba                 | 10        | 1.27%   |
| Raspberry Pi Foundation | 9         | 1.15%   |
| Notebook                | 9         | 1.15%   |
| Intel                   | 9         | 1.15%   |
| HUAWEI                  | 5         | 0.64%   |
| Shuttle                 | 4         | 0.51%   |
| Google                  | 4         | 0.51%   |
| AMI                     | 4         | 0.51%   |
| Unknown                 | 4         | 0.51%   |
| Samsung Electronics     | 3         | 0.38%   |
| Pegatron                | 3         | 0.38%   |
| Packard Bell            | 3         | 0.38%   |
| Microsoft               | 3         | 0.38%   |
| Fujitsu                 | 3         | 0.38%   |
| eMachines               | 3         | 0.38%   |
| Valve                   | 2         | 0.25%   |
| TUXEDO                  | 2         | 0.25%   |
| Timi                    | 2         | 0.25%   |
| Razer                   | 2         | 0.25%   |
| Quanta                  | 2         | 0.25%   |
| GPD                     | 2         | 0.25%   |
| Alienware               | 2         | 0.25%   |
| Tactus                  | 1         | 0.13%   |
| T-bao                   | 1         | 0.13%   |
| System76                | 1         | 0.13%   |
| Supermicro              | 1         | 0.13%   |
| Standard                | 1         | 0.13%   |
| SLIMBOOK                | 1         | 0.13%   |
| Purism                  | 1         | 0.13%   |
| NEXCOM                  | 1         | 0.13%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| Unknown                               | 11        | 1.4%    |
| RPi Raspberry Pi                      | 5         | 0.64%   |
| ASUS ROG STRIX B450-E GAMING          | 5         | 0.64%   |
| ASUS All Series                       | 5         | 0.64%   |
| HP Pavilion dv7                       | 4         | 0.51%   |
| Dell XPS 15 9570                      | 4         | 0.51%   |
| ASUS Z170 PRO GAMING                  | 4         | 0.51%   |
| RPi Raspberry Pi 4 Model B Rev 1.1    | 3         | 0.38%   |
| MSI MS-7C37                           | 3         | 0.38%   |
| HP EliteBook 820 G3                   | 3         | 0.38%   |
| Dell XPS 13 9370                      | 3         | 0.38%   |
| Dell OptiPlex 9020                    | 3         | 0.38%   |
| ASUS ROG Zephyrus G14 GA402RK_GA402RK | 3         | 0.38%   |
| ASUS ROG STRIX B550-F GAMING          | 3         | 0.38%   |
| Apple MacBookPro5,5                   | 3         | 0.38%   |
| Valve Jupiter                         | 2         | 0.25%   |
| Toshiba Satellite L40                 | 2         | 0.25%   |
| Quanta MW1/HW1                        | 2         | 0.25%   |
| Notebook W54_55SU1,SUW                | 2         | 0.25%   |
| MSI MS-7C02                           | 2         | 0.25%   |
| MSI MS-7B79                           | 2         | 0.25%   |
| Medion MS-7797                        | 2         | 0.25%   |
| Medion MS-7646                        | 2         | 0.25%   |
| Lenovo Yoga C740-14IML 81TC           | 2         | 0.25%   |
| Lenovo ThinkPad T530 24295L4          | 2         | 0.25%   |
| Lenovo IdeaPad S130-14IGM 81J2        | 2         | 0.25%   |
| Lenovo IdeaPad 310-15IKB 80TV         | 2         | 0.25%   |
| Lenovo H30-05 90BJ00CNMT              | 2         | 0.25%   |
| Lenovo E31-80 80MX                    | 2         | 0.25%   |
| HP ProBook 650 G1                     | 2         | 0.25%   |
| HP Pavilion x360 Convertible 14-ba0xx | 2         | 0.25%   |
| HP Pavilion Notebook                  | 2         | 0.25%   |
| HP Pavilion g7                        | 2         | 0.25%   |
| HP Pavilion 15                        | 2         | 0.25%   |
| HP Notebook                           | 2         | 0.25%   |
| HP Laptop 15s-eq2xxx                  | 2         | 0.25%   |
| HP Laptop 15-bw0xx                    | 2         | 0.25%   |
| HP EliteBook 845 G7 Notebook PC       | 2         | 0.25%   |
| HP EliteBook 840 G1                   | 2         | 0.25%   |
| HP Compaq Presario CQ71               | 2         | 0.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 116       | 14.76%  |
| ASUS ROG            | 32        | 4.07%   |
| Acer Aspire         | 28        | 3.56%   |
| HP Pavilion         | 22        | 2.8%    |
| HP EliteBook        | 21        | 2.67%   |
| ASUS PRIME          | 20        | 2.54%   |
| Dell Latitude       | 19        | 2.42%   |
| Lenovo IdeaPad      | 15        | 1.91%   |
| Lenovo Yoga         | 14        | 1.78%   |
| Lenovo ThinkCentre  | 13        | 1.65%   |
| Dell XPS            | 13        | 1.65%   |
| HP Compaq           | 11        | 1.4%    |
| Unknown             | 11        | 1.4%    |
| Toshiba Satellite   | 10        | 1.27%   |
| HP ProBook          | 10        | 1.27%   |
| ASUS TUF            | 10        | 1.27%   |
| RPi Raspberry       | 9         | 1.15%   |
| HP Laptop           | 9         | 1.15%   |
| Dell Inspiron       | 9         | 1.15%   |
| Gigabyte X570       | 7         | 0.89%   |
| ASUS ZenBook        | 7         | 0.89%   |
| Dell OptiPlex       | 6         | 0.76%   |
| ASUS All            | 5         | 0.64%   |
| Lenovo ThinkStation | 4         | 0.51%   |
| Lenovo Legion       | 4         | 0.51%   |
| HP ProLiant         | 4         | 0.51%   |
| Dell Precision      | 4         | 0.51%   |
| ASUS Z170           | 4         | 0.51%   |
| ASUS VivoBook       | 4         | 0.51%   |
| MSI MS-7C37         | 3         | 0.38%   |
| Microsoft Surface   | 3         | 0.38%   |
| Lenovo ThinkBook    | 3         | 0.38%   |
| HP ZBook            | 3         | 0.38%   |
| HP OMEN             | 3         | 0.38%   |
| HP ENVY             | 3         | 0.38%   |
| Gigabyte B550       | 3         | 0.38%   |
| ASUS SABERTOOTH     | 3         | 0.38%   |
| ASUS M5A78L-M       | 3         | 0.38%   |
| ASRock Z170         | 3         | 0.38%   |
| Apple MacBookPro5   | 3         | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 79        | 10.05%  |
| 2020    | 74        | 9.41%   |
| 2019    | 72        | 9.16%   |
| 2017    | 62        | 7.89%   |
| 2012    | 60        | 7.63%   |
| 2013    | 59        | 7.51%   |
| 2021    | 56        | 7.12%   |
| 2016    | 53        | 6.74%   |
| 2015    | 49        | 6.23%   |
| 2011    | 47        | 5.98%   |
| 2010    | 33        | 4.2%    |
| 2009    | 33        | 4.2%    |
| 2014    | 30        | 3.82%   |
| 2008    | 25        | 3.18%   |
| 2022    | 20        | 2.54%   |
| 2007    | 18        | 2.29%   |
| Unknown | 8         | 1.02%   |
| 2006    | 7         | 0.89%   |
| 2003    | 1         | 0.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 450       | 57.25%  |
| Desktop        | 268       | 34.1%   |
| Convertible    | 22        | 2.8%    |
| All in one     | 14        | 1.78%   |
| Mini pc        | 13        | 1.65%   |
| System on chip | 9         | 1.15%   |
| Tablet         | 6         | 0.76%   |
| Server         | 3         | 0.38%   |
| Phone          | 1         | 0.13%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 728       | 92.15%  |
| Enabled  | 62        | 7.85%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 781       | 99.36%  |
| Yes  | 5         | 0.64%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 180       | 22.39%  |
| 4.01-8.0        | 177       | 22.01%  |
| 8.01-16.0       | 157       | 19.53%  |
| 3.01-4.0        | 113       | 14.05%  |
| 32.01-64.0      | 95        | 11.82%  |
| 64.01-256.0     | 27        | 3.36%   |
| 1.01-2.0        | 20        | 2.49%   |
| 24.01-32.0      | 18        | 2.24%   |
| 2.01-3.0        | 12        | 1.49%   |
| 0.51-1.0        | 3         | 0.37%   |
| More than 256.0 | 1         | 0.12%   |
| 0.01-0.5        | 1         | 0.12%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 283       | 32.23%  |
| 2.01-3.0   | 234       | 26.65%  |
| 4.01-8.0   | 146       | 16.63%  |
| 3.01-4.0   | 130       | 14.81%  |
| 0.51-1.0   | 39        | 4.44%   |
| 8.01-16.0  | 30        | 3.42%   |
| 0.01-0.5   | 9         | 1.03%   |
| 16.01-24.0 | 3         | 0.34%   |
| 32.01-64.0 | 2         | 0.23%   |
| 24.01-32.0 | 2         | 0.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 512       | 63.76%  |
| 2      | 161       | 20.05%  |
| 3      | 69        | 8.59%   |
| 4      | 26        | 3.24%   |
| 5      | 16        | 1.99%   |
| 0      | 10        | 1.25%   |
| 6      | 5         | 0.62%   |
| 8      | 2         | 0.25%   |
| 9      | 1         | 0.12%   |
| 7      | 1         | 0.12%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 509       | 64.19%  |
| Yes       | 284       | 35.81%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 693       | 87.61%  |
| No        | 98        | 12.39%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 625       | 79.01%  |
| No        | 166       | 20.99%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 521       | 65.21%  |
| No        | 278       | 34.79%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Denmark | 786       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                     | Computers | Percent |
|--------------------------|-----------|---------|
| Copenhagen               | 180       | 21.74%  |
| Odense                   | 53        | 6.4%    |
| Frederiksberg            | 53        | 6.4%    |
| Aarhus                   | 28        | 3.38%   |
| Bronshoj                 | 22        | 2.66%   |
| Silkeborg                | 20        | 2.42%   |
| Aalborg                  | 17        | 2.05%   |
| Horsens                  | 16        | 1.93%   |
| Aabenraa                 | 15        | 1.81%   |
| Slagelse                 | 13        | 1.57%   |
| Valby                    | 12        | 1.45%   |
| Holstebro                | 12        | 1.45%   |
| Esbjerg                  | 12        | 1.45%   |
| Roskilde                 | 11        | 1.33%   |
| Kongens Lyngby           | 11        | 1.33%   |
| Glostrup Municipality    | 11        | 1.33%   |
| Nyborg                   | 9         | 1.09%   |
| Norresundby              | 9         | 1.09%   |
| Herlev                   | 9         | 1.09%   |
| Vejle                    | 8         | 0.97%   |
| Risskov                  | 8         | 0.97%   |
| Hvidovre                 | 8         | 0.97%   |
| Gentofte Municipality    | 8         | 0.97%   |
| Skanderborg              | 7         | 0.85%   |
| Naestved                 | 7         | 0.85%   |
| Kastrup                  | 7         | 0.85%   |
| Vaerlose                 | 6         | 0.72%   |
| Taastrup                 | 6         | 0.72%   |
| Svendborg                | 6         | 0.72%   |
| Albertslund Municipality | 6         | 0.72%   |
| Vanlose                  | 5         | 0.6%    |
| Sindal                   | 5         | 0.6%    |
| Elsinore                 | 5         | 0.6%    |
| Thisted                  | 4         | 0.48%   |
| Køge                    | 4         | 0.48%   |
| Kolding                  | 4         | 0.48%   |
| Hojbjerg                 | 4         | 0.48%   |
| Hjørring                | 4         | 0.48%   |
| Aars                     | 4         | 0.48%   |
| Aabybro                  | 4         | 0.48%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 248       | 378    | 22.34%  |
| WDC                         | 147       | 222    | 13.24%  |
| Seagate                     | 134       | 189    | 12.07%  |
| Kingston                    | 91        | 129    | 8.2%    |
| Toshiba                     | 64        | 85     | 5.77%   |
| SanDisk                     | 47        | 61     | 4.23%   |
| SK hynix                    | 44        | 58     | 3.96%   |
| Intel                       | 42        | 52     | 3.78%   |
| Unknown                     | 34        | 38     | 3.06%   |
| Hitachi                     | 33        | 42     | 2.97%   |
| Crucial                     | 29        | 38     | 2.61%   |
| Micron Technology           | 19        | 24     | 1.71%   |
| HGST                        | 15        | 24     | 1.35%   |
| Intenso                     | 14        | 19     | 1.26%   |
| LITEON                      | 13        | 21     | 1.17%   |
| PNY                         | 12        | 12     | 1.08%   |
| A-DATA Technology           | 10        | 10     | 0.9%    |
| Phison                      | 9         | 13     | 0.81%   |
| OCZ                         | 9         | 9      | 0.81%   |
| Corsair                     | 9         | 12     | 0.81%   |
| Apple                       | 9         | 14     | 0.81%   |
| LITEONIT                    | 5         | 6      | 0.45%   |
| Phison Electronics          | 4         | 6      | 0.36%   |
| JMicron Technology          | 4         | 4      | 0.36%   |
| Fujitsu                     | 4         | 5      | 0.36%   |
| XPG                         | 3         | 3      | 0.27%   |
| Transcend                   | 3         | 3      | 0.27%   |
| Lenovo                      | 3         | 4      | 0.27%   |
| KIOXIA                      | 3         | 4      | 0.27%   |
| China                       | 3         | 3      | 0.27%   |
| Verbatim                    | 2         | 5      | 0.18%   |
| Silicon Motion              | 2         | 2      | 0.18%   |
| Micron/Crucial Technology   | 2         | 2      | 0.18%   |
| Maxtor                      | 2         | 2      | 0.18%   |
| Kingston Technology Company | 2         | 2      | 0.18%   |
| HUAWEI                      | 2         | 2      | 0.18%   |
| Hewlett-Packard             | 2         | 4      | 0.18%   |
| AFOX                        | 2         | 2      | 0.18%   |
| Unknown                     | 2         | 4      | 0.18%   |
| USB3.0                      | 1         | 1      | 0.09%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB                            | 15        | 1.22%   |
| Samsung SSD 850 EVO 500GB                            | 13        | 1.06%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB               | 13        | 1.06%   |
| Kingston SA400S37240G 240GB SSD                      | 13        | 1.06%   |
| Kingston SV300S37A120G 120GB SSD                     | 12        | 0.97%   |
| Kingston SA400S37480G 480GB SSD                      | 12        | 0.97%   |
| Samsung NVMe SSD Drive 512GB                         | 10        | 0.81%   |
| Samsung NVMe SSD Drive 500GB                         | 10        | 0.81%   |
| Samsung NVMe SSD Drive 1TB                           | 10        | 0.81%   |
| Samsung SSD 860 EVO 1TB                              | 9         | 0.73%   |
| Samsung SSD 840 EVO 250GB                            | 9         | 0.73%   |
| Samsung SSD 860 QVO 1TB                              | 8         | 0.65%   |
| Samsung SSD 860 EVO 500GB                            | 8         | 0.65%   |
| Kingston SA400S37120G 120GB SSD                      | 8         | 0.65%   |
| Toshiba NVMe SSD Drive 256GB                         | 7         | 0.57%   |
| SK hynix NVMe SSD Drive 512GB                        | 7         | 0.57%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB  | 7         | 0.57%   |
| PNY CS900 120GB SSD                                  | 7         | 0.57%   |
| Unknown MMC Card  64GB                               | 6         | 0.49%   |
| Unknown MMC Card  32GB                               | 6         | 0.49%   |
| Toshiba NVMe SSD Drive 512GB                         | 6         | 0.49%   |
| Seagate ST2000DM001-1ER164 2TB                       | 6         | 0.49%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 6         | 0.49%   |
| Crucial CT1000MX500SSD1 1TB                          | 6         | 0.49%   |
| SK hynix HFS256G39TND-N210A 256GB SSD                | 5         | 0.41%   |
| Seagate ST1000DM010-2EP102 1TB                       | 5         | 0.41%   |
| Samsung SSD 970 EVO Plus 1TB                         | 5         | 0.41%   |
| Samsung NVMe SSD Drive 1024GB                        | 5         | 0.41%   |
| Kingston SV300S37A240G 240GB SSD                     | 5         | 0.41%   |
| Kingston SUV400S37240G 240GB SSD                     | 5         | 0.41%   |
| Kingston SUV400S37120G 120GB SSD                     | 5         | 0.41%   |
| Intel NVMe SSD Drive 512GB                           | 5         | 0.41%   |
| Unknown SD/MMC/MS PRO 2GB                            | 4         | 0.32%   |
| Toshiba MQ01ABD100 1TB                               | 4         | 0.32%   |
| SK hynix NVMe SSD Drive 256GB                        | 4         | 0.32%   |
| Seagate ST500DM002-1BD142 500GB                      | 4         | 0.32%   |
| Seagate ST2000DM001-1CH164 2TB                       | 4         | 0.32%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 4         | 0.32%   |
| Seagate ST1000DM003-1SB10C 1TB                       | 4         | 0.32%   |
| Seagate ST1000DM003-1SB102 1TB                       | 4         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 129       | 183    | 36.86%  |
| WDC                 | 109       | 178    | 31.14%  |
| Hitachi             | 33        | 42     | 9.43%   |
| Toshiba             | 32        | 39     | 9.14%   |
| HGST                | 15        | 24     | 4.29%   |
| Samsung Electronics | 11        | 17     | 3.14%   |
| Unknown             | 4         | 5      | 1.14%   |
| Fujitsu             | 4         | 5      | 1.14%   |
| Apple               | 3         | 7      | 0.86%   |
| Maxtor              | 2         | 2      | 0.57%   |
| Unknown             | 2         | 4      | 0.57%   |
| USB3.0              | 1         | 1      | 0.29%   |
| USB                 | 1         | 1      | 0.29%   |
| Intenso             | 1         | 2      | 0.29%   |
| Hewlett-Packard     | 1         | 3      | 0.29%   |
| ASMT109x            | 1         | 1      | 0.29%   |
| Apricorn            | 1         | 2      | 0.29%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 133       | 199    | 31.89%  |
| Kingston            | 77        | 108    | 18.47%  |
| SanDisk             | 25        | 29     | 6%      |
| Crucial             | 24        | 33     | 5.76%   |
| WDC                 | 17        | 20     | 4.08%   |
| Intel               | 15        | 21     | 3.6%    |
| PNY                 | 12        | 12     | 2.88%   |
| LITEON              | 12        | 20     | 2.88%   |
| Toshiba             | 11        | 13     | 2.64%   |
| SK hynix            | 10        | 12     | 2.4%    |
| Intenso             | 10        | 12     | 2.4%    |
| OCZ                 | 9         | 9      | 2.16%   |
| Micron Technology   | 9         | 11     | 2.16%   |
| A-DATA Technology   | 8         | 8      | 1.92%   |
| LITEONIT            | 5         | 6      | 1.2%    |
| Corsair             | 5         | 6      | 1.2%    |
| Apple               | 5         | 5      | 1.2%    |
| JMicron Technology  | 4         | 4      | 0.96%   |
| China               | 3         | 3      | 0.72%   |
| Verbatim            | 2         | 5      | 0.48%   |
| Transcend           | 2         | 2      | 0.48%   |
| AFOX                | 2         | 2      | 0.48%   |
| Unknown (CF)        | 1         | 1      | 0.24%   |
| Teclast             | 1         | 1      | 0.24%   |
| Team                | 1         | 1      | 0.24%   |
| Supersonic          | 1         | 1      | 0.24%   |
| Shark               | 1         | 1      | 0.24%   |
| Patriot             | 1         | 1      | 0.24%   |
| OCZ-VERTEX3         | 1         | 1      | 0.24%   |
| Leven               | 1         | 1      | 0.24%   |
| KingFast            | 1         | 1      | 0.24%   |
| KingDian            | 1         | 1      | 0.24%   |
| Kingchuxing         | 1         | 1      | 0.24%   |
| INDMEM              | 1         | 1      | 0.24%   |
| FORESEE             | 1         | 1      | 0.24%   |
| Dogfish             | 1         | 1      | 0.24%   |
| ASUS-PHISON         | 1         | 1      | 0.24%   |
| ADATA SU            | 1         | 1      | 0.24%   |
| 2-Power             | 1         | 2      | 0.24%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 368       | 558    | 36.95%  |
| NVMe    | 294       | 424    | 29.52%  |
| HDD     | 290       | 516    | 29.12%  |
| MMC     | 32        | 35     | 3.21%   |
| Unknown | 12        | 13     | 1.2%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 550       | 1035   | 59.85%  |
| NVMe | 294       | 424    | 31.99%  |
| SAS  | 43        | 52     | 4.68%   |
| MMC  | 32        | 35     | 3.48%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 422       | 648    | 60.37%  |
| 0.51-1.0   | 165       | 225    | 23.61%  |
| 1.01-2.0   | 52        | 92     | 7.44%   |
| 4.01-10.0  | 20        | 44     | 2.86%   |
| 2.01-3.0   | 18        | 30     | 2.58%   |
| 3.01-4.0   | 16        | 23     | 2.29%   |
| 10.01-20.0 | 6         | 12     | 0.86%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 210       | 25.03%  |
| 251-500        | 167       | 19.9%   |
| 501-1000       | 134       | 15.97%  |
| 1001-2000      | 70        | 8.34%   |
| 1-20           | 62        | 7.39%   |
| 51-100         | 50        | 5.96%   |
| More than 3000 | 46        | 5.48%   |
| Unknown        | 37        | 4.41%   |
| 21-50          | 32        | 3.81%   |
| 2001-3000      | 31        | 3.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 326       | 37.95%  |
| 21-50          | 135       | 15.72%  |
| 101-250        | 105       | 12.22%  |
| 51-100         | 87        | 10.13%  |
| 251-500        | 67        | 7.8%    |
| 501-1000       | 54        | 6.29%   |
| Unknown        | 37        | 4.31%   |
| 1001-2000      | 25        | 2.91%   |
| More than 3000 | 17        | 1.98%   |
| 2001-3000      | 6         | 0.7%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB        | 2         | 2      | 4.17%   |
| Kingston SV300S37A120G 120GB SSD      | 2         | 4      | 4.17%   |
| Kingston SHPM2280P2H 480G SSD         | 2         | 2      | 4.17%   |
| Kingston SA400S37480G 480GB SSD       | 2         | 2      | 4.17%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1         | 1      | 2.08%   |
| WDC WD5000BPVT-80HXZT3 500GB          | 1         | 1      | 2.08%   |
| WDC WD5000BEVT-35ZAT0 500GB           | 1         | 1      | 2.08%   |
| WDC WD5000AAKX-001CA0 500GB           | 1         | 1      | 2.08%   |
| WDC WD5000AADS-00S9B0 500GB           | 1         | 1      | 2.08%   |
| WDC WD10EZRX-00A8LB0 1TB              | 1         | 1      | 2.08%   |
| WDC WD10EZEX-60WN4A0 1TB              | 1         | 1      | 2.08%   |
| WDC WD10EURX-73FH1Y0 1TB              | 1         | 1      | 2.08%   |
| WDC WD10EARS-00Y5B1 1TB               | 1         | 1      | 2.08%   |
| Toshiba THNSNF128GCSS 128GB SSD       | 1         | 1      | 2.08%   |
| Toshiba MQ02ABD100H 1TB               | 1         | 1      | 2.08%   |
| Toshiba KSG60ZSE256G SATA 256GB SSD   | 1         | 1      | 2.08%   |
| SK hynix SC308 SATA 256GB SSD         | 1         | 1      | 2.08%   |
| SK hynix BC711 HFM512GD3JX013N 512GB  | 1         | 1      | 2.08%   |
| Seagate ST9500420AS 500GB             | 1         | 1      | 2.08%   |
| Seagate ST500LT012-9WS142 500GB       | 1         | 1      | 2.08%   |
| Seagate ST380013AS 80GB               | 1         | 1      | 2.08%   |
| Seagate ST3400633AS 400GB             | 1         | 1      | 2.08%   |
| Seagate ST3250318AS 249GB             | 1         | 1      | 2.08%   |
| Seagate ST320LT020-9YG142 320GB       | 1         | 1      | 2.08%   |
| Seagate ST3200822AS 200GB             | 1         | 1      | 2.08%   |
| Seagate ST31000524AS 1TB              | 1         | 1      | 2.08%   |
| Seagate ST2000DX002-2DV164 2TB        | 1         | 1      | 2.08%   |
| Seagate ST2000DM008-2FR102 2TB        | 1         | 1      | 2.08%   |
| Seagate ST1000DM010-2EP102 1TB        | 1         | 1      | 2.08%   |
| SanDisk SDSSDX240GG25 240GB           | 1         | 1      | 2.08%   |
| Samsung Electronics SSD 870 EVO 500GB | 1         | 1      | 2.08%   |
| Samsung Electronics SP0812C 80GB      | 1         | 1      | 2.08%   |
| Samsung Electronics HD753LJ 752GB     | 1         | 1      | 2.08%   |
| Samsung Electronics HD103SJ 1TB       | 1         | 1      | 2.08%   |
| OCZ AGILITY3 240GB SSD                | 1         | 1      | 2.08%   |
| OCZ AGILITY3 120GB SSD                | 1         | 1      | 2.08%   |
| Micron Technology 1100 SATA 512GB SSD | 1         | 1      | 2.08%   |
| Leven JAJS300M480C 480GB SSD          | 1         | 1      | 2.08%   |
| Intel SSDSC2BW480H6 480GB             | 1         | 1      | 2.08%   |
| Hitachi HDP725032GLA360 320GB         | 1         | 2      | 2.08%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 13     | 26.67%  |
| WDC                 | 8         | 9      | 17.78%  |
| Kingston            | 6         | 8      | 13.33%  |
| Toshiba             | 3         | 3      | 6.67%   |
| Samsung Electronics | 3         | 4      | 6.67%   |
| SK hynix            | 2         | 2      | 4.44%   |
| OCZ                 | 2         | 2      | 4.44%   |
| HGST                | 2         | 2      | 4.44%   |
| SanDisk             | 1         | 1      | 2.22%   |
| Micron Technology   | 1         | 1      | 2.22%   |
| Leven               | 1         | 1      | 2.22%   |
| Intel               | 1         | 1      | 2.22%   |
| Hitachi             | 1         | 2      | 2.22%   |
| Apple               | 1         | 1      | 2.22%   |
| Unknown             | 1         | 2      | 2.22%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 13     | 44.44%  |
| WDC                 | 7         | 8      | 25.93%  |
| Samsung Electronics | 2         | 3      | 7.41%   |
| HGST                | 2         | 2      | 7.41%   |
| Toshiba             | 1         | 1      | 3.7%    |
| Hitachi             | 1         | 2      | 3.7%    |
| Apple               | 1         | 1      | 3.7%    |
| Unknown             | 1         | 2      | 3.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 23        | 32     | 57.5%   |
| SSD  | 16        | 19     | 40%     |
| NVMe | 1         | 1      | 2.5%    |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 541       | 1042   | 63.95%  |
| Works    | 265       | 452    | 31.32%  |
| Malfunc  | 40        | 52     | 4.73%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 493       | 49.3%   |
| AMD                              | 143       | 14.3%   |
| Samsung Electronics              | 125       | 12.5%   |
| SanDisk                          | 39        | 3.9%    |
| SK hynix                         | 33        | 3.3%    |
| ASMedia Technology               | 22        | 2.2%    |
| Toshiba America Info Systems     | 21        | 2.1%    |
| Kingston Technology Company      | 20        | 2%      |
| Nvidia                           | 18        | 1.8%    |
| Phison Electronics               | 17        | 1.7%    |
| Micron Technology                | 11        | 1.1%    |
| JMicron Technology               | 11        | 1.1%    |
| Marvell Technology Group         | 8         | 0.8%    |
| Silicon Motion                   | 6         | 0.6%    |
| Micron/Crucial Technology        | 6         | 0.6%    |
| ADATA Technology                 | 5         | 0.5%    |
| Seagate Technology               | 3         | 0.3%    |
| Lenovo                           | 3         | 0.3%    |
| KIOXIA                           | 3         | 0.3%    |
| VIA Technologies                 | 2         | 0.2%    |
| Hewlett-Packard                  | 2         | 0.2%    |
| Union Memory (Shenzhen)          | 1         | 0.1%    |
| Solid State Storage Technology   | 1         | 0.1%    |
| Silicon Integrated Systems [SiS] | 1         | 0.1%    |
| Realtek Semiconductor            | 1         | 0.1%    |
| LSI Logic / Symbios Logic        | 1         | 0.1%    |
| Lite-On Technology               | 1         | 0.1%    |
| HighPoint Technologies           | 1         | 0.1%    |
| Broadcom / LSI                   | 1         | 0.1%    |
| Apple                            | 1         | 0.1%    |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 100       | 8.76%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 72        | 6.3%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 49        | 4.29%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 37        | 3.24%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 33        | 2.89%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 28        | 2.45%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 27        | 2.36%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 24        | 2.1%    |
| AMD 400 Series Chipset SATA Controller                                         | 24        | 2.1%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 20        | 1.75%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 20        | 1.75%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 20        | 1.75%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 19        | 1.66%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 18        | 1.58%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 18        | 1.58%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 18        | 1.58%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 15        | 1.31%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 14        | 1.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 14        | 1.23%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 13        | 1.14%   |
| Intel SSD 660P Series                                                          | 13        | 1.14%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 13        | 1.14%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 13        | 1.14%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 13        | 1.14%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 12        | 1.05%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 12        | 1.05%   |
| AMD 500 Series Chipset SATA Controller                                         | 12        | 1.05%   |
| Micron Non-Volatile memory controller                                          | 11        | 0.96%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 11        | 0.96%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 11        | 0.96%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 11        | 0.96%   |
| Phison E12 NVMe Controller                                                     | 10        | 0.88%   |
| Intel Volume Management Device NVMe RAID Controller                            | 10        | 0.88%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 9         | 0.79%   |
| Kingston Company A2000 NVMe SSD                                                | 9         | 0.79%   |
| Intel Comet Lake SATA AHCI Controller                                          | 9         | 0.79%   |
| SK hynix Non-Volatile memory controller                                        | 8         | 0.7%    |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 7         | 0.61%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 7         | 0.61%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 7         | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 568       | 56.52%  |
| NVMe | 297       | 29.55%  |
| IDE  | 93        | 9.25%   |
| RAID | 46        | 4.58%   |
| SAS  | 1         | 0.1%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 583       | 74.17%  |
| AMD      | 193       | 24.55%  |
| ARM      | 9         | 1.15%   |
| QUALCOMM | 1         | 0.13%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz             | 13        | 1.65%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 12        | 1.52%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 12        | 1.52%   |
| AMD Ryzen 5 3600 6-Core Processor             | 10        | 1.27%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 8         | 1.02%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 8         | 1.02%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 8         | 1.02%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 7         | 0.89%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 7         | 0.89%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 7         | 0.89%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 7         | 0.89%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 6         | 0.76%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 6         | 0.76%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 6         | 0.76%   |
| Intel Core i5-6600K CPU @ 3.50GHz             | 6         | 0.76%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 6         | 0.76%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 6         | 0.76%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 6         | 0.76%   |
| ARM Processor                                 | 6         | 0.76%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 6         | 0.76%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 6         | 0.76%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 6         | 0.76%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 6         | 0.76%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 5         | 0.64%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 5         | 0.64%   |
| Intel Core i5-7500 CPU @ 3.40GHz              | 5         | 0.64%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 5         | 0.64%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 5         | 0.64%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 5         | 0.64%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 4         | 0.51%   |
| Intel Core i9-9900K CPU @ 3.60GHz             | 4         | 0.51%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 4         | 0.51%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 4         | 0.51%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 4         | 0.51%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 4         | 0.51%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 4         | 0.51%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 4         | 0.51%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 4         | 0.51%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 4         | 0.51%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 4         | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 193       | 24.52%  |
| Intel Core i7           | 190       | 24.14%  |
| AMD Ryzen 7             | 45        | 5.72%   |
| Intel Core i3           | 37        | 4.7%    |
| AMD Ryzen 5             | 37        | 4.7%    |
| Other                   | 35        | 4.45%   |
| Intel Core 2 Duo        | 34        | 4.32%   |
| Intel Celeron           | 26        | 3.3%    |
| AMD Ryzen 9             | 23        | 2.92%   |
| Intel Xeon              | 14        | 1.78%   |
| Intel Pentium           | 10        | 1.27%   |
| Intel Core i9           | 10        | 1.27%   |
| AMD Ryzen 7 PRO         | 10        | 1.27%   |
| Intel Pentium Dual-Core | 9         | 1.14%   |
| Intel Atom              | 9         | 1.14%   |
| AMD FX                  | 9         | 1.14%   |
| AMD Ryzen 3             | 8         | 1.02%   |
| AMD A6                  | 8         | 1.02%   |
| AMD A8                  | 7         | 0.89%   |
| Intel Core 2 Quad       | 4         | 0.51%   |
| Intel Core 2            | 4         | 0.51%   |
| AMD Ryzen 5 PRO         | 4         | 0.51%   |
| AMD Phenom II X4        | 4         | 0.51%   |
| AMD Athlon 64 X2        | 4         | 0.51%   |
| AMD A10                 | 4         | 0.51%   |
| Intel Pentium Silver    | 3         | 0.38%   |
| Intel Pentium M         | 3         | 0.38%   |
| Intel Pentium Dual      | 3         | 0.38%   |
| ARM BCM                 | 3         | 0.38%   |
| AMD Ryzen Threadripper  | 3         | 0.38%   |
| AMD E                   | 3         | 0.38%   |
| AMD Athlon II X4        | 3         | 0.38%   |
| AMD A4                  | 3         | 0.38%   |
| Intel Genuine           | 2         | 0.25%   |
| Intel Core m5           | 2         | 0.25%   |
| Intel Core m3           | 2         | 0.25%   |
| AMD Turion 64 X2 Mobile | 2         | 0.25%   |
| AMD E1                  | 2         | 0.25%   |
| AMD Athlon II Neo       | 2         | 0.25%   |
| AMD Athlon              | 2         | 0.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 296       | 37.61%  |
| 4       | 287       | 36.47%  |
| 6       | 79        | 10.04%  |
| 8       | 78        | 9.91%   |
| 12      | 17        | 2.16%   |
| 1       | 16        | 2.03%   |
| 16      | 8         | 1.02%   |
| 64      | 1         | 0.13%   |
| 32      | 1         | 0.13%   |
| 24      | 1         | 0.13%   |
| 14      | 1         | 0.13%   |
| 10      | 1         | 0.13%   |
| Unknown | 1         | 0.13%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 781       | 99.36%  |
| 2       | 4         | 0.51%   |
| Unknown | 1         | 0.13%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 549       | 69.85%  |
| 1       | 236       | 30.03%  |
| Unknown | 1         | 0.13%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 757       | 95.7%   |
| Unknown        | 29        | 3.67%   |
| 32-bit         | 5         | 0.63%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 185       | 22.78%  |
| 0x306a9    | 39        | 4.8%    |
| 0x206a7    | 39        | 4.8%    |
| 0x306c3    | 37        | 4.56%   |
| 0x1067a    | 29        | 3.57%   |
| 0x40651    | 28        | 3.45%   |
| 0x406e3    | 27        | 3.33%   |
| 0x906ea    | 24        | 2.96%   |
| 0x806e9    | 22        | 2.71%   |
| 0x506e3    | 22        | 2.71%   |
| 0x806ea    | 20        | 2.46%   |
| 0x806ec    | 16        | 1.97%   |
| 0x906e9    | 15        | 1.85%   |
| 0x20655    | 12        | 1.48%   |
| 0x08600106 | 11        | 1.35%   |
| 0x906ed    | 10        | 1.23%   |
| 0x0800820d | 10        | 1.23%   |
| 0x0a50000c | 9         | 1.11%   |
| 0x08701021 | 9         | 1.11%   |
| 0x806eb    | 8         | 0.99%   |
| 0x806c1    | 8         | 0.99%   |
| 0x20652    | 8         | 0.99%   |
| 0x706e5    | 7         | 0.86%   |
| 0x6fd      | 7         | 0.86%   |
| 0x08701013 | 7         | 0.86%   |
| 0x08001138 | 7         | 0.86%   |
| 0x010000c8 | 7         | 0.86%   |
| 0x406c3    | 6         | 0.74%   |
| 0x10676    | 6         | 0.74%   |
| 0x0a201009 | 6         | 0.74%   |
| 0x08600104 | 6         | 0.74%   |
| 0x0810100b | 6         | 0.74%   |
| 0x90672    | 5         | 0.62%   |
| 0x306d4    | 5         | 0.62%   |
| 0x08108102 | 5         | 0.62%   |
| 0x07030105 | 5         | 0.62%   |
| 0x06000852 | 5         | 0.62%   |
| 0xa0653    | 4         | 0.49%   |
| 0x906ec    | 4         | 0.49%   |
| 0x706a1    | 4         | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 155       | 19.7%   |
| Haswell          | 78        | 9.91%   |
| Skylake          | 62        | 7.88%   |
| SandyBridge      | 51        | 6.48%   |
| IvyBridge        | 51        | 6.48%   |
| Zen 2            | 49        | 6.23%   |
| Penryn           | 43        | 5.46%   |
| Unknown          | 33        | 4.19%   |
| Zen 3            | 27        | 3.43%   |
| Westmere         | 24        | 3.05%   |
| Zen+             | 23        | 2.92%   |
| Core             | 18        | 2.29%   |
| Zen              | 17        | 2.16%   |
| Silvermont       | 17        | 2.16%   |
| CometLake        | 14        | 1.78%   |
| K10              | 12        | 1.52%   |
| Broadwell        | 12        | 1.52%   |
| TigerLake        | 11        | 1.4%    |
| Piledriver       | 10        | 1.27%   |
| IceLake          | 10        | 1.27%   |
| Puma             | 7         | 0.89%   |
| K8 Hammer        | 7         | 0.89%   |
| Excavator        | 7         | 0.89%   |
| Alderlake Hybrid | 7         | 0.89%   |
| Nehalem          | 6         | 0.76%   |
| Goldmont plus    | 6         | 0.76%   |
| P6               | 5         | 0.64%   |
| Bobcat           | 5         | 0.64%   |
| Steamroller      | 4         | 0.51%   |
| Bonnell          | 4         | 0.51%   |
| K8 & K10 hybrid  | 3         | 0.38%   |
| Jaguar           | 3         | 0.38%   |
| Goldmont         | 3         | 0.38%   |
| Bulldozer        | 2         | 0.25%   |
| K10 Llano        | 1         | 0.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 432       | 46.5%   |
| Nvidia                           | 296       | 31.86%  |
| AMD                              | 196       | 21.1%   |
| Matrox Electronics Systems       | 2         | 0.22%   |
| ASPEED Technology                | 2         | 0.22%   |
| Silicon Integrated Systems [SiS] | 1         | 0.11%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 38        | 3.97%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 29        | 3.03%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 29        | 3.03%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 29        | 3.03%   |
| Intel UHD Graphics 620                                                                   | 28        | 2.93%   |
| Intel HD Graphics 620                                                                    | 23        | 2.41%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 23        | 2.41%   |
| AMD Renoir                                                                               | 21        | 2.2%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 17        | 1.78%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 16        | 1.67%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 16        | 1.67%   |
| Intel HD Graphics 630                                                                    | 15        | 1.57%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 14        | 1.46%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 13        | 1.36%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 11        | 1.15%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 11        | 1.15%   |
| Intel HD Graphics 530                                                                    | 11        | 1.15%   |
| Intel Core Processor Integrated Graphics Controller                                      | 11        | 1.15%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 11        | 1.15%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 11        | 1.15%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 11        | 1.15%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 10        | 1.05%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 9         | 0.94%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 9         | 0.94%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 8         | 0.84%   |
| Intel HD Graphics 5500                                                                   | 7         | 0.73%   |
| Nvidia GP108M [GeForce MX150]                                                            | 6         | 0.63%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 6         | 0.63%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 6         | 0.63%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 6         | 0.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 6         | 0.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 6         | 0.63%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 6         | 0.63%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 0.63%   |
| AMD Rembrandt [Radeon 680M]                                                              | 6         | 0.63%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 6         | 0.63%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 6         | 0.63%   |
| AMD Lucienne                                                                             | 6         | 0.63%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 5         | 0.52%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 5         | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 298       | 37.82%  |
| 1 x Nvidia      | 175       | 22.21%  |
| 1 x AMD         | 143       | 18.15%  |
| Intel + Nvidia  | 101       | 12.82%  |
| 2 x AMD         | 18        | 2.28%   |
| Intel + AMD     | 18        | 2.28%   |
| AMD + Nvidia    | 16        | 2.03%   |
| Other           | 12        | 1.52%   |
| 2 x Nvidia      | 2         | 0.25%   |
| 1 x Matrox      | 2         | 0.25%   |
| 1 x SiS         | 1         | 0.13%   |
| Nvidia + ASPEED | 1         | 0.13%   |
| 1 x ASPEED      | 1         | 0.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 605       | 75.44%  |
| Proprietary | 168       | 20.95%  |
| Unknown     | 29        | 3.62%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 427       | 53.24%  |
| 1.01-2.0   | 114       | 14.21%  |
| 0.01-0.5   | 93        | 11.6%   |
| 3.01-4.0   | 43        | 5.36%   |
| 7.01-8.0   | 41        | 5.11%   |
| 0.51-1.0   | 39        | 4.86%   |
| 5.01-6.0   | 29        | 3.62%   |
| 8.01-16.0  | 10        | 1.25%   |
| 2.01-3.0   | 4         | 0.5%    |
| 4.01-5.0   | 1         | 0.12%   |
| 16.01-24.0 | 1         | 0.12%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 126       | 13.92%  |
| AU Optronics            | 119       | 13.15%  |
| LG Display              | 80        | 8.84%   |
| Chimei Innolux          | 61        | 6.74%   |
| BOE                     | 58        | 6.41%   |
| Dell                    | 56        | 6.19%   |
| Lenovo                  | 43        | 4.75%   |
| Philips                 | 28        | 3.09%   |
| Hewlett-Packard         | 28        | 3.09%   |
| AOC                     | 28        | 3.09%   |
| Apple                   | 23        | 2.54%   |
| Ancor Communications    | 23        | 2.54%   |
| BenQ                    | 20        | 2.21%   |
| Goldstar                | 19        | 2.1%    |
| Acer                    | 19        | 2.1%    |
| Sharp                   | 18        | 1.99%   |
| ASUSTek Computer        | 17        | 1.88%   |
| Sony                    | 14        | 1.55%   |
| Chi Mei Optoelectronics | 12        | 1.33%   |
| PANDA                   | 8         | 0.88%   |
| Panasonic               | 7         | 0.77%   |
| InfoVision              | 7         | 0.77%   |
| Unknown                 | 6         | 0.66%   |
| Packard Bell            | 5         | 0.55%   |
| Medion                  | 5         | 0.55%   |
| Lenovo Group Limited    | 5         | 0.55%   |
| ViewSonic               | 4         | 0.44%   |
| MSI                     | 4         | 0.44%   |
| LG Electronics          | 4         | 0.44%   |
| IBM                     | 4         | 0.44%   |
| Vestel Elektronik       | 3         | 0.33%   |
| LG Philips              | 3         | 0.33%   |
| Gigabyte Technology     | 3         | 0.33%   |
| Fujitsu Siemens         | 3         | 0.33%   |
| TMX                     | 2         | 0.22%   |
| Tech Concepts           | 2         | 0.22%   |
| Seiko/Epson             | 2         | 0.22%   |
| LGD                     | 2         | 0.22%   |
| Idek Iiyama             | 2         | 0.22%   |
| CSO                     | 2         | 0.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch                  | 7         | 0.73%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch           | 6         | 0.63%   |
| ASUSTek Computer VA326 AUS32FA 1920x1080 698x393mm 31.5-inch             | 6         | 0.63%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 5         | 0.52%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 5         | 0.52%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                         | 4         | 0.42%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 4         | 0.42%   |
| Panasonic VVX14P048M00 MEI96A2 3000x2000 285x190mm 13.5-inch             | 4         | 0.42%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 4         | 0.42%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch         | 4         | 0.42%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch           | 4         | 0.42%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch           | 4         | 0.42%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 4         | 0.42%   |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                       | 4         | 0.42%   |
| Vestel Elektronik 50FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch    | 3         | 0.31%   |
| Sony TV SNYEE01 1920x1080                                                | 3         | 0.31%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 3         | 0.31%   |
| Samsung Electronics LCD Monitor S24F350 1920x1080                        | 3         | 0.31%   |
| Packard Bell Maestro223DXL PKB01B2 1920x1080 477x268mm 21.5-inch         | 3         | 0.31%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                 | 3         | 0.31%   |
| Gigabyte Technology G32QC GBT3200 2560x1440 697x392mm 31.5-inch          | 3         | 0.31%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                        | 3         | 0.31%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 3         | 0.31%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 3         | 0.31%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 276x155mm 12.5-inch         | 3         | 0.31%   |
| Chi Mei Optoelectronics LCD Monitor CMO1719 1600x900 382x215mm 17.3-inch | 3         | 0.31%   |
| BOE LCD Monitor BOE0A1D 2560x1600 302x189mm 14.0-inch                    | 3         | 0.31%   |
| BOE LCD Monitor BOE0691 1920x1080 280x165mm 12.8-inch                    | 3         | 0.31%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 3         | 0.31%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch           | 3         | 0.31%   |
| AU Optronics LCD Monitor AUO113D 1920x1080 309x173mm 13.9-inch           | 3         | 0.31%   |
| AU Optronics LCD Monitor AUO109E 1600x900 382x214mm 17.2-inch            | 3         | 0.31%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 3         | 0.31%   |
| AOC 2460 AOC2460 1920x1080 531x299mm 24.0-inch                           | 3         | 0.31%   |
| Ancor Communications MX279 ACI27C3 1920x1080 600x340mm 27.2-inch         | 3         | 0.31%   |
| Acer KG241Q ACR0604 1920x1080 521x293mm 23.5-inch                        | 3         | 0.31%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch                  | 2         | 0.21%   |
| Tech Concepts LCD Monitor TCL SMART TV 3840x2160                         | 2         | 0.21%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                  | 2         | 0.21%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                  | 2         | 0.21%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 402       | 46.26%  |
| 1366x768 (WXGA)    | 97        | 11.16%  |
| 3840x2160 (4K)     | 78        | 8.98%   |
| 2560x1440 (QHD)    | 65        | 7.48%   |
| 1600x900 (HD+)     | 42        | 4.83%   |
| 1680x1050 (WSXGA+) | 25        | 2.88%   |
| 1920x1200 (WUXGA)  | 19        | 2.19%   |
| 1280x800 (WXGA)    | 18        | 2.07%   |
| Unknown            | 17        | 1.96%   |
| 1280x1024 (SXGA)   | 16        | 1.84%   |
| 1440x900 (WXGA+)   | 14        | 1.61%   |
| 3440x1440          | 11        | 1.27%   |
| 2560x1600          | 8         | 0.92%   |
| 3840x1080          | 7         | 0.81%   |
| 2880x1800          | 7         | 0.81%   |
| 1360x768           | 4         | 0.46%   |
| 2160x1440          | 3         | 0.35%   |
| 1920x540           | 3         | 0.35%   |
| 1400x1050          | 3         | 0.35%   |
| 800x1280           | 2         | 0.23%   |
| 3840x2400          | 2         | 0.23%   |
| 3840x1600          | 2         | 0.23%   |
| 3840x1200          | 2         | 0.23%   |
| 3200x1800 (QHD+)   | 2         | 0.23%   |
| 3000x2000          | 2         | 0.23%   |
| 1024x600           | 2         | 0.23%   |
| 9840x3840          | 1         | 0.12%   |
| 6400x2160          | 1         | 0.12%   |
| 5760x1440          | 1         | 0.12%   |
| 5760x1080          | 1         | 0.12%   |
| 5120x1440          | 1         | 0.12%   |
| 4608x1440          | 1         | 0.12%   |
| 4480x1440          | 1         | 0.12%   |
| 3840x1100          | 1         | 0.12%   |
| 3200x1200          | 1         | 0.12%   |
| 3200x1080          | 1         | 0.12%   |
| 2736x1824          | 1         | 0.12%   |
| 2560x1080          | 1         | 0.12%   |
| 2560x1024          | 1         | 0.12%   |
| 2048x1152          | 1         | 0.12%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 200       | 22.1%   |
| 27      | 94        | 10.39%  |
| 14      | 89        | 9.83%   |
| 13      | 86        | 9.5%    |
| 24      | 76        | 8.4%    |
| Unknown | 61        | 6.74%   |
| 23      | 48        | 5.3%    |
| 17      | 44        | 4.86%   |
| 31      | 30        | 3.31%   |
| 21      | 30        | 3.31%   |
| 12      | 26        | 2.87%   |
| 19      | 17        | 1.88%   |
| 22      | 16        | 1.77%   |
| 20      | 11        | 1.22%   |
| 84      | 10        | 1.1%    |
| 72      | 10        | 1.1%    |
| 34      | 10        | 1.1%    |
| 11      | 7         | 0.77%   |
| 32      | 4         | 0.44%   |
| 18      | 4         | 0.44%   |
| 25      | 3         | 0.33%   |
| 10      | 3         | 0.33%   |
| 65      | 2         | 0.22%   |
| 55      | 2         | 0.22%   |
| 54      | 2         | 0.22%   |
| 37      | 2         | 0.22%   |
| 29      | 2         | 0.22%   |
| 28      | 2         | 0.22%   |
| 16      | 2         | 0.22%   |
| 75      | 1         | 0.11%   |
| 60      | 1         | 0.11%   |
| 57      | 1         | 0.11%   |
| 48      | 1         | 0.11%   |
| 42      | 1         | 0.11%   |
| 40      | 1         | 0.11%   |
| 39      | 1         | 0.11%   |
| 38      | 1         | 0.11%   |
| 35      | 1         | 0.11%   |
| 33      | 1         | 0.11%   |
| 30      | 1         | 0.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 325       | 36.97%  |
| 501-600     | 185       | 21.05%  |
| 201-300     | 81        | 9.22%   |
| 401-500     | 66        | 7.51%   |
| Unknown     | 61        | 6.94%   |
| 351-400     | 60        | 6.83%   |
| 601-700     | 48        | 5.46%   |
| 1501-2000   | 21        | 2.39%   |
| 701-800     | 15        | 1.71%   |
| 1001-1500   | 9         | 1.02%   |
| 801-900     | 6         | 0.68%   |
| 901-1000    | 1         | 0.11%   |
| 1-100       | 1         | 0.11%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 600       | 75.19%  |
| 16/10   | 100       | 12.53%  |
| Unknown | 51        | 6.39%   |
| 5/4     | 14        | 1.75%   |
| 21/9    | 14        | 1.75%   |
| 3/2     | 9         | 1.13%   |
| 4/3     | 5         | 0.63%   |
| 32/9    | 2         | 0.25%   |
| 3.40    | 1         | 0.13%   |
| 0.67    | 1         | 0.13%   |
| 0.62    | 1         | 0.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 199       | 22.19%  |
| 81-90          | 137       | 15.27%  |
| 201-250        | 131       | 14.6%   |
| 301-350        | 94        | 10.48%  |
| Unknown        | 61        | 6.8%    |
| 351-500        | 49        | 5.46%   |
| 71-80          | 40        | 4.46%   |
| 151-200        | 34        | 3.79%   |
| 121-130        | 33        | 3.68%   |
| 251-300        | 31        | 3.46%   |
| More than 1000 | 29        | 3.23%   |
| 61-70          | 22        | 2.45%   |
| 51-60          | 8         | 0.89%   |
| 131-140        | 8         | 0.89%   |
| 501-1000       | 7         | 0.78%   |
| 141-150        | 6         | 0.67%   |
| 41-50          | 3         | 0.33%   |
| 111-120        | 2         | 0.22%   |
| 91-100         | 2         | 0.22%   |
| 1-40           | 1         | 0.11%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 261       | 30.21%  |
| 51-100        | 251       | 29.05%  |
| 101-120       | 188       | 21.76%  |
| Unknown       | 61        | 7.06%   |
| 161-240       | 55        | 6.37%   |
| More than 240 | 30        | 3.47%   |
| 1-50          | 18        | 2.08%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 612       | 75.84%  |
| 2     | 145       | 17.97%  |
| 0     | 27        | 3.35%   |
| 3     | 21        | 2.6%    |
| 4     | 2         | 0.25%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 441       | 37.22%  |
| Realtek Semiconductor             | 373       | 31.48%  |
| Qualcomm Atheros                  | 107       | 9.03%   |
| Broadcom                          | 61        | 5.15%   |
| MediaTek                          | 17        | 1.43%   |
| Nvidia                            | 16        | 1.35%   |
| Lenovo                            | 14        | 1.18%   |
| Broadcom Limited                  | 14        | 1.18%   |
| Ralink                            | 13        | 1.1%    |
| Sierra Wireless                   | 12        | 1.01%   |
| Ralink Technology                 | 10        | 0.84%   |
| Ericsson Business Mobile Networks | 9         | 0.76%   |
| Marvell Technology Group          | 8         | 0.68%   |
| TP-Link                           | 6         | 0.51%   |
| DisplayLink                       | 6         | 0.51%   |
| ASUSTek Computer                  | 6         | 0.51%   |
| ASIX Electronics                  | 6         | 0.51%   |
| Huawei Technologies               | 5         | 0.42%   |
| Aquantia                          | 5         | 0.42%   |
| Samsung Electronics               | 4         | 0.34%   |
| Qualcomm Atheros Communications   | 4         | 0.34%   |
| OnePlus Technology (Shenzhen)     | 4         | 0.34%   |
| NetGear                           | 4         | 0.34%   |
| IMC Networks                      | 4         | 0.34%   |
| Dell                              | 4         | 0.34%   |
| Qualcomm                          | 3         | 0.25%   |
| Edimax Technology                 | 3         | 0.25%   |
| Xiaomi                            | 2         | 0.17%   |
| Microsoft                         | 2         | 0.17%   |
| Linksys                           | 2         | 0.17%   |
| ICS Advent                        | 2         | 0.17%   |
| D-Link System                     | 2         | 0.17%   |
| D-Link                            | 2         | 0.17%   |
| ZyXEL Communications              | 1         | 0.08%   |
| Unknown                           | 1         | 0.08%   |
| Texas Instruments                 | 1         | 0.08%   |
| Standard Microsystems             | 1         | 0.08%   |
| Solarflare Communications         | 1         | 0.08%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.08%   |
| Philips (or NXP)                  | 1         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 263       | 18.25%  |
| Intel Wi-Fi 6 AX200                                               | 45        | 3.12%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 35        | 2.43%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 34        | 2.36%   |
| Intel Wireless 8265 / 8275                                        | 34        | 2.36%   |
| Intel Wireless 7260                                               | 29        | 2.01%   |
| Intel I211 Gigabit Network Connection                             | 25        | 1.73%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 25        | 1.73%   |
| Intel Wireless 8260                                               | 24        | 1.67%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 23        | 1.6%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 20        | 1.39%   |
| Intel Wireless 7265                                               | 19        | 1.32%   |
| Intel Ethernet Connection (2) I219-V                              | 18        | 1.25%   |
| Realtek RTL8125 2.5GbE Controller                                 | 17        | 1.18%   |
| Intel Ethernet Connection I217-LM                                 | 16        | 1.11%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 14        | 0.97%   |
| Intel Wireless-AC 9260                                            | 14        | 0.97%   |
| Intel Ethernet Connection (4) I219-LM                             | 14        | 0.97%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 14        | 0.97%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 13        | 0.9%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 13        | 0.9%    |
| Intel Ethernet Connection I218-LM                                 | 12        | 0.83%   |
| Intel Ethernet Connection (7) I219-V                              | 12        | 0.83%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 12        | 0.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 11        | 0.76%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 11        | 0.76%   |
| Intel Ethernet Connection I219-LM                                 | 10        | 0.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 9         | 0.62%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 9         | 0.62%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 9         | 0.62%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 9         | 0.62%   |
| Intel Ethernet Controller I225-V                                  | 9         | 0.62%   |
| Intel Ethernet Connection I219-V                                  | 9         | 0.62%   |
| Intel Ethernet Connection (4) I219-V                              | 9         | 0.62%   |
| Intel Centrino Wireless-N 2230                                    | 9         | 0.62%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 9         | 0.62%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 8         | 0.56%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 8         | 0.56%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 8         | 0.56%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 8         | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 348       | 52.65%  |
| Qualcomm Atheros                  | 85        | 12.86%  |
| Realtek Semiconductor             | 81        | 12.25%  |
| Broadcom                          | 42        | 6.35%   |
| MediaTek                          | 16        | 2.42%   |
| Ralink                            | 13        | 1.97%   |
| Sierra Wireless                   | 12        | 1.82%   |
| Ralink Technology                 | 10        | 1.51%   |
| Broadcom Limited                  | 8         | 1.21%   |
| TP-Link                           | 6         | 0.91%   |
| ASUSTek Computer                  | 6         | 0.91%   |
| Qualcomm Atheros Communications   | 4         | 0.61%   |
| NetGear                           | 4         | 0.61%   |
| IMC Networks                      | 4         | 0.61%   |
| Edimax Technology                 | 3         | 0.45%   |
| Dell                              | 3         | 0.45%   |
| Qualcomm                          | 2         | 0.3%    |
| Microsoft                         | 2         | 0.3%    |
| Marvell Technology Group          | 2         | 0.3%    |
| Ericsson Business Mobile Networks | 2         | 0.3%    |
| D-Link System                     | 2         | 0.3%    |
| D-Link                            | 2         | 0.3%    |
| ZyXEL Communications              | 1         | 0.15%   |
| Philips (or NXP)                  | 1         | 0.15%   |
| Linksys                           | 1         | 0.15%   |
| Fibocom                           | 1         | 0.15%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 45        | 6.77%   |
| Intel Wireless 8265 / 8275                                              | 34        | 5.11%   |
| Intel Wireless 7260                                                     | 29        | 4.36%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 25        | 3.76%   |
| Intel Wireless 8260                                                     | 24        | 3.61%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 20        | 3.01%   |
| Intel Wireless 7265                                                     | 19        | 2.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 14        | 2.11%   |
| Intel Wireless-AC 9260                                                  | 14        | 2.11%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 14        | 2.11%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 13        | 1.95%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 13        | 1.95%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 12        | 1.8%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 11        | 1.65%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 11        | 1.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 9         | 1.35%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 9         | 1.35%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 9         | 1.35%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 9         | 1.35%   |
| Intel Centrino Wireless-N 2230                                          | 9         | 1.35%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 9         | 1.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 8         | 1.2%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 8         | 1.2%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 8         | 1.2%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 8         | 1.2%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 8         | 1.2%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 7         | 1.05%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 7         | 1.05%   |
| Intel Centrino Ultimate-N 6300                                          | 7         | 1.05%   |
| Sierra Wireless EM7455                                                  | 6         | 0.9%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 0.9%    |
| Intel Wi-Fi 6 AX201                                                     | 6         | 0.9%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 6         | 0.9%    |
| Sierra Wireless EM7345 4G LTE                                           | 5         | 0.75%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 5         | 0.75%   |
| Realtek 802.11ac NIC                                                    | 5         | 0.75%   |
| Intel Wireless 3165                                                     | 5         | 0.75%   |
| Intel Wireless 3160                                                     | 5         | 0.75%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 0.75%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 5         | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 342       | 45.97%  |
| Intel                            | 264       | 35.48%  |
| Qualcomm Atheros                 | 30        | 4.03%   |
| Broadcom                         | 26        | 3.49%   |
| Nvidia                           | 16        | 2.15%   |
| Lenovo                           | 14        | 1.88%   |
| Marvell Technology Group         | 6         | 0.81%   |
| DisplayLink                      | 6         | 0.81%   |
| Broadcom Limited                 | 6         | 0.81%   |
| ASIX Electronics                 | 6         | 0.81%   |
| Aquantia                         | 5         | 0.67%   |
| Samsung Electronics              | 4         | 0.54%   |
| OnePlus Technology (Shenzhen)    | 3         | 0.4%    |
| Xiaomi                           | 2         | 0.27%   |
| ICS Advent                       | 2         | 0.27%   |
| Huawei Technologies              | 2         | 0.27%   |
| Standard Microsystems            | 1         | 0.13%   |
| Solarflare Communications        | 1         | 0.13%   |
| Silicon Integrated Systems [SiS] | 1         | 0.13%   |
| Qualcomm                         | 1         | 0.13%   |
| Microchip Technology             | 1         | 0.13%   |
| MediaTek                         | 1         | 0.13%   |
| Linksys                          | 1         | 0.13%   |
| JMicron Technology               | 1         | 0.13%   |
| HMD Global                       | 1         | 0.13%   |
| Google                           | 1         | 0.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 263       | 34.65%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 35        | 4.61%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 34        | 4.48%   |
| Intel I211 Gigabit Network Connection                             | 25        | 3.29%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 23        | 3.03%   |
| Intel Ethernet Connection (2) I219-V                              | 18        | 2.37%   |
| Realtek RTL8125 2.5GbE Controller                                 | 17        | 2.24%   |
| Intel Ethernet Connection I217-LM                                 | 16        | 2.11%   |
| Intel Ethernet Connection (4) I219-LM                             | 14        | 1.84%   |
| Intel Ethernet Connection I218-LM                                 | 12        | 1.58%   |
| Intel Ethernet Connection (7) I219-V                              | 12        | 1.58%   |
| Intel Ethernet Connection I219-LM                                 | 10        | 1.32%   |
| Intel Ethernet Controller I225-V                                  | 9         | 1.19%   |
| Intel Ethernet Connection I219-V                                  | 9         | 1.19%   |
| Intel Ethernet Connection (4) I219-V                              | 9         | 1.19%   |
| Intel Ethernet Connection (7) I219-LM                             | 8         | 1.05%   |
| Intel 82577LM Gigabit Network Connection                          | 8         | 1.05%   |
| Nvidia MCP79 Ethernet                                             | 6         | 0.79%   |
| Intel I210 Gigabit Network Connection                             | 6         | 0.79%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 5         | 0.66%   |
| Lenovo USB-C Dock Ethernet                                        | 5         | 0.66%   |
| Intel Ethernet Connection (6) I219-V                              | 5         | 0.66%   |
| Intel Ethernet Connection (10) I219-V                             | 5         | 0.66%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 5         | 0.66%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 5         | 0.66%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 4         | 0.53%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4         | 0.53%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 4         | 0.53%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 0.53%   |
| Intel Ethernet Connection I217-V                                  | 4         | 0.53%   |
| Intel Ethernet Connection (6) I219-LM                             | 4         | 0.53%   |
| Intel Ethernet Connection (5) I219-LM                             | 4         | 0.53%   |
| Intel Ethernet Connection (2) I219-LM                             | 4         | 0.53%   |
| Intel Ethernet Connection (2) I218-V                              | 4         | 0.53%   |
| Intel Ethernet Connection (13) I219-V                             | 4         | 0.53%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4         | 0.53%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 4         | 0.53%   |
| ASIX AX88179 Gigabit Ethernet                                     | 4         | 0.53%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3         | 0.4%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 3         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 691       | 51.84%  |
| WiFi     | 625       | 46.89%  |
| Modem    | 15        | 1.13%   |
| Unknown  | 2         | 0.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 481       | 57.74%  |
| Ethernet | 352       | 42.26%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 474       | 60.15%  |
| 1     | 274       | 34.77%  |
| 3     | 21        | 2.66%   |
| 0     | 17        | 2.16%   |
| 4     | 2         | 0.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 757       | 95.94%  |
| Yes  | 32        | 4.06%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 279       | 52.64%  |
| Broadcom                        | 44        | 8.3%    |
| Realtek Semiconductor           | 33        | 6.23%   |
| Cambridge Silicon Radio         | 28        | 5.28%   |
| Qualcomm Atheros Communications | 26        | 4.91%   |
| IMC Networks                    | 22        | 4.15%   |
| Apple                           | 21        | 3.96%   |
| Lite-On Technology              | 18        | 3.4%    |
| Foxconn / Hon Hai               | 16        | 3.02%   |
| Hewlett-Packard                 | 9         | 1.7%    |
| ASUSTek Computer                | 9         | 1.7%    |
| MediaTek                        | 4         | 0.75%   |
| Dell                            | 3         | 0.57%   |
| Realtek                         | 2         | 0.38%   |
| Ralink Technology               | 2         | 0.38%   |
| Ralink                          | 2         | 0.38%   |
| Marvell Semiconductor           | 2         | 0.38%   |
| Belkin Components               | 2         | 0.38%   |
| USI                             | 1         | 0.19%   |
| Toshiba                         | 1         | 0.19%   |
| Taiyo Yuden                     | 1         | 0.19%   |
| HTC (High Tech Computer)        | 1         | 0.19%   |
| Foxconn International           | 1         | 0.19%   |
| Edimax Technology               | 1         | 0.19%   |
| D-Link System                   | 1         | 0.19%   |
| Chicony Electronics             | 1         | 0.19%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 124       | 23.4%   |
| Intel AX200 Bluetooth                               | 42        | 7.92%   |
| Intel Bluetooth Device                              | 33        | 6.23%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 31        | 5.85%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 28        | 5.28%   |
| Realtek Bluetooth Radio                             | 17        | 3.21%   |
| Broadcom BCM2045B (BDC-2.1)                         | 16        | 3.02%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 13        | 2.45%   |
| Intel Wireless-AC 3168 Bluetooth                    | 13        | 2.45%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 11        | 2.08%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 10        | 1.89%   |
| Lite-On Bluetooth Device                            | 10        | 1.89%   |
| Apple Bluetooth Host Controller                     | 10        | 1.89%   |
| Intel AX210 Bluetooth                               | 9         | 1.7%    |
| IMC Networks Bluetooth Radio                        | 9         | 1.7%    |
| Qualcomm Atheros  Bluetooth Device                  | 8         | 1.51%   |
| IMC Networks Wireless_Device                        | 8         | 1.51%   |
| Foxconn / Hon Hai Bluetooth Device                  | 8         | 1.51%   |
| Realtek  Bluetooth 4.2 Adapter                      | 7         | 1.32%   |
| Lite-On Atheros AR3012 Bluetooth                    | 6         | 1.13%   |
| HP Broadcom 2070 Bluetooth Combo                    | 6         | 1.13%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 6         | 1.13%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 6         | 1.13%   |
| MediaTek Wireless_Device                            | 4         | 0.75%   |
| Broadcom HP Portable Bumble Bee                     | 4         | 0.75%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 4         | 0.75%   |
| Apple Bluetooth USB Host Controller                 | 4         | 0.75%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 3         | 0.57%   |
| Realtek RTL8723B Bluetooth                          | 3         | 0.57%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 0.57%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 0.57%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 3         | 0.57%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 3         | 0.57%   |
| Dell DW375 Bluetooth Module                         | 3         | 0.57%   |
| ASUS ASUS USB-BT500                                 | 3         | 0.57%   |
| Realtek RTL8821A Bluetooth                          | 2         | 0.38%   |
| Realtek Bluetooth Radio                             | 2         | 0.38%   |
| Ralink RT3290 Bluetooth                             | 2         | 0.38%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 0.38%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 0.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 550       | 47.78%  |
| Nvidia                           | 233       | 20.24%  |
| AMD                              | 222       | 19.29%  |
| SteelSeries ApS                  | 14        | 1.22%   |
| Lenovo                           | 13        | 1.13%   |
| GN Netcom                        | 13        | 1.13%   |
| Kingston Technology              | 12        | 1.04%   |
| C-Media Electronics              | 12        | 1.04%   |
| Creative Technology              | 8         | 0.7%    |
| Logitech                         | 7         | 0.61%   |
| ASUSTek Computer                 | 7         | 0.61%   |
| Creative Labs                    | 6         | 0.52%   |
| Realtek Semiconductor            | 4         | 0.35%   |
| Razer USA                        | 4         | 0.35%   |
| Hewlett-Packard                  | 4         | 0.35%   |
| VIA Technologies                 | 3         | 0.26%   |
| Texas Instruments                | 3         | 0.26%   |
| Plantronics                      | 3         | 0.26%   |
| Focusrite-Novation               | 3         | 0.26%   |
| Corsair                          | 3         | 0.26%   |
| Yamaha                           | 2         | 0.17%   |
| Sennheiser Communications        | 2         | 0.17%   |
| RODE Microphones                 | 2         | 0.17%   |
| XMOS                             | 1         | 0.09%   |
| Unknown                          | 1         | 0.09%   |
| Turtle Beach                     | 1         | 0.09%   |
| Tenx Technology                  | 1         | 0.09%   |
| Syntek                           | 1         | 0.09%   |
| Sony                             | 1         | 0.09%   |
| Silicon Integrated Systems [SiS] | 1         | 0.09%   |
| Shure                            | 1         | 0.09%   |
| Samson Technologies              | 1         | 0.09%   |
| ROCCAT                           | 1         | 0.09%   |
| NAD Electronics                  | 1         | 0.09%   |
| JMTek                            | 1         | 0.09%   |
| Jieli Technology                 | 1         | 0.09%   |
| GYROCOM C&C                      | 1         | 0.09%   |
| Clavia DMI AB                    | 1         | 0.09%   |
| Blue Microphones                 | 1         | 0.09%   |
| BEHRINGER International          | 1         | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 91        | 6.7%    |
| AMD Family 17h/19h HD Audio Controller                                     | 70        | 5.15%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 52        | 3.83%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 46        | 3.39%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 43        | 3.17%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 41        | 3.02%   |
| Intel Cannon Lake PCH cAVS                                                 | 37        | 2.72%   |
| AMD Starship/Matisse HD Audio Controller                                   | 37        | 2.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 30        | 2.21%   |
| Intel 8 Series HD Audio Controller                                         | 29        | 2.14%   |
| Intel Haswell-ULT HD Audio Controller                                      | 28        | 2.06%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 26        | 1.91%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 25        | 1.84%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 24        | 1.77%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 22        | 1.62%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 21        | 1.55%   |
| AMD FCH Azalia Controller                                                  | 20        | 1.47%   |
| Nvidia GP107GL High Definition Audio Controller                            | 19        | 1.4%    |
| Intel 200 Series PCH HD Audio                                              | 19        | 1.4%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 18        | 1.33%   |
| Nvidia TU106 High Definition Audio Controller                              | 17        | 1.25%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 16        | 1.18%   |
| Nvidia TU116 High Definition Audio Controller                              | 15        | 1.1%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 14        | 1.03%   |
| Nvidia TU104 HD Audio Controller                                           | 13        | 0.96%   |
| Nvidia GP104 High Definition Audio Controller                              | 13        | 0.96%   |
| AMD Kabini HDMI/DP Audio                                                   | 13        | 0.96%   |
| Nvidia GF108 High Definition Audio Controller                              | 12        | 0.88%   |
| Intel Comet Lake PCH-LP cAVS                                               | 12        | 0.88%   |
| Intel CM238 HD Audio Controller                                            | 12        | 0.88%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 12        | 0.88%   |
| AMD Navi 10 HDMI Audio                                                     | 12        | 0.88%   |
| Nvidia GK107 HDMI Audio Controller                                         | 11        | 0.81%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 11        | 0.81%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 11        | 0.81%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 11        | 0.81%   |
| Nvidia GP106 High Definition Audio Controller                              | 10        | 0.74%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 10        | 0.74%   |
| Kingston Technology HyperX 7.1 Audio                                       | 10        | 0.74%   |
| Intel Comet Lake PCH cAVS                                                  | 10        | 0.74%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 102       | 23.56%  |
| SK hynix            | 79        | 18.24%  |
| Kingston            | 54        | 12.47%  |
| Micron Technology   | 46        | 10.62%  |
| Corsair             | 41        | 9.47%   |
| Unknown             | 33        | 7.62%   |
| G.Skill             | 24        | 5.54%   |
| Crucial             | 20        | 4.62%   |
| Elpida              | 8         | 1.85%   |
| Ramaxel Technology  | 6         | 1.39%   |
| Nanya Technology    | 5         | 1.15%   |
| A-DATA Technology   | 3         | 0.69%   |
| Unknown             | 3         | 0.69%   |
| Unknown (ABCD)      | 1         | 0.23%   |
| Unifosa             | 1         | 0.23%   |
| Transcend           | 1         | 0.23%   |
| SHARETRONIC         | 1         | 0.23%   |
| ff                  | 1         | 0.23%   |
| fef5                | 1         | 0.23%   |
| Avant               | 1         | 0.23%   |
| Apacer              | 1         | 0.23%   |
| 4ea5                | 1         | 0.23%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 9         | 1.96%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 7         | 1.53%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 7         | 1.53%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 1.31%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 1.31%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 1.09%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 0.87%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 0.87%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 4         | 0.87%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 4         | 0.87%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s            | 4         | 0.87%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 3         | 0.65%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 3         | 0.65%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 3         | 0.65%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 3         | 0.65%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 3         | 0.65%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 0.65%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 3         | 0.65%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 3         | 0.65%   |
| Unknown                                                          | 3         | 0.65%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                          | 2         | 0.44%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 2         | 0.44%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 2         | 0.44%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 2         | 0.44%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2667MT/s                    | 2         | 0.44%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.44%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.44%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.44%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 2         | 0.44%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 0.44%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 0.44%   |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 0.44%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.44%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 2         | 0.44%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.44%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.44%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 0.44%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 0.44%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 2         | 0.44%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 2         | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 193       | 50.79%  |
| DDR3    | 115       | 30.26%  |
| LPDDR3  | 20        | 5.26%   |
| Unknown | 12        | 3.16%   |
| LPDDR4  | 11        | 2.89%   |
| DDR2    | 10        | 2.63%   |
| SDRAM   | 7         | 1.84%   |
| DDR5    | 6         | 1.58%   |
| DDR     | 3         | 0.79%   |
| LPDDR5  | 2         | 0.53%   |
| DRAM    | 1         | 0.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 215       | 56.58%  |
| DIMM         | 128       | 33.68%  |
| Row Of Chips | 27        | 7.11%   |
| Chip         | 5         | 1.32%   |
| Unknown      | 4         | 1.05%   |
| FB-DIMM      | 1         | 0.26%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 175       | 43.64%  |
| 4096  | 90        | 22.44%  |
| 16384 | 74        | 18.45%  |
| 2048  | 42        | 10.47%  |
| 32768 | 12        | 2.99%   |
| 1024  | 5         | 1.25%   |
| 512   | 3         | 0.75%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 84        | 20.64%  |
| 2667    | 66        | 16.22%  |
| 3200    | 53        | 13.02%  |
| 2133    | 29        | 7.13%   |
| 2400    | 26        | 6.39%   |
| 1333    | 24        | 5.9%    |
| 3600    | 16        | 3.93%   |
| 1867    | 13        | 3.19%   |
| 1334    | 12        | 2.95%   |
| 667     | 11        | 2.7%    |
| 3400    | 7         | 1.72%   |
| 3466    | 6         | 1.47%   |
| Unknown | 6         | 1.47%   |
| 2933    | 5         | 1.23%   |
| 1067    | 5         | 1.23%   |
| 4267    | 4         | 0.98%   |
| 6400    | 3         | 0.74%   |
| 4266    | 3         | 0.74%   |
| 3000    | 3         | 0.74%   |
| 5200    | 2         | 0.49%   |
| 4800    | 2         | 0.49%   |
| 3666    | 2         | 0.49%   |
| 3500    | 2         | 0.49%   |
| 3266    | 2         | 0.49%   |
| 2048    | 2         | 0.49%   |
| 800     | 2         | 0.49%   |
| 20306   | 1         | 0.25%   |
| 8400    | 1         | 0.25%   |
| 4400    | 1         | 0.25%   |
| 4199    | 1         | 0.25%   |
| 4000    | 1         | 0.25%   |
| 3866    | 1         | 0.25%   |
| 3800    | 1         | 0.25%   |
| 3733    | 1         | 0.25%   |
| 3533    | 1         | 0.25%   |
| 3333    | 1         | 0.25%   |
| 3100    | 1         | 0.25%   |
| 2733    | 1         | 0.25%   |
| 1866    | 1         | 0.25%   |
| 1800    | 1         | 0.25%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 9         | 47.37%  |
| Brother Industries  | 5         | 26.32%  |
| Canon               | 3         | 15.79%  |
| Samsung Electronics | 1         | 5.26%   |
| Prolific Technology | 1         | 5.26%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Samsung M2020 Series          | 1         | 5.26%   |
| Prolific PL2305 Parallel Port | 1         | 5.26%   |
| HP LaserJet 1020              | 1         | 5.26%   |
| HP ENVY Photo 6200 series     | 1         | 5.26%   |
| HP ENVY 4520 series           | 1         | 5.26%   |
| HP Deskjet D4300 series       | 1         | 5.26%   |
| HP DeskJet 990c               | 1         | 5.26%   |
| HP DeskJet 5940               | 1         | 5.26%   |
| HP DeskJet 5550               | 1         | 5.26%   |
| HP DeskJet 3700 series        | 1         | 5.26%   |
| HP DeskJet 2600 series        | 1         | 5.26%   |
| Canon PIXMA MX370 Series      | 1         | 5.26%   |
| Canon PIXMA MP280             | 1         | 5.26%   |
| Canon iP7200 series           | 1         | 5.26%   |
| Brother HL-5250DN Printer     | 1         | 5.26%   |
| Brother HL-2240D series       | 1         | 5.26%   |
| Brother HL-2030 Laser Printer | 1         | 5.26%   |
| Brother HL-1210W series       | 1         | 5.26%   |
| Brother DCP-J140W             | 1         | 5.26%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 2         | 66.67%  |
| Canon           | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| HP ScanJet 5470c/5490c | 1         | 33.33%  |
| HP PSC 1200            | 1         | 33.33%  |
| Canon CanoScan LiDE 60 | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 133       | 27.88%  |
| Acer                                   | 53        | 11.11%  |
| IMC Networks                           | 44        | 9.22%   |
| Realtek Semiconductor                  | 35        | 7.34%   |
| Logitech                               | 35        | 7.34%   |
| Apple                                  | 20        | 4.19%   |
| Microdia                               | 19        | 3.98%   |
| Quanta                                 | 18        | 3.77%   |
| Sunplus Innovation Technology          | 17        | 3.56%   |
| Suyin                                  | 16        | 3.35%   |
| Lite-On Technology                     | 16        | 3.35%   |
| Cheng Uei Precision Industry (Foxlink) | 15        | 3.14%   |
| Syntek                                 | 12        | 2.52%   |
| Samsung Electronics                    | 5         | 1.05%   |
| Luxvisions Innotech Limited            | 5         | 1.05%   |
| Lenovo                                 | 5         | 1.05%   |
| Silicon Motion                         | 4         | 0.84%   |
| Microsoft                              | 4         | 0.84%   |
| Trust                                  | 3         | 0.63%   |
| Primax Electronics                     | 2         | 0.42%   |
| Alcor Micro                            | 2         | 0.42%   |
| Z-Star Microelectronics                | 1         | 0.21%   |
| Tripath Technology                     | 1         | 0.21%   |
| Sonix Technology                       | 1         | 0.21%   |
| Ricoh                                  | 1         | 0.21%   |
| Oculus VR                              | 1         | 0.21%   |
| MacroSilicon                           | 1         | 0.21%   |
| Jieli Technology                       | 1         | 0.21%   |
| Intel                                  | 1         | 0.21%   |
| Hewlett-Packard                        | 1         | 0.21%   |
| Genesys Logic                          | 1         | 0.21%   |
| GEMBIRD                                | 1         | 0.21%   |
| Cubeternet                             | 1         | 0.21%   |
| Creative Technology                    | 1         | 0.21%   |
| ALi                                    | 1         | 0.21%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 38        | 7.9%    |
| IMC Networks Integrated Camera           | 18        | 3.74%   |
| Realtek Integrated_Webcam_HD             | 15        | 3.12%   |
| Chicony HD Webcam                        | 14        | 2.91%   |
| IMC Networks USB2.0 HD UVC WebCam        | 12        | 2.49%   |
| Acer Integrated Camera                   | 11        | 2.29%   |
| Apple Built-in iSight                    | 10        | 2.08%   |
| Microdia Integrated_Webcam_HD            | 9         | 1.87%   |
| Lite-On Integrated Camera                | 9         | 1.87%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 8         | 1.66%   |
| Acer Lenovo EasyCamera                   | 8         | 1.66%   |
| Chicony HP HD Camera                     | 6         | 1.25%   |
| Apple FaceTime HD Camera (Built-in)      | 6         | 1.25%   |
| Syntek Lenovo EasyCamera                 | 5         | 1.04%   |
| Syntek Integrated Camera                 | 5         | 1.04%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 5         | 1.04%   |
| Samsung Galaxy A5 (MTP)                  | 5         | 1.04%   |
| Logitech StreamCam                       | 5         | 1.04%   |
| Logitech HD Pro Webcam C920              | 5         | 1.04%   |
| Chicony USB 2.0 Camera                   | 5         | 1.04%   |
| Chicony Integrated Camera (1280x720@30)  | 5         | 1.04%   |
| Chicony EasyCamera                       | 5         | 1.04%   |
| Acer SunplusIT Integrated Camera         | 5         | 1.04%   |
| Acer EasyCamera                          | 5         | 1.04%   |
| Quanta USB2.0 HD UVC WebCam              | 4         | 0.83%   |
| Microdia Integrated Webcam               | 4         | 0.83%   |
| Luxvisions Innotech Limited HP HD Camera | 4         | 0.83%   |
| Logitech Webcam C270                     | 4         | 0.83%   |
| Chicony Integrated Camera [ThinkPad]     | 4         | 0.83%   |
| Chicony HP Truevision HD                 | 4         | 0.83%   |
| Acer ThinkPad Integrated Camera          | 4         | 0.83%   |
| Acer HD Webcam                           | 4         | 0.83%   |
| Trust USB Camera                         | 3         | 0.62%   |
| Suyin HP Truevision HD                   | 3         | 0.62%   |
| Sunplus Laptop Integrated WebCam HD      | 3         | 0.62%   |
| Sunplus Integrated_Webcam_HD             | 3         | 0.62%   |
| Realtek HP Wide Vision HD Camera         | 3         | 0.62%   |
| Quanta HP Webcam                         | 3         | 0.62%   |
| Quanta HD Webcam                         | 3         | 0.62%   |
| Logitech HD Webcam C525                  | 3         | 0.62%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 48        | 35.29%  |
| Synaptics                  | 48        | 35.29%  |
| Upek                       | 13        | 9.56%   |
| Shenzhen Goodix Technology | 11        | 8.09%   |
| AuthenTec                  | 9         | 6.62%   |
| Elan Microelectronics      | 4         | 2.94%   |
| STMicroelectronics         | 2         | 1.47%   |
| LighTuning Technology      | 1         | 0.74%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 24        | 17.65%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 13        | 9.56%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 13        | 9.56%   |
| Validity Sensors Synaptics WBDI                                            | 9         | 6.62%   |
| Unknown                                                                    | 9         | 6.62%   |
| Shenzhen Goodix  FingerPrint Device                                        | 6         | 4.41%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 3.68%   |
| Synaptics  WBDI                                                            | 5         | 3.68%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 2.94%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 2.94%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 2.94%   |
| AuthenTec AES2810                                                          | 4         | 2.94%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 4         | 2.94%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 2.21%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 2.21%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 1.47%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 1.47%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.47%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 1.47%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 1.47%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 1.47%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 1.47%   |
| Elan ELAN:Fingerprint                                                      | 2         | 1.47%   |
| Elan ELAN:ARM-M4                                                           | 2         | 1.47%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.74%   |
| Validity Sensors VFS491                                                    | 1         | 0.74%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.74%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.74%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 0.74%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.74%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 0.74%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.74%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 39        | 61.9%   |
| Broadcom              | 15        | 23.81%  |
| Upek                  | 6         | 9.52%   |
| Lenovo                | 2         | 3.17%   |
| Advanced Card Systems | 1         | 1.59%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 39        | 61.9%   |
| Broadcom 5880                                                                | 7         | 11.11%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 6         | 9.52%   |
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 7.94%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 3.17%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 3.17%   |
| Broadcom 58200                                                               | 1         | 1.59%   |
| Advanced Card Systems ACR1252 Dual Reader                                    | 1         | 1.59%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 517       | 64.3%   |
| 1     | 214       | 26.62%  |
| 2     | 56        | 6.97%   |
| 3     | 10        | 1.24%   |
| 4     | 4         | 0.5%    |
| 6     | 2         | 0.25%   |
| 10    | 1         | 0.12%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 135       | 36.49%  |
| Graphics card            | 59        | 15.95%  |
| Chipcard                 | 59        | 15.95%  |
| Net/wireless             | 32        | 8.65%   |
| Multimedia controller    | 26        | 7.03%   |
| Communication controller | 12        | 3.24%   |
| Card reader              | 10        | 2.7%    |
| Camera                   | 8         | 2.16%   |
| Sound                    | 7         | 1.89%   |
| Net/ethernet             | 5         | 1.35%   |
| Bluetooth                | 5         | 1.35%   |
| Unassigned class         | 4         | 1.08%   |
| Storage                  | 4         | 1.08%   |
| Storage/raid             | 2         | 0.54%   |
| Network                  | 1         | 0.27%   |
| Modem                    | 1         | 0.27%   |

