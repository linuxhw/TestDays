Fedora - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for Fedora.

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

Total: 7151

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | PRIME B450M-A               | [1e825c5574](https://linux-hardware.org/?probe=1e825c5574) | Oct 01, 2023 |
| MSI           | X99A RAIDER                 | [3e13770075](https://linux-hardware.org/?probe=3e13770075) | Oct 01, 2023 |
| Gigabyte      | D525TUD                     | [913e98318d](https://linux-hardware.org/?probe=913e98318d) | Oct 01, 2023 |
| Gigabyte      | D525TUD                     | [f48a538837](https://linux-hardware.org/?probe=f48a538837) | Oct 01, 2023 |
| ASUSTek       | Z170-DELUXE                 | [9e04efc2d9](https://linux-hardware.org/?probe=9e04efc2d9) | Oct 01, 2023 |
| ASRock        | X570 Taichi                 | [7a670fe0ef](https://linux-hardware.org/?probe=7a670fe0ef) | Sep 30, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | [f3d279f91b](https://linux-hardware.org/?probe=f3d279f91b) | Sep 30, 2023 |
| ASUSTek       | Z170-A                      | [bee067d5dd](https://linux-hardware.org/?probe=bee067d5dd) | Sep 30, 2023 |
| MSI           | PRO B660M-A DDR4            | [a7683dc02d](https://linux-hardware.org/?probe=a7683dc02d) | Sep 30, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | [02af70281a](https://linux-hardware.org/?probe=02af70281a) | Sep 30, 2023 |
| Dell          | 0V8WGR A02                  | [9c9ded765b](https://linux-hardware.org/?probe=9c9ded765b) | Sep 30, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | [9a749a1c41](https://linux-hardware.org/?probe=9a749a1c41) | Sep 30, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | [452cd2622a](https://linux-hardware.org/?probe=452cd2622a) | Sep 30, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [3d40d7878a](https://linux-hardware.org/?probe=3d40d7878a) | Sep 30, 2023 |
| Gigabyte      | GA-870A-UD3                 | [5a507ec4da](https://linux-hardware.org/?probe=5a507ec4da) | Sep 30, 2023 |
| MSI           | X99A RAIDER                 | [a36938e994](https://linux-hardware.org/?probe=a36938e994) | Sep 30, 2023 |
| HP            | 8055                        | [3ddf31c78e](https://linux-hardware.org/?probe=3ddf31c78e) | Sep 30, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [3bec9011bd](https://linux-hardware.org/?probe=3bec9011bd) | Sep 30, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [74bed86ee5](https://linux-hardware.org/?probe=74bed86ee5) | Sep 30, 2023 |
| ASUSTek       | PRIME B450M-A               | [3c9f4d4aef](https://linux-hardware.org/?probe=3c9f4d4aef) | Sep 29, 2023 |
| Intel         | H61                         | [f6a417439c](https://linux-hardware.org/?probe=f6a417439c) | Sep 29, 2023 |
| ASRock        | B450M Pro4 R2.0             | [8e039e23f3](https://linux-hardware.org/?probe=8e039e23f3) | Sep 29, 2023 |
| Intel         | H61                         | [e7dac2f9ed](https://linux-hardware.org/?probe=e7dac2f9ed) | Sep 29, 2023 |
| MSI           | PRO B660M-A DDR4            | [4b5a46a1e2](https://linux-hardware.org/?probe=4b5a46a1e2) | Sep 29, 2023 |
| ANGXUN        | X99-DM3 V3.0                | [1a7ed0ba7d](https://linux-hardware.org/?probe=1a7ed0ba7d) | Sep 29, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [60c04875f1](https://linux-hardware.org/?probe=60c04875f1) | Sep 29, 2023 |
| ASUSTek       | PRIME X570-PRO              | [74ec125e88](https://linux-hardware.org/?probe=74ec125e88) | Sep 29, 2023 |
| ASUSTek       | PRIME X570-PRO              | [cc8c6efba3](https://linux-hardware.org/?probe=cc8c6efba3) | Sep 28, 2023 |
| Dell          | 0YJPT1 A00                  | [a0a41d401e](https://linux-hardware.org/?probe=a0a41d401e) | Sep 28, 2023 |
| MSI           | H310M PRO-VD                | [67e14c1b2d](https://linux-hardware.org/?probe=67e14c1b2d) | Sep 28, 2023 |
| ASUSTek       | Z97-A-USB31                 | [b7e5fb069c](https://linux-hardware.org/?probe=b7e5fb069c) | Sep 28, 2023 |
| Dell          | 0XC7MM A01                  | [9fdfc5a13f](https://linux-hardware.org/?probe=9fdfc5a13f) | Sep 28, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [5dbe8e1541](https://linux-hardware.org/?probe=5dbe8e1541) | Sep 28, 2023 |
| Gigabyte      | B560M AORUS PRO AX          | [2e3d19e919](https://linux-hardware.org/?probe=2e3d19e919) | Sep 28, 2023 |
| MSI           | MPG Z490M GAMING EDGE WI... | [23150c5bd3](https://linux-hardware.org/?probe=23150c5bd3) | Sep 27, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [546df5b57f](https://linux-hardware.org/?probe=546df5b57f) | Sep 27, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [503570ad7a](https://linux-hardware.org/?probe=503570ad7a) | Sep 27, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [41f0f8666c](https://linux-hardware.org/?probe=41f0f8666c) | Sep 27, 2023 |
| Gigabyte      | GA-MA785G-UD3H              | [4f0651ccc2](https://linux-hardware.org/?probe=4f0651ccc2) | Sep 27, 2023 |
| Gigabyte      | B650M K                     | [73da1b7ade](https://linux-hardware.org/?probe=73da1b7ade) | Sep 27, 2023 |
| ASRock        | B450M Steel Legend          | [b4de4fe266](https://linux-hardware.org/?probe=b4de4fe266) | Sep 27, 2023 |
| Dell          | 0773VG A00                  | [a68caa37d8](https://linux-hardware.org/?probe=a68caa37d8) | Sep 26, 2023 |
| Dell          | 0773VG A00                  | [5e34f7d424](https://linux-hardware.org/?probe=5e34f7d424) | Sep 26, 2023 |
| Gigabyte      | B550M S2H                   | [f61801ddb3](https://linux-hardware.org/?probe=f61801ddb3) | Sep 26, 2023 |
| Gigabyte      | B550M DS3H                  | [3bb1109d44](https://linux-hardware.org/?probe=3bb1109d44) | Sep 26, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [85c6c01e63](https://linux-hardware.org/?probe=85c6c01e63) | Sep 26, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [8da87a8c78](https://linux-hardware.org/?probe=8da87a8c78) | Sep 26, 2023 |
| MSI           | MPG B650 CARBON WIFI        | [4b0aff27e8](https://linux-hardware.org/?probe=4b0aff27e8) | Sep 26, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | [b49d28bbd4](https://linux-hardware.org/?probe=b49d28bbd4) | Sep 26, 2023 |
| ASRock        | B450M Steel Legend          | [ccb7f736f6](https://linux-hardware.org/?probe=ccb7f736f6) | Sep 26, 2023 |
| Huanan        | X99-8M-F V1.2               | [4ddba514a1](https://linux-hardware.org/?probe=4ddba514a1) | Sep 26, 2023 |
| MSI           | X99A RAIDER                 | [b69e9b97ec](https://linux-hardware.org/?probe=b69e9b97ec) | Sep 26, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [4375a551e1](https://linux-hardware.org/?probe=4375a551e1) | Sep 25, 2023 |
| ASUSTek       | P9D WS                      | [fd2133400d](https://linux-hardware.org/?probe=fd2133400d) | Sep 25, 2023 |
| MSI           | MPG Z490M GAMING EDGE WI... | [a6ef2b5028](https://linux-hardware.org/?probe=a6ef2b5028) | Sep 25, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [b7dae6ef48](https://linux-hardware.org/?probe=b7dae6ef48) | Sep 25, 2023 |
| ASUSTek       | Z170I PRO GAMING            | [f4d45948eb](https://linux-hardware.org/?probe=f4d45948eb) | Sep 25, 2023 |
| MSI           | X99A RAIDER                 | [c6dc860de5](https://linux-hardware.org/?probe=c6dc860de5) | Sep 25, 2023 |
| ASRock        | B550M Pro4                  | [1b8b856469](https://linux-hardware.org/?probe=1b8b856469) | Sep 25, 2023 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | [23d9e87224](https://linux-hardware.org/?probe=23d9e87224) | Sep 24, 2023 |
| Gigabyte      | X570S UD                    | [88653e2f06](https://linux-hardware.org/?probe=88653e2f06) | Sep 24, 2023 |
| Gigabyte      | EP45-DS3L                   | [57d5f67adf](https://linux-hardware.org/?probe=57d5f67adf) | Sep 24, 2023 |
| ASUSTek       | PRIME B660M-A AC D4         | [7c0eb47c16](https://linux-hardware.org/?probe=7c0eb47c16) | Sep 24, 2023 |
| ASRock        | B150M Pro4/Hyper            | [6bd5055b96](https://linux-hardware.org/?probe=6bd5055b96) | Sep 24, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [5ed3f9381a](https://linux-hardware.org/?probe=5ed3f9381a) | Sep 23, 2023 |
| MSI           | B450M MORTAR MAX            | [fa3021d826](https://linux-hardware.org/?probe=fa3021d826) | Sep 23, 2023 |
| ASRock        | N68C-S UCC                  | [844c35381f](https://linux-hardware.org/?probe=844c35381f) | Sep 23, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [f59df7021c](https://linux-hardware.org/?probe=f59df7021c) | Sep 23, 2023 |
| Gigabyte      | MZGLKBP-00                  | [678c17756d](https://linux-hardware.org/?probe=678c17756d) | Sep 23, 2023 |
| ASRock        | H61M/U3S3                   | [1d397abb90](https://linux-hardware.org/?probe=1d397abb90) | Sep 23, 2023 |
| Dell          | 00010C A00                  | [40d7defca4](https://linux-hardware.org/?probe=40d7defca4) | Sep 23, 2023 |
| Gigabyte      | B85-HD3                     | [5da83e8683](https://linux-hardware.org/?probe=5da83e8683) | Sep 23, 2023 |
| ASUSTek       | PRIME B360-PLUS             | [5629e161ab](https://linux-hardware.org/?probe=5629e161ab) | Sep 23, 2023 |
| MSI           | MS-7388                     | [f5ee235af0](https://linux-hardware.org/?probe=f5ee235af0) | Sep 23, 2023 |
| ASUSTek       | PRIME B660M-A AC D4         | [1a81f24fbb](https://linux-hardware.org/?probe=1a81f24fbb) | Sep 23, 2023 |
| Dell          | 0KWVT8 A03                  | [c6f224508a](https://linux-hardware.org/?probe=c6f224508a) | Sep 23, 2023 |
| HP            | 3397                        | [fa230ba389](https://linux-hardware.org/?probe=fa230ba389) | Sep 23, 2023 |
| MSI           | B450M MORTAR MAX            | [3b9bbcebb0](https://linux-hardware.org/?probe=3b9bbcebb0) | Sep 23, 2023 |
| Dell          | 0PP150 A00                  | [766815ba45](https://linux-hardware.org/?probe=766815ba45) | Sep 22, 2023 |
| MSI           | H110M PRO-D                 | [40380b4dce](https://linux-hardware.org/?probe=40380b4dce) | Sep 22, 2023 |
| HP            | 834F                        | [b69b667f2c](https://linux-hardware.org/?probe=b69b667f2c) | Sep 22, 2023 |
| Gigabyte      | H61M-S2PV                   | [fd5d5651ce](https://linux-hardware.org/?probe=fd5d5651ce) | Sep 22, 2023 |
| MSI           | 760GM-P33                   | [6dfb722e45](https://linux-hardware.org/?probe=6dfb722e45) | Sep 22, 2023 |
| ASUSTek       | PRIME X570-P                | [21b73523cf](https://linux-hardware.org/?probe=21b73523cf) | Sep 22, 2023 |
| Gigabyte      | Z170-D3H-CF                 | [2e715ca7b2](https://linux-hardware.org/?probe=2e715ca7b2) | Sep 22, 2023 |
| ASUSTek       | Rampage V EXTREME           | [fe545c13e7](https://linux-hardware.org/?probe=fe545c13e7) | Sep 22, 2023 |
| Lenovo        | 1036 SDK0Q40104 WIN 3305... | [80c7b750ea](https://linux-hardware.org/?probe=80c7b750ea) | Sep 21, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [609a91b51f](https://linux-hardware.org/?probe=609a91b51f) | Sep 21, 2023 |
| ANGXUN        | X99-DM3 V3.0                | [20e0572ade](https://linux-hardware.org/?probe=20e0572ade) | Sep 21, 2023 |
| Intel         | B75                         | [37b59e6605](https://linux-hardware.org/?probe=37b59e6605) | Sep 21, 2023 |
| HP            | 1495                        | [ad97ea883d](https://linux-hardware.org/?probe=ad97ea883d) | Sep 21, 2023 |
| HP            | 3047h                       | [cb19fdc589](https://linux-hardware.org/?probe=cb19fdc589) | Sep 21, 2023 |
| Apple         | Mac-27AD2F918AE68F61 Mac... | [ff9bab7040](https://linux-hardware.org/?probe=ff9bab7040) | Sep 21, 2023 |
| Gigabyte      | B360M D3H-CF                | [875f4f3f2a](https://linux-hardware.org/?probe=875f4f3f2a) | Sep 21, 2023 |
| ASUSTek       | V230IC                      | [aea46e7fc6](https://linux-hardware.org/?probe=aea46e7fc6) | Sep 21, 2023 |
| MSI           | Z270M MORTAR                | [ec0adfb60f](https://linux-hardware.org/?probe=ec0adfb60f) | Sep 21, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | [5e05853c00](https://linux-hardware.org/?probe=5e05853c00) | Sep 20, 2023 |
| HP            | 3397                        | [f202c90e23](https://linux-hardware.org/?probe=f202c90e23) | Sep 20, 2023 |
| Dell          | 0WN7Y6 A01                  | [f4d4f80645](https://linux-hardware.org/?probe=f4d4f80645) | Sep 20, 2023 |
| Gigabyte      | Z77MX-D3H                   | [624ebbd6c1](https://linux-hardware.org/?probe=624ebbd6c1) | Sep 20, 2023 |
| ASUSTek       | Z170I PRO GAMING            | [238224ef08](https://linux-hardware.org/?probe=238224ef08) | Sep 20, 2023 |
| Gigabyte      | H110M-DS2-CF                | [b2519e8577](https://linux-hardware.org/?probe=b2519e8577) | Sep 20, 2023 |
| Dell          | 06HR05 A00                  | [a01d6b8630](https://linux-hardware.org/?probe=a01d6b8630) | Sep 20, 2023 |
| MSI           | A320M-A PRO MAX             | [411b34f287](https://linux-hardware.org/?probe=411b34f287) | Sep 19, 2023 |
| ASUSTek       | PRIME B550M-A               | [56d2a67030](https://linux-hardware.org/?probe=56d2a67030) | Sep 19, 2023 |
| Gigabyte      | J1900M-D2P                  | [1bd6653d3e](https://linux-hardware.org/?probe=1bd6653d3e) | Sep 19, 2023 |
| Positivo      | POS-EIH610EX 11187943       | [10fbe8fd9b](https://linux-hardware.org/?probe=10fbe8fd9b) | Sep 18, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [96a6758726](https://linux-hardware.org/?probe=96a6758726) | Sep 18, 2023 |
| Lenovo        | ThinkCentre M58p 7220A72    | [39d6e8a728](https://linux-hardware.org/?probe=39d6e8a728) | Sep 18, 2023 |
| Gigabyte      | GA-880GM-UD2H               | [7e05f3299f](https://linux-hardware.org/?probe=7e05f3299f) | Sep 18, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [517795acfd](https://linux-hardware.org/?probe=517795acfd) | Sep 18, 2023 |
| Kllisre       | X99-B5 V1.1                 | [5597daf348](https://linux-hardware.org/?probe=5597daf348) | Sep 18, 2023 |
| Gigabyte      | 970A-DS3P                   | [b0de1885b9](https://linux-hardware.org/?probe=b0de1885b9) | Sep 18, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [8566235f94](https://linux-hardware.org/?probe=8566235f94) | Sep 17, 2023 |
| Dell          | 0MGK50 A02                  | [ec87c19874](https://linux-hardware.org/?probe=ec87c19874) | Sep 17, 2023 |
| ASRock        | B450 Pro4                   | [2e8cd612d8](https://linux-hardware.org/?probe=2e8cd612d8) | Sep 17, 2023 |
| ASUSTek       | Pro H510M-C                 | [aff784bd75](https://linux-hardware.org/?probe=aff784bd75) | Sep 16, 2023 |
| ASUSTek       | PRIME H270-PRO              | [394d932643](https://linux-hardware.org/?probe=394d932643) | Sep 16, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [83c2fb6018](https://linux-hardware.org/?probe=83c2fb6018) | Sep 16, 2023 |
| Intel         | DQ45CB AAE30148-207         | [2c74d735db](https://linux-hardware.org/?probe=2c74d735db) | Sep 16, 2023 |
| Gigabyte      | GA-H81M-DS2-CF              | [3ebcf35cf2](https://linux-hardware.org/?probe=3ebcf35cf2) | Sep 15, 2023 |
| HP            | 84FD                        | [d0845ca4d2](https://linux-hardware.org/?probe=d0845ca4d2) | Sep 15, 2023 |
| Gigabyte      | GA-H81M-DS2-CF              | [8e5f637ac0](https://linux-hardware.org/?probe=8e5f637ac0) | Sep 15, 2023 |
| HP            | 3397                        | [3cf175e939](https://linux-hardware.org/?probe=3cf175e939) | Sep 14, 2023 |
| MSI           | 2A9C                        | [378490ed0b](https://linux-hardware.org/?probe=378490ed0b) | Sep 14, 2023 |
| ASRock        | B450M-HDV R4.0              | [305679af22](https://linux-hardware.org/?probe=305679af22) | Sep 14, 2023 |
| HP            | 8459                        | [e7cbc6d34d](https://linux-hardware.org/?probe=e7cbc6d34d) | Sep 14, 2023 |
| Dell          | 0YXT71 A02                  | [f462fe5985](https://linux-hardware.org/?probe=f462fe5985) | Sep 14, 2023 |
| Intel         | DH87MC AAG74242-401         | [6c37cc0b51](https://linux-hardware.org/?probe=6c37cc0b51) | Sep 14, 2023 |
| HP            | 843B                        | [08ce9ca0eb](https://linux-hardware.org/?probe=08ce9ca0eb) | Sep 14, 2023 |
| MSI           | MPG Z690 EDGE WIFI          | [2ad1c71fce](https://linux-hardware.org/?probe=2ad1c71fce) | Sep 13, 2023 |
| Gigabyte      | Z170-D3H-CF                 | [418eee8ea7](https://linux-hardware.org/?probe=418eee8ea7) | Sep 13, 2023 |
| ASUSTek       | PRIME X570-PRO              | [746f94b75d](https://linux-hardware.org/?probe=746f94b75d) | Sep 13, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [035fb7f099](https://linux-hardware.org/?probe=035fb7f099) | Sep 13, 2023 |
| MSI           | MAG B460M MORTAR            | [c0980eee03](https://linux-hardware.org/?probe=c0980eee03) | Sep 13, 2023 |
| Gigabyte      | GA-870A-UD3                 | [20ec05f55b](https://linux-hardware.org/?probe=20ec05f55b) | Sep 13, 2023 |
| Gigabyte      | GA-870A-UD3                 | [172b7a1d48](https://linux-hardware.org/?probe=172b7a1d48) | Sep 13, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [a7e93922ce](https://linux-hardware.org/?probe=a7e93922ce) | Sep 13, 2023 |
| Acer          | F690GVM                     | [a9a370c528](https://linux-hardware.org/?probe=a9a370c528) | Sep 13, 2023 |
| Pegatron      | IPMSB-VH1/HDMI/ODM          | [fd4e189b56](https://linux-hardware.org/?probe=fd4e189b56) | Sep 12, 2023 |
| Gigabyte      | B450M S2H                   | [9099ebc0a7](https://linux-hardware.org/?probe=9099ebc0a7) | Sep 12, 2023 |
| ASUSTek       | Maximus VI EXTREME          | [e1eea73611](https://linux-hardware.org/?probe=e1eea73611) | Sep 12, 2023 |
| HP            | 3397                        | [ed9caadb58](https://linux-hardware.org/?probe=ed9caadb58) | Sep 12, 2023 |
| MSI           | MPG Z490 GAMING PLUS        | [f5b3cd74bc](https://linux-hardware.org/?probe=f5b3cd74bc) | Sep 11, 2023 |
| Dell          | 0GXM1W A01                  | [ff9bf89fad](https://linux-hardware.org/?probe=ff9bf89fad) | Sep 11, 2023 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | [baeb174dc3](https://linux-hardware.org/?probe=baeb174dc3) | Sep 10, 2023 |
| ASRock        | B550M Pro4                  | [92eb1e3aa7](https://linux-hardware.org/?probe=92eb1e3aa7) | Sep 10, 2023 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | [6dc842bbb4](https://linux-hardware.org/?probe=6dc842bbb4) | Sep 10, 2023 |
| Dell          | 042P49 A01                  | [fc47b9c2f4](https://linux-hardware.org/?probe=fc47b9c2f4) | Sep 10, 2023 |
| Dell          | 0GM819                      | [f7d8bdb2a3](https://linux-hardware.org/?probe=f7d8bdb2a3) | Sep 10, 2023 |
| Acer          | Veriton M2631 V:1.0         | [ec947814d1](https://linux-hardware.org/?probe=ec947814d1) | Sep 10, 2023 |
| ASRock        | H570M Pro4                  | [4124ca4b35](https://linux-hardware.org/?probe=4124ca4b35) | Sep 10, 2023 |
| ASRock        | H97M Pro4                   | [a875b11982](https://linux-hardware.org/?probe=a875b11982) | Sep 10, 2023 |
| Dell          | 084J0R A00                  | [25d0f0d7ef](https://linux-hardware.org/?probe=25d0f0d7ef) | Sep 10, 2023 |
| MSI           | MAG Z390 TOMAHAWK           | [7b441b9b50](https://linux-hardware.org/?probe=7b441b9b50) | Sep 10, 2023 |
| MSI           | MPG Z790I EDGE WIFI         | [1225463e4a](https://linux-hardware.org/?probe=1225463e4a) | Sep 09, 2023 |
| ASUSTek       | PRIME B550M-A               | [7d3f7effe2](https://linux-hardware.org/?probe=7d3f7effe2) | Sep 09, 2023 |
| Unknown       | Unknown                     | [aa67f256bc](https://linux-hardware.org/?probe=aa67f256bc) | Sep 09, 2023 |
| Gigabyte      | B450M DS3H-CF               | [c8e3d0d7f9](https://linux-hardware.org/?probe=c8e3d0d7f9) | Sep 09, 2023 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | [b15cd2d6e5](https://linux-hardware.org/?probe=b15cd2d6e5) | Sep 09, 2023 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | [d6302862b1](https://linux-hardware.org/?probe=d6302862b1) | Sep 09, 2023 |
| Dell          | 00V62H A00                  | [fc7937d763](https://linux-hardware.org/?probe=fc7937d763) | Sep 09, 2023 |
| ASRock        | B450M Pro4                  | [a47195331c](https://linux-hardware.org/?probe=a47195331c) | Sep 08, 2023 |
| Lenovo        | SHARKBAY NOK                | [a09c6ad4a9](https://linux-hardware.org/?probe=a09c6ad4a9) | Sep 08, 2023 |
| ASUSTek       | P8Z77-I DELUXE              | [b5081191af](https://linux-hardware.org/?probe=b5081191af) | Sep 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [6e57fc6cf2](https://linux-hardware.org/?probe=6e57fc6cf2) | Sep 08, 2023 |
| Gigabyte      | B650I AORUS ULTRA           | [03a233a395](https://linux-hardware.org/?probe=03a233a395) | Sep 08, 2023 |
| HP            | ProLiant ML110 G7           | [5f806b31b4](https://linux-hardware.org/?probe=5f806b31b4) | Sep 08, 2023 |
| Gigabyte      | G41MT-D3                    | [0940dc7ebd](https://linux-hardware.org/?probe=0940dc7ebd) | Sep 08, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [860985ecc0](https://linux-hardware.org/?probe=860985ecc0) | Sep 08, 2023 |
| MSI           | X99A RAIDER                 | [362b2dadfc](https://linux-hardware.org/?probe=362b2dadfc) | Sep 08, 2023 |
| HP            | 1497                        | [1729554f58](https://linux-hardware.org/?probe=1729554f58) | Sep 07, 2023 |
| Dell          | 0J37VM A01                  | [7781be38be](https://linux-hardware.org/?probe=7781be38be) | Sep 07, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [d98f5a5a06](https://linux-hardware.org/?probe=d98f5a5a06) | Sep 07, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [35b6b3a9dd](https://linux-hardware.org/?probe=35b6b3a9dd) | Sep 07, 2023 |
| Dell          | 0NDYHG A01                  | [250bc7b8ea](https://linux-hardware.org/?probe=250bc7b8ea) | Sep 07, 2023 |
| NZXT          | N7 Z370                     | [34a23bdc5f](https://linux-hardware.org/?probe=34a23bdc5f) | Sep 07, 2023 |
| Dell          | 088DT1 A01                  | [e7d12d040e](https://linux-hardware.org/?probe=e7d12d040e) | Sep 07, 2023 |
| MSI           | X99A RAIDER                 | [0434d08b59](https://linux-hardware.org/?probe=0434d08b59) | Sep 07, 2023 |
| Gigabyte      | G41MT-D3                    | [f0c3188082](https://linux-hardware.org/?probe=f0c3188082) | Sep 07, 2023 |
| ASUSTek       | PRIME B550M-A               | [b17a5edce5](https://linux-hardware.org/?probe=b17a5edce5) | Sep 06, 2023 |
| Pegatron      | 2AB6                        | [40b17904fa](https://linux-hardware.org/?probe=40b17904fa) | Sep 06, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [09e4ad77a9](https://linux-hardware.org/?probe=09e4ad77a9) | Sep 06, 2023 |
| HP            | 3047h                       | [9b6ecf8471](https://linux-hardware.org/?probe=9b6ecf8471) | Sep 06, 2023 |
| HP            | 3047h                       | [51ba95dc5a](https://linux-hardware.org/?probe=51ba95dc5a) | Sep 06, 2023 |
| ASRock        | B650E PG-ITX WiFi           | [9dd5c2a861](https://linux-hardware.org/?probe=9dd5c2a861) | Sep 06, 2023 |
| Dell          | 02YYK5 A01                  | [ce6860153d](https://linux-hardware.org/?probe=ce6860153d) | Sep 06, 2023 |
| Pegatron      | TRUCKEE                     | [145414b8e3](https://linux-hardware.org/?probe=145414b8e3) | Sep 06, 2023 |
| ASUSTek       | PRIME B550M-A               | [7b99e058ff](https://linux-hardware.org/?probe=7b99e058ff) | Sep 06, 2023 |
| Gigabyte      | Z68MA-D2H-B3                | [7db6779b5c](https://linux-hardware.org/?probe=7db6779b5c) | Sep 06, 2023 |
| MSI           | A320M PRO-VH PLUS           | [9614656d9b](https://linux-hardware.org/?probe=9614656d9b) | Sep 05, 2023 |
| HP            | 82E0                        | [a86ac881df](https://linux-hardware.org/?probe=a86ac881df) | Sep 05, 2023 |
| ASRock        | AD525PV3                    | [0fa982f7ad](https://linux-hardware.org/?probe=0fa982f7ad) | Sep 05, 2023 |
| ASRock        | AD525PV3                    | [9ab25d4913](https://linux-hardware.org/?probe=9ab25d4913) | Sep 05, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [44c55bd588](https://linux-hardware.org/?probe=44c55bd588) | Sep 05, 2023 |
| MSI           | A320M PRO-VH PLUS           | [3e2b7d52c5](https://linux-hardware.org/?probe=3e2b7d52c5) | Sep 05, 2023 |
| MSI           | X99A RAIDER                 | [c06fdd0648](https://linux-hardware.org/?probe=c06fdd0648) | Sep 05, 2023 |
| ASUSTek       | A8R32-MVP Deluxe            | [d20cf2e835](https://linux-hardware.org/?probe=d20cf2e835) | Sep 05, 2023 |
| ASRock        | H310M-STX                   | [5585353638](https://linux-hardware.org/?probe=5585353638) | Sep 04, 2023 |
| ASUSTek       | X99-M WS                    | [f324b3dd33](https://linux-hardware.org/?probe=f324b3dd33) | Sep 04, 2023 |
| ASUSTek       | Pro H510M-C                 | [ea823862a6](https://linux-hardware.org/?probe=ea823862a6) | Sep 04, 2023 |
| ASUSTek       | PRIME B550M-A               | [d99ec42689](https://linux-hardware.org/?probe=d99ec42689) | Sep 04, 2023 |
| MSI           | MPG X570S EDGE MAX WIFI     | [59b20fdfab](https://linux-hardware.org/?probe=59b20fdfab) | Sep 04, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | [80a94d69c2](https://linux-hardware.org/?probe=80a94d69c2) | Sep 04, 2023 |
| MSI           | X99A RAIDER                 | [6bf9db20f8](https://linux-hardware.org/?probe=6bf9db20f8) | Sep 04, 2023 |
| Dell          | 042P49 A01                  | [29e55d4d72](https://linux-hardware.org/?probe=29e55d4d72) | Sep 04, 2023 |
| MSI           | B450M PRO-VDH PLUS          | [7e0c89dfdb](https://linux-hardware.org/?probe=7e0c89dfdb) | Sep 04, 2023 |
| ASUSTek       | PRIME B550M-A               | [2252b35243](https://linux-hardware.org/?probe=2252b35243) | Sep 03, 2023 |
| MSI           | MAG B460M MORTAR            | [dd19cc0d48](https://linux-hardware.org/?probe=dd19cc0d48) | Sep 03, 2023 |
| MSI           | MAG B460M MORTAR            | [fc0731667e](https://linux-hardware.org/?probe=fc0731667e) | Sep 03, 2023 |
| MSI           | MAG B460M MORTAR            | [5e3f2f01d4](https://linux-hardware.org/?probe=5e3f2f01d4) | Sep 03, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [926751fb6e](https://linux-hardware.org/?probe=926751fb6e) | Sep 03, 2023 |
| Gigabyte      | X79-UP4                     | [3593994f4e](https://linux-hardware.org/?probe=3593994f4e) | Sep 03, 2023 |
| Dell          | 0HHV7N A00                  | [9ae746229d](https://linux-hardware.org/?probe=9ae746229d) | Sep 02, 2023 |
| Lenovo        | 3129 SDK0J40700 WIN 3258... | [c4c911d725](https://linux-hardware.org/?probe=c4c911d725) | Sep 02, 2023 |
| Lenovo        | 3129 SDK0J40700 WIN 3258... | [bc7e99e576](https://linux-hardware.org/?probe=bc7e99e576) | Sep 02, 2023 |
| Gigabyte      | MZGLKBP-00                  | [e6c5ae208f](https://linux-hardware.org/?probe=e6c5ae208f) | Sep 02, 2023 |
| Dell          | 0GY6Y8 A01                  | [f592e65a04](https://linux-hardware.org/?probe=f592e65a04) | Sep 02, 2023 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [d7fcde026e](https://linux-hardware.org/?probe=d7fcde026e) | Sep 02, 2023 |
| ASUSTek       | PRIME Z370-P                | [f6a5d73879](https://linux-hardware.org/?probe=f6a5d73879) | Sep 01, 2023 |
| HP            | 89B5 A                      | [3b6a46c308](https://linux-hardware.org/?probe=3b6a46c308) | Sep 01, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [90be513b41](https://linux-hardware.org/?probe=90be513b41) | Sep 01, 2023 |
| ASUSTek       | E3M-ET V5 SERIES            | [62d1008e3a](https://linux-hardware.org/?probe=62d1008e3a) | Sep 01, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [81e9e055de](https://linux-hardware.org/?probe=81e9e055de) | Sep 01, 2023 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | [a4ee14b9ac](https://linux-hardware.org/?probe=a4ee14b9ac) | Sep 01, 2023 |
| MSI           | MPG B650I EDGE WIFI         | [dd5735f315](https://linux-hardware.org/?probe=dd5735f315) | Sep 01, 2023 |
| Unknown       | H110M2                      | [bff031410a](https://linux-hardware.org/?probe=bff031410a) | Aug 31, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [57ecd81ed7](https://linux-hardware.org/?probe=57ecd81ed7) | Aug 31, 2023 |
| ASUSTek       | Crosshair V Formula         | [85cb771ac1](https://linux-hardware.org/?probe=85cb771ac1) | Aug 31, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [ffa39e6acd](https://linux-hardware.org/?probe=ffa39e6acd) | Aug 31, 2023 |
| Gigabyte      | Z270X-Gaming K5             | [189647b3df](https://linux-hardware.org/?probe=189647b3df) | Aug 31, 2023 |
| ASUSTek       | EX-H110M-V3                 | [c38af5d04d](https://linux-hardware.org/?probe=c38af5d04d) | Aug 31, 2023 |
| Gigabyte      | H77N-WIFI                   | [84ed05802d](https://linux-hardware.org/?probe=84ed05802d) | Aug 31, 2023 |
| Gigabyte      | D525TUD                     | [9a459d2372](https://linux-hardware.org/?probe=9a459d2372) | Aug 31, 2023 |
| Gigabyte      | Z77MX-D3H                   | [ffb1e72844](https://linux-hardware.org/?probe=ffb1e72844) | Aug 31, 2023 |
| ASUSTek       | EX-H110M-V3                 | [e2b97e4436](https://linux-hardware.org/?probe=e2b97e4436) | Aug 31, 2023 |
| MSI           | 970 GAMING                  | [f5aaee7de3](https://linux-hardware.org/?probe=f5aaee7de3) | Aug 31, 2023 |
| ASUSTek       | PHOENIX                     | [5fa96dfd97](https://linux-hardware.org/?probe=5fa96dfd97) | Aug 31, 2023 |
| Gigabyte      | MZGLKBP-00                  | [2ed0efb0a0](https://linux-hardware.org/?probe=2ed0efb0a0) | Aug 31, 2023 |
| LattePanda    | 3 Delta LP-BS-7-S70JR120... | [04d647ae08](https://linux-hardware.org/?probe=04d647ae08) | Aug 30, 2023 |
| Dell          | 0J2J3Y A00                  | [57ac609885](https://linux-hardware.org/?probe=57ac609885) | Aug 30, 2023 |
| Gigabyte      | Z270X-Gaming K5             | [193a50f761](https://linux-hardware.org/?probe=193a50f761) | Aug 30, 2023 |
| MSI           | H110M PRO-VD PLUS           | [a75e60a457](https://linux-hardware.org/?probe=a75e60a457) | Aug 30, 2023 |
| ASUSTek       | PRIME Z490-A                | [3cfa79235e](https://linux-hardware.org/?probe=3cfa79235e) | Aug 30, 2023 |
| ASUSTek       | TUF Z370-PLUS GAMING        | [b93e0fc32b](https://linux-hardware.org/?probe=b93e0fc32b) | Aug 30, 2023 |
| MSI           | Z270M MORTAR                | [416723b60c](https://linux-hardware.org/?probe=416723b60c) | Aug 30, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [44e98cb157](https://linux-hardware.org/?probe=44e98cb157) | Aug 29, 2023 |
| Gigabyte      | G41MT-D3                    | [a2f594cf56](https://linux-hardware.org/?probe=a2f594cf56) | Aug 29, 2023 |
| MSI           | Z370-A PRO                  | [d9a6d27a28](https://linux-hardware.org/?probe=d9a6d27a28) | Aug 29, 2023 |
| ASUSTek       | TUF Z370-PLUS GAMING        | [7da432892e](https://linux-hardware.org/?probe=7da432892e) | Aug 29, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [1fd98a124f](https://linux-hardware.org/?probe=1fd98a124f) | Aug 29, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [7674d12aa5](https://linux-hardware.org/?probe=7674d12aa5) | Aug 28, 2023 |
| Fujitsu       | D3817-A1 S26361-D3817-A1... | [50e64dbfa2](https://linux-hardware.org/?probe=50e64dbfa2) | Aug 28, 2023 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | [b68e4634b7](https://linux-hardware.org/?probe=b68e4634b7) | Aug 28, 2023 |
| Gigabyte      | EP45-DS3L                   | [c326205a9b](https://linux-hardware.org/?probe=c326205a9b) | Aug 27, 2023 |
| Fujitsu       | D3417-B1 S26361-D3417-B1    | [492a021411](https://linux-hardware.org/?probe=492a021411) | Aug 27, 2023 |
| Acer          | Veriton X2631G V:1.0        | [47b9d876af](https://linux-hardware.org/?probe=47b9d876af) | Aug 27, 2023 |
| Fujitsu       | D3417-B1 S26361-D3417-B1    | [c1bea53459](https://linux-hardware.org/?probe=c1bea53459) | Aug 27, 2023 |
| Gigabyte      | H77N-WIFI                   | [d80e4744e9](https://linux-hardware.org/?probe=d80e4744e9) | Aug 27, 2023 |
| MSI           | MS-7388                     | [42530086f2](https://linux-hardware.org/?probe=42530086f2) | Aug 27, 2023 |
| Dell          | 04Y8V0 A02                  | [629b07f8bc](https://linux-hardware.org/?probe=629b07f8bc) | Aug 27, 2023 |
| Gigabyte      | B560M AORUS ELITE           | [f71c3553e6](https://linux-hardware.org/?probe=f71c3553e6) | Aug 27, 2023 |
| Gigabyte      | GA-880GM-UD2H               | [08748d2c86](https://linux-hardware.org/?probe=08748d2c86) | Aug 27, 2023 |
| ASUSTek       | Z170-P                      | [9e90f8b308](https://linux-hardware.org/?probe=9e90f8b308) | Aug 26, 2023 |
| Dell          | 0GXM1W A01                  | [9bd4ef3aac](https://linux-hardware.org/?probe=9bd4ef3aac) | Aug 26, 2023 |
| Dell          | 0GXM1W A01                  | [978f1e9fa5](https://linux-hardware.org/?probe=978f1e9fa5) | Aug 26, 2023 |
| AZW           | U59                         | [ea7bf087cc](https://linux-hardware.org/?probe=ea7bf087cc) | Aug 26, 2023 |
| AZW           | U59                         | [d35717e2e4](https://linux-hardware.org/?probe=d35717e2e4) | Aug 26, 2023 |
| ASRock        | B560 Steel Legend           | [b2e8cd4ed2](https://linux-hardware.org/?probe=b2e8cd4ed2) | Aug 26, 2023 |
| MSI           | MS-B9321                    | [07564a2fc4](https://linux-hardware.org/?probe=07564a2fc4) | Aug 25, 2023 |
| Dell          | 0HHV7N A00                  | [1bcc49b615](https://linux-hardware.org/?probe=1bcc49b615) | Aug 25, 2023 |
| MSI           | MS-B9321                    | [df54486a48](https://linux-hardware.org/?probe=df54486a48) | Aug 25, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [771adfa310](https://linux-hardware.org/?probe=771adfa310) | Aug 25, 2023 |
| MSI           | MS-7388                     | [5c1e4b0c2b](https://linux-hardware.org/?probe=5c1e4b0c2b) | Aug 25, 2023 |
| Acer          | Veriton N4640G              | [914ba9937f](https://linux-hardware.org/?probe=914ba9937f) | Aug 25, 2023 |
| HP            | 3047h                       | [5c415723ef](https://linux-hardware.org/?probe=5c415723ef) | Aug 24, 2023 |
| Dell          | 088DT1 A01                  | [0d9ddb7de2](https://linux-hardware.org/?probe=0d9ddb7de2) | Aug 24, 2023 |
| Packard Be... | GA-T671MG                   | [ba401056e8](https://linux-hardware.org/?probe=ba401056e8) | Aug 24, 2023 |
| Gigabyte      | F2A88XM-D3H                 | [6486781183](https://linux-hardware.org/?probe=6486781183) | Aug 24, 2023 |
| Packard Be... | GA-T671MG                   | [d51fb378a1](https://linux-hardware.org/?probe=d51fb378a1) | Aug 24, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [c86651dbd3](https://linux-hardware.org/?probe=c86651dbd3) | Aug 24, 2023 |
| MSI           | A320M-A PRO                 | [25dc707bff](https://linux-hardware.org/?probe=25dc707bff) | Aug 24, 2023 |
| ASRock        | B560M-ITX/ac                | [1330f2ac2a](https://linux-hardware.org/?probe=1330f2ac2a) | Aug 24, 2023 |
| Gigabyte      | H310M M.2                   | [9b1205f50a](https://linux-hardware.org/?probe=9b1205f50a) | Aug 24, 2023 |
| ASUSTek       | B85M-E                      | [a06cf8de37](https://linux-hardware.org/?probe=a06cf8de37) | Aug 24, 2023 |
| ASUSTek       | B85M-E                      | [b6591e9fd9](https://linux-hardware.org/?probe=b6591e9fd9) | Aug 24, 2023 |
| AZW           | GTR V02                     | [6c91212b1a](https://linux-hardware.org/?probe=6c91212b1a) | Aug 24, 2023 |
| ASRock        | FP6D4-P1                    | [722789f2ac](https://linux-hardware.org/?probe=722789f2ac) | Aug 23, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | [fd9fa02e66](https://linux-hardware.org/?probe=fd9fa02e66) | Aug 23, 2023 |
| MSI           | B550-A PRO                  | [f2f57d0e61](https://linux-hardware.org/?probe=f2f57d0e61) | Aug 23, 2023 |
| Gigabyte      | B85M-D3V-A                  | [e11053f833](https://linux-hardware.org/?probe=e11053f833) | Aug 23, 2023 |
| ASRock        | Z77 Extreme6                | [6477cdd647](https://linux-hardware.org/?probe=6477cdd647) | Aug 23, 2023 |
| Gigabyte      | GA-A55M-S2V                 | [e9b32aa827](https://linux-hardware.org/?probe=e9b32aa827) | Aug 23, 2023 |
| MSI           | Z370-OC PRO                 | [4ee0bb1c63](https://linux-hardware.org/?probe=4ee0bb1c63) | Aug 23, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | [64f3da359d](https://linux-hardware.org/?probe=64f3da359d) | Aug 22, 2023 |
| Lenovo        | 1046 SDK0T08861 WIN 3305... | [fe7b3d01bb](https://linux-hardware.org/?probe=fe7b3d01bb) | Aug 22, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [73a003bf4b](https://linux-hardware.org/?probe=73a003bf4b) | Aug 22, 2023 |
| MSI           | H510M-A PRO                 | [e405022cc9](https://linux-hardware.org/?probe=e405022cc9) | Aug 22, 2023 |
| MSI           | Z370-OC PRO                 | [bbd85c94d6](https://linux-hardware.org/?probe=bbd85c94d6) | Aug 22, 2023 |
| ASUSTek       | B460M-N                     | [382640772b](https://linux-hardware.org/?probe=382640772b) | Aug 22, 2023 |
| Gigabyte      | X570 GAMING X               | [6a3c737df2](https://linux-hardware.org/?probe=6a3c737df2) | Aug 22, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [05c761f480](https://linux-hardware.org/?probe=05c761f480) | Aug 22, 2023 |
| Intel         | DH77EB AAG39073-304         | [70399bc4c6](https://linux-hardware.org/?probe=70399bc4c6) | Aug 21, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [fdfc3b92f9](https://linux-hardware.org/?probe=fdfc3b92f9) | Aug 21, 2023 |
| ASUSTek       | P8Z77-I DELUXE              | [09d57c6701](https://linux-hardware.org/?probe=09d57c6701) | Aug 21, 2023 |
| HP            | 3048h                       | [959637abde](https://linux-hardware.org/?probe=959637abde) | Aug 21, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [735e03f0f9](https://linux-hardware.org/?probe=735e03f0f9) | Aug 21, 2023 |
| MSI           | PRO B650M-A WIFI            | [da3f4808a1](https://linux-hardware.org/?probe=da3f4808a1) | Aug 20, 2023 |
| ASRock        | A520M-HDV                   | [cb333c6fae](https://linux-hardware.org/?probe=cb333c6fae) | Aug 20, 2023 |
| Pegatron      | TRUCKEE                     | [c3a8668cee](https://linux-hardware.org/?probe=c3a8668cee) | Aug 20, 2023 |
| Pegatron      | TRUCKEE                     | [7da89c9360](https://linux-hardware.org/?probe=7da89c9360) | Aug 20, 2023 |
| MSI           | H310M PRO-VDH               | [c6f278a589](https://linux-hardware.org/?probe=c6f278a589) | Aug 20, 2023 |
| ASUSTek       | CM6870                      | [05507d2151](https://linux-hardware.org/?probe=05507d2151) | Aug 20, 2023 |
| ASUSTek       | CM6870                      | [b91ffcb2be](https://linux-hardware.org/?probe=b91ffcb2be) | Aug 20, 2023 |
| HP            | 3032h                       | [f3292df409](https://linux-hardware.org/?probe=f3292df409) | Aug 20, 2023 |
| ASUSTek       | Rampage V EXTREME           | [1b7a1416fc](https://linux-hardware.org/?probe=1b7a1416fc) | Aug 20, 2023 |
| Dell          | 04Y8V0 A02                  | [645bd9ed6b](https://linux-hardware.org/?probe=645bd9ed6b) | Aug 20, 2023 |
| Gigabyte      | B450M DS3H-CF               | [978af80f5a](https://linux-hardware.org/?probe=978af80f5a) | Aug 20, 2023 |
| Gigabyte      | B450M DS3H-CF               | [06daace50c](https://linux-hardware.org/?probe=06daace50c) | Aug 20, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | [a15e796833](https://linux-hardware.org/?probe=a15e796833) | Aug 19, 2023 |
| ASUSTek       | M4A77                       | [89bb5a2821](https://linux-hardware.org/?probe=89bb5a2821) | Aug 19, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [c99b76f9fe](https://linux-hardware.org/?probe=c99b76f9fe) | Aug 19, 2023 |
| Gigabyte      | B450M H                     | [722707e986](https://linux-hardware.org/?probe=722707e986) | Aug 18, 2023 |
| Dell          | 0YJMC0 A02                  | [f4818214d5](https://linux-hardware.org/?probe=f4818214d5) | Aug 18, 2023 |
| Dell          | 06D7TR A00                  | [f719885fe3](https://linux-hardware.org/?probe=f719885fe3) | Aug 18, 2023 |
| MSI           | X470 GAMING M7 AC           | [92f8391f8f](https://linux-hardware.org/?probe=92f8391f8f) | Aug 18, 2023 |
| ASUSTek       | Z97-PRO                     | [607356bb8f](https://linux-hardware.org/?probe=607356bb8f) | Aug 17, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [8958908392](https://linux-hardware.org/?probe=8958908392) | Aug 17, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | [4b8894823c](https://linux-hardware.org/?probe=4b8894823c) | Aug 17, 2023 |
| ASUSTek       | Pro B550M-C                 | [0af0e7a958](https://linux-hardware.org/?probe=0af0e7a958) | Aug 17, 2023 |
| MSI           | A320M PRO-VH PLUS           | [65a1f155c0](https://linux-hardware.org/?probe=65a1f155c0) | Aug 17, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [ae88c56896](https://linux-hardware.org/?probe=ae88c56896) | Aug 17, 2023 |
| ASRock        | A320M-HD R4.0               | [f67dd298b1](https://linux-hardware.org/?probe=f67dd298b1) | Aug 16, 2023 |
| Dell          | 0VRWRC A00                  | [b27f36262e](https://linux-hardware.org/?probe=b27f36262e) | Aug 16, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [725cdd1013](https://linux-hardware.org/?probe=725cdd1013) | Aug 16, 2023 |
| MSI           | Z170A GAMING M9 ACK         | [1ff9bff198](https://linux-hardware.org/?probe=1ff9bff198) | Aug 15, 2023 |
| HP            | 3047h                       | [b136128b47](https://linux-hardware.org/?probe=b136128b47) | Aug 15, 2023 |
| Lenovo        | 1036 SDK0Q40104 WIN 3305... | [4ac83eed41](https://linux-hardware.org/?probe=4ac83eed41) | Aug 15, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [12c4ed323e](https://linux-hardware.org/?probe=12c4ed323e) | Aug 15, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO II     | [6e7b731daa](https://linux-hardware.org/?probe=6e7b731daa) | Aug 15, 2023 |
| Medion        | MS-7800                     | [afab92f1e4](https://linux-hardware.org/?probe=afab92f1e4) | Aug 14, 2023 |
| MSI           | H510M PRO                   | [df350cd466](https://linux-hardware.org/?probe=df350cd466) | Aug 14, 2023 |
| Lenovo        | 1046 SBB1C50531 WIN 3556... | [f24668bfd7](https://linux-hardware.org/?probe=f24668bfd7) | Aug 14, 2023 |
| Acer          | Veriton X2640G V:1.0        | [f4ba515a8d](https://linux-hardware.org/?probe=f4ba515a8d) | Aug 14, 2023 |
| Acer          | Veriton X2640G V:1.0        | [2473d1c807](https://linux-hardware.org/?probe=2473d1c807) | Aug 14, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [d2ccdc066b](https://linux-hardware.org/?probe=d2ccdc066b) | Aug 14, 2023 |
| Gigabyte      | Z77M-D3H-MVP                | [c939a92f1d](https://linux-hardware.org/?probe=c939a92f1d) | Aug 14, 2023 |
| Gigabyte      | Z77M-D3H-MVP                | [56efab026f](https://linux-hardware.org/?probe=56efab026f) | Aug 14, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [cc343d2dce](https://linux-hardware.org/?probe=cc343d2dce) | Aug 14, 2023 |
| ASUSTek       | PRIME B550M-A               | [361ad7057c](https://linux-hardware.org/?probe=361ad7057c) | Aug 13, 2023 |
| MSI           | X99A RAIDER                 | [88056b62e3](https://linux-hardware.org/?probe=88056b62e3) | Aug 13, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [45cb1198bb](https://linux-hardware.org/?probe=45cb1198bb) | Aug 13, 2023 |
| HP            | 0B4Ch D                     | [b718d1c1f8](https://linux-hardware.org/?probe=b718d1c1f8) | Aug 13, 2023 |
| HP            | 3646h                       | [b3c30163f9](https://linux-hardware.org/?probe=b3c30163f9) | Aug 13, 2023 |
| HP            | 3646h                       | [180d25235f](https://linux-hardware.org/?probe=180d25235f) | Aug 13, 2023 |
| ASUSTek       | Z97-PRO GAMER               | [25a3921b74](https://linux-hardware.org/?probe=25a3921b74) | Aug 13, 2023 |
| ASRock        | H55M-LE                     | [3751d5807e](https://linux-hardware.org/?probe=3751d5807e) | Aug 12, 2023 |
| Gigabyte      | X670E AORUS MASTER          | [57a63573fc](https://linux-hardware.org/?probe=57a63573fc) | Aug 12, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [22690b9d65](https://linux-hardware.org/?probe=22690b9d65) | Aug 12, 2023 |
| MSI           | X99A RAIDER                 | [90816726b0](https://linux-hardware.org/?probe=90816726b0) | Aug 12, 2023 |
| MSI           | PRO Z790-P WIFI             | [5b9aef438f](https://linux-hardware.org/?probe=5b9aef438f) | Aug 12, 2023 |
| MSI           | PRO Z790-P WIFI             | [1f3f8a869b](https://linux-hardware.org/?probe=1f3f8a869b) | Aug 12, 2023 |
| Gigabyte      | Z170-HD3P-CF                | [7ef87af541](https://linux-hardware.org/?probe=7ef87af541) | Aug 12, 2023 |
| ASUSTek       | PRIME A520M-E               | [92f4e14369](https://linux-hardware.org/?probe=92f4e14369) | Aug 11, 2023 |
| MSI           | MAG B650M MORTAR WIFI       | [d4b93affe2](https://linux-hardware.org/?probe=d4b93affe2) | Aug 11, 2023 |
| MSI           | MAG B650M MORTAR WIFI       | [7a8e32eb89](https://linux-hardware.org/?probe=7a8e32eb89) | Aug 11, 2023 |
| Unknown       | Unknown                     | [4b174f07d2](https://linux-hardware.org/?probe=4b174f07d2) | Aug 11, 2023 |
| Lenovo        | IdeaCentre B320             | [175fb6f041](https://linux-hardware.org/?probe=175fb6f041) | Aug 11, 2023 |
| Gigabyte      | Z170N-WIFI-CF               | [2ee88f0ec0](https://linux-hardware.org/?probe=2ee88f0ec0) | Aug 11, 2023 |
| MSI           | X99A RAIDER                 | [ee1a7cb0aa](https://linux-hardware.org/?probe=ee1a7cb0aa) | Aug 11, 2023 |
| ASUSTek       | P8Z68-V LE                  | [a88d7e81e5](https://linux-hardware.org/?probe=a88d7e81e5) | Aug 11, 2023 |
| ASUSTek       | PRIME B550M-A               | [7da6954bc5](https://linux-hardware.org/?probe=7da6954bc5) | Aug 10, 2023 |
| Dell          | 0MGK50 A01                  | [ac0ed4109e](https://linux-hardware.org/?probe=ac0ed4109e) | Aug 10, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [c5491b8e9f](https://linux-hardware.org/?probe=c5491b8e9f) | Aug 10, 2023 |
| Unknown       | Unknown                     | [09037ac346](https://linux-hardware.org/?probe=09037ac346) | Aug 09, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [466419add0](https://linux-hardware.org/?probe=466419add0) | Aug 09, 2023 |
| Huanan        | X99-TF-Q GAMING V1.2        | [da612198cc](https://linux-hardware.org/?probe=da612198cc) | Aug 09, 2023 |
| Unknown       | HX90                        | [7a14bb927e](https://linux-hardware.org/?probe=7a14bb927e) | Aug 09, 2023 |
| ASRock        | AB350 Pro4                  | [1aa926149a](https://linux-hardware.org/?probe=1aa926149a) | Aug 09, 2023 |
| Dell          | 06CJMN A00                  | [cead9bd601](https://linux-hardware.org/?probe=cead9bd601) | Aug 09, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | [ee7bcf8fe1](https://linux-hardware.org/?probe=ee7bcf8fe1) | Aug 08, 2023 |
| MSI           | B450 GAMING PLUS            | [c8553cabce](https://linux-hardware.org/?probe=c8553cabce) | Aug 08, 2023 |
| Gigabyte      | H510M S2H                   | [72eb04ca17](https://linux-hardware.org/?probe=72eb04ca17) | Aug 08, 2023 |
| MSI           | Z170A GAMING M9 ACK         | [8839aa58c4](https://linux-hardware.org/?probe=8839aa58c4) | Aug 08, 2023 |
| HP            | 3397                        | [d7edc80c00](https://linux-hardware.org/?probe=d7edc80c00) | Aug 08, 2023 |
| ASUSTek       | PHOENIX                     | [388bcf4158](https://linux-hardware.org/?probe=388bcf4158) | Aug 08, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | [ee8f18e185](https://linux-hardware.org/?probe=ee8f18e185) | Aug 07, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [04e63e59bd](https://linux-hardware.org/?probe=04e63e59bd) | Aug 07, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [3d4073bb1d](https://linux-hardware.org/?probe=3d4073bb1d) | Aug 07, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [c3df1aaae9](https://linux-hardware.org/?probe=c3df1aaae9) | Aug 06, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | [c003e20331](https://linux-hardware.org/?probe=c003e20331) | Aug 06, 2023 |
| ASRock        | X470 Taichi                 | [f9d29dca0d](https://linux-hardware.org/?probe=f9d29dca0d) | Aug 06, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [932391bfea](https://linux-hardware.org/?probe=932391bfea) | Aug 06, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [8add0a69cc](https://linux-hardware.org/?probe=8add0a69cc) | Aug 05, 2023 |
| Gateway       | SX2185                      | [a6df16b355](https://linux-hardware.org/?probe=a6df16b355) | Aug 05, 2023 |
| ASUSTek       | Z97-K                       | [4c1ef04fe9](https://linux-hardware.org/?probe=4c1ef04fe9) | Aug 05, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [40bc2f506a](https://linux-hardware.org/?probe=40bc2f506a) | Aug 05, 2023 |
| MSI           | X99A RAIDER                 | [87fc943eb1](https://linux-hardware.org/?probe=87fc943eb1) | Aug 05, 2023 |
| ASUSTek       | PRIME B450M-A               | [d2d45c853b](https://linux-hardware.org/?probe=d2d45c853b) | Aug 05, 2023 |
| ASUSTek       | PRIME B450M-A               | [f18b2ff744](https://linux-hardware.org/?probe=f18b2ff744) | Aug 05, 2023 |
| ASUSTek       | PRIME B550M-A               | [364b15d850](https://linux-hardware.org/?probe=364b15d850) | Aug 05, 2023 |
| Intel         | B75                         | [9411dd987c](https://linux-hardware.org/?probe=9411dd987c) | Aug 05, 2023 |
| ASUSTek       | PHOENIX                     | [193262b7ea](https://linux-hardware.org/?probe=193262b7ea) | Aug 05, 2023 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | [5dc4c594ea](https://linux-hardware.org/?probe=5dc4c594ea) | Aug 05, 2023 |
| ASUSTek       | PRIME B350M-A               | [9a4f9f590c](https://linux-hardware.org/?probe=9a4f9f590c) | Aug 04, 2023 |
| MSI           | PRO H610M-G WIFI DDR4       | [d8b172537e](https://linux-hardware.org/?probe=d8b172537e) | Aug 04, 2023 |
| AZW           | GTR V02                     | [b2afc2c53e](https://linux-hardware.org/?probe=b2afc2c53e) | Aug 04, 2023 |
| Gigabyte      | GA-MA785G-UD3H              | [a02f0405a3](https://linux-hardware.org/?probe=a02f0405a3) | Aug 04, 2023 |
| Dell          | 05XGC8 A01                  | [de1c7d119e](https://linux-hardware.org/?probe=de1c7d119e) | Aug 04, 2023 |
| MSI           | X99A RAIDER                 | [4077d11575](https://linux-hardware.org/?probe=4077d11575) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO S      | [a260479012](https://linux-hardware.org/?probe=a260479012) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [3c3d90d709](https://linux-hardware.org/?probe=3c3d90d709) | Aug 04, 2023 |
| ASUSTek       | PRIME B550M-A               | [c0a4bb6c7e](https://linux-hardware.org/?probe=c0a4bb6c7e) | Aug 03, 2023 |
| Gigabyte      | Z68P-DS3                    | [aa6b646b24](https://linux-hardware.org/?probe=aa6b646b24) | Aug 03, 2023 |
| HP            | 1791                        | [61285d3724](https://linux-hardware.org/?probe=61285d3724) | Aug 03, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | [2d10ecdff1](https://linux-hardware.org/?probe=2d10ecdff1) | Aug 03, 2023 |
| ASUSTek       | PRIME Z270-P                | [219278bb56](https://linux-hardware.org/?probe=219278bb56) | Aug 03, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | [a449d60316](https://linux-hardware.org/?probe=a449d60316) | Aug 03, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [3f5df1b569](https://linux-hardware.org/?probe=3f5df1b569) | Aug 03, 2023 |
| ASRock        | Z170 Gaming K4              | [2c10cb0378](https://linux-hardware.org/?probe=2c10cb0378) | Aug 02, 2023 |
| Gigabyte      | B450M DS3H-CF               | [c66b1ed22c](https://linux-hardware.org/?probe=c66b1ed22c) | Aug 02, 2023 |
| MSI           | B560M PRO-E                 | [b10154befd](https://linux-hardware.org/?probe=b10154befd) | Aug 02, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [883a115efd](https://linux-hardware.org/?probe=883a115efd) | Aug 02, 2023 |
| Gigabyte      | H410M H V3                  | [2d1e78ec7e](https://linux-hardware.org/?probe=2d1e78ec7e) | Aug 02, 2023 |
| ASRock        | B450M Pro4 R2.0             | [5bbfe225b6](https://linux-hardware.org/?probe=5bbfe225b6) | Aug 02, 2023 |
| ASUSTek       | ROG Maximus XII APEX        | [b8a5aee838](https://linux-hardware.org/?probe=b8a5aee838) | Aug 02, 2023 |
| ASRock        | A320M-HDV R4.0              | [2ff30156cf](https://linux-hardware.org/?probe=2ff30156cf) | Aug 02, 2023 |
| ASRock        | B450M Pro4 R2.0             | [8c9bca1e79](https://linux-hardware.org/?probe=8c9bca1e79) | Aug 02, 2023 |
| MSI           | B450M BAZOOKA V2            | [f37f2f707b](https://linux-hardware.org/?probe=f37f2f707b) | Aug 02, 2023 |
| Gigabyte      | B550 GAMING X V2            | [8353d48977](https://linux-hardware.org/?probe=8353d48977) | Aug 01, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | [abe7173905](https://linux-hardware.org/?probe=abe7173905) | Aug 01, 2023 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [13d25503d7](https://linux-hardware.org/?probe=13d25503d7) | Aug 01, 2023 |
| ASRock        | H61M/U3S3                   | [33c887e577](https://linux-hardware.org/?probe=33c887e577) | Aug 01, 2023 |
| Unknown       | Unknown                     | [7a5ef06c39](https://linux-hardware.org/?probe=7a5ef06c39) | Aug 01, 2023 |
| ASUSTek       | PRIME B350M-A               | [41cc0d3bfc](https://linux-hardware.org/?probe=41cc0d3bfc) | Aug 01, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [afbf5d75c1](https://linux-hardware.org/?probe=afbf5d75c1) | Jul 31, 2023 |
| ASRock        | H110M-HG4                   | [7584e2db20](https://linux-hardware.org/?probe=7584e2db20) | Jul 31, 2023 |
| MSI           | B450M PRO-VDH MAX           | [a7cf8e8ef1](https://linux-hardware.org/?probe=a7cf8e8ef1) | Jul 31, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [a3bbf1ecd0](https://linux-hardware.org/?probe=a3bbf1ecd0) | Jul 31, 2023 |
| Gigabyte      | GA-880GM-UD2H               | [bb88f3afdc](https://linux-hardware.org/?probe=bb88f3afdc) | Jul 31, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS        | [7890c76098](https://linux-hardware.org/?probe=7890c76098) | Jul 31, 2023 |
| HP            | 8056                        | [3a98a11778](https://linux-hardware.org/?probe=3a98a11778) | Jul 30, 2023 |
| HP            | 0AECh D                     | [50c84d005e](https://linux-hardware.org/?probe=50c84d005e) | Jul 30, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | [6bf2e91f31](https://linux-hardware.org/?probe=6bf2e91f31) | Jul 30, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | [0f9accc3e8](https://linux-hardware.org/?probe=0f9accc3e8) | Jul 30, 2023 |
| HP            | 8617                        | [0c3ee28cd8](https://linux-hardware.org/?probe=0c3ee28cd8) | Jul 30, 2023 |
| MSI           | Z87-G45 GAMING              | [6c5528a787](https://linux-hardware.org/?probe=6c5528a787) | Jul 30, 2023 |
| Gigabyte      | H77N-WIFI                   | [4fb6a46f65](https://linux-hardware.org/?probe=4fb6a46f65) | Jul 30, 2023 |
| ASRock        | X570 Phantom Gaming X       | [df34eb4472](https://linux-hardware.org/?probe=df34eb4472) | Jul 30, 2023 |
| MSI           | A320M PRO-VH PLUS           | [f5cc7a2d00](https://linux-hardware.org/?probe=f5cc7a2d00) | Jul 30, 2023 |
| ASRock        | X570 Phantom Gaming X       | [0449350f3d](https://linux-hardware.org/?probe=0449350f3d) | Jul 30, 2023 |
| MSI           | MPG X570S EDGE MAX WIFI     | [9469c1037c](https://linux-hardware.org/?probe=9469c1037c) | Jul 29, 2023 |
| ASUSTek       | M4A89TD PRO USB3            | [bcfe09b617](https://linux-hardware.org/?probe=bcfe09b617) | Jul 29, 2023 |
| HP            | 3397                        | [98e4e362d9](https://linux-hardware.org/?probe=98e4e362d9) | Jul 29, 2023 |
| ECS           | H61H2-M17                   | [360623689a](https://linux-hardware.org/?probe=360623689a) | Jul 29, 2023 |
| ASUSTek       | H110M-D                     | [9669adfa57](https://linux-hardware.org/?probe=9669adfa57) | Jul 29, 2023 |
| ECS           | H61H2-M17                   | [aa0f0813e4](https://linux-hardware.org/?probe=aa0f0813e4) | Jul 29, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | [580c4fb755](https://linux-hardware.org/?probe=580c4fb755) | Jul 29, 2023 |
| MSI           | A520M-A PRO                 | [733695ae93](https://linux-hardware.org/?probe=733695ae93) | Jul 29, 2023 |
| MSI           | A320M PRO-VH                | [0728a96775](https://linux-hardware.org/?probe=0728a96775) | Jul 29, 2023 |
| ASRock        | H110M-HG4                   | [205f3a047f](https://linux-hardware.org/?probe=205f3a047f) | Jul 28, 2023 |
| Gigabyte      | B550 GAMING X V2            | [dcd24dfdc7](https://linux-hardware.org/?probe=dcd24dfdc7) | Jul 28, 2023 |
| ASUSTek       | PRIME X570-P                | [fa1452d305](https://linux-hardware.org/?probe=fa1452d305) | Jul 28, 2023 |
| ASUSTek       | WS C246 PRO                 | [cfffc2ba92](https://linux-hardware.org/?probe=cfffc2ba92) | Jul 28, 2023 |
| Gigabyte      | B550M DS3H AC               | [2e0e88694a](https://linux-hardware.org/?probe=2e0e88694a) | Jul 28, 2023 |
| Gigabyte      | J1900M-D2P                  | [7864dbf54c](https://linux-hardware.org/?probe=7864dbf54c) | Jul 28, 2023 |
| Gigabyte      | B550M DS3H AC               | [f7c6565b62](https://linux-hardware.org/?probe=f7c6565b62) | Jul 28, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [49daa98623](https://linux-hardware.org/?probe=49daa98623) | Jul 28, 2023 |
| MSI           | Z270 GAMING PLUS            | [cc489fad92](https://linux-hardware.org/?probe=cc489fad92) | Jul 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [e46fa3639e](https://linux-hardware.org/?probe=e46fa3639e) | Jul 27, 2023 |
| Gigabyte      | H77N-WIFI                   | [abf0e5979c](https://linux-hardware.org/?probe=abf0e5979c) | Jul 27, 2023 |
| ASUSTek       | PHOENIX                     | [aad7b03818](https://linux-hardware.org/?probe=aad7b03818) | Jul 27, 2023 |
| ASUSTek       | PRIME B550M-A               | [02cf19407b](https://linux-hardware.org/?probe=02cf19407b) | Jul 26, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [aed4f431ec](https://linux-hardware.org/?probe=aed4f431ec) | Jul 26, 2023 |
| Lenovo        | SDK0E50510 WIN              | [f375185ce4](https://linux-hardware.org/?probe=f375185ce4) | Jul 26, 2023 |
| MSI           | X99A RAIDER                 | [9b1ae569c1](https://linux-hardware.org/?probe=9b1ae569c1) | Jul 26, 2023 |
| MSI           | A520M-A PRO                 | [b731684f10](https://linux-hardware.org/?probe=b731684f10) | Jul 25, 2023 |
| Gigabyte      | B365M H                     | [12902831a7](https://linux-hardware.org/?probe=12902831a7) | Jul 25, 2023 |
| Gigabyte      | J1900M-D2P                  | [31b7924358](https://linux-hardware.org/?probe=31b7924358) | Jul 25, 2023 |
| ASUSTek       | PRIME B550M-A               | [0ecaae8a05](https://linux-hardware.org/?probe=0ecaae8a05) | Jul 25, 2023 |
| MSI           | X99A RAIDER                 | [7ee6422d01](https://linux-hardware.org/?probe=7ee6422d01) | Jul 25, 2023 |
| Unknown       | Unknown                     | [a7d120e20a](https://linux-hardware.org/?probe=a7d120e20a) | Jul 24, 2023 |
| ASUSTek       | PHOENIX                     | [66ab03991c](https://linux-hardware.org/?probe=66ab03991c) | Jul 24, 2023 |
| Gigabyte      | B75M-D2V                    | [60b9e2fbc9](https://linux-hardware.org/?probe=60b9e2fbc9) | Jul 24, 2023 |
| ASUSTek       | PRIME B550M-A               | [b892c011a8](https://linux-hardware.org/?probe=b892c011a8) | Jul 24, 2023 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | [2afa2c2afe](https://linux-hardware.org/?probe=2afa2c2afe) | Jul 23, 2023 |
| Gigabyte      | H510M S2H V2                | [95290b34e3](https://linux-hardware.org/?probe=95290b34e3) | Jul 23, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | [e1f3c75353](https://linux-hardware.org/?probe=e1f3c75353) | Jul 23, 2023 |
| MSI           | Z170A SLI PLUS              | [a3ccd7aece](https://linux-hardware.org/?probe=a3ccd7aece) | Jul 23, 2023 |
| Gigabyte      | B550M DS3H                  | [04982390e0](https://linux-hardware.org/?probe=04982390e0) | Jul 23, 2023 |
| Gigabyte      | B550M DS3H                  | [b13bb2310f](https://linux-hardware.org/?probe=b13bb2310f) | Jul 23, 2023 |
| Gigabyte      | H61MS                       | [545d840e2f](https://linux-hardware.org/?probe=545d840e2f) | Jul 23, 2023 |
| ASUSTek       | PRIME Z370-A                | [9a2136d9ef](https://linux-hardware.org/?probe=9a2136d9ef) | Jul 23, 2023 |
| Gigabyte      | B360M D2V                   | [eef08e2598](https://linux-hardware.org/?probe=eef08e2598) | Jul 22, 2023 |
| Dell          | 06D7TR A00                  | [b957598d8e](https://linux-hardware.org/?probe=b957598d8e) | Jul 22, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [51ca7593a6](https://linux-hardware.org/?probe=51ca7593a6) | Jul 22, 2023 |
| Kllisre       | X99-B5 V1.1                 | [b132b3f39c](https://linux-hardware.org/?probe=b132b3f39c) | Jul 21, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [8c79a454ff](https://linux-hardware.org/?probe=8c79a454ff) | Jul 21, 2023 |
| MACHINIST     | E5-D8-MAX V1.1              | [ea68d9762b](https://linux-hardware.org/?probe=ea68d9762b) | Jul 21, 2023 |
| Shenzhen M... | HX90G                       | [355ac636c1](https://linux-hardware.org/?probe=355ac636c1) | Jul 21, 2023 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | [e8249dc6d6](https://linux-hardware.org/?probe=e8249dc6d6) | Jul 21, 2023 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | [37132be6bd](https://linux-hardware.org/?probe=37132be6bd) | Jul 21, 2023 |
| MSI           | A320M PRO-VH PLUS           | [689b191bae](https://linux-hardware.org/?probe=689b191bae) | Jul 21, 2023 |
| MSI           | PRO B550-VC                 | [5439295c30](https://linux-hardware.org/?probe=5439295c30) | Jul 20, 2023 |
| Dell          | 00010C A00                  | [71eca6ee4c](https://linux-hardware.org/?probe=71eca6ee4c) | Jul 20, 2023 |
| ASUSTek       | PRIME Z270-P                | [e9c650988e](https://linux-hardware.org/?probe=e9c650988e) | Jul 20, 2023 |
| ASRock        | B450M Pro4 R2.0             | [b3a1dbc5d0](https://linux-hardware.org/?probe=b3a1dbc5d0) | Jul 19, 2023 |
| MSI           | B450M MORTAR MAX            | [22bbaa5937](https://linux-hardware.org/?probe=22bbaa5937) | Jul 19, 2023 |
| ASUSTek       | TUF B360-PLUS GAMING        | [173929b667](https://linux-hardware.org/?probe=173929b667) | Jul 19, 2023 |
| Dell          | 0MN1TX A01                  | [696072cf7c](https://linux-hardware.org/?probe=696072cf7c) | Jul 18, 2023 |
| LattePanda    | 3 Delta LP-BS-7-S70JR120... | [0296e5fd5c](https://linux-hardware.org/?probe=0296e5fd5c) | Jul 18, 2023 |
| Gigabyte      | Z270XP-SLI-CF               | [14478a9226](https://linux-hardware.org/?probe=14478a9226) | Jul 18, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [3618885533](https://linux-hardware.org/?probe=3618885533) | Jul 18, 2023 |
| Gigabyte      | B450M GAMING                | [d0fff20fb0](https://linux-hardware.org/?probe=d0fff20fb0) | Jul 18, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | [d2c6c9bcba](https://linux-hardware.org/?probe=d2c6c9bcba) | Jul 18, 2023 |
| ASUSTek       | M11AD                       | [4019d4eb57](https://linux-hardware.org/?probe=4019d4eb57) | Jul 18, 2023 |
| MSI           | IONA                        | [7b8b6c38e1](https://linux-hardware.org/?probe=7b8b6c38e1) | Jul 18, 2023 |
| ASRock        | X570M Pro4                  | [bb84df2364](https://linux-hardware.org/?probe=bb84df2364) | Jul 18, 2023 |
| ASRock        | X570M Pro4                  | [b8caf7c9a3](https://linux-hardware.org/?probe=b8caf7c9a3) | Jul 18, 2023 |
| HP            | 3048h                       | [ad7b0d8c8d](https://linux-hardware.org/?probe=ad7b0d8c8d) | Jul 17, 2023 |
| Gigabyte      | B550 GAMING X V2            | [60d7a077dc](https://linux-hardware.org/?probe=60d7a077dc) | Jul 17, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [62238aaf82](https://linux-hardware.org/?probe=62238aaf82) | Jul 17, 2023 |
| ASRock        | H510M-HDV/M.2               | [4c07b0b74c](https://linux-hardware.org/?probe=4c07b0b74c) | Jul 17, 2023 |
| ASUSTek       | Maximus VIII HERO           | [49e298a314](https://linux-hardware.org/?probe=49e298a314) | Jul 17, 2023 |
| ASUSTek       | Maximus VIII HERO           | [d8595efd58](https://linux-hardware.org/?probe=d8595efd58) | Jul 17, 2023 |
| ASRock        | B450M Pro4 R2.0             | [6039e0f3c4](https://linux-hardware.org/?probe=6039e0f3c4) | Jul 17, 2023 |
| Dell          | 0WMJ54 A01                  | [07161141b4](https://linux-hardware.org/?probe=07161141b4) | Jul 16, 2023 |
| MSI           | PRO B650-P WIFI             | [65afe9f74b](https://linux-hardware.org/?probe=65afe9f74b) | Jul 16, 2023 |
| MSI           | 2A9C                        | [eaaf1d2a5a](https://linux-hardware.org/?probe=eaaf1d2a5a) | Jul 16, 2023 |
| HP            | ProLiant ML110 G7           | [2278b34727](https://linux-hardware.org/?probe=2278b34727) | Jul 16, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | [5bf40815d5](https://linux-hardware.org/?probe=5bf40815d5) | Jul 16, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [b7992c5de7](https://linux-hardware.org/?probe=b7992c5de7) | Jul 16, 2023 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | [3becbb23af](https://linux-hardware.org/?probe=3becbb23af) | Jul 15, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [14bae4d3e7](https://linux-hardware.org/?probe=14bae4d3e7) | Jul 15, 2023 |
| Gateway       | SX2185                      | [1fe932f485](https://linux-hardware.org/?probe=1fe932f485) | Jul 15, 2023 |
| Gateway       | SX2185                      | [00e7bb0f9f](https://linux-hardware.org/?probe=00e7bb0f9f) | Jul 15, 2023 |
| ASRock        | X670E Steel Legend          | [f25464fb37](https://linux-hardware.org/?probe=f25464fb37) | Jul 15, 2023 |
| ASUSTek       | A88XM-A                     | [c58d69659f](https://linux-hardware.org/?probe=c58d69659f) | Jul 14, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [4e78c933e4](https://linux-hardware.org/?probe=4e78c933e4) | Jul 14, 2023 |
| ASUSTek       | A88XM-A                     | [e34b3f4c71](https://linux-hardware.org/?probe=e34b3f4c71) | Jul 14, 2023 |
| ASUSTek       | PRIME B365M-A               | [62099e9da7](https://linux-hardware.org/?probe=62099e9da7) | Jul 14, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [065aed3358](https://linux-hardware.org/?probe=065aed3358) | Jul 14, 2023 |
| ASUSTek       | PRIME B550M-A AC            | [ed49c9c5e0](https://linux-hardware.org/?probe=ed49c9c5e0) | Jul 14, 2023 |
| ASUSTek       | X99-DELUXE II               | [d132761a85](https://linux-hardware.org/?probe=d132761a85) | Jul 14, 2023 |
| ASUSTek       | X99-DELUXE II               | [70345fff08](https://linux-hardware.org/?probe=70345fff08) | Jul 14, 2023 |
| MSI           | MPG Z690 EDGE WIFI DDR4     | [96921926b1](https://linux-hardware.org/?probe=96921926b1) | Jul 14, 2023 |
| Gigabyte      | H77N-WIFI                   | [8ee665fb8f](https://linux-hardware.org/?probe=8ee665fb8f) | Jul 14, 2023 |
| GALAX         | A320M G10g                  | [730e46d4f0](https://linux-hardware.org/?probe=730e46d4f0) | Jul 14, 2023 |
| Gigabyte      | P75-D3P                     | [0a7c65caae](https://linux-hardware.org/?probe=0a7c65caae) | Jul 13, 2023 |
| ASUSTek       | PRIME X570-P                | [ab0a96405e](https://linux-hardware.org/?probe=ab0a96405e) | Jul 13, 2023 |
| Gigabyte      | GA-A55M-S2V                 | [fadd5eeba6](https://linux-hardware.org/?probe=fadd5eeba6) | Jul 13, 2023 |
| Dell          | 0GY6Y8 A01                  | [144711a0e0](https://linux-hardware.org/?probe=144711a0e0) | Jul 13, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [cd3de89b97](https://linux-hardware.org/?probe=cd3de89b97) | Jul 12, 2023 |
| MSI           | MAG B550M BAZOOKA           | [4271ad9e9b](https://linux-hardware.org/?probe=4271ad9e9b) | Jul 12, 2023 |
| MSI           | 970A-G46                    | [09496b3221](https://linux-hardware.org/?probe=09496b3221) | Jul 12, 2023 |
| MSI           | A320M PRO-VH PLUS           | [e99992afd5](https://linux-hardware.org/?probe=e99992afd5) | Jul 12, 2023 |
| ASRock        | B550M Pro4                  | [18a8fc202c](https://linux-hardware.org/?probe=18a8fc202c) | Jul 12, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [30d6b8bfde](https://linux-hardware.org/?probe=30d6b8bfde) | Jul 11, 2023 |
| MSI           | B350M MORTAR                | [069cf3a06d](https://linux-hardware.org/?probe=069cf3a06d) | Jul 11, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [5c12592f23](https://linux-hardware.org/?probe=5c12592f23) | Jul 11, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [2b544082c2](https://linux-hardware.org/?probe=2b544082c2) | Jul 11, 2023 |
| Gigabyte      | J1900M-D2P                  | [a9e19d3887](https://linux-hardware.org/?probe=a9e19d3887) | Jul 11, 2023 |
| Pegatron      | IPMH61P1                    | [9aa934f232](https://linux-hardware.org/?probe=9aa934f232) | Jul 11, 2023 |
| ASUSTek       | PRIME B250M-D               | [304630d909](https://linux-hardware.org/?probe=304630d909) | Jul 11, 2023 |
| Gigabyte      | B75M-D2V                    | [2749c7cf78](https://linux-hardware.org/?probe=2749c7cf78) | Jul 11, 2023 |
| Pegatron      | 2AD5                        | [04c6c9ba2b](https://linux-hardware.org/?probe=04c6c9ba2b) | Jul 10, 2023 |
| ASUSTek       | PRIME X470-PRO              | [eca6eabcb2](https://linux-hardware.org/?probe=eca6eabcb2) | Jul 10, 2023 |
| Gigabyte      | Z77MX-D3H                   | [ac8df9628d](https://linux-hardware.org/?probe=ac8df9628d) | Jul 10, 2023 |
| MSI           | MEG Z390 GODLIKE            | [b904121800](https://linux-hardware.org/?probe=b904121800) | Jul 10, 2023 |
| MSI           | MPG B650I EDGE WIFI         | [dcf418007d](https://linux-hardware.org/?probe=dcf418007d) | Jul 10, 2023 |
| MSI           | MPG B650I EDGE WIFI         | [b515a2980e](https://linux-hardware.org/?probe=b515a2980e) | Jul 10, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [a2f3950062](https://linux-hardware.org/?probe=a2f3950062) | Jul 10, 2023 |
| GALAX         | A320M G10g                  | [8ab8387585](https://linux-hardware.org/?probe=8ab8387585) | Jul 10, 2023 |
| MSI           | B450M-A PRO MAX             | [ceccedafbd](https://linux-hardware.org/?probe=ceccedafbd) | Jul 10, 2023 |
| ASUSTek       | PHOENIX                     | [88c02f40e7](https://linux-hardware.org/?probe=88c02f40e7) | Jul 09, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [c09e539c94](https://linux-hardware.org/?probe=c09e539c94) | Jul 09, 2023 |
| MSI           | MEG Z390 GODLIKE            | [9a2170442d](https://linux-hardware.org/?probe=9a2170442d) | Jul 09, 2023 |
| Gigabyte      | B365M DS3H WIFI             | [150b2a2675](https://linux-hardware.org/?probe=150b2a2675) | Jul 09, 2023 |
| Gigabyte      | B365M DS3H WIFI             | [a887a01dd7](https://linux-hardware.org/?probe=a887a01dd7) | Jul 09, 2023 |
| ASUSTek       | PRIME H310M-K               | [e7c0c87a14](https://linux-hardware.org/?probe=e7c0c87a14) | Jul 09, 2023 |
| Lenovo        | SHARKBAY NOK                | [fbeae7b57e](https://linux-hardware.org/?probe=fbeae7b57e) | Jul 09, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [d9880a123f](https://linux-hardware.org/?probe=d9880a123f) | Jul 09, 2023 |
| MSI           | PRO B650-P WIFI             | [7d98a62bcc](https://linux-hardware.org/?probe=7d98a62bcc) | Jul 09, 2023 |
| MSI           | B250M PRO-VD                | [f9c2ea463a](https://linux-hardware.org/?probe=f9c2ea463a) | Jul 09, 2023 |
| Dell          | 00F82W A00                  | [603d370b5c](https://linux-hardware.org/?probe=603d370b5c) | Jul 09, 2023 |
| MSI           | Z97 GUARD-PRO               | [298da90a40](https://linux-hardware.org/?probe=298da90a40) | Jul 09, 2023 |
| MSI           | X99A RAIDER                 | [30658f7ab7](https://linux-hardware.org/?probe=30658f7ab7) | Jul 09, 2023 |
| MSI           | PRO Z690-A DDR4             | [f8aa10b5cb](https://linux-hardware.org/?probe=f8aa10b5cb) | Jul 08, 2023 |
| MSI           | PRO Z690-A DDR4             | [1027217195](https://linux-hardware.org/?probe=1027217195) | Jul 08, 2023 |
| ECS           | P43T-AD3                    | [bdbd07c719](https://linux-hardware.org/?probe=bdbd07c719) | Jul 08, 2023 |
| GALAX         | A320M G10g                  | [21dab37c75](https://linux-hardware.org/?probe=21dab37c75) | Jul 08, 2023 |
| HP            | 0AECh D                     | [c3d2867e48](https://linux-hardware.org/?probe=c3d2867e48) | Jul 08, 2023 |
| ASRock        | X670E Pro RS                | [d41838c540](https://linux-hardware.org/?probe=d41838c540) | Jul 08, 2023 |
| Gigabyte      | GA-A55M-S2V                 | [6cac69cac1](https://linux-hardware.org/?probe=6cac69cac1) | Jul 08, 2023 |
| MSI           | X99A RAIDER                 | [f86f946540](https://linux-hardware.org/?probe=f86f946540) | Jul 08, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [4bcab5adb1](https://linux-hardware.org/?probe=4bcab5adb1) | Jul 08, 2023 |
| MSI           | MPG B650I EDGE WIFI         | [bdaa09e52c](https://linux-hardware.org/?probe=bdaa09e52c) | Jul 08, 2023 |
| ASUSTek       | PRIME B550M-A               | [09c80a40ac](https://linux-hardware.org/?probe=09c80a40ac) | Jul 07, 2023 |
| ASUSTek       | PHOENIX                     | [f12b531ae3](https://linux-hardware.org/?probe=f12b531ae3) | Jul 07, 2023 |
| Gigabyte      | H170-HD3-CF                 | [f2203ae88e](https://linux-hardware.org/?probe=f2203ae88e) | Jul 07, 2023 |
| Gigabyte      | H170-HD3-CF                 | [e2adf09ecf](https://linux-hardware.org/?probe=e2adf09ecf) | Jul 07, 2023 |
| ASUSTek       | PHOENIX                     | [cc54a5a0bf](https://linux-hardware.org/?probe=cc54a5a0bf) | Jul 07, 2023 |
| HP            | 3397                        | [45bc734b0b](https://linux-hardware.org/?probe=45bc734b0b) | Jul 07, 2023 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | [bdf5ce2163](https://linux-hardware.org/?probe=bdf5ce2163) | Jul 07, 2023 |
| ASRock        | Z370 Professional Gaming... | [9101223f5e](https://linux-hardware.org/?probe=9101223f5e) | Jul 07, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | [2eb6b1bb05](https://linux-hardware.org/?probe=2eb6b1bb05) | Jul 07, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [4068c56cd3](https://linux-hardware.org/?probe=4068c56cd3) | Jul 07, 2023 |
| Dell          | 0KRC95 A02                  | [5d0d505ca1](https://linux-hardware.org/?probe=5d0d505ca1) | Jul 07, 2023 |
| Gigabyte      | X570 AORUS PRO              | [2802b7951e](https://linux-hardware.org/?probe=2802b7951e) | Jul 06, 2023 |
| MSI           | MS-7142                     | [3247a2f71c](https://linux-hardware.org/?probe=3247a2f71c) | Jul 06, 2023 |
| MSI           | H510M PRO-E                 | [598f789eb0](https://linux-hardware.org/?probe=598f789eb0) | Jul 06, 2023 |
| Gigabyte      | X399 AORUS PRO-CF           | [4122f6e73c](https://linux-hardware.org/?probe=4122f6e73c) | Jul 06, 2023 |
| HP            | 82FE 11                     | [fcac934bde](https://linux-hardware.org/?probe=fcac934bde) | Jul 06, 2023 |
| AZW           | U59                         | [0b59408438](https://linux-hardware.org/?probe=0b59408438) | Jul 06, 2023 |
| MSI           | B150 GAMING M3              | [a8018be55a](https://linux-hardware.org/?probe=a8018be55a) | Jul 06, 2023 |
| Dell          | 06D7TR A00                  | [27f1fe9389](https://linux-hardware.org/?probe=27f1fe9389) | Jul 06, 2023 |
| ASUSTek       | A8R32-MVP Deluxe            | [3af1e33a01](https://linux-hardware.org/?probe=3af1e33a01) | Jul 06, 2023 |
| Gigabyte      | Z87X-UD5H-CF                | [ed520a330d](https://linux-hardware.org/?probe=ed520a330d) | Jul 06, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | [a98b1d131d](https://linux-hardware.org/?probe=a98b1d131d) | Jul 06, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | [eb913300f2](https://linux-hardware.org/?probe=eb913300f2) | Jul 06, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [dd020d65e5](https://linux-hardware.org/?probe=dd020d65e5) | Jul 05, 2023 |
| HP            | 304Ah                       | [029412ce85](https://linux-hardware.org/?probe=029412ce85) | Jul 05, 2023 |
| Gigabyte      | B660M DS3H DDR4             | [c997aced4e](https://linux-hardware.org/?probe=c997aced4e) | Jul 05, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [06b0f38502](https://linux-hardware.org/?probe=06b0f38502) | Jul 05, 2023 |
| ASUSTek       | PRIME H310M-K               | [65cc87f2f0](https://linux-hardware.org/?probe=65cc87f2f0) | Jul 05, 2023 |
| Shenzhen M... | F7BFC                       | [bb708e03aa](https://linux-hardware.org/?probe=bb708e03aa) | Jul 05, 2023 |
| Gigabyte      | 970A-DS3P                   | [50edacf233](https://linux-hardware.org/?probe=50edacf233) | Jul 05, 2023 |
| ASUSTek       | CROSSBLADE RANGER           | [d816bd723e](https://linux-hardware.org/?probe=d816bd723e) | Jul 05, 2023 |
| Lenovo        | 30D0 SDK0J40700 WIN 3258... | [2bb5ca7ea2](https://linux-hardware.org/?probe=2bb5ca7ea2) | Jul 05, 2023 |
| Gigabyte      | P85-D3                      | [6b4a40a1db](https://linux-hardware.org/?probe=6b4a40a1db) | Jul 04, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [fea629b2e8](https://linux-hardware.org/?probe=fea629b2e8) | Jul 04, 2023 |
| HP            | 212B                        | [5c022be621](https://linux-hardware.org/?probe=5c022be621) | Jul 04, 2023 |
| ASUSTek       | SABERTOOTH P67              | [7acafd9528](https://linux-hardware.org/?probe=7acafd9528) | Jul 04, 2023 |
| Gigabyte      | G41MT-D3                    | [da0ca66579](https://linux-hardware.org/?probe=da0ca66579) | Jul 04, 2023 |
| ASUSTek       | H110M-E/M.2                 | [234c36d2ba](https://linux-hardware.org/?probe=234c36d2ba) | Jul 04, 2023 |
| MSI           | PRO Z690-A DDR4             | [d36574de10](https://linux-hardware.org/?probe=d36574de10) | Jul 03, 2023 |
| Kupi deshe... | X99Z-V102 Date 27052020     | [0cdbbfe5b3](https://linux-hardware.org/?probe=0cdbbfe5b3) | Jul 03, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [293008463e](https://linux-hardware.org/?probe=293008463e) | Jul 03, 2023 |
| MSI           | Z170A KRAIT GAMING          | [4bede9ff31](https://linux-hardware.org/?probe=4bede9ff31) | Jul 03, 2023 |
| HP            | 861A                        | [0531675f82](https://linux-hardware.org/?probe=0531675f82) | Jul 03, 2023 |
| ASUSTek       | PRIME B550M-A               | [dc77810d67](https://linux-hardware.org/?probe=dc77810d67) | Jul 03, 2023 |
| MSI           | A320M PRO-VH PLUS           | [a7c8848746](https://linux-hardware.org/?probe=a7c8848746) | Jul 03, 2023 |
| MSI           | X99A RAIDER                 | [40ca2e97cc](https://linux-hardware.org/?probe=40ca2e97cc) | Jul 03, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [bdbf0fa0c3](https://linux-hardware.org/?probe=bdbf0fa0c3) | Jul 03, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [590efa4873](https://linux-hardware.org/?probe=590efa4873) | Jul 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [a6ceaae01b](https://linux-hardware.org/?probe=a6ceaae01b) | Jul 02, 2023 |
| ASRock        | Z87 Extreme6                | [d69ea1a2cb](https://linux-hardware.org/?probe=d69ea1a2cb) | Jul 02, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [69c34bf001](https://linux-hardware.org/?probe=69c34bf001) | Jul 02, 2023 |
| ASUSTek       | X99-M WS                    | [4f9ad96681](https://linux-hardware.org/?probe=4f9ad96681) | Jul 02, 2023 |
| AZW           | MINI S                      | [fb96f8d7bf](https://linux-hardware.org/?probe=fb96f8d7bf) | Jul 02, 2023 |
| ASUSTek       | PRIME B550M-A               | [740a0dad30](https://linux-hardware.org/?probe=740a0dad30) | Jul 02, 2023 |
| Gigabyte      | X570 AORUS PRO              | [0a9e5c0979](https://linux-hardware.org/?probe=0a9e5c0979) | Jul 02, 2023 |
| MSI           | X99A RAIDER                 | [c2b529a2ee](https://linux-hardware.org/?probe=c2b529a2ee) | Jul 02, 2023 |
| Gigabyte      | A320M-S2H-CF                | [d0ab54293f](https://linux-hardware.org/?probe=d0ab54293f) | Jul 02, 2023 |
| ASRock        | B560M-ITX/ac                | [4c5f8f3d95](https://linux-hardware.org/?probe=4c5f8f3d95) | Jul 01, 2023 |
| ASRock        | A620M Pro RS WiFi           | [f771aedc9c](https://linux-hardware.org/?probe=f771aedc9c) | Jul 01, 2023 |
| HP            | 8061                        | [429534fab2](https://linux-hardware.org/?probe=429534fab2) | Jul 01, 2023 |
| HP            | 8054                        | [30c45def21](https://linux-hardware.org/?probe=30c45def21) | Jul 01, 2023 |
| HP            | 8054                        | [edf94b1f66](https://linux-hardware.org/?probe=edf94b1f66) | Jul 01, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | [6c1829f43d](https://linux-hardware.org/?probe=6c1829f43d) | Jul 01, 2023 |
| ASUSTek       | PRIME B550M-A               | [246d688f1c](https://linux-hardware.org/?probe=246d688f1c) | Jul 01, 2023 |
| MSI           | MPG Z390M GAMING EDGE AC    | [cfdff3114c](https://linux-hardware.org/?probe=cfdff3114c) | Jul 01, 2023 |
| MSI           | X99A RAIDER                 | [d7efa66a54](https://linux-hardware.org/?probe=d7efa66a54) | Jul 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | [8ea4c888cf](https://linux-hardware.org/?probe=8ea4c888cf) | Jul 01, 2023 |
| Gigabyte      | H410M S2H V3                | [e539937c27](https://linux-hardware.org/?probe=e539937c27) | Jun 30, 2023 |
| Acer          | Predator PO5-640            | [416b01c954](https://linux-hardware.org/?probe=416b01c954) | Jun 30, 2023 |
| Gigabyte      | Z87X-UD5H-CF                | [3749bda51b](https://linux-hardware.org/?probe=3749bda51b) | Jun 30, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [3c3556dd33](https://linux-hardware.org/?probe=3c3556dd33) | Jun 30, 2023 |
| Gigabyte      | Z87X-UD5H-CF                | [6ee8476c0e](https://linux-hardware.org/?probe=6ee8476c0e) | Jun 30, 2023 |
| ASRock        | FM2A88X Extreme6+           | [77e6b09eb9](https://linux-hardware.org/?probe=77e6b09eb9) | Jun 30, 2023 |
| MSI           | X99A RAIDER                 | [bb8a8eac46](https://linux-hardware.org/?probe=bb8a8eac46) | Jun 30, 2023 |
| AZW           | MINI S 10                   | [84eec8c276](https://linux-hardware.org/?probe=84eec8c276) | Jun 29, 2023 |
| AZW           | MINI S 10                   | [d1795fbf64](https://linux-hardware.org/?probe=d1795fbf64) | Jun 29, 2023 |
| Gigabyte      | H310M H                     | [0ad496c06d](https://linux-hardware.org/?probe=0ad496c06d) | Jun 29, 2023 |
| Gigabyte      | H410M H V3                  | [5496b9130e](https://linux-hardware.org/?probe=5496b9130e) | Jun 29, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [95fb20193a](https://linux-hardware.org/?probe=95fb20193a) | Jun 29, 2023 |
| ASUSTek       | PRIME B550M-A               | [5bb4af3f8b](https://linux-hardware.org/?probe=5bb4af3f8b) | Jun 29, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [08708e8e9d](https://linux-hardware.org/?probe=08708e8e9d) | Jun 28, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | [3f9d0da410](https://linux-hardware.org/?probe=3f9d0da410) | Jun 28, 2023 |
| Gigabyte      | B560M DS3H V2               | [aa24aa071b](https://linux-hardware.org/?probe=aa24aa071b) | Jun 28, 2023 |
| MSI           | 880GM-E41                   | [91a2474332](https://linux-hardware.org/?probe=91a2474332) | Jun 28, 2023 |
| Fill By OE... | Q7700                       | [93c7c01ecb](https://linux-hardware.org/?probe=93c7c01ecb) | Jun 28, 2023 |
| ASRock        | H510M-HVS                   | [b90f532588](https://linux-hardware.org/?probe=b90f532588) | Jun 28, 2023 |
| HP            | 802F                        | [585f9bf338](https://linux-hardware.org/?probe=585f9bf338) | Jun 27, 2023 |
| HP            | 802F                        | [efceba0028](https://linux-hardware.org/?probe=efceba0028) | Jun 27, 2023 |
| Intel         | LADPNVMO AAE76523-300       | [76cc7bbb86](https://linux-hardware.org/?probe=76cc7bbb86) | Jun 27, 2023 |
| Fill By OE... | Q7700                       | [32ac9cb839](https://linux-hardware.org/?probe=32ac9cb839) | Jun 27, 2023 |
| Dell          | 0R6PCT A01                  | [2fd7aa28db](https://linux-hardware.org/?probe=2fd7aa28db) | Jun 27, 2023 |
| Gigabyte      | B450M DS3H-CF               | [b21d5b2e0a](https://linux-hardware.org/?probe=b21d5b2e0a) | Jun 26, 2023 |
| Gigabyte      | MZBAYAB-00                  | [a44397603c](https://linux-hardware.org/?probe=a44397603c) | Jun 26, 2023 |
| ASRock        | FM2A88X Extreme6+           | [a974c1b82e](https://linux-hardware.org/?probe=a974c1b82e) | Jun 26, 2023 |
| MSI           | X99A RAIDER                 | [31fc00f1ac](https://linux-hardware.org/?probe=31fc00f1ac) | Jun 26, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [3486e43434](https://linux-hardware.org/?probe=3486e43434) | Jun 25, 2023 |
| ASRock        | FM2A88X Extreme6+           | [1c648f1f3e](https://linux-hardware.org/?probe=1c648f1f3e) | Jun 25, 2023 |
| MSI           | X99A RAIDER                 | [684000f2c5](https://linux-hardware.org/?probe=684000f2c5) | Jun 25, 2023 |
| Gigabyte      | H110M-H-CF                  | [7baa53c127](https://linux-hardware.org/?probe=7baa53c127) | Jun 25, 2023 |
| ASUSTek       | P9X79 PRO                   | [3d1eeda7fa](https://linux-hardware.org/?probe=3d1eeda7fa) | Jun 24, 2023 |
| Dell          | 088DT1 A01                  | [755d1f8c03](https://linux-hardware.org/?probe=755d1f8c03) | Jun 24, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [1c0d2d86f3](https://linux-hardware.org/?probe=1c0d2d86f3) | Jun 24, 2023 |
| ASUSTek       | P8Z77-V LK                  | [bcfc1fe2de](https://linux-hardware.org/?probe=bcfc1fe2de) | Jun 23, 2023 |
| ASRock        | B450 Pro4                   | [a5f281a10e](https://linux-hardware.org/?probe=a5f281a10e) | Jun 23, 2023 |
| ASUSTek       | M4A77                       | [67e6b51c63](https://linux-hardware.org/?probe=67e6b51c63) | Jun 23, 2023 |
| MSI           | B450M PRO-M2 V2             | [af46eedb6f](https://linux-hardware.org/?probe=af46eedb6f) | Jun 23, 2023 |
| ASUSTek       | PRIME B350M-A               | [efb0264470](https://linux-hardware.org/?probe=efb0264470) | Jun 23, 2023 |
| ASUSTek       | Maximus VIII RANGER Modi... | [d24120bc4e](https://linux-hardware.org/?probe=d24120bc4e) | Jun 22, 2023 |
| MSI           | PRO B550M-VC WIFI           | [c9f86c15b7](https://linux-hardware.org/?probe=c9f86c15b7) | Jun 22, 2023 |
| Lenovo        | ThinkServer TS140           | [5043d686d8](https://linux-hardware.org/?probe=5043d686d8) | Jun 22, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [b07361bc89](https://linux-hardware.org/?probe=b07361bc89) | Jun 22, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [52bcb712ec](https://linux-hardware.org/?probe=52bcb712ec) | Jun 22, 2023 |
| Lenovo        | SHARKBAY NOK                | [c0f250b2f9](https://linux-hardware.org/?probe=c0f250b2f9) | Jun 22, 2023 |
| Unknown       | Unknown                     | [172c84a53d](https://linux-hardware.org/?probe=172c84a53d) | Jun 22, 2023 |
| Dell          | 09KPNV A01                  | [eaa3017d03](https://linux-hardware.org/?probe=eaa3017d03) | Jun 21, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [30f85c0f2e](https://linux-hardware.org/?probe=30f85c0f2e) | Jun 21, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [fd367d0725](https://linux-hardware.org/?probe=fd367d0725) | Jun 21, 2023 |
| ASUSTek       | PRIME B550M-A               | [a5e833c54e](https://linux-hardware.org/?probe=a5e833c54e) | Jun 21, 2023 |
| ASUSTek       | Z87-A                       | [ca84827c75](https://linux-hardware.org/?probe=ca84827c75) | Jun 21, 2023 |
| ASUSTek       | Z87-A                       | [a30c01fab8](https://linux-hardware.org/?probe=a30c01fab8) | Jun 21, 2023 |
| ASUSTek       | TUF B360-PRO GAMING WIFI    | [52e2d1b77a](https://linux-hardware.org/?probe=52e2d1b77a) | Jun 21, 2023 |
| Pegatron      | IPMIP-H55-INSPUR            | [176a1c3e01](https://linux-hardware.org/?probe=176a1c3e01) | Jun 21, 2023 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [a1e0b61e89](https://linux-hardware.org/?probe=a1e0b61e89) | Jun 20, 2023 |
| MSI           | X570-A PRO                  | [b968cb073e](https://linux-hardware.org/?probe=b968cb073e) | Jun 20, 2023 |
| ASUSTek       | Rampage V EXTREME           | [e7bb42d6d4](https://linux-hardware.org/?probe=e7bb42d6d4) | Jun 20, 2023 |
| ASUSTek       | Rampage V EXTREME           | [2fe4bf8ad2](https://linux-hardware.org/?probe=2fe4bf8ad2) | Jun 20, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [b154e92f35](https://linux-hardware.org/?probe=b154e92f35) | Jun 20, 2023 |
| MSI           | B75MA-P45                   | [2d8b92b0e6](https://linux-hardware.org/?probe=2d8b92b0e6) | Jun 20, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [ee8a4e18c4](https://linux-hardware.org/?probe=ee8a4e18c4) | Jun 20, 2023 |
| Gigabyte      | MZBAYAB-00                  | [5864261490](https://linux-hardware.org/?probe=5864261490) | Jun 20, 2023 |
| Itautec       | ST 4265 ST-4265 Padrao 0... | [689b10e4be](https://linux-hardware.org/?probe=689b10e4be) | Jun 19, 2023 |
| Gigabyte      | B365M D2V                   | [e16cbf315f](https://linux-hardware.org/?probe=e16cbf315f) | Jun 19, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [b3e34f06a4](https://linux-hardware.org/?probe=b3e34f06a4) | Jun 19, 2023 |
| Gigabyte      | GA-MA785G-UD3H              | [e5740353af](https://linux-hardware.org/?probe=e5740353af) | Jun 19, 2023 |
| Dell          | 0C2XKD A01                  | [15331b91ed](https://linux-hardware.org/?probe=15331b91ed) | Jun 18, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | [5ff46d41fd](https://linux-hardware.org/?probe=5ff46d41fd) | Jun 18, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [924b6e8d54](https://linux-hardware.org/?probe=924b6e8d54) | Jun 18, 2023 |
| Lenovo        | SHARKBAY NOK                | [73a438e6b8](https://linux-hardware.org/?probe=73a438e6b8) | Jun 18, 2023 |
| MSI           | X470 GAMING PLUS            | [17c61c0aee](https://linux-hardware.org/?probe=17c61c0aee) | Jun 18, 2023 |
| Intel         | DG965RY AAD41691-301        | [3f18a24757](https://linux-hardware.org/?probe=3f18a24757) | Jun 18, 2023 |
| Gigabyte      | GA-880GM-UD2H               | [fdbe50b1d6](https://linux-hardware.org/?probe=fdbe50b1d6) | Jun 18, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [231a3aeb2e](https://linux-hardware.org/?probe=231a3aeb2e) | Jun 18, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [cd87a6b19f](https://linux-hardware.org/?probe=cd87a6b19f) | Jun 17, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [ae4661e26f](https://linux-hardware.org/?probe=ae4661e26f) | Jun 17, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E EXTR... | [c555238190](https://linux-hardware.org/?probe=c555238190) | Jun 17, 2023 |
| ASUSTek       | PRIME B550M-A               | [7e135be518](https://linux-hardware.org/?probe=7e135be518) | Jun 17, 2023 |
| Huanan        | X99-ZD4 V2.0                | [be1f0f151e](https://linux-hardware.org/?probe=be1f0f151e) | Jun 16, 2023 |
| ASUSTek       | ROG ZENITH EXTREME          | [5dc49896e5](https://linux-hardware.org/?probe=5dc49896e5) | Jun 16, 2023 |
| MSI           | B85-G43 GAMING              | [93da970965](https://linux-hardware.org/?probe=93da970965) | Jun 16, 2023 |
| HP            | 212B                        | [134ff203c4](https://linux-hardware.org/?probe=134ff203c4) | Jun 16, 2023 |
| MSI           | B450 GAMING PLUS            | [8a480175f8](https://linux-hardware.org/?probe=8a480175f8) | Jun 16, 2023 |
| ASUSTek       | ROG STRIX B550-XE GAMING... | [84b103464e](https://linux-hardware.org/?probe=84b103464e) | Jun 16, 2023 |
| MSI           | B450M MORTAR TITANIUM       | [3b83e2ea48](https://linux-hardware.org/?probe=3b83e2ea48) | Jun 16, 2023 |
| MSI           | B450 GAMING PLUS            | [8a3d74a5fa](https://linux-hardware.org/?probe=8a3d74a5fa) | Jun 16, 2023 |
| ASRock        | X399 Phantom Gaming 6       | [aad3ead710](https://linux-hardware.org/?probe=aad3ead710) | Jun 16, 2023 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | [9c3bb21706](https://linux-hardware.org/?probe=9c3bb21706) | Jun 16, 2023 |
| ASUSTek       | A8R32-MVP Deluxe            | [29ff056f4a](https://linux-hardware.org/?probe=29ff056f4a) | Jun 16, 2023 |
| MSI           | Z170A GAMING M5             | [a0d460b4a3](https://linux-hardware.org/?probe=a0d460b4a3) | Jun 16, 2023 |
| Gigabyte      | H97-HD3                     | [24a487274f](https://linux-hardware.org/?probe=24a487274f) | Jun 16, 2023 |
| MSI           | MAG B550M MORTAR            | [9604c6211e](https://linux-hardware.org/?probe=9604c6211e) | Jun 15, 2023 |
| Itautec       | ST 4265 ST-4265 Padrao 0... | [ecc8c7d2d0](https://linux-hardware.org/?probe=ecc8c7d2d0) | Jun 15, 2023 |
| Itautec       | ST 4265 ST-4265 Padrao 0... | [4cad282848](https://linux-hardware.org/?probe=4cad282848) | Jun 15, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [5a1e944af2](https://linux-hardware.org/?probe=5a1e944af2) | Jun 15, 2023 |
| MSI           | PRO B550M-VC WIFI           | [64e0ce279b](https://linux-hardware.org/?probe=64e0ce279b) | Jun 15, 2023 |
| HP            | 212B                        | [b107461bdd](https://linux-hardware.org/?probe=b107461bdd) | Jun 14, 2023 |
| Gigabyte      | B85M-D3V-A                  | [bbcb31d079](https://linux-hardware.org/?probe=bbcb31d079) | Jun 14, 2023 |
| ASUSTek       | P5G41C-M LX                 | [7ae654d4e2](https://linux-hardware.org/?probe=7ae654d4e2) | Jun 14, 2023 |
| Kllisre       | X99-B5 V1.1                 | [5e22a31b3e](https://linux-hardware.org/?probe=5e22a31b3e) | Jun 14, 2023 |
| Gigabyte      | D525TUD                     | [2d854be38a](https://linux-hardware.org/?probe=2d854be38a) | Jun 14, 2023 |
| ECS           | H61H2-M17                   | [63ded73edb](https://linux-hardware.org/?probe=63ded73edb) | Jun 14, 2023 |
| Dell          | 0KRC95 A02                  | [5f9a1aafe0](https://linux-hardware.org/?probe=5f9a1aafe0) | Jun 14, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [ddb9fc5a43](https://linux-hardware.org/?probe=ddb9fc5a43) | Jun 14, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [4fac659113](https://linux-hardware.org/?probe=4fac659113) | Jun 13, 2023 |
| MSI           | H510M PRO                   | [08e44766fe](https://linux-hardware.org/?probe=08e44766fe) | Jun 13, 2023 |
| ECS           | H61H2-M17                   | [fb57cc3ed4](https://linux-hardware.org/?probe=fb57cc3ed4) | Jun 13, 2023 |
| MSI           | IONA                        | [86535af79b](https://linux-hardware.org/?probe=86535af79b) | Jun 13, 2023 |
| Gigabyte      | D525TUD                     | [be2c796ab2](https://linux-hardware.org/?probe=be2c796ab2) | Jun 13, 2023 |
| MSI           | Z77A-G45                    | [db1a941e2c](https://linux-hardware.org/?probe=db1a941e2c) | Jun 13, 2023 |
| Gigabyte      | A520M DS3H                  | [0f5b161a60](https://linux-hardware.org/?probe=0f5b161a60) | Jun 13, 2023 |
| ASUSTek       | P5G41C-M LX                 | [1361d3551c](https://linux-hardware.org/?probe=1361d3551c) | Jun 12, 2023 |
| Gigabyte      | B560M DS3H V2               | [1b8ad811e0](https://linux-hardware.org/?probe=1b8ad811e0) | Jun 12, 2023 |
| ASRock        | Z390 Pro4                   | [067d0e5da5](https://linux-hardware.org/?probe=067d0e5da5) | Jun 12, 2023 |
| Shenzhen M... | F7BFD                       | [8f43ad0e76](https://linux-hardware.org/?probe=8f43ad0e76) | Jun 12, 2023 |
| ASUSTek       | PRIME H310M-K               | [f1614bb08f](https://linux-hardware.org/?probe=f1614bb08f) | Jun 11, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [cf9274f969](https://linux-hardware.org/?probe=cf9274f969) | Jun 11, 2023 |
| ASUSTek       | PRIME Z270-P                | [57fcd66521](https://linux-hardware.org/?probe=57fcd66521) | Jun 11, 2023 |
| ASUSTek       | P9X79 PRO                   | [a280f19bb2](https://linux-hardware.org/?probe=a280f19bb2) | Jun 11, 2023 |
| MSI           | PRO Z790-A WIFI DDR4        | [0e3bbb5b14](https://linux-hardware.org/?probe=0e3bbb5b14) | Jun 11, 2023 |
| MSI           | X99A RAIDER                 | [1fd265b6d8](https://linux-hardware.org/?probe=1fd265b6d8) | Jun 11, 2023 |
| ASRock        | FM2A88X Extreme6+           | [1c5e1b092a](https://linux-hardware.org/?probe=1c5e1b092a) | Jun 11, 2023 |
| MSI           | PRO B660M-A DDR4            | [e3311e26b6](https://linux-hardware.org/?probe=e3311e26b6) | Jun 11, 2023 |
| Gigabyte      | Z87X-UD4H-CF                | [abd31d2f92](https://linux-hardware.org/?probe=abd31d2f92) | Jun 10, 2023 |
| Lenovo        | 32E9 SDK0T76465 WIN 3422... | [2ac8db1b4c](https://linux-hardware.org/?probe=2ac8db1b4c) | Jun 10, 2023 |
| Dell          | 0N4YC8 A00                  | [bc832400b4](https://linux-hardware.org/?probe=bc832400b4) | Jun 10, 2023 |
| MSI           | MS-7388                     | [6d3a406400](https://linux-hardware.org/?probe=6d3a406400) | Jun 10, 2023 |
| MSI           | X99A RAIDER                 | [4ab556e4b8](https://linux-hardware.org/?probe=4ab556e4b8) | Jun 10, 2023 |
| ASRock        | FM2A88X Extreme6+           | [212c44c43f](https://linux-hardware.org/?probe=212c44c43f) | Jun 10, 2023 |
| HP            | 339B                        | [bc6de07e07](https://linux-hardware.org/?probe=bc6de07e07) | Jun 09, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [f9677c0861](https://linux-hardware.org/?probe=f9677c0861) | Jun 09, 2023 |
| ASUSTek       | A8R32-MVP Deluxe            | [f02bc23dd0](https://linux-hardware.org/?probe=f02bc23dd0) | Jun 09, 2023 |
| ASRock        | AB350M Pro4                 | [8f0087d741](https://linux-hardware.org/?probe=8f0087d741) | Jun 09, 2023 |
| MSI           | 760GM-P23                   | [abc3a3d8a1](https://linux-hardware.org/?probe=abc3a3d8a1) | Jun 09, 2023 |
| MSI           | 760GM-P23                   | [fc826b3cb1](https://linux-hardware.org/?probe=fc826b3cb1) | Jun 09, 2023 |
| ASUSTek       | STRIX B250F GAMING          | [c0fd33b9cc](https://linux-hardware.org/?probe=c0fd33b9cc) | Jun 09, 2023 |
| ASUSTek       | STRIX B250F GAMING          | [76c3e6625b](https://linux-hardware.org/?probe=76c3e6625b) | Jun 09, 2023 |
| Dell          | 0FDY5C A00                  | [1caf029f79](https://linux-hardware.org/?probe=1caf029f79) | Jun 09, 2023 |
| ASRock        | A320M-HD                    | [9e88454384](https://linux-hardware.org/?probe=9e88454384) | Jun 09, 2023 |
| ASUSTek       | Z97M-PLUS                   | [24f6f6e727](https://linux-hardware.org/?probe=24f6f6e727) | Jun 08, 2023 |
| ASUSTek       | Z97M-PLUS                   | [8d4e2bedde](https://linux-hardware.org/?probe=8d4e2bedde) | Jun 08, 2023 |
| Colorful T... | A520M-K PRO V14             | [48c4aa3d8c](https://linux-hardware.org/?probe=48c4aa3d8c) | Jun 08, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [b9e1c5e320](https://linux-hardware.org/?probe=b9e1c5e320) | Jun 08, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [bf2fc7d3b7](https://linux-hardware.org/?probe=bf2fc7d3b7) | Jun 08, 2023 |
| MSI           | B450M PRO-VDH MAX           | [c96be9f4cd](https://linux-hardware.org/?probe=c96be9f4cd) | Jun 08, 2023 |
| Gigabyte      | B75M-D3H                    | [65e06561cf](https://linux-hardware.org/?probe=65e06561cf) | Jun 08, 2023 |
| Gigabyte      | Z77MX-D3H                   | [e1fdfde650](https://linux-hardware.org/?probe=e1fdfde650) | Jun 08, 2023 |
| HPE           | ProLiant MicroServer Gen... | [e95900bc0c](https://linux-hardware.org/?probe=e95900bc0c) | Jun 08, 2023 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [74f55613b5](https://linux-hardware.org/?probe=74f55613b5) | Jun 08, 2023 |
| Lenovo        | ThinkServer TS140           | [e9ca405eff](https://linux-hardware.org/?probe=e9ca405eff) | Jun 08, 2023 |
| Gigabyte      | Z390 GAMING SLI-CF          | [5f0e8ab63a](https://linux-hardware.org/?probe=5f0e8ab63a) | Jun 07, 2023 |
| Gigabyte      | Z87X-UD5H-CF                | [fd156e669f](https://linux-hardware.org/?probe=fd156e669f) | Jun 07, 2023 |
| Lenovo        | SHARKBAY NOK                | [cf560e91e7](https://linux-hardware.org/?probe=cf560e91e7) | Jun 07, 2023 |
| HP            | 339B                        | [a1739aa36b](https://linux-hardware.org/?probe=a1739aa36b) | Jun 07, 2023 |
| Gigabyte      | H77N-WIFI                   | [1c8078b748](https://linux-hardware.org/?probe=1c8078b748) | Jun 07, 2023 |
| Gigabyte      | B550 VISION D               | [94cf7f5675](https://linux-hardware.org/?probe=94cf7f5675) | Jun 07, 2023 |
| MSI           | B350M GAMING PRO            | [eb3fbddd2c](https://linux-hardware.org/?probe=eb3fbddd2c) | Jun 06, 2023 |
| Gigabyte      | B250-FinTech-CF             | [022138ad16](https://linux-hardware.org/?probe=022138ad16) | Jun 06, 2023 |
| Dell          | 0427JK A00                  | [addb15771e](https://linux-hardware.org/?probe=addb15771e) | Jun 06, 2023 |
| Dell          | 0NW6H5 A00                  | [631e6bba84](https://linux-hardware.org/?probe=631e6bba84) | Jun 06, 2023 |
| Dell          | 06X1TJ A00                  | [c3f02841f4](https://linux-hardware.org/?probe=c3f02841f4) | Jun 06, 2023 |
| Dell          | 06X1TJ A00                  | [4cec4f0517](https://linux-hardware.org/?probe=4cec4f0517) | Jun 06, 2023 |
| HP            | 83E1                        | [227e410c6f](https://linux-hardware.org/?probe=227e410c6f) | Jun 06, 2023 |
| Lenovo        | 30D0 NOK                    | [045b011b7a](https://linux-hardware.org/?probe=045b011b7a) | Jun 06, 2023 |
| MSI           | X99A RAIDER                 | [d70fe31101](https://linux-hardware.org/?probe=d70fe31101) | Jun 06, 2023 |
| ASRock        | FM2A88X Extreme6+           | [3c3708dcec](https://linux-hardware.org/?probe=3c3708dcec) | Jun 06, 2023 |
| HP            | 8918                        | [917b8c425f](https://linux-hardware.org/?probe=917b8c425f) | Jun 06, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [91ee57c108](https://linux-hardware.org/?probe=91ee57c108) | Jun 05, 2023 |
| Gigabyte      | B250-FinTech-CF             | [e22c496628](https://linux-hardware.org/?probe=e22c496628) | Jun 05, 2023 |
| Unknown       | Unknown                     | [292269611c](https://linux-hardware.org/?probe=292269611c) | Jun 05, 2023 |
| ASRock        | FM2A88X Extreme6+           | [79b80daf83](https://linux-hardware.org/?probe=79b80daf83) | Jun 05, 2023 |
| MSI           | X99A RAIDER                 | [36173d5a42](https://linux-hardware.org/?probe=36173d5a42) | Jun 05, 2023 |
| MSI           | B360M PRO-VH                | [8e4ad66edc](https://linux-hardware.org/?probe=8e4ad66edc) | Jun 05, 2023 |
| ASUSTek       | PRIME B350M-A               | [3a0576b177](https://linux-hardware.org/?probe=3a0576b177) | Jun 05, 2023 |
| ASUSTek       | PRIME B550M-A               | [d6befa925e](https://linux-hardware.org/?probe=d6befa925e) | Jun 04, 2023 |
| Dell          | 09D7F7 A00                  | [9b80703b01](https://linux-hardware.org/?probe=9b80703b01) | Jun 04, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [5b35735d26](https://linux-hardware.org/?probe=5b35735d26) | Jun 04, 2023 |
| MSI           | X470 GAMING PLUS            | [7af9263ba9](https://linux-hardware.org/?probe=7af9263ba9) | Jun 04, 2023 |
| MSI           | X470 GAMING PLUS            | [ae24cbf98d](https://linux-hardware.org/?probe=ae24cbf98d) | Jun 04, 2023 |
| Lenovo        | 32E9 SDK0T76465 WIN 3422... | [fa41f1f3c2](https://linux-hardware.org/?probe=fa41f1f3c2) | Jun 04, 2023 |
| Dell          | 0KRC95 A02                  | [3fb87e5a0e](https://linux-hardware.org/?probe=3fb87e5a0e) | Jun 03, 2023 |
| MSI           | A320M PRO-VH PLUS           | [8ba76b1e88](https://linux-hardware.org/?probe=8ba76b1e88) | Jun 03, 2023 |
| MSI           | MAG B550M MORTAR            | [3d911ac9c9](https://linux-hardware.org/?probe=3d911ac9c9) | Jun 03, 2023 |
| Gigabyte      | B650M GAMING X AX           | [610ba5871f](https://linux-hardware.org/?probe=610ba5871f) | Jun 03, 2023 |
| Gigabyte      | Z590 UD AC                  | [da5b2056e4](https://linux-hardware.org/?probe=da5b2056e4) | Jun 02, 2023 |
| ASUSTek       | P8Z77-V LK                  | [d50ca19dc3](https://linux-hardware.org/?probe=d50ca19dc3) | Jun 02, 2023 |
| HP            | 212B                        | [15c4a7b64f](https://linux-hardware.org/?probe=15c4a7b64f) | Jun 02, 2023 |
| Gigabyte      | B85-HD3                     | [9931f8e663](https://linux-hardware.org/?probe=9931f8e663) | Jun 02, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [5562bc75b8](https://linux-hardware.org/?probe=5562bc75b8) | Jun 02, 2023 |
| MSI           | PRO X670-P WIFI             | [714ed7283d](https://linux-hardware.org/?probe=714ed7283d) | Jun 02, 2023 |
| MSI           | PRO X670-P WIFI             | [bb2776b990](https://linux-hardware.org/?probe=bb2776b990) | Jun 02, 2023 |
| MSI           | MS-7388                     | [fc12ac6b90](https://linux-hardware.org/?probe=fc12ac6b90) | Jun 02, 2023 |
| Alienware     | 0N43JM A00                  | [047bfb6e8e](https://linux-hardware.org/?probe=047bfb6e8e) | Jun 02, 2023 |
| Dell          | 04Y8V0 A02                  | [ce749a8df5](https://linux-hardware.org/?probe=ce749a8df5) | Jun 02, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [def2c6020b](https://linux-hardware.org/?probe=def2c6020b) | Jun 01, 2023 |
| ASUSTek       | PRIME X570-P                | [cde4aaef3e](https://linux-hardware.org/?probe=cde4aaef3e) | Jun 01, 2023 |
| Itautec       | ST 4265 ST-4265 Padrao 0... | [7ac5ec7c05](https://linux-hardware.org/?probe=7ac5ec7c05) | Jun 01, 2023 |
| ASRock        | H310M-HDV                   | [3dc5138ecd](https://linux-hardware.org/?probe=3dc5138ecd) | Jun 01, 2023 |
| HP            | 845A                        | [b68054952b](https://linux-hardware.org/?probe=b68054952b) | Jun 01, 2023 |
| Lenovo        | SHARKBAY NOK                | [108cb2ce17](https://linux-hardware.org/?probe=108cb2ce17) | Jun 01, 2023 |
| HP            | 339A                        | [24ab8463bb](https://linux-hardware.org/?probe=24ab8463bb) | Jun 01, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [9afffc17a1](https://linux-hardware.org/?probe=9afffc17a1) | Jun 01, 2023 |
| ASUSTek       | PRIME B550M-A               | [8799da8513](https://linux-hardware.org/?probe=8799da8513) | Jun 01, 2023 |
| Gigabyte      | J1900M-D2P                  | [0e89db7255](https://linux-hardware.org/?probe=0e89db7255) | Jun 01, 2023 |
| MSI           | X99A RAIDER                 | [b951e6223c](https://linux-hardware.org/?probe=b951e6223c) | Jun 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | [df9086deb4](https://linux-hardware.org/?probe=df9086deb4) | Jun 01, 2023 |
| ASUSTek       | PRIME H510M-K               | [f6f91b620c](https://linux-hardware.org/?probe=f6f91b620c) | May 31, 2023 |
| Lenovo        | ThinkServer TS140           | [e8e3834bf8](https://linux-hardware.org/?probe=e8e3834bf8) | May 31, 2023 |
| Lenovo        | ThinkServer TS140           | [48cf9db6cd](https://linux-hardware.org/?probe=48cf9db6cd) | May 31, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [3718997542](https://linux-hardware.org/?probe=3718997542) | May 31, 2023 |
| MSI           | X99A RAIDER                 | [3404cb6c67](https://linux-hardware.org/?probe=3404cb6c67) | May 31, 2023 |
| ASRock        | FM2A88X Extreme6+           | [4a908da319](https://linux-hardware.org/?probe=4a908da319) | May 31, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [ad79be40f5](https://linux-hardware.org/?probe=ad79be40f5) | May 31, 2023 |
| Gigabyte      | B250-FinTech-CF             | [1903d991a3](https://linux-hardware.org/?probe=1903d991a3) | May 30, 2023 |
| Shenzhen M... | F7BFC                       | [c496e8a74f](https://linux-hardware.org/?probe=c496e8a74f) | May 30, 2023 |
| ASUSTek       | PRIME B550M-A               | [349eb108ab](https://linux-hardware.org/?probe=349eb108ab) | May 30, 2023 |
| ASRock        | B450M Steel Legend          | [87c3dbc5df](https://linux-hardware.org/?probe=87c3dbc5df) | May 30, 2023 |
| ASRock        | A320M-DVS R4.0              | [611b47056d](https://linux-hardware.org/?probe=611b47056d) | May 30, 2023 |
| HP            | 8307                        | [c8d0506eda](https://linux-hardware.org/?probe=c8d0506eda) | May 30, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [ffbccb8f47](https://linux-hardware.org/?probe=ffbccb8f47) | May 30, 2023 |
| ASRock        | FM2A88X Extreme6+           | [8b96413dfd](https://linux-hardware.org/?probe=8b96413dfd) | May 30, 2023 |
| MSI           | X99A RAIDER                 | [ffe895debc](https://linux-hardware.org/?probe=ffe895debc) | May 30, 2023 |
| ASRock        | B560M-ITX/ac                | [e643aa0f5d](https://linux-hardware.org/?probe=e643aa0f5d) | May 30, 2023 |
| HP            | 8169                        | [4f10a589e7](https://linux-hardware.org/?probe=4f10a589e7) | May 29, 2023 |
| Itautec       | ST 4265                     | [8814373cb4](https://linux-hardware.org/?probe=8814373cb4) | May 29, 2023 |
| Lenovo        | SHARKBAY NOK                | [a199dc360d](https://linux-hardware.org/?probe=a199dc360d) | May 29, 2023 |
| MSI           | X370 XPOWER GAMING TITAN... | [3ecf79af69](https://linux-hardware.org/?probe=3ecf79af69) | May 29, 2023 |
| Biostar       | H310MHP                     | [7bfe35481d](https://linux-hardware.org/?probe=7bfe35481d) | May 29, 2023 |
| Itautec       | ST 4265                     | [b89c45a31d](https://linux-hardware.org/?probe=b89c45a31d) | May 29, 2023 |
| Gigabyte      | B550M DS3H AC               | [6dca0624e2](https://linux-hardware.org/?probe=6dca0624e2) | May 29, 2023 |
| HP            | 2820h                       | [d326b49f48](https://linux-hardware.org/?probe=d326b49f48) | May 29, 2023 |
| Biostar       | H310MHP                     | [7138f287c8](https://linux-hardware.org/?probe=7138f287c8) | May 29, 2023 |
| MSI           | X99A RAIDER                 | [0b7f7fb99a](https://linux-hardware.org/?probe=0b7f7fb99a) | May 29, 2023 |
| ASRock        | FM2A88X Extreme6+           | [38936854c8](https://linux-hardware.org/?probe=38936854c8) | May 29, 2023 |
| MSI           | B350M GAMING PRO            | [52517395ca](https://linux-hardware.org/?probe=52517395ca) | May 29, 2023 |
| ASUSTek       | PRIME H510M-K               | [0c7bfc7977](https://linux-hardware.org/?probe=0c7bfc7977) | May 28, 2023 |
| HP            | ProLiant ML110 G7           | [fd74c84f0a](https://linux-hardware.org/?probe=fd74c84f0a) | May 28, 2023 |
| ASRock        | B550M Phantom Gaming 4      | [773f0d5242](https://linux-hardware.org/?probe=773f0d5242) | May 28, 2023 |
| Gigabyte      | Z77MX-D3H                   | [3c001962b0](https://linux-hardware.org/?probe=3c001962b0) | May 28, 2023 |
| Dell          | 0W2F8G A00                  | [f5a76aaf01](https://linux-hardware.org/?probe=f5a76aaf01) | May 28, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [4e1ad3c652](https://linux-hardware.org/?probe=4e1ad3c652) | May 28, 2023 |
| Dell          | 0W2F8G A00                  | [419c0c7359](https://linux-hardware.org/?probe=419c0c7359) | May 28, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [db3d362e28](https://linux-hardware.org/?probe=db3d362e28) | May 28, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [94fe283791](https://linux-hardware.org/?probe=94fe283791) | May 28, 2023 |
| Intel         | X99                         | [6826d78921](https://linux-hardware.org/?probe=6826d78921) | May 28, 2023 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | [906e585809](https://linux-hardware.org/?probe=906e585809) | May 27, 2023 |
| Huanan        | X79 249PC V2.2              | [0723379042](https://linux-hardware.org/?probe=0723379042) | May 27, 2023 |
| Huanan        | X79 249PC V2.2              | [ef1a056412](https://linux-hardware.org/?probe=ef1a056412) | May 27, 2023 |
| MSI           | X370 GAMING PRO CARBON A... | [ffbc308836](https://linux-hardware.org/?probe=ffbc308836) | May 27, 2023 |
| HP            | 8307                        | [94cad3911e](https://linux-hardware.org/?probe=94cad3911e) | May 27, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [9a3691f3f2](https://linux-hardware.org/?probe=9a3691f3f2) | May 27, 2023 |
| MSI           | MPG B650I EDGE WIFI         | [8fdbd504af](https://linux-hardware.org/?probe=8fdbd504af) | May 27, 2023 |
| Gigabyte      | P75-D3P                     | [c341cbff1b](https://linux-hardware.org/?probe=c341cbff1b) | May 26, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [ecf6ecb00d](https://linux-hardware.org/?probe=ecf6ecb00d) | May 26, 2023 |
| ASUSTek       | PRIME B550M-A               | [424078f376](https://linux-hardware.org/?probe=424078f376) | May 26, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [16d7a61394](https://linux-hardware.org/?probe=16d7a61394) | May 26, 2023 |
| HP            | 0AECh D                     | [30868178ea](https://linux-hardware.org/?probe=30868178ea) | May 26, 2023 |
| Gigabyte      | J1900M-D2P                  | [f0c2fede02](https://linux-hardware.org/?probe=f0c2fede02) | May 25, 2023 |
| Gigabyte      | B560M AORUS ELITE           | [c2d85ba655](https://linux-hardware.org/?probe=c2d85ba655) | May 25, 2023 |
| Gigabyte      | J1900M-D2P                  | [a167562cba](https://linux-hardware.org/?probe=a167562cba) | May 25, 2023 |
| ASRock        | B450M-HDV R4.0              | [063077bd52](https://linux-hardware.org/?probe=063077bd52) | May 25, 2023 |
| Foxconn       | 2ABF                        | [8472aba19b](https://linux-hardware.org/?probe=8472aba19b) | May 25, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [2c31d88fa2](https://linux-hardware.org/?probe=2c31d88fa2) | May 25, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [efb5aa9bfc](https://linux-hardware.org/?probe=efb5aa9bfc) | May 24, 2023 |
| ASUSTek       | PRIME Z390-P                | [909becff79](https://linux-hardware.org/?probe=909becff79) | May 24, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [d6ec4cc9bc](https://linux-hardware.org/?probe=d6ec4cc9bc) | May 24, 2023 |
| MSI           | 2A9C                        | [acaff65dda](https://linux-hardware.org/?probe=acaff65dda) | May 24, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [bcb5af2775](https://linux-hardware.org/?probe=bcb5af2775) | May 24, 2023 |
| HP            | 8307                        | [6797c02e08](https://linux-hardware.org/?probe=6797c02e08) | May 24, 2023 |
| ASUSTek       | ROG ZENITH EXTREME          | [402231776b](https://linux-hardware.org/?probe=402231776b) | May 23, 2023 |
| Gigabyte      | B250-FinTech-CF             | [d8d33293ef](https://linux-hardware.org/?probe=d8d33293ef) | May 23, 2023 |
| MSI           | B460M PRO                   | [94ce62125f](https://linux-hardware.org/?probe=94ce62125f) | May 23, 2023 |
| HP            | 3647h                       | [fc8cf5c799](https://linux-hardware.org/?probe=fc8cf5c799) | May 23, 2023 |
| ASRock        | B450M Pro4                  | [2d42a4443c](https://linux-hardware.org/?probe=2d42a4443c) | May 23, 2023 |
| ASRock        | FM2A88X Extreme6+           | [ec7d8d12e1](https://linux-hardware.org/?probe=ec7d8d12e1) | May 23, 2023 |
| MSI           | X99A RAIDER                 | [1b7089a58b](https://linux-hardware.org/?probe=1b7089a58b) | May 23, 2023 |
| ASUSTek       | PRIME B550M-A               | [de335816aa](https://linux-hardware.org/?probe=de335816aa) | May 22, 2023 |
| ASRock        | B550 Taichi                 | [175272b7e0](https://linux-hardware.org/?probe=175272b7e0) | May 22, 2023 |
| Gigabyte      | GA-880GM-UD2H               | [e110548f6e](https://linux-hardware.org/?probe=e110548f6e) | May 22, 2023 |
| MSI           | X370 GAMING PRO CARBON A... | [71730fa381](https://linux-hardware.org/?probe=71730fa381) | May 22, 2023 |
| Lenovo        | ThinkCentre M58p 7220A72    | [c2965aff69](https://linux-hardware.org/?probe=c2965aff69) | May 22, 2023 |
| ASUSTek       | PRIME B550M-A               | [63b100e342](https://linux-hardware.org/?probe=63b100e342) | May 22, 2023 |
| MSI           | X99A RAIDER                 | [1fd2d41164](https://linux-hardware.org/?probe=1fd2d41164) | May 22, 2023 |
| ASRock        | FM2A88X Extreme6+           | [ecc77ee7a9](https://linux-hardware.org/?probe=ecc77ee7a9) | May 22, 2023 |
| HP            | 1589                        | [a7d56849a5](https://linux-hardware.org/?probe=a7d56849a5) | May 22, 2023 |
| Unknown       | Unknown                     | [9cc7b8d0a8](https://linux-hardware.org/?probe=9cc7b8d0a8) | May 22, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [94c7ddea69](https://linux-hardware.org/?probe=94c7ddea69) | May 21, 2023 |
| Fujitsu Si... | D2831-S1 S26361-D2831-S1    | [0d2426a070](https://linux-hardware.org/?probe=0d2426a070) | May 21, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [2ae04bd0d4](https://linux-hardware.org/?probe=2ae04bd0d4) | May 21, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [2adc02040e](https://linux-hardware.org/?probe=2adc02040e) | May 21, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [7b5628af0e](https://linux-hardware.org/?probe=7b5628af0e) | May 21, 2023 |
| ASRock        | B550M-ITX/ac                | [b03cb56dfa](https://linux-hardware.org/?probe=b03cb56dfa) | May 21, 2023 |
| ASUSTek       | G10DK                       | [b19380fb21](https://linux-hardware.org/?probe=b19380fb21) | May 21, 2023 |
| Acer          | Aspire XC-705               | [bdd393edd7](https://linux-hardware.org/?probe=bdd393edd7) | May 21, 2023 |
| ASRock        | H310CM-HG4                  | [6f698f47d8](https://linux-hardware.org/?probe=6f698f47d8) | May 21, 2023 |
| ASUSTek       | PRIME Z370-P                | [b3564ca1cf](https://linux-hardware.org/?probe=b3564ca1cf) | May 20, 2023 |
| ASUSTek       | P5B                         | [3effc437bb](https://linux-hardware.org/?probe=3effc437bb) | May 20, 2023 |
| ASRock        | A320M-HD                    | [1a05e80ee5](https://linux-hardware.org/?probe=1a05e80ee5) | May 20, 2023 |
| Gigabyte      | B550M S2H                   | [04dac52364](https://linux-hardware.org/?probe=04dac52364) | May 19, 2023 |
| MSI           | 2A9C                        | [78d54a3ebf](https://linux-hardware.org/?probe=78d54a3ebf) | May 19, 2023 |
| Gigabyte      | H77N-WIFI                   | [b59b0160fb](https://linux-hardware.org/?probe=b59b0160fb) | May 19, 2023 |
| ASRock        | X470 Taichi                 | [a6755db2c4](https://linux-hardware.org/?probe=a6755db2c4) | May 19, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [52bfbb69ee](https://linux-hardware.org/?probe=52bfbb69ee) | May 19, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [6d04bdb08d](https://linux-hardware.org/?probe=6d04bdb08d) | May 19, 2023 |
| Lenovo        | 314F SDK0J40697 WIN 3305... | [ebe436d0b5](https://linux-hardware.org/?probe=ebe436d0b5) | May 18, 2023 |
| ASRock        | B85M-HDS                    | [411344a862](https://linux-hardware.org/?probe=411344a862) | May 18, 2023 |
| ASRock        | B85M-HDS                    | [868d98e4f4](https://linux-hardware.org/?probe=868d98e4f4) | May 18, 2023 |
| Gigabyte      | X99-UD4-CF                  | [0eec4b5bbe](https://linux-hardware.org/?probe=0eec4b5bbe) | May 18, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [b8ed6a8b77](https://linux-hardware.org/?probe=b8ed6a8b77) | May 18, 2023 |
| MSI           | MPG B650I EDGE WIFI         | [c15ff8f4c4](https://linux-hardware.org/?probe=c15ff8f4c4) | May 18, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [4c72848255](https://linux-hardware.org/?probe=4c72848255) | May 18, 2023 |
| Lenovo        | MAHOBAY NOK                 | [a33efd912c](https://linux-hardware.org/?probe=a33efd912c) | May 18, 2023 |
| Gigabyte      | Z790 GAMING X AX            | [09f9f2e231](https://linux-hardware.org/?probe=09f9f2e231) | May 17, 2023 |
| HP            | 3048h                       | [9e65995057](https://linux-hardware.org/?probe=9e65995057) | May 17, 2023 |
| ASUSTek       | M5A97 R2.0                  | [5d77e9825a](https://linux-hardware.org/?probe=5d77e9825a) | May 17, 2023 |
| Gigabyte      | 990FXA-UD3 R5               | [b3e10fd912](https://linux-hardware.org/?probe=b3e10fd912) | May 17, 2023 |
| Dell          | 0D6H9T A00                  | [e4787e9b05](https://linux-hardware.org/?probe=e4787e9b05) | May 17, 2023 |
| ASUSTek       | Leonite2                    | [9c923defd1](https://linux-hardware.org/?probe=9c923defd1) | May 17, 2023 |
| ASUSTek       | PRIME Z490-A                | [c3f3d961bb](https://linux-hardware.org/?probe=c3f3d961bb) | May 17, 2023 |
| ASUSTek       | PRIME Z370-A                | [cf08703fd3](https://linux-hardware.org/?probe=cf08703fd3) | May 17, 2023 |
| ASUSTek       | D700SC                      | [eab212a67d](https://linux-hardware.org/?probe=eab212a67d) | May 17, 2023 |
| HP            | 8055                        | [0efb5c8b5d](https://linux-hardware.org/?probe=0efb5c8b5d) | May 17, 2023 |
| ASUSTek       | PRIME B550M-A               | [d4b209ad20](https://linux-hardware.org/?probe=d4b209ad20) | May 17, 2023 |
| HP            | 8055                        | [d660088965](https://linux-hardware.org/?probe=d660088965) | May 17, 2023 |
| ASRock        | B450M Pro4                  | [c05d5e127e](https://linux-hardware.org/?probe=c05d5e127e) | May 16, 2023 |
| ASUSTek       | TUF Gaming X570-PRO WIFI... | [9b29aafd95](https://linux-hardware.org/?probe=9b29aafd95) | May 16, 2023 |
| Gigabyte      | H170-Gaming 3               | [ae5f06df99](https://linux-hardware.org/?probe=ae5f06df99) | May 16, 2023 |
| MSI           | MAG B560M MORTAR            | [2323128fd2](https://linux-hardware.org/?probe=2323128fd2) | May 16, 2023 |
| iRU           | A231                        | [0b35bba039](https://linux-hardware.org/?probe=0b35bba039) | May 16, 2023 |
| Gigabyte      | GA-990FX-GAMING             | [d7503c22b2](https://linux-hardware.org/?probe=d7503c22b2) | May 16, 2023 |
| Dell          | 09KPNV A01                  | [15b4320ae1](https://linux-hardware.org/?probe=15b4320ae1) | May 16, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [294fe7853f](https://linux-hardware.org/?probe=294fe7853f) | May 15, 2023 |
| Gigabyte      | GA-990FX-GAMING             | [cc42c4e227](https://linux-hardware.org/?probe=cc42c4e227) | May 15, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [4529ae76bb](https://linux-hardware.org/?probe=4529ae76bb) | May 15, 2023 |
| MSI           | H170A PC MATE               | [389ab53539](https://linux-hardware.org/?probe=389ab53539) | May 15, 2023 |
| Gigabyte      | H310M S2H x.x               | [8f36de95ee](https://linux-hardware.org/?probe=8f36de95ee) | May 15, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Fedora/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| Fedora 38 | 722      | 15.18%  |
| Fedora 36 | 689      | 14.48%  |
| Fedora 37 | 607      | 12.76%  |
| Fedora 33 | 567      | 11.92%  |
| Fedora 35 | 535      | 11.25%  |
| Fedora 34 | 518      | 10.89%  |
| Fedora 32 | 518      | 10.89%  |
| Fedora 31 | 343      | 7.21%   |
| Fedora 30 | 132      | 2.77%   |
| Fedora 29 | 75       | 1.58%   |
| Fedora 39 | 15       | 0.32%   |
| Fedora 28 | 14       | 0.29%   |
| Fedora 27 | 9        | 0.19%   |
| Fedora 40 | 5        | 0.11%   |
| Fedora 25 | 2        | 0.04%   |
| Fedora 24 | 2        | 0.04%   |
| Fedora 4  | 1        | 0.02%   |
| Fedora 21 | 1        | 0.02%   |
| Fedora 17 | 1        | 0.02%   |
| Fedora 14 | 1        | 0.02%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Fedora | 4105     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Desktops | Percent |
|-------------------------|----------|---------|
| 6.2.9-300.fc38.x86_64   | 83       | 1.52%   |
| 6.3.8-200.fc38.x86_64   | 71       | 1.3%    |
| 6.2.15-300.fc38.x86_64  | 71       | 1.3%    |
| 6.4.15-200.fc38.x86_64  | 70       | 1.28%   |
| 5.9.16-200.fc33.x86_64  | 58       | 1.06%   |
| 5.16.18-200.fc35.x86_64 | 57       | 1.04%   |
| 5.17.5-300.fc36.x86_64  | 52       | 0.95%   |
| 6.2.14-300.fc38.x86_64  | 48       | 0.88%   |
| 6.0.15-300.fc37.x86_64  | 45       | 0.82%   |
| 6.0.12-300.fc37.x86_64  | 44       | 0.8%    |
| 5.18.13-200.fc36.x86_64 | 42       | 0.77%   |
| 6.3.12-200.fc38.x86_64  | 40       | 0.73%   |
| 5.19.16-200.fc36.x86_64 | 40       | 0.73%   |
| 5.13.12-200.fc34.x86_64 | 39       | 0.71%   |
| 6.4.11-200.fc38.x86_64  | 37       | 0.68%   |
| 6.0.7-301.fc37.x86_64   | 37       | 0.68%   |
| 5.14.10-300.fc35.x86_64 | 37       | 0.68%   |
| 6.0.5-200.fc36.x86_64   | 35       | 0.64%   |
| 5.11.12-300.fc34.x86_64 | 35       | 0.64%   |
| 6.2.11-300.fc38.x86_64  | 33       | 0.6%    |
| 6.1.18-200.fc37.x86_64  | 33       | 0.6%    |
| 5.8.4-200.fc32.x86_64   | 33       | 0.6%    |
| 5.8.15-301.fc33.x86_64  | 33       | 0.6%    |
| 6.3.11-200.fc38.x86_64  | 32       | 0.58%   |
| 5.18.16-200.fc36.x86_64 | 32       | 0.58%   |
| 6.0.11-300.fc37.x86_64  | 31       | 0.57%   |
| 5.19.9-200.fc36.x86_64  | 31       | 0.57%   |
| 5.18.11-200.fc36.x86_64 | 31       | 0.57%   |
| 5.6.19-300.fc32.x86_64  | 30       | 0.55%   |
| 5.18.5-200.fc36.x86_64  | 30       | 0.55%   |
| 5.12.13-300.fc34.x86_64 | 30       | 0.55%   |
| 6.4.6-200.fc38.x86_64   | 29       | 0.53%   |
| 5.8.18-300.fc33.x86_64  | 29       | 0.53%   |
| 5.15.6-200.fc35.x86_64  | 29       | 0.53%   |
| 5.8.16-300.fc33.x86_64  | 28       | 0.51%   |
| 6.0.9-300.fc37.x86_64   | 27       | 0.49%   |
| 6.0.8-300.fc37.x86_64   | 27       | 0.49%   |
| 6.4.12-200.fc38.x86_64  | 26       | 0.47%   |
| 5.9.11-200.fc33.x86_64  | 26       | 0.47%   |
| 5.3.16-300.fc31.x86_64  | 26       | 0.47%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.2.9   | 96       | 1.75%   |
| 6.2.15  | 88       | 1.61%   |
| 6.3.8   | 76       | 1.39%   |
| 6.4.15  | 72       | 1.32%   |
| 5.17.5  | 68       | 1.24%   |
| 5.9.16  | 67       | 1.22%   |
| 5.16.18 | 65       | 1.19%   |
| 6.2.14  | 59       | 1.08%   |
| 5.19.16 | 59       | 1.08%   |
| 6.0.12  | 53       | 0.97%   |
| 5.8.15  | 53       | 0.97%   |
| 6.0.15  | 51       | 0.93%   |
| 6.0.7   | 50       | 0.91%   |
| 5.8.18  | 47       | 0.86%   |
| 6.3.12  | 43       | 0.79%   |
| 5.18.13 | 43       | 0.79%   |
| 5.8.16  | 40       | 0.73%   |
| 5.13.12 | 40       | 0.73%   |
| 6.0.8   | 39       | 0.71%   |
| 5.19.9  | 39       | 0.71%   |
| 5.14.10 | 39       | 0.71%   |
| 6.4.11  | 38       | 0.69%   |
| 6.2.11  | 38       | 0.69%   |
| 6.0.5   | 38       | 0.69%   |
| 6.0.9   | 37       | 0.68%   |
| 5.11.12 | 37       | 0.68%   |
| 5.11.11 | 37       | 0.68%   |
| 6.1.18  | 36       | 0.66%   |
| 5.18.5  | 35       | 0.64%   |
| 6.0.11  | 34       | 0.62%   |
| 5.14.18 | 34       | 0.62%   |
| 5.8.4   | 33       | 0.6%    |
| 5.18.16 | 33       | 0.6%    |
| 6.3.11  | 32       | 0.58%   |
| 5.18.11 | 32       | 0.58%   |
| 5.12.13 | 32       | 0.58%   |
| 5.6.19  | 31       | 0.57%   |
| 6.4.6   | 30       | 0.55%   |
| 6.0.10  | 30       | 0.55%   |
| 5.12.8  | 30       | 0.55%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.2     | 390      | 7.51%   |
| 6.0     | 357      | 6.88%   |
| 5.8     | 307      | 5.91%   |
| 6.4     | 288      | 5.55%   |
| 5.11    | 257      | 4.95%   |
| 5.19    | 256      | 4.93%   |
| 5.18    | 252      | 4.85%   |
| 5.17    | 250      | 4.82%   |
| 6.1     | 242      | 4.66%   |
| 6.3     | 228      | 4.39%   |
| 5.16    | 224      | 4.31%   |
| 5.9     | 209      | 4.03%   |
| 5.10    | 206      | 3.97%   |
| 5.14    | 205      | 3.95%   |
| 5.6     | 195      | 3.76%   |
| 5.13    | 191      | 3.68%   |
| 5.15    | 180      | 3.47%   |
| 5.12    | 176      | 3.39%   |
| 5.7     | 171      | 3.29%   |
| 5.4     | 135      | 2.6%    |
| 5.5     | 121      | 2.33%   |
| 5.3     | 116      | 2.23%   |
| 5.2     | 55       | 1.06%   |
| 5.0     | 48       | 0.92%   |
| 6.5     | 26       | 0.5%    |
| 5.1     | 25       | 0.48%   |
| 4.19    | 22       | 0.42%   |
| 4.18    | 19       | 0.37%   |
| 4.20    | 18       | 0.35%   |
| 4.16    | 5        | 0.1%    |
| 6.6     | 3        | 0.06%   |
| 4.15    | 3        | 0.06%   |
| 4.17    | 2        | 0.04%   |
| 4.13    | 2        | 0.04%   |
| 4.11    | 2        | 0.04%   |
| 4.14    | 1        | 0.02%   |
| 4.1     | 1        | 0.02%   |
| 3.9     | 1        | 0.02%   |
| 3.17    | 1        | 0.02%   |
| 2.6.35  | 1        | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 4101     | 99.88%  |
| i686    | 3        | 0.07%   |
| ppc64le | 1        | 0.02%   |
| Unknown | 1        | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| GNOME                        | 2847     | 67.34%  |
| KDE5                         | 575      | 13.6%   |
| Unknown                      | 276      | 6.53%   |
| KDE                          | 116      | 2.74%   |
| XFCE                         | 101      | 2.39%   |
| X-Cinnamon                   | 77       | 1.82%   |
| Cinnamon                     | 64       | 1.51%   |
| MATE                         | 60       | 1.42%   |
| GNOME Classic                | 32       | 0.76%   |
| LXQt                         | 12       | 0.28%   |
| Deepin                       | 11       | 0.26%   |
| LXDE                         | 10       | 0.24%   |
| i3                           | 8        | 0.19%   |
| sway                         | 6        | 0.14%   |
| KDE4                         | 6        | 0.14%   |
| Budgie                       | 4        | 0.09%   |
| Xpra                         | 3        | 0.07%   |
| openbox                      | 3        | 0.07%   |
| Hyprland                     | 3        | 0.07%   |
| awesome                      | 3        | 0.07%   |
| qtile                        | 2        | 0.05%   |
| DWM                          | 2        | 0.05%   |
| bspwm                        | 2        | 0.05%   |
| Pantheon                     | 1        | 0.02%   |
| NsCDE                        | 1        | 0.02%   |
| GNUstep                      | 1        | 0.02%   |
| GNOME Flashback              | 1        | 0.02%   |
| ${XDG_CURRENT_DESKTOP:-sway} | 1        | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 2318     | 53.82%  |
| X11     | 1695     | 39.35%  |
| Tty     | 149      | 3.46%   |
| Unknown | 140      | 3.25%   |
| Web     | 5        | 0.12%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 2411     | 57.01%  |
| GDM     | 1192     | 28.19%  |
| SDDM    | 341      | 8.06%   |
| LightDM | 195      | 4.61%   |
| TDM     | 73       | 1.73%   |
| XDM     | 7        | 0.17%   |
| KDM     | 7        | 0.17%   |
| LXDM    | 2        | 0.05%   |
| SLiM    | 1        | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 1953     | 46.74%  |
| en_GB   | 285      | 6.82%   |
| Unknown | 250      | 5.98%   |
| ru_RU   | 208      | 4.98%   |
| pt_BR   | 207      | 4.95%   |
| de_DE   | 186      | 4.45%   |
| fr_FR   | 131      | 3.14%   |
| en_CA   | 126      | 3.02%   |
| en_AU   | 126      | 3.02%   |
| it_IT   | 88       | 2.11%   |
| es_ES   | 65       | 1.56%   |
| pl_PL   | 63       | 1.51%   |
| en_IN   | 29       | 0.69%   |
| es_MX   | 27       | 0.65%   |
| cs_CZ   | 26       | 0.62%   |
| es_AR   | 22       | 0.53%   |
| en_NZ   | 22       | 0.53%   |
| es_CO   | 17       | 0.41%   |
| nl_NL   | 16       | 0.38%   |
| ja_JP   | 15       | 0.36%   |
| fi_FI   | 15       | 0.36%   |
| tr_TR   | 14       | 0.34%   |
| nl_BE   | 14       | 0.34%   |
| en_IE   | 14       | 0.34%   |
| de_AT   | 13       | 0.31%   |
| sv_SE   | 12       | 0.29%   |
| hu_HU   | 11       | 0.26%   |
| es_CL   | 11       | 0.26%   |
| C       | 11       | 0.26%   |
| zh_CN   | 10       | 0.24%   |
| uk_UA   | 10       | 0.24%   |
| en_DK   | 10       | 0.24%   |
| ru_UA   | 8        | 0.19%   |
| pt_PT   | 8        | 0.19%   |
| ko_KR   | 8        | 0.19%   |
| fr_CH   | 8        | 0.19%   |
| fr_BE   | 7        | 0.17%   |
| sk_SK   | 6        | 0.14%   |
| fr_CA   | 6        | 0.14%   |
| en_PH   | 6        | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 2698     | 64.67%  |
| BIOS | 1474     | 35.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type                | Desktops | Percent |
|---------------------|----------|---------|
| Btrfs               | 2382     | 56.54%  |
| Ext4                | 1485     | 35.25%  |
| Xfs                 | 194      | 4.6%    |
| Unknown             | 132      | 3.13%   |
| Overlay             | 8        | 0.19%   |
| Ext3                | 5        | 0.12%   |
| Zfs                 | 4        | 0.09%   |
| F2fs                | 2        | 0.05%   |
| Fuse.fuse-overlayfs | 1        | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 2348     | 55.5%   |
| GPT     | 1501     | 35.48%  |
| MBR     | 382      | 9.03%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 3577     | 85.02%  |
| Yes       | 630      | 14.98%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 3316     | 79.39%  |
| Yes       | 861      | 20.61%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 1183     | 28.82%  |
| Gigabyte Technology                  | 799      | 19.46%  |
| MSI                                  | 631      | 15.37%  |
| ASRock                               | 415      | 10.11%  |
| Dell                                 | 289      | 7.04%   |
| Hewlett-Packard                      | 226      | 5.51%   |
| Lenovo                               | 121      | 2.95%   |
| Intel                                | 67       | 1.63%   |
| Unknown                              | 49       | 1.19%   |
| Acer                                 | 42       | 1.02%   |
| Pegatron                             | 24       | 0.58%   |
| Huanan                               | 19       | 0.46%   |
| Biostar                              | 18       | 0.44%   |
| Fujitsu                              | 17       | 0.41%   |
| ECS                                  | 17       | 0.41%   |
| BESSTAR Tech                         | 15       | 0.37%   |
| Foxconn                              | 12       | 0.29%   |
| Supermicro                           | 11       | 0.27%   |
| AZW                                  | 9        | 0.22%   |
| Apple                                | 9        | 0.22%   |
| Alienware                            | 9        | 0.22%   |
| Shuttle                              | 8        | 0.19%   |
| Positivo                             | 8        | 0.19%   |
| Itautec                              | 8        | 0.19%   |
| Medion                               | 6        | 0.15%   |
| PCWare                               | 5        | 0.12%   |
| Packard Bell                         | 5        | 0.12%   |
| System76                             | 4        | 0.1%    |
| MACHINIST                            | 4        | 0.1%    |
| EVGA                                 | 4        | 0.1%    |
| ZOTAC                                | 3        | 0.07%   |
| Shenzhen Meigao Electronic Equipment | 3        | 0.07%   |
| NZXT                                 | 3        | 0.07%   |
| eMachines                            | 3        | 0.07%   |
| AMI                                  | 3        | 0.07%   |
| ABIT                                 | 3        | 0.07%   |
| XFX                                  | 2        | 0.05%   |
| OEM                                  | 2        | 0.05%   |
| LattePanda                           | 2        | 0.05%   |
| JINGSHA                              | 2        | 0.05%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| ASUS All Series                | 118      | 2.87%   |
| Unknown                        | 52       | 1.27%   |
| MSI MS-7C37                    | 45       | 1.1%    |
| ASUS TUF Gaming X570-PLUS      | 32       | 0.78%   |
| Dell OptiPlex 7010             | 28       | 0.68%   |
| MSI MS-7A38                    | 26       | 0.63%   |
| Gigabyte B450M DS3H            | 25       | 0.61%   |
| MSI MS-7C02                    | 24       | 0.58%   |
| MSI MS-7B86                    | 19       | 0.46%   |
| MSI MS-7C91                    | 18       | 0.44%   |
| MSI MS-7C56                    | 18       | 0.44%   |
| MSI MS-7B89                    | 17       | 0.41%   |
| MSI MS-7B79                    | 17       | 0.41%   |
| Dell OptiPlex 9020             | 17       | 0.41%   |
| ASUS ROG STRIX B550-F GAMING   | 17       | 0.41%   |
| Gigabyte B450 AORUS ELITE      | 16       | 0.39%   |
| ASUS ROG STRIX X570-F GAMING   | 16       | 0.39%   |
| ASRock B450M Pro4              | 16       | 0.39%   |
| Gigabyte 970A-DS3P             | 15       | 0.37%   |
| ASUS ROG STRIX B550-I GAMING   | 15       | 0.37%   |
| ASUS PRIME X370-PRO            | 15       | 0.37%   |
| ASUS ROG STRIX B450-F GAMING   | 14       | 0.34%   |
| MSI MS-7C84                    | 13       | 0.32%   |
| MSI MS-7C52                    | 13       | 0.32%   |
| Gigabyte A320M-S2H             | 13       | 0.32%   |
| ASUS TUF Gaming B550M-PLUS     | 13       | 0.32%   |
| ASUS PRIME X470-PRO            | 13       | 0.32%   |
| ASUS PRIME A320M-K             | 13       | 0.32%   |
| MSI MS-7C95                    | 12       | 0.29%   |
| MSI MS-7A34                    | 12       | 0.29%   |
| Gigabyte X570 I AORUS PRO WIFI | 12       | 0.29%   |
| Dell OptiPlex 3020             | 12       | 0.29%   |
| ASUS TUF Gaming B550-PLUS      | 12       | 0.29%   |
| ASUS ROG STRIX X570-E GAMING   | 12       | 0.29%   |
| ASRock B450M Steel Legend      | 12       | 0.29%   |
| Gigabyte X570 AORUS ELITE      | 11       | 0.27%   |
| Gigabyte B550M DS3H            | 11       | 0.27%   |
| Gigabyte B450 AORUS M          | 11       | 0.27%   |
| Gigabyte AB350-Gaming 3        | 11       | 0.27%   |
| ASUS Z170-A                    | 11       | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 245      | 5.97%   |
| ASUS ROG               | 238      | 5.8%    |
| Dell OptiPlex          | 160      | 3.9%    |
| ASUS TUF               | 146      | 3.56%   |
| ASUS All               | 118      | 2.87%   |
| Gigabyte X570          | 68       | 1.66%   |
| Lenovo ThinkCentre     | 65       | 1.58%   |
| HP Compaq              | 58       | 1.41%   |
| Unknown                | 52       | 1.27%   |
| Dell Precision         | 50       | 1.22%   |
| Gigabyte B450          | 49       | 1.19%   |
| MSI MS-7C37            | 45       | 1.1%    |
| Gigabyte B450M         | 43       | 1.05%   |
| HP EliteDesk           | 40       | 0.97%   |
| ASRock B450M           | 34       | 0.83%   |
| Gigabyte B550          | 31       | 0.76%   |
| Dell Inspiron          | 31       | 0.76%   |
| Dell XPS               | 28       | 0.68%   |
| ASRock X570            | 27       | 0.66%   |
| Acer Aspire            | 27       | 0.66%   |
| MSI MS-7A38            | 26       | 0.63%   |
| HP ProDesk             | 25       | 0.61%   |
| MSI MS-7C02            | 24       | 0.58%   |
| Gigabyte B550M         | 23       | 0.56%   |
| ASRock B450            | 21       | 0.51%   |
| MSI MS-7B86            | 19       | 0.46%   |
| MSI MS-7C91            | 18       | 0.44%   |
| MSI MS-7C56            | 18       | 0.44%   |
| ASUS P8Z77-V           | 18       | 0.44%   |
| MSI MS-7B89            | 17       | 0.41%   |
| MSI MS-7B79            | 17       | 0.41%   |
| Lenovo ThinkStation    | 17       | 0.41%   |
| Gigabyte Z390          | 16       | 0.39%   |
| Gigabyte 970A-DS3P     | 16       | 0.39%   |
| ASUS SABERTOOTH        | 16       | 0.39%   |
| ASUS Maximus           | 16       | 0.39%   |
| ASUS M5A78L-M          | 16       | 0.39%   |
| Gigabyte A320M-S2H     | 15       | 0.37%   |
| Gigabyte X470          | 14       | 0.34%   |
| Gigabyte GA-78LMT-USB3 | 14       | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 569      | 13.86%  |
| 2019    | 466      | 11.35%  |
| 2020    | 437      | 10.65%  |
| 2017    | 336      | 8.19%   |
| 2012    | 315      | 7.67%   |
| 2013    | 291      | 7.09%   |
| 2021    | 269      | 6.55%   |
| 2014    | 249      | 6.07%   |
| 2015    | 194      | 4.73%   |
| 2011    | 194      | 4.73%   |
| 2016    | 185      | 4.51%   |
| 2022    | 148      | 3.61%   |
| 2010    | 131      | 3.19%   |
| 2009    | 129      | 3.14%   |
| 2008    | 91       | 2.22%   |
| 2007    | 44       | 1.07%   |
| 2023    | 28       | 0.68%   |
| 2006    | 20       | 0.49%   |
| 2005    | 5        | 0.12%   |
| Unknown | 4        | 0.1%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 4105     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 3830     | 92.42%  |
| Enabled  | 314      | 7.58%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 4103     | 99.95%  |
| Yes  | 2        | 0.05%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 1284     | 30.45%  |
| 32.01-64.0      | 972      | 23.05%  |
| 8.01-16.0       | 692      | 16.41%  |
| 4.01-8.0        | 466      | 11.05%  |
| 64.01-256.0     | 350      | 8.3%    |
| 3.01-4.0        | 242      | 5.74%   |
| 24.01-32.0      | 161      | 3.82%   |
| 1.01-2.0        | 23       | 0.55%   |
| 2.01-3.0        | 19       | 0.45%   |
| Unknown         | 4        | 0.09%   |
| More than 256.0 | 3        | 0.07%   |
| 0.51-1.0        | 1        | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 1351     | 28.35%  |
| 2.01-3.0    | 1190     | 24.97%  |
| 3.01-4.0    | 959      | 20.13%  |
| 1.01-2.0    | 606      | 12.72%  |
| 8.01-16.0   | 440      | 9.23%   |
| 16.01-24.0  | 83       | 1.74%   |
| 0.51-1.0    | 66       | 1.39%   |
| 24.01-32.0  | 31       | 0.65%   |
| 32.01-64.0  | 17       | 0.36%   |
| 0.01-0.5    | 13       | 0.27%   |
| Unknown     | 6        | 0.13%   |
| 64.01-256.0 | 3        | 0.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 1356     | 31.07%  |
| 1      | 1197     | 27.43%  |
| 3      | 873      | 20%     |
| 4      | 460      | 10.54%  |
| 5      | 232      | 5.32%   |
| 6      | 113      | 2.59%   |
| 7      | 58       | 1.33%   |
| 8      | 28       | 0.64%   |
| 9      | 12       | 0.27%   |
| 0      | 12       | 0.27%   |
| 10     | 7        | 0.16%   |
| 11     | 5        | 0.11%   |
| 12     | 3        | 0.07%   |
| 15     | 2        | 0.05%   |
| 14     | 2        | 0.05%   |
| 27     | 1        | 0.02%   |
| 24     | 1        | 0.02%   |
| 18     | 1        | 0.02%   |
| 13     | 1        | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2718     | 65.32%  |
| Yes       | 1443     | 34.68%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 4078     | 99.32%  |
| No        | 28       | 0.68%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2149     | 51.51%  |
| Yes       | 2023     | 48.49%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2418     | 57.78%  |
| Yes       | 1767     | 42.22%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 966      | 23.38%  |
| Germany     | 311      | 7.53%   |
| Brazil      | 309      | 7.48%   |
| Russia      | 267      | 6.46%   |
| Canada      | 174      | 4.21%   |
| UK          | 158      | 3.82%   |
| France      | 155      | 3.75%   |
| Italy       | 145      | 3.51%   |
| Australia   | 139      | 3.36%   |
| Poland      | 117      | 2.83%   |
| Spain       | 104      | 2.52%   |
| Netherlands | 73       | 1.77%   |
| Sweden      | 67       | 1.62%   |
| India       | 62       | 1.5%    |
| Czechia     | 52       | 1.26%   |
| Switzerland | 50       | 1.21%   |
| Mexico      | 49       | 1.19%   |
| Belgium     | 48       | 1.16%   |
| Ukraine     | 42       | 1.02%   |
| Austria     | 41       | 0.99%   |
| Argentina   | 41       | 0.99%   |
| Norway      | 37       | 0.9%    |
| Finland     | 37       | 0.9%    |
| Turkey      | 34       | 0.82%   |
| Romania     | 34       | 0.82%   |
| Colombia    | 28       | 0.68%   |
| Portugal    | 26       | 0.63%   |
| New Zealand | 26       | 0.63%   |
| Greece      | 26       | 0.63%   |
| Japan       | 25       | 0.61%   |
| Hungary     | 25       | 0.61%   |
| Indonesia   | 20       | 0.48%   |
| Denmark     | 20       | 0.48%   |
| Chile       | 20       | 0.48%   |
| Belarus     | 18       | 0.44%   |
| Thailand    | 16       | 0.39%   |
| Philippines | 16       | 0.39%   |
| Ireland     | 14       | 0.34%   |
| South Korea | 13       | 0.31%   |
| Israel      | 13       | 0.31%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Moscow         | 67       | 1.51%   |
| Sydney         | 54       | 1.22%   |
| Berlin         | 34       | 0.77%   |
| St Petersburg  | 33       | 0.75%   |
| Sao Paulo      | 33       | 0.75%   |
| Warsaw         | 30       | 0.68%   |
| Vienna         | 28       | 0.63%   |
| Melbourne      | 22       | 0.5%    |
| Brisbane       | 21       | 0.47%   |
| Toronto        | 20       | 0.45%   |
| Paris          | 20       | 0.45%   |
| Rome           | 19       | 0.43%   |
| Madrid         | 19       | 0.43%   |
| Hamburg        | 19       | 0.43%   |
| Rio de Janeiro | 18       | 0.41%   |
| Auckland       | 18       | 0.41%   |
| Athens         | 18       | 0.41%   |
| Seattle        | 17       | 0.38%   |
| Prague         | 17       | 0.38%   |
| Palmas         | 17       | 0.38%   |
| Zurich         | 16       | 0.36%   |
| Porto Alegre   | 16       | 0.36%   |
| Amsterdam      | 16       | 0.36%   |
| Munich         | 15       | 0.34%   |
| Milan          | 15       | 0.34%   |
| Los Angeles    | 15       | 0.34%   |
| London         | 15       | 0.34%   |
| Helsinki       | 15       | 0.34%   |
| Yekaterinburg  | 14       | 0.32%   |
| Wroclaw        | 14       | 0.32%   |
| Minsk          | 14       | 0.32%   |
| Istanbul       | 14       | 0.32%   |
| Buenos Aires   | 14       | 0.32%   |
| Budapest       | 14       | 0.32%   |
| Vancouver      | 12       | 0.27%   |
| Mexico City    | 12       | 0.27%   |
| Krakow         | 12       | 0.27%   |
| Dallas         | 12       | 0.27%   |
| Cologne        | 12       | 0.27%   |
| Brussels       | 12       | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 1516     | 3029   | 18.13%  |
| WDC                         | 1452     | 2846   | 17.36%  |
| Seagate                     | 1347     | 2447   | 16.11%  |
| Kingston                    | 567      | 841    | 6.78%   |
| Sandisk                     | 440      | 634    | 5.26%   |
| Crucial                     | 436      | 682    | 5.21%   |
| Toshiba                     | 432      | 661    | 5.17%   |
| Hitachi                     | 208      | 350    | 2.49%   |
| Intel                       | 189      | 334    | 2.26%   |
| A-DATA Technology           | 145      | 196    | 1.73%   |
| Phison                      | 109      | 152    | 1.3%    |
| HGST                        | 79       | 153    | 0.94%   |
| Micron/Crucial Technology   | 78       | 102    | 0.93%   |
| Phison Electronics          | 71       | 111    | 0.85%   |
| China                       | 62       | 85     | 0.74%   |
| Unknown                     | 61       | 96     | 0.73%   |
| SPCC                        | 60       | 93     | 0.72%   |
| Silicon Motion              | 58       | 76     | 0.69%   |
| Corsair                     | 58       | 88     | 0.69%   |
| SK hynix                    | 56       | 66     | 0.67%   |
| PNY                         | 48       | 66     | 0.57%   |
| Patriot                     | 46       | 70     | 0.55%   |
| Micron Technology           | 45       | 60     | 0.54%   |
| OCZ                         | 42       | 57     | 0.5%    |
| Maxtor                      | 27       | 33     | 0.32%   |
| Intenso                     | 27       | 36     | 0.32%   |
| Transcend                   | 26       | 34     | 0.31%   |
| XPG                         | 25       | 35     | 0.3%    |
| Team                        | 25       | 36     | 0.3%    |
| Realtek Semiconductor       | 23       | 32     | 0.28%   |
| ADATA Technology            | 23       | 28     | 0.28%   |
| ASMT                        | 22       | 25     | 0.26%   |
| Plextor                     | 21       | 29     | 0.25%   |
| Gigabyte Technology         | 21       | 38     | 0.25%   |
| Kingston Technology Company | 20       | 26     | 0.24%   |
| GOODRAM                     | 20       | 32     | 0.24%   |
| KingSpec                    | 19       | 29     | 0.23%   |
| Hewlett-Packard             | 19       | 23     | 0.23%   |
| Apacer                      | 19       | 32     | 0.23%   |
| MAXIO Technology (Hangzhou) | 18       | 22     | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Samsung SSD 850 EVO 250GB                           | 135      | 1.34%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 115      | 1.14%   |
| Samsung SSD 860 EVO 500GB                           | 114      | 1.13%   |
| Kingston SA400S37240G 240GB SSD                     | 112      | 1.11%   |
| Seagate ST1000DM010-2EP102 1TB                      | 108      | 1.07%   |
| Seagate ST2000DM008-2FR102 2TB                      | 104      | 1.03%   |
| Samsung SSD 860 EVO 1TB                             | 95       | 0.94%   |
| Samsung SSD 850 EVO 500GB                           | 95       | 0.94%   |
| Samsung NVMe SSD Drive 500GB                        | 91       | 0.9%    |
| Seagate ST500DM002-1BD142 500GB                     | 86       | 0.86%   |
| Kingston SA400S37480G 480GB SSD                     | 79       | 0.79%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 76       | 0.76%   |
| Toshiba DT01ACA100 1TB                              | 76       | 0.76%   |
| Kingston SA400S37120G 120GB SSD                     | 75       | 0.75%   |
| Crucial CT500MX500SSD1 500GB                        | 73       | 0.73%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 71       | 0.71%   |
| Samsung NVMe SSD Drive 1TB                          | 69       | 0.69%   |
| Crucial CT1000MX500SSD1 1TB                         | 58       | 0.58%   |
| Seagate ST1000DM003-1ER162 1TB                      | 50       | 0.5%    |
| Samsung SSD 860 EVO 250GB                           | 48       | 0.48%   |
| Seagate ST2000DM001-1ER164 2TB                      | 47       | 0.47%   |
| Kingston SV300S37A120G 120GB SSD                    | 47       | 0.47%   |
| Toshiba HDWD110 1TB                                 | 46       | 0.46%   |
| Seagate ST4000DM004-2CV104 4TB                      | 46       | 0.46%   |
| Samsung SSD 970 EVO Plus 500GB                      | 46       | 0.46%   |
| Seagate ST1000DM003-1CH162 1TB                      | 43       | 0.43%   |
| SanDisk NVMe SSD Drive 1TB                          | 42       | 0.42%   |
| SanDisk NVMe SSD Drive 500GB                        | 41       | 0.41%   |
| Crucial CT240BX500SSD1 240GB                        | 41       | 0.41%   |
| Toshiba DT01ACA200 2TB                              | 40       | 0.4%    |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 39       | 0.39%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 39       | 0.39%   |
| Samsung SSD 840 EVO 250GB                           | 39       | 0.39%   |
| Seagate ST2000DM006-2DM164 2TB                      | 38       | 0.38%   |
| Samsung SSD 860 QVO 1TB                             | 37       | 0.37%   |
| Seagate ST3500418AS 500GB                           | 36       | 0.36%   |
| Seagate ST1000DM003-1SB102 1TB                      | 36       | 0.36%   |
| Samsung SSD 970 EVO Plus 1TB                        | 36       | 0.36%   |
| Samsung SM963 2.5" NVMe PCIe SSD 250GB              | 33       | 0.33%   |
| Phison E12 NVMe Controller 2TB                      | 33       | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1307     | 2365   | 37.37%  |
| WDC                 | 1243     | 2400   | 35.54%  |
| Toshiba             | 376      | 549    | 10.75%  |
| Hitachi             | 208      | 350    | 5.95%   |
| Samsung Electronics | 155      | 244    | 4.43%   |
| HGST                | 79       | 153    | 2.26%   |
| Maxtor              | 26       | 30     | 0.74%   |
| Unknown             | 20       | 26     | 0.57%   |
| SABRENT             | 15       | 18     | 0.43%   |
| Fujitsu             | 9        | 11     | 0.26%   |
| ASMT                | 8        | 10     | 0.23%   |
| Intenso             | 5        | 8      | 0.14%   |
| Hewlett-Packard     | 5        | 6      | 0.14%   |
| JMicron Technology  | 4        | 10     | 0.11%   |
| Apple               | 4        | 4      | 0.11%   |
| USB                 | 3        | 3      | 0.09%   |
| SSK                 | 3        | 3      | 0.09%   |
| MaxDigital          | 3        | 3      | 0.09%   |
| USB3.0              | 2        | 2      | 0.06%   |
| Synology            | 2        | 3      | 0.06%   |
| QNAP                | 2        | 2      | 0.06%   |
| LaCie               | 2        | 4      | 0.06%   |
| H/W                 | 2        | 4      | 0.06%   |
| ASMT109x            | 2        | 2      | 0.06%   |
| USB 3.0             | 1        | 3      | 0.03%   |
| SAGE                | 1        | 1      | 0.03%   |
| RSH-339             | 1        | 1      | 0.03%   |
| MARVELL             | 1        | 1      | 0.03%   |
| Magnetic Data       | 1        | 1      | 0.03%   |
| KESU                | 1        | 1      | 0.03%   |
| IET                 | 1        | 1      | 0.03%   |
| External            | 1        | 1      | 0.03%   |
| ExcelStor           | 1        | 1      | 0.03%   |
| ASMT106x            | 1        | 2      | 0.03%   |
| ASMedia             | 1        | 1      | 0.03%   |
| Unknown             | 1        | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 887      | 1602   | 27.6%   |
| Kingston            | 463      | 688    | 14.41%  |
| Crucial             | 399      | 628    | 12.41%  |
| SanDisk             | 242      | 315    | 7.53%   |
| WDC                 | 217      | 331    | 6.75%   |
| A-DATA Technology   | 125      | 168    | 3.89%   |
| Intel               | 94       | 179    | 2.92%   |
| China               | 62       | 85     | 1.93%   |
| SPCC                | 49       | 73     | 1.52%   |
| PNY                 | 48       | 65     | 1.49%   |
| Patriot             | 43       | 66     | 1.34%   |
| OCZ                 | 42       | 57     | 1.31%   |
| Toshiba             | 36       | 57     | 1.12%   |
| Corsair             | 32       | 49     | 1%      |
| Micron Technology   | 31       | 43     | 0.96%   |
| Transcend           | 26       | 34     | 0.81%   |
| Team                | 22       | 33     | 0.68%   |
| SK hynix            | 22       | 23     | 0.68%   |
| GOODRAM             | 20       | 32     | 0.62%   |
| KingSpec            | 19       | 29     | 0.59%   |
| Plextor             | 18       | 25     | 0.56%   |
| Intenso             | 17       | 22     | 0.53%   |
| Apacer              | 17       | 29     | 0.53%   |
| Seagate             | 15       | 18     | 0.47%   |
| Gigabyte Technology | 14       | 24     | 0.44%   |
| LITEON              | 13       | 16     | 0.4%    |
| LITEONIT            | 12       | 13     | 0.37%   |
| KingDian            | 11       | 12     | 0.34%   |
| ASMT                | 11       | 12     | 0.34%   |
| Verbatim            | 9        | 12     | 0.28%   |
| Unknown             | 9        | 9      | 0.28%   |
| Mushkin             | 9        | 14     | 0.28%   |
| Lexar               | 9        | 14     | 0.28%   |
| Hewlett-Packard     | 8        | 9      | 0.25%   |
| Leven               | 7        | 8      | 0.22%   |
| JMicron Technology  | 7        | 7      | 0.22%   |
| AMD                 | 7        | 10     | 0.22%   |
| Netac               | 6        | 6      | 0.19%   |
| Unknown             | 5        | 7      | 0.16%   |
| OWC                 | 4        | 6      | 0.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 2669     | 6225   | 37.98%  |
| SSD     | 2575     | 4995   | 36.64%  |
| NVMe    | 1653     | 2895   | 23.52%  |
| Unknown | 121      | 168    | 1.72%   |
| MMC     | 10       | 12     | 0.14%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 3630     | 10883  | 64.56%  |
| NVMe | 1650     | 2884   | 29.34%  |
| SAS  | 333      | 516    | 5.92%   |
| MMC  | 10       | 12     | 0.18%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 2646     | 5397   | 45.19%  |
| 0.51-1.0   | 1776     | 3152   | 30.33%  |
| 1.01-2.0   | 729      | 1193   | 12.45%  |
| 3.01-4.0   | 303      | 578    | 5.18%   |
| 4.01-10.0  | 185      | 453    | 3.16%   |
| 2.01-3.0   | 183      | 371    | 3.13%   |
| 10.01-20.0 | 33       | 76     | 0.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 826      | 18.67%  |
| 1001-2000      | 806      | 18.22%  |
| More than 3000 | 670      | 15.14%  |
| 251-500        | 669      | 15.12%  |
| 101-250        | 563      | 12.73%  |
| 2001-3000      | 362      | 8.18%   |
| 1-20           | 205      | 4.63%   |
| Unknown        | 169      | 3.82%   |
| 51-100         | 106      | 2.4%    |
| 21-50          | 47       | 1.06%   |
| 0              | 1        | 0.02%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 844      | 18.16%  |
| 101-250        | 633      | 13.62%  |
| 21-50          | 613      | 13.19%  |
| 251-500        | 559      | 12.03%  |
| 501-1000       | 558      | 12.01%  |
| 51-100         | 498      | 10.72%  |
| 1001-2000      | 400      | 8.61%   |
| More than 3000 | 210      | 4.52%   |
| Unknown        | 169      | 3.64%   |
| 2001-3000      | 161      | 3.46%   |
| 0              | 2        | 0.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 19       | 44     | 3.29%   |
| Seagate ST31000528AS 1TB              | 8        | 10     | 1.39%   |
| Seagate ST31000524AS 1TB              | 8        | 8      | 1.39%   |
| WDC WD10EZEX-00BN5A0 1TB              | 7        | 7      | 1.21%   |
| Seagate ST3500418AS 500GB             | 7        | 16     | 1.21%   |
| Samsung Electronics SSD 870 EVO 1TB   | 7        | 9      | 1.21%   |
| Intel SSDSC2CT120A3 120GB             | 6        | 33     | 1.04%   |
| Toshiba MQ01ABD050 500GB              | 5        | 6      | 0.87%   |
| Seagate ST31500341AS 1TB              | 5        | 5      | 0.87%   |
| Seagate ST2000DM001-1CH164 2TB        | 5        | 5      | 0.87%   |
| Seagate ST1000DM010-2EP102 1TB        | 5        | 5      | 0.87%   |
| Samsung Electronics HD322HJ 320GB     | 5        | 7      | 0.87%   |
| Crucial CT128MX100SSD1 128GB          | 5        | 7      | 0.87%   |
| WDC WD10EZEX-08WN4A0 1TB              | 4        | 5      | 0.69%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 4        | 4      | 0.69%   |
| Samsung Electronics HD501LJ 500GB     | 4        | 31     | 0.69%   |
| Crucial CT275MX300SSD1 275GB          | 4        | 5      | 0.69%   |
| Crucial CT240M500SSD1 240GB           | 4        | 4      | 0.69%   |
| WDC WD5000AAKX-603CA0 500GB           | 3        | 3      | 0.52%   |
| WDC WD5000AAKX-00ERMA0 500GB          | 3        | 3      | 0.52%   |
| WDC WD20EZRX-00D8PB0 2TB              | 3        | 5      | 0.52%   |
| WDC WD10EZEX-00WN4A0 1TB              | 3        | 3      | 0.52%   |
| Toshiba MQ01ABD100 1TB                | 3        | 3      | 0.52%   |
| Toshiba DT01ACA100 1TB                | 3        | 3      | 0.52%   |
| Seagate ST500LT012-1DG142 500GB       | 3        | 3      | 0.52%   |
| Seagate ST3000DM008-2DM166 3TB        | 3        | 4      | 0.52%   |
| Seagate ST2000DM008-2FR102 2TB        | 3        | 3      | 0.52%   |
| Seagate ST2000DM001-1ER164 2TB        | 3        | 3      | 0.52%   |
| Seagate ST2000DL003-9VT166 2TB        | 3        | 3      | 0.52%   |
| Seagate ST1000DM003-1ER162 1TB        | 3        | 3      | 0.52%   |
| SanDisk SSD PLUS 480GB                | 3        | 3      | 0.52%   |
| Samsung Electronics SSD 870 EVO 500GB | 3        | 4      | 0.52%   |
| Samsung Electronics SSD 870 EVO 2TB   | 3        | 3      | 0.52%   |
| Kingston SV300S37A120G 120GB SSD      | 3        | 3      | 0.52%   |
| Kingston SA400S37240G 240GB SSD       | 3        | 3      | 0.52%   |
| Hitachi HDS721010DLE630 1TB           | 3        | 5      | 0.52%   |
| Hitachi HDS721010CLA332 1TB           | 3        | 3      | 0.52%   |
| Hitachi HDP725050GLA360 500GB         | 3        | 3      | 0.52%   |
| WDC WD5000AAKX-753CA1 500GB           | 2        | 2      | 0.35%   |
| WDC WD5000AAKX-003CA0 500GB           | 2        | 2      | 0.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 144      | 229    | 26.37%  |
| WDC                         | 135      | 197    | 24.73%  |
| Samsung Electronics         | 54       | 95     | 9.89%   |
| Hitachi                     | 38       | 51     | 6.96%   |
| Toshiba                     | 33       | 38     | 6.04%   |
| Intel                       | 23       | 52     | 4.21%   |
| Crucial                     | 23       | 32     | 4.21%   |
| SanDisk                     | 18       | 18     | 3.3%    |
| Kingston                    | 14       | 16     | 2.56%   |
| A-DATA Technology           | 11       | 11     | 2.01%   |
| Maxtor                      | 7        | 7      | 1.28%   |
| Corsair                     | 6        | 9      | 1.1%    |
| OCZ                         | 4        | 5      | 0.73%   |
| SPCC                        | 3        | 4      | 0.55%   |
| SK hynix                    | 3        | 3      | 0.55%   |
| LITEON                      | 3        | 3      | 0.55%   |
| HGST                        | 3        | 5      | 0.55%   |
| OCZ-VERTEX3                 | 2        | 2      | 0.37%   |
| Micron Technology           | 2        | 2      | 0.37%   |
| Intenso                     | 2        | 2      | 0.37%   |
| Fujitsu                     | 2        | 2      | 0.37%   |
| Verbatim                    | 1        | 1      | 0.18%   |
| Unknown                     | 1        | 1      | 0.18%   |
| Team                        | 1        | 4      | 0.18%   |
| PNY                         | 1        | 1      | 0.18%   |
| ORICO                       | 1        | 1      | 0.18%   |
| MAXIO Technology (Hangzhou) | 1        | 1      | 0.18%   |
| LITEONIT                    | 1        | 1      | 0.18%   |
| KingSpec                    | 1        | 1      | 0.18%   |
| KingDian                    | 1        | 1      | 0.18%   |
| HPE                         | 1        | 1      | 0.18%   |
| Hewlett-Packard             | 1        | 1      | 0.18%   |
| BIWIN                       | 1        | 1      | 0.18%   |
| ASMT                        | 1        | 1      | 0.18%   |
| ASMedia                     | 1        | 1      | 0.18%   |
| Apacer                      | 1        | 1      | 0.18%   |
| AMD                         | 1        | 2      | 0.18%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 144      | 229    | 36.92%  |
| WDC                 | 132      | 193    | 33.85%  |
| Hitachi             | 38       | 51     | 9.74%   |
| Toshiba             | 33       | 38     | 8.46%   |
| Samsung Electronics | 29       | 64     | 7.44%   |
| Maxtor              | 7        | 7      | 1.79%   |
| HGST                | 3        | 5      | 0.77%   |
| Fujitsu             | 2        | 2      | 0.51%   |
| Hewlett-Packard     | 1        | 1      | 0.26%   |
| ASMT                | 1        | 1      | 0.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 355      | 591    | 69.88%  |
| SSD  | 139      | 198    | 27.36%  |
| NVMe | 14       | 14     | 2.76%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD5000BEVT-00ZAT0 500GB       | 1        | 2      | 11.11%  |
| Toshiba HDWD130 3TB               | 1        | 1      | 11.11%  |
| SPCC M.2 PCIe SSD 2TB             | 1        | 1      | 11.11%  |
| Seagate ST3320613AS 320GB         | 1        | 1      | 11.11%  |
| Seagate ST31000528AS 1TB          | 1        | 2      | 11.11%  |
| Samsung Electronics SSD 980 500GB | 1        | 2      | 11.11%  |
| Samsung Electronics SSD 980 1TB   | 1        | 2      | 11.11%  |
| Samsung Electronics HD321HJ 320GB | 1        | 2      | 11.11%  |
| Hitachi HDS721010DLE630 1TB       | 1        | 8      | 11.11%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 3        | 6      | 33.33%  |
| Seagate             | 2        | 3      | 22.22%  |
| WDC                 | 1        | 2      | 11.11%  |
| Toshiba             | 1        | 1      | 11.11%  |
| SPCC                | 1        | 1      | 11.11%  |
| Hitachi             | 1        | 8      | 11.11%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 2479     | 8125   | 52.07%  |
| Works    | 1785     | 5346   | 37.49%  |
| Malfunc  | 489      | 803    | 10.27%  |
| Failed   | 8        | 21     | 0.17%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 2318     | 35.72%  |
| AMD                              | 1744     | 26.87%  |
| Samsung Electronics              | 722      | 11.12%  |
| SanDisk                          | 280      | 4.31%   |
| ASMedia Technology               | 276      | 4.25%   |
| Phison Electronics               | 207      | 3.19%   |
| Kingston Technology Company      | 140      | 2.16%   |
| Marvell Technology Group         | 131      | 2.02%   |
| Micron/Crucial Technology        | 113      | 1.74%   |
| JMicron Technology               | 92       | 1.42%   |
| Silicon Motion                   | 69       | 1.06%   |
| ADATA Technology                 | 57       | 0.88%   |
| Nvidia                           | 54       | 0.83%   |
| SK hynix                         | 33       | 0.51%   |
| Realtek Semiconductor            | 32       | 0.49%   |
| Toshiba America Info Systems     | 28       | 0.43%   |
| LSI Logic / Symbios Logic        | 25       | 0.39%   |
| Seagate Technology               | 22       | 0.34%   |
| MAXIO Technology (Hangzhou)      | 20       | 0.31%   |
| Broadcom / LSI                   | 20       | 0.31%   |
| Micron Technology                | 16       | 0.25%   |
| Silicon Image                    | 13       | 0.2%    |
| VIA Technologies                 | 12       | 0.18%   |
| KIOXIA                           | 10       | 0.15%   |
| Lite-On Technology               | 9        | 0.14%   |
| Adaptec                          | 8        | 0.12%   |
| Netac Technology                 | 6        | 0.09%   |
| Solid State Storage Technology   | 4        | 0.06%   |
| Integrated Technology Express    | 4        | 0.06%   |
| Shenzhen Longsys Electronics     | 3        | 0.05%   |
| INNOGRIT                         | 3        | 0.05%   |
| Hewlett-Packard                  | 3        | 0.05%   |
| 3ware                            | 3        | 0.05%   |
| Union Memory (Shenzhen)          | 2        | 0.03%   |
| ULi Electronics                  | 2        | 0.03%   |
| Lite-On IT Corp. / Plextor       | 2        | 0.03%   |
| HighPoint Technologies           | 2        | 0.03%   |
| Solidigm                         | 1        | 0.02%   |
| Silicon Integrated Systems [SiS] | 1        | 0.02%   |
| Promise Technology               | 1        | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 1114     | 14.18%  |
| AMD 400 Series Chipset SATA Controller                                                  | 423      | 5.38%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 420      | 5.35%   |
| AMD 500 Series Chipset SATA Controller                                                  | 275      | 3.5%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 268      | 3.41%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 263      | 3.35%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 244      | 3.11%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 221      | 2.81%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 177      | 2.25%   |
| Intel SATA Controller [RAID mode]                                                       | 168      | 2.14%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 162      | 2.06%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 162      | 2.06%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 148      | 1.88%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 146      | 1.86%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 144      | 1.83%   |
| Phison E12 NVMe Controller                                                              | 113      | 1.44%   |
| AMD 300 Series Chipset SATA Controller                                                  | 112      | 1.43%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 105      | 1.34%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 100      | 1.27%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 96       | 1.22%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 88       | 1.12%   |
| AMD FCH SATA Controller D                                                               | 75       | 0.95%   |
| Samsung NVMe SSD Controller 980                                                         | 66       | 0.84%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 65       | 0.83%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 65       | 0.83%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 64       | 0.81%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 63       | 0.8%    |
| Intel Volume Management Device NVMe RAID Controller                                     | 57       | 0.73%   |
| AMD X370 Series Chipset SATA Controller                                                 | 55       | 0.7%    |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 52       | 0.66%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 48       | 0.61%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 48       | 0.61%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 48       | 0.61%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 48       | 0.61%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 47       | 0.6%    |
| Kingston Company A2000 NVMe SSD                                                         | 46       | 0.59%   |
| Intel SSD 660P Series                                                                   | 46       | 0.59%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 46       | 0.59%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 43       | 0.55%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 42       | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 3601     | 58.12%  |
| NVMe | 1647     | 26.58%  |
| IDE  | 578      | 9.33%   |
| RAID | 312      | 5.04%   |
| SAS  | 43       | 0.69%   |
| SCSI | 15       | 0.24%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 2301     | 56.05%  |
| AMD                      | 1803     | 43.92%  |
| PowerNV C1P9S01 REV 1.01 | 1        | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 139      | 3.36%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 100      | 2.42%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 76       | 1.84%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 74       | 1.79%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 69       | 1.67%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 66       | 1.6%    |
| AMD Ryzen 9 5900X 12-Core Processor         | 57       | 1.38%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 56       | 1.36%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 56       | 1.36%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 55       | 1.33%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 55       | 1.33%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 51       | 1.23%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 44       | 1.06%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 42       | 1.02%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 42       | 1.02%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 40       | 0.97%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 40       | 0.97%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 40       | 0.97%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 40       | 0.97%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 40       | 0.97%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 37       | 0.9%    |
| Intel Core i5-2400 CPU @ 3.10GHz            | 35       | 0.85%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 35       | 0.85%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 35       | 0.85%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 34       | 0.82%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 34       | 0.82%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 33       | 0.8%    |
| AMD FX-6300 Six-Core Processor              | 33       | 0.8%    |
| Intel Core i5-9400F CPU @ 2.90GHz           | 31       | 0.75%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 31       | 0.75%   |
| AMD FX-8350 Eight-Core Processor            | 31       | 0.75%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 30       | 0.73%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 27       | 0.65%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 26       | 0.63%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 26       | 0.63%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 26       | 0.63%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 25       | 0.61%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 25       | 0.61%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 25       | 0.61%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 24       | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 704      | 17.09%  |
| Intel Core i7           | 649      | 15.75%  |
| AMD Ryzen 5             | 591      | 14.34%  |
| AMD Ryzen 7             | 411      | 9.98%   |
| AMD Ryzen 9             | 257      | 6.24%   |
| Intel Xeon              | 219      | 5.32%   |
| Intel Core i3           | 216      | 5.24%   |
| Other                   | 164      | 3.98%   |
| AMD FX                  | 145      | 3.52%   |
| Intel Core 2 Duo        | 73       | 1.77%   |
| AMD Ryzen 3             | 64       | 1.55%   |
| Intel Core i9           | 56       | 1.36%   |
| Intel Core 2 Quad       | 56       | 1.36%   |
| Intel Celeron           | 51       | 1.24%   |
| Intel Pentium           | 49       | 1.19%   |
| AMD Ryzen Threadripper  | 48       | 1.17%   |
| AMD Phenom II X4        | 45       | 1.09%   |
| AMD A10                 | 32       | 0.78%   |
| AMD A8                  | 27       | 0.66%   |
| Intel Pentium Dual-Core | 24       | 0.58%   |
| AMD A6                  | 21       | 0.51%   |
| AMD Athlon II X2        | 19       | 0.46%   |
| AMD Athlon              | 19       | 0.46%   |
| AMD Phenom II X6        | 17       | 0.41%   |
| Intel Core 2            | 15       | 0.36%   |
| AMD Athlon 64 X2        | 13       | 0.32%   |
| Intel Atom              | 12       | 0.29%   |
| AMD Phenom              | 12       | 0.29%   |
| AMD Ryzen 7 PRO         | 11       | 0.27%   |
| AMD A4                  | 11       | 0.27%   |
| AMD Ryzen 5 PRO         | 10       | 0.24%   |
| AMD Athlon X4           | 8        | 0.19%   |
| Intel Pentium Gold      | 7        | 0.17%   |
| AMD Phenom II X2        | 7        | 0.17%   |
| AMD Athlon II X4        | 7        | 0.17%   |
| Intel Pentium Dual      | 6        | 0.15%   |
| Intel Genuine           | 4        | 0.1%    |
| AMD Athlon Dual Core    | 4        | 0.1%    |
| Intel Pentium D         | 3        | 0.07%   |
| AMD Opteron             | 3        | 0.07%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 1528     | 37.07%  |
| 6      | 884      | 21.45%  |
| 8      | 591      | 14.34%  |
| 2      | 573      | 13.9%   |
| 12     | 227      | 5.51%   |
| 16     | 141      | 3.42%   |
| 3      | 53       | 1.29%   |
| 10     | 50       | 1.21%   |
| 1      | 32       | 0.78%   |
| 24     | 17       | 0.41%   |
| 32     | 12       | 0.29%   |
| 14     | 10       | 0.24%   |
| 28     | 1        | 0.02%   |
| 20     | 1        | 0.02%   |
| 18     | 1        | 0.02%   |
| 5      | 1        | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 4054     | 98.76%  |
| 2      | 51       | 1.24%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 2826     | 68.69%  |
| 1      | 1287     | 31.28%  |
| 4      | 1        | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 4016     | 97.43%  |
| Unknown        | 106      | 2.57%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 680      | 15.9%   |
| 0x306c3    | 319      | 7.46%   |
| 0x08701021 | 291      | 6.8%    |
| 0x306a9    | 186      | 4.35%   |
| 0x506e3    | 175      | 4.09%   |
| 0x0800820d | 167      | 3.9%    |
| 0x206a7    | 137      | 3.2%    |
| 0x906ea    | 135      | 3.16%   |
| 0x08701013 | 121      | 2.83%   |
| 0x906e9    | 118      | 2.76%   |
| 0x0a201016 | 90       | 2.1%    |
| 0x1067a    | 88       | 2.06%   |
| 0x06000852 | 77       | 1.8%    |
| 0x0a201009 | 69       | 1.61%   |
| 0x08108109 | 65       | 1.52%   |
| 0x08001138 | 64       | 1.5%    |
| 0x0a20120a | 60       | 1.4%    |
| 0x906ed    | 57       | 1.33%   |
| 0x0a50000c | 53       | 1.24%   |
| 0x010000c8 | 51       | 1.19%   |
| 0x08001137 | 50       | 1.17%   |
| 0x0a601203 | 49       | 1.15%   |
| 0x90672    | 48       | 1.12%   |
| 0x306f2    | 45       | 1.05%   |
| 0xa0655    | 44       | 1.03%   |
| 0x0a50000d | 42       | 0.98%   |
| 0xa0653    | 41       | 0.96%   |
| 0x08101016 | 40       | 0.94%   |
| 0x06001119 | 34       | 0.79%   |
| 0x206d7    | 33       | 0.77%   |
| 0x20655    | 28       | 0.65%   |
| 0xa0671    | 27       | 0.63%   |
| 0x106a5    | 27       | 0.63%   |
| 0x10676    | 27       | 0.63%   |
| 0x6fb      | 26       | 0.61%   |
| 0x106e5    | 26       | 0.61%   |
| 0x906eb    | 25       | 0.58%   |
| 0x06000822 | 25       | 0.58%   |
| 0x906ec    | 23       | 0.54%   |
| 0x0800820b | 22       | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 479      | 11.61%  |
| KabyLake         | 469      | 11.37%  |
| Haswell          | 441      | 10.69%  |
| Zen 3            | 375      | 9.09%   |
| Zen+             | 287      | 6.96%   |
| IvyBridge        | 268      | 6.5%    |
| Skylake          | 244      | 5.92%   |
| SandyBridge      | 211      | 5.12%   |
| Zen              | 209      | 5.07%   |
| Piledriver       | 157      | 3.81%   |
| Penryn           | 138      | 3.35%   |
| CometLake        | 115      | 2.79%   |
| K10              | 112      | 2.72%   |
| Alderlake Hybrid | 108      | 2.62%   |
| Unknown          | 77       | 1.87%   |
| Westmere         | 65       | 1.58%   |
| Nehalem          | 62       | 1.5%    |
| Core             | 60       | 1.45%   |
| Icelake          | 43       | 1.04%   |
| Steamroller      | 31       | 0.75%   |
| Excavator        | 26       | 0.63%   |
| Bulldozer        | 26       | 0.63%   |
| K8 Hammer        | 22       | 0.53%   |
| Broadwell        | 20       | 0.48%   |
| Silvermont       | 16       | 0.39%   |
| Bonnell          | 10       | 0.24%   |
| K10 Llano        | 8        | 0.19%   |
| NetBurst         | 7        | 0.17%   |
| Jaguar           | 7        | 0.17%   |
| Tremont          | 6        | 0.15%   |
| Goldmont plus    | 6        | 0.15%   |
| Goldmont         | 5        | 0.12%   |
| Bobcat           | 5        | 0.12%   |
| Puma             | 4        | 0.1%    |
| Gracemont        | 3        | 0.07%   |
| TigerLake        | 2        | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Nvidia                           | 1784     | 39.74%  |
| AMD                              | 1667     | 37.14%  |
| Intel                            | 1016     | 22.63%  |
| ASPEED Technology                | 10       | 0.22%   |
| Matrox Electronics Systems       | 9        | 0.2%    |
| VIA Technologies                 | 1        | 0.02%   |
| Silicon Integrated Systems [SiS] | 1        | 0.02%   |
| S3 Graphics                      | 1        | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 331      | 7.11%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 165      | 3.55%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 134      | 2.88%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 119      | 2.56%   |
| Intel HD Graphics 530                                                       | 114      | 2.45%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 112      | 2.41%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 102      | 2.19%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 86       | 1.85%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 83       | 1.78%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 83       | 1.78%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 80       | 1.72%   |
| Intel HD Graphics 630                                                       | 75       | 1.61%   |
| Nvidia GK208B [GeForce GT 710]                                              | 67       | 1.44%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 64       | 1.38%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 62       | 1.33%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 60       | 1.29%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 59       | 1.27%   |
| Nvidia GT218 [GeForce 210]                                                  | 54       | 1.16%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 54       | 1.16%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 51       | 1.1%    |
| Nvidia GM204 [GeForce GTX 970]                                              | 50       | 1.07%   |
| AMD Raphael                                                                 | 50       | 1.07%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 49       | 1.05%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 47       | 1.01%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 47       | 1.01%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 46       | 0.99%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 46       | 0.99%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 44       | 0.95%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 42       | 0.9%    |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 41       | 0.88%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 41       | 0.88%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 40       | 0.86%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 39       | 0.84%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 37       | 0.8%    |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 35       | 0.75%   |
| Nvidia GK208B [GeForce GT 730]                                              | 34       | 0.73%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 32       | 0.69%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 32       | 0.69%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 32       | 0.69%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 31       | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Nvidia               | 1598     | 38.27%  |
| 1 x AMD                  | 1503     | 35.99%  |
| 1 x Intel                | 752      | 18.01%  |
| Intel + Nvidia           | 101      | 2.42%   |
| 2 x AMD                  | 74       | 1.77%   |
| AMD + Nvidia             | 53       | 1.27%   |
| Intel + AMD              | 36       | 0.86%   |
| 2 x Nvidia               | 25       | 0.6%    |
| 1 x ASPEED               | 6        | 0.14%   |
| 2 x Intel                | 5        | 0.12%   |
| 1 x Matrox               | 5        | 0.12%   |
| Nvidia + Matrox          | 3        | 0.07%   |
| Nvidia + ASPEED          | 2        | 0.05%   |
| Intel + AMD + 1 x Nvidia | 2        | 0.05%   |
| Other                    | 1        | 0.02%   |
| 3 x AMD                  | 1        | 0.02%   |
| 2 x Nvidia + 1 x ASPEED  | 1        | 0.02%   |
| 1 x VIA                  | 1        | 0.02%   |
| 1 x SiS                  | 1        | 0.02%   |
| 1 x S3 Graphics          | 1        | 0.02%   |
| Intel + 2 x Nvidia       | 1        | 0.02%   |
| Intel + 2 x AMD          | 1        | 0.02%   |
| AMD + 2 x Nvidia         | 1        | 0.02%   |
| AMD + Matrox             | 1        | 0.02%   |
| AMD + ASPEED             | 1        | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 3088     | 73.77%  |
| Proprietary | 977      | 23.34%  |
| Unknown     | 121      | 2.89%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1421     | 33.19%  |
| 7.01-8.0   | 680      | 15.88%  |
| 1.01-2.0   | 544      | 12.7%   |
| 3.01-4.0   | 462      | 10.79%  |
| 0.51-1.0   | 388      | 9.06%   |
| 0.01-0.5   | 286      | 6.68%   |
| 8.01-16.0  | 231      | 5.39%   |
| 5.01-6.0   | 184      | 4.3%    |
| 2.01-3.0   | 59       | 1.38%   |
| 16.01-24.0 | 26       | 0.61%   |
| 4.01-5.0   | 1        | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 728      | 15.09%  |
| Dell                 | 649      | 13.46%  |
| Goldstar             | 616      | 12.77%  |
| Acer                 | 334      | 6.93%   |
| Hewlett-Packard      | 298      | 6.18%   |
| AOC                  | 277      | 5.74%   |
| BenQ                 | 256      | 5.31%   |
| Ancor Communications | 231      | 4.79%   |
| Philips              | 196      | 4.06%   |
| ViewSonic            | 121      | 2.51%   |
| Lenovo               | 109      | 2.26%   |
| ASUSTek Computer     | 105      | 2.18%   |
| Iiyama               | 99       | 2.05%   |
| Sceptre Tech         | 47       | 0.97%   |
| MSI                  | 47       | 0.97%   |
| Sony                 | 46       | 0.95%   |
| Unknown              | 40       | 0.83%   |
| Eizo                 | 40       | 0.83%   |
| Gigabyte Technology  | 38       | 0.79%   |
| HannStar             | 28       | 0.58%   |
| NEC Computers        | 26       | 0.54%   |
| Vizio                | 21       | 0.44%   |
| Mi                   | 19       | 0.39%   |
| LG Electronics       | 16       | 0.33%   |
| Insignia             | 16       | 0.33%   |
| Fujitsu Siemens      | 15       | 0.31%   |
| ___                  | 12       | 0.25%   |
| Panasonic            | 12       | 0.25%   |
| Pixio                | 10       | 0.21%   |
| Gateway              | 10       | 0.21%   |
| Hitachi              | 9        | 0.19%   |
| Vestel Elektronik    | 8        | 0.17%   |
| Unknown (XXX)        | 8        | 0.17%   |
| Toshiba              | 8        | 0.17%   |
| RTK                  | 8        | 0.17%   |
| HUAWEI               | 8        | 0.17%   |
| ONN                  | 7        | 0.15%   |
| Medion               | 7        | 0.15%   |
| Apple                | 7        | 0.15%   |
| Sharp                | 6        | 0.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 37       | 0.71%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 37       | 0.71%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 27       | 0.52%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 25       | 0.48%   |
| AOC 27B2 AOC2702 1920x1080 598x336mm 27.0-inch                        | 25       | 0.48%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 20       | 0.38%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 19       | 0.36%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 19       | 0.36%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 19       | 0.36%   |
| AOC 24V2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                    | 18       | 0.34%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 17       | 0.32%   |
| AOC 24P1X AOC2401 1920x1200 518x324mm 24.1-inch                       | 16       | 0.31%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch      | 16       | 0.31%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch     | 15       | 0.29%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                     | 15       | 0.29%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 15       | 0.29%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                       | 14       | 0.27%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 13       | 0.25%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch    | 12       | 0.23%   |
| Samsung Electronics SyncMaster SAM01D3 1440x900 410x260mm 19.1-inch   | 11       | 0.21%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch              | 11       | 0.21%   |
| Hewlett-Packard 24f HPN3545 1920x1080 527x296mm 23.8-inch             | 11       | 0.21%   |
| Goldstar 23MP55 GSM5A23 1920x1080 510x290mm 23.1-inch                 | 11       | 0.21%   |
| Dell U2515H DELD06F 2560x1440 550x310mm 24.9-inch                     | 11       | 0.21%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                     | 11       | 0.21%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                     | 11       | 0.21%   |
| AOC 2460G4 AOC2460 1920x1080 531x299mm 24.0-inch                      | 11       | 0.21%   |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                      | 10       | 0.19%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 10       | 0.19%   |
| Acer SB220Q ACR06AB 1920x1080 476x268mm 21.5-inch                     | 10       | 0.19%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch     | 9        | 0.17%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 700x390mm 31.5-inch | 9        | 0.17%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 9        | 0.17%   |
| MSI Optix MAG27C MSI1462 1920x1080 598x336mm 27.0-inch                | 9        | 0.17%   |
| Goldstar ULTRAWIDE GSM76E4 3440x1440 800x335mm 34.1-inch              | 9        | 0.17%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 597x336mm 27.0-inch                | 9        | 0.17%   |
| Dell U2414H DELA0A4 1920x1080 527x296mm 23.8-inch                     | 9        | 0.17%   |
| Dell S2716DG DELA0D1 2560x1440 598x336mm 27.0-inch                    | 9        | 0.17%   |
| BenQ GW2765 BNQ78D6 2560x1440 597x336mm 27.0-inch                     | 9        | 0.17%   |
| ASUSTek Computer VG27A AUS2722 2560x1440 597x336mm 27.0-inch          | 9        | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 2062     | 44.52%  |
| 2560x1440 (QHD)    | 596      | 12.87%  |
| 3840x2160 (4K)     | 548      | 11.83%  |
| 1280x1024 (SXGA)   | 184      | 3.97%   |
| 1680x1050 (WSXGA+) | 177      | 3.82%   |
| 3440x1440          | 156      | 3.37%   |
| 1920x1200 (WUXGA)  | 150      | 3.24%   |
| 1366x768 (WXGA)    | 131      | 2.83%   |
| 1440x900 (WXGA+)   | 113      | 2.44%   |
| 2560x1080          | 106      | 2.29%   |
| 1600x900 (HD+)     | 102      | 2.2%    |
| 1360x768           | 56       | 1.21%   |
| Unknown            | 43       | 0.93%   |
| 3840x1080          | 40       | 0.86%   |
| 1600x1200          | 23       | 0.5%    |
| 2288x1287          | 21       | 0.45%   |
| 1920x540           | 18       | 0.39%   |
| 1024x768 (XGA)     | 18       | 0.39%   |
| 2560x1600          | 15       | 0.32%   |
| 1280x720 (HD)      | 9        | 0.19%   |
| 2048x1152          | 8        | 0.17%   |
| 3840x1600          | 6        | 0.13%   |
| 1280x960           | 6        | 0.13%   |
| 2160x1200          | 4        | 0.09%   |
| 5760x1080          | 3        | 0.06%   |
| 5760x2160          | 2        | 0.04%   |
| 3840x2560          | 2        | 0.04%   |
| 3840x1200          | 2        | 0.04%   |
| 1920x1440          | 2        | 0.04%   |
| 1280x768           | 2        | 0.04%   |
| 7680x2160          | 1        | 0.02%   |
| 7680x1440          | 1        | 0.02%   |
| 7120x1080          | 1        | 0.02%   |
| 6784x2160          | 1        | 0.02%   |
| 6400x2160          | 1        | 0.02%   |
| 6400x1080          | 1        | 0.02%   |
| 5760x1200          | 1        | 0.02%   |
| 5120x1440          | 1        | 0.02%   |
| 4864x2160          | 1        | 0.02%   |
| 4480x1200          | 1        | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 925      | 18.99%  |
| 24      | 829      | 17.02%  |
| 23      | 581      | 11.93%  |
| 21      | 551      | 11.31%  |
| 31      | 262      | 5.38%   |
| 34      | 229      | 4.7%    |
| 19      | 213      | 4.37%   |
| 18      | 154      | 3.16%   |
| 22      | 150      | 3.08%   |
| Unknown | 142      | 2.92%   |
| 20      | 129      | 2.65%   |
| 17      | 70       | 1.44%   |
| 32      | 65       | 1.33%   |
| 72      | 59       | 1.21%   |
| 84      | 54       | 1.11%   |
| 25      | 51       | 1.05%   |
| 15      | 42       | 0.86%   |
| 40      | 40       | 0.82%   |
| 54      | 33       | 0.68%   |
| 48      | 31       | 0.64%   |
| 26      | 24       | 0.49%   |
| 42      | 22       | 0.45%   |
| 28      | 22       | 0.45%   |
| 142     | 19       | 0.39%   |
| 29      | 15       | 0.31%   |
| 35      | 14       | 0.29%   |
| 16      | 13       | 0.27%   |
| 52      | 12       | 0.25%   |
| 49      | 11       | 0.23%   |
| 65      | 10       | 0.21%   |
| 46      | 10       | 0.21%   |
| 36      | 10       | 0.21%   |
| 13      | 10       | 0.21%   |
| 37      | 9        | 0.18%   |
| 39      | 7        | 0.14%   |
| 69      | 6        | 0.12%   |
| 43      | 6        | 0.12%   |
| 33      | 5        | 0.1%    |
| 30      | 5        | 0.1%    |
| 12      | 4        | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 2095     | 45.39%  |
| 401-500        | 1025     | 22.21%  |
| 601-700        | 403      | 8.73%   |
| 701-800        | 309      | 6.69%   |
| 351-400        | 156      | 3.38%   |
| Unknown        | 142      | 3.08%   |
| 1501-2000      | 121      | 2.62%   |
| 1001-1500      | 116      | 2.51%   |
| 301-350        | 110      | 2.38%   |
| 801-900        | 71       | 1.54%   |
| 901-1000       | 34       | 0.74%   |
| More than 2000 | 21       | 0.45%   |
| 201-300        | 13       | 0.28%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 3081     | 72.07%  |
| 16/10   | 510      | 11.93%  |
| 21/9    | 255      | 5.96%   |
| 5/4     | 181      | 4.23%   |
| Unknown | 94       | 2.2%    |
| 4/3     | 63       | 1.47%   |
| 32/9    | 33       | 0.77%   |
| 1.00    | 20       | 0.47%   |
| 6/5     | 16       | 0.37%   |
| 3/2     | 11       | 0.26%   |
| 1.96    | 5        | 0.12%   |
| 0.56    | 2        | 0.05%   |
| 3.20    | 1        | 0.02%   |
| 2.12    | 1        | 0.02%   |
| 0.89    | 1        | 0.02%   |
| 0.80    | 1        | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 1593     | 33.86%  |
| 301-350        | 939      | 19.96%  |
| 351-500        | 589      | 12.52%  |
| 151-200        | 514      | 10.92%  |
| 251-300        | 315      | 6.7%    |
| More than 1000 | 213      | 4.53%   |
| 141-150        | 175      | 3.72%   |
| 501-1000       | 144      | 3.06%   |
| Unknown        | 142      | 3.02%   |
| 101-110        | 39       | 0.83%   |
| 131-140        | 11       | 0.23%   |
| 71-80          | 7        | 0.15%   |
| 121-130        | 7        | 0.15%   |
| 111-120        | 6        | 0.13%   |
| 91-100         | 6        | 0.13%   |
| 81-90          | 5        | 0.11%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 2607     | 58.56%  |
| 101-120       | 1122     | 25.2%   |
| 121-160       | 265      | 5.95%   |
| 1-50          | 187      | 4.2%    |
| Unknown       | 142      | 3.19%   |
| 161-240       | 127      | 2.85%   |
| More than 240 | 2        | 0.04%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 2943     | 69.28%  |
| 2     | 1001     | 23.56%  |
| 0     | 145      | 3.41%   |
| 3     | 136      | 3.2%    |
| 4     | 19       | 0.45%   |
| 5     | 4        | 0.09%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 2421     | 40.42%  |
| Intel                           | 2064     | 34.46%  |
| Qualcomm Atheros                | 330      | 5.51%   |
| Broadcom                        | 169      | 2.82%   |
| TP-Link                         | 129      | 2.15%   |
| Ralink Technology               | 108      | 1.8%    |
| MediaTek                        | 93       | 1.55%   |
| Ralink                          | 59       | 0.98%   |
| Microsoft                       | 59       | 0.98%   |
| Aquantia                        | 57       | 0.95%   |
| Nvidia                          | 44       | 0.73%   |
| Qualcomm Atheros Communications | 35       | 0.58%   |
| ASUSTek Computer                | 31       | 0.52%   |
| NetGear                         | 26       | 0.43%   |
| Xiaomi                          | 24       | 0.4%    |
| Marvell Technology Group        | 24       | 0.4%    |
| D-Link                          | 24       | 0.4%    |
| Samsung Electronics             | 23       | 0.38%   |
| Edimax Technology               | 16       | 0.27%   |
| Google                          | 15       | 0.25%   |
| ASIX Electronics                | 14       | 0.23%   |
| Mellanox Technologies           | 13       | 0.22%   |
| Huawei Technologies             | 12       | 0.2%    |
| Broadcom Limited                | 11       | 0.18%   |
| Motorola PCS                    | 10       | 0.17%   |
| Linksys                         | 9        | 0.15%   |
| D-Link System                   | 9        | 0.15%   |
| DisplayLink                     | 8        | 0.13%   |
| Arduino SA                      | 8        | 0.13%   |
| Qualcomm                        | 7        | 0.12%   |
| ICS Advent                      | 7        | 0.12%   |
| Belkin Components               | 7        | 0.12%   |
| Apple                           | 7        | 0.12%   |
| Wilocity                        | 6        | 0.1%    |
| AVM                             | 6        | 0.1%    |
| OPPO Electronics                | 5        | 0.08%   |
| Microchip Technology            | 5        | 0.08%   |
| InterBiometrics                 | 5        | 0.08%   |
| HMD Global                      | 5        | 0.08%   |
| 3Com                            | 4        | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1890     | 27.23%  |
| Intel I211 Gigabit Network Connection                             | 408      | 5.88%   |
| Intel Wi-Fi 6 AX200                                               | 387      | 5.58%   |
| Realtek RTL8125 2.5GbE Controller                                 | 290      | 4.18%   |
| Intel Ethernet Connection (2) I219-V                              | 224      | 3.23%   |
| Intel Ethernet Controller I225-V                                  | 192      | 2.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 140      | 2.02%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 116      | 1.67%   |
| Intel Ethernet Connection (7) I219-V                              | 101      | 1.46%   |
| Intel Ethernet Connection I217-LM                                 | 84       | 1.21%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 79       | 1.14%   |
| Intel Wireless-AC 9260                                            | 74       | 1.07%   |
| Intel Ethernet Connection (2) I218-V                              | 72       | 1.04%   |
| Intel Ethernet Connection (2) I219-LM                             | 58       | 0.84%   |
| Intel 82579V Gigabit Network Connection                           | 57       | 0.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 54       | 0.78%   |
| Intel 82574L Gigabit Network Connection                           | 52       | 0.75%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 47       | 0.68%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 46       | 0.66%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 45       | 0.65%   |
| Intel Ethernet Connection I217-V                                  | 44       | 0.63%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 44       | 0.63%   |
| Ralink MT7601U Wireless Adapter                                   | 43       | 0.62%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 39       | 0.56%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 39       | 0.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 37       | 0.53%   |
| Intel Wireless 7260                                               | 37       | 0.53%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 36       | 0.52%   |
| Intel Wireless 8260                                               | 33       | 0.48%   |
| Realtek 802.11ac NIC                                              | 31       | 0.45%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 31       | 0.45%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 30       | 0.43%   |
| Intel Wireless 7265                                               | 29       | 0.42%   |
| Intel I210 Gigabit Network Connection                             | 27       | 0.39%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 26       | 0.37%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 26       | 0.37%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 25       | 0.36%   |
| Qualcomm Atheros AR9271 802.11n                                   | 25       | 0.36%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 25       | 0.36%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 25       | 0.36%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 947      | 43.44%  |
| Realtek Semiconductor                 | 338      | 15.5%   |
| Qualcomm Atheros                      | 180      | 8.26%   |
| TP-Link                               | 127      | 5.83%   |
| Ralink Technology                     | 108      | 4.95%   |
| MediaTek                              | 92       | 4.22%   |
| Broadcom                              | 86       | 3.94%   |
| Ralink                                | 59       | 2.71%   |
| Microsoft                             | 58       | 2.66%   |
| Qualcomm Atheros Communications       | 35       | 1.61%   |
| ASUSTek Computer                      | 29       | 1.33%   |
| NetGear                               | 25       | 1.15%   |
| D-Link                                | 20       | 0.92%   |
| Edimax Technology                     | 16       | 0.73%   |
| Linksys                               | 9        | 0.41%   |
| Belkin Components                     | 7        | 0.32%   |
| Wilocity                              | 6        | 0.28%   |
| D-Link System                         | 6        | 0.28%   |
| AVM                                   | 6        | 0.28%   |
| Broadcom Limited                      | 4        | 0.18%   |
| IMC Networks                          | 3        | 0.14%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3        | 0.14%   |
| Xiaomi                                | 2        | 0.09%   |
| Mercucys                              | 2        | 0.09%   |
| BUFFALO                               | 2        | 0.09%   |
| AboCom Systems                        | 2        | 0.09%   |
| ZyDAS                                 | 1        | 0.05%   |
| ZTE WCDMA Technologies MSM            | 1        | 0.05%   |
| Toshiba                               | 1        | 0.05%   |
| Sitecom Europe                        | 1        | 0.05%   |
| Sierra Wireless                       | 1        | 0.05%   |
| Samsung Electronics                   | 1        | 0.05%   |
| PLANEX                                | 1        | 0.05%   |
| Gemtek                                | 1        | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 387      | 17.57%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 116      | 5.27%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 79       | 3.59%   |
| Intel Wireless-AC 9260                                         | 74       | 3.36%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 45       | 2.04%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 44       | 2%      |
| Ralink MT7601U Wireless Adapter                                | 43       | 1.95%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 39       | 1.77%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 39       | 1.77%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 37       | 1.68%   |
| Intel Wireless 7260                                            | 37       | 1.68%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 36       | 1.63%   |
| Intel Wireless 8260                                            | 33       | 1.5%    |
| Realtek 802.11ac NIC                                           | 31       | 1.41%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 31       | 1.41%   |
| Intel Wireless 7265                                            | 29       | 1.32%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 26       | 1.18%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 25       | 1.14%   |
| Qualcomm Atheros AR9271 802.11n                                | 25       | 1.14%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 25       | 1.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 24       | 1.09%   |
| Intel Wireless 8265 / 8275                                     | 24       | 1.09%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 23       | 1.04%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 23       | 1.04%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 22       | 1%      |
| Ralink RT5370 Wireless Adapter                                 | 22       | 1%      |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 22       | 1%      |
| Microsoft Xbox Wireless Adapter for Windows                    | 22       | 1%      |
| Intel Wireless 3165                                            | 21       | 0.95%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 20       | 0.91%   |
| Microsoft Xbox 360 Wireless Adapter                            | 20       | 0.91%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 18       | 0.82%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 17       | 0.77%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 17       | 0.77%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 16       | 0.73%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 16       | 0.73%   |
| TP-Link Archer T4U ver.3                                       | 15       | 0.68%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 15       | 0.68%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 15       | 0.68%   |
| Microsoft Wireless XBox Controller Dongle                      | 15       | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 2278     | 50.79%  |
| Intel                                  | 1636     | 36.48%  |
| Qualcomm Atheros                       | 168      | 3.75%   |
| Broadcom                               | 84       | 1.87%   |
| Aquantia                               | 57       | 1.27%   |
| Nvidia                                 | 44       | 0.98%   |
| Marvell Technology Group               | 24       | 0.54%   |
| Xiaomi                                 | 22       | 0.49%   |
| Samsung Electronics                    | 22       | 0.49%   |
| Google                                 | 15       | 0.33%   |
| ASIX Electronics                       | 14       | 0.31%   |
| Mellanox Technologies                  | 11       | 0.25%   |
| Motorola PCS                           | 9        | 0.2%    |
| DisplayLink                            | 8        | 0.18%   |
| Qualcomm                               | 7        | 0.16%   |
| ICS Advent                             | 7        | 0.16%   |
| Huawei Technologies                    | 7        | 0.16%   |
| Broadcom Limited                       | 7        | 0.16%   |
| Apple                                  | 7        | 0.16%   |
| OPPO Electronics                       | 5        | 0.11%   |
| HMD Global                             | 5        | 0.11%   |
| D-Link                                 | 4        | 0.09%   |
| 3Com                                   | 4        | 0.09%   |
| VIA Technologies                       | 3        | 0.07%   |
| D-Link System                          | 3        | 0.07%   |
| ADMtek                                 | 3        | 0.07%   |
| ZTE WCDMA Technologies MSM             | 2        | 0.04%   |
| TP-Link                                | 2        | 0.04%   |
| Sundance Technology Inc / IC Plus      | 2        | 0.04%   |
| Sony Ericsson Mobile Communications AB | 2        | 0.04%   |
| OnePlus Technology (Shenzhen)          | 2        | 0.04%   |
| National Semiconductor                 | 2        | 0.04%   |
| Lenovo                                 | 2        | 0.04%   |
| Davicom Semiconductor                  | 2        | 0.04%   |
| ASUSTek Computer                       | 2        | 0.04%   |
| Accton Technology                      | 2        | 0.04%   |
| Xilinx                                 | 1        | 0.02%   |
| vivo                                   | 1        | 0.02%   |
| Tehuti Networks                        | 1        | 0.02%   |
| QNAP System                            | 1        | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 1890     | 40.4%   |
| Intel I211 Gigabit Network Connection                                         | 408      | 8.72%   |
| Realtek RTL8125 2.5GbE Controller                                             | 290      | 6.2%    |
| Intel Ethernet Connection (2) I219-V                                          | 224      | 4.79%   |
| Intel Ethernet Controller I225-V                                              | 192      | 4.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 140      | 2.99%   |
| Intel Ethernet Connection (7) I219-V                                          | 101      | 2.16%   |
| Intel Ethernet Connection I217-LM                                             | 84       | 1.8%    |
| Intel Ethernet Connection (2) I218-V                                          | 72       | 1.54%   |
| Intel Ethernet Connection (2) I219-LM                                         | 58       | 1.24%   |
| Intel 82579V Gigabit Network Connection                                       | 57       | 1.22%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 54       | 1.15%   |
| Intel 82574L Gigabit Network Connection                                       | 52       | 1.11%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 47       | 1%      |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 46       | 0.98%   |
| Intel Ethernet Connection I217-V                                              | 44       | 0.94%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 30       | 0.64%   |
| Intel I210 Gigabit Network Connection                                         | 27       | 0.58%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 26       | 0.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 25       | 0.53%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 23       | 0.49%   |
| Intel Ethernet Connection (7) I219-LM                                         | 22       | 0.47%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 20       | 0.43%   |
| Nvidia MCP61 Ethernet                                                         | 20       | 0.43%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 19       | 0.41%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 19       | 0.41%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 18       | 0.38%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 16       | 0.34%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 16       | 0.34%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]           | 16       | 0.34%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 15       | 0.32%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                     | 14       | 0.3%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 14       | 0.3%    |
| Intel 82566DM-2 Gigabit Network Connection                                    | 13       | 0.28%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 12       | 0.26%   |
| Intel Ethernet Connection (2) I218-LM                                         | 12       | 0.26%   |
| Intel Ethernet Connection (14) I219-V                                         | 12       | 0.26%   |
| Intel 82578DM Gigabit Network Connection                                      | 12       | 0.26%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 12       | 0.26%   |
| ASIX AX88179 Gigabit Ethernet                                                 | 12       | 0.26%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 4076     | 66.18%  |
| WiFi     | 2024     | 32.86%  |
| Modem    | 51       | 0.83%   |
| Unknown  | 8        | 0.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 3257     | 74.62%  |
| WiFi     | 1108     | 25.38%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 2345     | 56.25%  |
| 2     | 1487     | 35.67%  |
| 3     | 249      | 5.97%   |
| 4     | 36       | 0.86%   |
| 0     | 27       | 0.65%   |
| 5     | 15       | 0.36%   |
| 6     | 7        | 0.17%   |
| 9     | 2        | 0.05%   |
| 8     | 1        | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Desktops | Percent |
|---------|----------|---------|
| No      | 3374     | 79.99%  |
| Yes     | 841      | 19.94%  |
| Unknown | 3        | 0.07%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 884      | 48.17%  |
| Cambridge Silicon Radio         | 372      | 20.27%  |
| ASUSTek Computer                | 128      | 6.98%   |
| Realtek Semiconductor           | 114      | 6.21%   |
| Broadcom                        | 87       | 4.74%   |
| MediaTek                        | 57       | 3.11%   |
| Qualcomm Atheros Communications | 43       | 2.34%   |
| TP-Link                         | 30       | 1.63%   |
| IMC Networks                    | 29       | 1.58%   |
| Apple                           | 19       | 1.04%   |
| Foxconn / Hon Hai               | 14       | 0.76%   |
| Belkin Components               | 8        | 0.44%   |
| HTC (High Tech Computer)        | 7        | 0.38%   |
| Edimax Technology               | 7        | 0.38%   |
| Lite-On Technology              | 6        | 0.33%   |
| Integrated System Solution      | 5        | 0.27%   |
| Dynex                           | 4        | 0.22%   |
| Toshiba                         | 3        | 0.16%   |
| Hewlett-Packard                 | 3        | 0.16%   |
| Dell                            | 3        | 0.16%   |
| SINO WEALTH                     | 2        | 0.11%   |
| Unknown                         | 2        | 0.11%   |
| Realtek                         | 1        | 0.05%   |
| Kensington                      | 1        | 0.05%   |
| Foxconn International           | 1        | 0.05%   |
| D-Link System                   | 1        | 0.05%   |
| D-Link                          | 1        | 0.05%   |
| Creative Technology             | 1        | 0.05%   |
| BUFFALO                         | 1        | 0.05%   |
| Actions                         | 1        | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 372      | 20.22%  |
| Intel AX200 Bluetooth                                                | 364      | 19.78%  |
| Intel Bluetooth wireless interface                                   | 145      | 7.88%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 114      | 6.2%    |
| Realtek Bluetooth Radio                                              | 88       | 4.78%   |
| Intel AX210 Bluetooth                                                | 74       | 4.02%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 70       | 3.8%    |
| Intel AX201 Bluetooth                                                | 65       | 3.53%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 60       | 3.26%   |
| MediaTek Wireless_Device                                             | 57       | 3.1%    |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 42       | 2.28%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 35       | 1.9%    |
| TP-Link UB5A Adapter                                                 | 30       | 1.63%   |
| ASUS Bluetooth Radio                                                 | 22       | 1.2%    |
| ASUS ASUS USB-BT500                                                  | 19       | 1.03%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 18       | 0.98%   |
| Qualcomm Atheros  Bluetooth Device                                   | 15       | 0.82%   |
| Intel Bluetooth Device                                               | 15       | 0.82%   |
| ASUS Bluetooth Adapter                                               | 15       | 0.82%   |
| Apple Bluetooth Host Controller                                      | 13       | 0.71%   |
| Foxconn / Hon Hai Wireless_Device                                    | 12       | 0.65%   |
| ASUS BCM20702A0                                                      | 11       | 0.6%    |
| IMC Networks Wireless_Device                                         | 10       | 0.54%   |
| Qualcomm Atheros AR9462 Bluetooth                                    | 9        | 0.49%   |
| IMC Networks Bluetooth Radio                                         | 9        | 0.49%   |
| ASUS Bluetooth Device                                                | 8        | 0.43%   |
| Qualcomm Atheros Bluetooth USB Host Controller                       | 7        | 0.38%   |
| IMC Networks Bluetooth Device                                        | 7        | 0.38%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 7        | 0.38%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 7        | 0.38%   |
| Realtek RTL8821A Bluetooth                                           | 6        | 0.33%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 6        | 0.33%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 6        | 0.33%   |
| Edimax Bluetooth Adapter                                             | 6        | 0.33%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter                     | 6        | 0.33%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 5        | 0.27%   |
| Broadcom BCM2045 Bluetooth                                           | 5        | 0.27%   |
| Lite-On Bluetooth Device                                             | 4        | 0.22%   |
| Integrated System Solution Bluetooth Device                          | 4        | 0.22%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]             | 4        | 0.22%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 2231     | 28.81%  |
| Intel                                | 2209     | 28.52%  |
| Nvidia                               | 1717     | 22.17%  |
| C-Media Electronics                  | 265      | 3.42%   |
| Logitech                             | 126      | 1.63%   |
| Creative Labs                        | 85       | 1.1%    |
| JMTek                                | 59       | 0.76%   |
| SteelSeries ApS                      | 55       | 0.71%   |
| Kingston Technology                  | 53       | 0.68%   |
| Focusrite-Novation                   | 53       | 0.68%   |
| Razer USA                            | 50       | 0.65%   |
| Texas Instruments                    | 49       | 0.63%   |
| Corsair                              | 46       | 0.59%   |
| ASUSTek Computer                     | 46       | 0.59%   |
| Creative Technology                  | 42       | 0.54%   |
| Generalplus Technology               | 37       | 0.48%   |
| GN Netcom                            | 30       | 0.39%   |
| Plantronics                          | 26       | 0.34%   |
| Blue Microphones                     | 25       | 0.32%   |
| Micro Star International             | 24       | 0.31%   |
| Realtek Semiconductor                | 23       | 0.3%    |
| Sony                                 | 22       | 0.28%   |
| GYROCOM C&C                          | 20       | 0.26%   |
| Samson Technologies                  | 18       | 0.23%   |
| RODE Microphones                     | 15       | 0.19%   |
| XMOS                                 | 14       | 0.18%   |
| Tenx Technology                      | 13       | 0.17%   |
| Giga-Byte Technology                 | 13       | 0.17%   |
| Dell                                 | 13       | 0.17%   |
| Cambridge Silicon Radio              | 12       | 0.15%   |
| VIA Technologies                     | 11       | 0.14%   |
| Schiit Audio                         | 11       | 0.14%   |
| DSEA A/S                             | 11       | 0.14%   |
| Yamaha                               | 10       | 0.13%   |
| FiiO Electronics Technology          | 9        | 0.12%   |
| SAVITECH                             | 8        | 0.1%    |
| M-Audio                              | 8        | 0.1%    |
| Lenovo                               | 8        | 0.1%    |
| BEHRINGER International              | 8        | 0.1%    |
| Thesycon Systemsoftware & Consulting | 7        | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 692      | 7.51%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 352      | 3.82%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 338      | 3.67%   |
| AMD Family 17h/19h HD Audio Controller                                     | 315      | 3.42%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 280      | 3.04%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 251      | 2.72%   |
| Intel 200 Series PCH HD Audio                                              | 248      | 2.69%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 237      | 2.57%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 219      | 2.38%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 216      | 2.34%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 204      | 2.21%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 187      | 2.03%   |
| Intel Cannon Lake PCH cAVS                                                 | 180      | 1.95%   |
| Nvidia GP107GL High Definition Audio Controller                            | 173      | 1.88%   |
| AMD Navi 10 HDMI Audio                                                     | 162      | 1.76%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 148      | 1.61%   |
| Nvidia GP106 High Definition Audio Controller                              | 146      | 1.58%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 138      | 1.5%    |
| Nvidia GP104 High Definition Audio Controller                              | 122      | 1.32%   |
| Nvidia TU116 High Definition Audio Controller                              | 117      | 1.27%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 111      | 1.2%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 110      | 1.19%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 102      | 1.11%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 100      | 1.09%   |
| Intel Alder Lake-S HD Audio Controller                                     | 96       | 1.04%   |
| AMD FCH Azalia Controller                                                  | 90       | 0.98%   |
| Nvidia GA104 High Definition Audio Controller                              | 88       | 0.95%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 81       | 0.88%   |
| Nvidia TU106 High Definition Audio Controller                              | 77       | 0.84%   |
| Nvidia High Definition Audio Controller                                    | 72       | 0.78%   |
| Nvidia TU104 HD Audio Controller                                           | 71       | 0.77%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 65       | 0.71%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 65       | 0.71%   |
| Nvidia GM206 High Definition Audio Controller                              | 62       | 0.67%   |
| Nvidia GM204 High Definition Audio Controller                              | 61       | 0.66%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 61       | 0.66%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 60       | 0.65%   |
| Nvidia GP108 High Definition Audio Controller                              | 58       | 0.63%   |
| Nvidia GK107 HDMI Audio Controller                                         | 55       | 0.6%    |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 55       | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 407      | 18.89%  |
| Corsair             | 368      | 17.08%  |
| G.Skill             | 274      | 12.71%  |
| Unknown             | 209      | 9.7%    |
| Crucial             | 168      | 7.8%    |
| Samsung Electronics | 160      | 7.42%   |
| SK hynix            | 150      | 6.96%   |
| Micron Technology   | 90       | 4.18%   |
| A-DATA Technology   | 54       | 2.51%   |
| Team                | 42       | 1.95%   |
| Patriot             | 35       | 1.62%   |
| Unknown             | 20       | 0.93%   |
| Ramaxel Technology  | 15       | 0.7%    |
| Smart               | 14       | 0.65%   |
| Nanya Technology    | 13       | 0.6%    |
| Elpida              | 10       | 0.46%   |
| GeIL                | 9        | 0.42%   |
| GOODRAM             | 8        | 0.37%   |
| AMD                 | 8        | 0.37%   |
| PNY                 | 7        | 0.32%   |
| Transcend           | 6        | 0.28%   |
| Silicon Power       | 6        | 0.28%   |
| Apacer              | 6        | 0.28%   |
| Qumo                | 4        | 0.19%   |
| Qimonda             | 4        | 0.19%   |
| Avant               | 4        | 0.19%   |
| Unifosa             | 3        | 0.14%   |
| CSX                 | 3        | 0.14%   |
| Unknown (ABCD)      | 2        | 0.09%   |
| Timetec             | 2        | 0.09%   |
| TakeMS              | 2        | 0.09%   |
| Sesame              | 2        | 0.09%   |
| Patriot Memory      | 2        | 0.09%   |
| OCZ                 | 2        | 0.09%   |
| Mushkin             | 2        | 0.09%   |
| MINPO               | 2        | 0.09%   |
| Goldkey             | 2        | 0.09%   |
| Golden Empire       | 2        | 0.09%   |
| Gold Key            | 2        | 0.09%   |
| Atermiter           | 2        | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s   | 40       | 1.71%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s   | 26       | 1.11%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s    | 23       | 0.98%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s    | 22       | 0.94%   |
| Unknown                                                 | 20       | 0.85%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s       | 18       | 0.77%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s     | 18       | 0.77%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s  | 17       | 0.73%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                    | 16       | 0.68%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s     | 15       | 0.64%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s     | 14       | 0.6%    |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s    | 13       | 0.56%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s  | 13       | 0.56%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                | 12       | 0.51%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s       | 11       | 0.47%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s     | 11       | 0.47%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s  | 11       | 0.47%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s    | 10       | 0.43%   |
| Patriot RAM 3200 C16 Series 16GB DIMM DDR4 3266MT/s     | 10       | 0.43%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s   | 10       | 0.43%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3800MT/s  | 10       | 0.43%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s             | 10       | 0.43%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s               | 9        | 0.38%   |
| Unknown RAM Module 2GB DIMM 800MT/s                     | 9        | 0.38%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s  | 9        | 0.38%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s     | 9        | 0.38%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s   | 9        | 0.38%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s    | 8        | 0.34%   |
| Kingston RAM KHX2133C14/8G 8192MB DIMM DDR4 2400MT/s    | 8        | 0.34%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s   | 8        | 0.34%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s      | 8        | 0.34%   |
| G.Skill RAM F4-2400C15-8GVR 8GB DIMM DDR4 3200MT/s      | 8        | 0.34%   |
| G.Skill RAM F3-12800CL10-8GBXL 8GB DIMM DDR3 1600MT/s   | 8        | 0.34%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s  | 8        | 0.34%   |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3100MT/s  | 8        | 0.34%   |
| Unknown RAM Module 2GB DIMM SDRAM                       | 7        | 0.3%    |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s      | 7        | 0.3%    |
| Smart RAM SH564128FH8N0TNSDR 4GB DIMM DDR3 1600MT/s     | 7        | 0.3%    |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s     | 7        | 0.3%    |
| Samsung RAM M378A2K43CB1-CTD 16384MB DIMM DDR4 3200MT/s | 7        | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 1120     | 58.12%  |
| DDR3    | 529      | 27.45%  |
| Unknown | 92       | 4.77%   |
| DDR2    | 68       | 3.53%   |
| DDR5    | 54       | 2.8%    |
| SDRAM   | 46       | 2.39%   |
| DDR     | 10       | 0.52%   |
| LPDDR3  | 3        | 0.16%   |
| DRAM    | 3        | 0.16%   |
| LPDDR4  | 2        | 0.1%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 1796     | 94.48%  |
| SODIMM       | 90       | 4.73%   |
| RIMM         | 10       | 0.53%   |
| FB-DIMM      | 3        | 0.16%   |
| Row Of Chips | 2        | 0.11%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 851      | 41.13%  |
| 16384 | 449      | 21.7%   |
| 4096  | 404      | 19.53%  |
| 2048  | 184      | 8.89%   |
| 32768 | 136      | 6.57%   |
| 1024  | 40       | 1.93%   |
| 512   | 4        | 0.19%   |
| 256   | 1        | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 301      | 14.22%  |
| 3200    | 278      | 13.14%  |
| 3600    | 218      | 10.3%   |
| 1333    | 173      | 8.18%   |
| 2400    | 134      | 6.33%   |
| 2133    | 104      | 4.91%   |
| 2667    | 94       | 4.44%   |
| 800     | 61       | 2.88%   |
| 3400    | 53       | 2.5%    |
| 3000    | 53       | 2.5%    |
| 667     | 45       | 2.13%   |
| 1867    | 44       | 2.08%   |
| 3800    | 33       | 1.56%   |
| 2666    | 31       | 1.47%   |
| 3733    | 30       | 1.42%   |
| 1866    | 29       | 1.37%   |
| 1800    | 29       | 1.37%   |
| 3866    | 28       | 1.32%   |
| 3533    | 28       | 1.32%   |
| 2800    | 26       | 1.23%   |
| Unknown | 26       | 1.23%   |
| 3466    | 24       | 1.13%   |
| 2933    | 24       | 1.13%   |
| 4800    | 22       | 1.04%   |
| 1066    | 18       | 0.85%   |
| 3666    | 17       | 0.8%    |
| 3266    | 14       | 0.66%   |
| 1067    | 12       | 0.57%   |
| 5200    | 10       | 0.47%   |
| 3100    | 9        | 0.43%   |
| 3534    | 8        | 0.38%   |
| 1334    | 8        | 0.38%   |
| 6000    | 7        | 0.33%   |
| 3334    | 7        | 0.33%   |
| 2733    | 7        | 0.33%   |
| 4000    | 6        | 0.28%   |
| 3333    | 6        | 0.28%   |
| 533     | 6        | 0.28%   |
| 2000    | 5        | 0.24%   |
| 400     | 5        | 0.24%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 70       | 38.67%  |
| Brother Industries    | 44       | 24.31%  |
| Canon                 | 18       | 9.94%   |
| Seiko Epson           | 13       | 7.18%   |
| Samsung Electronics   | 13       | 7.18%   |
| Prolific Technology   | 5        | 2.76%   |
| Lexmark International | 4        | 2.21%   |
| Dymo-CoStar           | 4        | 2.21%   |
| Xerox                 | 2        | 1.1%    |
| Kyocera               | 2        | 1.1%    |
| Star Micronics        | 1        | 0.55%   |
| QinHeng Electronics   | 1        | 0.55%   |
| Pantum                | 1        | 0.55%   |
| Graphtec America      | 1        | 0.55%   |
| Dell                  | 1        | 0.55%   |
| Boca Systems          | 1        | 0.55%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Samsung M2070 Series                         | 5        | 2.75%   |
| Prolific PL2305 Parallel Port                | 5        | 2.75%   |
| HP LaserJet Professional P 1102w             | 4        | 2.2%    |
| HP ENVY 5000 series                          | 4        | 2.2%    |
| Brother HL-L2340D series                     | 4        | 2.2%    |
| HP ENVY 4520 series                          | 3        | 1.65%   |
| HP DeskJet F300 series                       | 3        | 1.65%   |
| HP DeskJet 3700 series                       | 3        | 1.65%   |
| Brother Printer                              | 3        | 1.65%   |
| Brother HL-1110 series                       | 3        | 1.65%   |
| Seiko Epson WF-2860 Series                   | 2        | 1.1%    |
| Seiko Epson Printer                          | 2        | 1.1%    |
| Samsung ML-216x Series Laser Printer         | 2        | 1.1%    |
| HP OfficeJet 6950                            | 2        | 1.1%    |
| HP LaserJet Professional P1102w              | 2        | 1.1%    |
| HP LaserJet 1020                             | 2        | 1.1%    |
| HP LaserJet 1010                             | 2        | 1.1%    |
| HP DeskJet 3630 series                       | 2        | 1.1%    |
| HP DeskJet 2700 series                       | 2        | 1.1%    |
| HP DeskJet 2600 series                       | 2        | 1.1%    |
| HP DeskJet 2130 series                       | 2        | 1.1%    |
| Dymo-CoStar DYMO LabelWriter 450 Turbo       | 2        | 1.1%    |
| Canon TS3300 series                          | 2        | 1.1%    |
| Canon TR4500 series                          | 2        | 1.1%    |
| Canon LiDE 300                               | 2        | 1.1%    |
| Brother MFC-9330CDW                          | 2        | 1.1%    |
| Brother HL-2230 series                       | 2        | 1.1%    |
| Brother HL-2030 Laser Printer                | 2        | 1.1%    |
| Brother HL-1440 Laser Printer                | 2        | 1.1%    |
| Xerox Phaser 6500DN                          | 1        | 0.55%   |
| Xerox Phaser 3010                            | 1        | 0.55%   |
| Star Micronics TUP592 (STR_T-001)            | 1        | 0.55%   |
| Seiko Epson XP-100 Series                    | 1        | 0.55%   |
| Seiko Epson WP-4020 Series                   | 1        | 0.55%   |
| Seiko Epson WF-2510 Series                   | 1        | 0.55%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1        | 0.55%   |
| Seiko Epson L360 Series                      | 1        | 0.55%   |
| Seiko Epson L3110 Series                     | 1        | 0.55%   |
| Seiko Epson L300 Series                      | 1        | 0.55%   |
| Seiko Epson L120 Series                      | 1        | 0.55%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 24       | 55.81%  |
| Seiko Epson     | 13       | 30.23%  |
| Hewlett-Packard | 4        | 9.3%    |
| UMAX            | 1        | 2.33%   |
| Mustek Systems  | 1        | 2.33%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Seiko Epson GT-X770 [Perfection V500]                    | 5        | 11.63%  |
| Canon CanoScan LiDE 210                                  | 5        | 11.63%  |
| Canon CanoScan LIDE 25                                   | 3        | 6.98%   |
| Canon CanoScan LiDE 220                                  | 3        | 6.98%   |
| Canon CanoScan LiDE 100                                  | 3        | 6.98%   |
| Seiko Epson GT-6600U [Perfection 610]                    | 2        | 4.65%   |
| Canon CanoScan N670U/N676U/LiDE 20                       | 2        | 4.65%   |
| Canon CanoScan LiDE 110                                  | 2        | 4.65%   |
| Canon CanoScan 4400F                                     | 2        | 4.65%   |
| UMAX Astra 2200/2200SU                                   | 1        | 2.33%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]              | 1        | 2.33%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]              | 1        | 2.33%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo]  | 1        | 2.33%   |
| Seiko Epson GT-F670 [Perfection V200 Photo]              | 1        | 2.33%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1        | 2.33%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]            | 1        | 2.33%   |
| Mustek Systems BearPaw 2448 TA Plus                      | 1        | 2.33%   |
| HP ScanJet G4050                                         | 1        | 2.33%   |
| HP ScanJet 5590                                          | 1        | 2.33%   |
| HP ScanJet 3400cse                                       | 1        | 2.33%   |
| HP ScanJet 2400c                                         | 1        | 2.33%   |
| Canon CanoScan N1240U/LiDE 30                            | 1        | 2.33%   |
| Canon CanoScan LiDE 70                                   | 1        | 2.33%   |
| Canon CanoScan LiDE 200                                  | 1        | 2.33%   |
| Canon CanoScan LiDE 120                                  | 1        | 2.33%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 486      | 45.59%  |
| Microsoft                              | 82       | 7.69%   |
| Microdia                               | 65       | 6.1%    |
| Apple                                  | 37       | 3.47%   |
| Samsung Electronics                    | 35       | 3.28%   |
| Sunplus Innovation Technology          | 32       | 3%      |
| Realtek Semiconductor                  | 23       | 2.16%   |
| KYE Systems (Mouse Systems)            | 21       | 1.97%   |
| Chicony Electronics                    | 19       | 1.78%   |
| Generalplus Technology                 | 16       | 1.5%    |
| Creative Technology                    | 15       | 1.41%   |
| Cubeternet                             | 14       | 1.31%   |
| ARC International                      | 14       | 1.31%   |
| webcamvendor                           | 12       | 1.13%   |
| Z-Star Microelectronics                | 11       | 1.03%   |
| AVerMedia Technologies                 | 11       | 1.03%   |
| Trust                                  | 10       | 0.94%   |
| Razer USA                              | 10       | 0.94%   |
| Jieli Technology                       | 10       | 0.94%   |
| Hewlett-Packard                        | 8        | 0.75%   |
| MacroSilicon                           | 7        | 0.66%   |
| Lenovo                                 | 7        | 0.66%   |
| GEMBIRD                                | 7        | 0.66%   |
| LG Electronics                         | 5        | 0.47%   |
| Aveo Technology                        | 5        | 0.47%   |
| Arkmicro Technologies                  | 5        | 0.47%   |
| SunplusIT                              | 4        | 0.38%   |
| Google                                 | 4        | 0.38%   |
| Asuscom Network                        | 4        | 0.38%   |
| Alcor Micro                            | 4        | 0.38%   |
| Unknown                                | 4        | 0.38%   |
| Valve Software                         | 3        | 0.28%   |
| Unknown                                | 3        | 0.28%   |
| Tobii Technology AB                    | 3        | 0.28%   |
| OmniVision Technologies                | 3        | 0.28%   |
| Huawei Technologies                    | 3        | 0.28%   |
| Genesys Logic                          | 3        | 0.28%   |
| Cheng Uei Precision Industry (Foxlink) | 3        | 0.28%   |
| A4Tech                                 | 3        | 0.28%   |
| XHT-211220-ZW                          | 2        | 0.19%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                | 121      | 11.21%  |
| Logitech Webcam C270                       | 99       | 9.18%   |
| Samsung Galaxy series, misc. (MTP mode)    | 34       | 3.15%   |
| Logitech HD Webcam C525                    | 32       | 2.97%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR         | 32       | 2.97%   |
| Microsoft LifeCam HD-3000                  | 28       | 2.59%   |
| Logitech C922 Pro Stream Webcam            | 26       | 2.41%   |
| Microdia Webcam Vitade AF                  | 24       | 2.22%   |
| Logitech HD Webcam C615                    | 23       | 2.13%   |
| Logitech Webcam C310                       | 20       | 1.85%   |
| Logitech Webcam C170                       | 20       | 1.85%   |
| Microsoft LifeCam Cinema                   | 18       | 1.67%   |
| Logitech BRIO                              | 17       | 1.58%   |
| Logitech Webcam Pro 9000                   | 15       | 1.39%   |
| Microdia USB 2.0 Camera                    | 14       | 1.3%    |
| ARC International Camera                   | 14       | 1.3%    |
| Logitech Webcam C925e                      | 13       | 1.2%    |
| webcamvendor webcamproduct                 | 12       | 1.11%   |
| Logitech Webcam C930e                      | 11       | 1.02%   |
| Logitech StreamCam                         | 11       | 1.02%   |
| Jieli USB PHY 2.0                          | 10       | 0.93%   |
| Sunplus HD 720P webcam                     | 9        | 0.83%   |
| Realtek Full HD webcam                     | 9        | 0.83%   |
| Generalplus CAMERA - UVC                   | 9        | 0.83%   |
| Microdia Camera                            | 8        | 0.74%   |
| Logitech QuickCam Pro 9000                 | 8        | 0.74%   |
| Logitech BRIO 4K Stream Edition            | 8        | 0.74%   |
| Razer USA Gaming Webcam [Kiyo]             | 7        | 0.65%   |
| AVerMedia Live Streamer CAM 313            | 7        | 0.65%   |
| Trust USB Camera                           | 6        | 0.56%   |
| Microsoft MicrosoftÂ LifeCam Cinema       | 6        | 0.56%   |
| Microsoft LifeCam VX-5000                  | 6        | 0.56%   |
| Microsoft LifeCam Studio                   | 6        | 0.56%   |
| Microdia Integrated Camera                 | 6        | 0.56%   |
| MacroSilicon USB3. 0 capture               | 6        | 0.56%   |
| Logitech HD Webcam C910                    | 6        | 0.56%   |
| Sunplus NexiGo N930AF FHD Webcam           | 5        | 0.46%   |
| Logitech C505 HD Webcam                    | 5        | 0.46%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera | 5        | 0.46%   |
| Creative Live! Cam Sync HD [VF0770]        | 5        | 0.46%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| LighTuning Technology | 3        | 17.65%  |
| Elan Microelectronics | 3        | 17.65%  |
| DigitalPersona        | 3        | 17.65%  |
| AuthenTec             | 3        | 17.65%  |
| Synaptics             | 2        | 11.76%  |
| Upek                  | 1        | 5.88%   |
| Microsoft             | 1        | 5.88%   |
| Dell                  | 1        | 5.88%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Elan fingerprint sensor [FeinTech FPS00200]    | 3        | 17.65%  |
| DigitalPersona Fingerprint Reader              | 3        | 17.65%  |
| Synaptics  WBDI Fingerprint Reader - USB 052   | 2        | 11.76%  |
| LighTuning Fingerprint Sensor                  | 2        | 11.76%  |
| AuthenTec Fingerprint Sensor                   | 2        | 11.76%  |
| Upek TCS1C EIM/STM32 Fingerprint sensor        | 1        | 5.88%   |
| Microsoft Fingerprint Reader                   | 1        | 5.88%   |
| LighTuning EgisTec Touch Fingerprint Sensor    | 1        | 5.88%   |
| Dell MS819 Wired Mouse With Fingerprint Reader | 1        | 5.88%   |
| AuthenTec AES1600                              | 1        | 5.88%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Yubico.com                        | 6        | 15%     |
| Realtek Semiconductor             | 5        | 12.5%   |
| Alcor Micro                       | 5        | 12.5%   |
| SCM Microsystems                  | 4        | 10%     |
| VASCO Data Security International | 3        | 7.5%    |
| OmniKey                           | 3        | 7.5%    |
| Gemalto (was Gemplus)             | 3        | 7.5%    |
| Cherry                            | 2        | 5%      |
| Aktiv                             | 2        | 5%      |
| Reiner SCT Kartensysteme          | 1        | 2.5%    |
| Fujitsu Siemens Computers         | 1        | 2.5%    |
| Feitian Technologies              | 1        | 2.5%    |
| Clay Logic                        | 1        | 2.5%    |
| Chicony Electronics               | 1        | 2.5%    |
| BIT4ID                            | 1        | 2.5%    |
| Advanced Card Systems             | 1        | 2.5%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek Semiconductor Smart Card Reader Interface                          | 5        | 12.5%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                            | 4        | 10%     |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                     | 3        | 7.5%    |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                          | 3        | 7.5%    |
| Alcor Micro AU9540 Smartcard Reader                                        | 3        | 7.5%    |
| VASCO Data Security International Digipass 905 SmartCard Reader            | 2        | 5%      |
| Alcor Micro Watchdata W 1981                                               | 2        | 5%      |
| Aktiv Rutoken lite                                                         | 2        | 5%      |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                        | 1        | 2.5%    |
| Yubico.com Yubikey 4/5 CCID                                                | 1        | 2.5%    |
| VASCO Data Security International DIGIPASS 870                             | 1        | 2.5%    |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                 | 1        | 2.5%    |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 1        | 2.5%    |
| OmniKey CardMan 3121 (HID Technologies)                                    | 1        | 2.5%    |
| OmniKey CardMan 3021 / 3121                                                | 1        | 2.5%    |
| OmniKey CardMan 1021                                                       | 1        | 2.5%    |
| Fujitsu Siemens Computers SmartCard Reader 2A                              | 1        | 2.5%    |
| Feitian Technologies FT SCR310                                             | 1        | 2.5%    |
| Clay Logic Nitrokey Pro                                                    | 1        | 2.5%    |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                       | 1        | 2.5%    |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                | 1        | 2.5%    |
| Cherry Smart Terminal XX44                                                 | 1        | 2.5%    |
| BIT4ID miniLector EVO                                                      | 1        | 2.5%    |
| Advanced Card Systems ACR122U                                              | 1        | 2.5%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 3563     | 84.85%  |
| 1     | 553      | 13.17%  |
| 2     | 56       | 1.33%   |
| 3     | 14       | 0.33%   |
| 4     | 7        | 0.17%   |
| 5     | 4        | 0.1%    |
| 8     | 1        | 0.02%   |
| 6     | 1        | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 207      | 29.4%   |
| Net/wireless             | 200      | 28.41%  |
| Unassigned class         | 67       | 9.52%   |
| Sound                    | 38       | 5.4%    |
| Multimedia controller    | 38       | 5.4%    |
| Camera                   | 34       | 4.83%   |
| Communication controller | 33       | 4.69%   |
| Fingerprint reader       | 16       | 2.27%   |
| Storage/raid             | 12       | 1.7%    |
| Network                  | 11       | 1.56%   |
| Bluetooth                | 11       | 1.56%   |
| Net/ethernet             | 9        | 1.28%   |
| Card reader              | 7        | 0.99%   |
| Modem                    | 5        | 0.71%   |
| Chipcard                 | 5        | 0.71%   |
| Firewire controller      | 4        | 0.57%   |
| Dvb card                 | 2        | 0.28%   |
| Wireless                 | 1        | 0.14%   |
| Tv card                  | 1        | 0.14%   |
| Storage/nvme             | 1        | 0.14%   |
| Storage/ata              | 1        | 0.14%   |
| Storage                  | 1        | 0.14%   |

