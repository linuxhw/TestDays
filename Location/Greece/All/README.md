Linux in Greece - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Greece.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Greece/Desktop/README.md) and [notebooks](/Location/Greece/Notebook/README.md).

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

Total: 1615

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | ENVY x360 Convertible 15... | Convertible | [c0663aa7da](https://linux-hardware.org/?probe=c0663aa7da) | Dec 01, 2022 |
| HP            | OMEN by Laptop 16-b1xxx     | Notebook    | [0cd3005f69](https://linux-hardware.org/?probe=0cd3005f69) | Dec 01, 2022 |
| HP            | OMEN by Laptop 16-b1xxx     | Notebook    | [32b68762df](https://linux-hardware.org/?probe=32b68762df) | Nov 30, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [1a742c23df](https://linux-hardware.org/?probe=1a742c23df) | Nov 29, 2022 |
| HP            | Pavilion g6                 | Notebook    | [fefac15f4c](https://linux-hardware.org/?probe=fefac15f4c) | Nov 29, 2022 |
| Dell          | Inspiron 5406 2n1           | Convertible | [92afc95831](https://linux-hardware.org/?probe=92afc95831) | Nov 29, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [d20243efed](https://linux-hardware.org/?probe=d20243efed) | Nov 28, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [dee60b9f35](https://linux-hardware.org/?probe=dee60b9f35) | Nov 28, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [1651962e5a](https://linux-hardware.org/?probe=1651962e5a) | Nov 28, 2022 |
| Clevo         | W55xEU                      | Notebook    | [5ed799ba64](https://linux-hardware.org/?probe=5ed799ba64) | Nov 28, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [fa5d6f5ca6](https://linux-hardware.org/?probe=fa5d6f5ca6) | Nov 28, 2022 |
| ASRock        | A88M-G                      | Desktop     | [323199813d](https://linux-hardware.org/?probe=323199813d) | Nov 27, 2022 |
| Acer          | Aspire A315-58              | Notebook    | [df3e0f4b6c](https://linux-hardware.org/?probe=df3e0f4b6c) | Nov 26, 2022 |
| Acer          | Aspire A315-58              | Notebook    | [82ee1f1740](https://linux-hardware.org/?probe=82ee1f1740) | Nov 26, 2022 |
| Lenovo        | ThinkCentre M58 6258AP4     | Desktop     | [54d4e3a0ae](https://linux-hardware.org/?probe=54d4e3a0ae) | Nov 26, 2022 |
| MSI           | GE62 2QC                    | Notebook    | [6bdf66b3b6](https://linux-hardware.org/?probe=6bdf66b3b6) | Nov 26, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [9e22e08aa1](https://linux-hardware.org/?probe=9e22e08aa1) | Nov 25, 2022 |
| Dell          | Inspiron 3585               | Notebook    | [33485dee6d](https://linux-hardware.org/?probe=33485dee6d) | Nov 24, 2022 |
| Lenovo        | ThinkPad T580 20LAS01H00    | Notebook    | [3714ee0985](https://linux-hardware.org/?probe=3714ee0985) | Nov 24, 2022 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [f442c854fc](https://linux-hardware.org/?probe=f442c854fc) | Nov 23, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [a7f0189359](https://linux-hardware.org/?probe=a7f0189359) | Nov 23, 2022 |
| Dell          | Latitude D530               | Notebook    | [1403a8c938](https://linux-hardware.org/?probe=1403a8c938) | Nov 23, 2022 |
| HP            | Pavilion dv5                | Notebook    | [2a497ff54f](https://linux-hardware.org/?probe=2a497ff54f) | Nov 22, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [452417fa68](https://linux-hardware.org/?probe=452417fa68) | Nov 21, 2022 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | Desktop     | [34e6521bc8](https://linux-hardware.org/?probe=34e6521bc8) | Nov 21, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [a1b9357fc6](https://linux-hardware.org/?probe=a1b9357fc6) | Nov 20, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [f7ebd3f633](https://linux-hardware.org/?probe=f7ebd3f633) | Nov 20, 2022 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [55bd7957b4](https://linux-hardware.org/?probe=55bd7957b4) | Nov 20, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [13f1a98b2c](https://linux-hardware.org/?probe=13f1a98b2c) | Nov 19, 2022 |
| Purism        | Librem 14                   | Notebook    | [cbc8bf9c96](https://linux-hardware.org/?probe=cbc8bf9c96) | Nov 19, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [4e04b1a51f](https://linux-hardware.org/?probe=4e04b1a51f) | Nov 19, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [c7fe31050b](https://linux-hardware.org/?probe=c7fe31050b) | Nov 19, 2022 |
| MSI           | H81M-P33                    | Desktop     | [a535339292](https://linux-hardware.org/?probe=a535339292) | Nov 17, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [814b5d3d2e](https://linux-hardware.org/?probe=814b5d3d2e) | Nov 17, 2022 |
| MSI           | H81M-P33                    | Desktop     | [246d594268](https://linux-hardware.org/?probe=246d594268) | Nov 16, 2022 |
| Acer          | Veriton N4630G              | Desktop     | [f4566a57a9](https://linux-hardware.org/?probe=f4566a57a9) | Nov 16, 2022 |
| HP            | 1495                        | Desktop     | [e29c423a17](https://linux-hardware.org/?probe=e29c423a17) | Nov 15, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [49ac6f08f9](https://linux-hardware.org/?probe=49ac6f08f9) | Nov 15, 2022 |
| ASUSTek       | ProArt B550-CREATOR         | Desktop     | [459c5879e6](https://linux-hardware.org/?probe=459c5879e6) | Nov 15, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [0007401910](https://linux-hardware.org/?probe=0007401910) | Nov 15, 2022 |
| Gigabyte      | Z690 AERO G                 | Desktop     | [311a20e88f](https://linux-hardware.org/?probe=311a20e88f) | Nov 13, 2022 |
| Acer          | Aspire A315-58              | Notebook    | [961b736faa](https://linux-hardware.org/?probe=961b736faa) | Nov 13, 2022 |
| Fujitsu Si... | MS-7304VP-A13               | Desktop     | [69b1471202](https://linux-hardware.org/?probe=69b1471202) | Nov 12, 2022 |
| Sony          | VGN-CR31S_P                 | Notebook    | [ce99a279ca](https://linux-hardware.org/?probe=ce99a279ca) | Nov 11, 2022 |
| Lenovo        | ThinkPad T580 20LAS01H00    | Notebook    | [4d41c7236e](https://linux-hardware.org/?probe=4d41c7236e) | Nov 10, 2022 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | Notebook    | [1cee1a7bd4](https://linux-hardware.org/?probe=1cee1a7bd4) | Nov 09, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [f49624457d](https://linux-hardware.org/?probe=f49624457d) | Nov 09, 2022 |
| MSI           | GE62 2QC                    | Notebook    | [513a929878](https://linux-hardware.org/?probe=513a929878) | Nov 08, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [7eca97a8ef](https://linux-hardware.org/?probe=7eca97a8ef) | Nov 08, 2022 |
| Dell          | Inspiron 5406 2n1           | Convertible | [a734aa34bf](https://linux-hardware.org/?probe=a734aa34bf) | Nov 07, 2022 |
| MSI           | GF65 Thin 10UE              | Notebook    | [ec09d9e22e](https://linux-hardware.org/?probe=ec09d9e22e) | Nov 06, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [605c859789](https://linux-hardware.org/?probe=605c859789) | Nov 06, 2022 |
| Insyde        | CherryTrail                 | Notebook    | [72fdd6a414](https://linux-hardware.org/?probe=72fdd6a414) | Nov 06, 2022 |
| Insyde        | CherryTrail                 | Notebook    | [1a65afa04d](https://linux-hardware.org/?probe=1a65afa04d) | Nov 06, 2022 |
| ASUSTek       | PRIME B365-PLUS             | Desktop     | [6dd41b1571](https://linux-hardware.org/?probe=6dd41b1571) | Nov 06, 2022 |
| MSI           | Z270 GAMING PRO CARBON      | Desktop     | [07e637210f](https://linux-hardware.org/?probe=07e637210f) | Nov 06, 2022 |
| Lenovo        | ThinkPad Edge 0301GBG       | Notebook    | [8b50396928](https://linux-hardware.org/?probe=8b50396928) | Nov 04, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [fecd8f06dd](https://linux-hardware.org/?probe=fecd8f06dd) | Nov 02, 2022 |
| HP            | 18E7                        | Desktop     | [c0d5c58895](https://linux-hardware.org/?probe=c0d5c58895) | Nov 02, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [aad6abb936](https://linux-hardware.org/?probe=aad6abb936) | Nov 01, 2022 |
| Lenovo        | ThinkCentre M55E 898578G    | Desktop     | [d025c115d8](https://linux-hardware.org/?probe=d025c115d8) | Nov 01, 2022 |
| HP            | Pavilion Sleekbook 15 PC    | Notebook    | [9dea1bfedb](https://linux-hardware.org/?probe=9dea1bfedb) | Nov 01, 2022 |
| ASUSTek       | H110M-D                     | Desktop     | [248b9533a3](https://linux-hardware.org/?probe=248b9533a3) | Nov 01, 2022 |
| MSI           | MS-7309                     | Desktop     | [a6b1a7d329](https://linux-hardware.org/?probe=a6b1a7d329) | Oct 31, 2022 |
| MSI           | MS-7309                     | Desktop     | [3c519589ad](https://linux-hardware.org/?probe=3c519589ad) | Oct 30, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [ed46beadef](https://linux-hardware.org/?probe=ed46beadef) | Oct 30, 2022 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [05b5af2e63](https://linux-hardware.org/?probe=05b5af2e63) | Oct 29, 2022 |
| ASRock        | FM2A88X-ITX+                | Desktop     | [00b65eaa83](https://linux-hardware.org/?probe=00b65eaa83) | Oct 29, 2022 |
| Gigabyte      | GA-MA790FX-DQ6              | Desktop     | [8ba31a020c](https://linux-hardware.org/?probe=8ba31a020c) | Oct 28, 2022 |
| Acer          | Aspire A315-58              | Notebook    | [7870d9b047](https://linux-hardware.org/?probe=7870d9b047) | Oct 28, 2022 |
| Dell          | 0KRC95 A02                  | Desktop     | [8afc3da46d](https://linux-hardware.org/?probe=8afc3da46d) | Oct 28, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [0e69671817](https://linux-hardware.org/?probe=0e69671817) | Oct 27, 2022 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [a3f55b1301](https://linux-hardware.org/?probe=a3f55b1301) | Oct 27, 2022 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [285a7d17e3](https://linux-hardware.org/?probe=285a7d17e3) | Oct 27, 2022 |
| HP            | Pavilion Sleekbook 15 PC    | Notebook    | [26e7b206ef](https://linux-hardware.org/?probe=26e7b206ef) | Oct 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [c9393d50b5](https://linux-hardware.org/?probe=c9393d50b5) | Oct 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [5199be5418](https://linux-hardware.org/?probe=5199be5418) | Oct 24, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [aaad9f52d4](https://linux-hardware.org/?probe=aaad9f52d4) | Oct 24, 2022 |
| Toshiba       | dynabook Satellite T87/8... | Notebook    | [10f344a2b3](https://linux-hardware.org/?probe=10f344a2b3) | Oct 24, 2022 |
| Samsung       | 300E4A/300E5A/300E7A        | Notebook    | [ade038c388](https://linux-hardware.org/?probe=ade038c388) | Oct 24, 2022 |
| Toshiba       | Satellite C50-B             | Notebook    | [a9041efc75](https://linux-hardware.org/?probe=a9041efc75) | Oct 23, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [19c3c8e1f6](https://linux-hardware.org/?probe=19c3c8e1f6) | Oct 23, 2022 |
| Acer          | Aspire A315-58              | Notebook    | [e5b07599e3](https://linux-hardware.org/?probe=e5b07599e3) | Oct 22, 2022 |
| HP            | EliteBook 820 G1            | Notebook    | [7abef2546e](https://linux-hardware.org/?probe=7abef2546e) | Oct 21, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [f3890a4db1](https://linux-hardware.org/?probe=f3890a4db1) | Oct 21, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [de5adb6775](https://linux-hardware.org/?probe=de5adb6775) | Oct 21, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [d135b32e8b](https://linux-hardware.org/?probe=d135b32e8b) | Oct 21, 2022 |
| HP            | Pavilion g7                 | Notebook    | [19048aa8f0](https://linux-hardware.org/?probe=19048aa8f0) | Oct 19, 2022 |
| HP            | 339A                        | Desktop     | [bea86a9671](https://linux-hardware.org/?probe=bea86a9671) | Oct 19, 2022 |
| Gigabyte      | P55-USB3                    | Desktop     | [6f441865a9](https://linux-hardware.org/?probe=6f441865a9) | Oct 19, 2022 |
| Acer          | Aspire V3-771               | Notebook    | [91e4682f34](https://linux-hardware.org/?probe=91e4682f34) | Oct 17, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [23c855f88b](https://linux-hardware.org/?probe=23c855f88b) | Oct 17, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [ebe65ec5fa](https://linux-hardware.org/?probe=ebe65ec5fa) | Oct 17, 2022 |
| Lenovo        | B590 20208                  | Notebook    | [6a3309f753](https://linux-hardware.org/?probe=6a3309f753) | Oct 14, 2022 |
| Dell          | Inspiron 5406 2n1           | Convertible | [7c58857f43](https://linux-hardware.org/?probe=7c58857f43) | Oct 11, 2022 |
| HP            | Pavilion g6                 | Notebook    | [943ee204e0](https://linux-hardware.org/?probe=943ee204e0) | Oct 10, 2022 |
| Samsung       | 300E4A/300E5A/300E7A        | Notebook    | [a281cc47e5](https://linux-hardware.org/?probe=a281cc47e5) | Oct 10, 2022 |
| MSI           | B550M PRO-VDH               | Desktop     | [c4e09cdf87](https://linux-hardware.org/?probe=c4e09cdf87) | Oct 09, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [d1c01a07a2](https://linux-hardware.org/?probe=d1c01a07a2) | Oct 08, 2022 |
| Gigabyte      | P55M-UD2                    | Desktop     | [e9627c4c34](https://linux-hardware.org/?probe=e9627c4c34) | Oct 07, 2022 |
| Dell          | Precision M6800             | Notebook    | [802d1dbfcd](https://linux-hardware.org/?probe=802d1dbfcd) | Oct 06, 2022 |
| Dell          | Inspiron 5406 2n1           | Convertible | [84ba2e1db1](https://linux-hardware.org/?probe=84ba2e1db1) | Oct 05, 2022 |
| Apple         | MacBookPro5,2               | Notebook    | [b0a6dc4162](https://linux-hardware.org/?probe=b0a6dc4162) | Oct 02, 2022 |
| Gigabyte      | P55-USB3                    | Desktop     | [adf7389f06](https://linux-hardware.org/?probe=adf7389f06) | Sep 30, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [4e0be93d26](https://linux-hardware.org/?probe=4e0be93d26) | Sep 29, 2022 |
| NU591         | 1.0                         | Desktop     | [6be5a78c90](https://linux-hardware.org/?probe=6be5a78c90) | Sep 27, 2022 |
| Purism        | Librem 14                   | Notebook    | [213731b934](https://linux-hardware.org/?probe=213731b934) | Sep 24, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [59c4a7e761](https://linux-hardware.org/?probe=59c4a7e761) | Sep 23, 2022 |
| HP            | Notebook                    | Notebook    | [18b9221add](https://linux-hardware.org/?probe=18b9221add) | Sep 22, 2022 |
| MSI           | H310M PRO-VH                | Desktop     | [c11e067cb5](https://linux-hardware.org/?probe=c11e067cb5) | Sep 22, 2022 |
| ASRock        | H81M-GL                     | Desktop     | [fe7e5bbc9c](https://linux-hardware.org/?probe=fe7e5bbc9c) | Sep 21, 2022 |
| NU591         | 1.0                         | Desktop     | [6e29ae977f](https://linux-hardware.org/?probe=6e29ae977f) | Sep 21, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [a1f237c86a](https://linux-hardware.org/?probe=a1f237c86a) | Sep 20, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [5c9688dac8](https://linux-hardware.org/?probe=5c9688dac8) | Sep 19, 2022 |
| Gigabyte      | H97M-D3H                    | Desktop     | [57db36ecc9](https://linux-hardware.org/?probe=57db36ecc9) | Sep 19, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [fe48912653](https://linux-hardware.org/?probe=fe48912653) | Sep 15, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [bad5b6606e](https://linux-hardware.org/?probe=bad5b6606e) | Sep 14, 2022 |
| Lenovo        | ThinkPad X230 23252QG       | Notebook    | [4146ff55f9](https://linux-hardware.org/?probe=4146ff55f9) | Sep 10, 2022 |
| Toshiba       | Satellite C55-A-1JL         | Notebook    | [906f27f221](https://linux-hardware.org/?probe=906f27f221) | Sep 10, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [7208ed4b83](https://linux-hardware.org/?probe=7208ed4b83) | Sep 10, 2022 |
| Toshiba       | Satellite C55-A-1JL         | Notebook    | [d229fa96f3](https://linux-hardware.org/?probe=d229fa96f3) | Sep 08, 2022 |
| Lenovo        | B5400 20278                 | Notebook    | [1c9d752f91](https://linux-hardware.org/?probe=1c9d752f91) | Sep 07, 2022 |
| MSI           | MAG B460 TOMAHAWK           | Desktop     | [29eaefa02d](https://linux-hardware.org/?probe=29eaefa02d) | Sep 06, 2022 |
| MSI           | MAG B460 TOMAHAWK           | Desktop     | [4ca1a490f8](https://linux-hardware.org/?probe=4ca1a490f8) | Sep 05, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | Notebook    | [ea93dfd855](https://linux-hardware.org/?probe=ea93dfd855) | Sep 04, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [bd0c518002](https://linux-hardware.org/?probe=bd0c518002) | Sep 03, 2022 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [ba1027940d](https://linux-hardware.org/?probe=ba1027940d) | Sep 03, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [109d233976](https://linux-hardware.org/?probe=109d233976) | Sep 03, 2022 |
| HP            | 620                         | Notebook    | [34002dc814](https://linux-hardware.org/?probe=34002dc814) | Sep 02, 2022 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [5e98ea70fb](https://linux-hardware.org/?probe=5e98ea70fb) | Sep 02, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [4aa935356c](https://linux-hardware.org/?probe=4aa935356c) | Sep 02, 2022 |
| Toshiba       | Satellite C850D-118         | Notebook    | [1950f0aeac](https://linux-hardware.org/?probe=1950f0aeac) | Aug 31, 2022 |
| Toshiba       | Satellite C850D-118         | Notebook    | [07000e4194](https://linux-hardware.org/?probe=07000e4194) | Aug 30, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [61a4780992](https://linux-hardware.org/?probe=61a4780992) | Aug 30, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [8beed8e261](https://linux-hardware.org/?probe=8beed8e261) | Aug 30, 2022 |
| Dell          | G15 5515                    | Notebook    | [708ef41c02](https://linux-hardware.org/?probe=708ef41c02) | Aug 29, 2022 |
| Plaisio       | Turbo X                     | Notebook    | [ae92ead1ca](https://linux-hardware.org/?probe=ae92ead1ca) | Aug 29, 2022 |
| Lenovo        | B590 20208                  | Notebook    | [7eaabdb9ca](https://linux-hardware.org/?probe=7eaabdb9ca) | Aug 27, 2022 |
| HP            | 339A                        | Desktop     | [961ac650aa](https://linux-hardware.org/?probe=961ac650aa) | Aug 24, 2022 |
| ASRock        | H310CM-DVS                  | Desktop     | [17f6682bf3](https://linux-hardware.org/?probe=17f6682bf3) | Aug 20, 2022 |
| ASUSTek       | ProArt B660-CREATOR D4      | Desktop     | [0b9e6d6ad9](https://linux-hardware.org/?probe=0b9e6d6ad9) | Aug 19, 2022 |
| Sony          | VPCEB1S1E                   | Notebook    | [45dbb67d02](https://linux-hardware.org/?probe=45dbb67d02) | Aug 18, 2022 |
| Gigabyte      | B550 AORUS ELITE AX         | Desktop     | [49943f84c8](https://linux-hardware.org/?probe=49943f84c8) | Aug 18, 2022 |
| ASUSTek       | ProArt B660-CREATOR D4      | Desktop     | [f9f180ac3a](https://linux-hardware.org/?probe=f9f180ac3a) | Aug 18, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [3ab7d6393c](https://linux-hardware.org/?probe=3ab7d6393c) | Aug 17, 2022 |
| Dell          | G15 5515                    | Notebook    | [3a7c8ea452](https://linux-hardware.org/?probe=3a7c8ea452) | Aug 17, 2022 |
| ASUSTek       | UX310UQ                     | Notebook    | [f058aa0bf2](https://linux-hardware.org/?probe=f058aa0bf2) | Aug 15, 2022 |
| ASUSTek       | P5K SE                      | Desktop     | [59168fc3cb](https://linux-hardware.org/?probe=59168fc3cb) | Aug 14, 2022 |
| ASRock        | J4125B-ITX                  | Desktop     | [6e4ca6823f](https://linux-hardware.org/?probe=6e4ca6823f) | Aug 14, 2022 |
| ASRock        | J4125B-ITX                  | Desktop     | [81a8491905](https://linux-hardware.org/?probe=81a8491905) | Aug 14, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | Notebook    | [ca96da9d08](https://linux-hardware.org/?probe=ca96da9d08) | Aug 12, 2022 |
| HP            | Laptop 15-db1xxx            | Notebook    | [0644c9f46c](https://linux-hardware.org/?probe=0644c9f46c) | Aug 12, 2022 |
| Lenovo        | V3000 80KV                  | Notebook    | [32c1aa64cf](https://linux-hardware.org/?probe=32c1aa64cf) | Aug 09, 2022 |
| HP            | Laptop 15-db1xxx            | Notebook    | [9e849a1708](https://linux-hardware.org/?probe=9e849a1708) | Aug 07, 2022 |
| Toshiba       | NB100                       | Notebook    | [b91ee9b36b](https://linux-hardware.org/?probe=b91ee9b36b) | Aug 05, 2022 |
| Gigabyte      | B85-HD3                     | Desktop     | [1498e07a4b](https://linux-hardware.org/?probe=1498e07a4b) | Aug 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [e74155922c](https://linux-hardware.org/?probe=e74155922c) | Aug 04, 2022 |
| MSI           | H110M PRO-VH                | Desktop     | [8bdd8d91db](https://linux-hardware.org/?probe=8bdd8d91db) | Aug 04, 2022 |
| ASUSTek       | PRIME B250-PLUS             | Desktop     | [dcc08c0fa5](https://linux-hardware.org/?probe=dcc08c0fa5) | Aug 03, 2022 |
| HP            | Compaq 6730s                | Notebook    | [5d805b2f5e](https://linux-hardware.org/?probe=5d805b2f5e) | Jul 31, 2022 |
| Notebook      | W54_W94_W955TU,-T,-C        | Notebook    | [7b0b52e138](https://linux-hardware.org/?probe=7b0b52e138) | Jul 31, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [ee5c151c3a](https://linux-hardware.org/?probe=ee5c151c3a) | Jul 30, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [e271ff9bf8](https://linux-hardware.org/?probe=e271ff9bf8) | Jul 29, 2022 |
| Gigabyte      | B550 AORUS ELITE AX         | Desktop     | [eee9c60bec](https://linux-hardware.org/?probe=eee9c60bec) | Jul 29, 2022 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [398fb75cec](https://linux-hardware.org/?probe=398fb75cec) | Jul 29, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [ceb1b7da41](https://linux-hardware.org/?probe=ceb1b7da41) | Jul 28, 2022 |
| MSI           | H110M PRO-VH                | Desktop     | [2058561297](https://linux-hardware.org/?probe=2058561297) | Jul 28, 2022 |
| Gigabyte      | Z97X-UD5H                   | Desktop     | [9b3bb82b80](https://linux-hardware.org/?probe=9b3bb82b80) | Jul 28, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [8b520883ad](https://linux-hardware.org/?probe=8b520883ad) | Jul 27, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [cf1f919243](https://linux-hardware.org/?probe=cf1f919243) | Jul 27, 2022 |
| HP            | Pavilion g6                 | Notebook    | [a57cf84361](https://linux-hardware.org/?probe=a57cf84361) | Jul 27, 2022 |
| Gigabyte      | Z68P-DS3                    | Desktop     | [a296eed968](https://linux-hardware.org/?probe=a296eed968) | Jul 27, 2022 |
| Gigabyte      | Z68P-DS3                    | Desktop     | [24ad5aed74](https://linux-hardware.org/?probe=24ad5aed74) | Jul 27, 2022 |
| Sony          | VPCF11M1E                   | Notebook    | [97a18303ee](https://linux-hardware.org/?probe=97a18303ee) | Jul 26, 2022 |
| Dynabook      | Satellite Pro C50D-B        | Notebook    | [bd7ef0af73](https://linux-hardware.org/?probe=bd7ef0af73) | Jul 25, 2022 |
| Dell          | Latitude 5420               | Notebook    | [eecbd6aeec](https://linux-hardware.org/?probe=eecbd6aeec) | Jul 22, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [52ca04ad6b](https://linux-hardware.org/?probe=52ca04ad6b) | Jul 20, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [59e9017400](https://linux-hardware.org/?probe=59e9017400) | Jul 19, 2022 |
| Dell          | Inspiron 15 3511            | Notebook    | [257823caa8](https://linux-hardware.org/?probe=257823caa8) | Jul 17, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [0f1dd0317a](https://linux-hardware.org/?probe=0f1dd0317a) | Jul 17, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [3884be1bc0](https://linux-hardware.org/?probe=3884be1bc0) | Jul 15, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [1d2991137d](https://linux-hardware.org/?probe=1d2991137d) | Jul 15, 2022 |
| Acer          | Extensa 215-32              | Notebook    | [bd34d99acc](https://linux-hardware.org/?probe=bd34d99acc) | Jul 15, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [e992a45818](https://linux-hardware.org/?probe=e992a45818) | Jul 15, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [95b0d6d487](https://linux-hardware.org/?probe=95b0d6d487) | Jul 14, 2022 |
| Toshiba       | Satellite L550              | Notebook    | [cb3f0e6381](https://linux-hardware.org/?probe=cb3f0e6381) | Jul 13, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [8bdaa5b844](https://linux-hardware.org/?probe=8bdaa5b844) | Jul 13, 2022 |
| ASUSTek       | P5Q3                        | Desktop     | [5fb3e2b502](https://linux-hardware.org/?probe=5fb3e2b502) | Jul 10, 2022 |
| Samsung       | 300E4A/300E5A/300E7A        | Notebook    | [f52d09ef30](https://linux-hardware.org/?probe=f52d09ef30) | Jul 07, 2022 |
| HP            | Compaq CQ58                 | Notebook    | [d46da7be57](https://linux-hardware.org/?probe=d46da7be57) | Jul 05, 2022 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [8dceb94bee](https://linux-hardware.org/?probe=8dceb94bee) | Jul 05, 2022 |
| Unknown       | Unknown                     | Notebook    | [df0722af87](https://linux-hardware.org/?probe=df0722af87) | Jul 04, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [af74b651d5](https://linux-hardware.org/?probe=af74b651d5) | Jul 04, 2022 |
| Toshiba       | Satellite A200              | Notebook    | [d030e357db](https://linux-hardware.org/?probe=d030e357db) | Jul 02, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [987d9aa4d3](https://linux-hardware.org/?probe=987d9aa4d3) | Jul 01, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [08ed20d4da](https://linux-hardware.org/?probe=08ed20d4da) | Jul 01, 2022 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [10620fe30b](https://linux-hardware.org/?probe=10620fe30b) | Jun 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [65e5ab29fd](https://linux-hardware.org/?probe=65e5ab29fd) | Jun 26, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [c6c59e12b6](https://linux-hardware.org/?probe=c6c59e12b6) | Jun 25, 2022 |
| Samsung       | 300E4A/300E5A/300E7A        | Notebook    | [bb4f0d2bce](https://linux-hardware.org/?probe=bb4f0d2bce) | Jun 25, 2022 |
| Lenovo        | IdeaPad 5 Pro 16IHU6 82L... | Notebook    | [a2a6f48fe2](https://linux-hardware.org/?probe=a2a6f48fe2) | Jun 22, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [eb61c79793](https://linux-hardware.org/?probe=eb61c79793) | Jun 21, 2022 |
| ASUSTek       | X550JX                      | Notebook    | [999d6e4735](https://linux-hardware.org/?probe=999d6e4735) | Jun 20, 2022 |
| Gigabyte      | 965P-S3                     | Desktop     | [0beb9ce480](https://linux-hardware.org/?probe=0beb9ce480) | Jun 19, 2022 |
| HP            | EliteBook 840 G4            | Notebook    | [d42c64a985](https://linux-hardware.org/?probe=d42c64a985) | Jun 18, 2022 |
| ASRock        | X370 Gaming-ITX/ac          | Desktop     | [292cc4bcab](https://linux-hardware.org/?probe=292cc4bcab) | Jun 17, 2022 |
| Gigabyte      | X570S UD                    | Desktop     | [98f8907a6b](https://linux-hardware.org/?probe=98f8907a6b) | Jun 14, 2022 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | Notebook    | [ee0b4c4389](https://linux-hardware.org/?probe=ee0b4c4389) | Jun 14, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [75fd209e13](https://linux-hardware.org/?probe=75fd209e13) | Jun 14, 2022 |
| Lenovo        | IdeaPad D330-10IGM 81H3     | Tablet      | [6acc89788e](https://linux-hardware.org/?probe=6acc89788e) | Jun 12, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [af2362a1e4](https://linux-hardware.org/?probe=af2362a1e4) | Jun 12, 2022 |
| HP            | ProBook 4530s               | Notebook    | [8162a82eba](https://linux-hardware.org/?probe=8162a82eba) | Jun 11, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [70254d6e4d](https://linux-hardware.org/?probe=70254d6e4d) | Jun 08, 2022 |
| Lenovo        | 3140 NOK                    | Desktop     | [03619a223f](https://linux-hardware.org/?probe=03619a223f) | Jun 07, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [039d0b1cdc](https://linux-hardware.org/?probe=039d0b1cdc) | Jun 07, 2022 |
| Dell          | Precision M4800             | Notebook    | [2607169dfe](https://linux-hardware.org/?probe=2607169dfe) | Jun 06, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [3ede7ad313](https://linux-hardware.org/?probe=3ede7ad313) | Jun 02, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [51e3142bae](https://linux-hardware.org/?probe=51e3142bae) | Jun 02, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [e8e9948f71](https://linux-hardware.org/?probe=e8e9948f71) | Jun 02, 2022 |
| HP            | Unknown                     | Notebook    | [521124e0e2](https://linux-hardware.org/?probe=521124e0e2) | May 28, 2022 |
| Lenovo        | ThinkPad X230 2324FV6       | Notebook    | [6386696f31](https://linux-hardware.org/?probe=6386696f31) | May 25, 2022 |
| Dell          | Vostro 5625                 | Notebook    | [2ae97190b6](https://linux-hardware.org/?probe=2ae97190b6) | May 24, 2022 |
| Dell          | Latitude 5420               | Notebook    | [28c0f1ba96](https://linux-hardware.org/?probe=28c0f1ba96) | May 24, 2022 |
| ASUSTek       | X505BA                      | Notebook    | [685c1f7378](https://linux-hardware.org/?probe=685c1f7378) | May 22, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [22fb59a94a](https://linux-hardware.org/?probe=22fb59a94a) | May 19, 2022 |
| Pegatron      | A15                         | Notebook    | [335d6a014c](https://linux-hardware.org/?probe=335d6a014c) | May 18, 2022 |
| ASUSTek       | P8H61 PRO                   | Desktop     | [87a148ac90](https://linux-hardware.org/?probe=87a148ac90) | May 18, 2022 |
| ASUSTek       | H61M-E                      | Desktop     | [1dc25cb237](https://linux-hardware.org/?probe=1dc25cb237) | May 17, 2022 |
| HP            | Mini 110-1100               | Notebook    | [b93ac7c302](https://linux-hardware.org/?probe=b93ac7c302) | May 16, 2022 |
| HP            | Mini 110-1100               | Notebook    | [4a5f85e53d](https://linux-hardware.org/?probe=4a5f85e53d) | May 16, 2022 |
| HP            | ProBook 645 G1              | Notebook    | [771f25ecc9](https://linux-hardware.org/?probe=771f25ecc9) | May 14, 2022 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [0e9a009c11](https://linux-hardware.org/?probe=0e9a009c11) | May 13, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [2c8d1eec1e](https://linux-hardware.org/?probe=2c8d1eec1e) | May 13, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [074043a5ca](https://linux-hardware.org/?probe=074043a5ca) | May 13, 2022 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [ed659a9633](https://linux-hardware.org/?probe=ed659a9633) | May 13, 2022 |
| Dell          | Inspiron 7786               | Convertible | [7df1484700](https://linux-hardware.org/?probe=7df1484700) | May 12, 2022 |
| AOpen         | i67QMx-DV R1.00BC1 55MP6... | Desktop     | [151db99970](https://linux-hardware.org/?probe=151db99970) | May 11, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [5d59ce5dd7](https://linux-hardware.org/?probe=5d59ce5dd7) | May 11, 2022 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [173fac4f5b](https://linux-hardware.org/?probe=173fac4f5b) | May 11, 2022 |
| HP            | 3031h                       | Desktop     | [4a57ff5761](https://linux-hardware.org/?probe=4a57ff5761) | May 10, 2022 |
| Gigabyte      | Z87X-D3H-CF                 | Desktop     | [8caf6e2b66](https://linux-hardware.org/?probe=8caf6e2b66) | May 09, 2022 |
| Gigabyte      | Z87X-D3H-CF                 | Desktop     | [4242d236c5](https://linux-hardware.org/?probe=4242d236c5) | May 09, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [bdfe0722a7](https://linux-hardware.org/?probe=bdfe0722a7) | May 09, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [4fe934e84d](https://linux-hardware.org/?probe=4fe934e84d) | May 06, 2022 |
| ASRock        | AB350 Gaming-ITX/ac         | Desktop     | [9967806049](https://linux-hardware.org/?probe=9967806049) | May 02, 2022 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | Notebook    | [ec5dbcb034](https://linux-hardware.org/?probe=ec5dbcb034) | May 02, 2022 |
| Dell          | Latitude E6500              | Notebook    | [bbd302d9ba](https://linux-hardware.org/?probe=bbd302d9ba) | May 02, 2022 |
| Dell          | Latitude E6500              | Notebook    | [8eb92ca472](https://linux-hardware.org/?probe=8eb92ca472) | May 02, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [d2903d25c5](https://linux-hardware.org/?probe=d2903d25c5) | Apr 30, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [de4ae72708](https://linux-hardware.org/?probe=de4ae72708) | Apr 28, 2022 |
| Lenovo        | ThinkPad T495 20NJ0012GM    | Notebook    | [81f7a796be](https://linux-hardware.org/?probe=81f7a796be) | Apr 28, 2022 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [c6bf48bfb3](https://linux-hardware.org/?probe=c6bf48bfb3) | Apr 27, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [9da2289998](https://linux-hardware.org/?probe=9da2289998) | Apr 24, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [e9676d63f9](https://linux-hardware.org/?probe=e9676d63f9) | Apr 24, 2022 |
| HP            | Notebook                    | Notebook    | [4772a69956](https://linux-hardware.org/?probe=4772a69956) | Apr 23, 2022 |
| HP            | Notebook                    | Notebook    | [e6099e9fd5](https://linux-hardware.org/?probe=e6099e9fd5) | Apr 22, 2022 |
| ASUSTek       | P5P43TD                     | Desktop     | [8c7c0bd289](https://linux-hardware.org/?probe=8c7c0bd289) | Apr 21, 2022 |
| HP            | Pavilion g7                 | Notebook    | [6bfdb0c3c9](https://linux-hardware.org/?probe=6bfdb0c3c9) | Apr 19, 2022 |
| HP            | Pavilion g7                 | Notebook    | [97e00013eb](https://linux-hardware.org/?probe=97e00013eb) | Apr 19, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [ee7354dd8d](https://linux-hardware.org/?probe=ee7354dd8d) | Apr 19, 2022 |
| Alienware     | M11x                        | Notebook    | [df72ecbe58](https://linux-hardware.org/?probe=df72ecbe58) | Apr 18, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [a6ae41a1c9](https://linux-hardware.org/?probe=a6ae41a1c9) | Apr 18, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [dddd6b6edd](https://linux-hardware.org/?probe=dddd6b6edd) | Apr 18, 2022 |
| Toshiba       | Satellite L50D-B            | Notebook    | [c5d02ba256](https://linux-hardware.org/?probe=c5d02ba256) | Apr 17, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [217905d42a](https://linux-hardware.org/?probe=217905d42a) | Apr 17, 2022 |
| Toshiba       | Satellite L50D-B            | Notebook    | [912c61bb9b](https://linux-hardware.org/?probe=912c61bb9b) | Apr 15, 2022 |
| Lenovo        | IdeaPad 5 Pro 16IHU6 82L... | Notebook    | [4838334e73](https://linux-hardware.org/?probe=4838334e73) | Apr 14, 2022 |
| Dell          | 04PT3G A00                  | Desktop     | [a10754ebca](https://linux-hardware.org/?probe=a10754ebca) | Apr 14, 2022 |
| Dell          | Latitude D630               | Notebook    | [dbee98e342](https://linux-hardware.org/?probe=dbee98e342) | Apr 13, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [92b78eaf1b](https://linux-hardware.org/?probe=92b78eaf1b) | Apr 13, 2022 |
| ASRock        | H97 Pro4                    | Desktop     | [0ad016db29](https://linux-hardware.org/?probe=0ad016db29) | Apr 13, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [b41fc0fac0](https://linux-hardware.org/?probe=b41fc0fac0) | Apr 13, 2022 |
| Unknown       | Z37S                        | Notebook    | [25d5118843](https://linux-hardware.org/?probe=25d5118843) | Apr 13, 2022 |
| Schenker      | XMG NEO (TGL/M21)           | Notebook    | [eeb87dca9a](https://linux-hardware.org/?probe=eeb87dca9a) | Apr 13, 2022 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [5c247da651](https://linux-hardware.org/?probe=5c247da651) | Apr 10, 2022 |
| HP            | G7000                       | Notebook    | [11280d88c6](https://linux-hardware.org/?probe=11280d88c6) | Apr 10, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [761e954b86](https://linux-hardware.org/?probe=761e954b86) | Apr 07, 2022 |
| ASRock        | X399 Phantom Gaming 6       | Desktop     | [111167cacb](https://linux-hardware.org/?probe=111167cacb) | Apr 07, 2022 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | Notebook    | [091e8b72d9](https://linux-hardware.org/?probe=091e8b72d9) | Apr 05, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [cda73dafa0](https://linux-hardware.org/?probe=cda73dafa0) | Apr 04, 2022 |
| Lenovo        | SHARKBAY SDK0J40705 WIN     | Desktop     | [374819f582](https://linux-hardware.org/?probe=374819f582) | Apr 04, 2022 |
| Acer          | Aspire 5745G                | Notebook    | [4a6e981204](https://linux-hardware.org/?probe=4a6e981204) | Apr 04, 2022 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [492c2c7bf4](https://linux-hardware.org/?probe=492c2c7bf4) | Apr 03, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [8d251b1b2a](https://linux-hardware.org/?probe=8d251b1b2a) | Apr 03, 2022 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [97969b1325](https://linux-hardware.org/?probe=97969b1325) | Apr 03, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [8aeaa381e8](https://linux-hardware.org/?probe=8aeaa381e8) | Apr 03, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [722346a184](https://linux-hardware.org/?probe=722346a184) | Apr 03, 2022 |
| ASUSTek       | PRIME H310-PLUS R2.0        | Desktop     | [348af6c202](https://linux-hardware.org/?probe=348af6c202) | Apr 02, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [e237e56d72](https://linux-hardware.org/?probe=e237e56d72) | Apr 02, 2022 |
| Sony          | VGN-AW11XU_Q                | Notebook    | [b3f2270d5f](https://linux-hardware.org/?probe=b3f2270d5f) | Apr 02, 2022 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | Notebook    | [6b00b2928a](https://linux-hardware.org/?probe=6b00b2928a) | Apr 01, 2022 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [3ac2dfc728](https://linux-hardware.org/?probe=3ac2dfc728) | Apr 01, 2022 |
| ASRock        | B75M R2.0                   | Desktop     | [ee7a1d8721](https://linux-hardware.org/?probe=ee7a1d8721) | Mar 30, 2022 |
| HP            | Unknown                     | Notebook    | [e989736b06](https://linux-hardware.org/?probe=e989736b06) | Mar 30, 2022 |
| HP            | Unknown                     | Notebook    | [672d3c8b62](https://linux-hardware.org/?probe=672d3c8b62) | Mar 29, 2022 |
| ASRock        | M3N78D FX                   | Desktop     | [66bb134c6c](https://linux-hardware.org/?probe=66bb134c6c) | Mar 29, 2022 |
| Raspberry ... | Raspberry Pi Zero Rev 1.... | Soc         | [380efd9f08](https://linux-hardware.org/?probe=380efd9f08) | Mar 29, 2022 |
| HP            | 250 G3                      | Notebook    | [22f691edac](https://linux-hardware.org/?probe=22f691edac) | Mar 29, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [6335525127](https://linux-hardware.org/?probe=6335525127) | Mar 28, 2022 |
| ASRock        | N68-GS4 FX R2.0             | Desktop     | [d01df98d83](https://linux-hardware.org/?probe=d01df98d83) | Mar 28, 2022 |
| ASRock        | M3N78D FX                   | Desktop     | [3ebcef4241](https://linux-hardware.org/?probe=3ebcef4241) | Mar 28, 2022 |
| Dell          | Latitude 7420               | Notebook    | [9ef752b49a](https://linux-hardware.org/?probe=9ef752b49a) | Mar 27, 2022 |
| Dell          | Inspiron 5406 2n1           | Convertible | [1297813d45](https://linux-hardware.org/?probe=1297813d45) | Mar 27, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [c8289cd264](https://linux-hardware.org/?probe=c8289cd264) | Mar 26, 2022 |
| HP            | ProBook 4530s               | Notebook    | [f4d3c7fddf](https://linux-hardware.org/?probe=f4d3c7fddf) | Mar 25, 2022 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [22d9e9ead2](https://linux-hardware.org/?probe=22d9e9ead2) | Mar 25, 2022 |
| Lenovo        | IdeaPad Y550 20017          | Notebook    | [09576b4897](https://linux-hardware.org/?probe=09576b4897) | Mar 25, 2022 |
| Lenovo        | IdeaPad Y550 20017          | Notebook    | [610b3ad535](https://linux-hardware.org/?probe=610b3ad535) | Mar 25, 2022 |
| Dell          | Latitude E6220              | Notebook    | [b006a7da3b](https://linux-hardware.org/?probe=b006a7da3b) | Mar 23, 2022 |
| Acer          | Aspire 5930                 | Notebook    | [ac66ce376e](https://linux-hardware.org/?probe=ac66ce376e) | Mar 23, 2022 |
| ASUSTek       | N752VX                      | Notebook    | [9eb7fe04cf](https://linux-hardware.org/?probe=9eb7fe04cf) | Mar 21, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [5c6b1616fa](https://linux-hardware.org/?probe=5c6b1616fa) | Mar 21, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [789a97d437](https://linux-hardware.org/?probe=789a97d437) | Mar 20, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [9055c398c9](https://linux-hardware.org/?probe=9055c398c9) | Mar 18, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [4fa05350b7](https://linux-hardware.org/?probe=4fa05350b7) | Mar 17, 2022 |
| Dell          | Latitude E7470              | Notebook    | [db5eecff9e](https://linux-hardware.org/?probe=db5eecff9e) | Mar 16, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [44e9c813e9](https://linux-hardware.org/?probe=44e9c813e9) | Mar 14, 2022 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [321ad64376](https://linux-hardware.org/?probe=321ad64376) | Mar 13, 2022 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [d5bc8e4202](https://linux-hardware.org/?probe=d5bc8e4202) | Mar 13, 2022 |
| HP            | 1850                        | Desktop     | [7e0b4230d4](https://linux-hardware.org/?probe=7e0b4230d4) | Mar 11, 2022 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [e251c9f079](https://linux-hardware.org/?probe=e251c9f079) | Mar 11, 2022 |
| HP            | 86F3 00100                  | All in one  | [7de0381db8](https://linux-hardware.org/?probe=7de0381db8) | Mar 11, 2022 |
| MSI           | MS-7091                     | Desktop     | [6ff1d651e4](https://linux-hardware.org/?probe=6ff1d651e4) | Mar 11, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [c36fe6c067](https://linux-hardware.org/?probe=c36fe6c067) | Mar 10, 2022 |
| ASUSTek       | P5GC-MX/MEDION/SI           | Desktop     | [772e020316](https://linux-hardware.org/?probe=772e020316) | Mar 09, 2022 |
| ASUSTek       | P5GC-MX/MEDION/SI           | Desktop     | [2a7edc452e](https://linux-hardware.org/?probe=2a7edc452e) | Mar 09, 2022 |
| Gigabyte      | F2A85XM-D3H                 | Desktop     | [cf20f6e233](https://linux-hardware.org/?probe=cf20f6e233) | Mar 09, 2022 |
| MSI           | MS-7091                     | Desktop     | [71aaa6a920](https://linux-hardware.org/?probe=71aaa6a920) | Mar 09, 2022 |
| MSI           | MS-7091                     | Desktop     | [b08ddd1115](https://linux-hardware.org/?probe=b08ddd1115) | Mar 09, 2022 |
| Toshiba       | Satellite C50-B             | Notebook    | [6bffc83185](https://linux-hardware.org/?probe=6bffc83185) | Mar 08, 2022 |
| Dell          | Latitude E6430              | Notebook    | [e32f5b40a1](https://linux-hardware.org/?probe=e32f5b40a1) | Mar 07, 2022 |
| ASUSTek       | X101CH                      | Notebook    | [486f5c28ad](https://linux-hardware.org/?probe=486f5c28ad) | Mar 07, 2022 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [f56996aab6](https://linux-hardware.org/?probe=f56996aab6) | Mar 07, 2022 |
| Acer          | Aspire A515-44G             | Notebook    | [7f95a3373c](https://linux-hardware.org/?probe=7f95a3373c) | Mar 06, 2022 |
| Acer          | Aspire A515-44G             | Notebook    | [ea17b9cff2](https://linux-hardware.org/?probe=ea17b9cff2) | Mar 06, 2022 |
| HP            | 3048h                       | Desktop     | [cb9a7b7f4f](https://linux-hardware.org/?probe=cb9a7b7f4f) | Mar 05, 2022 |
| Dell          | Inspiron 3593               | Notebook    | [9e9718070f](https://linux-hardware.org/?probe=9e9718070f) | Mar 02, 2022 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [3cc5bac970](https://linux-hardware.org/?probe=3cc5bac970) | Mar 02, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [299a727e8a](https://linux-hardware.org/?probe=299a727e8a) | Mar 02, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [2789dc5384](https://linux-hardware.org/?probe=2789dc5384) | Mar 02, 2022 |
| ASUSTek       | PRIME H310-PLUS R2.0        | Desktop     | [3f6b2ab46e](https://linux-hardware.org/?probe=3f6b2ab46e) | Mar 01, 2022 |
| Toshiba       | Satellite C50-A-19T         | Notebook    | [daa7733b2d](https://linux-hardware.org/?probe=daa7733b2d) | Feb 28, 2022 |
| Gigabyte      | H410M S2H V3                | Desktop     | [e5da146c8e](https://linux-hardware.org/?probe=e5da146c8e) | Feb 27, 2022 |
| ASUSTek       | X550CA                      | Notebook    | [926781b691](https://linux-hardware.org/?probe=926781b691) | Feb 27, 2022 |
| Supermicro    | X9SRA/X9SRA-3               | Server      | [7f43788673](https://linux-hardware.org/?probe=7f43788673) | Feb 27, 2022 |
| Fujitsu       | LIFEBOOK S752               | Notebook    | [abb12adccc](https://linux-hardware.org/?probe=abb12adccc) | Feb 26, 2022 |
| HP            | 2000                        | Notebook    | [53d7131a3d](https://linux-hardware.org/?probe=53d7131a3d) | Feb 26, 2022 |
| Clevo         | M740TU(N)/M760TU(N)/W7X0... | Notebook    | [810f5ad6fa](https://linux-hardware.org/?probe=810f5ad6fa) | Feb 25, 2022 |
| Dell          | 0N185P A01                  | Desktop     | [996f9f7805](https://linux-hardware.org/?probe=996f9f7805) | Feb 24, 2022 |
| Fujitsu       | LIFEBOOK AH512              | Notebook    | [d7889a52d1](https://linux-hardware.org/?probe=d7889a52d1) | Feb 24, 2022 |
| ASUSTek       | X550CA                      | Notebook    | [ad54ee0dbe](https://linux-hardware.org/?probe=ad54ee0dbe) | Feb 20, 2022 |
| Gigabyte      | MZBSWMP-00                  | Desktop     | [fc444df804](https://linux-hardware.org/?probe=fc444df804) | Feb 20, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [1ba170be6a](https://linux-hardware.org/?probe=1ba170be6a) | Feb 20, 2022 |
| ASUSTek       | X550CA                      | Notebook    | [c036f1a977](https://linux-hardware.org/?probe=c036f1a977) | Feb 20, 2022 |
| Teclast       | F7                          | Notebook    | [fccda8fbdc](https://linux-hardware.org/?probe=fccda8fbdc) | Feb 20, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [b8e767511b](https://linux-hardware.org/?probe=b8e767511b) | Feb 19, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [9e10ad29c3](https://linux-hardware.org/?probe=9e10ad29c3) | Feb 19, 2022 |
| Lenovo        | G700 20251                  | Notebook    | [2e68ddfdd3](https://linux-hardware.org/?probe=2e68ddfdd3) | Feb 18, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [536a1e49b0](https://linux-hardware.org/?probe=536a1e49b0) | Feb 17, 2022 |
| Lenovo        | IdeaPad D330-10IGM 81H3     | Tablet      | [c9d8bb9bd9](https://linux-hardware.org/?probe=c9d8bb9bd9) | Feb 16, 2022 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [87774dacdd](https://linux-hardware.org/?probe=87774dacdd) | Feb 15, 2022 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [3cf4dc7f97](https://linux-hardware.org/?probe=3cf4dc7f97) | Feb 15, 2022 |
| MSI           | MS-7176                     | Desktop     | [b54631ff57](https://linux-hardware.org/?probe=b54631ff57) | Feb 14, 2022 |
| E-shop.gr     | V113                        | Notebook    | [e9a1ae2e96](https://linux-hardware.org/?probe=e9a1ae2e96) | Feb 14, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [640d06ac28](https://linux-hardware.org/?probe=640d06ac28) | Feb 12, 2022 |
| E-shop.gr     | V113                        | Notebook    | [6d015f399b](https://linux-hardware.org/?probe=6d015f399b) | Feb 12, 2022 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [57de891506](https://linux-hardware.org/?probe=57de891506) | Feb 12, 2022 |
| Gigabyte      | Z87N-WIFI                   | Desktop     | [e86fa9ee02](https://linux-hardware.org/?probe=e86fa9ee02) | Feb 09, 2022 |
| Gigabyte      | Z87N-WIFI                   | Desktop     | [1b6aa0ce08](https://linux-hardware.org/?probe=1b6aa0ce08) | Feb 09, 2022 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [dcd0177f71](https://linux-hardware.org/?probe=dcd0177f71) | Feb 07, 2022 |
| ASUSTek       | 900                         | Notebook    | [88ce413793](https://linux-hardware.org/?probe=88ce413793) | Feb 06, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [8f79e4d763](https://linux-hardware.org/?probe=8f79e4d763) | Feb 06, 2022 |
| Notebook      | W54_W94_W955TU,-T,-C        | Notebook    | [5a3fcd1230](https://linux-hardware.org/?probe=5a3fcd1230) | Feb 05, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [e32abec202](https://linux-hardware.org/?probe=e32abec202) | Feb 03, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [df711c6514](https://linux-hardware.org/?probe=df711c6514) | Feb 03, 2022 |
| Lenovo        | ThinkCentre M58 7373W43     | Desktop     | [4dc312f4f3](https://linux-hardware.org/?probe=4dc312f4f3) | Feb 02, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [f317005b0a](https://linux-hardware.org/?probe=f317005b0a) | Feb 02, 2022 |
| Lenovo        | NOK                         | Desktop     | [8905840b45](https://linux-hardware.org/?probe=8905840b45) | Feb 02, 2022 |
| ASUSTek       | H110M-D                     | Desktop     | [3dbf1d9544](https://linux-hardware.org/?probe=3dbf1d9544) | Jan 31, 2022 |
| Lenovo        | ThinkPad Edge 0301GBG       | Notebook    | [2227d37e2f](https://linux-hardware.org/?probe=2227d37e2f) | Jan 30, 2022 |
| Sony          | SVE1113M1EB                 | Notebook    | [83220eef23](https://linux-hardware.org/?probe=83220eef23) | Jan 30, 2022 |
| HP            | Pavilion dv3                | Notebook    | [c1abcb66ee](https://linux-hardware.org/?probe=c1abcb66ee) | Jan 29, 2022 |
| RuggedPC      | RuggedPadC86V               | Tablet      | [c9f76be971](https://linux-hardware.org/?probe=c9f76be971) | Jan 28, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [48ad956cc2](https://linux-hardware.org/?probe=48ad956cc2) | Jan 28, 2022 |
| HP            | 8434 11                     | Desktop     | [76a7851e7f](https://linux-hardware.org/?probe=76a7851e7f) | Jan 28, 2022 |
| VIA Techno... | VT8366-8233/5               | Desktop     | [e285c87c48](https://linux-hardware.org/?probe=e285c87c48) | Jan 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f7633506c3](https://linux-hardware.org/?probe=f7633506c3) | Jan 26, 2022 |
| VIA Techno... | VT8366-8233/5               | Desktop     | [54ce61fa7e](https://linux-hardware.org/?probe=54ce61fa7e) | Jan 25, 2022 |
| MSI           | A88XM-E45                   | Desktop     | [6a25ca99d2](https://linux-hardware.org/?probe=6a25ca99d2) | Jan 24, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [f6b7e2e2e6](https://linux-hardware.org/?probe=f6b7e2e2e6) | Jan 24, 2022 |
| HP            | 86F3 00100                  | All in one  | [6b9bc0d34d](https://linux-hardware.org/?probe=6b9bc0d34d) | Jan 24, 2022 |
| Lenovo        | 314F NO DPK                 | Desktop     | [07bd238c48](https://linux-hardware.org/?probe=07bd238c48) | Jan 24, 2022 |
| ASRock        | A300M-STX                   | Desktop     | [13de9d767d](https://linux-hardware.org/?probe=13de9d767d) | Jan 21, 2022 |
| MSI           | H310M PRO-VH                | Desktop     | [68c71dac17](https://linux-hardware.org/?probe=68c71dac17) | Jan 21, 2022 |
| ASRock        | G41C-VS                     | Desktop     | [4dbb4b7fad](https://linux-hardware.org/?probe=4dbb4b7fad) | Jan 21, 2022 |
| Albatron      | PM73V                       | Desktop     | [7bd3956f1f](https://linux-hardware.org/?probe=7bd3956f1f) | Jan 21, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [e5d70436b2](https://linux-hardware.org/?probe=e5d70436b2) | Jan 21, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [5716cdab2a](https://linux-hardware.org/?probe=5716cdab2a) | Jan 21, 2022 |
| HP            | 8455                        | Desktop     | [fbf272366c](https://linux-hardware.org/?probe=fbf272366c) | Jan 20, 2022 |
| ASUSTek       | H110M-D                     | Desktop     | [b105d56395](https://linux-hardware.org/?probe=b105d56395) | Jan 19, 2022 |
| ASUSTek       | P5LD2                       | Desktop     | [00ec990ce2](https://linux-hardware.org/?probe=00ec990ce2) | Jan 19, 2022 |
| Dell          | 0KP561                      | Desktop     | [1b772786e5](https://linux-hardware.org/?probe=1b772786e5) | Jan 19, 2022 |
| Dell          | 0FH884                      | Desktop     | [5ffacf9f99](https://linux-hardware.org/?probe=5ffacf9f99) | Jan 19, 2022 |
| Dell          | 0UG982                      | Desktop     | [c85c923e97](https://linux-hardware.org/?probe=c85c923e97) | Jan 19, 2022 |
| Dell          | 0X7841                      | Desktop     | [40600195c8](https://linux-hardware.org/?probe=40600195c8) | Jan 19, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [597677191c](https://linux-hardware.org/?probe=597677191c) | Jan 19, 2022 |
| Dell          | 0UG982                      | Desktop     | [686f3558d2](https://linux-hardware.org/?probe=686f3558d2) | Jan 19, 2022 |
| Lenovo        | 314F NO DPK                 | Desktop     | [f4f3386726](https://linux-hardware.org/?probe=f4f3386726) | Jan 19, 2022 |
| Dell          | 0FH884                      | Desktop     | [f6e9bda3a9](https://linux-hardware.org/?probe=f6e9bda3a9) | Jan 19, 2022 |
| Lenovo        | 314F NO DPK                 | Desktop     | [b9153e0c28](https://linux-hardware.org/?probe=b9153e0c28) | Jan 19, 2022 |
| HP            | 18E7                        | Desktop     | [b68364ed90](https://linux-hardware.org/?probe=b68364ed90) | Jan 19, 2022 |
| Dell          | 0HY9JP A02                  | Desktop     | [8314cd9ba6](https://linux-hardware.org/?probe=8314cd9ba6) | Jan 19, 2022 |
| Dell          | 0UG982                      | Desktop     | [38c30e280b](https://linux-hardware.org/?probe=38c30e280b) | Jan 19, 2022 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [f2d5dba7ff](https://linux-hardware.org/?probe=f2d5dba7ff) | Jan 19, 2022 |
| Dell          | 0FH884                      | Desktop     | [083697081f](https://linux-hardware.org/?probe=083697081f) | Jan 19, 2022 |
| MSI           | H310M PRO-VH                | Desktop     | [844791ed3e](https://linux-hardware.org/?probe=844791ed3e) | Jan 19, 2022 |
| ASRock        | B550M Steel Legend          | Desktop     | [0601abdfa6](https://linux-hardware.org/?probe=0601abdfa6) | Jan 18, 2022 |
| HP            | 18E7                        | Desktop     | [9fedcb7ff7](https://linux-hardware.org/?probe=9fedcb7ff7) | Jan 18, 2022 |
| HP            | 18E7                        | Desktop     | [48871270a2](https://linux-hardware.org/?probe=48871270a2) | Jan 18, 2022 |
| HP            | 18E7                        | Desktop     | [ca38c856e1](https://linux-hardware.org/?probe=ca38c856e1) | Jan 18, 2022 |
| HP            | 18E7                        | Desktop     | [a4df88b38f](https://linux-hardware.org/?probe=a4df88b38f) | Jan 18, 2022 |
| HP            | 18E7                        | Desktop     | [a745b9add0](https://linux-hardware.org/?probe=a745b9add0) | Jan 18, 2022 |
| HP            | 18E7                        | Desktop     | [b69abe6fd4](https://linux-hardware.org/?probe=b69abe6fd4) | Jan 18, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [9753f9164a](https://linux-hardware.org/?probe=9753f9164a) | Jan 18, 2022 |
| Lenovo        | ThinkCentre M58 7373W43     | Desktop     | [2d7a6e6cb6](https://linux-hardware.org/?probe=2d7a6e6cb6) | Jan 18, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [51484889f9](https://linux-hardware.org/?probe=51484889f9) | Jan 18, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [4ca462c89a](https://linux-hardware.org/?probe=4ca462c89a) | Jan 18, 2022 |
| Dell          | 0HY9JP A02                  | Desktop     | [c4c9f4b0a9](https://linux-hardware.org/?probe=c4c9f4b0a9) | Jan 18, 2022 |
| HP            | 8434 11                     | Desktop     | [4a128d2bb2](https://linux-hardware.org/?probe=4a128d2bb2) | Jan 18, 2022 |
| HP            | 18E7                        | Desktop     | [97d4bc7367](https://linux-hardware.org/?probe=97d4bc7367) | Jan 18, 2022 |
| Lenovo        | NOK                         | Desktop     | [7ae2819a6f](https://linux-hardware.org/?probe=7ae2819a6f) | Jan 18, 2022 |
| HP            | 18E7                        | Desktop     | [e86d0cc284](https://linux-hardware.org/?probe=e86d0cc284) | Jan 18, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [022f56a960](https://linux-hardware.org/?probe=022f56a960) | Jan 18, 2022 |
| HP            | 18E7                        | Desktop     | [0d2a09f683](https://linux-hardware.org/?probe=0d2a09f683) | Jan 18, 2022 |
| HP            | 8455                        | Desktop     | [639182896b](https://linux-hardware.org/?probe=639182896b) | Jan 18, 2022 |
| ASUSTek       | H81M-C                      | Desktop     | [f4bb742149](https://linux-hardware.org/?probe=f4bb742149) | Jan 17, 2022 |
| ASUSTek       | P5LD2                       | Desktop     | [b972c7929f](https://linux-hardware.org/?probe=b972c7929f) | Jan 17, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [9a6c2f82f1](https://linux-hardware.org/?probe=9a6c2f82f1) | Jan 17, 2022 |
| Dell          | 0UG982                      | Desktop     | [684478b2fb](https://linux-hardware.org/?probe=684478b2fb) | Jan 17, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [13b01fb40a](https://linux-hardware.org/?probe=13b01fb40a) | Jan 17, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [385f76b996](https://linux-hardware.org/?probe=385f76b996) | Jan 17, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [910af5ce1a](https://linux-hardware.org/?probe=910af5ce1a) | Jan 17, 2022 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [dc02dbb307](https://linux-hardware.org/?probe=dc02dbb307) | Jan 16, 2022 |
| ASUSTek       | H81M-C                      | Desktop     | [f21bf32c9a](https://linux-hardware.org/?probe=f21bf32c9a) | Jan 15, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [f1858e63f4](https://linux-hardware.org/?probe=f1858e63f4) | Jan 14, 2022 |
| Gigabyte      | P55-USB3                    | Desktop     | [07d50b5a0a](https://linux-hardware.org/?probe=07d50b5a0a) | Jan 14, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [6261e290d6](https://linux-hardware.org/?probe=6261e290d6) | Jan 13, 2022 |
| Dell          | Latitude E5440              | Notebook    | [e4ec245baf](https://linux-hardware.org/?probe=e4ec245baf) | Jan 12, 2022 |
| Lenovo        | ThinkPad Edge 0301GBG       | Notebook    | [41205188c5](https://linux-hardware.org/?probe=41205188c5) | Jan 12, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [32b2cea437](https://linux-hardware.org/?probe=32b2cea437) | Jan 10, 2022 |
| Unknown       | Unknown                     | Notebook    | [5557e91853](https://linux-hardware.org/?probe=5557e91853) | Jan 09, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [c09f135f63](https://linux-hardware.org/?probe=c09f135f63) | Jan 09, 2022 |
| HP            | Notebook                    | Notebook    | [97eb40cec9](https://linux-hardware.org/?probe=97eb40cec9) | Jan 07, 2022 |
| Dell          | Inspiron 3585               | Notebook    | [bd035d052c](https://linux-hardware.org/?probe=bd035d052c) | Jan 07, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [5467cc6a24](https://linux-hardware.org/?probe=5467cc6a24) | Jan 06, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [7887040435](https://linux-hardware.org/?probe=7887040435) | Jan 05, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [a03baba93d](https://linux-hardware.org/?probe=a03baba93d) | Jan 05, 2022 |
| ASRock        | H97M Pro4                   | Desktop     | [92a6f429b5](https://linux-hardware.org/?probe=92a6f429b5) | Jan 05, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [f5f5eadcd4](https://linux-hardware.org/?probe=f5f5eadcd4) | Jan 04, 2022 |
| ECS           | G31T-M7                     | Desktop     | [8cd5d79924](https://linux-hardware.org/?probe=8cd5d79924) | Dec 31, 2021 |
| ECS           | G31T-M7                     | Desktop     | [9ebfb53472](https://linux-hardware.org/?probe=9ebfb53472) | Dec 31, 2021 |
| HP            | Compaq 6730s                | Notebook    | [bd8962f904](https://linux-hardware.org/?probe=bd8962f904) | Dec 30, 2021 |
| Acer          | AOA110                      | Notebook    | [1670ad4a71](https://linux-hardware.org/?probe=1670ad4a71) | Dec 29, 2021 |
| ASRock        | B75M R2.0                   | Desktop     | [8e4a08a77a](https://linux-hardware.org/?probe=8e4a08a77a) | Dec 26, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [68ea35c97d](https://linux-hardware.org/?probe=68ea35c97d) | Dec 25, 2021 |
| Foxconn       | 2ABF                        | Desktop     | [fdc6aac853](https://linux-hardware.org/?probe=fdc6aac853) | Dec 25, 2021 |
| Gigabyte      | H170M-D3H DDR3-CF           | Desktop     | [537cb36279](https://linux-hardware.org/?probe=537cb36279) | Dec 25, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [261883bf38](https://linux-hardware.org/?probe=261883bf38) | Dec 23, 2021 |
| HP            | Notebook                    | Notebook    | [c14ea64659](https://linux-hardware.org/?probe=c14ea64659) | Dec 23, 2021 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [c860a1c3c5](https://linux-hardware.org/?probe=c860a1c3c5) | Dec 22, 2021 |
| Dell          | Vostro 3580                 | Notebook    | [a57edf2ddc](https://linux-hardware.org/?probe=a57edf2ddc) | Dec 22, 2021 |
| MSI           | H81M PRO-VD                 | Desktop     | [b0c70d78fd](https://linux-hardware.org/?probe=b0c70d78fd) | Dec 22, 2021 |
| Sony          | SVE1113M1EB                 | Notebook    | [09619ba678](https://linux-hardware.org/?probe=09619ba678) | Dec 19, 2021 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [8962cfd1c6](https://linux-hardware.org/?probe=8962cfd1c6) | Dec 19, 2021 |
| Dell          | 0MN1TX A01                  | Desktop     | [312bd0bfd8](https://linux-hardware.org/?probe=312bd0bfd8) | Dec 18, 2021 |
| IBM           | 00D4062                     | Server      | [76a0ebbfc4](https://linux-hardware.org/?probe=76a0ebbfc4) | Dec 17, 2021 |
| ASUSTek       | P5LD2-Deluxe                | Desktop     | [a2ee48eeb1](https://linux-hardware.org/?probe=a2ee48eeb1) | Dec 16, 2021 |
| Dell          | Inspiron 3585               | Notebook    | [e12da201c3](https://linux-hardware.org/?probe=e12da201c3) | Dec 16, 2021 |
| Dell          | Inspiron 3585               | Notebook    | [f8e1e0ea63](https://linux-hardware.org/?probe=f8e1e0ea63) | Dec 16, 2021 |
| Sony          | SVE1113M1EB                 | Notebook    | [a91f9c891f](https://linux-hardware.org/?probe=a91f9c891f) | Dec 15, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [495d348f1e](https://linux-hardware.org/?probe=495d348f1e) | Dec 15, 2021 |
| HP            | G62                         | Notebook    | [80ca0b53f0](https://linux-hardware.org/?probe=80ca0b53f0) | Dec 14, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [da23db2916](https://linux-hardware.org/?probe=da23db2916) | Dec 13, 2021 |
| ASUSTek       | P8P67 LE                    | Desktop     | [b86c41a0a9](https://linux-hardware.org/?probe=b86c41a0a9) | Dec 13, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [ecc22ad350](https://linux-hardware.org/?probe=ecc22ad350) | Dec 12, 2021 |
| Sony          | SVF1521A1EW                 | Notebook    | [3ffae5f3ba](https://linux-hardware.org/?probe=3ffae5f3ba) | Dec 12, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [b049c5de44](https://linux-hardware.org/?probe=b049c5de44) | Dec 12, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [ac3e0f0271](https://linux-hardware.org/?probe=ac3e0f0271) | Dec 11, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [191c3b9c7e](https://linux-hardware.org/?probe=191c3b9c7e) | Dec 10, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [c7efd05b73](https://linux-hardware.org/?probe=c7efd05b73) | Dec 10, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [1876329ada](https://linux-hardware.org/?probe=1876329ada) | Dec 10, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [c97b5a008f](https://linux-hardware.org/?probe=c97b5a008f) | Dec 09, 2021 |
| Toshiba       | Satellite C850D-118         | Notebook    | [b15f2e2c92](https://linux-hardware.org/?probe=b15f2e2c92) | Dec 09, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [f0a11b91f5](https://linux-hardware.org/?probe=f0a11b91f5) | Dec 09, 2021 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [11f31cc288](https://linux-hardware.org/?probe=11f31cc288) | Dec 08, 2021 |
| Gigabyte      | Z97P-D3                     | Desktop     | [abc89c9b78](https://linux-hardware.org/?probe=abc89c9b78) | Dec 07, 2021 |
| Gateway       | DT55                        | Desktop     | [efc935f11c](https://linux-hardware.org/?probe=efc935f11c) | Dec 06, 2021 |
| Dell          | Inspiron 3585               | Notebook    | [eea11725bb](https://linux-hardware.org/?probe=eea11725bb) | Dec 06, 2021 |
| Gigabyte      | G31M-S2C                    | Desktop     | [75933dd4ba](https://linux-hardware.org/?probe=75933dd4ba) | Dec 06, 2021 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [998b2258eb](https://linux-hardware.org/?probe=998b2258eb) | Dec 05, 2021 |
| Dell          | Inspiron 3585               | Notebook    | [d614f524af](https://linux-hardware.org/?probe=d614f524af) | Dec 05, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [e2d660554f](https://linux-hardware.org/?probe=e2d660554f) | Dec 05, 2021 |
| Acer          | Aspire 7540                 | Notebook    | [ebaf96fd07](https://linux-hardware.org/?probe=ebaf96fd07) | Dec 04, 2021 |
| Dell          | Inspiron 3541               | Notebook    | [6b187612d2](https://linux-hardware.org/?probe=6b187612d2) | Dec 04, 2021 |
| Sony          | SVE1711Q1EB                 | Notebook    | [a4e4d21671](https://linux-hardware.org/?probe=a4e4d21671) | Dec 04, 2021 |
| HP            | Compaq 6910p (GC021ET#AB... | Notebook    | [677180a63e](https://linux-hardware.org/?probe=677180a63e) | Dec 03, 2021 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [5ade9a0569](https://linux-hardware.org/?probe=5ade9a0569) | Dec 02, 2021 |
| Dell          | 0WK833                      | Desktop     | [59fed7d754](https://linux-hardware.org/?probe=59fed7d754) | Nov 30, 2021 |
| Lenovo        | G70-35 80Q5                 | Notebook    | [a53168ca9d](https://linux-hardware.org/?probe=a53168ca9d) | Nov 30, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [d860ff9858](https://linux-hardware.org/?probe=d860ff9858) | Nov 30, 2021 |
| HP            | Pavilion g7                 | Notebook    | [da6e298046](https://linux-hardware.org/?probe=da6e298046) | Nov 29, 2021 |
| Sony          | SVE1113M1EB                 | Notebook    | [e2df3c29e6](https://linux-hardware.org/?probe=e2df3c29e6) | Nov 29, 2021 |
| Dell          | Latitude 7490               | Notebook    | [c12e537d05](https://linux-hardware.org/?probe=c12e537d05) | Nov 29, 2021 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [6e37f9cd8a](https://linux-hardware.org/?probe=6e37f9cd8a) | Nov 29, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [999b38ba1f](https://linux-hardware.org/?probe=999b38ba1f) | Nov 28, 2021 |
| Dell          | 042P49 A02                  | Desktop     | [f6d9c481bd](https://linux-hardware.org/?probe=f6d9c481bd) | Nov 27, 2021 |
| Gigabyte      | P35-S3G                     | Desktop     | [f8b94398df](https://linux-hardware.org/?probe=f8b94398df) | Nov 27, 2021 |
| Toshiba       | Satellite C855-27U          | Notebook    | [5974840aa7](https://linux-hardware.org/?probe=5974840aa7) | Nov 27, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [82a3d5c144](https://linux-hardware.org/?probe=82a3d5c144) | Nov 27, 2021 |
| Unknown       | Unknown                     | Notebook    | [72b623d149](https://linux-hardware.org/?probe=72b623d149) | Nov 27, 2021 |
| Toshiba       | Satellite C850D-118         | Notebook    | [db07af607f](https://linux-hardware.org/?probe=db07af607f) | Nov 26, 2021 |
| ASRock        | B450 Gaming K4              | Desktop     | [ba4141a214](https://linux-hardware.org/?probe=ba4141a214) | Nov 26, 2021 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [b6396cac2d](https://linux-hardware.org/?probe=b6396cac2d) | Nov 25, 2021 |
| Sony          | SVF1521A1EW                 | Notebook    | [52bd968f68](https://linux-hardware.org/?probe=52bd968f68) | Nov 25, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [2c14d4d6ad](https://linux-hardware.org/?probe=2c14d4d6ad) | Nov 23, 2021 |
| Unknown       | Unknown                     | Notebook    | [b6800c14dc](https://linux-hardware.org/?probe=b6800c14dc) | Nov 21, 2021 |
| Unknown       | Unknown                     | Notebook    | [65b01d9a8a](https://linux-hardware.org/?probe=65b01d9a8a) | Nov 21, 2021 |
| ASUSTek       | X550CC                      | Notebook    | [9915f9e908](https://linux-hardware.org/?probe=9915f9e908) | Nov 20, 2021 |
| ASRock        | B75M R2.0                   | Desktop     | [000f6b6f44](https://linux-hardware.org/?probe=000f6b6f44) | Nov 20, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | Notebook    | [709cd419bc](https://linux-hardware.org/?probe=709cd419bc) | Nov 19, 2021 |
| HP            | 304Bh                       | Desktop     | [d6f490c0ea](https://linux-hardware.org/?probe=d6f490c0ea) | Nov 19, 2021 |
| Acer          | TravelMate 5720             | Notebook    | [77b5cad080](https://linux-hardware.org/?probe=77b5cad080) | Nov 18, 2021 |
| Intel         | NUC5i5RYB H40999-504        | Mini pc     | [b3319a217d](https://linux-hardware.org/?probe=b3319a217d) | Nov 17, 2021 |
| Acer          | Aspire 5735                 | Notebook    | [9b2574c5be](https://linux-hardware.org/?probe=9b2574c5be) | Nov 17, 2021 |
| Dell          | 0Y2K8N A00                  | Desktop     | [db79ad16d3](https://linux-hardware.org/?probe=db79ad16d3) | Nov 16, 2021 |
| MSI           | B350 TOMAHAWK ARCTIC        | Desktop     | [9cc745f754](https://linux-hardware.org/?probe=9cc745f754) | Nov 16, 2021 |
| ASUSTek       | X550CC                      | Notebook    | [e39729aec8](https://linux-hardware.org/?probe=e39729aec8) | Nov 14, 2021 |
| Gigabyte      | 945P-S3                     | Desktop     | [770408fd3d](https://linux-hardware.org/?probe=770408fd3d) | Nov 14, 2021 |
| Gigabyte      | 945P-S3                     | Desktop     | [2cf9966c22](https://linux-hardware.org/?probe=2cf9966c22) | Nov 14, 2021 |
| Acer          | Aspire E5-553G              | Notebook    | [b22df8f53d](https://linux-hardware.org/?probe=b22df8f53d) | Nov 14, 2021 |
| Acer          | Aspire E5-553G              | Notebook    | [93d20530a1](https://linux-hardware.org/?probe=93d20530a1) | Nov 14, 2021 |
| Gigabyte      | G41M-Combo                  | Desktop     | [7a3d3a2f06](https://linux-hardware.org/?probe=7a3d3a2f06) | Nov 12, 2021 |
| Acer          | Aspire 5742                 | Notebook    | [4c0a93b88d](https://linux-hardware.org/?probe=4c0a93b88d) | Nov 12, 2021 |
| Lenovo        | IdeaPad 5 Pro 16IHU6 82L... | Notebook    | [a7998fa53a](https://linux-hardware.org/?probe=a7998fa53a) | Nov 11, 2021 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [867958b2cc](https://linux-hardware.org/?probe=867958b2cc) | Nov 11, 2021 |
| Dell          | 0DXJD9 A00                  | Desktop     | [e9abfeb7a2](https://linux-hardware.org/?probe=e9abfeb7a2) | Nov 11, 2021 |
| Intel         | NUC5i5RYB H40999-504        | Mini pc     | [476167fea8](https://linux-hardware.org/?probe=476167fea8) | Nov 10, 2021 |
| HP            | 339A                        | Desktop     | [702ccff1e4](https://linux-hardware.org/?probe=702ccff1e4) | Nov 09, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [9dc24197f3](https://linux-hardware.org/?probe=9dc24197f3) | Nov 09, 2021 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [dc9fcc92be](https://linux-hardware.org/?probe=dc9fcc92be) | Nov 08, 2021 |
| ASUSTek       | 900                         | Notebook    | [b3f1475dcf](https://linux-hardware.org/?probe=b3f1475dcf) | Nov 08, 2021 |
| HP            | 255 G1                      | Notebook    | [3676d15104](https://linux-hardware.org/?probe=3676d15104) | Nov 06, 2021 |
| MSI           | B150M MORTAR                | Desktop     | [58d8ce0102](https://linux-hardware.org/?probe=58d8ce0102) | Nov 05, 2021 |
| ASUSTek       | P5LD2-Deluxe                | Desktop     | [d1dcf79c72](https://linux-hardware.org/?probe=d1dcf79c72) | Nov 05, 2021 |
| Sony          | SVE1513Y1ESI                | Notebook    | [fc86d071c2](https://linux-hardware.org/?probe=fc86d071c2) | Nov 02, 2021 |
| Lenovo        | IdeaPad D330-10IGM 81H3     | Tablet      | [44acfe85a5](https://linux-hardware.org/?probe=44acfe85a5) | Oct 31, 2021 |
| Fujitsu Si... | AMILO Xi 2428               | Notebook    | [3332a4c510](https://linux-hardware.org/?probe=3332a4c510) | Oct 30, 2021 |
| Dell          | Latitude 5520               | Notebook    | [370dda1922](https://linux-hardware.org/?probe=370dda1922) | Oct 28, 2021 |
| HP            | Pavilion dv7                | Notebook    | [d4b81612a8](https://linux-hardware.org/?probe=d4b81612a8) | Oct 28, 2021 |
| Dell          | Latitude 5520               | Notebook    | [2a08ef4aeb](https://linux-hardware.org/?probe=2a08ef4aeb) | Oct 27, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [02cc756dd4](https://linux-hardware.org/?probe=02cc756dd4) | Oct 26, 2021 |
| ASUSTek       | TP202NAS                    | Convertible | [3498f0a5df](https://linux-hardware.org/?probe=3498f0a5df) | Oct 26, 2021 |
| Lenovo        | ThinkPad E595 20NF0002BM    | Notebook    | [52ba950565](https://linux-hardware.org/?probe=52ba950565) | Oct 25, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [cecd552e89](https://linux-hardware.org/?probe=cecd552e89) | Oct 25, 2021 |
| Lenovo        | G50-30 80G0                 | Notebook    | [4e11b29d08](https://linux-hardware.org/?probe=4e11b29d08) | Oct 23, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [16268db25b](https://linux-hardware.org/?probe=16268db25b) | Oct 22, 2021 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [963b34aa8b](https://linux-hardware.org/?probe=963b34aa8b) | Oct 22, 2021 |
| Toshiba       | Satellite L50-A-1D9         | Notebook    | [cd55b73689](https://linux-hardware.org/?probe=cd55b73689) | Oct 20, 2021 |
| Lenovo        | ThinkCentre M71e 3167A46    | Desktop     | [afc98aba09](https://linux-hardware.org/?probe=afc98aba09) | Oct 20, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [c76a2534a0](https://linux-hardware.org/?probe=c76a2534a0) | Oct 19, 2021 |
| HP            | Notebook                    | Notebook    | [ff690977bf](https://linux-hardware.org/?probe=ff690977bf) | Oct 19, 2021 |
| HP            | 8717                        | Desktop     | [23f7ea44ce](https://linux-hardware.org/?probe=23f7ea44ce) | Oct 18, 2021 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [fa1ceccee5](https://linux-hardware.org/?probe=fa1ceccee5) | Oct 18, 2021 |
| Dell          | Inspiron 3537               | Notebook    | [255aca010b](https://linux-hardware.org/?probe=255aca010b) | Oct 18, 2021 |
| HP            | 1496                        | Desktop     | [f438fdb757](https://linux-hardware.org/?probe=f438fdb757) | Oct 17, 2021 |
| Dell          | Precision M4800             | Notebook    | [87034ed159](https://linux-hardware.org/?probe=87034ed159) | Oct 16, 2021 |
| MSI           | H110I PRO                   | Desktop     | [0aeac6b99e](https://linux-hardware.org/?probe=0aeac6b99e) | Oct 16, 2021 |
| HP            | 1495                        | Desktop     | [e7c0f59f92](https://linux-hardware.org/?probe=e7c0f59f92) | Oct 15, 2021 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [7ba2477e56](https://linux-hardware.org/?probe=7ba2477e56) | Oct 13, 2021 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [ae1811a242](https://linux-hardware.org/?probe=ae1811a242) | Oct 13, 2021 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [a671b6ab07](https://linux-hardware.org/?probe=a671b6ab07) | Oct 11, 2021 |
| HP            | 1496                        | Desktop     | [f6ad468908](https://linux-hardware.org/?probe=f6ad468908) | Oct 10, 2021 |
| ARIMA         | W651UI                      | Notebook    | [287379af9f](https://linux-hardware.org/?probe=287379af9f) | Oct 10, 2021 |
| MSI           | H110I PRO                   | Desktop     | [33e1bf9b6c](https://linux-hardware.org/?probe=33e1bf9b6c) | Oct 09, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [13ee121adc](https://linux-hardware.org/?probe=13ee121adc) | Oct 07, 2021 |
| MSI           | B150M MORTAR                | Desktop     | [fd3b108340](https://linux-hardware.org/?probe=fd3b108340) | Oct 07, 2021 |
| MSI           | Alpha 17 A4DEK              | Notebook    | [eca8493d4b](https://linux-hardware.org/?probe=eca8493d4b) | Oct 07, 2021 |
| HP            | 1496                        | Desktop     | [3f369a5dd6](https://linux-hardware.org/?probe=3f369a5dd6) | Oct 06, 2021 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [415ce3638d](https://linux-hardware.org/?probe=415ce3638d) | Oct 06, 2021 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [74e6b1bc07](https://linux-hardware.org/?probe=74e6b1bc07) | Oct 06, 2021 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [9e35238cd2](https://linux-hardware.org/?probe=9e35238cd2) | Oct 05, 2021 |
| ASUSTek       | PRIME H310-PLUS R2.0        | Desktop     | [c627fc3c07](https://linux-hardware.org/?probe=c627fc3c07) | Oct 04, 2021 |
| HP            | 255 G6 Notebook PC          | Notebook    | [6ae274321c](https://linux-hardware.org/?probe=6ae274321c) | Oct 03, 2021 |
| MSI           | B150M MORTAR                | Desktop     | [224b713b5c](https://linux-hardware.org/?probe=224b713b5c) | Oct 03, 2021 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [62558ba69c](https://linux-hardware.org/?probe=62558ba69c) | Sep 29, 2021 |
| Lenovo        | ThinkPad T420 4236A22       | Notebook    | [e92d8556e9](https://linux-hardware.org/?probe=e92d8556e9) | Sep 29, 2021 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [68b6365968](https://linux-hardware.org/?probe=68b6365968) | Sep 28, 2021 |
| ASUSTek       | ROG STRIX X399-E GAMING     | Desktop     | [1c1bca9399](https://linux-hardware.org/?probe=1c1bca9399) | Sep 28, 2021 |
| PC Special... | N85_N87,HJ,HJ1,HK1          | Notebook    | [c5a7069c64](https://linux-hardware.org/?probe=c5a7069c64) | Sep 26, 2021 |
| Apple         | MacBookAir3,1               | Notebook    | [2b14368aed](https://linux-hardware.org/?probe=2b14368aed) | Sep 25, 2021 |
| ASRock        | M3A790GXH/128M              | Desktop     | [818ec10ec8](https://linux-hardware.org/?probe=818ec10ec8) | Sep 24, 2021 |
| HP            | Pavilion g6                 | Notebook    | [43a34f4589](https://linux-hardware.org/?probe=43a34f4589) | Sep 23, 2021 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [bfa3ee0eda](https://linux-hardware.org/?probe=bfa3ee0eda) | Sep 22, 2021 |
| ASUSTek       | ROG STRIX X399-E GAMING     | Desktop     | [b04783b7e1](https://linux-hardware.org/?probe=b04783b7e1) | Sep 20, 2021 |
| Sony          | VGN-FW510F                  | Notebook    | [8f2f403347](https://linux-hardware.org/?probe=8f2f403347) | Sep 19, 2021 |
| Fujitsu Si... | AMILO M7440D                | Notebook    | [e23f21b9b4](https://linux-hardware.org/?probe=e23f21b9b4) | Sep 19, 2021 |
| Fujitsu Si... | AMILO M7440D                | Notebook    | [bce3e66350](https://linux-hardware.org/?probe=bce3e66350) | Sep 19, 2021 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [ad193a0b9c](https://linux-hardware.org/?probe=ad193a0b9c) | Sep 16, 2021 |
| Apple         | MacBookPro8,2               | Notebook    | [64a2bd261a](https://linux-hardware.org/?probe=64a2bd261a) | Sep 12, 2021 |
| Acer          | Aspire 5020                 | Notebook    | [54ddef7aa7](https://linux-hardware.org/?probe=54ddef7aa7) | Sep 11, 2021 |
| Acer          | Aspire 5020                 | Notebook    | [8c00427976](https://linux-hardware.org/?probe=8c00427976) | Sep 11, 2021 |
| Acer          | Aspire 3610                 | Notebook    | [fc6953a3f9](https://linux-hardware.org/?probe=fc6953a3f9) | Sep 10, 2021 |
| Acer          | Aspire 3610                 | Notebook    | [3ab0387498](https://linux-hardware.org/?probe=3ab0387498) | Sep 08, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [0bfdb154b9](https://linux-hardware.org/?probe=0bfdb154b9) | Sep 08, 2021 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [d45a82c3c9](https://linux-hardware.org/?probe=d45a82c3c9) | Sep 06, 2021 |
| HP            | 255 G3                      | Notebook    | [bd1a8b58da](https://linux-hardware.org/?probe=bd1a8b58da) | Sep 03, 2021 |
| HP            | 255 G3                      | Notebook    | [b5f1c73339](https://linux-hardware.org/?probe=b5f1c73339) | Sep 03, 2021 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | Notebook    | [d3f86f70ae](https://linux-hardware.org/?probe=d3f86f70ae) | Sep 03, 2021 |
| HP            | Presario CQ58               | Notebook    | [313af01ef8](https://linux-hardware.org/?probe=313af01ef8) | Sep 01, 2021 |
| Foxconn       | 2ABF                        | Desktop     | [171462cc36](https://linux-hardware.org/?probe=171462cc36) | Aug 29, 2021 |
| MSI           | 970A SLI Krait Edition      | Desktop     | [862999e242](https://linux-hardware.org/?probe=862999e242) | Aug 27, 2021 |
| Dell          | Inspiron 15 5510            | Notebook    | [cbc1dd6499](https://linux-hardware.org/?probe=cbc1dd6499) | Aug 27, 2021 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [540c64bf79](https://linux-hardware.org/?probe=540c64bf79) | Aug 26, 2021 |
| Sony          | SVT1122B2EW                 | Notebook    | [cb166ff02b](https://linux-hardware.org/?probe=cb166ff02b) | Aug 24, 2021 |
| Gigabyte      | F2A88XM-HD3P                | Desktop     | [dee9503ed0](https://linux-hardware.org/?probe=dee9503ed0) | Aug 24, 2021 |
| Sony          | SVT1122B2EW                 | Notebook    | [7ef0a9c54a](https://linux-hardware.org/?probe=7ef0a9c54a) | Aug 21, 2021 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [80dfc52333](https://linux-hardware.org/?probe=80dfc52333) | Aug 21, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [1639c4e352](https://linux-hardware.org/?probe=1639c4e352) | Aug 20, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [a7c72d0be5](https://linux-hardware.org/?probe=a7c72d0be5) | Aug 20, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [301da897a6](https://linux-hardware.org/?probe=301da897a6) | Aug 19, 2021 |
| Pegatron      | 2A72h                       | Desktop     | [57575daae2](https://linux-hardware.org/?probe=57575daae2) | Aug 19, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [e1467bfa3e](https://linux-hardware.org/?probe=e1467bfa3e) | Aug 18, 2021 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [0cdcd7cac9](https://linux-hardware.org/?probe=0cdcd7cac9) | Aug 17, 2021 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [d436538e39](https://linux-hardware.org/?probe=d436538e39) | Aug 13, 2021 |
| Acer          | Aspire A517-51G             | Notebook    | [6387ddee62](https://linux-hardware.org/?probe=6387ddee62) | Aug 13, 2021 |
| Dell          | Latitude 7420               | Notebook    | [67165b9d66](https://linux-hardware.org/?probe=67165b9d66) | Aug 12, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [b937ce5e88](https://linux-hardware.org/?probe=b937ce5e88) | Aug 10, 2021 |
| HP            | Pavilion g6                 | Notebook    | [d4523e209b](https://linux-hardware.org/?probe=d4523e209b) | Aug 09, 2021 |
| Lenovo        | 36EE SDK0J40700 WIN 3258... | Desktop     | [a2c47444e8](https://linux-hardware.org/?probe=a2c47444e8) | Aug 09, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [b5f6eb1dc0](https://linux-hardware.org/?probe=b5f6eb1dc0) | Aug 09, 2021 |
| HP            | Pavilion g6                 | Notebook    | [4116e486f5](https://linux-hardware.org/?probe=4116e486f5) | Aug 07, 2021 |
| Samsung       | R780                        | Notebook    | [f59b3d2a3f](https://linux-hardware.org/?probe=f59b3d2a3f) | Aug 05, 2021 |
| MSI           | 970A SLI Krait Edition      | Desktop     | [08cf0272da](https://linux-hardware.org/?probe=08cf0272da) | Aug 05, 2021 |
| Dell          | Latitude 5410               | Notebook    | [5f861ac987](https://linux-hardware.org/?probe=5f861ac987) | Aug 04, 2021 |
| Dell          | Latitude 5410               | Notebook    | [aed58623e2](https://linux-hardware.org/?probe=aed58623e2) | Aug 04, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [7243281e28](https://linux-hardware.org/?probe=7243281e28) | Aug 01, 2021 |
| Dell          | Latitude 7390               | Notebook    | [ee6d9cb25f](https://linux-hardware.org/?probe=ee6d9cb25f) | Aug 01, 2021 |
| Dell          | Vostro 5502                 | Notebook    | [f1e6f11078](https://linux-hardware.org/?probe=f1e6f11078) | Jul 31, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [49e2ef564c](https://linux-hardware.org/?probe=49e2ef564c) | Jul 31, 2021 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [4c6cb12482](https://linux-hardware.org/?probe=4c6cb12482) | Jul 30, 2021 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | Notebook    | [1cd2de69ff](https://linux-hardware.org/?probe=1cd2de69ff) | Jul 29, 2021 |
| Toshiba       | Satellite C850D-119         | Notebook    | [bb3f1b4afa](https://linux-hardware.org/?probe=bb3f1b4afa) | Jul 29, 2021 |
| Dell          | Latitude E7470              | Notebook    | [9d580f1809](https://linux-hardware.org/?probe=9d580f1809) | Jul 28, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [e2877b1692](https://linux-hardware.org/?probe=e2877b1692) | Jul 27, 2021 |
| Gigabyte      | P35C-DS3R                   | Desktop     | [e8ffe8991b](https://linux-hardware.org/?probe=e8ffe8991b) | Jul 27, 2021 |
| Dell          | Studio 1555                 | Notebook    | [30b17f2421](https://linux-hardware.org/?probe=30b17f2421) | Jul 26, 2021 |
| Acer          | Aspire 5735                 | Notebook    | [60451d6f55](https://linux-hardware.org/?probe=60451d6f55) | Jul 25, 2021 |
| Fujitsu       | LIFEBOOK AH532/G52          | Notebook    | [4e8d8d9253](https://linux-hardware.org/?probe=4e8d8d9253) | Jul 25, 2021 |
| Dell          | 0JD6X3 A05                  | Server      | [494cd954e9](https://linux-hardware.org/?probe=494cd954e9) | Jul 22, 2021 |
| MSI           | H81M PRO-VD                 | Desktop     | [190d4540e9](https://linux-hardware.org/?probe=190d4540e9) | Jul 20, 2021 |
| HP            | 250 G3                      | Notebook    | [b1a0952727](https://linux-hardware.org/?probe=b1a0952727) | Jul 19, 2021 |
| Lenovo        | Yoga 710-15IKB 80V5         | Convertible | [aed568d94c](https://linux-hardware.org/?probe=aed568d94c) | Jul 19, 2021 |
| HP            | ProBook 470 G0              | Notebook    | [0ac8121d51](https://linux-hardware.org/?probe=0ac8121d51) | Jul 14, 2021 |
| Lenovo        | ThinkPad E490 20N8005JMH    | Notebook    | [4ffde7a90a](https://linux-hardware.org/?probe=4ffde7a90a) | Jul 13, 2021 |
| Gigabyte      | GA-790XT-USB3               | Desktop     | [72f5d673d9](https://linux-hardware.org/?probe=72f5d673d9) | Jul 11, 2021 |
| PC Special... | N85_N87,HJ,HJ1,HK1          | Notebook    | [515b7e11d1](https://linux-hardware.org/?probe=515b7e11d1) | Jul 11, 2021 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [89a5013659](https://linux-hardware.org/?probe=89a5013659) | Jul 09, 2021 |
| Lenovo        | QIQY2                       | Notebook    | [7f8f82feb5](https://linux-hardware.org/?probe=7f8f82feb5) | Jul 07, 2021 |
| ASRock        | X370 Gaming X               | Desktop     | [df5a9e402e](https://linux-hardware.org/?probe=df5a9e402e) | Jul 07, 2021 |
| Dell          | Latitude D531               | Notebook    | [5a671e0dc0](https://linux-hardware.org/?probe=5a671e0dc0) | Jul 06, 2021 |
| Dell          | Latitude D531               | Notebook    | [bc3e80d306](https://linux-hardware.org/?probe=bc3e80d306) | Jul 06, 2021 |
| ASUSTek       | X540UA                      | Notebook    | [b9169c0ae3](https://linux-hardware.org/?probe=b9169c0ae3) | Jul 05, 2021 |
| Gigabyte      | P35-DS3                     | Desktop     | [1756b98ff7](https://linux-hardware.org/?probe=1756b98ff7) | Jul 04, 2021 |
| HP            | Laptop 15-bs1xx             | Notebook    | [f57bd1d1d8](https://linux-hardware.org/?probe=f57bd1d1d8) | Jul 04, 2021 |
| ASRock        | B450 Gaming K4              | Desktop     | [ed31fd442f](https://linux-hardware.org/?probe=ed31fd442f) | Jul 01, 2021 |
| ASRock        | B450 Gaming K4              | Desktop     | [479f6c752d](https://linux-hardware.org/?probe=479f6c752d) | Jul 01, 2021 |
| Gigabyte      | Z68XP-UD3P                  | Desktop     | [259e2a4ac0](https://linux-hardware.org/?probe=259e2a4ac0) | Jun 24, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [03f12de5a1](https://linux-hardware.org/?probe=03f12de5a1) | Jun 17, 2021 |
| HP            | 339A                        | Desktop     | [88af8ec05f](https://linux-hardware.org/?probe=88af8ec05f) | Jun 16, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [22c9d6c7de](https://linux-hardware.org/?probe=22c9d6c7de) | Jun 16, 2021 |
| Dell          | Latitude 7400               | Notebook    | [c58ebb3bf8](https://linux-hardware.org/?probe=c58ebb3bf8) | Jun 15, 2021 |
| HP            | Notebook                    | Notebook    | [611efdde0d](https://linux-hardware.org/?probe=611efdde0d) | Jun 15, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [8d612e77f2](https://linux-hardware.org/?probe=8d612e77f2) | Jun 14, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [7a4b730903](https://linux-hardware.org/?probe=7a4b730903) | Jun 13, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [2989252679](https://linux-hardware.org/?probe=2989252679) | Jun 12, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [128de02660](https://linux-hardware.org/?probe=128de02660) | Jun 12, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [e8a90de6cd](https://linux-hardware.org/?probe=e8a90de6cd) | Jun 12, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [676f8cfa11](https://linux-hardware.org/?probe=676f8cfa11) | Jun 12, 2021 |
| Sony          | VGN-FW510F                  | Notebook    | [88362a4659](https://linux-hardware.org/?probe=88362a4659) | Jun 10, 2021 |
| Sony          | VGN-FW510F                  | Notebook    | [d87f3ea107](https://linux-hardware.org/?probe=d87f3ea107) | Jun 10, 2021 |
| HP            | Compaq 6910p                | Notebook    | [5b4d256824](https://linux-hardware.org/?probe=5b4d256824) | Jun 10, 2021 |
| Dell          | Inspiron 5559               | Notebook    | [356b7fd3c6](https://linux-hardware.org/?probe=356b7fd3c6) | Jun 09, 2021 |
| ASUSTek       | N550JV                      | Notebook    | [7973dc9123](https://linux-hardware.org/?probe=7973dc9123) | Jun 08, 2021 |
| MSI           | H97 GAMING 3                | Desktop     | [831ff65864](https://linux-hardware.org/?probe=831ff65864) | Jun 07, 2021 |
| Dell          | 0Y7WYT A00                  | Desktop     | [e7b9652dbd](https://linux-hardware.org/?probe=e7b9652dbd) | Jun 07, 2021 |
| MSI           | H97 GAMING 3                | Desktop     | [33dcfeee7b](https://linux-hardware.org/?probe=33dcfeee7b) | Jun 07, 2021 |
| PLAISIO CO... | TURBO-X                     | Notebook    | [44f5d57c9d](https://linux-hardware.org/?probe=44f5d57c9d) | Jun 06, 2021 |
| PLAISIO CO... | TURBO-X                     | Notebook    | [47473943ab](https://linux-hardware.org/?probe=47473943ab) | Jun 06, 2021 |
| HP            | 304Bh                       | Desktop     | [4f331fec6f](https://linux-hardware.org/?probe=4f331fec6f) | Jun 04, 2021 |
| HP            | 304Bh                       | Desktop     | [a41a097984](https://linux-hardware.org/?probe=a41a097984) | Jun 04, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [ef4e2ca66f](https://linux-hardware.org/?probe=ef4e2ca66f) | Jun 03, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [2ff583b918](https://linux-hardware.org/?probe=2ff583b918) | Jun 02, 2021 |
| Gigabyte      | GA-MA785GT-UD3H             | Desktop     | [6018f18645](https://linux-hardware.org/?probe=6018f18645) | Jun 02, 2021 |
| Gigabyte      | GA-MA785GT-UD3H             | Desktop     | [03b8f35b44](https://linux-hardware.org/?probe=03b8f35b44) | Jun 02, 2021 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [5c26b20836](https://linux-hardware.org/?probe=5c26b20836) | Jun 01, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [b7f26cced7](https://linux-hardware.org/?probe=b7f26cced7) | Jun 01, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [36f36a1183](https://linux-hardware.org/?probe=36f36a1183) | Jun 01, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [bd16a61719](https://linux-hardware.org/?probe=bd16a61719) | May 31, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [da0e32387a](https://linux-hardware.org/?probe=da0e32387a) | May 31, 2021 |
| MSI           | B365M PRO-VH                | Desktop     | [9a3529c8ae](https://linux-hardware.org/?probe=9a3529c8ae) | May 29, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [e5a1aba629](https://linux-hardware.org/?probe=e5a1aba629) | May 26, 2021 |
| Fujitsu Si... | LIFEBOOK S7220              | Notebook    | [b9c73baf1d](https://linux-hardware.org/?probe=b9c73baf1d) | May 25, 2021 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [dd9596a6b0](https://linux-hardware.org/?probe=dd9596a6b0) | May 25, 2021 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [79e354be47](https://linux-hardware.org/?probe=79e354be47) | May 24, 2021 |
| ASUSTek       | A8V Deluxe                  | Desktop     | [e739f2f0ba](https://linux-hardware.org/?probe=e739f2f0ba) | May 24, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [91cf490677](https://linux-hardware.org/?probe=91cf490677) | May 24, 2021 |
| Toshiba       | Satellite A200              | Notebook    | [455915e23a](https://linux-hardware.org/?probe=455915e23a) | May 21, 2021 |
| HP            | G62                         | Notebook    | [72f8505e51](https://linux-hardware.org/?probe=72f8505e51) | May 20, 2021 |
| MSI           | B350M GAMING PRO            | Desktop     | [c04e6666e7](https://linux-hardware.org/?probe=c04e6666e7) | May 20, 2021 |
| Lenovo        | ThinkPad T440p 20AWS4PN0... | Notebook    | [f8b2c84bc1](https://linux-hardware.org/?probe=f8b2c84bc1) | May 19, 2021 |
| ASRock        | Z370 Professional Gaming... | Desktop     | [2c915c81d9](https://linux-hardware.org/?probe=2c915c81d9) | May 18, 2021 |
| HP            | Pavilion Laptop 13-an1xx... | Notebook    | [ead418c0a3](https://linux-hardware.org/?probe=ead418c0a3) | May 17, 2021 |
| HP            | Pavilion Laptop 13-an1xx... | Notebook    | [8312f6899d](https://linux-hardware.org/?probe=8312f6899d) | May 17, 2021 |
| HP            | 84EE 1100                   | All in one  | [df07e6aab4](https://linux-hardware.org/?probe=df07e6aab4) | May 17, 2021 |
| Dell          | Precision 3551              | Notebook    | [a080388baa](https://linux-hardware.org/?probe=a080388baa) | May 16, 2021 |
| Dell          | Precision 3551              | Notebook    | [f9f9852b96](https://linux-hardware.org/?probe=f9f9852b96) | May 16, 2021 |
| ASUSTek       | Z170-K                      | Desktop     | [8f3fc4eeda](https://linux-hardware.org/?probe=8f3fc4eeda) | May 15, 2021 |
| HP            | Unknown                     | Notebook    | [554d7cd528](https://linux-hardware.org/?probe=554d7cd528) | May 14, 2021 |
| Dell          | Inspiron 3537               | Notebook    | [3038e4027b](https://linux-hardware.org/?probe=3038e4027b) | May 14, 2021 |
| HP            | Compaq 6735s                | Notebook    | [b3d6b7770a](https://linux-hardware.org/?probe=b3d6b7770a) | May 13, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [e6848fb30e](https://linux-hardware.org/?probe=e6848fb30e) | May 13, 2021 |
| Notebook      | W65_67SF                    | Notebook    | [342074c2e1](https://linux-hardware.org/?probe=342074c2e1) | May 13, 2021 |
| Notebook      | W65_67SF                    | Notebook    | [54aedd8090](https://linux-hardware.org/?probe=54aedd8090) | May 13, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [643481b28f](https://linux-hardware.org/?probe=643481b28f) | May 10, 2021 |
| ASUSTek       | H170 PRO GAMING             | Desktop     | [b1375145c3](https://linux-hardware.org/?probe=b1375145c3) | May 10, 2021 |
| MSI           | GF75 Thin 10SCSR            | Notebook    | [d88c558cda](https://linux-hardware.org/?probe=d88c558cda) | May 09, 2021 |
| ASUSTek       | P5LD2-Deluxe                | Desktop     | [46242d579f](https://linux-hardware.org/?probe=46242d579f) | May 09, 2021 |
| ASUSTek       | P5LD2-Deluxe                | Desktop     | [0b6b9eab78](https://linux-hardware.org/?probe=0b6b9eab78) | May 07, 2021 |
| Notebook      | W65_67SF                    | Notebook    | [89628bc0a5](https://linux-hardware.org/?probe=89628bc0a5) | May 07, 2021 |
| Sony          | SVE1513R1EB                 | Notebook    | [e87dd3a1c3](https://linux-hardware.org/?probe=e87dd3a1c3) | May 07, 2021 |
| ASRock        | 880GM-LE FX                 | Desktop     | [256c66503a](https://linux-hardware.org/?probe=256c66503a) | May 06, 2021 |
| ASUSTek       | P5LD2-Deluxe                | Desktop     | [70bb3aecd9](https://linux-hardware.org/?probe=70bb3aecd9) | May 05, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [0b34a1f92d](https://linux-hardware.org/?probe=0b34a1f92d) | May 04, 2021 |
| Lenovo        | B590 20208                  | Notebook    | [f483fd5a3b](https://linux-hardware.org/?probe=f483fd5a3b) | May 04, 2021 |
| HP            | Compaq 6735s                | Notebook    | [f50dd52975](https://linux-hardware.org/?probe=f50dd52975) | May 03, 2021 |
| Unknown       | Unknown                     | Notebook    | [6f9d6686f3](https://linux-hardware.org/?probe=6f9d6686f3) | May 03, 2021 |
| ASUSTek       | P5LD2-Deluxe                | Desktop     | [193ecc62cf](https://linux-hardware.org/?probe=193ecc62cf) | May 03, 2021 |
| QDI           | P4I865A                     | Desktop     | [a3df896b35](https://linux-hardware.org/?probe=a3df896b35) | May 03, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [ad00f41e81](https://linux-hardware.org/?probe=ad00f41e81) | May 02, 2021 |
| Toshiba       | NB100                       | Notebook    | [9540e0d0d5](https://linux-hardware.org/?probe=9540e0d0d5) | May 02, 2021 |
| HP            | G62                         | Notebook    | [327a8383cf](https://linux-hardware.org/?probe=327a8383cf) | Apr 30, 2021 |
| Dell          | Inspiron 5406 2n1           | Convertible | [7dbdf36326](https://linux-hardware.org/?probe=7dbdf36326) | Apr 30, 2021 |
| Dell          | Inspiron 5406 2n1           | Convertible | [abc02a4329](https://linux-hardware.org/?probe=abc02a4329) | Apr 30, 2021 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [34b91a88a8](https://linux-hardware.org/?probe=34b91a88a8) | Apr 28, 2021 |
| MSI           | MS-7235                     | Desktop     | [3d8c008ca3](https://linux-hardware.org/?probe=3d8c008ca3) | Apr 27, 2021 |
| Acer          | AO756                       | Notebook    | [f398615a01](https://linux-hardware.org/?probe=f398615a01) | Apr 22, 2021 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [eb3e5cf436](https://linux-hardware.org/?probe=eb3e5cf436) | Apr 22, 2021 |
| Lenovo        | ThinkPad T430 2349CV2       | Notebook    | [98063e03b9](https://linux-hardware.org/?probe=98063e03b9) | Apr 21, 2021 |
| HP            | 1494                        | Desktop     | [775b59a599](https://linux-hardware.org/?probe=775b59a599) | Apr 20, 2021 |
| MSI           | H81M PRO-VD                 | Desktop     | [4c7c9824db](https://linux-hardware.org/?probe=4c7c9824db) | Apr 19, 2021 |
| Dell          | G3 3590                     | Notebook    | [5fe47837ac](https://linux-hardware.org/?probe=5fe47837ac) | Apr 19, 2021 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [0a7e8b0fab](https://linux-hardware.org/?probe=0a7e8b0fab) | Apr 19, 2021 |
| Toshiba       | Satellite C850D-119         | Notebook    | [7c519e9719](https://linux-hardware.org/?probe=7c519e9719) | Apr 17, 2021 |
| Google        | Coral                       | Notebook    | [d0fef96a1b](https://linux-hardware.org/?probe=d0fef96a1b) | Apr 15, 2021 |
| Toshiba       | Satellite C55-A-1F5         | Notebook    | [d7b4bf2642](https://linux-hardware.org/?probe=d7b4bf2642) | Apr 15, 2021 |
| Toshiba       | Satellite C55-A-1F5         | Notebook    | [aa32e3693a](https://linux-hardware.org/?probe=aa32e3693a) | Apr 14, 2021 |
| MSI           | 970A SLI Krait Edition      | Desktop     | [8695142550](https://linux-hardware.org/?probe=8695142550) | Apr 13, 2021 |
| Acer          | Predator G3-571             | Notebook    | [2db50fb736](https://linux-hardware.org/?probe=2db50fb736) | Apr 12, 2021 |
| HP            | 255 G1                      | Notebook    | [0244337bdd](https://linux-hardware.org/?probe=0244337bdd) | Apr 12, 2021 |
| HP            | 255 G1                      | Notebook    | [df0d528c9c](https://linux-hardware.org/?probe=df0d528c9c) | Apr 12, 2021 |
| HP            | 255 G8 Notebook PC          | Notebook    | [fd8afa6f02](https://linux-hardware.org/?probe=fd8afa6f02) | Apr 11, 2021 |
| HP            | 255 G8 Notebook PC          | Notebook    | [166de8c643](https://linux-hardware.org/?probe=166de8c643) | Apr 11, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [fd3c6d01f7](https://linux-hardware.org/?probe=fd3c6d01f7) | Apr 11, 2021 |
| Gigabyte      | B550 VISION D               | Desktop     | [3246784665](https://linux-hardware.org/?probe=3246784665) | Apr 09, 2021 |
| Gigabyte      | P41T-D3                     | Desktop     | [2f9a494265](https://linux-hardware.org/?probe=2f9a494265) | Apr 09, 2021 |
| Hampoo        | Cherry Trail CR V200        | Notebook    | [fcbaa285ef](https://linux-hardware.org/?probe=fcbaa285ef) | Apr 07, 2021 |
| ASRock        | J3355B-ITX                  | Desktop     | [8f3bd77b70](https://linux-hardware.org/?probe=8f3bd77b70) | Apr 06, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [f1c3f62a55](https://linux-hardware.org/?probe=f1c3f62a55) | Apr 04, 2021 |
| MSI           | GF75 Thin 10SCSR            | Notebook    | [4c5b57df0f](https://linux-hardware.org/?probe=4c5b57df0f) | Apr 03, 2021 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [2d30481374](https://linux-hardware.org/?probe=2d30481374) | Apr 01, 2021 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [63df5a92c1](https://linux-hardware.org/?probe=63df5a92c1) | Apr 01, 2021 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [9312919fed](https://linux-hardware.org/?probe=9312919fed) | Apr 01, 2021 |
| Lenovo        | ThinkCentre M71e 3157H2U    | Desktop     | [6e0ad0f342](https://linux-hardware.org/?probe=6e0ad0f342) | Mar 31, 2021 |
| Acer          | Aspire A315-51              | Notebook    | [a6ad1251de](https://linux-hardware.org/?probe=a6ad1251de) | Mar 30, 2021 |
| Toshiba       | Satellite L500              | Notebook    | [d11d1f9916](https://linux-hardware.org/?probe=d11d1f9916) | Mar 28, 2021 |
| Quest         | GTN1408                     | Notebook    | [e0a15c69a8](https://linux-hardware.org/?probe=e0a15c69a8) | Mar 25, 2021 |
| ASUSTek       | X555QG                      | Notebook    | [9e2fba943d](https://linux-hardware.org/?probe=9e2fba943d) | Mar 25, 2021 |
| Gigabyte      | F2A88XM-HD3P                | Desktop     | [5bedab76df](https://linux-hardware.org/?probe=5bedab76df) | Mar 25, 2021 |
| Gigabyte      | B550 VISION D               | Desktop     | [5916c313e7](https://linux-hardware.org/?probe=5916c313e7) | Mar 25, 2021 |
| Gigabyte      | F2A88XM-HD3P                | Desktop     | [aab9ef0b36](https://linux-hardware.org/?probe=aab9ef0b36) | Mar 24, 2021 |
| Dell          | Latitude D530               | Notebook    | [bd67bc09cd](https://linux-hardware.org/?probe=bd67bc09cd) | Mar 22, 2021 |
| HP            | 0984h                       | Desktop     | [20a29fe8b0](https://linux-hardware.org/?probe=20a29fe8b0) | Mar 20, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [82fb28dfec](https://linux-hardware.org/?probe=82fb28dfec) | Mar 19, 2021 |
| ASUSTek       | X556UQK                     | Notebook    | [67d33fc829](https://linux-hardware.org/?probe=67d33fc829) | Mar 19, 2021 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [f579ddfcb8](https://linux-hardware.org/?probe=f579ddfcb8) | Mar 17, 2021 |
| HP            | 18E4                        | Desktop     | [b5eec7a501](https://linux-hardware.org/?probe=b5eec7a501) | Mar 17, 2021 |
| ASRock        | Z97 Extreme4                | Desktop     | [6378d46f22](https://linux-hardware.org/?probe=6378d46f22) | Mar 17, 2021 |
| ASUSTek       | N552VX                      | Notebook    | [79120776d5](https://linux-hardware.org/?probe=79120776d5) | Mar 14, 2021 |
| ASUSTek       | N552VX                      | Notebook    | [2bb101d8ca](https://linux-hardware.org/?probe=2bb101d8ca) | Mar 14, 2021 |
| MSI           | Z97-G45 GAMING              | Desktop     | [5843e7b038](https://linux-hardware.org/?probe=5843e7b038) | Mar 14, 2021 |
| MSI           | Z97-G45 GAMING              | Desktop     | [fc76eddc08](https://linux-hardware.org/?probe=fc76eddc08) | Mar 14, 2021 |
| HP            | G62                         | Notebook    | [f586fad981](https://linux-hardware.org/?probe=f586fad981) | Mar 14, 2021 |
| Gigabyte      | G31M-S2L                    | Desktop     | [9ff279ae01](https://linux-hardware.org/?probe=9ff279ae01) | Mar 11, 2021 |
| Teclast       | F15                         | Notebook    | [2a9e97f18c](https://linux-hardware.org/?probe=2a9e97f18c) | Mar 10, 2021 |
| HP            | Notebook                    | Notebook    | [26fdd1f108](https://linux-hardware.org/?probe=26fdd1f108) | Mar 09, 2021 |
| Gigabyte      | B75-D3V                     | Desktop     | [f4b8176eb4](https://linux-hardware.org/?probe=f4b8176eb4) | Mar 09, 2021 |
| Dell          | Latitude E7250              | Notebook    | [551399bf55](https://linux-hardware.org/?probe=551399bf55) | Mar 08, 2021 |
| Gigabyte      | G31M-S2L                    | Desktop     | [78933b8238](https://linux-hardware.org/?probe=78933b8238) | Mar 07, 2021 |
| Acer          | Aspire E5-771G              | Notebook    | [693347465d](https://linux-hardware.org/?probe=693347465d) | Mar 06, 2021 |
| Info Quest... | GTN1408                     | Notebook    | [571eedb776](https://linux-hardware.org/?probe=571eedb776) | Mar 03, 2021 |
| Toshiba       | NB100                       | Notebook    | [7876cca0bb](https://linux-hardware.org/?probe=7876cca0bb) | Mar 03, 2021 |
| MSI           | H81M PRO-VD                 | Desktop     | [efa82d3df7](https://linux-hardware.org/?probe=efa82d3df7) | Mar 02, 2021 |
| Dell          | Latitude E6400              | Notebook    | [ebe53e8b99](https://linux-hardware.org/?probe=ebe53e8b99) | Feb 28, 2021 |
| Dell          | Inspiron 5567               | Notebook    | [e2ede83088](https://linux-hardware.org/?probe=e2ede83088) | Feb 27, 2021 |
| Dell          | Inspiron 5567               | Notebook    | [951acd6af9](https://linux-hardware.org/?probe=951acd6af9) | Feb 27, 2021 |
| HP            | ProBook 430 G7              | Notebook    | [b4b70424b9](https://linux-hardware.org/?probe=b4b70424b9) | Feb 27, 2021 |
| Gigabyte      | 8I915PL-G                   | Desktop     | [e9ed9c7fdf](https://linux-hardware.org/?probe=e9ed9c7fdf) | Feb 27, 2021 |
| Notebook      | W54_W94_W955TU,-T,-C        | Notebook    | [1ecf28a1c8](https://linux-hardware.org/?probe=1ecf28a1c8) | Feb 27, 2021 |
| Notebook      | W54_W94_W955TU,-T,-C        | Notebook    | [cada48fb79](https://linux-hardware.org/?probe=cada48fb79) | Feb 27, 2021 |
| ASUSTek       | UX305CA                     | Notebook    | [65b536ca2f](https://linux-hardware.org/?probe=65b536ca2f) | Feb 26, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [c501aa1f72](https://linux-hardware.org/?probe=c501aa1f72) | Feb 26, 2021 |
| Gigabyte      | G31M-S2L                    | Desktop     | [c0301ac11d](https://linux-hardware.org/?probe=c0301ac11d) | Feb 26, 2021 |
| ASUSTek       | P6T                         | Desktop     | [c2d58a2c68](https://linux-hardware.org/?probe=c2d58a2c68) | Feb 25, 2021 |
| HP            | Pavilion dv6                | Notebook    | [ffde1aad10](https://linux-hardware.org/?probe=ffde1aad10) | Feb 25, 2021 |
| MSI           | MS-7176                     | Desktop     | [f04765b1b9](https://linux-hardware.org/?probe=f04765b1b9) | Feb 24, 2021 |
| MSI           | MS-7176                     | Desktop     | [760a593d35](https://linux-hardware.org/?probe=760a593d35) | Feb 24, 2021 |
| Dell          | Latitude E6400              | Notebook    | [256426a815](https://linux-hardware.org/?probe=256426a815) | Feb 22, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [ec035af0d0](https://linux-hardware.org/?probe=ec035af0d0) | Feb 21, 2021 |
| Gigabyte      | G31M-S2L                    | Desktop     | [563f422327](https://linux-hardware.org/?probe=563f422327) | Feb 21, 2021 |
| Gigabyte      | Z97X-UD5H                   | Desktop     | [74869ab078](https://linux-hardware.org/?probe=74869ab078) | Feb 21, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [e6ea03de75](https://linux-hardware.org/?probe=e6ea03de75) | Feb 21, 2021 |
| Gigabyte      | G31M-S2L                    | Desktop     | [38e7b43029](https://linux-hardware.org/?probe=38e7b43029) | Feb 21, 2021 |
| Gigabyte      | G31M-S2L                    | Desktop     | [aac0643552](https://linux-hardware.org/?probe=aac0643552) | Feb 21, 2021 |
| HP            | Pavilion AB7                | Notebook    | [410cf90e15](https://linux-hardware.org/?probe=410cf90e15) | Feb 20, 2021 |
| Intel         | DP55WB AAE64798-204         | Desktop     | [6e9ac2a13d](https://linux-hardware.org/?probe=6e9ac2a13d) | Feb 20, 2021 |
| Fujitsu       | LIFEBOOK NH570              | Notebook    | [9b2fc1e55f](https://linux-hardware.org/?probe=9b2fc1e55f) | Feb 19, 2021 |
| ASUSTek       | P8P67 LE                    | Desktop     | [492632cd6f](https://linux-hardware.org/?probe=492632cd6f) | Feb 19, 2021 |
| ASUSTek       | P8P67 LE                    | Desktop     | [2dae363129](https://linux-hardware.org/?probe=2dae363129) | Feb 19, 2021 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [6e91e6e551](https://linux-hardware.org/?probe=6e91e6e551) | Feb 18, 2021 |
| ABIT          | FP-IN9 SLI                  | Desktop     | [91f5f66c7c](https://linux-hardware.org/?probe=91f5f66c7c) | Feb 17, 2021 |
| HP            | Laptop 15-db0xxx            | Notebook    | [9e831f773a](https://linux-hardware.org/?probe=9e831f773a) | Feb 17, 2021 |
| Dell          | Studio 1557                 | Notebook    | [bf361a7ed3](https://linux-hardware.org/?probe=bf361a7ed3) | Feb 16, 2021 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [209ecb3837](https://linux-hardware.org/?probe=209ecb3837) | Feb 16, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [38a0ac2efa](https://linux-hardware.org/?probe=38a0ac2efa) | Feb 16, 2021 |
| Gigabyte      | G31M-S2L                    | Desktop     | [6c898a20f1](https://linux-hardware.org/?probe=6c898a20f1) | Feb 15, 2021 |
| Dell          | Precision M6400             | Notebook    | [2bd1a24330](https://linux-hardware.org/?probe=2bd1a24330) | Feb 14, 2021 |
| ASUSTek       | Rampage III GENE            | Desktop     | [3994b32fbb](https://linux-hardware.org/?probe=3994b32fbb) | Feb 14, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [e688396a21](https://linux-hardware.org/?probe=e688396a21) | Feb 14, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [696129adca](https://linux-hardware.org/?probe=696129adca) | Feb 14, 2021 |
| Gigabyte      | H61MA-D2V                   | Desktop     | [35291823d8](https://linux-hardware.org/?probe=35291823d8) | Feb 14, 2021 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [de94ccbf1a](https://linux-hardware.org/?probe=de94ccbf1a) | Feb 14, 2021 |
| ASUSTek       | P8H77-V                     | Desktop     | [71b1c108c4](https://linux-hardware.org/?probe=71b1c108c4) | Feb 14, 2021 |
| ASRock        | B450 Gaming K4              | Desktop     | [2dd140ff3e](https://linux-hardware.org/?probe=2dd140ff3e) | Feb 14, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [dfc223f07c](https://linux-hardware.org/?probe=dfc223f07c) | Feb 14, 2021 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [e0ef54344d](https://linux-hardware.org/?probe=e0ef54344d) | Feb 14, 2021 |
| HP            | ProBook 450 G5              | Notebook    | [3e6fa8f362](https://linux-hardware.org/?probe=3e6fa8f362) | Feb 13, 2021 |
| HP            | Pavilion dv6000 (RR398EA... | Notebook    | [2b5732689b](https://linux-hardware.org/?probe=2b5732689b) | Feb 13, 2021 |
| HP            | Pavilion dv6000 (RR398EA... | Notebook    | [0005b66219](https://linux-hardware.org/?probe=0005b66219) | Feb 13, 2021 |
| ASUSTek       | P5Q                         | Desktop     | [a9bc15b309](https://linux-hardware.org/?probe=a9bc15b309) | Feb 13, 2021 |
| Teclast       | F15                         | Notebook    | [1c7d49b0b0](https://linux-hardware.org/?probe=1c7d49b0b0) | Feb 13, 2021 |
| ASUSTek       | P7P55D-E DELUXE             | Desktop     | [b0857a93ff](https://linux-hardware.org/?probe=b0857a93ff) | Feb 13, 2021 |
| Gigabyte      | GA-MA790XT-UD4P             | Desktop     | [0ebedefc78](https://linux-hardware.org/?probe=0ebedefc78) | Feb 13, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [654141e59d](https://linux-hardware.org/?probe=654141e59d) | Feb 13, 2021 |
| Fujitsu Si... | AMILO Li 1818               | Notebook    | [68c7aa1fa1](https://linux-hardware.org/?probe=68c7aa1fa1) | Feb 09, 2021 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [2ed0ae9569](https://linux-hardware.org/?probe=2ed0ae9569) | Feb 09, 2021 |
| Gigabyte      | H77M-D3H                    | Desktop     | [0a56b88fc8](https://linux-hardware.org/?probe=0a56b88fc8) | Feb 08, 2021 |
| Gigabyte      | B365M DS3H                  | Desktop     | [6b7db83192](https://linux-hardware.org/?probe=6b7db83192) | Feb 06, 2021 |
| Lenovo        | G510 20238                  | Notebook    | [0022cd41e5](https://linux-hardware.org/?probe=0022cd41e5) | Feb 06, 2021 |
| Gigabyte      | B365M DS3H                  | Desktop     | [543b5a7398](https://linux-hardware.org/?probe=543b5a7398) | Feb 06, 2021 |
| ASUSTek       | Z97-A                       | Desktop     | [fc8c462cc7](https://linux-hardware.org/?probe=fc8c462cc7) | Feb 04, 2021 |
| Lenovo        | Y50-70 20378                | Notebook    | [a95bc37d1f](https://linux-hardware.org/?probe=a95bc37d1f) | Feb 03, 2021 |
| Gigabyte      | GA-790XT-USB3               | Desktop     | [d14e71b6b4](https://linux-hardware.org/?probe=d14e71b6b4) | Feb 03, 2021 |
| HP            | G62                         | Notebook    | [273bf04457](https://linux-hardware.org/?probe=273bf04457) | Feb 03, 2021 |
| HP            | G62                         | Notebook    | [a74ecdb45c](https://linux-hardware.org/?probe=a74ecdb45c) | Feb 03, 2021 |
| HP            | 1494                        | Desktop     | [d3fbad0c50](https://linux-hardware.org/?probe=d3fbad0c50) | Feb 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [4f64a771ff](https://linux-hardware.org/?probe=4f64a771ff) | Feb 01, 2021 |
| Foxconn       | P43A01                      | Desktop     | [6ebcadfb23](https://linux-hardware.org/?probe=6ebcadfb23) | Jan 31, 2021 |
| HP            | Pavilion Sleekbook 15       | Notebook    | [bf72f555cb](https://linux-hardware.org/?probe=bf72f555cb) | Jan 31, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [4d8f4f66c7](https://linux-hardware.org/?probe=4d8f4f66c7) | Jan 31, 2021 |
| Acer          | Aspire A517-51G             | Notebook    | [7b7f7244e6](https://linux-hardware.org/?probe=7b7f7244e6) | Jan 28, 2021 |
| Lenovo        | G510 20238                  | Notebook    | [c53a37fb5a](https://linux-hardware.org/?probe=c53a37fb5a) | Jan 28, 2021 |
| ASUSTek       | Rampage III GENE            | Desktop     | [32605971fb](https://linux-hardware.org/?probe=32605971fb) | Jan 28, 2021 |
| ASUSTek       | Rampage III GENE            | Desktop     | [1ac6133a40](https://linux-hardware.org/?probe=1ac6133a40) | Jan 28, 2021 |
| Dell          | 06FW8P A01                  | Desktop     | [392c18a8d2](https://linux-hardware.org/?probe=392c18a8d2) | Jan 28, 2021 |
| HP            | Unknown                     | Notebook    | [437cd35d62](https://linux-hardware.org/?probe=437cd35d62) | Jan 28, 2021 |
| Gigabyte      | G41M-Combo                  | Desktop     | [a85f6c4759](https://linux-hardware.org/?probe=a85f6c4759) | Jan 27, 2021 |
| IBM           | ThinkPad T41 2373271        | Notebook    | [71daf2c5b4](https://linux-hardware.org/?probe=71daf2c5b4) | Jan 26, 2021 |
| Fujitsu       | AMILO Pi 3560               | Notebook    | [a54f523eae](https://linux-hardware.org/?probe=a54f523eae) | Jan 26, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [54bfedf54f](https://linux-hardware.org/?probe=54bfedf54f) | Jan 24, 2021 |
| Lenovo        | G40-30 80FY                 | Notebook    | [2ade08670a](https://linux-hardware.org/?probe=2ade08670a) | Jan 22, 2021 |
| Dell          | 0DFRFW A01                  | Desktop     | [7bcce8c99f](https://linux-hardware.org/?probe=7bcce8c99f) | Jan 22, 2021 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [ef38db344e](https://linux-hardware.org/?probe=ef38db344e) | Jan 20, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [0c61498134](https://linux-hardware.org/?probe=0c61498134) | Jan 19, 2021 |
| HP            | Unknown                     | Notebook    | [db1b52d959](https://linux-hardware.org/?probe=db1b52d959) | Jan 19, 2021 |
| Toshiba       | Satellite L50-B             | Notebook    | [6e7fe8b488](https://linux-hardware.org/?probe=6e7fe8b488) | Jan 18, 2021 |
| Toshiba       | Satellite L50-B             | Notebook    | [df23913572](https://linux-hardware.org/?probe=df23913572) | Jan 18, 2021 |
| HP            | 550                         | Notebook    | [384b3f65ed](https://linux-hardware.org/?probe=384b3f65ed) | Jan 18, 2021 |
| Lenovo        | ThinkCentre M55 880894G     | Desktop     | [3b766a7c24](https://linux-hardware.org/?probe=3b766a7c24) | Jan 17, 2021 |
| Acer          | Aspire 1410                 | Notebook    | [c7045484b1](https://linux-hardware.org/?probe=c7045484b1) | Jan 16, 2021 |
| Sony          | VPCS11X9E                   | Notebook    | [279fb61afa](https://linux-hardware.org/?probe=279fb61afa) | Jan 16, 2021 |
| Acer          | Aspire E1-571G              | Notebook    | [051b3d5b1b](https://linux-hardware.org/?probe=051b3d5b1b) | Jan 16, 2021 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [ca2c414b09](https://linux-hardware.org/?probe=ca2c414b09) | Jan 13, 2021 |
| HP            | 3648h                       | Desktop     | [21e48412d9](https://linux-hardware.org/?probe=21e48412d9) | Jan 12, 2021 |
| Lenovo        | IdeaPad 320-17IKB 81BJ      | Notebook    | [a137e1b57f](https://linux-hardware.org/?probe=a137e1b57f) | Jan 11, 2021 |
| Gigabyte      | GA-790XT-USB3               | Desktop     | [637d6c6ea6](https://linux-hardware.org/?probe=637d6c6ea6) | Jan 11, 2021 |
| Medion        | P6612                       | Notebook    | [5e83afdaae](https://linux-hardware.org/?probe=5e83afdaae) | Jan 11, 2021 |
| Dell          | G3 3579                     | Notebook    | [d48d0d6f85](https://linux-hardware.org/?probe=d48d0d6f85) | Jan 11, 2021 |
| HP            | 550                         | Notebook    | [10da4607b5](https://linux-hardware.org/?probe=10da4607b5) | Jan 11, 2021 |
| Lenovo        | ThinkPad T430 2347AG4       | Notebook    | [01c5b6209d](https://linux-hardware.org/?probe=01c5b6209d) | Jan 11, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [9a71b52057](https://linux-hardware.org/?probe=9a71b52057) | Jan 11, 2021 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [6164e26717](https://linux-hardware.org/?probe=6164e26717) | Jan 09, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [a2113ca536](https://linux-hardware.org/?probe=a2113ca536) | Jan 08, 2021 |
| ASRock        | A320M Pro4                  | Desktop     | [df605a19b9](https://linux-hardware.org/?probe=df605a19b9) | Jan 07, 2021 |
| Dell          | Precision 3551              | Notebook    | [1f3d433e7b](https://linux-hardware.org/?probe=1f3d433e7b) | Jan 07, 2021 |
| Dell          | Precision 3551              | Notebook    | [b9869afb9a](https://linux-hardware.org/?probe=b9869afb9a) | Jan 07, 2021 |
| HP            | ENVY Laptop 13-ad0xx        | Notebook    | [2040f17b4e](https://linux-hardware.org/?probe=2040f17b4e) | Jan 07, 2021 |
| HP            | ENVY Laptop 13-ad0xx        | Notebook    | [7758717ed0](https://linux-hardware.org/?probe=7758717ed0) | Jan 07, 2021 |
| Unknown       | Unknown                     | Notebook    | [394c90d235](https://linux-hardware.org/?probe=394c90d235) | Jan 06, 2021 |
| ASRock        | 970M Pro3                   | Desktop     | [7e9042951e](https://linux-hardware.org/?probe=7e9042951e) | Jan 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [7fa2f92090](https://linux-hardware.org/?probe=7fa2f92090) | Jan 05, 2021 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [d6f76d5ca0](https://linux-hardware.org/?probe=d6f76d5ca0) | Jan 05, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [1bf71bd97d](https://linux-hardware.org/?probe=1bf71bd97d) | Jan 04, 2021 |
| ASRock        | J3455-ITX                   | Desktop     | [45519ff99d](https://linux-hardware.org/?probe=45519ff99d) | Jan 04, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [8708f0aa1a](https://linux-hardware.org/?probe=8708f0aa1a) | Jan 04, 2021 |
| ASUSTek       | P5E3 Deluxe                 | Desktop     | [6f3605f8a7](https://linux-hardware.org/?probe=6f3605f8a7) | Jan 04, 2021 |
| ASUSTek       | P5E3 Deluxe                 | Desktop     | [5939021d4c](https://linux-hardware.org/?probe=5939021d4c) | Jan 03, 2021 |
| Lenovo        | IdeaPad 720S-13IKB 81BV     | Notebook    | [010507185c](https://linux-hardware.org/?probe=010507185c) | Jan 03, 2021 |
| HP            | G62                         | Notebook    | [26fedb2989](https://linux-hardware.org/?probe=26fedb2989) | Jan 03, 2021 |
| Sony          | VGN-CR11S_W                 | Notebook    | [e7b02a15dc](https://linux-hardware.org/?probe=e7b02a15dc) | Dec 30, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d8fb43bcba](https://linux-hardware.org/?probe=d8fb43bcba) | Dec 29, 2020 |
| Fujitsu Si... | AMILO Pi 2530               | Notebook    | [33e1b7b962](https://linux-hardware.org/?probe=33e1b7b962) | Dec 28, 2020 |
| Fujitsu Si... | AMILO Pi 2530               | Notebook    | [7463092751](https://linux-hardware.org/?probe=7463092751) | Dec 28, 2020 |
| ASRock        | J3455B-ITX                  | Desktop     | [188b19422f](https://linux-hardware.org/?probe=188b19422f) | Dec 28, 2020 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | Notebook    | [cb411462ef](https://linux-hardware.org/?probe=cb411462ef) | Dec 28, 2020 |
| Acer          | Aspire 9410                 | Notebook    | [502b2847a6](https://linux-hardware.org/?probe=502b2847a6) | Dec 28, 2020 |
| Acer          | Aspire 9410                 | Notebook    | [29cadd906c](https://linux-hardware.org/?probe=29cadd906c) | Dec 28, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [4301611dfb](https://linux-hardware.org/?probe=4301611dfb) | Dec 28, 2020 |
| Dell          | Inspiron 5567               | Notebook    | [4bed00686e](https://linux-hardware.org/?probe=4bed00686e) | Dec 27, 2020 |
| Lenovo        | 3000 G530 444624G           | Notebook    | [34e6d98329](https://linux-hardware.org/?probe=34e6d98329) | Dec 27, 2020 |
| Dell          | 0WR7PY A03                  | Desktop     | [e9d1c14615](https://linux-hardware.org/?probe=e9d1c14615) | Dec 27, 2020 |
| Insyde        | CherryTrail                 | Notebook    | [3d9eb0babd](https://linux-hardware.org/?probe=3d9eb0babd) | Dec 26, 2020 |
| HP            | Pavilion dv7                | Notebook    | [cc13d41ddd](https://linux-hardware.org/?probe=cc13d41ddd) | Dec 25, 2020 |
| Dell          | XPS 15 7590                 | Notebook    | [2974690eda](https://linux-hardware.org/?probe=2974690eda) | Dec 25, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [752fb8d0c7](https://linux-hardware.org/?probe=752fb8d0c7) | Dec 25, 2020 |
| ASRock        | J3455-ITX                   | Desktop     | [e530bd21e8](https://linux-hardware.org/?probe=e530bd21e8) | Dec 23, 2020 |
| HP            | Laptop 15-db0xxx            | Notebook    | [08f4092908](https://linux-hardware.org/?probe=08f4092908) | Dec 21, 2020 |
| Lenovo        | ThinkPad X200 7458Y28       | Notebook    | [508111c39d](https://linux-hardware.org/?probe=508111c39d) | Dec 20, 2020 |
| HP            | Laptop 15-db1xxx            | Notebook    | [c7807b04ff](https://linux-hardware.org/?probe=c7807b04ff) | Dec 20, 2020 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [71036e26bf](https://linux-hardware.org/?probe=71036e26bf) | Dec 19, 2020 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [c58e872c12](https://linux-hardware.org/?probe=c58e872c12) | Dec 19, 2020 |
| Lenovo        | IdeaPad S210 Touch 20257    | Notebook    | [faacb1a39b](https://linux-hardware.org/?probe=faacb1a39b) | Dec 19, 2020 |
| Lenovo        | ThinkPad X220 4291W3B       | Notebook    | [0cb7ed54d1](https://linux-hardware.org/?probe=0cb7ed54d1) | Dec 19, 2020 |
| Lenovo        | IdeaPad Y560                | Notebook    | [c5c8b0a320](https://linux-hardware.org/?probe=c5c8b0a320) | Dec 19, 2020 |
| Lenovo        | IdeaPad Y560                | Notebook    | [1a68fc4e19](https://linux-hardware.org/?probe=1a68fc4e19) | Dec 19, 2020 |
| Toshiba       | NB100                       | Notebook    | [01daa00e87](https://linux-hardware.org/?probe=01daa00e87) | Dec 19, 2020 |
| Dell          | Latitude D520               | Notebook    | [7f5d3e9a40](https://linux-hardware.org/?probe=7f5d3e9a40) | Dec 19, 2020 |
| Lenovo        | 3000 G530 444624G           | Notebook    | [fb187878c5](https://linux-hardware.org/?probe=fb187878c5) | Dec 16, 2020 |
| ASRock        | B450 Gaming K4              | Desktop     | [6fcb38f3dc](https://linux-hardware.org/?probe=6fcb38f3dc) | Dec 15, 2020 |
| ASUSTek       | X550CC                      | Notebook    | [d8723f48ef](https://linux-hardware.org/?probe=d8723f48ef) | Dec 15, 2020 |
| Sony          | VPCCB2S1E                   | Notebook    | [dadaeb0257](https://linux-hardware.org/?probe=dadaeb0257) | Dec 14, 2020 |
| Sony          | VPCCB2S1E                   | Notebook    | [b08942a95c](https://linux-hardware.org/?probe=b08942a95c) | Dec 14, 2020 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [de42fe0cb3](https://linux-hardware.org/?probe=de42fe0cb3) | Dec 14, 2020 |
| ECS           | GF7050VT-M5                 | Desktop     | [c29ca24015](https://linux-hardware.org/?probe=c29ca24015) | Dec 12, 2020 |
| ECS           | GF7050VT-M5                 | Desktop     | [657f63e3cb](https://linux-hardware.org/?probe=657f63e3cb) | Dec 12, 2020 |
| Lenovo        | G50-80 80L0                 | Notebook    | [951a5a280f](https://linux-hardware.org/?probe=951a5a280f) | Dec 11, 2020 |
| ASUSTek       | M4N78 PRO                   | Desktop     | [f25cf52f68](https://linux-hardware.org/?probe=f25cf52f68) | Dec 11, 2020 |
| Sony          | VGN-CR11S_W                 | Notebook    | [9f07e6181c](https://linux-hardware.org/?probe=9f07e6181c) | Dec 10, 2020 |
| Gigabyte      | G41M-Combo                  | Desktop     | [5866279b5d](https://linux-hardware.org/?probe=5866279b5d) | Dec 10, 2020 |
| HP            | OMEN by Laptop              | Notebook    | [ae88c5398f](https://linux-hardware.org/?probe=ae88c5398f) | Dec 10, 2020 |
| HP            | ENVY x360 Convertible 15... | Convertible | [763ee2bb89](https://linux-hardware.org/?probe=763ee2bb89) | Dec 09, 2020 |
| Gigabyte      | 8IPE1000                    | Desktop     | [af54151e80](https://linux-hardware.org/?probe=af54151e80) | Dec 09, 2020 |
| HP            | 158B                        | Desktop     | [3a87a2e567](https://linux-hardware.org/?probe=3a87a2e567) | Dec 09, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [b7becb585e](https://linux-hardware.org/?probe=b7becb585e) | Dec 08, 2020 |
| Intel         | CAPELL VALLEY CRB           | Notebook    | [59d2069d40](https://linux-hardware.org/?probe=59d2069d40) | Dec 07, 2020 |
| Intel         | CAPELL VALLEY CRB           | Notebook    | [ce350750e3](https://linux-hardware.org/?probe=ce350750e3) | Dec 05, 2020 |
| Toshiba       | Satellite C850D-119         | Notebook    | [4a0f2ef22e](https://linux-hardware.org/?probe=4a0f2ef22e) | Dec 05, 2020 |
| HP            | Pavilion dv7                | Notebook    | [ea3cf2d030](https://linux-hardware.org/?probe=ea3cf2d030) | Dec 04, 2020 |
| Lenovo        | G70-35 80Q5                 | Notebook    | [455f011c08](https://linux-hardware.org/?probe=455f011c08) | Dec 03, 2020 |
| ASUSTek       | X556UQK                     | Notebook    | [529e0c244d](https://linux-hardware.org/?probe=529e0c244d) | Dec 02, 2020 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [584da25316](https://linux-hardware.org/?probe=584da25316) | Dec 02, 2020 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [24658bc507](https://linux-hardware.org/?probe=24658bc507) | Dec 01, 2020 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | Notebook    | [09b180815e](https://linux-hardware.org/?probe=09b180815e) | Dec 01, 2020 |
| Fujitsu       | CELSIUS H710                | Notebook    | [03fea3325c](https://linux-hardware.org/?probe=03fea3325c) | Dec 01, 2020 |
| Lenovo        | G70-35 80Q5                 | Notebook    | [23ee81bd5e](https://linux-hardware.org/?probe=23ee81bd5e) | Dec 01, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [193e7f8bf4](https://linux-hardware.org/?probe=193e7f8bf4) | Dec 01, 2020 |
| Toshiba       | NB100                       | Notebook    | [73e92718a9](https://linux-hardware.org/?probe=73e92718a9) | Dec 01, 2020 |
| HP            | Unknown                     | Notebook    | [6ecc666f9f](https://linux-hardware.org/?probe=6ecc666f9f) | Dec 01, 2020 |
| Sony          | VPCW12J1E                   | Notebook    | [7f54f3a6f0](https://linux-hardware.org/?probe=7f54f3a6f0) | Dec 01, 2020 |
| Gigabyte      | F2A78M-DS2                  | Desktop     | [32f996990f](https://linux-hardware.org/?probe=32f996990f) | Dec 01, 2020 |
| Fujitsu       | CELSIUS H710                | Notebook    | [1214e804ff](https://linux-hardware.org/?probe=1214e804ff) | Dec 01, 2020 |
| Lenovo        | 36EE SDK0J40700 WIN 3258... | Desktop     | [a56d5a585c](https://linux-hardware.org/?probe=a56d5a585c) | Nov 30, 2020 |
| Lenovo        | 36EE SDK0J40700 WIN 3258... | Desktop     | [2810240912](https://linux-hardware.org/?probe=2810240912) | Nov 30, 2020 |
| Acer          | Predator G5-793             | Notebook    | [ae170a3127](https://linux-hardware.org/?probe=ae170a3127) | Nov 30, 2020 |
| HP            | 1998                        | Desktop     | [33515aa889](https://linux-hardware.org/?probe=33515aa889) | Nov 29, 2020 |
| ASUSTek       | P5QL-ASUS-SE                | Desktop     | [e2e1a617e3](https://linux-hardware.org/?probe=e2e1a617e3) | Nov 29, 2020 |
| Acer          | Aspire 5738                 | Notebook    | [c34c324fc5](https://linux-hardware.org/?probe=c34c324fc5) | Nov 28, 2020 |
| HP            | EliteBook 850 G5            | Notebook    | [e261ebbf0e](https://linux-hardware.org/?probe=e261ebbf0e) | Nov 26, 2020 |
| ASUSTek       | M2A74-AM SE                 | Desktop     | [c95d6e0e82](https://linux-hardware.org/?probe=c95d6e0e82) | Nov 24, 2020 |
| Toshiba       | Satellite P500              | Notebook    | [25e5577463](https://linux-hardware.org/?probe=25e5577463) | Nov 24, 2020 |
| Dell          | Inspiron 5570               | Notebook    | [2074f71e04](https://linux-hardware.org/?probe=2074f71e04) | Nov 24, 2020 |
| Dell          | Inspiron 3537               | Notebook    | [0bc23c46e1](https://linux-hardware.org/?probe=0bc23c46e1) | Nov 23, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Greece/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Ubuntu 20.04      | 170       | 14.58%  |
| Ubuntu 18.04      | 123       | 10.55%  |
| Ubuntu 22.04      | 38        | 3.26%   |
| OpenMandriva 4.2  | 36        | 3.09%   |
| KDE neon 20.04    | 26        | 2.23%   |
| Arch Rolling      | 23        | 1.97%   |
| OpenMandriva 4.3  | 22        | 1.89%   |
| Ubuntu MATE 20.04 | 21        | 1.8%    |
| Linux Mint 19.3   | 20        | 1.72%   |
| Zorin 16          | 19        | 1.63%   |
| Ubuntu 19.10      | 19        | 1.63%   |
| Debian 11         | 18        | 1.54%   |
| Zorin 15          | 17        | 1.46%   |
| Ubuntu MATE 18.04 | 16        | 1.37%   |
| Manjaro           | 16        | 1.37%   |
| Linux Mint 20.3   | 16        | 1.37%   |
| Arch              | 16        | 1.37%   |
| Ubuntu 19.04      | 15        | 1.29%   |
| Pop!_OS 22.04     | 15        | 1.29%   |
| Pop!_OS 20.04     | 15        | 1.29%   |
| Linux Mint 20.1   | 15        | 1.29%   |
| Xubuntu 18.04     | 14        | 1.2%    |
| Kubuntu 20.04     | 14        | 1.2%    |
| Ubuntu 21.10      | 13        | 1.11%   |
| Linux Mint 20.2   | 13        | 1.11%   |
| Fedora 35         | 13        | 1.11%   |
| Xubuntu 20.04     | 12        | 1.03%   |
| Gentoo 2.7        | 12        | 1.03%   |
| Ubuntu 21.04      | 11        | 0.94%   |
| Pop!_OS 21.04     | 11        | 0.94%   |
| Linux Mint 21     | 11        | 0.94%   |
| Debian 10         | 11        | 0.94%   |
| ArcoLinux Rolling | 11        | 0.94%   |
| ROSA R10          | 10        | 0.86%   |
| Pop!_OS 20.10     | 9         | 0.77%   |
| Linux Mint 20     | 9         | 0.77%   |
| Fedora 32         | 9         | 0.77%   |
| Ubuntu 20.10      | 8         | 0.69%   |
| Pop!_OS 21.10     | 8         | 0.69%   |
| Fedora 36         | 8         | 0.69%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 387       | 35.09%  |
| Linux Mint    | 89        | 8.07%   |
| OpenMandriva  | 66        | 5.98%   |
| Pop!_OS       | 55        | 4.99%   |
| Fedora        | 50        | 4.53%   |
| Manjaro       | 44        | 3.99%   |
| Ubuntu MATE   | 39        | 3.54%   |
| Zorin         | 38        | 3.45%   |
| Arch          | 38        | 3.45%   |
| Debian        | 36        | 3.26%   |
| Xubuntu       | 32        | 2.9%    |
| KDE neon      | 30        | 2.72%   |
| Kubuntu       | 23        | 2.09%   |
| ROSA          | 22        | 1.99%   |
| Endless       | 17        | 1.54%   |
| Gentoo        | 16        | 1.45%   |
| ArcoLinux     | 14        | 1.27%   |
| Ubuntu Unity  | 11        | 1%      |
| openSUSE      | 9         | 0.82%   |
| Lubuntu       | 7         | 0.63%   |
| BlackPanther  | 7         | 0.63%   |
| Elementary    | 6         | 0.54%   |
| ALT Linux     | 6         | 0.54%   |
| Ubuntu Budgie | 5         | 0.45%   |
| LMDE          | 5         | 0.45%   |
| Peppermint    | 4         | 0.36%   |
| Kali          | 4         | 0.36%   |
| EndeavourOS   | 4         | 0.36%   |
| Artix         | 4         | 0.36%   |
| Xero          | 3         | 0.27%   |
| Slackware     | 3         | 0.27%   |
| LinuxFX       | 3         | 0.27%   |
| CentOS        | 3         | 0.27%   |
| Void Linux    | 2         | 0.18%   |
| Solus         | 2         | 0.18%   |
| Reborn OS     | 2         | 0.18%   |
| MX            | 2         | 0.18%   |
| Mageia        | 2         | 0.18%   |
| SteamOS       | 1         | 0.09%   |
| Raspbian      | 1         | 0.09%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 35        | 2.74%   |
| 5.15.0-52-generic        | 25        | 1.96%   |
| 5.16.7-desktop-1omv4003  | 22        | 1.72%   |
| 5.4.0-42-generic         | 20        | 1.57%   |
| 5.4.0-58-generic         | 19        | 1.49%   |
| 5.4.0-29-generic         | 14        | 1.1%    |
| 4.15.0-163-generic       | 14        | 1.1%    |
| 5.4.0-94-generic         | 13        | 1.02%   |
| 5.3.0-46-generic         | 12        | 0.94%   |
| 5.4.0-54-generic         | 11        | 0.86%   |
| 5.4.0-48-generic         | 11        | 0.86%   |
| 5.11.0-40-generic        | 11        | 0.86%   |
| 5.4.0-91-generic         | 10        | 0.78%   |
| 5.4.0-65-generic         | 10        | 0.78%   |
| 5.15.0-53-generic        | 10        | 0.78%   |
| 4.15.0-47-generic        | 10        | 0.78%   |
| 5.4.0-52-generic         | 9         | 0.7%    |
| 5.4.0-56-generic         | 8         | 0.63%   |
| 5.4.0-37-generic         | 8         | 0.63%   |
| 5.3.0-42-generic         | 8         | 0.63%   |
| 5.15.0-46-generic        | 8         | 0.63%   |
| 5.13.0-39-generic        | 8         | 0.63%   |
| 5.11.0-38-generic        | 8         | 0.63%   |
| 5.11.0-37-generic        | 8         | 0.63%   |
| 5.0.0-37-generic         | 8         | 0.63%   |
| 5.0.0-13-generic         | 8         | 0.63%   |
| 4.15.0-45-generic        | 8         | 0.63%   |
| 5.8.0-43-generic         | 7         | 0.55%   |
| 5.4.0-53-generic         | 7         | 0.55%   |
| 5.4.0-47-generic         | 7         | 0.55%   |
| 5.4.0-40-generic         | 7         | 0.55%   |
| 5.3.0-51-generic         | 7         | 0.55%   |
| 5.3.0-45-generic         | 7         | 0.55%   |
| 5.15.0-41-generic        | 7         | 0.55%   |
| 5.8.0-55-generic         | 6         | 0.47%   |
| 5.4.0-72-generic         | 6         | 0.47%   |
| 5.4.0-66-generic         | 6         | 0.47%   |
| 5.4.0-59-generic         | 6         | 0.47%   |
| 5.4.0-26-generic         | 6         | 0.47%   |
| 5.3.0-28-generic         | 6         | 0.47%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 244       | 20.23%  |
| 4.15.0  | 105       | 8.71%   |
| 5.11.0  | 82        | 6.8%    |
| 5.15.0  | 79        | 6.55%   |
| 5.3.0   | 66        | 5.47%   |
| 5.8.0   | 65        | 5.39%   |
| 5.13.0  | 63        | 5.22%   |
| 5.0.0   | 38        | 3.15%   |
| 5.10.14 | 35        | 2.9%    |
| 4.18.0  | 30        | 2.49%   |
| 5.16.7  | 23        | 1.91%   |
| 5.10.0  | 20        | 1.66%   |
| 4.19.0  | 14        | 1.16%   |
| 5.9.11  | 7         | 0.58%   |
| 5.19.0  | 7         | 0.58%   |
| 5.10.88 | 7         | 0.58%   |
| 4.9.60  | 7         | 0.58%   |
| 5.17.5  | 6         | 0.5%    |
| 5.18.12 | 5         | 0.41%   |
| 5.18.10 | 5         | 0.41%   |
| 5.12.4  | 5         | 0.41%   |
| 4.9.20  | 5         | 0.41%   |
| 4.18.16 | 5         | 0.41%   |
| 5.8.18  | 4         | 0.33%   |
| 5.17.4  | 4         | 0.33%   |
| 5.17.1  | 4         | 0.33%   |
| 5.16.0  | 4         | 0.33%   |
| 5.15.32 | 4         | 0.33%   |
| 5.14.14 | 4         | 0.33%   |
| 5.11.12 | 4         | 0.33%   |
| 6.0.6   | 3         | 0.25%   |
| 6.0.2   | 3         | 0.25%   |
| 5.7.2   | 3         | 0.25%   |
| 5.7.0   | 3         | 0.25%   |
| 5.6.10  | 3         | 0.25%   |
| 5.4.77  | 3         | 0.25%   |
| 5.3.18  | 3         | 0.25%   |
| 5.15.5  | 3         | 0.25%   |
| 5.15.19 | 3         | 0.25%   |
| 5.14.10 | 3         | 0.25%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 265       | 22.18%  |
| 5.15    | 111       | 9.29%   |
| 4.15    | 105       | 8.79%   |
| 5.11    | 99        | 8.28%   |
| 5.10    | 92        | 7.7%    |
| 5.8     | 86        | 7.2%    |
| 5.3     | 72        | 6.03%   |
| 5.13    | 70        | 5.86%   |
| 5.0     | 42        | 3.51%   |
| 5.16    | 36        | 3.01%   |
| 4.18    | 36        | 3.01%   |
| 5.9     | 19        | 1.59%   |
| 5.17    | 19        | 1.59%   |
| 5.18    | 16        | 1.34%   |
| 5.19    | 15        | 1.26%   |
| 5.14    | 15        | 1.26%   |
| 4.19    | 15        | 1.26%   |
| 5.6     | 14        | 1.17%   |
| 4.9     | 14        | 1.17%   |
| 6.0     | 13        | 1.09%   |
| 5.7     | 12        | 1%      |
| 5.12    | 11        | 0.92%   |
| 5.5     | 6         | 0.5%    |
| 4.4     | 2         | 0.17%   |
| 4.1     | 2         | 0.17%   |
| 5.2     | 1         | 0.08%   |
| 5.1     | 1         | 0.08%   |
| 4.20    | 1         | 0.08%   |
| 4.16    | 1         | 0.08%   |
| 4.14    | 1         | 0.08%   |
| 4.10    | 1         | 0.08%   |
| 3.16    | 1         | 0.08%   |
| 3.10    | 1         | 0.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1008      | 94.56%  |
| i686    | 54        | 5.07%   |
| aarch64 | 3         | 0.28%   |
| armv6l  | 1         | 0.09%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| GNOME               | 468       | 41.94%  |
| KDE5                | 171       | 15.32%  |
| Unknown             | 150       | 13.44%  |
| XFCE                | 97        | 8.69%   |
| X-Cinnamon          | 74        | 6.63%   |
| MATE                | 53        | 4.75%   |
| KDE                 | 37        | 3.32%   |
| KDE4                | 12        | 1.08%   |
| Unity               | 11        | 0.99%   |
| LXQt                | 8         | 0.72%   |
| Budgie              | 7         | 0.63%   |
| i3                  | 6         | 0.54%   |
| Pantheon            | 5         | 0.45%   |
| Cinnamon            | 5         | 0.45%   |
| LXDE                | 3         | 0.27%   |
| Openbox             | 2         | 0.18%   |
| GNOME Classic       | 2         | 0.18%   |
| herbstluftwm        | 1         | 0.09%   |
| GNOME Flashback     | 1         | 0.09%   |
| Deepin              | 1         | 0.09%   |
| awesome             | 1         | 0.09%   |
| /usr/bin/startxfce4 | 1         | 0.09%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 888       | 80.8%   |
| Wayland | 103       | 9.37%   |
| Unknown | 85        | 7.73%   |
| Tty     | 23        | 2.09%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 614       | 55.32%  |
| SDDM    | 148       | 13.33%  |
| LightDM | 117       | 10.54%  |
| GDM     | 98        | 8.83%   |
| GDM3    | 91        | 8.2%    |
| TDM     | 24        | 2.16%   |
| KDM     | 12        | 1.08%   |
| XDM     | 3         | 0.27%   |
| SLiM    | 2         | 0.18%   |
| Ly      | 1         | 0.09%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 580       | 52.97%  |
| el_GR      | 304       | 27.76%  |
| Unknown    | 144       | 13.15%  |
| en_GB      | 22        | 2.01%   |
| de_DE      | 12        | 1.1%    |
| C          | 11        | 1%      |
| ru_RU      | 5         | 0.46%   |
| POSIX      | 3         | 0.27%   |
| fr_FR      | 2         | 0.18%   |
| en_IE      | 2         | 0.18%   |
| unm_US     | 1         | 0.09%   |
| pl_PL      | 1         | 0.09%   |
| it_IT      | 1         | 0.09%   |
| hu_HU      | 1         | 0.09%   |
| es_ES      | 1         | 0.09%   |
| en_AU      | 1         | 0.09%   |
| en_AG      | 1         | 0.09%   |
| el_GR@euro | 1         | 0.09%   |
| C.UTF8     | 1         | 0.09%   |
| anp_IN     | 1         | 0.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 636       | 58.3%   |
| EFI  | 455       | 41.7%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 846       | 77.54%  |
| Overlay | 105       | 9.62%   |
| Btrfs   | 77        | 7.06%   |
| Unknown | 44        | 4.03%   |
| Xfs     | 8         | 0.73%   |
| Zfs     | 4         | 0.37%   |
| F2fs    | 3         | 0.27%   |
| Ext3    | 2         | 0.18%   |
| Tmpfs   | 1         | 0.09%   |
| Ext2    | 1         | 0.09%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 676       | 62.08%  |
| GPT     | 282       | 25.9%   |
| MBR     | 131       | 12.03%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 908       | 83.38%  |
| Yes       | 181       | 16.62%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 690       | 63.77%  |
| Yes       | 392       | 36.23%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 175       | 16.42%  |
| ASUSTek Computer        | 164       | 15.38%  |
| Lenovo                  | 137       | 12.85%  |
| Dell                    | 130       | 12.2%   |
| Gigabyte Technology     | 125       | 11.73%  |
| MSI                     | 50        | 4.69%   |
| ASRock                  | 50        | 4.69%   |
| Acer                    | 44        | 4.13%   |
| Toshiba                 | 28        | 2.63%   |
| Sony                    | 26        | 2.44%   |
| Fujitsu Siemens         | 12        | 1.13%   |
| Apple                   | 12        | 1.13%   |
| Intel                   | 11        | 1.03%   |
| Fujitsu                 | 10        | 0.94%   |
| Unknown                 | 7         | 0.66%   |
| Notebook                | 6         | 0.56%   |
| HUAWEI                  | 6         | 0.56%   |
| Clevo                   | 6         | 0.56%   |
| Pegatron                | 5         | 0.47%   |
| Samsung Electronics     | 4         | 0.38%   |
| Raspberry Pi Foundation | 4         | 0.38%   |
| Foxconn                 | 4         | 0.38%   |
| Teclast                 | 3         | 0.28%   |
| Insyde                  | 3         | 0.28%   |
| IBM                     | 3         | 0.28%   |
| E-shop.gr               | 3         | 0.28%   |
| Chuwi                   | 3         | 0.28%   |
| Info Quest Technologies | 2         | 0.19%   |
| Hampoo                  | 2         | 0.19%   |
| ECS                     | 2         | 0.19%   |
| AOpen                   | 2         | 0.19%   |
| ZOTAC                   | 1         | 0.09%   |
| VIA Technologies        | 1         | 0.09%   |
| VERO                    | 1         | 0.09%   |
| Valve                   | 1         | 0.09%   |
| TUXEDO                  | 1         | 0.09%   |
| Supermicro              | 1         | 0.09%   |
| Schenker                | 1         | 0.09%   |
| RuggedPC                | 1         | 0.09%   |
| Quest                   | 1         | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| ASUS All Series                        | 12        | 1.13%   |
| Unknown                                | 12        | 1.13%   |
| HP Pavilion g6                         | 9         | 0.84%   |
| HP ProDesk 600 G1 SFF                  | 7         | 0.66%   |
| HP Notebook                            | 7         | 0.66%   |
| Dell OptiPlex 7010                     | 5         | 0.47%   |
| Dell Inspiron 3542                     | 5         | 0.47%   |
| ASUS ROG STRIX B350-F GAMING           | 5         | 0.47%   |
| ASRock B450 Gaming K4                  | 5         | 0.47%   |
| MSI MS-7C02                            | 4         | 0.38%   |
| HP G62                                 | 4         | 0.38%   |
| HP Compaq Pro 6300 SFF                 | 4         | 0.38%   |
| HP Compaq 8200 Elite SFF PC            | 4         | 0.38%   |
| HP 255 G7 Notebook PC                  | 4         | 0.38%   |
| Gigabyte H61M-S2PV                     | 4         | 0.38%   |
| Gigabyte B450 AORUS M                  | 4         | 0.38%   |
| Dell OptiPlex GX520                    | 4         | 0.38%   |
| Dell Inspiron 5567                     | 4         | 0.38%   |
| Dell Inspiron 3537                     | 4         | 0.38%   |
| Notebook W54_W94_W955TU,-T,-C          | 3         | 0.28%   |
| MSI MS-7C56                            | 3         | 0.28%   |
| Lenovo G510 20238                      | 3         | 0.28%   |
| Insyde CherryTrail                     | 3         | 0.28%   |
| HP Pavilion dv7                        | 3         | 0.28%   |
| HP 255 G8 Notebook PC                  | 3         | 0.28%   |
| Gigabyte G41M-Combo                    | 3         | 0.28%   |
| Gigabyte G31M-S2L                      | 3         | 0.28%   |
| Gigabyte B75M-D3H                      | 3         | 0.28%   |
| Gigabyte B450M DS3H                    | 3         | 0.28%   |
| Gigabyte B250M-DS3H                    | 3         | 0.28%   |
| Gigabyte A320M-S2H                     | 3         | 0.28%   |
| Dell OptiPlex GX620                    | 3         | 0.28%   |
| Dell OptiPlex 7040                     | 3         | 0.28%   |
| ASUS Z170-A                            | 3         | 0.28%   |
| ASUS VivoBook_ASUSLaptop X512DA_X512DA | 3         | 0.28%   |
| ASUS PRIME X570-P                      | 3         | 0.28%   |
| ASUS P6T                               | 3         | 0.28%   |
| ASUS H110M-D                           | 3         | 0.28%   |
| Apple MacBookPro8,1                    | 3         | 0.28%   |
| Acer Aspire A315-51                    | 3         | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Dell Inspiron         | 41        | 3.85%   |
| Lenovo ThinkPad       | 36        | 3.38%   |
| Lenovo IdeaPad        | 36        | 3.38%   |
| HP Pavilion           | 36        | 3.38%   |
| Acer Aspire           | 34        | 3.19%   |
| HP Compaq             | 31        | 2.91%   |
| Dell Latitude         | 28        | 2.63%   |
| Dell OptiPlex         | 27        | 2.53%   |
| Toshiba Satellite     | 24        | 2.25%   |
| Lenovo ThinkCentre    | 20        | 1.88%   |
| ASUS PRIME            | 19        | 1.78%   |
| HP EliteBook          | 12        | 1.13%   |
| HP 255                | 12        | 1.13%   |
| ASUS All              | 12        | 1.13%   |
| Unknown               | 12        | 1.13%   |
| HP Laptop             | 11        | 1.03%   |
| Dell Precision        | 11        | 1.03%   |
| ASUS VivoBook         | 11        | 1.03%   |
| HP ProBook            | 9         | 0.84%   |
| ASUS ROG              | 9         | 0.84%   |
| HP ProDesk            | 8         | 0.75%   |
| Fujitsu LIFEBOOK      | 8         | 0.75%   |
| ASUS TUF              | 8         | 0.75%   |
| HP Notebook           | 7         | 0.66%   |
| HP ENVY               | 7         | 0.66%   |
| Fujitsu Siemens AMILO | 7         | 0.66%   |
| Dell XPS              | 7         | 0.66%   |
| Dell Vostro           | 7         | 0.66%   |
| Gigabyte B450         | 6         | 0.56%   |
| HP 250                | 5         | 0.47%   |
| ASRock B450           | 5         | 0.47%   |
| RPi Raspberry         | 4         | 0.38%   |
| MSI MS-7C02           | 4         | 0.38%   |
| Lenovo Yoga           | 4         | 0.38%   |
| HP G62                | 4         | 0.38%   |
| Gigabyte Z370         | 4         | 0.38%   |
| Gigabyte H61M-S2PV    | 4         | 0.38%   |
| Apple MacBookPro8     | 4         | 0.38%   |
| Notebook W54          | 3         | 0.28%   |
| MSI MS-7C56           | 3         | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2013    | 89        | 8.35%   |
| 2019    | 85        | 7.97%   |
| 2018    | 85        | 7.97%   |
| 2008    | 79        | 7.41%   |
| 2012    | 78        | 7.32%   |
| 2011    | 78        | 7.32%   |
| 2017    | 75        | 7.04%   |
| 2014    | 68        | 6.38%   |
| 2020    | 66        | 6.19%   |
| 2009    | 66        | 6.19%   |
| 2015    | 57        | 5.35%   |
| 2007    | 52        | 4.88%   |
| 2010    | 50        | 4.69%   |
| 2016    | 44        | 4.13%   |
| 2021    | 33        | 3.1%    |
| 2006    | 21        | 1.97%   |
| 2005    | 20        | 1.88%   |
| 2022    | 8         | 0.75%   |
| 2004    | 5         | 0.47%   |
| 2003    | 4         | 0.38%   |
| Unknown | 3         | 0.28%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 568       | 53.28%  |
| Desktop        | 461       | 43.25%  |
| Convertible    | 15        | 1.41%   |
| Tablet         | 7         | 0.66%   |
| All in one     | 5         | 0.47%   |
| System on chip | 4         | 0.38%   |
| Server         | 4         | 0.38%   |
| Mini pc        | 2         | 0.19%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1002      | 93.3%   |
| Enabled  | 72        | 6.7%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1064      | 99.81%  |
| Yes  | 2         | 0.19%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 281       | 25.9%   |
| 4.01-8.0    | 233       | 21.47%  |
| 8.01-16.0   | 203       | 18.71%  |
| 16.01-24.0  | 161       | 14.84%  |
| 1.01-2.0    | 95        | 8.76%   |
| 32.01-64.0  | 50        | 4.61%   |
| 2.01-3.0    | 34        | 3.13%   |
| 0.51-1.0    | 14        | 1.29%   |
| 64.01-256.0 | 7         | 0.65%   |
| 24.01-32.0  | 6         | 0.55%   |
| 0.01-0.5    | 1         | 0.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 478       | 40.68%  |
| 2.01-3.0   | 270       | 22.98%  |
| 3.01-4.0   | 125       | 10.64%  |
| 0.51-1.0   | 122       | 10.38%  |
| 4.01-8.0   | 115       | 9.79%   |
| 8.01-16.0  | 34        | 2.89%   |
| 0.01-0.5   | 24        | 2.04%   |
| 16.01-24.0 | 5         | 0.43%   |
| 32.01-64.0 | 1         | 0.09%   |
| 24.01-32.0 | 1         | 0.09%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 630       | 57.64%  |
| 2      | 287       | 26.26%  |
| 3      | 86        | 7.87%   |
| 4      | 45        | 4.12%   |
| 5      | 19        | 1.74%   |
| 6      | 13        | 1.19%   |
| 0      | 9         | 0.82%   |
| 7      | 3         | 0.27%   |
| 12     | 1         | 0.09%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 548       | 51.12%  |
| Yes       | 524       | 48.88%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 957       | 89.69%  |
| No        | 110       | 10.31%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 743       | 69.05%  |
| No        | 333       | 30.95%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 547       | 50.74%  |
| Yes       | 531       | 49.26%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Greece  | 1066      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Computers | Percent |
|--------------|-----------|---------|
| Athens       | 554       | 48.3%   |
| Thessaloniki | 178       | 15.52%  |
| Heraklion    | 33        | 2.88%   |
| Pátrai      | 27        | 2.35%   |
| Chalcis      | 18        | 1.57%   |
| Kavala       | 17        | 1.48%   |
| Volos        | 12        | 1.05%   |
| Larissa      | 12        | 1.05%   |
| Katerini     | 12        | 1.05%   |
| Chania       | 11        | 0.96%   |
| Ioannina     | 10        | 0.87%   |
| Piraeus      | 9         | 0.78%   |
| Kalamata     | 9         | 0.78%   |
| Trikala      | 8         | 0.7%    |
| Rhodes       | 8         | 0.7%    |
| Lamia        | 8         | 0.7%    |
| Serres       | 7         | 0.61%   |
| Drama        | 7         | 0.61%   |
| Chalandri    | 7         | 0.61%   |
| Xanthi       | 5         | 0.44%   |
| Veroia       | 5         | 0.44%   |
| Karditsa     | 5         | 0.44%   |
| Fira         | 5         | 0.44%   |
| Corinth      | 5         | 0.44%   |
| Corfu        | 5         | 0.44%   |
| Samos        | 4         | 0.35%   |
| Komotini     | 4         | 0.35%   |
| Kilkis       | 4         | 0.35%   |
| Aigaleo      | 4         | 0.35%   |
| Agrinio      | 4         | 0.35%   |
| Zakynthos    | 3         | 0.26%   |
| Rethymno     | 3         | 0.26%   |
| PГЎtrai    | 3         | 0.26%   |
| Paros        | 3         | 0.26%   |
| Nea Smyrni   | 3         | 0.26%   |
| Nafplion     | 3         | 0.26%   |
| Mytilene     | 3         | 0.26%   |
| Kozani       | 3         | 0.26%   |
| Koropi       | 3         | 0.26%   |
| Kallithea    | 3         | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 300       | 473    | 18.81%  |
| Seagate                   | 224       | 322    | 14.04%  |
| Samsung Electronics       | 213       | 293    | 13.35%  |
| Toshiba                   | 129       | 165    | 8.09%   |
| Kingston                  | 98        | 123    | 6.14%   |
| SanDisk                   | 91        | 118    | 5.71%   |
| Patriot                   | 64        | 77     | 4.01%   |
| Unknown                   | 53        | 88     | 3.32%   |
| Hitachi                   | 44        | 46     | 2.76%   |
| SK hynix                  | 33        | 44     | 2.07%   |
| Intenso                   | 30        | 38     | 1.88%   |
| Crucial                   | 30        | 39     | 1.88%   |
| Intel                     | 28        | 34     | 1.76%   |
| HGST                      | 27        | 34     | 1.69%   |
| Fujitsu                   | 18        | 19     | 1.13%   |
| Team                      | 17        | 23     | 1.07%   |
| Micron Technology         | 17        | 20     | 1.07%   |
| OCZ                       | 16        | 19     | 1%      |
| A-DATA Technology         | 12        | 18     | 0.75%   |
| Maxtor                    | 11        | 13     | 0.69%   |
| KIOXIA                    | 10        | 12     | 0.63%   |
| PNY                       | 8         | 8      | 0.5%    |
| Phison                    | 8         | 11     | 0.5%    |
| JMicron Technology        | 8         | 11     | 0.5%    |
| SPCC                      | 7         | 9      | 0.44%   |
| Gigabyte Technology       | 6         | 8      | 0.38%   |
| Corsair                   | 6         | 6      | 0.38%   |
| XPG                       | 5         | 7      | 0.31%   |
| Transcend                 | 5         | 5      | 0.31%   |
| Leven                     | 5         | 5      | 0.31%   |
| Mushkin                   | 4         | 4      | 0.25%   |
| Micron/Crucial Technology | 4         | 5      | 0.25%   |
| China                     | 4         | 4      | 0.25%   |
| Unknown                   | 4         | 4      | 0.25%   |
| Teclast                   | 3         | 3      | 0.19%   |
| GOODRAM                   | 3         | 5      | 0.19%   |
| Emtec                     | 3         | 4      | 0.19%   |
| Apple                     | 3         | 3      | 0.19%   |
| Verbatim                  | 2         | 3      | 0.13%   |
| Silicon Motion            | 2         | 2      | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 250GB              | 26        | 1.48%   |
| Samsung SSD 860 EVO 500GB              | 21        | 1.2%    |
| Unknown MMC Card  32GB                 | 19        | 1.08%   |
| Patriot Burst 120GB SSD                | 18        | 1.03%   |
| Seagate ST500DM002-1BD142 500GB        | 17        | 0.97%   |
| Samsung SSD 850 EVO 250GB              | 16        | 0.91%   |
| Kingston SA400S37240G 240GB SSD        | 16        | 0.91%   |
| Kingston SA400S37120G 120GB SSD        | 15        | 0.85%   |
| Toshiba DT01ACA100 1TB                 | 14        | 0.8%    |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 14        | 0.8%    |
| Patriot Burst 240GB SSD                | 14        | 0.8%    |
| Toshiba MQ01ABF050 500GB               | 12        | 0.68%   |
| SK hynix NVMe SSD Drive 256GB          | 12        | 0.68%   |
| Unknown MMC Card  64GB                 | 11        | 0.63%   |
| Toshiba DT01ACA050 500GB               | 11        | 0.63%   |
| Seagate ST1000DM010-2EP102 1TB         | 11        | 0.63%   |
| Patriot Burst 480GB SSD                | 11        | 0.63%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 10        | 0.57%   |
| Seagate ST1000LM035-1RK172 1TB         | 10        | 0.57%   |
| Samsung SSD 850 EVO 500GB              | 10        | 0.57%   |
| Toshiba MQ01ABD100 1TB                 | 9         | 0.51%   |
| Seagate ST500LT012-1DG142 500GB        | 9         | 0.51%   |
| Seagate ST500LM012 HN-M500MBB 500GB    | 9         | 0.51%   |
| Samsung NVMe SSD Drive 500GB           | 9         | 0.51%   |
| WDC WD10EZEX-08WN4A0 1TB               | 8         | 0.46%   |
| Toshiba DT01ACA200 2TB                 | 8         | 0.46%   |
| SanDisk NVMe SSD Drive 256GB           | 8         | 0.46%   |
| Kingston SV300S37A120G 120GB SSD       | 8         | 0.46%   |
| Kingston SA400S37480G 480GB SSD        | 8         | 0.46%   |
| HGST HTS545050A7E680 500GB             | 8         | 0.46%   |
| Unknown MMC Card  128GB                | 7         | 0.4%    |
| SanDisk SDSSDA120G 120GB               | 7         | 0.4%    |
| Samsung SSD 850 EVO 120GB              | 7         | 0.4%    |
| Samsung NVMe SSD Drive 512GB           | 7         | 0.4%    |
| WDC WD5000AAKX-08U6AA0 500GB           | 6         | 0.34%   |
| SanDisk NVMe SSD Drive 512GB           | 6         | 0.34%   |
| Samsung SSD 970 EVO Plus 500GB         | 6         | 0.34%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 6         | 0.34%   |
| PNY CS900 120GB SSD                    | 6         | 0.34%   |
| Intenso SSD Sata III 240GB             | 6         | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 257       | 396    | 36.2%   |
| Seagate             | 221       | 317    | 31.13%  |
| Toshiba             | 97        | 120    | 13.66%  |
| Hitachi             | 44        | 46     | 6.2%    |
| HGST                | 27        | 34     | 3.8%    |
| Samsung Electronics | 21        | 26     | 2.96%   |
| Fujitsu             | 18        | 19     | 2.54%   |
| Maxtor              | 11        | 13     | 1.55%   |
| Intenso             | 5         | 6      | 0.7%    |
| Apple               | 2         | 2      | 0.28%   |
| Unknown             | 1         | 1      | 0.14%   |
| Quantum             | 1         | 1      | 0.14%   |
| JMicron Technology  | 1         | 1      | 0.14%   |
| IBM/Hitachi         | 1         | 1      | 0.14%   |
| IBM-ESXS            | 1         | 3      | 0.14%   |
| Hewlett-Packard     | 1         | 1      | 0.14%   |
| ASMT109x            | 1         | 1      | 0.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 133       | 168    | 21.66%  |
| Kingston            | 80        | 103    | 13.03%  |
| SanDisk             | 69        | 92     | 11.24%  |
| Patriot             | 63        | 76     | 10.26%  |
| WDC                 | 37        | 59     | 6.03%   |
| Crucial             | 28        | 37     | 4.56%   |
| Intenso             | 22        | 29     | 3.58%   |
| Toshiba             | 20        | 29     | 3.26%   |
| Intel               | 18        | 21     | 2.93%   |
| Team                | 17        | 23     | 2.77%   |
| OCZ                 | 15        | 18     | 2.44%   |
| A-DATA Technology   | 11        | 17     | 1.79%   |
| Micron Technology   | 10        | 11     | 1.63%   |
| PNY                 | 8         | 8      | 1.3%    |
| SPCC                | 7         | 9      | 1.14%   |
| Gigabyte Technology | 6         | 8      | 0.98%   |
| SK hynix            | 5         | 5      | 0.81%   |
| Leven               | 5         | 5      | 0.81%   |
| JMicron Technology  | 5         | 5      | 0.81%   |
| Corsair             | 5         | 5      | 0.81%   |
| Transcend           | 4         | 4      | 0.65%   |
| Mushkin             | 4         | 4      | 0.65%   |
| China               | 4         | 4      | 0.65%   |
| Teclast             | 3         | 3      | 0.49%   |
| GOODRAM             | 3         | 5      | 0.49%   |
| Emtec               | 3         | 4      | 0.49%   |
| Unknown             | 3         | 3      | 0.49%   |
| Verbatim            | 2         | 3      | 0.33%   |
| Plextor             | 2         | 2      | 0.33%   |
| Platinet            | 2         | 2      | 0.33%   |
| LITEONIT            | 2         | 2      | 0.33%   |
| Drevo               | 2         | 2      | 0.33%   |
| Apacer              | 2         | 2      | 0.33%   |
| WDC WDS             | 1         | 1      | 0.16%   |
| USB30               | 1         | 1      | 0.16%   |
| Unknown             | 1         | 4      | 0.16%   |
| Seagate             | 1         | 1      | 0.16%   |
| OCZ-AGIL            | 1         | 1      | 0.16%   |
| Netac               | 1         | 1      | 0.16%   |
| LITEON              | 1         | 1      | 0.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 610       | 988    | 42.81%  |
| SSD     | 530       | 787    | 37.19%  |
| NVMe    | 222       | 295    | 15.58%  |
| MMC     | 52        | 88     | 3.65%   |
| Unknown | 11        | 17     | 0.77%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 899       | 1735   | 73.99%  |
| NVMe | 221       | 293    | 18.19%  |
| MMC  | 52        | 88     | 4.28%   |
| SAS  | 43        | 59     | 3.54%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 767       | 1251   | 67.76%  |
| 0.51-1.0   | 255       | 365    | 22.53%  |
| 1.01-2.0   | 56        | 77     | 4.95%   |
| 3.01-4.0   | 21        | 27     | 1.86%   |
| 2.01-3.0   | 21        | 34     | 1.86%   |
| 4.01-10.0  | 10        | 18     | 0.88%   |
| 10.01-20.0 | 2         | 3      | 0.18%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 331       | 29.34%  |
| 251-500        | 224       | 19.86%  |
| 501-1000       | 126       | 11.17%  |
| 51-100         | 97        | 8.6%    |
| 1001-2000      | 85        | 7.54%   |
| 1-20           | 82        | 7.27%   |
| 21-50          | 63        | 5.59%   |
| Unknown        | 51        | 4.52%   |
| More than 3000 | 44        | 3.9%    |
| 2001-3000      | 25        | 2.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 444       | 38.24%  |
| 21-50          | 192       | 16.54%  |
| 51-100         | 138       | 11.89%  |
| 101-250        | 121       | 10.42%  |
| 251-500        | 90        | 7.75%   |
| 501-1000       | 57        | 4.91%   |
| Unknown        | 51        | 4.39%   |
| 1001-2000      | 39        | 3.36%   |
| More than 3000 | 21        | 1.81%   |
| 2001-3000      | 8         | 0.69%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| HGST HTS545050A7E680 500GB           | 4         | 4      | 4.44%   |
| Seagate ST500DM002-1BD142 500GB      | 2         | 2      | 2.22%   |
| Seagate ST3500320AS 500GB            | 2         | 2      | 2.22%   |
| SanDisk SSD PLUS 240GB               | 2         | 2      | 2.22%   |
| WDC WD800JB-00JJC0 80GB              | 1         | 1      | 1.11%   |
| WDC WD5000LPCX-24VHAT0 500GB         | 1         | 1      | 1.11%   |
| WDC WD5000BPVT-60HXZT1 500GB         | 1         | 1      | 1.11%   |
| WDC WD5000AAVS-22G9B1 500GB          | 1         | 1      | 1.11%   |
| WDC WD5000AAKB-00H8A0 500GB          | 1         | 1      | 1.11%   |
| WDC WD3200BEVT-26ZCT0 320GB          | 1         | 1      | 1.11%   |
| WDC WD3200BEVT-00A0RT0 320GB         | 1         | 1      | 1.11%   |
| WDC WD30EZRZ-00GXCB0 3TB             | 1         | 1      | 1.11%   |
| WDC WD2500YS-01SHB1 256GB            | 1         | 2      | 1.11%   |
| WDC WD2500BEVT-22A23T0 250GB         | 1         | 1      | 1.11%   |
| WDC WD2500AAKX-083CA1 250GB          | 1         | 1      | 1.11%   |
| WDC WD20PURX-64P6ZY0 2TB             | 1         | 1      | 1.11%   |
| WDC WD2002FAEX-007BA0 2TB            | 1         | 2      | 1.11%   |
| WDC WD1600BEVS-22RST0 160GB          | 1         | 1      | 1.11%   |
| WDC WD1600AAJS-22L7A0 160GB          | 1         | 1      | 1.11%   |
| WDC WD1200JD-00HBB0 120GB            | 1         | 2      | 1.11%   |
| WDC WD10EZEX-60WN4A1 1TB             | 1         | 3      | 1.11%   |
| WDC WD10EZEX-60WN4A0 1TB             | 1         | 1      | 1.11%   |
| WDC WD10EALX-009BA0 1TB              | 1         | 1      | 1.11%   |
| WDC WD10EADS-00M2B0 1TB              | 1         | 1      | 1.11%   |
| Toshiba MQ01ACF050 500GB             | 1         | 1      | 1.11%   |
| Toshiba MQ01ABD100M 1TB              | 1         | 1      | 1.11%   |
| Toshiba MQ01ABD050 500GB             | 1         | 3      | 1.11%   |
| Toshiba MK3263GSX 320GB              | 1         | 1      | 1.11%   |
| Toshiba MK1665GSX H 160GB            | 1         | 1      | 1.11%   |
| Toshiba DT01ACA100 1TB               | 1         | 1      | 1.11%   |
| Toshiba DT01ACA050 500GB             | 1         | 1      | 1.11%   |
| SK hynix SC210 mSATA 256GB SSD       | 1         | 1      | 1.11%   |
| SK hynix BC711 HFM256GD3JX013N 256GB | 1         | 1      | 1.11%   |
| Seagate ST980811AS 80GB              | 1         | 1      | 1.11%   |
| Seagate ST9320325AS 320GB            | 1         | 1      | 1.11%   |
| Seagate ST9160412AS 160GB            | 1         | 1      | 1.11%   |
| Seagate ST9160310AS 160GB            | 1         | 1      | 1.11%   |
| Seagate ST500LT012-9WS142 500GB      | 1         | 1      | 1.11%   |
| Seagate ST500LT012-1DG142 500GB      | 1         | 1      | 1.11%   |
| Seagate ST500LM021-1KJ152 500GB      | 1         | 1      | 1.11%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 23        | 25     | 25.84%  |
| WDC                 | 19        | 25     | 21.35%  |
| Toshiba             | 7         | 9      | 7.87%   |
| Hitachi             | 7         | 7      | 7.87%   |
| HGST                | 5         | 5      | 5.62%   |
| SanDisk             | 4         | 4      | 4.49%   |
| Samsung Electronics | 4         | 4      | 4.49%   |
| Corsair             | 3         | 3      | 3.37%   |
| SK hynix            | 2         | 2      | 2.25%   |
| Patriot             | 2         | 2      | 2.25%   |
| Micron Technology   | 2         | 2      | 2.25%   |
| Maxtor              | 2         | 2      | 2.25%   |
| Kingston            | 2         | 2      | 2.25%   |
| Intel               | 2         | 2      | 2.25%   |
| Crucial             | 2         | 3      | 2.25%   |
| OCZ-AGIL            | 1         | 1      | 1.12%   |
| Fujitsu             | 1         | 1      | 1.12%   |
| A-DATA Technology   | 1         | 1      | 1.12%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 23        | 25     | 35.38%  |
| WDC                 | 19        | 25     | 29.23%  |
| Toshiba             | 7         | 9      | 10.77%  |
| Hitachi             | 7         | 7      | 10.77%  |
| HGST                | 5         | 5      | 7.69%   |
| Maxtor              | 2         | 2      | 3.08%   |
| Samsung Electronics | 1         | 1      | 1.54%   |
| Fujitsu             | 1         | 1      | 1.54%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 61        | 75     | 71.76%  |
| SSD  | 20        | 21     | 23.53%  |
| NVMe | 4         | 4      | 4.71%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST3500418AS 500GB | 1         | 1      | 50%     |
| Mushkin MKNSSDCR120GB-7   | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| Mushkin | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 733       | 1425   | 63.79%  |
| Works    | 333       | 648    | 28.98%  |
| Malfunc  | 81        | 100    | 7.05%   |
| Failed   | 2         | 2      | 0.17%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 714       | 55.35%  |
| AMD                              | 232       | 17.98%  |
| Samsung Electronics              | 79        | 6.12%   |
| JMicron Technology               | 35        | 2.71%   |
| SanDisk                          | 30        | 2.33%   |
| SK hynix                         | 27        | 2.09%   |
| Nvidia                           | 23        | 1.78%   |
| Kingston Technology Company      | 20        | 1.55%   |
| Marvell Technology Group         | 19        | 1.47%   |
| ASMedia Technology               | 17        | 1.32%   |
| KIOXIA                           | 13        | 1.01%   |
| Toshiba America Info Systems     | 12        | 0.93%   |
| Phison Electronics               | 11        | 0.85%   |
| VIA Technologies                 | 10        | 0.78%   |
| Silicon Image                    | 7         | 0.54%   |
| Micron Technology                | 7         | 0.54%   |
| Micron/Crucial Technology        | 5         | 0.39%   |
| ADATA Technology                 | 5         | 0.39%   |
| Silicon Motion                   | 4         | 0.31%   |
| LSI Logic / Symbios Logic        | 3         | 0.23%   |
| Broadcom / LSI                   | 3         | 0.23%   |
| Union Memory (Shenzhen)          | 2         | 0.16%   |
| Seagate Technology               | 2         | 0.16%   |
| Realtek Semiconductor            | 2         | 0.16%   |
| Solid State Storage Technology   | 1         | 0.08%   |
| Silicon Integrated Systems [SiS] | 1         | 0.08%   |
| Promise Technology               | 1         | 0.08%   |
| OCZ Technology Group             | 1         | 0.08%   |
| O2 Micro                         | 1         | 0.08%   |
| Lite-On Technology               | 1         | 0.08%   |
| Integrated Technology Express    | 1         | 0.08%   |
| INNOGRIT                         | 1         | 0.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 160       | 10.08%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 61        | 3.84%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 52        | 3.28%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 46        | 2.9%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 44        | 2.77%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 42        | 2.65%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 38        | 2.39%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 36        | 2.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 35        | 2.21%   |
| AMD 400 Series Chipset SATA Controller                                                  | 34        | 2.14%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 33        | 2.08%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 24        | 1.51%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 24        | 1.51%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 23        | 1.45%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 22        | 1.39%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 22        | 1.39%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 22        | 1.39%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 22        | 1.39%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 20        | 1.26%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 19        | 1.2%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 18        | 1.13%   |
| Samsung NVMe SSD Controller 980                                                         | 16        | 1.01%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 16        | 1.01%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 16        | 1.01%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 16        | 1.01%   |
| AMD 300 Series Chipset SATA Controller                                                  | 15        | 0.95%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 13        | 0.82%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 13        | 0.82%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 13        | 0.82%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 13        | 0.82%   |
| KIOXIA NVMe SSD Controller BG4                                                          | 12        | 0.76%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 12        | 0.76%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 12        | 0.76%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 12        | 0.76%   |
| AMD 500 Series Chipset SATA Controller                                                  | 12        | 0.76%   |
| Intel SATA Controller [RAID mode]                                                       | 11        | 0.69%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 11        | 0.69%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 11        | 0.69%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 11        | 0.69%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 11        | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 763       | 57.33%  |
| IDE  | 274       | 20.59%  |
| NVMe | 228       | 17.13%  |
| RAID | 60        | 4.51%   |
| SAS  | 5         | 0.38%   |
| SCSI | 1         | 0.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 773       | 72.51%  |
| AMD          | 288       | 27.02%  |
| ARM          | 4         | 0.38%   |
| CentaurHauls | 1         | 0.09%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 13        | 1.22%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 12        | 1.12%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 11        | 1.03%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 10        | 0.94%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 9         | 0.84%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 8         | 0.75%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 8         | 0.75%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 8         | 0.75%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 8         | 0.75%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 8         | 0.75%   |
| Intel Pentium 4 CPU 3.20GHz                   | 7         | 0.66%   |
| Intel Pentium 4 CPU 3.00GHz                   | 7         | 0.66%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 7         | 0.66%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 7         | 0.66%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 7         | 0.66%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 7         | 0.66%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 7         | 0.66%   |
| AMD FX-6300 Six-Core Processor                | 7         | 0.66%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 6         | 0.56%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 6         | 0.56%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 6         | 0.56%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 6         | 0.56%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 6         | 0.56%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 6         | 0.56%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 6         | 0.56%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 6         | 0.56%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 6         | 0.56%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 6         | 0.56%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 6         | 0.56%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz          | 6         | 0.56%   |
| Intel Celeron CPU G1840 @ 2.80GHz             | 6         | 0.56%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 6         | 0.56%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 6         | 0.56%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz        | 5         | 0.47%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 5         | 0.47%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 5         | 0.47%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 5         | 0.47%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 5         | 0.47%   |
| AMD Ryzen 5 2600X Six-Core Processor          | 5         | 0.47%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 5         | 0.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 187       | 17.53%  |
| Intel Core i7                  | 133       | 12.46%  |
| Intel Core i3                  | 91        | 8.53%   |
| Intel Core 2 Duo               | 84        | 7.87%   |
| AMD Ryzen 5                    | 75        | 7.03%   |
| Intel Celeron                  | 59        | 5.53%   |
| AMD Ryzen 7                    | 44        | 4.12%   |
| Intel Pentium                  | 38        | 3.56%   |
| Intel Atom                     | 36        | 3.37%   |
| Other                          | 30        | 2.81%   |
| Intel Core 2 Quad              | 22        | 2.06%   |
| AMD Ryzen 3                    | 21        | 1.97%   |
| Intel Pentium 4                | 19        | 1.78%   |
| Intel Core 2                   | 17        | 1.59%   |
| AMD FX                         | 16        | 1.5%    |
| AMD Athlon 64 X2               | 15        | 1.41%   |
| Intel Xeon                     | 14        | 1.31%   |
| Intel Pentium Dual-Core        | 14        | 1.31%   |
| AMD A8                         | 12        | 1.12%   |
| AMD Ryzen 9                    | 10        | 0.94%   |
| AMD Phenom II X4               | 10        | 0.94%   |
| AMD A10                        | 10        | 0.94%   |
| AMD E1                         | 9         | 0.84%   |
| AMD A6                         | 9         | 0.84%   |
| AMD A4                         | 9         | 0.84%   |
| Intel Pentium Dual             | 8         | 0.75%   |
| Intel Pentium D                | 6         | 0.56%   |
| AMD Athlon                     | 6         | 0.56%   |
| Intel Genuine                  | 5         | 0.47%   |
| Intel Celeron M                | 5         | 0.47%   |
| Intel Pentium M                | 4         | 0.37%   |
| Intel Celeron Dual-Core        | 4         | 0.37%   |
| AMD Phenom II X6               | 4         | 0.37%   |
| AMD Sempron                    | 3         | 0.28%   |
| AMD Ryzen 7 PRO                | 3         | 0.28%   |
| AMD E                          | 3         | 0.28%   |
| AMD Turion X2 Dual-Core Mobile | 2         | 0.19%   |
| AMD Turion 64 X2 Mobile        | 2         | 0.19%   |
| AMD Turion                     | 2         | 0.19%   |
| AMD Ryzen Threadripper         | 2         | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 498       | 46.67%  |
| 4       | 348       | 32.61%  |
| 6       | 84        | 7.87%   |
| 1       | 59        | 5.53%   |
| 8       | 51        | 4.78%   |
| 12      | 12        | 1.12%   |
| 3       | 9         | 0.84%   |
| 16      | 4         | 0.37%   |
| 14      | 1         | 0.09%   |
| Unknown | 1         | 0.09%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1058      | 99.25%  |
| 2       | 7         | 0.66%   |
| Unknown | 1         | 0.09%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 566       | 53.1%   |
| 1       | 497       | 46.62%  |
| 8       | 1         | 0.09%   |
| 4       | 1         | 0.09%   |
| Unknown | 1         | 0.09%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1017      | 95.05%  |
| 32-bit         | 33        | 3.08%   |
| Unknown        | 18        | 1.68%   |
| 64-bit         | 2         | 0.19%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 219       | 19.87%  |
| 0x206a7    | 67        | 6.08%   |
| 0x306c3    | 66        | 5.99%   |
| 0x306a9    | 53        | 4.81%   |
| 0x1067a    | 45        | 4.08%   |
| 0x10676    | 24        | 2.18%   |
| 0x6fd      | 23        | 2.09%   |
| 0x40651    | 23        | 2.09%   |
| 0x806ea    | 19        | 1.72%   |
| 0x906ea    | 18        | 1.63%   |
| 0x506e3    | 17        | 1.54%   |
| 0x08108109 | 17        | 1.54%   |
| 0x08108102 | 17        | 1.54%   |
| 0x0800820d | 16        | 1.45%   |
| 0x906e9    | 15        | 1.36%   |
| 0x806e9    | 15        | 1.36%   |
| 0x406c4    | 15        | 1.36%   |
| 0x806c1    | 14        | 1.27%   |
| 0x30678    | 14        | 1.27%   |
| 0x506c9    | 13        | 1.18%   |
| 0x306d4    | 13        | 1.18%   |
| 0x6f6      | 12        | 1.09%   |
| 0x106c2    | 11        | 1%      |
| 0x20655    | 10        | 0.91%   |
| 0x06000852 | 10        | 0.91%   |
| 0x906ed    | 9         | 0.82%   |
| 0x806ec    | 9         | 0.82%   |
| 0x406c3    | 9         | 0.82%   |
| 0x20652    | 9         | 0.82%   |
| 0x106e5    | 9         | 0.82%   |
| 0x0810100b | 9         | 0.82%   |
| 0xf43      | 8         | 0.73%   |
| 0x6fb      | 8         | 0.73%   |
| 0x08701021 | 8         | 0.73%   |
| 0x906eb    | 7         | 0.64%   |
| 0x406e3    | 7         | 0.64%   |
| 0x0a50000c | 7         | 0.64%   |
| 0x06003106 | 7         | 0.64%   |
| 0x05000119 | 7         | 0.64%   |
| 0xf41      | 6         | 0.54%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 114       | 10.68%  |
| Haswell          | 101       | 9.47%   |
| Penryn           | 94        | 8.81%   |
| SandyBridge      | 79        | 7.4%    |
| Zen+             | 68        | 6.37%   |
| IvyBridge        | 67        | 6.28%   |
| Core             | 67        | 6.28%   |
| Silvermont       | 44        | 4.12%   |
| Skylake          | 34        | 3.19%   |
| Zen              | 33        | 3.09%   |
| Zen 2            | 30        | 2.81%   |
| Westmere         | 26        | 2.44%   |
| NetBurst         | 26        | 2.44%   |
| Zen 3            | 25        | 2.34%   |
| Piledriver       | 22        | 2.06%   |
| K8 Hammer        | 22        | 2.06%   |
| K10              | 22        | 2.06%   |
| TigerLake        | 17        | 1.59%   |
| Broadwell        | 15        | 1.41%   |
| Bonnell          | 15        | 1.41%   |
| Nehalem          | 14        | 1.31%   |
| Goldmont         | 14        | 1.31%   |
| Excavator        | 14        | 1.31%   |
| Unknown          | 14        | 1.31%   |
| P6               | 13        | 1.22%   |
| CometLake        | 13        | 1.22%   |
| Bobcat           | 11        | 1.03%   |
| Puma             | 9         | 0.84%   |
| Steamroller      | 8         | 0.75%   |
| Goldmont plus    | 8         | 0.75%   |
| IceLake          | 7         | 0.66%   |
| K8 & K10 hybrid  | 6         | 0.56%   |
| K10 Llano        | 5         | 0.47%   |
| K6               | 3         | 0.28%   |
| Jaguar           | 3         | 0.28%   |
| Alderlake Hybrid | 3         | 0.28%   |
| Bulldozer        | 1         | 0.09%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 525       | 43.25%  |
| AMD                              | 348       | 28.67%  |
| Nvidia                           | 334       | 27.51%  |
| VIA Technologies                 | 3         | 0.25%   |
| Matrox Electronics Systems       | 2         | 0.16%   |
| Silicon Integrated Systems [SiS] | 1         | 0.08%   |
| Conexant Systems                 | 1         | 0.08%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 62        | 4.85%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 43        | 3.36%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 32        | 2.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 28        | 2.19%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 27        | 2.11%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 24        | 1.88%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 20        | 1.56%   |
| Intel HD Graphics 620                                                                    | 20        | 1.56%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 20        | 1.56%   |
| Intel UHD Graphics 620                                                                   | 19        | 1.49%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 19        | 1.49%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 19        | 1.49%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 16        | 1.25%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 16        | 1.25%   |
| AMD Renoir                                                                               | 16        | 1.25%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 15        | 1.17%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 15        | 1.17%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 15        | 1.17%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 15        | 1.17%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 14        | 1.1%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 13        | 1.02%   |
| Intel HD Graphics 500                                                                    | 13        | 1.02%   |
| Intel Core Processor Integrated Graphics Controller                                      | 13        | 1.02%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 13        | 1.02%   |
| Intel HD Graphics 5500                                                                   | 12        | 0.94%   |
| Intel HD Graphics 530                                                                    | 12        | 0.94%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 12        | 0.94%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 11        | 0.86%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 11        | 0.86%   |
| Nvidia GT218 [GeForce 210]                                                               | 10        | 0.78%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 10        | 0.78%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 9         | 0.7%    |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 9         | 0.7%    |
| Intel HD Graphics 630                                                                    | 9         | 0.7%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 9         | 0.7%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 9         | 0.7%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 8         | 0.63%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 8         | 0.63%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 8         | 0.63%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 8         | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| 1 x Intel                      | 386       | 35.94%  |
| 1 x AMD                        | 281       | 26.16%  |
| 1 x Nvidia                     | 224       | 20.86%  |
| Intel + Nvidia                 | 99        | 9.22%   |
| Intel + AMD                    | 34        | 3.17%   |
| 2 x AMD                        | 25        | 2.33%   |
| Other                          | 7         | 0.65%   |
| AMD + Nvidia                   | 7         | 0.65%   |
| 2 x Nvidia                     | 3         | 0.28%   |
| 1 x VIA                        | 3         | 0.28%   |
| 1 x Matrox                     | 2         | 0.19%   |
| 2 x Intel                      | 1         | 0.09%   |
| 2 x AMD + 1 x Conexant Systems | 1         | 0.09%   |
| 1 x SiS                        | 1         | 0.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 874       | 81.08%  |
| Proprietary | 161       | 14.94%  |
| Unknown     | 43        | 3.99%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 508       | 46.35%  |
| 1.01-2.0   | 187       | 17.06%  |
| 0.01-0.5   | 170       | 15.51%  |
| 0.51-1.0   | 104       | 9.49%   |
| 3.01-4.0   | 72        | 6.57%   |
| 7.01-8.0   | 26        | 2.37%   |
| 5.01-6.0   | 20        | 1.82%   |
| 2.01-3.0   | 6         | 0.55%   |
| 8.01-16.0  | 3         | 0.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 162       | 14.63%  |
| Goldstar                | 136       | 12.29%  |
| LG Display              | 104       | 9.39%   |
| AU Optronics            | 104       | 9.39%   |
| BOE                     | 86        | 7.77%   |
| Chimei Innolux          | 79        | 7.14%   |
| Dell                    | 62        | 5.6%    |
| Philips                 | 33        | 2.98%   |
| Hewlett-Packard         | 26        | 2.35%   |
| LG Electronics          | 23        | 2.08%   |
| Chi Mei Optoelectronics | 22        | 1.99%   |
| ViewSonic               | 18        | 1.63%   |
| AOC                     | 18        | 1.63%   |
| BenQ                    | 16        | 1.45%   |
| LG Philips              | 15        | 1.36%   |
| Lenovo                  | 14        | 1.26%   |
| Ancor Communications    | 14        | 1.26%   |
| Sony                    | 12        | 1.08%   |
| Apple                   | 12        | 1.08%   |
| Eizo                    | 11        | 0.99%   |
| Sharp                   | 10        | 0.9%    |
| Vestel Elektronik       | 9         | 0.81%   |
| Iiyama                  | 8         | 0.72%   |
| CPT                     | 7         | 0.63%   |
| Unknown                 | 6         | 0.54%   |
| PANDA                   | 6         | 0.54%   |
| NEC Computers           | 6         | 0.54%   |
| HannStar                | 6         | 0.54%   |
| Fujitsu Siemens         | 6         | 0.54%   |
| JRY                     | 5         | 0.45%   |
| Acer                    | 5         | 0.45%   |
| Medion                  | 4         | 0.36%   |
| InfoVision              | 4         | 0.36%   |
| Belinea                 | 4         | 0.36%   |
| ASUSTek Computer        | 4         | 0.36%   |
| Quanta Display          | 3         | 0.27%   |
| Mi                      | 3         | 0.27%   |
| Toshiba                 | 2         | 0.18%   |
| Nvidia                  | 2         | 0.18%   |
| LLL                     | 2         | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 11        | 0.97%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch         | 11        | 0.97%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 9         | 0.79%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 8         | 0.7%    |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch       | 7         | 0.62%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch          | 7         | 0.62%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                  | 6         | 0.53%   |
| ViewSonic VA703-4SERIES VSC6A1E 1280x1024 338x270mm 17.0-inch          | 5         | 0.44%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch            | 5         | 0.44%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 5         | 0.44%   |
| Goldstar 2D FHD TV GSM59C6 1920x1080 509x286mm 23.0-inch               | 5         | 0.44%   |
| CPT LCD Monitor CPT1415 1280x800 331x207mm 15.4-inch                   | 5         | 0.44%   |
| Samsung Electronics T24E390 SAM0C20 1920x1080 521x293mm 23.5-inch      | 4         | 0.35%   |
| Samsung Electronics T23B350 SAM093B 1920x1080 510x287mm 23.0-inch      | 4         | 0.35%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch      | 4         | 0.35%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 4         | 0.35%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch   | 4         | 0.35%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch   | 4         | 0.35%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch      | 4         | 0.35%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch          | 4         | 0.35%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch            | 4         | 0.35%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch            | 4         | 0.35%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                 | 4         | 0.35%   |
| Dell S2715H DEL40BB 1920x1080 598x336mm 27.0-inch                      | 4         | 0.35%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch       | 4         | 0.35%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch        | 4         | 0.35%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch        | 4         | 0.35%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 4         | 0.35%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch          | 4         | 0.35%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                    | 4         | 0.35%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 520x290mm 23.4-inch  | 4         | 0.35%   |
| Samsung Electronics S27E390 SAM0C1C 1920x1080 598x336mm 27.0-inch      | 3         | 0.26%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch      | 3         | 0.26%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch   | 3         | 0.26%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch   | 3         | 0.26%   |
| Samsung Electronics LCD Monitor SAM090B 1920x1080 890x500mm 40.2-inch  | 3         | 0.26%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 3         | 0.26%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                | 3         | 0.26%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                    | 3         | 0.26%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                | 3         | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 457       | 43.15%  |
| 1366x768 (WXGA)    | 213       | 20.11%  |
| 1280x1024 (SXGA)   | 65        | 6.14%   |
| 1280x800 (WXGA)    | 49        | 4.63%   |
| 3840x2160 (4K)     | 40        | 3.78%   |
| 1680x1050 (WSXGA+) | 40        | 3.78%   |
| 1600x900 (HD+)     | 34        | 3.21%   |
| 1440x900 (WXGA+)   | 31        | 2.93%   |
| 2560x1440 (QHD)    | 24        | 2.27%   |
| 1920x1200 (WUXGA)  | 19        | 1.79%   |
| 1360x768           | 11        | 1.04%   |
| 1024x768 (XGA)     | 11        | 1.04%   |
| 1024x600           | 9         | 0.85%   |
| Unknown            | 9         | 0.85%   |
| 2560x1080          | 8         | 0.76%   |
| 1600x1200          | 6         | 0.57%   |
| 3840x1080          | 5         | 0.47%   |
| 3440x1440          | 4         | 0.38%   |
| 2160x1440          | 3         | 0.28%   |
| 2880x1800          | 2         | 0.19%   |
| 2560x1600          | 2         | 0.19%   |
| 2048x1152          | 2         | 0.19%   |
| 1920x540           | 2         | 0.19%   |
| 800x1280           | 1         | 0.09%   |
| 5120x1440          | 1         | 0.09%   |
| 4864x2160          | 1         | 0.09%   |
| 4480x1080          | 1         | 0.09%   |
| 3840x2400          | 1         | 0.09%   |
| 3600x1080          | 1         | 0.09%   |
| 3200x1800 (QHD+)   | 1         | 0.09%   |
| 3000x1920          | 1         | 0.09%   |
| 2960x1050          | 1         | 0.09%   |
| 2624x900           | 1         | 0.09%   |
| 1680x945           | 1         | 0.09%   |
| 1280x768           | 1         | 0.09%   |
| 1024x576           | 1         | 0.09%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 321       | 29.05%  |
| 23      | 86        | 7.78%   |
| 21      | 83        | 7.51%   |
| 17      | 75        | 6.79%   |
| 13      | 69        | 6.24%   |
| 27      | 67        | 6.06%   |
| Unknown | 62        | 5.61%   |
| 14      | 57        | 5.16%   |
| 24      | 54        | 4.89%   |
| 19      | 44        | 3.98%   |
| 18      | 26        | 2.35%   |
| 20      | 24        | 2.17%   |
| 22      | 18        | 1.63%   |
| 34      | 12        | 1.09%   |
| 12      | 12        | 1.09%   |
| 11      | 12        | 1.09%   |
| 31      | 11        | 1%      |
| 84      | 10        | 0.9%    |
| 10      | 10        | 0.9%    |
| 72      | 6         | 0.54%   |
| 54      | 5         | 0.45%   |
| 33      | 5         | 0.45%   |
| 16      | 5         | 0.45%   |
| 32      | 4         | 0.36%   |
| 25      | 4         | 0.36%   |
| 42      | 3         | 0.27%   |
| 8       | 3         | 0.27%   |
| 65      | 2         | 0.18%   |
| 49      | 2         | 0.18%   |
| 47      | 2         | 0.18%   |
| 40      | 2         | 0.18%   |
| 60      | 1         | 0.09%   |
| 48      | 1         | 0.09%   |
| 46      | 1         | 0.09%   |
| 44      | 1         | 0.09%   |
| 39      | 1         | 0.09%   |
| 37      | 1         | 0.09%   |
| 29      | 1         | 0.09%   |
| 28      | 1         | 0.09%   |
| 26      | 1         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 446       | 41.07%  |
| 501-600     | 187       | 17.22%  |
| 401-500     | 168       | 15.47%  |
| 351-400     | 78        | 7.18%   |
| 201-300     | 65        | 5.99%   |
| Unknown     | 62        | 5.71%   |
| 701-800     | 21        | 1.93%   |
| 601-700     | 18        | 1.66%   |
| 1501-2000   | 16        | 1.47%   |
| 1001-1500   | 14        | 1.29%   |
| 801-900     | 4         | 0.37%   |
| 901-1000    | 4         | 0.37%   |
| 101-200     | 3         | 0.28%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 722       | 71.27%  |
| 16/10   | 133       | 13.13%  |
| 5/4     | 53        | 5.23%   |
| Unknown | 53        | 5.23%   |
| 4/3     | 21        | 2.07%   |
| 21/9    | 11        | 1.09%   |
| 6/5     | 9         | 0.89%   |
| 3/2     | 8         | 0.79%   |
| 32/9    | 2         | 0.2%    |
| 0.62    | 1         | 0.1%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 321       | 29.29%  |
| 201-250        | 201       | 18.34%  |
| 81-90          | 102       | 9.31%   |
| 151-200        | 86        | 7.85%   |
| 301-350        | 68        | 6.2%    |
| Unknown        | 62        | 5.66%   |
| 141-150        | 52        | 4.74%   |
| 351-500        | 33        | 3.01%   |
| 121-130        | 33        | 3.01%   |
| More than 1000 | 26        | 2.37%   |
| 71-80          | 24        | 2.19%   |
| 251-300        | 23        | 2.1%    |
| 501-1000       | 13        | 1.19%   |
| 51-60          | 12        | 1.09%   |
| 61-70          | 11        | 1%      |
| 131-140        | 11        | 1%      |
| 41-50          | 10        | 0.91%   |
| 1-40           | 3         | 0.27%   |
| 111-120        | 3         | 0.27%   |
| 91-100         | 2         | 0.18%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 413       | 38.82%  |
| 101-120       | 289       | 27.16%  |
| 121-160       | 237       | 22.27%  |
| Unknown       | 62        | 5.83%   |
| 161-240       | 27        | 2.54%   |
| 1-50          | 25        | 2.35%   |
| More than 240 | 11        | 1.03%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 898       | 82.31%  |
| 2     | 128       | 11.73%  |
| 0     | 52        | 4.77%   |
| 3     | 13        | 1.19%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 617       | 38.81%  |
| Intel                                 | 417       | 26.23%  |
| Qualcomm Atheros                      | 190       | 11.95%  |
| Broadcom                              | 94        | 5.91%   |
| Marvell Technology Group              | 39        | 2.45%   |
| TP-Link                               | 33        | 2.08%   |
| Ralink Technology                     | 32        | 2.01%   |
| Ralink                                | 22        | 1.38%   |
| Broadcom Limited                      | 22        | 1.38%   |
| Nvidia                                | 19        | 1.19%   |
| Qualcomm Atheros Communications       | 10        | 0.63%   |
| MediaTek                              | 10        | 0.63%   |
| VIA Technologies                      | 8         | 0.5%    |
| D-Link                                | 7         | 0.44%   |
| Xiaomi                                | 4         | 0.25%   |
| NetGear                               | 4         | 0.25%   |
| Huawei Technologies                   | 4         | 0.25%   |
| Ericsson Business Mobile Networks     | 4         | 0.25%   |
| Dell                                  | 4         | 0.25%   |
| ASUSTek Computer                      | 4         | 0.25%   |
| Sierra Wireless                       | 3         | 0.19%   |
| JMicron Technology                    | 3         | 0.19%   |
| Hewlett-Packard                       | 3         | 0.19%   |
| Belkin Components                     | 3         | 0.19%   |
| Motorola                              | 2         | 0.13%   |
| Microsoft                             | 2         | 0.13%   |
| Fujitsu Siemens Computers             | 2         | 0.13%   |
| Edimax Technology                     | 2         | 0.13%   |
| D-Link System                         | 2         | 0.13%   |
| ASIX Electronics                      | 2         | 0.13%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.13%   |
| ZyDAS                                 | 1         | 0.06%   |
| U-Blox                                | 1         | 0.06%   |
| Toshiba                               | 1         | 0.06%   |
| Sundance Technology Inc / IC Plus     | 1         | 0.06%   |
| Sitecom Europe                        | 1         | 0.06%   |
| Silicon Integrated Systems [SiS]      | 1         | 0.06%   |
| Samsung Electronics                   | 1         | 0.06%   |
| PCTel                                 | 1         | 0.06%   |
| Ovislink                              | 1         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 401       | 21.9%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 110       | 6.01%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 44        | 2.4%    |
| Intel I211 Gigabit Network Connection                                   | 34        | 1.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 28        | 1.53%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 28        | 1.53%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 27        | 1.47%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 26        | 1.42%   |
| Intel Wireless 8265 / 8275                                              | 25        | 1.37%   |
| Intel Wi-Fi 6 AX200                                                     | 24        | 1.31%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 23        | 1.26%   |
| Intel Ethernet Connection I217-LM                                       | 21        | 1.15%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 19        | 1.04%   |
| Intel Wireless 3165                                                     | 19        | 1.04%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 18        | 0.98%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 18        | 0.98%   |
| Broadcom BCM43142 802.11b/g/n                                           | 18        | 0.98%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 17        | 0.93%   |
| Intel Wireless 7260                                                     | 17        | 0.93%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 16        | 0.87%   |
| Intel Wi-Fi 6 AX201                                                     | 15        | 0.82%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 14        | 0.76%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 13        | 0.71%   |
| Intel Wireless 7265                                                     | 13        | 0.71%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 12        | 0.66%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 12        | 0.66%   |
| Intel Ethernet Connection (2) I219-V                                    | 12        | 0.66%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 12        | 0.66%   |
| Realtek RTL8125 2.5GbE Controller                                       | 11        | 0.6%    |
| Intel Wireless 3160                                                     | 11        | 0.6%    |
| Intel 82567LM-3 Gigabit Network Connection                              | 11        | 0.6%    |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 10        | 0.55%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                         | 10        | 0.55%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 10        | 0.55%   |
| Intel WiFi Link 5100                                                    | 10        | 0.55%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 10        | 0.55%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 10        | 0.55%   |
| Qualcomm Atheros AR9271 802.11n                                         | 9         | 0.49%   |
| Intel Ultimate N WiFi Link 5300                                         | 9         | 0.49%   |
| Intel Centrino Wireless-N 2230                                          | 9         | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 281       | 35.08%  |
| Realtek Semiconductor                 | 165       | 20.6%   |
| Qualcomm Atheros                      | 145       | 18.1%   |
| Broadcom                              | 60        | 7.49%   |
| Ralink Technology                     | 32        | 4%      |
| TP-Link                               | 31        | 3.87%   |
| Ralink                                | 22        | 2.75%   |
| Qualcomm Atheros Communications       | 10        | 1.25%   |
| Broadcom Limited                      | 9         | 1.12%   |
| MediaTek                              | 7         | 0.87%   |
| D-Link                                | 7         | 0.87%   |
| NetGear                               | 4         | 0.5%    |
| ASUSTek Computer                      | 4         | 0.5%    |
| Sierra Wireless                       | 3         | 0.37%   |
| Belkin Components                     | 3         | 0.37%   |
| Microsoft                             | 2         | 0.25%   |
| Hewlett-Packard                       | 2         | 0.25%   |
| Fujitsu Siemens Computers             | 2         | 0.25%   |
| Edimax Technology                     | 2         | 0.25%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.25%   |
| ZyDAS                                 | 1         | 0.12%   |
| Sitecom Europe                        | 1         | 0.12%   |
| Ovislink                              | 1         | 0.12%   |
| Micro Star International              | 1         | 0.12%   |
| Linksys                               | 1         | 0.12%   |
| InProComm                             | 1         | 0.12%   |
| Dell                                  | 1         | 0.12%   |
| Accton Technology                     | 1         | 0.12%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 28        | 3.47%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 28        | 3.47%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 27        | 3.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 26        | 3.23%   |
| Intel Wireless 8265 / 8275                                              | 25        | 3.1%    |
| Intel Wi-Fi 6 AX200                                                     | 24        | 2.98%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 23        | 2.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 19        | 2.36%   |
| Intel Wireless 3165                                                     | 19        | 2.36%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 18        | 2.23%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 18        | 2.23%   |
| Broadcom BCM43142 802.11b/g/n                                           | 18        | 2.23%   |
| Intel Wireless 7260                                                     | 17        | 2.11%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 16        | 1.99%   |
| Intel Wi-Fi 6 AX201                                                     | 15        | 1.86%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 14        | 1.74%   |
| Intel Wireless 7265                                                     | 13        | 1.61%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 12        | 1.49%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 12        | 1.49%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 12        | 1.49%   |
| Intel Wireless 3160                                                     | 11        | 1.36%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 10        | 1.24%   |
| Intel WiFi Link 5100                                                    | 10        | 1.24%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 10        | 1.24%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 10        | 1.24%   |
| Qualcomm Atheros AR9271 802.11n                                         | 9         | 1.12%   |
| Intel Ultimate N WiFi Link 5300                                         | 9         | 1.12%   |
| Intel Centrino Wireless-N 2230                                          | 9         | 1.12%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 8         | 0.99%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 8         | 0.99%   |
| Intel Wireless-AC 9260                                                  | 8         | 0.99%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 8         | 0.99%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 7         | 0.87%   |
| Ralink MT7601U Wireless Adapter                                         | 7         | 0.87%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 7         | 0.87%   |
| Intel Wireless 8260                                                     | 7         | 0.87%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 7         | 0.87%   |
| Intel Centrino Advanced-N 6200                                          | 7         | 0.87%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 0.87%   |
| Realtek RTL8187 Wireless Adapter                                        | 6         | 0.74%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 562       | 56.94%  |
| Intel                             | 219       | 22.19%  |
| Qualcomm Atheros                  | 61        | 6.18%   |
| Broadcom                          | 40        | 4.05%   |
| Marvell Technology Group          | 39        | 3.95%   |
| Nvidia                            | 19        | 1.93%   |
| Broadcom Limited                  | 16        | 1.62%   |
| VIA Technologies                  | 7         | 0.71%   |
| Xiaomi                            | 4         | 0.41%   |
| JMicron Technology                | 3         | 0.3%    |
| TP-Link                           | 2         | 0.2%    |
| MediaTek                          | 2         | 0.2%    |
| Huawei Technologies               | 2         | 0.2%    |
| D-Link System                     | 2         | 0.2%    |
| ASIX Electronics                  | 2         | 0.2%    |
| Sundance Technology Inc / IC Plus | 1         | 0.1%    |
| Silicon Integrated Systems [SiS]  | 1         | 0.1%    |
| Samsung Electronics               | 1         | 0.1%    |
| IBM                               | 1         | 0.1%    |
| DisplayLink                       | 1         | 0.1%    |
| Attansic Technology               | 1         | 0.1%    |
| Aquantia                          | 1         | 0.1%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 401       | 40.1%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 110       | 11%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 44        | 4.4%    |
| Intel I211 Gigabit Network Connection                             | 34        | 3.4%    |
| Intel Ethernet Connection I217-LM                                 | 21        | 2.1%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 17        | 1.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 13        | 1.3%    |
| Intel Ethernet Connection (2) I219-V                              | 12        | 1.2%    |
| Realtek RTL8125 2.5GbE Controller                                 | 11        | 1.1%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 11        | 1.1%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 10        | 1%      |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 10        | 1%      |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 8         | 0.8%    |
| Intel Ethernet Connection (2) I218-V                              | 8         | 0.8%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 7         | 0.7%    |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 7         | 0.7%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 6         | 0.6%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 6         | 0.6%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 6         | 0.6%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 6         | 0.6%    |
| Intel Ethernet Connection I217-V                                  | 6         | 0.6%    |
| Intel Ethernet Connection (4) I219-LM                             | 6         | 0.6%    |
| Intel 82567LM Gigabit Network Connection                          | 6         | 0.6%    |
| VIA VT6102/VT6103 [Rhine-II]                                      | 5         | 0.5%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 5         | 0.5%    |
| Nvidia MCP61 Ethernet                                             | 5         | 0.5%    |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 5         | 0.5%    |
| Intel Ethernet Connection (2) I219-LM                             | 5         | 0.5%    |
| Intel 82577LM Gigabit Network Connection                          | 5         | 0.5%    |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 5         | 0.5%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 5         | 0.5%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 4         | 0.4%    |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 4         | 0.4%    |
| Nvidia MCP77 Ethernet                                             | 4         | 0.4%    |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 4         | 0.4%    |
| Intel Ethernet Connection I218-LM                                 | 4         | 0.4%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 0.4%    |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 4         | 0.4%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 0.3%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 0.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 957       | 55.48%  |
| WiFi     | 743       | 43.07%  |
| Modem    | 25        | 1.45%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 581       | 52.91%  |
| Ethernet | 517       | 47.09%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 546       | 51.03%  |
| 1     | 482       | 45.05%  |
| 0     | 25        | 2.34%   |
| 3     | 14        | 1.31%   |
| 4     | 3         | 0.28%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 849       | 77.53%  |
| Yes  | 246       | 22.47%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 181       | 33.64%  |
| Realtek Semiconductor           | 72        | 13.38%  |
| Qualcomm Atheros Communications | 52        | 9.67%   |
| Cambridge Silicon Radio         | 49        | 9.11%   |
| Broadcom                        | 35        | 6.51%   |
| IMC Networks                    | 23        | 4.28%   |
| Foxconn / Hon Hai               | 19        | 3.53%   |
| Toshiba                         | 16        | 2.97%   |
| Lite-On Technology              | 14        | 2.6%    |
| Hewlett-Packard                 | 14        | 2.6%    |
| Apple                           | 11        | 2.04%   |
| Ralink                          | 8         | 1.49%   |
| Foxconn International           | 6         | 1.12%   |
| ASUSTek Computer                | 6         | 1.12%   |
| Alps Electric                   | 6         | 1.12%   |
| Realtek                         | 5         | 0.93%   |
| Dell                            | 5         | 0.93%   |
| Ralink Technology               | 4         | 0.74%   |
| Askey Computer                  | 4         | 0.74%   |
| Micro Star International        | 2         | 0.37%   |
| Syntek                          | 1         | 0.19%   |
| Mobile Action Technology        | 1         | 0.19%   |
| Integrated System Solution      | 1         | 0.19%   |
| Edimax Technology               | 1         | 0.19%   |
| Chicony Electronics             | 1         | 0.19%   |
| Belkin Components               | 1         | 0.19%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 85        | 15.8%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 49        | 9.11%   |
| Realtek Bluetooth Radio                             | 42        | 7.81%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 25        | 4.65%   |
| Qualcomm Atheros  Bluetooth Device                  | 24        | 4.46%   |
| Intel AX201 Bluetooth                               | 22        | 4.09%   |
| Intel AX200 Bluetooth                               | 22        | 4.09%   |
| Realtek  Bluetooth 4.2 Adapter                      | 19        | 3.53%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 9         | 1.67%   |
| IMC Networks Bluetooth Radio                        | 9         | 1.67%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 9         | 1.67%   |
| Realtek RTL8723B Bluetooth                          | 8         | 1.49%   |
| Ralink RT3290 Bluetooth                             | 8         | 1.49%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 8         | 1.49%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 8         | 1.49%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 8         | 1.49%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 7         | 1.3%    |
| Intel Wireless-AC 3168 Bluetooth                    | 7         | 1.3%    |
| Foxconn International BCM43142A0 Bluetooth module   | 6         | 1.12%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 6         | 1.12%   |
| Toshiba RT Bluetooth Radio                          | 5         | 0.93%   |
| Toshiba Bluetooth Device                            | 5         | 0.93%   |
| Realtek Bluetooth Radio                             | 5         | 0.93%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 5         | 0.93%   |
| IMC Networks Bluetooth Device                       | 5         | 0.93%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 5         | 0.93%   |
| Apple Bluetooth Host Controller                     | 5         | 0.93%   |
| Qualcomm Atheros Bluetooth                          | 4         | 0.74%   |
| Lite-On Bluetooth Device                            | 4         | 0.74%   |
| HP Broadcom 2070 Bluetooth Combo                    | 4         | 0.74%   |
| Foxconn / Hon Hai Bluetooth Device                  | 4         | 0.74%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 4         | 0.74%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 0.74%   |
| Askey Bluetooth Device                              | 4         | 0.74%   |
| Realtek RTL8723A Bluetooth                          | 3         | 0.56%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 3         | 0.56%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 3         | 0.56%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 3         | 0.56%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 3         | 0.56%   |
| Dell DW375 Bluetooth Module                         | 3         | 0.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 727       | 50.7%   |
| AMD                                             | 350       | 24.41%  |
| Nvidia                                          | 226       | 15.76%  |
| C-Media Electronics                             | 24        | 1.67%   |
| Creative Labs                                   | 13        | 0.91%   |
| Creative Technology                             | 9         | 0.63%   |
| Logitech                                        | 8         | 0.56%   |
| VIA Technologies                                | 6         | 0.42%   |
| Razer USA                                       | 6         | 0.42%   |
| Barco Display Systems                           | 6         | 0.42%   |
| Focusrite-Novation                              | 4         | 0.28%   |
| BEHRINGER International                         | 4         | 0.28%   |
| Texas Instruments                               | 3         | 0.21%   |
| Kingston Technology                             | 3         | 0.21%   |
| GN Netcom                                       | 3         | 0.21%   |
| Nordic Semiconductor ASA                        | 2         | 0.14%   |
| Hewlett-Packard                                 | 2         | 0.14%   |
| Guillemot                                       | 2         | 0.14%   |
| Ensoniq                                         | 2         | 0.14%   |
| Edifier Technology                              | 2         | 0.14%   |
| Cooler Master                                   | 2         | 0.14%   |
| AudioQuest                                      | 2         | 0.14%   |
| Altec Lansing Technologies                      | 2         | 0.14%   |
| Yamaha                                          | 1         | 0.07%   |
| Trust                                           | 1         | 0.07%   |
| Tenx Technology                                 | 1         | 0.07%   |
| SteelSeries ApS                                 | 1         | 0.07%   |
| Silicon Integrated Systems [SiS]                | 1         | 0.07%   |
| Shenzhen Riitek Technology                      | 1         | 0.07%   |
| RODE Microphones                                | 1         | 0.07%   |
| Realtek Semiconductor                           | 1         | 0.07%   |
| Plantronics                                     | 1         | 0.07%   |
| Numark                                          | 1         | 0.07%   |
| Native Instruments                              | 1         | 0.07%   |
| Mark of the Unicorn                             | 1         | 0.07%   |
| M-Audio                                         | 1         | 0.07%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.07%   |
| Lenovo                                          | 1         | 0.07%   |
| JMTek                                           | 1         | 0.07%   |
| iCreate Technologies                            | 1         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 96        | 5.54%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 70        | 4.04%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 68        | 3.92%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 62        | 3.58%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 61        | 3.52%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 57        | 3.29%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 53        | 3.06%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 51        | 2.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 50        | 2.89%   |
| Intel Sunrise Point-LP HD Audio                                            | 49        | 2.83%   |
| AMD FCH Azalia Controller                                                  | 40        | 2.31%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 40        | 2.31%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 37        | 2.14%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 33        | 1.9%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 33        | 1.9%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 30        | 1.73%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 28        | 1.62%   |
| Nvidia GP107GL High Definition Audio Controller                            | 26        | 1.5%    |
| Intel Haswell-ULT HD Audio Controller                                      | 25        | 1.44%   |
| Intel Cannon Lake PCH cAVS                                                 | 25        | 1.44%   |
| Intel 8 Series HD Audio Controller                                         | 25        | 1.44%   |
| AMD Starship/Matisse HD Audio Controller                                   | 22        | 1.27%   |
| Nvidia High Definition Audio Controller                                    | 19        | 1.1%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 19        | 1.1%    |
| Nvidia GF108 High Definition Audio Controller                              | 18        | 1.04%   |
| Intel 200 Series PCH HD Audio                                              | 18        | 1.04%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 18        | 1.04%   |
| AMD Kabini HDMI/DP Audio                                                   | 18        | 1.04%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 17        | 0.98%   |
| Intel Broadwell-U Audio Controller                                         | 15        | 0.87%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 15        | 0.87%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 15        | 0.87%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 14        | 0.81%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 14        | 0.81%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 14        | 0.81%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 14        | 0.81%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 13        | 0.75%   |
| Nvidia GP106 High Definition Audio Controller                              | 12        | 0.69%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 12        | 0.69%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 12        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 99        | 17.81%  |
| SK hynix            | 93        | 16.73%  |
| Unknown             | 81        | 14.57%  |
| Kingston            | 71        | 12.77%  |
| Micron Technology   | 44        | 7.91%   |
| G.Skill             | 37        | 6.65%   |
| Corsair             | 35        | 6.29%   |
| Crucial             | 32        | 5.76%   |
| Ramaxel Technology  | 11        | 1.98%   |
| Transcend           | 8         | 1.44%   |
| Elpida              | 8         | 1.44%   |
| Team                | 6         | 1.08%   |
| Nanya Technology    | 5         | 0.9%    |
| Unknown (ABCD)      | 4         | 0.72%   |
| A-DATA Technology   | 4         | 0.72%   |
| Goodram             | 3         | 0.54%   |
| Apacer              | 3         | 0.54%   |
| Patriot             | 2         | 0.36%   |
| Unknown             | 2         | 0.36%   |
| Veineda             | 1         | 0.18%   |
| Toshiba             | 1         | 0.18%   |
| Silicon Power       | 1         | 0.18%   |
| Qimonda             | 1         | 0.18%   |
| Infineon            | 1         | 0.18%   |
| HMD                 | 1         | 0.18%   |
| H                   | 1         | 0.18%   |
| Goldkey             | 1         | 0.18%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s              | 9         | 1.46%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 1.3%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 1.14%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 6         | 0.98%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.98%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 5         | 0.81%   |
| Unknown RAM Module 1024MB DIMM SDRAM                             | 5         | 0.81%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 0.81%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 0.81%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.81%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 4         | 0.65%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 4         | 0.65%   |
| Unknown RAM Module 2048MB DIMM DDR 533MT/s                       | 4         | 0.65%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 4         | 0.65%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 0.65%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 0.65%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 0.65%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 0.65%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 4         | 0.65%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s      | 4         | 0.65%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s              | 4         | 0.65%   |
| Unknown RAM Module 512MB DIMM SDRAM                              | 3         | 0.49%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 3         | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 3         | 0.49%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 3         | 0.49%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 3         | 0.49%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 3         | 0.49%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                           | 3         | 0.49%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.49%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 0.49%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 3         | 0.49%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 3         | 0.49%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.49%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 3         | 0.49%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 0.49%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s             | 3         | 0.49%   |
| G.Skill RAM F4-3200C14-8GFX 8GB DIMM DDR4 3733MT/s               | 3         | 0.49%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s          | 3         | 0.49%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s              | 3         | 0.49%   |
| Corsair RAM CMZ4GX3M1A1600C9 4096MB DIMM DDR3 1600MT/s           | 3         | 0.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 190       | 39.5%   |
| DDR3    | 164       | 34.1%   |
| DDR2    | 41        | 8.52%   |
| Unknown | 31        | 6.44%   |
| SDRAM   | 20        | 4.16%   |
| DDR     | 14        | 2.91%   |
| LPDDR4  | 12        | 2.49%   |
| LPDDR3  | 5         | 1.04%   |
| DRAM    | 2         | 0.42%   |
| DDR5    | 2         | 0.42%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 247       | 52.33%  |
| DIMM         | 206       | 43.64%  |
| Row Of Chips | 18        | 3.81%   |
| Unknown      | 1         | 0.21%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 175       | 33.21%  |
| 4096  | 157       | 29.79%  |
| 2048  | 101       | 19.17%  |
| 16384 | 46        | 8.73%   |
| 1024  | 36        | 6.83%   |
| 512   | 9         | 1.71%   |
| 32768 | 2         | 0.38%   |
| 256   | 1         | 0.19%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 107       | 20.38%  |
| 2667    | 60        | 11.43%  |
| 3200    | 57        | 10.86%  |
| 2400    | 38        | 7.24%   |
| 1333    | 36        | 6.86%   |
| 667     | 24        | 4.57%   |
| Unknown | 23        | 4.38%   |
| 800     | 21        | 4%      |
| 2133    | 20        | 3.81%   |
| 1334    | 15        | 2.86%   |
| 3600    | 14        | 2.67%   |
| 1066    | 12        | 2.29%   |
| 533     | 10        | 1.9%    |
| 3866    | 9         | 1.71%   |
| 1067    | 9         | 1.71%   |
| 2933    | 8         | 1.52%   |
| 3266    | 6         | 1.14%   |
| 3400    | 5         | 0.95%   |
| 400     | 5         | 0.95%   |
| 4267    | 4         | 0.76%   |
| 3733    | 4         | 0.76%   |
| 3000    | 4         | 0.76%   |
| 1867    | 4         | 0.76%   |
| 1866    | 4         | 0.76%   |
| 4199    | 3         | 0.57%   |
| 333     | 3         | 0.57%   |
| 4800    | 2         | 0.38%   |
| 3007    | 2         | 0.38%   |
| 2733    | 2         | 0.38%   |
| 2666    | 2         | 0.38%   |
| 2048    | 2         | 0.38%   |
| 1800    | 2         | 0.38%   |
| 49926   | 1         | 0.19%   |
| 3466    | 1         | 0.19%   |
| 3334    | 1         | 0.19%   |
| 3333    | 1         | 0.19%   |
| 2800    | 1         | 0.19%   |
| 1639    | 1         | 0.19%   |
| 975     | 1         | 0.19%   |
| 200     | 1         | 0.19%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 27        | 60%     |
| Canon               | 7         | 15.56%  |
| Samsung Electronics | 6         | 13.33%  |
| Seiko Epson         | 1         | 2.22%   |
| Ricoh               | 1         | 2.22%   |
| Oki Data            | 1         | 2.22%   |
| Konica Minolta      | 1         | 2.22%   |
| Brother Industries  | 1         | 2.22%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung M2020 Series                 | 4         | 8.89%   |
| Canon TS3100 series                  | 3         | 6.67%   |
| HP LaserJet P1102                    | 2         | 4.44%   |
| HP DeskJet 3830 series               | 2         | 4.44%   |
| Seiko Epson L312 Series              | 1         | 2.22%   |
| Samsung SCX-3400 Series              | 1         | 2.22%   |
| Samsung M2070 Series                 | 1         | 2.22%   |
| Ricoh SP 112SU                       | 1         | 2.22%   |
| Oki Data USB Device                  | 1         | 2.22%   |
| Konica Minolta magicolor 1680MF scan | 1         | 2.22%   |
| HP Smart Tank 510 series             | 1         | 2.22%   |
| HP Officejet Pro L7400               | 1         | 2.22%   |
| HP OfficeJet Pro 8020 series         | 1         | 2.22%   |
| HP Officejet J4500 series            | 1         | 2.22%   |
| HP OfficeJet 6200                    | 1         | 2.22%   |
| HP Officejet 4500 G510g-m            | 1         | 2.22%   |
| HP LaserJet P1005                    | 1         | 2.22%   |
| HP LaserJet 1020                     | 1         | 2.22%   |
| HP LaserJet 1018                     | 1         | 2.22%   |
| HP LaserJet 1010                     | 1         | 2.22%   |
| HP Laser 107a                        | 1         | 2.22%   |
| HP DeskJet F300 series               | 1         | 2.22%   |
| HP DeskJet F2492 All-in-One          | 1         | 2.22%   |
| HP DeskJet D2300                     | 1         | 2.22%   |
| HP DeskJet 930c                      | 1         | 2.22%   |
| HP DeskJet 840c                      | 1         | 2.22%   |
| HP DeskJet 4670 series               | 1         | 2.22%   |
| HP DeskJet 4530 series               | 1         | 2.22%   |
| HP DeskJet 4100 series               | 1         | 2.22%   |
| HP DeskJet 3700 series               | 1         | 2.22%   |
| HP Deskjet 2640 series               | 1         | 2.22%   |
| HP DeskJet 2620 All-in-One Printer   | 1         | 2.22%   |
| HP Color Laser 150nw                 | 1         | 2.22%   |
| Canon TR4500 series                  | 1         | 2.22%   |
| Canon PIXMA MX390 Series             | 1         | 2.22%   |
| Canon PIXMA MG5500 Series            | 1         | 2.22%   |
| Canon MG5600 series                  | 1         | 2.22%   |
| Brother HL-2030 Laser Printer        | 1         | 2.22%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 3         | 50%     |
| Seiko Epson     | 1         | 16.67%  |
| Mustek Systems  | 1         | 16.67%  |
| Hewlett-Packard | 1         | 16.67%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X800 [Perfection 4990 PHOTO] | 1         | 16.67%  |
| Mustek Systems BearPaw 1200 CU Plus         | 1         | 16.67%  |
| HP ScanJet 4370                             | 1         | 16.67%  |
| Canon CanoScan LiDE 220                     | 1         | 16.67%  |
| Canon CanoScan LiDE 110                     | 1         | 16.67%  |
| Canon CanoScan LiDE 100                     | 1         | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 123       | 19.74%  |
| IMC Networks                           | 57        | 9.15%   |
| Realtek Semiconductor                  | 52        | 8.35%   |
| Microdia                               | 52        | 8.35%   |
| Logitech                               | 45        | 7.22%   |
| Acer                                   | 41        | 6.58%   |
| Suyin                                  | 32        | 5.14%   |
| Cheng Uei Precision Industry (Foxlink) | 24        | 3.85%   |
| Sunplus Innovation Technology          | 23        | 3.69%   |
| Quanta                                 | 18        | 2.89%   |
| Microsoft                              | 16        | 2.57%   |
| Ricoh                                  | 15        | 2.41%   |
| Syntek                                 | 13        | 2.09%   |
| Lite-On Technology                     | 13        | 2.09%   |
| Alcor Micro                            | 13        | 2.09%   |
| Apple                                  | 9         | 1.44%   |
| Generalplus Technology                 | 8         | 1.28%   |
| Z-Star Microelectronics                | 7         | 1.12%   |
| Silicon Motion                         | 6         | 0.96%   |
| Luxvisions Innotech Limited            | 5         | 0.8%    |
| Creative Technology                    | 5         | 0.8%    |
| Arkmicro Technologies                  | 5         | 0.8%    |
| Samsung Electronics                    | 4         | 0.64%   |
| Lenovo                                 | 4         | 0.64%   |
| Aveo Technology                        | 4         | 0.64%   |
| Philips (or NXP)                       | 3         | 0.48%   |
| Sonix Technology                       | 2         | 0.32%   |
| Razer USA                              | 2         | 0.32%   |
| Pixart Imaging                         | 2         | 0.32%   |
| Importek                               | 2         | 0.32%   |
| Genesys Logic                          | 2         | 0.32%   |
| ALi                                    | 2         | 0.32%   |
| Xiongmai                               | 1         | 0.16%   |
| Sweex                                  | 1         | 0.16%   |
| Primax Electronics                     | 1         | 0.16%   |
| OmniVision Technologies                | 1         | 0.16%   |
| Nokia Mobile Phones                    | 1         | 0.16%   |
| MacroSilicon                           | 1         | 0.16%   |
| Leap Motion                            | 1         | 0.16%   |
| Jieli Technology                       | 1         | 0.16%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                        | 20        | 3.19%   |
| Microdia Integrated_Webcam_HD                       | 18        | 2.88%   |
| Chicony Integrated Camera                           | 18        | 2.88%   |
| Logitech Webcam C270                                | 16        | 2.56%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 15        | 2.4%    |
| IMC Networks Integrated Camera                      | 14        | 2.24%   |
| Chicony HP Truevision HD                            | 12        | 1.92%   |
| Realtek USB Camera                                  | 9         | 1.44%   |
| Sunplus Integrated_Webcam_HD                        | 8         | 1.28%   |
| Acer Lenovo EasyCamera                              | 8         | 1.28%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 7         | 1.12%   |
| Chicony TOSHIBA Web Camera - HD                     | 7         | 1.12%   |
| Chicony HP Webcam                                   | 7         | 1.12%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 7         | 1.12%   |
| Acer BisonCam, NB Pro                               | 7         | 1.12%   |
| Syntek Integrated Camera                            | 6         | 0.96%   |
| Microsoft LifeCam HD-3000                           | 6         | 0.96%   |
| Chicony USB 2.0 Camera                              | 6         | 0.96%   |
| Suyin Integrated_Webcam_HD                          | 5         | 0.8%    |
| Realtek Lenovo EasyCamera                           | 5         | 0.8%    |
| Quanta VGA WebCam                                   | 5         | 0.8%    |
| Microdia Camera                                     | 5         | 0.8%    |
| Logitech HD Pro Webcam C920                         | 5         | 0.8%    |
| Chicony USB2.0 VGA UVC WebCam                       | 5         | 0.8%    |
| Chicony Integrated Camera (1280x720@30)             | 5         | 0.8%    |
| Chicony HD WebCam                                   | 5         | 0.8%    |
| Alcor Micro USB 2.0 Camera                          | 5         | 0.8%    |
| Z-Star Venus USB2.0 Camera                          | 4         | 0.64%   |
| Samsung Galaxy series, misc. (MTP mode)             | 4         | 0.64%   |
| Ricoh Visual Communication Camera VGP-VCC6 [R5U870] | 4         | 0.64%   |
| Realtek USB2.0 HD UVC WebCam                        | 4         | 0.64%   |
| Realtek Integrated Webcam                           | 4         | 0.64%   |
| Quanta HP TrueVision HD Camera                      | 4         | 0.64%   |
| Microdia Laptop_Integrated_Webcam_HD                | 4         | 0.64%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 4         | 0.64%   |
| Logitech Webcam C310                                | 4         | 0.64%   |
| Logitech Webcam C300                                | 4         | 0.64%   |
| IMC Networks ov9734_azurewave_camera                | 4         | 0.64%   |
| IMC Networks EasyCamera                             | 4         | 0.64%   |
| Generalplus GENERAL WEBCAM                          | 4         | 0.64%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 24        | 29.63%  |
| Synaptics                  | 17        | 20.99%  |
| AuthenTec                  | 13        | 16.05%  |
| Upek                       | 11        | 13.58%  |
| Shenzhen Goodix Technology | 11        | 13.58%  |
| Elan Microelectronics      | 3         | 3.7%    |
| STMicroelectronics         | 1         | 1.23%   |
| LighTuning Technology      | 1         | 1.23%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 10        | 12.35%  |
| Shenzhen Goodix  Fingerprint Device                                        | 7         | 8.64%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 7         | 8.64%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 6         | 7.41%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 6.17%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 5         | 6.17%   |
| Synaptics  WBDI                                                            | 4         | 4.94%   |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 4.94%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 3.7%    |
| Elan ELAN:ARM-M4                                                           | 3         | 3.7%    |
| AuthenTec AES2810                                                          | 3         | 3.7%    |
| Unknown                                                                    | 3         | 3.7%    |
| Validity Sensors VFS491                                                    | 2         | 2.47%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 2.47%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 2.47%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 2.47%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 2.47%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 1.23%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 1.23%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 1.23%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 1.23%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 1.23%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.23%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 1.23%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 1.23%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 1.23%   |
| LighTuning Fingerprint Reader                                              | 1         | 1.23%   |
| AuthenTec AES1600                                                          | 1         | 1.23%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 24        | 60%     |
| Alcor Micro | 7         | 17.5%   |
| O2 Micro    | 4         | 10%     |
| Upek        | 2         | 5%      |
| Lenovo      | 2         | 5%      |
| Yubico.com  | 1         | 2.5%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 58200                                                               | 10        | 25%     |
| Broadcom BCM5880 Secure Applications Processor                               | 9         | 22.5%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 7         | 17.5%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 10%     |
| Broadcom 5880                                                                | 3         | 7.5%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 5%      |
| Lenovo Integrated Smart Card Reader                                          | 2         | 5%      |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 5%      |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 2.5%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 799       | 73.17%  |
| 1     | 240       | 21.98%  |
| 2     | 42        | 3.85%   |
| 3     | 7         | 0.64%   |
| 6     | 2         | 0.18%   |
| 4     | 2         | 0.18%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 81        | 23.41%  |
| Graphics card            | 69        | 19.94%  |
| Net/wireless             | 54        | 15.61%  |
| Chipcard                 | 36        | 10.4%   |
| Multimedia controller    | 22        | 6.36%   |
| Bluetooth                | 19        | 5.49%   |
| Communication controller | 13        | 3.76%   |
| Camera                   | 9         | 2.6%    |
| Sound                    | 8         | 2.31%   |
| Modem                    | 7         | 2.02%   |
| Storage                  | 5         | 1.45%   |
| Flash memory             | 4         | 1.16%   |
| Dvb card                 | 4         | 1.16%   |
| Card reader              | 4         | 1.16%   |
| Net/ethernet             | 3         | 0.87%   |
| Unassigned class         | 2         | 0.58%   |
| Network                  | 2         | 0.58%   |
| Firewire controller      | 2         | 0.58%   |
| Tv card                  | 1         | 0.29%   |
| Storage/raid             | 1         | 0.29%   |

