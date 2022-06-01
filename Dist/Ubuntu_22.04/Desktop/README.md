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

Total: 406

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Alienware     | 0XJKKD A00                  | [ae3a750f2e](https://linux-hardware.org/?probe=ae3a750f2e) | Jun 01, 2022 |
| Intel         | DP67BG AAG10491-305         | [714722d24b](https://linux-hardware.org/?probe=714722d24b) | Jun 01, 2022 |
| MSI           | B250M BAZOOKA               | [45d3300158](https://linux-hardware.org/?probe=45d3300158) | Jun 01, 2022 |
| Dell          | 0NK5PH A00                  | [960e8817bf](https://linux-hardware.org/?probe=960e8817bf) | Jun 01, 2022 |
| Unknown       | SKYBAY                      | [88ef811c4d](https://linux-hardware.org/?probe=88ef811c4d) | May 31, 2022 |
| Pegatron      | 2AED                        | [67df0b1c08](https://linux-hardware.org/?probe=67df0b1c08) | May 31, 2022 |
| Dell          | 07WP95 A02                  | [65ae31976a](https://linux-hardware.org/?probe=65ae31976a) | May 31, 2022 |
| Dell          | 0200DY A01                  | [0d7be8de90](https://linux-hardware.org/?probe=0d7be8de90) | May 31, 2022 |
| MSI           | B450-A PRO MAX              | [72484e859d](https://linux-hardware.org/?probe=72484e859d) | May 31, 2022 |
| Dell          | 0200DY A01                  | [c3c585ba02](https://linux-hardware.org/?probe=c3c585ba02) | May 31, 2022 |
| Unknown       | Unknown                     | [c2d6d647d8](https://linux-hardware.org/?probe=c2d6d647d8) | May 31, 2022 |
| MSI           | B450-A PRO MAX              | [9f7d224ed7](https://linux-hardware.org/?probe=9f7d224ed7) | May 31, 2022 |
| ASUSTek       | Rampage V EDITION 10        | [ab6fb60b96](https://linux-hardware.org/?probe=ab6fb60b96) | May 31, 2022 |
| ASUSTek       | H81M-A                      | [d24672a3cd](https://linux-hardware.org/?probe=d24672a3cd) | May 31, 2022 |
| Intel         | DP67BG AAG10491-305         | [966ab11802](https://linux-hardware.org/?probe=966ab11802) | May 31, 2022 |
| Gigabyte      | Q35M-S2                     | [7ef3498226](https://linux-hardware.org/?probe=7ef3498226) | May 30, 2022 |
| ASRock        | 870 Extreme3                | [7e2000d3a1](https://linux-hardware.org/?probe=7e2000d3a1) | May 30, 2022 |
| Gigabyte      | Z87X-UD3H-CF                | [b0e96de917](https://linux-hardware.org/?probe=b0e96de917) | May 30, 2022 |
| ASUSTek       | PRO H410M-C                 | [c40635b66e](https://linux-hardware.org/?probe=c40635b66e) | May 30, 2022 |
| Unknown       | Unknown                     | [59d0634230](https://linux-hardware.org/?probe=59d0634230) | May 30, 2022 |
| Gigabyte      | Z87X-UD3H-CF                | [b4f73129a2](https://linux-hardware.org/?probe=b4f73129a2) | May 30, 2022 |
| ASUSTek       | M5A78L LE                   | [44e2ec7714](https://linux-hardware.org/?probe=44e2ec7714) | May 30, 2022 |
| ASUSTek       | X99-E-10G WS                | [83e525ca4e](https://linux-hardware.org/?probe=83e525ca4e) | May 30, 2022 |
| ECS           | MCP61M-M3                   | [b785b68657](https://linux-hardware.org/?probe=b785b68657) | May 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [0b83e8fa79](https://linux-hardware.org/?probe=0b83e8fa79) | May 29, 2022 |
| Intel         | DQ35JO AAD82085-803         | [40429e6d9a](https://linux-hardware.org/?probe=40429e6d9a) | May 29, 2022 |
| Biostar       | G41U3G                      | [1c6caef665](https://linux-hardware.org/?probe=1c6caef665) | May 29, 2022 |
| MSI           | H510I PRO WIFI              | [b4b8c3db64](https://linux-hardware.org/?probe=b4b8c3db64) | May 29, 2022 |
| ASUSTek       | PRO H410M-C                 | [bcca466c5e](https://linux-hardware.org/?probe=bcca466c5e) | May 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [c11ae8de66](https://linux-hardware.org/?probe=c11ae8de66) | May 29, 2022 |
| Gigabyte      | Z87X-UD3H-CF                | [c1dd2cf1be](https://linux-hardware.org/?probe=c1dd2cf1be) | May 29, 2022 |
| Gigabyte      | Z87X-UD3H-CF                | [0df520da7e](https://linux-hardware.org/?probe=0df520da7e) | May 29, 2022 |
| ASUSTek       | PRO H410M-C                 | [b83d80f5d2](https://linux-hardware.org/?probe=b83d80f5d2) | May 29, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | [7fd1e065eb](https://linux-hardware.org/?probe=7fd1e065eb) | May 29, 2022 |
| Shuttle       | FS81                        | [756f86d9fc](https://linux-hardware.org/?probe=756f86d9fc) | May 28, 2022 |
| Acer          | Veriton X2631G V:1.0        | [3c144d36f0](https://linux-hardware.org/?probe=3c144d36f0) | May 28, 2022 |
| Pegatron      | 2ACF                        | [bd97a6b3dd](https://linux-hardware.org/?probe=bd97a6b3dd) | May 28, 2022 |
| ASUSTek       | H110M-K                     | [9ff7306bbd](https://linux-hardware.org/?probe=9ff7306bbd) | May 28, 2022 |
| Gigabyte      | B150M-D3H-CF                | [e5fdf1083f](https://linux-hardware.org/?probe=e5fdf1083f) | May 28, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c0399b42b7](https://linux-hardware.org/?probe=c0399b42b7) | May 28, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | [1094233e96](https://linux-hardware.org/?probe=1094233e96) | May 28, 2022 |
| Dell          | 0C2XKD A01                  | [2aaa53dd85](https://linux-hardware.org/?probe=2aaa53dd85) | May 28, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [5458522367](https://linux-hardware.org/?probe=5458522367) | May 28, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [ce112fb9d2](https://linux-hardware.org/?probe=ce112fb9d2) | May 28, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [bd7aea9bfd](https://linux-hardware.org/?probe=bd7aea9bfd) | May 28, 2022 |
| Acer          | Veriton X2631G V:1.0        | [26e26a3995](https://linux-hardware.org/?probe=26e26a3995) | May 28, 2022 |
| MSI           | B450 TOMAHAWK               | [2651c1881a](https://linux-hardware.org/?probe=2651c1881a) | May 27, 2022 |
| Dell          | 0GXM1W A02                  | [8e0891e3c7](https://linux-hardware.org/?probe=8e0891e3c7) | May 27, 2022 |
| Dell          | 09KPNV A01                  | [b98a471ead](https://linux-hardware.org/?probe=b98a471ead) | May 27, 2022 |
| Dell          | 09KPNV A01                  | [44162ea497](https://linux-hardware.org/?probe=44162ea497) | May 27, 2022 |
| ASUSTek       | P5G41T-M LX                 | [5dbf3199e0](https://linux-hardware.org/?probe=5dbf3199e0) | May 27, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [f5beaba229](https://linux-hardware.org/?probe=f5beaba229) | May 27, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [2624ebd3a1](https://linux-hardware.org/?probe=2624ebd3a1) | May 27, 2022 |
| ASUSTek       | B150-PLUS                   | [bdcda1dabc](https://linux-hardware.org/?probe=bdcda1dabc) | May 27, 2022 |
| Gigabyte      | Z590 VISION G               | [586d86827b](https://linux-hardware.org/?probe=586d86827b) | May 27, 2022 |
| Dell          | 0YJPT1 A00                  | [b122151e55](https://linux-hardware.org/?probe=b122151e55) | May 27, 2022 |
| Gigabyte      | Z77X-UD3H                   | [0cf6ee749e](https://linux-hardware.org/?probe=0cf6ee749e) | May 27, 2022 |
| ASUSTek       | STRIKER II FORMULA          | [f10aecd449](https://linux-hardware.org/?probe=f10aecd449) | May 27, 2022 |
| ASUSTek       | STRIKER II FORMULA          | [df37e5c694](https://linux-hardware.org/?probe=df37e5c694) | May 27, 2022 |
| Dell          | 0MY171 A01                  | [9500786a21](https://linux-hardware.org/?probe=9500786a21) | May 26, 2022 |
| ASUSTek       | PRIME X570-P                | [3774c9e6e6](https://linux-hardware.org/?probe=3774c9e6e6) | May 26, 2022 |
| MSI           | A320M-A PRO MAX             | [f1ccdbbba4](https://linux-hardware.org/?probe=f1ccdbbba4) | May 26, 2022 |
| ASUSTek       | PRIME X570-P                | [f52de609a0](https://linux-hardware.org/?probe=f52de609a0) | May 26, 2022 |
| ASUSTek       | PRO H410M-C                 | [e38c676047](https://linux-hardware.org/?probe=e38c676047) | May 26, 2022 |
| Gigabyte      | GA-E7AUM-DS2H               | [9f18dbe621](https://linux-hardware.org/?probe=9f18dbe621) | May 26, 2022 |
| ASRock        | Z270 Gaming K6              | [fbf8e08024](https://linux-hardware.org/?probe=fbf8e08024) | May 25, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | [9d9a7dc189](https://linux-hardware.org/?probe=9d9a7dc189) | May 25, 2022 |
| ASRock        | AB350M Pro4                 | [dd39f18241](https://linux-hardware.org/?probe=dd39f18241) | May 25, 2022 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | [200070a992](https://linux-hardware.org/?probe=200070a992) | May 25, 2022 |
| Gigabyte      | G31M-S2C                    | [5251ce0950](https://linux-hardware.org/?probe=5251ce0950) | May 25, 2022 |
| Gigabyte      | Z77X-UD3H                   | [0d439f9812](https://linux-hardware.org/?probe=0d439f9812) | May 25, 2022 |
| Dell          | 0DT029 A00                  | [17b19530f5](https://linux-hardware.org/?probe=17b19530f5) | May 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [a649429f59](https://linux-hardware.org/?probe=a649429f59) | May 25, 2022 |
| Dell          | 096JG8 A01                  | [51aaf4adcd](https://linux-hardware.org/?probe=51aaf4adcd) | May 24, 2022 |
| Dell          | 0WG864                      | [5bda6fbb3a](https://linux-hardware.org/?probe=5bda6fbb3a) | May 24, 2022 |
| Gigabyte      | P55-UD3L                    | [256b5355c3](https://linux-hardware.org/?probe=256b5355c3) | May 24, 2022 |
| Dell          | 0HY9JP A01                  | [4107e267d7](https://linux-hardware.org/?probe=4107e267d7) | May 24, 2022 |
| Gigabyte      | Z590 VISION G               | [1158b31567](https://linux-hardware.org/?probe=1158b31567) | May 24, 2022 |
| MSI           | H97M-G43                    | [4c1e9752b6](https://linux-hardware.org/?probe=4c1e9752b6) | May 23, 2022 |
| ASUSTek       | PRIME B660M-A AC D4         | [286688e46b](https://linux-hardware.org/?probe=286688e46b) | May 23, 2022 |
| ASRock        | 970 Pro3 R2.0               | [afeae78ecd](https://linux-hardware.org/?probe=afeae78ecd) | May 23, 2022 |
| Shuttle       | FS110                       | [d1147263be](https://linux-hardware.org/?probe=d1147263be) | May 23, 2022 |
| Intel         | H55                         | [8dd80b1c9d](https://linux-hardware.org/?probe=8dd80b1c9d) | May 23, 2022 |
| ASUSTek       | PRIME A320M-K               | [be78ab6334](https://linux-hardware.org/?probe=be78ab6334) | May 23, 2022 |
| ASUSTek       | PRIME A320M-K               | [c21c66647d](https://linux-hardware.org/?probe=c21c66647d) | May 23, 2022 |
| ASUSTek       | PRO H410M-C                 | [a700df310a](https://linux-hardware.org/?probe=a700df310a) | May 23, 2022 |
| Intel         | H55                         | [c383403505](https://linux-hardware.org/?probe=c383403505) | May 23, 2022 |
| Gigabyte      | X99-UD4-CF                  | [f5ff0b74e4](https://linux-hardware.org/?probe=f5ff0b74e4) | May 23, 2022 |
| Gigabyte      | X99-UD4-CF                  | [9678842f4f](https://linux-hardware.org/?probe=9678842f4f) | May 23, 2022 |
| Gigabyte      | Z390 UD                     | [d49bf6427c](https://linux-hardware.org/?probe=d49bf6427c) | May 23, 2022 |
| MSI           | 2AE0                        | [ea14a764bb](https://linux-hardware.org/?probe=ea14a764bb) | May 22, 2022 |
| Gigabyte      | AB350M-DS3H-CF              | [ee04d8165a](https://linux-hardware.org/?probe=ee04d8165a) | May 22, 2022 |
| Gigabyte      | Z690 UD DDR4                | [85ec601970](https://linux-hardware.org/?probe=85ec601970) | May 22, 2022 |
| ASRock        | 760GM-HDV                   | [a7c99d7f14](https://linux-hardware.org/?probe=a7c99d7f14) | May 22, 2022 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | [70c677bafe](https://linux-hardware.org/?probe=70c677bafe) | May 22, 2022 |
| ASRock        | 760GM-HDV                   | [a37dd040cc](https://linux-hardware.org/?probe=a37dd040cc) | May 22, 2022 |
| Gigabyte      | Z690 UD DDR4                | [1ceb70430f](https://linux-hardware.org/?probe=1ceb70430f) | May 22, 2022 |
| MSI           | Z97 GAMING 3                | [495bcbd710](https://linux-hardware.org/?probe=495bcbd710) | May 22, 2022 |
| Shuttle       | FS110                       | [4845946b59](https://linux-hardware.org/?probe=4845946b59) | May 22, 2022 |
| HP            | 18E4                        | [e8bc371de1](https://linux-hardware.org/?probe=e8bc371de1) | May 22, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [5f03a4b52d](https://linux-hardware.org/?probe=5f03a4b52d) | May 21, 2022 |
| Gigabyte      | G41MT-D3                    | [aac14b5554](https://linux-hardware.org/?probe=aac14b5554) | May 21, 2022 |
| ASRock        | AB350M-HDV R3.0             | [01fcce62c6](https://linux-hardware.org/?probe=01fcce62c6) | May 21, 2022 |
| Gigabyte      | G41MT-D3                    | [6763ad45ce](https://linux-hardware.org/?probe=6763ad45ce) | May 21, 2022 |
| ASUSTek       | Crosshair IV Formula        | [d6c9df82c6](https://linux-hardware.org/?probe=d6c9df82c6) | May 21, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | [cedcf3fa98](https://linux-hardware.org/?probe=cedcf3fa98) | May 21, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | [72560a6e0c](https://linux-hardware.org/?probe=72560a6e0c) | May 21, 2022 |
| HP            | 18E4                        | [e567895819](https://linux-hardware.org/?probe=e567895819) | May 21, 2022 |
| ASUSTek       | P7H55-M LX                  | [72a96fc8a3](https://linux-hardware.org/?probe=72a96fc8a3) | May 20, 2022 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | [73c9c54bb6](https://linux-hardware.org/?probe=73c9c54bb6) | May 20, 2022 |
| Medion        | H81H3-EM2                   | [ba616a92bf](https://linux-hardware.org/?probe=ba616a92bf) | May 20, 2022 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | [7dcdef576a](https://linux-hardware.org/?probe=7dcdef576a) | May 20, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING     | [162c85f06d](https://linux-hardware.org/?probe=162c85f06d) | May 20, 2022 |
| Gigabyte      | Z590 VISION G               | [6e7143bfd4](https://linux-hardware.org/?probe=6e7143bfd4) | May 20, 2022 |
| Gigabyte      | Z77X-UP7                    | [8b4b27f72d](https://linux-hardware.org/?probe=8b4b27f72d) | May 20, 2022 |
| Dell          | 09M8Y8 A01                  | [f4894739f4](https://linux-hardware.org/?probe=f4894739f4) | May 20, 2022 |
| HP            | 8767 A                      | [a1b50431fa](https://linux-hardware.org/?probe=a1b50431fa) | May 19, 2022 |
| MSI           | MPG B550I GAMING EDGE MA... | [407d3e4f43](https://linux-hardware.org/?probe=407d3e4f43) | May 19, 2022 |
| Intel         | ChiefRiver                  | [8e4aca2b1f](https://linux-hardware.org/?probe=8e4aca2b1f) | May 19, 2022 |
| Intel         | ChiefRiver                  | [4d38806404](https://linux-hardware.org/?probe=4d38806404) | May 19, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [6a9166ca20](https://linux-hardware.org/?probe=6a9166ca20) | May 19, 2022 |
| Dell          | 0HY9JP A01                  | [d845952849](https://linux-hardware.org/?probe=d845952849) | May 19, 2022 |
| Gigabyte      | AX370M-DS3H-CF              | [39fb6cd4e3](https://linux-hardware.org/?probe=39fb6cd4e3) | May 19, 2022 |
| MSI           | B450M PRO-VDH MAX           | [b2eceeef6d](https://linux-hardware.org/?probe=b2eceeef6d) | May 19, 2022 |
| ASUSTek       | PRIME B360M-D               | [6a00f5f597](https://linux-hardware.org/?probe=6a00f5f597) | May 18, 2022 |
| ECS           | GF7050VT-M5                 | [485f780320](https://linux-hardware.org/?probe=485f780320) | May 18, 2022 |
| ASUSTek       | M5A88-V EVO                 | [ab5a307891](https://linux-hardware.org/?probe=ab5a307891) | May 18, 2022 |
| ASUSTek       | PRIME B450M-K               | [54f3323bd2](https://linux-hardware.org/?probe=54f3323bd2) | May 18, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [eaea352b1a](https://linux-hardware.org/?probe=eaea352b1a) | May 18, 2022 |
| Foxconn       | 2ADA                        | [60579b7d68](https://linux-hardware.org/?probe=60579b7d68) | May 18, 2022 |
| Gigabyte      | Z370 AORUS ULTRA GAMING-... | [ea23b1fec2](https://linux-hardware.org/?probe=ea23b1fec2) | May 18, 2022 |
| MSI           | A320M-A PRO MAX             | [13bacdb7b6](https://linux-hardware.org/?probe=13bacdb7b6) | May 18, 2022 |
| ASRock        | FM2A68M-DG3+                | [a1b9d7e608](https://linux-hardware.org/?probe=a1b9d7e608) | May 18, 2022 |
| ASUSTek       | PRIME B450M-K               | [1dba88e243](https://linux-hardware.org/?probe=1dba88e243) | May 18, 2022 |
| ASUSTek       | F2A85-M PRO                 | [99e949c3e8](https://linux-hardware.org/?probe=99e949c3e8) | May 18, 2022 |
| Dell          | 0HN7XN A00                  | [6fba9a10da](https://linux-hardware.org/?probe=6fba9a10da) | May 18, 2022 |
| ASUSTek       | P8H61 PRO                   | [87a148ac90](https://linux-hardware.org/?probe=87a148ac90) | May 18, 2022 |
| ASUSTek       | PRIME A320M-K               | [cb6038cd9b](https://linux-hardware.org/?probe=cb6038cd9b) | May 18, 2022 |
| ASUSTek       | A8N32-SLI-Deluxe            | [78a9ab4d15](https://linux-hardware.org/?probe=78a9ab4d15) | May 17, 2022 |
| ASRock        | 970M Pro3                   | [f08826b5b4](https://linux-hardware.org/?probe=f08826b5b4) | May 17, 2022 |
| HP            | 22F8                        | [70f6561c5c](https://linux-hardware.org/?probe=70f6561c5c) | May 16, 2022 |
| ASUSTek       | PRO H410M-C                 | [1b0cb5afca](https://linux-hardware.org/?probe=1b0cb5afca) | May 16, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | [3bf7390ce3](https://linux-hardware.org/?probe=3bf7390ce3) | May 16, 2022 |
| ASUSTek       | M3N78 PRO                   | [246f442b9b](https://linux-hardware.org/?probe=246f442b9b) | May 15, 2022 |
| Gigabyte      | Z690 UD DDR4                | [e2ed8b47c2](https://linux-hardware.org/?probe=e2ed8b47c2) | May 15, 2022 |
| ASRock        | 970 Pro3 R2.0               | [5ad0b4a6c6](https://linux-hardware.org/?probe=5ad0b4a6c6) | May 15, 2022 |
| Acer          | H57M01                      | [9116ecebcb](https://linux-hardware.org/?probe=9116ecebcb) | May 15, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [d4e303b92c](https://linux-hardware.org/?probe=d4e303b92c) | May 15, 2022 |
| Gigabyte      | H110M-S2-CF                 | [a2fa413622](https://linux-hardware.org/?probe=a2fa413622) | May 15, 2022 |
| ASUSTek       | M3N78 PRO                   | [af5eec886b](https://linux-hardware.org/?probe=af5eec886b) | May 15, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [021f95ce24](https://linux-hardware.org/?probe=021f95ce24) | May 15, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [9ce2f8b28b](https://linux-hardware.org/?probe=9ce2f8b28b) | May 15, 2022 |
| Gigabyte      | PH67A-D3-B3                 | [e819cbe6f7](https://linux-hardware.org/?probe=e819cbe6f7) | May 15, 2022 |
| ASRock        | 970M Pro3                   | [5f67a595f4](https://linux-hardware.org/?probe=5f67a595f4) | May 15, 2022 |
| ASUSTek       | Z170I PRO GAMING            | [a58685906f](https://linux-hardware.org/?probe=a58685906f) | May 15, 2022 |
| MSI           | PRO Z690-A DDR4             | [5ce4d54b58](https://linux-hardware.org/?probe=5ce4d54b58) | May 14, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [d7f98d5384](https://linux-hardware.org/?probe=d7f98d5384) | May 14, 2022 |
| Gigabyte      | X570S AORUS MASTER          | [b061586ff0](https://linux-hardware.org/?probe=b061586ff0) | May 14, 2022 |
| Gigabyte      | PH67A-D3-B3                 | [a292b16ff7](https://linux-hardware.org/?probe=a292b16ff7) | May 14, 2022 |
| ASUSTek       | Z97-P                       | [3fc95850aa](https://linux-hardware.org/?probe=3fc95850aa) | May 14, 2022 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [975e7a6b47](https://linux-hardware.org/?probe=975e7a6b47) | May 14, 2022 |
| Acer          | H57M01                      | [42100344af](https://linux-hardware.org/?probe=42100344af) | May 14, 2022 |
| Intel         | X99 V1.0                    | [554b088978](https://linux-hardware.org/?probe=554b088978) | May 14, 2022 |
| Acer          | Veriton M670G               | [a583d3a342](https://linux-hardware.org/?probe=a583d3a342) | May 13, 2022 |
| Gigabyte      | X58A-UD3R                   | [0e9a009c11](https://linux-hardware.org/?probe=0e9a009c11) | May 13, 2022 |
| MSI           | B550M PRO-VDH               | [fd15b34806](https://linux-hardware.org/?probe=fd15b34806) | May 13, 2022 |
| Shuttle       | DS10U                       | [2f2acb55e9](https://linux-hardware.org/?probe=2f2acb55e9) | May 13, 2022 |
| Intel         | DH67BL AAG10189-210         | [2340d530cd](https://linux-hardware.org/?probe=2340d530cd) | May 13, 2022 |
| Gigabyte      | X58A-UD3R                   | [ed659a9633](https://linux-hardware.org/?probe=ed659a9633) | May 13, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [3fe223176c](https://linux-hardware.org/?probe=3fe223176c) | May 13, 2022 |
| Acer          | Aspire X3400                | [9dd76b4599](https://linux-hardware.org/?probe=9dd76b4599) | May 13, 2022 |
| Acer          | Aspire X3400                | [b590b149fc](https://linux-hardware.org/?probe=b590b149fc) | May 13, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [a2e10758ca](https://linux-hardware.org/?probe=a2e10758ca) | May 13, 2022 |
| Dell          | 0773VG A02                  | [0743f4573d](https://linux-hardware.org/?probe=0743f4573d) | May 12, 2022 |
| Dell          | 0HY9JP A01                  | [0026740e3f](https://linux-hardware.org/?probe=0026740e3f) | May 12, 2022 |
| Shuttle       | FH87                        | [42cb5c0ef7](https://linux-hardware.org/?probe=42cb5c0ef7) | May 12, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [91404c39c7](https://linux-hardware.org/?probe=91404c39c7) | May 12, 2022 |
| ASUSTek       | P8H61                       | [d2b843c446](https://linux-hardware.org/?probe=d2b843c446) | May 12, 2022 |
| HP            | 0AECh D                     | [68adfe0740](https://linux-hardware.org/?probe=68adfe0740) | May 12, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | [578328d0b5](https://linux-hardware.org/?probe=578328d0b5) | May 12, 2022 |
| Unknown       | Unknown                     | [7931f8191f](https://linux-hardware.org/?probe=7931f8191f) | May 11, 2022 |
| Unknown       | Unknown                     | [271a8ba23e](https://linux-hardware.org/?probe=271a8ba23e) | May 11, 2022 |
| MSI           | Z97S SLI Krait Edition      | [861cbb7b6e](https://linux-hardware.org/?probe=861cbb7b6e) | May 11, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [14f5c24c81](https://linux-hardware.org/?probe=14f5c24c81) | May 11, 2022 |
| Dell          | 0WMJ54 A00                  | [393406b0e8](https://linux-hardware.org/?probe=393406b0e8) | May 11, 2022 |
| Gigabyte      | Z590 VISION G               | [0e12a4aa26](https://linux-hardware.org/?probe=0e12a4aa26) | May 11, 2022 |
| Intel         | B75                         | [d2a9132d48](https://linux-hardware.org/?probe=d2a9132d48) | May 11, 2022 |
| ASUSTek       | H61M-K                      | [64f2ed4df2](https://linux-hardware.org/?probe=64f2ed4df2) | May 11, 2022 |
| ASRock        | B550 Steel Legend           | [a940d31b37](https://linux-hardware.org/?probe=a940d31b37) | May 10, 2022 |
| ASUSTek       | PRIME Z690M-HZ              | [74862d462d](https://linux-hardware.org/?probe=74862d462d) | May 10, 2022 |
| Gigabyte      | H97N                        | [21f1bf0f0c](https://linux-hardware.org/?probe=21f1bf0f0c) | May 10, 2022 |
| ASRock        | J4105B-ITX                  | [6e507d9a68](https://linux-hardware.org/?probe=6e507d9a68) | May 09, 2022 |
| ECS           | A68M-C4DL                   | [b8c60cf7a0](https://linux-hardware.org/?probe=b8c60cf7a0) | May 09, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [05b7c2c72c](https://linux-hardware.org/?probe=05b7c2c72c) | May 09, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [a9e6ecf483](https://linux-hardware.org/?probe=a9e6ecf483) | May 09, 2022 |
| ASUSTek       | PRIME Z690M-HZ              | [7987b700d5](https://linux-hardware.org/?probe=7987b700d5) | May 09, 2022 |
| MSI           | B450M PRO-VDH PLUS          | [b57ce8e7e1](https://linux-hardware.org/?probe=b57ce8e7e1) | May 09, 2022 |
| MSI           | B450M PRO-VDH PLUS          | [b3cac7c464](https://linux-hardware.org/?probe=b3cac7c464) | May 09, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [38e20673c2](https://linux-hardware.org/?probe=38e20673c2) | May 09, 2022 |
| ASRock        | J4105B-ITX                  | [c4eea9f630](https://linux-hardware.org/?probe=c4eea9f630) | May 09, 2022 |
| Intel         | H61                         | [3f5d8ae941](https://linux-hardware.org/?probe=3f5d8ae941) | May 09, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | [89f0b017b1](https://linux-hardware.org/?probe=89f0b017b1) | May 09, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | [bd7335e1cd](https://linux-hardware.org/?probe=bd7335e1cd) | May 09, 2022 |
| ASUSTek       | Pro WS C621-64L SAGE-10G... | [4ebf4d9cc8](https://linux-hardware.org/?probe=4ebf4d9cc8) | May 09, 2022 |
| Gigabyte      | Z97X-Gaming 5               | [77145b587d](https://linux-hardware.org/?probe=77145b587d) | May 09, 2022 |
| Gigabyte      | Z97X-Gaming 5               | [e3f65dec10](https://linux-hardware.org/?probe=e3f65dec10) | May 09, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | [422c9f9cae](https://linux-hardware.org/?probe=422c9f9cae) | May 09, 2022 |
| ASUSTek       | P8H61-M LX2 R2.0            | [344bc071a2](https://linux-hardware.org/?probe=344bc071a2) | May 09, 2022 |
| HP            | 1998                        | [bb8d501109](https://linux-hardware.org/?probe=bb8d501109) | May 09, 2022 |
| ASUSTek       | P5Q SE/R                    | [c99b0a0683](https://linux-hardware.org/?probe=c99b0a0683) | May 08, 2022 |
| Acer          | Revo RL80                   | [c48857049a](https://linux-hardware.org/?probe=c48857049a) | May 08, 2022 |
| Pegatron      | Eureka3                     | [e383533179](https://linux-hardware.org/?probe=e383533179) | May 08, 2022 |
| Gigabyte      | Z170X-GamingG1              | [28fc5f92bc](https://linux-hardware.org/?probe=28fc5f92bc) | May 08, 2022 |
| HP            | 870C                        | [adb470192a](https://linux-hardware.org/?probe=adb470192a) | May 08, 2022 |
| ASUSTek       | Z170-A                      | [abccbed349](https://linux-hardware.org/?probe=abccbed349) | May 08, 2022 |
| ASUSTek       | P8H77-V LE                  | [acf562b58b](https://linux-hardware.org/?probe=acf562b58b) | May 08, 2022 |
| ASUSTek       | P8H77-V LE                  | [1a3e2da376](https://linux-hardware.org/?probe=1a3e2da376) | May 08, 2022 |
| ASUSTek       | Z170-A                      | [97e2613936](https://linux-hardware.org/?probe=97e2613936) | May 08, 2022 |
| ASUSTek       | PRIME B360M-A               | [c589ad9143](https://linux-hardware.org/?probe=c589ad9143) | May 07, 2022 |
| ASUSTek       | P8B75-M                     | [6371d77b5d](https://linux-hardware.org/?probe=6371d77b5d) | May 07, 2022 |
| Pegatron      | 2AC3                        | [d2932b8b78](https://linux-hardware.org/?probe=d2932b8b78) | May 07, 2022 |
| Dell          | 0WMJ54 A01                  | [58b3a1b83d](https://linux-hardware.org/?probe=58b3a1b83d) | May 07, 2022 |
| Dell          | 00V62H A00                  | [5c5f2f2b5c](https://linux-hardware.org/?probe=5c5f2f2b5c) | May 07, 2022 |
| Medion        | B460H6-EM                   | [e2abcd94ce](https://linux-hardware.org/?probe=e2abcd94ce) | May 06, 2022 |
| Lenovo        | 0B98401 WIN                 | [b080a2bae5](https://linux-hardware.org/?probe=b080a2bae5) | May 06, 2022 |
| HP            | 1495                        | [4b63b733be](https://linux-hardware.org/?probe=4b63b733be) | May 06, 2022 |
| Lenovo        | NO DPK                      | [24340ea9a8](https://linux-hardware.org/?probe=24340ea9a8) | May 06, 2022 |
| Google        | Panther                     | [4b7366ed94](https://linux-hardware.org/?probe=4b7366ed94) | May 06, 2022 |
| ASRock        | B85M DASH/OL R2.0           | [61c86467ba](https://linux-hardware.org/?probe=61c86467ba) | May 06, 2022 |
| MSI           | B550M PRO-VDH               | [40f4bf344a](https://linux-hardware.org/?probe=40f4bf344a) | May 05, 2022 |
| Supermicro    | X8ST3                       | [3cab505f0a](https://linux-hardware.org/?probe=3cab505f0a) | May 05, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | [7b488333bb](https://linux-hardware.org/?probe=7b488333bb) | May 05, 2022 |
| ASUSTek       | Z97-K                       | [f03b0f28ef](https://linux-hardware.org/?probe=f03b0f28ef) | May 05, 2022 |
| MSI           | 770-C45                     | [0e9179888b](https://linux-hardware.org/?probe=0e9179888b) | May 05, 2022 |
| Lenovo        | NO DPK                      | [dc8d8b070e](https://linux-hardware.org/?probe=dc8d8b070e) | May 05, 2022 |
| MSI           | Z390-A PRO                  | [145317db95](https://linux-hardware.org/?probe=145317db95) | May 05, 2022 |
| MSI           | H55M-E23                    | [d42084b294](https://linux-hardware.org/?probe=d42084b294) | May 04, 2022 |
| ASUSTek       | Maximus VI HERO             | [540a55671c](https://linux-hardware.org/?probe=540a55671c) | May 04, 2022 |
| Gigabyte      | X99-UD4-CF                  | [d5cd65ba5b](https://linux-hardware.org/?probe=d5cd65ba5b) | May 04, 2022 |
| Lenovo        | 0B98401 WIN                 | [180a5d086f](https://linux-hardware.org/?probe=180a5d086f) | May 04, 2022 |
| Lenovo        | 0B98401 WIN                 | [f47683cd76](https://linux-hardware.org/?probe=f47683cd76) | May 04, 2022 |
| ASUSTek       | PRIME B360-PLUS             | [4ce66ff579](https://linux-hardware.org/?probe=4ce66ff579) | May 04, 2022 |
| Gigabyte      | H110M-S2-CF                 | [156de9d4de](https://linux-hardware.org/?probe=156de9d4de) | May 04, 2022 |
| ASUSTek       | Z97M-PLUS                   | [c2ab1a3ec2](https://linux-hardware.org/?probe=c2ab1a3ec2) | May 04, 2022 |
| Gigabyte      | B75M-HD3                    | [7dc76bf420](https://linux-hardware.org/?probe=7dc76bf420) | May 04, 2022 |
| ASUSTek       | B150M PRO GAMING            | [a31ab08668](https://linux-hardware.org/?probe=a31ab08668) | May 04, 2022 |
| Dell          | 0Y56T3 A00                  | [3bdd958639](https://linux-hardware.org/?probe=3bdd958639) | May 04, 2022 |
| Dell          | 0P301D A02                  | [ab9edfbc39](https://linux-hardware.org/?probe=ab9edfbc39) | May 03, 2022 |
| Acer          | FX58M                       | [0a6673afb9](https://linux-hardware.org/?probe=0a6673afb9) | May 03, 2022 |
| Gigabyte      | H110-D3A-CF                 | [74e69f5610](https://linux-hardware.org/?probe=74e69f5610) | May 03, 2022 |
| Shuttle       | FG41 V20                    | [fd07bdf7b5](https://linux-hardware.org/?probe=fd07bdf7b5) | May 02, 2022 |
| Dell          | 0M017G A00                  | [93884340db](https://linux-hardware.org/?probe=93884340db) | May 02, 2022 |
| Alienware     | 07JNH0 A02                  | [d39a57aed6](https://linux-hardware.org/?probe=d39a57aed6) | May 02, 2022 |
| ASUSTek       | PRIME B450M-A               | [bbbfaa9157](https://linux-hardware.org/?probe=bbbfaa9157) | May 02, 2022 |
| Dell          | 09M8Y8 A01                  | [301694185a](https://linux-hardware.org/?probe=301694185a) | May 02, 2022 |
| Dell          | 0HHV7N A00                  | [7636489d8e](https://linux-hardware.org/?probe=7636489d8e) | May 01, 2022 |
| ASUSTek       | M5A97 LE R2.0               | [965ebad5cb](https://linux-hardware.org/?probe=965ebad5cb) | May 01, 2022 |
| MSI           | A320M-A PRO MAX             | [c396021a33](https://linux-hardware.org/?probe=c396021a33) | May 01, 2022 |
| Gigabyte      | B365M DS3H                  | [cc016ce0c5](https://linux-hardware.org/?probe=cc016ce0c5) | May 01, 2022 |
| ASUSTek       | H61M-K                      | [fbbae98a18](https://linux-hardware.org/?probe=fbbae98a18) | May 01, 2022 |
| Gigabyte      | Z77X-UD3H                   | [f30bbca593](https://linux-hardware.org/?probe=f30bbca593) | May 01, 2022 |
| ASUSTek       | P5B                         | [39c9900546](https://linux-hardware.org/?probe=39c9900546) | May 01, 2022 |
| Positivo      | POS-ECIG41BSA               | [b622f7f43f](https://linux-hardware.org/?probe=b622f7f43f) | Apr 30, 2022 |
| Medion        | MS-7616                     | [f3572ea9a5](https://linux-hardware.org/?probe=f3572ea9a5) | Apr 30, 2022 |
| Gigabyte      | H61M-DS2 x.x                | [463e99eb8c](https://linux-hardware.org/?probe=463e99eb8c) | Apr 30, 2022 |
| MSI           | X570-A PRO                  | [ff568c874c](https://linux-hardware.org/?probe=ff568c874c) | Apr 30, 2022 |
| Gigabyte      | B365M DS3H                  | [f140b54261](https://linux-hardware.org/?probe=f140b54261) | Apr 30, 2022 |
| Gigabyte      | B550M DS3H                  | [f62d8963d7](https://linux-hardware.org/?probe=f62d8963d7) | Apr 30, 2022 |
| ASRock        | B75M-ITX                    | [dbc851e0d3](https://linux-hardware.org/?probe=dbc851e0d3) | Apr 30, 2022 |
| HP            | 3396                        | [468c2975ee](https://linux-hardware.org/?probe=468c2975ee) | Apr 30, 2022 |
| Huanan        | X99-BD4 V/OPCZAO            | [2f215a330a](https://linux-hardware.org/?probe=2f215a330a) | Apr 30, 2022 |
| MSI           | B550-A PRO                  | [0b23621ed1](https://linux-hardware.org/?probe=0b23621ed1) | Apr 30, 2022 |
| MSI           | A88XM-E45 V2                | [a50ad068b1](https://linux-hardware.org/?probe=a50ad068b1) | Apr 30, 2022 |
| Gigabyte      | B550M DS3H                  | [7797c23169](https://linux-hardware.org/?probe=7797c23169) | Apr 30, 2022 |
| MSI           | A320M PRO-E                 | [655905bb3b](https://linux-hardware.org/?probe=655905bb3b) | Apr 29, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [fe522bdf2e](https://linux-hardware.org/?probe=fe522bdf2e) | Apr 29, 2022 |
| ASUSTek       | M5A97 LE R2.0               | [686f4acac4](https://linux-hardware.org/?probe=686f4acac4) | Apr 29, 2022 |
| ASUSTek       | Rampage IV EXTREME          | [111d072676](https://linux-hardware.org/?probe=111d072676) | Apr 29, 2022 |
| Dell          | 07WP95 A02                  | [8dd4d42608](https://linux-hardware.org/?probe=8dd4d42608) | Apr 29, 2022 |
| Huanan        | X99-BD4 V/OPCZAO            | [a5743a1922](https://linux-hardware.org/?probe=a5743a1922) | Apr 29, 2022 |
| Pepper Job... | GLK-UC2X                    | [28495f32bd](https://linux-hardware.org/?probe=28495f32bd) | Apr 29, 2022 |
| Alienware     | 07W25T A00                  | [b989838f70](https://linux-hardware.org/?probe=b989838f70) | Apr 29, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | [27df4d83ea](https://linux-hardware.org/?probe=27df4d83ea) | Apr 29, 2022 |
| ASUSTek       | PRIME B360M-A               | [519ed87066](https://linux-hardware.org/?probe=519ed87066) | Apr 29, 2022 |
| ASUSTek       | PRIME B360M-A               | [c46a1d595b](https://linux-hardware.org/?probe=c46a1d595b) | Apr 29, 2022 |
| MSI           | A78M-E35                    | [8f9bf75a08](https://linux-hardware.org/?probe=8f9bf75a08) | Apr 29, 2022 |
| ASUSTek       | Z87-WS                      | [1c67952875](https://linux-hardware.org/?probe=1c67952875) | Apr 29, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [d291472a69](https://linux-hardware.org/?probe=d291472a69) | Apr 28, 2022 |
| ASRock        | H61M-VG4                    | [92f92ef4ee](https://linux-hardware.org/?probe=92f92ef4ee) | Apr 28, 2022 |
| ASRock        | B450M Pro4                  | [773f69d63b](https://linux-hardware.org/?probe=773f69d63b) | Apr 28, 2022 |
| ASUSTek       | M5A78L LE                   | [96739891ab](https://linux-hardware.org/?probe=96739891ab) | Apr 28, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [919872f97b](https://linux-hardware.org/?probe=919872f97b) | Apr 28, 2022 |
| ASRock        | B450M Pro4                  | [2943b21899](https://linux-hardware.org/?probe=2943b21899) | Apr 28, 2022 |
| MSI           | B450M PRO-VDH PLUS          | [c4f91167bb](https://linux-hardware.org/?probe=c4f91167bb) | Apr 27, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [b923126955](https://linux-hardware.org/?probe=b923126955) | Apr 27, 2022 |
| ASUSTek       | H110M-A/M.2                 | [4c6852d631](https://linux-hardware.org/?probe=4c6852d631) | Apr 27, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [f06ce3d416](https://linux-hardware.org/?probe=f06ce3d416) | Apr 27, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [a3f49d1a04](https://linux-hardware.org/?probe=a3f49d1a04) | Apr 27, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [b47f678ce9](https://linux-hardware.org/?probe=b47f678ce9) | Apr 27, 2022 |
| ASRock        | H61M-VG4                    | [fff58f97e8](https://linux-hardware.org/?probe=fff58f97e8) | Apr 27, 2022 |
| Gigabyte      | GA-880GM-UD2H               | [3c53a0e59d](https://linux-hardware.org/?probe=3c53a0e59d) | Apr 27, 2022 |
| Gigabyte      | H61M-S2PV                   | [f09766a481](https://linux-hardware.org/?probe=f09766a481) | Apr 27, 2022 |
| HP            | 22F8                        | [eb4d49a17b](https://linux-hardware.org/?probe=eb4d49a17b) | Apr 27, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [56da721176](https://linux-hardware.org/?probe=56da721176) | Apr 27, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [1619af58d4](https://linux-hardware.org/?probe=1619af58d4) | Apr 27, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [3c6aace75c](https://linux-hardware.org/?probe=3c6aace75c) | Apr 27, 2022 |
| MSI           | 880GMA-E35                  | [6ff68166f7](https://linux-hardware.org/?probe=6ff68166f7) | Apr 26, 2022 |
| Dell          | 0WR7PY A03                  | [4ac0a4dff1](https://linux-hardware.org/?probe=4ac0a4dff1) | Apr 26, 2022 |
| Dell          | 0VNM11 A00                  | [6aae7c23ad](https://linux-hardware.org/?probe=6aae7c23ad) | Apr 26, 2022 |
| MSI           | A320M-A PRO MAX             | [e06fd46729](https://linux-hardware.org/?probe=e06fd46729) | Apr 26, 2022 |
| Biostar       | J3160NH                     | [8ffd3a1aa4](https://linux-hardware.org/?probe=8ffd3a1aa4) | Apr 26, 2022 |
| MSI           | Z68A-GD80                   | [fedca9082a](https://linux-hardware.org/?probe=fedca9082a) | Apr 25, 2022 |
| ASUSTek       | H81M-V3                     | [4d87f6f113](https://linux-hardware.org/?probe=4d87f6f113) | Apr 25, 2022 |
| Gigabyte      | P55M-UD2                    | [5f9ffc8d46](https://linux-hardware.org/?probe=5f9ffc8d46) | Apr 24, 2022 |
| Dell          | 0GXM1W A02                  | [6564561a75](https://linux-hardware.org/?probe=6564561a75) | Apr 24, 2022 |
| ASRock        | Z170 Gaming K4              | [96b772b4e6](https://linux-hardware.org/?probe=96b772b4e6) | Apr 24, 2022 |
| Acer          | FX58M                       | [3074ddb372](https://linux-hardware.org/?probe=3074ddb372) | Apr 24, 2022 |
| Dell          | 0GXM1W A02                  | [af6b49b2a5](https://linux-hardware.org/?probe=af6b49b2a5) | Apr 24, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | [e0e448efcb](https://linux-hardware.org/?probe=e0e448efcb) | Apr 24, 2022 |
| ASUSTek       | F2A85-M PRO                 | [e0298dd8f0](https://linux-hardware.org/?probe=e0298dd8f0) | Apr 24, 2022 |
| HP            | 21EF                        | [9e37979ea3](https://linux-hardware.org/?probe=9e37979ea3) | Apr 23, 2022 |
| Gigabyte      | Z390 M GAMING-CF            | [929f99800a](https://linux-hardware.org/?probe=929f99800a) | Apr 23, 2022 |
| Dell          | 00V62H A00                  | [2da43c32a4](https://linux-hardware.org/?probe=2da43c32a4) | Apr 23, 2022 |
| Dell          | 0HD5W2 A00                  | [3b01c4a4a5](https://linux-hardware.org/?probe=3b01c4a4a5) | Apr 23, 2022 |
| MSI           | MS-1T11                     | [9c16a631ef](https://linux-hardware.org/?probe=9c16a631ef) | Apr 23, 2022 |
| MSI           | MS-1T11                     | [e263cd80f5](https://linux-hardware.org/?probe=e263cd80f5) | Apr 23, 2022 |
| HP            | 22F8                        | [67dc13d1ad](https://linux-hardware.org/?probe=67dc13d1ad) | Apr 23, 2022 |
| ASUSTek       | PRIME B560-PLUS             | [8e31efa5fa](https://linux-hardware.org/?probe=8e31efa5fa) | Apr 23, 2022 |
| Dell          | 088DT1 A01                  | [9e72ff0940](https://linux-hardware.org/?probe=9e72ff0940) | Apr 22, 2022 |
| ASUSTek       | CROSSHAIR II FORMULA        | [d35c4838f2](https://linux-hardware.org/?probe=d35c4838f2) | Apr 22, 2022 |
| ASUSTek       | CROSSHAIR II FORMULA        | [61e0546ed7](https://linux-hardware.org/?probe=61e0546ed7) | Apr 22, 2022 |
| ASRock        | Z370 Pro4-IB                | [c0c51e4d53](https://linux-hardware.org/?probe=c0c51e4d53) | Apr 22, 2022 |
| Dell          | 0HD5W2 A00                  | [ddfd89e9dc](https://linux-hardware.org/?probe=ddfd89e9dc) | Apr 22, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [a76e953825](https://linux-hardware.org/?probe=a76e953825) | Apr 22, 2022 |
| MSI           | MAG B460 TOMAHAWK           | [8ef18c7ea4](https://linux-hardware.org/?probe=8ef18c7ea4) | Apr 21, 2022 |
| HP            | 8054                        | [f9ec7b0896](https://linux-hardware.org/?probe=f9ec7b0896) | Apr 21, 2022 |
| Lenovo        | ThinkCentre M58 6258D3G     | [b84eab559e](https://linux-hardware.org/?probe=b84eab559e) | Apr 21, 2022 |
| Gigabyte      | B450M GAMING                | [bf31ebdabe](https://linux-hardware.org/?probe=bf31ebdabe) | Apr 21, 2022 |
| MSI           | Z97 GAMING 5                | [a6bd59cad3](https://linux-hardware.org/?probe=a6bd59cad3) | Apr 20, 2022 |
| ASRock        | X470 Taichi Ultimate        | [d10be6941f](https://linux-hardware.org/?probe=d10be6941f) | Apr 20, 2022 |
| ASRock        | X470 Taichi Ultimate        | [a92dda8ded](https://linux-hardware.org/?probe=a92dda8ded) | Apr 20, 2022 |
| MSI           | Z97 GAMING 5                | [350979cb0a](https://linux-hardware.org/?probe=350979cb0a) | Apr 19, 2022 |
| Gigabyte      | H310M S2H x.x               | [a0325fabb2](https://linux-hardware.org/?probe=a0325fabb2) | Apr 17, 2022 |
| Gigabyte      | H310M S2H x.x               | [d775ab24fe](https://linux-hardware.org/?probe=d775ab24fe) | Apr 17, 2022 |
| MSI           | 970 GAMING                  | [1ed579d3d1](https://linux-hardware.org/?probe=1ed579d3d1) | Apr 16, 2022 |
| MSI           | 970 GAMING                  | [dae8a4db62](https://linux-hardware.org/?probe=dae8a4db62) | Apr 16, 2022 |
| Unknown       | Unknown                     | [3e2989ae49](https://linux-hardware.org/?probe=3e2989ae49) | Apr 15, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [cf9feaf8ec](https://linux-hardware.org/?probe=cf9feaf8ec) | Apr 15, 2022 |
| Gigabyte      | B75M-D3P                    | [cfb6502298](https://linux-hardware.org/?probe=cfb6502298) | Apr 14, 2022 |
| MSI           | MEG X570 UNIFY              | [bacc580e7a](https://linux-hardware.org/?probe=bacc580e7a) | Apr 13, 2022 |
| MSI           | X370 GAMING PRO CARBON A... | [e4ea2782f9](https://linux-hardware.org/?probe=e4ea2782f9) | Apr 10, 2022 |
| Gigabyte      | H55M-S2HP                   | [f394924315](https://linux-hardware.org/?probe=f394924315) | Apr 10, 2022 |
| Gigabyte      | H55M-S2HP                   | [9edb3bbc43](https://linux-hardware.org/?probe=9edb3bbc43) | Apr 10, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [1009093226](https://linux-hardware.org/?probe=1009093226) | Apr 10, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN 2625... | [62c84ef4b4](https://linux-hardware.org/?probe=62c84ef4b4) | Apr 09, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN 2625... | [07bde861ad](https://linux-hardware.org/?probe=07bde861ad) | Apr 09, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [8a07adc0f8](https://linux-hardware.org/?probe=8a07adc0f8) | Apr 09, 2022 |
| Unknown       | HX90                        | [913b92a244](https://linux-hardware.org/?probe=913b92a244) | Apr 08, 2022 |
| HP            | 1495                        | [36ea4763de](https://linux-hardware.org/?probe=36ea4763de) | Apr 08, 2022 |
| Maxtang       | FP30 V1.0                   | [2062d8578e](https://linux-hardware.org/?probe=2062d8578e) | Apr 08, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [fa9314716d](https://linux-hardware.org/?probe=fa9314716d) | Apr 07, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [d2f9498bd2](https://linux-hardware.org/?probe=d2f9498bd2) | Apr 05, 2022 |
| Acer          | Aspire XC-603               | [ef344607ad](https://linux-hardware.org/?probe=ef344607ad) | Apr 04, 2022 |
| Packard Be... | IMEDIA S2110A               | [b8bf871708](https://linux-hardware.org/?probe=b8bf871708) | Apr 04, 2022 |
| Gigabyte      | B365 M AORUS ELITE-CF       | [7da8a936ea](https://linux-hardware.org/?probe=7da8a936ea) | Apr 04, 2022 |
| Gigabyte      | Z690 UD AX                  | [a052a5e936](https://linux-hardware.org/?probe=a052a5e936) | Apr 03, 2022 |
| Unknown       | Unknown                     | [ec51dcaf0a](https://linux-hardware.org/?probe=ec51dcaf0a) | Apr 03, 2022 |
| MSI           | MAG B660M MORTAR DDR4       | [a9f2820894](https://linux-hardware.org/?probe=a9f2820894) | Apr 02, 2022 |
| Dell          | 07PR60 A00                  | [40f34fbc8f](https://linux-hardware.org/?probe=40f34fbc8f) | Apr 01, 2022 |
| Fujitsu       | D3223-C1 S26361-D3223-C1    | [f0fdc95810](https://linux-hardware.org/?probe=f0fdc95810) | Apr 01, 2022 |
| HP            | ProLiant ML110 G7           | [9e1e2b2ae7](https://linux-hardware.org/?probe=9e1e2b2ae7) | Apr 01, 2022 |
| MSI           | X370 GAMING PRO CARBON A... | [ce2e9f743d](https://linux-hardware.org/?probe=ce2e9f743d) | Mar 31, 2022 |
| Dell          | 0YNVJG A01                  | [4ccce61117](https://linux-hardware.org/?probe=4ccce61117) | Mar 30, 2022 |
| MSI           | B450M PRO-M2 MAX            | [f21ef43d0f](https://linux-hardware.org/?probe=f21ef43d0f) | Mar 30, 2022 |
| Le Cube 1     | Unknown                     | [a881cc0397](https://linux-hardware.org/?probe=a881cc0397) | Mar 26, 2022 |
| HP            | 1589                        | [8c1f30bb6f](https://linux-hardware.org/?probe=8c1f30bb6f) | Mar 23, 2022 |
| ASRock        | 970 Extreme3 R2.0           | [f417e6a6ef](https://linux-hardware.org/?probe=f417e6a6ef) | Mar 11, 2022 |
| Unknown       | T3 MRD                      | [256dc440ec](https://linux-hardware.org/?probe=256dc440ec) | Mar 09, 2022 |
| MSI           | X370 GAMING PRO CARBON A... | [1fb25ad2c3](https://linux-hardware.org/?probe=1fb25ad2c3) | Mar 05, 2022 |
| ASUSTek       | M4A87TD/USB3                | [aa80ded615](https://linux-hardware.org/?probe=aa80ded615) | Mar 04, 2022 |
| ASUSTek       | M4A87TD/USB3                | [3e997c5618](https://linux-hardware.org/?probe=3e997c5618) | Mar 03, 2022 |
| Unknown       | T3 MRD                      | [35ab38818d](https://linux-hardware.org/?probe=35ab38818d) | Feb 28, 2022 |
| Unknown       | T3 MRD                      | [01dd9cefa7](https://linux-hardware.org/?probe=01dd9cefa7) | Feb 28, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [18d37562a8](https://linux-hardware.org/?probe=18d37562a8) | Feb 26, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [d8af57f59a](https://linux-hardware.org/?probe=d8af57f59a) | Feb 26, 2022 |
| Gigabyte      | H61M-DS2 DVI                | [90c43679f7](https://linux-hardware.org/?probe=90c43679f7) | Feb 23, 2022 |
| MSI           | X370 GAMING PRO CARBON A... | [fa5ed1f68b](https://linux-hardware.org/?probe=fa5ed1f68b) | Feb 13, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | [e329340668](https://linux-hardware.org/?probe=e329340668) | Feb 11, 2022 |
| Dell          | 0YXT71 A03                  | [19227aa57d](https://linux-hardware.org/?probe=19227aa57d) | Feb 11, 2022 |
| HP            | 212B                        | [fab24340a5](https://linux-hardware.org/?probe=fab24340a5) | Feb 10, 2022 |
| ASRockRack    | X470D4U2/1N1                | [735bc0f806](https://linux-hardware.org/?probe=735bc0f806) | Feb 04, 2022 |
| ASUSTek       | P5P41T/USB3                 | [f45dc3454a](https://linux-hardware.org/?probe=f45dc3454a) | Jan 25, 2022 |
| ASUSTek       | P5P41T/USB3                 | [105593cece](https://linux-hardware.org/?probe=105593cece) | Jan 23, 2022 |
| Gigabyte      | GB-BSi7-1165G7              | [ab94ff1199](https://linux-hardware.org/?probe=ab94ff1199) | Jan 20, 2022 |
| MSI           | Z490-A PRO                  | [b2655bbd43](https://linux-hardware.org/?probe=b2655bbd43) | Jan 15, 2022 |
| MSI           | C236A WORKSTATION           | [97795d3ebc](https://linux-hardware.org/?probe=97795d3ebc) | Jan 07, 2022 |
| Intel         | H61                         | [e2b49aa759](https://linux-hardware.org/?probe=e2b49aa759) | Dec 30, 2021 |
| Lenovo        | 3141 NOK                    | [cc90d7c889](https://linux-hardware.org/?probe=cc90d7c889) | Dec 13, 2021 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [0db33a5b23](https://linux-hardware.org/?probe=0db33a5b23) | Dec 10, 2021 |
| Huanan        | X99 F8D V2.2                | [dcd5217827](https://linux-hardware.org/?probe=dcd5217827) | Nov 29, 2021 |
| Gigabyte      | M52L-S3                     | [16854f2502](https://linux-hardware.org/?probe=16854f2502) | Nov 29, 2021 |
| Gigabyte      | M52L-S3                     | [e6f3417028](https://linux-hardware.org/?probe=e6f3417028) | Nov 27, 2021 |
| Gigabyte      | EP31-DS3L                   | [c0134f6231](https://linux-hardware.org/?probe=c0134f6231) | Nov 11, 2021 |
| Gigabyte      | EP31-DS3L                   | [4d659bf7e4](https://linux-hardware.org/?probe=4d659bf7e4) | Nov 11, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [36e64b8256](https://linux-hardware.org/?probe=36e64b8256) | Nov 10, 2021 |
| MSI           | MS-7235                     | [bbfa7fb897](https://linux-hardware.org/?probe=bbfa7fb897) | Oct 24, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Desktops | Percent |
|----------------------------|----------|---------|
| 5.15.0-27-generic          | 99       | 32.04%  |
| 5.15.0-25-generic          | 52       | 16.83%  |
| 5.15.0-30-generic          | 49       | 15.86%  |
| 5.15.0-33-generic          | 45       | 14.56%  |
| 5.15.0-23-generic          | 11       | 3.56%   |
| 5.15.0-18-generic          | 9        | 2.91%   |
| 5.13.0-19-generic          | 7        | 2.27%   |
| 5.15.0-32-generic          | 5        | 1.62%   |
| 5.15.0-28-generic          | 4        | 1.29%   |
| 5.15.0-22-generic          | 3        | 0.97%   |
| 5.18.0-051800-generic      | 2        | 0.65%   |
| 5.17.0-051700-generic      | 2        | 0.65%   |
| 5.17.9-xanmod1-x64v2       | 1        | 0.32%   |
| 5.17.7-051707-generic      | 1        | 0.32%   |
| 5.17.6-051706-generic      | 1        | 0.32%   |
| 5.17.5-051705-generic      | 1        | 0.32%   |
| 5.17.4-051704-generic      | 1        | 0.32%   |
| 5.17.2-051702-generic      | 1        | 0.32%   |
| 5.17.1-051701-generic      | 1        | 0.32%   |
| 5.17.0-void25-nomac-znver3 | 1        | 0.32%   |
| 5.17.0-tkg-cacule          | 1        | 0.32%   |
| 5.17.0-4.1-liquorix-amd64  | 1        | 0.32%   |
| 5.17.0-1003-oem            | 1        | 0.32%   |
| 5.16.0-051600-generic      | 1        | 0.32%   |
| 5.15.13-051513-generic     | 1        | 0.32%   |
| 5.15.0-35-generic          | 1        | 0.32%   |
| 5.15.0-30-lowlatency       | 1        | 0.32%   |
| 5.15.0-27-lowlatency       | 1        | 0.32%   |
| 5.15.0-17-generic          | 1        | 0.32%   |
| 5.15.0-051500rc7-generic   | 1        | 0.32%   |
| 5.13.0-40-generic          | 1        | 0.32%   |
| 5.13.0-28-generic          | 1        | 0.32%   |
| 5.13.0-20-generic          | 1        | 0.32%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 275      | 91.06%  |
| 5.13.0  | 10       | 3.31%   |
| 5.17.0  | 6        | 1.99%   |
| 5.18.0  | 2        | 0.66%   |
| 5.17.9  | 1        | 0.33%   |
| 5.17.7  | 1        | 0.33%   |
| 5.17.6  | 1        | 0.33%   |
| 5.17.5  | 1        | 0.33%   |
| 5.17.4  | 1        | 0.33%   |
| 5.17.2  | 1        | 0.33%   |
| 5.17.1  | 1        | 0.33%   |
| 5.16.0  | 1        | 0.33%   |
| 5.15.13 | 1        | 0.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 276      | 91.39%  |
| 5.17    | 13       | 4.3%    |
| 5.13    | 10       | 3.31%   |
| 5.18    | 2        | 0.66%   |
| 5.16    | 1        | 0.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 301      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 280      | 93.02%  |
| Unknown         | 11       | 3.65%   |
| X-Cinnamon      | 6        | 1.99%   |
| Unity           | 3        | 1%      |
| GNOME Flashback | 1        | 0.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 155      | 50.99%  |
| X11     | 139      | 45.72%  |
| Unknown | 6        | 1.97%   |
| Tty     | 4        | 1.32%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| GDM3    | 264      | 87.13%  |
| Unknown | 29       | 9.57%   |
| LightDM | 5        | 1.65%   |
| GDM     | 3        | 0.99%   |
| SDDM    | 2        | 0.66%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 115      | 38.21%  |
| de_DE | 32       | 10.63%  |
| en_GB | 23       | 7.64%   |
| fr_FR | 21       | 6.98%   |
| pt_BR | 16       | 5.32%   |
| es_ES | 9        | 2.99%   |
| en_CA | 9        | 2.99%   |
| ru_RU | 8        | 2.66%   |
| en_AU | 8        | 2.66%   |
| cs_CZ | 8        | 2.66%   |
| pl_PL | 6        | 1.99%   |
| it_IT | 5        | 1.66%   |
| en_IN | 4        | 1.33%   |
| zh_CN | 3        | 1%      |
| ja_JP | 3        | 1%      |
| zh_TW | 2        | 0.66%   |
| tr_TR | 2        | 0.66%   |
| sk_SK | 2        | 0.66%   |
| pt_PT | 2        | 0.66%   |
| nl_BE | 2        | 0.66%   |
| fi_FI | 2        | 0.66%   |
| el_GR | 2        | 0.66%   |
| C     | 2        | 0.66%   |
| th_TH | 1        | 0.33%   |
| ro_RO | 1        | 0.33%   |
| hu_HU | 1        | 0.33%   |
| es_PE | 1        | 0.33%   |
| es_EC | 1        | 0.33%   |
| es_CR | 1        | 0.33%   |
| es_CL | 1        | 0.33%   |
| es_AR | 1        | 0.33%   |
| en_ZW | 1        | 0.33%   |
| en_ZA | 1        | 0.33%   |
| en_PH | 1        | 0.33%   |
| en_NZ | 1        | 0.33%   |
| de_CH | 1        | 0.33%   |
| de_BE | 1        | 0.33%   |
| de_AT | 1        | 0.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 223      | 73.11%  |
| EFI  | 82       | 26.89%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 264      | 87.42%  |
| Zfs     | 13       | 4.3%    |
| Overlay | 13       | 4.3%    |
| Btrfs   | 6        | 1.99%   |
| Xfs     | 5        | 1.66%   |
| Ext2    | 1        | 0.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 224      | 74.17%  |
| GPT     | 73       | 24.17%  |
| MBR     | 5        | 1.66%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 247      | 81.79%  |
| Yes       | 55       | 18.21%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 160      | 52.98%  |
| Yes       | 142      | 47.02%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 73       | 24.25%  |
| Gigabyte Technology | 53       | 17.61%  |
| MSI                 | 47       | 15.61%  |
| Dell                | 30       | 9.97%   |
| ASRock              | 19       | 6.31%   |
| Hewlett-Packard     | 14       | 4.65%   |
| Intel               | 9        | 2.99%   |
| Lenovo              | 7        | 2.33%   |
| Acer                | 7        | 2.33%   |
| Unknown             | 6        | 1.99%   |
| Shuttle             | 5        | 1.66%   |
| Pegatron            | 4        | 1.33%   |
| Fujitsu             | 4        | 1.33%   |
| Medion              | 3        | 1%      |
| ECS                 | 3        | 1%      |
| Alienware           | 3        | 1%      |
| Huanan              | 2        | 0.66%   |
| Biostar             | 2        | 0.66%   |
| Supermicro          | 1        | 0.33%   |
| Positivo            | 1        | 0.33%   |
| Pepper Jobs         | 1        | 0.33%   |
| Packard Bell        | 1        | 0.33%   |
| Maxtang             | 1        | 0.33%   |
| Le Cube 1           | 1        | 0.33%   |
| Google              | 1        | 0.33%   |
| Foxconn             | 1        | 0.33%   |
| ASRockRack          | 1        | 0.33%   |
| Apple               | 1        | 0.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| ASUS All Series                | 9        | 2.99%   |
| Unknown                        | 7        | 2.33%   |
| Dell OptiPlex 7010             | 4        | 1.33%   |
| MSI MS-7C52                    | 3        | 1%      |
| MSI MS-7C37                    | 3        | 1%      |
| MSI MS-7D54                    | 2        | 0.66%   |
| MSI MS-7C95                    | 2        | 0.66%   |
| MSI MS-7C92                    | 2        | 0.66%   |
| MSI MS-7C91                    | 2        | 0.66%   |
| MSI MS-7C02                    | 2        | 0.66%   |
| MSI MS-7A38                    | 2        | 0.66%   |
| MSI MS-7721                    | 2        | 0.66%   |
| Intel H61                      | 2        | 0.66%   |
| HP Compaq 8200 Elite SFF PC    | 2        | 0.66%   |
| Gigabyte Z77X-UD3H             | 2        | 0.66%   |
| Gigabyte X99-UD4-CF            | 2        | 0.66%   |
| Gigabyte X570 AORUS MASTER     | 2        | 0.66%   |
| Fujitsu CELSIUS R570-2         | 2        | 0.66%   |
| Dell Precision WorkStation 690 | 2        | 0.66%   |
| Dell OptiPlex 790              | 2        | 0.66%   |
| Dell OptiPlex 7040             | 2        | 0.66%   |
| Dell OptiPlex 3020             | 2        | 0.66%   |
| ASUS Z170-A                    | 2        | 0.66%   |
| ASUS TUF Gaming X570-PLUS      | 2        | 0.66%   |
| ASUS ROG STRIX B350-F GAMING   | 2        | 0.66%   |
| ASUS PRIME A320M-K             | 2        | 0.66%   |
| ASUS M5A97 LE R2.0             | 2        | 0.66%   |
| ASRock X470 Taichi Ultimate    | 2        | 0.66%   |
| Supermicro X8ST3               | 1        | 0.33%   |
| Shuttle SH87R                  | 1        | 0.33%   |
| Shuttle SG41                   | 1        | 0.33%   |
| Shuttle DS81D                  | 1        | 0.33%   |
| Shuttle DS10U                  | 1        | 0.33%   |
| Shuttle DH110                  | 1        | 0.33%   |
| Positivo POS-ECIG41BS          | 1        | 0.33%   |
| Pepper Jobs GLK-UC2X           | 1        | 0.33%   |
| Pegatron VN433AA-ABF p6235fr   | 1        | 0.33%   |
| Pegatron p6-2109eo             | 1        | 0.33%   |
| Pegatron 520-1030uk            | 1        | 0.33%   |
| Pegatron 23-1015               | 1        | 0.33%   |
| Packard Bell IMEDIA S2110      | 1        | 0.33%   |
| MSI Vortex G65VR 6RE SLI       | 1        | 0.33%   |
| MSI p7-1240                    | 1        | 0.33%   |
| MSI MS-7D42                    | 1        | 0.33%   |
| MSI MS-7D25                    | 1        | 0.33%   |
| MSI MS-7D16                    | 1        | 0.33%   |
| MSI MS-7C81                    | 1        | 0.33%   |
| MSI MS-7C80                    | 1        | 0.33%   |
| MSI MS-7C75                    | 1        | 0.33%   |
| MSI MS-7C56                    | 1        | 0.33%   |
| MSI MS-7C35                    | 1        | 0.33%   |
| MSI MS-7B86                    | 1        | 0.33%   |
| MSI MS-7B84                    | 1        | 0.33%   |
| MSI MS-7B79                    | 1        | 0.33%   |
| MSI MS-7A70                    | 1        | 0.33%   |
| MSI MS-7A32                    | 1        | 0.33%   |
| MSI MS-7998                    | 1        | 0.33%   |
| MSI MS-7924                    | 1        | 0.33%   |
| MSI MS-7922                    | 1        | 0.33%   |
| MSI MS-7918                    | 1        | 0.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| Dell OptiPlex         | 16       | 5.32%   |
| ASUS PRIME            | 11       | 3.65%   |
| ASUS ROG              | 9        | 2.99%   |
| ASUS All              | 9        | 2.99%   |
| Dell Precision        | 7        | 2.33%   |
| Unknown               | 7        | 2.33%   |
| Lenovo ThinkCentre    | 4        | 1.33%   |
| HP EliteDesk          | 4        | 1.33%   |
| Gigabyte X570         | 4        | 1.33%   |
| ASUS TUF              | 4        | 1.33%   |
| Acer Aspire           | 4        | 1.33%   |
| MSI MS-7C52           | 3        | 1%      |
| MSI MS-7C37           | 3        | 1%      |
| HP Compaq             | 3        | 1%      |
| Dell Inspiron         | 3        | 1%      |
| ASUS PRO              | 3        | 1%      |
| ASUS CROSSHAIR        | 3        | 1%      |
| MSI MS-7D54           | 2        | 0.66%   |
| MSI MS-7C95           | 2        | 0.66%   |
| MSI MS-7C92           | 2        | 0.66%   |
| MSI MS-7C91           | 2        | 0.66%   |
| MSI MS-7C02           | 2        | 0.66%   |
| MSI MS-7A38           | 2        | 0.66%   |
| MSI MS-7721           | 2        | 0.66%   |
| Intel H61             | 2        | 0.66%   |
| Gigabyte Z77X-UD3H    | 2        | 0.66%   |
| Gigabyte Z690         | 2        | 0.66%   |
| Gigabyte Z390         | 2        | 0.66%   |
| Gigabyte X99-UD4-CF   | 2        | 0.66%   |
| Gigabyte X570S        | 2        | 0.66%   |
| Gigabyte H61M-DS2     | 2        | 0.66%   |
| Fujitsu CELSIUS       | 2        | 0.66%   |
| ASUS Z170-A           | 2        | 0.66%   |
| ASUS P8H61-M          | 2        | 0.66%   |
| ASUS P8H61            | 2        | 0.66%   |
| ASUS M5A97            | 2        | 0.66%   |
| ASRock X470           | 2        | 0.66%   |
| ASRock 970            | 2        | 0.66%   |
| Acer Veriton          | 2        | 0.66%   |
| Supermicro X8ST3      | 1        | 0.33%   |
| Shuttle SH87R         | 1        | 0.33%   |
| Shuttle SG41          | 1        | 0.33%   |
| Shuttle DS81D         | 1        | 0.33%   |
| Shuttle DS10U         | 1        | 0.33%   |
| Shuttle DH110         | 1        | 0.33%   |
| Positivo POS-ECIG41BS | 1        | 0.33%   |
| Pepper Jobs GLK-UC2X  | 1        | 0.33%   |
| Pegatron VN433AA-ABF  | 1        | 0.33%   |
| Pegatron p6-2109eo    | 1        | 0.33%   |
| Pegatron 520-1030uk   | 1        | 0.33%   |
| Pegatron 23-1015      | 1        | 0.33%   |
| Packard Bell IMEDIA   | 1        | 0.33%   |
| MSI Vortex            | 1        | 0.33%   |
| MSI p7-1240           | 1        | 0.33%   |
| MSI MS-7D42           | 1        | 0.33%   |
| MSI MS-7D25           | 1        | 0.33%   |
| MSI MS-7D16           | 1        | 0.33%   |
| MSI MS-7C81           | 1        | 0.33%   |
| MSI MS-7C80           | 1        | 0.33%   |
| MSI MS-7C75           | 1        | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 30       | 9.97%   |
| 2018 | 29       | 9.63%   |
| 2021 | 28       | 9.3%    |
| 2019 | 28       | 9.3%    |
| 2014 | 27       | 8.97%   |
| 2020 | 25       | 8.31%   |
| 2010 | 21       | 6.98%   |
| 2016 | 18       | 5.98%   |
| 2013 | 16       | 5.32%   |
| 2011 | 15       | 4.98%   |
| 2017 | 14       | 4.65%   |
| 2015 | 14       | 4.65%   |
| 2009 | 12       | 3.99%   |
| 2008 | 10       | 3.32%   |
| 2022 | 6        | 1.99%   |
| 2007 | 4        | 1.33%   |
| 2006 | 3        | 1%      |
| 2005 | 1        | 0.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 301      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 297      | 98.34%  |
| Enabled  | 5        | 1.66%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 300      | 99.67%  |
| Yes  | 1        | 0.33%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 72       | 23.92%  |
| 32.01-64.0      | 63       | 20.93%  |
| 8.01-16.0       | 53       | 17.61%  |
| 4.01-8.0        | 48       | 15.95%  |
| 3.01-4.0        | 30       | 9.97%   |
| 64.01-256.0     | 22       | 7.31%   |
| 24.01-32.0      | 7        | 2.33%   |
| 1.01-2.0        | 3        | 1%      |
| More than 256.0 | 2        | 0.66%   |
| 2.01-3.0        | 1        | 0.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 101      | 33.01%  |
| 2.01-3.0   | 80       | 26.14%  |
| 4.01-8.0   | 53       | 17.32%  |
| 3.01-4.0   | 45       | 14.71%  |
| 8.01-16.0  | 17       | 5.56%   |
| 16.01-24.0 | 3        | 0.98%   |
| 0.51-1.0   | 3        | 0.98%   |
| 32.01-64.0 | 2        | 0.65%   |
| 24.01-32.0 | 2        | 0.65%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 98       | 32.13%  |
| 2      | 83       | 27.21%  |
| 3      | 50       | 16.39%  |
| 4      | 33       | 10.82%  |
| 5      | 18       | 5.9%    |
| 6      | 7        | 2.3%    |
| 0      | 5        | 1.64%   |
| 8      | 4        | 1.31%   |
| 7      | 3        | 0.98%   |
| 20     | 1        | 0.33%   |
| 13     | 1        | 0.33%   |
| 10     | 1        | 0.33%   |
| 9      | 1        | 0.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 173      | 57.48%  |
| Yes       | 128      | 42.52%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 300      | 99.34%  |
| No        | 2        | 0.66%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 169      | 55.96%  |
| Yes       | 133      | 44.04%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 195      | 64.57%  |
| Yes       | 107      | 35.43%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 50       | 16.61%  |
| Germany      | 35       | 11.63%  |
| UK           | 22       | 7.31%   |
| France       | 22       | 7.31%   |
| Brazil       | 17       | 5.65%   |
| Canada       | 11       | 3.65%   |
| Spain        | 10       | 3.32%   |
| Poland       | 10       | 3.32%   |
| Czechia      | 9        | 2.99%   |
| Australia    | 8        | 2.66%   |
| Russia       | 7        | 2.33%   |
| Finland      | 7        | 2.33%   |
| Argentina    | 7        | 2.33%   |
| Italy        | 6        | 1.99%   |
| Turkey       | 5        | 1.66%   |
| Switzerland  | 5        | 1.66%   |
| Netherlands  | 5        | 1.66%   |
| Japan        | 5        | 1.66%   |
| Romania      | 4        | 1.33%   |
| India        | 4        | 1.33%   |
| Belgium      | 4        | 1.33%   |
| Peru         | 3        | 1%      |
| Norway       | 3        | 1%      |
| China        | 3        | 1%      |
| Austria      | 3        | 1%      |
| Taiwan       | 2        | 0.66%   |
| Sweden       | 2        | 0.66%   |
| South Africa | 2        | 0.66%   |
| Slovakia     | 2        | 0.66%   |
| Serbia       | 2        | 0.66%   |
| Saudi Arabia | 2        | 0.66%   |
| Portugal     | 2        | 0.66%   |
| New Zealand  | 2        | 0.66%   |
| Greece       | 2        | 0.66%   |
| Bulgaria     | 2        | 0.66%   |
| Ukraine      | 1        | 0.33%   |
| Thailand     | 1        | 0.33%   |
| South Korea  | 1        | 0.33%   |
| Réunion     | 1        | 0.33%   |
| Philippines  | 1        | 0.33%   |
| Lithuania    | 1        | 0.33%   |
| Iran         | 1        | 0.33%   |
| Indonesia    | 1        | 0.33%   |
| Hungary      | 1        | 0.33%   |
| Estonia      | 1        | 0.33%   |
| Egypt        | 1        | 0.33%   |
| Ecuador      | 1        | 0.33%   |
| Denmark      | 1        | 0.33%   |
| Costa Rica   | 1        | 0.33%   |
| Chile        | 1        | 0.33%   |
| Algeria      | 1        | 0.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Istanbul             | 4        | 1.32%   |
| Debica               | 4        | 1.32%   |
| Sao Paulo            | 3        | 0.99%   |
| Prague               | 3        | 0.99%   |
| Paris                | 3        | 0.99%   |
| Madrid               | 3        | 0.99%   |
| London               | 3        | 0.99%   |
| Helsinki             | 3        | 0.99%   |
| Dallas               | 3        | 0.99%   |
| Brisbane             | 3        | 0.99%   |
| Warsaw               | 2        | 0.66%   |
| Sydney               | 2        | 0.66%   |
| San Jose             | 2        | 0.66%   |
| Rosario              | 2        | 0.66%   |
| Pretoria             | 2        | 0.66%   |
| Ottawa               | 2        | 0.66%   |
| Ostrava              | 2        | 0.66%   |
| Niederhaslach        | 2        | 0.66%   |
| Melbourne            | 2        | 0.66%   |
| Lima                 | 2        | 0.66%   |
| Hamburg              | 2        | 0.66%   |
| Dublin               | 2        | 0.66%   |
| Buenos Aires         | 2        | 0.66%   |
| Bucharest            | 2        | 0.66%   |
| Zurich               | 1        | 0.33%   |
| Zoersel              | 1        | 0.33%   |
| Ziar nad Hronom      | 1        | 0.33%   |
| Zdanice              | 1        | 0.33%   |
| Ypsilanti            | 1        | 0.33%   |
| Yekaterinburg        | 1        | 0.33%   |
| Wuhan                | 1        | 0.33%   |
| Woodland Hills       | 1        | 0.33%   |
| Woodbridge           | 1        | 0.33%   |
| Wingerode            | 1        | 0.33%   |
| Wiesbaden            | 1        | 0.33%   |
| West Monroe          | 1        | 0.33%   |
| Walled Lake          | 1        | 0.33%   |
| Volta Redonda        | 1        | 0.33%   |
| Vilnius              | 1        | 0.33%   |
| Villanova Monteleone | 1        | 0.33%   |
| Vila Nova de Gaia    | 1        | 0.33%   |
| Vienna               | 1        | 0.33%   |
| Varna                | 1        | 0.33%   |
| Varginha             | 1        | 0.33%   |
| Vantaa               | 1        | 0.33%   |
| Valparaiso de Goias  | 1        | 0.33%   |
| Valdemoro            | 1        | 0.33%   |
| Utrecht              | 1        | 0.33%   |
| Ufa                  | 1        | 0.33%   |
| Tuscola              | 1        | 0.33%   |
| Thessaloniki         | 1        | 0.33%   |
| Temple City          | 1        | 0.33%   |
| Tehran               | 1        | 0.33%   |
| Tampere              | 1        | 0.33%   |
| Tampa                | 1        | 0.33%   |
| Tallinn              | 1        | 0.33%   |
| Taipei               | 1        | 0.33%   |
| Taichung             | 1        | 0.33%   |
| Szaflary             | 1        | 0.33%   |
| Sutton Coldfield     | 1        | 0.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 111      | 205    | 19.37%  |
| Seagate                     | 104      | 149    | 18.15%  |
| Samsung Electronics         | 84       | 124    | 14.66%  |
| Kingston                    | 42       | 52     | 7.33%   |
| Toshiba                     | 28       | 42     | 4.89%   |
| Crucial                     | 27       | 33     | 4.71%   |
| SanDisk                     | 26       | 30     | 4.54%   |
| Phison                      | 11       | 12     | 1.92%   |
| Hitachi                     | 11       | 13     | 1.92%   |
| HGST                        | 8        | 11     | 1.4%    |
| A-DATA Technology           | 8        | 10     | 1.4%    |
| SK Hynix                    | 6        | 8      | 1.05%   |
| Unknown                     | 5        | 11     | 0.87%   |
| PNY                         | 5        | 7      | 0.87%   |
| OCZ                         | 5        | 13     | 0.87%   |
| Micron/Crucial Technology   | 5        | 8      | 0.87%   |
| Intenso                     | 5        | 5      | 0.87%   |
| Intel                       | 5        | 5      | 0.87%   |
| Gigabyte Technology         | 5        | 5      | 0.87%   |
| China                       | 5        | 6      | 0.87%   |
| Silicon Motion              | 4        | 4      | 0.7%    |
| Micron Technology           | 4        | 5      | 0.7%    |
| XPG                         | 3        | 4      | 0.52%   |
| Transcend                   | 3        | 3      | 0.52%   |
| SPCC                        | 3        | 3      | 0.52%   |
| Netac                       | 3        | 3      | 0.52%   |
| Lexar                       | 3        | 3      | 0.52%   |
| Dogfish                     | 3        | 3      | 0.52%   |
| Corsair                     | 3        | 3      | 0.52%   |
| WALRAM                      | 2        | 2      | 0.35%   |
| MAXTOR                      | 2        | 3      | 0.35%   |
| KIOXIA                      | 2        | 3      | 0.35%   |
| KingFast                    | 2        | 2      | 0.35%   |
| JMicron                     | 2        | 2      | 0.35%   |
| ASMT                        | 2        | 2      | 0.35%   |
| Unknown                     | 2        | 2      | 0.35%   |
| ViperTeq                    | 1        | 1      | 0.17%   |
| USB3.0                      | 1        | 1      | 0.17%   |
| UMAX                        | 1        | 1      | 0.17%   |
| TCSUNBOW-X5                 | 1        | 1      | 0.17%   |
| TCSUNBOW                    | 1        | 2      | 0.17%   |
| Smartbuy                    | 1        | 1      | 0.17%   |
| S3+                         | 1        | 1      | 0.17%   |
| RIM                         | 1        | 1      | 0.17%   |
| Realtek Semiconductor       | 1        | 1      | 0.17%   |
| Patriot                     | 1        | 1      | 0.17%   |
| MidasForce                  | 1        | 1      | 0.17%   |
| MAXIO Technology (Hangzhou) | 1        | 1      | 0.17%   |
| LONDISK                     | 1        | 2      | 0.17%   |
| LDLC                        | 1        | 1      | 0.17%   |
| KLEVV                       | 1        | 1      | 0.17%   |
| KIOXIA-EXCERIA              | 1        | 1      | 0.17%   |
| HGST HTS                    | 1        | 1      | 0.17%   |
| Hewlett-Packard             | 1        | 1      | 0.17%   |
| FORESEE                     | 1        | 1      | 0.17%   |
| EMTEC                       | 1        | 1      | 0.17%   |
| COOLFISH                    | 1        | 1      | 0.17%   |
| BAITITON                    | 1        | 1      | 0.17%   |
| Apacer                      | 1        | 1      | 0.17%   |
| AMD                         | 1        | 1      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Seagate ST2000DM008-2FR102 2TB    | 10       | 1.41%   |
| Samsung NVMe SSD Drive 1TB        | 9        | 1.27%   |
| Seagate ST500DM002-1BD142 500GB   | 8        | 1.13%   |
| Kingston SA400S37240G 240GB SSD   | 8        | 1.13%   |
| Seagate ST1000DM010-2EP102 1TB    | 7        | 0.99%   |
| Sandisk NVMe SSD Drive 1TB        | 7        | 0.99%   |
| WDC WD10EZEX-08WN4A0 1TB          | 6        | 0.85%   |
| Seagate ST1000DM003-1ER162 1TB    | 6        | 0.85%   |
| Samsung SSD 860 EVO 500GB         | 6        | 0.85%   |
| Samsung SSD 850 EVO 500GB         | 6        | 0.85%   |
| Samsung SSD 850 EVO 250GB         | 6        | 0.85%   |
| Toshiba HDWD110 1TB               | 5        | 0.71%   |
| Seagate ST31000528AS 1TB          | 5        | 0.71%   |
| Sandisk NVMe SSD Drive 500GB      | 5        | 0.71%   |
| Samsung SSD 980 1TB               | 5        | 0.71%   |
| Samsung SSD 970 EVO Plus 500GB    | 5        | 0.71%   |
| Samsung NVMe SSD Drive 500GB      | 5        | 0.71%   |
| Kingston SA400S37480G 480GB SSD   | 5        | 0.71%   |
| Crucial CT1000MX500SSD1 1TB       | 5        | 0.71%   |
| Toshiba MQ01ABD100 1TB            | 4        | 0.56%   |
| Toshiba DT01ACA200 2TB            | 4        | 0.56%   |
| Toshiba DT01ACA050 500GB          | 4        | 0.56%   |
| Seagate ST1000DM003-1CH162 1TB    | 4        | 0.56%   |
| Samsung SSD 980 PRO 1TB           | 4        | 0.56%   |
| Samsung SSD 870 QVO 1TB           | 4        | 0.56%   |
| Crucial CT500MX500SSD1 500GB      | 4        | 0.56%   |
| WDC WD80EFAX-68LHPN0 8TB          | 3        | 0.42%   |
| WDC WD20EARX-00PASB0 2TB          | 3        | 0.42%   |
| WDC WD1003FZEX-00MK2A0 1TB        | 3        | 0.42%   |
| Toshiba DT01ACA300 3TB            | 3        | 0.42%   |
| Seagate ST4000DM004-2CV104 4TB    | 3        | 0.42%   |
| Seagate ST2000DL003-9VT166 2TB    | 3        | 0.42%   |
| Seagate ST1000DM003-9YN162 1TB    | 3        | 0.42%   |
| SanDisk SSD PLUS 2000GB           | 3        | 0.42%   |
| SanDisk SDSSDHII240G 240GB        | 3        | 0.42%   |
| SanDisk SDSSDA240G 240GB          | 3        | 0.42%   |
| Samsung SSD 870 QVO 2TB           | 3        | 0.42%   |
| Phison NVMe SSD Drive 256GB       | 3        | 0.42%   |
| Micron/Crucial NVMe SSD Drive 1TB | 3        | 0.42%   |
| Lexar 128GB SSD                   | 3        | 0.42%   |
| Kingston SV300S37A240G 240GB SSD  | 3        | 0.42%   |
| Kingston SHSS37A480G 480GB SSD    | 3        | 0.42%   |
| Kingston SA400S37120G 120GB SSD   | 3        | 0.42%   |
| Kingston NVMe SSD Drive 500GB     | 3        | 0.42%   |
| HGST HTS721010A9E630 1TB          | 3        | 0.42%   |
| Dogfish SSD 128GB                 | 3        | 0.42%   |
| Crucial CT1000BX500SSD1 1TB       | 3        | 0.42%   |
| WDC WDS500G3X0C-00SJG0 500GB      | 2        | 0.28%   |
| WDC WDS500G2B0A-00SM50 500GB SSD  | 2        | 0.28%   |
| WDC WDS250G2B0A-00SM50 250GB SSD  | 2        | 0.28%   |
| WDC WDS240G2G0A-00JH30 240GB SSD  | 2        | 0.28%   |
| WDC WDS120G2G0A-00JH30 120GB SSD  | 2        | 0.28%   |
| WDC WDS100T3X0C-00SJG0 1TB        | 2        | 0.28%   |
| WDC WDS100T1X0E-00AFY0 1TB        | 2        | 0.28%   |
| WDC WD82PURZ-85TEUY0 8TB          | 2        | 0.28%   |
| WDC WD80EMAZ-00WJTA0 8TB          | 2        | 0.28%   |
| WDC WD80EFAX-68KNBN0 8TB          | 2        | 0.28%   |
| WDC WD800JD-75MSA3 80GB           | 2        | 0.28%   |
| WDC WD6003FZBX-00K5WB0 6TB        | 2        | 0.28%   |
| WDC WD5000AZLX-08K2TA0 500GB      | 2        | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 99       | 144    | 39.76%  |
| WDC                 | 95       | 172    | 38.15%  |
| Toshiba             | 24       | 36     | 9.64%   |
| Hitachi             | 11       | 13     | 4.42%   |
| Samsung Electronics | 8        | 10     | 3.21%   |
| HGST                | 8        | 11     | 3.21%   |
| ASMT                | 2        | 2      | 0.8%    |
| Unknown             | 1        | 1      | 0.4%    |
| MAXTOR              | 1        | 2      | 0.4%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 47       | 60     | 20.98%  |
| Kingston            | 37       | 43     | 16.52%  |
| Crucial             | 27       | 33     | 12.05%  |
| WDC                 | 16       | 19     | 7.14%   |
| SanDisk             | 16       | 16     | 7.14%   |
| A-DATA Technology   | 6        | 8      | 2.68%   |
| PNY                 | 5        | 7      | 2.23%   |
| Intel               | 5        | 5      | 2.23%   |
| China               | 5        | 6      | 2.23%   |
| Transcend           | 3        | 3      | 1.34%   |
| Toshiba             | 3        | 4      | 1.34%   |
| SPCC                | 3        | 3      | 1.34%   |
| SK Hynix            | 3        | 3      | 1.34%   |
| OCZ                 | 3        | 3      | 1.34%   |
| Lexar               | 3        | 3      | 1.34%   |
| Intenso             | 3        | 3      | 1.34%   |
| Gigabyte Technology | 3        | 3      | 1.34%   |
| Dogfish             | 3        | 3      | 1.34%   |
| Corsair             | 3        | 3      | 1.34%   |
| Phison              | 2        | 2      | 0.89%   |
| Netac               | 2        | 2      | 0.89%   |
| Micron Technology   | 2        | 3      | 0.89%   |
| JMicron             | 2        | 2      | 0.89%   |
| Unknown             | 2        | 2      | 0.89%   |
| ViperTeq            | 1        | 1      | 0.45%   |
| USB3.0              | 1        | 1      | 0.45%   |
| UMAX                | 1        | 1      | 0.45%   |
| TCSUNBOW-X5         | 1        | 1      | 0.45%   |
| Smartbuy            | 1        | 1      | 0.45%   |
| Seagate             | 1        | 1      | 0.45%   |
| S3+                 | 1        | 1      | 0.45%   |
| Patriot             | 1        | 1      | 0.45%   |
| MidasForce          | 1        | 1      | 0.45%   |
| MAXTOR              | 1        | 1      | 0.45%   |
| LONDISK             | 1        | 2      | 0.45%   |
| LDLC                | 1        | 1      | 0.45%   |
| KLEVV               | 1        | 1      | 0.45%   |
| KIOXIA-EXCERIA      | 1        | 1      | 0.45%   |
| Hewlett-Packard     | 1        | 1      | 0.45%   |
| FORESEE             | 1        | 1      | 0.45%   |
| EMTEC               | 1        | 1      | 0.45%   |
| BAITITON            | 1        | 1      | 0.45%   |
| Apacer              | 1        | 1      | 0.45%   |
| AMD                 | 1        | 1      | 0.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 196      | 391    | 40.41%  |
| SSD     | 177      | 260    | 36.49%  |
| NVMe    | 94       | 146    | 19.38%  |
| Unknown | 16       | 20     | 3.3%    |
| MMC     | 2        | 5      | 0.41%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 265      | 631    | 68.65%  |
| NVMe | 94       | 146    | 24.35%  |
| SAS  | 25       | 40     | 6.48%   |
| MMC  | 2        | 5      | 0.52%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 189      | 278    | 45.43%  |
| 0.51-1.0   | 118      | 169    | 28.37%  |
| 1.01-2.0   | 59       | 98     | 14.18%  |
| 3.01-4.0   | 18       | 25     | 4.33%   |
| 4.01-10.0  | 18       | 59     | 4.33%   |
| 2.01-3.0   | 8        | 10     | 1.92%   |
| 10.01-20.0 | 6        | 12     | 1.44%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 74       | 24.18%  |
| 251-500        | 58       | 18.95%  |
| 501-1000       | 52       | 16.99%  |
| More than 3000 | 38       | 12.42%  |
| 1001-2000      | 36       | 11.76%  |
| 1-20           | 18       | 5.88%   |
| 2001-3000      | 17       | 5.56%   |
| 51-100         | 11       | 3.59%   |
| 21-50          | 1        | 0.33%   |
| Unknown        | 1        | 0.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 112      | 36.25%  |
| 21-50          | 43       | 13.92%  |
| 101-250        | 38       | 12.3%   |
| 251-500        | 34       | 11%     |
| 51-100         | 30       | 9.71%   |
| More than 3000 | 18       | 5.83%   |
| 1001-2000      | 15       | 4.85%   |
| 501-1000       | 11       | 3.56%   |
| 2001-3000      | 6        | 1.94%   |
| 0              | 1        | 0.32%   |
| Unknown        | 1        | 0.32%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| WDC WD5000AAKX-08ERMA0 500GB        | 1        | 1      | 6.25%   |
| WDC WD5000AAKS-65V0A0 500GB         | 1        | 1      | 6.25%   |
| WDC WD20EARX-008FB0 2TB             | 1        | 2      | 6.25%   |
| WDC WD10EZEX-22MFCA0 1TB            | 1        | 1      | 6.25%   |
| WDC WD10EFRX-68FYTN0 1TB            | 1        | 1      | 6.25%   |
| WDC WD1003FBYX-01Y7B1 1TB           | 1        | 1      | 6.25%   |
| Toshiba MQ01ABD100 1TB              | 1        | 1      | 6.25%   |
| Seagate ST500DM002-1BD142 500GB     | 1        | 1      | 6.25%   |
| Seagate ST3750640NS 752GB           | 1        | 2      | 6.25%   |
| Seagate ST2000DX002-2DV164 2TB      | 1        | 1      | 6.25%   |
| Samsung Electronics SSD 870 EVO 1TB | 1        | 1      | 6.25%   |
| Kingston SV300S37A60G 64GB SSD      | 1        | 1      | 6.25%   |
| Kingston SA400S37240G 240GB SSD     | 1        | 1      | 6.25%   |
| Intenso SSD 120GB                   | 1        | 1      | 6.25%   |
| Hitachi HDS721010CLA332 1TB         | 1        | 1      | 6.25%   |
| HGST HTS721010A9E630 1TB            | 1        | 2      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 6        | 7      | 37.5%   |
| Seagate             | 3        | 4      | 18.75%  |
| Kingston            | 2        | 2      | 12.5%   |
| Toshiba             | 1        | 1      | 6.25%   |
| Samsung Electronics | 1        | 1      | 6.25%   |
| Intenso             | 1        | 1      | 6.25%   |
| Hitachi             | 1        | 1      | 6.25%   |
| HGST                | 1        | 2      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 6        | 7      | 50%     |
| Seagate | 3        | 4      | 25%     |
| Toshiba | 1        | 1      | 8.33%   |
| Hitachi | 1        | 1      | 8.33%   |
| HGST    | 1        | 2      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 11       | 15     | 73.33%  |
| SSD  | 4        | 4      | 26.67%  |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 230      | 619    | 70.99%  |
| Works    | 79       | 184    | 24.38%  |
| Malfunc  | 15       | 19     | 4.63%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 195      | 41.94%  |
| AMD                          | 94       | 20.22%  |
| Samsung Electronics          | 41       | 8.82%   |
| Sandisk                      | 24       | 5.16%   |
| ASMedia Technology           | 19       | 4.09%   |
| Marvell Technology Group     | 16       | 3.44%   |
| JMicron Technology           | 12       | 2.58%   |
| Phison Electronics           | 10       | 2.15%   |
| Nvidia                       | 9        | 1.94%   |
| Kingston Technology Company  | 6        | 1.29%   |
| Micron/Crucial Technology    | 5        | 1.08%   |
| LSI Logic / Symbios Logic    | 5        | 1.08%   |
| SK Hynix                     | 4        | 0.86%   |
| Silicon Motion               | 4        | 0.86%   |
| KIOXIA                       | 3        | 0.65%   |
| ADATA Technology             | 3        | 0.65%   |
| VIA Technologies             | 2        | 0.43%   |
| Silicon Image                | 2        | 0.43%   |
| Realtek Semiconductor        | 2        | 0.43%   |
| OCZ Technology Group         | 2        | 0.43%   |
| Micron Technology            | 2        | 0.43%   |
| Toshiba America Info Systems | 1        | 0.22%   |
| Seagate Technology           | 1        | 0.22%   |
| MAXIO Technology (Hangzhou)  | 1        | 0.22%   |
| Chelsio Communications       | 1        | 0.22%   |
| Broadcom / LSI               | 1        | 0.22%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 60       | 10.43%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 21       | 3.65%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 20       | 3.48%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 19       | 3.3%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 18       | 3.13%   |
| AMD 400 Series Chipset SATA Controller                                                  | 18       | 3.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 17       | 2.96%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 14       | 2.43%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 12       | 2.09%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 12       | 2.09%   |
| AMD 500 Series Chipset SATA Controller                                                  | 11       | 1.91%   |
| Samsung NVMe SSD Controller 980                                                         | 10       | 1.74%   |
| Intel SATA Controller [RAID mode]                                                       | 9        | 1.57%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 9        | 1.57%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 9        | 1.57%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 8        | 1.39%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 8        | 1.39%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 8        | 1.39%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 8        | 1.39%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 7        | 1.22%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 7        | 1.22%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 7        | 1.22%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 7        | 1.22%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                              | 6        | 1.04%   |
| Sandisk Non-Volatile memory controller                                                  | 6        | 1.04%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 6        | 1.04%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 6        | 1.04%   |
| AMD FCH SATA Controller D                                                               | 6        | 1.04%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 5        | 0.87%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 5        | 0.87%   |
| JMicron JMB368 IDE controller                                                           | 5        | 0.87%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 5        | 0.87%   |
| AMD X370 Series Chipset SATA Controller                                                 | 5        | 0.87%   |
| AMD 300 Series Chipset SATA Controller                                                  | 5        | 0.87%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 4        | 0.7%    |
| Sandisk WD Blue SN570 NVMe SSD                                                          | 4        | 0.7%    |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 4        | 0.7%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 4        | 0.7%    |
| Kingston Company A2000 NVMe SSD                                                         | 4        | 0.7%    |
| Intel Volume Management Device NVMe RAID Controller                                     | 4        | 0.7%    |
| Intel Comet Lake SATA AHCI Controller                                                   | 4        | 0.7%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 4        | 0.7%    |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 4        | 0.7%    |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 4        | 0.7%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 4        | 0.7%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4        | 0.7%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 4        | 0.7%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 4        | 0.7%    |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 3        | 0.52%   |
| Phison E12 NVMe Controller                                                              | 3        | 0.52%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 3        | 0.52%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 3        | 0.52%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 3        | 0.52%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 3        | 0.52%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 3        | 0.52%   |
| Intel 631xESB/632xESB SATA AHCI Controller                                              | 3        | 0.52%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 3        | 0.52%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3        | 0.52%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 3        | 0.52%   |
| SK Hynix Gold P31 SSD                                                                   | 2        | 0.35%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 247      | 55.76%  |
| NVMe | 94       | 21.22%  |
| IDE  | 70       | 15.8%   |
| RAID | 21       | 4.74%   |
| SAS  | 6        | 1.35%   |
| SCSI | 5        | 1.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 201      | 66.78%  |
| AMD    | 100      | 33.22%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 10       | 3.32%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 5        | 1.66%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 5        | 1.66%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 5        | 1.66%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 5        | 1.66%   |
| AMD Phenom II X4 965 Processor              | 5        | 1.66%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 4        | 1.33%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 4        | 1.33%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 4        | 1.33%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 4        | 1.33%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 4        | 1.33%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 3        | 1%      |
| Intel Core i5-3570 CPU @ 3.40GHz            | 3        | 1%      |
| Intel Core i3-3220 CPU @ 3.30GHz            | 3        | 1%      |
| Intel Core i3-10100 CPU @ 3.60GHz           | 3        | 1%      |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz       | 3        | 1%      |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 3        | 1%      |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 3        | 1%      |
| AMD Ryzen 9 3900X 12-Core Processor         | 3        | 1%      |
| AMD Ryzen 7 5800X 8-Core Processor          | 3        | 1%      |
| AMD Ryzen 7 5700G with Radeon Graphics      | 3        | 1%      |
| AMD Ryzen 7 2700X Eight-Core Processor      | 3        | 1%      |
| AMD Ryzen 7 1800X Eight-Core Processor      | 3        | 1%      |
| AMD Ryzen 7 1700 Eight-Core Processor       | 3        | 1%      |
| AMD Ryzen 5 5600G with Radeon Graphics      | 3        | 1%      |
| AMD Ryzen 5 2600 Six-Core Processor         | 3        | 1%      |
| Intel Xeon CPU E5640 @ 2.67GHz              | 2        | 0.66%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 2        | 0.66%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 0.66%   |
| Intel Core i7-3820 CPU @ 3.60GHz            | 2        | 0.66%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2        | 0.66%   |
| Intel Core i5-9500 CPU @ 3.00GHz            | 2        | 0.66%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 2        | 0.66%   |
| Intel Core i5-4440 CPU @ 3.10GHz            | 2        | 0.66%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 0.66%   |
| Intel Core i5-3450 CPU @ 3.10GHz            | 2        | 0.66%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 2        | 0.66%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2        | 0.66%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 2        | 0.66%   |
| Intel Core i3-4170 CPU @ 3.70GHz            | 2        | 0.66%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 2        | 0.66%   |
| Intel Core i3-4150 CPU @ 3.50GHz            | 2        | 0.66%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 2        | 0.66%   |
| Intel Core i3 CPU 550 @ 3.20GHz             | 2        | 0.66%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 2        | 0.66%   |
| Intel Celeron J4105 CPU @ 1.50GHz           | 2        | 0.66%   |
| Intel 12th Gen Core i5-12600K               | 2        | 0.66%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 2        | 0.66%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 2        | 0.66%   |
| AMD Ryzen 5 3500X 6-Core Processor          | 2        | 0.66%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 2        | 0.66%   |
| AMD Phenom II X6 1090T Processor            | 2        | 0.66%   |
| AMD FX-8350 Eight-Core Processor            | 2        | 0.66%   |
| AMD FX-6300 Six-Core Processor              | 2        | 0.66%   |
| AMD Athlon II X4 640 Processor              | 2        | 0.66%   |
| Intel Xeon W-3275 CPU @ 2.50GHz             | 1        | 0.33%   |
| Intel Xeon CPU X5667 @ 3.07GHz              | 1        | 0.33%   |
| Intel Xeon CPU X5650 @ 2.67GHz              | 1        | 0.33%   |
| Intel Xeon CPU E5502 @ 1.87GHz              | 1        | 0.33%   |
| Intel Xeon CPU E5462 @ 2.80GHz              | 1        | 0.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 45       | 14.95%  |
| Intel Core i7           | 43       | 14.29%  |
| Intel Core i3           | 33       | 10.96%  |
| AMD Ryzen 7             | 24       | 7.97%   |
| AMD Ryzen 5             | 24       | 7.97%   |
| Intel Xeon              | 23       | 7.64%   |
| Other                   | 14       | 4.65%   |
| Intel Celeron           | 12       | 3.99%   |
| Intel Core 2 Quad       | 10       | 3.32%   |
| AMD Ryzen 9             | 10       | 3.32%   |
| Intel Core 2 Duo        | 8        | 2.66%   |
| AMD FX                  | 8        | 2.66%   |
| AMD Phenom II X4        | 7        | 2.33%   |
| Intel Pentium           | 5        | 1.66%   |
| Intel Core i9           | 3        | 1%      |
| AMD Ryzen 3             | 3        | 1%      |
| AMD Phenom II X6        | 3        | 1%      |
| AMD A8                  | 3        | 1%      |
| AMD Athlon II X4        | 2        | 0.66%   |
| AMD A10                 | 2        | 0.66%   |
| Intel Pentium Dual-Core | 1        | 0.33%   |
| Intel Pentium Dual      | 1        | 0.33%   |
| Intel Pentium 4         | 1        | 0.33%   |
| Intel Core 2 Extreme    | 1        | 0.33%   |
| Intel Core 2            | 1        | 0.33%   |
| Intel Atom              | 1        | 0.33%   |
| AMD Ryzen Threadripper  | 1        | 0.33%   |
| AMD Ryzen Embedded      | 1        | 0.33%   |
| AMD Ryzen 7 PRO         | 1        | 0.33%   |
| AMD Ryzen 5 PRO         | 1        | 0.33%   |
| AMD Phenom              | 1        | 0.33%   |
| AMD GX                  | 1        | 0.33%   |
| AMD E1                  | 1        | 0.33%   |
| AMD Athlon II X3        | 1        | 0.33%   |
| AMD Athlon 64 X2        | 1        | 0.33%   |
| AMD Athlon 64           | 1        | 0.33%   |
| AMD Athlon              | 1        | 0.33%   |
| AMD A6                  | 1        | 0.33%   |
| AMD A4                  | 1        | 0.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 119      | 39.53%  |
| 2      | 66       | 21.93%  |
| 6      | 44       | 14.62%  |
| 8      | 38       | 12.62%  |
| 12     | 11       | 3.65%   |
| 16     | 6        | 1.99%   |
| 10     | 6        | 1.99%   |
| 3      | 5        | 1.66%   |
| 1      | 3        | 1%      |
| 28     | 2        | 0.66%   |
| 64     | 1        | 0.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 292      | 97.01%  |
| 2      | 9        | 2.99%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 180      | 59.8%   |
| 1      | 121      | 40.2%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 301      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 196      | 64.26%  |
| 0x306c3    | 12       | 3.93%   |
| 0x506e3    | 6        | 1.97%   |
| 0x306a9    | 6        | 1.97%   |
| 0x0a201016 | 6        | 1.97%   |
| 0x08701021 | 6        | 1.97%   |
| 0x906e9    | 5        | 1.64%   |
| 0x206a7    | 5        | 1.64%   |
| 0x906ea    | 4        | 1.31%   |
| 0x90672    | 3        | 0.98%   |
| 0x1067a    | 3        | 0.98%   |
| 0x0a50000c | 3        | 0.98%   |
| 0x010000c8 | 3        | 0.98%   |
| 0xa0653    | 2        | 0.66%   |
| 0x906eb    | 2        | 0.66%   |
| 0x90675    | 2        | 0.66%   |
| 0x706a1    | 2        | 0.66%   |
| 0x306f2    | 2        | 0.66%   |
| 0x0a201009 | 2        | 0.66%   |
| 0x08701013 | 2        | 0.66%   |
| 0x0810100b | 2        | 0.66%   |
| 0x0800820d | 2        | 0.66%   |
| 0x06001119 | 2        | 0.66%   |
| 0x06000852 | 2        | 0.66%   |
| 0xa0671    | 1        | 0.33%   |
| 0xa0655    | 1        | 0.33%   |
| 0x906ed    | 1        | 0.33%   |
| 0x906ec    | 1        | 0.33%   |
| 0x806ec    | 1        | 0.33%   |
| 0x806e9    | 1        | 0.33%   |
| 0x806c1    | 1        | 0.33%   |
| 0x50654    | 1        | 0.33%   |
| 0x406f1    | 1        | 0.33%   |
| 0x306e4    | 1        | 0.33%   |
| 0x20655    | 1        | 0.33%   |
| 0x106a5    | 1        | 0.33%   |
| 0x10677    | 1        | 0.33%   |
| 0x10676    | 1        | 0.33%   |
| 0x0a201205 | 1        | 0.33%   |
| 0x0a201204 | 1        | 0.33%   |
| 0x0830104d | 1        | 0.33%   |
| 0x08108109 | 1        | 0.33%   |
| 0x08101016 | 1        | 0.33%   |
| 0x08001138 | 1        | 0.33%   |
| 0x08001137 | 1        | 0.33%   |
| 0x0800111c | 1        | 0.33%   |
| 0x0600611a | 1        | 0.33%   |
| 0x06003106 | 1        | 0.33%   |
| 0x05000119 | 1        | 0.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 38       | 12.62%  |
| IvyBridge        | 28       | 9.3%    |
| Zen 2            | 24       | 7.97%   |
| Zen 3            | 22       | 7.31%   |
| KabyLake         | 22       | 7.31%   |
| SandyBridge      | 21       | 6.98%   |
| Penryn           | 18       | 5.98%   |
| Skylake          | 17       | 5.65%   |
| K10              | 14       | 4.65%   |
| Piledriver       | 11       | 3.65%   |
| Zen+             | 10       | 3.32%   |
| Zen              | 10       | 3.32%   |
| Westmere         | 9        | 2.99%   |
| Core             | 8        | 2.66%   |
| CometLake        | 8        | 2.66%   |
| Nehalem          | 6        | 1.99%   |
| Unknown          | 6        | 1.99%   |
| Broadwell        | 5        | 1.66%   |
| Goldmont plus    | 4        | 1.33%   |
| Alderlake Hybrid | 4        | 1.33%   |
| Silvermont       | 3        | 1%      |
| TigerLake        | 2        | 0.66%   |
| Steamroller      | 2        | 0.66%   |
| K8 Hammer        | 2        | 0.66%   |
| Excavator        | 2        | 0.66%   |
| Puma             | 1        | 0.33%   |
| NetBurst         | 1        | 0.33%   |
| K10 Llano        | 1        | 0.33%   |
| Icelake          | 1        | 0.33%   |
| Bobcat           | 1        | 0.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 138      | 43.95%  |
| Intel                      | 91       | 28.98%  |
| AMD                        | 80       | 25.48%  |
| ASPEED Technology          | 3        | 0.96%   |
| Matrox Electronics Systems | 2        | 0.64%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 15       | 4.69%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 10       | 3.13%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 9        | 2.81%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9        | 2.81%   |
| Intel HD Graphics 530                                                                    | 7        | 2.19%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 7        | 2.19%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 7        | 2.19%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 6        | 1.88%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 6        | 1.88%   |
| AMD Cezanne                                                                              | 6        | 1.88%   |
| Nvidia GT218 [GeForce 210]                                                               | 5        | 1.56%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 5        | 1.56%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 5        | 1.56%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 5        | 1.56%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 5        | 1.56%   |
| Intel AlderLake-S GT1                                                                    | 5        | 1.56%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 5        | 1.56%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 4        | 1.25%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 4        | 1.25%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4        | 1.25%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 4        | 1.25%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4        | 1.25%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 4        | 1.25%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 4        | 1.25%   |
| Nvidia GT216 [GeForce GT 220]                                                            | 3        | 0.94%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 3        | 0.94%   |
| Nvidia GF108 [GeForce GT 440]                                                            | 3        | 0.94%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                                           | 3        | 0.94%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 3        | 0.94%   |
| Intel HD Graphics 630                                                                    | 3        | 0.94%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3        | 0.94%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3        | 0.94%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 3        | 0.94%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3        | 0.94%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 3        | 0.94%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 2        | 0.63%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 2        | 0.63%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                                       | 2        | 0.63%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 2        | 0.63%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 2        | 0.63%   |
| Nvidia GM206 [GeForce GTX 950]                                                           | 2        | 0.63%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 2        | 0.63%   |
| Nvidia GK104 [GeForce GTX 680]                                                           | 2        | 0.63%   |
| Nvidia GF114 [GeForce GTX 560]                                                           | 2        | 0.63%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 2        | 0.63%   |
| Nvidia GF106GL [Quadro 2000]                                                             | 2        | 0.63%   |
| Nvidia GA106 [Geforce RTX 3050]                                                          | 2        | 0.63%   |
| Nvidia GA104GL [RTX A4000]                                                               | 2        | 0.63%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                                        | 2        | 0.63%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                                       | 2        | 0.63%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2        | 0.63%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2        | 0.63%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2        | 0.63%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 2        | 0.63%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 2        | 0.63%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 2        | 0.63%   |
| AMD Hawaii PRO [Radeon R9 290/390]                                                       | 2        | 0.63%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 2        | 0.63%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 2        | 0.63%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 1        | 0.31%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 128      | 42.24%  |
| 1 x Intel       | 84       | 27.72%  |
| 1 x AMD         | 75       | 24.75%  |
| 2 x Nvidia      | 4        | 1.32%   |
| AMD + Nvidia    | 4        | 1.32%   |
| 2 x AMD         | 2        | 0.66%   |
| 1 x ASPEED      | 2        | 0.66%   |
| Nvidia + Matrox | 1        | 0.33%   |
| Nvidia + ASPEED | 1        | 0.33%   |
| 1 x Matrox      | 1        | 0.33%   |
| Intel + Nvidia  | 1        | 0.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 199      | 65.89%  |
| Proprietary | 86       | 28.48%  |
| Unknown     | 17       | 5.63%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 214      | 70.39%  |
| 7.01-8.0   | 21       | 6.91%   |
| 0.51-1.0   | 21       | 6.91%   |
| 1.01-2.0   | 16       | 5.26%   |
| 3.01-4.0   | 13       | 4.28%   |
| 8.01-16.0  | 10       | 3.29%   |
| 0.01-0.5   | 5        | 1.64%   |
| 5.01-6.0   | 2        | 0.66%   |
| 4.01-5.0   | 1        | 0.33%   |
| 2.01-3.0   | 1        | 0.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 59       | 19.03%  |
| Goldstar             | 36       | 11.61%  |
| Dell                 | 34       | 10.97%  |
| Ancor Communications | 20       | 6.45%   |
| Acer                 | 18       | 5.81%   |
| Hewlett-Packard      | 13       | 4.19%   |
| BenQ                 | 12       | 3.87%   |
| AOC                  | 12       | 3.87%   |
| Philips              | 11       | 3.55%   |
| ViewSonic            | 10       | 3.23%   |
| Lenovo               | 8        | 2.58%   |
| ASUSTek Computer     | 8        | 2.58%   |
| LG Electronics       | 6        | 1.94%   |
| Unknown              | 4        | 1.29%   |
| Onkyo                | 4        | 1.29%   |
| Iiyama               | 3        | 0.97%   |
| Unknown              | 3        | 0.97%   |
| Vizio                | 2        | 0.65%   |
| Unknown (XXX)        | 2        | 0.65%   |
| Sony                 | 2        | 0.65%   |
| Sceptre Tech         | 2        | 0.65%   |
| Panasonic            | 2        | 0.65%   |
| NEC Computers        | 2        | 0.65%   |
| Medion               | 2        | 0.65%   |
| HKC                  | 2        | 0.65%   |
| CTV                  | 2        | 0.65%   |
| ___                  | 1        | 0.32%   |
| Vestel Elektronik    | 1        | 0.32%   |
| Toshiba              | 1        | 0.32%   |
| TCT                  | 1        | 0.32%   |
| Sunplus              | 1        | 0.32%   |
| SPU                  | 1        | 0.32%   |
| Skyworth             | 1        | 0.32%   |
| Sharp                | 1        | 0.32%   |
| RTK                  | 1        | 0.32%   |
| RS                   | 1        | 0.32%   |
| RCA                  | 1        | 0.32%   |
| Planar               | 1        | 0.32%   |
| Plain Tree Systems   | 1        | 0.32%   |
| OEM                  | 1        | 0.32%   |
| MStar                | 1        | 0.32%   |
| MSI                  | 1        | 0.32%   |
| Mitsubishi           | 1        | 0.32%   |
| KTC                  | 1        | 0.32%   |
| Idek Iiyama          | 1        | 0.32%   |
| HUAWEI               | 1        | 0.32%   |
| Hitachi              | 1        | 0.32%   |
| HannStar             | 1        | 0.32%   |
| Gigabyte Technology  | 1        | 0.32%   |
| Fujitsu Siemens      | 1        | 0.32%   |
| EVE                  | 1        | 0.32%   |
| Eizo                 | 1        | 0.32%   |
| CTL                  | 1        | 0.32%   |
| Compal               | 1        | 0.32%   |
| CHD                  | 1        | 0.32%   |
| Apple                | 1        | 0.32%   |
| AMG                  | 1        | 0.32%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 3        | 0.93%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 3        | 0.93%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 520x290mm 23.4-inch | 3        | 0.93%   |
| Unknown                                                               | 3        | 0.93%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 2        | 0.62%   |
| Samsung Electronics LS28AG700N SAM7177 3840x2160 632x360mm 28.6-inch  | 2        | 0.62%   |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 700x390mm 31.5-inch | 2        | 0.62%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 532x304mm 24.1-inch    | 2        | 0.62%   |
| Onkyo TX-NR747 ONK0F71 1920x1200 550x309mm 24.8-inch                  | 2        | 0.62%   |
| HKC 24N1 HKC2413 1920x1080 527x296mm 23.8-inch                        | 2        | 0.62%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2        | 0.62%   |
| Dell U2410 DELF016 1920x1200 518x324mm 24.1-inch                      | 2        | 0.62%   |
| CTV bbk TV CTV0030 3840x2160 708x398mm 32.0-inch                      | 2        | 0.62%   |
| BenQ XL2411Z BNQ7F31 1920x1080 530x300mm 24.0-inch                    | 2        | 0.62%   |
| AOC 27B1 AOC2701 1920x1080 598x336mm 27.0-inch                        | 2        | 0.62%   |
| Ancor Communications VE248 ACI2494 1920x1080 531x299mm 24.0-inch      | 2        | 0.62%   |
| Ancor Communications ASUS VX279 ACI27E4 1920x1080 621x341mm 27.9-inch | 2        | 0.62%   |
| ___ LCDTV16 ___3393 1366x768                                          | 1        | 0.31%   |
| Vizio E40-D0 VIZ2001 1920x1080 885x498mm 40.0-inch                    | 1        | 0.31%   |
| Vizio E220VA VIZ0070 1920x1080 476x268mm 21.5-inch                    | 1        | 0.31%   |
| ViewSonic VX3276-FHD VSCE735 1920x1080 698x393mm 31.5-inch            | 1        | 0.31%   |
| ViewSonic VX2457 VSCB931 1920x1080 521x293mm 23.5-inch                | 1        | 0.31%   |
| ViewSonic VG2719-2K VSC1935 2560x1440 597x336mm 27.0-inch             | 1        | 0.31%   |
| ViewSonic VA902b VSC211C 1280x1024 376x301mm 19.0-inch                | 1        | 0.31%   |
| ViewSonic VA2855 SERIES VSCD62F 1920x1080 621x341mm 27.9-inch         | 1        | 0.31%   |
| ViewSonic VA2719 Series VSCC132 1920x1080 598x336mm 27.0-inch         | 1        | 0.31%   |
| ViewSonic VA2452 Series VSC7931 1920x1080 521x293mm 23.5-inch         | 1        | 0.31%   |
| ViewSonic VA2246 SERIES VSC6F2E 1920x1080 477x268mm 21.5-inch         | 1        | 0.31%   |
| ViewSonic VA1948 SERIES VSCE827 1440x900 408x255mm 18.9-inch          | 1        | 0.31%   |
| ViewSonic LCD Monitor VG2228 SERIES                                   | 1        | 0.31%   |
| Vestel Elektronik 22W_LCD_TV VES3700 1920x540                         | 1        | 0.31%   |
| Unknown LCDTV16 3393 1920x1080 1600x900mm 72.3-inch                   | 1        | 0.31%   |
| Unknown LCD Monitor XXX Union TV 1920x1080                            | 1        | 0.31%   |
| Unknown LCD Monitor SAMSUNG 2464x900                                  | 1        | 0.31%   |
| Unknown LCD Monitor RTK                                               | 1        | 0.31%   |
| Unknown HDMI 1560 1920x1080 300x260mm 15.6-inch                       | 1        | 0.31%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch         | 1        | 0.31%   |
| Unknown (XXX) SMART TV XXX2851 3840x2160                              | 1        | 0.31%   |
| Toshiba TV TSB0109 1920x1080 1594x900mm 72.1-inch                     | 1        | 0.31%   |
| TCT DP1080P60 TCT0270 2560x1600 480x270mm 21.7-inch                   | 1        | 0.31%   |
| Sunplus Monitor TV SPVFFFF 1920x1080 376x301mm 19.0-inch              | 1        | 0.31%   |
| SPU NERO3 SPU0757 1920x1080 708x398mm 32.0-inch                       | 1        | 0.31%   |
| Sony TV SNYDC02 1920x1080 930x523mm 42.0-inch                         | 1        | 0.31%   |
| Sony TV SNY6604 1920x1080                                             | 1        | 0.31%   |
| Skyworth SII REPEATER SII214F 1920x1080 476x268mm 21.5-inch           | 1        | 0.31%   |
| Sharp LCD SHP1099 1920x540 890x500mm 40.2-inch                        | 1        | 0.31%   |
| Sceptre Tech Sceptre T27 SPT0AD7 1920x1080 600x330mm 27.0-inch        | 1        | 0.31%   |
| Sceptre Tech Sceptre F27 SPT0ABF 1920x1080 409x230mm 18.5-inch        | 1        | 0.31%   |
| Samsung Electronics U32J59x SAM0F33 3840x2160 697x392mm 31.5-inch     | 1        | 0.31%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch     | 1        | 0.31%   |
| Samsung Electronics U28D590 SAM0B81 3840x2160 608x345mm 27.5-inch     | 1        | 0.31%   |
| Samsung Electronics T24D391 SAM0B73 1920x1080 520x290mm 23.4-inch     | 1        | 0.31%   |
| Samsung Electronics T24C550 SAM0AA1 1920x1080 521x293mm 23.5-inch     | 1        | 0.31%   |
| Samsung Electronics SyncMaster SAM05FC 1920x1080                      | 1        | 0.31%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                      | 1        | 0.31%   |
| Samsung Electronics SyncMaster SAM05CC 1920x1080 530x300mm 24.0-inch  | 1        | 0.31%   |
| Samsung Electronics SyncMaster SAM0524 1920x1080 480x270mm 21.7-inch  | 1        | 0.31%   |
| Samsung Electronics SyncMaster SAM0473 2048x1152 510x287mm 23.0-inch  | 1        | 0.31%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch  | 1        | 0.31%   |
| Samsung Electronics SyncMaster SAM037C 1680x1050 474x296mm 22.0-inch  | 1        | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 136      | 45.33%  |
| 3840x2160 (4K)     | 43       | 14.33%  |
| 2560x1440 (QHD)    | 29       | 9.67%   |
| 1680x1050 (WSXGA+) | 16       | 5.33%   |
| 1280x1024 (SXGA)   | 16       | 5.33%   |
| 1920x1200 (WUXGA)  | 12       | 4%      |
| 1440x900 (WXGA+)   | 8        | 2.67%   |
| 1366x768 (WXGA)    | 8        | 2.67%   |
| 1600x900 (HD+)     | 6        | 2%      |
| 3440x1440          | 5        | 1.67%   |
| 2560x1080          | 3        | 1%      |
| 1920x540           | 3        | 1%      |
| Unknown            | 3        | 1%      |
| 1024x768 (XGA)     | 2        | 0.67%   |
| 4480x1440          | 1        | 0.33%   |
| 4480x1080          | 1        | 0.33%   |
| 3840x1600          | 1        | 0.33%   |
| 3840x1080          | 1        | 0.33%   |
| 2560x1600          | 1        | 0.33%   |
| 2464x900           | 1        | 0.33%   |
| 2048x1536          | 1        | 0.33%   |
| 2048x1152          | 1        | 0.33%   |
| 1600x1200          | 1        | 0.33%   |
| 1280x768           | 1        | 0.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 48       | 15.64%  |
| 24      | 42       | 13.68%  |
| 23      | 41       | 13.36%  |
| 21      | 38       | 12.38%  |
| Unknown | 25       | 8.14%   |
| 19      | 14       | 4.56%   |
| 22      | 12       | 3.91%   |
| 31      | 11       | 3.58%   |
| 17      | 11       | 3.58%   |
| 34      | 8        | 2.61%   |
| 32      | 6        | 1.95%   |
| 20      | 6        | 1.95%   |
| 84      | 5        | 1.63%   |
| 43      | 4        | 1.3%    |
| 18      | 4        | 1.3%    |
| 72      | 3        | 0.98%   |
| 46      | 3        | 0.98%   |
| 40      | 3        | 0.98%   |
| 25      | 3        | 0.98%   |
| 15      | 3        | 0.98%   |
| 65      | 2        | 0.65%   |
| 54      | 2        | 0.65%   |
| 28      | 2        | 0.65%   |
| 26      | 2        | 0.65%   |
| 63      | 1        | 0.33%   |
| 57      | 1        | 0.33%   |
| 52      | 1        | 0.33%   |
| 48      | 1        | 0.33%   |
| 42      | 1        | 0.33%   |
| 37      | 1        | 0.33%   |
| 36      | 1        | 0.33%   |
| 33      | 1        | 0.33%   |
| 29      | 1        | 0.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 118      | 39.73%  |
| 401-500     | 66       | 22.22%  |
| Unknown     | 25       | 8.42%   |
| 601-700     | 24       | 8.08%   |
| 701-800     | 16       | 5.39%   |
| 301-350     | 12       | 4.04%   |
| 1001-1500   | 11       | 3.7%    |
| 1501-2000   | 8        | 2.69%   |
| 351-400     | 7        | 2.36%   |
| 901-1000    | 5        | 1.68%   |
| 801-900     | 4        | 1.35%   |
| 201-300     | 1        | 0.34%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 195      | 68.66%  |
| 16/10   | 38       | 13.38%  |
| Unknown | 20       | 7.04%   |
| 5/4     | 15       | 5.28%   |
| 21/9    | 8        | 2.82%   |
| 4/3     | 4        | 1.41%   |
| 32/9    | 2        | 0.7%    |
| 6/5     | 1        | 0.35%   |
| 3/2     | 1        | 0.35%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 105      | 34.88%  |
| 301-350        | 50       | 16.61%  |
| 151-200        | 30       | 9.97%   |
| 351-500        | 28       | 9.3%    |
| Unknown        | 25       | 8.31%   |
| 251-300        | 16       | 5.32%   |
| More than 1000 | 15       | 4.98%   |
| 501-1000       | 15       | 4.98%   |
| 141-150        | 13       | 4.32%   |
| 101-110        | 2        | 0.66%   |
| 131-140        | 1        | 0.33%   |
| 121-130        | 1        | 0.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 168      | 57.14%  |
| 101-120 | 57       | 19.39%  |
| Unknown | 25       | 8.5%    |
| 121-160 | 20       | 6.8%    |
| 1-50    | 16       | 5.44%   |
| 161-240 | 8        | 2.72%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 227      | 74.43%  |
| 2     | 54       | 17.7%   |
| 0     | 21       | 6.89%   |
| 3     | 2        | 0.66%   |
| 4     | 1        | 0.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 187      | 44%     |
| Intel                    | 134      | 31.53%  |
| Qualcomm Atheros         | 29       | 6.82%   |
| Broadcom                 | 12       | 2.82%   |
| Nvidia                   | 9        | 2.12%   |
| TP-Link                  | 6        | 1.41%   |
| Ralink                   | 5        | 1.18%   |
| Microsoft                | 4        | 0.94%   |
| Marvell Technology Group | 4        | 0.94%   |
| ASUSTek Computer         | 4        | 0.94%   |
| Mellanox Technologies    | 3        | 0.71%   |
| Broadcom Limited         | 3        | 0.71%   |
| Xiaomi                   | 2        | 0.47%   |
| Samsung Electronics      | 2        | 0.47%   |
| NetGear                  | 2        | 0.47%   |
| MEDIATEK                 | 2        | 0.47%   |
| ASIX Electronics         | 2        | 0.47%   |
| Aquantia                 | 2        | 0.47%   |
| Ralink Technology        | 1        | 0.24%   |
| Pulse-Eight              | 1        | 0.24%   |
| Motorola PCS             | 1        | 0.24%   |
| Microchip Technology     | 1        | 0.24%   |
| Micro Star International | 1        | 0.24%   |
| Linksys                  | 1        | 0.24%   |
| JMicron Technology       | 1        | 0.24%   |
| IMC Networks             | 1        | 0.24%   |
| D-Link System            | 1        | 0.24%   |
| D-Link                   | 1        | 0.24%   |
| Chelsio Communications   | 1        | 0.24%   |
| AVM                      | 1        | 0.24%   |
| American Megatrends      | 1        | 0.24%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 144      | 29.63%  |
| Realtek RTL8125 2.5GbE Controller                                 | 22       | 4.53%   |
| Intel I211 Gigabit Network Connection                             | 19       | 3.91%   |
| Intel Wi-Fi 6 AX200                                               | 17       | 3.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 13       | 2.67%   |
| Intel Ethernet Connection (2) I219-V                              | 12       | 2.47%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 9        | 1.85%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 9        | 1.85%   |
| Intel Ethernet Controller I225-V                                  | 9        | 1.85%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 7        | 1.44%   |
| Intel Ethernet Connection I217-V                                  | 7        | 1.44%   |
| Intel Ethernet Connection I217-LM                                 | 6        | 1.23%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5        | 1.03%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5        | 1.03%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 5        | 1.03%   |
| Intel 82579V Gigabit Network Connection                           | 5        | 1.03%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 5        | 1.03%   |
| Realtek 802.11ac NIC                                              | 4        | 0.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 4        | 0.82%   |
| Microsoft XBOX ACC                                                | 4        | 0.82%   |
| Intel Wireless 7260                                               | 4        | 0.82%   |
| Intel Ethernet Connection (2) I219-LM                             | 4        | 0.82%   |
| Intel Ethernet Connection (2) I218-V                              | 4        | 0.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4        | 0.82%   |
| Intel 82574L Gigabit Network Connection                           | 4        | 0.82%   |
| TP-Link 802.11ac WLAN Adapter                                     | 3        | 0.62%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 3        | 0.62%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3        | 0.62%   |
| Nvidia MCP77 Ethernet                                             | 3        | 0.62%   |
| Intel Wireless 7265                                               | 3        | 0.62%   |
| Intel Wireless 3165                                               | 3        | 0.62%   |
| Intel I210 Gigabit Network Connection                             | 3        | 0.62%   |
| Intel Ethernet Controller X550                                    | 3        | 0.62%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 0.62%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 3        | 0.62%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3        | 0.62%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 0.41%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2        | 0.41%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 2        | 0.41%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 2        | 0.41%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2        | 0.41%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2        | 0.41%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 2        | 0.41%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 0.41%   |
| Nvidia MCP61 Ethernet                                             | 2        | 0.41%   |
| MEDIATEK MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 2        | 0.41%   |
| Intel Ethernet Connection (17) I219-V                             | 2        | 0.41%   |
| Intel Ethernet Connection (13) I219-V                             | 2        | 0.41%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 0.41%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 2        | 0.41%   |
| Broadcom Limited BCM4321 802.11a/b/g/n                            | 2        | 0.41%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2        | 0.41%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1        | 0.21%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                             | 1        | 0.21%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 1        | 0.21%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 0.21%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.21%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.21%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1        | 0.21%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter               | 1        | 0.21%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 50       | 35.71%  |
| Realtek Semiconductor    | 34       | 24.29%  |
| Qualcomm Atheros         | 16       | 11.43%  |
| Broadcom                 | 7        | 5%      |
| TP-Link                  | 6        | 4.29%   |
| Ralink                   | 5        | 3.57%   |
| Microsoft                | 4        | 2.86%   |
| ASUSTek Computer         | 4        | 2.86%   |
| Broadcom Limited         | 3        | 2.14%   |
| NetGear                  | 2        | 1.43%   |
| MEDIATEK                 | 2        | 1.43%   |
| Ralink Technology        | 1        | 0.71%   |
| Micro Star International | 1        | 0.71%   |
| Linksys                  | 1        | 0.71%   |
| IMC Networks             | 1        | 0.71%   |
| D-Link System            | 1        | 0.71%   |
| D-Link                   | 1        | 0.71%   |
| AVM                      | 1        | 0.71%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                       | Desktops | Percent |
|---------------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                         | 17       | 12.06%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                         | 9        | 6.38%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                      | 9        | 6.38%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                          | 7        | 4.96%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                          | 5        | 3.55%   |
| Realtek 802.11ac NIC                                                                        | 4        | 2.84%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                  | 4        | 2.84%   |
| Microsoft XBOX ACC                                                                          | 4        | 2.84%   |
| Intel Wireless 7260                                                                         | 4        | 2.84%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                            | 4        | 2.84%   |
| TP-Link 802.11ac WLAN Adapter                                                               | 3        | 2.13%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                            | 3        | 2.13%   |
| Intel Wireless 7265                                                                         | 3        | 2.13%   |
| Intel Wireless 3165                                                                         | 3        | 2.13%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                            | 3        | 2.13%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                    | 2        | 1.42%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                             | 2        | 1.42%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                   | 2        | 1.42%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                  | 2        | 1.42%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                            | 2        | 1.42%   |
| MEDIATEK MT7921K (RZ608) Wi-Fi 6E 80MHz                                                     | 2        | 1.42%   |
| Broadcom Limited BCM4321 802.11a/b/g/n                                                      | 2        | 1.42%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                 | 1        | 0.71%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                                       | 1        | 0.71%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                         | 1        | 0.71%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                    | 1        | 0.71%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                             | 1        | 0.71%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                                         | 1        | 0.71%   |
| Realtek RTL8813AE 802.11ac PCIe Wireless Network Adapter                                    | 1        | 0.71%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                    | 1        | 0.71%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                             | 1        | 0.71%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                  | 1        | 0.71%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                       | 1        | 0.71%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                     | 1        | 0.71%   |
| Realtek RTL8187 Wireless Adapter                                                            | 1        | 0.71%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                                   | 1        | 0.71%   |
| Ralink MT7601U Wireless Adapter                                                             | 1        | 0.71%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                      | 1        | 0.71%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                                        | 1        | 0.71%   |
| Ralink RT2561/RT61 rev B 802.11g                                                            | 1        | 0.71%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                  | 1        | 0.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                            | 1        | 0.71%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                            | 1        | 0.71%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                              | 1        | 0.71%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                                  | 1        | 0.71%   |
| NetGear WN111(v2) RangeMax Next Wireless [Atheros AR9170+AR9101]                            | 1        | 0.71%   |
| NetGear A6210                                                                               | 1        | 0.71%   |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070]                  | 1        | 0.71%   |
| Linksys AE3000 802.11abgn (3x3) Wireless Adapter [Ralink RT3573]                            | 1        | 0.71%   |
| Intel Wireless-AC 9260                                                                      | 1        | 0.71%   |
| Intel Wireless 8265 / 8275                                                                  | 1        | 0.71%   |
| Intel Wireless 8260                                                                         | 1        | 0.71%   |
| Intel WiFi Link 5100                                                                        | 1        | 0.71%   |
| Intel Tiger Lake PCH CNVi WiFi                                                              | 1        | 0.71%   |
| Intel Comet Lake PCH CNVi WiFi                                                              | 1        | 0.71%   |
| Intel Centrino Advanced-N 6235                                                              | 1        | 0.71%   |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]                                        | 1        | 0.71%   |
| D-Link System DWA-160 802.11abgn Xtreme N Dual Band Adapter(rev.A1) [Atheros AR9170+AR9104] | 1        | 0.71%   |
| D-Link 802.11n WLAN Adapter                                                                 | 1        | 0.71%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                                  | 1        | 0.71%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 175      | 53.52%  |
| Intel                    | 107      | 32.72%  |
| Qualcomm Atheros         | 14       | 4.28%   |
| Nvidia                   | 9        | 2.75%   |
| Broadcom                 | 5        | 1.53%   |
| Marvell Technology Group | 4        | 1.22%   |
| Xiaomi                   | 2        | 0.61%   |
| Samsung Electronics      | 2        | 0.61%   |
| Mellanox Technologies    | 2        | 0.61%   |
| ASIX Electronics         | 2        | 0.61%   |
| Aquantia                 | 2        | 0.61%   |
| JMicron Technology       | 1        | 0.31%   |
| Chelsio Communications   | 1        | 0.31%   |
| American Megatrends      | 1        | 0.31%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 144      | 42.23%  |
| Realtek RTL8125 2.5GbE Controller                                              | 22       | 6.45%   |
| Intel I211 Gigabit Network Connection                                          | 19       | 5.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 13       | 3.81%   |
| Intel Ethernet Connection (2) I219-V                                           | 12       | 3.52%   |
| Intel Ethernet Controller I225-V                                               | 9        | 2.64%   |
| Intel Ethernet Connection I217-V                                               | 7        | 2.05%   |
| Intel Ethernet Connection I217-LM                                              | 6        | 1.76%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 5        | 1.47%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 5        | 1.47%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 5        | 1.47%   |
| Intel 82579V Gigabit Network Connection                                        | 5        | 1.47%   |
| Intel Ethernet Connection (2) I219-LM                                          | 4        | 1.17%   |
| Intel Ethernet Connection (2) I218-V                                           | 4        | 1.17%   |
| Intel 82574L Gigabit Network Connection                                        | 4        | 1.17%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 3        | 0.88%   |
| Nvidia MCP77 Ethernet                                                          | 3        | 0.88%   |
| Intel I210 Gigabit Network Connection                                          | 3        | 0.88%   |
| Intel Ethernet Controller X550                                                 | 3        | 0.88%   |
| Intel Ethernet Connection (7) I219-V                                           | 3        | 0.88%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 3        | 0.88%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 2        | 0.59%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 2        | 0.59%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2        | 0.59%   |
| Nvidia MCP61 Ethernet                                                          | 2        | 0.59%   |
| Intel Ethernet Connection (17) I219-V                                          | 2        | 0.59%   |
| Intel Ethernet Connection (13) I219-V                                          | 2        | 0.59%   |
| Intel 82566DM-2 Gigabit Network Connection                                     | 2        | 0.59%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                        | 2        | 0.59%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]              | 2        | 0.59%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1        | 0.29%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1        | 0.29%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1        | 0.29%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 1        | 0.29%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1        | 0.29%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1        | 0.29%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1        | 0.29%   |
| Nvidia MCP79 Ethernet                                                          | 1        | 0.29%   |
| Nvidia MCP73 Ethernet                                                          | 1        | 0.29%   |
| Nvidia MCP55 Ethernet                                                          | 1        | 0.29%   |
| Nvidia CK804 Ethernet Controller                                               | 1        | 0.29%   |
| Mellanox MT27500 Family [ConnectX-3]                                           | 1        | 0.29%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                          | 1        | 0.29%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1        | 0.29%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1        | 0.29%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 1        | 0.29%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                        | 1        | 0.29%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                            | 1        | 0.29%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                  | 1        | 0.29%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1        | 0.29%   |
| Intel Ethernet Connection (6) I219-LM                                          | 1        | 0.29%   |
| Intel Ethernet Connection (2) I218-LM                                          | 1        | 0.29%   |
| Intel Ethernet Connection (17) I219-LM                                         | 1        | 0.29%   |
| Intel Ethernet Connection (14) I219-V                                          | 1        | 0.29%   |
| Intel Ethernet Connection (12) I219-V                                          | 1        | 0.29%   |
| Intel Ethernet Connection (11) I219-V                                          | 1        | 0.29%   |
| Intel Ethernet Connection (11) I219-LM                                         | 1        | 0.29%   |
| Intel 82599 10 Gigabit Network Connection                                      | 1        | 0.29%   |
| Intel 82578DC Gigabit Network Connection                                       | 1        | 0.29%   |
| Intel 82576 Gigabit Network Connection                                         | 1        | 0.29%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 299      | 68.58%  |
| WiFi     | 133      | 30.5%   |
| Modem    | 2        | 0.46%   |
| Unknown  | 2        | 0.46%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 244      | 79.22%  |
| WiFi     | 64       | 20.78%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 179      | 59.47%  |
| 2     | 97       | 32.23%  |
| 3     | 20       | 6.64%   |
| 0     | 3        | 1%      |
| 8     | 1        | 0.33%   |
| 4     | 1        | 0.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 200      | 66.45%  |
| Yes  | 101      | 33.55%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 43       | 39.09%  |
| Cambridge Silicon Radio         | 23       | 20.91%  |
| Qualcomm Atheros Communications | 8        | 7.27%   |
| ASUSTek Computer                | 8        | 7.27%   |
| Realtek Semiconductor           | 6        | 5.45%   |
| Broadcom                        | 6        | 5.45%   |
| IMC Networks                    | 3        | 2.73%   |
| MediaTek                        | 2        | 1.82%   |
| Lite-On Technology              | 2        | 1.82%   |
| Apple                           | 2        | 1.82%   |
| TRENDnet                        | 1        | 0.91%   |
| TP-Link                         | 1        | 0.91%   |
| Micro Star International        | 1        | 0.91%   |
| Logitech                        | 1        | 0.91%   |
| Dell                            | 1        | 0.91%   |
| Belkin Components               | 1        | 0.91%   |
| Unknown                         | 1        | 0.91%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 23       | 20.91%  |
| Intel AX200 Bluetooth                                 | 13       | 11.82%  |
| Intel Bluetooth wireless interface                    | 10       | 9.09%   |
| Intel AX210 Bluetooth                                 | 9        | 8.18%   |
| Realtek Bluetooth Radio                               | 6        | 5.45%   |
| Qualcomm Atheros  Bluetooth Device                    | 4        | 3.64%   |
| Intel Wireless-AC 3168 Bluetooth                      | 4        | 3.64%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 4        | 3.64%   |
| Intel AX201 Bluetooth                                 | 3        | 2.73%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 3        | 2.73%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 2        | 1.82%   |
| MediaTek Wireless_Device                              | 2        | 1.82%   |
| Lite-On Bluetooth Device                              | 2        | 1.82%   |
| IMC Networks Bluetooth Radio                          | 2        | 1.82%   |
| ASUS ASUS USB-BT500                                   | 2        | 1.82%   |
| Apple Bluetooth USB Host Controller                   | 2        | 1.82%   |
| TRENDnet TBW-108UB USB Adapter                        | 1        | 0.91%   |
| TP-Link UB500 Adapter                                 | 1        | 0.91%   |
| Qualcomm Atheros Bluetooth USB Host Controller        | 1        | 0.91%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 1        | 0.91%   |
| Micro Star International Bluetooth Device             | 1        | 0.91%   |
| Logitech BT Mini-Receiver (HCI mode)                  | 1        | 0.91%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 1        | 0.91%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 1        | 0.91%   |
| Intel Bluetooth Device                                | 1        | 0.91%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 1        | 0.91%   |
| IMC Networks Bluetooth Device                         | 1        | 0.91%   |
| Dell BCM20702A0 Bluetooth Module                      | 1        | 0.91%   |
| Broadcom HP Bluethunder                               | 1        | 0.91%   |
| Broadcom BCM2035 Bluetooth dongle                     | 1        | 0.91%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter | 1        | 0.91%   |
| ASUS Qualcomm Bluetooth 4.1                           | 1        | 0.91%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 0.91%   |
| ASUS Bluetooth Radio                                  | 1        | 0.91%   |
| Unknown                                               | 1        | 0.91%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 191      | 38.9%   |
| Nvidia                                       | 124      | 25.25%  |
| AMD                                          | 123      | 25.05%  |
| C-Media Electronics                          | 12       | 2.44%   |
| Logitech                                     | 7        | 1.43%   |
| Creative Labs                                | 4        | 0.81%   |
| Generalplus Technology                       | 3        | 0.61%   |
| Razer USA                                    | 2        | 0.41%   |
| Micro Star International                     | 2        | 0.41%   |
| Kingston Technology                          | 2        | 0.41%   |
| Corsair                                      | 2        | 0.41%   |
| ASUSTek Computer                             | 2        | 0.41%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.2%    |
| XMOS                                         | 1        | 0.2%    |
| Texas Instruments                            | 1        | 0.2%    |
| Syntek                                       | 1        | 0.2%    |
| SteelSeries ApS                              | 1        | 0.2%    |
| Nam Tai E&E Products                         | 1        | 0.2%    |
| Medeli Electronics                           | 1        | 0.2%    |
| Giga-Byte Technology                         | 1        | 0.2%    |
| Ensoniq                                      | 1        | 0.2%    |
| Elgato Systems                               | 1        | 0.2%    |
| DigiTech                                     | 1        | 0.2%    |
| Creative Technology                          | 1        | 0.2%    |
| Bose                                         | 1        | 0.2%    |
| Audient                                      | 1        | 0.2%    |
| Astro Gaming                                 | 1        | 0.2%    |
| Arturia                                      | 1        | 0.2%    |
| Apple                                        | 1        | 0.2%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                          | 38       | 6.76%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 24       | 4.27%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 24       | 4.27%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 20       | 3.56%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 19       | 3.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 18       | 3.2%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 17       | 3.02%   |
| Nvidia GP104 High Definition Audio Controller                                     | 14       | 2.49%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 14       | 2.49%   |
| AMD Family 17h/19h HD Audio Controller                                            | 12       | 2.14%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 10       | 1.78%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 10       | 1.78%   |
| Nvidia GF108 High Definition Audio Controller                                     | 9        | 1.6%    |
| Intel C610/X99 series chipset HD Audio Controller                                 | 9        | 1.6%    |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 9        | 1.6%    |
| AMD Navi 10 HDMI Audio                                                            | 9        | 1.6%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 9        | 1.6%    |
| Nvidia High Definition Audio Controller                                           | 8        | 1.42%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 8        | 1.42%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 8        | 1.42%   |
| Intel 200 Series PCH HD Audio                                                     | 8        | 1.42%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 8        | 1.42%   |
| AMD FCH Azalia Controller                                                         | 8        | 1.42%   |
| Nvidia GM204 High Definition Audio Controller                                     | 7        | 1.25%   |
| Intel Cannon Lake PCH cAVS                                                        | 7        | 1.25%   |
| Intel Alder Lake-S HD Audio Controller                                            | 7        | 1.25%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 6        | 1.07%   |
| Nvidia GP106 High Definition Audio Controller                                     | 6        | 1.07%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 6        | 1.07%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 6        | 1.07%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 6        | 1.07%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 5        | 0.89%   |
| Nvidia GA102 High Definition Audio Controller                                     | 5        | 0.89%   |
| Nvidia Audio device                                                               | 5        | 0.89%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 5        | 0.89%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 5        | 0.89%   |
| Nvidia TU106 High Definition Audio Controller                                     | 4        | 0.71%   |
| Nvidia TU104 HD Audio Controller                                                  | 4        | 0.71%   |
| Nvidia GT216 HDMI Audio Controller                                                | 4        | 0.71%   |
| Nvidia GP108 High Definition Audio Controller                                     | 4        | 0.71%   |
| Nvidia GM206 High Definition Audio Controller                                     | 4        | 0.71%   |
| Nvidia GK107 HDMI Audio Controller                                                | 4        | 0.71%   |
| Nvidia GA104 High Definition Audio Controller                                     | 4        | 0.71%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 4        | 0.71%   |
| Intel Audio device                                                                | 4        | 0.71%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 4        | 0.71%   |
| Nvidia TU116 High Definition Audio Controller                                     | 3        | 0.53%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                         | 3        | 0.53%   |
| Nvidia GK104 HDMI Audio Controller                                                | 3        | 0.53%   |
| Nvidia GF106 High Definition Audio Controller                                     | 3        | 0.53%   |
| Intel Comet Lake PCH-V cAVS                                                       | 3        | 0.53%   |
| Intel Comet Lake PCH cAVS                                                         | 3        | 0.53%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 3        | 0.53%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 3        | 0.53%   |
| Intel 631xESB/632xESB High Definition Audio Controller                            | 3        | 0.53%   |
| Generalplus Technology Usb Audio Device                                           | 3        | 0.53%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 3        | 0.53%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3        | 0.53%   |
| Nvidia MCP61 High Definition Audio                                                | 2        | 0.36%   |
| Nvidia GP102 HDMI Audio Controller                                                | 2        | 0.36%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 28       | 21.21%  |
| Corsair             | 20       | 15.15%  |
| G.Skill             | 15       | 11.36%  |
| SK Hynix            | 13       | 9.85%   |
| Samsung Electronics | 12       | 9.09%   |
| Unknown             | 10       | 7.58%   |
| Micron Technology   | 8        | 6.06%   |
| Crucial             | 8        | 6.06%   |
| Patriot             | 3        | 2.27%   |
| Team                | 2        | 1.52%   |
| GeIL                | 2        | 1.52%   |
| V-Color             | 1        | 0.76%   |
| Unknown (ABCD)      | 1        | 0.76%   |
| TIMETEC             | 1        | 0.76%   |
| Ramaxel Technology  | 1        | 0.76%   |
| PNY                 | 1        | 0.76%   |
| Kllisre             | 1        | 0.76%   |
| Kingmax             | 1        | 0.76%   |
| Hewlett-Packard     | 1        | 0.76%   |
| GOODRAM             | 1        | 0.76%   |
| A-DATA Technology   | 1        | 0.76%   |
| Unknown             | 1        | 0.76%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s              | 3        | 2.05%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 2        | 1.37%   |
| Samsung RAM M391A2K43BB1-CTD 16384MB DIMM DDR4 3600MT/s        | 2        | 1.37%   |
| Micron RAM 8JTF25664AZ-1G6M1 2GB DIMM DDR3 1600MT/s            | 2        | 1.37%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s         | 2        | 1.37%   |
| Kingston RAM KHX2400C15/8G 8192MB DIMM DDR4 2933MT/s           | 2        | 1.37%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s            | 2        | 1.37%   |
| Kingston RAM KHX1600C10D3/8G 4096MB DIMM DDR3 1600MT/s         | 2        | 1.37%   |
| Corsair RAM CMY8GX3M2A1866C9 4GB DIMM DDR3 1867MT/s            | 2        | 1.37%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3600MT/s         | 2        | 1.37%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s          | 2        | 1.37%   |
| V-Color RAM TD48G26S819K-VC 8GB DIMM DDR4 2667MT/s             | 1        | 0.68%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                           | 1        | 0.68%   |
| Unknown RAM Module 4GB DIMM SDRAM                              | 1        | 0.68%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                           | 1        | 0.68%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 1        | 0.68%   |
| Unknown RAM Module 2GB DIMM DDR2                               | 1        | 0.68%   |
| Unknown RAM Module 2GB DIMM 400MT/s                            | 1        | 0.68%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 1        | 0.68%   |
| Unknown RAM Module 2GB DIMM 1066MT/s                           | 1        | 0.68%   |
| Unknown RAM Module 16GB DIMM DDR4 2133MT/s                     | 1        | 0.68%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1        | 0.68%   |
| TIMETEC RAM SD4-2400 8GB SODIMM DDR4 2400MT/s                  | 1        | 0.68%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s            | 1        | 0.68%   |
| Team RAM TEAMGROUP-UD4-2400 16GB DIMM DDR4 2400MT/s            | 1        | 0.68%   |
| SK Hynix RAM Module 4GB FB-DIMM DDR2 667MT/s                   | 1        | 0.68%   |
| SK Hynix RAM Module 4GB DIMM DDR3 1333MT/s                     | 1        | 0.68%   |
| SK Hynix RAM Module 4GB DIMM DDR3 1066MT/s                     | 1        | 0.68%   |
| SK Hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s           | 1        | 0.68%   |
| SK Hynix RAM HMT451U6AFR8C-PB 4096MB DIMM DDR3 1600MT/s        | 1        | 0.68%   |
| SK Hynix RAM HMT41GU6BFR8C-PB 8GB DIMM DDR3 1600MT/s           | 1        | 0.68%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s        | 1        | 0.68%   |
| SK Hynix RAM HMT125U6BFR8C-H9 2GB DIMM 1333MT/s                | 1        | 0.68%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s         | 1        | 0.68%   |
| SK Hynix RAM HMA84GR7MFR4N-UH 32GB RIMM DDR4 2400MT/s          | 1        | 0.68%   |
| SK Hynix RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2666MT/s           | 1        | 0.68%   |
| SK Hynix RAM HMA81GU6CJR8N-VK 8GB DIMM DDR4 2667MT/s           | 1        | 0.68%   |
| SK Hynix RAM HMA81GU6CJR8N-VK 8GB DIMM DDR4 2666MT/s           | 1        | 0.68%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s                      | 1        | 0.68%   |
| Samsung RAM Module 1GB DIMM DDR3 1333MT/s                      | 1        | 0.68%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 1        | 0.68%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s       | 1        | 0.68%   |
| Samsung RAM M393AAG40M32-CAE 128GB DIMM DDR4 3200MT/s          | 1        | 0.68%   |
| Samsung RAM M378B5773CH0-CK0 2GB DIMM DDR3 1600MT/s            | 1        | 0.68%   |
| Samsung RAM M378B5673EH1-CH9 2048MB DIMM DDR3 1333MT/s         | 1        | 0.68%   |
| Samsung RAM M378B5673DZ1-CF8 2GB DIMM 1066MT/s                 | 1        | 0.68%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s            | 1        | 0.68%   |
| Samsung RAM M378A5143DB0-CPB 4GB DIMM DDR4 2400MT/s            | 1        | 0.68%   |
| Samsung RAM M378A4G43AB2-CWE 32GB DIMM DDR4 3200MT/s           | 1        | 0.68%   |
| Samsung RAM M378A1G43EB1-CPB 8GB DIMM DDR4 2133MT/s            | 1        | 0.68%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s        | 1        | 0.68%   |
| PNY RAM 16GF2X08QFHH36-135-K 16GB DIMM DDR4 3200MT/s           | 1        | 0.68%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s                 | 1        | 0.68%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3200MT/s             | 1        | 0.68%   |
| Patriot RAM 1600EL Series 4GB DIMM DDR3 1600MT/s               | 1        | 0.68%   |
| Micron RAM 8JTF25664AZ-1G4D1 2GB DIMM DDR3 1333MT/s            | 1        | 0.68%   |
| Micron RAM 8ATF2G64AZ-3G2E1 16384MB DIMM DDR4 3200MT/s         | 1        | 0.68%   |
| Micron RAM 8ATF1G64AZ-2G6E1 8GB DIMM DDR4 2667MT/s             | 1        | 0.68%   |
| Micron RAM 38ADF2G72AZ-2G6E1 16GB DIMM DDR4 2133MT/s           | 1        | 0.68%   |
| Micron RAM 36JSF2G72PZ-1G9E1 16GB DIMM DDR3 1866MT/s           | 1        | 0.68%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 71       | 58.68%  |
| DDR3    | 34       | 28.1%   |
| Unknown | 7        | 5.79%   |
| SDRAM   | 4        | 3.31%   |
| DDR2    | 3        | 2.48%   |
| LPDDR4  | 2        | 1.65%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 107      | 89.17%  |
| SODIMM  | 11       | 9.17%   |
| RIMM    | 1        | 0.83%   |
| FB-DIMM | 1        | 0.83%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size   | Desktops | Percent |
|--------|----------|---------|
| 8192   | 47       | 35.88%  |
| 16384  | 33       | 25.19%  |
| 4096   | 32       | 24.43%  |
| 2048   | 10       | 7.63%   |
| 32768  | 7        | 5.34%   |
| 131072 | 1        | 0.76%   |
| 1024   | 1        | 0.76%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 21       | 16.15%  |
| 3200    | 19       | 14.62%  |
| 3600    | 13       | 10%     |
| 1333    | 12       | 9.23%   |
| 2667    | 11       | 8.46%   |
| 2400    | 9        | 6.92%   |
| 2133    | 9        | 6.92%   |
| 3466    | 6        | 4.62%   |
| 1867    | 5        | 3.85%   |
| 2666    | 4        | 3.08%   |
| 3000    | 3        | 2.31%   |
| 1066    | 3        | 2.31%   |
| 2933    | 2        | 1.54%   |
| Unknown | 2        | 1.54%   |
| 4600    | 1        | 0.77%   |
| 4000    | 1        | 0.77%   |
| 3666    | 1        | 0.77%   |
| 3533    | 1        | 0.77%   |
| 3467    | 1        | 0.77%   |
| 3400    | 1        | 0.77%   |
| 1866    | 1        | 0.77%   |
| 1800    | 1        | 0.77%   |
| 800     | 1        | 0.77%   |
| 667     | 1        | 0.77%   |
| 400     | 1        | 0.77%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 4        | 33.33%  |
| Samsung Electronics   | 3        | 25%     |
| Canon                 | 2        | 16.67%  |
| Brother Industries    | 2        | 16.67%  |
| Lexmark International | 1        | 8.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Samsung SCX-4600 Series              | 1        | 7.69%   |
| Samsung ML-216x Series Laser Printer | 1        | 7.69%   |
| Samsung Composite Device             | 1        | 7.69%   |
| Lexmark International B2442dw        | 1        | 7.69%   |
| HP OfficeJet 8700                    | 1        | 7.69%   |
| HP OfficeJet 5500 series             | 1        | 7.69%   |
| HP OfficeJet 3830 series             | 1        | 7.69%   |
| HP DeskJet 1110 series               | 1        | 7.69%   |
| Canon MF632C/634C                    | 1        | 7.69%   |
| Canon MF4320-4350                    | 1        | 7.69%   |
| Canon iR2004/2204 UFRII LT           | 1        | 7.69%   |
| Brother HL-1440 Laser Printer        | 1        | 7.69%   |
| Brother HL-1200 series               | 1        | 7.69%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 3        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LiDE 220 | 1        | 33.33%  |
| Canon CanoScan LiDE 200 | 1        | 33.33%  |
| Canon CanoScan LiDE 100 | 1        | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 32       | 43.24%  |
| Sunplus Innovation Technology | 7        | 9.46%   |
| Microdia                      | 5        | 6.76%   |
| Microsoft                     | 3        | 4.05%   |
| Generalplus Technology        | 3        | 4.05%   |
| Apple                         | 3        | 4.05%   |
| Realtek Semiconductor         | 2        | 2.7%    |
| Razer USA                     | 2        | 2.7%    |
| Chicony Electronics           | 2        | 2.7%    |
| Z-Star Microelectronics       | 1        | 1.35%   |
| WaveRider Communications      | 1        | 1.35%   |
| Trust                         | 1        | 1.35%   |
| Sony                          | 1        | 1.35%   |
| Samsung Electronics           | 1        | 1.35%   |
| Pixart Imaging                | 1        | 1.35%   |
| MacroSilicon                  | 1        | 1.35%   |
| Jieli Technology              | 1        | 1.35%   |
| Hewlett-Packard               | 1        | 1.35%   |
| HD USB Camera                 | 1        | 1.35%   |
| Guillemot                     | 1        | 1.35%   |
| Google                        | 1        | 1.35%   |
| GEMBIRD                       | 1        | 1.35%   |
| Arkmicro Technologies         | 1        | 1.35%   |
| 2M UVC CAMERA                 | 1        | 1.35%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                       | 10       | 13.33%  |
| Logitech Webcam C270                              | 5        | 6.67%   |
| Sunplus HK 1080P K20Pro                           | 4        | 5.33%   |
| Logitech C922 Pro Stream Webcam                   | 4        | 5.33%   |
| Microsoft LifeCam HD-3000                         | 2        | 2.67%   |
| Logitech Webcam C170                              | 2        | 2.67%   |
| Logitech C920 PRO HD Webcam                       | 2        | 2.67%   |
| Generalplus CAMERA - UVC                          | 2        | 2.67%   |
| Apple iPhone 5/5C/5S/6/SE                         | 2        | 2.67%   |
| Z-Star Venus USB2.0 Camera                        | 1        | 1.33%   |
| WaveRider USB 2.0 Camera                          | 1        | 1.33%   |
| Trust USB Camera                                  | 1        | 1.33%   |
| Sunplus USB camera                                | 1        | 1.33%   |
| Sunplus Canyon CNS-CWC5 Webcam                    | 1        | 1.33%   |
| Sunplus Canyon CNS CWC5 Webcam                    | 1        | 1.33%   |
| Sony CEVCECM                                      | 1        | 1.33%   |
| Samsung Galaxy A5 (MTP)                           | 1        | 1.33%   |
| Realtek WEB CAMERA M9 Pro                         | 1        | 1.33%   |
| Realtek Full HD webcam                            | 1        | 1.33%   |
| Razer USA Razer Ripsaw HD - Game Capture Card     | 1        | 1.33%   |
| Razer USA Gaming Webcam [Kiyo]                    | 1        | 1.33%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro              | 1        | 1.33%   |
| Microsoft LifeCam Cinema                          | 1        | 1.33%   |
| Microdia Webcam Vitade AF                         | 1        | 1.33%   |
| Microdia USB Camera                               | 1        | 1.33%   |
| Microdia USB 2.0 Camera                           | 1        | 1.33%   |
| Microdia Sonix USB 2.0 Camera                     | 1        | 1.33%   |
| Microdia Integrated Camera                        | 1        | 1.33%   |
| MacroSilicon USB Video                            | 1        | 1.33%   |
| Logitech Webcam C925e                             | 1        | 1.33%   |
| Logitech Webcam C210                              | 1        | 1.33%   |
| Logitech StreamCam                                | 1        | 1.33%   |
| Logitech HD Webcam C910                           | 1        | 1.33%   |
| Logitech HD Webcam C525                           | 1        | 1.33%   |
| Logitech HD Webcam C510                           | 1        | 1.33%   |
| Logitech C930c                                    | 1        | 1.33%   |
| Logitech BRIO 4K Stream Edition                   | 1        | 1.33%   |
| Logitech B525 HD Webcam                           | 1        | 1.33%   |
| Jieli USB PHY 2.0                                 | 1        | 1.33%   |
| HP Webcam                                         | 1        | 1.33%   |
| HD USB Camera HD USB Camera                       | 1        | 1.33%   |
| HD USB Camera                                     | 1        | 1.33%   |
| Guillemot Hercules HD Twist                       | 1        | 1.33%   |
| Google Nexus/Pixel Device (MTP + debug)           | 1        | 1.33%   |
| Generalplus WEB CAM                               | 1        | 1.33%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 1        | 1.33%   |
| Chicony Integrated Camera                         | 1        | 1.33%   |
| Chicony HP High Definition 1MP Webcam             | 1        | 1.33%   |
| Arkmicro Webcam Carrefour                         | 1        | 1.33%   |
| Apple iSight in LED Cinema Display                | 1        | 1.33%   |
| 2M UVC CAMERA Web Camera                          | 1        | 1.33%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Elan Microelectronics | 1        | 50%     |
| Dell                  | 1        | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Elan fingerprint sensor [FeinTech FPS00200]    | 1        | 50%     |
| Dell MS819 Wired Mouse With Fingerprint Reader | 1        | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Realtek Semiconductor Smart Card Reader Interface | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 243      | 80.2%   |
| 1     | 51       | 16.83%  |
| 2     | 6        | 1.98%   |
| 3     | 2        | 0.66%   |
| 5     | 1        | 0.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 26       | 38.81%  |
| Net/wireless             | 14       | 20.9%   |
| Unassigned class         | 10       | 14.93%  |
| Sound                    | 5        | 7.46%   |
| Communication controller | 3        | 4.48%   |
| Bluetooth                | 2        | 2.99%   |
| Storage/raid             | 1        | 1.49%   |
| Net/ethernet             | 1        | 1.49%   |
| Multimedia controller    | 1        | 1.49%   |
| Fingerprint reader       | 1        | 1.49%   |
| Chipcard                 | 1        | 1.49%   |
| Card reader              | 1        | 1.49%   |
| Camera                   | 1        | 1.49%   |

