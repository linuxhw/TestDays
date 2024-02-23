Linux in Romania - Tested Hardware & Statistics (Desktops)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Romania.

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

Total: 917

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | X670 AORUS ELITE AX         | [f0bd42b414](https://linux-hardware.org/?probe=f0bd42b414) | Feb 01, 2024 |
| ASUSTek       | B85M-K                      | [3058093889](https://linux-hardware.org/?probe=3058093889) | Jan 31, 2024 |
| HP            | 1495                        | [a2017adb28](https://linux-hardware.org/?probe=a2017adb28) | Jan 30, 2024 |
| Gateway       | DS10G                       | [869339de12](https://linux-hardware.org/?probe=869339de12) | Jan 28, 2024 |
| ASUSTek       | PRIME B550M-A               | [0937d9ebea](https://linux-hardware.org/?probe=0937d9ebea) | Jan 27, 2024 |
| Alienware     | 07W25T A01                  | [538d2e2b5f](https://linux-hardware.org/?probe=538d2e2b5f) | Jan 24, 2024 |
| ASUSTek       | ROG Rampage VI EXTREME E... | [299dd0311b](https://linux-hardware.org/?probe=299dd0311b) | Jan 24, 2024 |
| Alienware     | 07W25T A01                  | [2a7a6fd405](https://linux-hardware.org/?probe=2a7a6fd405) | Jan 22, 2024 |
| AZW           | GTR V21                     | [dbc8e08754](https://linux-hardware.org/?probe=dbc8e08754) | Jan 21, 2024 |
| Gigabyte      | 945GZM-S2                   | [41c285445b](https://linux-hardware.org/?probe=41c285445b) | Jan 21, 2024 |
| ASUSTek       | ProArt B550-CREATOR         | [97f56eac35](https://linux-hardware.org/?probe=97f56eac35) | Jan 19, 2024 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [f830d5e5f7](https://linux-hardware.org/?probe=f830d5e5f7) | Jan 18, 2024 |
| ASRock        | X470 Taichi                 | [85ada6019c](https://linux-hardware.org/?probe=85ada6019c) | Jan 15, 2024 |
| ASUSTek       | Pro WS X570-ACE             | [268e37f04e](https://linux-hardware.org/?probe=268e37f04e) | Jan 14, 2024 |
| Lenovo        | SHARKBAY NOK                | [1ece67bdd1](https://linux-hardware.org/?probe=1ece67bdd1) | Jan 12, 2024 |
| ASUSTek       | G10DK                       | [7339bf1ed8](https://linux-hardware.org/?probe=7339bf1ed8) | Jan 09, 2024 |
| Gigabyte      | 945GZM-S2                   | [931f2e4a0e](https://linux-hardware.org/?probe=931f2e4a0e) | Jan 08, 2024 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [1db7814b85](https://linux-hardware.org/?probe=1db7814b85) | Jan 07, 2024 |
| Gigabyte      | GA-78LMT-USB3 R2            | [d99098989d](https://linux-hardware.org/?probe=d99098989d) | Jan 03, 2024 |
| Gigabyte      | MH610AT-SI                  | [1b75d28eb3](https://linux-hardware.org/?probe=1b75d28eb3) | Jan 03, 2024 |
| Fujitsu       | D3501-A1 S26361-D3501-A1    | [9711c69823](https://linux-hardware.org/?probe=9711c69823) | Jan 02, 2024 |
| ASUSTek       | Z87-DELUXE                  | [018238aa79](https://linux-hardware.org/?probe=018238aa79) | Jan 01, 2024 |
| ASUSTek       | PRIME A320M-K               | [e260b20e5d](https://linux-hardware.org/?probe=e260b20e5d) | Dec 28, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [aa11af3235](https://linux-hardware.org/?probe=aa11af3235) | Dec 20, 2023 |
| MSI           | B85-G43                     | [2c855d2376](https://linux-hardware.org/?probe=2c855d2376) | Dec 19, 2023 |
| MSI           | MAG B550M MORTAR            | [6d81343411](https://linux-hardware.org/?probe=6d81343411) | Dec 18, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [f93e198dd4](https://linux-hardware.org/?probe=f93e198dd4) | Dec 18, 2023 |
| Fujitsu       | D3501-A1 S26361-D3501-A1    | [47747d42ef](https://linux-hardware.org/?probe=47747d42ef) | Dec 17, 2023 |
| ASUSTek       | Z170-A                      | [9c68457da9](https://linux-hardware.org/?probe=9c68457da9) | Dec 16, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [230f41f6b5](https://linux-hardware.org/?probe=230f41f6b5) | Dec 12, 2023 |
| Gigabyte      | P55-UD3                     | [4c20f6a826](https://linux-hardware.org/?probe=4c20f6a826) | Dec 10, 2023 |
| Dell          | 0GM819                      | [5c9ffb0977](https://linux-hardware.org/?probe=5c9ffb0977) | Dec 07, 2023 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [5f96473345](https://linux-hardware.org/?probe=5f96473345) | Dec 07, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [93675534e1](https://linux-hardware.org/?probe=93675534e1) | Dec 05, 2023 |
| HP            | 8299                        | [fb5b226159](https://linux-hardware.org/?probe=fb5b226159) | Dec 02, 2023 |
| HP            | 843B                        | [5a69492f49](https://linux-hardware.org/?probe=5a69492f49) | Nov 30, 2023 |
| Dell          | 0YP806 A01                  | [078d014e70](https://linux-hardware.org/?probe=078d014e70) | Nov 26, 2023 |
| ASUSTek       | PRIME Z490-P                | [6dcba67a12](https://linux-hardware.org/?probe=6dcba67a12) | Nov 26, 2023 |
| Gigabyte      | X99-UD4-CF                  | [d71110004d](https://linux-hardware.org/?probe=d71110004d) | Nov 23, 2023 |
| MSI           | X370 XPOWER GAMING TITAN... | [4cb5f6eae9](https://linux-hardware.org/?probe=4cb5f6eae9) | Nov 17, 2023 |
| MSI           | B550M-A PRO                 | [753bf22a5f](https://linux-hardware.org/?probe=753bf22a5f) | Nov 17, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [391e71ffae](https://linux-hardware.org/?probe=391e71ffae) | Nov 17, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [adaf0ff475](https://linux-hardware.org/?probe=adaf0ff475) | Nov 15, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | [b7788fefa0](https://linux-hardware.org/?probe=b7788fefa0) | Nov 13, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | [de08a9140e](https://linux-hardware.org/?probe=de08a9140e) | Nov 12, 2023 |
| ASUSTek       | PRIME Q270M-C               | [0fcd993247](https://linux-hardware.org/?probe=0fcd993247) | Nov 10, 2023 |
| MSI           | X299 RAIDER                 | [3f714787ff](https://linux-hardware.org/?probe=3f714787ff) | Nov 09, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2            | [0d04acd22d](https://linux-hardware.org/?probe=0d04acd22d) | Nov 07, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2            | [982bf3ea4c](https://linux-hardware.org/?probe=982bf3ea4c) | Nov 07, 2023 |
| ASUSTek       | P30AD                       | [63322c386f](https://linux-hardware.org/?probe=63322c386f) | Nov 05, 2023 |
| ASUSTek       | PRIME Z490-P                | [f8a30d78d3](https://linux-hardware.org/?probe=f8a30d78d3) | Nov 04, 2023 |
| ASUSTek       | Z97M-PLUS                   | [b0d77e36b1](https://linux-hardware.org/?probe=b0d77e36b1) | Nov 03, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2            | [0af35bd53b](https://linux-hardware.org/?probe=0af35bd53b) | Nov 02, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2            | [32a001fb07](https://linux-hardware.org/?probe=32a001fb07) | Nov 02, 2023 |
| ASUSTek       | P8H67-M EVO                 | [64a6524677](https://linux-hardware.org/?probe=64a6524677) | Oct 31, 2023 |
| Intel         | X99                         | [426c412f62](https://linux-hardware.org/?probe=426c412f62) | Oct 30, 2023 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [4d9e5a7157](https://linux-hardware.org/?probe=4d9e5a7157) | Oct 30, 2023 |
| ASUSTek       | P8H67-M EVO                 | [a4bed1729d](https://linux-hardware.org/?probe=a4bed1729d) | Oct 28, 2023 |
| Intel         | DX79TO AAG28805-401         | [75e8f73b6a](https://linux-hardware.org/?probe=75e8f73b6a) | Oct 25, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [e622e81e16](https://linux-hardware.org/?probe=e622e81e16) | Oct 24, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [a7a49e3d3f](https://linux-hardware.org/?probe=a7a49e3d3f) | Oct 23, 2023 |
| HP            | 3397                        | [d826d02943](https://linux-hardware.org/?probe=d826d02943) | Oct 20, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [de8a8232ba](https://linux-hardware.org/?probe=de8a8232ba) | Oct 19, 2023 |
| ASRock        | X670E PG Lightning          | [d2e0e9fc07](https://linux-hardware.org/?probe=d2e0e9fc07) | Oct 14, 2023 |
| Gigabyte      | B650 GAMING X AX            | [551ff39482](https://linux-hardware.org/?probe=551ff39482) | Oct 14, 2023 |
| HP            | 8437                        | [ac8d6773a3](https://linux-hardware.org/?probe=ac8d6773a3) | Oct 11, 2023 |
| HP            | 0A58h                       | [f55b84ff65](https://linux-hardware.org/?probe=f55b84ff65) | Oct 07, 2023 |
| ASUSTek       | PRIME B550M-A               | [5324f47bcf](https://linux-hardware.org/?probe=5324f47bcf) | Oct 07, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [96c62ad87e](https://linux-hardware.org/?probe=96c62ad87e) | Oct 03, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | [9a749a1c41](https://linux-hardware.org/?probe=9a749a1c41) | Sep 30, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | [452cd2622a](https://linux-hardware.org/?probe=452cd2622a) | Sep 30, 2023 |
| WesternDig... | BBC 0001                    | [b31e10d01b](https://linux-hardware.org/?probe=b31e10d01b) | Sep 29, 2023 |
| WesternDig... | BBC 0001                    | [ba340393f7](https://linux-hardware.org/?probe=ba340393f7) | Sep 29, 2023 |
| HP            | 1496                        | [3867e7af58](https://linux-hardware.org/?probe=3867e7af58) | Sep 28, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [7ab6fc6901](https://linux-hardware.org/?probe=7ab6fc6901) | Sep 27, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [d59518d612](https://linux-hardware.org/?probe=d59518d612) | Sep 25, 2023 |
| ASUSTek       | B150M-C D3                  | [179a66ec43](https://linux-hardware.org/?probe=179a66ec43) | Sep 19, 2023 |
| ASUSTek       | H81M-R                      | [6ed76f72d7](https://linux-hardware.org/?probe=6ed76f72d7) | Sep 19, 2023 |
| HP            | 158B                        | [f8385c7d22](https://linux-hardware.org/?probe=f8385c7d22) | Sep 18, 2023 |
| ASRock        | B550 Phantom Gaming 4       | [afbaf99497](https://linux-hardware.org/?probe=afbaf99497) | Sep 16, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [effa0104c0](https://linux-hardware.org/?probe=effa0104c0) | Sep 16, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [72ec01815f](https://linux-hardware.org/?probe=72ec01815f) | Sep 16, 2023 |
| HP            | 158B                        | [986f0c6ba1](https://linux-hardware.org/?probe=986f0c6ba1) | Sep 15, 2023 |
| HP            | 339A                        | [1b8a467d98](https://linux-hardware.org/?probe=1b8a467d98) | Sep 13, 2023 |
| Lenovo        | 3717 NO DPK                 | [13870a17b4](https://linux-hardware.org/?probe=13870a17b4) | Sep 13, 2023 |
| ASUSTek       | H110M-K                     | [ba05e7b3a7](https://linux-hardware.org/?probe=ba05e7b3a7) | Sep 12, 2023 |
| ASUSTek       | PRIME A320M-K               | [1275709f08](https://linux-hardware.org/?probe=1275709f08) | Sep 09, 2023 |
| Acer          | EQ45LM                      | [015ea66c32](https://linux-hardware.org/?probe=015ea66c32) | Sep 09, 2023 |
| Acer          | EQ45LM                      | [22af76a0b6](https://linux-hardware.org/?probe=22af76a0b6) | Sep 06, 2023 |
| ASUSTek       | PRIME A320M-K               | [7263435dde](https://linux-hardware.org/?probe=7263435dde) | Sep 05, 2023 |
| Gigabyte      | B550M DS3H                  | [90b8d2cb66](https://linux-hardware.org/?probe=90b8d2cb66) | Aug 28, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [8169effdbe](https://linux-hardware.org/?probe=8169effdbe) | Aug 27, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [dd4626de1b](https://linux-hardware.org/?probe=dd4626de1b) | Aug 27, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [78a62eeefe](https://linux-hardware.org/?probe=78a62eeefe) | Aug 26, 2023 |
| Acer          | EQ45LM                      | [aa8ea529f7](https://linux-hardware.org/?probe=aa8ea529f7) | Aug 24, 2023 |
| ASUSTek       | PRIME H270-PRO              | [05eae6c877](https://linux-hardware.org/?probe=05eae6c877) | Aug 22, 2023 |
| ASRock        | 890GX Pro3                  | [c36b43c52a](https://linux-hardware.org/?probe=c36b43c52a) | Aug 21, 2023 |
| ASRock        | B250M-HDV                   | [d7805c8232](https://linux-hardware.org/?probe=d7805c8232) | Aug 19, 2023 |
| Gigabyte      | Z390 AORUS PRO-CF           | [8478931432](https://linux-hardware.org/?probe=8478931432) | Aug 17, 2023 |
| Gigabyte      | Z270M-D3H-CF                | [74d96ec17a](https://linux-hardware.org/?probe=74d96ec17a) | Aug 15, 2023 |
| Gigabyte      | Z270M-D3H-CF                | [8e4f3bf14e](https://linux-hardware.org/?probe=8e4f3bf14e) | Aug 15, 2023 |
| Gigabyte      | X670E AORUS MASTER          | [f0f6b13bf3](https://linux-hardware.org/?probe=f0f6b13bf3) | Aug 13, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [3b5e9f52a2](https://linux-hardware.org/?probe=3b5e9f52a2) | Aug 05, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [66d6565a06](https://linux-hardware.org/?probe=66d6565a06) | Aug 05, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [70aa79986f](https://linux-hardware.org/?probe=70aa79986f) | Aug 05, 2023 |
| Acer          | EQ45LM                      | [b9be16315e](https://linux-hardware.org/?probe=b9be16315e) | Aug 05, 2023 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [cc0ea700cc](https://linux-hardware.org/?probe=cc0ea700cc) | Aug 04, 2023 |
| MSI           | Z270 TOMAHAWK OPT BOOST     | [9cc0db1a3d](https://linux-hardware.org/?probe=9cc0db1a3d) | Jul 29, 2023 |
| Unknown       | Unknown                     | [9f04167710](https://linux-hardware.org/?probe=9f04167710) | Jul 27, 2023 |
| Acer          | EQ45LM                      | [29e2f587cd](https://linux-hardware.org/?probe=29e2f587cd) | Jul 26, 2023 |
| Acer          | EQ45LM                      | [37f6c76c11](https://linux-hardware.org/?probe=37f6c76c11) | Jul 25, 2023 |
| MSI           | Z270 TOMAHAWK OPT BOOST     | [6417b2e0e3](https://linux-hardware.org/?probe=6417b2e0e3) | Jul 24, 2023 |
| ASUSTek       | PRIME A320M-K               | [d64ea4b9cd](https://linux-hardware.org/?probe=d64ea4b9cd) | Jul 15, 2023 |
| ASRock        | B250M-HDV                   | [85d4919b9c](https://linux-hardware.org/?probe=85d4919b9c) | Jul 12, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [0ae95a7985](https://linux-hardware.org/?probe=0ae95a7985) | Jul 10, 2023 |
| Acer          | EQ45LM                      | [3cafc83ffb](https://linux-hardware.org/?probe=3cafc83ffb) | Jul 08, 2023 |
| ASUSTek       | P5KC                        | [952e97925b](https://linux-hardware.org/?probe=952e97925b) | Jul 08, 2023 |
| ASUSTek       | V-P7H55E                    | [79d631563a](https://linux-hardware.org/?probe=79d631563a) | Jul 01, 2023 |
| Acer          | EQ45LM                      | [30781f8f1b](https://linux-hardware.org/?probe=30781f8f1b) | Jun 25, 2023 |
| ASUSTek       | Q87M-E                      | [f0ab10725e](https://linux-hardware.org/?probe=f0ab10725e) | Jun 23, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [4622902df7](https://linux-hardware.org/?probe=4622902df7) | Jun 17, 2023 |
| Acer          | Veriton N4640G              | [f1f16d8add](https://linux-hardware.org/?probe=f1f16d8add) | Jun 16, 2023 |
| HP            | 81B3                        | [9ba98d3c27](https://linux-hardware.org/?probe=9ba98d3c27) | Jun 14, 2023 |
| Gigabyte      | 970A-D3                     | [1c62ecb77d](https://linux-hardware.org/?probe=1c62ecb77d) | Jun 14, 2023 |
| Gigabyte      | A520M DS3H                  | [0f5b161a60](https://linux-hardware.org/?probe=0f5b161a60) | Jun 13, 2023 |
| Dell          | 0XCR8D A02                  | [d567ae409c](https://linux-hardware.org/?probe=d567ae409c) | Jun 12, 2023 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [b6a626c812](https://linux-hardware.org/?probe=b6a626c812) | Jun 10, 2023 |
| Gigabyte      | B560M H                     | [fadb7a6aa8](https://linux-hardware.org/?probe=fadb7a6aa8) | Jun 10, 2023 |
| Acer          | EQ45LM                      | [73f7a3078f](https://linux-hardware.org/?probe=73f7a3078f) | Jun 06, 2023 |
| ASRock        | X670E PG Lightning          | [7cd25ddbda](https://linux-hardware.org/?probe=7cd25ddbda) | Jun 04, 2023 |
| MSI           | X370 XPOWER GAMING TITAN... | [3ecf79af69](https://linux-hardware.org/?probe=3ecf79af69) | May 29, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [acee298918](https://linux-hardware.org/?probe=acee298918) | May 26, 2023 |
| Acer          | EQ45LM                      | [a49c4c8438](https://linux-hardware.org/?probe=a49c4c8438) | May 26, 2023 |
| HP            | 805D                        | [2ac4992bcd](https://linux-hardware.org/?probe=2ac4992bcd) | May 22, 2023 |
| Gigabyte      | B450M S2H                   | [5309c41b94](https://linux-hardware.org/?probe=5309c41b94) | May 21, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [b8ed6a8b77](https://linux-hardware.org/?probe=b8ed6a8b77) | May 18, 2023 |
| Dell          | 09KPNV A01                  | [cbd408a1a6](https://linux-hardware.org/?probe=cbd408a1a6) | May 13, 2023 |
| Gigabyte      | Z97X-SLI-CF                 | [5921d78ceb](https://linux-hardware.org/?probe=5921d78ceb) | May 10, 2023 |
| Dell          | 0YXT71 A03                  | [b8281f77a3](https://linux-hardware.org/?probe=b8281f77a3) | May 07, 2023 |
| Gigabyte      | Z97-D3H-CF                  | [f86e67c005](https://linux-hardware.org/?probe=f86e67c005) | May 07, 2023 |
| ASRock        | B250M-HDV                   | [d905babc43](https://linux-hardware.org/?probe=d905babc43) | May 06, 2023 |
| ASRock        | B250M-HDV                   | [bb7835495e](https://linux-hardware.org/?probe=bb7835495e) | May 06, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [862ef64565](https://linux-hardware.org/?probe=862ef64565) | May 05, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [e055c16455](https://linux-hardware.org/?probe=e055c16455) | May 03, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [2beb48be05](https://linux-hardware.org/?probe=2beb48be05) | Apr 27, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [481c5a9169](https://linux-hardware.org/?probe=481c5a9169) | Apr 23, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [1127dfa79c](https://linux-hardware.org/?probe=1127dfa79c) | Apr 21, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [c7ca0e9fd1](https://linux-hardware.org/?probe=c7ca0e9fd1) | Apr 14, 2023 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | [356ff49c7c](https://linux-hardware.org/?probe=356ff49c7c) | Apr 13, 2023 |
| HP            | 1495                        | [569a6f28f4](https://linux-hardware.org/?probe=569a6f28f4) | Apr 12, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [6b554016fe](https://linux-hardware.org/?probe=6b554016fe) | Apr 03, 2023 |
| ASUSTek       | J1900I-C                    | [0fbd47b12e](https://linux-hardware.org/?probe=0fbd47b12e) | Apr 02, 2023 |
| Gigabyte      | GA-880GM-UD2H               | [90796fbad9](https://linux-hardware.org/?probe=90796fbad9) | Mar 31, 2023 |
| HP            | 3047h                       | [c4f4f0c51d](https://linux-hardware.org/?probe=c4f4f0c51d) | Mar 28, 2023 |
| Gigabyte      | A320M-S2H-CF                | [ceb794a09f](https://linux-hardware.org/?probe=ceb794a09f) | Mar 17, 2023 |
| ASUSTek       | P9X79 WS                    | [29e03bb7ce](https://linux-hardware.org/?probe=29e03bb7ce) | Mar 17, 2023 |
| ASUSTek       | PRIME H510M-D               | [d1edfbc4b3](https://linux-hardware.org/?probe=d1edfbc4b3) | Mar 16, 2023 |
| Dell          | 042P49 A00                  | [8912f590e3](https://linux-hardware.org/?probe=8912f590e3) | Mar 14, 2023 |
| MSI           | X370 XPOWER GAMING TITAN... | [abebd8a5c2](https://linux-hardware.org/?probe=abebd8a5c2) | Mar 11, 2023 |
| Gigabyte      | B85M-D3H                    | [a3a158ccf2](https://linux-hardware.org/?probe=a3a158ccf2) | Mar 08, 2023 |
| ASUSTek       | P5KC                        | [72d0284bdd](https://linux-hardware.org/?probe=72d0284bdd) | Mar 05, 2023 |
| ASUSTek       | PRIME Z390-P                | [ab48c17484](https://linux-hardware.org/?probe=ab48c17484) | Mar 04, 2023 |
| Lenovo        | SHARKBAY NOK                | [9fba7bceb7](https://linux-hardware.org/?probe=9fba7bceb7) | Mar 03, 2023 |
| ASUSTek       | P5KC                        | [45f781ee3a](https://linux-hardware.org/?probe=45f781ee3a) | Feb 28, 2023 |
| Gigabyte      | H87-D3H-CF                  | [ea8bb4c0e4](https://linux-hardware.org/?probe=ea8bb4c0e4) | Feb 27, 2023 |
| ASUSTek       | PRIME Q270M-C               | [edf748dbbb](https://linux-hardware.org/?probe=edf748dbbb) | Feb 26, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [fad109dc98](https://linux-hardware.org/?probe=fad109dc98) | Feb 25, 2023 |
| ASRock        | B460 Steel Legend           | [e8963c4e59](https://linux-hardware.org/?probe=e8963c4e59) | Feb 21, 2023 |
| ASRock        | B250M-HDV                   | [f36e84dcaf](https://linux-hardware.org/?probe=f36e84dcaf) | Feb 16, 2023 |
| Gigabyte      | B450M DS3H-CF               | [684445aeab](https://linux-hardware.org/?probe=684445aeab) | Feb 16, 2023 |
| HP            | 0AA8h                       | [e7bbc5903b](https://linux-hardware.org/?probe=e7bbc5903b) | Feb 15, 2023 |
| ASUSTek       | PRIME H410M-K               | [7cc71e6021](https://linux-hardware.org/?probe=7cc71e6021) | Feb 12, 2023 |
| Gigabyte      | H410M H V3                  | [1360d3227f](https://linux-hardware.org/?probe=1360d3227f) | Feb 10, 2023 |
| Acer          | Veriton N4630G              | [262d8ec347](https://linux-hardware.org/?probe=262d8ec347) | Feb 09, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING       | [fa2a1dba2d](https://linux-hardware.org/?probe=fa2a1dba2d) | Feb 09, 2023 |
| Lenovo        | MAHOBAY NOK                 | [a2729c9880](https://linux-hardware.org/?probe=a2729c9880) | Feb 08, 2023 |
| Gigabyte      | B660M DS3H DDR4             | [6161d6b31d](https://linux-hardware.org/?probe=6161d6b31d) | Feb 08, 2023 |
| HP            | 1494                        | [ba7c61bf23](https://linux-hardware.org/?probe=ba7c61bf23) | Feb 07, 2023 |
| HP            | 1494                        | [a582a0d6c7](https://linux-hardware.org/?probe=a582a0d6c7) | Feb 07, 2023 |
| ASRock        | 4X4-4000 Series             | [4ed27fe851](https://linux-hardware.org/?probe=4ed27fe851) | Feb 04, 2023 |
| ASRock        | B250M-HDV                   | [a2ff80e7dd](https://linux-hardware.org/?probe=a2ff80e7dd) | Feb 01, 2023 |
| Dell          | 042P49 A01                  | [2791787281](https://linux-hardware.org/?probe=2791787281) | Jan 31, 2023 |
| MSI           | H81M-P33                    | [63402c414d](https://linux-hardware.org/?probe=63402c414d) | Jan 30, 2023 |
| ASRock        | J4125M                      | [535c1b6821](https://linux-hardware.org/?probe=535c1b6821) | Jan 30, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | [da2056876e](https://linux-hardware.org/?probe=da2056876e) | Jan 29, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | [b7377ee894](https://linux-hardware.org/?probe=b7377ee894) | Jan 27, 2023 |
| Gigabyte      | B450 AORUS M                | [3e65f42529](https://linux-hardware.org/?probe=3e65f42529) | Jan 26, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [5269e78083](https://linux-hardware.org/?probe=5269e78083) | Jan 26, 2023 |
| ASRock        | B250M-HDV                   | [5b2fd24ed7](https://linux-hardware.org/?probe=5b2fd24ed7) | Jan 24, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [7f1bb5c3c3](https://linux-hardware.org/?probe=7f1bb5c3c3) | Jan 23, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [f74d2ca84b](https://linux-hardware.org/?probe=f74d2ca84b) | Jan 23, 2023 |
| ASUSTek       | PRIME H270-PRO              | [ac4fa9fd5f](https://linux-hardware.org/?probe=ac4fa9fd5f) | Jan 23, 2023 |
| ASRock        | N68-GE3 UCC                 | [cd23d81f65](https://linux-hardware.org/?probe=cd23d81f65) | Jan 22, 2023 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | [e3d0558aee](https://linux-hardware.org/?probe=e3d0558aee) | Jan 19, 2023 |
| MSI           | 970A-G43                    | [086e04b65f](https://linux-hardware.org/?probe=086e04b65f) | Jan 17, 2023 |
| Dell          | 06D7TR A00                  | [bf8115e391](https://linux-hardware.org/?probe=bf8115e391) | Jan 15, 2023 |
| Gigabyte      | B450M DS3H-CF               | [25cf332260](https://linux-hardware.org/?probe=25cf332260) | Jan 15, 2023 |
| Gigabyte      | B450M DS3H-CF               | [3f12fad87c](https://linux-hardware.org/?probe=3f12fad87c) | Jan 15, 2023 |
| Gigabyte      | A320M-S2H-CF                | [6584beb723](https://linux-hardware.org/?probe=6584beb723) | Jan 15, 2023 |
| Gigabyte      | H67M-D2-B3                  | [6a4e71bb84](https://linux-hardware.org/?probe=6a4e71bb84) | Jan 14, 2023 |
| ASUSTek       | J1900I-C                    | [f12439ce42](https://linux-hardware.org/?probe=f12439ce42) | Jan 13, 2023 |
| HP            | 21F5                        | [141aa3faa6](https://linux-hardware.org/?probe=141aa3faa6) | Jan 12, 2023 |
| ASUSTek       | P5G41T-M LE                 | [de94c3e313](https://linux-hardware.org/?probe=de94c3e313) | Jan 12, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [34259527c2](https://linux-hardware.org/?probe=34259527c2) | Jan 07, 2023 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | [c4ae03416f](https://linux-hardware.org/?probe=c4ae03416f) | Jan 07, 2023 |
| ASUSTek       | H81M-E                      | [165bb4a9ab](https://linux-hardware.org/?probe=165bb4a9ab) | Jan 06, 2023 |
| ASRock        | FM2A88M-HD+ R3.0            | [acbd8114d2](https://linux-hardware.org/?probe=acbd8114d2) | Jan 04, 2023 |
| ASRock        | FM2A88X Extreme4+           | [3fb1b015e3](https://linux-hardware.org/?probe=3fb1b015e3) | Jan 02, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [cdb2bf4725](https://linux-hardware.org/?probe=cdb2bf4725) | Jan 02, 2023 |
| MSI           | PRO B660M-E DDR4            | [6ae9b30e34](https://linux-hardware.org/?probe=6ae9b30e34) | Jan 02, 2023 |
| Lenovo        | No DPK                      | [944f84567a](https://linux-hardware.org/?probe=944f84567a) | Dec 28, 2022 |
| ASRock        | N68-GE3 UCC                 | [57a42cabf6](https://linux-hardware.org/?probe=57a42cabf6) | Dec 27, 2022 |
| ASUSTek       | PRIME B450M-K II            | [9a6b000b23](https://linux-hardware.org/?probe=9a6b000b23) | Dec 23, 2022 |
| ASRock        | N68-GE3 UCC                 | [2892951c9c](https://linux-hardware.org/?probe=2892951c9c) | Dec 23, 2022 |
| ASRock        | N68-GE3 UCC                 | [ddc35a5b0d](https://linux-hardware.org/?probe=ddc35a5b0d) | Dec 22, 2022 |
| ASUSTek       | M2N-E                       | [d27a2a4e0f](https://linux-hardware.org/?probe=d27a2a4e0f) | Dec 20, 2022 |
| Dell          | 0VHWTR A01                  | [a5070ec279](https://linux-hardware.org/?probe=a5070ec279) | Dec 20, 2022 |
| MSI           | A320M-A PRO MAX             | [30aec905c0](https://linux-hardware.org/?probe=30aec905c0) | Dec 19, 2022 |
| ASRock        | X670E Steel Legend          | [fec86201de](https://linux-hardware.org/?probe=fec86201de) | Dec 15, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [d087536cbf](https://linux-hardware.org/?probe=d087536cbf) | Dec 14, 2022 |
| ASRock        | B250M-HDV                   | [20c4b98c2c](https://linux-hardware.org/?probe=20c4b98c2c) | Dec 14, 2022 |
| MSI           | MS-B1591                    | [33cb107fb9](https://linux-hardware.org/?probe=33cb107fb9) | Dec 13, 2022 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [d1b0bc1c03](https://linux-hardware.org/?probe=d1b0bc1c03) | Dec 12, 2022 |
| ASRock        | X300M-STX                   | [97691e3dca](https://linux-hardware.org/?probe=97691e3dca) | Dec 11, 2022 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [32e7431c24](https://linux-hardware.org/?probe=32e7431c24) | Dec 11, 2022 |
| ASUSTek       | PRIME X670E-PRO WIFI        | [a9351a042f](https://linux-hardware.org/?probe=a9351a042f) | Dec 10, 2022 |
| MSI           | X370 XPOWER GAMING TITAN... | [cb246bfc71](https://linux-hardware.org/?probe=cb246bfc71) | Dec 08, 2022 |
| MSI           | X370 XPOWER GAMING TITAN... | [1b0ddaccb8](https://linux-hardware.org/?probe=1b0ddaccb8) | Dec 08, 2022 |
| ASRock        | B250M-HDV                   | [e7495f12e4](https://linux-hardware.org/?probe=e7495f12e4) | Dec 08, 2022 |
| Gigabyte      | EP45-DS3P                   | [6844d4578b](https://linux-hardware.org/?probe=6844d4578b) | Dec 07, 2022 |
| ASRock        | N68-GE3 UCC                 | [fd65cfedda](https://linux-hardware.org/?probe=fd65cfedda) | Dec 07, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [d5ada57985](https://linux-hardware.org/?probe=d5ada57985) | Dec 03, 2022 |
| MSI           | G41M-S03                    | [763decb5d5](https://linux-hardware.org/?probe=763decb5d5) | Dec 01, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [40c84f5af9](https://linux-hardware.org/?probe=40c84f5af9) | Nov 28, 2022 |
| Dell          | 0D24M8 A00                  | [c58c83e367](https://linux-hardware.org/?probe=c58c83e367) | Nov 26, 2022 |
| Dell          | 0D24M8 A00                  | [85b508d6d3](https://linux-hardware.org/?probe=85b508d6d3) | Nov 26, 2022 |
| Gigabyte      | EP45-DS3P                   | [20015fb913](https://linux-hardware.org/?probe=20015fb913) | Nov 26, 2022 |
| Gigabyte      | TRX40 AORUS MASTER          | [0e35d31780](https://linux-hardware.org/?probe=0e35d31780) | Nov 26, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [6c797b4554](https://linux-hardware.org/?probe=6c797b4554) | Nov 23, 2022 |
| Unknown       | Unknown                     | [029cddbcd6](https://linux-hardware.org/?probe=029cddbcd6) | Nov 23, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [b8379d261b](https://linux-hardware.org/?probe=b8379d261b) | Nov 22, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [2089ec3efb](https://linux-hardware.org/?probe=2089ec3efb) | Nov 18, 2022 |
| Fujitsu Si... | D2364-A3 S26361-D2364-A3    | [62ce7f9a0b](https://linux-hardware.org/?probe=62ce7f9a0b) | Nov 18, 2022 |
| ASUSTek       | PRIME H510M-D               | [3491c5eef1](https://linux-hardware.org/?probe=3491c5eef1) | Nov 17, 2022 |
| HP            | 843B                        | [373e5cc61d](https://linux-hardware.org/?probe=373e5cc61d) | Nov 16, 2022 |
| ASRock        | B250M-HDV                   | [30916d8420](https://linux-hardware.org/?probe=30916d8420) | Nov 16, 2022 |
| ASUSTek       | PRIME X470-PRO              | [370fb87faa](https://linux-hardware.org/?probe=370fb87faa) | Nov 13, 2022 |
| MSI           | H81M-P33                    | [2ef23ed4ac](https://linux-hardware.org/?probe=2ef23ed4ac) | Nov 07, 2022 |
| Gigabyte      | B450M GAMING                | [12c49f9e36](https://linux-hardware.org/?probe=12c49f9e36) | Nov 05, 2022 |
| Gigabyte      | GA-MA770-DS3                | [f435ef302a](https://linux-hardware.org/?probe=f435ef302a) | Nov 05, 2022 |
| Gigabyte      | H410M S2H V3                | [9e8ec19352](https://linux-hardware.org/?probe=9e8ec19352) | Oct 26, 2022 |
| ASUSTek       | ROG STRIX B360-G GAMING     | [eaad7f0757](https://linux-hardware.org/?probe=eaad7f0757) | Oct 20, 2022 |
| ASRock        | B250M-HDV                   | [478ba58d34](https://linux-hardware.org/?probe=478ba58d34) | Oct 13, 2022 |
| Intel         | D54250WYK H13922-303        | [79236a7a89](https://linux-hardware.org/?probe=79236a7a89) | Oct 11, 2022 |
| Intel         | D54250WYK H13922-303        | [abc991002e](https://linux-hardware.org/?probe=abc991002e) | Oct 10, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [8694ed82a6](https://linux-hardware.org/?probe=8694ed82a6) | Oct 09, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [d4f76a4236](https://linux-hardware.org/?probe=d4f76a4236) | Oct 01, 2022 |
| ASRock        | B450M Pro4                  | [ed76eeb703](https://linux-hardware.org/?probe=ed76eeb703) | Sep 30, 2022 |
| Intel         | DQ67SW AAG12527-310         | [235930defb](https://linux-hardware.org/?probe=235930defb) | Sep 28, 2022 |
| BESSTAR Te... | UM250 V1.0                  | [aba8915769](https://linux-hardware.org/?probe=aba8915769) | Sep 19, 2022 |
| ASUSTek       | PRIME B450M-A               | [2af6edb7a0](https://linux-hardware.org/?probe=2af6edb7a0) | Sep 12, 2022 |
| Dell          | 03NVJ6 A00                  | [ef8c1a9dee](https://linux-hardware.org/?probe=ef8c1a9dee) | Sep 10, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [43311add57](https://linux-hardware.org/?probe=43311add57) | Sep 09, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [c13cd2c2ac](https://linux-hardware.org/?probe=c13cd2c2ac) | Sep 09, 2022 |
| Dell          | 09KPNV A01                  | [b5cc00787f](https://linux-hardware.org/?probe=b5cc00787f) | Sep 04, 2022 |
| Gigabyte      | B450 AORUS M                | [3ac55201b6](https://linux-hardware.org/?probe=3ac55201b6) | Sep 04, 2022 |
| Gigabyte      | TRX40 DESIGNARE             | [a2962588fa](https://linux-hardware.org/?probe=a2962588fa) | Sep 04, 2022 |
| MSI           | Z97 GAMING 7                | [c9ebe69583](https://linux-hardware.org/?probe=c9ebe69583) | Aug 30, 2022 |
| Gigabyte      | EP45-DS3P                   | [2af48f00ac](https://linux-hardware.org/?probe=2af48f00ac) | Aug 22, 2022 |
| Gigabyte      | EP45-DS3P                   | [0910ca3887](https://linux-hardware.org/?probe=0910ca3887) | Aug 22, 2022 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [5cf178d7ac](https://linux-hardware.org/?probe=5cf178d7ac) | Aug 22, 2022 |
| Gigabyte      | Z77X-UD5H                   | [5262ee60e8](https://linux-hardware.org/?probe=5262ee60e8) | Aug 14, 2022 |
| Intel         | DQ67SW AAG12527-309         | [ca6a3b3fba](https://linux-hardware.org/?probe=ca6a3b3fba) | Aug 12, 2022 |
| MSI           | A320M-A PRO MAX             | [cdee8ca864](https://linux-hardware.org/?probe=cdee8ca864) | Aug 12, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [aebe04abda](https://linux-hardware.org/?probe=aebe04abda) | Aug 11, 2022 |
| ASUSTek       | Z170 PRO GAMING             | [20a93d57e6](https://linux-hardware.org/?probe=20a93d57e6) | Aug 08, 2022 |
| MSI           | B550-A PRO                  | [94d50a1c56](https://linux-hardware.org/?probe=94d50a1c56) | Aug 08, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [1fe8a14d3b](https://linux-hardware.org/?probe=1fe8a14d3b) | Aug 06, 2022 |
| Unknown       | 1.0                         | [4394243123](https://linux-hardware.org/?probe=4394243123) | Aug 05, 2022 |
| Unknown       | 1.0                         | [545d9cf73c](https://linux-hardware.org/?probe=545d9cf73c) | Aug 04, 2022 |
| HP            | 8704                        | [eaa4bc0059](https://linux-hardware.org/?probe=eaa4bc0059) | Jul 21, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [892229b650](https://linux-hardware.org/?probe=892229b650) | Jul 21, 2022 |
| ASUSTek       | M4A79XTD EVO                | [b12edadc03](https://linux-hardware.org/?probe=b12edadc03) | Jul 13, 2022 |
| Gigabyte      | B450 AORUS M                | [6d15b85193](https://linux-hardware.org/?probe=6d15b85193) | Jul 10, 2022 |
| ASUSTek       | P5KC                        | [0ce9dd5cee](https://linux-hardware.org/?probe=0ce9dd5cee) | Jul 08, 2022 |
| ASUSTek       | Pro H510M-C                 | [f991c1fba8](https://linux-hardware.org/?probe=f991c1fba8) | Jul 07, 2022 |
| ASUSTek       | Pro H510M-C                 | [a5f338ae1a](https://linux-hardware.org/?probe=a5f338ae1a) | Jul 07, 2022 |
| Dell          | 0VHWTR A02                  | [32463f298d](https://linux-hardware.org/?probe=32463f298d) | Jul 05, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [92fe4c2ff3](https://linux-hardware.org/?probe=92fe4c2ff3) | Jul 03, 2022 |
| Gigabyte      | Z690I AORUS ULTRA           | [eeac425783](https://linux-hardware.org/?probe=eeac425783) | Jun 23, 2022 |
| HP            | 1790                        | [341a6c4c70](https://linux-hardware.org/?probe=341a6c4c70) | Jun 15, 2022 |
| Lenovo        | SHARKBAY NOK                | [4b2037715f](https://linux-hardware.org/?probe=4b2037715f) | Jun 15, 2022 |
| ASUSTek       | PRIME B450M-A               | [a144e0b75e](https://linux-hardware.org/?probe=a144e0b75e) | Jun 08, 2022 |
| ASRock        | B365M Pro4                  | [ef5b8100ce](https://linux-hardware.org/?probe=ef5b8100ce) | Jun 07, 2022 |
| Dell          | 07WP95 A02                  | [65ae31976a](https://linux-hardware.org/?probe=65ae31976a) | May 31, 2022 |
| Dell          | 096JG8 A01                  | [51aaf4adcd](https://linux-hardware.org/?probe=51aaf4adcd) | May 24, 2022 |
| Unknown       | Unknown                     | [aa6db2ed41](https://linux-hardware.org/?probe=aa6db2ed41) | May 23, 2022 |
| Foxconn       | 2ADA                        | [60579b7d68](https://linux-hardware.org/?probe=60579b7d68) | May 18, 2022 |
| ASUSTek       | P5KC                        | [bf7fdb19c8](https://linux-hardware.org/?probe=bf7fdb19c8) | May 12, 2022 |
| HP            | 0AA8h                       | [7d29587a1a](https://linux-hardware.org/?probe=7d29587a1a) | May 11, 2022 |
| Dell          | 0D6H9T A00                  | [9fe037820e](https://linux-hardware.org/?probe=9fe037820e) | May 05, 2022 |
| Dell          | 0YNVJG A01                  | [7a6aa0c236](https://linux-hardware.org/?probe=7a6aa0c236) | May 03, 2022 |
| ASRock        | B450 Pro4                   | [a8e967a378](https://linux-hardware.org/?probe=a8e967a378) | May 01, 2022 |
| Dell          | 07WP95 A02                  | [8dd4d42608](https://linux-hardware.org/?probe=8dd4d42608) | Apr 29, 2022 |
| ASUSTek       | PRIME B450M-A               | [a3a204ed56](https://linux-hardware.org/?probe=a3a204ed56) | Apr 21, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [4521315d14](https://linux-hardware.org/?probe=4521315d14) | Apr 21, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [fff2447e5a](https://linux-hardware.org/?probe=fff2447e5a) | Apr 21, 2022 |
| Gigabyte      | H61M-D2H-USB3               | [016243a675](https://linux-hardware.org/?probe=016243a675) | Apr 15, 2022 |
| Unknown       | Unknown                     | [9709ffeb9a](https://linux-hardware.org/?probe=9709ffeb9a) | Apr 14, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [59b9f6ab96](https://linux-hardware.org/?probe=59b9f6ab96) | Apr 09, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [27e9b2e124](https://linux-hardware.org/?probe=27e9b2e124) | Apr 09, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [dd2c447b48](https://linux-hardware.org/?probe=dd2c447b48) | Apr 07, 2022 |
| HP            | 0AA8h                       | [0de7915496](https://linux-hardware.org/?probe=0de7915496) | Apr 06, 2022 |
| Gigabyte      | Z690 UD AX                  | [a052a5e936](https://linux-hardware.org/?probe=a052a5e936) | Apr 03, 2022 |
| HP            | 1790                        | [9b8f0779ab](https://linux-hardware.org/?probe=9b8f0779ab) | Apr 03, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [13aa7656f3](https://linux-hardware.org/?probe=13aa7656f3) | Apr 03, 2022 |
| Unknown       | Unknown                     | [4de543bc53](https://linux-hardware.org/?probe=4de543bc53) | Apr 03, 2022 |
| Unknown       | Unknown                     | [ec51dcaf0a](https://linux-hardware.org/?probe=ec51dcaf0a) | Apr 03, 2022 |
| Gigabyte      | Z690 UD AX                  | [62982f1e80](https://linux-hardware.org/?probe=62982f1e80) | Apr 02, 2022 |
| Medion        | H81H3-EM2                   | [4c887e357d](https://linux-hardware.org/?probe=4c887e357d) | Mar 31, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [c1e113a82d](https://linux-hardware.org/?probe=c1e113a82d) | Mar 26, 2022 |
| Dell          | 0C522T A03                  | [3dc84dc8ff](https://linux-hardware.org/?probe=3dc84dc8ff) | Mar 24, 2022 |
| ASUSTek       | PRIME H410M-R               | [4bc060dc9d](https://linux-hardware.org/?probe=4bc060dc9d) | Mar 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [28303b98cc](https://linux-hardware.org/?probe=28303b98cc) | Mar 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [a339fe7a39](https://linux-hardware.org/?probe=a339fe7a39) | Mar 13, 2022 |
| Intel         | DG31PR AAD97573-300         | [509c41b106](https://linux-hardware.org/?probe=509c41b106) | Mar 13, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [e8c3922bb3](https://linux-hardware.org/?probe=e8c3922bb3) | Mar 12, 2022 |
| MSI           | B75MA-P45                   | [6034a2269a](https://linux-hardware.org/?probe=6034a2269a) | Mar 09, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [385d1914ee](https://linux-hardware.org/?probe=385d1914ee) | Mar 07, 2022 |
| Dell          | 0YXT71 A03                  | [b1ac4ae8e7](https://linux-hardware.org/?probe=b1ac4ae8e7) | Mar 05, 2022 |
| Daewoo Luc... | Solo Top                    | [7f7b20688f](https://linux-hardware.org/?probe=7f7b20688f) | Mar 03, 2022 |
| Dell          | 0XHGV1 A02                  | [768657efd5](https://linux-hardware.org/?probe=768657efd5) | Mar 03, 2022 |
| Gigabyte      | GA-790XTA-UD4               | [f455a7b7a5](https://linux-hardware.org/?probe=f455a7b7a5) | Feb 28, 2022 |
| Gigabyte      | GA-790XTA-UD4               | [74461b0659](https://linux-hardware.org/?probe=74461b0659) | Feb 27, 2022 |
| MSI           | MS-7392                     | [c64a5b4adf](https://linux-hardware.org/?probe=c64a5b4adf) | Feb 20, 2022 |
| MSI           | MS-7392                     | [308ed6c0c6](https://linux-hardware.org/?probe=308ed6c0c6) | Feb 20, 2022 |
| Gigabyte      | H77-DS3H                    | [417a759484](https://linux-hardware.org/?probe=417a759484) | Feb 18, 2022 |
| Gigabyte      | B365M H                     | [fec0662c03](https://linux-hardware.org/?probe=fec0662c03) | Feb 16, 2022 |
| Gigabyte      | GA-790XTA-UD4               | [b06467c5df](https://linux-hardware.org/?probe=b06467c5df) | Feb 16, 2022 |
| Gigabyte      | H81M-HD3                    | [13989d56ec](https://linux-hardware.org/?probe=13989d56ec) | Feb 14, 2022 |
| Gigabyte      | B450M DS3H-CF               | [e48e07387e](https://linux-hardware.org/?probe=e48e07387e) | Feb 13, 2022 |
| HP            | 09F8h                       | [d887fef9ff](https://linux-hardware.org/?probe=d887fef9ff) | Feb 13, 2022 |
| ASUSTek       | P8H61-M LX                  | [a016adec7d](https://linux-hardware.org/?probe=a016adec7d) | Feb 12, 2022 |
| HP            | 339A                        | [a4eac4d7b8](https://linux-hardware.org/?probe=a4eac4d7b8) | Feb 11, 2022 |
| Lenovo        | NOK                         | [f860aaeaf3](https://linux-hardware.org/?probe=f860aaeaf3) | Feb 11, 2022 |
| HP            | 0AA8h                       | [a78b5c3460](https://linux-hardware.org/?probe=a78b5c3460) | Feb 10, 2022 |
| MSI           | MAG B550M MORTAR            | [5e071a1807](https://linux-hardware.org/?probe=5e071a1807) | Feb 09, 2022 |
| Lenovo        | 3140 SDK0J40697 WIN 3305... | [23b715cc77](https://linux-hardware.org/?probe=23b715cc77) | Feb 05, 2022 |
| Gigabyte      | P35-DS3R                    | [3164a5ed5b](https://linux-hardware.org/?probe=3164a5ed5b) | Feb 05, 2022 |
| ASUSTek       | H81M-PLUS                   | [5eaea69c49](https://linux-hardware.org/?probe=5eaea69c49) | Feb 04, 2022 |
| Gigabyte      | H81M-HD3                    | [d554447e6b](https://linux-hardware.org/?probe=d554447e6b) | Feb 04, 2022 |
| MSI           | A320M PRO-VD/S              | [5d9bab6a00](https://linux-hardware.org/?probe=5d9bab6a00) | Feb 02, 2022 |
| ASUSTek       | PRIME H510M-D               | [94fefac9e1](https://linux-hardware.org/?probe=94fefac9e1) | Feb 01, 2022 |
| ASUSTek       | P8H61-M LX3                 | [b80429c5fe](https://linux-hardware.org/?probe=b80429c5fe) | Jan 31, 2022 |
| Acer          | RS880M05                    | [43b14c0f42](https://linux-hardware.org/?probe=43b14c0f42) | Jan 31, 2022 |
| Gigabyte      | B85-HD3                     | [ad70601774](https://linux-hardware.org/?probe=ad70601774) | Jan 26, 2022 |
| Gigabyte      | Z690 UD AX                  | [6ab6d3c8b2](https://linux-hardware.org/?probe=6ab6d3c8b2) | Jan 23, 2022 |
| Dell          | 0YXT71 A03                  | [3609f04919](https://linux-hardware.org/?probe=3609f04919) | Jan 19, 2022 |
| MSI           | B365M PRO-VH                | [8e66dbbe5c](https://linux-hardware.org/?probe=8e66dbbe5c) | Jan 19, 2022 |
| ASUSTek       | Maximus IV GENE-Z           | [e4489c39b8](https://linux-hardware.org/?probe=e4489c39b8) | Jan 18, 2022 |
| MSI           | 2A9C                        | [09004ce71d](https://linux-hardware.org/?probe=09004ce71d) | Jan 14, 2022 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | [6976b6ebbd](https://linux-hardware.org/?probe=6976b6ebbd) | Jan 14, 2022 |
| Acer          | Aspire T3-710 V:1.1         | [088a0a9608](https://linux-hardware.org/?probe=088a0a9608) | Jan 12, 2022 |
| Unknown       | Unknown                     | [a80be6a29f](https://linux-hardware.org/?probe=a80be6a29f) | Jan 12, 2022 |
| HP            | 843B                        | [24e5dae02e](https://linux-hardware.org/?probe=24e5dae02e) | Jan 07, 2022 |
| HP            | 1497                        | [540458f943](https://linux-hardware.org/?probe=540458f943) | Jan 02, 2022 |
| ASUSTek       | P8H61-M LE/USB3             | [a8b3cc88b1](https://linux-hardware.org/?probe=a8b3cc88b1) | Dec 29, 2021 |
| Lenovo        | ThinkStation E20 4220RF8    | [e525340bef](https://linux-hardware.org/?probe=e525340bef) | Dec 28, 2021 |
| Gigabyte      | B450M DS3H-CF               | [1f334f4c1c](https://linux-hardware.org/?probe=1f334f4c1c) | Dec 22, 2021 |
| HP            | 18E7                        | [b233eb9f3e](https://linux-hardware.org/?probe=b233eb9f3e) | Dec 20, 2021 |
| Dell          | 0YXT71 A03                  | [0a48d9579b](https://linux-hardware.org/?probe=0a48d9579b) | Dec 19, 2021 |
| HP            | 1998                        | [9bfa0ed638](https://linux-hardware.org/?probe=9bfa0ed638) | Dec 17, 2021 |
| Gigabyte      | TRX40 AORUS MASTER          | [5915e986de](https://linux-hardware.org/?probe=5915e986de) | Dec 15, 2021 |
| Lenovo        | SHARKBAY NOK                | [2acaeac0de](https://linux-hardware.org/?probe=2acaeac0de) | Dec 14, 2021 |
| Lenovo        | SHARKBAY NOK                | [2c39bc3721](https://linux-hardware.org/?probe=2c39bc3721) | Dec 14, 2021 |
| Gigabyte      | GA-MA78LMT-US2H             | [45a5dc5b06](https://linux-hardware.org/?probe=45a5dc5b06) | Dec 13, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [ed065155fb](https://linux-hardware.org/?probe=ed065155fb) | Dec 11, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [7fe98389c6](https://linux-hardware.org/?probe=7fe98389c6) | Dec 11, 2021 |
| Dell          | 0J3C2F A02                  | [a1cc2ad6fd](https://linux-hardware.org/?probe=a1cc2ad6fd) | Dec 08, 2021 |
| ASRockRack    | E3C232D4U-V1L               | [139a75e689](https://linux-hardware.org/?probe=139a75e689) | Dec 07, 2021 |
| Unknown       | Unknown                     | [1c6db4a61b](https://linux-hardware.org/?probe=1c6db4a61b) | Dec 03, 2021 |
| Gigabyte      | H110M-S2V-CF                | [ad91050095](https://linux-hardware.org/?probe=ad91050095) | Dec 03, 2021 |
| MSI           | X370 XPOWER GAMING TITAN... | [56bd9b515c](https://linux-hardware.org/?probe=56bd9b515c) | Dec 02, 2021 |
| Unknown       | Unknown                     | [e73cda5c1e](https://linux-hardware.org/?probe=e73cda5c1e) | Dec 02, 2021 |
| ASUSTek       | Maximus IV GENE-Z           | [89729fef47](https://linux-hardware.org/?probe=89729fef47) | Nov 25, 2021 |
| ASUSTek       | Maximus IV GENE-Z           | [dab6e17223](https://linux-hardware.org/?probe=dab6e17223) | Nov 23, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | [dba80843bc](https://linux-hardware.org/?probe=dba80843bc) | Nov 23, 2021 |
| Dell          | 0YNVJG A01                  | [00f5cc73fe](https://linux-hardware.org/?probe=00f5cc73fe) | Nov 19, 2021 |
| Lenovo        | SHARKBAY NOK                | [2e7ed34d33](https://linux-hardware.org/?probe=2e7ed34d33) | Nov 16, 2021 |
| Gigabyte      | Z270X-Gaming 5              | [c32869e5a8](https://linux-hardware.org/?probe=c32869e5a8) | Nov 08, 2021 |
| ASUSTek       | A58M-K                      | [0dbc01db57](https://linux-hardware.org/?probe=0dbc01db57) | Nov 08, 2021 |
| Gigabyte      | P31-DS3L                    | [c0ef5646a8](https://linux-hardware.org/?probe=c0ef5646a8) | Nov 07, 2021 |
| HP            | 18E4                        | [1c3ea795a0](https://linux-hardware.org/?probe=1c3ea795a0) | Nov 03, 2021 |
| HP            | 18E4                        | [4994f5c700](https://linux-hardware.org/?probe=4994f5c700) | Nov 03, 2021 |
| Dell          | 0YNVJG A01                  | [0243b19a08](https://linux-hardware.org/?probe=0243b19a08) | Nov 03, 2021 |
| Dell          | 0YNVJG A01                  | [f7d58b572d](https://linux-hardware.org/?probe=f7d58b572d) | Nov 03, 2021 |
| ASUSTek       | H61M-K                      | [f31e6e3dd0](https://linux-hardware.org/?probe=f31e6e3dd0) | Oct 29, 2021 |
| Dell          | 07T4MC A11                  | [219a3a234f](https://linux-hardware.org/?probe=219a3a234f) | Oct 27, 2021 |
| Dell          | 07T4MC A11                  | [870145802c](https://linux-hardware.org/?probe=870145802c) | Oct 27, 2021 |
| IBM           | 82121QG                     | [765d524e7f](https://linux-hardware.org/?probe=765d524e7f) | Oct 26, 2021 |
| ASUSTek       | P5KC                        | [109cb750a6](https://linux-hardware.org/?probe=109cb750a6) | Oct 25, 2021 |
| ASRock        | A75 Extreme6                | [5735bac676](https://linux-hardware.org/?probe=5735bac676) | Oct 16, 2021 |
| ASRock        | 4X4-4000 Series             | [fd95402aa1](https://linux-hardware.org/?probe=fd95402aa1) | Oct 14, 2021 |
| ASRock        | 4X4-4000 Series             | [538c0f7723](https://linux-hardware.org/?probe=538c0f7723) | Oct 14, 2021 |
| HP            | 3031h                       | [eb48a6bfe5](https://linux-hardware.org/?probe=eb48a6bfe5) | Oct 10, 2021 |
| MSI           | H110M PRO-VD                | [ec7609239e](https://linux-hardware.org/?probe=ec7609239e) | Oct 06, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [1f29f9efba](https://linux-hardware.org/?probe=1f29f9efba) | Oct 06, 2021 |
| Dell          | 0T10XW A02                  | [97333f9cab](https://linux-hardware.org/?probe=97333f9cab) | Oct 04, 2021 |
| ASUSTek       | H81M-K                      | [06d254591f](https://linux-hardware.org/?probe=06d254591f) | Oct 02, 2021 |
| ASUSTek       | P5QL PRO                    | [02d6cacb04](https://linux-hardware.org/?probe=02d6cacb04) | Sep 30, 2021 |
| Gigabyte      | J4005ND2P-CF                | [699985f9e6](https://linux-hardware.org/?probe=699985f9e6) | Sep 28, 2021 |
| Gigabyte      | J4005ND2P-CF                | [d82bdfcf17](https://linux-hardware.org/?probe=d82bdfcf17) | Sep 28, 2021 |
| MSI           | H110M PRO-VD                | [68a76785a0](https://linux-hardware.org/?probe=68a76785a0) | Sep 27, 2021 |
| ASRock        | 970 Extreme4                | [7baf276ca0](https://linux-hardware.org/?probe=7baf276ca0) | Sep 26, 2021 |
| Dell          | 0GM819                      | [708ca8f58a](https://linux-hardware.org/?probe=708ca8f58a) | Sep 22, 2021 |
| Dell          | 0GM819                      | [37f5afac35](https://linux-hardware.org/?probe=37f5afac35) | Sep 22, 2021 |
| MSI           | A55M-E33                    | [695bc5477d](https://linux-hardware.org/?probe=695bc5477d) | Sep 22, 2021 |
| ASRock        | Z68 Pro3-M                  | [c7e3f44f44](https://linux-hardware.org/?probe=c7e3f44f44) | Sep 19, 2021 |
| HP            | 3397                        | [13d358c48e](https://linux-hardware.org/?probe=13d358c48e) | Sep 18, 2021 |
| Fujitsu Si... | D2608-A1 S26361-D2608-A1    | [d47952ec42](https://linux-hardware.org/?probe=d47952ec42) | Sep 15, 2021 |
| Fujitsu Si... | D2608-A1 S26361-D2608-A1    | [9c310e15bd](https://linux-hardware.org/?probe=9c310e15bd) | Sep 15, 2021 |
| ASUSTek       | PRIME B450M-K               | [b8b49f201f](https://linux-hardware.org/?probe=b8b49f201f) | Sep 14, 2021 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [da1dd9bb01](https://linux-hardware.org/?probe=da1dd9bb01) | Sep 13, 2021 |
| Dell          | 0YXT71 A03                  | [151a3381f0](https://linux-hardware.org/?probe=151a3381f0) | Sep 09, 2021 |
| MSI           | B350 TOMAHAWK               | [638993c7b0](https://linux-hardware.org/?probe=638993c7b0) | Sep 06, 2021 |
| Dell          | 0YXT71 A03                  | [bb0ef0735f](https://linux-hardware.org/?probe=bb0ef0735f) | Sep 05, 2021 |
| ASUSTek       | D340MC-C                    | [cf81a7ddc2](https://linux-hardware.org/?probe=cf81a7ddc2) | Sep 02, 2021 |
| HP            | 18E9                        | [22f86af485](https://linux-hardware.org/?probe=22f86af485) | Sep 01, 2021 |
| MSI           | A88XM-E35                   | [66070c788f](https://linux-hardware.org/?probe=66070c788f) | Sep 01, 2021 |
| HP            | 3032h                       | [7d94cc3baa](https://linux-hardware.org/?probe=7d94cc3baa) | Sep 01, 2021 |
| HP            | 18E9                        | [539f181954](https://linux-hardware.org/?probe=539f181954) | Aug 29, 2021 |
| Gigabyte      | H61M-DS2                    | [fd9d91270d](https://linux-hardware.org/?probe=fd9d91270d) | Aug 29, 2021 |
| Gigabyte      | H110M-S2-CF                 | [30d745e8d3](https://linux-hardware.org/?probe=30d745e8d3) | Aug 28, 2021 |
| HP            | 1587h                       | [3ddbdb3101](https://linux-hardware.org/?probe=3ddbdb3101) | Aug 19, 2021 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [70be38d5e1](https://linux-hardware.org/?probe=70be38d5e1) | Aug 18, 2021 |
| ASUSTek       | PRIME Z390-P                | [8cf3477dd1](https://linux-hardware.org/?probe=8cf3477dd1) | Aug 18, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [4b4a995bad](https://linux-hardware.org/?probe=4b4a995bad) | Aug 15, 2021 |
| ASUSTek       | PRIME A320M-K               | [40d1d24c90](https://linux-hardware.org/?probe=40d1d24c90) | Aug 11, 2021 |
| ASUSTek       | PRIME A320M-K               | [7cc269740d](https://linux-hardware.org/?probe=7cc269740d) | Aug 10, 2021 |
| Gigabyte      | B450M DS3H-CF               | [99763e52f1](https://linux-hardware.org/?probe=99763e52f1) | Aug 09, 2021 |
| HP            | 2AE2                        | [e8a9a769fe](https://linux-hardware.org/?probe=e8a9a769fe) | Aug 07, 2021 |
| Gigabyte      | A520 AORUS ELITE            | [1d3167cdf0](https://linux-hardware.org/?probe=1d3167cdf0) | Aug 05, 2021 |
| MSI           | Z370 TOMAHAWK               | [3118d29bf0](https://linux-hardware.org/?probe=3118d29bf0) | Aug 05, 2021 |
| ASRock        | X570 Taichi                 | [a7feba2af0](https://linux-hardware.org/?probe=a7feba2af0) | Aug 04, 2021 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | [a7c1a61e9f](https://linux-hardware.org/?probe=a7c1a61e9f) | Aug 03, 2021 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | [d58be51f72](https://linux-hardware.org/?probe=d58be51f72) | Aug 03, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [64dcd58bc3](https://linux-hardware.org/?probe=64dcd58bc3) | Aug 03, 2021 |
| Gigabyte      | P75-D3                      | [5f0bee42c2](https://linux-hardware.org/?probe=5f0bee42c2) | Aug 01, 2021 |
| HP            | 2AE2                        | [61acec4a9c](https://linux-hardware.org/?probe=61acec4a9c) | Aug 01, 2021 |
| HP            | 2AE2                        | [3de122823e](https://linux-hardware.org/?probe=3de122823e) | Aug 01, 2021 |
| MSI           | Z97 GAMING 3                | [a5cc51aec1](https://linux-hardware.org/?probe=a5cc51aec1) | Jul 26, 2021 |
| MSI           | Z97 GAMING 3                | [9e05add91a](https://linux-hardware.org/?probe=9e05add91a) | Jul 26, 2021 |
| HP            | 1850                        | [76e386707a](https://linux-hardware.org/?probe=76e386707a) | Jul 24, 2021 |
| Gigabyte      | Z170X-GamingG1              | [b0ce1bc8f5](https://linux-hardware.org/?probe=b0ce1bc8f5) | Jul 24, 2021 |
| Gigabyte      | TRX40 DESIGNARE             | [11daeb0d8d](https://linux-hardware.org/?probe=11daeb0d8d) | Jul 24, 2021 |
| HP            | 0AA8h                       | [a04f3a673d](https://linux-hardware.org/?probe=a04f3a673d) | Jul 23, 2021 |
| HP            | 0AA8h                       | [b3bbc0186c](https://linux-hardware.org/?probe=b3bbc0186c) | Jul 22, 2021 |
| Dell          | 0YXT71 A03                  | [9f6c5866ae](https://linux-hardware.org/?probe=9f6c5866ae) | Jul 20, 2021 |
| Dell          | 0YXT71 A03                  | [74f54d66b2](https://linux-hardware.org/?probe=74f54d66b2) | Jul 20, 2021 |
| HP            | 3047h                       | [ac149ca840](https://linux-hardware.org/?probe=ac149ca840) | Jul 17, 2021 |
| ASUSTek       | Z97-K                       | [a2a1798503](https://linux-hardware.org/?probe=a2a1798503) | Jul 15, 2021 |
| Dell          | 0X9X1W A00                  | [702d489268](https://linux-hardware.org/?probe=702d489268) | Jul 13, 2021 |
| Lenovo        | 3102 NOK                    | [71974ffb04](https://linux-hardware.org/?probe=71974ffb04) | Jul 12, 2021 |
| Biostar       | N61PA-M2S                   | [346b5914bf](https://linux-hardware.org/?probe=346b5914bf) | Jul 11, 2021 |
| Dell          | 0YXT71 A03                  | [e6d4cd2e90](https://linux-hardware.org/?probe=e6d4cd2e90) | Jul 10, 2021 |
| Dell          | 04GJJT A00                  | [257e9719c0](https://linux-hardware.org/?probe=257e9719c0) | Jul 07, 2021 |
| Dell          | 0VD5HY A07                  | [398ee87d95](https://linux-hardware.org/?probe=398ee87d95) | Jul 04, 2021 |
| Dell          | 0VD5HY A07                  | [0fa3ef38f2](https://linux-hardware.org/?probe=0fa3ef38f2) | Jul 04, 2021 |
| MSI           | B350 TOMAHAWK               | [42fcbcb1e4](https://linux-hardware.org/?probe=42fcbcb1e4) | Jul 02, 2021 |
| ASRock        | B550 Phantom Gaming 4       | [2e13a4aff4](https://linux-hardware.org/?probe=2e13a4aff4) | Jul 02, 2021 |
| ASRock        | B550 Phantom Gaming 4       | [618b266cc7](https://linux-hardware.org/?probe=618b266cc7) | Jul 02, 2021 |
| Gigabyte      | P55-UD5                     | [934948c85f](https://linux-hardware.org/?probe=934948c85f) | Jun 27, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | [59b653ec10](https://linux-hardware.org/?probe=59b653ec10) | Jun 25, 2021 |
| ASUSTek       | H81M-K                      | [aa753c135b](https://linux-hardware.org/?probe=aa753c135b) | Jun 21, 2021 |
| MSI           | Z87-G43                     | [c049769b6b](https://linux-hardware.org/?probe=c049769b6b) | Jun 20, 2021 |
| ASRock        | A320M-DVS R4.0              | [4bc7b480e0](https://linux-hardware.org/?probe=4bc7b480e0) | Jun 16, 2021 |
| ASRock        | G41M-VS3                    | [1df7b23225](https://linux-hardware.org/?probe=1df7b23225) | Jun 11, 2021 |
| HP            | 1494                        | [d34b022996](https://linux-hardware.org/?probe=d34b022996) | Jun 11, 2021 |
| Gigabyte      | B250M-DS3H-CF               | [290d70d292](https://linux-hardware.org/?probe=290d70d292) | Jun 03, 2021 |
| ASUSTek       | P5LD2-VM                    | [6b68ceb0b3](https://linux-hardware.org/?probe=6b68ceb0b3) | Jun 02, 2021 |
| ASUSTek       | P5LD2-VM                    | [3bdb847f96](https://linux-hardware.org/?probe=3bdb847f96) | Jun 01, 2021 |
| Huanan        | X99-TF                      | [b92f4485e6](https://linux-hardware.org/?probe=b92f4485e6) | May 31, 2021 |
| HP            | 3031h                       | [d69cd77c4d](https://linux-hardware.org/?probe=d69cd77c4d) | May 28, 2021 |
| Gigabyte      | 965GM-S2                    | [05ac3124f9](https://linux-hardware.org/?probe=05ac3124f9) | May 26, 2021 |
| Gigabyte      | G41M-Combo                  | [87aca59a7c](https://linux-hardware.org/?probe=87aca59a7c) | May 25, 2021 |
| Gigabyte      | H310M H x.x                 | [141475f02b](https://linux-hardware.org/?probe=141475f02b) | May 25, 2021 |
| HP            | 3029h                       | [1f0ebaa79c](https://linux-hardware.org/?probe=1f0ebaa79c) | May 20, 2021 |
| HP            | 3029h                       | [9eac66bf17](https://linux-hardware.org/?probe=9eac66bf17) | May 20, 2021 |
| Pegatron      | IPPPV-D3G                   | [d4187bad77](https://linux-hardware.org/?probe=d4187bad77) | May 20, 2021 |
| ASRock        | Z77 Extreme4                | [9bc3a8a33e](https://linux-hardware.org/?probe=9bc3a8a33e) | May 20, 2021 |
| Gigabyte      | 965GM-S2                    | [7db6d2bc1a](https://linux-hardware.org/?probe=7db6d2bc1a) | May 20, 2021 |
| ASUSTek       | H170 PRO GAMING             | [110d291fde](https://linux-hardware.org/?probe=110d291fde) | May 13, 2021 |
| HP            | 1494                        | [26a35b5f46](https://linux-hardware.org/?probe=26a35b5f46) | May 10, 2021 |
| ASUSTek       | J1800I-C                    | [2554e9ed0c](https://linux-hardware.org/?probe=2554e9ed0c) | May 10, 2021 |
| HP            | 1496                        | [ef4e0697d7](https://linux-hardware.org/?probe=ef4e0697d7) | May 08, 2021 |
| Gigabyte      | B450M DS3H-CF               | [356c77df30](https://linux-hardware.org/?probe=356c77df30) | May 07, 2021 |
| Gigabyte      | TRX40 AORUS MASTER          | [5927d6bfa2](https://linux-hardware.org/?probe=5927d6bfa2) | May 06, 2021 |
| Intel         | DQ77MK AAG39642-500         | [b1a5da541f](https://linux-hardware.org/?probe=b1a5da541f) | May 04, 2021 |
| Intel         | DQ77MK AAG39642-500         | [155da00fc0](https://linux-hardware.org/?probe=155da00fc0) | May 03, 2021 |
| Gigabyte      | B250M-D2V-CF                | [3eeaf82899](https://linux-hardware.org/?probe=3eeaf82899) | May 01, 2021 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [7f935099f0](https://linux-hardware.org/?probe=7f935099f0) | Apr 28, 2021 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [8dbfa5594e](https://linux-hardware.org/?probe=8dbfa5594e) | Apr 27, 2021 |
| Dell          | 0YXT71 A03                  | [ed71084f85](https://linux-hardware.org/?probe=ed71084f85) | Apr 27, 2021 |
| MSI           | MS-7502 Fab D               | [2a2d112995](https://linux-hardware.org/?probe=2a2d112995) | Apr 23, 2021 |
| ASUSTek       | A68HM-K                     | [06b060c49c](https://linux-hardware.org/?probe=06b060c49c) | Apr 23, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | [42b2eb88ad](https://linux-hardware.org/?probe=42b2eb88ad) | Apr 19, 2021 |
| MSI           | MS-7367                     | [1a103f941a](https://linux-hardware.org/?probe=1a103f941a) | Apr 18, 2021 |
| HP            | 1790                        | [75557f3294](https://linux-hardware.org/?probe=75557f3294) | Apr 18, 2021 |
| Dell          | 0YXT71 A03                  | [a83dfd361b](https://linux-hardware.org/?probe=a83dfd361b) | Apr 14, 2021 |
| Dell          | 0YXT71 A03                  | [b8e3c87a38](https://linux-hardware.org/?probe=b8e3c87a38) | Apr 14, 2021 |
| Dell          | 04GJJT A00                  | [b687e379b9](https://linux-hardware.org/?probe=b687e379b9) | Apr 11, 2021 |
| Gigabyte      | Z68P-DS3                    | [7b4c090391](https://linux-hardware.org/?probe=7b4c090391) | Apr 11, 2021 |
| Lenovo        | ThinkCentre M91p 4524AS3    | [79febd76c3](https://linux-hardware.org/?probe=79febd76c3) | Apr 11, 2021 |
| HP            | 2215                        | [0ce403b929](https://linux-hardware.org/?probe=0ce403b929) | Apr 09, 2021 |
| Lenovo        | ThinkCentre M58 7373WB7     | [57e7329bf2](https://linux-hardware.org/?probe=57e7329bf2) | Apr 09, 2021 |
| Lenovo        | ThinkCentre M58 7359A59     | [0784afdde4](https://linux-hardware.org/?probe=0784afdde4) | Apr 05, 2021 |
| Lenovo        | ThinkCentre M58 7359A59     | [3c49f2205f](https://linux-hardware.org/?probe=3c49f2205f) | Apr 05, 2021 |
| MSI           | FM2-A55M-E33                | [ac0a48160a](https://linux-hardware.org/?probe=ac0a48160a) | Apr 05, 2021 |
| MSI           | FM2-A55M-E33                | [533ebeaa6e](https://linux-hardware.org/?probe=533ebeaa6e) | Apr 05, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [93285dae9e](https://linux-hardware.org/?probe=93285dae9e) | Mar 29, 2021 |
| ASUSTek       | P5KC                        | [0d1ffacb54](https://linux-hardware.org/?probe=0d1ffacb54) | Mar 24, 2021 |
| Gigabyte      | A320M-H-CF                  | [6270efa573](https://linux-hardware.org/?probe=6270efa573) | Mar 20, 2021 |
| HP            | 3029h                       | [0ddf4fe8c8](https://linux-hardware.org/?probe=0ddf4fe8c8) | Mar 20, 2021 |
| HP            | 3047h                       | [d4a58313d6](https://linux-hardware.org/?probe=d4a58313d6) | Mar 16, 2021 |
| Dell          | 0RY007                      | [8c2cacd439](https://linux-hardware.org/?probe=8c2cacd439) | Mar 15, 2021 |
| Dell          | 0RY007                      | [e2527f8f11](https://linux-hardware.org/?probe=e2527f8f11) | Mar 15, 2021 |
| MSI           | 760GM -E51                  | [ed4ec28115](https://linux-hardware.org/?probe=ed4ec28115) | Mar 13, 2021 |
| Gigabyte      | P55-UD5                     | [203d98c6a0](https://linux-hardware.org/?probe=203d98c6a0) | Mar 13, 2021 |
| ASUSTek       | P5KC                        | [d20831473f](https://linux-hardware.org/?probe=d20831473f) | Mar 12, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [3f9b2942e1](https://linux-hardware.org/?probe=3f9b2942e1) | Mar 10, 2021 |
| HP            | 3047h                       | [970a03f12b](https://linux-hardware.org/?probe=970a03f12b) | Mar 09, 2021 |
| HP            | 3047h                       | [2277d0a259](https://linux-hardware.org/?probe=2277d0a259) | Mar 09, 2021 |
| HP            | 3029h                       | [163d32c75c](https://linux-hardware.org/?probe=163d32c75c) | Mar 09, 2021 |
| Dell          | 0GY6Y8 A02                  | [6eac92f735](https://linux-hardware.org/?probe=6eac92f735) | Mar 08, 2021 |
| HP            | 1497                        | [6d49e950fe](https://linux-hardware.org/?probe=6d49e950fe) | Mar 03, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [8b2adea4fc](https://linux-hardware.org/?probe=8b2adea4fc) | Feb 27, 2021 |
| Gigabyte      | B450M DS3H-CF               | [8f08d3592d](https://linux-hardware.org/?probe=8f08d3592d) | Feb 20, 2021 |
| MSI           | 760GM-P23                   | [2f9c20e9ed](https://linux-hardware.org/?probe=2f9c20e9ed) | Feb 20, 2021 |
| HP            | 1998                        | [a574c0a6bb](https://linux-hardware.org/?probe=a574c0a6bb) | Feb 18, 2021 |
| ASUSTek       | M4A785D-M PRO               | [dcc226166f](https://linux-hardware.org/?probe=dcc226166f) | Feb 17, 2021 |
| ASUSTek       | M4A785D-M PRO               | [d326bb69fd](https://linux-hardware.org/?probe=d326bb69fd) | Feb 16, 2021 |
| Gigabyte      | GA-MA790GP-DS4H             | [d288f0a8cd](https://linux-hardware.org/?probe=d288f0a8cd) | Feb 16, 2021 |
| Gigabyte      | GA-MA790GP-DS4H             | [656a59d9a6](https://linux-hardware.org/?probe=656a59d9a6) | Feb 16, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [7450b827a1](https://linux-hardware.org/?probe=7450b827a1) | Feb 14, 2021 |
| ASRock        | B550M Steel Legend          | [4744d31675](https://linux-hardware.org/?probe=4744d31675) | Feb 14, 2021 |
| ASUSTek       | PRIME A320M-K               | [19dc97c5e3](https://linux-hardware.org/?probe=19dc97c5e3) | Feb 13, 2021 |
| HP            | 3048h                       | [2c055ef572](https://linux-hardware.org/?probe=2c055ef572) | Feb 13, 2021 |
| MSI           | MS-7502 Fab D               | [147ca461b7](https://linux-hardware.org/?probe=147ca461b7) | Feb 12, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [5fff5b3dd5](https://linux-hardware.org/?probe=5fff5b3dd5) | Feb 12, 2021 |
| Lenovo        | ThinkStation D20 415892G    | [4abbaf6f5b](https://linux-hardware.org/?probe=4abbaf6f5b) | Feb 11, 2021 |
| MSI           | A68HM-E33 V2                | [353831c5ff](https://linux-hardware.org/?probe=353831c5ff) | Feb 11, 2021 |
| Complet       | MY8313                      | [c730316a6b](https://linux-hardware.org/?probe=c730316a6b) | Feb 03, 2021 |
| ASUSTek       | M11BB                       | [30ab270226](https://linux-hardware.org/?probe=30ab270226) | Feb 02, 2021 |
| ASUSTek       | M11BB                       | [58e5dd3c71](https://linux-hardware.org/?probe=58e5dd3c71) | Feb 02, 2021 |
| ASRock        | H61M-HVS                    | [eee3d9cfa2](https://linux-hardware.org/?probe=eee3d9cfa2) | Jan 31, 2021 |
| Lenovo        | ThinkCentre M58 7373A25     | [80c84ece52](https://linux-hardware.org/?probe=80c84ece52) | Jan 30, 2021 |
| Lenovo        | ThinkCentre M58 7373A25     | [1610c2fab2](https://linux-hardware.org/?probe=1610c2fab2) | Jan 28, 2021 |
| ASUSTek       | CS-B                        | [46b5f91f9e](https://linux-hardware.org/?probe=46b5f91f9e) | Jan 27, 2021 |
| ASUSTek       | CS-B                        | [cf20b0834e](https://linux-hardware.org/?probe=cf20b0834e) | Jan 27, 2021 |
| ASUSTek       | M2N-MX SE Plus              | [83922cd9de](https://linux-hardware.org/?probe=83922cd9de) | Jan 23, 2021 |
| Acer          | Predator G3610              | [582803fed3](https://linux-hardware.org/?probe=582803fed3) | Jan 23, 2021 |
| Gigabyte      | H61M-DS2                    | [9939bcc31c](https://linux-hardware.org/?probe=9939bcc31c) | Jan 20, 2021 |
| Lenovo        | ThinkCentre M58 7373A25     | [2f06637fa5](https://linux-hardware.org/?probe=2f06637fa5) | Jan 19, 2021 |
| Gigabyte      | A320M-S2H-CF                | [bda205658e](https://linux-hardware.org/?probe=bda205658e) | Jan 19, 2021 |
| Gigabyte      | P55-UD5                     | [8552ebd200](https://linux-hardware.org/?probe=8552ebd200) | Jan 18, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [72500dd03c](https://linux-hardware.org/?probe=72500dd03c) | Jan 16, 2021 |
| Packard Be... | VG300                       | [9a025e03bb](https://linux-hardware.org/?probe=9a025e03bb) | Jan 15, 2021 |
| Packard Be... | VG300                       | [7649b086c0](https://linux-hardware.org/?probe=7649b086c0) | Jan 15, 2021 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [4aeb7c78a2](https://linux-hardware.org/?probe=4aeb7c78a2) | Jan 12, 2021 |
| MSI           | B450M PRO-VDH MAX           | [0efd730397](https://linux-hardware.org/?probe=0efd730397) | Jan 12, 2021 |
| ASRock        | B450 Pro4                   | [c4bd6738dd](https://linux-hardware.org/?probe=c4bd6738dd) | Jan 05, 2021 |
| ASRock        | B450 Pro4                   | [462a5eec6c](https://linux-hardware.org/?probe=462a5eec6c) | Jan 05, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [65d3eda43c](https://linux-hardware.org/?probe=65d3eda43c) | Jan 02, 2021 |
| MSI           | MS-7346                     | [3e709ba6e1](https://linux-hardware.org/?probe=3e709ba6e1) | Dec 26, 2020 |
| HP            | 18E9                        | [a33c671a96](https://linux-hardware.org/?probe=a33c671a96) | Dec 26, 2020 |
| ASUSTek       | Maximus VIII HERO           | [56d4ff7c49](https://linux-hardware.org/?probe=56d4ff7c49) | Dec 22, 2020 |
| ASUSTek       | Maximus VIII HERO           | [33193096fe](https://linux-hardware.org/?probe=33193096fe) | Dec 22, 2020 |
| ECS           | nForce3-A                   | [0150835d63](https://linux-hardware.org/?probe=0150835d63) | Dec 21, 2020 |
| ECS           | nForce3-A                   | [c08a9c2d3a](https://linux-hardware.org/?probe=c08a9c2d3a) | Dec 21, 2020 |
| MSI           | X370 GAMING PRO CARBON      | [c74c628d8a](https://linux-hardware.org/?probe=c74c628d8a) | Dec 19, 2020 |
| Gigabyte      | B85M-D3H-A                  | [f0c5adfa14](https://linux-hardware.org/?probe=f0c5adfa14) | Dec 15, 2020 |
| Acer          | Nitro GX50-600              | [ca40ac648d](https://linux-hardware.org/?probe=ca40ac648d) | Dec 14, 2020 |
| Acer          | Nitro GX50-600              | [61f4f9991a](https://linux-hardware.org/?probe=61f4f9991a) | Dec 13, 2020 |
| Acer          | Nitro N50-610               | [560e5d0b17](https://linux-hardware.org/?probe=560e5d0b17) | Dec 12, 2020 |
| HP            | 3047h                       | [b7967b4e02](https://linux-hardware.org/?probe=b7967b4e02) | Dec 10, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [e452d60d3e](https://linux-hardware.org/?probe=e452d60d3e) | Dec 09, 2020 |
| Gigabyte      | B250M-D3H-CF                | [b8cf7df3c1](https://linux-hardware.org/?probe=b8cf7df3c1) | Dec 09, 2020 |
| MSI           | H170A PC MATE               | [5cc4fd552a](https://linux-hardware.org/?probe=5cc4fd552a) | Dec 07, 2020 |
| Gigabyte      | B550M DS3H                  | [01fa23f0fc](https://linux-hardware.org/?probe=01fa23f0fc) | Dec 07, 2020 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [3f93555527](https://linux-hardware.org/?probe=3f93555527) | Dec 05, 2020 |
| HP            | 2820h                       | [eb04cf12aa](https://linux-hardware.org/?probe=eb04cf12aa) | Dec 05, 2020 |
| OEM_MB        | Acacia                      | [e6eacc1023](https://linux-hardware.org/?probe=e6eacc1023) | Dec 03, 2020 |
| ASUSTek       | PRIME A320M-E               | [9d05f29b71](https://linux-hardware.org/?probe=9d05f29b71) | Dec 02, 2020 |
| HP            | 18E9                        | [0358f91af6](https://linux-hardware.org/?probe=0358f91af6) | Dec 01, 2020 |
| Dell          | 0GM819                      | [2555a4411a](https://linux-hardware.org/?probe=2555a4411a) | Nov 30, 2020 |
| Gigabyte      | AB350-Gaming 3-CF           | [194ae6839d](https://linux-hardware.org/?probe=194ae6839d) | Nov 30, 2020 |
| Dell          | 0XPDFK A01                  | [02ffa180c8](https://linux-hardware.org/?probe=02ffa180c8) | Nov 30, 2020 |
| MSI           | A320M-A PRO MAX             | [4b40e4f17c](https://linux-hardware.org/?probe=4b40e4f17c) | Nov 28, 2020 |
| Gigabyte      | X570 AORUS ELITE            | [294c2bf2e7](https://linux-hardware.org/?probe=294c2bf2e7) | Nov 28, 2020 |
| ASUSTek       | Z97-A                       | [ab840ac981](https://linux-hardware.org/?probe=ab840ac981) | Nov 26, 2020 |
| HP            | 2820h                       | [2afd23d45d](https://linux-hardware.org/?probe=2afd23d45d) | Nov 26, 2020 |
| Gigabyte      | TRX40 AORUS MASTER          | [a6e62c55c4](https://linux-hardware.org/?probe=a6e62c55c4) | Nov 24, 2020 |
| Dell          | 0C27VV A02                  | [0ed1683811](https://linux-hardware.org/?probe=0ed1683811) | Nov 24, 2020 |
| Gigabyte      | B450M DS3H-CF               | [6e5f3102d1](https://linux-hardware.org/?probe=6e5f3102d1) | Nov 21, 2020 |
| ASUSTek       | PRIME B250M-K               | [e8b8c79116](https://linux-hardware.org/?probe=e8b8c79116) | Nov 20, 2020 |
| ASUSTek       | PRIME B250M-K               | [0f5dcabdb8](https://linux-hardware.org/?probe=0f5dcabdb8) | Nov 20, 2020 |
| Gigabyte      | H81M-DS2V                   | [32e27e5b75](https://linux-hardware.org/?probe=32e27e5b75) | Nov 19, 2020 |
| Gigabyte      | H81M-DS2V                   | [dc3e802782](https://linux-hardware.org/?probe=dc3e802782) | Nov 19, 2020 |
| HP            | 3048h                       | [7fe9c668aa](https://linux-hardware.org/?probe=7fe9c668aa) | Nov 18, 2020 |
| Gigabyte      | Z77X-D3H                    | [d7dc793c40](https://linux-hardware.org/?probe=d7dc793c40) | Nov 15, 2020 |
| Gigabyte      | X570 UD                     | [9003c7f0b1](https://linux-hardware.org/?probe=9003c7f0b1) | Nov 15, 2020 |
| ASUSTek       | J1800I-C                    | [d93f8d1bbc](https://linux-hardware.org/?probe=d93f8d1bbc) | Nov 13, 2020 |
| Unknown       | Unknown                     | [5f2dac9c99](https://linux-hardware.org/?probe=5f2dac9c99) | Nov 11, 2020 |
| Foxconn       | 45CMX/45GMX/45CMX-K         | [05b7d97ed0](https://linux-hardware.org/?probe=05b7d97ed0) | Nov 08, 2020 |
| ASRock        | N68-GE3 UCC                 | [325e278ffe](https://linux-hardware.org/?probe=325e278ffe) | Nov 08, 2020 |
| Fujitsu Si... | D2587-A1 S26361-D2587-A1    | [d584773eee](https://linux-hardware.org/?probe=d584773eee) | Nov 08, 2020 |
| Foxconn       | 45CMX/45GMX/45CMX-K         | [6b84bce70f](https://linux-hardware.org/?probe=6b84bce70f) | Nov 08, 2020 |
| MSI           | MS-7367                     | [1caace16cf](https://linux-hardware.org/?probe=1caace16cf) | Nov 08, 2020 |
| MSI           | H110M PRO-VD                | [bb789b7196](https://linux-hardware.org/?probe=bb789b7196) | Nov 04, 2020 |
| MSI           | B365M PRO-VH                | [2f0b8b27c3](https://linux-hardware.org/?probe=2f0b8b27c3) | Nov 03, 2020 |
| ASUSTek       | CS-B                        | [4e0f76c433](https://linux-hardware.org/?probe=4e0f76c433) | Nov 02, 2020 |
| Fujitsu Si... | D2594-A1 S26361-D2594-A1    | [b04f10e40a](https://linux-hardware.org/?probe=b04f10e40a) | Nov 01, 2020 |
| MSI           | MEG Z490I UNIFY             | [e59b548946](https://linux-hardware.org/?probe=e59b548946) | Oct 31, 2020 |
| MSI           | MEG Z490I UNIFY             | [39348ac053](https://linux-hardware.org/?probe=39348ac053) | Oct 31, 2020 |
| Gigabyte      | A320M-S2H-CF                | [85c49d42c4](https://linux-hardware.org/?probe=85c49d42c4) | Oct 29, 2020 |
| MSI           | MS-7253                     | [5a04962352](https://linux-hardware.org/?probe=5a04962352) | Oct 24, 2020 |
| MSI           | MS-7253                     | [b8ace166e0](https://linux-hardware.org/?probe=b8ace166e0) | Oct 23, 2020 |
| Dell          | 0J3C2F A02                  | [a0c7490384](https://linux-hardware.org/?probe=a0c7490384) | Oct 23, 2020 |
| Lenovo        | ThinkCentre M91p 4524AS3    | [910418d797](https://linux-hardware.org/?probe=910418d797) | Oct 22, 2020 |
| Gigabyte      | H310M H x.x                 | [72566da264](https://linux-hardware.org/?probe=72566da264) | Oct 18, 2020 |
| ASUSTek       | H81M-K                      | [799659ac10](https://linux-hardware.org/?probe=799659ac10) | Oct 18, 2020 |
| MSI           | B450 GAMING PLUS MAX        | [5fa86b3b29](https://linux-hardware.org/?probe=5fa86b3b29) | Oct 18, 2020 |
| Foxconn       | 2ADA                        | [4365f32962](https://linux-hardware.org/?probe=4365f32962) | Oct 16, 2020 |
| Foxconn       | 45CMX/45GMX/45CMX-K         | [dff0f9c7be](https://linux-hardware.org/?probe=dff0f9c7be) | Oct 16, 2020 |
| Foxconn       | 45CMX/45GMX/45CMX-K         | [98b9a321a8](https://linux-hardware.org/?probe=98b9a321a8) | Oct 15, 2020 |
| HP            | 843B                        | [86632c3a3e](https://linux-hardware.org/?probe=86632c3a3e) | Oct 15, 2020 |
| Dell          | 0PC5F7 A02                  | [0b4436db73](https://linux-hardware.org/?probe=0b4436db73) | Oct 14, 2020 |
| ASUSTek       | H110M-C                     | [8e61f49a7f](https://linux-hardware.org/?probe=8e61f49a7f) | Oct 14, 2020 |
| Gigabyte      | Z270X-Gaming 5              | [f700963cf3](https://linux-hardware.org/?probe=f700963cf3) | Oct 11, 2020 |
| MSI           | H61M-P20                    | [0bf2f11818](https://linux-hardware.org/?probe=0bf2f11818) | Oct 08, 2020 |
| ASUSTek       | P5KPL-AM EPU                | [091b86b414](https://linux-hardware.org/?probe=091b86b414) | Oct 06, 2020 |
| ASRock        | 970 Extreme4                | [e4bb5bfc52](https://linux-hardware.org/?probe=e4bb5bfc52) | Oct 02, 2020 |
| ASUSTek       | ROG Maximus XII FORMULA     | [baf6875e8d](https://linux-hardware.org/?probe=baf6875e8d) | Sep 29, 2020 |
| ASRock        | H87 Pro4                    | [c9e5c6c639](https://linux-hardware.org/?probe=c9e5c6c639) | Sep 29, 2020 |
| Acer          | FG43D                       | [6b0868f448](https://linux-hardware.org/?probe=6b0868f448) | Sep 27, 2020 |
| MSI           | B350 TOMAHAWK               | [3be86ad86b](https://linux-hardware.org/?probe=3be86ad86b) | Sep 26, 2020 |
| MSI           | B350 TOMAHAWK               | [a0de953cb3](https://linux-hardware.org/?probe=a0de953cb3) | Sep 26, 2020 |
| ASUSTek       | P8H77-M PRO                 | [2b3c2ec612](https://linux-hardware.org/?probe=2b3c2ec612) | Sep 22, 2020 |
| Gigabyte      | GA-870A-USB3L               | [bfff15642e](https://linux-hardware.org/?probe=bfff15642e) | Sep 22, 2020 |
| HP            | 0A54h                       | [0ee20adf26](https://linux-hardware.org/?probe=0ee20adf26) | Sep 20, 2020 |
| Dell          | 0J3C2F A02                  | [c1cbfad587](https://linux-hardware.org/?probe=c1cbfad587) | Sep 20, 2020 |
| HP            | 0A54h                       | [0095e33a1e](https://linux-hardware.org/?probe=0095e33a1e) | Sep 20, 2020 |
| ASUSTek       | PRIME X470-PRO              | [6c0de749d5](https://linux-hardware.org/?probe=6c0de749d5) | Sep 12, 2020 |
| Fujitsu Si... | D2584-A1 S26361-D2584-A1    | [bdc2121d7e](https://linux-hardware.org/?probe=bdc2121d7e) | Sep 11, 2020 |
| Gigabyte      | Z77-DS3H                    | [ab95a02da7](https://linux-hardware.org/?probe=ab95a02da7) | Sep 09, 2020 |
| HP            | 0A54h                       | [a519d456a2](https://linux-hardware.org/?probe=a519d456a2) | Sep 05, 2020 |
| Gigabyte      | X570 AORUS PRO              | [4a6b216d3f](https://linux-hardware.org/?probe=4a6b216d3f) | Sep 03, 2020 |
| MSI           | B450 GAMING PLUS MAX        | [ed48b53c8f](https://linux-hardware.org/?probe=ed48b53c8f) | Sep 03, 2020 |
| ASUSTek       | PRIME A320M-K               | [55f5a50f2f](https://linux-hardware.org/?probe=55f5a50f2f) | Sep 03, 2020 |
| Gigabyte      | X570 AORUS PRO              | [106859ac08](https://linux-hardware.org/?probe=106859ac08) | Sep 03, 2020 |
| Fujitsu Si... | D2587-A1 S26361-D2587-A1    | [89e7ddc6ec](https://linux-hardware.org/?probe=89e7ddc6ec) | Sep 01, 2020 |
| Dell          | 0GTK4K A02                  | [81f3fe5ce0](https://linux-hardware.org/?probe=81f3fe5ce0) | Aug 26, 2020 |
| Dell          | 0GTK4K A02                  | [09fb692364](https://linux-hardware.org/?probe=09fb692364) | Aug 26, 2020 |
| HP            | 2215                        | [3a17574701](https://linux-hardware.org/?probe=3a17574701) | Aug 25, 2020 |
| ECS           | nForce3-A                   | [749e54bb87](https://linux-hardware.org/?probe=749e54bb87) | Aug 24, 2020 |
| ASUSTek       | P8H77-M PRO                 | [bab7cedeb6](https://linux-hardware.org/?probe=bab7cedeb6) | Aug 15, 2020 |
| HP            | 0A54h                       | [2267cb3001](https://linux-hardware.org/?probe=2267cb3001) | Aug 14, 2020 |
| Gigabyte      | B360M HD3                   | [be8312bb93](https://linux-hardware.org/?probe=be8312bb93) | Aug 14, 2020 |
| MSI           | 760GM -E51                  | [a519c7c3b0](https://linux-hardware.org/?probe=a519c7c3b0) | Aug 06, 2020 |
| Foxconn       | 2ABF                        | [d35ce8ed45](https://linux-hardware.org/?probe=d35ce8ed45) | Aug 05, 2020 |
| HP            | 2820h                       | [07f1d4d4c5](https://linux-hardware.org/?probe=07f1d4d4c5) | Aug 01, 2020 |
| MSI           | H61M-P20                    | [0f9ddb6d2d](https://linux-hardware.org/?probe=0f9ddb6d2d) | Jul 29, 2020 |
| MSI           | H61M-P20                    | [5c52b6abf8](https://linux-hardware.org/?probe=5c52b6abf8) | Jul 29, 2020 |
| ASRock        | G41M-VS3                    | [f8c988d901](https://linux-hardware.org/?probe=f8c988d901) | Jul 22, 2020 |
| ASRock        | G41M-VS3                    | [1ea1f6acd1](https://linux-hardware.org/?probe=1ea1f6acd1) | Jul 22, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [01f8c369e0](https://linux-hardware.org/?probe=01f8c369e0) | Jul 21, 2020 |
| MSI           | B360M PRO-VDH               | [d0203a02fc](https://linux-hardware.org/?probe=d0203a02fc) | Jul 21, 2020 |
| Dell          | 0C27VV A00                  | [60cd9f8b7e](https://linux-hardware.org/?probe=60cd9f8b7e) | Jul 19, 2020 |
| HP            | 158A                        | [7bd0d3ac0a](https://linux-hardware.org/?probe=7bd0d3ac0a) | Jul 17, 2020 |
| Gigabyte      | Z170-HD3 DDR3-CF            | [b48720d1bf](https://linux-hardware.org/?probe=b48720d1bf) | Jul 16, 2020 |
| HP            | 2215                        | [fbd9395652](https://linux-hardware.org/?probe=fbd9395652) | Jul 12, 2020 |
| Gigabyte      | X570 AORUS MASTER           | [2e464f5c9a](https://linux-hardware.org/?probe=2e464f5c9a) | Jul 11, 2020 |
| Biostar       | N61PA-M2S                   | [42e0cd75c1](https://linux-hardware.org/?probe=42e0cd75c1) | Jul 10, 2020 |
| Biostar       | N61PA-M2S                   | [d8c6dd9ca2](https://linux-hardware.org/?probe=d8c6dd9ca2) | Jul 10, 2020 |
| ASRock        | K8Upgrade-NF3               | [c083fb4bfe](https://linux-hardware.org/?probe=c083fb4bfe) | Jul 08, 2020 |
| MSI           | MPG X570 GAMING EDGE WIF... | [27ee239e69](https://linux-hardware.org/?probe=27ee239e69) | Jul 07, 2020 |
| MSI           | MS-7367                     | [f34fd6f016](https://linux-hardware.org/?probe=f34fd6f016) | Jul 07, 2020 |
| ASRock        | K8Upgrade-NF3               | [8ee0cf7d01](https://linux-hardware.org/?probe=8ee0cf7d01) | Jul 06, 2020 |
| ASRock        | 990FX Extreme3              | [e5ec01d31c](https://linux-hardware.org/?probe=e5ec01d31c) | Jul 05, 2020 |
| ASUSTek       | PRIME X370-PRO              | [333fcb65b5](https://linux-hardware.org/?probe=333fcb65b5) | Jul 04, 2020 |
| ASRock        | 990FX Extreme3              | [318ea016b3](https://linux-hardware.org/?probe=318ea016b3) | Jul 04, 2020 |
| Gigabyte      | H110M-S2H DDR3-CF           | [647c30ca0c](https://linux-hardware.org/?probe=647c30ca0c) | Jul 03, 2020 |
| Foxconn       | 2ADA                        | [478ff4e2a2](https://linux-hardware.org/?probe=478ff4e2a2) | Jul 01, 2020 |
| Foxconn       | 2ADA                        | [d63d4101a2](https://linux-hardware.org/?probe=d63d4101a2) | Jul 01, 2020 |
| Dell          | 0JJW8N A03                  | [f3f1076643](https://linux-hardware.org/?probe=f3f1076643) | Jul 01, 2020 |
| HP            | 0A54h                       | [2613499d80](https://linux-hardware.org/?probe=2613499d80) | Jun 30, 2020 |
| Fujitsu Si... | D2811-A1 S26361-D2811-A1    | [a40e30b62b](https://linux-hardware.org/?probe=a40e30b62b) | Jun 29, 2020 |
| Fujitsu Si... | D2811-A1 S26361-D2811-A1    | [cb20f6e877](https://linux-hardware.org/?probe=cb20f6e877) | Jun 29, 2020 |
| HP            | 0A54h                       | [89d11a0415](https://linux-hardware.org/?probe=89d11a0415) | Jun 27, 2020 |
| Dell          | 0RW203                      | [8ba004d478](https://linux-hardware.org/?probe=8ba004d478) | Jun 25, 2020 |
| Dell          | 0RW203                      | [7e50eb34dc](https://linux-hardware.org/?probe=7e50eb34dc) | Jun 24, 2020 |
| Dell          | 0RW203                      | [b853674a1a](https://linux-hardware.org/?probe=b853674a1a) | Jun 24, 2020 |
| HP            | 3032h                       | [5976308dd2](https://linux-hardware.org/?probe=5976308dd2) | Jun 23, 2020 |
| Gigabyte      | H81M-S2V                    | [5834d675d4](https://linux-hardware.org/?probe=5834d675d4) | Jun 22, 2020 |
| ASRock        | H61M-VS                     | [a7873af7a8](https://linux-hardware.org/?probe=a7873af7a8) | Jun 22, 2020 |
| HP            | 3032h                       | [e8f5c5f1dd](https://linux-hardware.org/?probe=e8f5c5f1dd) | Jun 22, 2020 |
| Gigabyte      | GA-870A-USB3L               | [5a16692c62](https://linux-hardware.org/?probe=5a16692c62) | Jun 21, 2020 |
| MSI           | H110M PRO-D                 | [c69d5f5bf9](https://linux-hardware.org/?probe=c69d5f5bf9) | Jun 20, 2020 |
| ASUSTek       | P5GC-MX/1333                | [c8f7c8e815](https://linux-hardware.org/?probe=c8f7c8e815) | Jun 15, 2020 |
| Gigabyte      | 990XA-UD3                   | [d8882da61a](https://linux-hardware.org/?probe=d8882da61a) | Jun 13, 2020 |
| Lenovo        | NOK                         | [b61ac858bf](https://linux-hardware.org/?probe=b61ac858bf) | Jun 06, 2020 |
| Gigabyte      | Z390 D                      | [b1a29e63a6](https://linux-hardware.org/?probe=b1a29e63a6) | Jun 06, 2020 |
| ASUSTek       | PRIME H310M-R R2.0          | [aa7fa3a7d6](https://linux-hardware.org/?probe=aa7fa3a7d6) | Jun 05, 2020 |
| Intel         | DQ77MK AAG39642-302         | [dee8f8adaa](https://linux-hardware.org/?probe=dee8f8adaa) | Jun 03, 2020 |
| Lenovo        | 30C9 SDK0J40697 WIN 3305... | [0bd408c7b1](https://linux-hardware.org/?probe=0bd408c7b1) | Jun 03, 2020 |
| MSI           | X570-A PRO                  | [aeb2569425](https://linux-hardware.org/?probe=aeb2569425) | Jun 03, 2020 |
| Lenovo        | 30C9 SDK0J40697 WIN 3305... | [b56fca6b80](https://linux-hardware.org/?probe=b56fca6b80) | Jun 02, 2020 |
| ASUSTek       | PRIME H310M-R R2.0          | [1cfddc628b](https://linux-hardware.org/?probe=1cfddc628b) | Jun 02, 2020 |
| Lenovo        | 30C9 SDK0J40697 WIN 3305... | [9db69a23c3](https://linux-hardware.org/?probe=9db69a23c3) | May 31, 2020 |
| Gigabyte      | Z390 AORUS ELITE-CF         | [570ec797bb](https://linux-hardware.org/?probe=570ec797bb) | May 26, 2020 |
| Lenovo        | NOK                         | [1533aaa14e](https://linux-hardware.org/?probe=1533aaa14e) | May 25, 2020 |
| Lenovo        | NOK                         | [870f6a7371](https://linux-hardware.org/?probe=870f6a7371) | May 25, 2020 |
| Lenovo        | NOK                         | [65e8f4a17a](https://linux-hardware.org/?probe=65e8f4a17a) | May 25, 2020 |
| ASUSTek       | P8H77-M PRO                 | [cdaf886b58](https://linux-hardware.org/?probe=cdaf886b58) | May 20, 2020 |
| ASUSTek       | P8H77-M PRO                 | [e8b5bf55c7](https://linux-hardware.org/?probe=e8b5bf55c7) | May 20, 2020 |
| ASRock        | 970 Pro3 R2.0               | [194b0f5144](https://linux-hardware.org/?probe=194b0f5144) | May 19, 2020 |
| Gigabyte      | Z390 AORUS PRO-CF           | [efbb3a1981](https://linux-hardware.org/?probe=efbb3a1981) | May 19, 2020 |
| MSI           | B350 PC MATE                | [e451a207b9](https://linux-hardware.org/?probe=e451a207b9) | May 17, 2020 |
| MSI           | B350 PC MATE                | [0ad7002dd0](https://linux-hardware.org/?probe=0ad7002dd0) | May 15, 2020 |
| ASUSTek       | P5KC                        | [430457f5ee](https://linux-hardware.org/?probe=430457f5ee) | May 15, 2020 |
| OEM_MB        | Acacia                      | [728c9bcc6f](https://linux-hardware.org/?probe=728c9bcc6f) | May 13, 2020 |
| ASUSTek       | PRIME H310M-R R2.0          | [bd619a1dbf](https://linux-hardware.org/?probe=bd619a1dbf) | May 09, 2020 |
| ASUSTek       | PRIME H310M-R R2.0          | [50fc5c1115](https://linux-hardware.org/?probe=50fc5c1115) | May 09, 2020 |
| ASUSTek       | TUF X470-PLUS GAMING        | [9e0089ee78](https://linux-hardware.org/?probe=9e0089ee78) | May 09, 2020 |
| Dell          | 09KPNV A00                  | [4a3b4d800c](https://linux-hardware.org/?probe=4a3b4d800c) | May 09, 2020 |
| ASUSTek       | PRIME H310M-R R2.0          | [24005d0bbd](https://linux-hardware.org/?probe=24005d0bbd) | May 08, 2020 |
| Dell          | 0XC7MM A00                  | [93a90c984c](https://linux-hardware.org/?probe=93a90c984c) | May 07, 2020 |
| Gigabyte      | Z97X-Gaming 3               | [a4c12b7e1d](https://linux-hardware.org/?probe=a4c12b7e1d) | May 05, 2020 |
| Lenovo        | 3102 NOK                    | [a5548bc2a2](https://linux-hardware.org/?probe=a5548bc2a2) | May 05, 2020 |
| Lenovo        | 3102 NOK                    | [9045fced05](https://linux-hardware.org/?probe=9045fced05) | May 05, 2020 |
| ASRock        | N68-S                       | [6fe5619a96](https://linux-hardware.org/?probe=6fe5619a96) | May 04, 2020 |
| Gigabyte      | B250M-D2V-CF                | [fe8ae782e5](https://linux-hardware.org/?probe=fe8ae782e5) | May 04, 2020 |
| Complet       | MY8313                      | [9113ead08c](https://linux-hardware.org/?probe=9113ead08c) | May 01, 2020 |
| ASUSTek       | TUF X470-PLUS GAMING        | [6bcd8b58d1](https://linux-hardware.org/?probe=6bcd8b58d1) | Apr 28, 2020 |
| Gigabyte      | EQ45M-S2                    | [1faa92e0c1](https://linux-hardware.org/?probe=1faa92e0c1) | Apr 27, 2020 |
| Gigabyte      | EQ45M-S2                    | [e8adc47158](https://linux-hardware.org/?probe=e8adc47158) | Apr 27, 2020 |
| Gigabyte      | Z97X-Gaming 7               | [ae0a57779f](https://linux-hardware.org/?probe=ae0a57779f) | Apr 24, 2020 |
| ASUSTek       | PRIME X370-PRO              | [4f21b4b167](https://linux-hardware.org/?probe=4f21b4b167) | Apr 18, 2020 |
| ASUSTek       | H81M-K                      | [13f01f24a0](https://linux-hardware.org/?probe=13f01f24a0) | Apr 18, 2020 |
| Intel         | P61A-D3                     | [0f22534587](https://linux-hardware.org/?probe=0f22534587) | Apr 16, 2020 |
| ASUSTek       | PRIME X470-PRO              | [e9be68d1ba](https://linux-hardware.org/?probe=e9be68d1ba) | Apr 13, 2020 |
| Gigabyte      | B150M-HD3-CF                | [cd8a2159c3](https://linux-hardware.org/?probe=cd8a2159c3) | Apr 13, 2020 |
| Intel         | DH77EB AAG39073-304         | [fcdb9f69df](https://linux-hardware.org/?probe=fcdb9f69df) | Apr 05, 2020 |
| Intel         | DH77EB AAG39073-304         | [e482f59a9f](https://linux-hardware.org/?probe=e482f59a9f) | Apr 04, 2020 |
| ASRock        | Q1900M                      | [ef0888b755](https://linux-hardware.org/?probe=ef0888b755) | Mar 31, 2020 |
| Dell          | 0M863N A00                  | [39201e0067](https://linux-hardware.org/?probe=39201e0067) | Mar 30, 2020 |
| HP            | 3047h                       | [82d80b5b7b](https://linux-hardware.org/?probe=82d80b5b7b) | Mar 28, 2020 |
| Pegatron      | 2A94h                       | [b48f3764dd](https://linux-hardware.org/?probe=b48f3764dd) | Mar 27, 2020 |
| Dell          | 0HR330                      | [45d93c28db](https://linux-hardware.org/?probe=45d93c28db) | Mar 27, 2020 |
| ASUSTek       | Maximus IV Extreme          | [0f6b13c96c](https://linux-hardware.org/?probe=0f6b13c96c) | Mar 26, 2020 |
| Gigabyte      | B450M DS3H-CF               | [63493eaa7c](https://linux-hardware.org/?probe=63493eaa7c) | Mar 26, 2020 |
| Gigabyte      | A320M-S2H-CF                | [7f673748d3](https://linux-hardware.org/?probe=7f673748d3) | Mar 25, 2020 |
| ASUSTek       | PRIME Z370-A                | [29e5b3da4d](https://linux-hardware.org/?probe=29e5b3da4d) | Mar 20, 2020 |
| MSI           | B250M PRO-VDH               | [76e711b112](https://linux-hardware.org/?probe=76e711b112) | Mar 19, 2020 |
| MSI           | B250M PRO-VDH               | [8dfaccae3f](https://linux-hardware.org/?probe=8dfaccae3f) | Mar 19, 2020 |
| Gigabyte      | B250M-D2V-CF                | [0a4936eac1](https://linux-hardware.org/?probe=0a4936eac1) | Mar 18, 2020 |
| Acer          | RS780DV                     | [e8a070d344](https://linux-hardware.org/?probe=e8a070d344) | Mar 15, 2020 |
| Gigabyte      | B450M DS3H-CF               | [5f9a0dc8a8](https://linux-hardware.org/?probe=5f9a0dc8a8) | Mar 12, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [9b5408936f](https://linux-hardware.org/?probe=9b5408936f) | Mar 09, 2020 |
| MSI           | MS-7367                     | [8eb4606ae2](https://linux-hardware.org/?probe=8eb4606ae2) | Mar 07, 2020 |
| Gigabyte      | B250M-D2V-CF                | [f625e9f2ae](https://linux-hardware.org/?probe=f625e9f2ae) | Mar 06, 2020 |
| ASRock        | N68-S                       | [dfa1f67ae9](https://linux-hardware.org/?probe=dfa1f67ae9) | Mar 03, 2020 |
| Intel         | P61A-D3                     | [21fe352cc4](https://linux-hardware.org/?probe=21fe352cc4) | Feb 29, 2020 |
| Gigabyte      | B250M-D2V-CF                | [6549fb9401](https://linux-hardware.org/?probe=6549fb9401) | Feb 25, 2020 |
| MSI           | MS-7367                     | [fd923525d3](https://linux-hardware.org/?probe=fd923525d3) | Feb 21, 2020 |
| ASRock        | X99 Professional Gaming ... | [d1589dfc12](https://linux-hardware.org/?probe=d1589dfc12) | Feb 21, 2020 |
| ASRock        | X570 Taichi                 | [4af950f796](https://linux-hardware.org/?probe=4af950f796) | Feb 21, 2020 |
| ASUSTek       | J1800I-C                    | [a1311f8998](https://linux-hardware.org/?probe=a1311f8998) | Feb 18, 2020 |
| ASUSTek       | J1800I-C                    | [35e0f9b772](https://linux-hardware.org/?probe=35e0f9b772) | Feb 18, 2020 |
| ASUSTek       | Maximus IV Extreme          | [daf1f1f048](https://linux-hardware.org/?probe=daf1f1f048) | Feb 18, 2020 |
| ASUSTek       | Maximus IV Extreme          | [48767aacae](https://linux-hardware.org/?probe=48767aacae) | Feb 18, 2020 |
| ASUSTek       | Z170-A                      | [1ef6222ab2](https://linux-hardware.org/?probe=1ef6222ab2) | Feb 16, 2020 |
| ASUSTek       | Z170-A                      | [c96f9af8a3](https://linux-hardware.org/?probe=c96f9af8a3) | Feb 16, 2020 |
| ASUSTek       | Z10PA-D8 Series             | [150fb396a7](https://linux-hardware.org/?probe=150fb396a7) | Feb 10, 2020 |
| Gigabyte      | P61A-D3                     | [2bc82261f2](https://linux-hardware.org/?probe=2bc82261f2) | Feb 10, 2020 |
| MSI           | A320M PRO-VD PLUS           | [e6ac4bad03](https://linux-hardware.org/?probe=e6ac4bad03) | Feb 04, 2020 |
| MSI           | A320M PRO-VD PLUS           | [3b23ebaf4a](https://linux-hardware.org/?probe=3b23ebaf4a) | Feb 04, 2020 |
| ASUSTek       | P8H61-M LX2/CSM             | [68ecdc80d6](https://linux-hardware.org/?probe=68ecdc80d6) | Jan 30, 2020 |
| ASUSTek       | Maximus IV Extreme          | [c693069d4a](https://linux-hardware.org/?probe=c693069d4a) | Jan 30, 2020 |
| HP            | 83F0                        | [89a6f21080](https://linux-hardware.org/?probe=89a6f21080) | Jan 27, 2020 |
| ASRock        | N68-S                       | [ce51ddbd14](https://linux-hardware.org/?probe=ce51ddbd14) | Jan 20, 2020 |
| HP            | 339B                        | [2660198e55](https://linux-hardware.org/?probe=2660198e55) | Jan 18, 2020 |
| Gigabyte      | AX370-Gaming 5              | [25c8c37228](https://linux-hardware.org/?probe=25c8c37228) | Jan 16, 2020 |
| ASUSTek       | Maximus IV Extreme          | [317c6352fb](https://linux-hardware.org/?probe=317c6352fb) | Jan 13, 2020 |
| HP            | 1850                        | [2b217c7053](https://linux-hardware.org/?probe=2b217c7053) | Jan 12, 2020 |
| ASRock        | B150M-HDV                   | [51120580b6](https://linux-hardware.org/?probe=51120580b6) | Jan 12, 2020 |
| Acer          | RS780DV                     | [ce332a3ede](https://linux-hardware.org/?probe=ce332a3ede) | Jan 08, 2020 |
| ASRock        | G41M-VS3                    | [746152d015](https://linux-hardware.org/?probe=746152d015) | Jan 08, 2020 |
| HP            | 3396                        | [ab6fc8a364](https://linux-hardware.org/?probe=ab6fc8a364) | Jan 05, 2020 |
| Acer          | Aspire TC-885 V:1.1         | [02c480f1df](https://linux-hardware.org/?probe=02c480f1df) | Jan 04, 2020 |
| Dell          | 0TY565                      | [f4507c2fdb](https://linux-hardware.org/?probe=f4507c2fdb) | Jan 03, 2020 |
| Gigabyte      | B365M HD3                   | [38e87e8eda](https://linux-hardware.org/?probe=38e87e8eda) | Dec 31, 2019 |
| Gigabyte      | B365M HD3                   | [27b598fbcd](https://linux-hardware.org/?probe=27b598fbcd) | Dec 31, 2019 |
| ASUSTek       | PRIME Z370-P                | [6b8999dfe2](https://linux-hardware.org/?probe=6b8999dfe2) | Dec 31, 2019 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [89c89d30f5](https://linux-hardware.org/?probe=89c89d30f5) | Dec 29, 2019 |
| ASRock        | G41M-VS3                    | [6fdb8dfe61](https://linux-hardware.org/?probe=6fdb8dfe61) | Dec 26, 2019 |
| MSI           | H81M-P33                    | [ad72c20454](https://linux-hardware.org/?probe=ad72c20454) | Dec 15, 2019 |
| Dell          | 0GXM1W A00                  | [0ef6e2666a](https://linux-hardware.org/?probe=0ef6e2666a) | Dec 12, 2019 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [94934b2da3](https://linux-hardware.org/?probe=94934b2da3) | Dec 07, 2019 |
| Pegatron      | 2A94                        | [f94ced2773](https://linux-hardware.org/?probe=f94ced2773) | Dec 05, 2019 |
| HP            | 3396                        | [aa20ad778c](https://linux-hardware.org/?probe=aa20ad778c) | Dec 01, 2019 |
| ZOTAC         | AMD HUDSON-M1               | [d26292844b](https://linux-hardware.org/?probe=d26292844b) | Nov 29, 2019 |
| Gigabyte      | G31M-ES2L                   | [cc5e341359](https://linux-hardware.org/?probe=cc5e341359) | Nov 22, 2019 |
| Packard Be... | IMEDIA L4880                | [3dc7cd311b](https://linux-hardware.org/?probe=3dc7cd311b) | Nov 21, 2019 |
| MSI           | A55M-P33                    | [ae27e5ac51](https://linux-hardware.org/?probe=ae27e5ac51) | Nov 18, 2019 |
| Pegatron      | Benicia                     | [50c16b189c](https://linux-hardware.org/?probe=50c16b189c) | Nov 15, 2019 |
| MSI           | A55M-P33                    | [29dd833843](https://linux-hardware.org/?probe=29dd833843) | Nov 14, 2019 |
| ASUSTek       | Z97-K                       | [1d74a5a6c1](https://linux-hardware.org/?probe=1d74a5a6c1) | Nov 12, 2019 |
| MSI           | Z170A XPOWER GAMING TITA... | [8868e8087f](https://linux-hardware.org/?probe=8868e8087f) | Nov 07, 2019 |
| MSI           | MS-7360                     | [d3a716b66f](https://linux-hardware.org/?probe=d3a716b66f) | Nov 03, 2019 |
| MSI           | MS-7360                     | [441f1bb5cc](https://linux-hardware.org/?probe=441f1bb5cc) | Nov 03, 2019 |
| HP            | 2820h                       | [61f956fa74](https://linux-hardware.org/?probe=61f956fa74) | Nov 02, 2019 |
| HP            | 2820h                       | [aa5b0ed445](https://linux-hardware.org/?probe=aa5b0ed445) | Nov 02, 2019 |
| HP            | 2820h                       | [2215b346af](https://linux-hardware.org/?probe=2215b346af) | Nov 02, 2019 |
| Dell          | 0RW199                      | [eec984cf36](https://linux-hardware.org/?probe=eec984cf36) | Oct 27, 2019 |
| MSI           | H81M-P33                    | [2b781a9140](https://linux-hardware.org/?probe=2b781a9140) | Oct 16, 2019 |
| MSI           | H81M-P33                    | [ebec8ad331](https://linux-hardware.org/?probe=ebec8ad331) | Oct 16, 2019 |
| Gigabyte      | 8I915P Duo                  | [62d61d6cf7](https://linux-hardware.org/?probe=62d61d6cf7) | Sep 23, 2019 |
| Gigabyte      | AB350-Gaming 3-CF           | [4c3108daed](https://linux-hardware.org/?probe=4c3108daed) | Sep 22, 2019 |
| Gigabyte      | G31M-S2C                    | [a6ba57e034](https://linux-hardware.org/?probe=a6ba57e034) | Sep 14, 2019 |
| Dell          | 0NK70N A03                  | [c7e1e32971](https://linux-hardware.org/?probe=c7e1e32971) | Sep 12, 2019 |
| MSI           | H110M PRO-D                 | [50b9ccd9d4](https://linux-hardware.org/?probe=50b9ccd9d4) | Aug 20, 2019 |
| Pegatron      | 2A94h                       | [036d8fd0d2](https://linux-hardware.org/?probe=036d8fd0d2) | Aug 11, 2019 |
| Foxconn       | 2A8C                        | [8c6027330f](https://linux-hardware.org/?probe=8c6027330f) | Aug 07, 2019 |
| Gigabyte      | B85-HD3-A                   | [49b5471963](https://linux-hardware.org/?probe=49b5471963) | Aug 06, 2019 |
| ASRock        | H81M-VG4 R2.0               | [5df54937af](https://linux-hardware.org/?probe=5df54937af) | Aug 01, 2019 |
| ASRock        | H81M-VG4 R2.0               | [fde713212c](https://linux-hardware.org/?probe=fde713212c) | Aug 01, 2019 |
| ASRock        | H81M-VG4 R2.0               | [f59241f4fe](https://linux-hardware.org/?probe=f59241f4fe) | Aug 01, 2019 |
| ASUSTek       | Z170 PRO GAMING             | [6dc8d77438](https://linux-hardware.org/?probe=6dc8d77438) | Jul 30, 2019 |
| Pegatron      | 2A73h                       | [dd83d661bd](https://linux-hardware.org/?probe=dd83d661bd) | Jul 22, 2019 |
| Gigabyte      | A320M-H-CF                  | [be4f0a278a](https://linux-hardware.org/?probe=be4f0a278a) | Jul 20, 2019 |
| Gigabyte      | A320M-H-CF                  | [2179866533](https://linux-hardware.org/?probe=2179866533) | Jul 12, 2019 |
| ASUSTek       | P5LD2-Deluxe                | [2bf9512ad1](https://linux-hardware.org/?probe=2bf9512ad1) | Jun 29, 2019 |
| ASUSTek       | P5LD2-Deluxe                | [a14cd7c7f6](https://linux-hardware.org/?probe=a14cd7c7f6) | Jun 29, 2019 |
| Gigabyte      | P41T-D3                     | [e6c57b3382](https://linux-hardware.org/?probe=e6c57b3382) | Jun 28, 2019 |
| Foxconn       | 2A8C                        | [928d183726](https://linux-hardware.org/?probe=928d183726) | Jun 21, 2019 |
| ASUSTek       | PRIME Z370-P                | [bbf26abf59](https://linux-hardware.org/?probe=bbf26abf59) | Jun 08, 2019 |
| AMI           | Cherry Trail CR             | [b22cee1c35](https://linux-hardware.org/?probe=b22cee1c35) | Jun 03, 2019 |
| ASRock        | A320M-DVS R4.0              | [6ca9fbd415](https://linux-hardware.org/?probe=6ca9fbd415) | May 28, 2019 |
| Gigabyte      | F2A78M-HD2                  | [57098a751c](https://linux-hardware.org/?probe=57098a751c) | May 23, 2019 |
| Dell          | 0Y7WYT A00                  | [5e6308d089](https://linux-hardware.org/?probe=5e6308d089) | May 21, 2019 |
| ASRock        | H97 Pro4                    | [3ce2141ee6](https://linux-hardware.org/?probe=3ce2141ee6) | May 20, 2019 |
| ASUSTek       | ROG Maximus X HERO          | [d7d3d4f56b](https://linux-hardware.org/?probe=d7d3d4f56b) | May 19, 2019 |
| MSI           | Z270 GAMING PRO CARBON      | [8a74ee23bc](https://linux-hardware.org/?probe=8a74ee23bc) | May 17, 2019 |
| Foxconn       | 945 7AE Series              | [3845e956b9](https://linux-hardware.org/?probe=3845e956b9) | May 07, 2019 |
| HP            | 3397                        | [6ae2115a36](https://linux-hardware.org/?probe=6ae2115a36) | Apr 30, 2019 |
| ASUSTek       | A88X-PLUS                   | [a9fe63d8fe](https://linux-hardware.org/?probe=a9fe63d8fe) | Apr 30, 2019 |
| MSI           | G31TM-P21                   | [99777b72f9](https://linux-hardware.org/?probe=99777b72f9) | Apr 26, 2019 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [cf5404d629](https://linux-hardware.org/?probe=cf5404d629) | Apr 19, 2019 |
| ASUSTek       | P5B-Premium                 | [40f56d3108](https://linux-hardware.org/?probe=40f56d3108) | Apr 14, 2019 |
| Dell          | 02YYK5 A01                  | [9dcd7b3dd8](https://linux-hardware.org/?probe=9dcd7b3dd8) | Apr 10, 2019 |
| ASUSTek       | P5B-Premium                 | [90ab4e39e8](https://linux-hardware.org/?probe=90ab4e39e8) | Apr 07, 2019 |
| ASUSTek       | Maximus IV Extreme-Z        | [995bc4566a](https://linux-hardware.org/?probe=995bc4566a) | Apr 04, 2019 |
| ASUSTek       | P5K SE                      | [31de6cd2d0](https://linux-hardware.org/?probe=31de6cd2d0) | Mar 30, 2019 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [41b11ce878](https://linux-hardware.org/?probe=41b11ce878) | Mar 27, 2019 |
| Gigabyte      | P61A-D3                     | [16fcc7801b](https://linux-hardware.org/?probe=16fcc7801b) | Mar 17, 2019 |
| ASUSTek       | A88XM-A                     | [42af7fc1f3](https://linux-hardware.org/?probe=42af7fc1f3) | Mar 14, 2019 |
| MSI           | MS-7346                     | [3baabb1753](https://linux-hardware.org/?probe=3baabb1753) | Mar 14, 2019 |
| ASRock        | B150 Gaming K4/Hyper        | [fcd2e0fac9](https://linux-hardware.org/?probe=fcd2e0fac9) | Mar 05, 2019 |
| Dell          | 0KRC95 A02                  | [a1988b9c4d](https://linux-hardware.org/?probe=a1988b9c4d) | Jan 30, 2019 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [cb29bdbf2d](https://linux-hardware.org/?probe=cb29bdbf2d) | Jan 28, 2019 |
| ASUSTek       | A88XM-A                     | [8727337204](https://linux-hardware.org/?probe=8727337204) | Jan 03, 2019 |
| MSI           | GF615M-P33                  | [5ea14f0cad](https://linux-hardware.org/?probe=5ea14f0cad) | Dec 06, 2018 |
| Gigabyte      | A320M-S2H-CF                | [0dc3a4c1d2](https://linux-hardware.org/?probe=0dc3a4c1d2) | Nov 25, 2018 |
| Gigabyte      | A320M-S2H-CF                | [d50f5a68ba](https://linux-hardware.org/?probe=d50f5a68ba) | Nov 25, 2018 |
| Gigabyte      | A320M-S2H-CF                | [a72d5458ff](https://linux-hardware.org/?probe=a72d5458ff) | Nov 23, 2018 |
| Gigabyte      | X48-DS5                     | [c40e02daf8](https://linux-hardware.org/?probe=c40e02daf8) | Nov 23, 2018 |
| Gigabyte      | GA-MA74GM-S2H               | [ce695c7b55](https://linux-hardware.org/?probe=ce695c7b55) | Nov 18, 2018 |
| ASRock        | 970A-G                      | [c94c26c4fe](https://linux-hardware.org/?probe=c94c26c4fe) | Nov 17, 2018 |
| ASRock        | 970A-G                      | [eafdda2dc2](https://linux-hardware.org/?probe=eafdda2dc2) | Nov 17, 2018 |
| Gigabyte      | H55M-S2                     | [cdc9ee702d](https://linux-hardware.org/?probe=cdc9ee702d) | Nov 17, 2018 |
| Gigabyte      | H61M-S1                     | [66f67078ab](https://linux-hardware.org/?probe=66f67078ab) | Nov 13, 2018 |
| MSI           | MS-7346                     | [5a3b5f371e](https://linux-hardware.org/?probe=5a3b5f371e) | Nov 06, 2018 |
| Gigabyte      | EP41-UD3L                   | [0dcbf3f2de](https://linux-hardware.org/?probe=0dcbf3f2de) | Oct 25, 2018 |
| Gigabyte      | X48-DS5                     | [fcc7ff886e](https://linux-hardware.org/?probe=fcc7ff886e) | Sep 30, 2018 |
| MSI           | MS-7346                     | [faf555551b](https://linux-hardware.org/?probe=faf555551b) | Sep 26, 2018 |
| Gigabyte      | X48-DS5                     | [c02908e70d](https://linux-hardware.org/?probe=c02908e70d) | Sep 19, 2018 |
| MSI           | H110M PRO-D                 | [da7af8d522](https://linux-hardware.org/?probe=da7af8d522) | Sep 19, 2018 |
| Foxconn       | 2A8C                        | [82d6455d21](https://linux-hardware.org/?probe=82d6455d21) | Sep 19, 2018 |
| MSI           | MS-7346                     | [b3c93d2eb7](https://linux-hardware.org/?probe=b3c93d2eb7) | May 31, 2018 |
| MSI           | MS-7346                     | [545037fda5](https://linux-hardware.org/?probe=545037fda5) | May 31, 2018 |
| Gigabyte      | G31M-S2L                    | [cb713e1fdc](https://linux-hardware.org/?probe=cb713e1fdc) | May 16, 2018 |
| Gigabyte      | AX370-Gaming 5              | [2f17066f92](https://linux-hardware.org/?probe=2f17066f92) | Mar 19, 2018 |
| Gigabyte      | AX370-Gaming 5              | [69127de08f](https://linux-hardware.org/?probe=69127de08f) | Mar 16, 2018 |
| ASUSTek       | H110M-K                     | [978f84d6c0](https://linux-hardware.org/?probe=978f84d6c0) | Mar 13, 2018 |
| ABIT          | IP35                        | [0bb2462820](https://linux-hardware.org/?probe=0bb2462820) | Feb 24, 2018 |
| MSI           | G41M4                       | [a00139a613](https://linux-hardware.org/?probe=a00139a613) | Feb 20, 2018 |
| Gigabyte      | EP43-UD3L                   | [585d110911](https://linux-hardware.org/?probe=585d110911) | Dec 17, 2017 |
| MSI           | G41M4                       | [36c4e313ac](https://linux-hardware.org/?probe=36c4e313ac) | Dec 08, 2017 |
| ASUSTek       | H110M-K                     | [6d7e86c85a](https://linux-hardware.org/?probe=6d7e86c85a) | Dec 08, 2017 |
| ASUSTek       | M3A78 PRO                   | [2c258a2915](https://linux-hardware.org/?probe=2c258a2915) | Dec 07, 2017 |
| ASRock        | H81M-HDS                    | [ab1774560b](https://linux-hardware.org/?probe=ab1774560b) | Dec 05, 2017 |
| ASUSTek       | P5K SE                      | [40bd9b1ada](https://linux-hardware.org/?probe=40bd9b1ada) | Oct 26, 2017 |
| Gigabyte      | H110M-DS2-CF                | [6d0e45f3ce](https://linux-hardware.org/?probe=6d0e45f3ce) | Sep 19, 2017 |
| MSI           | 2A78h                       | [11214e5016](https://linux-hardware.org/?probe=11214e5016) | May 31, 2017 |
| MSI           | G41M4                       | [238edf60a9](https://linux-hardware.org/?probe=238edf60a9) | May 13, 2017 |
| Foxconn       | 2A8C                        | [40bd4d1f0c](https://linux-hardware.org/?probe=40bd4d1f0c) | Apr 22, 2017 |
| ASRock        | B85M-DGS                    | [e85a15a247](https://linux-hardware.org/?probe=e85a15a247) | Apr 02, 2017 |
| HP            | 3029h                       | [3a677087d4](https://linux-hardware.org/?probe=3a677087d4) | Mar 11, 2017 |
| Gigabyte      | P75-D3                      | [c489105947](https://linux-hardware.org/?probe=c489105947) | Mar 10, 2017 |
| Gigabyte      | P75-D3                      | [185a41377a](https://linux-hardware.org/?probe=185a41377a) | Mar 10, 2017 |
| Gigabyte      | EP35-DS3                    | [a9bf5b385b](https://linux-hardware.org/?probe=a9bf5b385b) | Mar 09, 2017 |
| ASRock        | B85 Killer                  | [a59bf1823c](https://linux-hardware.org/?probe=a59bf1823c) | Feb 24, 2017 |
| ASRock        | B150M-HDV                   | [d95ccebd88](https://linux-hardware.org/?probe=d95ccebd88) | Feb 08, 2017 |
| Gigabyte      | B250-HD3P-CF                | [6126e55d1a](https://linux-hardware.org/?probe=6126e55d1a) | Jan 19, 2017 |
| ASRock        | B150M-HDV                   | [14e2cbe871](https://linux-hardware.org/?probe=14e2cbe871) | Jan 10, 2017 |
| Gigabyte      | EP45-DS3R                   | [86b3438b9e](https://linux-hardware.org/?probe=86b3438b9e) | Dec 05, 2016 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Romania/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 63       | 9.5%    |
| Ubuntu 18.04                 | 37       | 5.58%   |
| BlackPanther 18.1            | 32       | 4.83%   |
| Ubuntu 22.04                 | 31       | 4.68%   |
| OpenMandriva 4.2             | 22       | 3.32%   |
| OpenMandriva 4.3             | 21       | 3.17%   |
| Manjaro                      | 14       | 2.11%   |
| Debian 11                    | 13       | 1.96%   |
| Arch Rolling                 | 13       | 1.96%   |
| ROSA R10                     | 11       | 1.66%   |
| ArcoLinux Rolling            | 11       | 1.66%   |
| Arch                         | 10       | 1.51%   |
| Xubuntu 20.04                | 8        | 1.21%   |
| Pop!_OS 20.04                | 8        | 1.21%   |
| Linux Mint 21.1              | 8        | 1.21%   |
| Linux Mint 20.2              | 8        | 1.21%   |
| Debian 12                    | 8        | 1.21%   |
| Zorin 16                     | 7        | 1.06%   |
| ROSA R11                     | 7        | 1.06%   |
| Pop!_OS 22.04                | 7        | 1.06%   |
| OpenMandriva 23.01           | 7        | 1.06%   |
| Ubuntu 19.10                 | 6        | 0.9%    |
| Pop!_OS 20.10                | 6        | 0.9%    |
| KDE neon 20.04               | 6        | 0.9%    |
| Fedora 37                    | 6        | 0.9%    |
| Fedora 35                    | 6        | 0.9%    |
| Fedora 31                    | 6        | 0.9%    |
| Ubuntu 21.04                 | 5        | 0.75%   |
| Ubuntu 20.10                 | 5        | 0.75%   |
| Ubuntu 19.04                 | 5        | 0.75%   |
| ROSA R9                      | 5        | 0.75%   |
| ROSA R8                      | 5        | 0.75%   |
| Pop!_OS 21.10                | 5        | 0.75%   |
| openSUSE Tumbleweed-XXXXXXXX | 5        | 0.75%   |
| OpenMandriva 23.03           | 5        | 0.75%   |
| Linux Mint 20.1              | 5        | 0.75%   |
| Debian 10                    | 5        | 0.75%   |
| Ubuntu 18.10                 | 4        | 0.6%    |
| ROSA R11.1                   | 4        | 0.6%    |
| Pop!_OS 21.04                | 4        | 0.6%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 160      | 25.72%  |
| OpenMandriva  | 73       | 11.74%  |
| Linux Mint    | 39       | 6.27%   |
| Fedora        | 36       | 5.79%   |
| BlackPanther  | 33       | 5.31%   |
| ROSA          | 31       | 4.98%   |
| Endless       | 30       | 4.82%   |
| Pop!_OS       | 29       | 4.66%   |
| Debian        | 28       | 4.5%    |
| Manjaro       | 25       | 4.02%   |
| Arch          | 23       | 3.7%    |
| Zorin         | 13       | 2.09%   |
| ArcoLinux     | 12       | 1.93%   |
| KDE neon      | 10       | 1.61%   |
| Xubuntu       | 8        | 1.29%   |
| Kubuntu       | 8        | 1.29%   |
| openSUSE      | 7        | 1.13%   |
| Gentoo        | 5        | 0.8%    |
| Clear Linux   | 5        | 0.8%    |
| Ubuntu Unity  | 4        | 0.64%   |
| Ubuntu Budgie | 3        | 0.48%   |
| Solus         | 3        | 0.48%   |
| Garuda Linux  | 3        | 0.48%   |
| CentOS        | 3        | 0.48%   |
| Xero          | 2        | 0.32%   |
| Ubuntu MATE   | 2        | 0.32%   |
| Peppermint    | 2        | 0.32%   |
| Nobara        | 2        | 0.32%   |
| Lubuntu       | 2        | 0.32%   |
| Kali          | 2        | 0.32%   |
| EndeavourOS   | 2        | 0.32%   |
| Elementary    | 2        | 0.32%   |
| AlmaLinux     | 2        | 0.32%   |
| Ultramarine   | 1        | 0.16%   |
| Ubuntu Studio | 1        | 0.16%   |
| TUXEDO OS     | 1        | 0.16%   |
| SteamOS       | 1        | 0.16%   |
| Redcore       | 1        | 0.16%   |
| Parrot        | 1        | 0.16%   |
| Oracle Linux  | 1        | 0.16%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Desktops | Percent |
|---------------------------------|----------|---------|
| 4.18.16-desktop-1bP             | 26       | 3.56%   |
| 5.10.14-desktop-1omv4002        | 21       | 2.87%   |
| 5.16.7-desktop-1omv4003         | 17       | 2.33%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 10       | 1.37%   |
| 5.4.0-42-generic                | 8        | 1.09%   |
| 5.15.0-58-generic               | 8        | 1.09%   |
| 6.1.1-desktop-1omv2290          | 7        | 0.96%   |
| 5.8.0-14-generic                | 7        | 0.96%   |
| 5.6.14-desktop-2bP              | 7        | 0.96%   |
| 5.4.0-40-generic                | 7        | 0.96%   |
| 6.3.5-desktop-3omv2390          | 6        | 0.82%   |
| 6.2.6-desktop-1omv2390          | 6        | 0.82%   |
| 6.2.0-36-generic                | 5        | 0.68%   |
| 5.4.0-74-generic                | 5        | 0.68%   |
| 5.4.0-72-generic                | 5        | 0.68%   |
| 5.4.0-52-generic                | 5        | 0.68%   |
| 5.4.0-29-generic                | 5        | 0.68%   |
| 5.3.0-28-generic                | 5        | 0.68%   |
| 5.16.13-desktop-1omv4003        | 5        | 0.68%   |
| 6.6.2-desktop-1omv2390          | 4        | 0.55%   |
| 6.5.0-14-generic                | 4        | 0.55%   |
| 5.8.0-7630-generic              | 4        | 0.55%   |
| 5.4.0-89-generic                | 4        | 0.55%   |
| 5.4.0-7634-generic              | 4        | 0.55%   |
| 5.4.0-66-generic                | 4        | 0.55%   |
| 5.4.0-51-generic                | 4        | 0.55%   |
| 5.4.0-48-generic                | 4        | 0.55%   |
| 5.4.0-47-generic                | 4        | 0.55%   |
| 5.4.0-19-generic                | 4        | 0.55%   |
| 5.3.0-46-generic                | 4        | 0.55%   |
| 5.3.0-23-generic                | 4        | 0.55%   |
| 5.3.0-19-generic                | 4        | 0.55%   |
| 5.11.0-34-generic               | 4        | 0.55%   |
| 4.15.0-50-generic               | 4        | 0.55%   |
| 6.4.11-desktop-1omv2390         | 3        | 0.41%   |
| 6.2.0-39-generic                | 3        | 0.41%   |
| 5.8.0-7642-generic              | 3        | 0.41%   |
| 5.4.0-91-generic                | 3        | 0.41%   |
| 5.4.0-77-generic                | 3        | 0.41%   |
| 5.4.0-54-generic                | 3        | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 95       | 13.69%  |
| 5.15.0  | 40       | 5.76%   |
| 4.15.0  | 35       | 5.04%   |
| 5.8.0   | 29       | 4.18%   |
| 5.11.0  | 28       | 4.03%   |
| 4.18.16 | 26       | 3.75%   |
| 5.3.0   | 25       | 3.6%    |
| 5.10.14 | 21       | 3.03%   |
| 5.16.7  | 17       | 2.45%   |
| 5.10.0  | 15       | 2.16%   |
| 5.0.0   | 15       | 2.16%   |
| 6.2.0   | 14       | 2.02%   |
| 5.19.0  | 14       | 2.02%   |
| 4.18.0  | 13       | 1.87%   |
| 6.1.0   | 10       | 1.44%   |
| 4.9.60  | 10       | 1.44%   |
| 6.5.0   | 9        | 1.3%    |
| 5.13.0  | 9        | 1.3%    |
| 6.1.1   | 8        | 1.15%   |
| 5.6.14  | 7        | 1.01%   |
| 6.3.5   | 6        | 0.86%   |
| 6.2.6   | 6        | 0.86%   |
| 6.0.11  | 6        | 0.86%   |
| 4.9.20  | 6        | 0.86%   |
| 5.8.18  | 5        | 0.72%   |
| 5.16.13 | 5        | 0.72%   |
| 6.6.2   | 4        | 0.58%   |
| 6.5.5   | 4        | 0.58%   |
| 6.4.11  | 4        | 0.58%   |
| 6.0.12  | 4        | 0.58%   |
| 5.15.12 | 4        | 0.58%   |
| 4.19.0  | 4        | 0.58%   |
| 6.1.12  | 3        | 0.43%   |
| 5.18.10 | 3        | 0.43%   |
| 5.16.11 | 3        | 0.43%   |
| 4.9.76  | 3        | 0.43%   |
| 4.9.155 | 3        | 0.43%   |
| 4.1.34  | 3        | 0.43%   |
| 6.6.8   | 2        | 0.29%   |
| 6.6.11  | 2        | 0.29%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 109      | 16.05%  |
| 5.15    | 57       | 8.39%   |
| 5.8     | 42       | 6.19%   |
| 5.10    | 40       | 5.89%   |
| 4.18    | 39       | 5.74%   |
| 4.15    | 35       | 5.15%   |
| 5.11    | 32       | 4.71%   |
| 5.16    | 30       | 4.42%   |
| 6.1     | 27       | 3.98%   |
| 5.3     | 27       | 3.98%   |
| 6.2     | 23       | 3.39%   |
| 6.5     | 22       | 3.24%   |
| 4.9     | 22       | 3.24%   |
| 5.19    | 18       | 2.65%   |
| 5.0     | 18       | 2.65%   |
| 6.0     | 17       | 2.5%    |
| 5.6     | 13       | 1.91%   |
| 5.13    | 12       | 1.77%   |
| 6.6     | 11       | 1.62%   |
| 5.18    | 11       | 1.62%   |
| 6.4     | 9        | 1.33%   |
| 6.3     | 9        | 1.33%   |
| 5.14    | 9        | 1.33%   |
| 5.9     | 7        | 1.03%   |
| 5.17    | 7        | 1.03%   |
| 5.12    | 6        | 0.88%   |
| 4.19    | 5        | 0.74%   |
| 4.1     | 5        | 0.74%   |
| 5.7     | 4        | 0.59%   |
| 5.2     | 3        | 0.44%   |
| 5.5     | 2        | 0.29%   |
| 4.8     | 2        | 0.29%   |
| 4.13    | 2        | 0.29%   |
| 6.7     | 1        | 0.15%   |
| 5.1     | 1        | 0.15%   |
| 4.4     | 1        | 0.15%   |
| 4.14    | 1        | 0.15%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 591      | 99.16%  |
| i686   | 5        | 0.84%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 247      | 39.33%  |
| KDE5            | 164      | 26.11%  |
| Unknown         | 71       | 11.31%  |
| XFCE            | 34       | 5.41%   |
| X-Cinnamon      | 29       | 4.62%   |
| KDE4            | 18       | 2.87%   |
| KDE             | 16       | 2.55%   |
| LXQt            | 11       | 1.75%   |
| MATE            | 9        | 1.43%   |
| LXDE            | 6        | 0.96%   |
| Unity           | 4        | 0.64%   |
| i3              | 4        | 0.64%   |
| Cinnamon        | 4        | 0.64%   |
| Budgie          | 3        | 0.48%   |
| sway            | 1        | 0.16%   |
| sussy_bspwm     | 1        | 0.16%   |
| Pantheon        | 1        | 0.16%   |
| GNUstep         | 1        | 0.16%   |
| GNOME Flashback | 1        | 0.16%   |
| dusk            | 1        | 0.16%   |
| Deepin          | 1        | 0.16%   |
| awesome         | 1        | 0.16%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| X11         | 472      | 76.75%  |
| Wayland     | 89       | 14.47%  |
| Unknown     | 41       | 6.67%   |
| Tty         | 12       | 1.95%   |
| Unspecified | 1        | 0.16%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 295      | 46.97%  |
| SDDM    | 153      | 24.36%  |
| GDM     | 53       | 8.44%   |
| GDM3    | 51       | 8.12%   |
| LightDM | 42       | 6.69%   |
| KDM     | 19       | 3.03%   |
| TDM     | 12       | 1.91%   |
| XDM     | 1        | 0.16%   |
| Ly      | 1        | 0.16%   |
| LXDM    | 1        | 0.16%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| en_US       | 361      | 59.08%  |
| Unknown     | 112      | 18.33%  |
| ro_RO       | 103      | 16.86%  |
| en_GB       | 10       | 1.64%   |
| C           | 7        | 1.15%   |
| hu_HU       | 6        | 0.98%   |
| fr_FR       | 3        | 0.49%   |
| de_DE       | 2        | 0.33%   |
| ru_RU       | 1        | 0.16%   |
| it_IT       | 1        | 0.16%   |
| es_ES       | 1        | 0.16%   |
| en_US.UTF8  | 1        | 0.16%   |
| en_US.utf-8 | 1        | 0.16%   |
| en_IN       | 1        | 0.16%   |
| en_DE       | 1        | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 370      | 61.26%  |
| EFI  | 234      | 38.74%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 417      | 67.92%  |
| Overlay | 78       | 12.7%   |
| Unknown | 41       | 6.68%   |
| Btrfs   | 39       | 6.35%   |
| Tmpfs   | 18       | 2.93%   |
| Xfs     | 12       | 1.95%   |
| Zfs     | 4        | 0.65%   |
| F2fs    | 2        | 0.33%   |
| Jfs     | 1        | 0.16%   |
| Ext3    | 1        | 0.16%   |
| Ext2    | 1        | 0.16%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 294      | 48.28%  |
| GPT     | 198      | 32.51%  |
| MBR     | 117      | 19.21%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 490      | 79.67%  |
| Yes       | 125      | 20.33%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 411      | 67.38%  |
| Yes       | 199      | 32.62%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 138      | 23.19%  |
| ASUSTek Computer    | 136      | 22.86%  |
| MSI                 | 67       | 11.26%  |
| Hewlett-Packard     | 52       | 8.74%   |
| ASRock              | 49       | 8.24%   |
| Dell                | 46       | 7.73%   |
| Lenovo              | 26       | 4.37%   |
| Acer                | 20       | 3.36%   |
| Intel               | 10       | 1.68%   |
| Fujitsu             | 8        | 1.34%   |
| Fujitsu Siemens     | 6        | 1.01%   |
| Foxconn             | 6        | 1.01%   |
| Pegatron            | 5        | 0.84%   |
| Unknown             | 5        | 0.84%   |
| WesternDigital      | 2        | 0.34%   |
| Complet             | 2        | 0.34%   |
| ZOTAC               | 1        | 0.17%   |
| Packard Bell        | 1        | 0.17%   |
| OEM_MB              | 1        | 0.17%   |
| Medion              | 1        | 0.17%   |
| IBM                 | 1        | 0.17%   |
| Huanan              | 1        | 0.17%   |
| Gateway             | 1        | 0.17%   |
| ECS                 | 1        | 0.17%   |
| Daewoo Lucoms       | 1        | 0.17%   |
| Biostar             | 1        | 0.17%   |
| BESSTAR Tech        | 1        | 0.17%   |
| AZW                 | 1        | 0.17%   |
| ASRockRack          | 1        | 0.17%   |
| Apple               | 1        | 0.17%   |
| AMI                 | 1        | 0.17%   |
| Alienware           | 1        | 0.17%   |
| ABIT                | 1        | 0.17%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| ASUS All Series                        | 17       | 2.86%   |
| Acer Veriton L670G                     | 10       | 1.68%   |
| Gigabyte B450M DS3H                    | 7        | 1.18%   |
| ASUS PRIME A320M-K                     | 6        | 1.01%   |
| Unknown                                | 5        | 0.84%   |
| MSI MS-7996                            | 4        | 0.67%   |
| MSI MS-7721                            | 4        | 0.67%   |
| Gigabyte X470 AORUS ULTRA GAMING       | 4        | 0.67%   |
| Dell OptiPlex 7010                     | 4        | 0.67%   |
| MSI MS-7C37                            | 3        | 0.5%    |
| HP Compaq Elite 8300 SFF               | 3        | 0.5%    |
| Gigabyte X570 AORUS ELITE              | 3        | 0.5%    |
| Gigabyte TRX40 AORUS MASTER            | 3        | 0.5%    |
| Gigabyte B450 AORUS M                  | 3        | 0.5%    |
| Gigabyte A320M-S2H                     | 3        | 0.5%    |
| Dell Precision WorkStation T3500       | 3        | 0.5%    |
| Dell OptiPlex 780                      | 3        | 0.5%    |
| Dell OptiPlex 755                      | 3        | 0.5%    |
| Dell OptiPlex 3010                     | 3        | 0.5%    |
| ASUS Z170 PRO GAMING                   | 3        | 0.5%    |
| ASUS PRIME X470-PRO                    | 3        | 0.5%    |
| ASUS PRIME H310M-R R2.0                | 3        | 0.5%    |
| ASRock G41M-VS3                        | 3        | 0.5%    |
| WesternDigital WDBNFA0000NBK-00        | 2        | 0.34%   |
| MSI MS-7C94                            | 2        | 0.34%   |
| MSI MS-7C52                            | 2        | 0.34%   |
| MSI MS-7C02                            | 2        | 0.34%   |
| MSI MS-7B86                            | 2        | 0.34%   |
| MSI MS-7B38                            | 2        | 0.34%   |
| MSI MS-7A34                            | 2        | 0.34%   |
| MSI MS-7817                            | 2        | 0.34%   |
| MSI MS-7816                            | 2        | 0.34%   |
| MSI MS-7596                            | 2        | 0.34%   |
| Lenovo ThinkCentre M83 10AHS0FM00      | 2        | 0.34%   |
| Lenovo ThinkCentre M73 10AXS04G01      | 2        | 0.34%   |
| HP EliteDesk 800 G1 SFF                | 2        | 0.34%   |
| HP Compaq dc7900 Small Form Factor     | 2        | 0.34%   |
| HP Compaq dc7900 Convertible Minitower | 2        | 0.34%   |
| HP Compaq dc7800p Small Form Factor    | 2        | 0.34%   |
| HP Compaq dc5800 Small Form Factor     | 2        | 0.34%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| ASUS PRIME                      | 35       | 5.88%   |
| HP Compaq                       | 33       | 5.55%   |
| Dell OptiPlex                   | 32       | 5.38%   |
| Lenovo ThinkCentre              | 18       | 3.03%   |
| ASUS ROG                        | 17       | 2.86%   |
| ASUS All                        | 17       | 2.86%   |
| Acer Veriton                    | 15       | 2.52%   |
| Gigabyte B450M                  | 9        | 1.51%   |
| ASUS TUF                        | 8        | 1.34%   |
| Gigabyte X570                   | 7        | 1.18%   |
| Fujitsu ESPRIMO                 | 7        | 1.18%   |
| Dell Precision                  | 7        | 1.18%   |
| HP ProDesk                      | 5        | 0.84%   |
| HP EliteDesk                    | 5        | 0.84%   |
| Gigabyte B450                   | 5        | 0.84%   |
| Unknown                         | 5        | 0.84%   |
| MSI MS-7996                     | 4        | 0.67%   |
| MSI MS-7721                     | 4        | 0.67%   |
| Gigabyte Z390                   | 4        | 0.67%   |
| Gigabyte X470                   | 4        | 0.67%   |
| Gigabyte TRX40                  | 4        | 0.67%   |
| Gigabyte B550M                  | 4        | 0.67%   |
| Fujitsu Siemens ESPRIMO         | 4        | 0.67%   |
| ASUS Pro                        | 4        | 0.67%   |
| ASUS Maximus                    | 4        | 0.67%   |
| MSI MS-7C37                     | 3        | 0.5%    |
| Gigabyte GA-78LMT-USB3          | 3        | 0.5%    |
| Gigabyte A320M-S2H              | 3        | 0.5%    |
| Dell PowerEdge                  | 3        | 0.5%    |
| ASUS Z170                       | 3        | 0.5%    |
| ASUS M5A78L-M                   | 3        | 0.5%    |
| ASRock X670E                    | 3        | 0.5%    |
| ASRock G41M-VS3                 | 3        | 0.5%    |
| WesternDigital WDBNFA0000NBK-00 | 2        | 0.34%   |
| Pegatron Pro                    | 2        | 0.34%   |
| MSI MS-7C94                     | 2        | 0.34%   |
| MSI MS-7C52                     | 2        | 0.34%   |
| MSI MS-7C02                     | 2        | 0.34%   |
| MSI MS-7B86                     | 2        | 0.34%   |
| MSI MS-7B38                     | 2        | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 72       | 12.1%   |
| 2013 | 47       | 7.9%    |
| 2008 | 44       | 7.39%   |
| 2012 | 43       | 7.23%   |
| 2020 | 42       | 7.06%   |
| 2019 | 40       | 6.72%   |
| 2017 | 38       | 6.39%   |
| 2015 | 36       | 6.05%   |
| 2014 | 36       | 6.05%   |
| 2011 | 36       | 6.05%   |
| 2009 | 31       | 5.21%   |
| 2007 | 29       | 4.87%   |
| 2021 | 28       | 4.71%   |
| 2010 | 25       | 4.2%    |
| 2016 | 23       | 3.87%   |
| 2022 | 13       | 2.18%   |
| 2006 | 5        | 0.84%   |
| 2005 | 4        | 0.67%   |
| 2023 | 2        | 0.34%   |
| 2004 | 1        | 0.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 595      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 590      | 98.83%  |
| Enabled  | 7        | 1.17%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 595      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 8.01-16.0       | 132      | 21.5%   |
| 3.01-4.0        | 118      | 19.22%  |
| 16.01-24.0      | 116      | 18.89%  |
| 32.01-64.0      | 86       | 14.01%  |
| 4.01-8.0        | 80       | 13.03%  |
| 64.01-256.0     | 36       | 5.86%   |
| 1.01-2.0        | 25       | 4.07%   |
| 24.01-32.0      | 12       | 1.95%   |
| 2.01-3.0        | 4        | 0.65%   |
| 0.51-1.0        | 3        | 0.49%   |
| More than 256.0 | 2        | 0.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 226      | 33.68%  |
| 2.01-3.0    | 157      | 23.4%   |
| 3.01-4.0    | 80       | 11.92%  |
| 4.01-8.0    | 77       | 11.48%  |
| 0.51-1.0    | 62       | 9.24%   |
| 8.01-16.0   | 32       | 4.77%   |
| 0.01-0.5    | 27       | 4.02%   |
| 16.01-24.0  | 5        | 0.75%   |
| 32.01-64.0  | 2        | 0.3%    |
| 64.01-256.0 | 2        | 0.3%    |
| 24.01-32.0  | 1        | 0.15%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 260      | 41.27%  |
| 2      | 169      | 26.83%  |
| 3      | 94       | 14.92%  |
| 4      | 53       | 8.41%   |
| 5      | 26       | 4.13%   |
| 6      | 8        | 1.27%   |
| 0      | 5        | 0.79%   |
| 9      | 4        | 0.63%   |
| 8      | 3        | 0.48%   |
| 7      | 3        | 0.48%   |
| 24     | 1        | 0.16%   |
| 15     | 1        | 0.16%   |
| 14     | 1        | 0.16%   |
| 11     | 1        | 0.16%   |
| 10     | 1        | 0.16%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 326      | 54.06%  |
| Yes       | 277      | 45.94%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 591      | 99.33%  |
| No        | 4        | 0.67%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 412      | 68.1%   |
| Yes       | 193      | 31.9%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 467      | 77.19%  |
| Yes       | 138      | 22.81%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Romania | 595      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Bucharest        | 177      | 28.1%   |
| Cluj-Napoca      | 45       | 7.14%   |
| Iasi             | 27       | 4.29%   |
| Timișoara       | 26       | 4.13%   |
| Târgu Mureş    | 20       | 3.17%   |
| Brasov           | 18       | 2.86%   |
| Sibiu            | 16       | 2.54%   |
| Oradea           | 16       | 2.54%   |
| Baia Mare        | 13       | 2.06%   |
| Arad             | 13       | 2.06%   |
| Constanța       | 11       | 1.75%   |
| Zalău           | 10       | 1.59%   |
| Craiova          | 9        | 1.43%   |
| Satu Mare        | 8        | 1.27%   |
| Ploieşti        | 8        | 1.27%   |
| Piatra Neamţ    | 8        | 1.27%   |
| Galati           | 7        | 1.11%   |
| Targoviste       | 6        | 0.95%   |
| Râmnicu Vâlcea | 6        | 0.95%   |
| Popesti-Leordeni | 6        | 0.95%   |
| Piteşti         | 6        | 0.95%   |
| Miercurea-Ciuc   | 6        | 0.95%   |
| Bacau            | 6        | 0.95%   |
| Voluntari        | 5        | 0.79%   |
| Tulcea           | 5        | 0.79%   |
| Braila           | 5        | 0.79%   |
| Otopeni          | 4        | 0.63%   |
| Floresti         | 4        | 0.63%   |
| Botosani         | 4        | 0.63%   |
| Beiuș           | 4        | 0.63%   |
| Alexandria       | 4        | 0.63%   |
| Târgu Jiu       | 3        | 0.48%   |
| Sfantu Gheorghe  | 3        | 0.48%   |
| Reşiţa         | 3        | 0.48%   |
| Mogosoaia        | 3        | 0.48%   |
| Mediaş          | 3        | 0.48%   |
| Focşani         | 3        | 0.48%   |
| Buzau            | 3        | 0.48%   |
| Alba Iulia       | 3        | 0.48%   |
| Urziceni         | 2        | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 226      | 384    | 20.45%  |
| Seagate                     | 199      | 349    | 18.01%  |
| Kingston                    | 150      | 225    | 13.57%  |
| Samsung Electronics         | 140      | 218    | 12.67%  |
| A-DATA Technology           | 48       | 67     | 4.34%   |
| Toshiba                     | 47       | 64     | 4.25%   |
| Hitachi                     | 32       | 49     | 2.9%    |
| Crucial                     | 23       | 31     | 2.08%   |
| Intel                       | 20       | 23     | 1.81%   |
| SanDisk                     | 17       | 25     | 1.54%   |
| Maxtor                      | 17       | 24     | 1.54%   |
| Unknown                     | 13       | 16     | 1.18%   |
| HGST                        | 13       | 23     | 1.18%   |
| Patriot                     | 11       | 14     | 1%      |
| Kingston Technology Company | 10       | 12     | 0.9%    |
| SPCC                        | 9        | 12     | 0.81%   |
| Hewlett-Packard             | 9        | 11     | 0.81%   |
| OCZ                         | 8        | 16     | 0.72%   |
| XPG                         | 7        | 10     | 0.63%   |
| Transcend                   | 6        | 8      | 0.54%   |
| Team                        | 6        | 6      | 0.54%   |
| Silicon Motion              | 6        | 8      | 0.54%   |
| Phison                      | 6        | 8      | 0.54%   |
| Kingmax                     | 6        | 7      | 0.54%   |
| Gigabyte Technology         | 6        | 10     | 0.54%   |
| Phison Electronics          | 5        | 6      | 0.45%   |
| SK hynix                    | 4        | 5      | 0.36%   |
| Plextor                     | 4        | 5      | 0.36%   |
| Micron/Crucial Technology   | 4        | 5      | 0.36%   |
| GOODRAM                     | 4        | 4      | 0.36%   |
| LaCie                       | 3        | 9      | 0.27%   |
| Emtec                       | 3        | 3      | 0.27%   |
| Corsair                     | 3        | 10     | 0.27%   |
| China                       | 3        | 3      | 0.27%   |
| ADATA Technology            | 3        | 3      | 0.27%   |
| Verbatim                    | 2        | 4      | 0.18%   |
| Realtek Semiconductor       | 2        | 2      | 0.18%   |
| PNY                         | 2        | 2      | 0.18%   |
| Micron Technology           | 2        | 3      | 0.18%   |
| KingFast                    | 2        | 2      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD                   | 43       | 3.41%   |
| Seagate ST1000DM010-2EP102 1TB                    | 26       | 2.06%   |
| Kingston SA400S37120G 120GB SSD                   | 24       | 1.9%    |
| Kingston SV300S37A120G 120GB SSD                  | 19       | 1.51%   |
| Kingston SA400S37480G 480GB SSD                   | 18       | 1.43%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 16       | 1.27%   |
| Seagate ST500DM002-1BD142 500GB                   | 15       | 1.19%   |
| Samsung SSD 850 EVO 250GB                         | 13       | 1.03%   |
| Samsung SSD 860 EVO 500GB                         | 12       | 0.95%   |
| Toshiba DT01ACA050 500GB                          | 11       | 0.87%   |
| WDC WD1600AAJS-22L7A0 160GB                       | 10       | 0.79%   |
| Seagate ST2000DM008-2FR102 2TB                    | 10       | 0.79%   |
| A-DATA SU650 240GB SSD                            | 10       | 0.79%   |
| Toshiba DT01ACA100 1TB                            | 9        | 0.71%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 9        | 0.71%   |
| Kingston Company A2000 NVMe SSD 500GB             | 8        | 0.63%   |
| Seagate ST2000DM006-2DM164 2TB                    | 7        | 0.55%   |
| Samsung SSD 860 EVO 250GB                         | 7        | 0.55%   |
| Patriot Burst 120GB SSD                           | 7        | 0.55%   |
| WDC WD5000AAKX-001CA0 500GB                       | 6        | 0.48%   |
| Kingston SUV400S37120G 120GB SSD                  | 6        | 0.48%   |
| WDC WD5000AADS-00S9B0 500GB                       | 5        | 0.4%    |
| WDC WD10EZEX-21WN4A0 1TB                          | 5        | 0.4%    |
| WDC WD10EZEX-00WN4A0 1TB                          | 5        | 0.4%    |
| WDC WD10EZEX-00BN5A0 1TB                          | 5        | 0.4%    |
| Unknown SD/MMC/MS PRO 256GB                       | 5        | 0.4%    |
| Seagate ST3500312CS 500GB                         | 5        | 0.4%    |
| Seagate ST250DM000-1BD141 250GB                   | 5        | 0.4%    |
| Seagate ST1000DM003-1SB10C 1TB                    | 5        | 0.4%    |
| Seagate ST1000DM003-1ER162 1TB                    | 5        | 0.4%    |
| Seagate ST1000DM003-1CH162 1TB                    | 5        | 0.4%    |
| Seagate Expansion Desk 8TB                        | 5        | 0.4%    |
| Samsung SSD 980 500GB                             | 5        | 0.4%    |
| Samsung SSD 860 QVO 1TB                           | 5        | 0.4%    |
| Kingston SA400S37960G 960GB SSD                   | 5        | 0.4%    |
| WDC WDS120G2G0A-00JH30 120GB SSD                  | 4        | 0.32%   |
| WDC WD5000AZRX-00A8LB0 500GB                      | 4        | 0.32%   |
| WDC WD10EZEX-60WN4A1 1TB                          | 4        | 0.32%   |
| WDC WD10EZEX-22MFCA0 1TB                          | 4        | 0.32%   |
| WDC WD10EADS-00L5B1 1TB                           | 4        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 212      | 360    | 37.99%  |
| Seagate             | 195      | 341    | 34.95%  |
| Toshiba             | 45       | 60     | 8.06%   |
| Hitachi             | 32       | 49     | 5.73%   |
| Samsung Electronics | 29       | 37     | 5.2%    |
| Maxtor              | 17       | 24     | 3.05%   |
| HGST                | 13       | 23     | 2.33%   |
| Unknown             | 5        | 5      | 0.9%    |
| LaCie               | 2        | 8      | 0.36%   |
| Fujitsu             | 2        | 2      | 0.36%   |
| TO Exter            | 1        | 2      | 0.18%   |
| Intenso             | 1        | 1      | 0.18%   |
| Hewlett-Packard     | 1        | 1      | 0.18%   |
| ExcelStor           | 1        | 1      | 0.18%   |
| ASMT109x            | 1        | 1      | 0.18%   |
| ASMT                | 1        | 1      | 0.18%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 134      | 189    | 34.54%  |
| Samsung Electronics | 66       | 93     | 17.01%  |
| A-DATA Technology   | 45       | 64     | 11.6%   |
| Crucial             | 18       | 26     | 4.64%   |
| WDC                 | 14       | 18     | 3.61%   |
| Intel               | 13       | 15     | 3.35%   |
| Patriot             | 11       | 14     | 2.84%   |
| SPCC                | 9        | 12     | 2.32%   |
| OCZ                 | 8        | 16     | 2.06%   |
| SanDisk             | 7        | 11     | 1.8%    |
| Team                | 6        | 6      | 1.55%   |
| Kingmax             | 6        | 7      | 1.55%   |
| Transcend           | 5        | 7      | 1.29%   |
| Hewlett-Packard     | 5        | 6      | 1.29%   |
| Gigabyte Technology | 5        | 9      | 1.29%   |
| GOODRAM             | 4        | 4      | 1.03%   |
| Toshiba             | 3        | 4      | 0.77%   |
| SK hynix            | 3        | 4      | 0.77%   |
| Emtec               | 3        | 3      | 0.77%   |
| China               | 3        | 3      | 0.77%   |
| Verbatim            | 2        | 4      | 0.52%   |
| Seagate             | 2        | 2      | 0.52%   |
| PNY                 | 2        | 2      | 0.52%   |
| Micron Technology   | 2        | 3      | 0.52%   |
| Corsair             | 2        | 8      | 0.52%   |
| OCZ-VERTEX3         | 1        | 1      | 0.26%   |
| MicroFrom           | 1        | 1      | 0.26%   |
| Kston               | 1        | 5      | 0.26%   |
| KingDian            | 1        | 1      | 0.26%   |
| EDGE SE8            | 1        | 1      | 0.26%   |
| BUFFALO             | 1        | 1      | 0.26%   |
| ASMT                | 1        | 1      | 0.26%   |
| Apple               | 1        | 1      | 0.26%   |
| Apacer              | 1        | 2      | 0.26%   |
| AMD                 | 1        | 1      | 0.26%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 429      | 916    | 47.25%  |
| SSD     | 325      | 545    | 35.79%  |
| NVMe    | 144      | 256    | 15.86%  |
| Unknown | 7        | 10     | 0.77%   |
| MMC     | 3        | 3      | 0.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 544      | 1406   | 75.14%  |
| NVMe | 143      | 255    | 19.75%  |
| SAS  | 34       | 66     | 4.7%    |
| MMC  | 3        | 3      | 0.41%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 439      | 857    | 56.28%  |
| 0.51-1.0   | 207      | 325    | 26.54%  |
| 1.01-2.0   | 71       | 105    | 9.1%    |
| 3.01-4.0   | 23       | 46     | 2.95%   |
| 4.01-10.0  | 20       | 67     | 2.56%   |
| 2.01-3.0   | 17       | 55     | 2.18%   |
| 10.01-20.0 | 3        | 6      | 0.38%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 157      | 24.19%  |
| 251-500        | 101      | 15.56%  |
| 501-1000       | 98       | 15.1%   |
| 1-20           | 59       | 9.09%   |
| 1001-2000      | 52       | 8.01%   |
| 51-100         | 50       | 7.7%    |
| Unknown        | 42       | 6.47%   |
| More than 3000 | 35       | 5.39%   |
| 2001-3000      | 29       | 4.47%   |
| 21-50          | 26       | 4.01%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 252      | 37.72%  |
| 21-50          | 97       | 14.52%  |
| 101-250        | 62       | 9.28%   |
| 51-100         | 61       | 9.13%   |
| 501-1000       | 49       | 7.34%   |
| 251-500        | 47       | 7.04%   |
| Unknown        | 42       | 6.29%   |
| 1001-2000      | 34       | 5.09%   |
| More than 3000 | 15       | 2.25%   |
| 2001-3000      | 9        | 1.35%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| WDC WD5000AAKX-001CA0 500GB      | 3        | 3      | 2.36%   |
| WDC WD3200AAJS-60Z0A0 320GB      | 3        | 6      | 2.36%   |
| Seagate ST500DM002-1BD142 500GB  | 3        | 3      | 2.36%   |
| Seagate ST3500312CS 500GB        | 3        | 3      | 2.36%   |
| Maxtor STM3250310AS 250GB        | 3        | 4      | 2.36%   |
| WDC WD5000AADS-00S9B0 500GB      | 2        | 2      | 1.57%   |
| WDC WD1002FAEX-00Z3A0 1TB        | 2        | 2      | 1.57%   |
| Seagate STM3250318AS 250GB       | 2        | 3      | 1.57%   |
| Seagate ST500LM021-1KJ152 500GB  | 2        | 2      | 1.57%   |
| Seagate ST3500320AS 500GB        | 2        | 3      | 1.57%   |
| Seagate ST3250318AS 250GB        | 2        | 3      | 1.57%   |
| Seagate ST1000DM010-2EP102 1TB   | 2        | 2      | 1.57%   |
| OCZ ARC100 240GB SSD             | 2        | 2      | 1.57%   |
| Hitachi HTS725032A9A364 320GB    | 2        | 3      | 1.57%   |
| Hitachi HDS721616PLA380 160GB    | 2        | 2      | 1.57%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 1        | 1      | 0.79%   |
| WDC WD5000AAKX-75U6AA0 500GB     | 1        | 1      | 0.79%   |
| WDC WD5000AAKX-22ERMA0 500GB     | 1        | 1      | 0.79%   |
| WDC WD5000AACS-00G8B1 500GB      | 1        | 7      | 0.79%   |
| WDC WD400EB-00CPF0 40GB          | 1        | 1      | 0.79%   |
| WDC WD400BD-08JMC0 40GB          | 1        | 1      | 0.79%   |
| WDC WD3200AVVS-63L2B0 320GB      | 1        | 1      | 0.79%   |
| WDC WD3200AVBS-63TAA0 320GB      | 1        | 1      | 0.79%   |
| WDC WD3200AAKS-75L9A0 320GB      | 1        | 1      | 0.79%   |
| WDC WD3200AAKS-00B3A0 320GB      | 1        | 1      | 0.79%   |
| WDC WD30PURX-64P6ZY0 3TB         | 1        | 2      | 0.79%   |
| WDC WD30EFRX-68EUZN0 3TB         | 1        | 10     | 0.79%   |
| WDC WD30EFRX-68AX9N0 3TB         | 1        | 1      | 0.79%   |
| WDC WD2500JS-60MHB5 250GB        | 1        | 3      | 0.79%   |
| WDC WD2500JB-00REA0 250GB        | 1        | 1      | 0.79%   |
| WDC WD2500BEKT-75PVMT1 250GB     | 1        | 1      | 0.79%   |
| WDC WD20EARX-00PASB0 2TB         | 1        | 1      | 0.79%   |
| WDC WD2000JD-22HBC0 200GB        | 1        | 1      | 0.79%   |
| WDC WD1600AAJS-07M0A0 160GB      | 1        | 1      | 0.79%   |
| WDC WD1600AAJS-00PSA0 160GB      | 1        | 2      | 0.79%   |
| WDC WD15EARS-00MVWB0 1TB         | 1        | 1      | 0.79%   |
| WDC WD1502FAEX-007BA0 1TB        | 1        | 1      | 0.79%   |
| WDC WD10EZEX-21WN4A0 1TB         | 1        | 1      | 0.79%   |
| WDC WD10EZEX-08WN4A0 1TB         | 1        | 1      | 0.79%   |
| WDC WD10EZEX-08M2NA0 1TB         | 1        | 1      | 0.79%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 37       | 61     | 30.83%  |
| Seagate             | 32       | 42     | 26.67%  |
| Samsung Electronics | 14       | 16     | 11.67%  |
| Hitachi             | 8        | 10     | 6.67%   |
| Maxtor              | 7        | 9      | 5.83%   |
| Kingston            | 4        | 6      | 3.33%   |
| Intel               | 3        | 3      | 2.5%    |
| HGST                | 3        | 4      | 2.5%    |
| Toshiba             | 2        | 2      | 1.67%   |
| OCZ                 | 2        | 2      | 1.67%   |
| A-DATA Technology   | 2        | 2      | 1.67%   |
| Plextor             | 1        | 1      | 0.83%   |
| Patriot             | 1        | 1      | 0.83%   |
| Hewlett-Packard     | 1        | 1      | 0.83%   |
| Crucial             | 1        | 1      | 0.83%   |
| Corsair             | 1        | 7      | 0.83%   |
| Apacer              | 1        | 2      | 0.83%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 36       | 60     | 36.36%  |
| Seagate             | 32       | 42     | 32.32%  |
| Samsung Electronics | 11       | 13     | 11.11%  |
| Hitachi             | 8        | 10     | 8.08%   |
| Maxtor              | 7        | 9      | 7.07%   |
| HGST                | 3        | 4      | 3.03%   |
| Toshiba             | 2        | 2      | 2.02%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 88       | 140    | 80.73%  |
| SSD  | 19       | 28     | 17.43%  |
| NVMe | 2        | 2      | 1.83%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                    | Desktops | Drives | Percent |
|--------------------------|----------|--------|---------|
| Seagate ST3160215A 160GB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 333      | 925    | 48.19%  |
| Works    | 257      | 634    | 37.19%  |
| Malfunc  | 100      | 170    | 14.47%  |
| Failed   | 1        | 1      | 0.14%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 397      | 48.36%  |
| AMD                           | 177      | 21.56%  |
| Samsung Electronics           | 61       | 7.43%   |
| Kingston Technology Company   | 31       | 3.78%   |
| ASMedia Technology            | 28       | 3.41%   |
| Marvell Technology Group      | 17       | 2.07%   |
| SanDisk                       | 14       | 1.71%   |
| ADATA Technology              | 14       | 1.71%   |
| Nvidia                        | 13       | 1.58%   |
| JMicron Technology            | 13       | 1.58%   |
| Phison Electronics            | 12       | 1.46%   |
| Silicon Motion                | 10       | 1.22%   |
| Micron/Crucial Technology     | 7        | 0.85%   |
| Lite-On Technology            | 5        | 0.61%   |
| VIA Technologies              | 4        | 0.49%   |
| Realtek Semiconductor         | 4        | 0.49%   |
| Silicon Image                 | 3        | 0.37%   |
| Broadcom / LSI                | 3        | 0.37%   |
| LSI Logic / Symbios Logic     | 2        | 0.24%   |
| Solidigm                      | 1        | 0.12%   |
| SK hynix                      | 1        | 0.12%   |
| Seagate Technology            | 1        | 0.12%   |
| KIOXIA                        | 1        | 0.12%   |
| Integrated Technology Express | 1        | 0.12%   |
| Biwin Storage Technology      | 1        | 0.12%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 99       | 9.52%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 49       | 4.71%   |
| AMD 400 Series Chipset SATA Controller                                                  | 39       | 3.75%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 35       | 3.37%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 33       | 3.17%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 30       | 2.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 28       | 2.69%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 27       | 2.6%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 26       | 2.5%    |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 26       | 2.5%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 22       | 2.12%   |
| Intel SATA Controller [RAID mode]                                                       | 21       | 2.02%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 21       | 2.02%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                                | 20       | 1.92%   |
| AMD FCH SATA Controller D                                                               | 19       | 1.83%   |
| AMD 500 Series Chipset SATA Controller                                                  | 19       | 1.83%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 18       | 1.73%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 18       | 1.73%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 17       | 1.63%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 15       | 1.44%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 15       | 1.44%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 15       | 1.44%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 14       | 1.35%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 13       | 1.25%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 13       | 1.25%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 13       | 1.25%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 11       | 1.06%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 10       | 0.96%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 9        | 0.87%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 9        | 0.87%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 8        | 0.77%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 8        | 0.77%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 8        | 0.77%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 8        | 0.77%   |
| AMD 600 Series Chipset SATA Controller                                                  | 8        | 0.77%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 7        | 0.67%   |
| Nvidia MCP61 SATA Controller                                                            | 7        | 0.67%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 7        | 0.67%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 7        | 0.67%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 7        | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 468      | 57.21%  |
| IDE  | 160      | 19.56%  |
| NVMe | 148      | 18.09%  |
| RAID | 36       | 4.4%    |
| SAS  | 6        | 0.73%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 401      | 67.39%  |
| AMD    | 194      | 32.61%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-2400 CPU @ 3.10GHz            | 12       | 2.01%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 12       | 2.01%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 10       | 1.67%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 10       | 1.67%   |
| AMD Ryzen 5 3600 6-Core Processor           | 10       | 1.67%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 9        | 1.51%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 7        | 1.17%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 7        | 1.17%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 7        | 1.17%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 7        | 1.17%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 6        | 1%      |
| Intel Core i7-4790 CPU @ 3.60GHz            | 6        | 1%      |
| Intel Core i5-4570 CPU @ 3.20GHz            | 6        | 1%      |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 6        | 1%      |
| Intel Core 2 CPU 6400 @ 2.13GHz             | 6        | 1%      |
| AMD Ryzen 9 3900X 12-Core Processor         | 6        | 1%      |
| AMD Ryzen 7 2700X Eight-Core Processor      | 6        | 1%      |
| AMD Ryzen 5 2600 Six-Core Processor         | 6        | 1%      |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 6        | 1%      |
| Intel Core i9-9900K CPU @ 3.60GHz           | 5        | 0.84%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 5        | 0.84%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 5        | 0.84%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 5        | 0.84%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 5        | 0.84%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 5        | 0.84%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 5        | 0.84%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 5        | 0.84%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 5        | 0.84%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 4        | 0.67%   |
| Intel Pentium CPU G4560 @ 3.50GHz           | 4        | 0.67%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 4        | 0.67%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 4        | 0.67%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 4        | 0.67%   |
| Intel Core i3-9100F CPU @ 3.60GHz           | 4        | 0.67%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 4        | 0.67%   |
| Intel Core i3-4170 CPU @ 3.70GHz            | 4        | 0.67%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 4        | 0.67%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 4        | 0.67%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz        | 4        | 0.67%   |
| Intel 12th Gen Core i7-12700K               | 4        | 0.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 102      | 17.14%  |
| Intel Core i7           | 68       | 11.43%  |
| Intel Core i3           | 51       | 8.57%   |
| Intel Core 2 Duo        | 46       | 7.73%   |
| AMD Ryzen 5             | 44       | 7.39%   |
| AMD Ryzen 7             | 35       | 5.88%   |
| Intel Xeon              | 20       | 3.36%   |
| Intel Pentium           | 20       | 3.36%   |
| Intel Core 2 Quad       | 18       | 3.03%   |
| Intel Celeron           | 18       | 3.03%   |
| AMD Ryzen 9             | 17       | 2.86%   |
| AMD Ryzen 3             | 16       | 2.69%   |
| AMD FX                  | 14       | 2.35%   |
| Other                   | 13       | 2.18%   |
| Intel Pentium Dual-Core | 12       | 2.02%   |
| Intel Core i9           | 11       | 1.85%   |
| AMD A8                  | 10       | 1.68%   |
| AMD Phenom II X4        | 8        | 1.34%   |
| AMD A4                  | 8        | 1.34%   |
| Intel Core 2            | 7        | 1.18%   |
| AMD Ryzen Threadripper  | 6        | 1.01%   |
| Intel Pentium Dual      | 4        | 0.67%   |
| AMD Sempron             | 4        | 0.67%   |
| AMD Athlon II X4        | 4        | 0.67%   |
| Intel Genuine           | 3        | 0.5%    |
| Intel Atom              | 3        | 0.5%    |
| AMD Athlon II X3        | 3        | 0.5%    |
| AMD Athlon 64 X2        | 3        | 0.5%    |
| Intel Pentium Gold      | 2        | 0.34%   |
| Intel Pentium D         | 2        | 0.34%   |
| Intel Pentium 4         | 2        | 0.34%   |
| AMD Phenom II X3        | 2        | 0.34%   |
| AMD Phenom              | 2        | 0.34%   |
| AMD Athlon X4           | 2        | 0.34%   |
| AMD Athlon II X2        | 2        | 0.34%   |
| AMD Athlon Dual Core    | 2        | 0.34%   |
| AMD Athlon              | 2        | 0.34%   |
| Intel Core 2 Extreme    | 1        | 0.17%   |
| AMD Ryzen Embedded      | 1        | 0.17%   |
| AMD Ryzen 7 PRO         | 1        | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 232      | 38.99%  |
| 2      | 171      | 28.74%  |
| 6      | 64       | 10.76%  |
| 8      | 55       | 9.24%   |
| 12     | 19       | 3.19%   |
| 1      | 18       | 3.03%   |
| 16     | 10       | 1.68%   |
| 3      | 10       | 1.68%   |
| 10     | 5        | 0.84%   |
| 32     | 4        | 0.67%   |
| 24     | 2        | 0.34%   |
| 64     | 1        | 0.17%   |
| 36     | 1        | 0.17%   |
| 20     | 1        | 0.17%   |
| 18     | 1        | 0.17%   |
| 14     | 1        | 0.17%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 586      | 98.49%  |
| 2      | 9        | 1.51%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 299      | 50.25%  |
| 1      | 295      | 49.58%  |
| 4      | 1        | 0.17%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 585      | 97.99%  |
| Unknown        | 12       | 2.01%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 157      | 25.16%  |
| 0x306c3    | 48       | 7.69%   |
| 0x1067a    | 34       | 5.45%   |
| 0x206a7    | 33       | 5.29%   |
| 0x306a9    | 29       | 4.65%   |
| 0x906e9    | 23       | 3.69%   |
| 0x906ea    | 20       | 3.21%   |
| 0x506e3    | 20       | 3.21%   |
| 0x010000c8 | 16       | 2.56%   |
| 0x08701021 | 14       | 2.24%   |
| 0x10676    | 13       | 2.08%   |
| 0x08701013 | 10       | 1.6%    |
| 0x0800820d | 10       | 1.6%    |
| 0x6fb      | 9        | 1.44%   |
| 0x06001119 | 9        | 1.44%   |
| 0x6fd      | 8        | 1.28%   |
| 0x08101016 | 8        | 1.28%   |
| 0x0810100b | 7        | 1.12%   |
| 0x06000852 | 7        | 1.12%   |
| 0x906eb    | 6        | 0.96%   |
| 0x0a601203 | 6        | 0.96%   |
| 0x0a201009 | 6        | 0.96%   |
| 0xa0653    | 5        | 0.8%    |
| 0x90672    | 5        | 0.8%    |
| 0x0a20120a | 5        | 0.8%    |
| 0xa0655    | 4        | 0.64%   |
| 0x6f2      | 4        | 0.64%   |
| 0x506c9    | 4        | 0.64%   |
| 0x406c4    | 4        | 0.64%   |
| 0x106e5    | 4        | 0.64%   |
| 0x0a201016 | 4        | 0.64%   |
| 0x08001137 | 4        | 0.64%   |
| 0xf62      | 3        | 0.48%   |
| 0x906ed    | 3        | 0.48%   |
| 0x20655    | 3        | 0.48%   |
| 0x0a50000d | 3        | 0.48%   |
| 0x0a20102b | 3        | 0.48%   |
| 0x08701030 | 3        | 0.48%   |
| 0x08600106 | 3        | 0.48%   |
| 0x08008206 | 3        | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 71       | 11.87%  |
| KabyLake         | 68       | 11.37%  |
| Penryn           | 64       | 10.7%   |
| SandyBridge      | 42       | 7.02%   |
| Zen 2            | 41       | 6.86%   |
| IvyBridge        | 37       | 6.19%   |
| Core             | 29       | 4.85%   |
| Zen              | 28       | 4.68%   |
| Skylake          | 28       | 4.68%   |
| Piledriver       | 26       | 4.35%   |
| K10              | 26       | 4.35%   |
| Zen 3            | 25       | 4.18%   |
| Zen+             | 21       | 3.51%   |
| CometLake        | 15       | 2.51%   |
| Unknown          | 14       | 2.34%   |
| Silvermont       | 9        | 1.51%   |
| K8 Hammer        | 9        | 1.51%   |
| Alderlake Hybrid | 8        | 1.34%   |
| Nehalem          | 7        | 1.17%   |
| Westmere         | 5        | 0.84%   |
| NetBurst         | 5        | 0.84%   |
| Goldmont         | 4        | 0.67%   |
| Goldmont plus    | 3        | 0.5%    |
| Steamroller      | 2        | 0.33%   |
| K10 Llano        | 2        | 0.33%   |
| Excavator        | 2        | 0.33%   |
| Broadwell        | 2        | 0.33%   |
| Puma             | 1        | 0.17%   |
| Icelake          | 1        | 0.17%   |
| Bulldozer        | 1        | 0.17%   |
| Bonnell          | 1        | 0.17%   |
| Bobcat           | 1        | 0.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 242      | 38.41%  |
| Intel             | 200      | 31.75%  |
| AMD               | 186      | 29.52%  |
| ASPEED Technology | 2        | 0.32%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 36       | 5.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 28       | 4.33%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 25       | 3.86%   |
| Nvidia GK208B [GeForce GT 710]                                              | 22       | 3.4%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 22       | 3.4%    |
| Intel HD Graphics 630                                                       | 15       | 2.32%   |
| Intel HD Graphics 530                                                       | 15       | 2.32%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 13       | 2.01%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 12       | 1.85%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 12       | 1.85%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 11       | 1.7%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 10       | 1.55%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 10       | 1.55%   |
| Nvidia GT218 [GeForce 210]                                                  | 9        | 1.39%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 9        | 1.39%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 8        | 1.24%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 8        | 1.24%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 8        | 1.24%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 8        | 1.24%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 7        | 1.08%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 7        | 1.08%   |
| Nvidia GF108 [GeForce GT 730]                                               | 7        | 1.08%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 7        | 1.08%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 7        | 1.08%   |
| Intel AlderLake-S GT1                                                       | 6        | 0.93%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 6        | 0.93%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 6        | 0.93%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 5        | 0.77%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 5        | 0.77%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 5        | 0.77%   |
| Nvidia GK107 [GeForce GT 740]                                               | 5        | 0.77%   |
| Nvidia GF108 [GeForce GT 630]                                               | 5        | 0.77%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 5        | 0.77%   |
| Nvidia G92 [GeForce GTS 250]                                                | 5        | 0.77%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 5        | 0.77%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 5        | 0.77%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 5        | 0.77%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 5        | 0.77%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 5        | 0.77%   |
| AMD Raphael                                                                 | 5        | 0.77%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 223      | 37.17%  |
| 1 x Intel      | 167      | 27.83%  |
| 1 x AMD        | 167      | 27.83%  |
| 2 x Intel      | 11       | 1.83%   |
| Intel + Nvidia | 10       | 1.67%   |
| 2 x AMD        | 9        | 1.5%    |
| AMD + Nvidia   | 8        | 1.33%   |
| 2 x Nvidia     | 2        | 0.33%   |
| Intel + AMD    | 1        | 0.17%   |
| 1 x ASPEED     | 1        | 0.17%   |
| AMD + ASPEED   | 1        | 0.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 452      | 74.59%  |
| Proprietary | 134      | 22.11%  |
| Unknown     | 20       | 3.3%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 265      | 42.47%  |
| 1.01-2.0   | 78       | 12.5%   |
| 0.51-1.0   | 71       | 11.38%  |
| 0.01-0.5   | 62       | 9.94%   |
| 7.01-8.0   | 56       | 8.97%   |
| 3.01-4.0   | 45       | 7.21%   |
| 5.01-6.0   | 20       | 3.21%   |
| 8.01-16.0  | 16       | 2.56%   |
| 2.01-3.0   | 6        | 0.96%   |
| 16.01-24.0 | 5        | 0.8%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 115      | 18.43%  |
| Dell                 | 95       | 15.22%  |
| Goldstar             | 81       | 12.98%  |
| Philips              | 62       | 9.94%   |
| BenQ                 | 32       | 5.13%   |
| AOC                  | 27       | 4.33%   |
| Ancor Communications | 25       | 4.01%   |
| Hewlett-Packard      | 24       | 3.85%   |
| Acer                 | 24       | 3.85%   |
| Fujitsu Siemens      | 17       | 2.72%   |
| Lenovo               | 14       | 2.24%   |
| LG Electronics       | 11       | 1.76%   |
| Unknown              | 10       | 1.6%    |
| Eizo                 | 10       | 1.6%    |
| ASUSTek Computer     | 8        | 1.28%   |
| Sony                 | 6        | 0.96%   |
| KTC                  | 5        | 0.8%    |
| ViewSonic            | 4        | 0.64%   |
| Vestel Elektronik    | 4        | 0.64%   |
| Toshiba              | 4        | 0.64%   |
| Panasonic            | 4        | 0.64%   |
| Lenovo Group Limited | 3        | 0.48%   |
| Iiyama               | 3        | 0.48%   |
| OEM                  | 2        | 0.32%   |
| MSI                  | 2        | 0.32%   |
| HannStar             | 2        | 0.32%   |
| FUS                  | 2        | 0.32%   |
| Belinea              | 2        | 0.32%   |
| AGO                  | 2        | 0.32%   |
| Unknown              | 2        | 0.32%   |
| ___                  | 1        | 0.16%   |
| Yakumo               | 1        | 0.16%   |
| Xerox                | 1        | 0.16%   |
| VIE                  | 1        | 0.16%   |
| Unknown (XXX)        | 1        | 0.16%   |
| RTD                  | 1        | 0.16%   |
| NEC Computers        | 1        | 0.16%   |
| NAD                  | 1        | 0.16%   |
| MStar                | 1        | 0.16%   |
| Mi                   | 1        | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Goldstar E2250 GSM578D 1920x1080 477x268mm 21.5-inch                   | 10       | 1.5%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 8        | 1.2%    |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 8        | 1.2%    |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                | 7        | 1.05%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                | 5        | 0.75%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                   | 5        | 0.75%   |
| Vestel Elektronik 32FHD_LCD_TV VES3700 1920x1080 700x400mm 31.7-inch   | 4        | 0.6%    |
| Samsung Electronics S24F350 SAM0D21 1920x1080 520x290mm 23.4-inch      | 4        | 0.6%    |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 4        | 0.6%    |
| Philips 220E PHLC02E 1920x1080 476x268mm 21.5-inch                     | 4        | 0.6%    |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch               | 4        | 0.6%    |
| Goldstar L1918S GSM4B31 1280x1024 376x301mm 19.0-inch                  | 4        | 0.6%    |
| AOC 2590G4 AOC2590 1920x1080 544x303mm 24.5-inch                       | 4        | 0.6%    |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch  | 4        | 0.6%    |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch      | 3        | 0.45%   |
| Samsung Electronics T24C300 SAM0A9B 1920x1080 531x299mm 24.0-inch      | 3        | 0.45%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 3        | 0.45%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 1020x570mm 46.0-inch | 3        | 0.45%   |
| Samsung Electronics LCD Monitor SAM0659 1920x1080                      | 3        | 0.45%   |
| Philips PHL 246V5 PHLC0C5 1920x1080 531x299mm 24.0-inch                | 3        | 0.45%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                     | 3        | 0.45%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                     | 3        | 0.45%   |
| Goldstar W1941 GSM4B91 1360x768 406x229mm 18.4-inch                    | 3        | 0.45%   |
| Goldstar MONITOR GSM59C6 1920x1080 509x286mm 23.0-inch                 | 3        | 0.45%   |
| Dell U2715H DELD067 2560x1440 597x336mm 27.0-inch                      | 3        | 0.45%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 3        | 0.45%   |
| Dell U2410 DELF017 1920x1200 520x320mm 24.0-inch                       | 3        | 0.45%   |
| Dell SE2419HR DELF113 1920x1080 527x296mm 23.8-inch                    | 3        | 0.45%   |
| Dell P2214H DELA097 1920x1080 477x268mm 21.5-inch                      | 3        | 0.45%   |
| AOC Q2770 AOC2770 2560x1440 597x336mm 27.0-inch                        | 3        | 0.45%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                  | 2        | 0.3%    |
| Unknown LCD Monitor SAMSUNG                                            | 2        | 0.3%    |
| Samsung Electronics SyncMaster SAM03F2 1680x1050                       | 2        | 0.3%    |
| Samsung Electronics SyncMaster SAM022B 1280x1024 338x270mm 17.0-inch   | 2        | 0.3%    |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch   | 2        | 0.3%    |
| Samsung Electronics SMS24A350H SAM07D6 1920x1080 531x299mm 24.0-inch   | 2        | 0.3%    |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch      | 2        | 0.3%    |
| Samsung Electronics S24B350 SAM08D9 1920x1080 531x299mm 24.0-inch      | 2        | 0.3%    |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch      | 2        | 0.3%    |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 950x540mm 43.0-inch  | 2        | 0.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 272      | 44.44%  |
| 1280x1024 (SXGA)   | 68       | 11.11%  |
| 2560x1440 (QHD)    | 46       | 7.52%   |
| 3840x2160 (4K)     | 43       | 7.03%   |
| 1680x1050 (WSXGA+) | 37       | 6.05%   |
| 1920x1200 (WUXGA)  | 21       | 3.43%   |
| 1366x768 (WXGA)    | 20       | 3.27%   |
| Unknown            | 19       | 3.1%    |
| 1440x900 (WXGA+)   | 14       | 2.29%   |
| 1360x768           | 12       | 1.96%   |
| 3440x1440          | 11       | 1.8%    |
| 3840x1080          | 6        | 0.98%   |
| 2560x1080          | 6        | 0.98%   |
| 1024x768 (XGA)     | 5        | 0.82%   |
| 1600x900 (HD+)     | 4        | 0.65%   |
| 1600x1200          | 3        | 0.49%   |
| 5760x2160          | 2        | 0.33%   |
| 5120x1440          | 2        | 0.33%   |
| 3840x1600          | 2        | 0.33%   |
| 2560x1600          | 2        | 0.33%   |
| 1920x540           | 2        | 0.33%   |
| 800x600            | 1        | 0.16%   |
| 7680x1440          | 1        | 0.16%   |
| 6400x1440          | 1        | 0.16%   |
| 6000x1440          | 1        | 0.16%   |
| 4960x1080          | 1        | 0.16%   |
| 3840x2524          | 1        | 0.16%   |
| 3600x1200          | 1        | 0.16%   |
| 3360x1080          | 1        | 0.16%   |
| 3286x1080          | 1        | 0.16%   |
| 2960x1050          | 1        | 0.16%   |
| 2720x1024          | 1        | 0.16%   |
| 2624x1200          | 1        | 0.16%   |
| 2288x1287          | 1        | 0.16%   |
| 1280x960           | 1        | 0.16%   |
| 1280x720 (HD)      | 1        | 0.16%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 90       | 14.71%  |
| 21      | 87       | 14.22%  |
| 27      | 76       | 12.42%  |
| 23      | 65       | 10.62%  |
| Unknown | 62       | 10.13%  |
| 19      | 46       | 7.52%   |
| 22      | 27       | 4.41%   |
| 18      | 24       | 3.92%   |
| 17      | 24       | 3.92%   |
| 31      | 17       | 2.78%   |
| 34      | 16       | 2.61%   |
| 84      | 12       | 1.96%   |
| 20      | 9        | 1.47%   |
| 15      | 8        | 1.31%   |
| 40      | 7        | 1.14%   |
| 54      | 6        | 0.98%   |
| 72      | 5        | 0.82%   |
| 65      | 5        | 0.82%   |
| 32      | 4        | 0.65%   |
| 26      | 4        | 0.65%   |
| 46      | 2        | 0.33%   |
| 43      | 2        | 0.33%   |
| 37      | 2        | 0.33%   |
| 29      | 2        | 0.33%   |
| 28      | 2        | 0.33%   |
| 25      | 2        | 0.33%   |
| 142     | 1        | 0.16%   |
| 52      | 1        | 0.16%   |
| 49      | 1        | 0.16%   |
| 42      | 1        | 0.16%   |
| 16      | 1        | 0.16%   |
| 12      | 1        | 0.16%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 212      | 35.57%  |
| 401-500        | 154      | 25.84%  |
| Unknown        | 62       | 10.4%   |
| 351-400        | 41       | 6.88%   |
| 301-350        | 32       | 5.37%   |
| 601-700        | 29       | 4.87%   |
| 701-800        | 20       | 3.36%   |
| 1501-2000      | 17       | 2.85%   |
| 1001-1500      | 15       | 2.52%   |
| 801-900        | 9        | 1.51%   |
| 901-1000       | 3        | 0.5%    |
| More than 2000 | 1        | 0.17%   |
| 201-300        | 1        | 0.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 349      | 61.34%  |
| 16/10   | 70       | 12.3%   |
| 5/4     | 59       | 10.37%  |
| Unknown | 53       | 9.31%   |
| 21/9    | 18       | 3.16%   |
| 4/3     | 11       | 1.93%   |
| 6/5     | 4        | 0.7%    |
| 3/2     | 3        | 0.53%   |
| 32/9    | 1        | 0.18%   |
| 1.00    | 1        | 0.18%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 214      | 35.67%  |
| 301-350        | 79       | 13.17%  |
| 151-200        | 77       | 12.83%  |
| Unknown        | 62       | 10.33%  |
| 141-150        | 40       | 6.67%   |
| 351-500        | 39       | 6.5%    |
| 251-300        | 33       | 5.5%    |
| More than 1000 | 30       | 5%      |
| 501-1000       | 15       | 2.5%    |
| 101-110        | 6        | 1%      |
| 111-120        | 2        | 0.33%   |
| 71-80          | 1        | 0.17%   |
| 131-140        | 1        | 0.17%   |
| 121-130        | 1        | 0.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 345      | 58.67%  |
| 101-120 | 130      | 22.11%  |
| Unknown | 62       | 10.54%  |
| 1-50    | 26       | 4.42%   |
| 121-160 | 18       | 3.06%   |
| 161-240 | 7        | 1.19%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 481      | 78.85%  |
| 2     | 82       | 13.44%  |
| 0     | 36       | 5.9%    |
| 3     | 11       | 1.8%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 328      | 41.1%   |
| Intel                           | 244      | 30.58%  |
| Qualcomm Atheros                | 42       | 5.26%   |
| TP-Link                         | 33       | 4.14%   |
| Broadcom                        | 26       | 3.26%   |
| Ralink Technology               | 13       | 1.63%   |
| Nvidia                          | 12       | 1.5%    |
| MediaTek                        | 12       | 1.5%    |
| Broadcom Limited                | 9        | 1.13%   |
| ASUSTek Computer                | 8        | 1%      |
| Ralink                          | 7        | 0.88%   |
| Aquantia                        | 7        | 0.88%   |
| D-Link                          | 6        | 0.75%   |
| Marvell Technology Group        | 5        | 0.63%   |
| Microsoft                       | 4        | 0.5%    |
| Samsung Electronics             | 3        | 0.38%   |
| Qualcomm Atheros Communications | 3        | 0.38%   |
| Edimax Technology               | 3        | 0.38%   |
| ZTE WCDMA Technologies MSM      | 2        | 0.25%   |
| Xiaomi                          | 2        | 0.25%   |
| VIA Technologies                | 2        | 0.25%   |
| Tenda                           | 2        | 0.25%   |
| IMC Networks                    | 2        | 0.25%   |
| Giga-Byte Technology            | 2        | 0.25%   |
| Belkin Components               | 2        | 0.25%   |
| ASIX Electronics                | 2        | 0.25%   |
| Texas Instruments               | 1        | 0.13%   |
| Qualcomm                        | 1        | 0.13%   |
| QNAP System                     | 1        | 0.13%   |
| QLogic                          | 1        | 0.13%   |
| QinHeng Electronics             | 1        | 0.13%   |
| NetGear                         | 1        | 0.13%   |
| Micro Star International        | 1        | 0.13%   |
| Mercucys                        | 1        | 0.13%   |
| Linksys                         | 1        | 0.13%   |
| Huawei Technologies             | 1        | 0.13%   |
| HMD Global                      | 1        | 0.13%   |
| Fitbit                          | 1        | 0.13%   |
| Dresden Elektronik              | 1        | 0.13%   |
| DisplayLink                     | 1        | 0.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 277      | 31.37%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 37       | 4.19%   |
| Intel I211 Gigabit Network Connection                                  | 33       | 3.74%   |
| Realtek RTL8125 2.5GbE Controller                                      | 27       | 3.06%   |
| Intel Ethernet Connection (2) I219-V                                   | 24       | 2.72%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 23       | 2.6%    |
| Intel Wi-Fi 6 AX200                                                    | 20       | 2.27%   |
| Intel Ethernet Connection I217-LM                                      | 18       | 2.04%   |
| Intel Ethernet Connection I217-V                                       | 11       | 1.25%   |
| Intel Ethernet Connection (7) I219-V                                   | 10       | 1.13%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 9        | 1.02%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 9        | 1.02%   |
| Intel Ethernet Controller I225-V                                       | 9        | 1.02%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 9        | 1.02%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 8        | 0.91%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 7        | 0.79%   |
| Nvidia MCP61 Ethernet                                                  | 7        | 0.79%   |
| Intel 82574L Gigabit Network Connection                                | 7        | 0.79%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                | 7        | 0.79%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 6        | 0.68%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                        | 6        | 0.68%   |
| Intel 82579V Gigabit Network Connection                                | 6        | 0.68%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                    | 5        | 0.57%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 5        | 0.57%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 5        | 0.57%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 5        | 0.57%   |
| Intel I210 Gigabit Network Connection                                  | 5        | 0.57%   |
| Intel Ethernet Connection (2) I219-LM                                  | 5        | 0.57%   |
| Intel Ethernet Connection (2) I218-V                                   | 5        | 0.57%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 5        | 0.57%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 5        | 0.57%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 4        | 0.45%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                 | 4        | 0.45%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 4        | 0.45%   |
| Ralink RT5370 Wireless Adapter                                         | 4        | 0.45%   |
| Ralink MT7601U Wireless Adapter                                        | 4        | 0.45%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 4        | 0.45%   |
| Intel Ethernet Connection (14) I219-V                                  | 4        | 0.45%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 4        | 0.45%   |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 4        | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 53       | 26.11%  |
| Realtek Semiconductor           | 36       | 17.73%  |
| TP-Link                         | 30       | 14.78%  |
| Ralink Technology               | 13       | 6.4%    |
| Qualcomm Atheros                | 12       | 5.91%   |
| MediaTek                        | 9        | 4.43%   |
| ASUSTek Computer                | 8        | 3.94%   |
| Ralink                          | 7        | 3.45%   |
| D-Link                          | 6        | 2.96%   |
| Broadcom                        | 6        | 2.96%   |
| Microsoft                       | 4        | 1.97%   |
| Qualcomm Atheros Communications | 3        | 1.48%   |
| Edimax Technology               | 3        | 1.48%   |
| Tenda                           | 2        | 0.99%   |
| IMC Networks                    | 2        | 0.99%   |
| Broadcom Limited                | 2        | 0.99%   |
| Belkin Components               | 2        | 0.99%   |
| NetGear                         | 1        | 0.49%   |
| Micro Star International        | 1        | 0.49%   |
| Mercucys                        | 1        | 0.49%   |
| Linksys                         | 1        | 0.49%   |
| Accton Technology               | 1        | 0.49%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                             | 20       | 9.8%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter             | 9        | 4.41%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                     | 6        | 2.94%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                 | 6        | 2.94%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                             | 5        | 2.45%   |
| Intel Cannon Lake PCH CNVi WiFi                                 | 5        | 2.45%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                    | 4        | 1.96%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                          | 4        | 1.96%   |
| Ralink RT5370 Wireless Adapter                                  | 4        | 1.96%   |
| Ralink MT7601U Wireless Adapter                                 | 4        | 1.96%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter   | 4        | 1.96%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                | 4        | 1.96%   |
| Intel Alder Lake-S PCH CNVi WiFi                                | 4        | 1.96%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                           | 3        | 1.47%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                             | 3        | 1.47%   |
| TP-Link Archer T4U ver.3                                        | 3        | 1.47%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                 | 3        | 1.47%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                         | 3        | 1.47%   |
| Ralink RT2501/RT2573 Wireless Adapter                           | 3        | 1.47%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                         | 3        | 1.47%   |
| Intel Wireless 8265 / 8275                                      | 3        | 1.47%   |
| Intel Wireless 3165                                             | 3        | 1.47%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]         | 3        | 1.47%   |
| Intel Comet Lake PCH CNVi WiFi                                  | 3        | 1.47%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter    | 3        | 1.47%   |
| ASUS USB-N14 802.11b/g/n (2x2) Wireless Adapter [Ralink RT5372] | 3        | 1.47%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                          | 2        | 0.98%   |
| Tenda U12                                                       | 2        | 0.98%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter        | 2        | 0.98%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                 | 2        | 0.98%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter           | 2        | 0.98%   |
| Ralink RT2870/RT3070 Wireless Adapter                           | 2        | 0.98%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                       | 2        | 0.98%   |
| Qualcomm Atheros AR9271 802.11n                                 | 2        | 0.98%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                | 2        | 0.98%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                | 2        | 0.98%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter      | 2        | 0.98%   |
| Microsoft Xbox Wireless Adapter for Windows                     | 2        | 0.98%   |
| Microsoft Xbox 360 Wireless Adapter                             | 2        | 0.98%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter   | 2        | 0.98%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 318      | 49.53%  |
| Intel                    | 217      | 33.8%   |
| Qualcomm Atheros         | 31       | 4.83%   |
| Broadcom                 | 21       | 3.27%   |
| Nvidia                   | 12       | 1.87%   |
| Broadcom Limited         | 7        | 1.09%   |
| Aquantia                 | 7        | 1.09%   |
| Marvell Technology Group | 5        | 0.78%   |
| TP-Link                  | 3        | 0.47%   |
| Samsung Electronics      | 3        | 0.47%   |
| Xiaomi                   | 2        | 0.31%   |
| VIA Technologies         | 2        | 0.31%   |
| MediaTek                 | 2        | 0.31%   |
| Giga-Byte Technology     | 2        | 0.31%   |
| ASIX Electronics         | 2        | 0.31%   |
| Qualcomm                 | 1        | 0.16%   |
| QNAP System              | 1        | 0.16%   |
| QLogic                   | 1        | 0.16%   |
| Huawei Technologies      | 1        | 0.16%   |
| HMD Global               | 1        | 0.16%   |
| DisplayLink              | 1        | 0.16%   |
| D-Link System            | 1        | 0.16%   |
| 3Com                     | 1        | 0.16%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 277      | 41.28%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 37       | 5.51%   |
| Intel I211 Gigabit Network Connection                                  | 33       | 4.92%   |
| Realtek RTL8125 2.5GbE Controller                                      | 27       | 4.02%   |
| Intel Ethernet Connection (2) I219-V                                   | 24       | 3.58%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 23       | 3.43%   |
| Intel Ethernet Connection I217-LM                                      | 18       | 2.68%   |
| Intel Ethernet Connection I217-V                                       | 11       | 1.64%   |
| Intel Ethernet Connection (7) I219-V                                   | 10       | 1.49%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 9        | 1.34%   |
| Intel Ethernet Controller I225-V                                       | 9        | 1.34%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 9        | 1.34%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 8        | 1.19%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 7        | 1.04%   |
| Nvidia MCP61 Ethernet                                                  | 7        | 1.04%   |
| Intel 82574L Gigabit Network Connection                                | 7        | 1.04%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                | 7        | 1.04%   |
| Intel 82579V Gigabit Network Connection                                | 6        | 0.89%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 5        | 0.75%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 5        | 0.75%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 5        | 0.75%   |
| Intel I210 Gigabit Network Connection                                  | 5        | 0.75%   |
| Intel Ethernet Connection (2) I219-LM                                  | 5        | 0.75%   |
| Intel Ethernet Connection (2) I218-V                                   | 5        | 0.75%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 5        | 0.75%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 4        | 0.6%    |
| Intel Ethernet Connection (14) I219-V                                  | 4        | 0.6%    |
| Intel 82583V Gigabit Network Connection                                | 4        | 0.6%    |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]      | 4        | 0.6%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 3        | 0.45%   |
| Intel Ethernet Controller X550                                         | 3        | 0.45%   |
| Intel Ethernet Connection (5) I219-LM                                  | 3        | 0.45%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 2        | 0.3%    |
| Samsung Galaxy series, misc. (tethering mode)                          | 2        | 0.3%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 2        | 0.3%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 2        | 0.3%    |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 2        | 0.3%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 2        | 0.3%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 2        | 0.3%    |
| Nvidia MCP51 Ethernet Controller                                       | 2        | 0.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 592      | 74.94%  |
| WiFi     | 190      | 24.05%  |
| Modem    | 6        | 0.76%   |
| Unknown  | 2        | 0.25%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 515      | 84.7%   |
| WiFi     | 93       | 15.3%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 438      | 73.24%  |
| 2     | 125      | 20.9%   |
| 3     | 27       | 4.52%   |
| 4     | 4        | 0.67%   |
| 0     | 4        | 0.67%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 500      | 82.51%  |
| Yes  | 106      | 17.49%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 51       | 36.43%  |
| Cambridge Silicon Radio         | 34       | 24.29%  |
| ASUSTek Computer                | 26       | 18.57%  |
| MediaTek                        | 7        | 5%      |
| Realtek Semiconductor           | 5        | 3.57%   |
| Qualcomm Atheros Communications | 2        | 1.43%   |
| IMC Networks                    | 2        | 1.43%   |
| Apple                           | 2        | 1.43%   |
| TP-Link                         | 1        | 0.71%   |
| SINO WEALTH                     | 1        | 0.71%   |
| Micro Star International        | 1        | 0.71%   |
| Lite-On Technology              | 1        | 0.71%   |
| Integrated System Solution      | 1        | 0.71%   |
| Foxconn / Hon Hai               | 1        | 0.71%   |
| Edimax Technology               | 1        | 0.71%   |
| Conwise Technology              | 1        | 0.71%   |
| Broadcom                        | 1        | 0.71%   |
| Belkin Components               | 1        | 0.71%   |
| Accel Semiconductor             | 1        | 0.71%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)     | 34       | 24.29%  |
| Intel AX200 Bluetooth                                   | 20       | 14.29%  |
| ASUS Broadcom BCM20702A0 Bluetooth                      | 18       | 12.86%  |
| Intel Bluetooth wireless interface                      | 9        | 6.43%   |
| MediaTek Wireless_Device                                | 7        | 5%      |
| Intel AX201 Bluetooth                                   | 7        | 5%      |
| ASUS ASUS USB-BT500                                     | 7        | 5%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)          | 5        | 3.57%   |
| Intel Wireless-AC 3168 Bluetooth                        | 4        | 2.86%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                | 3        | 2.14%   |
| Realtek  Bluetooth 4.2 Adapter                          | 2        | 1.43%   |
| Realtek Bluetooth Radio                                 | 2        | 1.43%   |
| Intel AX210 Bluetooth                                   | 2        | 1.43%   |
| Apple Bluetooth Host Controller                         | 2        | 1.43%   |
| TP-Link UB500 Adapter                                   | 1        | 0.71%   |
| SINO WEALTH RK Bluetooth Keyboar                        | 1        | 0.71%   |
| Realtek RTL8723B Bluetooth                              | 1        | 0.71%   |
| Qualcomm Atheros  Bluetooth Device                      | 1        | 0.71%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                  | 1        | 0.71%   |
| Micro Star International Bluetooth Device               | 1        | 0.71%   |
| Lite-On Bluetooth Radio                                 | 1        | 0.71%   |
| Intel Bluetooth Device                                  | 1        | 0.71%   |
| Integrated System Solution Bluetooth Device             | 1        | 0.71%   |
| IMC Networks Wireless_Device                            | 1        | 0.71%   |
| IMC Networks Bluetooth Radio                            | 1        | 0.71%   |
| Foxconn / Hon Hai Wireless_Device                       | 1        | 0.71%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter | 1        | 0.71%   |
| Conwise CW6622                                          | 1        | 0.71%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter        | 1        | 0.71%   |
| Belkin Components Bluetooth Mini Dongle                 | 1        | 0.71%   |
| ASUS BCM20702A0                                         | 1        | 0.71%   |
| Accel Bluetooth Device                                  | 1        | 0.71%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 381      | 39.24%  |
| AMD                                          | 228      | 23.48%  |
| Nvidia                                       | 217      | 22.35%  |
| C-Media Electronics                          | 31       | 3.19%   |
| Creative Labs                                | 22       | 2.27%   |
| Logitech                                     | 9        | 0.93%   |
| Trust                                        | 7        | 0.72%   |
| Texas Instruments                            | 6        | 0.62%   |
| Creative Technology                          | 6        | 0.62%   |
| Giga-Byte Technology                         | 5        | 0.51%   |
| ASUSTek Computer                             | 5        | 0.51%   |
| Kingston Technology                          | 4        | 0.41%   |
| Tenx Technology                              | 3        | 0.31%   |
| Razer USA                                    | 3        | 0.31%   |
| Generalplus Technology                       | 3        | 0.31%   |
| DSEA A/S                                     | 3        | 0.31%   |
| JMTek                                        | 2        | 0.21%   |
| GYROCOM C&C                                  | 2        | 0.21%   |
| GN Netcom                                    | 2        | 0.21%   |
| Focusrite-Novation                           | 2        | 0.21%   |
| Edifier Technology                           | 2        | 0.21%   |
| Corsair                                      | 2        | 0.21%   |
| Audio-Technica                               | 2        | 0.21%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.1%    |
| XMOS                                         | 1        | 0.1%    |
| VIA Technologies                             | 1        | 0.1%    |
| Thesycon Systemsoftware & Consulting         | 1        | 0.1%    |
| TEAC                                         | 1        | 0.1%    |
| Studiologic                                  | 1        | 0.1%    |
| Sennheiser Communications                    | 1        | 0.1%    |
| Samson Technologies                          | 1        | 0.1%    |
| Realtek Semiconductor                        | 1        | 0.1%    |
| Plantronics                                  | 1        | 0.1%    |
| OnePlus Technology (Shenzhen)                | 1        | 0.1%    |
| Nam Tai E&E Products                         | 1        | 0.1%    |
| Microsoft                                    | 1        | 0.1%    |
| KTMicro                                      | 1        | 0.1%    |
| iCreate Technologies                         | 1        | 0.1%    |
| Holtek Semiconductor                         | 1        | 0.1%    |
| EGO SYStems                                  | 1        | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 52       | 4.57%   |
| AMD Starship/Matisse HD Audio Controller                                          | 49       | 4.31%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 46       | 4.05%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 37       | 3.25%   |
| AMD Family 17h/19h HD Audio Controller                                            | 36       | 3.17%   |
| Intel 200 Series PCH HD Audio                                                     | 35       | 3.08%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 35       | 3.08%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 34       | 2.99%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 33       | 2.9%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 31       | 2.73%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 30       | 2.64%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 27       | 2.37%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 24       | 2.11%   |
| Intel Cannon Lake PCH cAVS                                                        | 22       | 1.93%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 22       | 1.93%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 22       | 1.93%   |
| AMD FCH Azalia Controller                                                         | 19       | 1.67%   |
| Nvidia GP104 High Definition Audio Controller                                     | 17       | 1.5%    |
| Nvidia High Definition Audio Controller                                           | 16       | 1.41%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 16       | 1.41%   |
| Nvidia GF108 High Definition Audio Controller                                     | 15       | 1.32%   |
| AMD Navi 10 HDMI Audio                                                            | 15       | 1.32%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 14       | 1.23%   |
| Nvidia GP106 High Definition Audio Controller                                     | 13       | 1.14%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 13       | 1.14%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 13       | 1.14%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 12       | 1.06%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 11       | 0.97%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 11       | 0.97%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 11       | 0.97%   |
| Nvidia TU104 HD Audio Controller                                                  | 9        | 0.79%   |
| Nvidia GP108 High Definition Audio Controller                                     | 9        | 0.79%   |
| Nvidia GK107 HDMI Audio Controller                                                | 9        | 0.79%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 9        | 0.79%   |
| Nvidia TU116 High Definition Audio Controller                                     | 8        | 0.7%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 8        | 0.7%    |
| Nvidia MCP61 High Definition Audio                                                | 7        | 0.62%   |
| Nvidia GM206 High Definition Audio Controller                                     | 7        | 0.62%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 7        | 0.62%   |
| Intel Alder Lake-S HD Audio Controller                                            | 7        | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Kingston                   | 87       | 22.37%  |
| Corsair                    | 54       | 13.88%  |
| Unknown                    | 53       | 13.62%  |
| Samsung Electronics        | 49       | 12.6%   |
| SK hynix                   | 33       | 8.48%   |
| G.Skill                    | 17       | 4.37%   |
| Crucial                    | 17       | 4.37%   |
| Micron Technology          | 12       | 3.08%   |
| A-DATA Technology          | 11       | 2.83%   |
| Nanya Technology           | 9        | 2.31%   |
| Kingmax                    | 8        | 2.06%   |
| Ramaxel Technology         | 7        | 1.8%    |
| Elpida                     | 5        | 1.29%   |
| Qimonda                    | 3        | 0.77%   |
| Patriot                    | 3        | 0.77%   |
| GOODRAM                    | 3        | 0.77%   |
| Unknown                    | 3        | 0.77%   |
| Golden Empire              | 2        | 0.51%   |
| Apacer                     | 2        | 0.51%   |
| Unknown (ABCD)             | 1        | 0.26%   |
| Unknown (7F7F7F94FFFFFFFF) | 1        | 0.26%   |
| Unknown (0x9801)           | 1        | 0.26%   |
| Team                       | 1        | 0.26%   |
| TakeMS                     | 1        | 0.26%   |
| Silicon Power              | 1        | 0.26%   |
| S                          | 1        | 0.26%   |
| H                          | 1        | 0.26%   |
| Exceleram                  | 1        | 0.26%   |
| Atermiter                  | 1        | 0.26%   |
| AMD                        | 1        | 0.26%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Samsung RAM M4 70T5663RZ3-CE6 2GB SODIMM DDR2 667MT/s   | 10       | 2.29%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s     | 8        | 1.83%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                  | 6        | 1.37%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2666MT/s       | 6        | 1.37%   |
| Unknown RAM Module 2048MB DIMM SDRAM                    | 5        | 1.14%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s     | 5        | 1.14%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s    | 4        | 0.92%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s       | 4        | 0.92%   |
| Kingston RAM KHX2133C14D4/4G 4GB DIMM DDR4 2933MT/s     | 4        | 0.92%   |
| Corsair RAM CMZ16GX3M2A1600C9 8GB DIMM DDR3 1600MT/s    | 4        | 0.92%   |
| Corsair RAM CMK32GX4M2B3000C15 16GB DIMM DDR4 3000MT/s  | 4        | 0.92%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s   | 4        | 0.92%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                    | 3        | 0.69%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s     | 3        | 0.69%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s     | 3        | 0.69%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s     | 3        | 0.69%   |
| Qimonda RAM 64T128020HU3SB 1GB DIMM DDR2 667MT/s        | 3        | 0.69%   |
| Nanya RAM NT1GT64U8HB0BY-3C 1GB DIMM DDR2 667MT/s       | 3        | 0.69%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s    | 3        | 0.69%   |
| Kingston RAM KHX1600C9D3/8GX 8192MB DIMM DDR3 2133MT/s  | 3        | 0.69%   |
| Kingston RAM 99U5458-005.A01LF 4GB DIMM DDR3 1333MT/s   | 3        | 0.69%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s     | 3        | 0.69%   |
| Unknown                                                 | 3        | 0.69%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s               | 2        | 0.46%   |
| Unknown RAM Module 4GB DIMM 400MT/s                     | 2        | 0.46%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s            | 2        | 0.46%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s               | 2        | 0.46%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                | 2        | 0.46%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s            | 2        | 0.46%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s             | 2        | 0.46%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                  | 2        | 0.46%   |
| Unknown RAM Module 1024MB DIMM                          | 2        | 0.46%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s    | 2        | 0.46%   |
| SK hynix RAM HMT351U6EFR8C-PB 4096MB DIMM DDR3 1800MT/s | 2        | 0.46%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s    | 2        | 0.46%   |
| SK hynix RAM HMT325U6BFR8C-H9 2GB DIMM DDR3 1333MT/s    | 2        | 0.46%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s    | 2        | 0.46%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s     | 2        | 0.46%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s     | 2        | 0.46%   |
| Ramaxel RAM RML1520EC48D7W-800 1GB DIMM DDR2 800MT/s    | 2        | 0.46%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 132      | 38.94%  |
| DDR3    | 116      | 34.22%  |
| DDR2    | 34       | 10.03%  |
| SDRAM   | 21       | 6.19%   |
| Unknown | 21       | 6.19%   |
| DDR5    | 11       | 3.24%   |
| DDR     | 3        | 0.88%   |
| LPDDR4  | 1        | 0.29%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 298      | 91.69%  |
| SODIMM  | 25       | 7.69%   |
| RIMM    | 1        | 0.31%   |
| FB-DIMM | 1        | 0.31%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 110      | 30.05%  |
| 4096  | 88       | 24.04%  |
| 2048  | 68       | 18.58%  |
| 16384 | 54       | 14.75%  |
| 1024  | 29       | 7.92%   |
| 32768 | 13       | 3.55%   |
| 512   | 4        | 1.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 60       | 15.67%  |
| 1333    | 46       | 12.01%  |
| 667     | 26       | 6.79%   |
| 800     | 25       | 6.53%   |
| 2400    | 24       | 6.27%   |
| 3600    | 21       | 5.48%   |
| 3200    | 21       | 5.48%   |
| 2667    | 18       | 4.7%    |
| 2133    | 15       | 3.92%   |
| 3000    | 10       | 2.61%   |
| 2666    | 10       | 2.61%   |
| Unknown | 9        | 2.35%   |
| 3733    | 8        | 2.09%   |
| 1866    | 7        | 1.83%   |
| 3400    | 6        | 1.57%   |
| 1867    | 6        | 1.57%   |
| 6000    | 4        | 1.04%   |
| 2933    | 4        | 1.04%   |
| 1800    | 4        | 1.04%   |
| 533     | 4        | 1.04%   |
| 3866    | 3        | 0.78%   |
| 3800    | 3        | 0.78%   |
| 3500    | 3        | 0.78%   |
| 1066    | 3        | 0.78%   |
| 4800    | 2        | 0.52%   |
| 3466    | 2        | 0.52%   |
| 3333    | 2        | 0.52%   |
| 3066    | 2        | 0.52%   |
| 2800    | 2        | 0.52%   |
| 2048    | 2        | 0.52%   |
| 1648    | 2        | 0.52%   |
| 1334    | 2        | 0.52%   |
| 1331    | 2        | 0.52%   |
| 1067    | 2        | 0.52%   |
| 400     | 2        | 0.52%   |
| 49926   | 1        | 0.26%   |
| 8192    | 1        | 0.26%   |
| 5900    | 1        | 0.26%   |
| 5808    | 1        | 0.26%   |
| 5800    | 1        | 0.26%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 6        | 20%     |
| Brother Industries    | 6        | 20%     |
| Samsung Electronics   | 5        | 16.67%  |
| Seiko Epson           | 4        | 13.33%  |
| Canon                 | 4        | 13.33%  |
| Zebra                 | 1        | 3.33%   |
| Xerox                 | 1        | 3.33%   |
| QinHeng Electronics   | 1        | 3.33%   |
| Lexmark International | 1        | 3.33%   |
| ATEN International    | 1        | 3.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Samsung M2070 Series                          | 2        | 6.67%   |
| HP DeskJet 2130 series                        | 2        | 6.67%   |
| Canon MF4010 series                           | 2        | 6.67%   |
| Zebra GK420t Label Printer                    | 1        | 3.33%   |
| Xerox Phaser 6130N                            | 1        | 3.33%   |
| Seiko Epson ME 340 Series/Stylus NX130 Series | 1        | 3.33%   |
| Seiko Epson L6160 Series                      | 1        | 3.33%   |
| Seiko Epson L3150 Series                      | 1        | 3.33%   |
| Seiko Epson ET-2600 Series                    | 1        | 3.33%   |
| Samsung ML-216x Series Laser Printer          | 1        | 3.33%   |
| Samsung M267x 287x Series                     | 1        | 3.33%   |
| Samsung CLP-310 Color Laser Printer           | 1        | 3.33%   |
| QinHeng CH340S                                | 1        | 3.33%   |
| Lexmark International InkJet Color Printer    | 1        | 3.33%   |
| HP LaserJet 3050                              | 1        | 3.33%   |
| HP HP LaserJet M14-M17                        | 1        | 3.33%   |
| HP DeskJet F2492 All-in-One                   | 1        | 3.33%   |
| HP Deskjet 3050A                              | 1        | 3.33%   |
| Canon PIXMA MP280                             | 1        | 3.33%   |
| Canon MF3110                                  | 1        | 3.33%   |
| Brother MFC-7420                              | 1        | 3.33%   |
| Brother HL-5380DN series                      | 1        | 3.33%   |
| Brother HL-5250DN Printer                     | 1        | 3.33%   |
| Brother HL-1210W series                       | 1        | 3.33%   |
| Brother HL-1110 series                        | 1        | 3.33%   |
| Brother DCP-7030                              | 1        | 3.33%   |
| ATEN International UC-1284B Printer Port      | 1        | 3.33%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LiDE 100 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 24       | 26.97%  |
| Microdia                      | 14       | 15.73%  |
| Microsoft                     | 9        | 10.11%  |
| Sunplus Innovation Technology | 6        | 6.74%   |
| Samsung Electronics           | 3        | 3.37%   |
| GEMBIRD                       | 3        | 3.37%   |
| Apple                         | 3        | 3.37%   |
| Z-Star Microelectronics       | 2        | 2.25%   |
| Realtek Semiconductor         | 2        | 2.25%   |
| Jieli Technology              | 2        | 2.25%   |
| Cubeternet                    | 2        | 2.25%   |
| Chicony Electronics           | 2        | 2.25%   |
| Aveo Technology               | 2        | 2.25%   |
| Arkmicro Technologies         | 2        | 2.25%   |
| WaveRider Communications      | 1        | 1.12%   |
| Unknown                       | 1        | 1.12%   |
| Novatek Microelectronics      | 1        | 1.12%   |
| Nikon                         | 1        | 1.12%   |
| MacroSilicon                  | 1        | 1.12%   |
| Lenovo                        | 1        | 1.12%   |
| KYE Systems (Mouse Systems)   | 1        | 1.12%   |
| Jeilin Technology             | 1        | 1.12%   |
| IMC Networks                  | 1        | 1.12%   |
| Huawei Technologies           | 1        | 1.12%   |
| Generalplus Technology        | 1        | 1.12%   |
| ARC International             | 1        | 1.12%   |
| Alcor Micro                   | 1        | 1.12%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Microsoft LifeCam HD-3000                   | 6        | 6.74%   |
| Microdia Camera                             | 5        | 5.62%   |
| Logitech HD Pro Webcam C920                 | 4        | 4.49%   |
| Sunplus FHD Camera Microphone               | 3        | 3.37%   |
| Samsung Galaxy series, misc. (MTP mode)     | 3        | 3.37%   |
| Microdia Sonix USB 2.0 Camera               | 3        | 3.37%   |
| Logitech QuickCam Pro 9000                  | 3        | 3.37%   |
| Sunplus Full HD webcam                      | 2        | 2.25%   |
| Microdia Integrated Camera                  | 2        | 2.25%   |
| Microdia HP Integrated Webcam               | 2        | 2.25%   |
| Logitech Webcam C270                        | 2        | 2.25%   |
| Logitech Webcam C170                        | 2        | 2.25%   |
| Logitech C920 PRO HD Webcam                 | 2        | 2.25%   |
| Jieli USB PHY 2.0                           | 2        | 2.25%   |
| GEMBIRD USB2.0 PC CAMERA                    | 2        | 2.25%   |
| Arkmicro USB2.0 PC CAMERA                   | 2        | 2.25%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR          | 2        | 2.25%   |
| Z-Star Venus USB2.0 Camera                  | 1        | 1.12%   |
| Z-Star A4 TECH HD PC Camera                 | 1        | 1.12%   |
| WaveRider USB Live camera                   | 1        | 1.12%   |
| Unknown HD camera                           | 1        | 1.12%   |
| Sunplus HD 720P webcam                      | 1        | 1.12%   |
| Realtek USB Camera                          | 1        | 1.12%   |
| Realtek Full HD webcam                      | 1        | 1.12%   |
| Novatek HP High Definition 2MP Webcam       | 1        | 1.12%   |
| Nikon DSC D3200                             | 1        | 1.12%   |
| Microsoft LifeCam VX-7000 (UVC-compliant)   | 1        | 1.12%   |
| Microsoft LifeCam VX-500 [1357]             | 1        | 1.12%   |
| Microsoft LifeCam VX-2000                   | 1        | 1.12%   |
| Microdia USB 2.0 Camera                     | 1        | 1.12%   |
| Microdia Defender G-Lens 2577 HD720p Camera | 1        | 1.12%   |
| MacroSilicon USB3. 0 capture                | 1        | 1.12%   |
| Logitech Webcam C310                        | 1        | 1.12%   |
| Logitech Webcam C250                        | 1        | 1.12%   |
| Logitech Webcam C110                        | 1        | 1.12%   |
| Logitech Webcam B500                        | 1        | 1.12%   |
| Logitech StreamCam                          | 1        | 1.12%   |
| Logitech Logitech Webcam C100               | 1        | 1.12%   |
| Logitech HD Webcam C615                     | 1        | 1.12%   |
| Logitech HD Webcam C525                     | 1        | 1.12%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| LighTuning Technology | 1        | 33.33%  |
| Focal-systems.Corp    | 1        | 33.33%  |
| AuthenTec             | 1        | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| LighTuning Fingerprint Sensor             | 1        | 33.33%  |
| Focal-systems.Corp FT9201Fingerprint.Ì | 1        | 33.33%  |
| AuthenTec AES2810                         | 1        | 33.33%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Fujitsu Siemens Computers | 1        | 50%     |
| Chicony Electronics       | 1        | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Fujitsu Siemens Computers SmartCard Reader 2A        | 1        | 50%     |
| Chicony Electronics HP Skylab USB Smartcard Keyboard | 1        | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 511      | 84.18%  |
| 1     | 86       | 14.17%  |
| 2     | 9        | 1.48%   |
| 3     | 1        | 0.16%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 41       | 39.81%  |
| Net/wireless             | 26       | 25.24%  |
| Unassigned class         | 6        | 5.83%   |
| Communication controller | 6        | 5.83%   |
| Sound                    | 4        | 3.88%   |
| Multimedia controller    | 4        | 3.88%   |
| Fingerprint reader       | 3        | 2.91%   |
| Camera                   | 3        | 2.91%   |
| Storage/ide              | 2        | 1.94%   |
| Bluetooth                | 2        | 1.94%   |
| Unclassified device      | 1        | 0.97%   |
| Storage/raid             | 1        | 0.97%   |
| Storage                  | 1        | 0.97%   |
| Net/ethernet             | 1        | 0.97%   |
| Chipcard                 | 1        | 0.97%   |
| Card reader              | 1        | 0.97%   |

