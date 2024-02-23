Linux in Spain - Tested Hardware & Statistics
---------------------------------------------

A project to collect tested hardware configurations for Linux in Spain.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Spain/Desktop/README.md) and [notebooks](/Location/Spain/Notebook/README.md).

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

Total: 9216

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | M4N72-E                     | Desktop     | [815b251540](https://linux-hardware.org/?probe=815b251540) | Feb 02, 2024 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [ef41c12950](https://linux-hardware.org/?probe=ef41c12950) | Feb 02, 2024 |
| Intel         | X99-P4 V5.1                 | Desktop     | [092e51b68e](https://linux-hardware.org/?probe=092e51b68e) | Feb 02, 2024 |
| Unknown       | Unknown                     | Notebook    | [8c03bd946c](https://linux-hardware.org/?probe=8c03bd946c) | Feb 02, 2024 |
| Gigabyte      | H61M-S1                     | Desktop     | [e7f247621c](https://linux-hardware.org/?probe=e7f247621c) | Feb 02, 2024 |
| Apple         | Mac-F4218FC8 DVT            | All in one  | [7e9ecedb98](https://linux-hardware.org/?probe=7e9ecedb98) | Feb 02, 2024 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [0bbbc51a52](https://linux-hardware.org/?probe=0bbbc51a52) | Feb 02, 2024 |
| SLIMBOOK      | HERO-S-TGL-RTX              | Notebook    | [1260457422](https://linux-hardware.org/?probe=1260457422) | Feb 02, 2024 |
| Apple         | MacBookAir5,1               | Notebook    | [e25bf95ccb](https://linux-hardware.org/?probe=e25bf95ccb) | Feb 02, 2024 |
| Apple         | MacBookAir5,1               | Notebook    | [058a447435](https://linux-hardware.org/?probe=058a447435) | Feb 02, 2024 |
| ASUSTek       | H110M-D                     | Desktop     | [287648c7d3](https://linux-hardware.org/?probe=287648c7d3) | Feb 01, 2024 |
| Apple         | Mac-F4218FC8 DVT            | All in one  | [9b97e0a028](https://linux-hardware.org/?probe=9b97e0a028) | Feb 01, 2024 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [f0b3157a23](https://linux-hardware.org/?probe=f0b3157a23) | Feb 01, 2024 |
| ASRock        | X370M-HDV                   | Desktop     | [64edf5f2dc](https://linux-hardware.org/?probe=64edf5f2dc) | Feb 01, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JTC... | Notebook    | [e91ff8608c](https://linux-hardware.org/?probe=e91ff8608c) | Jan 31, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [3f6fe6218f](https://linux-hardware.org/?probe=3f6fe6218f) | Jan 31, 2024 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | Notebook    | [9c0cf210c3](https://linux-hardware.org/?probe=9c0cf210c3) | Jan 31, 2024 |
| Dell          | Latitude E5410              | Notebook    | [d91781267c](https://linux-hardware.org/?probe=d91781267c) | Jan 31, 2024 |
| HP            | Pavilion Laptop 15-ck0xx    | Notebook    | [573d69639e](https://linux-hardware.org/?probe=573d69639e) | Jan 31, 2024 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [e26a562041](https://linux-hardware.org/?probe=e26a562041) | Jan 30, 2024 |
| Acer          | Nitro AN515-54              | Notebook    | [51116cec97](https://linux-hardware.org/?probe=51116cec97) | Jan 30, 2024 |
| Acer          | Nitro AN515-54              | Notebook    | [3b5313811c](https://linux-hardware.org/?probe=3b5313811c) | Jan 30, 2024 |
| Toshiba       | NB250                       | Notebook    | [f6694e7f86](https://linux-hardware.org/?probe=f6694e7f86) | Jan 30, 2024 |
| Toshiba       | NB250                       | Notebook    | [635c466f5f](https://linux-hardware.org/?probe=635c466f5f) | Jan 30, 2024 |
| Gigabyte      | B75M-D3H                    | Desktop     | [b1b2694b98](https://linux-hardware.org/?probe=b1b2694b98) | Jan 30, 2024 |
| ASUSTek       | ROG Maximus Z790 DARK HE... | Desktop     | [64433c2a96](https://linux-hardware.org/?probe=64433c2a96) | Jan 29, 2024 |
| HP            | ProBook 640 G1              | Notebook    | [7bbe891072](https://linux-hardware.org/?probe=7bbe891072) | Jan 29, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [3819e0c97d](https://linux-hardware.org/?probe=3819e0c97d) | Jan 29, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [0bba02c4c8](https://linux-hardware.org/?probe=0bba02c4c8) | Jan 29, 2024 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [907099b1e7](https://linux-hardware.org/?probe=907099b1e7) | Jan 29, 2024 |
| ASUSTek       | N550JK                      | Notebook    | [097f96652f](https://linux-hardware.org/?probe=097f96652f) | Jan 29, 2024 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | Desktop     | [29fcd258c7](https://linux-hardware.org/?probe=29fcd258c7) | Jan 28, 2024 |
| Acer          | Nitro AN515-58              | Notebook    | [20b00f9064](https://linux-hardware.org/?probe=20b00f9064) | Jan 28, 2024 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [21e149d013](https://linux-hardware.org/?probe=21e149d013) | Jan 28, 2024 |
| Acer          | Aspire M3-581G              | Notebook    | [b91416ad7c](https://linux-hardware.org/?probe=b91416ad7c) | Jan 28, 2024 |
| ASRock        | Z690 Phantom Gaming-ITX/... | Desktop     | [fe3286f6e5](https://linux-hardware.org/?probe=fe3286f6e5) | Jan 28, 2024 |
| MSI           | Modern 15 H B13M            | Notebook    | [53eae9905c](https://linux-hardware.org/?probe=53eae9905c) | Jan 27, 2024 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [26c552f089](https://linux-hardware.org/?probe=26c552f089) | Jan 27, 2024 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [96bce63bad](https://linux-hardware.org/?probe=96bce63bad) | Jan 27, 2024 |
| Dell          | Inspiron 5405               | Notebook    | [c9256b244b](https://linux-hardware.org/?probe=c9256b244b) | Jan 27, 2024 |
| Acer          | Aspire A315-58              | Notebook    | [c85674acbd](https://linux-hardware.org/?probe=c85674acbd) | Jan 26, 2024 |
| Gigabyte      | AX370-Gaming 5              | Desktop     | [579b4a4daa](https://linux-hardware.org/?probe=579b4a4daa) | Jan 26, 2024 |
| ASUSTek       | ROG Maximus Z790 DARK HE... | Desktop     | [aa9e38d0e2](https://linux-hardware.org/?probe=aa9e38d0e2) | Jan 26, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [516ae40374](https://linux-hardware.org/?probe=516ae40374) | Jan 25, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [c0bdeb8655](https://linux-hardware.org/?probe=c0bdeb8655) | Jan 25, 2024 |
| Sony          | VPCEB3B4E                   | Notebook    | [afa1b50b5a](https://linux-hardware.org/?probe=afa1b50b5a) | Jan 25, 2024 |
| Lenovo        | IdeaPad Pro 5 14IMH9 83D... | Notebook    | [2915b21d64](https://linux-hardware.org/?probe=2915b21d64) | Jan 25, 2024 |
| MSI           | B560M PRO-VDH               | Desktop     | [e64338286f](https://linux-hardware.org/?probe=e64338286f) | Jan 24, 2024 |
| Dell          | 00V62H A01                  | Desktop     | [83f7e8b344](https://linux-hardware.org/?probe=83f7e8b344) | Jan 24, 2024 |
| Lenovo        | ThinkPad X1 Carbon 34604... | Notebook    | [8add6b9229](https://linux-hardware.org/?probe=8add6b9229) | Jan 24, 2024 |
| MSI           | Modern 15 B7M               | Notebook    | [f04098f192](https://linux-hardware.org/?probe=f04098f192) | Jan 23, 2024 |
| MSI           | Modern 15 B7M               | Notebook    | [1caccbdf16](https://linux-hardware.org/?probe=1caccbdf16) | Jan 23, 2024 |
| Intel         | Unknown                     | Desktop     | [8427ffd0dc](https://linux-hardware.org/?probe=8427ffd0dc) | Jan 23, 2024 |
| AZW           | Z83 V                       | Notebook    | [eed16e1e68](https://linux-hardware.org/?probe=eed16e1e68) | Jan 23, 2024 |
| AZW           | Z83 V                       | Notebook    | [b9b8c82621](https://linux-hardware.org/?probe=b9b8c82621) | Jan 23, 2024 |
| HP            | 0A5Ch                       | Desktop     | [f886596563](https://linux-hardware.org/?probe=f886596563) | Jan 23, 2024 |
| Unknown       | Unknown                     | Notebook    | [dd7b17439f](https://linux-hardware.org/?probe=dd7b17439f) | Jan 22, 2024 |
| MSI           | B350M MORTAR                | Desktop     | [f728e7ad76](https://linux-hardware.org/?probe=f728e7ad76) | Jan 22, 2024 |
| Acer          | TravelMate B115-M           | Notebook    | [e91da1c312](https://linux-hardware.org/?probe=e91da1c312) | Jan 22, 2024 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [ed85e4518e](https://linux-hardware.org/?probe=ed85e4518e) | Jan 22, 2024 |
| ASUSTek       | B85M-G                      | Desktop     | [3941eb54fd](https://linux-hardware.org/?probe=3941eb54fd) | Jan 21, 2024 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [3ae3d26304](https://linux-hardware.org/?probe=3ae3d26304) | Jan 21, 2024 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [248ddfc03e](https://linux-hardware.org/?probe=248ddfc03e) | Jan 21, 2024 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [5e268775c9](https://linux-hardware.org/?probe=5e268775c9) | Jan 21, 2024 |
| Foxconn       | 2A8C                        | Desktop     | [591fafe62b](https://linux-hardware.org/?probe=591fafe62b) | Jan 21, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [871f86a545](https://linux-hardware.org/?probe=871f86a545) | Jan 21, 2024 |
| Dell          | 00V62H A01                  | Desktop     | [7104f7e7cf](https://linux-hardware.org/?probe=7104f7e7cf) | Jan 21, 2024 |
| Lenovo        | Yoga 510-14ISK 80S7         | Convertible | [ba8ae9ea01](https://linux-hardware.org/?probe=ba8ae9ea01) | Jan 21, 2024 |
| Apple         | MacBookPro11,5              | Notebook    | [f3fe3777b0](https://linux-hardware.org/?probe=f3fe3777b0) | Jan 21, 2024 |
| Lenovo        | ThinkPad L15 Gen 1 20U3C... | Notebook    | [354671b848](https://linux-hardware.org/?probe=354671b848) | Jan 20, 2024 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | Notebook    | [fa6a332180](https://linux-hardware.org/?probe=fa6a332180) | Jan 20, 2024 |
| Sony          | VGN-NS11Z_S                 | Notebook    | [64fa921691](https://linux-hardware.org/?probe=64fa921691) | Jan 20, 2024 |
| Lenovo        | ThinkPad L15 Gen 1 20U3C... | Notebook    | [3e339aec48](https://linux-hardware.org/?probe=3e339aec48) | Jan 20, 2024 |
| HP            | ProBook x360 435 G8 Note... | Convertible | [a3d6355fc9](https://linux-hardware.org/?probe=a3d6355fc9) | Jan 20, 2024 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [b244483cc6](https://linux-hardware.org/?probe=b244483cc6) | Jan 20, 2024 |
| Toshiba       | PORTEGE R700                | Notebook    | [9783d3e6f7](https://linux-hardware.org/?probe=9783d3e6f7) | Jan 20, 2024 |
| MSI           | Prestige 16Studio A13VF     | Notebook    | [c345bf4b85](https://linux-hardware.org/?probe=c345bf4b85) | Jan 20, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JTC... | Notebook    | [9f7b8c991a](https://linux-hardware.org/?probe=9f7b8c991a) | Jan 20, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [e07a558ed5](https://linux-hardware.org/?probe=e07a558ed5) | Jan 20, 2024 |
| Notebook      | W350STQ/W370ST              | Notebook    | [a61e368a41](https://linux-hardware.org/?probe=a61e368a41) | Jan 19, 2024 |
| Acer          | TravelMate 5744Z            | Notebook    | [b03213c22c](https://linux-hardware.org/?probe=b03213c22c) | Jan 19, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [363f712134](https://linux-hardware.org/?probe=363f712134) | Jan 19, 2024 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [dd3153283a](https://linux-hardware.org/?probe=dd3153283a) | Jan 19, 2024 |
| HP            | Laptop 15-bs0xx             | Notebook    | [8cd9ebc60f](https://linux-hardware.org/?probe=8cd9ebc60f) | Jan 18, 2024 |
| Intel         | X99                         | Desktop     | [44d8693e2b](https://linux-hardware.org/?probe=44d8693e2b) | Jan 18, 2024 |
| ASUSTek       | PRIME H310M-E               | Desktop     | [6674d084a8](https://linux-hardware.org/?probe=6674d084a8) | Jan 18, 2024 |
| MSI           | Stealth 15M B12UE           | Notebook    | [64561711ef](https://linux-hardware.org/?probe=64561711ef) | Jan 18, 2024 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [08a4e7960a](https://linux-hardware.org/?probe=08a4e7960a) | Jan 18, 2024 |
| HP            | Laptop 15-fd0xxx            | Notebook    | [577019511f](https://linux-hardware.org/?probe=577019511f) | Jan 17, 2024 |
| HP            | Laptop 15-fd0xxx            | Notebook    | [fa7b8cb83e](https://linux-hardware.org/?probe=fa7b8cb83e) | Jan 17, 2024 |
| Lenovo        | ThinkPad X240 20AMS31700    | Notebook    | [d5d3c69c94](https://linux-hardware.org/?probe=d5d3c69c94) | Jan 17, 2024 |
| Lenovo        | ThinkPad X260 20F5S3J301    | Notebook    | [90905d3416](https://linux-hardware.org/?probe=90905d3416) | Jan 17, 2024 |
| Dell          | XPS 9315                    | Notebook    | [2271aed5c7](https://linux-hardware.org/?probe=2271aed5c7) | Jan 17, 2024 |
| HONOR         | HLYL-WXX9                   | Notebook    | [de76a39d7b](https://linux-hardware.org/?probe=de76a39d7b) | Jan 17, 2024 |
| MSI           | B560M PRO-VDH               | Desktop     | [cc460a0905](https://linux-hardware.org/?probe=cc460a0905) | Jan 16, 2024 |
| BESSTAR Te... | GB1B                        | Mini pc     | [817daf41f7](https://linux-hardware.org/?probe=817daf41f7) | Jan 16, 2024 |
| BESSTAR Te... | GB1B                        | Mini pc     | [87ad2c7889](https://linux-hardware.org/?probe=87ad2c7889) | Jan 16, 2024 |
| Unknown       | Unknown                     | Notebook    | [40de727301](https://linux-hardware.org/?probe=40de727301) | Jan 16, 2024 |
| HP            | 8750                        | Desktop     | [6dd29a1c24](https://linux-hardware.org/?probe=6dd29a1c24) | Jan 16, 2024 |
| Lenovo        | 30D9 SDK0J40697 WIN 3305... | Desktop     | [eddee431eb](https://linux-hardware.org/?probe=eddee431eb) | Jan 16, 2024 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | Notebook    | [323c35348f](https://linux-hardware.org/?probe=323c35348f) | Jan 16, 2024 |
| Apple         | MacBookPro9,1               | Notebook    | [3b43ca4be8](https://linux-hardware.org/?probe=3b43ca4be8) | Jan 16, 2024 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [6b8df5e5f8](https://linux-hardware.org/?probe=6b8df5e5f8) | Jan 16, 2024 |
| Lenovo        | ThinkPad L390 Yoga 20NTC... | Convertible | [b190a1f79a](https://linux-hardware.org/?probe=b190a1f79a) | Jan 15, 2024 |
| Unknown       | Unknown                     | Notebook    | [7cb9c4ae9a](https://linux-hardware.org/?probe=7cb9c4ae9a) | Jan 15, 2024 |
| MSI           | B85-G41 PC Mate             | Desktop     | [a31032a308](https://linux-hardware.org/?probe=a31032a308) | Jan 15, 2024 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [662828b0e7](https://linux-hardware.org/?probe=662828b0e7) | Jan 15, 2024 |
| HP            | 630                         | Notebook    | [15cea68071](https://linux-hardware.org/?probe=15cea68071) | Jan 15, 2024 |
| Jumper        | EZpad .A002                 | Notebook    | [165b30453c](https://linux-hardware.org/?probe=165b30453c) | Jan 15, 2024 |
| Lenovo        | G580 2189                   | Notebook    | [9f78e2fda0](https://linux-hardware.org/?probe=9f78e2fda0) | Jan 15, 2024 |
| Intel         | X99-P4 V5.0                 | Desktop     | [574a971f93](https://linux-hardware.org/?probe=574a971f93) | Jan 14, 2024 |
| HP            | EliteBook x360 1040 G6      | Convertible | [52e03411d9](https://linux-hardware.org/?probe=52e03411d9) | Jan 14, 2024 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [c4edc08fb7](https://linux-hardware.org/?probe=c4edc08fb7) | Jan 14, 2024 |
| MSI           | A320M-A PRO                 | Desktop     | [4f2655db6f](https://linux-hardware.org/?probe=4f2655db6f) | Jan 14, 2024 |
| Apple         | MacBookPro12,1              | Notebook    | [1a33b5b4c6](https://linux-hardware.org/?probe=1a33b5b4c6) | Jan 14, 2024 |
| Gigabyte      | AX370-Gaming 5              | Desktop     | [44ec140279](https://linux-hardware.org/?probe=44ec140279) | Jan 14, 2024 |
| Gigabyte      | G5 KD                       | Notebook    | [1f4984ff1a](https://linux-hardware.org/?probe=1f4984ff1a) | Jan 14, 2024 |
| Apple         | MacBookPro12,1              | Notebook    | [6e1b95e72e](https://linux-hardware.org/?probe=6e1b95e72e) | Jan 14, 2024 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [9000ce06e8](https://linux-hardware.org/?probe=9000ce06e8) | Jan 14, 2024 |
| Acer          | TravelMate P259-G2-M        | Notebook    | [24d3ae9a88](https://linux-hardware.org/?probe=24d3ae9a88) | Jan 14, 2024 |
| Supermicro    | X11SSH-F                    | Server      | [4ec98ce9b3](https://linux-hardware.org/?probe=4ec98ce9b3) | Jan 13, 2024 |
| Sony          | VGN-NS11Z_S                 | Notebook    | [863785eef9](https://linux-hardware.org/?probe=863785eef9) | Jan 13, 2024 |
| ASUSTek       | P8H61-M2 USB3               | Desktop     | [705185dd25](https://linux-hardware.org/?probe=705185dd25) | Jan 13, 2024 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [fe4ed2794f](https://linux-hardware.org/?probe=fe4ed2794f) | Jan 13, 2024 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [b5c9600b1e](https://linux-hardware.org/?probe=b5c9600b1e) | Jan 13, 2024 |
| RCA           | W101SA23T2                  | Tablet      | [ad61c4c1cf](https://linux-hardware.org/?probe=ad61c4c1cf) | Jan 13, 2024 |
| Gigabyte      | H510M H V2                  | Desktop     | [1340d91b43](https://linux-hardware.org/?probe=1340d91b43) | Jan 13, 2024 |
| HP            | EliteBook 840 G5            | Notebook    | [60f88b1f3f](https://linux-hardware.org/?probe=60f88b1f3f) | Jan 13, 2024 |
| RCA           | W101SA23T2                  | Tablet      | [2cd2a3d3b7](https://linux-hardware.org/?probe=2cd2a3d3b7) | Jan 12, 2024 |
| Alurin        | ALU-LPT-N4020-8256-140      | Notebook    | [61fdeffbaf](https://linux-hardware.org/?probe=61fdeffbaf) | Jan 12, 2024 |
| MSI           | H97 PC Mate                 | Desktop     | [b9df3e4a61](https://linux-hardware.org/?probe=b9df3e4a61) | Jan 12, 2024 |
| Apple         | MacBookPro14,3              | Notebook    | [3b0c274172](https://linux-hardware.org/?probe=3b0c274172) | Jan 12, 2024 |
| Lenovo        | ThinkPad T440 20B7S1M20F    | Notebook    | [41dcda72fa](https://linux-hardware.org/?probe=41dcda72fa) | Jan 12, 2024 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | Notebook    | [c913eb2c1b](https://linux-hardware.org/?probe=c913eb2c1b) | Jan 12, 2024 |
| Alienware     | 17 R5                       | Notebook    | [4588195d7c](https://linux-hardware.org/?probe=4588195d7c) | Jan 12, 2024 |
| HP            | 650                         | Notebook    | [9c5b3c57f6](https://linux-hardware.org/?probe=9c5b3c57f6) | Jan 11, 2024 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [da41d1e19b](https://linux-hardware.org/?probe=da41d1e19b) | Jan 11, 2024 |
| Samsung       | 750QFG                      | Convertible | [97bec49dfe](https://linux-hardware.org/?probe=97bec49dfe) | Jan 11, 2024 |
| Acer          | Veriton X490G               | Desktop     | [1110362d9a](https://linux-hardware.org/?probe=1110362d9a) | Jan 11, 2024 |
| Toshiba       | Satellite L750              | Notebook    | [44ec4c7459](https://linux-hardware.org/?probe=44ec4c7459) | Jan 11, 2024 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [ca8734dc63](https://linux-hardware.org/?probe=ca8734dc63) | Jan 11, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [7cf8b59aee](https://linux-hardware.org/?probe=7cf8b59aee) | Jan 10, 2024 |
| Dell          | Latitude 5580               | Notebook    | [d97f97cf29](https://linux-hardware.org/?probe=d97f97cf29) | Jan 10, 2024 |
| HP            | Pavilion Sleekbook 14       | Notebook    | [9f54d91b95](https://linux-hardware.org/?probe=9f54d91b95) | Jan 10, 2024 |
| Toshiba       | PORTEGE R700                | Notebook    | [3322fd81c6](https://linux-hardware.org/?probe=3322fd81c6) | Jan 10, 2024 |
| Toshiba       | PORTEGE R700                | Notebook    | [dd25b116ff](https://linux-hardware.org/?probe=dd25b116ff) | Jan 10, 2024 |
| Primux Tec... | Primux_1406F_W10            | Notebook    | [30587bf7e5](https://linux-hardware.org/?probe=30587bf7e5) | Jan 10, 2024 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [1ed7bf40d8](https://linux-hardware.org/?probe=1ed7bf40d8) | Jan 10, 2024 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [e8e7b87b69](https://linux-hardware.org/?probe=e8e7b87b69) | Jan 10, 2024 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [03202bdde9](https://linux-hardware.org/?probe=03202bdde9) | Jan 10, 2024 |
| ASUSTek       | M4N78                       | Desktop     | [b9b072474d](https://linux-hardware.org/?probe=b9b072474d) | Jan 10, 2024 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [757c6f2826](https://linux-hardware.org/?probe=757c6f2826) | Jan 10, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [6c8905667e](https://linux-hardware.org/?probe=6c8905667e) | Jan 09, 2024 |
| Primux Tec... | Primux_1406F_W10            | Notebook    | [8df3356415](https://linux-hardware.org/?probe=8df3356415) | Jan 09, 2024 |
| ASUSTek       | K52F                        | Notebook    | [0b3d88eb7e](https://linux-hardware.org/?probe=0b3d88eb7e) | Jan 09, 2024 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [cd8ee8db1f](https://linux-hardware.org/?probe=cd8ee8db1f) | Jan 09, 2024 |
| HP            | Notebook                    | Notebook    | [ae9cfe9cc7](https://linux-hardware.org/?probe=ae9cfe9cc7) | Jan 09, 2024 |
| Intel         | X99H                        | Desktop     | [b0bb3cb105](https://linux-hardware.org/?probe=b0bb3cb105) | Jan 09, 2024 |
| Valve         | Galileo                     | Notebook    | [4032bdfc39](https://linux-hardware.org/?probe=4032bdfc39) | Jan 08, 2024 |
| MSI           | Modern 15 A5M               | Notebook    | [1032489aa7](https://linux-hardware.org/?probe=1032489aa7) | Jan 08, 2024 |
| Acer          | Aspire A315-24P             | Notebook    | [716c2f37dd](https://linux-hardware.org/?probe=716c2f37dd) | Jan 08, 2024 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [9ee22790e4](https://linux-hardware.org/?probe=9ee22790e4) | Jan 08, 2024 |
| Acer          | Aspire A315-24P             | Notebook    | [ba75fc0540](https://linux-hardware.org/?probe=ba75fc0540) | Jan 08, 2024 |
| HP            | Laptop                      | Notebook    | [0fce2e2603](https://linux-hardware.org/?probe=0fce2e2603) | Jan 08, 2024 |
| Gigabyte      | H510M S2H V2                | Desktop     | [48ba042e53](https://linux-hardware.org/?probe=48ba042e53) | Jan 08, 2024 |
| Lenovo        | G710 20252                  | Notebook    | [ec645bc6c5](https://linux-hardware.org/?probe=ec645bc6c5) | Jan 08, 2024 |
| Samsung       | 750QFG                      | Convertible | [5f982793b5](https://linux-hardware.org/?probe=5f982793b5) | Jan 07, 2024 |
| Valve         | Jupiter                     | Notebook    | [67ec614b0e](https://linux-hardware.org/?probe=67ec614b0e) | Jan 07, 2024 |
| HP            | 350 G2                      | Notebook    | [75e4063ce8](https://linux-hardware.org/?probe=75e4063ce8) | Jan 07, 2024 |
| ASRock        | J5040-ITX                   | Desktop     | [2dc9e2367b](https://linux-hardware.org/?probe=2dc9e2367b) | Jan 07, 2024 |
| Cisco Syst... | UCSC-C220-M3S 74-10442-0... | Desktop     | [2bc5f49245](https://linux-hardware.org/?probe=2bc5f49245) | Jan 07, 2024 |
| Valve         | Galileo                     | Notebook    | [7365f742df](https://linux-hardware.org/?probe=7365f742df) | Jan 06, 2024 |
| Lenovo        | MIIX 510-12IKB 80XE         | Tablet      | [009c5330a2](https://linux-hardware.org/?probe=009c5330a2) | Jan 06, 2024 |
| Dell          | Inspiron 1501               | Notebook    | [65d521ef7c](https://linux-hardware.org/?probe=65d521ef7c) | Jan 06, 2024 |
| Apple         | Mac-F221BEC8                | Desktop     | [c172686fae](https://linux-hardware.org/?probe=c172686fae) | Jan 06, 2024 |
| Apple         | Mac-F221BEC8                | Desktop     | [a36307cb4c](https://linux-hardware.org/?probe=a36307cb4c) | Jan 06, 2024 |
| Acer          | Aspire 5750G                | Notebook    | [f013b4abc7](https://linux-hardware.org/?probe=f013b4abc7) | Jan 05, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [cc89127000](https://linux-hardware.org/?probe=cc89127000) | Jan 05, 2024 |
| HP            | 83E9                        | Notebook    | [5794eaa509](https://linux-hardware.org/?probe=5794eaa509) | Jan 05, 2024 |
| HP            | 83E9                        | Notebook    | [ca6565530d](https://linux-hardware.org/?probe=ca6565530d) | Jan 05, 2024 |
| HP            | Laptop 15s-fq4xxx           | Notebook    | [11a2efcfc6](https://linux-hardware.org/?probe=11a2efcfc6) | Jan 05, 2024 |
| Valve         | Jupiter                     | Notebook    | [da56767d30](https://linux-hardware.org/?probe=da56767d30) | Jan 05, 2024 |
| Unknown       | Unknown                     | Desktop     | [dd6b7a2d69](https://linux-hardware.org/?probe=dd6b7a2d69) | Jan 05, 2024 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [2cf96ce326](https://linux-hardware.org/?probe=2cf96ce326) | Jan 05, 2024 |
| ASRock        | J5040-ITX                   | Desktop     | [18b422e05b](https://linux-hardware.org/?probe=18b422e05b) | Jan 04, 2024 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [d8329e0062](https://linux-hardware.org/?probe=d8329e0062) | Jan 04, 2024 |
| ASUSTek       | K53SV                       | Notebook    | [c5f4f5d73b](https://linux-hardware.org/?probe=c5f4f5d73b) | Jan 04, 2024 |
| ASUSTek       | K53SV                       | Notebook    | [0dd63031cf](https://linux-hardware.org/?probe=0dd63031cf) | Jan 04, 2024 |
| Toshiba       | Satellite L50t-A            | Notebook    | [1067ec305c](https://linux-hardware.org/?probe=1067ec305c) | Jan 04, 2024 |
| Toshiba       | Satellite L50t-A            | Notebook    | [e5bd2a0ab7](https://linux-hardware.org/?probe=e5bd2a0ab7) | Jan 04, 2024 |
| HP            | ProBook x360 11 G3 EE       | Convertible | [5f9d913149](https://linux-hardware.org/?probe=5f9d913149) | Jan 04, 2024 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [f4db017a3f](https://linux-hardware.org/?probe=f4db017a3f) | Jan 03, 2024 |
| Unknown       | Unknown                     | Other       | [ceb8edb5ac](https://linux-hardware.org/?probe=ceb8edb5ac) | Jan 03, 2024 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [0b2828413f](https://linux-hardware.org/?probe=0b2828413f) | Jan 03, 2024 |
| HP            | 2B34                        | Desktop     | [cecedd0691](https://linux-hardware.org/?probe=cecedd0691) | Jan 02, 2024 |
| Unknown       | X99H                        | Desktop     | [61c57cb006](https://linux-hardware.org/?probe=61c57cb006) | Jan 01, 2024 |
| Dell          | Latitude 5511               | Notebook    | [3b186725e3](https://linux-hardware.org/?probe=3b186725e3) | Jan 01, 2024 |
| Apple         | Mac-F22C86C8                | Mini pc     | [b1e1f0314c](https://linux-hardware.org/?probe=b1e1f0314c) | Jan 01, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [4eb26f2685](https://linux-hardware.org/?probe=4eb26f2685) | Jan 01, 2024 |
| ASUSTek       | M4N72-E                     | Desktop     | [7d21517ee3](https://linux-hardware.org/?probe=7d21517ee3) | Dec 31, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [08f5647277](https://linux-hardware.org/?probe=08f5647277) | Dec 31, 2023 |
| ASRock        | B75M-DGS                    | Desktop     | [3a2df88d60](https://linux-hardware.org/?probe=3a2df88d60) | Dec 31, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [47e1e3c766](https://linux-hardware.org/?probe=47e1e3c766) | Dec 31, 2023 |
| Huanan        | X58 V1.0                    | Desktop     | [d13c9b1573](https://linux-hardware.org/?probe=d13c9b1573) | Dec 31, 2023 |
| HP            | Laptop 17-cn3xxx            | Notebook    | [3a84122c5a](https://linux-hardware.org/?probe=3a84122c5a) | Dec 30, 2023 |
| QIYIDA        | X99-H9 V2.0                 | Desktop     | [af479728a3](https://linux-hardware.org/?probe=af479728a3) | Dec 30, 2023 |
| HP            | Pavilion g6                 | Notebook    | [6adc1110b8](https://linux-hardware.org/?probe=6adc1110b8) | Dec 30, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [2b7e4fe145](https://linux-hardware.org/?probe=2b7e4fe145) | Dec 30, 2023 |
| HP            | Pavilion 17                 | Notebook    | [d6e11fbd64](https://linux-hardware.org/?probe=d6e11fbd64) | Dec 30, 2023 |
| Alurin        | ALU-BAR-I511-000-140        | Notebook    | [04ce6d9f2e](https://linux-hardware.org/?probe=04ce6d9f2e) | Dec 30, 2023 |
| Lenovo        | Yoga Slim 7 14APU8 83AA     | Notebook    | [8fe9261232](https://linux-hardware.org/?probe=8fe9261232) | Dec 30, 2023 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [101c85733f](https://linux-hardware.org/?probe=101c85733f) | Dec 29, 2023 |
| Intel         | NUC6i3SYB H81132-503        | Mini pc     | [c834d2e2e0](https://linux-hardware.org/?probe=c834d2e2e0) | Dec 29, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [a3a0b274d0](https://linux-hardware.org/?probe=a3a0b274d0) | Dec 29, 2023 |
| MSI           | B450M PRO-VDH V2            | Desktop     | [7efa5db123](https://linux-hardware.org/?probe=7efa5db123) | Dec 29, 2023 |
| Microsoft     | Surface Pro 7+              | Tablet      | [8b3b7b1de7](https://linux-hardware.org/?probe=8b3b7b1de7) | Dec 29, 2023 |
| MSI           | MEG X570S ACE MAX           | Desktop     | [e0e92720cb](https://linux-hardware.org/?probe=e0e92720cb) | Dec 29, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [a353b43ac0](https://linux-hardware.org/?probe=a353b43ac0) | Dec 29, 2023 |
| HP            | 8719                        | Desktop     | [91c89a31b5](https://linux-hardware.org/?probe=91c89a31b5) | Dec 29, 2023 |
| ASUSTek       | G750JS                      | Notebook    | [1164f5c600](https://linux-hardware.org/?probe=1164f5c600) | Dec 29, 2023 |
| ASUSTek       | ROG Strix G712LV_G712LV     | Notebook    | [c2d6079fe7](https://linux-hardware.org/?probe=c2d6079fe7) | Dec 28, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [4e1a45dee6](https://linux-hardware.org/?probe=4e1a45dee6) | Dec 28, 2023 |
| Qilive        | QW20141BSP                  | Notebook    | [3f2d1e03c3](https://linux-hardware.org/?probe=3f2d1e03c3) | Dec 28, 2023 |
| Apple         | MacBookPro15,4              | Notebook    | [b3691ac681](https://linux-hardware.org/?probe=b3691ac681) | Dec 28, 2023 |
| BAKED         | P65xRP                      | Notebook    | [4bd66fa9db](https://linux-hardware.org/?probe=4bd66fa9db) | Dec 28, 2023 |
| Dell          | 0K216C                      | Desktop     | [203ef6afde](https://linux-hardware.org/?probe=203ef6afde) | Dec 28, 2023 |
| Packard Be... | EasyNote TN36               | Notebook    | [2b83138160](https://linux-hardware.org/?probe=2b83138160) | Dec 28, 2023 |
| MSI           | Z170A GAMING PRO CARBON     | Desktop     | [dfdfad519d](https://linux-hardware.org/?probe=dfdfad519d) | Dec 28, 2023 |
| Apple         | MacBookPro15,4              | Notebook    | [1d368b7c25](https://linux-hardware.org/?probe=1d368b7c25) | Dec 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [37fe922c9d](https://linux-hardware.org/?probe=37fe922c9d) | Dec 28, 2023 |
| AZW           | EQ                          | Desktop     | [1300ad3a67](https://linux-hardware.org/?probe=1300ad3a67) | Dec 27, 2023 |
| Gigabyte      | B760M DS3H DDR4             | Desktop     | [10fa4fd32b](https://linux-hardware.org/?probe=10fa4fd32b) | Dec 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [1fc3f917f2](https://linux-hardware.org/?probe=1fc3f917f2) | Dec 27, 2023 |
| Unknown       | Unknown                     | Notebook    | [0f40cd177e](https://linux-hardware.org/?probe=0f40cd177e) | Dec 27, 2023 |
| Unknown       | Unknown                     | Notebook    | [5965d25e5a](https://linux-hardware.org/?probe=5965d25e5a) | Dec 27, 2023 |
| Unknown       | Unknown                     | Notebook    | [0d550e2115](https://linux-hardware.org/?probe=0d550e2115) | Dec 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | Notebook    | [8af95757fe](https://linux-hardware.org/?probe=8af95757fe) | Dec 27, 2023 |
| HP            | 3397                        | Desktop     | [d7bbeccfe9](https://linux-hardware.org/?probe=d7bbeccfe9) | Dec 27, 2023 |
| Unknown       | Unknown                     | Notebook    | [2bb2a6cd8b](https://linux-hardware.org/?probe=2bb2a6cd8b) | Dec 27, 2023 |
| MSI           | MS-B1591                    | Desktop     | [8baf11e980](https://linux-hardware.org/?probe=8baf11e980) | Dec 27, 2023 |
| ASUSTek       | ROG Strix G713RW_G713RW     | Notebook    | [44db3755d8](https://linux-hardware.org/?probe=44db3755d8) | Dec 26, 2023 |
| Acer          | Nitro ANV15-51              | Notebook    | [0e1146871b](https://linux-hardware.org/?probe=0e1146871b) | Dec 26, 2023 |
| Intel         | X99-P4 V5.0                 | Desktop     | [875d756d73](https://linux-hardware.org/?probe=875d756d73) | Dec 26, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [4fb309a12a](https://linux-hardware.org/?probe=4fb309a12a) | Dec 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [229d71f583](https://linux-hardware.org/?probe=229d71f583) | Dec 26, 2023 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [af65354320](https://linux-hardware.org/?probe=af65354320) | Dec 26, 2023 |
| Unknown       | Unknown                     | Notebook    | [d382bd5980](https://linux-hardware.org/?probe=d382bd5980) | Dec 26, 2023 |
| Unknown       | Unknown                     | Notebook    | [c701a5ce22](https://linux-hardware.org/?probe=c701a5ce22) | Dec 26, 2023 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [f85a8a3b68](https://linux-hardware.org/?probe=f85a8a3b68) | Dec 25, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [a9fdc9aee5](https://linux-hardware.org/?probe=a9fdc9aee5) | Dec 25, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [5b4d3b8b68](https://linux-hardware.org/?probe=5b4d3b8b68) | Dec 25, 2023 |
| HP            | Laptop 17-bs1xx             | Notebook    | [736cd905c8](https://linux-hardware.org/?probe=736cd905c8) | Dec 25, 2023 |
| Clevo         | W760/M770CU                 | Notebook    | [c64bdf2349](https://linux-hardware.org/?probe=c64bdf2349) | Dec 24, 2023 |
| HP            | 1497                        | Desktop     | [c17c12a021](https://linux-hardware.org/?probe=c17c12a021) | Dec 24, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [720ff4cf67](https://linux-hardware.org/?probe=720ff4cf67) | Dec 24, 2023 |
| HP            | Unknown                     | Notebook    | [3bc06ba7d3](https://linux-hardware.org/?probe=3bc06ba7d3) | Dec 24, 2023 |
| Lenovo        | G50-80 80L0                 | Notebook    | [21df7039b9](https://linux-hardware.org/?probe=21df7039b9) | Dec 23, 2023 |
| HP            | 1497                        | Desktop     | [9d5244b557](https://linux-hardware.org/?probe=9d5244b557) | Dec 23, 2023 |
| ASRock        | X370 Taichi                 | Desktop     | [689d51f57e](https://linux-hardware.org/?probe=689d51f57e) | Dec 23, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | Notebook    | [36492390fd](https://linux-hardware.org/?probe=36492390fd) | Dec 22, 2023 |
| Acer          | Aspire VX5-591G             | Notebook    | [2268342e9f](https://linux-hardware.org/?probe=2268342e9f) | Dec 22, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [7148cd104d](https://linux-hardware.org/?probe=7148cd104d) | Dec 22, 2023 |
| Huanan        | X58 V1.0                    | Desktop     | [ac62468ad1](https://linux-hardware.org/?probe=ac62468ad1) | Dec 21, 2023 |
| HP            | EliteBook 650 15.6 inch ... | Notebook    | [2e9f8a97e5](https://linux-hardware.org/?probe=2e9f8a97e5) | Dec 21, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [a102e5839d](https://linux-hardware.org/?probe=a102e5839d) | Dec 21, 2023 |
| Foxconn       | 2ADA                        | Desktop     | [735572694e](https://linux-hardware.org/?probe=735572694e) | Dec 21, 2023 |
| Panasonic     | CF-19RDRCHH7                | Notebook    | [0e67081368](https://linux-hardware.org/?probe=0e67081368) | Dec 21, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [664d34d04d](https://linux-hardware.org/?probe=664d34d04d) | Dec 20, 2023 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [11628f388e](https://linux-hardware.org/?probe=11628f388e) | Dec 20, 2023 |
| ASUSTek       | V6-P5G31E                   | Desktop     | [83a8408a7e](https://linux-hardware.org/?probe=83a8408a7e) | Dec 20, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [6f7295809b](https://linux-hardware.org/?probe=6f7295809b) | Dec 20, 2023 |
| ASUSTek       | Pro B550M-C                 | Desktop     | [4e3b422400](https://linux-hardware.org/?probe=4e3b422400) | Dec 19, 2023 |
| MSI           | Alpha 17 C7VF               | Notebook    | [34b3014f66](https://linux-hardware.org/?probe=34b3014f66) | Dec 19, 2023 |
| Clevo         | W760/M770CU                 | Notebook    | [fdde778b3c](https://linux-hardware.org/?probe=fdde778b3c) | Dec 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [1b5268d64f](https://linux-hardware.org/?probe=1b5268d64f) | Dec 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [1290fe8e5a](https://linux-hardware.org/?probe=1290fe8e5a) | Dec 19, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | Desktop     | [619bbec719](https://linux-hardware.org/?probe=619bbec719) | Dec 19, 2023 |
| ASUSTek       | Pro B550M-C                 | Desktop     | [1cd7c1b629](https://linux-hardware.org/?probe=1cd7c1b629) | Dec 19, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [12f149be7f](https://linux-hardware.org/?probe=12f149be7f) | Dec 18, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9afec278e2](https://linux-hardware.org/?probe=9afec278e2) | Dec 18, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [1d8ddbcb75](https://linux-hardware.org/?probe=1d8ddbcb75) | Dec 18, 2023 |
| ASUSTek       | X550EA                      | Notebook    | [a874ac5799](https://linux-hardware.org/?probe=a874ac5799) | Dec 18, 2023 |
| ASUSTek       | H110M-D                     | Desktop     | [c26e0d3896](https://linux-hardware.org/?probe=c26e0d3896) | Dec 18, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [fd092daf92](https://linux-hardware.org/?probe=fd092daf92) | Dec 18, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [4a83771100](https://linux-hardware.org/?probe=4a83771100) | Dec 18, 2023 |
| ASUSTek       | TUF Gaming B660M-E D4       | Desktop     | [ff5da894f9](https://linux-hardware.org/?probe=ff5da894f9) | Dec 18, 2023 |
| Gigabyte      | H510M H V2                  | Desktop     | [3228539880](https://linux-hardware.org/?probe=3228539880) | Dec 18, 2023 |
| HP            | 255 G6 Notebook PC          | Notebook    | [f4412027d4](https://linux-hardware.org/?probe=f4412027d4) | Dec 18, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [def7de5871](https://linux-hardware.org/?probe=def7de5871) | Dec 17, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [26503ce57e](https://linux-hardware.org/?probe=26503ce57e) | Dec 17, 2023 |
| Notebook      | W65_67SR                    | Notebook    | [8f970e8d4c](https://linux-hardware.org/?probe=8f970e8d4c) | Dec 17, 2023 |
| ASRock        | H310M-STX                   | Desktop     | [df11c23d7c](https://linux-hardware.org/?probe=df11c23d7c) | Dec 17, 2023 |
| ASUSTek       | K53SD                       | Notebook    | [7962dd075b](https://linux-hardware.org/?probe=7962dd075b) | Dec 17, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [299d6ae362](https://linux-hardware.org/?probe=299d6ae362) | Dec 17, 2023 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [28b95cc0b7](https://linux-hardware.org/?probe=28b95cc0b7) | Dec 16, 2023 |
| Allview       | Allbook H                   | Notebook    | [2da4fcb35c](https://linux-hardware.org/?probe=2da4fcb35c) | Dec 16, 2023 |
| HP            | 3647h                       | Desktop     | [4feaf76045](https://linux-hardware.org/?probe=4feaf76045) | Dec 16, 2023 |
| AMI           | Intel                       | Desktop     | [9564eaaec0](https://linux-hardware.org/?probe=9564eaaec0) | Dec 16, 2023 |
| HP            | G62                         | Notebook    | [fd110d99fd](https://linux-hardware.org/?probe=fd110d99fd) | Dec 15, 2023 |
| Lenovo        | IdeaPad Pro 5 16APH8 83A... | Notebook    | [d438fe20ff](https://linux-hardware.org/?probe=d438fe20ff) | Dec 15, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [cde85f7526](https://linux-hardware.org/?probe=cde85f7526) | Dec 15, 2023 |
| Lenovo        | B590 62742QG                | Notebook    | [edb1cd89f6](https://linux-hardware.org/?probe=edb1cd89f6) | Dec 15, 2023 |
| Trigkey       | S5 V2.0                     | Mini pc     | [90a7a3db53](https://linux-hardware.org/?probe=90a7a3db53) | Dec 15, 2023 |
| TUXEDO        | InfinityBook Pro Gen8 (M... | Notebook    | [5ae09c04d4](https://linux-hardware.org/?probe=5ae09c04d4) | Dec 14, 2023 |
| Lenovo        | ThinkPad E16 Gen 1 21JNC... | Notebook    | [46fbc450b5](https://linux-hardware.org/?probe=46fbc450b5) | Dec 14, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [74030d2ce6](https://linux-hardware.org/?probe=74030d2ce6) | Dec 14, 2023 |
| MSI           | GS66 Stealth 10SE           | Notebook    | [7f045bdc89](https://linux-hardware.org/?probe=7f045bdc89) | Dec 14, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [c4e3486e91](https://linux-hardware.org/?probe=c4e3486e91) | Dec 13, 2023 |
| ASRock        | AB350M-HDV                  | Desktop     | [945274527c](https://linux-hardware.org/?probe=945274527c) | Dec 13, 2023 |
| Lenovo        | IdeaPad Slim 3 15IAH8 83... | Notebook    | [f942d9c43e](https://linux-hardware.org/?probe=f942d9c43e) | Dec 13, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [8339b9aa1a](https://linux-hardware.org/?probe=8339b9aa1a) | Dec 13, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [5a65590bed](https://linux-hardware.org/?probe=5a65590bed) | Dec 13, 2023 |
| Intel         | MIR1 RVP7                   | Desktop     | [eade46459a](https://linux-hardware.org/?probe=eade46459a) | Dec 13, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [c5d4eabc9b](https://linux-hardware.org/?probe=c5d4eabc9b) | Dec 12, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [87fa57a3af](https://linux-hardware.org/?probe=87fa57a3af) | Dec 12, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [089a40a6f2](https://linux-hardware.org/?probe=089a40a6f2) | Dec 12, 2023 |
| Acer          | Aspire one                  | Notebook    | [fb1f2ccd2e](https://linux-hardware.org/?probe=fb1f2ccd2e) | Dec 12, 2023 |
| Lenovo        | 3130 SDK0J40697 WIN 3305... | Mini pc     | [e290fd161e](https://linux-hardware.org/?probe=e290fd161e) | Dec 12, 2023 |
| HP            | Laptop 15-fd0xxx            | Notebook    | [f5b7104728](https://linux-hardware.org/?probe=f5b7104728) | Dec 11, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [f932ad9551](https://linux-hardware.org/?probe=f932ad9551) | Dec 11, 2023 |
| Acer          | Aspire ES1-512              | Notebook    | [40438b3cd0](https://linux-hardware.org/?probe=40438b3cd0) | Dec 11, 2023 |
| ASUSTek       | M3A78                       | Desktop     | [d2c14973f1](https://linux-hardware.org/?probe=d2c14973f1) | Dec 10, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [2abe635055](https://linux-hardware.org/?probe=2abe635055) | Dec 10, 2023 |
| Gigabyte      | EP41-UD3L                   | Desktop     | [9b40e5889d](https://linux-hardware.org/?probe=9b40e5889d) | Dec 10, 2023 |
| MSI           | B560M PRO-VDH               | Desktop     | [4a2deac69b](https://linux-hardware.org/?probe=4a2deac69b) | Dec 10, 2023 |
| Packard Be... | MCP73PV                     | Desktop     | [9d707e64d4](https://linux-hardware.org/?probe=9d707e64d4) | Dec 10, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [a668492169](https://linux-hardware.org/?probe=a668492169) | Dec 10, 2023 |
| Dell          | Latitude 7490               | Notebook    | [d9f20ad453](https://linux-hardware.org/?probe=d9f20ad453) | Dec 10, 2023 |
| Gigabyte      | B450 AORUS ELITE V2         | Desktop     | [505f85e4d4](https://linux-hardware.org/?probe=505f85e4d4) | Dec 10, 2023 |
| HP            | 240 G8 Notebook PC          | Notebook    | [e5f4045026](https://linux-hardware.org/?probe=e5f4045026) | Dec 10, 2023 |
| Packard Be... | EasyNote TE11BZ             | Notebook    | [514899b0b9](https://linux-hardware.org/?probe=514899b0b9) | Dec 10, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [215b8bc94a](https://linux-hardware.org/?probe=215b8bc94a) | Dec 09, 2023 |
| ASUSTek       | X540SA                      | Notebook    | [71c6b35d56](https://linux-hardware.org/?probe=71c6b35d56) | Dec 09, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [21131b7844](https://linux-hardware.org/?probe=21131b7844) | Dec 09, 2023 |
| Dell          | Vostro 3560                 | Notebook    | [d2abe7128b](https://linux-hardware.org/?probe=d2abe7128b) | Dec 09, 2023 |
| Notebook      | N24_25JU                    | Notebook    | [48dc91498c](https://linux-hardware.org/?probe=48dc91498c) | Dec 09, 2023 |
| Notebook      | N24_25JU                    | Notebook    | [170b205714](https://linux-hardware.org/?probe=170b205714) | Dec 09, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [c576c4fbae](https://linux-hardware.org/?probe=c576c4fbae) | Dec 09, 2023 |
| Lenovo        | ThinkPad L15 Gen 4 21H3C... | Notebook    | [2c3c1f7ad2](https://linux-hardware.org/?probe=2c3c1f7ad2) | Dec 08, 2023 |
| HP            | Victus by Laptop 16-e1xx... | Notebook    | [9b973fc192](https://linux-hardware.org/?probe=9b973fc192) | Dec 08, 2023 |
| Lenovo        | ThinkPad L15 Gen 4 21H3C... | Notebook    | [f463c790b4](https://linux-hardware.org/?probe=f463c790b4) | Dec 08, 2023 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | Notebook    | [a7dccd5888](https://linux-hardware.org/?probe=a7dccd5888) | Dec 08, 2023 |
| HP            | 630                         | Notebook    | [b6c4bc59c1](https://linux-hardware.org/?probe=b6c4bc59c1) | Dec 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [c652e80145](https://linux-hardware.org/?probe=c652e80145) | Dec 08, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [e6e9d305e9](https://linux-hardware.org/?probe=e6e9d305e9) | Dec 08, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1502CBA    | Notebook    | [b46d0490b6](https://linux-hardware.org/?probe=b46d0490b6) | Dec 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [2cc6eaff05](https://linux-hardware.org/?probe=2cc6eaff05) | Dec 08, 2023 |
| Fanless Mi... | PCG02 GLE                   | Stick pc    | [7e738d8259](https://linux-hardware.org/?probe=7e738d8259) | Dec 08, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [69e785cddb](https://linux-hardware.org/?probe=69e785cddb) | Dec 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [82fd570b21](https://linux-hardware.org/?probe=82fd570b21) | Dec 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [b706d26f30](https://linux-hardware.org/?probe=b706d26f30) | Dec 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [18d69df8d2](https://linux-hardware.org/?probe=18d69df8d2) | Dec 07, 2023 |
| Gigabyte      | GA-MA770-DS3                | Desktop     | [66917779ad](https://linux-hardware.org/?probe=66917779ad) | Dec 07, 2023 |
| AMI           | Intel                       | Desktop     | [d2e7be0ff3](https://linux-hardware.org/?probe=d2e7be0ff3) | Dec 07, 2023 |
| ASUSTek       | Pro B560M-C                 | Desktop     | [116dce4b93](https://linux-hardware.org/?probe=116dce4b93) | Dec 07, 2023 |
| HP            | Laptop 15-fd0xxx            | Notebook    | [6bdc66013b](https://linux-hardware.org/?probe=6bdc66013b) | Dec 07, 2023 |
| MSI           | Z490-A PRO                  | Desktop     | [8d3648a498](https://linux-hardware.org/?probe=8d3648a498) | Dec 07, 2023 |
| HP            | Laptop 17-by3xxx            | Notebook    | [d124640ef5](https://linux-hardware.org/?probe=d124640ef5) | Dec 06, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [923f26e8d8](https://linux-hardware.org/?probe=923f26e8d8) | Dec 06, 2023 |
| Lenovo        | ThinkPad SL500 274678G      | Notebook    | [3cfa60a8bb](https://linux-hardware.org/?probe=3cfa60a8bb) | Dec 06, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [7317dc8b5c](https://linux-hardware.org/?probe=7317dc8b5c) | Dec 06, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [ca5df22812](https://linux-hardware.org/?probe=ca5df22812) | Dec 06, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [1297909900](https://linux-hardware.org/?probe=1297909900) | Dec 05, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [0e8746ee4e](https://linux-hardware.org/?probe=0e8746ee4e) | Dec 05, 2023 |
| Alurin        | Go Notebook                 | Notebook    | [197598d3dd](https://linux-hardware.org/?probe=197598d3dd) | Dec 05, 2023 |
| MSI           | Z490-A PRO                  | Desktop     | [443436c7ab](https://linux-hardware.org/?probe=443436c7ab) | Dec 05, 2023 |
| MSI           | H510I PRO WIFI              | Desktop     | [b0e2df98b4](https://linux-hardware.org/?probe=b0e2df98b4) | Dec 05, 2023 |
| HP            | Pavilion 13 x360 PC         | Notebook    | [3eba272feb](https://linux-hardware.org/?probe=3eba272feb) | Dec 05, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [ddb2183d6c](https://linux-hardware.org/?probe=ddb2183d6c) | Dec 05, 2023 |
| HP            | 630                         | Notebook    | [7d372bb7da](https://linux-hardware.org/?probe=7d372bb7da) | Dec 04, 2023 |
| ASUSTek       | P8Z68-V PRO                 | Desktop     | [fde3c9253f](https://linux-hardware.org/?probe=fde3c9253f) | Dec 04, 2023 |
| ASUSTek       | ROG Maximus Z790 HERO       | Desktop     | [c492be4899](https://linux-hardware.org/?probe=c492be4899) | Dec 04, 2023 |
| Lenovo        | B50-50 80S2                 | Notebook    | [6150907e1e](https://linux-hardware.org/?probe=6150907e1e) | Dec 04, 2023 |
| MSI           | Prestige 15 A12UD           | Notebook    | [b19937fb48](https://linux-hardware.org/?probe=b19937fb48) | Dec 04, 2023 |
| MSI           | Prestige 15 A12UD           | Notebook    | [0c9a3a5cae](https://linux-hardware.org/?probe=0c9a3a5cae) | Dec 04, 2023 |
| Adreamer      | PN1308P                     | Notebook    | [b503469408](https://linux-hardware.org/?probe=b503469408) | Dec 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [db9e1baffe](https://linux-hardware.org/?probe=db9e1baffe) | Dec 04, 2023 |
| HP            | 2B0A                        | All in one  | [94d8a9c118](https://linux-hardware.org/?probe=94d8a9c118) | Dec 04, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [8bca63eb54](https://linux-hardware.org/?probe=8bca63eb54) | Dec 03, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [0926acf98a](https://linux-hardware.org/?probe=0926acf98a) | Dec 03, 2023 |
| Acer          | Aspire A315-24P             | Notebook    | [b8af3ee6d5](https://linux-hardware.org/?probe=b8af3ee6d5) | Dec 03, 2023 |
| Acer          | Aspire A315-24P             | Notebook    | [67efae847f](https://linux-hardware.org/?probe=67efae847f) | Dec 03, 2023 |
| HP            | 2B46                        | Desktop     | [5bfce44b96](https://linux-hardware.org/?probe=5bfce44b96) | Dec 03, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [f04a8e4722](https://linux-hardware.org/?probe=f04a8e4722) | Dec 03, 2023 |
| Lenovo        | IdeaPad 320S-15IKB 81BQ     | Notebook    | [9cedc35586](https://linux-hardware.org/?probe=9cedc35586) | Dec 03, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [3753de5af1](https://linux-hardware.org/?probe=3753de5af1) | Dec 03, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [fb15da06c7](https://linux-hardware.org/?probe=fb15da06c7) | Dec 03, 2023 |
| Lenovo        | ThinkPad W500 40624DG       | Notebook    | [920dc046a3](https://linux-hardware.org/?probe=920dc046a3) | Dec 03, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [426263e458](https://linux-hardware.org/?probe=426263e458) | Dec 03, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [e2d48a6b41](https://linux-hardware.org/?probe=e2d48a6b41) | Dec 03, 2023 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [ece8f86f29](https://linux-hardware.org/?probe=ece8f86f29) | Dec 02, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [89effd522f](https://linux-hardware.org/?probe=89effd522f) | Dec 02, 2023 |
| Acer          | IPXHW-RL                    | Desktop     | [aa0f30e67f](https://linux-hardware.org/?probe=aa0f30e67f) | Dec 02, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [3a6eb27098](https://linux-hardware.org/?probe=3a6eb27098) | Dec 02, 2023 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | Notebook    | [3b3d0cb740](https://linux-hardware.org/?probe=3b3d0cb740) | Dec 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [16215b0c85](https://linux-hardware.org/?probe=16215b0c85) | Dec 02, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [bb033837d5](https://linux-hardware.org/?probe=bb033837d5) | Dec 02, 2023 |
| HP            | 8459                        | Desktop     | [b7a22ecb3f](https://linux-hardware.org/?probe=b7a22ecb3f) | Dec 01, 2023 |
| Intel         | H61 V1.5                    | Desktop     | [45487af3d7](https://linux-hardware.org/?probe=45487af3d7) | Dec 01, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [7eb86d01c5](https://linux-hardware.org/?probe=7eb86d01c5) | Dec 01, 2023 |
| Samsung       | R530/R730                   | Notebook    | [cdda254219](https://linux-hardware.org/?probe=cdda254219) | Dec 01, 2023 |
| Acer          | Extensa M2610 V:1.0         | Desktop     | [e4c1bd6f51](https://linux-hardware.org/?probe=e4c1bd6f51) | Nov 30, 2023 |
| ASUSTek       | P5N-MX                      | Desktop     | [c586157333](https://linux-hardware.org/?probe=c586157333) | Nov 30, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [a828388299](https://linux-hardware.org/?probe=a828388299) | Nov 30, 2023 |
| MSI           | Prestige 16Studio A13VF     | Notebook    | [dc93bfeb80](https://linux-hardware.org/?probe=dc93bfeb80) | Nov 30, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [d92b5d4caf](https://linux-hardware.org/?probe=d92b5d4caf) | Nov 30, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [75dcedad41](https://linux-hardware.org/?probe=75dcedad41) | Nov 30, 2023 |
| Gigabyte      | GA-73PVM-S2H                | Desktop     | [0d85f5e172](https://linux-hardware.org/?probe=0d85f5e172) | Nov 30, 2023 |
| HP            | 304Ah                       | Desktop     | [03437e0238](https://linux-hardware.org/?probe=03437e0238) | Nov 29, 2023 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [ebae1fe9c2](https://linux-hardware.org/?probe=ebae1fe9c2) | Nov 29, 2023 |
| HP            | 8298                        | Desktop     | [f66cb29dd1](https://linux-hardware.org/?probe=f66cb29dd1) | Nov 29, 2023 |
| Alurin        | ALU-LPT-N4020-8256-140      | Notebook    | [0524ad397b](https://linux-hardware.org/?probe=0524ad397b) | Nov 29, 2023 |
| MSI           | Z170A PC MATE               | Desktop     | [913553eac4](https://linux-hardware.org/?probe=913553eac4) | Nov 29, 2023 |
| HP            | EliteBook 640 14 inch G9... | Notebook    | [a9f36d870b](https://linux-hardware.org/?probe=a9f36d870b) | Nov 28, 2023 |
| HONOR         | HLYL-WXX9                   | Notebook    | [fa6847a75b](https://linux-hardware.org/?probe=fa6847a75b) | Nov 28, 2023 |
| MSI           | MS-B1591                    | Desktop     | [1f97b0b293](https://linux-hardware.org/?probe=1f97b0b293) | Nov 28, 2023 |
| HP            | 18E5                        | Desktop     | [a9c04bd2c7](https://linux-hardware.org/?probe=a9c04bd2c7) | Nov 28, 2023 |
| MSI           | MS-B1591                    | Desktop     | [d5ff2835f3](https://linux-hardware.org/?probe=d5ff2835f3) | Nov 28, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [e5509bd1ba](https://linux-hardware.org/?probe=e5509bd1ba) | Nov 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon 34603... | Notebook    | [edb57fe6c8](https://linux-hardware.org/?probe=edb57fe6c8) | Nov 28, 2023 |
| Lenovo        | 30BC SDK0J40705 WIN 3425... | Desktop     | [d16f76117d](https://linux-hardware.org/?probe=d16f76117d) | Nov 28, 2023 |
| HP            | EliteBook 640 14 inch G9... | Notebook    | [f5f1058473](https://linux-hardware.org/?probe=f5f1058473) | Nov 27, 2023 |
| Gigabyte      | Z590I VISION D              | Desktop     | [cb4704c5ba](https://linux-hardware.org/?probe=cb4704c5ba) | Nov 27, 2023 |
| HP            | Elite x2 1012 G1            | Notebook    | [388c6ba69d](https://linux-hardware.org/?probe=388c6ba69d) | Nov 27, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [936970029f](https://linux-hardware.org/?probe=936970029f) | Nov 27, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [121db7e081](https://linux-hardware.org/?probe=121db7e081) | Nov 27, 2023 |
| SHENZHEN Y... | XBOOK-3                     | Notebook    | [beeefc2461](https://linux-hardware.org/?probe=beeefc2461) | Nov 26, 2023 |
| HP            | ENVY m6                     | Notebook    | [41cff88708](https://linux-hardware.org/?probe=41cff88708) | Nov 26, 2023 |
| Lenovo        | Aptio CRB 31900058 STD      | Mini pc     | [bd08d681a3](https://linux-hardware.org/?probe=bd08d681a3) | Nov 26, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | Desktop     | [d3e69f25a6](https://linux-hardware.org/?probe=d3e69f25a6) | Nov 26, 2023 |
| HP            | 339A                        | Desktop     | [5cad333081](https://linux-hardware.org/?probe=5cad333081) | Nov 26, 2023 |
| MSI           | B650 GAMING PLUS WIFI       | Desktop     | [c25e140976](https://linux-hardware.org/?probe=c25e140976) | Nov 26, 2023 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [91001125ab](https://linux-hardware.org/?probe=91001125ab) | Nov 25, 2023 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [c22007e726](https://linux-hardware.org/?probe=c22007e726) | Nov 25, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [7359fe59a4](https://linux-hardware.org/?probe=7359fe59a4) | Nov 25, 2023 |
| ASUSTek       | ROG STRIX B460-I GAMING     | Desktop     | [7a0adaf9f3](https://linux-hardware.org/?probe=7a0adaf9f3) | Nov 25, 2023 |
| ASUSTek       | ROG STRIX B460-I GAMING     | Desktop     | [b96e460a4f](https://linux-hardware.org/?probe=b96e460a4f) | Nov 25, 2023 |
| Dell          | Latitude 3510               | Notebook    | [0ebe37e56d](https://linux-hardware.org/?probe=0ebe37e56d) | Nov 25, 2023 |
| Lenovo        | IdeaPad Pro 5 16APH8 83A... | Notebook    | [2b5e71ca1e](https://linux-hardware.org/?probe=2b5e71ca1e) | Nov 24, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [ac2895b3d7](https://linux-hardware.org/?probe=ac2895b3d7) | Nov 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [d262dd65d4](https://linux-hardware.org/?probe=d262dd65d4) | Nov 24, 2023 |
| ASUSTek       | P8H77-M LE                  | Desktop     | [39919b75ba](https://linux-hardware.org/?probe=39919b75ba) | Nov 24, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [94886bc9d7](https://linux-hardware.org/?probe=94886bc9d7) | Nov 24, 2023 |
| ASUSTek       | M3A78                       | Desktop     | [c4895d59da](https://linux-hardware.org/?probe=c4895d59da) | Nov 23, 2023 |
| AZW           | SEi V1.0                    | Desktop     | [d18296a25c](https://linux-hardware.org/?probe=d18296a25c) | Nov 23, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [7a59ed85d0](https://linux-hardware.org/?probe=7a59ed85d0) | Nov 23, 2023 |
| Lenovo        | ThinkPad T460 20FMS57C00    | Notebook    | [adabeb3e91](https://linux-hardware.org/?probe=adabeb3e91) | Nov 23, 2023 |
| MSI           | Prestige 15 A10SC           | Notebook    | [3b9404eda4](https://linux-hardware.org/?probe=3b9404eda4) | Nov 23, 2023 |
| Lenovo        | ThinkPad T460 20FMS57C00    | Notebook    | [467b2f3c4e](https://linux-hardware.org/?probe=467b2f3c4e) | Nov 23, 2023 |
| Gigabyte      | MZBAYAP-00                  | Desktop     | [101c96a0c0](https://linux-hardware.org/?probe=101c96a0c0) | Nov 22, 2023 |
| Gigabyte      | MZBAYAP-00                  | Desktop     | [f990b64367](https://linux-hardware.org/?probe=f990b64367) | Nov 22, 2023 |
| ASRock        | J4105-ITX                   | Desktop     | [d5a155c906](https://linux-hardware.org/?probe=d5a155c906) | Nov 22, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [6791592808](https://linux-hardware.org/?probe=6791592808) | Nov 22, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [69d5dcd30b](https://linux-hardware.org/?probe=69d5dcd30b) | Nov 22, 2023 |
| Valve         | Jupiter                     | Notebook    | [2fa43c6f3d](https://linux-hardware.org/?probe=2fa43c6f3d) | Nov 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [28af744237](https://linux-hardware.org/?probe=28af744237) | Nov 21, 2023 |
| Dell          | Latitude E6430              | Notebook    | [7fb0b53d1c](https://linux-hardware.org/?probe=7fb0b53d1c) | Nov 21, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [936b04414c](https://linux-hardware.org/?probe=936b04414c) | Nov 21, 2023 |
| MSI           | Pulse GL76 12UEK            | Notebook    | [def3f12e81](https://linux-hardware.org/?probe=def3f12e81) | Nov 21, 2023 |
| Allview       | Allbook H                   | Notebook    | [8c23eb07ac](https://linux-hardware.org/?probe=8c23eb07ac) | Nov 21, 2023 |
| Lenovo        | Aptio CRB 31900058 STD      | Mini pc     | [c99fb132a1](https://linux-hardware.org/?probe=c99fb132a1) | Nov 21, 2023 |
| Dell          | 062TCH A00                  | Desktop     | [6df960f264](https://linux-hardware.org/?probe=6df960f264) | Nov 21, 2023 |
| Lenovo        | Legion Pro 7 16ARX8H 82W... | Notebook    | [43d2b6b8b6](https://linux-hardware.org/?probe=43d2b6b8b6) | Nov 21, 2023 |
| MSI           | Bravo 15 A4DDR              | Notebook    | [d678fe79f8](https://linux-hardware.org/?probe=d678fe79f8) | Nov 20, 2023 |
| Shenzhen M... | F7BFC                       | Desktop     | [bd7cd76d26](https://linux-hardware.org/?probe=bd7cd76d26) | Nov 20, 2023 |
| Chuwi         | LarkBox X                   | Mini pc     | [a0915a9fe1](https://linux-hardware.org/?probe=a0915a9fe1) | Nov 20, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [885444b8af](https://linux-hardware.org/?probe=885444b8af) | Nov 20, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | Notebook    | [ba43f46e34](https://linux-hardware.org/?probe=ba43f46e34) | Nov 20, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [3982d2c377](https://linux-hardware.org/?probe=3982d2c377) | Nov 20, 2023 |
| Dell          | 062TCH A00                  | Desktop     | [895c93e639](https://linux-hardware.org/?probe=895c93e639) | Nov 20, 2023 |
| ASRock        | H81M-ITX/WiFi               | Desktop     | [e4b1bf4519](https://linux-hardware.org/?probe=e4b1bf4519) | Nov 20, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [f91d973bab](https://linux-hardware.org/?probe=f91d973bab) | Nov 19, 2023 |
| Alurin        | ALU-BAR-R555-000-156        | Notebook    | [ce453601f1](https://linux-hardware.org/?probe=ce453601f1) | Nov 19, 2023 |
| ASUSTek       | M3A78                       | Desktop     | [a6392d3aae](https://linux-hardware.org/?probe=a6392d3aae) | Nov 19, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [c9b5f09ea5](https://linux-hardware.org/?probe=c9b5f09ea5) | Nov 19, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [c76562a6ce](https://linux-hardware.org/?probe=c76562a6ce) | Nov 19, 2023 |
| Lenovo        | 314F SDK0J40697 WIN 3305... | Desktop     | [a4523c2cf4](https://linux-hardware.org/?probe=a4523c2cf4) | Nov 19, 2023 |
| HP            | 0A54h                       | Desktop     | [7b3cd2dc7a](https://linux-hardware.org/?probe=7b3cd2dc7a) | Nov 19, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [80d502e7c1](https://linux-hardware.org/?probe=80d502e7c1) | Nov 19, 2023 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [6876ff8fc6](https://linux-hardware.org/?probe=6876ff8fc6) | Nov 19, 2023 |
| Acer          | Extensa M2610 V:1.0         | Desktop     | [7b70ac1965](https://linux-hardware.org/?probe=7b70ac1965) | Nov 19, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [fa116d20dc](https://linux-hardware.org/?probe=fa116d20dc) | Nov 19, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [beae506a63](https://linux-hardware.org/?probe=beae506a63) | Nov 18, 2023 |
| Lenovo        | ThinkPad X13 Gen 3 21CMC... | Notebook    | [e25caef1f8](https://linux-hardware.org/?probe=e25caef1f8) | Nov 18, 2023 |
| Trigkey       | S5 V2.0                     | Mini pc     | [b36fc50456](https://linux-hardware.org/?probe=b36fc50456) | Nov 18, 2023 |
| Star Labs     | Lite                        | Notebook    | [715761cc4e](https://linux-hardware.org/?probe=715761cc4e) | Nov 18, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [66a57a819b](https://linux-hardware.org/?probe=66a57a819b) | Nov 17, 2023 |
| Acer          | Aspire TC-780               | Desktop     | [76cc38fcb0](https://linux-hardware.org/?probe=76cc38fcb0) | Nov 17, 2023 |
| ASUSTek       | X540YA                      | Notebook    | [ffdc6b121c](https://linux-hardware.org/?probe=ffdc6b121c) | Nov 17, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [0c9b59ab03](https://linux-hardware.org/?probe=0c9b59ab03) | Nov 17, 2023 |
| Dell          | XPS 13 9365                 | Convertible | [b0fca6e283](https://linux-hardware.org/?probe=b0fca6e283) | Nov 17, 2023 |
| MSI           | Pulse GL66 12UEK            | Notebook    | [9421ac824c](https://linux-hardware.org/?probe=9421ac824c) | Nov 17, 2023 |
| Intel         | D34010WYK H14771-304        | Desktop     | [b3c1feb070](https://linux-hardware.org/?probe=b3c1feb070) | Nov 17, 2023 |
| AMI           | Intel                       | Desktop     | [36c0765b5c](https://linux-hardware.org/?probe=36c0765b5c) | Nov 17, 2023 |
| Sony          | VPCEB1J8E                   | Notebook    | [961e0e701d](https://linux-hardware.org/?probe=961e0e701d) | Nov 17, 2023 |
| Dell          | Precision 5680              | Notebook    | [a2957d2ece](https://linux-hardware.org/?probe=a2957d2ece) | Nov 16, 2023 |
| Dell          | Precision 5680              | Notebook    | [2c6c6027a6](https://linux-hardware.org/?probe=2c6c6027a6) | Nov 16, 2023 |
| MSI           | GF75 Thin 10SC              | Notebook    | [5388f8cbdd](https://linux-hardware.org/?probe=5388f8cbdd) | Nov 16, 2023 |
| Lenovo        | ThinkPad Edge E320 1298R... | Notebook    | [535d92743c](https://linux-hardware.org/?probe=535d92743c) | Nov 16, 2023 |
| Lenovo        | ThinkPad Edge E320 1298R... | Notebook    | [331f7da246](https://linux-hardware.org/?probe=331f7da246) | Nov 16, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [23bd3ec971](https://linux-hardware.org/?probe=23bd3ec971) | Nov 16, 2023 |
| Lenovo        | G580 2189                   | Notebook    | [552aa58bee](https://linux-hardware.org/?probe=552aa58bee) | Nov 16, 2023 |
| Dell          | 062TCH A00                  | Desktop     | [5e674f81ca](https://linux-hardware.org/?probe=5e674f81ca) | Nov 15, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [2e59ea85e9](https://linux-hardware.org/?probe=2e59ea85e9) | Nov 15, 2023 |
| ASUSTek       | K52Jr                       | Notebook    | [142c6a9c61](https://linux-hardware.org/?probe=142c6a9c61) | Nov 15, 2023 |
| Adreamer      | PN1308P                     | Notebook    | [8c4d2fca5a](https://linux-hardware.org/?probe=8c4d2fca5a) | Nov 14, 2023 |
| Adreamer      | PN1308P                     | Notebook    | [5efc66eebc](https://linux-hardware.org/?probe=5efc66eebc) | Nov 14, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [1606b9e027](https://linux-hardware.org/?probe=1606b9e027) | Nov 14, 2023 |
| MSI           | Prestige 14 A10SC           | Notebook    | [59ad7e7e27](https://linux-hardware.org/?probe=59ad7e7e27) | Nov 14, 2023 |
| MSI           | Prestige 14 A10SC           | Notebook    | [6b1a5452f8](https://linux-hardware.org/?probe=6b1a5452f8) | Nov 14, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [7a178e1a0f](https://linux-hardware.org/?probe=7a178e1a0f) | Nov 14, 2023 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [db881a2b07](https://linux-hardware.org/?probe=db881a2b07) | Nov 13, 2023 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [b43a43b268](https://linux-hardware.org/?probe=b43a43b268) | Nov 13, 2023 |
| Shenzhen M... | F7BSC                       | Desktop     | [23cc4e28d3](https://linux-hardware.org/?probe=23cc4e28d3) | Nov 13, 2023 |
| ASUSTek       | K52Jr                       | Notebook    | [7e34d5b70b](https://linux-hardware.org/?probe=7e34d5b70b) | Nov 13, 2023 |
| Unknown       | T3 MRD                      | Desktop     | [ae1a1c1e9b](https://linux-hardware.org/?probe=ae1a1c1e9b) | Nov 13, 2023 |
| Toshiba       | PORTEGE Z30-B               | Notebook    | [2cd609dfe0](https://linux-hardware.org/?probe=2cd609dfe0) | Nov 12, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [78b909aa81](https://linux-hardware.org/?probe=78b909aa81) | Nov 12, 2023 |
| Shenzhen M... | F7BFC                       | Desktop     | [b375ae991a](https://linux-hardware.org/?probe=b375ae991a) | Nov 12, 2023 |
| Lenovo        | ThinkPad L540 20AUS11P00    | Notebook    | [593d2114d9](https://linux-hardware.org/?probe=593d2114d9) | Nov 12, 2023 |
| MSI           | Z490-A PRO                  | Desktop     | [1291055857](https://linux-hardware.org/?probe=1291055857) | Nov 12, 2023 |
| HP            | 630                         | Notebook    | [ccc318ee31](https://linux-hardware.org/?probe=ccc318ee31) | Nov 12, 2023 |
| HP            | 630                         | Notebook    | [df3b4ec5db](https://linux-hardware.org/?probe=df3b4ec5db) | Nov 12, 2023 |
| Unknown       | Unknown                     | Notebook    | [be77c5477d](https://linux-hardware.org/?probe=be77c5477d) | Nov 12, 2023 |
| Unknown       | Unknown                     | Notebook    | [d93ab747bb](https://linux-hardware.org/?probe=d93ab747bb) | Nov 12, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [e89b871c81](https://linux-hardware.org/?probe=e89b871c81) | Nov 12, 2023 |
| Dell          | Latitude 7440               | Notebook    | [5c19a02292](https://linux-hardware.org/?probe=5c19a02292) | Nov 11, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [1ce5868093](https://linux-hardware.org/?probe=1ce5868093) | Nov 11, 2023 |
| Toshiba       | PORTEGE Z30-A               | Notebook    | [1b3661590f](https://linux-hardware.org/?probe=1b3661590f) | Nov 11, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [3da6dfb4b3](https://linux-hardware.org/?probe=3da6dfb4b3) | Nov 11, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [332413e83b](https://linux-hardware.org/?probe=332413e83b) | Nov 11, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [26a111bc63](https://linux-hardware.org/?probe=26a111bc63) | Nov 11, 2023 |
| ALLDOCUBE     | i1405C                      | Notebook    | [8f63b8af98](https://linux-hardware.org/?probe=8f63b8af98) | Nov 10, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [ca677ba9c3](https://linux-hardware.org/?probe=ca677ba9c3) | Nov 10, 2023 |
| ASUSTek       | H110M-D                     | Desktop     | [6e0b13392e](https://linux-hardware.org/?probe=6e0b13392e) | Nov 10, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [9f3d17b672](https://linux-hardware.org/?probe=9f3d17b672) | Nov 10, 2023 |
| MSI           | Prestige 15 A10SC           | Notebook    | [e2f423f938](https://linux-hardware.org/?probe=e2f423f938) | Nov 10, 2023 |
| ASUSTek       | H110M-D                     | Desktop     | [d4e6049883](https://linux-hardware.org/?probe=d4e6049883) | Nov 10, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [0bf36ad434](https://linux-hardware.org/?probe=0bf36ad434) | Nov 09, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [2adf99d3df](https://linux-hardware.org/?probe=2adf99d3df) | Nov 09, 2023 |
| MSI           | Z170-A PRO                  | Desktop     | [2bdf6b2a2f](https://linux-hardware.org/?probe=2bdf6b2a2f) | Nov 09, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [9bb56dd3fd](https://linux-hardware.org/?probe=9bb56dd3fd) | Nov 09, 2023 |
| HP            | Compaq Presario CQ70        | Notebook    | [1c495f3402](https://linux-hardware.org/?probe=1c495f3402) | Nov 09, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [9f34bb8f83](https://linux-hardware.org/?probe=9f34bb8f83) | Nov 09, 2023 |
| Lenovo        | G580 2189                   | Notebook    | [e6ceb0d192](https://linux-hardware.org/?probe=e6ceb0d192) | Nov 09, 2023 |
| LG Electro... | 15Z90RT-G.AD75B             | Notebook    | [2ec6124055](https://linux-hardware.org/?probe=2ec6124055) | Nov 09, 2023 |
| HP            | Pavilion dv6                | Notebook    | [919942c11f](https://linux-hardware.org/?probe=919942c11f) | Nov 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [193098a1ea](https://linux-hardware.org/?probe=193098a1ea) | Nov 08, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [ab1a7393ef](https://linux-hardware.org/?probe=ab1a7393ef) | Nov 08, 2023 |
| HP            | Pavilion dm4                | Notebook    | [93ee8aa87c](https://linux-hardware.org/?probe=93ee8aa87c) | Nov 08, 2023 |
| MSI           | B360M PRO-VDH               | Desktop     | [536865249c](https://linux-hardware.org/?probe=536865249c) | Nov 08, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | Notebook    | [0fceea6321](https://linux-hardware.org/?probe=0fceea6321) | Nov 08, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [7ecc25dda7](https://linux-hardware.org/?probe=7ecc25dda7) | Nov 08, 2023 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [ef9e91fdbf](https://linux-hardware.org/?probe=ef9e91fdbf) | Nov 08, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [c0f28da2b7](https://linux-hardware.org/?probe=c0f28da2b7) | Nov 07, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [5a6cfb8bce](https://linux-hardware.org/?probe=5a6cfb8bce) | Nov 07, 2023 |
| Dell          | 062TCH A00                  | Desktop     | [ac7ca2b01b](https://linux-hardware.org/?probe=ac7ca2b01b) | Nov 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [18a292fb51](https://linux-hardware.org/?probe=18a292fb51) | Nov 07, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [3de6cf8221](https://linux-hardware.org/?probe=3de6cf8221) | Nov 07, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [24cd0b58d3](https://linux-hardware.org/?probe=24cd0b58d3) | Nov 07, 2023 |
| AZW           | EQ                          | Desktop     | [50c0310d2e](https://linux-hardware.org/?probe=50c0310d2e) | Nov 06, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [980eb7c13d](https://linux-hardware.org/?probe=980eb7c13d) | Nov 06, 2023 |
| Unknown       | Unknown                     | Notebook    | [1545b5a7bb](https://linux-hardware.org/?probe=1545b5a7bb) | Nov 06, 2023 |
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [51ed218597](https://linux-hardware.org/?probe=51ed218597) | Nov 06, 2023 |
| AZW           | EQ                          | Desktop     | [161d2abf24](https://linux-hardware.org/?probe=161d2abf24) | Nov 06, 2023 |
| MSI           | H55M-E33                    | Desktop     | [09ba697574](https://linux-hardware.org/?probe=09ba697574) | Nov 06, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [27381bdf35](https://linux-hardware.org/?probe=27381bdf35) | Nov 06, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [9e50325ddd](https://linux-hardware.org/?probe=9e50325ddd) | Nov 06, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [b40c43c829](https://linux-hardware.org/?probe=b40c43c829) | Nov 05, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [67a1ec0ae8](https://linux-hardware.org/?probe=67a1ec0ae8) | Nov 05, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [1cc495d15b](https://linux-hardware.org/?probe=1cc495d15b) | Nov 05, 2023 |
| HP            | Spectre Pro G1              | Notebook    | [78bce56071](https://linux-hardware.org/?probe=78bce56071) | Nov 05, 2023 |
| Toshiba       | TECRA R950                  | Notebook    | [864877692e](https://linux-hardware.org/?probe=864877692e) | Nov 05, 2023 |
| MSI           | MEG Z590 UNIFY              | Desktop     | [1f84fe45f8](https://linux-hardware.org/?probe=1f84fe45f8) | Nov 05, 2023 |
| MSI           | B560M PRO-VDH               | Desktop     | [82bf4f530a](https://linux-hardware.org/?probe=82bf4f530a) | Nov 05, 2023 |
| Shuttle       | FH87                        | Desktop     | [1488ef29c3](https://linux-hardware.org/?probe=1488ef29c3) | Nov 05, 2023 |
| HP            | Pavilion dm4                | Notebook    | [ed4309477f](https://linux-hardware.org/?probe=ed4309477f) | Nov 05, 2023 |
| HP            | Pavilion dv6                | Notebook    | [60ff7a74af](https://linux-hardware.org/?probe=60ff7a74af) | Nov 05, 2023 |
| Dell          | 062TCH A00                  | Desktop     | [b82fbd03d5](https://linux-hardware.org/?probe=b82fbd03d5) | Nov 05, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [ae9fcece31](https://linux-hardware.org/?probe=ae9fcece31) | Nov 05, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [fefb7e12d2](https://linux-hardware.org/?probe=fefb7e12d2) | Nov 05, 2023 |
| MSI           | B560M PRO-VDH               | Desktop     | [04e96e2742](https://linux-hardware.org/?probe=04e96e2742) | Nov 04, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [dade20f823](https://linux-hardware.org/?probe=dade20f823) | Nov 04, 2023 |
| MSI           | Modern 15 B7M               | Notebook    | [b4a588e60e](https://linux-hardware.org/?probe=b4a588e60e) | Nov 04, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [20ffbbc165](https://linux-hardware.org/?probe=20ffbbc165) | Nov 04, 2023 |
| Dell          | 062TCH A00                  | Desktop     | [b964b2c6be](https://linux-hardware.org/?probe=b964b2c6be) | Nov 04, 2023 |
| ASUSTek       | H110M-D                     | Desktop     | [03303fa6ed](https://linux-hardware.org/?probe=03303fa6ed) | Nov 04, 2023 |
| Lenovo        | G580 2189                   | Notebook    | [29a529e02c](https://linux-hardware.org/?probe=29a529e02c) | Nov 03, 2023 |
| Lenovo        | ThinkPad X1 Fold Gen 1 2... | Tablet      | [a06677f6ea](https://linux-hardware.org/?probe=a06677f6ea) | Nov 03, 2023 |
| Lenovo        | ThinkPad X1 Fold Gen 1 2... | Tablet      | [d8c90f446f](https://linux-hardware.org/?probe=d8c90f446f) | Nov 03, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [8b855ce4f4](https://linux-hardware.org/?probe=8b855ce4f4) | Nov 03, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [b724ede64d](https://linux-hardware.org/?probe=b724ede64d) | Nov 02, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [89a9c53f3a](https://linux-hardware.org/?probe=89a9c53f3a) | Nov 02, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [ae6c835796](https://linux-hardware.org/?probe=ae6c835796) | Nov 02, 2023 |
| MSI           | Prestige 14 A11SCS          | Notebook    | [e114e8ae5b](https://linux-hardware.org/?probe=e114e8ae5b) | Nov 02, 2023 |
| Intel         | X99                         | Desktop     | [b740510fc0](https://linux-hardware.org/?probe=b740510fc0) | Nov 02, 2023 |
| Lenovo        | 318D                        | All in one  | [9936941c90](https://linux-hardware.org/?probe=9936941c90) | Nov 02, 2023 |
| Lenovo        | 318D                        | All in one  | [2774838df7](https://linux-hardware.org/?probe=2774838df7) | Nov 02, 2023 |
| MSI           | Z170A GAMING M7             | Desktop     | [9ba4f50201](https://linux-hardware.org/?probe=9ba4f50201) | Nov 02, 2023 |
| Lenovo        | Yoga Slim 9 14IAP7 82T0     | Notebook    | [11e373f762](https://linux-hardware.org/?probe=11e373f762) | Nov 02, 2023 |
| Lenovo        | ThinkPad X240 20AMS2EC00    | Notebook    | [820620d5c4](https://linux-hardware.org/?probe=820620d5c4) | Nov 01, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [993d985e9e](https://linux-hardware.org/?probe=993d985e9e) | Nov 01, 2023 |
| Dell          | G3 3579                     | Notebook    | [0b33f63284](https://linux-hardware.org/?probe=0b33f63284) | Nov 01, 2023 |
| MSI           | Z170A GAMING M7             | Desktop     | [a613aa5a0f](https://linux-hardware.org/?probe=a613aa5a0f) | Nov 01, 2023 |
| Lenovo        | ThinkPad E560 20EVA02SSP    | Notebook    | [165be504bf](https://linux-hardware.org/?probe=165be504bf) | Nov 01, 2023 |
| HP            | ZBook 15u G6                | Notebook    | [b74e35da2b](https://linux-hardware.org/?probe=b74e35da2b) | Nov 01, 2023 |
| Acer          | Aspire E1-572G              | Notebook    | [d347dc93b5](https://linux-hardware.org/?probe=d347dc93b5) | Nov 01, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [bb9a00e5b5](https://linux-hardware.org/?probe=bb9a00e5b5) | Nov 01, 2023 |
| ASUSTek       | X550LD                      | Notebook    | [2d0fae2241](https://linux-hardware.org/?probe=2d0fae2241) | Nov 01, 2023 |
| MSI           | H110M ECO                   | Desktop     | [d2f60e8bc9](https://linux-hardware.org/?probe=d2f60e8bc9) | Nov 01, 2023 |
| HP            | 8054                        | Desktop     | [b667e30b0e](https://linux-hardware.org/?probe=b667e30b0e) | Nov 01, 2023 |
| Gigabyte      | GA-MA770-DS3                | Desktop     | [968cf90d9a](https://linux-hardware.org/?probe=968cf90d9a) | Nov 01, 2023 |
| ASUSTek       | X555QG                      | Notebook    | [f047c1d264](https://linux-hardware.org/?probe=f047c1d264) | Nov 01, 2023 |
| Gigabyte      | P67A-D3-B3                  | Desktop     | [0c51ffc039](https://linux-hardware.org/?probe=0c51ffc039) | Nov 01, 2023 |
| VANT          | MOOVE3-15                   | Notebook    | [5fc04a6d0a](https://linux-hardware.org/?probe=5fc04a6d0a) | Oct 31, 2023 |
| Toshiba       | Satellite C55-C             | Notebook    | [859d23eed0](https://linux-hardware.org/?probe=859d23eed0) | Oct 31, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [7b6fe38982](https://linux-hardware.org/?probe=7b6fe38982) | Oct 31, 2023 |
| VANT          | MOOVE3-15                   | Notebook    | [7e12621e6d](https://linux-hardware.org/?probe=7e12621e6d) | Oct 31, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [0eae5ed294](https://linux-hardware.org/?probe=0eae5ed294) | Oct 31, 2023 |
| Chuwi         | LarkBox X                   | Mini pc     | [d9518c52b4](https://linux-hardware.org/?probe=d9518c52b4) | Oct 30, 2023 |
| Timi          | RedmiBook Pro 14S           | Notebook    | [780e721e24](https://linux-hardware.org/?probe=780e721e24) | Oct 30, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [e4b4cf1229](https://linux-hardware.org/?probe=e4b4cf1229) | Oct 30, 2023 |
| Unknown       | Unknown                     | Notebook    | [43e6db0023](https://linux-hardware.org/?probe=43e6db0023) | Oct 30, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [4254def277](https://linux-hardware.org/?probe=4254def277) | Oct 30, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [d03daf3967](https://linux-hardware.org/?probe=d03daf3967) | Oct 30, 2023 |
| HP            | 8436                        | Desktop     | [4fe5c2e03c](https://linux-hardware.org/?probe=4fe5c2e03c) | Oct 30, 2023 |
| ASUSTek       | PN53-G                      | Mini pc     | [e64336b3cd](https://linux-hardware.org/?probe=e64336b3cd) | Oct 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [bb991098d1](https://linux-hardware.org/?probe=bb991098d1) | Oct 30, 2023 |
| MSI           | GF75 Thin 10SC              | Notebook    | [7aa47ebfa1](https://linux-hardware.org/?probe=7aa47ebfa1) | Oct 30, 2023 |
| Gigabyte      | H81M-HD3                    | Desktop     | [1be6955dfc](https://linux-hardware.org/?probe=1be6955dfc) | Oct 30, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [794edd04ea](https://linux-hardware.org/?probe=794edd04ea) | Oct 30, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [e741e073e0](https://linux-hardware.org/?probe=e741e073e0) | Oct 30, 2023 |
| Lenovo        | ZIWB2                       | Notebook    | [9e6bd45db9](https://linux-hardware.org/?probe=9e6bd45db9) | Oct 29, 2023 |
| Chuwi         | LarkBox X                   | Mini pc     | [9fc3537861](https://linux-hardware.org/?probe=9fc3537861) | Oct 29, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [d443352482](https://linux-hardware.org/?probe=d443352482) | Oct 29, 2023 |
| Apple         | MacBookPro15,4              | Notebook    | [09ee918b60](https://linux-hardware.org/?probe=09ee918b60) | Oct 29, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 6 2... | Convertible | [923dc22e28](https://linux-hardware.org/?probe=923dc22e28) | Oct 29, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 6 2... | Convertible | [ab6738f16c](https://linux-hardware.org/?probe=ab6738f16c) | Oct 29, 2023 |
| Allview       | Allbook H                   | Notebook    | [e56046d262](https://linux-hardware.org/?probe=e56046d262) | Oct 29, 2023 |
| Allview       | Allbook H                   | Notebook    | [3f2fc29d49](https://linux-hardware.org/?probe=3f2fc29d49) | Oct 29, 2023 |
| Lenovo        | ThinkPad X270 20HMS1T600    | Notebook    | [97fbe59dd7](https://linux-hardware.org/?probe=97fbe59dd7) | Oct 29, 2023 |
| SLIMBOOK      | TITAN                       | Notebook    | [8697e4de09](https://linux-hardware.org/?probe=8697e4de09) | Oct 29, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [4db0be5324](https://linux-hardware.org/?probe=4db0be5324) | Oct 29, 2023 |
| Koloe         | X58                         | Desktop     | [91fbabe04c](https://linux-hardware.org/?probe=91fbabe04c) | Oct 29, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [dee4ef8a3b](https://linux-hardware.org/?probe=dee4ef8a3b) | Oct 29, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [39d06d7acf](https://linux-hardware.org/?probe=39d06d7acf) | Oct 28, 2023 |
| HP            | 18E4                        | Desktop     | [b192ce4f35](https://linux-hardware.org/?probe=b192ce4f35) | Oct 28, 2023 |
| HP            | Notebook                    | Notebook    | [715435e533](https://linux-hardware.org/?probe=715435e533) | Oct 28, 2023 |
| MSI           | H110M PRO-D                 | Desktop     | [96710ad70e](https://linux-hardware.org/?probe=96710ad70e) | Oct 28, 2023 |
| Toshiba       | TECRA R950                  | Notebook    | [afa984b0d3](https://linux-hardware.org/?probe=afa984b0d3) | Oct 28, 2023 |
| Packard Be... | EasyNote MH36               | Notebook    | [6d73774152](https://linux-hardware.org/?probe=6d73774152) | Oct 28, 2023 |
| SLIMBOOK      | PROX14-10                   | Notebook    | [4ffcd3ced8](https://linux-hardware.org/?probe=4ffcd3ced8) | Oct 28, 2023 |
| Lenovo        | ThinkPad L540 20AUS11P00    | Notebook    | [d59d45eb50](https://linux-hardware.org/?probe=d59d45eb50) | Oct 27, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [fc29a80949](https://linux-hardware.org/?probe=fc29a80949) | Oct 27, 2023 |
| MSI           | Modern 15 A10M              | Notebook    | [79b0d0252f](https://linux-hardware.org/?probe=79b0d0252f) | Oct 27, 2023 |
| Acer          | TravelMate P259-M           | Notebook    | [7c1c04b9b2](https://linux-hardware.org/?probe=7c1c04b9b2) | Oct 26, 2023 |
| Acer          | TravelMate P259-M           | Notebook    | [670cd56ea3](https://linux-hardware.org/?probe=670cd56ea3) | Oct 26, 2023 |
| Lenovo        | ZIWB2                       | Notebook    | [2537a6e7b9](https://linux-hardware.org/?probe=2537a6e7b9) | Oct 26, 2023 |
| Lenovo        | G580 2189                   | Notebook    | [bba412f376](https://linux-hardware.org/?probe=bba412f376) | Oct 26, 2023 |
| Unknown       | Unknown                     | Notebook    | [7d25c7409a](https://linux-hardware.org/?probe=7d25c7409a) | Oct 26, 2023 |
| Apple         | MacBookPro15,4              | Notebook    | [751e98cb04](https://linux-hardware.org/?probe=751e98cb04) | Oct 26, 2023 |
| MSI           | Prestige 15 A10SC           | Notebook    | [796a2f6a53](https://linux-hardware.org/?probe=796a2f6a53) | Oct 25, 2023 |
| ASUSTek       | GL752VW                     | Notebook    | [a11cf1d28d](https://linux-hardware.org/?probe=a11cf1d28d) | Oct 25, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | Desktop     | [9207de9b44](https://linux-hardware.org/?probe=9207de9b44) | Oct 25, 2023 |
| Acer          | Aspire 9300                 | Notebook    | [3094b549c5](https://linux-hardware.org/?probe=3094b549c5) | Oct 25, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [50abb592dd](https://linux-hardware.org/?probe=50abb592dd) | Oct 25, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [61ec26bc75](https://linux-hardware.org/?probe=61ec26bc75) | Oct 24, 2023 |
| HP            | 14                          | Notebook    | [5e8b808f2f](https://linux-hardware.org/?probe=5e8b808f2f) | Oct 24, 2023 |
| TUXEDO        | InfinityBook Pro Gen8 (M... | Notebook    | [3907a62f64](https://linux-hardware.org/?probe=3907a62f64) | Oct 24, 2023 |
| Gigabyte      | B85M-D3V Plus               | Desktop     | [845b1f10ef](https://linux-hardware.org/?probe=845b1f10ef) | Oct 24, 2023 |
| rocky         | ASUS EXPERTBOOK B1402CBA... | Notebook    | [e7dc573b01](https://linux-hardware.org/?probe=e7dc573b01) | Oct 23, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B2502CBA... | Notebook    | [823dcebef0](https://linux-hardware.org/?probe=823dcebef0) | Oct 23, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B2502CBA... | Notebook    | [b7e1e895b9](https://linux-hardware.org/?probe=b7e1e895b9) | Oct 23, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | Notebook    | [f4375f7115](https://linux-hardware.org/?probe=f4375f7115) | Oct 23, 2023 |
| Acer          | TravelMate P259-M           | Notebook    | [d6096c6736](https://linux-hardware.org/?probe=d6096c6736) | Oct 23, 2023 |
| ASUSTek       | T101HA                      | Tablet      | [7190f336e0](https://linux-hardware.org/?probe=7190f336e0) | Oct 23, 2023 |
| ASUSTek       | T101HA                      | Tablet      | [fc5437cf30](https://linux-hardware.org/?probe=fc5437cf30) | Oct 22, 2023 |
| ASUSTek       | ROG Flow X13 GV301RC_GV3... | Convertible | [2d3766505f](https://linux-hardware.org/?probe=2d3766505f) | Oct 22, 2023 |
| ASUSTek       | X551CA                      | Notebook    | [43c37fb1fe](https://linux-hardware.org/?probe=43c37fb1fe) | Oct 22, 2023 |
| ASUSTek       | X551CA                      | Notebook    | [e9a381c722](https://linux-hardware.org/?probe=e9a381c722) | Oct 22, 2023 |
| MSI           | MS-B0621 100                | All in one  | [f1b56a371d](https://linux-hardware.org/?probe=f1b56a371d) | Oct 22, 2023 |
| AZW           | SEi                         | Notebook    | [94602bd41b](https://linux-hardware.org/?probe=94602bd41b) | Oct 22, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [918cd67301](https://linux-hardware.org/?probe=918cd67301) | Oct 22, 2023 |
| Acer          | Aspire A715-76G             | Notebook    | [448723995f](https://linux-hardware.org/?probe=448723995f) | Oct 22, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [c5027da111](https://linux-hardware.org/?probe=c5027da111) | Oct 22, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [04a430e244](https://linux-hardware.org/?probe=04a430e244) | Oct 22, 2023 |
| Gigabyte      | GA-MA790XT-UD4P             | Desktop     | [ad17620d9f](https://linux-hardware.org/?probe=ad17620d9f) | Oct 21, 2023 |
| Gigabyte      | Z390 UD                     | Desktop     | [edf8acb455](https://linux-hardware.org/?probe=edf8acb455) | Oct 21, 2023 |
| ASRock        | N68C-S UCC                  | Desktop     | [6468bd6335](https://linux-hardware.org/?probe=6468bd6335) | Oct 21, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [59d8c7186d](https://linux-hardware.org/?probe=59d8c7186d) | Oct 21, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [f2ee678da1](https://linux-hardware.org/?probe=f2ee678da1) | Oct 21, 2023 |
| Gigabyte      | GA-MA790XT-UD4P             | Desktop     | [9286fa6477](https://linux-hardware.org/?probe=9286fa6477) | Oct 21, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [37cdbd73b0](https://linux-hardware.org/?probe=37cdbd73b0) | Oct 21, 2023 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [ff0d8bbab4](https://linux-hardware.org/?probe=ff0d8bbab4) | Oct 21, 2023 |
| HP            | TouchSmart tm2              | Notebook    | [a79b82edd3](https://linux-hardware.org/?probe=a79b82edd3) | Oct 21, 2023 |
| Packard Be... | IMEDIA S3840                | Desktop     | [3cc1398528](https://linux-hardware.org/?probe=3cc1398528) | Oct 21, 2023 |
| ASUSTek       | ROG STRIX B450-E GAMING     | Desktop     | [2d07542448](https://linux-hardware.org/?probe=2d07542448) | Oct 20, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [56621ceace](https://linux-hardware.org/?probe=56621ceace) | Oct 20, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [e02418f8c1](https://linux-hardware.org/?probe=e02418f8c1) | Oct 20, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [7323684232](https://linux-hardware.org/?probe=7323684232) | Oct 20, 2023 |
| Sony          | VPCSB2L1R                   | Notebook    | [153440d631](https://linux-hardware.org/?probe=153440d631) | Oct 20, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [17b8a78644](https://linux-hardware.org/?probe=17b8a78644) | Oct 20, 2023 |
| Razer         | Blade 14 (2022) - RZ09-0... | Notebook    | [64929e25f7](https://linux-hardware.org/?probe=64929e25f7) | Oct 20, 2023 |
| Chuwi         | MiniBook                    | Notebook    | [baaf33908c](https://linux-hardware.org/?probe=baaf33908c) | Oct 20, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [fe5af0991d](https://linux-hardware.org/?probe=fe5af0991d) | Oct 20, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [6e5d214cb8](https://linux-hardware.org/?probe=6e5d214cb8) | Oct 20, 2023 |
| Razer         | Blade 14 (2022) - RZ09-0... | Notebook    | [da8f06a8e0](https://linux-hardware.org/?probe=da8f06a8e0) | Oct 19, 2023 |
| Toshiba       | Satellite P50t-B-118        | Notebook    | [5237c0866e](https://linux-hardware.org/?probe=5237c0866e) | Oct 19, 2023 |
| Dell          | Precision 7760              | Notebook    | [30e33a33c3](https://linux-hardware.org/?probe=30e33a33c3) | Oct 19, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [0fa5f53ce0](https://linux-hardware.org/?probe=0fa5f53ce0) | Oct 19, 2023 |
| ASUSTek       | M4A78LT-M                   | Desktop     | [cc8d1f7fb2](https://linux-hardware.org/?probe=cc8d1f7fb2) | Oct 19, 2023 |
| ASUSTek       | X555QG                      | Notebook    | [e2e11a852f](https://linux-hardware.org/?probe=e2e11a852f) | Oct 19, 2023 |
| ASUSTek       | K46CB                       | Notebook    | [58573f017a](https://linux-hardware.org/?probe=58573f017a) | Oct 19, 2023 |
| HP            | TouchSmart tm2              | Notebook    | [f72f6a43b5](https://linux-hardware.org/?probe=f72f6a43b5) | Oct 19, 2023 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [491538303f](https://linux-hardware.org/?probe=491538303f) | Oct 19, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [9c9781a7ee](https://linux-hardware.org/?probe=9c9781a7ee) | Oct 19, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [a25bc084fc](https://linux-hardware.org/?probe=a25bc084fc) | Oct 19, 2023 |
| ASUSTek       | T101HA                      | Tablet      | [b3cd8983eb](https://linux-hardware.org/?probe=b3cd8983eb) | Oct 18, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [cb9366b6ae](https://linux-hardware.org/?probe=cb9366b6ae) | Oct 18, 2023 |
| HP            | 2B52                        | Desktop     | [b14a00a196](https://linux-hardware.org/?probe=b14a00a196) | Oct 18, 2023 |
| HP            | 250 G3                      | Notebook    | [e4e0140eb3](https://linux-hardware.org/?probe=e4e0140eb3) | Oct 18, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [b99a873ab7](https://linux-hardware.org/?probe=b99a873ab7) | Oct 18, 2023 |
| ASUSTek       | K46CB                       | Notebook    | [f524007ed7](https://linux-hardware.org/?probe=f524007ed7) | Oct 18, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [2530967a90](https://linux-hardware.org/?probe=2530967a90) | Oct 17, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [0ca9b4c2bd](https://linux-hardware.org/?probe=0ca9b4c2bd) | Oct 17, 2023 |
| HP            | Pavilion dv6                | Notebook    | [0846a94456](https://linux-hardware.org/?probe=0846a94456) | Oct 17, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [200b756e67](https://linux-hardware.org/?probe=200b756e67) | Oct 17, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DL... | Notebook    | [060a9c66c5](https://linux-hardware.org/?probe=060a9c66c5) | Oct 17, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [295c6b08bd](https://linux-hardware.org/?probe=295c6b08bd) | Oct 17, 2023 |
| ASUSTek       | N61Jv                       | Notebook    | [cb8a1ca22a](https://linux-hardware.org/?probe=cb8a1ca22a) | Oct 17, 2023 |
| ASUSTek       | X500MA                      | Desktop     | [2ffe0522e1](https://linux-hardware.org/?probe=2ffe0522e1) | Oct 17, 2023 |
| MSI           | Prestige 14H B12UCX         | Notebook    | [81dac6f109](https://linux-hardware.org/?probe=81dac6f109) | Oct 17, 2023 |
| HP            | ProBook 440 G6              | Notebook    | [5860734f3a](https://linux-hardware.org/?probe=5860734f3a) | Oct 16, 2023 |
| Allview       | Allbook H                   | Notebook    | [456afe3921](https://linux-hardware.org/?probe=456afe3921) | Oct 16, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d519c10989](https://linux-hardware.org/?probe=d519c10989) | Oct 16, 2023 |
| Pine Micro... | Pine64 PineTab2 v2.0        | Soc         | [8efa3d8f19](https://linux-hardware.org/?probe=8efa3d8f19) | Oct 16, 2023 |
| MSI           | Modern 14 A10RAS            | Notebook    | [571e9b4e91](https://linux-hardware.org/?probe=571e9b4e91) | Oct 15, 2023 |
| ASUSTek       | UX550VD                     | Notebook    | [a58d0c5f1c](https://linux-hardware.org/?probe=a58d0c5f1c) | Oct 15, 2023 |
| ASUSTek       | UX550VD                     | Notebook    | [c29e83963a](https://linux-hardware.org/?probe=c29e83963a) | Oct 15, 2023 |
| Teclast       | F7 Plus                     | Notebook    | [8c4d203e84](https://linux-hardware.org/?probe=8c4d203e84) | Oct 15, 2023 |
| Google        | Dratini                     | Notebook    | [0c74e4ac18](https://linux-hardware.org/?probe=0c74e4ac18) | Oct 15, 2023 |
| Google        | Dratini                     | Notebook    | [bc181ae269](https://linux-hardware.org/?probe=bc181ae269) | Oct 15, 2023 |
| Dell          | XPS 13 9343                 | Notebook    | [97a3c4d92d](https://linux-hardware.org/?probe=97a3c4d92d) | Oct 15, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [374a5bf116](https://linux-hardware.org/?probe=374a5bf116) | Oct 15, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [7919d1517f](https://linux-hardware.org/?probe=7919d1517f) | Oct 14, 2023 |
| MSI           | Prestige 14H B12UCX         | Notebook    | [ddc0082c22](https://linux-hardware.org/?probe=ddc0082c22) | Oct 14, 2023 |
| MSI           | MAG B550 TORPEDO            | Desktop     | [2bb3baf0f6](https://linux-hardware.org/?probe=2bb3baf0f6) | Oct 14, 2023 |
| Dell          | Latitude E4200              | Notebook    | [2a5bbc07aa](https://linux-hardware.org/?probe=2a5bbc07aa) | Oct 14, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [11d91a0246](https://linux-hardware.org/?probe=11d91a0246) | Oct 14, 2023 |
| Medion        | E15415                      | Notebook    | [b9a4ecdc97](https://linux-hardware.org/?probe=b9a4ecdc97) | Oct 14, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [584433cc95](https://linux-hardware.org/?probe=584433cc95) | Oct 14, 2023 |
| Intel         | JSL MRD                     | Desktop     | [a39b6e2f92](https://linux-hardware.org/?probe=a39b6e2f92) | Oct 14, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [36ce3b4e93](https://linux-hardware.org/?probe=36ce3b4e93) | Oct 13, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [b572583fd2](https://linux-hardware.org/?probe=b572583fd2) | Oct 13, 2023 |
| MSI           | Prestige 14H B12UCX         | Notebook    | [63a132c897](https://linux-hardware.org/?probe=63a132c897) | Oct 13, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [5ee0d65118](https://linux-hardware.org/?probe=5ee0d65118) | Oct 13, 2023 |
| Panasonic     | CF-C1AD06GDE                | Notebook    | [473265139b](https://linux-hardware.org/?probe=473265139b) | Oct 13, 2023 |
| HP            | 1998                        | Desktop     | [e8d3c2b8ef](https://linux-hardware.org/?probe=e8d3c2b8ef) | Oct 12, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [b53da36041](https://linux-hardware.org/?probe=b53da36041) | Oct 12, 2023 |
| HP            | Unknown                     | Notebook    | [c64a37f28f](https://linux-hardware.org/?probe=c64a37f28f) | Oct 12, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [ba690b36a3](https://linux-hardware.org/?probe=ba690b36a3) | Oct 12, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [4957e141ac](https://linux-hardware.org/?probe=4957e141ac) | Oct 12, 2023 |
| MSI           | PS42 Modern 8MO             | Notebook    | [be9a0659d4](https://linux-hardware.org/?probe=be9a0659d4) | Oct 11, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [0baddc9010](https://linux-hardware.org/?probe=0baddc9010) | Oct 11, 2023 |
| HP            | 240 G8 Notebook PC          | Notebook    | [0a98dcd952](https://linux-hardware.org/?probe=0a98dcd952) | Oct 11, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [0cbd266486](https://linux-hardware.org/?probe=0cbd266486) | Oct 11, 2023 |
| Toshiba       | QOSMIO X70-B                | Notebook    | [fc0abd191f](https://linux-hardware.org/?probe=fc0abd191f) | Oct 11, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [670b2194c0](https://linux-hardware.org/?probe=670b2194c0) | Oct 11, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [046e552e27](https://linux-hardware.org/?probe=046e552e27) | Oct 11, 2023 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | Notebook    | [d7d6c74d55](https://linux-hardware.org/?probe=d7d6c74d55) | Oct 11, 2023 |
| Dell          | 09CKT0 A03                  | Desktop     | [27c33c2ec5](https://linux-hardware.org/?probe=27c33c2ec5) | Oct 11, 2023 |
| ASRock        | X79 Extreme9                | Desktop     | [4a0805a07a](https://linux-hardware.org/?probe=4a0805a07a) | Oct 11, 2023 |
| Lenovo        | G580 2189                   | Notebook    | [ea46e68be2](https://linux-hardware.org/?probe=ea46e68be2) | Oct 11, 2023 |
| Valve         | Jupiter                     | Notebook    | [2bde49db66](https://linux-hardware.org/?probe=2bde49db66) | Oct 11, 2023 |
| Intel         | X99                         | Desktop     | [c025563ec2](https://linux-hardware.org/?probe=c025563ec2) | Oct 10, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [68372adfc5](https://linux-hardware.org/?probe=68372adfc5) | Oct 10, 2023 |
| ASUSTek       | S550CM                      | Notebook    | [ad1b08de66](https://linux-hardware.org/?probe=ad1b08de66) | Oct 10, 2023 |
| AZW           | Green G5                    | Desktop     | [cb5efe1873](https://linux-hardware.org/?probe=cb5efe1873) | Oct 10, 2023 |
| HP            | 8054                        | Desktop     | [66ad5550d1](https://linux-hardware.org/?probe=66ad5550d1) | Oct 10, 2023 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [947e4c6b2f](https://linux-hardware.org/?probe=947e4c6b2f) | Oct 10, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [fed7f26361](https://linux-hardware.org/?probe=fed7f26361) | Oct 10, 2023 |
| MSI           | MS-7125                     | Desktop     | [2e6837be6d](https://linux-hardware.org/?probe=2e6837be6d) | Oct 10, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [3f6528d99d](https://linux-hardware.org/?probe=3f6528d99d) | Oct 10, 2023 |
| HP            | 89B5 A                      | Desktop     | [746fef0fc7](https://linux-hardware.org/?probe=746fef0fc7) | Oct 10, 2023 |
| MSI           | B450M BAZOOKA V2            | Desktop     | [3b598550c2](https://linux-hardware.org/?probe=3b598550c2) | Oct 10, 2023 |
| Lenovo        | ThinkPad L540 20AUS11P00    | Notebook    | [ec64651cec](https://linux-hardware.org/?probe=ec64651cec) | Oct 10, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [333535db5f](https://linux-hardware.org/?probe=333535db5f) | Oct 10, 2023 |
| Teclast       | F7S                         | Notebook    | [92c51af32a](https://linux-hardware.org/?probe=92c51af32a) | Oct 10, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [6d2a6c2a6f](https://linux-hardware.org/?probe=6d2a6c2a6f) | Oct 09, 2023 |
| Apple         | MacBookAir5,1               | Notebook    | [e4f9055fce](https://linux-hardware.org/?probe=e4f9055fce) | Oct 09, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [a41b75e081](https://linux-hardware.org/?probe=a41b75e081) | Oct 09, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [ac6149e371](https://linux-hardware.org/?probe=ac6149e371) | Oct 08, 2023 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [fd3c1d1196](https://linux-hardware.org/?probe=fd3c1d1196) | Oct 08, 2023 |
| Valve         | Jupiter                     | Notebook    | [86be8c226a](https://linux-hardware.org/?probe=86be8c226a) | Oct 08, 2023 |
| HP            | Notebook                    | Notebook    | [a181ec12af](https://linux-hardware.org/?probe=a181ec12af) | Oct 08, 2023 |
| HP            | Notebook                    | Notebook    | [039a70e9ce](https://linux-hardware.org/?probe=039a70e9ce) | Oct 07, 2023 |
| Dell          | Inspiron 16 Plus 7630       | Notebook    | [51571d43df](https://linux-hardware.org/?probe=51571d43df) | Oct 07, 2023 |
| Lenovo        | 370A SDK0J40709 WIN 3259... | Desktop     | [38c0c97684](https://linux-hardware.org/?probe=38c0c97684) | Oct 07, 2023 |
| Pegatron      | EVANS                       | Desktop     | [f798f24c90](https://linux-hardware.org/?probe=f798f24c90) | Oct 07, 2023 |
| VANT          | MOOVE14_2023                | Notebook    | [d9379b5405](https://linux-hardware.org/?probe=d9379b5405) | Oct 06, 2023 |
| Dell          | Latitude 7275               | Notebook    | [f1892c721d](https://linux-hardware.org/?probe=f1892c721d) | Oct 06, 2023 |
| Allview       | Allbook H                   | Notebook    | [9c1933c4eb](https://linux-hardware.org/?probe=9c1933c4eb) | Oct 06, 2023 |
| MSI           | GE63 Raider RGB 8RE         | Notebook    | [39b9855097](https://linux-hardware.org/?probe=39b9855097) | Oct 05, 2023 |
| MSI           | GE63 Raider RGB 8RE         | Notebook    | [74bb875f9f](https://linux-hardware.org/?probe=74bb875f9f) | Oct 05, 2023 |
| Packard Be... | MCP73PV                     | Desktop     | [dc24306f2f](https://linux-hardware.org/?probe=dc24306f2f) | Oct 05, 2023 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [2070a1032e](https://linux-hardware.org/?probe=2070a1032e) | Oct 05, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [377e8e1994](https://linux-hardware.org/?probe=377e8e1994) | Oct 05, 2023 |
| Lenovo        | G580 2189                   | Notebook    | [bd7f2d9d03](https://linux-hardware.org/?probe=bd7f2d9d03) | Oct 05, 2023 |
| MSI           | Prestige 15 A11SCX          | Notebook    | [9a4bc722e5](https://linux-hardware.org/?probe=9a4bc722e5) | Oct 05, 2023 |
| Lenovo        | B50-80 80LT                 | Notebook    | [74b54d0f3f](https://linux-hardware.org/?probe=74b54d0f3f) | Oct 05, 2023 |
| Acer          | Aspire M3-581G              | Notebook    | [040dc9b84b](https://linux-hardware.org/?probe=040dc9b84b) | Oct 04, 2023 |
| HP            | EliteBook 745 G6            | Notebook    | [77cfc34723](https://linux-hardware.org/?probe=77cfc34723) | Oct 04, 2023 |
| ASUSTek       | A88XM-E                     | Desktop     | [cef182f4e0](https://linux-hardware.org/?probe=cef182f4e0) | Oct 04, 2023 |
| Apple         | MacBookPro14,2              | Notebook    | [49a295d5f0](https://linux-hardware.org/?probe=49a295d5f0) | Oct 04, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [6c95b1e3b2](https://linux-hardware.org/?probe=6c95b1e3b2) | Oct 04, 2023 |
| Packard Be... | MCP73PV                     | Desktop     | [2ecd860fef](https://linux-hardware.org/?probe=2ecd860fef) | Oct 03, 2023 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [e583e35b95](https://linux-hardware.org/?probe=e583e35b95) | Oct 03, 2023 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [538889d79f](https://linux-hardware.org/?probe=538889d79f) | Oct 03, 2023 |
| HP            | ENVY 15                     | Notebook    | [589ff0a0af](https://linux-hardware.org/?probe=589ff0a0af) | Oct 03, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c77065abde](https://linux-hardware.org/?probe=c77065abde) | Oct 03, 2023 |
| Acer          | TravelMate P414-51          | Notebook    | [520fe0b494](https://linux-hardware.org/?probe=520fe0b494) | Oct 03, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [6615883de3](https://linux-hardware.org/?probe=6615883de3) | Oct 03, 2023 |
| Pegatron      | EVANS                       | Desktop     | [3f2a4fe53e](https://linux-hardware.org/?probe=3f2a4fe53e) | Oct 03, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [8fd9631bea](https://linux-hardware.org/?probe=8fd9631bea) | Oct 03, 2023 |
| Supermicro    | X10SL7-F                    | Server      | [5e6d01b044](https://linux-hardware.org/?probe=5e6d01b044) | Oct 03, 2023 |
| Dynabook      | Satellite Pro C50-G         | Notebook    | [36e6d60078](https://linux-hardware.org/?probe=36e6d60078) | Oct 02, 2023 |
| ASUSTek       | ROG Strix G513IH_G513IH     | Notebook    | [7d076d124e](https://linux-hardware.org/?probe=7d076d124e) | Oct 02, 2023 |
| Dynabook      | Satellite Pro C50-E-11H     | Notebook    | [29d9d8dd30](https://linux-hardware.org/?probe=29d9d8dd30) | Oct 02, 2023 |
| Shuttle       | DS47D                       | Notebook    | [d4c27bdf9e](https://linux-hardware.org/?probe=d4c27bdf9e) | Oct 02, 2023 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [bc03d7f758](https://linux-hardware.org/?probe=bc03d7f758) | Oct 02, 2023 |
| MSI           | Vector GP68HX 12VH          | Notebook    | [e582127237](https://linux-hardware.org/?probe=e582127237) | Oct 02, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | Desktop     | [76c5466daa](https://linux-hardware.org/?probe=76c5466daa) | Oct 02, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [6fb4d2a754](https://linux-hardware.org/?probe=6fb4d2a754) | Oct 01, 2023 |
| HP            | 3397                        | Desktop     | [fac50277cc](https://linux-hardware.org/?probe=fac50277cc) | Oct 01, 2023 |
| HP            | Presario CQ57               | Notebook    | [e83f052dc8](https://linux-hardware.org/?probe=e83f052dc8) | Oct 01, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [96ce4b8060](https://linux-hardware.org/?probe=96ce4b8060) | Oct 01, 2023 |
| Packard Be... | DOT S                       | Notebook    | [5fd6d403d1](https://linux-hardware.org/?probe=5fd6d403d1) | Oct 01, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [2e7aba6432](https://linux-hardware.org/?probe=2e7aba6432) | Oct 01, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [279922964e](https://linux-hardware.org/?probe=279922964e) | Oct 01, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [085fbda5a6](https://linux-hardware.org/?probe=085fbda5a6) | Sep 30, 2023 |
| MSI           | Prestige 14H B12UCX         | Notebook    | [b3a006adc7](https://linux-hardware.org/?probe=b3a006adc7) | Sep 30, 2023 |
| MSI           | Prestige 15 A10SC           | Notebook    | [6e53cd8a65](https://linux-hardware.org/?probe=6e53cd8a65) | Sep 30, 2023 |
| MSI           | Prestige 14H B12UCX         | Notebook    | [1c1f35d1c8](https://linux-hardware.org/?probe=1c1f35d1c8) | Sep 30, 2023 |
| Dell          | 0Y56T3 A01                  | Desktop     | [bfc1d1dd13](https://linux-hardware.org/?probe=bfc1d1dd13) | Sep 30, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [3421ba07f9](https://linux-hardware.org/?probe=3421ba07f9) | Sep 30, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [480316a0da](https://linux-hardware.org/?probe=480316a0da) | Sep 30, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [2fc3f16671](https://linux-hardware.org/?probe=2fc3f16671) | Sep 30, 2023 |
| Packard Be... | EasyNote TK85               | Notebook    | [0c62f48dda](https://linux-hardware.org/?probe=0c62f48dda) | Sep 30, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [3c9f4d4aef](https://linux-hardware.org/?probe=3c9f4d4aef) | Sep 29, 2023 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [4d2f60a496](https://linux-hardware.org/?probe=4d2f60a496) | Sep 29, 2023 |
| Lenovo        | Z50-70 20354                | Notebook    | [eb33abdaae](https://linux-hardware.org/?probe=eb33abdaae) | Sep 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [4a6090c2f4](https://linux-hardware.org/?probe=4a6090c2f4) | Sep 29, 2023 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [08fb652352](https://linux-hardware.org/?probe=08fb652352) | Sep 29, 2023 |
| HP            | Laptop 15-fd0xxx            | Notebook    | [0a548c4390](https://linux-hardware.org/?probe=0a548c4390) | Sep 28, 2023 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [b6316ea4df](https://linux-hardware.org/?probe=b6316ea4df) | Sep 28, 2023 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [f75ab187aa](https://linux-hardware.org/?probe=f75ab187aa) | Sep 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [426e8bd9c0](https://linux-hardware.org/?probe=426e8bd9c0) | Sep 28, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [3c4c65947a](https://linux-hardware.org/?probe=3c4c65947a) | Sep 28, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | Desktop     | [41f0f8666c](https://linux-hardware.org/?probe=41f0f8666c) | Sep 27, 2023 |
| Packard Be... | EasyNote TK85               | Notebook    | [79e6dd1302](https://linux-hardware.org/?probe=79e6dd1302) | Sep 27, 2023 |
| Dell          | XPS 9315                    | Notebook    | [6fa1beb451](https://linux-hardware.org/?probe=6fa1beb451) | Sep 26, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [2bdd48e441](https://linux-hardware.org/?probe=2bdd48e441) | Sep 26, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [14cbad7097](https://linux-hardware.org/?probe=14cbad7097) | Sep 26, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [1e61c0fb6b](https://linux-hardware.org/?probe=1e61c0fb6b) | Sep 26, 2023 |
| LG Electro... | 13U70Q-G.AA75B              | Notebook    | [f38b79055b](https://linux-hardware.org/?probe=f38b79055b) | Sep 26, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [dd48e0075b](https://linux-hardware.org/?probe=dd48e0075b) | Sep 26, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [21c3145a6a](https://linux-hardware.org/?probe=21c3145a6a) | Sep 26, 2023 |
| MSI           | GF75 Thin 10SC              | Notebook    | [f19700e7b0](https://linux-hardware.org/?probe=f19700e7b0) | Sep 26, 2023 |
| MSI           | GF75 Thin 10SC              | Notebook    | [a7610be494](https://linux-hardware.org/?probe=a7610be494) | Sep 26, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [786338b217](https://linux-hardware.org/?probe=786338b217) | Sep 26, 2023 |
| Sony          | VPCSB2L1R                   | Notebook    | [9395b9347e](https://linux-hardware.org/?probe=9395b9347e) | Sep 26, 2023 |
| Acer          | Extensa 5635Z               | Notebook    | [19afe08920](https://linux-hardware.org/?probe=19afe08920) | Sep 25, 2023 |
| ASUSTek       | TUF B360-PRO GAMING WIFI    | Desktop     | [16c22d9ead](https://linux-hardware.org/?probe=16c22d9ead) | Sep 25, 2023 |
| Dell          | 0441XG A04                  | Server      | [60298ae886](https://linux-hardware.org/?probe=60298ae886) | Sep 25, 2023 |
| BESSTAR Te... | HM90                        | Desktop     | [a85d516a80](https://linux-hardware.org/?probe=a85d516a80) | Sep 25, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [1deb55b03b](https://linux-hardware.org/?probe=1deb55b03b) | Sep 25, 2023 |
| Fanless Mi... | PCG02 GLE                   | Stick pc    | [6dca52cc54](https://linux-hardware.org/?probe=6dca52cc54) | Sep 25, 2023 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [c50564e3bb](https://linux-hardware.org/?probe=c50564e3bb) | Sep 25, 2023 |
| ASRock        | 970 Extreme4                | Desktop     | [4b78e93dff](https://linux-hardware.org/?probe=4b78e93dff) | Sep 25, 2023 |
| ASRock        | 970 Extreme4                | Desktop     | [e05aa71be7](https://linux-hardware.org/?probe=e05aa71be7) | Sep 25, 2023 |
| Sony          | SVF14A15CXB                 | Notebook    | [cbce21a887](https://linux-hardware.org/?probe=cbce21a887) | Sep 25, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [7d4c2dc8f6](https://linux-hardware.org/?probe=7d4c2dc8f6) | Sep 25, 2023 |
| Biostar       | A68N-2100K                  | Desktop     | [38a92e23c8](https://linux-hardware.org/?probe=38a92e23c8) | Sep 24, 2023 |
| Dell          | 0T10XW A02                  | Desktop     | [5df1a942d9](https://linux-hardware.org/?probe=5df1a942d9) | Sep 24, 2023 |
| Raspberry ... | Raspberry Pi 2 Model B R... | Soc         | [1c09a9f9c9](https://linux-hardware.org/?probe=1c09a9f9c9) | Sep 23, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [54ed40361d](https://linux-hardware.org/?probe=54ed40361d) | Sep 23, 2023 |
| Lenovo        | G580 2189                   | Notebook    | [7ddc30adc9](https://linux-hardware.org/?probe=7ddc30adc9) | Sep 23, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [a579fd2872](https://linux-hardware.org/?probe=a579fd2872) | Sep 23, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [fdfd7f2e50](https://linux-hardware.org/?probe=fdfd7f2e50) | Sep 23, 2023 |
| Lenovo        | G580 2189                   | Notebook    | [fe1c9060da](https://linux-hardware.org/?probe=fe1c9060da) | Sep 23, 2023 |
| Packard Be... | EasyNote TK85               | Notebook    | [c970ee5a12](https://linux-hardware.org/?probe=c970ee5a12) | Sep 23, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [30a324bad7](https://linux-hardware.org/?probe=30a324bad7) | Sep 23, 2023 |
| HP            | Pavilion g6                 | Notebook    | [226a590989](https://linux-hardware.org/?probe=226a590989) | Sep 23, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [347b768d57](https://linux-hardware.org/?probe=347b768d57) | Sep 22, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [6ae9f9d9f2](https://linux-hardware.org/?probe=6ae9f9d9f2) | Sep 22, 2023 |
| Toshiba       | Satellite Pro R40-D         | Notebook    | [d33d1b7b77](https://linux-hardware.org/?probe=d33d1b7b77) | Sep 22, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [fd5d5651ce](https://linux-hardware.org/?probe=fd5d5651ce) | Sep 22, 2023 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [81bf9d5194](https://linux-hardware.org/?probe=81bf9d5194) | Sep 22, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [7b093ed910](https://linux-hardware.org/?probe=7b093ed910) | Sep 22, 2023 |
| Primux Tec... | Primux_1406F_W10            | Notebook    | [a1911e4e9a](https://linux-hardware.org/?probe=a1911e4e9a) | Sep 22, 2023 |
| ASUSTek       | ZenBook Pro 15 UX550GEX_... | Notebook    | [aee02d5429](https://linux-hardware.org/?probe=aee02d5429) | Sep 22, 2023 |
| Dell          | XPS 9320                    | Notebook    | [1fe2e34799](https://linux-hardware.org/?probe=1fe2e34799) | Sep 22, 2023 |
| Primux Tec... | Primux_1406F_W10            | Notebook    | [c267e8d9a3](https://linux-hardware.org/?probe=c267e8d9a3) | Sep 22, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [146d33a16d](https://linux-hardware.org/?probe=146d33a16d) | Sep 22, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [7c5cc5e0ab](https://linux-hardware.org/?probe=7c5cc5e0ab) | Sep 22, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [74fa7aed8b](https://linux-hardware.org/?probe=74fa7aed8b) | Sep 22, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [28c84c64c1](https://linux-hardware.org/?probe=28c84c64c1) | Sep 21, 2023 |
| HP            | 18E7                        | Desktop     | [ba0cb8996d](https://linux-hardware.org/?probe=ba0cb8996d) | Sep 21, 2023 |
| HP            | 1495                        | Desktop     | [ad97ea883d](https://linux-hardware.org/?probe=ad97ea883d) | Sep 21, 2023 |
| Acer          | Aspire F5-571               | Notebook    | [21bcc4a506](https://linux-hardware.org/?probe=21bcc4a506) | Sep 21, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [f9430fd075](https://linux-hardware.org/?probe=f9430fd075) | Sep 21, 2023 |
| ASUSTek       | PRIME X670E-PRO WIFI        | Desktop     | [f87766b547](https://linux-hardware.org/?probe=f87766b547) | Sep 21, 2023 |
| ASUSTek       | B150M-A                     | Desktop     | [d2e741051e](https://linux-hardware.org/?probe=d2e741051e) | Sep 21, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [03c9da6c46](https://linux-hardware.org/?probe=03c9da6c46) | Sep 20, 2023 |
| MSI           | Indio                       | Desktop     | [330a2c9640](https://linux-hardware.org/?probe=330a2c9640) | Sep 20, 2023 |
| Intel         | DG31PR AAD97573-205         | Desktop     | [a25329cfdb](https://linux-hardware.org/?probe=a25329cfdb) | Sep 20, 2023 |
| MSI           | Prestige 14 A10SC           | Notebook    | [6f81167a6c](https://linux-hardware.org/?probe=6f81167a6c) | Sep 20, 2023 |
| Toshiba       | PORTEGE X30-E               | Notebook    | [2225b3687d](https://linux-hardware.org/?probe=2225b3687d) | Sep 20, 2023 |
| MSI           | Prestige 14 A10SC           | Notebook    | [e0ee68b1a7](https://linux-hardware.org/?probe=e0ee68b1a7) | Sep 20, 2023 |
| ASUSTek       | X556UQ                      | Notebook    | [c34d9b9514](https://linux-hardware.org/?probe=c34d9b9514) | Sep 20, 2023 |
| ASUSTek       | X556UQ                      | Notebook    | [7ec3567855](https://linux-hardware.org/?probe=7ec3567855) | Sep 20, 2023 |
| ASUSTek       | X556UQ                      | Notebook    | [676dd13401](https://linux-hardware.org/?probe=676dd13401) | Sep 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [8b6f78da91](https://linux-hardware.org/?probe=8b6f78da91) | Sep 20, 2023 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [a2f44141ba](https://linux-hardware.org/?probe=a2f44141ba) | Sep 20, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [911f7b8df2](https://linux-hardware.org/?probe=911f7b8df2) | Sep 19, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [6edec4d045](https://linux-hardware.org/?probe=6edec4d045) | Sep 19, 2023 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [b858f753b2](https://linux-hardware.org/?probe=b858f753b2) | Sep 19, 2023 |
| ASUSTek       | P5K-E                       | Desktop     | [233a59e640](https://linux-hardware.org/?probe=233a59e640) | Sep 18, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [bb3c1bf2b9](https://linux-hardware.org/?probe=bb3c1bf2b9) | Sep 18, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [4e845095f4](https://linux-hardware.org/?probe=4e845095f4) | Sep 18, 2023 |
| HP            | ProBook 4530s               | Notebook    | [251e7cc45b](https://linux-hardware.org/?probe=251e7cc45b) | Sep 18, 2023 |
| Biostar       | A68N-2100K                  | Desktop     | [56340d8ed4](https://linux-hardware.org/?probe=56340d8ed4) | Sep 18, 2023 |
| ASUSTek       | A88XM-PLUS                  | Desktop     | [ab79a26993](https://linux-hardware.org/?probe=ab79a26993) | Sep 18, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [1e40d8e0b9](https://linux-hardware.org/?probe=1e40d8e0b9) | Sep 18, 2023 |
| Samsung       | Galaxy TabPro S             | Tablet      | [0866503148](https://linux-hardware.org/?probe=0866503148) | Sep 17, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [178981670d](https://linux-hardware.org/?probe=178981670d) | Sep 17, 2023 |
| HP            | Pavilion g6                 | Notebook    | [158b6f4df9](https://linux-hardware.org/?probe=158b6f4df9) | Sep 17, 2023 |
| Google        | Droid                       | Notebook    | [e0a0628d0a](https://linux-hardware.org/?probe=e0a0628d0a) | Sep 17, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [1398fa87b2](https://linux-hardware.org/?probe=1398fa87b2) | Sep 17, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [d37d40b74c](https://linux-hardware.org/?probe=d37d40b74c) | Sep 16, 2023 |
| ASRock        | 960GC-GS FX                 | Desktop     | [513b6982f2](https://linux-hardware.org/?probe=513b6982f2) | Sep 16, 2023 |
| Valve         | Jupiter                     | Notebook    | [3bd1c975cc](https://linux-hardware.org/?probe=3bd1c975cc) | Sep 16, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [020deea6d9](https://linux-hardware.org/?probe=020deea6d9) | Sep 15, 2023 |
| MSI           | MPG Z590 GAMING PLUS        | Desktop     | [cfa86cec4f](https://linux-hardware.org/?probe=cfa86cec4f) | Sep 15, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [fa347b6b46](https://linux-hardware.org/?probe=fa347b6b46) | Sep 15, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [add3c0be93](https://linux-hardware.org/?probe=add3c0be93) | Sep 15, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [c8ac03221f](https://linux-hardware.org/?probe=c8ac03221f) | Sep 15, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [1322cd195f](https://linux-hardware.org/?probe=1322cd195f) | Sep 15, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [b76ae8f9db](https://linux-hardware.org/?probe=b76ae8f9db) | Sep 15, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [f48f6375b2](https://linux-hardware.org/?probe=f48f6375b2) | Sep 15, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [9390e3d243](https://linux-hardware.org/?probe=9390e3d243) | Sep 15, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [9fc334d8b3](https://linux-hardware.org/?probe=9fc334d8b3) | Sep 15, 2023 |
| ASUSTek       | ROG Strix G713IC_G713IC     | Notebook    | [fd2d28b8af](https://linux-hardware.org/?probe=fd2d28b8af) | Sep 14, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [b0702745f5](https://linux-hardware.org/?probe=b0702745f5) | Sep 14, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [e2454dd5b9](https://linux-hardware.org/?probe=e2454dd5b9) | Sep 14, 2023 |
| ASUSTek       | M2N-E SLI                   | Desktop     | [21e27c3e56](https://linux-hardware.org/?probe=21e27c3e56) | Sep 14, 2023 |
| Toshiba       | PORTEGE Z830                | Notebook    | [a3e1ac295c](https://linux-hardware.org/?probe=a3e1ac295c) | Sep 14, 2023 |
| ASUSTek       | ROG Strix G713IC_G713IC     | Notebook    | [1cf96bfa0e](https://linux-hardware.org/?probe=1cf96bfa0e) | Sep 14, 2023 |
| Toshiba       | PORTEGE Z830                | Notebook    | [6f4c4a4120](https://linux-hardware.org/?probe=6f4c4a4120) | Sep 14, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [9b982600ce](https://linux-hardware.org/?probe=9b982600ce) | Sep 14, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [c0bcb5b2c6](https://linux-hardware.org/?probe=c0bcb5b2c6) | Sep 14, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [262209b6a0](https://linux-hardware.org/?probe=262209b6a0) | Sep 13, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [d334b8fcd2](https://linux-hardware.org/?probe=d334b8fcd2) | Sep 13, 2023 |
| Gigabyte      | B365M H                     | Desktop     | [b57846d1cb](https://linux-hardware.org/?probe=b57846d1cb) | Sep 12, 2023 |
| ZOTAC         | ZBOX-ID88/ID89/ID90         | Mini pc     | [c687b18168](https://linux-hardware.org/?probe=c687b18168) | Sep 12, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [9099ebc0a7](https://linux-hardware.org/?probe=9099ebc0a7) | Sep 12, 2023 |
| Lenovo        | ThinkPad E490 20N8000YUK    | Notebook    | [df9271331c](https://linux-hardware.org/?probe=df9271331c) | Sep 12, 2023 |
| MSI           | Katana GF66 12UC            | Notebook    | [0191ff7bb8](https://linux-hardware.org/?probe=0191ff7bb8) | Sep 12, 2023 |
| Acer          | Aspire A315-21              | Notebook    | [a7fca90eab](https://linux-hardware.org/?probe=a7fca90eab) | Sep 12, 2023 |
| SLIMBOOK      | Essential15L                | Notebook    | [92dbc92137](https://linux-hardware.org/?probe=92dbc92137) | Sep 12, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [84f6190c40](https://linux-hardware.org/?probe=84f6190c40) | Sep 11, 2023 |
| Intel         | DG31PR AAD97573-205         | Desktop     | [486d89ed3a](https://linux-hardware.org/?probe=486d89ed3a) | Sep 11, 2023 |
| MSI           | MPG Z490 GAMING PLUS        | Desktop     | [f5b3cd74bc](https://linux-hardware.org/?probe=f5b3cd74bc) | Sep 11, 2023 |
| MSI           | GE70 2PE                    | Notebook    | [335798b8c9](https://linux-hardware.org/?probe=335798b8c9) | Sep 11, 2023 |
| MSI           | GE62 7RD                    | Notebook    | [ff590de77d](https://linux-hardware.org/?probe=ff590de77d) | Sep 11, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [24e256ad9e](https://linux-hardware.org/?probe=24e256ad9e) | Sep 11, 2023 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [366932ee55](https://linux-hardware.org/?probe=366932ee55) | Sep 11, 2023 |
| HP            | 240 G8 Notebook PC          | Notebook    | [6fec1bd640](https://linux-hardware.org/?probe=6fec1bd640) | Sep 11, 2023 |
| MSI           | B450M BAZOOKA V2            | Desktop     | [a98de00f8f](https://linux-hardware.org/?probe=a98de00f8f) | Sep 11, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [7809da04f1](https://linux-hardware.org/?probe=7809da04f1) | Sep 10, 2023 |
| MSI           | Modern 14 A10M              | Notebook    | [978f30c076](https://linux-hardware.org/?probe=978f30c076) | Sep 10, 2023 |
| Acer          | Aspire E1-572G              | Notebook    | [9f3f71e147](https://linux-hardware.org/?probe=9f3f71e147) | Sep 10, 2023 |
| Acer          | Aspire E1-572G              | Notebook    | [f56c6e875b](https://linux-hardware.org/?probe=f56c6e875b) | Sep 10, 2023 |
| Fujitsu       | LIFEBOOK S752               | Notebook    | [de16eeb9ef](https://linux-hardware.org/?probe=de16eeb9ef) | Sep 09, 2023 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | Notebook    | [3865278574](https://linux-hardware.org/?probe=3865278574) | Sep 09, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | Notebook    | [2e9fbd4683](https://linux-hardware.org/?probe=2e9fbd4683) | Sep 08, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [ff8e50a7ea](https://linux-hardware.org/?probe=ff8e50a7ea) | Sep 08, 2023 |
| BESSTAR Te... | HX90                        | Desktop     | [f8c66085b0](https://linux-hardware.org/?probe=f8c66085b0) | Sep 08, 2023 |
| ASUSTek       | UX430UAR                    | Notebook    | [dbd0ea122b](https://linux-hardware.org/?probe=dbd0ea122b) | Sep 08, 2023 |
| ASUSTek       | UX430UAR                    | Notebook    | [34601ced54](https://linux-hardware.org/?probe=34601ced54) | Sep 08, 2023 |
| HP            | 630                         | Notebook    | [11393e1391](https://linux-hardware.org/?probe=11393e1391) | Sep 08, 2023 |
| Lenovo        | ThinkPad E14 20RA001BUK     | Notebook    | [6bd319be4e](https://linux-hardware.org/?probe=6bd319be4e) | Sep 08, 2023 |
| Lenovo        | V15 G3 ABA 82TV             | Notebook    | [b906e23303](https://linux-hardware.org/?probe=b906e23303) | Sep 08, 2023 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | Notebook    | [7be90edf82](https://linux-hardware.org/?probe=7be90edf82) | Sep 08, 2023 |
| SLIMBOOK      | ONE-AM5                     | Desktop     | [0c8c554ff5](https://linux-hardware.org/?probe=0c8c554ff5) | Sep 08, 2023 |
| Notebook      | W65_67SR                    | Notebook    | [7169bc1dbb](https://linux-hardware.org/?probe=7169bc1dbb) | Sep 07, 2023 |
| Gigabyte      | Z97X-Gaming 5               | Notebook    | [a3cdc2345d](https://linux-hardware.org/?probe=a3cdc2345d) | Sep 07, 2023 |
| HP            | Pavilion dv6                | Notebook    | [9ffcb827b4](https://linux-hardware.org/?probe=9ffcb827b4) | Sep 07, 2023 |
| MSI           | Alpha 15 A3DDK              | Notebook    | [9a87dfb80b](https://linux-hardware.org/?probe=9a87dfb80b) | Sep 07, 2023 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | Notebook    | [0ca7d43ae9](https://linux-hardware.org/?probe=0ca7d43ae9) | Sep 07, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [1a2a0eef04](https://linux-hardware.org/?probe=1a2a0eef04) | Sep 06, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Spain/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 747       | 11.19%  |
| Ubuntu 18.04                 | 512       | 7.67%   |
| Ubuntu 22.04                 | 432       | 6.47%   |
| Debian 11                    | 260       | 3.9%    |
| OpenMandriva 4.2             | 187       | 2.8%    |
| Zorin 16                     | 134       | 2.01%   |
| OpenMandriva 4.3             | 125       | 1.87%   |
| KDE neon 20.04               | 112       | 1.68%   |
| Arch Rolling                 | 109       | 1.63%   |
| Manjaro                      | 94        | 1.41%   |
| Debian 12                    | 90        | 1.35%   |
| OpenMandriva 23.01           | 89        | 1.33%   |
| Fedora 38                    | 85        | 1.27%   |
| Linux Mint 20.3              | 84        | 1.26%   |
| Debian 10                    | 83        | 1.24%   |
| Linux Mint 21.1              | 80        | 1.2%    |
| Ubuntu 20.10                 | 72        | 1.08%   |
| Linux Mint 19.3              | 71        | 1.06%   |
| Arch                         | 65        | 0.97%   |
| Pop!_OS 22.04                | 63        | 0.94%   |
| Xubuntu 20.04                | 62        | 0.93%   |
| Ubuntu 19.04                 | 61        | 0.91%   |
| Linux Mint 20.1              | 59        | 0.88%   |
| Ubuntu 19.10                 | 58        | 0.87%   |
| Fedora 36                    | 58        | 0.87%   |
| Linux Mint 21.2              | 56        | 0.84%   |
| ArcoLinux Rolling            | 56        | 0.84%   |
| OpenMandriva 23.03           | 55        | 0.82%   |
| OpenMandriva 23.08           | 54        | 0.81%   |
| Ubuntu 21.04                 | 53        | 0.79%   |
| Linux Mint 20                | 53        | 0.79%   |
| Fedora 37                    | 53        | 0.79%   |
| Ubuntu 21.10                 | 51        | 0.76%   |
| Xubuntu 18.04                | 48        | 0.72%   |
| Linux Mint 20.2              | 48        | 0.72%   |
| Kubuntu 20.04                | 47        | 0.7%    |
| Fedora 35                    | 47        | 0.7%    |
| Ubuntu 22.10                 | 46        | 0.69%   |
| Linux Mint 21                | 46        | 0.69%   |
| openSUSE Tumbleweed-XXXXXXXX | 45        | 0.67%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 2067      | 32.95%  |
| OpenMandriva  | 529       | 8.43%   |
| Linux Mint    | 525       | 8.37%   |
| Debian        | 489       | 7.8%    |
| Fedora        | 374       | 5.96%   |
| Manjaro       | 215       | 3.43%   |
| Zorin         | 187       | 2.98%   |
| Arch          | 172       | 2.74%   |
| KDE neon      | 159       | 2.53%   |
| Pop!_OS       | 147       | 2.34%   |
| Xubuntu       | 137       | 2.18%   |
| Kubuntu       | 137       | 2.18%   |
| Endless       | 128       | 2.04%   |
| ROSA          | 112       | 1.79%   |
| openSUSE      | 69        | 1.1%    |
| ArcoLinux     | 68        | 1.08%   |
| Ubuntu MATE   | 63        | 1%      |
| Elementary    | 61        | 0.97%   |
| Gentoo        | 56        | 0.89%   |
| Kali          | 54        | 0.86%   |
| SteamOS       | 43        | 0.69%   |
| Ubuntu Unity  | 40        | 0.64%   |
| Lubuntu       | 37        | 0.59%   |
| BlackPanther  | 30        | 0.48%   |
| EndeavourOS   | 29        | 0.46%   |
| Nobara        | 28        | 0.45%   |
| MX            | 27        | 0.43%   |
| LMDE          | 27        | 0.43%   |
| Parrot        | 22        | 0.35%   |
| Clear Linux   | 18        | 0.29%   |
| Ubuntu Budgie | 16        | 0.26%   |
| Garuda Linux  | 14        | 0.22%   |
| CentOS        | 10        | 0.16%   |
| Xero          | 9         | 0.14%   |
| Reborn OS     | 8         | 0.13%   |
| Ubuntu Studio | 7         | 0.11%   |
| RHEL          | 7         | 0.11%   |
| Deepin        | 7         | 0.11%   |
| Sparky        | 6         | 0.1%    |
| Solus         | 5         | 0.08%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002        | 183       | 2.51%   |
| 5.16.7-desktop-1omv4003         | 122       | 1.67%   |
| 5.4.0-42-generic                | 96        | 1.31%   |
| 6.1.1-desktop-1omv2290          | 84        | 1.15%   |
| 5.15.0-56-generic               | 68        | 0.93%   |
| 5.4.0-58-generic                | 60        | 0.82%   |
| 5.10.0-8-amd64                  | 56        | 0.77%   |
| 6.2.6-desktop-1omv2390          | 53        | 0.73%   |
| 5.4.0-52-generic                | 49        | 0.67%   |
| 5.4.0-54-generic                | 48        | 0.66%   |
| 5.4.0-26-generic                | 47        | 0.64%   |
| 6.4.11-desktop-1omv2390         | 44        | 0.6%    |
| 5.15.0-52-generic               | 44        | 0.6%    |
| 5.15.0-58-generic               | 43        | 0.59%   |
| 5.3.0-28-generic                | 42        | 0.58%   |
| 5.4.0-48-generic                | 39        | 0.53%   |
| 5.11.0-27-generic               | 38        | 0.52%   |
| 5.3.0-40-generic                | 37        | 0.51%   |
| 6.5.0-14-generic                | 36        | 0.49%   |
| 5.0.0-37-generic                | 36        | 0.49%   |
| 5.4.0-29-generic                | 34        | 0.47%   |
| 5.4.0-65-generic                | 32        | 0.44%   |
| 5.3.0-46-generic                | 32        | 0.44%   |
| 5.19.0-35-generic               | 32        | 0.44%   |
| 5.15.0-60-generic               | 32        | 0.44%   |
| 5.13.0-30-generic               | 32        | 0.44%   |
| 5.11.0-43-generic               | 32        | 0.44%   |
| 5.10.0-21-amd64                 | 31        | 0.42%   |
| 5.10.0-18-amd64                 | 31        | 0.42%   |
| 6.1.0-13-amd64                  | 30        | 0.41%   |
| 5.0.0-32-generic                | 30        | 0.41%   |
| 5.4.0-72-generic                | 29        | 0.4%    |
| 5.4.0-40-generic                | 29        | 0.4%    |
| 5.15.0-48-generic               | 29        | 0.4%    |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 29        | 0.4%    |
| 5.4.0-47-generic                | 27        | 0.37%   |
| 5.4.0-37-generic                | 27        | 0.37%   |
| 5.3.0-51-generic                | 27        | 0.37%   |
| 5.15.0-91-generic               | 27        | 0.37%   |
| 6.2.0-39-generic                | 26        | 0.36%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 968       | 14.06%  |
| 5.15.0  | 612       | 8.89%   |
| 4.15.0  | 419       | 6.09%   |
| 5.10.0  | 300       | 4.36%   |
| 5.11.0  | 279       | 4.05%   |
| 5.8.0   | 267       | 3.88%   |
| 5.13.0  | 255       | 3.7%    |
| 5.3.0   | 254       | 3.69%   |
| 5.19.0  | 210       | 3.05%   |
| 5.0.0   | 198       | 2.88%   |
| 6.2.0   | 190       | 2.76%   |
| 5.10.14 | 185       | 2.69%   |
| 6.1.0   | 128       | 1.86%   |
| 5.16.7  | 126       | 1.83%   |
| 4.18.0  | 114       | 1.66%   |
| 6.1.1   | 94        | 1.37%   |
| 6.5.0   | 87        | 1.26%   |
| 4.19.0  | 86        | 1.25%   |
| 6.2.6   | 72        | 1.05%   |
| 6.4.11  | 49        | 0.71%   |
| 4.9.60  | 33        | 0.48%   |
| 5.14.0  | 29        | 0.42%   |
| 6.6.2   | 27        | 0.39%   |
| 6.0.0   | 27        | 0.39%   |
| 4.18.16 | 24        | 0.35%   |
| 4.4.0   | 22        | 0.32%   |
| 5.18.0  | 21        | 0.31%   |
| 6.5.5   | 20        | 0.29%   |
| 6.4.8   | 19        | 0.28%   |
| 5.17.5  | 18        | 0.26%   |
| 6.3.5   | 16        | 0.23%   |
| 6.6.1   | 15        | 0.22%   |
| 6.5.6   | 15        | 0.22%   |
| 6.0.12  | 15        | 0.22%   |
| 5.9.16  | 15        | 0.22%   |
| 6.6.8   | 14        | 0.2%    |
| 6.6.6   | 14        | 0.2%    |
| 6.2.9   | 14        | 0.2%    |
| 5.16.0  | 14        | 0.2%    |
| 6.4.6   | 13        | 0.19%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 1032      | 15.2%   |
| 5.15    | 736       | 10.84%  |
| 5.10    | 567       | 8.35%   |
| 4.15    | 419       | 6.17%   |
| 5.11    | 336       | 4.95%   |
| 6.1     | 331       | 4.88%   |
| 6.2     | 329       | 4.85%   |
| 5.8     | 327       | 4.82%   |
| 5.13    | 293       | 4.32%   |
| 5.3     | 282       | 4.15%   |
| 5.19    | 272       | 4.01%   |
| 5.0     | 202       | 2.98%   |
| 5.16    | 193       | 2.84%   |
| 6.5     | 183       | 2.7%    |
| 6.4     | 139       | 2.05%   |
| 4.18    | 139       | 2.05%   |
| 6.6     | 113       | 1.66%   |
| 6.0     | 108       | 1.59%   |
| 4.19    | 102       | 1.5%    |
| 5.14    | 89        | 1.31%   |
| 4.9     | 81        | 1.19%   |
| 6.3     | 75        | 1.1%    |
| 5.18    | 68        | 1%      |
| 5.9     | 52        | 0.77%   |
| 5.17    | 52        | 0.77%   |
| 5.6     | 51        | 0.75%   |
| 5.7     | 45        | 0.66%   |
| 5.12    | 44        | 0.65%   |
| 5.5     | 26        | 0.38%   |
| 4.4     | 26        | 0.38%   |
| 6.7     | 10        | 0.15%   |
| 4.1     | 9         | 0.13%   |
| 5.2     | 8         | 0.12%   |
| 3.10    | 8         | 0.12%   |
| 5.1     | 7         | 0.1%    |
| 4.16    | 6         | 0.09%   |
| 4.14    | 5         | 0.07%   |
| 4.20    | 4         | 0.06%   |
| 4.17    | 4         | 0.06%   |
| 4.13    | 4         | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 5804      | 96.25%  |
| i686    | 185       | 3.07%   |
| aarch64 | 32        | 0.53%   |
| armv7l  | 8         | 0.13%   |
| armv8l  | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 2741      | 43.27%  |
| KDE5             | 1189      | 18.77%  |
| Unknown          | 677       | 10.69%  |
| XFCE             | 472       | 7.45%   |
| X-Cinnamon       | 421       | 6.65%   |
| MATE             | 180       | 2.84%   |
| KDE              | 161       | 2.54%   |
| LXQt             | 76        | 1.2%    |
| Pantheon         | 57        | 0.9%    |
| Cinnamon         | 55        | 0.87%   |
| KDE4             | 48        | 0.76%   |
| i3               | 41        | 0.65%   |
| Unity            | 39        | 0.62%   |
| Budgie           | 32        | 0.51%   |
| LXDE             | 25        | 0.39%   |
| Deepin           | 24        | 0.38%   |
| GNOME Flashback  | 17        | 0.27%   |
| openbox          | 11        | 0.17%   |
| GNOME Classic    | 8         | 0.13%   |
| bspwm            | 8         | 0.13%   |
| Dwm              | 5         | 0.08%   |
| qtile            | 4         | 0.06%   |
| lightdm-xsession | 4         | 0.06%   |
| icewm            | 4         | 0.06%   |
| Hyprland         | 4         | 0.06%   |
| Endless:GNOME    | 4         | 0.06%   |
| xmonad           | 3         | 0.05%   |
| sway             | 3         | 0.05%   |
| LeftWM           | 3         | 0.05%   |
| enlightenment    | 3         | 0.05%   |
| Trinity          | 2         | 0.03%   |
| i3-with-shmlog   | 2         | 0.03%   |
| Cutefish         | 2         | 0.03%   |
| BunsenLabs       | 2         | 0.03%   |
| awesome          | 2         | 0.03%   |
| river            | 1         | 0.02%   |
| Phosh:GNOME      | 1         | 0.02%   |
| Lubuntu          | 1         | 0.02%   |
| KDE6             | 1         | 0.02%   |
| fvwm             | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 4652      | 74.3%   |
| Wayland | 1142      | 18.24%  |
| Unknown | 364       | 5.81%   |
| Tty     | 103       | 1.65%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3050      | 48.57%  |
| SDDM    | 1029      | 16.39%  |
| GDM3    | 754       | 12.01%  |
| GDM     | 651       | 10.37%  |
| LightDM | 560       | 8.92%   |
| TDM     | 150       | 2.39%   |
| KDM     | 48        | 0.76%   |
| XDM     | 13        | 0.21%   |
| LXDM    | 9         | 0.14%   |
| SLiM    | 5         | 0.08%   |
| Ly      | 5         | 0.08%   |
| WDM     | 1         | 0.02%   |
| SLIMSKI | 1         | 0.02%   |
| NODM    | 1         | 0.02%   |
| LY-DM   | 1         | 0.02%   |
| GREETD  | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang           | Computers | Percent |
|----------------|-----------|---------|
| es_ES          | 3678      | 59.1%   |
| en_US          | 1129      | 18.14%  |
| Unknown        | 661       | 10.62%  |
| ca_ES          | 220       | 3.54%   |
| en_GB          | 139       | 2.23%   |
| C              | 71        | 1.14%   |
| de_DE          | 42        | 0.67%   |
| gl_ES          | 40        | 0.64%   |
| eu_ES          | 30        | 0.48%   |
| fr_FR          | 22        | 0.35%   |
| ru_RU          | 20        | 0.32%   |
| it_IT          | 19        | 0.31%   |
| es_AR          | 13        | 0.21%   |
| an_ES          | 13        | 0.21%   |
| es_MX          | 10        | 0.16%   |
| pt_BR          | 9         | 0.14%   |
| ca_AD          | 8         | 0.13%   |
| en_IE          | 7         | 0.11%   |
| ca_ES@valencia | 7         | 0.11%   |
| POSIX          | 6         | 0.1%    |
| ro_RO          | 5         | 0.08%   |
| pl_PL          | 5         | 0.08%   |
| es_ES.UTF8     | 5         | 0.08%   |
| en_AG          | 5         | 0.08%   |
| C.UTF8         | 5         | 0.08%   |
| pt_PT          | 4         | 0.06%   |
| nl_NL          | 3         | 0.05%   |
| fr_BE          | 3         | 0.05%   |
| de_AT          | 3         | 0.05%   |
| bg_BG          | 3         | 0.05%   |
| fr_CH          | 2         | 0.03%   |
| es_US          | 2         | 0.03%   |
| es_BO          | 2         | 0.03%   |
| eo             | 2         | 0.03%   |
| en_HK          | 2         | 0.03%   |
| en_DK          | 2         | 0.03%   |
| en_CA          | 2         | 0.03%   |
| en_AU          | 2         | 0.03%   |
| de_CH          | 2         | 0.03%   |
| zh_CN          | 1         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 3102      | 50.19%  |
| BIOS | 3078      | 49.81%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 4557      | 73.23%  |
| Btrfs    | 547       | 8.79%   |
| Overlay  | 518       | 8.32%   |
| Unknown  | 212       | 3.41%   |
| Tmpfs    | 199       | 3.2%    |
| Xfs      | 94        | 1.51%   |
| Ext3     | 34        | 0.55%   |
| Zfs      | 32        | 0.51%   |
| Ext2     | 16        | 0.26%   |
| Reiserfs | 4         | 0.06%   |
| F2fs     | 4         | 0.06%   |
| Jfs      | 3         | 0.05%   |
| Aufs     | 3         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3199      | 51.61%  |
| GPT     | 2340      | 37.75%  |
| MBR     | 660       | 10.65%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 5162      | 83.57%  |
| Yes       | 1015      | 16.43%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4130      | 67.11%  |
| Yes       | 2024      | 32.89%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 1132      | 18.78%  |
| Hewlett-Packard         | 861       | 14.28%  |
| Lenovo                  | 723       | 11.99%  |
| MSI                     | 541       | 8.97%   |
| Gigabyte Technology     | 481       | 7.98%   |
| Acer                    | 383       | 6.35%   |
| Dell                    | 369       | 6.12%   |
| Apple                   | 164       | 2.72%   |
| ASRock                  | 144       | 2.39%   |
| Toshiba                 | 127       | 2.11%   |
| Intel                   | 98        | 1.63%   |
| Unknown                 | 84        | 1.39%   |
| HUAWEI                  | 57        | 0.95%   |
| Packard Bell            | 52        | 0.86%   |
| Sony                    | 49        | 0.81%   |
| Chuwi                   | 48        | 0.8%    |
| Medion                  | 46        | 0.76%   |
| Samsung Electronics     | 39        | 0.65%   |
| Valve                   | 38        | 0.63%   |
| Notebook                | 35        | 0.58%   |
| SLIMBOOK                | 32        | 0.53%   |
| Raspberry Pi Foundation | 23        | 0.38%   |
| LG Electronics          | 23        | 0.38%   |
| Fujitsu                 | 23        | 0.38%   |
| AMI                     | 22        | 0.36%   |
| Pegatron                | 21        | 0.35%   |
| eMachines               | 19        | 0.32%   |
| BESSTAR Tech            | 19        | 0.32%   |
| Teclast                 | 18        | 0.3%    |
| ECS                     | 17        | 0.28%   |
| AZW                     | 17        | 0.28%   |
| Foxconn                 | 15        | 0.25%   |
| Fujitsu Siemens         | 14        | 0.23%   |
| Timi                    | 13        | 0.22%   |
| Supermicro              | 13        | 0.22%   |
| Microsoft               | 12        | 0.2%    |
| Huanan                  | 12        | 0.2%    |
| Dynabook                | 10        | 0.17%   |
| Clevo                   | 10        | 0.17%   |
| Shuttle                 | 9         | 0.15%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 113       | 1.87%   |
| ASUS All Series                            | 60        | 1%      |
| Valve Jupiter                              | 36        | 0.6%    |
| HP Pavilion g6                             | 24        | 0.4%    |
| Lenovo ThinkCentre E73 10DR0033SP          | 22        | 0.36%   |
| HP Pavilion dv6                            | 22        | 0.36%   |
| HP Notebook                                | 22        | 0.36%   |
| ASUS ZenBook UX431DA_UM431DA               | 19        | 0.32%   |
| Lenovo IdeaPad 330-15IKB 81DE              | 17        | 0.28%   |
| Gigabyte B450M DS3H                        | 16        | 0.27%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_R540MA | 16        | 0.27%   |
| HP G62                                     | 13        | 0.22%   |
| ASUS H110M-D                               | 13        | 0.22%   |
| MSI MS-7B79                                | 12        | 0.2%    |
| MSI MS-7817                                | 12        | 0.2%    |
| Lenovo IdeaPad 3 15ITL6 82H8               | 12        | 0.2%    |
| HUAWEI BOHK-WAX9X                          | 12        | 0.2%    |
| HP Laptop 15-da0xxx                        | 12        | 0.2%    |
| Gigabyte 970A-DS3P                         | 12        | 0.2%    |
| ASUS P5G41T-M LX                           | 12        | 0.2%    |
| MSI MS-7C37                                | 11        | 0.18%   |
| HP Compaq Elite 8300 SFF                   | 11        | 0.18%   |
| Chuwi GemiBook Pro                         | 11        | 0.18%   |
| RPi Raspberry Pi                           | 10        | 0.17%   |
| MSI MS-7C91                                | 10        | 0.17%   |
| MSI MS-7B86                                | 10        | 0.17%   |
| HP Pavilion 15                             | 10        | 0.17%   |
| Gigabyte H81M-S2H                          | 10        | 0.17%   |
| Gigabyte H61M-DS2                          | 10        | 0.17%   |
| Dell XPS 13 7390                           | 10        | 0.17%   |
| ASUS TUF Gaming X570-PLUS                  | 10        | 0.17%   |
| HP Laptop 15s-fq1xxx                       | 9         | 0.15%   |
| HP Laptop 15s-eq1xxx                       | 9         | 0.15%   |
| HP Laptop 15-bs0xx                         | 9         | 0.15%   |
| HP EliteDesk 800 G1 SFF                    | 9         | 0.15%   |
| Gigabyte H110M-S2H                         | 9         | 0.15%   |
| Gigabyte B450 AORUS M                      | 9         | 0.15%   |
| ASUS PRIME B450M-A                         | 9         | 0.15%   |
| ASUS PRIME A320M-K                         | 9         | 0.15%   |
| Acer Aspire 5750G                          | 9         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 267       | 4.43%   |
| Lenovo ThinkPad       | 240       | 3.98%   |
| HP Pavilion           | 170       | 2.82%   |
| Lenovo IdeaPad        | 166       | 2.75%   |
| Unknown               | 113       | 1.87%   |
| HP Compaq             | 111       | 1.84%   |
| ASUS VivoBook         | 108       | 1.79%   |
| Dell Latitude         | 107       | 1.78%   |
| HP Laptop             | 102       | 1.69%   |
| ASUS PRIME            | 102       | 1.69%   |
| ASUS ROG              | 96        | 1.59%   |
| Toshiba Satellite     | 95        | 1.58%   |
| ASUS TUF              | 81        | 1.34%   |
| HP EliteBook          | 75        | 1.24%   |
| Dell XPS              | 73        | 1.21%   |
| Lenovo ThinkCentre    | 67        | 1.11%   |
| ASUS All              | 60        | 1%      |
| Dell OptiPlex         | 59        | 0.98%   |
| Dell Inspiron         | 51        | 0.85%   |
| HP ProBook            | 50        | 0.83%   |
| ASUS ZenBook          | 50        | 0.83%   |
| MSI Prestige          | 41        | 0.68%   |
| Valve Jupiter         | 36        | 0.6%    |
| MSI Modern            | 36        | 0.6%    |
| Packard Bell EasyNote | 35        | 0.58%   |
| Lenovo Yoga           | 33        | 0.55%   |
| HP 250                | 33        | 0.55%   |
| Lenovo Legion         | 32        | 0.53%   |
| Acer TravelMate       | 32        | 0.53%   |
| Dell Precision        | 30        | 0.5%    |
| ASUS ASUS             | 29        | 0.48%   |
| HP EliteDesk          | 28        | 0.46%   |
| HP OMEN               | 27        | 0.45%   |
| Gigabyte B450M        | 27        | 0.45%   |
| Acer Extensa          | 24        | 0.4%    |
| RPi Raspberry         | 23        | 0.38%   |
| Gigabyte X570         | 23        | 0.38%   |
| HP Notebook           | 22        | 0.36%   |
| HP ENVY               | 22        | 0.36%   |
| Lenovo ThinkBook      | 21        | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 583       | 9.67%   |
| 2019    | 537       | 8.91%   |
| 2020    | 510       | 8.46%   |
| 2021    | 463       | 7.68%   |
| 2014    | 415       | 6.88%   |
| 2012    | 370       | 6.14%   |
| 2013    | 363       | 6.02%   |
| 2017    | 349       | 5.79%   |
| 2015    | 325       | 5.39%   |
| 2011    | 324       | 5.37%   |
| 2010    | 293       | 4.86%   |
| 2009    | 276       | 4.58%   |
| 2016    | 259       | 4.3%    |
| 2022    | 253       | 4.2%    |
| 2008    | 252       | 4.18%   |
| 2007    | 188       | 3.12%   |
| 2023    | 99        | 1.64%   |
| 2006    | 91        | 1.51%   |
| Unknown | 40        | 0.66%   |
| 2005    | 23        | 0.38%   |
| 2004    | 7         | 0.12%   |
| 2003    | 3         | 0.05%   |
| 2002    | 2         | 0.03%   |
| 2001    | 2         | 0.03%   |
| 2024    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 3368      | 55.87%  |
| Desktop        | 2229      | 36.98%  |
| All in one     | 111       | 1.84%   |
| Mini pc        | 98        | 1.63%   |
| Convertible    | 94        | 1.56%   |
| Tablet         | 56        | 0.93%   |
| System on chip | 36        | 0.6%    |
| Server         | 31        | 0.51%   |
| Phone          | 3         | 0.05%   |
| Other          | 1         | 0.02%   |
| Stick pc       | 1         | 0.02%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 5646      | 93.09%  |
| Enabled  | 419       | 6.91%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 6019      | 99.85%  |
| Yes  | 9         | 0.15%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 1377      | 22.41%  |
| 16.01-24.0      | 1266      | 20.61%  |
| 3.01-4.0        | 1187      | 19.32%  |
| 8.01-16.0       | 1148      | 18.68%  |
| 32.01-64.0      | 573       | 9.33%   |
| 1.01-2.0        | 243       | 3.96%   |
| 64.01-256.0     | 105       | 1.71%   |
| 2.01-3.0        | 91        | 1.48%   |
| 24.01-32.0      | 78        | 1.27%   |
| 0.51-1.0        | 66        | 1.07%   |
| More than 256.0 | 7         | 0.11%   |
| 0.01-0.5        | 2         | 0.03%   |
| Unknown         | 1         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 2418      | 35.92%  |
| 2.01-3.0   | 1710      | 25.4%   |
| 4.01-8.0   | 941       | 13.98%  |
| 3.01-4.0   | 844       | 12.54%  |
| 0.51-1.0   | 467       | 6.94%   |
| 8.01-16.0  | 236       | 3.51%   |
| 0.01-0.5   | 74        | 1.1%    |
| 16.01-24.0 | 24        | 0.36%   |
| 24.01-32.0 | 12        | 0.18%   |
| 32.01-64.0 | 5         | 0.07%   |
| Unknown    | 1         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3731      | 59.66%  |
| 2       | 1560      | 24.94%  |
| 3       | 494       | 7.9%    |
| 4       | 228       | 3.65%   |
| 5       | 99        | 1.58%   |
| 0       | 49        | 0.78%   |
| 6       | 45        | 0.72%   |
| 7       | 16        | 0.26%   |
| 9       | 11        | 0.18%   |
| 8       | 8         | 0.13%   |
| 10      | 5         | 0.08%   |
| 12      | 2         | 0.03%   |
| 11      | 2         | 0.03%   |
| 35      | 1         | 0.02%   |
| 18      | 1         | 0.02%   |
| 13      | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 3791      | 62.26%  |
| Yes       | 2298      | 37.74%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5151      | 85.07%  |
| No        | 904       | 14.93%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4600      | 75.72%  |
| No        | 1475      | 24.28%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3595      | 58.88%  |
| No        | 2511      | 41.12%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Spain   | 6028      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                       | Computers | Percent |
|----------------------------|-----------|---------|
| Madrid                     | 992       | 15.03%  |
| Barcelona                  | 675       | 10.22%  |
| Valencia                   | 241       | 3.65%   |
| Seville                    | 216       | 3.27%   |
| Zaragoza                   | 111       | 1.68%   |
| Málaga                    | 97        | 1.47%   |
| Granada                    | 92        | 1.39%   |
| Palma                      | 69        | 1.05%   |
| Valladolid                 | 68        | 1.03%   |
| Vigo                       | 64        | 0.97%   |
| Bilbao                     | 63        | 0.95%   |
| Alcobendas                 | 62        | 0.94%   |
| Sabadell                   | 60        | 0.91%   |
| Las Palmas de Gran Canaria | 57        | 0.86%   |
| Córdoba                   | 57        | 0.86%   |
| Alicante                   | 54        | 0.82%   |
| Murcia                     | 47        | 0.71%   |
| Pamplona                   | 45        | 0.68%   |
| Oviedo                     | 44        | 0.67%   |
| A Coruña                  | 44        | 0.67%   |
| Ourense                    | 42        | 0.64%   |
| Donostia / San Sebastian   | 42        | 0.64%   |
| Santiago de Compostela     | 39        | 0.59%   |
| Santa Cruz de Tenerife     | 36        | 0.55%   |
| Alcalá de Henares         | 36        | 0.55%   |
| Almería                   | 33        | 0.5%    |
| Gijón                     | 32        | 0.48%   |
| Burgos                     | 31        | 0.47%   |
| Salamanca                  | 28        | 0.42%   |
| León                      | 28        | 0.42%   |
| Vitoria-Gasteiz            | 27        | 0.41%   |
| Santander                  | 27        | 0.41%   |
| Mostoles                   | 27        | 0.41%   |
| Barakaldo                  | 27        | 0.41%   |
| Girona                     | 26        | 0.39%   |
| Badalona                   | 26        | 0.39%   |
| Getxo                      | 25        | 0.38%   |
| Albacete                   | 23        | 0.35%   |
| Terrassa                   | 22        | 0.33%   |
| Jerez de la Frontera       | 22        | 0.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 1424      | 2211   | 16.02%  |
| WDC                         | 1171      | 1764   | 13.17%  |
| Samsung Electronics         | 1163      | 1705   | 13.08%  |
| Kingston                    | 979       | 1350   | 11.01%  |
| Toshiba                     | 605       | 932    | 6.81%   |
| SanDisk                     | 514       | 714    | 5.78%   |
| Crucial                     | 348       | 487    | 3.91%   |
| Unknown                     | 347       | 461    | 3.9%    |
| Hitachi                     | 256       | 314    | 2.88%   |
| SK hynix                    | 221       | 276    | 2.49%   |
| Intel                       | 198       | 267    | 2.23%   |
| Micron Technology           | 177       | 228    | 1.99%   |
| HGST                        | 140       | 173    | 1.57%   |
| China                       | 94        | 132    | 1.06%   |
| Apple                       | 65        | 88     | 0.73%   |
| Phison Electronics          | 61        | 79     | 0.69%   |
| KIOXIA                      | 61        | 78     | 0.69%   |
| Micron/Crucial Technology   | 59        | 78     | 0.66%   |
| Phison                      | 58        | 65     | 0.65%   |
| Kingston Technology Company | 47        | 64     | 0.53%   |
| Fujitsu                     | 45        | 53     | 0.51%   |
| Maxtor                      | 42        | 61     | 0.47%   |
| Silicon Motion              | 39        | 47     | 0.44%   |
| OCZ                         | 35        | 50     | 0.39%   |
| JMicron Technology          | 34        | 38     | 0.38%   |
| KIOXIA-EXCERIA              | 30        | 44     | 0.34%   |
| Unknown                     | 30        | 33     | 0.34%   |
| Netac                       | 29        | 44     | 0.33%   |
| Transcend                   | 27        | 52     | 0.3%    |
| A-DATA Technology           | 27        | 38     | 0.3%    |
| LITEON                      | 24        | 26     | 0.27%   |
| KingSpec                    | 24        | 32     | 0.27%   |
| Corsair                     | 24        | 29     | 0.27%   |
| Emtec                       | 23        | 30     | 0.26%   |
| PNY                         | 22        | 33     | 0.25%   |
| KingDian                    | 19        | 26     | 0.21%   |
| Intenso                     | 19        | 30     | 0.21%   |
| Patriot                     | 17        | 28     | 0.19%   |
| USB30                       | 16        | 34     | 0.18%   |
| Teclast                     | 15        | 18     | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                   | 315       | 3.22%   |
| Kingston SA400S37480G 480GB SSD                   | 158       | 1.61%   |
| Seagate ST1000DM010-2EP102 1TB                    | 111       | 1.13%   |
| Kingston SA400S37120G 120GB SSD                   | 96        | 0.98%   |
| Seagate ST500DM002-1BD142 500GB                   | 95        | 0.97%   |
| Kingston SV300S37A120G 120GB SSD                  | 79        | 0.81%   |
| Seagate ST3500418AS 500GB                         | 71        | 0.73%   |
| Samsung SSD 860 EVO 500GB                         | 70        | 0.72%   |
| Unknown MMC Card  64GB                            | 67        | 0.68%   |
| Seagate ST1000DM003-1ER162 1TB                    | 62        | 0.63%   |
| Seagate ST2000DM008-2FR102 2TB                    | 60        | 0.61%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 59        | 0.6%    |
| Crucial CT500MX500SSD1 500GB                      | 58        | 0.59%   |
| Unknown MMC Card  32GB                            | 57        | 0.58%   |
| Samsung SSD 850 EVO 250GB                         | 57        | 0.58%   |
| Seagate ST500LT012-1DG142 500GB                   | 54        | 0.55%   |
| Samsung SSD 850 EVO 500GB                         | 52        | 0.53%   |
| Seagate ST1000DM003-1CH162 1TB                    | 51        | 0.52%   |
| Toshiba DT01ACA100 1TB                            | 50        | 0.51%   |
| SanDisk SSD PLUS 480GB                            | 50        | 0.51%   |
| Toshiba MQ01ABD100 1TB                            | 49        | 0.5%    |
| Kingston SUV400S37240G 240GB SSD                  | 48        | 0.49%   |
| Seagate ST9500325AS 500GB                         | 47        | 0.48%   |
| Seagate ST1000LM035-1RK172 1TB                    | 46        | 0.47%   |
| Unknown MMC Card  128GB                           | 44        | 0.45%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 44        | 0.45%   |
| HGST HTS721010A9E630 1TB                          | 43        | 0.44%   |
| Toshiba MQ01ABF050 500GB                          | 39        | 0.4%    |
| Unknown SD/MMC/MS PRO 256GB                       | 38        | 0.39%   |
| Kingston SV300S37A240G 240GB SSD                  | 38        | 0.39%   |
| Crucial CT480BX500SSD1 480GB                      | 37        | 0.38%   |
| Seagate ST31000528AS 1TB                          | 36        | 0.37%   |
| SanDisk NVMe SSD Drive 512GB                      | 36        | 0.37%   |
| Samsung NVMe SSD Drive 512GB                      | 36        | 0.37%   |
| Samsung NVMe SSD Drive 500GB                      | 36        | 0.37%   |
| Toshiba MQ01ABD050 500GB                          | 35        | 0.36%   |
| Crucial CT1000MX500SSD1 1TB                       | 35        | 0.36%   |
| Toshiba TR200 240GB SSD                           | 34        | 0.35%   |
| SK hynix NVMe SSD Drive 512GB                     | 34        | 0.35%   |
| Seagate Expansion 1TB                             | 33        | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1409      | 2186   | 40.35%  |
| WDC                 | 913       | 1362   | 26.15%  |
| Toshiba             | 430       | 622    | 12.31%  |
| Hitachi             | 256       | 314    | 7.33%   |
| Samsung Electronics | 141       | 172    | 4.04%   |
| HGST                | 140       | 173    | 4.01%   |
| Fujitsu             | 44        | 52     | 1.26%   |
| Unknown             | 40        | 47     | 1.15%   |
| Maxtor              | 37        | 52     | 1.06%   |
| Apple               | 26        | 33     | 0.74%   |
| JMicron Technology  | 22        | 24     | 0.63%   |
| ASMT                | 5         | 9      | 0.14%   |
| Hewlett-Packard     | 3         | 4      | 0.09%   |
| USB3.0              | 2         | 2      | 0.06%   |
| TO Exter            | 2         | 3      | 0.06%   |
| SSK                 | 2         | 2      | 0.06%   |
| LaCie               | 2         | 2      | 0.06%   |
| Intenso             | 2         | 3      | 0.06%   |
| Inateck             | 2         | 2      | 0.06%   |
| USB                 | 1         | 1      | 0.03%   |
| SABRENT             | 1         | 2      | 0.03%   |
| Quantum             | 1         | 1      | 0.03%   |
| OEM                 | 1         | 1      | 0.03%   |
| Maxone              | 1         | 1      | 0.03%   |
| IBM-207x            | 1         | 8      | 0.03%   |
| IBM                 | 1         | 1      | 0.03%   |
| HPE                 | 1         | 2      | 0.03%   |
| HGST HTS            | 1         | 1      | 0.03%   |
| Generic-            | 1         | 1      | 0.03%   |
| External            | 1         | 1      | 0.03%   |
| CIRAGO              | 1         | 1      | 0.03%   |
| China               | 1         | 1      | 0.03%   |
| Unknown             | 1         | 3      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 884       | 1214   | 29.25%  |
| Samsung Electronics | 516       | 725    | 17.07%  |
| Crucial             | 313       | 437    | 10.36%  |
| SanDisk             | 276       | 362    | 9.13%   |
| WDC                 | 149       | 218    | 4.93%   |
| Toshiba             | 114       | 216    | 3.77%   |
| China               | 92        | 130    | 3.04%   |
| SK hynix            | 46        | 51     | 1.52%   |
| Micron Technology   | 42        | 56     | 1.39%   |
| Intel               | 40        | 59     | 1.32%   |
| OCZ                 | 35        | 50     | 1.16%   |
| Netac               | 28        | 43     | 0.93%   |
| Transcend           | 26        | 51     | 0.86%   |
| Apple               | 25        | 30     | 0.83%   |
| KingSpec            | 24        | 32     | 0.79%   |
| A-DATA Technology   | 23        | 34     | 0.76%   |
| LITEON              | 22        | 23     | 0.73%   |
| KIOXIA-EXCERIA      | 21        | 29     | 0.69%   |
| Emtec               | 21        | 26     | 0.69%   |
| KingDian            | 18        | 25     | 0.6%    |
| Intenso             | 17        | 25     | 0.56%   |
| USB30               | 16        | 34     | 0.53%   |
| PNY                 | 16        | 27     | 0.53%   |
| Patriot             | 16        | 27     | 0.53%   |
| Teclast             | 15        | 18     | 0.5%    |
| Unknown             | 13        | 13     | 0.43%   |
| FORESEE             | 12        | 18     | 0.4%    |
| Corsair             | 11        | 14     | 0.36%   |
| Drevo               | 10        | 12     | 0.33%   |
| BAITITON            | 8         | 15     | 0.26%   |
| LITEONIT            | 7         | 8      | 0.23%   |
| GOODRAM             | 7         | 9      | 0.23%   |
| Fanxiang            | 7         | 9      | 0.23%   |
| Dogfish             | 7         | 9      | 0.23%   |
| SABRENT             | 6         | 6      | 0.2%    |
| Lexar               | 6         | 6      | 0.2%    |
| USB3.0              | 5         | 5      | 0.17%   |
| SPCC                | 5         | 5      | 0.17%   |
| Maxtor              | 5         | 9      | 0.17%   |
| Unknown             | 4         | 4      | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2955      | 5089   | 37.44%  |
| SSD     | 2583      | 4223   | 32.73%  |
| NVMe    | 1941      | 2793   | 24.59%  |
| MMC     | 315       | 427    | 3.99%   |
| Unknown | 99        | 123    | 1.25%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 4389      | 9030   | 63.14%  |
| NVMe | 1939      | 2784   | 27.9%   |
| MMC  | 315       | 427    | 4.53%   |
| SAS  | 308       | 414    | 4.43%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 3497      | 5830   | 61.17%  |
| 0.51-1.0        | 1545      | 2327   | 27.02%  |
| 1.01-2.0        | 416       | 687    | 7.28%   |
| 3.01-4.0        | 108       | 183    | 1.89%   |
| 2.01-3.0        | 93        | 151    | 1.63%   |
| 4.01-10.0       | 53        | 128    | 0.93%   |
| 10.01-20.0      | 4         | 4      | 0.07%   |
| More than 100.0 | 1         | 2      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1724      | 26.7%   |
| 251-500        | 1531      | 23.71%  |
| 501-1000       | 913       | 14.14%  |
| 1-20           | 487       | 7.54%   |
| 1001-2000      | 472       | 7.31%   |
| 51-100         | 417       | 6.46%   |
| More than 3000 | 281       | 4.35%   |
| 21-50          | 247       | 3.83%   |
| 2001-3000      | 219       | 3.39%   |
| Unknown        | 166       | 2.57%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2535      | 37.83%  |
| 21-50          | 1131      | 16.88%  |
| 101-250        | 870       | 12.98%  |
| 51-100         | 728       | 10.86%  |
| 251-500        | 516       | 7.7%    |
| 501-1000       | 362       | 5.4%    |
| 1001-2000      | 209       | 3.12%   |
| Unknown        | 166       | 2.48%   |
| More than 3000 | 103       | 1.54%   |
| 2001-3000      | 77        | 1.15%   |
| 0              | 4         | 0.06%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 20        | 20     | 3.29%   |
| Seagate ST3500418AS 500GB           | 17        | 23     | 2.8%    |
| Kingston SV300S37A120G 120GB SSD    | 14        | 20     | 2.31%   |
| Seagate ST9500325AS 500GB           | 12        | 14     | 1.98%   |
| SanDisk SSD PLUS 480GB              | 11        | 13     | 1.81%   |
| Seagate ST500LT012-1DG142 500GB     | 10        | 10     | 1.65%   |
| Seagate ST31000528AS 1TB            | 8         | 9      | 1.32%   |
| HGST HTS545050A7E680 500GB          | 7         | 9      | 1.15%   |
| Seagate ST3500320AS 500GB           | 6         | 10     | 0.99%   |
| Seagate ST1000DM010-2EP102 1TB      | 6         | 8      | 0.99%   |
| Seagate ST1000DM003-1CH162 1TB      | 6         | 7      | 0.99%   |
| Seagate ST9250827AS 250GB           | 5         | 5      | 0.82%   |
| Seagate ST500LM021-1KJ152 500GB     | 5         | 5      | 0.82%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 5         | 5      | 0.82%   |
| Kingston SUV400S37240G 240GB SSD    | 5         | 8      | 0.82%   |
| Kingston SA400S37480G 480GB SSD     | 5         | 8      | 0.82%   |
| HGST HTS721010A9E630 1TB            | 5         | 5      | 0.82%   |
| China G521N256GB SSD                | 5         | 6      | 0.82%   |
| WDC WD5000BEVT-22ZAT0 500GB         | 4         | 4      | 0.66%   |
| WDC WD5000AAKX-001CA0 500GB         | 4         | 6      | 0.66%   |
| WDC WD20EFRX-68EUZN0 2TB            | 4         | 7      | 0.66%   |
| WDC WD20EARX-00PASB0 2TB            | 4         | 7      | 0.66%   |
| Seagate ST9500420AS 500GB           | 4         | 4      | 0.66%   |
| Seagate ST31500341AS 1TB            | 4         | 4      | 0.66%   |
| Seagate ST1000LM035-1RK172 1TB      | 4         | 4      | 0.66%   |
| Seagate ST1000DM003-1ER162 1TB      | 4         | 7      | 0.66%   |
| Hitachi HTS545050A7E380 500GB       | 4         | 4      | 0.66%   |
| Drevo X1 SSD 480GB                  | 4         | 6      | 0.66%   |
| WDC WD5000BPVT-60HXZT3 500GB        | 3         | 4      | 0.49%   |
| WDC WD20PURZ-85GU6Y0 2TB            | 3         | 5      | 0.49%   |
| WDC WD20EZRX-00DC0B0 2TB            | 3         | 3      | 0.49%   |
| Toshiba MQ01ABD100 1TB              | 3         | 3      | 0.49%   |
| Toshiba DT01ACA100 1TB              | 3         | 7      | 0.49%   |
| Toshiba DT01ACA050 500GB            | 3         | 4      | 0.49%   |
| Seagate ST3500830AS 500GB           | 3         | 4      | 0.49%   |
| Seagate ST3250310AS 250GB           | 3         | 3      | 0.49%   |
| Seagate ST3200822A 200GB            | 3         | 3      | 0.49%   |
| Seagate ST2000DL003-9VT166 2TB      | 3         | 4      | 0.49%   |
| Samsung Electronics SSD 870 EVO 1TB | 3         | 4      | 0.49%   |
| Samsung Electronics HD501LJ 500GB   | 3         | 3      | 0.49%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 192       | 241    | 32.6%   |
| WDC                 | 107       | 139    | 18.17%  |
| Samsung Electronics | 40        | 44     | 6.79%   |
| Toshiba             | 39        | 46     | 6.62%   |
| Hitachi             | 38        | 41     | 6.45%   |
| Kingston            | 33        | 47     | 5.6%    |
| HGST                | 21        | 24     | 3.57%   |
| SanDisk             | 20        | 22     | 3.4%    |
| Crucial             | 15        | 17     | 2.55%   |
| China               | 11        | 13     | 1.87%   |
| Intel               | 10        | 12     | 1.7%    |
| SK hynix            | 9         | 9      | 1.53%   |
| Maxtor              | 9         | 11     | 1.53%   |
| Fujitsu             | 7         | 8      | 1.19%   |
| Micron Technology   | 6         | 8      | 1.02%   |
| Drevo               | 5         | 7      | 0.85%   |
| OCZ                 | 3         | 3      | 0.51%   |
| Transcend           | 2         | 9      | 0.34%   |
| KingDian            | 2         | 3      | 0.34%   |
| Intenso             | 2         | 2      | 0.34%   |
| Dogfish             | 2         | 3      | 0.34%   |
| Unknown             | 1         | 1      | 0.17%   |
| SPCC                | 1         | 1      | 0.17%   |
| Patriot             | 1         | 1      | 0.17%   |
| Netac               | 1         | 1      | 0.17%   |
| KingSpec            | 1         | 1      | 0.17%   |
| JMicron Technology  | 1         | 1      | 0.17%   |
| IBM                 | 1         | 1      | 0.17%   |
| Hypertec            | 1         | 1      | 0.17%   |
| HPE                 | 1         | 2      | 0.17%   |
| G521N               | 1         | 1      | 0.17%   |
| Corsair             | 1         | 1      | 0.17%   |
| BAITITON            | 1         | 1      | 0.17%   |
| ASMT                | 1         | 2      | 0.17%   |
| Apple               | 1         | 1      | 0.17%   |
| A-DATA Technology   | 1         | 1      | 0.17%   |
| Unknown             | 1         | 1      | 0.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 192       | 241    | 44.04%  |
| WDC                 | 105       | 137    | 24.08%  |
| Hitachi             | 38        | 41     | 8.72%   |
| Toshiba             | 34        | 41     | 7.8%    |
| Samsung Electronics | 23        | 25     | 5.28%   |
| HGST                | 21        | 24     | 4.82%   |
| Maxtor              | 9         | 11     | 2.06%   |
| Fujitsu             | 7         | 8      | 1.61%   |
| Unknown             | 1         | 1      | 0.23%   |
| JMicron Technology  | 1         | 1      | 0.23%   |
| IBM                 | 1         | 1      | 0.23%   |
| HPE                 | 1         | 2      | 0.23%   |
| China               | 1         | 1      | 0.23%   |
| ASMT                | 1         | 2      | 0.23%   |
| Apple               | 1         | 1      | 0.23%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 404       | 537    | 73.32%  |
| SSD  | 131       | 173    | 23.77%  |
| NVMe | 16        | 17     | 2.9%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST3500418AS 500GB         | 2         | 2      | 13.33%  |
| WDC WD5000BEVT-60ZAT1 500GB       | 1         | 1      | 6.67%   |
| Toshiba DT01ACA200 2TB            | 1         | 1      | 6.67%   |
| Toshiba DT01ACA050 500GB          | 1         | 1      | 6.67%   |
| Seagate ST500LT012-1DG142 500GB   | 1         | 1      | 6.67%   |
| Seagate ST3500830AS 500GB         | 1         | 1      | 6.67%   |
| Seagate ST31000528AS 1TB          | 1         | 1      | 6.67%   |
| Seagate ST31000520AS 1TB          | 1         | 1      | 6.67%   |
| Seagate ST31000333AS 1TB          | 1         | 1      | 6.67%   |
| Samsung Electronics SSD 980 500GB | 1         | 1      | 6.67%   |
| Samsung Electronics SSD 980 1TB   | 1         | 1      | 6.67%   |
| Samsung Electronics HD253GJ 250GB | 1         | 1      | 6.67%   |
| Samsung Electronics HD103SJ 1TB   | 1         | 2      | 6.67%   |
| Hitachi HDS721010DLE630 1TB       | 1         | 1      | 6.67%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 7      | 46.67%  |
| Samsung Electronics | 4         | 5      | 26.67%  |
| Toshiba             | 2         | 2      | 13.33%  |
| WDC                 | 1         | 1      | 6.67%   |
| Hitachi             | 1         | 1      | 6.67%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 3721      | 7540   | 56.34%  |
| Works    | 2341      | 4372   | 35.45%  |
| Malfunc  | 527       | 727    | 7.98%   |
| Failed   | 15        | 16     | 0.23%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 4024      | 53.78%  |
| AMD                              | 1030      | 13.76%  |
| Samsung Electronics              | 597       | 7.98%   |
| SanDisk                          | 371       | 4.96%   |
| SK hynix                         | 166       | 2.22%   |
| Kingston Technology Company      | 154       | 2.06%   |
| Phison Electronics               | 141       | 1.88%   |
| Micron Technology                | 139       | 1.86%   |
| Nvidia                           | 117       | 1.56%   |
| ASMedia Technology               | 99        | 1.32%   |
| JMicron Technology               | 95        | 1.27%   |
| Micron/Crucial Technology        | 93        | 1.24%   |
| KIOXIA                           | 75        | 1%      |
| Marvell Technology Group         | 74        | 0.99%   |
| Toshiba America Info Systems     | 69        | 0.92%   |
| Silicon Motion                   | 49        | 0.65%   |
| VIA Technologies                 | 35        | 0.47%   |
| Silicon Integrated Systems [SiS] | 24        | 0.32%   |
| LSI Logic / Symbios Logic        | 14        | 0.19%   |
| MAXIO Technology (Hangzhou)      | 13        | 0.17%   |
| Union Memory (Shenzhen)          | 12        | 0.16%   |
| Apple                            | 11        | 0.15%   |
| Shenzhen Longsys Electronics     | 7         | 0.09%   |
| Realtek Semiconductor            | 7         | 0.09%   |
| Silicon Image                    | 6         | 0.08%   |
| Seagate Technology               | 6         | 0.08%   |
| Hewlett-Packard                  | 6         | 0.08%   |
| Broadcom / LSI                   | 6         | 0.08%   |
| Solid State Storage Technology   | 5         | 0.07%   |
| O2 Micro                         | 5         | 0.07%   |
| ADATA Technology                 | 5         | 0.07%   |
| Lite-On Technology               | 4         | 0.05%   |
| Integrated Technology Express    | 3         | 0.04%   |
| Adaptec                          | 3         | 0.04%   |
| 3ware                            | 3         | 0.04%   |
| Solidigm                         | 2         | 0.03%   |
| Netac Technology                 | 2         | 0.03%   |
| Lenovo                           | 2         | 0.03%   |
| HighPoint Technologies           | 2         | 0.03%   |
| Yangtze Memory Technologies      | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 709       | 8.16%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 309       | 3.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 297       | 3.42%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 284       | 3.27%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 179       | 2.06%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 166       | 1.91%   |
| AMD 400 Series Chipset SATA Controller                                         | 157       | 1.81%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 151       | 1.74%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 149       | 1.72%   |
| Intel Volume Management Device NVMe RAID Controller                            | 143       | 1.65%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 141       | 1.62%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 139       | 1.6%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 134       | 1.54%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 129       | 1.48%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 129       | 1.48%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 121       | 1.39%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 110       | 1.27%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 108       | 1.24%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 108       | 1.24%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 103       | 1.19%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 103       | 1.19%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 97        | 1.12%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 95        | 1.09%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 94        | 1.08%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 89        | 1.02%   |
| Intel SATA Controller [RAID mode]                                              | 88        | 1.01%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 84        | 0.97%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 83        | 0.96%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 82        | 0.94%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 80        | 0.92%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 78        | 0.9%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 78        | 0.9%    |
| Intel SSD 660P Series                                                          | 75        | 0.86%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 73        | 0.84%   |
| AMD 500 Series Chipset SATA Controller                                         | 72        | 0.83%   |
| Intel Comet Lake SATA AHCI Controller                                          | 71        | 0.82%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 67        | 0.77%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 60        | 0.69%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 58        | 0.67%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 58        | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 4257      | 55.98%  |
| NVMe | 1953      | 25.68%  |
| IDE  | 902       | 11.86%  |
| RAID | 471       | 6.19%   |
| SAS  | 13        | 0.17%   |
| SCSI | 9         | 0.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 4614      | 76.54%  |
| AMD          | 1372      | 22.76%  |
| ARM          | 36        | 0.6%    |
| QUALCOMM     | 4         | 0.07%   |
| CentaurHauls | 1         | 0.02%   |
| Unknown      | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 67        | 1.11%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 66        | 1.09%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 65        | 1.08%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 61        | 1.01%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 60        | 0.99%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 52        | 0.86%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 49        | 0.81%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 49        | 0.81%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 49        | 0.81%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 45        | 0.74%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 44        | 0.73%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 43        | 0.71%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 42        | 0.69%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 42        | 0.69%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 41        | 0.68%   |
| AMD Ryzen 5 3600 6-Core Processor             | 41        | 0.68%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 38        | 0.63%   |
| AMD Custom APU 0405                           | 38        | 0.63%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 37        | 0.61%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 34        | 0.56%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 34        | 0.56%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 32        | 0.53%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 31        | 0.51%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 31        | 0.51%   |
| Intel 12th Gen Core i7-12700H                 | 31        | 0.51%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 30        | 0.5%    |
| Intel Celeron N4020 CPU @ 1.10GHz             | 29        | 0.48%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 29        | 0.48%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 29        | 0.48%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 28        | 0.46%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 28        | 0.46%   |
| Intel Core i3-4150 CPU @ 3.50GHz              | 28        | 0.46%   |
| ARM Processor                                 | 27        | 0.45%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 26        | 0.43%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 26        | 0.43%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 26        | 0.43%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 26        | 0.43%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 25        | 0.41%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 25        | 0.41%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 25        | 0.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1139      | 18.86%  |
| Intel Core i7           | 1088      | 18.01%  |
| Other                   | 519       | 8.59%   |
| Intel Core i3           | 473       | 7.83%   |
| Intel Celeron           | 378       | 6.26%   |
| AMD Ryzen 5             | 337       | 5.58%   |
| AMD Ryzen 7             | 328       | 5.43%   |
| Intel Core 2 Duo        | 275       | 4.55%   |
| Intel Atom              | 161       | 2.67%   |
| Intel Xeon              | 129       | 2.14%   |
| Intel Pentium           | 105       | 1.74%   |
| Intel Pentium Dual-Core | 87        | 1.44%   |
| Intel Core 2 Quad       | 77        | 1.27%   |
| AMD Ryzen 9             | 74        | 1.23%   |
| AMD FX                  | 67        | 1.11%   |
| Intel Pentium Dual      | 58        | 0.96%   |
| Intel Core 2            | 58        | 0.96%   |
| AMD Ryzen 3             | 57        | 0.94%   |
| AMD A4                  | 51        | 0.84%   |
| AMD A6                  | 40        | 0.66%   |
| Intel Genuine           | 38        | 0.63%   |
| AMD A8                  | 37        | 0.61%   |
| AMD A10                 | 37        | 0.61%   |
| Intel Core i9           | 35        | 0.58%   |
| AMD Athlon 64 X2        | 28        | 0.46%   |
| AMD E1                  | 27        | 0.45%   |
| Intel Pentium 4         | 25        | 0.41%   |
| AMD Athlon II X2        | 23        | 0.38%   |
| AMD Athlon              | 21        | 0.35%   |
| AMD Ryzen 7 PRO         | 17        | 0.28%   |
| AMD Phenom II X4        | 16        | 0.26%   |
| AMD E                   | 15        | 0.25%   |
| Intel Pentium Silver    | 13        | 0.22%   |
| AMD Phenom              | 12        | 0.2%    |
| AMD Ryzen 5 PRO         | 11        | 0.18%   |
| Intel Pentium D         | 10        | 0.17%   |
| Intel Pentium M         | 9         | 0.15%   |
| Intel Pentium Gold      | 9         | 0.15%   |
| Intel Core m3           | 9         | 0.15%   |
| Intel Celeron M         | 9         | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2374      | 39.26%  |
| 4       | 2104      | 34.79%  |
| 6       | 583       | 9.64%   |
| 8       | 489       | 8.09%   |
| 1       | 196       | 3.24%   |
| 12      | 89        | 1.47%   |
| 10      | 60        | 0.99%   |
| 14      | 58        | 0.96%   |
| 16      | 36        | 0.6%    |
| 3       | 23        | 0.38%   |
| Unknown | 17        | 0.28%   |
| 24      | 5         | 0.08%   |
| 20      | 4         | 0.07%   |
| 64      | 2         | 0.03%   |
| 32      | 2         | 0.03%   |
| 48      | 1         | 0.02%   |
| 40      | 1         | 0.02%   |
| 36      | 1         | 0.02%   |
| 28      | 1         | 0.02%   |
| 5       | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 5975      | 99.1%   |
| 2       | 47        | 0.78%   |
| Unknown | 7         | 0.12%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 3882      | 64.22%  |
| 1       | 2145      | 35.48%  |
| Unknown | 17        | 0.28%   |
| 4       | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 5839      | 96.38%  |
| Unknown        | 117       | 1.93%   |
| 32-bit         | 68        | 1.12%   |
| 64-bit         | 34        | 0.56%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1733      | 27.49%  |
| 0x306c3    | 278       | 4.41%   |
| 0x206a7    | 251       | 3.98%   |
| 0x306a9    | 234       | 3.71%   |
| 0x1067a    | 192       | 3.05%   |
| 0x906ea    | 153       | 2.43%   |
| 0x806ea    | 133       | 2.11%   |
| 0x806c1    | 126       | 2%      |
| 0x506e3    | 119       | 1.89%   |
| 0x6fd      | 111       | 1.76%   |
| 0x40651    | 111       | 1.76%   |
| 0x806ec    | 110       | 1.74%   |
| 0x806e9    | 103       | 1.63%   |
| 0x406e3    | 103       | 1.63%   |
| 0x20655    | 101       | 1.6%    |
| 0x08108109 | 90        | 1.43%   |
| 0x906e9    | 85        | 1.35%   |
| 0x306d4    | 82        | 1.3%    |
| 0x0a50000c | 67        | 1.06%   |
| 0x30678    | 62        | 0.98%   |
| 0x10676    | 61        | 0.97%   |
| 0x08701021 | 60        | 0.95%   |
| 0x6fb      | 55        | 0.87%   |
| 0x20652    | 54        | 0.86%   |
| 0x706a1    | 51        | 0.81%   |
| 0x0800820d | 51        | 0.81%   |
| 0x506c9    | 48        | 0.76%   |
| 0x706e5    | 46        | 0.73%   |
| 0x406c4    | 45        | 0.71%   |
| 0x08600106 | 45        | 0.71%   |
| 0x706a8    | 44        | 0.7%    |
| 0x06006705 | 43        | 0.68%   |
| 0xa0652    | 42        | 0.67%   |
| 0x6f6      | 40        | 0.63%   |
| 0x106ca    | 37        | 0.59%   |
| 0x906a3    | 36        | 0.57%   |
| 0x08108102 | 36        | 0.57%   |
| 0x06000852 | 36        | 0.57%   |
| 0x906ed    | 35        | 0.56%   |
| 0x06001119 | 35        | 0.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 896       | 14.82%  |
| Haswell          | 568       | 9.4%    |
| SandyBridge      | 347       | 5.74%   |
| Penryn           | 338       | 5.59%   |
| IvyBridge        | 316       | 5.23%   |
| Skylake          | 299       | 4.95%   |
| Core             | 286       | 4.73%   |
| Unknown          | 266       | 4.4%    |
| Zen+             | 231       | 3.82%   |
| Zen 2            | 224       | 3.71%   |
| Westmere         | 205       | 3.39%   |
| TigerLake        | 196       | 3.24%   |
| Silvermont       | 191       | 3.16%   |
| Zen 3            | 189       | 3.13%   |
| CometLake        | 143       | 2.37%   |
| Goldmont plus    | 137       | 2.27%   |
| Broadwell        | 136       | 2.25%   |
| Alderlake Hybrid | 111       | 1.84%   |
| Zen              | 104       | 1.72%   |
| Piledriver       | 101       | 1.67%   |
| IceLake          | 100       | 1.65%   |
| K10              | 98        | 1.62%   |
| Bonnell          | 79        | 1.31%   |
| Excavator        | 75        | 1.24%   |
| K8 Hammer        | 60        | 0.99%   |
| Goldmont         | 59        | 0.98%   |
| Nehalem          | 56        | 0.93%   |
| NetBurst         | 38        | 0.63%   |
| Puma             | 36        | 0.6%    |
| P6               | 31        | 0.51%   |
| Steamroller      | 30        | 0.5%    |
| Jaguar           | 30        | 0.5%    |
| Bobcat           | 25        | 0.41%   |
| Tremont          | 17        | 0.28%   |
| K10 Llano        | 12        | 0.2%    |
| Bulldozer        | 8         | 0.13%   |
| K8 & K10 hybrid  | 3         | 0.05%   |
| Gracemont        | 2         | 0.03%   |
| K6               | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 3468      | 48.61%  |
| Nvidia                                       | 2047      | 28.69%  |
| AMD                                          | 1553      | 21.77%  |
| Matrox Electronics Systems                   | 24        | 0.34%   |
| Silicon Integrated Systems [SiS]             | 16        | 0.22%   |
| VIA Technologies                             | 12        | 0.17%   |
| ASPEED Technology                            | 12        | 0.17%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.01%   |
| Silicon Motion                               | 1         | 0.01%   |
| ATI Technologies                             | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 240       | 3.26%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 186       | 2.53%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 166       | 2.26%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 157       | 2.13%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 146       | 1.98%   |
| Intel UHD Graphics 620                                                                   | 140       | 1.9%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 133       | 1.81%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 124       | 1.69%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 124       | 1.69%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 121       | 1.64%   |
| Intel Core Processor Integrated Graphics Controller                                      | 117       | 1.59%   |
| Intel HD Graphics 620                                                                    | 113       | 1.54%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 110       | 1.5%    |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 107       | 1.45%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 106       | 1.44%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 104       | 1.41%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 101       | 1.37%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 98        | 1.33%   |
| Intel HD Graphics 530                                                                    | 94        | 1.28%   |
| Intel HD Graphics 5500                                                                   | 93        | 1.26%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 92        | 1.25%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 90        | 1.22%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 90        | 1.22%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 86        | 1.17%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 81        | 1.1%    |
| Intel HD Graphics 630                                                                    | 80        | 1.09%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 75        | 1.02%   |
| Nvidia GT218 [GeForce 210]                                                               | 71        | 0.97%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 68        | 0.92%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 61        | 0.83%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 56        | 0.76%   |
| Intel HD Graphics 500                                                                    | 55        | 0.75%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 54        | 0.73%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 54        | 0.73%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 54        | 0.73%   |
| AMD Lucienne                                                                             | 53        | 0.72%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 51        | 0.69%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 51        | 0.69%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 47        | 0.64%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 47        | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| 1 x Intel              | 2476      | 40.76%  |
| 1 x AMD                | 1210      | 19.92%  |
| 1 x Nvidia             | 1119      | 18.42%  |
| Intel + Nvidia         | 781       | 12.86%  |
| AMD + Nvidia           | 130       | 2.14%   |
| Intel + AMD            | 129       | 2.12%   |
| 2 x AMD                | 85        | 1.4%    |
| Other                  | 46        | 0.76%   |
| 1 x Matrox             | 21        | 0.35%   |
| 2 x Nvidia             | 17        | 0.28%   |
| 1 x SiS                | 16        | 0.26%   |
| 2 x Intel              | 13        | 0.21%   |
| 1 x VIA                | 12        | 0.2%    |
| 1 x ASPEED             | 7         | 0.12%   |
| Nvidia + ASPEED        | 5         | 0.08%   |
| Nvidia + Matrox        | 3         | 0.05%   |
| 3 x AMD                | 1         | 0.02%   |
| 1 x XGI                | 1         | 0.02%   |
| 1 x Silicon Motion     | 1         | 0.02%   |
| 1 x Intel + 3 x Nvidia | 1         | 0.02%   |
| Intel + 2 x AMD        | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 4841      | 79.04%  |
| Proprietary | 1025      | 16.73%  |
| Unknown     | 259       | 4.23%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 3462      | 55.56%  |
| 1.01-2.0   | 771       | 12.37%  |
| 0.01-0.5   | 720       | 11.56%  |
| 3.01-4.0   | 438       | 7.03%   |
| 0.51-1.0   | 414       | 6.64%   |
| 7.01-8.0   | 230       | 3.69%   |
| 5.01-6.0   | 112       | 1.8%    |
| 8.01-16.0  | 39        | 0.63%   |
| 2.01-3.0   | 33        | 0.53%   |
| 16.01-24.0 | 10        | 0.16%   |
| 32.01-64.0 | 1         | 0.02%   |
| 4.01-5.0   | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 767       | 11.78%  |
| AU Optronics            | 678       | 10.42%  |
| Chimei Innolux          | 623       | 9.57%   |
| LG Display              | 505       | 7.76%   |
| BOE                     | 497       | 7.64%   |
| Goldstar                | 444       | 6.82%   |
| Hewlett-Packard         | 321       | 4.93%   |
| Dell                    | 259       | 3.98%   |
| BenQ                    | 247       | 3.79%   |
| Acer                    | 219       | 3.36%   |
| Ancor Communications    | 177       | 2.72%   |
| Philips                 | 174       | 2.67%   |
| Apple                   | 144       | 2.21%   |
| AOC                     | 143       | 2.2%    |
| Sharp                   | 108       | 1.66%   |
| Chi Mei Optoelectronics | 106       | 1.63%   |
| Lenovo                  | 105       | 1.61%   |
| PANDA                   | 81        | 1.24%   |
| LG Electronics          | 60        | 0.92%   |
| Sony                    | 58        | 0.89%   |
| ASUSTek Computer        | 52        | 0.8%    |
| Unknown                 | 51        | 0.78%   |
| HannStar                | 48        | 0.74%   |
| LG Philips              | 45        | 0.69%   |
| ViewSonic               | 34        | 0.52%   |
| Valve                   | 29        | 0.45%   |
| MSI                     | 28        | 0.43%   |
| InfoVision              | 26        | 0.4%    |
| CSO                     | 17        | 0.26%   |
| CPT                     | 16        | 0.25%   |
| OEM                     | 15        | 0.23%   |
| Toshiba                 | 13        | 0.2%    |
| Eizo                    | 13        | 0.2%    |
| ___                     | 12        | 0.18%   |
| Vestel Elektronik       | 12        | 0.18%   |
| RTK                     | 12        | 0.18%   |
| NEC Computers           | 12        | 0.18%   |
| Mi                      | 12        | 0.18%   |
| Iiyama                  | 12        | 0.18%   |
| Fujitsu Siemens         | 12        | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 70        | 1.04%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 45        | 0.67%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 35        | 0.52%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 33        | 0.49%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 33        | 0.49%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 32        | 0.48%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 27        | 0.4%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 25        | 0.37%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 25        | 0.37%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 24        | 0.36%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 23        | 0.34%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 22        | 0.33%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 22        | 0.33%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 21        | 0.31%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 20        | 0.3%    |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 20        | 0.3%    |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                   | 20        | 0.3%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 19        | 0.28%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 19        | 0.28%   |
| AOC 24G2W1G4 AOC2402 1920x1080 527x296mm 23.8-inch                       | 19        | 0.28%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 18        | 0.27%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 17        | 0.25%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 17        | 0.25%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 340x190mm 15.3-inch            | 17        | 0.25%   |
| Ancor Communications ASUS VX239 ACI23E1 1920x1080 509x286mm 23.0-inch    | 17        | 0.25%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 16        | 0.24%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                  | 16        | 0.24%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch              | 16        | 0.24%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 16        | 0.24%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 16        | 0.24%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                    | 16        | 0.24%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 16        | 0.24%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 15        | 0.22%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 15        | 0.22%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 15        | 0.22%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch        | 14        | 0.21%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                  | 14        | 0.21%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                        | 14        | 0.21%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch           | 14        | 0.21%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 14        | 0.21%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2695      | 43.62%  |
| 1366x768 (WXGA)    | 1194      | 19.33%  |
| 3840x2160 (4K)     | 321       | 5.2%    |
| 2560x1440 (QHD)    | 260       | 4.21%   |
| 1280x1024 (SXGA)   | 244       | 3.95%   |
| 1280x800 (WXGA)    | 184       | 2.98%   |
| 1680x1050 (WSXGA+) | 175       | 2.83%   |
| 1440x900 (WXGA+)   | 164       | 2.65%   |
| 1600x900 (HD+)     | 136       | 2.2%    |
| 1920x1200 (WUXGA)  | 119       | 1.93%   |
| 2560x1080          | 72        | 1.17%   |
| Unknown            | 69        | 1.12%   |
| 1360x768           | 57        | 0.92%   |
| 2560x1600          | 54        | 0.87%   |
| 1024x600           | 47        | 0.76%   |
| 3440x1440          | 44        | 0.71%   |
| 2160x1440          | 36        | 0.58%   |
| 800x1280           | 35        | 0.57%   |
| 2880x1800          | 31        | 0.5%    |
| 1024x768 (XGA)     | 29        | 0.47%   |
| 3840x1080          | 26        | 0.42%   |
| 1920x540           | 16        | 0.26%   |
| 1600x1200          | 15        | 0.24%   |
| 3200x1800 (QHD+)   | 11        | 0.18%   |
| 2288x1287          | 9         | 0.15%   |
| 3840x2400          | 8         | 0.13%   |
| 2736x1824          | 8         | 0.13%   |
| 3200x1080          | 6         | 0.1%    |
| 1920x1280          | 6         | 0.1%    |
| 3840x1600          | 5         | 0.08%   |
| 1280x768           | 5         | 0.08%   |
| 4480x1080          | 4         | 0.06%   |
| 2256x1504          | 4         | 0.06%   |
| 1280x720 (HD)      | 4         | 0.06%   |
| 3840x1200          | 3         | 0.05%   |
| 3600x1080          | 3         | 0.05%   |
| 3456x2160          | 3         | 0.05%   |
| 3360x1080          | 3         | 0.05%   |
| 3200x2000          | 3         | 0.05%   |
| 3072x1920          | 3         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1830      | 28.16%  |
| 13      | 508       | 7.82%   |
| 24      | 476       | 7.33%   |
| 27      | 454       | 6.99%   |
| 21      | 451       | 6.94%   |
| 23      | 376       | 5.79%   |
| 14      | 354       | 5.45%   |
| Unknown | 335       | 5.16%   |
| 17      | 320       | 4.92%   |
| 19      | 190       | 2.92%   |
| 18      | 137       | 2.11%   |
| 31      | 103       | 1.59%   |
| 34      | 102       | 1.57%   |
| 22      | 102       | 1.57%   |
| 12      | 91        | 1.4%    |
| 20      | 90        | 1.39%   |
| 16      | 73        | 1.12%   |
| 11      | 65        | 1%      |
| 10      | 58        | 0.89%   |
| 84      | 55        | 0.85%   |
| 54      | 35        | 0.54%   |
| 32      | 30        | 0.46%   |
| 7       | 29        | 0.45%   |
| 25      | 28        | 0.43%   |
| 72      | 27        | 0.42%   |
| 26      | 26        | 0.4%    |
| 40      | 24        | 0.37%   |
| 46      | 12        | 0.18%   |
| 28      | 12        | 0.18%   |
| 48      | 10        | 0.15%   |
| 65      | 9         | 0.14%   |
| 52      | 9         | 0.14%   |
| 142     | 8         | 0.12%   |
| 3       | 8         | 0.12%   |
| 42      | 6         | 0.09%   |
| 33      | 6         | 0.09%   |
| 37      | 5         | 0.08%   |
| 36      | 5         | 0.08%   |
| 29      | 5         | 0.08%   |
| 8       | 5         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 2528      | 39.64%  |
| 501-600        | 1211      | 18.99%  |
| 401-500        | 867       | 13.6%   |
| 201-300        | 512       | 8.03%   |
| 351-400        | 350       | 5.49%   |
| Unknown        | 335       | 5.25%   |
| 601-700        | 167       | 2.62%   |
| 701-800        | 139       | 2.18%   |
| 1501-2000      | 86        | 1.35%   |
| 1001-1500      | 85        | 1.33%   |
| 801-900        | 38        | 0.6%    |
| 1-100          | 37        | 0.58%   |
| 901-1000       | 9         | 0.14%   |
| More than 2000 | 8         | 0.13%   |
| 101-200        | 5         | 0.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 4292      | 73.37%  |
| 16/10   | 734       | 12.55%  |
| Unknown | 280       | 4.79%   |
| 5/4     | 223       | 3.81%   |
| 21/9    | 109       | 1.86%   |
| 3/2     | 76        | 1.3%    |
| 4/3     | 64        | 1.09%   |
| 0.67    | 27        | 0.46%   |
| 6/5     | 15        | 0.26%   |
| 32/9    | 9         | 0.15%   |
| 1.00    | 8         | 0.14%   |
| 0.62    | 3         | 0.05%   |
| 0.45    | 3         | 0.05%   |
| 0.56    | 2         | 0.03%   |
| 2.00    | 1         | 0.02%   |
| 1.03    | 1         | 0.02%   |
| 0.89    | 1         | 0.02%   |
| 0.65    | 1         | 0.02%   |
| 0.58    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1839      | 28.56%  |
| 201-250        | 1156      | 17.96%  |
| 81-90          | 631       | 9.8%    |
| 301-350        | 468       | 7.27%   |
| 151-200        | 404       | 6.28%   |
| Unknown        | 335       | 5.2%    |
| 351-500        | 245       | 3.81%   |
| 141-150        | 245       | 3.81%   |
| 71-80          | 235       | 3.65%   |
| More than 1000 | 162       | 2.52%   |
| 121-130        | 152       | 2.36%   |
| 251-300        | 141       | 2.19%   |
| 61-70          | 77        | 1.2%    |
| 501-1000       | 70        | 1.09%   |
| 51-60          | 65        | 1.01%   |
| 41-50          | 58        | 0.9%    |
| 111-120        | 53        | 0.82%   |
| 1-40           | 42        | 0.65%   |
| 131-140        | 39        | 0.61%   |
| 91-100         | 21        | 0.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 2145      | 34.27%  |
| 101-120       | 1649      | 26.34%  |
| 121-160       | 1514      | 24.19%  |
| 161-240       | 380       | 6.07%   |
| Unknown       | 335       | 5.35%   |
| 1-50          | 130       | 2.08%   |
| More than 240 | 107       | 1.71%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 4855      | 78.46%  |
| 2     | 927       | 14.98%  |
| 0     | 286       | 4.62%   |
| 3     | 111       | 1.79%   |
| 4     | 8         | 0.13%   |
| 5     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 3456      | 37.93%  |
| Intel                             | 2591      | 28.44%  |
| Qualcomm Atheros                  | 1050      | 11.52%  |
| Broadcom                          | 552       | 6.06%   |
| TP-Link                           | 150       | 1.65%   |
| MediaTek                          | 147       | 1.61%   |
| Ralink Technology                 | 132       | 1.45%   |
| Marvell Technology Group          | 132       | 1.45%   |
| Broadcom Limited                  | 113       | 1.24%   |
| Nvidia                            | 100       | 1.1%    |
| Ralink                            | 92        | 1.01%   |
| ASIX Electronics                  | 51        | 0.56%   |
| Qualcomm Atheros Communications   | 45        | 0.49%   |
| Xiaomi                            | 42        | 0.46%   |
| Samsung Electronics               | 34        | 0.37%   |
| D-Link                            | 28        | 0.31%   |
| DisplayLink                       | 27        | 0.3%    |
| Silicon Integrated Systems [SiS]  | 21        | 0.23%   |
| Qualcomm                          | 21        | 0.23%   |
| VIA Technologies                  | 19        | 0.21%   |
| Ericsson Business Mobile Networks | 19        | 0.21%   |
| D-Link System                     | 19        | 0.21%   |
| Lenovo                            | 18        | 0.2%    |
| ASUSTek Computer                  | 18        | 0.2%    |
| JMicron Technology                | 17        | 0.19%   |
| Dell                              | 16        | 0.18%   |
| Sierra Wireless                   | 14        | 0.15%   |
| Hewlett-Packard                   | 14        | 0.15%   |
| Belkin Components                 | 14        | 0.15%   |
| Microsoft                         | 13        | 0.14%   |
| Huawei Technologies               | 12        | 0.13%   |
| Edimax Technology                 | 10        | 0.11%   |
| ZyDAS                             | 7         | 0.08%   |
| Microchip Technology              | 7         | 0.08%   |
| NetGear                           | 6         | 0.07%   |
| Aquantia                          | 6         | 0.07%   |
| Google                            | 5         | 0.05%   |
| Arduino SA                        | 5         | 0.05%   |
| Apple                             | 5         | 0.05%   |
| LSI                               | 4         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 2328      | 22.11%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 351       | 3.33%   |
| Intel Wi-Fi 6 AX200                                                    | 243       | 2.31%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 190       | 1.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 168       | 1.6%    |
| Intel Wi-Fi 6 AX201                                                    | 145       | 1.38%   |
| Intel Wireless 8265 / 8275                                             | 144       | 1.37%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 142       | 1.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 128       | 1.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 128       | 1.22%   |
| Realtek RTL8125 2.5GbE Controller                                      | 123       | 1.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 122       | 1.16%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 120       | 1.14%   |
| Intel Wireless 7265                                                    | 120       | 1.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 115       | 1.09%   |
| Intel Wireless 3165                                                    | 110       | 1.04%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 102       | 0.97%   |
| Intel I211 Gigabit Network Connection                                  | 97        | 0.92%   |
| Intel Ethernet Connection (2) I219-V                                   | 95        | 0.9%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 92        | 0.87%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 87        | 0.83%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 86        | 0.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 79        | 0.75%   |
| Intel Wireless 7260                                                    | 77        | 0.73%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 74        | 0.7%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 62        | 0.59%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 60        | 0.57%   |
| Broadcom BCM43142 802.11b/g/n                                          | 60        | 0.57%   |
| Intel Ethernet Controller I225-V                                       | 59        | 0.56%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 56        | 0.53%   |
| Intel Ethernet Connection I217-LM                                      | 55        | 0.52%   |
| Intel Wireless 8260                                                    | 54        | 0.51%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 54        | 0.51%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 54        | 0.51%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 53        | 0.5%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)         | 52        | 0.49%   |
| Intel WiFi Link 5100                                                   | 52        | 0.49%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 51        | 0.48%   |
| Intel Wireless 3160                                                    | 51        | 0.48%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 49        | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1975      | 40.4%   |
| Realtek Semiconductor                 | 945       | 19.33%  |
| Qualcomm Atheros                      | 811       | 16.59%  |
| Broadcom                              | 355       | 7.26%   |
| MediaTek                              | 142       | 2.9%    |
| Ralink Technology                     | 132       | 2.7%    |
| TP-Link                               | 128       | 2.62%   |
| Ralink                                | 92        | 1.88%   |
| Broadcom Limited                      | 79        | 1.62%   |
| Qualcomm Atheros Communications       | 45        | 0.92%   |
| D-Link                                | 27        | 0.55%   |
| ASUSTek Computer                      | 18        | 0.37%   |
| Sierra Wireless                       | 14        | 0.29%   |
| Belkin Components                     | 14        | 0.29%   |
| Microsoft                             | 12        | 0.25%   |
| D-Link System                         | 12        | 0.25%   |
| Edimax Technology                     | 10        | 0.2%    |
| Qualcomm                              | 9         | 0.18%   |
| Dell                                  | 9         | 0.18%   |
| Marvell Technology Group              | 8         | 0.16%   |
| ZyDAS                                 | 7         | 0.14%   |
| NetGear                               | 6         | 0.12%   |
| Ericsson Business Mobile Networks     | 6         | 0.12%   |
| Hewlett-Packard                       | 4         | 0.08%   |
| Gemtek                                | 4         | 0.08%   |
| Texas Instruments                     | 3         | 0.06%   |
| Fibocom                               | 3         | 0.06%   |
| Tenda                                 | 2         | 0.04%   |
| Sitecom Europe                        | 2         | 0.04%   |
| Linksys                               | 2         | 0.04%   |
| Accton Technology                     | 2         | 0.04%   |
| ZyXEL Communications                  | 1         | 0.02%   |
| Xiaomi                                | 1         | 0.02%   |
| Wilocity                              | 1         | 0.02%   |
| Wacom                                 | 1         | 0.02%   |
| TRENDnet                              | 1         | 0.02%   |
| Standard Microsystems                 | 1         | 0.02%   |
| Samsung Electronics                   | 1         | 0.02%   |
| AirTies Wireless Networks             | 1         | 0.02%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 243       | 4.93%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 168       | 3.41%   |
| Intel Wi-Fi 6 AX201                                                     | 145       | 2.94%   |
| Intel Wireless 8265 / 8275                                              | 144       | 2.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 142       | 2.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 128       | 2.6%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 122       | 2.48%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 120       | 2.44%   |
| Intel Wireless 7265                                                     | 120       | 2.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 115       | 2.33%   |
| Intel Wireless 3165                                                     | 110       | 2.23%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 102       | 2.07%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 92        | 1.87%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 87        | 1.77%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 86        | 1.75%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 79        | 1.6%    |
| Intel Wireless 7260                                                     | 77        | 1.56%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 74        | 1.5%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 62        | 1.26%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 60        | 1.22%   |
| Broadcom BCM43142 802.11b/g/n                                           | 60        | 1.22%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 56        | 1.14%   |
| Intel Wireless 8260                                                     | 54        | 1.1%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 54        | 1.1%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 54        | 1.1%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 53        | 1.08%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 52        | 1.06%   |
| Intel WiFi Link 5100                                                    | 52        | 1.06%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 51        | 1.03%   |
| Intel Wireless 3160                                                     | 51        | 1.03%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 49        | 0.99%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 48        | 0.97%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 48        | 0.97%   |
| Realtek 802.11ac NIC                                                    | 46        | 0.93%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 46        | 0.93%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 44        | 0.89%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 42        | 0.85%   |
| Qualcomm Atheros AR9271 802.11n                                         | 41        | 0.83%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 39        | 0.79%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 37        | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 3048      | 56.33%  |
| Intel                                  | 1150      | 21.25%  |
| Qualcomm Atheros                       | 336       | 6.21%   |
| Broadcom                               | 271       | 5.01%   |
| Marvell Technology Group               | 125       | 2.31%   |
| Nvidia                                 | 100       | 1.85%   |
| ASIX Electronics                       | 51        | 0.94%   |
| Xiaomi                                 | 41        | 0.76%   |
| Broadcom Limited                       | 36        | 0.67%   |
| Samsung Electronics                    | 33        | 0.61%   |
| DisplayLink                            | 27        | 0.5%    |
| TP-Link                                | 23        | 0.43%   |
| Silicon Integrated Systems [SiS]       | 21        | 0.39%   |
| VIA Technologies                       | 19        | 0.35%   |
| Lenovo                                 | 18        | 0.33%   |
| JMicron Technology                     | 17        | 0.31%   |
| Qualcomm                               | 12        | 0.22%   |
| D-Link System                          | 7         | 0.13%   |
| Huawei Technologies                    | 6         | 0.11%   |
| Hewlett-Packard                        | 6         | 0.11%   |
| Aquantia                               | 6         | 0.11%   |
| Microchip Technology                   | 5         | 0.09%   |
| Google                                 | 5         | 0.09%   |
| Apple                                  | 5         | 0.09%   |
| MediaTek                               | 4         | 0.07%   |
| LSI                                    | 4         | 0.07%   |
| Attansic Technology                    | 4         | 0.07%   |
| Sony Ericsson Mobile Communications AB | 3         | 0.06%   |
| OPPO Electronics                       | 3         | 0.06%   |
| IBM                                    | 3         | 0.06%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.04%   |
| Davicom Semiconductor                  | 2         | 0.04%   |
| ADMtek                                 | 2         | 0.04%   |
| Accton Technology                      | 2         | 0.04%   |
| Tehuti Networks                        | 1         | 0.02%   |
| T & A Mobile Phones                    | 1         | 0.02%   |
| Spreadtrum Communications              | 1         | 0.02%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.02%   |
| National Semiconductor                 | 1         | 0.02%   |
| Motorola PCS                           | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 2328      | 42.12%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 351       | 6.35%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 190       | 3.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 128       | 2.32%   |
| Realtek RTL8125 2.5GbE Controller                                      | 123       | 2.23%   |
| Intel I211 Gigabit Network Connection                                  | 97        | 1.76%   |
| Intel Ethernet Connection (2) I219-V                                   | 95        | 1.72%   |
| Intel Ethernet Controller I225-V                                       | 59        | 1.07%   |
| Intel Ethernet Connection I217-LM                                      | 55        | 1%      |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 48        | 0.87%   |
| Intel 82579V Gigabit Network Connection                                | 44        | 0.8%    |
| ASIX AX88179 Gigabit Ethernet                                          | 44        | 0.8%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 43        | 0.78%   |
| Intel Ethernet Connection (7) I219-V                                   | 42        | 0.76%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 39        | 0.71%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 38        | 0.69%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 36        | 0.65%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 32        | 0.58%   |
| Nvidia MCP79 Ethernet                                                  | 32        | 0.58%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 31        | 0.56%   |
| Intel 82577LM Gigabit Network Connection                               | 31        | 0.56%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 31        | 0.56%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 30        | 0.54%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 29        | 0.52%   |
| Nvidia MCP61 Ethernet                                                  | 29        | 0.52%   |
| Intel Ethernet Connection (4) I219-LM                                  | 29        | 0.52%   |
| Intel Ethernet Connection (2) I219-LM                                  | 29        | 0.52%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 28        | 0.51%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 28        | 0.51%   |
| Intel Ethernet Connection (6) I219-V                                   | 28        | 0.51%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 27        | 0.49%   |
| Intel Ethernet Connection (2) I218-V                                   | 27        | 0.49%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 26        | 0.47%   |
| Intel I210 Gigabit Network Connection                                  | 26        | 0.47%   |
| Intel Ethernet Connection I218-LM                                      | 26        | 0.47%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 24        | 0.43%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 23        | 0.42%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 23        | 0.42%   |
| Intel Ethernet Connection I217-V                                       | 23        | 0.42%   |
| Intel Ethernet Connection (4) I219-V                                   | 23        | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 5147      | 52.42%  |
| WiFi     | 4596      | 46.81%  |
| Modem    | 65        | 0.66%   |
| Unknown  | 10        | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 3490      | 55.45%  |
| Ethernet | 2804      | 44.55%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 3215      | 53.08%  |
| 1     | 2585      | 42.68%  |
| 0     | 144       | 2.38%   |
| 3     | 86        | 1.42%   |
| 4     | 18        | 0.3%    |
| 5     | 5         | 0.08%   |
| 6     | 4         | 0.07%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 5777      | 95.09%  |
| Yes  | 298       | 4.91%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1605      | 43.94%  |
| Realtek Semiconductor           | 440       | 12.04%  |
| Cambridge Silicon Radio         | 298       | 8.16%   |
| IMC Networks                    | 246       | 6.73%   |
| Qualcomm Atheros Communications | 184       | 5.04%   |
| Apple                           | 155       | 4.24%   |
| Broadcom                        | 139       | 3.81%   |
| Foxconn / Hon Hai               | 125       | 3.42%   |
| Lite-On Technology              | 117       | 3.2%    |
| ASUSTek Computer                | 58        | 1.59%   |
| Realtek                         | 46        | 1.26%   |
| Toshiba                         | 43        | 1.18%   |
| Dell                            | 30        | 0.82%   |
| MediaTek                        | 27        | 0.74%   |
| Hewlett-Packard                 | 27        | 0.74%   |
| Ralink                          | 25        | 0.68%   |
| Alps Electric                   | 16        | 0.44%   |
| Foxconn International           | 12        | 0.33%   |
| Belkin Components               | 11        | 0.3%    |
| TP-Link                         | 10        | 0.27%   |
| Integrated System Solution      | 8         | 0.22%   |
| Marvell Semiconductor           | 5         | 0.14%   |
| Actions                         | 5         | 0.14%   |
| Ralink Technology               | 4         | 0.11%   |
| Edimax Technology               | 3         | 0.08%   |
| Askey Computer                  | 3         | 0.08%   |
| USI                             | 2         | 0.05%   |
| Taiyo Yuden                     | 2         | 0.05%   |
| Roper                           | 2         | 0.05%   |
| Sitecom Europe                  | 1         | 0.03%   |
| Opticis                         | 1         | 0.03%   |
| Logitech                        | 1         | 0.03%   |
| Corsair                         | 1         | 0.03%   |
| Chicony Electronics             | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 556       | 15.21%  |
| Realtek Bluetooth Radio                             | 334       | 9.14%   |
| Intel AX201 Bluetooth                               | 299       | 8.18%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 298       | 8.15%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 252       | 6.89%   |
| Intel AX200 Bluetooth                               | 234       | 6.4%    |
| IMC Networks Bluetooth Radio                        | 114       | 3.12%   |
| Intel Bluetooth Device                              | 87        | 2.38%   |
| Realtek  Bluetooth 4.2 Adapter                      | 80        | 2.19%   |
| Qualcomm Atheros  Bluetooth Device                  | 76        | 2.08%   |
| Apple Bluetooth Host Controller                     | 66        | 1.81%   |
| IMC Networks Bluetooth Device                       | 58        | 1.59%   |
| IMC Networks Wireless_Device                        | 55        | 1.5%    |
| Intel AX210 Bluetooth                               | 54        | 1.48%   |
| Intel Wireless-AC 3168 Bluetooth                    | 53        | 1.45%   |
| Realtek Bluetooth Radio                             | 46        | 1.26%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 43        | 1.18%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 42        | 1.15%   |
| Foxconn / Hon Hai Wireless_Device                   | 42        | 1.15%   |
| Foxconn / Hon Hai Bluetooth Device                  | 42        | 1.15%   |
| Apple Bluetooth USB Host Controller                 | 40        | 1.09%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 32        | 0.88%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 30        | 0.82%   |
| Lite-On Bluetooth Device                            | 29        | 0.79%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 29        | 0.79%   |
| Lite-On Atheros AR3012 Bluetooth                    | 28        | 0.77%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 28        | 0.77%   |
| MediaTek Wireless_Device                            | 27        | 0.74%   |
| Ralink RT3290 Bluetooth                             | 25        | 0.68%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 23        | 0.63%   |
| Apple Bluetooth HCI                                 | 19        | 0.52%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 18        | 0.49%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 16        | 0.44%   |
| HP Broadcom 2070 Bluetooth Combo                    | 15        | 0.41%   |
| Broadcom BCM2045B (BDC-2.1)                         | 15        | 0.41%   |
| Realtek RTL8723B Bluetooth                          | 14        | 0.38%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 13        | 0.36%   |
| Broadcom BCM2045 Bluetooth                          | 13        | 0.36%   |
| Foxconn International BCM43142A0 Bluetooth module   | 12        | 0.33%   |
| Broadcom HP Portable Bumble Bee                     | 12        | 0.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 4375      | 53.32%  |
| AMD                                  | 1633      | 19.9%   |
| Nvidia                               | 1434      | 17.48%  |
| C-Media Electronics                  | 124       | 1.51%   |
| Logitech                             | 54        | 0.66%   |
| Creative Labs                        | 42        | 0.51%   |
| Texas Instruments                    | 34        | 0.41%   |
| JMTek                                | 32        | 0.39%   |
| ASUSTek Computer                     | 27        | 0.33%   |
| Silicon Integrated Systems [SiS]     | 24        | 0.29%   |
| Plantronics                          | 23        | 0.28%   |
| Lenovo                               | 23        | 0.28%   |
| VIA Technologies                     | 21        | 0.26%   |
| Kingston Technology                  | 20        | 0.24%   |
| GN Netcom                            | 20        | 0.24%   |
| Corsair                              | 20        | 0.24%   |
| Focusrite-Novation                   | 16        | 0.2%    |
| Creative Technology                  | 16        | 0.2%    |
| SteelSeries ApS                      | 15        | 0.18%   |
| Realtek Semiconductor                | 14        | 0.17%   |
| Generalplus Technology               | 13        | 0.16%   |
| Micro Star International             | 11        | 0.13%   |
| Dell                                 | 11        | 0.13%   |
| Sennheiser Communications            | 10        | 0.12%   |
| BEHRINGER International              | 10        | 0.12%   |
| Apple                                | 10        | 0.12%   |
| Hewlett-Packard                      | 8         | 0.1%    |
| Razer USA                            | 7         | 0.09%   |
| M-Audio                              | 7         | 0.09%   |
| Tenx Technology                      | 6         | 0.07%   |
| Ensoniq                              | 6         | 0.07%   |
| Thesycon Systemsoftware & Consulting | 5         | 0.06%   |
| Sony                                 | 5         | 0.06%   |
| Yamaha                               | 4         | 0.05%   |
| Blue Microphones                     | 4         | 0.05%   |
| XMOS                                 | 3         | 0.04%   |
| Trust                                | 3         | 0.04%   |
| SAVITECH                             | 3         | 0.04%   |
| RODE Microphones                     | 3         | 0.04%   |
| QinHeng Electronics                  | 3         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 538       | 5.53%   |
| Intel Sunrise Point-LP HD Audio                                            | 396       | 4.07%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 339       | 3.49%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 320       | 3.29%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 309       | 3.18%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 249       | 2.56%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 243       | 2.5%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 238       | 2.45%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 223       | 2.29%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 219       | 2.25%   |
| Intel Cannon Lake PCH cAVS                                                 | 217       | 2.23%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 196       | 2.02%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 185       | 1.9%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 183       | 1.88%   |
| AMD Starship/Matisse HD Audio Controller                                   | 168       | 1.73%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 168       | 1.73%   |
| AMD FCH Azalia Controller                                                  | 161       | 1.66%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 159       | 1.63%   |
| Intel 8 Series HD Audio Controller                                         | 158       | 1.62%   |
| Intel Haswell-ULT HD Audio Controller                                      | 157       | 1.61%   |
| Nvidia GP107GL High Definition Audio Controller                            | 140       | 1.44%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 137       | 1.41%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 127       | 1.31%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 126       | 1.3%    |
| Intel Comet Lake PCH-LP cAVS                                               | 125       | 1.29%   |
| Intel 200 Series PCH HD Audio                                              | 124       | 1.28%   |
| Intel Broadwell-U Audio Controller                                         | 122       | 1.25%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 116       | 1.19%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 113       | 1.16%   |
| Nvidia High Definition Audio Controller                                    | 100       | 1.03%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 99        | 1.02%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 98        | 1.01%   |
| Intel Comet Lake PCH cAVS                                                  | 89        | 0.92%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 84        | 0.86%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 80        | 0.82%   |
| AMD Kabini HDMI/DP Audio                                                   | 75        | 0.77%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 73        | 0.75%   |
| Nvidia GP106 High Definition Audio Controller                              | 72        | 0.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 69        | 0.71%   |
| Nvidia TU106 High Definition Audio Controller                              | 68        | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 813       | 22.75%  |
| SK hynix                     | 574       | 16.06%  |
| Kingston                     | 545       | 15.25%  |
| Micron Technology            | 350       | 9.8%    |
| Unknown                      | 344       | 9.63%   |
| Crucial                      | 249       | 6.97%   |
| Corsair                      | 162       | 4.53%   |
| G.Skill                      | 104       | 2.91%   |
| Ramaxel Technology           | 79        | 2.21%   |
| Unknown (ABCD)               | 59        | 1.65%   |
| Elpida                       | 48        | 1.34%   |
| A-DATA Technology            | 37        | 1.04%   |
| Nanya Technology             | 32        | 0.9%    |
| Unknown                      | 24        | 0.67%   |
| Silicon Power                | 16        | 0.45%   |
| Team                         | 14        | 0.39%   |
| GOODRAM                      | 14        | 0.39%   |
| Transcend                    | 10        | 0.28%   |
| Apacer                       | 9         | 0.25%   |
| Unifosa                      | 6         | 0.17%   |
| Timetec                      | 5         | 0.14%   |
| Kllisre                      | 5         | 0.14%   |
| Wilk                         | 4         | 0.11%   |
| Patriot                      | 4         | 0.11%   |
| Avant                        | 4         | 0.11%   |
| ASint Technology             | 4         | 0.11%   |
| Micron/Elpida                | 3         | 0.08%   |
| ChangXin Memory              | 3         | 0.08%   |
| Atermiter                    | 3         | 0.08%   |
| Wodposit                     | 2         | 0.06%   |
| Unknown (AB)                 | 2         | 0.06%   |
| Toshiba                      | 2         | 0.06%   |
| SHARETRONIC                  | 2         | 0.06%   |
| Qimonda                      | 2         | 0.06%   |
| PNY                          | 2         | 0.06%   |
| Patriot Memory (PDP Systems) | 2         | 0.06%   |
| Netac                        | 2         | 0.06%   |
| Neo Forza                    | 2         | 0.06%   |
| KomputerBay                  | 2         | 0.06%   |
| Innodisk                     | 2         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 39        | 1.02%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 37        | 0.97%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s              | 36        | 0.94%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 27        | 0.71%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 26        | 0.68%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 26        | 0.68%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 25        | 0.65%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 24        | 0.63%   |
| Unknown                                                             | 24        | 0.63%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 23        | 0.6%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 23        | 0.6%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 22        | 0.58%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 21        | 0.55%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s               | 21        | 0.55%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s      | 20        | 0.52%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 20        | 0.52%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 20        | 0.52%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 20        | 0.52%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 19        | 0.5%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 19        | 0.5%    |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s              | 18        | 0.47%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 18        | 0.47%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s               | 18        | 0.47%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 17        | 0.44%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 17        | 0.44%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 17        | 0.44%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 17        | 0.44%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 16        | 0.42%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 16        | 0.42%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s                 | 16        | 0.42%   |
| SK hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s             | 15        | 0.39%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 15        | 0.39%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s              | 15        | 0.39%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s             | 14        | 0.37%   |
| Corsair RAM CMK16GX4M2E3200C16 8GB DIMM DDR4 3200MT/s               | 13        | 0.34%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 12        | 0.31%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 12        | 0.31%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 12        | 0.31%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 12        | 0.31%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s              | 12        | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1510      | 48.24%  |
| DDR3    | 948       | 30.29%  |
| DDR2    | 162       | 5.18%   |
| LPDDR4  | 141       | 4.5%    |
| SDRAM   | 88        | 2.81%   |
| Unknown | 87        | 2.78%   |
| LPDDR3  | 73        | 2.33%   |
| DDR5    | 61        | 1.95%   |
| LPDDR5  | 30        | 0.96%   |
| DDR     | 19        | 0.61%   |
| DRAM    | 11        | 0.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| SODIMM          | 1837      | 58.78%  |
| DIMM            | 1040      | 33.28%  |
| Row Of Chips    | 228       | 7.3%    |
| Chip            | 12        | 0.38%   |
| FB-DIMM         | 3         | 0.1%    |
| RIMM            | 2         | 0.06%   |
| Unknown         | 2         | 0.06%   |
| Proprietary Car | 1         | 0.03%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 1351      | 39.82%  |
| 4096  | 853       | 25.14%  |
| 16384 | 532       | 15.68%  |
| 2048  | 420       | 12.38%  |
| 1024  | 129       | 3.8%    |
| 32768 | 90        | 2.65%   |
| 512   | 10        | 0.29%   |
| 65536 | 4         | 0.12%   |
| 256   | 3         | 0.09%   |
| 3072  | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 589       | 17.46%  |
| 3200    | 554       | 16.42%  |
| 2667    | 480       | 14.23%  |
| 2400    | 276       | 8.18%   |
| 1333    | 204       | 6.05%   |
| 2133    | 152       | 4.51%   |
| 667     | 100       | 2.96%   |
| 1334    | 99        | 2.94%   |
| 800     | 83        | 2.46%   |
| 3600    | 71        | 2.1%    |
| Unknown | 68        | 2.02%   |
| 1867    | 65        | 1.93%   |
| 4800    | 44        | 1.3%    |
| 4267    | 43        | 1.27%   |
| 8400    | 37        | 1.1%    |
| 1067    | 36        | 1.07%   |
| 3733    | 34        | 1.01%   |
| 6400    | 32        | 0.95%   |
| 1866    | 28        | 0.83%   |
| 3266    | 25        | 0.74%   |
| 2933    | 25        | 0.74%   |
| 1066    | 23        | 0.68%   |
| 3400    | 22        | 0.65%   |
| 3533    | 21        | 0.62%   |
| 3800    | 19        | 0.56%   |
| 2048    | 19        | 0.56%   |
| 3000    | 18        | 0.53%   |
| 533     | 17        | 0.5%    |
| 2733    | 15        | 0.44%   |
| 4199    | 14        | 0.42%   |
| 2666    | 13        | 0.39%   |
| 4266    | 12        | 0.36%   |
| 5600    | 10        | 0.3%    |
| 1800    | 10        | 0.3%    |
| 3933    | 8         | 0.24%   |
| 3534    | 8         | 0.24%   |
| 3466    | 7         | 0.21%   |
| 2800    | 7         | 0.21%   |
| 1639    | 7         | 0.21%   |
| 975     | 7         | 0.21%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Hewlett-Packard          | 77        | 49.36%  |
| Brother Industries       | 31        | 19.87%  |
| Canon                    | 16        | 10.26%  |
| Samsung Electronics      | 9         | 5.77%   |
| Seiko Epson              | 8         | 5.13%   |
| Oki Data                 | 4         | 2.56%   |
| Dymo-CoStar              | 2         | 1.28%   |
| STMicroelectronics       | 1         | 0.64%   |
| Ricoh                    | 1         | 0.64%   |
| QinHeng Electronics      | 1         | 0.64%   |
| Prolific Technology      | 1         | 0.64%   |
| Magic Control Technology | 1         | 0.64%   |
| Lexmark International    | 1         | 0.64%   |
| Kyocera                  | 1         | 0.64%   |
| Konica Minolta           | 1         | 0.64%   |
| Apple                    | 1         | 0.64%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| HP LaserJet 1018                                | 6         | 3.82%   |
| HP DeskJet 2600 series                          | 6         | 3.82%   |
| Brother HL-2030 Laser Printer                   | 6         | 3.82%   |
| HP LaserJet 1020                                | 4         | 2.55%   |
| Canon PIXMA MG2500 Series                       | 4         | 2.55%   |
| HP ENVY 5540 series                             | 3         | 1.91%   |
| HP DeskJet F2492 All-in-One                     | 3         | 1.91%   |
| HP DeskJet 3630 series                          | 3         | 1.91%   |
| HP DeskJet 2700 series                          | 3         | 1.91%   |
| HP Deskjet 1050 J410                            | 3         | 1.91%   |
| Canon LiDE 400                                  | 3         | 1.91%   |
| Samsung M262x/M282x Xpress Series Laser Printer | 2         | 1.27%   |
| Samsung M2070 Series                            | 2         | 1.27%   |
| Oki Data USB Device                             | 2         | 1.27%   |
| Oki Data MC363 Multifunction Printer            | 2         | 1.27%   |
| HP Printing Support                             | 2         | 1.27%   |
| HP LaserJet 1010                                | 2         | 1.27%   |
| HP HP LaserJet M14-M17                          | 2         | 1.27%   |
| HP ENVY 5000 series                             | 2         | 1.27%   |
| HP ENVY 4520 series                             | 2         | 1.27%   |
| HP ENVY 4500 series                             | 2         | 1.27%   |
| HP DeskJet 5550                                 | 2         | 1.27%   |
| HP Deskjet 2050 J510                            | 2         | 1.27%   |
| Dymo-CoStar LabelWriter 450                     | 2         | 1.27%   |
| Canon CanoScan LiDE 300                         | 2         | 1.27%   |
| Brother Printer                                 | 2         | 1.27%   |
| Brother MFC-J5330DW                             | 2         | 1.27%   |
| Brother HL-2240D series                         | 2         | 1.27%   |
| Brother DCP-L2520DW                             | 2         | 1.27%   |
| Brother DCP-1510                                | 2         | 1.27%   |
| STMicroelectronics USB Printer P                | 1         | 0.64%   |
| Seiko Epson XP-255 257 Series                   | 1         | 0.64%   |
| Seiko Epson XP-235 Series                       | 1         | 0.64%   |
| Seiko Epson XP-225 Series                       | 1         | 0.64%   |
| Seiko Epson WF-2830 Series                      | 1         | 0.64%   |
| Seiko Epson Printer                             | 1         | 0.64%   |
| Seiko Epson L555 Series                         | 1         | 0.64%   |
| Seiko Epson L1300 Series                        | 1         | 0.64%   |
| Seiko Epson ET-2700 Series                      | 1         | 0.64%   |
| Samsung SCX-4300 Series                         | 1         | 0.64%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Canon                       | 18        | 48.65%  |
| Hewlett-Packard             | 8         | 21.62%  |
| Seiko Epson                 | 7         | 18.92%  |
| Acer Peripherals (now BenQ) | 2         | 5.41%   |
| Mustek Systems              | 1         | 2.7%    |
| KYE Systems (Mouse Systems) | 1         | 2.7%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 210                                  | 5         | 13.51%  |
| Canon CanoScan N670U/N676U/LiDE 20                       | 3         | 8.11%   |
| Canon CanoScan N1240U/LiDE 30                            | 3         | 8.11%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]       | 2         | 5.41%   |
| HP Scanjet 300                                           | 2         | 5.41%   |
| Canon CanoScan N650U/N656U                               | 2         | 5.41%   |
| Canon CanoScan LiDE 220                                  | 2         | 5.41%   |
| Acer Peripherals (now BenQ) S2W 3300U/4300U              | 2         | 5.41%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]              | 1         | 2.7%    |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]        | 1         | 2.7%    |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1         | 2.7%    |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]        | 1         | 2.7%    |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]        | 1         | 2.7%    |
| Mustek Systems ScanExpress 1200 CU                       | 1         | 2.7%    |
| KYE Systems (Mouse Systems) ColorPage-Vivid4             | 1         | 2.7%    |
| HP Scanjet N6010                                         | 1         | 2.7%    |
| HP ScanJet 5200c                                         | 1         | 2.7%    |
| HP ScanJet 4570c                                         | 1         | 2.7%    |
| HP ScanJet 4300c                                         | 1         | 2.7%    |
| HP ScanJet 3570c                                         | 1         | 2.7%    |
| HP ScanJet 3300c                                         | 1         | 2.7%    |
| Canon CanoScan LiDE 700F                                 | 1         | 2.7%    |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                   | 1         | 2.7%    |
| Canon CanoScan LIDE 25                                   | 1         | 2.7%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 767       | 21.76%  |
| IMC Networks                           | 386       | 10.95%  |
| Microdia                               | 231       | 6.55%   |
| Bison Electronics                      | 223       | 6.33%   |
| Realtek Semiconductor                  | 212       | 6.01%   |
| Logitech                               | 173       | 4.91%   |
| Quanta                                 | 169       | 4.79%   |
| Sunplus Innovation Technology          | 150       | 4.26%   |
| Suyin                                  | 129       | 3.66%   |
| Cheng Uei Precision Industry (Foxlink) | 127       | 3.6%    |
| Apple                                  | 117       | 3.32%   |
| Acer                                   | 110       | 3.12%   |
| Syntek                                 | 93        | 2.64%   |
| Alcor Micro                            | 64        | 1.82%   |
| Luxvisions Innotech Limited            | 54        | 1.53%   |
| Lite-On Technology                     | 53        | 1.5%    |
| Ricoh                                  | 36        | 1.02%   |
| Samsung Electronics                    | 29        | 0.82%   |
| Sonix Technology                       | 28        | 0.79%   |
| Silicon Motion                         | 26        | 0.74%   |
| Creative Technology                    | 23        | 0.65%   |
| Microsoft                              | 19        | 0.54%   |
| Z-Star Microelectronics                | 18        | 0.51%   |
| GEMBIRD                                | 16        | 0.45%   |
| Generalplus Technology                 | 14        | 0.4%    |
| USB Camera                             | 13        | 0.37%   |
| Lenovo                                 | 13        | 0.37%   |
| Importek                               | 13        | 0.37%   |
| SunplusIT                              | 12        | 0.34%   |
| Sunplus Technology                     | 10        | 0.28%   |
| ARC International                      | 10        | 0.28%   |
| ALi                                    | 10        | 0.28%   |
| webcamvendor                           | 9         | 0.26%   |
| KYE Systems (Mouse Systems)            | 9         | 0.26%   |
| Genesys Logic                          | 9         | 0.26%   |
| Cubeternet                             | 9         | 0.26%   |
| Trust                                  | 8         | 0.23%   |
| Intel                                  | 8         | 0.23%   |
| DigiTech                               | 8         | 0.23%   |
| Primax Electronics                     | 7         | 0.2%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                       | 109       | 3.07%   |
| Chicony Integrated Camera                               | 96        | 2.71%   |
| Chicony HD WebCam                                       | 84        | 2.37%   |
| Microdia Integrated_Webcam_HD                           | 78        | 2.2%    |
| IMC Networks USB2.0 VGA UVC WebCam                      | 74        | 2.09%   |
| IMC Networks Integrated Camera                          | 70        | 1.97%   |
| Bison Integrated Camera                                 | 54        | 1.52%   |
| Bison HD Webcam                                         | 47        | 1.32%   |
| Chicony USB2.0 VGA UVC WebCam                           | 46        | 1.3%    |
| Apple Built-in iSight                                   | 45        | 1.27%   |
| Realtek Integrated_Webcam_HD                            | 41        | 1.16%   |
| Logitech Webcam C270                                    | 40        | 1.13%   |
| Realtek USB Camera                                      | 39        | 1.1%    |
| Syntek Integrated Camera                                | 37        | 1.04%   |
| Quanta HP TrueVision HD Camera                          | 36        | 1.01%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 34        | 0.96%   |
| Microdia Webcam Vitade AF                               | 34        | 0.96%   |
| Sunplus HD WebCam                                       | 32        | 0.9%    |
| Chicony HP TrueVision HD Camera                         | 30        | 0.85%   |
| Chicony EasyCamera                                      | 30        | 0.85%   |
| Samsung Galaxy series, misc. (MTP mode)                 | 29        | 0.82%   |
| Chicony USB 2.0 Camera                                  | 29        | 0.82%   |
| Chicony TOSHIBA Web Camera - HD                         | 29        | 0.82%   |
| Apple FaceTime HD Camera (Built-in)                     | 29        | 0.82%   |
| Acer HD Webcam                                          | 29        | 0.82%   |
| Alcor Micro USB 2.0 Camera                              | 26        | 0.73%   |
| Chicony USB2.0 HD UVC WebCam                            | 25        | 0.7%    |
| Logitech HD Pro Webcam C920                             | 24        | 0.68%   |
| Acer Integrated Camera                                  | 24        | 0.68%   |
| Chicony HP Truevision HD                                | 23        | 0.65%   |
| Bison Lenovo EasyCamera                                 | 23        | 0.65%   |
| Sonix USB2.0 HD UVC WebCam                              | 22        | 0.62%   |
| Realtek Lenovo EasyCamera                               | 21        | 0.59%   |
| Lite-On Integrated Camera                               | 21        | 0.59%   |
| Syntek EasyCamera                                       | 20        | 0.56%   |
| Quanta HP Wide Vision HD Camera                         | 20        | 0.56%   |
| IMC Networks ov9734_azurewave_camera                    | 20        | 0.56%   |
| Chicony USB2.0 Camera                                   | 20        | 0.56%   |
| Chicony HP HD Camera                                    | 20        | 0.56%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 20        | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 153       | 30.42%  |
| Validity Sensors                   | 117       | 23.26%  |
| Shenzhen Goodix Technology         | 89        | 17.69%  |
| Elan Microelectronics              | 45        | 8.95%   |
| AuthenTec                          | 45        | 8.95%   |
| Upek                               | 28        | 5.57%   |
| LighTuning Technology              | 15        | 2.98%   |
| STMicroelectronics                 | 7         | 1.39%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 0.6%    |
| Focal-systems.Corp                 | 1         | 0.2%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 66        | 13.12%  |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 44        | 8.75%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 37        | 7.36%   |
| Elan ELAN:Fingerprint                                                      | 37        | 7.36%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 23        | 4.57%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 21        | 4.17%   |
| Shenzhen Goodix Fingerprint Reader                                         | 19        | 3.78%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 18        | 3.58%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 15        | 2.98%   |
| Synaptics  WBDI                                                            | 12        | 2.39%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 12        | 2.39%   |
| Validity Sensors Synaptics WBDI                                            | 11        | 2.19%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 10        | 1.99%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 10        | 1.99%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 9         | 1.79%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 9         | 1.79%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 9         | 1.79%   |
| AuthenTec Fingerprint Sensor                                               | 9         | 1.79%   |
| Elan ELAN:ARM-M4                                                           | 8         | 1.59%   |
| AuthenTec AES1600                                                          | 8         | 1.59%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 1.39%   |
| Validity Sensors VFS491                                                    | 6         | 1.19%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 6         | 1.19%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 1.19%   |
| Synaptics WBDI                                                             | 6         | 1.19%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 6         | 1.19%   |
| Synaptics Fingerprint reader [HP G6]                                       | 6         | 1.19%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 6         | 1.19%   |
| AuthenTec AES2810                                                          | 6         | 1.19%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 6         | 1.19%   |
| Upek TCS5B Fingerprint sensor                                              | 5         | 0.99%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 0.8%    |
| Validity Sensors Fingerprint scanner                                       | 4         | 0.8%    |
| Synaptics UWP WBDI Device                                                  | 4         | 0.8%    |
| Shenzhen Goodix FingerPrint                                                | 4         | 0.8%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 0.8%    |
| AuthenTec AES1660 Fingerprint Sensor                                       | 4         | 0.8%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 3         | 0.6%    |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 0.6%    |
| Synaptics UWP WBDI                                                         | 3         | 0.6%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 87        | 35.66%  |
| Broadcom                  | 63        | 25.82%  |
| O2 Micro                  | 26        | 10.66%  |
| Lenovo                    | 10        | 4.1%    |
| Advanced Card Systems     | 9         | 3.69%   |
| Chicony Electronics       | 8         | 3.28%   |
| Cherry                    | 7         | 2.87%   |
| Upek                      | 6         | 2.46%   |
| Realtek Semiconductor     | 6         | 2.46%   |
| C3PO                      | 6         | 2.46%   |
| SCM Microsystems          | 5         | 2.05%   |
| Gemalto (was Gemplus)     | 4         | 1.64%   |
| OmniKey                   | 2         | 0.82%   |
| Hewlett-Packard           | 2         | 0.82%   |
| In Focus Systems          | 1         | 0.41%   |
| Fujitsu Siemens Computers | 1         | 0.41%   |
| Bit4id                    | 1         | 0.41%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 82        | 33.61%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 25        | 10.25%  |
| Broadcom BCM5880 Secure Applications Processor                               | 20        | 8.2%    |
| Broadcom 5880                                                                | 18        | 7.38%   |
| Broadcom 58200                                                               | 13        | 5.33%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 11        | 4.51%   |
| Lenovo Integrated Smart Card Reader                                          | 10        | 4.1%    |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 8         | 3.28%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 7         | 2.87%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 6         | 2.46%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 6         | 2.46%   |
| C3PO LTC31v2                                                                 | 5         | 2.05%   |
| Alcor Micro Watchdata W 1981                                                 | 5         | 2.05%   |
| Cherry SmartTerminal XX1X                                                    | 4         | 1.64%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 3         | 1.23%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 1.23%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 3         | 1.23%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 0.82%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 2         | 0.82%   |
| SCM Microsystems SCR35xx USB Smart Card Reader                               | 1         | 0.41%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 0.41%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.41%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.41%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.41%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.41%   |
| C3PO USB SMART CARD READER                                                   | 1         | 0.41%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.41%   |
| Bit4id miniLector-s                                                          | 1         | 0.41%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.41%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.41%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 4476      | 72.39%  |
| 1     | 1347      | 21.79%  |
| 2     | 289       | 4.67%   |
| 3     | 45        | 0.73%   |
| 4     | 14        | 0.23%   |
| 5     | 7         | 0.11%   |
| 6     | 3         | 0.05%   |
| 9     | 1         | 0.02%   |
| 8     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 528       | 25.43%  |
| Fingerprint reader       | 493       | 23.75%  |
| Net/wireless             | 301       | 14.5%   |
| Chipcard                 | 198       | 9.54%   |
| Multimedia controller    | 141       | 6.79%   |
| Camera                   | 77        | 3.71%   |
| Communication controller | 61        | 2.94%   |
| Bluetooth                | 58        | 2.79%   |
| Unassigned class         | 44        | 2.12%   |
| Sound                    | 34        | 1.64%   |
| Storage                  | 31        | 1.49%   |
| Card reader              | 27        | 1.3%    |
| Network                  | 20        | 0.96%   |
| Net/ethernet             | 20        | 0.96%   |
| Flash memory             | 11        | 0.53%   |
| Modem                    | 10        | 0.48%   |
| Dvb card                 | 7         | 0.34%   |
| Storage/raid             | 5         | 0.24%   |
| Firewire controller      | 4         | 0.19%   |
| Storage/ide              | 3         | 0.14%   |
| Storage/nvme             | 2         | 0.1%    |
| Tv card                  | 1         | 0.05%   |

