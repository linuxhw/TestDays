Nobara - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for Nobara.

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

Total: 179

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| HP        | 8054                        | [36f5306e37](https://linux-hardware.org/?probe=36f5306e37) | Jan 30, 2023 |
| Gigabyte  | F2A88XM-D3H                 | [1605fbe62a](https://linux-hardware.org/?probe=1605fbe62a) | Jan 28, 2023 |
| ASUSTek   | ROG Maximus XI HERO         | [95f5d0904e](https://linux-hardware.org/?probe=95f5d0904e) | Jan 26, 2023 |
| MSI       | MAG B550 TOMAHAWK           | [c69db4d96f](https://linux-hardware.org/?probe=c69db4d96f) | Jan 24, 2023 |
| MSI       | B450 GAMING PLUS            | [bc95b86800](https://linux-hardware.org/?probe=bc95b86800) | Jan 22, 2023 |
| Gigabyte  | Z77-D3H                     | [9035a00600](https://linux-hardware.org/?probe=9035a00600) | Jan 22, 2023 |
| MSI       | MPG X570 GAMING PLUS        | [3eb7e4f3cf](https://linux-hardware.org/?probe=3eb7e4f3cf) | Jan 22, 2023 |
| MSI       | MPG Z390M GAMING EDGE AC    | [085d30a350](https://linux-hardware.org/?probe=085d30a350) | Jan 21, 2023 |
| MSI       | Z490-A PRO                  | [0a3fe4cb00](https://linux-hardware.org/?probe=0a3fe4cb00) | Jan 21, 2023 |
| ASUSTek   | ROG STRIX Z490-F GAMING     | [9a70fa222c](https://linux-hardware.org/?probe=9a70fa222c) | Jan 19, 2023 |
| Gigabyte  | B450 AORUS M                | [4d52b408c2](https://linux-hardware.org/?probe=4d52b408c2) | Jan 19, 2023 |
| MSI       | GF615M-P33                  | [bf838ee958](https://linux-hardware.org/?probe=bf838ee958) | Jan 18, 2023 |
| ASUSTek   | PRIME Z370-A                | [f215410f54](https://linux-hardware.org/?probe=f215410f54) | Jan 17, 2023 |
| ASUSTek   | Z97-A                       | [c1b01960be](https://linux-hardware.org/?probe=c1b01960be) | Jan 17, 2023 |
| ASRock    | B450 Gaming-ITX/ac          | [aade436557](https://linux-hardware.org/?probe=aade436557) | Jan 14, 2023 |
| ASUSTek   | ROG STRIX B650E-I GAMING... | [5b50555e06](https://linux-hardware.org/?probe=5b50555e06) | Jan 13, 2023 |
| ASUSTek   | P9X79 DELUXE                | [d73373e8e9](https://linux-hardware.org/?probe=d73373e8e9) | Jan 13, 2023 |
| ASUSTek   | TUF Gaming X570-PLUS        | [73da880450](https://linux-hardware.org/?probe=73da880450) | Jan 12, 2023 |
| HP        | 8054                        | [d4398dee29](https://linux-hardware.org/?probe=d4398dee29) | Jan 08, 2023 |
| MSI       | MAG B560M MORTAR WIFI       | [33f6781ba8](https://linux-hardware.org/?probe=33f6781ba8) | Jan 08, 2023 |
| ASUSTek   | ROG CROSSHAIR VIII HERO     | [c74a6daaaa](https://linux-hardware.org/?probe=c74a6daaaa) | Jan 07, 2023 |
| ASRock    | X470 Master SLI             | [c138f9159c](https://linux-hardware.org/?probe=c138f9159c) | Jan 07, 2023 |
| HP        | 1497                        | [71550a0f21](https://linux-hardware.org/?probe=71550a0f21) | Jan 07, 2023 |
| ASRock    | H77M-ITX                    | [fb6cbfce9a](https://linux-hardware.org/?probe=fb6cbfce9a) | Jan 06, 2023 |
| MSI       | B450 GAMING PLUS MAX        | [406b407b64](https://linux-hardware.org/?probe=406b407b64) | Jan 06, 2023 |
| ASUSTek   | PRIME B450M-A               | [61b7c0cda0](https://linux-hardware.org/?probe=61b7c0cda0) | Jan 06, 2023 |
| ASUSTek   | ROG STRIX B450-F GAMING     | [569f5cd751](https://linux-hardware.org/?probe=569f5cd751) | Jan 06, 2023 |
| Gigabyte  | B550M DS3H                  | [3978c4253f](https://linux-hardware.org/?probe=3978c4253f) | Jan 06, 2023 |
| ASUSTek   | G20AJ                       | [9be7e0b11f](https://linux-hardware.org/?probe=9be7e0b11f) | Jan 05, 2023 |
| ASUSTek   | TUF Gaming B550M-PLUS       | [b6bf9d074f](https://linux-hardware.org/?probe=b6bf9d074f) | Jan 05, 2023 |
| ASUSTek   | PRIME B550M-K               | [11d17c68b8](https://linux-hardware.org/?probe=11d17c68b8) | Jan 05, 2023 |
| MSI       | X470 GAMING PLUS MAX        | [7655f77ada](https://linux-hardware.org/?probe=7655f77ada) | Jan 04, 2023 |
| ASUSTek   | ROG CROSSHAIR VII HERO      | [6c40dc7dd6](https://linux-hardware.org/?probe=6c40dc7dd6) | Jan 03, 2023 |
| ASUSTek   | M5A88-M                     | [dc7201711c](https://linux-hardware.org/?probe=dc7201711c) | Dec 30, 2022 |
| ASUSTek   | ROG CROSSHAIR VII HERO      | [4ca2070d42](https://linux-hardware.org/?probe=4ca2070d42) | Dec 29, 2022 |
| ASUSTek   | PRIME Z270-P                | [b9e4ff3fea](https://linux-hardware.org/?probe=b9e4ff3fea) | Dec 25, 2022 |
| HP        | 1589                        | [4769414712](https://linux-hardware.org/?probe=4769414712) | Dec 24, 2022 |
| MSI       | MAG B550 TOMAHAWK           | [353cbeb5c8](https://linux-hardware.org/?probe=353cbeb5c8) | Dec 19, 2022 |
| Biostar   | X470GTN                     | [7c067277b2](https://linux-hardware.org/?probe=7c067277b2) | Dec 17, 2022 |
| ASUSTek   | M5A88-M                     | [3bc811ef2a](https://linux-hardware.org/?probe=3bc811ef2a) | Dec 17, 2022 |
| HP        | 2ABD A01                    | [c5c5c07485](https://linux-hardware.org/?probe=c5c5c07485) | Dec 16, 2022 |
| HP        | 2ABD A01                    | [c992b15fbe](https://linux-hardware.org/?probe=c992b15fbe) | Dec 16, 2022 |
| ASUSTek   | M5A97 LE R2.0               | [fc8f4624a4](https://linux-hardware.org/?probe=fc8f4624a4) | Dec 16, 2022 |
| ASRock    | H310M-HDV/M.2               | [76dff63f5c](https://linux-hardware.org/?probe=76dff63f5c) | Dec 15, 2022 |
| ASUSTek   | M5A88-M                     | [4378eff64f](https://linux-hardware.org/?probe=4378eff64f) | Dec 13, 2022 |
| MSI       | MAG B660 TOMAHAWK WIFI      | [1beb5ff3c4](https://linux-hardware.org/?probe=1beb5ff3c4) | Dec 13, 2022 |
| ASUSTek   | ROG STRIX B660-F GAMING ... | [3f57fa2c71](https://linux-hardware.org/?probe=3f57fa2c71) | Dec 12, 2022 |
| Gigabyte  | H81M-H                      | [02ba14a443](https://linux-hardware.org/?probe=02ba14a443) | Dec 09, 2022 |
| Dell      | 0215PR A02                  | [b9d16b98d2](https://linux-hardware.org/?probe=b9d16b98d2) | Dec 09, 2022 |
| Gigabyte  | Z590I VISION D              | [9cc2be8747](https://linux-hardware.org/?probe=9cc2be8747) | Dec 09, 2022 |
| MSI       | GF615M-P33                  | [af4d483414](https://linux-hardware.org/?probe=af4d483414) | Dec 08, 2022 |
| ASUSTek   | M5A88-M                     | [d7b2726838](https://linux-hardware.org/?probe=d7b2726838) | Dec 08, 2022 |
| ASUSTek   | STRIX Z270H GAMING          | [c9cc6de1c4](https://linux-hardware.org/?probe=c9cc6de1c4) | Dec 08, 2022 |
| ASUSTek   | STRIX Z270H GAMING          | [8973296b3b](https://linux-hardware.org/?probe=8973296b3b) | Dec 08, 2022 |
| ASUSTek   | M5A88-M                     | [f5bd8a0e5b](https://linux-hardware.org/?probe=f5bd8a0e5b) | Dec 07, 2022 |
| MSI       | MAG B550 TOMAHAWK           | [a742429421](https://linux-hardware.org/?probe=a742429421) | Dec 06, 2022 |
| ASUSTek   | M5A88-M                     | [69ed3a0345](https://linux-hardware.org/?probe=69ed3a0345) | Dec 02, 2022 |
| MSI       | MAG B550 TOMAHAWK MAX WI... | [1775ec9d4b](https://linux-hardware.org/?probe=1775ec9d4b) | Dec 01, 2022 |
| MSI       | MAG B550 TOMAHAWK MAX WI... | [097d1c062e](https://linux-hardware.org/?probe=097d1c062e) | Dec 01, 2022 |
| Gigabyte  | Z590I VISION D              | [655e907d62](https://linux-hardware.org/?probe=655e907d62) | Dec 01, 2022 |
| Intel     | X79G V2.x                   | [6b229554fc](https://linux-hardware.org/?probe=6b229554fc) | Nov 28, 2022 |
| Gigabyte  | H410M H V3                  | [afea73cc2a](https://linux-hardware.org/?probe=afea73cc2a) | Nov 22, 2022 |
| ASUSTek   | TUF Gaming B550M-PLUS WI... | [56c9fb93ce](https://linux-hardware.org/?probe=56c9fb93ce) | Nov 22, 2022 |
| ASUSTek   | TUF Gaming B550M-PLUS WI... | [1ec2520541](https://linux-hardware.org/?probe=1ec2520541) | Nov 22, 2022 |
| ASUSTek   | ROG STRIX X570-F GAMING     | [0fd2d81cad](https://linux-hardware.org/?probe=0fd2d81cad) | Nov 22, 2022 |
| OEM       | SHARKBAY JHS695             | [03c915bbd9](https://linux-hardware.org/?probe=03c915bbd9) | Nov 22, 2022 |
| MSI       | GF615M-P33                  | [7a6be335c4](https://linux-hardware.org/?probe=7a6be335c4) | Nov 22, 2022 |
| ASRock    | B550 Extreme4               | [7fba8e38dc](https://linux-hardware.org/?probe=7fba8e38dc) | Nov 20, 2022 |
| Gigabyte  | H310M M.2 x.x               | [87406f0722](https://linux-hardware.org/?probe=87406f0722) | Nov 19, 2022 |
| Alienware | 0PGRP5 A01                  | [2ff9360669](https://linux-hardware.org/?probe=2ff9360669) | Nov 17, 2022 |
| MSI       | MEG X570 UNIFY              | [750d7eb0d7](https://linux-hardware.org/?probe=750d7eb0d7) | Nov 16, 2022 |
| ASUSTek   | ROG STRIX Z390-H GAMING     | [4d4d5aa456](https://linux-hardware.org/?probe=4d4d5aa456) | Nov 15, 2022 |
| Fujitsu   | D3062-A1 S26361-D3062-A1    | [d4240ae5c7](https://linux-hardware.org/?probe=d4240ae5c7) | Nov 12, 2022 |
| MSI       | MPG X570S EDGE MAX WIFI     | [51d6598b74](https://linux-hardware.org/?probe=51d6598b74) | Nov 11, 2022 |
| ASUSTek   | A68HM-K                     | [70daf967f2](https://linux-hardware.org/?probe=70daf967f2) | Nov 10, 2022 |
| Gigabyte  | 990FXA-UD3                  | [a49a1465d3](https://linux-hardware.org/?probe=a49a1465d3) | Nov 10, 2022 |
| ASRock    | N68C-GS4 FX                 | [5e151ea22f](https://linux-hardware.org/?probe=5e151ea22f) | Nov 07, 2022 |
| Intel     | D33217GKE G76540-207        | [f90e6e931c](https://linux-hardware.org/?probe=f90e6e931c) | Nov 07, 2022 |
| Intel     | D33217GKE G76540-207        | [a154fd19a0](https://linux-hardware.org/?probe=a154fd19a0) | Nov 07, 2022 |
| ASUSTek   | TUF Gaming Z490-PLUS        | [4239b9f4a9](https://linux-hardware.org/?probe=4239b9f4a9) | Nov 06, 2022 |
| MSI       | MPG Z390 GAMING PRO CARB... | [05529fe361](https://linux-hardware.org/?probe=05529fe361) | Nov 06, 2022 |
| Dell      | 042P49 A02                  | [55d7ddf0c8](https://linux-hardware.org/?probe=55d7ddf0c8) | Nov 06, 2022 |
| MSI       | MPG Z390 GAMING PRO CARB... | [677dcff84a](https://linux-hardware.org/?probe=677dcff84a) | Nov 06, 2022 |
| MSI       | MPG X570S EDGE MAX WIFI     | [049bac8501](https://linux-hardware.org/?probe=049bac8501) | Nov 06, 2022 |
| ASUSTek   | M5A97 R2.0                  | [5ca257fd77](https://linux-hardware.org/?probe=5ca257fd77) | Nov 06, 2022 |
| MSI       | B450 TOMAHAWK MAX II        | [bd9e0be4e8](https://linux-hardware.org/?probe=bd9e0be4e8) | Nov 03, 2022 |
| ECS       | H61H2-CM                    | [792ce0e34e](https://linux-hardware.org/?probe=792ce0e34e) | Oct 31, 2022 |
| ASRock    | Z77 Pro4                    | [5ab5790e5f](https://linux-hardware.org/?probe=5ab5790e5f) | Oct 29, 2022 |
| ASRock    | Z77 Pro4                    | [74cc7f147b](https://linux-hardware.org/?probe=74cc7f147b) | Oct 29, 2022 |
| HP        | 8653 A                      | [bc1f3b445b](https://linux-hardware.org/?probe=bc1f3b445b) | Oct 28, 2022 |
| ASRock    | X570 Taichi                 | [967f52e510](https://linux-hardware.org/?probe=967f52e510) | Oct 28, 2022 |
| Dell      | 09KPNV A00                  | [c25493f420](https://linux-hardware.org/?probe=c25493f420) | Oct 27, 2022 |
| Gigabyte  | 970A-DS3P                   | [7e31b6af67](https://linux-hardware.org/?probe=7e31b6af67) | Oct 27, 2022 |
| Gigabyte  | 970A-DS3P                   | [6823943242](https://linux-hardware.org/?probe=6823943242) | Oct 27, 2022 |
| Intel     | B75                         | [eb7c27f1e5](https://linux-hardware.org/?probe=eb7c27f1e5) | Oct 26, 2022 |
| HP        | 3029h                       | [c278953154](https://linux-hardware.org/?probe=c278953154) | Oct 25, 2022 |
| Gigabyte  | Z590I VISION D              | [be4c6573cd](https://linux-hardware.org/?probe=be4c6573cd) | Oct 25, 2022 |
| ASUSTek   | PRIME A320M-K               | [c0b3f0d88e](https://linux-hardware.org/?probe=c0b3f0d88e) | Oct 24, 2022 |
| ASUSTek   | ROG STRIX Z390-E GAMING     | [7e40be1c82](https://linux-hardware.org/?probe=7e40be1c82) | Oct 23, 2022 |
| Gigabyte  | Z97-HD3                     | [f79eb0cbb0](https://linux-hardware.org/?probe=f79eb0cbb0) | Oct 23, 2022 |
| ASUSTek   | TUF Gaming X570-PRO WIFI... | [c3b1784ecc](https://linux-hardware.org/?probe=c3b1784ecc) | Oct 21, 2022 |
| Gigabyte  | B450M DS3H-CF               | [c901f6927c](https://linux-hardware.org/?probe=c901f6927c) | Oct 18, 2022 |
| MSI       | MPG Z390 GAMING PLUS        | [624be3f0f3](https://linux-hardware.org/?probe=624be3f0f3) | Oct 17, 2022 |
| ASUSTek   | TUF Gaming B450M-PLUS II    | [cb63aa5619](https://linux-hardware.org/?probe=cb63aa5619) | Oct 17, 2022 |
| MSI       | MPG Z390 GAMING PRO CARB... | [a4919afa07](https://linux-hardware.org/?probe=a4919afa07) | Oct 16, 2022 |
| MSI       | Z87 XPOWER                  | [5e73f5004a](https://linux-hardware.org/?probe=5e73f5004a) | Oct 13, 2022 |
| ASUSTek   | PRIME X370-PRO              | [0a89e9b77e](https://linux-hardware.org/?probe=0a89e9b77e) | Oct 13, 2022 |
| MSI       | MPG Z390 GAMING PRO CARB... | [a920c57a3e](https://linux-hardware.org/?probe=a920c57a3e) | Oct 11, 2022 |
| Dell      | 0F6X5P A00                  | [49baafbc65](https://linux-hardware.org/?probe=49baafbc65) | Oct 10, 2022 |
| MSI       | PRO Z690-A DDR4             | [2a1088b211](https://linux-hardware.org/?probe=2a1088b211) | Oct 08, 2022 |
| ASUSTek   | SABERTOOTH 990FX R2.0       | [05dfea29df](https://linux-hardware.org/?probe=05dfea29df) | Oct 07, 2022 |
| ASUSTek   | SABERTOOTH 990FX R2.0       | [24471f06da](https://linux-hardware.org/?probe=24471f06da) | Oct 07, 2022 |
| Gigabyte  | X570 I AORUS PRO WIFI       | [cc955e89b7](https://linux-hardware.org/?probe=cc955e89b7) | Oct 07, 2022 |
| HP        | 1998                        | [f2b9957fdd](https://linux-hardware.org/?probe=f2b9957fdd) | Oct 06, 2022 |
| MSI       | B450-A PRO MAX              | [b161553abb](https://linux-hardware.org/?probe=b161553abb) | Oct 05, 2022 |
| ASRock    | B450M Steel Legend          | [4f4352de45](https://linux-hardware.org/?probe=4f4352de45) | Oct 04, 2022 |
| ASUSTek   | H61M-K                      | [e0408b49e7](https://linux-hardware.org/?probe=e0408b49e7) | Oct 02, 2022 |
| MSI       | B350 PC MATE                | [a4c73b484e](https://linux-hardware.org/?probe=a4c73b484e) | Oct 02, 2022 |
| Dell      | 0M5DCD A00                  | [3cc1e139dc](https://linux-hardware.org/?probe=3cc1e139dc) | Oct 02, 2022 |
| MSI       | MEG X570 UNIFY              | [4d2e449699](https://linux-hardware.org/?probe=4d2e449699) | Sep 30, 2022 |
| ASRock    | X470 Master SLI             | [47c190b6e9](https://linux-hardware.org/?probe=47c190b6e9) | Sep 30, 2022 |
| Gigabyte  | H270-Gaming 3               | [9426d21070](https://linux-hardware.org/?probe=9426d21070) | Sep 29, 2022 |
| Gigabyte  | H270-Gaming 3               | [830af9c53e](https://linux-hardware.org/?probe=830af9c53e) | Sep 29, 2022 |
| Gigabyte  | AB350-Gaming 3-CF           | [365d74f8e4](https://linux-hardware.org/?probe=365d74f8e4) | Sep 28, 2022 |
| Intel     | B75                         | [af5aef869c](https://linux-hardware.org/?probe=af5aef869c) | Sep 28, 2022 |
| Gigabyte  | AB350-Gaming 3-CF           | [cfd24b9e0a](https://linux-hardware.org/?probe=cfd24b9e0a) | Sep 27, 2022 |
| MSI       | MAG X570 TOMAHAWK WIFI      | [6bfc8d43ef](https://linux-hardware.org/?probe=6bfc8d43ef) | Sep 27, 2022 |
| MSI       | A68HM-E33 V2                | [d51c90a7a8](https://linux-hardware.org/?probe=d51c90a7a8) | Sep 27, 2022 |
| ASUSTek   | 970 PRO GAMING/AURA         | [f61a736922](https://linux-hardware.org/?probe=f61a736922) | Sep 26, 2022 |
| ASUSTek   | 970 PRO GAMING/AURA         | [1ecfe379e7](https://linux-hardware.org/?probe=1ecfe379e7) | Sep 26, 2022 |
| ASUSTek   | PRIME H410M-A               | [dafae8d45b](https://linux-hardware.org/?probe=dafae8d45b) | Sep 26, 2022 |
| MSI       | 970 GAMING                  | [015cd37f26](https://linux-hardware.org/?probe=015cd37f26) | Sep 24, 2022 |
| Dell      | 0G785M A00                  | [c461ec42d6](https://linux-hardware.org/?probe=c461ec42d6) | Sep 24, 2022 |
| ASUSTek   | PRIME A320M-K               | [d72e6b3865](https://linux-hardware.org/?probe=d72e6b3865) | Sep 23, 2022 |
| Gigabyte  | EP45-UD3L                   | [71c630ea03](https://linux-hardware.org/?probe=71c630ea03) | Sep 22, 2022 |
| ASUSTek   | PRIME H310M-E R2.0          | [7299d75966](https://linux-hardware.org/?probe=7299d75966) | Sep 22, 2022 |
| HP        | 8594                        | [281774ad4a](https://linux-hardware.org/?probe=281774ad4a) | Sep 21, 2022 |
| Gigabyte  | EP45-UD3L                   | [2b90168b71](https://linux-hardware.org/?probe=2b90168b71) | Sep 21, 2022 |
| ASRock    | X470 Master SLI             | [3c8fefe578](https://linux-hardware.org/?probe=3c8fefe578) | Sep 20, 2022 |
| ASRock    | X470 Master SLI             | [1975320cad](https://linux-hardware.org/?probe=1975320cad) | Sep 20, 2022 |
| Dell      | 0G785M A00                  | [8b8c41b401](https://linux-hardware.org/?probe=8b8c41b401) | Sep 19, 2022 |
| Unknown   | T3 MRD                      | [1f60a4d202](https://linux-hardware.org/?probe=1f60a4d202) | Sep 19, 2022 |
| MSI       | X570-A PRO                  | [cabf88c8be](https://linux-hardware.org/?probe=cabf88c8be) | Sep 19, 2022 |
| Gigabyte  | A320M-S2H-CF                | [7b95813c96](https://linux-hardware.org/?probe=7b95813c96) | Sep 18, 2022 |
| Unknown   | T3 MRD                      | [b10823b50f](https://linux-hardware.org/?probe=b10823b50f) | Sep 17, 2022 |
| Biostar   | H410MH S2                   | [832dd81851](https://linux-hardware.org/?probe=832dd81851) | Sep 17, 2022 |
| Lenovo    | MAHOBAY NOK                 | [cce010fd53](https://linux-hardware.org/?probe=cce010fd53) | Sep 16, 2022 |
| ASUSTek   | TUF Gaming B550M-PLUS WI... | [d9e9ec9afa](https://linux-hardware.org/?probe=d9e9ec9afa) | Sep 09, 2022 |
| ASUSTek   | TUF Gaming B550M-PLUS WI... | [1cdd7cda15](https://linux-hardware.org/?probe=1cdd7cda15) | Sep 09, 2022 |
| ASUSTek   | TUF Gaming X570-PRO         | [6eae76b5d0](https://linux-hardware.org/?probe=6eae76b5d0) | Sep 01, 2022 |
| ASRock    | FM2A55M-HD+                 | [2f96c73efb](https://linux-hardware.org/?probe=2f96c73efb) | Sep 01, 2022 |
| Gigabyte  | H110M-H-CF                  | [86fc2bf58f](https://linux-hardware.org/?probe=86fc2bf58f) | Aug 31, 2022 |
| Alienware | 01NYPT A00                  | [cd95b79270](https://linux-hardware.org/?probe=cd95b79270) | Aug 29, 2022 |
| ASRock    | B560 Steel Legend           | [c64907de8d](https://linux-hardware.org/?probe=c64907de8d) | Aug 27, 2022 |
| ASUSTek   | P8Z68-V PRO                 | [37ae937f4d](https://linux-hardware.org/?probe=37ae937f4d) | Aug 26, 2022 |
| ASUSTek   | PRIME X570-PRO              | [663509c999](https://linux-hardware.org/?probe=663509c999) | Aug 24, 2022 |
| ASUSTek   | PRIME X570-PRO              | [2b7d1d59a1](https://linux-hardware.org/?probe=2b7d1d59a1) | Aug 24, 2022 |
| ASUSTek   | PRIME A320M-K               | [928ce75df1](https://linux-hardware.org/?probe=928ce75df1) | Aug 24, 2022 |
| ASRock    | H61M-VG3                    | [a3cd7ba2c1](https://linux-hardware.org/?probe=a3cd7ba2c1) | Aug 22, 2022 |
| ASUSTek   | B85M-E                      | [0b5044dacf](https://linux-hardware.org/?probe=0b5044dacf) | Aug 19, 2022 |
| Gigabyte  | B450M DS3H-CF               | [a2b6c2ae17](https://linux-hardware.org/?probe=a2b6c2ae17) | Aug 19, 2022 |
| ASRock    | X470 Master SLI             | [ce62975b20](https://linux-hardware.org/?probe=ce62975b20) | Aug 15, 2022 |
| ASUSTek   | PRIME B350-PLUS             | [b2bbce2845](https://linux-hardware.org/?probe=b2bbce2845) | Aug 15, 2022 |
| ASRock    | Z97 Extreme6                | [31d7973a9d](https://linux-hardware.org/?probe=31d7973a9d) | Aug 14, 2022 |
| ASRock    | 760GM-HDV                   | [beabb7dd99](https://linux-hardware.org/?probe=beabb7dd99) | Aug 14, 2022 |
| MSI       | B450 TOMAHAWK MAX           | [27cd96982f](https://linux-hardware.org/?probe=27cd96982f) | Aug 10, 2022 |
| HP        | 8906 SMVB                   | [8f30392f49](https://linux-hardware.org/?probe=8f30392f49) | Aug 10, 2022 |
| HP        | 8054                        | [469b765fe0](https://linux-hardware.org/?probe=469b765fe0) | Aug 10, 2022 |
| ASUSTek   | G20AJ                       | [613f8a0c36](https://linux-hardware.org/?probe=613f8a0c36) | Aug 08, 2022 |
| Gigabyte  | X570 AORUS ELITE            | [f65ba77de3](https://linux-hardware.org/?probe=f65ba77de3) | Aug 07, 2022 |
| ASUSTek   | ROG CROSSHAIR VIII HERO     | [7a60eede9a](https://linux-hardware.org/?probe=7a60eede9a) | Aug 04, 2022 |
| MSI       | B450-A PRO MAX              | [e142cf5c91](https://linux-hardware.org/?probe=e142cf5c91) | Aug 04, 2022 |
| MSI       | B450 TOMAHAWK MAX           | [7c4355417f](https://linux-hardware.org/?probe=7c4355417f) | Aug 03, 2022 |
| MSI       | X570-A PRO                  | [f034a02e69](https://linux-hardware.org/?probe=f034a02e69) | Aug 01, 2022 |
| MSI       | 970 GAMING                  | [bf2a870952](https://linux-hardware.org/?probe=bf2a870952) | Jul 23, 2022 |
| Dell      | 0J8H4R A01                  | [3d7d06475c](https://linux-hardware.org/?probe=3d7d06475c) | Jul 23, 2022 |
| ASUSTek   | PRIME B450-PLUS             | [7d6b6d93d3](https://linux-hardware.org/?probe=7d6b6d93d3) | Jul 21, 2022 |
| eMachines | EL1870                      | [58e76fb684](https://linux-hardware.org/?probe=58e76fb684) | Jul 19, 2022 |
| MSI       | X570-A PRO                  | [c9683ea265](https://linux-hardware.org/?probe=c9683ea265) | Jul 19, 2022 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| Nobara 36 | 122      | 87.77%  |
| Nobara 37 | 17       | 12.23%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Nobara | 137      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                       | Desktops | Percent |
|-------------------------------|----------|---------|
| 6.0.14-201.fsync.fc36.x86_64  | 15       | 10.27%  |
| 6.0.10-201.fc36.x86_64        | 15       | 10.27%  |
| 5.19.9-201.fsync.fc36.x86_64  | 8        | 5.48%   |
| 5.19.16-201.fsync.fc36.x86_64 | 8        | 5.48%   |
| 5.19.14-201.fsync.fc36.x86_64 | 8        | 5.48%   |
| 5.19.7-204.fsync.fc36.x86_64  | 7        | 4.79%   |
| 5.18.13-201.fsync.fc36.x86_64 | 7        | 4.79%   |
| 6.0.9-201.fc36.x86_64         | 6        | 4.11%   |
| 6.0.7-201.fsync.fc36.x86_64   | 6        | 4.11%   |
| 6.0.5-201.fsync.fc36.x86_64   | 6        | 4.11%   |
| 5.19.10-201.fsync.fc36.x86_64 | 6        | 4.11%   |
| 6.1.6-203.fsync.fc37.x86_64   | 5        | 3.42%   |
| 6.1.4-203.fsync.fc37.x86_64   | 4        | 2.74%   |
| 5.19.4-201.fsync.fc36.x86_64  | 4        | 2.74%   |
| 5.19.15-202.fsync.fc36.x86_64 | 4        | 2.74%   |
| 5.18.17-201.fsync.fc36.x86_64 | 4        | 2.74%   |
| 5.18.16-201.fsync.fc36.x86_64 | 4        | 2.74%   |
| 6.0.16-301.fsync.fc37.x86_64  | 3        | 2.05%   |
| 5.19.12-201.fsync.fc36.x86_64 | 3        | 2.05%   |
| 5.18.19-201.fsync.fc36.x86_64 | 3        | 2.05%   |
| 5.18.11-201.fsync.fc36.x86_64 | 3        | 2.05%   |
| 6.1.6-201.fsync.fc37.x86_64   | 2        | 1.37%   |
| 6.0.8-201.fsync.fc36.x86_64   | 2        | 1.37%   |
| 6.0.7-202.fsync.fc36.x86_64   | 2        | 1.37%   |
| 6.0.18-301.fsync.fc37.x86_64  | 2        | 1.37%   |
| 5.19.11-201.fsync.fc36.x86_64 | 2        | 1.37%   |
| 6.0.15-301.fsync.fc37.x86_64  | 1        | 0.68%   |
| 5.19.7-203.fsync.fc36.x86_64  | 1        | 0.68%   |
| 5.19.2-602.inttf.fc36.x86_64  | 1        | 0.68%   |
| 5.19.13-202.fsync.fc36.x86_64 | 1        | 0.68%   |
| 5.19.13-201.fsync.fc36.x86_64 | 1        | 0.68%   |
| 5.18.9-201.fsync.fc36.x86_64  | 1        | 0.68%   |
| 5.18.18-201.fsync.fc36.x86_64 | 1        | 0.68%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.0.14  | 15       | 10.27%  |
| 6.0.10  | 15       | 10.27%  |
| 6.0.7   | 8        | 5.48%   |
| 5.19.9  | 8        | 5.48%   |
| 5.19.7  | 8        | 5.48%   |
| 5.19.16 | 8        | 5.48%   |
| 5.19.14 | 8        | 5.48%   |
| 6.1.6   | 7        | 4.79%   |
| 5.18.13 | 7        | 4.79%   |
| 6.0.9   | 6        | 4.11%   |
| 6.0.5   | 6        | 4.11%   |
| 5.19.10 | 6        | 4.11%   |
| 6.1.4   | 4        | 2.74%   |
| 5.19.4  | 4        | 2.74%   |
| 5.19.15 | 4        | 2.74%   |
| 5.18.17 | 4        | 2.74%   |
| 5.18.16 | 4        | 2.74%   |
| 6.0.16  | 3        | 2.05%   |
| 5.19.12 | 3        | 2.05%   |
| 5.18.19 | 3        | 2.05%   |
| 5.18.11 | 3        | 2.05%   |
| 6.0.8   | 2        | 1.37%   |
| 6.0.18  | 2        | 1.37%   |
| 5.19.13 | 2        | 1.37%   |
| 5.19.11 | 2        | 1.37%   |
| 6.0.15  | 1        | 0.68%   |
| 5.19.2  | 1        | 0.68%   |
| 5.18.9  | 1        | 0.68%   |
| 5.18.18 | 1        | 0.68%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.0     | 56       | 38.89%  |
| 5.19    | 54       | 37.5%   |
| 5.18    | 23       | 15.97%  |
| 6.1     | 11       | 7.64%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 137      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 105      | 76.64%  |
| KDE5          | 29       | 21.17%  |
| GNOME Classic | 2        | 1.46%   |
| X-Cinnamon    | 1        | 0.73%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 104      | 73.76%  |
| X11     | 37       | 26.24%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 120      | 87.59%  |
| GDM     | 12       | 8.76%   |
| SDDM    | 4        | 2.92%   |
| LightDM | 1        | 0.73%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 74       | 53.62%  |
| en_GB   | 11       | 7.97%   |
| en_CA   | 6        | 4.35%   |
| es_MX   | 5        | 3.62%   |
| es_AR   | 5        | 3.62%   |
| de_DE   | 5        | 3.62%   |
| fr_FR   | 4        | 2.9%    |
| es_ES   | 4        | 2.9%    |
| ru_RU   | 3        | 2.17%   |
| pt_BR   | 2        | 1.45%   |
| nl_NL   | 2        | 1.45%   |
| es_CO   | 2        | 1.45%   |
| en_AU   | 2        | 1.45%   |
| de_AT   | 2        | 1.45%   |
| sv_SE   | 1        | 0.72%   |
| sk_SK   | 1        | 0.72%   |
| pl_PL   | 1        | 0.72%   |
| fi_FI   | 1        | 0.72%   |
| es_GT   | 1        | 0.72%   |
| es_EC   | 1        | 0.72%   |
| en_PH   | 1        | 0.72%   |
| en_NZ   | 1        | 0.72%   |
| cs_CZ   | 1        | 0.72%   |
| C       | 1        | 0.72%   |
| Unknown | 1        | 0.72%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 100      | 72.99%  |
| BIOS | 37       | 27.01%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Btrfs | 81       | 58.7%   |
| Ext4  | 56       | 40.58%  |
| Xfs   | 1        | 0.72%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 119      | 86.86%  |
| GPT     | 15       | 10.95%  |
| MBR     | 3        | 2.19%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 131      | 95.62%  |
| Yes       | 6        | 4.38%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 129      | 94.16%  |
| Yes       | 8        | 5.84%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 44       | 32.12%  |
| MSI                 | 30       | 21.9%   |
| Gigabyte Technology | 21       | 15.33%  |
| ASRock              | 14       | 10.22%  |
| Hewlett-Packard     | 8        | 5.84%   |
| Dell                | 7        | 5.11%   |
| Intel               | 3        | 2.19%   |
| Biostar             | 2        | 1.46%   |
| Alienware           | 2        | 1.46%   |
| OEM                 | 1        | 0.73%   |
| Lenovo              | 1        | 0.73%   |
| Fujitsu             | 1        | 0.73%   |
| eMachines           | 1        | 0.73%   |
| ECS                 | 1        | 0.73%   |
| Unknown             | 1        | 0.73%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| MSI MS-7C91                          | 4        | 2.92%   |
| MSI MS-7B86                          | 4        | 2.92%   |
| MSI MS-7C37                          | 3        | 2.19%   |
| ASUS PRIME A320M-K                   | 3        | 2.19%   |
| MSI MS-7C02                          | 2        | 1.46%   |
| MSI MS-7693                          | 2        | 1.46%   |
| Gigabyte Z590I VISION D              | 2        | 1.46%   |
| Gigabyte B450M DS3H                  | 2        | 1.46%   |
| Dell OptiPlex 390                    | 2        | 1.46%   |
| ASUS ROG CROSSHAIR VIII HERO         | 2        | 1.46%   |
| OEM SHARKBAY                         | 1        | 0.73%   |
| MSI MS-7D53                          | 1        | 0.73%   |
| MSI MS-7D41                          | 1        | 0.73%   |
| MSI MS-7D25                          | 1        | 0.73%   |
| MSI MS-7D17                          | 1        | 0.73%   |
| MSI MS-7C84                          | 1        | 0.73%   |
| MSI MS-7C75                          | 1        | 0.73%   |
| MSI MS-7C35                          | 1        | 0.73%   |
| MSI MS-7B79                          | 1        | 0.73%   |
| MSI MS-7B51                          | 1        | 0.73%   |
| MSI MS-7B50                          | 1        | 0.73%   |
| MSI MS-7B17                          | 1        | 0.73%   |
| MSI MS-7A34                          | 1        | 0.73%   |
| MSI MS-7811                          | 1        | 0.73%   |
| MSI MS-7721                          | 1        | 0.73%   |
| MSI MS-7597                          | 1        | 0.73%   |
| Lenovo ThinkCentre M92p 3238E5U      | 1        | 0.73%   |
| Intel X79                            | 1        | 0.73%   |
| Intel D33217GKE G76540-207           | 1        | 0.73%   |
| Intel B75                            | 1        | 0.73%   |
| HP Z420 Workstation                  | 1        | 0.73%   |
| HP Pavilion Gaming Desktop TG01-0xxx | 1        | 0.73%   |
| HP Pavilion Desktop TP01-2xxx        | 1        | 0.73%   |
| HP EliteDesk 800 G5 Desktop Mini     | 1        | 0.73%   |
| HP EliteDesk 800 G2 SFF              | 1        | 0.73%   |
| HP EliteDesk 800 G1 SFF              | 1        | 0.73%   |
| HP Compaq dc5850 Small Form Factor   | 1        | 0.73%   |
| HP Compaq 6200 Pro SFF PC            | 1        | 0.73%   |
| Gigabyte Z97-HD3                     | 1        | 0.73%   |
| Gigabyte Z77-D3H                     | 1        | 0.73%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| ASUS PRIME         | 13       | 9.49%   |
| ASUS ROG           | 11       | 8.03%   |
| ASUS TUF           | 6        | 4.38%   |
| MSI MS-7C91        | 4        | 2.92%   |
| MSI MS-7B86        | 4        | 2.92%   |
| Dell OptiPlex      | 4        | 2.92%   |
| MSI MS-7C37        | 3        | 2.19%   |
| HP EliteDesk       | 3        | 2.19%   |
| MSI MS-7C02        | 2        | 1.46%   |
| MSI MS-7693        | 2        | 1.46%   |
| HP Pavilion        | 2        | 1.46%   |
| HP Compaq          | 2        | 1.46%   |
| Gigabyte Z590I     | 2        | 1.46%   |
| Gigabyte X570      | 2        | 1.46%   |
| Gigabyte B450M     | 2        | 1.46%   |
| Dell Precision     | 2        | 1.46%   |
| ASUS M5A97         | 2        | 1.46%   |
| OEM SHARKBAY       | 1        | 0.73%   |
| MSI MS-7D53        | 1        | 0.73%   |
| MSI MS-7D41        | 1        | 0.73%   |
| MSI MS-7D25        | 1        | 0.73%   |
| MSI MS-7D17        | 1        | 0.73%   |
| MSI MS-7C84        | 1        | 0.73%   |
| MSI MS-7C75        | 1        | 0.73%   |
| MSI MS-7C35        | 1        | 0.73%   |
| MSI MS-7B79        | 1        | 0.73%   |
| MSI MS-7B51        | 1        | 0.73%   |
| MSI MS-7B50        | 1        | 0.73%   |
| MSI MS-7B17        | 1        | 0.73%   |
| MSI MS-7A34        | 1        | 0.73%   |
| MSI MS-7811        | 1        | 0.73%   |
| MSI MS-7721        | 1        | 0.73%   |
| MSI MS-7597        | 1        | 0.73%   |
| Lenovo ThinkCentre | 1        | 0.73%   |
| Intel X79          | 1        | 0.73%   |
| Intel D33217GKE    | 1        | 0.73%   |
| Intel B75          | 1        | 0.73%   |
| HP Z420            | 1        | 0.73%   |
| Gigabyte Z97-HD3   | 1        | 0.73%   |
| Gigabyte Z77-D3H   | 1        | 0.73%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 27       | 19.71%  |
| 2018 | 16       | 11.68%  |
| 2020 | 14       | 10.22%  |
| 2021 | 13       | 9.49%   |
| 2013 | 13       | 9.49%   |
| 2017 | 10       | 7.3%    |
| 2014 | 9        | 6.57%   |
| 2011 | 9        | 6.57%   |
| 2012 | 8        | 5.84%   |
| 2022 | 6        | 4.38%   |
| 2016 | 5        | 3.65%   |
| 2015 | 3        | 2.19%   |
| 2008 | 2        | 1.46%   |
| 2010 | 1        | 0.73%   |
| 2009 | 1        | 0.73%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 137      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 137      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 137      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 55       | 40.15%  |
| 32.01-64.0  | 36       | 26.28%  |
| 8.01-16.0   | 20       | 14.6%   |
| 4.01-8.0    | 11       | 8.03%   |
| 3.01-4.0    | 7        | 5.11%   |
| 24.01-32.0  | 4        | 2.92%   |
| 64.01-256.0 | 4        | 2.92%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 68       | 47.55%  |
| 3.01-4.0   | 35       | 24.48%  |
| 8.01-16.0  | 19       | 13.29%  |
| 2.01-3.0   | 15       | 10.49%  |
| 1.01-2.0   | 3        | 2.1%    |
| 16.01-24.0 | 2        | 1.4%    |
| 24.01-32.0 | 1        | 0.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 3      | 38       | 27.34%  |
| 1      | 37       | 26.62%  |
| 2      | 34       | 24.46%  |
| 5      | 15       | 10.79%  |
| 4      | 11       | 7.91%   |
| 6      | 2        | 1.44%   |
| 10     | 1        | 0.72%   |
| 7      | 1        | 0.72%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 108      | 78.83%  |
| Yes       | 29       | 21.17%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 137      | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 73       | 53.28%  |
| No        | 64       | 46.72%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 71       | 51.45%  |
| Yes       | 67       | 48.55%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 43       | 31.39%  |
| UK           | 8        | 5.84%   |
| Canada       | 8        | 5.84%   |
| Germany      | 7        | 5.11%   |
| France       | 7        | 5.11%   |
| Argentina    | 7        | 5.11%   |
| Mexico       | 5        | 3.65%   |
| Spain        | 4        | 2.92%   |
| Sweden       | 3        | 2.19%   |
| Russia       | 3        | 2.19%   |
| Netherlands  | 3        | 2.19%   |
| Brazil       | 3        | 2.19%   |
| Serbia       | 2        | 1.46%   |
| Philippines  | 2        | 1.46%   |
| Hungary      | 2        | 1.46%   |
| Colombia     | 2        | 1.46%   |
| Chile        | 2        | 1.46%   |
| Austria      | 2        | 1.46%   |
| Australia    | 2        | 1.46%   |
| Venezuela    | 1        | 0.73%   |
| Ukraine      | 1        | 0.73%   |
| South Korea  | 1        | 0.73%   |
| South Africa | 1        | 0.73%   |
| Slovakia     | 1        | 0.73%   |
| Saudi Arabia | 1        | 0.73%   |
| Portugal     | 1        | 0.73%   |
| Poland       | 1        | 0.73%   |
| Norway       | 1        | 0.73%   |
| New Zealand  | 1        | 0.73%   |
| Lithuania    | 1        | 0.73%   |
| Kuwait       | 1        | 0.73%   |
| Jordan       | 1        | 0.73%   |
| Italy        | 1        | 0.73%   |
| Indonesia    | 1        | 0.73%   |
| Guatemala    | 1        | 0.73%   |
| Georgia      | 1        | 0.73%   |
| Finland      | 1        | 0.73%   |
| Ecuador      | 1        | 0.73%   |
| Czechia      | 1        | 0.73%   |
| Croatia      | 1        | 0.73%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Buenos Aires      | 3        | 2.1%    |
| Philadelphia      | 2        | 1.4%    |
| Guadalajara       | 2        | 1.4%    |
| Atlanta           | 2        | 1.4%    |
| Zagreb            | 1        | 0.7%    |
| Wooster           | 1        | 0.7%    |
| Wiesbaden         | 1        | 0.7%    |
| Wellington        | 1        | 0.7%    |
| Waldorf           | 1        | 0.7%    |
| Vouziers          | 1        | 0.7%    |
| Vineland          | 1        | 0.7%    |
| Vilnius           | 1        | 0.7%    |
| Villa Nueva       | 1        | 0.7%    |
| Valledupar        | 1        | 0.7%    |
| Valladolid        | 1        | 0.7%    |
| Thornhill         | 1        | 0.7%    |
| Tamworth          | 1        | 0.7%    |
| Tampere           | 1        | 0.7%    |
| Szeged            | 1        | 0.7%    |
| Stockholm         | 1        | 0.7%    |
| Serquigny         | 1        | 0.7%    |
| Seattle           | 1        | 0.7%    |
| Schruns           | 1        | 0.7%    |
| Satellite Beach   | 1        | 0.7%    |
| Sao Paulo         | 1        | 0.7%    |
| Santiago          | 1        | 0.7%    |
| San Jose          | 1        | 0.7%    |
| San Antonio       | 1        | 0.7%    |
| Salon-de-Provence | 1        | 0.7%    |
| Sacramento        | 1        | 0.7%    |
| Rotterdam         | 1        | 0.7%    |
| Rosario           | 1        | 0.7%    |
| Rome              | 1        | 0.7%    |
| Richardson        | 1        | 0.7%    |
| Reimlingen        | 1        | 0.7%    |
| Raleigh           | 1        | 0.7%    |
| Quito             | 1        | 0.7%    |
| Prague            | 1        | 0.7%    |
| Plano             | 1        | 0.7%    |
| Philipsburg       | 1        | 0.7%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 52       | 76     | 17.16%  |
| Samsung Electronics         | 48       | 82     | 15.84%  |
| Seagate                     | 43       | 59     | 14.19%  |
| Crucial                     | 24       | 31     | 7.92%   |
| Toshiba                     | 21       | 22     | 6.93%   |
| Kingston                    | 21       | 23     | 6.93%   |
| SanDisk                     | 15       | 16     | 4.95%   |
| Phison Electronics          | 7        | 8      | 2.31%   |
| PNY                         | 6        | 10     | 1.98%   |
| Phison                      | 6        | 7      | 1.98%   |
| Intel                       | 6        | 10     | 1.98%   |
| Hitachi                     | 4        | 4      | 1.32%   |
| China                       | 4        | 4      | 1.32%   |
| ADATA Technology            | 4        | 4      | 1.32%   |
| SPCC                        | 3        | 3      | 0.99%   |
| Realtek Semiconductor       | 3        | 3      | 0.99%   |
| Micron/Crucial Technology   | 3        | 3      | 0.99%   |
| Transcend                   | 2        | 2      | 0.66%   |
| Team                        | 2        | 2      | 0.66%   |
| Silicon Motion              | 2        | 2      | 0.66%   |
| Micron Technology           | 2        | 2      | 0.66%   |
| Apple                       | 2        | 2      | 0.66%   |
| A-DATA Technology           | 2        | 2      | 0.66%   |
| XPG                         | 1        | 1      | 0.33%   |
| Verbatim                    | 1        | 1      | 0.33%   |
| USB3.0                      | 1        | 1      | 0.33%   |
| Unknown                     | 1        | 1      | 0.33%   |
| SuperSSpeed                 | 1        | 1      | 0.33%   |
| SK hynix                    | 1        | 1      | 0.33%   |
| PNY CS90                    | 1        | 1      | 0.33%   |
| Patriot                     | 1        | 1      | 0.33%   |
| OCZ                         | 1        | 1      | 0.33%   |
| MyDigitalSSD                | 1        | 1      | 0.33%   |
| Mushkin                     | 1        | 1      | 0.33%   |
| Maxtor                      | 1        | 1      | 0.33%   |
| MAXIO Technology (Hangzhou) | 1        | 1      | 0.33%   |
| LITEONIT                    | 1        | 1      | 0.33%   |
| KIOXIA-EXCERIA              | 1        | 1      | 0.33%   |
| KIOXIA                      | 1        | 1      | 0.33%   |
| Kingston Technology Company | 1        | 1      | 0.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD                      | 8        | 2.23%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB  | 6        | 1.67%   |
| Phison E12 NVMe Controller 1TB                       | 6        | 1.67%   |
| Crucial CT1000MX500SSD1 1TB                          | 6        | 1.67%   |
| Toshiba HDWD110 1TB                                  | 5        | 1.39%   |
| Samsung SSD 860 EVO 500GB                            | 5        | 1.39%   |
| Intel SSD 660P Series 512GB                          | 5        | 1.39%   |
| WDC WD10EZEX-08WN4A0 1TB                             | 4        | 1.11%   |
| Toshiba DT01ACA100 1TB                               | 4        | 1.11%   |
| Seagate ST2000DM008-2FR102 2TB                       | 4        | 1.11%   |
| Samsung SSD 850 EVO 500GB                            | 4        | 1.11%   |
| Samsung SSD 850 EVO 250GB                            | 4        | 1.11%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 4        | 1.11%   |
| WDC WDBNCE5000PNC 500GB SSD                          | 3        | 0.84%   |
| Seagate ST2000DM001-1ER164 2TB                       | 3        | 0.84%   |
| Seagate ST1000DM003-1ER162 1TB                       | 3        | 0.84%   |
| SanDisk SSD PLUS 240GB                               | 3        | 0.84%   |
| Samsung SSD 980 500GB                                | 3        | 0.84%   |
| Samsung SSD 860 EVO 1TB                              | 3        | 0.84%   |
| Kingston SA400S37120G 120GB SSD                      | 3        | 0.84%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                     | 2        | 0.56%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                     | 2        | 0.56%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                     | 2        | 0.56%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                       | 2        | 0.56%   |
| WDC WD5000BEVT-75ZAT0 500GB                          | 2        | 0.56%   |
| WDC WD20EURS-63S48Y0 2TB                             | 2        | 0.56%   |
| WDC WD20EARS-00MVWB0 2TB                             | 2        | 0.56%   |
| WDC WD10JPCX-24UE4T0 1TB                             | 2        | 0.56%   |
| WDC WD10EZEX-00BN5A0 1TB                             | 2        | 0.56%   |
| Toshiba DT01ACA200 2TB                               | 2        | 0.56%   |
| Seagate ST3500418AS 500GB                            | 2        | 0.56%   |
| Seagate ST3500414CS 500GB                            | 2        | 0.56%   |
| Seagate ST3500413AS 500GB                            | 2        | 0.56%   |
| Seagate ST2000DX002-2DV164 2TB                       | 2        | 0.56%   |
| Seagate ST2000DX001-1NS164 2TB                       | 2        | 0.56%   |
| Seagate ST2000DM006-2DM164 2TB                       | 2        | 0.56%   |
| Sandisk WD Black SN850 2TB                           | 2        | 0.56%   |
| Samsung SSD 970 EVO Plus 500GB                       | 2        | 0.56%   |
| Samsung SSD 860 EVO 250GB                            | 2        | 0.56%   |
| Samsung SSD 840 EVO 120GB                            | 2        | 0.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 43       | 57     | 37.39%  |
| WDC                 | 42       | 60     | 36.52%  |
| Toshiba             | 17       | 18     | 14.78%  |
| Samsung Electronics | 6        | 11     | 5.22%   |
| Hitachi             | 4        | 4      | 3.48%   |
| Apple               | 2        | 2      | 1.74%   |
| Maxtor              | 1        | 1      | 0.87%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 30       | 37     | 23.08%  |
| Crucial             | 24       | 31     | 18.46%  |
| Kingston            | 19       | 21     | 14.62%  |
| WDC                 | 13       | 14     | 10%     |
| SanDisk             | 9        | 9      | 6.92%   |
| PNY                 | 6        | 10     | 4.62%   |
| China               | 4        | 4      | 3.08%   |
| SPCC                | 3        | 3      | 2.31%   |
| Transcend           | 2        | 2      | 1.54%   |
| A-DATA Technology   | 2        | 2      | 1.54%   |
| Verbatim            | 1        | 1      | 0.77%   |
| USB3.0              | 1        | 1      | 0.77%   |
| Toshiba             | 1        | 1      | 0.77%   |
| Team                | 1        | 1      | 0.77%   |
| SuperSSpeed         | 1        | 1      | 0.77%   |
| Seagate             | 1        | 1      | 0.77%   |
| PNY CS90            | 1        | 1      | 0.77%   |
| Patriot             | 1        | 1      | 0.77%   |
| OCZ                 | 1        | 1      | 0.77%   |
| MyDigitalSSD        | 1        | 1      | 0.77%   |
| Mushkin             | 1        | 1      | 0.77%   |
| Micron Technology   | 1        | 1      | 0.77%   |
| LITEONIT            | 1        | 1      | 0.77%   |
| KIOXIA-EXCERIA      | 1        | 1      | 0.77%   |
| JMicron Technology  | 1        | 1      | 0.77%   |
| Intel               | 1        | 1      | 0.77%   |
| Foxline             | 1        | 1      | 0.77%   |
| Drevo               | 1        | 1      | 0.77%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 99       | 151    | 39.76%  |
| HDD     | 89       | 153    | 35.74%  |
| NVMe    | 57       | 90     | 22.89%  |
| Unknown | 3        | 3      | 1.2%    |
| MMC     | 1        | 1      | 0.4%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 124      | 296    | 64.92%  |
| NVMe | 57       | 90     | 29.84%  |
| SAS  | 9        | 11     | 4.71%   |
| MMC  | 1        | 1      | 0.52%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 93       | 140    | 43.46%  |
| 0.51-1.0   | 65       | 90     | 30.37%  |
| 1.01-2.0   | 35       | 51     | 16.36%  |
| 3.01-4.0   | 6        | 6      | 2.8%    |
| 2.01-3.0   | 6        | 6      | 2.8%    |
| 4.01-10.0  | 6        | 7      | 2.8%    |
| 10.01-20.0 | 3        | 4      | 1.4%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 33       | 23.74%  |
| 251-500        | 29       | 20.86%  |
| 1001-2000      | 25       | 17.99%  |
| 501-1000       | 22       | 15.83%  |
| More than 3000 | 18       | 12.95%  |
| 2001-3000      | 6        | 4.32%   |
| 51-100         | 3        | 2.16%   |
| 21-50          | 2        | 1.44%   |
| 1-20           | 1        | 0.72%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 21-50          | 38       | 26.39%  |
| 1-20           | 29       | 20.14%  |
| 51-100         | 18       | 12.5%   |
| 101-250        | 16       | 11.11%  |
| 251-500        | 14       | 9.72%   |
| 501-1000       | 12       | 8.33%   |
| More than 3000 | 6        | 4.17%   |
| 2001-3000      | 6        | 4.17%   |
| 1001-2000      | 5        | 3.47%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Desktops | Drives | Percent |
|------------------------------------------------|----------|--------|---------|
| WDC WD5000BEVT-75ZAT0 500GB                    | 2        | 2      | 22.22%  |
| WDC WD20EURS-63S48Y0 2TB                       | 1        | 1      | 11.11%  |
| WDC WD10EZEX-08M2NA0 1TB                       | 1        | 1      | 11.11%  |
| Seagate ST2000DX002-2DV164 2TB                 | 1        | 1      | 11.11%  |
| Seagate ST1000DM003-9YN162 1TB                 | 1        | 1      | 11.11%  |
| Samsung Electronics SSD 970 EVO 1TB            | 1        | 1      | 11.11%  |
| Samsung Electronics HD161GJ 160GB              | 1        | 1      | 11.11%  |
| Micron Technology MTFDDAK256MAM-1K12 256GB SSD | 1        | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 4        | 4      | 44.44%  |
| Seagate             | 2        | 2      | 22.22%  |
| Samsung Electronics | 2        | 2      | 22.22%  |
| Micron Technology   | 1        | 1      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 4        | 4      | 57.14%  |
| Seagate             | 2        | 2      | 28.57%  |
| Samsung Electronics | 1        | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 7        | 7      | 77.78%  |
| NVMe | 1        | 1      | 11.11%  |
| SSD  | 1        | 1      | 11.11%  |

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
| Detected | 119      | 330    | 82.07%  |
| Works    | 17       | 58     | 11.72%  |
| Malfunc  | 8        | 9      | 5.52%   |
| Limited  | 1        | 1      | 0.69%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| AMD                          | 69       | 31.51%  |
| Intel                        | 67       | 30.59%  |
| Samsung Electronics          | 23       | 10.5%   |
| Phison Electronics           | 13       | 5.94%   |
| ASMedia Technology           | 9        | 4.11%   |
| SanDisk                      | 7        | 3.2%    |
| Realtek Semiconductor        | 4        | 1.83%   |
| ADATA Technology             | 4        | 1.83%   |
| Micron/Crucial Technology    | 3        | 1.37%   |
| Marvell Technology Group     | 3        | 1.37%   |
| Kingston Technology Company  | 3        | 1.37%   |
| Toshiba America Info Systems | 2        | 0.91%   |
| Silicon Motion               | 2        | 0.91%   |
| Nvidia                       | 2        | 0.91%   |
| JMicron Technology           | 2        | 0.91%   |
| SK hynix                     | 1        | 0.46%   |
| Silicon Image                | 1        | 0.46%   |
| Micron Technology            | 1        | 0.46%   |
| MAXIO Technology (Hangzhou)  | 1        | 0.46%   |
| KIOXIA                       | 1        | 0.46%   |
| Broadcom / LSI               | 1        | 0.46%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 41       | 15.71%  |
| AMD 400 Series Chipset SATA Controller                                                  | 20       | 7.66%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 12       | 4.6%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 9        | 3.45%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 9        | 3.45%   |
| AMD 500 Series Chipset SATA Controller                                                  | 9        | 3.45%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 8        | 3.07%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 8        | 3.07%   |
| Phison E12 NVMe Controller                                                              | 6        | 2.3%    |
| Intel SATA Controller [RAID mode]                                                       | 6        | 2.3%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 6        | 2.3%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 6        | 2.3%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 5        | 1.92%   |
| Intel SSD 660P Series                                                                   | 5        | 1.92%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5        | 1.92%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5        | 1.92%   |
| Samsung NVMe SSD Controller 980                                                         | 4        | 1.53%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4        | 1.53%   |
| AMD FCH SATA Controller D                                                               | 4        | 1.53%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 3        | 1.15%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 3        | 1.15%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 3        | 1.15%   |
| Kingston Company A2000 NVMe SSD                                                         | 3        | 1.15%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 3        | 1.15%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 3        | 1.15%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3        | 1.15%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3        | 1.15%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 2        | 0.77%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 2        | 0.77%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2        | 0.77%   |
| Phison E18 PCIe4 NVMe Controller                                                        | 2        | 0.77%   |
| Nvidia MCP61 SATA Controller                                                            | 2        | 0.77%   |
| Nvidia MCP61 IDE                                                                        | 2        | 0.77%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 2        | 0.77%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 2        | 0.77%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2        | 0.77%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2        | 0.77%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2        | 0.77%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 0.77%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 0.77%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 124      | 60.19%  |
| NVMe | 57       | 27.67%  |
| IDE  | 14       | 6.8%    |
| RAID | 9        | 4.37%   |
| SAS  | 2        | 0.97%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 71       | 51.82%  |
| Intel  | 66       | 48.18%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 2600 Six-Core Processor         | 7        | 5.11%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 5        | 3.65%   |
| AMD FX-8350 Eight-Core Processor            | 5        | 3.65%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 4        | 2.92%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 4        | 2.92%   |
| AMD Ryzen 5 3600 6-Core Processor           | 4        | 2.92%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 3        | 2.19%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 3        | 2.19%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 3        | 2.19%   |
| Intel 12th Gen Core i5-12600K               | 3        | 2.19%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 3        | 2.19%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 3        | 2.19%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 3        | 2.19%   |
| AMD FX-6300 Six-Core Processor              | 3        | 2.19%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 2        | 1.46%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 2        | 1.46%   |
| Intel Core i5-7600K CPU @ 3.80GHz           | 2        | 1.46%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 2        | 1.46%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 2        | 1.46%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2        | 1.46%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz      | 2        | 1.46%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 2        | 1.46%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 2        | 1.46%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 2        | 1.46%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 2        | 1.46%   |
| Intel Xeon CPU W3530 @ 2.80GHz              | 1        | 0.73%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz          | 1        | 0.73%   |
| Intel Xeon CPU E5-2667 v4 @ 3.20GHz         | 1        | 0.73%   |
| Intel Xeon CPU E5-2667 0 @ 2.90GHz          | 1        | 0.73%   |
| Intel Xeon CPU E3-1240 V2 @ 3.40GHz         | 1        | 0.73%   |
| Intel Pentium CPU G640 @ 2.80GHz            | 1        | 0.73%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1        | 0.73%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1        | 0.73%   |
| Intel Core i7-3960X CPU @ 3.30GHz           | 1        | 0.73%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 1        | 0.73%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 0.73%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1        | 0.73%   |
| Intel Core i7-10700KF CPU @ 3.80GHz         | 1        | 0.73%   |
| Intel Core i7-10700K CPU @ 3.80GHz          | 1        | 0.73%   |
| Intel Core i7-10700F CPU @ 2.90GHz          | 1        | 0.73%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Desktops | Percent |
|----------------------|----------|---------|
| AMD Ryzen 5          | 28       | 20.44%  |
| Intel Core i5        | 22       | 16.06%  |
| Intel Core i7        | 16       | 11.68%  |
| AMD Ryzen 9          | 12       | 8.76%   |
| AMD Ryzen 7          | 11       | 8.03%   |
| Intel Core i3        | 9        | 6.57%   |
| AMD FX               | 9        | 6.57%   |
| Other                | 6        | 4.38%   |
| Intel Xeon           | 5        | 3.65%   |
| Intel Core i9        | 3        | 2.19%   |
| AMD Ryzen 3          | 3        | 2.19%   |
| Intel Core 2 Duo     | 2        | 1.46%   |
| AMD Phenom II X6     | 2        | 1.46%   |
| Intel Pentium        | 1        | 0.73%   |
| Intel Celeron        | 1        | 0.73%   |
| Intel Atom           | 1        | 0.73%   |
| AMD Phenom II X4     | 1        | 0.73%   |
| AMD Athlon X4        | 1        | 0.73%   |
| AMD Athlon Dual Core | 1        | 0.73%   |
| AMD A6               | 1        | 0.73%   |
| AMD A4               | 1        | 0.73%   |
| AMD A10              | 1        | 0.73%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 6      | 42       | 30.66%  |
| 4      | 37       | 27.01%  |
| 8      | 21       | 15.33%  |
| 2      | 17       | 12.41%  |
| 12     | 8        | 5.84%   |
| 16     | 4        | 2.92%   |
| 10     | 3        | 2.19%   |
| 3      | 3        | 2.19%   |
| 1      | 2        | 1.46%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 136      | 99.27%  |
| 2      | 1        | 0.73%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 105      | 76.64%  |
| 1      | 32       | 23.36%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 137      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x08701021 | 13       | 9.49%   |
| 0x306c3    | 10       | 7.3%    |
| 0x306a9    | 9        | 6.57%   |
| 0x0800820d | 8        | 5.84%   |
| 0x06000822 | 8        | 5.84%   |
| 0x206a7    | 6        | 4.38%   |
| 0x0a201016 | 6        | 4.38%   |
| 0xa0655    | 5        | 3.65%   |
| 0x906ea    | 5        | 3.65%   |
| 0x0a50000c | 4        | 2.92%   |
| 0x08001138 | 4        | 2.92%   |
| Unknown    | 4        | 2.92%   |
| 0x906ed    | 3        | 2.19%   |
| 0x906ec    | 3        | 2.19%   |
| 0x906e9    | 3        | 2.19%   |
| 0x90672    | 3        | 2.19%   |
| 0x506e3    | 3        | 2.19%   |
| 0x206d7    | 3        | 2.19%   |
| 0x0a201205 | 3        | 2.19%   |
| 0x0a201204 | 3        | 2.19%   |
| 0x08108109 | 3        | 2.19%   |
| 0xa0671    | 2        | 1.46%   |
| 0xa0653    | 2        | 1.46%   |
| 0x1067a    | 2        | 1.46%   |
| 0x0a50000d | 2        | 1.46%   |
| 0x0a201009 | 2        | 1.46%   |
| 0x08701013 | 2        | 1.46%   |
| 0x06003106 | 2        | 1.46%   |
| 0x06001119 | 2        | 1.46%   |
| 0x010000bf | 2        | 1.46%   |
| 0x406f1    | 1        | 0.73%   |
| 0x406c4    | 1        | 0.73%   |
| 0x40651    | 1        | 0.73%   |
| 0x106a5    | 1        | 0.73%   |
| 0x0a601203 | 1        | 0.73%   |
| 0x0a20120a | 1        | 0.73%   |
| 0x08108102 | 1        | 0.73%   |
| 0x0800820b | 1        | 0.73%   |
| 0x06000817 | 1        | 0.73%   |
| 0x01000086 | 1        | 0.73%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 3            | 21       | 15.33%  |
| Zen 2            | 15       | 10.95%  |
| KabyLake         | 15       | 10.95%  |
| Zen+             | 13       | 9.49%   |
| Piledriver       | 11       | 8.03%   |
| Haswell          | 11       | 8.03%   |
| SandyBridge      | 10       | 7.3%    |
| IvyBridge        | 9        | 6.57%   |
| CometLake        | 7        | 5.11%   |
| Zen              | 4        | 2.92%   |
| Skylake          | 3        | 2.19%   |
| K10              | 3        | 2.19%   |
| Alderlake Hybrid | 3        | 2.19%   |
| Steamroller      | 2        | 1.46%   |
| Penryn           | 2        | 1.46%   |
| Icelake          | 2        | 1.46%   |
| Unknown          | 2        | 1.46%   |
| Silvermont       | 1        | 0.73%   |
| Nehalem          | 1        | 0.73%   |
| K8 Hammer        | 1        | 0.73%   |
| Broadwell        | 1        | 0.73%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 71       | 47.33%  |
| AMD    | 56       | 37.33%  |
| Intel  | 23       | 15.33%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 12       | 7.79%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                        | 8        | 5.19%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 5        | 3.25%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 4        | 2.6%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4        | 2.6%    |
| Nvidia GP104 [GeForce GTX 1080]                                             | 4        | 2.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 4        | 2.6%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 4        | 2.6%    |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 1.95%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 3        | 1.95%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 3        | 1.95%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3        | 1.95%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 1.95%   |
| Intel AlderLake-S GT1                                                       | 3        | 1.95%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 1.95%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 1.95%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 3        | 1.95%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 1.3%    |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2        | 1.3%    |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 2        | 1.3%    |
| Nvidia TU104 [GeForce RTX 2060]                                             | 2        | 1.3%    |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 2        | 1.3%    |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 1.3%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 2        | 1.3%    |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2        | 1.3%    |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 2        | 1.3%    |
| Nvidia GK104 [GeForce GTX 760]                                              | 2        | 1.3%    |
| Nvidia GA104 [GeForce RTX 3060]                                             | 2        | 1.3%    |
| Nvidia GA102 [GeForce RTX 3080]                                             | 2        | 1.3%    |
| Intel HD Graphics 530                                                       | 2        | 1.3%    |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                                  | 2        | 1.3%    |
| AMD Navi 21 [Radeon RX 6900 XT]                                             | 2        | 1.3%    |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2        | 1.3%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 1.3%    |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 2        | 1.3%    |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 0.65%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 0.65%   |
| Nvidia TU104GL [Quadro RTX 4000]                                            | 1        | 0.65%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 0.65%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x Nvidia   | 66       | 48.18%  |
| 1 x AMD      | 49       | 35.77%  |
| 1 x Intel    | 14       | 10.22%  |
| AMD + Nvidia | 3        | 2.19%   |
| 2 x Nvidia   | 2        | 1.46%   |
| Intel + AMD  | 2        | 1.46%   |
| 2 x AMD      | 1        | 0.73%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 80       | 57.97%  |
| Proprietary | 55       | 39.86%  |
| Unknown     | 3        | 2.17%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 46       | 33.09%  |
| 7.01-8.0   | 27       | 19.42%  |
| 3.01-4.0   | 18       | 12.95%  |
| 8.01-16.0  | 17       | 12.23%  |
| 1.01-2.0   | 13       | 9.35%   |
| 0.51-1.0   | 6        | 4.32%   |
| 0.01-0.5   | 5        | 3.6%    |
| 5.01-6.0   | 3        | 2.16%   |
| 2.01-3.0   | 2        | 1.44%   |
| 16.01-24.0 | 2        | 1.44%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 25       | 16.34%  |
| Goldstar             | 20       | 13.07%  |
| Acer                 | 14       | 9.15%   |
| Dell                 | 10       | 6.54%   |
| Ancor Communications | 10       | 6.54%   |
| BenQ                 | 9        | 5.88%   |
| ASUSTek Computer     | 8        | 5.23%   |
| AOC                  | 8        | 5.23%   |
| MSI                  | 6        | 3.92%   |
| Hewlett-Packard      | 6        | 3.92%   |
| Vizio                | 5        | 3.27%   |
| Sony                 | 4        | 2.61%   |
| Philips              | 4        | 2.61%   |
| ViewSonic            | 3        | 1.96%   |
| Toshiba              | 3        | 1.96%   |
| Sceptre Tech         | 3        | 1.96%   |
| Lenovo               | 2        | 1.31%   |
| Gigabyte Technology  | 2        | 1.31%   |
| SNC                  | 1        | 0.65%   |
| SFX                  | 1        | 0.65%   |
| PRI                  | 1        | 0.65%   |
| NPC                  | 1        | 0.65%   |
| MStar                | 1        | 0.65%   |
| Iiyama               | 1        | 0.65%   |
| HUAWEI               | 1        | 0.65%   |
| Hitachi              | 1        | 0.65%   |
| GDH                  | 1        | 0.65%   |
| Dark Matter          | 1        | 0.65%   |
| Unknown              | 1        | 0.65%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Toshiba TV TSB0108 1440x900 700x390mm 31.5-inch                        | 2        | 1.2%    |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch   | 2        | 1.2%    |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 1060x626mm 48.5-inch | 2        | 1.2%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 2        | 1.2%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 2        | 1.2%    |
| MSI G27C4 MSI3CA9 1920x1080 598x336mm 27.0-inch                        | 2        | 1.2%    |
| Goldstar ULTRAGEAR GSM7766 2560x1440 697x392mm 31.5-inch               | 2        | 1.2%    |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 2        | 1.2%    |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 2        | 1.2%    |
| ASUSTek Computer ROG XG27UQR AUS27BA 3840x2160 596x335mm 26.9-inch     | 2        | 1.2%    |
| ASUSTek Computer PA278QV AUS2700 2560x1440 597x336mm 27.0-inch         | 2        | 1.2%    |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch  | 2        | 1.2%    |
| Vizio VX42L HDTV10A VIZ0030 1280x720 930x523mm 42.0-inch               | 1        | 0.6%    |
| Vizio V435-J01 VIZ1039 3840x2160 941x529mm 42.5-inch                   | 1        | 0.6%    |
| Vizio E601i-A3 VIZ0092 1920x1080 1329x748mm 60.0-inch                  | 1        | 0.6%    |
| Vizio E400i-C2 VIZ1004 1920x1080 477x268mm 21.5-inch                   | 1        | 0.6%    |
| Vizio D24h-G9 VIZ1028 1360x768 521x293mm 23.5-inch                     | 1        | 0.6%    |
| ViewSonic XG2402 SERIES VSC1B35 1920x1080 531x299mm 24.0-inch          | 1        | 0.6%    |
| ViewSonic XG2401 SERIES VSCBB31 1920x1080 531x299mm 24.0-inch          | 1        | 0.6%    |
| ViewSonic VX3218-PC-mhd VSCEB3A 1920x1080 609x348mm 27.6-inch          | 1        | 0.6%    |
| Toshiba LCD-MONITOR LCDE980 1440x900 408x255mm 18.9-inch               | 1        | 0.6%    |
| Sony TV SNYEB01 1360x768                                               | 1        | 0.6%    |
| Sony TV SNY8F03 1360x768                                               | 1        | 0.6%    |
| Sony TV *00 SNYF303 1920x1080 1218x685mm 55.0-inch                     | 1        | 0.6%    |
| Sony SDM-HS75P SNY2200 1280x1024 338x270mm 17.0-inch                   | 1        | 0.6%    |
| SNC SKP_E20-32 SNC3200 1920x1080 477x268mm 21.5-inch                   | 1        | 0.6%    |
| SFX HDMI2.0 KVM SFX0100 1920x1080 708x398mm 32.0-inch                  | 1        | 0.6%    |
| Sceptre Tech Sceptre Y40 SPT0FCD 2560x1440 852x480mm 38.5-inch         | 1        | 0.6%    |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x291mm 29.5-inch         | 1        | 0.6%    |
| Sceptre Tech Sceptre O345 SPT8540 3440x1440 797x334mm 34.0-inch        | 1        | 0.6%    |
| Sceptre Tech Sceptre M27 SPT0ACD 1920x1080 598x336mm 27.0-inch         | 1        | 0.6%    |
| Samsung Electronics U32J59x SAM0F34 3840x2160 697x392mm 31.5-inch      | 1        | 0.6%    |
| Samsung Electronics U28D590 SAM0B80 3840x2160 610x350mm 27.7-inch      | 1        | 0.6%    |
| Samsung Electronics SyncMaster SAM05FC 1920x1080                       | 1        | 0.6%    |
| Samsung Electronics SyncMaster SAM0422 1920x1200 518x324mm 24.1-inch   | 1        | 0.6%    |
| Samsung Electronics SyncMaster SAM037A 1680x1050 433x271mm 20.1-inch   | 1        | 0.6%    |
| Samsung Electronics SyncMaster SAM0168 1280x1024 338x270mm 17.0-inch   | 1        | 0.6%    |
| Samsung Electronics SyncMaster SAM0124 1280x1024 338x270mm 17.0-inch   | 1        | 0.6%    |
| Samsung Electronics SMB2030N SAM0634 1600x900 443x249mm 20.0-inch      | 1        | 0.6%    |
| Samsung Electronics S27F350 SAM0D22 1920x1080 600x340mm 27.2-inch      | 1        | 0.6%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 65       | 42.76%  |
| 3840x2160 (4K)     | 26       | 17.11%  |
| 2560x1440 (QHD)    | 24       | 15.79%  |
| 1680x1050 (WSXGA+) | 6        | 3.95%   |
| 3440x1440          | 5        | 3.29%   |
| 2560x1080          | 4        | 2.63%   |
| 1600x900 (HD+)     | 4        | 2.63%   |
| 1440x900 (WXGA+)   | 3        | 1.97%   |
| 1360x768           | 3        | 1.97%   |
| 1280x1024 (SXGA)   | 3        | 1.97%   |
| 1920x540           | 2        | 1.32%   |
| 1366x768 (WXGA)    | 2        | 1.32%   |
| 5760x1080          | 1        | 0.66%   |
| 3840x2560          | 1        | 0.66%   |
| 3840x1600          | 1        | 0.66%   |
| 1920x1200 (WUXGA)  | 1        | 0.66%   |
| Unknown            | 1        | 0.66%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 37       | 23.42%  |
| 23      | 16       | 10.13%  |
| 21      | 15       | 9.49%   |
| 24      | 14       | 8.86%   |
| 31      | 13       | 8.23%   |
| 34      | 6        | 3.8%    |
| 84      | 5        | 3.16%   |
| 19      | 5        | 3.16%   |
| 72      | 4        | 2.53%   |
| 22      | 4        | 2.53%   |
| 20      | 4        | 2.53%   |
| 48      | 3        | 1.9%    |
| 26      | 3        | 1.9%    |
| 17      | 3        | 1.9%    |
| Unknown | 3        | 1.9%    |
| 52      | 2        | 1.27%   |
| 42      | 2        | 1.27%   |
| 40      | 2        | 1.27%   |
| 38      | 2        | 1.27%   |
| 29      | 2        | 1.27%   |
| 28      | 2        | 1.27%   |
| 75      | 1        | 0.63%   |
| 69      | 1        | 0.63%   |
| 60      | 1        | 0.63%   |
| 58      | 1        | 0.63%   |
| 54      | 1        | 0.63%   |
| 49      | 1        | 0.63%   |
| 37      | 1        | 0.63%   |
| 33      | 1        | 0.63%   |
| 32      | 1        | 0.63%   |
| 18      | 1        | 0.63%   |
| 14      | 1        | 0.63%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 60       | 39.74%  |
| 401-500     | 29       | 19.21%  |
| 601-700     | 20       | 13.25%  |
| 1501-2000   | 11       | 7.28%   |
| 1001-1500   | 9        | 5.96%   |
| 701-800     | 8        | 5.3%    |
| 801-900     | 5        | 3.31%   |
| 301-350     | 3        | 1.99%   |
| Unknown     | 3        | 1.99%   |
| 901-1000    | 2        | 1.32%   |
| 201-300     | 1        | 0.66%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 100      | 76.34%  |
| 16/10   | 13       | 9.92%   |
| 21/9    | 10       | 7.63%   |
| 5/4     | 3        | 2.29%   |
| 4/3     | 2        | 1.53%   |
| 32/9    | 1        | 0.76%   |
| 3/2     | 1        | 0.76%   |
| Unknown | 1        | 0.76%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 301-350        | 41       | 26.28%  |
| 201-250        | 41       | 26.28%  |
| 351-500        | 22       | 14.1%   |
| More than 1000 | 19       | 12.18%  |
| 151-200        | 14       | 8.97%   |
| 501-1000       | 8        | 5.13%   |
| 251-300        | 4        | 2.56%   |
| 141-150        | 3        | 1.92%   |
| Unknown        | 3        | 1.92%   |
| 101-110        | 1        | 0.64%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 82       | 56.94%  |
| 101-120 | 34       | 23.61%  |
| 1-50    | 14       | 9.72%   |
| 121-160 | 6        | 4.17%   |
| 161-240 | 5        | 3.47%   |
| Unknown | 3        | 2.08%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 94       | 68.61%  |
| 2     | 30       | 21.9%   |
| 3     | 6        | 4.38%   |
| 0     | 6        | 4.38%   |
| 4     | 1        | 0.73%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 88       | 43.35%  |
| Intel                           | 66       | 32.51%  |
| Qualcomm Atheros                | 9        | 4.43%   |
| TP-Link                         | 8        | 3.94%   |
| Microsoft                       | 6        | 2.96%   |
| MediaTek                        | 5        | 2.46%   |
| Broadcom                        | 4        | 1.97%   |
| Ralink Technology               | 2        | 0.99%   |
| Ralink                          | 2        | 0.99%   |
| Broadcom Limited                | 2        | 0.99%   |
| Wacom                           | 1        | 0.49%   |
| T & A Mobile Phones             | 1        | 0.49%   |
| Samsung Electronics             | 1        | 0.49%   |
| Qualcomm Atheros Communications | 1        | 0.49%   |
| Oculus VR                       | 1        | 0.49%   |
| Motorola PCS                    | 1        | 0.49%   |
| Linksys                         | 1        | 0.49%   |
| ICS Advent                      | 1        | 0.49%   |
| Holtek Semiconductor            | 1        | 0.49%   |
| D-Link                          | 1        | 0.49%   |
| ASUSTek Computer                | 1        | 0.49%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 71       | 30.47%  |
| Intel Wi-Fi 6 AX200                                               | 18       | 7.73%   |
| Realtek RTL8125 2.5GbE Controller                                 | 16       | 6.87%   |
| Intel I211 Gigabit Network Connection                             | 13       | 5.58%   |
| Intel Ethernet Controller I225-V                                  | 8        | 3.43%   |
| Intel Ethernet Connection (7) I219-V                              | 7        | 3%      |
| Intel 82579V Gigabit Network Connection                           | 4        | 1.72%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 1.72%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 3        | 1.29%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3        | 1.29%   |
| Microsoft Wireless XBox Controller Dongle                         | 3        | 1.29%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 3        | 1.29%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3        | 1.29%   |
| Intel Ethernet Connection (2) I218-V                              | 3        | 1.29%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3        | 1.29%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 3        | 1.29%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 2        | 0.86%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 2        | 0.86%   |
| TP-Link 802.11ac NIC                                              | 2        | 0.86%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2        | 0.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2        | 0.86%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 2        | 0.86%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2        | 0.86%   |
| Realtek 802.11ac NIC                                              | 2        | 0.86%   |
| Microsoft Xbox 360 Wireless Adapter                               | 2        | 0.86%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 0.86%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 0.86%   |
| Intel Ethernet Connection (14) I219-V                             | 2        | 0.86%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 2        | 0.86%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                          | 1        | 0.43%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 1        | 0.43%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1        | 0.43%   |
| T & A Mobile Phones ALCATEL ONETOUCH PIXI 3 (4)                   | 1        | 0.43%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.43%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.43%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 1        | 0.43%   |
| Realtek RTL8150 Fast Ethernet Adapter                             | 1        | 0.43%   |
| Ralink RT5572 Wireless Adapter                                    | 1        | 0.43%   |
| Ralink MT7601U Wireless Adapter                                   | 1        | 0.43%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 1        | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 31       | 38.75%  |
| Realtek Semiconductor           | 15       | 18.75%  |
| TP-Link                         | 8        | 10%     |
| Microsoft                       | 6        | 7.5%    |
| MediaTek                        | 5        | 6.25%   |
| Broadcom                        | 3        | 3.75%   |
| Ralink Technology               | 2        | 2.5%    |
| Ralink                          | 2        | 2.5%    |
| Qualcomm Atheros                | 2        | 2.5%    |
| Wacom                           | 1        | 1.25%   |
| Qualcomm Atheros Communications | 1        | 1.25%   |
| Linksys                         | 1        | 1.25%   |
| D-Link                          | 1        | 1.25%   |
| Broadcom Limited                | 1        | 1.25%   |
| ASUSTek Computer                | 1        | 1.25%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 18       | 22.5%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 3        | 3.75%   |
| Microsoft Wireless XBox Controller Dongle                      | 3        | 3.75%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 3        | 3.75%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 3        | 3.75%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3        | 3.75%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 3        | 3.75%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 2        | 2.5%    |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 2        | 2.5%    |
| TP-Link 802.11ac NIC                                           | 2        | 2.5%    |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 2        | 2.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2        | 2.5%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 2        | 2.5%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2        | 2.5%    |
| Realtek 802.11ac NIC                                           | 2        | 2.5%    |
| Microsoft Xbox 360 Wireless Adapter                            | 2        | 2.5%    |
| Intel Alder Lake-S PCH CNVi WiFi                               | 2        | 2.5%    |
| Wacom ACK-40401 [Wireless Accessory Kit]                       | 1        | 1.25%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 1        | 1.25%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1        | 1.25%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1        | 1.25%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1        | 1.25%   |
| Ralink RT5572 Wireless Adapter                                 | 1        | 1.25%   |
| Ralink MT7601U Wireless Adapter                                | 1        | 1.25%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 1        | 1.25%   |
| Ralink RT2800 802.11n PCI                                      | 1        | 1.25%   |
| Qualcomm Atheros AR9271 802.11n                                | 1        | 1.25%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1        | 1.25%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1        | 1.25%   |
| Microsoft XBOX ACC                                             | 1        | 1.25%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 1        | 1.25%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 1        | 1.25%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter            | 1        | 1.25%   |
| Intel Wireless-AC 9260                                         | 1        | 1.25%   |
| Intel Wireless 7265                                            | 1        | 1.25%   |
| Intel Wireless 3165                                            | 1        | 1.25%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1        | 1.25%   |
| Intel Centrino Wireless-N 2200                                 | 1        | 1.25%   |
| D-Link 802.11ac NIC                                            | 1        | 1.25%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter     | 1        | 1.25%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 84       | 57.53%  |
| Intel                 | 49       | 33.56%  |
| Qualcomm Atheros      | 7        | 4.79%   |
| T & A Mobile Phones   | 1        | 0.68%   |
| Samsung Electronics   | 1        | 0.68%   |
| Motorola PCS          | 1        | 0.68%   |
| ICS Advent            | 1        | 0.68%   |
| Broadcom Limited      | 1        | 0.68%   |
| Broadcom              | 1        | 0.68%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 71       | 47.02%  |
| Realtek RTL8125 2.5GbE Controller                                 | 16       | 10.6%   |
| Intel I211 Gigabit Network Connection                             | 13       | 8.61%   |
| Intel Ethernet Controller I225-V                                  | 8        | 5.3%    |
| Intel Ethernet Connection (7) I219-V                              | 7        | 4.64%   |
| Intel 82579V Gigabit Network Connection                           | 4        | 2.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 2.65%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3        | 1.99%   |
| Intel Ethernet Connection (2) I218-V                              | 3        | 1.99%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 1.32%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 1.32%   |
| Intel Ethernet Connection (14) I219-V                             | 2        | 1.32%   |
| T & A Mobile Phones ALCATEL ONETOUCH PIXI 3 (4)                   | 1        | 0.66%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.66%   |
| Realtek RTL8150 Fast Ethernet Adapter                             | 1        | 0.66%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.66%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.66%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.66%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.66%   |
| Motorola PCS motorola one 5G ace                                  | 1        | 0.66%   |
| Intel I210 Gigabit Network Connection                             | 1        | 0.66%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.66%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 0.66%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 0.66%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 0.66%   |
| ICS Advent USB 10/100 LAN                                         | 1        | 0.66%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 0.66%   |
| Broadcom Limited NetXtreme BCM5754 Gigabit Ethernet PCI Express   | 1        | 0.66%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 137      | 65.24%  |
| WiFi     | 71       | 33.81%  |
| Modem    | 1        | 0.48%   |
| Unknown  | 1        | 0.48%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 110      | 75.34%  |
| WiFi     | 36       | 24.66%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 83       | 60.58%  |
| 2     | 50       | 36.5%   |
| 3     | 4        | 2.92%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 93       | 66.91%  |
| Yes  | 46       | 33.09%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 30       | 44.12%  |
| Cambridge Silicon Radio         | 13       | 19.12%  |
| Broadcom                        | 5        | 7.35%   |
| Realtek Semiconductor           | 3        | 4.41%   |
| MediaTek                        | 3        | 4.41%   |
| ASUSTek Computer                | 3        | 4.41%   |
| TP-Link                         | 2        | 2.94%   |
| IMC Networks                    | 2        | 2.94%   |
| Foxconn / Hon Hai               | 2        | 2.94%   |
| Qualcomm Atheros Communications | 1        | 1.47%   |
| Integrated System Solution      | 1        | 1.47%   |
| Edimax Technology               | 1        | 1.47%   |
| Dell                            | 1        | 1.47%   |
| Unknown                         | 1        | 1.47%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                   | 18       | 26.47%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)     | 13       | 19.12%  |
| MediaTek Wireless_Device                                | 3        | 4.41%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)          | 3        | 4.41%   |
| Intel AX210 Bluetooth                                   | 3        | 4.41%   |
| Broadcom BCM20702A0 Bluetooth 4.0                       | 3        | 4.41%   |
| ASUS ASUS USB-BT500                                     | 3        | 4.41%   |
| TP-Link TPuLink UB500 Adapter                           | 2        | 2.94%   |
| Realtek Bluetooth Radio                                 | 2        | 2.94%   |
| Intel Bluetooth wireless interface                      | 2        | 2.94%   |
| Intel Bluetooth Device                                  | 2        | 2.94%   |
| Realtek  Bluetooth 4.2 Adapter                          | 1        | 1.47%   |
| Qualcomm Atheros AR3011 Bluetooth                       | 1        | 1.47%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                | 1        | 1.47%   |
| Intel Wireless-AC 3168 Bluetooth                        | 1        | 1.47%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter   | 1        | 1.47%   |
| IMC Networks Wireless_Device                            | 1        | 1.47%   |
| IMC Networks Bluetooth Radio                            | 1        | 1.47%   |
| Foxconn / Hon Hai Wireless_Device                       | 1        | 1.47%   |
| Foxconn / Hon Hai Bluetooth Device                      | 1        | 1.47%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter | 1        | 1.47%   |
| Dell Broadcom BCM20702A0 Bluetooth                      | 1        | 1.47%   |
| Broadcom Bluetooth Device                               | 1        | 1.47%   |
| Broadcom BCM2045 Bluetooth                              | 1        | 1.47%   |
| Unknown                                                 | 1        | 1.47%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| AMD                      | 85       | 29.93%  |
| Nvidia                   | 70       | 24.65%  |
| Intel                    | 62       | 21.83%  |
| C-Media Electronics      | 12       | 4.23%   |
| Logitech                 | 10       | 3.52%   |
| Razer USA                | 4        | 1.41%   |
| SteelSeries ApS          | 3        | 1.06%   |
| Plantronics              | 3        | 1.06%   |
| Kingston Technology      | 3        | 1.06%   |
| JMTek                    | 3        | 1.06%   |
| Focusrite-Novation       | 3        | 1.06%   |
| ASUSTek Computer         | 3        | 1.06%   |
| Samson Technologies      | 2        | 0.7%    |
| Realtek Semiconductor    | 2        | 0.7%    |
| Creative Technology      | 2        | 0.7%    |
| Creative Labs            | 2        | 0.7%    |
| Blue Microphones         | 2        | 0.7%    |
| Asahi Kasei Microsystems | 2        | 0.7%    |
| Texas Instruments        | 1        | 0.35%   |
| ROCCAT                   | 1        | 0.35%   |
| Positive Grid            | 1        | 0.35%   |
| Micro Star International | 1        | 0.35%   |
| Giga-Byte Technology     | 1        | 0.35%   |
| Generalplus Technology   | 1        | 0.35%   |
| Elgato Systems           | 1        | 0.35%   |
| Corsair                  | 1        | 0.35%   |
| Cambridge Silicon Radio  | 1        | 0.35%   |
| Audio-Technica           | 1        | 0.35%   |
| AKAI Professional M.I.   | 1        | 0.35%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 29       | 8.66%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 20       | 5.97%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 13       | 3.88%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 12       | 3.58%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 11       | 3.28%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 10       | 2.99%   |
| Intel Cannon Lake PCH cAVS                                                 | 9        | 2.69%   |
| AMD Family 17h/19h HD Audio Controller                                     | 9        | 2.69%   |
| Nvidia GP104 High Definition Audio Controller                              | 8        | 2.39%   |
| Nvidia GA104 High Definition Audio Controller                              | 8        | 2.39%   |
| Nvidia GA102 High Definition Audio Controller                              | 6        | 1.79%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6        | 1.79%   |
| Intel 200 Series PCH HD Audio                                              | 6        | 1.79%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 6        | 1.79%   |
| Nvidia TU116 High Definition Audio Controller                              | 5        | 1.49%   |
| Nvidia TU106 High Definition Audio Controller                              | 5        | 1.49%   |
| Nvidia TU104 HD Audio Controller                                           | 5        | 1.49%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5        | 1.49%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5        | 1.49%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5        | 1.49%   |
| AMD Navi 10 HDMI Audio                                                     | 5        | 1.49%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 5        | 1.49%   |
| Logitech PRO X Wireless Gaming Headset                                     | 4        | 1.19%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 4        | 1.19%   |
| AMD FCH Azalia Controller                                                  | 4        | 1.19%   |
| Nvidia GP106 High Definition Audio Controller                              | 3        | 0.9%    |
| Nvidia GM204 High Definition Audio Controller                              | 3        | 0.9%    |
| Intel Comet Lake PCH cAVS                                                  | 3        | 0.9%    |
| Intel C600/X79 series chipset High Definition Audio Controller             | 3        | 0.9%    |
| Intel Audio device                                                         | 3        | 0.9%    |
| Intel Alder Lake-S HD Audio Controller                                     | 3        | 0.9%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3        | 0.9%    |
| ASUSTek Computer USB Audio                                                 | 3        | 0.9%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3        | 0.9%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3        | 0.9%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2        | 0.6%    |
| Nvidia TU102 High Definition Audio Controller                              | 2        | 0.6%    |
| Nvidia MCP61 High Definition Audio                                         | 2        | 0.6%    |
| Nvidia GP108 High Definition Audio Controller                              | 2        | 0.6%    |
| Nvidia GP102 HDMI Audio Controller                                         | 2        | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 6        | 27.27%  |
| Kingston            | 3        | 13.64%  |
| G.Skill             | 3        | 13.64%  |
| Unknown             | 2        | 9.09%   |
| Team                | 2        | 9.09%   |
| Samsung Electronics | 2        | 9.09%   |
| SK hynix            | 1        | 4.55%   |
| Ramaxel Technology  | 1        | 4.55%   |
| Crucial             | 1        | 4.55%   |
| Asgard              | 1        | 4.55%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s  | 2        | 8%      |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s              | 1        | 4%      |
| Unknown RAM 2400 C15 Series 16384MB DIMM DDR4 2133MT/s | 1        | 4%      |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3733MT/s    | 1        | 4%      |
| Team RAM TEAMGROUP-UD3 8192MB DIMM DDR3 1600MT/s       | 1        | 4%      |
| SK hynix RAM HMT351S6EFR8A-PB 4GB DIMM DDR3 1600MT/s   | 1        | 4%      |
| Samsung RAM M471B5674EB0-YK0 2GB SODIMM DDR3 1600MT/s  | 1        | 4%      |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s  | 1        | 4%      |
| Samsung RAM M3 78T2863QZS-CF7 1GB DIMM DDR2 800MT/s    | 1        | 4%      |
| Ramaxel RAM RMR5030ED58E8W1600 2GB DIMM DDR3 1600MT/s  | 1        | 4%      |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s   | 1        | 4%      |
| Kingston RAM KHX2933C15D4/8GX 8GB DIMM DDR4 2933MT/s   | 1        | 4%      |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3200MT/s  | 1        | 4%      |
| G.Skill RAM F4-3600C16-8GTZNC 8GB DIMM DDR4 3800MT/s   | 1        | 4%      |
| G.Skill RAM F4-3600C14-8GTZNB 8GB DIMM DDR4 3600MT/s   | 1        | 4%      |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s    | 1        | 4%      |
| Crucial RAM BL16G32C16U4B.16FE 16GB DIMM DDR4 3200MT/s | 1        | 4%      |
| Corsair RAM CMZ16GX3M4A2133C11 4GB DIMM DDR3 1600MT/s  | 1        | 4%      |
| Corsair RAM CMY16GX3M2A1866C9 8GB DIMM DDR3 2400MT/s   | 1        | 4%      |
| Corsair RAM CMW32GX4M2Z2933C16 16GB DIMM DDR4 2933MT/s | 1        | 4%      |
| Corsair RAM CMK8GX4M1A2666C16 8GB DIMM DDR4 3000MT/s   | 1        | 4%      |
| Corsair RAM CMK8GX4M1A2400C14 8GB DIMM DDR4 2800MT/s   | 1        | 4%      |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s  | 1        | 4%      |
| Asgard RAM VMA45UG-MEC1U2AW2 8GB DIMM DDR4 3200MT/s    | 1        | 4%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR4  | 14       | 66.67%  |
| DDR3  | 6        | 28.57%  |
| SDRAM | 1        | 4.76%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 20       | 95.24%  |
| SODIMM | 1        | 4.76%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 11       | 50%     |
| 16384 | 3        | 13.64%  |
| 4096  | 3        | 13.64%  |
| 32768 | 2        | 9.09%   |
| 2048  | 2        | 9.09%   |
| 1024  | 1        | 4.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 5        | 20.83%  |
| 3600  | 4        | 16.67%  |
| 3200  | 3        | 12.5%   |
| 2933  | 2        | 8.33%   |
| 2400  | 2        | 8.33%   |
| 3866  | 1        | 4.17%   |
| 3800  | 1        | 4.17%   |
| 3733  | 1        | 4.17%   |
| 3466  | 1        | 4.17%   |
| 3000  | 1        | 4.17%   |
| 2800  | 1        | 4.17%   |
| 1066  | 1        | 4.17%   |
| 800   | 1        | 4.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Canon              | 2        | 50%     |
| Brother Industries | 2        | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                      | Desktops | Percent |
|----------------------------|----------|---------|
| Canon TR4500 series        | 1        | 25%     |
| Canon PIXMA MX370 Series   | 1        | 25%     |
| Brother MFC-L2710DN series | 1        | 25%     |
| Brother HL-L2370DW series  | 1        | 25%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model            | Desktops | Percent |
|------------------|----------|---------|
| HP ScanJet 2400c | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Logitech            | 15       | 46.88%  |
| Apple               | 3        | 9.38%   |
| Microsoft           | 2        | 6.25%   |
| Microdia            | 2        | 6.25%   |
| Hewlett-Packard     | 2        | 6.25%   |
| Chicony Electronics | 2        | 6.25%   |
| Samsung Electronics | 1        | 3.13%   |
| Owon                | 1        | 3.13%   |
| Lenovo              | 1        | 3.13%   |
| HD WEBCAM           | 1        | 3.13%   |
| ARC International   | 1        | 3.13%   |
| ANYKA               | 1        | 3.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Logitech C922 Pro Stream Webcam       | 5        | 15.63%  |
| Logitech Webcam C270                  | 3        | 9.38%   |
| Apple iPhone 5/5C/5S/6/SE             | 3        | 9.38%   |
| Microdia Laptop_Integrated_Webcam_FHD | 2        | 6.25%   |
| Logitech StreamCam                    | 2        | 6.25%   |
| Logitech HD Pro Webcam C920           | 2        | 6.25%   |
| Samsung Galaxy A5 (MTP)               | 1        | 3.13%   |
| Owon USB CAMERA                       | 1        | 3.13%   |
| Microsoft Xbox NUI Camera             | 1        | 3.13%   |
| Microsoft LifeCam Cinema              | 1        | 3.13%   |
| Logitech QuickCam Pro 9000            | 1        | 3.13%   |
| Logitech C920 PRO HD Webcam           | 1        | 3.13%   |
| Logitech BRIO 4K Stream Edition       | 1        | 3.13%   |
| Lenovo 500 RGB Camera                 | 1        | 3.13%   |
| HP Webcam HD-2200                     | 1        | 3.13%   |
| HP Webcam HD 2300                     | 1        | 3.13%   |
| HD WEBCAM Web Camera                  | 1        | 3.13%   |
| Chicony HP Webcam 2100                | 1        | 3.13%   |
| Chicony CNFA035                       | 1        | 3.13%   |
| ARC International Camera              | 1        | 3.13%   |
| ANYKA V380 FHD Camera                 | 1        | 3.13%   |

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
| 0     | 119      | 86.23%  |
| 1     | 18       | 13.04%  |
| 2     | 1        | 0.72%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 11       | 55%     |
| Graphics card            | 5        | 25%     |
| Unassigned class         | 1        | 5%      |
| Sound                    | 1        | 5%      |
| Multimedia controller    | 1        | 5%      |
| Communication controller | 1        | 5%      |

