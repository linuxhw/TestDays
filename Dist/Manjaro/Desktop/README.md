Manjaro - Tested Hardware & Statistics (Desktops)
-------------------------------------------------

A project to collect tested hardware configurations for Manjaro.

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

Total: 3490

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | ROG STRIX X570-F GAMING     | [7e22db9b23](https://linux-hardware.org/?probe=7e22db9b23) | Dec 31, 2022 |
| ASRock        | B550 Steel Legend           | [8705e10ac6](https://linux-hardware.org/?probe=8705e10ac6) | Dec 31, 2022 |
| ASUSTek       | PRIME X670-P WIFI           | [cecef0575d](https://linux-hardware.org/?probe=cecef0575d) | Dec 30, 2022 |
| Gigabyte      | Z87-HD3                     | [97f08bd689](https://linux-hardware.org/?probe=97f08bd689) | Dec 30, 2022 |
| Gigabyte      | H510M H                     | [24574296e5](https://linux-hardware.org/?probe=24574296e5) | Dec 29, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [7a7f335c4a](https://linux-hardware.org/?probe=7a7f335c4a) | Dec 29, 2022 |
| MSI           | X370 GAMING M7 ACK          | [60fe0d0b31](https://linux-hardware.org/?probe=60fe0d0b31) | Dec 29, 2022 |
| MSI           | PRO B660M-A DDR4            | [dbc37ff826](https://linux-hardware.org/?probe=dbc37ff826) | Dec 29, 2022 |
| Dell          | 0TTDMJ A00                  | [198e723dc2](https://linux-hardware.org/?probe=198e723dc2) | Dec 28, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [6d56c4c392](https://linux-hardware.org/?probe=6d56c4c392) | Dec 27, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [d6a12148ec](https://linux-hardware.org/?probe=d6a12148ec) | Dec 27, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [bd232cd937](https://linux-hardware.org/?probe=bd232cd937) | Dec 27, 2022 |
| Gigabyte      | Z370 HD3-CF                 | [ac6571db76](https://linux-hardware.org/?probe=ac6571db76) | Dec 27, 2022 |
| ASRock        | Z690 Taichi                 | [4a4e2975d2](https://linux-hardware.org/?probe=4a4e2975d2) | Dec 27, 2022 |
| ASUSTek       | M5A78L-M LX3                | [a6c0667059](https://linux-hardware.org/?probe=a6c0667059) | Dec 27, 2022 |
| ASUSTek       | M5A78L-M LX3                | [ad94a727ab](https://linux-hardware.org/?probe=ad94a727ab) | Dec 27, 2022 |
| ASRock        | AB350M-HDV                  | [666ea6d820](https://linux-hardware.org/?probe=666ea6d820) | Dec 26, 2022 |
| ASUSTek       | M5A97 R2.0                  | [be1ace7f20](https://linux-hardware.org/?probe=be1ace7f20) | Dec 26, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | [82de75771e](https://linux-hardware.org/?probe=82de75771e) | Dec 25, 2022 |
| ASRock        | X670E Pro RS                | [b7a0a3d703](https://linux-hardware.org/?probe=b7a0a3d703) | Dec 24, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [e3e2773bde](https://linux-hardware.org/?probe=e3e2773bde) | Dec 24, 2022 |
| Gigabyte      | H510M H                     | [d592546f0a](https://linux-hardware.org/?probe=d592546f0a) | Dec 23, 2022 |
| Gigabyte      | H510M H                     | [52f1e32fc8](https://linux-hardware.org/?probe=52f1e32fc8) | Dec 23, 2022 |
| Dell          | 0GY6Y8 A02                  | [1044231936](https://linux-hardware.org/?probe=1044231936) | Dec 22, 2022 |
| HP            | 8053                        | [38b3012a7c](https://linux-hardware.org/?probe=38b3012a7c) | Dec 22, 2022 |
| ASRock        | X670E Taichi                | [e1b13226a4](https://linux-hardware.org/?probe=e1b13226a4) | Dec 21, 2022 |
| ASRock        | AB350 Pro4                  | [c7005e1e89](https://linux-hardware.org/?probe=c7005e1e89) | Dec 21, 2022 |
| Gigabyte      | Z690 AORUS PRO              | [dbefd12c1c](https://linux-hardware.org/?probe=dbefd12c1c) | Dec 19, 2022 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | [9fb0357e3e](https://linux-hardware.org/?probe=9fb0357e3e) | Dec 19, 2022 |
| ASRock        | Z390 Pro4                   | [478165e478](https://linux-hardware.org/?probe=478165e478) | Dec 18, 2022 |
| Gigabyte      | B550M DS3H                  | [d868b73cfb](https://linux-hardware.org/?probe=d868b73cfb) | Dec 18, 2022 |
| Gigabyte      | B460M AORUS PRO             | [6deb38fb48](https://linux-hardware.org/?probe=6deb38fb48) | Dec 17, 2022 |
| MSI           | X370 GAMING M7 ACK          | [71dabd9e44](https://linux-hardware.org/?probe=71dabd9e44) | Dec 17, 2022 |
| MSI           | A68HM-E33                   | [0df6f80110](https://linux-hardware.org/?probe=0df6f80110) | Dec 17, 2022 |
| MSI           | X370 GAMING M7 ACK          | [3b245437e5](https://linux-hardware.org/?probe=3b245437e5) | Dec 17, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [d2dce9cbfd](https://linux-hardware.org/?probe=d2dce9cbfd) | Dec 16, 2022 |
| Gigabyte      | H510M H                     | [ccb746cd73](https://linux-hardware.org/?probe=ccb746cd73) | Dec 15, 2022 |
| ZOTAC         | ION                         | [f02f6b8382](https://linux-hardware.org/?probe=f02f6b8382) | Dec 15, 2022 |
| Dell          | 0D6H9T A02                  | [6266999282](https://linux-hardware.org/?probe=6266999282) | Dec 15, 2022 |
| Gigabyte      | B450M H                     | [c888c743e3](https://linux-hardware.org/?probe=c888c743e3) | Dec 15, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [7d15ecff86](https://linux-hardware.org/?probe=7d15ecff86) | Dec 15, 2022 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [72175490ae](https://linux-hardware.org/?probe=72175490ae) | Dec 15, 2022 |
| MSI           | B250 GAMING M3              | [cf050915a5](https://linux-hardware.org/?probe=cf050915a5) | Dec 14, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | [39d58ec9aa](https://linux-hardware.org/?probe=39d58ec9aa) | Dec 13, 2022 |
| ASUSTek       | X99-A II                    | [a6e0258bbe](https://linux-hardware.org/?probe=a6e0258bbe) | Dec 13, 2022 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [8fd3c60681](https://linux-hardware.org/?probe=8fd3c60681) | Dec 13, 2022 |
| Intel         | Eaglelake Fab D             | [ed5c44a200](https://linux-hardware.org/?probe=ed5c44a200) | Dec 13, 2022 |
| MSI           | B450I GAMING PLUS MAX WI... | [0973466d88](https://linux-hardware.org/?probe=0973466d88) | Dec 13, 2022 |
| MSI           | B450I GAMING PLUS MAX WI... | [9d2ef8adf1](https://linux-hardware.org/?probe=9d2ef8adf1) | Dec 13, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | [c5501c208c](https://linux-hardware.org/?probe=c5501c208c) | Dec 11, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [6964e348d6](https://linux-hardware.org/?probe=6964e348d6) | Dec 11, 2022 |
| ASUSTek       | X99-A II                    | [09f8da551c](https://linux-hardware.org/?probe=09f8da551c) | Dec 11, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [23be4288bb](https://linux-hardware.org/?probe=23be4288bb) | Dec 11, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [121359234c](https://linux-hardware.org/?probe=121359234c) | Dec 11, 2022 |
| ASUSTek       | PRIME X570-P                | [6b00f35a38](https://linux-hardware.org/?probe=6b00f35a38) | Dec 10, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [deab1a46db](https://linux-hardware.org/?probe=deab1a46db) | Dec 10, 2022 |
| ASUSTek       | PRIME B550M-A               | [e843a9c61d](https://linux-hardware.org/?probe=e843a9c61d) | Dec 10, 2022 |
| Gigabyte      | Z170-HD3P-CF                | [27fdfb657e](https://linux-hardware.org/?probe=27fdfb657e) | Dec 09, 2022 |
| Gigabyte      | B550M S2H                   | [5e56097f25](https://linux-hardware.org/?probe=5e56097f25) | Dec 08, 2022 |
| MSI           | PRO B650-P WIFI             | [b74866314e](https://linux-hardware.org/?probe=b74866314e) | Dec 08, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [d6666dccec](https://linux-hardware.org/?probe=d6666dccec) | Dec 08, 2022 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | [c6895362e6](https://linux-hardware.org/?probe=c6895362e6) | Dec 07, 2022 |
| Lenovo        | ThinkStation S20 4157DT6    | [7c45cf5115](https://linux-hardware.org/?probe=7c45cf5115) | Dec 07, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | [037c8e9cbc](https://linux-hardware.org/?probe=037c8e9cbc) | Dec 06, 2022 |
| Gigabyte      | F2A58M-HD2                  | [61c23e2501](https://linux-hardware.org/?probe=61c23e2501) | Dec 06, 2022 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | [689479ce87](https://linux-hardware.org/?probe=689479ce87) | Dec 06, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [f11d4ebe40](https://linux-hardware.org/?probe=f11d4ebe40) | Dec 05, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [ddd1487d81](https://linux-hardware.org/?probe=ddd1487d81) | Dec 05, 2022 |
| HP            | 8053                        | [5fad592ef3](https://linux-hardware.org/?probe=5fad592ef3) | Dec 05, 2022 |
| Gigabyte      | B550M S2H                   | [dd012c9f92](https://linux-hardware.org/?probe=dd012c9f92) | Dec 04, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [9eb248d38e](https://linux-hardware.org/?probe=9eb248d38e) | Dec 04, 2022 |
| ASUSTek       | M5A97 R2.0                  | [b3b5eb90e5](https://linux-hardware.org/?probe=b3b5eb90e5) | Dec 03, 2022 |
| ASRock        | Z87 Extreme4                | [422dde5ae5](https://linux-hardware.org/?probe=422dde5ae5) | Dec 03, 2022 |
| MSI           | B450I GAMING PLUS AC        | [366f9ae2aa](https://linux-hardware.org/?probe=366f9ae2aa) | Dec 03, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [ec36ceb3fd](https://linux-hardware.org/?probe=ec36ceb3fd) | Dec 02, 2022 |
| MSI           | A68HM-E33                   | [4e2313d8b7](https://linux-hardware.org/?probe=4e2313d8b7) | Dec 02, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [8cf4925f08](https://linux-hardware.org/?probe=8cf4925f08) | Dec 01, 2022 |
| ASRock        | X300M-STX                   | [97ceee65f3](https://linux-hardware.org/?probe=97ceee65f3) | Dec 01, 2022 |
| ASRock        | X300M-STX                   | [5b7f983a24](https://linux-hardware.org/?probe=5b7f983a24) | Dec 01, 2022 |
| ASRock        | X300M-STX                   | [42ddb2463e](https://linux-hardware.org/?probe=42ddb2463e) | Dec 01, 2022 |
| Gigabyte      | Z370 HD3-CF                 | [ece7618688](https://linux-hardware.org/?probe=ece7618688) | Nov 30, 2022 |
| ASRock        | B550M Pro4                  | [f48969af69](https://linux-hardware.org/?probe=f48969af69) | Nov 29, 2022 |
| Dell          | 09WH54 A00                  | [2700be5b4a](https://linux-hardware.org/?probe=2700be5b4a) | Nov 28, 2022 |
| Gigabyte      | M61PME-S2P                  | [4aa3d8ee32](https://linux-hardware.org/?probe=4aa3d8ee32) | Nov 27, 2022 |
| HP            | 3397                        | [e264b68f30](https://linux-hardware.org/?probe=e264b68f30) | Nov 27, 2022 |
| Gigabyte      | 970A-DS3P FX                | [4ded1fb943](https://linux-hardware.org/?probe=4ded1fb943) | Nov 26, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [bb0d4b34af](https://linux-hardware.org/?probe=bb0d4b34af) | Nov 26, 2022 |
| Gigabyte      | A320M-H-CF                  | [5f1188d448](https://linux-hardware.org/?probe=5f1188d448) | Nov 26, 2022 |
| ASRock        | B550M Pro4                  | [0828e5929e](https://linux-hardware.org/?probe=0828e5929e) | Nov 26, 2022 |
| Gigabyte      | A320M-H-CF                  | [771019bcc6](https://linux-hardware.org/?probe=771019bcc6) | Nov 26, 2022 |
| Gigabyte      | B550M S2H                   | [8ea3c120c6](https://linux-hardware.org/?probe=8ea3c120c6) | Nov 23, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [6cd720c62c](https://linux-hardware.org/?probe=6cd720c62c) | Nov 23, 2022 |
| MSI           | PRO Z690-A DDR4             | [fc53a66047](https://linux-hardware.org/?probe=fc53a66047) | Nov 22, 2022 |
| ASUSTek       | Maximus VI GENE             | [62b0cb4c94](https://linux-hardware.org/?probe=62b0cb4c94) | Nov 22, 2022 |
| ASUSTek       | Maximus VI GENE             | [26e7d04331](https://linux-hardware.org/?probe=26e7d04331) | Nov 22, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [a22e271ac2](https://linux-hardware.org/?probe=a22e271ac2) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [64cff39a82](https://linux-hardware.org/?probe=64cff39a82) | Nov 21, 2022 |
| ASRock        | B550M Pro4                  | [7d1d0390ba](https://linux-hardware.org/?probe=7d1d0390ba) | Nov 20, 2022 |
| MSI           | 970A-G43                    | [6c04d813ff](https://linux-hardware.org/?probe=6c04d813ff) | Nov 20, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [d40491a06a](https://linux-hardware.org/?probe=d40491a06a) | Nov 19, 2022 |
| Intel         | DH55PJ AAE93812-303         | [bebe890c96](https://linux-hardware.org/?probe=bebe890c96) | Nov 19, 2022 |
| ASUSTek       | PRIME A320M-K               | [6d02e2a960](https://linux-hardware.org/?probe=6d02e2a960) | Nov 19, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [598f8e7c34](https://linux-hardware.org/?probe=598f8e7c34) | Nov 19, 2022 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | [c8fc039301](https://linux-hardware.org/?probe=c8fc039301) | Nov 19, 2022 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | [1ffee02fee](https://linux-hardware.org/?probe=1ffee02fee) | Nov 19, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [312da35b57](https://linux-hardware.org/?probe=312da35b57) | Nov 17, 2022 |
| ASUSTek       | Maximus VIII GENE           | [8b542ffc42](https://linux-hardware.org/?probe=8b542ffc42) | Nov 17, 2022 |
| MSI           | X79A-GD45                   | [7f7b7354b8](https://linux-hardware.org/?probe=7f7b7354b8) | Nov 17, 2022 |
| MSI           | X79A-GD45                   | [42d08e1136](https://linux-hardware.org/?probe=42d08e1136) | Nov 17, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [f5fd3e9e4b](https://linux-hardware.org/?probe=f5fd3e9e4b) | Nov 16, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [07d80f1783](https://linux-hardware.org/?probe=07d80f1783) | Nov 16, 2022 |
| Gigabyte      | GA-A75M-UD2H                | [4da8ff348a](https://linux-hardware.org/?probe=4da8ff348a) | Nov 15, 2022 |
| ASRock        | A320M-HDV R4.0              | [7764c0fea2](https://linux-hardware.org/?probe=7764c0fea2) | Nov 15, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [c8c74ea1ec](https://linux-hardware.org/?probe=c8c74ea1ec) | Nov 15, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [567b81705d](https://linux-hardware.org/?probe=567b81705d) | Nov 15, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [389d8cf0e0](https://linux-hardware.org/?probe=389d8cf0e0) | Nov 15, 2022 |
| ASUSTek       | PRIME B350M-A               | [aabc2148da](https://linux-hardware.org/?probe=aabc2148da) | Nov 15, 2022 |
| MSI           | Z97A GAMING 7               | [275a1c28dd](https://linux-hardware.org/?probe=275a1c28dd) | Nov 13, 2022 |
| ASUSTek       | PRIME X470-PRO              | [370fb87faa](https://linux-hardware.org/?probe=370fb87faa) | Nov 13, 2022 |
| MSI           | B85M-P33 V2                 | [d633461307](https://linux-hardware.org/?probe=d633461307) | Nov 13, 2022 |
| ASRock        | X300M-STX                   | [6b2e935e07](https://linux-hardware.org/?probe=6b2e935e07) | Nov 12, 2022 |
| ASRock        | X300M-STX                   | [b071af765d](https://linux-hardware.org/?probe=b071af765d) | Nov 12, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [87b7416681](https://linux-hardware.org/?probe=87b7416681) | Nov 12, 2022 |
| ASUSTek       | PRIME A320M-K               | [f4ed581802](https://linux-hardware.org/?probe=f4ed581802) | Nov 11, 2022 |
| ASUSTek       | PRIME A320M-K               | [e06ab9c0b9](https://linux-hardware.org/?probe=e06ab9c0b9) | Nov 11, 2022 |
| Gigabyte      | H410M S2H V3                | [2172ca7325](https://linux-hardware.org/?probe=2172ca7325) | Nov 11, 2022 |
| MSI           | X79A-GD45                   | [cb82895374](https://linux-hardware.org/?probe=cb82895374) | Nov 11, 2022 |
| Gigabyte      | Z690 AORUS PRO              | [8dcd548e89](https://linux-hardware.org/?probe=8dcd548e89) | Nov 10, 2022 |
| Gigabyte      | Z690 AORUS PRO              | [e95608162f](https://linux-hardware.org/?probe=e95608162f) | Nov 10, 2022 |
| ASUSTek       | H110M-A                     | [4868cf87f5](https://linux-hardware.org/?probe=4868cf87f5) | Nov 09, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [9571026291](https://linux-hardware.org/?probe=9571026291) | Nov 08, 2022 |
| ASRock        | X300M-STX                   | [1fee3f08a9](https://linux-hardware.org/?probe=1fee3f08a9) | Nov 07, 2022 |
| MSI           | B550-A PRO                  | [6c4ff211d1](https://linux-hardware.org/?probe=6c4ff211d1) | Nov 07, 2022 |
| HP            | 844C                        | [5b8b05d13d](https://linux-hardware.org/?probe=5b8b05d13d) | Nov 07, 2022 |
| ASRock        | AB350M                      | [fae0de4ece](https://linux-hardware.org/?probe=fae0de4ece) | Nov 07, 2022 |
| Pegatron      | 2AB6                        | [c55efc41db](https://linux-hardware.org/?probe=c55efc41db) | Nov 06, 2022 |
| HP            | 828A                        | [42d15a94b0](https://linux-hardware.org/?probe=42d15a94b0) | Nov 06, 2022 |
| ASRock        | H310CM-HDV                  | [cb1cecc5e1](https://linux-hardware.org/?probe=cb1cecc5e1) | Nov 05, 2022 |
| ASUSTek       | P8H61-M LE/CSM              | [fb29e83d2d](https://linux-hardware.org/?probe=fb29e83d2d) | Nov 05, 2022 |
| ASUSTek       | P8H67                       | [0d98e4b3b3](https://linux-hardware.org/?probe=0d98e4b3b3) | Nov 05, 2022 |
| Lenovo        | 3728 SDK0J40700 WIN 3258... | [6700909ef7](https://linux-hardware.org/?probe=6700909ef7) | Nov 03, 2022 |
| ASUSTek       | M5A97 R2.0                  | [fecd8f06dd](https://linux-hardware.org/?probe=fecd8f06dd) | Nov 02, 2022 |
| HP            | 8054                        | [0f866b3605](https://linux-hardware.org/?probe=0f866b3605) | Nov 02, 2022 |
| ASUSTek       | P5K-E                       | [6b48759d1d](https://linux-hardware.org/?probe=6b48759d1d) | Nov 02, 2022 |
| MSI           | Z370 GAMING PLUS            | [527c779cfb](https://linux-hardware.org/?probe=527c779cfb) | Nov 01, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [8ce0b9271b](https://linux-hardware.org/?probe=8ce0b9271b) | Nov 01, 2022 |
| MSI           | MAG B660M MORTAR WIFI DD... | [115e9027d0](https://linux-hardware.org/?probe=115e9027d0) | Nov 01, 2022 |
| Acer          | H410H6-M17 P21-A1           | [9333be5120](https://linux-hardware.org/?probe=9333be5120) | Nov 01, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [6e577f6de5](https://linux-hardware.org/?probe=6e577f6de5) | Nov 01, 2022 |
| HP            | 3397                        | [942cfa2a25](https://linux-hardware.org/?probe=942cfa2a25) | Oct 31, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [f497e98b58](https://linux-hardware.org/?probe=f497e98b58) | Oct 31, 2022 |
| Gigabyte      | Z77M-D3H                    | [83cd207e4e](https://linux-hardware.org/?probe=83cd207e4e) | Oct 30, 2022 |
| ASRock        | X570 Pro4                   | [d2407c253b](https://linux-hardware.org/?probe=d2407c253b) | Oct 30, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [7d6c392e74](https://linux-hardware.org/?probe=7d6c392e74) | Oct 29, 2022 |
| Gigabyte      | Z370 HD3-CF                 | [06cb3f01ba](https://linux-hardware.org/?probe=06cb3f01ba) | Oct 29, 2022 |
| ASUSTek       | PRIME A320M-K               | [25caeb6d9e](https://linux-hardware.org/?probe=25caeb6d9e) | Oct 29, 2022 |
| ASUSTek       | PRIME B365M-C               | [ccf9650f9a](https://linux-hardware.org/?probe=ccf9650f9a) | Oct 29, 2022 |
| Acer          | Aspire TC-885 V:1.1         | [81ccab7297](https://linux-hardware.org/?probe=81ccab7297) | Oct 29, 2022 |
| ASUSTek       | PRIME A320M-K               | [5876a2f3d6](https://linux-hardware.org/?probe=5876a2f3d6) | Oct 28, 2022 |
| ASUSTek       | P9X79-WS-SYS                | [8b10d380a5](https://linux-hardware.org/?probe=8b10d380a5) | Oct 28, 2022 |
| ASRock        | B550M Pro4                  | [b21b6b2908](https://linux-hardware.org/?probe=b21b6b2908) | Oct 27, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [2227bb9824](https://linux-hardware.org/?probe=2227bb9824) | Oct 25, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | [1f3561258a](https://linux-hardware.org/?probe=1f3561258a) | Oct 25, 2022 |
| Unknown       | 1.0                         | [cf3a9de207](https://linux-hardware.org/?probe=cf3a9de207) | Oct 25, 2022 |
| MSI           | H97 PC Mate                 | [1916f5c048](https://linux-hardware.org/?probe=1916f5c048) | Oct 25, 2022 |
| Acer          | Aspire MC605 v1.0           | [9544ff7787](https://linux-hardware.org/?probe=9544ff7787) | Oct 24, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [4b88876126](https://linux-hardware.org/?probe=4b88876126) | Oct 24, 2022 |
| HP            | 828A                        | [2123f2610c](https://linux-hardware.org/?probe=2123f2610c) | Oct 24, 2022 |
| MSI           | Z68MA-G45                   | [3f398756eb](https://linux-hardware.org/?probe=3f398756eb) | Oct 23, 2022 |
| MSI           | Z68MA-G45                   | [d96627943d](https://linux-hardware.org/?probe=d96627943d) | Oct 23, 2022 |
| Lenovo        | ThinkCentre A57 9851CDF     | [8910fecc7d](https://linux-hardware.org/?probe=8910fecc7d) | Oct 23, 2022 |
| Gigabyte      | Z690 AORUS PRO              | [7cb3500943](https://linux-hardware.org/?probe=7cb3500943) | Oct 22, 2022 |
| Gigabyte      | B365M DS3H                  | [d5f16dde87](https://linux-hardware.org/?probe=d5f16dde87) | Oct 22, 2022 |
| ASUSTek       | P8Z68-V GEN3                | [e1dedae10a](https://linux-hardware.org/?probe=e1dedae10a) | Oct 22, 2022 |
| ASRock        | H310CM-HDV                  | [afe54b52c9](https://linux-hardware.org/?probe=afe54b52c9) | Oct 21, 2022 |
| ASUSTek       | ROG STRIX B360-G GAMING     | [eaad7f0757](https://linux-hardware.org/?probe=eaad7f0757) | Oct 20, 2022 |
| Gigabyte      | H61M-S2V-B3                 | [9e7b79bfbb](https://linux-hardware.org/?probe=9e7b79bfbb) | Oct 20, 2022 |
| ASUSTek       | Pro WS X570-ACE             | [7f069e1021](https://linux-hardware.org/?probe=7f069e1021) | Oct 20, 2022 |
| ASUSTek       | H110M-K                     | [a43f7f6601](https://linux-hardware.org/?probe=a43f7f6601) | Oct 19, 2022 |
| ASUSTek       | H170 PRO GAMING             | [cb86d1ba99](https://linux-hardware.org/?probe=cb86d1ba99) | Oct 18, 2022 |
| ASRock        | X670E PG Lightning          | [c3ce6dce01](https://linux-hardware.org/?probe=c3ce6dce01) | Oct 18, 2022 |
| Foxconn       | 2ABF                        | [ac2c9383c0](https://linux-hardware.org/?probe=ac2c9383c0) | Oct 18, 2022 |
| ASRock        | H310CM-HDV                  | [2426012acb](https://linux-hardware.org/?probe=2426012acb) | Oct 18, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [98024d1066](https://linux-hardware.org/?probe=98024d1066) | Oct 17, 2022 |
| MACHINIST     | X79 V2.82H                  | [5d99fbefc1](https://linux-hardware.org/?probe=5d99fbefc1) | Oct 17, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [7de3eff9df](https://linux-hardware.org/?probe=7de3eff9df) | Oct 16, 2022 |
| Gigabyte      | X399 AORUS PRO-CF           | [93e82a30ac](https://linux-hardware.org/?probe=93e82a30ac) | Oct 16, 2022 |
| Gigabyte      | X399 AORUS PRO-CF           | [eb9b7e329b](https://linux-hardware.org/?probe=eb9b7e329b) | Oct 16, 2022 |
| ASUSTek       | P8H77-V                     | [d6af5204e6](https://linux-hardware.org/?probe=d6af5204e6) | Oct 14, 2022 |
| Gigabyte      | H510M H                     | [28a0b7d55f](https://linux-hardware.org/?probe=28a0b7d55f) | Oct 14, 2022 |
| HP            | 802E                        | [6231a344aa](https://linux-hardware.org/?probe=6231a344aa) | Oct 14, 2022 |
| Dell          | 0HN7XN A01                  | [a71fb08b36](https://linux-hardware.org/?probe=a71fb08b36) | Oct 14, 2022 |
| Dell          | 0HN7XN A01                  | [abf7c780d2](https://linux-hardware.org/?probe=abf7c780d2) | Oct 13, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [f55bb836c3](https://linux-hardware.org/?probe=f55bb836c3) | Oct 13, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [8e2b577a03](https://linux-hardware.org/?probe=8e2b577a03) | Oct 13, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [dd9695948c](https://linux-hardware.org/?probe=dd9695948c) | Oct 11, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [d006fa9a19](https://linux-hardware.org/?probe=d006fa9a19) | Oct 11, 2022 |
| Gigabyte      | B450M H                     | [36fc5f2c90](https://linux-hardware.org/?probe=36fc5f2c90) | Oct 10, 2022 |
| Gigabyte      | B450M H                     | [c3dc2e33df](https://linux-hardware.org/?probe=c3dc2e33df) | Oct 10, 2022 |
| HP            | 8460                        | [08601807cc](https://linux-hardware.org/?probe=08601807cc) | Oct 10, 2022 |
| HP            | 8460                        | [5be586f271](https://linux-hardware.org/?probe=5be586f271) | Oct 10, 2022 |
| ASUSTek       | P6X58-E-WS                  | [786a8ba316](https://linux-hardware.org/?probe=786a8ba316) | Oct 09, 2022 |
| Dell          | 0TTDMJ A00                  | [656b9369be](https://linux-hardware.org/?probe=656b9369be) | Oct 09, 2022 |
| ASRock        | B550M Steel Legend          | [740a5f78d8](https://linux-hardware.org/?probe=740a5f78d8) | Oct 09, 2022 |
| Gigabyte      | B450 GAMING X               | [a297c351ed](https://linux-hardware.org/?probe=a297c351ed) | Oct 09, 2022 |
| Dell          | 0NW73C A00                  | [2b0a3f91ea](https://linux-hardware.org/?probe=2b0a3f91ea) | Oct 08, 2022 |
| Dell          | 0M9KCM A01                  | [6fa93f6da5](https://linux-hardware.org/?probe=6fa93f6da5) | Oct 07, 2022 |
| Gigabyte      | P55M-UD2                    | [e9627c4c34](https://linux-hardware.org/?probe=e9627c4c34) | Oct 07, 2022 |
| Dell          | 0D24M8 A00                  | [8130af2fab](https://linux-hardware.org/?probe=8130af2fab) | Oct 06, 2022 |
| HP            | 87D6 SMVB                   | [03cf885086](https://linux-hardware.org/?probe=03cf885086) | Oct 05, 2022 |
| Gigabyte      | H510M H                     | [a4c0e2324f](https://linux-hardware.org/?probe=a4c0e2324f) | Oct 04, 2022 |
| HP            | 21D0                        | [6815e2bba2](https://linux-hardware.org/?probe=6815e2bba2) | Oct 04, 2022 |
| Dell          | 0HN7XN A00                  | [77776da6f7](https://linux-hardware.org/?probe=77776da6f7) | Oct 03, 2022 |
| Dell          | 0HN7XN A00                  | [84d4748b3e](https://linux-hardware.org/?probe=84d4748b3e) | Oct 03, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [668ad3e30a](https://linux-hardware.org/?probe=668ad3e30a) | Oct 02, 2022 |
| ASRock        | B450 Pro4                   | [402a7995c4](https://linux-hardware.org/?probe=402a7995c4) | Oct 02, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [15a068e26b](https://linux-hardware.org/?probe=15a068e26b) | Oct 01, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [3a9d882d91](https://linux-hardware.org/?probe=3a9d882d91) | Oct 01, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [dda857d7e6](https://linux-hardware.org/?probe=dda857d7e6) | Oct 01, 2022 |
| Gigabyte      | Z170X-Gaming GT             | [991ea6c93f](https://linux-hardware.org/?probe=991ea6c93f) | Oct 01, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [32a742b50d](https://linux-hardware.org/?probe=32a742b50d) | Oct 01, 2022 |
| Dell          | 07PR60 A01                  | [812cb18129](https://linux-hardware.org/?probe=812cb18129) | Sep 30, 2022 |
| Dell          | 0HN7XN A00                  | [c9126cd382](https://linux-hardware.org/?probe=c9126cd382) | Sep 30, 2022 |
| ASRock        | X399M Taichi                | [b7943d1645](https://linux-hardware.org/?probe=b7943d1645) | Sep 29, 2022 |
| Gigabyte      | Z690 GAMING X DDR4          | [b372f8126f](https://linux-hardware.org/?probe=b372f8126f) | Sep 29, 2022 |
| ASRock        | J3160DC-ITX                 | [7e1818288f](https://linux-hardware.org/?probe=7e1818288f) | Sep 29, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [c83049a0f6](https://linux-hardware.org/?probe=c83049a0f6) | Sep 29, 2022 |
| ASRock        | Z97 Pro3                    | [7b34a50df8](https://linux-hardware.org/?probe=7b34a50df8) | Sep 28, 2022 |
| ASRock        | B450 Pro4                   | [6a9066019c](https://linux-hardware.org/?probe=6a9066019c) | Sep 28, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [76aac25208](https://linux-hardware.org/?probe=76aac25208) | Sep 28, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [27ce89f701](https://linux-hardware.org/?probe=27ce89f701) | Sep 28, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [30507c8461](https://linux-hardware.org/?probe=30507c8461) | Sep 27, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [e5b4fe8914](https://linux-hardware.org/?probe=e5b4fe8914) | Sep 25, 2022 |
| ASUSTek       | Rampage V EDITION 10        | [c65cbf84dc](https://linux-hardware.org/?probe=c65cbf84dc) | Sep 25, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [e47b2b85dc](https://linux-hardware.org/?probe=e47b2b85dc) | Sep 24, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [719b20fd4e](https://linux-hardware.org/?probe=719b20fd4e) | Sep 24, 2022 |
| Huanan        | X99-TF                      | [1361d73bcd](https://linux-hardware.org/?probe=1361d73bcd) | Sep 22, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [1faf714086](https://linux-hardware.org/?probe=1faf714086) | Sep 21, 2022 |
| Minix         | NEO G41V-4 Max              | [a1640603ca](https://linux-hardware.org/?probe=a1640603ca) | Sep 20, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [6c7d6ef178](https://linux-hardware.org/?probe=6c7d6ef178) | Sep 20, 2022 |
| Dell          | 040DDP A01                  | [635c6895e1](https://linux-hardware.org/?probe=635c6895e1) | Sep 20, 2022 |
| Intel         | X99 V1.0                    | [02bfe94d24](https://linux-hardware.org/?probe=02bfe94d24) | Sep 19, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [25d7dc8f0d](https://linux-hardware.org/?probe=25d7dc8f0d) | Sep 19, 2022 |
| Gigabyte      | A320M-H-CF                  | [a3e30957c7](https://linux-hardware.org/?probe=a3e30957c7) | Sep 19, 2022 |
| HP            | 212B                        | [c823e0060e](https://linux-hardware.org/?probe=c823e0060e) | Sep 19, 2022 |
| MSI           | B250M PRO-VDH               | [b0836f0c26](https://linux-hardware.org/?probe=b0836f0c26) | Sep 19, 2022 |
| ASRock        | X399 Phantom Gaming 6       | [a28b408f4a](https://linux-hardware.org/?probe=a28b408f4a) | Sep 19, 2022 |
| MSI           | B250M PRO-VDH               | [3b6b90fee6](https://linux-hardware.org/?probe=3b6b90fee6) | Sep 18, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [d11c4e27df](https://linux-hardware.org/?probe=d11c4e27df) | Sep 18, 2022 |
| Intel         | X99 V1.0                    | [735c794db9](https://linux-hardware.org/?probe=735c794db9) | Sep 17, 2022 |
| Foxconn       | 2ADA                        | [b136916fb3](https://linux-hardware.org/?probe=b136916fb3) | Sep 16, 2022 |
| BESSTAR Te... | UM700                       | [f6ccaeed5e](https://linux-hardware.org/?probe=f6ccaeed5e) | Sep 16, 2022 |
| ASRock        | B450M Pro4                  | [19a46a2f8e](https://linux-hardware.org/?probe=19a46a2f8e) | Sep 16, 2022 |
| ASUSTek       | PRIME H410M-E               | [91f1fdc978](https://linux-hardware.org/?probe=91f1fdc978) | Sep 14, 2022 |
| Exo           | H310CH5-M2                  | [9154b5149b](https://linux-hardware.org/?probe=9154b5149b) | Sep 14, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [4a436fb179](https://linux-hardware.org/?probe=4a436fb179) | Sep 14, 2022 |
| ASUSTek       | X99-DELUXE II               | [8c9013ec12](https://linux-hardware.org/?probe=8c9013ec12) | Sep 13, 2022 |
| Dell          | 04YP6J A00                  | [ef4ae2baac](https://linux-hardware.org/?probe=ef4ae2baac) | Sep 13, 2022 |
| Gigabyte      | H77M-D3H                    | [3767b84078](https://linux-hardware.org/?probe=3767b84078) | Sep 12, 2022 |
| Foxconn       | 2ADA                        | [1b43b0d291](https://linux-hardware.org/?probe=1b43b0d291) | Sep 11, 2022 |
| MSI           | B350M BAZOOKA               | [ff7d2e74a5](https://linux-hardware.org/?probe=ff7d2e74a5) | Sep 11, 2022 |
| ASRock        | J3160DC-ITX                 | [e854b82ab9](https://linux-hardware.org/?probe=e854b82ab9) | Sep 10, 2022 |
| Gigabyte      | B450M DS3H-CF               | [6248f4732d](https://linux-hardware.org/?probe=6248f4732d) | Sep 10, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [70f5e3d77c](https://linux-hardware.org/?probe=70f5e3d77c) | Sep 08, 2022 |
| HP            | 3397                        | [0ebeef29bf](https://linux-hardware.org/?probe=0ebeef29bf) | Sep 07, 2022 |
| Intel         | Unknown                     | [2758407d23](https://linux-hardware.org/?probe=2758407d23) | Sep 07, 2022 |
| ASUSTek       | PRIME B360-PLUS             | [d35810173c](https://linux-hardware.org/?probe=d35810173c) | Sep 07, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [038f57c2d8](https://linux-hardware.org/?probe=038f57c2d8) | Sep 06, 2022 |
| MSI           | Z87-G41 PC Mate             | [775e007fc8](https://linux-hardware.org/?probe=775e007fc8) | Sep 05, 2022 |
| Intel         | B75                         | [eca0b46101](https://linux-hardware.org/?probe=eca0b46101) | Sep 05, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [43267285d4](https://linux-hardware.org/?probe=43267285d4) | Sep 04, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [518aa50eb0](https://linux-hardware.org/?probe=518aa50eb0) | Sep 04, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [4a27f8b033](https://linux-hardware.org/?probe=4a27f8b033) | Sep 04, 2022 |
| HP            | 8054                        | [878115f808](https://linux-hardware.org/?probe=878115f808) | Sep 04, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [65562b09e0](https://linux-hardware.org/?probe=65562b09e0) | Sep 03, 2022 |
| BESSTAR Te... | UM700                       | [f1198508de](https://linux-hardware.org/?probe=f1198508de) | Sep 03, 2022 |
| Dell          | 07PR60 A01                  | [d37a4374eb](https://linux-hardware.org/?probe=d37a4374eb) | Sep 02, 2022 |
| ASUSTek       | P6X58D-E                    | [cf774b3e03](https://linux-hardware.org/?probe=cf774b3e03) | Sep 02, 2022 |
| HP            | 8054                        | [1586ce33d1](https://linux-hardware.org/?probe=1586ce33d1) | Sep 02, 2022 |
| ASRock        | N68-S                       | [df5d34428a](https://linux-hardware.org/?probe=df5d34428a) | Sep 01, 2022 |
| ASUSTek       | M5A78L-M LX3                | [5ba264dfb2](https://linux-hardware.org/?probe=5ba264dfb2) | Sep 01, 2022 |
| ASUSTek       | M5A78L-M LX3                | [169c9af937](https://linux-hardware.org/?probe=169c9af937) | Sep 01, 2022 |
| Lenovo        | SHARKBAY NO DPK             | [f872d36cd5](https://linux-hardware.org/?probe=f872d36cd5) | Sep 01, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | [37695eb7e5](https://linux-hardware.org/?probe=37695eb7e5) | Aug 31, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d816d2ade0](https://linux-hardware.org/?probe=d816d2ade0) | Aug 30, 2022 |
| ASRock        | N68-S                       | [6aabf89438](https://linux-hardware.org/?probe=6aabf89438) | Aug 30, 2022 |
| ASUSTek       | PRIME Z590-P                | [e05dcd4a08](https://linux-hardware.org/?probe=e05dcd4a08) | Aug 29, 2022 |
| ASRock        | FM2A58M-VG3+ R2.0           | [422af9d6b5](https://linux-hardware.org/?probe=422af9d6b5) | Aug 29, 2022 |
| ASRock        | N68-S                       | [4fff0a6104](https://linux-hardware.org/?probe=4fff0a6104) | Aug 29, 2022 |
| ASUSTek       | ProArt B550-CREATOR         | [ec9f8ea30e](https://linux-hardware.org/?probe=ec9f8ea30e) | Aug 28, 2022 |
| ASRock        | B550M Pro4                  | [8c6b85a46c](https://linux-hardware.org/?probe=8c6b85a46c) | Aug 27, 2022 |
| ASRock        | B450M Pro4                  | [f4fe5fd168](https://linux-hardware.org/?probe=f4fe5fd168) | Aug 27, 2022 |
| Gigabyte      | B550 GAMING X V2            | [94e2f7cedc](https://linux-hardware.org/?probe=94e2f7cedc) | Aug 27, 2022 |
| Dell          | 0KWVT8 A02                  | [3f9c00b0da](https://linux-hardware.org/?probe=3f9c00b0da) | Aug 27, 2022 |
| ASRock        | X99 WS                      | [d16d59fab2](https://linux-hardware.org/?probe=d16d59fab2) | Aug 26, 2022 |
| ASUSTek       | Z170-P                      | [0bd08aee88](https://linux-hardware.org/?probe=0bd08aee88) | Aug 24, 2022 |
| Gigabyte      | B550M S2H                   | [8b5fe2494e](https://linux-hardware.org/?probe=8b5fe2494e) | Aug 23, 2022 |
| ASUSTek       | PRIME B450M-A               | [bfdd1ab294](https://linux-hardware.org/?probe=bfdd1ab294) | Aug 23, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [0dbe2c5dfd](https://linux-hardware.org/?probe=0dbe2c5dfd) | Aug 22, 2022 |
| MACHINIST     | H81M-PRO S1 V2.0            | [12be75fa90](https://linux-hardware.org/?probe=12be75fa90) | Aug 21, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [3b799e56c6](https://linux-hardware.org/?probe=3b799e56c6) | Aug 21, 2022 |
| MSI           | P55-GD55                    | [89f2c92fa1](https://linux-hardware.org/?probe=89f2c92fa1) | Aug 21, 2022 |
| ASUSTek       | PRIME B365M-C               | [8ae386a7a0](https://linux-hardware.org/?probe=8ae386a7a0) | Aug 20, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [1d1f39fd1b](https://linux-hardware.org/?probe=1d1f39fd1b) | Aug 19, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [d59342b7a4](https://linux-hardware.org/?probe=d59342b7a4) | Aug 19, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [e61c3cee8a](https://linux-hardware.org/?probe=e61c3cee8a) | Aug 18, 2022 |
| ASRock        | B550M Pro4                  | [41b271c4e7](https://linux-hardware.org/?probe=41b271c4e7) | Aug 17, 2022 |
| Gigabyte      | H61M-S2P                    | [49aedf1cf8](https://linux-hardware.org/?probe=49aedf1cf8) | Aug 17, 2022 |
| Gigabyte      | B550M S2H                   | [e04617befa](https://linux-hardware.org/?probe=e04617befa) | Aug 17, 2022 |
| MSI           | Z87-G41 PC Mate             | [08e79a0a1c](https://linux-hardware.org/?probe=08e79a0a1c) | Aug 16, 2022 |
| MSI           | X470 GAMING PRO             | [52b08fd4ba](https://linux-hardware.org/?probe=52b08fd4ba) | Aug 16, 2022 |
| ASRock        | Z77 Extreme4                | [07e825ed5b](https://linux-hardware.org/?probe=07e825ed5b) | Aug 16, 2022 |
| VS Company    | H61H2                       | [a0b88242a4](https://linux-hardware.org/?probe=a0b88242a4) | Aug 16, 2022 |
| Gigabyte      | B450 AORUS M                | [bdf5ba285f](https://linux-hardware.org/?probe=bdf5ba285f) | Aug 15, 2022 |
| Gigabyte      | B550M S2H                   | [db7b7b3126](https://linux-hardware.org/?probe=db7b7b3126) | Aug 15, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | [2fb0eea98c](https://linux-hardware.org/?probe=2fb0eea98c) | Aug 15, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [76e185a2e5](https://linux-hardware.org/?probe=76e185a2e5) | Aug 15, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [59b6bdadd3](https://linux-hardware.org/?probe=59b6bdadd3) | Aug 14, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | [45ddbf814d](https://linux-hardware.org/?probe=45ddbf814d) | Aug 14, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [e63db5769a](https://linux-hardware.org/?probe=e63db5769a) | Aug 14, 2022 |
| ASRock        | 990FX Extreme3              | [646169ae62](https://linux-hardware.org/?probe=646169ae62) | Aug 14, 2022 |
| HP            | 82A2                        | [bc3d667d42](https://linux-hardware.org/?probe=bc3d667d42) | Aug 13, 2022 |
| MSI           | B350M PRO-VD PLUS           | [ba65d9b67e](https://linux-hardware.org/?probe=ba65d9b67e) | Aug 13, 2022 |
| MSI           | 970A SLI Krait Edition      | [a94fe940b1](https://linux-hardware.org/?probe=a94fe940b1) | Aug 13, 2022 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | [41560e8e13](https://linux-hardware.org/?probe=41560e8e13) | Aug 12, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [f82761570b](https://linux-hardware.org/?probe=f82761570b) | Aug 12, 2022 |
| AZW           | U59                         | [344d4587f6](https://linux-hardware.org/?probe=344d4587f6) | Aug 12, 2022 |
| ASRock        | 990FX Extreme3              | [e3006f6ca1](https://linux-hardware.org/?probe=e3006f6ca1) | Aug 11, 2022 |
| ASUSTek       | Z87-PRO                     | [f8a688c41e](https://linux-hardware.org/?probe=f8a688c41e) | Aug 11, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [3219cc3946](https://linux-hardware.org/?probe=3219cc3946) | Aug 10, 2022 |
| HP            | 8053                        | [db80dc0ee1](https://linux-hardware.org/?probe=db80dc0ee1) | Aug 10, 2022 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | [48b0dfdee0](https://linux-hardware.org/?probe=48b0dfdee0) | Aug 10, 2022 |
| Unknown       | Unknown                     | [e4c7906333](https://linux-hardware.org/?probe=e4c7906333) | Aug 09, 2022 |
| Lenovo        | Bantry CRB NOK              | [fbeb21c99a](https://linux-hardware.org/?probe=fbeb21c99a) | Aug 09, 2022 |
| ASUSTek       | G10DK                       | [2401d4af44](https://linux-hardware.org/?probe=2401d4af44) | Aug 08, 2022 |
| MSI           | MAG B550M MORTAR            | [7cf010b820](https://linux-hardware.org/?probe=7cf010b820) | Aug 08, 2022 |
| ASRock        | B450 Pro4                   | [b87492e7c7](https://linux-hardware.org/?probe=b87492e7c7) | Aug 08, 2022 |
| Gigabyte      | B150M-D3H-CF                | [5235533a87](https://linux-hardware.org/?probe=5235533a87) | Aug 07, 2022 |
| MSI           | B550-A PRO                  | [a3aa8d0879](https://linux-hardware.org/?probe=a3aa8d0879) | Aug 05, 2022 |
| Dell          | 0XR1GT A00                  | [2e069ba5c2](https://linux-hardware.org/?probe=2e069ba5c2) | Aug 04, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [e963ce265b](https://linux-hardware.org/?probe=e963ce265b) | Aug 04, 2022 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | [22b43d3149](https://linux-hardware.org/?probe=22b43d3149) | Aug 04, 2022 |
| ECS           | H61H2-MV                    | [6b2a77a281](https://linux-hardware.org/?probe=6b2a77a281) | Aug 02, 2022 |
| MSI           | B450 GAMING PRO CARBON M... | [5951f66289](https://linux-hardware.org/?probe=5951f66289) | Aug 02, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [30e0a23365](https://linux-hardware.org/?probe=30e0a23365) | Aug 01, 2022 |
| ASUSTek       | F2A55-M LK2                 | [97a5e9c390](https://linux-hardware.org/?probe=97a5e9c390) | Aug 01, 2022 |
| Dell          | 0D24M8 A00                  | [6367e245e6](https://linux-hardware.org/?probe=6367e245e6) | Jul 31, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [9ea9e6f737](https://linux-hardware.org/?probe=9ea9e6f737) | Jul 30, 2022 |
| MSI           | X470 GAMING PRO MAX         | [5651db0a63](https://linux-hardware.org/?probe=5651db0a63) | Jul 30, 2022 |
| ASRock        | H81M-VG4                    | [1fd9e0ca3a](https://linux-hardware.org/?probe=1fd9e0ca3a) | Jul 30, 2022 |
| ASRock        | H81M-VG4                    | [309df31c47](https://linux-hardware.org/?probe=309df31c47) | Jul 30, 2022 |
| ASUSTek       | PRIME Z590-P                | [fa38197b4d](https://linux-hardware.org/?probe=fa38197b4d) | Jul 29, 2022 |
| Lenovo        | 3133 SDK0J40675 WIN 3305... | [4434d4d78a](https://linux-hardware.org/?probe=4434d4d78a) | Jul 29, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [f666b16fde](https://linux-hardware.org/?probe=f666b16fde) | Jul 28, 2022 |
| Gigabyte      | H97-Gaming 3                | [90656d8ef4](https://linux-hardware.org/?probe=90656d8ef4) | Jul 27, 2022 |
| Lenovo        | 3717 SDK0J40697 WIN 3305... | [701f519b4c](https://linux-hardware.org/?probe=701f519b4c) | Jul 27, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [b41540a078](https://linux-hardware.org/?probe=b41540a078) | Jul 26, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [331a99ef9a](https://linux-hardware.org/?probe=331a99ef9a) | Jul 26, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [1f3433b9e1](https://linux-hardware.org/?probe=1f3433b9e1) | Jul 26, 2022 |
| Gigabyte      | 990XA-UD3                   | [803bd277e7](https://linux-hardware.org/?probe=803bd277e7) | Jul 26, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [0c310749f1](https://linux-hardware.org/?probe=0c310749f1) | Jul 26, 2022 |
| Gigabyte      | H61M-D2P-B3                 | [8f0769b485](https://linux-hardware.org/?probe=8f0769b485) | Jul 25, 2022 |
| Gigabyte      | Z68P-DS3                    | [b03f1fee53](https://linux-hardware.org/?probe=b03f1fee53) | Jul 24, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [e512b2f9f2](https://linux-hardware.org/?probe=e512b2f9f2) | Jul 23, 2022 |
| Dell          | 0GM819                      | [8c617c1c3f](https://linux-hardware.org/?probe=8c617c1c3f) | Jul 23, 2022 |
| BESSTAR Te... | HM90                        | [cb4da5b649](https://linux-hardware.org/?probe=cb4da5b649) | Jul 23, 2022 |
| MSI           | B450M PRO-VDH MAX           | [9002ca2e54](https://linux-hardware.org/?probe=9002ca2e54) | Jul 23, 2022 |
| ASUSTek       | Maximus Formula             | [2e71fca3d5](https://linux-hardware.org/?probe=2e71fca3d5) | Jul 22, 2022 |
| BESSTAR Te... | HM90                        | [380230bbf6](https://linux-hardware.org/?probe=380230bbf6) | Jul 22, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [51c2b5bc3b](https://linux-hardware.org/?probe=51c2b5bc3b) | Jul 22, 2022 |
| MACHINIST     | X79 V2.82H                  | [da4a098248](https://linux-hardware.org/?probe=da4a098248) | Jul 22, 2022 |
| MACHINIST     | X79 V2.82H                  | [0e06f3fdf5](https://linux-hardware.org/?probe=0e06f3fdf5) | Jul 22, 2022 |
| ASUSTek       | P9X79                       | [5ff04691ce](https://linux-hardware.org/?probe=5ff04691ce) | Jul 21, 2022 |
| ASUSTek       | P9X79                       | [1bcee43b6e](https://linux-hardware.org/?probe=1bcee43b6e) | Jul 21, 2022 |
| ASRock        | Z77 Extreme4                | [492529f973](https://linux-hardware.org/?probe=492529f973) | Jul 21, 2022 |
| PCWare        | IPMH81G1                    | [cb66716a63](https://linux-hardware.org/?probe=cb66716a63) | Jul 21, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [1a28383fee](https://linux-hardware.org/?probe=1a28383fee) | Jul 19, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [63489ff6e5](https://linux-hardware.org/?probe=63489ff6e5) | Jul 19, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [fd46c32d92](https://linux-hardware.org/?probe=fd46c32d92) | Jul 19, 2022 |
| ASUSTek       | Maximus Formula             | [3c600cafa6](https://linux-hardware.org/?probe=3c600cafa6) | Jul 17, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [b28f8248b4](https://linux-hardware.org/?probe=b28f8248b4) | Jul 17, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [84d62872f5](https://linux-hardware.org/?probe=84d62872f5) | Jul 17, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [3b1f082065](https://linux-hardware.org/?probe=3b1f082065) | Jul 16, 2022 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | [3605f29c73](https://linux-hardware.org/?probe=3605f29c73) | Jul 16, 2022 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | [533392d790](https://linux-hardware.org/?probe=533392d790) | Jul 16, 2022 |
| Gigabyte      | A520M S2H                   | [dfc64d417f](https://linux-hardware.org/?probe=dfc64d417f) | Jul 15, 2022 |
| ASUSTek       | M5A97 R2.0                  | [06992e615b](https://linux-hardware.org/?probe=06992e615b) | Jul 15, 2022 |
| BESSTAR Te... | TL50                        | [c77ff65710](https://linux-hardware.org/?probe=c77ff65710) | Jul 15, 2022 |
| ASRock        | B550M Pro4                  | [dcdc04db9f](https://linux-hardware.org/?probe=dcdc04db9f) | Jul 14, 2022 |
| Gigabyte      | Z97-D3H-CF                  | [55f956b817](https://linux-hardware.org/?probe=55f956b817) | Jul 14, 2022 |
| MSI           | A320M-A PRO MAX             | [31127e76f8](https://linux-hardware.org/?probe=31127e76f8) | Jul 14, 2022 |
| MSI           | X470 GAMING PRO             | [716dd72eeb](https://linux-hardware.org/?probe=716dd72eeb) | Jul 13, 2022 |
| ASUSTek       | Maximus Formula             | [cd81bcaf19](https://linux-hardware.org/?probe=cd81bcaf19) | Jul 13, 2022 |
| MSI           | A320M-A PRO MAX             | [ed83060c1a](https://linux-hardware.org/?probe=ed83060c1a) | Jul 13, 2022 |
| ASUSTek       | M5A97 R2.0                  | [8bdaa5b844](https://linux-hardware.org/?probe=8bdaa5b844) | Jul 13, 2022 |
| BESSTAR Te... | UM350                       | [7437e30da5](https://linux-hardware.org/?probe=7437e30da5) | Jul 11, 2022 |
| MSI           | Z77A-G45                    | [ff2bae4518](https://linux-hardware.org/?probe=ff2bae4518) | Jul 11, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [5c8deeb62c](https://linux-hardware.org/?probe=5c8deeb62c) | Jul 10, 2022 |
| MSI           | H110M PRO-VH PLUS           | [02cbc3a4ae](https://linux-hardware.org/?probe=02cbc3a4ae) | Jul 10, 2022 |
| MSI           | Z77A-G45                    | [2d4a011972](https://linux-hardware.org/?probe=2d4a011972) | Jul 10, 2022 |
| Gigabyte      | B365M DS3H                  | [8c2d8a89d0](https://linux-hardware.org/?probe=8c2d8a89d0) | Jul 10, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [5dc09a66d8](https://linux-hardware.org/?probe=5dc09a66d8) | Jul 08, 2022 |
| ASUSTek       | M5A97 R2.0                  | [b46404cc89](https://linux-hardware.org/?probe=b46404cc89) | Jul 07, 2022 |
| Dell          | 0NK5PH A00                  | [6e17948aa5](https://linux-hardware.org/?probe=6e17948aa5) | Jul 07, 2022 |
| Dell          | 0NK5PH A00                  | [56b772ade4](https://linux-hardware.org/?probe=56b772ade4) | Jul 07, 2022 |
| ASRock        | B450M Pro4 R2.0             | [d9dc513be7](https://linux-hardware.org/?probe=d9dc513be7) | Jul 06, 2022 |
| Fujitsu       | D2981-A1 S26361-D2981-A1    | [5e40d26a2b](https://linux-hardware.org/?probe=5e40d26a2b) | Jul 06, 2022 |
| Inventec      | D CLASS A02                 | [ac1652fd54](https://linux-hardware.org/?probe=ac1652fd54) | Jul 06, 2022 |
| ASUSTek       | PRIME B550M-A               | [a5e8e3a046](https://linux-hardware.org/?probe=a5e8e3a046) | Jul 05, 2022 |
| ASRock        | B550M Pro4                  | [39803eaf94](https://linux-hardware.org/?probe=39803eaf94) | Jul 04, 2022 |
| ASRock        | B550M Pro4                  | [747051c1fc](https://linux-hardware.org/?probe=747051c1fc) | Jul 04, 2022 |
| MSI           | B250M PRO-VDH               | [fb76db49bd](https://linux-hardware.org/?probe=fb76db49bd) | Jul 04, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [327086a8b8](https://linux-hardware.org/?probe=327086a8b8) | Jul 04, 2022 |
| ASRock        | IMB-1213                    | [6e1ba0ba69](https://linux-hardware.org/?probe=6e1ba0ba69) | Jul 04, 2022 |
| HP            | 0A9Ch                       | [3dafdd1a3f](https://linux-hardware.org/?probe=3dafdd1a3f) | Jul 03, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [6918411ee2](https://linux-hardware.org/?probe=6918411ee2) | Jul 03, 2022 |
| ASUSTek       | PRIME A320M-K               | [a381b573f6](https://linux-hardware.org/?probe=a381b573f6) | Jul 03, 2022 |
| ASUSTek       | PRIME X570-P                | [1a729c627d](https://linux-hardware.org/?probe=1a729c627d) | Jul 03, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [c633887935](https://linux-hardware.org/?probe=c633887935) | Jul 02, 2022 |
| MSI           | X370 GAMING PRO CARBON      | [5763cb4576](https://linux-hardware.org/?probe=5763cb4576) | Jul 01, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [21dd020507](https://linux-hardware.org/?probe=21dd020507) | Jul 01, 2022 |
| MSI           | PRESTIGE X570 CREATION      | [7f17faf180](https://linux-hardware.org/?probe=7f17faf180) | Jun 30, 2022 |
| HP            | 0B54h D                     | [bef89f554e](https://linux-hardware.org/?probe=bef89f554e) | Jun 30, 2022 |
| Gigabyte      | B450M DS3H-CF               | [6a2f1d22f1](https://linux-hardware.org/?probe=6a2f1d22f1) | Jun 29, 2022 |
| Gigabyte      | B450M DS3H-CF               | [0a976062da](https://linux-hardware.org/?probe=0a976062da) | Jun 29, 2022 |
| ASRock        | H61M-ITX                    | [e8d5e4ff14](https://linux-hardware.org/?probe=e8d5e4ff14) | Jun 29, 2022 |
| ASUSTek       | PRIME Z390-P                | [97613877b7](https://linux-hardware.org/?probe=97613877b7) | Jun 29, 2022 |
| Gigabyte      | B550 AORUS MASTER           | [be4dd3360f](https://linux-hardware.org/?probe=be4dd3360f) | Jun 28, 2022 |
| Gigabyte      | A520M DS3H                  | [b56fe3beb3](https://linux-hardware.org/?probe=b56fe3beb3) | Jun 28, 2022 |
| ASUSTek       | PRIME Z690-P WIFI           | [0441b2cf28](https://linux-hardware.org/?probe=0441b2cf28) | Jun 27, 2022 |
| HP            | 212B                        | [687ca162d2](https://linux-hardware.org/?probe=687ca162d2) | Jun 27, 2022 |
| ASUSTek       | PRIME Z690-P WIFI           | [ca055793c5](https://linux-hardware.org/?probe=ca055793c5) | Jun 27, 2022 |
| ASUSTek       | PRIME B450M-K               | [441cba3212](https://linux-hardware.org/?probe=441cba3212) | Jun 27, 2022 |
| Gigabyte      | H370M DS3H-CF               | [862d58f1a4](https://linux-hardware.org/?probe=862d58f1a4) | Jun 27, 2022 |
| MSI           | A320M PRO-M2 V2             | [a801c7c2ba](https://linux-hardware.org/?probe=a801c7c2ba) | Jun 27, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [da1c9472bd](https://linux-hardware.org/?probe=da1c9472bd) | Jun 27, 2022 |
| ASRock        | A320M-HDV R4.0              | [0e8993f232](https://linux-hardware.org/?probe=0e8993f232) | Jun 27, 2022 |
| ASRock        | B550M Pro4                  | [92d424a6b5](https://linux-hardware.org/?probe=92d424a6b5) | Jun 26, 2022 |
| Minix         | NEO Z83-4 V1.1              | [4fd5881226](https://linux-hardware.org/?probe=4fd5881226) | Jun 26, 2022 |
| Minix         | NEO Z83-4 V1.1              | [01e2541b47](https://linux-hardware.org/?probe=01e2541b47) | Jun 26, 2022 |
| Dell          | 088DT1 A01                  | [6b2aa6c257](https://linux-hardware.org/?probe=6b2aa6c257) | Jun 26, 2022 |
| Dell          | 088DT1 A01                  | [dae78cdc9e](https://linux-hardware.org/?probe=dae78cdc9e) | Jun 26, 2022 |
| ASRock        | Z77 Extreme4                | [b397f63621](https://linux-hardware.org/?probe=b397f63621) | Jun 26, 2022 |
| ASRock        | H61M-ITX                    | [6c9ee0dadd](https://linux-hardware.org/?probe=6c9ee0dadd) | Jun 26, 2022 |
| ASRock        | B450M Pro4 R2.0             | [f1e0998426](https://linux-hardware.org/?probe=f1e0998426) | Jun 25, 2022 |
| ASRock        | B450M Pro4 R2.0             | [abdb925c2a](https://linux-hardware.org/?probe=abdb925c2a) | Jun 24, 2022 |
| Gigabyte      | MQLP5AP-00                  | [fad6b4b320](https://linux-hardware.org/?probe=fad6b4b320) | Jun 24, 2022 |
| Gigabyte      | B450M S2H V2                | [e0e21604de](https://linux-hardware.org/?probe=e0e21604de) | Jun 24, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [4a8c282d59](https://linux-hardware.org/?probe=4a8c282d59) | Jun 24, 2022 |
| ASRock        | H510M-ITX/ac                | [f1e5f3d686](https://linux-hardware.org/?probe=f1e5f3d686) | Jun 23, 2022 |
| ECS           | H61H2-MV                    | [6035d3cf75](https://linux-hardware.org/?probe=6035d3cf75) | Jun 22, 2022 |
| Gigabyte      | 970A-DS3P                   | [43c1598008](https://linux-hardware.org/?probe=43c1598008) | Jun 22, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [0e6a585307](https://linux-hardware.org/?probe=0e6a585307) | Jun 21, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [7063b6a7ef](https://linux-hardware.org/?probe=7063b6a7ef) | Jun 21, 2022 |
| ASRock        | B550M Pro4                  | [ab46a92e42](https://linux-hardware.org/?probe=ab46a92e42) | Jun 20, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [1bd776020e](https://linux-hardware.org/?probe=1bd776020e) | Jun 20, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [75d908e7db](https://linux-hardware.org/?probe=75d908e7db) | Jun 19, 2022 |
| ASUSTek       | M5A97 R2.0                  | [df832fa379](https://linux-hardware.org/?probe=df832fa379) | Jun 18, 2022 |
| Gigabyte      | B450 AORUS M                | [8b1fb7056f](https://linux-hardware.org/?probe=8b1fb7056f) | Jun 17, 2022 |
| Gigabyte      | B450 AORUS M                | [277df992e4](https://linux-hardware.org/?probe=277df992e4) | Jun 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [530c081484](https://linux-hardware.org/?probe=530c081484) | Jun 17, 2022 |
| ASRock        | AB350M-HDV                  | [65478d1857](https://linux-hardware.org/?probe=65478d1857) | Jun 17, 2022 |
| Gigabyte      | X399 AORUS Gaming 7         | [b9de371265](https://linux-hardware.org/?probe=b9de371265) | Jun 17, 2022 |
| Gigabyte      | X399 AORUS Gaming 7         | [d987e4522e](https://linux-hardware.org/?probe=d987e4522e) | Jun 17, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [4a8163d07f](https://linux-hardware.org/?probe=4a8163d07f) | Jun 17, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [cee122d15f](https://linux-hardware.org/?probe=cee122d15f) | Jun 16, 2022 |
| AZW           | U59                         | [5a661910dc](https://linux-hardware.org/?probe=5a661910dc) | Jun 16, 2022 |
| Unknown       | Unknown                     | [87eb57392c](https://linux-hardware.org/?probe=87eb57392c) | Jun 16, 2022 |
| MSI           | B360M PRO-VD                | [fa86b2da10](https://linux-hardware.org/?probe=fa86b2da10) | Jun 15, 2022 |
| Gigabyte      | B560M AORUS PRO AX          | [a46a8033f8](https://linux-hardware.org/?probe=a46a8033f8) | Jun 15, 2022 |
| ASRock        | B550M Pro4                  | [4dc0746a65](https://linux-hardware.org/?probe=4dc0746a65) | Jun 15, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [7587cca95a](https://linux-hardware.org/?probe=7587cca95a) | Jun 14, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | [0b792ecaef](https://linux-hardware.org/?probe=0b792ecaef) | Jun 14, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [d0050d4fcd](https://linux-hardware.org/?probe=d0050d4fcd) | Jun 14, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | [9dae5c70a5](https://linux-hardware.org/?probe=9dae5c70a5) | Jun 14, 2022 |
| Dell          | 0D28YY A00                  | [18487dbcb1](https://linux-hardware.org/?probe=18487dbcb1) | Jun 14, 2022 |
| ASRock        | B550M Pro4                  | [5c9ca9542b](https://linux-hardware.org/?probe=5c9ca9542b) | Jun 13, 2022 |
| HP            | 212B                        | [2680c53ca7](https://linux-hardware.org/?probe=2680c53ca7) | Jun 13, 2022 |
| ASRock        | B550M Pro4                  | [275c522503](https://linux-hardware.org/?probe=275c522503) | Jun 13, 2022 |
| Unknown       | 1.0                         | [8c8f612260](https://linux-hardware.org/?probe=8c8f612260) | Jun 13, 2022 |
| Huanan        | X99-TF V2.0                 | [cf8091c979](https://linux-hardware.org/?probe=cf8091c979) | Jun 13, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [feca5f6bb5](https://linux-hardware.org/?probe=feca5f6bb5) | Jun 12, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | [1d0ca4cb7a](https://linux-hardware.org/?probe=1d0ca4cb7a) | Jun 12, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | [ded6b87e98](https://linux-hardware.org/?probe=ded6b87e98) | Jun 12, 2022 |
| HP            | 0A9Ch                       | [bd8345d324](https://linux-hardware.org/?probe=bd8345d324) | Jun 12, 2022 |
| Gigabyte      | H510M H                     | [7b1a78a681](https://linux-hardware.org/?probe=7b1a78a681) | Jun 11, 2022 |
| Gigabyte      | Z68P-DS3                    | [03554389d5](https://linux-hardware.org/?probe=03554389d5) | Jun 11, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [568b23271e](https://linux-hardware.org/?probe=568b23271e) | Jun 11, 2022 |
| Gigabyte      | B550M DS3H                  | [32415f8bd1](https://linux-hardware.org/?probe=32415f8bd1) | Jun 10, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [0dd5653fc1](https://linux-hardware.org/?probe=0dd5653fc1) | Jun 10, 2022 |
| Gigabyte      | Z97X-SLI-CF                 | [294890a076](https://linux-hardware.org/?probe=294890a076) | Jun 10, 2022 |
| ASUSTek       | ROG STRIX B360-I GAMING     | [1b4307a298](https://linux-hardware.org/?probe=1b4307a298) | Jun 09, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | [c18fee9219](https://linux-hardware.org/?probe=c18fee9219) | Jun 08, 2022 |
| MSI           | H81M-E33                    | [49191a1c98](https://linux-hardware.org/?probe=49191a1c98) | Jun 08, 2022 |
| MSI           | B350 GAMING PRO CARBON      | [2f1acce421](https://linux-hardware.org/?probe=2f1acce421) | Jun 08, 2022 |
| HP            | 1998                        | [fd5184fe12](https://linux-hardware.org/?probe=fd5184fe12) | Jun 08, 2022 |
| ASRock        | B550M Pro4                  | [10fbde5027](https://linux-hardware.org/?probe=10fbde5027) | Jun 07, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [25213ed098](https://linux-hardware.org/?probe=25213ed098) | Jun 07, 2022 |
| Gigabyte      | Z690 AORUS PRO DDR4         | [1196dd3b41](https://linux-hardware.org/?probe=1196dd3b41) | Jun 06, 2022 |
| MSI           | B350M PRO-VDH               | [ae45bf67a3](https://linux-hardware.org/?probe=ae45bf67a3) | Jun 06, 2022 |
| Gigabyte      | Z690 AORUS PRO DDR4         | [15efe8a0a2](https://linux-hardware.org/?probe=15efe8a0a2) | Jun 06, 2022 |
| MSI           | H81M-E33                    | [6a2d6cbe74](https://linux-hardware.org/?probe=6a2d6cbe74) | Jun 04, 2022 |
| BESSTAR Te... | UM700                       | [ea24f8341e](https://linux-hardware.org/?probe=ea24f8341e) | Jun 02, 2022 |
| BESSTAR Te... | UM700                       | [d3799b37d7](https://linux-hardware.org/?probe=d3799b37d7) | Jun 02, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [829ee446bd](https://linux-hardware.org/?probe=829ee446bd) | Jun 02, 2022 |
| MSI           | B350 TOMAHAWK               | [b9cdc775ea](https://linux-hardware.org/?probe=b9cdc775ea) | Jun 02, 2022 |
| ASRock        | B550M Pro4                  | [9ac2f5ba04](https://linux-hardware.org/?probe=9ac2f5ba04) | Jun 01, 2022 |
| MSI           | H81I                        | [6b4e34a35e](https://linux-hardware.org/?probe=6b4e34a35e) | Jun 01, 2022 |
| MSI           | B250M PRO-VDH               | [eede963720](https://linux-hardware.org/?probe=eede963720) | May 31, 2022 |
| MSI           | B250M PRO-VDH               | [e2dd690b16](https://linux-hardware.org/?probe=e2dd690b16) | May 31, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [a6506e0582](https://linux-hardware.org/?probe=a6506e0582) | May 30, 2022 |
| ASRock        | B550M Pro4                  | [a5eee874a5](https://linux-hardware.org/?probe=a5eee874a5) | May 30, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [0050247c85](https://linux-hardware.org/?probe=0050247c85) | May 29, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [1416d5a87d](https://linux-hardware.org/?probe=1416d5a87d) | May 29, 2022 |
| Google        | Guado                       | [d026c0565d](https://linux-hardware.org/?probe=d026c0565d) | May 29, 2022 |
| ASRock        | B550M Pro4                  | [4e2d37a90d](https://linux-hardware.org/?probe=4e2d37a90d) | May 29, 2022 |
| ASRock        | B550M Pro4                  | [b861a73ade](https://linux-hardware.org/?probe=b861a73ade) | May 28, 2022 |
| Gigabyte      | B450M DS3H-CF               | [c3d1916e14](https://linux-hardware.org/?probe=c3d1916e14) | May 28, 2022 |
| Gigabyte      | MCMLUCB-00                  | [90c886e471](https://linux-hardware.org/?probe=90c886e471) | May 27, 2022 |
| Dell          | 0KP561                      | [2435960bba](https://linux-hardware.org/?probe=2435960bba) | May 27, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [63690e08a1](https://linux-hardware.org/?probe=63690e08a1) | May 27, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [d1891c2d3b](https://linux-hardware.org/?probe=d1891c2d3b) | May 27, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [bf3f9d0ed3](https://linux-hardware.org/?probe=bf3f9d0ed3) | May 26, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [c9c34c5c6f](https://linux-hardware.org/?probe=c9c34c5c6f) | May 26, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [c8f47b62d2](https://linux-hardware.org/?probe=c8f47b62d2) | May 26, 2022 |
| ASRock        | B550M Pro4                  | [d5df82a4ce](https://linux-hardware.org/?probe=d5df82a4ce) | May 25, 2022 |
| ASRock        | H670M-ITX/ax                | [c11c9ac073](https://linux-hardware.org/?probe=c11c9ac073) | May 25, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | [0390e0a7c2](https://linux-hardware.org/?probe=0390e0a7c2) | May 25, 2022 |
| MSI           | X470 GAMING PRO             | [8409fe7eab](https://linux-hardware.org/?probe=8409fe7eab) | May 24, 2022 |
| ASRock        | B550M Pro4                  | [35ba2b5a7a](https://linux-hardware.org/?probe=35ba2b5a7a) | May 24, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [7375e6d7ec](https://linux-hardware.org/?probe=7375e6d7ec) | May 24, 2022 |
| Unknown       | Unknown                     | [62b61f57ef](https://linux-hardware.org/?probe=62b61f57ef) | May 24, 2022 |
| Gigabyte      | Z77M-D3H                    | [b7369242f9](https://linux-hardware.org/?probe=b7369242f9) | May 23, 2022 |
| Google        | Guado                       | [3245615e95](https://linux-hardware.org/?probe=3245615e95) | May 23, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [de3cd5c495](https://linux-hardware.org/?probe=de3cd5c495) | May 23, 2022 |
| ASRock        | Z77 Extreme4                | [198a8b039a](https://linux-hardware.org/?probe=198a8b039a) | May 22, 2022 |
| ASRock        | Z77 Extreme4                | [3c45f702eb](https://linux-hardware.org/?probe=3c45f702eb) | May 22, 2022 |
| MSI           | H97M-G43                    | [3869b1146e](https://linux-hardware.org/?probe=3869b1146e) | May 22, 2022 |
| ASRock        | B550M Pro4                  | [85974104c5](https://linux-hardware.org/?probe=85974104c5) | May 21, 2022 |
| MSI           | Z390-A PRO                  | [8baf319c52](https://linux-hardware.org/?probe=8baf319c52) | May 21, 2022 |
| Gigabyte      | H61M-S2PV                   | [4dce3bdb3a](https://linux-hardware.org/?probe=4dce3bdb3a) | May 21, 2022 |
| Chatreey      | AC1-DP                      | [aefe90ce82](https://linux-hardware.org/?probe=aefe90ce82) | May 20, 2022 |
| HP            | 212B                        | [a52da35d02](https://linux-hardware.org/?probe=a52da35d02) | May 20, 2022 |
| Gigabyte      | Z270-HD3P-CF                | [1efa62dcdb](https://linux-hardware.org/?probe=1efa62dcdb) | May 19, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [bcb2dd930d](https://linux-hardware.org/?probe=bcb2dd930d) | May 19, 2022 |
| HP            | 8053                        | [67ea3799ad](https://linux-hardware.org/?probe=67ea3799ad) | May 18, 2022 |
| MSI           | X99S GAMING 7               | [ff6fe109c0](https://linux-hardware.org/?probe=ff6fe109c0) | May 17, 2022 |
| ASUSTek       | PRIME X570-P                | [0e0b2d38d8](https://linux-hardware.org/?probe=0e0b2d38d8) | May 17, 2022 |
| ASUSTek       | PRIME X570-P                | [a80d230e6e](https://linux-hardware.org/?probe=a80d230e6e) | May 17, 2022 |
| ASRock        | B550M Pro4                  | [acd5c94fc8](https://linux-hardware.org/?probe=acd5c94fc8) | May 16, 2022 |
| HP            | 3031h                       | [9a6723ea52](https://linux-hardware.org/?probe=9a6723ea52) | May 16, 2022 |
| HP            | 3031h                       | [414614ec5d](https://linux-hardware.org/?probe=414614ec5d) | May 16, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [798d2cee16](https://linux-hardware.org/?probe=798d2cee16) | May 16, 2022 |
| Gigabyte      | MCMLUCB-00                  | [1ad57be6ad](https://linux-hardware.org/?probe=1ad57be6ad) | May 16, 2022 |
| ASUSTek       | PRIME Z390-P                | [a0c15e2a2f](https://linux-hardware.org/?probe=a0c15e2a2f) | May 16, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [6d1b1bca17](https://linux-hardware.org/?probe=6d1b1bca17) | May 16, 2022 |
| HP            | 8053                        | [35d3caac96](https://linux-hardware.org/?probe=35d3caac96) | May 16, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [178d910ec8](https://linux-hardware.org/?probe=178d910ec8) | May 15, 2022 |
| Gigabyte      | Z97M-DS3H                   | [82b98a2f7e](https://linux-hardware.org/?probe=82b98a2f7e) | May 15, 2022 |
| ASRock        | B550M Pro4                  | [289c04b1dd](https://linux-hardware.org/?probe=289c04b1dd) | May 14, 2022 |
| Dell          | 0C27VV A01                  | [bf0f5c5d07](https://linux-hardware.org/?probe=bf0f5c5d07) | May 14, 2022 |
| ASRock        | X570 Taichi                 | [4d3e26ea12](https://linux-hardware.org/?probe=4d3e26ea12) | May 14, 2022 |
| MSI           | B450M MORTAR MAX            | [0d7682cb61](https://linux-hardware.org/?probe=0d7682cb61) | May 14, 2022 |
| ASUSTek       | Acacia                      | [4b633150fa](https://linux-hardware.org/?probe=4b633150fa) | May 14, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [7a7065c273](https://linux-hardware.org/?probe=7a7065c273) | May 13, 2022 |
| MSI           | MPG Z390 GAMING EDGE AC     | [25654025a8](https://linux-hardware.org/?probe=25654025a8) | May 13, 2022 |
| ASRock        | B550M Pro4                  | [9f9e071e39](https://linux-hardware.org/?probe=9f9e071e39) | May 12, 2022 |
| ASRock        | B550M Pro4                  | [fad48ff5dd](https://linux-hardware.org/?probe=fad48ff5dd) | May 12, 2022 |
| ASUSTek       | P8P67 DELUXE                | [4293bc4b1c](https://linux-hardware.org/?probe=4293bc4b1c) | May 12, 2022 |
| ASUSTek       | P8Z77-V LX                  | [1c124eec80](https://linux-hardware.org/?probe=1c124eec80) | May 12, 2022 |
| Gigabyte      | B550 GAMING X V2            | [326b50009b](https://linux-hardware.org/?probe=326b50009b) | May 12, 2022 |
| ASUSTek       | PRIME X570-PRO              | [23b8b07484](https://linux-hardware.org/?probe=23b8b07484) | May 11, 2022 |
| ASUSTek       | PRIME X570-PRO              | [3fa341f81f](https://linux-hardware.org/?probe=3fa341f81f) | May 11, 2022 |
| Gigabyte      | H97M-HD3                    | [5b0d379b54](https://linux-hardware.org/?probe=5b0d379b54) | May 11, 2022 |
| HP            | 1905                        | [91a5807da1](https://linux-hardware.org/?probe=91a5807da1) | May 10, 2022 |
| HP            | 1905                        | [40dbe34df3](https://linux-hardware.org/?probe=40dbe34df3) | May 10, 2022 |
| MSI           | Z170A GAMING M5             | [766ec913a6](https://linux-hardware.org/?probe=766ec913a6) | May 09, 2022 |
| BESSTAR Te... | UM350                       | [c5234552de](https://linux-hardware.org/?probe=c5234552de) | May 09, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [1906da1cb4](https://linux-hardware.org/?probe=1906da1cb4) | May 08, 2022 |
| Intel         | X79M-S                      | [770b00ef16](https://linux-hardware.org/?probe=770b00ef16) | May 08, 2022 |
| ASRock        | B550M Steel Legend          | [a384972a7a](https://linux-hardware.org/?probe=a384972a7a) | May 08, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [21486c437b](https://linux-hardware.org/?probe=21486c437b) | May 08, 2022 |
| Pegatron      | NARRA5                      | [bfe1e3f80d](https://linux-hardware.org/?probe=bfe1e3f80d) | May 07, 2022 |
| ASUSTek       | P8Z77-V LX                  | [027968f6e4](https://linux-hardware.org/?probe=027968f6e4) | May 07, 2022 |
| ASUSTek       | P8Z77-V LX                  | [72ae77348e](https://linux-hardware.org/?probe=72ae77348e) | May 07, 2022 |
| ASRock        | X370 Taichi                 | [256b60b267](https://linux-hardware.org/?probe=256b60b267) | May 07, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | [093d7ea1c9](https://linux-hardware.org/?probe=093d7ea1c9) | May 06, 2022 |
| ASRock        | H470M-HDV                   | [14d8e1d537](https://linux-hardware.org/?probe=14d8e1d537) | May 06, 2022 |
| MSI           | MEG Z590 GODLIKE            | [0b88e8e449](https://linux-hardware.org/?probe=0b88e8e449) | May 06, 2022 |
| ASRock        | AB350 Pro4                  | [2ce796a070](https://linux-hardware.org/?probe=2ce796a070) | May 05, 2022 |
| MSI           | MEG Z590 GODLIKE            | [ce253bc962](https://linux-hardware.org/?probe=ce253bc962) | May 05, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [3a3a4e634d](https://linux-hardware.org/?probe=3a3a4e634d) | May 05, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [9a2b895663](https://linux-hardware.org/?probe=9a2b895663) | May 04, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [0a2ba1d529](https://linux-hardware.org/?probe=0a2ba1d529) | May 04, 2022 |
| ASUSTek       | P8Z77-V LX                  | [97185f1809](https://linux-hardware.org/?probe=97185f1809) | May 04, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [473e906b63](https://linux-hardware.org/?probe=473e906b63) | May 03, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [9176b48887](https://linux-hardware.org/?probe=9176b48887) | May 03, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [2089066a7d](https://linux-hardware.org/?probe=2089066a7d) | May 03, 2022 |
| MSI           | B450M BAZOOKA PLUS          | [edc5f16866](https://linux-hardware.org/?probe=edc5f16866) | May 03, 2022 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [26aa108efd](https://linux-hardware.org/?probe=26aa108efd) | May 03, 2022 |
| ASUSTek       | PRIME X570-PRO              | [142c1f1a2f](https://linux-hardware.org/?probe=142c1f1a2f) | May 03, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [1fea9af929](https://linux-hardware.org/?probe=1fea9af929) | May 03, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [d49d0283d4](https://linux-hardware.org/?probe=d49d0283d4) | May 03, 2022 |
| Gigabyte      | H81M-S1                     | [8a7d82f85b](https://linux-hardware.org/?probe=8a7d82f85b) | May 03, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [935eb1722b](https://linux-hardware.org/?probe=935eb1722b) | May 02, 2022 |
| ASRock        | AB350 Gaming-ITX/ac         | [9967806049](https://linux-hardware.org/?probe=9967806049) | May 02, 2022 |
| Gigabyte      | A520M H                     | [80f3ccadb9](https://linux-hardware.org/?probe=80f3ccadb9) | May 02, 2022 |
| MSI           | B450 GAMING PLUS            | [a792e309de](https://linux-hardware.org/?probe=a792e309de) | May 02, 2022 |
| ASRock        | B550AM Gaming               | [e31ad2a03f](https://linux-hardware.org/?probe=e31ad2a03f) | May 02, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [45a9821bc8](https://linux-hardware.org/?probe=45a9821bc8) | May 02, 2022 |
| ASUSTek       | PRIME X470-PRO              | [a19c88dc27](https://linux-hardware.org/?probe=a19c88dc27) | May 02, 2022 |
| MSI           | Z77A-G43                    | [2c6195f0b8](https://linux-hardware.org/?probe=2c6195f0b8) | May 02, 2022 |
| MSI           | B450M BAZOOKA               | [a913401ce9](https://linux-hardware.org/?probe=a913401ce9) | May 02, 2022 |
| MSI           | B450M BAZOOKA               | [726be8a4f1](https://linux-hardware.org/?probe=726be8a4f1) | May 02, 2022 |
| ASUSTek       | PRIME B350M-A               | [87542ba2c2](https://linux-hardware.org/?probe=87542ba2c2) | Apr 30, 2022 |
| Gigabyte      | H310N x.x                   | [d0daa33c07](https://linux-hardware.org/?probe=d0daa33c07) | Apr 30, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [da04f72dfc](https://linux-hardware.org/?probe=da04f72dfc) | Apr 30, 2022 |
| ASRock        | Z370 Gaming K6              | [63d2d272b6](https://linux-hardware.org/?probe=63d2d272b6) | Apr 30, 2022 |
| MSI           | MEG Z590 GODLIKE            | [d0ca0e52ad](https://linux-hardware.org/?probe=d0ca0e52ad) | Apr 28, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [29e1e28903](https://linux-hardware.org/?probe=29e1e28903) | Apr 28, 2022 |
| MSI           | MEG Z590 GODLIKE            | [a2f86e2fea](https://linux-hardware.org/?probe=a2f86e2fea) | Apr 28, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [6f7b2f6a78](https://linux-hardware.org/?probe=6f7b2f6a78) | Apr 28, 2022 |
| ASRock        | B550M Pro4                  | [31f358fdd0](https://linux-hardware.org/?probe=31f358fdd0) | Apr 28, 2022 |
| Gigabyte      | X570 UD                     | [67f24b974b](https://linux-hardware.org/?probe=67f24b974b) | Apr 27, 2022 |
| ASRock        | AB350M-HDV                  | [6ee4ea44a8](https://linux-hardware.org/?probe=6ee4ea44a8) | Apr 27, 2022 |
| Dell          | 00V62H A01                  | [7c7b023841](https://linux-hardware.org/?probe=7c7b023841) | Apr 27, 2022 |
| Dell          | 00V62H A01                  | [eddac3b03f](https://linux-hardware.org/?probe=eddac3b03f) | Apr 27, 2022 |
| ASRock        | B550M Pro4                  | [003eab04ae](https://linux-hardware.org/?probe=003eab04ae) | Apr 26, 2022 |
| MSI           | MEG X570 UNIFY              | [4f7c3fc75d](https://linux-hardware.org/?probe=4f7c3fc75d) | Apr 26, 2022 |
| AZW           | U59                         | [ecee060925](https://linux-hardware.org/?probe=ecee060925) | Apr 26, 2022 |
| Gigabyte      | Z590 D                      | [afad17a56d](https://linux-hardware.org/?probe=afad17a56d) | Apr 26, 2022 |
| ASUSTek       | PRIME X570-P                | [6bee5ac8c6](https://linux-hardware.org/?probe=6bee5ac8c6) | Apr 26, 2022 |
| ASUSTek       | PRIME X570-P                | [a304ccdfb1](https://linux-hardware.org/?probe=a304ccdfb1) | Apr 26, 2022 |
| Alienware     | 02XRCM A01                  | [90cc83b1aa](https://linux-hardware.org/?probe=90cc83b1aa) | Apr 26, 2022 |
| ASRock        | H97 Pro4                    | [e937f129bf](https://linux-hardware.org/?probe=e937f129bf) | Apr 25, 2022 |
| Dell          | 042P49 A02                  | [cc2266d5aa](https://linux-hardware.org/?probe=cc2266d5aa) | Apr 25, 2022 |
| MSI           | MEG B550 UNIFY              | [3cf3319591](https://linux-hardware.org/?probe=3cf3319591) | Apr 25, 2022 |
| Dell          | 0KP561                      | [0467bf679e](https://linux-hardware.org/?probe=0467bf679e) | Apr 25, 2022 |
| ASRock        | H110 Pro BTC+               | [1251ef669d](https://linux-hardware.org/?probe=1251ef669d) | Apr 24, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | [81f1c06851](https://linux-hardware.org/?probe=81f1c06851) | Apr 23, 2022 |
| Alienware     | 07HV66 A00                  | [7b889c5010](https://linux-hardware.org/?probe=7b889c5010) | Apr 23, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [6af9cfacd0](https://linux-hardware.org/?probe=6af9cfacd0) | Apr 23, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [afcef911ce](https://linux-hardware.org/?probe=afcef911ce) | Apr 23, 2022 |
| ASRock        | AB350M Pro4                 | [544c5dbbf7](https://linux-hardware.org/?probe=544c5dbbf7) | Apr 22, 2022 |
| ASUSTek       | H81M-K                      | [95a2757020](https://linux-hardware.org/?probe=95a2757020) | Apr 22, 2022 |
| MSI           | B350M MORTAR ARCTIC         | [6c6203c7ff](https://linux-hardware.org/?probe=6c6203c7ff) | Apr 22, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [acc082b594](https://linux-hardware.org/?probe=acc082b594) | Apr 22, 2022 |
| Acer          | Predator G3610              | [a53edf84d4](https://linux-hardware.org/?probe=a53edf84d4) | Apr 22, 2022 |
| ASUSTek       | PRIME A320M-K               | [822db71f7a](https://linux-hardware.org/?probe=822db71f7a) | Apr 21, 2022 |
| Gigabyte      | B450 AORUS M                | [ff11434d18](https://linux-hardware.org/?probe=ff11434d18) | Apr 20, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [34c876e7e6](https://linux-hardware.org/?probe=34c876e7e6) | Apr 19, 2022 |
| Dell          | 0C522T A00                  | [8684c390a7](https://linux-hardware.org/?probe=8684c390a7) | Apr 19, 2022 |
| Dell          | 09M8Y8 A01                  | [8b989c82a2](https://linux-hardware.org/?probe=8b989c82a2) | Apr 18, 2022 |
| Dell          | 09M8Y8 A01                  | [fff624b795](https://linux-hardware.org/?probe=fff624b795) | Apr 18, 2022 |
| ECS           | H61H2-M13                   | [f3d574e81e](https://linux-hardware.org/?probe=f3d574e81e) | Apr 18, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [ff70aec1ae](https://linux-hardware.org/?probe=ff70aec1ae) | Apr 18, 2022 |
| Foxconn       | 2ABF                        | [ce158f41e2](https://linux-hardware.org/?probe=ce158f41e2) | Apr 17, 2022 |
| MSI           | B350M PRO-VDH               | [884f15c1df](https://linux-hardware.org/?probe=884f15c1df) | Apr 17, 2022 |
| BESSTAR Te... | UM250 V1.0                  | [271eb8380b](https://linux-hardware.org/?probe=271eb8380b) | Apr 17, 2022 |
| Lenovo        | 3714 NOK                    | [80ed454cc3](https://linux-hardware.org/?probe=80ed454cc3) | Apr 17, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [e7b66178ce](https://linux-hardware.org/?probe=e7b66178ce) | Apr 17, 2022 |
| MSI           | MAG B460M MORTAR            | [278ccbaf44](https://linux-hardware.org/?probe=278ccbaf44) | Apr 17, 2022 |
| MSI           | MS-7438 100                 | [bac261ba9a](https://linux-hardware.org/?probe=bac261ba9a) | Apr 16, 2022 |
| ASRock        | B550M Phantom Gaming 4      | [3e3e2fd22f](https://linux-hardware.org/?probe=3e3e2fd22f) | Apr 16, 2022 |
| MSI           | B450M PRO-M2 MAX            | [4702e93a67](https://linux-hardware.org/?probe=4702e93a67) | Apr 16, 2022 |
| ASUSTek       | GRYPHON Z87                 | [557390f9cf](https://linux-hardware.org/?probe=557390f9cf) | Apr 15, 2022 |
| Dell          | 0C522T A00                  | [593941cc0a](https://linux-hardware.org/?probe=593941cc0a) | Apr 15, 2022 |
| BESSTAR Te... | UM250 V1.0                  | [bd378877e0](https://linux-hardware.org/?probe=bd378877e0) | Apr 14, 2022 |
| ASRock        | B550M Pro4                  | [e1b00199f8](https://linux-hardware.org/?probe=e1b00199f8) | Apr 14, 2022 |
| ASRock        | AB350 Pro4                  | [137e25f240](https://linux-hardware.org/?probe=137e25f240) | Apr 14, 2022 |
| ASUSTek       | PRIME B360M-C               | [417d3ab696](https://linux-hardware.org/?probe=417d3ab696) | Apr 14, 2022 |
| ASUSTek       | Maximus IX HERO             | [624c5a033e](https://linux-hardware.org/?probe=624c5a033e) | Apr 14, 2022 |
| ASRock        | AB350M                      | [f79bfabcf5](https://linux-hardware.org/?probe=f79bfabcf5) | Apr 14, 2022 |
| Gigabyte      | Z97X-Gaming 3               | [5d45d7b3f7](https://linux-hardware.org/?probe=5d45d7b3f7) | Apr 13, 2022 |
| ASRock        | X570M Pro4                  | [b7373e1f8f](https://linux-hardware.org/?probe=b7373e1f8f) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | [0056c8d32e](https://linux-hardware.org/?probe=0056c8d32e) | Apr 13, 2022 |
| Dell          | 03V3TG A00                  | [a91e96515c](https://linux-hardware.org/?probe=a91e96515c) | Apr 13, 2022 |
| ASUSTek       | STRIX Z270G GAMING          | [e04e7a6bc9](https://linux-hardware.org/?probe=e04e7a6bc9) | Apr 13, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | [157197f213](https://linux-hardware.org/?probe=157197f213) | Apr 13, 2022 |
| HP            | 18E4                        | [83cf0afd92](https://linux-hardware.org/?probe=83cf0afd92) | Apr 13, 2022 |
| HP            | 18E4                        | [61a163f744](https://linux-hardware.org/?probe=61a163f744) | Apr 13, 2022 |
| Gigabyte      | B450M DS3H-CF               | [81ef10ca5d](https://linux-hardware.org/?probe=81ef10ca5d) | Apr 13, 2022 |
| Gigabyte      | 970A-DS3P                   | [8101ed4e60](https://linux-hardware.org/?probe=8101ed4e60) | Apr 12, 2022 |
| Gigabyte      | 970A-DS3P                   | [bf61a75cfd](https://linux-hardware.org/?probe=bf61a75cfd) | Apr 12, 2022 |
| Intel         | SHARKBAY                    | [f676b9a255](https://linux-hardware.org/?probe=f676b9a255) | Apr 11, 2022 |
| ASRock        | B250M Performance           | [3d9af3df5a](https://linux-hardware.org/?probe=3d9af3df5a) | Apr 11, 2022 |
| MSI           | 760GM-P34                   | [c346a58754](https://linux-hardware.org/?probe=c346a58754) | Apr 11, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [1a475ba1e6](https://linux-hardware.org/?probe=1a475ba1e6) | Apr 11, 2022 |
| HP            | 1998                        | [28dcd611cc](https://linux-hardware.org/?probe=28dcd611cc) | Apr 10, 2022 |
| MSI           | Z370 PC PRO                 | [2d4574e9fe](https://linux-hardware.org/?probe=2d4574e9fe) | Apr 10, 2022 |
| Gigabyte      | H61M-S2PV                   | [8760e3254a](https://linux-hardware.org/?probe=8760e3254a) | Apr 10, 2022 |
| ASUSTek       | Z87-K                       | [b0ffa911b5](https://linux-hardware.org/?probe=b0ffa911b5) | Apr 10, 2022 |
| ASUSTek       | PRIME H410M-E               | [885cbd9d0c](https://linux-hardware.org/?probe=885cbd9d0c) | Apr 10, 2022 |
| ASUSTek       | P8Z77-V DELUXE              | [e890c4c2f7](https://linux-hardware.org/?probe=e890c4c2f7) | Apr 10, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [645fb7bb30](https://linux-hardware.org/?probe=645fb7bb30) | Apr 09, 2022 |
| ASUSTek       | Z87-K                       | [5264d55ce2](https://linux-hardware.org/?probe=5264d55ce2) | Apr 09, 2022 |
| ASRock        | Z77 Pro4                    | [38eeb648af](https://linux-hardware.org/?probe=38eeb648af) | Apr 09, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [a618981311](https://linux-hardware.org/?probe=a618981311) | Apr 09, 2022 |
| MSI           | X370 XPOWER GAMING TITAN... | [2db23c062e](https://linux-hardware.org/?probe=2db23c062e) | Apr 08, 2022 |
| ASUSTek       | P8Z77-V LX                  | [94f4873110](https://linux-hardware.org/?probe=94f4873110) | Apr 06, 2022 |
| MSI           | Z370-A PRO                  | [c4f0f0573c](https://linux-hardware.org/?probe=c4f0f0573c) | Apr 06, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [091190515b](https://linux-hardware.org/?probe=091190515b) | Apr 06, 2022 |
| Dell          | 0D24M8 A00                  | [4f81a4a54a](https://linux-hardware.org/?probe=4f81a4a54a) | Apr 06, 2022 |
| ASUSTek       | A8N-VM CSM                  | [eac824e348](https://linux-hardware.org/?probe=eac824e348) | Apr 06, 2022 |
| Biostar       | TB250-BTC                   | [d6ef15453d](https://linux-hardware.org/?probe=d6ef15453d) | Apr 05, 2022 |
| ASUSTek       | Z97-A-USB31                 | [cd6f73403e](https://linux-hardware.org/?probe=cd6f73403e) | Apr 05, 2022 |
| ASRock        | B450 Pro4                   | [47ff657a18](https://linux-hardware.org/?probe=47ff657a18) | Apr 04, 2022 |
| Dell          | 0C522T A00                  | [4a42777634](https://linux-hardware.org/?probe=4a42777634) | Apr 04, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [5348103896](https://linux-hardware.org/?probe=5348103896) | Apr 03, 2022 |
| Intel         | DH67BL AAG10189-207         | [2daa6a85f4](https://linux-hardware.org/?probe=2daa6a85f4) | Apr 03, 2022 |
| MSI           | X470 GAMING PLUS            | [b7cf273d03](https://linux-hardware.org/?probe=b7cf273d03) | Apr 03, 2022 |
| ASRock        | 960GM-GS3 FX                | [cf80b64dad](https://linux-hardware.org/?probe=cf80b64dad) | Apr 02, 2022 |
| ASRock        | 960GM-GS3 FX                | [50c200ee58](https://linux-hardware.org/?probe=50c200ee58) | Apr 02, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [a11d93b9d5](https://linux-hardware.org/?probe=a11d93b9d5) | Apr 02, 2022 |
| Acer          | Aspire TC-120               | [a92d7ab62a](https://linux-hardware.org/?probe=a92d7ab62a) | Apr 02, 2022 |
| ASUSTek       | Z97-A-USB31                 | [6f40a4ebce](https://linux-hardware.org/?probe=6f40a4ebce) | Apr 02, 2022 |
| Dell          | 0N867P A02                  | [aaf4c4cf2b](https://linux-hardware.org/?probe=aaf4c4cf2b) | Apr 01, 2022 |
| ASRock        | Z390 Taichi                 | [b5995c13e5](https://linux-hardware.org/?probe=b5995c13e5) | Mar 31, 2022 |
| ASRock        | Z390 Taichi                 | [308ec93236](https://linux-hardware.org/?probe=308ec93236) | Mar 31, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [101c38851b](https://linux-hardware.org/?probe=101c38851b) | Mar 31, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [5f25594023](https://linux-hardware.org/?probe=5f25594023) | Mar 31, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [42e098223b](https://linux-hardware.org/?probe=42e098223b) | Mar 30, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [0deba367b9](https://linux-hardware.org/?probe=0deba367b9) | Mar 30, 2022 |
| ASRock        | Z77 Extreme4                | [4ab227f4be](https://linux-hardware.org/?probe=4ab227f4be) | Mar 29, 2022 |
| Gigabyte      | Z87MX-D3H-CF                | [0401591ebc](https://linux-hardware.org/?probe=0401591ebc) | Mar 29, 2022 |
| HP            | 1998                        | [13b901f36a](https://linux-hardware.org/?probe=13b901f36a) | Mar 29, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | [a10bdc00e2](https://linux-hardware.org/?probe=a10bdc00e2) | Mar 28, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [0bcee9c78e](https://linux-hardware.org/?probe=0bcee9c78e) | Mar 28, 2022 |
| MSI           | H81M-E34                    | [42ff46ca6c](https://linux-hardware.org/?probe=42ff46ca6c) | Mar 28, 2022 |
| Gigabyte      | M68MT-D3P                   | [8d596570ed](https://linux-hardware.org/?probe=8d596570ed) | Mar 28, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [3ed10cce06](https://linux-hardware.org/?probe=3ed10cce06) | Mar 27, 2022 |
| ASRock        | B550M Pro4                  | [4c69702c19](https://linux-hardware.org/?probe=4c69702c19) | Mar 27, 2022 |
| AMD           | 970A-D3                     | [010b978f01](https://linux-hardware.org/?probe=010b978f01) | Mar 26, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [22e95f050f](https://linux-hardware.org/?probe=22e95f050f) | Mar 26, 2022 |
| ASUSTek       | P8H61-M LE/BR               | [732876bdd8](https://linux-hardware.org/?probe=732876bdd8) | Mar 26, 2022 |
| Alienware     | 0R3FWM A00                  | [46a5c111c3](https://linux-hardware.org/?probe=46a5c111c3) | Mar 25, 2022 |
| Gigabyte      | 990XA-UD3                   | [913cf55cc3](https://linux-hardware.org/?probe=913cf55cc3) | Mar 25, 2022 |
| ASUSTek       | PRIME Z370-P                | [f3cd1a314c](https://linux-hardware.org/?probe=f3cd1a314c) | Mar 25, 2022 |
| Gigabyte      | X58A-UD3R                   | [40ec2200ee](https://linux-hardware.org/?probe=40ec2200ee) | Mar 25, 2022 |
| Gigabyte      | X58A-UD3R                   | [cb639d5f0a](https://linux-hardware.org/?probe=cb639d5f0a) | Mar 25, 2022 |
| Acer          | Veriton M6660G V:1.0        | [ee5d755daf](https://linux-hardware.org/?probe=ee5d755daf) | Mar 24, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [994cca77b2](https://linux-hardware.org/?probe=994cca77b2) | Mar 24, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [fe7be471b2](https://linux-hardware.org/?probe=fe7be471b2) | Mar 24, 2022 |
| ASRock        | B550 Taichi                 | [2c71d397fd](https://linux-hardware.org/?probe=2c71d397fd) | Mar 24, 2022 |
| Unknown       | Unknown                     | [52ce856be5](https://linux-hardware.org/?probe=52ce856be5) | Mar 24, 2022 |
| Unknown       | Unknown                     | [1dd07eeee0](https://linux-hardware.org/?probe=1dd07eeee0) | Mar 24, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [bb1d6b4aae](https://linux-hardware.org/?probe=bb1d6b4aae) | Mar 24, 2022 |
| Intel         | Unknown                     | [169b017d29](https://linux-hardware.org/?probe=169b017d29) | Mar 23, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [c5a0300da9](https://linux-hardware.org/?probe=c5a0300da9) | Mar 23, 2022 |
| ASUSTek       | B150I PRO GAMING/AURA       | [0839d5feb0](https://linux-hardware.org/?probe=0839d5feb0) | Mar 22, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [d24fcefe24](https://linux-hardware.org/?probe=d24fcefe24) | Mar 22, 2022 |
| Acer          | Veriton M6660G V:1.0        | [228974c486](https://linux-hardware.org/?probe=228974c486) | Mar 22, 2022 |
| Dell          | 0K3CM7 A00                  | [8f5ec6c004](https://linux-hardware.org/?probe=8f5ec6c004) | Mar 22, 2022 |
| Apple         | Mac-27AD2F918AE68F61        | [03e06a3a70](https://linux-hardware.org/?probe=03e06a3a70) | Mar 22, 2022 |
| Gigabyte      | G31M-ES2L                   | [90a8431fc2](https://linux-hardware.org/?probe=90a8431fc2) | Mar 22, 2022 |
| Gigabyte      | A320M-H-CF                  | [1462cd20b7](https://linux-hardware.org/?probe=1462cd20b7) | Mar 22, 2022 |
| MSI           | B450M PRO-VDH MAX           | [a6718f483b](https://linux-hardware.org/?probe=a6718f483b) | Mar 22, 2022 |
| Gigabyte      | B560M AORUS PRO AX          | [b7f10d6ec0](https://linux-hardware.org/?probe=b7f10d6ec0) | Mar 21, 2022 |
| MSI           | B450M BAZOOKA MAX WIFI      | [747e4d92cf](https://linux-hardware.org/?probe=747e4d92cf) | Mar 21, 2022 |
| ASRock        | B550 Extreme4               | [9c194b83e5](https://linux-hardware.org/?probe=9c194b83e5) | Mar 21, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [daa5dd8024](https://linux-hardware.org/?probe=daa5dd8024) | Mar 20, 2022 |
| ASUSTek       | H170 PRO GAMING             | [8ce1eed900](https://linux-hardware.org/?probe=8ce1eed900) | Mar 20, 2022 |
| ASUSTek       | TUF B360M-PLUS GAMING S     | [1897912bfc](https://linux-hardware.org/?probe=1897912bfc) | Mar 19, 2022 |
| TPV-INVENT... | 2AF2 A01                    | [1ab476e992](https://linux-hardware.org/?probe=1ab476e992) | Mar 18, 2022 |
| Dell          | 040DDP A01                  | [4cf633a014](https://linux-hardware.org/?probe=4cf633a014) | Mar 18, 2022 |
| ASUSTek       | ROG Maximus X HERO          | [d2378fc2ac](https://linux-hardware.org/?probe=d2378fc2ac) | Mar 18, 2022 |
| Gigabyte      | GA-MA74GM-S2                | [af8d9c8c06](https://linux-hardware.org/?probe=af8d9c8c06) | Mar 18, 2022 |
| ASUSTek       | PRIME B460M-A               | [bb8e459621](https://linux-hardware.org/?probe=bb8e459621) | Mar 17, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [9ebb2a429f](https://linux-hardware.org/?probe=9ebb2a429f) | Mar 17, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [b844e23ce9](https://linux-hardware.org/?probe=b844e23ce9) | Mar 17, 2022 |
| Gigabyte      | B560M AORUS PRO AX          | [04e11e3668](https://linux-hardware.org/?probe=04e11e3668) | Mar 16, 2022 |
| MSI           | B75MA-P45                   | [f617b8e30b](https://linux-hardware.org/?probe=f617b8e30b) | Mar 16, 2022 |
| System76      | Thelio thelio-r2            | [ac96c74ffa](https://linux-hardware.org/?probe=ac96c74ffa) | Mar 16, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [ca405b99d5](https://linux-hardware.org/?probe=ca405b99d5) | Mar 16, 2022 |
| MSI           | MEG X570 UNIFY              | [0927f69114](https://linux-hardware.org/?probe=0927f69114) | Mar 15, 2022 |
| MSI           | B450M PRO-VDH PLUS          | [1b6764fd97](https://linux-hardware.org/?probe=1b6764fd97) | Mar 15, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [a4cc8c4dda](https://linux-hardware.org/?probe=a4cc8c4dda) | Mar 15, 2022 |
| MSI           | MEG X570 UNIFY              | [a4dd59149a](https://linux-hardware.org/?probe=a4dd59149a) | Mar 15, 2022 |
| ASUSTek       | PRIME H410M-R               | [4bc060dc9d](https://linux-hardware.org/?probe=4bc060dc9d) | Mar 14, 2022 |
| ASUSTek       | PRIME Z490M-PLUS            | [e0efdaa76a](https://linux-hardware.org/?probe=e0efdaa76a) | Mar 13, 2022 |
| Gigabyte      | H310M H x.x                 | [0a16c273a4](https://linux-hardware.org/?probe=0a16c273a4) | Mar 13, 2022 |
| ASRock        | H61 Pro BTC                 | [43528c8a20](https://linux-hardware.org/?probe=43528c8a20) | Mar 13, 2022 |
| Gigabyte      | B450M DS3H-CF               | [75561646a7](https://linux-hardware.org/?probe=75561646a7) | Mar 13, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [693ec12319](https://linux-hardware.org/?probe=693ec12319) | Mar 12, 2022 |
| MSI           | H81M-P33                    | [138594b67f](https://linux-hardware.org/?probe=138594b67f) | Mar 12, 2022 |
| Lenovo        | 3704 SDK0J40700 WIN 3258... | [e6c507dff4](https://linux-hardware.org/?probe=e6c507dff4) | Mar 12, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [e8c3922bb3](https://linux-hardware.org/?probe=e8c3922bb3) | Mar 12, 2022 |
| MSI           | H81M-E34                    | [8d5b326668](https://linux-hardware.org/?probe=8d5b326668) | Mar 12, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [bd9b6ec157](https://linux-hardware.org/?probe=bd9b6ec157) | Mar 11, 2022 |
| HP            | 1850                        | [7e0b4230d4](https://linux-hardware.org/?probe=7e0b4230d4) | Mar 11, 2022 |
| Gigabyte      | B75M-D3H                    | [30df05cc2f](https://linux-hardware.org/?probe=30df05cc2f) | Mar 11, 2022 |
| HP            | 3396                        | [7bd27c71ed](https://linux-hardware.org/?probe=7bd27c71ed) | Mar 11, 2022 |
| HP            | 3396                        | [adeef3162a](https://linux-hardware.org/?probe=adeef3162a) | Mar 11, 2022 |
| Gigabyte      | H61M-S2PV                   | [6b32e0c788](https://linux-hardware.org/?probe=6b32e0c788) | Mar 10, 2022 |
| ASRock        | H81M-VG4 R2.0               | [2d72940994](https://linux-hardware.org/?probe=2d72940994) | Mar 10, 2022 |
| Gigabyte      | X570 GAMING X               | [4f7aa0f57c](https://linux-hardware.org/?probe=4f7aa0f57c) | Mar 10, 2022 |
| HP            | 1497                        | [f67b96c14e](https://linux-hardware.org/?probe=f67b96c14e) | Mar 07, 2022 |
| ASRock        | H97 Pro4                    | [83df7fb05a](https://linux-hardware.org/?probe=83df7fb05a) | Mar 07, 2022 |
| Gigabyte      | Z68P-DS3                    | [0bb1088899](https://linux-hardware.org/?probe=0bb1088899) | Mar 06, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [783c8d9097](https://linux-hardware.org/?probe=783c8d9097) | Mar 06, 2022 |
| Fujitsu       | D3400-A1 S26361-D3400-A1    | [68250a6d74](https://linux-hardware.org/?probe=68250a6d74) | Mar 06, 2022 |
| Dell          | 0YXT71 A03                  | [b1ac4ae8e7](https://linux-hardware.org/?probe=b1ac4ae8e7) | Mar 05, 2022 |
| MSI           | X99A SLI PLUS               | [b56033aa1d](https://linux-hardware.org/?probe=b56033aa1d) | Mar 05, 2022 |
| Gigabyte      | 2AC8                        | [af655fd169](https://linux-hardware.org/?probe=af655fd169) | Mar 04, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [8e27cc62b4](https://linux-hardware.org/?probe=8e27cc62b4) | Mar 04, 2022 |
| ASRock        | AB350M Pro4                 | [6ea2fbdb95](https://linux-hardware.org/?probe=6ea2fbdb95) | Mar 03, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [ee8029d2c8](https://linux-hardware.org/?probe=ee8029d2c8) | Mar 03, 2022 |
| MSI           | Z170A KRAIT GAMING 3X       | [cff135fa1e](https://linux-hardware.org/?probe=cff135fa1e) | Mar 03, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [eb3d721453](https://linux-hardware.org/?probe=eb3d721453) | Mar 02, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [5f0757c539](https://linux-hardware.org/?probe=5f0757c539) | Mar 02, 2022 |
| ASRock        | Z77 Pro4                    | [ae5611419f](https://linux-hardware.org/?probe=ae5611419f) | Mar 02, 2022 |
| ASRock        | X370 Killer SLI/ac          | [07f8fcde55](https://linux-hardware.org/?probe=07f8fcde55) | Mar 02, 2022 |
| HP            | 18E4                        | [192b302f41](https://linux-hardware.org/?probe=192b302f41) | Feb 27, 2022 |
| ASRock        | H61M-ITX                    | [081ea4e585](https://linux-hardware.org/?probe=081ea4e585) | Feb 26, 2022 |
| AIO           | H61H-G11                    | [137ec871e7](https://linux-hardware.org/?probe=137ec871e7) | Feb 25, 2022 |
| ASUSTek       | PRIME B450M-K               | [6f1958559b](https://linux-hardware.org/?probe=6f1958559b) | Feb 24, 2022 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | [b6891f77df](https://linux-hardware.org/?probe=b6891f77df) | Feb 24, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [f2a6491fc3](https://linux-hardware.org/?probe=f2a6491fc3) | Feb 24, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [1c8a37fb2f](https://linux-hardware.org/?probe=1c8a37fb2f) | Feb 24, 2022 |
| HP            | 21D0                        | [448912eeb9](https://linux-hardware.org/?probe=448912eeb9) | Feb 24, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [1c6d204561](https://linux-hardware.org/?probe=1c6d204561) | Feb 24, 2022 |
| Dell          | 00V62H A01                  | [e6564282e5](https://linux-hardware.org/?probe=e6564282e5) | Feb 23, 2022 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [2f53cef399](https://linux-hardware.org/?probe=2f53cef399) | Feb 23, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [6d2bec51f3](https://linux-hardware.org/?probe=6d2bec51f3) | Feb 23, 2022 |
| ASUSTek       | Pro WS C621-64L SAGE Ser... | [17aa7b3d5b](https://linux-hardware.org/?probe=17aa7b3d5b) | Feb 23, 2022 |
| Gigabyte      | B460M DS3H                  | [c2ed3df75c](https://linux-hardware.org/?probe=c2ed3df75c) | Feb 23, 2022 |
| MSI           | 880G-E45                    | [e6f9c8c9f6](https://linux-hardware.org/?probe=e6f9c8c9f6) | Feb 23, 2022 |
| Gigabyte      | B250M-DS3H-CF               | [db907dad62](https://linux-hardware.org/?probe=db907dad62) | Feb 21, 2022 |
| Gigabyte      | 2AC8                        | [90d30ccc29](https://linux-hardware.org/?probe=90d30ccc29) | Feb 21, 2022 |
| Gigabyte      | H61M-DS2 DVI                | [03491eae09](https://linux-hardware.org/?probe=03491eae09) | Feb 21, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | [e1943c32e9](https://linux-hardware.org/?probe=e1943c32e9) | Feb 20, 2022 |
| HP            | 1998                        | [1cd99a92d0](https://linux-hardware.org/?probe=1cd99a92d0) | Feb 20, 2022 |
| Biostar       | TB250-BTC                   | [90154b9001](https://linux-hardware.org/?probe=90154b9001) | Feb 20, 2022 |
| Biostar       | TB250-BTC                   | [b42d2ce48e](https://linux-hardware.org/?probe=b42d2ce48e) | Feb 20, 2022 |
| ASRock        | H370M-ITX/ac                | [95b177e121](https://linux-hardware.org/?probe=95b177e121) | Feb 19, 2022 |
| Gigabyte      | C246-WU4-CF                 | [e849c7b27b](https://linux-hardware.org/?probe=e849c7b27b) | Feb 19, 2022 |
| Gigabyte      | Z490I AORUS ULTRA           | [7ecf132718](https://linux-hardware.org/?probe=7ecf132718) | Feb 19, 2022 |
| Dell          | 0CRH6C A02                  | [726633bbcc](https://linux-hardware.org/?probe=726633bbcc) | Feb 18, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [d08ed1959b](https://linux-hardware.org/?probe=d08ed1959b) | Feb 18, 2022 |
| HP            | 1497                        | [8693cfc8c8](https://linux-hardware.org/?probe=8693cfc8c8) | Feb 17, 2022 |
| ASRock        | Z370 Extreme4               | [304e498f77](https://linux-hardware.org/?probe=304e498f77) | Feb 17, 2022 |
| HP            | 2820h                       | [f45476e17a](https://linux-hardware.org/?probe=f45476e17a) | Feb 17, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [3dc3e4c8c8](https://linux-hardware.org/?probe=3dc3e4c8c8) | Feb 17, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [2dece71caa](https://linux-hardware.org/?probe=2dece71caa) | Feb 17, 2022 |
| HP            | 0AA8h                       | [cb11b8e6fb](https://linux-hardware.org/?probe=cb11b8e6fb) | Feb 16, 2022 |
| ASUSTek       | Pro WS C621-64L SAGE Ser... | [922f3559c8](https://linux-hardware.org/?probe=922f3559c8) | Feb 16, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [913928e6e9](https://linux-hardware.org/?probe=913928e6e9) | Feb 16, 2022 |
| ASUSTek       | M5A97 EVO                   | [c80545d294](https://linux-hardware.org/?probe=c80545d294) | Feb 16, 2022 |
| ASUSTek       | M5A97 EVO                   | [98e8879090](https://linux-hardware.org/?probe=98e8879090) | Feb 16, 2022 |
| MSI           | B150M PRO-VD                | [b46943492e](https://linux-hardware.org/?probe=b46943492e) | Feb 15, 2022 |
| Gigabyte      | A520M H                     | [6f8f7c786e](https://linux-hardware.org/?probe=6f8f7c786e) | Feb 14, 2022 |
| Gigabyte      | A520M H                     | [b4c976a541](https://linux-hardware.org/?probe=b4c976a541) | Feb 14, 2022 |
| ASUSTek       | P5QL/EPU                    | [2a5bcaeec9](https://linux-hardware.org/?probe=2a5bcaeec9) | Feb 14, 2022 |
| ASRock        | B450M Pro4                  | [3bbcbc62f5](https://linux-hardware.org/?probe=3bbcbc62f5) | Feb 13, 2022 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | [cc35d4696d](https://linux-hardware.org/?probe=cc35d4696d) | Feb 13, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [a25fea3795](https://linux-hardware.org/?probe=a25fea3795) | Feb 12, 2022 |
| HP            | 8618                        | [6976caf9ed](https://linux-hardware.org/?probe=6976caf9ed) | Feb 12, 2022 |
| HP            | 8618                        | [1038885608](https://linux-hardware.org/?probe=1038885608) | Feb 12, 2022 |
| MSI           | MPG B550 GAMING CARBON W... | [73767731d9](https://linux-hardware.org/?probe=73767731d9) | Feb 11, 2022 |
| Intel         | DH67GD AAG10206-202         | [56c802164a](https://linux-hardware.org/?probe=56c802164a) | Feb 11, 2022 |
| Gigabyte      | B250M-DS3H-CF               | [040550cdaa](https://linux-hardware.org/?probe=040550cdaa) | Feb 11, 2022 |
| ASUSTek       | Maximus Formula             | [130c778a64](https://linux-hardware.org/?probe=130c778a64) | Feb 11, 2022 |
| Acer          | Predator PO3-630            | [96dccc1214](https://linux-hardware.org/?probe=96dccc1214) | Feb 11, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [afc31097cd](https://linux-hardware.org/?probe=afc31097cd) | Feb 09, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [a752207fe2](https://linux-hardware.org/?probe=a752207fe2) | Feb 09, 2022 |
| ASRock        | FM2A68M-HD+                 | [8545c3246e](https://linux-hardware.org/?probe=8545c3246e) | Feb 08, 2022 |
| Dell          | 00V62H A00                  | [7135f3c638](https://linux-hardware.org/?probe=7135f3c638) | Feb 07, 2022 |
| Dell          | 00V62H A00                  | [d6aefe2df6](https://linux-hardware.org/?probe=d6aefe2df6) | Feb 07, 2022 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [9dd525ae45](https://linux-hardware.org/?probe=9dd525ae45) | Feb 07, 2022 |
| ASUSTek       | PRIME H510M-A               | [b2bc043c0b](https://linux-hardware.org/?probe=b2bc043c0b) | Feb 07, 2022 |
| HP            | 2820h                       | [347b6a83de](https://linux-hardware.org/?probe=347b6a83de) | Feb 07, 2022 |
| HP            | 2820h                       | [7c5fb9c18f](https://linux-hardware.org/?probe=7c5fb9c18f) | Feb 07, 2022 |
| ASRock        | B450M Pro4                  | [9efa6de9c0](https://linux-hardware.org/?probe=9efa6de9c0) | Feb 07, 2022 |
| ASRock        | H510M-HDV/M.2               | [11b7d331bc](https://linux-hardware.org/?probe=11b7d331bc) | Feb 06, 2022 |
| Intel         | H61 V124                    | [258b472104](https://linux-hardware.org/?probe=258b472104) | Feb 06, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [497f20602c](https://linux-hardware.org/?probe=497f20602c) | Feb 05, 2022 |
| Acer          | Predator PO3-630            | [7d12bf5399](https://linux-hardware.org/?probe=7d12bf5399) | Feb 05, 2022 |
| MSI           | Z270I GAMING PRO CARBON ... | [424f798e37](https://linux-hardware.org/?probe=424f798e37) | Feb 05, 2022 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | [4c27e1f600](https://linux-hardware.org/?probe=4c27e1f600) | Feb 05, 2022 |
| Gigabyte      | B560M AORUS PRO AX          | [055aea6734](https://linux-hardware.org/?probe=055aea6734) | Feb 05, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [035ccaeec8](https://linux-hardware.org/?probe=035ccaeec8) | Feb 04, 2022 |
| MSI           | MEG X570 UNIFY              | [5e8f4aba70](https://linux-hardware.org/?probe=5e8f4aba70) | Feb 03, 2022 |
| Dell          | 0XR1GT A00                  | [436259c69f](https://linux-hardware.org/?probe=436259c69f) | Feb 03, 2022 |
| Gigabyte      | F2A55M-DS2                  | [05d8bff376](https://linux-hardware.org/?probe=05d8bff376) | Feb 02, 2022 |
| ASUSTek       | PRIME Z390-A                | [8086fa496d](https://linux-hardware.org/?probe=8086fa496d) | Feb 02, 2022 |
| ASRock        | B450 Pro4                   | [01eb76fa65](https://linux-hardware.org/?probe=01eb76fa65) | Feb 01, 2022 |
| Dell          | 0HD5W2 A01                  | [9d172808c8](https://linux-hardware.org/?probe=9d172808c8) | Feb 01, 2022 |
| Intel         | X99 V1.0                    | [c342bd0bba](https://linux-hardware.org/?probe=c342bd0bba) | Jan 30, 2022 |
| Huanan        | X99-TF GAMING V2.0          | [aa1fb1fa56](https://linux-hardware.org/?probe=aa1fb1fa56) | Jan 29, 2022 |
| ASUSTek       | PRIME B450M-A               | [1ce7d1b347](https://linux-hardware.org/?probe=1ce7d1b347) | Jan 29, 2022 |
| ASUSTek       | P5QL/EPU                    | [c1e858090a](https://linux-hardware.org/?probe=c1e858090a) | Jan 28, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [bfc2cf603f](https://linux-hardware.org/?probe=bfc2cf603f) | Jan 27, 2022 |
| ASUSTek       | TUF Gaming A520M-PLUS II    | [ad887e6da9](https://linux-hardware.org/?probe=ad887e6da9) | Jan 27, 2022 |
| Dell          | 06D7TR A00                  | [1fdcf46e3b](https://linux-hardware.org/?probe=1fdcf46e3b) | Jan 26, 2022 |
| GALAX         | B365M G10b                  | [bd83b31919](https://linux-hardware.org/?probe=bd83b31919) | Jan 26, 2022 |
| Gigabyte      | 2AC8                        | [1480b4a02f](https://linux-hardware.org/?probe=1480b4a02f) | Jan 25, 2022 |
| Gigabyte      | 970A-DS3P                   | [d0dde4a553](https://linux-hardware.org/?probe=d0dde4a553) | Jan 24, 2022 |
| Gigabyte      | 965P-S3                     | [9e4aca104e](https://linux-hardware.org/?probe=9e4aca104e) | Jan 24, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | [f48fe5a028](https://linux-hardware.org/?probe=f48fe5a028) | Jan 24, 2022 |
| MSI           | Z170A PC MATE               | [dd98b6fbca](https://linux-hardware.org/?probe=dd98b6fbca) | Jan 23, 2022 |
| ASRock        | H510M-ITX/ac                | [606c183545](https://linux-hardware.org/?probe=606c183545) | Jan 23, 2022 |
| ASUSTek       | TUF Gaming A520M-PLUS II    | [f950d7e322](https://linux-hardware.org/?probe=f950d7e322) | Jan 23, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [1c15058d91](https://linux-hardware.org/?probe=1c15058d91) | Jan 22, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [6d6c1565b7](https://linux-hardware.org/?probe=6d6c1565b7) | Jan 21, 2022 |
| Lenovo        | 313C SDK0J40697 WIN 3305... | [6cad862612](https://linux-hardware.org/?probe=6cad862612) | Jan 21, 2022 |
| Gigabyte      | Z590 VISION D               | [1d8fa44afd](https://linux-hardware.org/?probe=1d8fa44afd) | Jan 20, 2022 |
| Medion        | H110H4-EM                   | [64a2a3257d](https://linux-hardware.org/?probe=64a2a3257d) | Jan 20, 2022 |
| Dell          | 0YXT71 A03                  | [3609f04919](https://linux-hardware.org/?probe=3609f04919) | Jan 19, 2022 |
| Medion        | H110H4-EM                   | [6eab6bd21a](https://linux-hardware.org/?probe=6eab6bd21a) | Jan 19, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [993543545b](https://linux-hardware.org/?probe=993543545b) | Jan 18, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [ce0d7ad7f6](https://linux-hardware.org/?probe=ce0d7ad7f6) | Jan 18, 2022 |
| ASUSTek       | Z170 PRO GAMING             | [a7cc00f1bb](https://linux-hardware.org/?probe=a7cc00f1bb) | Jan 18, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [7e0c6ebfc9](https://linux-hardware.org/?probe=7e0c6ebfc9) | Jan 18, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [d531de56b2](https://linux-hardware.org/?probe=d531de56b2) | Jan 18, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [5cccda3e40](https://linux-hardware.org/?probe=5cccda3e40) | Jan 18, 2022 |
| Dell          | 0R230R A00                  | [484bd19da3](https://linux-hardware.org/?probe=484bd19da3) | Jan 18, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [2f8e734236](https://linux-hardware.org/?probe=2f8e734236) | Jan 17, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [42d55a089f](https://linux-hardware.org/?probe=42d55a089f) | Jan 16, 2022 |
| Dell          | 0R230R A00                  | [9b7d66cb9d](https://linux-hardware.org/?probe=9b7d66cb9d) | Jan 16, 2022 |
| MSI           | B350M MORTAR                | [5f93713b6d](https://linux-hardware.org/?probe=5f93713b6d) | Jan 16, 2022 |
| Dell          | 01XK1W A00                  | [eafa397038](https://linux-hardware.org/?probe=eafa397038) | Jan 14, 2022 |
| Acer          | Aspire XC-230               | [ba7ea12461](https://linux-hardware.org/?probe=ba7ea12461) | Jan 14, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [8ec42ce5c6](https://linux-hardware.org/?probe=8ec42ce5c6) | Jan 14, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [d0ebb55aa3](https://linux-hardware.org/?probe=d0ebb55aa3) | Jan 12, 2022 |
| MSI           | X99S GAMING 7               | [66556a15be](https://linux-hardware.org/?probe=66556a15be) | Jan 11, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [4debe87ebd](https://linux-hardware.org/?probe=4debe87ebd) | Jan 11, 2022 |
| Intel         | D2550MUD2 AAG73892-600      | [7a18fc5ecf](https://linux-hardware.org/?probe=7a18fc5ecf) | Jan 11, 2022 |
| Gigabyte      | B450M DS3H V2               | [c4d0e193e1](https://linux-hardware.org/?probe=c4d0e193e1) | Jan 11, 2022 |
| Gigabyte      | B450M DS3H-CF               | [8c319cd6fc](https://linux-hardware.org/?probe=8c319cd6fc) | Jan 11, 2022 |
| Dell          | 0KP561                      | [91846f4dc8](https://linux-hardware.org/?probe=91846f4dc8) | Jan 10, 2022 |
| ASRock        | H81M-VG4                    | [8678202106](https://linux-hardware.org/?probe=8678202106) | Jan 10, 2022 |
| ASUSTek       | P5WDG2 WS PRO               | [c22b31be4e](https://linux-hardware.org/?probe=c22b31be4e) | Jan 10, 2022 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | [936bd6bf44](https://linux-hardware.org/?probe=936bd6bf44) | Jan 10, 2022 |
| Chatreey      | AC1-DP                      | [fb4af3e7ac](https://linux-hardware.org/?probe=fb4af3e7ac) | Jan 09, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [c8e28c5df0](https://linux-hardware.org/?probe=c8e28c5df0) | Jan 09, 2022 |
| MSI           | B450M BAZOOKA MAX WIFI      | [6cb48fa647](https://linux-hardware.org/?probe=6cb48fa647) | Jan 08, 2022 |
| MSI           | B550-A PRO                  | [14e41b405a](https://linux-hardware.org/?probe=14e41b405a) | Jan 08, 2022 |
| Gigabyte      | H61M-S1                     | [50adc5f773](https://linux-hardware.org/?probe=50adc5f773) | Jan 08, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [b5fbd6f1c9](https://linux-hardware.org/?probe=b5fbd6f1c9) | Jan 08, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [4c8aea2ca5](https://linux-hardware.org/?probe=4c8aea2ca5) | Jan 08, 2022 |
| Gigabyte      | P55A-UD3                    | [46878503d2](https://linux-hardware.org/?probe=46878503d2) | Jan 07, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [5b879a9c87](https://linux-hardware.org/?probe=5b879a9c87) | Jan 07, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | [8a1611ac33](https://linux-hardware.org/?probe=8a1611ac33) | Jan 06, 2022 |
| MSI           | B85M-E33 V2                 | [ef65c0c144](https://linux-hardware.org/?probe=ef65c0c144) | Jan 05, 2022 |
| ASRock        | Z77 Pro4                    | [d83cbe9961](https://linux-hardware.org/?probe=d83cbe9961) | Jan 05, 2022 |
| ASUSTek       | Maximus IV GENE-Z/GEN3      | [a1e2cab707](https://linux-hardware.org/?probe=a1e2cab707) | Jan 05, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [f5f5eadcd4](https://linux-hardware.org/?probe=f5f5eadcd4) | Jan 04, 2022 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [608b8edfd4](https://linux-hardware.org/?probe=608b8edfd4) | Jan 03, 2022 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [157c5615eb](https://linux-hardware.org/?probe=157c5615eb) | Jan 03, 2022 |
| Dell          | 08HPGT A01                  | [ce034fa823](https://linux-hardware.org/?probe=ce034fa823) | Jan 03, 2022 |
| Gigabyte      | 970A-DS3P                   | [5209cf627a](https://linux-hardware.org/?probe=5209cf627a) | Jan 02, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [ec461a0a66](https://linux-hardware.org/?probe=ec461a0a66) | Jan 02, 2022 |
| MSI           | MPG Z690 FORCE WIFI         | [8317742b36](https://linux-hardware.org/?probe=8317742b36) | Jan 01, 2022 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [255ef3cc1a](https://linux-hardware.org/?probe=255ef3cc1a) | Jan 01, 2022 |
| ASUSTek       | M51BC                       | [bdf0263352](https://linux-hardware.org/?probe=bdf0263352) | Dec 31, 2021 |
| MSI           | MAG B550 TORPEDO            | [b674024789](https://linux-hardware.org/?probe=b674024789) | Dec 30, 2021 |
| Dell          | 01XK1W A00                  | [5407438c6e](https://linux-hardware.org/?probe=5407438c6e) | Dec 30, 2021 |
| Dell          | 01XK1W A00                  | [0b80d9da29](https://linux-hardware.org/?probe=0b80d9da29) | Dec 30, 2021 |
| ASUSTek       | Rampage Formula             | [5c4181f9b7](https://linux-hardware.org/?probe=5c4181f9b7) | Dec 29, 2021 |
| MSI           | B150M PRO-VDH               | [6af03f4abc](https://linux-hardware.org/?probe=6af03f4abc) | Dec 28, 2021 |
| Gigabyte      | B560M AORUS PRO AX          | [becfdd4806](https://linux-hardware.org/?probe=becfdd4806) | Dec 28, 2021 |
| ASRock        | B550M-ITX/ac                | [ea1a58e848](https://linux-hardware.org/?probe=ea1a58e848) | Dec 26, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [b482ef13ea](https://linux-hardware.org/?probe=b482ef13ea) | Dec 26, 2021 |
| MSI           | B450 GAMING PLUS MAX        | [9257b6fa8f](https://linux-hardware.org/?probe=9257b6fa8f) | Dec 26, 2021 |
| HP            | 1998                        | [fffadbe1cf](https://linux-hardware.org/?probe=fffadbe1cf) | Dec 25, 2021 |
| Acer          | Aspire XC-885 V:1.1         | [c7fcfb6f2a](https://linux-hardware.org/?probe=c7fcfb6f2a) | Dec 25, 2021 |
| HP            | 3047h                       | [71b6f0abea](https://linux-hardware.org/?probe=71b6f0abea) | Dec 25, 2021 |
| Gigabyte      | B450M DS3H V2               | [c3905a26bc](https://linux-hardware.org/?probe=c3905a26bc) | Dec 24, 2021 |
| MSI           | Z77A-G43                    | [f3b0f91998](https://linux-hardware.org/?probe=f3b0f91998) | Dec 23, 2021 |
| MSI           | Z77A-G43                    | [ec762046b0](https://linux-hardware.org/?probe=ec762046b0) | Dec 23, 2021 |
| Dell          | 0Y56T3 A00                  | [456cb4ebcc](https://linux-hardware.org/?probe=456cb4ebcc) | Dec 23, 2021 |
| HP            | 1494                        | [690d2204ea](https://linux-hardware.org/?probe=690d2204ea) | Dec 23, 2021 |
| MSI           | X470 GAMING PRO             | [d683987eea](https://linux-hardware.org/?probe=d683987eea) | Dec 23, 2021 |
| Intel         | X79 V1.3                    | [fbd3ea5fee](https://linux-hardware.org/?probe=fbd3ea5fee) | Dec 23, 2021 |
| MSI           | Z590-A PRO                  | [4b20c43b53](https://linux-hardware.org/?probe=4b20c43b53) | Dec 22, 2021 |
| Gigabyte      | B450M DS3H-CF               | [1f334f4c1c](https://linux-hardware.org/?probe=1f334f4c1c) | Dec 22, 2021 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [32e8c7ccb2](https://linux-hardware.org/?probe=32e8c7ccb2) | Dec 22, 2021 |
| ASRock        | X399 Taichi                 | [2ebe7aff5f](https://linux-hardware.org/?probe=2ebe7aff5f) | Dec 21, 2021 |
| ASUSTek       | P5LD2-SE                    | [28771b0751](https://linux-hardware.org/?probe=28771b0751) | Dec 21, 2021 |
| MSI           | A78M-E45 V2                 | [abed6d2431](https://linux-hardware.org/?probe=abed6d2431) | Dec 19, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | [69570e76ba](https://linux-hardware.org/?probe=69570e76ba) | Dec 19, 2021 |
| ASUSTek       | PRIME B350M-A               | [d38d7f8ea2](https://linux-hardware.org/?probe=d38d7f8ea2) | Dec 18, 2021 |
| HP            | 8169                        | [ed47c6784c](https://linux-hardware.org/?probe=ed47c6784c) | Dec 18, 2021 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | [855061aa1a](https://linux-hardware.org/?probe=855061aa1a) | Dec 18, 2021 |
| ASRock        | H510M-HVS R2.0              | [99e3241324](https://linux-hardware.org/?probe=99e3241324) | Dec 18, 2021 |
| Gigabyte      | H61M-DS2 DVI                | [13bfd7bbd2](https://linux-hardware.org/?probe=13bfd7bbd2) | Dec 18, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [856134876d](https://linux-hardware.org/?probe=856134876d) | Dec 18, 2021 |
| ASUSTek       | P5K SE                      | [bd3d222214](https://linux-hardware.org/?probe=bd3d222214) | Dec 17, 2021 |
| Samsung       | DT1234567890 SEC_SW_REVI... | [bfe957f66c](https://linux-hardware.org/?probe=bfe957f66c) | Dec 17, 2021 |
| Intel         | DX58SO2 AAG10925-205        | [952c6df001](https://linux-hardware.org/?probe=952c6df001) | Dec 16, 2021 |
| Intel         | DX58SO2 AAG10925-205        | [376eb1624e](https://linux-hardware.org/?probe=376eb1624e) | Dec 16, 2021 |
| Gigabyte      | B460M DS3H                  | [83c339b963](https://linux-hardware.org/?probe=83c339b963) | Dec 16, 2021 |
| Gigabyte      | B450M DS3H-CF               | [b7b779b709](https://linux-hardware.org/?probe=b7b779b709) | Dec 16, 2021 |
| Dell          | 0427JK A00                  | [5633e414a2](https://linux-hardware.org/?probe=5633e414a2) | Dec 16, 2021 |
| MSI           | A320M-A PRO                 | [f3f7e374e1](https://linux-hardware.org/?probe=f3f7e374e1) | Dec 16, 2021 |
| Gigabyte      | H61MS                       | [f5d1de8ec2](https://linux-hardware.org/?probe=f5d1de8ec2) | Dec 15, 2021 |
| MSI           | B550M PRO-VDH WIFI          | [9ea3459352](https://linux-hardware.org/?probe=9ea3459352) | Dec 15, 2021 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | [a6ddae1f31](https://linux-hardware.org/?probe=a6ddae1f31) | Dec 15, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [3d9f848d7e](https://linux-hardware.org/?probe=3d9f848d7e) | Dec 15, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [0db7a32c32](https://linux-hardware.org/?probe=0db7a32c32) | Dec 15, 2021 |
| Pegatron      | IPPPV-D3G                   | [bcdd9529a6](https://linux-hardware.org/?probe=bcdd9529a6) | Dec 15, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Manjaro/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| Manjaro           | 986      | 39.79%  |
| Manjaro 20.1      | 135      | 5.45%   |
| Manjaro 20.2.1    | 108      | 4.36%   |
| Manjaro 20.2      | 89       | 3.59%   |
| Manjaro 22.0.0    | 87       | 3.51%   |
| Manjaro 20.0.3    | 81       | 3.27%   |
| Manjaro 18.1.5    | 56       | 2.26%   |
| Manjaro 21.2.6    | 53       | 2.14%   |
| Manjaro 21.2.5    | 53       | 2.14%   |
| Manjaro 21.1.0    | 53       | 2.14%   |
| Manjaro 18.0.4    | 46       | 1.86%   |
| Manjaro 21.2.0    | 45       | 1.82%   |
| Manjaro 20.0      | 45       | 1.82%   |
| Manjaro 21.1.6    | 38       | 1.53%   |
| Manjaro 21.0.7    | 36       | 1.45%   |
| Manjaro 21.0.5    | 35       | 1.41%   |
| Manjaro 21.0      | 35       | 1.41%   |
| Manjaro 19.0.2    | 31       | 1.25%   |
| Manjaro 20.1.2    | 29       | 1.17%   |
| Manjaro 20.0.1    | 29       | 1.17%   |
| Manjaro 21.2.3    | 27       | 1.09%   |
| Manjaro 20.1.1    | 24       | 0.97%   |
| Manjaro 21.2.1    | 23       | 0.93%   |
| Manjaro 21.3.7    | 20       | 0.81%   |
| Manjaro 21.3.6    | 17       | 0.69%   |
| Manjaro 21.0.4    | 16       | 0.65%   |
| Manjaro 21.0.1    | 14       | 0.56%   |
| Manjaro 21.0.2    | 13       | 0.52%   |
| Manjaro 21.2rc    | 12       | 0.48%   |
| Manjaro 21.2.4    | 12       | 0.48%   |
| Manjaro 21.1.2    | 12       | 0.48%   |
| Manjaro 21.0.3    | 12       | 0.48%   |
| Manjaro 18.0.0-rc | 12       | 0.48%   |
| Manjaro 21.3.1    | 11       | 0.44%   |
| Manjaro 21.1.5    | 11       | 0.44%   |
| Manjaro 21.3.0    | 10       | 0.4%    |
| Manjaro 21.2.2    | 10       | 0.4%    |
| Manjaro 21.1.4    | 10       | 0.4%    |
| Manjaro 18.1.3    | 9        | 0.36%   |
| Manjaro 18.0.0    | 9        | 0.36%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Manjaro | 2272     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.9.16-1-MANJARO  | 114      | 4.15%   |
| 5.8.6-1-MANJARO   | 68       | 2.48%   |
| 5.13.19-2-MANJARO | 65       | 2.37%   |
| 5.15.28-1-MANJARO | 49       | 1.79%   |
| 5.9.11-3-MANJARO  | 47       | 1.71%   |
| 5.8.11-1-MANJARO  | 46       | 1.68%   |
| 5.10.42-1-MANJARO | 40       | 1.46%   |
| 5.8.18-1-MANJARO  | 38       | 1.38%   |
| 5.15.32-1-MANJARO | 32       | 1.17%   |
| 5.6.16-1-MANJARO  | 31       | 1.13%   |
| 5.15.60-1-MANJARO | 30       | 1.09%   |
| 5.10.36-2-MANJARO | 30       | 1.09%   |
| 5.7.9-1-MANJARO   | 29       | 1.06%   |
| 5.15.12-1-MANJARO | 29       | 1.06%   |
| 5.8.3-2-MANJARO   | 25       | 0.91%   |
| 5.8.16-2-MANJARO  | 25       | 0.91%   |
| 5.6.19-2-MANJARO  | 24       | 0.87%   |
| 5.6.15-1-MANJARO  | 24       | 0.87%   |
| 5.17.1-3-MANJARO  | 24       | 0.87%   |
| 5.7.0-3-MANJARO   | 23       | 0.84%   |
| 5.10.2-2-MANJARO  | 23       | 0.84%   |
| 5.6.7-1-MANJARO   | 22       | 0.8%    |
| 5.6.12-1-MANJARO  | 22       | 0.8%    |
| 5.16.14-1-MANJARO | 22       | 0.8%    |
| 5.15.2-2-MANJARO  | 22       | 0.8%    |
| 5.10.23-1-MANJARO | 22       | 0.8%    |
| 5.9.1-1-MANJARO   | 21       | 0.77%   |
| 5.11.6-1-MANJARO  | 21       | 0.77%   |
| 5.4.15-2-MANJARO  | 20       | 0.73%   |
| 5.7.17-2-MANJARO  | 19       | 0.69%   |
| 5.4.6-2-MANJARO   | 19       | 0.69%   |
| 5.10.7-3-MANJARO  | 19       | 0.69%   |
| 5.10.15-1-MANJARO | 19       | 0.69%   |
| 5.14.10-1-MANJARO | 17       | 0.62%   |
| 5.11.2-1-MANJARO  | 17       | 0.62%   |
| 5.10.53-1-MANJARO | 17       | 0.62%   |
| 5.9.3-1-MANJARO   | 16       | 0.58%   |
| 5.6.11-1-MANJARO  | 16       | 0.58%   |
| 5.15.7-1-MANJARO  | 16       | 0.58%   |
| 5.15.41-1-MANJARO | 16       | 0.58%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.9.16  | 114      | 4.15%   |
| 5.8.6   | 68       | 2.48%   |
| 5.13.19 | 65       | 2.37%   |
| 5.9.11  | 50       | 1.82%   |
| 5.15.28 | 49       | 1.79%   |
| 5.8.11  | 47       | 1.71%   |
| 5.10.42 | 40       | 1.46%   |
| 5.8.18  | 38       | 1.38%   |
| 5.15.32 | 32       | 1.17%   |
| 5.6.16  | 31       | 1.13%   |
| 5.15.60 | 30       | 1.09%   |
| 5.10.36 | 30       | 1.09%   |
| 5.7.9   | 29       | 1.06%   |
| 5.7.0   | 29       | 1.06%   |
| 5.17.1  | 29       | 1.06%   |
| 5.15.12 | 29       | 1.06%   |
| 5.9.1   | 28       | 1.02%   |
| 5.6.19  | 27       | 0.98%   |
| 5.8.3   | 26       | 0.95%   |
| 5.8.16  | 25       | 0.91%   |
| 5.6.15  | 24       | 0.87%   |
| 5.6.12  | 23       | 0.84%   |
| 5.15.2  | 23       | 0.84%   |
| 5.10.2  | 23       | 0.84%   |
| 5.6.7   | 22       | 0.8%    |
| 5.16.14 | 22       | 0.8%    |
| 5.10.23 | 22       | 0.8%    |
| 5.11.6  | 21       | 0.77%   |
| 5.7.17  | 20       | 0.73%   |
| 5.4.15  | 20       | 0.73%   |
| 5.10.7  | 20       | 0.73%   |
| 5.4.6   | 19       | 0.69%   |
| 5.10.15 | 19       | 0.69%   |
| 5.15.7  | 17       | 0.62%   |
| 5.14.10 | 17       | 0.62%   |
| 5.14.0  | 17       | 0.62%   |
| 5.11.2  | 17       | 0.62%   |
| 5.10.53 | 17       | 0.62%   |
| 5.9.3   | 16       | 0.58%   |
| 5.6.11  | 16       | 0.58%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 383      | 14.9%   |
| 5.10    | 354      | 13.77%  |
| 5.4     | 252      | 9.81%   |
| 5.9     | 228      | 8.87%   |
| 5.8     | 228      | 8.87%   |
| 5.6     | 172      | 6.69%   |
| 5.13    | 125      | 4.86%   |
| 5.7     | 109      | 4.24%   |
| 5.11    | 91       | 3.54%   |
| 4.19    | 66       | 2.57%   |
| 5.17    | 64       | 2.49%   |
| 5.16    | 63       | 2.45%   |
| 5.14    | 61       | 2.37%   |
| 5.18    | 54       | 2.1%    |
| 5.19    | 51       | 1.98%   |
| 5.12    | 49       | 1.91%   |
| 6.0     | 48       | 1.87%   |
| 5.5     | 39       | 1.52%   |
| 4.14    | 33       | 1.28%   |
| 5.3     | 23       | 0.89%   |
| 5.2     | 17       | 0.66%   |
| 6.1     | 14       | 0.54%   |
| 5.1     | 13       | 0.51%   |
| 5.0     | 11       | 0.43%   |
| 4.20    | 5        | 0.19%   |
| 4.18    | 5        | 0.19%   |
| 4.17    | 3        | 0.12%   |
| 4.16    | 3        | 0.12%   |
| 4.9     | 2        | 0.08%   |
| 4.7     | 2        | 0.08%   |
| 4.4     | 2        | 0.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 2272     | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| KDE5                     | 829      | 34.79%  |
| XFCE                     | 532      | 22.32%  |
| GNOME                    | 459      | 19.26%  |
| KDE                      | 244      | 10.24%  |
| Unknown                  | 99       | 4.15%   |
| X-Cinnamon               | 74       | 3.11%   |
| i3                       | 43       | 1.8%    |
| Cinnamon                 | 22       | 0.92%   |
| MATE                     | 21       | 0.88%   |
| Deepin                   | 21       | 0.88%   |
| Budgie                   | 13       | 0.55%   |
| LXQt                     | 7        | 0.29%   |
| Awesome                  | 4        | 0.17%   |
| sway                     | 3        | 0.13%   |
| bspwm                    | 3        | 0.13%   |
| ICEWM                    | 2        | 0.08%   |
| GNOME Classic            | 2        | 0.08%   |
| openbox                  | 1        | 0.04%   |
| LXDE                     | 1        | 0.04%   |
| Enlightenment            | 1        | 0.04%   |
| DWM                      | 1        | 0.04%   |
| /usr/bin/openbox-session | 1        | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 2079     | 89.88%  |
| Wayland | 174      | 7.52%   |
| Unknown | 37       | 1.6%    |
| Tty     | 23       | 0.99%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 980      | 41.74%  |
| SDDM    | 600      | 25.55%  |
| LightDM | 407      | 17.33%  |
| GDM     | 263      | 11.2%   |
| TDM     | 89       | 3.79%   |
| LXDM    | 4        | 0.17%   |
| SLiM    | 2        | 0.09%   |
| GREETD  | 2        | 0.09%   |
| XDM     | 1        | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 913      | 39.51%  |
| de_DE   | 198      | 8.57%   |
| ru_RU   | 184      | 7.96%   |
| Unknown | 151      | 6.53%   |
| en_GB   | 141      | 6.1%    |
| pt_BR   | 93       | 4.02%   |
| en_CA   | 64       | 2.77%   |
| fr_FR   | 59       | 2.55%   |
| es_ES   | 58       | 2.51%   |
| it_IT   | 50       | 2.16%   |
| pl_PL   | 42       | 1.82%   |
| en_AU   | 32       | 1.38%   |
| en_IN   | 19       | 0.82%   |
| ru_UA   | 18       | 0.78%   |
| nl_NL   | 18       | 0.78%   |
| de_AT   | 16       | 0.69%   |
| sv_SE   | 15       | 0.65%   |
| es_AR   | 14       | 0.61%   |
| zh_CN   | 13       | 0.56%   |
| fi_FI   | 12       | 0.52%   |
| es_MX   | 11       | 0.48%   |
| en_IE   | 11       | 0.48%   |
| fr_CA   | 9        | 0.39%   |
| en_ZA   | 9        | 0.39%   |
| hu_HU   | 8        | 0.35%   |
| en_NZ   | 8        | 0.35%   |
| da_DK   | 8        | 0.35%   |
| pt_PT   | 7        | 0.3%    |
| es_CL   | 7        | 0.3%    |
| en_PH   | 7        | 0.3%    |
| cs_CZ   | 7        | 0.3%    |
| en_IL   | 6        | 0.26%   |
| en_DK   | 6        | 0.26%   |
| uk_UA   | 5        | 0.22%   |
| ja_JP   | 5        | 0.22%   |
| tr_TR   | 4        | 0.17%   |
| nb_NO   | 4        | 0.17%   |
| fr_BE   | 4        | 0.17%   |
| es_UY   | 4        | 0.17%   |
| en_DE   | 4        | 0.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 1443     | 62.09%  |
| EFI  | 881      | 37.91%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 1954     | 84.55%  |
| Btrfs   | 211      | 9.13%   |
| Unknown | 40       | 1.73%   |
| Xfs     | 38       | 1.64%   |
| Overlay | 36       | 1.56%   |
| F2fs    | 12       | 0.52%   |
| Tmpfs   | 9        | 0.39%   |
| Zfs     | 4        | 0.17%   |
| Ext2    | 3        | 0.13%   |
| Ext3    | 2        | 0.09%   |
| XXXX    | 1        | 0.04%   |
| XXXfs   | 1        | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1085     | 46.59%  |
| GPT     | 988      | 42.42%  |
| MBR     | 256      | 10.99%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1911     | 82.3%   |
| Yes       | 411      | 17.7%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1417     | 61.08%  |
| Yes       | 903      | 38.92%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 670      | 29.49%  |
| Gigabyte Technology | 477      | 20.99%  |
| MSI                 | 365      | 16.07%  |
| ASRock              | 253      | 11.14%  |
| Dell                | 113      | 4.97%   |
| Hewlett-Packard     | 106      | 4.67%   |
| Intel               | 53       | 2.33%   |
| Lenovo              | 46       | 2.02%   |
| Acer                | 27       | 1.19%   |
| Unknown             | 19       | 0.84%   |
| Biostar             | 17       | 0.75%   |
| Pegatron            | 15       | 0.66%   |
| Huanan              | 12       | 0.53%   |
| Foxconn             | 10       | 0.44%   |
| Medion              | 8        | 0.35%   |
| Fujitsu             | 7        | 0.31%   |
| ECS                 | 7        | 0.31%   |
| Apple               | 7        | 0.31%   |
| BESSTAR Tech        | 5        | 0.22%   |
| Alienware           | 4        | 0.18%   |
| Positivo            | 3        | 0.13%   |
| PCWare              | 3        | 0.13%   |
| AZW                 | 3        | 0.13%   |
| ZOTAC               | 2        | 0.09%   |
| Shuttle             | 2        | 0.09%   |
| Minix               | 2        | 0.09%   |
| MACHINIST           | 2        | 0.09%   |
| Inventec            | 2        | 0.09%   |
| Google              | 2        | 0.09%   |
| Fujitsu Siemens     | 2        | 0.09%   |
| XFX                 | 1        | 0.04%   |
| VS Company          | 1        | 0.04%   |
| TPV-INVENTA         | 1        | 0.04%   |
| SYWZ                | 1        | 0.04%   |
| System76            | 1        | 0.04%   |
| Supermicro          | 1        | 0.04%   |
| SiYW                | 1        | 0.04%   |
| Samsung Electronics | 1        | 0.04%   |
| Packard Bell        | 1        | 0.04%   |
| OEM                 | 1        | 0.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| ASUS All Series                  | 65       | 2.86%   |
| Gigabyte B450M DS3H              | 25       | 1.1%    |
| MSI MS-7C02                      | 22       | 0.97%   |
| MSI MS-7C37                      | 21       | 0.92%   |
| Unknown                          | 21       | 0.92%   |
| ASUS TUF Gaming X570-PLUS        | 19       | 0.84%   |
| ASUS PRIME A320M-K               | 18       | 0.79%   |
| MSI MS-7C91                      | 15       | 0.66%   |
| MSI MS-7B79                      | 15       | 0.66%   |
| ASRock B450M Pro4                | 15       | 0.66%   |
| MSI MS-7B86                      | 13       | 0.57%   |
| ASUS ROG STRIX B450-F GAMING     | 13       | 0.57%   |
| MSI MS-7A38                      | 12       | 0.53%   |
| Gigabyte X570 AORUS ELITE        | 12       | 0.53%   |
| ASUS TUF Gaming B550M-PLUS       | 12       | 0.53%   |
| ASUS ROG STRIX B550-F GAMING     | 11       | 0.48%   |
| ASUS PRIME B450M-A               | 11       | 0.48%   |
| ASUS PRIME B350-PLUS             | 11       | 0.48%   |
| Gigabyte X570 AORUS MASTER       | 10       | 0.44%   |
| Gigabyte X470 AORUS ULTRA GAMING | 10       | 0.44%   |
| Gigabyte B450 AORUS M            | 10       | 0.44%   |
| Gigabyte 970A-DS3P               | 10       | 0.44%   |
| Dell OptiPlex 9020               | 10       | 0.44%   |
| MSI MS-7B89                      | 9        | 0.4%    |
| MSI MS-7693                      | 9        | 0.4%    |
| Dell OptiPlex 7010               | 9        | 0.4%    |
| ASUS ROG STRIX X570-E GAMING     | 9        | 0.4%    |
| ASUS ROG CROSSHAIR VIII HERO     | 9        | 0.4%    |
| ASUS PRIME X470-PRO              | 9        | 0.4%    |
| MSI MS-7C94                      | 8        | 0.35%   |
| MSI MS-7A34                      | 8        | 0.35%   |
| MSI MS-7817                      | 8        | 0.35%   |
| ASUS PRIME B450-PLUS             | 8        | 0.35%   |
| ASUS PRIME B350M-A               | 8        | 0.35%   |
| ASRock B450 Pro4                 | 8        | 0.35%   |
| Gigabyte B450 AORUS ELITE        | 7        | 0.31%   |
| ASUS PRIME X370-PRO              | 7        | 0.31%   |
| ASUS M5A78L-M PLUS/USB3          | 7        | 0.31%   |
| MSI MS-7C84                      | 6        | 0.26%   |
| MSI MS-7B85                      | 6        | 0.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| ASUS PRIME         | 139      | 6.12%   |
| ASUS ROG           | 124      | 5.46%   |
| ASUS TUF           | 69       | 3.04%   |
| Dell OptiPlex      | 68       | 2.99%   |
| ASUS All           | 65       | 2.86%   |
| Gigabyte X570      | 46       | 2.02%   |
| Gigabyte B450M     | 41       | 1.8%    |
| HP Compaq          | 33       | 1.45%   |
| Gigabyte B450      | 31       | 1.36%   |
| ASRock B450M       | 23       | 1.01%   |
| MSI MS-7C02        | 22       | 0.97%   |
| Lenovo ThinkCentre | 22       | 0.97%   |
| MSI MS-7C37        | 21       | 0.92%   |
| Unknown            | 21       | 0.92%   |
| Dell Precision     | 17       | 0.75%   |
| ASRock X570        | 17       | 0.75%   |
| ASRock B450        | 17       | 0.75%   |
| Acer Aspire        | 17       | 0.75%   |
| MSI MS-7C91        | 15       | 0.66%   |
| MSI MS-7B79        | 15       | 0.66%   |
| HP EliteDesk       | 15       | 0.66%   |
| ASUS P8Z77-V       | 15       | 0.66%   |
| Gigabyte B550      | 14       | 0.62%   |
| MSI MS-7B86        | 13       | 0.57%   |
| Gigabyte Z390      | 13       | 0.57%   |
| ASUS M5A97         | 13       | 0.57%   |
| ASUS M5A78L-M      | 13       | 0.57%   |
| MSI MS-7A38        | 12       | 0.53%   |
| Gigabyte X470      | 12       | 0.53%   |
| ASUS Maximus       | 12       | 0.53%   |
| Gigabyte 970A-DS3P | 11       | 0.48%   |
| ASUS P8H61-M       | 11       | 0.48%   |
| Gigabyte B550M     | 10       | 0.44%   |
| MSI MS-7B89        | 9        | 0.4%    |
| MSI MS-7693        | 9        | 0.4%    |
| HP Pavilion        | 9        | 0.4%    |
| ASRock X470        | 9        | 0.4%    |
| ASRock B550M       | 9        | 0.4%    |
| MSI MS-7C94        | 8        | 0.35%   |
| MSI MS-7A34        | 8        | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 379      | 16.68%  |
| 2019    | 288      | 12.68%  |
| 2020    | 245      | 10.78%  |
| 2017    | 198      | 8.71%   |
| 2012    | 196      | 8.63%   |
| 2013    | 162      | 7.13%   |
| 2014    | 135      | 5.94%   |
| 2011    | 124      | 5.46%   |
| 2016    | 100      | 4.4%    |
| 2015    | 97       | 4.27%   |
| 2010    | 83       | 3.65%   |
| 2021    | 75       | 3.3%    |
| 2009    | 69       | 3.04%   |
| 2008    | 43       | 1.89%   |
| 2007    | 39       | 1.72%   |
| 2022    | 22       | 0.97%   |
| 2006    | 12       | 0.53%   |
| 2005    | 4        | 0.18%   |
| Unknown | 1        | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 2272     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 2271     | 99.91%  |
| Enabled  | 2        | 0.09%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2270     | 99.91%  |
| Yes  | 2        | 0.09%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 844      | 36.47%  |
| 32.01-64.0  | 456      | 19.71%  |
| 8.01-16.0   | 435      | 18.8%   |
| 4.01-8.0    | 213      | 9.2%    |
| 3.01-4.0    | 161      | 6.96%   |
| 64.01-256.0 | 107      | 4.62%   |
| 24.01-32.0  | 65       | 2.81%   |
| 1.01-2.0    | 28       | 1.21%   |
| 2.01-3.0    | 5        | 0.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 629      | 24.51%  |
| 1.01-2.0    | 591      | 23.03%  |
| 2.01-3.0    | 585      | 22.8%   |
| 3.01-4.0    | 414      | 16.13%  |
| 8.01-16.0   | 212      | 8.26%   |
| 0.51-1.0    | 69       | 2.69%   |
| 16.01-24.0  | 36       | 1.4%    |
| 0.01-0.5    | 11       | 0.43%   |
| 32.01-64.0  | 9        | 0.35%   |
| 24.01-32.0  | 9        | 0.35%   |
| 64.01-256.0 | 1        | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 713      | 29.83%  |
| 1      | 566      | 23.68%  |
| 3      | 486      | 20.33%  |
| 4      | 310      | 12.97%  |
| 5      | 177      | 7.41%   |
| 6      | 67       | 2.8%    |
| 7      | 35       | 1.46%   |
| 8      | 11       | 0.46%   |
| 0      | 9        | 0.38%   |
| 9      | 7        | 0.29%   |
| 11     | 4        | 0.17%   |
| 12     | 2        | 0.08%   |
| 10     | 2        | 0.08%   |
| 20     | 1        | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1517     | 65.81%  |
| Yes       | 788      | 34.19%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 2246     | 98.86%  |
| No        | 26       | 1.14%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1235     | 53.65%  |
| Yes       | 1067     | 46.35%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1385     | 59.98%  |
| Yes       | 924      | 40.02%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 428      | 18.72%  |
| Germany      | 276      | 12.07%  |
| Russia       | 215      | 9.41%   |
| Brazil       | 131      | 5.73%   |
| Canada       | 95       | 4.16%   |
| France       | 81       | 3.54%   |
| Spain        | 78       | 3.41%   |
| UK           | 73       | 3.19%   |
| Italy        | 71       | 3.11%   |
| Poland       | 68       | 2.97%   |
| Ukraine      | 52       | 2.27%   |
| Netherlands  | 43       | 1.88%   |
| Sweden       | 42       | 1.84%   |
| Australia    | 34       | 1.49%   |
| Austria      | 32       | 1.4%    |
| Finland      | 29       | 1.27%   |
| Belgium      | 25       | 1.09%   |
| Mexico       | 24       | 1.05%   |
| Romania      | 22       | 0.96%   |
| India        | 22       | 0.96%   |
| Argentina    | 21       | 0.92%   |
| Greece       | 20       | 0.87%   |
| Norway       | 18       | 0.79%   |
| Bulgaria     | 18       | 0.79%   |
| Portugal     | 17       | 0.74%   |
| Hungary      | 16       | 0.7%    |
| Denmark      | 16       | 0.7%    |
| Switzerland  | 15       | 0.66%   |
| South Africa | 13       | 0.57%   |
| China        | 12       | 0.52%   |
| Belarus      | 12       | 0.52%   |
| Israel       | 11       | 0.48%   |
| Czechia      | 11       | 0.48%   |
| New Zealand  | 10       | 0.44%   |
| Lithuania    | 10       | 0.44%   |
| Ireland      | 10       | 0.44%   |
| Turkey       | 9        | 0.39%   |
| Saudi Arabia | 9        | 0.39%   |
| Chile        | 9        | 0.39%   |
| Bangladesh   | 9        | 0.39%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Moscow            | 51       | 2.12%   |
| St Petersburg     | 21       | 0.87%   |
| Warsaw            | 17       | 0.71%   |
| Vienna            | 17       | 0.71%   |
| Kyiv              | 17       | 0.71%   |
| Berlin            | 16       | 0.67%   |
| Madrid            | 15       | 0.62%   |
| Toronto           | 14       | 0.58%   |
| Athens            | 14       | 0.58%   |
| Stockholm         | 12       | 0.5%    |
| Sao Paulo         | 12       | 0.5%    |
| Rome              | 12       | 0.5%    |
| Helsinki          | 11       | 0.46%   |
| Rio de Janeiro    | 10       | 0.42%   |
| Paris             | 10       | 0.42%   |
| Frankfurt am Main | 10       | 0.42%   |
| Amsterdam         | 10       | 0.42%   |
| Sofia             | 9        | 0.37%   |
| Portland          | 9        | 0.37%   |
| Milan             | 9        | 0.37%   |
| Krakow            | 9        | 0.37%   |
| Hamburg           | 9        | 0.37%   |
| Copenhagen        | 9        | 0.37%   |
| Bucharest         | 9        | 0.37%   |
| Sydney            | 8        | 0.33%   |
| Stuttgart         | 8        | 0.33%   |
| Miami             | 8        | 0.33%   |
| Melbourne         | 8        | 0.33%   |
| Dallas            | 8        | 0.33%   |
| Barcelona         | 8        | 0.33%   |
| Austin            | 8        | 0.33%   |
| Omsk              | 7        | 0.29%   |
| Montreal          | 7        | 0.29%   |
| Minsk             | 7        | 0.29%   |
| Indianapolis      | 7        | 0.29%   |
| Yekaterinburg     | 6        | 0.25%   |
| Vilnius           | 6        | 0.25%   |
| Riyadh            | 6        | 0.25%   |
| Oslo              | 6        | 0.25%   |
| New York          | 6        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 900      | 1509   | 18.04%  |
| Seagate                   | 882      | 1423   | 17.68%  |
| Samsung Electronics       | 836      | 1452   | 16.75%  |
| Kingston                  | 320      | 452    | 6.41%   |
| Toshiba                   | 277      | 357    | 5.55%   |
| Crucial                   | 264      | 405    | 5.29%   |
| SanDisk                   | 245      | 322    | 4.91%   |
| Hitachi                   | 128      | 185    | 2.57%   |
| Intel                     | 96       | 132    | 1.92%   |
| Phison                    | 82       | 110    | 1.64%   |
| A-DATA Technology         | 78       | 106    | 1.56%   |
| HGST                      | 57       | 92     | 1.14%   |
| China                     | 41       | 60     | 0.82%   |
| PNY                       | 40       | 58     | 0.8%    |
| Silicon Motion            | 38       | 50     | 0.76%   |
| OCZ                       | 38       | 48     | 0.76%   |
| Unknown                   | 34       | 55     | 0.68%   |
| SPCC                      | 33       | 40     | 0.66%   |
| XPG                       | 32       | 36     | 0.64%   |
| Patriot                   | 32       | 38     | 0.64%   |
| Intenso                   | 32       | 47     | 0.64%   |
| Micron/Crucial Technology | 30       | 38     | 0.6%    |
| SK hynix                  | 28       | 32     | 0.56%   |
| Corsair                   | 26       | 37     | 0.52%   |
| Micron Technology         | 23       | 28     | 0.46%   |
| Transcend                 | 21       | 21     | 0.42%   |
| Plextor                   | 20       | 23     | 0.4%    |
| Team                      | 18       | 23     | 0.36%   |
| Lexar                     | 18       | 20     | 0.36%   |
| JMicron Technology        | 17       | 23     | 0.34%   |
| Realtek Semiconductor     | 16       | 21     | 0.32%   |
| GOODRAM                   | 16       | 18     | 0.32%   |
| Apacer                    | 14       | 16     | 0.28%   |
| Maxtor                    | 12       | 14     | 0.24%   |
| Phison Electronics        | 11       | 13     | 0.22%   |
| KingDian                  | 10       | 10     | 0.2%    |
| Gigabyte Technology       | 10       | 18     | 0.2%    |
| Hewlett-Packard           | 9        | 12     | 0.18%   |
| ASMT                      | 9        | 16     | 0.18%   |
| ADATA Technology          | 9        | 11     | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD  | 80       | 1.35%   |
| Samsung SSD 860 EVO 500GB        | 75       | 1.26%   |
| Seagate ST1000DM010-2EP102 1TB   | 73       | 1.23%   |
| Seagate ST2000DM008-2FR102 2TB   | 68       | 1.14%   |
| Samsung NVMe SSD Drive 500GB     | 63       | 1.06%   |
| Samsung SSD 850 EVO 500GB        | 60       | 1.01%   |
| Samsung SSD 850 EVO 250GB        | 59       | 0.99%   |
| Kingston SA400S37120G 120GB SSD  | 52       | 0.87%   |
| Toshiba DT01ACA100 1TB           | 51       | 0.86%   |
| WDC WD10EZEX-08WN4A0 1TB         | 49       | 0.82%   |
| Samsung NVMe SSD Drive 1TB       | 49       | 0.82%   |
| Samsung SSD 860 EVO 1TB          | 47       | 0.79%   |
| Crucial CT500MX500SSD1 500GB     | 46       | 0.77%   |
| Seagate ST2000DM006-2DM164 2TB   | 39       | 0.66%   |
| Seagate ST1000DM003-1ER162 1TB   | 38       | 0.64%   |
| Samsung SSD 860 EVO 250GB        | 38       | 0.64%   |
| Kingston SA400S37480G 480GB SSD  | 38       | 0.64%   |
| Seagate ST500DM002-1BD142 500GB  | 37       | 0.62%   |
| WDC WD10EZEX-00BN5A0 1TB         | 36       | 0.61%   |
| Crucial CT240BX500SSD1 240GB     | 35       | 0.59%   |
| Crucial CT1000MX500SSD1 1TB      | 35       | 0.59%   |
| Toshiba HDWD110 1TB              | 34       | 0.57%   |
| Seagate ST1000DM003-1CH162 1TB   | 32       | 0.54%   |
| Seagate ST2000DM001-1ER164 2TB   | 31       | 0.52%   |
| SanDisk NVMe SSD Drive 500GB     | 31       | 0.52%   |
| Kingston SV300S37A120G 120GB SSD | 31       | 0.52%   |
| Seagate ST3500418AS 500GB        | 29       | 0.49%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 28       | 0.47%   |
| Seagate ST4000DM004-2CV104 4TB   | 26       | 0.44%   |
| Seagate Expansion 4TB            | 26       | 0.44%   |
| Toshiba DT01ACA050 500GB         | 25       | 0.42%   |
| Seagate ST2000DM001-1CH164 2TB   | 25       | 0.42%   |
| Toshiba DT01ACA200 2TB           | 24       | 0.4%    |
| Samsung SSD 970 EVO Plus 500GB   | 24       | 0.4%    |
| Samsung SSD 840 EVO 250GB        | 23       | 0.39%   |
| Samsung NVMe SSD Drive 250GB     | 23       | 0.39%   |
| Phison NVMe SSD Drive 1TB        | 22       | 0.37%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 21       | 0.35%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 21       | 0.35%   |
| Seagate ST31000524AS 1TB         | 21       | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 866      | 1392   | 37.65%  |
| WDC                 | 799      | 1292   | 34.74%  |
| Toshiba             | 247      | 314    | 10.74%  |
| Samsung Electronics | 131      | 200    | 5.7%    |
| Hitachi             | 128      | 185    | 5.57%   |
| HGST                | 56       | 91     | 2.43%   |
| Unknown             | 16       | 24     | 0.7%    |
| Maxtor              | 12       | 14     | 0.52%   |
| ASMT                | 7        | 10     | 0.3%    |
| Fujitsu             | 6        | 6      | 0.26%   |
| Intenso             | 5        | 8      | 0.22%   |
| Apple               | 5        | 8      | 0.22%   |
| USB3.0              | 4        | 4      | 0.17%   |
| HGST HTS            | 3        | 3      | 0.13%   |
| ASMedia             | 3        | 3      | 0.13%   |
| USB                 | 2        | 2      | 0.09%   |
| Maxone              | 2        | 2      | 0.09%   |
| JMicron Technology  | 2        | 4      | 0.09%   |
| Hewlett-Packard     | 2        | 2      | 0.09%   |
| SABRENT             | 1        | 1      | 0.04%   |
| MaxDigital          | 1        | 1      | 0.04%   |
| Lenovo              | 1        | 1      | 0.04%   |
| IBM/Hitachi         | 1        | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 500      | 761    | 26.53%  |
| Kingston            | 282      | 389    | 14.96%  |
| Crucial             | 237      | 369    | 12.57%  |
| SanDisk             | 155      | 203    | 8.22%   |
| WDC                 | 121      | 171    | 6.42%   |
| A-DATA Technology   | 64       | 87     | 3.4%    |
| Intel               | 49       | 66     | 2.6%    |
| China               | 40       | 59     | 2.12%   |
| OCZ                 | 38       | 48     | 2.02%   |
| PNY                 | 35       | 53     | 1.86%   |
| Patriot             | 30       | 36     | 1.59%   |
| SPCC                | 27       | 34     | 1.43%   |
| Toshiba             | 22       | 32     | 1.17%   |
| Intenso             | 20       | 30     | 1.06%   |
| Plextor             | 18       | 21     | 0.95%   |
| Lexar               | 18       | 20     | 0.95%   |
| Corsair             | 18       | 27     | 0.95%   |
| Transcend           | 16       | 16     | 0.85%   |
| Micron Technology   | 15       | 16     | 0.8%    |
| GOODRAM             | 15       | 17     | 0.8%    |
| Team                | 14       | 19     | 0.74%   |
| Apacer              | 14       | 16     | 0.74%   |
| KingDian            | 10       | 10     | 0.53%   |
| SK hynix            | 9        | 10     | 0.48%   |
| Seagate             | 8        | 11     | 0.42%   |
| Gigabyte Technology | 8        | 11     | 0.42%   |
| Leven               | 6        | 6      | 0.32%   |
| JMicron Technology  | 6        | 7      | 0.32%   |
| KingSpec            | 5        | 6      | 0.27%   |
| Mushkin             | 4        | 4      | 0.21%   |
| LITEONIT            | 4        | 5      | 0.21%   |
| LITEON              | 4        | 4      | 0.21%   |
| Hoodisk             | 4        | 4      | 0.21%   |
| NGFF                | 3        | 3      | 0.16%   |
| Kingmax             | 3        | 4      | 0.16%   |
| Apple               | 3        | 3      | 0.16%   |
| Verbatim            | 2        | 2      | 0.11%   |
| TO Exter            | 2        | 2      | 0.11%   |
| Smartbuy            | 2        | 2      | 0.11%   |
| Pioneer             | 2        | 2      | 0.11%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 1666     | 3568   | 41.53%  |
| SSD     | 1462     | 2662   | 36.44%  |
| NVMe    | 804      | 1261   | 20.04%  |
| Unknown | 75       | 99     | 1.87%   |
| MMC     | 5        | 5      | 0.12%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 2108     | 6020   | 67.72%  |
| NVMe | 797      | 1249   | 25.6%   |
| SAS  | 203      | 321    | 6.52%   |
| MMC  | 5        | 5      | 0.16%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 1594     | 3060   | 44.45%  |
| 0.51-1.0   | 1096     | 1784   | 30.56%  |
| 1.01-2.0   | 483      | 719    | 13.47%  |
| 3.01-4.0   | 176      | 269    | 4.91%   |
| 2.01-3.0   | 112      | 172    | 3.12%   |
| 4.01-10.0  | 112      | 203    | 3.12%   |
| 10.01-20.0 | 13       | 23     | 0.36%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 420      | 17.33%  |
| 251-500        | 414      | 17.09%  |
| 1001-2000      | 402      | 16.59%  |
| 501-1000       | 398      | 16.43%  |
| More than 3000 | 340      | 14.03%  |
| 2001-3000      | 207      | 8.54%   |
| 51-100         | 87       | 3.59%   |
| Unknown        | 83       | 3.43%   |
| 1-20           | 39       | 1.61%   |
| 21-50          | 33       | 1.36%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 390      | 15.53%  |
| 1-20           | 375      | 14.93%  |
| 501-1000       | 320      | 12.74%  |
| 21-50          | 297      | 11.82%  |
| 251-500        | 289      | 11.5%   |
| 51-100         | 270      | 10.75%  |
| 1001-2000      | 246      | 9.79%   |
| More than 3000 | 144      | 5.73%   |
| 2001-3000      | 97       | 3.86%   |
| Unknown        | 83       | 3.3%    |
| 0              | 1        | 0.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 7        | 9      | 2.3%    |
| WDC WD5000AAKX-001CA0 500GB           | 5        | 7      | 1.64%   |
| WDC WD10EARS-00Y5B1 1TB               | 5        | 5      | 1.64%   |
| Samsung Electronics HD103SJ 1TB       | 5        | 5      | 1.64%   |
| Hitachi HDS721010CLA332 1TB           | 5        | 5      | 1.64%   |
| Seagate ST3500413AS 500GB             | 4        | 5      | 1.32%   |
| Seagate ST1000DX001-1CM162 1TB        | 4        | 6      | 1.32%   |
| Samsung Electronics SSD 960 EVO 250GB | 4        | 5      | 1.32%   |
| Samsung Electronics HD103UJ 1TB       | 4        | 6      | 1.32%   |
| WDC WD15EARS-00MVWB0 1TB              | 3        | 3      | 0.99%   |
| WDC WD10EZEX-00RKKA0 1TB              | 3        | 3      | 0.99%   |
| WDC WD10EZEX-00BN5A0 1TB              | 3        | 3      | 0.99%   |
| WDC WD10EARX-00N0YB0 1TB              | 3        | 4      | 0.99%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 3        | 3      | 0.99%   |
| Toshiba MQ01ABD050 500GB              | 3        | 3      | 0.99%   |
| Seagate ST4000DM000-1F2168 4TB        | 3        | 8      | 0.99%   |
| Seagate ST2000DM001-1CH164 2TB        | 3        | 3      | 0.99%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 3        | 3      | 0.99%   |
| Kingston SV300S37A120G 120GB SSD      | 3        | 3      | 0.99%   |
| WDC WD5000AAKX-00ERMA0 500GB          | 2        | 2      | 0.66%   |
| WDC WD5000AAKX-003CA0 500GB           | 2        | 2      | 0.66%   |
| WDC WD5000AACS-00G8B1 500GB           | 2        | 2      | 0.66%   |
| WDC WD40EFRX-68WT0N0 4TB              | 2        | 3      | 0.66%   |
| WDC WD20EARX-00PASB0 2TB              | 2        | 2      | 0.66%   |
| WDC WD20EARS-00MVWB0 2TB              | 2        | 2      | 0.66%   |
| Seagate ST3250318AS 250GB             | 2        | 2      | 0.66%   |
| Seagate ST3250310AS 250GB             | 2        | 2      | 0.66%   |
| Seagate ST31000524AS 1TB              | 2        | 4      | 0.66%   |
| Seagate ST31000340NS 1TB              | 2        | 3      | 0.66%   |
| Seagate ST2000DX001-1CM164 2TB        | 2        | 2      | 0.66%   |
| Seagate ST2000DM008-2FR102 2TB        | 2        | 2      | 0.66%   |
| Seagate ST2000DM001-1ER164 2TB        | 2        | 7      | 0.66%   |
| Seagate ST1000DX001-1NS162 1TB        | 2        | 3      | 0.66%   |
| Seagate ST1000DM010-2EP102 1TB        | 2        | 2      | 0.66%   |
| Seagate ST1000DM003-9YN162 1TB        | 2        | 3      | 0.66%   |
| SanDisk SSD PLUS 240GB                | 2        | 2      | 0.66%   |
| Samsung Electronics HD501LJ 500GB     | 2        | 2      | 0.66%   |
| Samsung Electronics HD322HJ 320GB     | 2        | 2      | 0.66%   |
| Kingston SA400S37480G 480GB SSD       | 2        | 2      | 0.66%   |
| Kingston SA400S37240G 240GB SSD       | 2        | 2      | 0.66%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 94       | 109    | 32.19%  |
| Seagate             | 81       | 117    | 27.74%  |
| Samsung Electronics | 26       | 32     | 8.9%    |
| Hitachi             | 19       | 21     | 6.51%   |
| Toshiba             | 11       | 14     | 3.77%   |
| Kingston            | 11       | 11     | 3.77%   |
| Intel               | 9        | 10     | 3.08%   |
| SanDisk             | 7        | 10     | 2.4%    |
| HGST                | 7        | 7      | 2.4%    |
| Crucial             | 6        | 6      | 2.05%   |
| A-DATA Technology   | 4        | 4      | 1.37%   |
| OCZ                 | 2        | 2      | 0.68%   |
| Apacer              | 2        | 2      | 0.68%   |
| Transcend           | 1        | 1      | 0.34%   |
| SPCC                | 1        | 1      | 0.34%   |
| SK hynix            | 1        | 2      | 0.34%   |
| Phison              | 1        | 2      | 0.34%   |
| Patriot             | 1        | 1      | 0.34%   |
| Maxtor              | 1        | 1      | 0.34%   |
| MaxDigital          | 1        | 1      | 0.34%   |
| Intenso             | 1        | 4      | 0.34%   |
| Hewlett-Packard     | 1        | 1      | 0.34%   |
| Fujitsu             | 1        | 1      | 0.34%   |
| Drevo               | 1        | 1      | 0.34%   |
| Corsair             | 1        | 5      | 0.34%   |
| ASMT                | 1        | 5      | 0.34%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 93       | 108    | 40.09%  |
| Seagate             | 80       | 114    | 34.48%  |
| Samsung Electronics | 19       | 24     | 8.19%   |
| Hitachi             | 19       | 21     | 8.19%   |
| Toshiba             | 11       | 14     | 4.74%   |
| HGST                | 7        | 7      | 3.02%   |
| Maxtor              | 1        | 1      | 0.43%   |
| MaxDigital          | 1        | 1      | 0.43%   |
| Fujitsu             | 1        | 1      | 0.43%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 213      | 291    | 78.6%   |
| SSD  | 49       | 69     | 18.08%  |
| NVMe | 9        | 11     | 3.32%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WDS256G1X0C-00ENX0 256GB      | 1        | 1      | 8.33%   |
| WDC WD3200BPVT-24ZEST0 320GB      | 1        | 1      | 8.33%   |
| WDC WD1600AAJS-65WAA0 160GB       | 1        | 1      | 8.33%   |
| Toshiba MQ01ABF050 500GB          | 1        | 1      | 8.33%   |
| Toshiba MK1059GSM 1TB             | 1        | 1      | 8.33%   |
| Seagate ST9640320AS 640GB         | 1        | 1      | 8.33%   |
| Seagate ST3500418AS 500GB         | 1        | 1      | 8.33%   |
| Seagate ST3250318AS 250GB         | 1        | 1      | 8.33%   |
| Seagate ST31000524AS 1TB          | 1        | 2      | 8.33%   |
| Samsung Electronics HD321HJ 320GB | 1        | 1      | 8.33%   |
| Kingston SV300S37A120G 120GB SSD  | 1        | 1      | 8.33%   |
| Hitachi HDS721010CLA332 1TB       | 1        | 1      | 8.33%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 4        | 5      | 33.33%  |
| WDC                 | 3        | 3      | 25%     |
| Toshiba             | 2        | 2      | 16.67%  |
| Samsung Electronics | 1        | 1      | 8.33%   |
| Kingston            | 1        | 1      | 8.33%   |
| Hitachi             | 1        | 1      | 8.33%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 1479     | 4650   | 55.87%  |
| Works    | 899      | 2561   | 33.96%  |
| Malfunc  | 257      | 371    | 9.71%   |
| Failed   | 12       | 13     | 0.45%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1204     | 34.65%  |
| AMD                              | 1063     | 30.59%  |
| Samsung Electronics              | 346      | 9.96%   |
| ASMedia Technology               | 147      | 4.23%   |
| SanDisk                          | 124      | 3.57%   |
| Phison Electronics               | 108      | 3.11%   |
| Marvell Technology Group         | 65       | 1.87%   |
| Micron/Crucial Technology        | 59       | 1.7%    |
| Silicon Motion                   | 53       | 1.53%   |
| JMicron Technology               | 53       | 1.53%   |
| Kingston Technology Company      | 52       | 1.5%    |
| ADATA Technology                 | 42       | 1.21%   |
| Nvidia                           | 34       | 0.98%   |
| Realtek Semiconductor            | 27       | 0.78%   |
| SK hynix                         | 19       | 0.55%   |
| Toshiba America Info Systems     | 8        | 0.23%   |
| Micron Technology                | 8        | 0.23%   |
| LSI Logic / Symbios Logic        | 8        | 0.23%   |
| KIOXIA                           | 8        | 0.23%   |
| VIA Technologies                 | 7        | 0.2%    |
| Seagate Technology               | 6        | 0.17%   |
| Silicon Image                    | 5        | 0.14%   |
| Lite-On Technology               | 5        | 0.14%   |
| Broadcom / LSI                   | 4        | 0.12%   |
| Adaptec                          | 4        | 0.12%   |
| Integrated Technology Express    | 3        | 0.09%   |
| Shenzhen Longsys Electronics     | 2        | 0.06%   |
| Union Memory (Shenzhen)          | 1        | 0.03%   |
| Transcend                        | 1        | 0.03%   |
| Silicon Integrated Systems [SiS] | 1        | 0.03%   |
| PMC-Sierra                       | 1        | 0.03%   |
| OCZ Technology Group             | 1        | 0.03%   |
| MAXIO Technology (Hangzhou)      | 1        | 0.03%   |
| Lenovo                           | 1        | 0.03%   |
| INNOGRIT                         | 1        | 0.03%   |
| HighPoint Technologies           | 1        | 0.03%   |
| Dell                             | 1        | 0.03%   |
| Biwin Storage Technology         | 1        | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 716      | 16.44%  |
| AMD 400 Series Chipset SATA Controller                                                  | 315      | 7.23%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 218      | 5.01%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 144      | 3.31%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 144      | 3.31%   |
| AMD 500 Series Chipset SATA Controller                                                  | 126      | 2.89%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 117      | 2.69%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 102      | 2.34%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 102      | 2.34%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 99       | 2.27%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 98       | 2.25%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 91       | 2.09%   |
| AMD 300 Series Chipset SATA Controller                                                  | 84       | 1.93%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 76       | 1.75%   |
| Intel SATA Controller [RAID mode]                                                       | 72       | 1.65%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 64       | 1.47%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 59       | 1.35%   |
| Phison E12 NVMe Controller                                                              | 55       | 1.26%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 50       | 1.15%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 49       | 1.13%   |
| AMD FCH SATA Controller D                                                               | 48       | 1.1%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 42       | 0.96%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 41       | 0.94%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 41       | 0.94%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 41       | 0.94%   |
| AMD X370 Series Chipset SATA Controller                                                 | 41       | 0.94%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 39       | 0.9%    |
| Kingston Company A2000 NVMe SSD                                                         | 36       | 0.83%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 35       | 0.8%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 34       | 0.78%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 33       | 0.76%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 30       | 0.69%   |
| Samsung NVMe SSD Controller 980                                                         | 30       | 0.69%   |
| Intel SSD 660P Series                                                                   | 30       | 0.69%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 30       | 0.69%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 28       | 0.64%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 26       | 0.6%    |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 26       | 0.6%    |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 26       | 0.6%    |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 25       | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 2017     | 61.1%   |
| NVMe | 802      | 24.3%   |
| IDE  | 347      | 10.51%  |
| RAID | 116      | 3.51%   |
| SAS  | 16       | 0.48%   |
| SCSI | 3        | 0.09%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 1179     | 51.87%  |
| AMD    | 1094     | 48.13%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 119      | 5.21%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 71       | 3.11%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 61       | 2.67%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 57       | 2.5%    |
| AMD Ryzen 9 3900X 12-Core Processor         | 44       | 1.93%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 29       | 1.27%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 28       | 1.23%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 27       | 1.18%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 25       | 1.1%    |
| AMD Ryzen 5 3600X 6-Core Processor          | 25       | 1.1%    |
| AMD FX-8350 Eight-Core Processor            | 24       | 1.05%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 23       | 1.01%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 21       | 0.92%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 21       | 0.92%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 21       | 0.92%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 21       | 0.92%   |
| AMD FX-6300 Six-Core Processor              | 21       | 0.92%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 20       | 0.88%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 20       | 0.88%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 20       | 0.88%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 20       | 0.88%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 19       | 0.83%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 19       | 0.83%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 19       | 0.83%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 19       | 0.83%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 18       | 0.79%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 17       | 0.74%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 17       | 0.74%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 17       | 0.74%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 17       | 0.74%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 17       | 0.74%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 16       | 0.7%    |
| Intel Core i7-6700 CPU @ 3.40GHz            | 15       | 0.66%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 15       | 0.66%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 15       | 0.66%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 15       | 0.66%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 15       | 0.66%   |
| AMD Ryzen 7 1700X Eight-Core Processor      | 15       | 0.66%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 15       | 0.66%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 14       | 0.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 397      | 17.44%  |
| AMD Ryzen 5             | 372      | 16.34%  |
| Intel Core i7           | 315      | 13.83%  |
| AMD Ryzen 7             | 261      | 11.46%  |
| Intel Core i3           | 122      | 5.36%   |
| Intel Xeon              | 108      | 4.74%   |
| AMD Ryzen 9             | 102      | 4.48%   |
| AMD FX                  | 101      | 4.44%   |
| AMD Ryzen 3             | 44       | 1.93%   |
| Intel Core 2 Duo        | 40       | 1.76%   |
| Other                   | 35       | 1.54%   |
| Intel Celeron           | 33       | 1.45%   |
| Intel Pentium           | 30       | 1.32%   |
| AMD Ryzen Threadripper  | 26       | 1.14%   |
| AMD Phenom II X4        | 25       | 1.1%    |
| Intel Core 2 Quad       | 22       | 0.97%   |
| Intel Pentium Dual-Core | 21       | 0.92%   |
| Intel Core i9           | 18       | 0.79%   |
| AMD Athlon II X2        | 18       | 0.79%   |
| AMD A8                  | 17       | 0.75%   |
| AMD A10                 | 17       | 0.75%   |
| AMD A4                  | 15       | 0.66%   |
| AMD Phenom II X6        | 11       | 0.48%   |
| AMD Athlon 64 X2        | 11       | 0.48%   |
| AMD Athlon              | 11       | 0.48%   |
| Intel Core 2            | 10       | 0.44%   |
| AMD Athlon II X4        | 9        | 0.4%    |
| Intel Atom              | 8        | 0.35%   |
| AMD Ryzen 5 PRO         | 8        | 0.35%   |
| AMD Athlon X4           | 8        | 0.35%   |
| AMD Phenom              | 7        | 0.31%   |
| Intel Pentium Gold      | 6        | 0.26%   |
| Intel Pentium Dual      | 6        | 0.26%   |
| AMD Ryzen 7 PRO         | 6        | 0.26%   |
| Intel Genuine           | 5        | 0.22%   |
| AMD Athlon II X3        | 5        | 0.22%   |
| Intel Pentium D         | 4        | 0.18%   |
| AMD Sempron             | 3        | 0.13%   |
| AMD Phenom II X2        | 3        | 0.13%   |
| AMD E1                  | 3        | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 813      | 35.69%  |
| 6       | 526      | 23.09%  |
| 2       | 356      | 15.63%  |
| 8       | 341      | 14.97%  |
| 12      | 92       | 4.04%   |
| 16      | 57       | 2.5%    |
| 3       | 40       | 1.76%   |
| 1       | 25       | 1.1%    |
| 10      | 17       | 0.75%   |
| 24      | 4        | 0.18%   |
| 32      | 3        | 0.13%   |
| Unknown | 2        | 0.09%   |
| 20      | 1        | 0.04%   |
| 14      | 1        | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 2254     | 99.21%  |
| 2      | 18       | 0.79%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 1517     | 66.56%  |
| 1       | 760      | 33.35%  |
| Unknown | 2        | 0.09%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 2244     | 98.55%  |
| Unknown        | 33       | 1.45%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1144     | 48.56%  |
| 0x08701021 | 127      | 5.39%   |
| 0x0800820d | 98       | 4.16%   |
| 0x306c3    | 97       | 4.12%   |
| 0x08701013 | 74       | 3.14%   |
| 0x306a9    | 65       | 2.76%   |
| 0x206a7    | 59       | 2.5%    |
| 0x906ea    | 55       | 2.33%   |
| 0x506e3    | 50       | 2.12%   |
| 0x06000852 | 44       | 1.87%   |
| 0x1067a    | 34       | 1.44%   |
| 0x08001138 | 30       | 1.27%   |
| 0x906e9    | 26       | 1.1%    |
| 0x306f2    | 22       | 0.93%   |
| 0x010000c8 | 22       | 0.93%   |
| 0x0a201009 | 21       | 0.89%   |
| 0x08108109 | 20       | 0.85%   |
| 0x0a201016 | 19       | 0.81%   |
| 0x08001137 | 19       | 0.81%   |
| 0x206d7    | 18       | 0.76%   |
| 0x06003106 | 13       | 0.55%   |
| 0xa0655    | 12       | 0.51%   |
| 0x106e5    | 12       | 0.51%   |
| 0x08101016 | 12       | 0.51%   |
| 0x06001119 | 12       | 0.51%   |
| 0x906ed    | 9        | 0.38%   |
| 0x08001129 | 9        | 0.38%   |
| 0xa0653    | 8        | 0.34%   |
| 0x906ec    | 8        | 0.34%   |
| 0x906eb    | 8        | 0.34%   |
| 0x90672    | 8        | 0.34%   |
| 0x6fd      | 8        | 0.34%   |
| 0x0a50000c | 8        | 0.34%   |
| 0x08600106 | 8        | 0.34%   |
| 0x10676    | 7        | 0.3%    |
| 0x0a20120a | 7        | 0.3%    |
| 0x010000dc | 7        | 0.3%    |
| 0xa0671    | 6        | 0.25%   |
| 0x206c2    | 6        | 0.25%   |
| 0x0a50000d | 6        | 0.25%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 331      | 14.52%  |
| Haswell          | 242      | 10.62%  |
| KabyLake         | 230      | 10.09%  |
| Zen+             | 222      | 9.74%   |
| Zen              | 154      | 6.76%   |
| SandyBridge      | 148      | 6.49%   |
| IvyBridge        | 141      | 6.19%   |
| Zen 3            | 119      | 5.22%   |
| Piledriver       | 111      | 4.87%   |
| Skylake          | 104      | 4.56%   |
| Penryn           | 85       | 3.73%   |
| K10              | 78       | 3.42%   |
| CometLake        | 51       | 2.24%   |
| Core             | 34       | 1.49%   |
| Nehalem          | 32       | 1.4%    |
| Unknown          | 32       | 1.4%    |
| Westmere         | 28       | 1.23%   |
| Steamroller      | 22       | 0.97%   |
| Bulldozer        | 17       | 0.75%   |
| Broadwell        | 15       | 0.66%   |
| K8 Hammer        | 14       | 0.61%   |
| Excavator        | 8        | 0.35%   |
| Alderlake Hybrid | 8        | 0.35%   |
| Goldmont plus    | 7        | 0.31%   |
| Bonnell          | 7        | 0.31%   |
| Silvermont       | 6        | 0.26%   |
| NetBurst         | 6        | 0.26%   |
| Goldmont         | 6        | 0.26%   |
| K10 Llano        | 5        | 0.22%   |
| Jaguar           | 4        | 0.18%   |
| Icelake          | 4        | 0.18%   |
| Bobcat           | 4        | 0.18%   |
| Puma             | 2        | 0.09%   |
| Tremont          | 1        | 0.04%   |
| TigerLake        | 1        | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 1153     | 47.2%   |
| AMD                        | 865      | 35.41%  |
| Intel                      | 423      | 17.31%  |
| Matrox Electronics Systems | 1        | 0.04%   |
| ATI Technologies           | 1        | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 222      | 8.84%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 88       | 3.51%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 80       | 3.19%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 77       | 3.07%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 77       | 3.07%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 60       | 2.39%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 52       | 2.07%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 51       | 2.03%   |
| Nvidia GK208B [GeForce GT 710]                                              | 47       | 1.87%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 46       | 1.83%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 41       | 1.63%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 39       | 1.55%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 37       | 1.47%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 36       | 1.43%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 33       | 1.31%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 33       | 1.31%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 31       | 1.24%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 31       | 1.24%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 29       | 1.16%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 28       | 1.12%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 27       | 1.08%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 26       | 1.04%   |
| Intel HD Graphics 530                                                       | 26       | 1.04%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 25       | 1%      |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 24       | 0.96%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 23       | 0.92%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 23       | 0.92%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 22       | 0.88%   |
| Intel HD Graphics 630                                                       | 21       | 0.84%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 21       | 0.84%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 19       | 0.76%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 19       | 0.76%   |
| Nvidia GK208B [GeForce GT 730]                                              | 19       | 0.76%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 19       | 0.76%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 18       | 0.72%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 18       | 0.72%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 18       | 0.72%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 17       | 0.68%   |
| Nvidia GF119 [GeForce GT 610]                                               | 17       | 0.68%   |
| Nvidia GT218 [GeForce 210]                                                  | 16       | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| 1 x Nvidia         | 1058     | 45.86%  |
| 1 x AMD            | 794      | 34.42%  |
| 1 x Intel          | 315      | 13.65%  |
| Intel + Nvidia     | 37       | 1.6%    |
| AMD + Nvidia       | 35       | 1.52%   |
| 2 x AMD            | 30       | 1.3%    |
| 2 x Nvidia         | 24       | 1.04%   |
| Intel + AMD        | 11       | 0.48%   |
| 1 x Matrox         | 1        | 0.04%   |
| Intel + 2 x Nvidia | 1        | 0.04%   |
| Intel + 2 x AMD    | 1        | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1352     | 58.76%  |
| Proprietary | 939      | 40.81%  |
| Unknown     | 10       | 0.43%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 915      | 39.1%   |
| 7.01-8.0   | 364      | 15.56%  |
| 1.01-2.0   | 297      | 12.69%  |
| 3.01-4.0   | 245      | 10.47%  |
| 5.01-6.0   | 168      | 7.18%   |
| 0.51-1.0   | 138      | 5.9%    |
| 8.01-16.0  | 84       | 3.59%   |
| 0.01-0.5   | 78       | 3.33%   |
| 2.01-3.0   | 40       | 1.71%   |
| 16.01-24.0 | 9        | 0.38%   |
| 4.01-5.0   | 2        | 0.09%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 422      | 15.43%  |
| Goldstar             | 308      | 11.26%  |
| Dell                 | 257      | 9.4%    |
| Acer                 | 222      | 8.12%   |
| AOC                  | 168      | 6.14%   |
| BenQ                 | 167      | 6.11%   |
| Ancor Communications | 167      | 6.11%   |
| Hewlett-Packard      | 123      | 4.5%    |
| Philips              | 116      | 4.24%   |
| LG Electronics       | 90       | 3.29%   |
| ViewSonic            | 62       | 2.27%   |
| ASUSTek Computer     | 58       | 2.12%   |
| Lenovo               | 42       | 1.54%   |
| Unknown              | 38       | 1.39%   |
| Iiyama               | 38       | 1.39%   |
| Sony                 | 24       | 0.88%   |
| Vizio                | 21       | 0.77%   |
| AUS                  | 17       | 0.62%   |
| Unknown              | 17       | 0.62%   |
| MSI                  | 16       | 0.59%   |
| Eizo                 | 15       | 0.55%   |
| NEC Computers        | 14       | 0.51%   |
| Fujitsu Siemens      | 14       | 0.51%   |
| Sceptre Tech         | 12       | 0.44%   |
| Medion               | 12       | 0.44%   |
| Idek Iiyama          | 11       | 0.4%    |
| Gigabyte Technology  | 9        | 0.33%   |
| Vestel Elektronik    | 8        | 0.29%   |
| Sharp                | 8        | 0.29%   |
| Microstep            | 8        | 0.29%   |
| Panasonic            | 7        | 0.26%   |
| HannStar             | 7        | 0.26%   |
| Toshiba              | 6        | 0.22%   |
| Pixio                | 6        | 0.22%   |
| Apple                | 6        | 0.22%   |
| Vestel               | 5        | 0.18%   |
| Plain Tree Systems   | 5        | 0.18%   |
| Packard Bell         | 5        | 0.18%   |
| KTC                  | 5        | 0.18%   |
| HPN                  | 5        | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch              | 18       | 0.6%    |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 17       | 0.57%   |
| Unknown                                                               | 17       | 0.57%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 16       | 0.54%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 12       | 0.4%    |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 10       | 0.34%   |
| AOC 27V2G5 AOC2702 1920x1080 598x336mm 27.0-inch                      | 10       | 0.34%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 9        | 0.3%    |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                    | 9        | 0.3%    |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 890x500mm 40.2-inch  | 8        | 0.27%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 8        | 0.27%   |
| Goldstar HDR WFHD GSM7715 2560x1080 798x334mm 34.1-inch               | 8        | 0.27%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                     | 8        | 0.27%   |
| AOC 2460G5 AOC2460 1920x1080 531x299mm 24.0-inch                      | 8        | 0.27%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch     | 7        | 0.23%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 7        | 0.23%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 7        | 0.23%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 7        | 0.23%   |
| BenQ GW2270 BNQ78DB 1920x1080 480x270mm 21.7-inch                     | 7        | 0.23%   |
| Ancor Communications VE247 ACI2493 1920x1080 530x300mm 24.0-inch      | 7        | 0.23%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                       | 6        | 0.2%    |
| Goldstar E2350 GSM5791 1920x1080 510x290mm 23.1-inch                  | 6        | 0.2%    |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch                | 6        | 0.2%    |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                     | 6        | 0.2%    |
| ASUSTek Computer VA326 AUS32FA 1920x1080 698x393mm 31.5-inch          | 6        | 0.2%    |
| AOC 27B1 AOC2701 1920x1080 598x336mm 27.0-inch                        | 6        | 0.2%    |
| AOC 24B1W AOC2401 1920x1080 521x293mm 23.5-inch                       | 6        | 0.2%    |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                        | 6        | 0.2%    |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch      | 6        | 0.2%    |
| Ancor Communications VG248 ACI24A4 1920x1080 531x299mm 24.0-inch      | 6        | 0.2%    |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch | 6        | 0.2%    |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 6        | 0.2%    |
| Ancor Communications ASUS MG279 ACI27A7 2560x1440 597x336mm 27.0-inch | 6        | 0.2%    |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch  | 5        | 0.17%   |
| Samsung Electronics LCD Monitor SyncMaster                            | 5        | 0.17%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                     | 5        | 0.17%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch              | 5        | 0.17%   |
| Goldstar MP59G GSM5B35 1920x1080 480x270mm 21.7-inch                  | 5        | 0.17%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 5        | 0.17%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                | 5        | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 1173     | 44.08%  |
| 3840x2160 (4K)     | 249      | 9.36%   |
| 2560x1440 (QHD)    | 243      | 9.13%   |
| Unknown            | 144      | 5.41%   |
| 1680x1050 (WSXGA+) | 112      | 4.21%   |
| 1280x1024 (SXGA)   | 105      | 3.95%   |
| 1920x1200 (WUXGA)  | 73       | 2.74%   |
| 1366x768 (WXGA)    | 72       | 2.71%   |
| 3440x1440          | 69       | 2.59%   |
| 1440x900 (WXGA+)   | 65       | 2.44%   |
| 3840x1080          | 64       | 2.41%   |
| 2560x1080          | 61       | 2.29%   |
| 1600x900 (HD+)     | 54       | 2.03%   |
| 1360x768           | 24       | 0.9%    |
| 4480x1440          | 10       | 0.38%   |
| 5120x1440          | 9        | 0.34%   |
| 1920x540           | 9        | 0.34%   |
| 1280x720 (HD)      | 9        | 0.34%   |
| 1024x768 (XGA)     | 9        | 0.34%   |
| 5760x1080          | 8        | 0.3%    |
| 5760x2160          | 6        | 0.23%   |
| 3600x1080          | 6        | 0.23%   |
| 2560x1600          | 6        | 0.23%   |
| 3840x1600          | 5        | 0.19%   |
| 3200x1080          | 5        | 0.19%   |
| 6400x2160          | 4        | 0.15%   |
| 3840x1200          | 4        | 0.15%   |
| 3520x1080          | 4        | 0.15%   |
| 3360x1080          | 3        | 0.11%   |
| 3286x1080          | 3        | 0.11%   |
| 1600x1200          | 3        | 0.11%   |
| 7680x2160          | 2        | 0.08%   |
| 5504x1440          | 2        | 0.08%   |
| 5120x1080          | 2        | 0.08%   |
| 4480x1080          | 2        | 0.08%   |
| 4240x1440          | 2        | 0.08%   |
| 3360x1050          | 2        | 0.08%   |
| 2880x900           | 2        | 0.08%   |
| 2720x1024          | 2        | 0.08%   |
| 2160x1200          | 2        | 0.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 439      | 16.64%  |
| 24      | 387      | 14.67%  |
| 27      | 382      | 14.48%  |
| 23      | 315      | 11.94%  |
| 21      | 270      | 10.24%  |
| 19      | 119      | 4.51%   |
| 34      | 103      | 3.9%    |
| 31      | 102      | 3.87%   |
| 22      | 76       | 2.88%   |
| 18      | 67       | 2.54%   |
| 20      | 60       | 2.27%   |
| 17      | 41       | 1.55%   |
| 84      | 34       | 1.29%   |
| 72      | 21       | 0.8%    |
| 32      | 20       | 0.76%   |
| 25      | 20       | 0.76%   |
| 54      | 19       | 0.72%   |
| 15      | 15       | 0.57%   |
| 48      | 11       | 0.42%   |
| 49      | 10       | 0.38%   |
| 65      | 9        | 0.34%   |
| 40      | 9        | 0.34%   |
| 28      | 9        | 0.34%   |
| 43      | 8        | 0.3%    |
| 46      | 7        | 0.27%   |
| 37      | 7        | 0.27%   |
| 33      | 7        | 0.27%   |
| 26      | 6        | 0.23%   |
| 14      | 6        | 0.23%   |
| 39      | 5        | 0.19%   |
| 35      | 5        | 0.19%   |
| 12      | 5        | 0.19%   |
| 60      | 4        | 0.15%   |
| 47      | 4        | 0.15%   |
| 42      | 4        | 0.15%   |
| 36      | 4        | 0.15%   |
| 29      | 4        | 0.15%   |
| 64      | 3        | 0.11%   |
| 38      | 3        | 0.11%   |
| 16      | 3        | 0.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 965      | 38.39%  |
| 401-500     | 512      | 20.37%  |
| Unknown     | 439      | 17.46%  |
| 601-700     | 149      | 5.93%   |
| 701-800     | 134      | 5.33%   |
| 351-400     | 76       | 3.02%   |
| 1001-1500   | 69       | 2.74%   |
| 1501-2000   | 59       | 2.35%   |
| 301-350     | 54       | 2.15%   |
| 801-900     | 31       | 1.23%   |
| 201-300     | 14       | 0.56%   |
| 901-1000    | 12       | 0.48%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 1456     | 61.02%  |
| Unknown | 409      | 17.14%  |
| 16/10   | 238      | 9.97%   |
| 21/9    | 112      | 4.69%   |
| 5/4     | 100      | 4.19%   |
| 4/3     | 28       | 1.17%   |
| 3/2     | 18       | 0.75%   |
| 32/9    | 15       | 0.63%   |
| 6/5     | 5        | 0.21%   |
| 3.20    | 1        | 0.04%   |
| 1.96    | 1        | 0.04%   |
| 1.03    | 1        | 0.04%   |
| 0.80    | 1        | 0.04%   |
| 0.56    | 1        | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 840      | 32.51%  |
| Unknown        | 439      | 16.99%  |
| 301-350        | 384      | 14.86%  |
| 351-500        | 247      | 9.56%   |
| 151-200        | 242      | 9.37%   |
| 251-300        | 138      | 5.34%   |
| More than 1000 | 106      | 4.1%    |
| 141-150        | 86       | 3.33%   |
| 501-1000       | 65       | 2.52%   |
| 101-110        | 18       | 0.7%    |
| 131-140        | 6        | 0.23%   |
| 71-80          | 5        | 0.19%   |
| 81-90          | 2        | 0.08%   |
| 51-60          | 2        | 0.08%   |
| 91-100         | 2        | 0.08%   |
| 121-130        | 1        | 0.04%   |
| 111-120        | 1        | 0.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 1325     | 54.02%  |
| 101-120 | 464      | 18.92%  |
| Unknown | 439      | 17.9%   |
| 1-50    | 84       | 3.42%   |
| 121-160 | 84       | 3.42%   |
| 161-240 | 57       | 2.32%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1680     | 72.26%  |
| 2     | 532      | 22.88%  |
| 3     | 76       | 3.27%   |
| 0     | 32       | 1.38%   |
| 4     | 5        | 0.22%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 1388     | 42.72%  |
| Intel                                  | 1022     | 31.46%  |
| Qualcomm Atheros                       | 173      | 5.32%   |
| Broadcom                               | 89       | 2.74%   |
| Ralink Technology                      | 85       | 2.62%   |
| TP-Link                                | 76       | 2.34%   |
| Microsoft                              | 44       | 1.35%   |
| Nvidia                                 | 30       | 0.92%   |
| Aquantia                               | 28       | 0.86%   |
| Ralink                                 | 25       | 0.77%   |
| Qualcomm Atheros Communications        | 23       | 0.71%   |
| MediaTek                               | 19       | 0.58%   |
| Xiaomi                                 | 18       | 0.55%   |
| ASUSTek Computer                       | 17       | 0.52%   |
| Samsung Electronics                    | 16       | 0.49%   |
| Marvell Technology Group               | 15       | 0.46%   |
| D-Link                                 | 14       | 0.43%   |
| NetGear                                | 13       | 0.4%    |
| Linksys                                | 12       | 0.37%   |
| Huawei Technologies                    | 12       | 0.37%   |
| Broadcom Limited                       | 12       | 0.37%   |
| D-Link System                          | 8        | 0.25%   |
| Microchip Technology                   | 7        | 0.22%   |
| Edimax Technology                      | 7        | 0.22%   |
| Mellanox Technologies                  | 6        | 0.18%   |
| Motorola PCS                           | 5        | 0.15%   |
| ASIX Electronics                       | 5        | 0.15%   |
| ZyXEL Communications                   | 4        | 0.12%   |
| InterBiometrics                        | 4        | 0.12%   |
| T & A Mobile Phones                    | 3        | 0.09%   |
| Sony Ericsson Mobile Communications AB | 3        | 0.09%   |
| SEGGER                                 | 3        | 0.09%   |
| Qualcomm                               | 3        | 0.09%   |
| OPPO Electronics                       | 3        | 0.09%   |
| OnePlus Technology (Shenzhen)          | 3        | 0.09%   |
| JMicron Technology                     | 3        | 0.09%   |
| IMC Networks                           | 3        | 0.09%   |
| Google                                 | 3        | 0.09%   |
| Belkin Components                      | 3        | 0.09%   |
| ZyDAS                                  | 2        | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1145     | 30.68%  |
| Intel I211 Gigabit Network Connection                             | 264      | 7.07%   |
| Intel Wi-Fi 6 AX200                                               | 174      | 4.66%   |
| Realtek RTL8125 2.5GbE Controller                                 | 122      | 3.27%   |
| Intel Ethernet Connection (2) I219-V                              | 115      | 3.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 69       | 1.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 63       | 1.69%   |
| Intel Ethernet Controller I225-V                                  | 61       | 1.63%   |
| Intel Ethernet Connection (7) I219-V                              | 51       | 1.37%   |
| Intel 82579V Gigabit Network Connection                           | 47       | 1.26%   |
| Intel Wireless-AC 9260                                            | 45       | 1.21%   |
| Intel Ethernet Connection (2) I218-V                              | 41       | 1.1%    |
| Intel Ethernet Connection I217-V                                  | 34       | 0.91%   |
| Intel Ethernet Connection I217-LM                                 | 34       | 0.91%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 29       | 0.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 29       | 0.78%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 28       | 0.75%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 28       | 0.75%   |
| Ralink MT7601U Wireless Adapter                                   | 27       | 0.72%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 26       | 0.7%    |
| Microsoft Xbox 360 Wireless Adapter                               | 25       | 0.67%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 23       | 0.62%   |
| Qualcomm Atheros AR9271 802.11n                                   | 23       | 0.62%   |
| Realtek 802.11ac NIC                                              | 22       | 0.59%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 22       | 0.59%   |
| Intel Wireless 7265                                               | 22       | 0.59%   |
| Intel 82574L Gigabit Network Connection                           | 20       | 0.54%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 19       | 0.51%   |
| Nvidia MCP61 Ethernet                                             | 19       | 0.51%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 19       | 0.51%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 18       | 0.48%   |
| Intel Wireless 8265 / 8275                                        | 18       | 0.48%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 16       | 0.43%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 16       | 0.43%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 16       | 0.43%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 16       | 0.43%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 15       | 0.4%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 15       | 0.4%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 15       | 0.4%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 15       | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 423      | 36.47%  |
| Realtek Semiconductor                 | 225      | 19.4%   |
| Qualcomm Atheros                      | 89       | 7.67%   |
| Ralink Technology                     | 85       | 7.33%   |
| TP-Link                               | 75       | 6.47%   |
| Broadcom                              | 56       | 4.83%   |
| Microsoft                             | 44       | 3.79%   |
| Ralink                                | 25       | 2.16%   |
| Qualcomm Atheros Communications       | 23       | 1.98%   |
| ASUSTek Computer                      | 17       | 1.47%   |
| MediaTek                              | 15       | 1.29%   |
| D-Link                                | 14       | 1.21%   |
| NetGear                               | 13       | 1.12%   |
| Linksys                               | 12       | 1.03%   |
| Edimax Technology                     | 7        | 0.6%    |
| D-Link System                         | 5        | 0.43%   |
| Broadcom Limited                      | 5        | 0.43%   |
| ZyXEL Communications                  | 4        | 0.34%   |
| IMC Networks                          | 3        | 0.26%   |
| Belkin Components                     | 3        | 0.26%   |
| ZyDAS                                 | 2        | 0.17%   |
| Tenda                                 | 2        | 0.17%   |
| Mercucys                              | 2        | 0.17%   |
| AVM                                   | 2        | 0.17%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2        | 0.17%   |
| Xiaomi                                | 1        | 0.09%   |
| Wacom                                 | 1        | 0.09%   |
| Senao                                 | 1        | 0.09%   |
| Philips (or NXP)                      | 1        | 0.09%   |
| Marvell Technology Group              | 1        | 0.09%   |
| Fujitsu Siemens Computers             | 1        | 0.09%   |
| Encore Electronics                    | 1        | 0.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 174      | 14.86%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 63       | 5.38%   |
| Intel Wireless-AC 9260                                         | 45       | 3.84%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 29       | 2.48%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 28       | 2.39%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 28       | 2.39%   |
| Ralink MT7601U Wireless Adapter                                | 27       | 2.31%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 26       | 2.22%   |
| Microsoft Xbox 360 Wireless Adapter                            | 25       | 2.13%   |
| Qualcomm Atheros AR9271 802.11n                                | 23       | 1.96%   |
| Realtek 802.11ac NIC                                           | 22       | 1.88%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 22       | 1.88%   |
| Intel Wireless 7265                                            | 22       | 1.88%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 19       | 1.62%   |
| Intel Wireless 8265 / 8275                                     | 18       | 1.54%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 16       | 1.37%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 16       | 1.37%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 15       | 1.28%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 15       | 1.28%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 15       | 1.28%   |
| Ralink RT5370 Wireless Adapter                                 | 14       | 1.2%    |
| Microsoft XBOX ACC                                             | 13       | 1.11%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 12       | 1.02%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 12       | 1.02%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 12       | 1.02%   |
| Realtek 802.11n WLAN Adapter                                   | 12       | 1.02%   |
| Intel Wireless 3165                                            | 12       | 1.02%   |
| Intel Wireless 7260                                            | 11       | 0.94%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 10       | 0.85%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 9        | 0.77%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 9        | 0.77%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 9        | 0.77%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 9        | 0.77%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 9        | 0.77%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 8        | 0.68%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 8        | 0.68%   |
| TP-Link 802.11ac NIC                                           | 8        | 0.68%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 8        | 0.68%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 8        | 0.68%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 8        | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 1312     | 53.75%  |
| Intel                                  | 822      | 33.67%  |
| Qualcomm Atheros                       | 98       | 4.01%   |
| Broadcom                               | 35       | 1.43%   |
| Nvidia                                 | 30       | 1.23%   |
| Aquantia                               | 28       | 1.15%   |
| Xiaomi                                 | 17       | 0.7%    |
| Samsung Electronics                    | 16       | 0.66%   |
| Marvell Technology Group               | 14       | 0.57%   |
| Huawei Technologies                    | 10       | 0.41%   |
| Broadcom Limited                       | 7        | 0.29%   |
| Mellanox Technologies                  | 6        | 0.25%   |
| ASIX Electronics                       | 5        | 0.2%    |
| Sony Ericsson Mobile Communications AB | 3        | 0.12%   |
| OPPO Electronics                       | 3        | 0.12%   |
| MediaTek                               | 3        | 0.12%   |
| JMicron Technology                     | 3        | 0.12%   |
| Google                                 | 3        | 0.12%   |
| D-Link System                          | 3        | 0.12%   |
| T & A Mobile Phones                    | 2        | 0.08%   |
| Qualcomm                               | 2        | 0.08%   |
| OnePlus Technology (Shenzhen)          | 2        | 0.08%   |
| National Semiconductor                 | 2        | 0.08%   |
| Motorola PCS                           | 2        | 0.08%   |
| HMD Global                             | 2        | 0.08%   |
| ZTE WCDMA Technologies MSM             | 1        | 0.04%   |
| VIA Technologies                       | 1        | 0.04%   |
| TP-Link                                | 1        | 0.04%   |
| Sundance Technology Inc / IC Plus      | 1        | 0.04%   |
| Silicon Integrated Systems [SiS]       | 1        | 0.04%   |
| NetXen Incorporated                    | 1        | 0.04%   |
| LG Electronics                         | 1        | 0.04%   |
| Foxconn / Hon Hai                      | 1        | 0.04%   |
| DisplayLink                            | 1        | 0.04%   |
| Apple                                  | 1        | 0.04%   |
| Accton Technology                      | 1        | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1145     | 45.35%  |
| Intel I211 Gigabit Network Connection                             | 264      | 10.46%  |
| Realtek RTL8125 2.5GbE Controller                                 | 122      | 4.83%   |
| Intel Ethernet Connection (2) I219-V                              | 115      | 4.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 69       | 2.73%   |
| Intel Ethernet Controller I225-V                                  | 61       | 2.42%   |
| Intel Ethernet Connection (7) I219-V                              | 51       | 2.02%   |
| Intel 82579V Gigabit Network Connection                           | 47       | 1.86%   |
| Intel Ethernet Connection (2) I218-V                              | 41       | 1.62%   |
| Intel Ethernet Connection I217-V                                  | 34       | 1.35%   |
| Intel Ethernet Connection I217-LM                                 | 34       | 1.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 29       | 1.15%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 23       | 0.91%   |
| Intel 82574L Gigabit Network Connection                           | 20       | 0.79%   |
| Nvidia MCP61 Ethernet                                             | 19       | 0.75%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 19       | 0.75%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 18       | 0.71%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 16       | 0.63%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 16       | 0.63%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 15       | 0.59%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 14       | 0.55%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 14       | 0.55%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 13       | 0.51%   |
| Intel Ethernet Connection (2) I219-LM                             | 12       | 0.48%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 11       | 0.44%   |
| Intel I210 Gigabit Network Connection                             | 10       | 0.4%    |
| Intel Ethernet Connection (11) I219-V                             | 10       | 0.4%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 9        | 0.36%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 8        | 0.32%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 8        | 0.32%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 8        | 0.32%   |
| Intel Ethernet Connection (7) I219-LM                             | 8        | 0.32%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 8        | 0.32%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 6        | 0.24%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 6        | 0.24%   |
| Intel Ethernet Connection (2) I218-LM                             | 6        | 0.24%   |
| Intel 82578DC Gigabit Network Connection                          | 6        | 0.24%   |
| Huawei STK-L21                                                    | 6        | 0.24%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 6        | 0.24%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 5        | 0.2%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2247     | 67.11%  |
| WiFi     | 1067     | 31.87%  |
| Modem    | 27       | 0.81%   |
| Unknown  | 7        | 0.21%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1806     | 76.36%  |
| WiFi     | 559      | 23.64%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1456     | 63.5%   |
| 2     | 704      | 30.7%   |
| 3     | 101      | 4.4%    |
| 0     | 18       | 0.78%   |
| 4     | 7        | 0.31%   |
| 5     | 5        | 0.22%   |
| 8     | 1        | 0.04%   |
| 7     | 1        | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1944     | 83.97%  |
| Yes  | 371      | 16.03%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 397      | 41.44%  |
| Cambridge Silicon Radio         | 269      | 28.08%  |
| ASUSTek Computer                | 88       | 9.19%   |
| Realtek Semiconductor           | 60       | 6.26%   |
| Broadcom                        | 51       | 5.32%   |
| Qualcomm Atheros Communications | 15       | 1.57%   |
| IMC Networks                    | 11       | 1.15%   |
| Apple                           | 11       | 1.15%   |
| MediaTek                        | 6        | 0.63%   |
| Dynex                           | 6        | 0.63%   |
| TP-Link                         | 5        | 0.52%   |
| HTC (High Tech Computer)        | 5        | 0.52%   |
| Foxconn / Hon Hai               | 5        | 0.52%   |
| Edimax Technology               | 5        | 0.52%   |
| Lite-On Technology              | 4        | 0.42%   |
| Conwise Technology              | 4        | 0.42%   |
| SINO WEALTH                     | 3        | 0.31%   |
| Integrated System Solution      | 3        | 0.31%   |
| Belkin Components               | 3        | 0.31%   |
| Realtek                         | 2        | 0.21%   |
| Ralink                          | 2        | 0.21%   |
| Sitecom Europe                  | 1        | 0.1%    |
| Micro Star International        | 1        | 0.1%    |
| D-Link                          | 1        | 0.1%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 269      | 27.99%  |
| Intel AX200 Bluetooth                                                | 160      | 16.65%  |
| Intel Bluetooth wireless interface                                   | 69       | 7.18%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 62       | 6.45%   |
| Realtek Bluetooth Radio                                              | 48       | 4.99%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 45       | 4.68%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 38       | 3.95%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 34       | 3.54%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 29       | 3.02%   |
| Intel AX201 Bluetooth                                                | 16       | 1.66%   |
| Intel AX210 Bluetooth                                                | 14       | 1.46%   |
| ASUS Bluetooth Radio                                                 | 13       | 1.35%   |
| ASUS Bluetooth Adapter                                               | 13       | 1.35%   |
| ASUS Bluetooth Device                                                | 11       | 1.14%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 9        | 0.94%   |
| ASUS BCM20702A0                                                      | 9        | 0.94%   |
| IMC Networks Bluetooth Radio                                         | 7        | 0.73%   |
| Qualcomm Atheros  Bluetooth Device                                   | 6        | 0.62%   |
| MediaTek Wireless_Device                                             | 6        | 0.62%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]             | 6        | 0.62%   |
| TP-Link UB500 Adapter                                                | 5        | 0.52%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 5        | 0.52%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 5        | 0.52%   |
| Apple Bluetooth USB Host Controller                                  | 5        | 0.52%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 4        | 0.42%   |
| Conwise CW6622                                                       | 4        | 0.42%   |
| SINO WEALTH RK Bluetooth Keyboar                                     | 3        | 0.31%   |
| Edimax Bluetooth Adapter                                             | 3        | 0.31%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                | 3        | 0.31%   |
| Apple Bluetooth HCI MacBookPro (HID mode)                            | 3        | 0.31%   |
| Realtek Bluetooth 5.1 Radio                                          | 2        | 0.21%   |
| Realtek Bluetooth Radio                                              | 2        | 0.21%   |
| Ralink RT3290 Bluetooth                                              | 2        | 0.21%   |
| Qualcomm Atheros Bluetooth USB Host Controller                       | 2        | 0.21%   |
| Lite-On Bluetooth Device                                             | 2        | 0.21%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 2        | 0.21%   |
| Intel Bluetooth Device                                               | 2        | 0.21%   |
| Integrated System Solution Bluetooth Device                          | 2        | 0.21%   |
| IMC Networks BCM20702A0                                              | 2        | 0.21%   |
| Foxconn / Hon Hai Wireless_Device                                    | 2        | 0.21%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD                                             | 1292     | 29.23%  |
| Intel                                           | 1135     | 25.68%  |
| Nvidia                                          | 1101     | 24.91%  |
| C-Media Electronics                             | 162      | 3.67%   |
| Creative Labs                                   | 66       | 1.49%   |
| Logitech                                        | 63       | 1.43%   |
| Kingston Technology                             | 43       | 0.97%   |
| JMTek                                           | 36       | 0.81%   |
| Texas Instruments                               | 32       | 0.72%   |
| Corsair                                         | 32       | 0.72%   |
| SteelSeries ApS                                 | 28       | 0.63%   |
| Focusrite-Novation                              | 26       | 0.59%   |
| Creative Technology                             | 26       | 0.59%   |
| Blue Microphones                                | 25       | 0.57%   |
| Razer USA                                       | 22       | 0.5%    |
| ASUSTek Computer                                | 22       | 0.5%    |
| Generalplus Technology                          | 20       | 0.45%   |
| BEHRINGER International                         | 19       | 0.43%   |
| Plantronics                                     | 14       | 0.32%   |
| Sony                                            | 13       | 0.29%   |
| Realtek Semiconductor                           | 11       | 0.25%   |
| GYROCOM C&C                                     | 11       | 0.25%   |
| VIA Technologies                                | 9        | 0.2%    |
| M-Audio                                         | 9        | 0.2%    |
| Turtle Beach                                    | 7        | 0.16%   |
| SAVITECH                                        | 7        | 0.16%   |
| Samson Technologies                             | 7        | 0.16%   |
| RODE Microphones                                | 7        | 0.16%   |
| Giga-Byte Technology                            | 7        | 0.16%   |
| Yamaha                                          | 6        | 0.14%   |
| GN Netcom                                       | 6        | 0.14%   |
| XMOS                                            | 5        | 0.11%   |
| Valve Software                                  | 5        | 0.11%   |
| Micro Star International                        | 5        | 0.11%   |
| Elgato Systems                                  | 5        | 0.11%   |
| Dell                                            | 5        | 0.11%   |
| Thesycon Systemsoftware & Consulting            | 4        | 0.09%   |
| Sennheiser Communications                       | 4        | 0.09%   |
| Licensed by Sony Computer Entertainment America | 4        | 0.09%   |
| KTMicro                                         | 4        | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 391      | 7.57%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 284      | 5.5%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 222      | 4.3%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 154      | 2.98%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 152      | 2.94%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 142      | 2.75%   |
| AMD Family 17h/19h HD Audio Controller                                     | 131      | 2.54%   |
| Intel 200 Series PCH HD Audio                                              | 123      | 2.38%   |
| Nvidia GP104 High Definition Audio Controller                              | 120      | 2.32%   |
| Nvidia GP106 High Definition Audio Controller                              | 113      | 2.19%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 105      | 2.03%   |
| AMD Navi 10 HDMI Audio                                                     | 103      | 1.99%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 101      | 1.96%   |
| Nvidia GP107GL High Definition Audio Controller                            | 99       | 1.92%   |
| Intel Cannon Lake PCH cAVS                                                 | 90       | 1.74%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 83       | 1.61%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 68       | 1.32%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 65       | 1.26%   |
| Nvidia TU116 High Definition Audio Controller                              | 63       | 1.22%   |
| AMD FCH Azalia Controller                                                  | 62       | 1.2%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 62       | 1.2%    |
| Nvidia GM204 High Definition Audio Controller                              | 61       | 1.18%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 57       | 1.1%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 56       | 1.08%   |
| Nvidia TU104 HD Audio Controller                                           | 55       | 1.07%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 53       | 1.03%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 51       | 0.99%   |
| Nvidia TU106 High Definition Audio Controller                              | 50       | 0.97%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 49       | 0.95%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 45       | 0.87%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 42       | 0.81%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 41       | 0.79%   |
| Nvidia GM206 High Definition Audio Controller                              | 40       | 0.77%   |
| Nvidia GP108 High Definition Audio Controller                              | 39       | 0.76%   |
| Nvidia GK104 HDMI Audio Controller                                         | 39       | 0.76%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 39       | 0.76%   |
| Nvidia GP102 HDMI Audio Controller                                         | 33       | 0.64%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 32       | 0.62%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 32       | 0.62%   |
| Nvidia GA104 High Definition Audio Controller                              | 31       | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Corsair                      | 285      | 18.8%   |
| Kingston                     | 271      | 17.88%  |
| G.Skill                      | 210      | 13.85%  |
| Unknown                      | 189      | 12.47%  |
| Crucial                      | 139      | 9.17%   |
| Samsung Electronics          | 87       | 5.74%   |
| SK hynix                     | 59       | 3.89%   |
| Micron Technology            | 45       | 2.97%   |
| Team                         | 39       | 2.57%   |
| A-DATA Technology            | 38       | 2.51%   |
| Patriot                      | 30       | 1.98%   |
| Nanya Technology             | 10       | 0.66%   |
| Unknown                      | 9        | 0.59%   |
| Goodram                      | 8        | 0.53%   |
| Unknown (ABCD)               | 7        | 0.46%   |
| Ramaxel Technology           | 6        | 0.4%    |
| Elpida                       | 6        | 0.4%    |
| Kllisre                      | 5        | 0.33%   |
| GeIL                         | 5        | 0.33%   |
| Transcend                    | 4        | 0.26%   |
| Smart                        | 4        | 0.26%   |
| Silicon Power                | 4        | 0.26%   |
| PNY                          | 4        | 0.26%   |
| AMD                          | 4        | 0.26%   |
| Kingmax                      | 3        | 0.2%    |
| CSX                          | 3        | 0.2%    |
| Apacer                       | 3        | 0.2%    |
| Unknown (08C8)               | 2        | 0.13%   |
| Qumo                         | 2        | 0.13%   |
| Patriot Memory               | 2        | 0.13%   |
| Neo Forza                    | 2        | 0.13%   |
| Wilk Elektronik              | 1        | 0.07%   |
| Unknown (AB)                 | 1        | 0.07%   |
| Unknown (0xAD44594E45540000) | 1        | 0.07%   |
| Unknown (0x8551)             | 1        | 0.07%   |
| Unknown (0x0416)             | 1        | 0.07%   |
| TwinMOS                      | 1        | 0.07%   |
| Thermaltake                  | 1        | 0.07%   |
| Super Talent                 | 1        | 0.07%   |
| SemsoTai                     | 1        | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s        | 39       | 2.33%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s        | 31       | 1.85%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s            | 20       | 1.19%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s          | 20       | 1.19%   |
| Kingston RAM KHX1600C10D3/8G 8192MB DIMM DDR3 1600MT/s       | 17       | 1.01%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s         | 15       | 0.89%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s          | 15       | 0.89%   |
| Kingston RAM KHX2400C15/8G 8192MB DIMM DDR4 3400MT/s         | 14       | 0.83%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s       | 14       | 0.83%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                         | 12       | 0.72%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s          | 11       | 0.66%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s         | 11       | 0.66%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                      | 10       | 0.6%    |
| Patriot RAM 3200 C16 Series 16GB DIMM DDR4 3200MT/s          | 10       | 0.6%    |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s          | 10       | 0.6%    |
| A-DATA RAM DDR4 3000 16384MB DIMM DDR4 3600MT/s              | 10       | 0.6%    |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s          | 9        | 0.54%   |
| Corsair RAM CMK16GX4M2D3000C16 8GB DIMM DDR4 3200MT/s        | 9        | 0.54%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s        | 9        | 0.54%   |
| Unknown                                                      | 9        | 0.54%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s           | 8        | 0.48%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s       | 8        | 0.48%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s          | 8        | 0.48%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s        | 8        | 0.48%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s          | 8        | 0.48%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                    | 7        | 0.42%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                      | 7        | 0.42%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 7        | 0.42%   |
| G.Skill RAM F4-3200C16-8GVGB 8GB DIMM DDR4 3200MT/s          | 7        | 0.42%   |
| G.Skill RAM F4-3200C16-8GTZR 8GB DIMM DDR4 3200MT/s          | 7        | 0.42%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                  | 6        | 0.36%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s        | 6        | 0.36%   |
| Kingston RAM KHX2666C15D4/4G 4GB DIMM DDR4 3200MT/s          | 6        | 0.36%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s          | 6        | 0.36%   |
| G.Skill RAM F4-3200C14-8GFX 8GB DIMM DDR4 3733MT/s           | 6        | 0.36%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s       | 6        | 0.36%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                       | 5        | 0.3%    |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s          | 5        | 0.3%    |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s          | 5        | 0.3%    |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s          | 5        | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 792      | 58.15%  |
| DDR3    | 386      | 28.34%  |
| Unknown | 77       | 5.65%   |
| DDR2    | 40       | 2.94%   |
| SDRAM   | 38       | 2.79%   |
| DDR     | 12       | 0.88%   |
| DDR5    | 8        | 0.59%   |
| LPDDR4  | 7        | 0.51%   |
| LPDDR3  | 1        | 0.07%   |
| DRAM    | 1        | 0.07%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 1313     | 97.55%  |
| SODIMM  | 29       | 2.15%   |
| FB-DIMM | 3        | 0.22%   |
| RIMM    | 1        | 0.07%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 659      | 44.68%  |
| 4096  | 308      | 20.88%  |
| 16384 | 263      | 17.83%  |
| 2048  | 138      | 9.36%   |
| 32768 | 62       | 4.2%    |
| 1024  | 40       | 2.71%   |
| 512   | 4        | 0.27%   |
| 3072  | 1        | 0.07%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 216      | 14.3%   |
| 3200    | 213      | 14.11%  |
| 3600    | 155      | 10.26%  |
| 1333    | 137      | 9.07%   |
| 2400    | 91       | 6.03%   |
| 2667    | 68       | 4.5%    |
| 2133    | 66       | 4.37%   |
| 3466    | 55       | 3.64%   |
| 1867    | 50       | 3.31%   |
| 3400    | 48       | 3.18%   |
| 3000    | 48       | 3.18%   |
| 800     | 43       | 2.85%   |
| 1866    | 29       | 1.92%   |
| 3800    | 27       | 1.79%   |
| 667     | 27       | 1.79%   |
| 3866    | 25       | 1.66%   |
| 3733    | 23       | 1.52%   |
| 2933    | 18       | 1.19%   |
| Unknown | 16       | 1.06%   |
| 2666    | 15       | 0.99%   |
| 1066    | 13       | 0.86%   |
| 2800    | 11       | 0.73%   |
| 1800    | 11       | 0.73%   |
| 4800    | 6        | 0.4%    |
| 3666    | 6        | 0.4%    |
| 3334    | 6        | 0.4%    |
| 1334    | 6        | 0.4%    |
| 1067    | 5        | 0.33%   |
| 333     | 5        | 0.33%   |
| 3500    | 4        | 0.26%   |
| 3100    | 4        | 0.26%   |
| 2448    | 4        | 0.26%   |
| 2048    | 4        | 0.26%   |
| 1648    | 4        | 0.26%   |
| 533     | 4        | 0.26%   |
| 400     | 4        | 0.26%   |
| 49926   | 3        | 0.2%    |
| 3151    | 3        | 0.2%    |
| 3066    | 3        | 0.2%    |
| 6000    | 2        | 0.13%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 39       | 41.49%  |
| Brother Industries    | 19       | 20.21%  |
| Canon                 | 10       | 10.64%  |
| Seiko Epson           | 6        | 6.38%   |
| Samsung Electronics   | 5        | 5.32%   |
| Pantum                | 3        | 3.19%   |
| Xerox                 | 2        | 2.13%   |
| Prolific Technology   | 2        | 2.13%   |
| Apple                 | 2        | 2.13%   |
| Ricoh                 | 1        | 1.06%   |
| QinHeng Electronics   | 1        | 1.06%   |
| Oki Data              | 1        | 1.06%   |
| Lexmark International | 1        | 1.06%   |
| Graphtec America      | 1        | 1.06%   |
| Dymo-CoStar           | 1        | 1.06%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| HP OfficeJet 5200 series                     | 3        | 3.16%   |
| HP LaserJet 1300                             | 3        | 3.16%   |
| Xerox Phaser 3020                            | 2        | 2.11%   |
| Seiko Epson L120 Series                      | 2        | 2.11%   |
| Prolific PL2305 Parallel Port                | 2        | 2.11%   |
| HP Officejet 2620 series                     | 2        | 2.11%   |
| HP DeskJet 2130 series                       | 2        | 2.11%   |
| HP Color LaserJet Pro M453-4                 | 2        | 2.11%   |
| Canon MG5700 series                          | 2        | 2.11%   |
| Brother HL-5370DW series                     | 2        | 2.11%   |
| Brother DCP-7040                             | 2        | 2.11%   |
| Apple Gamesir-G3s 2.15                       | 2        | 2.11%   |
| Seiko Epson Stylus NX230/SX235W Series       | 1        | 1.05%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1        | 1.05%   |
| Seiko Epson L805 Series                      | 1        | 1.05%   |
| Seiko Epson ET-4760 Series                   | 1        | 1.05%   |
| Seiko Epson ET-3850 Series                   | 1        | 1.05%   |
| Samsung ML-1660 Series                       | 1        | 1.05%   |
| Samsung ML-1640 Series Laser Printer         | 1        | 1.05%   |
| Samsung M2020 Series                         | 1        | 1.05%   |
| Samsung CLX-3300 Series                      | 1        | 1.05%   |
| Samsung CLP-310 Color Laser Printer          | 1        | 1.05%   |
| Ricoh SP 112SU                               | 1        | 1.05%   |
| QinHeng CH340S                               | 1        | 1.05%   |
| Pantum P2500W series                         | 1        | 1.05%   |
| Pantum P2200 series                          | 1        | 1.05%   |
| Pantum M6500 series                          | 1        | 1.05%   |
| Oki Data USB Device                          | 1        | 1.05%   |
| Lexmark International Lexmark MS312dn        | 1        | 1.05%   |
| HP Smart Install                             | 1        | 1.05%   |
| HP OfficeJet Pro 8020 series                 | 1        | 1.05%   |
| HP LaserJet P2015 series                     | 1        | 1.05%   |
| HP Laserjet P1505                            | 1        | 1.05%   |
| HP LaserJet P1005                            | 1        | 1.05%   |
| HP LaserJet 200 colorMFP M276nw              | 1        | 1.05%   |
| HP LaserJet 1020                             | 1        | 1.05%   |
| HP LaserJet 1018                             | 1        | 1.05%   |
| HP LaserJet 1012                             | 1        | 1.05%   |
| HP LaserJet 1010                             | 1        | 1.05%   |
| HP ENVY Photo 7100 series                    | 1        | 1.05%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Canon              | 11       | 50%     |
| Seiko Epson        | 5        | 22.73%  |
| Hewlett-Packard    | 2        | 9.09%   |
| Visioneer          | 1        | 4.55%   |
| Ultima Electronics | 1        | 4.55%   |
| Mustek Systems     | 1        | 4.55%   |
| AGFA-Gevaert NV    | 1        | 4.55%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 110                                                               | 4        | 18.18%  |
| Canon CanoScan LiDE 220                                                               | 3        | 13.64%  |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 2        | 9.09%   |
| Canon CanoScan LIDE 25                                                                | 2        | 9.09%   |
| Visioneer OneTouch 5300 USB                                                           | 1        | 4.55%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1        | 4.55%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 1        | 4.55%   |
| Seiko Epson GT-9700F [Perfection 2450 PHOTO]                                          | 1        | 4.55%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]                                     | 1        | 4.55%   |
| Mustek Systems ScanExpress A3 USB 1200 PRO                                            | 1        | 4.55%   |
| HP ScanJet 3500c                                                                      | 1        | 4.55%   |
| HP ScanJet 3400cse                                                                    | 1        | 4.55%   |
| Canon CanoScan LiDE 90                                                                | 1        | 4.55%   |
| Canon CanoScan LiDE 120                                                               | 1        | 4.55%   |
| AGFA-Gevaert NV SnapScan e26                                                          | 1        | 4.55%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 220      | 42.23%  |
| Microsoft                              | 45       | 8.64%   |
| Microdia                               | 39       | 7.49%   |
| Samsung Electronics                    | 19       | 3.65%   |
| Z-Star Microelectronics                | 17       | 3.26%   |
| Sunplus Innovation Technology          | 13       | 2.5%    |
| Creative Technology                    | 11       | 2.11%   |
| Apple                                  | 9        | 1.73%   |
| MacroSilicon                           | 7        | 1.34%   |
| GEMBIRD                                | 7        | 1.34%   |
| Cubeternet                             | 7        | 1.34%   |
| Realtek Semiconductor                  | 6        | 1.15%   |
| Google                                 | 6        | 1.15%   |
| Generalplus Technology                 | 6        | 1.15%   |
| Chicony Electronics                    | 6        | 1.15%   |
| ARC International                      | 6        | 1.15%   |
| Valve Software                         | 5        | 0.96%   |
| LG Electronics                         | 5        | 0.96%   |
| KYE Systems (Mouse Systems)            | 4        | 0.77%   |
| Genesys Logic                          | 4        | 0.77%   |
| Aveo Technology                        | 4        | 0.77%   |
| Alcor Micro                            | 4        | 0.77%   |
| Xiongmai                               | 3        | 0.58%   |
| Sonix Technology                       | 3        | 0.58%   |
| SHENZHEN EMEET TECHNOLOGY              | 3        | 0.58%   |
| Razer USA                              | 3        | 0.58%   |
| Pixart Imaging                         | 3        | 0.58%   |
| Jieli Technology                       | 3        | 0.58%   |
| Huawei Technologies                    | 3        | 0.58%   |
| HD 2MP WEBCAM                          | 3        | 0.58%   |
| Arkmicro Technologies                  | 3        | 0.58%   |
| WCM_USB                                | 2        | 0.38%   |
| WaveRider Communications               | 2        | 0.38%   |
| SJ-180517-N                            | 2        | 0.38%   |
| Silicon Motion                         | 2        | 0.38%   |
| Philips (or NXP)                       | 2        | 0.38%   |
| Elgato Systems                         | 2        | 0.38%   |
| Cheng Uei Precision Industry (Foxlink) | 2        | 0.38%   |
| AVerMedia Technologies                 | 2        | 0.38%   |
| Acer                                   | 2        | 0.38%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Logitech Webcam C270                                  | 55       | 10.52%  |
| Logitech HD Pro Webcam C920                           | 40       | 7.65%   |
| Microsoft LifeCam HD-3000                             | 20       | 3.82%   |
| Samsung Galaxy A5 (MTP)                               | 19       | 3.63%   |
| Logitech C922 Pro Stream Webcam                       | 17       | 3.25%   |
| Microdia Webcam Vitade AF                             | 13       | 2.49%   |
| Microdia USB 2.0 Camera                               | 13       | 2.49%   |
| Logitech Webcam C310                                  | 10       | 1.91%   |
| Z-Star Venus USB2.0 Camera                            | 9        | 1.72%   |
| Logitech HD Webcam C615                               | 8        | 1.53%   |
| MacroSilicon USB Video                                | 7        | 1.34%   |
| Logitech Webcam C930e                                 | 7        | 1.34%   |
| Logitech Webcam C170                                  | 7        | 1.34%   |
| Logitech HD Webcam C525                               | 7        | 1.34%   |
| Logitech BRIO Ultra HD Webcam                         | 7        | 1.34%   |
| Apple iPhone5/5C/5S/6                                 | 7        | 1.34%   |
| Sunplus SPCA2650 AV Camera                            | 6        | 1.15%   |
| Microsoft LifeCam VX-2000                             | 6        | 1.15%   |
| Logitech StreamCam                                    | 6        | 1.15%   |
| Valve Software 3D Camera                              | 5        | 0.96%   |
| Logitech Webcam Pro 9000                              | 5        | 0.96%   |
| Logitech HD Webcam C910                               | 5        | 0.96%   |
| Logitech C920 PRO HD Webcam                           | 5        | 0.96%   |
| ARC International Camera                              | 5        | 0.96%   |
| Sunplus Full HD webcam                                | 4        | 0.76%   |
| Logitech HD Webcam C510                               | 4        | 0.76%   |
| Logitech B525 HD Webcam                               | 4        | 0.76%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 4        | 0.76%   |
| Google Nexus/Pixel Device (MTP + debug)               | 4        | 0.76%   |
| GEMBIRD USB2.0 PC CAMERA                              | 4        | 0.76%   |
| Creative Live! Cam Chat HD [VF0700]                   | 4        | 0.76%   |
| Z-Star Vimicro USB Camera (Altair)                    | 3        | 0.57%   |
| Xiongmai web camera                                   | 3        | 0.57%   |
| SHENZHEN EMEET TECHNOLOGY HD Webcam eMeet C960        | 3        | 0.57%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro                  | 3        | 0.57%   |
| Microsoft MicrosoftÂ LifeCam Studio                  | 3        | 0.57%   |
| Microsoft LifeCam VX-800                              | 3        | 0.57%   |
| Microsoft LifeCam Studio                              | 3        | 0.57%   |
| Microsoft LifeCam HD-5000                             | 3        | 0.57%   |
| Microsoft LifeCam Cinema                              | 3        | 0.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Elan Microelectronics | 3        | 50%     |
| STMicroelectronics    | 1        | 16.67%  |
| Futronic Technology   | 1        | 16.67%  |
| AuthenTec             | 1        | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Elan fingerprint sensor [FeinTech FPS00200] | 3        | 50%     |
| STMicroelectronics Fingerprint Reader       | 1        | 16.67%  |
| Futronic FS81 Fingerprint Scanner Module    | 1        | 16.67%  |
| AuthenTec AES1600                           | 1        | 16.67%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Gemalto (was Gemplus)             | 5        | 23.81%  |
| Realtek Semiconductor             | 4        | 19.05%  |
| Alcor Micro                       | 4        | 19.05%  |
| VASCO Data Security International | 3        | 14.29%  |
| OmniKey                           | 2        | 9.52%   |
| SCM Microsystems                  | 1        | 4.76%   |
| Cherry                            | 1        | 4.76%   |
| BIT4ID                            | 1        | 4.76%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader               | 5        | 23.81%  |
| Realtek Semiconductor Smart Card Reader Interface               | 4        | 19.05%  |
| Alcor Micro AU9540 Smartcard Reader                             | 3        | 14.29%  |
| OmniKey 3x21 Smart Card Reader                                  | 2        | 9.52%   |
| VASCO Data Security International DIGIPASS 920                  | 1        | 4.76%   |
| VASCO Data Security International Digipass 905 SmartCard Reader | 1        | 4.76%   |
| VASCO Data Security International DIGIPASS 870                  | 1        | 4.76%   |
| SCM Microsystems SCR331 SmartCard Reader                        | 1        | 4.76%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                     | 1        | 4.76%   |
| BIT4ID miniLector EVO                                           | 1        | 4.76%   |
| Alcor Micro Watchdata W 1981                                    | 1        | 4.76%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 2000     | 86.36%  |
| 1     | 283      | 12.22%  |
| 2     | 30       | 1.3%    |
| 3     | 3        | 0.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 134      | 40.24%  |
| Unassigned class         | 45       | 13.51%  |
| Graphics card            | 42       | 12.61%  |
| Camera                   | 16       | 4.8%    |
| Chipcard                 | 14       | 4.2%    |
| Sound                    | 11       | 3.3%    |
| Net/ethernet             | 11       | 3.3%    |
| Multimedia controller    | 11       | 3.3%    |
| Communication controller | 11       | 3.3%    |
| Bluetooth                | 10       | 3%      |
| Dvb card                 | 9        | 2.7%    |
| Storage/raid             | 5        | 1.5%    |
| Fingerprint reader       | 5        | 1.5%    |
| Network                  | 4        | 1.2%    |
| Storage/ide              | 2        | 0.6%    |
| Video                    | 1        | 0.3%    |
| Storage/ata              | 1        | 0.3%    |
| Storage                  | 1        | 0.3%    |

