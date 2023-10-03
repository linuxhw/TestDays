Ubuntu 22.04 - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu 22.04.

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

Total: 6074

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Colorful T... | BATTLE-AX B365M-D V20       | [f8c7c20100](https://linux-hardware.org/?probe=f8c7c20100) | Oct 01, 2023 |
| Colorful T... | BATTLE-AX B365M-D V20       | [c118982282](https://linux-hardware.org/?probe=c118982282) | Oct 01, 2023 |
| Dell          | 09KPNV A01                  | [38dba6ab76](https://linux-hardware.org/?probe=38dba6ab76) | Oct 01, 2023 |
| ASRock        | FM2A55M-VG3+                | [6faa4fd636](https://linux-hardware.org/?probe=6faa4fd636) | Oct 01, 2023 |
| Acer          | H57M01                      | [77fd0bf30a](https://linux-hardware.org/?probe=77fd0bf30a) | Sep 30, 2023 |
| Colorful T... | BATTLE-AX B365M-D V20       | [e212af9208](https://linux-hardware.org/?probe=e212af9208) | Sep 30, 2023 |
| MSI           | MPG Z390M GAMING EDGE AC    | [04432690a4](https://linux-hardware.org/?probe=04432690a4) | Sep 30, 2023 |
| Gigabyte      | X99-UD3-CF                  | [f1cc7e5a93](https://linux-hardware.org/?probe=f1cc7e5a93) | Sep 30, 2023 |
| Gigabyte      | X99-UD3-CF                  | [51d10770c6](https://linux-hardware.org/?probe=51d10770c6) | Sep 30, 2023 |
| ASRock        | A300M-STX                   | [d8c97108ad](https://linux-hardware.org/?probe=d8c97108ad) | Sep 30, 2023 |
| Acer          | H57M01                      | [d506730eed](https://linux-hardware.org/?probe=d506730eed) | Sep 30, 2023 |
| ASRock        | A300M-STX                   | [bcbf0e5bfd](https://linux-hardware.org/?probe=bcbf0e5bfd) | Sep 30, 2023 |
| Foxconn       | 2AB1                        | [28ef0f3fbc](https://linux-hardware.org/?probe=28ef0f3fbc) | Sep 29, 2023 |
| Acer          | H57M01                      | [ad7b1bf379](https://linux-hardware.org/?probe=ad7b1bf379) | Sep 29, 2023 |
| Acer          | Nitro N50-610               | [a91f602e4a](https://linux-hardware.org/?probe=a91f602e4a) | Sep 29, 2023 |
| Dell          | 0PRR48 A00                  | [52fd06666a](https://linux-hardware.org/?probe=52fd06666a) | Sep 29, 2023 |
| Intel         | B75                         | [a30fa8031b](https://linux-hardware.org/?probe=a30fa8031b) | Sep 29, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [6177caee37](https://linux-hardware.org/?probe=6177caee37) | Sep 29, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [8724efb686](https://linux-hardware.org/?probe=8724efb686) | Sep 29, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [76fc0d8239](https://linux-hardware.org/?probe=76fc0d8239) | Sep 29, 2023 |
| ASUSTek       | M5A97 R2.0                  | [2c2f49b6bf](https://linux-hardware.org/?probe=2c2f49b6bf) | Sep 29, 2023 |
| Gigabyte      | GA-MA780G-UD3H              | [9b86a89bf4](https://linux-hardware.org/?probe=9b86a89bf4) | Sep 29, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [cce7c03059](https://linux-hardware.org/?probe=cce7c03059) | Sep 29, 2023 |
| ASUSTek       | H81M-E                      | [0137140cae](https://linux-hardware.org/?probe=0137140cae) | Sep 28, 2023 |
| Gigabyte      | B150M-D3V-CF                | [75b228c5fb](https://linux-hardware.org/?probe=75b228c5fb) | Sep 28, 2023 |
| Gigabyte      | B360M DS3H                  | [1308430981](https://linux-hardware.org/?probe=1308430981) | Sep 28, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [ce357bee14](https://linux-hardware.org/?probe=ce357bee14) | Sep 28, 2023 |
| Gigabyte      | EX58-EXTREME                | [4a1a75d0e3](https://linux-hardware.org/?probe=4a1a75d0e3) | Sep 28, 2023 |
| GMKtec        | NucBox3                     | [c99750febd](https://linux-hardware.org/?probe=c99750febd) | Sep 28, 2023 |
| Gigabyte      | EX58-EXTREME                | [bc2a9ecc6a](https://linux-hardware.org/?probe=bc2a9ecc6a) | Sep 28, 2023 |
| HP            | 1496                        | [3867e7af58](https://linux-hardware.org/?probe=3867e7af58) | Sep 28, 2023 |
| Wistron       | ProLiant ML110 G6           | [4284ef7737](https://linux-hardware.org/?probe=4284ef7737) | Sep 28, 2023 |
| Acer          | Aspire TC-885 V:1.1         | [7aef46e946](https://linux-hardware.org/?probe=7aef46e946) | Sep 28, 2023 |
| Wistron       | ProLiant ML110 G6           | [6282804553](https://linux-hardware.org/?probe=6282804553) | Sep 28, 2023 |
| Lenovo        | ThinkServer TS140           | [0e08685628](https://linux-hardware.org/?probe=0e08685628) | Sep 28, 2023 |
| Gigabyte      | 970A-DS3P FX                | [627751c21a](https://linux-hardware.org/?probe=627751c21a) | Sep 28, 2023 |
| Lenovo        | ThinkCentre M57 6075Y3W     | [8e39080ed3](https://linux-hardware.org/?probe=8e39080ed3) | Sep 28, 2023 |
| MiTAC         | PD10EHI                     | [29716ecb18](https://linux-hardware.org/?probe=29716ecb18) | Sep 27, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | [e15856c8f1](https://linux-hardware.org/?probe=e15856c8f1) | Sep 27, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [f47347fb9b](https://linux-hardware.org/?probe=f47347fb9b) | Sep 27, 2023 |
| ASUSTek       | PRO H410M-C                 | [6554d255c3](https://linux-hardware.org/?probe=6554d255c3) | Sep 27, 2023 |
| AAEON         | MIX-H310D1 V1.0             | [7a3b3d3b2d](https://linux-hardware.org/?probe=7a3b3d3b2d) | Sep 27, 2023 |
| ASUSTek       | M5A99FX PRO R2.0            | [500909194e](https://linux-hardware.org/?probe=500909194e) | Sep 27, 2023 |
| ASRock        | Z790 Taichi                 | [949be6194e](https://linux-hardware.org/?probe=949be6194e) | Sep 27, 2023 |
| ASRock        | Z790 Taichi                 | [50ff8d28e4](https://linux-hardware.org/?probe=50ff8d28e4) | Sep 26, 2023 |
| MSI           | MAG B550M MORTAR            | [5a2571575f](https://linux-hardware.org/?probe=5a2571575f) | Sep 26, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [9fcff9b281](https://linux-hardware.org/?probe=9fcff9b281) | Sep 26, 2023 |
| Supermicro    | X9DRL-3F/iF                 | [07543468b6](https://linux-hardware.org/?probe=07543468b6) | Sep 26, 2023 |
| Supermicro    | X10DRL-i                    | [4215bb2639](https://linux-hardware.org/?probe=4215bb2639) | Sep 26, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [ac6d6574e9](https://linux-hardware.org/?probe=ac6d6574e9) | Sep 26, 2023 |
| Medion        | D3F3-EM                     | [82989a21af](https://linux-hardware.org/?probe=82989a21af) | Sep 26, 2023 |
| MSI           | MAG B550M MORTAR            | [efee605c17](https://linux-hardware.org/?probe=efee605c17) | Sep 26, 2023 |
| Colorful T... | BATTLE-AX B365M-D V20       | [dfdb4a33bd](https://linux-hardware.org/?probe=dfdb4a33bd) | Sep 26, 2023 |
| Gateway       | FX6840                      | [613810c0ed](https://linux-hardware.org/?probe=613810c0ed) | Sep 26, 2023 |
| MSI           | X299 RAIDER 2018-10-08      | [8bccf1be8d](https://linux-hardware.org/?probe=8bccf1be8d) | Sep 26, 2023 |
| ASUSTek       | M2N-VM DVI                  | [7b8649cccc](https://linux-hardware.org/?probe=7b8649cccc) | Sep 26, 2023 |
| HP            | 3397                        | [e0396e65c6](https://linux-hardware.org/?probe=e0396e65c6) | Sep 26, 2023 |
| Lenovo        | ThinkServer TS140           | [461eeadd52](https://linux-hardware.org/?probe=461eeadd52) | Sep 26, 2023 |
| Supermicro    | X9DRL-3F/iF                 | [cac5990658](https://linux-hardware.org/?probe=cac5990658) | Sep 25, 2023 |
| Dell          | 0KRC95 A02                  | [c0f2f5244b](https://linux-hardware.org/?probe=c0f2f5244b) | Sep 25, 2023 |
| ASUSTek       | G10DK                       | [882b029219](https://linux-hardware.org/?probe=882b029219) | Sep 25, 2023 |
| Dell          | 05GD68 A00                  | [7112169fc8](https://linux-hardware.org/?probe=7112169fc8) | Sep 25, 2023 |
| ASRock        | H81M-DG6                    | [ac6944c3df](https://linux-hardware.org/?probe=ac6944c3df) | Sep 25, 2023 |
| MSI           | Z490-A PRO                  | [7ff4162cbb](https://linux-hardware.org/?probe=7ff4162cbb) | Sep 25, 2023 |
| MSI           | Z490-A PRO                  | [55f54a0aeb](https://linux-hardware.org/?probe=55f54a0aeb) | Sep 25, 2023 |
| Gigabyte      | Z97M-DS3H                   | [2881d9e4ec](https://linux-hardware.org/?probe=2881d9e4ec) | Sep 25, 2023 |
| HP            | 1589                        | [3d151e09bb](https://linux-hardware.org/?probe=3d151e09bb) | Sep 25, 2023 |
| Dell          | 0JP3NX A01                  | [d42f0f6791](https://linux-hardware.org/?probe=d42f0f6791) | Sep 25, 2023 |
| ASRock        | 970 Extreme4                | [4b78e93dff](https://linux-hardware.org/?probe=4b78e93dff) | Sep 25, 2023 |
| ASRock        | 970 Extreme4                | [e05aa71be7](https://linux-hardware.org/?probe=e05aa71be7) | Sep 25, 2023 |
| MSI           | B250M BAZOOKA               | [425bd32230](https://linux-hardware.org/?probe=425bd32230) | Sep 25, 2023 |
| Acer          | RL100                       | [13755a17ee](https://linux-hardware.org/?probe=13755a17ee) | Sep 25, 2023 |
| Gigabyte      | P55-UD4                     | [45d1ad03f8](https://linux-hardware.org/?probe=45d1ad03f8) | Sep 25, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [739be981d6](https://linux-hardware.org/?probe=739be981d6) | Sep 24, 2023 |
| Supermicro    | X9DRL-3F/iF                 | [e9f47778b4](https://linux-hardware.org/?probe=e9f47778b4) | Sep 24, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [7a121f2a9e](https://linux-hardware.org/?probe=7a121f2a9e) | Sep 24, 2023 |
| Gigabyte      | H77-D3H                     | [3d7d389342](https://linux-hardware.org/?probe=3d7d389342) | Sep 24, 2023 |
| MSI           | A78M-E35                    | [894b759057](https://linux-hardware.org/?probe=894b759057) | Sep 24, 2023 |
| HOUTER        | OROPC                       | [96625070be](https://linux-hardware.org/?probe=96625070be) | Sep 24, 2023 |
| Positivo      | POS-EIBTPDC                 | [3c2427ba03](https://linux-hardware.org/?probe=3c2427ba03) | Sep 23, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [54ed40361d](https://linux-hardware.org/?probe=54ed40361d) | Sep 23, 2023 |
| Positivo      | POS-EIBTPDC                 | [586c05976a](https://linux-hardware.org/?probe=586c05976a) | Sep 23, 2023 |
| Fujitsu       | D2990-A1 S26361-D2990-A1    | [19757abbb8](https://linux-hardware.org/?probe=19757abbb8) | Sep 23, 2023 |
| HOUTER        | OROPC                       | [3f78fb9290](https://linux-hardware.org/?probe=3f78fb9290) | Sep 23, 2023 |
| Gigabyte      | H110N-CF                    | [7655a31997](https://linux-hardware.org/?probe=7655a31997) | Sep 23, 2023 |
| Gigabyte      | F2A88XM-D3H                 | [f597ec9360](https://linux-hardware.org/?probe=f597ec9360) | Sep 23, 2023 |
| Dell          | 0C2KJT A00                  | [a6fcc5eb53](https://linux-hardware.org/?probe=a6fcc5eb53) | Sep 23, 2023 |
| Acer          | Aspire TC-895 V:1.0         | [6f3c1fed91](https://linux-hardware.org/?probe=6f3c1fed91) | Sep 23, 2023 |
| ASUSTek       | H81M-K                      | [30a324bad7](https://linux-hardware.org/?probe=30a324bad7) | Sep 23, 2023 |
| MSI           | PRO H410M-B                 | [dd6815e149](https://linux-hardware.org/?probe=dd6815e149) | Sep 23, 2023 |
| Foxconn       | 2ABF                        | [b566fc3ff3](https://linux-hardware.org/?probe=b566fc3ff3) | Sep 23, 2023 |
| Centerm       | C92                         | [022344ea10](https://linux-hardware.org/?probe=022344ea10) | Sep 22, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | [312172129f](https://linux-hardware.org/?probe=312172129f) | Sep 22, 2023 |
| ASUSTek       | P5G41T-M LX                 | [988711772b](https://linux-hardware.org/?probe=988711772b) | Sep 22, 2023 |
| ASUSTek       | PRIME Z370-P                | [fb3ade25c0](https://linux-hardware.org/?probe=fb3ade25c0) | Sep 22, 2023 |
| ASUSTek       | A88X-PLUS                   | [4e3033c305](https://linux-hardware.org/?probe=4e3033c305) | Sep 22, 2023 |
| ASRock        | Z790 Taichi                 | [d1a889a811](https://linux-hardware.org/?probe=d1a889a811) | Sep 21, 2023 |
| ASRock        | AM1B-ITX                    | [95b1c6332b](https://linux-hardware.org/?probe=95b1c6332b) | Sep 21, 2023 |
| MSI           | Boston                      | [a9fe9241ec](https://linux-hardware.org/?probe=a9fe9241ec) | Sep 21, 2023 |
| ASUSTek       | Z87-A                       | [97747fb973](https://linux-hardware.org/?probe=97747fb973) | Sep 21, 2023 |
| Acer          | Nitro N50-600 V:1.1         | [34d899f825](https://linux-hardware.org/?probe=34d899f825) | Sep 21, 2023 |
| Dell          | 0XHGV1 A01                  | [eeae4a837e](https://linux-hardware.org/?probe=eeae4a837e) | Sep 21, 2023 |
| MSI           | PRO B650M-A WIFI            | [8e60d0df9c](https://linux-hardware.org/?probe=8e60d0df9c) | Sep 21, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [08989d4bba](https://linux-hardware.org/?probe=08989d4bba) | Sep 21, 2023 |
| Acer          | Nitro N50-600 V:1.1         | [b1fd4a61ae](https://linux-hardware.org/?probe=b1fd4a61ae) | Sep 21, 2023 |
| DFI           | CH960                       | [a6514c3301](https://linux-hardware.org/?probe=a6514c3301) | Sep 21, 2023 |
| Gigabyte      | B85M-DS3H-A                 | [6d0e6a863d](https://linux-hardware.org/?probe=6d0e6a863d) | Sep 21, 2023 |
| ASUSTek       | PRIME Z370-A II             | [d348acd6c8](https://linux-hardware.org/?probe=d348acd6c8) | Sep 21, 2023 |
| ASUSTek       | P9X79 PRO                   | [b58de0bed0](https://linux-hardware.org/?probe=b58de0bed0) | Sep 21, 2023 |
| AZW           | MINI S 10                   | [4e2cc1421f](https://linux-hardware.org/?probe=4e2cc1421f) | Sep 21, 2023 |
| ASUSTek       | B150M-A                     | [d2e741051e](https://linux-hardware.org/?probe=d2e741051e) | Sep 21, 2023 |
| HP            | 8027                        | [e8568c8f9b](https://linux-hardware.org/?probe=e8568c8f9b) | Sep 20, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [0f28c5cddd](https://linux-hardware.org/?probe=0f28c5cddd) | Sep 20, 2023 |
| Acer          | Veriton S2680G              | [76f872c7bb](https://linux-hardware.org/?probe=76f872c7bb) | Sep 20, 2023 |
| Dell          | 03NVJ6 A00                  | [af48b03e82](https://linux-hardware.org/?probe=af48b03e82) | Sep 20, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [f7629203e7](https://linux-hardware.org/?probe=f7629203e7) | Sep 20, 2023 |
| HP            | 1998                        | [27c06c8617](https://linux-hardware.org/?probe=27c06c8617) | Sep 20, 2023 |
| Intel         | H61                         | [82a94f86d2](https://linux-hardware.org/?probe=82a94f86d2) | Sep 20, 2023 |
| Gigabyte      | B250M-HD3-CF                | [f7280def0d](https://linux-hardware.org/?probe=f7280def0d) | Sep 20, 2023 |
| MSI           | X399 GAMING PRO CARBON A... | [040189d6dc](https://linux-hardware.org/?probe=040189d6dc) | Sep 20, 2023 |
| HP            | 1497                        | [8ea04759fc](https://linux-hardware.org/?probe=8ea04759fc) | Sep 20, 2023 |
| Dell          | 09KPNV A01                  | [4ce81f3886](https://linux-hardware.org/?probe=4ce81f3886) | Sep 20, 2023 |
| Gateway       | DX4850                      | [ebd6fd7a33](https://linux-hardware.org/?probe=ebd6fd7a33) | Sep 19, 2023 |
| Supermicro    | X9DRL-3F/iF                 | [419c68293c](https://linux-hardware.org/?probe=419c68293c) | Sep 19, 2023 |
| Gigabyte      | B75M-HD3                    | [fe4ef48e82](https://linux-hardware.org/?probe=fe4ef48e82) | Sep 19, 2023 |
| Medion        | D3F3-EM                     | [6fe93a02c7](https://linux-hardware.org/?probe=6fe93a02c7) | Sep 19, 2023 |
| Supermicro    | X9DRW                       | [6f4a97a40b](https://linux-hardware.org/?probe=6f4a97a40b) | Sep 19, 2023 |
| Medion        | MS-7848                     | [acbe0e1821](https://linux-hardware.org/?probe=acbe0e1821) | Sep 19, 2023 |
| HP            | 1998                        | [d65f099f06](https://linux-hardware.org/?probe=d65f099f06) | Sep 19, 2023 |
| Apple         | Mac-7BA5B2D9E42DDD94 iMa... | [7c74dca781](https://linux-hardware.org/?probe=7c74dca781) | Sep 19, 2023 |
| ASUSTek       | P8H61-M LE/USB3             | [8ea05ba99b](https://linux-hardware.org/?probe=8ea05ba99b) | Sep 18, 2023 |
| Gateway       | SX2865 V1.0                 | [5966c7d7e3](https://linux-hardware.org/?probe=5966c7d7e3) | Sep 18, 2023 |
| HP            | 339A                        | [bb4819d02f](https://linux-hardware.org/?probe=bb4819d02f) | Sep 18, 2023 |
| ASUSTek       | PRIME X670-P                | [766c0407a2](https://linux-hardware.org/?probe=766c0407a2) | Sep 18, 2023 |
| ASUSTek       | PRIME B550M-A               | [c6abc7bdf4](https://linux-hardware.org/?probe=c6abc7bdf4) | Sep 18, 2023 |
| MSI           | H61M-P22                    | [4c32887473](https://linux-hardware.org/?probe=4c32887473) | Sep 18, 2023 |
| ASRock        | X570 Extreme4               | [18bc19acdf](https://linux-hardware.org/?probe=18bc19acdf) | Sep 18, 2023 |
| Dell          | 0PTTT9 A01                  | [35248efbaf](https://linux-hardware.org/?probe=35248efbaf) | Sep 18, 2023 |
| HP            | 8767 A                      | [7698226e84](https://linux-hardware.org/?probe=7698226e84) | Sep 18, 2023 |
| Dell          | 0GM819                      | [48495ce23e](https://linux-hardware.org/?probe=48495ce23e) | Sep 18, 2023 |
| ASRock        | B650M PG Riptide            | [8dd27c1671](https://linux-hardware.org/?probe=8dd27c1671) | Sep 18, 2023 |
| ASRock        | B650M PG Riptide            | [06b00c7739](https://linux-hardware.org/?probe=06b00c7739) | Sep 18, 2023 |
| Gigabyte      | B450M DS3H V2               | [45c70e0bf9](https://linux-hardware.org/?probe=45c70e0bf9) | Sep 17, 2023 |
| Shenzhen M... | F6BFC                       | [b45825033c](https://linux-hardware.org/?probe=b45825033c) | Sep 17, 2023 |
| Shenzhen M... | F6BFC                       | [3dae667762](https://linux-hardware.org/?probe=3dae667762) | Sep 17, 2023 |
| Acer          | RL100                       | [803bd98e9f](https://linux-hardware.org/?probe=803bd98e9f) | Sep 17, 2023 |
| ASRock        | A320M-HDV R4.0              | [4cd954351c](https://linux-hardware.org/?probe=4cd954351c) | Sep 17, 2023 |
| Acer          | Veriton L4630G V:1.0        | [4ee96f70b9](https://linux-hardware.org/?probe=4ee96f70b9) | Sep 17, 2023 |
| Acer          | Veriton L4630G V:1.0        | [1a0448ff84](https://linux-hardware.org/?probe=1a0448ff84) | Sep 17, 2023 |
| ASUSTek       | Z87-PLUS                    | [ae6215005e](https://linux-hardware.org/?probe=ae6215005e) | Sep 17, 2023 |
| HC Technol... | HCAR5000-MI                 | [eb9e6551ac](https://linux-hardware.org/?probe=eb9e6551ac) | Sep 17, 2023 |
| HC Technol... | HCAR5000-MI                 | [f3a4ce70fb](https://linux-hardware.org/?probe=f3a4ce70fb) | Sep 17, 2023 |
| ASUSTek       | Z87-PLUS                    | [613d6735a3](https://linux-hardware.org/?probe=613d6735a3) | Sep 17, 2023 |
| Unknown       | Unknown                     | [bd72d25583](https://linux-hardware.org/?probe=bd72d25583) | Sep 17, 2023 |
| ASUSTek       | P8Z68-V LX                  | [bc7f403188](https://linux-hardware.org/?probe=bc7f403188) | Sep 16, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | [bc002722a7](https://linux-hardware.org/?probe=bc002722a7) | Sep 16, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | [45cfc84d3e](https://linux-hardware.org/?probe=45cfc84d3e) | Sep 16, 2023 |
| Dell          | 0VHWTR A02                  | [c34520d1c2](https://linux-hardware.org/?probe=c34520d1c2) | Sep 16, 2023 |
| MSI           | H510I PRO WIFI              | [e8f9c86131](https://linux-hardware.org/?probe=e8f9c86131) | Sep 16, 2023 |
| Acer          | Veriton N4640G              | [73af90ca23](https://linux-hardware.org/?probe=73af90ca23) | Sep 16, 2023 |
| HC Technol... | HCAR5000-MI                 | [14ec27ff9d](https://linux-hardware.org/?probe=14ec27ff9d) | Sep 16, 2023 |
| ASUSTek       | CM1740                      | [96b9168216](https://linux-hardware.org/?probe=96b9168216) | Sep 16, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [87e9bbfef5](https://linux-hardware.org/?probe=87e9bbfef5) | Sep 16, 2023 |
| Gigabyte      | B250M-HD3-CF                | [8bc40fd9f1](https://linux-hardware.org/?probe=8bc40fd9f1) | Sep 16, 2023 |
| Gigabyte      | B450M DS3H V2               | [91ab2c03a2](https://linux-hardware.org/?probe=91ab2c03a2) | Sep 15, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | [02bd43e898](https://linux-hardware.org/?probe=02bd43e898) | Sep 15, 2023 |
| ASRock        | B650E Steel Legend WiFi     | [0f87ffad72](https://linux-hardware.org/?probe=0f87ffad72) | Sep 15, 2023 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [c8c55eb300](https://linux-hardware.org/?probe=c8c55eb300) | Sep 15, 2023 |
| Gigabyte      | 970A-DS3P                   | [708a3e1ceb](https://linux-hardware.org/?probe=708a3e1ceb) | Sep 15, 2023 |
| Acer          | Aspire XC-780               | [1019ced6e5](https://linux-hardware.org/?probe=1019ced6e5) | Sep 15, 2023 |
| Dell          | 0YXT71 A00                  | [49f912aad2](https://linux-hardware.org/?probe=49f912aad2) | Sep 15, 2023 |
| Supermicro    | X10DRU-i+A                  | [d0cee7fa36](https://linux-hardware.org/?probe=d0cee7fa36) | Sep 15, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | [b6a802c0ac](https://linux-hardware.org/?probe=b6a802c0ac) | Sep 15, 2023 |
| Dell          | 0TDG4V A01                  | [7c2d7aeafa](https://linux-hardware.org/?probe=7c2d7aeafa) | Sep 15, 2023 |
| Gigabyte      | B450M DS3H-CF               | [f48f6375b2](https://linux-hardware.org/?probe=f48f6375b2) | Sep 15, 2023 |
| ASUSTek       | P8B75-M LX                  | [cdbfe7dc54](https://linux-hardware.org/?probe=cdbfe7dc54) | Sep 15, 2023 |
| Dell          | 0YXT71 A00                  | [e857239d67](https://linux-hardware.org/?probe=e857239d67) | Sep 15, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [c424e240c8](https://linux-hardware.org/?probe=c424e240c8) | Sep 15, 2023 |
| ASUSTek       | PRIME B660M-A D4            | [a44de9f197](https://linux-hardware.org/?probe=a44de9f197) | Sep 15, 2023 |
| AZW           | N4                          | [4237228bca](https://linux-hardware.org/?probe=4237228bca) | Sep 15, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [5fae508d12](https://linux-hardware.org/?probe=5fae508d12) | Sep 14, 2023 |
| Gigabyte      | A320M-S2H-CF                | [e484eea129](https://linux-hardware.org/?probe=e484eea129) | Sep 14, 2023 |
| Dell          | 09WH54 A00                  | [128763445e](https://linux-hardware.org/?probe=128763445e) | Sep 14, 2023 |
| Gigabyte      | 970A-DS3P                   | [3958b55e0e](https://linux-hardware.org/?probe=3958b55e0e) | Sep 14, 2023 |
| ASRock        | N68-S3 UCC                  | [4164e2d7c7](https://linux-hardware.org/?probe=4164e2d7c7) | Sep 14, 2023 |
| MSI           | B85-G43 GAMING              | [44d14cb672](https://linux-hardware.org/?probe=44d14cb672) | Sep 14, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | [160685ce41](https://linux-hardware.org/?probe=160685ce41) | Sep 14, 2023 |
| Supermicro    | X10DRU-i+B                  | [3650d44342](https://linux-hardware.org/?probe=3650d44342) | Sep 13, 2023 |
| Fujitsu       | D3400-A1 S26361-D3400-A1    | [d405b46cb7](https://linux-hardware.org/?probe=d405b46cb7) | Sep 13, 2023 |
| Unknown       | Unknown                     | [2035ddd158](https://linux-hardware.org/?probe=2035ddd158) | Sep 13, 2023 |
| Fujitsu       | FujitsuTP7000 -1            | [e4a4c070c5](https://linux-hardware.org/?probe=e4a4c070c5) | Sep 13, 2023 |
| HP            | 0A9Ch                       | [f18d5b9584](https://linux-hardware.org/?probe=f18d5b9584) | Sep 13, 2023 |
| Dell          | 0TDG4V A01                  | [7d79af3d22](https://linux-hardware.org/?probe=7d79af3d22) | Sep 13, 2023 |
| ASRock        | B660-ITX                    | [9d3d4b479e](https://linux-hardware.org/?probe=9d3d4b479e) | Sep 13, 2023 |
| HOUTER        | OROPC                       | [711d8f8d80](https://linux-hardware.org/?probe=711d8f8d80) | Sep 13, 2023 |
| AZW           | MINI S                      | [b29be994f6](https://linux-hardware.org/?probe=b29be994f6) | Sep 13, 2023 |
| Gateway       | SX2865 V1.0                 | [6a3aadc121](https://linux-hardware.org/?probe=6a3aadc121) | Sep 13, 2023 |
| ASUSTek       | P5K                         | [e27562d8d0](https://linux-hardware.org/?probe=e27562d8d0) | Sep 12, 2023 |
| Intel         | H61                         | [513ebd18a2](https://linux-hardware.org/?probe=513ebd18a2) | Sep 12, 2023 |
| Lenovo        | 310B SDK0J40705 WIN 3425... | [863317803b](https://linux-hardware.org/?probe=863317803b) | Sep 12, 2023 |
| Gigabyte      | B365M H                     | [b57846d1cb](https://linux-hardware.org/?probe=b57846d1cb) | Sep 12, 2023 |
| ASUSTek       | PRIME X570-P                | [efc20753cd](https://linux-hardware.org/?probe=efc20753cd) | Sep 12, 2023 |
| Google        | Tricky                      | [369d9cc69f](https://linux-hardware.org/?probe=369d9cc69f) | Sep 12, 2023 |
| ASUSTek       | M3N78-VM                    | [79e5a35fa4](https://linux-hardware.org/?probe=79e5a35fa4) | Sep 12, 2023 |
| Dell          | 0GM819                      | [10c8f8313f](https://linux-hardware.org/?probe=10c8f8313f) | Sep 12, 2023 |
| ASRock        | J5005-ITX                   | [1ef1e0a2cb](https://linux-hardware.org/?probe=1ef1e0a2cb) | Sep 12, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [40df085797](https://linux-hardware.org/?probe=40df085797) | Sep 12, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [78f326afa5](https://linux-hardware.org/?probe=78f326afa5) | Sep 12, 2023 |
| HP            | 18E5                        | [0706e3225c](https://linux-hardware.org/?probe=0706e3225c) | Sep 12, 2023 |
| Dell          | 0N185P A02                  | [36318c6f09](https://linux-hardware.org/?probe=36318c6f09) | Sep 11, 2023 |
| Gigabyte      | B250M-DS3H-CF               | [951faca7d0](https://linux-hardware.org/?probe=951faca7d0) | Sep 11, 2023 |
| Dell          | 0N185P A02                  | [2a5e66fcbe](https://linux-hardware.org/?probe=2a5e66fcbe) | Sep 11, 2023 |
| Pegatron      | 2AB6                        | [752a87de3b](https://linux-hardware.org/?probe=752a87de3b) | Sep 11, 2023 |
| Gigabyte      | GA-MA78LMT-S2               | [fc808572da](https://linux-hardware.org/?probe=fc808572da) | Sep 11, 2023 |
| ASUSTek       | P8H77-M                     | [61dc55f063](https://linux-hardware.org/?probe=61dc55f063) | Sep 11, 2023 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [c780b34220](https://linux-hardware.org/?probe=c780b34220) | Sep 11, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [510f627c91](https://linux-hardware.org/?probe=510f627c91) | Sep 11, 2023 |
| Intel         | DH67BL AAG10189-213         | [305dbf2be1](https://linux-hardware.org/?probe=305dbf2be1) | Sep 11, 2023 |
| Lenovo        | SHARKBAY NOK                | [dc3c32cc6a](https://linux-hardware.org/?probe=dc3c32cc6a) | Sep 11, 2023 |
| Acer          | Veriton N4640G              | [4ad00f4c17](https://linux-hardware.org/?probe=4ad00f4c17) | Sep 10, 2023 |
| MSI           | B450M PRO-M2 V2             | [7340842ec5](https://linux-hardware.org/?probe=7340842ec5) | Sep 10, 2023 |
| MSI           | MAG B550M MORTAR MAX WIF... | [5cb0ed682a](https://linux-hardware.org/?probe=5cb0ed682a) | Sep 10, 2023 |
| ASRock        | B450M Pro4                  | [c8e3010177](https://linux-hardware.org/?probe=c8e3010177) | Sep 10, 2023 |
| ASUSTek       | M51AC                       | [3408573237](https://linux-hardware.org/?probe=3408573237) | Sep 09, 2023 |
| Intel         | H61                         | [f8eaac6637](https://linux-hardware.org/?probe=f8eaac6637) | Sep 09, 2023 |
| ASUSTek       | P8H77-M                     | [0916725ace](https://linux-hardware.org/?probe=0916725ace) | Sep 09, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [3e5c4db7aa](https://linux-hardware.org/?probe=3e5c4db7aa) | Sep 09, 2023 |
| Dell          | 0J3C2F A00                  | [8027340ed2](https://linux-hardware.org/?probe=8027340ed2) | Sep 09, 2023 |
| MSI           | B450M MORTAR MAX            | [6526a9d926](https://linux-hardware.org/?probe=6526a9d926) | Sep 09, 2023 |
| ASRock        | X399 Taichi                 | [0c2dda2476](https://linux-hardware.org/?probe=0c2dda2476) | Sep 09, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | [72bc6278d3](https://linux-hardware.org/?probe=72bc6278d3) | Sep 09, 2023 |
| Dell          | 0GX297                      | [c7619d7897](https://linux-hardware.org/?probe=c7619d7897) | Sep 09, 2023 |
| Dell          | 00V62H A01                  | [7b02c70750](https://linux-hardware.org/?probe=7b02c70750) | Sep 09, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [2b74633199](https://linux-hardware.org/?probe=2b74633199) | Sep 09, 2023 |
| ASUSTek       | P8B75-M                     | [d64063efa5](https://linux-hardware.org/?probe=d64063efa5) | Sep 09, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [3bb12f9fa5](https://linux-hardware.org/?probe=3bb12f9fa5) | Sep 09, 2023 |
| MSI           | Z170A PC MATE               | [8ef6db8e31](https://linux-hardware.org/?probe=8ef6db8e31) | Sep 09, 2023 |
| MSI           | Boston                      | [865959d898](https://linux-hardware.org/?probe=865959d898) | Sep 08, 2023 |
| ASRock        | A520M-ITX/ac                | [0429117716](https://linux-hardware.org/?probe=0429117716) | Sep 08, 2023 |
| Fujitsu       | D3427-A1 S26361-D3427-A1    | [cd4215585d](https://linux-hardware.org/?probe=cd4215585d) | Sep 08, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [0c30921512](https://linux-hardware.org/?probe=0c30921512) | Sep 08, 2023 |
| ASUSTek       | P6T                         | [50079d9e1d](https://linux-hardware.org/?probe=50079d9e1d) | Sep 08, 2023 |
| Dell          | 06X1TJ A00                  | [2c4e147992](https://linux-hardware.org/?probe=2c4e147992) | Sep 08, 2023 |
| Gateway       | DX4850                      | [6f2e112b3f](https://linux-hardware.org/?probe=6f2e112b3f) | Sep 08, 2023 |
| ASRock        | B550M Steel Legend          | [ecd59bd254](https://linux-hardware.org/?probe=ecd59bd254) | Sep 08, 2023 |
| ASUSTek       | P8H61-I R2.0                | [16e39e16a0](https://linux-hardware.org/?probe=16e39e16a0) | Sep 08, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [edf1e3f8c4](https://linux-hardware.org/?probe=edf1e3f8c4) | Sep 08, 2023 |
| Gigabyte      | 970A-DS3P FX                | [c0785a953a](https://linux-hardware.org/?probe=c0785a953a) | Sep 08, 2023 |
| EVGA          | Z690 CLASSIFIED.0           | [573a3152c0](https://linux-hardware.org/?probe=573a3152c0) | Sep 08, 2023 |
| EVGA          | Z690 CLASSIFIED.0           | [b5d0d5fcf1](https://linux-hardware.org/?probe=b5d0d5fcf1) | Sep 08, 2023 |
| Dell          | 077RRV A00                  | [5ebc4171ff](https://linux-hardware.org/?probe=5ebc4171ff) | Sep 08, 2023 |
| ASUSTek       | P5K-VM                      | [9b8cb6e3f6](https://linux-hardware.org/?probe=9b8cb6e3f6) | Sep 07, 2023 |
| Dell          | 00V62H A01                  | [88eba1ea14](https://linux-hardware.org/?probe=88eba1ea14) | Sep 07, 2023 |
| Supermicro    | X10DRU-i+A                  | [abdec86bab](https://linux-hardware.org/?probe=abdec86bab) | Sep 07, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [2b734c4a23](https://linux-hardware.org/?probe=2b734c4a23) | Sep 07, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [f8453df937](https://linux-hardware.org/?probe=f8453df937) | Sep 07, 2023 |
| Unknown       | Unknown                     | [59544c398a](https://linux-hardware.org/?probe=59544c398a) | Sep 07, 2023 |
| HP            | 0B4Ch D                     | [1a2a0eef04](https://linux-hardware.org/?probe=1a2a0eef04) | Sep 06, 2023 |
| HP            | 0B4Ch D                     | [e6c990ad64](https://linux-hardware.org/?probe=e6c990ad64) | Sep 06, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [9d45d79cb0](https://linux-hardware.org/?probe=9d45d79cb0) | Sep 06, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | [97bacd8975](https://linux-hardware.org/?probe=97bacd8975) | Sep 06, 2023 |
| ASUSTek       | P8H77-M                     | [ebc8d3e851](https://linux-hardware.org/?probe=ebc8d3e851) | Sep 06, 2023 |
| Unknown       | Unknown                     | [c4829899c3](https://linux-hardware.org/?probe=c4829899c3) | Sep 06, 2023 |
| Intel         | H81                         | [5a16cea30a](https://linux-hardware.org/?probe=5a16cea30a) | Sep 06, 2023 |
| DFI           | CH960                       | [f0caeeeae0](https://linux-hardware.org/?probe=f0caeeeae0) | Sep 06, 2023 |
| ASUSTek       | B150M-PLUS                  | [a5a6f0acfb](https://linux-hardware.org/?probe=a5a6f0acfb) | Sep 06, 2023 |
| Supermicro    | X9DRW                       | [01d640708d](https://linux-hardware.org/?probe=01d640708d) | Sep 06, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [586f1d2fa7](https://linux-hardware.org/?probe=586f1d2fa7) | Sep 06, 2023 |
| Dell          | 0VNP2H A00                  | [04e5805a67](https://linux-hardware.org/?probe=04e5805a67) | Sep 06, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [f04f6fc2a6](https://linux-hardware.org/?probe=f04f6fc2a6) | Sep 06, 2023 |
| ASUSTek       | X99-DELUXE                  | [0035cdf446](https://linux-hardware.org/?probe=0035cdf446) | Sep 05, 2023 |
| ASRock        | N68C-S UCC                  | [c2e1fe7134](https://linux-hardware.org/?probe=c2e1fe7134) | Sep 05, 2023 |
| DFI           | CH960                       | [29c9bcf1ed](https://linux-hardware.org/?probe=29c9bcf1ed) | Sep 05, 2023 |
| ASUSTek       | SABERTOOTH X58              | [9139773ff9](https://linux-hardware.org/?probe=9139773ff9) | Sep 05, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [190675e9f1](https://linux-hardware.org/?probe=190675e9f1) | Sep 05, 2023 |
| Dell          | 0PTTT9 A01                  | [2c7accd18e](https://linux-hardware.org/?probe=2c7accd18e) | Sep 05, 2023 |
| Dell          | 073MMW A02                  | [5b5728ae8d](https://linux-hardware.org/?probe=5b5728ae8d) | Sep 05, 2023 |
| AZW           | MINI S                      | [a2a1414ea6](https://linux-hardware.org/?probe=a2a1414ea6) | Sep 05, 2023 |
| ASUSTek       | M4A785-M                    | [0e073fb229](https://linux-hardware.org/?probe=0e073fb229) | Sep 05, 2023 |
| MSI           | B350 GAMING PRO CARBON      | [c2257ed5b8](https://linux-hardware.org/?probe=c2257ed5b8) | Sep 04, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [bcd06888e4](https://linux-hardware.org/?probe=bcd06888e4) | Sep 04, 2023 |
| MSI           | Boston                      | [5e1b8aa70b](https://linux-hardware.org/?probe=5e1b8aa70b) | Sep 04, 2023 |
| Gigabyte      | Z390 AORUS PRO-CF           | [a9321ea88e](https://linux-hardware.org/?probe=a9321ea88e) | Sep 04, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [cda189c68a](https://linux-hardware.org/?probe=cda189c68a) | Sep 04, 2023 |
| MSI           | Boston                      | [5ad763345c](https://linux-hardware.org/?probe=5ad763345c) | Sep 04, 2023 |
| Medion        | H110H4-EM                   | [e4752c330e](https://linux-hardware.org/?probe=e4752c330e) | Sep 04, 2023 |
| Dell          | 06X1TJ A00                  | [f24368d776](https://linux-hardware.org/?probe=f24368d776) | Sep 04, 2023 |
| Dell          | 06X1TJ A00                  | [f4fbaa8dd1](https://linux-hardware.org/?probe=f4fbaa8dd1) | Sep 04, 2023 |
| Gigabyte      | B360HD3                     | [1242798344](https://linux-hardware.org/?probe=1242798344) | Sep 04, 2023 |
| ASUSTek       | VM42                        | [2869496e53](https://linux-hardware.org/?probe=2869496e53) | Sep 04, 2023 |
| Acer          | Veriton S2680G              | [e1fdce5232](https://linux-hardware.org/?probe=e1fdce5232) | Sep 04, 2023 |
| ECS           | Nettle2                     | [8492f01e46](https://linux-hardware.org/?probe=8492f01e46) | Sep 04, 2023 |
| ASUSTek       | SABERTOOTH X58              | [edc8896f06](https://linux-hardware.org/?probe=edc8896f06) | Sep 04, 2023 |
| ASRock        | A520M-HDV                   | [8da6b89260](https://linux-hardware.org/?probe=8da6b89260) | Sep 04, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [15826e3d9e](https://linux-hardware.org/?probe=15826e3d9e) | Sep 04, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | [0eff1074a1](https://linux-hardware.org/?probe=0eff1074a1) | Sep 03, 2023 |
| Gigabyte      | B550M DS3H                  | [b8a2b22a6c](https://linux-hardware.org/?probe=b8a2b22a6c) | Sep 03, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [493d16ff67](https://linux-hardware.org/?probe=493d16ff67) | Sep 03, 2023 |
| ASUSTek       | PRIME X470-PRO              | [35e2cffa7f](https://linux-hardware.org/?probe=35e2cffa7f) | Sep 03, 2023 |
| AZW           | U59                         | [98e1e109a5](https://linux-hardware.org/?probe=98e1e109a5) | Sep 03, 2023 |
| Intel         | DG31PR AAD97573-301         | [359e7817c3](https://linux-hardware.org/?probe=359e7817c3) | Sep 03, 2023 |
| Gigabyte      | Z690 AORUS ELITE DDR4       | [7e7d27d9f2](https://linux-hardware.org/?probe=7e7d27d9f2) | Sep 03, 2023 |
| ASRock        | Z77 Extreme4                | [1115c7ff24](https://linux-hardware.org/?probe=1115c7ff24) | Sep 03, 2023 |
| Gigabyte      | P67A-UD3P-B3                | [cf62b3f40c](https://linux-hardware.org/?probe=cf62b3f40c) | Sep 02, 2023 |
| ASUSTek       | PRIME B760M-A WIFI D4       | [f2eccf0aa8](https://linux-hardware.org/?probe=f2eccf0aa8) | Sep 02, 2023 |
| MSI           | MAG B650M MORTAR WIFI       | [1b5109eb83](https://linux-hardware.org/?probe=1b5109eb83) | Sep 02, 2023 |
| ASUSTek       | Acacia                      | [78b7252269](https://linux-hardware.org/?probe=78b7252269) | Sep 02, 2023 |
| Lenovo        | SDK0E50510 WIN              | [84cd7c1a93](https://linux-hardware.org/?probe=84cd7c1a93) | Sep 02, 2023 |
| ASUSTek       | ROG Maximus XII EXTREME     | [7cfd1c36d1](https://linux-hardware.org/?probe=7cfd1c36d1) | Sep 02, 2023 |
| ASRock        | Z370M Pro4                  | [b50da6446a](https://linux-hardware.org/?probe=b50da6446a) | Sep 02, 2023 |
| ASUSTek       | SABERTOOTH X58              | [0c99b66fde](https://linux-hardware.org/?probe=0c99b66fde) | Sep 02, 2023 |
| ASUSTek       | H110M-R                     | [ab9746582a](https://linux-hardware.org/?probe=ab9746582a) | Sep 02, 2023 |
| ASUSTek       | H110M-R                     | [091c787432](https://linux-hardware.org/?probe=091c787432) | Sep 02, 2023 |
| Lenovo        | SHARKBAY NOK                | [6fb1aaaab8](https://linux-hardware.org/?probe=6fb1aaaab8) | Sep 02, 2023 |
| Dell          | 06X1TJ A00                  | [ef4c22cc94](https://linux-hardware.org/?probe=ef4c22cc94) | Sep 01, 2023 |
| Pegatron      | 2AD5                        | [644b70347e](https://linux-hardware.org/?probe=644b70347e) | Sep 01, 2023 |
| MSI           | MPG Z390 GAMING PLUS        | [2c9f663c14](https://linux-hardware.org/?probe=2c9f663c14) | Sep 01, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | [da16406c15](https://linux-hardware.org/?probe=da16406c15) | Sep 01, 2023 |
| MSI           | A320M PRO-M2 V2             | [35a0110255](https://linux-hardware.org/?probe=35a0110255) | Sep 01, 2023 |
| HP            | 82F1                        | [2b601bfc6a](https://linux-hardware.org/?probe=2b601bfc6a) | Sep 01, 2023 |
| HP            | 82F1                        | [fe3e193418](https://linux-hardware.org/?probe=fe3e193418) | Sep 01, 2023 |
| ASRock        | B450M-HDV                   | [3b02e0db71](https://linux-hardware.org/?probe=3b02e0db71) | Sep 01, 2023 |
| ASUSTek       | P5Q SE                      | [288078e39e](https://linux-hardware.org/?probe=288078e39e) | Sep 01, 2023 |
| Acer          | Veriton S2680G              | [17206d19f9](https://linux-hardware.org/?probe=17206d19f9) | Sep 01, 2023 |
| Dell          | 00V62H A01                  | [f3c99a0cc5](https://linux-hardware.org/?probe=f3c99a0cc5) | Sep 01, 2023 |
| Dell          | 09KPNV A01                  | [2d7e76e864](https://linux-hardware.org/?probe=2d7e76e864) | Sep 01, 2023 |
| ASUSTek       | PRIME B550M-A AC            | [da19202792](https://linux-hardware.org/?probe=da19202792) | Sep 01, 2023 |
| ASUSTek       | PRIME B550M-A AC            | [e65f42e0d6](https://linux-hardware.org/?probe=e65f42e0d6) | Sep 01, 2023 |
| Maxtang       | BYT30                       | [6f7fa1fde6](https://linux-hardware.org/?probe=6f7fa1fde6) | Aug 31, 2023 |
| Lenovo        | NOK                         | [3b2d750004](https://linux-hardware.org/?probe=3b2d750004) | Aug 31, 2023 |
| Lenovo        | NOK                         | [0e10fff36a](https://linux-hardware.org/?probe=0e10fff36a) | Aug 31, 2023 |
| MACHINIST     | E5-D8-MAX V1.0              | [339734178a](https://linux-hardware.org/?probe=339734178a) | Aug 31, 2023 |
| Dell          | 0M5DCD A00                  | [dbc3edd473](https://linux-hardware.org/?probe=dbc3edd473) | Aug 31, 2023 |
| Dell          | 0D6H9T A00                  | [9830dce088](https://linux-hardware.org/?probe=9830dce088) | Aug 31, 2023 |
| ASUSTek       | P5N-E SLI                   | [04688c03ea](https://linux-hardware.org/?probe=04688c03ea) | Aug 31, 2023 |
| ASUSTek       | P8B75-M                     | [4f8c86072b](https://linux-hardware.org/?probe=4f8c86072b) | Aug 31, 2023 |
| HP            | 89B5 A                      | [1364f50166](https://linux-hardware.org/?probe=1364f50166) | Aug 31, 2023 |
| HP            | 82B4                        | [28155e6336](https://linux-hardware.org/?probe=28155e6336) | Aug 30, 2023 |
| Supermicro    | X9DRW                       | [a71700e059](https://linux-hardware.org/?probe=a71700e059) | Aug 30, 2023 |
| Alienware     | 0PGRP5 A02                  | [9a95d4ab16](https://linux-hardware.org/?probe=9a95d4ab16) | Aug 30, 2023 |
| ASUSTek       | TUF Z270 MARK 2             | [2d74d46701](https://linux-hardware.org/?probe=2d74d46701) | Aug 30, 2023 |
| Supermicro    | X9DRW                       | [1ff3234fa5](https://linux-hardware.org/?probe=1ff3234fa5) | Aug 30, 2023 |
| ASUSTek       | P8P67 PRO                   | [3740c90267](https://linux-hardware.org/?probe=3740c90267) | Aug 30, 2023 |
| ASRock        | B450M-HDV                   | [047f752404](https://linux-hardware.org/?probe=047f752404) | Aug 30, 2023 |
| Gigabyte      | EP35-DS3                    | [c317e9aa3a](https://linux-hardware.org/?probe=c317e9aa3a) | Aug 30, 2023 |
| ASUSTek       | M5A97 R2.0                  | [c1514e209a](https://linux-hardware.org/?probe=c1514e209a) | Aug 30, 2023 |
| Intel         | DH67CL AAG10212-206         | [e3f4b109ff](https://linux-hardware.org/?probe=e3f4b109ff) | Aug 30, 2023 |
| Pegatron      | 2AB6                        | [ed71da8f69](https://linux-hardware.org/?probe=ed71da8f69) | Aug 29, 2023 |
| Dell          | 0XHGV1 A01                  | [a5f30ecf01](https://linux-hardware.org/?probe=a5f30ecf01) | Aug 29, 2023 |
| HP            | 83EE                        | [d558afff67](https://linux-hardware.org/?probe=d558afff67) | Aug 29, 2023 |
| Huanan        | X99-4MT V1.0                | [b1ebbd0661](https://linux-hardware.org/?probe=b1ebbd0661) | Aug 29, 2023 |
| Colorful T... | CVN X570M GAMING PRO V14    | [187d930341](https://linux-hardware.org/?probe=187d930341) | Aug 29, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [2b9741ce87](https://linux-hardware.org/?probe=2b9741ce87) | Aug 29, 2023 |
| Dell          | 0KWVT8 A03                  | [04ee67e1ad](https://linux-hardware.org/?probe=04ee67e1ad) | Aug 29, 2023 |
| Dell          | 0GXM1W A01                  | [00207aee12](https://linux-hardware.org/?probe=00207aee12) | Aug 29, 2023 |
| MSI           | MAG B460M BAZOOKA           | [dcd9ab0f79](https://linux-hardware.org/?probe=dcd9ab0f79) | Aug 29, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [d97cedcf3c](https://linux-hardware.org/?probe=d97cedcf3c) | Aug 28, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [fe9f235c26](https://linux-hardware.org/?probe=fe9f235c26) | Aug 28, 2023 |
| Intel         | DX79SR AAG57199-200         | [418a709636](https://linux-hardware.org/?probe=418a709636) | Aug 28, 2023 |
| Acer          | Aspire TC-330               | [d8182593c2](https://linux-hardware.org/?probe=d8182593c2) | Aug 28, 2023 |
| ASUSTek       | PRIME B360-PLUS             | [f54073855c](https://linux-hardware.org/?probe=f54073855c) | Aug 28, 2023 |
| ASUSTek       | PRIME B360-PLUS             | [4bcfe8de49](https://linux-hardware.org/?probe=4bcfe8de49) | Aug 28, 2023 |
| HP            | 83EF                        | [05c3bcb04f](https://linux-hardware.org/?probe=05c3bcb04f) | Aug 28, 2023 |
| ASUSTek       | Maximus VII RANGER          | [79803f8898](https://linux-hardware.org/?probe=79803f8898) | Aug 28, 2023 |
| ASRock        | AM1B-M                      | [d35e6acf9a](https://linux-hardware.org/?probe=d35e6acf9a) | Aug 28, 2023 |
| Gigabyte      | B560 DS3H AC-Y1             | [1838cb8b9f](https://linux-hardware.org/?probe=1838cb8b9f) | Aug 28, 2023 |
| Dell          | 00V62H A01                  | [714c46e2fd](https://linux-hardware.org/?probe=714c46e2fd) | Aug 28, 2023 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [c9935dab6b](https://linux-hardware.org/?probe=c9935dab6b) | Aug 27, 2023 |
| Dell          | 0XHGV1 A01                  | [d03180d370](https://linux-hardware.org/?probe=d03180d370) | Aug 27, 2023 |
| Packard Be... | IMEDIA S3730                | [88e192b5f0](https://linux-hardware.org/?probe=88e192b5f0) | Aug 27, 2023 |
| Gigabyte      | H110M-S2-CF                 | [08f577f854](https://linux-hardware.org/?probe=08f577f854) | Aug 27, 2023 |
| ASRock        | X399 Taichi                 | [3d8f7e9e00](https://linux-hardware.org/?probe=3d8f7e9e00) | Aug 27, 2023 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [d03d50ea3c](https://linux-hardware.org/?probe=d03d50ea3c) | Aug 27, 2023 |
| ASUSTek       | PRIME A320M-K               | [9a571d0670](https://linux-hardware.org/?probe=9a571d0670) | Aug 27, 2023 |
| MSI           | H110I PRO                   | [49da08efbd](https://linux-hardware.org/?probe=49da08efbd) | Aug 26, 2023 |
| Packard Be... | IMEDIA S3730                | [fc3a889045](https://linux-hardware.org/?probe=fc3a889045) | Aug 26, 2023 |
| Dell          | 088DT1 A01                  | [b69a80ea82](https://linux-hardware.org/?probe=b69a80ea82) | Aug 26, 2023 |
| HP            | 1905                        | [c1758c3a05](https://linux-hardware.org/?probe=c1758c3a05) | Aug 26, 2023 |
| ASUSTek       | PRIME B650M-A WIFI          | [6a55471f69](https://linux-hardware.org/?probe=6a55471f69) | Aug 26, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | [6a38c0266f](https://linux-hardware.org/?probe=6a38c0266f) | Aug 26, 2023 |
| Acer          | Aspire TC-780               | [70d914b85a](https://linux-hardware.org/?probe=70d914b85a) | Aug 26, 2023 |
| Unknown       | Unknown                     | [e78b6b1077](https://linux-hardware.org/?probe=e78b6b1077) | Aug 26, 2023 |
| Dell          | 03NVJ6 A01                  | [6bbb1d2e62](https://linux-hardware.org/?probe=6bbb1d2e62) | Aug 26, 2023 |
| Dell          | 03NVJ6 A01                  | [ccfb67648a](https://linux-hardware.org/?probe=ccfb67648a) | Aug 26, 2023 |
| ASUSTek       | PRIME B450M-A II            | [607925cb89](https://linux-hardware.org/?probe=607925cb89) | Aug 25, 2023 |
| MSI           | B150 GAMING M3              | [5a1ef4b710](https://linux-hardware.org/?probe=5a1ef4b710) | Aug 25, 2023 |
| ASUSTek       | PRIME X370-PRO              | [fd03f60906](https://linux-hardware.org/?probe=fd03f60906) | Aug 25, 2023 |
| ASUSTek       | X99-DELUXE                  | [d4d9345d6f](https://linux-hardware.org/?probe=d4d9345d6f) | Aug 25, 2023 |
| ASUSTek       | H97I-PLUS                   | [2c9e75e34a](https://linux-hardware.org/?probe=2c9e75e34a) | Aug 25, 2023 |
| Gigabyte      | GA-770TA-UD3                | [6bd78c519f](https://linux-hardware.org/?probe=6bd78c519f) | Aug 25, 2023 |
| Gigabyte      | Z170X-Gaming 7              | [3ddae42f27](https://linux-hardware.org/?probe=3ddae42f27) | Aug 25, 2023 |
| Unknown       | Unknown                     | [1ebb1de535](https://linux-hardware.org/?probe=1ebb1de535) | Aug 25, 2023 |
| ASRock        | A320M-HDV R4.0              | [ccc34d5a51](https://linux-hardware.org/?probe=ccc34d5a51) | Aug 25, 2023 |
| ASUSTek       | P5G41T-M LX                 | [a45010b5bb](https://linux-hardware.org/?probe=a45010b5bb) | Aug 25, 2023 |
| ASRock        | AM1B-M                      | [fe8df93529](https://linux-hardware.org/?probe=fe8df93529) | Aug 25, 2023 |
| Dell          | 0P096C A01                  | [3efa99668a](https://linux-hardware.org/?probe=3efa99668a) | Aug 24, 2023 |
| Dell          | 0P096C A01                  | [1f67d435b7](https://linux-hardware.org/?probe=1f67d435b7) | Aug 24, 2023 |
| Gigabyte      | H61M-S1                     | [09db81cde4](https://linux-hardware.org/?probe=09db81cde4) | Aug 24, 2023 |
| Gigabyte      | P35-DS3R                    | [798717deb6](https://linux-hardware.org/?probe=798717deb6) | Aug 24, 2023 |
| Acer          | Aspire XC-705               | [abb2a529c7](https://linux-hardware.org/?probe=abb2a529c7) | Aug 24, 2023 |
| ASRock        | B550M Pro4                  | [6554eecc36](https://linux-hardware.org/?probe=6554eecc36) | Aug 24, 2023 |
| Acer          | Aspire XC-705               | [1e42c10a2f](https://linux-hardware.org/?probe=1e42c10a2f) | Aug 24, 2023 |
| HP            | 0A9Ch                       | [f5d07e235d](https://linux-hardware.org/?probe=f5d07e235d) | Aug 24, 2023 |
| HP            | 1497                        | [8bb03862e2](https://linux-hardware.org/?probe=8bb03862e2) | Aug 24, 2023 |
| HP            | 1589                        | [cd1492c33d](https://linux-hardware.org/?probe=cd1492c33d) | Aug 24, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [8b76616574](https://linux-hardware.org/?probe=8b76616574) | Aug 24, 2023 |
| Lenovo        | 103D SDK0J40697 WIN 3305... | [18fdc0c2a2](https://linux-hardware.org/?probe=18fdc0c2a2) | Aug 24, 2023 |
| ASUSTek       | M5A78L-M LX3                | [b96cc7270e](https://linux-hardware.org/?probe=b96cc7270e) | Aug 24, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [c63d6cfab0](https://linux-hardware.org/?probe=c63d6cfab0) | Aug 24, 2023 |
| ASUSTek       | ROG Maximus XII FORMULA     | [69df93b6b4](https://linux-hardware.org/?probe=69df93b6b4) | Aug 24, 2023 |
| ASUSTek       | ROG Maximus XII FORMULA     | [8cd328af00](https://linux-hardware.org/?probe=8cd328af00) | Aug 24, 2023 |
| MSI           | H110I PRO                   | [12891f2138](https://linux-hardware.org/?probe=12891f2138) | Aug 24, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [083700ba74](https://linux-hardware.org/?probe=083700ba74) | Aug 23, 2023 |
| ASUSTek       | P7H55-USB3                  | [86ca529583](https://linux-hardware.org/?probe=86ca529583) | Aug 23, 2023 |
| Gigabyte      | A520M DS3H                  | [f8990a10d8](https://linux-hardware.org/?probe=f8990a10d8) | Aug 23, 2023 |
| Gigabyte      | A520M DS3H                  | [a09e28d1d6](https://linux-hardware.org/?probe=a09e28d1d6) | Aug 23, 2023 |
| Pegatron      | 2AC2                        | [7b0af9060e](https://linux-hardware.org/?probe=7b0af9060e) | Aug 23, 2023 |
| ASUSTek       | EX-A320M-GAMING             | [a28ee4ea6b](https://linux-hardware.org/?probe=a28ee4ea6b) | Aug 23, 2023 |
| MiTAC         | PD10EHI                     | [972fe64be0](https://linux-hardware.org/?probe=972fe64be0) | Aug 23, 2023 |
| ASRock        | 990FX Killer                | [20a65c4f0d](https://linux-hardware.org/?probe=20a65c4f0d) | Aug 23, 2023 |
| ASUSTek       | PRIME A320M-K               | [824c7b257e](https://linux-hardware.org/?probe=824c7b257e) | Aug 23, 2023 |
| ASRock        | TRX40 Creator               | [6c3b3d9727](https://linux-hardware.org/?probe=6c3b3d9727) | Aug 23, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | [3a0ddb0171](https://linux-hardware.org/?probe=3a0ddb0171) | Aug 23, 2023 |
| Dell          | 0M858N A01                  | [f8f62c1afb](https://linux-hardware.org/?probe=f8f62c1afb) | Aug 23, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [2bb217b4df](https://linux-hardware.org/?probe=2bb217b4df) | Aug 23, 2023 |
| Supermicro    | X10DRG-Q                    | [45ef204e3e](https://linux-hardware.org/?probe=45ef204e3e) | Aug 23, 2023 |
| ASRock        | H310CM-ITX/ac               | [5725adebf5](https://linux-hardware.org/?probe=5725adebf5) | Aug 22, 2023 |
| Gigabyte      | 990FXA-UD5                  | [5e141011cd](https://linux-hardware.org/?probe=5e141011cd) | Aug 22, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [80c67a4432](https://linux-hardware.org/?probe=80c67a4432) | Aug 22, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [888f62077c](https://linux-hardware.org/?probe=888f62077c) | Aug 22, 2023 |
| Dell          | 06D7TR A00                  | [6e44011ff7](https://linux-hardware.org/?probe=6e44011ff7) | Aug 22, 2023 |
| Dell          | 06D7TR A00                  | [f80faa8301](https://linux-hardware.org/?probe=f80faa8301) | Aug 22, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [236b200fd8](https://linux-hardware.org/?probe=236b200fd8) | Aug 22, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [16d770ddb1](https://linux-hardware.org/?probe=16d770ddb1) | Aug 22, 2023 |
| Supermicro    | X10DRG-Q                    | [ea3995e7d5](https://linux-hardware.org/?probe=ea3995e7d5) | Aug 22, 2023 |
| GMKtec        | NucBox K2                   | [3cc85b0145](https://linux-hardware.org/?probe=3cc85b0145) | Aug 22, 2023 |
| Intel         | X79G V2.x                   | [658431c5b8](https://linux-hardware.org/?probe=658431c5b8) | Aug 22, 2023 |
| HP            | 845A                        | [4a8699daad](https://linux-hardware.org/?probe=4a8699daad) | Aug 22, 2023 |
| Dell          | 088DT1 A01                  | [15020bffbb](https://linux-hardware.org/?probe=15020bffbb) | Aug 22, 2023 |
| HP            | 18E5                        | [c17629e422](https://linux-hardware.org/?probe=c17629e422) | Aug 22, 2023 |
| Apple         | Mac-F221BEC8                | [907a1d574b](https://linux-hardware.org/?probe=907a1d574b) | Aug 21, 2023 |
| ASUSTek       | P8H61-I R2.0                | [510cd25b0e](https://linux-hardware.org/?probe=510cd25b0e) | Aug 21, 2023 |
| HP            | 18E7                        | [49957c261d](https://linux-hardware.org/?probe=49957c261d) | Aug 21, 2023 |
| Intel         | X99                         | [785fcd2a1d](https://linux-hardware.org/?probe=785fcd2a1d) | Aug 21, 2023 |
| Intel         | X99                         | [b54ecfbbc3](https://linux-hardware.org/?probe=b54ecfbbc3) | Aug 21, 2023 |
| Shuttle       | FH170                       | [f96106ab4c](https://linux-hardware.org/?probe=f96106ab4c) | Aug 21, 2023 |
| HP            | 212B                        | [ee20bd40d8](https://linux-hardware.org/?probe=ee20bd40d8) | Aug 21, 2023 |
| Dell          | 0VNM11 A00                  | [e448e177d3](https://linux-hardware.org/?probe=e448e177d3) | Aug 21, 2023 |
| Dell          | 088DT1 A01                  | [762f9cfed0](https://linux-hardware.org/?probe=762f9cfed0) | Aug 21, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [f19c5a2bde](https://linux-hardware.org/?probe=f19c5a2bde) | Aug 21, 2023 |
| ASUSTek       | Benicia                     | [29f90f4d18](https://linux-hardware.org/?probe=29f90f4d18) | Aug 20, 2023 |
| MSI           | MAG B550M MORTAR            | [1c177ea7e4](https://linux-hardware.org/?probe=1c177ea7e4) | Aug 20, 2023 |
| Intel         | D915GAV AAC64134-400        | [c7cad9e093](https://linux-hardware.org/?probe=c7cad9e093) | Aug 20, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [f8f877ce04](https://linux-hardware.org/?probe=f8f877ce04) | Aug 20, 2023 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [9f7605c000](https://linux-hardware.org/?probe=9f7605c000) | Aug 20, 2023 |
| ASUSTek       | P8H61-M LE/USB3             | [49289df595](https://linux-hardware.org/?probe=49289df595) | Aug 20, 2023 |
| Gigabyte      | B550M DS3H                  | [b50e7eb542](https://linux-hardware.org/?probe=b50e7eb542) | Aug 20, 2023 |
| HP            | 339A                        | [fe5a02e559](https://linux-hardware.org/?probe=fe5a02e559) | Aug 20, 2023 |
| ASUSTek       | PRIME H370M-PLUS            | [73ae467f5d](https://linux-hardware.org/?probe=73ae467f5d) | Aug 20, 2023 |
| HP            | 158A                        | [ba0211611f](https://linux-hardware.org/?probe=ba0211611f) | Aug 19, 2023 |
| HP            | 158A                        | [25e8725a35](https://linux-hardware.org/?probe=25e8725a35) | Aug 19, 2023 |
| Unknown       | Unknown                     | [c642878288](https://linux-hardware.org/?probe=c642878288) | Aug 19, 2023 |
| ASRock        | B450M Pro4                  | [12ec49f019](https://linux-hardware.org/?probe=12ec49f019) | Aug 19, 2023 |
| ASRock        | B550M-ITX/ac                | [53a81617e7](https://linux-hardware.org/?probe=53a81617e7) | Aug 19, 2023 |
| HPE           | ProLiant MicroServer Gen... | [467b1475ec](https://linux-hardware.org/?probe=467b1475ec) | Aug 19, 2023 |
| Dell          | 0CT017                      | [3bb33d455c](https://linux-hardware.org/?probe=3bb33d455c) | Aug 18, 2023 |
| Dell          | 06X1TJ A00                  | [e0a9b4c86f](https://linux-hardware.org/?probe=e0a9b4c86f) | Aug 18, 2023 |
| Gigabyte      | H77N-WIFI                   | [687a84cc8b](https://linux-hardware.org/?probe=687a84cc8b) | Aug 18, 2023 |
| Gigabyte      | Z77-D3H                     | [49d0f197aa](https://linux-hardware.org/?probe=49d0f197aa) | Aug 18, 2023 |
| Supermicro    | X10DRi-T4+                  | [2d10353983](https://linux-hardware.org/?probe=2d10353983) | Aug 18, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [024d9028bb](https://linux-hardware.org/?probe=024d9028bb) | Aug 18, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [92ae579bec](https://linux-hardware.org/?probe=92ae579bec) | Aug 18, 2023 |
| Supermicro    | X9DRW                       | [eb0dd75419](https://linux-hardware.org/?probe=eb0dd75419) | Aug 17, 2023 |
| Gateway       | FX6840                      | [b0b3962785](https://linux-hardware.org/?probe=b0b3962785) | Aug 17, 2023 |
| Dell          | 0CT017                      | [5f628eeffa](https://linux-hardware.org/?probe=5f628eeffa) | Aug 17, 2023 |
| ASUSTek       | F2A55-M LK                  | [c2acb99219](https://linux-hardware.org/?probe=c2acb99219) | Aug 17, 2023 |
| Dell          | 0HN7XN A01                  | [6376619639](https://linux-hardware.org/?probe=6376619639) | Aug 17, 2023 |
| Apple         | Mac-27AD2F918AE68F61 Mac... | [2dcf46780c](https://linux-hardware.org/?probe=2dcf46780c) | Aug 17, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [bfc46e751d](https://linux-hardware.org/?probe=bfc46e751d) | Aug 17, 2023 |
| MSI           | H310M PRO-M2 PLUS           | [e4fe24b00a](https://linux-hardware.org/?probe=e4fe24b00a) | Aug 16, 2023 |
| Gigabyte      | X570S AERO G                | [e5618417ed](https://linux-hardware.org/?probe=e5618417ed) | Aug 16, 2023 |
| ASUSTek       | M3A76-CM                    | [031a6edf78](https://linux-hardware.org/?probe=031a6edf78) | Aug 16, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [12f64c8222](https://linux-hardware.org/?probe=12f64c8222) | Aug 16, 2023 |
| ASUSTek       | F2A55-M LK                  | [e14c769e1b](https://linux-hardware.org/?probe=e14c769e1b) | Aug 16, 2023 |
| ASRock        | Z270 Killer SLI             | [10d0229ef0](https://linux-hardware.org/?probe=10d0229ef0) | Aug 16, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | [25279b238a](https://linux-hardware.org/?probe=25279b238a) | Aug 16, 2023 |
| Dell          | 0WR7PY A03                  | [91509a6450](https://linux-hardware.org/?probe=91509a6450) | Aug 15, 2023 |
| ASRock        | EP2C602                     | [26c37b5dfa](https://linux-hardware.org/?probe=26c37b5dfa) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [2412623eac](https://linux-hardware.org/?probe=2412623eac) | Aug 15, 2023 |
| Supermicro    | X9DRW                       | [0fdb533afb](https://linux-hardware.org/?probe=0fdb533afb) | Aug 15, 2023 |
| Alienware     | 0XJKKD A01                  | [1b0f880002](https://linux-hardware.org/?probe=1b0f880002) | Aug 15, 2023 |
| ASUSTek       | PRIME H510M-K               | [b0c33014c5](https://linux-hardware.org/?probe=b0c33014c5) | Aug 15, 2023 |
| Gigabyte      | Z270M-D3H-CF                | [74d96ec17a](https://linux-hardware.org/?probe=74d96ec17a) | Aug 15, 2023 |
| Gigabyte      | Z270M-D3H-CF                | [8e4f3bf14e](https://linux-hardware.org/?probe=8e4f3bf14e) | Aug 15, 2023 |
| ASUSTek       | PRIME H510M-K               | [4b88db67fc](https://linux-hardware.org/?probe=4b88db67fc) | Aug 15, 2023 |
| Apple         | Mac-27AD2F918AE68F61 Mac... | [5002915fe5](https://linux-hardware.org/?probe=5002915fe5) | Aug 15, 2023 |
| Alienware     | 0CPDXD A00                  | [d732dfbf3b](https://linux-hardware.org/?probe=d732dfbf3b) | Aug 15, 2023 |
| HP            | 3047h                       | [4c2aba9453](https://linux-hardware.org/?probe=4c2aba9453) | Aug 14, 2023 |
| Gigabyte      | Z97M-DS3H                   | [69deac32bd](https://linux-hardware.org/?probe=69deac32bd) | Aug 14, 2023 |
| ASUSTek       | P8B75-M                     | [aa3414ebdc](https://linux-hardware.org/?probe=aa3414ebdc) | Aug 14, 2023 |
| MSI           | MS-7380                     | [519b55fb5d](https://linux-hardware.org/?probe=519b55fb5d) | Aug 14, 2023 |
| Gigabyte      | P35-DS3R                    | [4bb45d75da](https://linux-hardware.org/?probe=4bb45d75da) | Aug 14, 2023 |
| ASRock        | EP2C602                     | [c152c5a2f9](https://linux-hardware.org/?probe=c152c5a2f9) | Aug 14, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [9dcf480eb8](https://linux-hardware.org/?probe=9dcf480eb8) | Aug 14, 2023 |
| ASUSTek       | X99-A II                    | [4587b7ff26](https://linux-hardware.org/?probe=4587b7ff26) | Aug 14, 2023 |
| HP            | 0AACh                       | [f65fb50f69](https://linux-hardware.org/?probe=f65fb50f69) | Aug 14, 2023 |
| Dell          | 0D24M8 A01                  | [042b081b3c](https://linux-hardware.org/?probe=042b081b3c) | Aug 14, 2023 |
| Gigabyte      | Z77-D3H                     | [94fe342785](https://linux-hardware.org/?probe=94fe342785) | Aug 14, 2023 |
| Gigabyte      | B450M GAMING                | [495c01f301](https://linux-hardware.org/?probe=495c01f301) | Aug 14, 2023 |
| ASRock        | H71M-DGS                    | [c200c4f848](https://linux-hardware.org/?probe=c200c4f848) | Aug 14, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [1de4045fb5](https://linux-hardware.org/?probe=1de4045fb5) | Aug 13, 2023 |
| Intel         | Alder Lake-H PCH E1.0G      | [ffc38858d0](https://linux-hardware.org/?probe=ffc38858d0) | Aug 13, 2023 |
| Intel         | Alder Lake-H PCH E1.0G      | [4737e7eee7](https://linux-hardware.org/?probe=4737e7eee7) | Aug 13, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [8a4aefedae](https://linux-hardware.org/?probe=8a4aefedae) | Aug 13, 2023 |
| Dell          | 0VNM11 A00                  | [71cd1ddbf5](https://linux-hardware.org/?probe=71cd1ddbf5) | Aug 13, 2023 |
| ASRock        | 970 Extreme3 R2.0           | [cf233e5568](https://linux-hardware.org/?probe=cf233e5568) | Aug 13, 2023 |
| ASRock        | X300M-STX                   | [dc72ce1b47](https://linux-hardware.org/?probe=dc72ce1b47) | Aug 13, 2023 |
| MSI           | A78M-E45                    | [2affb76a98](https://linux-hardware.org/?probe=2affb76a98) | Aug 13, 2023 |
| Intel         | H55                         | [9eb68ebabb](https://linux-hardware.org/?probe=9eb68ebabb) | Aug 13, 2023 |
| Gigabyte      | 990FXA-UD5                  | [e4f4812b8c](https://linux-hardware.org/?probe=e4f4812b8c) | Aug 13, 2023 |
| ASRock        | B550M-C                     | [69cda8cb24](https://linux-hardware.org/?probe=69cda8cb24) | Aug 12, 2023 |
| Dell          | 08NPPY A00                  | [e15632468b](https://linux-hardware.org/?probe=e15632468b) | Aug 12, 2023 |
| ASUSTek       | Z170-K                      | [689401dab4](https://linux-hardware.org/?probe=689401dab4) | Aug 12, 2023 |
| MSI           | B450M PRO-VDH MAX           | [151c51f46f](https://linux-hardware.org/?probe=151c51f46f) | Aug 12, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [a4f97e45f1](https://linux-hardware.org/?probe=a4f97e45f1) | Aug 12, 2023 |
| ECS           | H61H2-M6                    | [b9b9ef9f84](https://linux-hardware.org/?probe=b9b9ef9f84) | Aug 12, 2023 |
| MSI           | P67A-GD65                   | [1024e95ca9](https://linux-hardware.org/?probe=1024e95ca9) | Aug 12, 2023 |
| Fujitsu       | D2990-A1 S26361-D2990-A1    | [ae7ae594f1](https://linux-hardware.org/?probe=ae7ae594f1) | Aug 12, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [7298d533c9](https://linux-hardware.org/?probe=7298d533c9) | Aug 12, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [13e0e622f3](https://linux-hardware.org/?probe=13e0e622f3) | Aug 12, 2023 |
| HP            | 0A04h                       | [61b0d9bc15](https://linux-hardware.org/?probe=61b0d9bc15) | Aug 12, 2023 |
| Fujitsu       | JIQ87Y                      | [b11d99014e](https://linux-hardware.org/?probe=b11d99014e) | Aug 12, 2023 |
| ASUSTek       | H81M-PLUS                   | [af419fe003](https://linux-hardware.org/?probe=af419fe003) | Aug 12, 2023 |
| ASUSTek       | H81M-PLUS                   | [16cd37e4fe](https://linux-hardware.org/?probe=16cd37e4fe) | Aug 12, 2023 |
| Dell          | 0Y2MRG A00                  | [04ce264a3e](https://linux-hardware.org/?probe=04ce264a3e) | Aug 12, 2023 |
| Intel         | DG31PR AAE58249-301         | [28bc891b6d](https://linux-hardware.org/?probe=28bc891b6d) | Aug 12, 2023 |
| Intel         | DG31PR AAE58249-301         | [3050db3fbf](https://linux-hardware.org/?probe=3050db3fbf) | Aug 12, 2023 |
| MSI           | Boston                      | [62ad275a7d](https://linux-hardware.org/?probe=62ad275a7d) | Aug 11, 2023 |
| MSI           | Boston                      | [a34a89c083](https://linux-hardware.org/?probe=a34a89c083) | Aug 11, 2023 |
| Intel         | B75                         | [17641de345](https://linux-hardware.org/?probe=17641de345) | Aug 11, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [483fc71762](https://linux-hardware.org/?probe=483fc71762) | Aug 11, 2023 |
| Unknown       | Unknown                     | [62ef56dbab](https://linux-hardware.org/?probe=62ef56dbab) | Aug 11, 2023 |
| ASRock        | B450M Pro4                  | [65d55091fa](https://linux-hardware.org/?probe=65d55091fa) | Aug 11, 2023 |
| Intel         | D915GEV AAC63667-501        | [4d65f6d8fa](https://linux-hardware.org/?probe=4d65f6d8fa) | Aug 11, 2023 |
| Gigabyte      | B85M-D2V                    | [d8d7d7bad7](https://linux-hardware.org/?probe=d8d7d7bad7) | Aug 11, 2023 |
| ASRock        | B550M-ITX/ac                | [e6624cc619](https://linux-hardware.org/?probe=e6624cc619) | Aug 11, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [7d31344218](https://linux-hardware.org/?probe=7d31344218) | Aug 11, 2023 |
| Dell          | 0HY9JP A01                  | [48d92d85c7](https://linux-hardware.org/?probe=48d92d85c7) | Aug 11, 2023 |
| Acer          | Aspire G7713                | [cb79bdce06](https://linux-hardware.org/?probe=cb79bdce06) | Aug 11, 2023 |
| Gigabyte      | Z77-D3H                     | [e71fc09944](https://linux-hardware.org/?probe=e71fc09944) | Aug 11, 2023 |
| ASUSTek       | PRIME H510M-K               | [3c239efc46](https://linux-hardware.org/?probe=3c239efc46) | Aug 11, 2023 |
| AZW           | Green G4 10                 | [a574280172](https://linux-hardware.org/?probe=a574280172) | Aug 11, 2023 |
| MSI           | MS-7380                     | [584074ca03](https://linux-hardware.org/?probe=584074ca03) | Aug 11, 2023 |
| Alienware     | Area-51 R2                  | [07a6f57292](https://linux-hardware.org/?probe=07a6f57292) | Aug 11, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [6a1d87f2aa](https://linux-hardware.org/?probe=6a1d87f2aa) | Aug 10, 2023 |
| ASUSTek       | P8P67 PRO                   | [c0d6900ba3](https://linux-hardware.org/?probe=c0d6900ba3) | Aug 10, 2023 |
| Fujitsu Si... | G31T-M2 V3.02               | [1c32da7aed](https://linux-hardware.org/?probe=1c32da7aed) | Aug 10, 2023 |
| Lenovo        | ThinkStation S30 056848U    | [e6bc23d815](https://linux-hardware.org/?probe=e6bc23d815) | Aug 10, 2023 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | [6bf6a38fba](https://linux-hardware.org/?probe=6bf6a38fba) | Aug 10, 2023 |
| Gigabyte      | H270N-WIFI-CF               | [bd9c532bbc](https://linux-hardware.org/?probe=bd9c532bbc) | Aug 10, 2023 |
| Dell          | 04YP6J A02                  | [5d5ce952b3](https://linux-hardware.org/?probe=5d5ce952b3) | Aug 10, 2023 |
| Gigabyte      | B560M DS3H                  | [96d3419a5f](https://linux-hardware.org/?probe=96d3419a5f) | Aug 10, 2023 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | [5264c46571](https://linux-hardware.org/?probe=5264c46571) | Aug 10, 2023 |
| YANYU         | EPIC-C57                    | [6d42c0f9af](https://linux-hardware.org/?probe=6d42c0f9af) | Aug 10, 2023 |
| MSI           | A320M PRO-VD/S              | [7f7c988470](https://linux-hardware.org/?probe=7f7c988470) | Aug 10, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [307c7bbe9c](https://linux-hardware.org/?probe=307c7bbe9c) | Aug 10, 2023 |
| Dell          | 0JP3NX A01                  | [a9c4812d66](https://linux-hardware.org/?probe=a9c4812d66) | Aug 09, 2023 |
| ASUSTek       | PRIME Z270-A                | [a6eabbbfef](https://linux-hardware.org/?probe=a6eabbbfef) | Aug 09, 2023 |
| MSI           | 970 GAMING                  | [a499728742](https://linux-hardware.org/?probe=a499728742) | Aug 09, 2023 |
| Dell          | 0WR7PY A03                  | [b97d54f6d8](https://linux-hardware.org/?probe=b97d54f6d8) | Aug 09, 2023 |
| Gigabyte      | B150M-D3H DDR3-CF           | [5df6fee2f9](https://linux-hardware.org/?probe=5df6fee2f9) | Aug 09, 2023 |
| ASRock        | H77M-ITX                    | [01dc3bfc4b](https://linux-hardware.org/?probe=01dc3bfc4b) | Aug 09, 2023 |
| HP            | 894D                        | [e1c397df93](https://linux-hardware.org/?probe=e1c397df93) | Aug 09, 2023 |
| MSI           | A78M-E45                    | [d39f224497](https://linux-hardware.org/?probe=d39f224497) | Aug 09, 2023 |
| MSI           | 970 GAMING                  | [4751920c96](https://linux-hardware.org/?probe=4751920c96) | Aug 09, 2023 |
| Lenovo        | 30C1                        | [dda7ed4e8b](https://linux-hardware.org/?probe=dda7ed4e8b) | Aug 09, 2023 |
| Dell          | 02YYK5 A00                  | [14382141e9](https://linux-hardware.org/?probe=14382141e9) | Aug 09, 2023 |
| MSI           | MAG B760 TOMAHAWK WIFI      | [64fbeeca5e](https://linux-hardware.org/?probe=64fbeeca5e) | Aug 08, 2023 |
| Fujitsu       | D2990-A1 S26361-D2990-A1    | [c48e0220d8](https://linux-hardware.org/?probe=c48e0220d8) | Aug 08, 2023 |
| Intel         | D33217GKE G76540-203        | [fa0fbda262](https://linux-hardware.org/?probe=fa0fbda262) | Aug 08, 2023 |
| Intel         | D33217GKE G76540-203        | [f75916b7c7](https://linux-hardware.org/?probe=f75916b7c7) | Aug 08, 2023 |
| Lenovo        | Bantry CRB SDK0E50510 WI... | [6ffda81a5e](https://linux-hardware.org/?probe=6ffda81a5e) | Aug 08, 2023 |
| HP            | 2129                        | [f005bdb494](https://linux-hardware.org/?probe=f005bdb494) | Aug 08, 2023 |
| Gigabyte      | Z97M-DS3H                   | [f2547c0339](https://linux-hardware.org/?probe=f2547c0339) | Aug 08, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [2335e10b59](https://linux-hardware.org/?probe=2335e10b59) | Aug 08, 2023 |
| Pegatron      | 2AB5                        | [9579022e6f](https://linux-hardware.org/?probe=9579022e6f) | Aug 07, 2023 |
| ASRock        | H610M-ITX/ac                | [205fab2707](https://linux-hardware.org/?probe=205fab2707) | Aug 07, 2023 |
| Gigabyte      | B450M DS3H-CF               | [40b0ea74b1](https://linux-hardware.org/?probe=40b0ea74b1) | Aug 07, 2023 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [873825c261](https://linux-hardware.org/?probe=873825c261) | Aug 07, 2023 |
| HP            | 8055                        | [5124119ce1](https://linux-hardware.org/?probe=5124119ce1) | Aug 07, 2023 |
| Gigabyte      | Z97M-DS3H                   | [beecacb434](https://linux-hardware.org/?probe=beecacb434) | Aug 07, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [002014034b](https://linux-hardware.org/?probe=002014034b) | Aug 07, 2023 |
| ASUSTek       | P5N-E SLI                   | [d552e347f5](https://linux-hardware.org/?probe=d552e347f5) | Aug 07, 2023 |
| AZW           | SEi                         | [b38e4eec2e](https://linux-hardware.org/?probe=b38e4eec2e) | Aug 07, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [fbfc0c60bd](https://linux-hardware.org/?probe=fbfc0c60bd) | Aug 07, 2023 |
| MSI           | Z97 GAMING 5                | [d076b394d9](https://linux-hardware.org/?probe=d076b394d9) | Aug 06, 2023 |
| Dell          | 0WMJ54 A01                  | [7f6aa0ed0c](https://linux-hardware.org/?probe=7f6aa0ed0c) | Aug 06, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [80c705f1a7](https://linux-hardware.org/?probe=80c705f1a7) | Aug 06, 2023 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [28ee020bed](https://linux-hardware.org/?probe=28ee020bed) | Aug 06, 2023 |
| HP            | 805D                        | [672e431e69](https://linux-hardware.org/?probe=672e431e69) | Aug 06, 2023 |
| ASUSTek       | PRIME H410M-E               | [8618a7051f](https://linux-hardware.org/?probe=8618a7051f) | Aug 06, 2023 |
| Lenovo        | 110536U ThinkServer TS13... | [5084897812](https://linux-hardware.org/?probe=5084897812) | Aug 05, 2023 |
| HP            | 1791                        | [4a89aab3d6](https://linux-hardware.org/?probe=4a89aab3d6) | Aug 05, 2023 |
| HP            | 198E                        | [34023c0d62](https://linux-hardware.org/?probe=34023c0d62) | Aug 05, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [8cc106746a](https://linux-hardware.org/?probe=8cc106746a) | Aug 05, 2023 |
| MSI           | A78M-E45                    | [988c1f5878](https://linux-hardware.org/?probe=988c1f5878) | Aug 05, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [4f2449c578](https://linux-hardware.org/?probe=4f2449c578) | Aug 05, 2023 |
| Gigabyte      | G31M-S2C                    | [9cda5ca576](https://linux-hardware.org/?probe=9cda5ca576) | Aug 05, 2023 |
| ASUSTek       | P5QD TURBO                  | [50be5e5725](https://linux-hardware.org/?probe=50be5e5725) | Aug 05, 2023 |
| ASUSTek       | ROG Maximus XII EXTREME     | [f5ebaad3b1](https://linux-hardware.org/?probe=f5ebaad3b1) | Aug 05, 2023 |
| Gigabyte      | H110M-H-CF                  | [17ea53b0c6](https://linux-hardware.org/?probe=17ea53b0c6) | Aug 05, 2023 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [cc0ea700cc](https://linux-hardware.org/?probe=cc0ea700cc) | Aug 04, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [af4ef366cf](https://linux-hardware.org/?probe=af4ef366cf) | Aug 04, 2023 |
| Gigabyte      | GA-MA69VM-S2                | [197a9b0139](https://linux-hardware.org/?probe=197a9b0139) | Aug 03, 2023 |
| MSI           | MS-7380                     | [98aa00b9e1](https://linux-hardware.org/?probe=98aa00b9e1) | Aug 03, 2023 |
| Medion        | MS-7616                     | [7b9dae91ad](https://linux-hardware.org/?probe=7b9dae91ad) | Aug 03, 2023 |
| Dell          | 0CRH6C A02                  | [79d26043a0](https://linux-hardware.org/?probe=79d26043a0) | Aug 03, 2023 |
| Supermicro    | X7DWU                       | [beddea6e34](https://linux-hardware.org/?probe=beddea6e34) | Aug 03, 2023 |
| Supermicro    | X7DWN+                      | [92bf3762f2](https://linux-hardware.org/?probe=92bf3762f2) | Aug 03, 2023 |
| Supermicro    | X7DWU                       | [37ebe498c2](https://linux-hardware.org/?probe=37ebe498c2) | Aug 03, 2023 |
| Supermicro    | X7DWN+                      | [53edc778db](https://linux-hardware.org/?probe=53edc778db) | Aug 03, 2023 |
| Supermicro    | X7DWU                       | [dc1c75a471](https://linux-hardware.org/?probe=dc1c75a471) | Aug 03, 2023 |
| MSI           | PRO Z790-P WIFI             | [8f3eaca764](https://linux-hardware.org/?probe=8f3eaca764) | Aug 03, 2023 |
| Dell          | 0GTK4K A10                  | [b6586709f2](https://linux-hardware.org/?probe=b6586709f2) | Aug 03, 2023 |
| HP            | 843E                        | [dbbfb83ae4](https://linux-hardware.org/?probe=dbbfb83ae4) | Aug 03, 2023 |
| HP            | 843E                        | [952db006c3](https://linux-hardware.org/?probe=952db006c3) | Aug 03, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [6b22568f3f](https://linux-hardware.org/?probe=6b22568f3f) | Aug 03, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [9dcbf7b10c](https://linux-hardware.org/?probe=9dcbf7b10c) | Aug 03, 2023 |
| ASUSTek       | ROG STRIX B760-A GAMING ... | [f629b6e16e](https://linux-hardware.org/?probe=f629b6e16e) | Aug 03, 2023 |
| Win elemen... | M600                        | [b9537c621c](https://linux-hardware.org/?probe=b9537c621c) | Aug 02, 2023 |
| Gigabyte      | Z690 AORUS ELITE AX         | [0e28c2aae2](https://linux-hardware.org/?probe=0e28c2aae2) | Aug 02, 2023 |
| Intel         | DH67BL AAG10189-211         | [db043e1572](https://linux-hardware.org/?probe=db043e1572) | Aug 02, 2023 |
| ECS           | H61H2-M6                    | [12990c5c80](https://linux-hardware.org/?probe=12990c5c80) | Aug 02, 2023 |
| Supermicro    | X9DAi                       | [d7390704d8](https://linux-hardware.org/?probe=d7390704d8) | Aug 02, 2023 |
| Dell          | 0FR6WH A01                  | [38feb4d1f7](https://linux-hardware.org/?probe=38feb4d1f7) | Aug 02, 2023 |
| Gigabyte      | Z97M-DS3H                   | [8bc1531bf6](https://linux-hardware.org/?probe=8bc1531bf6) | Aug 02, 2023 |
| Lenovo        | Bantry CRB SDK0E50510 WI... | [69cd0aae71](https://linux-hardware.org/?probe=69cd0aae71) | Aug 02, 2023 |
| Dell          | 0GRJJ9 A01                  | [dca7ee3fdc](https://linux-hardware.org/?probe=dca7ee3fdc) | Aug 02, 2023 |
| Pegatron      | Benicia                     | [5db4c563c6](https://linux-hardware.org/?probe=5db4c563c6) | Aug 01, 2023 |
| MSI           | MS-7380                     | [6f3e83e5a2](https://linux-hardware.org/?probe=6f3e83e5a2) | Aug 01, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [9b314ec48b](https://linux-hardware.org/?probe=9b314ec48b) | Aug 01, 2023 |
| Gigabyte      | P35-DS4                     | [9116e4042c](https://linux-hardware.org/?probe=9116e4042c) | Aug 01, 2023 |
| HP            | 18E4                        | [20ebffd9a8](https://linux-hardware.org/?probe=20ebffd9a8) | Aug 01, 2023 |
| ECS           | H61H2-M6                    | [836267e5f7](https://linux-hardware.org/?probe=836267e5f7) | Aug 01, 2023 |
| HP            | 2B2C                        | [3f0b3f8811](https://linux-hardware.org/?probe=3f0b3f8811) | Aug 01, 2023 |
| Dell          | 06NWYK A00                  | [1c3a3db0ec](https://linux-hardware.org/?probe=1c3a3db0ec) | Aug 01, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [668eb36a4a](https://linux-hardware.org/?probe=668eb36a4a) | Aug 01, 2023 |
| Dell          | 09KPNV A01                  | [1768a6834a](https://linux-hardware.org/?probe=1768a6834a) | Aug 01, 2023 |
| Dell          | OptiPlex 980                | [7ec85c3865](https://linux-hardware.org/?probe=7ec85c3865) | Aug 01, 2023 |
| HP            | 3048h                       | [02df08e8ab](https://linux-hardware.org/?probe=02df08e8ab) | Jul 31, 2023 |
| HP            | 3398                        | [c271d5d40e](https://linux-hardware.org/?probe=c271d5d40e) | Jul 31, 2023 |
| Gigabyte      | B85M-D3H                    | [9ddb5c2ea3](https://linux-hardware.org/?probe=9ddb5c2ea3) | Jul 31, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [4e4e6cd3eb](https://linux-hardware.org/?probe=4e4e6cd3eb) | Jul 31, 2023 |
| Dell          | 08NPPY A00                  | [26acefc1b8](https://linux-hardware.org/?probe=26acefc1b8) | Jul 31, 2023 |
| ASUSTek       | P6T SE                      | [aead9f82b2](https://linux-hardware.org/?probe=aead9f82b2) | Jul 31, 2023 |
| ASUSTek       | P6T SE                      | [9e8f131101](https://linux-hardware.org/?probe=9e8f131101) | Jul 31, 2023 |
| HP            | 212A                        | [4f81f09718](https://linux-hardware.org/?probe=4f81f09718) | Jul 30, 2023 |
| HP            | 3398                        | [444f9d27d5](https://linux-hardware.org/?probe=444f9d27d5) | Jul 30, 2023 |
| Intel         | DH67BL AAG10189-211         | [33ac97b0c6](https://linux-hardware.org/?probe=33ac97b0c6) | Jul 30, 2023 |
| Gigabyte      | X58A-UD7                    | [98759e7a12](https://linux-hardware.org/?probe=98759e7a12) | Jul 30, 2023 |
| Acer          | Aspire G7713                | [e0624d410e](https://linux-hardware.org/?probe=e0624d410e) | Jul 30, 2023 |
| ASUSTek       | PRIME A320M-K               | [de6e904009](https://linux-hardware.org/?probe=de6e904009) | Jul 30, 2023 |
| ASUSTek       | PRIME A320M-K               | [6928788f05](https://linux-hardware.org/?probe=6928788f05) | Jul 30, 2023 |
| Lenovo        | SHARKBAY 31900058 STD       | [4ff0e84129](https://linux-hardware.org/?probe=4ff0e84129) | Jul 30, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [fe48f2b4d4](https://linux-hardware.org/?probe=fe48f2b4d4) | Jul 30, 2023 |
| ASUSTek       | PRIME Z270-A                | [eb13fb97fb](https://linux-hardware.org/?probe=eb13fb97fb) | Jul 30, 2023 |
| Dell          | 0RF705                      | [9370437c75](https://linux-hardware.org/?probe=9370437c75) | Jul 30, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [d788283742](https://linux-hardware.org/?probe=d788283742) | Jul 30, 2023 |
| Lenovo        | 0C48431 WIN                 | [4e0d5538b2](https://linux-hardware.org/?probe=4e0d5538b2) | Jul 30, 2023 |
| Gigabyte      | B460M DS3H V2               | [42b35cd473](https://linux-hardware.org/?probe=42b35cd473) | Jul 30, 2023 |
| Dell          | 0RF705                      | [fe3118bd3c](https://linux-hardware.org/?probe=fe3118bd3c) | Jul 30, 2023 |
| ASUSTek       | PRIME A320M-K               | [a4d7919584](https://linux-hardware.org/?probe=a4d7919584) | Jul 29, 2023 |
| MSI           | Z270 TOMAHAWK OPT BOOST     | [9cc0db1a3d](https://linux-hardware.org/?probe=9cc0db1a3d) | Jul 29, 2023 |
| Intel         | D33217GKE G76540-203        | [d551e6904d](https://linux-hardware.org/?probe=d551e6904d) | Jul 29, 2023 |
| Medion        | H110H4-EM                   | [7c2b005f92](https://linux-hardware.org/?probe=7c2b005f92) | Jul 29, 2023 |
| Lenovo        | SHARKBAY NOK                | [6e89d2949a](https://linux-hardware.org/?probe=6e89d2949a) | Jul 29, 2023 |
| Positivo      | POS-EINM70CS POSITIVO       | [bee5e6175b](https://linux-hardware.org/?probe=bee5e6175b) | Jul 29, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [a69e475106](https://linux-hardware.org/?probe=a69e475106) | Jul 29, 2023 |
| HP            | 2B1B                        | [8454c98fbb](https://linux-hardware.org/?probe=8454c98fbb) | Jul 29, 2023 |
| Gigabyte      | X570S AERO G                | [d500093891](https://linux-hardware.org/?probe=d500093891) | Jul 28, 2023 |
| ASUSTek       | PRIME H370M-PLUS            | [099c883745](https://linux-hardware.org/?probe=099c883745) | Jul 28, 2023 |
| Lenovo        | NO DPK                      | [15d3803dcc](https://linux-hardware.org/?probe=15d3803dcc) | Jul 28, 2023 |
| ASRock        | H81 Pro BTC R2.0            | [b322ef8e74](https://linux-hardware.org/?probe=b322ef8e74) | Jul 28, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [d4774401e3](https://linux-hardware.org/?probe=d4774401e3) | Jul 28, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [45c79840cc](https://linux-hardware.org/?probe=45c79840cc) | Jul 28, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [735d4f8f84](https://linux-hardware.org/?probe=735d4f8f84) | Jul 28, 2023 |
| Dell          | 0FR6WH A01                  | [d20434fd50](https://linux-hardware.org/?probe=d20434fd50) | Jul 28, 2023 |
| HP            | 2B0B 100                    | [586d94bacc](https://linux-hardware.org/?probe=586d94bacc) | Jul 28, 2023 |
| HP            | 2B0B 100                    | [da33776470](https://linux-hardware.org/?probe=da33776470) | Jul 28, 2023 |
| HP            | 0A04h                       | [aaf7bb9453](https://linux-hardware.org/?probe=aaf7bb9453) | Jul 28, 2023 |
| ASUSTek       | PRIME X470-PRO              | [f689c31a17](https://linux-hardware.org/?probe=f689c31a17) | Jul 28, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [ccfe4b2234](https://linux-hardware.org/?probe=ccfe4b2234) | Jul 27, 2023 |
| ASRock        | X670E Pro RS                | [27a13f80b2](https://linux-hardware.org/?probe=27a13f80b2) | Jul 27, 2023 |
| Medion        | MS-7616                     | [349360bcba](https://linux-hardware.org/?probe=349360bcba) | Jul 27, 2023 |
| MSI           | MS-B1831                    | [35f0e625f1](https://linux-hardware.org/?probe=35f0e625f1) | Jul 27, 2023 |
| Pegatron      | 2A99                        | [068f8c77fd](https://linux-hardware.org/?probe=068f8c77fd) | Jul 27, 2023 |
| Medion        | H110H4-EM                   | [080a30ad72](https://linux-hardware.org/?probe=080a30ad72) | Jul 27, 2023 |
| Gigabyte      | Z97M-DS3H                   | [f0bd5c3409](https://linux-hardware.org/?probe=f0bd5c3409) | Jul 27, 2023 |
| ASUSTek       | P6X58D PREMIUM              | [0a84eeb8e2](https://linux-hardware.org/?probe=0a84eeb8e2) | Jul 26, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [d54ad601d0](https://linux-hardware.org/?probe=d54ad601d0) | Jul 26, 2023 |
| Alienware     | 04VWF2 A02                  | [e6c2096ce5](https://linux-hardware.org/?probe=e6c2096ce5) | Jul 26, 2023 |
| Intel         | D33217GKE G76540-203        | [b4089ed499](https://linux-hardware.org/?probe=b4089ed499) | Jul 26, 2023 |
| Cincoze       | DS-1300.00.001              | [e359107d20](https://linux-hardware.org/?probe=e359107d20) | Jul 26, 2023 |
| Gigabyte      | Z490 UD                     | [29aa67256f](https://linux-hardware.org/?probe=29aa67256f) | Jul 26, 2023 |
| Cincoze       | DS-1300.00.001              | [01309bf370](https://linux-hardware.org/?probe=01309bf370) | Jul 26, 2023 |
| AZW           | SEi                         | [115142c288](https://linux-hardware.org/?probe=115142c288) | Jul 26, 2023 |
| ASUSTek       | PRIME X370-PRO              | [45e8471971](https://linux-hardware.org/?probe=45e8471971) | Jul 26, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | [88dd1326f2](https://linux-hardware.org/?probe=88dd1326f2) | Jul 26, 2023 |
| HP            | 8169                        | [f2885ba2de](https://linux-hardware.org/?probe=f2885ba2de) | Jul 26, 2023 |
| Intel         | X79                         | [46434d0a2c](https://linux-hardware.org/?probe=46434d0a2c) | Jul 26, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [ded7cda68f](https://linux-hardware.org/?probe=ded7cda68f) | Jul 26, 2023 |
| Gigabyte      | B550M DS3H                  | [94a5fdec96](https://linux-hardware.org/?probe=94a5fdec96) | Jul 26, 2023 |
| ASUSTek       | Rampage II GENE             | [c3df12e6ea](https://linux-hardware.org/?probe=c3df12e6ea) | Jul 25, 2023 |
| MSI           | A68HM-E33 V2                | [858b41037e](https://linux-hardware.org/?probe=858b41037e) | Jul 25, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [5e77384bb8](https://linux-hardware.org/?probe=5e77384bb8) | Jul 25, 2023 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [a08da8df65](https://linux-hardware.org/?probe=a08da8df65) | Jul 25, 2023 |
| Intel         | X79                         | [520788cdc8](https://linux-hardware.org/?probe=520788cdc8) | Jul 25, 2023 |
| Intel         | DQ965GF AAD41676-601        | [384577dee3](https://linux-hardware.org/?probe=384577dee3) | Jul 25, 2023 |
| Dell          | 0M5DCD A00                  | [f03fba3891](https://linux-hardware.org/?probe=f03fba3891) | Jul 25, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [b5380c8836](https://linux-hardware.org/?probe=b5380c8836) | Jul 25, 2023 |
| ASRock        | B450M Pro4                  | [ab5995e72d](https://linux-hardware.org/?probe=ab5995e72d) | Jul 25, 2023 |
| Gigabyte      | X570 AORUS XTREME           | [9b3ed16747](https://linux-hardware.org/?probe=9b3ed16747) | Jul 25, 2023 |
| ASUSTek       | UN45                        | [ea2bebc887](https://linux-hardware.org/?probe=ea2bebc887) | Jul 25, 2023 |
| MSI           | Z270 TOMAHAWK OPT BOOST     | [6417b2e0e3](https://linux-hardware.org/?probe=6417b2e0e3) | Jul 24, 2023 |
| Dell          | 0U880P A01                  | [91d0931125](https://linux-hardware.org/?probe=91d0931125) | Jul 24, 2023 |
| Pegatron      | Benicia                     | [ad8b67f72e](https://linux-hardware.org/?probe=ad8b67f72e) | Jul 24, 2023 |
| ASRock        | Z690 Phantom Gaming 4       | [0a334297a5](https://linux-hardware.org/?probe=0a334297a5) | Jul 24, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [ce1c4f4026](https://linux-hardware.org/?probe=ce1c4f4026) | Jul 24, 2023 |
| Dell          | 088DT1 A01                  | [f796a78d27](https://linux-hardware.org/?probe=f796a78d27) | Jul 24, 2023 |
| Dell          | 088DT1 A01                  | [e130e8c0f2](https://linux-hardware.org/?probe=e130e8c0f2) | Jul 24, 2023 |
| Gigabyte      | Z97M-DS3H                   | [816a8d70bb](https://linux-hardware.org/?probe=816a8d70bb) | Jul 24, 2023 |
| Intel         | X79                         | [c0c619638e](https://linux-hardware.org/?probe=c0c619638e) | Jul 24, 2023 |
| Lenovo        | MAHOBAY NOK                 | [e391e5bca6](https://linux-hardware.org/?probe=e391e5bca6) | Jul 24, 2023 |
| Gigabyte      | X570 AORUS XTREME           | [955c69d2b2](https://linux-hardware.org/?probe=955c69d2b2) | Jul 24, 2023 |
| Fujitsu       | FujitsuTP7000 -1            | [96e8002856](https://linux-hardware.org/?probe=96e8002856) | Jul 24, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [f6c6668305](https://linux-hardware.org/?probe=f6c6668305) | Jul 23, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS D4     | [4c4109b8f3](https://linux-hardware.org/?probe=4c4109b8f3) | Jul 23, 2023 |
| Gigabyte      | Z370P D3-CF                 | [5b4c2db6cf](https://linux-hardware.org/?probe=5b4c2db6cf) | Jul 23, 2023 |
| HP            | 81BB                        | [75973dea3f](https://linux-hardware.org/?probe=75973dea3f) | Jul 23, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS D4     | [d89bdeec87](https://linux-hardware.org/?probe=d89bdeec87) | Jul 23, 2023 |
| Gigabyte      | X570S AERO G                | [8e3dbf7ff9](https://linux-hardware.org/?probe=8e3dbf7ff9) | Jul 23, 2023 |
| ASRock        | 960GM-GS3 FX                | [3ddda4afa3](https://linux-hardware.org/?probe=3ddda4afa3) | Jul 23, 2023 |
| ASRock        | 4X4-4000 Series             | [d95040e760](https://linux-hardware.org/?probe=d95040e760) | Jul 23, 2023 |
| CWWK          | CW-AD4L-N V1                | [8d9ea8214d](https://linux-hardware.org/?probe=8d9ea8214d) | Jul 23, 2023 |
| Dell          | 02YYK5 A01                  | [13da37735a](https://linux-hardware.org/?probe=13da37735a) | Jul 23, 2023 |
| BESSTAR Te... | JB9                         | [ea014bad4f](https://linux-hardware.org/?probe=ea014bad4f) | Jul 22, 2023 |
| MSI           | MEG Z490I UNIFY             | [9a414330bf](https://linux-hardware.org/?probe=9a414330bf) | Jul 22, 2023 |
| Fujitsu       | D3403-A1 S26361-D3403-A1    | [9f52ae219f](https://linux-hardware.org/?probe=9f52ae219f) | Jul 22, 2023 |
| Shenzhen M... | F7BFC                       | [a9639fb963](https://linux-hardware.org/?probe=a9639fb963) | Jul 22, 2023 |
| ASUSTek       | SABERTOOTH X58              | [8841163f3b](https://linux-hardware.org/?probe=8841163f3b) | Jul 22, 2023 |
| ASRock        | J3355B-ITX                  | [3edbf4710e](https://linux-hardware.org/?probe=3edbf4710e) | Jul 22, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [50641feb57](https://linux-hardware.org/?probe=50641feb57) | Jul 22, 2023 |
| Intel         | DH61WW AAG23116-206         | [9ab47777ca](https://linux-hardware.org/?probe=9ab47777ca) | Jul 21, 2023 |
| HP            | 2B0B 100                    | [42df5ab3e8](https://linux-hardware.org/?probe=42df5ab3e8) | Jul 21, 2023 |
| Gigabyte      | H270-HD3-CF                 | [73a56d2df7](https://linux-hardware.org/?probe=73a56d2df7) | Jul 21, 2023 |
| Dell          | 00010C A00                  | [40543af7a5](https://linux-hardware.org/?probe=40543af7a5) | Jul 21, 2023 |
| Intel         | DP67BG AAG10491-400         | [084b222fa7](https://linux-hardware.org/?probe=084b222fa7) | Jul 21, 2023 |
| MSI           | Z170A GAMING M7             | [0e79ff628d](https://linux-hardware.org/?probe=0e79ff628d) | Jul 21, 2023 |
| MW            | NAS-N5105                   | [1a5c7ab436](https://linux-hardware.org/?probe=1a5c7ab436) | Jul 20, 2023 |
| Intel         | DP67BG AAG10491-400         | [e0ff2f40fa](https://linux-hardware.org/?probe=e0ff2f40fa) | Jul 20, 2023 |
| ECS           | H61H2-MV                    | [69a0cd41e0](https://linux-hardware.org/?probe=69a0cd41e0) | Jul 20, 2023 |
| ASUSTek       | ROG Maximus XII FORMULA     | [a77eda6cc3](https://linux-hardware.org/?probe=a77eda6cc3) | Jul 20, 2023 |
| ASUSTek       | ROG Maximus XII FORMULA     | [ad0df808cb](https://linux-hardware.org/?probe=ad0df808cb) | Jul 20, 2023 |
| Dell          | 0D28YY A01                  | [6b01835487](https://linux-hardware.org/?probe=6b01835487) | Jul 20, 2023 |
| Gigabyte      | Z77MX-D3H                   | [044cf93e31](https://linux-hardware.org/?probe=044cf93e31) | Jul 20, 2023 |
| ASRock        | X99M Extreme4               | [caf88d9f9d](https://linux-hardware.org/?probe=caf88d9f9d) | Jul 20, 2023 |
| Dell          | 0HN7XN A01                  | [567369da67](https://linux-hardware.org/?probe=567369da67) | Jul 20, 2023 |
| Gigabyte      | 990FXA-UD3                  | [8be5de827d](https://linux-hardware.org/?probe=8be5de827d) | Jul 20, 2023 |
| Dell          | 0HD5W2 A01                  | [26c19ee81f](https://linux-hardware.org/?probe=26c19ee81f) | Jul 19, 2023 |
| ASUSTek       | H97I-PLUS                   | [d244fb3ef9](https://linux-hardware.org/?probe=d244fb3ef9) | Jul 19, 2023 |
| Unknown       | Unknown                     | [39d3820e1a](https://linux-hardware.org/?probe=39d3820e1a) | Jul 19, 2023 |
| Lenovo        | 310B SDK0J40705 WIN 3425... | [ececa8856a](https://linux-hardware.org/?probe=ececa8856a) | Jul 19, 2023 |
| Dell          | 0XC7MM A00                  | [8d7dd80fa4](https://linux-hardware.org/?probe=8d7dd80fa4) | Jul 19, 2023 |
| ASUSTek       | ROG Maximus XII EXTREME     | [0f7fea54eb](https://linux-hardware.org/?probe=0f7fea54eb) | Jul 19, 2023 |
| MSI           | PRO B660M-E DDR4            | [62aa29ec8e](https://linux-hardware.org/?probe=62aa29ec8e) | Jul 19, 2023 |
| Lenovo        | 36C5 SDK0K17763 WIN 1801... | [290f64f841](https://linux-hardware.org/?probe=290f64f841) | Jul 19, 2023 |
| Dell          | 0HN7XN A01                  | [a7c167f16f](https://linux-hardware.org/?probe=a7c167f16f) | Jul 19, 2023 |
| MSI           | H81M-E33                    | [dc821e7080](https://linux-hardware.org/?probe=dc821e7080) | Jul 19, 2023 |
| Gigabyte      | H61M-DS2                    | [06e511f834](https://linux-hardware.org/?probe=06e511f834) | Jul 19, 2023 |
| ASUSTek       | H97M-E                      | [7171de16ea](https://linux-hardware.org/?probe=7171de16ea) | Jul 19, 2023 |
| Gigabyte      | H61M-DS2                    | [0c537839b2](https://linux-hardware.org/?probe=0c537839b2) | Jul 19, 2023 |
| ASUSTek       | PRIME Z390-A                | [94856d413f](https://linux-hardware.org/?probe=94856d413f) | Jul 19, 2023 |
| Gigabyte      | B450M DS3H V2               | [67db76ffed](https://linux-hardware.org/?probe=67db76ffed) | Jul 19, 2023 |
| Alienware     | 0VDT73 A00                  | [dfdf19c0f1](https://linux-hardware.org/?probe=dfdf19c0f1) | Jul 19, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [140d426127](https://linux-hardware.org/?probe=140d426127) | Jul 18, 2023 |
| Dell          | 02YRK5 A02                  | [a09aa96e91](https://linux-hardware.org/?probe=a09aa96e91) | Jul 18, 2023 |
| HP            | 18E7                        | [bddd22fb18](https://linux-hardware.org/?probe=bddd22fb18) | Jul 18, 2023 |
| ASUSTek       | PRIME Z370-A II             | [6ca4720242](https://linux-hardware.org/?probe=6ca4720242) | Jul 18, 2023 |
| HP            | 889C                        | [3124074b5a](https://linux-hardware.org/?probe=3124074b5a) | Jul 18, 2023 |
| AMI           | Intel                       | [fb562a8b94](https://linux-hardware.org/?probe=fb562a8b94) | Jul 18, 2023 |
| AMI           | Intel                       | [52cb51f3c6](https://linux-hardware.org/?probe=52cb51f3c6) | Jul 18, 2023 |
| HP            | 304Ah                       | [649b673c7e](https://linux-hardware.org/?probe=649b673c7e) | Jul 18, 2023 |
| HP            | 304Ah                       | [8cd2a48010](https://linux-hardware.org/?probe=8cd2a48010) | Jul 18, 2023 |
| ASUSTek       | P8H61-M LE/BR               | [0d9c612141](https://linux-hardware.org/?probe=0d9c612141) | Jul 17, 2023 |
| Gigabyte      | GA-78LMT-S2                 | [a58b13cf37](https://linux-hardware.org/?probe=a58b13cf37) | Jul 17, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [0f497ef7f8](https://linux-hardware.org/?probe=0f497ef7f8) | Jul 17, 2023 |
| Dell          | 0GXM1W A00                  | [692ba8a4af](https://linux-hardware.org/?probe=692ba8a4af) | Jul 17, 2023 |
| MSI           | MAG B760 TOMAHAWK WIFI      | [e7e1588ebf](https://linux-hardware.org/?probe=e7e1588ebf) | Jul 17, 2023 |
| ASRock Ind... | NUC-1220P                   | [3b1cedb39d](https://linux-hardware.org/?probe=3b1cedb39d) | Jul 17, 2023 |
| MSI           | MAG B760 TOMAHAWK WIFI      | [b729a884f0](https://linux-hardware.org/?probe=b729a884f0) | Jul 17, 2023 |
| Lenovo        | 36C5 SDK0K17763 WIN 1801... | [d4b5c25500](https://linux-hardware.org/?probe=d4b5c25500) | Jul 17, 2023 |
| ASUSTek       | SABERTOOTH X58              | [d206dfdfed](https://linux-hardware.org/?probe=d206dfdfed) | Jul 17, 2023 |
| Dell          | 0PC5F7 A02                  | [b6fe9245e4](https://linux-hardware.org/?probe=b6fe9245e4) | Jul 17, 2023 |
| ASRock Ind... | NUC-1220P                   | [8094cfcbe6](https://linux-hardware.org/?probe=8094cfcbe6) | Jul 16, 2023 |
| HP            | 82F2 A01                    | [d4033cf114](https://linux-hardware.org/?probe=d4033cf114) | Jul 16, 2023 |
| MSI           | Z97 GAMING 7                | [28c6cd48b8](https://linux-hardware.org/?probe=28c6cd48b8) | Jul 16, 2023 |
| MSI           | Z97 GAMING 7                | [9ef499d31f](https://linux-hardware.org/?probe=9ef499d31f) | Jul 16, 2023 |
| MSI           | MAG Z690 TORPEDO            | [8f4a9f7202](https://linux-hardware.org/?probe=8f4a9f7202) | Jul 16, 2023 |
| Dell          | 0CRH6C A02                  | [abf1be3307](https://linux-hardware.org/?probe=abf1be3307) | Jul 16, 2023 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | [20ee7f8016](https://linux-hardware.org/?probe=20ee7f8016) | Jul 16, 2023 |
| MSI           | PRESTIGE X570 CREATION      | [08d99231a6](https://linux-hardware.org/?probe=08d99231a6) | Jul 16, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | [7fe3a6b5b2](https://linux-hardware.org/?probe=7fe3a6b5b2) | Jul 16, 2023 |
| HP            | ProLiant MicroServer Gen... | [ec8fee15ed](https://linux-hardware.org/?probe=ec8fee15ed) | Jul 16, 2023 |
| Shenzhen M... | F7BFC                       | [a6bcd9758f](https://linux-hardware.org/?probe=a6bcd9758f) | Jul 15, 2023 |
| Shenzhen M... | F7BFC                       | [c7eadb3912](https://linux-hardware.org/?probe=c7eadb3912) | Jul 15, 2023 |
| MSI           | MS-7369                     | [7cd5c6d6f0](https://linux-hardware.org/?probe=7cd5c6d6f0) | Jul 15, 2023 |
| ASUSTek       | PRIME B450M-A               | [8296b2914a](https://linux-hardware.org/?probe=8296b2914a) | Jul 15, 2023 |
| Pegatron      | 2AB5                        | [f625288322](https://linux-hardware.org/?probe=f625288322) | Jul 15, 2023 |
| Dell          | 0D24M8 A01                  | [9e82c71281](https://linux-hardware.org/?probe=9e82c71281) | Jul 15, 2023 |
| MSI           | Z590-A PRO                  | [8c4fe85b51](https://linux-hardware.org/?probe=8c4fe85b51) | Jul 15, 2023 |
| ASUSTek       | PRIME B450M-A               | [7d3eea9c76](https://linux-hardware.org/?probe=7d3eea9c76) | Jul 15, 2023 |
| HP            | 212A                        | [5ed0059210](https://linux-hardware.org/?probe=5ed0059210) | Jul 15, 2023 |
| ASUSTek       | H81M-V3                     | [017671472c](https://linux-hardware.org/?probe=017671472c) | Jul 15, 2023 |
| ASUSTek       | AT3IONT-I                   | [f1a7e1dbb3](https://linux-hardware.org/?probe=f1a7e1dbb3) | Jul 15, 2023 |
| ASUSTek       | PRIME Z490-P                | [9eff556aca](https://linux-hardware.org/?probe=9eff556aca) | Jul 15, 2023 |
| ASRock        | G41M-VS3                    | [f472934f38](https://linux-hardware.org/?probe=f472934f38) | Jul 15, 2023 |
| Intel         | DH67BL AAG10189-211         | [3ac8b2e91d](https://linux-hardware.org/?probe=3ac8b2e91d) | Jul 14, 2023 |
| Gigabyte      | H510M H                     | [8771f0ddd0](https://linux-hardware.org/?probe=8771f0ddd0) | Jul 14, 2023 |
| Gigabyte      | Z97M-DS3H                   | [9e829a5538](https://linux-hardware.org/?probe=9e829a5538) | Jul 14, 2023 |
| Dell          | 0GXM1W A00                  | [cbdd93f7d6](https://linux-hardware.org/?probe=cbdd93f7d6) | Jul 14, 2023 |
| ASRock        | B650M PG Riptide WiFi       | [62890116b3](https://linux-hardware.org/?probe=62890116b3) | Jul 14, 2023 |
| ASRock        | B650M PG Riptide WiFi       | [476c241a58](https://linux-hardware.org/?probe=476c241a58) | Jul 14, 2023 |
| Huanan        | X99-F8 V5.0 JX              | [a45c6e5f27](https://linux-hardware.org/?probe=a45c6e5f27) | Jul 14, 2023 |
| ASUSTek       | PRIME A320M-K               | [6776e11ac9](https://linux-hardware.org/?probe=6776e11ac9) | Jul 14, 2023 |
| Unknown       | Unknown                     | [cdf60a9582](https://linux-hardware.org/?probe=cdf60a9582) | Jul 14, 2023 |
| ASUSTek       | J1800I-A                    | [ce7f031b0a](https://linux-hardware.org/?probe=ce7f031b0a) | Jul 14, 2023 |
| ASUSTek       | P5E-V HDMI                  | [460e520a69](https://linux-hardware.org/?probe=460e520a69) | Jul 13, 2023 |
| Shenzhen M... | F7BFC                       | [a0c045bcd6](https://linux-hardware.org/?probe=a0c045bcd6) | Jul 13, 2023 |
| Shenzhen M... | F7BFC                       | [c0c4f2abb6](https://linux-hardware.org/?probe=c0c4f2abb6) | Jul 13, 2023 |
| Acer          | Aspire TC-895 V:1.0         | [bc805d82a7](https://linux-hardware.org/?probe=bc805d82a7) | Jul 13, 2023 |
| ASUSTek       | PRIME H410M-K               | [0dbf02ef16](https://linux-hardware.org/?probe=0dbf02ef16) | Jul 13, 2023 |
| ASUSTek       | P8Z68-V LX                  | [7c9bb65c6a](https://linux-hardware.org/?probe=7c9bb65c6a) | Jul 13, 2023 |
| ASUSTek       | P8Z68-V LX                  | [3795772e96](https://linux-hardware.org/?probe=3795772e96) | Jul 13, 2023 |
| Unknown       | Unknown                     | [beea313884](https://linux-hardware.org/?probe=beea313884) | Jul 13, 2023 |
| ASUSTek       | AT3IONT-I                   | [773d5ee9aa](https://linux-hardware.org/?probe=773d5ee9aa) | Jul 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | [3428c47b0c](https://linux-hardware.org/?probe=3428c47b0c) | Jul 13, 2023 |
| Dell          | 00V62H A01                  | [7462f134fc](https://linux-hardware.org/?probe=7462f134fc) | Jul 13, 2023 |
| HP            | 1495                        | [fdbc0b7f33](https://linux-hardware.org/?probe=fdbc0b7f33) | Jul 13, 2023 |
| Dell          | 00V62H A01                  | [f2878312b2](https://linux-hardware.org/?probe=f2878312b2) | Jul 12, 2023 |
| Biostar       | H61MGV                      | [4fadeeb5bd](https://linux-hardware.org/?probe=4fadeeb5bd) | Jul 12, 2023 |
| Gigabyte      | Z97MX-Gaming 5              | [f8ffcb4828](https://linux-hardware.org/?probe=f8ffcb4828) | Jul 12, 2023 |
| HP            | 1495                        | [8fa2ff9487](https://linux-hardware.org/?probe=8fa2ff9487) | Jul 12, 2023 |
| Gigabyte      | Z270X-Gaming 5              | [949ca22bb2](https://linux-hardware.org/?probe=949ca22bb2) | Jul 12, 2023 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | [40281279ab](https://linux-hardware.org/?probe=40281279ab) | Jul 12, 2023 |
| HP            | 81BB                        | [ae0ad9c6fb](https://linux-hardware.org/?probe=ae0ad9c6fb) | Jul 12, 2023 |
| ASUSTek       | P8Z68-V PRO                 | [077367f0bd](https://linux-hardware.org/?probe=077367f0bd) | Jul 12, 2023 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [58c9a4c19c](https://linux-hardware.org/?probe=58c9a4c19c) | Jul 12, 2023 |
| Dell          | 0CRH6C A02                  | [333813fa10](https://linux-hardware.org/?probe=333813fa10) | Jul 11, 2023 |
| Dell          | 0CRH6C A02                  | [66fb93438f](https://linux-hardware.org/?probe=66fb93438f) | Jul 11, 2023 |
| Gigabyte      | B450 AORUS M                | [500fee1ce5](https://linux-hardware.org/?probe=500fee1ce5) | Jul 11, 2023 |
| ASUSTek       | PRIME B450M-A               | [6c541c67b9](https://linux-hardware.org/?probe=6c541c67b9) | Jul 11, 2023 |
| Dell          | 09M8Y8 A01                  | [7a6bfcf1a9](https://linux-hardware.org/?probe=7a6bfcf1a9) | Jul 11, 2023 |
| Dell          | 09M8Y8 A01                  | [2397913be3](https://linux-hardware.org/?probe=2397913be3) | Jul 11, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [6481c63fee](https://linux-hardware.org/?probe=6481c63fee) | Jul 11, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | [9b3b477b44](https://linux-hardware.org/?probe=9b3b477b44) | Jul 11, 2023 |
| Positivo      | POS-PIQ77CL POSITIVO        | [bad8c925e6](https://linux-hardware.org/?probe=bad8c925e6) | Jul 11, 2023 |
| Positivo      | POS-PIQ77CL POSITIVO        | [f754f1e59b](https://linux-hardware.org/?probe=f754f1e59b) | Jul 11, 2023 |
| ASRock        | H81M                        | [042e2e3b56](https://linux-hardware.org/?probe=042e2e3b56) | Jul 11, 2023 |
| ASRock        | H81M                        | [c4b398d08c](https://linux-hardware.org/?probe=c4b398d08c) | Jul 11, 2023 |
| Gigabyte      | B650I AORUS ULTRA           | [7dc652ae30](https://linux-hardware.org/?probe=7dc652ae30) | Jul 11, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI      | [8131ccf070](https://linux-hardware.org/?probe=8131ccf070) | Jul 11, 2023 |
| HP            | 212A                        | [65b433407e](https://linux-hardware.org/?probe=65b433407e) | Jul 11, 2023 |
| HP            | 3047h                       | [1a4c2d4702](https://linux-hardware.org/?probe=1a4c2d4702) | Jul 11, 2023 |
| ASUSTek       | H110M-A                     | [b2de29a3db](https://linux-hardware.org/?probe=b2de29a3db) | Jul 10, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [00e22b8fa7](https://linux-hardware.org/?probe=00e22b8fa7) | Jul 10, 2023 |
| ASRock        | Z390 Phantom Gaming-ITX/... | [3aae868be2](https://linux-hardware.org/?probe=3aae868be2) | Jul 10, 2023 |
| ASRock        | Z390 Phantom Gaming-ITX/... | [08c3b18c08](https://linux-hardware.org/?probe=08c3b18c08) | Jul 10, 2023 |
| WeiBu         | ADL-N Prod                  | [23746411d7](https://linux-hardware.org/?probe=23746411d7) | Jul 10, 2023 |
| Avalue        | NUC-APL E9697JAI006R        | [8e289dc3f9](https://linux-hardware.org/?probe=8e289dc3f9) | Jul 10, 2023 |
| Avalue        | NUC-APL E9697JAI006R        | [8f7a02d8b5](https://linux-hardware.org/?probe=8f7a02d8b5) | Jul 10, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [7c9b47b69f](https://linux-hardware.org/?probe=7c9b47b69f) | Jul 10, 2023 |
| Dell          | 02YRK5 A02                  | [113d7e1853](https://linux-hardware.org/?probe=113d7e1853) | Jul 10, 2023 |
| Dell          | 0JP3NX A01                  | [fb5723d423](https://linux-hardware.org/?probe=fb5723d423) | Jul 10, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [7c3e56e08a](https://linux-hardware.org/?probe=7c3e56e08a) | Jul 10, 2023 |
| MSI           | B550-A PRO                  | [483109bdd9](https://linux-hardware.org/?probe=483109bdd9) | Jul 09, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [08ae4ea22e](https://linux-hardware.org/?probe=08ae4ea22e) | Jul 09, 2023 |
| ASUSTek       | P8Z77-V                     | [13ece994a6](https://linux-hardware.org/?probe=13ece994a6) | Jul 09, 2023 |
| Gigabyte      | P55-USB3L                   | [b225c530bd](https://linux-hardware.org/?probe=b225c530bd) | Jul 09, 2023 |
| Unknown       | CoffeeLake                  | [b3f96a87d5](https://linux-hardware.org/?probe=b3f96a87d5) | Jul 09, 2023 |
| ASRock        | E3C224D4I-14S               | [bd2d074d07](https://linux-hardware.org/?probe=bd2d074d07) | Jul 09, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [549875a866](https://linux-hardware.org/?probe=549875a866) | Jul 09, 2023 |
| MSI           | MS-B9181                    | [4702ba374d](https://linux-hardware.org/?probe=4702ba374d) | Jul 09, 2023 |
| ECS           | A790GXM-AD3                 | [d88aa3d8d1](https://linux-hardware.org/?probe=d88aa3d8d1) | Jul 09, 2023 |
| Unknown       | X99-GT                      | [34c4fadab5](https://linux-hardware.org/?probe=34c4fadab5) | Jul 08, 2023 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | [8590628d0a](https://linux-hardware.org/?probe=8590628d0a) | Jul 08, 2023 |
| ASUSTek       | P5KC                        | [952e97925b](https://linux-hardware.org/?probe=952e97925b) | Jul 08, 2023 |
| HP            | 3399                        | [432d638098](https://linux-hardware.org/?probe=432d638098) | Jul 08, 2023 |
| Unknown       | X99-GT                      | [de745928b7](https://linux-hardware.org/?probe=de745928b7) | Jul 08, 2023 |
| Lenovo        | 3730 SDK0T76463 WIN 3422... | [2ef97a52b8](https://linux-hardware.org/?probe=2ef97a52b8) | Jul 08, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [391ec4c6a8](https://linux-hardware.org/?probe=391ec4c6a8) | Jul 08, 2023 |
| ASUSTek       | TUF B360-PLUS GAMING        | [e07a2eb978](https://linux-hardware.org/?probe=e07a2eb978) | Jul 08, 2023 |
| Gigabyte      | A320M-S2H-CF                | [703f0e9012](https://linux-hardware.org/?probe=703f0e9012) | Jul 08, 2023 |
| MSI           | B550-A PRO                  | [9c6ce21357](https://linux-hardware.org/?probe=9c6ce21357) | Jul 07, 2023 |
| Gigabyte      | H61M-S2V-B3                 | [4b952291ac](https://linux-hardware.org/?probe=4b952291ac) | Jul 07, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [901c7b45c2](https://linux-hardware.org/?probe=901c7b45c2) | Jul 07, 2023 |
| Unknown       | Unknown                     | [690678e4bd](https://linux-hardware.org/?probe=690678e4bd) | Jul 07, 2023 |
| Gigabyte      | H61M-S2PV                   | [8c816d8f1b](https://linux-hardware.org/?probe=8c816d8f1b) | Jul 07, 2023 |
| Lenovo        | SHARKBAY NOK                | [ab73e6cc7f](https://linux-hardware.org/?probe=ab73e6cc7f) | Jul 07, 2023 |
| ASUSTek       | ROG Maximus Z790 HERO       | [e0e1896cc3](https://linux-hardware.org/?probe=e0e1896cc3) | Jul 07, 2023 |
| ASUSTek       | ROG Maximus Z790 HERO       | [3908772779](https://linux-hardware.org/?probe=3908772779) | Jul 07, 2023 |
| Gigabyte      | A320M-S2H-CF                | [3401b425ae](https://linux-hardware.org/?probe=3401b425ae) | Jul 07, 2023 |
| HP            | 2129                        | [12a66801ad](https://linux-hardware.org/?probe=12a66801ad) | Jul 07, 2023 |
| ASUSTek       | PRIME X370-PRO              | [23c5c27995](https://linux-hardware.org/?probe=23c5c27995) | Jul 07, 2023 |
| Gigabyte      | Z97M-DS3H                   | [9ecae424ad](https://linux-hardware.org/?probe=9ecae424ad) | Jul 07, 2023 |
| ASRock        | A320M-HD                    | [7eb9d089cf](https://linux-hardware.org/?probe=7eb9d089cf) | Jul 06, 2023 |
| ASRock        | A320M-HD                    | [2d20ffc659](https://linux-hardware.org/?probe=2d20ffc659) | Jul 06, 2023 |
| HP            | 2B2C                        | [3989b4f642](https://linux-hardware.org/?probe=3989b4f642) | Jul 06, 2023 |
| ASUSTek       | Z170-A                      | [87a26e01e6](https://linux-hardware.org/?probe=87a26e01e6) | Jul 06, 2023 |
| HP            | 3398                        | [3124ceac21](https://linux-hardware.org/?probe=3124ceac21) | Jul 06, 2023 |
| Gigabyte      | Z68MA-D2H-B3                | [04d7534d9e](https://linux-hardware.org/?probe=04d7534d9e) | Jul 06, 2023 |
| Gigabyte      | F2A68HM-H                   | [e9b7499b4d](https://linux-hardware.org/?probe=e9b7499b4d) | Jul 06, 2023 |
| Dell          | 0N4YC8 A00                  | [b6c778034c](https://linux-hardware.org/?probe=b6c778034c) | Jul 06, 2023 |
| ASUSTek       | A88X-PRO                    | [6a20985072](https://linux-hardware.org/?probe=6a20985072) | Jul 05, 2023 |
| ASRock        | H81M-HDS                    | [80074bc9c4](https://linux-hardware.org/?probe=80074bc9c4) | Jul 05, 2023 |
| MSI           | MAG B460 TOMAHAWK           | [a9f169ce16](https://linux-hardware.org/?probe=a9f169ce16) | Jul 05, 2023 |
| ASUSTek       | WS X299 SAGE                | [f97dafae6f](https://linux-hardware.org/?probe=f97dafae6f) | Jul 05, 2023 |
| Gateway       | SX2110GA                    | [1698b8292d](https://linux-hardware.org/?probe=1698b8292d) | Jul 05, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [3ec7b573fc](https://linux-hardware.org/?probe=3ec7b573fc) | Jul 05, 2023 |
| HP            | 18E4                        | [6d3964fd1b](https://linux-hardware.org/?probe=6d3964fd1b) | Jul 05, 2023 |
| HP            | 18E4                        | [8a382f8911](https://linux-hardware.org/?probe=8a382f8911) | Jul 05, 2023 |
| MSI           | PRO X670-P WIFI             | [497e454852](https://linux-hardware.org/?probe=497e454852) | Jul 05, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [44140c28bb](https://linux-hardware.org/?probe=44140c28bb) | Jul 05, 2023 |
| Lenovo        | SHARKBAY NOK                | [a89cd340ff](https://linux-hardware.org/?probe=a89cd340ff) | Jul 05, 2023 |
| MSI           | Indio                       | [b61c090b7e](https://linux-hardware.org/?probe=b61c090b7e) | Jul 05, 2023 |
| ASUSTek       | H81M-PLUS                   | [80ed1496a1](https://linux-hardware.org/?probe=80ed1496a1) | Jul 05, 2023 |
| Gigabyte      | B760M AORUS ELITE AX        | [8a5ddbbafc](https://linux-hardware.org/?probe=8a5ddbbafc) | Jul 05, 2023 |
| Gigabyte      | H110-D3A-CF                 | [bd9c7a22d6](https://linux-hardware.org/?probe=bd9c7a22d6) | Jul 05, 2023 |
| Dell          | 0MWYPT A02                  | [bbfc788fae](https://linux-hardware.org/?probe=bbfc788fae) | Jul 05, 2023 |
| ASUSTek       | SABERTOOTH Z77              | [607d40a328](https://linux-hardware.org/?probe=607d40a328) | Jul 04, 2023 |
| Intel         | B85 V5.56                   | [f9688a073f](https://linux-hardware.org/?probe=f9688a073f) | Jul 04, 2023 |
| Intel         | DH61WW AAG23116-206         | [fceaf9bea9](https://linux-hardware.org/?probe=fceaf9bea9) | Jul 04, 2023 |
| Apple         | Mac-F4208DA9 PVT            | [6c2cdc1c76](https://linux-hardware.org/?probe=6c2cdc1c76) | Jul 04, 2023 |
| HP            | 83EF                        | [5f850e2bc1](https://linux-hardware.org/?probe=5f850e2bc1) | Jul 04, 2023 |
| HP            | 212A                        | [f936acf506](https://linux-hardware.org/?probe=f936acf506) | Jul 04, 2023 |
| ADLINK Tec... | ABX-5600 A1                 | [db376a9857](https://linux-hardware.org/?probe=db376a9857) | Jul 04, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [5f1c0efa6b](https://linux-hardware.org/?probe=5f1c0efa6b) | Jul 04, 2023 |
| MSI           | PRO X670-P WIFI             | [a6658d55ff](https://linux-hardware.org/?probe=a6658d55ff) | Jul 04, 2023 |
| Dell          | 0TNDVR A00                  | [050573aef7](https://linux-hardware.org/?probe=050573aef7) | Jul 04, 2023 |
| Intel         | B85 V5.56                   | [ed7caf91c0](https://linux-hardware.org/?probe=ed7caf91c0) | Jul 03, 2023 |
| Gigabyte      | B450M DS3H V2               | [7002d2d6a8](https://linux-hardware.org/?probe=7002d2d6a8) | Jul 03, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [4b9e57acb0](https://linux-hardware.org/?probe=4b9e57acb0) | Jul 03, 2023 |
| HP            | 1791                        | [64fdea845b](https://linux-hardware.org/?probe=64fdea845b) | Jul 03, 2023 |
| ASUSTek       | H170M-PLUS                  | [530d25db12](https://linux-hardware.org/?probe=530d25db12) | Jul 03, 2023 |
| ADLINK Tec... | ABX-5600 A1                 | [46dbe425b5](https://linux-hardware.org/?probe=46dbe425b5) | Jul 03, 2023 |
| Medion        | BTDD-LT                     | [6c22cd4728](https://linux-hardware.org/?probe=6c22cd4728) | Jul 03, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [231af0c684](https://linux-hardware.org/?probe=231af0c684) | Jul 03, 2023 |
| Gigabyte      | X670E AORUS MASTER          | [5509c9dd07](https://linux-hardware.org/?probe=5509c9dd07) | Jul 03, 2023 |
| ASUSTek       | WS X299 PRO_SE              | [d31cedc2ad](https://linux-hardware.org/?probe=d31cedc2ad) | Jul 03, 2023 |
| HP            | 2129                        | [cc9462c976](https://linux-hardware.org/?probe=cc9462c976) | Jul 02, 2023 |
| Gigabyte      | B460M DS3H AC               | [71aa2fd160](https://linux-hardware.org/?probe=71aa2fd160) | Jul 02, 2023 |
| Medion        | BTDD-LT                     | [fb1c5c941c](https://linux-hardware.org/?probe=fb1c5c941c) | Jul 02, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [8712050b69](https://linux-hardware.org/?probe=8712050b69) | Jul 02, 2023 |
| Lenovo        | ThinkStation E30 782497U    | [f9376fd059](https://linux-hardware.org/?probe=f9376fd059) | Jul 02, 2023 |
| Lenovo        | ThinkStation E30 782497U    | [6dcf0eeb55](https://linux-hardware.org/?probe=6dcf0eeb55) | Jul 02, 2023 |
| ASUSTek       | PRIME B450M-A II            | [24b39db7e7](https://linux-hardware.org/?probe=24b39db7e7) | Jul 02, 2023 |
| MSI           | B450M PRO-VDH MAX           | [b010348549](https://linux-hardware.org/?probe=b010348549) | Jul 02, 2023 |
| MSI           | Boston                      | [39a458d562](https://linux-hardware.org/?probe=39a458d562) | Jul 01, 2023 |
| Unknown       | Unknown                     | [1b8105097a](https://linux-hardware.org/?probe=1b8105097a) | Jul 01, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [46c52eedc1](https://linux-hardware.org/?probe=46c52eedc1) | Jul 01, 2023 |
| Intel         | X99                         | [81dbd5c4f0](https://linux-hardware.org/?probe=81dbd5c4f0) | Jul 01, 2023 |
| Acer          | TDPS05                      | [71cf03e3a2](https://linux-hardware.org/?probe=71cf03e3a2) | Jul 01, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [dea1298c2e](https://linux-hardware.org/?probe=dea1298c2e) | Jul 01, 2023 |
| Gigabyte      | H61M-USB3V                  | [cebfe5c301](https://linux-hardware.org/?probe=cebfe5c301) | Jul 01, 2023 |
| Gigabyte      | H61M-USB3V                  | [715907e0c3](https://linux-hardware.org/?probe=715907e0c3) | Jul 01, 2023 |
| Unknown       | Unknown                     | [53eedfaac9](https://linux-hardware.org/?probe=53eedfaac9) | Jul 01, 2023 |
| Dell          | 09KPNV A01                  | [ca6243303f](https://linux-hardware.org/?probe=ca6243303f) | Jul 01, 2023 |
| ASUSTek       | M4A78LT-M-LE                | [9564e74fb6](https://linux-hardware.org/?probe=9564e74fb6) | Jul 01, 2023 |
| ASRock        | H510M-HDV/M.2               | [ec9ab3662c](https://linux-hardware.org/?probe=ec9ab3662c) | Jul 01, 2023 |
| ZR            | A320M-F 1005                | [c32d8de777](https://linux-hardware.org/?probe=c32d8de777) | Jun 30, 2023 |
| Supermicro    | X10DDW-i                    | [c43e65f1ae](https://linux-hardware.org/?probe=c43e65f1ae) | Jun 30, 2023 |
| Intel         | B85 V5.56                   | [a582972a5e](https://linux-hardware.org/?probe=a582972a5e) | Jun 30, 2023 |
| Gigabyte      | B760M DS3H AX DDR4          | [0d3ecc7c44](https://linux-hardware.org/?probe=0d3ecc7c44) | Jun 30, 2023 |
| Pegatron      | 2AB5                        | [f23fa01e43](https://linux-hardware.org/?probe=f23fa01e43) | Jun 30, 2023 |
| AZW           | SEi                         | [37527da518](https://linux-hardware.org/?probe=37527da518) | Jun 30, 2023 |
| Intel         | X99H                        | [8e8c7e8b20](https://linux-hardware.org/?probe=8e8c7e8b20) | Jun 30, 2023 |
| Supermicro    | X9DRW                       | [cb955d7a58](https://linux-hardware.org/?probe=cb955d7a58) | Jun 30, 2023 |
| HP            | 1497                        | [4dd582d288](https://linux-hardware.org/?probe=4dd582d288) | Jun 30, 2023 |
| Dell          | 0KYJ8C A02                  | [f4fff60df3](https://linux-hardware.org/?probe=f4fff60df3) | Jun 30, 2023 |
| ASUSTek       | M51AC                       | [d32d060e9c](https://linux-hardware.org/?probe=d32d060e9c) | Jun 30, 2023 |
| Dell          | 0KYJ8C A02                  | [c860545122](https://linux-hardware.org/?probe=c860545122) | Jun 30, 2023 |
| Medion        | Z370H4-EM                   | [b8327a4d00](https://linux-hardware.org/?probe=b8327a4d00) | Jun 30, 2023 |
| Intel         | B85 V5.56                   | [e8b15eb823](https://linux-hardware.org/?probe=e8b15eb823) | Jun 29, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | [5a6b149eb4](https://linux-hardware.org/?probe=5a6b149eb4) | Jun 29, 2023 |
| Dell          | 0T568R A00                  | [cf98a8a69b](https://linux-hardware.org/?probe=cf98a8a69b) | Jun 29, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d6cb722f64](https://linux-hardware.org/?probe=d6cb722f64) | Jun 29, 2023 |
| ASRock        | Z690 Steel Legend WiFi 6... | [d09ee66df1](https://linux-hardware.org/?probe=d09ee66df1) | Jun 29, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [304ff06fc0](https://linux-hardware.org/?probe=304ff06fc0) | Jun 29, 2023 |
| MSI           | Z87 MPOWER                  | [e34420b76e](https://linux-hardware.org/?probe=e34420b76e) | Jun 29, 2023 |
| ASUSTek       | F2A85-M PRO                 | [a7617c12c5](https://linux-hardware.org/?probe=a7617c12c5) | Jun 28, 2023 |
| ZR            | A320M-F 1005                | [f70bb41b80](https://linux-hardware.org/?probe=f70bb41b80) | Jun 28, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [e29021ab76](https://linux-hardware.org/?probe=e29021ab76) | Jun 28, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Ubuntu_22.04/Desktop/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.15.0-56-generic | 291      | 6.29%   |
| 5.15.0-52-generic | 250      | 5.4%    |
| 5.15.0-58-generic | 244      | 5.27%   |
| 5.19.0-35-generic | 211      | 4.56%   |
| 5.15.0-48-generic | 202      | 4.36%   |
| 5.15.0-47-generic | 196      | 4.24%   |
| 5.15.0-43-generic | 194      | 4.19%   |
| 5.19.0-32-generic | 185      | 4%      |
| 5.19.0-41-generic | 166      | 3.59%   |
| 5.19.0-46-generic | 155      | 3.35%   |
| 5.15.0-53-generic | 150      | 3.24%   |
| 5.19.0-38-generic | 149      | 3.22%   |
| 6.2.0-26-generic  | 148      | 3.2%    |
| 5.15.0-46-generic | 137      | 2.96%   |
| 5.15.0-25-generic | 112      | 2.42%   |
| 5.19.0-43-generic | 105      | 2.27%   |
| 5.15.0-27-generic | 102      | 2.2%    |
| 5.15.0-60-generic | 96       | 2.07%   |
| 5.15.0-41-generic | 93       | 2.01%   |
| 5.15.0-40-generic | 91       | 1.97%   |
| 6.2.0-32-generic  | 89       | 1.92%   |
| 5.15.0-57-generic | 83       | 1.79%   |
| 5.15.0-50-generic | 80       | 1.73%   |
| 5.19.0-45-generic | 74       | 1.6%    |
| 5.19.0-40-generic | 68       | 1.47%   |
| 5.15.0-67-generic | 63       | 1.36%   |
| 6.2.0-33-generic  | 60       | 1.3%    |
| 5.15.0-33-generic | 60       | 1.3%    |
| 5.19.0-50-generic | 53       | 1.15%   |
| 5.15.0-30-generic | 53       | 1.15%   |
| 5.15.0-69-generic | 49       | 1.06%   |
| 5.19.0-42-generic | 48       | 1.04%   |
| 5.15.0-39-generic | 46       | 0.99%   |
| 5.15.0-35-generic | 44       | 0.95%   |
| 5.15.0-37-generic | 41       | 0.89%   |
| 6.2.0-31-generic  | 38       | 0.82%   |
| 5.15.0-76-generic | 28       | 0.61%   |
| 5.15.0-71-generic | 27       | 0.58%   |
| 5.15.0-78-generic | 21       | 0.45%   |
| 5.15.0-83-generic | 18       | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 2622     | 62.53%  |
| 5.19.0  | 1110     | 26.47%  |
| 6.2.0   | 333      | 7.94%   |
| 5.17.0  | 19       | 0.45%   |
| 5.13.0  | 15       | 0.36%   |
| 6.1.0   | 8        | 0.19%   |
| 6.0.0   | 5        | 0.12%   |
| 5.18.0  | 5        | 0.12%   |
| 6.0.1   | 3        | 0.07%   |
| 5.19.5  | 3        | 0.07%   |
| 5.18.10 | 3        | 0.07%   |
| 5.10.60 | 3        | 0.07%   |
| 6.4.3   | 2        | 0.05%   |
| 6.4.12  | 2        | 0.05%   |
| 6.4.0   | 2        | 0.05%   |
| 6.2.16  | 2        | 0.05%   |
| 6.2.11  | 2        | 0.05%   |
| 6.1.11  | 2        | 0.05%   |
| 6.0.9   | 2        | 0.05%   |
| 5.8.0   | 2        | 0.05%   |
| 5.19.17 | 2        | 0.05%   |
| 5.17.9  | 2        | 0.05%   |
| 5.17.15 | 2        | 0.05%   |
| 5.15.13 | 2        | 0.05%   |
| 5.14.0  | 2        | 0.05%   |
| 6.5.1   | 1        | 0.02%   |
| 6.4.9   | 1        | 0.02%   |
| 6.4.14  | 1        | 0.02%   |
| 6.4.11  | 1        | 0.02%   |
| 6.3.7   | 1        | 0.02%   |
| 6.3.4   | 1        | 0.02%   |
| 6.3.2   | 1        | 0.02%   |
| 6.3.0   | 1        | 0.02%   |
| 6.2.9   | 1        | 0.02%   |
| 6.2.6   | 1        | 0.02%   |
| 6.2.3   | 1        | 0.02%   |
| 6.2.2   | 1        | 0.02%   |
| 6.2.10  | 1        | 0.02%   |
| 6.2.1   | 1        | 0.02%   |
| 6.1.8   | 1        | 0.02%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 2624     | 62.61%  |
| 5.19    | 1116     | 26.63%  |
| 6.2     | 343      | 8.18%   |
| 5.17    | 28       | 0.67%   |
| 6.1     | 16       | 0.38%   |
| 5.13    | 15       | 0.36%   |
| 5.18    | 13       | 0.31%   |
| 6.0     | 12       | 0.29%   |
| 6.4     | 9        | 0.21%   |
| 6.3     | 4        | 0.1%    |
| 5.10    | 3        | 0.07%   |
| 5.8     | 2        | 0.05%   |
| 5.14    | 2        | 0.05%   |
| 6.5     | 1        | 0.02%   |
| 5.4     | 1        | 0.02%   |
| 5.16    | 1        | 0.02%   |
| 5.11    | 1        | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 4019     | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 3659     | 90.95%  |
| Unknown         | 217      | 5.39%   |
| GNUstep         | 66       | 1.64%   |
| X-Cinnamon      | 43       | 1.07%   |
| GNOME Flashback | 16       | 0.4%    |
| GNOME Classic   | 9        | 0.22%   |
| i3              | 5        | 0.12%   |
| Enlightenment   | 3        | 0.07%   |
| ubuntu=GNOME    | 1        | 0.02%   |
| ubuntu          | 1        | 0.02%   |
| INPT            | 1        | 0.02%   |
| i3-with-shmlog  | 1        | 0.02%   |
| awesome         | 1        | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 2185     | 53.27%  |
| X11     | 1578     | 38.47%  |
| Tty     | 231      | 5.63%   |
| Unknown | 107      | 2.61%   |
| Web     | 1        | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| GDM3    | 3506     | 87%     |
| Unknown | 360      | 8.93%   |
| LightDM | 127      | 3.15%   |
| GDM     | 17       | 0.42%   |
| SDDM    | 15       | 0.37%   |
| SLiM    | 4        | 0.1%    |
| LXDM    | 1        | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 1778     | 44.1%   |
| de_DE   | 391      | 9.7%    |
| fr_FR   | 265      | 6.57%   |
| en_GB   | 192      | 4.76%   |
| pt_BR   | 157      | 3.89%   |
| it_IT   | 127      | 3.15%   |
| en_CA   | 117      | 2.9%    |
| ru_RU   | 97       | 2.41%   |
| es_ES   | 86       | 2.13%   |
| en_AU   | 75       | 1.86%   |
| C       | 61       | 1.51%   |
| en_IN   | 60       | 1.49%   |
| pl_PL   | 52       | 1.29%   |
| nl_NL   | 40       | 0.99%   |
| Unknown | 36       | 0.89%   |
| cs_CZ   | 34       | 0.84%   |
| ja_JP   | 32       | 0.79%   |
| es_MX   | 29       | 0.72%   |
| de_AT   | 29       | 0.72%   |
| es_AR   | 27       | 0.67%   |
| zh_CN   | 24       | 0.6%    |
| sv_SE   | 23       | 0.57%   |
| hu_HU   | 20       | 0.5%    |
| en_ZA   | 19       | 0.47%   |
| fi_FI   | 17       | 0.42%   |
| pt_PT   | 14       | 0.35%   |
| fr_BE   | 14       | 0.35%   |
| en_NZ   | 14       | 0.35%   |
| el_GR   | 13       | 0.32%   |
| tr_TR   | 12       | 0.3%    |
| nl_BE   | 10       | 0.25%   |
| ko_KR   | 10       | 0.25%   |
| en_PH   | 10       | 0.25%   |
| de_CH   | 10       | 0.25%   |
| fr_CA   | 9        | 0.22%   |
| sk_SK   | 8        | 0.2%    |
| es_CO   | 8        | 0.2%    |
| zh_TW   | 7        | 0.17%   |
| en_HK   | 6        | 0.15%   |
| ro_RO   | 5        | 0.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 2810     | 69.18%  |
| EFI  | 1252     | 30.82%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Ext4          | 3184     | 76.93%  |
| Tmpfs         | 669      | 16.16%  |
| Overlay       | 122      | 2.95%   |
| Zfs           | 86       | 2.08%   |
| Btrfs         | 41       | 0.99%   |
| Xfs           | 22       | 0.53%   |
| Ext2          | 7        | 0.17%   |
| Unknown       | 4        | 0.1%    |
| XXXX          | 1        | 0.02%   |
| Jfs           | 1        | 0.02%   |
| Fuse.snapfuse | 1        | 0.02%   |
| Ext3          | 1        | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 2778     | 66.86%  |
| Unknown | 938      | 22.58%  |
| MBR     | 439      | 10.57%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 3357     | 82.24%  |
| Yes       | 725      | 17.76%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 2323     | 57.16%  |
| Yes       | 1741     | 42.84%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 1010     | 25.13%  |
| Gigabyte Technology                  | 590      | 14.68%  |
| MSI                                  | 468      | 11.64%  |
| Dell                                 | 427      | 10.62%  |
| ASRock                               | 315      | 7.84%   |
| Hewlett-Packard                      | 305      | 7.59%   |
| Lenovo                               | 163      | 4.06%   |
| Intel                                | 119      | 2.96%   |
| Acer                                 | 80       | 1.99%   |
| Fujitsu                              | 66       | 1.64%   |
| Unknown                              | 54       | 1.34%   |
| Pegatron                             | 36       | 0.9%    |
| Medion                               | 33       | 0.82%   |
| Foxconn                              | 30       | 0.75%   |
| Biostar                              | 27       | 0.67%   |
| Supermicro                           | 25       | 0.62%   |
| Apple                                | 22       | 0.55%   |
| ECS                                  | 21       | 0.52%   |
| Shuttle                              | 18       | 0.45%   |
| Alienware                            | 18       | 0.45%   |
| AZW                                  | 15       | 0.37%   |
| Huanan                               | 13       | 0.32%   |
| Gateway                              | 12       | 0.3%    |
| Positivo                             | 9        | 0.22%   |
| Packard Bell                         | 9        | 0.22%   |
| BESSTAR Tech                         | 8        | 0.2%    |
| ASRockRack                           | 6        | 0.15%   |
| OEM                                  | 5        | 0.12%   |
| eMachines                            | 5        | 0.12%   |
| Wistron                              | 4        | 0.1%    |
| Shenzhen Meigao Electronic Equipment | 4        | 0.1%    |
| AMI                                  | 4        | 0.1%    |
| YANYU                                | 3        | 0.07%   |
| PCWare                               | 3        | 0.07%   |
| Maxtang                              | 3        | 0.07%   |
| MACHINIST                            | 3        | 0.07%   |
| Google                               | 3        | 0.07%   |
| Fujitsu Siemens                      | 3        | 0.07%   |
| Colorful Technology                  | 3        | 0.07%   |
| ZOTAC                                | 2        | 0.05%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| ASUS All Series                 | 98       | 2.44%   |
| Unknown                         | 60       | 1.49%   |
| Dell OptiPlex 7010              | 33       | 0.82%   |
| Dell OptiPlex 9020              | 30       | 0.75%   |
| ASUS PRIME A320M-K              | 26       | 0.65%   |
| ASUS TUF Gaming X570-PLUS       | 23       | 0.57%   |
| Dell OptiPlex 3020              | 20       | 0.5%    |
| MSI MS-7C37                     | 19       | 0.47%   |
| MSI MS-7721                     | 19       | 0.47%   |
| ASUS PRIME Z590-P               | 18       | 0.45%   |
| MSI MS-7C91                     | 17       | 0.42%   |
| Dell OptiPlex 790               | 16       | 0.4%    |
| Dell OptiPlex 3050              | 15       | 0.37%   |
| ASUS ROG STRIX B550-F GAMING    | 15       | 0.37%   |
| ASUS PRIME B550M-A              | 15       | 0.37%   |
| Dell OptiPlex 7050              | 14       | 0.35%   |
| ASUS PRIME X570-PRO             | 14       | 0.35%   |
| ASRock B450M Pro4               | 14       | 0.35%   |
| Intel H61                       | 13       | 0.32%   |
| HP Compaq 8200 Elite SFF PC     | 13       | 0.32%   |
| Dell OptiPlex 990               | 13       | 0.32%   |
| ASUS M5A78L-M/USB3              | 12       | 0.3%    |
| MSI MS-7C52                     | 11       | 0.27%   |
| HP ProDesk 600 G1 SFF           | 11       | 0.27%   |
| Gigabyte B450M DS3H             | 11       | 0.27%   |
| Dell OptiPlex 780               | 11       | 0.27%   |
| Dell OptiPlex 7040              | 11       | 0.27%   |
| MSI MS-7C56                     | 10       | 0.25%   |
| MSI MS-7C02                     | 10       | 0.25%   |
| MSI MS-7B79                     | 10       | 0.25%   |
| Gigabyte A320M-S2H              | 10       | 0.25%   |
| ASUS Pro WS WRX80E-SAGE SE WIFI | 10       | 0.25%   |
| ASRock A320M-HDV R4.0           | 10       | 0.25%   |
| MSI MS-7B86                     | 9        | 0.22%   |
| MSI MS-7817                     | 9        | 0.22%   |
| MSI MS-7693                     | 9        | 0.22%   |
| HP EliteDesk 800 G1 SFF         | 9        | 0.22%   |
| HP Compaq Pro 6300 SFF          | 9        | 0.22%   |
| Gigabyte 970A-DS3P              | 9        | 0.22%   |
| ASUS TUF Gaming B550-PLUS       | 9        | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell OptiPlex       | 266      | 6.62%   |
| ASUS PRIME          | 229      | 5.7%    |
| ASUS ROG            | 137      | 3.41%   |
| ASUS All            | 98       | 2.44%   |
| HP Compaq           | 97       | 2.41%   |
| ASUS TUF            | 95       | 2.36%   |
| Lenovo ThinkCentre  | 88       | 2.19%   |
| Dell Precision      | 65       | 1.62%   |
| Unknown             | 60       | 1.49%   |
| HP EliteDesk        | 48       | 1.19%   |
| Acer Aspire         | 48       | 1.19%   |
| Dell Inspiron       | 44       | 1.09%   |
| Fujitsu ESPRIMO     | 39       | 0.97%   |
| HP ProDesk          | 37       | 0.92%   |
| Gigabyte B450M      | 26       | 0.65%   |
| Lenovo ThinkStation | 25       | 0.62%   |
| ASUS M5A78L-M       | 25       | 0.62%   |
| Gigabyte X570       | 22       | 0.55%   |
| Gigabyte Z390       | 21       | 0.52%   |
| Fujitsu CELSIUS     | 20       | 0.5%    |
| ASUS M5A97          | 20       | 0.5%    |
| ASRock B450M        | 20       | 0.5%    |
| MSI MS-7C37         | 19       | 0.47%   |
| MSI MS-7721         | 19       | 0.47%   |
| Lenovo IdeaCentre   | 19       | 0.47%   |
| Gigabyte B550M      | 19       | 0.47%   |
| Dell XPS            | 19       | 0.47%   |
| ASUS P8H61-M        | 18       | 0.45%   |
| MSI MS-7C91         | 17       | 0.42%   |
| ASUS Pro            | 17       | 0.42%   |
| Gigabyte B550       | 16       | 0.4%    |
| Gigabyte B450       | 16       | 0.4%    |
| Dell Vostro         | 15       | 0.37%   |
| Acer Veriton        | 15       | 0.37%   |
| ASUS CROSSHAIR      | 14       | 0.35%   |
| Intel H61           | 13       | 0.32%   |
| ASRock X570         | 13       | 0.32%   |
| HP Pavilion         | 12       | 0.3%    |
| Gigabyte A320M-S2H  | 12       | 0.3%    |
| Gigabyte 970A-DS3P  | 12       | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 372      | 9.26%   |
| 2013    | 353      | 8.78%   |
| 2012    | 343      | 8.53%   |
| 2020    | 324      | 8.06%   |
| 2021    | 308      | 7.66%   |
| 2011    | 286      | 7.12%   |
| 2014    | 283      | 7.04%   |
| 2019    | 280      | 6.97%   |
| 2017    | 250      | 6.22%   |
| 2015    | 224      | 5.57%   |
| 2022    | 215      | 5.35%   |
| 2010    | 194      | 4.83%   |
| 2009    | 163      | 4.06%   |
| 2016    | 157      | 3.91%   |
| 2008    | 113      | 2.81%   |
| 2007    | 77       | 1.92%   |
| 2023    | 44       | 1.09%   |
| 2006    | 21       | 0.52%   |
| 2005    | 6        | 0.15%   |
| Unknown | 5        | 0.12%   |
| 2004    | 1        | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 4019     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 3884     | 96.45%  |
| Enabled  | 143      | 3.55%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 4013     | 99.85%  |
| Yes  | 6        | 0.15%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 1056     | 25.98%  |
| 32.01-64.0      | 690      | 16.97%  |
| 8.01-16.0       | 682      | 16.78%  |
| 4.01-8.0        | 662      | 16.29%  |
| 3.01-4.0        | 453      | 11.14%  |
| 64.01-256.0     | 306      | 7.53%   |
| 24.01-32.0      | 125      | 3.08%   |
| 1.01-2.0        | 47       | 1.16%   |
| 2.01-3.0        | 22       | 0.54%   |
| More than 256.0 | 19       | 0.47%   |
| 0.51-1.0        | 2        | 0.05%   |
| 0.01-0.5        | 1        | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 1328     | 30.79%  |
| 2.01-3.0    | 1308     | 30.33%  |
| 4.01-8.0    | 664      | 15.4%   |
| 3.01-4.0    | 616      | 14.28%  |
| 8.01-16.0   | 226      | 5.24%   |
| 0.51-1.0    | 85       | 1.97%   |
| 16.01-24.0  | 35       | 0.81%   |
| 0.01-0.5    | 19       | 0.44%   |
| 24.01-32.0  | 18       | 0.42%   |
| 32.01-64.0  | 13       | 0.3%    |
| 64.01-256.0 | 1        | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 1644     | 39.77%  |
| 2      | 1231     | 29.78%  |
| 3      | 607      | 14.68%  |
| 4      | 298      | 7.21%   |
| 5      | 147      | 3.56%   |
| 6      | 67       | 1.62%   |
| 0      | 47       | 1.14%   |
| 7      | 38       | 0.92%   |
| 8      | 15       | 0.36%   |
| 9      | 14       | 0.34%   |
| 11     | 7        | 0.17%   |
| 10     | 7        | 0.17%   |
| 13     | 3        | 0.07%   |
| 12     | 3        | 0.07%   |
| 25     | 2        | 0.05%   |
| 38     | 1        | 0.02%   |
| 20     | 1        | 0.02%   |
| 17     | 1        | 0.02%   |
| 14     | 1        | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2270     | 56.05%  |
| Yes       | 1780     | 43.95%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 3987     | 99.18%  |
| No        | 33       | 0.82%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2222     | 54.86%  |
| Yes       | 1828     | 45.14%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2738     | 67.55%  |
| Yes       | 1315     | 32.45%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 884      | 21.95%  |
| Germany      | 459      | 11.4%   |
| France       | 281      | 6.98%   |
| Brazil       | 221      | 5.49%   |
| UK           | 185      | 4.59%   |
| Russia       | 158      | 3.92%   |
| Canada       | 152      | 3.77%   |
| Italy        | 151      | 3.75%   |
| Switzerland  | 138      | 3.43%   |
| Spain        | 96       | 2.38%   |
| Australia    | 84       | 2.09%   |
| Netherlands  | 77       | 1.91%   |
| Poland       | 68       | 1.69%   |
| India        | 67       | 1.66%   |
| Austria      | 54       | 1.34%   |
| Sweden       | 48       | 1.19%   |
| Mexico       | 48       | 1.19%   |
| Argentina    | 45       | 1.12%   |
| Belgium      | 44       | 1.09%   |
| Japan        | 42       | 1.04%   |
| Czechia      | 42       | 1.04%   |
| Finland      | 38       | 0.94%   |
| Greece       | 32       | 0.79%   |
| Hungary      | 30       | 0.74%   |
| Turkey       | 28       | 0.7%    |
| China        | 26       | 0.65%   |
| Romania      | 23       | 0.57%   |
| South Africa | 22       | 0.55%   |
| Slovakia     | 22       | 0.55%   |
| Portugal     | 20       | 0.5%    |
| Bulgaria     | 20       | 0.5%    |
| South Korea  | 19       | 0.47%   |
| Norway       | 16       | 0.4%    |
| New Zealand  | 16       | 0.4%    |
| Hong Kong    | 16       | 0.4%    |
| Denmark      | 14       | 0.35%   |
| Colombia     | 14       | 0.35%   |
| Thailand     | 13       | 0.32%   |
| Taiwan       | 13       | 0.32%   |
| Serbia       | 13       | 0.32%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Zurich            | 83       | 1.98%   |
| Berlin            | 39       | 0.93%   |
| Vienna            | 34       | 0.81%   |
| Moscow            | 34       | 0.81%   |
| Sydney            | 32       | 0.76%   |
| Paris             | 32       | 0.76%   |
| Sao Paulo         | 24       | 0.57%   |
| Milan             | 24       | 0.57%   |
| Cheboksary        | 24       | 0.57%   |
| Madrid            | 22       | 0.52%   |
| Hamburg           | 21       | 0.5%    |
| Rio de Janeiro    | 20       | 0.48%   |
| New York          | 20       | 0.48%   |
| Helsinki          | 20       | 0.48%   |
| St Petersburg     | 19       | 0.45%   |
| Prague            | 18       | 0.43%   |
| Lucerne           | 18       | 0.43%   |
| Athens            | 18       | 0.43%   |
| Seattle           | 17       | 0.41%   |
| Munich            | 17       | 0.41%   |
| San Jose          | 15       | 0.36%   |
| Warsaw            | 14       | 0.33%   |
| Toronto           | 14       | 0.33%   |
| Los Angeles       | 14       | 0.33%   |
| London            | 14       | 0.33%   |
| Istanbul          | 14       | 0.33%   |
| Budapest          | 14       | 0.33%   |
| Stockholm         | 13       | 0.31%   |
| Melbourne         | 13       | 0.31%   |
| Amsterdam         | 13       | 0.31%   |
| Rome              | 12       | 0.29%   |
| Manchester        | 12       | 0.29%   |
| Dallas            | 12       | 0.29%   |
| Brisbane          | 12       | 0.29%   |
| Beverly Hills     | 12       | 0.29%   |
| Vancouver         | 11       | 0.26%   |
| Sofia             | 11       | 0.26%   |
| Singapore         | 11       | 0.26%   |
| Houston           | 11       | 0.26%   |
| Frankfurt am Main | 11       | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 1302     | 2077   | 18.35%  |
| WDC                         | 1257     | 2083   | 17.72%  |
| Samsung Electronics         | 1070     | 1672   | 15.08%  |
| Kingston                    | 449      | 561    | 6.33%   |
| Sandisk                     | 352      | 493    | 4.96%   |
| Toshiba                     | 345      | 452    | 4.86%   |
| Crucial                     | 310      | 468    | 4.37%   |
| Hitachi                     | 223      | 287    | 3.14%   |
| A-DATA Technology           | 110      | 133    | 1.55%   |
| Intel                       | 103      | 121    | 1.45%   |
| China                       | 92       | 103    | 1.3%    |
| Unknown                     | 83       | 136    | 1.17%   |
| HGST                        | 78       | 117    | 1.1%    |
| SK hynix                    | 68       | 87     | 0.96%   |
| Phison Electronics          | 63       | 88     | 0.89%   |
| PNY                         | 59       | 67     | 0.83%   |
| Micron/Crucial Technology   | 59       | 79     | 0.83%   |
| Intenso                     | 56       | 71     | 0.79%   |
| Silicon Motion              | 52       | 70     | 0.73%   |
| Kingston Technology Company | 51       | 61     | 0.72%   |
| SPCC                        | 42       | 72     | 0.59%   |
| Phison                      | 39       | 53     | 0.55%   |
| Micron Technology           | 36       | 49     | 0.51%   |
| OCZ                         | 33       | 51     | 0.47%   |
| Patriot                     | 28       | 35     | 0.39%   |
| Maxtor                      | 28       | 39     | 0.39%   |
| Gigabyte Technology         | 28       | 37     | 0.39%   |
| Transcend                   | 26       | 26     | 0.37%   |
| Corsair                     | 26       | 29     | 0.37%   |
| Unknown                     | 26       | 29     | 0.37%   |
| Team                        | 25       | 36     | 0.35%   |
| Lexar                       | 24       | 27     | 0.34%   |
| Hewlett-Packard             | 20       | 53     | 0.28%   |
| JMicron Technology          | 19       | 20     | 0.27%   |
| ADATA Technology            | 18       | 25     | 0.25%   |
| ASMT                        | 17       | 30     | 0.24%   |
| SABRENT                     | 15       | 20     | 0.21%   |
| KingSpec                    | 15       | 17     | 0.21%   |
| Realtek Semiconductor       | 14       | 16     | 0.2%    |
| KIOXIA                      | 14       | 27     | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB   | 104      | 1.26%   |
| Seagate ST1000DM010-2EP102 1TB                        | 103      | 1.25%   |
| Seagate ST500DM002-1BD142 500GB                       | 100      | 1.21%   |
| Kingston SA400S37240G 240GB SSD                       | 97       | 1.18%   |
| Seagate ST2000DM008-2FR102 2TB                        | 90       | 1.09%   |
| Kingston SA400S37480G 480GB SSD                       | 70       | 0.85%   |
| Samsung SSD 850 EVO 250GB                             | 68       | 0.83%   |
| Samsung SSD 850 EVO 500GB                             | 63       | 0.77%   |
| Samsung SSD 860 EVO 500GB                             | 62       | 0.75%   |
| Samsung SSD 980 PRO 1TB                               | 59       | 0.72%   |
| Seagate ST1000DM003-1CH162 1TB                        | 54       | 0.66%   |
| Toshiba DT01ACA100 1TB                                | 53       | 0.64%   |
| Seagate ST4000DM004-2CV104 4TB                        | 52       | 0.63%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 46       | 0.56%   |
| Toshiba DT01ACA050 500GB                              | 44       | 0.53%   |
| Kingston SA400S37120G 120GB SSD                       | 44       | 0.53%   |
| Crucial CT500MX500SSD1 500GB                          | 43       | 0.52%   |
| Seagate ST1000DM003-1ER162 1TB                        | 42       | 0.51%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB    | 40       | 0.49%   |
| Crucial CT240BX500SSD1 240GB                          | 40       | 0.49%   |
| Crucial CT1000MX500SSD1 1TB                           | 40       | 0.49%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                   | 38       | 0.46%   |
| SanDisk NVMe SSD Drive 1TB                            | 37       | 0.45%   |
| Toshiba HDWD110 1TB                                   | 35       | 0.43%   |
| Unknown SD/MMC/MS PRO 128GB                           | 33       | 0.4%    |
| Samsung SSD 980 1TB                                   | 33       | 0.4%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 512GB | 31       | 0.38%   |
| Seagate ST2000DM001-1ER164 2TB                        | 31       | 0.38%   |
| Samsung NVMe SSD Drive 1TB                            | 31       | 0.38%   |
| Toshiba DT01ACA200 2TB                                | 30       | 0.36%   |
| Seagate ST2000DM006-2DM164 2TB                        | 30       | 0.36%   |
| Seagate ST1000DM003-1SB102 1TB                        | 30       | 0.36%   |
| Seagate ST2000DM001-1CH164 2TB                        | 29       | 0.35%   |
| Samsung SSD 870 EVO 500GB                             | 29       | 0.35%   |
| Samsung SSD 860 EVO 1TB                               | 28       | 0.34%   |
| Seagate ST3500418AS 500GB                             | 27       | 0.33%   |
| Crucial CT480BX500SSD1 480GB                          | 26       | 0.32%   |
| Unknown                                               | 26       | 0.32%   |
| Seagate Expansion Desk 8TB                            | 25       | 0.3%    |
| Samsung SSD 970 EVO Plus 1TB                          | 25       | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1274     | 2020   | 38.55%  |
| WDC                 | 1115     | 1839   | 33.74%  |
| Toshiba             | 295      | 380    | 8.93%   |
| Hitachi             | 221      | 285    | 6.69%   |
| Samsung Electronics | 173      | 246    | 5.23%   |
| HGST                | 78       | 113    | 2.36%   |
| Unknown             | 37       | 50     | 1.12%   |
| Maxtor              | 26       | 34     | 0.79%   |
| Intenso             | 16       | 18     | 0.48%   |
| SABRENT             | 14       | 19     | 0.42%   |
| Fujitsu             | 12       | 13     | 0.36%   |
| Apple               | 8        | 9      | 0.24%   |
| Hewlett-Packard     | 5        | 15     | 0.15%   |
| WD MediaMax         | 4        | 4      | 0.12%   |
| HPE                 | 3        | 5      | 0.09%   |
| ASMT                | 3        | 4      | 0.09%   |
| USB3.0              | 2        | 3      | 0.06%   |
| USB                 | 2        | 2      | 0.06%   |
| TDAS                | 2        | 11     | 0.06%   |
| LaCie               | 2        | 3      | 0.06%   |
| External            | 2        | 2      | 0.06%   |
| ExcelStor           | 2        | 2      | 0.06%   |
| ASMedia             | 2        | 2      | 0.06%   |
| RSH-339             | 1        | 1      | 0.03%   |
| QUANTUM             | 1        | 1      | 0.03%   |
| Min Yi U            | 1        | 2      | 0.03%   |
| MARVELL             | 1        | 1      | 0.03%   |
| HGST HTS            | 1        | 1      | 0.03%   |
| DAS                 | 1        | 3      | 0.03%   |
| Unknown             | 1        | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 541      | 734    | 21.95%  |
| Kingston            | 374      | 467    | 15.17%  |
| Crucial             | 277      | 421    | 11.24%  |
| SanDisk             | 184      | 261    | 7.46%   |
| WDC                 | 140      | 177    | 5.68%   |
| A-DATA Technology   | 95       | 117    | 3.85%   |
| China               | 91       | 101    | 3.69%   |
| Intel               | 60       | 67     | 2.43%   |
| Toshiba             | 54       | 61     | 2.19%   |
| PNY                 | 54       | 62     | 2.19%   |
| SPCC                | 39       | 68     | 1.58%   |
| OCZ                 | 31       | 37     | 1.26%   |
| Intenso             | 31       | 43     | 1.26%   |
| Patriot             | 27       | 34     | 1.1%    |
| Transcend           | 24       | 24     | 0.97%   |
| Team                | 24       | 35     | 0.97%   |
| Micron Technology   | 23       | 35     | 0.93%   |
| SK hynix            | 22       | 30     | 0.89%   |
| Gigabyte Technology | 20       | 29     | 0.81%   |
| Lexar               | 17       | 20     | 0.69%   |
| JMicron Technology  | 16       | 17     | 0.65%   |
| KingSpec            | 15       | 17     | 0.61%   |
| Corsair             | 14       | 16     | 0.57%   |
| ASMT                | 14       | 26     | 0.57%   |
| Unknown             | 14       | 15     | 0.57%   |
| Hewlett-Packard     | 12       | 12     | 0.49%   |
| Apacer              | 12       | 12     | 0.49%   |
| GOODRAM             | 11       | 17     | 0.45%   |
| LITEON              | 9        | 12     | 0.37%   |
| LITEONIT            | 8        | 8      | 0.32%   |
| Fanxiang            | 8        | 11     | 0.32%   |
| Seagate             | 7        | 9      | 0.28%   |
| FORESEE             | 7        | 7      | 0.28%   |
| Emtec               | 7        | 7      | 0.28%   |
| Dogfish             | 7        | 11     | 0.28%   |
| Netac               | 6        | 8      | 0.24%   |
| Plextor             | 5        | 5      | 0.2%    |
| Mushkin             | 5        | 5      | 0.2%    |
| Leven               | 5        | 8      | 0.2%    |
| KingDian            | 5        | 5      | 0.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 2568     | 5089   | 42.69%  |
| SSD     | 2083     | 3225   | 34.62%  |
| NVMe    | 1202     | 1849   | 19.98%  |
| Unknown | 139      | 230    | 2.31%   |
| MMC     | 24       | 33     | 0.4%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 3486     | 7987   | 69.14%  |
| NVMe | 1202     | 1842   | 23.84%  |
| SAS  | 330      | 564    | 6.55%   |
| MMC  | 24       | 33     | 0.48%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 2437     | 3973   | 47.83%  |
| 0.51-1.0   | 1455     | 2263   | 28.56%  |
| 1.01-2.0   | 612      | 954    | 12.01%  |
| 3.01-4.0   | 246      | 397    | 4.83%   |
| 4.01-10.0  | 162      | 391    | 3.18%   |
| 2.01-3.0   | 133      | 192    | 2.61%   |
| 10.01-20.0 | 49       | 143    | 0.96%   |
| 0          | 1        | 1      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 999      | 23.88%  |
| 251-500        | 790      | 18.89%  |
| 501-1000       | 758      | 18.12%  |
| 1001-2000      | 495      | 11.83%  |
| More than 3000 | 410      | 9.8%    |
| 2001-3000      | 208      | 4.97%   |
| 51-100         | 197      | 4.71%   |
| 1-20           | 163      | 3.9%    |
| Unknown        | 82       | 1.96%   |
| 21-50          | 81       | 1.94%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 1343     | 31.28%  |
| 21-50          | 772      | 17.98%  |
| 51-100         | 513      | 11.95%  |
| 101-250        | 511      | 11.9%   |
| 251-500        | 351      | 8.17%   |
| 501-1000       | 292      | 6.8%    |
| 1001-2000      | 184      | 4.29%   |
| More than 3000 | 171      | 3.98%   |
| Unknown        | 82       | 1.91%   |
| 2001-3000      | 74       | 1.72%   |
| 0              | 1        | 0.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WD40EFRX-68WT0N0 4TB              | 8        | 10     | 2.24%   |
| Seagate ST500DM002-1BD142 500GB       | 8        | 8      | 2.24%   |
| WDC WD10EARS-00Y5B1 1TB               | 4        | 5      | 1.12%   |
| Seagate ST1000DM003-1CH162 1TB        | 4        | 5      | 1.12%   |
| SanDisk SSD PLUS 480GB                | 4        | 4      | 1.12%   |
| Kingston SA400S37240G 240GB SSD       | 4        | 4      | 1.12%   |
| WDC WD5000AAKX-08ERMA0 500GB          | 3        | 3      | 0.84%   |
| WDC WD5000AAKX-00ERMA0 500GB          | 3        | 4      | 0.84%   |
| WDC WD10EZEX-21WN4A0 1TB              | 3        | 3      | 0.84%   |
| WDC WD10EZEX-21M2NA0 1TB              | 3        | 3      | 0.84%   |
| Toshiba DT01ACA050 500GB              | 3        | 3      | 0.84%   |
| Seagate ST3500418AS 500GB             | 3        | 4      | 0.84%   |
| Seagate ST3250310AS 250GB             | 3        | 3      | 0.84%   |
| Seagate ST31000528AS 1TB              | 3        | 3      | 0.84%   |
| Seagate ST2000DM001-1CH164 2TB        | 3        | 3      | 0.84%   |
| Samsung Electronics SSD 870 EVO 1TB   | 3        | 3      | 0.84%   |
| Kingston SV300S37A120G 120GB SSD      | 3        | 3      | 0.84%   |
| Intel SSDSC2CW120A3 120GB             | 3        | 3      | 0.84%   |
| WDC WD4003FZEX-00Z4SA0 4TB            | 2        | 4      | 0.56%   |
| WDC WD30EZRX-00MMMB0 3TB              | 2        | 6      | 0.56%   |
| WDC WD10EZEX-60ZF5A0 1TB              | 2        | 2      | 0.56%   |
| WDC WD10EZEX-22MFCA0 1TB              | 2        | 2      | 0.56%   |
| WDC WD10EADS-00M2B0 1TB               | 2        | 2      | 0.56%   |
| Toshiba DT01ACA100 1TB                | 2        | 2      | 0.56%   |
| Seagate ST500LM021-1KJ152 500GB       | 2        | 2      | 0.56%   |
| Seagate ST3750528AS 752GB             | 2        | 2      | 0.56%   |
| Seagate ST3320620AS 320GB             | 2        | 2      | 0.56%   |
| Seagate ST2000DM008-2FR102 2TB        | 2        | 2      | 0.56%   |
| Seagate ST1000DX001-1CM162 1TB        | 2        | 2      | 0.56%   |
| Seagate ST1000DM010-2EP102 1TB        | 2        | 2      | 0.56%   |
| Seagate ST1000DM003-9YN162 1TB        | 2        | 2      | 0.56%   |
| SanDisk SSD PLUS 1000GB               | 2        | 2      | 0.56%   |
| Samsung Electronics SSD 980 PRO 1TB   | 2        | 3      | 0.56%   |
| Samsung Electronics SSD 970 EVO 500GB | 2        | 2      | 0.56%   |
| Samsung Electronics SSD 970 EVO 1TB   | 2        | 2      | 0.56%   |
| Samsung Electronics SSD 870 EVO 500GB | 2        | 2      | 0.56%   |
| Samsung Electronics SSD 850 EVO 1TB   | 2        | 2      | 0.56%   |
| Samsung Electronics HD502HI 500GB     | 2        | 2      | 0.56%   |
| Samsung Electronics HD322GJ 320GB     | 2        | 2      | 0.56%   |
| Samsung Electronics HD321KJ 320GB     | 2        | 2      | 0.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 103      | 129    | 29.51%  |
| Seagate             | 88       | 108    | 25.21%  |
| Samsung Electronics | 43       | 48     | 12.32%  |
| Hitachi             | 21       | 22     | 6.02%   |
| Toshiba             | 14       | 14     | 4.01%   |
| Kingston            | 12       | 12     | 3.44%   |
| Intel               | 11       | 12     | 3.15%   |
| Crucial             | 8        | 10     | 2.29%   |
| SanDisk             | 7        | 9      | 2.01%   |
| Maxtor              | 5        | 6      | 1.43%   |
| A-DATA Technology   | 5        | 5      | 1.43%   |
| HGST                | 4        | 5      | 1.15%   |
| China               | 4        | 4      | 1.15%   |
| Micron Technology   | 3        | 9      | 0.86%   |
| LITEONIT            | 3        | 3      | 0.86%   |
| LDLC                | 2        | 2      | 0.57%   |
| Intenso             | 2        | 2      | 0.57%   |
| YS                  | 1        | 1      | 0.29%   |
| XPG                 | 1        | 1      | 0.29%   |
| WD MediaMax         | 1        | 1      | 0.29%   |
| SK hynix            | 1        | 1      | 0.29%   |
| Silicon Motion      | 1        | 1      | 0.29%   |
| PNY                 | 1        | 1      | 0.29%   |
| Patriot             | 1        | 1      | 0.29%   |
| OCZ                 | 1        | 1      | 0.29%   |
| Netac               | 1        | 2      | 0.29%   |
| Mushkin             | 1        | 1      | 0.29%   |
| KingSpec            | 1        | 1      | 0.29%   |
| Gigabyte Technology | 1        | 1      | 0.29%   |
| ASMedia             | 1        | 1      | 0.29%   |
| Unknown             | 1        | 1      | 0.29%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 100      | 126    | 39.53%  |
| Seagate             | 88       | 108    | 34.78%  |
| Samsung Electronics | 21       | 23     | 8.3%    |
| Hitachi             | 21       | 22     | 8.3%    |
| Toshiba             | 13       | 13     | 5.14%   |
| Maxtor              | 5        | 6      | 1.98%   |
| HGST                | 4        | 5      | 1.58%   |
| WD MediaMax         | 1        | 1      | 0.4%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 234      | 304    | 70.91%  |
| SSD  | 78       | 91     | 23.64%  |
| NVMe | 18       | 20     | 5.45%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Samsung Electronics SSD 980 500GB     | 2        | 2      | 25%     |
| WDC WD800BB-00FJA0 80GB               | 1        | 1      | 12.5%   |
| WDC WD3200AAJS-22VWA0 320GB           | 1        | 1      | 12.5%   |
| Seagate ST3500630AS 500GB             | 1        | 1      | 12.5%   |
| Samsung Electronics SSD 960 EVO 250GB | 1        | 1      | 12.5%   |
| Intel SSDPEKKW256G7 256GB             | 1        | 1      | 12.5%   |
| Hewlett-Packard EF0450FARMV 450GB     | 1        | 4      | 12.5%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 3        | 3      | 37.5%   |
| WDC                 | 2        | 2      | 25%     |
| Seagate             | 1        | 1      | 12.5%   |
| Intel               | 1        | 1      | 12.5%   |
| Hewlett-Packard     | 1        | 4      | 12.5%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 2731     | 7167   | 62.39%  |
| Works    | 1331     | 2833   | 30.41%  |
| Malfunc  | 307      | 415    | 7.01%   |
| Failed   | 8        | 11     | 0.18%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 2682     | 45.73%  |
| AMD                           | 1211     | 20.65%  |
| Samsung Electronics           | 465      | 7.93%   |
| SanDisk                       | 231      | 3.94%   |
| ASMedia Technology            | 222      | 3.79%   |
| Kingston Technology Company   | 132      | 2.25%   |
| Marvell Technology Group      | 121      | 2.06%   |
| Phison Electronics            | 119      | 2.03%   |
| JMicron Technology            | 111      | 1.89%   |
| Micron/Crucial Technology     | 94       | 1.6%    |
| Nvidia                        | 89       | 1.52%   |
| Silicon Motion                | 63       | 1.07%   |
| SK hynix                      | 48       | 0.82%   |
| ADATA Technology              | 36       | 0.61%   |
| Broadcom / LSI                | 26       | 0.44%   |
| LSI Logic / Symbios Logic     | 24       | 0.41%   |
| Realtek Semiconductor         | 22       | 0.38%   |
| MAXIO Technology (Hangzhou)   | 20       | 0.34%   |
| KIOXIA                        | 19       | 0.32%   |
| Silicon Image                 | 18       | 0.31%   |
| VIA Technologies              | 15       | 0.26%   |
| Seagate Technology            | 14       | 0.24%   |
| Micron Technology             | 14       | 0.24%   |
| Adaptec                       | 13       | 0.22%   |
| Shenzhen Longsys Electronics  | 8        | 0.14%   |
| Toshiba America Info Systems  | 7        | 0.12%   |
| INNOGRIT                      | 5        | 0.09%   |
| Apple                         | 4        | 0.07%   |
| Solidigm                      | 3        | 0.05%   |
| Lite-On Technology            | 3        | 0.05%   |
| Hewlett-Packard               | 3        | 0.05%   |
| Union Memory (Shenzhen)       | 2        | 0.03%   |
| Transcend                     | 2        | 0.03%   |
| OCZ Technology Group          | 2        | 0.03%   |
| Integrated Technology Express | 2        | 0.03%   |
| Chelsio Communications        | 2        | 0.03%   |
| 3ware                         | 2        | 0.03%   |
| Western Digital               | 1        | 0.02%   |
| Toshiba                       | 1        | 0.02%   |
| TenaFe                        | 1        | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 666      | 9.37%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 340      | 4.79%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 227      | 3.19%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 217      | 3.05%   |
| Intel SATA Controller [RAID mode]                                                       | 216      | 3.04%   |
| AMD 400 Series Chipset SATA Controller                                                  | 212      | 2.98%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 206      | 2.9%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 203      | 2.86%   |
| AMD 500 Series Chipset SATA Controller                                                  | 192      | 2.7%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 177      | 2.49%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 175      | 2.46%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 156      | 2.2%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 140      | 1.97%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 136      | 1.91%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 118      | 1.66%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 116      | 1.63%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 110      | 1.55%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 104      | 1.46%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 92       | 1.29%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 85       | 1.2%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 84       | 1.18%   |
| AMD FCH SATA Controller D                                                               | 84       | 1.18%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 71       | 1%      |
| Samsung NVMe SSD Controller 980                                                         | 67       | 0.94%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 66       | 0.93%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 63       | 0.89%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 62       | 0.87%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 56       | 0.79%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 56       | 0.79%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 53       | 0.75%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 52       | 0.73%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 48       | 0.68%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 48       | 0.68%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 46       | 0.65%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 44       | 0.62%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 42       | 0.59%   |
| Nvidia MCP61 SATA Controller                                                            | 42       | 0.59%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 40       | 0.56%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 40       | 0.56%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 39       | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 3294     | 57.69%  |
| NVMe | 1201     | 21.03%  |
| IDE  | 755      | 13.22%  |
| RAID | 390      | 6.83%   |
| SAS  | 53       | 0.93%   |
| SCSI | 17       | 0.3%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 2732     | 67.98%  |
| AMD    | 1287     | 32.02%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 67       | 1.66%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 59       | 1.46%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 51       | 1.26%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 48       | 1.19%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 46       | 1.14%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 46       | 1.14%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 45       | 1.12%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 44       | 1.09%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 43       | 1.07%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 41       | 1.02%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 40       | 0.99%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 40       | 0.99%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 39       | 0.97%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 38       | 0.94%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 37       | 0.92%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 35       | 0.87%   |
| AMD FX-8350 Eight-Core Processor            | 35       | 0.87%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 34       | 0.84%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 32       | 0.79%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 32       | 0.79%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 31       | 0.77%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 30       | 0.74%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 28       | 0.69%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 27       | 0.67%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 27       | 0.67%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 27       | 0.67%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 24       | 0.6%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 24       | 0.6%    |
| Intel Core i5 CPU 650 @ 3.20GHz             | 23       | 0.57%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 22       | 0.55%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 22       | 0.55%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 22       | 0.55%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 22       | 0.55%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 22       | 0.55%   |
| AMD FX-6300 Six-Core Processor              | 22       | 0.55%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 21       | 0.52%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 21       | 0.52%   |
| Intel 12th Gen Core i9-12900K               | 21       | 0.52%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 21       | 0.52%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 21       | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 789      | 19.6%   |
| Intel Core i7           | 592      | 14.7%   |
| AMD Ryzen 5             | 322      | 8%      |
| Intel Core i3           | 321      | 7.97%   |
| Intel Xeon              | 269      | 6.68%   |
| Other                   | 247      | 6.14%   |
| AMD Ryzen 7             | 211      | 5.24%   |
| AMD Ryzen 9             | 151      | 3.75%   |
| AMD FX                  | 132      | 3.28%   |
| Intel Celeron           | 124      | 3.08%   |
| Intel Core 2 Duo        | 91       | 2.26%   |
| Intel Core 2 Quad       | 87       | 2.16%   |
| Intel Pentium           | 82       | 2.04%   |
| AMD Ryzen 3             | 61       | 1.52%   |
| AMD A10                 | 49       | 1.22%   |
| Intel Core i9           | 39       | 0.97%   |
| Intel Pentium Dual-Core | 37       | 0.92%   |
| AMD Phenom II X4        | 37       | 0.92%   |
| AMD Ryzen Threadripper  | 34       | 0.84%   |
| AMD Athlon II X2        | 33       | 0.82%   |
| AMD A8                  | 33       | 0.82%   |
| AMD A6                  | 26       | 0.65%   |
| AMD Athlon 64 X2        | 20       | 0.5%    |
| AMD Phenom II X6        | 19       | 0.47%   |
| AMD A4                  | 19       | 0.47%   |
| Intel Core 2            | 17       | 0.42%   |
| AMD Athlon II X4        | 17       | 0.42%   |
| AMD Athlon              | 17       | 0.42%   |
| Intel Atom              | 14       | 0.35%   |
| AMD Ryzen 5 PRO         | 11       | 0.27%   |
| AMD Phenom II X2        | 11       | 0.27%   |
| Intel Pentium Dual      | 10       | 0.25%   |
| AMD Athlon II X3        | 10       | 0.25%   |
| AMD Sempron             | 8        | 0.2%    |
| AMD Athlon X4           | 8        | 0.2%    |
| Intel Pentium Gold      | 7        | 0.17%   |
| Intel Pentium 4         | 7        | 0.17%   |
| AMD Ryzen 3 PRO         | 6        | 0.15%   |
| AMD Phenom              | 5        | 0.12%   |
| AMD E1                  | 5        | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 1629     | 40.46%  |
| 2      | 850      | 21.11%  |
| 6      | 618      | 15.35%  |
| 8      | 433      | 10.76%  |
| 12     | 157      | 3.9%    |
| 16     | 121      | 3.01%   |
| 1      | 59       | 1.47%   |
| 3      | 53       | 1.32%   |
| 10     | 36       | 0.89%   |
| 24     | 23       | 0.57%   |
| 14     | 11       | 0.27%   |
| 32     | 10       | 0.25%   |
| 28     | 10       | 0.25%   |
| 20     | 5        | 0.12%   |
| 18     | 5        | 0.12%   |
| 64     | 2        | 0.05%   |
| 128    | 1        | 0.02%   |
| 44     | 1        | 0.02%   |
| 40     | 1        | 0.02%   |
| 36     | 1        | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 3933     | 97.86%  |
| 2      | 86       | 2.14%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 2375     | 59.01%  |
| 1      | 1648     | 40.94%  |
| 6      | 1        | 0.02%   |
| 4      | 1        | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 4017     | 99.93%  |
| Unknown        | 3        | 0.07%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 2516     | 61.07%  |
| 0x306c3    | 165      | 4%      |
| 0x306a9    | 106      | 2.57%   |
| 0x506e3    | 92       | 2.23%   |
| 0x206a7    | 88       | 2.14%   |
| 0x08701021 | 68       | 1.65%   |
| 0x906ea    | 62       | 1.5%    |
| 0x906e9    | 57       | 1.38%   |
| 0x90672    | 42       | 1.02%   |
| 0x0a20120a | 40       | 0.97%   |
| 0x0a201016 | 37       | 0.9%    |
| 0x0800820d | 36       | 0.87%   |
| 0x06000852 | 36       | 0.87%   |
| 0xa0671    | 35       | 0.85%   |
| 0xa0653    | 35       | 0.85%   |
| 0x306f2    | 34       | 0.83%   |
| 0x1067a    | 31       | 0.75%   |
| 0xa0655    | 29       | 0.7%    |
| 0x906ed    | 29       | 0.7%    |
| 0x0a601203 | 29       | 0.7%    |
| 0x010000c8 | 28       | 0.68%   |
| 0x08108109 | 24       | 0.58%   |
| 0xb0671    | 20       | 0.49%   |
| 0x08701013 | 20       | 0.49%   |
| 0x0a50000d | 16       | 0.39%   |
| 0x0a50000c | 16       | 0.39%   |
| 0x06003106 | 16       | 0.39%   |
| 0x906ec    | 14       | 0.34%   |
| 0x406f1    | 14       | 0.34%   |
| 0x06001119 | 14       | 0.34%   |
| 0x906eb    | 13       | 0.32%   |
| 0x106e5    | 13       | 0.32%   |
| 0x0a201205 | 13       | 0.32%   |
| 0x106a5    | 11       | 0.27%   |
| 0x0a201009 | 11       | 0.27%   |
| 0x08001138 | 11       | 0.27%   |
| 0x20655    | 10       | 0.24%   |
| 0x0810100b | 10       | 0.24%   |
| 0x906c0    | 9        | 0.22%   |
| 0x90675    | 9        | 0.22%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 534      | 13.27%  |
| KabyLake         | 373      | 9.27%   |
| IvyBridge        | 320      | 7.95%   |
| SandyBridge      | 281      | 6.98%   |
| Zen 3            | 275      | 6.83%   |
| Skylake          | 248      | 6.16%   |
| Zen 2            | 232      | 5.76%   |
| Penryn           | 187      | 4.65%   |
| Unknown          | 182      | 4.52%   |
| Piledriver       | 169      | 4.2%    |
| K10              | 147      | 3.65%   |
| Zen+             | 143      | 3.55%   |
| CometLake        | 127      | 3.16%   |
| Westmere         | 112      | 2.78%   |
| Zen              | 104      | 2.58%   |
| Core             | 89       | 2.21%   |
| Alderlake Hybrid | 76       | 1.89%   |
| Nehalem          | 71       | 1.76%   |
| Steamroller      | 43       | 1.07%   |
| Icelake          | 42       | 1.04%   |
| Silvermont       | 39       | 0.97%   |
| Broadwell        | 37       | 0.92%   |
| K8 Hammer        | 30       | 0.75%   |
| Excavator        | 26       | 0.65%   |
| Goldmont plus    | 25       | 0.62%   |
| Bulldozer        | 25       | 0.62%   |
| Goldmont         | 17       | 0.42%   |
| NetBurst         | 12       | 0.3%    |
| K10 Llano        | 12       | 0.3%    |
| Tremont          | 10       | 0.25%   |
| Jaguar           | 9        | 0.22%   |
| TigerLake        | 8        | 0.2%    |
| Bobcat           | 7        | 0.17%   |
| Puma             | 6        | 0.15%   |
| Bonnell          | 6        | 0.15%   |
| Gracemont        | 1        | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Nvidia                                       | 1763     | 40.55%  |
| Intel                                        | 1407     | 32.36%  |
| AMD                                          | 1130     | 25.99%  |
| ASPEED Technology                            | 23       | 0.53%   |
| Matrox Electronics Systems                   | 21       | 0.48%   |
| ATI Technologies                             | 2        | 0.05%   |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 0.02%   |
| VIA Technologies                             | 1        | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 244      | 5.49%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 137      | 3.08%   |
| Intel HD Graphics 530                                                       | 135      | 3.04%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 128      | 2.88%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 122      | 2.75%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 107      | 2.41%   |
| Nvidia GK208B [GeForce GT 710]                                              | 88       | 1.98%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 66       | 1.49%   |
| Intel HD Graphics 630                                                       | 66       | 1.49%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 66       | 1.49%   |
| Nvidia GT218 [GeForce 210]                                                  | 63       | 1.42%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 61       | 1.37%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 59       | 1.33%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 57       | 1.28%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 56       | 1.26%   |
| Nvidia GK208B [GeForce GT 730]                                              | 52       | 1.17%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 48       | 1.08%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 47       | 1.06%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 47       | 1.06%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 44       | 0.99%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 42       | 0.95%   |
| AMD Raphael                                                                 | 41       | 0.92%   |
| Intel AlderLake-S GT1                                                       | 40       | 0.9%    |
| Nvidia GP104 [GeForce GTX 1070]                                             | 37       | 0.83%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 35       | 0.79%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 35       | 0.79%   |
| Nvidia GF119 [GeForce GT 610]                                               | 33       | 0.74%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 33       | 0.74%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 33       | 0.74%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 31       | 0.7%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 31       | 0.7%    |
| Nvidia GP104 [GeForce GTX 1080]                                             | 30       | 0.68%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 29       | 0.65%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 29       | 0.65%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 29       | 0.65%   |
| Intel Core Processor Integrated Graphics Controller                         | 28       | 0.63%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 28       | 0.63%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 27       | 0.61%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 27       | 0.61%   |
| AMD RS780L [Radeon 3000]                                                    | 26       | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Nvidia               | 1588     | 39.16%  |
| 1 x Intel                | 1193     | 29.42%  |
| 1 x AMD                  | 998      | 24.61%  |
| Intel + Nvidia           | 70       | 1.73%   |
| AMD + Nvidia             | 61       | 1.5%    |
| 2 x AMD                  | 41       | 1.01%   |
| 2 x Nvidia               | 25       | 0.62%   |
| Intel + AMD              | 23       | 0.57%   |
| 1 x Matrox               | 15       | 0.37%   |
| 1 x ASPEED               | 15       | 0.37%   |
| Nvidia + ASPEED          | 7        | 0.17%   |
| Nvidia + Matrox          | 4        | 0.1%    |
| Other                    | 2        | 0.05%   |
| Intel + AMD + 1 x Nvidia | 2        | 0.05%   |
| AMD + Matrox             | 2        | 0.05%   |
| 3 x AMD                  | 1        | 0.02%   |
| 1 x XGI                  | 1        | 0.02%   |
| 1 x VIA                  | 1        | 0.02%   |
| 1 x Intel + 3 x Nvidia   | 1        | 0.02%   |
| Intel + 2 x Nvidia       | 1        | 0.02%   |
| Intel + 2 x AMD          | 1        | 0.02%   |
| Intel + AMD + 3 x Nvidia | 1        | 0.02%   |
| AMD + 2 x Nvidia         | 1        | 0.02%   |
| AMD + ASPEED             | 1        | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 2799     | 68.52%  |
| Proprietary | 1076     | 26.34%  |
| Unknown     | 210      | 5.14%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 2955     | 72.34%  |
| 1.01-2.0   | 249      | 6.1%    |
| 7.01-8.0   | 191      | 4.68%   |
| 0.51-1.0   | 186      | 4.55%   |
| 3.01-4.0   | 156      | 3.82%   |
| 0.01-0.5   | 130      | 3.18%   |
| 8.01-16.0  | 96       | 2.35%   |
| 5.01-6.0   | 61       | 1.49%   |
| 2.01-3.0   | 28       | 0.69%   |
| 16.01-24.0 | 28       | 0.69%   |
| 4.01-5.0   | 5        | 0.12%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 692      | 17.08%  |
| Dell                 | 477      | 11.77%  |
| Goldstar             | 387      | 9.55%   |
| Hewlett-Packard      | 286      | 7.06%   |
| Acer                 | 273      | 6.74%   |
| BenQ                 | 196      | 4.84%   |
| AOC                  | 188      | 4.64%   |
| Philips              | 178      | 4.39%   |
| Ancor Communications | 157      | 3.88%   |
| Iiyama               | 92       | 2.27%   |
| Lenovo               | 84       | 2.07%   |
| ViewSonic            | 79       | 1.95%   |
| ASUSTek Computer     | 77       | 1.9%    |
| Sony                 | 57       | 1.41%   |
| Vizio                | 36       | 0.89%   |
| Fujitsu Siemens      | 35       | 0.86%   |
| LG Electronics       | 33       | 0.81%   |
| Panasonic            | 31       | 0.77%   |
| Sceptre Tech         | 29       | 0.72%   |
| NEC Computers        | 28       | 0.69%   |
| MSI                  | 28       | 0.69%   |
| Unknown              | 27       | 0.67%   |
| Eizo                 | 27       | 0.67%   |
| HannStar             | 20       | 0.49%   |
| Medion               | 19       | 0.47%   |
| Unknown              | 19       | 0.47%   |
| Toshiba              | 15       | 0.37%   |
| Apple                | 14       | 0.35%   |
| HKC                  | 12       | 0.3%    |
| Gigabyte Technology  | 12       | 0.3%    |
| Vestel Elektronik    | 11       | 0.27%   |
| Sharp                | 11       | 0.27%   |
| Unknown (XXX)        | 10       | 0.25%   |
| RTK                  | 10       | 0.25%   |
| Mi                   | 10       | 0.25%   |
| HUAWEI               | 10       | 0.25%   |
| Hitachi              | 10       | 0.25%   |
| Gericom              | 10       | 0.25%   |
| Plain Tree Systems   | 8        | 0.2%    |
| MStar                | 8        | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                     | 21       | 0.49%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 20       | 0.47%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 19       | 0.44%   |
| Unknown                                                               | 19       | 0.44%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 18       | 0.42%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 16       | 0.37%   |
| Samsung Electronics LCD Monitor LF24T450F 1920x1080                   | 15       | 0.35%   |
| AOC 24V2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                    | 15       | 0.35%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 14       | 0.33%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 13       | 0.3%    |
| Sony TV SNY3102 1920x1080 708x398mm 32.0-inch                         | 12       | 0.28%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 12       | 0.28%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch    | 11       | 0.26%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 11       | 0.26%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 950x540mm 43.0-inch | 10       | 0.23%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 10       | 0.23%   |
| AOC 27B2 AOC2702 1920x1080 598x336mm 27.0-inch                        | 10       | 0.23%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 10       | 0.23%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch     | 9        | 0.21%   |
| Philips 247EL PHLC084 1920x1080 521x293mm 23.5-inch                   | 9        | 0.21%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                    | 9        | 0.21%   |
| Gericom Q26 QMX2426 1920x1080 550x344mm 25.5-inch                     | 9        | 0.21%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 8        | 0.19%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 8        | 0.19%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 798x334mm 34.1-inch              | 8        | 0.19%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 8        | 0.19%   |
| AOC G2790G4 AOC2790 1920x1080 598x336mm 27.0-inch                     | 8        | 0.19%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch | 7        | 0.16%   |
| Philips PHL 273V7 PHLC156 1920x1080 600x340mm 27.2-inch               | 7        | 0.16%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch               | 7        | 0.16%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                | 7        | 0.16%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                     | 7        | 0.16%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                     | 7        | 0.16%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                    | 7        | 0.16%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch      | 7        | 0.16%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 6        | 0.14%   |
| Sceptre Tech E24 SPT099D 1920x1080 530x300mm 24.0-inch                | 6        | 0.14%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch     | 6        | 0.14%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 520x290mm 23.4-inch     | 6        | 0.14%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch     | 6        | 0.14%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 1860     | 46.89%  |
| 3840x2160 (4K)     | 449      | 11.32%  |
| 2560x1440 (QHD)    | 273      | 6.88%   |
| 1280x1024 (SXGA)   | 226      | 5.7%    |
| 1680x1050 (WSXGA+) | 194      | 4.89%   |
| 1366x768 (WXGA)    | 139      | 3.5%    |
| 1920x1200 (WUXGA)  | 133      | 3.35%   |
| 1440x900 (WXGA+)   | 122      | 3.08%   |
| 1600x900 (HD+)     | 121      | 3.05%   |
| 3440x1440          | 62       | 1.56%   |
| 2560x1080          | 56       | 1.41%   |
| 1360x768           | 50       | 1.26%   |
| Unknown            | 50       | 1.26%   |
| 1920x540           | 40       | 1.01%   |
| 3840x1080          | 32       | 0.81%   |
| 1024x768 (XGA)     | 27       | 0.68%   |
| 1280x720 (HD)      | 20       | 0.5%    |
| 1600x1200          | 18       | 0.45%   |
| 2560x1600          | 13       | 0.33%   |
| 3840x1600          | 11       | 0.28%   |
| 2288x1287          | 11       | 0.28%   |
| 2048x1152          | 7        | 0.18%   |
| 1400x1050          | 6        | 0.15%   |
| 3840x1200          | 5        | 0.13%   |
| 1280x960           | 5        | 0.13%   |
| 4480x1440          | 3        | 0.08%   |
| 3600x1080          | 3        | 0.08%   |
| 5760x1080          | 2        | 0.05%   |
| 5120x1440          | 2        | 0.05%   |
| 3360x1080          | 2        | 0.05%   |
| 1280x768           | 2        | 0.05%   |
| 7680x2160          | 1        | 0.03%   |
| 720x480            | 1        | 0.03%   |
| 6400x2160          | 1        | 0.03%   |
| 5760x2160          | 1        | 0.03%   |
| 5520x1080          | 1        | 0.03%   |
| 4480x1080          | 1        | 0.03%   |
| 4240x1440          | 1        | 0.03%   |
| 4093x4093          | 1        | 0.03%   |
| 4080x2058          | 1        | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 574      | 14.15%  |
| 24      | 566      | 13.95%  |
| 23      | 515      | 12.7%   |
| 21      | 439      | 10.82%  |
| Unknown | 275      | 6.78%   |
| 19      | 254      | 6.26%   |
| 31      | 213      | 5.25%   |
| 20      | 133      | 3.28%   |
| 22      | 130      | 3.21%   |
| 18      | 128      | 3.16%   |
| 17      | 116      | 2.86%   |
| 34      | 94       | 2.32%   |
| 84      | 75       | 1.85%   |
| 32      | 59       | 1.45%   |
| 15      | 53       | 1.31%   |
| 72      | 44       | 1.08%   |
| 40      | 41       | 1.01%   |
| 54      | 39       | 0.96%   |
| 25      | 36       | 0.89%   |
| 28      | 21       | 0.52%   |
| 46      | 19       | 0.47%   |
| 42      | 17       | 0.42%   |
| 37      | 16       | 0.39%   |
| 65      | 15       | 0.37%   |
| 52      | 14       | 0.35%   |
| 29      | 14       | 0.35%   |
| 26      | 14       | 0.35%   |
| 43      | 12       | 0.3%    |
| 36      | 12       | 0.3%    |
| 48      | 11       | 0.27%   |
| 49      | 10       | 0.25%   |
| 35      | 8        | 0.2%    |
| 14      | 7        | 0.17%   |
| 142     | 6        | 0.15%   |
| 64      | 6        | 0.15%   |
| 12      | 6        | 0.15%   |
| 60      | 5        | 0.12%   |
| 57      | 5        | 0.12%   |
| 50      | 5        | 0.12%   |
| 39      | 5        | 0.12%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 1542     | 39.12%  |
| 401-500        | 948      | 24.05%  |
| 601-700        | 315      | 7.99%   |
| Unknown        | 275      | 6.98%   |
| 701-800        | 171      | 4.34%   |
| 301-350        | 162      | 4.11%   |
| 351-400        | 139      | 3.53%   |
| 1001-1500      | 139      | 3.53%   |
| 1501-2000      | 128      | 3.25%   |
| 801-900        | 73       | 1.85%   |
| 901-1000       | 29       | 0.74%   |
| 201-300        | 14       | 0.36%   |
| More than 2000 | 7        | 0.18%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 2588     | 68.65%  |
| 16/10   | 483      | 12.81%  |
| 5/4     | 223      | 5.92%   |
| Unknown | 221      | 5.86%   |
| 21/9    | 126      | 3.34%   |
| 4/3     | 57       | 1.51%   |
| 32/9    | 24       | 0.64%   |
| 3/2     | 19       | 0.5%    |
| 6/5     | 10       | 0.27%   |
| 1.00    | 8        | 0.21%   |
| 0.56    | 3        | 0.08%   |
| 2.12    | 2        | 0.05%   |
| 2.00    | 2        | 0.05%   |
| 1.96    | 2        | 0.05%   |
| 3.20    | 1        | 0.03%   |
| 0.89    | 1        | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 1297     | 32.55%  |
| 301-350        | 584      | 14.65%  |
| 151-200        | 520      | 13.05%  |
| 351-500        | 400      | 10.04%  |
| Unknown        | 275      | 6.9%    |
| More than 1000 | 239      | 6%      |
| 251-300        | 234      | 5.87%   |
| 141-150        | 211      | 5.29%   |
| 501-1000       | 143      | 3.59%   |
| 101-110        | 46       | 1.15%   |
| 71-80          | 9        | 0.23%   |
| 131-140        | 9        | 0.23%   |
| 111-120        | 9        | 0.23%   |
| 81-90          | 4        | 0.1%    |
| 121-130        | 2        | 0.05%   |
| 91-100         | 2        | 0.05%   |
| 41-50          | 1        | 0.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 2395     | 62.76%  |
| 101-120       | 667      | 17.48%  |
| Unknown       | 275      | 7.21%   |
| 1-50          | 204      | 5.35%   |
| 121-160       | 185      | 4.85%   |
| 161-240       | 89       | 2.33%   |
| More than 240 | 1        | 0.03%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 3023     | 73.77%  |
| 2     | 651      | 15.89%  |
| 0     | 345      | 8.42%   |
| 3     | 67       | 1.63%   |
| 4     | 10       | 0.24%   |
| 6     | 1        | 0.02%   |
| 5     | 1        | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 2385     | 41.91%  |
| Intel                           | 1877     | 32.98%  |
| Qualcomm Atheros                | 289      | 5.08%   |
| Broadcom                        | 167      | 2.93%   |
| TP-Link                         | 120      | 2.11%   |
| Ralink Technology               | 108      | 1.9%    |
| MediaTek                        | 79       | 1.39%   |
| Nvidia                          | 74       | 1.3%    |
| Ralink                          | 62       | 1.09%   |
| Aquantia                        | 44       | 0.77%   |
| NetGear                         | 36       | 0.63%   |
| Broadcom Limited                | 33       | 0.58%   |
| Marvell Technology Group        | 32       | 0.56%   |
| Qualcomm Atheros Communications | 27       | 0.47%   |
| Microsoft                       | 27       | 0.47%   |
| ASIX Electronics                | 27       | 0.47%   |
| Samsung Electronics             | 26       | 0.46%   |
| D-Link System                   | 24       | 0.42%   |
| Xiaomi                          | 21       | 0.37%   |
| D-Link                          | 19       | 0.33%   |
| ASUSTek Computer                | 17       | 0.3%    |
| Edimax Technology               | 13       | 0.23%   |
| Linksys                         | 12       | 0.21%   |
| IMC Networks                    | 10       | 0.18%   |
| DisplayLink                     | 10       | 0.18%   |
| Sitecom Europe                  | 7        | 0.12%   |
| Qualcomm                        | 7        | 0.12%   |
| Belkin Components               | 6        | 0.11%   |
| AVM                             | 6        | 0.11%   |
| VIA Technologies                | 5        | 0.09%   |
| Huawei Technologies             | 5        | 0.09%   |
| ZyDAS                           | 4        | 0.07%   |
| Wilocity                        | 4        | 0.07%   |
| Sigma Designs                   | 4        | 0.07%   |
| OPPO Electronics                | 4        | 0.07%   |
| JMicron Technology              | 4        | 0.07%   |
| ICS Advent                      | 4        | 0.07%   |
| ZTE WCDMA Technologies MSM      | 3        | 0.05%   |
| Texas Instruments               | 3        | 0.05%   |
| Micro Star International        | 3        | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1847     | 28.34%  |
| Realtek RTL8125 2.5GbE Controller                                 | 270      | 4.14%   |
| Intel I211 Gigabit Network Connection                             | 201      | 3.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 191      | 2.93%   |
| Intel Wi-Fi 6 AX200                                               | 172      | 2.64%   |
| Intel Ethernet Controller I225-V                                  | 144      | 2.21%   |
| Intel Ethernet Connection I217-LM                                 | 144      | 2.21%   |
| Intel Ethernet Connection (2) I219-V                              | 139      | 2.13%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 80       | 1.23%   |
| Intel 82579V Gigabit Network Connection                           | 80       | 1.23%   |
| Intel Ethernet Connection (7) I219-V                              | 73       | 1.12%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 69       | 1.06%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 68       | 1.04%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 67       | 1.03%   |
| Intel Ethernet Connection (2) I219-LM                             | 63       | 0.97%   |
| Realtek 802.11ac NIC                                              | 61       | 0.94%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 55       | 0.84%   |
| Intel Ethernet Connection I217-V                                  | 53       | 0.81%   |
| Intel Ethernet Connection (2) I218-V                              | 49       | 0.75%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 45       | 0.69%   |
| Intel 82574L Gigabit Network Connection                           | 44       | 0.68%   |
| Ralink MT7601U Wireless Adapter                                   | 42       | 0.64%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 41       | 0.63%   |
| Nvidia MCP61 Ethernet                                             | 38       | 0.58%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 37       | 0.57%   |
| Intel Wireless-AC 9260                                            | 36       | 0.55%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 36       | 0.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 34       | 0.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 34       | 0.52%   |
| Intel Wireless 7265                                               | 33       | 0.51%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 32       | 0.49%   |
| Intel Wireless 7260                                               | 32       | 0.49%   |
| Intel I210 Gigabit Network Connection                             | 31       | 0.48%   |
| Intel Ethernet Connection (7) I219-LM                             | 29       | 0.44%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 29       | 0.44%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 28       | 0.43%   |
| Intel Wireless 3165                                               | 27       | 0.41%   |
| Intel Ethernet Connection (5) I219-LM                             | 27       | 0.41%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 27       | 0.41%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 26       | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 672      | 34.23%  |
| Realtek Semiconductor                 | 462      | 23.54%  |
| Qualcomm Atheros                      | 162      | 8.25%   |
| TP-Link                               | 117      | 5.96%   |
| Ralink Technology                     | 108      | 5.5%    |
| MediaTek                              | 73       | 3.72%   |
| Broadcom                              | 65       | 3.31%   |
| Ralink                                | 62       | 3.16%   |
| NetGear                               | 36       | 1.83%   |
| Qualcomm Atheros Communications       | 27       | 1.38%   |
| Microsoft                             | 27       | 1.38%   |
| D-Link System                         | 19       | 0.97%   |
| D-Link                                | 19       | 0.97%   |
| Broadcom Limited                      | 16       | 0.82%   |
| ASUSTek Computer                      | 16       | 0.82%   |
| Edimax Technology                     | 13       | 0.66%   |
| Linksys                               | 10       | 0.51%   |
| IMC Networks                          | 10       | 0.51%   |
| Sitecom Europe                        | 7        | 0.36%   |
| Belkin Components                     | 6        | 0.31%   |
| AVM                                   | 6        | 0.31%   |
| ZyDAS                                 | 4        | 0.2%    |
| Wilocity                              | 4        | 0.2%    |
| Micro Star International              | 3        | 0.15%   |
| Mercucys                              | 3        | 0.15%   |
| BUFFALO                               | 3        | 0.15%   |
| Gemtek                                | 2        | 0.1%    |
| Encore Electronics                    | 2        | 0.1%    |
| ZyXEL Communications                  | 1        | 0.05%   |
| TRENDnet                              | 1        | 0.05%   |
| Sierra Wireless                       | 1        | 0.05%   |
| Sagem                                 | 1        | 0.05%   |
| Philips (or NXP)                      | 1        | 0.05%   |
| LSI                                   | 1        | 0.05%   |
| Guillemot                             | 1        | 0.05%   |
| Dell                                  | 1        | 0.05%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                           | 172      | 8.65%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 80       | 4.02%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 69       | 3.47%   |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 67       | 3.37%   |
| Realtek 802.11ac NIC                                          | 61       | 3.07%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 55       | 2.77%   |
| Intel Alder Lake-S PCH CNVi WiFi                              | 45       | 2.26%   |
| Ralink MT7601U Wireless Adapter                               | 42       | 2.11%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 41       | 2.06%   |
| Intel Wireless-AC 9260                                        | 36       | 1.81%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 34       | 1.71%   |
| Intel Wireless 7265                                           | 33       | 1.66%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 32       | 1.61%   |
| Intel Wireless 7260                                           | 32       | 1.61%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter            | 28       | 1.41%   |
| Intel Wireless 3165                                           | 27       | 1.36%   |
| Intel Comet Lake PCH CNVi WiFi                                | 27       | 1.36%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter               | 25       | 1.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 25       | 1.26%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter         | 24       | 1.21%   |
| Ralink RT5370 Wireless Adapter                                | 23       | 1.16%   |
| Qualcomm Atheros AR9271 802.11n                               | 23       | 1.16%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 23       | 1.16%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter              | 22       | 1.11%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                    | 21       | 1.06%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                   | 20       | 1.01%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                  | 19       | 0.96%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter               | 19       | 0.96%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 19       | 0.96%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 19       | 0.96%   |
| Intel Wireless 8260                                           | 19       | 0.96%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter      | 18       | 0.9%    |
| Intel Tiger Lake PCH CNVi WiFi                                | 18       | 0.9%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                           | 16       | 0.8%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                        | 15       | 0.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 15       | 0.75%   |
| Intel 700 Series Chipset Family Wi-Fi                         | 15       | 0.75%   |
| Ralink RT2870/RT3070 Wireless Adapter                         | 14       | 0.7%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter              | 14       | 0.7%    |
| Microsoft Xbox Wireless Adapter for Windows                   | 14       | 0.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 2223     | 51.34%  |
| Intel                                  | 1532     | 35.38%  |
| Qualcomm Atheros                       | 144      | 3.33%   |
| Broadcom                               | 105      | 2.42%   |
| Nvidia                                 | 74       | 1.71%   |
| Aquantia                               | 44       | 1.02%   |
| Marvell Technology Group               | 32       | 0.74%   |
| ASIX Electronics                       | 27       | 0.62%   |
| Samsung Electronics                    | 26       | 0.6%    |
| Xiaomi                                 | 21       | 0.48%   |
| Broadcom Limited                       | 17       | 0.39%   |
| DisplayLink                            | 10       | 0.23%   |
| Qualcomm                               | 7        | 0.16%   |
| VIA Technologies                       | 5        | 0.12%   |
| MediaTek                               | 5        | 0.12%   |
| D-Link System                          | 5        | 0.12%   |
| OPPO Electronics                       | 4        | 0.09%   |
| JMicron Technology                     | 4        | 0.09%   |
| ICS Advent                             | 4        | 0.09%   |
| Huawei Technologies                    | 4        | 0.09%   |
| ZTE WCDMA Technologies MSM             | 3        | 0.07%   |
| TP-Link                                | 3        | 0.07%   |
| Google                                 | 3        | 0.07%   |
| Chelsio Communications                 | 3        | 0.07%   |
| Tehuti Networks                        | 2        | 0.05%   |
| Sundance Technology Inc / IC Plus      | 2        | 0.05%   |
| Sony Ericsson Mobile Communications AB | 2        | 0.05%   |
| Mellanox Technologies                  | 2        | 0.05%   |
| Linksys                                | 2        | 0.05%   |
| Apple                                  | 2        | 0.05%   |
| American Megatrends                    | 2        | 0.05%   |
| 3Com                                   | 2        | 0.05%   |
| Vimtron Electronics                    | 1        | 0.02%   |
| Spreadtrum Communications              | 1        | 0.02%   |
| Prolific Technology                    | 1        | 0.02%   |
| MUCSE                                  | 1        | 0.02%   |
| Motorola PCS                           | 1        | 0.02%   |
| MosChip Semiconductor                  | 1        | 0.02%   |
| LG Electronics                         | 1        | 0.02%   |
| Compal Electronics                     | 1        | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1847     | 41.2%   |
| Realtek RTL8125 2.5GbE Controller                                 | 270      | 6.02%   |
| Intel I211 Gigabit Network Connection                             | 201      | 4.48%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 191      | 4.26%   |
| Intel Ethernet Controller I225-V                                  | 144      | 3.21%   |
| Intel Ethernet Connection I217-LM                                 | 144      | 3.21%   |
| Intel Ethernet Connection (2) I219-V                              | 139      | 3.1%    |
| Intel 82579V Gigabit Network Connection                           | 80       | 1.78%   |
| Intel Ethernet Connection (7) I219-V                              | 73       | 1.63%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 68       | 1.52%   |
| Intel Ethernet Connection (2) I219-LM                             | 63       | 1.41%   |
| Intel Ethernet Connection I217-V                                  | 53       | 1.18%   |
| Intel Ethernet Connection (2) I218-V                              | 49       | 1.09%   |
| Intel 82574L Gigabit Network Connection                           | 44       | 0.98%   |
| Nvidia MCP61 Ethernet                                             | 38       | 0.85%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 37       | 0.83%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 36       | 0.8%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 34       | 0.76%   |
| Intel I210 Gigabit Network Connection                             | 31       | 0.69%   |
| Intel Ethernet Connection (7) I219-LM                             | 29       | 0.65%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 29       | 0.65%   |
| Intel Ethernet Connection (5) I219-LM                             | 27       | 0.6%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 26       | 0.58%   |
| ASIX AX88179 Gigabit Ethernet                                     | 22       | 0.49%   |
| Intel 82578DC Gigabit Network Connection                          | 21       | 0.47%   |
| Intel Ethernet Connection (14) I219-V                             | 20       | 0.45%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 19       | 0.42%   |
| Intel Ethernet Connection (2) I218-LM                             | 19       | 0.42%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 18       | 0.4%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 18       | 0.4%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 18       | 0.4%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 17       | 0.38%   |
| Intel Ethernet Controller X550                                    | 17       | 0.38%   |
| Intel Ethernet Connection (17) I219-V                             | 17       | 0.38%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 16       | 0.36%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 16       | 0.36%   |
| Intel 82578DM Gigabit Network Connection                          | 16       | 0.36%   |
| Intel Ethernet Controller I226-V                                  | 14       | 0.31%   |
| Intel Ethernet Connection (11) I219-V                             | 14       | 0.31%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 14       | 0.31%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 3987     | 67.99%  |
| WiFi     | 1832     | 31.24%  |
| Modem    | 40       | 0.68%   |
| Unknown  | 5        | 0.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 3196     | 75.93%  |
| WiFi     | 1013     | 24.07%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 2494     | 61.72%  |
| 2     | 1286     | 31.82%  |
| 3     | 186      | 4.6%    |
| 4     | 35       | 0.87%   |
| 0     | 24       | 0.59%   |
| 5     | 10       | 0.25%   |
| 8     | 2        | 0.05%   |
| 7     | 2        | 0.05%   |
| 9     | 1        | 0.02%   |
| 6     | 1        | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2722     | 67.28%  |
| Yes  | 1324     | 32.72%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 617      | 45.4%   |
| Cambridge Silicon Radio         | 257      | 18.91%  |
| Realtek Semiconductor           | 94       | 6.92%   |
| ASUSTek Computer                | 83       | 6.11%   |
| Qualcomm Atheros Communications | 56       | 4.12%   |
| Broadcom                        | 54       | 3.97%   |
| MediaTek                        | 39       | 2.87%   |
| IMC Networks                    | 30       | 2.21%   |
| TP-Link                         | 24       | 1.77%   |
| Apple                           | 23       | 1.69%   |
| Lite-On Technology              | 18       | 1.32%   |
| Foxconn / Hon Hai               | 12       | 0.88%   |
| Belkin Components               | 8        | 0.59%   |
| Edimax Technology               | 5        | 0.37%   |
| Micro Star International        | 4        | 0.29%   |
| Logitech                        | 4        | 0.29%   |
| Dell                            | 4        | 0.29%   |
| Realtek                         | 3        | 0.22%   |
| Unknown                         | 3        | 0.22%   |
| Toshiba                         | 2        | 0.15%   |
| Ralink                          | 2        | 0.15%   |
| Integrated System Solution      | 2        | 0.15%   |
| Hewlett-Packard                 | 2        | 0.15%   |
| Dynex                           | 2        | 0.15%   |
| D-Link System                   | 2        | 0.15%   |
| Conwise Technology              | 2        | 0.15%   |
| TRENDnet                        | 1        | 0.07%   |
| Primax Electronics              | 1        | 0.07%   |
| Mobile Action Technology        | 1        | 0.07%   |
| ISSC                            | 1        | 0.07%   |
| HTC (High Tech Computer)        | 1        | 0.07%   |
| D-Link                          | 1        | 0.07%   |
| Actions                         | 1        | 0.07%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 257      | 18.88%  |
| Intel AX200 Bluetooth                                 | 146      | 10.73%  |
| Intel Bluetooth wireless interface                    | 121      | 8.89%   |
| Intel AX210 Bluetooth                                 | 79       | 5.8%    |
| Intel AX201 Bluetooth                                 | 78       | 5.73%   |
| Realtek Bluetooth Radio                               | 70       | 5.14%   |
| Intel Wireless-AC 3168 Bluetooth                      | 67       | 4.92%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 47       | 3.45%   |
| MediaTek Wireless_Device                              | 39       | 2.87%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 36       | 2.65%   |
| Intel Bluetooth Device                                | 33       | 2.42%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 29       | 2.13%   |
| ASUS ASUS USB-BT500                                   | 26       | 1.91%   |
| TP-Link UB5A Adapter                                  | 24       | 1.76%   |
| Qualcomm Atheros  Bluetooth Device                    | 21       | 1.54%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 19       | 1.4%    |
| IMC Networks Bluetooth Radio                          | 17       | 1.25%   |
| Realtek  Bluetooth 4.2 Adapter                        | 14       | 1.03%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 14       | 1.03%   |
| ASUS Bluetooth Radio                                  | 14       | 1.03%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 12       | 0.88%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 10       | 0.73%   |
| Foxconn / Hon Hai Wireless_Device                     | 10       | 0.73%   |
| Lite-On Bluetooth Device                              | 9        | 0.66%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                  | 9        | 0.66%   |
| IMC Networks Wireless_Device                          | 8        | 0.59%   |
| Apple Bluetooth Host Controller                       | 8        | 0.59%   |
| Realtek RTL8821A Bluetooth                            | 7        | 0.51%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 7        | 0.51%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 5        | 0.37%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth            | 5        | 0.37%   |
| Broadcom BCM2045 Bluetooth                            | 5        | 0.37%   |
| ASUS Qualcomm Bluetooth 4.1                           | 5        | 0.37%   |
| ASUS Bluetooth Device                                 | 5        | 0.37%   |
| ASUS BCM20702A0                                       | 5        | 0.37%   |
| Qualcomm Atheros Bluetooth USB Host Controller        | 4        | 0.29%   |
| Micro Star International Bluetooth Device             | 4        | 0.29%   |
| Logitech BT Mini-Receiver (HCI mode)                  | 4        | 0.29%   |
| Edimax Bluetooth Adapter                              | 4        | 0.29%   |
| Broadcom BCM2035 Bluetooth dongle                     | 4        | 0.29%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 2607     | 38.99%  |
| Nvidia                                       | 1677     | 25.08%  |
| AMD                                          | 1593     | 23.82%  |
| C-Media Electronics                          | 131      | 1.96%   |
| Logitech                                     | 70       | 1.05%   |
| Creative Labs                                | 63       | 0.94%   |
| ASUSTek Computer                             | 50       | 0.75%   |
| GN Netcom                                    | 33       | 0.49%   |
| Micro Star International                     | 31       | 0.46%   |
| Texas Instruments                            | 26       | 0.39%   |
| Kingston Technology                          | 26       | 0.39%   |
| JMTek                                        | 22       | 0.33%   |
| Razer USA                                    | 20       | 0.3%    |
| SteelSeries ApS                              | 19       | 0.28%   |
| Focusrite-Novation                           | 18       | 0.27%   |
| Generalplus Technology                       | 17       | 0.25%   |
| Creative Technology                          | 16       | 0.24%   |
| Corsair                                      | 15       | 0.22%   |
| Plantronics                                  | 12       | 0.18%   |
| Zoran Co. Personal Media Division (Nogatech) | 9        | 0.13%   |
| VIA Technologies                             | 8        | 0.12%   |
| Tenx Technology                              | 8        | 0.12%   |
| Giga-Byte Technology                         | 8        | 0.12%   |
| Blue Microphones                             | 8        | 0.12%   |
| KTMicro                                      | 7        | 0.1%    |
| Hewlett-Packard                              | 7        | 0.1%    |
| Apple                                        | 7        | 0.1%    |
| Sony                                         | 6        | 0.09%   |
| Realtek Semiconductor                        | 6        | 0.09%   |
| M-Audio                                      | 6        | 0.09%   |
| Dell                                         | 6        | 0.09%   |
| Sennheiser Communications                    | 5        | 0.07%   |
| Samson Technologies                          | 5        | 0.07%   |
| Astro Gaming                                 | 5        | 0.07%   |
| BR23                                         | 4        | 0.06%   |
| Yamaha                                       | 3        | 0.04%   |
| Xilinx                                       | 3        | 0.04%   |
| Syntek                                       | 3        | 0.04%   |
| SAVITECH                                     | 3        | 0.04%   |
| RODE Microphones                             | 3        | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 403      | 5.22%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 385      | 4.99%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 299      | 3.87%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 274      | 3.55%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 241      | 3.12%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 230      | 2.98%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 229      | 2.97%   |
| AMD Family 17h/19h HD Audio Controller                                     | 229      | 2.97%   |
| Intel 200 Series PCH HD Audio                                              | 209      | 2.71%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 151      | 1.96%   |
| Intel Cannon Lake PCH cAVS                                                 | 146      | 1.89%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 144      | 1.87%   |
| AMD FCH Azalia Controller                                                  | 132      | 1.71%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 132      | 1.71%   |
| Nvidia GP107GL High Definition Audio Controller                            | 115      | 1.49%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 110      | 1.43%   |
| Intel Alder Lake-S HD Audio Controller                                     | 109      | 1.41%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 101      | 1.31%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 101      | 1.31%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 99       | 1.28%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 97       | 1.26%   |
| Nvidia High Definition Audio Controller                                    | 95       | 1.23%   |
| Nvidia GA104 High Definition Audio Controller                              | 94       | 1.22%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 91       | 1.18%   |
| Nvidia GP104 High Definition Audio Controller                              | 87       | 1.13%   |
| Nvidia GA102 High Definition Audio Controller                              | 83       | 1.08%   |
| Nvidia TU116 High Definition Audio Controller                              | 81       | 1.05%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 80       | 1.04%   |
| Nvidia GP106 High Definition Audio Controller                              | 79       | 1.02%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 79       | 1.02%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 72       | 0.93%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 71       | 0.92%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 68       | 0.88%   |
| Nvidia GK107 HDMI Audio Controller                                         | 66       | 0.86%   |
| Nvidia GA106 High Definition Audio Controller                              | 66       | 0.86%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 63       | 0.82%   |
| Nvidia GF119 HDMI Audio Controller                                         | 59       | 0.76%   |
| Nvidia TU106 High Definition Audio Controller                              | 57       | 0.74%   |
| Nvidia GP108 High Definition Audio Controller                              | 56       | 0.73%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 53       | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 381      | 18.07%  |
| Corsair                      | 314      | 14.89%  |
| Samsung Electronics          | 230      | 10.91%  |
| SK hynix                     | 208      | 9.86%   |
| G.Skill                      | 175      | 8.3%    |
| Crucial                      | 169      | 8.01%   |
| Unknown                      | 163      | 7.73%   |
| Micron Technology            | 113      | 5.36%   |
| A-DATA Technology            | 57       | 2.7%    |
| Team                         | 37       | 1.75%   |
| Unknown                      | 33       | 1.56%   |
| Patriot                      | 23       | 1.09%   |
| Ramaxel Technology           | 19       | 0.9%    |
| Nanya Technology             | 17       | 0.81%   |
| Unknown (ABCD)               | 12       | 0.57%   |
| Elpida                       | 9        | 0.43%   |
| Transcend                    | 8        | 0.38%   |
| Smart                        | 8        | 0.38%   |
| Apacer                       | 8        | 0.38%   |
| AMD                          | 8        | 0.38%   |
| PNY                          | 7        | 0.33%   |
| GOODRAM                      | 6        | 0.28%   |
| ASint Technology             | 6        | 0.28%   |
| Silicon Power                | 5        | 0.24%   |
| Hewlett-Packard              | 5        | 0.24%   |
| Timetec                      | 4        | 0.19%   |
| KETECH                       | 4        | 0.19%   |
| Innodisk                     | 4        | 0.19%   |
| GeIL                         | 4        | 0.19%   |
| Avant                        | 4        | 0.19%   |
| Asgard                       | 4        | 0.19%   |
| Patriot Memory (PDP Systems) | 3        | 0.14%   |
| Lexar                        | 3        | 0.14%   |
| KLEVV                        | 3        | 0.14%   |
| Kingmax                      | 3        | 0.14%   |
| Hikvision                    | 3        | 0.14%   |
| Atermiter                    | 3        | 0.14%   |
| Unknown (0x0C97)             | 2        | 0.09%   |
| Super Talent                 | 2        | 0.09%   |
| Qumo                         | 2        | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown                                                        | 33       | 1.45%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s          | 22       | 0.97%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s          | 20       | 0.88%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s            | 15       | 0.66%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s           | 15       | 0.66%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s                    | 15       | 0.66%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s            | 13       | 0.57%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s         | 13       | 0.57%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM LPDDR4 2400MT/s | 12       | 0.53%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s             | 12       | 0.53%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s            | 12       | 0.53%   |
| Kingston RAM 9905734-415.A00G 16GB DIMM DDR4 3200MT/s          | 12       | 0.53%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s         | 12       | 0.53%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 11       | 0.48%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s           | 11       | 0.48%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s           | 11       | 0.48%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 10       | 0.44%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s          | 10       | 0.44%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 9        | 0.4%    |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s           | 9        | 0.4%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 9        | 0.4%    |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s            | 9        | 0.4%    |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s              | 9        | 0.4%    |
| Kingston RAM 9905734-016.A00G 16GB DIMM DDR4 3200MT/s          | 9        | 0.4%    |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3800MT/s         | 9        | 0.4%    |
| Unknown RAM Module 4GB DIMM 1600MT/s                           | 8        | 0.35%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s            | 8        | 0.35%   |
| Corsair RAM CM4X16GC3000C16K4D 16GB DIMM DDR4 3000MT/s         | 8        | 0.35%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 7        | 0.31%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s           | 7        | 0.31%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s            | 7        | 0.31%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s            | 7        | 0.31%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s            | 7        | 0.31%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3933MT/s          | 7        | 0.31%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s         | 7        | 0.31%   |
| Corsair RAM CMK16GX4M2E3200C16 8GB DIMM DDR4 3200MT/s          | 7        | 0.31%   |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4 3600MT/s          | 7        | 0.31%   |
| A-DATA RAM DDR4 3000 8GB DIMM DDR4 3600MT/s                    | 7        | 0.31%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                           | 6        | 0.26%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 6        | 0.26%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind         | Desktops | Percent |
|--------------|----------|---------|
| DDR4         | 999      | 53.22%  |
| DDR3         | 586      | 31.22%  |
| DDR5         | 83       | 4.42%   |
| Unknown      | 66       | 3.52%   |
| SDRAM        | 55       | 2.93%   |
| DDR2         | 44       | 2.34%   |
| LPDDR4       | 22       | 1.17%   |
| DDR          | 13       | 0.69%   |
| LPDDR3       | 4        | 0.21%   |
| DRAM         | 3        | 0.16%   |
| LPDDR5       | 1        | 0.05%   |
| DDR2 FB-DIMM | 1        | 0.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 1673     | 90.63%  |
| SODIMM       | 151      | 8.18%   |
| Row Of Chips | 9        | 0.49%   |
| RIMM         | 9        | 0.49%   |
| FB-DIMM      | 3        | 0.16%   |
| Unknown      | 1        | 0.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size   | Desktops | Percent |
|--------|----------|---------|
| 8192   | 731      | 36.75%  |
| 16384  | 434      | 21.82%  |
| 4096   | 424      | 21.32%  |
| 2048   | 186      | 9.35%   |
| 32768  | 177      | 8.9%    |
| 1024   | 30       | 1.51%   |
| 65536  | 4        | 0.2%    |
| 512    | 2        | 0.1%    |
| 131072 | 1        | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 354      | 17.13%  |
| 3200    | 270      | 13.07%  |
| 1333    | 188      | 9.1%    |
| 2400    | 158      | 7.65%   |
| 3600    | 149      | 7.21%   |
| 2667    | 138      | 6.68%   |
| 2133    | 86       | 4.16%   |
| 3000    | 50       | 2.42%   |
| 1867    | 49       | 2.37%   |
| 800     | 45       | 2.18%   |
| 4800    | 37       | 1.79%   |
| 2666    | 37       | 1.79%   |
| 2933    | 30       | 1.45%   |
| 1800    | 30       | 1.45%   |
| 3800    | 29       | 1.4%    |
| 667     | 28       | 1.36%   |
| 3400    | 25       | 1.21%   |
| 3533    | 23       | 1.11%   |
| 3733    | 22       | 1.06%   |
| 1866    | 20       | 0.97%   |
| 1066    | 18       | 0.87%   |
| Unknown | 16       | 0.77%   |
| 3266    | 14       | 0.68%   |
| 3534    | 13       | 0.63%   |
| 3466    | 13       | 0.63%   |
| 3666    | 12       | 0.58%   |
| 1067    | 12       | 0.58%   |
| 5200    | 11       | 0.53%   |
| 2800    | 10       | 0.48%   |
| 5600    | 9        | 0.44%   |
| 3500    | 9        | 0.44%   |
| 3866    | 8        | 0.39%   |
| 2000    | 8        | 0.39%   |
| 1648    | 8        | 0.39%   |
| 1334    | 8        | 0.39%   |
| 400     | 8        | 0.39%   |
| 6400    | 7        | 0.34%   |
| 6000    | 7        | 0.34%   |
| 3933    | 7        | 0.34%   |
| 5808    | 6        | 0.29%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Hewlett-Packard        | 66       | 33.5%   |
| Brother Industries     | 45       | 22.84%  |
| Canon                  | 24       | 12.18%  |
| Samsung Electronics    | 20       | 10.15%  |
| Seiko Epson            | 19       | 9.64%   |
| Dymo-CoStar            | 4        | 2.03%   |
| Prolific Technology    | 3        | 1.52%   |
| Lexmark International  | 3        | 1.52%   |
| STMicroelectronics     | 2        | 1.02%   |
| QinHeng Electronics    | 2        | 1.02%   |
| Kyocera                | 2        | 1.02%   |
| Zebra                  | 1        | 0.51%   |
| Pantum                 | 1        | 0.51%   |
| Oki Data               | 1        | 0.51%   |
| Fuji Xerox             | 1        | 0.51%   |
| Custom Engineering SPA | 1        | 0.51%   |
| BESTEASY               | 1        | 0.51%   |
| Apple                  | 1        | 0.51%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| HP DeskJet 2130 series                                    | 5        | 2.49%   |
| Seiko Epson L360 Series                                   | 3        | 1.49%   |
| Seiko Epson ET-2720 Series                                | 3        | 1.49%   |
| Samsung Composite Device                                  | 3        | 1.49%   |
| Prolific PL2305 Parallel Port                             | 3        | 1.49%   |
| HP OfficeJet 3830 series                                  | 3        | 1.49%   |
| Dymo-CoStar LabelWriter 400                               | 3        | 1.49%   |
| Brother Printer                                           | 3        | 1.49%   |
| Brother HL-L2350DW series                                 | 3        | 1.49%   |
| Brother HL-1440 Laser Printer                             | 3        | 1.49%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 2        | 1%      |
| Seiko Epson XP-2100 Series                                | 2        | 1%      |
| Seiko Epson ET-2810 Series                                | 2        | 1%      |
| Samsung ML-216x Series Laser Printer                      | 2        | 1%      |
| Samsung M2070 Series                                      | 2        | 1%      |
| Samsung C460 Series                                       | 2        | 1%      |
| QinHeng CH340S                                            | 2        | 1%      |
| HP OfficeJet Pro 8020 series                              | 2        | 1%      |
| HP OfficeJet 5600 (USBHUB)                                | 2        | 1%      |
| HP Officejet 4500 G510n-z                                 | 2        | 1%      |
| HP LaserJet P1005                                         | 2        | 1%      |
| HP LaserJet M203-M206                                     | 2        | 1%      |
| HP LaserJet M14-M17                                       | 2        | 1%      |
| HP LaserJet 4250                                          | 2        | 1%      |
| HP LaserJet 3015                                          | 2        | 1%      |
| HP ENVY 4520 series                                       | 2        | 1%      |
| HP DeskJet 4100 series                                    | 2        | 1%      |
| HP DeskJet 3700 series                                    | 2        | 1%      |
| HP DeskJet 3630 series                                    | 2        | 1%      |
| HP DeskJet 2600 series                                    | 2        | 1%      |
| HP DeskJet 2300 series                                    | 2        | 1%      |
| HP DeskJet 1110 series                                    | 2        | 1%      |
| Canon TS3100 series                                       | 2        | 1%      |
| Canon PIXMA MG2500 Series                                 | 2        | 1%      |
| Canon LBP2900                                             | 2        | 1%      |
| Brother HL-L2375DW series                                 | 2        | 1%      |
| Brother HL-2270DW Laser Printer                           | 2        | 1%      |
| Brother DCP-J105                                          | 2        | 1%      |
| Brother DCP-7055 scanner/printer                          | 2        | 1%      |
| Brother DCP-1610W                                         | 2        | 1%      |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Canon                       | 19       | 57.58%  |
| Seiko Epson                 | 7        | 21.21%  |
| Hewlett-Packard             | 6        | 18.18%  |
| Acer Peripherals (now BenQ) | 1        | 3.03%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 120                                  | 5        | 15.15%  |
| Canon CanoScan LiDE 100                                  | 3        | 9.09%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]      | 2        | 6.06%   |
| Canon CanoScan LiDE 220                                  | 2        | 6.06%   |
| Canon CanoScan LiDE 110                                  | 2        | 6.06%   |
| Seiko Epson GT-X770 [Perfection V500]                    | 1        | 3.03%   |
| Seiko Epson GT-F700 [Perfection V350]                    | 1        | 3.03%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1        | 3.03%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]       | 1        | 3.03%   |
| Seiko Epson GT-7700U [Perfection 1240U]                  | 1        | 3.03%   |
| HP Scanjet N6010                                         | 1        | 3.03%   |
| HP ScanJet G4010                                         | 1        | 3.03%   |
| HP Scanjet G2710                                         | 1        | 3.03%   |
| HP ScanJet 4850C/4890C                                   | 1        | 3.03%   |
| HP ScanJet 3970c                                         | 1        | 3.03%   |
| HP ScanJet 3400cse                                       | 1        | 3.03%   |
| Canon CanoScan N670U/N676U/LiDE 20                       | 1        | 3.03%   |
| Canon CanoScan N1240U/LiDE 30                            | 1        | 3.03%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                   | 1        | 3.03%   |
| Canon CanoScan LIDE 25                                   | 1        | 3.03%   |
| Canon CanoScan LiDE 200                                  | 1        | 3.03%   |
| Canon CanoScan 9000F Mark II                             | 1        | 3.03%   |
| Canon CanoScan 4200F                                     | 1        | 3.03%   |
| Acer Peripherals (now BenQ) Benq 5000                    | 1        | 3.03%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 265      | 35.24%  |
| Microdia                      | 68       | 9.04%   |
| Microsoft                     | 50       | 6.65%   |
| Sunplus Innovation Technology | 31       | 4.12%   |
| Apple                         | 28       | 3.72%   |
| Samsung Electronics           | 24       | 3.19%   |
| Generalplus Technology        | 23       | 3.06%   |
| ARC International             | 21       | 2.79%   |
| Realtek Semiconductor         | 19       | 2.53%   |
| Chicony Electronics           | 18       | 2.39%   |
| Z-Star Microelectronics       | 17       | 2.26%   |
| webcamvendor                  | 11       | 1.46%   |
| Trust                         | 9        | 1.2%    |
| Creative Technology           | 9        | 1.2%    |
| Cubeternet                    | 8        | 1.06%   |
| MacroSilicon                  | 7        | 0.93%   |
| Razer USA                     | 6        | 0.8%    |
| KYE Systems (Mouse Systems)   | 6        | 0.8%    |
| GEMBIRD                       | 6        | 0.8%    |
| WaveRider Communications      | 5        | 0.66%   |
| Sonix Technology              | 5        | 0.66%   |
| Jieli Technology              | 5        | 0.66%   |
| Hewlett-Packard               | 5        | 0.66%   |
| AVerMedia Technologies        | 5        | 0.66%   |
| Philips (or NXP)              | 4        | 0.53%   |
| Linux Foundation              | 4        | 0.53%   |
| Genesys Logic                 | 4        | 0.53%   |
| Aveo Technology               | 4        | 0.53%   |
| OPPO Electronics              | 3        | 0.4%    |
| IMC Networks                  | 3        | 0.4%    |
| Huawei Technologies           | 3        | 0.4%    |
| Fifine K420                   | 3        | 0.4%    |
| Asuscom Network               | 3        | 0.4%    |
| Arkmicro Technologies         | 3        | 0.4%    |
| Alcor Micro                   | 3        | 0.4%    |
| Sunplus IT                    | 2        | 0.27%   |
| Silicon Motion                | 2        | 0.27%   |
| SHENZHEN EMEET TECHNOLOGY     | 2        | 0.27%   |
| Quanta                        | 2        | 0.27%   |
| Pixart Imaging                | 2        | 0.27%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech Webcam C270                    | 65       | 8.62%   |
| Logitech HD Pro Webcam C920             | 53       | 7.03%   |
| Logitech C922 Pro Stream Webcam         | 26       | 3.45%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR      | 25       | 3.32%   |
| Samsung Galaxy series, misc. (MTP mode) | 23       | 3.05%   |
| ARC International Camera                | 21       | 2.79%   |
| Microdia Webcam Vitade AF               | 20       | 2.65%   |
| Microdia USB 2.0 Camera                 | 16       | 2.12%   |
| Microsoft LifeCam HD-3000               | 13       | 1.72%   |
| Logitech HD Webcam C615                 | 13       | 1.72%   |
| Generalplus CAMERA - UVC                | 13       | 1.72%   |
| webcamvendor webcamproduct              | 10       | 1.33%   |
| Logitech Webcam C170                    | 10       | 1.33%   |
| Logitech BRIO                           | 10       | 1.33%   |
| Sunplus Integrated_Webcam_HD            | 9        | 1.19%   |
| Microsoft LifeCam Cinema                | 9        | 1.19%   |
| Microdia Sonix USB 2.0 Camera           | 9        | 1.19%   |
| Logitech Webcam C310                    | 9        | 1.19%   |
| Microdia Camera                         | 8        | 1.06%   |
| Logitech HD Webcam C525                 | 8        | 1.06%   |
| Sunplus Full HD webcam                  | 6        | 0.8%    |
| Microdia Integrated Camera              | 6        | 0.8%    |
| MacroSilicon USB3. 0 capture            | 6        | 0.8%    |
| Logitech StreamCam                      | 6        | 0.8%    |
| Generalplus 808 Camera                  | 6        | 0.8%    |
| Chicony HP High Definition 1MP Webcam   | 6        | 0.8%    |
| Z-Star Venus USB2.0 Camera              | 5        | 0.66%   |
| Realtek USB Camera                      | 5        | 0.66%   |
| Realtek Full HD webcam                  | 5        | 0.66%   |
| Logitech Webcam C925e                   | 5        | 0.66%   |
| Logitech HD Webcam C910                 | 5        | 0.66%   |
| Jieli USB PHY 2.0                       | 5        | 0.66%   |
| Chicony Integrated Camera               | 5        | 0.66%   |
| Razer USA Gaming Webcam [Kiyo]          | 4        | 0.53%   |
| Microsoft LifeCam VX-500 [1357]         | 4        | 0.53%   |
| Microsoft LifeCam Studio                | 4        | 0.53%   |
| Logitech Webcam C930e                   | 4        | 0.53%   |
| Logitech Webcam C250                    | 4        | 0.53%   |
| Logitech QuickCam Pro 9000              | 4        | 0.53%   |
| Logitech QuickCam Pro 5000              | 4        | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Dell                  | 2        | 40%     |
| Microsoft             | 1        | 20%     |
| Elan Microelectronics | 1        | 20%     |
| DigitalPersona        | 1        | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Dell MS819 Wired Mouse With Fingerprint Reader | 2        | 40%     |
| Microsoft Fingerprint Reader                   | 1        | 20%     |
| Elan fingerprint sensor [FeinTech FPS00200]    | 1        | 20%     |
| DigitalPersona Fingerprint Reader              | 1        | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Advanced Card Systems     | 8        | 24.24%  |
| Realtek Semiconductor     | 4        | 12.12%  |
| Gemalto (was Gemplus)     | 4        | 12.12%  |
| Alcor Micro               | 4        | 12.12%  |
| SCM Microsystems          | 3        | 9.09%   |
| Chicony Electronics       | 3        | 9.09%   |
| Reiner SCT Kartensysteme  | 1        | 3.03%   |
| Lenovo                    | 1        | 3.03%   |
| Giesecke & Devrient       | 1        | 3.03%   |
| Fujitsu Siemens Computers | 1        | 3.03%   |
| Cherry                    | 1        | 3.03%   |
| BIT4ID                    | 1        | 3.03%   |
| Aladdin Knowledge Systems | 1        | 3.03%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek Semiconductor Smart Card Reader Interface                          | 4        | 12.12%  |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                          | 4        | 12.12%  |
| Advanced Card Systems ACR38 SmartCard Reader                               | 4        | 12.12%  |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                     | 3        | 9.09%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                       | 3        | 9.09%   |
| Alcor Micro AU9540 Smartcard Reader                                        | 3        | 9.09%   |
| Advanced Card Systems ACR122U                                              | 2        | 6.06%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 1        | 3.03%   |
| Lenovo Smartcard Keyboard                                                  | 1        | 3.03%   |
| Giesecke & Devrient StarSign CUT S                                         | 1        | 3.03%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                              | 1        | 3.03%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                | 1        | 3.03%   |
| BIT4ID miniLector EVO                                                      | 1        | 3.03%   |
| Alcor Micro Watchdata W 1981                                               | 1        | 3.03%   |
| Aladdin Knowledge Systems Token JC                                         | 1        | 3.03%   |
| Advanced Card Systems ACR39U                                               | 1        | 3.03%   |
| Advanced Card Systems ACR1281 1S Dual Reader                               | 1        | 3.03%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 3350     | 81.99%  |
| 1     | 607      | 14.86%  |
| 2     | 73       | 1.79%   |
| 3     | 26       | 0.64%   |
| 4     | 14       | 0.34%   |
| 5     | 10       | 0.24%   |
| 6     | 3        | 0.07%   |
| 8     | 2        | 0.05%   |
| 7     | 1        | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 325      | 36.39%  |
| Net/wireless             | 192      | 21.5%   |
| Unassigned class         | 96       | 10.75%  |
| Communication controller | 71       | 7.95%   |
| Sound                    | 55       | 6.16%   |
| Camera                   | 22       | 2.46%   |
| Chipcard                 | 21       | 2.35%   |
| Bluetooth                | 20       | 2.24%   |
| Net/ethernet             | 18       | 2.02%   |
| Multimedia controller    | 18       | 2.02%   |
| Storage/raid             | 17       | 1.9%    |
| Network                  | 10       | 1.12%   |
| Card reader              | 6        | 0.67%   |
| Dvb card                 | 5        | 0.56%   |
| Storage/nvme             | 3        | 0.34%   |
| Storage/ata              | 3        | 0.34%   |
| Modem                    | 3        | 0.34%   |
| Fingerprint reader       | 3        | 0.34%   |
| Tv card                  | 2        | 0.22%   |
| Firewire controller      | 2        | 0.22%   |
| Wireless                 | 1        | 0.11%   |

