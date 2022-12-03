Debian 11 - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for Debian 11.

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

Total: 2411

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | SHARKBAY NOK                | [e03c6b53ed](https://linux-hardware.org/?probe=e03c6b53ed) | Dec 01, 2022 |
| ASUSTek       | P5B                         | [44f13beada](https://linux-hardware.org/?probe=44f13beada) | Dec 01, 2022 |
| Gigabyte      | Z390 M GAMING-CF            | [f0dba35258](https://linux-hardware.org/?probe=f0dba35258) | Dec 01, 2022 |
| Gigabyte      | Z390 M GAMING-CF            | [baa969bf8b](https://linux-hardware.org/?probe=baa969bf8b) | Nov 30, 2022 |
| Pegatron      | BYT-X1                      | [edadb85201](https://linux-hardware.org/?probe=edadb85201) | Nov 30, 2022 |
| Pegatron      | BYT-X1                      | [b248df8671](https://linux-hardware.org/?probe=b248df8671) | Nov 30, 2022 |
| ASUSTek       | ROG STRIX Z490-A GAMING     | [dc5ec6eb84](https://linux-hardware.org/?probe=dc5ec6eb84) | Nov 30, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [6b21f343c3](https://linux-hardware.org/?probe=6b21f343c3) | Nov 30, 2022 |
| Gigabyte      | B450M DS3H-CF               | [952c3681c0](https://linux-hardware.org/?probe=952c3681c0) | Nov 30, 2022 |
| Gigabyte      | B450 AORUS M                | [3e3ccd1471](https://linux-hardware.org/?probe=3e3ccd1471) | Nov 30, 2022 |
| MSI           | B560M-A PRO                 | [81bf84e7e5](https://linux-hardware.org/?probe=81bf84e7e5) | Nov 29, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [9dd6019148](https://linux-hardware.org/?probe=9dd6019148) | Nov 29, 2022 |
| BESSTAR Te... | UM700                       | [a97334be81](https://linux-hardware.org/?probe=a97334be81) | Nov 29, 2022 |
| Gigabyte      | B450M DS3H-CF               | [eae94e440a](https://linux-hardware.org/?probe=eae94e440a) | Nov 29, 2022 |
| ASUSTek       | P5KPL-CM                    | [a20e18af73](https://linux-hardware.org/?probe=a20e18af73) | Nov 29, 2022 |
| ASRock        | H510M-HDV                   | [03a1675c85](https://linux-hardware.org/?probe=03a1675c85) | Nov 29, 2022 |
| Gigabyte      | F2A55M-HD2                  | [8b3da34947](https://linux-hardware.org/?probe=8b3da34947) | Nov 28, 2022 |
| ASRock        | B450M Pro4-F                | [8d0514a0df](https://linux-hardware.org/?probe=8d0514a0df) | Nov 28, 2022 |
| ECS           | H61H2-M13                   | [88988d4d0d](https://linux-hardware.org/?probe=88988d4d0d) | Nov 28, 2022 |
| Dell          | 0K3CM7 A00                  | [076eeadd80](https://linux-hardware.org/?probe=076eeadd80) | Nov 28, 2022 |
| HP            | 212B                        | [53471968c2](https://linux-hardware.org/?probe=53471968c2) | Nov 28, 2022 |
| Dell          | 05XGC8 A00                  | [e0e0efb9be](https://linux-hardware.org/?probe=e0e0efb9be) | Nov 27, 2022 |
| Dell          | 0D24M8 A00                  | [c58c83e367](https://linux-hardware.org/?probe=c58c83e367) | Nov 26, 2022 |
| Dell          | 0D24M8 A00                  | [85b508d6d3](https://linux-hardware.org/?probe=85b508d6d3) | Nov 26, 2022 |
| Dell          | 05XGC8 A00                  | [6ea1a60122](https://linux-hardware.org/?probe=6ea1a60122) | Nov 26, 2022 |
| Gigabyte      | B250-FinTech-CF             | [fcc81ea02b](https://linux-hardware.org/?probe=fcc81ea02b) | Nov 24, 2022 |
| ASUSTek       | P5Q3                        | [655065ee03](https://linux-hardware.org/?probe=655065ee03) | Nov 24, 2022 |
| Lenovo        | 312A NOK                    | [94cdaff2c9](https://linux-hardware.org/?probe=94cdaff2c9) | Nov 24, 2022 |
| Gigabyte      | 990FXA-UD3                  | [38aca80776](https://linux-hardware.org/?probe=38aca80776) | Nov 24, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [c0ce9a3ff3](https://linux-hardware.org/?probe=c0ce9a3ff3) | Nov 23, 2022 |
| MSI           | MAG B550 TORPEDO            | [ca3bcfa403](https://linux-hardware.org/?probe=ca3bcfa403) | Nov 23, 2022 |
| Gigabyte      | G31M-ES2L                   | [e8ab5ad410](https://linux-hardware.org/?probe=e8ab5ad410) | Nov 23, 2022 |
| ASRock        | H410M-HVS R2.0              | [3f381f9fa3](https://linux-hardware.org/?probe=3f381f9fa3) | Nov 23, 2022 |
| ASUSTek       | PRIME Z270-P                | [0e778da8b6](https://linux-hardware.org/?probe=0e778da8b6) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | [6d50058ef8](https://linux-hardware.org/?probe=6d50058ef8) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | [f6a783a27a](https://linux-hardware.org/?probe=f6a783a27a) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | [423fbc1fa0](https://linux-hardware.org/?probe=423fbc1fa0) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | [debc5b7ab9](https://linux-hardware.org/?probe=debc5b7ab9) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | [dc53077baa](https://linux-hardware.org/?probe=dc53077baa) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | [856bb3def2](https://linux-hardware.org/?probe=856bb3def2) | Nov 22, 2022 |
| Foxconn       | H61MXL/H61MXL-K             | [d140a0f503](https://linux-hardware.org/?probe=d140a0f503) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | [ee55108218](https://linux-hardware.org/?probe=ee55108218) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | [ec03d1b050](https://linux-hardware.org/?probe=ec03d1b050) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | [1f2a4089cc](https://linux-hardware.org/?probe=1f2a4089cc) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | [4190bbb2d8](https://linux-hardware.org/?probe=4190bbb2d8) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | [570a11d74b](https://linux-hardware.org/?probe=570a11d74b) | Nov 22, 2022 |
| Gigabyte      | G41M-ES2L                   | [404927f4cc](https://linux-hardware.org/?probe=404927f4cc) | Nov 22, 2022 |
| ASUSTek       | M4A78T-E                    | [aef32a0e69](https://linux-hardware.org/?probe=aef32a0e69) | Nov 22, 2022 |
| Dell          | 05DN3X A00                  | [f15eef78fa](https://linux-hardware.org/?probe=f15eef78fa) | Nov 22, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [dba99c363e](https://linux-hardware.org/?probe=dba99c363e) | Nov 20, 2022 |
| Intel         | JSL MRD                     | [469567b71f](https://linux-hardware.org/?probe=469567b71f) | Nov 20, 2022 |
| Dell          | 0WPMFG A00                  | [8b3a3dc37f](https://linux-hardware.org/?probe=8b3a3dc37f) | Nov 20, 2022 |
| Acer          | Nitro N50-620               | [ecd8e9ec1b](https://linux-hardware.org/?probe=ecd8e9ec1b) | Nov 20, 2022 |
| Intel         | JSL MRD                     | [e8171566d3](https://linux-hardware.org/?probe=e8171566d3) | Nov 19, 2022 |
| Gigabyte      | G31M-ES2L                   | [3e3d8f727c](https://linux-hardware.org/?probe=3e3d8f727c) | Nov 19, 2022 |
| Dell          | 02YRK5 A02                  | [da08e08dec](https://linux-hardware.org/?probe=da08e08dec) | Nov 18, 2022 |
| MSI           | H510M-A PRO                 | [e913feb821](https://linux-hardware.org/?probe=e913feb821) | Nov 18, 2022 |
| MSI           | MAG B550M MORTAR            | [57c6327e27](https://linux-hardware.org/?probe=57c6327e27) | Nov 18, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d1d9ddf9f3](https://linux-hardware.org/?probe=d1d9ddf9f3) | Nov 18, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [da04bee118](https://linux-hardware.org/?probe=da04bee118) | Nov 18, 2022 |
| ASUSTek       | PRIME Z690-A                | [06a234be2c](https://linux-hardware.org/?probe=06a234be2c) | Nov 17, 2022 |
| ASUSTek       | P6T DELUXE V2               | [550bd99088](https://linux-hardware.org/?probe=550bd99088) | Nov 17, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [b3e809f3d2](https://linux-hardware.org/?probe=b3e809f3d2) | Nov 17, 2022 |
| Dell          | 09KPNV A01                  | [b21e07c887](https://linux-hardware.org/?probe=b21e07c887) | Nov 16, 2022 |
| GuoGuang      | IC2M1028N-3                 | [32351ceb62](https://linux-hardware.org/?probe=32351ceb62) | Nov 16, 2022 |
| Gigabyte      | H61M-DS2                    | [757a1066ff](https://linux-hardware.org/?probe=757a1066ff) | Nov 16, 2022 |
| ASUSTek       | P8Z68-V LX                  | [a3c41dcc96](https://linux-hardware.org/?probe=a3c41dcc96) | Nov 16, 2022 |
| Gigabyte      | P75-D3                      | [02bdf99508](https://linux-hardware.org/?probe=02bdf99508) | Nov 16, 2022 |
| ASRock        | J3455-ITX                   | [71c99edeb1](https://linux-hardware.org/?probe=71c99edeb1) | Nov 16, 2022 |
| ASRock        | FM2A68M-HD+                 | [e907b4c718](https://linux-hardware.org/?probe=e907b4c718) | Nov 15, 2022 |
| Gigabyte      | A320M-S2H-CF                | [c3cacc3ed6](https://linux-hardware.org/?probe=c3cacc3ed6) | Nov 15, 2022 |
| Gigabyte      | GA-78LMT-S2P                | [ee8a80240d](https://linux-hardware.org/?probe=ee8a80240d) | Nov 15, 2022 |
| ASRock        | B450M-HDV R4.0              | [a46c1d62cf](https://linux-hardware.org/?probe=a46c1d62cf) | Nov 15, 2022 |
| ASRock        | H470M-HVS                   | [e69c2f0da4](https://linux-hardware.org/?probe=e69c2f0da4) | Nov 15, 2022 |
| Intel         | DH77KC AAG39641-400         | [137906fffe](https://linux-hardware.org/?probe=137906fffe) | Nov 15, 2022 |
| ASUSTek       | B85M-G                      | [2029195495](https://linux-hardware.org/?probe=2029195495) | Nov 14, 2022 |
| Lenovo        | ThinkServer TS440           | [9fe9bc94a0](https://linux-hardware.org/?probe=9fe9bc94a0) | Nov 14, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [28df02c741](https://linux-hardware.org/?probe=28df02c741) | Nov 14, 2022 |
| Gigabyte      | P75-D3                      | [37f9da1b7f](https://linux-hardware.org/?probe=37f9da1b7f) | Nov 14, 2022 |
| ASUSTek       | B85M-G                      | [277739769b](https://linux-hardware.org/?probe=277739769b) | Nov 14, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [53a532435e](https://linux-hardware.org/?probe=53a532435e) | Nov 14, 2022 |
| ASUSTek       | PRIME H310M-A R2.0          | [80cce966ce](https://linux-hardware.org/?probe=80cce966ce) | Nov 14, 2022 |
| Gigabyte      | A320M-H-CF                  | [2a6473f450](https://linux-hardware.org/?probe=2a6473f450) | Nov 13, 2022 |
| ASUSTek       | H81M-K                      | [d7ae86ad73](https://linux-hardware.org/?probe=d7ae86ad73) | Nov 13, 2022 |
| Gigabyte      | GA-MA770-UD3                | [d31168230f](https://linux-hardware.org/?probe=d31168230f) | Nov 13, 2022 |
| ASUSTek       | PRIME H310M-A R2.0          | [4788a2a91d](https://linux-hardware.org/?probe=4788a2a91d) | Nov 13, 2022 |
| Gigabyte      | Z590 UD AC                  | [57952c1512](https://linux-hardware.org/?probe=57952c1512) | Nov 13, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [dc2a41e0ee](https://linux-hardware.org/?probe=dc2a41e0ee) | Nov 12, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [e69a98ce67](https://linux-hardware.org/?probe=e69a98ce67) | Nov 11, 2022 |
| ASRock        | H470M-HVS                   | [b81b19a472](https://linux-hardware.org/?probe=b81b19a472) | Nov 11, 2022 |
| Gigabyte      | H61M-D2-B3                  | [46ee069dd8](https://linux-hardware.org/?probe=46ee069dd8) | Nov 11, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [524b1115eb](https://linux-hardware.org/?probe=524b1115eb) | Nov 11, 2022 |
| Apple         | Mac-F4208DC8 PVT            | [45dc316bea](https://linux-hardware.org/?probe=45dc316bea) | Nov 10, 2022 |
| ASUSTek       | M4A78T-E                    | [a885b61478](https://linux-hardware.org/?probe=a885b61478) | Nov 10, 2022 |
| ASUSTek       | M4A78T-E                    | [475ad820cd](https://linux-hardware.org/?probe=475ad820cd) | Nov 10, 2022 |
| Gigabyte      | B75M-D3H                    | [6dd51f8707](https://linux-hardware.org/?probe=6dd51f8707) | Nov 10, 2022 |
| Gigabyte      | X570 UD                     | [29641e8b7c](https://linux-hardware.org/?probe=29641e8b7c) | Nov 09, 2022 |
| ASUSTek       | A88XM-PLUS                  | [e6eee311ea](https://linux-hardware.org/?probe=e6eee311ea) | Nov 08, 2022 |
| ASRock        | FM2A68M-HD+                 | [a90c14df17](https://linux-hardware.org/?probe=a90c14df17) | Nov 08, 2022 |
| ASUSTek       | H110-PLUS                   | [4d260267d7](https://linux-hardware.org/?probe=4d260267d7) | Nov 06, 2022 |
| ASUSTek       | H110-PLUS                   | [789df18cfb](https://linux-hardware.org/?probe=789df18cfb) | Nov 06, 2022 |
| Intel         | DQ67SW AAG12527-310         | [97d0b022d2](https://linux-hardware.org/?probe=97d0b022d2) | Nov 05, 2022 |
| Foxconn       | A88GMV                      | [1391b33f62](https://linux-hardware.org/?probe=1391b33f62) | Nov 05, 2022 |
| ASUSTek       | X99-DELUXE                  | [ab4089c760](https://linux-hardware.org/?probe=ab4089c760) | Nov 04, 2022 |
| ASUSTek       | X99-E WS/USB                | [7a65820be2](https://linux-hardware.org/?probe=7a65820be2) | Nov 04, 2022 |
| Dell          | 0200DY A01                  | [a473b71b4e](https://linux-hardware.org/?probe=a473b71b4e) | Nov 03, 2022 |
| MSI           | H510M PRO-E                 | [23fa7a2cf8](https://linux-hardware.org/?probe=23fa7a2cf8) | Nov 03, 2022 |
| Foxconn       | 2A92                        | [927cf971e9](https://linux-hardware.org/?probe=927cf971e9) | Nov 02, 2022 |
| Gigabyte      | B560M DS3H V2               | [36612b5e01](https://linux-hardware.org/?probe=36612b5e01) | Nov 02, 2022 |
| Shenzhen a... | AC1-DP                      | [754335ffe9](https://linux-hardware.org/?probe=754335ffe9) | Nov 02, 2022 |
| Dell          | 0JGM7F A00                  | [28f4800b2b](https://linux-hardware.org/?probe=28f4800b2b) | Nov 02, 2022 |
| MSI           | H110M PRO-VD                | [1fb0a79791](https://linux-hardware.org/?probe=1fb0a79791) | Nov 02, 2022 |
| Foxconn       | 2A92                        | [0898482b18](https://linux-hardware.org/?probe=0898482b18) | Nov 02, 2022 |
| ASUSTek       | PRO B460M-C                 | [dcf7112b3d](https://linux-hardware.org/?probe=dcf7112b3d) | Nov 01, 2022 |
| ASUSTek       | PRO B460M-C                 | [a333f47ffa](https://linux-hardware.org/?probe=a333f47ffa) | Nov 01, 2022 |
| Phoenix       | POULSBO                     | [177f05205b](https://linux-hardware.org/?probe=177f05205b) | Nov 01, 2022 |
| Gigabyte      | H610M H DDR4                | [b726668f90](https://linux-hardware.org/?probe=b726668f90) | Nov 01, 2022 |
| Gigabyte      | X570S AERO G                | [92fccb6716](https://linux-hardware.org/?probe=92fccb6716) | Nov 01, 2022 |
| MSI           | Z390-A PRO                  | [3eea020596](https://linux-hardware.org/?probe=3eea020596) | Nov 01, 2022 |
| MSI           | MEG Z590 ACE                | [1082f00d60](https://linux-hardware.org/?probe=1082f00d60) | Oct 31, 2022 |
| ASRock        | 960GM-VGS3 FX               | [f31f613901](https://linux-hardware.org/?probe=f31f613901) | Oct 31, 2022 |
| Intel         | DG41AN AAE92991-401         | [cd670cef3d](https://linux-hardware.org/?probe=cd670cef3d) | Oct 31, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | [4179fe16d6](https://linux-hardware.org/?probe=4179fe16d6) | Oct 31, 2022 |
| ASUSTek       | PRIME X570-PRO              | [3fbcca75d5](https://linux-hardware.org/?probe=3fbcca75d5) | Oct 30, 2022 |
| HP            | 158B                        | [9c02b7fe58](https://linux-hardware.org/?probe=9c02b7fe58) | Oct 30, 2022 |
| Foxconn       | 2ADA                        | [16815dacc1](https://linux-hardware.org/?probe=16815dacc1) | Oct 29, 2022 |
| Unknown       | 775V88+                     | [f1a685b497](https://linux-hardware.org/?probe=f1a685b497) | Oct 28, 2022 |
| HP            | 3396                        | [d42479acb8](https://linux-hardware.org/?probe=d42479acb8) | Oct 28, 2022 |
| ASUSTek       | PRIME X370-PRO              | [d3cf194e94](https://linux-hardware.org/?probe=d3cf194e94) | Oct 28, 2022 |
| Apple         | Mac-F221BEC8                | [0bf03c49f7](https://linux-hardware.org/?probe=0bf03c49f7) | Oct 27, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [b682a38061](https://linux-hardware.org/?probe=b682a38061) | Oct 27, 2022 |
| MSI           | H110M PRO-VD                | [175f39979c](https://linux-hardware.org/?probe=175f39979c) | Oct 27, 2022 |
| Gigabyte      | 970A-DS3P                   | [1bc5db124b](https://linux-hardware.org/?probe=1bc5db124b) | Oct 27, 2022 |
| Lenovo        | ThinkServer TS440           | [acdfb9b02e](https://linux-hardware.org/?probe=acdfb9b02e) | Oct 26, 2022 |
| ASUSTek       | B85M-G                      | [0d3545c6aa](https://linux-hardware.org/?probe=0d3545c6aa) | Oct 26, 2022 |
| ASUSTek       | B85M-G                      | [0b8dc998a9](https://linux-hardware.org/?probe=0b8dc998a9) | Oct 26, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [c1067e423b](https://linux-hardware.org/?probe=c1067e423b) | Oct 26, 2022 |
| MSI           | Z170A GAMING M5             | [b5dcdb6844](https://linux-hardware.org/?probe=b5dcdb6844) | Oct 25, 2022 |
| MSI           | H81M-P33                    | [b0f36ae0c5](https://linux-hardware.org/?probe=b0f36ae0c5) | Oct 25, 2022 |
| MSI           | H110M PRO-VD                | [f8466185a4](https://linux-hardware.org/?probe=f8466185a4) | Oct 25, 2022 |
| Dell          | 0YJPT1 A00                  | [bb1a7da646](https://linux-hardware.org/?probe=bb1a7da646) | Oct 25, 2022 |
| Dell          | 01XK1W A00                  | [c0fb49f07a](https://linux-hardware.org/?probe=c0fb49f07a) | Oct 25, 2022 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [54710cefe5](https://linux-hardware.org/?probe=54710cefe5) | Oct 24, 2022 |
| ASUSTek       | H81M-C                      | [1deed99314](https://linux-hardware.org/?probe=1deed99314) | Oct 24, 2022 |
| ASUSTek       | M4A78T-E                    | [ee86cdac2a](https://linux-hardware.org/?probe=ee86cdac2a) | Oct 24, 2022 |
| Dell          | 0M5WNK A00                  | [fad0f2f50e](https://linux-hardware.org/?probe=fad0f2f50e) | Oct 24, 2022 |
| Lenovo        | 0x36C017AA SDK0J40700 WI... | [0d21d658ee](https://linux-hardware.org/?probe=0d21d658ee) | Oct 24, 2022 |
| Inventec      | DQ Class A02                | [f64d3223c5](https://linux-hardware.org/?probe=f64d3223c5) | Oct 24, 2022 |
| Inventec      | DQ Class A02                | [c4fddde4b6](https://linux-hardware.org/?probe=c4fddde4b6) | Oct 24, 2022 |
| Dell          | 040DDP A01                  | [083b2c218e](https://linux-hardware.org/?probe=083b2c218e) | Oct 24, 2022 |
| Biostar       | B450MH                      | [048cd18957](https://linux-hardware.org/?probe=048cd18957) | Oct 24, 2022 |
| ASUSTek       | STRIX Z270F GAMING          | [ce3e956a0a](https://linux-hardware.org/?probe=ce3e956a0a) | Oct 24, 2022 |
| ASRock        | Z97 Anniversary             | [9c94714d56](https://linux-hardware.org/?probe=9c94714d56) | Oct 24, 2022 |
| Dell          | 01XK1W A00                  | [86e8f9141a](https://linux-hardware.org/?probe=86e8f9141a) | Oct 24, 2022 |
| Gigabyte      | G41MT-S2P                   | [9d2d49b8e4](https://linux-hardware.org/?probe=9d2d49b8e4) | Oct 23, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [50b6612f7d](https://linux-hardware.org/?probe=50b6612f7d) | Oct 23, 2022 |
| ASRock        | G31M-S                      | [5f1ca232ea](https://linux-hardware.org/?probe=5f1ca232ea) | Oct 23, 2022 |
| Dell          | 0YJPT1 A00                  | [678916671d](https://linux-hardware.org/?probe=678916671d) | Oct 23, 2022 |
| Unknown       | Unknown                     | [dcb8b694a7](https://linux-hardware.org/?probe=dcb8b694a7) | Oct 23, 2022 |
| ASRock        | FM2A68M-HD+                 | [1a49be478c](https://linux-hardware.org/?probe=1a49be478c) | Oct 22, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [168cbb8438](https://linux-hardware.org/?probe=168cbb8438) | Oct 21, 2022 |
| MSI           | H81M-P33                    | [efbd4959b8](https://linux-hardware.org/?probe=efbd4959b8) | Oct 21, 2022 |
| MSI           | H81M-P33                    | [a59f545a7b](https://linux-hardware.org/?probe=a59f545a7b) | Oct 21, 2022 |
| Gigabyte      | H61M-S2PV                   | [f60716afd0](https://linux-hardware.org/?probe=f60716afd0) | Oct 20, 2022 |
| ASRock        | Q1900-ITX                   | [c9d76cd138](https://linux-hardware.org/?probe=c9d76cd138) | Oct 20, 2022 |
| Gigabyte      | GA-6LXSV 00000001           | [ac15415eca](https://linux-hardware.org/?probe=ac15415eca) | Oct 20, 2022 |
| Dell          | 0D4MD1 A02                  | [becbded076](https://linux-hardware.org/?probe=becbded076) | Oct 20, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [e7875c59bc](https://linux-hardware.org/?probe=e7875c59bc) | Oct 20, 2022 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | [7799fd6266](https://linux-hardware.org/?probe=7799fd6266) | Oct 20, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [565e5d5e3b](https://linux-hardware.org/?probe=565e5d5e3b) | Oct 20, 2022 |
| Dell          | 0782GW A00                  | [d54932d557](https://linux-hardware.org/?probe=d54932d557) | Oct 19, 2022 |
| ASUSTek       | P9X79                       | [285e78cfbe](https://linux-hardware.org/?probe=285e78cfbe) | Oct 19, 2022 |
| HP            | 876C SMVB                   | [384313312d](https://linux-hardware.org/?probe=384313312d) | Oct 19, 2022 |
| MSI           | H81M-P33                    | [784b068521](https://linux-hardware.org/?probe=784b068521) | Oct 19, 2022 |
| ASUSTek       | B85M-G                      | [42a1bedb35](https://linux-hardware.org/?probe=42a1bedb35) | Oct 19, 2022 |
| HP            | 8061                        | [8692ad745b](https://linux-hardware.org/?probe=8692ad745b) | Oct 19, 2022 |
| ASUSTek       | P5G41T-M LX2/BR             | [46a99f3d0e](https://linux-hardware.org/?probe=46a99f3d0e) | Oct 18, 2022 |
| HP            | 0A58h                       | [4c8d533bb0](https://linux-hardware.org/?probe=4c8d533bb0) | Oct 18, 2022 |
| HP            | 3047h                       | [c1716b926a](https://linux-hardware.org/?probe=c1716b926a) | Oct 18, 2022 |
| Giga-Byte ... | i440BX-W977                 | [018daa60e1](https://linux-hardware.org/?probe=018daa60e1) | Oct 18, 2022 |
| ASUSTek       | B85M-G                      | [86b92cdc50](https://linux-hardware.org/?probe=86b92cdc50) | Oct 18, 2022 |
| Dell          | 0DFRFW A01                  | [dd4ada0631](https://linux-hardware.org/?probe=dd4ada0631) | Oct 18, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [db3ce64578](https://linux-hardware.org/?probe=db3ce64578) | Oct 18, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [621cca0fca](https://linux-hardware.org/?probe=621cca0fca) | Oct 18, 2022 |
| Gigabyte      | B450M DS3H-CF               | [e61760eab3](https://linux-hardware.org/?probe=e61760eab3) | Oct 18, 2022 |
| Dell          | 0WG864                      | [2feb42b3cf](https://linux-hardware.org/?probe=2feb42b3cf) | Oct 17, 2022 |
| HP            | 1589                        | [a6be3ee931](https://linux-hardware.org/?probe=a6be3ee931) | Oct 17, 2022 |
| ASRock        | B450M-HDV                   | [6a523a41da](https://linux-hardware.org/?probe=6a523a41da) | Oct 17, 2022 |
| Dell          | 01XK1W A00                  | [d86b86e8a8](https://linux-hardware.org/?probe=d86b86e8a8) | Oct 17, 2022 |
| HP            | 1589                        | [c36aa260eb](https://linux-hardware.org/?probe=c36aa260eb) | Oct 17, 2022 |
| Acer          | MCP7A                       | [32f914d009](https://linux-hardware.org/?probe=32f914d009) | Oct 17, 2022 |
| ASRock        | B450M Pro4                  | [d55b50c6c7](https://linux-hardware.org/?probe=d55b50c6c7) | Oct 16, 2022 |
| ASRock        | B450M Pro4                  | [4af4c60051](https://linux-hardware.org/?probe=4af4c60051) | Oct 16, 2022 |
| Gigabyte      | C246N-WU2-CF                | [cb7ca4eb5a](https://linux-hardware.org/?probe=cb7ca4eb5a) | Oct 16, 2022 |
| ASUSTek       | PRIME B250M-PLUS            | [c0feb12708](https://linux-hardware.org/?probe=c0feb12708) | Oct 16, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [f26592e956](https://linux-hardware.org/?probe=f26592e956) | Oct 16, 2022 |
| Dell          | 0782GW A00                  | [6a6f7314c0](https://linux-hardware.org/?probe=6a6f7314c0) | Oct 15, 2022 |
| Gigabyte      | H61M-S2PV                   | [f9568da63c](https://linux-hardware.org/?probe=f9568da63c) | Oct 15, 2022 |
| Gigabyte      | H61M-S2PV                   | [b226135430](https://linux-hardware.org/?probe=b226135430) | Oct 15, 2022 |
| Dell          | 0M863N A00                  | [27e1ded122](https://linux-hardware.org/?probe=27e1ded122) | Oct 15, 2022 |
| ASRock        | J5040-ITX                   | [aee52607f0](https://linux-hardware.org/?probe=aee52607f0) | Oct 14, 2022 |
| MSI           | G31TM-P21                   | [ea0fc2d497](https://linux-hardware.org/?probe=ea0fc2d497) | Oct 14, 2022 |
| ASRockRack    | X470D4U2-2T                 | [ebada4e791](https://linux-hardware.org/?probe=ebada4e791) | Oct 14, 2022 |
| Dell          | 0N4YC8 A00                  | [85766540b3](https://linux-hardware.org/?probe=85766540b3) | Oct 14, 2022 |
| Dell          | 0GY6Y8 A01                  | [06e46e98b4](https://linux-hardware.org/?probe=06e46e98b4) | Oct 14, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [9554b1f29a](https://linux-hardware.org/?probe=9554b1f29a) | Oct 14, 2022 |
| ASUSTek       | P5QL-CM                     | [34c01c8045](https://linux-hardware.org/?probe=34c01c8045) | Oct 14, 2022 |
| MSI           | PRO B550-VC                 | [0141458d01](https://linux-hardware.org/?probe=0141458d01) | Oct 14, 2022 |
| Gigabyte      | B450M DS3H-CF               | [ede8c7fa36](https://linux-hardware.org/?probe=ede8c7fa36) | Oct 13, 2022 |
| ASRock        | AM2NF6G-VSTA                | [6a810d253c](https://linux-hardware.org/?probe=6a810d253c) | Oct 13, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [1e2eda446c](https://linux-hardware.org/?probe=1e2eda446c) | Oct 13, 2022 |
| HP            | ProLiant MicroServer        | [067097bef8](https://linux-hardware.org/?probe=067097bef8) | Oct 13, 2022 |
| HP            | 158A                        | [6b1d53174a](https://linux-hardware.org/?probe=6b1d53174a) | Oct 12, 2022 |
| HP            | 3047h                       | [ba7f593887](https://linux-hardware.org/?probe=ba7f593887) | Oct 12, 2022 |
| Gigabyte      | 970A-DS3P                   | [744091dcaa](https://linux-hardware.org/?probe=744091dcaa) | Oct 12, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [55bb52409c](https://linux-hardware.org/?probe=55bb52409c) | Oct 12, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [300975f708](https://linux-hardware.org/?probe=300975f708) | Oct 11, 2022 |
| ASRock        | H570M-ITX/ac                | [eac6add22e](https://linux-hardware.org/?probe=eac6add22e) | Oct 11, 2022 |
| Gigabyte      | GA-880GM-D2H                | [6a9fe776d8](https://linux-hardware.org/?probe=6a9fe776d8) | Oct 10, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | [97bbb3b52b](https://linux-hardware.org/?probe=97bbb3b52b) | Oct 09, 2022 |
| Unknown       | Seagate Personal Cloud (... | [40ea197650](https://linux-hardware.org/?probe=40ea197650) | Oct 09, 2022 |
| ASUSTek       | PRIME B450M-A               | [bef5f7f7d7](https://linux-hardware.org/?probe=bef5f7f7d7) | Oct 09, 2022 |
| Dell          | 01XK1W A00                  | [ce045937bc](https://linux-hardware.org/?probe=ce045937bc) | Oct 09, 2022 |
| Dell          | 01XK1W A00                  | [939e426600](https://linux-hardware.org/?probe=939e426600) | Oct 08, 2022 |
| Dell          | 003KPJ A00                  | [e151f6645b](https://linux-hardware.org/?probe=e151f6645b) | Oct 08, 2022 |
| MSI           | H81M-E34                    | [154cb109bf](https://linux-hardware.org/?probe=154cb109bf) | Oct 08, 2022 |
| ASUSTek       | V-P8H67E                    | [b4f0f561d2](https://linux-hardware.org/?probe=b4f0f561d2) | Oct 08, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | [1798b09b89](https://linux-hardware.org/?probe=1798b09b89) | Oct 08, 2022 |
| ASRockRack    | X470D4U2-2T                 | [5b543dbd16](https://linux-hardware.org/?probe=5b543dbd16) | Oct 08, 2022 |
| Shuttle       | FS81                        | [ba7c22e135](https://linux-hardware.org/?probe=ba7c22e135) | Oct 07, 2022 |
| Shuttle       | FS81                        | [63ec5c8971](https://linux-hardware.org/?probe=63ec5c8971) | Oct 07, 2022 |
| Fujitsu       | D3417-B1 S26361-D3417-B1    | [aa89234022](https://linux-hardware.org/?probe=aa89234022) | Oct 07, 2022 |
| ASRock        | Z68 Extreme4                | [6b96459f0a](https://linux-hardware.org/?probe=6b96459f0a) | Oct 07, 2022 |
| ASUSTek       | PRIME H270-PRO              | [bbf95bf34d](https://linux-hardware.org/?probe=bbf95bf34d) | Oct 06, 2022 |
| ASUSTek       | P5GDC Pro                   | [25ac480f76](https://linux-hardware.org/?probe=25ac480f76) | Oct 06, 2022 |
| Techvision    | TVI7309X B0                 | [a12d335502](https://linux-hardware.org/?probe=a12d335502) | Oct 06, 2022 |
| Techvision    | TVI7309X B0                 | [fd49fda31a](https://linux-hardware.org/?probe=fd49fda31a) | Oct 06, 2022 |
| ASRock        | B450M Pro4                  | [0432411e08](https://linux-hardware.org/?probe=0432411e08) | Oct 05, 2022 |
| ASRock        | B450M Pro4                  | [c287d961f7](https://linux-hardware.org/?probe=c287d961f7) | Oct 05, 2022 |
| MSI           | X399 GAMING PRO CARBON A... | [1b399dcbb2](https://linux-hardware.org/?probe=1b399dcbb2) | Oct 05, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [bbea875fdc](https://linux-hardware.org/?probe=bbea875fdc) | Oct 05, 2022 |
| Lenovo        | ThinkStation S30 0569BE3    | [026d1ee25e](https://linux-hardware.org/?probe=026d1ee25e) | Oct 05, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [93698d1670](https://linux-hardware.org/?probe=93698d1670) | Oct 05, 2022 |
| ASRock        | 970M Pro3                   | [a9e9513b41](https://linux-hardware.org/?probe=a9e9513b41) | Oct 04, 2022 |
| Dell          | 0D4MD1 A00                  | [9ab1446c27](https://linux-hardware.org/?probe=9ab1446c27) | Oct 04, 2022 |
| Inventec      | D CLASS A02                 | [851214001a](https://linux-hardware.org/?probe=851214001a) | Oct 04, 2022 |
| ASUSTek       | P6T DELUXE V2               | [1c6fd70d5f](https://linux-hardware.org/?probe=1c6fd70d5f) | Oct 04, 2022 |
| HP            | 1906                        | [a6f705f119](https://linux-hardware.org/?probe=a6f705f119) | Oct 03, 2022 |
| Dell          | 0T7D40 A01                  | [1fb6d9ec64](https://linux-hardware.org/?probe=1fb6d9ec64) | Oct 03, 2022 |
| Gigabyte      | D525TUD                     | [47d31ff25c](https://linux-hardware.org/?probe=47d31ff25c) | Oct 03, 2022 |
| Lenovo        | ThinkServer TS440           | [1031dfcd50](https://linux-hardware.org/?probe=1031dfcd50) | Oct 03, 2022 |
| Pegatron      | 2AC3                        | [0ea51f0746](https://linux-hardware.org/?probe=0ea51f0746) | Oct 03, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [e3a783a839](https://linux-hardware.org/?probe=e3a783a839) | Oct 02, 2022 |
| ASUSTek       | PRIME B550M-K               | [31dcf67714](https://linux-hardware.org/?probe=31dcf67714) | Oct 02, 2022 |
| ASUSTek       | PRIME B550M-K               | [97afbe98b8](https://linux-hardware.org/?probe=97afbe98b8) | Oct 02, 2022 |
| ASUSTek       | M5A97 R2.0                  | [78ff851478](https://linux-hardware.org/?probe=78ff851478) | Oct 02, 2022 |
| Dell          | 0KJCC5 A00                  | [7915b298b2](https://linux-hardware.org/?probe=7915b298b2) | Oct 01, 2022 |
| Dell          | 01XK1W A00                  | [29c4292c62](https://linux-hardware.org/?probe=29c4292c62) | Oct 01, 2022 |
| Gigabyte      | H81M-D2V                    | [21a601e10a](https://linux-hardware.org/?probe=21a601e10a) | Sep 30, 2022 |
| HP            | 859C                        | [08161b9516](https://linux-hardware.org/?probe=08161b9516) | Sep 30, 2022 |
| ASRock        | X570 Steel Legend           | [40e65e38cf](https://linux-hardware.org/?probe=40e65e38cf) | Sep 30, 2022 |
| ECS           | G31T-M9                     | [45b25aaf8c](https://linux-hardware.org/?probe=45b25aaf8c) | Sep 29, 2022 |
| Biostar       | H55 HD                      | [bde8e0a133](https://linux-hardware.org/?probe=bde8e0a133) | Sep 28, 2022 |
| BESSTAR Te... | TH50                        | [2045e665b1](https://linux-hardware.org/?probe=2045e665b1) | Sep 28, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | [6d92b99f8e](https://linux-hardware.org/?probe=6d92b99f8e) | Sep 28, 2022 |
| HP            | 339A                        | [5c961ef93f](https://linux-hardware.org/?probe=5c961ef93f) | Sep 28, 2022 |
| HP            | 339A                        | [ac9538b489](https://linux-hardware.org/?probe=ac9538b489) | Sep 28, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [82b108b3b8](https://linux-hardware.org/?probe=82b108b3b8) | Sep 28, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [0031772f40](https://linux-hardware.org/?probe=0031772f40) | Sep 27, 2022 |
| MSI           | B365M PRO-VDH               | [45e07c7119](https://linux-hardware.org/?probe=45e07c7119) | Sep 27, 2022 |
| Medion        | MS-7728                     | [0b9b2ca570](https://linux-hardware.org/?probe=0b9b2ca570) | Sep 27, 2022 |
| HP            | 339A                        | [25ef7556cc](https://linux-hardware.org/?probe=25ef7556cc) | Sep 27, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | [757d465447](https://linux-hardware.org/?probe=757d465447) | Sep 27, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [e3826dca71](https://linux-hardware.org/?probe=e3826dca71) | Sep 27, 2022 |
| Gigabyte      | H81M-S2PV                   | [76a7224818](https://linux-hardware.org/?probe=76a7224818) | Sep 26, 2022 |
| HP            | 339A                        | [07986ca95e](https://linux-hardware.org/?probe=07986ca95e) | Sep 26, 2022 |
| HP            | 0B40h                       | [d72bb749ff](https://linux-hardware.org/?probe=d72bb749ff) | Sep 26, 2022 |
| Lenovo        | Myrtle CRB SDK0J40700 WI... | [508c873693](https://linux-hardware.org/?probe=508c873693) | Sep 26, 2022 |
| Dell          | 01XK1W A00                  | [4e228116be](https://linux-hardware.org/?probe=4e228116be) | Sep 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [6c9c3f13d0](https://linux-hardware.org/?probe=6c9c3f13d0) | Sep 25, 2022 |
| ASRockRack    | X570D4U-2L2T                | [779faa3cfd](https://linux-hardware.org/?probe=779faa3cfd) | Sep 25, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [65d54e7273](https://linux-hardware.org/?probe=65d54e7273) | Sep 25, 2022 |
| Google        | Teemo                       | [5ddc8b97b8](https://linux-hardware.org/?probe=5ddc8b97b8) | Sep 24, 2022 |
| MSI           | H81M-P33                    | [7e4f539e70](https://linux-hardware.org/?probe=7e4f539e70) | Sep 24, 2022 |
| MSI           | H81M-P33                    | [64cd74457e](https://linux-hardware.org/?probe=64cd74457e) | Sep 24, 2022 |
| Foxconn       | 2ADA                        | [8a734f0799](https://linux-hardware.org/?probe=8a734f0799) | Sep 24, 2022 |
| ASUSTek       | P8B75-M                     | [0299e4f7b1](https://linux-hardware.org/?probe=0299e4f7b1) | Sep 24, 2022 |
| ASUSTek       | P8B75-M                     | [cad0f6f375](https://linux-hardware.org/?probe=cad0f6f375) | Sep 24, 2022 |
| ASUSTek       | P8B75-M                     | [91d179670c](https://linux-hardware.org/?probe=91d179670c) | Sep 23, 2022 |
| ASUSTek       | PRIME X570-P                | [5f1b4b1679](https://linux-hardware.org/?probe=5f1b4b1679) | Sep 23, 2022 |
| ECS           | H61H2-CM                    | [13ad69a13e](https://linux-hardware.org/?probe=13ad69a13e) | Sep 23, 2022 |
| ASUSTek       | P5QPL-VM EPU                | [8a4819f23d](https://linux-hardware.org/?probe=8a4819f23d) | Sep 23, 2022 |
| Gigabyte      | H81M-S2V                    | [6c884d4968](https://linux-hardware.org/?probe=6c884d4968) | Sep 23, 2022 |
| Gigabyte      | H81M-S2V                    | [39a94459dc](https://linux-hardware.org/?probe=39a94459dc) | Sep 23, 2022 |
| ASUSTek       | H110M-R                     | [c9f00bec8e](https://linux-hardware.org/?probe=c9f00bec8e) | Sep 23, 2022 |
| HP            | 876C SMVB                   | [c6fbf7c631](https://linux-hardware.org/?probe=c6fbf7c631) | Sep 23, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [c0cc0dc101](https://linux-hardware.org/?probe=c0cc0dc101) | Sep 21, 2022 |
| Lenovo        | ThinkCentre A70z 0401R6U    | [2a93ca040a](https://linux-hardware.org/?probe=2a93ca040a) | Sep 21, 2022 |
| Thecus        | N2810 0001                  | [f54df3994c](https://linux-hardware.org/?probe=f54df3994c) | Sep 21, 2022 |
| ECS           | G31T-M9                     | [6e67780df1](https://linux-hardware.org/?probe=6e67780df1) | Sep 21, 2022 |
| Gigabyte      | H61M-DS2                    | [a9e18191f7](https://linux-hardware.org/?probe=a9e18191f7) | Sep 21, 2022 |
| ASRock        | H470M-HVS                   | [e267d78b42](https://linux-hardware.org/?probe=e267d78b42) | Sep 21, 2022 |
| ECS           | G31T-M9                     | [46fd18ee44](https://linux-hardware.org/?probe=46fd18ee44) | Sep 21, 2022 |
| ASUSTek       | M3N78-VM                    | [03e6d4f5bc](https://linux-hardware.org/?probe=03e6d4f5bc) | Sep 21, 2022 |
| ASUSTek       | M3N78-VM                    | [658141844b](https://linux-hardware.org/?probe=658141844b) | Sep 21, 2022 |
| Lenovo        | ThinkCentre M57 6072WMD     | [eb8221088f](https://linux-hardware.org/?probe=eb8221088f) | Sep 21, 2022 |
| HP            | 158A                        | [428326af76](https://linux-hardware.org/?probe=428326af76) | Sep 21, 2022 |
| Supermicro    | X9DR3-F                     | [da32f7dbfb](https://linux-hardware.org/?probe=da32f7dbfb) | Sep 21, 2022 |
| ASUSTek       | G20CB                       | [34f4d43b97](https://linux-hardware.org/?probe=34f4d43b97) | Sep 20, 2022 |
| Shuttle       | FS81                        | [4c1fb942aa](https://linux-hardware.org/?probe=4c1fb942aa) | Sep 20, 2022 |
| Gigabyte      | A320M-S2H-CF                | [172fd1874d](https://linux-hardware.org/?probe=172fd1874d) | Sep 20, 2022 |
| Dell          | 0KY237 A01                  | [e1258b712e](https://linux-hardware.org/?probe=e1258b712e) | Sep 20, 2022 |
| Dell          | 0KY237 A01                  | [6f2ce8e794](https://linux-hardware.org/?probe=6f2ce8e794) | Sep 20, 2022 |
| ASUSTek       | B85M-G                      | [f9fa37f0d2](https://linux-hardware.org/?probe=f9fa37f0d2) | Sep 20, 2022 |
| Gigabyte      | GA-M56S-S3                  | [ecd62e14f4](https://linux-hardware.org/?probe=ecd62e14f4) | Sep 20, 2022 |
| Unknown       | 1.0                         | [1ef071c553](https://linux-hardware.org/?probe=1ef071c553) | Sep 20, 2022 |
| MSI           | Z370 PC PRO                 | [7967e43f1d](https://linux-hardware.org/?probe=7967e43f1d) | Sep 20, 2022 |
| Lenovo        | SKYBAY SDK0J40700 WIN 32... | [37fcfc48c5](https://linux-hardware.org/?probe=37fcfc48c5) | Sep 20, 2022 |
| Gigabyte      | EP45T-UD3R                  | [979765d106](https://linux-hardware.org/?probe=979765d106) | Sep 20, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [a0a61b5d8c](https://linux-hardware.org/?probe=a0a61b5d8c) | Sep 20, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [bb8e3ae62a](https://linux-hardware.org/?probe=bb8e3ae62a) | Sep 20, 2022 |
| ASUSTek       | M5A97 R2.0                  | [96e0712ca0](https://linux-hardware.org/?probe=96e0712ca0) | Sep 19, 2022 |
| ASRock        | H470M-HVS                   | [ee235bf98c](https://linux-hardware.org/?probe=ee235bf98c) | Sep 19, 2022 |
| Gigabyte      | B550 VISION D-P             | [9457acbe13](https://linux-hardware.org/?probe=9457acbe13) | Sep 19, 2022 |
| ASUSTek       | P5G41T-M LX                 | [74e31be1be](https://linux-hardware.org/?probe=74e31be1be) | Sep 19, 2022 |
| AZW           | GK55                        | [9a9019eee6](https://linux-hardware.org/?probe=9a9019eee6) | Sep 19, 2022 |
| ASRock        | Z590M-ITX/ax                | [d202b0a504](https://linux-hardware.org/?probe=d202b0a504) | Sep 19, 2022 |
| Supermicro    | X10DRi-T4+                  | [1f507cde8c](https://linux-hardware.org/?probe=1f507cde8c) | Sep 19, 2022 |
| HP            | 1998                        | [14eeedb712](https://linux-hardware.org/?probe=14eeedb712) | Sep 18, 2022 |
| Dell          | 0KY237 A01                  | [8b2d50f5d1](https://linux-hardware.org/?probe=8b2d50f5d1) | Sep 18, 2022 |
| Dell          | 0G785M A00                  | [c1045050d6](https://linux-hardware.org/?probe=c1045050d6) | Sep 17, 2022 |
| Gigabyte      | B365M DS3H                  | [e552983263](https://linux-hardware.org/?probe=e552983263) | Sep 17, 2022 |
| Dell          | 0T2HR0 A02                  | [46dd4dfa8f](https://linux-hardware.org/?probe=46dd4dfa8f) | Sep 17, 2022 |
| AZW           | Gemini T34-M                | [baafe96fc5](https://linux-hardware.org/?probe=baafe96fc5) | Sep 17, 2022 |
| ASUSTek       | P8Z77-V                     | [3ace24ebfc](https://linux-hardware.org/?probe=3ace24ebfc) | Sep 16, 2022 |
| ASUSTek       | LITHIUM                     | [3aab1aa49f](https://linux-hardware.org/?probe=3aab1aa49f) | Sep 16, 2022 |
| ASUSTek       | KCMA-D8                     | [dc8ecec94f](https://linux-hardware.org/?probe=dc8ecec94f) | Sep 16, 2022 |
| Gigabyte      | B150M-D3P-WG-CF             | [e37ff8fec3](https://linux-hardware.org/?probe=e37ff8fec3) | Sep 16, 2022 |
| ASRock        | H470M-HVS                   | [205e3937a8](https://linux-hardware.org/?probe=205e3937a8) | Sep 16, 2022 |
| MSI           | B450-A PRO MAX              | [c63f6d45b4](https://linux-hardware.org/?probe=c63f6d45b4) | Sep 16, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [00ca986a4c](https://linux-hardware.org/?probe=00ca986a4c) | Sep 16, 2022 |
| MSI           | H110M PRO-VD                | [23194305f6](https://linux-hardware.org/?probe=23194305f6) | Sep 15, 2022 |
| ASUSTek       | B85M-G                      | [9f2a08c261](https://linux-hardware.org/?probe=9f2a08c261) | Sep 15, 2022 |
| Gigabyte      | EP45T-UD3R                  | [007e9d4205](https://linux-hardware.org/?probe=007e9d4205) | Sep 15, 2022 |
| HP            | 876C SMVB                   | [adc81b2fd5](https://linux-hardware.org/?probe=adc81b2fd5) | Sep 15, 2022 |
| Gigabyte      | B560M DS3H V2               | [af4b9d7add](https://linux-hardware.org/?probe=af4b9d7add) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | [01d92ffc28](https://linux-hardware.org/?probe=01d92ffc28) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | [c04d19fe27](https://linux-hardware.org/?probe=c04d19fe27) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | [ad0ac85a1c](https://linux-hardware.org/?probe=ad0ac85a1c) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | [6cb46b9558](https://linux-hardware.org/?probe=6cb46b9558) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | [bec6da09ae](https://linux-hardware.org/?probe=bec6da09ae) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | [0366b6294c](https://linux-hardware.org/?probe=0366b6294c) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | [a914907c0f](https://linux-hardware.org/?probe=a914907c0f) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | [662117584a](https://linux-hardware.org/?probe=662117584a) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | [272b6ec971](https://linux-hardware.org/?probe=272b6ec971) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | [2528bbb7ac](https://linux-hardware.org/?probe=2528bbb7ac) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | [212a063241](https://linux-hardware.org/?probe=212a063241) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | [2b6d3fc6f0](https://linux-hardware.org/?probe=2b6d3fc6f0) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | [9bc2776801](https://linux-hardware.org/?probe=9bc2776801) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | [4048396126](https://linux-hardware.org/?probe=4048396126) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | [7036d4bc55](https://linux-hardware.org/?probe=7036d4bc55) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | [e4147da882](https://linux-hardware.org/?probe=e4147da882) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | [f85ab5e109](https://linux-hardware.org/?probe=f85ab5e109) | Sep 14, 2022 |
| Lenovo        | SHARKBAY 0C48431 WIN        | [4598920e84](https://linux-hardware.org/?probe=4598920e84) | Sep 13, 2022 |
| HP            | 876C SMVB                   | [15ec81ce9d](https://linux-hardware.org/?probe=15ec81ce9d) | Sep 13, 2022 |
| Biostar       | NF560-A2G                   | [96c296c2f3](https://linux-hardware.org/?probe=96c296c2f3) | Sep 13, 2022 |
| ASRock        | H470M-HDV                   | [41977548bc](https://linux-hardware.org/?probe=41977548bc) | Sep 13, 2022 |
| Positivo      | POS-EINM10CB POSITIVO       | [7c876e560b](https://linux-hardware.org/?probe=7c876e560b) | Sep 13, 2022 |
| HP            | 8464                        | [fcc16a5a56](https://linux-hardware.org/?probe=fcc16a5a56) | Sep 12, 2022 |
| Gigabyte      | H410M S2H                   | [31ca5d0add](https://linux-hardware.org/?probe=31ca5d0add) | Sep 12, 2022 |
| Gigabyte      | H410M S2H                   | [d76d427a61](https://linux-hardware.org/?probe=d76d427a61) | Sep 12, 2022 |
| Gigabyte      | H410M S2H                   | [c996d652d3](https://linux-hardware.org/?probe=c996d652d3) | Sep 12, 2022 |
| Gigabyte      | H410M S2H                   | [d08cb8e35b](https://linux-hardware.org/?probe=d08cb8e35b) | Sep 12, 2022 |
| Gigabyte      | H410M S2H                   | [0c2d66313e](https://linux-hardware.org/?probe=0c2d66313e) | Sep 12, 2022 |
| Gigabyte      | H410M S2H                   | [5461cdbf3b](https://linux-hardware.org/?probe=5461cdbf3b) | Sep 12, 2022 |
| Gigabyte      | H410M S2H                   | [c055d82971](https://linux-hardware.org/?probe=c055d82971) | Sep 12, 2022 |
| Gigabyte      | H410M S2H                   | [8c0d419ac8](https://linux-hardware.org/?probe=8c0d419ac8) | Sep 12, 2022 |
| ASUSTek       | PRIME B450M-A               | [2af6edb7a0](https://linux-hardware.org/?probe=2af6edb7a0) | Sep 12, 2022 |
| ASUSTek       | G20CB                       | [a52ff97f3b](https://linux-hardware.org/?probe=a52ff97f3b) | Sep 12, 2022 |
| ASUSTek       | G20CB                       | [2d737743f4](https://linux-hardware.org/?probe=2d737743f4) | Sep 12, 2022 |
| ASUSTek       | Pro WS 565-ACE              | [e8da6da2b0](https://linux-hardware.org/?probe=e8da6da2b0) | Sep 12, 2022 |
| Inventec      | C CLASS A01                 | [613f741235](https://linux-hardware.org/?probe=613f741235) | Sep 12, 2022 |
| Dell          | 01XK1W A00                  | [09d0fcce0e](https://linux-hardware.org/?probe=09d0fcce0e) | Sep 12, 2022 |
| Lenovo        | 36EB SDK0J40700 WIN 3258... | [e007728e0a](https://linux-hardware.org/?probe=e007728e0a) | Sep 11, 2022 |
| Inventec      | C CLASS A01                 | [21ae14e7a0](https://linux-hardware.org/?probe=21ae14e7a0) | Sep 11, 2022 |
| Inventec      | C CLASS A01                 | [3ddd0d7aa0](https://linux-hardware.org/?probe=3ddd0d7aa0) | Sep 11, 2022 |
| Dell          | 01XK1W A00                  | [41b9796681](https://linux-hardware.org/?probe=41b9796681) | Sep 10, 2022 |
| HP            | 1998                        | [37cd896e72](https://linux-hardware.org/?probe=37cd896e72) | Sep 10, 2022 |
| HP            | 1998                        | [3da9c3ef8e](https://linux-hardware.org/?probe=3da9c3ef8e) | Sep 10, 2022 |
| Lenovo        | ThinkServer TS440           | [cf028f9b8c](https://linux-hardware.org/?probe=cf028f9b8c) | Sep 10, 2022 |
| Lenovo        | ThinkCentre A70 7099A5G     | [102cf248e9](https://linux-hardware.org/?probe=102cf248e9) | Sep 10, 2022 |
| Biostar       | NF560-A2G                   | [68ffa42095](https://linux-hardware.org/?probe=68ffa42095) | Sep 09, 2022 |
| ASRock        | H310CM-HDV                  | [4f0ec780ee](https://linux-hardware.org/?probe=4f0ec780ee) | Sep 09, 2022 |
| Gigabyte      | A320M-S2H-CF                | [e4d2c1c120](https://linux-hardware.org/?probe=e4d2c1c120) | Sep 09, 2022 |
| Gigabyte      | A320M-S2H-CF                | [d28677add3](https://linux-hardware.org/?probe=d28677add3) | Sep 09, 2022 |
| Gigabyte      | M61PME-S2                   | [2557dd83ce](https://linux-hardware.org/?probe=2557dd83ce) | Sep 09, 2022 |
| ASRock        | Q1900M                      | [aadbe54f8d](https://linux-hardware.org/?probe=aadbe54f8d) | Sep 08, 2022 |
| ASUSTek       | P8H61-MX R2.0               | [17675b7bc8](https://linux-hardware.org/?probe=17675b7bc8) | Sep 08, 2022 |
| Gigabyte      | M61PME-S2                   | [1c48e52b18](https://linux-hardware.org/?probe=1c48e52b18) | Sep 08, 2022 |
| Gigabyte      | GA-M56S-S3                  | [b090ccb8fe](https://linux-hardware.org/?probe=b090ccb8fe) | Sep 07, 2022 |
| ASUSTek       | P5G41T-M LE                 | [6949fd04b7](https://linux-hardware.org/?probe=6949fd04b7) | Sep 07, 2022 |
| ASUSTek       | X99-E WS                    | [fcf815d38f](https://linux-hardware.org/?probe=fcf815d38f) | Sep 07, 2022 |
| MSI           | H110M PRO-VD                | [754b9daf74](https://linux-hardware.org/?probe=754b9daf74) | Sep 07, 2022 |
| Gigabyte      | GA-M56S-S3                  | [9012dd4a5d](https://linux-hardware.org/?probe=9012dd4a5d) | Sep 06, 2022 |
| Foxconn       | H61MXL/H61MXL-K             | [92af2339e3](https://linux-hardware.org/?probe=92af2339e3) | Sep 06, 2022 |
| ECS           | G31T-M9                     | [5005d8382e](https://linux-hardware.org/?probe=5005d8382e) | Sep 06, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [f7b09fb3e3](https://linux-hardware.org/?probe=f7b09fb3e3) | Sep 06, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [dacafc4729](https://linux-hardware.org/?probe=dacafc4729) | Sep 06, 2022 |
| ASUSTek       | PRIME Z690M-HZ              | [2c5b0be3af](https://linux-hardware.org/?probe=2c5b0be3af) | Sep 06, 2022 |
| Gigabyte      | G41M-ES2L                   | [4071a8ff9b](https://linux-hardware.org/?probe=4071a8ff9b) | Sep 05, 2022 |
| ASUSTek       | PRIME X370-PRO              | [312e33b434](https://linux-hardware.org/?probe=312e33b434) | Sep 05, 2022 |
| HP            | 805D                        | [fdf50a9e36](https://linux-hardware.org/?probe=fdf50a9e36) | Sep 05, 2022 |
| Dell          | 06FW8P A00                  | [6023e5aa76](https://linux-hardware.org/?probe=6023e5aa76) | Sep 05, 2022 |
| ASUSTek       | Z97-PRO                     | [b9f3857d65](https://linux-hardware.org/?probe=b9f3857d65) | Sep 04, 2022 |
| ASRock        | Q1900M                      | [55a86f60b9](https://linux-hardware.org/?probe=55a86f60b9) | Sep 04, 2022 |
| Gigabyte      | Z87X-UD4H-CF                | [8ffe312747](https://linux-hardware.org/?probe=8ffe312747) | Sep 04, 2022 |
| MSI           | H510M-A PRO                 | [eb29524a90](https://linux-hardware.org/?probe=eb29524a90) | Sep 03, 2022 |
| ASUSTek       | Pro WS 565-ACE              | [3a599be2f2](https://linux-hardware.org/?probe=3a599be2f2) | Sep 03, 2022 |
| ASUSTek       | P8H61 PRO                   | [082520f2d8](https://linux-hardware.org/?probe=082520f2d8) | Sep 03, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [9b8eef74b8](https://linux-hardware.org/?probe=9b8eef74b8) | Sep 03, 2022 |
| ASUSTek       | PRIME H270-PRO              | [5c0b32f572](https://linux-hardware.org/?probe=5c0b32f572) | Sep 03, 2022 |
| ASRockRack    | X470D4U2/1N1                | [0be6c5963d](https://linux-hardware.org/?probe=0be6c5963d) | Sep 02, 2022 |
| ASRock        | J3455-ITX                   | [262c6222d1](https://linux-hardware.org/?probe=262c6222d1) | Sep 02, 2022 |
| Gigabyte      | B550M DS3H                  | [acdd27f635](https://linux-hardware.org/?probe=acdd27f635) | Sep 02, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [3870423379](https://linux-hardware.org/?probe=3870423379) | Sep 02, 2022 |
| Lenovo        | SDK0J40705 WIN 342504154... | [4feb69184d](https://linux-hardware.org/?probe=4feb69184d) | Sep 02, 2022 |
| Lenovo        | SDK0J40705 WIN 342504154... | [bfee1a862f](https://linux-hardware.org/?probe=bfee1a862f) | Sep 02, 2022 |
| Gigabyte      | H77-DS3H                    | [11f9e9fa68](https://linux-hardware.org/?probe=11f9e9fa68) | Sep 02, 2022 |
| Gigabyte      | GA-970A-UD3                 | [e9f6cafc6c](https://linux-hardware.org/?probe=e9f6cafc6c) | Sep 02, 2022 |
| Gigabyte      | Z590 UD AC                  | [6c7b47158f](https://linux-hardware.org/?probe=6c7b47158f) | Sep 02, 2022 |
| Dell          | 02YRK5 A02                  | [bc316a8d3f](https://linux-hardware.org/?probe=bc316a8d3f) | Sep 01, 2022 |
| MSI           | H81M-P33                    | [8d15799ff9](https://linux-hardware.org/?probe=8d15799ff9) | Sep 01, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [b226dd8bc2](https://linux-hardware.org/?probe=b226dd8bc2) | Sep 01, 2022 |
| Gigabyte      | M68MT-S2                    | [29b9669488](https://linux-hardware.org/?probe=29b9669488) | Aug 31, 2022 |
| ASRock        | B450M-HDV R4.0              | [9c9e1d1ff1](https://linux-hardware.org/?probe=9c9e1d1ff1) | Aug 31, 2022 |
| ASRock        | N68-VS3 UCC                 | [688dcf88c9](https://linux-hardware.org/?probe=688dcf88c9) | Aug 30, 2022 |
| ASRock        | N68-VS3 UCC                 | [4ccef99860](https://linux-hardware.org/?probe=4ccef99860) | Aug 30, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [28f3abde34](https://linux-hardware.org/?probe=28f3abde34) | Aug 30, 2022 |
| Fujitsu       | D3348-B1 S26361-D3348-B1    | [9721d1f81d](https://linux-hardware.org/?probe=9721d1f81d) | Aug 30, 2022 |
| Unknown       | Unknown                     | [fd4ab67b77](https://linux-hardware.org/?probe=fd4ab67b77) | Aug 29, 2022 |
| Pegatron      | VIOLET6                     | [f17bcbfc4b](https://linux-hardware.org/?probe=f17bcbfc4b) | Aug 28, 2022 |
| Pegatron      | VIOLET6                     | [4960a57d91](https://linux-hardware.org/?probe=4960a57d91) | Aug 28, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [859b3cb78a](https://linux-hardware.org/?probe=859b3cb78a) | Aug 28, 2022 |
| ASUSTek       | Z170 PRO GAMING             | [e0fedafd62](https://linux-hardware.org/?probe=e0fedafd62) | Aug 27, 2022 |
| ASRock        | Z68 Pro3 Gen3               | [186a63fa9e](https://linux-hardware.org/?probe=186a63fa9e) | Aug 27, 2022 |
| ASUSTek       | P5G41T-M LX V2              | [3c63953ca6](https://linux-hardware.org/?probe=3c63953ca6) | Aug 27, 2022 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | [fbfc58655a](https://linux-hardware.org/?probe=fbfc58655a) | Aug 26, 2022 |
| Dell          | 01XK1W A00                  | [7728612d53](https://linux-hardware.org/?probe=7728612d53) | Aug 26, 2022 |
| Dell          | 01XK1W A00                  | [ee6cec5f61](https://linux-hardware.org/?probe=ee6cec5f61) | Aug 26, 2022 |
| Gigabyte      | B250M-DS3H-CF               | [5d4e41a441](https://linux-hardware.org/?probe=5d4e41a441) | Aug 26, 2022 |
| Intel         | X79G V2.x                   | [8418a8e83c](https://linux-hardware.org/?probe=8418a8e83c) | Aug 26, 2022 |
| ASUSTek       | IPN73-BA                    | [89f8b175e2](https://linux-hardware.org/?probe=89f8b175e2) | Aug 26, 2022 |
| Foxconn       | 2ABF                        | [46efca142c](https://linux-hardware.org/?probe=46efca142c) | Aug 26, 2022 |
| HP            | 18E5                        | [9196bf639b](https://linux-hardware.org/?probe=9196bf639b) | Aug 26, 2022 |
| Lenovo        | 7033EW4                     | [54417ae55f](https://linux-hardware.org/?probe=54417ae55f) | Aug 26, 2022 |
| Gigabyte      | X399 AORUS PRO-CF           | [5769de3299](https://linux-hardware.org/?probe=5769de3299) | Aug 25, 2022 |
| Gigabyte      | M61SME-S2                   | [2ee74a388d](https://linux-hardware.org/?probe=2ee74a388d) | Aug 25, 2022 |
| Dell          | 0D4MD1 A02                  | [7a06622253](https://linux-hardware.org/?probe=7a06622253) | Aug 25, 2022 |
| Dell          | 0WG864                      | [a333ec7f99](https://linux-hardware.org/?probe=a333ec7f99) | Aug 25, 2022 |
| ASUSTek       | A7N8X2.0                    | [f063b3e61a](https://linux-hardware.org/?probe=f063b3e61a) | Aug 25, 2022 |
| Gigabyte      | G41MT-S2                    | [42cd205688](https://linux-hardware.org/?probe=42cd205688) | Aug 25, 2022 |
| ASUSTek       | IPN73-BA                    | [da7e1db516](https://linux-hardware.org/?probe=da7e1db516) | Aug 25, 2022 |
| Dell          | 01XK1W A00                  | [604a0a7789](https://linux-hardware.org/?probe=604a0a7789) | Aug 25, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [413cc5a3c3](https://linux-hardware.org/?probe=413cc5a3c3) | Aug 24, 2022 |
| HP            | 339A                        | [961ac650aa](https://linux-hardware.org/?probe=961ac650aa) | Aug 24, 2022 |
| Dell          | 0D4MD1 A02                  | [b634bcdfa9](https://linux-hardware.org/?probe=b634bcdfa9) | Aug 24, 2022 |
| Huanan        | X99-F8D V2.4                | [11cfa7a502](https://linux-hardware.org/?probe=11cfa7a502) | Aug 24, 2022 |
| ASUSTek       | Pro B550M-C                 | [f0691dc9d8](https://linux-hardware.org/?probe=f0691dc9d8) | Aug 23, 2022 |
| Aquarius      | AQH310CM                    | [5e7e2820f4](https://linux-hardware.org/?probe=5e7e2820f4) | Aug 23, 2022 |
| ASUSTek       | A7N8X2.0                    | [56416fa002](https://linux-hardware.org/?probe=56416fa002) | Aug 23, 2022 |
| Dell          | 0MWYPT A02                  | [017af6f58d](https://linux-hardware.org/?probe=017af6f58d) | Aug 23, 2022 |
| Dell          | 0WG864                      | [e199a1a176](https://linux-hardware.org/?probe=e199a1a176) | Aug 23, 2022 |
| MSI           | H110M PRO-VD                | [7652f87b3a](https://linux-hardware.org/?probe=7652f87b3a) | Aug 22, 2022 |
| ASUSTek       | Z10PA-U8 Series             | [3e560a4018](https://linux-hardware.org/?probe=3e560a4018) | Aug 22, 2022 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [5cf178d7ac](https://linux-hardware.org/?probe=5cf178d7ac) | Aug 22, 2022 |
| ASUSTek       | Z170-A                      | [35270005d4](https://linux-hardware.org/?probe=35270005d4) | Aug 22, 2022 |
| Biostar       | A68N-5100                   | [2c6df92279](https://linux-hardware.org/?probe=2c6df92279) | Aug 22, 2022 |
| Foxconn       | 2ABF                        | [3eed86b908](https://linux-hardware.org/?probe=3eed86b908) | Aug 21, 2022 |
| ASRock        | Z77 Extreme6                | [660091e5bb](https://linux-hardware.org/?probe=660091e5bb) | Aug 20, 2022 |
| Google        | Teemo                       | [4cc9295e6d](https://linux-hardware.org/?probe=4cc9295e6d) | Aug 20, 2022 |
| MSI           | Z370 PC PRO                 | [9131aa23c4](https://linux-hardware.org/?probe=9131aa23c4) | Aug 20, 2022 |
| Gigabyte      | B460M DS3H V2               | [e5e74eea07](https://linux-hardware.org/?probe=e5e74eea07) | Aug 19, 2022 |
| Intel         | DN2820FYK H24582-201        | [a67c5b1926](https://linux-hardware.org/?probe=a67c5b1926) | Aug 19, 2022 |
| ASRock        | B450M-HDV R4.0              | [2f99e182f6](https://linux-hardware.org/?probe=2f99e182f6) | Aug 19, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [38eed67854](https://linux-hardware.org/?probe=38eed67854) | Aug 18, 2022 |
| Gateway       | DS50                        | [3d4faf13bb](https://linux-hardware.org/?probe=3d4faf13bb) | Aug 18, 2022 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | [58b22885a8](https://linux-hardware.org/?probe=58b22885a8) | Aug 18, 2022 |
| Gigabyte      | B560M DS3H AC               | [84e861fd2c](https://linux-hardware.org/?probe=84e861fd2c) | Aug 18, 2022 |
| ECS           | H61H2-M13                   | [fb83ed3720](https://linux-hardware.org/?probe=fb83ed3720) | Aug 18, 2022 |
| ECS           | G31T-M9                     | [d5b3edd559](https://linux-hardware.org/?probe=d5b3edd559) | Aug 18, 2022 |
| Lenovo        | ThinkStation D30 4223CC9    | [16e54152fd](https://linux-hardware.org/?probe=16e54152fd) | Aug 18, 2022 |
| Lenovo        | ThinkStation D30 4223CC9    | [e0208cab99](https://linux-hardware.org/?probe=e0208cab99) | Aug 18, 2022 |
| MSI           | B85M-E45                    | [cb991c0789](https://linux-hardware.org/?probe=cb991c0789) | Aug 17, 2022 |
| MSI           | X470 GAMING PRO             | [b648d56b04](https://linux-hardware.org/?probe=b648d56b04) | Aug 17, 2022 |
| Gigabyte      | H61M-DS2                    | [d066e1bcdf](https://linux-hardware.org/?probe=d066e1bcdf) | Aug 17, 2022 |
| ECS           | G31T-M9                     | [6192258c32](https://linux-hardware.org/?probe=6192258c32) | Aug 17, 2022 |
| Gigabyte      | D525TUD                     | [125fdc6af1](https://linux-hardware.org/?probe=125fdc6af1) | Aug 17, 2022 |
| Dell          | 0F6X5P A00                  | [47ecca331e](https://linux-hardware.org/?probe=47ecca331e) | Aug 16, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [1999369ff0](https://linux-hardware.org/?probe=1999369ff0) | Aug 16, 2022 |
| Dell          | 02YRK5 A02                  | [959d35921a](https://linux-hardware.org/?probe=959d35921a) | Aug 15, 2022 |
| HP            | 3047h                       | [bba72086af](https://linux-hardware.org/?probe=bba72086af) | Aug 15, 2022 |
| ASUSTek       | WS C422 DC                  | [92d816348a](https://linux-hardware.org/?probe=92d816348a) | Aug 15, 2022 |
| Gigabyte      | GA-970A-UD3                 | [9a1ff39910](https://linux-hardware.org/?probe=9a1ff39910) | Aug 15, 2022 |
| ASRock        | AB350 Gaming K4             | [8a6141848a](https://linux-hardware.org/?probe=8a6141848a) | Aug 13, 2022 |
| Dell          | 0WWJRX A00                  | [c9a3a6e952](https://linux-hardware.org/?probe=c9a3a6e952) | Aug 13, 2022 |
| System76      | Thelio thelio-r1            | [5b24d3e87b](https://linux-hardware.org/?probe=5b24d3e87b) | Aug 12, 2022 |
| Dell          | 0WG864                      | [de74f89735](https://linux-hardware.org/?probe=de74f89735) | Aug 12, 2022 |
| Unknown       | Unknown                     | [ed94063eb8](https://linux-hardware.org/?probe=ed94063eb8) | Aug 12, 2022 |
| ASUSTek       | PRIME Z370-P                | [7afaba2067](https://linux-hardware.org/?probe=7afaba2067) | Aug 12, 2022 |
| MSI           | H110M PRO-VD                | [57be8a8829](https://linux-hardware.org/?probe=57be8a8829) | Aug 12, 2022 |
| MSI           | B450M PRO-VDH MAX           | [059e0786bf](https://linux-hardware.org/?probe=059e0786bf) | Aug 11, 2022 |
| ASRock        | H110M-DGS R3.0              | [934583e785](https://linux-hardware.org/?probe=934583e785) | Aug 11, 2022 |
| Aquarius      | AQH310CM                    | [4084737708](https://linux-hardware.org/?probe=4084737708) | Aug 11, 2022 |
| MSI           | H110M PRO-VD                | [830489f44c](https://linux-hardware.org/?probe=830489f44c) | Aug 11, 2022 |
| Gigabyte      | B360M HD3                   | [d8432224a8](https://linux-hardware.org/?probe=d8432224a8) | Aug 11, 2022 |
| Gigabyte      | B360M HD3                   | [1325d40c4e](https://linux-hardware.org/?probe=1325d40c4e) | Aug 11, 2022 |
| ASRock        | H61M/U3S3                   | [be0d853621](https://linux-hardware.org/?probe=be0d853621) | Aug 11, 2022 |
| Gigabyte      | B450M DS3H V2               | [33dc68fe04](https://linux-hardware.org/?probe=33dc68fe04) | Aug 11, 2022 |
| ASUSTek       | H81T                        | [4049aa824c](https://linux-hardware.org/?probe=4049aa824c) | Aug 11, 2022 |
| ASRock        | G31M-S                      | [335a6f8616](https://linux-hardware.org/?probe=335a6f8616) | Aug 10, 2022 |
| MSI           | H81M-P33                    | [fd910dc3ca](https://linux-hardware.org/?probe=fd910dc3ca) | Aug 10, 2022 |
| MSI           | G41M-P28                    | [c20d54489d](https://linux-hardware.org/?probe=c20d54489d) | Aug 10, 2022 |
| Intel         | DP35DP AAD81073-207         | [3f55eb1ae4](https://linux-hardware.org/?probe=3f55eb1ae4) | Aug 10, 2022 |
| Intel         | DH87RL AAG74240-402         | [a83fd820d4](https://linux-hardware.org/?probe=a83fd820d4) | Aug 10, 2022 |
| MSI           | H81M-P33                    | [243392c01f](https://linux-hardware.org/?probe=243392c01f) | Aug 10, 2022 |
| ASUSTek       | Pro WS 565-ACE              | [ea9b6a4757](https://linux-hardware.org/?probe=ea9b6a4757) | Aug 10, 2022 |
| ASUSTek       | Pro WS 565-ACE              | [4e9256cf7f](https://linux-hardware.org/?probe=4e9256cf7f) | Aug 10, 2022 |
| Intel         | DH87RL AAG74240-402         | [8ea693190b](https://linux-hardware.org/?probe=8ea693190b) | Aug 09, 2022 |
| ASUSTek       | P8H61-M LX3                 | [19346d16de](https://linux-hardware.org/?probe=19346d16de) | Aug 09, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [1713317338](https://linux-hardware.org/?probe=1713317338) | Aug 09, 2022 |
| Gigabyte      | Z270-Gaming K3              | [b73567b27b](https://linux-hardware.org/?probe=b73567b27b) | Aug 09, 2022 |
| ASUSTek       | Z97M-PLUS/BR                | [b66253f362](https://linux-hardware.org/?probe=b66253f362) | Aug 09, 2022 |
| Gigabyte      | B550 GAMING X V2            | [fb01a8303f](https://linux-hardware.org/?probe=fb01a8303f) | Aug 08, 2022 |
| ASUSTek       | M5A88-V EVO                 | [b07157a232](https://linux-hardware.org/?probe=b07157a232) | Aug 08, 2022 |
| Unknown       | Unknown                     | [49c2378f28](https://linux-hardware.org/?probe=49c2378f28) | Aug 08, 2022 |
| Unknown       | Unknown                     | [9943b58e25](https://linux-hardware.org/?probe=9943b58e25) | Aug 08, 2022 |
| Foxconn       | G41MXP/G41MXP-V             | [91fb10e9c6](https://linux-hardware.org/?probe=91fb10e9c6) | Aug 08, 2022 |
| ECS           | G31T-M9                     | [6d24097613](https://linux-hardware.org/?probe=6d24097613) | Aug 08, 2022 |
| ASUSTek       | P8Z77-V                     | [18935d4aff](https://linux-hardware.org/?probe=18935d4aff) | Aug 07, 2022 |
| Gigabyte      | MZGLKAP-00                  | [5a349b05d2](https://linux-hardware.org/?probe=5a349b05d2) | Aug 07, 2022 |
| ASUSTek       | PRIME Z690M-HZ              | [67934f8ed6](https://linux-hardware.org/?probe=67934f8ed6) | Aug 07, 2022 |
| ASUSTek       | PRIME Z690M-HZ              | [d6d5cc239f](https://linux-hardware.org/?probe=d6d5cc239f) | Aug 07, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [468c10942e](https://linux-hardware.org/?probe=468c10942e) | Aug 06, 2022 |
| ECS           | G31T-M9                     | [8cdebd57de](https://linux-hardware.org/?probe=8cdebd57de) | Aug 05, 2022 |
| Gigabyte      | H81M-S2V                    | [696740d407](https://linux-hardware.org/?probe=696740d407) | Aug 05, 2022 |
| Lenovo        | 102F NO DPK                 | [1a040c2717](https://linux-hardware.org/?probe=1a040c2717) | Aug 04, 2022 |
| Intel         | X99                         | [33e0d23783](https://linux-hardware.org/?probe=33e0d23783) | Aug 04, 2022 |
| Foxconn       | 2AB1                        | [a2ebd67b7b](https://linux-hardware.org/?probe=a2ebd67b7b) | Aug 04, 2022 |
| ASUSTek       | P8H61-M LX3                 | [3d945110f8](https://linux-hardware.org/?probe=3d945110f8) | Aug 03, 2022 |
| ASUSTek       | Pro WS 565-ACE              | [d5e820b393](https://linux-hardware.org/?probe=d5e820b393) | Aug 03, 2022 |
| HP            | 8876 11                     | [150fcb8977](https://linux-hardware.org/?probe=150fcb8977) | Aug 03, 2022 |
| HP            | 8876 11                     | [029813dfc5](https://linux-hardware.org/?probe=029813dfc5) | Aug 03, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | [ca1d7dd61b](https://linux-hardware.org/?probe=ca1d7dd61b) | Aug 03, 2022 |
| Foxconn       | 2AB1                        | [74cd42b826](https://linux-hardware.org/?probe=74cd42b826) | Aug 03, 2022 |
| Lenovo        | 102F SDK0E50510 WIN 2625... | [80512402c0](https://linux-hardware.org/?probe=80512402c0) | Aug 02, 2022 |
| MSI           | Z97 GAMING 5                | [d2c534d06f](https://linux-hardware.org/?probe=d2c534d06f) | Aug 02, 2022 |
| ASUSTek       | P5G41T-M LE                 | [80c0577159](https://linux-hardware.org/?probe=80c0577159) | Aug 02, 2022 |
| Gigabyte      | H110M-Gaming3-CF            | [99a140d79b](https://linux-hardware.org/?probe=99a140d79b) | Aug 01, 2022 |
| ASRock        | H470M-HVS                   | [5282e92d2c](https://linux-hardware.org/?probe=5282e92d2c) | Aug 01, 2022 |
| ASUSTek       | P9X79                       | [4a518ab792](https://linux-hardware.org/?probe=4a518ab792) | Jul 31, 2022 |
| Gigabyte      | Z590 UD AC                  | [12cf4f1c81](https://linux-hardware.org/?probe=12cf4f1c81) | Jul 31, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [cc1944f4a3](https://linux-hardware.org/?probe=cc1944f4a3) | Jul 31, 2022 |
| Gigabyte      | A320M-H-CF                  | [5facb7723f](https://linux-hardware.org/?probe=5facb7723f) | Jul 30, 2022 |
| MSI           | MS-7418 100                 | [c17e48cc2b](https://linux-hardware.org/?probe=c17e48cc2b) | Jul 30, 2022 |
| MSI           | MS-7418 100                 | [4644e4eaa8](https://linux-hardware.org/?probe=4644e4eaa8) | Jul 30, 2022 |
| ASUSTek       | P8B75-M                     | [ddf26da899](https://linux-hardware.org/?probe=ddf26da899) | Jul 30, 2022 |
| ASUSTek       | P8H61-M LX3                 | [0cdabe4b69](https://linux-hardware.org/?probe=0cdabe4b69) | Jul 30, 2022 |
| ASUSTek       | STRIX Z270F GAMING          | [3b1f863612](https://linux-hardware.org/?probe=3b1f863612) | Jul 30, 2022 |
| Intel         | TR440BXA A16643-311         | [e6245255f4](https://linux-hardware.org/?probe=e6245255f4) | Jul 29, 2022 |
| MSI           | H110M PRO-VD                | [675b1fa2ff](https://linux-hardware.org/?probe=675b1fa2ff) | Jul 29, 2022 |
| ASUSTek       | B85M-E/DASH                 | [2ebbaa4052](https://linux-hardware.org/?probe=2ebbaa4052) | Jul 29, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [902ee3b350](https://linux-hardware.org/?probe=902ee3b350) | Jul 29, 2022 |
| AZW           | MINI S                      | [53ba28d9c3](https://linux-hardware.org/?probe=53ba28d9c3) | Jul 28, 2022 |
| AZW           | MINI S                      | [46216b2db1](https://linux-hardware.org/?probe=46216b2db1) | Jul 28, 2022 |
| MSI           | Z370 GAMING M5              | [b9ec9e3dd4](https://linux-hardware.org/?probe=b9ec9e3dd4) | Jul 28, 2022 |
| MSI           | X470 GAMING PLUS            | [8415a45799](https://linux-hardware.org/?probe=8415a45799) | Jul 28, 2022 |
| MSI           | PRO Z690-A DDR4             | [b5b5f049d0](https://linux-hardware.org/?probe=b5b5f049d0) | Jul 28, 2022 |
| HP            | ProLiant MicroServer        | [8104eee56e](https://linux-hardware.org/?probe=8104eee56e) | Jul 28, 2022 |
| ASUSTek       | P7P55D                      | [0c9828e226](https://linux-hardware.org/?probe=0c9828e226) | Jul 28, 2022 |
| ASUSTek       | H97-PRO                     | [ca77f59b41](https://linux-hardware.org/?probe=ca77f59b41) | Jul 28, 2022 |
| MSI           | H110M PRO-VD                | [33961c087b](https://linux-hardware.org/?probe=33961c087b) | Jul 28, 2022 |
| MSI           | X470 GAMING PLUS            | [88ac64a1bd](https://linux-hardware.org/?probe=88ac64a1bd) | Jul 28, 2022 |
| Gigabyte      | B660M GAMING DDR4           | [661a4a67d4](https://linux-hardware.org/?probe=661a4a67d4) | Jul 27, 2022 |
| ECS           | G31T-M9                     | [5537dcbed3](https://linux-hardware.org/?probe=5537dcbed3) | Jul 27, 2022 |
| Medion        | MS-7728                     | [662e3948f2](https://linux-hardware.org/?probe=662e3948f2) | Jul 27, 2022 |
| HP            | 0AACh                       | [d7df31df8c](https://linux-hardware.org/?probe=d7df31df8c) | Jul 26, 2022 |
| HP            | 0AACh                       | [357aa343ec](https://linux-hardware.org/?probe=357aa343ec) | Jul 26, 2022 |
| ASUSTek       | PRIME H310M-K               | [ba71ad5870](https://linux-hardware.org/?probe=ba71ad5870) | Jul 26, 2022 |
| ASRock        | H510M-HDV/M.2               | [e7672c215b](https://linux-hardware.org/?probe=e7672c215b) | Jul 26, 2022 |
| Gigabyte      | H61M-S1                     | [5e8e9fbd71](https://linux-hardware.org/?probe=5e8e9fbd71) | Jul 26, 2022 |
| ASUSTek       | P8B75-M                     | [46e85f96ca](https://linux-hardware.org/?probe=46e85f96ca) | Jul 26, 2022 |
| ASUSTek       | AT5NM10T-I                  | [9738c4bebc](https://linux-hardware.org/?probe=9738c4bebc) | Jul 26, 2022 |
| ASUSTek       | PRIME Z690M-HZ              | [9d3da43bea](https://linux-hardware.org/?probe=9d3da43bea) | Jul 25, 2022 |
| Dell          | 03NVJ6 A01                  | [3998c390f0](https://linux-hardware.org/?probe=3998c390f0) | Jul 25, 2022 |
| ASRock        | H470M Pro4                  | [5a709f059c](https://linux-hardware.org/?probe=5a709f059c) | Jul 25, 2022 |
| ASRockRack    | B565D4-V1L                  | [1301ad9bd0](https://linux-hardware.org/?probe=1301ad9bd0) | Jul 25, 2022 |
| Gigabyte      | B365M DS3H                  | [571655453a](https://linux-hardware.org/?probe=571655453a) | Jul 24, 2022 |
| AZW           | U59                         | [82e7dfdca5](https://linux-hardware.org/?probe=82e7dfdca5) | Jul 24, 2022 |
| ASUSTek       | TUF Gaming H570-PRO         | [36edefbce1](https://linux-hardware.org/?probe=36edefbce1) | Jul 24, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [de6f28d0f7](https://linux-hardware.org/?probe=de6f28d0f7) | Jul 24, 2022 |
| ASRock        | J5005-ITX                   | [8fdd045c35](https://linux-hardware.org/?probe=8fdd045c35) | Jul 24, 2022 |
| ASUSTek       | PRIME Z390-A                | [9a3ffce1a4](https://linux-hardware.org/?probe=9a3ffce1a4) | Jul 24, 2022 |
| ECS           | G31T-M9                     | [f7489c3b16](https://linux-hardware.org/?probe=f7489c3b16) | Jul 22, 2022 |
| MSI           | H110M PRO-VD                | [ffd65c627e](https://linux-hardware.org/?probe=ffd65c627e) | Jul 22, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | [7cd95094de](https://linux-hardware.org/?probe=7cd95094de) | Jul 21, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | [4655fe2442](https://linux-hardware.org/?probe=4655fe2442) | Jul 21, 2022 |
| MSI           | H110M PRO-VD                | [ffcc0670ba](https://linux-hardware.org/?probe=ffcc0670ba) | Jul 21, 2022 |
| Gigabyte      | M68MT-S2                    | [e505d3e2da](https://linux-hardware.org/?probe=e505d3e2da) | Jul 21, 2022 |
| MSI           | B150M BAZOOKA               | [41053f8c0e](https://linux-hardware.org/?probe=41053f8c0e) | Jul 21, 2022 |
| MSI           | G31TM-P21                   | [34b4e0a6ea](https://linux-hardware.org/?probe=34b4e0a6ea) | Jul 21, 2022 |
| Gigabyte      | M68MT-S2                    | [de41a6c75f](https://linux-hardware.org/?probe=de41a6c75f) | Jul 21, 2022 |
| Intel         | DH67BL AAG10189-209         | [8b924d9018](https://linux-hardware.org/?probe=8b924d9018) | Jul 21, 2022 |
| Dell          | 0HD5W2 A01                  | [e2eca7122c](https://linux-hardware.org/?probe=e2eca7122c) | Jul 21, 2022 |
| Intel         | DH67BL AAG10189-209         | [d9ce312767](https://linux-hardware.org/?probe=d9ce312767) | Jul 20, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [8ad4c64b76](https://linux-hardware.org/?probe=8ad4c64b76) | Jul 20, 2022 |
| MSI           | MS-7236                     | [e824199021](https://linux-hardware.org/?probe=e824199021) | Jul 20, 2022 |
| ASUSTek       | Pro WS 565-ACE              | [b35dabeb45](https://linux-hardware.org/?probe=b35dabeb45) | Jul 20, 2022 |
| Acer          | Aspire TC-120               | [2625b243eb](https://linux-hardware.org/?probe=2625b243eb) | Jul 20, 2022 |
| Acer          | Aspire TC-120               | [25728e964b](https://linux-hardware.org/?probe=25728e964b) | Jul 20, 2022 |
| Thecus        | N2810 0001                  | [dd4d9fb1d5](https://linux-hardware.org/?probe=dd4d9fb1d5) | Jul 20, 2022 |
| Dell          | 07T4MC A11                  | [61d394116d](https://linux-hardware.org/?probe=61d394116d) | Jul 20, 2022 |
| Gigabyte      | B365M DS3H                  | [27bf18a32e](https://linux-hardware.org/?probe=27bf18a32e) | Jul 20, 2022 |
| Intel         | DH67BL AAG10189-209         | [ff8bfdfce1](https://linux-hardware.org/?probe=ff8bfdfce1) | Jul 19, 2022 |
| MSI           | H110M PRO-VD                | [ecf613ee2c](https://linux-hardware.org/?probe=ecf613ee2c) | Jul 19, 2022 |
| ASRock        | H470M-HVS                   | [2ccd5ab488](https://linux-hardware.org/?probe=2ccd5ab488) | Jul 19, 2022 |
| MSI           | H110M PRO-VD                | [069d79d670](https://linux-hardware.org/?probe=069d79d670) | Jul 19, 2022 |
| ASUSTek       | Z170M-PLUS                  | [85df5dd7a2](https://linux-hardware.org/?probe=85df5dd7a2) | Jul 19, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [4f256f41a7](https://linux-hardware.org/?probe=4f256f41a7) | Jul 19, 2022 |
| Gigabyte      | GA-880GM-UD2H               | [a5082efd70](https://linux-hardware.org/?probe=a5082efd70) | Jul 19, 2022 |
| Compaq        | 07A8h                       | [329d1b25c3](https://linux-hardware.org/?probe=329d1b25c3) | Jul 18, 2022 |
| MSI           | H110M PRO-VD                | [b9799fcb96](https://linux-hardware.org/?probe=b9799fcb96) | Jul 18, 2022 |
| ASUSTek       | P5K SE/EPU                  | [b2b12a6837](https://linux-hardware.org/?probe=b2b12a6837) | Jul 18, 2022 |
| ASUSTek       | P8Z77-V                     | [bb9f40d075](https://linux-hardware.org/?probe=bb9f40d075) | Jul 18, 2022 |
| ASRock        | X300M-STX                   | [150da602c4](https://linux-hardware.org/?probe=150da602c4) | Jul 17, 2022 |
| ASRock        | X300M-STX                   | [a46f6b3901](https://linux-hardware.org/?probe=a46f6b3901) | Jul 17, 2022 |
| Gigabyte      | F2A78M-DS2                  | [00a709911c](https://linux-hardware.org/?probe=00a709911c) | Jul 17, 2022 |
| Unknown       | Unknown                     | [e862207f95](https://linux-hardware.org/?probe=e862207f95) | Jul 15, 2022 |
| Gigabyte      | B450M S2H                   | [2fcccdc54a](https://linux-hardware.org/?probe=2fcccdc54a) | Jul 15, 2022 |
| HP            | 0B4Ch D                     | [a27d53815e](https://linux-hardware.org/?probe=a27d53815e) | Jul 15, 2022 |
| ASUSTek       | P8H61/USB3 R2.0             | [e53d3eb407](https://linux-hardware.org/?probe=e53d3eb407) | Jul 15, 2022 |
| Gigabyte      | B250M-DS3H-CF               | [85f6b3a720](https://linux-hardware.org/?probe=85f6b3a720) | Jul 14, 2022 |
| Intel         | DH67BL AAG10189-209         | [15c0aec8fc](https://linux-hardware.org/?probe=15c0aec8fc) | Jul 14, 2022 |
| Gigabyte      | H61M-DS2                    | [d0f1a65579](https://linux-hardware.org/?probe=d0f1a65579) | Jul 14, 2022 |
| Dell          | 09D2HH A00                  | [aadb1249e7](https://linux-hardware.org/?probe=aadb1249e7) | Jul 13, 2022 |
| Gigabyte      | H61M-DS2                    | [d581679f95](https://linux-hardware.org/?probe=d581679f95) | Jul 13, 2022 |
| ASUSTek       | H110M-R                     | [b1ec1ae2ba](https://linux-hardware.org/?probe=b1ec1ae2ba) | Jul 13, 2022 |
| ASRock        | H470M-HVS                   | [8f07cb2956](https://linux-hardware.org/?probe=8f07cb2956) | Jul 13, 2022 |
| Gigabyte      | B450M S2H                   | [0287348f80](https://linux-hardware.org/?probe=0287348f80) | Jul 12, 2022 |
| ASUSTek       | Maximus VIII HERO           | [491e37bdfb](https://linux-hardware.org/?probe=491e37bdfb) | Jul 12, 2022 |
| Dell          | 0N4YC8 A00                  | [7bee96ebd2](https://linux-hardware.org/?probe=7bee96ebd2) | Jul 12, 2022 |
| ECS           | G31T-M9                     | [3465370e70](https://linux-hardware.org/?probe=3465370e70) | Jul 11, 2022 |
| MSI           | H110M PRO-VD                | [4fd6d22bdc](https://linux-hardware.org/?probe=4fd6d22bdc) | Jul 11, 2022 |
| ASRock        | H470M-HVS                   | [d670acc906](https://linux-hardware.org/?probe=d670acc906) | Jul 11, 2022 |
| ASUSTek       | TUF B450M-PRO GAMING        | [33c06e2d9c](https://linux-hardware.org/?probe=33c06e2d9c) | Jul 11, 2022 |
| MSI           | H110M PRO-VD                | [56a2a5762d](https://linux-hardware.org/?probe=56a2a5762d) | Jul 11, 2022 |
| MSI           | B350 GAMING PLUS            | [778b1989d4](https://linux-hardware.org/?probe=778b1989d4) | Jul 11, 2022 |
| ASUSTek       | PRIME Z690M-HZ              | [abf6dfebe1](https://linux-hardware.org/?probe=abf6dfebe1) | Jul 11, 2022 |
| ASUSTek       | PRIME Z690M-HZ              | [6aeac582a4](https://linux-hardware.org/?probe=6aeac582a4) | Jul 11, 2022 |
| Dell          | 042P49 A00                  | [58ae3712ed](https://linux-hardware.org/?probe=58ae3712ed) | Jul 10, 2022 |
| ASRock        | 990FX Killer                | [397d8bb63f](https://linux-hardware.org/?probe=397d8bb63f) | Jul 10, 2022 |
| ASRock        | Z77 Extreme6                | [fd8bd29c03](https://linux-hardware.org/?probe=fd8bd29c03) | Jul 09, 2022 |
| Lenovo        | 3132 SDK0R32862 WIN 3258... | [8c3180c6f5](https://linux-hardware.org/?probe=8c3180c6f5) | Jul 09, 2022 |
| Dell          | 0N4YC8 A00                  | [f83cbbc674](https://linux-hardware.org/?probe=f83cbbc674) | Jul 08, 2022 |
| ASRock        | H470M-HVS                   | [ec73826821](https://linux-hardware.org/?probe=ec73826821) | Jul 08, 2022 |
| ASRock        | H470M-HVS                   | [d6274d6dbb](https://linux-hardware.org/?probe=d6274d6dbb) | Jul 08, 2022 |
| ASRock        | H470M-HVS                   | [0d57ba971f](https://linux-hardware.org/?probe=0d57ba971f) | Jul 08, 2022 |
| ASRock        | H470M-HVS                   | [1d775a2c62](https://linux-hardware.org/?probe=1d775a2c62) | Jul 08, 2022 |
| ASRock        | H470M-HVS                   | [74b436de8d](https://linux-hardware.org/?probe=74b436de8d) | Jul 08, 2022 |
| ASRock        | H470M-HVS                   | [8a7a7fc746](https://linux-hardware.org/?probe=8a7a7fc746) | Jul 08, 2022 |
| ASRock        | H470M-HVS                   | [cfbc35dc7d](https://linux-hardware.org/?probe=cfbc35dc7d) | Jul 08, 2022 |
| ASRock        | M3A UCC                     | [a7ffeac935](https://linux-hardware.org/?probe=a7ffeac935) | Jul 08, 2022 |
| Intel         | DH61CR AAG14064-204         | [0ebf0eb484](https://linux-hardware.org/?probe=0ebf0eb484) | Jul 08, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [28a59cd061](https://linux-hardware.org/?probe=28a59cd061) | Jul 07, 2022 |
| Intel         | DQ35MP AAD82086-801         | [1f861ad92a](https://linux-hardware.org/?probe=1f861ad92a) | Jul 07, 2022 |
| ASRock        | B450M Pro4                  | [ff75212757](https://linux-hardware.org/?probe=ff75212757) | Jul 07, 2022 |
| Inventec      | D CLASS A02                 | [0fecc82851](https://linux-hardware.org/?probe=0fecc82851) | Jul 06, 2022 |
| congatec      | TS170 B.0                   | [b9469e26f8](https://linux-hardware.org/?probe=b9469e26f8) | Jul 06, 2022 |
| Gigabyte      | X99-UD4-CF                  | [5ac5b5f182](https://linux-hardware.org/?probe=5ac5b5f182) | Jul 06, 2022 |
| ECS           | G31T-M9                     | [f075057e96](https://linux-hardware.org/?probe=f075057e96) | Jul 06, 2022 |
| ASRockRack    | B565D4-V1L                  | [a363492ad6](https://linux-hardware.org/?probe=a363492ad6) | Jul 06, 2022 |
| Gigabyte      | B450M S2H V2                | [5da0f57567](https://linux-hardware.org/?probe=5da0f57567) | Jul 06, 2022 |
| MSI           | Creator TRX40               | [8d512a1405](https://linux-hardware.org/?probe=8d512a1405) | Jul 06, 2022 |
| ASRock        | K10N78D                     | [650465a972](https://linux-hardware.org/?probe=650465a972) | Jul 06, 2022 |
| Gigabyte      | B450M DS3H-CF               | [5636dc957a](https://linux-hardware.org/?probe=5636dc957a) | Jul 05, 2022 |
| HP            | 8433 11                     | [308e487f48](https://linux-hardware.org/?probe=308e487f48) | Jul 05, 2022 |
| MSI           | H61M-P31/W8                 | [ae5c00cbd0](https://linux-hardware.org/?probe=ae5c00cbd0) | Jul 05, 2022 |
| MSI           | H110M PRO-VD                | [cf4ef3e43e](https://linux-hardware.org/?probe=cf4ef3e43e) | Jul 05, 2022 |
| ASUSTek       | H97-PLUS                    | [07a45bcfef](https://linux-hardware.org/?probe=07a45bcfef) | Jul 04, 2022 |
| Intel         | MAHOBAY                     | [39c0379cee](https://linux-hardware.org/?probe=39c0379cee) | Jul 04, 2022 |
| MSI           | H510M-A PRO                 | [12a1f193b8](https://linux-hardware.org/?probe=12a1f193b8) | Jul 04, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [9fd928b97f](https://linux-hardware.org/?probe=9fd928b97f) | Jul 03, 2022 |
| Gigabyte      | 945GCM-S2L                  | [2d627ba67d](https://linux-hardware.org/?probe=2d627ba67d) | Jul 03, 2022 |
| BESSTAR Te... | HM90                        | [064e176be8](https://linux-hardware.org/?probe=064e176be8) | Jul 02, 2022 |
| ASUSTek       | H97-PLUS                    | [85de5cfaff](https://linux-hardware.org/?probe=85de5cfaff) | Jul 02, 2022 |
| MSI           | 880GMA-E35                  | [8bcc34797b](https://linux-hardware.org/?probe=8bcc34797b) | Jul 02, 2022 |
| ASRock        | B450M Pro4                  | [64eae559ae](https://linux-hardware.org/?probe=64eae559ae) | Jul 02, 2022 |
| Gigabyte      | H81M-DS2V                   | [5f35ee7109](https://linux-hardware.org/?probe=5f35ee7109) | Jul 01, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [d7d9387e6d](https://linux-hardware.org/?probe=d7d9387e6d) | Jul 01, 2022 |
| Gigabyte      | B85M-D3H                    | [d0d9e7b5c7](https://linux-hardware.org/?probe=d0d9e7b5c7) | Jul 01, 2022 |
| MSI           | B75MA-E33                   | [482aec0a52](https://linux-hardware.org/?probe=482aec0a52) | Jun 30, 2022 |
| ASUSTek       | P5KPL-E                     | [c969c7cce8](https://linux-hardware.org/?probe=c969c7cce8) | Jun 30, 2022 |
| Dell          | 0D441T A01                  | [b205bc201e](https://linux-hardware.org/?probe=b205bc201e) | Jun 29, 2022 |
| Dell          | 0M858N A01                  | [6cc8dcd51e](https://linux-hardware.org/?probe=6cc8dcd51e) | Jun 29, 2022 |
| Gigabyte      | B150-HD3 DDR3-CF            | [3fe71d66c6](https://linux-hardware.org/?probe=3fe71d66c6) | Jun 28, 2022 |
| ECS           | G41T-M16                    | [5a3363d66f](https://linux-hardware.org/?probe=5a3363d66f) | Jun 28, 2022 |
| Intel         | D945PLRN AAD32731-404       | [d9519690b8](https://linux-hardware.org/?probe=d9519690b8) | Jun 28, 2022 |
| ASUSTek       | B85M-G                      | [642e677d05](https://linux-hardware.org/?probe=642e677d05) | Jun 27, 2022 |
| ASUSTek       | PRIME B450M-A               | [60810eb934](https://linux-hardware.org/?probe=60810eb934) | Jun 27, 2022 |
| ASUSTek       | PRIME B450M-A               | [6ab12fa31e](https://linux-hardware.org/?probe=6ab12fa31e) | Jun 27, 2022 |
| Maxtang       | FP30 V1.0                   | [6d86a132d4](https://linux-hardware.org/?probe=6d86a132d4) | Jun 26, 2022 |
| ASUSTek       | P8Z77-V PRO                 | [838a928e6a](https://linux-hardware.org/?probe=838a928e6a) | Jun 26, 2022 |
| Gigabyte      | M52LT-D3                    | [6c650dabf3](https://linux-hardware.org/?probe=6c650dabf3) | Jun 24, 2022 |
| Gigabyte      | B150-HD3P-CF                | [c62062eac9](https://linux-hardware.org/?probe=c62062eac9) | Jun 24, 2022 |
| Intel         | MAHOBAY                     | [c292904665](https://linux-hardware.org/?probe=c292904665) | Jun 24, 2022 |
| Lenovo        | ThinkServer TS440           | [e68364c28e](https://linux-hardware.org/?probe=e68364c28e) | Jun 24, 2022 |
| Gigabyte      | H470M DS3H                  | [624ad307fc](https://linux-hardware.org/?probe=624ad307fc) | Jun 24, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [cf76d2d9a4](https://linux-hardware.org/?probe=cf76d2d9a4) | Jun 23, 2022 |
| HP            | 830C                        | [7e34e5c70d](https://linux-hardware.org/?probe=7e34e5c70d) | Jun 23, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | [c44391986b](https://linux-hardware.org/?probe=c44391986b) | Jun 23, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | [2c1f55aa8f](https://linux-hardware.org/?probe=2c1f55aa8f) | Jun 23, 2022 |
| ECS           | G31T-M9                     | [79e0e345f0](https://linux-hardware.org/?probe=79e0e345f0) | Jun 23, 2022 |
| Dell          | 0J8885                      | [06e5e2fe54](https://linux-hardware.org/?probe=06e5e2fe54) | Jun 23, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | [989b450d8b](https://linux-hardware.org/?probe=989b450d8b) | Jun 23, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | [39cc29c976](https://linux-hardware.org/?probe=39cc29c976) | Jun 23, 2022 |
| ASUSTek       | STRIX Z270F GAMING          | [d5d735e981](https://linux-hardware.org/?probe=d5d735e981) | Jun 22, 2022 |
| Gigabyte      | B660M GAMING X DDR4         | [d2d5590419](https://linux-hardware.org/?probe=d2d5590419) | Jun 22, 2022 |
| MSI           | H110M PRO-VD                | [a46ae32016](https://linux-hardware.org/?probe=a46ae32016) | Jun 22, 2022 |
| Gigabyte      | H97M-D3H                    | [1529cf29a5](https://linux-hardware.org/?probe=1529cf29a5) | Jun 22, 2022 |
| Gigabyte      | H97M-D3H                    | [4a2493f02c](https://linux-hardware.org/?probe=4a2493f02c) | Jun 22, 2022 |
| Unknown       | Unknown                     | [6024015ecc](https://linux-hardware.org/?probe=6024015ecc) | Jun 21, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [273f19137a](https://linux-hardware.org/?probe=273f19137a) | Jun 21, 2022 |
| ASUSTek       | H110M-R                     | [49fca67e16](https://linux-hardware.org/?probe=49fca67e16) | Jun 21, 2022 |
| ASUSTek       | P5KPL-AM SE                 | [fd01dae061](https://linux-hardware.org/?probe=fd01dae061) | Jun 21, 2022 |
| Gigabyte      | B360M H                     | [3b3898bab6](https://linux-hardware.org/?probe=3b3898bab6) | Jun 21, 2022 |
| Lenovo        | ThinkStation S20 4105J6G    | [3182b17f83](https://linux-hardware.org/?probe=3182b17f83) | Jun 21, 2022 |
| ASUSTek       | P5G41T-M LE                 | [2ff86ed754](https://linux-hardware.org/?probe=2ff86ed754) | Jun 21, 2022 |
| Intel         | CD952                       | [da181703fa](https://linux-hardware.org/?probe=da181703fa) | Jun 21, 2022 |
| Unknown       | Unknown                     | [604913c4e4](https://linux-hardware.org/?probe=604913c4e4) | Jun 20, 2022 |
| ASUSTek       | P5GC-MX/1333                | [e7527331d5](https://linux-hardware.org/?probe=e7527331d5) | Jun 20, 2022 |
| Foxconn       | G33M03                      | [e66dc33431](https://linux-hardware.org/?probe=e66dc33431) | Jun 20, 2022 |
| HP            | ProLiant ML350 G5           | [57a6a7a493](https://linux-hardware.org/?probe=57a6a7a493) | Jun 20, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [e6bd544051](https://linux-hardware.org/?probe=e6bd544051) | Jun 20, 2022 |
| Gigabyte      | B450M S2H                   | [deae1c7af7](https://linux-hardware.org/?probe=deae1c7af7) | Jun 19, 2022 |
| Lenovo        | ThinkServer TS440           | [42bf4b080d](https://linux-hardware.org/?probe=42bf4b080d) | Jun 19, 2022 |
| Lenovo        | 3132 SDK0R32862 WIN 3258... | [473e2262b2](https://linux-hardware.org/?probe=473e2262b2) | Jun 19, 2022 |
| Lenovo        | 3132 SDK0R32862 WIN 3258... | [83858f351b](https://linux-hardware.org/?probe=83858f351b) | Jun 19, 2022 |
| Dell          | 00V62H A00                  | [b902ece510](https://linux-hardware.org/?probe=b902ece510) | Jun 19, 2022 |
| ASUSTek       | KGPE-D16                    | [8a0bcff648](https://linux-hardware.org/?probe=8a0bcff648) | Jun 19, 2022 |
| ASUSTek       | KGPE-D16                    | [2ce805f758](https://linux-hardware.org/?probe=2ce805f758) | Jun 19, 2022 |
| ASUSTek       | Z77-A                       | [b416c587af](https://linux-hardware.org/?probe=b416c587af) | Jun 18, 2022 |
| Dell          | 0P9XHK A00                  | [e167c05dd2](https://linux-hardware.org/?probe=e167c05dd2) | Jun 17, 2022 |
| ASUSTek       | H110M-R                     | [575d907137](https://linux-hardware.org/?probe=575d907137) | Jun 17, 2022 |
| ASUSTek       | P5G41T-M LE                 | [9f392efe48](https://linux-hardware.org/?probe=9f392efe48) | Jun 17, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [eb011c0886](https://linux-hardware.org/?probe=eb011c0886) | Jun 17, 2022 |
| Dell          | 0NDYHG A01                  | [c4ed1ece70](https://linux-hardware.org/?probe=c4ed1ece70) | Jun 16, 2022 |
| Gigabyte      | B75-D3V                     | [3de9ecfb70](https://linux-hardware.org/?probe=3de9ecfb70) | Jun 16, 2022 |
| Gigabyte      | H81M-S2V                    | [de482da93c](https://linux-hardware.org/?probe=de482da93c) | Jun 15, 2022 |
| Gigabyte      | H81M-S2V                    | [2af43ca43d](https://linux-hardware.org/?probe=2af43ca43d) | Jun 15, 2022 |
| MSI           | H110M PRO-VD                | [9ac46f589f](https://linux-hardware.org/?probe=9ac46f589f) | Jun 14, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [0c8ec2807f](https://linux-hardware.org/?probe=0c8ec2807f) | Jun 14, 2022 |
| ASUSTek       | PRIME B360M-C               | [c250d3b2e0](https://linux-hardware.org/?probe=c250d3b2e0) | Jun 14, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [54800ad012](https://linux-hardware.org/?probe=54800ad012) | Jun 14, 2022 |
| ASUSTek       | P8Z68-V GEN3                | [863fc6a3bd](https://linux-hardware.org/?probe=863fc6a3bd) | Jun 14, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [cdbe0685be](https://linux-hardware.org/?probe=cdbe0685be) | Jun 13, 2022 |
| ASUSTek       | P8H77-M PRO                 | [674cb88747](https://linux-hardware.org/?probe=674cb88747) | Jun 13, 2022 |
| Supermicro    | X8STi                       | [d99d775afe](https://linux-hardware.org/?probe=d99d775afe) | Jun 12, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [3ddbde438b](https://linux-hardware.org/?probe=3ddbde438b) | Jun 12, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [b15a9cd9ec](https://linux-hardware.org/?probe=b15a9cd9ec) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [530d14088b](https://linux-hardware.org/?probe=530d14088b) | Jun 11, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [55be0755f9](https://linux-hardware.org/?probe=55be0755f9) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [288ab3a8ad](https://linux-hardware.org/?probe=288ab3a8ad) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [e7931e1d59](https://linux-hardware.org/?probe=e7931e1d59) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [4624e51d0d](https://linux-hardware.org/?probe=4624e51d0d) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [4d5e823219](https://linux-hardware.org/?probe=4d5e823219) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [d185e26655](https://linux-hardware.org/?probe=d185e26655) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [c184039865](https://linux-hardware.org/?probe=c184039865) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [96026aee3c](https://linux-hardware.org/?probe=96026aee3c) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [a7feb8b173](https://linux-hardware.org/?probe=a7feb8b173) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [8cf2ab21a1](https://linux-hardware.org/?probe=8cf2ab21a1) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [361ad1fd01](https://linux-hardware.org/?probe=361ad1fd01) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [2f0948a486](https://linux-hardware.org/?probe=2f0948a486) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [cbe79f811b](https://linux-hardware.org/?probe=cbe79f811b) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [128a4f95b3](https://linux-hardware.org/?probe=128a4f95b3) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [62c847aae6](https://linux-hardware.org/?probe=62c847aae6) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [0cdb0bc0ec](https://linux-hardware.org/?probe=0cdb0bc0ec) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [c6ea351f57](https://linux-hardware.org/?probe=c6ea351f57) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [a9a0fd0187](https://linux-hardware.org/?probe=a9a0fd0187) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [e0610fc3ee](https://linux-hardware.org/?probe=e0610fc3ee) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [17e9ad5909](https://linux-hardware.org/?probe=17e9ad5909) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [3ddd67d79c](https://linux-hardware.org/?probe=3ddd67d79c) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [52b1a2ddcc](https://linux-hardware.org/?probe=52b1a2ddcc) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [855eccf466](https://linux-hardware.org/?probe=855eccf466) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [8e97ffd0ce](https://linux-hardware.org/?probe=8e97ffd0ce) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [4c0f195f39](https://linux-hardware.org/?probe=4c0f195f39) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [e525f8832b](https://linux-hardware.org/?probe=e525f8832b) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [8511f3e652](https://linux-hardware.org/?probe=8511f3e652) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [44e4fe183c](https://linux-hardware.org/?probe=44e4fe183c) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [f8f771b95b](https://linux-hardware.org/?probe=f8f771b95b) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [3c70a63df1](https://linux-hardware.org/?probe=3c70a63df1) | Jun 11, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [ea7ec909e0](https://linux-hardware.org/?probe=ea7ec909e0) | Jun 11, 2022 |
| Dell          | 0TDG4V A01                  | [3da09dbe5d](https://linux-hardware.org/?probe=3da09dbe5d) | Jun 10, 2022 |
| ASRock        | G31M-VS2                    | [8da76dfd88](https://linux-hardware.org/?probe=8da76dfd88) | Jun 10, 2022 |
| Gigabyte      | H81M-DS2                    | [8f6316f63d](https://linux-hardware.org/?probe=8f6316f63d) | Jun 10, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [25b0162512](https://linux-hardware.org/?probe=25b0162512) | Jun 10, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [dec67b7ea7](https://linux-hardware.org/?probe=dec67b7ea7) | Jun 10, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [a1af74a271](https://linux-hardware.org/?probe=a1af74a271) | Jun 10, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [5863863487](https://linux-hardware.org/?probe=5863863487) | Jun 10, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [4dd447cf4a](https://linux-hardware.org/?probe=4dd447cf4a) | Jun 10, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [b248c80824](https://linux-hardware.org/?probe=b248c80824) | Jun 10, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [ec484ac5f1](https://linux-hardware.org/?probe=ec484ac5f1) | Jun 10, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [fbfb5f5567](https://linux-hardware.org/?probe=fbfb5f5567) | Jun 10, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [69177b9dd1](https://linux-hardware.org/?probe=69177b9dd1) | Jun 10, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [7b37f934d9](https://linux-hardware.org/?probe=7b37f934d9) | Jun 10, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [f81bbaa809](https://linux-hardware.org/?probe=f81bbaa809) | Jun 10, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [53cde78383](https://linux-hardware.org/?probe=53cde78383) | Jun 10, 2022 |
| Gigabyte      | H410M S2H                   | [958add1814](https://linux-hardware.org/?probe=958add1814) | Jun 10, 2022 |
| Gigabyte      | H410M S2H                   | [0045fbc083](https://linux-hardware.org/?probe=0045fbc083) | Jun 10, 2022 |
| Gigabyte      | H410M S2H                   | [4e319d922b](https://linux-hardware.org/?probe=4e319d922b) | Jun 10, 2022 |
| Gigabyte      | H410M S2H                   | [6d0ab85ca8](https://linux-hardware.org/?probe=6d0ab85ca8) | Jun 10, 2022 |
| Gigabyte      | H410M S2H                   | [057d965770](https://linux-hardware.org/?probe=057d965770) | Jun 10, 2022 |
| Gigabyte      | H410M S2H                   | [e6c10e7c75](https://linux-hardware.org/?probe=e6c10e7c75) | Jun 10, 2022 |
| Gigabyte      | H410M S2H                   | [aa239405c6](https://linux-hardware.org/?probe=aa239405c6) | Jun 10, 2022 |
| Gigabyte      | H410M S2H                   | [c581adfc75](https://linux-hardware.org/?probe=c581adfc75) | Jun 10, 2022 |
| Gigabyte      | H410M S2H                   | [495a331678](https://linux-hardware.org/?probe=495a331678) | Jun 10, 2022 |
| Gigabyte      | H410M S2H                   | [50d4873224](https://linux-hardware.org/?probe=50d4873224) | Jun 10, 2022 |
| Dell          | 0X75JG A01                  | [04a5e20d9e](https://linux-hardware.org/?probe=04a5e20d9e) | Jun 10, 2022 |
| MSI           | X99S GAMING 7               | [d36fec156a](https://linux-hardware.org/?probe=d36fec156a) | Jun 10, 2022 |
| ASRock        | 970 Performance             | [d017602bb8](https://linux-hardware.org/?probe=d017602bb8) | Jun 10, 2022 |
| ASRock        | 970 Performance             | [a2afdf2651](https://linux-hardware.org/?probe=a2afdf2651) | Jun 10, 2022 |
| ASRockRack    | X470D4U                     | [bdf16fa487](https://linux-hardware.org/?probe=bdf16fa487) | Jun 09, 2022 |
| Gigabyte      | B360M H                     | [94843ffed7](https://linux-hardware.org/?probe=94843ffed7) | Jun 09, 2022 |
| MSI           | H110M PRO-VD                | [d731f8ac03](https://linux-hardware.org/?probe=d731f8ac03) | Jun 09, 2022 |
| ASUSTek       | P5G41T-M LE                 | [6ae73c0b67](https://linux-hardware.org/?probe=6ae73c0b67) | Jun 09, 2022 |
| HP            | 085Ch                       | [357911a814](https://linux-hardware.org/?probe=357911a814) | Jun 08, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [6daae3f4db](https://linux-hardware.org/?probe=6daae3f4db) | Jun 08, 2022 |
| MSI           | H110M PRO-VD                | [aac1519759](https://linux-hardware.org/?probe=aac1519759) | Jun 08, 2022 |
| ASRock        | H470M-HVS                   | [0de4237fba](https://linux-hardware.org/?probe=0de4237fba) | Jun 08, 2022 |
| MSI           | H110M PRO-VD                | [0f1129c5f3](https://linux-hardware.org/?probe=0f1129c5f3) | Jun 08, 2022 |
| ASUSTek       | H110M-R                     | [75c023ebe1](https://linux-hardware.org/?probe=75c023ebe1) | Jun 08, 2022 |
| MSI           | H110M PRO-VH                | [ceae668577](https://linux-hardware.org/?probe=ceae668577) | Jun 07, 2022 |
| Gigabyte      | H81M-S2H                    | [4ca91078a2](https://linux-hardware.org/?probe=4ca91078a2) | Jun 07, 2022 |
| ASRock        | B365M Pro4-F                | [90b2505b78](https://linux-hardware.org/?probe=90b2505b78) | Jun 07, 2022 |
| MSI           | H110M PRO-VD                | [dbea5c81f2](https://linux-hardware.org/?probe=dbea5c81f2) | Jun 07, 2022 |
| ASUSTek       | B85M-G                      | [67662acc02](https://linux-hardware.org/?probe=67662acc02) | Jun 07, 2022 |
| MSI           | H81M-E33                    | [b2ce1d66a3](https://linux-hardware.org/?probe=b2ce1d66a3) | Jun 07, 2022 |
| ASRock        | B85M Pro3                   | [929408f1cd](https://linux-hardware.org/?probe=929408f1cd) | Jun 07, 2022 |
| Dell          | 040DDP A01                  | [94cce73a9d](https://linux-hardware.org/?probe=94cce73a9d) | Jun 07, 2022 |
| ASRock        | B365M Pro4-F                | [722cfa9375](https://linux-hardware.org/?probe=722cfa9375) | Jun 06, 2022 |
| PC Engines    | APU2                        | [269fa69513](https://linux-hardware.org/?probe=269fa69513) | Jun 06, 2022 |
| ASUSTek       | P8H61-MX                    | [a1b3220a4e](https://linux-hardware.org/?probe=a1b3220a4e) | Jun 06, 2022 |
| ASRock        | H310CM-DVS                  | [2c46c3adb2](https://linux-hardware.org/?probe=2c46c3adb2) | Jun 06, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [9998592ce0](https://linux-hardware.org/?probe=9998592ce0) | Jun 06, 2022 |
| MSI           | B450M PRO-VDH MAX           | [2aeb22bc4b](https://linux-hardware.org/?probe=2aeb22bc4b) | Jun 06, 2022 |
| Gigabyte      | A320M-S2H-CF                | [e3c84aefa8](https://linux-hardware.org/?probe=e3c84aefa8) | Jun 05, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [0948fcded8](https://linux-hardware.org/?probe=0948fcded8) | Jun 05, 2022 |
| Dell          | 0WR7PY A01                  | [39c37e56ec](https://linux-hardware.org/?probe=39c37e56ec) | Jun 04, 2022 |
| ASUSTek       | PRIME B360M-C               | [b57fa63f1a](https://linux-hardware.org/?probe=b57fa63f1a) | Jun 04, 2022 |
| BESSTAR Te... | HM90                        | [5272429aa9](https://linux-hardware.org/?probe=5272429aa9) | Jun 04, 2022 |
| Gigabyte      | H61M-USB3H                  | [1f88a2c07c](https://linux-hardware.org/?probe=1f88a2c07c) | Jun 04, 2022 |
| Gigabyte      | H61M-USB3H                  | [3cc513c431](https://linux-hardware.org/?probe=3cc513c431) | Jun 04, 2022 |
| ASUSTek       | PRIME A320M-A               | [b610820278](https://linux-hardware.org/?probe=b610820278) | Jun 03, 2022 |
| Gigabyte      | B360M H                     | [8f5cd5eef5](https://linux-hardware.org/?probe=8f5cd5eef5) | Jun 03, 2022 |
| Gigabyte      | B360M H                     | [3cd0f35827](https://linux-hardware.org/?probe=3cd0f35827) | Jun 03, 2022 |
| Gigabyte      | M61PME-S2P                  | [a56a39a60e](https://linux-hardware.org/?probe=a56a39a60e) | Jun 03, 2022 |
| MSI           | H81M-P33                    | [c7974d4e6d](https://linux-hardware.org/?probe=c7974d4e6d) | Jun 03, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [b20f8a904c](https://linux-hardware.org/?probe=b20f8a904c) | Jun 03, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [deaecc76bb](https://linux-hardware.org/?probe=deaecc76bb) | Jun 03, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [65725a95b9](https://linux-hardware.org/?probe=65725a95b9) | Jun 03, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [a4622d1f55](https://linux-hardware.org/?probe=a4622d1f55) | Jun 03, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [e8019b4f83](https://linux-hardware.org/?probe=e8019b4f83) | Jun 03, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [afba735e60](https://linux-hardware.org/?probe=afba735e60) | Jun 03, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [7f34664fe0](https://linux-hardware.org/?probe=7f34664fe0) | Jun 03, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [feaafa4cfa](https://linux-hardware.org/?probe=feaafa4cfa) | Jun 03, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [61260328d6](https://linux-hardware.org/?probe=61260328d6) | Jun 03, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [5dcef6967d](https://linux-hardware.org/?probe=5dcef6967d) | Jun 03, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [3a2e3ed469](https://linux-hardware.org/?probe=3a2e3ed469) | Jun 03, 2022 |
| Gigabyte      | H57M-USB3                   | [ad3c50375c](https://linux-hardware.org/?probe=ad3c50375c) | Jun 03, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [7725e74369](https://linux-hardware.org/?probe=7725e74369) | Jun 02, 2022 |
| MSI           | H110M PRO-VD                | [cd124df84c](https://linux-hardware.org/?probe=cd124df84c) | Jun 02, 2022 |
| Gigabyte      | M68MT-S2                    | [c71933a046](https://linux-hardware.org/?probe=c71933a046) | Jun 02, 2022 |
| Lenovo        | 3132 SDK0R32862 WIN 3258... | [459a6a7c75](https://linux-hardware.org/?probe=459a6a7c75) | Jun 02, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | [b9eb4d507e](https://linux-hardware.org/?probe=b9eb4d507e) | Jun 02, 2022 |
| Dell          | 0J8885                      | [1b1eafbd15](https://linux-hardware.org/?probe=1b1eafbd15) | Jun 01, 2022 |
| Gigabyte      | 970A-DS3P                   | [272322b54a](https://linux-hardware.org/?probe=272322b54a) | Jun 01, 2022 |
| ASRock        | A320M-HDV R3.0              | [1b402ad8a4](https://linux-hardware.org/?probe=1b402ad8a4) | Jun 01, 2022 |
| Unknown       | Unknown                     | [bcb55ce8ce](https://linux-hardware.org/?probe=bcb55ce8ce) | Jun 01, 2022 |
| Gigabyte      | M68MT-S2                    | [24ef5903aa](https://linux-hardware.org/?probe=24ef5903aa) | Jun 01, 2022 |
| Intel         | DH61BF AAG81311-101         | [b1fe95fd93](https://linux-hardware.org/?probe=b1fe95fd93) | May 31, 2022 |
| HP            | ProLiant ML110 Gen9         | [2940e1d0b2](https://linux-hardware.org/?probe=2940e1d0b2) | May 31, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [4dad4a323a](https://linux-hardware.org/?probe=4dad4a323a) | May 31, 2022 |
| MSI           | A320M-HDV R4.0              | [c6f912a3cd](https://linux-hardware.org/?probe=c6f912a3cd) | May 31, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [c60a969370](https://linux-hardware.org/?probe=c60a969370) | May 31, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [7bd2b1490a](https://linux-hardware.org/?probe=7bd2b1490a) | May 31, 2022 |
| ASUSTek       | P7H55-M SI                  | [bd7e895652](https://linux-hardware.org/?probe=bd7e895652) | May 31, 2022 |
| MSI           | G31TM-P21                   | [3ddbd38a08](https://linux-hardware.org/?probe=3ddbd38a08) | May 31, 2022 |
| Gigabyte      | M61PME-S2P                  | [6960eaa85b](https://linux-hardware.org/?probe=6960eaa85b) | May 31, 2022 |
| HP            | 158A                        | [7f7c6ae514](https://linux-hardware.org/?probe=7f7c6ae514) | May 31, 2022 |
| Gigabyte      | H61M-S2-B3                  | [3de5695c62](https://linux-hardware.org/?probe=3de5695c62) | May 30, 2022 |
| Gigabyte      | H61M-S2PV                   | [b002ab0fe8](https://linux-hardware.org/?probe=b002ab0fe8) | May 30, 2022 |
| Gigabyte      | M52L-S3                     | [1add8e904e](https://linux-hardware.org/?probe=1add8e904e) | May 30, 2022 |
| Gigabyte      | H61M-S2PV                   | [990a8757b8](https://linux-hardware.org/?probe=990a8757b8) | May 30, 2022 |
| Gigabyte      | M52L-S3                     | [e49b2962df](https://linux-hardware.org/?probe=e49b2962df) | May 30, 2022 |
| ASRock        | H470M-HVS                   | [b7404d28e0](https://linux-hardware.org/?probe=b7404d28e0) | May 30, 2022 |
| ASRock        | B450M-HDV R4.0              | [b6d663fde6](https://linux-hardware.org/?probe=b6d663fde6) | May 29, 2022 |
| MSI           | MAG B550M BAZOOKA           | [9399a639c8](https://linux-hardware.org/?probe=9399a639c8) | May 29, 2022 |
| Biostar       | X470GTQ                     | [44e1072418](https://linux-hardware.org/?probe=44e1072418) | May 28, 2022 |
| HP            | 213D A01                    | [1be94a04b6](https://linux-hardware.org/?probe=1be94a04b6) | May 28, 2022 |
| BESSTAR Te... | HM80                        | [f507d65c2e](https://linux-hardware.org/?probe=f507d65c2e) | May 28, 2022 |
| Gigabyte      | B450M DS3H-CF               | [ed9c55ffc6](https://linux-hardware.org/?probe=ed9c55ffc6) | May 28, 2022 |
| MSI           | MAG B550M BAZOOKA           | [42b16ce834](https://linux-hardware.org/?probe=42b16ce834) | May 28, 2022 |
| MSI           | MAG B550M BAZOOKA           | [4620e51e7b](https://linux-hardware.org/?probe=4620e51e7b) | May 28, 2022 |
| ASRock        | AM2NF6G-VSTA                | [475179d795](https://linux-hardware.org/?probe=475179d795) | May 27, 2022 |
| MSI           | H110M PRO-VD                | [6c505927be](https://linux-hardware.org/?probe=6c505927be) | May 27, 2022 |
| Gigabyte      | B85M-D3H                    | [dc5f3161bd](https://linux-hardware.org/?probe=dc5f3161bd) | May 27, 2022 |
| ASRock        | 970M Pro3                   | [7c13c36e57](https://linux-hardware.org/?probe=7c13c36e57) | May 27, 2022 |
| ECS           | H61H2-M13                   | [6c5eea6e0a](https://linux-hardware.org/?probe=6c5eea6e0a) | May 27, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [e28ecda6a9](https://linux-hardware.org/?probe=e28ecda6a9) | May 27, 2022 |
| ASRock        | IMB-185                     | [f7b3b565a0](https://linux-hardware.org/?probe=f7b3b565a0) | May 27, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [5b4a1a0b2d](https://linux-hardware.org/?probe=5b4a1a0b2d) | May 27, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [8a9debf1da](https://linux-hardware.org/?probe=8a9debf1da) | May 27, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [c34cf96051](https://linux-hardware.org/?probe=c34cf96051) | May 27, 2022 |
| Gigabyte      | H110M-S2H-CF                | [305a4aa2be](https://linux-hardware.org/?probe=305a4aa2be) | May 26, 2022 |
| Gigabyte      | H410M S2H                   | [c7e011235c](https://linux-hardware.org/?probe=c7e011235c) | May 26, 2022 |
| MSI           | H110M PRO-VD                | [f50e4f5314](https://linux-hardware.org/?probe=f50e4f5314) | May 26, 2022 |
| ASRock        | H470M-HVS                   | [134bd88895](https://linux-hardware.org/?probe=134bd88895) | May 26, 2022 |
| Gigabyte      | Z77-DS3H                    | [fe6eb0ff04](https://linux-hardware.org/?probe=fe6eb0ff04) | May 26, 2022 |
| ASUSTek       | H81M-K                      | [3fc005308d](https://linux-hardware.org/?probe=3fc005308d) | May 26, 2022 |
| Intel         | DZ77SL-50K AAG55115-300     | [a05a4109f7](https://linux-hardware.org/?probe=a05a4109f7) | May 26, 2022 |
| Gigabyte      | Z590 AORUS ULTRA            | [544888143f](https://linux-hardware.org/?probe=544888143f) | May 25, 2022 |
| ECS           | G31T-M9                     | [cbc52e0724](https://linux-hardware.org/?probe=cbc52e0724) | May 25, 2022 |
| Foxconn       | H61MXL/H61MXL-K             | [c44b877046](https://linux-hardware.org/?probe=c44b877046) | May 25, 2022 |
| ASUSTek       | M4A785TD-V EVO              | [29dd7760ba](https://linux-hardware.org/?probe=29dd7760ba) | May 25, 2022 |
| Packard Be... | IMEDIA S3840                | [d102437a6f](https://linux-hardware.org/?probe=d102437a6f) | May 25, 2022 |
| Foxconn       | G31MXP FAB:1.1              | [64552194de](https://linux-hardware.org/?probe=64552194de) | May 24, 2022 |
| Gigabyte      | H510M H                     | [4bf981574e](https://linux-hardware.org/?probe=4bf981574e) | May 24, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [ca5eb0e4ff](https://linux-hardware.org/?probe=ca5eb0e4ff) | May 24, 2022 |
| ASUSTek       | Z97M-PLUS/BR                | [66b8c4e68c](https://linux-hardware.org/?probe=66b8c4e68c) | May 24, 2022 |
| MSI           | H110M PRO-VD                | [5f3d17f133](https://linux-hardware.org/?probe=5f3d17f133) | May 24, 2022 |
| Gigabyte      | H61M-DS2                    | [1613ab8b42](https://linux-hardware.org/?probe=1613ab8b42) | May 23, 2022 |
| ASRock        | H470M-HVS                   | [0e8f0ed773](https://linux-hardware.org/?probe=0e8f0ed773) | May 23, 2022 |
| ASRock        | H470M-HVS                   | [193d7daf36](https://linux-hardware.org/?probe=193d7daf36) | May 23, 2022 |
| ASRock        | H470M-HVS                   | [ea8294c786](https://linux-hardware.org/?probe=ea8294c786) | May 23, 2022 |
| ASRock        | H470M-HVS                   | [a888bc633f](https://linux-hardware.org/?probe=a888bc633f) | May 23, 2022 |
| ASRock        | H470M-HVS                   | [6bfc4ef24f](https://linux-hardware.org/?probe=6bfc4ef24f) | May 23, 2022 |
| ASRock        | H470M-HVS                   | [3629d7c796](https://linux-hardware.org/?probe=3629d7c796) | May 23, 2022 |
| ASRock        | H470M-HVS                   | [9938056162](https://linux-hardware.org/?probe=9938056162) | May 23, 2022 |
| ASRock        | H470M-HVS                   | [02393f8ed7](https://linux-hardware.org/?probe=02393f8ed7) | May 23, 2022 |
| ASRock        | H470M-HVS                   | [3c545f2940](https://linux-hardware.org/?probe=3c545f2940) | May 23, 2022 |
| ECS           | H61H2-MV                    | [13918cd2b7](https://linux-hardware.org/?probe=13918cd2b7) | May 23, 2022 |
| MSI           | H81M-P33                    | [5694eb0d0e](https://linux-hardware.org/?probe=5694eb0d0e) | May 22, 2022 |
| Gigabyte      | G41MT-S2                    | [0245a34484](https://linux-hardware.org/?probe=0245a34484) | May 20, 2022 |
| ASUSTek       | H81M-R                      | [d29d7ee0ad](https://linux-hardware.org/?probe=d29d7ee0ad) | May 20, 2022 |
| Dell          | 0D6H9T A02                  | [3f87c84f7a](https://linux-hardware.org/?probe=3f87c84f7a) | May 20, 2022 |
| Intel         | CM-iAM/SBC-FITPC2i          | [cbfe433386](https://linux-hardware.org/?probe=cbfe433386) | May 20, 2022 |
| Apple         | Mac-F4208DC8 PVT            | [9330599ada](https://linux-hardware.org/?probe=9330599ada) | May 20, 2022 |
| MSI           | H110M PRO-VD                | [a9d54e08c9](https://linux-hardware.org/?probe=a9d54e08c9) | May 20, 2022 |
| Gigabyte      | X570S AORUS MASTER          | [d26b453c29](https://linux-hardware.org/?probe=d26b453c29) | May 20, 2022 |
| MSI           | B550-A PRO                  | [373569ca56](https://linux-hardware.org/?probe=373569ca56) | May 20, 2022 |
| HP            | 8298                        | [3f45b43adb](https://linux-hardware.org/?probe=3f45b43adb) | May 19, 2022 |
| ASRock        | H470M-HVS                   | [b78055bf57](https://linux-hardware.org/?probe=b78055bf57) | May 19, 2022 |
| HP            | 158A                        | [befd0b5756](https://linux-hardware.org/?probe=befd0b5756) | May 18, 2022 |
| Gigabyte      | B75-D3V                     | [81bd72f465](https://linux-hardware.org/?probe=81bd72f465) | May 18, 2022 |
| MouseCompu... | B360M-ITX                   | [bee48ca0b0](https://linux-hardware.org/?probe=bee48ca0b0) | May 18, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [05c3d14729](https://linux-hardware.org/?probe=05c3d14729) | May 18, 2022 |
| ASUSTek       | P8Z68-V                     | [4e8ebb2b51](https://linux-hardware.org/?probe=4e8ebb2b51) | May 17, 2022 |
| Gigabyte      | B75M-D2V                    | [6eba5e9bf2](https://linux-hardware.org/?probe=6eba5e9bf2) | May 17, 2022 |
| HP            | 1905                        | [eae1688df4](https://linux-hardware.org/?probe=eae1688df4) | May 17, 2022 |
| HP            | ProLiant MicroServer Gen... | [2a8a53c628](https://linux-hardware.org/?probe=2a8a53c628) | May 17, 2022 |
| ASRock        | H470M-HVS                   | [d71e59e4ef](https://linux-hardware.org/?probe=d71e59e4ef) | May 17, 2022 |
| Gigabyte      | G31M-ES2L                   | [1ab7586d5f](https://linux-hardware.org/?probe=1ab7586d5f) | May 17, 2022 |
| Dell          | 07N90W A01                  | [09d256b2ea](https://linux-hardware.org/?probe=09d256b2ea) | May 17, 2022 |
| ASUSTek       | Pro WS X570-ACE             | [79682a20fa](https://linux-hardware.org/?probe=79682a20fa) | May 16, 2022 |
| IP3 Tech      | TB20                        | [1cf2be0840](https://linux-hardware.org/?probe=1cf2be0840) | May 16, 2022 |
| Gigabyte      | B75M-D2V                    | [86de85c736](https://linux-hardware.org/?probe=86de85c736) | May 16, 2022 |
| Gigabyte      | H81M-S2V                    | [f5817a11ec](https://linux-hardware.org/?probe=f5817a11ec) | May 16, 2022 |
| Gigabyte      | X570S AORUS MASTER          | [e12a8b383f](https://linux-hardware.org/?probe=e12a8b383f) | May 16, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [587c1deb4c](https://linux-hardware.org/?probe=587c1deb4c) | May 15, 2022 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | [709552ce76](https://linux-hardware.org/?probe=709552ce76) | May 15, 2022 |
| Lenovo        | ThinkServer TS440           | [bde3f15809](https://linux-hardware.org/?probe=bde3f15809) | May 15, 2022 |
| Dell          | 0654JC A01                  | [ed0864a499](https://linux-hardware.org/?probe=ed0864a499) | May 14, 2022 |
| Dell          | 0654JC A01                  | [ed8e9e61b7](https://linux-hardware.org/?probe=ed8e9e61b7) | May 14, 2022 |
| Fujitsu       | D3813-A1 S26361-D3813-A1... | [f0e3c26d56](https://linux-hardware.org/?probe=f0e3c26d56) | May 14, 2022 |
| Dell          | 0JGM7F A00                  | [49bb61d936](https://linux-hardware.org/?probe=49bb61d936) | May 14, 2022 |
| Dell          | 0JGM7F A00                  | [1f5b1d9c0a](https://linux-hardware.org/?probe=1f5b1d9c0a) | May 14, 2022 |
| HP            | 2129                        | [d0babde387](https://linux-hardware.org/?probe=d0babde387) | May 14, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [e39a3d8da2](https://linux-hardware.org/?probe=e39a3d8da2) | May 14, 2022 |
| Dell          | 0HY9JP A02                  | [5f98aaf42c](https://linux-hardware.org/?probe=5f98aaf42c) | May 14, 2022 |
| ASUSTek       | ROG ZENITH II EXTREME AL... | [bc9270aeff](https://linux-hardware.org/?probe=bc9270aeff) | May 13, 2022 |
| MSI           | 870S-C45                    | [eefd6f4979](https://linux-hardware.org/?probe=eefd6f4979) | May 12, 2022 |
| ASRock        | B365M Pro4-F                | [75587e5d3e](https://linux-hardware.org/?probe=75587e5d3e) | May 12, 2022 |
| ASRockRack    | X399D8A-2T                  | [f1d2fbc435](https://linux-hardware.org/?probe=f1d2fbc435) | May 12, 2022 |
| Medion        | Z370H4-EM                   | [2030abcd26](https://linux-hardware.org/?probe=2030abcd26) | May 12, 2022 |
| ASUSTek       | ROG ZENITH II EXTREME AL... | [f0e5f896a4](https://linux-hardware.org/?probe=f0e5f896a4) | May 11, 2022 |
| ASRock        | H570M-ITX/ac                | [74f198b961](https://linux-hardware.org/?probe=74f198b961) | May 11, 2022 |
| MSI           | H97M-E35                    | [fdd0f51b46](https://linux-hardware.org/?probe=fdd0f51b46) | May 10, 2022 |
| Gigabyte      | H370M D3H-CF                | [ffc3d3cf27](https://linux-hardware.org/?probe=ffc3d3cf27) | May 10, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [8575f58f88](https://linux-hardware.org/?probe=8575f58f88) | May 10, 2022 |
| Dell          | 0KV3RP A00                  | [6ef8c2f171](https://linux-hardware.org/?probe=6ef8c2f171) | May 10, 2022 |
| ASUSTek       | PRIME H510M-E               | [0fed762686](https://linux-hardware.org/?probe=0fed762686) | May 10, 2022 |
| Dell          | 0J37VM A01                  | [a5363ae511](https://linux-hardware.org/?probe=a5363ae511) | May 09, 2022 |
| ASUSTek       | PRIME H510M-A               | [1e2ee4a2fb](https://linux-hardware.org/?probe=1e2ee4a2fb) | May 09, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian_11/Desktop/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 5.10.0-7-amd64         | 505      | 26.83%  |
| 5.10.0-8-amd64         | 229      | 12.17%  |
| 5.10.0-9-amd64         | 117      | 6.22%   |
| 5.10.0-13-amd64        | 84       | 4.46%   |
| 5.10.0-2-amd64         | 77       | 4.09%   |
| 5.10.0-11-amd64        | 71       | 3.77%   |
| 5.10.0-18-amd64        | 70       | 3.72%   |
| 5.10.0-10-amd64        | 69       | 3.67%   |
| 5.10.0-16-amd64        | 67       | 3.56%   |
| 5.10.0-19-amd64        | 60       | 3.19%   |
| 5.10.0-14-amd64        | 47       | 2.5%    |
| 5.10.0-17-amd64        | 42       | 2.23%   |
| 5.10.0-15-amd64        | 30       | 1.59%   |
| 5.10.0-12-amd64        | 29       | 1.54%   |
| 5.15.0-2-amd64         | 22       | 1.17%   |
| 5.18.0-0.bpo.1-amd64   | 15       | 0.8%    |
| 5.16.0-0.bpo.4-amd64   | 15       | 0.8%    |
| 5.13.19-2-pve          | 14       | 0.74%   |
| 5.13.19-6-pve          | 13       | 0.69%   |
| 5.10.0-6-amd64         | 13       | 0.69%   |
| 5.18.0-0.deb11.4-amd64 | 12       | 0.64%   |
| 5.15.53-1-pve          | 10       | 0.53%   |
| 5.15.35-1-pve          | 9        | 0.48%   |
| 5.15.30-2-pve          | 9        | 0.48%   |
| 5.19.0-2-amd64         | 7        | 0.37%   |
| 5.14.0-0.bpo.2-amd64   | 7        | 0.37%   |
| 5.11.22-4-pve          | 7        | 0.37%   |
| 5.19.0-0.deb11.2-amd64 | 6        | 0.32%   |
| 5.15.39-4-pve          | 6        | 0.32%   |
| 5.13.19-1-pve          | 6        | 0.32%   |
| 5.15.39-1-pve          | 5        | 0.27%   |
| 5.10.0-9-686           | 5        | 0.27%   |
| 5.18.0-2-amd64         | 4        | 0.21%   |
| 5.17.0-1-amd64         | 4        | 0.21%   |
| 5.15.0-3-amd64         | 4        | 0.21%   |
| 5.13.19-3-pve          | 4        | 0.21%   |
| 5.10.0-8-686-pae       | 4        | 0.21%   |
| 5.10.0-4-amd64         | 4        | 0.21%   |
| 5.10.0-13-686-pae      | 4        | 0.21%   |
| 5.10.0-10-686-pae      | 4        | 0.21%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.10.0   | 1473     | 82.47%  |
| 5.18.0   | 38       | 2.13%   |
| 5.13.19  | 38       | 2.13%   |
| 5.15.0   | 33       | 1.85%   |
| 5.16.0   | 26       | 1.46%   |
| 5.11.22  | 17       | 0.95%   |
| 5.19.0   | 16       | 0.9%    |
| 5.14.0   | 15       | 0.84%   |
| 5.15.39  | 13       | 0.73%   |
| 5.15.35  | 13       | 0.73%   |
| 5.15.53  | 10       | 0.56%   |
| 5.17.0   | 9        | 0.5%    |
| 5.15.30  | 9        | 0.5%    |
| 6.0.0    | 5        | 0.28%   |
| 6.0.8    | 4        | 0.22%   |
| 5.13.0   | 4        | 0.22%   |
| 5.16.5   | 3        | 0.17%   |
| 5.15.60  | 3        | 0.17%   |
| 4.19.0   | 3        | 0.17%   |
| 5.15.64  | 2        | 0.11%   |
| 5.15.19  | 2        | 0.11%   |
| 5.15.12  | 2        | 0.11%   |
| 5.13.13  | 2        | 0.11%   |
| 5.11.0   | 2        | 0.11%   |
| 5.10.81  | 2        | 0.11%   |
| 5.10.57  | 2        | 0.11%   |
| 5.10.46  | 2        | 0.11%   |
| 5.10.109 | 2        | 0.11%   |
| 6.0.3    | 1        | 0.06%   |
| 5.8.0    | 1        | 0.06%   |
| 5.5.0    | 1        | 0.06%   |
| 5.4.148  | 1        | 0.06%   |
| 5.4.0    | 1        | 0.06%   |
| 5.19.8   | 1        | 0.06%   |
| 5.19.7   | 1        | 0.06%   |
| 5.19.11  | 1        | 0.06%   |
| 5.18.6   | 1        | 0.06%   |
| 5.18.5   | 1        | 0.06%   |
| 5.18.16  | 1        | 0.06%   |
| 5.18.15  | 1        | 0.06%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 1490     | 83.71%  |
| 5.15    | 85       | 4.78%   |
| 5.13    | 48       | 2.7%    |
| 5.18    | 42       | 2.36%   |
| 5.16    | 31       | 1.74%   |
| 5.11    | 20       | 1.12%   |
| 5.19    | 19       | 1.07%   |
| 5.14    | 16       | 0.9%    |
| 5.17    | 11       | 0.62%   |
| 6.0     | 9        | 0.51%   |
| 4.19    | 3        | 0.17%   |
| 5.4     | 2        | 0.11%   |
| 5.8     | 1        | 0.06%   |
| 5.5     | 1        | 0.06%   |
| 5.12    | 1        | 0.06%   |
| 5.1     | 1        | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 1704     | 97.48%  |
| i686    | 42       | 2.4%    |
| riscv64 | 1        | 0.06%   |
| armv7l  | 1        | 0.06%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Unknown          | 794      | 44.81%  |
| GNOME            | 306      | 17.27%  |
| KDE5             | 188      | 10.61%  |
| XFCE             | 180      | 10.16%  |
| MATE             | 72       | 4.06%   |
| X-Cinnamon       | 51       | 2.88%   |
| LXDE             | 37       | 2.09%   |
| Cinnamon         | 36       | 2.03%   |
| LXQt             | 21       | 1.19%   |
| i3               | 16       | 0.9%    |
| KDE              | 12       | 0.68%   |
| trinity          | 11       | 0.62%   |
| lightdm-xsession | 10       | 0.56%   |
| Openbox          | 9        | 0.51%   |
| GNOME Flashback  | 9        | 0.51%   |
| Budgie           | 7        | 0.4%    |
| sway             | 3        | 0.17%   |
| awesome          | 3        | 0.17%   |
| GNOME Classic    | 2        | 0.11%   |
| UKUI             | 1        | 0.06%   |
| GNUstep          | 1        | 0.06%   |
| Enlightenment    | 1        | 0.06%   |
| e16-session      | 1        | 0.06%   |
| DWM              | 1        | 0.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 749      | 42.41%  |
| Unknown | 598      | 33.86%  |
| Tty     | 249      | 14.1%   |
| Wayland | 169      | 9.57%   |
| Web     | 1        | 0.06%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1010     | 57.32%  |
| LightDM | 263      | 14.93%  |
| GDM     | 226      | 12.83%  |
| SDDM    | 151      | 8.57%   |
| TDM     | 72       | 4.09%   |
| GDM3    | 28       | 1.59%   |
| SLiM    | 5        | 0.28%   |
| XDM     | 4        | 0.23%   |
| NODM    | 3        | 0.17%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| ru_RU   | 600      | 34.19%  |
| en_US   | 536      | 30.54%  |
| de_DE   | 84       | 4.79%   |
| fr_FR   | 76       | 4.33%   |
| en_GB   | 69       | 3.93%   |
| es_ES   | 42       | 2.39%   |
| pt_BR   | 40       | 2.28%   |
| Unknown | 34       | 1.94%   |
| it_IT   | 33       | 1.88%   |
| en_AU   | 25       | 1.42%   |
| C       | 20       | 1.14%   |
| en_CA   | 18       | 1.03%   |
| pl_PL   | 13       | 0.74%   |
| ja_JP   | 11       | 0.63%   |
| hu_HU   | 10       | 0.57%   |
| es_AR   | 10       | 0.57%   |
| es_VE   | 9        | 0.51%   |
| en_IE   | 9        | 0.51%   |
| es_MX   | 8        | 0.46%   |
| de_AT   | 7        | 0.4%    |
| zh_CN   | 6        | 0.34%   |
| pt_PT   | 6        | 0.34%   |
| nl_BE   | 6        | 0.34%   |
| en_IN   | 5        | 0.28%   |
| uk_UA   | 4        | 0.23%   |
| de_CH   | 4        | 0.23%   |
| ca_ES   | 4        | 0.23%   |
| sv_SE   | 3        | 0.17%   |
| ru_UA   | 3        | 0.17%   |
| nl_NL   | 3        | 0.17%   |
| hr_HR   | 3        | 0.17%   |
| fr_BE   | 3        | 0.17%   |
| es_CO   | 3        | 0.17%   |
| en_ZA   | 3        | 0.17%   |
| en_NZ   | 3        | 0.17%   |
| en_HK   | 3        | 0.17%   |
| cs_CZ   | 3        | 0.17%   |
| fr_CH   | 2        | 0.11%   |
| es_US   | 2        | 0.11%   |
| es_PE   | 2        | 0.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 1181     | 66.5%   |
| EFI  | 595      | 33.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 1021     | 58.11%  |
| Overlay | 598      | 34.04%  |
| Btrfs   | 66       | 3.76%   |
| Zfs     | 35       | 1.99%   |
| Xfs     | 20       | 1.14%   |
| Ext3    | 9        | 0.51%   |
| Unknown | 3        | 0.17%   |
| Tmpfs   | 2        | 0.11%   |
| Ext2    | 2        | 0.11%   |
| Rootfs  | 1        | 0.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| MBR     | 806      | 45.38%  |
| GPT     | 716      | 40.32%  |
| Unknown | 254      | 14.3%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1453     | 82.56%  |
| Yes       | 307      | 17.44%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 919      | 52.13%  |
| Yes       | 844      | 47.87%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 497      | 28.45%  |
| Gigabyte Technology | 308      | 17.63%  |
| MSI                 | 189      | 10.82%  |
| ASRock              | 174      | 9.96%   |
| Dell                | 113      | 6.47%   |
| Hewlett-Packard     | 97       | 5.55%   |
| Intel               | 55       | 3.15%   |
| Lenovo              | 51       | 2.92%   |
| ECS                 | 44       | 2.52%   |
| Foxconn             | 26       | 1.49%   |
| Unknown             | 20       | 1.14%   |
| Fujitsu             | 17       | 0.97%   |
| ASRockRack          | 15       | 0.86%   |
| Supermicro          | 13       | 0.74%   |
| Acer                | 11       | 0.63%   |
| Pegatron            | 10       | 0.57%   |
| Biostar             | 10       | 0.57%   |
| AZW                 | 6        | 0.34%   |
| Inventec            | 5        | 0.29%   |
| BESSTAR Tech        | 5        | 0.29%   |
| Positivo            | 4        | 0.23%   |
| Medion              | 4        | 0.23%   |
| Huanan              | 4        | 0.23%   |
| Apple               | 4        | 0.23%   |
| Shuttle             | 3        | 0.17%   |
| Packard Bell        | 3        | 0.17%   |
| Google              | 3        | 0.17%   |
| Fujitsu Siemens     | 3        | 0.17%   |
| Thecus              | 2        | 0.11%   |
| Semp Toshiba        | 2        | 0.11%   |
| PC Engines          | 2        | 0.11%   |
| HPE                 | 2        | 0.11%   |
| Hardkernel          | 2        | 0.11%   |
| Gateway             | 2        | 0.11%   |
| Aquarius            | 2        | 0.11%   |
| AAEON               | 2        | 0.11%   |
| ZOTAC               | 1        | 0.06%   |
| Wistron             | 1        | 0.06%   |
| Techvision          | 1        | 0.06%   |
| System76            | 1        | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| ASUS All Series            | 73       | 4.18%   |
| ASUS S20 K29               | 55       | 3.15%   |
| MSI MS-7996                | 36       | 2.06%   |
| Unknown                    | 21       | 1.2%    |
| ECS G31T-M9                | 20       | 1.14%   |
| ASRock H470M-HVS           | 20       | 1.14%   |
| MSI MS-7817                | 18       | 1.03%   |
| Gigabyte H81M-S2V          | 17       | 0.97%   |
| ASUS PRIME H510M-A         | 17       | 0.97%   |
| Gigabyte H410M S2H         | 16       | 0.92%   |
| ECS H61H2-M13              | 16       | 0.92%   |
| ASUS P8H61-M LX3 R2.0      | 14       | 0.8%    |
| Dell OptiPlex 7010         | 10       | 0.57%   |
| ASUS PRIME B450M-A         | 9        | 0.52%   |
| Gigabyte B450M DS3H        | 8        | 0.46%   |
| ASUS H110M-R               | 8        | 0.46%   |
| Gigabyte B360M H           | 7        | 0.4%    |
| Fujitsu ESPRIMO P720       | 7        | 0.4%    |
| ASUS PRIME A320M-K         | 7        | 0.4%    |
| ASUS P8H67-M               | 7        | 0.4%    |
| ASUS P8H61-M LX3 PLUS R2.0 | 7        | 0.4%    |
| ASRock H61M-VG4            | 7        | 0.4%    |
| ASRock G31M-VS2            | 7        | 0.4%    |
| ASRock B450M Pro4          | 7        | 0.4%    |
| MSI MS-7C56                | 6        | 0.34%   |
| Intel Pro, Std, Elt Series | 6        | 0.34%   |
| HP Z620 Workstation        | 6        | 0.34%   |
| Gigabyte B85M-D3H          | 6        | 0.34%   |
| Gigabyte A320M-S2H         | 6        | 0.34%   |
| ASUS TUF Gaming X570-PLUS  | 6        | 0.34%   |
| ASUS Pro WS 565-ACE        | 6        | 0.34%   |
| ASUS P5G41T-M LE           | 6        | 0.34%   |
| MSI MS-7C95                | 5        | 0.29%   |
| MSI MS-7C84                | 5        | 0.29%   |
| HP Z420 Workstation        | 5        | 0.29%   |
| Gigabyte H61M-DS2 REV 1.2  | 5        | 0.29%   |
| Gigabyte GA-78LMT-USB3     | 5        | 0.29%   |
| Gigabyte B450M S2H         | 5        | 0.29%   |
| Gigabyte 970A-DS3P         | 5        | 0.29%   |
| Foxconn H61MXL/H61MXL-K    | 5        | 0.29%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 93       | 5.32%   |
| ASUS All               | 73       | 4.18%   |
| Dell OptiPlex          | 61       | 3.49%   |
| ASUS S20               | 55       | 3.15%   |
| MSI MS-7996            | 36       | 2.06%   |
| Lenovo ThinkCentre     | 30       | 1.72%   |
| ASUS ROG               | 29       | 1.66%   |
| ASUS P8H61-M           | 28       | 1.6%    |
| HP Compaq              | 25       | 1.43%   |
| Dell Precision         | 25       | 1.43%   |
| ASUS TUF               | 25       | 1.43%   |
| Unknown                | 21       | 1.2%    |
| Gigabyte B450M         | 20       | 1.14%   |
| ECS G31T-M9            | 20       | 1.14%   |
| ASRock H470M-HVS       | 20       | 1.14%   |
| ASUS PRO               | 19       | 1.09%   |
| MSI MS-7817            | 18       | 1.03%   |
| Gigabyte H81M-S2V      | 17       | 0.97%   |
| Gigabyte H410M         | 17       | 0.97%   |
| ECS H61H2-M13          | 16       | 0.92%   |
| HP EliteDesk           | 13       | 0.74%   |
| HP ProLiant            | 11       | 0.63%   |
| Fujitsu ESPRIMO        | 11       | 0.63%   |
| ASRock B450M           | 11       | 0.63%   |
| Gigabyte X570          | 10       | 0.57%   |
| ASUS P5G41T-M          | 10       | 0.57%   |
| Dell XPS               | 9        | 0.52%   |
| ASUS P8H67-M           | 9        | 0.52%   |
| ASRock B450            | 9        | 0.52%   |
| Gigabyte H61M-DS2      | 8        | 0.46%   |
| Gigabyte B360M         | 8        | 0.46%   |
| Gigabyte A320M-S2H     | 8        | 0.46%   |
| ASUS H110M-R           | 8        | 0.46%   |
| Lenovo ThinkStation    | 7        | 0.4%    |
| HP ProDesk             | 7        | 0.4%    |
| Gigabyte GA-78LMT-USB3 | 7        | 0.4%    |
| ASUS M5A97             | 7        | 0.4%    |
| ASRock H61M-VG4        | 7        | 0.4%    |
| ASRock G31M-VS2        | 7        | 0.4%    |
| Acer Aspire            | 7        | 0.4%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2020    | 200      | 11.45%  |
| 2012    | 181      | 10.36%  |
| 2018    | 157      | 8.99%   |
| 2021    | 149      | 8.53%   |
| 2013    | 148      | 8.47%   |
| 2011    | 124      | 7.1%    |
| 2019    | 104      | 5.95%   |
| 2009    | 99       | 5.67%   |
| 2014    | 97       | 5.55%   |
| 2015    | 96       | 5.5%    |
| 2017    | 78       | 4.46%   |
| 2010    | 72       | 4.12%   |
| 2016    | 67       | 3.84%   |
| 2008    | 65       | 3.72%   |
| 2007    | 41       | 2.35%   |
| 2022    | 29       | 1.66%   |
| 2006    | 16       | 0.92%   |
| 2005    | 11       | 0.63%   |
| 2003    | 5        | 0.29%   |
| 2001    | 3        | 0.17%   |
| 2004    | 2        | 0.11%   |
| Unknown | 2        | 0.11%   |
| 2000    | 1        | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 1747     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 1728     | 98.69%  |
| Enabled  | 23       | 1.31%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1738     | 99.48%  |
| Yes  | 9        | 0.52%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 4.01-8.0        | 363      | 20.59%  |
| 16.01-24.0      | 325      | 18.43%  |
| 3.01-4.0        | 301      | 17.07%  |
| 8.01-16.0       | 247      | 14.01%  |
| 32.01-64.0      | 202      | 11.46%  |
| 64.01-256.0     | 134      | 7.6%    |
| 1.01-2.0        | 92       | 5.22%   |
| 24.01-32.0      | 37       | 2.1%    |
| 2.01-3.0        | 37       | 2.1%    |
| 0.51-1.0        | 10       | 0.57%   |
| More than 256.0 | 9        | 0.51%   |
| 0.01-0.5        | 6        | 0.34%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 0.51-1.0    | 640      | 34.74%  |
| 1.01-2.0    | 339      | 18.4%   |
| 2.01-3.0    | 248      | 13.46%  |
| 4.01-8.0    | 222      | 12.05%  |
| 3.01-4.0    | 158      | 8.58%   |
| 8.01-16.0   | 87       | 4.72%   |
| 0.01-0.5    | 65       | 3.53%   |
| 16.01-24.0  | 40       | 2.17%   |
| 32.01-64.0  | 22       | 1.19%   |
| 24.01-32.0  | 14       | 0.76%   |
| 64.01-256.0 | 7        | 0.38%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 949      | 53.14%  |
| 2      | 337      | 18.87%  |
| 3      | 201      | 11.25%  |
| 4      | 135      | 7.56%   |
| 5      | 64       | 3.58%   |
| 6      | 33       | 1.85%   |
| 7      | 19       | 1.06%   |
| 8      | 16       | 0.9%    |
| 0      | 10       | 0.56%   |
| 10     | 7        | 0.39%   |
| 9      | 5        | 0.28%   |
| 12     | 3        | 0.17%   |
| 13     | 2        | 0.11%   |
| 11     | 2        | 0.11%   |
| 28     | 1        | 0.06%   |
| 27     | 1        | 0.06%   |
| 14     | 1        | 0.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1171     | 66.69%  |
| Yes       | 585      | 33.31%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1739     | 99.54%  |
| No        | 8        | 0.46%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1297     | 73.86%  |
| Yes       | 459      | 26.14%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1407     | 80.03%  |
| Yes       | 351      | 19.97%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Russia       | 616      | 35.22%  |
| USA          | 247      | 14.12%  |
| Germany      | 143      | 8.18%   |
| France       | 95       | 5.43%   |
| Spain        | 57       | 3.26%   |
| UK           | 50       | 2.86%   |
| Brazil       | 48       | 2.74%   |
| Italy        | 43       | 2.46%   |
| Australia    | 33       | 1.89%   |
| Canada       | 31       | 1.77%   |
| Poland       | 25       | 1.43%   |
| Ukraine      | 20       | 1.14%   |
| Netherlands  | 18       | 1.03%   |
| Argentina    | 18       | 1.03%   |
| Mexico       | 17       | 0.97%   |
| Hungary      | 17       | 0.97%   |
| Austria      | 17       | 0.97%   |
| Switzerland  | 16       | 0.91%   |
| Belgium      | 16       | 0.91%   |
| Portugal     | 13       | 0.74%   |
| Japan        | 13       | 0.74%   |
| China        | 12       | 0.69%   |
| Venezuela    | 11       | 0.63%   |
| Bulgaria     | 11       | 0.63%   |
| Sweden       | 9        | 0.51%   |
| Finland      | 9        | 0.51%   |
| Czechia      | 9        | 0.51%   |
| Romania      | 7        | 0.4%    |
| Norway       | 7        | 0.4%    |
| Pakistan     | 6        | 0.34%   |
| India        | 6        | 0.34%   |
| Croatia      | 6        | 0.34%   |
| Turkey       | 5        | 0.29%   |
| South Africa | 5        | 0.29%   |
| Ireland      | 5        | 0.29%   |
| Malaysia     | 4        | 0.23%   |
| Kazakhstan   | 4        | 0.23%   |
| Israel       | 4        | 0.23%   |
| Hong Kong    | 4        | 0.23%   |
| Greece       | 4        | 0.23%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Voronezh          | 530      | 29.74%  |
| Moscow            | 19       | 1.07%   |
| St Petersburg     | 15       | 0.84%   |
| Vienna            | 13       | 0.73%   |
| Bangor            | 12       | 0.67%   |
| Seville           | 11       | 0.62%   |
| Paris             | 11       | 0.62%   |
| Barcelona         | 11       | 0.62%   |
| Sao Paulo         | 10       | 0.56%   |
| Falkenstein       | 10       | 0.56%   |
| Dover-Foxcroft    | 10       | 0.56%   |
| Munich            | 7        | 0.39%   |
| Milan             | 7        | 0.39%   |
| Brisbane          | 7        | 0.39%   |
| Berlin            | 7        | 0.39%   |
| Sydney            | 6        | 0.34%   |
| Stockholm         | 6        | 0.34%   |
| Sofia             | 6        | 0.34%   |
| Ocala             | 6        | 0.34%   |
| Leipzig           | 6        | 0.34%   |
| Cologne           | 6        | 0.34%   |
| Chicago           | 6        | 0.34%   |
| Buenos Aires      | 6        | 0.34%   |
| Zurich            | 5        | 0.28%   |
| Warsaw            | 5        | 0.28%   |
| Orlando           | 5        | 0.28%   |
| Melbourne         | 5        | 0.28%   |
| Lyon              | 5        | 0.28%   |
| Los Angeles       | 5        | 0.28%   |
| Las Vegas         | 5        | 0.28%   |
| Kyiv              | 5        | 0.28%   |
| Frankfurt am Main | 5        | 0.28%   |
| Caracas           | 5        | 0.28%   |
| Budapest          | 5        | 0.28%   |
| Winterport        | 4        | 0.22%   |
| Valencia          | 4        | 0.22%   |
| Tuusula           | 4        | 0.22%   |
| Tsukuba           | 4        | 0.22%   |
| Toronto           | 4        | 0.22%   |
| Tel Aviv          | 4        | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 528      | 896    | 18.35%  |
| WDC                 | 513      | 844    | 17.83%  |
| Samsung Electronics | 404      | 625    | 14.04%  |
| Kingston            | 228      | 291    | 7.92%   |
| Toshiba             | 213      | 388    | 7.4%    |
| Crucial             | 197      | 242    | 6.85%   |
| Hitachi             | 105      | 144    | 3.65%   |
| SanDisk             | 89       | 110    | 3.09%   |
| Intel               | 50       | 65     | 1.74%   |
| A-DATA Technology   | 42       | 53     | 1.46%   |
| China               | 38       | 45     | 1.32%   |
| HGST                | 36       | 55     | 1.25%   |
| SPCC                | 31       | 34     | 1.08%   |
| Netac               | 23       | 80     | 0.8%    |
| Unknown             | 22       | 38     | 0.76%   |
| PNY                 | 20       | 25     | 0.7%    |
| Maxtor              | 18       | 20     | 0.63%   |
| Phison              | 15       | 20     | 0.52%   |
| Patriot             | 15       | 17     | 0.52%   |
| Hewlett-Packard     | 15       | 28     | 0.52%   |
| Micron Technology   | 14       | 17     | 0.49%   |
| Intenso             | 14       | 18     | 0.49%   |
| Corsair             | 14       | 24     | 0.49%   |
| Gigabyte Technology | 13       | 15     | 0.45%   |
| OCZ                 | 11       | 14     | 0.38%   |
| Unknown             | 11       | 12     | 0.38%   |
| Transcend           | 10       | 11     | 0.35%   |
| GOODRAM             | 9        | 18     | 0.31%   |
| SK hynix            | 8        | 14     | 0.28%   |
| XPG                 | 7        | 9      | 0.24%   |
| Hajaan              | 7        | 9      | 0.24%   |
| JMicron Technology  | 6        | 6      | 0.21%   |
| Team                | 5        | 6      | 0.17%   |
| LITEON              | 5        | 6      | 0.17%   |
| KIOXIA              | 5        | 5      | 0.17%   |
| Apacer              | 5        | 5      | 0.17%   |
| Xinhaike            | 4        | 6      | 0.14%   |
| T-FORCE             | 4        | 6      | 0.14%   |
| Silicon Motion      | 4        | 7      | 0.14%   |
| SABRENT             | 4        | 4      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 68       | 2.04%   |
| Crucial CT480BX500SSD1 480GB     | 65       | 1.95%   |
| Kingston SA400S37240G 240GB SSD  | 61       | 1.83%   |
| Toshiba DT01ACA050 500GB         | 47       | 1.41%   |
| Seagate ST1000DM010-2EP102 1TB   | 40       | 1.2%    |
| WDC WD5000AAKX-60U6AA0 500GB     | 34       | 1.02%   |
| Samsung SSD 860 EVO 250GB        | 33       | 0.99%   |
| Kingston SV300S37A120G 120GB SSD | 32       | 0.96%   |
| Samsung SSD 860 EVO 1TB          | 29       | 0.87%   |
| Kingston SA400S37480G 480GB SSD  | 29       | 0.87%   |
| WDC WD10EZEX-08WN4A0 1TB         | 28       | 0.84%   |
| Toshiba HDWD110 1TB              | 28       | 0.84%   |
| Hitachi HDS721050CLA362 500GB    | 28       | 0.84%   |
| Toshiba DT01ACA100 1TB           | 27       | 0.81%   |
| Seagate ST1000DM003-1ER162 1TB   | 24       | 0.72%   |
| Samsung SSD 970 EVO Plus 500GB   | 23       | 0.69%   |
| Samsung SSD 860 EVO 500GB        | 23       | 0.69%   |
| Crucial CT1000MX500SSD1 1TB      | 22       | 0.66%   |
| Seagate ST2000DM008-2FR102 2TB   | 21       | 0.63%   |
| Seagate ST1000DM003-1CH162 1TB   | 20       | 0.6%    |
| Samsung SSD 970 EVO Plus 1TB     | 20       | 0.6%    |
| Netac SSD 240GB                  | 20       | 0.6%    |
| Crucial CT240BX500SSD1 240GB     | 20       | 0.6%    |
| Crucial CT500MX500SSD1 500GB     | 19       | 0.57%   |
| Samsung SSD 850 EVO 250GB        | 18       | 0.54%   |
| Kingston SA400S37120G 120GB SSD  | 17       | 0.51%   |
| Seagate ST4000DM004-2CV104 4TB   | 16       | 0.48%   |
| Seagate ST3250318AS 250GB        | 16       | 0.48%   |
| Seagate ST3500418AS 500GB        | 15       | 0.45%   |
| Toshiba DT01ACA200 2TB           | 14       | 0.42%   |
| Samsung SSD 850 EVO 500GB        | 14       | 0.42%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 13       | 0.39%   |
| Crucial CT250MX500SSD1 250GB     | 13       | 0.39%   |
| SPCC Solid State Disk 120GB      | 12       | 0.36%   |
| Seagate ST2000DM001-1ER164 2TB   | 12       | 0.36%   |
| Kingston SUV400S37120G 120GB SSD | 12       | 0.36%   |
| WDC WD5000AAKX-08U6AA0 500GB     | 11       | 0.33%   |
| WDC WD10EZEX-00BN5A0 1TB         | 11       | 0.33%   |
| Toshiba DT01ACA300 3TB           | 11       | 0.33%   |
| Seagate ST1000DM003-9YN162 1TB   | 11       | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 515      | 869    | 36.86%  |
| WDC                 | 449      | 741    | 32.14%  |
| Toshiba             | 196      | 367    | 14.03%  |
| Hitachi             | 105      | 144    | 7.52%   |
| Samsung Electronics | 45       | 60     | 3.22%   |
| HGST                | 36       | 55     | 2.58%   |
| Maxtor              | 18       | 20     | 1.29%   |
| Unknown             | 6        | 11     | 0.43%   |
| Hewlett-Packard     | 5        | 14     | 0.36%   |
| Fujitsu             | 3        | 4      | 0.21%   |
| Intenso             | 2        | 2      | 0.14%   |
| HPE                 | 2        | 6      | 0.14%   |
| Synology            | 1        | 1      | 0.07%   |
| RSH-319             | 1        | 1      | 0.07%   |
| QNAP                | 1        | 1      | 0.07%   |
| pqi                 | 1        | 1      | 0.07%   |
| NAS                 | 1        | 5      | 0.07%   |
| MaxDigital          | 1        | 4      | 0.07%   |
| MARSHAL             | 1        | 1      | 0.07%   |
| IBM/Hitachi         | 1        | 1      | 0.07%   |
| Hajaan              | 1        | 1      | 0.07%   |
| ASMT                | 1        | 1      | 0.07%   |
| Apple               | 1        | 1      | 0.07%   |
| AMP                 | 1        | 1      | 0.07%   |
| Advantech           | 1        | 1      | 0.07%   |
| 3ware               | 1        | 4      | 0.07%   |
| 128MB               | 1        | 1      | 0.07%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 238      | 345    | 21.54%  |
| Kingston            | 202      | 256    | 18.28%  |
| Crucial             | 181      | 219    | 16.38%  |
| SanDisk             | 66       | 81     | 5.97%   |
| WDC                 | 53       | 58     | 4.8%    |
| China               | 37       | 44     | 3.35%   |
| A-DATA Technology   | 36       | 44     | 3.26%   |
| SPCC                | 28       | 29     | 2.53%   |
| Intel               | 26       | 32     | 2.35%   |
| Netac               | 23       | 80     | 2.08%   |
| PNY                 | 15       | 19     | 1.36%   |
| Toshiba             | 14       | 16     | 1.27%   |
| Patriot             | 13       | 14     | 1.18%   |
| OCZ                 | 11       | 14     | 1%      |
| Transcend           | 10       | 11     | 0.9%    |
| Intenso             | 10       | 12     | 0.9%    |
| Micron Technology   | 9        | 10     | 0.81%   |
| GOODRAM             | 8        | 13     | 0.72%   |
| Gigabyte Technology | 8        | 8      | 0.72%   |
| Unknown             | 8        | 9      | 0.72%   |
| Hajaan              | 7        | 8      | 0.63%   |
| Seagate             | 6        | 7      | 0.54%   |
| Hewlett-Packard     | 6        | 8      | 0.54%   |
| Corsair             | 5        | 8      | 0.45%   |
| Apacer              | 5        | 5      | 0.45%   |
| Xinhaike            | 4        | 6      | 0.36%   |
| Unknown             | 4        | 7      | 0.36%   |
| Team                | 4        | 4      | 0.36%   |
| Plextor             | 4        | 7      | 0.36%   |
| Mushkin             | 4        | 5      | 0.36%   |
| LITEONIT            | 4        | 6      | 0.36%   |
| LITEON              | 4        | 5      | 0.36%   |
| Foxline             | 4        | 4      | 0.36%   |
| Supermicro          | 3        | 4      | 0.27%   |
| JMicron Technology  | 3        | 3      | 0.27%   |
| TEXTORM             | 2        | 3      | 0.18%   |
| T-FORCE             | 2        | 3      | 0.18%   |
| Smartbuy            | 2        | 2      | 0.18%   |
| Pioneer             | 2        | 2      | 0.18%   |
| NGFF                | 2        | 2      | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 1122     | 2318   | 45.5%   |
| SSD     | 929      | 1451   | 37.67%  |
| NVMe    | 372      | 548    | 15.09%  |
| Unknown | 33       | 63     | 1.34%   |
| MMC     | 10       | 11     | 0.41%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 1599     | 3617   | 77.06%  |
| NVMe | 367      | 538    | 17.69%  |
| SAS  | 99       | 225    | 4.77%   |
| MMC  | 10       | 11     | 0.48%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 1276     | 2012   | 56.74%  |
| 0.51-1.0   | 502      | 787    | 22.32%  |
| 1.01-2.0   | 200      | 335    | 8.89%   |
| 3.01-4.0   | 103      | 217    | 4.58%   |
| 4.01-10.0  | 90       | 230    | 4%      |
| 2.01-3.0   | 50       | 78     | 2.22%   |
| 10.01-20.0 | 27       | 108    | 1.2%    |
| 20.01-50.0 | 1        | 2      | 0.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 600      | 33.69%  |
| 101-250        | 234      | 13.14%  |
| 251-500        | 202      | 11.34%  |
| 501-1000       | 198      | 11.12%  |
| More than 3000 | 170      | 9.55%   |
| 1001-2000      | 118      | 6.63%   |
| 51-100         | 79       | 4.44%   |
| 1-20           | 67       | 3.76%   |
| 2001-3000      | 61       | 3.43%   |
| 21-50          | 52       | 2.92%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 600      | 33.13%  |
| 1-20           | 407      | 22.47%  |
| 101-250        | 159      | 8.78%   |
| 51-100         | 123      | 6.79%   |
| 21-50          | 120      | 6.63%   |
| 251-500        | 112      | 6.18%   |
| 501-1000       | 98       | 5.41%   |
| More than 3000 | 81       | 4.47%   |
| 1001-2000      | 64       | 3.53%   |
| 2001-3000      | 41       | 2.26%   |
| 0              | 6        | 0.33%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| WDC WD5000AAKX-60U6AA0 500GB     | 20       | 23     | 5.21%   |
| Seagate ST500DM002-1BD142 500GB  | 16       | 16     | 4.17%   |
| Kingston SV300S37A120G 120GB SSD | 12       | 12     | 3.13%   |
| Hitachi HDS721050CLA362 500GB    | 8        | 8      | 2.08%   |
| WDC WD5000AAKX-08U6AA0 500GB     | 6        | 6      | 1.56%   |
| Seagate ST3500418AS 500GB        | 5        | 6      | 1.3%    |
| Seagate ST3250318AS 250GB        | 5        | 5      | 1.3%    |
| Seagate ST250DM000-1BD141 250GB  | 5        | 5      | 1.3%    |
| Seagate ST1000DM003-9YN162 1TB   | 5        | 6      | 1.3%    |
| Hitachi HDS721050DLE630 500GB    | 5        | 10     | 1.3%    |
| WDC WD20EARS-00MVWB0 2TB         | 4        | 4      | 1.04%   |
| WDC WD10EZEX-08WN4A0 1TB         | 4        | 4      | 1.04%   |
| Toshiba DT01ACA050 500GB         | 4        | 5      | 1.04%   |
| Seagate ST31500341AS 1TB         | 4        | 6      | 1.04%   |
| Seagate ST31000528AS 1TB         | 4        | 4      | 1.04%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 3        | 3      | 0.78%   |
| WDC WD5000AAKX-001CA0 500GB      | 3        | 3      | 0.78%   |
| WDC WD3200AAJS-08L7A0 320GB      | 3        | 3      | 0.78%   |
| WDC WD2500AAJS-00YZCA0 250GB     | 3        | 3      | 0.78%   |
| Seagate ST3320620AS 320GB        | 3        | 5      | 0.78%   |
| Seagate ST3320613AS 320GB        | 3        | 3      | 0.78%   |
| Seagate ST3120827AS 120GB        | 3        | 4      | 0.78%   |
| Seagate ST2000DM001-1ER164 2TB   | 3        | 3      | 0.78%   |
| Seagate ST1000DM003-1CH162 1TB   | 3        | 3      | 0.78%   |
| WDC WD5000AAKX-00ERMA0 500GB     | 2        | 3      | 0.52%   |
| WDC WD5000AAKS-00UU3A0 500GB     | 2        | 2      | 0.52%   |
| WDC WD3200AAKX-753CA1 320GB      | 2        | 2      | 0.52%   |
| WDC WD3200AAJS-00L7A0 320GB      | 2        | 2      | 0.52%   |
| WDC WD2500AAJS-00B4A0 250GB      | 2        | 2      | 0.52%   |
| WDC WD20EFRX-68EUZN0 2TB         | 2        | 5      | 0.52%   |
| WDC WD20EARX-00PASB0 2TB         | 2        | 2      | 0.52%   |
| WDC WD1600AAJS-00B4A0 160GB      | 2        | 2      | 0.52%   |
| WDC WD10EARS-00Y5B1 1TB          | 2        | 2      | 0.52%   |
| WDC WD1002FAEX-00Z3A0 1TB        | 2        | 2      | 0.52%   |
| Toshiba DT01ACA100 1TB           | 2        | 2      | 0.52%   |
| Seagate ST9500325AS 500GB        | 2        | 4      | 0.52%   |
| Seagate ST3500413AS 500GB        | 2        | 3      | 0.52%   |
| Seagate ST3250310AS 250GB        | 2        | 2      | 0.52%   |
| Seagate ST3160815AS 160GB        | 2        | 2      | 0.52%   |
| Seagate ST3160813AS 160GB        | 2        | 2      | 0.52%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 124      | 150    | 33.42%  |
| Seagate             | 115      | 146    | 31%     |
| Hitachi             | 31       | 41     | 8.36%   |
| Samsung Electronics | 25       | 27     | 6.74%   |
| Kingston            | 19       | 24     | 5.12%   |
| Toshiba             | 13       | 14     | 3.5%    |
| Intel               | 9        | 12     | 2.43%   |
| A-DATA Technology   | 8        | 11     | 2.16%   |
| Maxtor              | 7        | 7      | 1.89%   |
| SanDisk             | 4        | 4      | 1.08%   |
| Crucial             | 4        | 7      | 1.08%   |
| HGST                | 2        | 2      | 0.54%   |
| Hewlett-Packard     | 2        | 3      | 0.54%   |
| China               | 2        | 2      | 0.54%   |
| SK hynix            | 1        | 4      | 0.27%   |
| PNY                 | 1        | 1      | 0.27%   |
| Micron Technology   | 1        | 1      | 0.27%   |
| LITEONIT            | 1        | 1      | 0.27%   |
| KingDian            | 1        | 1      | 0.27%   |
| Fujitsu             | 1        | 2      | 0.27%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 120      | 145    | 39.47%  |
| Seagate             | 115      | 146    | 37.83%  |
| Hitachi             | 31       | 41     | 10.2%   |
| Toshiba             | 13       | 14     | 4.28%   |
| Samsung Electronics | 13       | 13     | 4.28%   |
| Maxtor              | 7        | 7      | 2.3%    |
| HGST                | 2        | 2      | 0.66%   |
| Hewlett-Packard     | 2        | 3      | 0.66%   |
| Fujitsu             | 1        | 2      | 0.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 283      | 373    | 80.63%  |
| SSD  | 58       | 72     | 16.52%  |
| NVMe | 10       | 15     | 2.85%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD4001FFSX-68JNUN0 4TB        | 1        | 1      | 11.11%  |
| Seagate ST500DM005 HD502HJ 500GB  | 1        | 1      | 11.11%  |
| Seagate ST500DM002-1BD142 500GB   | 1        | 2      | 11.11%  |
| Seagate ST3500830AS 500GB         | 1        | 1      | 11.11%  |
| Seagate ST3500630A 500GB          | 1        | 1      | 11.11%  |
| Samsung Electronics HD253GJ 250GB | 1        | 1      | 11.11%  |
| HGST HUH728080ALN600 8TB          | 1        | 1      | 11.11%  |
| HGST HDN724040ALE640 4TB          | 1        | 1      | 11.11%  |
| Hewlett-Packard SSD S700 500GB    | 1        | 2      | 11.11%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 4        | 5      | 44.44%  |
| HGST                | 2        | 2      | 22.22%  |
| WDC                 | 1        | 1      | 11.11%  |
| Samsung Electronics | 1        | 1      | 11.11%  |
| Hewlett-Packard     | 1        | 2      | 11.11%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 1314     | 2946   | 66.1%   |
| Malfunc  | 340      | 460    | 17.1%   |
| Detected | 324      | 973    | 16.3%   |
| Failed   | 9        | 11     | 0.45%   |
| Limited  | 1        | 1      | 0.05%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1254     | 53.38%  |
| AMD                              | 438      | 18.65%  |
| Samsung Electronics              | 163      | 6.94%   |
| ASMedia Technology               | 76       | 3.24%   |
| SanDisk                          | 56       | 2.38%   |
| Marvell Technology Group         | 51       | 2.17%   |
| JMicron Technology               | 46       | 1.96%   |
| Phison Electronics               | 44       | 1.87%   |
| Nvidia                           | 41       | 1.75%   |
| Kingston Technology Company      | 31       | 1.32%   |
| Micron/Crucial Technology        | 22       | 0.94%   |
| VIA Technologies                 | 20       | 0.85%   |
| LSI Logic / Symbios Logic        | 20       | 0.85%   |
| Broadcom / LSI                   | 12       | 0.51%   |
| Silicon Motion                   | 10       | 0.43%   |
| ADATA Technology                 | 10       | 0.43%   |
| SK hynix                         | 7        | 0.3%    |
| Toshiba America Info Systems     | 6        | 0.26%   |
| Micron Technology                | 6        | 0.26%   |
| Adaptec                          | 6        | 0.26%   |
| Seagate Technology               | 5        | 0.21%   |
| KIOXIA                           | 5        | 0.21%   |
| Silicon Image                    | 4        | 0.17%   |
| Realtek Semiconductor            | 3        | 0.13%   |
| Hewlett-Packard                  | 2        | 0.09%   |
| 3ware                            | 2        | 0.09%   |
| Silicon Integrated Systems [SiS] | 1        | 0.04%   |
| MAXIO Technology (Hangzhou)      | 1        | 0.04%   |
| Lite-On Technology               | 1        | 0.04%   |
| Integrated Technology Express    | 1        | 0.04%   |
| INNOGRIT                         | 1        | 0.04%   |
| HighPoint Technologies           | 1        | 0.04%   |
| Broadcom                         | 1        | 0.04%   |
| Biwin Storage Technology         | 1        | 0.04%   |
| Unknown                          | 1        | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 251      | 8.53%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 161      | 5.47%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 116      | 3.94%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 108      | 3.67%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 104      | 3.53%   |
| AMD 400 Series Chipset SATA Controller                                                  | 104      | 3.53%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 102      | 3.47%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 102      | 3.47%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 80       | 2.72%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 66       | 2.24%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 64       | 2.17%   |
| AMD 500 Series Chipset SATA Controller                                                  | 62       | 2.11%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 57       | 1.94%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 57       | 1.94%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 56       | 1.9%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 48       | 1.63%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 48       | 1.63%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 45       | 1.53%   |
| Intel SATA Controller [RAID mode]                                                       | 42       | 1.43%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 40       | 1.36%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 31       | 1.05%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 30       | 1.02%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 29       | 0.99%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 29       | 0.99%   |
| AMD FCH SATA Controller D                                                               | 27       | 0.92%   |
| Nvidia MCP61 SATA Controller                                                            | 24       | 0.82%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 22       | 0.75%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 22       | 0.75%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 22       | 0.75%   |
| Nvidia MCP61 IDE                                                                        | 20       | 0.68%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 20       | 0.68%   |
| Phison E12 NVMe Controller                                                              | 19       | 0.65%   |
| AMD 300 Series Chipset SATA Controller                                                  | 19       | 0.65%   |
| Samsung NVMe SSD Controller 980                                                         | 17       | 0.58%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 17       | 0.58%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 16       | 0.54%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 16       | 0.54%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 16       | 0.54%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 16       | 0.54%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 15       | 0.51%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 1400     | 59.42%  |
| IDE  | 448      | 19.02%  |
| NVMe | 367      | 15.58%  |
| RAID | 92       | 3.9%    |
| SAS  | 38       | 1.61%   |
| SCSI | 11       | 0.47%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 1261     | 72.18%  |
| AMD                   | 480      | 27.48%  |
| CentaurHauls          | 4        | 0.23%   |
| Marvell Semiconductor | 1        | 0.06%   |
| Unknown               | 1        | 0.06%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-9400 CPU @ 2.90GHz            | 59       | 3.38%   |
| Intel Pentium CPU G3420 @ 3.20GHz           | 35       | 2%      |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 28       | 1.6%    |
| Intel Pentium CPU G4400 @ 3.30GHz           | 28       | 1.6%    |
| Intel Core i3-10100 CPU @ 3.60GHz           | 27       | 1.54%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 25       | 1.43%   |
| AMD Ryzen 5 3600 6-Core Processor           | 25       | 1.43%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 21       | 1.2%    |
| Intel Core i3-4130 CPU @ 3.40GHz            | 21       | 1.2%    |
| Intel Pentium CPU G630 @ 2.70GHz            | 20       | 1.14%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 20       | 1.14%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 19       | 1.09%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 17       | 0.97%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 17       | 0.97%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 16       | 0.92%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 16       | 0.92%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 16       | 0.92%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 16       | 0.92%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 16       | 0.92%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 15       | 0.86%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 14       | 0.8%    |
| Intel Core i5-6500 CPU @ 3.20GHz            | 13       | 0.74%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 13       | 0.74%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 12       | 0.69%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 12       | 0.69%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 12       | 0.69%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 12       | 0.69%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 12       | 0.69%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 12       | 0.69%   |
| AMD FX-8350 Eight-Core Processor            | 12       | 0.69%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 11       | 0.63%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 11       | 0.63%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 11       | 0.63%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 11       | 0.63%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 10       | 0.57%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 10       | 0.57%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 10       | 0.57%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 9        | 0.51%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 9        | 0.51%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 9        | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 300      | 17.16%  |
| Intel Core i3           | 188      | 10.76%  |
| Intel Core i7           | 158      | 9.04%   |
| Intel Pentium           | 146      | 8.35%   |
| Intel Xeon              | 107      | 6.12%   |
| AMD Ryzen 5             | 105      | 6.01%   |
| Intel Celeron           | 78       | 4.46%   |
| Intel Core 2 Duo        | 74       | 4.23%   |
| AMD Ryzen 7             | 72       | 4.12%   |
| Other                   | 50       | 2.86%   |
| Intel Pentium Dual-Core | 50       | 2.86%   |
| AMD FX                  | 50       | 2.86%   |
| AMD Ryzen 9             | 48       | 2.75%   |
| AMD Ryzen 3             | 32       | 1.83%   |
| Intel Core 2 Quad       | 26       | 1.49%   |
| AMD Ryzen Threadripper  | 20       | 1.14%   |
| Intel Core i9           | 17       | 0.97%   |
| Intel Atom              | 17       | 0.97%   |
| AMD Athlon              | 17       | 0.97%   |
| AMD A10                 | 15       | 0.86%   |
| Intel Pentium Gold      | 14       | 0.8%    |
| AMD Athlon 64 X2        | 14       | 0.8%    |
| AMD Phenom II X4        | 12       | 0.69%   |
| AMD Athlon II X2        | 12       | 0.69%   |
| Intel Pentium 4         | 11       | 0.63%   |
| Intel Core 2            | 10       | 0.57%   |
| AMD Phenom II X6        | 8        | 0.46%   |
| Intel Pentium Dual      | 7        | 0.4%    |
| AMD GX                  | 7        | 0.4%    |
| AMD Sempron             | 6        | 0.34%   |
| AMD Ryzen 5 PRO         | 5        | 0.29%   |
| AMD A8                  | 5        | 0.29%   |
| Intel Pentium D         | 4        | 0.23%   |
| Intel Genuine           | 4        | 0.23%   |
| AMD Athlon X4           | 4        | 0.23%   |
| AMD Athlon II X4        | 4        | 0.23%   |
| AMD Athlon II X3        | 4        | 0.23%   |
| AMD A6                  | 4        | 0.23%   |
| Intel Pentium Silver    | 3        | 0.17%   |
| CentaurHauls VIA Eden   | 3        | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 598      | 34.19%  |
| 4       | 556      | 31.79%  |
| 6       | 253      | 14.47%  |
| 8       | 157      | 8.98%   |
| 1       | 49       | 2.8%    |
| 16      | 48       | 2.74%   |
| 12      | 35       | 2%      |
| 3       | 22       | 1.26%   |
| 10      | 11       | 0.63%   |
| 32      | 9        | 0.51%   |
| 24      | 3        | 0.17%   |
| 44      | 2        | 0.11%   |
| 64      | 1        | 0.06%   |
| 28      | 1        | 0.06%   |
| 20      | 1        | 0.06%   |
| 18      | 1        | 0.06%   |
| 14      | 1        | 0.06%   |
| Unknown | 1        | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 1718     | 98.28%  |
| 2       | 29       | 1.66%   |
| Unknown | 1        | 0.06%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 901      | 51.54%  |
| 1       | 846      | 48.4%   |
| Unknown | 1        | 0.06%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 1725     | 98.68%  |
| 32-bit         | 20       | 1.14%   |
| Unknown        | 3        | 0.17%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 287      | 16.2%   |
| 0x306c3    | 170      | 9.59%   |
| 0x206a7    | 108      | 6.09%   |
| 0x1067a    | 107      | 6.04%   |
| 0x306a9    | 94       | 5.3%    |
| 0x906ea    | 87       | 4.91%   |
| 0x506e3    | 87       | 4.91%   |
| 0xa0653    | 61       | 3.44%   |
| 0x08701021 | 51       | 2.88%   |
| 0xa0655    | 37       | 2.09%   |
| 0x906e9    | 35       | 1.98%   |
| 0x08108109 | 32       | 1.81%   |
| 0x0a201016 | 29       | 1.64%   |
| 0xa0671    | 27       | 1.52%   |
| 0x0800820d | 27       | 1.52%   |
| 0x6fd      | 17       | 0.96%   |
| 0x010000c8 | 17       | 0.96%   |
| 0x906eb    | 15       | 0.85%   |
| 0x08101016 | 15       | 0.85%   |
| 0x6fb      | 14       | 0.79%   |
| 0x306f2    | 14       | 0.79%   |
| 0x206d7    | 14       | 0.79%   |
| 0x06003106 | 13       | 0.73%   |
| 0x906ed    | 12       | 0.68%   |
| 0x0a201009 | 12       | 0.68%   |
| 0x06000822 | 12       | 0.68%   |
| 0x010000b6 | 12       | 0.68%   |
| 0x20655    | 11       | 0.62%   |
| 0x90672    | 10       | 0.56%   |
| 0x306e4    | 10       | 0.56%   |
| 0x206c2    | 10       | 0.56%   |
| 0x10676    | 10       | 0.56%   |
| 0x0a50000c | 10       | 0.56%   |
| 0x06000852 | 10       | 0.56%   |
| 0x706a8    | 9        | 0.51%   |
| 0x106a5    | 9        | 0.51%   |
| 0x08600106 | 9        | 0.51%   |
| 0x0600063e | 9        | 0.51%   |
| 0x30678    | 8        | 0.45%   |
| 0x6f6      | 7        | 0.4%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 225      | 12.88%  |
| KabyLake         | 180      | 10.3%   |
| SandyBridge      | 136      | 7.78%   |
| Penryn           | 135      | 7.73%   |
| IvyBridge        | 117      | 6.7%    |
| CometLake        | 110      | 6.3%    |
| Skylake          | 105      | 6.01%   |
| Zen 2            | 94       | 5.38%   |
| Zen+             | 82       | 4.69%   |
| Zen 3            | 82       | 4.69%   |
| Core             | 54       | 3.09%   |
| K10              | 53       | 3.03%   |
| Piledriver       | 44       | 2.52%   |
| Zen              | 42       | 2.4%    |
| Unknown          | 41       | 2.35%   |
| Westmere         | 31       | 1.77%   |
| Silvermont       | 27       | 1.55%   |
| K8 Hammer        | 22       | 1.26%   |
| Nehalem          | 21       | 1.2%    |
| NetBurst         | 19       | 1.09%   |
| Goldmont plus    | 17       | 0.97%   |
| Steamroller      | 16       | 0.92%   |
| Bulldozer        | 15       | 0.86%   |
| Bonnell          | 12       | 0.69%   |
| Broadwell        | 10       | 0.57%   |
| Jaguar           | 8        | 0.46%   |
| Excavator        | 8        | 0.46%   |
| Goldmont         | 7        | 0.4%    |
| Alderlake Hybrid | 7        | 0.4%    |
| Icelake          | 6        | 0.34%   |
| Tremont          | 5        | 0.29%   |
| Bobcat           | 4        | 0.23%   |
| Puma             | 3        | 0.17%   |
| P6               | 3        | 0.17%   |
| K6               | 3        | 0.17%   |
| TigerLake        | 2        | 0.11%   |
| K10 Llano        | 1        | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 797      | 43.24%  |
| Nvidia                           | 598      | 32.45%  |
| AMD                              | 395      | 21.43%  |
| ASPEED Technology                | 35       | 1.9%    |
| Matrox Electronics Systems       | 11       | 0.6%    |
| VIA Technologies                 | 5        | 0.27%   |
| Silicon Integrated Systems [SiS] | 1        | 0.05%   |
| ATI Technologies                 | 1        | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 120      | 6.39%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 93       | 4.95%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 70       | 3.73%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 68       | 3.62%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 55       | 2.93%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 53       | 2.82%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 50       | 2.66%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 46       | 2.45%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 37       | 1.97%   |
| Nvidia GF108 [GeForce GT 730]                                               | 37       | 1.97%   |
| Intel HD Graphics 530                                                       | 35       | 1.86%   |
| ASPEED Technology ASPEED Graphics Family                                    | 35       | 1.86%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 35       | 1.86%   |
| Nvidia GK208B [GeForce GT 710]                                              | 34       | 1.81%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 33       | 1.76%   |
| Intel HD Graphics 510                                                       | 28       | 1.49%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 25       | 1.33%   |
| Intel HD Graphics 630                                                       | 24       | 1.28%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 23       | 1.22%   |
| Nvidia GF108 [GeForce GT 630]                                               | 20       | 1.06%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 20       | 1.06%   |
| Nvidia GT218 [GeForce 210]                                                  | 18       | 0.96%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 16       | 0.85%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 15       | 0.8%    |
| Intel GeminiLake [UHD Graphics 600]                                         | 15       | 0.8%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 15       | 0.8%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 14       | 0.75%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 14       | 0.75%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 13       | 0.69%   |
| Nvidia G86 [GeForce 8500 GT]                                                | 12       | 0.64%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 12       | 0.64%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 12       | 0.64%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 12       | 0.64%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 11       | 0.59%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 11       | 0.59%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 11       | 0.59%   |
| Nvidia GK208B [GeForce GT 730]                                              | 11       | 0.59%   |
| Nvidia GF108 [GeForce GT 430]                                               | 11       | 0.59%   |
| AMD RS780L [Radeon 3000]                                                    | 11       | 0.59%   |
| AMD Renoir                                                                  | 11       | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| 1 x Intel                         | 723      | 41.03%  |
| 1 x Nvidia                        | 549      | 31.16%  |
| 1 x AMD                           | 363      | 20.6%   |
| Intel + Nvidia                    | 28       | 1.59%   |
| 1 x ASPEED                        | 25       | 1.42%   |
| 2 x AMD                           | 17       | 0.96%   |
| Other                             | 13       | 0.74%   |
| 1 x Matrox                        | 10       | 0.57%   |
| AMD + Nvidia                      | 6        | 0.34%   |
| 1 x VIA                           | 5        | 0.28%   |
| 2 x Nvidia                        | 4        | 0.23%   |
| Nvidia + ASPEED                   | 4        | 0.23%   |
| AMD + ASPEED                      | 4        | 0.23%   |
| Intel + 2 x Nvidia                | 3        | 0.17%   |
| Intel + AMD                       | 3        | 0.17%   |
| 3 x AMD                           | 1        | 0.06%   |
| 2 x Nvidia + 1 x ASPEED           | 1        | 0.06%   |
| 2 x AMD + 1 x Nvidia + 1 x ASPEED | 1        | 0.06%   |
| 1 x SiS                           | 1        | 0.06%   |
| AMD + Matrox                      | 1        | 0.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 846      | 48.07%  |
| Unknown     | 674      | 38.3%   |
| Proprietary | 240      | 13.64%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1196     | 67.57%  |
| 1.01-2.0   | 142      | 8.02%   |
| 0.51-1.0   | 93       | 5.25%   |
| 0.01-0.5   | 93       | 5.25%   |
| 3.01-4.0   | 91       | 5.14%   |
| 7.01-8.0   | 79       | 4.46%   |
| 5.01-6.0   | 38       | 2.15%   |
| 8.01-16.0  | 15       | 0.85%   |
| 2.01-3.0   | 14       | 0.79%   |
| 16.01-24.0 | 6        | 0.34%   |
| 4.01-5.0   | 2        | 0.11%   |
| 24.01-32.0 | 1        | 0.06%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 180      | 15.36%  |
| Dell                    | 136      | 11.6%   |
| Goldstar                | 124      | 10.58%  |
| Acer                    | 76       | 6.48%   |
| Hewlett-Packard         | 69       | 5.89%   |
| BenQ                    | 67       | 5.72%   |
| AOC                     | 60       | 5.12%   |
| Ancor Communications    | 54       | 4.61%   |
| Philips                 | 51       | 4.35%   |
| Iiyama                  | 29       | 2.47%   |
| ViewSonic               | 25       | 2.13%   |
| Unknown                 | 25       | 2.13%   |
| ASUSTek Computer        | 25       | 2.13%   |
| Eizo                    | 22       | 1.88%   |
| Lenovo                  | 18       | 1.54%   |
| LG Electronics          | 15       | 1.28%   |
| Sony                    | 11       | 0.94%   |
| NEC Computers           | 9        | 0.77%   |
| Vestel Elektronik       | 7        | 0.6%    |
| Medion                  | 6        | 0.51%   |
| Unknown                 | 6        | 0.51%   |
| Vizio                   | 5        | 0.43%   |
| Toshiba                 | 4        | 0.34%   |
| MSI                     | 4        | 0.34%   |
| Microstep               | 4        | 0.34%   |
| Idek Iiyama             | 4        | 0.34%   |
| Fujitsu Siemens         | 4        | 0.34%   |
| Chi Mei Optoelectronics | 4        | 0.34%   |
| Sceptre Tech            | 3        | 0.26%   |
| Panasonic               | 3        | 0.26%   |
| ONN                     | 3        | 0.26%   |
| Mi                      | 3        | 0.26%   |
| Lenovo Group Limited    | 3        | 0.26%   |
| Hitachi                 | 3        | 0.26%   |
| Grundig                 | 3        | 0.26%   |
| DENON                   | 3        | 0.26%   |
| Belinea                 | 3        | 0.26%   |
| VIZ                     | 2        | 0.17%   |
| VIE                     | 2        | 0.17%   |
| Videoseven              | 2        | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 17       | 1.37%   |
| ViewSonic VG730m VSC951E 1280x1024 338x270mm 17.0-inch                 | 7        | 0.56%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 7        | 0.56%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 7        | 0.56%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch            | 6        | 0.48%   |
| Unknown                                                                | 6        | 0.48%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch      | 5        | 0.4%    |
| Dell E176FP DELA014 1280x1024 338x270mm 17.0-inch                      | 5        | 0.4%    |
| AOC 1950w AOC1950 1366x768 410x230mm 18.5-inch                         | 5        | 0.4%    |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch      | 4        | 0.32%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch   | 4        | 0.32%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 4        | 0.32%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 4        | 0.32%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                  | 4        | 0.32%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                  | 4        | 0.32%   |
| Dell U2518D DEL413A 2560x1440 553x311mm 25.0-inch                      | 4        | 0.32%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 4        | 0.32%   |
| BenQ GL2480 BNQ78ED 1920x1080 531x298mm 24.0-inch                      | 4        | 0.32%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch  | 4        | 0.32%   |
| Acer K242HL ACR03E3 1920x1080 531x299mm 24.0-inch                      | 4        | 0.32%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch      | 3        | 0.24%   |
| Samsung Electronics LC32G7xT SAM7058 2560x1440 698x393mm 31.5-inch     | 3        | 0.24%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 3        | 0.24%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 3        | 0.24%   |
| Philips PHL 242V8 PHLC219 1920x1080 527x296mm 23.8-inch                | 3        | 0.24%   |
| Philips 220WS PHL0851 1680x1050 434x270mm 20.1-inch                    | 3        | 0.24%   |
| Iiyama PL2409HD IVM560C 1920x1080 520x290mm 23.4-inch                  | 3        | 0.24%   |
| Iiyama PL2283H IVM562E 1920x1080 496x292mm 22.7-inch                   | 3        | 0.24%   |
| Grundig WXGA GRU4448 1600x1200                                         | 3        | 0.24%   |
| Goldstar W2243 GSM56FE 1920x1080 477x269mm 21.6-inch                   | 3        | 0.24%   |
| Goldstar ULTRAGEAR GSM5B80 2560x1440 597x336mm 27.0-inch               | 3        | 0.24%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                   | 3        | 0.24%   |
| Dell U2715H DELD065 2560x1440 597x336mm 27.0-inch                      | 3        | 0.24%   |
| Dell U2713HM DEL407E 2560x1440 597x336mm 27.0-inch                     | 3        | 0.24%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                       | 3        | 0.24%   |
| Dell P2415Q DELA0BE 3840x2160 527x296mm 23.8-inch                      | 3        | 0.24%   |
| Dell LCD Monitor U2312HM 1920x1080                                     | 3        | 0.24%   |
| Dell 1907FP DEL4014 1280x1024 376x301mm 19.0-inch                      | 3        | 0.24%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                      | 3        | 0.24%   |
| BenQ GW2470 BNQ78E4 1920x1080 527x296mm 23.8-inch                      | 3        | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 497      | 43.07%  |
| 3840x2160 (4K)     | 105      | 9.1%    |
| 1280x1024 (SXGA)   | 101      | 8.75%   |
| 2560x1440 (QHD)    | 89       | 7.71%   |
| 1680x1050 (WSXGA+) | 55       | 4.77%   |
| Unknown            | 42       | 3.64%   |
| 1366x768 (WXGA)    | 35       | 3.03%   |
| 1920x1200 (WUXGA)  | 29       | 2.51%   |
| 1440x900 (WXGA+)   | 28       | 2.43%   |
| 1600x900 (HD+)     | 25       | 2.17%   |
| 2288x1287          | 18       | 1.56%   |
| 3840x1080          | 17       | 1.47%   |
| 3440x1440          | 14       | 1.21%   |
| 2560x1080          | 14       | 1.21%   |
| 1024x768 (XGA)     | 14       | 1.21%   |
| 1600x1200          | 13       | 1.13%   |
| 1360x768           | 13       | 1.13%   |
| 1920x540           | 6        | 0.52%   |
| 4480x1440          | 5        | 0.43%   |
| 3200x1080          | 3        | 0.26%   |
| 2560x1600          | 3        | 0.26%   |
| 5760x1080          | 2        | 0.17%   |
| 5360x1440          | 2        | 0.17%   |
| 3360x1050          | 2        | 0.17%   |
| 1400x1050          | 2        | 0.17%   |
| 1280x720 (HD)      | 2        | 0.17%   |
| 7680x4320          | 1        | 0.09%   |
| 6400x2160          | 1        | 0.09%   |
| 5760x2160          | 1        | 0.09%   |
| 5120x2160          | 1        | 0.09%   |
| 5120x1440          | 1        | 0.09%   |
| 5120x1080          | 1        | 0.09%   |
| 4480x1600          | 1        | 0.09%   |
| 3840x2560          | 1        | 0.09%   |
| 3360x1080          | 1        | 0.09%   |
| 3280x1080          | 1        | 0.09%   |
| 2960x1050          | 1        | 0.09%   |
| 2880x1620          | 1        | 0.09%   |
| 2560x1024          | 1        | 0.09%   |
| 2048x1536          | 1        | 0.09%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 170      | 14.91%  |
| 27      | 154      | 13.51%  |
| 23      | 147      | 12.89%  |
| 21      | 104      | 9.12%   |
| Unknown | 103      | 9.04%   |
| 19      | 69       | 6.05%   |
| 17      | 53       | 4.65%   |
| 31      | 51       | 4.47%   |
| 18      | 48       | 4.21%   |
| 22      | 46       | 4.04%   |
| 15      | 30       | 2.63%   |
| 20      | 28       | 2.46%   |
| 34      | 20       | 1.75%   |
| 142     | 17       | 1.49%   |
| 84      | 15       | 1.32%   |
| 72      | 9        | 0.79%   |
| 32      | 9        | 0.79%   |
| 25      | 8        | 0.7%    |
| 28      | 6        | 0.53%   |
| 52      | 5        | 0.44%   |
| 48      | 5        | 0.44%   |
| 26      | 5        | 0.44%   |
| 54      | 4        | 0.35%   |
| 13      | 4        | 0.35%   |
| 42      | 3        | 0.26%   |
| 39      | 3        | 0.26%   |
| 35      | 3        | 0.26%   |
| 33      | 3        | 0.26%   |
| 29      | 3        | 0.26%   |
| 65      | 2        | 0.18%   |
| 75      | 1        | 0.09%   |
| 74      | 1        | 0.09%   |
| 55      | 1        | 0.09%   |
| 50      | 1        | 0.09%   |
| 49      | 1        | 0.09%   |
| 47      | 1        | 0.09%   |
| 43      | 1        | 0.09%   |
| 40      | 1        | 0.09%   |
| 38      | 1        | 0.09%   |
| 30      | 1        | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 430      | 39.02%  |
| 401-500        | 247      | 22.41%  |
| Unknown        | 103      | 9.35%   |
| 301-350        | 81       | 7.35%   |
| 601-700        | 79       | 7.17%   |
| 351-400        | 51       | 4.63%   |
| 701-800        | 30       | 2.72%   |
| 1501-2000      | 26       | 2.36%   |
| 1001-1500      | 20       | 1.81%   |
| More than 2000 | 17       | 1.54%   |
| 801-900        | 8        | 0.73%   |
| 201-300        | 5        | 0.45%   |
| 901-1000       | 4        | 0.36%   |
| 101-200        | 1        | 0.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 661      | 62.12%  |
| 16/10   | 122      | 11.47%  |
| 5/4     | 93       | 8.74%   |
| Unknown | 92       | 8.65%   |
| 4/3     | 35       | 3.29%   |
| 21/9    | 25       | 2.35%   |
| 1.00    | 19       | 1.79%   |
| 3/2     | 8        | 0.75%   |
| 6/5     | 4        | 0.38%   |
| 32/9    | 3        | 0.28%   |
| 2.65    | 1        | 0.09%   |
| 1.96    | 1        | 0.09%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 374      | 33.75%  |
| 301-350        | 157      | 14.17%  |
| 151-200        | 134      | 12.09%  |
| Unknown        | 103      | 9.3%    |
| 351-500        | 91       | 8.21%   |
| 141-150        | 84       | 7.58%   |
| More than 1000 | 58       | 5.23%   |
| 251-300        | 54       | 4.87%   |
| 101-110        | 24       | 2.17%   |
| 501-1000       | 13       | 1.17%   |
| 111-120        | 5        | 0.45%   |
| 131-140        | 4        | 0.36%   |
| 71-80          | 3        | 0.27%   |
| 81-90          | 1        | 0.09%   |
| 41-50          | 1        | 0.09%   |
| 1-40           | 1        | 0.09%   |
| 91-100         | 1        | 0.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 666      | 62.36%  |
| 101-120 | 180      | 16.85%  |
| Unknown | 103      | 9.64%   |
| 121-160 | 46       | 4.31%   |
| 1-50    | 45       | 4.21%   |
| 161-240 | 28       | 2.62%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 802      | 45.29%  |
| 0     | 747      | 42.18%  |
| 2     | 200      | 11.29%  |
| 3     | 20       | 1.13%   |
| 4     | 2        | 0.11%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 1102     | 48.96%  |
| Intel                            | 647      | 28.74%  |
| Qualcomm Atheros                 | 133      | 5.91%   |
| Broadcom                         | 55       | 2.44%   |
| Ralink Technology                | 38       | 1.69%   |
| Nvidia                           | 37       | 1.64%   |
| TP-Link                          | 20       | 0.89%   |
| Broadcom Limited                 | 17       | 0.76%   |
| Ralink                           | 13       | 0.58%   |
| Marvell Technology Group         | 13       | 0.58%   |
| Qualcomm Atheros Communications  | 11       | 0.49%   |
| Aquantia                         | 11       | 0.49%   |
| Samsung Electronics              | 10       | 0.44%   |
| Mellanox Technologies            | 10       | 0.44%   |
| MediaTek                         | 10       | 0.44%   |
| D-Link System                    | 9        | 0.4%    |
| D-Link                           | 9        | 0.4%    |
| ASIX Electronics                 | 9        | 0.4%    |
| Microsoft                        | 8        | 0.36%   |
| NetGear                          | 7        | 0.31%   |
| VIA Technologies                 | 6        | 0.27%   |
| ASUSTek Computer                 | 6        | 0.27%   |
| Huawei Technologies              | 5        | 0.22%   |
| Gemtek                           | 4        | 0.18%   |
| Dresden Elektronik               | 4        | 0.18%   |
| American Megatrends              | 4        | 0.18%   |
| Texas Instruments                | 3        | 0.13%   |
| IMC Networks                     | 3        | 0.13%   |
| Edimax Technology                | 3        | 0.13%   |
| Xiaomi                           | 2        | 0.09%   |
| Silicon Integrated Systems [SiS] | 2        | 0.09%   |
| Qualcomm                         | 2        | 0.09%   |
| QLogic                           | 2        | 0.09%   |
| ICS Advent                       | 2        | 0.09%   |
| Belkin Components                | 2        | 0.09%   |
| AVM                              | 2        | 0.09%   |
| 3Com                             | 2        | 0.09%   |
| ZTE WCDMA Technologies MSM       | 1        | 0.04%   |
| Wilocity                         | 1        | 0.04%   |
| U-Blox                           | 1        | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 904      | 36.38%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 73       | 2.94%   |
| Intel I211 Gigabit Network Connection                             | 64       | 2.58%   |
| Realtek RTL8125 2.5GbE Controller                                 | 62       | 2.49%   |
| Intel Wi-Fi 6 AX200                                               | 62       | 2.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 57       | 2.29%   |
| Intel I210 Gigabit Network Connection                             | 40       | 1.61%   |
| Intel Ethernet Connection (2) I219-V                              | 40       | 1.61%   |
| Intel Ethernet Controller I225-V                                  | 36       | 1.45%   |
| Intel Ethernet Connection (14) I219-V                             | 31       | 1.25%   |
| Intel Ethernet Connection I217-LM                                 | 29       | 1.17%   |
| Intel 82579V Gigabit Network Connection                           | 28       | 1.13%   |
| Intel 82574L Gigabit Network Connection                           | 25       | 1.01%   |
| Nvidia MCP61 Ethernet                                             | 23       | 0.93%   |
| Intel Ethernet Connection (7) I219-V                              | 22       | 0.89%   |
| Intel Ethernet Connection I217-V                                  | 20       | 0.8%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 19       | 0.76%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 19       | 0.76%   |
| Intel Ethernet Connection (2) I219-LM                             | 18       | 0.72%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 17       | 0.68%   |
| Intel Ethernet Connection (2) I218-V                              | 16       | 0.64%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 15       | 0.6%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 14       | 0.56%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 14       | 0.56%   |
| Intel Wireless-AC 9260                                            | 14       | 0.56%   |
| Intel Wireless 3165                                               | 14       | 0.56%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 14       | 0.56%   |
| Ralink MT7601U Wireless Adapter                                   | 13       | 0.52%   |
| Ralink RT5370 Wireless Adapter                                    | 12       | 0.48%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 11       | 0.44%   |
| Realtek 802.11ac NIC                                              | 11       | 0.44%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 11       | 0.44%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 10       | 0.4%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 10       | 0.4%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 10       | 0.4%    |
| Qualcomm Atheros AR9271 802.11n                                   | 10       | 0.4%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 10       | 0.4%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 10       | 0.4%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 10       | 0.4%    |
| Intel Ethernet Controller X550                                    | 10       | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 179      | 36.46%  |
| Realtek Semiconductor           | 98       | 19.96%  |
| Qualcomm Atheros                | 55       | 11.2%   |
| Ralink Technology               | 38       | 7.74%   |
| TP-Link                         | 18       | 3.67%   |
| Broadcom                        | 16       | 3.26%   |
| Ralink                          | 13       | 2.65%   |
| Qualcomm Atheros Communications | 11       | 2.24%   |
| MediaTek                        | 9        | 1.83%   |
| D-Link                          | 8        | 1.63%   |
| NetGear                         | 7        | 1.43%   |
| Microsoft                       | 7        | 1.43%   |
| ASUSTek Computer                | 6        | 1.22%   |
| D-Link System                   | 5        | 1.02%   |
| IMC Networks                    | 3        | 0.61%   |
| Gemtek                          | 3        | 0.61%   |
| Edimax Technology               | 3        | 0.61%   |
| Broadcom Limited                | 3        | 0.61%   |
| Belkin Components               | 2        | 0.41%   |
| AVM                             | 2        | 0.41%   |
| Wilocity                        | 1        | 0.2%    |
| Sitecom Europe                  | 1        | 0.2%    |
| Micro Star International        | 1        | 0.2%    |
| Linksys                         | 1        | 0.2%    |
| BUFFALO                         | 1        | 0.2%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 62       | 12.55%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 19       | 3.85%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 15       | 3.04%   |
| Intel Wireless-AC 9260                                         | 14       | 2.83%   |
| Intel Wireless 3165                                            | 14       | 2.83%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 14       | 2.83%   |
| Ralink MT7601U Wireless Adapter                                | 13       | 2.63%   |
| Ralink RT5370 Wireless Adapter                                 | 12       | 2.43%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 11       | 2.23%   |
| Realtek 802.11ac NIC                                           | 11       | 2.23%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 10       | 2.02%   |
| Qualcomm Atheros AR9271 802.11n                                | 10       | 2.02%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 10       | 2.02%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 9        | 1.82%   |
| Intel Wireless 7260                                            | 9        | 1.82%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 8        | 1.62%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 8        | 1.62%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 8        | 1.62%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 6        | 1.21%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 6        | 1.21%   |
| Intel Wireless 8260                                            | 6        | 1.21%   |
| Intel Wireless 7265                                            | 6        | 1.21%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 6        | 1.21%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 5        | 1.01%   |
| Ralink RT5372 Wireless Adapter                                 | 5        | 1.01%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 5        | 1.01%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 5        | 1.01%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 5        | 1.01%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 5        | 1.01%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 4        | 0.81%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 4        | 0.81%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 4        | 0.81%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4        | 0.81%   |
| NetGear A6210                                                  | 4        | 0.81%   |
| Microsoft Xbox 360 Wireless Adapter                            | 4        | 0.81%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 3        | 0.61%   |
| TP-Link 802.11n NIC                                            | 3        | 0.61%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 3        | 0.61%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 3        | 0.61%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 3        | 0.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 1063     | 56.36%  |
| Intel                             | 550      | 29.16%  |
| Qualcomm Atheros                  | 84       | 4.45%   |
| Broadcom                          | 42       | 2.23%   |
| Nvidia                            | 37       | 1.96%   |
| Broadcom Limited                  | 14       | 0.74%   |
| Marvell Technology Group          | 13       | 0.69%   |
| Aquantia                          | 11       | 0.58%   |
| Samsung Electronics               | 10       | 0.53%   |
| Mellanox Technologies             | 9        | 0.48%   |
| ASIX Electronics                  | 9        | 0.48%   |
| VIA Technologies                  | 6        | 0.32%   |
| D-Link System                     | 4        | 0.21%   |
| American Megatrends               | 4        | 0.21%   |
| Huawei Technologies               | 3        | 0.16%   |
| Xiaomi                            | 2        | 0.11%   |
| TP-Link                           | 2        | 0.11%   |
| Silicon Integrated Systems [SiS]  | 2        | 0.11%   |
| Qualcomm                          | 2        | 0.11%   |
| QLogic                            | 2        | 0.11%   |
| ICS Advent                        | 2        | 0.11%   |
| 3Com                              | 2        | 0.11%   |
| ZTE WCDMA Technologies MSM        | 1        | 0.05%   |
| Tehuti Networks                   | 1        | 0.05%   |
| Sundance Technology Inc / IC Plus | 1        | 0.05%   |
| OPPO Electronics                  | 1        | 0.05%   |
| Motorola PCS                      | 1        | 0.05%   |
| Microsoft                         | 1        | 0.05%   |
| Google                            | 1        | 0.05%   |
| Gemtek                            | 1        | 0.05%   |
| DisplayLink                       | 1        | 0.05%   |
| D-Link                            | 1        | 0.05%   |
| ATEN International                | 1        | 0.05%   |
| ADMtek                            | 1        | 0.05%   |
| Accton Technology                 | 1        | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 904      | 46.01%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 73       | 3.72%   |
| Intel I211 Gigabit Network Connection                             | 64       | 3.26%   |
| Realtek RTL8125 2.5GbE Controller                                 | 62       | 3.16%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 57       | 2.9%    |
| Intel I210 Gigabit Network Connection                             | 40       | 2.04%   |
| Intel Ethernet Connection (2) I219-V                              | 40       | 2.04%   |
| Intel Ethernet Controller I225-V                                  | 36       | 1.83%   |
| Intel Ethernet Connection (14) I219-V                             | 31       | 1.58%   |
| Intel Ethernet Connection I217-LM                                 | 29       | 1.48%   |
| Intel 82579V Gigabit Network Connection                           | 28       | 1.42%   |
| Intel 82574L Gigabit Network Connection                           | 25       | 1.27%   |
| Nvidia MCP61 Ethernet                                             | 23       | 1.17%   |
| Intel Ethernet Connection (7) I219-V                              | 22       | 1.12%   |
| Intel Ethernet Connection I217-V                                  | 20       | 1.02%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 19       | 0.97%   |
| Intel Ethernet Connection (2) I219-LM                             | 18       | 0.92%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 17       | 0.87%   |
| Intel Ethernet Connection (2) I218-V                              | 16       | 0.81%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 14       | 0.71%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 14       | 0.71%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 11       | 0.56%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 10       | 0.51%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 10       | 0.51%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 10       | 0.51%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 10       | 0.51%   |
| Intel Ethernet Controller X550                                    | 10       | 0.51%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 9        | 0.46%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 9        | 0.46%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 9        | 0.46%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 8        | 0.41%   |
| Intel I350 Gigabit Network Connection                             | 8        | 0.41%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 7        | 0.36%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7        | 0.36%   |
| Intel Ethernet Connection (7) I219-LM                             | 7        | 0.36%   |
| Intel Ethernet Connection (2) I218-LM                             | 7        | 0.36%   |
| Intel Ethernet Connection (11) I219-V                             | 7        | 0.36%   |
| Mellanox MT27500 Family [ConnectX-3]                              | 6        | 0.31%   |
| Intel Ethernet Connection (5) I219-LM                             | 6        | 0.31%   |
| Intel 82583V Gigabit Network Connection                           | 6        | 0.31%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1739     | 78.26%  |
| WiFi     | 458      | 20.61%  |
| Modem    | 23       | 1.04%   |
| Unknown  | 2        | 0.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1554     | 88.9%   |
| WiFi     | 194      | 11.1%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1240     | 70.74%  |
| 2     | 380      | 21.68%  |
| 3     | 81       | 4.62%   |
| 4     | 19       | 1.08%   |
| 5     | 11       | 0.63%   |
| 6     | 7        | 0.4%    |
| 0     | 7        | 0.4%    |
| 8     | 3        | 0.17%   |
| 7     | 2        | 0.11%   |
| 13    | 1        | 0.06%   |
| 12    | 1        | 0.06%   |
| 9     | 1        | 0.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1459     | 83.18%  |
| Yes  | 295      | 16.82%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 166      | 45.98%  |
| Cambridge Silicon Radio         | 87       | 24.1%   |
| Realtek Semiconductor           | 26       | 7.2%    |
| Broadcom                        | 21       | 5.82%   |
| ASUSTek Computer                | 18       | 4.99%   |
| Qualcomm Atheros Communications | 12       | 3.32%   |
| IMC Networks                    | 8        | 2.22%   |
| MediaTek                        | 7        | 1.94%   |
| Apple                           | 3        | 0.83%   |
| Belkin Components               | 2        | 0.55%   |
| Toshiba                         | 1        | 0.28%   |
| Sitecom Europe                  | 1        | 0.28%   |
| Realtek                         | 1        | 0.28%   |
| Microsoft                       | 1        | 0.28%   |
| Micro Star International        | 1        | 0.28%   |
| Lite-On Technology              | 1        | 0.28%   |
| Integrated System Solution      | 1        | 0.28%   |
| Foxconn / Hon Hai               | 1        | 0.28%   |
| Edimax Technology               | 1        | 0.28%   |
| Dynex                           | 1        | 0.28%   |
| Unknown                         | 1        | 0.28%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)       | 87       | 24.03%  |
| Intel AX200 Bluetooth                                     | 57       | 15.75%  |
| Intel Bluetooth wireless interface                        | 39       | 10.77%  |
| Realtek Bluetooth Radio                                   | 20       | 5.52%   |
| Intel Wireless-AC 3168 Bluetooth                          | 19       | 5.25%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                  | 13       | 3.59%   |
| Broadcom BCM20702A0 Bluetooth 4.0                         | 13       | 3.59%   |
| Intel AX210 Bluetooth                                     | 12       | 3.31%   |
| Intel AX201 Bluetooth                                     | 12       | 3.31%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)            | 11       | 3.04%   |
| MediaTek Wireless_Device                                  | 7        | 1.93%   |
| ASUS Broadcom BCM20702A0 Bluetooth                        | 7        | 1.93%   |
| Realtek  Bluetooth 4.2 Adapter                            | 5        | 1.38%   |
| Qualcomm Atheros  Bluetooth Device                        | 4        | 1.1%    |
| Intel Centrino Bluetooth Wireless Transceiver             | 4        | 1.1%    |
| IMC Networks Bluetooth Radio                              | 4        | 1.1%    |
| Qualcomm Atheros Bluetooth USB Host Controller            | 3        | 0.83%   |
| IMC Networks Bluetooth Device                             | 3        | 0.83%   |
| ASUS Bluetooth Radio                                      | 3        | 0.83%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                    | 2        | 0.55%   |
| Qualcomm Atheros AR9462 Bluetooth                         | 2        | 0.55%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE     | 2        | 0.55%   |
| ASUS Bluetooth Adapter                                    | 2        | 0.55%   |
| ASUS ASUS USB-BT500                                       | 2        | 0.55%   |
| Apple Bluetooth USB Host Controller                       | 2        | 0.55%   |
| Toshiba Atheros AR3012 Bluetooth                          | 1        | 0.28%   |
| Sitecom Europe Sitecom bluetooth2.0 class 1 dongle CN-521 | 1        | 0.28%   |
| Realtek Bluetooth 5.1 Radio                               | 1        | 0.28%   |
| Realtek Bluetooth Radio                                   | 1        | 0.28%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                     | 1        | 0.28%   |
| Microsoft Wireless Transceiver for Bluetooth              | 1        | 0.28%   |
| Micro Star International Bluetooth EDR Device             | 1        | 0.28%   |
| Lite-On Atheros AR3012 Bluetooth                          | 1        | 0.28%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter     | 1        | 0.28%   |
| IMC Networks Bluetooth                                    | 1        | 0.28%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller           | 1        | 0.28%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter   | 1        | 0.28%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]  | 1        | 0.28%   |
| Broadcom HP Portable Bumble Bee                           | 1        | 0.28%   |
| Broadcom Bluetooth 3.0 Dongle                             | 1        | 0.28%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 1165     | 45.94%  |
| Nvidia                                       | 556      | 21.92%  |
| AMD                                          | 534      | 21.06%  |
| C-Media Electronics                          | 47       | 1.85%   |
| Creative Labs                                | 22       | 0.87%   |
| Logitech                                     | 21       | 0.83%   |
| Texas Instruments                            | 13       | 0.51%   |
| ASUSTek Computer                             | 12       | 0.47%   |
| Generalplus Technology                       | 10       | 0.39%   |
| Focusrite-Novation                           | 10       | 0.39%   |
| VIA Technologies                             | 9        | 0.35%   |
| Kingston Technology                          | 9        | 0.35%   |
| Creative Technology                          | 8        | 0.32%   |
| JMTek                                        | 7        | 0.28%   |
| Plantronics                                  | 6        | 0.24%   |
| GYROCOM C&C                                  | 6        | 0.24%   |
| SteelSeries ApS                              | 5        | 0.2%    |
| RODE Microphones                             | 5        | 0.2%    |
| Micro Star International                     | 5        | 0.2%    |
| GN Netcom                                    | 5        | 0.2%    |
| Cambridge Silicon Radio                      | 5        | 0.2%    |
| Yamaha                                       | 4        | 0.16%   |
| Unknown                                      | 4        | 0.16%   |
| BEHRINGER International                      | 4        | 0.16%   |
| Sennheiser Communications                    | 3        | 0.12%   |
| Samson Technologies                          | 3        | 0.12%   |
| Razer USA                                    | 3        | 0.12%   |
| Dell                                         | 3        | 0.12%   |
| Blue Microphones                             | 3        | 0.12%   |
| Zoran Co. Personal Media Division (Nogatech) | 2        | 0.08%   |
| XMOS                                         | 2        | 0.08%   |
| TerraTec Electronic                          | 2        | 0.08%   |
| Tenx Technology                              | 2        | 0.08%   |
| ROCCAT                                       | 2        | 0.08%   |
| Microsoft                                    | 2        | 0.08%   |
| M-Audio                                      | 2        | 0.08%   |
| Huawei Technologies                          | 2        | 0.08%   |
| Valve Software                               | 1        | 0.04%   |
| TEAC                                         | 1        | 0.04%   |
| Silicon Integrated Systems [SiS]             | 1        | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 175      | 5.97%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 145      | 4.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 134      | 4.57%   |
| AMD Starship/Matisse HD Audio Controller                                   | 131      | 4.47%   |
| Intel 200 Series PCH HD Audio                                              | 118      | 4.02%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 108      | 3.68%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 106      | 3.61%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 92       | 3.14%   |
| AMD Family 17h/19h HD Audio Controller                                     | 86       | 2.93%   |
| Nvidia GF108 High Definition Audio Controller                              | 73       | 2.49%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 66       | 2.25%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 60       | 2.05%   |
| Nvidia GP107GL High Definition Audio Controller                            | 56       | 1.91%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 55       | 1.88%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 54       | 1.84%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 48       | 1.64%   |
| Intel Comet Lake PCH cAVS                                                  | 46       | 1.57%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 42       | 1.43%   |
| Intel Cannon Lake PCH cAVS                                                 | 41       | 1.4%    |
| Intel Audio device                                                         | 37       | 1.26%   |
| AMD FCH Azalia Controller                                                  | 35       | 1.19%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 34       | 1.16%   |
| Nvidia GP106 High Definition Audio Controller                              | 30       | 1.02%   |
| Nvidia High Definition Audio Controller                                    | 29       | 0.99%   |
| Nvidia TU106 High Definition Audio Controller                              | 28       | 0.95%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 28       | 0.95%   |
| Intel Comet Lake PCH-V cAVS                                                | 27       | 0.92%   |
| Nvidia GP104 High Definition Audio Controller                              | 25       | 0.85%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 25       | 0.85%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 25       | 0.85%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 24       | 0.82%   |
| Nvidia TU116 High Definition Audio Controller                              | 23       | 0.78%   |
| Nvidia MCP61 High Definition Audio                                         | 23       | 0.78%   |
| Nvidia GP108 High Definition Audio Controller                              | 23       | 0.78%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 23       | 0.78%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 23       | 0.78%   |
| AMD Navi 10 HDMI Audio                                                     | 22       | 0.75%   |
| Nvidia GM204 High Definition Audio Controller                              | 19       | 0.65%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 19       | 0.65%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 19       | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 307      | 17.98%  |
| Unknown             | 261      | 15.29%  |
| Crucial             | 250      | 14.65%  |
| Samsung Electronics | 163      | 9.55%   |
| SK hynix            | 155      | 9.08%   |
| Corsair             | 123      | 7.21%   |
| G.Skill             | 92       | 5.39%   |
| Micron Technology   | 67       | 3.93%   |
| Patriot             | 56       | 3.28%   |
| A-DATA Technology   | 23       | 1.35%   |
| Hikvision           | 21       | 1.23%   |
| Unknown             | 20       | 1.17%   |
| Ramaxel Technology  | 16       | 0.94%   |
| Team                | 15       | 0.88%   |
| AMD                 | 14       | 0.82%   |
| Nanya Technology    | 11       | 0.64%   |
| Elpida              | 10       | 0.59%   |
| Unknown (ABCD)      | 9        | 0.53%   |
| Transcend           | 5        | 0.29%   |
| Smart               | 5        | 0.29%   |
| GeIL                | 5        | 0.29%   |
| Timetec             | 4        | 0.23%   |
| Qimonda             | 4        | 0.23%   |
| GOODRAM             | 4        | 0.23%   |
| Toshiba             | 3        | 0.18%   |
| Kingmax             | 3        | 0.18%   |
| Hewlett-Packard     | 3        | 0.18%   |
| V-Color             | 2        | 0.12%   |
| Unifosa             | 2        | 0.12%   |
| Silicon Power       | 2        | 0.12%   |
| Kllisre             | 2        | 0.12%   |
| KLEVV               | 2        | 0.12%   |
| Kimtigo             | 2        | 0.12%   |
| KETECH              | 2        | 0.12%   |
| Infineon            | 2        | 0.12%   |
| Goldkey             | 2        | 0.12%   |
| Apacer              | 2        | 0.12%   |
| 48spaces            | 2        | 0.12%   |
| Wilk Elektronik     | 1        | 0.06%   |
| Wilk                | 1        | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM SDRAM                            | 37       | 1.96%   |
| Kingston RAM 99U5584-010.A00LF 4GB DIMM DDR3 1866MT/s        | 33       | 1.75%   |
| Crucial RAM CT8G4DFRA266.M16FG 8GB DIMM DDR4 2666MT/s        | 31       | 1.65%   |
| Crucial RAM CT4G4DFS8213.C8FAR2 4GB DIMM DDR4 2133MT/s       | 26       | 1.38%   |
| Crucial RAM CT8G4DFRA266.C8FN 8GB DIMM DDR4 2866MT/s         | 24       | 1.27%   |
| Hikvision RAM HKED4161DAA1D0MA1 16GB DIMM DDR4 2667MT/s      | 20       | 1.06%   |
| Unknown                                                      | 20       | 1.06%   |
| Unknown RAM Module 2GB DIMM 800MT/s                          | 18       | 0.96%   |
| Unknown RAM Module 1GB DIMM SDRAM                            | 18       | 0.96%   |
| SK hynix RAM HMA82GU6JJR8N-VK 16GB DIMM DDR4 2667MT/s        | 18       | 0.96%   |
| Patriot RAM PSD34G160081 4096MB DIMM DDR3 1600MT/s           | 16       | 0.85%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                         | 14       | 0.74%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                     | 14       | 0.74%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s        | 14       | 0.74%   |
| Unknown RAM Module 1GB DIMM 800MT/s                          | 13       | 0.69%   |
| Patriot RAM PSD32G13332 2GB DIMM DDR3 1333MT/s               | 13       | 0.69%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                         | 12       | 0.64%   |
| Crucial RAM CT8G4DFRA32A.M4FE 8GB DIMM DDR4 3200MT/s         | 12       | 0.64%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s            | 10       | 0.53%   |
| Crucial RAM CT8G4DFD8213.C16FAR2 8GB DIMM DDR4 2133MT/s      | 10       | 0.53%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 9        | 0.48%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s          | 9        | 0.48%   |
| Unknown RAM Module 2GB DIMM 1066MT/s                         | 8        | 0.42%   |
| Patriot RAM PSD32G133381 2GB DIMM DDR3 1333MT/s              | 8        | 0.42%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s       | 8        | 0.42%   |
| Kingston RAM 99U5474-013.A00LF 2GB DIMM DDR3 1600MT/s        | 8        | 0.42%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s        | 8        | 0.42%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM 1600MT/s               | 7        | 0.37%   |
| Samsung RAM M378A1K43DB2-CTD 8GB DIMM DDR4 4333MT/s          | 7        | 0.37%   |
| Patriot RAM PSD38G13332 8192MB DIMM DDR3 1333MT/s            | 7        | 0.37%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s        | 7        | 0.37%   |
| Kingston RAM 99U5474-025.A00LF 2GB DIMM DDR3 1333MT/s        | 7        | 0.37%   |
| Kingston RAM 9905474-012.A00LF 2GB DIMM DDR3 1333MT/s        | 7        | 0.37%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s          | 7        | 0.37%   |
| Crucial RAM CT25664BA160B.D8FE 2GB DIMM DDR3 1600MT/s        | 7        | 0.37%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                    | 6        | 0.32%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                    | 6        | 0.32%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                     | 6        | 0.32%   |
| Unknown RAM Module 1GB DIMM                                  | 6        | 0.32%   |
| Samsung RAM M391A4G43AB1-CWE 32GB DIMM DDR4 3200MT/s         | 6        | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind         | Desktops | Percent |
|--------------|----------|---------|
| DDR4         | 678      | 44.43%  |
| DDR3         | 528      | 34.6%   |
| Unknown      | 112      | 7.34%   |
| SDRAM        | 95       | 6.23%   |
| DDR2         | 76       | 4.98%   |
| DDR          | 19       | 1.25%   |
| LPDDR4       | 11       | 0.72%   |
| DRAM         | 3        | 0.2%    |
| DDR5         | 3        | 0.2%    |
| DDR2 FB-DIMM | 1        | 0.07%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 1421     | 94.36%  |
| SODIMM       | 75       | 4.98%   |
| FB-DIMM      | 4        | 0.27%   |
| Row Of Chips | 2        | 0.13%   |
| RIMM         | 2        | 0.13%   |
| Chip         | 1        | 0.07%   |
| Unknown      | 1        | 0.07%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 529      | 31.94%  |
| 4096  | 390      | 23.55%  |
| 2048  | 288      | 17.39%  |
| 16384 | 225      | 13.59%  |
| 1024  | 96       | 5.8%    |
| 32768 | 95       | 5.74%   |
| 512   | 22       | 1.33%   |
| 256   | 6        | 0.36%   |
| 65536 | 3        | 0.18%   |
| 1536  | 1        | 0.06%   |
| 128   | 1        | 0.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 296      | 18.03%  |
| 1333    | 197      | 12%     |
| 3200    | 136      | 8.28%   |
| 2667    | 128      | 7.8%    |
| 2400    | 104      | 6.33%   |
| 2133    | 82       | 4.99%   |
| 800     | 82       | 4.99%   |
| 3600    | 71       | 4.32%   |
| Unknown | 71       | 4.32%   |
| 2666    | 56       | 3.41%   |
| 1866    | 56       | 3.41%   |
| 667     | 43       | 2.62%   |
| 3000    | 25       | 1.52%   |
| 2866    | 25       | 1.52%   |
| 3400    | 24       | 1.46%   |
| 1066    | 23       | 1.4%    |
| 3466    | 19       | 1.16%   |
| 1867    | 19       | 1.16%   |
| 1067    | 19       | 1.16%   |
| 2933    | 16       | 0.97%   |
| 1800    | 16       | 0.97%   |
| 3733    | 13       | 0.79%   |
| 400     | 10       | 0.61%   |
| 3866    | 9        | 0.55%   |
| 3800    | 8        | 0.49%   |
| 1334    | 8        | 0.49%   |
| 4333    | 7        | 0.43%   |
| 533     | 7        | 0.43%   |
| 3066    | 6        | 0.37%   |
| 4800    | 5        | 0.3%    |
| 3100    | 5        | 0.3%    |
| 2048    | 5        | 0.3%    |
| 3500    | 4        | 0.24%   |
| 2800    | 4        | 0.24%   |
| 1648    | 4        | 0.24%   |
| 333     | 4        | 0.24%   |
| 2733    | 3        | 0.18%   |
| 2465    | 3        | 0.18%   |
| 1400    | 3        | 0.18%   |
| 266     | 3        | 0.18%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 29       | 41.43%  |
| Brother Industries  | 13       | 18.57%  |
| Samsung Electronics | 5        | 7.14%   |
| Canon               | 4        | 5.71%   |
| Xerox               | 3        | 4.29%   |
| Dymo-CoStar         | 3        | 4.29%   |
| Zebra               | 2        | 2.86%   |
| Seiko Epson         | 2        | 2.86%   |
| Prolific Technology | 2        | 2.86%   |
| Pantum              | 2        | 2.86%   |
| STMicroelectronics  | 1        | 1.43%   |
| Kyocera             | 1        | 1.43%   |
| Konica Minolta      | 1        | 1.43%   |
| GODEX INTERNATIONAL | 1        | 1.43%   |
| Apple               | 1        | 1.43%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Xerox B205                                                | 3        | 4.29%   |
| HP LaserJet M101-M106                                     | 3        | 4.29%   |
| HP LaserJet 1200                                          | 3        | 4.29%   |
| HP LaserJet 1020                                          | 3        | 4.29%   |
| Samsung ML-1660 Series                                    | 2        | 2.86%   |
| Prolific PL2305 Parallel Port                             | 2        | 2.86%   |
| HP LaserJet P1005                                         | 2        | 2.86%   |
| HP ENVY 4520 series                                       | 2        | 2.86%   |
| Zebra ZTC ZP 500 (ZPL)                                    | 1        | 1.43%   |
| Zebra ZTC ZD420-203dpi ZPL                                | 1        | 1.43%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1        | 1.43%   |
| Seiko Epson XP-200 Series                                 | 1        | 1.43%   |
| Seiko Epson L4150 Series                                  | 1        | 1.43%   |
| Samsung SCX-4650 4x21S Series                             | 1        | 1.43%   |
| Samsung SCX-3200 Series                                   | 1        | 1.43%   |
| Samsung ML-216x Series Laser Printer                      | 1        | 1.43%   |
| Pantum P2500W series                                      | 1        | 1.43%   |
| Pantum M6500-series                                       | 1        | 1.43%   |
| Kyocera ECOSYS M5521cdn                                   | 1        | 1.43%   |
| Konica Minolta bizhub 4402P                               | 1        | 1.43%   |
| HP Officejet J4500 series                                 | 1        | 1.43%   |
| HP Officejet 7110 series                                  | 1        | 1.43%   |
| HP LaserJet Pro M404-M405                                 | 1        | 1.43%   |
| HP LaserJet Pro M148-M149                                 | 1        | 1.43%   |
| HP LaserJet P2055 series                                  | 1        | 1.43%   |
| HP Laserjet P1505                                         | 1        | 1.43%   |
| HP LaserJet P1006                                         | 1        | 1.43%   |
| HP LaserJet M14-M17                                       | 1        | 1.43%   |
| HP LaserJet 400 M401dne                                   | 1        | 1.43%   |
| HP LaserJet 1300                                          | 1        | 1.43%   |
| HP LaserJet 1150                                          | 1        | 1.43%   |
| HP LaserJet 1015                                          | 1        | 1.43%   |
| HP ENVY Photo 6200 series                                 | 1        | 1.43%   |
| HP ENVY 5000 series                                       | 1        | 1.43%   |
| HP Deskjet 4640 series                                    | 1        | 1.43%   |
| HP DeskJet 2620 All-in-One Printer                        | 1        | 1.43%   |
| GODEX INTERNATIONAL DT2                                   | 1        | 1.43%   |
| Dymo-CoStar LabelWriter 450                               | 1        | 1.43%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo                    | 1        | 1.43%   |
| Dymo-CoStar DYMO LabelWriter 450 DUO                      | 1        | 1.43%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 10       | 55.56%  |
| Seiko Epson     | 3        | 16.67%  |
| Hewlett-Packard | 3        | 16.67%  |
| AGFA-Gevaert NV | 2        | 11.11%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 220                                       | 3        | 16.67%  |
| Canon CanoScan N670U/N676U/LiDE 20                            | 2        | 11.11%  |
| Canon CanoScan LiDE 110                                       | 2        | 11.11%  |
| AGFA-Gevaert NV SnapScan 1212U (?)                            | 2        | 11.11%  |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]             | 1        | 5.56%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]      | 1        | 5.56%   |
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1        | 5.56%   |
| HP ScanJet Pro 2500 f1                                        | 1        | 5.56%   |
| HP ScanJet 3970c                                              | 1        | 5.56%   |
| HP Scanjet 300                                                | 1        | 5.56%   |
| Canon CanoScan LiDE 210                                       | 1        | 5.56%   |
| Canon CanoScan 8800F                                          | 1        | 5.56%   |
| Canon CanoScan 5600F                                          | 1        | 5.56%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 97       | 43.5%   |
| Microdia                      | 18       | 8.07%   |
| Generalplus Technology        | 12       | 5.38%   |
| Sunplus Innovation Technology | 10       | 4.48%   |
| Samsung Electronics           | 7        | 3.14%   |
| Microsoft                     | 7        | 3.14%   |
| Apple                         | 7        | 3.14%   |
| Creative Technology           | 6        | 2.69%   |
| KYE Systems (Mouse Systems)   | 5        | 2.24%   |
| Z-Star Microelectronics       | 4        | 1.79%   |
| Jieli Technology              | 4        | 1.79%   |
| ARC International             | 4        | 1.79%   |
| Novatek Microelectronics      | 3        | 1.35%   |
| Genesys Logic                 | 3        | 1.35%   |
| Xiongmai                      | 2        | 0.9%    |
| Nintendo                      | 2        | 0.9%    |
| MacroSilicon                  | 2        | 0.9%    |
| GEMBIRD                       | 2        | 0.9%    |
| Chicony Electronics           | 2        | 0.9%    |
| AVerMedia Technologies        | 2        | 0.9%    |
| Xiaomi                        | 1        | 0.45%   |
| WaveRider Communications      | 1        | 0.45%   |
| Valve Software                | 1        | 0.45%   |
| Unknown                       | 1        | 0.45%   |
| Trust                         | 1        | 0.45%   |
| SunplusIT                     | 1        | 0.45%   |
| SiGma Micro                   | 1        | 0.45%   |
| Ruision                       | 1        | 0.45%   |
| Realtek Semiconductor         | 1        | 0.45%   |
| Razer USA                     | 1        | 0.45%   |
| Mimaki Engineering            | 1        | 0.45%   |
| Linux Foundation              | 1        | 0.45%   |
| Lenovo                        | 1        | 0.45%   |
| IMC Networks                  | 1        | 0.45%   |
| Huawei Technologies           | 1        | 0.45%   |
| Hewlett-Packard               | 1        | 0.45%   |
| Google                        | 1        | 0.45%   |
| GenesysLogic Technology       | 1        | 0.45%   |
| EVGA                          | 1        | 0.45%   |
| eMPIA Technology              | 1        | 0.45%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| Logitech Webcam C270                      | 36       | 16%     |
| Logitech C922 Pro Stream Webcam           | 12       | 5.33%   |
| Logitech HD Pro Webcam C920               | 9        | 4%      |
| Samsung Galaxy series, misc. (MTP mode)   | 7        | 3.11%   |
| Generalplus GENERAL WEBCAM                | 7        | 3.11%   |
| Apple iPhone 5/5C/5S/6/SE                 | 7        | 3.11%   |
| Microdia Webcam Vitade AF                 | 6        | 2.67%   |
| Logitech Webcam C170                      | 6        | 2.67%   |
| Microsoft LifeCam HD-3000                 | 4        | 1.78%   |
| Microdia Hy-HD-Camera                     | 4        | 1.78%   |
| Logitech HD Webcam C615                   | 4        | 1.78%   |
| Jieli USB PHY 2.0                         | 4        | 1.78%   |
| Z-Star Venus USB2.0 Camera                | 3        | 1.33%   |
| Novatek HP High Definition 2MP Webcam     | 3        | 1.33%   |
| Microdia USB 2.0 Camera                   | 3        | 1.33%   |
| Logitech Logi Webcam C920e                | 3        | 1.33%   |
| Logitech HD Webcam C910                   | 3        | 1.33%   |
| Logitech C920 PRO HD Webcam               | 3        | 1.33%   |
| Logitech BRIO                             | 3        | 1.33%   |
| KYE Systems (Mouse Systems) Genius Webcam | 3        | 1.33%   |
| Generalplus 808 Camera                    | 3        | 1.33%   |
| Xiongmai web camera                       | 2        | 0.89%   |
| Sunplus Full HD webcam                    | 2        | 0.89%   |
| Sunplus FHD Camera Microphone             | 2        | 0.89%   |
| Nintendo USB Camera                       | 2        | 0.89%   |
| Microdia Sonix USB 2.0 Camera             | 2        | 0.89%   |
| Logitech Webcam C925e                     | 2        | 0.89%   |
| Logitech Webcam C310                      | 2        | 0.89%   |
| Logitech StreamCam                        | 2        | 0.89%   |
| Genesys Logic USB2.0 Digital Camera       | 2        | 0.89%   |
| Generalplus WEB CAM                       | 2        | 0.89%   |
| Creative Live! Cam Optia AF               | 2        | 0.89%   |
| Creative Live! Cam Chat HD [VF0700]       | 2        | 0.89%   |
| ARC International Camera - 1080p          | 2        | 0.89%   |
| ARC International Camera                  | 2        | 0.89%   |
| Z-Star Integrated Camera                  | 1        | 0.44%   |
| Xiaomi Redmi Note 10 Pro                  | 1        | 0.44%   |
| WaveRider USB 2.0 Camera                  | 1        | 0.44%   |
| Valve Software 3D Camera                  | 1        | 0.44%   |
| Unknown Konftel Cam20                     | 1        | 0.44%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Validity Sensors | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Gemalto (was Gemplus) | 2        | 20%     |
| Alcor Micro           | 2        | 20%     |
| Yubico.com            | 1        | 10%     |
| SCM Microsystems      | 1        | 10%     |
| Lenovo                | 1        | 10%     |
| Clay Logic            | 1        | 10%     |
| Chicony Electronics   | 1        | 10%     |
| Cherry                | 1        | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Yubico.com Yubikey 4/5 CCID                          | 1        | 10%     |
| SCM Microsystems uTrust 3512 SAM slot Token          | 1        | 10%     |
| Lenovo Smartcard Keyboard                            | 1        | 10%     |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader    | 1        | 10%     |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader     | 1        | 10%     |
| Clay Logic Nitrokey Pro                              | 1        | 10%     |
| Chicony Electronics HP Skylab USB Smartcard Keyboard | 1        | 10%     |
| Cherry SmartTerminal XX1X                            | 1        | 10%     |
| Alcor Micro Watchdata W 1981                         | 1        | 10%     |
| Alcor Micro AU9540 Smartcard Reader                  | 1        | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 959      | 54.49%  |
| 1     | 719      | 40.85%  |
| 2     | 71       | 4.03%   |
| 3     | 7        | 0.4%    |
| 4     | 2        | 0.11%   |
| 7     | 1        | 0.06%   |
| 5     | 1        | 0.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 696      | 82.46%  |
| Net/wireless             | 43       | 5.09%   |
| Unassigned class         | 26       | 3.08%   |
| Communication controller | 23       | 2.73%   |
| Sound                    | 13       | 1.54%   |
| Multimedia controller    | 10       | 1.18%   |
| Bluetooth                | 8        | 0.95%   |
| Card reader              | 5        | 0.59%   |
| Net/ethernet             | 4        | 0.47%   |
| Modem                    | 3        | 0.36%   |
| Chipcard                 | 3        | 0.36%   |
| Tv card                  | 2        | 0.24%   |
| Storage/raid             | 2        | 0.24%   |
| Camera                   | 2        | 0.24%   |
| Storage                  | 1        | 0.12%   |
| Network                  | 1        | 0.12%   |
| Fingerprint reader       | 1        | 0.12%   |
| Dvb card                 | 1        | 0.12%   |

