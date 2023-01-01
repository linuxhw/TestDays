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

Total: 146

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
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
| Nobara 36 | 110      | 100%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Nobara | 110      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                       | Desktops | Percent |
|-------------------------------|----------|---------|
| 6.0.10-201.fc36.x86_64        | 15       | 13.04%  |
| 5.19.9-201.fsync.fc36.x86_64  | 8        | 6.96%   |
| 5.19.14-201.fsync.fc36.x86_64 | 8        | 6.96%   |
| 5.19.7-204.fsync.fc36.x86_64  | 7        | 6.09%   |
| 5.19.16-201.fsync.fc36.x86_64 | 7        | 6.09%   |
| 5.18.13-201.fsync.fc36.x86_64 | 7        | 6.09%   |
| 6.0.9-201.fc36.x86_64         | 6        | 5.22%   |
| 6.0.7-201.fsync.fc36.x86_64   | 6        | 5.22%   |
| 6.0.5-201.fsync.fc36.x86_64   | 6        | 5.22%   |
| 5.19.10-201.fsync.fc36.x86_64 | 6        | 5.22%   |
| 5.19.4-201.fsync.fc36.x86_64  | 4        | 3.48%   |
| 5.19.15-202.fsync.fc36.x86_64 | 4        | 3.48%   |
| 5.18.17-201.fsync.fc36.x86_64 | 4        | 3.48%   |
| 5.18.16-201.fsync.fc36.x86_64 | 4        | 3.48%   |
| 5.19.12-201.fsync.fc36.x86_64 | 3        | 2.61%   |
| 5.18.19-201.fsync.fc36.x86_64 | 3        | 2.61%   |
| 5.18.11-201.fsync.fc36.x86_64 | 3        | 2.61%   |
| 6.0.8-201.fsync.fc36.x86_64   | 2        | 1.74%   |
| 6.0.7-202.fsync.fc36.x86_64   | 2        | 1.74%   |
| 6.0.14-201.fsync.fc36.x86_64  | 2        | 1.74%   |
| 5.19.11-201.fsync.fc36.x86_64 | 2        | 1.74%   |
| 5.19.7-203.fsync.fc36.x86_64  | 1        | 0.87%   |
| 5.19.2-602.inttf.fc36.x86_64  | 1        | 0.87%   |
| 5.19.13-202.fsync.fc36.x86_64 | 1        | 0.87%   |
| 5.19.13-201.fsync.fc36.x86_64 | 1        | 0.87%   |
| 5.18.9-201.fsync.fc36.x86_64  | 1        | 0.87%   |
| 5.18.18-201.fsync.fc36.x86_64 | 1        | 0.87%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.0.10  | 15       | 13.04%  |
| 6.0.7   | 8        | 6.96%   |
| 5.19.9  | 8        | 6.96%   |
| 5.19.7  | 8        | 6.96%   |
| 5.19.14 | 8        | 6.96%   |
| 5.19.16 | 7        | 6.09%   |
| 5.18.13 | 7        | 6.09%   |
| 6.0.9   | 6        | 5.22%   |
| 6.0.5   | 6        | 5.22%   |
| 5.19.10 | 6        | 5.22%   |
| 5.19.4  | 4        | 3.48%   |
| 5.19.15 | 4        | 3.48%   |
| 5.18.17 | 4        | 3.48%   |
| 5.18.16 | 4        | 3.48%   |
| 5.19.12 | 3        | 2.61%   |
| 5.18.19 | 3        | 2.61%   |
| 5.18.11 | 3        | 2.61%   |
| 6.0.8   | 2        | 1.74%   |
| 6.0.14  | 2        | 1.74%   |
| 5.19.13 | 2        | 1.74%   |
| 5.19.11 | 2        | 1.74%   |
| 5.19.2  | 1        | 0.87%   |
| 5.18.9  | 1        | 0.87%   |
| 5.18.18 | 1        | 0.87%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.19    | 53       | 46.49%  |
| 6.0     | 38       | 33.33%  |
| 5.18    | 23       | 20.18%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 110      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 82       | 74.55%  |
| KDE5          | 25       | 22.73%  |
| GNOME Classic | 2        | 1.82%   |
| X-Cinnamon    | 1        | 0.91%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 80       | 70.8%   |
| X11     | 33       | 29.2%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 96       | 87.27%  |
| GDM     | 9        | 8.18%   |
| SDDM    | 4        | 3.64%   |
| LightDM | 1        | 0.91%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 62       | 55.86%  |
| en_GB   | 7        | 6.31%   |
| es_AR   | 5        | 4.5%    |
| es_ES   | 4        | 3.6%    |
| en_CA   | 4        | 3.6%    |
| de_DE   | 4        | 3.6%    |
| fr_FR   | 3        | 2.7%    |
| es_MX   | 3        | 2.7%    |
| ru_RU   | 2        | 1.8%    |
| pt_BR   | 2        | 1.8%    |
| es_CO   | 2        | 1.8%    |
| en_AU   | 2        | 1.8%    |
| sv_SE   | 1        | 0.9%    |
| sk_SK   | 1        | 0.9%    |
| nl_NL   | 1        | 0.9%    |
| fi_FI   | 1        | 0.9%    |
| es_GT   | 1        | 0.9%    |
| es_EC   | 1        | 0.9%    |
| en_NZ   | 1        | 0.9%    |
| de_AT   | 1        | 0.9%    |
| cs_CZ   | 1        | 0.9%    |
| C       | 1        | 0.9%    |
| Unknown | 1        | 0.9%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 79       | 71.82%  |
| BIOS | 31       | 28.18%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Btrfs | 57       | 51.82%  |
| Ext4  | 53       | 48.18%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 95       | 86.36%  |
| GPT     | 12       | 10.91%  |
| MBR     | 3        | 2.73%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 105      | 95.45%  |
| Yes       | 5        | 4.55%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 103      | 93.64%  |
| Yes       | 7        | 6.36%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 32       | 29.09%  |
| MSI                 | 22       | 20%     |
| Gigabyte Technology | 17       | 15.45%  |
| ASRock              | 12       | 10.91%  |
| Hewlett-Packard     | 7        | 6.36%   |
| Dell                | 7        | 6.36%   |
| Intel               | 3        | 2.73%   |
| Biostar             | 2        | 1.82%   |
| Alienware           | 2        | 1.82%   |
| OEM                 | 1        | 0.91%   |
| Lenovo              | 1        | 0.91%   |
| Fujitsu             | 1        | 0.91%   |
| eMachines           | 1        | 0.91%   |
| ECS                 | 1        | 0.91%   |
| Unknown             | 1        | 0.91%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| MSI MS-7C91                          | 3        | 2.73%   |
| ASUS PRIME A320M-K                   | 3        | 2.73%   |
| MSI MS-7C37                          | 2        | 1.82%   |
| MSI MS-7C02                          | 2        | 1.82%   |
| MSI MS-7B86                          | 2        | 1.82%   |
| MSI MS-7693                          | 2        | 1.82%   |
| Gigabyte Z590I VISION D              | 2        | 1.82%   |
| Gigabyte B450M DS3H                  | 2        | 1.82%   |
| Dell OptiPlex 390                    | 2        | 1.82%   |
| OEM SHARKBAY                         | 1        | 0.91%   |
| MSI MS-7D53                          | 1        | 0.91%   |
| MSI MS-7D41                          | 1        | 0.91%   |
| MSI MS-7D25                          | 1        | 0.91%   |
| MSI MS-7C84                          | 1        | 0.91%   |
| MSI MS-7C35                          | 1        | 0.91%   |
| MSI MS-7B51                          | 1        | 0.91%   |
| MSI MS-7B17                          | 1        | 0.91%   |
| MSI MS-7A34                          | 1        | 0.91%   |
| MSI MS-7811                          | 1        | 0.91%   |
| MSI MS-7721                          | 1        | 0.91%   |
| MSI MS-7597                          | 1        | 0.91%   |
| Lenovo ThinkCentre M92p 3238E5U      | 1        | 0.91%   |
| Intel X79                            | 1        | 0.91%   |
| Intel D33217GKE G76540-207           | 1        | 0.91%   |
| Intel B75                            | 1        | 0.91%   |
| HP Z420 Workstation                  | 1        | 0.91%   |
| HP Pavilion Gaming Desktop TG01-0xxx | 1        | 0.91%   |
| HP Pavilion Desktop TP01-2xxx        | 1        | 0.91%   |
| HP EliteDesk 800 G5 Desktop Mini     | 1        | 0.91%   |
| HP EliteDesk 800 G2 SFF              | 1        | 0.91%   |
| HP EliteDesk 800 G1 SFF              | 1        | 0.91%   |
| HP Compaq dc5850 Small Form Factor   | 1        | 0.91%   |
| Gigabyte Z97-HD3                     | 1        | 0.91%   |
| Gigabyte X570 I AORUS PRO WIFI       | 1        | 0.91%   |
| Gigabyte X570 AORUS ELITE            | 1        | 0.91%   |
| Gigabyte H81M-H                      | 1        | 0.91%   |
| Gigabyte H410M H V3                  | 1        | 0.91%   |
| Gigabyte H310M M.2 2.0               | 1        | 0.91%   |
| Gigabyte H270-Gaming 3               | 1        | 0.91%   |
| Gigabyte H110M-H                     | 1        | 0.91%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS PRIME           | 10       | 9.09%   |
| ASUS ROG             | 6        | 5.45%   |
| Dell OptiPlex        | 4        | 3.64%   |
| ASUS TUF             | 4        | 3.64%   |
| MSI MS-7C91          | 3        | 2.73%   |
| HP EliteDesk         | 3        | 2.73%   |
| MSI MS-7C37          | 2        | 1.82%   |
| MSI MS-7C02          | 2        | 1.82%   |
| MSI MS-7B86          | 2        | 1.82%   |
| MSI MS-7693          | 2        | 1.82%   |
| HP Pavilion          | 2        | 1.82%   |
| Gigabyte Z590I       | 2        | 1.82%   |
| Gigabyte X570        | 2        | 1.82%   |
| Gigabyte B450M       | 2        | 1.82%   |
| Dell Precision       | 2        | 1.82%   |
| ASUS M5A97           | 2        | 1.82%   |
| OEM SHARKBAY         | 1        | 0.91%   |
| MSI MS-7D53          | 1        | 0.91%   |
| MSI MS-7D41          | 1        | 0.91%   |
| MSI MS-7D25          | 1        | 0.91%   |
| MSI MS-7C84          | 1        | 0.91%   |
| MSI MS-7C35          | 1        | 0.91%   |
| MSI MS-7B51          | 1        | 0.91%   |
| MSI MS-7B17          | 1        | 0.91%   |
| MSI MS-7A34          | 1        | 0.91%   |
| MSI MS-7811          | 1        | 0.91%   |
| MSI MS-7721          | 1        | 0.91%   |
| MSI MS-7597          | 1        | 0.91%   |
| Lenovo ThinkCentre   | 1        | 0.91%   |
| Intel X79            | 1        | 0.91%   |
| Intel D33217GKE      | 1        | 0.91%   |
| Intel B75            | 1        | 0.91%   |
| HP Z420              | 1        | 0.91%   |
| HP Compaq            | 1        | 0.91%   |
| Gigabyte Z97-HD3     | 1        | 0.91%   |
| Gigabyte H81M-H      | 1        | 0.91%   |
| Gigabyte H410M       | 1        | 0.91%   |
| Gigabyte H310M       | 1        | 0.91%   |
| Gigabyte H270-Gaming | 1        | 0.91%   |
| Gigabyte H110M-H     | 1        | 0.91%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 23       | 20.91%  |
| 2013 | 12       | 10.91%  |
| 2021 | 11       | 10%     |
| 2018 | 10       | 9.09%   |
| 2017 | 9        | 8.18%   |
| 2020 | 8        | 7.27%   |
| 2014 | 8        | 7.27%   |
| 2011 | 7        | 6.36%   |
| 2012 | 6        | 5.45%   |
| 2016 | 5        | 4.55%   |
| 2022 | 4        | 3.64%   |
| 2015 | 3        | 2.73%   |
| 2008 | 2        | 1.82%   |
| 2010 | 1        | 0.91%   |
| 2009 | 1        | 0.91%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 110      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 110      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 110      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 45       | 40.91%  |
| 32.01-64.0  | 26       | 23.64%  |
| 8.01-16.0   | 18       | 16.36%  |
| 4.01-8.0    | 10       | 9.09%   |
| 3.01-4.0    | 7        | 6.36%   |
| 64.01-256.0 | 3        | 2.73%   |
| 24.01-32.0  | 1        | 0.91%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 51       | 44.35%  |
| 3.01-4.0   | 30       | 26.09%  |
| 2.01-3.0   | 14       | 12.17%  |
| 8.01-16.0  | 14       | 12.17%  |
| 1.01-2.0   | 3        | 2.61%   |
| 16.01-24.0 | 2        | 1.74%   |
| 24.01-32.0 | 1        | 0.87%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 33       | 29.73%  |
| 2      | 29       | 26.13%  |
| 3      | 28       | 25.23%  |
| 5      | 10       | 9.01%   |
| 4      | 7        | 6.31%   |
| 6      | 2        | 1.8%    |
| 10     | 1        | 0.9%    |
| 7      | 1        | 0.9%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 88       | 80%     |
| Yes       | 22       | 20%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 110      | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 56       | 50.91%  |
| Yes       | 54       | 49.09%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 60       | 54.05%  |
| Yes       | 51       | 45.95%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 38       | 34.55%  |
| Germany      | 6        | 5.45%   |
| France       | 6        | 5.45%   |
| Canada       | 6        | 5.45%   |
| Argentina    | 6        | 5.45%   |
| UK           | 5        | 4.55%   |
| Spain        | 3        | 2.73%   |
| Mexico       | 3        | 2.73%   |
| Brazil       | 3        | 2.73%   |
| Serbia       | 2        | 1.82%   |
| Russia       | 2        | 1.82%   |
| Netherlands  | 2        | 1.82%   |
| Hungary      | 2        | 1.82%   |
| Colombia     | 2        | 1.82%   |
| Chile        | 2        | 1.82%   |
| Australia    | 2        | 1.82%   |
| Venezuela    | 1        | 0.91%   |
| Sweden       | 1        | 0.91%   |
| South Korea  | 1        | 0.91%   |
| South Africa | 1        | 0.91%   |
| Slovakia     | 1        | 0.91%   |
| Portugal     | 1        | 0.91%   |
| Philippines  | 1        | 0.91%   |
| Norway       | 1        | 0.91%   |
| New Zealand  | 1        | 0.91%   |
| Lithuania    | 1        | 0.91%   |
| Jordan       | 1        | 0.91%   |
| Indonesia    | 1        | 0.91%   |
| Guatemala    | 1        | 0.91%   |
| Georgia      | 1        | 0.91%   |
| Finland      | 1        | 0.91%   |
| Ecuador      | 1        | 0.91%   |
| Czechia      | 1        | 0.91%   |
| Croatia      | 1        | 0.91%   |
| Belgium      | 1        | 0.91%   |
| Austria      | 1        | 0.91%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Buenos Aires      | 3        | 2.65%   |
| Philadelphia      | 2        | 1.77%   |
| Atlanta           | 2        | 1.77%   |
| Zagreb            | 1        | 0.88%   |
| Wooster           | 1        | 0.88%   |
| Wiesbaden         | 1        | 0.88%   |
| Wellington        | 1        | 0.88%   |
| Waldorf           | 1        | 0.88%   |
| Vineland          | 1        | 0.88%   |
| Vilnius           | 1        | 0.88%   |
| Villa Nueva       | 1        | 0.88%   |
| Valledupar        | 1        | 0.88%   |
| Thornhill         | 1        | 0.88%   |
| Tamworth          | 1        | 0.88%   |
| Tampere           | 1        | 0.88%   |
| Szeged            | 1        | 0.88%   |
| Serquigny         | 1        | 0.88%   |
| Seattle           | 1        | 0.88%   |
| Schruns           | 1        | 0.88%   |
| Satellite Beach   | 1        | 0.88%   |
| Sao Paulo         | 1        | 0.88%   |
| Santiago          | 1        | 0.88%   |
| San Jose          | 1        | 0.88%   |
| San Antonio       | 1        | 0.88%   |
| Salon-de-Provence | 1        | 0.88%   |
| Sacramento        | 1        | 0.88%   |
| Rotterdam         | 1        | 0.88%   |
| Richardson        | 1        | 0.88%   |
| Raleigh           | 1        | 0.88%   |
| Quito             | 1        | 0.88%   |
| Prague            | 1        | 0.88%   |
| Philipsburg       | 1        | 0.88%   |
| Perth             | 1        | 0.88%   |
| Paris             | 1        | 0.88%   |
| Palu              | 1        | 0.88%   |
| Osa               | 1        | 0.88%   |
| Orenburg          | 1        | 0.88%   |
| North Vancouver   | 1        | 0.88%   |
| Mount Pleasant    | 1        | 0.88%   |
| Monterrey         | 1        | 0.88%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 46       | 64     | 19.83%  |
| Samsung Electronics       | 37       | 61     | 15.95%  |
| Seagate                   | 34       | 47     | 14.66%  |
| Crucial                   | 18       | 22     | 7.76%   |
| Toshiba                   | 16       | 16     | 6.9%    |
| Kingston                  | 14       | 16     | 6.03%   |
| SanDisk                   | 13       | 14     | 5.6%    |
| Phison                    | 6        | 7      | 2.59%   |
| PNY                       | 5        | 8      | 2.16%   |
| Phison Electronics        | 5        | 5      | 2.16%   |
| Intel                     | 3        | 6      | 1.29%   |
| Hitachi                   | 3        | 3      | 1.29%   |
| ADATA Technology          | 3        | 3      | 1.29%   |
| Transcend                 | 2        | 2      | 0.86%   |
| Team                      | 2        | 2      | 0.86%   |
| Realtek Semiconductor     | 2        | 2      | 0.86%   |
| Micron/Crucial Technology | 2        | 2      | 0.86%   |
| Micron Technology         | 2        | 2      | 0.86%   |
| China                     | 2        | 2      | 0.86%   |
| XPG                       | 1        | 1      | 0.43%   |
| Verbatim                  | 1        | 1      | 0.43%   |
| Unknown                   | 1        | 1      | 0.43%   |
| SuperSSpeed               | 1        | 1      | 0.43%   |
| SPCC                      | 1        | 1      | 0.43%   |
| SK hynix                  | 1        | 1      | 0.43%   |
| Silicon Motion            | 1        | 1      | 0.43%   |
| OCZ                       | 1        | 1      | 0.43%   |
| MyDigitalSSD              | 1        | 1      | 0.43%   |
| Mushkin                   | 1        | 1      | 0.43%   |
| LITEONIT                  | 1        | 1      | 0.43%   |
| KIOXIA-EXCERIA            | 1        | 1      | 0.43%   |
| KIOXIA                    | 1        | 1      | 0.43%   |
| JMicron Technology        | 1        | 1      | 0.43%   |
| Foxline                   | 1        | 1      | 0.43%   |
| Apple                     | 1        | 1      | 0.43%   |
| A-DATA Technology         | 1        | 1      | 0.43%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Toshiba HDWD110 1TB                                 | 5        | 1.8%    |
| Samsung SSD 860 EVO 500GB                           | 5        | 1.8%    |
| Phison E12 NVMe Controller 1TB                      | 5        | 1.8%    |
| WDC WD10EZEX-08WN4A0 1TB                            | 4        | 1.44%   |
| Seagate ST2000DM008-2FR102 2TB                      | 4        | 1.44%   |
| Kingston SA400S37240G 240GB SSD                     | 4        | 1.44%   |
| Crucial CT1000MX500SSD1 1TB                         | 4        | 1.44%   |
| WDC WDBNCE5000PNC 500GB SSD                         | 3        | 1.08%   |
| Toshiba DT01ACA100 1TB                              | 3        | 1.08%   |
| Samsung SSD 850 EVO 500GB                           | 3        | 1.08%   |
| Samsung SSD 850 EVO 250GB                           | 3        | 1.08%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 3        | 1.08%   |
| Intel SSD 660P Series 1024GB                        | 3        | 1.08%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                    | 2        | 0.72%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 2        | 0.72%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 2        | 0.72%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                      | 2        | 0.72%   |
| WDC WD5000BEVT-75ZAT0 500GB                         | 2        | 0.72%   |
| WDC WD20EURS-63S48Y0 2TB                            | 2        | 0.72%   |
| WDC WD10JPCX-24UE4T0 1TB                            | 2        | 0.72%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 2        | 0.72%   |
| Seagate ST3500418AS 500GB                           | 2        | 0.72%   |
| Seagate ST3500414CS 500GB                           | 2        | 0.72%   |
| Seagate ST2000DX002-2DV164 2TB                      | 2        | 0.72%   |
| Seagate ST2000DM006-2DM164 2TB                      | 2        | 0.72%   |
| Seagate ST2000DM001-1ER164 2TB                      | 2        | 0.72%   |
| Sandisk WD Black SN850 1TB                          | 2        | 0.72%   |
| SanDisk SSD PLUS 240GB                              | 2        | 0.72%   |
| Samsung SSD 980 500GB                               | 2        | 0.72%   |
| Samsung SSD 860 EVO 1TB                             | 2        | 0.72%   |
| Samsung NVMe SSD Drive 1TB                          | 2        | 0.72%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 2        | 0.72%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 2        | 0.72%   |
| PNY CS900 500GB SSD                                 | 2        | 0.72%   |
| PNY CS900 1TB SSD                                   | 2        | 0.72%   |
| Phison Sabrent Rocket 4.0 2TB                       | 2        | 0.72%   |
| Phison NVMe SSD Drive 2TB                           | 2        | 0.72%   |
| Kingston SV300S37A240G 240GB SSD                    | 2        | 0.72%   |
| Kingston SA400S37120G 120GB SSD                     | 2        | 0.72%   |
| Kingston NVMe SSD Drive 500GB                       | 2        | 0.72%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 36       | 49     | 38.71%  |
| Seagate             | 34       | 45     | 36.56%  |
| Toshiba             | 13       | 13     | 13.98%  |
| Samsung Electronics | 6        | 9      | 6.45%   |
| Hitachi             | 3        | 3      | 3.23%   |
| Apple               | 1        | 1      | 1.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 24       | 29     | 24.49%  |
| Crucial             | 18       | 22     | 18.37%  |
| WDC                 | 12       | 13     | 12.24%  |
| Kingston            | 12       | 14     | 12.24%  |
| SanDisk             | 8        | 8      | 8.16%   |
| PNY                 | 5        | 8      | 5.1%    |
| Transcend           | 2        | 2      | 2.04%   |
| China               | 2        | 2      | 2.04%   |
| Verbatim            | 1        | 1      | 1.02%   |
| Toshiba             | 1        | 1      | 1.02%   |
| Team                | 1        | 1      | 1.02%   |
| SuperSSpeed         | 1        | 1      | 1.02%   |
| SPCC                | 1        | 1      | 1.02%   |
| Seagate             | 1        | 1      | 1.02%   |
| OCZ                 | 1        | 1      | 1.02%   |
| MyDigitalSSD        | 1        | 1      | 1.02%   |
| Mushkin             | 1        | 1      | 1.02%   |
| Micron Technology   | 1        | 1      | 1.02%   |
| LITEONIT            | 1        | 1      | 1.02%   |
| KIOXIA-EXCERIA      | 1        | 1      | 1.02%   |
| JMicron Technology  | 1        | 1      | 1.02%   |
| Foxline             | 1        | 1      | 1.02%   |
| A-DATA Technology   | 1        | 1      | 1.02%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 77       | 113    | 40.31%  |
| HDD     | 70       | 120    | 36.65%  |
| NVMe    | 41       | 65     | 21.47%  |
| Unknown | 2        | 2      | 1.05%   |
| MMC     | 1        | 1      | 0.52%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 100      | 227    | 67.11%  |
| NVMe | 41       | 65     | 27.52%  |
| SAS  | 7        | 8      | 4.7%    |
| MMC  | 1        | 1      | 0.67%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 74       | 105    | 42.77%  |
| 0.51-1.0   | 55       | 75     | 31.79%  |
| 1.01-2.0   | 24       | 33     | 13.87%  |
| 3.01-4.0   | 8        | 8      | 4.62%   |
| 2.01-3.0   | 6        | 6      | 3.47%   |
| 4.01-10.0  | 4        | 4      | 2.31%   |
| 10.01-20.0 | 2        | 2      | 1.16%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 30       | 27.27%  |
| 251-500        | 22       | 20%     |
| 1001-2000      | 18       | 16.36%  |
| 501-1000       | 17       | 15.45%  |
| More than 3000 | 14       | 12.73%  |
| 2001-3000      | 4        | 3.64%   |
| 51-100         | 3        | 2.73%   |
| 21-50          | 1        | 0.91%   |
| 1-20           | 1        | 0.91%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 21-50          | 28       | 24.35%  |
| 1-20           | 27       | 23.48%  |
| 51-100         | 15       | 13.04%  |
| 101-250        | 13       | 11.3%   |
| 251-500        | 10       | 8.7%    |
| 501-1000       | 10       | 8.7%    |
| 2001-3000      | 5        | 4.35%   |
| 1001-2000      | 4        | 3.48%   |
| More than 3000 | 3        | 2.61%   |

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
| Detected | 95       | 250    | 80.51%  |
| Works    | 14       | 41     | 11.86%  |
| Malfunc  | 8        | 9      | 6.78%   |
| Limited  | 1        | 1      | 0.85%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 55       | 32.16%  |
| AMD                          | 53       | 30.99%  |
| Samsung Electronics          | 16       | 9.36%   |
| Phison Electronics           | 11       | 6.43%   |
| ASMedia Technology           | 7        | 4.09%   |
| SanDisk                      | 6        | 3.51%   |
| Realtek Semiconductor        | 3        | 1.75%   |
| ADATA Technology             | 3        | 1.75%   |
| Nvidia                       | 2        | 1.17%   |
| Micron/Crucial Technology    | 2        | 1.17%   |
| Marvell Technology Group     | 2        | 1.17%   |
| Kingston Technology Company  | 2        | 1.17%   |
| JMicron Technology           | 2        | 1.17%   |
| Toshiba America Info Systems | 1        | 0.58%   |
| SK hynix                     | 1        | 0.58%   |
| Silicon Motion               | 1        | 0.58%   |
| Silicon Image                | 1        | 0.58%   |
| Micron Technology            | 1        | 0.58%   |
| KIOXIA                       | 1        | 0.58%   |
| Broadcom / LSI               | 1        | 0.58%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 32       | 15.69%  |
| AMD 400 Series Chipset SATA Controller                                                  | 13       | 6.37%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 9        | 4.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 7        | 3.43%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 7        | 3.43%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 7        | 3.43%   |
| Intel SATA Controller [RAID mode]                                                       | 6        | 2.94%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6        | 2.94%   |
| Phison E12 NVMe Controller                                                              | 5        | 2.45%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5        | 2.45%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 5        | 2.45%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5        | 2.45%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5        | 2.45%   |
| AMD 500 Series Chipset SATA Controller                                                  | 5        | 2.45%   |
| AMD FCH SATA Controller D                                                               | 4        | 1.96%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 3        | 1.47%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3        | 1.47%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 3        | 1.47%   |
| Intel SSD 660P Series                                                                   | 3        | 1.47%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 3        | 1.47%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3        | 1.47%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3        | 1.47%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 2        | 0.98%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2        | 0.98%   |
| Samsung NVMe SSD Controller 980                                                         | 2        | 0.98%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 2        | 0.98%   |
| Phison E18 PCIe4 NVMe Controller                                                        | 2        | 0.98%   |
| Nvidia MCP61 SATA Controller                                                            | 2        | 0.98%   |
| Nvidia MCP61 IDE                                                                        | 2        | 0.98%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 2        | 0.98%   |
| Kingston Company A2000 NVMe SSD                                                         | 2        | 0.98%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2        | 0.98%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 0.98%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2        | 0.98%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 0.98%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 0.98%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 0.98%   |
| ADATA ADATA XPG GAMMIXS1 1L Media                                                       | 2        | 0.98%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                                    | 1        | 0.49%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                          | 1        | 0.49%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 98       | 60.12%  |
| NVMe | 41       | 25.15%  |
| IDE  | 13       | 7.98%   |
| RAID | 9        | 5.52%   |
| SAS  | 2        | 1.23%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 55       | 50%     |
| AMD    | 55       | 50%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 2600 Six-Core Processor         | 5        | 4.55%   |
| AMD FX-8350 Eight-Core Processor            | 5        | 4.55%   |
| AMD Ryzen 5 3600 6-Core Processor           | 4        | 3.64%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 3        | 2.73%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 3        | 2.73%   |
| Intel 12th Gen Core i5-12600K               | 3        | 2.73%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 3        | 2.73%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 3        | 2.73%   |
| AMD FX-6300 Six-Core Processor              | 3        | 2.73%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 2        | 1.82%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 2        | 1.82%   |
| Intel Core i5-7600K CPU @ 3.80GHz           | 2        | 1.82%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 2        | 1.82%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 2        | 1.82%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2        | 1.82%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2        | 1.82%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 2        | 1.82%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 2        | 1.82%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 2        | 1.82%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 2        | 1.82%   |
| Intel Xeon CPU W3530 @ 2.80GHz              | 1        | 0.91%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz          | 1        | 0.91%   |
| Intel Xeon CPU E5-2667 v4 @ 3.20GHz         | 1        | 0.91%   |
| Intel Xeon CPU E5-2667 0 @ 2.90GHz          | 1        | 0.91%   |
| Intel Xeon CPU E3-1240 V2 @ 3.40GHz         | 1        | 0.91%   |
| Intel Pentium CPU G640 @ 2.80GHz            | 1        | 0.91%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1        | 0.91%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1        | 0.91%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1        | 0.91%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1        | 0.91%   |
| Intel Core i7-10700KF CPU @ 3.80GHz         | 1        | 0.91%   |
| Intel Core i7-10700F CPU @ 2.90GHz          | 1        | 0.91%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1        | 0.91%   |
| Intel Core i5-9500 CPU @ 3.00GHz            | 1        | 0.91%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 1        | 0.91%   |
| Intel Core i5-7600 CPU @ 3.50GHz            | 1        | 0.91%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1        | 0.91%   |
| Intel Core i5-4590T CPU @ 2.00GHz           | 1        | 0.91%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 1        | 0.91%   |
| Intel Core i5-3470T CPU @ 2.90GHz           | 1        | 0.91%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Desktops | Percent |
|----------------------|----------|---------|
| AMD Ryzen 5          | 21       | 19.09%  |
| Intel Core i5        | 18       | 16.36%  |
| Intel Core i7        | 11       | 10%     |
| Intel Core i3        | 9        | 8.18%   |
| AMD FX               | 9        | 8.18%   |
| AMD Ryzen 9          | 8        | 7.27%   |
| AMD Ryzen 7          | 7        | 6.36%   |
| Other                | 5        | 4.55%   |
| Intel Xeon           | 5        | 4.55%   |
| AMD Ryzen 3          | 3        | 2.73%   |
| Intel Core i9        | 2        | 1.82%   |
| Intel Core 2 Duo     | 2        | 1.82%   |
| AMD Phenom II X6     | 2        | 1.82%   |
| Intel Pentium        | 1        | 0.91%   |
| Intel Celeron        | 1        | 0.91%   |
| Intel Atom           | 1        | 0.91%   |
| AMD Phenom II X4     | 1        | 0.91%   |
| AMD Athlon X4        | 1        | 0.91%   |
| AMD Athlon Dual Core | 1        | 0.91%   |
| AMD A6               | 1        | 0.91%   |
| AMD A10              | 1        | 0.91%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 33       | 30%     |
| 6      | 31       | 28.18%  |
| 2      | 17       | 15.45%  |
| 8      | 14       | 12.73%  |
| 12     | 6        | 5.45%   |
| 10     | 3        | 2.73%   |
| 3      | 3        | 2.73%   |
| 16     | 2        | 1.82%   |
| 1      | 1        | 0.91%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 109      | 99.09%  |
| 2      | 1        | 0.91%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 82       | 74.55%  |
| 1      | 28       | 25.45%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 110      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x08701021 | 12       | 10.91%  |
| 0x306c3    | 9        | 8.18%   |
| 0x06000822 | 8        | 7.27%   |
| 0x306a9    | 7        | 6.36%   |
| 0x0800820d | 6        | 5.45%   |
| 0x206a7    | 5        | 4.55%   |
| 0x0a201016 | 5        | 4.55%   |
| 0x906ea    | 4        | 3.64%   |
| 0x08001138 | 4        | 3.64%   |
| Unknown    | 4        | 3.64%   |
| 0xa0655    | 3        | 2.73%   |
| 0x906e9    | 3        | 2.73%   |
| 0x90672    | 3        | 2.73%   |
| 0x506e3    | 3        | 2.73%   |
| 0x08108109 | 3        | 2.73%   |
| 0xa0653    | 2        | 1.82%   |
| 0x906ed    | 2        | 1.82%   |
| 0x906ec    | 2        | 1.82%   |
| 0x206d7    | 2        | 1.82%   |
| 0x1067a    | 2        | 1.82%   |
| 0x0a50000c | 2        | 1.82%   |
| 0x0a201204 | 2        | 1.82%   |
| 0x06003106 | 2        | 1.82%   |
| 0x010000bf | 2        | 1.82%   |
| 0xa0671    | 1        | 0.91%   |
| 0x406f1    | 1        | 0.91%   |
| 0x406c4    | 1        | 0.91%   |
| 0x40651    | 1        | 0.91%   |
| 0x106a5    | 1        | 0.91%   |
| 0x0a50000d | 1        | 0.91%   |
| 0x0a201205 | 1        | 0.91%   |
| 0x0a201009 | 1        | 0.91%   |
| 0x08701013 | 1        | 0.91%   |
| 0x08108102 | 1        | 0.91%   |
| 0x06001119 | 1        | 0.91%   |
| 0x06000817 | 1        | 0.91%   |
| 0x01000086 | 1        | 0.91%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 13       | 11.82%  |
| Zen 3            | 12       | 10.91%  |
| KabyLake         | 12       | 10.91%  |
| Zen+             | 10       | 9.09%   |
| Piledriver       | 10       | 9.09%   |
| Haswell          | 10       | 9.09%   |
| SandyBridge      | 8        | 7.27%   |
| IvyBridge        | 7        | 6.36%   |
| CometLake        | 5        | 4.55%   |
| Zen              | 4        | 3.64%   |
| Skylake          | 3        | 2.73%   |
| K10              | 3        | 2.73%   |
| Alderlake Hybrid | 3        | 2.73%   |
| Steamroller      | 2        | 1.82%   |
| Penryn           | 2        | 1.82%   |
| Silvermont       | 1        | 0.91%   |
| Nehalem          | 1        | 0.91%   |
| K8 Hammer        | 1        | 0.91%   |
| Icelake          | 1        | 0.91%   |
| Broadwell        | 1        | 0.91%   |
| Unknown          | 1        | 0.91%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 54       | 45.38%  |
| AMD    | 46       | 38.66%  |
| Intel  | 19       | 15.97%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 12       | 9.76%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 4        | 3.25%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                        | 4        | 3.25%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 4        | 3.25%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 3        | 2.44%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 2.44%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3        | 2.44%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3        | 2.44%   |
| Intel AlderLake-S GT1                                                       | 3        | 2.44%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 2.44%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 1.63%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 2        | 1.63%   |
| Nvidia TU104 [GeForce RTX 2060]                                             | 2        | 1.63%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 1.63%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 2        | 1.63%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2        | 1.63%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 2        | 1.63%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 2        | 1.63%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 2        | 1.63%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 2        | 1.63%   |
| Intel HD Graphics 530                                                       | 2        | 1.63%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 1.63%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.63%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 2        | 1.63%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2        | 1.63%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 1.63%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 0.81%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.81%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 0.81%   |
| Nvidia TU104GL [Quadro RTX 4000]                                            | 1        | 0.81%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 0.81%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 1        | 0.81%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 0.81%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 0.81%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 0.81%   |
| Nvidia GP104 [GeForce GTX 1060 3GB]                                         | 1        | 0.81%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 0.81%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1        | 0.81%   |
| Nvidia GM204 [GeForce GTX 980]                                              | 1        | 0.81%   |
| Nvidia GM107M [GeForce GTX 860M]                                            | 1        | 0.81%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x Nvidia   | 51       | 46.36%  |
| 1 x AMD      | 41       | 37.27%  |
| 1 x Intel    | 12       | 10.91%  |
| 2 x Nvidia   | 2        | 1.82%   |
| Intel + AMD  | 2        | 1.82%   |
| 2 x AMD      | 1        | 0.91%   |
| AMD + Nvidia | 1        | 0.91%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 68       | 61.82%  |
| Proprietary | 41       | 37.27%  |
| Unknown     | 1        | 0.91%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 36       | 32.43%  |
| 7.01-8.0   | 23       | 20.72%  |
| 3.01-4.0   | 15       | 13.51%  |
| 1.01-2.0   | 13       | 11.71%  |
| 8.01-16.0  | 9        | 8.11%   |
| 0.51-1.0   | 6        | 5.41%   |
| 0.01-0.5   | 4        | 3.6%    |
| 5.01-6.0   | 2        | 1.8%    |
| 2.01-3.0   | 2        | 1.8%    |
| 16.01-24.0 | 1        | 0.9%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 18       | 15.65%  |
| Goldstar             | 13       | 11.3%   |
| Dell                 | 9        | 7.83%   |
| Acer                 | 9        | 7.83%   |
| Ancor Communications | 8        | 6.96%   |
| ASUSTek Computer     | 7        | 6.09%   |
| BenQ                 | 6        | 5.22%   |
| AOC                  | 6        | 5.22%   |
| Vizio                | 5        | 4.35%   |
| Hewlett-Packard      | 5        | 4.35%   |
| Sony                 | 4        | 3.48%   |
| Philips              | 4        | 3.48%   |
| MSI                  | 4        | 3.48%   |
| ViewSonic            | 2        | 1.74%   |
| Sceptre Tech         | 2        | 1.74%   |
| Lenovo               | 2        | 1.74%   |
| Gigabyte Technology  | 2        | 1.74%   |
| Toshiba              | 1        | 0.87%   |
| SNC                  | 1        | 0.87%   |
| SFX                  | 1        | 0.87%   |
| PRI                  | 1        | 0.87%   |
| NPC                  | 1        | 0.87%   |
| MStar                | 1        | 0.87%   |
| HUAWEI               | 1        | 0.87%   |
| Hitachi              | 1        | 0.87%   |
| GDH                  | 1        | 0.87%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch       | 2        | 1.57%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 2        | 1.57%   |
| Goldstar ULTRAGEAR GSM7766 2560x1440 697x392mm 31.5-inch                | 2        | 1.57%   |
| ASUSTek Computer ROG XG27UQR AUS27BA 3840x2160 596x335mm 26.9-inch      | 2        | 1.57%   |
| ASUSTek Computer PA278QV AUS2700 2560x1440 597x336mm 27.0-inch          | 2        | 1.57%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch   | 2        | 1.57%   |
| Vizio VX42L HDTV10A VIZ0030 1280x720 930x523mm 42.0-inch                | 1        | 0.79%   |
| Vizio M65Q6-J09 VIZ1039 3840x2160 1428x803mm 64.5-inch                  | 1        | 0.79%   |
| Vizio E500i-A0 VIZ0092 1920x1080 1096x616mm 49.5-inch                   | 1        | 0.79%   |
| Vizio E50-C1 VIZ1004 1920x1080 1095x616mm 49.5-inch                     | 1        | 0.79%   |
| Vizio D24h-G9 VIZ1028 1360x768 521x293mm 23.5-inch                      | 1        | 0.79%   |
| ViewSonic XG2401 SERIES VSCBB31 1920x1080 531x299mm 24.0-inch           | 1        | 0.79%   |
| ViewSonic VX3218-PC-mhd VSCEB3A 1920x1080 609x348mm 27.6-inch           | 1        | 0.79%   |
| Toshiba LCD-MONITOR LCDE980 1440x900 408x255mm 18.9-inch                | 1        | 0.79%   |
| Sony TV SNYEB01 1360x768                                                | 1        | 0.79%   |
| Sony TV SNY8F03 1360x768                                                | 1        | 0.79%   |
| Sony TV *00 SNYF303 1920x1080 1218x685mm 55.0-inch                      | 1        | 0.79%   |
| Sony SDM-HS75P SNY2200 1280x1024 338x270mm 17.0-inch                    | 1        | 0.79%   |
| SNC SKP_E20-32 SNC3200 1920x1080 477x268mm 21.5-inch                    | 1        | 0.79%   |
| SFX HDMI2.0 KVM SFX0100 1920x1080 708x398mm 32.0-inch                   | 1        | 0.79%   |
| Sceptre Tech Sceptre Y40 SPT0FCD 2560x1440 852x480mm 38.5-inch          | 1        | 0.79%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x291mm 29.5-inch          | 1        | 0.79%   |
| Sceptre Tech Sceptre M27 SPT0ACD 1920x1080 598x336mm 27.0-inch          | 1        | 0.79%   |
| Samsung Electronics U32J59x SAM0F34 3840x2160 697x392mm 31.5-inch       | 1        | 0.79%   |
| Samsung Electronics U28D590 SAM0B80 3840x2160 607x345mm 27.5-inch       | 1        | 0.79%   |
| Samsung Electronics SyncMaster SAM0422 1920x1200 518x324mm 24.1-inch    | 1        | 0.79%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch    | 1        | 0.79%   |
| Samsung Electronics SyncMaster SAM0168 1280x1024 338x270mm 17.0-inch    | 1        | 0.79%   |
| Samsung Electronics SMB2030N SAM0634 1600x900 443x249mm 20.0-inch       | 1        | 0.79%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 600x340mm 27.2-inch       | 1        | 0.79%   |
| Samsung Electronics S24E650 SAM0C86 1920x1200 518x324mm 24.1-inch       | 1        | 0.79%   |
| Samsung Electronics S24B300 SAM08CC 1920x1080 521x293mm 23.5-inch       | 1        | 0.79%   |
| Samsung Electronics LCD Monitor SAM7129 3840x2160 1020x570mm 46.0-inch  | 1        | 0.79%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 950x540mm 43.0-inch   | 1        | 0.79%   |
| Samsung Electronics LCD Monitor SAM0FA5 3840x2160 1872x1053mm 84.6-inch | 1        | 0.79%   |
| Samsung Electronics LCD Monitor SAM0B7C 1920x1080 890x500mm 40.2-inch   | 1        | 0.79%   |
| Samsung Electronics LCD Monitor SAM0B54 1366x768 609x347mm 27.6-inch    | 1        | 0.79%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 1060x626mm 48.5-inch  | 1        | 0.79%   |
| Samsung Electronics LCD Monitor SAM090B 1920x1080 1020x570mm 46.0-inch  | 1        | 0.79%   |
| Samsung Electronics LC27G5xT SAM7079 2560x1440 597x336mm 27.0-inch      | 1        | 0.79%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 55       | 47.01%  |
| 3840x2160 (4K)     | 21       | 17.95%  |
| 2560x1440 (QHD)    | 18       | 15.38%  |
| 2560x1080          | 3        | 2.56%   |
| 1680x1050 (WSXGA+) | 3        | 2.56%   |
| 1600x900 (HD+)     | 3        | 2.56%   |
| 1360x768           | 3        | 2.56%   |
| 3440x1440          | 2        | 1.71%   |
| 1440x900 (WXGA+)   | 2        | 1.71%   |
| 1366x768 (WXGA)    | 2        | 1.71%   |
| 1280x1024 (SXGA)   | 2        | 1.71%   |
| 3840x2560          | 1        | 0.85%   |
| 3840x1600          | 1        | 0.85%   |
| 1920x1200 (WUXGA)  | 1        | 0.85%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 28       | 23.14%  |
| 23      | 15       | 12.4%   |
| 24      | 12       | 9.92%   |
| 21      | 12       | 9.92%   |
| 31      | 10       | 8.26%   |
| 84      | 4        | 3.31%   |
| 19      | 4        | 3.31%   |
| 34      | 3        | 2.48%   |
| 26      | 3        | 2.48%   |
| 72      | 2        | 1.65%   |
| 52      | 2        | 1.65%   |
| 42      | 2        | 1.65%   |
| 38      | 2        | 1.65%   |
| 28      | 2        | 1.65%   |
| 22      | 2        | 1.65%   |
| 20      | 2        | 1.65%   |
| 17      | 2        | 1.65%   |
| 75      | 1        | 0.83%   |
| 69      | 1        | 0.83%   |
| 60      | 1        | 0.83%   |
| 58      | 1        | 0.83%   |
| 54      | 1        | 0.83%   |
| 49      | 1        | 0.83%   |
| 48      | 1        | 0.83%   |
| 37      | 1        | 0.83%   |
| 33      | 1        | 0.83%   |
| 32      | 1        | 0.83%   |
| 29      | 1        | 0.83%   |
| 18      | 1        | 0.83%   |
| 14      | 1        | 0.83%   |
| Unknown | 1        | 0.83%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 51       | 44.35%  |
| 401-500     | 21       | 18.26%  |
| 601-700     | 14       | 12.17%  |
| 1501-2000   | 8        | 6.96%   |
| 1001-1500   | 7        | 6.09%   |
| 701-800     | 5        | 4.35%   |
| 801-900     | 3        | 2.61%   |
| 301-350     | 2        | 1.74%   |
| 901-1000    | 2        | 1.74%   |
| 201-300     | 1        | 0.87%   |
| Unknown     | 1        | 0.87%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 82       | 81.19%  |
| 16/10 | 8        | 7.92%   |
| 21/9  | 6        | 5.94%   |
| 5/4   | 2        | 1.98%   |
| 4/3   | 2        | 1.98%   |
| 3/2   | 1        | 0.99%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 34       | 28.57%  |
| 301-350        | 31       | 26.05%  |
| 351-500        | 16       | 13.45%  |
| More than 1000 | 15       | 12.61%  |
| 151-200        | 10       | 8.4%    |
| 501-1000       | 5        | 4.2%    |
| 251-300        | 4        | 3.36%   |
| 141-150        | 2        | 1.68%   |
| 101-110        | 1        | 0.84%   |
| Unknown        | 1        | 0.84%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 65       | 58.04%  |
| 101-120 | 26       | 23.21%  |
| 1-50    | 11       | 9.82%   |
| 161-240 | 5        | 4.46%   |
| 121-160 | 4        | 3.57%   |
| Unknown | 1        | 0.89%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 79       | 71.82%  |
| 2     | 23       | 20.91%  |
| 0     | 4        | 3.64%   |
| 3     | 3        | 2.73%   |
| 4     | 1        | 0.91%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 71       | 45.51%  |
| Intel                           | 51       | 32.69%  |
| TP-Link                         | 7        | 4.49%   |
| Qualcomm Atheros                | 7        | 4.49%   |
| MediaTek                        | 3        | 1.92%   |
| Broadcom                        | 3        | 1.92%   |
| Microsoft                       | 2        | 1.28%   |
| Broadcom Limited                | 2        | 1.28%   |
| Wacom                           | 1        | 0.64%   |
| T & A Mobile Phones             | 1        | 0.64%   |
| Ralink Technology               | 1        | 0.64%   |
| Ralink                          | 1        | 0.64%   |
| Qualcomm Atheros Communications | 1        | 0.64%   |
| Linksys                         | 1        | 0.64%   |
| ICS Advent                      | 1        | 0.64%   |
| Holtek Semiconductor            | 1        | 0.64%   |
| D-Link                          | 1        | 0.64%   |
| ASUSTek Computer                | 1        | 0.64%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 58       | 32.4%   |
| Intel Wi-Fi 6 AX200                                               | 15       | 8.38%   |
| Realtek RTL8125 2.5GbE Controller                                 | 11       | 6.15%   |
| Intel I211 Gigabit Network Connection                             | 10       | 5.59%   |
| Intel Ethernet Controller I225-V                                  | 6        | 3.35%   |
| Intel Ethernet Connection (7) I219-V                              | 5        | 2.79%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 3        | 1.68%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3        | 1.68%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 1.68%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 1.68%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 2        | 1.12%   |
| TP-Link 802.11ac NIC                                              | 2        | 1.12%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2        | 1.12%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 2        | 1.12%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2        | 1.12%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 2        | 1.12%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2        | 1.12%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 1.12%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 1.12%   |
| Intel Ethernet Connection (14) I219-V                             | 2        | 1.12%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 2        | 1.12%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 2        | 1.12%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                          | 1        | 0.56%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1        | 0.56%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 1        | 0.56%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1        | 0.56%   |
| T & A Mobile Phones ALCATEL ONETOUCH PIXI 3 (4)                   | 1        | 0.56%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1        | 0.56%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.56%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 1        | 0.56%   |
| Realtek RTL8150 Fast Ethernet Adapter                             | 1        | 0.56%   |
| Realtek 802.11ac NIC                                              | 1        | 0.56%   |
| Ralink MT7601U Wireless Adapter                                   | 1        | 0.56%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 1        | 0.56%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.56%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.56%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.56%   |
| Qualcomm Atheros AR9271 802.11n                                   | 1        | 0.56%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1        | 0.56%   |
| Microsoft Xbox 360 Wireless Adapter                               | 1        | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 23       | 38.98%  |
| Realtek Semiconductor           | 13       | 22.03%  |
| TP-Link                         | 7        | 11.86%  |
| MediaTek                        | 3        | 5.08%   |
| Microsoft                       | 2        | 3.39%   |
| Broadcom                        | 2        | 3.39%   |
| Wacom                           | 1        | 1.69%   |
| Ralink Technology               | 1        | 1.69%   |
| Ralink                          | 1        | 1.69%   |
| Qualcomm Atheros Communications | 1        | 1.69%   |
| Qualcomm Atheros                | 1        | 1.69%   |
| Linksys                         | 1        | 1.69%   |
| D-Link                          | 1        | 1.69%   |
| Broadcom Limited                | 1        | 1.69%   |
| ASUSTek Computer                | 1        | 1.69%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                           | 15       | 25.42%  |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter      | 3        | 5.08%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                        | 2        | 3.39%   |
| TP-Link 802.11ac NIC                                          | 2        | 3.39%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 2        | 3.39%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter         | 2        | 3.39%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 2        | 3.39%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 2        | 3.39%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 2        | 3.39%   |
| Intel Alder Lake-S PCH CNVi WiFi                              | 2        | 3.39%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter            | 2        | 3.39%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                      | 1        | 1.69%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                   | 1        | 1.69%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                           | 1        | 1.69%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                  | 1        | 1.69%   |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 1        | 1.69%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter      | 1        | 1.69%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter       | 1        | 1.69%   |
| Realtek 802.11ac NIC                                          | 1        | 1.69%   |
| Ralink MT7601U Wireless Adapter                               | 1        | 1.69%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                     | 1        | 1.69%   |
| Qualcomm Atheros AR9271 802.11n                               | 1        | 1.69%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter              | 1        | 1.69%   |
| Microsoft Xbox 360 Wireless Adapter                           | 1        | 1.69%   |
| Microsoft Wireless XBox Controller Dongle                     | 1        | 1.69%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 1        | 1.69%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter           | 1        | 1.69%   |
| Intel Wireless 7265                                           | 1        | 1.69%   |
| Intel Wireless 3165                                           | 1        | 1.69%   |
| Intel Centrino Wireless-N 2200                                | 1        | 1.69%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 1        | 1.69%   |
| D-Link 802.11ac NIC                                           | 1        | 1.69%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter    | 1        | 1.69%   |
| ASUS 802.11ac WLAN                                            | 1        | 1.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 67       | 58.26%  |
| Intel                 | 38       | 33.04%  |
| Qualcomm Atheros      | 6        | 5.22%   |
| T & A Mobile Phones   | 1        | 0.87%   |
| ICS Advent            | 1        | 0.87%   |
| Broadcom Limited      | 1        | 0.87%   |
| Broadcom              | 1        | 0.87%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 58       | 48.74%  |
| Realtek RTL8125 2.5GbE Controller                                 | 11       | 9.24%   |
| Intel I211 Gigabit Network Connection                             | 10       | 8.4%    |
| Intel Ethernet Controller I225-V                                  | 6        | 5.04%   |
| Intel Ethernet Connection (7) I219-V                              | 5        | 4.2%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3        | 2.52%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 2.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 2.52%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 1.68%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 1.68%   |
| Intel Ethernet Connection (14) I219-V                             | 2        | 1.68%   |
| T & A Mobile Phones ALCATEL ONETOUCH PIXI 3 (4)                   | 1        | 0.84%   |
| Realtek RTL8150 Fast Ethernet Adapter                             | 1        | 0.84%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.84%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.84%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.84%   |
| Intel I210 Gigabit Network Connection                             | 1        | 0.84%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.84%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 0.84%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 0.84%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 0.84%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 0.84%   |
| ICS Advent USB 10/100 LAN                                         | 1        | 0.84%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 0.84%   |
| Broadcom Limited NetXtreme BCM5754 Gigabit Ethernet PCI Express   | 1        | 0.84%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 110      | 66.67%  |
| WiFi     | 54       | 32.73%  |
| Unknown  | 1        | 0.61%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 88       | 75.21%  |
| WiFi     | 29       | 24.79%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 69       | 62.73%  |
| 2     | 40       | 36.36%  |
| 3     | 1        | 0.91%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 70       | 62.5%   |
| Yes  | 42       | 37.5%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 22       | 43.14%  |
| Cambridge Silicon Radio | 11       | 21.57%  |
| Broadcom                | 5        | 9.8%    |
| Realtek Semiconductor   | 3        | 5.88%   |
| MediaTek                | 2        | 3.92%   |
| IMC Networks            | 2        | 3.92%   |
| ASUSTek Computer        | 2        | 3.92%   |
| TP-Link                 | 1        | 1.96%   |
| Foxconn / Hon Hai       | 1        | 1.96%   |
| Dell                    | 1        | 1.96%   |
| Unknown                 | 1        | 1.96%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 15       | 29.41%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 11       | 21.57%  |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 3        | 5.88%   |
| Realtek Bluetooth Radio                             | 2        | 3.92%   |
| MediaTek Wireless_Device                            | 2        | 3.92%   |
| Intel Bluetooth wireless interface                  | 2        | 3.92%   |
| Intel AX210 Bluetooth                               | 2        | 3.92%   |
| ASUS Bluetooth Device                               | 2        | 3.92%   |
| TP-Link UB500 Adapter                               | 1        | 1.96%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 1.96%   |
| Intel Bluetooth Device                              | 1        | 1.96%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 1.96%   |
| Intel AX201 Bluetooth                               | 1        | 1.96%   |
| IMC Networks Wireless_Device                        | 1        | 1.96%   |
| IMC Networks Bluetooth Radio                        | 1        | 1.96%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1        | 1.96%   |
| Dell Broadcom BCM20702A0 Bluetooth                  | 1        | 1.96%   |
| Broadcom Bluetooth Device                           | 1        | 1.96%   |
| Broadcom BCM2045 Bluetooth                          | 1        | 1.96%   |
| Unknown                                             | 1        | 1.96%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| AMD                      | 68       | 30.36%  |
| Nvidia                   | 54       | 24.11%  |
| Intel                    | 52       | 23.21%  |
| C-Media Electronics      | 10       | 4.46%   |
| Razer USA                | 4        | 1.79%   |
| Logitech                 | 4        | 1.79%   |
| Plantronics              | 3        | 1.34%   |
| Kingston Technology      | 3        | 1.34%   |
| JMTek                    | 3        | 1.34%   |
| Samson Technologies      | 2        | 0.89%   |
| Focusrite-Novation       | 2        | 0.89%   |
| Creative Technology      | 2        | 0.89%   |
| Creative Labs            | 2        | 0.89%   |
| ASUSTek Computer         | 2        | 0.89%   |
| Texas Instruments        | 1        | 0.45%   |
| SteelSeries ApS          | 1        | 0.45%   |
| ROCCAT                   | 1        | 0.45%   |
| Realtek Semiconductor    | 1        | 0.45%   |
| Positive Grid            | 1        | 0.45%   |
| Micro Star International | 1        | 0.45%   |
| Giga-Byte Technology     | 1        | 0.45%   |
| Generalplus Technology   | 1        | 0.45%   |
| Elgato Systems           | 1        | 0.45%   |
| Corsair                  | 1        | 0.45%   |
| Blue Microphones         | 1        | 0.45%   |
| Audio-Technica           | 1        | 0.45%   |
| Asahi Kasei Microsystems | 1        | 0.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 22       | 8.33%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 12       | 4.55%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 12       | 4.55%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 11       | 4.17%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 10       | 3.79%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 9        | 3.41%   |
| Intel Cannon Lake PCH cAVS                                                 | 7        | 2.65%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6        | 2.27%   |
| AMD Family 17h/19h HD Audio Controller                                     | 6        | 2.27%   |
| Intel 200 Series PCH HD Audio                                              | 5        | 1.89%   |
| AMD Navi 10 HDMI Audio                                                     | 5        | 1.89%   |
| Nvidia TU116 High Definition Audio Controller                              | 4        | 1.52%   |
| Nvidia TU106 High Definition Audio Controller                              | 4        | 1.52%   |
| Nvidia TU104 HD Audio Controller                                           | 4        | 1.52%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4        | 1.52%   |
| Nvidia GP104 High Definition Audio Controller                              | 4        | 1.52%   |
| Nvidia GA104 High Definition Audio Controller                              | 4        | 1.52%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4        | 1.52%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4        | 1.52%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4        | 1.52%   |
| Nvidia GP106 High Definition Audio Controller                              | 3        | 1.14%   |
| Nvidia GM204 High Definition Audio Controller                              | 3        | 1.14%   |
| Nvidia GA102 High Definition Audio Controller                              | 3        | 1.14%   |
| Logitech PRO X Wireless Gaming Headset                                     | 3        | 1.14%   |
| JMTek USB PnP Audio Device                                                 | 3        | 1.14%   |
| Intel Audio device                                                         | 3        | 1.14%   |
| Intel Alder Lake-S HD Audio Controller                                     | 3        | 1.14%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 3        | 1.14%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3        | 1.14%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3        | 1.14%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3        | 1.14%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3        | 1.14%   |
| AMD FCH Azalia Controller                                                  | 3        | 1.14%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2        | 0.76%   |
| Nvidia MCP61 High Definition Audio                                         | 2        | 0.76%   |
| Nvidia GP108 High Definition Audio Controller                              | 2        | 0.76%   |
| Nvidia GP102 HDMI Audio Controller                                         | 2        | 0.76%   |
| Nvidia GM206 High Definition Audio Controller                              | 2        | 0.76%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2        | 0.76%   |
| Nvidia GK104 HDMI Audio Controller                                         | 2        | 0.76%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 5        | 26.32%  |
| G.Skill             | 3        | 15.79%  |
| Unknown             | 2        | 10.53%  |
| Samsung Electronics | 2        | 10.53%  |
| Kingston            | 2        | 10.53%  |
| Team                | 1        | 5.26%   |
| SK hynix            | 1        | 5.26%   |
| Ramaxel Technology  | 1        | 5.26%   |
| Crucial             | 1        | 5.26%   |
| Asgard              | 1        | 5.26%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s  | 2        | 9.52%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s              | 1        | 4.76%   |
| Unknown RAM 2400 C15 Series 16384MB DIMM DDR4 2133MT/s | 1        | 4.76%   |
| Team RAM TEAMGROUP-UD3 8GB DIMM DDR3 1600MT/s          | 1        | 4.76%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB DIMM DDR3 1600MT/s   | 1        | 4.76%   |
| Samsung RAM M471B5674EB0-YK0 2GB SODIMM DDR3 1600MT/s  | 1        | 4.76%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s  | 1        | 4.76%   |
| Samsung RAM M3 78T2863QZS-CF7 1GB DIMM DDR2 800MT/s    | 1        | 4.76%   |
| Ramaxel RAM RMR5030ED58E8W1600 2GB DIMM DDR3 1600MT/s  | 1        | 4.76%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s   | 1        | 4.76%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3200MT/s  | 1        | 4.76%   |
| G.Skill RAM F4-3600C16-8GTZNC 8GB DIMM DDR4 3800MT/s   | 1        | 4.76%   |
| G.Skill RAM F4-3600C14-8GTZNB 8GB DIMM DDR4 3600MT/s   | 1        | 4.76%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s    | 1        | 4.76%   |
| Crucial RAM BL16G32C16U4B.16FE 16GB DIMM DDR4 3200MT/s | 1        | 4.76%   |
| Corsair RAM CMZ16GX3M4A2133C11 4GB DIMM DDR3 1600MT/s  | 1        | 4.76%   |
| Corsair RAM CMY16GX3M2A1866C9 8GB DIMM DDR3 2400MT/s   | 1        | 4.76%   |
| Corsair RAM CMW32GX4M2Z2933C16 16GB DIMM DDR4 2933MT/s | 1        | 4.76%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s  | 1        | 4.76%   |
| Asgard RAM VMA45UG-MEC1U2AW2 8GB DIMM DDR4 2400MT/s    | 1        | 4.76%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR4  | 11       | 61.11%  |
| DDR3  | 6        | 33.33%  |
| SDRAM | 1        | 5.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 17       | 94.44%  |
| SODIMM | 1        | 5.56%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 9        | 47.37%  |
| 16384 | 3        | 15.79%  |
| 4096  | 3        | 15.79%  |
| 2048  | 2        | 10.53%  |
| 32768 | 1        | 5.26%   |
| 1024  | 1        | 5.26%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 5        | 25%     |
| 3600  | 4        | 20%     |
| 2400  | 3        | 15%     |
| 3200  | 2        | 10%     |
| 3866  | 1        | 5%      |
| 3800  | 1        | 5%      |
| 3466  | 1        | 5%      |
| 2933  | 1        | 5%      |
| 1066  | 1        | 5%      |
| 800   | 1        | 5%      |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Canon              | 1        | 50%     |
| Brother Industries | 1        | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                      | Desktops | Percent |
|----------------------------|----------|---------|
| Canon TR4500 series        | 1        | 50%     |
| Brother MFC-L2710DN series | 1        | 50%     |

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
| Logitech            | 11       | 44%     |
| Apple               | 3        | 12%     |
| Microsoft           | 2        | 8%      |
| Microdia            | 2        | 8%      |
| Hewlett-Packard     | 2        | 8%      |
| Samsung Electronics | 1        | 4%      |
| Lenovo              | 1        | 4%      |
| Chicony Electronics | 1        | 4%      |
| ARC International   | 1        | 4%      |
| ANYKA               | 1        | 4%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Logitech C922 Pro Stream Webcam | 4        | 16%     |
| Logitech Webcam C270            | 3        | 12%     |
| Apple iPhone5/5C/5S/6           | 3        | 12%     |
| Microdia Integrated Camera      | 2        | 8%      |
| Samsung Galaxy A5 (MTP)         | 1        | 4%      |
| Microsoft Xbox NUI Camera       | 1        | 4%      |
| Microsoft LifeCam Cinema        | 1        | 4%      |
| Logitech StreamCam              | 1        | 4%      |
| Logitech QuickCam Pro 9000      | 1        | 4%      |
| Logitech Logi 4K Stream Edition | 1        | 4%      |
| Logitech HD Pro Webcam C920     | 1        | 4%      |
| Lenovo 500 RGB Camera           | 1        | 4%      |
| HP Webcam HD-2200               | 1        | 4%      |
| HP Webcam HD 2300               | 1        | 4%      |
| Chicony CNFA035                 | 1        | 4%      |
| ARC International Camera        | 1        | 4%      |
| ANYKA V380 FHD Camera           | 1        | 4%      |

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
| 0     | 96       | 87.27%  |
| 1     | 13       | 11.82%  |
| 2     | 1        | 0.91%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 8        | 53.33%  |
| Graphics card            | 3        | 20%     |
| Unassigned class         | 1        | 6.67%   |
| Sound                    | 1        | 6.67%   |
| Multimedia controller    | 1        | 6.67%   |
| Communication controller | 1        | 6.67%   |

