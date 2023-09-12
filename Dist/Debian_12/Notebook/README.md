Debian 12 - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Debian 12.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 770

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [0468bc91fc](https://linux-hardware.org/?probe=0468bc91fc) | Sep 06, 2023 |
| ASUSTek       | X542UQ                      | [50ecc5159c](https://linux-hardware.org/?probe=50ecc5159c) | Sep 06, 2023 |
| ASUSTek       | X542UQ                      | [b34e0e7866](https://linux-hardware.org/?probe=b34e0e7866) | Sep 06, 2023 |
| Acer          | Aspire E1-531               | [9d5880bc6c](https://linux-hardware.org/?probe=9d5880bc6c) | Sep 06, 2023 |
| Acer          | Aspire E1-531               | [6ffc334cf9](https://linux-hardware.org/?probe=6ffc334cf9) | Sep 06, 2023 |
| HP            | ZBook 15 G3                 | [faac131992](https://linux-hardware.org/?probe=faac131992) | Sep 05, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [1bcf7b95c6](https://linux-hardware.org/?probe=1bcf7b95c6) | Sep 05, 2023 |
| Lenovo        | ThinkPad T490 20N2001YUS    | [75c15ac2e8](https://linux-hardware.org/?probe=75c15ac2e8) | Sep 05, 2023 |
| ASUSTek       | K53SD                       | [051fefc7ca](https://linux-hardware.org/?probe=051fefc7ca) | Sep 05, 2023 |
| Sony          | VGN-CS108D                  | [24bf5bb06c](https://linux-hardware.org/?probe=24bf5bb06c) | Sep 05, 2023 |
| HUAWEI        | NBD-WXX9                    | [005ebd39ce](https://linux-hardware.org/?probe=005ebd39ce) | Sep 05, 2023 |
| ASUSTek       | X541NC                      | [927ba04557](https://linux-hardware.org/?probe=927ba04557) | Sep 05, 2023 |
| Acer          | Aspire E1-531               | [7f9460a97c](https://linux-hardware.org/?probe=7f9460a97c) | Sep 04, 2023 |
| eMachines     | Rhine V1.42                 | [c18c4d64bd](https://linux-hardware.org/?probe=c18c4d64bd) | Sep 04, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [f7a6b9d479](https://linux-hardware.org/?probe=f7a6b9d479) | Sep 04, 2023 |
| ASUSTek       | X507UB                      | [e74c3ad568](https://linux-hardware.org/?probe=e74c3ad568) | Sep 03, 2023 |
| Dell          | Latitude 5414               | [704d861366](https://linux-hardware.org/?probe=704d861366) | Sep 03, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [526a6826ab](https://linux-hardware.org/?probe=526a6826ab) | Sep 03, 2023 |
| Google        | Droid                       | [da26431a82](https://linux-hardware.org/?probe=da26431a82) | Sep 03, 2023 |
| Google        | Droid                       | [278861e9e8](https://linux-hardware.org/?probe=278861e9e8) | Sep 03, 2023 |
| Acer          | Aspire A515-56              | [435cb2d610](https://linux-hardware.org/?probe=435cb2d610) | Sep 03, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [7ba8b58ea7](https://linux-hardware.org/?probe=7ba8b58ea7) | Sep 03, 2023 |
| Toshiba       | Satellite L10W-B-101        | [1865cdf1ad](https://linux-hardware.org/?probe=1865cdf1ad) | Sep 02, 2023 |
| HP            | ZBook 15 G2                 | [d20f8f324d](https://linux-hardware.org/?probe=d20f8f324d) | Sep 02, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [d00f64dfcf](https://linux-hardware.org/?probe=d00f64dfcf) | Sep 02, 2023 |
| Samsung       | RF511/RF411/RF711           | [ab39767c20](https://linux-hardware.org/?probe=ab39767c20) | Sep 02, 2023 |
| Lenovo        | G505 20240                  | [ea15ab596a](https://linux-hardware.org/?probe=ea15ab596a) | Sep 02, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [155023d91f](https://linux-hardware.org/?probe=155023d91f) | Sep 02, 2023 |
| Lenovo        | Legion 5 15ACH6 82QJ        | [5897684d9e](https://linux-hardware.org/?probe=5897684d9e) | Sep 02, 2023 |
| Dell          | Latitude 5430               | [7a9eb9995d](https://linux-hardware.org/?probe=7a9eb9995d) | Sep 02, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | [52e8a720ba](https://linux-hardware.org/?probe=52e8a720ba) | Sep 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [062f19958d](https://linux-hardware.org/?probe=062f19958d) | Sep 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [af78cafb1a](https://linux-hardware.org/?probe=af78cafb1a) | Sep 01, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [f98a2afc33](https://linux-hardware.org/?probe=f98a2afc33) | Aug 31, 2023 |
| Acer          | Swift SF314-42              | [80bebab849](https://linux-hardware.org/?probe=80bebab849) | Aug 31, 2023 |
| Google        | Enguarde                    | [d67a18c110](https://linux-hardware.org/?probe=d67a18c110) | Aug 30, 2023 |
| GPU Compan... | GWTN156-9                   | [4c8ea16ab2](https://linux-hardware.org/?probe=4c8ea16ab2) | Aug 30, 2023 |
| HP            | Laptop 15s-fq2xxx           | [6d85c1d397](https://linux-hardware.org/?probe=6d85c1d397) | Aug 30, 2023 |
| Acer          | Aspire A515-57              | [c9a61f810d](https://linux-hardware.org/?probe=c9a61f810d) | Aug 30, 2023 |
| Google        | Enguarde                    | [08ff2764b2](https://linux-hardware.org/?probe=08ff2764b2) | Aug 30, 2023 |
| Unknown       | Unknown                     | [3718299cea](https://linux-hardware.org/?probe=3718299cea) | Aug 29, 2023 |
| Google        | Enguarde                    | [e2e5a3dadc](https://linux-hardware.org/?probe=e2e5a3dadc) | Aug 29, 2023 |
| Google        | Enguarde                    | [e7a59ac286](https://linux-hardware.org/?probe=e7a59ac286) | Aug 29, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [4bdfa8b9ea](https://linux-hardware.org/?probe=4bdfa8b9ea) | Aug 29, 2023 |
| HP            | EliteBook 845 14 inch G9... | [41ce572b6d](https://linux-hardware.org/?probe=41ce572b6d) | Aug 29, 2023 |
| Acer          | Swift SF314-512             | [a41a08d4ae](https://linux-hardware.org/?probe=a41a08d4ae) | Aug 29, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [62ff88eaf7](https://linux-hardware.org/?probe=62ff88eaf7) | Aug 29, 2023 |
| Lenovo        | ThinkPad E470 20H2S00700    | [cea73826dc](https://linux-hardware.org/?probe=cea73826dc) | Aug 28, 2023 |
| win elemen... | MoreFine S500+              | [9675488adc](https://linux-hardware.org/?probe=9675488adc) | Aug 28, 2023 |
| win elemen... | MoreFine S500+              | [29e062fb36](https://linux-hardware.org/?probe=29e062fb36) | Aug 27, 2023 |
| Apple         | MacBookPro6,2               | [e25e18e9b1](https://linux-hardware.org/?probe=e25e18e9b1) | Aug 27, 2023 |
| Lenovo        | B590 20208                  | [65bf0970da](https://linux-hardware.org/?probe=65bf0970da) | Aug 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X760... | [5ef3048a11](https://linux-hardware.org/?probe=5ef3048a11) | Aug 26, 2023 |
| Dell          | Latitude E6420              | [ae48a8c618](https://linux-hardware.org/?probe=ae48a8c618) | Aug 26, 2023 |
| MSI           | GP76 Leopard 11UG           | [5de726089b](https://linux-hardware.org/?probe=5de726089b) | Aug 26, 2023 |
| Alienware     | m16 R1                      | [75f20a1519](https://linux-hardware.org/?probe=75f20a1519) | Aug 26, 2023 |
| Alienware     | m16 R1                      | [89cffc75ea](https://linux-hardware.org/?probe=89cffc75ea) | Aug 26, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [4ca70b63ef](https://linux-hardware.org/?probe=4ca70b63ef) | Aug 25, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [c288ff6b78](https://linux-hardware.org/?probe=c288ff6b78) | Aug 25, 2023 |
| MSI           | GS65 Stealth Thin 8RE       | [b53212efce](https://linux-hardware.org/?probe=b53212efce) | Aug 24, 2023 |
| Acer          | Aspire 7741                 | [648f667e11](https://linux-hardware.org/?probe=648f667e11) | Aug 24, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | [4d1d53f6d8](https://linux-hardware.org/?probe=4d1d53f6d8) | Aug 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [5a6247f9b2](https://linux-hardware.org/?probe=5a6247f9b2) | Aug 24, 2023 |
| HP            | Laptop 17-by4xxx            | [9fd582b91e](https://linux-hardware.org/?probe=9fd582b91e) | Aug 24, 2023 |
| HP            | ZBook 14 G2                 | [fcbebfc95a](https://linux-hardware.org/?probe=fcbebfc95a) | Aug 23, 2023 |
| Acer          | Aspire ES1-311              | [93f204808e](https://linux-hardware.org/?probe=93f204808e) | Aug 23, 2023 |
| Panasonic     | CFMX4-1                     | [fd352acae8](https://linux-hardware.org/?probe=fd352acae8) | Aug 23, 2023 |
| Acer          | TravelMate P214-52          | [6d7eeef62a](https://linux-hardware.org/?probe=6d7eeef62a) | Aug 23, 2023 |
| MSI           | Stealth 17Studio A13VF      | [ca952946e9](https://linux-hardware.org/?probe=ca952946e9) | Aug 23, 2023 |
| ASUSTek       | X507UB                      | [6c8e9739d4](https://linux-hardware.org/?probe=6c8e9739d4) | Aug 23, 2023 |
| Positivo      | Mobile                      | [e39dbd02a9](https://linux-hardware.org/?probe=e39dbd02a9) | Aug 22, 2023 |
| ASUSTek       | ZenBook UX425UG_Q408UG      | [8b219ffa3b](https://linux-hardware.org/?probe=8b219ffa3b) | Aug 22, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [b460d0aa2d](https://linux-hardware.org/?probe=b460d0aa2d) | Aug 22, 2023 |
| Samsung       | 905S3G/906S3G/915S3G        | [ae599c9d4b](https://linux-hardware.org/?probe=ae599c9d4b) | Aug 22, 2023 |
| ASUSTek       | ROG Strix G531GU_G531GU     | [627606b933](https://linux-hardware.org/?probe=627606b933) | Aug 22, 2023 |
| HP            | Laptop 15z-ef3xxx           | [cf603a20c0](https://linux-hardware.org/?probe=cf603a20c0) | Aug 22, 2023 |
| Sony          | SVE14123CBW                 | [b7891b51b2](https://linux-hardware.org/?probe=b7891b51b2) | Aug 21, 2023 |
| Sony          | SVE14123CBW                 | [9730d7f8f5](https://linux-hardware.org/?probe=9730d7f8f5) | Aug 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [0baece8878](https://linux-hardware.org/?probe=0baece8878) | Aug 21, 2023 |
| Dell          | Inspiron 15 3515            | [534e1dc3e5](https://linux-hardware.org/?probe=534e1dc3e5) | Aug 21, 2023 |
| Sony          | VPCEH2J9R                   | [a919beee79](https://linux-hardware.org/?probe=a919beee79) | Aug 21, 2023 |
| Acer          | Aspire A517-53G             | [692bd3fa37](https://linux-hardware.org/?probe=692bd3fa37) | Aug 20, 2023 |
| Acer          | Aspire A517-53G             | [6313b3f69e](https://linux-hardware.org/?probe=6313b3f69e) | Aug 20, 2023 |
| Dell          | Latitude E5550              | [0f3afef2ac](https://linux-hardware.org/?probe=0f3afef2ac) | Aug 20, 2023 |
| EUROCOM       | RACER 2.0                   | [b27f687c16](https://linux-hardware.org/?probe=b27f687c16) | Aug 20, 2023 |
| Acer          | Aspire A515-56              | [501ee4caf7](https://linux-hardware.org/?probe=501ee4caf7) | Aug 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [ab5bc08964](https://linux-hardware.org/?probe=ab5bc08964) | Aug 19, 2023 |
| Dell          | Vostro 3501                 | [5369c283ad](https://linux-hardware.org/?probe=5369c283ad) | Aug 18, 2023 |
| Acer          | Extensa 5235                | [1dc9843f33](https://linux-hardware.org/?probe=1dc9843f33) | Aug 18, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [95c536cff4](https://linux-hardware.org/?probe=95c536cff4) | Aug 18, 2023 |
| ASUSTek       | M3N                         | [7c4b9386db](https://linux-hardware.org/?probe=7c4b9386db) | Aug 18, 2023 |
| Lenovo        | ThinkPad T430s 2355C33      | [4c589a0320](https://linux-hardware.org/?probe=4c589a0320) | Aug 18, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [e66c463188](https://linux-hardware.org/?probe=e66c463188) | Aug 18, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [55b9d87888](https://linux-hardware.org/?probe=55b9d87888) | Aug 18, 2023 |
| HP            | Laptop 15-dy0xxx            | [f938725821](https://linux-hardware.org/?probe=f938725821) | Aug 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [748298f0c8](https://linux-hardware.org/?probe=748298f0c8) | Aug 18, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [24a295f95b](https://linux-hardware.org/?probe=24a295f95b) | Aug 17, 2023 |
| Lenovo        | ThinkPad X220 4291MW5       | [adf4aceec8](https://linux-hardware.org/?probe=adf4aceec8) | Aug 17, 2023 |
| HP            | Laptop 15s-eq2xxx           | [c647987aaf](https://linux-hardware.org/?probe=c647987aaf) | Aug 16, 2023 |
| Acer          | Aspire A515-52G             | [2d38a6554a](https://linux-hardware.org/?probe=2d38a6554a) | Aug 16, 2023 |
| Lenovo        | G505s 20255                 | [2486dc323f](https://linux-hardware.org/?probe=2486dc323f) | Aug 16, 2023 |
| Lenovo        | ThinkPad L580 20LW000WGE    | [69e443b8a8](https://linux-hardware.org/?probe=69e443b8a8) | Aug 16, 2023 |
| Google        | Phaser360                   | [3c248cc2c8](https://linux-hardware.org/?probe=3c248cc2c8) | Aug 16, 2023 |
| Dell          | Vostro 3501                 | [c36d4d9de0](https://linux-hardware.org/?probe=c36d4d9de0) | Aug 15, 2023 |
| Acer          | Aspire A315-59              | [901f34e440](https://linux-hardware.org/?probe=901f34e440) | Aug 15, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [268eeb2657](https://linux-hardware.org/?probe=268eeb2657) | Aug 15, 2023 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | [6242833326](https://linux-hardware.org/?probe=6242833326) | Aug 15, 2023 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | [22252eb1d9](https://linux-hardware.org/?probe=22252eb1d9) | Aug 15, 2023 |
| Alienware     | m15 R4                      | [40d4ad1e4f](https://linux-hardware.org/?probe=40d4ad1e4f) | Aug 14, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [72e71d1afc](https://linux-hardware.org/?probe=72e71d1afc) | Aug 14, 2023 |
| MSI           | Z790 GAMING WIFI            | [95e340d91b](https://linux-hardware.org/?probe=95e340d91b) | Aug 14, 2023 |
| Beelink       | Gemini X                    | [1610652627](https://linux-hardware.org/?probe=1610652627) | Aug 14, 2023 |
| Google        | Blooglet                    | [b9967e65c2](https://linux-hardware.org/?probe=b9967e65c2) | Aug 14, 2023 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | [57af1d89d6](https://linux-hardware.org/?probe=57af1d89d6) | Aug 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [ab5728ee52](https://linux-hardware.org/?probe=ab5728ee52) | Aug 13, 2023 |
| ASUSTek       | GL552VW                     | [1d77ac2450](https://linux-hardware.org/?probe=1d77ac2450) | Aug 13, 2023 |
| HP            | Pavilion dv5                | [78530d4418](https://linux-hardware.org/?probe=78530d4418) | Aug 13, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [b0524c4203](https://linux-hardware.org/?probe=b0524c4203) | Aug 13, 2023 |
| ASUSTek       | GL552VW                     | [6986ca63da](https://linux-hardware.org/?probe=6986ca63da) | Aug 12, 2023 |
| Dell          | Latitude E6430              | [8037585070](https://linux-hardware.org/?probe=8037585070) | Aug 12, 2023 |
| HP            | ZBook 17 G3                 | [475b07d2dc](https://linux-hardware.org/?probe=475b07d2dc) | Aug 12, 2023 |
| Unknown       | Unknown                     | [8d7674c3b3](https://linux-hardware.org/?probe=8d7674c3b3) | Aug 11, 2023 |
| HP            | Pavilion dv5                | [41c7682f98](https://linux-hardware.org/?probe=41c7682f98) | Aug 11, 2023 |
| HP            | Pavilion dv5                | [a8f62e42dc](https://linux-hardware.org/?probe=a8f62e42dc) | Aug 11, 2023 |
| Unknown       | Unknown                     | [a064a2d5fd](https://linux-hardware.org/?probe=a064a2d5fd) | Aug 11, 2023 |
| Dell          | Inspiron 3531               | [0384e8a950](https://linux-hardware.org/?probe=0384e8a950) | Aug 11, 2023 |
| Avell High... | A40 LIV                     | [9bc62c7eec](https://linux-hardware.org/?probe=9bc62c7eec) | Aug 11, 2023 |
| HP            | Laptop 15s-eq2xxx           | [e45562b838](https://linux-hardware.org/?probe=e45562b838) | Aug 10, 2023 |
| PC Special... | NH5xAx                      | [891b5ec398](https://linux-hardware.org/?probe=891b5ec398) | Aug 10, 2023 |
| Lenovo        | ThinkPad T410 25372E6       | [69c4723b51](https://linux-hardware.org/?probe=69c4723b51) | Aug 10, 2023 |
| Lenovo        | ThinkPad T480 20L6S29D00    | [a728658683](https://linux-hardware.org/?probe=a728658683) | Aug 10, 2023 |
| HP            | Laptop 15s-eq2xxx           | [c87b299407](https://linux-hardware.org/?probe=c87b299407) | Aug 10, 2023 |
| Acer          | Aspire A515-57              | [b95e28ab5d](https://linux-hardware.org/?probe=b95e28ab5d) | Aug 09, 2023 |
| Lenovo        | G460 20041                  | [709445c691](https://linux-hardware.org/?probe=709445c691) | Aug 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [72655a5d65](https://linux-hardware.org/?probe=72655a5d65) | Aug 08, 2023 |
| Dell          | Inspiron 7537               | [61093a9af1](https://linux-hardware.org/?probe=61093a9af1) | Aug 08, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [965f96493c](https://linux-hardware.org/?probe=965f96493c) | Aug 08, 2023 |
| HONOR         | HYM-WXX                     | [6f5e2be121](https://linux-hardware.org/?probe=6f5e2be121) | Aug 08, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [c06b23398a](https://linux-hardware.org/?probe=c06b23398a) | Aug 08, 2023 |
| Avell High... | A40 LIV                     | [4022d66d9a](https://linux-hardware.org/?probe=4022d66d9a) | Aug 08, 2023 |
| Lenovo        | ThinkPad T530 2394EN6       | [d348a65379](https://linux-hardware.org/?probe=d348a65379) | Aug 07, 2023 |
| Echips Imp... | NQ15E                       | [7d5e97a545](https://linux-hardware.org/?probe=7d5e97a545) | Aug 07, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [36c52dfe36](https://linux-hardware.org/?probe=36c52dfe36) | Aug 07, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [543719cf07](https://linux-hardware.org/?probe=543719cf07) | Aug 07, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [be823adc05](https://linux-hardware.org/?probe=be823adc05) | Aug 07, 2023 |
| Acer          | Aspire V5-121               | [4b8b0f132d](https://linux-hardware.org/?probe=4b8b0f132d) | Aug 07, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E02    | [a3e3489451](https://linux-hardware.org/?probe=a3e3489451) | Aug 07, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [7e185ae211](https://linux-hardware.org/?probe=7e185ae211) | Aug 07, 2023 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [053d461635](https://linux-hardware.org/?probe=053d461635) | Aug 06, 2023 |
| Apple         | MacBook7,1                  | [38d285144e](https://linux-hardware.org/?probe=38d285144e) | Aug 06, 2023 |
| Lenovo        | ThinkPad T440s 20AQ005TU... | [55e9e43f37](https://linux-hardware.org/?probe=55e9e43f37) | Aug 06, 2023 |
| HP            | Presario CQ57               | [cd84f6fa01](https://linux-hardware.org/?probe=cd84f6fa01) | Aug 06, 2023 |
| GPU Compan... | GWNR71517                   | [d754d51977](https://linux-hardware.org/?probe=d754d51977) | Aug 06, 2023 |
| Dell          | Latitude E5440              | [326ba9627a](https://linux-hardware.org/?probe=326ba9627a) | Aug 06, 2023 |
| HP            | EliteBook 840 G3            | [9c2b1b1da7](https://linux-hardware.org/?probe=9c2b1b1da7) | Aug 06, 2023 |
| Acer          | Aspire E5-553G              | [39140ff7de](https://linux-hardware.org/?probe=39140ff7de) | Aug 05, 2023 |
| Acer          | Aspire A315-59              | [fc1d6007aa](https://linux-hardware.org/?probe=fc1d6007aa) | Aug 05, 2023 |
| Acer          | Aspire A315-59              | [deff4c99b6](https://linux-hardware.org/?probe=deff4c99b6) | Aug 05, 2023 |
| HUAWEI        | MACHD-WXX9                  | [8511f4c245](https://linux-hardware.org/?probe=8511f4c245) | Aug 05, 2023 |
| Sony          | VGN-NS11S_S                 | [8ad31bd20c](https://linux-hardware.org/?probe=8ad31bd20c) | Aug 05, 2023 |
| Shuttle       | DS47D                       | [7d1ceb9b3a](https://linux-hardware.org/?probe=7d1ceb9b3a) | Aug 05, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [76662ba2c9](https://linux-hardware.org/?probe=76662ba2c9) | Aug 05, 2023 |
| Dell          | Latitude E6400              | [ca61145546](https://linux-hardware.org/?probe=ca61145546) | Aug 04, 2023 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | [12948b89f6](https://linux-hardware.org/?probe=12948b89f6) | Aug 04, 2023 |
| HP            | ProBook 640 G2              | [7cacb46425](https://linux-hardware.org/?probe=7cacb46425) | Aug 04, 2023 |
| Dell          | XPS 9320                    | [140f8f8b2e](https://linux-hardware.org/?probe=140f8f8b2e) | Aug 04, 2023 |
| Sony          | VGN-FW373D                  | [535f0edf33](https://linux-hardware.org/?probe=535f0edf33) | Aug 04, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [51ad22a795](https://linux-hardware.org/?probe=51ad22a795) | Aug 03, 2023 |
| Dell          | Vostro 3405                 | [db4954c21d](https://linux-hardware.org/?probe=db4954c21d) | Aug 03, 2023 |
| Lenovo        | ThinkPad T480 20L6S5LF00    | [6bc628f4e6](https://linux-hardware.org/?probe=6bc628f4e6) | Aug 03, 2023 |
| Google        | Enguarde                    | [663e44ce58](https://linux-hardware.org/?probe=663e44ce58) | Aug 03, 2023 |
| Acer          | Nitro AN515-57              | [cef74aa3cb](https://linux-hardware.org/?probe=cef74aa3cb) | Aug 03, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | [1317097350](https://linux-hardware.org/?probe=1317097350) | Aug 03, 2023 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [8036065591](https://linux-hardware.org/?probe=8036065591) | Aug 03, 2023 |
| Samsung       | 305U1A                      | [f65d34a8fb](https://linux-hardware.org/?probe=f65d34a8fb) | Aug 03, 2023 |
| ASUSTek       | 1015BX                      | [4770dbfc22](https://linux-hardware.org/?probe=4770dbfc22) | Aug 02, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [a1f99c3e4d](https://linux-hardware.org/?probe=a1f99c3e4d) | Aug 02, 2023 |
| HP            | EliteBook 840 G3            | [0ae0b35097](https://linux-hardware.org/?probe=0ae0b35097) | Aug 02, 2023 |
| Dell          | Vostro 5515                 | [0e031a4729](https://linux-hardware.org/?probe=0e031a4729) | Aug 02, 2023 |
| HP            | Laptop 15s-eq2xxx           | [2d046d70cc](https://linux-hardware.org/?probe=2d046d70cc) | Aug 02, 2023 |
| Samsung       | 300E5M/300E5L               | [d4c5149060](https://linux-hardware.org/?probe=d4c5149060) | Aug 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [291bf82303](https://linux-hardware.org/?probe=291bf82303) | Aug 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [7a9c57ad84](https://linux-hardware.org/?probe=7a9c57ad84) | Aug 02, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [dfb33be517](https://linux-hardware.org/?probe=dfb33be517) | Aug 01, 2023 |
| HP            | EliteBook 840 G3            | [b53d4c2fad](https://linux-hardware.org/?probe=b53d4c2fad) | Aug 01, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [d3250ef8d7](https://linux-hardware.org/?probe=d3250ef8d7) | Aug 01, 2023 |
| Timi          | Xiaomi Book Pro 16 2022     | [1e963cc76b](https://linux-hardware.org/?probe=1e963cc76b) | Aug 01, 2023 |
| ASUSTek       | G750JX                      | [06279baf34](https://linux-hardware.org/?probe=06279baf34) | Aug 01, 2023 |
| Samsung       | 305E4Z/305E5Z/305E7Z        | [a9232da3e4](https://linux-hardware.org/?probe=a9232da3e4) | Jul 31, 2023 |
| Lenovo        | Flex 2-14 20404             | [dd24507513](https://linux-hardware.org/?probe=dd24507513) | Jul 31, 2023 |
| HP            | ProBook 640 G2              | [9e297e7c8e](https://linux-hardware.org/?probe=9e297e7c8e) | Jul 31, 2023 |
| Dell          | Inspiron 15 3511            | [3ea3ff2535](https://linux-hardware.org/?probe=3ea3ff2535) | Jul 31, 2023 |
| Apple         | MacBookAir3,1               | [1859204a6f](https://linux-hardware.org/?probe=1859204a6f) | Jul 31, 2023 |
| Apple         | MacBookPro6,2               | [c5205f5512](https://linux-hardware.org/?probe=c5205f5512) | Jul 30, 2023 |
| Dell          | Latitude E5270              | [ae07c57989](https://linux-hardware.org/?probe=ae07c57989) | Jul 30, 2023 |
| HP            | ProBook 640 G2              | [87a4b835cf](https://linux-hardware.org/?probe=87a4b835cf) | Jul 30, 2023 |
| Lenovo        | ThinkPad Edge E430 32543... | [b30651e46f](https://linux-hardware.org/?probe=b30651e46f) | Jul 30, 2023 |
| Lenovo        | ThinkPad T480s 20L8S0YW0... | [3ff995e8b7](https://linux-hardware.org/?probe=3ff995e8b7) | Jul 30, 2023 |
| ASUSTek       | Zephyrus S GX701GX_GX701... | [69da742061](https://linux-hardware.org/?probe=69da742061) | Jul 30, 2023 |
| Lenovo        | ThinkPad X201 3680BF5       | [dd11ccaaad](https://linux-hardware.org/?probe=dd11ccaaad) | Jul 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [d1a4b2769a](https://linux-hardware.org/?probe=d1a4b2769a) | Jul 29, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [d1bf55b135](https://linux-hardware.org/?probe=d1bf55b135) | Jul 29, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [ea8a893b11](https://linux-hardware.org/?probe=ea8a893b11) | Jul 29, 2023 |
| Acer          | Swift SF315-52G             | [aca997f2b5](https://linux-hardware.org/?probe=aca997f2b5) | Jul 29, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [ce140941bc](https://linux-hardware.org/?probe=ce140941bc) | Jul 29, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [19850c3ad1](https://linux-hardware.org/?probe=19850c3ad1) | Jul 29, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | [7207a12cd1](https://linux-hardware.org/?probe=7207a12cd1) | Jul 29, 2023 |
| VALE          | Notebook Classic C140       | [ec65662265](https://linux-hardware.org/?probe=ec65662265) | Jul 28, 2023 |
| HP            | Pavilion Gaming Laptop      | [b277fcda26](https://linux-hardware.org/?probe=b277fcda26) | Jul 28, 2023 |
| HP            | Victus by Gaming Laptop ... | [7595472fb4](https://linux-hardware.org/?probe=7595472fb4) | Jul 28, 2023 |
| Dell          | Latitude 7480               | [4287f8186f](https://linux-hardware.org/?probe=4287f8186f) | Jul 28, 2023 |
| Chitech Sh... | Tibuta_MasterPad-W100       | [202a9be7b7](https://linux-hardware.org/?probe=202a9be7b7) | Jul 28, 2023 |
| Casper        | EXCALIBUR G770              | [1b416b9f01](https://linux-hardware.org/?probe=1b416b9f01) | Jul 28, 2023 |
| Dell          | Precision 3520              | [bc2e0ff018](https://linux-hardware.org/?probe=bc2e0ff018) | Jul 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [9cbedced8b](https://linux-hardware.org/?probe=9cbedced8b) | Jul 28, 2023 |
| Dell          | System XPS L702X            | [5e9f83aa10](https://linux-hardware.org/?probe=5e9f83aa10) | Jul 28, 2023 |
| Acer          | Aspire A315-21G             | [0a4e1c4510](https://linux-hardware.org/?probe=0a4e1c4510) | Jul 28, 2023 |
| Apple         | MacBookPro5,2               | [2c6617e2f9](https://linux-hardware.org/?probe=2c6617e2f9) | Jul 27, 2023 |
| Dell          | Inspiron 5720               | [8674c464bd](https://linux-hardware.org/?probe=8674c464bd) | Jul 27, 2023 |
| Google        | Vortininja                  | [70f9ee30d3](https://linux-hardware.org/?probe=70f9ee30d3) | Jul 27, 2023 |
| Acer          | Aspire A315-23G             | [4d7b874be2](https://linux-hardware.org/?probe=4d7b874be2) | Jul 27, 2023 |
| Fujitsu       | LIFEBOOK U748               | [23d71a87d0](https://linux-hardware.org/?probe=23d71a87d0) | Jul 26, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | [0552cb3e44](https://linux-hardware.org/?probe=0552cb3e44) | Jul 26, 2023 |
| Dell          | XPS 13 7390                 | [0217675942](https://linux-hardware.org/?probe=0217675942) | Jul 26, 2023 |
| Dell          | Precision 3520              | [2502fbaef2](https://linux-hardware.org/?probe=2502fbaef2) | Jul 26, 2023 |
| Dell          | Vostro 3405                 | [82a990b785](https://linux-hardware.org/?probe=82a990b785) | Jul 26, 2023 |
| Dell          | Vostro 3405                 | [dc97ca175a](https://linux-hardware.org/?probe=dc97ca175a) | Jul 25, 2023 |
| HP            | ProBook 640 G2              | [ae244aab21](https://linux-hardware.org/?probe=ae244aab21) | Jul 25, 2023 |
| Google        | Droid                       | [ae803483c2](https://linux-hardware.org/?probe=ae803483c2) | Jul 25, 2023 |
| Dell          | XPS 13 9370                 | [835ca23b88](https://linux-hardware.org/?probe=835ca23b88) | Jul 25, 2023 |
| HP            | Laptop 15-db0xxx            | [f01ec95642](https://linux-hardware.org/?probe=f01ec95642) | Jul 25, 2023 |
| Dell          | XPS 13 9370                 | [321bdf6295](https://linux-hardware.org/?probe=321bdf6295) | Jul 25, 2023 |
| Acer          | Aspire 3610                 | [b40dd6ad17](https://linux-hardware.org/?probe=b40dd6ad17) | Jul 25, 2023 |
| Dell          | Latitude 3420               | [18d920dab2](https://linux-hardware.org/?probe=18d920dab2) | Jul 24, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [fd441fa52f](https://linux-hardware.org/?probe=fd441fa52f) | Jul 24, 2023 |
| ASUSTek       | X541UV                      | [eb0aac9c32](https://linux-hardware.org/?probe=eb0aac9c32) | Jul 24, 2023 |
| Acer          | Nitro AN515-57              | [ae6caf81d7](https://linux-hardware.org/?probe=ae6caf81d7) | Jul 24, 2023 |
| Acer          | Aspire A515-45              | [e1de4fabc7](https://linux-hardware.org/?probe=e1de4fabc7) | Jul 24, 2023 |
| Timi          | A7S                         | [d0bcd36416](https://linux-hardware.org/?probe=d0bcd36416) | Jul 24, 2023 |
| MSI           | Alpha 15 B5EEK              | [ea2f3666ba](https://linux-hardware.org/?probe=ea2f3666ba) | Jul 23, 2023 |
| HP            | EliteBook 835 G8 Noteboo... | [a3350e1d80](https://linux-hardware.org/?probe=a3350e1d80) | Jul 23, 2023 |
| Acer          | Aspire A315-21              | [17f482e878](https://linux-hardware.org/?probe=17f482e878) | Jul 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [d957d5efe0](https://linux-hardware.org/?probe=d957d5efe0) | Jul 22, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [467cc30f89](https://linux-hardware.org/?probe=467cc30f89) | Jul 22, 2023 |
| HP            | EliteBook 840 G1            | [cafa1082f8](https://linux-hardware.org/?probe=cafa1082f8) | Jul 22, 2023 |
| HP            | Presario CQ57               | [2c1bcfe898](https://linux-hardware.org/?probe=2c1bcfe898) | Jul 22, 2023 |
| Dell          | Inspiron 3558               | [2cad6d3cb7](https://linux-hardware.org/?probe=2cad6d3cb7) | Jul 22, 2023 |
| Dell          | Latitude 5580               | [06c9677557](https://linux-hardware.org/?probe=06c9677557) | Jul 22, 2023 |
| HP            | ENVY Laptop 17-ch2xxx       | [7d88a01e49](https://linux-hardware.org/?probe=7d88a01e49) | Jul 22, 2023 |
| HP            | 635                         | [bb148a8b2b](https://linux-hardware.org/?probe=bb148a8b2b) | Jul 21, 2023 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | [7527ca0197](https://linux-hardware.org/?probe=7527ca0197) | Jul 20, 2023 |
| HP            | Pavilion Notebook           | [d366e7101c](https://linux-hardware.org/?probe=d366e7101c) | Jul 20, 2023 |
| ASUSTek       | T100TAM                     | [43cb18f0ee](https://linux-hardware.org/?probe=43cb18f0ee) | Jul 20, 2023 |
| ASUSTek       | VivoBook E14 E402YA_L402... | [311144e138](https://linux-hardware.org/?probe=311144e138) | Jul 20, 2023 |
| Shanghai Z... | ZXE CRB                     | [da6bb4265c](https://linux-hardware.org/?probe=da6bb4265c) | Jul 20, 2023 |
| Notebook      | N650DU                      | [c04f4faa06](https://linux-hardware.org/?probe=c04f4faa06) | Jul 19, 2023 |
| HP            | Pavilion 15                 | [e1bfe97e63](https://linux-hardware.org/?probe=e1bfe97e63) | Jul 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [524d69b498](https://linux-hardware.org/?probe=524d69b498) | Jul 19, 2023 |
| Acer          | Aspire 7739Z                | [3e75dec5e0](https://linux-hardware.org/?probe=3e75dec5e0) | Jul 19, 2023 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [9672a393c9](https://linux-hardware.org/?probe=9672a393c9) | Jul 19, 2023 |
| Acer          | Extensa 215-22              | [fc3dadd5bc](https://linux-hardware.org/?probe=fc3dadd5bc) | Jul 19, 2023 |
| Acer          | Nitro AN515-57              | [cdad3aa931](https://linux-hardware.org/?probe=cdad3aa931) | Jul 19, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [bddb3e26c1](https://linux-hardware.org/?probe=bddb3e26c1) | Jul 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [a4584a139f](https://linux-hardware.org/?probe=a4584a139f) | Jul 19, 2023 |
| MSI           | GF63 Thin 11UC              | [3ef8cdcacb](https://linux-hardware.org/?probe=3ef8cdcacb) | Jul 18, 2023 |
| Dell          | Vostro 3500                 | [69cc1eb6f6](https://linux-hardware.org/?probe=69cc1eb6f6) | Jul 18, 2023 |
| HP            | Pavilion 15                 | [a5485bb7e0](https://linux-hardware.org/?probe=a5485bb7e0) | Jul 18, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [c6da4f3b1e](https://linux-hardware.org/?probe=c6da4f3b1e) | Jul 18, 2023 |
| Lenovo        | ThinkPad L580 20LW000WGE    | [1b210ca778](https://linux-hardware.org/?probe=1b210ca778) | Jul 18, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [35d510901b](https://linux-hardware.org/?probe=35d510901b) | Jul 18, 2023 |
| HP            | Laptop 17-cp0xxx            | [9d9ff78d29](https://linux-hardware.org/?probe=9d9ff78d29) | Jul 18, 2023 |
| Unknown       | TU-142                      | [d62ade82c2](https://linux-hardware.org/?probe=d62ade82c2) | Jul 17, 2023 |
| HP            | Pavilion dm1                | [135bb20fbd](https://linux-hardware.org/?probe=135bb20fbd) | Jul 17, 2023 |
| Acer          | Aspire A515-57T             | [dd4a3bf595](https://linux-hardware.org/?probe=dd4a3bf595) | Jul 17, 2023 |
| Acer          | Aspire A315-23G             | [df26ae3dab](https://linux-hardware.org/?probe=df26ae3dab) | Jul 17, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [ab43e6b8ef](https://linux-hardware.org/?probe=ab43e6b8ef) | Jul 16, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [6b52cef555](https://linux-hardware.org/?probe=6b52cef555) | Jul 16, 2023 |
| Lenovo        | Yoga 14sITL 2021 82G2       | [899c1452e4](https://linux-hardware.org/?probe=899c1452e4) | Jul 16, 2023 |
| Lenovo        | ThinkPad X120e 0611AN2      | [497e6c5432](https://linux-hardware.org/?probe=497e6c5432) | Jul 16, 2023 |
| HP            | Laptop 14s-dq2xxx           | [cd9bfc68b6](https://linux-hardware.org/?probe=cd9bfc68b6) | Jul 16, 2023 |
| SIRAGON       | LM-C100                     | [daef084233](https://linux-hardware.org/?probe=daef084233) | Jul 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [1625385cef](https://linux-hardware.org/?probe=1625385cef) | Jul 16, 2023 |
| Dell          | Latitude D610               | [791cabd713](https://linux-hardware.org/?probe=791cabd713) | Jul 16, 2023 |
| Lenovo        | ThinkPad T440p 20AN0069U... | [02af27da78](https://linux-hardware.org/?probe=02af27da78) | Jul 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d43ad7594c](https://linux-hardware.org/?probe=d43ad7594c) | Jul 16, 2023 |
| Dell          | Latitude E6330              | [6adb67344f](https://linux-hardware.org/?probe=6adb67344f) | Jul 15, 2023 |
| SLIMBOOK      | PROX15-AMD                  | [7e088e838b](https://linux-hardware.org/?probe=7e088e838b) | Jul 15, 2023 |
| Lenovo        | ThinkPad T470s 20HGS1VD0... | [b62ed55325](https://linux-hardware.org/?probe=b62ed55325) | Jul 15, 2023 |
| Dell          | Latitude 7490               | [6811ebe45a](https://linux-hardware.org/?probe=6811ebe45a) | Jul 15, 2023 |
| Apple         | MacBookPro14,3              | [bd2e85e3ce](https://linux-hardware.org/?probe=bd2e85e3ce) | Jul 15, 2023 |
| HUAWEI        | KLVL-WXXW                   | [c76e3df311](https://linux-hardware.org/?probe=c76e3df311) | Jul 14, 2023 |
| Lenovo        | ThinkPad T530 2429HD6       | [1c48702f3c](https://linux-hardware.org/?probe=1c48702f3c) | Jul 14, 2023 |
| Lenovo        | ThinkPad X220 4290FC1       | [d6c0ccb8f1](https://linux-hardware.org/?probe=d6c0ccb8f1) | Jul 14, 2023 |
| HP            | ProBook 640 G2              | [e5efd1b971](https://linux-hardware.org/?probe=e5efd1b971) | Jul 14, 2023 |
| HP            | Pavilion dm1                | [3b05c5dc5c](https://linux-hardware.org/?probe=3b05c5dc5c) | Jul 14, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [e790a3c22f](https://linux-hardware.org/?probe=e790a3c22f) | Jul 14, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [dae11c33ed](https://linux-hardware.org/?probe=dae11c33ed) | Jul 14, 2023 |
| Google        | Blorb                       | [6bbcc9b8f3](https://linux-hardware.org/?probe=6bbcc9b8f3) | Jul 14, 2023 |
| Valve         | Jupiter                     | [14f7ea4a48](https://linux-hardware.org/?probe=14f7ea4a48) | Jul 13, 2023 |
| Dell          | XPS 17 9730                 | [b074a1deb3](https://linux-hardware.org/?probe=b074a1deb3) | Jul 13, 2023 |
| Google        | Reks                        | [680b857c0d](https://linux-hardware.org/?probe=680b857c0d) | Jul 13, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [7d2bb16563](https://linux-hardware.org/?probe=7d2bb16563) | Jul 13, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [b054249d03](https://linux-hardware.org/?probe=b054249d03) | Jul 13, 2023 |
| MSI           | Alpha 15 A4DEK              | [9a192c4a0b](https://linux-hardware.org/?probe=9a192c4a0b) | Jul 13, 2023 |
| ASUSTek       | VivoBook E14 E402YA_L402... | [34ec75d601](https://linux-hardware.org/?probe=34ec75d601) | Jul 13, 2023 |
| Acer          | Aspire A515-52              | [56b110f152](https://linux-hardware.org/?probe=56b110f152) | Jul 13, 2023 |
| Acer          | Aspire A515-52              | [ad9fd505fa](https://linux-hardware.org/?probe=ad9fd505fa) | Jul 13, 2023 |
| Toshiba       | Satellite S75-B             | [ee71e28c8f](https://linux-hardware.org/?probe=ee71e28c8f) | Jul 12, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [603a591fcb](https://linux-hardware.org/?probe=603a591fcb) | Jul 12, 2023 |
| Acer          | Aspire 5820TG               | [86cfbf79ce](https://linux-hardware.org/?probe=86cfbf79ce) | Jul 12, 2023 |
| MSI           | FX603                       | [a2c598f9eb](https://linux-hardware.org/?probe=a2c598f9eb) | Jul 12, 2023 |
| MSI           | SUMMIT E13FlipEvo A12MT     | [90faae34f3](https://linux-hardware.org/?probe=90faae34f3) | Jul 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [15c5dec8dc](https://linux-hardware.org/?probe=15c5dec8dc) | Jul 12, 2023 |
| Dell          | XPS 13 9380                 | [e40c69408d](https://linux-hardware.org/?probe=e40c69408d) | Jul 11, 2023 |
| Lenovo        | IdeaPad S540-14API 81NH     | [9fc68063e3](https://linux-hardware.org/?probe=9fc68063e3) | Jul 11, 2023 |
| Dell          | Latitude 7275               | [0647894f7f](https://linux-hardware.org/?probe=0647894f7f) | Jul 11, 2023 |
| HP            | ProBook 4730s               | [0b6a6c7260](https://linux-hardware.org/?probe=0b6a6c7260) | Jul 11, 2023 |
| HP            | EliteBook 645 14 inch G9... | [65f4b4e813](https://linux-hardware.org/?probe=65f4b4e813) | Jul 11, 2023 |
| Unknown       | HP Chromebook 14            | [63b183aa51](https://linux-hardware.org/?probe=63b183aa51) | Jul 11, 2023 |
| Dell          | Inspiron 7560               | [a761bfffd2](https://linux-hardware.org/?probe=a761bfffd2) | Jul 11, 2023 |
| HP            | ZBook 15 G6                 | [47ea5a35cb](https://linux-hardware.org/?probe=47ea5a35cb) | Jul 11, 2023 |
| Acer          | Aspire 4937                 | [fe9bfd5f77](https://linux-hardware.org/?probe=fe9bfd5f77) | Jul 10, 2023 |
| Acer          | Aspire 4937                 | [d4dadd2e77](https://linux-hardware.org/?probe=d4dadd2e77) | Jul 10, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [707f0b8eeb](https://linux-hardware.org/?probe=707f0b8eeb) | Jul 10, 2023 |
| HP            | Victus by Laptop 16-e1xx... | [a14d8855bc](https://linux-hardware.org/?probe=a14d8855bc) | Jul 10, 2023 |
| Dell          | OptiPlex 9020               | [3384a64b67](https://linux-hardware.org/?probe=3384a64b67) | Jul 10, 2023 |
| Fujitsu       | LIFEBOOK U727               | [ce095d85c9](https://linux-hardware.org/?probe=ce095d85c9) | Jul 09, 2023 |
| HP            | Pro x2 612 G1 Tablet USA... | [c10c965a51](https://linux-hardware.org/?probe=c10c965a51) | Jul 09, 2023 |
| Acer          | Aspire V3-372T              | [566ff1d23e](https://linux-hardware.org/?probe=566ff1d23e) | Jul 09, 2023 |
| MSI           | Modern 14 B11MOU            | [c2e76ab704](https://linux-hardware.org/?probe=c2e76ab704) | Jul 09, 2023 |
| ASUSTek       | VivoBook S14 X430UA         | [fdb15c83de](https://linux-hardware.org/?probe=fdb15c83de) | Jul 09, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | [59f06e2baf](https://linux-hardware.org/?probe=59f06e2baf) | Jul 09, 2023 |
| Acer          | Aspire V3-372T              | [f2a9fbdf50](https://linux-hardware.org/?probe=f2a9fbdf50) | Jul 09, 2023 |
| HP            | EliteBook 8560p             | [39fe220963](https://linux-hardware.org/?probe=39fe220963) | Jul 09, 2023 |
| Dell          | Inspiron N4050              | [d5fa70cfda](https://linux-hardware.org/?probe=d5fa70cfda) | Jul 08, 2023 |
| Acer          | TravelMate P215-53          | [5810f4f1f8](https://linux-hardware.org/?probe=5810f4f1f8) | Jul 08, 2023 |
| Apple         | MacBookPro14,3              | [6a739102d0](https://linux-hardware.org/?probe=6a739102d0) | Jul 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [ae008e5343](https://linux-hardware.org/?probe=ae008e5343) | Jul 07, 2023 |
| Fujitsu       | LIFEBOOK E5512A             | [96d1578908](https://linux-hardware.org/?probe=96d1578908) | Jul 07, 2023 |
| HP            | ProBook 430 G1              | [abb4e75faa](https://linux-hardware.org/?probe=abb4e75faa) | Jul 07, 2023 |
| Lenovo        | ThinkPad X270 20HMS10600    | [5d03b4b2ad](https://linux-hardware.org/?probe=5d03b4b2ad) | Jul 07, 2023 |
| Lenovo        | Flex 2-14 20404             | [93f50211c2](https://linux-hardware.org/?probe=93f50211c2) | Jul 07, 2023 |
| HUAWEI        | BOM-WXX9                    | [905af6686d](https://linux-hardware.org/?probe=905af6686d) | Jul 06, 2023 |
| Dell          | Latitude 7430               | [743d41d534](https://linux-hardware.org/?probe=743d41d534) | Jul 06, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [37f1a0082b](https://linux-hardware.org/?probe=37f1a0082b) | Jul 06, 2023 |
| Lenovo        | ThinkPad T470 20HES05500    | [12b31081e2](https://linux-hardware.org/?probe=12b31081e2) | Jul 06, 2023 |
| HONOR         | BOHK-WAX9X                  | [95d2ae1051](https://linux-hardware.org/?probe=95d2ae1051) | Jul 06, 2023 |
| HONOR         | BOHK-WAX9X                  | [4f6d2375a3](https://linux-hardware.org/?probe=4f6d2375a3) | Jul 06, 2023 |
| Apple         | MacBookAir7,2               | [c1d387dfc5](https://linux-hardware.org/?probe=c1d387dfc5) | Jul 06, 2023 |
| Dell          | XPS 15 9520                 | [f255433162](https://linux-hardware.org/?probe=f255433162) | Jul 06, 2023 |
| Dell          | Precision M6800             | [4b8d02d04a](https://linux-hardware.org/?probe=4b8d02d04a) | Jul 06, 2023 |
| Dell          | Precision M6800             | [239c3ea2b9](https://linux-hardware.org/?probe=239c3ea2b9) | Jul 06, 2023 |
| Apple         | MacBookPro14,3              | [d6153317bf](https://linux-hardware.org/?probe=d6153317bf) | Jul 05, 2023 |
| Samsung       | 770Z5E/780Z5E               | [2d38e98c83](https://linux-hardware.org/?probe=2d38e98c83) | Jul 05, 2023 |
| Apple         | MacBook5,2                  | [41366bcd54](https://linux-hardware.org/?probe=41366bcd54) | Jul 05, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [9d57d6a85f](https://linux-hardware.org/?probe=9d57d6a85f) | Jul 05, 2023 |
| HP            | ProBook 450 G5              | [7a15493631](https://linux-hardware.org/?probe=7a15493631) | Jul 05, 2023 |
| Lenovo        | ThinkPad E16 Gen 1 21JT0... | [fc1c7254b3](https://linux-hardware.org/?probe=fc1c7254b3) | Jul 04, 2023 |
| MSI           | Creator 15M A9SD            | [84c85a8969](https://linux-hardware.org/?probe=84c85a8969) | Jul 04, 2023 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [79c5344e62](https://linux-hardware.org/?probe=79c5344e62) | Jul 04, 2023 |
| Google        | Lick                        | [f2b9397a8b](https://linux-hardware.org/?probe=f2b9397a8b) | Jul 04, 2023 |
| Acer          | Aspire 6930                 | [772d3d7f4a](https://linux-hardware.org/?probe=772d3d7f4a) | Jul 04, 2023 |
| HP            | Pavilion dv6                | [517e6b81c1](https://linux-hardware.org/?probe=517e6b81c1) | Jul 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [73146ccba2](https://linux-hardware.org/?probe=73146ccba2) | Jul 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [19a254cdee](https://linux-hardware.org/?probe=19a254cdee) | Jul 03, 2023 |
| Lenovo        | ThinkPad T440s 20ARA1DJM... | [18230f7c64](https://linux-hardware.org/?probe=18230f7c64) | Jul 03, 2023 |
| HONOR         | NMH-WCX9                    | [a8caf9af8e](https://linux-hardware.org/?probe=a8caf9af8e) | Jul 02, 2023 |
| HUAWEI        | BOHB-WAX9                   | [4055aa6f2b](https://linux-hardware.org/?probe=4055aa6f2b) | Jul 02, 2023 |
| Dell          | Latitude 3410               | [11d9814008](https://linux-hardware.org/?probe=11d9814008) | Jul 02, 2023 |
| Lenovo        | ThinkPad T61p 6457UN2       | [4708f2b480](https://linux-hardware.org/?probe=4708f2b480) | Jul 02, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [54987b03a1](https://linux-hardware.org/?probe=54987b03a1) | Jul 02, 2023 |
| HP            | Laptop 15-dw3xxx            | [3fe182f682](https://linux-hardware.org/?probe=3fe182f682) | Jul 02, 2023 |
| HP            | Pavilion dv7                | [e10b64716f](https://linux-hardware.org/?probe=e10b64716f) | Jul 01, 2023 |
| HP            | EliteBook 2570p             | [c55a78c98a](https://linux-hardware.org/?probe=c55a78c98a) | Jul 01, 2023 |
| ASUSTek       | X541UV                      | [d0fc2ea58e](https://linux-hardware.org/?probe=d0fc2ea58e) | Jul 01, 2023 |
| Dell          | Inspiron 7720               | [9d8f40247e](https://linux-hardware.org/?probe=9d8f40247e) | Jul 01, 2023 |
| ASUSTek       | X541UV                      | [8b5dc3456b](https://linux-hardware.org/?probe=8b5dc3456b) | Jul 01, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDC... | [0aed51f639](https://linux-hardware.org/?probe=0aed51f639) | Jul 01, 2023 |
| Lenovo        | ThinkPad T400 2768WGB       | [55bfc9f544](https://linux-hardware.org/?probe=55bfc9f544) | Jul 01, 2023 |
| Apple         | MacBookPro14,3              | [4a51b35cb8](https://linux-hardware.org/?probe=4a51b35cb8) | Jul 01, 2023 |
| Dell          | Latitude 3500               | [8e82f9abda](https://linux-hardware.org/?probe=8e82f9abda) | Jul 01, 2023 |
| Acer          | Aspire V5-123               | [8507833f22](https://linux-hardware.org/?probe=8507833f22) | Jul 01, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [39a8ee4269](https://linux-hardware.org/?probe=39a8ee4269) | Jun 30, 2023 |
| HP            | EliteBook 850 G1            | [a5f3a5ad14](https://linux-hardware.org/?probe=a5f3a5ad14) | Jun 30, 2023 |
| Lenovo        | ThinkPad T495 20NK000XBR    | [2b5e40efaa](https://linux-hardware.org/?probe=2b5e40efaa) | Jun 30, 2023 |
| Lenovo        | ThinkPad T430s 23554L7      | [501b0860c8](https://linux-hardware.org/?probe=501b0860c8) | Jun 30, 2023 |
| Dell          | G3 3590                     | [5c7312fed9](https://linux-hardware.org/?probe=5c7312fed9) | Jun 30, 2023 |
| Lenovo        | ThinkPad L512 44444NG       | [300a79aa88](https://linux-hardware.org/?probe=300a79aa88) | Jun 30, 2023 |
| ASUSTek       | T100TA                      | [921821fda8](https://linux-hardware.org/?probe=921821fda8) | Jun 30, 2023 |
| ASUSTek       | K52F                        | [98e9b448c7](https://linux-hardware.org/?probe=98e9b448c7) | Jun 30, 2023 |
| Lenovo        | ThinkPad T440p 2000CT0      | [10c852dc38](https://linux-hardware.org/?probe=10c852dc38) | Jun 29, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | [25a1aaf938](https://linux-hardware.org/?probe=25a1aaf938) | Jun 29, 2023 |
| Lenovo        | ThinkPad T480 20L6S68T00    | [a50310948a](https://linux-hardware.org/?probe=a50310948a) | Jun 29, 2023 |
| Dell          | Latitude 3500               | [e1831984f8](https://linux-hardware.org/?probe=e1831984f8) | Jun 28, 2023 |
| Aquarius      | NS585                       | [52a07593c9](https://linux-hardware.org/?probe=52a07593c9) | Jun 28, 2023 |
| HP            | Pavilion dv6                | [7fe9e439c0](https://linux-hardware.org/?probe=7fe9e439c0) | Jun 28, 2023 |
| Aquarius      | NS585                       | [b2f86e98f9](https://linux-hardware.org/?probe=b2f86e98f9) | Jun 28, 2023 |
| ASUSTek       | ZenBook Pro 15 UX550GEX_... | [56eef68e89](https://linux-hardware.org/?probe=56eef68e89) | Jun 28, 2023 |
| Acer          | Aspire A315-23G             | [1c07c9f0b8](https://linux-hardware.org/?probe=1c07c9f0b8) | Jun 28, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [8112f38f33](https://linux-hardware.org/?probe=8112f38f33) | Jun 27, 2023 |
| HP            | Laptop 15-ef1xxx            | [765d0708eb](https://linux-hardware.org/?probe=765d0708eb) | Jun 26, 2023 |
| Lenovo        | ThinkPad T480 20L6S5LF00    | [5a062be874](https://linux-hardware.org/?probe=5a062be874) | Jun 26, 2023 |
| HP            | EliteBook 835 13 inch G1... | [e43818af40](https://linux-hardware.org/?probe=e43818af40) | Jun 26, 2023 |
| LG Electro... | 17Z90R-G.AD79F              | [0d641b84fe](https://linux-hardware.org/?probe=0d641b84fe) | Jun 26, 2023 |
| Acer          | Aspire A515-56              | [0ee45fd3e8](https://linux-hardware.org/?probe=0ee45fd3e8) | Jun 26, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [b8a3042b9d](https://linux-hardware.org/?probe=b8a3042b9d) | Jun 26, 2023 |
| Aquarius      | NS585                       | [25af22ec30](https://linux-hardware.org/?probe=25af22ec30) | Jun 26, 2023 |
| Aquarius      | NS585                       | [8e957a70f0](https://linux-hardware.org/?probe=8e957a70f0) | Jun 26, 2023 |
| Aquarius      | NS585                       | [bb09ae1f8d](https://linux-hardware.org/?probe=bb09ae1f8d) | Jun 26, 2023 |
| HP            | OMEN by Laptop              | [07d9cc6d71](https://linux-hardware.org/?probe=07d9cc6d71) | Jun 26, 2023 |
| Apple         | MacBook2,1                  | [f5c0a2fd49](https://linux-hardware.org/?probe=f5c0a2fd49) | Jun 26, 2023 |
| HP            | Compaq Mini 110c-1100       | [0dc147bd7c](https://linux-hardware.org/?probe=0dc147bd7c) | Jun 26, 2023 |
| Lenovo        | ThinkPad T430 34766TT       | [06ad7b4a25](https://linux-hardware.org/?probe=06ad7b4a25) | Jun 26, 2023 |
| Dell          | XPS 15 7590                 | [dfc817892b](https://linux-hardware.org/?probe=dfc817892b) | Jun 26, 2023 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | [ed89cd0d05](https://linux-hardware.org/?probe=ed89cd0d05) | Jun 26, 2023 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | [62665eec25](https://linux-hardware.org/?probe=62665eec25) | Jun 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [0a233c34b3](https://linux-hardware.org/?probe=0a233c34b3) | Jun 26, 2023 |
| Avell High... | A70 HYB                     | [3ccdaf3c82](https://linux-hardware.org/?probe=3ccdaf3c82) | Jun 26, 2023 |
| ASUSTek       | E403SA                      | [bdc47269c3](https://linux-hardware.org/?probe=bdc47269c3) | Jun 25, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH7 ... | [cee2bb11dc](https://linux-hardware.org/?probe=cee2bb11dc) | Jun 25, 2023 |
| HP            | Laptop 15s-eq2xxx           | [14cc9e067f](https://linux-hardware.org/?probe=14cc9e067f) | Jun 25, 2023 |
| Dell          | Inspiron 5593               | [06f1256f88](https://linux-hardware.org/?probe=06f1256f88) | Jun 25, 2023 |
| Dell          | Latitude E6430              | [be9b6c75da](https://linux-hardware.org/?probe=be9b6c75da) | Jun 25, 2023 |
| Toshiba       | IS 1413G                    | [a87db20468](https://linux-hardware.org/?probe=a87db20468) | Jun 25, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [a7df01b153](https://linux-hardware.org/?probe=a7df01b153) | Jun 24, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [fe084d5ddb](https://linux-hardware.org/?probe=fe084d5ddb) | Jun 24, 2023 |
| Lenovo        | ThinkPad X120e 0611AN2      | [a8420bc87d](https://linux-hardware.org/?probe=a8420bc87d) | Jun 24, 2023 |
| Dell          | XPS 15 9570                 | [2c09eb930c](https://linux-hardware.org/?probe=2c09eb930c) | Jun 23, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [3cc7c77a76](https://linux-hardware.org/?probe=3cc7c77a76) | Jun 23, 2023 |
| HP            | 8470p EliteBook             | [da3719515b](https://linux-hardware.org/?probe=da3719515b) | Jun 23, 2023 |
| Acer          | Predator PH315-54           | [46d748a0a1](https://linux-hardware.org/?probe=46d748a0a1) | Jun 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [3cdf59359c](https://linux-hardware.org/?probe=3cdf59359c) | Jun 23, 2023 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [5298e132fc](https://linux-hardware.org/?probe=5298e132fc) | Jun 23, 2023 |
| Lenovo        | Flex 2-14 20404             | [b5576af3f8](https://linux-hardware.org/?probe=b5576af3f8) | Jun 23, 2023 |
| Lenovo        | Flex 2-14 20404             | [911336b572](https://linux-hardware.org/?probe=911336b572) | Jun 23, 2023 |
| Lenovo        | ThinkPad X230 2325SRQ       | [fd42553eea](https://linux-hardware.org/?probe=fd42553eea) | Jun 22, 2023 |
| ASUSTek       | X45U                        | [63a491a160](https://linux-hardware.org/?probe=63a491a160) | Jun 22, 2023 |
| Apple         | MacBookPro10,1              | [9841bf505c](https://linux-hardware.org/?probe=9841bf505c) | Jun 21, 2023 |
| Apple         | MacBookAir7,2               | [9f3829c99f](https://linux-hardware.org/?probe=9f3829c99f) | Jun 21, 2023 |
| Apple         | MacBookAir7,2               | [379e3473e2](https://linux-hardware.org/?probe=379e3473e2) | Jun 21, 2023 |
| Apple         | MacBookAir7,2               | [8a2a9fd293](https://linux-hardware.org/?probe=8a2a9fd293) | Jun 21, 2023 |
| Dell          | Inspiron 5570               | [d661316023](https://linux-hardware.org/?probe=d661316023) | Jun 21, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [8a61f834dd](https://linux-hardware.org/?probe=8a61f834dd) | Jun 21, 2023 |
| Dell          | Vostro 5490                 | [10d1aeda8b](https://linux-hardware.org/?probe=10d1aeda8b) | Jun 21, 2023 |
| Lenovo        | IdeaPad 330-17AST 81D7      | [dc5a63aacc](https://linux-hardware.org/?probe=dc5a63aacc) | Jun 20, 2023 |
| Apple         | MacBook6,1                  | [c7e1912b55](https://linux-hardware.org/?probe=c7e1912b55) | Jun 20, 2023 |
| Apple         | MacBook5,2                  | [53f708517b](https://linux-hardware.org/?probe=53f708517b) | Jun 20, 2023 |
| Google        | Stout                       | [cb67ad655e](https://linux-hardware.org/?probe=cb67ad655e) | Jun 20, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | [c3f77cf346](https://linux-hardware.org/?probe=c3f77cf346) | Jun 20, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | [a0862de551](https://linux-hardware.org/?probe=a0862de551) | Jun 19, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | [3cfd8a448c](https://linux-hardware.org/?probe=3cfd8a448c) | Jun 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [42fd301e8b](https://linux-hardware.org/?probe=42fd301e8b) | Jun 19, 2023 |
| Lenovo        | IdeaPad S340-15APITouch ... | [fe617b45f8](https://linux-hardware.org/?probe=fe617b45f8) | Jun 19, 2023 |
| Toshiba       | TECRA R850                  | [c40116d0de](https://linux-hardware.org/?probe=c40116d0de) | Jun 19, 2023 |
| Dell          | Latitude E7450              | [addda016c8](https://linux-hardware.org/?probe=addda016c8) | Jun 18, 2023 |
| HP            | EliteBook 8440p             | [4b1b2457a4](https://linux-hardware.org/?probe=4b1b2457a4) | Jun 17, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [e4c418382a](https://linux-hardware.org/?probe=e4c418382a) | Jun 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [26b4c05332](https://linux-hardware.org/?probe=26b4c05332) | Jun 17, 2023 |
| Lenovo        | ThinkPad T480s 20L8S10T0... | [a3dd392c51](https://linux-hardware.org/?probe=a3dd392c51) | Jun 17, 2023 |
| Dell          | Latitude E6400              | [0f8aca3e72](https://linux-hardware.org/?probe=0f8aca3e72) | Jun 17, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [d9e1222bc3](https://linux-hardware.org/?probe=d9e1222bc3) | Jun 17, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [9cdeeb06de](https://linux-hardware.org/?probe=9cdeeb06de) | Jun 16, 2023 |
| Lenovo        | ThinkPad P51 20HJS1SF00     | [664ae7a0f2](https://linux-hardware.org/?probe=664ae7a0f2) | Jun 16, 2023 |
| HONOR         | NMH-WCX9                    | [ec1b8c4ef4](https://linux-hardware.org/?probe=ec1b8c4ef4) | Jun 16, 2023 |
| HUAWEI        | NBD-WXX9                    | [b9bf7ea3c2](https://linux-hardware.org/?probe=b9bf7ea3c2) | Jun 16, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [b05e4ee752](https://linux-hardware.org/?probe=b05e4ee752) | Jun 15, 2023 |
| Unknown       | Unknown                     | [f1294224ee](https://linux-hardware.org/?probe=f1294224ee) | Jun 15, 2023 |
| Unknown       | Unknown                     | [9b8a05d0f9](https://linux-hardware.org/?probe=9b8a05d0f9) | Jun 15, 2023 |
| Acer          | TravelMate 8172             | [569fde2487](https://linux-hardware.org/?probe=569fde2487) | Jun 15, 2023 |
| Apple         | MacBookAir7,2               | [2db615249d](https://linux-hardware.org/?probe=2db615249d) | Jun 15, 2023 |
| Apple         | MacBookAir7,2               | [138e2807af](https://linux-hardware.org/?probe=138e2807af) | Jun 15, 2023 |
| Apple         | MacBookAir7,1               | [5d8061c350](https://linux-hardware.org/?probe=5d8061c350) | Jun 15, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [aafa9250df](https://linux-hardware.org/?probe=aafa9250df) | Jun 15, 2023 |
| Lenovo        | B590 20206                  | [f7e4f16796](https://linux-hardware.org/?probe=f7e4f16796) | Jun 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [eb0ba3c881](https://linux-hardware.org/?probe=eb0ba3c881) | Jun 15, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [65298dde46](https://linux-hardware.org/?probe=65298dde46) | Jun 14, 2023 |
| HONOR         | BBR-WAX9                    | [b980e4f162](https://linux-hardware.org/?probe=b980e4f162) | Jun 14, 2023 |
| Dell          | XPS M1530                   | [252d777fa0](https://linux-hardware.org/?probe=252d777fa0) | Jun 14, 2023 |
| Acer          | TravelMate 5742Z            | [abf5dbde31](https://linux-hardware.org/?probe=abf5dbde31) | Jun 14, 2023 |
| Dell          | Latitude 7480               | [375fb09bca](https://linux-hardware.org/?probe=375fb09bca) | Jun 14, 2023 |
| Acer          | Aspire A315-23G             | [18a5adccb6](https://linux-hardware.org/?probe=18a5adccb6) | Jun 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [e073b99b63](https://linux-hardware.org/?probe=e073b99b63) | Jun 13, 2023 |
| HP            | Pavilion Notebook           | [f444f44a49](https://linux-hardware.org/?probe=f444f44a49) | Jun 13, 2023 |
| Samsung       | 750XED                      | [8997330d6a](https://linux-hardware.org/?probe=8997330d6a) | Jun 13, 2023 |
| Sony          | SVE11116FGW                 | [4c34707bef](https://linux-hardware.org/?probe=4c34707bef) | Jun 13, 2023 |
| Sony          | SVE11116FGW                 | [a048cbcdeb](https://linux-hardware.org/?probe=a048cbcdeb) | Jun 13, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [f578df0eb9](https://linux-hardware.org/?probe=f578df0eb9) | Jun 13, 2023 |
| Apple         | MacBookPro12,1              | [a515b0dbf7](https://linux-hardware.org/?probe=a515b0dbf7) | Jun 12, 2023 |
| ASUSTek       | ASUSPRO P5440FA_P5440FA     | [20b91b813f](https://linux-hardware.org/?probe=20b91b813f) | Jun 12, 2023 |
| HP            | EliteBook 840 G5            | [331ac1da01](https://linux-hardware.org/?probe=331ac1da01) | Jun 12, 2023 |
| HP            | EliteBook 2530p             | [8e5a09ba99](https://linux-hardware.org/?probe=8e5a09ba99) | Jun 12, 2023 |
| Dell          | Latitude 3320               | [e467a71dac](https://linux-hardware.org/?probe=e467a71dac) | Jun 12, 2023 |
| Dell          | Latitude 3320               | [ec4f04b63e](https://linux-hardware.org/?probe=ec4f04b63e) | Jun 12, 2023 |
| NEC Comput... | VERSA P91 series            | [7a4183e095](https://linux-hardware.org/?probe=7a4183e095) | Jun 12, 2023 |
| NEC Comput... | VERSA P91 series            | [2051db7014](https://linux-hardware.org/?probe=2051db7014) | Jun 12, 2023 |
| Dell          | Inspiron 5515               | [9ac2f1ed7e](https://linux-hardware.org/?probe=9ac2f1ed7e) | Jun 12, 2023 |
| Dell          | Inspiron 3501               | [8e9562dd9a](https://linux-hardware.org/?probe=8e9562dd9a) | Jun 11, 2023 |
| Lenovo        | G565 4385                   | [2fd61f3fc5](https://linux-hardware.org/?probe=2fd61f3fc5) | Jun 11, 2023 |
| MSI           | Prestige 15 A10SC           | [ceb7680734](https://linux-hardware.org/?probe=ceb7680734) | Jun 11, 2023 |
| ASUSTek       | ZenBook UX334FAC_UX334FA    | [ba762c6d80](https://linux-hardware.org/?probe=ba762c6d80) | Jun 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [8b88702b69](https://linux-hardware.org/?probe=8b88702b69) | Jun 11, 2023 |
| Dell          | Latitude 5480               | [5b3fb0b4f8](https://linux-hardware.org/?probe=5b3fb0b4f8) | Jun 09, 2023 |
| HP            | Laptop 14-cm0xxx            | [f1100ce875](https://linux-hardware.org/?probe=f1100ce875) | Jun 08, 2023 |
| HP            | G62                         | [fb9522ceac](https://linux-hardware.org/?probe=fb9522ceac) | Jun 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [ef71a1641b](https://linux-hardware.org/?probe=ef71a1641b) | Jun 08, 2023 |
| Fujitsu       | FMVNA4NE-                   | [626a677331](https://linux-hardware.org/?probe=626a677331) | Jun 06, 2023 |
| Aquarius      | NS585                       | [b3f11e4a53](https://linux-hardware.org/?probe=b3f11e4a53) | Jun 05, 2023 |
| Fujitsu       | FMVNA4NE-                   | [b1c1176a5b](https://linux-hardware.org/?probe=b1c1176a5b) | Jun 05, 2023 |
| Dell          | Latitude 5420               | [9085f3c8f7](https://linux-hardware.org/?probe=9085f3c8f7) | Jun 04, 2023 |
| Apple         | MacBookPro9,2               | [eb51cb6dcf](https://linux-hardware.org/?probe=eb51cb6dcf) | Jun 03, 2023 |
| Acer          | Aspire A115-31              | [338f025bce](https://linux-hardware.org/?probe=338f025bce) | Jun 03, 2023 |
| HP            | Laptop 14-cm0xxx            | [8933e1b0ad](https://linux-hardware.org/?probe=8933e1b0ad) | Jun 03, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [2a67b74a26](https://linux-hardware.org/?probe=2a67b74a26) | Jun 02, 2023 |
| HP            | ZBook 15 G6                 | [2f7bb21988](https://linux-hardware.org/?probe=2f7bb21988) | Jun 02, 2023 |
| Aquarius      | NS585                       | [6f93385917](https://linux-hardware.org/?probe=6f93385917) | Jun 02, 2023 |
| Dell          | Inspiron 5567               | [bd3a6c5bd8](https://linux-hardware.org/?probe=bd3a6c5bd8) | Jun 02, 2023 |
| Aquarius      | NS585                       | [091267ec3a](https://linux-hardware.org/?probe=091267ec3a) | Jun 02, 2023 |
| Aquarius      | NS585                       | [7534819f94](https://linux-hardware.org/?probe=7534819f94) | Jun 02, 2023 |
| Lenovo        | S40-70 80GQ                 | [9a3fbc7388](https://linux-hardware.org/?probe=9a3fbc7388) | Jun 02, 2023 |
| Aquarius      | NS585                       | [ffa7425b95](https://linux-hardware.org/?probe=ffa7425b95) | Jun 01, 2023 |
| Aquarius      | NS585                       | [fafcbbe90e](https://linux-hardware.org/?probe=fafcbbe90e) | Jun 01, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [ffc6b5e345](https://linux-hardware.org/?probe=ffc6b5e345) | Jun 01, 2023 |
| Unknown       | Unknown                     | [412c6d4af8](https://linux-hardware.org/?probe=412c6d4af8) | May 31, 2023 |
| Apple         | MacBookPro16,1              | [717c7884c8](https://linux-hardware.org/?probe=717c7884c8) | May 31, 2023 |
| Chuwi         | HeroBook Air                | [80afc31c99](https://linux-hardware.org/?probe=80afc31c99) | May 30, 2023 |
| Acer          | Aspire A315-58              | [66de62e958](https://linux-hardware.org/?probe=66de62e958) | May 29, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [c8e0efc288](https://linux-hardware.org/?probe=c8e0efc288) | May 29, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [da399dc7cc](https://linux-hardware.org/?probe=da399dc7cc) | May 29, 2023 |
| HP            | EliteBook 735 G6            | [18b33e6fc7](https://linux-hardware.org/?probe=18b33e6fc7) | May 29, 2023 |
| Acer          | Aspire A515-56              | [108833c92b](https://linux-hardware.org/?probe=108833c92b) | May 29, 2023 |
| Dell          | Latitude 7480               | [9eb2396796](https://linux-hardware.org/?probe=9eb2396796) | May 28, 2023 |
| Lenovo        | ThinkPad T400 2768WGB       | [447ea38d26](https://linux-hardware.org/?probe=447ea38d26) | May 27, 2023 |
| Lenovo        | ThinkPad T400 2768WGB       | [57dcd55314](https://linux-hardware.org/?probe=57dcd55314) | May 27, 2023 |
| Aquarius      | NS585                       | [a87c8d46b6](https://linux-hardware.org/?probe=a87c8d46b6) | May 27, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [9b93292db9](https://linux-hardware.org/?probe=9b93292db9) | May 26, 2023 |
| Dell          | Latitude 3520               | [bfa8a18cb5](https://linux-hardware.org/?probe=bfa8a18cb5) | May 26, 2023 |
| eMachines     | E725                        | [a4be8012a8](https://linux-hardware.org/?probe=a4be8012a8) | May 26, 2023 |
| Aquarius      | NS585                       | [82a0d45251](https://linux-hardware.org/?probe=82a0d45251) | May 25, 2023 |
| Acer          | Aspire E5-575               | [45ac56e70c](https://linux-hardware.org/?probe=45ac56e70c) | May 25, 2023 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | [f8ef460648](https://linux-hardware.org/?probe=f8ef460648) | May 23, 2023 |
| Acer          | Nitro AN515-45              | [d784b0822d](https://linux-hardware.org/?probe=d784b0822d) | May 22, 2023 |
| Lenovo        | ThinkPad T410s 2904FAG      | [742f2c09c5](https://linux-hardware.org/?probe=742f2c09c5) | May 21, 2023 |
| Terrans Fo... | AMD                         | [8087d42d0e](https://linux-hardware.org/?probe=8087d42d0e) | May 21, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [473ea193d5](https://linux-hardware.org/?probe=473ea193d5) | May 21, 2023 |
| Acer          | Aspire 5253                 | [f28727e594](https://linux-hardware.org/?probe=f28727e594) | May 21, 2023 |
| Acer          | Aspire 5739G                | [23a84a79ed](https://linux-hardware.org/?probe=23a84a79ed) | May 20, 2023 |
| Acer          | Aspire 5739G                | [2ae6c83437](https://linux-hardware.org/?probe=2ae6c83437) | May 20, 2023 |
| Dell          | Latitude E5430 non-vPro     | [51827f5ae5](https://linux-hardware.org/?probe=51827f5ae5) | May 19, 2023 |
| Acer          | Aspire 5253                 | [fa328bbd9c](https://linux-hardware.org/?probe=fa328bbd9c) | May 19, 2023 |
| Avell High... | A40 LIV                     | [d1e00e62c4](https://linux-hardware.org/?probe=d1e00e62c4) | May 19, 2023 |
| Toshiba       | Satellite C855-22N          | [f5ccfb46ea](https://linux-hardware.org/?probe=f5ccfb46ea) | May 18, 2023 |
| Aquarius      | NS585                       | [dc2b351b40](https://linux-hardware.org/?probe=dc2b351b40) | May 18, 2023 |
| ASUSTek       | Zenbook UM6702RA_RM6702R... | [66f184855c](https://linux-hardware.org/?probe=66f184855c) | May 17, 2023 |
| Acer          | TravelMate X514-51          | [24465d2184](https://linux-hardware.org/?probe=24465d2184) | May 17, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAA... | [5e4e802b87](https://linux-hardware.org/?probe=5e4e802b87) | May 17, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | [966e89afc3](https://linux-hardware.org/?probe=966e89afc3) | May 17, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [b4bd4b7d23](https://linux-hardware.org/?probe=b4bd4b7d23) | May 17, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [3089c7ab46](https://linux-hardware.org/?probe=3089c7ab46) | May 16, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [a587179a2f](https://linux-hardware.org/?probe=a587179a2f) | May 16, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BS... | [0fd753db6d](https://linux-hardware.org/?probe=0fd753db6d) | May 16, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [8ab7fe837d](https://linux-hardware.org/?probe=8ab7fe837d) | May 16, 2023 |
| HP            | EliteBook 840 G5            | [7b8c68cfcf](https://linux-hardware.org/?probe=7b8c68cfcf) | May 13, 2023 |
| ASUSTek       | Zenbook UM6702RA_RM6702R... | [a25f9e8d93](https://linux-hardware.org/?probe=a25f9e8d93) | May 13, 2023 |
| ASUSTek       | Zenbook UM6702RA_RM6702R... | [d2ba323017](https://linux-hardware.org/?probe=d2ba323017) | May 13, 2023 |
| HUAWEI        | BOHB-WAX9                   | [89747b6213](https://linux-hardware.org/?probe=89747b6213) | May 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | [17510fcd4f](https://linux-hardware.org/?probe=17510fcd4f) | May 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | [6eb320d381](https://linux-hardware.org/?probe=6eb320d381) | May 12, 2023 |
| HP            | ProBook 640 G1              | [4bbb20185b](https://linux-hardware.org/?probe=4bbb20185b) | May 12, 2023 |
| HP            | ProBook 640 G1              | [f89a68e432](https://linux-hardware.org/?probe=f89a68e432) | May 12, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E02    | [d90b0e6626](https://linux-hardware.org/?probe=d90b0e6626) | May 12, 2023 |
| HP            | ProBook 440 14 inch G9 N... | [a07acb448b](https://linux-hardware.org/?probe=a07acb448b) | May 12, 2023 |
| Lenovo        | ThinkPad X260 20F600A7MS    | [67daafed56](https://linux-hardware.org/?probe=67daafed56) | May 12, 2023 |
| HP            | ProBook 6470b               | [7f1a6e0d48](https://linux-hardware.org/?probe=7f1a6e0d48) | May 12, 2023 |
| HP            | ProBook 440 14 inch G9 N... | [f4df381f0e](https://linux-hardware.org/?probe=f4df381f0e) | May 12, 2023 |
| Lenovo        | ThinkPad T440 20B7S2SM00    | [8f6bd394c4](https://linux-hardware.org/?probe=8f6bd394c4) | May 12, 2023 |
| ASUSTek       | Zenbook UM6702RA_RM6702R... | [ba177fa007](https://linux-hardware.org/?probe=ba177fa007) | May 12, 2023 |
| HUAWEI        | MACHD-WXX9                  | [f5d0a04a09](https://linux-hardware.org/?probe=f5d0a04a09) | May 12, 2023 |
| Dell          | XPS 9315                    | [d53e7f5d92](https://linux-hardware.org/?probe=d53e7f5d92) | May 11, 2023 |
| Dell          | Precision 5520              | [5dfdbeff37](https://linux-hardware.org/?probe=5dfdbeff37) | May 10, 2023 |
| Dell          | XPS 15 9560                 | [b904defc14](https://linux-hardware.org/?probe=b904defc14) | May 09, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [9b21cbbca0](https://linux-hardware.org/?probe=9b21cbbca0) | May 09, 2023 |
| Avell High... | A40 LIV                     | [c4c4a1fe74](https://linux-hardware.org/?probe=c4c4a1fe74) | May 09, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [1f874eaf6d](https://linux-hardware.org/?probe=1f874eaf6d) | May 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [36334e327a](https://linux-hardware.org/?probe=36334e327a) | May 08, 2023 |
| Lenovo        | ThinkPad X260 20F6CTO1WW    | [7998abcdcd](https://linux-hardware.org/?probe=7998abcdcd) | May 07, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [e0357a19f3](https://linux-hardware.org/?probe=e0357a19f3) | May 05, 2023 |
| Samsung       | 530U3C/530U4C/532U3C        | [d016282342](https://linux-hardware.org/?probe=d016282342) | May 05, 2023 |
| Avell High... | A40 LIV                     | [5745ae021d](https://linux-hardware.org/?probe=5745ae021d) | May 05, 2023 |
| Aquarius      | NS585                       | [817d9a6b62](https://linux-hardware.org/?probe=817d9a6b62) | May 04, 2023 |
| Aquarius      | NS585                       | [c629501448](https://linux-hardware.org/?probe=c629501448) | May 03, 2023 |
| Lenovo        | ThinkPad T495 20NK000XBR    | [c7ca4b1477](https://linux-hardware.org/?probe=c7ca4b1477) | May 03, 2023 |
| MSI           | Unknown                     | [917d7a7fc9](https://linux-hardware.org/?probe=917d7a7fc9) | May 03, 2023 |
| HP            | OMEN by Laptop              | [a60578cfe2](https://linux-hardware.org/?probe=a60578cfe2) | May 02, 2023 |
| Aquarius      | NS585                       | [e6922e974c](https://linux-hardware.org/?probe=e6922e974c) | May 02, 2023 |
| Toshiba       | Satellite X200              | [e1674b1234](https://linux-hardware.org/?probe=e1674b1234) | May 02, 2023 |
| Sony          | VPCF13WFX                   | [6500c354c7](https://linux-hardware.org/?probe=6500c354c7) | May 01, 2023 |
| Lenovo        | Slim 9 14IAP7 82T1          | [fe1b421c9d](https://linux-hardware.org/?probe=fe1b421c9d) | May 01, 2023 |
| HP            | 255 G8 Notebook PC          | [7262375294](https://linux-hardware.org/?probe=7262375294) | Apr 30, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [0a9a85f5f0](https://linux-hardware.org/?probe=0a9a85f5f0) | Apr 29, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [83b10185e8](https://linux-hardware.org/?probe=83b10185e8) | Apr 29, 2023 |
| Aquarius      | NS585                       | [b23696ca41](https://linux-hardware.org/?probe=b23696ca41) | Apr 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [2474e8e580](https://linux-hardware.org/?probe=2474e8e580) | Apr 27, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [2093399e21](https://linux-hardware.org/?probe=2093399e21) | Apr 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M640... | [0234325d36](https://linux-hardware.org/?probe=0234325d36) | Apr 26, 2023 |
| Aquarius      | NS585                       | [a0983c89d8](https://linux-hardware.org/?probe=a0983c89d8) | Apr 25, 2023 |
| Aquarius      | NS585                       | [5d9edb6ed4](https://linux-hardware.org/?probe=5d9edb6ed4) | Apr 25, 2023 |
| Aquarius      | NS585                       | [972d7f6e4a](https://linux-hardware.org/?probe=972d7f6e4a) | Apr 25, 2023 |
| Aquarius      | NS585                       | [c89bbd8bc0](https://linux-hardware.org/?probe=c89bbd8bc0) | Apr 25, 2023 |
| Aquarius      | NS585                       | [a6e5a5f3d1](https://linux-hardware.org/?probe=a6e5a5f3d1) | Apr 25, 2023 |
| Aquarius      | NS585                       | [b6dac5b058](https://linux-hardware.org/?probe=b6dac5b058) | Apr 25, 2023 |
| Aquarius      | NS585                       | [1563889dac](https://linux-hardware.org/?probe=1563889dac) | Apr 25, 2023 |
| Aquarius      | NS585                       | [9bdbad2ab7](https://linux-hardware.org/?probe=9bdbad2ab7) | Apr 25, 2023 |
| Aquarius      | NS585                       | [e30d7dde7b](https://linux-hardware.org/?probe=e30d7dde7b) | Apr 25, 2023 |
| Aquarius      | NS585                       | [68527a900f](https://linux-hardware.org/?probe=68527a900f) | Apr 25, 2023 |
| Aquarius      | NS585                       | [ce99b27fb4](https://linux-hardware.org/?probe=ce99b27fb4) | Apr 25, 2023 |
| Aquarius      | NS585                       | [fc377acae2](https://linux-hardware.org/?probe=fc377acae2) | Apr 25, 2023 |
| Aquarius      | NS585                       | [ed32f24d6e](https://linux-hardware.org/?probe=ed32f24d6e) | Apr 25, 2023 |
| Aquarius      | NS585                       | [ea60267a5b](https://linux-hardware.org/?probe=ea60267a5b) | Apr 25, 2023 |
| Aquarius      | NS585                       | [f71897bf76](https://linux-hardware.org/?probe=f71897bf76) | Apr 25, 2023 |
| Aquarius      | NS585                       | [7aa4561ca5](https://linux-hardware.org/?probe=7aa4561ca5) | Apr 25, 2023 |
| Aquarius      | NS585                       | [385ce8cd93](https://linux-hardware.org/?probe=385ce8cd93) | Apr 25, 2023 |
| Aquarius      | NS585                       | [3fc8926a1a](https://linux-hardware.org/?probe=3fc8926a1a) | Apr 25, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [9e6ce2eb71](https://linux-hardware.org/?probe=9e6ce2eb71) | Apr 25, 2023 |
| Aquarius      | NS585                       | [58306d0266](https://linux-hardware.org/?probe=58306d0266) | Apr 25, 2023 |
| HP            | ProBook 4520s               | [b680525b61](https://linux-hardware.org/?probe=b680525b61) | Apr 24, 2023 |
| HP            | ProBook 4520s               | [e4ce7aed55](https://linux-hardware.org/?probe=e4ce7aed55) | Apr 24, 2023 |
| Hampoo        | Cherry Trail CR V200        | [f3d90b0d4a](https://linux-hardware.org/?probe=f3d90b0d4a) | Apr 23, 2023 |
| Acer          | Aspire E1-571G              | [0e2671ee2e](https://linux-hardware.org/?probe=0e2671ee2e) | Apr 23, 2023 |
| Dell          | G15 5520                    | [238c8f53aa](https://linux-hardware.org/?probe=238c8f53aa) | Apr 22, 2023 |
| Dell          | Latitude E6330              | [b532a9756c](https://linux-hardware.org/?probe=b532a9756c) | Apr 22, 2023 |
| Acer          | Nitro AN515-45              | [91f538e2ab](https://linux-hardware.org/?probe=91f538e2ab) | Apr 21, 2023 |
| Lenovo        | IdeaPad S510p 20298         | [8a1e6b7f32](https://linux-hardware.org/?probe=8a1e6b7f32) | Apr 21, 2023 |
| HP            | ZBook Power 15.6 inch G9... | [036616c992](https://linux-hardware.org/?probe=036616c992) | Apr 21, 2023 |
| HP            | ZBook Power 15.6 inch G8... | [cb40e046d8](https://linux-hardware.org/?probe=cb40e046d8) | Apr 21, 2023 |
| Toshiba       | Satellite X200              | [15035835d0](https://linux-hardware.org/?probe=15035835d0) | Apr 20, 2023 |
| HP            | Notebook                    | [7174065ed3](https://linux-hardware.org/?probe=7174065ed3) | Apr 20, 2023 |
| Aquarius      | NS585                       | [753222f54f](https://linux-hardware.org/?probe=753222f54f) | Apr 20, 2023 |
| Aquarius      | NS585                       | [be0bc2be01](https://linux-hardware.org/?probe=be0bc2be01) | Apr 20, 2023 |
| HP            | EliteBook 830 G5            | [6090be709d](https://linux-hardware.org/?probe=6090be709d) | Apr 20, 2023 |
| Aquarius      | NS585                       | [f7f0464c39](https://linux-hardware.org/?probe=f7f0464c39) | Apr 20, 2023 |
| Aquarius      | NS585                       | [8393642230](https://linux-hardware.org/?probe=8393642230) | Apr 20, 2023 |
| Aquarius      | NS585                       | [a5b9a09e63](https://linux-hardware.org/?probe=a5b9a09e63) | Apr 20, 2023 |
| Medion        | P17605                      | [b68359f3d1](https://linux-hardware.org/?probe=b68359f3d1) | Apr 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [d669bcc680](https://linux-hardware.org/?probe=d669bcc680) | Apr 19, 2023 |
| Tactus        | GeoBook 140                 | [704da241f5](https://linux-hardware.org/?probe=704da241f5) | Apr 18, 2023 |
| Dell          | Vostro 5402                 | [e492c87b46](https://linux-hardware.org/?probe=e492c87b46) | Apr 18, 2023 |
| Dell          | Vostro 5402                 | [b15f47258b](https://linux-hardware.org/?probe=b15f47258b) | Apr 18, 2023 |
| PC Special... | NV4XMB,ME,MZ                | [65c0a28c58](https://linux-hardware.org/?probe=65c0a28c58) | Apr 18, 2023 |
| Lenovo        | IdeaPad S510p 20298         | [7f0be1868e](https://linux-hardware.org/?probe=7f0be1868e) | Apr 18, 2023 |
| MSI           | Prestige 15 A12UC           | [0f4c1e1ac3](https://linux-hardware.org/?probe=0f4c1e1ac3) | Apr 18, 2023 |
| ASUSTek       | G551JW                      | [65f6143e36](https://linux-hardware.org/?probe=65f6143e36) | Apr 18, 2023 |
| Lenovo        | ThinkPad L540 20AUA39QJP    | [180ef53338](https://linux-hardware.org/?probe=180ef53338) | Apr 18, 2023 |
| Lenovo        | ThinkPad L540 20AUA39QJP    | [fd3b20c292](https://linux-hardware.org/?probe=fd3b20c292) | Apr 18, 2023 |
| LG Electro... | 17Z90Q-K.AA78A1             | [594a7fa16b](https://linux-hardware.org/?probe=594a7fa16b) | Apr 18, 2023 |
| IBM           | ThinkPad R51 1836Q4U        | [ebec8b53eb](https://linux-hardware.org/?probe=ebec8b53eb) | Apr 18, 2023 |
| Acer          | Swift SF314-41              | [8c42a0aba8](https://linux-hardware.org/?probe=8c42a0aba8) | Apr 16, 2023 |
| Dell          | XPS 13 9305                 | [838519057f](https://linux-hardware.org/?probe=838519057f) | Apr 16, 2023 |
| HP            | 255 G8 Notebook PC          | [58ec498e8f](https://linux-hardware.org/?probe=58ec498e8f) | Apr 14, 2023 |
| Toshiba       | Satellite L850              | [15de4db91b](https://linux-hardware.org/?probe=15de4db91b) | Apr 14, 2023 |
| Dell          | G15 5510                    | [6b4ef54307](https://linux-hardware.org/?probe=6b4ef54307) | Apr 13, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [60f7db51fa](https://linux-hardware.org/?probe=60f7db51fa) | Apr 13, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [e9708d65e9](https://linux-hardware.org/?probe=e9708d65e9) | Apr 13, 2023 |
| Dell          | Latitude 5490               | [38ebdedf58](https://linux-hardware.org/?probe=38ebdedf58) | Apr 12, 2023 |
| Acer          | Aspire E1-571G              | [45a3503764](https://linux-hardware.org/?probe=45a3503764) | Apr 11, 2023 |
| Aquarius      | NS585                       | [6f4b987640](https://linux-hardware.org/?probe=6f4b987640) | Apr 11, 2023 |
| Dell          | Latitude 3320               | [b7c2bb88b3](https://linux-hardware.org/?probe=b7c2bb88b3) | Apr 10, 2023 |
| Dell          | Latitude 3320               | [436e7b8903](https://linux-hardware.org/?probe=436e7b8903) | Apr 10, 2023 |
| Lenovo        | Yoga 500-15IBD 80N6         | [885fff9ddb](https://linux-hardware.org/?probe=885fff9ddb) | Apr 10, 2023 |
| Lenovo        | ThinkPad X220 4291LR6       | [ea86227d59](https://linux-hardware.org/?probe=ea86227d59) | Apr 09, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | [8d4288ca33](https://linux-hardware.org/?probe=8d4288ca33) | Apr 09, 2023 |
| eMachines     | eME728                      | [aff08e7f2d](https://linux-hardware.org/?probe=aff08e7f2d) | Apr 05, 2023 |
| eMachines     | eMachiens G443              | [58c297218a](https://linux-hardware.org/?probe=58c297218a) | Apr 05, 2023 |
| System76      | Lemur Pro                   | [2232424d5a](https://linux-hardware.org/?probe=2232424d5a) | Apr 05, 2023 |
| HONOR         | NMH-WCX9                    | [9ea45909a2](https://linux-hardware.org/?probe=9ea45909a2) | Apr 05, 2023 |
| Framework     | Laptop                      | [5bb187865d](https://linux-hardware.org/?probe=5bb187865d) | Apr 04, 2023 |
| Packard Be... | EasyNote TJ65               | [cd6a05149d](https://linux-hardware.org/?probe=cd6a05149d) | Apr 02, 2023 |
| Schenker      | XMG CORE (REN/M20)          | [50e9dee7b1](https://linux-hardware.org/?probe=50e9dee7b1) | Apr 01, 2023 |
| HP            | EliteBook 840 G5            | [3c509a7075](https://linux-hardware.org/?probe=3c509a7075) | Apr 01, 2023 |
| Tactus        | GeoBook 140                 | [0ceb5a3b7c](https://linux-hardware.org/?probe=0ceb5a3b7c) | Apr 01, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [a9e7ad7ecd](https://linux-hardware.org/?probe=a9e7ad7ecd) | Mar 29, 2023 |
| MSI           | Prestige 14Evo A11M         | [fc06b01f31](https://linux-hardware.org/?probe=fc06b01f31) | Mar 29, 2023 |
| MSI           | Prestige 14Evo A11M         | [5ac693dbd4](https://linux-hardware.org/?probe=5ac693dbd4) | Mar 29, 2023 |
| Acer          | Nitro AN515-43              | [47c758c261](https://linux-hardware.org/?probe=47c758c261) | Mar 29, 2023 |
| THUNDEROBO... | 911 Plus                    | [6617ad47b7](https://linux-hardware.org/?probe=6617ad47b7) | Mar 28, 2023 |
| Google        | Swanky                      | [0f32e48b38](https://linux-hardware.org/?probe=0f32e48b38) | Mar 28, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21B9C... | [0744b26f5c](https://linux-hardware.org/?probe=0744b26f5c) | Mar 27, 2023 |
| GPD           | P3 MAX                      | [b3627909f1](https://linux-hardware.org/?probe=b3627909f1) | Mar 27, 2023 |
| Dell          | Latitude E5430 non-vPro     | [17794caffa](https://linux-hardware.org/?probe=17794caffa) | Mar 27, 2023 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | [7cd7234999](https://linux-hardware.org/?probe=7cd7234999) | Mar 27, 2023 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | [2d83ebd124](https://linux-hardware.org/?probe=2d83ebd124) | Mar 26, 2023 |
| Dell          | Precision 5570              | [454590a1a8](https://linux-hardware.org/?probe=454590a1a8) | Mar 26, 2023 |
| Dell          | Latitude E6330              | [32833b4683](https://linux-hardware.org/?probe=32833b4683) | Mar 25, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [9b9a21b7da](https://linux-hardware.org/?probe=9b9a21b7da) | Mar 24, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [58f8d5849a](https://linux-hardware.org/?probe=58f8d5849a) | Mar 24, 2023 |
| Toshiba       | Satellite C50-B             | [4b563f19dd](https://linux-hardware.org/?probe=4b563f19dd) | Mar 24, 2023 |
| Sony          | SVE1512M6ESI                | [db00c70eb7](https://linux-hardware.org/?probe=db00c70eb7) | Mar 24, 2023 |
| Acer          | Aspire VN7-791              | [054efde4e8](https://linux-hardware.org/?probe=054efde4e8) | Mar 22, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [1f5d2a057c](https://linux-hardware.org/?probe=1f5d2a057c) | Mar 22, 2023 |
| Lenovo        | ThinkPad T440 20B7S3N304    | [af39e826be](https://linux-hardware.org/?probe=af39e826be) | Mar 22, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [de7c628210](https://linux-hardware.org/?probe=de7c628210) | Mar 22, 2023 |
| Toshiba       | Satellite C50-B             | [b9bf22cc53](https://linux-hardware.org/?probe=b9bf22cc53) | Mar 20, 2023 |
| Dell          | G3 3590                     | [cba689e7f5](https://linux-hardware.org/?probe=cba689e7f5) | Mar 20, 2023 |
| ASUSTek       | ZenBook 13 UX331UAL         | [9d44bf5769](https://linux-hardware.org/?probe=9d44bf5769) | Mar 20, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [d58b6cfe61](https://linux-hardware.org/?probe=d58b6cfe61) | Mar 18, 2023 |
| Aquarius      | NS585                       | [cd1e92458f](https://linux-hardware.org/?probe=cd1e92458f) | Mar 17, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [66f4a76724](https://linux-hardware.org/?probe=66f4a76724) | Mar 17, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [b50b834744](https://linux-hardware.org/?probe=b50b834744) | Mar 16, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [f3ee556fb5](https://linux-hardware.org/?probe=f3ee556fb5) | Mar 16, 2023 |
| HP            | EliteBook 830 G5            | [c6aa050dd1](https://linux-hardware.org/?probe=c6aa050dd1) | Mar 16, 2023 |
| HP            | ProBook 430 G8 Notebook ... | [ca6ab3c197](https://linux-hardware.org/?probe=ca6ab3c197) | Mar 16, 2023 |
| TUXEDO        | Aura 15 Gen2                | [15d4cdae49](https://linux-hardware.org/?probe=15d4cdae49) | Mar 14, 2023 |
| Acer          | Aspire E5-551G              | [7a992ff109](https://linux-hardware.org/?probe=7a992ff109) | Mar 14, 2023 |
| Schenker      | VIA 15 Pro                  | [ef02f8156e](https://linux-hardware.org/?probe=ef02f8156e) | Mar 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [cc878090ee](https://linux-hardware.org/?probe=cc878090ee) | Mar 13, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | [f762c7cc29](https://linux-hardware.org/?probe=f762c7cc29) | Mar 13, 2023 |
| Lenovo        | Legion 5 15IAH7H 82RB       | [9841e70d67](https://linux-hardware.org/?probe=9841e70d67) | Mar 13, 2023 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | [fd6d58db15](https://linux-hardware.org/?probe=fd6d58db15) | Mar 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [55a73e2e07](https://linux-hardware.org/?probe=55a73e2e07) | Mar 12, 2023 |
| HP            | Pavilion Notebook           | [158d246d65](https://linux-hardware.org/?probe=158d246d65) | Mar 11, 2023 |
| Dell          | Precision 5570              | [470ba58973](https://linux-hardware.org/?probe=470ba58973) | Mar 11, 2023 |
| Dell          | Latitude 3320               | [2a58a07005](https://linux-hardware.org/?probe=2a58a07005) | Mar 11, 2023 |
| Dell          | Latitude 3320               | [d17364c0ef](https://linux-hardware.org/?probe=d17364c0ef) | Mar 11, 2023 |
| Dell          | XPS 13 9310                 | [c528b16696](https://linux-hardware.org/?probe=c528b16696) | Mar 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [276ce8bd7c](https://linux-hardware.org/?probe=276ce8bd7c) | Mar 09, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [5bc1f5d6d8](https://linux-hardware.org/?probe=5bc1f5d6d8) | Mar 09, 2023 |
| Dell          | Precision 3560              | [0873d45206](https://linux-hardware.org/?probe=0873d45206) | Mar 08, 2023 |
| Dell          | XPS 15 9570                 | [fc0152a6de](https://linux-hardware.org/?probe=fc0152a6de) | Mar 08, 2023 |
| Acer          | Nitro AN515-43              | [32d1af5dee](https://linux-hardware.org/?probe=32d1af5dee) | Mar 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [ac92e5ce13](https://linux-hardware.org/?probe=ac92e5ce13) | Mar 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [92f8093adb](https://linux-hardware.org/?probe=92f8093adb) | Mar 07, 2023 |
| HP            | EliteBook 830 G7 Noteboo... | [cee8496315](https://linux-hardware.org/?probe=cee8496315) | Mar 06, 2023 |
| ASUSTek       | X550JX                      | [a9a82b2395](https://linux-hardware.org/?probe=a9a82b2395) | Mar 06, 2023 |
| Fujitsu       | LIFEBOOK U9312              | [19a72f502b](https://linux-hardware.org/?probe=19a72f502b) | Mar 06, 2023 |
| MSI           | Modern 15 A5M               | [7d708fea96](https://linux-hardware.org/?probe=7d708fea96) | Mar 06, 2023 |
| HUAWEI        | BOHB-WAX9                   | [eb5b9b8cb9](https://linux-hardware.org/?probe=eb5b9b8cb9) | Mar 06, 2023 |
| Lenovo        | ThinkPad T440p 20AWS37F0... | [48677f9f86](https://linux-hardware.org/?probe=48677f9f86) | Mar 05, 2023 |
| Toshiba       | Satellite A200              | [b9677c823b](https://linux-hardware.org/?probe=b9677c823b) | Mar 05, 2023 |
| Toshiba       | Satellite A200              | [47f08e4094](https://linux-hardware.org/?probe=47f08e4094) | Mar 04, 2023 |
| Dell          | Vostro 3700                 | [ea14c47abb](https://linux-hardware.org/?probe=ea14c47abb) | Mar 04, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [c4def038d9](https://linux-hardware.org/?probe=c4def038d9) | Mar 04, 2023 |
| Dell          | XPS 15 9520                 | [1bef11c91d](https://linux-hardware.org/?probe=1bef11c91d) | Mar 04, 2023 |
| Lenovo        | ThinkPad X220 429035U       | [83266c1006](https://linux-hardware.org/?probe=83266c1006) | Mar 04, 2023 |
| Notebook      | NS5x_NS7xPU                 | [55ca2f6ac5](https://linux-hardware.org/?probe=55ca2f6ac5) | Mar 03, 2023 |
| HP            | Laptop 17-bs0xx             | [e055e73b69](https://linux-hardware.org/?probe=e055e73b69) | Mar 02, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | [e56350a1c1](https://linux-hardware.org/?probe=e56350a1c1) | Feb 28, 2023 |
| ASUSTek       | UX31A                       | [56654a2659](https://linux-hardware.org/?probe=56654a2659) | Feb 27, 2023 |
| Dell          | G3 3590                     | [eb9009fad9](https://linux-hardware.org/?probe=eb9009fad9) | Feb 27, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [7d7953a826](https://linux-hardware.org/?probe=7d7953a826) | Feb 26, 2023 |
| Lenovo        | ThinkPad T440s 20AQ009DG... | [27e2d41750](https://linux-hardware.org/?probe=27e2d41750) | Feb 24, 2023 |
| Shanghai Z... | ZXE CRB                     | [478a4b921f](https://linux-hardware.org/?probe=478a4b921f) | Feb 24, 2023 |
| Dell          | Latitude 7530               | [4844568edb](https://linux-hardware.org/?probe=4844568edb) | Feb 21, 2023 |
| Dell          | Inspiron 3468               | [e5977ee094](https://linux-hardware.org/?probe=e5977ee094) | Feb 21, 2023 |
| HP            | EliteBook 830 G5            | [0cb773d407](https://linux-hardware.org/?probe=0cb773d407) | Feb 20, 2023 |
| Dell          | XPS 13 9370                 | [e710561f68](https://linux-hardware.org/?probe=e710561f68) | Feb 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [5300c136fd](https://linux-hardware.org/?probe=5300c136fd) | Feb 19, 2023 |
| HP            | Laptop 17-bs0xx             | [cc805e31b0](https://linux-hardware.org/?probe=cc805e31b0) | Feb 17, 2023 |
| Lenovo        | ThinkPad T61p 6457UN2       | [02e6818311](https://linux-hardware.org/?probe=02e6818311) | Feb 17, 2023 |
| Dell          | Precision 5570              | [d5f9d13ae3](https://linux-hardware.org/?probe=d5f9d13ae3) | Feb 16, 2023 |
| Dell          | Precision 5570              | [d0f2fa25c3](https://linux-hardware.org/?probe=d0f2fa25c3) | Feb 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [13866e78a2](https://linux-hardware.org/?probe=13866e78a2) | Feb 15, 2023 |
| ASUSTek       | X505BP                      | [579388a539](https://linux-hardware.org/?probe=579388a539) | Feb 13, 2023 |
| Dell          | Latitude E6330              | [1b5cdf846f](https://linux-hardware.org/?probe=1b5cdf846f) | Feb 11, 2023 |
| Lenovo        | ThinkPad SL510 28477MG      | [8f22e1beaa](https://linux-hardware.org/?probe=8f22e1beaa) | Feb 10, 2023 |
| Samsung       | 550XDA                      | [45d947c9f9](https://linux-hardware.org/?probe=45d947c9f9) | Feb 10, 2023 |
| HP            | Laptop 17-bs0xx             | [84eb5f0ad8](https://linux-hardware.org/?probe=84eb5f0ad8) | Feb 09, 2023 |
| Dell          | Precision 5570              | [6c257e667d](https://linux-hardware.org/?probe=6c257e667d) | Feb 08, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [d37cc19110](https://linux-hardware.org/?probe=d37cc19110) | Feb 08, 2023 |
| Dell          | Precision 5570              | [e81b3de663](https://linux-hardware.org/?probe=e81b3de663) | Feb 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [eca3a05d41](https://linux-hardware.org/?probe=eca3a05d41) | Feb 07, 2023 |
| Dell          | Latitude E5430 non-vPro     | [7d2d46a579](https://linux-hardware.org/?probe=7d2d46a579) | Feb 06, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian_12/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 6.1.0-9-amd64                   | 171       | 27.71%  |
| 6.1.0-10-amd64                  | 144       | 23.34%  |
| 6.1.0-11-amd64                  | 71        | 11.51%  |
| 6.1.0-7-amd64                   | 50        | 8.1%    |
| 6.1.0-4-amd64                   | 40        | 6.48%   |
| 6.1.0-6-amd64                   | 28        | 4.54%   |
| 6.1.0-5-amd64                   | 21        | 3.4%    |
| 6.1.0-3-amd64                   | 20        | 3.24%   |
| 6.1.0-8-amd64                   | 8         | 1.3%    |
| 6.1.0-10-686-pae                | 6         | 0.97%   |
| 6.2.16-3-pve                    | 3         | 0.49%   |
| 6.0.0-2-amd64                   | 3         | 0.49%   |
| 6.4.3-1-liquorix-amd64          | 2         | 0.32%   |
| 6.4.0-1-amd64                   | 2         | 0.32%   |
| 6.2.16-6-pve                    | 2         | 0.32%   |
| 6.1.0-9-686-pae                 | 2         | 0.32%   |
| 6.1.0-7-rt-amd64                | 2         | 0.32%   |
| 6.0.0-6-amd64                   | 2         | 0.32%   |
| 6.0.0-0.deb11.6-amd64           | 2         | 0.32%   |
| 6.5.0-rc5                       | 1         | 0.16%   |
| 6.5.0-060500-generic            | 1         | 0.16%   |
| 6.4.9-1-liquorix-amd64          | 1         | 0.16%   |
| 6.4.7-1-liquorix-amd64          | 1         | 0.16%   |
| 6.4.2-surface                   | 1         | 0.16%   |
| 6.4.2-edwardron-amd64           | 1         | 0.16%   |
| 6.4.0-asahi-00515-g35564c906fa6 | 1         | 0.16%   |
| 6.4.0-1mx-ahs-amd64             | 1         | 0.16%   |
| 6.4.0-0.deb12.2-amd64           | 1         | 0.16%   |
| 6.3.9-1-liquorix-amd64          | 1         | 0.16%   |
| 6.3.8-1-liquorix-amd64          | 1         | 0.16%   |
| 6.3.10-1-liquorix-amd64         | 1         | 0.16%   |
| 6.3.0-7-amd64                   | 1         | 0.16%   |
| 6.3.0-2-amd64                   | 1         | 0.16%   |
| 6.3.0-1-amd64                   | 1         | 0.16%   |
| 6.2.8                           | 1         | 0.16%   |
| 6.2.16-8-pve                    | 1         | 0.16%   |
| 6.2.11                          | 1         | 0.16%   |
| 6.1.38-icbinu                   | 1         | 0.16%   |
| 6.1.38-cuerdos-amd              | 1         | 0.16%   |
| 6.1.12+                         | 1         | 0.16%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1.0   | 542       | 92.02%  |
| 6.0.0   | 8         | 1.36%   |
| 6.2.16  | 6         | 1.02%   |
| 6.4.0   | 5         | 0.85%   |
| 5.10.0  | 5         | 0.85%   |
| 6.3.0   | 3         | 0.51%   |
| 6.5.0   | 2         | 0.34%   |
| 6.4.3   | 2         | 0.34%   |
| 6.4.2   | 2         | 0.34%   |
| 6.1.38  | 2         | 0.34%   |
| 6.4.9   | 1         | 0.17%   |
| 6.4.7   | 1         | 0.17%   |
| 6.3.9   | 1         | 0.17%   |
| 6.3.8   | 1         | 0.17%   |
| 6.3.10  | 1         | 0.17%   |
| 6.2.8   | 1         | 0.17%   |
| 6.2.11  | 1         | 0.17%   |
| 6.1.12  | 1         | 0.17%   |
| 6.1.11  | 1         | 0.17%   |
| 5.19.0  | 1         | 0.17%   |
| 5.16.0  | 1         | 0.17%   |
| 5.15.95 | 1         | 0.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1     | 546       | 92.7%   |
| 6.4     | 11        | 1.87%   |
| 6.2     | 8         | 1.36%   |
| 6.0     | 8         | 1.36%   |
| 6.3     | 6         | 1.02%   |
| 5.10    | 5         | 0.85%   |
| 6.5     | 2         | 0.34%   |
| 5.19    | 1         | 0.17%   |
| 5.16    | 1         | 0.17%   |
| 5.15    | 1         | 0.17%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 574       | 97.79%  |
| i686    | 11        | 1.87%   |
| armv7l  | 1         | 0.17%   |
| aarch64 | 1         | 0.17%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 228       | 38.58%  |
| KDE5             | 119       | 20.14%  |
| Unknown          | 81        | 13.71%  |
| XFCE             | 58        | 9.81%   |
| X-Cinnamon       | 38        | 6.43%   |
| MATE             | 22        | 3.72%   |
| LXQt             | 9         | 1.52%   |
| LXDE             | 7         | 1.18%   |
| i3               | 7         | 1.18%   |
| GNOME Flashback  | 4         | 0.68%   |
| Cinnamon         | 4         | 0.68%   |
| GNOME Classic    | 2         | 0.34%   |
| Enlightenment    | 2         | 0.34%   |
| xmonad           | 1         | 0.17%   |
| Trinity          | 1         | 0.17%   |
| sway             | 1         | 0.17%   |
| Pantheon         | 1         | 0.17%   |
| lightdm-xsession | 1         | 0.17%   |
| KDE              | 1         | 0.17%   |
| dwm              | 1         | 0.17%   |
| Budgie           | 1         | 0.17%   |
| bspwm            | 1         | 0.17%   |
| awesome          | 1         | 0.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 272       | 45.56%  |
| Wayland | 234       | 39.2%   |
| Unknown | 62        | 10.39%  |
| Tty     | 29        | 4.86%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 204       | 34.4%   |
| GDM3    | 180       | 30.35%  |
| LightDM | 107       | 18.04%  |
| SDDM    | 94        | 15.85%  |
| Ly      | 2         | 0.34%   |
| LXDM    | 2         | 0.34%   |
| GREETD  | 2         | 0.34%   |
| GDM     | 2         | 0.34%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 217       | 36.84%  |
| ru_RU   | 69        | 11.71%  |
| de_DE   | 39        | 6.62%   |
| fr_FR   | 37        | 6.28%   |
| en_GB   | 35        | 5.94%   |
| Unknown | 23        | 3.9%    |
| pt_BR   | 21        | 3.57%   |
| sv_SE   | 13        | 2.21%   |
| es_ES   | 11        | 1.87%   |
| en_IN   | 10        | 1.7%    |
| en_CA   | 10        | 1.7%    |
| zh_CN   | 8         | 1.36%   |
| it_IT   | 8         | 1.36%   |
| en_AU   | 7         | 1.19%   |
| C       | 7         | 1.19%   |
| pl_PL   | 6         | 1.02%   |
| es_CL   | 5         | 0.85%   |
| nl_NL   | 4         | 0.68%   |
| hu_HU   | 4         | 0.68%   |
| en_IE   | 4         | 0.68%   |
| ca_ES   | 4         | 0.68%   |
| es_VE   | 3         | 0.51%   |
| cs_CZ   | 3         | 0.51%   |
| be_BY   | 3         | 0.51%   |
| tr_TR   | 2         | 0.34%   |
| pt_PT   | 2         | 0.34%   |
| es_MX   | 2         | 0.34%   |
| en_NZ   | 2         | 0.34%   |
| en_IL   | 2         | 0.34%   |
| en_DK   | 2         | 0.34%   |
| zh_TW   | 1         | 0.17%   |
| zh_SG   | 1         | 0.17%   |
| uk_UA   | 1         | 0.17%   |
| sk_SK   | 1         | 0.17%   |
| oc_FR   | 1         | 0.17%   |
| nn_NO   | 1         | 0.17%   |
| nl_BE   | 1         | 0.17%   |
| lv_LV   | 1         | 0.17%   |
| ko_KR   | 1         | 0.17%   |
| it_CH   | 1         | 0.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 364       | 61.9%   |
| BIOS | 224       | 38.1%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 455       | 77.38%  |
| Overlay | 82        | 13.95%  |
| Btrfs   | 34        | 5.78%   |
| Tmpfs   | 9         | 1.53%   |
| Xfs     | 5         | 0.85%   |
| Zfs     | 3         | 0.51%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 380       | 64.41%  |
| Unknown | 127       | 21.53%  |
| MBR     | 83        | 14.07%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 531       | 90%     |
| Yes       | 59        | 10%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 419       | 71.14%  |
| Yes       | 170       | 28.86%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 140       | 23.85%  |
| Dell                           | 83        | 14.14%  |
| Hewlett-Packard                | 82        | 13.97%  |
| ASUSTek Computer               | 55        | 9.37%   |
| Acer                           | 49        | 8.35%   |
| Aquarius                       | 29        | 4.94%   |
| Apple                          | 22        | 3.75%   |
| MSI                            | 16        | 2.73%   |
| HUAWEI                         | 11        | 1.87%   |
| Google                         | 11        | 1.87%   |
| Samsung Electronics            | 9         | 1.53%   |
| Sony                           | 8         | 1.36%   |
| Toshiba                        | 6         | 1.02%   |
| HONOR                          | 6         | 1.02%   |
| Unknown                        | 6         | 1.02%   |
| Fujitsu                        | 4         | 0.68%   |
| Framework                      | 4         | 0.68%   |
| eMachines                      | 4         | 0.68%   |
| Timi                           | 2         | 0.34%   |
| Schenker                       | 2         | 0.34%   |
| PC Specialist                  | 2         | 0.34%   |
| Notebook                       | 2         | 0.34%   |
| LG Electronics                 | 2         | 0.34%   |
| GPU Company                    | 2         | 0.34%   |
| Avell High Performance         | 2         | 0.34%   |
| Alienware                      | 2         | 0.34%   |
| win element                    | 1         | 0.17%   |
| Valve                          | 1         | 0.17%   |
| VALE                           | 1         | 0.17%   |
| TUXEDO                         | 1         | 0.17%   |
| THUNDEROBOT                    | 1         | 0.17%   |
| Terrans Force                  | 1         | 0.17%   |
| Tactus                         | 1         | 0.17%   |
| System76                       | 1         | 0.17%   |
| SLIMBOOK                       | 1         | 0.17%   |
| SIRAGON                        | 1         | 0.17%   |
| Shuttle                        | 1         | 0.17%   |
| Shanghai Zhaoxin Semiconductor | 1         | 0.17%   |
| Semp Toshiba                   | 1         | 0.17%   |
| Positivo                       | 1         | 0.17%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Aquarius NS585                           | 29        | 4.94%   |
| Unknown                                  | 7         | 1.19%   |
| Apple MacBookAir7,2                      | 6         | 1.02%   |
| Lenovo ThinkPad L14 Gen 2 20X1004CMX     | 4         | 0.68%   |
| Dell Precision 5570                      | 4         | 0.68%   |
| Lenovo ThinkPad 13 2nd Gen 20J10046US    | 3         | 0.51%   |
| HUAWEI BOHK-WAX9X                        | 3         | 0.51%   |
| HONOR NMH-WCX9                           | 3         | 0.51%   |
| HP Laptop 15s-eq2xxx                     | 3         | 0.51%   |
| HP EliteBook 845 G8 Notebook PC          | 3         | 0.51%   |
| HP EliteBook 840 G5                      | 3         | 0.51%   |
| HP EliteBook 840 G3                      | 3         | 0.51%   |
| Framework Laptop (13th Gen Intel Core)   | 3         | 0.51%   |
| Dell Latitude 7480                       | 3         | 0.51%   |
| Acer Aspire A515-56                      | 3         | 0.51%   |
| Lenovo ThinkPad L13 Gen 2 20VJS6RY00     | 2         | 0.34%   |
| Lenovo IdeaPad 5 14ALC05 82LM            | 2         | 0.34%   |
| Lenovo IdeaPad 3 15IML05 81WB            | 2         | 0.34%   |
| HUAWEI NBLK-WAX9X                        | 2         | 0.34%   |
| HUAWEI MACHD-WXX9                        | 2         | 0.34%   |
| HUAWEI BOHB-WAX9                         | 2         | 0.34%   |
| HP ProBook 640 G2                        | 2         | 0.34%   |
| HP ProBook 640 G1                        | 2         | 0.34%   |
| HP ProBook 440 14 inch G9 Notebook PC    | 2         | 0.34%   |
| HP Presario CQ57                         | 2         | 0.34%   |
| HP Pavilion Notebook                     | 2         | 0.34%   |
| HP Pavilion dv6                          | 2         | 0.34%   |
| HP OMEN by Laptop                        | 2         | 0.34%   |
| HP 255 G8 Notebook PC                    | 2         | 0.34%   |
| Google Enguarde                          | 2         | 0.34%   |
| Dell XPS 15 9570                         | 2         | 0.34%   |
| Dell XPS 13 9370                         | 2         | 0.34%   |
| Dell Latitude E6430                      | 2         | 0.34%   |
| Dell Latitude E6400                      | 2         | 0.34%   |
| Dell Latitude E6330                      | 2         | 0.34%   |
| Dell Latitude 3320                       | 2         | 0.34%   |
| Dell G3 3590                             | 2         | 0.34%   |
| ASUS Zenbook UX535QE_UM535QE             | 2         | 0.34%   |
| ASUS VivoBook_ASUSLaptop M3401QA_M3401QA | 2         | 0.34%   |
| Apple MacBookPro6,2                      | 2         | 0.34%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 96        | 16.35%  |
| Dell Latitude     | 32        | 5.45%   |
| Acer Aspire       | 32        | 5.45%   |
| Aquarius NS585    | 29        | 4.94%   |
| Lenovo IdeaPad    | 22        | 3.75%   |
| HP EliteBook      | 21        | 3.58%   |
| ASUS VivoBook     | 20        | 3.41%   |
| Dell XPS          | 15        | 2.56%   |
| Dell Inspiron     | 15        | 2.56%   |
| HP ProBook        | 13        | 2.21%   |
| HP Laptop         | 13        | 2.21%   |
| HP Pavilion       | 11        | 1.87%   |
| Dell Precision    | 8         | 1.36%   |
| ASUS ZenBook      | 8         | 1.36%   |
| Dell Vostro       | 7         | 1.19%   |
| Apple MacBookAir7 | 7         | 1.19%   |
| Unknown           | 7         | 1.19%   |
| Toshiba Satellite | 6         | 1.02%   |
| Lenovo Yoga       | 6         | 1.02%   |
| HP ZBook          | 6         | 1.02%   |
| Acer Nitro        | 6         | 1.02%   |
| Acer TravelMate   | 5         | 0.85%   |
| Lenovo Legion     | 4         | 0.68%   |
| Fujitsu LIFEBOOK  | 4         | 0.68%   |
| Framework Laptop  | 4         | 0.68%   |
| MSI Prestige      | 3         | 0.51%   |
| HUAWEI BOHK-WAX9X | 3         | 0.51%   |
| HONOR NMH-WCX9    | 3         | 0.51%   |
| HP OMEN           | 3         | 0.51%   |
| HP 255            | 3         | 0.51%   |
| ASUS ASUS         | 3         | 0.51%   |
| Acer Swift        | 3         | 0.51%   |
| MSI Modern        | 2         | 0.34%   |
| MSI Alpha         | 2         | 0.34%   |
| Lenovo B590       | 2         | 0.34%   |
| HUAWEI NBLK-WAX9X | 2         | 0.34%   |
| HUAWEI MACHD-WXX9 | 2         | 0.34%   |
| HUAWEI BOHB-WAX9  | 2         | 0.34%   |
| HP Victus         | 2         | 0.34%   |
| HP Presario       | 2         | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 93        | 15.84%  |
| 2022    | 76        | 12.95%  |
| 2019    | 71        | 12.1%   |
| 2020    | 60        | 10.22%  |
| 2018    | 36        | 6.13%   |
| 2017    | 33        | 5.62%   |
| 2012    | 32        | 5.45%   |
| 2013    | 27        | 4.6%    |
| 2016    | 22        | 3.75%   |
| 2011    | 22        | 3.75%   |
| 2010    | 21        | 3.58%   |
| 2015    | 20        | 3.41%   |
| 2023    | 19        | 3.24%   |
| 2014    | 16        | 2.73%   |
| 2009    | 16        | 2.73%   |
| 2008    | 13        | 2.21%   |
| 2007    | 4         | 0.68%   |
| 2005    | 3         | 0.51%   |
| Unknown | 2         | 0.34%   |
| 2004    | 1         | 0.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 587       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 512       | 87.07%  |
| Enabled  | 76        | 12.93%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 573       | 97.61%  |
| Yes  | 14        | 2.39%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 188       | 31.86%  |
| 16.01-24.0  | 119       | 20.17%  |
| 8.01-16.0   | 118       | 20%     |
| 3.01-4.0    | 68        | 11.53%  |
| 32.01-64.0  | 58        | 9.83%   |
| 1.01-2.0    | 13        | 2.2%    |
| 64.01-256.0 | 11        | 1.86%   |
| 2.01-3.0    | 9         | 1.53%   |
| 24.01-32.0  | 5         | 0.85%   |
| 0.51-1.0    | 1         | 0.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 146       | 24.05%  |
| 1.01-2.0   | 140       | 23.06%  |
| 4.01-8.0   | 132       | 21.75%  |
| 3.01-4.0   | 90        | 14.83%  |
| 0.51-1.0   | 56        | 9.23%   |
| 8.01-16.0  | 33        | 5.44%   |
| 0.01-0.5   | 6         | 0.99%   |
| 16.01-24.0 | 2         | 0.33%   |
| 32.01-64.0 | 1         | 0.16%   |
| 24.01-32.0 | 1         | 0.16%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 454       | 76.95%  |
| 2      | 113       | 19.15%  |
| 3      | 20        | 3.39%   |
| 4      | 2         | 0.34%   |
| 0      | 1         | 0.17%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 479       | 81.32%  |
| Yes       | 110       | 18.68%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 440       | 74.96%  |
| No        | 147       | 25.04%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 576       | 98.13%  |
| No        | 11        | 1.87%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 502       | 85.37%  |
| No        | 86        | 14.63%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 83        | 14.02%  |
| Russia      | 77        | 13.01%  |
| Germany     | 59        | 9.97%   |
| France      | 40        | 6.76%   |
| Brazil      | 30        | 5.07%   |
| Sweden      | 24        | 4.05%   |
| Spain       | 20        | 3.38%   |
| UK          | 18        | 3.04%   |
| Poland      | 17        | 2.87%   |
| Canada      | 17        | 2.87%   |
| Italy       | 16        | 2.7%    |
| Netherlands | 12        | 2.03%   |
| India       | 12        | 2.03%   |
| China       | 10        | 1.69%   |
| Turkey      | 9         | 1.52%   |
| Australia   | 9         | 1.52%   |
| Czechia     | 8         | 1.35%   |
| Austria     | 7         | 1.18%   |
| Hungary     | 6         | 1.01%   |
| Chile       | 6         | 1.01%   |
| Ukraine     | 5         | 0.84%   |
| Romania     | 5         | 0.84%   |
| Belarus     | 5         | 0.84%   |
| Venezuela   | 4         | 0.68%   |
| Switzerland | 4         | 0.68%   |
| Mexico      | 4         | 0.68%   |
| Indonesia   | 4         | 0.68%   |
| Costa Rica  | 4         | 0.68%   |
| Singapore   | 3         | 0.51%   |
| Portugal    | 3         | 0.51%   |
| Philippines | 3         | 0.51%   |
| New Zealand | 3         | 0.51%   |
| Israel      | 3         | 0.51%   |
| Hong Kong   | 3         | 0.51%   |
| Belgium     | 3         | 0.51%   |
| Uruguay     | 2         | 0.34%   |
| Slovakia    | 2         | 0.34%   |
| Norway      | 2         | 0.34%   |
| Madagascar  | 2         | 0.34%   |
| Lithuania   | 2         | 0.34%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Voronezh          | 40        | 6.61%   |
| Bangor            | 22        | 3.64%   |
| Moscow            | 19        | 3.14%   |
| Saltsjoe-Boo      | 13        | 2.15%   |
| Paris             | 7         | 1.16%   |
| Berlin            | 7         | 1.16%   |
| Toronto           | 5         | 0.83%   |
| Brasília         | 5         | 0.83%   |
| Wroclaw           | 4         | 0.66%   |
| Stockholm         | 4         | 0.66%   |
| St Petersburg     | 4         | 0.66%   |
| Marseille         | 4         | 0.66%   |
| London            | 4         | 0.66%   |
| Beijing           | 4         | 0.66%   |
| Vienna            | 3         | 0.5%    |
| Vancouver         | 3         | 0.5%    |
| Sydney            | 3         | 0.5%    |
| Singapore         | 3         | 0.5%    |
| Santiago          | 3         | 0.5%    |
| Prague            | 3         | 0.5%    |
| Munich            | 3         | 0.5%    |
| Mesa              | 3         | 0.5%    |
| Melbourne         | 3         | 0.5%    |
| Istanbul          | 3         | 0.5%    |
| Frankfurt am Main | 3         | 0.5%    |
| Bonn              | 3         | 0.5%    |
| Barcelona         | 3         | 0.5%    |
| Washington        | 2         | 0.33%   |
| Warsaw            | 2         | 0.33%   |
| Tiranges          | 2         | 0.33%   |
| Tbilisi           | 2         | 0.33%   |
| Seville           | 2         | 0.33%   |
| San Salvador      | 2         | 0.33%   |
| San José         | 2         | 0.33%   |
| San Francisco     | 2         | 0.33%   |
| Samara            | 2         | 0.33%   |
| Płock            | 2         | 0.33%   |
| Portland          | 2         | 0.33%   |
| Most              | 2         | 0.33%   |
| Montpellier       | 2         | 0.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 123       | 146    | 17.11%  |
| WDC                         | 71        | 80     | 9.87%   |
| SanDisk                     | 50        | 57     | 6.95%   |
| SK hynix                    | 48        | 52     | 6.68%   |
| A-DATA Technology           | 40        | 54     | 5.56%   |
| Seagate                     | 37        | 39     | 5.15%   |
| Unknown                     | 34        | 42     | 4.73%   |
| Micron Technology           | 34        | 36     | 4.73%   |
| Kingston                    | 33        | 36     | 4.59%   |
| Toshiba                     | 31        | 35     | 4.31%   |
| Intel                       | 24        | 26     | 3.34%   |
| Crucial                     | 21        | 24     | 2.92%   |
| Apple                       | 12        | 14     | 1.67%   |
| Hitachi                     | 11        | 11     | 1.53%   |
| KIOXIA                      | 10        | 12     | 1.39%   |
| HGST                        | 10        | 10     | 1.39%   |
| Kingston Technology Company | 9         | 10     | 1.25%   |
| Intenso                     | 7         | 7      | 0.97%   |
| China                       | 7         | 9      | 0.97%   |
| SSSTC                       | 6         | 6      | 0.83%   |
| SPCC                        | 6         | 7      | 0.83%   |
| Phison                      | 5         | 5      | 0.7%    |
| Fujitsu                     | 5         | 5      | 0.7%    |
| ADATA Technology            | 5         | 5      | 0.7%    |
| Patriot                     | 4         | 4      | 0.56%   |
| LITEON                      | 4         | 4      | 0.56%   |
| JMicron Technology          | 4         | 4      | 0.56%   |
| YMTC                        | 3         | 3      | 0.42%   |
| Silicon Motion              | 3         | 4      | 0.42%   |
| Realtek                     | 3         | 3      | 0.42%   |
| Netac                       | 3         | 3      | 0.42%   |
| Wibtek                      | 2         | 2      | 0.28%   |
| TO Exter                    | 2         | 3      | 0.28%   |
| Phison Electronics          | 2         | 3      | 0.28%   |
| OCZ                         | 2         | 2      | 0.28%   |
| Micron/Crucial Technology   | 2         | 2      | 0.28%   |
| LITEONIT                    | 2         | 2      | 0.28%   |
| Lexar                       | 2         | 2      | 0.28%   |
| KIOXIA-EXCERIA              | 2         | 2      | 0.28%   |
| Gigabyte Technology         | 2         | 2      | 0.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| A-DATA SU800 512GB SSD                                | 29        | 3.94%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB   | 11        | 1.49%   |
| Kingston SA400S37480G 480GB SSD                       | 9         | 1.22%   |
| Seagate ST1000LM035-1RK172 1TB                        | 8         | 1.09%   |
| Sandisk WD Blue SN550 NVMe SSD 250GB                  | 6         | 0.82%   |
| Samsung SSD 980 1TB                                   | 6         | 0.82%   |
| Crucial CT500MX500SSD1 500GB                          | 6         | 0.82%   |
| Toshiba MQ01ABF050 500GB                              | 5         | 0.68%   |
| SK hynix BC711 NVMe 256GB                             | 5         | 0.68%   |
| Samsung PM9A1 NVMe 1024GB                             | 5         | 0.68%   |
| Intel SSDPEKNU512GZ 512GB                             | 5         | 0.68%   |
| Apple SSD SM0128G 121GB                               | 5         | 0.68%   |
| Unknown MMC Card  64GB                                | 4         | 0.54%   |
| Toshiba XG6 NVMe SSD Controller 1024GB                | 4         | 0.54%   |
| SanDisk SD8SN8U128G1001 128GB SSD                     | 4         | 0.54%   |
| SanDisk NVMe SSD Drive 512GB                          | 4         | 0.54%   |
| Samsung SSD 860 EVO 500GB                             | 4         | 0.54%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1024GB | 4         | 0.54%   |
| Micron 2450_MTFDKBA512TFK 512GB                       | 4         | 0.54%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 3         | 0.41%   |
| Unknown SD32G  32GB                                   | 3         | 0.41%   |
| SK hynix PC711 HFS512GDE9X073N 512GB                  | 3         | 0.41%   |
| Seagate ST2000LM003 HN-M201RAD 2TB                    | 3         | 0.41%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB     | 3         | 0.41%   |
| SanDisk NVMe SSD Drive 500GB                          | 3         | 0.41%   |
| Samsung SSD 990 PRO 2TB                               | 3         | 0.41%   |
| Samsung SSD 980 PRO 1TB                               | 3         | 0.41%   |
| Samsung SSD 970 EVO Plus 1TB                          | 3         | 0.41%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1024GB  | 3         | 0.41%   |
| Micron 2400_MTFDKBA512QFM 512GB                       | 3         | 0.41%   |
| KIOXIA KBG50ZNS256G NVMe 256GB                        | 3         | 0.41%   |
| Kingston Company OM3PDP3 NVMe SSD 256GB               | 3         | 0.41%   |
| Kingston SNVS2000G 2TB                                | 3         | 0.41%   |
| Hitachi HTS545032B9A300 320GB                         | 3         | 0.41%   |
| HGST HTS721010A9E630 1TB                              | 3         | 0.41%   |
| Fujitsu MHZ2160BH FFS G1 160GB                        | 3         | 0.41%   |
| China SSD 256GB                                       | 3         | 0.41%   |
| A-DATA IM2P33F3A NVMe 256GB                           | 3         | 0.41%   |
| Wibtek W800S 512GB SSD                                | 2         | 0.27%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                      | 2         | 0.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 35        | 36     | 32.11%  |
| WDC                 | 29        | 30     | 26.61%  |
| Toshiba             | 13        | 15     | 11.93%  |
| Hitachi             | 11        | 11     | 10.09%  |
| HGST                | 10        | 10     | 9.17%   |
| Fujitsu             | 5         | 5      | 4.59%   |
| WALRAM              | 1         | 1      | 0.92%   |
| Unknown             | 1         | 1      | 0.92%   |
| SYMTEC              | 1         | 1      | 0.92%   |
| Samsung Electronics | 1         | 1      | 0.92%   |
| SABRENT             | 1         | 1      | 0.92%   |
| Apple               | 1         | 1      | 0.92%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 34        | 38     | 14.11%  |
| A-DATA Technology   | 34        | 46     | 14.11%  |
| SanDisk             | 23        | 29     | 9.54%   |
| Kingston            | 20        | 22     | 8.3%    |
| Crucial             | 18        | 20     | 7.47%   |
| WDC                 | 14        | 15     | 5.81%   |
| SK hynix            | 8         | 8      | 3.32%   |
| Apple               | 8         | 8      | 3.32%   |
| Intenso             | 7         | 7      | 2.9%    |
| China               | 7         | 9      | 2.9%    |
| Toshiba             | 6         | 7      | 2.49%   |
| Micron Technology   | 6         | 7      | 2.49%   |
| SPCC                | 5         | 6      | 2.07%   |
| Intel               | 5         | 5      | 2.07%   |
| Netac               | 3         | 3      | 1.24%   |
| LITEON              | 3         | 3      | 1.24%   |
| Wibtek              | 2         | 2      | 0.83%   |
| TO Exter            | 2         | 3      | 0.83%   |
| Patriot             | 2         | 2      | 0.83%   |
| OCZ                 | 2         | 2      | 0.83%   |
| LITEONIT            | 2         | 2      | 0.83%   |
| Lexar               | 2         | 2      | 0.83%   |
| JMicron Technology  | 2         | 2      | 0.83%   |
| Wellcomm            | 1         | 1      | 0.41%   |
| V-GeN               | 1         | 1      | 0.41%   |
| Team                | 1         | 1      | 0.41%   |
| S3+                 | 1         | 1      | 0.41%   |
| Plextor             | 1         | 1      | 0.41%   |
| Pioneer             | 1         | 1      | 0.41%   |
| Origin              | 1         | 1      | 0.41%   |
| Neo                 | 1         | 1      | 0.41%   |
| Mushkin             | 1         | 1      | 0.41%   |
| MicroFrom           | 1         | 1      | 0.41%   |
| Maxtor              | 1         | 1      | 0.41%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.41%   |
| KingFast            | 1         | 1      | 0.41%   |
| Kingchuxing         | 1         | 1      | 0.41%   |
| INNOVATION IT       | 1         | 2      | 0.41%   |
| Hikvision           | 1         | 1      | 0.41%   |
| Hewlett-Packard     | 1         | 1      | 0.41%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 306       | 376    | 44.8%   |
| SSD     | 224       | 275    | 32.8%   |
| HDD     | 109       | 113    | 15.96%  |
| MMC     | 34        | 41     | 4.98%   |
| Unknown | 10        | 10     | 1.46%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 306       | 372    | 46.02%  |
| SATA | 303       | 378    | 45.56%  |
| MMC  | 34        | 41     | 5.11%   |
| SAS  | 22        | 24     | 3.31%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 213       | 251    | 65.34%  |
| 0.51-1.0   | 100       | 123    | 30.67%  |
| 1.01-2.0   | 11        | 12     | 3.37%   |
| 3.01-4.0   | 2         | 2      | 0.61%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 167       | 27.97%  |
| 101-250        | 146       | 24.46%  |
| 501-1000       | 87        | 14.57%  |
| Unknown        | 60        | 10.05%  |
| 1001-2000      | 51        | 8.54%   |
| 51-100         | 36        | 6.03%   |
| 1-20           | 26        | 4.36%   |
| 21-50          | 16        | 2.68%   |
| 2001-3000      | 5         | 0.84%   |
| More than 3000 | 3         | 0.5%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 214       | 35.49%  |
| 21-50     | 97        | 16.09%  |
| 101-250   | 88        | 14.59%  |
| 51-100    | 67        | 11.11%  |
| Unknown   | 60        | 9.95%   |
| 251-500   | 42        | 6.97%   |
| 501-1000  | 23        | 3.81%   |
| 1001-2000 | 11        | 1.82%   |
| 2001-3000 | 1         | 0.17%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                       | Notebooks | Drives | Percent |
|---------------------------------------------|-----------|--------|---------|
| SK hynix PC711 HFS512GDE9X073N 512GB        | 3         | 3      | 6.38%   |
| SK hynix HFS128G39TND-N210A 128GB SSD       | 2         | 2      | 4.26%   |
| SK hynix BC711 HFM512GD3JX013N 512GB        | 2         | 2      | 4.26%   |
| Seagate ST9500325AS 500GB                   | 2         | 2      | 4.26%   |
| WDC WD5000LPVT-08G33T1 500GB                | 1         | 1      | 2.13%   |
| WDC WD400UE-22HCT0 40GB                     | 1         | 1      | 2.13%   |
| WDC WD3200BPVT-80ZEST0 320GB                | 1         | 1      | 2.13%   |
| WDC WD3200BEVT-80A0RT0 320GB                | 1         | 1      | 2.13%   |
| WDC WD3200BEVT-00A0RT0 320GB                | 1         | 1      | 2.13%   |
| WDC WD2500BEVT-22A23T0 208GB                | 1         | 1      | 2.13%   |
| Toshiba MQ01ACF032 320GB                    | 1         | 1      | 2.13%   |
| Toshiba MQ01ABF050 500GB                    | 1         | 1      | 2.13%   |
| Toshiba MQ01ABD100 1TB                      | 1         | 1      | 2.13%   |
| Toshiba MK3259GSXP 320GB                    | 1         | 1      | 2.13%   |
| SK hynix HFS128G3BTND-N210A 128GB SSD       | 1         | 1      | 2.13%   |
| ShiJi 1TB                                   | 1         | 3      | 2.13%   |
| Seagate ST9250414ASG 250GB                  | 1         | 1      | 2.13%   |
| Seagate ST500LM021-1KJ152 500GB             | 1         | 1      | 2.13%   |
| Seagate ST320LM001 HN-M320MBB 320GB         | 1         | 1      | 2.13%   |
| SanDisk SDSSDXPS960G 960GB                  | 1         | 1      | 2.13%   |
| SanDisk SD7SB2Q512G1001 512GB SSD           | 1         | 1      | 2.13%   |
| Samsung Electronics SSD 870 EVO 500GB       | 1         | 1      | 2.13%   |
| Micron Technology 2300 NVMe 512GB           | 1         | 1      | 2.13%   |
| Micron Technology 2200V_MTFDHBA512TCK 512GB | 1         | 1      | 2.13%   |
| Kingston SV300S37A120G 120GB SSD            | 1         | 1      | 2.13%   |
| Kingston SA400S37480G 480GB SSD             | 1         | 1      | 2.13%   |
| Kingston SA400S37240G 240GB SSD             | 1         | 1      | 2.13%   |
| JMicron Technology Generic 1TB              | 1         | 1      | 2.13%   |
| Intel SSDSC2BW120A4 120GB                   | 1         | 1      | 2.13%   |
| Intel SSDSC2BF240A4L 240GB                  | 1         | 1      | 2.13%   |
| Intel SSDPEKKW128G7 BTPY63260JJU128A 128GB  | 1         | 1      | 2.13%   |
| Hitachi HTS545050B9SA02 500GB               | 1         | 1      | 2.13%   |
| Hitachi HTS545050B9A300 500GB               | 1         | 1      | 2.13%   |
| Hitachi HTS545050A7E380 500GB               | 1         | 1      | 2.13%   |
| Hitachi HTS541616J9SA00 160GB               | 1         | 1      | 2.13%   |
| HGST HTS725032A7E630 320GB                  | 1         | 1      | 2.13%   |
| HGST HTS545050A7E680 500GB                  | 1         | 1      | 2.13%   |
| HGST HTS541075A9E680 752GB                  | 1         | 1      | 2.13%   |
| HGST HTS541010B7E610 1TB                    | 1         | 1      | 2.13%   |
| HGST HTS541010A7E630 1TB                    | 1         | 1      | 2.13%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SK hynix            | 8         | 8      | 17.02%  |
| WDC                 | 6         | 6      | 12.77%  |
| Seagate             | 5         | 5      | 10.64%  |
| HGST                | 5         | 5      | 10.64%  |
| Toshiba             | 4         | 4      | 8.51%   |
| Hitachi             | 4         | 4      | 8.51%   |
| Kingston            | 3         | 3      | 6.38%   |
| Intel               | 3         | 3      | 6.38%   |
| SanDisk             | 2         | 2      | 4.26%   |
| Micron Technology   | 2         | 2      | 4.26%   |
| Crucial             | 2         | 2      | 4.26%   |
| ShiJi               | 1         | 3      | 2.13%   |
| Samsung Electronics | 1         | 1      | 2.13%   |
| JMicron Technology  | 1         | 1      | 2.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 6         | 6      | 25%     |
| Seagate | 5         | 5      | 20.83%  |
| HGST    | 5         | 5      | 20.83%  |
| Toshiba | 4         | 4      | 16.67%  |
| Hitachi | 4         | 4      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 24        | 24     | 51.06%  |
| SSD  | 14        | 14     | 29.79%  |
| NVMe | 9         | 11     | 19.15%  |

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

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 392       | 499    | 62.62%  |
| Detected | 187       | 267    | 29.87%  |
| Malfunc  | 47        | 49     | 7.51%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 329       | 46.01%  |
| Samsung Electronics            | 92        | 12.87%  |
| AMD                            | 70        | 9.79%   |
| SanDisk                        | 56        | 7.83%   |
| SK hynix                       | 38        | 5.31%   |
| Micron Technology              | 28        | 3.92%   |
| Kingston Technology Company    | 21        | 2.94%   |
| Toshiba America Info Systems   | 13        | 1.82%   |
| ADATA Technology               | 11        | 1.54%   |
| Phison Electronics             | 10        | 1.4%    |
| KIOXIA                         | 10        | 1.4%    |
| Solid State Storage Technology | 6         | 0.84%   |
| Nvidia                         | 6         | 0.84%   |
| Micron/Crucial Technology      | 6         | 0.84%   |
| Silicon Motion                 | 4         | 0.56%   |
| Yangtze Memory Technologies    | 3         | 0.42%   |
| Union Memory (Shenzhen)        | 2         | 0.28%   |
| MAXIO Technology (Hangzhou)    | 2         | 0.28%   |
| Apple                          | 2         | 0.28%   |
| Seagate Technology             | 1         | 0.14%   |
| Realtek Semiconductor          | 1         | 0.14%   |
| Lite-On Technology             | 1         | 0.14%   |
| Jiangsu Huacun Elec.           | 1         | 0.14%   |
| INNOGRIT                       | 1         | 0.14%   |
| Biwin Storage Technology       | 1         | 0.14%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 60        | 7.96%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 43        | 5.7%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 31        | 4.11%   |
| Intel Volume Management Device NVMe RAID Controller                            | 31        | 4.11%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 29        | 3.85%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 29        | 3.85%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 24        | 3.18%   |
| Samsung NVMe SSD Controller 980                                                | 23        | 3.05%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 21        | 2.79%   |
| Intel Tiger Lake-LP SATA Controller                                            | 17        | 2.25%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 17        | 2.25%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 16        | 2.12%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 15        | 1.99%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 14        | 1.86%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 14        | 1.86%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 13        | 1.72%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 13        | 1.72%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 12        | 1.59%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 12        | 1.59%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 11        | 1.46%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 11        | 1.46%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 10        | 1.33%   |
| Intel Comet Lake SATA AHCI Controller                                          | 9         | 1.19%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 8         | 1.06%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 8         | 1.06%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 8         | 1.06%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 7         | 0.93%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 7         | 0.93%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 6         | 0.8%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 6         | 0.8%    |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                     | 6         | 0.8%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 6         | 0.8%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 6         | 0.8%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 6         | 0.8%    |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 5         | 0.66%   |
| Phison PS5013 E13 NVMe Controller                                              | 5         | 0.66%   |
| Kingston Company Company Non-Volatile memory controller                        | 5         | 0.66%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 4         | 0.53%   |
| Solid State Storage Non-Volatile memory controller                             | 4         | 0.53%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 4         | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 357       | 49.17%  |
| NVMe | 304       | 41.87%  |
| RAID | 49        | 6.75%   |
| IDE  | 16        | 2.2%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 449       | 76.49%  |
| AMD          | 135       | 23%     |
| CentaurHauls | 1         | 0.17%   |
| ARM          | 1         | 0.17%   |
| Unknown      | 1         | 0.17%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i3-9100 CPU @ 3.60GHz              | 29        | 4.93%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 25        | 4.25%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 13        | 2.21%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 9         | 1.53%   |
| Intel 12th Gen Core i5-1235U                  | 9         | 1.53%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 9         | 1.53%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 9         | 1.53%   |
| Intel 12th Gen Core i7-12700H                 | 8         | 1.36%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 8         | 1.36%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 7         | 1.19%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 7         | 1.19%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 7         | 1.19%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 7         | 1.19%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 7         | 1.19%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 7         | 1.19%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 6         | 1.02%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 6         | 1.02%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 6         | 1.02%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 6         | 1.02%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 6         | 1.02%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 6         | 1.02%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 5         | 0.85%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 5         | 0.85%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 5         | 0.85%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 5         | 0.85%   |
| Intel 13th Gen Core i7-1360P                  | 5         | 0.85%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 5         | 0.85%   |
| AMD Ryzen 7 5825U with Radeon Graphics        | 5         | 0.85%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 4         | 0.68%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 4         | 0.68%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 0.68%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 4         | 0.68%   |
| Intel Celeron CPU 3865U @ 1.80GHz             | 4         | 0.68%   |
| Intel 12th Gen Core i7-1260P                  | 4         | 0.68%   |
| Intel 12th Gen Core i7-1255U                  | 4         | 0.68%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 4         | 0.68%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 4         | 0.68%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 3         | 0.51%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 0.51%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Other                   | 120       | 20.41%  |
| Intel Core i5           | 108       | 18.37%  |
| Intel Core i7           | 88        | 14.97%  |
| Intel Core i3           | 54        | 9.18%   |
| AMD Ryzen 5             | 47        | 7.99%   |
| AMD Ryzen 7             | 33        | 5.61%   |
| Intel Celeron           | 27        | 4.59%   |
| Intel Core 2 Duo        | 24        | 4.08%   |
| Intel Pentium           | 14        | 2.38%   |
| AMD Ryzen 7 PRO         | 10        | 1.7%    |
| AMD Ryzen 9             | 7         | 1.19%   |
| AMD Ryzen 5 PRO         | 7         | 1.19%   |
| AMD E                   | 7         | 1.19%   |
| Intel Atom              | 5         | 0.85%   |
| Intel Pentium Dual-Core | 4         | 0.68%   |
| Intel Pentium Silver    | 3         | 0.51%   |
| Intel Pentium M         | 3         | 0.51%   |
| AMD Ryzen 3             | 3         | 0.51%   |
| Intel Genuine           | 2         | 0.34%   |
| Intel Core i9           | 2         | 0.34%   |
| AMD E2                  | 2         | 0.34%   |
| AMD E1                  | 2         | 0.34%   |
| AMD Athlon II           | 2         | 0.34%   |
| AMD A6                  | 2         | 0.34%   |
| AMD A4                  | 2         | 0.34%   |
| Intel Xeon              | 1         | 0.17%   |
| Intel Core m5           | 1         | 0.17%   |
| Intel Core 2            | 1         | 0.17%   |
| Intel Celeron M         | 1         | 0.17%   |
| AMD Quad-Core           | 1         | 0.17%   |
| AMD C-70                | 1         | 0.17%   |
| AMD C-60                | 1         | 0.17%   |
| AMD C-50                | 1         | 0.17%   |
| AMD Athlon              | 1         | 0.17%   |
| AMD A8                  | 1         | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 222       | 37.82%  |
| 4      | 194       | 33.05%  |
| 6      | 60        | 10.22%  |
| 8      | 51        | 8.69%   |
| 10     | 19        | 3.24%   |
| 14     | 15        | 2.56%   |
| 12     | 15        | 2.56%   |
| 1      | 8         | 1.36%   |
| 16     | 3         | 0.51%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 587       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 441       | 74.87%  |
| 1      | 148       | 25.13%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 580       | 98.81%  |
| 32-bit         | 5         | 0.85%   |
| 64-bit         | 1         | 0.17%   |
| Unknown        | 1         | 0.17%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 176       | 29.73%  |
| 0x806c1    | 38        | 6.42%   |
| 0x906eb    | 29        | 4.9%    |
| 0x906a4    | 19        | 3.21%   |
| 0x906a3    | 19        | 3.21%   |
| 0x1067a    | 15        | 2.53%   |
| 0x0a50000c | 15        | 2.53%   |
| 0x08108109 | 15        | 2.53%   |
| 0x806ec    | 14        | 2.36%   |
| 0x806ea    | 14        | 2.36%   |
| 0x806e9    | 14        | 2.36%   |
| 0x206a7    | 14        | 2.36%   |
| 0x306a9    | 13        | 2.2%    |
| 0x706a8    | 11        | 1.86%   |
| 0x406e3    | 11        | 1.86%   |
| 0x306d4    | 11        | 1.86%   |
| 0x306c3    | 11        | 1.86%   |
| 0x0a50000d | 11        | 1.86%   |
| 0x08608103 | 11        | 1.86%   |
| 0x40651    | 10        | 1.69%   |
| 0x20655    | 10        | 1.69%   |
| 0x906ea    | 9         | 1.52%   |
| 0xb06a2    | 7         | 1.18%   |
| 0x30678    | 7         | 1.18%   |
| 0x08600106 | 5         | 0.84%   |
| 0x806d1    | 4         | 0.68%   |
| 0x10676    | 4         | 0.68%   |
| 0x0a404102 | 4         | 0.68%   |
| 0x06006705 | 4         | 0.68%   |
| 0x05000119 | 4         | 0.68%   |
| 0x806eb    | 3         | 0.51%   |
| 0x806c2    | 3         | 0.51%   |
| 0x6fd      | 3         | 0.51%   |
| 0x506e3    | 3         | 0.51%   |
| 0x08600103 | 3         | 0.51%   |
| 0x05000029 | 3         | 0.51%   |
| 0xa0652    | 2         | 0.34%   |
| 0x906e9    | 2         | 0.34%   |
| 0x6d8      | 2         | 0.34%   |
| 0x08701013 | 2         | 0.34%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 122       | 20.75%  |
| TigerLake        | 51        | 8.67%   |
| Unknown          | 47        | 7.99%   |
| Alderlake Hybrid | 46        | 7.82%   |
| Zen 3            | 38        | 6.46%   |
| Haswell          | 29        | 4.93%   |
| Skylake          | 28        | 4.76%   |
| IvyBridge        | 27        | 4.59%   |
| Penryn           | 25        | 4.25%   |
| Zen+             | 22        | 3.74%   |
| SandyBridge      | 20        | 3.4%    |
| Zen 2            | 17        | 2.89%   |
| Westmere         | 17        | 2.89%   |
| Broadwell        | 15        | 2.55%   |
| Goldmont plus    | 14        | 2.38%   |
| Silvermont       | 12        | 2.04%   |
| Bobcat           | 11        | 1.87%   |
| Icelake          | 8         | 1.36%   |
| Core             | 7         | 1.19%   |
| Excavator        | 6         | 1.02%   |
| CometLake        | 6         | 1.02%   |
| P6               | 4         | 0.68%   |
| Jaguar           | 3         | 0.51%   |
| Goldmont         | 3         | 0.51%   |
| K10              | 2         | 0.34%   |
| Bonnell          | 2         | 0.34%   |
| Zen              | 1         | 0.17%   |
| Tremont          | 1         | 0.17%   |
| Puma             | 1         | 0.17%   |
| Piledriver       | 1         | 0.17%   |
| Nehalem          | 1         | 0.17%   |
| K10 Llano        | 1         | 0.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 413       | 57.68%  |
| AMD     | 159       | 22.21%  |
| Nvidia  | 143       | 19.97%  |
| Zhaoxin | 1         | 0.14%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 45        | 6.13%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                 | 29        | 3.95%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 27        | 3.68%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 27        | 3.68%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 24        | 3.27%   |
| AMD Lucienne                                                              | 22        | 3%      |
| Intel UHD Graphics 620                                                    | 21        | 2.86%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 19        | 2.59%   |
| Intel HD Graphics 620                                                     | 19        | 2.59%   |
| Intel Alder Lake-P Integrated Graphics Controller                         | 19        | 2.59%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 16        | 2.18%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                               | 16        | 2.18%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 16        | 2.18%   |
| AMD Renoir                                                                | 15        | 2.04%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 14        | 1.91%   |
| Intel Core Processor Integrated Graphics Controller                       | 14        | 1.91%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 12        | 1.63%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 12        | 1.63%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 11        | 1.5%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 11        | 1.5%    |
| AMD Barcelo                                                               | 11        | 1.5%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 10        | 1.36%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                    | 9         | 1.23%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 9         | 1.23%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 8         | 1.09%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 8         | 1.09%   |
| AMD Rembrandt [Radeon 680M]                                               | 8         | 1.09%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                | 7         | 0.95%   |
| Intel HD Graphics 6000                                                    | 7         | 0.95%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 6         | 0.82%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                 | 6         | 0.82%   |
| Intel HD Graphics 5500                                                    | 6         | 0.82%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 5         | 0.68%   |
| Intel HD Graphics 630                                                     | 5         | 0.68%   |
| Intel HD Graphics 610                                                     | 5         | 0.68%   |
| Intel HD Graphics 530                                                     | 5         | 0.68%   |
| AMD Wrestler [Radeon HD 6310]                                             | 5         | 0.68%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 5         | 0.68%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                | 5         | 0.68%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 4         | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 289       | 49.15%  |
| 1 x AMD        | 116       | 19.73%  |
| Intel + Nvidia | 97        | 16.5%   |
| 1 x Nvidia     | 27        | 4.59%   |
| AMD + Nvidia   | 18        | 3.06%   |
| Intel + AMD    | 14        | 2.38%   |
| 2 x Intel      | 11        | 1.87%   |
| 2 x AMD        | 11        | 1.87%   |
| Other          | 3         | 0.51%   |
| 2 x Nvidia     | 1         | 0.17%   |
| 1 x Zhaoxin    | 1         | 0.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 489       | 82.88%  |
| Proprietary | 53        | 8.98%   |
| Unknown     | 48        | 8.14%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 428       | 72.42%  |
| 0.01-0.5   | 65        | 11%     |
| 1.01-2.0   | 32        | 5.41%   |
| 0.51-1.0   | 25        | 4.23%   |
| 3.01-4.0   | 23        | 3.89%   |
| 7.01-8.0   | 8         | 1.35%   |
| 5.01-6.0   | 6         | 1.02%   |
| 2.01-3.0   | 2         | 0.34%   |
| 16.01-24.0 | 1         | 0.17%   |
| 0          | 1         | 0.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 124       | 19.97%  |
| BOE                     | 95        | 15.3%   |
| Chimei Innolux          | 85        | 13.69%  |
| LG Display              | 62        | 9.98%   |
| Samsung Electronics     | 50        | 8.05%   |
| Apple                   | 21        | 3.38%   |
| Sharp                   | 20        | 3.22%   |
| PANDA                   | 20        | 3.22%   |
| Dell                    | 19        | 3.06%   |
| Lenovo                  | 15        | 2.42%   |
| InfoVision              | 14        | 2.25%   |
| Hewlett-Packard         | 9         | 1.45%   |
| BenQ                    | 9         | 1.45%   |
| Philips                 | 8         | 1.29%   |
| Goldstar                | 8         | 1.29%   |
| CSO                     | 7         | 1.13%   |
| Chi Mei Optoelectronics | 6         | 0.97%   |
| ASUSTek Computer        | 6         | 0.97%   |
| LG Philips              | 4         | 0.64%   |
| AOC                     | 4         | 0.64%   |
| Acer                    | 4         | 0.64%   |
| Iiyama                  | 3         | 0.48%   |
| Ancor Communications    | 3         | 0.48%   |
| ViewSonic               | 2         | 0.32%   |
| Toshiba                 | 2         | 0.32%   |
| Sony                    | 2         | 0.32%   |
| InnoLux Display         | 2         | 0.32%   |
| Vizio                   | 1         | 0.16%   |
| Valve                   | 1         | 0.16%   |
| Tianma XM               | 1         | 0.16%   |
| STD                     | 1         | 0.16%   |
| SANYO                   | 1         | 0.16%   |
| SAC                     | 1         | 0.16%   |
| MSF                     | 1         | 0.16%   |
| Mi                      | 1         | 0.16%   |
| JDI                     | 1         | 0.16%   |
| IBM                     | 1         | 0.16%   |
| HKC                     | 1         | 0.16%   |
| H-Buster                | 1         | 0.16%   |
| Denver                  | 1         | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 11        | 1.76%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 6         | 0.96%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 5         | 0.8%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 4         | 0.64%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 4         | 0.64%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch        | 4         | 0.64%   |
| AU Optronics LCD Monitor AUO80ED 1920x1080 344x193mm 15.5-inch        | 4         | 0.64%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 4         | 0.64%   |
| Sharp LCD Monitor SHP1516 3840x2400 336x210mm 15.6-inch               | 3         | 0.48%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch               | 3         | 0.48%   |
| PANDA LCD Monitor NCP0035 1920x1080 344x194mm 15.5-inch               | 3         | 0.48%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch          | 3         | 0.48%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 3         | 0.48%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 0.48%   |
| Chimei Innolux LCD Monitor CMN153B 1920x1080 344x193mm 15.5-inch      | 3         | 0.48%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 3         | 0.48%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 3         | 0.48%   |
| BOE LCD Monitor BOE0BCA 2256x1504 285x190mm 13.5-inch                 | 3         | 0.48%   |
| BOE LCD Monitor BOE0A81 1920x1080 344x194mm 15.5-inch                 | 3         | 0.48%   |
| BOE LCD Monitor BOE091D 1920x1080 309x174mm 14.0-inch                 | 3         | 0.48%   |
| BOE LCD Monitor BOE0818 1920x1080 344x194mm 15.5-inch                 | 3         | 0.48%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 3         | 0.48%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch        | 3         | 0.48%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 3         | 0.48%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 3         | 0.48%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 3         | 0.48%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                | 3         | 0.48%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                  | 3         | 0.48%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 2         | 0.32%   |
| Sharp LCD Monitor SHP1515 1920x1200 336x210mm 15.6-inch               | 2         | 0.32%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch               | 2         | 0.32%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 2         | 0.32%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 2         | 0.32%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 277x156mm 12.5-inch  | 2         | 0.32%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 2         | 0.32%   |
| Philips PHL 272V8 PHLC21A 1920x1080 598x336mm 27.0-inch               | 2         | 0.32%   |
| PANDA LCD Monitor NCP005F 1920x1080 344x194mm 15.5-inch               | 2         | 0.32%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 2         | 0.32%   |
| LG Display LCD Monitor LGD06EA 2560x1600 366x229mm 17.0-inch          | 2         | 0.32%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch          | 2         | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 305       | 51.87%  |
| 1366x768 (WXGA)    | 116       | 19.73%  |
| 2560x1440 (QHD)    | 24        | 4.08%   |
| 1920x1200 (WUXGA)  | 24        | 4.08%   |
| 1600x900 (HD+)     | 21        | 3.57%   |
| 1280x800 (WXGA)    | 13        | 2.21%   |
| 3840x2160 (4K)     | 12        | 2.04%   |
| 1440x900 (WXGA+)   | 12        | 2.04%   |
| 2560x1600          | 9         | 1.53%   |
| 3840x2400          | 8         | 1.36%   |
| 2880x1800          | 7         | 1.19%   |
| 2256x1504          | 4         | 0.68%   |
| 1680x1050 (WSXGA+) | 4         | 0.68%   |
| 3440x1440          | 3         | 0.51%   |
| 2560x1080          | 3         | 0.51%   |
| 3456x2160          | 2         | 0.34%   |
| 3072x1920          | 2         | 0.34%   |
| 3000x2000          | 2         | 0.34%   |
| 1920x540           | 2         | 0.34%   |
| 1280x1024 (SXGA)   | 2         | 0.34%   |
| 800x1280           | 1         | 0.17%   |
| 3840x1100          | 1         | 0.17%   |
| 3200x2000          | 1         | 0.17%   |
| 3200x1800 (QHD+)   | 1         | 0.17%   |
| 2966x900           | 1         | 0.17%   |
| 2880x1620          | 1         | 0.17%   |
| 2160x1440          | 1         | 0.17%   |
| 1600x2560          | 1         | 0.17%   |
| 1400x1050          | 1         | 0.17%   |
| 1360x768           | 1         | 0.17%   |
| 1024x768 (XGA)     | 1         | 0.17%   |
| 1024x600           | 1         | 0.17%   |
| Unknown            | 1         | 0.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 225       | 36.23%  |
| 13      | 115       | 18.52%  |
| 14      | 94        | 15.14%  |
| 17      | 31        | 4.99%   |
| 24      | 29        | 4.67%   |
| 27      | 21        | 3.38%   |
| 12      | 17        | 2.74%   |
| 11      | 17        | 2.74%   |
| 16      | 16        | 2.58%   |
| 23      | 13        | 2.09%   |
| 21      | 8         | 1.29%   |
| 34      | 6         | 0.97%   |
| Unknown | 5         | 0.81%   |
| 31      | 4         | 0.64%   |
| 22      | 3         | 0.48%   |
| 18      | 3         | 0.48%   |
| 72      | 2         | 0.32%   |
| 19      | 2         | 0.32%   |
| 48      | 1         | 0.16%   |
| 33      | 1         | 0.16%   |
| 32      | 1         | 0.16%   |
| 28      | 1         | 0.16%   |
| 26      | 1         | 0.16%   |
| 25      | 1         | 0.16%   |
| 20      | 1         | 0.16%   |
| 10      | 1         | 0.16%   |
| 8       | 1         | 0.16%   |
| 7       | 1         | 0.16%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 384       | 62.24%  |
| 201-300     | 92        | 14.91%  |
| 501-600     | 62        | 10.05%  |
| 351-400     | 40        | 6.48%   |
| 401-500     | 15        | 2.43%   |
| 701-800     | 8         | 1.3%    |
| 601-700     | 6         | 0.97%   |
| Unknown     | 5         | 0.81%   |
| 1501-2000   | 2         | 0.32%   |
| 101-200     | 1         | 0.16%   |
| 1001-1500   | 1         | 0.16%   |
| 1-100       | 1         | 0.16%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 447       | 80.83%  |
| 16/10   | 79        | 14.29%  |
| 3/2     | 8         | 1.45%   |
| 21/9    | 6         | 1.08%   |
| 4/3     | 4         | 0.72%   |
| Unknown | 4         | 0.72%   |
| 5/4     | 2         | 0.36%   |
| 3.40    | 1         | 0.18%   |
| 0.67    | 1         | 0.18%   |
| 0.58    | 1         | 0.18%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 223       | 35.97%  |
| 81-90          | 167       | 26.94%  |
| 201-250        | 42        | 6.77%   |
| 71-80          | 39        | 6.29%   |
| 121-130        | 28        | 4.52%   |
| 301-350        | 22        | 3.55%   |
| 51-60          | 18        | 2.9%    |
| 111-120        | 18        | 2.9%    |
| 61-70          | 17        | 2.74%   |
| 351-500        | 13        | 2.1%    |
| 251-300        | 8         | 1.29%   |
| 151-200        | 6         | 0.97%   |
| Unknown        | 5         | 0.81%   |
| More than 1000 | 3         | 0.48%   |
| 141-150        | 3         | 0.48%   |
| 131-140        | 3         | 0.48%   |
| 1-40           | 2         | 0.32%   |
| 91-100         | 2         | 0.32%   |
| 41-50          | 1         | 0.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 316       | 51.55%  |
| 101-120       | 123       | 20.07%  |
| 51-100        | 76        | 12.4%   |
| 161-240       | 66        | 10.77%  |
| More than 240 | 22        | 3.59%   |
| 1-50          | 5         | 0.82%   |
| Unknown       | 5         | 0.82%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 448       | 75.55%  |
| 2     | 90        | 15.18%  |
| 0     | 48        | 8.09%   |
| 3     | 7         | 1.18%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 346       | 37.73%  |
| Realtek Semiconductor             | 296       | 32.28%  |
| Qualcomm Atheros                  | 84        | 9.16%   |
| Broadcom                          | 46        | 5.02%   |
| MediaTek                          | 27        | 2.94%   |
| ASIX Electronics                  | 16        | 1.74%   |
| Qualcomm                          | 15        | 1.64%   |
| Broadcom Limited                  | 15        | 1.64%   |
| Sierra Wireless                   | 8         | 0.87%   |
| Ralink Technology                 | 6         | 0.65%   |
| Marvell Technology Group          | 6         | 0.65%   |
| TP-Link                           | 5         | 0.55%   |
| Nvidia                            | 5         | 0.55%   |
| Xiaomi                            | 4         | 0.44%   |
| Lenovo                            | 4         | 0.44%   |
| Ralink                            | 3         | 0.33%   |
| Google                            | 3         | 0.33%   |
| Microsoft                         | 2         | 0.22%   |
| JMicron Technology                | 2         | 0.22%   |
| Ericsson Business Mobile Networks | 2         | 0.22%   |
| DisplayLink                       | 2         | 0.22%   |
| Dell                              | 2         | 0.22%   |
| D-Link                            | 2         | 0.22%   |
| ASUSTek Computer                  | 2         | 0.22%   |
| Wacom                             | 1         | 0.11%   |
| U-Blox                            | 1         | 0.11%   |
| Spreadtrum Communications         | 1         | 0.11%   |
| OPPO Electronics                  | 1         | 0.11%   |
| OpenMoko                          | 1         | 0.11%   |
| NetGear                           | 1         | 0.11%   |
| Microchip Technology              | 1         | 0.11%   |
| Huawei Technologies               | 1         | 0.11%   |
| Hewlett-Packard                   | 1         | 0.11%   |
| Fujitsu                           | 1         | 0.11%   |
| Fibocom                           | 1         | 0.11%   |
| Dresden Elektronik                | 1         | 0.11%   |
| Attansic Technology               | 1         | 0.11%   |
| Apple                             | 1         | 0.11%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 189       | 17.12%  |
| Intel Wireless 8265 / 8275                                        | 38        | 3.44%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 37        | 3.35%   |
| Intel Wi-Fi 6 AX201                                               | 36        | 3.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 34        | 3.08%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 34        | 3.08%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 28        | 2.54%   |
| Intel Wi-Fi 6 AX200                                               | 28        | 2.54%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 24        | 2.17%   |
| Intel Ethernet Connection (4) I219-LM                             | 20        | 1.81%   |
| Intel Wireless 7260                                               | 19        | 1.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 18        | 1.63%   |
| Intel Wireless 8260                                               | 18        | 1.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 17        | 1.54%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 17        | 1.54%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 16        | 1.45%   |
| ASIX AX88179 Gigabit Ethernet                                     | 15        | 1.36%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 14        | 1.27%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 12        | 1.09%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 11        | 1%      |
| Qualcomm QCNFA765 Wireless Network Adapter                        | 11        | 1%      |
| Intel Wireless 7265                                               | 11        | 1%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 11        | 1%      |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 10        | 0.91%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 10        | 0.91%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 9         | 0.82%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 9         | 0.82%   |
| Intel Ethernet Connection I219-LM                                 | 9         | 0.82%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 9         | 0.82%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 8         | 0.72%   |
| Intel Ethernet Connection (4) I219-V                              | 8         | 0.72%   |
| Intel Ethernet Connection (13) I219-V                             | 8         | 0.72%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 7         | 0.63%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 7         | 0.63%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 6         | 0.54%   |
| Intel Ethernet Connection I218-LM                                 | 6         | 0.54%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 0.54%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 6         | 0.54%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 6         | 0.54%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 5         | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 328       | 53.86%  |
| Realtek Semiconductor             | 88        | 14.45%  |
| Qualcomm Atheros                  | 73        | 11.99%  |
| Broadcom                          | 38        | 6.24%   |
| MediaTek                          | 26        | 4.27%   |
| Broadcom Limited                  | 13        | 2.13%   |
| Qualcomm                          | 12        | 1.97%   |
| Sierra Wireless                   | 8         | 1.31%   |
| Ralink Technology                 | 6         | 0.99%   |
| TP-Link                           | 4         | 0.66%   |
| Ralink                            | 3         | 0.49%   |
| Microsoft                         | 2         | 0.33%   |
| D-Link                            | 2         | 0.33%   |
| ASUSTek Computer                  | 2         | 0.33%   |
| Wacom                             | 1         | 0.16%   |
| NetGear                           | 1         | 0.16%   |
| Fibocom                           | 1         | 0.16%   |
| Ericsson Business Mobile Networks | 1         | 0.16%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 38        | 6.2%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 37        | 6.04%   |
| Intel Wi-Fi 6 AX201                                            | 36        | 5.87%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 34        | 5.55%   |
| Intel Wi-Fi 6 AX200                                            | 28        | 4.57%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 24        | 3.92%   |
| Intel Wireless 7260                                            | 19        | 3.1%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 18        | 2.94%   |
| Intel Wireless 8260                                            | 18        | 2.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 17        | 2.77%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 16        | 2.61%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 14        | 2.28%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 12        | 1.96%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 11        | 1.79%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 11        | 1.79%   |
| Intel Wireless 7265                                            | 11        | 1.79%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 11        | 1.79%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 10        | 1.63%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 10        | 1.63%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 9         | 1.47%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 9         | 1.47%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 9         | 1.47%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 8         | 1.31%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 7         | 1.14%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 7         | 1.14%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 6         | 0.98%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 6         | 0.98%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 6         | 0.98%   |
| Intel Wireless-AC 9260                                         | 5         | 0.82%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 5         | 0.82%   |
| Intel Raptor Lake PCH CNVi WiFi                                | 5         | 0.82%   |
| Sierra Wireless EM7455                                         | 4         | 0.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 0.65%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 4         | 0.65%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 4         | 0.65%   |
| Intel WiFi Link 5100                                           | 4         | 0.65%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 4         | 0.65%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 4         | 0.65%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 4         | 0.65%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 3         | 0.49%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Realtek Semiconductor     | 259       | 55.34%  |
| Intel                     | 121       | 25.85%  |
| Qualcomm Atheros          | 20        | 4.27%   |
| ASIX Electronics          | 16        | 3.42%   |
| Broadcom                  | 12        | 2.56%   |
| Marvell Technology Group  | 6         | 1.28%   |
| Nvidia                    | 5         | 1.07%   |
| Xiaomi                    | 4         | 0.85%   |
| Lenovo                    | 4         | 0.85%   |
| Qualcomm                  | 3         | 0.64%   |
| Google                    | 3         | 0.64%   |
| JMicron Technology        | 2         | 0.43%   |
| DisplayLink               | 2         | 0.43%   |
| Broadcom Limited          | 2         | 0.43%   |
| TP-Link                   | 1         | 0.21%   |
| Spreadtrum Communications | 1         | 0.21%   |
| OPPO Electronics          | 1         | 0.21%   |
| Microchip Technology      | 1         | 0.21%   |
| MediaTek                  | 1         | 0.21%   |
| Huawei Technologies       | 1         | 0.21%   |
| Hewlett-Packard           | 1         | 0.21%   |
| Attansic Technology       | 1         | 0.21%   |
| Apple                     | 1         | 0.21%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 189       | 39.46%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 34        | 7.1%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 28        | 5.85%   |
| Intel Ethernet Connection (4) I219-LM                             | 20        | 4.18%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 17        | 3.55%   |
| ASIX AX88179 Gigabit Ethernet                                     | 15        | 3.13%   |
| Intel Ethernet Connection I219-LM                                 | 9         | 1.88%   |
| Intel Ethernet Connection (4) I219-V                              | 8         | 1.67%   |
| Intel Ethernet Connection (13) I219-V                             | 8         | 1.67%   |
| Intel Ethernet Connection I218-LM                                 | 6         | 1.25%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 1.25%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 5         | 1.04%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 1.04%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 5         | 1.04%   |
| Intel Ethernet Connection (16) I219-V                             | 5         | 1.04%   |
| Nvidia MCP79 Ethernet                                             | 4         | 0.84%   |
| Intel Ethernet Connection I219-V                                  | 4         | 0.84%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 0.84%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.63%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 0.63%   |
| Intel Ethernet Connection I217-V                                  | 3         | 0.63%   |
| Intel Ethernet Connection (5) I219-LM                             | 3         | 0.63%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 0.63%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.63%   |
| Intel Ethernet Connection (16) I219-LM                            | 3         | 0.63%   |
| Intel Ethernet Connection (13) I219-LM                            | 3         | 0.63%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 0.63%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 0.42%   |
| Qualcomm Redmi Note 8                                             | 2         | 0.42%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.42%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.42%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.42%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.42%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.42%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 0.42%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 0.42%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 0.42%   |
| Intel Ethernet Connection I218-V                                  | 2         | 0.42%   |
| Google Nexus/Pixel Device (tether)                                | 2         | 0.42%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 577       | 55.97%  |
| Ethernet | 442       | 42.87%  |
| Modem    | 11        | 1.07%   |
| Unknown  | 1         | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 430       | 68.91%  |
| Ethernet | 194       | 31.09%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 386       | 65.76%  |
| 1     | 189       | 32.2%   |
| 0     | 7         | 1.19%   |
| 3     | 5         | 0.85%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 417       | 70.32%  |
| Yes  | 176       | 29.68%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 287       | 56.5%   |
| Realtek Semiconductor           | 59        | 11.61%  |
| Qualcomm Atheros Communications | 30        | 5.91%   |
| Foxconn / Hon Hai               | 23        | 4.53%   |
| IMC Networks                    | 21        | 4.13%   |
| Lite-On Technology              | 19        | 3.74%   |
| Apple                           | 18        | 3.54%   |
| Broadcom                        | 17        | 3.35%   |
| Realtek                         | 8         | 1.57%   |
| Dell                            | 5         | 0.98%   |
| Hewlett-Packard                 | 4         | 0.79%   |
| Toshiba                         | 3         | 0.59%   |
| USI                             | 2         | 0.39%   |
| Micro Star International        | 2         | 0.39%   |
| MediaTek                        | 2         | 0.39%   |
| Cambridge Silicon Radio         | 2         | 0.39%   |
| ASUSTek Computer                | 2         | 0.39%   |
| Ralink Technology               | 1         | 0.2%    |
| Fujitsu                         | 1         | 0.2%    |
| Foxconn International           | 1         | 0.2%    |
| Alps Electric                   | 1         | 0.2%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 90        | 17.72%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 66        | 12.99%  |
| Realtek Bluetooth Radio                             | 53        | 10.43%  |
| Intel AX201 Bluetooth                               | 50        | 9.84%   |
| Intel Bluetooth Device                              | 33        | 6.5%    |
| Intel AX200 Bluetooth                               | 28        | 5.51%   |
| Qualcomm Atheros  Bluetooth Device                  | 14        | 2.76%   |
| Foxconn / Hon Hai Bluetooth Device                  | 14        | 2.76%   |
| IMC Networks Wireless_Device                        | 10        | 1.97%   |
| Realtek 802.11ac WLAN Adapter                       | 8         | 1.57%   |
| Intel AX210 Bluetooth                               | 8         | 1.57%   |
| Apple Bluetooth USB Host Controller                 | 8         | 1.57%   |
| Lite-On Wireless_Device                             | 7         | 1.38%   |
| Apple Bluetooth Host Controller                     | 7         | 1.38%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 6         | 1.18%   |
| Lite-On Bluetooth Device                            | 6         | 1.18%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 6         | 1.18%   |
| IMC Networks Bluetooth Radio                        | 6         | 1.18%   |
| Foxconn / Hon Hai Wireless_Device                   | 6         | 1.18%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 5         | 0.98%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 0.98%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 0.79%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 4         | 0.79%   |
| Dell BCM20702A0 Bluetooth Module                    | 4         | 0.79%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 0.79%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 0.59%   |
| USI Bluetooth Device                                | 2         | 0.39%   |
| MediaTek Wireless_Device                            | 2         | 0.39%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 0.39%   |
| IMC Networks Bluetooth Device                       | 2         | 0.39%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 2         | 0.39%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 0.39%   |
| Broadcom HP Portable SoftSailing                    | 2         | 0.39%   |
| Broadcom HP Portable Bumble Bee                     | 2         | 0.39%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 0.39%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2         | 0.39%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.2%    |
| Toshiba Integrated Bluetooth HCI                    | 1         | 0.2%    |
| Toshiba Bluetooth Radio                             | 1         | 0.2%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.2%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 438       | 62.04%  |
| AMD                        | 146       | 20.68%  |
| Nvidia                     | 73        | 10.34%  |
| Lenovo                     | 7         | 0.99%   |
| C-Media Electronics        | 6         | 0.85%   |
| Logitech                   | 5         | 0.71%   |
| Realtek Semiconductor      | 4         | 0.57%   |
| Yamaha                     | 2         | 0.28%   |
| JMTek                      | 2         | 0.28%   |
| Hewlett-Packard            | 2         | 0.28%   |
| Creative Technology        | 2         | 0.28%   |
| CMX Systems                | 2         | 0.28%   |
| Zhaoxin                    | 1         | 0.14%   |
| SteelSeries ApS            | 1         | 0.14%   |
| Samson Technologies        | 1         | 0.14%   |
| Plantronics                | 1         | 0.14%   |
| Phoenix Audio Technologies | 1         | 0.14%   |
| Kingston Technology        | 1         | 0.14%   |
| GN Netcom                  | 1         | 0.14%   |
| Generalplus Technology     | 1         | 0.14%   |
| Fujitsu                    | 1         | 0.14%   |
| Focusrite-Novation         | 1         | 0.14%   |
| Cambridge Silicon Radio    | 1         | 0.14%   |
| Beyerdynamic               | 1         | 0.14%   |
| bestechnic                 | 1         | 0.14%   |
| Audient                    | 1         | 0.14%   |
| ASUSTek Computer           | 1         | 0.14%   |
| Apple                      | 1         | 0.14%   |
| AlfaPlus Semiconductor     | 1         | 0.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 105       | 11.99%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 69        | 7.88%   |
| Intel Sunrise Point-LP HD Audio                                            | 64        | 7.31%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 51        | 5.82%   |
| Intel Cannon Lake PCH cAVS                                                 | 46        | 5.25%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 40        | 4.57%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 33        | 3.77%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 23        | 2.63%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 19        | 2.17%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 17        | 1.94%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 15        | 1.71%   |
| Intel Haswell-ULT HD Audio Controller                                      | 15        | 1.71%   |
| Intel Comet Lake PCH-LP cAVS                                               | 15        | 1.71%   |
| Intel Broadwell-U Audio Controller                                         | 15        | 1.71%   |
| Intel 8 Series HD Audio Controller                                         | 15        | 1.71%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 14        | 1.6%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 14        | 1.6%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 14        | 1.6%    |
| Nvidia Audio device                                                        | 12        | 1.37%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 12        | 1.37%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 10        | 1.14%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 10        | 1.14%   |
| AMD Wrestler HDMI Audio                                                    | 9         | 1.03%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 9         | 1.03%   |
| AMD FCH Azalia Controller                                                  | 9         | 1.03%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 8         | 0.91%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 8         | 0.91%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 8         | 0.91%   |
| Intel CM238 HD Audio Controller                                            | 7         | 0.8%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 7         | 0.8%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 6         | 0.68%   |
| Nvidia TU106 High Definition Audio Controller                              | 6         | 0.68%   |
| Nvidia GF108 High Definition Audio Controller                              | 6         | 0.68%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 6         | 0.68%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 6         | 0.68%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5         | 0.57%   |
| Nvidia GA106 High Definition Audio Controller                              | 5         | 0.57%   |
| Nvidia GA104 High Definition Audio Controller                              | 5         | 0.57%   |
| AMD Kabini HDMI/DP Audio                                                   | 5         | 0.57%   |
| AMD High Definition Audio Controller                                       | 5         | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 145       | 26.65%  |
| SK hynix                                | 119       | 21.88%  |
| Micron Technology                       | 78        | 14.34%  |
| Crucial                                 | 52        | 9.56%   |
| Kingston                                | 32        | 5.88%   |
| Unknown                                 | 29        | 5.33%   |
| Elpida                                  | 14        | 2.57%   |
| A-DATA Technology                       | 12        | 2.21%   |
| Ramaxel Technology                      | 8         | 1.47%   |
| Corsair                                 | 8         | 1.47%   |
| Nanya Technology                        | 6         | 1.1%    |
| Unknown (ABCD)                          | 5         | 0.92%   |
| ff                                      | 5         | 0.92%   |
| 4ea5                                    | 5         | 0.92%   |
| Smart                                   | 4         | 0.74%   |
| G.Skill                                 | 4         | 0.74%   |
| ASint Technology                        | 3         | 0.55%   |
| Unknown                                 | 3         | 0.55%   |
| Unknown (06CE)                          | 1         | 0.18%   |
| Transcend                               | 1         | 0.18%   |
| Team                                    | 1         | 0.18%   |
| Silicon Power Computer & Communications | 1         | 0.18%   |
| PKI                                     | 1         | 0.18%   |
| Patriot                                 | 1         | 0.18%   |
| Neo Forza                               | 1         | 0.18%   |
| Asgard                                  | 1         | 0.18%   |
| ad8a                                    | 1         | 0.18%   |
| A Force                                 | 1         | 0.18%   |
| <Invalid>                               | 1         | 0.18%   |
| 2B0B00000000                            | 1         | 0.18%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Crucial RAM CT8G4SFRA266.C8FD1 8GB SODIMM DDR4 2667MT/s          | 29        | 5.02%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 13        | 2.25%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 9         | 1.56%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 9         | 1.56%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 8         | 1.38%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 7         | 1.21%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 1.04%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 1.04%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 5         | 0.87%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 5         | 0.87%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.87%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 5         | 0.87%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 5         | 0.87%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 4         | 0.69%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                    | 4         | 0.69%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.69%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 0.69%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 4         | 0.69%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 0.69%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.69%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 4         | 0.69%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 4         | 0.69%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 4         | 0.69%   |
| Unknown RAM Module 2GB SODIMM 800MT/s                            | 3         | 0.52%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 3         | 0.52%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 3         | 0.52%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 3         | 0.52%   |
| SK hynix RAM HMCG88MEBSA092N 32GB SODIMM DDR5 4800MT/s           | 3         | 0.52%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 3         | 0.52%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 3         | 0.52%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 3         | 0.52%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.52%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.52%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.52%   |
| Samsung RAM M471B5674QH0-YK0 2048MB SODIMM DDR3 1600MT/s         | 3         | 0.52%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.52%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 0.52%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 3         | 0.52%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 0.52%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.52%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 248       | 54.51%  |
| DDR3    | 108       | 23.74%  |
| LPDDR4  | 30        | 6.59%   |
| DDR5    | 18        | 3.96%   |
| LPDDR3  | 16        | 3.52%   |
| LPDDR5  | 12        | 2.64%   |
| DDR2    | 10        | 2.2%    |
| SDRAM   | 5         | 1.1%    |
| Unknown | 5         | 1.1%    |
| DDR     | 3         | 0.66%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 391       | 83.91%  |
| Row Of Chips | 60        | 12.88%  |
| Unknown      | 9         | 1.93%   |
| Chip         | 4         | 0.86%   |
| DIMM         | 2         | 0.43%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 220       | 43.91%  |
| 4096  | 127       | 25.35%  |
| 16384 | 69        | 13.77%  |
| 2048  | 46        | 9.18%   |
| 1024  | 21        | 4.19%   |
| 32768 | 17        | 3.39%   |
| 256   | 1         | 0.2%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 124       | 25.51%  |
| 2667    | 98        | 20.16%  |
| 1600    | 69        | 14.2%   |
| 2400    | 38        | 7.82%   |
| 2133    | 24        | 4.94%   |
| 1334    | 22        | 4.53%   |
| 4267    | 15        | 3.09%   |
| 4800    | 14        | 2.88%   |
| 6400    | 13        | 2.67%   |
| Unknown | 12        | 2.47%   |
| 1067    | 11        | 2.26%   |
| 1333    | 9         | 1.85%   |
| 800     | 8         | 1.65%   |
| 1867    | 5         | 1.03%   |
| 1066    | 4         | 0.82%   |
| 5600    | 3         | 0.62%   |
| 3266    | 3         | 0.62%   |
| 667     | 3         | 0.62%   |
| 8400    | 2         | 0.41%   |
| 4266    | 2         | 0.41%   |
| 4199    | 2         | 0.41%   |
| 2666    | 1         | 0.21%   |
| 2048    | 1         | 0.21%   |
| 975     | 1         | 0.21%   |
| 666     | 1         | 0.21%   |
| 533     | 1         | 0.21%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Brother Industries | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Brother DCP-7010 | 1         | 100%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 50%     |
| Canon       | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X800 [Perfection 4990 PHOTO] | 1         | 50%     |
| Canon CanoScan LiDE 110                     | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 130       | 24.53%  |
| IMC Networks                           | 65        | 12.26%  |
| Bison Electronics                      | 63        | 11.89%  |
| Microdia                               | 42        | 7.92%   |
| Quanta                                 | 39        | 7.36%   |
| Realtek Semiconductor                  | 30        | 5.66%   |
| Sunplus Innovation Technology          | 23        | 4.34%   |
| Luxvisions Innotech Limited            | 19        | 3.58%   |
| Cheng Uei Precision Industry (Foxlink) | 13        | 2.45%   |
| Apple                                  | 13        | 2.45%   |
| Lite-On Technology                     | 12        | 2.26%   |
| Syntek                                 | 10        | 1.89%   |
| Suyin                                  | 9         | 1.7%    |
| Logitech                               | 8         | 1.51%   |
| Acer                                   | 8         | 1.51%   |
| Silicon Motion                         | 7         | 1.32%   |
| Lenovo                                 | 5         | 0.94%   |
| Sonix Technology                       | 4         | 0.75%   |
| Ricoh                                  | 4         | 0.75%   |
| SunplusIT                              | 3         | 0.57%   |
| Microsoft                              | 3         | 0.57%   |
| icSpring                               | 3         | 0.57%   |
| Alcor Micro                            | 3         | 0.57%   |
| Jieli Technology                       | 2         | 0.38%   |
| ALi                                    | 2         | 0.38%   |
| Z-Star Microelectronics                | 1         | 0.19%   |
| Sony Electronics                       | 1         | 0.19%   |
| SN0002                                 | 1         | 0.19%   |
| Primax Electronics                     | 1         | 0.19%   |
| OmniVision Technologies                | 1         | 0.19%   |
| Importek                               | 1         | 0.19%   |
| Image Processor                        | 1         | 0.19%   |
| HRY                                    | 1         | 0.19%   |
| Generalplus Technology                 | 1         | 0.19%   |
| BKX-210918                             | 1         | 0.19%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 40        | 7.45%   |
| Bison BisonCam, NB Pro                              | 29        | 5.4%    |
| Microdia Integrated_Webcam_HD                       | 26        | 4.84%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 19        | 3.54%   |
| IMC Networks Integrated Camera                      | 19        | 3.54%   |
| Bison Integrated Camera                             | 13        | 2.42%   |
| Sunplus Integrated_Webcam_HD                        | 12        | 2.23%   |
| Chicony HP HD Camera                                | 12        | 2.23%   |
| Realtek Integrated_Webcam_HD                        | 11        | 2.05%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 10        | 1.86%   |
| Quanta HD User Facing                               | 9         | 1.68%   |
| Chicony HD Webcam                                   | 9         | 1.68%   |
| Chicony HD User Facing                              | 9         | 1.68%   |
| Syntek Integrated Camera                            | 8         | 1.49%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 7         | 1.3%    |
| Lite-On Integrated Camera                           | 6         | 1.12%   |
| IMC Networks ov9734_azurewave_camera                | 6         | 1.12%   |
| Quanta HP TrueVision HD Camera                      | 5         | 0.93%   |
| Chicony USB2.0 Camera                               | 5         | 0.93%   |
| Chicony Integrated Camera (1280x720@30)             | 5         | 0.93%   |
| Bison Integrated RGB Camera                         | 5         | 0.93%   |
| Apple Built-in iSight                               | 5         | 0.93%   |
| Sonix USB2.0 HD UVC WebCam                          | 4         | 0.74%   |
| Quanta ov9734_techfront_camera                      | 4         | 0.74%   |
| Quanta ACER HD User Facing                          | 4         | 0.74%   |
| Luxvisions Innotech Limited HP HD Camera            | 4         | 0.74%   |
| Chicony USB 2.0 Camera                              | 4         | 0.74%   |
| Chicony HP TrueVision HD Camera                     | 4         | 0.74%   |
| Realtek USB Camera                                  | 3         | 0.56%   |
| Realtek Laptop Camera                               | 3         | 0.56%   |
| Realtek Integrated Webcam                           | 3         | 0.56%   |
| Quanta HP HD Camera                                 | 3         | 0.56%   |
| Microdia Integrated_Webcam_FHD                      | 3         | 0.56%   |
| Microdia Integrated Webcam                          | 3         | 0.56%   |
| Luxvisions Innotech Limited Integrated Camera       | 3         | 0.56%   |
| Lite-On HP HD Camera                                | 3         | 0.56%   |
| Lenovo Integrated Webcam [R5U877]                   | 3         | 0.56%   |
| IMC Networks HD Camera                              | 3         | 0.56%   |
| icSpring camera                                     | 3         | 0.56%   |
| Chicony Integrated IR Camera                        | 3         | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 41        | 35.04%  |
| Validity Sensors                   | 36        | 30.77%  |
| Shenzhen Goodix Technology         | 19        | 16.24%  |
| Elan Microelectronics              | 6         | 5.13%   |
| Upek                               | 5         | 4.27%   |
| STMicroelectronics                 | 3         | 2.56%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 1.71%   |
| LighTuning Technology              | 2         | 1.71%   |
| AuthenTec                          | 2         | 1.71%   |
| Focal-systems.Corp                 | 1         | 0.85%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 18        | 15.38%  |
| Shenzhen Goodix  FingerPrint Device                                        | 17        | 14.53%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 12        | 10.26%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 6.84%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 5         | 4.27%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 5         | 4.27%   |
| Validity Sensors Synaptics WBDI                                            | 5         | 4.27%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 5         | 4.27%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 4         | 3.42%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 4         | 3.42%   |
| Synaptics UWP WBDI Device                                                  | 4         | 3.42%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 2.56%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 2.56%   |
| STMicroelectronics Fingerprint Reader                                      | 3         | 2.56%   |
| Elan ELAN:Fingerprint                                                      | 3         | 2.56%   |
| Elan ELAN:ARM-M4                                                           | 3         | 2.56%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 1.71%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 1.71%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 1.71%   |
| Unknown                                                                    | 2         | 1.71%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.85%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.85%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 0.85%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.85%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 0.85%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.85%   |
| AuthenTec AES1600                                                          | 1         | 0.85%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 19        | 45.24%  |
| Broadcom    | 16        | 38.1%   |
| Lenovo      | 3         | 7.14%   |
| Upek        | 2         | 4.76%   |
| Yubico.com  | 1         | 2.38%   |
| O2 Micro    | 1         | 2.38%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 18        | 42.86%  |
| Broadcom 5880                                                                | 5         | 11.9%   |
| Broadcom 58200                                                               | 5         | 11.9%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 4         | 9.52%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 7.14%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 4.76%   |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 4.76%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 2.38%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 2.38%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 2.38%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 307       | 51.68%  |
| 1     | 232       | 39.06%  |
| 2     | 47        | 7.91%   |
| 3     | 6         | 1.01%   |
| 5     | 1         | 0.17%   |
| 4     | 1         | 0.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 115       | 34.53%  |
| Graphics card            | 92        | 27.63%  |
| Chipcard                 | 36        | 10.81%  |
| Camera                   | 29        | 8.71%   |
| Multimedia controller    | 24        | 7.21%   |
| Net/wireless             | 22        | 6.61%   |
| Bluetooth                | 4         | 1.2%    |
| Storage                  | 2         | 0.6%    |
| Sound                    | 2         | 0.6%    |
| Network                  | 2         | 0.6%    |
| Card reader              | 2         | 0.6%    |
| Wireless                 | 1         | 0.3%    |
| Net/ethernet             | 1         | 0.3%    |
| Communication controller | 1         | 0.3%    |

