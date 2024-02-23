Linux in Spain - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in Spain.

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

Total: 5111

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Unknown       | Unknown                     | [8c03bd946c](https://linux-hardware.org/?probe=8c03bd946c) | Feb 02, 2024 |
| HP            | ProBook 450 G8 Notebook ... | [0bbbc51a52](https://linux-hardware.org/?probe=0bbbc51a52) | Feb 02, 2024 |
| SLIMBOOK      | HERO-S-TGL-RTX              | [1260457422](https://linux-hardware.org/?probe=1260457422) | Feb 02, 2024 |
| Apple         | MacBookAir5,1               | [e25bf95ccb](https://linux-hardware.org/?probe=e25bf95ccb) | Feb 02, 2024 |
| Apple         | MacBookAir5,1               | [058a447435](https://linux-hardware.org/?probe=058a447435) | Feb 02, 2024 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [f0b3157a23](https://linux-hardware.org/?probe=f0b3157a23) | Feb 01, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JTC... | [e91ff8608c](https://linux-hardware.org/?probe=e91ff8608c) | Jan 31, 2024 |
| Apple         | MacBookPro11,1              | [3f6fe6218f](https://linux-hardware.org/?probe=3f6fe6218f) | Jan 31, 2024 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | [9c0cf210c3](https://linux-hardware.org/?probe=9c0cf210c3) | Jan 31, 2024 |
| Dell          | Latitude E5410              | [d91781267c](https://linux-hardware.org/?probe=d91781267c) | Jan 31, 2024 |
| HP            | Pavilion Laptop 15-ck0xx    | [573d69639e](https://linux-hardware.org/?probe=573d69639e) | Jan 31, 2024 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | [e26a562041](https://linux-hardware.org/?probe=e26a562041) | Jan 30, 2024 |
| Acer          | Nitro AN515-54              | [51116cec97](https://linux-hardware.org/?probe=51116cec97) | Jan 30, 2024 |
| Acer          | Nitro AN515-54              | [3b5313811c](https://linux-hardware.org/?probe=3b5313811c) | Jan 30, 2024 |
| Toshiba       | NB250                       | [f6694e7f86](https://linux-hardware.org/?probe=f6694e7f86) | Jan 30, 2024 |
| Toshiba       | NB250                       | [635c466f5f](https://linux-hardware.org/?probe=635c466f5f) | Jan 30, 2024 |
| HP            | ProBook 640 G1              | [7bbe891072](https://linux-hardware.org/?probe=7bbe891072) | Jan 29, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [3819e0c97d](https://linux-hardware.org/?probe=3819e0c97d) | Jan 29, 2024 |
| HP            | Laptop 15s-eq2xxx           | [0bba02c4c8](https://linux-hardware.org/?probe=0bba02c4c8) | Jan 29, 2024 |
| ASUSTek       | N550JK                      | [097f96652f](https://linux-hardware.org/?probe=097f96652f) | Jan 29, 2024 |
| Acer          | Nitro AN515-58              | [20b00f9064](https://linux-hardware.org/?probe=20b00f9064) | Jan 28, 2024 |
| HP            | Pavilion Laptop 14-dv1xx... | [21e149d013](https://linux-hardware.org/?probe=21e149d013) | Jan 28, 2024 |
| Acer          | Aspire M3-581G              | [b91416ad7c](https://linux-hardware.org/?probe=b91416ad7c) | Jan 28, 2024 |
| MSI           | Modern 15 H B13M            | [53eae9905c](https://linux-hardware.org/?probe=53eae9905c) | Jan 27, 2024 |
| HP            | Laptop 14s-fq0xxx           | [96bce63bad](https://linux-hardware.org/?probe=96bce63bad) | Jan 27, 2024 |
| Dell          | Inspiron 5405               | [c9256b244b](https://linux-hardware.org/?probe=c9256b244b) | Jan 27, 2024 |
| Acer          | Aspire A315-58              | [c85674acbd](https://linux-hardware.org/?probe=c85674acbd) | Jan 26, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [516ae40374](https://linux-hardware.org/?probe=516ae40374) | Jan 25, 2024 |
| Sony          | VPCEB3B4E                   | [afa1b50b5a](https://linux-hardware.org/?probe=afa1b50b5a) | Jan 25, 2024 |
| Lenovo        | IdeaPad Pro 5 14IMH9 83D... | [2915b21d64](https://linux-hardware.org/?probe=2915b21d64) | Jan 25, 2024 |
| Lenovo        | ThinkPad X1 Carbon 34604... | [8add6b9229](https://linux-hardware.org/?probe=8add6b9229) | Jan 24, 2024 |
| MSI           | Modern 15 B7M               | [f04098f192](https://linux-hardware.org/?probe=f04098f192) | Jan 23, 2024 |
| MSI           | Modern 15 B7M               | [1caccbdf16](https://linux-hardware.org/?probe=1caccbdf16) | Jan 23, 2024 |
| AZW           | Z83 V                       | [eed16e1e68](https://linux-hardware.org/?probe=eed16e1e68) | Jan 23, 2024 |
| AZW           | Z83 V                       | [b9b8c82621](https://linux-hardware.org/?probe=b9b8c82621) | Jan 23, 2024 |
| Unknown       | Unknown                     | [dd7b17439f](https://linux-hardware.org/?probe=dd7b17439f) | Jan 22, 2024 |
| Acer          | TravelMate B115-M           | [e91da1c312](https://linux-hardware.org/?probe=e91da1c312) | Jan 22, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [871f86a545](https://linux-hardware.org/?probe=871f86a545) | Jan 21, 2024 |
| Apple         | MacBookPro11,5              | [f3fe3777b0](https://linux-hardware.org/?probe=f3fe3777b0) | Jan 21, 2024 |
| Lenovo        | ThinkPad L15 Gen 1 20U3C... | [354671b848](https://linux-hardware.org/?probe=354671b848) | Jan 20, 2024 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | [fa6a332180](https://linux-hardware.org/?probe=fa6a332180) | Jan 20, 2024 |
| Sony          | VGN-NS11Z_S                 | [64fa921691](https://linux-hardware.org/?probe=64fa921691) | Jan 20, 2024 |
| Lenovo        | ThinkPad L15 Gen 1 20U3C... | [3e339aec48](https://linux-hardware.org/?probe=3e339aec48) | Jan 20, 2024 |
| Toshiba       | PORTEGE R700                | [9783d3e6f7](https://linux-hardware.org/?probe=9783d3e6f7) | Jan 20, 2024 |
| MSI           | Prestige 16Studio A13VF     | [c345bf4b85](https://linux-hardware.org/?probe=c345bf4b85) | Jan 20, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JTC... | [9f7b8c991a](https://linux-hardware.org/?probe=9f7b8c991a) | Jan 20, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [e07a558ed5](https://linux-hardware.org/?probe=e07a558ed5) | Jan 20, 2024 |
| Notebook      | W350STQ/W370ST              | [a61e368a41](https://linux-hardware.org/?probe=a61e368a41) | Jan 19, 2024 |
| Acer          | TravelMate 5744Z            | [b03213c22c](https://linux-hardware.org/?probe=b03213c22c) | Jan 19, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [363f712134](https://linux-hardware.org/?probe=363f712134) | Jan 19, 2024 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [dd3153283a](https://linux-hardware.org/?probe=dd3153283a) | Jan 19, 2024 |
| HP            | Laptop 15-bs0xx             | [8cd9ebc60f](https://linux-hardware.org/?probe=8cd9ebc60f) | Jan 18, 2024 |
| MSI           | Stealth 15M B12UE           | [64561711ef](https://linux-hardware.org/?probe=64561711ef) | Jan 18, 2024 |
| HP            | Laptop 15-fd0xxx            | [577019511f](https://linux-hardware.org/?probe=577019511f) | Jan 17, 2024 |
| HP            | Laptop 15-fd0xxx            | [fa7b8cb83e](https://linux-hardware.org/?probe=fa7b8cb83e) | Jan 17, 2024 |
| Lenovo        | ThinkPad X240 20AMS31700    | [d5d3c69c94](https://linux-hardware.org/?probe=d5d3c69c94) | Jan 17, 2024 |
| Lenovo        | ThinkPad X260 20F5S3J301    | [90905d3416](https://linux-hardware.org/?probe=90905d3416) | Jan 17, 2024 |
| Dell          | XPS 9315                    | [2271aed5c7](https://linux-hardware.org/?probe=2271aed5c7) | Jan 17, 2024 |
| HONOR         | HLYL-WXX9                   | [de76a39d7b](https://linux-hardware.org/?probe=de76a39d7b) | Jan 17, 2024 |
| Unknown       | Unknown                     | [40de727301](https://linux-hardware.org/?probe=40de727301) | Jan 16, 2024 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | [323c35348f](https://linux-hardware.org/?probe=323c35348f) | Jan 16, 2024 |
| Apple         | MacBookPro9,1               | [3b43ca4be8](https://linux-hardware.org/?probe=3b43ca4be8) | Jan 16, 2024 |
| Unknown       | Unknown                     | [7cb9c4ae9a](https://linux-hardware.org/?probe=7cb9c4ae9a) | Jan 15, 2024 |
| HP            | 630                         | [15cea68071](https://linux-hardware.org/?probe=15cea68071) | Jan 15, 2024 |
| Jumper        | EZpad .A002                 | [165b30453c](https://linux-hardware.org/?probe=165b30453c) | Jan 15, 2024 |
| Lenovo        | G580 2189                   | [9f78e2fda0](https://linux-hardware.org/?probe=9f78e2fda0) | Jan 15, 2024 |
| Apple         | MacBookPro12,1              | [1a33b5b4c6](https://linux-hardware.org/?probe=1a33b5b4c6) | Jan 14, 2024 |
| Gigabyte      | G5 KD                       | [1f4984ff1a](https://linux-hardware.org/?probe=1f4984ff1a) | Jan 14, 2024 |
| Apple         | MacBookPro12,1              | [6e1b95e72e](https://linux-hardware.org/?probe=6e1b95e72e) | Jan 14, 2024 |
| HUAWEI        | BOD-WXX9                    | [9000ce06e8](https://linux-hardware.org/?probe=9000ce06e8) | Jan 14, 2024 |
| Acer          | TravelMate P259-G2-M        | [24d3ae9a88](https://linux-hardware.org/?probe=24d3ae9a88) | Jan 14, 2024 |
| Sony          | VGN-NS11Z_S                 | [863785eef9](https://linux-hardware.org/?probe=863785eef9) | Jan 13, 2024 |
| HUAWEI        | BOD-WXX9                    | [fe4ed2794f](https://linux-hardware.org/?probe=fe4ed2794f) | Jan 13, 2024 |
| HUAWEI        | BOD-WXX9                    | [b5c9600b1e](https://linux-hardware.org/?probe=b5c9600b1e) | Jan 13, 2024 |
| HP            | EliteBook 840 G5            | [60f88b1f3f](https://linux-hardware.org/?probe=60f88b1f3f) | Jan 13, 2024 |
| Alurin        | ALU-LPT-N4020-8256-140      | [61fdeffbaf](https://linux-hardware.org/?probe=61fdeffbaf) | Jan 12, 2024 |
| Apple         | MacBookPro14,3              | [3b0c274172](https://linux-hardware.org/?probe=3b0c274172) | Jan 12, 2024 |
| Lenovo        | ThinkPad T440 20B7S1M20F    | [41dcda72fa](https://linux-hardware.org/?probe=41dcda72fa) | Jan 12, 2024 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [c913eb2c1b](https://linux-hardware.org/?probe=c913eb2c1b) | Jan 12, 2024 |
| Alienware     | 17 R5                       | [4588195d7c](https://linux-hardware.org/?probe=4588195d7c) | Jan 12, 2024 |
| HP            | 650                         | [9c5b3c57f6](https://linux-hardware.org/?probe=9c5b3c57f6) | Jan 11, 2024 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [da41d1e19b](https://linux-hardware.org/?probe=da41d1e19b) | Jan 11, 2024 |
| Toshiba       | Satellite L750              | [44ec4c7459](https://linux-hardware.org/?probe=44ec4c7459) | Jan 11, 2024 |
| Apple         | MacBookPro9,2               | [7cf8b59aee](https://linux-hardware.org/?probe=7cf8b59aee) | Jan 10, 2024 |
| Dell          | Latitude 5580               | [d97f97cf29](https://linux-hardware.org/?probe=d97f97cf29) | Jan 10, 2024 |
| HP            | Pavilion Sleekbook 14       | [9f54d91b95](https://linux-hardware.org/?probe=9f54d91b95) | Jan 10, 2024 |
| Toshiba       | PORTEGE R700                | [3322fd81c6](https://linux-hardware.org/?probe=3322fd81c6) | Jan 10, 2024 |
| Toshiba       | PORTEGE R700                | [dd25b116ff](https://linux-hardware.org/?probe=dd25b116ff) | Jan 10, 2024 |
| Primux Tec... | Primux_1406F_W10            | [30587bf7e5](https://linux-hardware.org/?probe=30587bf7e5) | Jan 10, 2024 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [1ed7bf40d8](https://linux-hardware.org/?probe=1ed7bf40d8) | Jan 10, 2024 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [e8e7b87b69](https://linux-hardware.org/?probe=e8e7b87b69) | Jan 10, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [6c8905667e](https://linux-hardware.org/?probe=6c8905667e) | Jan 09, 2024 |
| Primux Tec... | Primux_1406F_W10            | [8df3356415](https://linux-hardware.org/?probe=8df3356415) | Jan 09, 2024 |
| ASUSTek       | K52F                        | [0b3d88eb7e](https://linux-hardware.org/?probe=0b3d88eb7e) | Jan 09, 2024 |
| HP            | Notebook                    | [ae9cfe9cc7](https://linux-hardware.org/?probe=ae9cfe9cc7) | Jan 09, 2024 |
| Valve         | Galileo                     | [4032bdfc39](https://linux-hardware.org/?probe=4032bdfc39) | Jan 08, 2024 |
| MSI           | Modern 15 A5M               | [1032489aa7](https://linux-hardware.org/?probe=1032489aa7) | Jan 08, 2024 |
| Acer          | Aspire A315-24P             | [716c2f37dd](https://linux-hardware.org/?probe=716c2f37dd) | Jan 08, 2024 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [9ee22790e4](https://linux-hardware.org/?probe=9ee22790e4) | Jan 08, 2024 |
| Acer          | Aspire A315-24P             | [ba75fc0540](https://linux-hardware.org/?probe=ba75fc0540) | Jan 08, 2024 |
| HP            | Laptop                      | [0fce2e2603](https://linux-hardware.org/?probe=0fce2e2603) | Jan 08, 2024 |
| Lenovo        | G710 20252                  | [ec645bc6c5](https://linux-hardware.org/?probe=ec645bc6c5) | Jan 08, 2024 |
| Valve         | Jupiter                     | [67ec614b0e](https://linux-hardware.org/?probe=67ec614b0e) | Jan 07, 2024 |
| HP            | 350 G2                      | [75e4063ce8](https://linux-hardware.org/?probe=75e4063ce8) | Jan 07, 2024 |
| Valve         | Galileo                     | [7365f742df](https://linux-hardware.org/?probe=7365f742df) | Jan 06, 2024 |
| Dell          | Inspiron 1501               | [65d521ef7c](https://linux-hardware.org/?probe=65d521ef7c) | Jan 06, 2024 |
| Acer          | Aspire 5750G                | [f013b4abc7](https://linux-hardware.org/?probe=f013b4abc7) | Jan 05, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [cc89127000](https://linux-hardware.org/?probe=cc89127000) | Jan 05, 2024 |
| HP            | 83E9                        | [5794eaa509](https://linux-hardware.org/?probe=5794eaa509) | Jan 05, 2024 |
| HP            | 83E9                        | [ca6565530d](https://linux-hardware.org/?probe=ca6565530d) | Jan 05, 2024 |
| HP            | Laptop 15s-fq4xxx           | [11a2efcfc6](https://linux-hardware.org/?probe=11a2efcfc6) | Jan 05, 2024 |
| Valve         | Jupiter                     | [da56767d30](https://linux-hardware.org/?probe=da56767d30) | Jan 05, 2024 |
| ASUSTek       | K53SV                       | [c5f4f5d73b](https://linux-hardware.org/?probe=c5f4f5d73b) | Jan 04, 2024 |
| ASUSTek       | K53SV                       | [0dd63031cf](https://linux-hardware.org/?probe=0dd63031cf) | Jan 04, 2024 |
| Toshiba       | Satellite L50t-A            | [1067ec305c](https://linux-hardware.org/?probe=1067ec305c) | Jan 04, 2024 |
| Toshiba       | Satellite L50t-A            | [e5bd2a0ab7](https://linux-hardware.org/?probe=e5bd2a0ab7) | Jan 04, 2024 |
| HP            | Pavilion Laptop 14-dv1xx... | [0b2828413f](https://linux-hardware.org/?probe=0b2828413f) | Jan 03, 2024 |
| Dell          | Latitude 5511               | [3b186725e3](https://linux-hardware.org/?probe=3b186725e3) | Jan 01, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [4eb26f2685](https://linux-hardware.org/?probe=4eb26f2685) | Jan 01, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [47e1e3c766](https://linux-hardware.org/?probe=47e1e3c766) | Dec 31, 2023 |
| HP            | Laptop 17-cn3xxx            | [3a84122c5a](https://linux-hardware.org/?probe=3a84122c5a) | Dec 30, 2023 |
| HP            | Pavilion g6                 | [6adc1110b8](https://linux-hardware.org/?probe=6adc1110b8) | Dec 30, 2023 |
| HP            | Pavilion 17                 | [d6e11fbd64](https://linux-hardware.org/?probe=d6e11fbd64) | Dec 30, 2023 |
| Alurin        | ALU-BAR-I511-000-140        | [04ce6d9f2e](https://linux-hardware.org/?probe=04ce6d9f2e) | Dec 30, 2023 |
| Lenovo        | Yoga Slim 7 14APU8 83AA     | [8fe9261232](https://linux-hardware.org/?probe=8fe9261232) | Dec 30, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [a353b43ac0](https://linux-hardware.org/?probe=a353b43ac0) | Dec 29, 2023 |
| ASUSTek       | G750JS                      | [1164f5c600](https://linux-hardware.org/?probe=1164f5c600) | Dec 29, 2023 |
| ASUSTek       | ROG Strix G712LV_G712LV     | [c2d6079fe7](https://linux-hardware.org/?probe=c2d6079fe7) | Dec 28, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [4e1a45dee6](https://linux-hardware.org/?probe=4e1a45dee6) | Dec 28, 2023 |
| Qilive        | QW20141BSP                  | [3f2d1e03c3](https://linux-hardware.org/?probe=3f2d1e03c3) | Dec 28, 2023 |
| Apple         | MacBookPro15,4              | [b3691ac681](https://linux-hardware.org/?probe=b3691ac681) | Dec 28, 2023 |
| BAKED         | P65xRP                      | [4bd66fa9db](https://linux-hardware.org/?probe=4bd66fa9db) | Dec 28, 2023 |
| Packard Be... | EasyNote TN36               | [2b83138160](https://linux-hardware.org/?probe=2b83138160) | Dec 28, 2023 |
| Apple         | MacBookPro15,4              | [1d368b7c25](https://linux-hardware.org/?probe=1d368b7c25) | Dec 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [1fc3f917f2](https://linux-hardware.org/?probe=1fc3f917f2) | Dec 27, 2023 |
| Unknown       | Unknown                     | [0f40cd177e](https://linux-hardware.org/?probe=0f40cd177e) | Dec 27, 2023 |
| Unknown       | Unknown                     | [5965d25e5a](https://linux-hardware.org/?probe=5965d25e5a) | Dec 27, 2023 |
| Unknown       | Unknown                     | [0d550e2115](https://linux-hardware.org/?probe=0d550e2115) | Dec 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | [8af95757fe](https://linux-hardware.org/?probe=8af95757fe) | Dec 27, 2023 |
| Unknown       | Unknown                     | [2bb2a6cd8b](https://linux-hardware.org/?probe=2bb2a6cd8b) | Dec 27, 2023 |
| ASUSTek       | ROG Strix G713RW_G713RW     | [44db3755d8](https://linux-hardware.org/?probe=44db3755d8) | Dec 26, 2023 |
| Acer          | Nitro ANV15-51              | [0e1146871b](https://linux-hardware.org/?probe=0e1146871b) | Dec 26, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [4fb309a12a](https://linux-hardware.org/?probe=4fb309a12a) | Dec 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [229d71f583](https://linux-hardware.org/?probe=229d71f583) | Dec 26, 2023 |
| Unknown       | Unknown                     | [d382bd5980](https://linux-hardware.org/?probe=d382bd5980) | Dec 26, 2023 |
| Unknown       | Unknown                     | [c701a5ce22](https://linux-hardware.org/?probe=c701a5ce22) | Dec 26, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [5b4d3b8b68](https://linux-hardware.org/?probe=5b4d3b8b68) | Dec 25, 2023 |
| HP            | Laptop 17-bs1xx             | [736cd905c8](https://linux-hardware.org/?probe=736cd905c8) | Dec 25, 2023 |
| Clevo         | W760/M770CU                 | [c64bdf2349](https://linux-hardware.org/?probe=c64bdf2349) | Dec 24, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [720ff4cf67](https://linux-hardware.org/?probe=720ff4cf67) | Dec 24, 2023 |
| HP            | Unknown                     | [3bc06ba7d3](https://linux-hardware.org/?probe=3bc06ba7d3) | Dec 24, 2023 |
| Lenovo        | G50-80 80L0                 | [21df7039b9](https://linux-hardware.org/?probe=21df7039b9) | Dec 23, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | [36492390fd](https://linux-hardware.org/?probe=36492390fd) | Dec 22, 2023 |
| Acer          | Aspire VX5-591G             | [2268342e9f](https://linux-hardware.org/?probe=2268342e9f) | Dec 22, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | [7148cd104d](https://linux-hardware.org/?probe=7148cd104d) | Dec 22, 2023 |
| HP            | EliteBook 650 15.6 inch ... | [2e9f8a97e5](https://linux-hardware.org/?probe=2e9f8a97e5) | Dec 21, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [a102e5839d](https://linux-hardware.org/?probe=a102e5839d) | Dec 21, 2023 |
| Panasonic     | CF-19RDRCHH7                | [0e67081368](https://linux-hardware.org/?probe=0e67081368) | Dec 21, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [664d34d04d](https://linux-hardware.org/?probe=664d34d04d) | Dec 20, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [6f7295809b](https://linux-hardware.org/?probe=6f7295809b) | Dec 20, 2023 |
| MSI           | Alpha 17 C7VF               | [34b3014f66](https://linux-hardware.org/?probe=34b3014f66) | Dec 19, 2023 |
| Clevo         | W760/M770CU                 | [fdde778b3c](https://linux-hardware.org/?probe=fdde778b3c) | Dec 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [1b5268d64f](https://linux-hardware.org/?probe=1b5268d64f) | Dec 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [1290fe8e5a](https://linux-hardware.org/?probe=1290fe8e5a) | Dec 19, 2023 |
| HUAWEI        | KLVL-WXX9                   | [12f149be7f](https://linux-hardware.org/?probe=12f149be7f) | Dec 18, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [9afec278e2](https://linux-hardware.org/?probe=9afec278e2) | Dec 18, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [1d8ddbcb75](https://linux-hardware.org/?probe=1d8ddbcb75) | Dec 18, 2023 |
| ASUSTek       | X550EA                      | [a874ac5799](https://linux-hardware.org/?probe=a874ac5799) | Dec 18, 2023 |
| HP            | Victus by Gaming Laptop ... | [fd092daf92](https://linux-hardware.org/?probe=fd092daf92) | Dec 18, 2023 |
| HP            | EliteBook 8440p             | [4a83771100](https://linux-hardware.org/?probe=4a83771100) | Dec 18, 2023 |
| HP            | 255 G6 Notebook PC          | [f4412027d4](https://linux-hardware.org/?probe=f4412027d4) | Dec 18, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [26503ce57e](https://linux-hardware.org/?probe=26503ce57e) | Dec 17, 2023 |
| Notebook      | W65_67SR                    | [8f970e8d4c](https://linux-hardware.org/?probe=8f970e8d4c) | Dec 17, 2023 |
| ASUSTek       | K53SD                       | [7962dd075b](https://linux-hardware.org/?probe=7962dd075b) | Dec 17, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [299d6ae362](https://linux-hardware.org/?probe=299d6ae362) | Dec 17, 2023 |
| Allview       | Allbook H                   | [2da4fcb35c](https://linux-hardware.org/?probe=2da4fcb35c) | Dec 16, 2023 |
| HP            | G62                         | [fd110d99fd](https://linux-hardware.org/?probe=fd110d99fd) | Dec 15, 2023 |
| Lenovo        | IdeaPad Pro 5 16APH8 83A... | [d438fe20ff](https://linux-hardware.org/?probe=d438fe20ff) | Dec 15, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [cde85f7526](https://linux-hardware.org/?probe=cde85f7526) | Dec 15, 2023 |
| Lenovo        | B590 62742QG                | [edb1cd89f6](https://linux-hardware.org/?probe=edb1cd89f6) | Dec 15, 2023 |
| TUXEDO        | InfinityBook Pro Gen8 (M... | [5ae09c04d4](https://linux-hardware.org/?probe=5ae09c04d4) | Dec 14, 2023 |
| Lenovo        | ThinkPad E16 Gen 1 21JNC... | [46fbc450b5](https://linux-hardware.org/?probe=46fbc450b5) | Dec 14, 2023 |
| HP            | Laptop 15-fc0xxx            | [74030d2ce6](https://linux-hardware.org/?probe=74030d2ce6) | Dec 14, 2023 |
| MSI           | GS66 Stealth 10SE           | [7f045bdc89](https://linux-hardware.org/?probe=7f045bdc89) | Dec 14, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [c4e3486e91](https://linux-hardware.org/?probe=c4e3486e91) | Dec 13, 2023 |
| Lenovo        | IdeaPad Slim 3 15IAH8 83... | [f942d9c43e](https://linux-hardware.org/?probe=f942d9c43e) | Dec 13, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [8339b9aa1a](https://linux-hardware.org/?probe=8339b9aa1a) | Dec 13, 2023 |
| Apple         | MacBookPro11,3              | [c5d4eabc9b](https://linux-hardware.org/?probe=c5d4eabc9b) | Dec 12, 2023 |
| Apple         | MacBookPro11,3              | [87fa57a3af](https://linux-hardware.org/?probe=87fa57a3af) | Dec 12, 2023 |
| Acer          | Aspire A515-45              | [089a40a6f2](https://linux-hardware.org/?probe=089a40a6f2) | Dec 12, 2023 |
| Acer          | Aspire one                  | [fb1f2ccd2e](https://linux-hardware.org/?probe=fb1f2ccd2e) | Dec 12, 2023 |
| HP            | Laptop 15-fd0xxx            | [f5b7104728](https://linux-hardware.org/?probe=f5b7104728) | Dec 11, 2023 |
| Acer          | Aspire ES1-512              | [40438b3cd0](https://linux-hardware.org/?probe=40438b3cd0) | Dec 11, 2023 |
| HUAWEI        | KLVL-WXX9                   | [2abe635055](https://linux-hardware.org/?probe=2abe635055) | Dec 10, 2023 |
| HP            | Laptop 15-fc0xxx            | [a668492169](https://linux-hardware.org/?probe=a668492169) | Dec 10, 2023 |
| Dell          | Latitude 7490               | [d9f20ad453](https://linux-hardware.org/?probe=d9f20ad453) | Dec 10, 2023 |
| HP            | 240 G8 Notebook PC          | [e5f4045026](https://linux-hardware.org/?probe=e5f4045026) | Dec 10, 2023 |
| Packard Be... | EasyNote TE11BZ             | [514899b0b9](https://linux-hardware.org/?probe=514899b0b9) | Dec 10, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [215b8bc94a](https://linux-hardware.org/?probe=215b8bc94a) | Dec 09, 2023 |
| ASUSTek       | X540SA                      | [71c6b35d56](https://linux-hardware.org/?probe=71c6b35d56) | Dec 09, 2023 |
| Dell          | Vostro 3550                 | [21131b7844](https://linux-hardware.org/?probe=21131b7844) | Dec 09, 2023 |
| Dell          | Vostro 3560                 | [d2abe7128b](https://linux-hardware.org/?probe=d2abe7128b) | Dec 09, 2023 |
| Notebook      | N24_25JU                    | [48dc91498c](https://linux-hardware.org/?probe=48dc91498c) | Dec 09, 2023 |
| Notebook      | N24_25JU                    | [170b205714](https://linux-hardware.org/?probe=170b205714) | Dec 09, 2023 |
| Lenovo        | ThinkPad L15 Gen 4 21H3C... | [2c3c1f7ad2](https://linux-hardware.org/?probe=2c3c1f7ad2) | Dec 08, 2023 |
| HP            | Victus by Laptop 16-e1xx... | [9b973fc192](https://linux-hardware.org/?probe=9b973fc192) | Dec 08, 2023 |
| Lenovo        | ThinkPad L15 Gen 4 21H3C... | [f463c790b4](https://linux-hardware.org/?probe=f463c790b4) | Dec 08, 2023 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | [a7dccd5888](https://linux-hardware.org/?probe=a7dccd5888) | Dec 08, 2023 |
| HP            | 630                         | [b6c4bc59c1](https://linux-hardware.org/?probe=b6c4bc59c1) | Dec 08, 2023 |
| Apple         | MacBook5,1                  | [e6e9d305e9](https://linux-hardware.org/?probe=e6e9d305e9) | Dec 08, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1502CBA    | [b46d0490b6](https://linux-hardware.org/?probe=b46d0490b6) | Dec 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [2cc6eaff05](https://linux-hardware.org/?probe=2cc6eaff05) | Dec 08, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [69e785cddb](https://linux-hardware.org/?probe=69e785cddb) | Dec 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [82fd570b21](https://linux-hardware.org/?probe=82fd570b21) | Dec 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [b706d26f30](https://linux-hardware.org/?probe=b706d26f30) | Dec 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [18d69df8d2](https://linux-hardware.org/?probe=18d69df8d2) | Dec 07, 2023 |
| HP            | Laptop 15-fd0xxx            | [6bdc66013b](https://linux-hardware.org/?probe=6bdc66013b) | Dec 07, 2023 |
| HP            | Laptop 17-by3xxx            | [d124640ef5](https://linux-hardware.org/?probe=d124640ef5) | Dec 06, 2023 |
| HP            | EliteBook 840 G1            | [923f26e8d8](https://linux-hardware.org/?probe=923f26e8d8) | Dec 06, 2023 |
| Lenovo        | ThinkPad SL500 274678G      | [3cfa60a8bb](https://linux-hardware.org/?probe=3cfa60a8bb) | Dec 06, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [7317dc8b5c](https://linux-hardware.org/?probe=7317dc8b5c) | Dec 06, 2023 |
| Alurin        | Go Notebook                 | [197598d3dd](https://linux-hardware.org/?probe=197598d3dd) | Dec 05, 2023 |
| HP            | Pavilion 13 x360 PC         | [3eba272feb](https://linux-hardware.org/?probe=3eba272feb) | Dec 05, 2023 |
| HP            | 630                         | [7d372bb7da](https://linux-hardware.org/?probe=7d372bb7da) | Dec 04, 2023 |
| Lenovo        | B50-50 80S2                 | [6150907e1e](https://linux-hardware.org/?probe=6150907e1e) | Dec 04, 2023 |
| MSI           | Prestige 15 A12UD           | [b19937fb48](https://linux-hardware.org/?probe=b19937fb48) | Dec 04, 2023 |
| MSI           | Prestige 15 A12UD           | [0c9a3a5cae](https://linux-hardware.org/?probe=0c9a3a5cae) | Dec 04, 2023 |
| Adreamer      | PN1308P                     | [b503469408](https://linux-hardware.org/?probe=b503469408) | Dec 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [db9e1baffe](https://linux-hardware.org/?probe=db9e1baffe) | Dec 04, 2023 |
| Acer          | Aspire 5750G                | [8bca63eb54](https://linux-hardware.org/?probe=8bca63eb54) | Dec 03, 2023 |
| Dell          | Vostro 3550                 | [0926acf98a](https://linux-hardware.org/?probe=0926acf98a) | Dec 03, 2023 |
| Acer          | Aspire A315-24P             | [b8af3ee6d5](https://linux-hardware.org/?probe=b8af3ee6d5) | Dec 03, 2023 |
| Acer          | Aspire A315-24P             | [67efae847f](https://linux-hardware.org/?probe=67efae847f) | Dec 03, 2023 |
| Acer          | Aspire 5750G                | [f04a8e4722](https://linux-hardware.org/?probe=f04a8e4722) | Dec 03, 2023 |
| Lenovo        | IdeaPad 320S-15IKB 81BQ     | [9cedc35586](https://linux-hardware.org/?probe=9cedc35586) | Dec 03, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [3753de5af1](https://linux-hardware.org/?probe=3753de5af1) | Dec 03, 2023 |
| Lenovo        | ThinkPad W500 40624DG       | [920dc046a3](https://linux-hardware.org/?probe=920dc046a3) | Dec 03, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [426263e458](https://linux-hardware.org/?probe=426263e458) | Dec 03, 2023 |
| Acer          | Nitro AN515-58              | [e2d48a6b41](https://linux-hardware.org/?probe=e2d48a6b41) | Dec 03, 2023 |
| SLIMBOOK      | PROX-AMD5                   | [3a6eb27098](https://linux-hardware.org/?probe=3a6eb27098) | Dec 02, 2023 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [3b3d0cb740](https://linux-hardware.org/?probe=3b3d0cb740) | Dec 02, 2023 |
| Apple         | MacBookPro11,1              | [bb033837d5](https://linux-hardware.org/?probe=bb033837d5) | Dec 02, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [7eb86d01c5](https://linux-hardware.org/?probe=7eb86d01c5) | Dec 01, 2023 |
| Samsung       | R530/R730                   | [cdda254219](https://linux-hardware.org/?probe=cdda254219) | Dec 01, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [a828388299](https://linux-hardware.org/?probe=a828388299) | Nov 30, 2023 |
| MSI           | Prestige 16Studio A13VF     | [dc93bfeb80](https://linux-hardware.org/?probe=dc93bfeb80) | Nov 30, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [d92b5d4caf](https://linux-hardware.org/?probe=d92b5d4caf) | Nov 30, 2023 |
| Lenovo        | G50-80 80E5                 | [75dcedad41](https://linux-hardware.org/?probe=75dcedad41) | Nov 30, 2023 |
| Alurin        | ALU-LPT-N4020-8256-140      | [0524ad397b](https://linux-hardware.org/?probe=0524ad397b) | Nov 29, 2023 |
| HP            | EliteBook 640 14 inch G9... | [a9f36d870b](https://linux-hardware.org/?probe=a9f36d870b) | Nov 28, 2023 |
| HONOR         | HLYL-WXX9                   | [fa6847a75b](https://linux-hardware.org/?probe=fa6847a75b) | Nov 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon 34603... | [edb57fe6c8](https://linux-hardware.org/?probe=edb57fe6c8) | Nov 28, 2023 |
| HP            | EliteBook 640 14 inch G9... | [f5f1058473](https://linux-hardware.org/?probe=f5f1058473) | Nov 27, 2023 |
| HP            | Elite x2 1012 G1            | [388c6ba69d](https://linux-hardware.org/?probe=388c6ba69d) | Nov 27, 2023 |
| HP            | 250 G6 Notebook PC          | [936970029f](https://linux-hardware.org/?probe=936970029f) | Nov 27, 2023 |
| SHENZHEN Y... | XBOOK-3                     | [beeefc2461](https://linux-hardware.org/?probe=beeefc2461) | Nov 26, 2023 |
| HP            | ENVY m6                     | [41cff88708](https://linux-hardware.org/?probe=41cff88708) | Nov 26, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [7359fe59a4](https://linux-hardware.org/?probe=7359fe59a4) | Nov 25, 2023 |
| Dell          | Latitude 3510               | [0ebe37e56d](https://linux-hardware.org/?probe=0ebe37e56d) | Nov 25, 2023 |
| Lenovo        | IdeaPad Pro 5 16APH8 83A... | [2b5e71ca1e](https://linux-hardware.org/?probe=2b5e71ca1e) | Nov 24, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [ac2895b3d7](https://linux-hardware.org/?probe=ac2895b3d7) | Nov 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [d262dd65d4](https://linux-hardware.org/?probe=d262dd65d4) | Nov 24, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [94886bc9d7](https://linux-hardware.org/?probe=94886bc9d7) | Nov 24, 2023 |
| Lenovo        | ThinkPad T460 20FMS57C00    | [adabeb3e91](https://linux-hardware.org/?probe=adabeb3e91) | Nov 23, 2023 |
| MSI           | Prestige 15 A10SC           | [3b9404eda4](https://linux-hardware.org/?probe=3b9404eda4) | Nov 23, 2023 |
| Lenovo        | ThinkPad T460 20FMS57C00    | [467b2f3c4e](https://linux-hardware.org/?probe=467b2f3c4e) | Nov 23, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [6791592808](https://linux-hardware.org/?probe=6791592808) | Nov 22, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [69d5dcd30b](https://linux-hardware.org/?probe=69d5dcd30b) | Nov 22, 2023 |
| Valve         | Jupiter                     | [2fa43c6f3d](https://linux-hardware.org/?probe=2fa43c6f3d) | Nov 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [28af744237](https://linux-hardware.org/?probe=28af744237) | Nov 21, 2023 |
| Dell          | Latitude E6430              | [7fb0b53d1c](https://linux-hardware.org/?probe=7fb0b53d1c) | Nov 21, 2023 |
| MSI           | Pulse GL76 12UEK            | [def3f12e81](https://linux-hardware.org/?probe=def3f12e81) | Nov 21, 2023 |
| Allview       | Allbook H                   | [8c23eb07ac](https://linux-hardware.org/?probe=8c23eb07ac) | Nov 21, 2023 |
| Lenovo        | Legion Pro 7 16ARX8H 82W... | [43d2b6b8b6](https://linux-hardware.org/?probe=43d2b6b8b6) | Nov 21, 2023 |
| MSI           | Bravo 15 A4DDR              | [d678fe79f8](https://linux-hardware.org/?probe=d678fe79f8) | Nov 20, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | [ba43f46e34](https://linux-hardware.org/?probe=ba43f46e34) | Nov 20, 2023 |
| HP            | Laptop 15-bs0xx             | [3982d2c377](https://linux-hardware.org/?probe=3982d2c377) | Nov 20, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | [f91d973bab](https://linux-hardware.org/?probe=f91d973bab) | Nov 19, 2023 |
| Alurin        | ALU-BAR-R555-000-156        | [ce453601f1](https://linux-hardware.org/?probe=ce453601f1) | Nov 19, 2023 |
| HP            | ProBook 650 G1              | [80d502e7c1](https://linux-hardware.org/?probe=80d502e7c1) | Nov 19, 2023 |
| Lenovo        | Z50-75 80EC                 | [6876ff8fc6](https://linux-hardware.org/?probe=6876ff8fc6) | Nov 19, 2023 |
| HP            | Laptop 15-da0xxx            | [fa116d20dc](https://linux-hardware.org/?probe=fa116d20dc) | Nov 19, 2023 |
| Lenovo        | ThinkPad X13 Gen 3 21CMC... | [e25caef1f8](https://linux-hardware.org/?probe=e25caef1f8) | Nov 18, 2023 |
| Star Labs     | Lite                        | [715761cc4e](https://linux-hardware.org/?probe=715761cc4e) | Nov 18, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [66a57a819b](https://linux-hardware.org/?probe=66a57a819b) | Nov 17, 2023 |
| ASUSTek       | X540YA                      | [ffdc6b121c](https://linux-hardware.org/?probe=ffdc6b121c) | Nov 17, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [0c9b59ab03](https://linux-hardware.org/?probe=0c9b59ab03) | Nov 17, 2023 |
| MSI           | Pulse GL66 12UEK            | [9421ac824c](https://linux-hardware.org/?probe=9421ac824c) | Nov 17, 2023 |
| Sony          | VPCEB1J8E                   | [961e0e701d](https://linux-hardware.org/?probe=961e0e701d) | Nov 17, 2023 |
| Dell          | Precision 5680              | [a2957d2ece](https://linux-hardware.org/?probe=a2957d2ece) | Nov 16, 2023 |
| Dell          | Precision 5680              | [2c6c6027a6](https://linux-hardware.org/?probe=2c6c6027a6) | Nov 16, 2023 |
| MSI           | GF75 Thin 10SC              | [5388f8cbdd](https://linux-hardware.org/?probe=5388f8cbdd) | Nov 16, 2023 |
| Lenovo        | ThinkPad Edge E320 1298R... | [535d92743c](https://linux-hardware.org/?probe=535d92743c) | Nov 16, 2023 |
| Lenovo        | ThinkPad Edge E320 1298R... | [331f7da246](https://linux-hardware.org/?probe=331f7da246) | Nov 16, 2023 |
| Lenovo        | G580 2189                   | [552aa58bee](https://linux-hardware.org/?probe=552aa58bee) | Nov 16, 2023 |
| ASUSTek       | K52Jr                       | [142c6a9c61](https://linux-hardware.org/?probe=142c6a9c61) | Nov 15, 2023 |
| Adreamer      | PN1308P                     | [8c4d2fca5a](https://linux-hardware.org/?probe=8c4d2fca5a) | Nov 14, 2023 |
| Adreamer      | PN1308P                     | [5efc66eebc](https://linux-hardware.org/?probe=5efc66eebc) | Nov 14, 2023 |
| HP            | Laptop 15-bs0xx             | [1606b9e027](https://linux-hardware.org/?probe=1606b9e027) | Nov 14, 2023 |
| MSI           | Prestige 14 A10SC           | [59ad7e7e27](https://linux-hardware.org/?probe=59ad7e7e27) | Nov 14, 2023 |
| MSI           | Prestige 14 A10SC           | [6b1a5452f8](https://linux-hardware.org/?probe=6b1a5452f8) | Nov 14, 2023 |
| HP            | ENVY Laptop 13-aq0xxx       | [db881a2b07](https://linux-hardware.org/?probe=db881a2b07) | Nov 13, 2023 |
| HP            | ENVY Laptop 13-aq0xxx       | [b43a43b268](https://linux-hardware.org/?probe=b43a43b268) | Nov 13, 2023 |
| ASUSTek       | K52Jr                       | [7e34d5b70b](https://linux-hardware.org/?probe=7e34d5b70b) | Nov 13, 2023 |
| Toshiba       | PORTEGE Z30-B               | [2cd609dfe0](https://linux-hardware.org/?probe=2cd609dfe0) | Nov 12, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [78b909aa81](https://linux-hardware.org/?probe=78b909aa81) | Nov 12, 2023 |
| Lenovo        | ThinkPad L540 20AUS11P00    | [593d2114d9](https://linux-hardware.org/?probe=593d2114d9) | Nov 12, 2023 |
| HP            | 630                         | [ccc318ee31](https://linux-hardware.org/?probe=ccc318ee31) | Nov 12, 2023 |
| HP            | 630                         | [df3b4ec5db](https://linux-hardware.org/?probe=df3b4ec5db) | Nov 12, 2023 |
| Unknown       | Unknown                     | [be77c5477d](https://linux-hardware.org/?probe=be77c5477d) | Nov 12, 2023 |
| Unknown       | Unknown                     | [d93ab747bb](https://linux-hardware.org/?probe=d93ab747bb) | Nov 12, 2023 |
| Dell          | Latitude 7440               | [5c19a02292](https://linux-hardware.org/?probe=5c19a02292) | Nov 11, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [1ce5868093](https://linux-hardware.org/?probe=1ce5868093) | Nov 11, 2023 |
| Toshiba       | PORTEGE Z30-A               | [1b3661590f](https://linux-hardware.org/?probe=1b3661590f) | Nov 11, 2023 |
| Apple         | MacBookPro8,1               | [3da6dfb4b3](https://linux-hardware.org/?probe=3da6dfb4b3) | Nov 11, 2023 |
| ALLDOCUBE     | i1405C                      | [8f63b8af98](https://linux-hardware.org/?probe=8f63b8af98) | Nov 10, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [9f3d17b672](https://linux-hardware.org/?probe=9f3d17b672) | Nov 10, 2023 |
| MSI           | Prestige 15 A10SC           | [e2f423f938](https://linux-hardware.org/?probe=e2f423f938) | Nov 10, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [0bf36ad434](https://linux-hardware.org/?probe=0bf36ad434) | Nov 09, 2023 |
| HP            | Compaq Presario CQ70        | [1c495f3402](https://linux-hardware.org/?probe=1c495f3402) | Nov 09, 2023 |
| Lenovo        | G580 2189                   | [e6ceb0d192](https://linux-hardware.org/?probe=e6ceb0d192) | Nov 09, 2023 |
| LG Electro... | 15Z90RT-G.AD75B             | [2ec6124055](https://linux-hardware.org/?probe=2ec6124055) | Nov 09, 2023 |
| HP            | Pavilion dv6                | [919942c11f](https://linux-hardware.org/?probe=919942c11f) | Nov 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [193098a1ea](https://linux-hardware.org/?probe=193098a1ea) | Nov 08, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [ab1a7393ef](https://linux-hardware.org/?probe=ab1a7393ef) | Nov 08, 2023 |
| HP            | Pavilion dm4                | [93ee8aa87c](https://linux-hardware.org/?probe=93ee8aa87c) | Nov 08, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [0fceea6321](https://linux-hardware.org/?probe=0fceea6321) | Nov 08, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [c0f28da2b7](https://linux-hardware.org/?probe=c0f28da2b7) | Nov 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [18a292fb51](https://linux-hardware.org/?probe=18a292fb51) | Nov 07, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [24cd0b58d3](https://linux-hardware.org/?probe=24cd0b58d3) | Nov 07, 2023 |
| Unknown       | Unknown                     | [1545b5a7bb](https://linux-hardware.org/?probe=1545b5a7bb) | Nov 06, 2023 |
| Dell          | Inspiron 15 3511            | [27381bdf35](https://linux-hardware.org/?probe=27381bdf35) | Nov 06, 2023 |
| HP            | ProBook 640 G1              | [1cc495d15b](https://linux-hardware.org/?probe=1cc495d15b) | Nov 05, 2023 |
| HP            | Spectre Pro G1              | [78bce56071](https://linux-hardware.org/?probe=78bce56071) | Nov 05, 2023 |
| Toshiba       | TECRA R950                  | [864877692e](https://linux-hardware.org/?probe=864877692e) | Nov 05, 2023 |
| HP            | Pavilion dm4                | [ed4309477f](https://linux-hardware.org/?probe=ed4309477f) | Nov 05, 2023 |
| HP            | Pavilion dv6                | [60ff7a74af](https://linux-hardware.org/?probe=60ff7a74af) | Nov 05, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [ae9fcece31](https://linux-hardware.org/?probe=ae9fcece31) | Nov 05, 2023 |
| MSI           | Modern 15 B7M               | [b4a588e60e](https://linux-hardware.org/?probe=b4a588e60e) | Nov 04, 2023 |
| Lenovo        | G580 2189                   | [29a529e02c](https://linux-hardware.org/?probe=29a529e02c) | Nov 03, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [8b855ce4f4](https://linux-hardware.org/?probe=8b855ce4f4) | Nov 03, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [b724ede64d](https://linux-hardware.org/?probe=b724ede64d) | Nov 02, 2023 |
| MSI           | Prestige 14 A11SCS          | [e114e8ae5b](https://linux-hardware.org/?probe=e114e8ae5b) | Nov 02, 2023 |
| Lenovo        | Yoga Slim 9 14IAP7 82T0     | [11e373f762](https://linux-hardware.org/?probe=11e373f762) | Nov 02, 2023 |
| Lenovo        | ThinkPad X240 20AMS2EC00    | [820620d5c4](https://linux-hardware.org/?probe=820620d5c4) | Nov 01, 2023 |
| Dell          | G3 3579                     | [0b33f63284](https://linux-hardware.org/?probe=0b33f63284) | Nov 01, 2023 |
| Lenovo        | ThinkPad E560 20EVA02SSP    | [165be504bf](https://linux-hardware.org/?probe=165be504bf) | Nov 01, 2023 |
| HP            | ZBook 15u G6                | [b74e35da2b](https://linux-hardware.org/?probe=b74e35da2b) | Nov 01, 2023 |
| Acer          | Aspire E1-572G              | [d347dc93b5](https://linux-hardware.org/?probe=d347dc93b5) | Nov 01, 2023 |
| ASUSTek       | X550LD                      | [2d0fae2241](https://linux-hardware.org/?probe=2d0fae2241) | Nov 01, 2023 |
| ASUSTek       | X555QG                      | [f047c1d264](https://linux-hardware.org/?probe=f047c1d264) | Nov 01, 2023 |
| VANT          | MOOVE3-15                   | [5fc04a6d0a](https://linux-hardware.org/?probe=5fc04a6d0a) | Oct 31, 2023 |
| Toshiba       | Satellite C55-C             | [859d23eed0](https://linux-hardware.org/?probe=859d23eed0) | Oct 31, 2023 |
| VANT          | MOOVE3-15                   | [7e12621e6d](https://linux-hardware.org/?probe=7e12621e6d) | Oct 31, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [0eae5ed294](https://linux-hardware.org/?probe=0eae5ed294) | Oct 31, 2023 |
| Timi          | RedmiBook Pro 14S           | [780e721e24](https://linux-hardware.org/?probe=780e721e24) | Oct 30, 2023 |
| Unknown       | Unknown                     | [43e6db0023](https://linux-hardware.org/?probe=43e6db0023) | Oct 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [bb991098d1](https://linux-hardware.org/?probe=bb991098d1) | Oct 30, 2023 |
| MSI           | GF75 Thin 10SC              | [7aa47ebfa1](https://linux-hardware.org/?probe=7aa47ebfa1) | Oct 30, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [794edd04ea](https://linux-hardware.org/?probe=794edd04ea) | Oct 30, 2023 |
| Lenovo        | ZIWB2                       | [9e6bd45db9](https://linux-hardware.org/?probe=9e6bd45db9) | Oct 29, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [d443352482](https://linux-hardware.org/?probe=d443352482) | Oct 29, 2023 |
| Apple         | MacBookPro15,4              | [09ee918b60](https://linux-hardware.org/?probe=09ee918b60) | Oct 29, 2023 |
| Allview       | Allbook H                   | [e56046d262](https://linux-hardware.org/?probe=e56046d262) | Oct 29, 2023 |
| Allview       | Allbook H                   | [3f2fc29d49](https://linux-hardware.org/?probe=3f2fc29d49) | Oct 29, 2023 |
| Lenovo        | ThinkPad X270 20HMS1T600    | [97fbe59dd7](https://linux-hardware.org/?probe=97fbe59dd7) | Oct 29, 2023 |
| SLIMBOOK      | TITAN                       | [8697e4de09](https://linux-hardware.org/?probe=8697e4de09) | Oct 29, 2023 |
| HP            | Laptop 15-da0xxx            | [39d06d7acf](https://linux-hardware.org/?probe=39d06d7acf) | Oct 28, 2023 |
| HP            | Notebook                    | [715435e533](https://linux-hardware.org/?probe=715435e533) | Oct 28, 2023 |
| Toshiba       | TECRA R950                  | [afa984b0d3](https://linux-hardware.org/?probe=afa984b0d3) | Oct 28, 2023 |
| Packard Be... | EasyNote MH36               | [6d73774152](https://linux-hardware.org/?probe=6d73774152) | Oct 28, 2023 |
| SLIMBOOK      | PROX14-10                   | [4ffcd3ced8](https://linux-hardware.org/?probe=4ffcd3ced8) | Oct 28, 2023 |
| Lenovo        | ThinkPad L540 20AUS11P00    | [d59d45eb50](https://linux-hardware.org/?probe=d59d45eb50) | Oct 27, 2023 |
| MSI           | Modern 15 A10M              | [79b0d0252f](https://linux-hardware.org/?probe=79b0d0252f) | Oct 27, 2023 |
| Acer          | TravelMate P259-M           | [7c1c04b9b2](https://linux-hardware.org/?probe=7c1c04b9b2) | Oct 26, 2023 |
| Acer          | TravelMate P259-M           | [670cd56ea3](https://linux-hardware.org/?probe=670cd56ea3) | Oct 26, 2023 |
| Lenovo        | ZIWB2                       | [2537a6e7b9](https://linux-hardware.org/?probe=2537a6e7b9) | Oct 26, 2023 |
| Lenovo        | G580 2189                   | [bba412f376](https://linux-hardware.org/?probe=bba412f376) | Oct 26, 2023 |
| Unknown       | Unknown                     | [7d25c7409a](https://linux-hardware.org/?probe=7d25c7409a) | Oct 26, 2023 |
| Apple         | MacBookPro15,4              | [751e98cb04](https://linux-hardware.org/?probe=751e98cb04) | Oct 26, 2023 |
| MSI           | Prestige 15 A10SC           | [796a2f6a53](https://linux-hardware.org/?probe=796a2f6a53) | Oct 25, 2023 |
| ASUSTek       | GL752VW                     | [a11cf1d28d](https://linux-hardware.org/?probe=a11cf1d28d) | Oct 25, 2023 |
| Acer          | Aspire 9300                 | [3094b549c5](https://linux-hardware.org/?probe=3094b549c5) | Oct 25, 2023 |
| HP            | 14                          | [5e8b808f2f](https://linux-hardware.org/?probe=5e8b808f2f) | Oct 24, 2023 |
| TUXEDO        | InfinityBook Pro Gen8 (M... | [3907a62f64](https://linux-hardware.org/?probe=3907a62f64) | Oct 24, 2023 |
| rocky         | ASUS EXPERTBOOK B1402CBA... | [e7dc573b01](https://linux-hardware.org/?probe=e7dc573b01) | Oct 23, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B2502CBA... | [823dcebef0](https://linux-hardware.org/?probe=823dcebef0) | Oct 23, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B2502CBA... | [b7e1e895b9](https://linux-hardware.org/?probe=b7e1e895b9) | Oct 23, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | [f4375f7115](https://linux-hardware.org/?probe=f4375f7115) | Oct 23, 2023 |
| Acer          | TravelMate P259-M           | [d6096c6736](https://linux-hardware.org/?probe=d6096c6736) | Oct 23, 2023 |
| ASUSTek       | X551CA                      | [43c37fb1fe](https://linux-hardware.org/?probe=43c37fb1fe) | Oct 22, 2023 |
| ASUSTek       | X551CA                      | [e9a381c722](https://linux-hardware.org/?probe=e9a381c722) | Oct 22, 2023 |
| AZW           | SEi                         | [94602bd41b](https://linux-hardware.org/?probe=94602bd41b) | Oct 22, 2023 |
| Acer          | Aspire A715-76G             | [448723995f](https://linux-hardware.org/?probe=448723995f) | Oct 22, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [c5027da111](https://linux-hardware.org/?probe=c5027da111) | Oct 22, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [59d8c7186d](https://linux-hardware.org/?probe=59d8c7186d) | Oct 21, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | [f2ee678da1](https://linux-hardware.org/?probe=f2ee678da1) | Oct 21, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [37cdbd73b0](https://linux-hardware.org/?probe=37cdbd73b0) | Oct 21, 2023 |
| HP            | TouchSmart tm2              | [a79b82edd3](https://linux-hardware.org/?probe=a79b82edd3) | Oct 21, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [56621ceace](https://linux-hardware.org/?probe=56621ceace) | Oct 20, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [7323684232](https://linux-hardware.org/?probe=7323684232) | Oct 20, 2023 |
| Sony          | VPCSB2L1R                   | [153440d631](https://linux-hardware.org/?probe=153440d631) | Oct 20, 2023 |
| Razer         | Blade 14 (2022) - RZ09-0... | [64929e25f7](https://linux-hardware.org/?probe=64929e25f7) | Oct 20, 2023 |
| Chuwi         | MiniBook                    | [baaf33908c](https://linux-hardware.org/?probe=baaf33908c) | Oct 20, 2023 |
| Lenovo        | G500 20236                  | [6e5d214cb8](https://linux-hardware.org/?probe=6e5d214cb8) | Oct 20, 2023 |
| Razer         | Blade 14 (2022) - RZ09-0... | [da8f06a8e0](https://linux-hardware.org/?probe=da8f06a8e0) | Oct 19, 2023 |
| Toshiba       | Satellite P50t-B-118        | [5237c0866e](https://linux-hardware.org/?probe=5237c0866e) | Oct 19, 2023 |
| Dell          | Precision 7760              | [30e33a33c3](https://linux-hardware.org/?probe=30e33a33c3) | Oct 19, 2023 |
| ASUSTek       | X555QG                      | [e2e11a852f](https://linux-hardware.org/?probe=e2e11a852f) | Oct 19, 2023 |
| ASUSTek       | K46CB                       | [58573f017a](https://linux-hardware.org/?probe=58573f017a) | Oct 19, 2023 |
| HP            | TouchSmart tm2              | [f72f6a43b5](https://linux-hardware.org/?probe=f72f6a43b5) | Oct 19, 2023 |
| HP            | Laptop 15s-eq2xxx           | [9c9781a7ee](https://linux-hardware.org/?probe=9c9781a7ee) | Oct 19, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [a25bc084fc](https://linux-hardware.org/?probe=a25bc084fc) | Oct 19, 2023 |
| MSI           | Modern 15 A5M               | [cb9366b6ae](https://linux-hardware.org/?probe=cb9366b6ae) | Oct 18, 2023 |
| HP            | 250 G3                      | [e4e0140eb3](https://linux-hardware.org/?probe=e4e0140eb3) | Oct 18, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [b99a873ab7](https://linux-hardware.org/?probe=b99a873ab7) | Oct 18, 2023 |
| ASUSTek       | K46CB                       | [f524007ed7](https://linux-hardware.org/?probe=f524007ed7) | Oct 18, 2023 |
| HUAWEI        | KLVL-WXX9                   | [0ca9b4c2bd](https://linux-hardware.org/?probe=0ca9b4c2bd) | Oct 17, 2023 |
| HP            | Pavilion dv6                | [0846a94456](https://linux-hardware.org/?probe=0846a94456) | Oct 17, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DL... | [060a9c66c5](https://linux-hardware.org/?probe=060a9c66c5) | Oct 17, 2023 |
| Dell          | XPS 13 9310                 | [295c6b08bd](https://linux-hardware.org/?probe=295c6b08bd) | Oct 17, 2023 |
| ASUSTek       | N61Jv                       | [cb8a1ca22a](https://linux-hardware.org/?probe=cb8a1ca22a) | Oct 17, 2023 |
| MSI           | Prestige 14H B12UCX         | [81dac6f109](https://linux-hardware.org/?probe=81dac6f109) | Oct 17, 2023 |
| HP            | ProBook 440 G6              | [5860734f3a](https://linux-hardware.org/?probe=5860734f3a) | Oct 16, 2023 |
| Allview       | Allbook H                   | [456afe3921](https://linux-hardware.org/?probe=456afe3921) | Oct 16, 2023 |
| MSI           | Modern 14 A10RAS            | [571e9b4e91](https://linux-hardware.org/?probe=571e9b4e91) | Oct 15, 2023 |
| ASUSTek       | UX550VD                     | [a58d0c5f1c](https://linux-hardware.org/?probe=a58d0c5f1c) | Oct 15, 2023 |
| ASUSTek       | UX550VD                     | [c29e83963a](https://linux-hardware.org/?probe=c29e83963a) | Oct 15, 2023 |
| Teclast       | F7 Plus                     | [8c4d203e84](https://linux-hardware.org/?probe=8c4d203e84) | Oct 15, 2023 |
| Google        | Dratini                     | [0c74e4ac18](https://linux-hardware.org/?probe=0c74e4ac18) | Oct 15, 2023 |
| Google        | Dratini                     | [bc181ae269](https://linux-hardware.org/?probe=bc181ae269) | Oct 15, 2023 |
| Dell          | XPS 13 9343                 | [97a3c4d92d](https://linux-hardware.org/?probe=97a3c4d92d) | Oct 15, 2023 |
| MSI           | Prestige 14H B12UCX         | [ddc0082c22](https://linux-hardware.org/?probe=ddc0082c22) | Oct 14, 2023 |
| Dell          | Latitude E4200              | [2a5bbc07aa](https://linux-hardware.org/?probe=2a5bbc07aa) | Oct 14, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [11d91a0246](https://linux-hardware.org/?probe=11d91a0246) | Oct 14, 2023 |
| Medion        | E15415                      | [b9a4ecdc97](https://linux-hardware.org/?probe=b9a4ecdc97) | Oct 14, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [584433cc95](https://linux-hardware.org/?probe=584433cc95) | Oct 14, 2023 |
| MSI           | Prestige 14H B12UCX         | [63a132c897](https://linux-hardware.org/?probe=63a132c897) | Oct 13, 2023 |
| Panasonic     | CF-C1AD06GDE                | [473265139b](https://linux-hardware.org/?probe=473265139b) | Oct 13, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [b53da36041](https://linux-hardware.org/?probe=b53da36041) | Oct 12, 2023 |
| HP            | Unknown                     | [c64a37f28f](https://linux-hardware.org/?probe=c64a37f28f) | Oct 12, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [ba690b36a3](https://linux-hardware.org/?probe=ba690b36a3) | Oct 12, 2023 |
| MSI           | PS42 Modern 8MO             | [be9a0659d4](https://linux-hardware.org/?probe=be9a0659d4) | Oct 11, 2023 |
| HP            | EliteBook 840 G5            | [0baddc9010](https://linux-hardware.org/?probe=0baddc9010) | Oct 11, 2023 |
| HP            | 240 G8 Notebook PC          | [0a98dcd952](https://linux-hardware.org/?probe=0a98dcd952) | Oct 11, 2023 |
| Toshiba       | QOSMIO X70-B                | [fc0abd191f](https://linux-hardware.org/?probe=fc0abd191f) | Oct 11, 2023 |
| HP            | Laptop 15-fc0xxx            | [670b2194c0](https://linux-hardware.org/?probe=670b2194c0) | Oct 11, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [046e552e27](https://linux-hardware.org/?probe=046e552e27) | Oct 11, 2023 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | [d7d6c74d55](https://linux-hardware.org/?probe=d7d6c74d55) | Oct 11, 2023 |
| Lenovo        | G580 2189                   | [ea46e68be2](https://linux-hardware.org/?probe=ea46e68be2) | Oct 11, 2023 |
| Valve         | Jupiter                     | [2bde49db66](https://linux-hardware.org/?probe=2bde49db66) | Oct 11, 2023 |
| ASUSTek       | S550CM                      | [ad1b08de66](https://linux-hardware.org/?probe=ad1b08de66) | Oct 10, 2023 |
| HP            | Pavilion 11 x360 PC         | [947e4c6b2f](https://linux-hardware.org/?probe=947e4c6b2f) | Oct 10, 2023 |
| HUAWEI        | KLVL-WXXW                   | [3f6528d99d](https://linux-hardware.org/?probe=3f6528d99d) | Oct 10, 2023 |
| Lenovo        | ThinkPad L540 20AUS11P00    | [ec64651cec](https://linux-hardware.org/?probe=ec64651cec) | Oct 10, 2023 |
| Teclast       | F7S                         | [92c51af32a](https://linux-hardware.org/?probe=92c51af32a) | Oct 10, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [6d2a6c2a6f](https://linux-hardware.org/?probe=6d2a6c2a6f) | Oct 09, 2023 |
| Apple         | MacBookAir5,1               | [e4f9055fce](https://linux-hardware.org/?probe=e4f9055fce) | Oct 09, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [a41b75e081](https://linux-hardware.org/?probe=a41b75e081) | Oct 09, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [ac6149e371](https://linux-hardware.org/?probe=ac6149e371) | Oct 08, 2023 |
| Valve         | Jupiter                     | [86be8c226a](https://linux-hardware.org/?probe=86be8c226a) | Oct 08, 2023 |
| HP            | Notebook                    | [a181ec12af](https://linux-hardware.org/?probe=a181ec12af) | Oct 08, 2023 |
| HP            | Notebook                    | [039a70e9ce](https://linux-hardware.org/?probe=039a70e9ce) | Oct 07, 2023 |
| Dell          | Inspiron 16 Plus 7630       | [51571d43df](https://linux-hardware.org/?probe=51571d43df) | Oct 07, 2023 |
| VANT          | MOOVE14_2023                | [d9379b5405](https://linux-hardware.org/?probe=d9379b5405) | Oct 06, 2023 |
| Dell          | Latitude 7275               | [f1892c721d](https://linux-hardware.org/?probe=f1892c721d) | Oct 06, 2023 |
| Allview       | Allbook H                   | [9c1933c4eb](https://linux-hardware.org/?probe=9c1933c4eb) | Oct 06, 2023 |
| MSI           | GE63 Raider RGB 8RE         | [39b9855097](https://linux-hardware.org/?probe=39b9855097) | Oct 05, 2023 |
| MSI           | GE63 Raider RGB 8RE         | [74bb875f9f](https://linux-hardware.org/?probe=74bb875f9f) | Oct 05, 2023 |
| Lenovo        | G580 2189                   | [bd7f2d9d03](https://linux-hardware.org/?probe=bd7f2d9d03) | Oct 05, 2023 |
| MSI           | Prestige 15 A11SCX          | [9a4bc722e5](https://linux-hardware.org/?probe=9a4bc722e5) | Oct 05, 2023 |
| Lenovo        | B50-80 80LT                 | [74b54d0f3f](https://linux-hardware.org/?probe=74b54d0f3f) | Oct 05, 2023 |
| Acer          | Aspire M3-581G              | [040dc9b84b](https://linux-hardware.org/?probe=040dc9b84b) | Oct 04, 2023 |
| HP            | EliteBook 745 G6            | [77cfc34723](https://linux-hardware.org/?probe=77cfc34723) | Oct 04, 2023 |
| Apple         | MacBookPro14,2              | [49a295d5f0](https://linux-hardware.org/?probe=49a295d5f0) | Oct 04, 2023 |
| HP            | ENVY 15                     | [589ff0a0af](https://linux-hardware.org/?probe=589ff0a0af) | Oct 03, 2023 |
| Acer          | TravelMate P414-51          | [520fe0b494](https://linux-hardware.org/?probe=520fe0b494) | Oct 03, 2023 |
| HP            | EliteBook 840 G5            | [6615883de3](https://linux-hardware.org/?probe=6615883de3) | Oct 03, 2023 |
| Dynabook      | Satellite Pro C50-G         | [36e6d60078](https://linux-hardware.org/?probe=36e6d60078) | Oct 02, 2023 |
| ASUSTek       | ROG Strix G513IH_G513IH     | [7d076d124e](https://linux-hardware.org/?probe=7d076d124e) | Oct 02, 2023 |
| Dynabook      | Satellite Pro C50-E-11H     | [29d9d8dd30](https://linux-hardware.org/?probe=29d9d8dd30) | Oct 02, 2023 |
| Shuttle       | DS47D                       | [d4c27bdf9e](https://linux-hardware.org/?probe=d4c27bdf9e) | Oct 02, 2023 |
| MSI           | Vector GP68HX 12VH          | [e582127237](https://linux-hardware.org/?probe=e582127237) | Oct 02, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [6fb4d2a754](https://linux-hardware.org/?probe=6fb4d2a754) | Oct 01, 2023 |
| HP            | Presario CQ57               | [e83f052dc8](https://linux-hardware.org/?probe=e83f052dc8) | Oct 01, 2023 |
| Lenovo        | G500 20236                  | [96ce4b8060](https://linux-hardware.org/?probe=96ce4b8060) | Oct 01, 2023 |
| Packard Be... | DOT S                       | [5fd6d403d1](https://linux-hardware.org/?probe=5fd6d403d1) | Oct 01, 2023 |
| Acer          | Aspire E1-571               | [2e7aba6432](https://linux-hardware.org/?probe=2e7aba6432) | Oct 01, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | [085fbda5a6](https://linux-hardware.org/?probe=085fbda5a6) | Sep 30, 2023 |
| MSI           | Prestige 14H B12UCX         | [b3a006adc7](https://linux-hardware.org/?probe=b3a006adc7) | Sep 30, 2023 |
| MSI           | Prestige 15 A10SC           | [6e53cd8a65](https://linux-hardware.org/?probe=6e53cd8a65) | Sep 30, 2023 |
| MSI           | Prestige 14H B12UCX         | [1c1f35d1c8](https://linux-hardware.org/?probe=1c1f35d1c8) | Sep 30, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [3421ba07f9](https://linux-hardware.org/?probe=3421ba07f9) | Sep 30, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [480316a0da](https://linux-hardware.org/?probe=480316a0da) | Sep 30, 2023 |
| HP            | 250 G7 Notebook PC          | [2fc3f16671](https://linux-hardware.org/?probe=2fc3f16671) | Sep 30, 2023 |
| Packard Be... | EasyNote TK85               | [0c62f48dda](https://linux-hardware.org/?probe=0c62f48dda) | Sep 30, 2023 |
| Lenovo        | Z50-70 20354                | [eb33abdaae](https://linux-hardware.org/?probe=eb33abdaae) | Sep 29, 2023 |
| HP            | Laptop 15s-fq1xxx           | [08fb652352](https://linux-hardware.org/?probe=08fb652352) | Sep 29, 2023 |
| HP            | Laptop 15-fd0xxx            | [0a548c4390](https://linux-hardware.org/?probe=0a548c4390) | Sep 28, 2023 |
| HP            | Pavilion 11 x360 PC         | [b6316ea4df](https://linux-hardware.org/?probe=b6316ea4df) | Sep 28, 2023 |
| HP            | Pavilion 11 x360 PC         | [f75ab187aa](https://linux-hardware.org/?probe=f75ab187aa) | Sep 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [426e8bd9c0](https://linux-hardware.org/?probe=426e8bd9c0) | Sep 28, 2023 |
| HP            | Victus by Gaming Laptop ... | [3c4c65947a](https://linux-hardware.org/?probe=3c4c65947a) | Sep 28, 2023 |
| Packard Be... | EasyNote TK85               | [79e6dd1302](https://linux-hardware.org/?probe=79e6dd1302) | Sep 27, 2023 |
| Dell          | XPS 9315                    | [6fa1beb451](https://linux-hardware.org/?probe=6fa1beb451) | Sep 26, 2023 |
| LG Electro... | 13U70Q-G.AA75B              | [f38b79055b](https://linux-hardware.org/?probe=f38b79055b) | Sep 26, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [dd48e0075b](https://linux-hardware.org/?probe=dd48e0075b) | Sep 26, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [21c3145a6a](https://linux-hardware.org/?probe=21c3145a6a) | Sep 26, 2023 |
| MSI           | GF75 Thin 10SC              | [f19700e7b0](https://linux-hardware.org/?probe=f19700e7b0) | Sep 26, 2023 |
| MSI           | GF75 Thin 10SC              | [a7610be494](https://linux-hardware.org/?probe=a7610be494) | Sep 26, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [786338b217](https://linux-hardware.org/?probe=786338b217) | Sep 26, 2023 |
| Sony          | VPCSB2L1R                   | [9395b9347e](https://linux-hardware.org/?probe=9395b9347e) | Sep 26, 2023 |
| Acer          | Extensa 5635Z               | [19afe08920](https://linux-hardware.org/?probe=19afe08920) | Sep 25, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [1deb55b03b](https://linux-hardware.org/?probe=1deb55b03b) | Sep 25, 2023 |
| Sony          | SVF14A15CXB                 | [cbce21a887](https://linux-hardware.org/?probe=cbce21a887) | Sep 25, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [7d4c2dc8f6](https://linux-hardware.org/?probe=7d4c2dc8f6) | Sep 25, 2023 |
| Lenovo        | G580 2189                   | [7ddc30adc9](https://linux-hardware.org/?probe=7ddc30adc9) | Sep 23, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [a579fd2872](https://linux-hardware.org/?probe=a579fd2872) | Sep 23, 2023 |
| Lenovo        | G580 2189                   | [fe1c9060da](https://linux-hardware.org/?probe=fe1c9060da) | Sep 23, 2023 |
| Packard Be... | EasyNote TK85               | [c970ee5a12](https://linux-hardware.org/?probe=c970ee5a12) | Sep 23, 2023 |
| HP            | Pavilion g6                 | [226a590989](https://linux-hardware.org/?probe=226a590989) | Sep 23, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [347b768d57](https://linux-hardware.org/?probe=347b768d57) | Sep 22, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [6ae9f9d9f2](https://linux-hardware.org/?probe=6ae9f9d9f2) | Sep 22, 2023 |
| Toshiba       | Satellite Pro R40-D         | [d33d1b7b77](https://linux-hardware.org/?probe=d33d1b7b77) | Sep 22, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [7b093ed910](https://linux-hardware.org/?probe=7b093ed910) | Sep 22, 2023 |
| Primux Tec... | Primux_1406F_W10            | [a1911e4e9a](https://linux-hardware.org/?probe=a1911e4e9a) | Sep 22, 2023 |
| ASUSTek       | ZenBook Pro 15 UX550GEX_... | [aee02d5429](https://linux-hardware.org/?probe=aee02d5429) | Sep 22, 2023 |
| Dell          | XPS 9320                    | [1fe2e34799](https://linux-hardware.org/?probe=1fe2e34799) | Sep 22, 2023 |
| Primux Tec... | Primux_1406F_W10            | [c267e8d9a3](https://linux-hardware.org/?probe=c267e8d9a3) | Sep 22, 2023 |
| Dell          | XPS 15 7590                 | [146d33a16d](https://linux-hardware.org/?probe=146d33a16d) | Sep 22, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [7c5cc5e0ab](https://linux-hardware.org/?probe=7c5cc5e0ab) | Sep 22, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [74fa7aed8b](https://linux-hardware.org/?probe=74fa7aed8b) | Sep 22, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [28c84c64c1](https://linux-hardware.org/?probe=28c84c64c1) | Sep 21, 2023 |
| Acer          | Aspire F5-571               | [21bcc4a506](https://linux-hardware.org/?probe=21bcc4a506) | Sep 21, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [f9430fd075](https://linux-hardware.org/?probe=f9430fd075) | Sep 21, 2023 |
| MSI           | Prestige 14 A10SC           | [6f81167a6c](https://linux-hardware.org/?probe=6f81167a6c) | Sep 20, 2023 |
| Toshiba       | PORTEGE X30-E               | [2225b3687d](https://linux-hardware.org/?probe=2225b3687d) | Sep 20, 2023 |
| MSI           | Prestige 14 A10SC           | [e0ee68b1a7](https://linux-hardware.org/?probe=e0ee68b1a7) | Sep 20, 2023 |
| ASUSTek       | X556UQ                      | [c34d9b9514](https://linux-hardware.org/?probe=c34d9b9514) | Sep 20, 2023 |
| ASUSTek       | X556UQ                      | [7ec3567855](https://linux-hardware.org/?probe=7ec3567855) | Sep 20, 2023 |
| ASUSTek       | X556UQ                      | [676dd13401](https://linux-hardware.org/?probe=676dd13401) | Sep 20, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [911f7b8df2](https://linux-hardware.org/?probe=911f7b8df2) | Sep 19, 2023 |
| Apple         | MacBookAir7,2               | [6edec4d045](https://linux-hardware.org/?probe=6edec4d045) | Sep 19, 2023 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [b858f753b2](https://linux-hardware.org/?probe=b858f753b2) | Sep 19, 2023 |
| HP            | Laptop 15-fc0xxx            | [bb3c1bf2b9](https://linux-hardware.org/?probe=bb3c1bf2b9) | Sep 18, 2023 |
| HP            | Laptop 15-fc0xxx            | [4e845095f4](https://linux-hardware.org/?probe=4e845095f4) | Sep 18, 2023 |
| HP            | ProBook 4530s               | [251e7cc45b](https://linux-hardware.org/?probe=251e7cc45b) | Sep 18, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [1e40d8e0b9](https://linux-hardware.org/?probe=1e40d8e0b9) | Sep 18, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | [178981670d](https://linux-hardware.org/?probe=178981670d) | Sep 17, 2023 |
| HP            | Pavilion g6                 | [158b6f4df9](https://linux-hardware.org/?probe=158b6f4df9) | Sep 17, 2023 |
| Google        | Droid                       | [e0a0628d0a](https://linux-hardware.org/?probe=e0a0628d0a) | Sep 17, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [d37d40b74c](https://linux-hardware.org/?probe=d37d40b74c) | Sep 16, 2023 |
| Valve         | Jupiter                     | [3bd1c975cc](https://linux-hardware.org/?probe=3bd1c975cc) | Sep 16, 2023 |
| Chuwi         | GemiBook Pro                | [add3c0be93](https://linux-hardware.org/?probe=add3c0be93) | Sep 15, 2023 |
| HP            | Laptop 15-fc0xxx            | [c8ac03221f](https://linux-hardware.org/?probe=c8ac03221f) | Sep 15, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [1322cd195f](https://linux-hardware.org/?probe=1322cd195f) | Sep 15, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [b76ae8f9db](https://linux-hardware.org/?probe=b76ae8f9db) | Sep 15, 2023 |
| HP            | EliteBook 840 14 inch G9... | [9390e3d243](https://linux-hardware.org/?probe=9390e3d243) | Sep 15, 2023 |
| HP            | EliteBook 840 14 inch G9... | [9fc334d8b3](https://linux-hardware.org/?probe=9fc334d8b3) | Sep 15, 2023 |
| ASUSTek       | ROG Strix G713IC_G713IC     | [fd2d28b8af](https://linux-hardware.org/?probe=fd2d28b8af) | Sep 14, 2023 |
| Dell          | XPS 15 9560                 | [b0702745f5](https://linux-hardware.org/?probe=b0702745f5) | Sep 14, 2023 |
| Dell          | Inspiron N5110              | [e2454dd5b9](https://linux-hardware.org/?probe=e2454dd5b9) | Sep 14, 2023 |
| Toshiba       | PORTEGE Z830                | [a3e1ac295c](https://linux-hardware.org/?probe=a3e1ac295c) | Sep 14, 2023 |
| ASUSTek       | ROG Strix G713IC_G713IC     | [1cf96bfa0e](https://linux-hardware.org/?probe=1cf96bfa0e) | Sep 14, 2023 |
| Toshiba       | PORTEGE Z830                | [6f4c4a4120](https://linux-hardware.org/?probe=6f4c4a4120) | Sep 14, 2023 |
| Chuwi         | GemiBook Pro                | [9b982600ce](https://linux-hardware.org/?probe=9b982600ce) | Sep 14, 2023 |
| HP            | Laptop 15-bw0xx             | [c0bcb5b2c6](https://linux-hardware.org/?probe=c0bcb5b2c6) | Sep 14, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [262209b6a0](https://linux-hardware.org/?probe=262209b6a0) | Sep 13, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [d334b8fcd2](https://linux-hardware.org/?probe=d334b8fcd2) | Sep 13, 2023 |
| Lenovo        | ThinkPad E490 20N8000YUK    | [df9271331c](https://linux-hardware.org/?probe=df9271331c) | Sep 12, 2023 |
| MSI           | Katana GF66 12UC            | [0191ff7bb8](https://linux-hardware.org/?probe=0191ff7bb8) | Sep 12, 2023 |
| Acer          | Aspire A315-21              | [a7fca90eab](https://linux-hardware.org/?probe=a7fca90eab) | Sep 12, 2023 |
| SLIMBOOK      | Essential15L                | [92dbc92137](https://linux-hardware.org/?probe=92dbc92137) | Sep 12, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [84f6190c40](https://linux-hardware.org/?probe=84f6190c40) | Sep 11, 2023 |
| MSI           | GE70 2PE                    | [335798b8c9](https://linux-hardware.org/?probe=335798b8c9) | Sep 11, 2023 |
| MSI           | GE62 7RD                    | [ff590de77d](https://linux-hardware.org/?probe=ff590de77d) | Sep 11, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [24e256ad9e](https://linux-hardware.org/?probe=24e256ad9e) | Sep 11, 2023 |
| HP            | Laptop 15s-fq2xxx           | [366932ee55](https://linux-hardware.org/?probe=366932ee55) | Sep 11, 2023 |
| HP            | 240 G8 Notebook PC          | [6fec1bd640](https://linux-hardware.org/?probe=6fec1bd640) | Sep 11, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [7809da04f1](https://linux-hardware.org/?probe=7809da04f1) | Sep 10, 2023 |
| MSI           | Modern 14 A10M              | [978f30c076](https://linux-hardware.org/?probe=978f30c076) | Sep 10, 2023 |
| Acer          | Aspire E1-572G              | [9f3f71e147](https://linux-hardware.org/?probe=9f3f71e147) | Sep 10, 2023 |
| Acer          | Aspire E1-572G              | [f56c6e875b](https://linux-hardware.org/?probe=f56c6e875b) | Sep 10, 2023 |
| Fujitsu       | LIFEBOOK S752               | [de16eeb9ef](https://linux-hardware.org/?probe=de16eeb9ef) | Sep 09, 2023 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [3865278574](https://linux-hardware.org/?probe=3865278574) | Sep 09, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | [2e9fbd4683](https://linux-hardware.org/?probe=2e9fbd4683) | Sep 08, 2023 |
| HUAWEI        | KLVL-WXX9                   | [ff8e50a7ea](https://linux-hardware.org/?probe=ff8e50a7ea) | Sep 08, 2023 |
| ASUSTek       | UX430UAR                    | [dbd0ea122b](https://linux-hardware.org/?probe=dbd0ea122b) | Sep 08, 2023 |
| ASUSTek       | UX430UAR                    | [34601ced54](https://linux-hardware.org/?probe=34601ced54) | Sep 08, 2023 |
| HP            | 630                         | [11393e1391](https://linux-hardware.org/?probe=11393e1391) | Sep 08, 2023 |
| Lenovo        | ThinkPad E14 20RA001BUK     | [6bd319be4e](https://linux-hardware.org/?probe=6bd319be4e) | Sep 08, 2023 |
| Lenovo        | V15 G3 ABA 82TV             | [b906e23303](https://linux-hardware.org/?probe=b906e23303) | Sep 08, 2023 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | [7be90edf82](https://linux-hardware.org/?probe=7be90edf82) | Sep 08, 2023 |
| Notebook      | W65_67SR                    | [7169bc1dbb](https://linux-hardware.org/?probe=7169bc1dbb) | Sep 07, 2023 |
| Gigabyte      | Z97X-Gaming 5               | [a3cdc2345d](https://linux-hardware.org/?probe=a3cdc2345d) | Sep 07, 2023 |
| HP            | Pavilion dv6                | [9ffcb827b4](https://linux-hardware.org/?probe=9ffcb827b4) | Sep 07, 2023 |
| MSI           | Alpha 15 A3DDK              | [9a87dfb80b](https://linux-hardware.org/?probe=9a87dfb80b) | Sep 07, 2023 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | [0ca7d43ae9](https://linux-hardware.org/?probe=0ca7d43ae9) | Sep 07, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [a4fb146fe8](https://linux-hardware.org/?probe=a4fb146fe8) | Sep 06, 2023 |
| Sony          | VGN-AW41MF_H                | [d3a3262a6e](https://linux-hardware.org/?probe=d3a3262a6e) | Sep 06, 2023 |
| Lenovo        | ThinkPad X390 20Q0002UUS    | [aab185ac48](https://linux-hardware.org/?probe=aab185ac48) | Sep 06, 2023 |
| Valve         | Jupiter                     | [8209a15afb](https://linux-hardware.org/?probe=8209a15afb) | Sep 06, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [cac93ead6f](https://linux-hardware.org/?probe=cac93ead6f) | Sep 05, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [9d86c0f6e5](https://linux-hardware.org/?probe=9d86c0f6e5) | Sep 05, 2023 |
| ASUSTek       | X751LD                      | [ed90b83cc0](https://linux-hardware.org/?probe=ed90b83cc0) | Sep 05, 2023 |
| Dell          | Precision 7670              | [42788bf2c7](https://linux-hardware.org/?probe=42788bf2c7) | Sep 05, 2023 |
| MSI           | Prestige 14H B12UCX         | [75d602c66f](https://linux-hardware.org/?probe=75d602c66f) | Sep 05, 2023 |
| Dell          | Precision 7670              | [41bb07b203](https://linux-hardware.org/?probe=41bb07b203) | Sep 05, 2023 |
| Valve         | Jupiter                     | [8ae585f958](https://linux-hardware.org/?probe=8ae585f958) | Sep 05, 2023 |
| Dell          | Inspiron 3482               | [078746577b](https://linux-hardware.org/?probe=078746577b) | Sep 05, 2023 |
| HUAWEI        | KLVL-WXX9                   | [d3cde5f4c5](https://linux-hardware.org/?probe=d3cde5f4c5) | Sep 04, 2023 |
| Acer          | Aspire E1-571               | [032fca9d1d](https://linux-hardware.org/?probe=032fca9d1d) | Sep 04, 2023 |
| Chuwi         | GemiBook                    | [cfdc48e9f6](https://linux-hardware.org/?probe=cfdc48e9f6) | Sep 04, 2023 |
| SLIMBOOK      | PROX14-AMD                  | [c2da44c04f](https://linux-hardware.org/?probe=c2da44c04f) | Sep 04, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | [8e29b0ae51](https://linux-hardware.org/?probe=8e29b0ae51) | Sep 04, 2023 |
| HUAWEI        | KLVL-WXX9                   | [c3e4035d47](https://linux-hardware.org/?probe=c3e4035d47) | Sep 03, 2023 |
| IP3 Techno... | ARN59P                      | [493a986305](https://linux-hardware.org/?probe=493a986305) | Sep 03, 2023 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | [ba5eecca4c](https://linux-hardware.org/?probe=ba5eecca4c) | Sep 03, 2023 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | [6f9a36245f](https://linux-hardware.org/?probe=6f9a36245f) | Sep 03, 2023 |
| Toshiba       | Satellite L50-A-1DL         | [d46487843e](https://linux-hardware.org/?probe=d46487843e) | Sep 03, 2023 |
| HP            | Laptop 15-bs0xx             | [9651a05c1d](https://linux-hardware.org/?probe=9651a05c1d) | Sep 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [1458b372fd](https://linux-hardware.org/?probe=1458b372fd) | Sep 03, 2023 |
| Toshiba       | Satellite L10W-B-101        | [1865cdf1ad](https://linux-hardware.org/?probe=1865cdf1ad) | Sep 02, 2023 |
| HP            | ZBook 15 G2                 | [d20f8f324d](https://linux-hardware.org/?probe=d20f8f324d) | Sep 02, 2023 |
| HP            | Pavilion dv6                | [9190ad12c2](https://linux-hardware.org/?probe=9190ad12c2) | Sep 02, 2023 |
| Lenovo        | V145-15AST 81MT             | [741ffec692](https://linux-hardware.org/?probe=741ffec692) | Sep 01, 2023 |
| Lenovo        | G70-70 80HW                 | [f8ac18ebd1](https://linux-hardware.org/?probe=f8ac18ebd1) | Sep 01, 2023 |
| Fujitsu       | LIFEBOOK S760               | [b7439f4404](https://linux-hardware.org/?probe=b7439f4404) | Sep 01, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [0a715ba5aa](https://linux-hardware.org/?probe=0a715ba5aa) | Sep 01, 2023 |
| Medion        | E15301                      | [7f6c4eb814](https://linux-hardware.org/?probe=7f6c4eb814) | Aug 31, 2023 |
| Acer          | Extensa 5230                | [e4877c4cd7](https://linux-hardware.org/?probe=e4877c4cd7) | Aug 31, 2023 |
| Acer          | Aspire E1-571               | [62b0ee9c60](https://linux-hardware.org/?probe=62b0ee9c60) | Aug 31, 2023 |
| Acer          | Aspire E1-530               | [39c2df1a0b](https://linux-hardware.org/?probe=39c2df1a0b) | Aug 30, 2023 |
| Lenovo        | ThinkPad X230 2325AJG       | [fa550a5ea1](https://linux-hardware.org/?probe=fa550a5ea1) | Aug 30, 2023 |
| UMAX          | VisionBook 14Wr Plus        | [d07fd99df0](https://linux-hardware.org/?probe=d07fd99df0) | Aug 30, 2023 |
| HP            | Laptop 15s-fq2xxx           | [6d85c1d397](https://linux-hardware.org/?probe=6d85c1d397) | Aug 30, 2023 |
| Dell          | Precision 7680              | [90240d0ffd](https://linux-hardware.org/?probe=90240d0ffd) | Aug 30, 2023 |
| Dell          | Precision 7680              | [065ed91451](https://linux-hardware.org/?probe=065ed91451) | Aug 30, 2023 |
| Dell          | Latitude 5330               | [7e63575d10](https://linux-hardware.org/?probe=7e63575d10) | Aug 29, 2023 |
| Acer          | Aspire E1-571               | [3208c59e9c](https://linux-hardware.org/?probe=3208c59e9c) | Aug 29, 2023 |
| Dell          | Latitude 5530               | [151de667a5](https://linux-hardware.org/?probe=151de667a5) | Aug 28, 2023 |
| MSI           | Katana GF66 12UGS           | [ca352a81f4](https://linux-hardware.org/?probe=ca352a81f4) | Aug 28, 2023 |
| Dell          | XPS 15 7590                 | [9abe07288a](https://linux-hardware.org/?probe=9abe07288a) | Aug 28, 2023 |
| Dell          | XPS 15 9560                 | [8288d35dff](https://linux-hardware.org/?probe=8288d35dff) | Aug 28, 2023 |
| HP            | ProBook 4540s               | [a477892896](https://linux-hardware.org/?probe=a477892896) | Aug 27, 2023 |
| Dell          | Latitude E5470              | [582c495a92](https://linux-hardware.org/?probe=582c495a92) | Aug 27, 2023 |
| Dell          | Latitude E5470              | [63816a7b5f](https://linux-hardware.org/?probe=63816a7b5f) | Aug 27, 2023 |
| Notebook      | NL4x_NL5xLU                 | [22c5b125e0](https://linux-hardware.org/?probe=22c5b125e0) | Aug 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [d0de544ecd](https://linux-hardware.org/?probe=d0de544ecd) | Aug 25, 2023 |
| HP            | Laptop                      | [94fd1a7af2](https://linux-hardware.org/?probe=94fd1a7af2) | Aug 25, 2023 |
| HP            | Laptop 15s-fq4xxx           | [e2c530b9fd](https://linux-hardware.org/?probe=e2c530b9fd) | Aug 25, 2023 |
| Acer          | TravelMate P215-53          | [113a5418ca](https://linux-hardware.org/?probe=113a5418ca) | Aug 25, 2023 |
| Acer          | TravelMate P215-53          | [b2579f594d](https://linux-hardware.org/?probe=b2579f594d) | Aug 25, 2023 |
| Lenovo        | ThinkPad Edge 25453BG       | [188af952b0](https://linux-hardware.org/?probe=188af952b0) | Aug 24, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | [7fdfaacf03](https://linux-hardware.org/?probe=7fdfaacf03) | Aug 24, 2023 |
| Acer          | TravelMate P214-52          | [6d7eeef62a](https://linux-hardware.org/?probe=6d7eeef62a) | Aug 23, 2023 |
| Acer          | TravelMate P214-52          | [0a000435ae](https://linux-hardware.org/?probe=0a000435ae) | Aug 23, 2023 |
| Apple         | MacBookPro8,1               | [06b5fb7c7f](https://linux-hardware.org/?probe=06b5fb7c7f) | Aug 22, 2023 |
| Dynabook      | Satellite Pro C50-E-11F     | [b8955c7cf1](https://linux-hardware.org/?probe=b8955c7cf1) | Aug 22, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [b66d308d42](https://linux-hardware.org/?probe=b66d308d42) | Aug 21, 2023 |
| Packard Be... | EasyNote TJ66               | [7e5e1655a6](https://linux-hardware.org/?probe=7e5e1655a6) | Aug 20, 2023 |
| MSI           | GF75 Thin 10SC              | [f50df27008](https://linux-hardware.org/?probe=f50df27008) | Aug 20, 2023 |
| Lenovo        | Unknown                     | [fbbadac782](https://linux-hardware.org/?probe=fbbadac782) | Aug 20, 2023 |
| Lenovo        | IdeaPad 110-15AST 80TR      | [60385dd9f0](https://linux-hardware.org/?probe=60385dd9f0) | Aug 20, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [d93165e8a9](https://linux-hardware.org/?probe=d93165e8a9) | Aug 19, 2023 |
| HP            | EliteBook 850 G3            | [a6a7224d63](https://linux-hardware.org/?probe=a6a7224d63) | Aug 17, 2023 |
| Chuwi         | GemiBook Pro                | [6a2e05ff64](https://linux-hardware.org/?probe=6a2e05ff64) | Aug 17, 2023 |
| Valve         | Jupiter                     | [2981eb04ba](https://linux-hardware.org/?probe=2981eb04ba) | Aug 16, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | [bf65b5fe16](https://linux-hardware.org/?probe=bf65b5fe16) | Aug 16, 2023 |
| HP            | Pavilion Laptop 15-ck0xx    | [97ced089bf](https://linux-hardware.org/?probe=97ced089bf) | Aug 15, 2023 |
| Acer          | Aspire A315-59              | [901f34e440](https://linux-hardware.org/?probe=901f34e440) | Aug 15, 2023 |
| Packard Be... | EasyNote TK85               | [214e2092c6](https://linux-hardware.org/?probe=214e2092c6) | Aug 15, 2023 |
| System76      | Galago Pro                  | [54348f9c55](https://linux-hardware.org/?probe=54348f9c55) | Aug 14, 2023 |
| Medion        | E15301                      | [e42771be29](https://linux-hardware.org/?probe=e42771be29) | Aug 14, 2023 |
| Dynabook      | Satellite Pro C50-E-11H     | [589af795e9](https://linux-hardware.org/?probe=589af795e9) | Aug 14, 2023 |
| MSI           | GE60 2OC\2OD\2OE            | [f99741ec7f](https://linux-hardware.org/?probe=f99741ec7f) | Aug 14, 2023 |
| Lenovo        | B50-50 80S2                 | [6c897e0c63](https://linux-hardware.org/?probe=6c897e0c63) | Aug 14, 2023 |
| Packard Be... | EasyNote TK85               | [da059008eb](https://linux-hardware.org/?probe=da059008eb) | Aug 14, 2023 |
| Acer          | Aspire 5742                 | [ebc3e37c86](https://linux-hardware.org/?probe=ebc3e37c86) | Aug 13, 2023 |
| Acer          | Extensa 5635Z               | [e1a35ce655](https://linux-hardware.org/?probe=e1a35ce655) | Aug 13, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [1632c89b98](https://linux-hardware.org/?probe=1632c89b98) | Aug 13, 2023 |
| AXDIA Inte... | WINPAD V10                  | [4dc8c20191](https://linux-hardware.org/?probe=4dc8c20191) | Aug 13, 2023 |
| MSI           | Summit E16Flip A13VET       | [c8d4dbcf88](https://linux-hardware.org/?probe=c8d4dbcf88) | Aug 13, 2023 |
| Valve         | Jupiter                     | [441be5ab4d](https://linux-hardware.org/?probe=441be5ab4d) | Aug 13, 2023 |
| Lenovo        | G505s 20255                 | [9e0052d329](https://linux-hardware.org/?probe=9e0052d329) | Aug 12, 2023 |
| Lenovo        | ThinkPad L13 20R3CTO1WW     | [6ac135c81c](https://linux-hardware.org/?probe=6ac135c81c) | Aug 12, 2023 |
| HP            | Laptop 15-db0xxx            | [3d875407fc](https://linux-hardware.org/?probe=3d875407fc) | Aug 12, 2023 |
| Dell          | G7 7588                     | [48faf46c2c](https://linux-hardware.org/?probe=48faf46c2c) | Aug 12, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | [72899a615b](https://linux-hardware.org/?probe=72899a615b) | Aug 12, 2023 |
| Intel Clie... | LAPQC71A                    | [c87bff1d43](https://linux-hardware.org/?probe=c87bff1d43) | Aug 11, 2023 |
| MSI           | Creator Z16 A11UET          | [7883e9a69d](https://linux-hardware.org/?probe=7883e9a69d) | Aug 11, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | [c083cb5f2f](https://linux-hardware.org/?probe=c083cb5f2f) | Aug 11, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [a708832571](https://linux-hardware.org/?probe=a708832571) | Aug 11, 2023 |
| ASUSTek       | 1005PE                      | [088a155ec9](https://linux-hardware.org/?probe=088a155ec9) | Aug 10, 2023 |
| PC Special... | NH5xAx                      | [891b5ec398](https://linux-hardware.org/?probe=891b5ec398) | Aug 10, 2023 |
| HP            | Victus by Gaming Laptop ... | [8b57037d50](https://linux-hardware.org/?probe=8b57037d50) | Aug 09, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [afa02e4c02](https://linux-hardware.org/?probe=afa02e4c02) | Aug 09, 2023 |
| Dell          | Latitude 5520               | [478f0a6a07](https://linux-hardware.org/?probe=478f0a6a07) | Aug 09, 2023 |
| ASUSTek       | ROG Strix G614JV_G614JV     | [a8fc44190a](https://linux-hardware.org/?probe=a8fc44190a) | Aug 09, 2023 |
| ASUSTek       | ROG Strix G614JV_G614JV     | [766e35e920](https://linux-hardware.org/?probe=766e35e920) | Aug 09, 2023 |
| Acer          | Ferrari One 200             | [be688aa584](https://linux-hardware.org/?probe=be688aa584) | Aug 08, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [de86921bce](https://linux-hardware.org/?probe=de86921bce) | Aug 08, 2023 |
| MSI           | Creator Z16 A11UET          | [ea05388cf5](https://linux-hardware.org/?probe=ea05388cf5) | Aug 08, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [b73a01acaf](https://linux-hardware.org/?probe=b73a01acaf) | Aug 07, 2023 |
| SGIN          | laptop                      | [d80389ea87](https://linux-hardware.org/?probe=d80389ea87) | Aug 07, 2023 |
| HP            | 255 G3                      | [d4e6fedb82](https://linux-hardware.org/?probe=d4e6fedb82) | Aug 07, 2023 |
| HP            | 255 G3                      | [0861b2330b](https://linux-hardware.org/?probe=0861b2330b) | Aug 07, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | [77840c201a](https://linux-hardware.org/?probe=77840c201a) | Aug 07, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | [804851c490](https://linux-hardware.org/?probe=804851c490) | Aug 07, 2023 |
| Acer          | Aspire V5-121               | [4b8b0f132d](https://linux-hardware.org/?probe=4b8b0f132d) | Aug 07, 2023 |
| Notebook      | NS5x_NS7xPU                 | [d71ac9524e](https://linux-hardware.org/?probe=d71ac9524e) | Aug 06, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [56c7715a6d](https://linux-hardware.org/?probe=56c7715a6d) | Aug 06, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [6a9e7cc3e2](https://linux-hardware.org/?probe=6a9e7cc3e2) | Aug 06, 2023 |
| HP            | Victus by Laptop 16-d1xx... | [74c80ca51b](https://linux-hardware.org/?probe=74c80ca51b) | Aug 06, 2023 |
| ASUSTek       | R2H                         | [a2972dc454](https://linux-hardware.org/?probe=a2972dc454) | Aug 06, 2023 |
| ASUSTek       | R2H                         | [c32b5889aa](https://linux-hardware.org/?probe=c32b5889aa) | Aug 06, 2023 |
| Acer          | Aspire A315-59              | [fc1d6007aa](https://linux-hardware.org/?probe=fc1d6007aa) | Aug 05, 2023 |
| Acer          | Aspire A315-59              | [deff4c99b6](https://linux-hardware.org/?probe=deff4c99b6) | Aug 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [1d6bf926f6](https://linux-hardware.org/?probe=1d6bf926f6) | Aug 05, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | [e815f65a97](https://linux-hardware.org/?probe=e815f65a97) | Aug 05, 2023 |
| Sony          | VGN-NS11S_S                 | [8ad31bd20c](https://linux-hardware.org/?probe=8ad31bd20c) | Aug 05, 2023 |
| Chuwi         | GemiBook Pro                | [87ecdcb4bd](https://linux-hardware.org/?probe=87ecdcb4bd) | Aug 04, 2023 |
| Toshiba       | PORTEGE R700                | [f0df061bb2](https://linux-hardware.org/?probe=f0df061bb2) | Aug 04, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [294dcce02b](https://linux-hardware.org/?probe=294dcce02b) | Aug 04, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ee147b0313](https://linux-hardware.org/?probe=ee147b0313) | Aug 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [7f601fe313](https://linux-hardware.org/?probe=7f601fe313) | Aug 03, 2023 |
| HP            | Laptop 15s-fq1xxx           | [f495796fe8](https://linux-hardware.org/?probe=f495796fe8) | Aug 03, 2023 |
| Acer          | Aspire M3-581G              | [82814fbe1e](https://linux-hardware.org/?probe=82814fbe1e) | Aug 02, 2023 |
| Chuwi         | GemiBook Pro                | [eb2554dce9](https://linux-hardware.org/?probe=eb2554dce9) | Aug 02, 2023 |
| MSI           | Modern 15 A10M              | [bab451a11e](https://linux-hardware.org/?probe=bab451a11e) | Aug 02, 2023 |
| Sony          | VPCSB2L1R                   | [582f50ea25](https://linux-hardware.org/?probe=582f50ea25) | Aug 02, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [839698eb4c](https://linux-hardware.org/?probe=839698eb4c) | Aug 01, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [8e7e80c44e](https://linux-hardware.org/?probe=8e7e80c44e) | Aug 01, 2023 |
| HP            | Laptop 15-db0xxx            | [2d7cbca56b](https://linux-hardware.org/?probe=2d7cbca56b) | Aug 01, 2023 |
| Chuwi         | GemiBook Pro                | [be8a59432a](https://linux-hardware.org/?probe=be8a59432a) | Aug 01, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [2dcefa3349](https://linux-hardware.org/?probe=2dcefa3349) | Aug 01, 2023 |
| Valve         | Jupiter                     | [6ea9f908cb](https://linux-hardware.org/?probe=6ea9f908cb) | Aug 01, 2023 |
| Acer          | Aspire E5-573G              | [7e3e1a7ee9](https://linux-hardware.org/?probe=7e3e1a7ee9) | Jul 31, 2023 |
| SHENZHEN Y... | A8S PRO                     | [829a4178a5](https://linux-hardware.org/?probe=829a4178a5) | Jul 30, 2023 |
| Panasonic     | CFMX4-1                     | [925f36396d](https://linux-hardware.org/?probe=925f36396d) | Jul 30, 2023 |
| VANT          | MOOVE15_2023                | [6943d341c4](https://linux-hardware.org/?probe=6943d341c4) | Jul 29, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [ce140941bc](https://linux-hardware.org/?probe=ce140941bc) | Jul 29, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [19850c3ad1](https://linux-hardware.org/?probe=19850c3ad1) | Jul 29, 2023 |
| SHENZHEN Y... | A8S PRO                     | [08a6feda0e](https://linux-hardware.org/?probe=08a6feda0e) | Jul 28, 2023 |
| HP            | Victus by Gaming Laptop ... | [7595472fb4](https://linux-hardware.org/?probe=7595472fb4) | Jul 28, 2023 |
| HP            | g14                         | [39d4ce09a1](https://linux-hardware.org/?probe=39d4ce09a1) | Jul 28, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [61321e569d](https://linux-hardware.org/?probe=61321e569d) | Jul 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [4bd819d37b](https://linux-hardware.org/?probe=4bd819d37b) | Jul 28, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [0a1ef2aa5b](https://linux-hardware.org/?probe=0a1ef2aa5b) | Jul 27, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [d4914d5e5d](https://linux-hardware.org/?probe=d4914d5e5d) | Jul 27, 2023 |
| Samsung       | 700T                        | [a6c83540ad](https://linux-hardware.org/?probe=a6c83540ad) | Jul 27, 2023 |
| Acer          | Extensa 2510                | [b276a715eb](https://linux-hardware.org/?probe=b276a715eb) | Jul 27, 2023 |
| Acer          | Aspire V3-571G              | [88f60930be](https://linux-hardware.org/?probe=88f60930be) | Jul 26, 2023 |
| Samsung       | 700T                        | [881cb15d92](https://linux-hardware.org/?probe=881cb15d92) | Jul 25, 2023 |
| Acer          | Extensa 2530                | [6691e96edf](https://linux-hardware.org/?probe=6691e96edf) | Jul 25, 2023 |
| AXDIA Inte... | WINPAD V10                  | [0e7e712860](https://linux-hardware.org/?probe=0e7e712860) | Jul 24, 2023 |
| Apple         | MacBookAir4,2               | [e220379405](https://linux-hardware.org/?probe=e220379405) | Jul 24, 2023 |
| Medion        | E15301                      | [e20403ff58](https://linux-hardware.org/?probe=e20403ff58) | Jul 22, 2023 |
| Toshiba       | Satellite L50-B             | [5e7da1cf33](https://linux-hardware.org/?probe=5e7da1cf33) | Jul 22, 2023 |
| AMI           | Cherry Trail CR             | [42d75ac45a](https://linux-hardware.org/?probe=42d75ac45a) | Jul 21, 2023 |
| Packard Be... | EasyNote SL65               | [f66a4415f3](https://linux-hardware.org/?probe=f66a4415f3) | Jul 21, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [fe0c696d47](https://linux-hardware.org/?probe=fe0c696d47) | Jul 21, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [b541d17031](https://linux-hardware.org/?probe=b541d17031) | Jul 21, 2023 |
| Dell          | XPS 15 7590                 | [714d6a38d3](https://linux-hardware.org/?probe=714d6a38d3) | Jul 20, 2023 |
| Dell          | XPS 15 7590                 | [f7edcc8364](https://linux-hardware.org/?probe=f7edcc8364) | Jul 20, 2023 |
| Lenovo        | Z50-70 20354                | [f92f9065bc](https://linux-hardware.org/?probe=f92f9065bc) | Jul 19, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [ec673415b4](https://linux-hardware.org/?probe=ec673415b4) | Jul 19, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [35944db669](https://linux-hardware.org/?probe=35944db669) | Jul 19, 2023 |
| Apple         | MacBookPro16,1              | [dd5d384a71](https://linux-hardware.org/?probe=dd5d384a71) | Jul 18, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [dc76c90236](https://linux-hardware.org/?probe=dc76c90236) | Jul 18, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [1cffa4bad9](https://linux-hardware.org/?probe=1cffa4bad9) | Jul 18, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [cdaad6fa25](https://linux-hardware.org/?probe=cdaad6fa25) | Jul 18, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [fdbbd2b641](https://linux-hardware.org/?probe=fdbbd2b641) | Jul 18, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [b0c8aaef19](https://linux-hardware.org/?probe=b0c8aaef19) | Jul 16, 2023 |
| HP            | Laptop 15s-fq1xxx           | [10e24627b0](https://linux-hardware.org/?probe=10e24627b0) | Jul 16, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [5e43c9d869](https://linux-hardware.org/?probe=5e43c9d869) | Jul 15, 2023 |
| HP            | Laptop 15-bw0xx             | [56448b6dd8](https://linux-hardware.org/?probe=56448b6dd8) | Jul 15, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [bcf8e9f2c3](https://linux-hardware.org/?probe=bcf8e9f2c3) | Jul 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [f1bbc61bb6](https://linux-hardware.org/?probe=f1bbc61bb6) | Jul 14, 2023 |
| Dell          | XPS 15 7590                 | [28b21d099f](https://linux-hardware.org/?probe=28b21d099f) | Jul 14, 2023 |
| Acer          | TravelMate P246-MG          | [62348fa6ed](https://linux-hardware.org/?probe=62348fa6ed) | Jul 13, 2023 |
| Acer          | Aspire 5749                 | [fc6d20a364](https://linux-hardware.org/?probe=fc6d20a364) | Jul 13, 2023 |
| Chuwi         | GemiBook Pro                | [f73994358d](https://linux-hardware.org/?probe=f73994358d) | Jul 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [d7c5b64bcb](https://linux-hardware.org/?probe=d7c5b64bcb) | Jul 12, 2023 |
| Dell          | XPS 13 9380                 | [e40c69408d](https://linux-hardware.org/?probe=e40c69408d) | Jul 11, 2023 |
| Dell          | Latitude 7275               | [0647894f7f](https://linux-hardware.org/?probe=0647894f7f) | Jul 11, 2023 |
| ASUSTek       | X555LAB                     | [464293fd0e](https://linux-hardware.org/?probe=464293fd0e) | Jul 11, 2023 |
| Clevo         | M550SE/M660SE               | [65697a4412](https://linux-hardware.org/?probe=65697a4412) | Jul 10, 2023 |
| Acer          | Extensa 5635Z               | [4967fbddb9](https://linux-hardware.org/?probe=4967fbddb9) | Jul 10, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [4ee2490bde](https://linux-hardware.org/?probe=4ee2490bde) | Jul 10, 2023 |
| Dell          | Latitude E5420              | [6dba8e523b](https://linux-hardware.org/?probe=6dba8e523b) | Jul 09, 2023 |
| Notebook      | V1x0PNPx                    | [5a37402681](https://linux-hardware.org/?probe=5a37402681) | Jul 09, 2023 |
| Apple         | MacBookPro14,1              | [62bbadc762](https://linux-hardware.org/?probe=62bbadc762) | Jul 08, 2023 |
| Valve         | Jupiter                     | [7fc70add85](https://linux-hardware.org/?probe=7fc70add85) | Jul 08, 2023 |
| Acer          | Nitro AN515-46              | [010208e38d](https://linux-hardware.org/?probe=010208e38d) | Jul 08, 2023 |
| Valve         | Jupiter                     | [fd3d1bc540](https://linux-hardware.org/?probe=fd3d1bc540) | Jul 08, 2023 |
| Apple         | MacBookPro12,1              | [8877b51b89](https://linux-hardware.org/?probe=8877b51b89) | Jul 08, 2023 |
| Lenovo        | G580 2189                   | [a783ca495d](https://linux-hardware.org/?probe=a783ca495d) | Jul 06, 2023 |
| Acer          | Aspire 5749                 | [c4bea06a7d](https://linux-hardware.org/?probe=c4bea06a7d) | Jul 06, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [f603fed65f](https://linux-hardware.org/?probe=f603fed65f) | Jul 05, 2023 |
| Apple         | MacBookPro8,1               | [d25474786c](https://linux-hardware.org/?probe=d25474786c) | Jul 05, 2023 |
| Acer          | TravelMate P246-MG          | [e1e4548a49](https://linux-hardware.org/?probe=e1e4548a49) | Jul 05, 2023 |
| HUAWEI        | BOD-WXX9                    | [8121ccc8a9](https://linux-hardware.org/?probe=8121ccc8a9) | Jul 05, 2023 |
| HUAWEI        | BOD-WXX9                    | [656b411052](https://linux-hardware.org/?probe=656b411052) | Jul 05, 2023 |
| Medion        | X782X                       | [7369e18cc2](https://linux-hardware.org/?probe=7369e18cc2) | Jul 05, 2023 |
| HP            | Pavilion dv5                | [8064b5c083](https://linux-hardware.org/?probe=8064b5c083) | Jul 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [54a88e79d1](https://linux-hardware.org/?probe=54a88e79d1) | Jul 04, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [c3098317a7](https://linux-hardware.org/?probe=c3098317a7) | Jul 04, 2023 |
| Lenovo        | G580 2189                   | [4c68104591](https://linux-hardware.org/?probe=4c68104591) | Jul 03, 2023 |
| Dell          | Latitude 5520               | [acb3fdea1b](https://linux-hardware.org/?probe=acb3fdea1b) | Jul 03, 2023 |
| Dell          | Latitude 5520               | [4bbef448c9](https://linux-hardware.org/?probe=4bbef448c9) | Jul 03, 2023 |
| HP            | ENVY m6                     | [748e336af0](https://linux-hardware.org/?probe=748e336af0) | Jul 02, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [5daabbcd55](https://linux-hardware.org/?probe=5daabbcd55) | Jul 02, 2023 |
| Valve         | Jupiter                     | [7863106765](https://linux-hardware.org/?probe=7863106765) | Jul 02, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [1eb1ecf3a9](https://linux-hardware.org/?probe=1eb1ecf3a9) | Jul 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [f78c4a1930](https://linux-hardware.org/?probe=f78c4a1930) | Jul 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | [27c53e1152](https://linux-hardware.org/?probe=27c53e1152) | Jul 01, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [c1051d3ef0](https://linux-hardware.org/?probe=c1051d3ef0) | Jul 01, 2023 |
| Apple         | MacBookAir9,1               | [d5e55f9e7d](https://linux-hardware.org/?probe=d5e55f9e7d) | Jul 01, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [546fe2b3ab](https://linux-hardware.org/?probe=546fe2b3ab) | Jul 01, 2023 |
| Apple         | MacBookAir9,1               | [bd5c030739](https://linux-hardware.org/?probe=bd5c030739) | Jun 30, 2023 |
| Apple         | MacBookAir9,1               | [ce486a5063](https://linux-hardware.org/?probe=ce486a5063) | Jun 30, 2023 |
| MSI           | Modern 14 B5M               | [cb0eb574da](https://linux-hardware.org/?probe=cb0eb574da) | Jun 29, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [06212dc183](https://linux-hardware.org/?probe=06212dc183) | Jun 29, 2023 |
| Acer          | TravelMate P648-G2-M        | [1bb728e7dd](https://linux-hardware.org/?probe=1bb728e7dd) | Jun 29, 2023 |
| ASUSTek       | X541UAK                     | [83d0d28a2a](https://linux-hardware.org/?probe=83d0d28a2a) | Jun 29, 2023 |
| Acer          | TravelMate P648-G2-M        | [d1ade76136](https://linux-hardware.org/?probe=d1ade76136) | Jun 29, 2023 |
| Chuwi         | GemiBook                    | [90f0de1460](https://linux-hardware.org/?probe=90f0de1460) | Jun 28, 2023 |
| Acer          | Nitro AN515-54              | [b30ff15571](https://linux-hardware.org/?probe=b30ff15571) | Jun 28, 2023 |
| HP            | ENVY m6                     | [715d68bfc0](https://linux-hardware.org/?probe=715d68bfc0) | Jun 28, 2023 |
| HP            | Laptop 15s-eq2xxx           | [5922b4d31f](https://linux-hardware.org/?probe=5922b4d31f) | Jun 27, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [18c2eb78d4](https://linux-hardware.org/?probe=18c2eb78d4) | Jun 26, 2023 |
| MSI           | Prestige 14H B12UCX         | [abf425c8d7](https://linux-hardware.org/?probe=abf425c8d7) | Jun 26, 2023 |
| Acer          | TravelMate 6493             | [490906b996](https://linux-hardware.org/?probe=490906b996) | Jun 25, 2023 |
| Dell          | Inspiron MM061              | [8152698df7](https://linux-hardware.org/?probe=8152698df7) | Jun 25, 2023 |
| Toshiba       | Satellite U400              | [58b2ad81eb](https://linux-hardware.org/?probe=58b2ad81eb) | Jun 25, 2023 |
| Acer          | Aspire M3-581G              | [0c348c2570](https://linux-hardware.org/?probe=0c348c2570) | Jun 25, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [f14b9f6ce5](https://linux-hardware.org/?probe=f14b9f6ce5) | Jun 25, 2023 |
| HUAWEI        | HKD-WXX                     | [433d7b4f7e](https://linux-hardware.org/?probe=433d7b4f7e) | Jun 24, 2023 |
| Toshiba       | Satellite U400              | [aa6254ebd2](https://linux-hardware.org/?probe=aa6254ebd2) | Jun 24, 2023 |
| HP            | Compaq 610                  | [f312ec5ede](https://linux-hardware.org/?probe=f312ec5ede) | Jun 23, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [6c3a0a7fe0](https://linux-hardware.org/?probe=6c3a0a7fe0) | Jun 23, 2023 |
| Dell          | XPS 9320                    | [2dcfa6718b](https://linux-hardware.org/?probe=2dcfa6718b) | Jun 23, 2023 |
| MSI           | Alpha 15 A3DDK              | [410b20161b](https://linux-hardware.org/?probe=410b20161b) | Jun 23, 2023 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | [69dfee1765](https://linux-hardware.org/?probe=69dfee1765) | Jun 22, 2023 |
| Lenovo        | ThinkPad T480 20L6S3H102    | [4a8bd602ff](https://linux-hardware.org/?probe=4a8bd602ff) | Jun 21, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [014c851c43](https://linux-hardware.org/?probe=014c851c43) | Jun 21, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [291796e3e4](https://linux-hardware.org/?probe=291796e3e4) | Jun 21, 2023 |
| HP            | ENVY m6                     | [ea4c3aca13](https://linux-hardware.org/?probe=ea4c3aca13) | Jun 20, 2023 |
| win elemen... | MoreFine S500+              | [32b221a438](https://linux-hardware.org/?probe=32b221a438) | Jun 20, 2023 |
| Dell          | Latitude 7430               | [84f66041f9](https://linux-hardware.org/?probe=84f66041f9) | Jun 19, 2023 |
| Samsung       | RF510/RF410/RF710           | [6131e6746c](https://linux-hardware.org/?probe=6131e6746c) | Jun 19, 2023 |
| Toshiba       | TECRA M10                   | [37f232dce0](https://linux-hardware.org/?probe=37f232dce0) | Jun 19, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [2b32ca2d11](https://linux-hardware.org/?probe=2b32ca2d11) | Jun 18, 2023 |
| Toshiba       | NB510                       | [a66bda9742](https://linux-hardware.org/?probe=a66bda9742) | Jun 18, 2023 |
| HP            | Pavilion Notebook           | [5d417b3d76](https://linux-hardware.org/?probe=5d417b3d76) | Jun 18, 2023 |
| Samsung       | RV415/RV515/E3415           | [b17c80df83](https://linux-hardware.org/?probe=b17c80df83) | Jun 17, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [9cdeeb06de](https://linux-hardware.org/?probe=9cdeeb06de) | Jun 16, 2023 |
| Acer          | Aspire E1-571               | [19e270cab0](https://linux-hardware.org/?probe=19e270cab0) | Jun 16, 2023 |
| Acer          | Aspire E1-571               | [e4b27c6a92](https://linux-hardware.org/?probe=e4b27c6a92) | Jun 16, 2023 |
| MSI           | Modern 14 B5M               | [21bd3b8234](https://linux-hardware.org/?probe=21bd3b8234) | Jun 16, 2023 |
| MSI           | MPG Z490 GAMING PLUS        | [3ea85763dc](https://linux-hardware.org/?probe=3ea85763dc) | Jun 16, 2023 |
| HP            | G62                         | [2e1e964887](https://linux-hardware.org/?probe=2e1e964887) | Jun 16, 2023 |
| Lenovo        | ThinkPad T470 20HES2SH2B    | [2c6d49788f](https://linux-hardware.org/?probe=2c6d49788f) | Jun 16, 2023 |
| Valve         | Jupiter                     | [28dc5a83fe](https://linux-hardware.org/?probe=28dc5a83fe) | Jun 16, 2023 |
| Beelink       | Gemini X                    | [f95615a561](https://linux-hardware.org/?probe=f95615a561) | Jun 15, 2023 |
| Beelink       | Gemini X                    | [3f69d07a3e](https://linux-hardware.org/?probe=3f69d07a3e) | Jun 15, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | [b9eac1e0b6](https://linux-hardware.org/?probe=b9eac1e0b6) | Jun 15, 2023 |
| HP            | Notebook                    | [dc40bd89f8](https://linux-hardware.org/?probe=dc40bd89f8) | Jun 15, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [f616cb77b5](https://linux-hardware.org/?probe=f616cb77b5) | Jun 13, 2023 |
| Alurin        | ALU-LPT-N4020-8256-156      | [542a1217bd](https://linux-hardware.org/?probe=542a1217bd) | Jun 13, 2023 |
| Alurin        | ALU-LPT-N4020-8256-156      | [0b717c2785](https://linux-hardware.org/?probe=0b717c2785) | Jun 13, 2023 |
| HP            | ENVY m6                     | [b3c165b329](https://linux-hardware.org/?probe=b3c165b329) | Jun 12, 2023 |
| MSI           | Stealth 15M B12UE           | [aabb8192ee](https://linux-hardware.org/?probe=aabb8192ee) | Jun 12, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [7b48584062](https://linux-hardware.org/?probe=7b48584062) | Jun 11, 2023 |
| HUAWEI        | BOD-WXX9                    | [e6079c9659](https://linux-hardware.org/?probe=e6079c9659) | Jun 11, 2023 |
| HUAWEI        | BOD-WXX9                    | [5a7c331645](https://linux-hardware.org/?probe=5a7c331645) | Jun 11, 2023 |
| HUAWEI        | BoDE-WXX9                   | [8bc28cc12c](https://linux-hardware.org/?probe=8bc28cc12c) | Jun 11, 2023 |
| Lenovo        | G580 2189                   | [eac7ae2f7a](https://linux-hardware.org/?probe=eac7ae2f7a) | Jun 11, 2023 |
| Sony          | VGN-FW41J_H                 | [0d419f2c9d](https://linux-hardware.org/?probe=0d419f2c9d) | Jun 11, 2023 |
| Valve         | Jupiter                     | [c7e458735d](https://linux-hardware.org/?probe=c7e458735d) | Jun 11, 2023 |
| Valve         | Jupiter                     | [3e31827529](https://linux-hardware.org/?probe=3e31827529) | Jun 11, 2023 |
| Sony          | VGN-FW41J_H                 | [afc5d143fe](https://linux-hardware.org/?probe=afc5d143fe) | Jun 11, 2023 |
| MSI           | Prestige 15 A10SC           | [ceb7680734](https://linux-hardware.org/?probe=ceb7680734) | Jun 11, 2023 |
| Lenovo        | ThinkPad T450 20BU000BIX    | [d82c175e3e](https://linux-hardware.org/?probe=d82c175e3e) | Jun 10, 2023 |
| Beelink       | Gemini X                    | [adcb5e774d](https://linux-hardware.org/?probe=adcb5e774d) | Jun 10, 2023 |
| Packard Be... | EasyNote TE11BZ             | [a8f9a31f17](https://linux-hardware.org/?probe=a8f9a31f17) | Jun 10, 2023 |
| Lenovo        | ThinkPad T61 7660A25        | [e1617105e0](https://linux-hardware.org/?probe=e1617105e0) | Jun 10, 2023 |
| Dell          | Latitude E5500              | [41ad12c465](https://linux-hardware.org/?probe=41ad12c465) | Jun 10, 2023 |
| Apple         | MacBookPro5,5               | [1b3630b25a](https://linux-hardware.org/?probe=1b3630b25a) | Jun 10, 2023 |
| Apple         | MacBookPro11,4              | [6d70667d42](https://linux-hardware.org/?probe=6d70667d42) | Jun 09, 2023 |
| MSI           | GE66 Raider 10UE            | [38a5122d9c](https://linux-hardware.org/?probe=38a5122d9c) | Jun 08, 2023 |
| Micro Comp... | NUCXI7                      | [3b930f4e22](https://linux-hardware.org/?probe=3b930f4e22) | Jun 08, 2023 |
| Beelink       | Gemini X                    | [49aca69972](https://linux-hardware.org/?probe=49aca69972) | Jun 07, 2023 |
| MSI           | Stealth 15M B12UE           | [ff2ebbb0ae](https://linux-hardware.org/?probe=ff2ebbb0ae) | Jun 07, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16ARH7 8... | [265c19be27](https://linux-hardware.org/?probe=265c19be27) | Jun 07, 2023 |
| MSI           | GT72 2QE                    | [211494a051](https://linux-hardware.org/?probe=211494a051) | Jun 07, 2023 |
| MSI           | Stealth 15M B12UE           | [acae4ee06e](https://linux-hardware.org/?probe=acae4ee06e) | Jun 06, 2023 |
| MSI           | Modern 14 C12M              | [a5d1a0e656](https://linux-hardware.org/?probe=a5d1a0e656) | Jun 04, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [1352a1d7c7](https://linux-hardware.org/?probe=1352a1d7c7) | Jun 04, 2023 |
| Acer          | Aspire E1-572P              | [a90316cac7](https://linux-hardware.org/?probe=a90316cac7) | Jun 04, 2023 |
| ASUSTek       | ROG Strix G712LW_G712LW     | [04fdc3c3b8](https://linux-hardware.org/?probe=04fdc3c3b8) | Jun 03, 2023 |
| Valve         | Jupiter                     | [8c33873318](https://linux-hardware.org/?probe=8c33873318) | Jun 03, 2023 |
| MSI           | Prestige 16 A12UD           | [b13e4f0242](https://linux-hardware.org/?probe=b13e4f0242) | Jun 02, 2023 |
| Notebook      | NL40_50CU                   | [47b838db36](https://linux-hardware.org/?probe=47b838db36) | Jun 02, 2023 |
| Notebook      | N141CU                      | [4af09bd0c3](https://linux-hardware.org/?probe=4af09bd0c3) | Jun 02, 2023 |
| Valve         | Jupiter                     | [762287e555](https://linux-hardware.org/?probe=762287e555) | Jun 02, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [c9e1edde25](https://linux-hardware.org/?probe=c9e1edde25) | Jun 02, 2023 |
| ASUSTek       | K70IJ                       | [5b877dfec5](https://linux-hardware.org/?probe=5b877dfec5) | Jun 02, 2023 |
| Lenovo        | ThinkPad T530 2392AHG       | [05c41c8464](https://linux-hardware.org/?probe=05c41c8464) | Jun 01, 2023 |
| HUAWEI        | CREM-WXX9                   | [c33f531350](https://linux-hardware.org/?probe=c33f531350) | Jun 01, 2023 |
| Lenovo        | G580 2189                   | [3138d92b76](https://linux-hardware.org/?probe=3138d92b76) | Jun 01, 2023 |
| MSI           | Modern 14 B4MW              | [2c4acbbad3](https://linux-hardware.org/?probe=2c4acbbad3) | May 31, 2023 |
| Acer          | Nitro AN515-54              | [7c031081c5](https://linux-hardware.org/?probe=7c031081c5) | May 31, 2023 |
| ASUSTek       | ROG Strix G712LW_G712LW     | [5e96e1c54e](https://linux-hardware.org/?probe=5e96e1c54e) | May 31, 2023 |
| Chuwi         | HeroBook Air                | [80afc31c99](https://linux-hardware.org/?probe=80afc31c99) | May 30, 2023 |
| Lenovo        | Legion 5 15IMH05 82AU       | [2ac99b8909](https://linux-hardware.org/?probe=2ac99b8909) | May 30, 2023 |
| ASUSTek       | ROG Strix G712LW_G712LW     | [7de5857b40](https://linux-hardware.org/?probe=7de5857b40) | May 29, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [e9830d0123](https://linux-hardware.org/?probe=e9830d0123) | May 29, 2023 |
| Lenovo        | V145-15AST 81MT             | [bf9c082ee0](https://linux-hardware.org/?probe=bf9c082ee0) | May 28, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [dc2b5e538f](https://linux-hardware.org/?probe=dc2b5e538f) | May 27, 2023 |
| HP            | Laptop 15-bs0xx             | [9605e313ac](https://linux-hardware.org/?probe=9605e313ac) | May 27, 2023 |
| HP            | Laptop 15-bs0xx             | [0a8ae92c13](https://linux-hardware.org/?probe=0a8ae92c13) | May 27, 2023 |
| HP            | OMEN by Laptop 15-ce0xx     | [f7f07e78d5](https://linux-hardware.org/?probe=f7f07e78d5) | May 27, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [0ccc456c4e](https://linux-hardware.org/?probe=0ccc456c4e) | May 27, 2023 |
| HP            | 255 G8 Notebook PC          | [9ecbba0aaa](https://linux-hardware.org/?probe=9ecbba0aaa) | May 26, 2023 |
| Toshiba       | TECRA M10                   | [3ce97963e7](https://linux-hardware.org/?probe=3ce97963e7) | May 26, 2023 |
| Toshiba       | TECRA M10                   | [2c574f9677](https://linux-hardware.org/?probe=2c574f9677) | May 26, 2023 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | [89b7c17d00](https://linux-hardware.org/?probe=89b7c17d00) | May 26, 2023 |
| MSI           | Alpha 15 A3DDK              | [722e709153](https://linux-hardware.org/?probe=722e709153) | May 25, 2023 |
| Acer          | TravelMate 5720             | [1066a7a5c5](https://linux-hardware.org/?probe=1066a7a5c5) | May 25, 2023 |
| HP            | Laptop 15s-fq4xxx           | [810c2ac411](https://linux-hardware.org/?probe=810c2ac411) | May 24, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [428a152134](https://linux-hardware.org/?probe=428a152134) | May 23, 2023 |
| Notebook      | W54_55SU1,SUW               | [25b79c51e2](https://linux-hardware.org/?probe=25b79c51e2) | May 23, 2023 |
| Lenovo        | ThinkPad Helix 36986DG      | [77f092da32](https://linux-hardware.org/?probe=77f092da32) | May 23, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [cd94cacffb](https://linux-hardware.org/?probe=cd94cacffb) | May 23, 2023 |
| Acer          | Extensa 5635Z               | [dcff2c30c6](https://linux-hardware.org/?probe=dcff2c30c6) | May 22, 2023 |
| MSI           | Modern 14 B10MW             | [895bca272b](https://linux-hardware.org/?probe=895bca272b) | May 22, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [c720d7e316](https://linux-hardware.org/?probe=c720d7e316) | May 22, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VH0... | [21f52b0bc9](https://linux-hardware.org/?probe=21f52b0bc9) | May 22, 2023 |
| MSI           | Stealth 15M B12UE           | [4051f4b27d](https://linux-hardware.org/?probe=4051f4b27d) | May 22, 2023 |
| Dell          | Inspiron 5770               | [4c16a00ef6](https://linux-hardware.org/?probe=4c16a00ef6) | May 22, 2023 |
| Acer          | Aspire E5-575G              | [d27d5d547e](https://linux-hardware.org/?probe=d27d5d547e) | May 21, 2023 |
| Lenovo        | ThinkPad Helix 36986DG      | [a6b4b230da](https://linux-hardware.org/?probe=a6b4b230da) | May 21, 2023 |
| Lenovo        | G580 2189                   | [8e7dbefb51](https://linux-hardware.org/?probe=8e7dbefb51) | May 21, 2023 |
| Apple         | MacBookPro8,1               | [43c5b0db78](https://linux-hardware.org/?probe=43c5b0db78) | May 20, 2023 |
| Apple         | MacBookAir7,2               | [7687732509](https://linux-hardware.org/?probe=7687732509) | May 20, 2023 |
| HP            | 350 G1                      | [7629c78328](https://linux-hardware.org/?probe=7629c78328) | May 20, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [e464ddd1b6](https://linux-hardware.org/?probe=e464ddd1b6) | May 20, 2023 |
| Chuwi         | GemiBook Pro                | [a8553d6ad6](https://linux-hardware.org/?probe=a8553d6ad6) | May 20, 2023 |
| HP            | 255 G8 Notebook PC          | [c1f679b4d4](https://linux-hardware.org/?probe=c1f679b4d4) | May 20, 2023 |
| HP            | 255 G8 Notebook PC          | [0c163f5c69](https://linux-hardware.org/?probe=0c163f5c69) | May 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [42e009b3c5](https://linux-hardware.org/?probe=42e009b3c5) | May 19, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [7f2ca00e36](https://linux-hardware.org/?probe=7f2ca00e36) | May 18, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [161776168b](https://linux-hardware.org/?probe=161776168b) | May 18, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [d4fc64a451](https://linux-hardware.org/?probe=d4fc64a451) | May 18, 2023 |
| HP            | Laptop 15-db0xxx            | [0c6bb22a24](https://linux-hardware.org/?probe=0c6bb22a24) | May 18, 2023 |
| HP            | Laptop 15-db0xxx            | [e042bb19ba](https://linux-hardware.org/?probe=e042bb19ba) | May 18, 2023 |
| ASUSTek       | TP300LA                     | [e2e6bc0209](https://linux-hardware.org/?probe=e2e6bc0209) | May 17, 2023 |
| MSI           | Stealth 15M B12UE           | [8517139acb](https://linux-hardware.org/?probe=8517139acb) | May 16, 2023 |
| AZW           | GT-R                        | [e156c5b105](https://linux-hardware.org/?probe=e156c5b105) | May 16, 2023 |
| HP            | 630                         | [3527caae6f](https://linux-hardware.org/?probe=3527caae6f) | May 16, 2023 |
| HP            | 630                         | [f34f960671](https://linux-hardware.org/?probe=f34f960671) | May 16, 2023 |
| ASUSTek       | X541UJ                      | [923f447e90](https://linux-hardware.org/?probe=923f447e90) | May 15, 2023 |
| Acer          | TravelMate P215-41-G2       | [84d5e196da](https://linux-hardware.org/?probe=84d5e196da) | May 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [a54f1f4e15](https://linux-hardware.org/?probe=a54f1f4e15) | May 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [c01a4de2f3](https://linux-hardware.org/?probe=c01a4de2f3) | May 15, 2023 |
| HP            | Presario CQ61               | [0967999006](https://linux-hardware.org/?probe=0967999006) | May 14, 2023 |
| Lenovo        | ThinkPad A275 20KCS0FT02    | [d697ec6804](https://linux-hardware.org/?probe=d697ec6804) | May 14, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [8d819952c9](https://linux-hardware.org/?probe=8d819952c9) | May 14, 2023 |
| HP            | 630                         | [40e895a75a](https://linux-hardware.org/?probe=40e895a75a) | May 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [dc1c717240](https://linux-hardware.org/?probe=dc1c717240) | May 13, 2023 |
| ASUSTek       | X551CA                      | [df0583682c](https://linux-hardware.org/?probe=df0583682c) | May 13, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | [9dda4f6b83](https://linux-hardware.org/?probe=9dda4f6b83) | May 13, 2023 |
| Valve         | Jupiter                     | [02275a9849](https://linux-hardware.org/?probe=02275a9849) | May 13, 2023 |
| Apple         | MacBookPro11,4              | [576d66cba7](https://linux-hardware.org/?probe=576d66cba7) | May 12, 2023 |
| HP            | Pavilion Sleekbook 15       | [db2c740451](https://linux-hardware.org/?probe=db2c740451) | May 12, 2023 |
| Valve         | Jupiter                     | [4b2b4bf799](https://linux-hardware.org/?probe=4b2b4bf799) | May 12, 2023 |
| Valve         | Jupiter                     | [e89eb08b8d](https://linux-hardware.org/?probe=e89eb08b8d) | May 11, 2023 |
| Acer          | Aspire 5253G                | [c5cae82cf1](https://linux-hardware.org/?probe=c5cae82cf1) | May 11, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [30d9e5ca7d](https://linux-hardware.org/?probe=30d9e5ca7d) | May 11, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [d3655e5453](https://linux-hardware.org/?probe=d3655e5453) | May 11, 2023 |
| Dell          | XPS 15 9560                 | [62abfc3d83](https://linux-hardware.org/?probe=62abfc3d83) | May 11, 2023 |
| Dell          | XPS 15 9560                 | [4c714fc6ea](https://linux-hardware.org/?probe=4c714fc6ea) | May 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [7d19994aa2](https://linux-hardware.org/?probe=7d19994aa2) | May 11, 2023 |
| Toshiba       | TECRA M10                   | [cf43cf62c7](https://linux-hardware.org/?probe=cf43cf62c7) | May 10, 2023 |
| Toshiba       | TECRA M10                   | [d2be66b23b](https://linux-hardware.org/?probe=d2be66b23b) | May 10, 2023 |
| Samsung       | X420/X520                   | [aec20f5b38](https://linux-hardware.org/?probe=aec20f5b38) | May 10, 2023 |
| Razer         | Blade 14 (2022) - RZ09-0... | [2e58ce6bd7](https://linux-hardware.org/?probe=2e58ce6bd7) | May 10, 2023 |
| HP            | Compaq Mini CQ10-500        | [4b9087625d](https://linux-hardware.org/?probe=4b9087625d) | May 09, 2023 |
| HP            | 630                         | [69a6753dab](https://linux-hardware.org/?probe=69a6753dab) | May 09, 2023 |
| HP            | 630                         | [d729f66fa2](https://linux-hardware.org/?probe=d729f66fa2) | May 09, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [7b102d2ecc](https://linux-hardware.org/?probe=7b102d2ecc) | May 08, 2023 |
| TerraQue      | W65_W67RB                   | [842f203ec5](https://linux-hardware.org/?probe=842f203ec5) | May 07, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [acd4c4af90](https://linux-hardware.org/?probe=acd4c4af90) | May 07, 2023 |
| eMachines     | eME728                      | [031e24359e](https://linux-hardware.org/?probe=031e24359e) | May 06, 2023 |
| HP            | 630                         | [20d6860e43](https://linux-hardware.org/?probe=20d6860e43) | May 05, 2023 |
| HP            | 630                         | [57d5ffbec9](https://linux-hardware.org/?probe=57d5ffbec9) | May 05, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [6069763b68](https://linux-hardware.org/?probe=6069763b68) | May 05, 2023 |
| Acer          | Nitro AN515-55              | [6264cfc1e6](https://linux-hardware.org/?probe=6264cfc1e6) | May 04, 2023 |
| Gigabyte      | G5 KD                       | [15f1eb707f](https://linux-hardware.org/?probe=15f1eb707f) | May 04, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Spain/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 405       | 10.96%  |
| Ubuntu 22.04       | 270       | 7.31%   |
| Ubuntu 18.04       | 256       | 6.93%   |
| Debian 11          | 141       | 3.82%   |
| OpenMandriva 4.2   | 87        | 2.36%   |
| Zorin 16           | 86        | 2.33%   |
| KDE neon 20.04     | 63        | 1.71%   |
| OpenMandriva 4.3   | 62        | 1.68%   |
| Debian 12          | 53        | 1.43%   |
| Arch Rolling       | 53        | 1.43%   |
| Fedora 38          | 51        | 1.38%   |
| Linux Mint 20.3    | 47        | 1.27%   |
| Pop!_OS 22.04      | 44        | 1.19%   |
| Manjaro            | 44        | 1.19%   |
| Linux Mint 21.1    | 41        | 1.11%   |
| Arch               | 41        | 1.11%   |
| Xubuntu 20.04      | 39        | 1.06%   |
| Ubuntu 20.10       | 39        | 1.06%   |
| OpenMandriva 23.01 | 39        | 1.06%   |
| Linux Mint 19.3    | 37        | 1%      |
| Debian 10          | 36        | 0.97%   |
| Ubuntu 19.10       | 34        | 0.92%   |
| Ubuntu 21.04       | 32        | 0.87%   |
| Ubuntu 19.04       | 32        | 0.87%   |
| Linux Mint 20.1    | 32        | 0.87%   |
| Kubuntu 20.04      | 32        | 0.87%   |
| Fedora 36          | 32        | 0.87%   |
| ArcoLinux Rolling  | 32        | 0.87%   |
| Linux Mint 21.2    | 31        | 0.84%   |
| Fedora 37          | 31        | 0.84%   |
| Ubuntu 22.10       | 30        | 0.81%   |
| Ubuntu 21.10       | 30        | 0.81%   |
| Linux Mint 20      | 30        | 0.81%   |
| Xubuntu 18.04      | 28        | 0.76%   |
| Zorin 15           | 27        | 0.73%   |
| Linux Mint 21      | 27        | 0.73%   |
| Linux Mint 20.2    | 27        | 0.73%   |
| OpenMandriva 23.08 | 26        | 0.7%    |
| Ubuntu 23.04       | 25        | 0.68%   |
| OpenMandriva 23.03 | 25        | 0.68%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1158      | 33.16%  |
| Linux Mint    | 288       | 8.25%   |
| Debian        | 256       | 7.33%   |
| OpenMandriva  | 248       | 7.1%    |
| Fedora        | 218       | 6.24%   |
| Zorin         | 120       | 3.44%   |
| Manjaro       | 111       | 3.18%   |
| Endless       | 105       | 3.01%   |
| Pop!_OS       | 97        | 2.78%   |
| Arch          | 93        | 2.66%   |
| Kubuntu       | 85        | 2.43%   |
| Xubuntu       | 83        | 2.38%   |
| KDE neon      | 83        | 2.38%   |
| ROSA          | 57        | 1.63%   |
| SteamOS       | 38        | 1.09%   |
| ArcoLinux     | 38        | 1.09%   |
| Ubuntu MATE   | 36        | 1.03%   |
| Kali          | 35        | 1%      |
| Elementary    | 34        | 0.97%   |
| openSUSE      | 31        | 0.89%   |
| Ubuntu Unity  | 23        | 0.66%   |
| Gentoo        | 21        | 0.6%    |
| Lubuntu       | 19        | 0.54%   |
| EndeavourOS   | 17        | 0.49%   |
| LMDE          | 16        | 0.46%   |
| BlackPanther  | 16        | 0.46%   |
| Nobara        | 15        | 0.43%   |
| Parrot        | 14        | 0.4%    |
| MX            | 10        | 0.29%   |
| Ubuntu Budgie | 9         | 0.26%   |
| Clear Linux   | 9         | 0.26%   |
| Xero          | 6         | 0.17%   |
| Sparky        | 5         | 0.14%   |
| Garuda Linux  | 5         | 0.14%   |
| Deepin        | 5         | 0.14%   |
| CentOS        | 5         | 0.14%   |
| BunsenLabs    | 5         | 0.14%   |
| Ubuntu Studio | 4         | 0.11%   |
| RHEL          | 4         | 0.11%   |
| Artix         | 4         | 0.11%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 85        | 2.1%    |
| 5.16.7-desktop-1omv4003  | 61        | 1.51%   |
| 5.4.0-42-generic         | 48        | 1.19%   |
| 6.1.1-desktop-1omv2290   | 36        | 0.89%   |
| 5.15.0-56-generic        | 36        | 0.89%   |
| 5.10.0-8-amd64           | 34        | 0.84%   |
| 5.4.0-58-generic         | 33        | 0.82%   |
| 5.15.0-52-generic        | 32        | 0.79%   |
| 5.3.0-28-generic         | 31        | 0.77%   |
| 5.4.0-54-generic         | 27        | 0.67%   |
| 5.4.0-52-generic         | 26        | 0.64%   |
| 5.4.0-26-generic         | 26        | 0.64%   |
| 5.10.0-18-amd64          | 26        | 0.64%   |
| 6.2.6-desktop-1omv2390   | 25        | 0.62%   |
| 5.15.0-58-generic        | 24        | 0.59%   |
| 5.15.0-53-generic        | 22        | 0.54%   |
| 5.11.0-27-generic        | 22        | 0.54%   |
| 5.0.0-37-generic         | 22        | 0.54%   |
| 6.5.0-14-generic         | 21        | 0.52%   |
| 6.4.11-desktop-1omv2390  | 21        | 0.52%   |
| 5.3.0-46-generic         | 21        | 0.52%   |
| 5.3.0-40-generic         | 21        | 0.52%   |
| 5.15.0-48-generic        | 21        | 0.52%   |
| 5.4.0-65-generic         | 20        | 0.5%    |
| 5.4.0-48-generic         | 20        | 0.5%    |
| 5.19.0-35-generic        | 19        | 0.47%   |
| 5.13.0-valve36-1-neptune | 19        | 0.47%   |
| 5.11.0-43-generic        | 19        | 0.47%   |
| 5.11.0-41-generic        | 19        | 0.47%   |
| 6.2.0-37-generic         | 18        | 0.45%   |
| 5.4.0-72-generic         | 18        | 0.45%   |
| 5.4.0-40-generic         | 18        | 0.45%   |
| 5.15.0-47-generic        | 18        | 0.45%   |
| 5.0.0-32-generic         | 18        | 0.45%   |
| 6.2.0-26-generic         | 17        | 0.42%   |
| 6.1.0-13-amd64           | 17        | 0.42%   |
| 5.8.0-44-generic         | 17        | 0.42%   |
| 5.4.0-19-generic         | 16        | 0.4%    |
| 5.3.0-45-generic         | 16        | 0.4%    |
| 5.15.0-91-generic        | 16        | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 549       | 14.36%  |
| 5.15.0  | 372       | 9.73%   |
| 4.15.0  | 205       | 5.36%   |
| 5.11.0  | 170       | 4.45%   |
| 5.10.0  | 165       | 4.31%   |
| 5.3.0   | 153       | 4%      |
| 5.8.0   | 151       | 3.95%   |
| 5.13.0  | 147       | 3.84%   |
| 5.19.0  | 124       | 3.24%   |
| 6.2.0   | 120       | 3.14%   |
| 5.0.0   | 109       | 2.85%   |
| 5.10.14 | 86        | 2.25%   |
| 6.1.0   | 81        | 2.12%   |
| 4.18.0  | 71        | 1.86%   |
| 5.16.7  | 65        | 1.7%    |
| 6.5.0   | 46        | 1.2%    |
| 6.1.1   | 42        | 1.1%    |
| 4.19.0  | 42        | 1.1%    |
| 6.2.6   | 39        | 1.02%   |
| 6.4.11  | 24        | 0.63%   |
| 5.14.0  | 19        | 0.5%    |
| 6.0.0   | 16        | 0.42%   |
| 4.9.60  | 15        | 0.39%   |
| 6.6.2   | 13        | 0.34%   |
| 6.5.5   | 13        | 0.34%   |
| 6.0.12  | 13        | 0.34%   |
| 5.18.0  | 13        | 0.34%   |
| 4.4.0   | 13        | 0.34%   |
| 4.18.16 | 13        | 0.34%   |
| 6.1.11  | 11        | 0.29%   |
| 6.4.6   | 10        | 0.26%   |
| 5.9.16  | 10        | 0.26%   |
| 5.17.5  | 10        | 0.26%   |
| 6.6.6   | 9         | 0.24%   |
| 6.6.1   | 9         | 0.24%   |
| 6.6.8   | 8         | 0.21%   |
| 6.2.9   | 8         | 0.21%   |
| 6.1.12  | 8         | 0.21%   |
| 5.16.0  | 8         | 0.21%   |
| 6.5.6   | 7         | 0.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 582       | 15.48%  |
| 5.15    | 431       | 11.46%  |
| 5.10    | 291       | 7.74%   |
| 4.15    | 205       | 5.45%   |
| 6.2     | 201       | 5.35%   |
| 5.11    | 198       | 5.27%   |
| 6.1     | 189       | 5.03%   |
| 5.8     | 177       | 4.71%   |
| 5.3     | 168       | 4.47%   |
| 5.13    | 167       | 4.44%   |
| 5.19    | 158       | 4.2%    |
| 5.0     | 111       | 2.95%   |
| 5.16    | 102       | 2.71%   |
| 6.5     | 99        | 2.63%   |
| 4.18    | 84        | 2.23%   |
| 6.4     | 73        | 1.94%   |
| 6.6     | 65        | 1.73%   |
| 6.0     | 59        | 1.57%   |
| 4.19    | 50        | 1.33%   |
| 5.14    | 48        | 1.28%   |
| 4.9     | 39        | 1.04%   |
| 5.18    | 37        | 0.98%   |
| 6.3     | 31        | 0.82%   |
| 5.17    | 31        | 0.82%   |
| 5.9     | 29        | 0.77%   |
| 5.6     | 25        | 0.66%   |
| 5.7     | 24        | 0.64%   |
| 5.12    | 23        | 0.61%   |
| 5.5     | 14        | 0.37%   |
| 4.4     | 14        | 0.37%   |
| 6.7     | 6         | 0.16%   |
| 4.16    | 5         | 0.13%   |
| 5.2     | 4         | 0.11%   |
| 4.1     | 4         | 0.11%   |
| 3.10    | 4         | 0.11%   |
| 5.1     | 3         | 0.08%   |
| 4.20    | 3         | 0.08%   |
| 4.13    | 3         | 0.08%   |
| 4.8     | 1         | 0.03%   |
| 4.17    | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 3241      | 96.2%   |
| i686   | 128       | 3.8%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 1597      | 45.32%  |
| KDE5             | 631       | 17.91%  |
| Unknown          | 343       | 9.73%   |
| XFCE             | 274       | 7.78%   |
| X-Cinnamon       | 227       | 6.44%   |
| MATE             | 96        | 2.72%   |
| KDE              | 78        | 2.21%   |
| LXQt             | 38        | 1.08%   |
| Cinnamon         | 34        | 0.96%   |
| Pantheon         | 33        | 0.94%   |
| i3               | 24        | 0.68%   |
| Unity            | 22        | 0.62%   |
| KDE4             | 22        | 0.62%   |
| Budgie           | 17        | 0.48%   |
| LXDE             | 16        | 0.45%   |
| GNOME Flashback  | 13        | 0.37%   |
| Deepin           | 10        | 0.28%   |
| openbox          | 6         | 0.17%   |
| GNOME Classic    | 5         | 0.14%   |
| bspwm            | 5         | 0.14%   |
| lightdm-xsession | 4         | 0.11%   |
| Endless:GNOME    | 4         | 0.11%   |
| Dwm              | 4         | 0.11%   |
| sway             | 2         | 0.06%   |
| LeftWM           | 2         | 0.06%   |
| icewm            | 2         | 0.06%   |
| Hyprland         | 2         | 0.06%   |
| Cutefish         | 2         | 0.06%   |
| BunsenLabs       | 2         | 0.06%   |
| awesome          | 2         | 0.06%   |
| xmonad           | 1         | 0.03%   |
| trinity          | 1         | 0.03%   |
| river            | 1         | 0.03%   |
| qtile            | 1         | 0.03%   |
| Lubuntu          | 1         | 0.03%   |
| i3-with-shmlog   | 1         | 0.03%   |
| enlightenment    | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 2566      | 73.5%   |
| Wayland | 702       | 20.11%  |
| Unknown | 197       | 5.64%   |
| Tty     | 26        | 0.74%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1657      | 47.29%  |
| SDDM    | 530       | 15.13%  |
| GDM3    | 459       | 13.1%   |
| GDM     | 404       | 11.53%  |
| LightDM | 324       | 9.25%   |
| TDM     | 90        | 2.57%   |
| KDM     | 24        | 0.68%   |
| XDM     | 7         | 0.2%    |
| SLiM    | 3         | 0.09%   |
| Ly      | 3         | 0.09%   |
| SLIMSKI | 1         | 0.03%   |
| LY-DM   | 1         | 0.03%   |
| LXDM    | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang           | Notebooks | Percent |
|----------------|-----------|---------|
| es_ES          | 2003      | 57.77%  |
| en_US          | 693       | 19.99%  |
| Unknown        | 346       | 9.98%   |
| ca_ES          | 131       | 3.78%   |
| en_GB          | 92        | 2.65%   |
| C              | 37        | 1.07%   |
| de_DE          | 24        | 0.69%   |
| gl_ES          | 14        | 0.4%    |
| eu_ES          | 14        | 0.4%    |
| ru_RU          | 11        | 0.32%   |
| it_IT          | 11        | 0.32%   |
| fr_FR          | 11        | 0.32%   |
| an_ES          | 9         | 0.26%   |
| es_AR          | 7         | 0.2%    |
| pt_BR          | 6         | 0.17%   |
| es_MX          | 6         | 0.17%   |
| en_AG          | 5         | 0.14%   |
| ca_AD          | 5         | 0.14%   |
| POSIX          | 3         | 0.09%   |
| pl_PL          | 3         | 0.09%   |
| fr_BE          | 3         | 0.09%   |
| en_IE          | 3         | 0.09%   |
| nl_NL          | 2         | 0.06%   |
| es_US          | 2         | 0.06%   |
| es_BO          | 2         | 0.06%   |
| en_CA          | 2         | 0.06%   |
| de_CH          | 2         | 0.06%   |
| de_AT          | 2         | 0.06%   |
| ca_ES@valencia | 2         | 0.06%   |
| uk_UA          | 1         | 0.03%   |
| sp_SP          | 1         | 0.03%   |
| ru_UA          | 1         | 0.03%   |
| ro_RO          | 1         | 0.03%   |
| nb_NO          | 1         | 0.03%   |
| fr_CH          | 1         | 0.03%   |
| et_EE          | 1         | 0.03%   |
| es_VE          | 1         | 0.03%   |
| es_PE          | 1         | 0.03%   |
| eo             | 1         | 0.03%   |
| en_NZ          | 1         | 0.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 1884      | 54.69%  |
| BIOS | 1561      | 45.31%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 2588      | 74.56%  |
| Btrfs   | 317       | 9.13%   |
| Overlay | 246       | 7.09%   |
| Tmpfs   | 122       | 3.51%   |
| Unknown | 111       | 3.2%    |
| Xfs     | 46        | 1.33%   |
| Zfs     | 21        | 0.61%   |
| Ext2    | 10        | 0.29%   |
| Ext3    | 4         | 0.12%   |
| Aufs    | 3         | 0.09%   |
| Jfs     | 2         | 0.06%   |
| F2fs    | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1736      | 50.28%  |
| GPT     | 1375      | 39.82%  |
| MBR     | 342       | 9.9%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3037      | 88.46%  |
| Yes       | 396       | 11.54%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2389      | 69.69%  |
| Yes       | 1039      | 30.31%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 623       | 18.5%   |
| Lenovo              | 584       | 17.34%  |
| ASUSTek Computer    | 499       | 14.82%  |
| Acer                | 322       | 9.56%   |
| Dell                | 268       | 7.96%   |
| MSI                 | 222       | 6.59%   |
| Toshiba             | 126       | 3.74%   |
| Apple               | 89        | 2.64%   |
| HUAWEI              | 57        | 1.69%   |
| Sony                | 49        | 1.45%   |
| Packard Bell        | 39        | 1.16%   |
| Valve               | 38        | 1.13%   |
| Chuwi               | 38        | 1.13%   |
| Unknown             | 37        | 1.1%    |
| Samsung Electronics | 35        | 1.04%   |
| Notebook            | 35        | 1.04%   |
| SLIMBOOK            | 30        | 0.89%   |
| LG Electronics      | 22        | 0.65%   |
| Medion              | 18        | 0.53%   |
| Fujitsu             | 15        | 0.45%   |
| Timi                | 13        | 0.39%   |
| Gigabyte Technology | 13        | 0.39%   |
| Fujitsu Siemens     | 13        | 0.39%   |
| eMachines           | 11        | 0.33%   |
| Teclast             | 10        | 0.3%    |
| Dynabook            | 10        | 0.3%    |
| Clevo               | 10        | 0.3%    |
| Intel               | 8         | 0.24%   |
| Google              | 6         | 0.18%   |
| ALURIN              | 6         | 0.18%   |
| VANT                | 4         | 0.12%   |
| TUXEDO              | 4         | 0.12%   |
| Razer               | 4         | 0.12%   |
| Qilive              | 4         | 0.12%   |
| PC Specialist       | 4         | 0.12%   |
| HONOR               | 4         | 0.12%   |
| AZW                 | 4         | 0.12%   |
| Alienware           | 4         | 0.12%   |
| Thomson             | 3         | 0.09%   |
| Primux Tech         | 3         | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 59        | 1.75%   |
| Valve Jupiter                              | 36        | 1.07%   |
| HP Pavilion g6                             | 24        | 0.71%   |
| HP Pavilion dv6                            | 22        | 0.65%   |
| HP Notebook                                | 22        | 0.65%   |
| ASUS ZenBook UX431DA_UM431DA               | 19        | 0.56%   |
| Lenovo IdeaPad 330-15IKB 81DE              | 17        | 0.5%    |
| ASUS VivoBook 15_ASUS Laptop X540MA_R540MA | 16        | 0.48%   |
| HP G62                                     | 13        | 0.39%   |
| Lenovo IdeaPad 3 15ITL6 82H8               | 12        | 0.36%   |
| HUAWEI BOHK-WAX9X                          | 12        | 0.36%   |
| HP Laptop 15-da0xxx                        | 12        | 0.36%   |
| Chuwi GemiBook Pro                         | 11        | 0.33%   |
| HP Pavilion 15                             | 10        | 0.3%    |
| Dell XPS 13 7390                           | 10        | 0.3%    |
| HP Laptop 15s-fq1xxx                       | 9         | 0.27%   |
| HP Laptop 15s-eq1xxx                       | 9         | 0.27%   |
| HP Laptop 15-bs0xx                         | 9         | 0.27%   |
| Acer Aspire 5750G                          | 9         | 0.27%   |
| MSI Prestige 15 A11SCS                     | 8         | 0.24%   |
| MSI Prestige 15 A10SC                      | 8         | 0.24%   |
| MSI Modern 14 A10M                         | 8         | 0.24%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2        | 8         | 0.24%   |
| HP Victus by Laptop 16-e0xxx               | 8         | 0.24%   |
| HP ProBook 450 G8 Notebook PC              | 8         | 0.24%   |
| HP Laptop 15-bw0xx                         | 8         | 0.24%   |
| HP EliteBook 840 G5                        | 8         | 0.24%   |
| Dell XPS 15 7590                           | 8         | 0.24%   |
| ASUS X555LAB                               | 8         | 0.24%   |
| ASUS X550VX                                | 8         | 0.24%   |
| ASUS X540NA                                | 8         | 0.24%   |
| ASUS VivoBook 15_ASUS Laptop X540BA        | 8         | 0.24%   |
| Apple MacBookPro8,1                        | 8         | 0.24%   |
| Acer TravelMate 5720                       | 8         | 0.24%   |
| Lenovo Z50-70 20354                        | 7         | 0.21%   |
| Lenovo Y520-15IKBN 80WK                    | 7         | 0.21%   |
| Lenovo Legion 5 15ACH6H 82JU               | 7         | 0.21%   |
| Lenovo IdeaPad S145-15AST 81N3             | 7         | 0.21%   |
| Lenovo IdeaPad 3 15ADA05 81W1              | 7         | 0.21%   |
| Lenovo G50-70 20351                        | 7         | 0.21%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 228       | 6.77%   |
| Acer Aspire           | 225       | 6.68%   |
| Lenovo IdeaPad        | 164       | 4.87%   |
| HP Pavilion           | 146       | 4.33%   |
| Dell Latitude         | 107       | 3.18%   |
| HP Laptop             | 102       | 3.03%   |
| ASUS VivoBook         | 101       | 3%      |
| Toshiba Satellite     | 95        | 2.82%   |
| HP EliteBook          | 68        | 2.02%   |
| Dell XPS              | 65        | 1.93%   |
| Unknown               | 59        | 1.75%   |
| ASUS ZenBook          | 47        | 1.4%    |
| HP ProBook            | 46        | 1.37%   |
| Dell Inspiron         | 45        | 1.34%   |
| ASUS ROG              | 42        | 1.25%   |
| MSI Prestige          | 41        | 1.22%   |
| HP Compaq             | 40        | 1.19%   |
| Valve Jupiter         | 36        | 1.07%   |
| MSI Modern            | 36        | 1.07%   |
| Packard Bell EasyNote | 35        | 1.04%   |
| HP 250                | 33        | 0.98%   |
| Lenovo Legion         | 32        | 0.95%   |
| Acer TravelMate       | 32        | 0.95%   |
| ASUS ASUS             | 25        | 0.74%   |
| HP OMEN               | 24        | 0.71%   |
| HP Notebook           | 22        | 0.65%   |
| Acer Extensa          | 22        | 0.65%   |
| Lenovo ThinkBook      | 20        | 0.59%   |
| HP Victus             | 17        | 0.5%    |
| HP ENVY               | 17        | 0.5%    |
| Chuwi GemiBook        | 17        | 0.5%    |
| ASUS TUF              | 17        | 0.5%    |
| Lenovo Yoga           | 16        | 0.48%   |
| Fujitsu LIFEBOOK      | 14        | 0.42%   |
| Dell Vostro           | 14        | 0.42%   |
| Dell Precision        | 14        | 0.42%   |
| Apple MacBookPro11    | 14        | 0.42%   |
| Toshiba PORTEGE       | 13        | 0.39%   |
| HP G62                | 13        | 0.39%   |
| HP 255                | 13        | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 323       | 9.59%   |
| 2021    | 316       | 9.38%   |
| 2018    | 313       | 9.29%   |
| 2020    | 306       | 9.09%   |
| 2014    | 218       | 6.47%   |
| 2011    | 193       | 5.73%   |
| 2015    | 191       | 5.67%   |
| 2017    | 190       | 5.64%   |
| 2022    | 175       | 5.2%    |
| 2013    | 170       | 5.05%   |
| 2010    | 167       | 4.96%   |
| 2012    | 162       | 4.81%   |
| 2008    | 151       | 4.48%   |
| 2009    | 135       | 4.01%   |
| 2016    | 130       | 3.86%   |
| 2007    | 100       | 2.97%   |
| 2023    | 71        | 2.11%   |
| 2006    | 33        | 0.98%   |
| 2005    | 10        | 0.3%    |
| 2004    | 5         | 0.15%   |
| Unknown | 4         | 0.12%   |
| 2003    | 3         | 0.09%   |
| 2002    | 1         | 0.03%   |
| 2001    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 3368      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 3076      | 90.68%  |
| Enabled  | 316       | 9.32%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3359      | 99.73%  |
| Yes  | 9         | 0.27%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 893       | 26.2%   |
| 3.01-4.0    | 717       | 21.03%  |
| 8.01-16.0   | 664       | 19.48%  |
| 16.01-24.0  | 598       | 17.54%  |
| 32.01-64.0  | 236       | 6.92%   |
| 1.01-2.0    | 146       | 4.28%   |
| 2.01-3.0    | 57        | 1.67%   |
| 0.51-1.0    | 50        | 1.47%   |
| 24.01-32.0  | 26        | 0.76%   |
| 64.01-256.0 | 20        | 0.59%   |
| 0.01-0.5    | 2         | 0.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1322      | 35.33%  |
| 2.01-3.0   | 991       | 26.48%  |
| 4.01-8.0   | 516       | 13.79%  |
| 3.01-4.0   | 469       | 12.53%  |
| 0.51-1.0   | 264       | 7.06%   |
| 8.01-16.0  | 132       | 3.53%   |
| 0.01-0.5   | 32        | 0.86%   |
| 16.01-24.0 | 11        | 0.29%   |
| 24.01-32.0 | 3         | 0.08%   |
| 32.01-64.0 | 2         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2595      | 75.52%  |
| 2      | 726       | 21.13%  |
| 3      | 77        | 2.24%   |
| 0      | 26        | 0.76%   |
| 4      | 9         | 0.26%   |
| 5      | 3         | 0.09%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2263      | 66.85%  |
| Yes       | 1122      | 33.15%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2652      | 78.23%  |
| No        | 738       | 21.77%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3305      | 98.1%   |
| No        | 64        | 1.9%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2557      | 75.32%  |
| No        | 838       | 24.68%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Spain   | 3368      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Madrid                     | 582       | 15.8%   |
| Barcelona                  | 404       | 10.97%  |
| Seville                    | 128       | 3.48%   |
| Valencia                   | 122       | 3.31%   |
| Zaragoza                   | 63        | 1.71%   |
| Granada                    | 57        | 1.55%   |
| Málaga                    | 51        | 1.38%   |
| Palma                      | 44        | 1.19%   |
| Alcobendas                 | 44        | 1.19%   |
| Vigo                       | 39        | 1.06%   |
| Valladolid                 | 37        | 1%      |
| Alicante                   | 34        | 0.92%   |
| Sabadell                   | 33        | 0.9%    |
| Bilbao                     | 30        | 0.81%   |
| Pamplona                   | 28        | 0.76%   |
| Córdoba                   | 27        | 0.73%   |
| Las Palmas de Gran Canaria | 26        | 0.71%   |
| Murcia                     | 25        | 0.68%   |
| A Coruña                  | 25        | 0.68%   |
| Oviedo                     | 24        | 0.65%   |
| Alcalá de Henares         | 24        | 0.65%   |
| Santiago de Compostela     | 23        | 0.62%   |
| Donostia / San Sebastian   | 23        | 0.62%   |
| Burgos                     | 19        | 0.52%   |
| León                      | 17        | 0.46%   |
| Vitoria-Gasteiz            | 16        | 0.43%   |
| Mostoles                   | 16        | 0.43%   |
| Gijón                     | 16        | 0.43%   |
| Barakaldo                  | 16        | 0.43%   |
| Salamanca                  | 15        | 0.41%   |
| Reus                       | 15        | 0.41%   |
| Getxo                      | 15        | 0.41%   |
| Jerez de la Frontera       | 14        | 0.38%   |
| Girona                     | 14        | 0.38%   |
| Almería                   | 14        | 0.38%   |
| Santander                  | 13        | 0.35%   |
| Santa Cruz de Tenerife     | 13        | 0.35%   |
| Cartagena                  | 13        | 0.35%   |
| Tres Cantos                | 12        | 0.33%   |
| Tarragona                  | 12        | 0.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 579       | 716    | 14.1%   |
| WDC                         | 415       | 525    | 10.11%  |
| Kingston                    | 401       | 510    | 9.77%   |
| Seagate                     | 399       | 474    | 9.72%   |
| Toshiba                     | 320       | 412    | 7.8%    |
| Sandisk                     | 286       | 376    | 6.97%   |
| Unknown                     | 207       | 282    | 5.04%   |
| SK hynix                    | 189       | 227    | 4.6%    |
| Micron Technology           | 160       | 207    | 3.9%    |
| Intel                       | 143       | 199    | 3.48%   |
| Hitachi                     | 137       | 162    | 3.34%   |
| Crucial                     | 121       | 150    | 2.95%   |
| HGST                        | 113       | 136    | 2.75%   |
| China                       | 44        | 63     | 1.07%   |
| KIOXIA                      | 41        | 53     | 1%      |
| Apple                       | 41        | 52     | 1%      |
| Phison Electronics          | 38        | 42     | 0.93%   |
| Phison                      | 33        | 36     | 0.8%    |
| Fujitsu                     | 33        | 37     | 0.8%    |
| Kingston Technology Company | 32        | 46     | 0.78%   |
| Netac                       | 22        | 35     | 0.54%   |
| Micron/Crucial Technology   | 20        | 23     | 0.49%   |
| LITEON                      | 20        | 21     | 0.49%   |
| KingSpec                    | 15        | 21     | 0.37%   |
| JMicron Technology          | 14        | 14     | 0.34%   |
| A-DATA Technology           | 14        | 16     | 0.34%   |
| Unknown                     | 12        | 13     | 0.29%   |
| Teclast                     | 10        | 11     | 0.24%   |
| Silicon Motion              | 10        | 11     | 0.24%   |
| FORESEE                     | 10        | 16     | 0.24%   |
| Transcend                   | 9         | 15     | 0.22%   |
| Emtec                       | 9         | 10     | 0.22%   |
| PNY                         | 8         | 14     | 0.19%   |
| OCZ                         | 8         | 9      | 0.19%   |
| USB30                       | 7         | 8      | 0.17%   |
| LITEONIT                    | 7         | 8      | 0.17%   |
| Patriot                     | 6         | 8      | 0.15%   |
| KIOXIA-EXCERIA              | 6         | 9      | 0.15%   |
| KingDian                    | 6         | 6      | 0.15%   |
| Intenso                     | 6         | 13     | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                    | 137       | 3.23%   |
| Kingston SA400S37480G 480GB SSD                    | 59        | 1.39%   |
| Seagate ST500LT012-1DG142 500GB                    | 50        | 1.18%   |
| Unknown MMC Card  64GB                             | 40        | 0.94%   |
| Unknown MMC Card  32GB                             | 40        | 0.94%   |
| Toshiba MQ01ABD100 1TB                             | 38        | 0.9%    |
| HGST HTS721010A9E630 1TB                           | 38        | 0.9%    |
| Seagate ST1000LM035-1RK172 1TB                     | 37        | 0.87%   |
| Seagate ST9500325AS 500GB                          | 35        | 0.83%   |
| Toshiba MQ01ABF050 500GB                           | 34        | 0.8%    |
| SK hynix NVMe SSD Drive 512GB                      | 34        | 0.8%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 33        | 0.78%   |
| Samsung NVMe SSD Drive 512GB                       | 31        | 0.73%   |
| Toshiba MQ04ABF100 1TB                             | 30        | 0.71%   |
| SanDisk NVMe SSD Drive 512GB                       | 30        | 0.71%   |
| Unknown MMC Card  128GB                            | 26        | 0.61%   |
| SanDisk SSD PLUS 480GB                             | 24        | 0.57%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 24        | 0.57%   |
| Kingston SA400S37120G 120GB SSD                    | 24        | 0.57%   |
| Samsung SSD 850 EVO 250GB                          | 23        | 0.54%   |
| Kingston SUV400S37240G 240GB SSD                   | 23        | 0.54%   |
| HGST HTS545050A7E680 500GB                         | 23        | 0.54%   |
| Toshiba MQ01ABD050 500GB                           | 22        | 0.52%   |
| Samsung SSD 860 EVO 500GB                          | 22        | 0.52%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB             | 22        | 0.52%   |
| Intel NVMe SSD Drive 512GB                         | 21        | 0.5%    |
| WDC WD10JPVX-22JC3T0 1TB                           | 20        | 0.47%   |
| Kingston RBUSC180DS37256GJ 256GB SSD               | 20        | 0.47%   |
| Phison PS5013 E13 NVMe Controller 256GB            | 19        | 0.45%   |
| HGST HTS541010A9E680 1TB                           | 19        | 0.45%   |
| Seagate Expansion 1TB                              | 18        | 0.42%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB   | 18        | 0.42%   |
| SanDisk NVMe SSD Drive 256GB                       | 18        | 0.42%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB               | 17        | 0.4%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 17        | 0.4%    |
| Kingston SA400S37960G 960GB SSD                    | 17        | 0.4%    |
| Crucial CT500MX500SSD1 500GB                       | 17        | 0.4%    |
| Samsung SSD 850 EVO 500GB                          | 16        | 0.38%   |
| Seagate ST1000LM049-2GH172 1TB                     | 15        | 0.35%   |
| Intel SSDPEKNU512GZ 512GB                          | 15        | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 392       | 466    | 32.24%  |
| WDC                 | 262       | 321    | 21.55%  |
| Toshiba             | 211       | 261    | 17.35%  |
| Hitachi             | 137       | 162    | 11.27%  |
| HGST                | 113       | 136    | 9.29%   |
| Samsung Electronics | 34        | 35     | 2.8%    |
| Fujitsu             | 33        | 37     | 2.71%   |
| Unknown             | 10        | 14     | 0.82%   |
| JMicron Technology  | 7         | 7      | 0.58%   |
| Apple               | 5         | 5      | 0.41%   |
| SSK                 | 2         | 2      | 0.16%   |
| LaCie               | 2         | 2      | 0.16%   |
| USB3.0              | 1         | 1      | 0.08%   |
| USB                 | 1         | 1      | 0.08%   |
| TO Exter            | 1         | 2      | 0.08%   |
| SABRENT             | 1         | 2      | 0.08%   |
| OEM                 | 1         | 1      | 0.08%   |
| Maxone              | 1         | 1      | 0.08%   |
| Inateck             | 1         | 1      | 0.08%   |
| IBM                 | 1         | 1      | 0.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 343       | 437    | 26.32%  |
| Samsung Electronics | 212       | 265    | 16.27%  |
| SanDisk             | 137       | 173    | 10.51%  |
| Crucial             | 109       | 135    | 8.37%   |
| Toshiba             | 52        | 72     | 3.99%   |
| WDC                 | 50        | 66     | 3.84%   |
| China               | 44        | 63     | 3.38%   |
| SK hynix            | 40        | 44     | 3.07%   |
| Micron Technology   | 38        | 50     | 2.92%   |
| Intel               | 24        | 38     | 1.84%   |
| Apple               | 22        | 25     | 1.69%   |
| Netac               | 21        | 34     | 1.61%   |
| LITEON              | 18        | 18     | 1.38%   |
| KingSpec            | 15        | 21     | 1.15%   |
| A-DATA Technology   | 11        | 13     | 0.84%   |
| Teclast             | 10        | 11     | 0.77%   |
| FORESEE             | 10        | 16     | 0.77%   |
| Transcend           | 8         | 14     | 0.61%   |
| OCZ                 | 8         | 9      | 0.61%   |
| Emtec               | 8         | 8      | 0.61%   |
| USB30               | 7         | 8      | 0.54%   |
| LITEONIT            | 7         | 8      | 0.54%   |
| PNY                 | 6         | 12     | 0.46%   |
| Patriot             | 5         | 7      | 0.38%   |
| KingDian            | 5         | 5      | 0.38%   |
| Intenso             | 5         | 11     | 0.38%   |
| KIOXIA-EXCERIA      | 4         | 7      | 0.31%   |
| Dogfish             | 4         | 4      | 0.31%   |
| Corsair             | 4         | 5      | 0.31%   |
| ASMT                | 4         | 4      | 0.31%   |
| Unknown             | 4         | 4      | 0.31%   |
| USB3.0              | 3         | 3      | 0.23%   |
| USB                 | 3         | 3      | 0.23%   |
| Unknown             | 3         | 3      | 0.23%   |
| TCSUNBOW            | 3         | 4      | 0.23%   |
| Phison              | 3         | 4      | 0.23%   |
| Lexar               | 3         | 3      | 0.23%   |
| Drevo               | 3         | 3      | 0.23%   |
| BAITITON            | 3         | 9      | 0.23%   |
| Verbatim            | 2         | 3      | 0.15%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 1272      | 1710   | 32.46%  |
| SSD     | 1217      | 1678   | 31.05%  |
| HDD     | 1185      | 1458   | 30.24%  |
| MMC     | 201       | 273    | 5.13%   |
| Unknown | 44        | 52     | 1.12%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2111      | 3015   | 56.63%  |
| NVMe | 1271      | 1703   | 34.09%  |
| MMC  | 201       | 273    | 5.39%   |
| SAS  | 145       | 180    | 3.89%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1718      | 2343   | 73.2%   |
| 0.51-1.0   | 572       | 718    | 24.37%  |
| 1.01-2.0   | 46        | 60     | 1.96%   |
| 3.01-4.0   | 6         | 7      | 0.26%   |
| 4.01-10.0  | 3         | 6      | 0.13%   |
| 2.01-3.0   | 1         | 1      | 0.04%   |
| 10.01-20.0 | 1         | 1      | 0.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1065      | 29.97%  |
| 251-500        | 1008      | 28.36%  |
| 501-1000       | 471       | 13.25%  |
| 1-20           | 255       | 7.18%   |
| 51-100         | 248       | 6.98%   |
| 1001-2000      | 184       | 5.18%   |
| 21-50          | 152       | 4.28%   |
| Unknown        | 76        | 2.14%   |
| 2001-3000      | 48        | 1.35%   |
| More than 3000 | 47        | 1.32%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1490      | 40%     |
| 21-50          | 693       | 18.6%   |
| 101-250        | 526       | 14.12%  |
| 51-100         | 436       | 11.7%   |
| 251-500        | 282       | 7.57%   |
| 501-1000       | 153       | 4.11%   |
| Unknown        | 76        | 2.04%   |
| 1001-2000      | 45        | 1.21%   |
| 2001-3000      | 11        | 0.3%    |
| More than 3000 | 10        | 0.27%   |
| 0              | 3         | 0.08%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                           | 7         | 8      | 3.26%   |
| Seagate ST500LT012-1DG142 500GB                     | 7         | 7      | 3.26%   |
| HGST HTS545050A7E680 500GB                          | 7         | 9      | 3.26%   |
| SanDisk SSD PLUS 480GB                              | 6         | 7      | 2.79%   |
| Seagate ST9250827AS 250GB                           | 5         | 5      | 2.33%   |
| China G521N256GB SSD                                | 5         | 6      | 2.33%   |
| Seagate ST9500420AS 500GB                           | 4         | 4      | 1.86%   |
| Seagate ST500LM021-1KJ152 500GB                     | 4         | 4      | 1.86%   |
| Seagate ST1000LM035-1RK172 1TB                      | 4         | 4      | 1.86%   |
| Kingston SA400S37480G 480GB SSD                     | 4         | 4      | 1.86%   |
| Hitachi HTS545050A7E380 500GB                       | 4         | 4      | 1.86%   |
| HGST HTS721010A9E630 1TB                            | 4         | 4      | 1.86%   |
| Toshiba MQ01ABD100 1TB                              | 3         | 3      | 1.4%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 3         | 3      | 1.4%    |
| HGST HTS541010A9E680 1TB                            | 3         | 3      | 1.4%    |
| WDC WD5000BPVT-60HXZT3 500GB                        | 2         | 3      | 0.93%   |
| Toshiba Q300. 240GB SSD                             | 2         | 2      | 0.93%   |
| Toshiba MQ01ABD050 500GB                            | 2         | 2      | 0.93%   |
| Toshiba MK5076GSX 500GB                             | 2         | 2      | 0.93%   |
| SK hynix HFS256G39TND-N210A 256GB SSD               | 2         | 2      | 0.93%   |
| Seagate ST9500420ASG 500GB                          | 2         | 2      | 0.93%   |
| Seagate ST500LT012-9WS142 500GB                     | 2         | 2      | 0.93%   |
| Seagate ST320LT012-9WS14C 320GB                     | 2         | 2      | 0.93%   |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB SSD | 2         | 2      | 0.93%   |
| Kingston SV300S37A120G 120GB SSD                    | 2         | 2      | 0.93%   |
| Kingston SUV400S37240G 240GB SSD                    | 2         | 3      | 0.93%   |
| Intel SSDSC2BF180A5H SED 180GB                      | 2         | 2      | 0.93%   |
| Hitachi HTS723232A7A364 320GB                       | 2         | 2      | 0.93%   |
| Hitachi HTS547550A9E384 500GB                       | 2         | 2      | 0.93%   |
| Hitachi HTS545050B9A300 500GB                       | 2         | 2      | 0.93%   |
| Hitachi HTS543232L9A300 320GB                       | 2         | 3      | 0.93%   |
| Hitachi HTS543232A7A384 320GB                       | 2         | 2      | 0.93%   |
| Hitachi HTS543216L9A300 160GB                       | 2         | 2      | 0.93%   |
| HGST HTS545050A7E380 500GB                          | 2         | 2      | 0.93%   |
| Fujitsu MHZ2250BH G2 250GB                          | 2         | 2      | 0.93%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 1         | 1      | 0.47%   |
| WDC WD7500BPVT-60HXZT1 752GB                        | 1         | 1      | 0.47%   |
| WDC WD6400BEVT-22A0RT0 640GB                        | 1         | 2      | 0.47%   |
| WDC WD5000LPVX-22V0TT0 500GB                        | 1         | 1      | 0.47%   |
| WDC WD5000LPCX-24VHAT0 500GB                        | 1         | 1      | 0.47%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 54        | 56     | 25.12%  |
| Hitachi             | 26        | 28     | 12.09%  |
| Toshiba             | 25        | 27     | 11.63%  |
| WDC                 | 21        | 24     | 9.77%   |
| HGST                | 18        | 21     | 8.37%   |
| Samsung Electronics | 14        | 15     | 6.51%   |
| SK hynix            | 9         | 9      | 4.19%   |
| Kingston            | 9         | 10     | 4.19%   |
| SanDisk             | 8         | 9      | 3.72%   |
| China               | 7         | 8      | 3.26%   |
| Intel               | 6         | 6      | 2.79%   |
| Micron Technology   | 5         | 7      | 2.33%   |
| Fujitsu             | 5         | 5      | 2.33%   |
| Crucial             | 4         | 6      | 1.86%   |
| OCZ                 | 1         | 1      | 0.47%   |
| IBM                 | 1         | 1      | 0.47%   |
| Dogfish             | 1         | 1      | 0.47%   |
| BAITITON            | 1         | 1      | 0.47%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 54        | 56     | 35.76%  |
| Hitachi             | 26        | 28     | 17.22%  |
| WDC                 | 20        | 23     | 13.25%  |
| Toshiba             | 20        | 22     | 13.25%  |
| HGST                | 18        | 21     | 11.92%  |
| Samsung Electronics | 7         | 7      | 4.64%   |
| Fujitsu             | 5         | 5      | 3.31%   |
| IBM                 | 1         | 1      | 0.66%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 149       | 163    | 70.28%  |
| SSD  | 55        | 64     | 25.94%  |
| NVMe | 8         | 8      | 3.77%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2029      | 3159   | 56.74%  |
| Works    | 1337      | 1776   | 37.39%  |
| Malfunc  | 209       | 235    | 5.84%   |
| Failed   | 1         | 1      | 0.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2284      | 57.87%  |
| Samsung Electronics              | 369       | 9.35%   |
| AMD                              | 361       | 9.15%   |
| SanDisk                          | 246       | 6.23%   |
| SK hynix                         | 143       | 3.62%   |
| Micron Technology                | 123       | 3.12%   |
| Kingston Technology Company      | 88        | 2.23%   |
| Phison Electronics               | 74        | 1.87%   |
| Toshiba America Info Systems     | 59        | 1.49%   |
| KIOXIA                           | 46        | 1.17%   |
| Nvidia                           | 29        | 0.73%   |
| Micron/Crucial Technology        | 29        | 0.73%   |
| Silicon Integrated Systems [SiS] | 15        | 0.38%   |
| Silicon Motion                   | 13        | 0.33%   |
| Apple                            | 11        | 0.28%   |
| VIA Technologies                 | 7         | 0.18%   |
| Union Memory (Shenzhen)          | 7         | 0.18%   |
| Solid State Storage Technology   | 5         | 0.13%   |
| O2 Micro                         | 5         | 0.13%   |
| MAXIO Technology (Hangzhou)      | 5         | 0.13%   |
| JMicron Technology               | 5         | 0.13%   |
| Shenzhen Longsys Electronics     | 3         | 0.08%   |
| Lite-On Technology               | 3         | 0.08%   |
| ADATA Technology                 | 3         | 0.08%   |
| Solidigm                         | 2         | 0.05%   |
| Silicon Image                    | 2         | 0.05%   |
| Netac Technology                 | 2         | 0.05%   |
| Marvell Technology Group         | 2         | 0.05%   |
| Lenovo                           | 2         | 0.05%   |
| Yangtze Memory Technologies      | 1         | 0.03%   |
| Seagate Technology               | 1         | 0.03%   |
| Biwin Storage Technology         | 1         | 0.03%   |
| ASMedia Technology               | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 311       | 7.3%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 242       | 5.68%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 162       | 3.8%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 161       | 3.78%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 159       | 3.73%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 148       | 3.47%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 147       | 3.45%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 130       | 3.05%   |
| Intel Volume Management Device NVMe RAID Controller                            | 112       | 2.63%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 108       | 2.53%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 102       | 2.39%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 94        | 2.21%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 89        | 2.09%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 87        | 2.04%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 86        | 2.02%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 85        | 1.99%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 76        | 1.78%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 68        | 1.6%    |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 66        | 1.55%   |
| Intel SSD 660P Series                                                          | 60        | 1.41%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 57        | 1.34%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 51        | 1.2%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 48        | 1.13%   |
| Intel Tiger Lake-LP SATA Controller                                            | 44        | 1.03%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 44        | 1.03%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 43        | 1.01%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 41        | 0.96%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 40        | 0.94%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 40        | 0.94%   |
| Intel Comet Lake SATA AHCI Controller                                          | 37        | 0.87%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 36        | 0.84%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 35        | 0.82%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 33        | 0.77%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 32        | 0.75%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 31        | 0.73%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 31        | 0.73%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 29        | 0.68%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 29        | 0.68%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 29        | 0.68%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 29        | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 2273      | 55.41%  |
| NVMe | 1278      | 31.16%  |
| RAID | 288       | 7.02%   |
| IDE  | 263       | 6.41%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 2737      | 81.26%  |
| AMD          | 630       | 18.71%  |
| CentaurHauls | 1         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8750H CPU @ 2.20GHz             | 65        | 1.93%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 57        | 1.69%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 56        | 1.66%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 56        | 1.66%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 52        | 1.54%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 49        | 1.45%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 47        | 1.39%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 44        | 1.31%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 44        | 1.31%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 43        | 1.28%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 42        | 1.25%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 41        | 1.22%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 40        | 1.19%   |
| AMD Custom APU 0405                           | 38        | 1.13%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 37        | 1.1%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 36        | 1.07%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 34        | 1.01%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 31        | 0.92%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 31        | 0.92%   |
| Intel 12th Gen Core i7-12700H                 | 31        | 0.92%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 28        | 0.83%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 28        | 0.83%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 27        | 0.8%    |
| Intel Celeron N4020 CPU @ 1.10GHz             | 27        | 0.8%    |
| AMD Ryzen 7 5700U with Radeon Graphics        | 27        | 0.8%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 26        | 0.77%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 25        | 0.74%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 25        | 0.74%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 23        | 0.68%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 22        | 0.65%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 22        | 0.65%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 22        | 0.65%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 22        | 0.65%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 20        | 0.59%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 19        | 0.56%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 19        | 0.56%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 19        | 0.56%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 19        | 0.56%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 19        | 0.56%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 18        | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 750       | 22.26%  |
| Intel Core i5           | 650       | 19.29%  |
| Other                   | 395       | 11.72%  |
| Intel Celeron           | 250       | 7.42%   |
| Intel Core i3           | 242       | 7.18%   |
| AMD Ryzen 7             | 191       | 5.67%   |
| Intel Core 2 Duo        | 184       | 5.46%   |
| AMD Ryzen 5             | 136       | 4.04%   |
| Intel Atom              | 110       | 3.27%   |
| Intel Pentium           | 42        | 1.25%   |
| Intel Pentium Dual-Core | 41        | 1.22%   |
| Intel Pentium Dual      | 33        | 0.98%   |
| AMD A4                  | 30        | 0.89%   |
| AMD A6                  | 28        | 0.83%   |
| Intel Genuine           | 26        | 0.77%   |
| Intel Core 2            | 26        | 0.77%   |
| AMD E1                  | 24        | 0.71%   |
| AMD A8                  | 21        | 0.62%   |
| AMD Ryzen 9             | 18        | 0.53%   |
| AMD Ryzen 7 PRO         | 15        | 0.45%   |
| AMD Ryzen 3             | 15        | 0.45%   |
| AMD E                   | 14        | 0.42%   |
| Intel Core i9           | 10        | 0.3%    |
| Intel Pentium M         | 9         | 0.27%   |
| Intel Celeron M         | 9         | 0.27%   |
| AMD Athlon              | 9         | 0.27%   |
| AMD A10                 | 9         | 0.27%   |
| AMD Turion 64 X2 Mobile | 7         | 0.21%   |
| Intel Core m3           | 6         | 0.18%   |
| AMD FX                  | 5         | 0.15%   |
| Intel Pentium Silver    | 4         | 0.12%   |
| Intel Pentium 4         | 4         | 0.12%   |
| Intel Core m5           | 4         | 0.12%   |
| AMD Turion II Dual-Core | 4         | 0.12%   |
| AMD Athlon II           | 4         | 0.12%   |
| AMD Turion 64 Mobile    | 3         | 0.09%   |
| AMD Ryzen 5 PRO         | 3         | 0.09%   |
| AMD E2                  | 3         | 0.09%   |
| AMD Athlon X2           | 3         | 0.09%   |
| AMD A12                 | 3         | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1592      | 47.21%  |
| 4       | 1048      | 31.08%  |
| 8       | 246       | 7.3%    |
| 6       | 238       | 7.06%   |
| 1       | 123       | 3.65%   |
| 14      | 54        | 1.6%    |
| 10      | 41        | 1.22%   |
| 12      | 19        | 0.56%   |
| 16      | 5         | 0.15%   |
| Unknown | 4         | 0.12%   |
| 24      | 1         | 0.03%   |
| 20      | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3367      | 99.97%  |
| 2      | 1         | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 2436      | 72.24%  |
| 1       | 932       | 27.64%  |
| Unknown | 4         | 0.12%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3256      | 96.25%  |
| 32-bit         | 58        | 1.71%   |
| Unknown        | 55        | 1.63%   |
| 64-bit         | 14        | 0.41%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 951       | 27.1%   |
| 0x206a7    | 146       | 4.16%   |
| 0x306a9    | 125       | 3.56%   |
| 0x806c1    | 113       | 3.22%   |
| 0x806ea    | 104       | 2.96%   |
| 0x40651    | 104       | 2.96%   |
| 0x906ea    | 97        | 2.76%   |
| 0x806ec    | 97        | 2.76%   |
| 0x406e3    | 88        | 2.51%   |
| 0x1067a    | 86        | 2.45%   |
| 0x806e9    | 81        | 2.31%   |
| 0x6fd      | 80        | 2.28%   |
| 0x20655    | 79        | 2.25%   |
| 0x306d4    | 72        | 2.05%   |
| 0x306c3    | 69        | 1.97%   |
| 0x30678    | 53        | 1.51%   |
| 0x0a50000c | 52        | 1.48%   |
| 0x08108109 | 50        | 1.42%   |
| 0x10676    | 43        | 1.23%   |
| 0xa0652    | 42        | 1.2%    |
| 0x706e5    | 42        | 1.2%    |
| 0x706a1    | 38        | 1.08%   |
| 0x20652    | 38        | 1.08%   |
| 0x06006705 | 38        | 1.08%   |
| 0x906a3    | 35        | 1%      |
| 0x506e3    | 35        | 1%      |
| 0x08600106 | 33        | 0.94%   |
| 0x106ca    | 32        | 0.91%   |
| 0x706a8    | 31        | 0.88%   |
| 0x08108102 | 30        | 0.85%   |
| 0x906e9    | 29        | 0.83%   |
| 0x806eb    | 28        | 0.8%    |
| 0x506c9    | 27        | 0.77%   |
| 0x08608103 | 27        | 0.77%   |
| 0x406c4    | 25        | 0.71%   |
| 0x806d1    | 24        | 0.68%   |
| 0x08600104 | 24        | 0.68%   |
| 0x406c3    | 22        | 0.63%   |
| 0x0a50000d | 22        | 0.63%   |
| 0x6f6      | 20        | 0.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 585       | 17.36%  |
| Haswell          | 253       | 7.51%   |
| SandyBridge      | 187       | 5.55%   |
| TigerLake        | 172       | 5.11%   |
| Unknown          | 171       | 5.08%   |
| Penryn           | 168       | 4.99%   |
| Skylake          | 156       | 4.63%   |
| IvyBridge        | 156       | 4.63%   |
| Core             | 155       | 4.6%    |
| Westmere         | 142       | 4.21%   |
| Silvermont       | 125       | 3.71%   |
| Broadwell        | 107       | 3.18%   |
| Goldmont plus    | 96        | 2.85%   |
| Zen+             | 95        | 2.82%   |
| Zen 3            | 95        | 2.82%   |
| Zen 2            | 90        | 2.67%   |
| Alderlake Hybrid | 84        | 2.49%   |
| IceLake          | 71        | 2.11%   |
| CometLake        | 71        | 2.11%   |
| Bonnell          | 68        | 2.02%   |
| Excavator        | 66        | 1.96%   |
| Goldmont         | 37        | 1.1%    |
| Zen              | 30        | 0.89%   |
| Puma             | 29        | 0.86%   |
| P6               | 28        | 0.83%   |
| Jaguar           | 25        | 0.74%   |
| Bobcat           | 23        | 0.68%   |
| K8 Hammer        | 18        | 0.53%   |
| K10              | 15        | 0.45%   |
| Tremont          | 12        | 0.36%   |
| Piledriver       | 10        | 0.3%    |
| Nehalem          | 10        | 0.3%    |
| Steamroller      | 6         | 0.18%   |
| NetBurst         | 5         | 0.15%   |
| K10 Llano        | 4         | 0.12%   |
| K8 & K10 hybrid  | 3         | 0.09%   |
| Gracemont        | 1         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2459      | 56.93%  |
| Nvidia                           | 992       | 22.97%  |
| AMD                              | 851       | 19.7%   |
| Silicon Integrated Systems [SiS] | 10        | 0.23%   |
| VIA Technologies                 | 7         | 0.16%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 170       | 3.81%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 162       | 3.63%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 151       | 3.39%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 146       | 3.27%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 132       | 2.96%   |
| Intel UHD Graphics 620                                                                   | 120       | 2.69%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 104       | 2.33%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 103       | 2.31%   |
| Intel Core Processor Integrated Graphics Controller                                      | 99        | 2.22%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 97        | 2.17%   |
| Intel HD Graphics 620                                                                    | 95        | 2.13%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 93        | 2.09%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 92        | 2.06%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 91        | 2.04%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 89        | 2%      |
| Intel HD Graphics 5500                                                                   | 89        | 2%      |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 87        | 1.95%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 73        | 1.64%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 73        | 1.64%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 70        | 1.57%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 68        | 1.52%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 55        | 1.23%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 55        | 1.23%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 54        | 1.21%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 54        | 1.21%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 52        | 1.17%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 51        | 1.14%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 47        | 1.05%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 47        | 1.05%   |
| Intel HD Graphics 530                                                                    | 47        | 1.05%   |
| AMD Lucienne                                                                             | 46        | 1.03%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 39        | 0.87%   |
| Intel HD Graphics 630                                                                    | 39        | 0.87%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 37        | 0.83%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 36        | 0.81%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 36        | 0.81%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 35        | 0.78%   |
| Intel HD Graphics 500                                                                    | 33        | 0.74%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 31        | 0.7%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 31        | 0.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 1610      | 47.68%  |
| Intel + Nvidia | 717       | 21.23%  |
| 1 x AMD        | 571       | 16.91%  |
| 1 x Nvidia     | 164       | 4.86%   |
| Intel + AMD    | 118       | 3.49%   |
| AMD + Nvidia   | 111       | 3.29%   |
| 2 x AMD        | 50        | 1.48%   |
| 2 x Intel      | 12        | 0.36%   |
| 1 x SiS        | 10        | 0.3%    |
| 1 x VIA        | 7         | 0.21%   |
| 2 x Nvidia     | 4         | 0.12%   |
| Other          | 3         | 0.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2834      | 83.13%  |
| Proprietary | 468       | 13.73%  |
| Unknown     | 107       | 3.14%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2186      | 63.12%  |
| 0.01-0.5   | 438       | 12.65%  |
| 1.01-2.0   | 366       | 10.57%  |
| 3.01-4.0   | 215       | 6.21%   |
| 0.51-1.0   | 174       | 5.02%   |
| 5.01-6.0   | 46        | 1.33%   |
| 7.01-8.0   | 30        | 0.87%   |
| 2.01-3.0   | 5         | 0.14%   |
| 8.01-16.0  | 3         | 0.09%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 653       | 17.24%  |
| Chimei Innolux          | 595       | 15.71%  |
| LG Display              | 484       | 12.78%  |
| BOE                     | 476       | 12.57%  |
| Samsung Electronics     | 355       | 9.37%   |
| Sharp                   | 100       | 2.64%   |
| Goldstar                | 100       | 2.64%   |
| Chi Mei Optoelectronics | 97        | 2.56%   |
| Dell                    | 92        | 2.43%   |
| Apple                   | 89        | 2.35%   |
| PANDA                   | 81        | 2.14%   |
| Hewlett-Packard         | 76        | 2.01%   |
| BenQ                    | 58        | 1.53%   |
| Lenovo                  | 53        | 1.4%    |
| LG Philips              | 45        | 1.19%   |
| Philips                 | 35        | 0.92%   |
| Acer                    | 33        | 0.87%   |
| Valve                   | 29        | 0.77%   |
| AOC                     | 28        | 0.74%   |
| Ancor Communications    | 28        | 0.74%   |
| HannStar                | 22        | 0.58%   |
| InfoVision              | 20        | 0.53%   |
| Sony                    | 19        | 0.5%    |
| ASUSTek Computer        | 18        | 0.48%   |
| CSO                     | 17        | 0.45%   |
| CPT                     | 16        | 0.42%   |
| MSI                     | 9         | 0.24%   |
| TMX                     | 8         | 0.21%   |
| Quanta Display          | 8         | 0.21%   |
| ViewSonic               | 7         | 0.18%   |
| Unknown                 | 7         | 0.18%   |
| Analogix                | 7         | 0.18%   |
| Mi                      | 6         | 0.16%   |
| Toshiba                 | 5         | 0.13%   |
| Seiko/Epson             | 5         | 0.13%   |
| Panasonic               | 5         | 0.13%   |
| HKC                     | 5         | 0.13%   |
| AGO                     | 5         | 0.13%   |
| ___                     | 4         | 0.11%   |
| NEC Computers           | 4         | 0.11%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 70        | 1.83%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 45        | 1.17%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 35        | 0.91%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 33        | 0.86%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 32        | 0.84%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 27        | 0.7%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 25        | 0.65%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 24        | 0.63%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 23        | 0.6%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 22        | 0.57%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 22        | 0.57%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 22        | 0.57%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 21        | 0.55%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 20        | 0.52%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 19        | 0.5%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 18        | 0.47%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 18        | 0.47%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 17        | 0.44%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 340x190mm 15.3-inch            | 17        | 0.44%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 16        | 0.42%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch              | 16        | 0.42%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 16        | 0.42%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 16        | 0.42%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                    | 16        | 0.42%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 15        | 0.39%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 15        | 0.39%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 15        | 0.39%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch           | 14        | 0.37%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 14        | 0.37%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 13        | 0.34%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 13        | 0.34%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 13        | 0.34%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 13        | 0.34%   |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch                    | 13        | 0.34%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 13        | 0.34%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 12        | 0.31%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 12        | 0.31%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 12        | 0.31%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 12        | 0.31%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 11        | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1459      | 41.53%  |
| 1366x768 (WXGA)    | 1082      | 30.8%   |
| 1280x800 (WXGA)    | 181       | 5.15%   |
| 3840x2160 (4K)     | 105       | 2.99%   |
| 1600x900 (HD+)     | 88        | 2.5%    |
| 2560x1440 (QHD)    | 78        | 2.22%   |
| 1440x900 (WXGA+)   | 69        | 1.96%   |
| 1920x1200 (WUXGA)  | 59        | 1.68%   |
| 2560x1600          | 50        | 1.42%   |
| 1024x600           | 47        | 1.34%   |
| 800x1280           | 35        | 1%      |
| 1680x1050 (WSXGA+) | 35        | 1%      |
| 1280x1024 (SXGA)   | 33        | 0.94%   |
| 2160x1440          | 32        | 0.91%   |
| 2880x1800          | 31        | 0.88%   |
| 3440x1440          | 18        | 0.51%   |
| 2560x1080          | 17        | 0.48%   |
| 3200x1800 (QHD+)   | 9         | 0.26%   |
| 1360x768           | 9         | 0.26%   |
| 1024x768 (XGA)     | 8         | 0.23%   |
| 3840x2400          | 7         | 0.2%    |
| Unknown            | 5         | 0.14%   |
| 1920x1280          | 4         | 0.11%   |
| 1280x768           | 4         | 0.11%   |
| 3456x2160          | 3         | 0.09%   |
| 3200x2000          | 3         | 0.09%   |
| 3072x1920          | 3         | 0.09%   |
| 2520x1680          | 3         | 0.09%   |
| 2288x1287          | 3         | 0.09%   |
| 1920x540           | 3         | 0.09%   |
| 1600x1200          | 3         | 0.09%   |
| 1400x1050          | 3         | 0.09%   |
| 3840x1600          | 2         | 0.06%   |
| 3840x1080          | 2         | 0.06%   |
| 2304x1440          | 2         | 0.06%   |
| 2256x1504          | 2         | 0.06%   |
| 5760x1080          | 1         | 0.03%   |
| 3200x1080          | 1         | 0.03%   |
| 3000x2000          | 1         | 0.03%   |
| 2944x1840          | 1         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1787      | 47.16%  |
| 13      | 444       | 11.72%  |
| 14      | 328       | 8.66%   |
| 17      | 202       | 5.33%   |
| 24      | 136       | 3.59%   |
| 27      | 114       | 3.01%   |
| 23      | 103       | 2.72%   |
| 21      | 103       | 2.72%   |
| 12      | 74        | 1.95%   |
| 16      | 72        | 1.9%    |
| 11      | 59        | 1.56%   |
| 10      | 54        | 1.43%   |
| Unknown | 41        | 1.08%   |
| 34      | 36        | 0.95%   |
| 31      | 32        | 0.84%   |
| 7       | 29        | 0.77%   |
| 19      | 25        | 0.66%   |
| 84      | 17        | 0.45%   |
| 20      | 17        | 0.45%   |
| 18      | 17        | 0.45%   |
| 22      | 12        | 0.32%   |
| 72      | 9         | 0.24%   |
| 40      | 9         | 0.24%   |
| 54      | 8         | 0.21%   |
| 25      | 8         | 0.21%   |
| 3       | 7         | 0.18%   |
| 32      | 6         | 0.16%   |
| 26      | 6         | 0.16%   |
| 52      | 4         | 0.11%   |
| 46      | 4         | 0.11%   |
| 8       | 4         | 0.11%   |
| 38      | 3         | 0.08%   |
| 37      | 3         | 0.08%   |
| 142     | 2         | 0.05%   |
| 36      | 2         | 0.05%   |
| 35      | 2         | 0.05%   |
| 28      | 2         | 0.05%   |
| 86      | 1         | 0.03%   |
| 75      | 1         | 0.03%   |
| 65      | 1         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 2317      | 61.82%  |
| 201-300        | 451       | 12.03%  |
| 501-600        | 333       | 8.88%   |
| 351-400        | 255       | 6.8%    |
| 401-500        | 159       | 4.24%   |
| 701-800        | 43        | 1.15%   |
| 601-700        | 42        | 1.12%   |
| Unknown        | 41        | 1.09%   |
| 1-100          | 36        | 0.96%   |
| 1501-2000      | 27        | 0.72%   |
| 1001-1500      | 20        | 0.53%   |
| 801-900        | 17        | 0.45%   |
| 101-200        | 4         | 0.11%   |
| More than 2000 | 2         | 0.05%   |
| 901-1000       | 1         | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 2669      | 80.42%  |
| 16/10   | 438       | 13.2%   |
| 3/2     | 51        | 1.54%   |
| 21/9    | 37        | 1.11%   |
| 5/4     | 32        | 0.96%   |
| Unknown | 29        | 0.87%   |
| 0.67    | 27        | 0.81%   |
| 4/3     | 18        | 0.54%   |
| 6/5     | 7         | 0.21%   |
| 0.62    | 3         | 0.09%   |
| 1.00    | 2         | 0.06%   |
| 0.56    | 2         | 0.06%   |
| 32/9    | 1         | 0.03%   |
| 1.03    | 1         | 0.03%   |
| 0.89    | 1         | 0.03%   |
| 0.65    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1806      | 47.85%  |
| 81-90          | 570       | 15.1%   |
| 201-250        | 295       | 7.82%   |
| 71-80          | 197       | 5.22%   |
| 121-130        | 147       | 3.9%    |
| 301-350        | 116       | 3.07%   |
| 351-500        | 75        | 1.99%   |
| 61-70          | 69        | 1.83%   |
| 151-200        | 67        | 1.78%   |
| 51-60          | 59        | 1.56%   |
| 41-50          | 54        | 1.43%   |
| More than 1000 | 45        | 1.19%   |
| 111-120        | 45        | 1.19%   |
| Unknown        | 41        | 1.09%   |
| 1-40           | 40        | 1.06%   |
| 131-140        | 39        | 1.03%   |
| 251-300        | 33        | 0.87%   |
| 141-150        | 33        | 0.87%   |
| 501-1000       | 24        | 0.64%   |
| 91-100         | 19        | 0.5%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1363      | 36.84%  |
| 101-120       | 1151      | 31.11%  |
| 51-100        | 705       | 19.05%  |
| 161-240       | 304       | 8.22%   |
| More than 240 | 92        | 2.49%   |
| 1-50          | 44        | 1.19%   |
| Unknown       | 41        | 1.11%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 2701      | 78.11%  |
| 2     | 551       | 15.93%  |
| 0     | 121       | 3.5%    |
| 3     | 78        | 2.26%   |
| 4     | 6         | 0.17%   |
| 5     | 1         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1873      | 34.54%  |
| Intel                             | 1597      | 29.45%  |
| Qualcomm Atheros                  | 786       | 14.49%  |
| Broadcom                          | 395       | 7.28%   |
| MediaTek                          | 108       | 1.99%   |
| Broadcom Limited                  | 84        | 1.55%   |
| Marvell Technology Group          | 80        | 1.48%   |
| TP-Link                           | 59        | 1.09%   |
| Ralink                            | 54        | 1%      |
| Ralink Technology                 | 43        | 0.79%   |
| ASIX Electronics                  | 40        | 0.74%   |
| Xiaomi                            | 26        | 0.48%   |
| Nvidia                            | 22        | 0.41%   |
| Samsung Electronics               | 20        | 0.37%   |
| DisplayLink                       | 19        | 0.35%   |
| Ericsson Business Mobile Networks | 18        | 0.33%   |
| JMicron Technology                | 17        | 0.31%   |
| Lenovo                            | 16        | 0.3%    |
| Dell                              | 16        | 0.3%    |
| Silicon Integrated Systems [SiS]  | 15        | 0.28%   |
| Qualcomm                          | 15        | 0.28%   |
| Hewlett-Packard                   | 14        | 0.26%   |
| Sierra Wireless                   | 12        | 0.22%   |
| Qualcomm Atheros Communications   | 9         | 0.17%   |
| Huawei Technologies               | 8         | 0.15%   |
| D-Link                            | 7         | 0.13%   |
| VIA Technologies                  | 6         | 0.11%   |
| Edimax Technology                 | 6         | 0.11%   |
| ASUSTek Computer                  | 5         | 0.09%   |
| LSI                               | 4         | 0.07%   |
| Google                            | 4         | 0.07%   |
| Attansic Technology               | 4         | 0.07%   |
| Toshiba                           | 3         | 0.06%   |
| NetGear                           | 3         | 0.06%   |
| D-Link System                     | 3         | 0.06%   |
| Arduino SA                        | 3         | 0.06%   |
| Apple                             | 3         | 0.06%   |
| OPPO Electronics                  | 2         | 0.04%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.04%   |
| Microchip Technology              | 2         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 1066      | 16.72%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 307       | 4.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 154       | 2.42%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 153       | 2.4%    |
| Intel Wi-Fi 6 AX200                                                     | 138       | 2.16%   |
| Intel Wi-Fi 6 AX201                                                     | 125       | 1.96%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 119       | 1.87%   |
| Intel Wireless 8265 / 8275                                              | 117       | 1.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 116       | 1.82%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 116       | 1.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 108       | 1.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 91        | 1.43%   |
| Intel Wireless 7265                                                     | 90        | 1.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 86        | 1.35%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 82        | 1.29%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 81        | 1.27%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 72        | 1.13%   |
| Intel Wireless 7260                                                     | 71        | 1.11%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 70        | 1.1%    |
| Intel Wireless 3165                                                     | 65        | 1.02%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 63        | 0.99%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 61        | 0.96%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 59        | 0.93%   |
| Broadcom BCM43142 802.11b/g/n                                           | 59        | 0.93%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 57        | 0.89%   |
| Intel WiFi Link 5100                                                    | 51        | 0.8%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 47        | 0.74%   |
| Intel Wireless 3160                                                     | 46        | 0.72%   |
| Intel Wireless 8260                                                     | 45        | 0.71%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 45        | 0.71%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 44        | 0.69%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 42        | 0.66%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 41        | 0.64%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 40        | 0.63%   |
| ASIX AX88179 Gigabit Ethernet                                           | 37        | 0.58%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 36        | 0.56%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                         | 36        | 0.56%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 34        | 0.53%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 31        | 0.49%   |
| Intel Centrino Advanced-N 6200                                          | 31        | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1542      | 43.97%  |
| Qualcomm Atheros                  | 658       | 18.76%  |
| Realtek Semiconductor             | 649       | 18.51%  |
| Broadcom                          | 274       | 7.81%   |
| MediaTek                          | 105       | 2.99%   |
| Broadcom Limited                  | 58        | 1.65%   |
| Ralink                            | 54        | 1.54%   |
| Ralink Technology                 | 43        | 1.23%   |
| TP-Link                           | 41        | 1.17%   |
| Sierra Wireless                   | 12        | 0.34%   |
| Qualcomm Atheros Communications   | 9         | 0.26%   |
| Qualcomm                          | 9         | 0.26%   |
| Dell                              | 9         | 0.26%   |
| D-Link                            | 7         | 0.2%    |
| Edimax Technology                 | 6         | 0.17%   |
| Ericsson Business Mobile Networks | 5         | 0.14%   |
| ASUSTek Computer                  | 5         | 0.14%   |
| Hewlett-Packard                   | 4         | 0.11%   |
| NetGear                           | 3         | 0.09%   |
| D-Link System                     | 3         | 0.09%   |
| Fibocom                           | 2         | 0.06%   |
| Belkin Components                 | 2         | 0.06%   |
| Accton Technology                 | 2         | 0.06%   |
| Sitecom Europe                    | 1         | 0.03%   |
| Linksys                           | 1         | 0.03%   |
| Gemtek                            | 1         | 0.03%   |
| AirTies Wireless Networks         | 1         | 0.03%   |
| Unknown                           | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 153       | 4.33%   |
| Intel Wi-Fi 6 AX200                                                     | 138       | 3.91%   |
| Intel Wi-Fi 6 AX201                                                     | 125       | 3.54%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 119       | 3.37%   |
| Intel Wireless 8265 / 8275                                              | 117       | 3.31%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 116       | 3.28%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 116       | 3.28%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 108       | 3.06%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 91        | 2.58%   |
| Intel Wireless 7265                                                     | 90        | 2.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 86        | 2.43%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 82        | 2.32%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 81        | 2.29%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 72        | 2.04%   |
| Intel Wireless 7260                                                     | 71        | 2.01%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 70        | 1.98%   |
| Intel Wireless 3165                                                     | 65        | 1.84%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 63        | 1.78%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 61        | 1.73%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 59        | 1.67%   |
| Broadcom BCM43142 802.11b/g/n                                           | 59        | 1.67%   |
| Intel WiFi Link 5100                                                    | 51        | 1.44%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 47        | 1.33%   |
| Intel Wireless 3160                                                     | 46        | 1.3%    |
| Intel Wireless 8260                                                     | 45        | 1.27%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 45        | 1.27%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 44        | 1.25%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 42        | 1.19%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 41        | 1.16%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 40        | 1.13%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 34        | 0.96%   |
| Intel Centrino Advanced-N 6200                                          | 31        | 0.88%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 30        | 0.85%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 29        | 0.82%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 28        | 0.79%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 28        | 0.79%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 27        | 0.76%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 27        | 0.76%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 25        | 0.71%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 24        | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1581      | 57.51%  |
| Intel                                  | 428       | 15.57%  |
| Qualcomm Atheros                       | 214       | 7.78%   |
| Broadcom                               | 174       | 6.33%   |
| Marvell Technology Group               | 80        | 2.91%   |
| ASIX Electronics                       | 40        | 1.46%   |
| Broadcom Limited                       | 28        | 1.02%   |
| Xiaomi                                 | 26        | 0.95%   |
| Nvidia                                 | 22        | 0.8%    |
| Samsung Electronics                    | 20        | 0.73%   |
| TP-Link                                | 19        | 0.69%   |
| DisplayLink                            | 19        | 0.69%   |
| JMicron Technology                     | 17        | 0.62%   |
| Lenovo                                 | 16        | 0.58%   |
| Silicon Integrated Systems [SiS]       | 15        | 0.55%   |
| VIA Technologies                       | 6         | 0.22%   |
| Qualcomm                               | 6         | 0.22%   |
| Hewlett-Packard                        | 6         | 0.22%   |
| LSI                                    | 4         | 0.15%   |
| Huawei Technologies                    | 4         | 0.15%   |
| Google                                 | 4         | 0.15%   |
| Attansic Technology                    | 4         | 0.15%   |
| MediaTek                               | 3         | 0.11%   |
| Apple                                  | 3         | 0.11%   |
| OPPO Electronics                       | 2         | 0.07%   |
| Microchip Technology                   | 2         | 0.07%   |
| T & A Mobile Phones                    | 1         | 0.04%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.04%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.04%   |
| National Semiconductor                 | 1         | 0.04%   |
| Davicom Semiconductor                  | 1         | 0.04%   |
| ADMtek                                 | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 1066      | 38.24%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 307       | 11.01%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 154       | 5.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 57        | 2.04%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 37        | 1.33%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 36        | 1.29%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 36        | 1.29%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 31        | 1.11%   |
| Intel 82577LM Gigabit Network Connection                                       | 30        | 1.08%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 27        | 0.97%   |
| Intel Ethernet Connection (4) I219-LM                                          | 27        | 0.97%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 26        | 0.93%   |
| Intel Ethernet Connection I218-LM                                              | 26        | 0.93%   |
| Intel Ethernet Connection (3) I218-LM                                          | 23        | 0.82%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 21        | 0.75%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 20        | 0.72%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 20        | 0.72%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 19        | 0.68%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 19        | 0.68%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 18        | 0.65%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 18        | 0.65%   |
| Intel Ethernet Connection (4) I219-V                                           | 18        | 0.65%   |
| Intel 82567LM Gigabit Network Connection                                       | 18        | 0.65%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 17        | 0.61%   |
| Realtek RTL8125 2.5GbE Controller                                              | 17        | 0.61%   |
| Intel Ethernet Connection I219-LM                                              | 17        | 0.61%   |
| Intel Ethernet Connection (13) I219-V                                          | 17        | 0.61%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 16        | 0.57%   |
| Nvidia MCP79 Ethernet                                                          | 16        | 0.57%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 16        | 0.57%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 15        | 0.54%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 15        | 0.54%   |
| Intel 82579V Gigabit Network Connection                                        | 14        | 0.5%    |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 14        | 0.5%    |
| Realtek Killer E2600 GbE Controller                                            | 13        | 0.47%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 13        | 0.47%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 13        | 0.47%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 13        | 0.47%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 13        | 0.47%   |
| Intel Ethernet Connection I217-LM                                              | 13        | 0.47%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3305      | 54.99%  |
| Ethernet | 2650      | 44.09%  |
| Modem    | 48        | 0.8%    |
| Unknown  | 7         | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2706      | 76.03%  |
| Ethernet | 853       | 23.97%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2353      | 69.8%   |
| 1     | 932       | 27.65%  |
| 0     | 70        | 2.08%   |
| 3     | 15        | 0.44%   |
| 4     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3221      | 94.82%  |
| Yes  | 176       | 5.18%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1193      | 46.2%   |
| Realtek Semiconductor           | 325       | 12.59%  |
| IMC Networks                    | 210       | 8.13%   |
| Qualcomm Atheros Communications | 164       | 6.35%   |
| Foxconn / Hon Hai               | 116       | 4.49%   |
| Lite-On Technology              | 112       | 4.34%   |
| Broadcom                        | 106       | 4.11%   |
| Apple                           | 77        | 2.98%   |
| Realtek                         | 45        | 1.74%   |
| Toshiba                         | 43        | 1.67%   |
| Cambridge Silicon Radio         | 39        | 1.51%   |
| Dell                            | 28        | 1.08%   |
| Hewlett-Packard                 | 27        | 1.05%   |
| Ralink                          | 25        | 0.97%   |
| ASUSTek Computer                | 18        | 0.7%    |
| Alps Electric                   | 16        | 0.62%   |
| Foxconn International           | 12        | 0.46%   |
| MediaTek                        | 10        | 0.39%   |
| Ralink Technology               | 4         | 0.15%   |
| Askey Computer                  | 3         | 0.12%   |
| USI                             | 2         | 0.08%   |
| Taiyo Yuden                     | 2         | 0.08%   |
| Actions                         | 2         | 0.08%   |
| TP-Link                         | 1         | 0.04%   |
| Opticis                         | 1         | 0.04%   |
| Chicony Electronics             | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 427       | 16.54%  |
| Intel AX201 Bluetooth                               | 249       | 9.64%   |
| Realtek Bluetooth Radio                             | 236       | 9.14%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 210       | 8.13%   |
| Intel AX200 Bluetooth                               | 136       | 5.27%   |
| IMC Networks Bluetooth Radio                        | 103       | 3.99%   |
| Intel Bluetooth Device                              | 76        | 2.94%   |
| Qualcomm Atheros  Bluetooth Device                  | 67        | 2.59%   |
| Realtek  Bluetooth 4.2 Adapter                      | 64        | 2.48%   |
| Apple Bluetooth Host Controller                     | 47        | 1.82%   |
| IMC Networks Bluetooth Device                       | 46        | 1.78%   |
| Realtek Bluetooth Radio                             | 45        | 1.74%   |
| IMC Networks Wireless_Device                        | 45        | 1.74%   |
| Foxconn / Hon Hai Bluetooth Device                  | 42        | 1.63%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 39        | 1.51%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 37        | 1.43%   |
| Foxconn / Hon Hai Wireless_Device                   | 35        | 1.36%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 32        | 1.24%   |
| Intel AX210 Bluetooth                               | 29        | 1.12%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 28        | 1.08%   |
| Lite-On Atheros AR3012 Bluetooth                    | 28        | 1.08%   |
| Lite-On Bluetooth Device                            | 26        | 1.01%   |
| Ralink RT3290 Bluetooth                             | 25        | 0.97%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 24        | 0.93%   |
| Intel Wireless-AC 3168 Bluetooth                    | 23        | 0.89%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 20        | 0.77%   |
| Apple Bluetooth USB Host Controller                 | 20        | 0.77%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 19        | 0.74%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 16        | 0.62%   |
| HP Broadcom 2070 Bluetooth Combo                    | 15        | 0.58%   |
| Broadcom BCM2045B (BDC-2.1)                         | 15        | 0.58%   |
| Realtek RTL8723B Bluetooth                          | 13        | 0.5%    |
| Foxconn International BCM43142A0 Bluetooth module   | 12        | 0.46%   |
| Toshiba Integrated Bluetooth HCI                    | 11        | 0.43%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 11        | 0.43%   |
| Foxconn / Hon Hai BCM20702A0                        | 11        | 0.43%   |
| MediaTek Wireless_Device                            | 10        | 0.39%   |
| Lite-On Wireless_Device                             | 10        | 0.39%   |
| Broadcom BCM2045 Bluetooth                          | 10        | 0.39%   |
| Alps Electric BCM2046 Bluetooth Device              | 10        | 0.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 2644      | 64.49%  |
| AMD                                  | 727       | 17.73%  |
| Nvidia                               | 480       | 11.71%  |
| C-Media Electronics                  | 26        | 0.63%   |
| Logitech                             | 25        | 0.61%   |
| Lenovo                               | 21        | 0.51%   |
| Silicon Integrated Systems [SiS]     | 15        | 0.37%   |
| Plantronics                          | 12        | 0.29%   |
| GN Netcom                            | 11        | 0.27%   |
| Texas Instruments                    | 9         | 0.22%   |
| Realtek Semiconductor                | 8         | 0.2%    |
| JMTek                                | 8         | 0.2%    |
| VIA Technologies                     | 7         | 0.17%   |
| ASUSTek Computer                     | 7         | 0.17%   |
| Apple                                | 7         | 0.17%   |
| SteelSeries ApS                      | 6         | 0.15%   |
| Kingston Technology                  | 6         | 0.15%   |
| Generalplus Technology               | 5         | 0.12%   |
| Corsair                              | 5         | 0.12%   |
| Hewlett-Packard                      | 4         | 0.1%    |
| Creative Technology                  | 4         | 0.1%    |
| BEHRINGER International              | 4         | 0.1%    |
| Sony                                 | 3         | 0.07%   |
| Sennheiser Communications            | 3         | 0.07%   |
| Dell                                 | 3         | 0.07%   |
| CMX Systems                          | 3         | 0.07%   |
| Trust                                | 2         | 0.05%   |
| Thesycon Systemsoftware & Consulting | 2         | 0.05%   |
| No brand                             | 2         | 0.05%   |
| Huawei Technologies                  | 2         | 0.05%   |
| Guillemot                            | 2         | 0.05%   |
| Conexant Systems                     | 2         | 0.05%   |
| Blue Microphones                     | 2         | 0.05%   |
| Alesis                               | 2         | 0.05%   |
| Vestax                               | 1         | 0.02%   |
| Veho                                 | 1         | 0.02%   |
| ThrustMaster                         | 1         | 0.02%   |
| Tenx Technology                      | 1         | 0.02%   |
| Silicon Motion                       | 1         | 0.02%   |
| Signalpath International             | 1         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 381       | 7.68%   |
| Intel Sunrise Point-LP HD Audio                                            | 331       | 6.67%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 189       | 3.81%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 179       | 3.61%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 172       | 3.47%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 166       | 3.35%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 154       | 3.1%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 152       | 3.06%   |
| Intel Haswell-ULT HD Audio Controller                                      | 147       | 2.96%   |
| Intel 8 Series HD Audio Controller                                         | 147       | 2.96%   |
| Intel Cannon Lake PCH cAVS                                                 | 140       | 2.82%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 115       | 2.32%   |
| Intel Comet Lake PCH-LP cAVS                                               | 109       | 2.2%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 109       | 2.2%    |
| Intel Broadwell-U Audio Controller                                         | 107       | 2.16%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 105       | 2.12%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 102       | 2.06%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 96        | 1.94%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 94        | 1.89%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 90        | 1.81%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 89        | 1.79%   |
| AMD FCH Azalia Controller                                                  | 82        | 1.65%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 78        | 1.57%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 65        | 1.31%   |
| AMD Kabini HDMI/DP Audio                                                   | 65        | 1.31%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 65        | 1.31%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 60        | 1.21%   |
| Intel Comet Lake PCH cAVS                                                  | 59        | 1.19%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 55        | 1.11%   |
| AMD High Definition Audio Controller                                       | 55        | 1.11%   |
| Nvidia GA106 High Definition Audio Controller                              | 51        | 1.03%   |
| Nvidia Audio device                                                        | 50        | 1.01%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 50        | 1.01%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 45        | 0.91%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 44        | 0.89%   |
| Nvidia TU106 High Definition Audio Controller                              | 43        | 0.87%   |
| Intel CM238 HD Audio Controller                                            | 42        | 0.85%   |
| Nvidia GP107GL High Definition Audio Controller                            | 41        | 0.83%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 37        | 0.75%   |
| Nvidia GF108 High Definition Audio Controller                              | 34        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 650       | 30.76%  |
| SK hynix                                         | 450       | 21.3%   |
| Micron Technology                                | 274       | 12.97%  |
| Kingston                                         | 195       | 9.23%   |
| Unknown                                          | 144       | 6.81%   |
| Crucial                                          | 105       | 4.97%   |
| Ramaxel Technology                               | 66        | 3.12%   |
| Unknown (ABCD)                                   | 34        | 1.61%   |
| Elpida                                           | 32        | 1.51%   |
| A-DATA Technology                                | 27        | 1.28%   |
| Nanya Technology                                 | 21        | 0.99%   |
| Corsair                                          | 18        | 0.85%   |
| G.Skill                                          | 14        | 0.66%   |
| Unknown                                          | 13        | 0.62%   |
| Silicon Power                                    | 11        | 0.52%   |
| GOODRAM                                          | 7         | 0.33%   |
| Transcend                                        | 5         | 0.24%   |
| Apacer                                           | 4         | 0.19%   |
| Wilk                                             | 3         | 0.14%   |
| Timetec                                          | 3         | 0.14%   |
| ChangXin Memory                                  | 3         | 0.14%   |
| Toshiba                                          | 2         | 0.09%   |
| Team                                             | 2         | 0.09%   |
| SHARETRONIC                                      | 2         | 0.09%   |
| Patriot                                          | 2         | 0.09%   |
| Micron/Elpida                                    | 2         | 0.09%   |
| KomputerBay                                      | 2         | 0.09%   |
| Kllisre                                          | 2         | 0.09%   |
| Avant                                            | 2         | 0.09%   |
| Unknown (0x202020202020202020202020202020202020) | 1         | 0.05%   |
| Unifosa                                          | 1         | 0.05%   |
| Qimonda                                          | 1         | 0.05%   |
| PUSKILL                                          | 1         | 0.05%   |
| PNY                                              | 1         | 0.05%   |
| Patriot Memory (PDP Systems)                     | 1         | 0.05%   |
| Netlist                                          | 1         | 0.05%   |
| Netac                                            | 1         | 0.05%   |
| Neo Forza                                        | 1         | 0.05%   |
| Kembona                                          | 1         | 0.05%   |
| Goldkey                                          | 1         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 36        | 1.63%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s              | 34        | 1.54%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 30        | 1.36%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 26        | 1.18%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 25        | 1.13%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 24        | 1.09%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 24        | 1.09%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 23        | 1.04%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 22        | 1%      |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 21        | 0.95%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 20        | 0.91%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 20        | 0.91%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 19        | 0.86%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 19        | 0.86%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 19        | 0.86%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 18        | 0.82%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 18        | 0.82%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 17        | 0.77%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s              | 17        | 0.77%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 16        | 0.73%   |
| SK hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s             | 15        | 0.68%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 15        | 0.68%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 15        | 0.68%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s              | 15        | 0.68%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 15        | 0.68%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 15        | 0.68%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 14        | 0.64%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 13        | 0.59%   |
| Unknown                                                             | 13        | 0.59%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 12        | 0.54%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 12        | 0.54%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 12        | 0.54%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s              | 12        | 0.54%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s               | 12        | 0.54%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s                | 12        | 0.54%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                | 12        | 0.54%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 12        | 0.54%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s             | 12        | 0.54%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s                | 11        | 0.5%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s          | 11        | 0.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 886       | 49.17%  |
| DDR3    | 528       | 29.3%   |
| LPDDR4  | 101       | 5.6%    |
| DDR2    | 98        | 5.44%   |
| LPDDR3  | 62        | 3.44%   |
| DDR5    | 39        | 2.16%   |
| SDRAM   | 36        | 2%      |
| LPDDR5  | 26        | 1.44%   |
| Unknown | 11        | 0.61%   |
| DDR     | 8         | 0.44%   |
| DRAM    | 7         | 0.39%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| SODIMM          | 1599      | 87.86%  |
| Row Of Chips    | 197       | 10.82%  |
| DIMM            | 11        | 0.6%    |
| Chip            | 10        | 0.55%   |
| Unknown         | 2         | 0.11%   |
| Proprietary Car | 1         | 0.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 812       | 41.49%  |
| 4096  | 499       | 25.5%   |
| 16384 | 313       | 15.99%  |
| 2048  | 212       | 10.83%  |
| 1024  | 66        | 3.37%   |
| 32768 | 45        | 2.3%    |
| 512   | 6         | 0.31%   |
| 256   | 3         | 0.15%   |
| 3072  | 1         | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 418       | 21.7%   |
| 2667    | 383       | 19.89%  |
| 1600    | 353       | 18.33%  |
| 2400    | 124       | 6.44%   |
| 1334    | 89        | 4.62%   |
| 2133    | 83        | 4.31%   |
| 667     | 67        | 3.48%   |
| 1333    | 61        | 3.17%   |
| Unknown | 44        | 2.28%   |
| 4800    | 35        | 1.82%   |
| 8400    | 34        | 1.77%   |
| 4267    | 32        | 1.66%   |
| 1067    | 28        | 1.45%   |
| 6400    | 27        | 1.4%    |
| 1867    | 21        | 1.09%   |
| 800     | 20        | 1.04%   |
| 3266    | 18        | 0.93%   |
| 2048    | 14        | 0.73%   |
| 533     | 12        | 0.62%   |
| 4266    | 11        | 0.57%   |
| 4199    | 11        | 0.57%   |
| 1066    | 10        | 0.52%   |
| 975     | 7         | 0.36%   |
| 5600    | 6         | 0.31%   |
| 3733    | 4         | 0.21%   |
| 2933    | 2         | 0.1%    |
| 1639    | 2         | 0.1%    |
| 1200    | 2         | 0.1%    |
| 3600    | 1         | 0.05%   |
| 3000    | 1         | 0.05%   |
| 2800    | 1         | 0.05%   |
| 1866    | 1         | 0.05%   |
| 1776    | 1         | 0.05%   |
| 666     | 1         | 0.05%   |
| 333     | 1         | 0.05%   |
| 266     | 1         | 0.05%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 17        | 53.13%  |
| Brother Industries | 7         | 21.88%  |
| Seiko Epson        | 4         | 12.5%   |
| Canon              | 4         | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Canon PIXMA MG2500 Series        | 3         | 9.38%   |
| HP Printing Support              | 2         | 6.25%   |
| HP LaserJet 1020                 | 2         | 6.25%   |
| HP DeskJet 2600 series           | 2         | 6.25%   |
| Brother HL-2030 Laser Printer    | 2         | 6.25%   |
| Seiko Epson XP-235 Series        | 1         | 3.13%   |
| Seiko Epson Printer              | 1         | 3.13%   |
| Seiko Epson L555 Series          | 1         | 3.13%   |
| Seiko Epson ET-2700 Series       | 1         | 3.13%   |
| HP PSC 1500 series               | 1         | 3.13%   |
| HP Officejet 7110 series         | 1         | 3.13%   |
| HP LaserJet Professional P 1102w | 1         | 3.13%   |
| HP LaserJet Pro M404-M405        | 1         | 3.13%   |
| HP LaserJet 1320                 | 1         | 3.13%   |
| HP LaserJet 1018                 | 1         | 3.13%   |
| HP LaserJet 1000                 | 1         | 3.13%   |
| HP HP LaserJet M14-M17           | 1         | 3.13%   |
| HP DeskJet F300 series           | 1         | 3.13%   |
| HP DeskJet F2492 All-in-One      | 1         | 3.13%   |
| HP Deskjet 2050 J510             | 1         | 3.13%   |
| Canon TS3100 series              | 1         | 3.13%   |
| Brother MFC-J5330DW              | 1         | 3.13%   |
| Brother HL-L3270CDW series       | 1         | 3.13%   |
| Brother HL-2240D series          | 1         | 3.13%   |
| Brother HL-1210W series          | 1         | 3.13%   |
| Brother DCP-L2520DW              | 1         | 3.13%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 4         | 80%     |
| Hewlett-Packard | 1         | 20%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Canon CanoScan LiDE 210       | 2         | 40%     |
| HP ScanJet 4300c              | 1         | 20%     |
| Canon CanoScan N1240U/LiDE 30 | 1         | 20%     |
| Canon CanoScan LiDE 220       | 1         | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 727       | 24.99%  |
| IMC Networks                           | 362       | 12.44%  |
| Bison Electronics                      | 214       | 7.36%   |
| Microdia                               | 191       | 6.57%   |
| Realtek Semiconductor                  | 180       | 6.19%   |
| Quanta                                 | 162       | 5.57%   |
| Suyin                                  | 127       | 4.37%   |
| Sunplus Innovation Technology          | 121       | 4.16%   |
| Cheng Uei Precision Industry (Foxlink) | 120       | 4.13%   |
| Acer                                   | 101       | 3.47%   |
| Syntek                                 | 82        | 2.82%   |
| Apple                                  | 57        | 1.96%   |
| Alcor Micro                            | 56        | 1.93%   |
| Lite-On Technology                     | 46        | 1.58%   |
| Luxvisions Innotech Limited            | 45        | 1.55%   |
| Ricoh                                  | 36        | 1.24%   |
| Logitech                               | 35        | 1.2%    |
| Sonix Technology                       | 27        | 0.93%   |
| Silicon Motion                         | 25        | 0.86%   |
| Samsung Electronics                    | 16        | 0.55%   |
| USB Camera                             | 13        | 0.45%   |
| Importek                               | 13        | 0.45%   |
| Lenovo                                 | 12        | 0.41%   |
| ALi                                    | 10        | 0.34%   |
| Z-Star Microelectronics                | 9         | 0.31%   |
| Sunplus Technology                     | 8         | 0.28%   |
| Intel                                  | 8         | 0.28%   |
| GEMBIRD                                | 8         | 0.28%   |
| DigiTech                               | 8         | 0.28%   |
| Primax Electronics                     | 7         | 0.24%   |
| SunplusIT                              | 6         | 0.21%   |
| Genesys Logic                          | 6         | 0.21%   |
| OmniVision Technologies                | 5         | 0.17%   |
| KYE Systems (Mouse Systems)            | 5         | 0.17%   |
| Trust                                  | 4         | 0.14%   |
| Shinetech                              | 4         | 0.14%   |
| Creative Technology                    | 4         | 0.14%   |
| ARC International                      | 4         | 0.14%   |
| webcamvendor                           | 3         | 0.1%    |
| Generalplus Technology                 | 3         | 0.1%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                       | 100       | 3.43%   |
| Chicony Integrated Camera                               | 90        | 3.09%   |
| Chicony HD WebCam                                       | 84        | 2.88%   |
| Microdia Integrated_Webcam_HD                           | 76        | 2.61%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 73        | 2.5%    |
| IMC Networks Integrated Camera                          | 64        | 2.19%   |
| Bison Integrated Camera                                 | 48        | 1.65%   |
| Bison HD Webcam                                         | 47        | 1.61%   |
| Chicony USB2.0 VGA UVC WebCam                           | 45        | 1.54%   |
| Realtek Integrated_Webcam_HD                            | 37        | 1.27%   |
| Realtek USB Camera                                      | 36        | 1.23%   |
| Quanta HP TrueVision HD Camera                          | 36        | 1.23%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 34        | 1.17%   |
| Sunplus HD WebCam                                       | 32        | 1.1%    |
| Syntek Integrated Camera                                | 29        | 0.99%   |
| Chicony TOSHIBA Web Camera - HD                         | 29        | 0.99%   |
| Acer HD Webcam                                          | 29        | 0.99%   |
| Chicony USB 2.0 Camera                                  | 27        | 0.93%   |
| Chicony HP TrueVision HD Camera                         | 27        | 0.93%   |
| Chicony EasyCamera                                      | 26        | 0.89%   |
| Chicony USB2.0 HD UVC WebCam                            | 24        | 0.82%   |
| Bison Lenovo EasyCamera                                 | 23        | 0.79%   |
| Sonix USB2.0 HD UVC WebCam                              | 22        | 0.75%   |
| Alcor Micro USB 2.0 Camera                              | 22        | 0.75%   |
| Realtek Lenovo EasyCamera                               | 21        | 0.72%   |
| Chicony HP TrueVision HD                                | 21        | 0.72%   |
| Acer Integrated Camera                                  | 21        | 0.72%   |
| Microdia Webcam Vitade AF                               | 20        | 0.69%   |
| Lite-On Integrated Camera                               | 20        | 0.69%   |
| IMC Networks ov9734_azurewave_camera                    | 20        | 0.69%   |
| Chicony USB2.0 Camera                                   | 20        | 0.69%   |
| Bison HD Camera                                         | 20        | 0.69%   |
| Apple FaceTime HD Camera                                | 20        | 0.69%   |
| Syntek Lenovo EasyCamera                                | 19        | 0.65%   |
| Syntek EasyCamera                                       | 19        | 0.65%   |
| Chicony VGA Webcam                                      | 19        | 0.65%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 19        | 0.65%   |
| Apple Built-in iSight                                   | 19        | 0.65%   |
| Alcor Micro Asus Integrated Webcam                      | 19        | 0.65%   |
| Quanta HP Wide Vision HD Camera                         | 18        | 0.62%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 130       | 28.2%   |
| Validity Sensors                   | 109       | 23.64%  |
| Shenzhen Goodix Technology         | 83        | 18%     |
| AuthenTec                          | 45        | 9.76%   |
| Elan Microelectronics              | 43        | 9.33%   |
| Upek                               | 28        | 6.07%   |
| LighTuning Technology              | 12        | 2.6%    |
| STMicroelectronics                 | 7         | 1.52%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 0.65%   |
| Focal-systems.Corp                 | 1         | 0.22%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 65        | 14.1%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 44        | 9.54%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 36        | 7.81%   |
| Elan ELAN:Fingerprint                                                      | 36        | 7.81%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 23        | 4.99%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 21        | 4.56%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 18        | 3.9%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 14        | 3.04%   |
| Shenzhen Goodix Fingerprint Reader                                         | 14        | 3.04%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 12        | 2.6%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 10        | 2.17%   |
| Validity Sensors Synaptics WBDI                                            | 9         | 1.95%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 9         | 1.95%   |
| AuthenTec Fingerprint Sensor                                               | 9         | 1.95%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 8         | 1.74%   |
| AuthenTec AES1600                                                          | 8         | 1.74%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 7         | 1.52%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 1.52%   |
| Elan ELAN:ARM-M4                                                           | 7         | 1.52%   |
| Validity Sensors VFS491                                                    | 6         | 1.3%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 6         | 1.3%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 1.3%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 6         | 1.3%    |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 6         | 1.3%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 6         | 1.3%    |
| AuthenTec AES2810                                                          | 6         | 1.3%    |
| AuthenTec AES2550 Fingerprint Sensor                                       | 6         | 1.3%    |
| Upek TCS5B Fingerprint sensor                                              | 5         | 1.08%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 0.87%   |
| Validity Sensors Fingerprint scanner                                       | 4         | 0.87%   |
| Synaptics UWP WBDI Device                                                  | 4         | 0.87%   |
| Synaptics  WBDI                                                            | 4         | 0.87%   |
| Synaptics Fingerprint reader [HP G6]                                       | 4         | 0.87%   |
| Shenzhen Goodix FingerPrint                                                | 4         | 0.87%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 0.87%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 4         | 0.87%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 0.65%   |
| Synaptics WBDI                                                             | 3         | 0.65%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 3         | 0.65%   |
| Synaptics UWP WBDI                                                         | 2         | 0.43%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 70        | 36.27%  |
| Broadcom              | 63        | 32.64%  |
| O2 Micro              | 26        | 13.47%  |
| Lenovo                | 10        | 5.18%   |
| Upek                  | 6         | 3.11%   |
| Cherry                | 4         | 2.07%   |
| C3PO                  | 4         | 2.07%   |
| Realtek Semiconductor | 3         | 1.55%   |
| Gemalto (was Gemplus) | 3         | 1.55%   |
| Advanced Card Systems | 2         | 1.04%   |
| In Focus Systems      | 1         | 0.52%   |
| Chicony Electronics   | 1         | 0.52%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 70        | 36.27%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 25        | 12.95%  |
| Broadcom BCM5880 Secure Applications Processor                               | 20        | 10.36%  |
| Broadcom 5880                                                                | 18        | 9.33%   |
| Broadcom 58200                                                               | 13        | 6.74%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 11        | 5.7%    |
| Lenovo Integrated Smart Card Reader                                          | 10        | 5.18%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 6         | 3.11%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 3         | 1.55%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 1.55%   |
| Cherry SmartTerminal XX1X                                                    | 3         | 1.55%   |
| C3PO LTC31v2                                                                 | 3         | 1.55%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 2         | 1.04%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.52%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.52%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.52%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.52%   |
| C3PO USB SMART CARD READER                                                   | 1         | 0.52%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.52%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 2206      | 63.7%   |
| 1     | 962       | 27.78%  |
| 2     | 240       | 6.93%   |
| 3     | 36        | 1.04%   |
| 4     | 11        | 0.32%   |
| 5     | 5         | 0.14%   |
| 6     | 2         | 0.06%   |
| 8     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 451       | 28.85%  |
| Graphics card            | 377       | 24.12%  |
| Net/wireless             | 205       | 13.12%  |
| Chipcard                 | 168       | 10.75%  |
| Multimedia controller    | 107       | 6.85%   |
| Camera                   | 64        | 4.09%   |
| Bluetooth                | 45        | 2.88%   |
| Storage                  | 30        | 1.92%   |
| Communication controller | 27        | 1.73%   |
| Card reader              | 22        | 1.41%   |
| Sound                    | 17        | 1.09%   |
| Net/ethernet             | 13        | 0.83%   |
| Flash memory             | 11        | 0.7%    |
| Network                  | 10        | 0.64%   |
| Modem                    | 9         | 0.58%   |
| Dvb card                 | 4         | 0.26%   |
| Storage/ide              | 2         | 0.13%   |
| Storage/raid             | 1         | 0.06%   |

