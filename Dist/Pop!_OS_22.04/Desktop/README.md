Pop!_OS 22.04 - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------

A project to collect tested hardware configurations for Pop!_OS 22.04.

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

Total: 259

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | MPG X570 GAMING EDGE WIF... | [7da3547526](https://linux-hardware.org/?probe=7da3547526) | Jul 01, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [d979555615](https://linux-hardware.org/?probe=d979555615) | Jul 01, 2022 |
| ASRock        | B450 Gaming K4              | [2bdfc5f472](https://linux-hardware.org/?probe=2bdfc5f472) | Jul 01, 2022 |
| MSI           | B250M PRO-VD                | [b48e88849b](https://linux-hardware.org/?probe=b48e88849b) | Jul 01, 2022 |
| ASUSTek       | Maximus IX FORMULA          | [8c29343495](https://linux-hardware.org/?probe=8c29343495) | Jul 01, 2022 |
| ASUSTek       | Maximus IX FORMULA          | [2631bf2ae1](https://linux-hardware.org/?probe=2631bf2ae1) | Jul 01, 2022 |
| HP            | 18E7                        | [1808b6dee4](https://linux-hardware.org/?probe=1808b6dee4) | Jul 01, 2022 |
| Dell          | 0HHV7N A00                  | [41255f7150](https://linux-hardware.org/?probe=41255f7150) | Jun 30, 2022 |
| ASRock        | X399 Taichi                 | [caea75035f](https://linux-hardware.org/?probe=caea75035f) | Jun 30, 2022 |
| Gigabyte      | B450 AORUS M                | [b85b1f9277](https://linux-hardware.org/?probe=b85b1f9277) | Jun 30, 2022 |
| Gigabyte      | B450 AORUS M                | [67dc174a62](https://linux-hardware.org/?probe=67dc174a62) | Jun 29, 2022 |
| Lenovo        | 36C5 NOK                    | [94d44ae5f2](https://linux-hardware.org/?probe=94d44ae5f2) | Jun 29, 2022 |
| Lenovo        | 36C5 NOK                    | [cd5e39b07a](https://linux-hardware.org/?probe=cd5e39b07a) | Jun 29, 2022 |
| MSI           | B450M PRO-VDH MAX           | [f01192b57e](https://linux-hardware.org/?probe=f01192b57e) | Jun 29, 2022 |
| Gigabyte      | Z97X-SLI-CF                 | [0a66ce61c6](https://linux-hardware.org/?probe=0a66ce61c6) | Jun 29, 2022 |
| Gigabyte      | Z97X-SLI-CF                 | [f2b790de57](https://linux-hardware.org/?probe=f2b790de57) | Jun 29, 2022 |
| HP            | 3647h                       | [3227f38f98](https://linux-hardware.org/?probe=3227f38f98) | Jun 28, 2022 |
| Gigabyte      | Z170-Gaming K3              | [70dc9ba605](https://linux-hardware.org/?probe=70dc9ba605) | Jun 28, 2022 |
| MSI           | B250M PRO-VD                | [8efb1d3556](https://linux-hardware.org/?probe=8efb1d3556) | Jun 28, 2022 |
| MSI           | B250M PRO-VD                | [5b239d8bba](https://linux-hardware.org/?probe=5b239d8bba) | Jun 28, 2022 |
| ASRock        | B450 Gaming K4              | [6ecc609381](https://linux-hardware.org/?probe=6ecc609381) | Jun 27, 2022 |
| ASRock        | B450 Steel Legend           | [6f8f8a9df6](https://linux-hardware.org/?probe=6f8f8a9df6) | Jun 26, 2022 |
| ASRock        | B450 Steel Legend           | [547aab5039](https://linux-hardware.org/?probe=547aab5039) | Jun 26, 2022 |
| ASUSTek       | VM40B                       | [35f67bace1](https://linux-hardware.org/?probe=35f67bace1) | Jun 26, 2022 |
| Dell          | 0D6H9T A00                  | [fd65f44d25](https://linux-hardware.org/?probe=fd65f44d25) | Jun 26, 2022 |
| MSI           | MPG B460I GAMING EDGE WI... | [6580b51e30](https://linux-hardware.org/?probe=6580b51e30) | Jun 25, 2022 |
| MSI           | MPG B460I GAMING EDGE WI... | [01fcd4495e](https://linux-hardware.org/?probe=01fcd4495e) | Jun 25, 2022 |
| Dell          | 040DDP A00                  | [02721926a7](https://linux-hardware.org/?probe=02721926a7) | Jun 25, 2022 |
| MSI           | MAG Z690 TORPEDO            | [44700880cf](https://linux-hardware.org/?probe=44700880cf) | Jun 24, 2022 |
| ASUSTek       | LEUCITE                     | [c4d2ed5723](https://linux-hardware.org/?probe=c4d2ed5723) | Jun 24, 2022 |
| MSI           | MAG Z690 TORPEDO            | [517a155f9b](https://linux-hardware.org/?probe=517a155f9b) | Jun 24, 2022 |
| Dell          | 0WMJ54 A01                  | [ee865231c1](https://linux-hardware.org/?probe=ee865231c1) | Jun 24, 2022 |
| Gigabyte      | G1.Sniper M3-CF             | [055977bdee](https://linux-hardware.org/?probe=055977bdee) | Jun 23, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [f3d1eeadb3](https://linux-hardware.org/?probe=f3d1eeadb3) | Jun 23, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [1e7e58ae1d](https://linux-hardware.org/?probe=1e7e58ae1d) | Jun 23, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [0bd1e7d592](https://linux-hardware.org/?probe=0bd1e7d592) | Jun 23, 2022 |
| ASUSTek       | PRIME B550M-A               | [d4492d1e5d](https://linux-hardware.org/?probe=d4492d1e5d) | Jun 23, 2022 |
| ASUSTek       | PRIME X570-PRO              | [ae30cadddf](https://linux-hardware.org/?probe=ae30cadddf) | Jun 22, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [21d1dc43e6](https://linux-hardware.org/?probe=21d1dc43e6) | Jun 22, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [27bc9defca](https://linux-hardware.org/?probe=27bc9defca) | Jun 22, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [941b96e6ab](https://linux-hardware.org/?probe=941b96e6ab) | Jun 22, 2022 |
| BESSTAR Te... | UM700                       | [5dc08ee2d7](https://linux-hardware.org/?probe=5dc08ee2d7) | Jun 22, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [d5fd58e3b0](https://linux-hardware.org/?probe=d5fd58e3b0) | Jun 21, 2022 |
| ASUSTek       | PRIME Z370-A                | [8dca736a46](https://linux-hardware.org/?probe=8dca736a46) | Jun 21, 2022 |
| ASUSTek       | P7H55-M LX                  | [f747d1bfd3](https://linux-hardware.org/?probe=f747d1bfd3) | Jun 21, 2022 |
| System76      | Thelio thelio-r2            | [b9b9d5ffda](https://linux-hardware.org/?probe=b9b9d5ffda) | Jun 21, 2022 |
| MSI           | B550M-A PRO                 | [1765b91360](https://linux-hardware.org/?probe=1765b91360) | Jun 21, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [eb61c79793](https://linux-hardware.org/?probe=eb61c79793) | Jun 21, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | [6ddca91c97](https://linux-hardware.org/?probe=6ddca91c97) | Jun 21, 2022 |
| Biostar       | N68S3+                      | [efe83d16ac](https://linux-hardware.org/?probe=efe83d16ac) | Jun 21, 2022 |
| Intel         | MAHOBAY                     | [f615165669](https://linux-hardware.org/?probe=f615165669) | Jun 21, 2022 |
| ASRock        | B450 Gaming K4              | [230bdf84a1](https://linux-hardware.org/?probe=230bdf84a1) | Jun 20, 2022 |
| MSI           | MPG Z490 GAMING PLUS        | [ec3bc83e7a](https://linux-hardware.org/?probe=ec3bc83e7a) | Jun 20, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [d5af99ece6](https://linux-hardware.org/?probe=d5af99ece6) | Jun 20, 2022 |
| ASUSTek       | P8Z77-V LX                  | [ad271e0eec](https://linux-hardware.org/?probe=ad271e0eec) | Jun 19, 2022 |
| Gigabyte      | Z590 AORUS ELITE AX         | [3d4d492e9d](https://linux-hardware.org/?probe=3d4d492e9d) | Jun 19, 2022 |
| Dell          | 0YXT71 A03                  | [890e65c781](https://linux-hardware.org/?probe=890e65c781) | Jun 19, 2022 |
| HP            | 158B                        | [b66a2770e7](https://linux-hardware.org/?probe=b66a2770e7) | Jun 18, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [6ba04b0f37](https://linux-hardware.org/?probe=6ba04b0f37) | Jun 18, 2022 |
| BESSTAR Te... | UM700                       | [d0c247db91](https://linux-hardware.org/?probe=d0c247db91) | Jun 17, 2022 |
| Intel         | MAHOBAY                     | [755ead951d](https://linux-hardware.org/?probe=755ead951d) | Jun 17, 2022 |
| Gigabyte      | B450M DS3H WIFI-CF          | [5241a60357](https://linux-hardware.org/?probe=5241a60357) | Jun 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [f4178c276d](https://linux-hardware.org/?probe=f4178c276d) | Jun 16, 2022 |
| Intel         | MAHOBAY                     | [91039940ea](https://linux-hardware.org/?probe=91039940ea) | Jun 16, 2022 |
| Lenovo        | 3715 SDK0L77769 WIN 3423... | [16d122d03e](https://linux-hardware.org/?probe=16d122d03e) | Jun 16, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [24140a62de](https://linux-hardware.org/?probe=24140a62de) | Jun 16, 2022 |
| Foxconn       | G41MX/G41MX-K 2.0 1.0       | [f5af934210](https://linux-hardware.org/?probe=f5af934210) | Jun 16, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [7cebf6f4c1](https://linux-hardware.org/?probe=7cebf6f4c1) | Jun 16, 2022 |
| MSI           | B450 TOMAHAWK               | [e11d001f52](https://linux-hardware.org/?probe=e11d001f52) | Jun 15, 2022 |
| MSI           | MPG Z390 GAMING EDGE AC     | [29cfeda814](https://linux-hardware.org/?probe=29cfeda814) | Jun 15, 2022 |
| Gigabyte      | 970A-DS3P                   | [b12643d9ac](https://linux-hardware.org/?probe=b12643d9ac) | Jun 15, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [d4e4001c4c](https://linux-hardware.org/?probe=d4e4001c4c) | Jun 15, 2022 |
| Medion        | MS-7728                     | [ae02539c17](https://linux-hardware.org/?probe=ae02539c17) | Jun 15, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [5be4039515](https://linux-hardware.org/?probe=5be4039515) | Jun 15, 2022 |
| ASUSTek       | TUF X299 MARK 2             | [507c214577](https://linux-hardware.org/?probe=507c214577) | Jun 15, 2022 |
| MSI           | B550-A PRO                  | [f7201ee1de](https://linux-hardware.org/?probe=f7201ee1de) | Jun 14, 2022 |
| HP            | 1905                        | [b3d0170095](https://linux-hardware.org/?probe=b3d0170095) | Jun 14, 2022 |
| HP            | 18E7                        | [9f82638329](https://linux-hardware.org/?probe=9f82638329) | Jun 14, 2022 |
| Lenovo        | 0B98401 PRO                 | [23de86aa97](https://linux-hardware.org/?probe=23de86aa97) | Jun 14, 2022 |
| Alienware     | 0R3FWM A00                  | [6690a39447](https://linux-hardware.org/?probe=6690a39447) | Jun 13, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [f9e74fdcd3](https://linux-hardware.org/?probe=f9e74fdcd3) | Jun 13, 2022 |
| Dell          | 073MMW A03                  | [3e206d2462](https://linux-hardware.org/?probe=3e206d2462) | Jun 13, 2022 |
| ASUSTek       | Z87-K                       | [cafc34944d](https://linux-hardware.org/?probe=cafc34944d) | Jun 13, 2022 |
| MSI           | B350 PC MATE                | [baf792ad50](https://linux-hardware.org/?probe=baf792ad50) | Jun 12, 2022 |
| ASUSTek       | PRIME H570M-PLUS            | [a332c946a2](https://linux-hardware.org/?probe=a332c946a2) | Jun 11, 2022 |
| Gigabyte      | G1.Sniper M3-CF             | [d02f89642d](https://linux-hardware.org/?probe=d02f89642d) | Jun 11, 2022 |
| ASUSTek       | ROG STRIX B560-F GAMING ... | [a4277bcba9](https://linux-hardware.org/?probe=a4277bcba9) | Jun 11, 2022 |
| MSI           | MEG X570 ACE                | [d88374c06d](https://linux-hardware.org/?probe=d88374c06d) | Jun 11, 2022 |
| Unknown       | Unknown                     | [19d1362c66](https://linux-hardware.org/?probe=19d1362c66) | Jun 10, 2022 |
| Gigabyte      | H87M-HD3                    | [eadd724efa](https://linux-hardware.org/?probe=eadd724efa) | Jun 10, 2022 |
| MSI           | H97 GAMING 3                | [839bbee3fa](https://linux-hardware.org/?probe=839bbee3fa) | Jun 10, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [1fef4f1cf3](https://linux-hardware.org/?probe=1fef4f1cf3) | Jun 10, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [9c7b34c996](https://linux-hardware.org/?probe=9c7b34c996) | Jun 09, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [70254d6e4d](https://linux-hardware.org/?probe=70254d6e4d) | Jun 08, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [44a6f3e33d](https://linux-hardware.org/?probe=44a6f3e33d) | Jun 07, 2022 |
| Gigabyte      | Z390 UD                     | [cd4b8b609f](https://linux-hardware.org/?probe=cd4b8b609f) | Jun 07, 2022 |
| Dell          | 0JW6C6 A01                  | [34d9fc3968](https://linux-hardware.org/?probe=34d9fc3968) | Jun 06, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [56c4428636](https://linux-hardware.org/?probe=56c4428636) | Jun 06, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [a0c155ffb9](https://linux-hardware.org/?probe=a0c155ffb9) | Jun 05, 2022 |
| ASUSTek       | P6X58D PREMIUM              | [816b4e757d](https://linux-hardware.org/?probe=816b4e757d) | Jun 05, 2022 |
| ASUSTek       | Rampage V EDITION 10        | [e92e195362](https://linux-hardware.org/?probe=e92e195362) | Jun 05, 2022 |
| ASUSTek       | P8Z68-V LX                  | [e7e3608105](https://linux-hardware.org/?probe=e7e3608105) | Jun 04, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | [a65dd5834e](https://linux-hardware.org/?probe=a65dd5834e) | Jun 04, 2022 |
| ASUSTek       | P6X58D PREMIUM              | [81bfe17cb5](https://linux-hardware.org/?probe=81bfe17cb5) | Jun 04, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [95db56a864](https://linux-hardware.org/?probe=95db56a864) | Jun 03, 2022 |
| ASUSTek       | Z87-K                       | [915e2819c0](https://linux-hardware.org/?probe=915e2819c0) | Jun 02, 2022 |
| ASRock        | Z390 Phantom Gaming SLI/... | [5f40da7ae9](https://linux-hardware.org/?probe=5f40da7ae9) | Jun 02, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [5348dd6576](https://linux-hardware.org/?probe=5348dd6576) | Jun 01, 2022 |
| ASUSTek       | PRIME Z590-A                | [fa29e357fa](https://linux-hardware.org/?probe=fa29e357fa) | Jun 01, 2022 |
| ASUSTek       | F2A85-M                     | [82b4935292](https://linux-hardware.org/?probe=82b4935292) | Jun 01, 2022 |
| MSI           | Z170A MPOWER GAMING TITA... | [538feade4f](https://linux-hardware.org/?probe=538feade4f) | May 31, 2022 |
| ASUSTek       | PRIME A320M-K               | [bee74ec003](https://linux-hardware.org/?probe=bee74ec003) | May 31, 2022 |
| ASRock        | B450 Steel Legend           | [136730f4ac](https://linux-hardware.org/?probe=136730f4ac) | May 31, 2022 |
| ASRock        | B450 Steel Legend           | [62b7e9aacd](https://linux-hardware.org/?probe=62b7e9aacd) | May 31, 2022 |
| System76      | Thelio Major thelio-majo... | [291730a3bb](https://linux-hardware.org/?probe=291730a3bb) | May 31, 2022 |
| Dell          | 0Y2MRG A00                  | [013e0da975](https://linux-hardware.org/?probe=013e0da975) | May 30, 2022 |
| Dell          | 0D02VH A01                  | [fc97b0a5bf](https://linux-hardware.org/?probe=fc97b0a5bf) | May 30, 2022 |
| ASUSTek       | PRIME Z590-A                | [1058cdf867](https://linux-hardware.org/?probe=1058cdf867) | May 30, 2022 |
| HP            | 8266                        | [d0e35451ab](https://linux-hardware.org/?probe=d0e35451ab) | May 29, 2022 |
| Gigabyte      | H270-Gaming 3               | [c28c21c4d8](https://linux-hardware.org/?probe=c28c21c4d8) | May 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [5d899f8fc5](https://linux-hardware.org/?probe=5d899f8fc5) | May 29, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [d1923db949](https://linux-hardware.org/?probe=d1923db949) | May 29, 2022 |
| Dell          | 0J3C2F A00                  | [c192680ab5](https://linux-hardware.org/?probe=c192680ab5) | May 29, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [b78390767c](https://linux-hardware.org/?probe=b78390767c) | May 28, 2022 |
| MSI           | MS-7717                     | [101b488b80](https://linux-hardware.org/?probe=101b488b80) | May 28, 2022 |
| MSI           | MS-7717                     | [9b0c2d0d8c](https://linux-hardware.org/?probe=9b0c2d0d8c) | May 28, 2022 |
| ASRock        | B450 Steel Legend           | [5d47d967ba](https://linux-hardware.org/?probe=5d47d967ba) | May 28, 2022 |
| Dell          | 040DDP A01                  | [925d3dce8d](https://linux-hardware.org/?probe=925d3dce8d) | May 28, 2022 |
| HP            | 158B                        | [a74e9da8aa](https://linux-hardware.org/?probe=a74e9da8aa) | May 28, 2022 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | [bdf54228e5](https://linux-hardware.org/?probe=bdf54228e5) | May 27, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [f5195788f8](https://linux-hardware.org/?probe=f5195788f8) | May 27, 2022 |
| ASUSTek       | PRIME Z270-A                | [5d1ee4048a](https://linux-hardware.org/?probe=5d1ee4048a) | May 27, 2022 |
| ASUSTek       | P5KPL-SE                    | [c4b27d79ef](https://linux-hardware.org/?probe=c4b27d79ef) | May 26, 2022 |
| ASUSTek       | P5QPL-AM                    | [938ab3ec5c](https://linux-hardware.org/?probe=938ab3ec5c) | May 26, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [ae0ada290a](https://linux-hardware.org/?probe=ae0ada290a) | May 26, 2022 |
| ASRock        | H670M-ITX/ax                | [b3f7ff3d98](https://linux-hardware.org/?probe=b3f7ff3d98) | May 25, 2022 |
| ASUSTek       | M5A78L/USB3                 | [852a292ba3](https://linux-hardware.org/?probe=852a292ba3) | May 25, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [4738560555](https://linux-hardware.org/?probe=4738560555) | May 25, 2022 |
| HP            | 8703                        | [14af29c571](https://linux-hardware.org/?probe=14af29c571) | May 24, 2022 |
| ASRock        | H470M-ITX/ac                | [181f7decc6](https://linux-hardware.org/?probe=181f7decc6) | May 24, 2022 |
| Dell          | 0Y2MRG A00                  | [08527b166e](https://linux-hardware.org/?probe=08527b166e) | May 24, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [1122022ae1](https://linux-hardware.org/?probe=1122022ae1) | May 24, 2022 |
| SIEMENS       | A5E02122237 ES010           | [3d7173e7a3](https://linux-hardware.org/?probe=3d7173e7a3) | May 24, 2022 |
| Lenovo        | MAHOBAY                     | [dbfb736222](https://linux-hardware.org/?probe=dbfb736222) | May 23, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [78bb2ba75c](https://linux-hardware.org/?probe=78bb2ba75c) | May 23, 2022 |
| Foxconn       | 2ABF                        | [39f9e9e717](https://linux-hardware.org/?probe=39f9e9e717) | May 22, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [21818b99b4](https://linux-hardware.org/?probe=21818b99b4) | May 22, 2022 |
| ASRock        | B450 Gaming K4              | [152469abdd](https://linux-hardware.org/?probe=152469abdd) | May 22, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [f1db82519f](https://linux-hardware.org/?probe=f1db82519f) | May 22, 2022 |
| MSI           | MEG Z390 ACE                | [0065576586](https://linux-hardware.org/?probe=0065576586) | May 22, 2022 |
| Gigabyte      | H67N-USB3-B3                | [382f206597](https://linux-hardware.org/?probe=382f206597) | May 21, 2022 |
| ASRock        | B450 Steel Legend           | [3c436952c7](https://linux-hardware.org/?probe=3c436952c7) | May 21, 2022 |
| ASUSTek       | P7P55D-E LX                 | [358e85c524](https://linux-hardware.org/?probe=358e85c524) | May 21, 2022 |
| MSI           | B250M PRO-VD                | [540e0831b1](https://linux-hardware.org/?probe=540e0831b1) | May 20, 2022 |
| ASRock        | TRX40 Creator               | [a810336f3f](https://linux-hardware.org/?probe=a810336f3f) | May 20, 2022 |
| ASRock        | TRX40 Creator               | [6993400976](https://linux-hardware.org/?probe=6993400976) | May 20, 2022 |
| Gigabyte      | GA-78LMT-S2P                | [2211d5c2a2](https://linux-hardware.org/?probe=2211d5c2a2) | May 20, 2022 |
| ASUSTek       | H110M-R                     | [7cae58580a](https://linux-hardware.org/?probe=7cae58580a) | May 20, 2022 |
| ASRock        | Z390 Phantom Gaming 4-IB    | [543ab770e8](https://linux-hardware.org/?probe=543ab770e8) | May 20, 2022 |
| Positivo      | POS-MI945AA                 | [0f9875e8fc](https://linux-hardware.org/?probe=0f9875e8fc) | May 19, 2022 |
| Lenovo        | MAHOBAY                     | [fa1f318919](https://linux-hardware.org/?probe=fa1f318919) | May 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [d94f4b0a43](https://linux-hardware.org/?probe=d94f4b0a43) | May 19, 2022 |
| Gigabyte      | B450 AORUS M                | [5ddfbf547b](https://linux-hardware.org/?probe=5ddfbf547b) | May 19, 2022 |
| Supermicro    | X8SIL                       | [66e8a4001f](https://linux-hardware.org/?probe=66e8a4001f) | May 18, 2022 |
| MSI           | B350M MORTAR                | [fd66fd9a5a](https://linux-hardware.org/?probe=fd66fd9a5a) | May 18, 2022 |
| Supermicro    | X8SIL                       | [5cb6f1067b](https://linux-hardware.org/?probe=5cb6f1067b) | May 18, 2022 |
| HP            | 8054                        | [725f204fd0](https://linux-hardware.org/?probe=725f204fd0) | May 18, 2022 |
| ASUSTek       | GA15DH                      | [ca68812bf2](https://linux-hardware.org/?probe=ca68812bf2) | May 17, 2022 |
| MSI           | Z270-A PRO                  | [f005623f03](https://linux-hardware.org/?probe=f005623f03) | May 17, 2022 |
| ASUSTek       | AM1M-A/BR                   | [e23e8291e0](https://linux-hardware.org/?probe=e23e8291e0) | May 17, 2022 |
| Gigabyte      | AX370M-DS3H-CF              | [2f7a99c28b](https://linux-hardware.org/?probe=2f7a99c28b) | May 17, 2022 |
| ASUSTek       | M4A785TD-V EVO              | [ee4e4a7bc7](https://linux-hardware.org/?probe=ee4e4a7bc7) | May 17, 2022 |
| Dell          | 040DDP A00                  | [4806ca2a7e](https://linux-hardware.org/?probe=4806ca2a7e) | May 17, 2022 |
| Gigabyte      | H310M S2H x.x               | [4d76b03e66](https://linux-hardware.org/?probe=4d76b03e66) | May 17, 2022 |
| ASUSTek       | Z87-K                       | [2daea316b2](https://linux-hardware.org/?probe=2daea316b2) | May 16, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [91d8b47a30](https://linux-hardware.org/?probe=91d8b47a30) | May 15, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | [608664ce7a](https://linux-hardware.org/?probe=608664ce7a) | May 15, 2022 |
| Dell          | 0CRH6C A02                  | [655afd62e6](https://linux-hardware.org/?probe=655afd62e6) | May 14, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [a049c51989](https://linux-hardware.org/?probe=a049c51989) | May 14, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [cb7b6b9cde](https://linux-hardware.org/?probe=cb7b6b9cde) | May 14, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING ... | [0cc824e2a5](https://linux-hardware.org/?probe=0cc824e2a5) | May 13, 2022 |
| NZXT          | N7 B550                     | [73441bbfc4](https://linux-hardware.org/?probe=73441bbfc4) | May 12, 2022 |
| Unknown       | BTC79X5                     | [42b222eb65](https://linux-hardware.org/?probe=42b222eb65) | May 12, 2022 |
| Gigabyte      | Z170-Gaming K3              | [768acb5df2](https://linux-hardware.org/?probe=768acb5df2) | May 12, 2022 |
| AZW           | BT3 X                       | [a17cb64acb](https://linux-hardware.org/?probe=a17cb64acb) | May 12, 2022 |
| Lenovo        | 0B98401 PRO                 | [ee225906fc](https://linux-hardware.org/?probe=ee225906fc) | May 12, 2022 |
| Lenovo        | 0B98401 PRO                 | [16911d5e64](https://linux-hardware.org/?probe=16911d5e64) | May 11, 2022 |
| Gigabyte      | B660 AORUS MASTER DDR4      | [e5981a9f20](https://linux-hardware.org/?probe=e5981a9f20) | May 11, 2022 |
| Gigabyte      | Z390 AORUS PRO-CF           | [1d4364ac51](https://linux-hardware.org/?probe=1d4364ac51) | May 10, 2022 |
| NZXT          | N7 B550                     | [147247dfb6](https://linux-hardware.org/?probe=147247dfb6) | May 10, 2022 |
| Gigabyte      | Z170-HD3P-CF                | [396a39e5a6](https://linux-hardware.org/?probe=396a39e5a6) | May 10, 2022 |
| ASRock        | X370 Professional Gaming    | [1e22ba0468](https://linux-hardware.org/?probe=1e22ba0468) | May 10, 2022 |
| ASUSTek       | PRIME B450M-A               | [0b3cda16db](https://linux-hardware.org/?probe=0b3cda16db) | May 10, 2022 |
| ASUSTek       | PRIME B450M-A               | [90190717eb](https://linux-hardware.org/?probe=90190717eb) | May 09, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [9f6a18226f](https://linux-hardware.org/?probe=9f6a18226f) | May 09, 2022 |
| ASUSTek       | Z97-AR                      | [29c93ea162](https://linux-hardware.org/?probe=29c93ea162) | May 09, 2022 |
| Gigabyte      | B450 AORUS M                | [cd1aff125e](https://linux-hardware.org/?probe=cd1aff125e) | May 09, 2022 |
| SIEMENS       | A5E02122237 ES010           | [cc728f6c38](https://linux-hardware.org/?probe=cc728f6c38) | May 09, 2022 |
| ASRock        | X299 Taichi CLX             | [47a45fca48](https://linux-hardware.org/?probe=47a45fca48) | May 08, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [8964a4c5ec](https://linux-hardware.org/?probe=8964a4c5ec) | May 08, 2022 |
| ECS           | Nettle3                     | [36f8cde007](https://linux-hardware.org/?probe=36f8cde007) | May 08, 2022 |
| ASUSTek       | PRIME X570-P                | [65d94c8458](https://linux-hardware.org/?probe=65d94c8458) | May 08, 2022 |
| ECS           | Nettle3                     | [646fb53a2c](https://linux-hardware.org/?probe=646fb53a2c) | May 07, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [61a4daec98](https://linux-hardware.org/?probe=61a4daec98) | May 07, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [180dd73bd6](https://linux-hardware.org/?probe=180dd73bd6) | May 07, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [f71ca35596](https://linux-hardware.org/?probe=f71ca35596) | May 06, 2022 |
| MSI           | B450-A PRO                  | [5b5ceb0f53](https://linux-hardware.org/?probe=5b5ceb0f53) | May 06, 2022 |
| Gigabyte      | 990FXA-UD3                  | [4fe934e84d](https://linux-hardware.org/?probe=4fe934e84d) | May 06, 2022 |
| ASRock        | 970M Pro3                   | [2853128cd0](https://linux-hardware.org/?probe=2853128cd0) | May 05, 2022 |
| ASRock        | 970M Pro3                   | [5f51fd4cf8](https://linux-hardware.org/?probe=5f51fd4cf8) | May 05, 2022 |
| Gigabyte      | Z170-HD3P-CF                | [7b7f29e504](https://linux-hardware.org/?probe=7b7f29e504) | May 05, 2022 |
| ASRock        | X470 Taichi                 | [e133868179](https://linux-hardware.org/?probe=e133868179) | May 05, 2022 |
| ASRock        | X470 Taichi                 | [93d6fb1610](https://linux-hardware.org/?probe=93d6fb1610) | May 05, 2022 |
| ASRock        | A320M-HDV R4.0              | [36cabd86ba](https://linux-hardware.org/?probe=36cabd86ba) | May 04, 2022 |
| ASUSTek       | B85M-E                      | [2b6338d755](https://linux-hardware.org/?probe=2b6338d755) | May 04, 2022 |
| Gigabyte      | Z170-HD3P-CF                | [7196bf2ec6](https://linux-hardware.org/?probe=7196bf2ec6) | May 03, 2022 |
| ASRock        | 970M Pro3                   | [f20f31b107](https://linux-hardware.org/?probe=f20f31b107) | May 03, 2022 |
| ASRock        | 970M Pro3                   | [73a563257a](https://linux-hardware.org/?probe=73a563257a) | May 03, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [65a2309744](https://linux-hardware.org/?probe=65a2309744) | May 03, 2022 |
| Alienware     | 0CPDXD A00                  | [17da14a17d](https://linux-hardware.org/?probe=17da14a17d) | May 03, 2022 |
| ASUSTek       | B85M-E                      | [9645231d87](https://linux-hardware.org/?probe=9645231d87) | May 03, 2022 |
| MSI           | B450I GAMING PLUS AC        | [c0ef0738b5](https://linux-hardware.org/?probe=c0ef0738b5) | May 02, 2022 |
| MSI           | X370 GAMING PRO CARBON      | [4a09f5d3f3](https://linux-hardware.org/?probe=4a09f5d3f3) | May 02, 2022 |
| MSI           | X370 GAMING PRO CARBON      | [ab716981c3](https://linux-hardware.org/?probe=ab716981c3) | May 02, 2022 |
| Alienware     | 0P0JWX A00                  | [e6e1548aa1](https://linux-hardware.org/?probe=e6e1548aa1) | May 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | [a456619489](https://linux-hardware.org/?probe=a456619489) | May 02, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [925447d7e9](https://linux-hardware.org/?probe=925447d7e9) | May 01, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [b1e331055f](https://linux-hardware.org/?probe=b1e331055f) | May 01, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [dec71580c4](https://linux-hardware.org/?probe=dec71580c4) | May 01, 2022 |
| Gigabyte      | X570S AERO G                | [ab6b8eaa71](https://linux-hardware.org/?probe=ab6b8eaa71) | May 01, 2022 |
| MSI           | 970 GAMING                  | [32052450db](https://linux-hardware.org/?probe=32052450db) | May 01, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [8db041a1e4](https://linux-hardware.org/?probe=8db041a1e4) | May 01, 2022 |
| ASRock        | B450 Steel Legend           | [ecc527cb4b](https://linux-hardware.org/?probe=ecc527cb4b) | May 01, 2022 |
| ASRock        | B450 Steel Legend           | [ca217fe968](https://linux-hardware.org/?probe=ca217fe968) | May 01, 2022 |
| MSI           | B450M GAMING PLUS           | [0929d58de7](https://linux-hardware.org/?probe=0929d58de7) | Apr 30, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [3edd5f05f7](https://linux-hardware.org/?probe=3edd5f05f7) | Apr 30, 2022 |
| ASRock        | X99 Extreme4                | [d45e1e88db](https://linux-hardware.org/?probe=d45e1e88db) | Apr 30, 2022 |
| ASRock        | X99 Extreme4                | [41cec63ac6](https://linux-hardware.org/?probe=41cec63ac6) | Apr 30, 2022 |
| EVGA          | X58 SLI Classified Tyler... | [07254f2dbb](https://linux-hardware.org/?probe=07254f2dbb) | Apr 30, 2022 |
| ASUSTek       | PRIME H510M-E               | [5c9e5fc14c](https://linux-hardware.org/?probe=5c9e5fc14c) | Apr 29, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING ... | [bce425f138](https://linux-hardware.org/?probe=bce425f138) | Apr 29, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [7b292b972d](https://linux-hardware.org/?probe=7b292b972d) | Apr 29, 2022 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [e37bc471b1](https://linux-hardware.org/?probe=e37bc471b1) | Apr 29, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [2b7167b16e](https://linux-hardware.org/?probe=2b7167b16e) | Apr 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [aed5ee3ded](https://linux-hardware.org/?probe=aed5ee3ded) | Apr 28, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [ab83eedd1f](https://linux-hardware.org/?probe=ab83eedd1f) | Apr 28, 2022 |
| MSI           | H55M-E23                    | [4ab5f58470](https://linux-hardware.org/?probe=4ab5f58470) | Apr 28, 2022 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [46430e1117](https://linux-hardware.org/?probe=46430e1117) | Apr 28, 2022 |
| Dell          | 09KPNV A00                  | [5046e0575b](https://linux-hardware.org/?probe=5046e0575b) | Apr 28, 2022 |
| Dell          | 0NW73C A00                  | [344e2b816e](https://linux-hardware.org/?probe=344e2b816e) | Apr 28, 2022 |
| Dell          | 088DT1 A01                  | [b664b8720e](https://linux-hardware.org/?probe=b664b8720e) | Apr 28, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [19e0445e6f](https://linux-hardware.org/?probe=19e0445e6f) | Apr 27, 2022 |
| Dell          | 0R1PCR A00                  | [feec38a0f5](https://linux-hardware.org/?probe=feec38a0f5) | Apr 27, 2022 |
| Unknown       | Unknown                     | [82ad7e86b5](https://linux-hardware.org/?probe=82ad7e86b5) | Apr 27, 2022 |
| ASUSTek       | GA15DH                      | [30a22d7be3](https://linux-hardware.org/?probe=30a22d7be3) | Apr 27, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [4b9faf4848](https://linux-hardware.org/?probe=4b9faf4848) | Apr 26, 2022 |
| System76      | Thelio thelio-r2            | [aae937be8b](https://linux-hardware.org/?probe=aae937be8b) | Apr 25, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [fabaa5b3ab](https://linux-hardware.org/?probe=fabaa5b3ab) | Apr 24, 2022 |
| MSI           | B250M BAZOOKA               | [91392a601e](https://linux-hardware.org/?probe=91392a601e) | Apr 08, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.17.5-76051705-generic  | 152      | 73.79%  |
| 5.16.19-76051619-generic | 40       | 19.42%  |
| 5.17.15-76051715-generic | 12       | 5.83%   |
| 5.17.4-051704-generic    | 1        | 0.49%   |
| 5.16.15-76051615-generic | 1        | 0.49%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.17.5  | 152      | 73.79%  |
| 5.16.19 | 40       | 19.42%  |
| 5.17.15 | 12       | 5.83%   |
| 5.17.4  | 1        | 0.49%   |
| 5.16.15 | 1        | 0.49%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.17    | 162      | 79.8%   |
| 5.16    | 41       | 20.2%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 200      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 195      | 97.5%   |
| KDE5       | 3        | 1.5%    |
| X-Cinnamon | 1        | 0.5%    |
| LXQt       | 1        | 0.5%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 197      | 98.5%   |
| Wayland | 2        | 1%      |
| Tty     | 1        | 0.5%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 171      | 85.5%   |
| GDM3    | 28       | 14%     |
| SDDM    | 1        | 0.5%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 122      | 60.7%   |
| en_GB | 11       | 5.47%   |
| C     | 11       | 5.47%   |
| en_CA | 9        | 4.48%   |
| pt_BR | 8        | 3.98%   |
| de_DE | 8        | 3.98%   |
| en_AU | 7        | 3.48%   |
| pl_PL | 5        | 2.49%   |
| fr_FR | 4        | 1.99%   |
| es_ES | 3        | 1.49%   |
| sv_SE | 2        | 1%      |
| es_CL | 2        | 1%      |
| ru_RU | 1        | 0.5%    |
| nl_NL | 1        | 0.5%    |
| nl_BE | 1        | 0.5%    |
| ja_JP | 1        | 0.5%    |
| fi_FI | 1        | 0.5%    |
| en_IL | 1        | 0.5%    |
| en_IE | 1        | 0.5%    |
| de_AT | 1        | 0.5%    |
| cs_CZ | 1        | 0.5%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 173      | 86.5%   |
| EFI  | 27       | 13.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 186      | 93%     |
| Btrfs   | 8        | 4%      |
| Overlay | 5        | 2.5%    |
| Xfs     | 1        | 0.5%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 171      | 85.5%   |
| GPT     | 29       | 14.5%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 195      | 97.5%   |
| Yes       | 5        | 2.5%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 177      | 88.5%   |
| Yes       | 23       | 11.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 63       | 31.5%   |
| Gigabyte Technology | 40       | 20%     |
| MSI                 | 29       | 14.5%   |
| Dell                | 16       | 8%      |
| ASRock              | 15       | 7.5%    |
| Hewlett-Packard     | 8        | 4%      |
| Lenovo              | 5        | 2.5%    |
| System76            | 3        | 1.5%    |
| Alienware           | 3        | 1.5%    |
| Unknown             | 3        | 1.5%    |
| Foxconn             | 2        | 1%      |
| Supermicro          | 1        | 0.5%    |
| SIEMENS             | 1        | 0.5%    |
| Positivo            | 1        | 0.5%    |
| NZXT                | 1        | 0.5%    |
| Medion              | 1        | 0.5%    |
| Intel               | 1        | 0.5%    |
| Fujitsu             | 1        | 0.5%    |
| EVGA                | 1        | 0.5%    |
| ECS                 | 1        | 0.5%    |
| Biostar             | 1        | 0.5%    |
| BESSTAR Tech        | 1        | 0.5%    |
| AZW                 | 1        | 0.5%    |
| Apple               | 1        | 0.5%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                               | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| ASUS All Series                                    | 5        | 2.5%    |
| Gigabyte X570 AORUS ELITE                          | 4        | 2%      |
| Gigabyte B450 AORUS M                              | 3        | 1.5%    |
| Dell OptiPlex 3020                                 | 3        | 1.5%    |
| ASUS ROG CROSSHAIR VIII DARK HERO                  | 3        | 1.5%    |
| Unknown                                            | 3        | 1.5%    |
| System76 Thelio                                    | 2        | 1%      |
| MSI MS-7D32                                        | 2        | 1%      |
| MSI MS-7C37                                        | 2        | 1%      |
| HP ProDesk 600 G1 SFF                              | 2        | 1%      |
| Gigabyte Z170-HD3P                                 | 2        | 1%      |
| Gigabyte Z170-Gaming K3                            | 2        | 1%      |
| ASUS ROG STRIX B450-I GAMING                       | 2        | 1%      |
| ASUS ROG CROSSHAIR VIII HERO                       | 2        | 1%      |
| ASUS PRIME B450M-A                                 | 2        | 1%      |
| ASUS P6X58D PREMIUM                                | 2        | 1%      |
| ASRock B450 Gaming K4                              | 2        | 1%      |
| System76 Thelio Major                              | 1        | 0.5%    |
| Supermicro X8SIL                                   | 1        | 0.5%    |
| SIEMENS SIMATIC BOX PC 627B/PANEL PC 677B Profibus | 1        | 0.5%    |
| Positivo POS-MI945AA                               | 1        | 0.5%    |
| NZXT N7 B550                                       | 1        | 0.5%    |
| MSI MS-7D54                                        | 1        | 0.5%    |
| MSI MS-7C96                                        | 1        | 0.5%    |
| MSI MS-7C91                                        | 1        | 0.5%    |
| MSI MS-7C75                                        | 1        | 0.5%    |
| MSI MS-7C56                                        | 1        | 0.5%    |
| MSI MS-7C35                                        | 1        | 0.5%    |
| MSI MS-7C02                                        | 1        | 0.5%    |
| MSI MS-7B87                                        | 1        | 0.5%    |
| MSI MS-7B86                                        | 1        | 0.5%    |
| MSI MS-7B17                                        | 1        | 0.5%    |
| MSI MS-7B12                                        | 1        | 0.5%    |
| MSI MS-7A74                                        | 1        | 0.5%    |
| MSI MS-7A71                                        | 1        | 0.5%    |
| MSI MS-7A70                                        | 1        | 0.5%    |
| MSI MS-7A40                                        | 1        | 0.5%    |
| MSI MS-7A38                                        | 1        | 0.5%    |
| MSI MS-7A37                                        | 1        | 0.5%    |
| MSI MS-7A34                                        | 1        | 0.5%    |
| MSI MS-7A32                                        | 1        | 0.5%    |
| MSI MS-7A16                                        | 1        | 0.5%    |
| MSI MS-7918                                        | 1        | 0.5%    |
| MSI MS-7693                                        | 1        | 0.5%    |
| MSI MS-7636                                        | 1        | 0.5%    |
| MSI MPG B460 Trident A (MS-B926)                   | 1        | 0.5%    |
| MSI A55PV.AR3510D                                  | 1        | 0.5%    |
| Medion MS-7728                                     | 1        | 0.5%    |
| Lenovo ZHENGJIUZHE REN9000K-34IMZ 90Q90022CP       | 1        | 0.5%    |
| Lenovo ThinkStation S30 43516Y7                    | 1        | 0.5%    |
| Lenovo ThinkCentre M93p 10A6S0RN00                 | 1        | 0.5%    |
| Lenovo ThinkCentre M82 2929AZ6                     | 1        | 0.5%    |
| Lenovo IdeaCentre 510-15IKL 90G8008EAL             | 1        | 0.5%    |
| Intel MAHOBAY                                      | 1        | 0.5%    |
| HP Z820 Workstation                                | 1        | 0.5%    |
| HP Z230 Tower Workstation                          | 1        | 0.5%    |
| HP OMEN 30L Desktop GT13-0xxx                      | 1        | 0.5%    |
| HP EliteDesk 800 G2 SFF                            | 1        | 0.5%    |
| HP EliteDesk 705 G3 Desktop Mini                   | 1        | 0.5%    |
| HP Compaq 8000 Elite CMT PC                        | 1        | 0.5%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| ASUS ROG              | 20       | 10%     |
| ASUS PRIME            | 13       | 6.5%    |
| Gigabyte X570         | 7        | 3.5%    |
| Dell OptiPlex         | 6        | 3%      |
| Dell Precision        | 5        | 2.5%    |
| ASUS All              | 5        | 2.5%    |
| ASUS TUF              | 4        | 2%      |
| System76 Thelio       | 3        | 1.5%    |
| Gigabyte B450         | 3        | 1.5%    |
| Dell Inspiron         | 3        | 1.5%    |
| ASRock B450           | 3        | 1.5%    |
| Alienware Aurora      | 3        | 1.5%    |
| Unknown               | 3        | 1.5%    |
| MSI MS-7D32           | 2        | 1%      |
| MSI MS-7C37           | 2        | 1%      |
| Lenovo ThinkCentre    | 2        | 1%      |
| HP ProDesk            | 2        | 1%      |
| HP EliteDesk          | 2        | 1%      |
| Gigabyte Z390         | 2        | 1%      |
| Gigabyte Z170-HD3P    | 2        | 1%      |
| Gigabyte Z170-Gaming  | 2        | 1%      |
| Gigabyte X470         | 2        | 1%      |
| Gigabyte B550         | 2        | 1%      |
| Gigabyte AB350-Gaming | 2        | 1%      |
| Dell XPS              | 2        | 1%      |
| ASUS P6X58D           | 2        | 1%      |
| ASRock Z390           | 2        | 1%      |
| Supermicro X8SIL      | 1        | 0.5%    |
| SIEMENS SIMATIC       | 1        | 0.5%    |
| Positivo POS-MI945AA  | 1        | 0.5%    |
| NZXT N7               | 1        | 0.5%    |
| MSI MS-7D54           | 1        | 0.5%    |
| MSI MS-7C96           | 1        | 0.5%    |
| MSI MS-7C91           | 1        | 0.5%    |
| MSI MS-7C75           | 1        | 0.5%    |
| MSI MS-7C56           | 1        | 0.5%    |
| MSI MS-7C35           | 1        | 0.5%    |
| MSI MS-7C02           | 1        | 0.5%    |
| MSI MS-7B87           | 1        | 0.5%    |
| MSI MS-7B86           | 1        | 0.5%    |
| MSI MS-7B17           | 1        | 0.5%    |
| MSI MS-7B12           | 1        | 0.5%    |
| MSI MS-7A74           | 1        | 0.5%    |
| MSI MS-7A71           | 1        | 0.5%    |
| MSI MS-7A70           | 1        | 0.5%    |
| MSI MS-7A40           | 1        | 0.5%    |
| MSI MS-7A38           | 1        | 0.5%    |
| MSI MS-7A37           | 1        | 0.5%    |
| MSI MS-7A34           | 1        | 0.5%    |
| MSI MS-7A32           | 1        | 0.5%    |
| MSI MS-7A16           | 1        | 0.5%    |
| MSI MS-7918           | 1        | 0.5%    |
| MSI MS-7693           | 1        | 0.5%    |
| MSI MS-7636           | 1        | 0.5%    |
| MSI MPG               | 1        | 0.5%    |
| MSI A55PV.AR3510D     | 1        | 0.5%    |
| Medion MS-7728        | 1        | 0.5%    |
| Lenovo ZHENGJIUZHE    | 1        | 0.5%    |
| Lenovo ThinkStation   | 1        | 0.5%    |
| Lenovo IdeaCentre     | 1        | 0.5%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 33       | 16.5%   |
| 2019 | 28       | 14%     |
| 2021 | 23       | 11.5%   |
| 2020 | 19       | 9.5%    |
| 2017 | 13       | 6.5%    |
| 2016 | 12       | 6%      |
| 2013 | 12       | 6%      |
| 2011 | 12       | 6%      |
| 2014 | 11       | 5.5%    |
| 2012 | 8        | 4%      |
| 2010 | 7        | 3.5%    |
| 2015 | 6        | 3%      |
| 2009 | 6        | 3%      |
| 2022 | 5        | 2.5%    |
| 2008 | 3        | 1.5%    |
| 2007 | 1        | 0.5%    |
| 2006 | 1        | 0.5%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 200      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 200      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 200      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 32.01-64.0      | 64       | 31.68%  |
| 16.01-24.0      | 60       | 29.7%   |
| 8.01-16.0       | 30       | 14.85%  |
| 64.01-256.0     | 15       | 7.43%   |
| 4.01-8.0        | 14       | 6.93%   |
| 3.01-4.0        | 13       | 6.44%   |
| 24.01-32.0      | 3        | 1.49%   |
| More than 256.0 | 2        | 0.99%   |
| 1.01-2.0        | 1        | 0.5%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 66       | 31.43%  |
| 4.01-8.0   | 61       | 29.05%  |
| 3.01-4.0   | 44       | 20.95%  |
| 1.01-2.0   | 26       | 12.38%  |
| 8.01-16.0  | 10       | 4.76%   |
| 16.01-24.0 | 3        | 1.43%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 75       | 37.31%  |
| 1      | 47       | 23.38%  |
| 3      | 45       | 22.39%  |
| 4      | 13       | 6.47%   |
| 5      | 9        | 4.48%   |
| 6      | 7        | 3.48%   |
| 7      | 2        | 1%      |
| 11     | 1        | 0.5%    |
| 10     | 1        | 0.5%    |
| 9      | 1        | 0.5%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 135      | 67.5%   |
| Yes       | 65       | 32.5%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 196      | 98%     |
| No        | 4        | 2%      |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 120      | 60%     |
| No        | 80       | 40%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 112      | 56%     |
| Yes       | 88       | 44%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 85       | 42.29%  |
| Germany      | 9        | 4.48%   |
| Canada       | 9        | 4.48%   |
| Australia    | 9        | 4.48%   |
| UK           | 8        | 3.98%   |
| Netherlands  | 8        | 3.98%   |
| Brazil       | 8        | 3.98%   |
| France       | 6        | 2.99%   |
| Switzerland  | 4        | 1.99%   |
| Poland       | 4        | 1.99%   |
| Sweden       | 3        | 1.49%   |
| Spain        | 3        | 1.49%   |
| Norway       | 3        | 1.49%   |
| Japan        | 3        | 1.49%   |
| Ireland      | 3        | 1.49%   |
| Austria      | 3        | 1.49%   |
| Thailand     | 2        | 1%      |
| South Africa | 2        | 1%      |
| Russia       | 2        | 1%      |
| Mexico       | 2        | 1%      |
| Italy        | 2        | 1%      |
| Greece       | 2        | 1%      |
| Finland      | 2        | 1%      |
| Czechia      | 2        | 1%      |
| Chile        | 2        | 1%      |
| Turkey       | 1        | 0.5%    |
| Tunisia      | 1        | 0.5%    |
| South Korea  | 1        | 0.5%    |
| Slovakia     | 1        | 0.5%    |
| Saudi Arabia | 1        | 0.5%    |
| Philippines  | 1        | 0.5%    |
| Nicaragua    | 1        | 0.5%    |
| Lithuania    | 1        | 0.5%    |
| Jordan       | 1        | 0.5%    |
| Israel       | 1        | 0.5%    |
| Hungary      | 1        | 0.5%    |
| Hong Kong    | 1        | 0.5%    |
| Belgium      | 1        | 0.5%    |
| Azerbaijan   | 1        | 0.5%    |
| Argentina    | 1        | 0.5%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Vienna            | 3        | 1.49%   |
| Zurich            | 2        | 1%      |
| Sydney            | 2        | 1%      |
| Seattle           | 2        | 1%      |
| Sapporo           | 2        | 1%      |
| San Francisco     | 2        | 1%      |
| Richmond          | 2        | 1%      |
| Ogden             | 2        | 1%      |
| Mannheim          | 2        | 1%      |
| Cleveland         | 2        | 1%      |
| Brisbane          | 2        | 1%      |
| Berlin            | 2        | 1%      |
| Bedford           | 2        | 1%      |
| Atlanta           | 2        | 1%      |
| Żyrardów        | 1        | 0.5%    |
| Zaragoza          | 1        | 0.5%    |
| Zapopan           | 1        | 0.5%    |
| Yekaterinburg     | 1        | 0.5%    |
| Woodstock         | 1        | 0.5%    |
| Winter Garden     | 1        | 0.5%    |
| Wichita           | 1        | 0.5%    |
| Weston-super-Mare | 1        | 0.5%    |
| Westland          | 1        | 0.5%    |
| Weimar            | 1        | 0.5%    |
| Wausau            | 1        | 0.5%    |
| Walker            | 1        | 0.5%    |
| Virginia Beach    | 1        | 0.5%    |
| Vilnius           | 1        | 0.5%    |
| Vicksburg         | 1        | 0.5%    |
| Ventura           | 1        | 0.5%    |
| Valparaiso        | 1        | 0.5%    |
| Union             | 1        | 0.5%    |
| Turku             | 1        | 0.5%    |
| Tunis             | 1        | 0.5%    |
| Tuen Mun          | 1        | 0.5%    |
| Tucson            | 1        | 0.5%    |
| Tuam              | 1        | 0.5%    |
| Trondheim         | 1        | 0.5%    |
| Toronto           | 1        | 0.5%    |
| Thessaloniki      | 1        | 0.5%    |
| Theilingen        | 1        | 0.5%    |
| Taunton           | 1        | 0.5%    |
| Tarlac City       | 1        | 0.5%    |
| Tahlequah         | 1        | 0.5%    |
| Swannanoa         | 1        | 0.5%    |
| Sunnyside         | 1        | 0.5%    |
| Sumter            | 1        | 0.5%    |
| Stuttgart         | 1        | 0.5%    |
| Strzegom          | 1        | 0.5%    |
| Stevensville      | 1        | 0.5%    |
| Springfield       | 1        | 0.5%    |
| Solleftea         | 1        | 0.5%    |
| Sokolov           | 1        | 0.5%    |
| Sidrolandia       | 1        | 0.5%    |
| Saskatoon         | 1        | 0.5%    |
| Sarcelles         | 1        | 0.5%    |
| Sao Paulo         | 1        | 0.5%    |
| Santiago          | 1        | 0.5%    |
| Sanger            | 1        | 0.5%    |
| San Jose          | 1        | 0.5%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 83       | 112    | 20.19%  |
| Samsung Electronics       | 78       | 115    | 18.98%  |
| WDC                       | 57       | 83     | 13.87%  |
| SanDisk                   | 24       | 31     | 5.84%   |
| Crucial                   | 24       | 34     | 5.84%   |
| Toshiba                   | 21       | 24     | 5.11%   |
| Kingston                  | 19       | 26     | 4.62%   |
| Hitachi                   | 15       | 20     | 3.65%   |
| Phison                    | 13       | 18     | 3.16%   |
| Intel                     | 8        | 9      | 1.95%   |
| A-DATA Technology         | 7        | 8      | 1.7%    |
| Micron Technology         | 6        | 7      | 1.46%   |
| SK hynix                  | 5        | 5      | 1.22%   |
| Silicon Motion            | 5        | 7      | 1.22%   |
| Micron/Crucial Technology | 4        | 6      | 0.97%   |
| China                     | 4        | 5      | 0.97%   |
| SPCC                      | 3        | 5      | 0.73%   |
| Unknown                   | 2        | 2      | 0.49%   |
| PNY                       | 2        | 2      | 0.49%   |
| Patriot                   | 2        | 2      | 0.49%   |
| Lexar                     | 2        | 2      | 0.49%   |
| Intenso                   | 2        | 2      | 0.49%   |
| HGST                      | 2        | 2      | 0.49%   |
| Hewlett-Packard           | 2        | 2      | 0.49%   |
| Fujitsu                   | 2        | 3      | 0.49%   |
| Corsair                   | 2        | 3      | 0.49%   |
| TurXun                    | 1        | 1      | 0.24%   |
| Transcend                 | 1        | 2      | 0.24%   |
| TO Exter                  | 1        | 1      | 0.24%   |
| T-FORCE                   | 1        | 1      | 0.24%   |
| Qunion                    | 1        | 1      | 0.24%   |
| PNY USB                   | 1        | 1      | 0.24%   |
| OCZ                       | 1        | 1      | 0.24%   |
| Mushkin                   | 1        | 2      | 0.24%   |
| Maxtor                    | 1        | 1      | 0.24%   |
| MaxDigital                | 1        | 1      | 0.24%   |
| Mass                      | 1        | 1      | 0.24%   |
| LITEON                    | 1        | 1      | 0.24%   |
| KingFast                  | 1        | 1      | 0.24%   |
| HS-SSD-C100               | 1        | 2      | 0.24%   |
| Gigabyte Technology       | 1        | 1      | 0.24%   |
| FORESEE                   | 1        | 2      | 0.24%   |
| ASMT                      | 1        | 1      | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Samsung SM963 2.5" NVMe PCIe SSD 500GB | 14       | 2.85%   |
| Seagate ST2000DM008-2FR102 2TB         | 13       | 2.64%   |
| Samsung NVMe SSD Drive 1TB             | 12       | 2.44%   |
| Samsung SSD 850 EVO 250GB              | 7        | 1.42%   |
| Seagate ST500DM002-1BD142 500GB        | 6        | 1.22%   |
| SanDisk NVMe SSD Drive 1TB             | 6        | 1.22%   |
| Phison NVMe SSD Drive 1TB              | 6        | 1.22%   |
| Kingston SA400S37240G 240GB SSD        | 6        | 1.22%   |
| Crucial CT1000MX500SSD1 1TB            | 6        | 1.22%   |
| WDC WD10EZEX-08WN4A0 1TB               | 5        | 1.02%   |
| Seagate ST4000DM004-2CV104 4TB         | 5        | 1.02%   |
| Seagate ST1000DM010-2EP102 1TB         | 5        | 1.02%   |
| Seagate ST1000DM003-1CH162 1TB         | 5        | 1.02%   |
| Samsung SSD 970 EVO Plus 1TB           | 5        | 1.02%   |
| Samsung NVMe SSD Drive 2TB             | 5        | 1.02%   |
| WDC WD30EFRX-68EUZN0 3TB               | 4        | 0.81%   |
| Toshiba DT01ACA200 2TB                 | 4        | 0.81%   |
| Seagate Expansion 1TB                  | 4        | 0.81%   |
| Samsung SSD 860 EVO 500GB              | 4        | 0.81%   |
| Samsung SSD 860 EVO 1TB                | 4        | 0.81%   |
| Phison NVMe SSD Drive 2TB              | 4        | 0.81%   |
| Crucial CT2000MX500SSD1 2TB            | 4        | 0.81%   |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 3        | 0.61%   |
| Toshiba HDWD120 2TB                    | 3        | 0.61%   |
| Toshiba DT01ACA100 1TB                 | 3        | 0.61%   |
| Seagate ST500LM012 HN-M500MBB 500GB    | 3        | 0.61%   |
| Seagate ST4000DM000-1F2168 4TB         | 3        | 0.61%   |
| Seagate ST31000528AS 1TB               | 3        | 0.61%   |
| Seagate ST2000DM001-1ER164 2TB         | 3        | 0.61%   |
| SanDisk NVMe SSD Drive 512GB           | 3        | 0.61%   |
| SanDisk NVMe SSD Drive 500GB           | 3        | 0.61%   |
| Samsung SSD 850 EVO 500GB              | 3        | 0.61%   |
| Micron/Crucial NVMe SSD Drive 1TB      | 3        | 0.61%   |
| WDC WDS100T3X0C-00SJG0 1TB             | 2        | 0.41%   |
| WDC WD20EZRX-00D8PB0 2TB               | 2        | 0.41%   |
| WDC WD10EZEX-08M2NA0 1TB               | 2        | 0.41%   |
| WDC WD10EZEX-00RKKA0 1TB               | 2        | 0.41%   |
| WDC WD10EZEX-00BN5A0 1TB               | 2        | 0.41%   |
| SPCC Solid State Disk 512GB            | 2        | 0.41%   |
| Silicon Motion NVMe SSD Drive 1TB      | 2        | 0.41%   |
| Silicon Motion NVMe SSD Drive 128GB    | 2        | 0.41%   |
| Seagate ST5000LM000-2AN170 5TB         | 2        | 0.41%   |
| Seagate ST3500418AS 500GB              | 2        | 0.41%   |
| Seagate ST3320620AS 320GB              | 2        | 0.41%   |
| Seagate ST31000524AS 1TB               | 2        | 0.41%   |
| Seagate ST2000DX002-2DV164 2TB         | 2        | 0.41%   |
| Seagate ST2000DM006-2DM164 2TB         | 2        | 0.41%   |
| Seagate ST2000DM001-1CH164 2TB         | 2        | 0.41%   |
| Seagate ST1000DM003-1SB102 1TB         | 2        | 0.41%   |
| Seagate ST1000DM003-1ER162 1TB         | 2        | 0.41%   |
| Seagate NVMe SSD Drive 1TB             | 2        | 0.41%   |
| SanDisk SDSSDH32000G 2TB               | 2        | 0.41%   |
| SanDisk NVMe SSD Drive 2TB             | 2        | 0.41%   |
| Samsung SSD 980 PRO 1TB                | 2        | 0.41%   |
| Samsung SSD 980 1TB                    | 2        | 0.41%   |
| Samsung SSD 970 EVO 500GB              | 2        | 0.41%   |
| Samsung SSD 870 EVO 500GB              | 2        | 0.41%   |
| Samsung SSD 860 EVO 250GB              | 2        | 0.41%   |
| Samsung SSD 850 EVO 1TB                | 2        | 0.41%   |
| Samsung SSD 840 PRO Series 256GB       | 2        | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 79       | 105    | 45.4%   |
| WDC                 | 48       | 66     | 27.59%  |
| Toshiba             | 20       | 23     | 11.49%  |
| Hitachi             | 15       | 20     | 8.62%   |
| Samsung Electronics | 6        | 9      | 3.45%   |
| HGST                | 2        | 2      | 1.15%   |
| Unknown             | 1        | 1      | 0.57%   |
| Maxtor              | 1        | 1      | 0.57%   |
| Fujitsu             | 1        | 2      | 0.57%   |
| ASMT                | 1        | 1      | 0.57%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 34       | 50     | 26.36%  |
| Crucial             | 21       | 31     | 16.28%  |
| Kingston            | 17       | 22     | 13.18%  |
| WDC                 | 9        | 13     | 6.98%   |
| SanDisk             | 9        | 12     | 6.98%   |
| A-DATA Technology   | 5        | 6      | 3.88%   |
| Intel               | 4        | 4      | 3.1%    |
| China               | 4        | 5      | 3.1%    |
| SK hynix            | 3        | 3      | 2.33%   |
| SPCC                | 2        | 3      | 1.55%   |
| PNY                 | 2        | 2      | 1.55%   |
| Patriot             | 2        | 2      | 1.55%   |
| Micron Technology   | 2        | 2      | 1.55%   |
| Lexar               | 2        | 2      | 1.55%   |
| Hewlett-Packard     | 2        | 2      | 1.55%   |
| Transcend           | 1        | 2      | 0.78%   |
| Toshiba             | 1        | 1      | 0.78%   |
| TO Exter            | 1        | 1      | 0.78%   |
| Seagate             | 1        | 1      | 0.78%   |
| PNY USB             | 1        | 1      | 0.78%   |
| OCZ                 | 1        | 1      | 0.78%   |
| Mushkin             | 1        | 2      | 0.78%   |
| Gigabyte Technology | 1        | 1      | 0.78%   |
| Fujitsu             | 1        | 1      | 0.78%   |
| FORESEE             | 1        | 2      | 0.78%   |
| Corsair             | 1        | 2      | 0.78%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 132      | 230    | 38.82%  |
| SSD     | 107      | 174    | 31.47%  |
| NVMe    | 90       | 140    | 26.47%  |
| Unknown | 10       | 11     | 2.94%   |
| MMC     | 1        | 1      | 0.29%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 175      | 391    | 61.62%  |
| NVMe | 90       | 140    | 31.69%  |
| SAS  | 18       | 24     | 6.34%   |
| MMC  | 1        | 1      | 0.35%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 111      | 164    | 37.88%  |
| 0.51-1.0   | 85       | 123    | 29.01%  |
| 1.01-2.0   | 58       | 68     | 19.8%   |
| 3.01-4.0   | 18       | 22     | 6.14%   |
| 2.01-3.0   | 12       | 15     | 4.1%    |
| 4.01-10.0  | 9        | 12     | 3.07%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 41       | 20.1%   |
| 251-500        | 38       | 18.63%  |
| 1001-2000      | 32       | 15.69%  |
| More than 3000 | 31       | 15.2%   |
| 101-250        | 30       | 14.71%  |
| 2001-3000      | 13       | 6.37%   |
| 1-20           | 9        | 4.41%   |
| 51-100         | 5        | 2.45%   |
| 21-50          | 3        | 1.47%   |
| Unknown        | 2        | 0.98%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 49       | 23.79%  |
| 21-50          | 38       | 18.45%  |
| 101-250        | 24       | 11.65%  |
| 51-100         | 24       | 11.65%  |
| 251-500        | 21       | 10.19%  |
| 1001-2000      | 18       | 8.74%   |
| 501-1000       | 14       | 6.8%    |
| More than 3000 | 12       | 5.83%   |
| 2001-3000      | 4        | 1.94%   |
| Unknown        | 2        | 0.97%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WD10JPVX-60JC3T0 1TB              | 1        | 1      | 14.29%  |
| WDC WD1001FALS-00E8B0 1TB             | 1        | 1      | 14.29%  |
| Seagate ST5000LM000-2AN170 5TB        | 1        | 1      | 14.29%  |
| Seagate ST2000DM008-2FR102 2TB        | 1        | 1      | 14.29%  |
| Samsung Electronics SSD 850 PRO 256GB | 1        | 1      | 14.29%  |
| Kingston SV300S37A240G 240GB SSD      | 1        | 1      | 14.29%  |
| Hitachi HDP725050GLA360 500GB         | 1        | 1      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 2        | 2      | 28.57%  |
| Seagate             | 2        | 2      | 28.57%  |
| Samsung Electronics | 1        | 1      | 14.29%  |
| Kingston            | 1        | 1      | 14.29%  |
| Hitachi             | 1        | 1      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 2        | 2      | 40%     |
| Seagate | 2        | 2      | 40%     |
| Hitachi | 1        | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 5        | 5      | 71.43%  |
| SSD  | 2        | 2      | 28.57%  |

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
| Detected | 174      | 471    | 80.93%  |
| Works    | 34       | 78     | 15.81%  |
| Malfunc  | 7        | 7      | 3.26%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 111      | 33.53%  |
| AMD                         | 89       | 26.89%  |
| Samsung Electronics         | 48       | 14.5%   |
| SanDisk                     | 16       | 4.83%   |
| Phison Electronics          | 16       | 4.83%   |
| ASMedia Technology          | 11       | 3.32%   |
| Silicon Motion              | 6        | 1.81%   |
| Micron/Crucial Technology   | 6        | 1.81%   |
| Micron Technology           | 4        | 1.21%   |
| Marvell Technology Group    | 4        | 1.21%   |
| Seagate Technology          | 3        | 0.91%   |
| Kingston Technology Company | 3        | 0.91%   |
| JMicron Technology          | 3        | 0.91%   |
| SK hynix                    | 2        | 0.6%    |
| Nvidia                      | 2        | 0.6%    |
| VIA Technologies            | 1        | 0.3%    |
| Silicon Image               | 1        | 0.3%    |
| Realtek Semiconductor       | 1        | 0.3%    |
| LSI Logic / Symbios Logic   | 1        | 0.3%    |
| Lite-On Technology          | 1        | 0.3%    |
| Broadcom / LSI              | 1        | 0.3%    |
| ADATA Technology            | 1        | 0.3%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 63       | 15.56%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 32       | 7.9%    |
| AMD 400 Series Chipset SATA Controller                                                  | 24       | 5.93%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 13       | 3.21%   |
| AMD 500 Series Chipset SATA Controller                                                  | 12       | 2.96%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 11       | 2.72%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 10       | 2.47%   |
| Phison E12 NVMe Controller                                                              | 9        | 2.22%   |
| Intel SATA Controller [RAID mode]                                                       | 9        | 2.22%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 8        | 1.98%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8        | 1.98%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 7        | 1.73%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 6        | 1.48%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6        | 1.48%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 6        | 1.48%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 6        | 1.48%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 5        | 1.23%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 5        | 1.23%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 5        | 1.23%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5        | 1.23%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 5        | 1.23%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5        | 1.23%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5        | 1.23%   |
| AMD 300 Series Chipset SATA Controller                                                  | 5        | 1.23%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 4        | 0.99%   |
| Samsung NVMe SSD Controller 980                                                         | 4        | 0.99%   |
| Micron Non-Volatile memory controller                                                   | 4        | 0.99%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4        | 0.99%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 0.99%   |
| AMD X370 Series Chipset SATA Controller                                                 | 4        | 0.99%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 4        | 0.99%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 3        | 0.74%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 3        | 0.74%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 3        | 0.74%   |
| Intel SSD 660P Series                                                                   | 3        | 0.74%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 3        | 0.74%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 3        | 0.74%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3        | 0.74%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 3        | 0.74%   |
| Seagate FireCuda 530 SSD                                                                | 2        | 0.49%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 2        | 0.49%   |
| SanDisk Non-Volatile memory controller                                                  | 2        | 0.49%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2        | 0.49%   |
| Phison PS5013 E13 NVMe Controller                                                       | 2        | 0.49%   |
| Nvidia MCP61 SATA Controller                                                            | 2        | 0.49%   |
| Nvidia MCP61 IDE                                                                        | 2        | 0.49%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 2        | 0.49%   |
| Micron/Crucial NVMe Controller                                                          | 2        | 0.49%   |
| Marvell Group 88SE9123 PCIe SATA 6.0 Gb/s controller                                    | 2        | 0.49%   |
| JMicron JMB361 AHCI/IDE                                                                 | 2        | 0.49%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 0.49%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 2        | 0.49%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 2        | 0.49%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 2        | 0.49%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 2        | 0.49%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]           | 2        | 0.49%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 2        | 0.49%   |
| AMD FCH SATA Controller D                                                               | 2        | 0.49%   |
| VIA VT6421 IDE/SATA Controller                                                          | 1        | 0.25%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                             | 1        | 0.25%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 168      | 54.55%  |
| NVMe | 91       | 29.55%  |
| IDE  | 29       | 9.42%   |
| RAID | 18       | 5.84%   |
| SAS  | 2        | 0.65%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 109      | 54.5%   |
| AMD    | 91       | 45.5%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor      | 9        | 4.5%    |
| AMD Ryzen 7 5800X 8-Core Processor     | 7        | 3.5%    |
| AMD Ryzen 9 5900X 12-Core Processor    | 6        | 3%      |
| AMD Ryzen 7 3700X 8-Core Processor     | 6        | 3%      |
| AMD Ryzen 5 5600X 6-Core Processor     | 6        | 3%      |
| AMD Ryzen 9 5950X 16-Core Processor    | 5        | 2.5%    |
| Intel Core i7-7700K CPU @ 4.20GHz      | 4        | 2%      |
| Intel Core i7-6700K CPU @ 4.00GHz      | 4        | 2%      |
| AMD FX-8350 Eight-Core Processor       | 4        | 2%      |
| Intel Core i7-8700K CPU @ 3.70GHz      | 3        | 1.5%    |
| Intel Core i7-3770 CPU @ 3.40GHz       | 3        | 1.5%    |
| Intel Core i7-2600 CPU @ 3.40GHz       | 3        | 1.5%    |
| Intel Core i5-6600K CPU @ 3.50GHz      | 3        | 1.5%    |
| Intel Core i5-4570 CPU @ 3.20GHz       | 3        | 1.5%    |
| AMD Ryzen 9 3900X 12-Core Processor    | 3        | 1.5%    |
| AMD Ryzen 7 5700G with Radeon Graphics | 3        | 1.5%    |
| AMD Ryzen 7 2700X Eight-Core Processor | 3        | 1.5%    |
| AMD Ryzen 7 1700 Eight-Core Processor  | 3        | 1.5%    |
| AMD Ryzen 5 2600X Six-Core Processor   | 3        | 1.5%    |
| AMD Ryzen 5 1600X Six-Core Processor   | 3        | 1.5%    |
| Intel Core i9-9900K CPU @ 3.60GHz      | 2        | 1%      |
| Intel Core i9-10900X CPU @ 3.70GHz     | 2        | 1%      |
| Intel Core i7-9700K CPU @ 3.60GHz      | 2        | 1%      |
| Intel Core i7-7700 CPU @ 3.60GHz       | 2        | 1%      |
| Intel Core i7-4790K CPU @ 4.00GHz      | 2        | 1%      |
| Intel Core i7-4790 CPU @ 3.60GHz       | 2        | 1%      |
| Intel Core i7 CPU 950 @ 3.07GHz        | 2        | 1%      |
| Intel Core i5-9600K CPU @ 3.70GHz      | 2        | 1%      |
| Intel Core i5-2400 CPU @ 3.10GHz       | 2        | 1%      |
| Intel Core i5 CPU 760 @ 2.80GHz        | 2        | 1%      |
| Intel Core i3-8100 CPU @ 3.60GHz       | 2        | 1%      |
| Intel Core i3-4150 CPU @ 3.50GHz       | 2        | 1%      |
| Intel Core i3-2120 CPU @ 3.30GHz       | 2        | 1%      |
| Intel Core i3-10105 CPU @ 3.70GHz      | 2        | 1%      |
| Intel 12th Gen Core i5-12600K          | 2        | 1%      |
| AMD Ryzen 9 3950X 16-Core Processor    | 2        | 1%      |
| AMD Ryzen 5 5600G with Radeon Graphics | 2        | 1%      |
| AMD Ryzen 5 3600X 6-Core Processor     | 2        | 1%      |
| AMD Ryzen 5 1600 Six-Core Processor    | 2        | 1%      |
| Intel Xeon E-2146G CPU @ 3.50GHz       | 1        | 0.5%    |
| Intel Xeon CPU X5670 @ 2.93GHz         | 1        | 0.5%    |
| Intel Xeon CPU X3430 @ 2.40GHz         | 1        | 0.5%    |
| Intel Xeon CPU W3530 @ 2.80GHz         | 1        | 0.5%    |
| Intel Xeon CPU E5462 @ 2.80GHz         | 1        | 0.5%    |
| Intel Xeon CPU E5-2687W 0 @ 3.10GHz    | 1        | 0.5%    |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz     | 1        | 0.5%    |
| Intel Xeon CPU E5-1680 v2 @ 3.00GHz    | 1        | 0.5%    |
| Intel Xeon CPU E5-1630 v4 @ 3.70GHz    | 1        | 0.5%    |
| Intel Pentium Gold G6400 CPU @ 4.00GHz | 1        | 0.5%    |
| Intel Pentium Dual CPU E2140 @ 1.60GHz | 1        | 0.5%    |
| Intel Pentium D CPU 2.80GHz            | 1        | 0.5%    |
| Intel Pentium CPU G4560 @ 3.50GHz      | 1        | 0.5%    |
| Intel Pentium CPU G3240 @ 3.10GHz      | 1        | 0.5%    |
| Intel Pentium CPU G2030 @ 3.00GHz      | 1        | 0.5%    |
| Intel Core i9-9900KF CPU @ 3.60GHz     | 1        | 0.5%    |
| Intel Core i9-7940X CPU @ 3.10GHz      | 1        | 0.5%    |
| Intel Core i9-10900K CPU @ 3.70GHz     | 1        | 0.5%    |
| Intel Core i7-9700 CPU @ 3.00GHz       | 1        | 0.5%    |
| Intel Core i7-6800K CPU @ 3.40GHz      | 1        | 0.5%    |
| Intel Core i7-6700 CPU @ 3.40GHz       | 1        | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i7          | 36       | 18%     |
| AMD Ryzen 5            | 30       | 15%     |
| Intel Core i5          | 25       | 12.5%   |
| AMD Ryzen 7            | 25       | 12.5%   |
| AMD Ryzen 9            | 16       | 8%      |
| Other                  | 9        | 4.5%    |
| Intel Xeon             | 9        | 4.5%    |
| Intel Core i3          | 9        | 4.5%    |
| Intel Core i9          | 7        | 3.5%    |
| AMD FX                 | 6        | 3%      |
| Intel Pentium          | 3        | 1.5%    |
| Intel Core 2 Quad      | 3        | 1.5%    |
| Intel Celeron          | 3        | 1.5%    |
| AMD Ryzen Threadripper | 3        | 1.5%    |
| Intel Core 2           | 2        | 1%      |
| AMD Ryzen 3            | 2        | 1%      |
| Intel Pentium Gold     | 1        | 0.5%    |
| Intel Pentium Dual     | 1        | 0.5%    |
| Intel Pentium D        | 1        | 0.5%    |
| AMD Sempron            | 1        | 0.5%    |
| AMD PRO A10            | 1        | 0.5%    |
| AMD Phenom II X6       | 1        | 0.5%    |
| AMD Phenom II X3       | 1        | 0.5%    |
| AMD Phenom             | 1        | 0.5%    |
| AMD Athlon II X4       | 1        | 0.5%    |
| AMD Athlon II X2       | 1        | 0.5%    |
| AMD A8                 | 1        | 0.5%    |
| AMD A10                | 1        | 0.5%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 67       | 33.5%   |
| 6      | 44       | 22%     |
| 8      | 36       | 18%     |
| 2      | 22       | 11%     |
| 12     | 11       | 5.5%    |
| 16     | 9        | 4.5%    |
| 10     | 5        | 2.5%    |
| 32     | 2        | 1%      |
| 3      | 2        | 1%      |
| 24     | 1        | 0.5%    |
| 14     | 1        | 0.5%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 197      | 98.5%   |
| 2      | 3        | 1.5%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 147      | 73.5%   |
| 1      | 53       | 26.5%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 200      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 168      | 84%     |
| 0x0800820d | 5        | 2.5%    |
| 0x08701021 | 3        | 1.5%    |
| 0x906ec    | 2        | 1%      |
| 0x906ea    | 2        | 1%      |
| 0x906e9    | 2        | 1%      |
| 0x90672    | 2        | 1%      |
| 0x206a7    | 2        | 1%      |
| 0x0a201016 | 2        | 1%      |
| 0x08001138 | 2        | 1%      |
| 0xa0655    | 1        | 0.5%    |
| 0xa0653    | 1        | 0.5%    |
| 0x506e3    | 1        | 0.5%    |
| 0x50657    | 1        | 0.5%    |
| 0x0a201006 | 1        | 0.5%    |
| 0x08701013 | 1        | 0.5%    |
| 0x08301039 | 1        | 0.5%    |
| 0x08101016 | 1        | 0.5%    |
| 0x08001137 | 1        | 0.5%    |
| 0x0600611a | 1        | 0.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 3            | 29       | 14.5%   |
| Zen 2            | 25       | 12.5%   |
| KabyLake         | 23       | 11.5%   |
| Haswell          | 16       | 8%      |
| Zen+             | 13       | 6.5%    |
| SandyBridge      | 12       | 6%      |
| Skylake          | 11       | 5.5%    |
| Zen              | 9        | 4.5%    |
| IvyBridge        | 9        | 4.5%    |
| CometLake        | 8        | 4%      |
| Piledriver       | 7        | 3.5%    |
| Nehalem          | 7        | 3.5%    |
| Unknown          | 7        | 3.5%    |
| K10              | 5        | 2.5%    |
| Penryn           | 4        | 2%      |
| Core             | 3        | 1.5%    |
| Westmere         | 2        | 1%      |
| Excavator        | 2        | 1%      |
| Broadwell        | 2        | 1%      |
| Alderlake Hybrid | 2        | 1%      |
| Silvermont       | 1        | 0.5%    |
| NetBurst         | 1        | 0.5%    |
| Jaguar           | 1        | 0.5%    |
| Goldmont         | 1        | 0.5%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 105      | 49.53%  |
| AMD                        | 72       | 33.96%  |
| Intel                      | 34       | 16.04%  |
| Matrox Electronics Systems | 1        | 0.47%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 10       | 4.52%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 8        | 3.62%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 7        | 3.17%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 7        | 3.17%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 6        | 2.71%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 6        | 2.71%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 5        | 2.26%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 4        | 1.81%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 4        | 1.81%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 4        | 1.81%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 4        | 1.81%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                        | 4        | 1.81%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 3        | 1.36%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 1.36%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 1.36%   |
| Nvidia GF108 [GeForce GT 730]                                               | 3        | 1.36%   |
| Nvidia GA106 [GeForce RTX 3060]                                             | 3        | 1.36%   |
| Nvidia GA104 [GeForce RTX 3070 Ti]                                          | 3        | 1.36%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 3        | 1.36%   |
| Intel HD Graphics 530                                                       | 3        | 1.36%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 1.36%   |
| Intel AlderLake-S GT1                                                       | 3        | 1.36%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 1.36%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 1.36%   |
| AMD Cezanne                                                                 | 3        | 1.36%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 1.36%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 3        | 1.36%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 2        | 0.9%    |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 2        | 0.9%    |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                      | 2        | 0.9%    |
| Nvidia TU102 [GeForce RTX 2080 Ti]                                          | 2        | 0.9%    |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 2        | 0.9%    |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 0.9%    |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 2        | 0.9%    |
| Nvidia GK104 [GeForce GTX 760]                                              | 2        | 0.9%    |
| Nvidia GA104 [GeForce RTX 3060 Ti]                                          | 2        | 0.9%    |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                          | 2        | 0.9%    |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 2        | 0.9%    |
| Intel 82945G/GZ Integrated Graphics Controller                              | 2        | 0.9%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 0.9%    |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 2        | 0.9%    |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 2        | 0.9%    |
| AMD Tonga PRO [Radeon R9 285/380]                                           | 2        | 0.9%    |
| AMD Navi 24 [Radeon RX 6400 / 6500 XT]                                      | 2        | 0.9%    |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2        | 0.9%    |
| AMD Cypress XT [Radeon HD 5870]                                             | 2        | 0.9%    |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 0.45%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.45%   |
| Nvidia TU116 [GeForce GTX 1650]                                             | 1        | 0.45%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 1        | 0.45%   |
| Nvidia TU104 [GeForce RTX 2080]                                             | 1        | 0.45%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 0.45%   |
| Nvidia GV100 [TITAN V]                                                      | 1        | 0.45%   |
| Nvidia GT216 [GeForce GT 220]                                               | 1        | 0.45%   |
| Nvidia GP107GL [Quadro P1000]                                               | 1        | 0.45%   |
| Nvidia GP107 [GeForce GTX 1050 3GB]                                         | 1        | 0.45%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 0.45%   |
| Nvidia GP100GL [Quadro GP100]                                               | 1        | 0.45%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 0.45%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 0.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| 1 x Nvidia           | 99       | 48.77%  |
| 1 x AMD              | 64       | 31.53%  |
| 1 x Intel            | 24       | 11.82%  |
| 2 x Nvidia           | 4        | 1.97%   |
| 2 x AMD              | 3        | 1.48%   |
| Intel + AMD          | 3        | 1.48%   |
| Other                | 1        | 0.49%   |
| 2 x AMD + 1 x Nvidia | 1        | 0.49%   |
| 1 x Matrox           | 1        | 0.49%   |
| Intel + Nvidia       | 1        | 0.49%   |
| AMD + 2 x Nvidia     | 1        | 0.49%   |
| AMD + Nvidia         | 1        | 0.49%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 101      | 50%     |
| Proprietary | 96       | 47.52%  |
| Unknown     | 5        | 2.48%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 102      | 50.25%  |
| 7.01-8.0   | 27       | 13.3%   |
| 8.01-16.0  | 20       | 9.85%   |
| 3.01-4.0   | 17       | 8.37%   |
| 5.01-6.0   | 15       | 7.39%   |
| 1.01-2.0   | 10       | 4.93%   |
| 2.01-3.0   | 7        | 3.45%   |
| 0.51-1.0   | 2        | 0.99%   |
| 32.01-64.0 | 1        | 0.49%   |
| 16.01-24.0 | 1        | 0.49%   |
| 0.01-0.5   | 1        | 0.49%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 39       | 17.11%  |
| Dell                 | 32       | 14.04%  |
| Goldstar             | 23       | 10.09%  |
| Hewlett-Packard      | 15       | 6.58%   |
| Acer                 | 14       | 6.14%   |
| Ancor Communications | 13       | 5.7%    |
| ASUSTek Computer     | 12       | 5.26%   |
| AOC                  | 12       | 5.26%   |
| BenQ                 | 11       | 4.82%   |
| Iiyama               | 5        | 2.19%   |
| Unknown              | 4        | 1.75%   |
| NEC Computers        | 4        | 1.75%   |
| ViewSonic            | 3        | 1.32%   |
| Sceptre Tech         | 3        | 1.32%   |
| MSI                  | 3        | 1.32%   |
| Gigabyte Technology  | 3        | 1.32%   |
| Viotek               | 2        | 0.88%   |
| Vestel Elektronik    | 2        | 0.88%   |
| Lenovo               | 2        | 0.88%   |
| ITE                  | 2        | 0.88%   |
| ___                  | 1        | 0.44%   |
| VOXICON              | 1        | 0.44%   |
| Vizio                | 1        | 0.44%   |
| Valve                | 1        | 0.44%   |
| Unknown (XXX)        | 1        | 0.44%   |
| SKY                  | 1        | 0.44%   |
| Sharp                | 1        | 0.44%   |
| RTK                  | 1        | 0.44%   |
| Positivo             | 1        | 0.44%   |
| Pioneer              | 1        | 0.44%   |
| Philips              | 1        | 0.44%   |
| Orion                | 1        | 0.44%   |
| ONN                  | 1        | 0.44%   |
| Onkyo                | 1        | 0.44%   |
| OEM                  | 1        | 0.44%   |
| Medion Akoya         | 1        | 0.44%   |
| Impression           | 1        | 0.44%   |
| Huion                | 1        | 0.44%   |
| Hitachi              | 1        | 0.44%   |
| GVE                  | 1        | 0.44%   |
| GDH                  | 1        | 0.44%   |
| Fujitsu Siemens      | 1        | 0.44%   |
| Eizo                 | 1        | 0.44%   |
| CVT                  | 1        | 0.44%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 3        | 1.26%   |
| ASUSTek Computer VG249 AUS2421 1920x1080 527x296mm 23.8-inch            | 3        | 1.26%   |
| Vestel Elektronik 28W_LCD_TV VES3700 1920x540                           | 2        | 0.84%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 2        | 0.84%   |
| Dell U2212HM DELD048 1920x1080 475x267mm 21.5-inch                      | 2        | 0.84%   |
| Dell S2716DG DELA0D1 2560x1440 598x336mm 27.0-inch                      | 2        | 0.84%   |
| Dell P2419H DELD0DA 1920x1080 530x300mm 24.0-inch                       | 2        | 0.84%   |
| Dell AW3821DW DELA17F 3840x1600 880x367mm 37.5-inch                     | 2        | 0.84%   |
| Dell 1704FPV DEL3016 1280x1024 338x270mm 17.0-inch                      | 2        | 0.84%   |
| ASUSTek Computer VG279 AUS2782 1920x1080 598x336mm 27.0-inch            | 2        | 0.84%   |
| AOC 27V2G5 AOC2702 1920x1080 598x336mm 27.0-inch                        | 2        | 0.84%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch   | 2        | 0.84%   |
| ___ LCDTV16 ___9000 1360x768                                            | 1        | 0.42%   |
| VOXICON D27Q0 DUS2700 2560x1440 597x336mm 27.0-inch                     | 1        | 0.42%   |
| Vizio V435-H1 VIZ1039 3840x2160 941x529mm 42.5-inch                     | 1        | 0.42%   |
| Viotek VIOTEKGN27C2 VTK0027 1920x1080 598x336mm 27.0-inch               | 1        | 0.42%   |
| Viotek SUW49DA VTK0490 2560x1440 1194x336mm 48.8-inch                   | 1        | 0.42%   |
| ViewSonic VX3276-FHD VSCE735 1920x1080 698x393mm 31.5-inch              | 1        | 0.42%   |
| ViewSonic VX2450 SERIES VSCE226 1920x1080 525x297mm 23.7-inch           | 1        | 0.42%   |
| ViewSonic VA2261 Series VSC0F30 1920x1080 477x268mm 21.5-inch           | 1        | 0.42%   |
| Valve Index HMD VLV91A8                                                 | 1        | 0.42%   |
| Unknown SMART TV 0563 1920x1080 1209x680mm 54.6-inch                    | 1        | 0.42%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                      | 1        | 0.42%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                   | 1        | 0.42%   |
| Unknown LCD Monitor MEC MD20491 1920x1080                               | 1        | 0.42%   |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1209x680mm 54.6-inch          | 1        | 0.42%   |
| SKY M16U1 SKY0156 3840x2160 345x194mm 15.6-inch                         | 1        | 0.42%   |
| Sharp HDMI SHP0FEC 1920x1080 820x460mm 37.0-inch                        | 1        | 0.42%   |
| Sceptre Tech Sceptre M25 SPT09FB 1920x1080 544x303mm 24.5-inch          | 1        | 0.42%   |
| Sceptre Tech F27 SPT0ABF 1920x1080 409x230mm 18.5-inch                  | 1        | 0.42%   |
| Sceptre Tech E32 SPT0CB8 1366x768 575x323mm 26.0-inch                   | 1        | 0.42%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch       | 1        | 0.42%   |
| Samsung Electronics SyncMaster SAM0613 1920x1080                        | 1        | 0.42%   |
| Samsung Electronics SyncMaster SAM0604 1920x1080                        | 1        | 0.42%   |
| Samsung Electronics SyncMaster SAM0598 1360x768 410x230mm 18.5-inch     | 1        | 0.42%   |
| Samsung Electronics SyncMaster SAM044C 1680x1050 474x296mm 22.0-inch    | 1        | 0.42%   |
| Samsung Electronics SyncMaster SAM031F 1680x1050 474x296mm 22.0-inch    | 1        | 0.42%   |
| Samsung Electronics SyncMaster SAM030E 1680x1050 474x296mm 22.0-inch    | 1        | 0.42%   |
| Samsung Electronics SMBX2440 SAM068A 1920x1080 531x299mm 24.0-inch      | 1        | 0.42%   |
| Samsung Electronics SMBX2431 SAM0771 1920x1080 531x299mm 24.0-inch      | 1        | 0.42%   |
| Samsung Electronics SMB2220N SAM06A2 1920x1080 480x270mm 21.7-inch      | 1        | 0.42%   |
| Samsung Electronics SA300/SA350 SAM0793 1920x1080 531x299mm 24.0-inch   | 1        | 0.42%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch    | 1        | 0.42%   |
| Samsung Electronics S32F351 SAM0D24 1920x1080 698x393mm 31.5-inch       | 1        | 0.42%   |
| Samsung Electronics S24E390 SAM0C1A 1920x1080 520x290mm 23.4-inch       | 1        | 0.42%   |
| Samsung Electronics S24D590 SAM0B47 1920x1080 521x293mm 23.5-inch       | 1        | 0.42%   |
| Samsung Electronics S24B240 SAM08E9 1920x1080 521x293mm 23.5-inch       | 1        | 0.42%   |
| Samsung Electronics S23B550 SAM0919 1920x1080 510x287mm 23.0-inch       | 1        | 0.42%   |
| Samsung Electronics S22C300 SAM0A20 1920x1080 480x270mm 21.7-inch       | 1        | 0.42%   |
| Samsung Electronics S22B150 SAM08A3 1920x1080 477x268mm 21.5-inch       | 1        | 0.42%   |
| Samsung Electronics LU28R55 SAM1017 3840x2160 632x360mm 28.6-inch       | 1        | 0.42%   |
| Samsung Electronics LU28R55 SAM1015 3840x2160 632x360mm 28.6-inch       | 1        | 0.42%   |
| Samsung Electronics LS27A70 SAM71A0 3840x2160 597x336mm 27.0-inch       | 1        | 0.42%   |
| Samsung Electronics LS24AG30x SAM7178 1920x1080 527x296mm 23.8-inch     | 1        | 0.42%   |
| Samsung Electronics LCD Monitor SyncMaster 3040x900                     | 1        | 0.42%   |
| Samsung Electronics LCD Monitor SyncMaster                              | 1        | 0.42%   |
| Samsung Electronics LCD Monitor SAM0F14 3840x2160 950x540mm 43.0-inch   | 1        | 0.42%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1872x1053mm 84.6-inch | 1        | 0.42%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch   | 1        | 0.42%   |
| Samsung Electronics LCD Monitor SAM08FC 1366x768 700x390mm 31.5-inch    | 1        | 0.42%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 104      | 48.37%  |
| 3840x2160 (4K)     | 30       | 13.95%  |
| 2560x1440 (QHD)    | 23       | 10.7%   |
| 1680x1050 (WSXGA+) | 11       | 5.12%   |
| 3440x1440          | 7        | 3.26%   |
| 1280x1024 (SXGA)   | 7        | 3.26%   |
| 2560x1080          | 6        | 2.79%   |
| 1920x1200 (WUXGA)  | 5        | 2.33%   |
| 3840x1600          | 3        | 1.4%    |
| 3840x1080          | 3        | 1.4%    |
| 1366x768 (WXGA)    | 3        | 1.4%    |
| 1920x540           | 2        | 0.93%   |
| 1600x900 (HD+)     | 2        | 0.93%   |
| 1440x900 (WXGA+)   | 2        | 0.93%   |
| 1360x768           | 2        | 0.93%   |
| Unknown            | 2        | 0.93%   |
| 3040x900           | 1        | 0.47%   |
| 2560x1600          | 1        | 0.47%   |
| 1024x768 (XGA)     | 1        | 0.47%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 41       | 18.39%  |
| 24      | 30       | 13.45%  |
| 23      | 30       | 13.45%  |
| 21      | 20       | 8.97%   |
| 31      | 14       | 6.28%   |
| 34      | 12       | 5.38%   |
| Unknown | 9        | 4.04%   |
| 22      | 7        | 3.14%   |
| 19      | 6        | 2.69%   |
| 84      | 5        | 2.24%   |
| 25      | 5        | 2.24%   |
| 20      | 5        | 2.24%   |
| 37      | 4        | 1.79%   |
| 17      | 4        | 1.79%   |
| 72      | 3        | 1.35%   |
| 54      | 3        | 1.35%   |
| 48      | 3        | 1.35%   |
| 32      | 3        | 1.35%   |
| 18      | 3        | 1.35%   |
| 46      | 2        | 0.9%    |
| 26      | 2        | 0.9%    |
| 15      | 2        | 0.9%    |
| 65      | 1        | 0.45%   |
| 52      | 1        | 0.45%   |
| 49      | 1        | 0.45%   |
| 47      | 1        | 0.45%   |
| 42      | 1        | 0.45%   |
| 35      | 1        | 0.45%   |
| 33      | 1        | 0.45%   |
| 30      | 1        | 0.45%   |
| 29      | 1        | 0.45%   |
| 28      | 1        | 0.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 96       | 44.86%  |
| 401-500     | 36       | 16.82%  |
| 601-700     | 21       | 9.81%   |
| 701-800     | 16       | 7.48%   |
| 1001-1500   | 12       | 5.61%   |
| Unknown     | 9        | 4.21%   |
| 1501-2000   | 8        | 3.74%   |
| 301-350     | 6        | 2.8%    |
| 801-900     | 5        | 2.34%   |
| 351-400     | 4        | 1.87%   |
| 901-1000    | 1        | 0.47%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 150      | 72.82%  |
| 16/10   | 20       | 9.71%   |
| 21/9    | 17       | 8.25%   |
| 5/4     | 7        | 3.4%    |
| Unknown | 6        | 2.91%   |
| 32/9    | 4        | 1.94%   |
| 4/3     | 2        | 0.97%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 66       | 30.56%  |
| 301-350        | 43       | 19.91%  |
| 351-500        | 34       | 15.74%  |
| 251-300        | 16       | 7.41%   |
| 151-200        | 15       | 6.94%   |
| More than 1000 | 13       | 6.02%   |
| 501-1000       | 11       | 5.09%   |
| Unknown        | 9        | 4.17%   |
| 141-150        | 7        | 3.24%   |
| 101-110        | 2        | 0.93%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 120      | 60.3%   |
| 101-120       | 49       | 24.62%  |
| 1-50          | 9        | 4.52%   |
| Unknown       | 9        | 4.52%   |
| 121-160       | 7        | 3.52%   |
| 161-240       | 4        | 2.01%   |
| More than 240 | 1        | 0.5%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 145      | 72.14%  |
| 2     | 43       | 21.39%  |
| 3     | 6        | 2.99%   |
| 0     | 6        | 2.99%   |
| 6     | 1        | 0.5%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 115      | 37.7%   |
| Intel                           | 112      | 36.72%  |
| Qualcomm Atheros                | 19       | 6.23%   |
| Broadcom                        | 11       | 3.61%   |
| TP-Link                         | 5        | 1.64%   |
| Ralink Technology               | 4        | 1.31%   |
| MediaTek                        | 4        | 1.31%   |
| Aquantia                        | 4        | 1.31%   |
| NetGear                         | 3        | 0.98%   |
| Microsoft                       | 3        | 0.98%   |
| ASUSTek Computer                | 3        | 0.98%   |
| Xiaomi                          | 2        | 0.66%   |
| Nvidia                          | 2        | 0.66%   |
| InterBiometrics                 | 2        | 0.66%   |
| D-Link                          | 2        | 0.66%   |
| Sitecom Europe                  | 1        | 0.33%   |
| SIEMENS                         | 1        | 0.33%   |
| Ralink                          | 1        | 0.33%   |
| Qualcomm Atheros Communications | 1        | 0.33%   |
| Qualcomm                        | 1        | 0.33%   |
| Mellanox Technologies           | 1        | 0.33%   |
| IMC Networks                    | 1        | 0.33%   |
| Hyperkin                        | 1        | 0.33%   |
| Google                          | 1        | 0.33%   |
| Gemtek                          | 1        | 0.33%   |
| DisplayLink                     | 1        | 0.33%   |
| D-Link System                   | 1        | 0.33%   |
| Broadcom Limited                | 1        | 0.33%   |
| Belkin Components               | 1        | 0.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 76       | 21.11%  |
| Intel I211 Gigabit Network Connection                                                         | 35       | 9.72%   |
| Intel Wi-Fi 6 AX200                                                                           | 29       | 8.06%   |
| Realtek RTL8125 2.5GbE Controller                                                             | 25       | 6.94%   |
| Intel Ethernet Controller I225-V                                                              | 11       | 3.06%   |
| Intel Ethernet Connection (2) I219-V                                                          | 9        | 2.5%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 9        | 2.5%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 7        | 1.94%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                            | 7        | 1.94%   |
| Realtek 802.11ac NIC                                                                          | 6        | 1.67%   |
| Intel Ethernet Connection I217-LM                                                             | 6        | 1.67%   |
| Intel Ethernet Connection (7) I219-V                                                          | 6        | 1.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 6        | 1.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 5        | 1.39%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 4        | 1.11%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                              | 4        | 1.11%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 3        | 0.83%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                                     | 3        | 0.83%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                     | 3        | 0.83%   |
| Intel Ethernet Connection (2) I218-V                                                          | 3        | 0.83%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 3        | 0.83%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                                          | 2        | 0.56%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 2        | 0.56%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 2        | 0.56%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 2        | 0.56%   |
| Nvidia MCP61 Ethernet                                                                         | 2        | 0.56%   |
| NetGear A6210                                                                                 | 2        | 0.56%   |
| Microsoft Xbox 360 Wireless Adapter                                                           | 2        | 0.56%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                 | 2        | 0.56%   |
| InterBiometrics Io                                                                            | 2        | 0.56%   |
| Intel Wireless Gigabit 17265                                                                  | 2        | 0.56%   |
| Intel Wireless 7265                                                                           | 2        | 0.56%   |
| Intel Tiger Lake PCH CNVi WiFi                                                                | 2        | 0.56%   |
| Intel Ethernet Connection (14) I219-V                                                         | 2        | 0.56%   |
| Intel 82579V Gigabit Network Connection                                                       | 2        | 0.56%   |
| Intel 82574L Gigabit Network Connection                                                       | 2        | 0.56%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                                              | 2        | 0.56%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]                             | 2        | 0.56%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                               | 1        | 0.28%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 1        | 0.28%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]                           | 1        | 0.28%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 1        | 0.28%   |
| TP-Link 802.11ac NIC                                                                          | 1        | 0.28%   |
| Sitecom Europe WL-344 Wireless Adapter 300N X2 [Ralink RT3071]                                | 1        | 0.28%   |
| SIEMENS SIMATIC NET CP 5611 / 5621                                                            | 1        | 0.28%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1        | 0.28%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 0.28%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 0.28%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                                        | 1        | 0.28%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                      | 1        | 0.28%   |
| Realtek RTL8152 Fast Ethernet Adapter                                                         | 1        | 0.28%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 0.28%   |
| Realtek Killer E3000 2.5GbE Controller                                                        | 1        | 0.28%   |
| Ralink RT5372 Wireless Adapter                                                                | 1        | 0.28%   |
| Ralink RT3572 Wireless Adapter                                                                | 1        | 0.28%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 1        | 0.28%   |
| Ralink MT7601U Wireless Adapter                                                               | 1        | 0.28%   |
| Ralink RT2500 Wireless 802.11bg                                                               | 1        | 0.28%   |
| Qualcomm Redmi 9T                                                                             | 1        | 0.28%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                                     | 1        | 0.28%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 64       | 50%     |
| Realtek Semiconductor           | 15       | 11.72%  |
| Qualcomm Atheros                | 11       | 8.59%   |
| Broadcom                        | 8        | 6.25%   |
| TP-Link                         | 4        | 3.13%   |
| Ralink Technology               | 4        | 3.13%   |
| MediaTek                        | 4        | 3.13%   |
| NetGear                         | 3        | 2.34%   |
| Microsoft                       | 3        | 2.34%   |
| ASUSTek Computer                | 3        | 2.34%   |
| D-Link                          | 2        | 1.56%   |
| Sitecom Europe                  | 1        | 0.78%   |
| Ralink                          | 1        | 0.78%   |
| Qualcomm Atheros Communications | 1        | 0.78%   |
| IMC Networks                    | 1        | 0.78%   |
| Gemtek                          | 1        | 0.78%   |
| D-Link System                   | 1        | 0.78%   |
| Belkin Components               | 1        | 0.78%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                           | 29       | 22.31%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 9        | 6.92%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 7        | 5.38%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                            | 7        | 5.38%   |
| Realtek 802.11ac NIC                                                                          | 6        | 4.62%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 5        | 3.85%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                              | 4        | 3.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 3        | 2.31%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 3        | 2.31%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 2        | 1.54%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 2        | 1.54%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 2        | 1.54%   |
| NetGear A6210                                                                                 | 2        | 1.54%   |
| Microsoft Xbox 360 Wireless Adapter                                                           | 2        | 1.54%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                 | 2        | 1.54%   |
| Intel Wireless Gigabit 17265                                                                  | 2        | 1.54%   |
| Intel Wireless 7265                                                                           | 2        | 1.54%   |
| Intel Tiger Lake PCH CNVi WiFi                                                                | 2        | 1.54%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 1        | 0.77%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]                           | 1        | 0.77%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 1        | 0.77%   |
| TP-Link 802.11ac NIC                                                                          | 1        | 0.77%   |
| Sitecom Europe WL-344 Wireless Adapter 300N X2 [Ralink RT3071]                                | 1        | 0.77%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1        | 0.77%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 0.77%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 0.77%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                                        | 1        | 0.77%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 0.77%   |
| Ralink RT5372 Wireless Adapter                                                                | 1        | 0.77%   |
| Ralink RT3572 Wireless Adapter                                                                | 1        | 0.77%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 1        | 0.77%   |
| Ralink MT7601U Wireless Adapter                                                               | 1        | 0.77%   |
| Ralink RT2500 Wireless 802.11bg                                                               | 1        | 0.77%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 1        | 0.77%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1        | 0.77%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1        | 0.77%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 1        | 0.77%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 1        | 0.77%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                              | 1        | 0.77%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express)         | 1        | 0.77%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]                                   | 1        | 0.77%   |
| Microsoft XBOX ACC                                                                            | 1        | 0.77%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                       | 1        | 0.77%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                                            | 1        | 0.77%   |
| Intel Wireless-AC 9260                                                                        | 1        | 0.77%   |
| Intel Wireless 8260                                                                           | 1        | 0.77%   |
| Intel Wireless 3165                                                                           | 1        | 0.77%   |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]                                          | 1        | 0.77%   |
| Gemtek WUBR-177G [Ralink RT2571W]                                                             | 1        | 0.77%   |
| D-Link System DWA-140 RangeBooster N Adapter(rev.B2) [Ralink RT3072]                          | 1        | 0.77%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]                          | 1        | 0.77%   |
| D-Link DWA-121 802.11n Wireless N 150 Pico Adapter [Realtek RTL8188CUS]                       | 1        | 0.77%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 1        | 0.77%   |
| Belkin Components F5D7050 Wireless G Adapter v4000 [Zydas ZD1211B]                            | 1        | 0.77%   |
| ASUS USB-AC68 802.11a/b/g/n/ac (4x4) Wireless Adapter [Realtek RTL8814AU]                     | 1        | 0.77%   |
| ASUS USB-AC56 802.11a/b/g/n/ac Wireless Adapter [Realtek RTL8812AU]                           | 1        | 0.77%   |
| ASUS 802.11ac NIC                                                                             | 1        | 0.77%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 107      | 48.42%  |
| Intel                 | 88       | 39.82%  |
| Qualcomm Atheros      | 9        | 4.07%   |
| Broadcom              | 4        | 1.81%   |
| Aquantia              | 4        | 1.81%   |
| Xiaomi                | 2        | 0.9%    |
| Nvidia                | 2        | 0.9%    |
| TP-Link               | 1        | 0.45%   |
| Qualcomm              | 1        | 0.45%   |
| Mellanox Technologies | 1        | 0.45%   |
| DisplayLink           | 1        | 0.45%   |
| Broadcom Limited      | 1        | 0.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 76       | 33.78%  |
| Intel I211 Gigabit Network Connection                             | 35       | 15.56%  |
| Realtek RTL8125 2.5GbE Controller                                 | 25       | 11.11%  |
| Intel Ethernet Controller I225-V                                  | 11       | 4.89%   |
| Intel Ethernet Connection (2) I219-V                              | 9        | 4%      |
| Intel Ethernet Connection I217-LM                                 | 6        | 2.67%   |
| Intel Ethernet Connection (7) I219-V                              | 6        | 2.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6        | 2.67%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4        | 1.78%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3        | 1.33%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3        | 1.33%   |
| Intel Ethernet Connection (2) I218-V                              | 3        | 1.33%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 2        | 0.89%   |
| Nvidia MCP61 Ethernet                                             | 2        | 0.89%   |
| Intel Ethernet Connection (14) I219-V                             | 2        | 0.89%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 0.89%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 0.89%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2        | 0.89%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2        | 0.89%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1        | 0.44%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.44%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1        | 0.44%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1        | 0.44%   |
| Qualcomm Redmi 9T                                                 | 1        | 0.44%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.44%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.44%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.44%   |
| Mellanox MT27500 Family [ConnectX-3]                              | 1        | 0.44%   |
| Intel Ethernet Connection I217-V                                  | 1        | 0.44%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.44%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 0.44%   |
| Intel Ethernet Connection (17) I219-V                             | 1        | 0.44%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 0.44%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 1        | 0.44%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1        | 0.44%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 0.44%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)            | 1        | 0.44%   |
| DisplayLink USB3.0 Dual Video Dock                                | 1        | 0.44%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1        | 0.44%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                   | 1        | 0.44%   |
| Broadcom Limited NetXtreme BCM5722 Gigabit Ethernet PCI Express   | 1        | 0.44%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 0.44%   |
| Aquantia AQC108 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 197      | 60.99%  |
| WiFi     | 121      | 37.46%  |
| Modem    | 3        | 0.93%   |
| Unknown  | 2        | 0.62%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 145      | 71.08%  |
| WiFi     | 59       | 28.92%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 98       | 48.76%  |
| 2     | 79       | 39.3%   |
| 3     | 18       | 8.96%   |
| 0     | 4        | 1.99%   |
| 4     | 2        | 1%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 143      | 71.14%  |
| Yes  | 58       | 28.86%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 58       | 65.17%  |
| Cambridge Silicon Radio         | 11       | 12.36%  |
| ASUSTek Computer                | 7        | 7.87%   |
| Qualcomm Atheros Communications | 5        | 5.62%   |
| Foxconn / Hon Hai               | 2        | 2.25%   |
| Apple                           | 2        | 2.25%   |
| Realtek Semiconductor           | 1        | 1.12%   |
| MediaTek                        | 1        | 1.12%   |
| IMC Networks                    | 1        | 1.12%   |
| Broadcom                        | 1        | 1.12%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                 | 26       | 29.21%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 11       | 12.36%  |
| Intel Wireless-AC 3168 Bluetooth                      | 9        | 10.11%  |
| Intel Bluetooth Device                                | 9        | 10.11%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 5        | 5.62%   |
| Intel AX210 Bluetooth                                 | 5        | 5.62%   |
| Qualcomm Atheros  Bluetooth Device                    | 3        | 3.37%   |
| Intel Bluetooth wireless interface                    | 3        | 3.37%   |
| ASUS Bluetooth Radio                                  | 3        | 3.37%   |
| Realtek Bluetooth Radio                               | 1        | 1.12%   |
| Qualcomm Atheros Bluetooth USB Host Controller        | 1        | 1.12%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 1        | 1.12%   |
| MediaTek Wireless_Device                              | 1        | 1.12%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 1        | 1.12%   |
| IMC Networks Bluetooth Radio                          | 1        | 1.12%   |
| Foxconn / Hon Hai Wireless_Device                     | 1        | 1.12%   |
| Foxconn / Hon Hai Bluetooth Device                    | 1        | 1.12%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 1        | 1.12%   |
| ASUS Qualcomm Bluetooth 4.1                           | 1        | 1.12%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 1        | 1.12%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 1.12%   |
| ASUS ASUS USB-BT500                                   | 1        | 1.12%   |
| Apple Bluetooth USB Host Controller                   | 1        | 1.12%   |
| Apple Bluetooth HCI                                   | 1        | 1.12%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 113      | 27.76%  |
| Nvidia                               | 104      | 25.55%  |
| Intel                                | 102      | 25.06%  |
| C-Media Electronics                  | 12       | 2.95%   |
| Logitech                             | 8        | 1.97%   |
| Kingston Technology                  | 6        | 1.47%   |
| Focusrite-Novation                   | 5        | 1.23%   |
| SteelSeries ApS                      | 4        | 0.98%   |
| Corsair                              | 4        | 0.98%   |
| Razer USA                            | 3        | 0.74%   |
| Micro Star International             | 3        | 0.74%   |
| JMTek                                | 3        | 0.74%   |
| Creative Labs                        | 3        | 0.74%   |
| Texas Instruments                    | 2        | 0.49%   |
| Sennheiser Communications            | 2        | 0.49%   |
| GN Netcom                            | 2        | 0.49%   |
| Creative Technology                  | 2        | 0.49%   |
| ASUSTek Computer                     | 2        | 0.49%   |
| Antlion Audio                        | 2        | 0.49%   |
| Yamaha                               | 1        | 0.25%   |
| Valve Software                       | 1        | 0.25%   |
| USB MIDI                             | 1        | 0.25%   |
| Unknown                              | 1        | 0.25%   |
| Turtle Beach                         | 1        | 0.25%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.25%   |
| Sony                                 | 1        | 0.25%   |
| Shenzhen Rapoo Technology            | 1        | 0.25%   |
| SAVITECH                             | 1        | 0.25%   |
| Samson Technologies                  | 1        | 0.25%   |
| Native Instruments                   | 1        | 0.25%   |
| Microsoft                            | 1        | 0.25%   |
| Medeli Electronics                   | 1        | 0.25%   |
| JOUNIVO JV601                        | 1        | 0.25%   |
| Google                               | 1        | 0.25%   |
| Giga-Byte Technology                 | 1        | 0.25%   |
| Generalplus Technology               | 1        | 0.25%   |
| GEMBIRD                              | 1        | 0.25%   |
| FiiO Electronics Technology          | 1        | 0.25%   |
| fifinemicrophone.com                 | 1        | 0.25%   |
| FIFINE Microphones                   | 1        | 0.25%   |
| DEXP BK-20                           | 1        | 0.25%   |
| C&T                                  | 1        | 0.25%   |
| Blue Microphones                     | 1        | 0.25%   |
| BEHRINGER International              | 1        | 0.25%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 47       | 10.11%  |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 18       | 3.87%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 18       | 3.87%   |
| Nvidia GP106 High Definition Audio Controller                              | 15       | 3.23%   |
| Intel 200 Series PCH HD Audio                                              | 14       | 3.01%   |
| Nvidia GP107GL High Definition Audio Controller                            | 11       | 2.37%   |
| Nvidia GP104 High Definition Audio Controller                              | 11       | 2.37%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 11       | 2.37%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11       | 2.37%   |
| Intel Cannon Lake PCH cAVS                                                 | 10       | 2.15%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 10       | 2.15%   |
| Nvidia GA104 High Definition Audio Controller                              | 9        | 1.94%   |
| Nvidia Audio device                                                        | 9        | 1.94%   |
| AMD Family 17h/19h HD Audio Controller                                     | 9        | 1.94%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8        | 1.72%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 8        | 1.72%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 8        | 1.72%   |
| Nvidia TU104 HD Audio Controller                                           | 6        | 1.29%   |
| Nvidia GA102 High Definition Audio Controller                              | 6        | 1.29%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6        | 1.29%   |
| AMD Navi 10 HDMI Audio                                                     | 6        | 1.29%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 6        | 1.29%   |
| Nvidia TU116 High Definition Audio Controller                              | 5        | 1.08%   |
| Kingston Technology HyperX 7.1 Audio                                       | 5        | 1.08%   |
| Intel Alder Lake-S HD Audio Controller                                     | 5        | 1.08%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 5        | 1.08%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 5        | 1.08%   |
| Nvidia TU102 High Definition Audio Controller                              | 4        | 0.86%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4        | 0.86%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4        | 0.86%   |
| Intel Comet Lake PCH cAVS                                                  | 4        | 0.86%   |
| Intel Audio device                                                         | 4        | 0.86%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4        | 0.86%   |
| Nvidia TU106 High Definition Audio Controller                              | 3        | 0.65%   |
| Nvidia GP108 High Definition Audio Controller                              | 3        | 0.65%   |
| Nvidia GK104 HDMI Audio Controller                                         | 3        | 0.65%   |
| Micro Star International USB Audio                                         | 3        | 0.65%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3        | 0.65%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 3        | 0.65%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 3        | 0.65%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3        | 0.65%   |
| Focusrite-Novation Scarlett 2i2 Camera                                     | 3        | 0.65%   |
| C-Media Electronics Blue Snowball                                          | 3        | 0.65%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 3        | 0.65%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3        | 0.65%   |
| AMD Kabini HDMI/DP Audio                                                   | 3        | 0.65%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                             | 3        | 0.65%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 3        | 0.65%   |
| Nvidia MCP61 High Definition Audio                                         | 2        | 0.43%   |
| Nvidia GP102 HDMI Audio Controller                                         | 2        | 0.43%   |
| Nvidia GK106 HDMI Audio Controller                                         | 2        | 0.43%   |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 0.43%   |
| Logitech PRO X Wireless Gaming Headset                                     | 2        | 0.43%   |
| JMTek USB PnP Audio Device                                                 | 2        | 0.43%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]              | 2        | 0.43%   |
| C-Media Electronics USB Audio Device                                       | 2        | 0.43%   |
| AMD Tonga HDMI Audio [Radeon R9 285/380]                                   | 2        | 0.43%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 2        | 0.43%   |
| AMD FCH Azalia Controller                                                  | 2        | 0.43%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2        | 0.43%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 14       | 41.18%  |
| G.Skill             | 6        | 17.65%  |
| Team                | 4        | 11.76%  |
| Kingston            | 2        | 5.88%   |
| Unknown             | 2        | 5.88%   |
| Unknown             | 1        | 2.94%   |
| SK hynix            | 1        | 2.94%   |
| Samsung Electronics | 1        | 2.94%   |
| Patriot Memory      | 1        | 2.94%   |
| Micron Technology   | 1        | 2.94%   |
| Avant               | 1        | 2.94%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3000C15 8192MB DIMM DDR4 3000MT/s  | 3        | 8.82%   |
| Team RAM TEAMGROUP-UD4-3200 32GB DIMM DDR4 3200MT/s       | 2        | 5.88%   |
| G.Skill RAM F4-3600C18-8GTZRX 8GB DIMM DDR4 3600MT/s      | 2        | 5.88%   |
| Unknown                                                   | 2        | 5.88%   |
| Unknown RAM Module 16GB DIMM DDR4 3600MT/s                | 1        | 2.94%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3067MT/s        | 1        | 2.94%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3000MT/s        | 1        | 2.94%   |
| SK hynix RAM HMT351U6CFR8C-PBA 4GB DIMM DDR3 1600MT/s     | 1        | 2.94%   |
| Samsung RAM M378A1K43CB2-CTD 8192MB DIMM DDR4 3200MT/s    | 1        | 2.94%   |
| Patriot Memory RAM 4400 C19 Series 8GB DIMM DDR4 3000MT/s | 1        | 2.94%   |
| Micron RAM M378A1K43BB2G3A141 8GB DIMM DDR4 2400MT/s      | 1        | 2.94%   |
| Kingston RAM KVT8FP-HYC 4GB DIMM DDR3 1600MT/s            | 1        | 2.94%   |
| Kingston RAM KHX3600C18D4/16GX 16GB DIMM DDR4 3600MT/s    | 1        | 2.94%   |
| G.Skill RAM F4-3600C18-8GVK 8GB DIMM DDR4 3600MT/s        | 1        | 2.94%   |
| G.Skill RAM F4-3200C16-4GVKB 4GB DIMM DDR4 3200MT/s       | 1        | 2.94%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s      | 1        | 2.94%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s       | 1        | 2.94%   |
| Corsair RAM Module 16GB SODIMM DDR4 2400MT/s              | 1        | 2.94%   |
| Corsair RAM CMY8GX3M2A2400C11 4GB DIMM DDR3 2133MT/s      | 1        | 2.94%   |
| Corsair RAM CMX16GX3M4A1333C9 4GB DIMM DDR3 1333MT/s      | 1        | 2.94%   |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3266MT/s     | 1        | 2.94%   |
| Corsair RAM CMT32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s    | 1        | 2.94%   |
| Corsair RAM CMK8GX4M1A2400C14 8GB DIMM DDR4 2800MT/s      | 1        | 2.94%   |
| Corsair RAM CMK32GX4M4A2400C14 8GB DIMM DDR4 2666MT/s     | 1        | 2.94%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3600MT/s    | 1        | 2.94%   |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3100MT/s    | 1        | 2.94%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s     | 1        | 2.94%   |
| Corsair RAM CMG32GX4M2D3600C18 16GB DIMM DDR4 3600MT/s    | 1        | 2.94%   |
| Avant RAM W641GU42J5213NB 8GB DIMM DDR4 2133MT/s          | 1        | 2.94%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 30       | 90.91%  |
| DDR3 | 3        | 9.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 32       | 96.97%  |
| SODIMM | 1        | 3.03%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 17       | 51.52%  |
| 16384 | 10       | 30.3%   |
| 32768 | 3        | 9.09%   |
| 4096  | 3        | 9.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3600  | 9        | 27.27%  |
| 3200  | 7        | 21.21%  |
| 3466  | 3        | 9.09%   |
| 3000  | 2        | 6.06%   |
| 2400  | 2        | 6.06%   |
| 2133  | 2        | 6.06%   |
| 3266  | 1        | 3.03%   |
| 3100  | 1        | 3.03%   |
| 3067  | 1        | 3.03%   |
| 2800  | 1        | 3.03%   |
| 2667  | 1        | 3.03%   |
| 2666  | 1        | 3.03%   |
| 1600  | 1        | 3.03%   |
| 1333  | 1        | 3.03%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 3        | 23.08%  |
| Hewlett-Packard     | 3        | 23.08%  |
| Brother Industries  | 3        | 23.08%  |
| Seiko Epson         | 1        | 7.69%   |
| QinHeng Electronics | 1        | 7.69%   |
| Dymo-CoStar         | 1        | 7.69%   |
| Canon               | 1        | 7.69%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Seiko Epson WF-4830 Series             | 1        | 7.14%   |
| Samsung SCX-3400 Series                | 1        | 7.14%   |
| Samsung ML-191x/ML-252x Laser Printer  | 1        | 7.14%   |
| Samsung M2070 Series                   | 1        | 7.14%   |
| QinHeng CH340S                         | 1        | 7.14%   |
| HP PSC-1315/PSC-1317                   | 1        | 7.14%   |
| HP LaserJet P2035                      | 1        | 7.14%   |
| HP ENVY Pro 6400 series                | 1        | 7.14%   |
| Dymo-CoStar DYMO LabelWriter 4XL       | 1        | 7.14%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo | 1        | 7.14%   |
| Canon Pro9000II series                 | 1        | 7.14%   |
| Brother MFC-L2700DW                    | 1        | 7.14%   |
| Brother MFC-5440CN                     | 1        | 7.14%   |
| Brother HL-2130 series                 | 1        | 7.14%   |

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


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Canon CanoScan LiDE 60 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 19       | 39.58%  |
| Sunplus Innovation Technology | 4        | 8.33%   |
| Microdia                      | 4        | 8.33%   |
| Sunplus IT                    | 2        | 4.17%   |
| Samsung Electronics           | 2        | 4.17%   |
| Razer USA                     | 2        | 4.17%   |
| ARC International             | 2        | 4.17%   |
| XHT-210518                    | 1        | 2.08%   |
| WaveRider Communications      | 1        | 2.08%   |
| Valve Software                | 1        | 2.08%   |
| Realtek Semiconductor         | 1        | 2.08%   |
| MacroSilicon                  | 1        | 2.08%   |
| Jieli Technology              | 1        | 2.08%   |
| icSpring                      | 1        | 2.08%   |
| Hewlett-Packard               | 1        | 2.08%   |
| HD WEBCAM                     | 1        | 2.08%   |
| GenesysLogic Technology       | 1        | 2.08%   |
| Generalplus Technology        | 1        | 2.08%   |
| Creative Technology           | 1        | 2.08%   |
| Apple                         | 1        | 2.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech Webcam C270                    | 5        | 10.42%  |
| Logitech HD Pro Webcam C920             | 5        | 10.42%  |
| Sunplus IT AUKEY PC-LM1 USB Camera      | 2        | 4.17%   |
| Sunplus SPCA2281 Web Camera             | 2        | 4.17%   |
| Sunplus Full HD webcam                  | 2        | 4.17%   |
| Samsung Galaxy series, misc. (MTP mode) | 2        | 4.17%   |
| Razer USA Gaming Webcam [Kiyo]          | 2        | 4.17%   |
| Logitech C922 Pro Stream Webcam         | 2        | 4.17%   |
| ARC International Camera                | 2        | 4.17%   |
| XHT-210518 EC500X                       | 1        | 2.08%   |
| WaveRider USB 2.0 Camera                | 1        | 2.08%   |
| Valve Software 3D Camera                | 1        | 2.08%   |
| Realtek Thronmax StreamGo Webcam        | 1        | 2.08%   |
| Microdia Webcam Vitade AF               | 1        | 2.08%   |
| Microdia Rapoo camera                   | 1        | 2.08%   |
| Microdia Integrated Camera              | 1        | 2.08%   |
| Microdia AUKEY PC-W1                    | 1        | 2.08%   |
| MacroSilicon MiraBox Capture            | 1        | 2.08%   |
| Logitech Webcam Pro 9000                | 1        | 2.08%   |
| Logitech Webcam C925e                   | 1        | 2.08%   |
| Logitech HD Webcam C615                 | 1        | 2.08%   |
| Logitech HD Webcam C525                 | 1        | 2.08%   |
| Logitech HD Webcam C510                 | 1        | 2.08%   |
| Logitech CrystalCam                     | 1        | 2.08%   |
| Logitech C920 PRO HD Webcam             | 1        | 2.08%   |
| Jieli USB PHY 2.0                       | 1        | 2.08%   |
| icSpring camera                         | 1        | 2.08%   |
| HP USB Webcam                           | 1        | 2.08%   |
| HD WEBCAM Web Camera                    | 1        | 2.08%   |
| GenesysLogic USB2.0 UVC PC Camera       | 1        | 2.08%   |
| Generalplus 2K HD Camera                | 1        | 2.08%   |
| Creative Live! Cam Optia                | 1        | 2.08%   |
| Apple iPhone 5/5C/5S/6/SE               | 1        | 2.08%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| SCM Microsystems | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 171      | 85.07%  |
| 1     | 26       | 12.94%  |
| 2     | 3        | 1.49%   |
| 3     | 1        | 0.5%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 12       | 34.29%  |
| Graphics card            | 6        | 17.14%  |
| Bluetooth                | 5        | 14.29%  |
| Unassigned class         | 3        | 8.57%   |
| Multimedia controller    | 2        | 5.71%   |
| Communication controller | 2        | 5.71%   |
| Storage/ide              | 1        | 2.86%   |
| Sound                    | 1        | 2.86%   |
| Network                  | 1        | 2.86%   |
| Net/ethernet             | 1        | 2.86%   |
| Chipcard                 | 1        | 2.86%   |

